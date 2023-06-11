BSD in Canada - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in Canada.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Canada/Desktop/README.md) and [notebooks](/Location/Canada/Notebook/README.md).

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

Total: 698

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Desktop     | [88a421e275](https://bsd-hardware.info/?probe=88a421e275) | Jun 10, 2023 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [48833ba1a3](https://bsd-hardware.info/?probe=48833ba1a3) | Jun 08, 2023 |
| Protectli     | VP2420                      | Desktop     | [45e550e09f](https://bsd-hardware.info/?probe=45e550e09f) | Jun 07, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [0754642fe6](https://bsd-hardware.info/?probe=0754642fe6) | Jun 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f0f13f5cea](https://bsd-hardware.info/?probe=f0f13f5cea) | Jun 06, 2023 |
| Unknown       | Unknown                     | Firewall    | [f971e964cd](https://bsd-hardware.info/?probe=f971e964cd) | Jun 05, 2023 |
| HP            | 1495                        | Desktop     | [a7a24624d7](https://bsd-hardware.info/?probe=a7a24624d7) | Jun 05, 2023 |
| Supermicro    | X10SL7-F                    | Server      | [7dbcaa598b](https://bsd-hardware.info/?probe=7dbcaa598b) | Jun 04, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [5fc38b17d3](https://bsd-hardware.info/?probe=5fc38b17d3) | Jun 04, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5be94420c2](https://bsd-hardware.info/?probe=5be94420c2) | Jun 02, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [8cc6299ba9](https://bsd-hardware.info/?probe=8cc6299ba9) | May 31, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [ed0c6cf73c](https://bsd-hardware.info/?probe=ed0c6cf73c) | May 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [88e6cd10c6](https://bsd-hardware.info/?probe=88e6cd10c6) | May 27, 2023 |
| Protectli     | FW4B                        | Desktop     | [c5c9276f48](https://bsd-hardware.info/?probe=c5c9276f48) | May 27, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [7bcb7c96be](https://bsd-hardware.info/?probe=7bcb7c96be) | May 23, 2023 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [860479dab3](https://bsd-hardware.info/?probe=860479dab3) | May 21, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [e782ceaea8](https://bsd-hardware.info/?probe=e782ceaea8) | May 19, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [cc4c36977f](https://bsd-hardware.info/?probe=cc4c36977f) | May 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [c258ecb4bc](https://bsd-hardware.info/?probe=c258ecb4bc) | May 13, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [432b2a27c3](https://bsd-hardware.info/?probe=432b2a27c3) | May 13, 2023 |
| ZOTAC         | ZBOX-CI325NANO              | Mini pc     | [f64e789401](https://bsd-hardware.info/?probe=f64e789401) | May 11, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [6cd0f02045](https://bsd-hardware.info/?probe=6cd0f02045) | May 08, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [dcea67b6a6](https://bsd-hardware.info/?probe=dcea67b6a6) | May 08, 2023 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [79f10d24d6](https://bsd-hardware.info/?probe=79f10d24d6) | May 07, 2023 |
| ASUSTek       | 1000HE                      | Notebook    | [36214f8bed](https://bsd-hardware.info/?probe=36214f8bed) | May 07, 2023 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [105a885451](https://bsd-hardware.info/?probe=105a885451) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [161fe49de4](https://bsd-hardware.info/?probe=161fe49de4) | May 05, 2023 |
| Lenovo        | ThinkPad X230 2325T4T       | Notebook    | [00303b7a59](https://bsd-hardware.info/?probe=00303b7a59) | May 05, 2023 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [bb714a4350](https://bsd-hardware.info/?probe=bb714a4350) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [28e76d5531](https://bsd-hardware.info/?probe=28e76d5531) | May 04, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [8c3f486dbc](https://bsd-hardware.info/?probe=8c3f486dbc) | May 03, 2023 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [e2c3df29b5](https://bsd-hardware.info/?probe=e2c3df29b5) | May 03, 2023 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [c7daf17edb](https://bsd-hardware.info/?probe=c7daf17edb) | May 02, 2023 |
| Lenovo        | ThinkCentre M58 7360EUU     | Desktop     | [b0c462fbd5](https://bsd-hardware.info/?probe=b0c462fbd5) | May 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [c4af168c4a](https://bsd-hardware.info/?probe=c4af168c4a) | May 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [73f9fac4f8](https://bsd-hardware.info/?probe=73f9fac4f8) | May 01, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [cf504f51df](https://bsd-hardware.info/?probe=cf504f51df) | May 01, 2023 |
| AZW           | SER                         | Mini pc     | [d3d9ba6f52](https://bsd-hardware.info/?probe=d3d9ba6f52) | Apr 30, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [44ea9fb6ae](https://bsd-hardware.info/?probe=44ea9fb6ae) | Apr 30, 2023 |
| Dell          | 00NH4P A03                  | Server      | [85fb3b322e](https://bsd-hardware.info/?probe=85fb3b322e) | Apr 29, 2023 |
| iBASE         | Mi956                       | Desktop     | [e2c1e52a68](https://bsd-hardware.info/?probe=e2c1e52a68) | Apr 29, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [8acf41eb6b](https://bsd-hardware.info/?probe=8acf41eb6b) | Apr 28, 2023 |
| iBASE         | Mi956                       | Desktop     | [cb08976732](https://bsd-hardware.info/?probe=cb08976732) | Apr 27, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [b32c8cbec8](https://bsd-hardware.info/?probe=b32c8cbec8) | Apr 27, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [8476daf227](https://bsd-hardware.info/?probe=8476daf227) | Apr 27, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [dcacaf8c50](https://bsd-hardware.info/?probe=dcacaf8c50) | Apr 26, 2023 |
| HP            | 1998                        | Desktop     | [41b5bbe52c](https://bsd-hardware.info/?probe=41b5bbe52c) | Apr 26, 2023 |
| Protectli     | FW4B                        | Desktop     | [111e2f7b3b](https://bsd-hardware.info/?probe=111e2f7b3b) | Apr 25, 2023 |
| BYTENUC       | AZ51                        | Mini pc     | [89f1d3809e](https://bsd-hardware.info/?probe=89f1d3809e) | Apr 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [389267d68d](https://bsd-hardware.info/?probe=389267d68d) | Apr 24, 2023 |
| Lenovo        | ThinkCentre M57p 6073ATU    | Desktop     | [b1e7583e6b](https://bsd-hardware.info/?probe=b1e7583e6b) | Apr 24, 2023 |
| AWOW          | PC BOX                      | Mini pc     | [cfd318affb](https://bsd-hardware.info/?probe=cfd318affb) | Apr 23, 2023 |
| BYTENUC       | AZ51                        | Mini pc     | [0743e8fcc3](https://bsd-hardware.info/?probe=0743e8fcc3) | Apr 22, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [24379ebf10](https://bsd-hardware.info/?probe=24379ebf10) | Apr 20, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [cf533da9bf](https://bsd-hardware.info/?probe=cf533da9bf) | Apr 16, 2023 |
| Pegatron      | 2A72h                       | Desktop     | [142340aed4](https://bsd-hardware.info/?probe=142340aed4) | Apr 15, 2023 |
| iBASE         | Mi956                       | Desktop     | [0d4d63b29b](https://bsd-hardware.info/?probe=0d4d63b29b) | Apr 14, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [8e77aee0e0](https://bsd-hardware.info/?probe=8e77aee0e0) | Apr 14, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [d2f19cb660](https://bsd-hardware.info/?probe=d2f19cb660) | Apr 13, 2023 |
| HP            | 3397                        | Desktop     | [cf2d152bee](https://bsd-hardware.info/?probe=cf2d152bee) | Apr 13, 2023 |
| Google        | Terra                       | Notebook    | [ef1619f65f](https://bsd-hardware.info/?probe=ef1619f65f) | Apr 13, 2023 |
| Google        | Terra                       | Notebook    | [bf598bc5bf](https://bsd-hardware.info/?probe=bf598bc5bf) | Apr 13, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [e6c9c37b02](https://bsd-hardware.info/?probe=e6c9c37b02) | Apr 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | Notebook    | [0249b4e73f](https://bsd-hardware.info/?probe=0249b4e73f) | Apr 11, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [ce3072c27a](https://bsd-hardware.info/?probe=ce3072c27a) | Apr 05, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [9418e51f7e](https://bsd-hardware.info/?probe=9418e51f7e) | Apr 03, 2023 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [3bb60897ff](https://bsd-hardware.info/?probe=3bb60897ff) | Apr 01, 2023 |
| Alienware     | 049PDM A00                  | Desktop     | [139d115cdb](https://bsd-hardware.info/?probe=139d115cdb) | Mar 29, 2023 |
| Lenovo        | ThinkCentre M58 7360EUU     | Desktop     | [b86ffef220](https://bsd-hardware.info/?probe=b86ffef220) | Mar 28, 2023 |
| HP            | Pavilion dv6                | Notebook    | [ce2cc6852d](https://bsd-hardware.info/?probe=ce2cc6852d) | Mar 27, 2023 |
| Acer          | WG43M                       | Desktop     | [c8f2a03a08](https://bsd-hardware.info/?probe=c8f2a03a08) | Mar 27, 2023 |
| Acer          | WG43M                       | Desktop     | [5e154dc7cf](https://bsd-hardware.info/?probe=5e154dc7cf) | Mar 26, 2023 |
| MSI           | PRO B660-A DDR4             | Desktop     | [735a5cc6a2](https://bsd-hardware.info/?probe=735a5cc6a2) | Mar 26, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4e22bbc131](https://bsd-hardware.info/?probe=4e22bbc131) | Mar 26, 2023 |
| HP            | 1497                        | Desktop     | [08daaf3be1](https://bsd-hardware.info/?probe=08daaf3be1) | Mar 25, 2023 |
| HP            | 21B4 A01                    | Desktop     | [8de4b8231a](https://bsd-hardware.info/?probe=8de4b8231a) | Mar 25, 2023 |
| HP            | 1497                        | Desktop     | [fc6a7ebc91](https://bsd-hardware.info/?probe=fc6a7ebc91) | Mar 25, 2023 |
| eMachines     | eM350                       | Notebook    | [bb900ace2d](https://bsd-hardware.info/?probe=bb900ace2d) | Mar 25, 2023 |
| HP            | 1497                        | Desktop     | [e98b5284d9](https://bsd-hardware.info/?probe=e98b5284d9) | Mar 25, 2023 |
| Alienware     | 14                          | Notebook    | [742d648570](https://bsd-hardware.info/?probe=742d648570) | Mar 25, 2023 |
| Acer          | AOD270                      | Notebook    | [73877008e9](https://bsd-hardware.info/?probe=73877008e9) | Mar 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [55c708e91a](https://bsd-hardware.info/?probe=55c708e91a) | Mar 24, 2023 |
| Intel         | SandyBridge Platform        | Notebook    | [954a21f7de](https://bsd-hardware.info/?probe=954a21f7de) | Mar 23, 2023 |
| Dell          | Edge Gateway 5100           | Mini pc     | [7cb4288db0](https://bsd-hardware.info/?probe=7cb4288db0) | Mar 23, 2023 |
| Dell          | 00NH4P A03                  | Server      | [0d29dd3a66](https://bsd-hardware.info/?probe=0d29dd3a66) | Mar 20, 2023 |
| HP            | ProBook 640 G3              | Notebook    | [860471150b](https://bsd-hardware.info/?probe=860471150b) | Mar 18, 2023 |
| HP            | 1632                        | Desktop     | [8f3bb99bb4](https://bsd-hardware.info/?probe=8f3bb99bb4) | Mar 17, 2023 |
| AWOW          | PC BOX                      | Mini pc     | [fcbdcaff04](https://bsd-hardware.info/?probe=fcbdcaff04) | Mar 16, 2023 |
| Lenovo        | ThinkCentre M58p 6138DK1    | Desktop     | [293de8b0fd](https://bsd-hardware.info/?probe=293de8b0fd) | Mar 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [898095b140](https://bsd-hardware.info/?probe=898095b140) | Mar 09, 2023 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [6a15f7d4a1](https://bsd-hardware.info/?probe=6a15f7d4a1) | Mar 09, 2023 |
| Intel         | S1200RP_SE G62252-406       | Server      | [2b2b508432](https://bsd-hardware.info/?probe=2b2b508432) | Mar 05, 2023 |
| Dell          | 0M877N A02                  | Server      | [a69882ae55](https://bsd-hardware.info/?probe=a69882ae55) | Mar 02, 2023 |
| Arctic Wol... | AWN101                      | Desktop     | [e0f187e449](https://bsd-hardware.info/?probe=e0f187e449) | Mar 01, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [22a1b812f8](https://bsd-hardware.info/?probe=22a1b812f8) | Mar 01, 2023 |
| Dell          | 0M877N A01                  | Server      | [8037b5a26c](https://bsd-hardware.info/?probe=8037b5a26c) | Feb 27, 2023 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [40d63fc1f7](https://bsd-hardware.info/?probe=40d63fc1f7) | Feb 27, 2023 |
| Dell          | 01TKCC A01                  | Desktop     | [42da900d88](https://bsd-hardware.info/?probe=42da900d88) | Feb 26, 2023 |
| Lenovo        | 30D9 No DPK                 | Desktop     | [c3864d9d51](https://bsd-hardware.info/?probe=c3864d9d51) | Feb 26, 2023 |
| AZW           | U59                         | Desktop     | [a4e906c608](https://bsd-hardware.info/?probe=a4e906c608) | Feb 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [d690aee80e](https://bsd-hardware.info/?probe=d690aee80e) | Feb 26, 2023 |
| AZW           | U59                         | Desktop     | [4dad05a05a](https://bsd-hardware.info/?probe=4dad05a05a) | Feb 24, 2023 |
| AZW           | U59                         | Desktop     | [638aa3ff8e](https://bsd-hardware.info/?probe=638aa3ff8e) | Feb 24, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [50f39ca7e0](https://bsd-hardware.info/?probe=50f39ca7e0) | Feb 20, 2023 |
| Apple         | PowerMac3,6                 | Desktop     | [f31181f95c](https://bsd-hardware.info/?probe=f31181f95c) | Feb 20, 2023 |
| Gigabyte      | GB-BSi3A-6100               | Notebook    | [e7ef795b9b](https://bsd-hardware.info/?probe=e7ef795b9b) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | Notebook    | [cd2273037f](https://bsd-hardware.info/?probe=cd2273037f) | Feb 19, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [fd90fc5154](https://bsd-hardware.info/?probe=fd90fc5154) | Feb 18, 2023 |
| ASUSTek       | PRIME H310M-C R2.0          | Desktop     | [9761fb446b](https://bsd-hardware.info/?probe=9761fb446b) | Feb 18, 2023 |
| Dell          | 0M877N A02                  | Server      | [94d00881ba](https://bsd-hardware.info/?probe=94d00881ba) | Feb 17, 2023 |
| Dell          | 0MFXTY A02                  | Server      | [706029e578](https://bsd-hardware.info/?probe=706029e578) | Feb 17, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [f3c3e6ecb5](https://bsd-hardware.info/?probe=f3c3e6ecb5) | Feb 16, 2023 |
| MiTAC         | UltraPoint                  | Desktop     | [00e52df710](https://bsd-hardware.info/?probe=00e52df710) | Feb 15, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [547c79f551](https://bsd-hardware.info/?probe=547c79f551) | Feb 13, 2023 |
| HP            | 212B                        | Desktop     | [0e13beb9f6](https://bsd-hardware.info/?probe=0e13beb9f6) | Feb 12, 2023 |
| Dell          | 0M877N A02                  | Server      | [36e51fcc8b](https://bsd-hardware.info/?probe=36e51fcc8b) | Feb 12, 2023 |
| Dell          | 0F3KHR A02                  | Desktop     | [f69bff2d41](https://bsd-hardware.info/?probe=f69bff2d41) | Feb 12, 2023 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [60f03e1dec](https://bsd-hardware.info/?probe=60f03e1dec) | Feb 12, 2023 |
| Dell          | 0F3KHR A02                  | Desktop     | [c9c53f2141](https://bsd-hardware.info/?probe=c9c53f2141) | Feb 12, 2023 |
| iBASE         | Mi956                       | Desktop     | [86d20c1bc0](https://bsd-hardware.info/?probe=86d20c1bc0) | Feb 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [3f0d4c3ced](https://bsd-hardware.info/?probe=3f0d4c3ced) | Feb 10, 2023 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [5c2047356d](https://bsd-hardware.info/?probe=5c2047356d) | Feb 08, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [0587338e57](https://bsd-hardware.info/?probe=0587338e57) | Feb 08, 2023 |
| Dell          | 0F3KHR A02                  | Desktop     | [98c9324352](https://bsd-hardware.info/?probe=98c9324352) | Feb 05, 2023 |
| Unknown       | Unknown                     | Notebook    | [4cae5c6bb7](https://bsd-hardware.info/?probe=4cae5c6bb7) | Feb 01, 2023 |
| Supermicro    | X9SCL/X9SCM                 | Desktop     | [1022faa668](https://bsd-hardware.info/?probe=1022faa668) | Feb 01, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [8597f8bbcc](https://bsd-hardware.info/?probe=8597f8bbcc) | Jan 31, 2023 |
| Dell          | 0J3C2F A01                  | Desktop     | [93a87b6106](https://bsd-hardware.info/?probe=93a87b6106) | Jan 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [b8efd7453b](https://bsd-hardware.info/?probe=b8efd7453b) | Jan 29, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [e00d33f978](https://bsd-hardware.info/?probe=e00d33f978) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [87e25e2abd](https://bsd-hardware.info/?probe=87e25e2abd) | Jan 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [cde064f460](https://bsd-hardware.info/?probe=cde064f460) | Jan 26, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [76840aba40](https://bsd-hardware.info/?probe=76840aba40) | Jan 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [14089c4ab4](https://bsd-hardware.info/?probe=14089c4ab4) | Jan 21, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [b0fe0783d5](https://bsd-hardware.info/?probe=b0fe0783d5) | Jan 21, 2023 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [629c2e1a21](https://bsd-hardware.info/?probe=629c2e1a21) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [32ebc1c99d](https://bsd-hardware.info/?probe=32ebc1c99d) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [c3281eb186](https://bsd-hardware.info/?probe=c3281eb186) | Jan 18, 2023 |
| HP            | 83F2                        | Desktop     | [a7230c1af5](https://bsd-hardware.info/?probe=a7230c1af5) | Jan 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [0049fd4cfc](https://bsd-hardware.info/?probe=0049fd4cfc) | Jan 17, 2023 |
| HP            | 83F2                        | Desktop     | [912de3c81d](https://bsd-hardware.info/?probe=912de3c81d) | Jan 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [23d2c64af3](https://bsd-hardware.info/?probe=23d2c64af3) | Jan 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [429659b071](https://bsd-hardware.info/?probe=429659b071) | Jan 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [7ba28d1e6b](https://bsd-hardware.info/?probe=7ba28d1e6b) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [917972b6ae](https://bsd-hardware.info/?probe=917972b6ae) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [bd60eadfc4](https://bsd-hardware.info/?probe=bd60eadfc4) | Jan 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [a21b21b82f](https://bsd-hardware.info/?probe=a21b21b82f) | Jan 12, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [2372c973c8](https://bsd-hardware.info/?probe=2372c973c8) | Jan 11, 2023 |
| HP            | 2000                        | Notebook    | [7f29899321](https://bsd-hardware.info/?probe=7f29899321) | Jan 09, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [e56cfbdedc](https://bsd-hardware.info/?probe=e56cfbdedc) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [db483e3d46](https://bsd-hardware.info/?probe=db483e3d46) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [b19ed4597a](https://bsd-hardware.info/?probe=b19ed4597a) | Jan 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [6347de602a](https://bsd-hardware.info/?probe=6347de602a) | Jan 07, 2023 |
| Lenovo        | ThinkPad T400 2764CTO       | Notebook    | [26f8459193](https://bsd-hardware.info/?probe=26f8459193) | Jan 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [4e8b83804d](https://bsd-hardware.info/?probe=4e8b83804d) | Jan 06, 2023 |
| Supermicro    | X10DRL-i                    | Server      | [c0fa5bb871](https://bsd-hardware.info/?probe=c0fa5bb871) | Jan 06, 2023 |
| MSI           | MEG Z690 UNIFY-X            | Desktop     | [e70cd80d11](https://bsd-hardware.info/?probe=e70cd80d11) | Jan 05, 2023 |
| Protectli     | VP2410 10                   | Desktop     | [81c02d080f](https://bsd-hardware.info/?probe=81c02d080f) | Jan 05, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [219200b0b6](https://bsd-hardware.info/?probe=219200b0b6) | Jan 05, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [4730790da9](https://bsd-hardware.info/?probe=4730790da9) | Jan 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [3d2465f9f9](https://bsd-hardware.info/?probe=3d2465f9f9) | Jan 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9dd29daa88](https://bsd-hardware.info/?probe=9dd29daa88) | Jan 02, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [a9bbb3592c](https://bsd-hardware.info/?probe=a9bbb3592c) | Jan 02, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [b6ec2e7e28](https://bsd-hardware.info/?probe=b6ec2e7e28) | Dec 31, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [cac58d91b6](https://bsd-hardware.info/?probe=cac58d91b6) | Dec 31, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [910c2bba4a](https://bsd-hardware.info/?probe=910c2bba4a) | Dec 31, 2022 |
| Gigabyte      | MBHM87P-00                  | Desktop     | [5d287163c9](https://bsd-hardware.info/?probe=5d287163c9) | Dec 29, 2022 |
| HP            | 1998                        | Desktop     | [afc7de60e3](https://bsd-hardware.info/?probe=afc7de60e3) | Dec 28, 2022 |
| ASRock        | N3710-NUC IPC               | Desktop     | [80c809e992](https://bsd-hardware.info/?probe=80c809e992) | Dec 24, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cde7bad6c3](https://bsd-hardware.info/?probe=cde7bad6c3) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [b8c89bdca8](https://bsd-hardware.info/?probe=b8c89bdca8) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [b0d1792185](https://bsd-hardware.info/?probe=b0d1792185) | Dec 21, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [0eea35e069](https://bsd-hardware.info/?probe=0eea35e069) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [f876d5d5b1](https://bsd-hardware.info/?probe=f876d5d5b1) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [3d77f833b0](https://bsd-hardware.info/?probe=3d77f833b0) | Dec 19, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [1f1de1d49c](https://bsd-hardware.info/?probe=1f1de1d49c) | Dec 18, 2022 |
| PC Engines    | APU                         | Desktop     | [19786edc61](https://bsd-hardware.info/?probe=19786edc61) | Dec 17, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [d9376f2f63](https://bsd-hardware.info/?probe=d9376f2f63) | Dec 16, 2022 |
| HP            | 1495                        | Desktop     | [04bd0455f2](https://bsd-hardware.info/?probe=04bd0455f2) | Dec 14, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [e44f465325](https://bsd-hardware.info/?probe=e44f465325) | Dec 14, 2022 |
| HP            | 1495                        | Desktop     | [23f8aeada7](https://bsd-hardware.info/?probe=23f8aeada7) | Dec 14, 2022 |
| Dell          | 0TY019 A02                  | Server      | [a12907d76a](https://bsd-hardware.info/?probe=a12907d76a) | Dec 12, 2022 |
| HP            | 2000                        | Notebook    | [5414b7c943](https://bsd-hardware.info/?probe=5414b7c943) | Dec 09, 2022 |
| HP            | 1495                        | Desktop     | [3eab39d89f](https://bsd-hardware.info/?probe=3eab39d89f) | Dec 09, 2022 |
| Sophos        | SG                          | Firewall    | [07fbfad254](https://bsd-hardware.info/?probe=07fbfad254) | Dec 09, 2022 |
| Sophos        | SG                          | Firewall    | [a3b0edbd3c](https://bsd-hardware.info/?probe=a3b0edbd3c) | Dec 09, 2022 |
| HP            | 3397                        | Desktop     | [bc9e5c3ab7](https://bsd-hardware.info/?probe=bc9e5c3ab7) | Dec 09, 2022 |
| Pegatron      | 2A72h                       | Desktop     | [87e76fd095](https://bsd-hardware.info/?probe=87e76fd095) | Dec 09, 2022 |
| Dell          | 0TY019 A02                  | Server      | [84b683ec0b](https://bsd-hardware.info/?probe=84b683ec0b) | Dec 08, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [27dea9bcb5](https://bsd-hardware.info/?probe=27dea9bcb5) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [15b2363325](https://bsd-hardware.info/?probe=15b2363325) | Dec 05, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Acer          | Aspire XC-105               | Desktop     | [250b12c3f2](https://bsd-hardware.info/?probe=250b12c3f2) | Dec 05, 2022 |
| Panasonic     | CF-54-1                     | Notebook    | [0c5820ea0d](https://bsd-hardware.info/?probe=0c5820ea0d) | Dec 01, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cfaeaeb2f2](https://bsd-hardware.info/?probe=cfaeaeb2f2) | Nov 29, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [e8e158f783](https://bsd-hardware.info/?probe=e8e158f783) | Nov 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [512a05eefb](https://bsd-hardware.info/?probe=512a05eefb) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5f0b8df8d0](https://bsd-hardware.info/?probe=5f0b8df8d0) | Nov 27, 2022 |
| CompuLab      | fit-PC3                     | Mini pc     | [34dd85f78d](https://bsd-hardware.info/?probe=34dd85f78d) | Nov 26, 2022 |
| CompuLab      | fit-PC3                     | Mini pc     | [54a64a269c](https://bsd-hardware.info/?probe=54a64a269c) | Nov 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [222e69ff59](https://bsd-hardware.info/?probe=222e69ff59) | Nov 26, 2022 |
| Protectli     | FW6                         | Desktop     | [74510f3177](https://bsd-hardware.info/?probe=74510f3177) | Nov 25, 2022 |
| HP            | 8055                        | Desktop     | [ace4570d15](https://bsd-hardware.info/?probe=ace4570d15) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [7258992b77](https://bsd-hardware.info/?probe=7258992b77) | Nov 24, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [e0f08b66c2](https://bsd-hardware.info/?probe=e0f08b66c2) | Nov 21, 2022 |
| Lenovo        | ThinkPad X230 2325T4T       | Notebook    | [f0cc17c7eb](https://bsd-hardware.info/?probe=f0cc17c7eb) | Nov 21, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [8257d11669](https://bsd-hardware.info/?probe=8257d11669) | Nov 20, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [7c7a121711](https://bsd-hardware.info/?probe=7c7a121711) | Nov 18, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [5875ecec9f](https://bsd-hardware.info/?probe=5875ecec9f) | Nov 18, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [0d37f1878b](https://bsd-hardware.info/?probe=0d37f1878b) | Nov 17, 2022 |
| AZW           | U59                         | Desktop     | [25e1349c5f](https://bsd-hardware.info/?probe=25e1349c5f) | Nov 17, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [269f915ce2](https://bsd-hardware.info/?probe=269f915ce2) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [4044f32351](https://bsd-hardware.info/?probe=4044f32351) | Nov 12, 2022 |
| Lenovo        | 30D9 No DPK                 | Desktop     | [bb9cf416c4](https://bsd-hardware.info/?probe=bb9cf416c4) | Nov 11, 2022 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [b8874a6df3](https://bsd-hardware.info/?probe=b8874a6df3) | Nov 10, 2022 |
| ASUSTek       | P8H77-I                     | Desktop     | [04ea3cc97d](https://bsd-hardware.info/?probe=04ea3cc97d) | Nov 09, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [32331d772c](https://bsd-hardware.info/?probe=32331d772c) | Nov 08, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [a84d0a0380](https://bsd-hardware.info/?probe=a84d0a0380) | Nov 08, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [e8aea441aa](https://bsd-hardware.info/?probe=e8aea441aa) | Nov 06, 2022 |
| Datto         | SSD                         | Desktop     | [235483110d](https://bsd-hardware.info/?probe=235483110d) | Nov 05, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [871a5c449f](https://bsd-hardware.info/?probe=871a5c449f) | Nov 01, 2022 |
| Dell          | 09T7VV A02                  | Server      | [6e89de5b97](https://bsd-hardware.info/?probe=6e89de5b97) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [5758027775](https://bsd-hardware.info/?probe=5758027775) | Oct 31, 2022 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [e5716f886a](https://bsd-hardware.info/?probe=e5716f886a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [34f0a2bc03](https://bsd-hardware.info/?probe=34f0a2bc03) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS10N00    | Notebook    | [04ce25bd7f](https://bsd-hardware.info/?probe=04ce25bd7f) | Oct 29, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [e3c5057898](https://bsd-hardware.info/?probe=e3c5057898) | Oct 29, 2022 |
| Unknown       | Unknown                     | Notebook    | [2df5c5b434](https://bsd-hardware.info/?probe=2df5c5b434) | Oct 28, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [6dda683e10](https://bsd-hardware.info/?probe=6dda683e10) | Oct 28, 2022 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [f2fafaa9e3](https://bsd-hardware.info/?probe=f2fafaa9e3) | Oct 27, 2022 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [d96fbc17b5](https://bsd-hardware.info/?probe=d96fbc17b5) | Oct 27, 2022 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [088e0245af](https://bsd-hardware.info/?probe=088e0245af) | Oct 27, 2022 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [6e8067d4d8](https://bsd-hardware.info/?probe=6e8067d4d8) | Oct 26, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [b7a4ee06a6](https://bsd-hardware.info/?probe=b7a4ee06a6) | Oct 26, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [f2236f17ee](https://bsd-hardware.info/?probe=f2236f17ee) | Oct 25, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [c4bbcf9537](https://bsd-hardware.info/?probe=c4bbcf9537) | Oct 24, 2022 |
| HP            | 18E4                        | Desktop     | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [c3f0ae254e](https://bsd-hardware.info/?probe=c3f0ae254e) | Oct 17, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [b4e02e3f51](https://bsd-hardware.info/?probe=b4e02e3f51) | Oct 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [00b5fa7a4e](https://bsd-hardware.info/?probe=00b5fa7a4e) | Oct 13, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [edead8a3ae](https://bsd-hardware.info/?probe=edead8a3ae) | Oct 11, 2022 |
| MSI           | GL65 Leopard 10SFSK         | Notebook    | [2ea7c7f9a2](https://bsd-hardware.info/?probe=2ea7c7f9a2) | Oct 10, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [ce728798a1](https://bsd-hardware.info/?probe=ce728798a1) | Oct 07, 2022 |
| Sophos        | XG                          | Firewall    | [cf528e776d](https://bsd-hardware.info/?probe=cf528e776d) | Oct 05, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [79060c241b](https://bsd-hardware.info/?probe=79060c241b) | Oct 03, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [3590d4504c](https://bsd-hardware.info/?probe=3590d4504c) | Oct 02, 2022 |
| MSI           | GL65 Leopard 10SFSK         | Notebook    | [489567748e](https://bsd-hardware.info/?probe=489567748e) | Oct 01, 2022 |
| Intel         | S1200RP_SE G62252-406       | Server      | [4763fe7595](https://bsd-hardware.info/?probe=4763fe7595) | Sep 30, 2022 |
| Intel         | H81U                        | Notebook    | [fa8c32528a](https://bsd-hardware.info/?probe=fa8c32528a) | Sep 28, 2022 |
| Acer          | Swift SF313-52              | Notebook    | [83516dabac](https://bsd-hardware.info/?probe=83516dabac) | Sep 28, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [33b252016c](https://bsd-hardware.info/?probe=33b252016c) | Sep 26, 2022 |
| Acer          | Swift SF313-52              | Notebook    | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [a1a2cbc6c9](https://bsd-hardware.info/?probe=a1a2cbc6c9) | Sep 20, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | Notebook    | [2f1f82558e](https://bsd-hardware.info/?probe=2f1f82558e) | Sep 18, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [22f23ccfa5](https://bsd-hardware.info/?probe=22f23ccfa5) | Sep 17, 2022 |
| Google        | Peppy                       | Notebook    | [80ffa77224](https://bsd-hardware.info/?probe=80ffa77224) | Sep 15, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [21e7190ff2](https://bsd-hardware.info/?probe=21e7190ff2) | Sep 11, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [3c152ae7bd](https://bsd-hardware.info/?probe=3c152ae7bd) | Sep 11, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [89b185547b](https://bsd-hardware.info/?probe=89b185547b) | Sep 10, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [a854e50942](https://bsd-hardware.info/?probe=a854e50942) | Sep 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [860518eb18](https://bsd-hardware.info/?probe=860518eb18) | Sep 04, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [b53e1d28cd](https://bsd-hardware.info/?probe=b53e1d28cd) | Sep 04, 2022 |
| Intel         | DQ67EP AAG12529-307         | Desktop     | [1fb1fd6705](https://bsd-hardware.info/?probe=1fb1fd6705) | Sep 03, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [2e4b87acd2](https://bsd-hardware.info/?probe=2e4b87acd2) | Sep 03, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [b3a1456bb4](https://bsd-hardware.info/?probe=b3a1456bb4) | Aug 29, 2022 |
| HP            | 8103 A01                    | Mini pc     | [de20688262](https://bsd-hardware.info/?probe=de20688262) | Aug 27, 2022 |
| Dell          | 09T7VV A07                  | Server      | [0325ade874](https://bsd-hardware.info/?probe=0325ade874) | Aug 23, 2022 |
| Gigabyte      | MBHM87P-00                  | Desktop     | [9fa5160871](https://bsd-hardware.info/?probe=9fa5160871) | Aug 22, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [04df24b0b8](https://bsd-hardware.info/?probe=04df24b0b8) | Aug 20, 2022 |
| Dell          | 04Y8V0 A02                  | Desktop     | [9fc4b3c63e](https://bsd-hardware.info/?probe=9fc4b3c63e) | Aug 17, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [753f277d5c](https://bsd-hardware.info/?probe=753f277d5c) | Aug 16, 2022 |
| AZW           | Green G1                    | Desktop     | [4bccb24702](https://bsd-hardware.info/?probe=4bccb24702) | Aug 15, 2022 |
| Dell          | 04Y8V0 A02                  | Desktop     | [a21172360d](https://bsd-hardware.info/?probe=a21172360d) | Aug 15, 2022 |
| Dell          | 04Y8V0 A02                  | Desktop     | [6acccc63ff](https://bsd-hardware.info/?probe=6acccc63ff) | Aug 15, 2022 |
| Lenovo        | 3111 SDK0J40705 WIN 3425... | Desktop     | [6927813b1d](https://bsd-hardware.info/?probe=6927813b1d) | Aug 13, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [a45977c76b](https://bsd-hardware.info/?probe=a45977c76b) | Aug 10, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [236cd1ee65](https://bsd-hardware.info/?probe=236cd1ee65) | Aug 08, 2022 |
| Biostar       | TA880GU3+                   | Desktop     | [8b0c8541b3](https://bsd-hardware.info/?probe=8b0c8541b3) | Aug 06, 2022 |
| MSI           | 785GT-E63                   | Desktop     | [8c307fb033](https://bsd-hardware.info/?probe=8c307fb033) | Aug 03, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [83bbf8e819](https://bsd-hardware.info/?probe=83bbf8e819) | Aug 03, 2022 |
| Intel         | H81U                        | Notebook    | [b5e2598580](https://bsd-hardware.info/?probe=b5e2598580) | Aug 03, 2022 |
| Intel         | H81U                        | Notebook    | [8f50dbe259](https://bsd-hardware.info/?probe=8f50dbe259) | Aug 01, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [860b06cb6b](https://bsd-hardware.info/?probe=860b06cb6b) | Aug 01, 2022 |
| HP            | 8055                        | Desktop     | [6a8a361dae](https://bsd-hardware.info/?probe=6a8a361dae) | Jul 31, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [900c62c2ba](https://bsd-hardware.info/?probe=900c62c2ba) | Jul 30, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [27b986a422](https://bsd-hardware.info/?probe=27b986a422) | Jul 30, 2022 |
| HP            | 8055                        | Desktop     | [41d802a80a](https://bsd-hardware.info/?probe=41d802a80a) | Jul 29, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [7be6ba0021](https://bsd-hardware.info/?probe=7be6ba0021) | Jul 29, 2022 |
| HP            | 18E9                        | Desktop     | [56460b095e](https://bsd-hardware.info/?probe=56460b095e) | Jul 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [03497b7b2a](https://bsd-hardware.info/?probe=03497b7b2a) | Jul 27, 2022 |
| Unknown       | Unknown                     | Firewall    | [15c779bfe1](https://bsd-hardware.info/?probe=15c779bfe1) | Jul 27, 2022 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [3df3bd2f62](https://bsd-hardware.info/?probe=3df3bd2f62) | Jul 22, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [1ed99ad502](https://bsd-hardware.info/?probe=1ed99ad502) | Jul 20, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [46a6f4e8f3](https://bsd-hardware.info/?probe=46a6f4e8f3) | Jul 19, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [7ca3d2715c](https://bsd-hardware.info/?probe=7ca3d2715c) | Jul 19, 2022 |
| Lenovo        | ThinkCentre M91 4518E4U     | Desktop     | [8dd1034cfa](https://bsd-hardware.info/?probe=8dd1034cfa) | Jul 16, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [7530b2fc5f](https://bsd-hardware.info/?probe=7530b2fc5f) | Jul 15, 2022 |
| AZW           | Green G1                    | Desktop     | [9a2120ae5a](https://bsd-hardware.info/?probe=9a2120ae5a) | Jul 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [bd1a86e875](https://bsd-hardware.info/?probe=bd1a86e875) | Jul 10, 2022 |
| Datto         | SSD                         | Desktop     | [639d28d449](https://bsd-hardware.info/?probe=639d28d449) | Jul 08, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [a945073364](https://bsd-hardware.info/?probe=a945073364) | Jul 07, 2022 |
| Protectli     | FW6                         | Desktop     | [e82838534b](https://bsd-hardware.info/?probe=e82838534b) | Jul 06, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [ac861b1ee3](https://bsd-hardware.info/?probe=ac861b1ee3) | Jun 25, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [598ecb5457](https://bsd-hardware.info/?probe=598ecb5457) | Jun 25, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [a6a5de19ae](https://bsd-hardware.info/?probe=a6a5de19ae) | Jun 23, 2022 |
| HP            | 82A2                        | Desktop     | [77c244bd43](https://bsd-hardware.info/?probe=77c244bd43) | Jun 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a57a2f609c](https://bsd-hardware.info/?probe=a57a2f609c) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [1febab0774](https://bsd-hardware.info/?probe=1febab0774) | Jun 12, 2022 |
| HP            | 1998                        | Desktop     | [1bb67075dd](https://bsd-hardware.info/?probe=1bb67075dd) | Jun 12, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [5054729300](https://bsd-hardware.info/?probe=5054729300) | Jun 11, 2022 |
| HP            | 1998                        | Desktop     | [54a6daf0a6](https://bsd-hardware.info/?probe=54a6daf0a6) | Jun 11, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [3b8d6cb36e](https://bsd-hardware.info/?probe=3b8d6cb36e) | Jun 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [26cd129290](https://bsd-hardware.info/?probe=26cd129290) | Jun 06, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [f3c197bdfb](https://bsd-hardware.info/?probe=f3c197bdfb) | Jun 04, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [8e8ef96421](https://bsd-hardware.info/?probe=8e8ef96421) | Jun 04, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [dce99bec81](https://bsd-hardware.info/?probe=dce99bec81) | Jun 03, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [8ca71ddf4d](https://bsd-hardware.info/?probe=8ca71ddf4d) | Jun 02, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [cc70f5d86f](https://bsd-hardware.info/?probe=cc70f5d86f) | Jun 01, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [9d5edd9fa9](https://bsd-hardware.info/?probe=9d5edd9fa9) | May 29, 2022 |
| Dell          | 0M3F6C A01                  | Desktop     | [21d45bc75d](https://bsd-hardware.info/?probe=21d45bc75d) | May 23, 2022 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [c956536edd](https://bsd-hardware.info/?probe=c956536edd) | May 23, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [6d7475e9c9](https://bsd-hardware.info/?probe=6d7475e9c9) | May 22, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [963fa158b5](https://bsd-hardware.info/?probe=963fa158b5) | May 22, 2022 |
| Sophos        | SG                          | Firewall    | [9f76b20afd](https://bsd-hardware.info/?probe=9f76b20afd) | May 22, 2022 |
| Dell          | Studio 1747                 | Notebook    | [7ae292b282](https://bsd-hardware.info/?probe=7ae292b282) | May 21, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [5d31f6f5a8](https://bsd-hardware.info/?probe=5d31f6f5a8) | May 19, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [1014f7f61c](https://bsd-hardware.info/?probe=1014f7f61c) | May 18, 2022 |
| Dell          | 0DXJD9 A01                  | Desktop     | [be13c9069c](https://bsd-hardware.info/?probe=be13c9069c) | May 18, 2022 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [b74299204a](https://bsd-hardware.info/?probe=b74299204a) | May 18, 2022 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [9ec22ea24c](https://bsd-hardware.info/?probe=9ec22ea24c) | May 17, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [c7af1dd7bf](https://bsd-hardware.info/?probe=c7af1dd7bf) | May 16, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [30cfcd5004](https://bsd-hardware.info/?probe=30cfcd5004) | May 15, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [44ab2d6faa](https://bsd-hardware.info/?probe=44ab2d6faa) | May 14, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [9af60bd6e4](https://bsd-hardware.info/?probe=9af60bd6e4) | May 14, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [fd066b2db9](https://bsd-hardware.info/?probe=fd066b2db9) | May 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [0958a64385](https://bsd-hardware.info/?probe=0958a64385) | May 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [0d62d4e3cd](https://bsd-hardware.info/?probe=0d62d4e3cd) | May 09, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [a7111b84cb](https://bsd-hardware.info/?probe=a7111b84cb) | May 08, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [3e60a82218](https://bsd-hardware.info/?probe=3e60a82218) | May 06, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [daed3f9401](https://bsd-hardware.info/?probe=daed3f9401) | May 06, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [a6393754b4](https://bsd-hardware.info/?probe=a6393754b4) | May 05, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [cf2f288b93](https://bsd-hardware.info/?probe=cf2f288b93) | May 04, 2022 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [774cab5326](https://bsd-hardware.info/?probe=774cab5326) | May 03, 2022 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [4b1abdd507](https://bsd-hardware.info/?probe=4b1abdd507) | May 03, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [2884106c6b](https://bsd-hardware.info/?probe=2884106c6b) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [00ba6ca9f8](https://bsd-hardware.info/?probe=00ba6ca9f8) | May 03, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [6b77fe651f](https://bsd-hardware.info/?probe=6b77fe651f) | May 03, 2022 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [f3c30a6190](https://bsd-hardware.info/?probe=f3c30a6190) | May 02, 2022 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [abd8754907](https://bsd-hardware.info/?probe=abd8754907) | May 01, 2022 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [1ce63e2214](https://bsd-hardware.info/?probe=1ce63e2214) | Apr 29, 2022 |
| HP            | 1495                        | Desktop     | [6e0f1cc72e](https://bsd-hardware.info/?probe=6e0f1cc72e) | Apr 29, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [586d311314](https://bsd-hardware.info/?probe=586d311314) | Apr 28, 2022 |
| HP            | 1998                        | Desktop     | [1244e0583b](https://bsd-hardware.info/?probe=1244e0583b) | Apr 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [b3d5defed1](https://bsd-hardware.info/?probe=b3d5defed1) | Apr 26, 2022 |
| Supermicro    | X12SCZ-TLN4FA               | Server      | [2a9ac1e6ee](https://bsd-hardware.info/?probe=2a9ac1e6ee) | Apr 23, 2022 |
| Sophos        | SG                          | Firewall    | [cbd2585bf3](https://bsd-hardware.info/?probe=cbd2585bf3) | Apr 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [4166c67369](https://bsd-hardware.info/?probe=4166c67369) | Apr 20, 2022 |
| Dell          | G5 5090                     | Desktop     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [01945539d9](https://bsd-hardware.info/?probe=01945539d9) | Apr 17, 2022 |
| Sophos        | SG                          | Firewall    | [ed297e4274](https://bsd-hardware.info/?probe=ed297e4274) | Apr 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [979e868c51](https://bsd-hardware.info/?probe=979e868c51) | Apr 16, 2022 |
| Dell          | 0DXJD9 A01                  | Desktop     | [4023d86091](https://bsd-hardware.info/?probe=4023d86091) | Apr 15, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [29be552d6a](https://bsd-hardware.info/?probe=29be552d6a) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [1173feae11](https://bsd-hardware.info/?probe=1173feae11) | Apr 13, 2022 |
| Alienware     | 049PDM A00                  | Desktop     | [6dac56f3bb](https://bsd-hardware.info/?probe=6dac56f3bb) | Apr 11, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [641d1574ce](https://bsd-hardware.info/?probe=641d1574ce) | Apr 11, 2022 |
| Toshiba       | Satellite Pro T130          | Notebook    | [62dd51afcf](https://bsd-hardware.info/?probe=62dd51afcf) | Apr 11, 2022 |
| HP            | 8103 A01                    | Mini pc     | [1fa67a8d17](https://bsd-hardware.info/?probe=1fa67a8d17) | Apr 04, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [e79f120d82](https://bsd-hardware.info/?probe=e79f120d82) | Apr 01, 2022 |
| Dell          | 081N4V A06                  | Server      | [700e5de168](https://bsd-hardware.info/?probe=700e5de168) | Apr 01, 2022 |
| PC Engines    | APU                         | Desktop     | [e266947055](https://bsd-hardware.info/?probe=e266947055) | Mar 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [ef1a743845](https://bsd-hardware.info/?probe=ef1a743845) | Mar 28, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [1176fca4ab](https://bsd-hardware.info/?probe=1176fca4ab) | Mar 27, 2022 |
| ASUSTek       | ET2411_W8                   | All in one  | [fb186da68e](https://bsd-hardware.info/?probe=fb186da68e) | Mar 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [d0e7b62eda](https://bsd-hardware.info/?probe=d0e7b62eda) | Mar 25, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cf576c571d](https://bsd-hardware.info/?probe=cf576c571d) | Mar 22, 2022 |
| HP            | 213D A01                    | Desktop     | [6baba4f9c1](https://bsd-hardware.info/?probe=6baba4f9c1) | Mar 20, 2022 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [3727ba82af](https://bsd-hardware.info/?probe=3727ba82af) | Mar 19, 2022 |
| ASUSTek       | ET2411_W8                   | All in one  | [b95da98f21](https://bsd-hardware.info/?probe=b95da98f21) | Mar 17, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [f22a45488b](https://bsd-hardware.info/?probe=f22a45488b) | Mar 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a5fd383c40](https://bsd-hardware.info/?probe=a5fd383c40) | Mar 14, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [6024b9491d](https://bsd-hardware.info/?probe=6024b9491d) | Mar 06, 2022 |
| MSI           | MS-7388                     | Desktop     | [ad8209dbdb](https://bsd-hardware.info/?probe=ad8209dbdb) | Mar 05, 2022 |
| MSI           | MS-7388                     | Desktop     | [a59bca8bde](https://bsd-hardware.info/?probe=a59bca8bde) | Mar 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [a6abb45607](https://bsd-hardware.info/?probe=a6abb45607) | Mar 04, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [589f10057f](https://bsd-hardware.info/?probe=589f10057f) | Mar 01, 2022 |
| Intel         | H81U                        | Notebook    | [71068a0577](https://bsd-hardware.info/?probe=71068a0577) | Mar 01, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [e14fd85d4a](https://bsd-hardware.info/?probe=e14fd85d4a) | Feb 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [6b2550968e](https://bsd-hardware.info/?probe=6b2550968e) | Feb 23, 2022 |
| Intel         | NUC5CPYB H61145-404         | Mini pc     | [5f4e1c30b8](https://bsd-hardware.info/?probe=5f4e1c30b8) | Feb 19, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b69015f0e0](https://bsd-hardware.info/?probe=b69015f0e0) | Feb 16, 2022 |
| PC Engines    | apu4                        | Desktop     | [09f27a0f23](https://bsd-hardware.info/?probe=09f27a0f23) | Feb 14, 2022 |
| Protectli     | FW6                         | Desktop     | [d33b2f1244](https://bsd-hardware.info/?probe=d33b2f1244) | Feb 13, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [04bee98c7e](https://bsd-hardware.info/?probe=04bee98c7e) | Feb 12, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [bd63b06ea9](https://bsd-hardware.info/?probe=bd63b06ea9) | Feb 11, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [12ccb8699b](https://bsd-hardware.info/?probe=12ccb8699b) | Feb 08, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [0d3b560aad](https://bsd-hardware.info/?probe=0d3b560aad) | Feb 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [3dabf0503d](https://bsd-hardware.info/?probe=3dabf0503d) | Feb 08, 2022 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [53abdfa3b1](https://bsd-hardware.info/?probe=53abdfa3b1) | Feb 07, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [1dafdcc71a](https://bsd-hardware.info/?probe=1dafdcc71a) | Feb 05, 2022 |
| Supermicro    | H11DSi                      | Server      | [4e41dc7f8b](https://bsd-hardware.info/?probe=4e41dc7f8b) | Feb 03, 2022 |
| ASRock        | J4105M                      | Desktop     | [09b9d104b9](https://bsd-hardware.info/?probe=09b9d104b9) | Feb 03, 2022 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [342915fccd](https://bsd-hardware.info/?probe=342915fccd) | Feb 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [07d565ad8c](https://bsd-hardware.info/?probe=07d565ad8c) | Feb 02, 2022 |
| Dell          | 00NH4P A03                  | Server      | [1fe915b90a](https://bsd-hardware.info/?probe=1fe915b90a) | Feb 01, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [83975bd2b1](https://bsd-hardware.info/?probe=83975bd2b1) | Jan 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ff629a490d](https://bsd-hardware.info/?probe=ff629a490d) | Jan 29, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [4b17ef7a18](https://bsd-hardware.info/?probe=4b17ef7a18) | Jan 27, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [4df3db0379](https://bsd-hardware.info/?probe=4df3db0379) | Jan 26, 2022 |
| Sophos        | SG                          | Firewall    | [3c6601bf94](https://bsd-hardware.info/?probe=3c6601bf94) | Jan 15, 2022 |
| PC Engines    | APU2                        | Desktop     | [5ea082ddf9](https://bsd-hardware.info/?probe=5ea082ddf9) | Jan 13, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [87000234dc](https://bsd-hardware.info/?probe=87000234dc) | Jan 11, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | Notebook    | [4ae2360503](https://bsd-hardware.info/?probe=4ae2360503) | Jan 11, 2022 |
| ASUSTek       | P8Z68-M PRO                 | Desktop     | [a0885f4f44](https://bsd-hardware.info/?probe=a0885f4f44) | Jan 10, 2022 |
| Dell          | 0DT021 A02                  | Server      | [d1fdef3d4d](https://bsd-hardware.info/?probe=d1fdef3d4d) | Jan 09, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7863226bbe](https://bsd-hardware.info/?probe=7863226bbe) | Jan 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [ded64258b4](https://bsd-hardware.info/?probe=ded64258b4) | Jan 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [8d607c1d19](https://bsd-hardware.info/?probe=8d607c1d19) | Jan 03, 2022 |
| Toshiba       | TECRA Z40-B                 | Notebook    | [d498fcd3f8](https://bsd-hardware.info/?probe=d498fcd3f8) | Jan 02, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [a07366611d](https://bsd-hardware.info/?probe=a07366611d) | Jan 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [c183bdd5af](https://bsd-hardware.info/?probe=c183bdd5af) | Jan 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [4848e4009f](https://bsd-hardware.info/?probe=4848e4009f) | Jan 01, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [7d47d0db05](https://bsd-hardware.info/?probe=7d47d0db05) | Dec 30, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [c3884fac44](https://bsd-hardware.info/?probe=c3884fac44) | Dec 30, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [259b5cc7b2](https://bsd-hardware.info/?probe=259b5cc7b2) | Dec 28, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [bde74629f9](https://bsd-hardware.info/?probe=bde74629f9) | Dec 25, 2021 |
| ASRock        | J3355B-ITX                  | Desktop     | [f4648747b0](https://bsd-hardware.info/?probe=f4648747b0) | Dec 22, 2021 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [839eed529d](https://bsd-hardware.info/?probe=839eed529d) | Dec 21, 2021 |
| Lenovo        | ThinkPad X280 20KF001UUS    | Notebook    | [5b9001009e](https://bsd-hardware.info/?probe=5b9001009e) | Dec 20, 2021 |
| HP            | 8103 A01                    | Mini pc     | [0138a82561](https://bsd-hardware.info/?probe=0138a82561) | Dec 18, 2021 |
| Quanta        | 2AC7 011                    | Desktop     | [1a831a1d34](https://bsd-hardware.info/?probe=1a831a1d34) | Dec 18, 2021 |
| HP            | 843B                        | Desktop     | [f0d279747f](https://bsd-hardware.info/?probe=f0d279747f) | Dec 13, 2021 |
| HP            | 843B                        | Desktop     | [56400d3999](https://bsd-hardware.info/?probe=56400d3999) | Dec 13, 2021 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [a86326d049](https://bsd-hardware.info/?probe=a86326d049) | Dec 11, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [624041b5db](https://bsd-hardware.info/?probe=624041b5db) | Dec 09, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [79d9964300](https://bsd-hardware.info/?probe=79d9964300) | Dec 02, 2021 |
| Dell          | 051FJ8 A01                  | Desktop     | [ccfb8336a0](https://bsd-hardware.info/?probe=ccfb8336a0) | Dec 01, 2021 |
| HP            | 843B                        | Desktop     | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| Apple         | Mac-F2218FA9                | All in one  | [7154bea350](https://bsd-hardware.info/?probe=7154bea350) | Nov 27, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [dc9d060c7f](https://bsd-hardware.info/?probe=dc9d060c7f) | Nov 27, 2021 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [339779baad](https://bsd-hardware.info/?probe=339779baad) | Nov 26, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [49a0a07721](https://bsd-hardware.info/?probe=49a0a07721) | Nov 25, 2021 |
| Supermicro    | X12SCZ-TLN4FA               | Server      | [3debb4fe22](https://bsd-hardware.info/?probe=3debb4fe22) | Nov 24, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [f922794063](https://bsd-hardware.info/?probe=f922794063) | Nov 22, 2021 |
| Apple         | Mac-F2218FA9                | All in one  | [1802f6c891](https://bsd-hardware.info/?probe=1802f6c891) | Nov 21, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [a26bc8f2b3](https://bsd-hardware.info/?probe=a26bc8f2b3) | Nov 14, 2021 |
| Gigabyte      | MRZNVMS-00                  | Desktop     | [817cb3e603](https://bsd-hardware.info/?probe=817cb3e603) | Nov 12, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b0a51ac0af](https://bsd-hardware.info/?probe=b0a51ac0af) | Nov 11, 2021 |
| Dell          | Studio 1747                 | Notebook    | [7ab6b58d69](https://bsd-hardware.info/?probe=7ab6b58d69) | Nov 11, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [970387f9d9](https://bsd-hardware.info/?probe=970387f9d9) | Nov 09, 2021 |
| Protectli     | FW6E                        | Desktop     | [ebe5b24dee](https://bsd-hardware.info/?probe=ebe5b24dee) | Nov 08, 2021 |
| Protectli     | FW6E                        | Desktop     | [6c12084410](https://bsd-hardware.info/?probe=6c12084410) | Nov 07, 2021 |
| Unknown       | Unknown                     | Firewall    | [053ec385f8](https://bsd-hardware.info/?probe=053ec385f8) | Nov 04, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [99b5ab3e42](https://bsd-hardware.info/?probe=99b5ab3e42) | Nov 04, 2021 |
| ASRock        | H370M-ITX/ac                | Desktop     | [bf37ad85e7](https://bsd-hardware.info/?probe=bf37ad85e7) | Nov 03, 2021 |
| Unknown       | Unknown                     | Desktop     | [579cf2ac1a](https://bsd-hardware.info/?probe=579cf2ac1a) | Oct 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7abc8386ec](https://bsd-hardware.info/?probe=7abc8386ec) | Oct 31, 2021 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [721ef0235c](https://bsd-hardware.info/?probe=721ef0235c) | Oct 30, 2021 |
| HP            | 843B                        | Desktop     | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [c3d6cddf87](https://bsd-hardware.info/?probe=c3d6cddf87) | Oct 25, 2021 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [9e254ab443](https://bsd-hardware.info/?probe=9e254ab443) | Oct 23, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [1d5e3e5bc3](https://bsd-hardware.info/?probe=1d5e3e5bc3) | Oct 22, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [3337c00433](https://bsd-hardware.info/?probe=3337c00433) | Oct 22, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [5c8f3708b1](https://bsd-hardware.info/?probe=5c8f3708b1) | Oct 21, 2021 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [93f9e34d05](https://bsd-hardware.info/?probe=93f9e34d05) | Oct 19, 2021 |
| Dell          | Studio 1747                 | Notebook    | [ca939fbe2f](https://bsd-hardware.info/?probe=ca939fbe2f) | Oct 19, 2021 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [b20953f2f4](https://bsd-hardware.info/?probe=b20953f2f4) | Oct 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [bbdfde368b](https://bsd-hardware.info/?probe=bbdfde368b) | Oct 18, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [1a5bae2227](https://bsd-hardware.info/?probe=1a5bae2227) | Oct 15, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [77101a00b3](https://bsd-hardware.info/?probe=77101a00b3) | Oct 11, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [cc419789f8](https://bsd-hardware.info/?probe=cc419789f8) | Oct 08, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | Desktop     | [00bafc5f7c](https://bsd-hardware.info/?probe=00bafc5f7c) | Oct 03, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| HP            | 1495                        | Desktop     | [36a5bc62bf](https://bsd-hardware.info/?probe=36a5bc62bf) | Sep 27, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [01e33c8399](https://bsd-hardware.info/?probe=01e33c8399) | Sep 26, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [ca41aa2f67](https://bsd-hardware.info/?probe=ca41aa2f67) | Sep 23, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [8dc995488e](https://bsd-hardware.info/?probe=8dc995488e) | Sep 13, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [3b709e37c2](https://bsd-hardware.info/?probe=3b709e37c2) | Sep 12, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [1feb22dc52](https://bsd-hardware.info/?probe=1feb22dc52) | Sep 12, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [0e81fce9eb](https://bsd-hardware.info/?probe=0e81fce9eb) | Sep 10, 2021 |
| HP            | 212B                        | Desktop     | [d3894b9f37](https://bsd-hardware.info/?probe=d3894b9f37) | Sep 10, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [df08c4e6d3](https://bsd-hardware.info/?probe=df08c4e6d3) | Sep 09, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [c64c51359c](https://bsd-hardware.info/?probe=c64c51359c) | Sep 09, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [e960bc2548](https://bsd-hardware.info/?probe=e960bc2548) | Sep 01, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [3dca10264a](https://bsd-hardware.info/?probe=3dca10264a) | Aug 29, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [70dc185964](https://bsd-hardware.info/?probe=70dc185964) | Aug 25, 2021 |
| HP            | 1589                        | Desktop     | [4d51cc9c4b](https://bsd-hardware.info/?probe=4d51cc9c4b) | Aug 24, 2021 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [da3e8986a3](https://bsd-hardware.info/?probe=da3e8986a3) | Aug 22, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [75f3efc215](https://bsd-hardware.info/?probe=75f3efc215) | Aug 18, 2021 |
| Supermicro    | X11SSW-F                    | Server      | [766c25105d](https://bsd-hardware.info/?probe=766c25105d) | Aug 17, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [bd94ad09ef](https://bsd-hardware.info/?probe=bd94ad09ef) | Aug 12, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | Desktop     | [94201b7633](https://bsd-hardware.info/?probe=94201b7633) | Aug 10, 2021 |
| HP            | Notebook                    | Notebook    | [a3c3297cd2](https://bsd-hardware.info/?probe=a3c3297cd2) | Aug 08, 2021 |
| HP            | Notebook                    | Notebook    | [0c316107a4](https://bsd-hardware.info/?probe=0c316107a4) | Aug 08, 2021 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [6da61be169](https://bsd-hardware.info/?probe=6da61be169) | Aug 08, 2021 |
| ZOTAC         | Board                       | Mini pc     | [e441e5484c](https://bsd-hardware.info/?probe=e441e5484c) | Aug 08, 2021 |
| IBM           | 00Y8494                     | Server      | [92ed5993f4](https://bsd-hardware.info/?probe=92ed5993f4) | Aug 07, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [535b577563](https://bsd-hardware.info/?probe=535b577563) | Aug 03, 2021 |
| HP            | ProLiant ML150 G6           | Desktop     | [783c2ba254](https://bsd-hardware.info/?probe=783c2ba254) | Aug 02, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [b434d9bfb8](https://bsd-hardware.info/?probe=b434d9bfb8) | Aug 02, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [4d118404a8](https://bsd-hardware.info/?probe=4d118404a8) | Jul 29, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [1c3ec31075](https://bsd-hardware.info/?probe=1c3ec31075) | Jul 28, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [fc13802cd3](https://bsd-hardware.info/?probe=fc13802cd3) | Jul 19, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [5697d53687](https://bsd-hardware.info/?probe=5697d53687) | Jul 19, 2021 |
| IBM           | 00Y8494                     | Server      | [76a17b83e5](https://bsd-hardware.info/?probe=76a17b83e5) | Jul 19, 2021 |
| Lenovo        | SHARKBAY 0C48431 PRO        | Desktop     | [0a1fa8924e](https://bsd-hardware.info/?probe=0a1fa8924e) | Jul 17, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [b86c2cfc99](https://bsd-hardware.info/?probe=b86c2cfc99) | Jul 16, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [4bd9c0bbb8](https://bsd-hardware.info/?probe=4bd9c0bbb8) | Jul 11, 2021 |
| PC Engines    | apu4                        | Desktop     | [51163b13ef](https://bsd-hardware.info/?probe=51163b13ef) | Jul 11, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [59a1b5f761](https://bsd-hardware.info/?probe=59a1b5f761) | Jul 10, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [f07b30b043](https://bsd-hardware.info/?probe=f07b30b043) | Jul 03, 2021 |
| Gigabyte      | MMLP3AP-00                  | Notebook    | [168e674b55](https://bsd-hardware.info/?probe=168e674b55) | Jul 03, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [d4f6eea56a](https://bsd-hardware.info/?probe=d4f6eea56a) | Jun 27, 2021 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [a326fd4061](https://bsd-hardware.info/?probe=a326fd4061) | Jun 20, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [ef7104e237](https://bsd-hardware.info/?probe=ef7104e237) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX H370-I GAMING     | Desktop     | [d2dd261a2a](https://bsd-hardware.info/?probe=d2dd261a2a) | Jun 20, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [6aa5f8046e](https://bsd-hardware.info/?probe=6aa5f8046e) | Jun 19, 2021 |
| Dell          | Inspiron 15-7579            | Notebook    | [4b8b5f7918](https://bsd-hardware.info/?probe=4b8b5f7918) | Jun 19, 2021 |
| Shuttle       | FS110                       | Desktop     | [9b4093c9a1](https://bsd-hardware.info/?probe=9b4093c9a1) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | Notebook    | [7db1345e97](https://bsd-hardware.info/?probe=7db1345e97) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | Notebook    | [cbade775b6](https://bsd-hardware.info/?probe=cbade775b6) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | Notebook    | [80052d6cdc](https://bsd-hardware.info/?probe=80052d6cdc) | Jun 15, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [34df628c87](https://bsd-hardware.info/?probe=34df628c87) | Jun 14, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [83cf0bb0fb](https://bsd-hardware.info/?probe=83cf0bb0fb) | Jun 12, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [d239ee4916](https://bsd-hardware.info/?probe=d239ee4916) | Jun 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [459bf008e9](https://bsd-hardware.info/?probe=459bf008e9) | Jun 12, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [d09c80b4d4](https://bsd-hardware.info/?probe=d09c80b4d4) | Jun 11, 2021 |
| HP            | 805D                        | Desktop     | [dc4e61ecd4](https://bsd-hardware.info/?probe=dc4e61ecd4) | Jun 07, 2021 |
| HP            | 8523 A01                    | Mini pc     | [d563d65a91](https://bsd-hardware.info/?probe=d563d65a91) | Jun 05, 2021 |
| HP            | 1998                        | Desktop     | [2806e1e8cf](https://bsd-hardware.info/?probe=2806e1e8cf) | Jun 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [95a281e2f8](https://bsd-hardware.info/?probe=95a281e2f8) | Jun 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [65dd81d59e](https://bsd-hardware.info/?probe=65dd81d59e) | Jun 02, 2021 |
| HP            | 8103 A01                    | Mini pc     | [93a434d951](https://bsd-hardware.info/?probe=93a434d951) | Jun 01, 2021 |
| Apple         | PowerBook5,2                | Notebook    | [8cc0aab53c](https://bsd-hardware.info/?probe=8cc0aab53c) | May 31, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [1cd4e4b333](https://bsd-hardware.info/?probe=1cd4e4b333) | May 28, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [5d64699270](https://bsd-hardware.info/?probe=5d64699270) | May 28, 2021 |
| HP            | 8103 A01                    | Mini pc     | [df43b9c68e](https://bsd-hardware.info/?probe=df43b9c68e) | May 26, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [fbfd0e7969](https://bsd-hardware.info/?probe=fbfd0e7969) | May 21, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [7e013ea910](https://bsd-hardware.info/?probe=7e013ea910) | May 20, 2021 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [ef5e9ec095](https://bsd-hardware.info/?probe=ef5e9ec095) | May 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [65f5931910](https://bsd-hardware.info/?probe=65f5931910) | May 18, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [1e9f399d73](https://bsd-hardware.info/?probe=1e9f399d73) | May 17, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [e6a555b397](https://bsd-hardware.info/?probe=e6a555b397) | May 17, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [109f3afa21](https://bsd-hardware.info/?probe=109f3afa21) | May 17, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [f92f43bc54](https://bsd-hardware.info/?probe=f92f43bc54) | May 17, 2021 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [33bc82e701](https://bsd-hardware.info/?probe=33bc82e701) | May 17, 2021 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [bf76401b74](https://bsd-hardware.info/?probe=bf76401b74) | May 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [f90e5f9566](https://bsd-hardware.info/?probe=f90e5f9566) | May 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [e67de92cb9](https://bsd-hardware.info/?probe=e67de92cb9) | May 14, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [273e379d9f](https://bsd-hardware.info/?probe=273e379d9f) | May 14, 2021 |
| Shuttle       | FS110                       | Desktop     | [e39173782f](https://bsd-hardware.info/?probe=e39173782f) | May 08, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [1f78fbb36c](https://bsd-hardware.info/?probe=1f78fbb36c) | May 08, 2021 |
| Dell          | Latitude 3440               | Notebook    | [3c8d21772a](https://bsd-hardware.info/?probe=3c8d21772a) | May 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5a128dd6a3](https://bsd-hardware.info/?probe=5a128dd6a3) | Apr 22, 2021 |
| HP            | 8523 A01                    | Mini pc     | [dde68fc65d](https://bsd-hardware.info/?probe=dde68fc65d) | Apr 22, 2021 |
| HP            | 18E7                        | Desktop     | [e6354de524](https://bsd-hardware.info/?probe=e6354de524) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7a6f106b0e](https://bsd-hardware.info/?probe=7a6f106b0e) | Apr 18, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [cd0467031a](https://bsd-hardware.info/?probe=cd0467031a) | Apr 17, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [5a1a372153](https://bsd-hardware.info/?probe=5a1a372153) | Apr 16, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [31a9bf167b](https://bsd-hardware.info/?probe=31a9bf167b) | Apr 16, 2021 |
| Dell          | 051FJ8 A01                  | Desktop     | [351b13fd3b](https://bsd-hardware.info/?probe=351b13fd3b) | Apr 15, 2021 |
| ASRock        | J4105M                      | Desktop     | [69165e1573](https://bsd-hardware.info/?probe=69165e1573) | Apr 13, 2021 |
| HP            | 8523 A01                    | Mini pc     | [f4e8e7e7e8](https://bsd-hardware.info/?probe=f4e8e7e7e8) | Apr 11, 2021 |
| HP            | 1495                        | Desktop     | [5aca6c03c1](https://bsd-hardware.info/?probe=5aca6c03c1) | Apr 09, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [5950dfc99a](https://bsd-hardware.info/?probe=5950dfc99a) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [0e814e53e9](https://bsd-hardware.info/?probe=0e814e53e9) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [817ec0a0da](https://bsd-hardware.info/?probe=817ec0a0da) | Apr 09, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [6f4f9fb14e](https://bsd-hardware.info/?probe=6f4f9fb14e) | Apr 07, 2021 |
| Dell          | 072XWF A01                  | Server      | [77f48d8337](https://bsd-hardware.info/?probe=77f48d8337) | Apr 07, 2021 |
| Dell          | Latitude 3440               | Notebook    | [7e85a38390](https://bsd-hardware.info/?probe=7e85a38390) | Apr 04, 2021 |
| HP            | 2AF7                        | Desktop     | [acd341147c](https://bsd-hardware.info/?probe=acd341147c) | Apr 03, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [39d86447b4](https://bsd-hardware.info/?probe=39d86447b4) | Mar 31, 2021 |
| Dell          | 0TTDMJ A00                  | Desktop     | [b5c0428c8a](https://bsd-hardware.info/?probe=b5c0428c8a) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [6af0a9bc78](https://bsd-hardware.info/?probe=6af0a9bc78) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [aaf140005c](https://bsd-hardware.info/?probe=aaf140005c) | Mar 30, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [636dfb334b](https://bsd-hardware.info/?probe=636dfb334b) | Mar 29, 2021 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [bb65d06888](https://bsd-hardware.info/?probe=bb65d06888) | Mar 28, 2021 |
| Gigabyte      | D525TUD                     | Desktop     | [a48a515986](https://bsd-hardware.info/?probe=a48a515986) | Mar 24, 2021 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [a951f7ffe4](https://bsd-hardware.info/?probe=a951f7ffe4) | Mar 24, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [9b84d1e7e6](https://bsd-hardware.info/?probe=9b84d1e7e6) | Mar 24, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [cf4b3e0c6f](https://bsd-hardware.info/?probe=cf4b3e0c6f) | Mar 23, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [4a59793120](https://bsd-hardware.info/?probe=4a59793120) | Mar 23, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [7280d52eff](https://bsd-hardware.info/?probe=7280d52eff) | Mar 23, 2021 |
| Lenovo        | 30D9 No DPK                 | Desktop     | [061ad76c0e](https://bsd-hardware.info/?probe=061ad76c0e) | Mar 20, 2021 |
| Dell          | Inspiron 7370               | Notebook    | [7e2328dda3](https://bsd-hardware.info/?probe=7e2328dda3) | Mar 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [03935b2745](https://bsd-hardware.info/?probe=03935b2745) | Mar 20, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [27cb6a75c8](https://bsd-hardware.info/?probe=27cb6a75c8) | Mar 19, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [8964a02114](https://bsd-hardware.info/?probe=8964a02114) | Mar 15, 2021 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [b13ee482e8](https://bsd-hardware.info/?probe=b13ee482e8) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [f46146b79e](https://bsd-hardware.info/?probe=f46146b79e) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [c1ed4c02b8](https://bsd-hardware.info/?probe=c1ed4c02b8) | Mar 11, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [e9ca160a2d](https://bsd-hardware.info/?probe=e9ca160a2d) | Mar 11, 2021 |
| Shuttle       | FS110                       | Desktop     | [fc31311d01](https://bsd-hardware.info/?probe=fc31311d01) | Mar 10, 2021 |
| Unknown       | Unknown                     | Firewall    | [7b7714416c](https://bsd-hardware.info/?probe=7b7714416c) | Mar 09, 2021 |
| Alienware     | 14                          | Notebook    | [0e0cdf952a](https://bsd-hardware.info/?probe=0e0cdf952a) | Mar 06, 2021 |
| Supermicro    | A2SDi-TP8F                  | Desktop     | [c30d805062](https://bsd-hardware.info/?probe=c30d805062) | Mar 05, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [c7b0539b99](https://bsd-hardware.info/?probe=c7b0539b99) | Mar 02, 2021 |
| IBM           | 94Y7614                     | Server      | [7515ccaa7a](https://bsd-hardware.info/?probe=7515ccaa7a) | Mar 01, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [48dfa4a5f6](https://bsd-hardware.info/?probe=48dfa4a5f6) | Mar 01, 2021 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [fc4265eb19](https://bsd-hardware.info/?probe=fc4265eb19) | Feb 24, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [9d35f9e853](https://bsd-hardware.info/?probe=9d35f9e853) | Feb 24, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [dbf040e5a8](https://bsd-hardware.info/?probe=dbf040e5a8) | Feb 22, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [11d6c98009](https://bsd-hardware.info/?probe=11d6c98009) | Feb 21, 2021 |
| Toshiba       | Satellite U500              | Notebook    | [feae098542](https://bsd-hardware.info/?probe=feae098542) | Feb 20, 2021 |
| Protectli     | FW6                         | Desktop     | [b656792690](https://bsd-hardware.info/?probe=b656792690) | Feb 20, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [cfd1824b40](https://bsd-hardware.info/?probe=cfd1824b40) | Feb 18, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [4c7959ac6e](https://bsd-hardware.info/?probe=4c7959ac6e) | Feb 17, 2021 |
| Gigabyte      | MRZNVMS-00                  | Desktop     | [b51cb672a4](https://bsd-hardware.info/?probe=b51cb672a4) | Feb 12, 2021 |
| Lenovo        | ThinkPad T410 253722U       | Notebook    | [219e9cb1d7](https://bsd-hardware.info/?probe=219e9cb1d7) | Feb 10, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3402eabdbf](https://bsd-hardware.info/?probe=3402eabdbf) | Feb 09, 2021 |
| Intel         | H81U                        | Notebook    | [efb1f9d207](https://bsd-hardware.info/?probe=efb1f9d207) | Feb 07, 2021 |
| Lenovo        | 314D SDK0J40700 WIN 3258... | Mini pc     | [5a5119a395](https://bsd-hardware.info/?probe=5a5119a395) | Feb 06, 2021 |
| ASRock        | Z270M-ITX/ac                | Desktop     | [9b50d422e3](https://bsd-hardware.info/?probe=9b50d422e3) | Feb 04, 2021 |
| Supermicro    | X8DT6                       | Server      | [6acb4d8445](https://bsd-hardware.info/?probe=6acb4d8445) | Feb 04, 2021 |
| HP            | 0AECh D                     | Desktop     | [6dde87584c](https://bsd-hardware.info/?probe=6dde87584c) | Feb 04, 2021 |
| HP            | 829A                        | Mini pc     | [ede207c6df](https://bsd-hardware.info/?probe=ede207c6df) | Feb 04, 2021 |
| PC Engines    | apu4                        | Desktop     | [18dfb34a97](https://bsd-hardware.info/?probe=18dfb34a97) | Feb 04, 2021 |
| HP            | 3397                        | Desktop     | [cda4af23ee](https://bsd-hardware.info/?probe=cda4af23ee) | Feb 03, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [0a48224f4b](https://bsd-hardware.info/?probe=0a48224f4b) | Feb 03, 2021 |
| HP            | 3397                        | Desktop     | [65f1db2a70](https://bsd-hardware.info/?probe=65f1db2a70) | Feb 03, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [efe09d459a](https://bsd-hardware.info/?probe=efe09d459a) | Jan 31, 2021 |
| Dell          | 086HF8 A08                  | Server      | [1d5c769e0f](https://bsd-hardware.info/?probe=1d5c769e0f) | Jan 31, 2021 |
| HP            | 82B4                        | Desktop     | [faf58d8f87](https://bsd-hardware.info/?probe=faf58d8f87) | Jan 30, 2021 |
| Lenovo        | 30D9 No DPK                 | Desktop     | [12056c71ad](https://bsd-hardware.info/?probe=12056c71ad) | Jan 30, 2021 |
| PC Engines    | APU2                        | Desktop     | [7e96c61bf9](https://bsd-hardware.info/?probe=7e96c61bf9) | Jan 30, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [0147020401](https://bsd-hardware.info/?probe=0147020401) | Jan 30, 2021 |
| ASRock        | J3455-ITX                   | Desktop     | [65bde09c13](https://bsd-hardware.info/?probe=65bde09c13) | Jan 26, 2021 |
| ASRock        | J3455-ITX                   | Desktop     | [0a4d4fc896](https://bsd-hardware.info/?probe=0a4d4fc896) | Jan 25, 2021 |
| Dell          | 086HF8 A08                  | Server      | [f2eb601b2a](https://bsd-hardware.info/?probe=f2eb601b2a) | Jan 25, 2021 |
| ASRock        | J3355B-ITX                  | Desktop     | [e8496a6202](https://bsd-hardware.info/?probe=e8496a6202) | Jan 24, 2021 |
| PC Engines    | APU2                        | Desktop     | [da6e3cd1a6](https://bsd-hardware.info/?probe=da6e3cd1a6) | Jan 23, 2021 |
| Supermicro    | X8DT6                       | Server      | [b24cc06305](https://bsd-hardware.info/?probe=b24cc06305) | Jan 22, 2021 |
| PC Engines    | APU2                        | Desktop     | [3d536a42eb](https://bsd-hardware.info/?probe=3d536a42eb) | Jan 21, 2021 |
| PC Engines    | APU2                        | Desktop     | [043446a653](https://bsd-hardware.info/?probe=043446a653) | Jan 21, 2021 |
| Shuttle       | FS110                       | Desktop     | [fed17a1f77](https://bsd-hardware.info/?probe=fed17a1f77) | Jan 21, 2021 |
| Supermicro    | X8DTH                       | Server      | [9ea2aeeb86](https://bsd-hardware.info/?probe=9ea2aeeb86) | Jan 20, 2021 |
| Supermicro    | X8STi                       | Desktop     | [7cda964f76](https://bsd-hardware.info/?probe=7cda964f76) | Jan 20, 2021 |
| Dell          | 0M9KCM A02                  | Desktop     | [1cc5f6a07b](https://bsd-hardware.info/?probe=1cc5f6a07b) | Jan 20, 2021 |
| Dell          | 086HF8 A08                  | Server      | [b087a1d9d2](https://bsd-hardware.info/?probe=b087a1d9d2) | Jan 20, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [8c55004504](https://bsd-hardware.info/?probe=8c55004504) | Jan 19, 2021 |
| Intel         | S1200RP_SE G62252-406       | Server      | [49ad4461dc](https://bsd-hardware.info/?probe=49ad4461dc) | Jan 16, 2021 |
| Supermicro    | C7Z170-OCEB                 | Server      | [9f6632de8b](https://bsd-hardware.info/?probe=9f6632de8b) | Jan 10, 2021 |
| Supermicro    | X7SLA                       | Desktop     | [2d31f38bf0](https://bsd-hardware.info/?probe=2d31f38bf0) | Jan 10, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [834cb6c68a](https://bsd-hardware.info/?probe=834cb6c68a) | Jan 10, 2021 |
| Alienware     | 14                          | Notebook    | [dd2cc000a7](https://bsd-hardware.info/?probe=dd2cc000a7) | Jan 07, 2021 |
| Alienware     | 14                          | Notebook    | [48f61623f2](https://bsd-hardware.info/?probe=48f61623f2) | Jan 07, 2021 |
| MSI           | X58 Pro-E                   | Desktop     | [bd108f94d5](https://bsd-hardware.info/?probe=bd108f94d5) | Jan 02, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [11011ecee1](https://bsd-hardware.info/?probe=11011ecee1) | Jan 02, 2021 |
| HP            | 212B                        | Desktop     | [7fe9d2c508](https://bsd-hardware.info/?probe=7fe9d2c508) | Dec 18, 2020 |
| Dell          | 0GM819                      | Desktop     | [adc8eb1931](https://bsd-hardware.info/?probe=adc8eb1931) | Dec 18, 2020 |
| HP            | 805D                        | Desktop     | [dc62857275](https://bsd-hardware.info/?probe=dc62857275) | Dec 17, 2020 |
| Supermicro    | X8STi                       | Desktop     | [80c2762cfb](https://bsd-hardware.info/?probe=80c2762cfb) | Dec 16, 2020 |
| ASRockRack    | D1541D4U-2O8R               | Desktop     | [d59d8a3b6d](https://bsd-hardware.info/?probe=d59d8a3b6d) | Dec 16, 2020 |
| Supermicro    | X11SSH-F                    | Desktop     | [ebb920c0c4](https://bsd-hardware.info/?probe=ebb920c0c4) | Dec 16, 2020 |
| MSI           | X99S SLI PLUS               | Desktop     | [9b2421d9d5](https://bsd-hardware.info/?probe=9b2421d9d5) | Nov 28, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5d5ecb38cd](https://bsd-hardware.info/?probe=5d5ecb38cd) | Nov 25, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [002b408f7e](https://bsd-hardware.info/?probe=002b408f7e) | Nov 18, 2020 |
| Lenovo        | ThinkPad T440 20B7S0A800    | Notebook    | [d3474f1ca3](https://bsd-hardware.info/?probe=d3474f1ca3) | Nov 18, 2020 |
| Dell          | 0YFVT1 A06                  | Server      | [fd37374e7b](https://bsd-hardware.info/?probe=fd37374e7b) | Nov 11, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | Notebook    | [6a0f910601](https://bsd-hardware.info/?probe=6a0f910601) | Nov 10, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | Notebook    | [6dca4cdd18](https://bsd-hardware.info/?probe=6dca4cdd18) | Nov 10, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [714b6539cf](https://bsd-hardware.info/?probe=714b6539cf) | Nov 07, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [9f871ab960](https://bsd-hardware.info/?probe=9f871ab960) | Nov 01, 2020 |
| Intel         | X79 V2.81A                  | Desktop     | [d5b4cdf28a](https://bsd-hardware.info/?probe=d5b4cdf28a) | Oct 30, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [59c940d739](https://bsd-hardware.info/?probe=59c940d739) | Oct 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [8552669e76](https://bsd-hardware.info/?probe=8552669e76) | Oct 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [50966c2f83](https://bsd-hardware.info/?probe=50966c2f83) | Oct 30, 2020 |
| Dell          | 0YFVT1 A06                  | Server      | [fca49dda17](https://bsd-hardware.info/?probe=fca49dda17) | Oct 29, 2020 |
| ADI Engine... | RCC-VE                      | Desktop     | [30440abc03](https://bsd-hardware.info/?probe=30440abc03) | Oct 29, 2020 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [c41d989a06](https://bsd-hardware.info/?probe=c41d989a06) | Oct 28, 2020 |
| IBM           | Board                       | Desktop     | [11b0b7012f](https://bsd-hardware.info/?probe=11b0b7012f) | Oct 21, 2020 |
| IBM           | Board                       | Desktop     | [a92c08a920](https://bsd-hardware.info/?probe=a92c08a920) | Oct 21, 2020 |
| IBM           | Board                       | Desktop     | [80d5f15a63](https://bsd-hardware.info/?probe=80d5f15a63) | Oct 21, 2020 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [f287de215c](https://bsd-hardware.info/?probe=f287de215c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [f846609c80](https://bsd-hardware.info/?probe=f846609c80) | Oct 20, 2020 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [feb1da0406](https://bsd-hardware.info/?probe=feb1da0406) | Oct 20, 2020 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [efece2abf7](https://bsd-hardware.info/?probe=efece2abf7) | Oct 20, 2020 |
| ASUSTek       | 1000HE                      | Notebook    | [621df26e0c](https://bsd-hardware.info/?probe=621df26e0c) | Oct 19, 2020 |
| Lenovo        | ThinkPad T460 20FMS1BC01    | Notebook    | [bf6d6d155b](https://bsd-hardware.info/?probe=bf6d6d155b) | Oct 19, 2020 |
| Lenovo        | ThinkPad E495 20NE0001US    | Notebook    | [a1fc75a9b7](https://bsd-hardware.info/?probe=a1fc75a9b7) | Oct 09, 2020 |
| MSI           | MS-7250                     | Desktop     | [41e2d9dab3](https://bsd-hardware.info/?probe=41e2d9dab3) | Sep 04, 2020 |
| HP            | Pavilion dv6500             | Notebook    | [316ffb0740](https://bsd-hardware.info/?probe=316ffb0740) | Sep 04, 2020 |
| HP            | 3031h                       | Desktop     | [1f2695b3a7](https://bsd-hardware.info/?probe=1f2695b3a7) | Aug 25, 2020 |
| Acer          | AOD270                      | Notebook    | [41d2974f13](https://bsd-hardware.info/?probe=41d2974f13) | Aug 20, 2020 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [515042ff2d](https://bsd-hardware.info/?probe=515042ff2d) | Aug 20, 2020 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [7f6095b266](https://bsd-hardware.info/?probe=7f6095b266) | Aug 20, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [e568f0f32e](https://bsd-hardware.info/?probe=e568f0f32e) | Aug 04, 2020 |
| ASUSTek       | Z170-P                      | Desktop     | [49e01a949b](https://bsd-hardware.info/?probe=49e01a949b) | Jul 29, 2020 |
| ASUSTek       | K52JK                       | Notebook    | [d5d32f1334](https://bsd-hardware.info/?probe=d5d32f1334) | Jun 29, 2020 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [0f7697b73a](https://bsd-hardware.info/?probe=0f7697b73a) | May 28, 2020 |
| Dell          | 0T10XW A02                  | Desktop     | [81f39f3061](https://bsd-hardware.info/?probe=81f39f3061) | May 28, 2020 |
| Lenovo        | ThinkPad T420 4180B39       | Notebook    | [05ed5eb1e4](https://bsd-hardware.info/?probe=05ed5eb1e4) | May 25, 2020 |
| Lenovo        | ThinkPad X270 20HNCTO1WW    | Notebook    | [7def094afb](https://bsd-hardware.info/?probe=7def094afb) | May 23, 2020 |
| ASUSTek       | K52JK                       | Notebook    | [6a6b06fc67](https://bsd-hardware.info/?probe=6a6b06fc67) | May 23, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OpenBSD 7.2       | 17        | 2.94%   |
| helloSystem 0.7.0 | 17        | 2.94%   |
| OPNsense 23.1     | 14        | 2.42%   |
| OPNsense 22.7.10  | 14        | 2.42%   |
| OpenBSD 7.3       | 14        | 2.42%   |
| OpenBSD 7.1       | 13        | 2.25%   |
| OPNsense 23.1.6   | 12        | 2.08%   |
| OPNsense 23.1.1   | 12        | 2.08%   |
| OPNsense 22.1.10  | 12        | 2.08%   |
| OPNsense 21.1.4   | 12        | 2.08%   |
| OPNsense 21.1     | 12        | 2.08%   |
| helloSystem 0.5.0 | 11        | 1.9%    |
| OPNsense 22.7.8   | 10        | 1.73%   |
| OPNsense 22.7.4   | 10        | 1.73%   |
| OPNsense 22.1.7   | 10        | 1.73%   |
| OPNsense 22.1.6   | 10        | 1.73%   |
| OPNsense 21.1.3   | 10        | 1.73%   |
| FreeBSD 13.1-p5   | 10        | 1.73%   |
| OPNsense 22.7     | 9         | 1.56%   |
| OPNsense 22.1     | 9         | 1.56%   |
| OPNsense 21.1.6   | 9         | 1.56%   |
| OpenBSD 7.0       | 9         | 1.56%   |
| OpenBSD 6.9       | 9         | 1.56%   |
| helloSystem 0.8.1 | 9         | 1.56%   |
| FreeBSD 12.2      | 9         | 1.56%   |
| OPNsense 22.1.8   | 8         | 1.38%   |
| OPNsense 21.7.7   | 8         | 1.38%   |
| OPNsense 21.7.1   | 8         | 1.38%   |
| OPNsense 21.1.5   | 8         | 1.38%   |
| OpenBSD 6.8       | 8         | 1.38%   |
| helloSystem 0.8.0 | 8         | 1.38%   |
| OPNsense 23.1.9   | 7         | 1.21%   |
| OPNsense 22.7.9   | 7         | 1.21%   |
| OPNsense 21.7     | 7         | 1.21%   |
| FreeBSD 13.1      | 7         | 1.21%   |
| FreeBSD 13.0      | 7         | 1.21%   |
| OPNsense 22.7.11  | 6         | 1.04%   |
| OPNsense 21.7.8   | 6         | 1.04%   |
| OPNsense 21.7.3   | 6         | 1.04%   |
| OPNsense 21.1.1   | 6         | 1.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 229       | 56.82%  |
| FreeBSD     | 88        | 21.84%  |
| helloSystem | 47        | 11.66%  |
| OpenBSD     | 25        | 6.2%    |
| GhostBSD    | 6         | 1.49%   |
| FreeNAS     | 3         | 0.74%   |
| TrueNAS     | 2         | 0.5%    |
| pfSense     | 1         | 0.25%   |
| NetBSD      | 1         | 0.25%   |
| MyBee       | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 392       | 98%     |
| i386   | 5         | 1.25%   |
| macppc | 2         | 0.5%    |
| arm64  | 1         | 0.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 268       | 64.89%  |
| helloDesktop | 65        | 15.74%  |
| XFCE         | 19        | 4.6%    |
| KDE5         | 13        | 3.15%   |
| fvwm         | 12        | 2.91%   |
| MATE         | 8         | 1.94%   |
| GNOME        | 7         | 1.69%   |
| TWM          | 5         | 1.21%   |
| Openbox      | 3         | 0.73%   |
| Cinnamon     | 3         | 0.73%   |
| LXQt         | 2         | 0.48%   |
| i3           | 2         | 0.48%   |
| X-Cinnamon   | 1         | 0.24%   |
| Window Maker | 1         | 0.24%   |
| LXDE         | 1         | 0.24%   |
| Lumina       | 1         | 0.24%   |
| Fluxbox      | 1         | 0.24%   |
| DWM          | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 268       | 67%     |
| X11     | 130       | 32.5%   |
| Wayland | 2         | 0.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 309       | 76.3%   |
| SLiM    | 52        | 12.84%  |
| SDDM    | 17        | 4.2%    |
| XDM     | 10        | 2.47%   |
| LightDM | 10        | 2.47%   |
| GDM     | 6         | 1.48%   |
| Ly      | 1         | 0.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 279       | 68.72%  |
| en_US   | 62        | 15.27%  |
| C       | 42        | 10.34%  |
| en_CA   | 11        | 2.71%   |
| fr_FR   | 5         | 1.23%   |
| en      | 3         | 0.74%   |
| fr      | 2         | 0.49%   |
| fr_CA   | 1         | 0.25%   |
| en_NL   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 326       | 80.49%  |
| BIOS | 79        | 19.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 203       | 49.03%  |
| Zfs     | 165       | 39.86%  |
| Ffs     | 25        | 6.04%   |
| Cd9660  | 20        | 4.83%   |
| Unknown | 1         | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 361       | 90.25%  |
| MBR     | 35        | 8.75%   |
| Unknown | 4         | 1%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell                           | 51        | 12.75%  |
| Hewlett-Packard                | 47        | 11.75%  |
| Lenovo                         | 46        | 11.5%   |
| ASUSTek Computer               | 37        | 9.25%   |
| Intel                          | 26        | 6.5%    |
| Unknown                        | 26        | 6.5%    |
| Supermicro                     | 22        | 5.5%    |
| Protectli                      | 19        | 4.75%   |
| Gigabyte Technology            | 15        | 3.75%   |
| MSI                            | 12        | 3%      |
| ASRock                         | 12        | 3%      |
| Acer                           | 9         | 2.25%   |
| Techvision                     | 6         | 1.5%    |
| AMI                            | 6         | 1.5%    |
| PC Engines                     | 5         | 1.25%   |
| AWOW                           | 5         | 1.25%   |
| Apple                          | 5         | 1.25%   |
| ZOTAC                          | 4         | 1%      |
| AZW                            | 4         | 1%      |
| Toshiba                        | 3         | 0.75%   |
| Panasonic                      | 3         | 0.75%   |
| IBM                            | 3         | 0.75%   |
| Sophos                         | 2         | 0.5%    |
| Matsushita Electric Industrial | 2         | 0.5%    |
| Google                         | 2         | 0.5%    |
| ASRockRack                     | 2         | 0.5%    |
| Alienware                      | 2         | 0.5%    |
| Yanling                        | 1         | 0.25%   |
| Shuttle                        | 1         | 0.25%   |
| ShenZhen MinWin Technology     | 1         | 0.25%   |
| SeeedStudio                    | 1         | 0.25%   |
| ReachingTech                   | 1         | 0.25%   |
| Raspberry Pi Foundation        | 1         | 0.25%   |
| Quanta                         | 1         | 0.25%   |
| Pegatron                       | 1         | 0.25%   |
| MiTAC                          | 1         | 0.25%   |
| LG Electronics                 | 1         | 0.25%   |
| iBASE                          | 1         | 0.25%   |
| HPE                            | 1         | 0.25%   |
| HARDKERNEL                     | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 26        | 6.5%    |
| Protectli FW4B                     | 11        | 2.75%   |
| Techvision TVI7309X                | 6         | 1.5%    |
| Intel Q3XXG4-P V1.0                | 6         | 1.5%    |
| Supermicro Super Server            | 5         | 1.25%   |
| Protectli FW6                      | 5         | 1.25%   |
| AWOW PC BOX                        | 5         | 1.25%   |
| Intel NDISB533                     | 4         | 1%      |
| HP EliteDesk 800 G1 SFF            | 4         | 1%      |
| Dell OptiPlex 9010                 | 4         | 1%      |
| AMI Aptio CRB                      | 4         | 1%      |
| Intel H81U                         | 3         | 0.75%   |
| HP Z440 Workstation                | 3         | 0.75%   |
| HP t730 Thin Client                | 3         | 0.75%   |
| HP Compaq 8200 Elite SFF PC        | 3         | 0.75%   |
| HP Compaq 6200 Pro MT PC           | 3         | 0.75%   |
| Dell OptiPlex 7010                 | 3         | 0.75%   |
| ASUS All Series                    | 3         | 0.75%   |
| Supermicro X8STi                   | 2         | 0.5%    |
| PC Engines apu4                    | 2         | 0.5%    |
| PC Engines APU2                    | 2         | 0.5%    |
| MSI MS-7A40                        | 2         | 0.5%    |
| Lenovo ThinkCentre M93p 10A8S16X0J | 2         | 0.5%    |
| Intel CRESCENTBAY                  | 2         | 0.5%    |
| HP Compaq Elite 8300 SFF           | 2         | 0.5%    |
| Dell Precision WorkStation T3500   | 2         | 0.5%    |
| Dell Precision Tower 5810          | 2         | 0.5%    |
| Dell PowerEdge R210 II             | 2         | 0.5%    |
| Dell PowerEdge R210                | 2         | 0.5%    |
| Dell OptiPlex 7050                 | 2         | 0.5%    |
| Dell OptiPlex 7020                 | 2         | 0.5%    |
| Dell OptiPlex 3020                 | 2         | 0.5%    |
| Dell G5 5090                       | 2         | 0.5%    |
| AZW U59                            | 2         | 0.5%    |
| ASUS P8H77-I                       | 2         | 0.5%    |
| ASUS M5A97 PLUS                    | 2         | 0.5%    |
| ASRock H110M-DGS R3.0              | 2         | 0.5%    |
| ASRock B450M Pro4                  | 2         | 0.5%    |
| ZOTAC ZBOX-CI341                   | 1         | 0.25%   |
| ZOTAC ZBOX-CI329NANO               | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 26        | 6.5%    |
| Lenovo ThinkPad     | 23        | 5.75%   |
| Dell OptiPlex       | 21        | 5.25%   |
| Lenovo ThinkCentre  | 20        | 5%      |
| Dell PowerEdge      | 12        | 3%      |
| Protectli FW4B      | 11        | 2.75%   |
| HP Compaq           | 10        | 2.5%    |
| ASUS PRIME          | 8         | 2%      |
| HP ProDesk          | 7         | 1.75%   |
| HP EliteDesk        | 7         | 1.75%   |
| Techvision TVI7309X | 6         | 1.5%    |
| Intel Q3XXG4-P      | 6         | 1.5%    |
| Acer Aspire         | 6         | 1.5%    |
| Supermicro Super    | 5         | 1.25%   |
| Protectli FW6       | 5         | 1.25%   |
| Dell Precision      | 5         | 1.25%   |
| Dell Inspiron       | 5         | 1.25%   |
| AWOW PC             | 5         | 1.25%   |
| ASUS ROG            | 5         | 1.25%   |
| Intel NDISB533      | 4         | 1%      |
| AMI Aptio           | 4         | 1%      |
| Intel H81U          | 3         | 0.75%   |
| HP Z440             | 3         | 0.75%   |
| HP t730             | 3         | 0.75%   |
| HP ProLiant         | 3         | 0.75%   |
| HP Pavilion         | 3         | 0.75%   |
| Dell Latitude       | 3         | 0.75%   |
| ASUS TUF            | 3         | 0.75%   |
| ASUS All            | 3         | 0.75%   |
| ASRock B450M        | 3         | 0.75%   |
| Toshiba Satellite   | 2         | 0.5%    |
| Supermicro X8STi    | 2         | 0.5%    |
| PC Engines apu4     | 2         | 0.5%    |
| PC Engines APU2     | 2         | 0.5%    |
| MSI MS-7A40         | 2         | 0.5%    |
| Intel CRESCENTBAY   | 2         | 0.5%    |
| IBM System          | 2         | 0.5%    |
| HP t620             | 2         | 0.5%    |
| Dell G5             | 2         | 0.5%    |
| AZW U59             | 2         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 49        | 12.25%  |
| 2020    | 41        | 10.25%  |
| 2022    | 39        | 9.75%   |
| 2014    | 34        | 8.5%    |
| 2019    | 31        | 7.75%   |
| 2016    | 26        | 6.5%    |
| 2011    | 24        | 6%      |
| 2010    | 24        | 6%      |
| 2013    | 23        | 5.75%   |
| 2015    | 22        | 5.5%    |
| 2021    | 20        | 5%      |
| 2012    | 20        | 5%      |
| 2017    | 15        | 3.75%   |
| 2009    | 13        | 3.25%   |
| 2008    | 6         | 1.5%    |
| 2023    | 5         | 1.25%   |
| Unknown | 4         | 1%      |
| 2006    | 2         | 0.5%    |
| 2007    | 1         | 0.25%   |
| 2002    | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 255       | 63.75%  |
| Notebook       | 75        | 18.75%  |
| Mini pc        | 33        | 8.25%   |
| Server         | 29        | 7.25%   |
| Firewall       | 4         | 1%      |
| All in one     | 3         | 0.75%   |
| System on chip | 1         | 0.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 389       | 97.25%  |
| Yes  | 11        | 2.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 150       | 36.67%  |
| 16.01-24.0      | 85        | 20.78%  |
| 4.01-8.0        | 76        | 18.58%  |
| 32.01-64.0      | 44        | 10.76%  |
| 64.01-256.0     | 20        | 4.89%   |
| 2.01-3.0        | 12        | 2.93%   |
| 3.01-4.0        | 8         | 1.96%   |
| 24.01-32.0      | 7         | 1.71%   |
| 1.01-2.0        | 3         | 0.73%   |
| 0.51-1.0        | 3         | 0.73%   |
| More than 256.0 | 1         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 206       | 50.12%  |
| 0.51-1.0    | 119       | 28.95%  |
| 1.01-2.0    | 50        | 12.17%  |
| 2.01-3.0    | 9         | 2.19%   |
| 4.01-8.0    | 8         | 1.95%   |
| 3.01-4.0    | 6         | 1.46%   |
| 0           | 4         | 0.97%   |
| 24.01-32.0  | 3         | 0.73%   |
| 64.01-256.0 | 2         | 0.49%   |
| 8.01-16.0   | 2         | 0.49%   |
| 32.01-64.0  | 1         | 0.24%   |
| Unknown     | 1         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 280       | 68.46%  |
| 2      | 59        | 14.43%  |
| 0      | 30        | 7.33%   |
| 3      | 19        | 4.65%   |
| 4      | 9         | 2.2%    |
| 7      | 2         | 0.49%   |
| 5      | 2         | 0.49%   |
| 58     | 1         | 0.24%   |
| 40     | 1         | 0.24%   |
| 25     | 1         | 0.24%   |
| 16     | 1         | 0.24%   |
| 14     | 1         | 0.24%   |
| 13     | 1         | 0.24%   |
| 10     | 1         | 0.24%   |
| 6      | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 317       | 77.89%  |
| Yes       | 90        | 22.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 390       | 97.26%  |
| No        | 11        | 2.74%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 262       | 64.69%  |
| Yes       | 143       | 35.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 296       | 73.45%  |
| Yes       | 107       | 26.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Canada  | 400       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Montreal          | 51        | 11.46%  |
| Toronto           | 40        | 8.99%   |
| Calgary           | 23        | 5.17%   |
| Ottawa            | 18        | 4.04%   |
| Victoria          | 17        | 3.82%   |
| Edmonton          | 16        | 3.6%    |
| Vancouver         | 14        | 3.15%   |
| Saint-Laurent     | 14        | 3.15%   |
| Brampton          | 11        | 2.47%   |
| Winnipeg          | 10        | 2.25%   |
| Kitchener         | 10        | 2.25%   |
| Surrey            | 9         | 2.02%   |
| QuГ©bec         | 6         | 1.35%   |
| Regina            | 5         | 1.12%   |
| Québec           | 5         | 1.12%   |
| Cambridge         | 5         | 1.12%   |
| St. Jean Baptiste | 4         | 0.9%    |
| St. Albert        | 4         | 0.9%    |
| Saskatoon         | 4         | 0.9%    |
| Sainte-Julie      | 4         | 0.9%    |
| Peterborough      | 4         | 0.9%    |
| Moncton           | 4         | 0.9%    |
| London            | 4         | 0.9%    |
| Laval             | 4         | 0.9%    |
| Gatineau          | 4         | 0.9%    |
| Burnaby           | 4         | 0.9%    |
| Windsor           | 3         | 0.67%   |
| Sherwood Park     | 3         | 0.67%   |
| Sarnia            | 3         | 0.67%   |
| QuÃ©bec         | 3         | 0.67%   |
| Pierrefonds       | 3         | 0.67%   |
| Oakville          | 3         | 0.67%   |
| Nanaimo           | 3         | 0.67%   |
| Mississauga       | 3         | 0.67%   |
| Maple Ridge       | 3         | 0.67%   |
| Langley           | 3         | 0.67%   |
| Lamont            | 3         | 0.67%   |
| Kingston          | 3         | 0.67%   |
| Kingsburg         | 3         | 0.67%   |
| Kanata            | 3         | 0.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 72        | 123    | 15.29%  |
| WDC                 | 71        | 188    | 15.07%  |
| Kingston            | 54        | 68     | 11.46%  |
| Seagate             | 52        | 107    | 11.04%  |
| Intel               | 21        | 34     | 4.46%   |
| Crucial             | 19        | 26     | 4.03%   |
| Toshiba             | 16        | 30     | 3.4%    |
| A-DATA Technology   | 16        | 29     | 3.4%    |
| SanDisk             | 13        | 17     | 2.76%   |
| Hitachi             | 13        | 56     | 2.76%   |
| Dogfish             | 8         | 21     | 1.7%    |
| SPCC                | 7         | 7      | 1.49%   |
| FORESEE             | 7         | 21     | 1.49%   |
| Transcend           | 6         | 7      | 1.27%   |
| SK hynix            | 6         | 8      | 1.27%   |
| Patriot             | 6         | 7      | 1.27%   |
| OCZ                 | 6         | 10     | 1.27%   |
| Micron Technology   | 6         | 9      | 1.27%   |
| Hewlett-Packard     | 6         | 6      | 1.27%   |
| HGST                | 5         | 75     | 1.06%   |
| NVMe                | 4         | 5      | 0.85%   |
| Mushkin             | 4         | 4      | 0.85%   |
| Hoodisk             | 4         | 5      | 0.85%   |
| BIWIN               | 4         | 5      | 0.85%   |
| PNY                 | 3         | 4      | 0.64%   |
| Phison              | 3         | 4      | 0.64%   |
| Lexar               | 3         | 4      | 0.64%   |
| VisionTek           | 2         | 6      | 0.42%   |
| Timetec             | 2         | 2      | 0.42%   |
| Silicon Motion      | 2         | 2      | 0.42%   |
| Protectli           | 2         | 3      | 0.42%   |
| Netac               | 2         | 2      | 0.42%   |
| HPE                 | 2         | 9      | 0.42%   |
| Fujitsu             | 2         | 2      | 0.42%   |
| Corsair             | 2         | 4      | 0.42%   |
| China               | 2         | 4      | 0.42%   |
| Apacer              | 2         | 2      | 0.42%   |
| ZTC                 | 1         | 1      | 0.21%   |
| XPG                 | 1         | 1      | 0.21%   |
| walram              | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB     | 15        | 2.93%   |
| Kingston SA400S37120G 120GB     | 12        | 2.34%   |
| Seagate ST1000DM010-2EP102 1TB  | 6         | 1.17%   |
| Samsung SSD 850 EVO 250GB       | 6         | 1.17%   |
| FORESEE 128GB SSD               | 6         | 1.17%   |
| Seagate ST500DM002-1BD142 500GB | 5         | 0.98%   |
| Seagate ST2000DM008-2FR102 2TB  | 5         | 0.98%   |
| Samsung SSD 860 EVO 500GB       | 5         | 0.98%   |
| Samsung SSD 970 EVO Plus 1TB    | 4         | 0.78%   |
| Dogfish SSD 128GB               | 4         | 0.78%   |
| BIWIN SSD 128GB                 | 4         | 0.78%   |
| WDC WDS500G2B0A-00SM50 500GB    | 3         | 0.59%   |
| WDC WD20EZRX-00DC0B0 2TB        | 3         | 0.59%   |
| Transcend TS256GMSA230S 256GB   | 3         | 0.59%   |
| Toshiba DT01ACA100 1TB          | 3         | 0.59%   |
| SPCC Solid State Disk 256GB     | 3         | 0.59%   |
| Seagate ST3500413AS 500GB       | 3         | 0.59%   |
| SanDisk SD6SB1M064G1022I 64GB   | 3         | 0.59%   |
| Samsung SSD 980 1TB             | 3         | 0.59%   |
| Samsung SSD 870 EVO 500GB       | 3         | 0.59%   |
| Samsung SSD 850 PRO 256GB       | 3         | 0.59%   |
| Samsung SSD 850 EVO 500GB       | 3         | 0.59%   |
| Samsung SSD 840 EVO 120GB       | 3         | 0.59%   |
| Kingston SUV500MS120G 120GB     | 3         | 0.59%   |
| Intel SSDSA2CW120G3 120GB       | 3         | 0.59%   |
| Crucial CT240BX500SSD1 240GB    | 3         | 0.59%   |
| WDC WD7500BPKX-00HPJT0 752GB    | 2         | 0.39%   |
| WDC WD6400AAKS-22A7B2 640GB     | 2         | 0.39%   |
| WDC WD40EFRX-68WT0N0 4TB        | 2         | 0.39%   |
| WDC WD30EFRX-68EUZN0 3TB        | 2         | 0.39%   |
| WDC WD20EFRX-68EUZN0 2TB        | 2         | 0.39%   |
| WDC WD120EDAZ-11F3RA0 12TB      | 2         | 0.39%   |
| WDC WD10JPLX-00MBPT0 1TB        | 2         | 0.39%   |
| WDC WD10EZEX-22MFCA0 1TB        | 2         | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB        | 2         | 0.39%   |
| WDC PC SN520 NVMe 256GB         | 2         | 0.39%   |
| VisionTek mSATA 120GB           | 2         | 0.39%   |
| Toshiba MQ01ABD075 752GB        | 2         | 0.39%   |
| SPCC Solid State Disk 128GB     | 2         | 0.39%   |
| Seagate ST4000VN008-2DR166 4TB  | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 51        | 159    | 35.66%  |
| Seagate             | 50        | 105    | 34.97%  |
| Toshiba             | 13        | 25     | 9.09%   |
| Hitachi             | 13        | 56     | 9.09%   |
| HGST                | 5         | 75     | 3.5%    |
| NVMe                | 2         | 3      | 1.4%    |
| Hewlett-Packard     | 2         | 2      | 1.4%    |
| Fujitsu             | 2         | 2      | 1.4%    |
| Samsung Electronics | 1         | 1      | 0.7%    |
| OPENBSD             | 1         | 1      | 0.7%    |
| Lexar               | 1         | 1      | 0.7%    |
| HPT                 | 1         | 1      | 0.7%    |
| HPE                 | 1         | 5      | 0.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 55        | 95     | 20.3%   |
| Kingston            | 51        | 60     | 18.82%  |
| Intel               | 18        | 31     | 6.64%   |
| Crucial             | 16        | 21     | 5.9%    |
| A-DATA Technology   | 15        | 28     | 5.54%   |
| SanDisk             | 13        | 17     | 4.8%    |
| WDC                 | 12        | 14     | 4.43%   |
| Dogfish             | 8         | 21     | 2.95%   |
| FORESEE             | 7         | 21     | 2.58%   |
| Transcend           | 6         | 7      | 2.21%   |
| SPCC                | 6         | 6      | 2.21%   |
| OCZ                 | 6         | 10     | 2.21%   |
| Patriot             | 4         | 5      | 1.48%   |
| Mushkin             | 4         | 4      | 1.48%   |
| Micron Technology   | 4         | 7      | 1.48%   |
| Hoodisk             | 4         | 5      | 1.48%   |
| BIWIN               | 4         | 5      | 1.48%   |
| PNY                 | 3         | 4      | 1.11%   |
| VisionTek           | 2         | 6      | 0.74%   |
| SK hynix            | 2         | 2      | 0.74%   |
| Seagate             | 2         | 2      | 0.74%   |
| Protectli           | 2         | 3      | 0.74%   |
| Netac               | 2         | 2      | 0.74%   |
| Lexar               | 2         | 3      | 0.74%   |
| Hewlett-Packard     | 2         | 2      | 0.74%   |
| Corsair             | 2         | 4      | 0.74%   |
| China               | 2         | 4      | 0.74%   |
| Apacer              | 2         | 2      | 0.74%   |
| ZTC                 | 1         | 1      | 0.37%   |
| walram              | 1         | 1      | 0.37%   |
| Toshiba             | 1         | 1      | 0.37%   |
| Timetec             | 1         | 1      | 0.37%   |
| SATADOM             | 1         | 2      | 0.37%   |
| Phison              | 1         | 1      | 0.37%   |
| NVMe                | 1         | 1      | 0.37%   |
| Kston               | 1         | 2      | 0.37%   |
| KingDian            | 1         | 1      | 0.37%   |
| Innodisk            | 1         | 1      | 0.37%   |
| HPE                 | 1         | 4      | 0.37%   |
| HP Phison           | 1         | 1      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 246       | 413    | 57.75%  |
| HDD  | 121       | 436    | 28.4%   |
| NVMe | 59        | 88     | 13.85%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 334       | 849    | 84.99%  |
| NVMe | 59        | 88     | 15.01%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 273       | 468    | 70.73%  |
| 0.51-1.0   | 60        | 122    | 15.54%  |
| 1.01-2.0   | 23        | 52     | 5.96%   |
| 3.01-4.0   | 11        | 107    | 2.85%   |
| 4.01-10.0  | 8         | 47     | 2.07%   |
| 2.01-3.0   | 6         | 27     | 1.55%   |
| 10.01-20.0 | 5         | 26     | 1.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 167       | 39.39%  |
| 251-500        | 59        | 13.92%  |
| 1-20           | 53        | 12.5%   |
| 51-100         | 51        | 12.03%  |
| 21-50          | 46        | 10.85%  |
| 501-1000       | 31        | 7.31%   |
| 1001-2000      | 10        | 2.36%   |
| Unknown        | 4         | 0.94%   |
| More than 3000 | 3         | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 359       | 86.09%  |
| 21-50     | 36        | 8.63%   |
| 51-100    | 10        | 2.4%    |
| Unknown   | 4         | 0.96%   |
| 101-250   | 3         | 0.72%   |
| 251-500   | 2         | 0.48%   |
| 1001-2000 | 2         | 0.48%   |
| 501-1000  | 1         | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB                | 2         | 6      | 3.13%   |
| VisionTek mSATA 120GB                      | 2         | 6      | 3.13%   |
| Toshiba MQ01ABD075 752GB                   | 2         | 2      | 3.13%   |
| Seagate ST500DM002-1BD142 500GB            | 2         | 4      | 3.13%   |
| Seagate ST3500413AS 500GB                  | 2         | 4      | 3.13%   |
| Dogfish SSD 128GB                          | 2         | 4      | 3.13%   |
| WDC WDS200T2B0A 2TB                        | 1         | 1      | 1.56%   |
| WDC WD7500BPKX-00HPJT0 752GB               | 1         | 6      | 1.56%   |
| WDC WD6400BEVT-22A0RT0 640GB               | 1         | 1      | 1.56%   |
| WDC WD50EFRX-68L0BN1 5TB                   | 1         | 1      | 1.56%   |
| WDC WD5003AZEX-00K1GA0 500GB               | 1         | 1      | 1.56%   |
| WDC WD40EFRX-68WT0N0 4TB                   | 1         | 2      | 1.56%   |
| WDC WD30EZRX-22D8PB0 3TB                   | 1         | 1      | 1.56%   |
| WDC WD2500AAKX-001CA0 250GB                | 1         | 1      | 1.56%   |
| WDC WD1600AAJS-60Z0A0 160GB                | 1         | 2      | 1.56%   |
| walram SSD 120G                            | 1         | 1      | 1.56%   |
| Toshiba MK1665GSX 160GB                    | 1         | 1      | 1.56%   |
| Toshiba DT01ACA100 1TB                     | 1         | 3      | 1.56%   |
| SPCC Solid State Disk 128GB                | 1         | 1      | 1.56%   |
| Seagate ST9500420AS 500GB                  | 1         | 2      | 1.56%   |
| Seagate ST500LM021-1KJ152 500GB            | 1         | 1      | 1.56%   |
| Seagate ST3250318AS 250GB                  | 1         | 1      | 1.56%   |
| Seagate ST3200822AS 200GB                  | 1         | 1      | 1.56%   |
| Seagate ST3160815AS 160GB                  | 1         | 1      | 1.56%   |
| Seagate ST31500341AS 1.5TB                 | 1         | 2      | 1.56%   |
| Seagate ST3120026A 120GB                   | 1         | 1      | 1.56%   |
| Seagate ST31000520AS 1TB                   | 1         | 1      | 1.56%   |
| Seagate ST2000DL003-9VT166 2TB             | 1         | 4      | 1.56%   |
| Seagate ST1000DM003-1CH162 1TB             | 1         | 2      | 1.56%   |
| Samsung Electronics SSD 970 EVO 2TB        | 1         | 2      | 1.56%   |
| Samsung Electronics SSD 870 EVO 250GB      | 1         | 3      | 1.56%   |
| Samsung Electronics SSD 860 EVO 1TB        | 1         | 3      | 1.56%   |
| OCZ VERTEX 32GB                            | 1         | 4      | 1.56%   |
| Mushkin MKNSSDEC512GB                      | 1         | 1      | 1.56%   |
| Micron Technology M500_MTFDDAK960MAV 960GB | 1         | 4      | 1.56%   |
| Kingston SV300S37A60G 64GB                 | 1         | 2      | 1.56%   |
| Kingston SV300S37A120G 120GB               | 1         | 1      | 1.56%   |
| Kingston SUV400S37240G 240GB               | 1         | 1      | 1.56%   |
| Kingston SNS4151S316GD 16GB                | 1         | 1      | 1.56%   |
| Kingston SNS4151S316G 16GB                 | 1         | 1      | 1.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 24     | 20.97%  |
| WDC                 | 11        | 22     | 17.74%  |
| Hitachi             | 6         | 19     | 9.68%   |
| Kingston            | 5         | 6      | 8.06%   |
| Intel               | 5         | 6      | 8.06%   |
| Toshiba             | 4         | 6      | 6.45%   |
| VisionTek           | 2         | 6      | 3.23%   |
| Samsung Electronics | 2         | 8      | 3.23%   |
| HGST                | 2         | 3      | 3.23%   |
| Dogfish             | 2         | 4      | 3.23%   |
| A-DATA Technology   | 2         | 7      | 3.23%   |
| walram              | 1         | 1      | 1.61%   |
| SPCC                | 1         | 1      | 1.61%   |
| OCZ                 | 1         | 4      | 1.61%   |
| Mushkin             | 1         | 1      | 1.61%   |
| Micron Technology   | 1         | 4      | 1.61%   |
| HP Phison           | 1         | 1      | 1.61%   |
| Crucial             | 1         | 1      | 1.61%   |
| Apacer              | 1         | 1      | 1.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 24     | 37.14%  |
| WDC     | 10        | 21     | 28.57%  |
| Hitachi | 6         | 19     | 17.14%  |
| Toshiba | 4         | 6      | 11.43%  |
| HGST    | 2         | 3      | 5.71%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 73     | 53.33%  |
| SSD  | 27        | 50     | 45%     |
| NVMe | 1         | 2      | 1.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC WD10SPZX-00Z10T0 1TB  | 1         | 1      | 33.33%  |
| Seagate ST3250310AS 250GB | 1         | 1      | 33.33%  |
| SanDisk pSSD 128GB        | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| SanDisk | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 332       | 795    | 81.98%  |
| Malfunc  | 58        | 125    | 14.32%  |
| Detected | 12        | 14     | 2.96%   |
| Failed   | 3         | 3      | 0.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 321       | 66.19%  |
| AMD                                     | 52        | 10.72%  |
| Samsung Electronics                     | 22        | 4.54%   |
| Broadcom / LSI                          | 16        | 3.3%    |
| SanDisk                                 | 14        | 2.89%   |
| Nvidia                                  | 7         | 1.44%   |
| Silicon Motion                          | 5         | 1.03%   |
| Kingston Technology Company             | 5         | 1.03%   |
| ASMedia Technology                      | 5         | 1.03%   |
| SK hynix                                | 4         | 0.82%   |
| Micron/Crucial Technology               | 4         | 0.82%   |
| Marvell Technology Group                | 4         | 0.82%   |
| Chelsio Communications                  | 4         | 0.82%   |
| Toshiba                                 | 3         | 0.62%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.62%   |
| Silicon Image                           | 2         | 0.41%   |
| Phison Electronics                      | 2         | 0.41%   |
| Micron Technology                       | 2         | 0.41%   |
| JMicron Technology                      | 2         | 0.41%   |
| Hewlett-Packard                         | 2         | 0.41%   |
| Shenzhen Unionmemory Information System | 1         | 0.21%   |
| Realtek Semiconductor                   | 1         | 0.21%   |
| Netac Technology                        | 1         | 0.21%   |
| HighPoint Technologies                  | 1         | 0.21%   |
| Dell                                    | 1         | 0.21%   |
| ADATA Technology                        | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 36        | 6.53%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 28        | 5.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 21        | 3.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 20        | 3.63%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 17        | 3.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 16        | 2.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 16        | 2.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 13        | 2.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 2.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 12        | 2.18%   |
| AMD 400 Series Chipset SATA Controller                                           | 12        | 2.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 2%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 2%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 11        | 2%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 10        | 1.81%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 9         | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 1.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 8         | 1.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 8         | 1.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7         | 1.27%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 6         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 1.09%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 0.91%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 0.91%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 5         | 0.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 0.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 0.91%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 5         | 0.91%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 4         | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 0.73%   |
| Intel Elkhart Lake SATA AHCI                                                     | 4         | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 0.73%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 4         | 0.73%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 4         | 0.73%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4         | 0.73%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4         | 0.73%   |
| AMD FCH SATA Controller [IDE mode]                                               | 4         | 0.73%   |
| Unknown                                                                          | 4         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 333       | 68.52%  |
| NVMe | 65        | 13.37%  |
| IDE  | 50        | 10.29%  |
| RAID | 20        | 4.12%   |
| SAS  | 11        | 2.26%   |
| SCSI | 7         | 1.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 341       | 84.62%  |
| AMD     | 59        | 14.64%  |
| Unknown | 2         | 0.5%    |
| ARM     | 1         | 0.25%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron N5105 @ 2.00GHz            | 14        | 3.41%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 12        | 2.92%   |
| Intel Core i5-3570 CPU @ 3.40GHz         | 8         | 1.95%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 7         | 1.7%    |
| Intel Core i5-4570 CPU @ 3.20GHz         | 7         | 1.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz        | 6         | 1.46%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 6         | 1.46%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 6         | 1.46%   |
| Intel Celeron CPU J3455E @ 1.50GHz       | 5         | 1.22%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 5         | 1.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 4         | 0.97%   |
| Intel Core i5-4570TE CPU @ 2.70GHz       | 4         | 0.97%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 4         | 0.97%   |
| Intel Core i3-2100 CPU @ 3.10GHz         | 4         | 0.97%   |
| AMD GX-412TC SOC                         | 4         | 0.97%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz      | 3         | 0.73%   |
| Intel Xeon                               | 3         | 0.73%   |
| Intel Pentium Silver N6005 @ 2.00GHz     | 3         | 0.73%   |
| Intel Pentium CPU G4560 @ 3.50GHz        | 3         | 0.73%   |
| Intel Core i7-9700K CPU @ 3.60GHz        | 3         | 0.73%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 3         | 0.73%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 3         | 0.73%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 3         | 0.73%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 3         | 0.73%   |
| Intel Core i3-5005U CPU @ 2.00GHz        | 3         | 0.73%   |
| Intel Core i3-4010U CPU @ 1.70GHz        | 3         | 0.73%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz     | 3         | 0.73%   |
| Intel Celeron J6413 @ 1.80GHz            | 3         | 0.73%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 3         | 0.73%   |
| AMD Ryzen 5 2600 Six-Core Processor      | 3         | 0.73%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 3         | 0.73%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 2         | 0.49%   |
| Intel Xeon CPU E5645 @ 2.40GHz           | 2         | 0.49%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz      | 2         | 0.49%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz      | 2         | 0.49%   |
| Intel CPU Version                        | 2         | 0.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 2         | 0.49%   |
| Intel Core i7-7700 CPU @ 3.60GHz         | 2         | 0.49%   |
| Intel Core i7-4790K CPU @ 4.00GHz        | 2         | 0.49%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 2         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 102       | 25%     |
| Intel Celeron           | 68        | 16.67%  |
| Intel Xeon              | 47        | 11.52%  |
| Intel Core i7           | 35        | 8.58%   |
| Intel Core i3           | 33        | 8.09%   |
| Other                   | 19        | 4.66%   |
| Intel Atom              | 16        | 3.92%   |
| Intel Core 2 Duo        | 10        | 2.45%   |
| Intel Pentium           | 7         | 1.72%   |
| AMD Ryzen 5             | 7         | 1.72%   |
| AMD Ryzen 7             | 6         | 1.47%   |
| AMD GX                  | 6         | 1.47%   |
| AMD FX                  | 6         | 1.47%   |
| AMD Ryzen 9             | 5         | 1.23%   |
| Intel Pentium Silver    | 4         | 0.98%   |
| Intel Pentium Dual-Core | 4         | 0.98%   |
| Intel Core 2 Quad       | 3         | 0.74%   |
| AMD EPYC                | 3         | 0.74%   |
| AMD Athlon 64 X2        | 3         | 0.74%   |
| Intel Pentium 4         | 2         | 0.49%   |
| AMD Ryzen Embedded      | 2         | 0.49%   |
| AMD Ryzen 5 PRO         | 2         | 0.49%   |
| AMD Ryzen 3             | 2         | 0.49%   |
| AMD Opteron             | 2         | 0.49%   |
| AMD G                   | 2         | 0.49%   |
| Intel Genuine           | 1         | 0.25%   |
| ARM Cortex              | 1         | 0.25%   |
| AMD Phenom II X6        | 1         | 0.25%   |
| AMD Phenom              | 1         | 0.25%   |
| AMD E1                  | 1         | 0.25%   |
| AMD E                   | 1         | 0.25%   |
| AMD Athlon II X2        | 1         | 0.25%   |
| AMD Athlon Dual Core    | 1         | 0.25%   |
| AMD Athlon              | 1         | 0.25%   |
| AMD A6                  | 1         | 0.25%   |
| AMD A4                  | 1         | 0.25%   |
| AMD A10                 | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 190       | 46.91%  |
| 2       | 123       | 30.37%  |
| 6       | 22        | 5.43%   |
| 8       | 18        | 4.44%   |
| 12      | 14        | 3.46%   |
| Unknown | 13        | 3.21%   |
| 16      | 8         | 1.98%   |
| 32      | 5         | 1.23%   |
| 10      | 4         | 0.99%   |
| 24      | 3         | 0.74%   |
| 1       | 2         | 0.49%   |
| 64      | 1         | 0.25%   |
| 11      | 1         | 0.25%   |
| 3       | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 381       | 94.54%  |
| 2       | 15        | 3.72%   |
| Unknown | 7         | 1.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 224       | 55.86%  |
| 2       | 163       | 40.65%  |
| Unknown | 14        | 3.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 57        | 13.9%   |
| KabyLake      | 39        | 9.51%   |
| Unknown       | 38        | 9.27%   |
| IvyBridge     | 34        | 8.29%   |
| Silvermont    | 28        | 6.83%   |
| Skylake       | 25        | 6.1%    |
| SandyBridge   | 24        | 5.85%   |
| Penryn        | 18        | 4.39%   |
| Broadwell     | 17        | 4.15%   |
| Westmere      | 14        | 3.41%   |
| Goldmont plus | 13        | 3.17%   |
| Goldmont      | 13        | 3.17%   |
| Zen+          | 9         | 2.2%    |
| Piledriver    | 9         | 2.2%    |
| Nehalem       | 8         | 1.95%   |
| CometLake     | 7         | 1.71%   |
| Bonnell       | 7         | 1.71%   |
| Zen           | 6         | 1.46%   |
| Zen 3         | 5         | 1.22%   |
| Jaguar        | 5         | 1.22%   |
| Zen 2         | 4         | 0.98%   |
| TigerLake     | 4         | 0.98%   |
| Puma          | 4         | 0.98%   |
| K8 Hammer     | 4         | 0.98%   |
| K10           | 4         | 0.98%   |
| Steamroller   | 3         | 0.73%   |
| Core          | 3         | 0.73%   |
| Bobcat        | 3         | 0.73%   |
| NetBurst      | 2         | 0.49%   |
| P6            | 1         | 0.24%   |
| IceLake       | 1         | 0.24%   |
| Excavator     | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 260       | 64.68%  |
| AMD                        | 54        | 13.43%  |
| Nvidia                     | 50        | 12.44%  |
| Matrox Electronics Systems | 21        | 5.22%   |
| ASPEED Technology          | 16        | 3.98%   |
| Silicon Motion             | 1         | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 30        | 7.28%   |
| Intel JasperLake [UHD Graphics]                                                          | 19        | 4.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 18        | 4.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 4.37%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 16        | 3.88%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 13        | 3.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 13        | 3.16%   |
| Intel HD Graphics 5500                                                                   | 12        | 2.91%   |
| Intel HD Graphics 530                                                                    | 12        | 2.91%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 2.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 2.67%   |
| Intel HD Graphics 500                                                                    | 10        | 2.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.18%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 1.94%   |
| Intel HD Graphics 620                                                                    | 7         | 1.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 1.7%    |
| Intel HD Graphics 630                                                                    | 6         | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.46%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.21%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 5         | 1.21%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 1.21%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.97%   |
| Matrox Electronics Systems G200eR2                                                       | 4         | 0.97%   |
| Intel HD Graphics 610                                                                    | 4         | 0.97%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 4         | 0.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 0.97%   |
| Nvidia GM107GL [Quadro K620]                                                             | 3         | 0.73%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.73%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.73%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.73%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.73%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3         | 0.73%   |
| AMD ES1000                                                                               | 3         | 0.73%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2         | 0.49%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.49%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.49%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 2         | 0.49%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 2         | 0.49%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 2         | 0.49%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 234       | 57.64%  |
| 1 x AMD            | 48        | 11.82%  |
| 1 x Nvidia         | 42        | 10.34%  |
| 1 x Matrox         | 21        | 5.17%   |
| Other              | 16        | 3.94%   |
| 2 x Intel          | 15        | 3.69%   |
| 1 x ASPEED         | 15        | 3.69%   |
| Intel + Nvidia     | 8         | 1.97%   |
| 2 x AMD            | 3         | 0.74%   |
| Intel + AMD        | 2         | 0.49%   |
| 1 x Silicon Motion | 1         | 0.25%   |
| AMD + ASPEED       | 1         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 361       | 88.92%  |
| Proprietary | 27        | 6.65%   |
| Unknown     | 18        | 4.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 359       | 88.86%  |
| 1.01-2.0   | 12        | 2.97%   |
| 0.51-1.0   | 10        | 2.48%   |
| 3.01-4.0   | 7         | 1.73%   |
| 0.01-0.5   | 6         | 1.49%   |
| 7.01-8.0   | 4         | 0.99%   |
| 5.01-6.0   | 3         | 0.74%   |
| 8.01-16.0  | 2         | 0.5%    |
| 2.01-3.0   | 1         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Goldstar                | 12        | 11.54%  |
| Dell                    | 11        | 10.58%  |
| LG Display              | 10        | 9.62%   |
| Chimei Innolux          | 9         | 8.65%   |
| Samsung Electronics     | 8         | 7.69%   |
| Lenovo                  | 6         | 5.77%   |
| BenQ                    | 6         | 5.77%   |
| AU Optronics            | 6         | 5.77%   |
| BOE                     | 5         | 4.81%   |
| Acer                    | 4         | 3.85%   |
| Sony                    | 3         | 2.88%   |
| LG Electronics          | 3         | 2.88%   |
| Chi Mei Optoelectronics | 3         | 2.88%   |
| ASUSTek Computer        | 3         | 2.88%   |
| Toshiba                 | 2         | 1.92%   |
| Hewlett-Packard         | 2         | 1.92%   |
| Apple                   | 2         | 1.92%   |
| AOC                     | 2         | 1.92%   |
| Ancor Communications    | 2         | 1.92%   |
| ViewSonic               | 1         | 0.96%   |
| Videoseven              | 1         | 0.96%   |
| RTK                     | 1         | 0.96%   |
| LTV                     | 1         | 0.96%   |
| Insignia                | 1         | 0.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Sony LCD Monitor TV XV 1920x1080                                       | 2         | 1.85%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 2         | 1.85%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch            | 2         | 1.85%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 2         | 1.85%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2         | 1.85%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch       | 2         | 1.85%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch         | 2         | 1.85%   |
| ViewSonic LCD Monitor VSCFA2B 1920x1080 510x290mm 23.1-inch            | 1         | 0.93%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1         | 0.93%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 1         | 0.93%   |
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch               | 1         | 0.93%   |
| Sony TV  *30 SNY05D1 3840x2160 1660x930mm 74.9-inch                    | 1         | 0.93%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch   | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch   | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 330x210mm 15.4-inch   | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch   | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch   | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1210x680mm 54.6-inch | 1         | 0.93%   |
| RTK CPL AIO PC RTK2482 1920x1080 510x280mm 22.9-inch                   | 1         | 0.93%   |
| LTV LTV1280M1A LTV0A3C 1024x768 800x450mm 36.1-inch                    | 1         | 0.93%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                      | 1         | 0.93%   |
| LG Electronics LCD Monitor LG Ultra HD 7680x2160                       | 1         | 0.93%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1         | 0.93%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1         | 0.93%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch            | 1         | 0.93%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch            | 1         | 0.93%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch            | 1         | 0.93%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch            | 1         | 0.93%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch            | 1         | 0.93%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch            | 1         | 0.93%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch           | 1         | 0.93%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch           | 1         | 0.93%   |
| Lenovo LEN-M93z-B  LEN0093 1920x1080 510x290mm 23.1-inch               | 1         | 0.93%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                | 1         | 0.93%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                | 1         | 0.93%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                | 1         | 0.93%   |
| Insignia LCD Monitor BBY0050 1920x1080 700x400mm 31.7-inch             | 1         | 0.93%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1         | 0.93%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch             | 1         | 0.93%   |
| Goldstar W2442 GSM56D9 1920x1080 530x300mm 24.0-inch                   | 1         | 0.93%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 46        | 44.66%  |
| 1366x768 (WXGA)    | 17        | 16.5%   |
| 3840x2160 (4K)     | 8         | 7.77%   |
| 1600x900 (HD+)     | 6         | 5.83%   |
| 1280x800 (WXGA)    | 4         | 3.88%   |
| 2560x1440 (QHD)    | 3         | 2.91%   |
| 1680x1050 (WSXGA+) | 3         | 2.91%   |
| 3440x1440          | 2         | 1.94%   |
| 2560x1080          | 2         | 1.94%   |
| 1440x900 (WXGA+)   | 2         | 1.94%   |
| 1280x1024 (SXGA)   | 2         | 1.94%   |
| Unknown            | 2         | 1.94%   |
| 7680x2160          | 1         | 0.97%   |
| 2256x1504          | 1         | 0.97%   |
| 1920x1200 (WUXGA)  | 1         | 0.97%   |
| 1600x1200          | 1         | 0.97%   |
| 1280x854           | 1         | 0.97%   |
| 1024x768 (XGA)     | 1         | 0.97%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 17        | 16.19%  |
| 24      | 13        | 12.38%  |
| 15      | 13        | 12.38%  |
| 27      | 10        | 9.52%   |
| 21      | 7         | 6.67%   |
| 12      | 7         | 6.67%   |
| Unknown | 6         | 5.71%   |
| 23      | 5         | 4.76%   |
| 19      | 5         | 4.76%   |
| 34      | 4         | 3.81%   |
| 22      | 4         | 3.81%   |
| 54      | 3         | 2.86%   |
| 31      | 2         | 1.9%    |
| 17      | 2         | 1.9%    |
| 14      | 2         | 1.9%    |
| 74      | 1         | 0.95%   |
| 36      | 1         | 0.95%   |
| 20      | 1         | 0.95%   |
| 18      | 1         | 0.95%   |
| 11      | 1         | 0.95%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 28        | 26.92%  |
| 301-350     | 24        | 23.08%  |
| 201-300     | 16        | 15.38%  |
| 401-500     | 15        | 14.42%  |
| Unknown     | 6         | 5.77%   |
| 701-800     | 5         | 4.81%   |
| 351-400     | 4         | 3.85%   |
| 1001-1500   | 3         | 2.88%   |
| 601-700     | 2         | 1.92%   |
| 1501-2000   | 1         | 0.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 75        | 74.26%  |
| 16/10   | 11        | 10.89%  |
| Unknown | 6         | 5.94%   |
| 21/9    | 4         | 3.96%   |
| 5/4     | 2         | 1.98%   |
| 3/2     | 2         | 1.98%   |
| 4/3     | 1         | 0.99%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 25        | 24.04%  |
| 81-90          | 15        | 14.42%  |
| 301-350        | 10        | 9.62%   |
| 61-70          | 7         | 6.73%   |
| 101-110        | 7         | 6.73%   |
| 351-500        | 6         | 5.77%   |
| 151-200        | 6         | 5.77%   |
| 91-100         | 6         | 5.77%   |
| Unknown        | 6         | 5.77%   |
| More than 1000 | 4         | 3.85%   |
| 71-80          | 4         | 3.85%   |
| 251-300        | 3         | 2.88%   |
| 121-130        | 2         | 1.92%   |
| 51-60          | 1         | 0.96%   |
| 141-150        | 1         | 0.96%   |
| 501-1000       | 1         | 0.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 44        | 41.9%   |
| 101-120 | 25        | 23.81%  |
| 121-160 | 20        | 19.05%  |
| 161-240 | 9         | 8.57%   |
| Unknown | 6         | 5.71%   |
| 1-50    | 1         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 285       | 70.2%   |
| 1     | 111       | 27.34%  |
| 2     | 10        | 2.46%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 311       | 54.85%  |
| Realtek Semiconductor             | 142       | 25.04%  |
| Broadcom                          | 40        | 7.05%   |
| Qualcomm Atheros                  | 26        | 4.59%   |
| Chelsio Communications            | 6         | 1.06%   |
| MediaTek                          | 4         | 0.71%   |
| Marvell Technology Group          | 4         | 0.71%   |
| Solarflare Communications         | 3         | 0.53%   |
| Sierra Wireless                   | 2         | 0.35%   |
| Ralink                            | 2         | 0.35%   |
| Nvidia                            | 2         | 0.35%   |
| Mellanox Technologies             | 2         | 0.35%   |
| IBM                               | 2         | 0.35%   |
| Ericsson Business Mobile Networks | 2         | 0.35%   |
| Apple                             | 2         | 0.35%   |
| 3Com                              | 2         | 0.35%   |
| TP-Link                           | 1         | 0.18%   |
| Ralink Technology                 | 1         | 0.18%   |
| Qualcomm Atheros Communications   | 1         | 0.18%   |
| QLogic                            | 1         | 0.18%   |
| NetGear                           | 1         | 0.18%   |
| JMicron Technology                | 1         | 0.18%   |
| Insyde Software                   | 1         | 0.18%   |
| IMC Networks                      | 1         | 0.18%   |
| ICS Advent                        | 1         | 0.18%   |
| Hewlett-Packard                   | 1         | 0.18%   |
| Google                            | 1         | 0.18%   |
| D-Link System                     | 1         | 0.18%   |
| Aquantia                          | 1         | 0.18%   |
| American Megatrends               | 1         | 0.18%   |
| AMD                               | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 115       | 16.08%  |
| Intel I211 Gigabit Network Connection                                         | 36        | 5.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 31        | 4.34%   |
| Intel 82574L Gigabit Network Connection                                       | 27        | 3.78%   |
| Intel I210 Gigabit Network Connection                                         | 22        | 3.08%   |
| Intel Ethernet Connection I217-LM                                             | 22        | 3.08%   |
| Intel I350 Gigabit Network Connection                                         | 18        | 2.52%   |
| Intel Ethernet Controller I225-V                                              | 15        | 2.1%    |
| Intel Ethernet Controller I226-V                                              | 14        | 1.96%   |
| Intel Wireless 7265                                                           | 13        | 1.82%   |
| Intel 82576 Gigabit Network Connection                                        | 13        | 1.82%   |
| Intel 82583V Gigabit Network Connection                                       | 11        | 1.54%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 11        | 1.54%   |
| Intel 82580 Gigabit Network Connection                                        | 10        | 1.4%    |
| Realtek RTL8125 2.5GbE Controller                                             | 9         | 1.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 9         | 1.26%   |
| Intel Wireless 8260                                                           | 9         | 1.26%   |
| Intel Wi-Fi 6 AX200                                                           | 8         | 1.12%   |
| Intel Ethernet Connection I219-LM                                             | 8         | 1.12%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 8         | 1.12%   |
| Intel Wireless 7260                                                           | 7         | 0.98%   |
| Intel Wireless 3165                                                           | 7         | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 7         | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6         | 0.84%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 0.7%    |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 0.7%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5         | 0.7%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 5         | 0.7%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 4         | 0.56%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 4         | 0.56%   |
| Intel Ethernet Connection (5) I219-LM                                         | 4         | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 4         | 0.56%   |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 0.56%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4         | 0.56%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4         | 0.56%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 0.56%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3         | 0.42%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 3         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 3         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 95        | 64.63%  |
| Qualcomm Atheros                | 19        | 12.93%  |
| Realtek Semiconductor           | 12        | 8.16%   |
| Broadcom                        | 8         | 5.44%   |
| MediaTek                        | 4         | 2.72%   |
| Ralink                          | 2         | 1.36%   |
| TP-Link                         | 1         | 0.68%   |
| Sierra Wireless                 | 1         | 0.68%   |
| Ralink Technology               | 1         | 0.68%   |
| Qualcomm Atheros Communications | 1         | 0.68%   |
| NetGear                         | 1         | 0.68%   |
| Marvell Technology Group        | 1         | 0.68%   |
| IMC Networks                    | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 13        | 8.67%   |
| Intel Wireless 8260                                                     | 9         | 6%      |
| Intel Wi-Fi 6 AX200                                                     | 8         | 5.33%   |
| Intel Wireless 7260                                                     | 7         | 4.67%   |
| Intel Wireless 3165                                                     | 7         | 4.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 4.67%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 2.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 2%      |
| Intel Wireless 3160                                                     | 3         | 2%      |
| Intel Centrino Advanced-N 6200                                          | 3         | 2%      |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 3         | 2%      |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 2%      |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.33%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.33%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 1.33%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.33%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                   | 1         | 0.67%   |
| Sierra Wireless EM7455                                                  | 1         | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.67%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.67%   |
| Realtek Bluetooth Adapter                                               | 1         | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.67%   |
| Ralink RT5592 PCIe Wireless Network Adapter                             | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 268       | 56.78%  |
| Realtek Semiconductor     | 137       | 29.03%  |
| Broadcom                  | 32        | 6.78%   |
| Qualcomm Atheros          | 10        | 2.12%   |
| Chelsio Communications    | 4         | 0.85%   |
| Solarflare Communications | 3         | 0.64%   |
| Marvell Technology Group  | 3         | 0.64%   |
| Nvidia                    | 2         | 0.42%   |
| Apple                     | 2         | 0.42%   |
| 3Com                      | 2         | 0.42%   |
| QLogic                    | 1         | 0.21%   |
| JMicron Technology        | 1         | 0.21%   |
| Insyde Software           | 1         | 0.21%   |
| ICS Advent                | 1         | 0.21%   |
| Google                    | 1         | 0.21%   |
| D-Link System             | 1         | 0.21%   |
| Aquantia                  | 1         | 0.21%   |
| American Megatrends       | 1         | 0.21%   |
| AMD                       | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 115       | 20.91%  |
| Intel I211 Gigabit Network Connection                                         | 36        | 6.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 31        | 5.64%   |
| Intel 82574L Gigabit Network Connection                                       | 27        | 4.91%   |
| Intel I210 Gigabit Network Connection                                         | 22        | 4%      |
| Intel Ethernet Connection I217-LM                                             | 22        | 4%      |
| Intel I350 Gigabit Network Connection                                         | 18        | 3.27%   |
| Intel Ethernet Controller I225-V                                              | 15        | 2.73%   |
| Intel Ethernet Controller I226-V                                              | 14        | 2.55%   |
| Intel 82576 Gigabit Network Connection                                        | 13        | 2.36%   |
| Intel 82583V Gigabit Network Connection                                       | 11        | 2%      |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 11        | 2%      |
| Intel 82580 Gigabit Network Connection                                        | 10        | 1.82%   |
| Realtek RTL8125 2.5GbE Controller                                             | 9         | 1.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 9         | 1.64%   |
| Intel Ethernet Connection I219-LM                                             | 8         | 1.45%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 8         | 1.45%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6         | 1.09%   |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 0.91%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5         | 0.91%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 5         | 0.91%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 0.91%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 4         | 0.73%   |
| Intel Ethernet Connection (5) I219-LM                                         | 4         | 0.73%   |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 0.73%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4         | 0.73%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4         | 0.73%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 0.73%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3         | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 3         | 0.55%   |
| Intel Ethernet Controller X550                                                | 3         | 0.55%   |
| Intel Ethernet Connection I354                                                | 3         | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                                         | 3         | 0.55%   |
| Intel Ethernet Connection (3) I218-V                                          | 3         | 0.55%   |
| Intel Ethernet Connection (2) I218-LM                                         | 3         | 0.55%   |
| Intel 82575GB Gigabit Network Connection                                      | 3         | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3         | 0.55%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3         | 0.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 3         | 0.55%   |
| Solarflare SFC9020 10G Ethernet Controller                                    | 2         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 390       | 71.17%  |
| WiFi     | 143       | 26.09%  |
| Unknown  | 11        | 2.01%   |
| Modem    | 4         | 0.73%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 361       | 83.37%  |
| WiFi     | 72        | 16.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 147       | 36.03%  |
| 4     | 67        | 16.42%  |
| 3     | 66        | 16.18%  |
| 1     | 54        | 13.24%  |
| 6     | 27        | 6.62%   |
| 5     | 25        | 6.13%   |
| 8     | 6         | 1.47%   |
| 7     | 6         | 1.47%   |
| 0     | 4         | 0.98%   |
| 10    | 2         | 0.49%   |
| 9     | 2         | 0.49%   |
| 14    | 1         | 0.25%   |
| 12    | 1         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 358       | 87.1%   |
| Yes  | 53        | 12.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 60.19%  |
| Cambridge Silicon Radio         | 8         | 7.41%   |
| Realtek Semiconductor           | 5         | 4.63%   |
| Foxconn / Hon Hai               | 5         | 4.63%   |
| Broadcom                        | 5         | 4.63%   |
| Qualcomm Atheros Communications | 4         | 3.7%    |
| IMC Networks                    | 4         | 3.7%    |
| Apple                           | 3         | 2.78%   |
| Lite-On Technology              | 2         | 1.85%   |
| ASUSTek Computer                | 2         | 1.85%   |
| Alps Electric                   | 2         | 1.85%   |
| Toshiba                         | 1         | 0.93%   |
| MediaTek                        | 1         | 0.93%   |
| Hewlett-Packard                 | 1         | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 34        | 31.19%  |
| Intel AX201 Bluetooth                                       | 9         | 8.26%   |
| Intel AX200 Bluetooth                                       | 8         | 7.34%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 8         | 7.34%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 6         | 5.5%    |
| Intel Wireless-AC 3168 Bluetooth                            | 4         | 3.67%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 2.75%   |
| Realtek Bluetooth Adapter                                   | 2         | 1.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.83%   |
| Intel Wireless Bluetooth                                    | 2         | 1.83%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                   | 2         | 1.83%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.83%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 1.83%   |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 1.83%   |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 0.92%   |
| Realtek RTL8723A Bluetooth                                  | 1         | 0.92%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.92%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.92%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.92%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.92%   |
| MediaTek RZ608 Bluetooth Adapter                            | 1         | 0.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.92%   |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 0.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.92%   |
| Intel AX210 Bluetooth                                       | 1         | 0.92%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 1         | 0.92%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 0.92%   |
| IMC Networks Bluetooth                                      | 1         | 0.92%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.92%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.92%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 0.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 0.92%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 0.92%   |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 0.92%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 0.92%   |
| Apple Bluetooth Host Controller                             | 1         | 0.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 259       | 68.16%  |
| AMD                      | 57        | 15%     |
| Nvidia                   | 42        | 11.05%  |
| C-Media Electronics      | 6         | 1.58%   |
| Logitech                 | 3         | 0.79%   |
| Texas Instruments        | 2         | 0.53%   |
| KTMicro                  | 2         | 0.53%   |
| ASUSTek Computer         | 2         | 0.53%   |
| Yamaha                   | 1         | 0.26%   |
| XMOS                     | 1         | 0.26%   |
| SteelSeries ApS          | 1         | 0.26%   |
| MosArt Semiconductor     | 1         | 0.26%   |
| Micro Star International | 1         | 0.26%   |
| Elgato Systems           | 1         | 0.26%   |
| Creative Labs            | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 30        | 6.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 27        | 5.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 5.04%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 4.17%   |
| Intel Jasper Lake HD Audio                                                                        | 19        | 4.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 3.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 3.51%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 2.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 2.63%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 2.41%   |
| Intel 200 Series PCH HD Audio                                                                     | 11        | 2.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 2.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 2.19%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 1.97%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 1.97%   |
| AMD FCH Azalia Controller                                                                         | 9         | 1.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 8         | 1.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 1.54%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 1.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.32%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 1.1%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.1%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5         | 1.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.1%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.1%    |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.1%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 0.88%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 4         | 0.88%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4         | 0.88%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 4         | 0.88%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.66%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.66%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3         | 0.66%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 0.66%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 77        | 17.5%   |
| Samsung Electronics | 71        | 16.14%  |
| Kingston            | 65        | 14.77%  |
| Unknown             | 40        | 9.09%   |
| Micron Technology   | 31        | 7.05%   |
| Crucial             | 30        | 6.82%   |
| Corsair             | 29        | 6.59%   |
| G.Skill             | 25        | 5.68%   |
| Unknown             | 13        | 2.95%   |
| Unknown (ABCD)      | 7         | 1.59%   |
| A-DATA Technology   | 6         | 1.36%   |
| Ramaxel Technology  | 5         | 1.14%   |
| Apacer              | 5         | 1.14%   |
| Transcend           | 4         | 0.91%   |
| Team                | 4         | 0.91%   |
| Nanya Technology    | 4         | 0.91%   |
| Unknown (0x0C26)    | 3         | 0.68%   |
| Timetec             | 3         | 0.68%   |
| Patriot             | 3         | 0.68%   |
| OCZ                 | 3         | 0.68%   |
| Avant               | 2         | 0.45%   |
| V-Color             | 1         | 0.23%   |
| Unknown (0x0DD5)    | 1         | 0.23%   |
| Toshiba             | 1         | 0.23%   |
| Teikon              | 1         | 0.23%   |
| Silicon Power       | 1         | 0.23%   |
| PNY                 | 1         | 0.23%   |
| Lexar Co Limited    | 1         | 0.23%   |
| Elpida              | 1         | 0.23%   |
| Cors                | 1         | 0.23%   |
| 0C26000000AD        | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 13        | 2.73%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 7         | 1.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 5         | 1.05%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 5         | 1.05%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s        | 5         | 1.05%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 4         | 0.84%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 4         | 0.84%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 4         | 0.84%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s            | 4         | 0.84%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s            | 4         | 0.84%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 3         | 0.63%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 3         | 0.63%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 3         | 0.63%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 3         | 0.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 0.63%   |
| SK hynix RAM HMT351U7BFR8A-H9 4GB DIMM DDR3 1333MT/s           | 3         | 0.63%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 3         | 0.63%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s          | 3         | 0.63%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 3         | 0.63%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s            | 3         | 0.63%   |
| Unknown RAM Module 8GB 1600MT/s                                | 2         | 0.42%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 2         | 0.42%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2         | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                      | 2         | 0.42%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 2         | 0.42%   |
| Transcend RAM TS512MSK64W3N 4GB DIMM DDR3 1333MT/s             | 2         | 0.42%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                     | 2         | 0.42%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.42%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.42%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 2         | 0.42%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.42%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s         | 2         | 0.42%   |
| SK hynix RAM HMT151R7BFR4C-H9 4GB DIMM DDR3 1333MT/s           | 2         | 0.42%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 2         | 0.42%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s           | 2         | 0.42%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s           | 2         | 0.42%   |
| SK hynix RAM HMA451R7AFR8N-TF 4GB RIMM DDR4 2133MT/s           | 2         | 0.42%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 2         | 0.42%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.42%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s            | 2         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 190       | 49.61%  |
| DDR4    | 137       | 35.77%  |
| DDR2    | 17        | 4.44%   |
| Unknown | 12        | 3.13%   |
| LPDDR4  | 11        | 2.87%   |
| SDRAM   | 7         | 1.83%   |
| DDR5    | 5         | 1.31%   |
| LPDDR3  | 2         | 0.52%   |
| DDR     | 2         | 0.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 211       | 55.67%  |
| SODIMM       | 155       | 40.9%   |
| Row Of Chips | 4         | 1.06%   |
| RIMM         | 3         | 0.79%   |
| Unknown      | 3         | 0.79%   |
| Chip         | 2         | 0.53%   |
| FB-DIMM      | 1         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 144       | 34.62%  |
| 8192  | 135       | 32.45%  |
| 2048  | 58        | 13.94%  |
| 16384 | 57        | 13.7%   |
| 1024  | 13        | 3.13%   |
| 32768 | 7         | 1.68%   |
| 512   | 2         | 0.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 126       | 30.58%  |
| 1333    | 62        | 15.05%  |
| 2400    | 43        | 10.44%  |
| 3200    | 35        | 8.5%    |
| 2667    | 35        | 8.5%    |
| 2133    | 27        | 6.55%   |
| 1067    | 13        | 3.16%   |
| 800     | 12        | 2.91%   |
| Unknown | 10        | 2.43%   |
| 2666    | 9         | 2.18%   |
| 667     | 8         | 1.94%   |
| 1334    | 6         | 1.46%   |
| 4800    | 4         | 0.97%   |
| 3600    | 3         | 0.73%   |
| 3000    | 3         | 0.73%   |
| 1867    | 3         | 0.73%   |
| 1066    | 3         | 0.73%   |
| 4267    | 2         | 0.49%   |
| 1866    | 2         | 0.49%   |
| 400     | 2         | 0.49%   |
| 6400    | 1         | 0.24%   |
| 5200    | 1         | 0.24%   |
| 3400    | 1         | 0.24%   |
| 333     | 1         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Brother Industries  | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 20%     |
| HP LaserJet 2200                   | 1         | 20%     |
| HP Color LaserJet CP1215           | 1         | 20%     |
| Brother HL-L5200DW series          | 1         | 20%     |
| Brother HL-L2300D series           | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 18        | 34.62%  |
| Microdia                      | 6         | 11.54%  |
| Bison Electronics             | 6         | 11.54%  |
| Realtek Semiconductor         | 5         | 9.62%   |
| Logitech                      | 3         | 5.77%   |
| Lite-On Technology            | 3         | 5.77%   |
| IMC Networks                  | 3         | 5.77%   |
| Syntek                        | 2         | 3.85%   |
| Sunplus Innovation Technology | 2         | 3.85%   |
| Quanta                        | 1         | 1.92%   |
| Luxvisions Innotech Limited   | 1         | 1.92%   |
| Lenovo                        | 1         | 1.92%   |
| ALi                           | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 4         | 7.69%   |
| Bison Integrated Camera                       | 4         | 7.69%   |
| Lite-On Integrated Camera                     | 3         | 5.77%   |
| Chicony HD Webcam                             | 3         | 5.77%   |
| Syntek Lenovo EasyCamera                      | 1         | 1.92%   |
| Syntek ASUS USB2.0 camera                     | 1         | 1.92%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 1         | 1.92%   |
| Sunplus ASUS Webcam                           | 1         | 1.92%   |
| Realtek USB 2.0 PC Camera                     | 1         | 1.92%   |
| Realtek PC Camera                             | 1         | 1.92%   |
| Realtek Integrated Webcam HD                  | 1         | 1.92%   |
| Realtek Integrated Webcam                     | 1         | 1.92%   |
| Realtek HD Webcam - Realtek                   | 1         | 1.92%   |
| Quanta Realtek PC Camera                      | 1         | 1.92%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 1.92%   |
| Microdia Laptop_Integrated_Webcam_2M          | 1         | 1.92%   |
| Microdia JOYACCESS JA-Webcam                  | 1         | 1.92%   |
| Microdia Integrated_Webcam_HD                 | 1         | 1.92%   |
| Microdia Integrated Webcam HD                 | 1         | 1.92%   |
| Microdia Integrated Webcam                    | 1         | 1.92%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.92%   |
| Logitech Webcam C310                          | 1         | 1.92%   |
| Logitech HD Pro Webcam C920                   | 1         | 1.92%   |
| Logitech BRIO Ultra HD Webcam                 | 1         | 1.92%   |
| Lenovo Integrated Webcam [R5U877]             | 1         | 1.92%   |
| IMC Networks UVC VGA Webcam                   | 1         | 1.92%   |
| IMC Networks Integrated Webcam                | 1         | 1.92%   |
| IMC Networks Integrated Camera                | 1         | 1.92%   |
| Chicony WebCam                                | 1         | 1.92%   |
| Chicony VGA 24fps UVC Webcam                  | 1         | 1.92%   |
| Chicony USB2.0 HD UVC WebCam                  | 1         | 1.92%   |
| Chicony TOSHIBA Web Camera - FHD              | 1         | 1.92%   |
| Chicony Sonix ST50220 USB Video Camera        | 1         | 1.92%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 1.92%   |
| Chicony Integrated Camera [ThinkPad]          | 1         | 1.92%   |
| Chicony HP HD Camera                          | 1         | 1.92%   |
| Chicony HP 0.3MP Webcam                       | 1         | 1.92%   |
| Chicony FJ Camera                             | 1         | 1.92%   |
| Chicony 2.0M UVC Webcam / CNF7129             | 1         | 1.92%   |
| Bison ThinkPad P50 Integrated Camera          | 1         | 1.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 47.06%  |
| Upek                       | 2         | 11.76%  |
| Synaptics                  | 2         | 11.76%  |
| LighTuning Technology      | 2         | 11.76%  |
| AuthenTec                  | 2         | 11.76%  |
| Shenzhen Goodix Technology | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 17.65%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 11.76%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 11.76%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5.88%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 5.88%   |
| Validity Sensors Synaptics WBDI                        | 1         | 5.88%   |
| Validity Sensors Fingerprint scanner                   | 1         | 5.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 5.88%   |
| AuthenTec AES2660                                      | 1         | 5.88%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 5.88%   |

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
| 1     | 200       | 47.96%  |
| 0     | 115       | 27.58%  |
| 2     | 64        | 15.35%  |
| 3     | 27        | 6.47%   |
| 4     | 9         | 2.16%   |
| 5     | 2         | 0.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 251       | 63.22%  |
| Bluetooth                | 43        | 10.83%  |
| Net/wireless             | 30        | 7.56%   |
| Card reader              | 18        | 4.53%   |
| Firewire controller      | 14        | 3.53%   |
| Fingerprint reader       | 13        | 3.27%   |
| Net/ethernet             | 8         | 2.02%   |
| Sound                    | 6         | 1.51%   |
| Network                  | 6         | 1.51%   |
| Graphics card            | 3         | 0.76%   |
| Storage/raid             | 2         | 0.5%    |
| Storage                  | 2         | 0.5%    |
| Storage/ata              | 1         | 0.25%   |

