BSD - Tested Hardware & Statistics
----------------------------------

A project to collect tested hardware configurations for BSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Desktop/README.md) and [notebooks](/Notebook/README.md).

OS-specific reports: [FreeBSD](/Dist/FreeBSD), [GhostBSD](/Dist/GhostBSD), [helloSystem](/Dist/helloSystem), [NetBSD](/Dist/NetBSD), [NomadBSD](/Dist/NomadBSD), [OpenBSD](/Dist/OpenBSD), [OPNsense](/Dist/OPNsense), [pfSense](/Dist/pfSense), [TrueNAS](/Dist/TrueNAS).

This report is for real hardware. Report for virtual hardware: [TestCoverage_VE](https://github.com/bsdhw/TestCoverage_VE)

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

Total: 12359

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Samsung       | 750TDA                      | Notebook    | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| HP            | 843F                        | Desktop     | [f921634ea0](https://bsd-hardware.info/?probe=f921634ea0) | Nov 02, 2022 |
| HP            | 339A                        | Desktop     | [370d93ecde](https://bsd-hardware.info/?probe=370d93ecde) | Nov 02, 2022 |
| Dell          | 0VWT90 A10                  | Server      | [b74220aee1](https://bsd-hardware.info/?probe=b74220aee1) | Nov 02, 2022 |
| HP            | ProLiant DL180 G6           | Server      | [289d2f383b](https://bsd-hardware.info/?probe=289d2f383b) | Nov 02, 2022 |
| Lenovo        | 00FN849 E63448-400          | Server      | [0794efc014](https://bsd-hardware.info/?probe=0794efc014) | Nov 02, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [f0e3f3177a](https://bsd-hardware.info/?probe=f0e3f3177a) | Nov 02, 2022 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [d7141b866c](https://bsd-hardware.info/?probe=d7141b866c) | Nov 02, 2022 |
| Dell          | 08HPGT A02                  | Desktop     | [b6044fb84c](https://bsd-hardware.info/?probe=b6044fb84c) | Nov 02, 2022 |
| HP            | 8053                        | Desktop     | [92583639f6](https://bsd-hardware.info/?probe=92583639f6) | Nov 02, 2022 |
| Dell          | 0W3F1J A00                  | Mini pc     | [7c95a69cc9](https://bsd-hardware.info/?probe=7c95a69cc9) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [7708c4bb19](https://bsd-hardware.info/?probe=7708c4bb19) | Nov 02, 2022 |
| HP            | 843F                        | Desktop     | [bba76c5ce6](https://bsd-hardware.info/?probe=bba76c5ce6) | Nov 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [bc7a300434](https://bsd-hardware.info/?probe=bc7a300434) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [22d3fc953a](https://bsd-hardware.info/?probe=22d3fc953a) | Nov 01, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [ac1e500e91](https://bsd-hardware.info/?probe=ac1e500e91) | Nov 01, 2022 |
| ASRock        | H670M-ITX/ax                | Desktop     | [bb78d5d8ea](https://bsd-hardware.info/?probe=bb78d5d8ea) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [871a5c449f](https://bsd-hardware.info/?probe=871a5c449f) | Nov 01, 2022 |
| Dell          | 09T7VV A02                  | Server      | [6e89de5b97](https://bsd-hardware.info/?probe=6e89de5b97) | Nov 01, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [8b2537708c](https://bsd-hardware.info/?probe=8b2537708c) | Nov 01, 2022 |
| Sophos        | SG                          | Firewall    | [ef9269be7e](https://bsd-hardware.info/?probe=ef9269be7e) | Nov 01, 2022 |
| ASRock        | H110 Pro BTC+               | Desktop     | [fb24f0fa6e](https://bsd-hardware.info/?probe=fb24f0fa6e) | Nov 01, 2022 |
| Sophos        | XG                          | Firewall    | [a245d23614](https://bsd-hardware.info/?probe=a245d23614) | Nov 01, 2022 |
| ASUSTek       | K30AM-J_A_F_K31AM-J         | Desktop     | [f587ec97a4](https://bsd-hardware.info/?probe=f587ec97a4) | Nov 01, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [23483285a8](https://bsd-hardware.info/?probe=23483285a8) | Nov 01, 2022 |
| Dell          | Latitude 5591               | Notebook    | [40957fa567](https://bsd-hardware.info/?probe=40957fa567) | Oct 31, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [5758027775](https://bsd-hardware.info/?probe=5758027775) | Oct 31, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6afa103d09](https://bsd-hardware.info/?probe=6afa103d09) | Oct 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [09cb46f6bf](https://bsd-hardware.info/?probe=09cb46f6bf) | Oct 31, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [bb0f8a5bfc](https://bsd-hardware.info/?probe=bb0f8a5bfc) | Oct 31, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [6f21c02bba](https://bsd-hardware.info/?probe=6f21c02bba) | Oct 31, 2022 |
| Supermicro    | X10DRU-i+                   | Desktop     | [1ffd63a929](https://bsd-hardware.info/?probe=1ffd63a929) | Oct 31, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [4dfd35f622](https://bsd-hardware.info/?probe=4dfd35f622) | Oct 31, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [d2d5364c96](https://bsd-hardware.info/?probe=d2d5364c96) | Oct 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [9737a80a1c](https://bsd-hardware.info/?probe=9737a80a1c) | Oct 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [c14a3eb06b](https://bsd-hardware.info/?probe=c14a3eb06b) | Oct 31, 2022 |
| Supermicro    | X7SPA-HF                    | Desktop     | [18b3b416ce](https://bsd-hardware.info/?probe=18b3b416ce) | Oct 31, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | Notebook    | [b816902c0b](https://bsd-hardware.info/?probe=b816902c0b) | Oct 31, 2022 |
| ASRock        | H110 Pro BTC+               | Desktop     | [20f2ab4251](https://bsd-hardware.info/?probe=20f2ab4251) | Oct 30, 2022 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [e5716f886a](https://bsd-hardware.info/?probe=e5716f886a) | Oct 30, 2022 |
| Sophos        | SG                          | Firewall    | [cab7a59023](https://bsd-hardware.info/?probe=cab7a59023) | Oct 30, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c4e84b8104](https://bsd-hardware.info/?probe=c4e84b8104) | Oct 30, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [0f22defdb3](https://bsd-hardware.info/?probe=0f22defdb3) | Oct 30, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [34f0a2bc03](https://bsd-hardware.info/?probe=34f0a2bc03) | Oct 30, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [cce93ff157](https://bsd-hardware.info/?probe=cce93ff157) | Oct 30, 2022 |
| Cisco Syst... | UCSC-C240-M5SX 74-105773... | Server      | [5a7e972a9e](https://bsd-hardware.info/?probe=5a7e972a9e) | Oct 30, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [a52d7dda08](https://bsd-hardware.info/?probe=a52d7dda08) | Oct 30, 2022 |
| Cisco Syst... | UCSC-C240-M5SX 74-105773... | Server      | [da2336a58a](https://bsd-hardware.info/?probe=da2336a58a) | Oct 30, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [af6807035f](https://bsd-hardware.info/?probe=af6807035f) | Oct 30, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [4aecc55dcc](https://bsd-hardware.info/?probe=4aecc55dcc) | Oct 30, 2022 |
| Thomas-Kre... | LES network 6L              | Desktop     | [0816f2da97](https://bsd-hardware.info/?probe=0816f2da97) | Oct 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [1eaa616342](https://bsd-hardware.info/?probe=1eaa616342) | Oct 30, 2022 |
| MSI           | H81M-P33                    | Desktop     | [b67d6a7bb2](https://bsd-hardware.info/?probe=b67d6a7bb2) | Oct 30, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [8161bfd24d](https://bsd-hardware.info/?probe=8161bfd24d) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a0896f17e4](https://bsd-hardware.info/?probe=a0896f17e4) | Oct 30, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [d20bfb6d64](https://bsd-hardware.info/?probe=d20bfb6d64) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | Notebook    | [2776d8c350](https://bsd-hardware.info/?probe=2776d8c350) | Oct 30, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [e05d9b2d17](https://bsd-hardware.info/?probe=e05d9b2d17) | Oct 30, 2022 |
| Lenovo        | ThinkPad W530 24491A0       | Notebook    | [4a700f43f8](https://bsd-hardware.info/?probe=4a700f43f8) | Oct 30, 2022 |
| HP            | 843B                        | Desktop     | [d7d572f9ad](https://bsd-hardware.info/?probe=d7d572f9ad) | Oct 29, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [ed59c93b79](https://bsd-hardware.info/?probe=ed59c93b79) | Oct 29, 2022 |
| Sophos        | SG                          | Firewall    | [03633cdc2e](https://bsd-hardware.info/?probe=03633cdc2e) | Oct 29, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [85be4177d6](https://bsd-hardware.info/?probe=85be4177d6) | Oct 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS10N00    | Notebook    | [04ce25bd7f](https://bsd-hardware.info/?probe=04ce25bd7f) | Oct 29, 2022 |
| Sophos        | SG                          | Firewall    | [01f57abe1b](https://bsd-hardware.info/?probe=01f57abe1b) | Oct 29, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [f8652952a4](https://bsd-hardware.info/?probe=f8652952a4) | Oct 29, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [06a8abdbf4](https://bsd-hardware.info/?probe=06a8abdbf4) | Oct 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [acf41f7000](https://bsd-hardware.info/?probe=acf41f7000) | Oct 29, 2022 |
| AWOW          | AK34Pro                     | Mini pc     | [70cc64ba78](https://bsd-hardware.info/?probe=70cc64ba78) | Oct 29, 2022 |
| Samsung       | Q430/Q530                   | Notebook    | [fb98c8c797](https://bsd-hardware.info/?probe=fb98c8c797) | Oct 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [b8323aa325](https://bsd-hardware.info/?probe=b8323aa325) | Oct 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [02d617a604](https://bsd-hardware.info/?probe=02d617a604) | Oct 29, 2022 |
| Dell          | 0XCR8D A01                  | Desktop     | [a019244c85](https://bsd-hardware.info/?probe=a019244c85) | Oct 29, 2022 |
| Acer          | JM11-MS                     | Notebook    | [3ff8b20107](https://bsd-hardware.info/?probe=3ff8b20107) | Oct 29, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [e3c5057898](https://bsd-hardware.info/?probe=e3c5057898) | Oct 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [3744629487](https://bsd-hardware.info/?probe=3744629487) | Oct 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [9a12cd02f0](https://bsd-hardware.info/?probe=9a12cd02f0) | Oct 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [2df5c5b434](https://bsd-hardware.info/?probe=2df5c5b434) | Oct 28, 2022 |
| YANYU         | R250                        | Desktop     | [f39d55e42d](https://bsd-hardware.info/?probe=f39d55e42d) | Oct 28, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [6911e08b7e](https://bsd-hardware.info/?probe=6911e08b7e) | Oct 28, 2022 |
| Intel         | NUC8BEB J72688-306          | Mini pc     | [17f444775b](https://bsd-hardware.info/?probe=17f444775b) | Oct 28, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [484e5520b7](https://bsd-hardware.info/?probe=484e5520b7) | Oct 28, 2022 |
| Centerm       | GA690-2 2                   | Desktop     | [9d6c3d67cd](https://bsd-hardware.info/?probe=9d6c3d67cd) | Oct 28, 2022 |
| MSI           | B360I GMAING PRO AC         | Desktop     | [7287c670f0](https://bsd-hardware.info/?probe=7287c670f0) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c483de83a9](https://bsd-hardware.info/?probe=c483de83a9) | Oct 28, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [6dda683e10](https://bsd-hardware.info/?probe=6dda683e10) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c03e63a0a8](https://bsd-hardware.info/?probe=c03e63a0a8) | Oct 28, 2022 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [f2fafaa9e3](https://bsd-hardware.info/?probe=f2fafaa9e3) | Oct 27, 2022 |
| ASUSTek       | P5BV-M                      | Desktop     | [c5277ae3cd](https://bsd-hardware.info/?probe=c5277ae3cd) | Oct 27, 2022 |
| Unknown       | YL-J3160L4                  | Desktop     | [fa8d5e324b](https://bsd-hardware.info/?probe=fa8d5e324b) | Oct 27, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [015f0a0a6d](https://bsd-hardware.info/?probe=015f0a0a6d) | Oct 27, 2022 |
| PC Engines    | APU2                        | Desktop     | [0c573848ce](https://bsd-hardware.info/?probe=0c573848ce) | Oct 27, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [16c226553c](https://bsd-hardware.info/?probe=16c226553c) | Oct 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e01e68bb2](https://bsd-hardware.info/?probe=4e01e68bb2) | Oct 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [9de7465e6e](https://bsd-hardware.info/?probe=9de7465e6e) | Oct 27, 2022 |
| Dell          | 0CNCJW A08                  | Server      | [38a54bc15c](https://bsd-hardware.info/?probe=38a54bc15c) | Oct 27, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [f89024b7be](https://bsd-hardware.info/?probe=f89024b7be) | Oct 27, 2022 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [d96fbc17b5](https://bsd-hardware.info/?probe=d96fbc17b5) | Oct 27, 2022 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [088e0245af](https://bsd-hardware.info/?probe=088e0245af) | Oct 27, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [766ee6f4eb](https://bsd-hardware.info/?probe=766ee6f4eb) | Oct 27, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [14f174bd7c](https://bsd-hardware.info/?probe=14f174bd7c) | Oct 26, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [d2adcc8230](https://bsd-hardware.info/?probe=d2adcc8230) | Oct 26, 2022 |
| HP            | 8103 A01                    | Mini pc     | [9017d1ac90](https://bsd-hardware.info/?probe=9017d1ac90) | Oct 26, 2022 |
| HP            | 82B4                        | Desktop     | [f3b7970068](https://bsd-hardware.info/?probe=f3b7970068) | Oct 26, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [5d4c95dcac](https://bsd-hardware.info/?probe=5d4c95dcac) | Oct 26, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [7b330abf44](https://bsd-hardware.info/?probe=7b330abf44) | Oct 26, 2022 |
| Dell          | 0CNCJW A08                  | Server      | [a514dcc456](https://bsd-hardware.info/?probe=a514dcc456) | Oct 26, 2022 |
| Dell          | 081N4V A05                  | Server      | [913791b3cc](https://bsd-hardware.info/?probe=913791b3cc) | Oct 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [a6d41c71fd](https://bsd-hardware.info/?probe=a6d41c71fd) | Oct 26, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [f6df7bf1e8](https://bsd-hardware.info/?probe=f6df7bf1e8) | Oct 26, 2022 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [6e8067d4d8](https://bsd-hardware.info/?probe=6e8067d4d8) | Oct 26, 2022 |
| Lenovo        | ThinkPad T420s 4174DL7      | Notebook    | [82d774e711](https://bsd-hardware.info/?probe=82d774e711) | Oct 26, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [b7a4ee06a6](https://bsd-hardware.info/?probe=b7a4ee06a6) | Oct 26, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [84502a19a0](https://bsd-hardware.info/?probe=84502a19a0) | Oct 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [06e6c07e90](https://bsd-hardware.info/?probe=06e6c07e90) | Oct 25, 2022 |
| PC Engines    | APU2                        | Desktop     | [0677b5c196](https://bsd-hardware.info/?probe=0677b5c196) | Oct 25, 2022 |
| Supermicro    | X11SSH-F                    | Server      | [66c10b64cb](https://bsd-hardware.info/?probe=66c10b64cb) | Oct 25, 2022 |
| Dell          | 05XGC8 A01                  | Desktop     | [97947568ee](https://bsd-hardware.info/?probe=97947568ee) | Oct 25, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [69a9ae7bde](https://bsd-hardware.info/?probe=69a9ae7bde) | Oct 25, 2022 |
| PC Engines    | apu1                        | Desktop     | [b8643f364d](https://bsd-hardware.info/?probe=b8643f364d) | Oct 25, 2022 |
| PC Engines    | APU2                        | Desktop     | [d52e3d0ce3](https://bsd-hardware.info/?probe=d52e3d0ce3) | Oct 25, 2022 |
| Samsung       | Q430/Q530                   | Notebook    | [4965215a13](https://bsd-hardware.info/?probe=4965215a13) | Oct 25, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [f2236f17ee](https://bsd-hardware.info/?probe=f2236f17ee) | Oct 25, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [0e2cd201d0](https://bsd-hardware.info/?probe=0e2cd201d0) | Oct 24, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [c4bbcf9537](https://bsd-hardware.info/?probe=c4bbcf9537) | Oct 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [51ec4ce710](https://bsd-hardware.info/?probe=51ec4ce710) | Oct 24, 2022 |
| Acer          | Veriton X2610G              | Desktop     | [e4289c3f15](https://bsd-hardware.info/?probe=e4289c3f15) | Oct 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [1f2cd1f9ea](https://bsd-hardware.info/?probe=1f2cd1f9ea) | Oct 24, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [079830f938](https://bsd-hardware.info/?probe=079830f938) | Oct 24, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2fa4641b0e](https://bsd-hardware.info/?probe=2fa4641b0e) | Oct 24, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [09e5063724](https://bsd-hardware.info/?probe=09e5063724) | Oct 24, 2022 |
| ZOTAC         | ZBOX-MI522NANO/MI542NANO    | Mini pc     | [0d6e868d9c](https://bsd-hardware.info/?probe=0d6e868d9c) | Oct 24, 2022 |
| Intel         | H81U                        | Notebook    | [b0e1f80338](https://bsd-hardware.info/?probe=b0e1f80338) | Oct 24, 2022 |
| Cisco         | ASA5515 A0                  | Desktop     | [3f20d7f9bb](https://bsd-hardware.info/?probe=3f20d7f9bb) | Oct 24, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [eea9a0bef3](https://bsd-hardware.info/?probe=eea9a0bef3) | Oct 24, 2022 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [0708c0f089](https://bsd-hardware.info/?probe=0708c0f089) | Oct 24, 2022 |
| Intel         | D34010WYK H14771-305        | Desktop     | [5414062624](https://bsd-hardware.info/?probe=5414062624) | Oct 24, 2022 |
| Unknown       | YL-J3160L4                  | Desktop     | [746694bb1d](https://bsd-hardware.info/?probe=746694bb1d) | Oct 24, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [607fcd2571](https://bsd-hardware.info/?probe=607fcd2571) | Oct 24, 2022 |
| Sophos        | SG                          | Firewall    | [bb50acf083](https://bsd-hardware.info/?probe=bb50acf083) | Oct 24, 2022 |
| HP            | ProLiant DL360 G5           | Server      | [8a90c37da4](https://bsd-hardware.info/?probe=8a90c37da4) | Oct 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [caad4323ba](https://bsd-hardware.info/?probe=caad4323ba) | Oct 23, 2022 |
| ASUSTek       | P5BV-M                      | Desktop     | [f7bfa3deed](https://bsd-hardware.info/?probe=f7bfa3deed) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [6f0d5a7497](https://bsd-hardware.info/?probe=6f0d5a7497) | Oct 23, 2022 |
| Dell          | Latitude 5591               | Notebook    | [58b577382a](https://bsd-hardware.info/?probe=58b577382a) | Oct 23, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [10ea57e48f](https://bsd-hardware.info/?probe=10ea57e48f) | Oct 23, 2022 |
| MSI           | H81M-P33                    | Desktop     | [626f503cad](https://bsd-hardware.info/?probe=626f503cad) | Oct 23, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [2b98739799](https://bsd-hardware.info/?probe=2b98739799) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [56dac6bc80](https://bsd-hardware.info/?probe=56dac6bc80) | Oct 23, 2022 |
| HP            | 843B                        | Desktop     | [9ea2590610](https://bsd-hardware.info/?probe=9ea2590610) | Oct 23, 2022 |
| Unknown       | 1.21                        | Desktop     | [f8a845fcda](https://bsd-hardware.info/?probe=f8a845fcda) | Oct 23, 2022 |
| IBM           | 49Y6512                     | Server      | [1bc9e20b16](https://bsd-hardware.info/?probe=1bc9e20b16) | Oct 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [89d0639a68](https://bsd-hardware.info/?probe=89d0639a68) | Oct 23, 2022 |
| Lenovo        | ThinkServer RS140           | Server      | [d6111b8ff1](https://bsd-hardware.info/?probe=d6111b8ff1) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [d7829c8f35](https://bsd-hardware.info/?probe=d7829c8f35) | Oct 22, 2022 |
| Cisco         | ASA5515 A0                  | Desktop     | [7f848d7c57](https://bsd-hardware.info/?probe=7f848d7c57) | Oct 22, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [521283b723](https://bsd-hardware.info/?probe=521283b723) | Oct 22, 2022 |
| Alienware     | m15                         | Notebook    | [3304a767ba](https://bsd-hardware.info/?probe=3304a767ba) | Oct 22, 2022 |
| Dell          | 01W23F A02                  | Server      | [8e2465430e](https://bsd-hardware.info/?probe=8e2465430e) | Oct 22, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [af3a73431f](https://bsd-hardware.info/?probe=af3a73431f) | Oct 22, 2022 |
| Google        | Edgar                       | Notebook    | [318a750368](https://bsd-hardware.info/?probe=318a750368) | Oct 22, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [a1b0ef3b39](https://bsd-hardware.info/?probe=a1b0ef3b39) | Oct 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [410283dd4f](https://bsd-hardware.info/?probe=410283dd4f) | Oct 22, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [8a4e3767e9](https://bsd-hardware.info/?probe=8a4e3767e9) | Oct 22, 2022 |
| HP            | 8719                        | Desktop     | [6bca1a0466](https://bsd-hardware.info/?probe=6bca1a0466) | Oct 22, 2022 |
| HP            | 8103 A01                    | Mini pc     | [d7df2919b1](https://bsd-hardware.info/?probe=d7df2919b1) | Oct 22, 2022 |
| HP            | 8103 A01                    | Mini pc     | [ff724ee8a1](https://bsd-hardware.info/?probe=ff724ee8a1) | Oct 22, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [172b2c53fe](https://bsd-hardware.info/?probe=172b2c53fe) | Oct 22, 2022 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [d7b32200a5](https://bsd-hardware.info/?probe=d7b32200a5) | Oct 22, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [947d061849](https://bsd-hardware.info/?probe=947d061849) | Oct 22, 2022 |
| Sophos        | UTM                         | Firewall    | [bae9180e3f](https://bsd-hardware.info/?probe=bae9180e3f) | Oct 22, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [803b44339b](https://bsd-hardware.info/?probe=803b44339b) | Oct 22, 2022 |
| Supermicro    | X9DRD-iF                    | Server      | [d21c2d1a10](https://bsd-hardware.info/?probe=d21c2d1a10) | Oct 22, 2022 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [f27ff1a7c3](https://bsd-hardware.info/?probe=f27ff1a7c3) | Oct 22, 2022 |
| Supermicro    | X9DRD-iF                    | Server      | [c708a7828f](https://bsd-hardware.info/?probe=c708a7828f) | Oct 22, 2022 |
| Dell          | 0M877N A00                  | Server      | [dd965c2bfc](https://bsd-hardware.info/?probe=dd965c2bfc) | Oct 22, 2022 |
| Dell          | 0KM5PX A04                  | Server      | [9c2ca983ac](https://bsd-hardware.info/?probe=9c2ca983ac) | Oct 22, 2022 |
| MSI           | 890GXM-G65                  | Desktop     | [03c116d78f](https://bsd-hardware.info/?probe=03c116d78f) | Oct 22, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [623594855a](https://bsd-hardware.info/?probe=623594855a) | Oct 22, 2022 |
| Alienware     | 0PGRP5 A01                  | Desktop     | [e34219da0f](https://bsd-hardware.info/?probe=e34219da0f) | Oct 22, 2022 |
| Gigabyte      | 945PLM-S2                   | Desktop     | [ca0d187a0b](https://bsd-hardware.info/?probe=ca0d187a0b) | Oct 22, 2022 |
| Gigabyte      | 945PLM-S2                   | Desktop     | [5b8c853c20](https://bsd-hardware.info/?probe=5b8c853c20) | Oct 22, 2022 |
| Acer          | Revo RN86                   | Desktop     | [692ea69bab](https://bsd-hardware.info/?probe=692ea69bab) | Oct 21, 2022 |
| PC Engines    | APU2                        | Desktop     | [f9ca8e5fdd](https://bsd-hardware.info/?probe=f9ca8e5fdd) | Oct 21, 2022 |
| Intel         | H67SL_VER1.2A               | Desktop     | [a469ad62a4](https://bsd-hardware.info/?probe=a469ad62a4) | Oct 21, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0cd674332b](https://bsd-hardware.info/?probe=0cd674332b) | Oct 21, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [54e4202bc7](https://bsd-hardware.info/?probe=54e4202bc7) | Oct 21, 2022 |
| PC Engines    | APU2                        | Desktop     | [cf1abf5e46](https://bsd-hardware.info/?probe=cf1abf5e46) | Oct 21, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [764a816130](https://bsd-hardware.info/?probe=764a816130) | Oct 21, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3b11114e36](https://bsd-hardware.info/?probe=3b11114e36) | Oct 21, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [d04ef8c45b](https://bsd-hardware.info/?probe=d04ef8c45b) | Oct 21, 2022 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [12f7ac40ac](https://bsd-hardware.info/?probe=12f7ac40ac) | Oct 21, 2022 |
| Sophos        | UTM                         | Firewall    | [6a4c00a973](https://bsd-hardware.info/?probe=6a4c00a973) | Oct 21, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [a47e59ad6b](https://bsd-hardware.info/?probe=a47e59ad6b) | Oct 21, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [eb9ffe08e7](https://bsd-hardware.info/?probe=eb9ffe08e7) | Oct 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [d5586487b4](https://bsd-hardware.info/?probe=d5586487b4) | Oct 21, 2022 |
| Protectli     | FW6                         | Desktop     | [528ef94fb5](https://bsd-hardware.info/?probe=528ef94fb5) | Oct 21, 2022 |
| HP            | 18E4                        | Desktop     | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| ASUSTek       | P10S-I Series               | Desktop     | [ceb58e75b8](https://bsd-hardware.info/?probe=ceb58e75b8) | Oct 20, 2022 |
| Dell          | Precision M4500             | Notebook    | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7ecffc1ca3](https://bsd-hardware.info/?probe=7ecffc1ca3) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [eb6eda641d](https://bsd-hardware.info/?probe=eb6eda641d) | Oct 20, 2022 |
| Hardkernel    | ODROID-H3                   | Desktop     | [304db9bbbf](https://bsd-hardware.info/?probe=304db9bbbf) | Oct 20, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [09bca1b1ff](https://bsd-hardware.info/?probe=09bca1b1ff) | Oct 20, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [c6ee09790d](https://bsd-hardware.info/?probe=c6ee09790d) | Oct 20, 2022 |
| ASRock        | B460M-ITX/ac                | Desktop     | [c1a691f99c](https://bsd-hardware.info/?probe=c1a691f99c) | Oct 20, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [348bef7dba](https://bsd-hardware.info/?probe=348bef7dba) | Oct 20, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [3d62c50607](https://bsd-hardware.info/?probe=3d62c50607) | Oct 20, 2022 |
| Sophos        | SG                          | Firewall    | [a8593e1424](https://bsd-hardware.info/?probe=a8593e1424) | Oct 20, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [bef50b27cb](https://bsd-hardware.info/?probe=bef50b27cb) | Oct 20, 2022 |
| PC Engines    | APU2                        | Desktop     | [c2e7b76bdf](https://bsd-hardware.info/?probe=c2e7b76bdf) | Oct 20, 2022 |
| PC Engines    | APU2                        | Desktop     | [ade8432e80](https://bsd-hardware.info/?probe=ade8432e80) | Oct 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [1778396ba9](https://bsd-hardware.info/?probe=1778396ba9) | Oct 20, 2022 |
| MSI           | PS63 Modern 8M              | Notebook    | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| Dell          | 012KND A00                  | Mini pc     | [c59e578a6f](https://bsd-hardware.info/?probe=c59e578a6f) | Oct 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [1188b56e14](https://bsd-hardware.info/?probe=1188b56e14) | Oct 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [915c66f8bd](https://bsd-hardware.info/?probe=915c66f8bd) | Oct 19, 2022 |
| Protectli     | FW6                         | Desktop     | [a7dabc97b0](https://bsd-hardware.info/?probe=a7dabc97b0) | Oct 19, 2022 |
| Quanmax       | spo-book TECH QUAD B1       | Desktop     | [f3db09e0f0](https://bsd-hardware.info/?probe=f3db09e0f0) | Oct 19, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [ef14460db8](https://bsd-hardware.info/?probe=ef14460db8) | Oct 19, 2022 |
| Supermicro    | X11SSL-F                    | Desktop     | [24faa4663c](https://bsd-hardware.info/?probe=24faa4663c) | Oct 19, 2022 |
| Protectli     | FW4B                        | Desktop     | [0acd6e1143](https://bsd-hardware.info/?probe=0acd6e1143) | Oct 19, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [fa1f806269](https://bsd-hardware.info/?probe=fa1f806269) | Oct 19, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [a6c8096599](https://bsd-hardware.info/?probe=a6c8096599) | Oct 19, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [3e2f5956c1](https://bsd-hardware.info/?probe=3e2f5956c1) | Oct 19, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [8c6555d6be](https://bsd-hardware.info/?probe=8c6555d6be) | Oct 18, 2022 |
| ASUSTek       | E35M1-I DELUXE              | Desktop     | [2fdf1c6db6](https://bsd-hardware.info/?probe=2fdf1c6db6) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [20ff21d751](https://bsd-hardware.info/?probe=20ff21d751) | Oct 18, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [f84b205626](https://bsd-hardware.info/?probe=f84b205626) | Oct 18, 2022 |
| Lenovo        | 30D0 NOK                    | Desktop     | [d1fab8bd54](https://bsd-hardware.info/?probe=d1fab8bd54) | Oct 18, 2022 |
| Iomega        | StorCenter Pro px2 SA       | Desktop     | [d4e8f25586](https://bsd-hardware.info/?probe=d4e8f25586) | Oct 18, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [c75bcb519e](https://bsd-hardware.info/?probe=c75bcb519e) | Oct 18, 2022 |
| Intel         | NUC9i7QNB K49245-500        | Mini pc     | [154dad5874](https://bsd-hardware.info/?probe=154dad5874) | Oct 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [c7971db0b8](https://bsd-hardware.info/?probe=c7971db0b8) | Oct 18, 2022 |
| ASUSTek       | N3050I-C                    | Desktop     | [4a83b0953e](https://bsd-hardware.info/?probe=4a83b0953e) | Oct 18, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [45d6590312](https://bsd-hardware.info/?probe=45d6590312) | Oct 18, 2022 |
| Dell          | 02K9CR A02                  | Desktop     | [a5cda6c49e](https://bsd-hardware.info/?probe=a5cda6c49e) | Oct 18, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [2e4cd910d7](https://bsd-hardware.info/?probe=2e4cd910d7) | Oct 17, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Dell          | 0CNCJW A10                  | Server      | [1bc8c02062](https://bsd-hardware.info/?probe=1bc8c02062) | Oct 17, 2022 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [50c3c93790](https://bsd-hardware.info/?probe=50c3c93790) | Oct 17, 2022 |
| Dell          | 0CNCJW A10                  | Server      | [25666c6950](https://bsd-hardware.info/?probe=25666c6950) | Oct 17, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [7024873a21](https://bsd-hardware.info/?probe=7024873a21) | Oct 17, 2022 |
| PC Engines    | apu4                        | Desktop     | [20cfd8a3c8](https://bsd-hardware.info/?probe=20cfd8a3c8) | Oct 17, 2022 |
| NF541         | 1.0                         | Desktop     | [6f4f72398d](https://bsd-hardware.info/?probe=6f4f72398d) | Oct 17, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [c57cc3a923](https://bsd-hardware.info/?probe=c57cc3a923) | Oct 17, 2022 |
| BESSTAR Te... | GB7B                        | Mini pc     | [75ee70a8cd](https://bsd-hardware.info/?probe=75ee70a8cd) | Oct 17, 2022 |
| Intel         | DH57DD AAE82022-202         | Desktop     | [01622a2528](https://bsd-hardware.info/?probe=01622a2528) | Oct 17, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [242e320350](https://bsd-hardware.info/?probe=242e320350) | Oct 17, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [e057b613a0](https://bsd-hardware.info/?probe=e057b613a0) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2885a5ce85](https://bsd-hardware.info/?probe=2885a5ce85) | Oct 17, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [c3f0ae254e](https://bsd-hardware.info/?probe=c3f0ae254e) | Oct 17, 2022 |
| HP            | 1588h                       | Desktop     | [e78a0308c7](https://bsd-hardware.info/?probe=e78a0308c7) | Oct 16, 2022 |
| Lenovo        | XiaoXinPro-13API 2019 81... | Notebook    | [dfa08657fd](https://bsd-hardware.info/?probe=dfa08657fd) | Oct 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [4fd307fbb4](https://bsd-hardware.info/?probe=4fd307fbb4) | Oct 16, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [f7d0616889](https://bsd-hardware.info/?probe=f7d0616889) | Oct 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0c91327549](https://bsd-hardware.info/?probe=0c91327549) | Oct 16, 2022 |
| HP            | 8719                        | Desktop     | [87efb126fc](https://bsd-hardware.info/?probe=87efb126fc) | Oct 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e7fe2f3a54](https://bsd-hardware.info/?probe=e7fe2f3a54) | Oct 16, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [d32449b8c4](https://bsd-hardware.info/?probe=d32449b8c4) | Oct 16, 2022 |
| HP            | SpectreXT Pro 13-b000 PC    | Notebook    | [f45ea42873](https://bsd-hardware.info/?probe=f45ea42873) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f80953ee2f](https://bsd-hardware.info/?probe=f80953ee2f) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f27ffa7217](https://bsd-hardware.info/?probe=f27ffa7217) | Oct 16, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [22881028bc](https://bsd-hardware.info/?probe=22881028bc) | Oct 16, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [b4e02e3f51](https://bsd-hardware.info/?probe=b4e02e3f51) | Oct 16, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [77d3019212](https://bsd-hardware.info/?probe=77d3019212) | Oct 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [baf0edf73a](https://bsd-hardware.info/?probe=baf0edf73a) | Oct 16, 2022 |
| Protectli     | FW4B                        | Desktop     | [57ae1d8cda](https://bsd-hardware.info/?probe=57ae1d8cda) | Oct 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [83ceb2fb33](https://bsd-hardware.info/?probe=83ceb2fb33) | Oct 15, 2022 |
| PC Engines    | apu4                        | Desktop     | [cefbafec73](https://bsd-hardware.info/?probe=cefbafec73) | Oct 15, 2022 |
| HP            | 8169                        | Desktop     | [86b1fbf917](https://bsd-hardware.info/?probe=86b1fbf917) | Oct 15, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [76a1007c46](https://bsd-hardware.info/?probe=76a1007c46) | Oct 15, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [55967e02f6](https://bsd-hardware.info/?probe=55967e02f6) | Oct 15, 2022 |
| Sophos        | SG                          | Firewall    | [885bf4ef1e](https://bsd-hardware.info/?probe=885bf4ef1e) | Oct 15, 2022 |
| TYAN Compu... | Tiger K8W Dual AMD Opter... | Desktop     | [bbd42243ae](https://bsd-hardware.info/?probe=bbd42243ae) | Oct 15, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [b02dcbb7b5](https://bsd-hardware.info/?probe=b02dcbb7b5) | Oct 15, 2022 |
| TYAN Compu... | Tiger K8W Dual AMD Opter... | Desktop     | [0e9ac1e935](https://bsd-hardware.info/?probe=0e9ac1e935) | Oct 15, 2022 |
| ASRock        | Q1900M                      | Desktop     | [7d0380e2d0](https://bsd-hardware.info/?probe=7d0380e2d0) | Oct 15, 2022 |
| Dell          | 081N4V A09                  | Server      | [3cbacacfa4](https://bsd-hardware.info/?probe=3cbacacfa4) | Oct 15, 2022 |
| HP            | Laptop 15q-bu0xx            | Notebook    | [99c01654a2](https://bsd-hardware.info/?probe=99c01654a2) | Oct 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [a8bdbe4d1b](https://bsd-hardware.info/?probe=a8bdbe4d1b) | Oct 15, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [799410c58f](https://bsd-hardware.info/?probe=799410c58f) | Oct 15, 2022 |
| TYAN Compu... | Intel 440BX/GX Rev. 4       | Desktop     | [8d99f317e4](https://bsd-hardware.info/?probe=8d99f317e4) | Oct 15, 2022 |
| Dell          | 0G1548 A00                  | Desktop     | [226af33d5b](https://bsd-hardware.info/?probe=226af33d5b) | Oct 15, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [73960ade29](https://bsd-hardware.info/?probe=73960ade29) | Oct 15, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [06214241b3](https://bsd-hardware.info/?probe=06214241b3) | Oct 15, 2022 |
| Sophos        | SG                          | Firewall    | [4fbe0156a8](https://bsd-hardware.info/?probe=4fbe0156a8) | Oct 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5a56504b92](https://bsd-hardware.info/?probe=5a56504b92) | Oct 15, 2022 |
| AZW           | Green G1                    | Desktop     | [f6f16c5141](https://bsd-hardware.info/?probe=f6f16c5141) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [6b15856d20](https://bsd-hardware.info/?probe=6b15856d20) | Oct 15, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ae4868c65b](https://bsd-hardware.info/?probe=ae4868c65b) | Oct 15, 2022 |
| Sophos        | XG                          | Firewall    | [e80ccac6ff](https://bsd-hardware.info/?probe=e80ccac6ff) | Oct 15, 2022 |
| Lenovo        | ThinkCentre M57p 6078AJ6    | Desktop     | [a808a7360d](https://bsd-hardware.info/?probe=a808a7360d) | Oct 14, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [e08c408ced](https://bsd-hardware.info/?probe=e08c408ced) | Oct 14, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [27d7eb468e](https://bsd-hardware.info/?probe=27d7eb468e) | Oct 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [3b7146c456](https://bsd-hardware.info/?probe=3b7146c456) | Oct 14, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e67cb3a0c5](https://bsd-hardware.info/?probe=e67cb3a0c5) | Oct 14, 2022 |
| Supermicro    | X10SLL-F                    | Desktop     | [3b13ea475b](https://bsd-hardware.info/?probe=3b13ea475b) | Oct 14, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5acdcd628d](https://bsd-hardware.info/?probe=5acdcd628d) | Oct 14, 2022 |
| PC Engines    | apu1                        | Desktop     | [06debf0076](https://bsd-hardware.info/?probe=06debf0076) | Oct 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [1ad8d9e64c](https://bsd-hardware.info/?probe=1ad8d9e64c) | Oct 14, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [91cc2cadd4](https://bsd-hardware.info/?probe=91cc2cadd4) | Oct 14, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [17a6b61af7](https://bsd-hardware.info/?probe=17a6b61af7) | Oct 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [6c330d9bab](https://bsd-hardware.info/?probe=6c330d9bab) | Oct 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [856e29140e](https://bsd-hardware.info/?probe=856e29140e) | Oct 14, 2022 |
| IBM           | 49Y6512                     | Server      | [4471bf6465](https://bsd-hardware.info/?probe=4471bf6465) | Oct 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [0e09ac984a](https://bsd-hardware.info/?probe=0e09ac984a) | Oct 14, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3a84a32c84](https://bsd-hardware.info/?probe=3a84a32c84) | Oct 14, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [42c01a3aaf](https://bsd-hardware.info/?probe=42c01a3aaf) | Oct 13, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [d7c3749eba](https://bsd-hardware.info/?probe=d7c3749eba) | Oct 13, 2022 |
| Sophos        | UTM                         | Firewall    | [364e007b1c](https://bsd-hardware.info/?probe=364e007b1c) | Oct 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [10358c7207](https://bsd-hardware.info/?probe=10358c7207) | Oct 13, 2022 |
| HP            | 260 G3 DM                   | Desktop     | [3ad5292d71](https://bsd-hardware.info/?probe=3ad5292d71) | Oct 13, 2022 |
| HP            | Compaq nw8440 (RND39ET)     | Desktop     | [55bef385e3](https://bsd-hardware.info/?probe=55bef385e3) | Oct 13, 2022 |
| Intel         | H81U                        | Notebook    | [9b212d2264](https://bsd-hardware.info/?probe=9b212d2264) | Oct 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b20b6c7997](https://bsd-hardware.info/?probe=b20b6c7997) | Oct 13, 2022 |
| IBM           | 49Y6512                     | Server      | [1ead286cbe](https://bsd-hardware.info/?probe=1ead286cbe) | Oct 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [00b5fa7a4e](https://bsd-hardware.info/?probe=00b5fa7a4e) | Oct 13, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [0da821d451](https://bsd-hardware.info/?probe=0da821d451) | Oct 13, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [9757e40c42](https://bsd-hardware.info/?probe=9757e40c42) | Oct 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [763365591a](https://bsd-hardware.info/?probe=763365591a) | Oct 12, 2022 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [ba30f2772b](https://bsd-hardware.info/?probe=ba30f2772b) | Oct 12, 2022 |
| PC Engines    | APU2                        | Desktop     | [a06a344954](https://bsd-hardware.info/?probe=a06a344954) | Oct 12, 2022 |
| Unknown       | YL-1900L4-V2                | Desktop     | [1f55db62cc](https://bsd-hardware.info/?probe=1f55db62cc) | Oct 12, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [0da59dff8f](https://bsd-hardware.info/?probe=0da59dff8f) | Oct 12, 2022 |
| Lenovo        | ThinkPad T440s 20AR003SM... | Notebook    | [df62882c3b](https://bsd-hardware.info/?probe=df62882c3b) | Oct 12, 2022 |
| HP            | 1589                        | Desktop     | [0696d30d3f](https://bsd-hardware.info/?probe=0696d30d3f) | Oct 12, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [ea8b1fd760](https://bsd-hardware.info/?probe=ea8b1fd760) | Oct 12, 2022 |
| Dell          | Latitude 5591               | Notebook    | [04f53f51c8](https://bsd-hardware.info/?probe=04f53f51c8) | Oct 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [7000ef7aeb](https://bsd-hardware.info/?probe=7000ef7aeb) | Oct 12, 2022 |
| Protectli     | FW4B                        | Desktop     | [2fd9fcda8e](https://bsd-hardware.info/?probe=2fd9fcda8e) | Oct 11, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [6674bbf7f3](https://bsd-hardware.info/?probe=6674bbf7f3) | Oct 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [94915735cc](https://bsd-hardware.info/?probe=94915735cc) | Oct 11, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [abceadc2e3](https://bsd-hardware.info/?probe=abceadc2e3) | Oct 11, 2022 |
| AMD           | Inagua CRB                  | Desktop     | [59c41dcd31](https://bsd-hardware.info/?probe=59c41dcd31) | Oct 11, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ff2b9a916f](https://bsd-hardware.info/?probe=ff2b9a916f) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [869687f6f0](https://bsd-hardware.info/?probe=869687f6f0) | Oct 11, 2022 |
| AMD           | Inagua CRB                  | Desktop     | [ff4eccae8a](https://bsd-hardware.info/?probe=ff4eccae8a) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [9d3b9cb318](https://bsd-hardware.info/?probe=9d3b9cb318) | Oct 11, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [097a263bfc](https://bsd-hardware.info/?probe=097a263bfc) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [f4b5bf9026](https://bsd-hardware.info/?probe=f4b5bf9026) | Oct 11, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [2cba6fbbb7](https://bsd-hardware.info/?probe=2cba6fbbb7) | Oct 11, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [edead8a3ae](https://bsd-hardware.info/?probe=edead8a3ae) | Oct 11, 2022 |
| Dell          | 0WC7KF A00                  | All in one  | [5f271a82bf](https://bsd-hardware.info/?probe=5f271a82bf) | Oct 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [a773a82ff4](https://bsd-hardware.info/?probe=a773a82ff4) | Oct 11, 2022 |
| Dell          | 0WC7KF A00                  | All in one  | [0f87a99ca7](https://bsd-hardware.info/?probe=0f87a99ca7) | Oct 11, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [dec7108b53](https://bsd-hardware.info/?probe=dec7108b53) | Oct 11, 2022 |
| AZW           | U59                         | Desktop     | [8839497803](https://bsd-hardware.info/?probe=8839497803) | Oct 11, 2022 |
| Dell          | Latitude 5591               | Notebook    | [eda94b6c48](https://bsd-hardware.info/?probe=eda94b6c48) | Oct 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [a5cbd6786d](https://bsd-hardware.info/?probe=a5cbd6786d) | Oct 11, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [4fb69eef28](https://bsd-hardware.info/?probe=4fb69eef28) | Oct 11, 2022 |
| Shuttle       | FH170                       | Desktop     | [8fd08beffa](https://bsd-hardware.info/?probe=8fd08beffa) | Oct 10, 2022 |
| Acer          | Aspire 5336                 | Notebook    | [127ddc93fb](https://bsd-hardware.info/?probe=127ddc93fb) | Oct 10, 2022 |
| Acer          | Aspire E5-722G              | Notebook    | [7a4eb565fe](https://bsd-hardware.info/?probe=7a4eb565fe) | Oct 10, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [58b53464d1](https://bsd-hardware.info/?probe=58b53464d1) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [c70e4d6b3c](https://bsd-hardware.info/?probe=c70e4d6b3c) | Oct 10, 2022 |
| NU941         | 1.0                         | Desktop     | [2690c2a8df](https://bsd-hardware.info/?probe=2690c2a8df) | Oct 10, 2022 |
| Lenovo        | 316E NOK                    | Mini pc     | [2a7c8f55cb](https://bsd-hardware.info/?probe=2a7c8f55cb) | Oct 10, 2022 |
| ASRock        | J4005B-ITX                  | Desktop     | [6cf37e95da](https://bsd-hardware.info/?probe=6cf37e95da) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [4c9069df20](https://bsd-hardware.info/?probe=4c9069df20) | Oct 10, 2022 |
| HP            | 1495                        | Desktop     | [cfa8ab5df3](https://bsd-hardware.info/?probe=cfa8ab5df3) | Oct 10, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [d802705c1d](https://bsd-hardware.info/?probe=d802705c1d) | Oct 10, 2022 |
| Clevo         | R130T                       | Desktop     | [6f8a6bf77c](https://bsd-hardware.info/?probe=6f8a6bf77c) | Oct 10, 2022 |
| MSI           | GL65 Leopard 10SFSK         | Notebook    | [2ea7c7f9a2](https://bsd-hardware.info/?probe=2ea7c7f9a2) | Oct 10, 2022 |
| Dell          | Latitude E6420              | Notebook    | [48c26d2a17](https://bsd-hardware.info/?probe=48c26d2a17) | Oct 10, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8b8f621562](https://bsd-hardware.info/?probe=8b8f621562) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [21117c0374](https://bsd-hardware.info/?probe=21117c0374) | Oct 10, 2022 |
| CncTion       | Jasper-4L B0                | Desktop     | [53c643dc95](https://bsd-hardware.info/?probe=53c643dc95) | Oct 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [2fc5bd737a](https://bsd-hardware.info/?probe=2fc5bd737a) | Oct 09, 2022 |
| Protectli     | FW1 Ver                     | Desktop     | [1015ef5e66](https://bsd-hardware.info/?probe=1015ef5e66) | Oct 09, 2022 |
| HP            | 8103 A01                    | Mini pc     | [f187229469](https://bsd-hardware.info/?probe=f187229469) | Oct 09, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [e08e2ca6e0](https://bsd-hardware.info/?probe=e08e2ca6e0) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [3a86733538](https://bsd-hardware.info/?probe=3a86733538) | Oct 09, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [5d929362ca](https://bsd-hardware.info/?probe=5d929362ca) | Oct 09, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [c79fa6f001](https://bsd-hardware.info/?probe=c79fa6f001) | Oct 09, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [73c9bfe38b](https://bsd-hardware.info/?probe=73c9bfe38b) | Oct 09, 2022 |
| HP            | 84F5                        | Mini pc     | [99c0387102](https://bsd-hardware.info/?probe=99c0387102) | Oct 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [e595ade938](https://bsd-hardware.info/?probe=e595ade938) | Oct 09, 2022 |
| ASRock        | J4005B-ITX                  | Desktop     | [0e0ff27c25](https://bsd-hardware.info/?probe=0e0ff27c25) | Oct 09, 2022 |
| MiTAC         | PH11CMI                     | Desktop     | [71802cdcad](https://bsd-hardware.info/?probe=71802cdcad) | Oct 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [464739212c](https://bsd-hardware.info/?probe=464739212c) | Oct 08, 2022 |
| HP            | 339A                        | Desktop     | [7ad68046ce](https://bsd-hardware.info/?probe=7ad68046ce) | Oct 08, 2022 |
| HP            | 86FC MVB                    | Desktop     | [56453b00c8](https://bsd-hardware.info/?probe=56453b00c8) | Oct 08, 2022 |
| HP            | 86FC MVB                    | Desktop     | [c542b16d75](https://bsd-hardware.info/?probe=c542b16d75) | Oct 08, 2022 |
| HP            | 84F5                        | Mini pc     | [ecdab22807](https://bsd-hardware.info/?probe=ecdab22807) | Oct 08, 2022 |
| Soekris En... | net6501                     | Desktop     | [1cb23f6bda](https://bsd-hardware.info/?probe=1cb23f6bda) | Oct 08, 2022 |
| Soekris En... | net6501                     | Desktop     | [03ee772b1f](https://bsd-hardware.info/?probe=03ee772b1f) | Oct 08, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [17d766d55a](https://bsd-hardware.info/?probe=17d766d55a) | Oct 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [f31f4c00cd](https://bsd-hardware.info/?probe=f31f4c00cd) | Oct 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [e76890ff26](https://bsd-hardware.info/?probe=e76890ff26) | Oct 08, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [442a743538](https://bsd-hardware.info/?probe=442a743538) | Oct 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [d6396a74dd](https://bsd-hardware.info/?probe=d6396a74dd) | Oct 08, 2022 |
| HP            | 18E7                        | Desktop     | [35e68316d8](https://bsd-hardware.info/?probe=35e68316d8) | Oct 08, 2022 |
| Lenovo        | ThinkCentre M72e 3664AD9    | Desktop     | [f6fded284d](https://bsd-hardware.info/?probe=f6fded284d) | Oct 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [e4e47282a9](https://bsd-hardware.info/?probe=e4e47282a9) | Oct 08, 2022 |
| ZOTAC         | ZBOX-CI527/CI547            | Mini pc     | [231a0f9ce0](https://bsd-hardware.info/?probe=231a0f9ce0) | Oct 08, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [82335a8874](https://bsd-hardware.info/?probe=82335a8874) | Oct 07, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [384de92279](https://bsd-hardware.info/?probe=384de92279) | Oct 07, 2022 |
| Supermicro    | X8DT6                       | Server      | [2bd1529913](https://bsd-hardware.info/?probe=2bd1529913) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [d25832111e](https://bsd-hardware.info/?probe=d25832111e) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [a34c1b8ccd](https://bsd-hardware.info/?probe=a34c1b8ccd) | Oct 07, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [9d3eed2bec](https://bsd-hardware.info/?probe=9d3eed2bec) | Oct 07, 2022 |
| ASRockRack    | EP2C612D16FM                | Desktop     | [30a582fccb](https://bsd-hardware.info/?probe=30a582fccb) | Oct 07, 2022 |
| Lenovo        | ThinkPad X270 20HMS04P00    | Notebook    | [7647b7a0b2](https://bsd-hardware.info/?probe=7647b7a0b2) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [ad8b88d10b](https://bsd-hardware.info/?probe=ad8b88d10b) | Oct 07, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [31ce3d5e46](https://bsd-hardware.info/?probe=31ce3d5e46) | Oct 07, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [ce728798a1](https://bsd-hardware.info/?probe=ce728798a1) | Oct 07, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [36fb81bec0](https://bsd-hardware.info/?probe=36fb81bec0) | Oct 07, 2022 |
| YANYU         | H67SL                       | Desktop     | [373902d38b](https://bsd-hardware.info/?probe=373902d38b) | Oct 07, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [92a125995f](https://bsd-hardware.info/?probe=92a125995f) | Oct 07, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [a28ea59f1f](https://bsd-hardware.info/?probe=a28ea59f1f) | Oct 07, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [130a05a115](https://bsd-hardware.info/?probe=130a05a115) | Oct 07, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [84300e7dcc](https://bsd-hardware.info/?probe=84300e7dcc) | Oct 07, 2022 |
| ADI Engine... | RCC-VE                      | Desktop     | [f6a9012bb2](https://bsd-hardware.info/?probe=f6a9012bb2) | Oct 07, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [7e24ab5841](https://bsd-hardware.info/?probe=7e24ab5841) | Oct 07, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [11e04b0c73](https://bsd-hardware.info/?probe=11e04b0c73) | Oct 07, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [34d05fe49c](https://bsd-hardware.info/?probe=34d05fe49c) | Oct 07, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [f521533d51](https://bsd-hardware.info/?probe=f521533d51) | Oct 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [7658e5e20d](https://bsd-hardware.info/?probe=7658e5e20d) | Oct 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [601029d3fc](https://bsd-hardware.info/?probe=601029d3fc) | Oct 06, 2022 |
| PC Engines    | apu1                        | Desktop     | [1a8ff34d31](https://bsd-hardware.info/?probe=1a8ff34d31) | Oct 06, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [cc0380b2c6](https://bsd-hardware.info/?probe=cc0380b2c6) | Oct 06, 2022 |
| PC Engines    | APU2                        | Desktop     | [02416f3157](https://bsd-hardware.info/?probe=02416f3157) | Oct 06, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [6dff6ec466](https://bsd-hardware.info/?probe=6dff6ec466) | Oct 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [b889791d9f](https://bsd-hardware.info/?probe=b889791d9f) | Oct 06, 2022 |
| Protectli     | FW4B                        | Desktop     | [89a0375ecb](https://bsd-hardware.info/?probe=89a0375ecb) | Oct 06, 2022 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [b164bfcf33](https://bsd-hardware.info/?probe=b164bfcf33) | Oct 06, 2022 |
| Protectli     | VP4650                      | Desktop     | [c9f3c90f23](https://bsd-hardware.info/?probe=c9f3c90f23) | Oct 06, 2022 |
| YANYU         | ITX-M9F VER:1.1             | Desktop     | [dcb1d22084](https://bsd-hardware.info/?probe=dcb1d22084) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [ce9cfa77aa](https://bsd-hardware.info/?probe=ce9cfa77aa) | Oct 05, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [9c092c9cd7](https://bsd-hardware.info/?probe=9c092c9cd7) | Oct 05, 2022 |
| Dell          | 081N4V A04                  | Server      | [a2d73ebe76](https://bsd-hardware.info/?probe=a2d73ebe76) | Oct 05, 2022 |
| HP            | 8299                        | Desktop     | [e0f84d2500](https://bsd-hardware.info/?probe=e0f84d2500) | Oct 05, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7eba59d7ca](https://bsd-hardware.info/?probe=7eba59d7ca) | Oct 05, 2022 |
| CncTion       | J4125-4L-I225               | Desktop     | [eb746dc4a1](https://bsd-hardware.info/?probe=eb746dc4a1) | Oct 05, 2022 |
| HP            | Compaq 6735s                | Notebook    | [f61208cfea](https://bsd-hardware.info/?probe=f61208cfea) | Oct 05, 2022 |
| Cisco         | ASA5515 A0                  | Desktop     | [bdda6913d3](https://bsd-hardware.info/?probe=bdda6913d3) | Oct 05, 2022 |
| Sophos        | SG                          | Firewall    | [44ca915943](https://bsd-hardware.info/?probe=44ca915943) | Oct 05, 2022 |
| HP            | Compaq 6735s                | Notebook    | [718126149c](https://bsd-hardware.info/?probe=718126149c) | Oct 05, 2022 |
| Sophos        | XG                          | Firewall    | [cf528e776d](https://bsd-hardware.info/?probe=cf528e776d) | Oct 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [7718c8e9ca](https://bsd-hardware.info/?probe=7718c8e9ca) | Oct 05, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [63b36c077a](https://bsd-hardware.info/?probe=63b36c077a) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | Notebook    | [86289a60aa](https://bsd-hardware.info/?probe=86289a60aa) | Oct 05, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [ec799eed0c](https://bsd-hardware.info/?probe=ec799eed0c) | Oct 05, 2022 |
| Sophos        | XG                          | Firewall    | [7db10dce96](https://bsd-hardware.info/?probe=7db10dce96) | Oct 05, 2022 |
| PC Engines    | APU2                        | Desktop     | [47e38f3abe](https://bsd-hardware.info/?probe=47e38f3abe) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | Notebook    | [9f4642f6a5](https://bsd-hardware.info/?probe=9f4642f6a5) | Oct 05, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [2ef96dc13f](https://bsd-hardware.info/?probe=2ef96dc13f) | Oct 04, 2022 |
| Dell          | 0WMJ54 A00                  | Desktop     | [541e5011d9](https://bsd-hardware.info/?probe=541e5011d9) | Oct 04, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| Dell          | Precision 5510              | Notebook    | [f69c9fb0ea](https://bsd-hardware.info/?probe=f69c9fb0ea) | Oct 04, 2022 |
| Lenovo        | ThinkPad T60 2613CTO        | Desktop     | [cb649b809c](https://bsd-hardware.info/?probe=cb649b809c) | Oct 04, 2022 |
| ASRock        | Z370M-ITX/ac                | Desktop     | [e73c308b5f](https://bsd-hardware.info/?probe=e73c308b5f) | Oct 04, 2022 |
| HP            | 18E7                        | Desktop     | [ad345682d8](https://bsd-hardware.info/?probe=ad345682d8) | Oct 04, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [724c70cfa3](https://bsd-hardware.info/?probe=724c70cfa3) | Oct 04, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [459c674b3b](https://bsd-hardware.info/?probe=459c674b3b) | Oct 04, 2022 |
| MSI           | MS-B1831                    | Desktop     | [7cf04bb1f4](https://bsd-hardware.info/?probe=7cf04bb1f4) | Oct 04, 2022 |
| Dell          | Latitude E6420              | Notebook    | [07b078fdef](https://bsd-hardware.info/?probe=07b078fdef) | Oct 04, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [627206d154](https://bsd-hardware.info/?probe=627206d154) | Oct 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [c3608a94b1](https://bsd-hardware.info/?probe=c3608a94b1) | Oct 04, 2022 |
| ASRock        | J3355M                      | Desktop     | [0240dbc2bb](https://bsd-hardware.info/?probe=0240dbc2bb) | Oct 04, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [1fd10e86d9](https://bsd-hardware.info/?probe=1fd10e86d9) | Oct 04, 2022 |
| Neousys Te... | NVS-5000 Rev. A3            | Server      | [49d9f0e06a](https://bsd-hardware.info/?probe=49d9f0e06a) | Oct 04, 2022 |
| Sophos        | XG                          | Firewall    | [6408d528c9](https://bsd-hardware.info/?probe=6408d528c9) | Oct 03, 2022 |
| Sophos        | XG                          | Firewall    | [4b62b03461](https://bsd-hardware.info/?probe=4b62b03461) | Oct 03, 2022 |
| Protectli     | FW4B                        | Desktop     | [36c62d7ffe](https://bsd-hardware.info/?probe=36c62d7ffe) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Desktop     | [e001150f93](https://bsd-hardware.info/?probe=e001150f93) | Oct 03, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [d89559e5c2](https://bsd-hardware.info/?probe=d89559e5c2) | Oct 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [58def8d407](https://bsd-hardware.info/?probe=58def8d407) | Oct 03, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [8123ab15ec](https://bsd-hardware.info/?probe=8123ab15ec) | Oct 03, 2022 |
| Toshiba       | NB300                       | Notebook    | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [dac9b93a46](https://bsd-hardware.info/?probe=dac9b93a46) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e83d522905](https://bsd-hardware.info/?probe=e83d522905) | Oct 03, 2022 |
| Dell          | Precision M4500             | Notebook    | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [bb4a59dd43](https://bsd-hardware.info/?probe=bb4a59dd43) | Oct 03, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [d30234a34e](https://bsd-hardware.info/?probe=d30234a34e) | Oct 03, 2022 |
| IBM           | 9210MML                     | Desktop     | [a6e7d7483f](https://bsd-hardware.info/?probe=a6e7d7483f) | Oct 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [02a9700c12](https://bsd-hardware.info/?probe=02a9700c12) | Oct 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [79060c241b](https://bsd-hardware.info/?probe=79060c241b) | Oct 03, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [3590d4504c](https://bsd-hardware.info/?probe=3590d4504c) | Oct 02, 2022 |
| Dell          | 04YP6J A02                  | Desktop     | [dacf88ac40](https://bsd-hardware.info/?probe=dacf88ac40) | Oct 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e021d720f](https://bsd-hardware.info/?probe=4e021d720f) | Oct 02, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [a49ac2701d](https://bsd-hardware.info/?probe=a49ac2701d) | Oct 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [f2647037ec](https://bsd-hardware.info/?probe=f2647037ec) | Oct 02, 2022 |
| HPE           | ProLiant ML30 Gen10         | Desktop     | [f1b45790d4](https://bsd-hardware.info/?probe=f1b45790d4) | Oct 02, 2022 |
| Biostar       | B450NH                      | Desktop     | [27f932ee37](https://bsd-hardware.info/?probe=27f932ee37) | Oct 02, 2022 |
| HP            | ProBook 4540s               | Notebook    | [df94757940](https://bsd-hardware.info/?probe=df94757940) | Oct 02, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6f40caa9f8](https://bsd-hardware.info/?probe=6f40caa9f8) | Oct 02, 2022 |
| Supermicro    | X11SSL-F                    | Server      | [d3c50c8d60](https://bsd-hardware.info/?probe=d3c50c8d60) | Oct 02, 2022 |
| Dell          | Precision M4800             | Notebook    | [0fcbdeeeb7](https://bsd-hardware.info/?probe=0fcbdeeeb7) | Oct 02, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [5671721752](https://bsd-hardware.info/?probe=5671721752) | Oct 02, 2022 |
| HP            | 8767 A                      | Desktop     | [9d98b3baa4](https://bsd-hardware.info/?probe=9d98b3baa4) | Oct 02, 2022 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [734ff7f48c](https://bsd-hardware.info/?probe=734ff7f48c) | Oct 02, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [122f6f6837](https://bsd-hardware.info/?probe=122f6f6837) | Oct 02, 2022 |
| HP            | 212B                        | Desktop     | [7bc6506336](https://bsd-hardware.info/?probe=7bc6506336) | Oct 01, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| AAEON         | FWS-2350 V1.0               | Desktop     | [00cc54cbad](https://bsd-hardware.info/?probe=00cc54cbad) | Oct 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [01566cd078](https://bsd-hardware.info/?probe=01566cd078) | Oct 01, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [23450789e4](https://bsd-hardware.info/?probe=23450789e4) | Oct 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [bdabafdcb1](https://bsd-hardware.info/?probe=bdabafdcb1) | Oct 01, 2022 |
| AMI           | PICO PC                     | Desktop     | [ab45092607](https://bsd-hardware.info/?probe=ab45092607) | Oct 01, 2022 |
| Shuttle       | FH61V                       | Desktop     | [305f06cd6a](https://bsd-hardware.info/?probe=305f06cd6a) | Oct 01, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [6f087682a4](https://bsd-hardware.info/?probe=6f087682a4) | Oct 01, 2022 |
| MSI           | GL65 Leopard 10SFSK         | Notebook    | [489567748e](https://bsd-hardware.info/?probe=489567748e) | Oct 01, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9c419c5d32](https://bsd-hardware.info/?probe=9c419c5d32) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 2ORES4XJ00     | Notebook    | [323a95e6a9](https://bsd-hardware.info/?probe=323a95e6a9) | Oct 01, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [9b95ddf7b9](https://bsd-hardware.info/?probe=9b95ddf7b9) | Oct 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [c4e771c07c](https://bsd-hardware.info/?probe=c4e771c07c) | Oct 01, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [53dfc5844c](https://bsd-hardware.info/?probe=53dfc5844c) | Oct 01, 2022 |
| BESSTAR Te... | IB9                         | Desktop     | [0cb7bacc88](https://bsd-hardware.info/?probe=0cb7bacc88) | Oct 01, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [05651f8664](https://bsd-hardware.info/?probe=05651f8664) | Oct 01, 2022 |
| Dell          | 0PC5F7 A00                  | Desktop     | [376550557f](https://bsd-hardware.info/?probe=376550557f) | Sep 30, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [5b31d03140](https://bsd-hardware.info/?probe=5b31d03140) | Sep 30, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [6853ba1191](https://bsd-hardware.info/?probe=6853ba1191) | Sep 30, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [6f95477df3](https://bsd-hardware.info/?probe=6f95477df3) | Sep 30, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [8e658fe40f](https://bsd-hardware.info/?probe=8e658fe40f) | Sep 30, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [c1c59c9d14](https://bsd-hardware.info/?probe=c1c59c9d14) | Sep 30, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [c2ff0bc0b9](https://bsd-hardware.info/?probe=c2ff0bc0b9) | Sep 30, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [30cb759583](https://bsd-hardware.info/?probe=30cb759583) | Sep 30, 2022 |
| Intel         | S1200RP_SE G62252-406       | Server      | [4763fe7595](https://bsd-hardware.info/?probe=4763fe7595) | Sep 30, 2022 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [5fd9a63834](https://bsd-hardware.info/?probe=5fd9a63834) | Sep 30, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [8ad31cc470](https://bsd-hardware.info/?probe=8ad31cc470) | Sep 29, 2022 |
| Kraftway      | KW10T                       | Notebook    | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| Intel         | CARLOW                      | Desktop     | [25b6d62332](https://bsd-hardware.info/?probe=25b6d62332) | Sep 29, 2022 |
| BESSTAR Te... | IB9                         | Desktop     | [eb0e449150](https://bsd-hardware.info/?probe=eb0e449150) | Sep 29, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [353008eb5e](https://bsd-hardware.info/?probe=353008eb5e) | Sep 29, 2022 |
| Biostar       | N68S3B                      | Desktop     | [24c8fcee9a](https://bsd-hardware.info/?probe=24c8fcee9a) | Sep 29, 2022 |
| Dell          | 0MFXTY A02                  | Server      | [6484798368](https://bsd-hardware.info/?probe=6484798368) | Sep 29, 2022 |
| HP            | 17E2                        | Mini pc     | [15ec4829ce](https://bsd-hardware.info/?probe=15ec4829ce) | Sep 29, 2022 |
| Lenovo        | ThinkPad W530 2436CTO       | Notebook    | [6515a18552](https://bsd-hardware.info/?probe=6515a18552) | Sep 29, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [62b9a56103](https://bsd-hardware.info/?probe=62b9a56103) | Sep 29, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [6418fd0b23](https://bsd-hardware.info/?probe=6418fd0b23) | Sep 28, 2022 |
| Intel         | H81U                        | Notebook    | [fa8c32528a](https://bsd-hardware.info/?probe=fa8c32528a) | Sep 28, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [a3e25236fc](https://bsd-hardware.info/?probe=a3e25236fc) | Sep 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [2926e2dc6f](https://bsd-hardware.info/?probe=2926e2dc6f) | Sep 28, 2022 |
| Biostar       | B450NH                      | Desktop     | [4beab225f6](https://bsd-hardware.info/?probe=4beab225f6) | Sep 28, 2022 |
| Tactus        | GeoFlex 110                 | Notebook    | [0b93b5f915](https://bsd-hardware.info/?probe=0b93b5f915) | Sep 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c3f8e853ef](https://bsd-hardware.info/?probe=c3f8e853ef) | Sep 28, 2022 |
| AMI           | MNHO-048                    | Desktop     | [2ec6e55a75](https://bsd-hardware.info/?probe=2ec6e55a75) | Sep 28, 2022 |
| Sophos        | SG                          | Firewall    | [6511e9620b](https://bsd-hardware.info/?probe=6511e9620b) | Sep 28, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7763... | Notebook    | [1f37ebf2bb](https://bsd-hardware.info/?probe=1f37ebf2bb) | Sep 28, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [441eb24fd2](https://bsd-hardware.info/?probe=441eb24fd2) | Sep 28, 2022 |
| Dell          | 0MFXTY A02                  | Server      | [901ca48f69](https://bsd-hardware.info/?probe=901ca48f69) | Sep 28, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3234a0b453](https://bsd-hardware.info/?probe=3234a0b453) | Sep 28, 2022 |
| Acer          | Swift SF313-52              | Notebook    | [83516dabac](https://bsd-hardware.info/?probe=83516dabac) | Sep 28, 2022 |
| Sophos        | UTM                         | Firewall    | [9856bb0d34](https://bsd-hardware.info/?probe=9856bb0d34) | Sep 28, 2022 |
| Dell          | 081N4V A04                  | Server      | [34f2cbafda](https://bsd-hardware.info/?probe=34f2cbafda) | Sep 28, 2022 |
| ASRock        | Z97 Professional            | Desktop     | [8936497eed](https://bsd-hardware.info/?probe=8936497eed) | Sep 27, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [390f4301dd](https://bsd-hardware.info/?probe=390f4301dd) | Sep 27, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [7e75a1888b](https://bsd-hardware.info/?probe=7e75a1888b) | Sep 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [16f6784862](https://bsd-hardware.info/?probe=16f6784862) | Sep 27, 2022 |
| Intel         | D34010WYK H14771-305        | Desktop     | [93e4627cc9](https://bsd-hardware.info/?probe=93e4627cc9) | Sep 27, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [a605b4582c](https://bsd-hardware.info/?probe=a605b4582c) | Sep 27, 2022 |
| ASRockRack    | X470D4U                     | Desktop     | [27a82e5fc8](https://bsd-hardware.info/?probe=27a82e5fc8) | Sep 27, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [3877787983](https://bsd-hardware.info/?probe=3877787983) | Sep 27, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [433857f5f7](https://bsd-hardware.info/?probe=433857f5f7) | Sep 27, 2022 |
| Protectli     | FW4B                        | Desktop     | [431bcb4425](https://bsd-hardware.info/?probe=431bcb4425) | Sep 27, 2022 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [5e823b71da](https://bsd-hardware.info/?probe=5e823b71da) | Sep 27, 2022 |
| Supermicro    | X11SBA-LN4F                 | Desktop     | [4c7f997199](https://bsd-hardware.info/?probe=4c7f997199) | Sep 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [69a8b9b8d9](https://bsd-hardware.info/?probe=69a8b9b8d9) | Sep 26, 2022 |
| Cisco         | ASA5515 A0                  | Desktop     | [7b1ba71a42](https://bsd-hardware.info/?probe=7b1ba71a42) | Sep 26, 2022 |
| Sophos        | SG                          | Firewall    | [fdd950a5e8](https://bsd-hardware.info/?probe=fdd950a5e8) | Sep 26, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [cfcfd2a636](https://bsd-hardware.info/?probe=cfcfd2a636) | Sep 26, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cde2481e46](https://bsd-hardware.info/?probe=cde2481e46) | Sep 26, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [b8db4655e5](https://bsd-hardware.info/?probe=b8db4655e5) | Sep 26, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [12493c3802](https://bsd-hardware.info/?probe=12493c3802) | Sep 26, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [68d99cffe1](https://bsd-hardware.info/?probe=68d99cffe1) | Sep 26, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [2c1aad67d1](https://bsd-hardware.info/?probe=2c1aad67d1) | Sep 26, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [659b695f09](https://bsd-hardware.info/?probe=659b695f09) | Sep 26, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [33b252016c](https://bsd-hardware.info/?probe=33b252016c) | Sep 26, 2022 |
| Dell          | 0TDG4V A00                  | Desktop     | [cc92be7e52](https://bsd-hardware.info/?probe=cc92be7e52) | Sep 25, 2022 |
| Acer          | Swift SF313-52              | Notebook    | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| PC Engines    | APU2                        | Desktop     | [3fcc5e5ae2](https://bsd-hardware.info/?probe=3fcc5e5ae2) | Sep 25, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [ae535b0b49](https://bsd-hardware.info/?probe=ae535b0b49) | Sep 25, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [c33dc6a072](https://bsd-hardware.info/?probe=c33dc6a072) | Sep 25, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [83607fc711](https://bsd-hardware.info/?probe=83607fc711) | Sep 25, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8f4900d0e6](https://bsd-hardware.info/?probe=8f4900d0e6) | Sep 25, 2022 |
| CncTion       | Jasper-4L B0                | Desktop     | [2998faa879](https://bsd-hardware.info/?probe=2998faa879) | Sep 25, 2022 |
| Pegatron      | H81-X1                      | Desktop     | [a27c76c490](https://bsd-hardware.info/?probe=a27c76c490) | Sep 25, 2022 |
| ASUSTek       | P9D-X Series                | Server      | [3494695f54](https://bsd-hardware.info/?probe=3494695f54) | Sep 25, 2022 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [fe44242c3b](https://bsd-hardware.info/?probe=fe44242c3b) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | Notebook    | [c947635b8f](https://bsd-hardware.info/?probe=c947635b8f) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | Notebook    | [533c7f35f1](https://bsd-hardware.info/?probe=533c7f35f1) | Sep 25, 2022 |
| Supermicro    | X10SRi-FB                   | Server      | [59ff2014e5](https://bsd-hardware.info/?probe=59ff2014e5) | Sep 25, 2022 |
| Intel         | S1200SP H57532-210          | Server      | [ab6e70abca](https://bsd-hardware.info/?probe=ab6e70abca) | Sep 25, 2022 |
| Supermicro    | X8DT3                       | Server      | [eda1df037b](https://bsd-hardware.info/?probe=eda1df037b) | Sep 25, 2022 |
| Supermicro    | X7DB8                       | Desktop     | [6ebc173873](https://bsd-hardware.info/?probe=6ebc173873) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [8bbf714f6d](https://bsd-hardware.info/?probe=8bbf714f6d) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [60d4585ece](https://bsd-hardware.info/?probe=60d4585ece) | Sep 25, 2022 |
| IBM           | ThinkPad T40 23737CG        | Notebook    | [dfc9b64da2](https://bsd-hardware.info/?probe=dfc9b64da2) | Sep 25, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [6e2d053e1c](https://bsd-hardware.info/?probe=6e2d053e1c) | Sep 25, 2022 |
| iEi           | SAE1 V1.04                  | Desktop     | [cc006e5c32](https://bsd-hardware.info/?probe=cc006e5c32) | Sep 25, 2022 |
| HP            | 3397                        | Desktop     | [8b019e6a96](https://bsd-hardware.info/?probe=8b019e6a96) | Sep 25, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [c81d389fd2](https://bsd-hardware.info/?probe=c81d389fd2) | Sep 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [9f998deaa4](https://bsd-hardware.info/?probe=9f998deaa4) | Sep 25, 2022 |
| Biostar       | N68S3B                      | Desktop     | [59bd37df63](https://bsd-hardware.info/?probe=59bd37df63) | Sep 25, 2022 |
| HP            | 8592                        | Desktop     | [898ce46c1f](https://bsd-hardware.info/?probe=898ce46c1f) | Sep 25, 2022 |
| Dell          | 05KX61 A04                  | Server      | [f1232f79c4](https://bsd-hardware.info/?probe=f1232f79c4) | Sep 25, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [de9d75d495](https://bsd-hardware.info/?probe=de9d75d495) | Sep 25, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [8883d36139](https://bsd-hardware.info/?probe=8883d36139) | Sep 25, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [59886931c5](https://bsd-hardware.info/?probe=59886931c5) | Sep 24, 2022 |
| System76      | Gazelle                     | Notebook    | [d087321049](https://bsd-hardware.info/?probe=d087321049) | Sep 24, 2022 |
| MSI           | A88XM-E45                   | Desktop     | [d9d06daa51](https://bsd-hardware.info/?probe=d9d06daa51) | Sep 24, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [dbda136daa](https://bsd-hardware.info/?probe=dbda136daa) | Sep 24, 2022 |
| ASUSTek       | All Series                  | Desktop     | [ab3b339cf0](https://bsd-hardware.info/?probe=ab3b339cf0) | Sep 24, 2022 |
| HP            | 18E7                        | Desktop     | [02ac7695d7](https://bsd-hardware.info/?probe=02ac7695d7) | Sep 24, 2022 |
| HP            | 339A                        | Desktop     | [fb436c3cc3](https://bsd-hardware.info/?probe=fb436c3cc3) | Sep 24, 2022 |
| Dell          | System Vostro 3750          | Notebook    | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8ed018c141](https://bsd-hardware.info/?probe=8ed018c141) | Sep 24, 2022 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [eccb37382c](https://bsd-hardware.info/?probe=eccb37382c) | Sep 24, 2022 |
| YANYU         | H67SL                       | Desktop     | [5f5819ef11](https://bsd-hardware.info/?probe=5f5819ef11) | Sep 24, 2022 |
| Dell          | 045M96 A00                  | Server      | [c5af7bf9e5](https://bsd-hardware.info/?probe=c5af7bf9e5) | Sep 24, 2022 |
| Lenovo        | G475 20080                  | Notebook    | [fb07463a9a](https://bsd-hardware.info/?probe=fb07463a9a) | Sep 24, 2022 |
| Lenovo        | G475 20080                  | Notebook    | [c4b1acb6d1](https://bsd-hardware.info/?probe=c4b1acb6d1) | Sep 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [8f42ff0969](https://bsd-hardware.info/?probe=8f42ff0969) | Sep 24, 2022 |
| System76      | Gazelle                     | Notebook    | [6d5d4f5021](https://bsd-hardware.info/?probe=6d5d4f5021) | Sep 24, 2022 |
| Lenovo        | ThinkPad T460p 20FW003PM... | Notebook    | [ac8e728222](https://bsd-hardware.info/?probe=ac8e728222) | Sep 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [95b1404339](https://bsd-hardware.info/?probe=95b1404339) | Sep 23, 2022 |
| Deciso        | Netboard A20                | Notebook    | [388e27791d](https://bsd-hardware.info/?probe=388e27791d) | Sep 23, 2022 |
| TYAN Compu... | S5530WG2NR-LE-AKA           | Desktop     | [18c4588a0e](https://bsd-hardware.info/?probe=18c4588a0e) | Sep 23, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a0672c6af1](https://bsd-hardware.info/?probe=a0672c6af1) | Sep 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [ffa40a08e8](https://bsd-hardware.info/?probe=ffa40a08e8) | Sep 23, 2022 |
| NITRINOnet    | M360RUS56                   | Desktop     | [490b9593e0](https://bsd-hardware.info/?probe=490b9593e0) | Sep 23, 2022 |
| Intel         | S3210SH FRU Ver             | Server      | [e6d299ffc1](https://bsd-hardware.info/?probe=e6d299ffc1) | Sep 23, 2022 |
| Sophos        | UTM                         | Firewall    | [fe6cf3c1ab](https://bsd-hardware.info/?probe=fe6cf3c1ab) | Sep 22, 2022 |
| ZOTAC         | ZBOX-MI522NANO/MI542NANO    | Mini pc     | [495b0dfebd](https://bsd-hardware.info/?probe=495b0dfebd) | Sep 22, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5029142d61](https://bsd-hardware.info/?probe=5029142d61) | Sep 22, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [13f6367ce8](https://bsd-hardware.info/?probe=13f6367ce8) | Sep 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [b7bfcbef72](https://bsd-hardware.info/?probe=b7bfcbef72) | Sep 22, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1a89d78fa4](https://bsd-hardware.info/?probe=1a89d78fa4) | Sep 22, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [036004bbfe](https://bsd-hardware.info/?probe=036004bbfe) | Sep 22, 2022 |
| Toshiba       | Satellite BE96-F299         | Notebook    | [15b93c9f4b](https://bsd-hardware.info/?probe=15b93c9f4b) | Sep 21, 2022 |
| Toshiba       | Satellite BE96-F299         | Notebook    | [9beae1547d](https://bsd-hardware.info/?probe=9beae1547d) | Sep 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [58b6d3d116](https://bsd-hardware.info/?probe=58b6d3d116) | Sep 21, 2022 |
| PC Engines    | APU                         | Desktop     | [a65b17ba04](https://bsd-hardware.info/?probe=a65b17ba04) | Sep 21, 2022 |
| Sophos        | SG                          | Firewall    | [d485561c3b](https://bsd-hardware.info/?probe=d485561c3b) | Sep 21, 2022 |
| Unknown       | Unknown                     | Notebook    | [fbd1af0e98](https://bsd-hardware.info/?probe=fbd1af0e98) | Sep 21, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [5cec3595a3](https://bsd-hardware.info/?probe=5cec3595a3) | Sep 21, 2022 |
| HP            | ProLiant DL160 G5           | Server      | [1a754b2a9e](https://bsd-hardware.info/?probe=1a754b2a9e) | Sep 21, 2022 |
| HP            | 21D0                        | Desktop     | [43fa46655e](https://bsd-hardware.info/?probe=43fa46655e) | Sep 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [199ad16750](https://bsd-hardware.info/?probe=199ad16750) | Sep 21, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [6c169bdb6a](https://bsd-hardware.info/?probe=6c169bdb6a) | Sep 20, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [37acdfe51c](https://bsd-hardware.info/?probe=37acdfe51c) | Sep 20, 2022 |
| MSI           | MS-B1831                    | Desktop     | [42f48d632c](https://bsd-hardware.info/?probe=42f48d632c) | Sep 20, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [37cafd59eb](https://bsd-hardware.info/?probe=37cafd59eb) | Sep 20, 2022 |
| Dell          | 02YRK5 A03                  | Desktop     | [2ec32e432d](https://bsd-hardware.info/?probe=2ec32e432d) | Sep 20, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [ca3b8f6b48](https://bsd-hardware.info/?probe=ca3b8f6b48) | Sep 20, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [3c74fc1690](https://bsd-hardware.info/?probe=3c74fc1690) | Sep 20, 2022 |
| Acer          | Aspire E5-771               | Notebook    | [0a58077c49](https://bsd-hardware.info/?probe=0a58077c49) | Sep 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [8e55c8e637](https://bsd-hardware.info/?probe=8e55c8e637) | Sep 20, 2022 |
| HP            | 1495                        | Desktop     | [163ac0a58b](https://bsd-hardware.info/?probe=163ac0a58b) | Sep 20, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [c057b7ab09](https://bsd-hardware.info/?probe=c057b7ab09) | Sep 20, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [a1a2cbc6c9](https://bsd-hardware.info/?probe=a1a2cbc6c9) | Sep 20, 2022 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [16479f1a2c](https://bsd-hardware.info/?probe=16479f1a2c) | Sep 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [1ceba97eb9](https://bsd-hardware.info/?probe=1ceba97eb9) | Sep 20, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [afbedcb189](https://bsd-hardware.info/?probe=afbedcb189) | Sep 20, 2022 |
| Supermicro    | X9DRD-iF                    | Server      | [f5e927f8ba](https://bsd-hardware.info/?probe=f5e927f8ba) | Sep 20, 2022 |
| HP            | 21D0                        | Desktop     | [463e2563d7](https://bsd-hardware.info/?probe=463e2563d7) | Sep 19, 2022 |
| Supermicro    | X9SCI/X9SCA                 | Desktop     | [1270203d0b](https://bsd-hardware.info/?probe=1270203d0b) | Sep 19, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [80e1559386](https://bsd-hardware.info/?probe=80e1559386) | Sep 19, 2022 |
| Toshiba       | PORTEGE R700                | Notebook    | [10b85eccae](https://bsd-hardware.info/?probe=10b85eccae) | Sep 19, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [b394504429](https://bsd-hardware.info/?probe=b394504429) | Sep 19, 2022 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [9d291758ef](https://bsd-hardware.info/?probe=9d291758ef) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [322c8947b6](https://bsd-hardware.info/?probe=322c8947b6) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [0307c109b5](https://bsd-hardware.info/?probe=0307c109b5) | Sep 19, 2022 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | Notebook    | [1b75ee6295](https://bsd-hardware.info/?probe=1b75ee6295) | Sep 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [8956b895ab](https://bsd-hardware.info/?probe=8956b895ab) | Sep 19, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [393da0c00c](https://bsd-hardware.info/?probe=393da0c00c) | Sep 19, 2022 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [1a9c6a10bd](https://bsd-hardware.info/?probe=1a9c6a10bd) | Sep 19, 2022 |
| HP            | 0B54h D                     | Desktop     | [a24f08281d](https://bsd-hardware.info/?probe=a24f08281d) | Sep 19, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [d1c81ef222](https://bsd-hardware.info/?probe=d1c81ef222) | Sep 19, 2022 |
| Gigabyte      | H61M-DS2V                   | Desktop     | [55f8e635b8](https://bsd-hardware.info/?probe=55f8e635b8) | Sep 19, 2022 |
| Dell          | 01TJ2K A02                  | Desktop     | [b34cf533f3](https://bsd-hardware.info/?probe=b34cf533f3) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a2f56848a9](https://bsd-hardware.info/?probe=a2f56848a9) | Sep 19, 2022 |
| Sophos        | UTM                         | Firewall    | [785bb6c2a0](https://bsd-hardware.info/?probe=785bb6c2a0) | Sep 19, 2022 |
| Lenovo        | ThinkStation D10 6493WEU    | Desktop     | [526e5eea0b](https://bsd-hardware.info/?probe=526e5eea0b) | Sep 18, 2022 |
| Supermicro    | A2SDi-TP8F                  | Desktop     | [db2194c9b9](https://bsd-hardware.info/?probe=db2194c9b9) | Sep 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [cad2b5fd02](https://bsd-hardware.info/?probe=cad2b5fd02) | Sep 18, 2022 |
| Sophos        | XG                          | Firewall    | [e8aca06194](https://bsd-hardware.info/?probe=e8aca06194) | Sep 18, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [fe9eecb935](https://bsd-hardware.info/?probe=fe9eecb935) | Sep 18, 2022 |
| Intel         | D34010WYK H14771-305        | Desktop     | [e734b98922](https://bsd-hardware.info/?probe=e734b98922) | Sep 18, 2022 |
| Dell          | Precision 7710              | Notebook    | [4c4937d824](https://bsd-hardware.info/?probe=4c4937d824) | Sep 18, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [f3058f97f9](https://bsd-hardware.info/?probe=f3058f97f9) | Sep 18, 2022 |
| MSI           | MS-B1831                    | Desktop     | [94a3d6891a](https://bsd-hardware.info/?probe=94a3d6891a) | Sep 18, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [d2945c003e](https://bsd-hardware.info/?probe=d2945c003e) | Sep 18, 2022 |
| HP            | 213D A01                    | Desktop     | [6e8a38b6ca](https://bsd-hardware.info/?probe=6e8a38b6ca) | Sep 18, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | Notebook    | [2f1f82558e](https://bsd-hardware.info/?probe=2f1f82558e) | Sep 18, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [d027a503a5](https://bsd-hardware.info/?probe=d027a503a5) | Sep 18, 2022 |
| EAGLE EYE ... | BayTrail-D Rev.00           | Desktop     | [261f623516](https://bsd-hardware.info/?probe=261f623516) | Sep 18, 2022 |
| CONTEC        | G1/EMB-CV1/iD2550           | Desktop     | [266ef0ca6a](https://bsd-hardware.info/?probe=266ef0ca6a) | Sep 18, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [55c82d4dd0](https://bsd-hardware.info/?probe=55c82d4dd0) | Sep 18, 2022 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [91e0f723ea](https://bsd-hardware.info/?probe=91e0f723ea) | Sep 18, 2022 |
| HP            | 18E7                        | Desktop     | [e999bdd87e](https://bsd-hardware.info/?probe=e999bdd87e) | Sep 17, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [da4bd87fee](https://bsd-hardware.info/?probe=da4bd87fee) | Sep 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [050c365fcd](https://bsd-hardware.info/?probe=050c365fcd) | Sep 17, 2022 |
| Intel         | D53427RKE G87971-403        | Desktop     | [aa00c60448](https://bsd-hardware.info/?probe=aa00c60448) | Sep 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [af8f180c2c](https://bsd-hardware.info/?probe=af8f180c2c) | Sep 17, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [431ad10ab2](https://bsd-hardware.info/?probe=431ad10ab2) | Sep 17, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a9da12dec0](https://bsd-hardware.info/?probe=a9da12dec0) | Sep 17, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [22f23ccfa5](https://bsd-hardware.info/?probe=22f23ccfa5) | Sep 17, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [8de53ac515](https://bsd-hardware.info/?probe=8de53ac515) | Sep 17, 2022 |
| HP            | 8103 A01                    | Mini pc     | [533a1ebabe](https://bsd-hardware.info/?probe=533a1ebabe) | Sep 17, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [e0b8ceecae](https://bsd-hardware.info/?probe=e0b8ceecae) | Sep 16, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [9fc1f66fcc](https://bsd-hardware.info/?probe=9fc1f66fcc) | Sep 16, 2022 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | Desktop     | [eb09d789de](https://bsd-hardware.info/?probe=eb09d789de) | Sep 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [050dee62c1](https://bsd-hardware.info/?probe=050dee62c1) | Sep 16, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [7bf7249432](https://bsd-hardware.info/?probe=7bf7249432) | Sep 16, 2022 |
| Intel BOXJ... | Unknown                     | Desktop     | [c28fe204f3](https://bsd-hardware.info/?probe=c28fe204f3) | Sep 16, 2022 |
| Intel BOXJ... | Unknown                     | Desktop     | [a900f3bc8b](https://bsd-hardware.info/?probe=a900f3bc8b) | Sep 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [3b66741f97](https://bsd-hardware.info/?probe=3b66741f97) | Sep 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [83e48aa232](https://bsd-hardware.info/?probe=83e48aa232) | Sep 16, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [09b5ca588f](https://bsd-hardware.info/?probe=09b5ca588f) | Sep 16, 2022 |
| Standard      | SFFGL Series                | Mini pc     | [a537bcd507](https://bsd-hardware.info/?probe=a537bcd507) | Sep 16, 2022 |
| Lenovo        | ThinkPad L420 7829WDY       | Notebook    | [a697be2aa9](https://bsd-hardware.info/?probe=a697be2aa9) | Sep 16, 2022 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [ce024b9f84](https://bsd-hardware.info/?probe=ce024b9f84) | Sep 15, 2022 |
| Standard      | SFFGL Series                | Mini pc     | [f1b8de71f4](https://bsd-hardware.info/?probe=f1b8de71f4) | Sep 15, 2022 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [15a7e37cbf](https://bsd-hardware.info/?probe=15a7e37cbf) | Sep 15, 2022 |
| Supermicro    | A2SDi-TP8F                  | Desktop     | [8c67aa0f6e](https://bsd-hardware.info/?probe=8c67aa0f6e) | Sep 15, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [505feb51ca](https://bsd-hardware.info/?probe=505feb51ca) | Sep 15, 2022 |
| Dell          | 081N4V A04                  | Server      | [1b5150b554](https://bsd-hardware.info/?probe=1b5150b554) | Sep 15, 2022 |
| Supermicro    | X10DRL-i                    | Server      | [de856f28a4](https://bsd-hardware.info/?probe=de856f28a4) | Sep 15, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [10f0cfa344](https://bsd-hardware.info/?probe=10f0cfa344) | Sep 15, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [eee7bdda02](https://bsd-hardware.info/?probe=eee7bdda02) | Sep 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [7df7bc66e7](https://bsd-hardware.info/?probe=7df7bc66e7) | Sep 15, 2022 |
| Google        | Peppy                       | Notebook    | [80ffa77224](https://bsd-hardware.info/?probe=80ffa77224) | Sep 15, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [6d0be3dcf1](https://bsd-hardware.info/?probe=6d0be3dcf1) | Sep 15, 2022 |
| Intel         | ChiefRiver                  | Desktop     | [5361453e6a](https://bsd-hardware.info/?probe=5361453e6a) | Sep 15, 2022 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [0157925fad](https://bsd-hardware.info/?probe=0157925fad) | Sep 15, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [ad70ccea4d](https://bsd-hardware.info/?probe=ad70ccea4d) | Sep 15, 2022 |
| Supermicro    | X11SSM-F                    | Server      | [a1dc602460](https://bsd-hardware.info/?probe=a1dc602460) | Sep 15, 2022 |
| YANYU         | H67SL                       | Desktop     | [37ba00c2f3](https://bsd-hardware.info/?probe=37ba00c2f3) | Sep 15, 2022 |
| Intel         | DENLOW_WS                   | Desktop     | [7ec0e7257d](https://bsd-hardware.info/?probe=7ec0e7257d) | Sep 14, 2022 |
| AZW           | Green G1                    | Desktop     | [1ccd8f86b3](https://bsd-hardware.info/?probe=1ccd8f86b3) | Sep 14, 2022 |
| Protectli     | FW6                         | Desktop     | [23227c99a0](https://bsd-hardware.info/?probe=23227c99a0) | Sep 14, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [13ec5a6f20](https://bsd-hardware.info/?probe=13ec5a6f20) | Sep 14, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7aa564bfb2](https://bsd-hardware.info/?probe=7aa564bfb2) | Sep 14, 2022 |
| HP            | 8103 A01                    | Mini pc     | [94ba5ceedb](https://bsd-hardware.info/?probe=94ba5ceedb) | Sep 14, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [0ee299e989](https://bsd-hardware.info/?probe=0ee299e989) | Sep 14, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [cce6101086](https://bsd-hardware.info/?probe=cce6101086) | Sep 14, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [58caab8946](https://bsd-hardware.info/?probe=58caab8946) | Sep 14, 2022 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [924dc8e7e1](https://bsd-hardware.info/?probe=924dc8e7e1) | Sep 14, 2022 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [2b4cf189e9](https://bsd-hardware.info/?probe=2b4cf189e9) | Sep 14, 2022 |
| Lenovo        | ThinkPad X270 20HMS2LL00    | Notebook    | [12f6a8866f](https://bsd-hardware.info/?probe=12f6a8866f) | Sep 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d2ad4471e0](https://bsd-hardware.info/?probe=d2ad4471e0) | Sep 14, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [a444259756](https://bsd-hardware.info/?probe=a444259756) | Sep 14, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [dc557f4385](https://bsd-hardware.info/?probe=dc557f4385) | Sep 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [992ddc4118](https://bsd-hardware.info/?probe=992ddc4118) | Sep 14, 2022 |
| HP            | ProLiant DL160 G5           | Server      | [77727b5832](https://bsd-hardware.info/?probe=77727b5832) | Sep 14, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [9e6bd1263d](https://bsd-hardware.info/?probe=9e6bd1263d) | Sep 13, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [cbc4aeb7be](https://bsd-hardware.info/?probe=cbc4aeb7be) | Sep 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [e8848edf41](https://bsd-hardware.info/?probe=e8848edf41) | Sep 13, 2022 |
| Dell          | 0HJK12 A03                  | Server      | [96ad323ca0](https://bsd-hardware.info/?probe=96ad323ca0) | Sep 13, 2022 |
| Dell          | 0H5J4J A01                  | Server      | [acb91f797f](https://bsd-hardware.info/?probe=acb91f797f) | Sep 13, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94        | Desktop     | [d2e169b8ad](https://bsd-hardware.info/?probe=d2e169b8ad) | Sep 13, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e95ac333fe](https://bsd-hardware.info/?probe=e95ac333fe) | Sep 13, 2022 |
| Intel         | D945GCLF2 AAE46416-106      | Desktop     | [8e2f7792eb](https://bsd-hardware.info/?probe=8e2f7792eb) | Sep 13, 2022 |
| Sophos        | XG                          | Firewall    | [1540138670](https://bsd-hardware.info/?probe=1540138670) | Sep 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f023ae7ed2](https://bsd-hardware.info/?probe=f023ae7ed2) | Sep 13, 2022 |
| Deciso        | Netboard A20                | Notebook    | [8af40be425](https://bsd-hardware.info/?probe=8af40be425) | Sep 13, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [81722a937a](https://bsd-hardware.info/?probe=81722a937a) | Sep 13, 2022 |
| PC Engines    | APU2                        | Desktop     | [95ae240b55](https://bsd-hardware.info/?probe=95ae240b55) | Sep 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [baaf9cbda6](https://bsd-hardware.info/?probe=baaf9cbda6) | Sep 13, 2022 |
| Protectli     | FW4B                        | Desktop     | [0553a226de](https://bsd-hardware.info/?probe=0553a226de) | Sep 13, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [d3ee67f09b](https://bsd-hardware.info/?probe=d3ee67f09b) | Sep 13, 2022 |
| SIEMENS       | SIMATIC IPC127E             | Notebook    | [d16e38e6b2](https://bsd-hardware.info/?probe=d16e38e6b2) | Sep 12, 2022 |
| Dell          | 03X6X0 A09                  | Server      | [ce56845976](https://bsd-hardware.info/?probe=ce56845976) | Sep 12, 2022 |
| Dell          | 07WP95 A01                  | Desktop     | [98e67ff164](https://bsd-hardware.info/?probe=98e67ff164) | Sep 12, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [05b5d1e01a](https://bsd-hardware.info/?probe=05b5d1e01a) | Sep 12, 2022 |
| HP            | 18E7                        | Desktop     | [f09635a7ee](https://bsd-hardware.info/?probe=f09635a7ee) | Sep 12, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [66e543ee47](https://bsd-hardware.info/?probe=66e543ee47) | Sep 12, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [2b4e2212dc](https://bsd-hardware.info/?probe=2b4e2212dc) | Sep 12, 2022 |
| HP            | 213D A01                    | Desktop     | [6354ddb4a8](https://bsd-hardware.info/?probe=6354ddb4a8) | Sep 12, 2022 |
| HP            | 8648                        | Desktop     | [e7e610794c](https://bsd-hardware.info/?probe=e7e610794c) | Sep 12, 2022 |
| Protectli     | FW4B                        | Desktop     | [0ccd9a9f2c](https://bsd-hardware.info/?probe=0ccd9a9f2c) | Sep 12, 2022 |
| HP            | 8054                        | Desktop     | [3385f78f9c](https://bsd-hardware.info/?probe=3385f78f9c) | Sep 12, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [71e53af7f9](https://bsd-hardware.info/?probe=71e53af7f9) | Sep 12, 2022 |
| Dell EMC      | VEP1425-V210-CPU A00        | Desktop     | [871a29677b](https://bsd-hardware.info/?probe=871a29677b) | Sep 12, 2022 |
| MSI           | H81M-E33                    | Desktop     | [b80a45410b](https://bsd-hardware.info/?probe=b80a45410b) | Sep 12, 2022 |
| HP            | 213D A01                    | Desktop     | [54288c6759](https://bsd-hardware.info/?probe=54288c6759) | Sep 11, 2022 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [db5bbdec3c](https://bsd-hardware.info/?probe=db5bbdec3c) | Sep 11, 2022 |
| HP            | ProLiant DL20 Gen9          | Server      | [32e9f95095](https://bsd-hardware.info/?probe=32e9f95095) | Sep 11, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [21e7190ff2](https://bsd-hardware.info/?probe=21e7190ff2) | Sep 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [37588a8565](https://bsd-hardware.info/?probe=37588a8565) | Sep 11, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [5abbba28de](https://bsd-hardware.info/?probe=5abbba28de) | Sep 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [700e6ba6a9](https://bsd-hardware.info/?probe=700e6ba6a9) | Sep 11, 2022 |
| MSI           | H81M-E33                    | Desktop     | [66d179c5f4](https://bsd-hardware.info/?probe=66d179c5f4) | Sep 11, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [1cbbe33027](https://bsd-hardware.info/?probe=1cbbe33027) | Sep 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [3b668ace72](https://bsd-hardware.info/?probe=3b668ace72) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [62c287a993](https://bsd-hardware.info/?probe=62c287a993) | Sep 11, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [3c152ae7bd](https://bsd-hardware.info/?probe=3c152ae7bd) | Sep 11, 2022 |
| Dell          | XPS M1330                   | Notebook    | [d84548dd9b](https://bsd-hardware.info/?probe=d84548dd9b) | Sep 11, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [ce6906d604](https://bsd-hardware.info/?probe=ce6906d604) | Sep 10, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [79503c0635](https://bsd-hardware.info/?probe=79503c0635) | Sep 10, 2022 |
| MSI           | A88XM-E45                   | Desktop     | [2df6d013e9](https://bsd-hardware.info/?probe=2df6d013e9) | Sep 10, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b2dc861f47](https://bsd-hardware.info/?probe=b2dc861f47) | Sep 10, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [7c9c1db9d7](https://bsd-hardware.info/?probe=7c9c1db9d7) | Sep 10, 2022 |
| AOpen         | iBTMx-DS R1.03 55DED10A0... | Desktop     | [50ac5c0aaf](https://bsd-hardware.info/?probe=50ac5c0aaf) | Sep 10, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9c7a64970c](https://bsd-hardware.info/?probe=9c7a64970c) | Sep 10, 2022 |
| HP            | 8103 A01                    | Mini pc     | [34f00f7f28](https://bsd-hardware.info/?probe=34f00f7f28) | Sep 10, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [89b185547b](https://bsd-hardware.info/?probe=89b185547b) | Sep 10, 2022 |
| Maxtang       | BYT30                       | Desktop     | [90053990c3](https://bsd-hardware.info/?probe=90053990c3) | Sep 10, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [836927cf63](https://bsd-hardware.info/?probe=836927cf63) | Sep 10, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b54e6663f9](https://bsd-hardware.info/?probe=b54e6663f9) | Sep 10, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [7e8d44c688](https://bsd-hardware.info/?probe=7e8d44c688) | Sep 10, 2022 |
| HP            | ProLiant DL160 G5           | Server      | [130de630ad](https://bsd-hardware.info/?probe=130de630ad) | Sep 10, 2022 |
| CONTEC        | G1/EMB-CV1/iD2550           | Desktop     | [0df35f9c64](https://bsd-hardware.info/?probe=0df35f9c64) | Sep 10, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [8eb8bf52d4](https://bsd-hardware.info/?probe=8eb8bf52d4) | Sep 10, 2022 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [6b449e63d3](https://bsd-hardware.info/?probe=6b449e63d3) | Sep 10, 2022 |
| Sophos        | SG                          | Firewall    | [0213c8bb69](https://bsd-hardware.info/?probe=0213c8bb69) | Sep 09, 2022 |
| ASRock        | H81M-DGS                    | Desktop     | [3c2b784001](https://bsd-hardware.info/?probe=3c2b784001) | Sep 09, 2022 |
| ASRock        | H81M-DGS                    | Desktop     | [581219cbc5](https://bsd-hardware.info/?probe=581219cbc5) | Sep 09, 2022 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [c25d3df4e2](https://bsd-hardware.info/?probe=c25d3df4e2) | Sep 09, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [b1a126ce25](https://bsd-hardware.info/?probe=b1a126ce25) | Sep 09, 2022 |
| Intel         | SandyBridge Platform        | Notebook    | [7c10326786](https://bsd-hardware.info/?probe=7c10326786) | Sep 09, 2022 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [f91afdb2f3](https://bsd-hardware.info/?probe=f91afdb2f3) | Sep 09, 2022 |
| AZW           | Green G1                    | Desktop     | [b9e82f5157](https://bsd-hardware.info/?probe=b9e82f5157) | Sep 09, 2022 |
| EAGLE EYE ... | BayTrail-D Rev.00           | Desktop     | [1e62e2ea85](https://bsd-hardware.info/?probe=1e62e2ea85) | Sep 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [1cd83a6904](https://bsd-hardware.info/?probe=1cd83a6904) | Sep 09, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [98dff45d54](https://bsd-hardware.info/?probe=98dff45d54) | Sep 09, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [8776541164](https://bsd-hardware.info/?probe=8776541164) | Sep 09, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [fb678970df](https://bsd-hardware.info/?probe=fb678970df) | Sep 09, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [860aea3ce4](https://bsd-hardware.info/?probe=860aea3ce4) | Sep 08, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [4e393e3814](https://bsd-hardware.info/?probe=4e393e3814) | Sep 08, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [e082eca671](https://bsd-hardware.info/?probe=e082eca671) | Sep 08, 2022 |
| EPSON DIRE... | ST170E                      | Desktop     | [1ac571538d](https://bsd-hardware.info/?probe=1ac571538d) | Sep 08, 2022 |
| Unknown       | YL-J3060L2                  | Desktop     | [2210876ea3](https://bsd-hardware.info/?probe=2210876ea3) | Sep 08, 2022 |
| Dell          | Precision 7540              | Notebook    | [f39c0f4d92](https://bsd-hardware.info/?probe=f39c0f4d92) | Sep 08, 2022 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [b0965df7e1](https://bsd-hardware.info/?probe=b0965df7e1) | Sep 08, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [6130d9c1d0](https://bsd-hardware.info/?probe=6130d9c1d0) | Sep 07, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [4db37ff154](https://bsd-hardware.info/?probe=4db37ff154) | Sep 07, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [1d81b77310](https://bsd-hardware.info/?probe=1d81b77310) | Sep 07, 2022 |
| Dell          | 0W0W22 A08                  | Server      | [4d371914ed](https://bsd-hardware.info/?probe=4d371914ed) | Sep 07, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [6c88b88822](https://bsd-hardware.info/?probe=6c88b88822) | Sep 07, 2022 |
| Intel         | SYS-2USM03-6M01E            | Desktop     | [d4f98f18b9](https://bsd-hardware.info/?probe=d4f98f18b9) | Sep 07, 2022 |
| Dell          | Latitude 5310               | Notebook    | [6edf4d34fe](https://bsd-hardware.info/?probe=6edf4d34fe) | Sep 07, 2022 |
| Dell          | Latitude E5470              | Notebook    | [9e798cbfc8](https://bsd-hardware.info/?probe=9e798cbfc8) | Sep 07, 2022 |
| Protectli     | FW4B                        | Desktop     | [b934171c54](https://bsd-hardware.info/?probe=b934171c54) | Sep 07, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [3c3c40a10f](https://bsd-hardware.info/?probe=3c3c40a10f) | Sep 07, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [f431032a32](https://bsd-hardware.info/?probe=f431032a32) | Sep 07, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7c6751649b](https://bsd-hardware.info/?probe=7c6751649b) | Sep 07, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [b803a767af](https://bsd-hardware.info/?probe=b803a767af) | Sep 06, 2022 |
| Lenovo        | ThinkPad T440 20B7S2LT00    | Notebook    | [5104875f94](https://bsd-hardware.info/?probe=5104875f94) | Sep 06, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [2d3a5a5260](https://bsd-hardware.info/?probe=2d3a5a5260) | Sep 06, 2022 |
| Dell          | Vostro 5415                 | Notebook    | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| Intel         | J1900                       | Desktop     | [a95dd12c65](https://bsd-hardware.info/?probe=a95dd12c65) | Sep 06, 2022 |
| Sophos        | SG                          | Firewall    | [4b393a08cd](https://bsd-hardware.info/?probe=4b393a08cd) | Sep 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [4f31f81571](https://bsd-hardware.info/?probe=4f31f81571) | Sep 06, 2022 |
| HP            | 1495                        | Desktop     | [4ba1b5820e](https://bsd-hardware.info/?probe=4ba1b5820e) | Sep 06, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [cd90f548c8](https://bsd-hardware.info/?probe=cd90f548c8) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [00ee0319aa](https://bsd-hardware.info/?probe=00ee0319aa) | Sep 06, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [a854e50942](https://bsd-hardware.info/?probe=a854e50942) | Sep 06, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [4bcc55d57f](https://bsd-hardware.info/?probe=4bcc55d57f) | Sep 06, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [817b37c259](https://bsd-hardware.info/?probe=817b37c259) | Sep 06, 2022 |
| Intel         | S5520UR E22554-753          | Server      | [9048eea837](https://bsd-hardware.info/?probe=9048eea837) | Sep 06, 2022 |
| Dell          | Precision 7550              | Notebook    | [d2bf200529](https://bsd-hardware.info/?probe=d2bf200529) | Sep 06, 2022 |
| HP            | 1496                        | Desktop     | [7cd97bd330](https://bsd-hardware.info/?probe=7cd97bd330) | Sep 05, 2022 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [975b49af4a](https://bsd-hardware.info/?probe=975b49af4a) | Sep 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [865dca4859](https://bsd-hardware.info/?probe=865dca4859) | Sep 05, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [3f5ad2f043](https://bsd-hardware.info/?probe=3f5ad2f043) | Sep 05, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [2870b9e4c7](https://bsd-hardware.info/?probe=2870b9e4c7) | Sep 05, 2022 |
| PC Engines    | APU2                        | Desktop     | [1650d8c419](https://bsd-hardware.info/?probe=1650d8c419) | Sep 05, 2022 |
| PC Engines    | APU2                        | Desktop     | [d9216cb730](https://bsd-hardware.info/?probe=d9216cb730) | Sep 05, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [68ac9de055](https://bsd-hardware.info/?probe=68ac9de055) | Sep 05, 2022 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [5a49c5aa98](https://bsd-hardware.info/?probe=5a49c5aa98) | Sep 05, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [91664c3bc1](https://bsd-hardware.info/?probe=91664c3bc1) | Sep 05, 2022 |
| CncTion       | N5105-4L                    | Desktop     | [2a34dc3fe0](https://bsd-hardware.info/?probe=2a34dc3fe0) | Sep 05, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [734a8e61c4](https://bsd-hardware.info/?probe=734a8e61c4) | Sep 05, 2022 |
| HP            | 8719                        | Desktop     | [f3132fc160](https://bsd-hardware.info/?probe=f3132fc160) | Sep 05, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [34bc2f5c5b](https://bsd-hardware.info/?probe=34bc2f5c5b) | Sep 04, 2022 |
| HP            | ProLiant DL20 Gen9          | Server      | [1eb31c7e35](https://bsd-hardware.info/?probe=1eb31c7e35) | Sep 04, 2022 |
| HP            | ProLiant DL360 G5           | Server      | [770f185ee2](https://bsd-hardware.info/?probe=770f185ee2) | Sep 04, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [ec74af083f](https://bsd-hardware.info/?probe=ec74af083f) | Sep 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [c1967c7cf8](https://bsd-hardware.info/?probe=c1967c7cf8) | Sep 04, 2022 |
| Dell          | 0H5J4J A01                  | Server      | [ab1c1b4aad](https://bsd-hardware.info/?probe=ab1c1b4aad) | Sep 04, 2022 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [3ee914e3a0](https://bsd-hardware.info/?probe=3ee914e3a0) | Sep 04, 2022 |
| MSI           | H81M-P33                    | Desktop     | [3f7258c807](https://bsd-hardware.info/?probe=3f7258c807) | Sep 04, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [cced3168c8](https://bsd-hardware.info/?probe=cced3168c8) | Sep 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [61b82d5ebb](https://bsd-hardware.info/?probe=61b82d5ebb) | Sep 04, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [f4d84edb3b](https://bsd-hardware.info/?probe=f4d84edb3b) | Sep 04, 2022 |
| HP            | ProLiant DL360 G5           | Server      | [387e5946f7](https://bsd-hardware.info/?probe=387e5946f7) | Sep 04, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [a769499d94](https://bsd-hardware.info/?probe=a769499d94) | Sep 04, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [0f35d398cb](https://bsd-hardware.info/?probe=0f35d398cb) | Sep 04, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [860518eb18](https://bsd-hardware.info/?probe=860518eb18) | Sep 04, 2022 |
| Protectli     | FW4B                        | Desktop     | [86a4422a0f](https://bsd-hardware.info/?probe=86a4422a0f) | Sep 04, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [b53e1d28cd](https://bsd-hardware.info/?probe=b53e1d28cd) | Sep 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [4034fae93d](https://bsd-hardware.info/?probe=4034fae93d) | Sep 04, 2022 |
| AMD           | Inagua CRB                  | Desktop     | [de18cc5073](https://bsd-hardware.info/?probe=de18cc5073) | Sep 04, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [5ea71c99c7](https://bsd-hardware.info/?probe=5ea71c99c7) | Sep 03, 2022 |
| Maxtang       | BYT30                       | Desktop     | [f5c34c7662](https://bsd-hardware.info/?probe=f5c34c7662) | Sep 03, 2022 |
| HP            | 1496                        | Desktop     | [94e8713f6d](https://bsd-hardware.info/?probe=94e8713f6d) | Sep 03, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [df57940ad5](https://bsd-hardware.info/?probe=df57940ad5) | Sep 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [88d8df1e3a](https://bsd-hardware.info/?probe=88d8df1e3a) | Sep 03, 2022 |
| ASRock        | Z97 Killer                  | Desktop     | [fac5afc851](https://bsd-hardware.info/?probe=fac5afc851) | Sep 03, 2022 |
| ASRock        | X570S PG Riptide            | Desktop     | [37a7192776](https://bsd-hardware.info/?probe=37a7192776) | Sep 03, 2022 |
| CompuLab      | fitlet                      | Mini pc     | [9772776314](https://bsd-hardware.info/?probe=9772776314) | Sep 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [72cdc4123c](https://bsd-hardware.info/?probe=72cdc4123c) | Sep 03, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [9941ee7afb](https://bsd-hardware.info/?probe=9941ee7afb) | Sep 03, 2022 |
| ASRockRack    | C3558D4I-4L                 | Desktop     | [9beb572e0d](https://bsd-hardware.info/?probe=9beb572e0d) | Sep 03, 2022 |
| Lenovo        | ThinkCentre M70e 0833A29    | Desktop     | [b7c5b9a51d](https://bsd-hardware.info/?probe=b7c5b9a51d) | Sep 03, 2022 |
| ASRock        | X570S PG Riptide            | Desktop     | [0c17c8dc3b](https://bsd-hardware.info/?probe=0c17c8dc3b) | Sep 03, 2022 |
| Dell          | 0DVNTK A00                  | Mini pc     | [216197e933](https://bsd-hardware.info/?probe=216197e933) | Sep 03, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [549daa1a49](https://bsd-hardware.info/?probe=549daa1a49) | Sep 03, 2022 |
| AMD           | Larne CRB                   | Desktop     | [787a51fa78](https://bsd-hardware.info/?probe=787a51fa78) | Sep 03, 2022 |
| Dell          | 0WMJ54 A00                  | Desktop     | [39ee331ecb](https://bsd-hardware.info/?probe=39ee331ecb) | Sep 03, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [62946d2956](https://bsd-hardware.info/?probe=62946d2956) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [72757feb65](https://bsd-hardware.info/?probe=72757feb65) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [5d575c85d0](https://bsd-hardware.info/?probe=5d575c85d0) | Sep 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [b2e4674180](https://bsd-hardware.info/?probe=b2e4674180) | Sep 03, 2022 |
| Intel         | DQ67EP AAG12529-307         | Desktop     | [1fb1fd6705](https://bsd-hardware.info/?probe=1fb1fd6705) | Sep 03, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [bb379f7083](https://bsd-hardware.info/?probe=bb379f7083) | Sep 03, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [2e4b87acd2](https://bsd-hardware.info/?probe=2e4b87acd2) | Sep 03, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [be2c7c6555](https://bsd-hardware.info/?probe=be2c7c6555) | Sep 03, 2022 |
| Unknown       | YL-E3845L4-V2               | Desktop     | [3082ae8ab3](https://bsd-hardware.info/?probe=3082ae8ab3) | Sep 02, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [11ac5a7932](https://bsd-hardware.info/?probe=11ac5a7932) | Sep 02, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [1e05b51bf1](https://bsd-hardware.info/?probe=1e05b51bf1) | Sep 02, 2022 |
| Protectli     | FW4B                        | Desktop     | [1e384b1cf6](https://bsd-hardware.info/?probe=1e384b1cf6) | Sep 02, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [b0ad128162](https://bsd-hardware.info/?probe=b0ad128162) | Sep 02, 2022 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [ce9dc034c9](https://bsd-hardware.info/?probe=ce9dc034c9) | Sep 02, 2022 |
| MSI           | H410M-A PRO                 | Desktop     | [d71ca3999c](https://bsd-hardware.info/?probe=d71ca3999c) | Sep 02, 2022 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [8575ceca09](https://bsd-hardware.info/?probe=8575ceca09) | Sep 02, 2022 |
| HP            | 213D A01                    | Desktop     | [5e8fa931ef](https://bsd-hardware.info/?probe=5e8fa931ef) | Sep 02, 2022 |
| Lenovo        | YangTianM6880N              | Desktop     | [f675498946](https://bsd-hardware.info/?probe=f675498946) | Sep 02, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [1c24e80838](https://bsd-hardware.info/?probe=1c24e80838) | Sep 02, 2022 |
| Intel         | D34010WYK H14771-305        | Desktop     | [ab544a7950](https://bsd-hardware.info/?probe=ab544a7950) | Sep 02, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [73304d07bb](https://bsd-hardware.info/?probe=73304d07bb) | Sep 01, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [3547d9da9c](https://bsd-hardware.info/?probe=3547d9da9c) | Sep 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [0ff0fc4c3b](https://bsd-hardware.info/?probe=0ff0fc4c3b) | Sep 01, 2022 |
| Unknown       | DTB1168                     | Desktop     | [e924ba2a44](https://bsd-hardware.info/?probe=e924ba2a44) | Sep 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [f2a26e2adc](https://bsd-hardware.info/?probe=f2a26e2adc) | Sep 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [9f6f4424c2](https://bsd-hardware.info/?probe=9f6f4424c2) | Sep 01, 2022 |
| Dell          | Latitude E5550              | Notebook    | [867e56fb52](https://bsd-hardware.info/?probe=867e56fb52) | Sep 01, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [9148bf85ec](https://bsd-hardware.info/?probe=9148bf85ec) | Sep 01, 2022 |
| Dell          | 0TY179 A05                  | Server      | [482bca3952](https://bsd-hardware.info/?probe=482bca3952) | Sep 01, 2022 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [91a1870b65](https://bsd-hardware.info/?probe=91a1870b65) | Sep 01, 2022 |
| Dell          | Precision 7710              | Notebook    | [339099bbf0](https://bsd-hardware.info/?probe=339099bbf0) | Sep 01, 2022 |
| HP            | 1496                        | Desktop     | [1567aa1c21](https://bsd-hardware.info/?probe=1567aa1c21) | Sep 01, 2022 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [a8d73a9156](https://bsd-hardware.info/?probe=a8d73a9156) | Sep 01, 2022 |
| Unknown       | HX90                        | Desktop     | [568468e95b](https://bsd-hardware.info/?probe=568468e95b) | Sep 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [b62a001fe9](https://bsd-hardware.info/?probe=b62a001fe9) | Sep 01, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [d26f88ae78](https://bsd-hardware.info/?probe=d26f88ae78) | Sep 01, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [721abbc383](https://bsd-hardware.info/?probe=721abbc383) | Sep 01, 2022 |
| Dell          | 0HYPX2 A00                  | Server      | [2779d78756](https://bsd-hardware.info/?probe=2779d78756) | Sep 01, 2022 |
| Dell          | 07F37C A01                  | Desktop     | [53de9cce89](https://bsd-hardware.info/?probe=53de9cce89) | Sep 01, 2022 |
| Dell          | 0MD99X A07                  | Server      | [3c8cc375dc](https://bsd-hardware.info/?probe=3c8cc375dc) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [4e58d828cc](https://bsd-hardware.info/?probe=4e58d828cc) | Sep 01, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [43a7b45df6](https://bsd-hardware.info/?probe=43a7b45df6) | Sep 01, 2022 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [caf005ed95](https://bsd-hardware.info/?probe=caf005ed95) | Sep 01, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [ebedb51d2f](https://bsd-hardware.info/?probe=ebedb51d2f) | Aug 31, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [78b1cb4ae5](https://bsd-hardware.info/?probe=78b1cb4ae5) | Aug 31, 2022 |
| Dell          | 07T4MC A09                  | Desktop     | [50fbb0435c](https://bsd-hardware.info/?probe=50fbb0435c) | Aug 31, 2022 |
| Dell          | 07T4MC A09                  | Desktop     | [200b8d381e](https://bsd-hardware.info/?probe=200b8d381e) | Aug 31, 2022 |
| Dell          | 07T4MC A09                  | Desktop     | [ebc79d7728](https://bsd-hardware.info/?probe=ebc79d7728) | Aug 31, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [77f98904c2](https://bsd-hardware.info/?probe=77f98904c2) | Aug 31, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [63587e2fca](https://bsd-hardware.info/?probe=63587e2fca) | Aug 31, 2022 |
| ASUSTek       | EX-H110M-V                  | Desktop     | [35e6c8463a](https://bsd-hardware.info/?probe=35e6c8463a) | Aug 31, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [ac185c104b](https://bsd-hardware.info/?probe=ac185c104b) | Aug 31, 2022 |
| Dell          | 0TP412                      | Desktop     | [3ac4a5aa72](https://bsd-hardware.info/?probe=3ac4a5aa72) | Aug 31, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [c77b23d1a7](https://bsd-hardware.info/?probe=c77b23d1a7) | Aug 31, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [0563755b0d](https://bsd-hardware.info/?probe=0563755b0d) | Aug 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [e8259494a3](https://bsd-hardware.info/?probe=e8259494a3) | Aug 31, 2022 |
| Intel         | DENLOW_WS                   | Desktop     | [40053c983b](https://bsd-hardware.info/?probe=40053c983b) | Aug 31, 2022 |
| HP            | 213D A01                    | Desktop     | [c495fb5448](https://bsd-hardware.info/?probe=c495fb5448) | Aug 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [9422de47ab](https://bsd-hardware.info/?probe=9422de47ab) | Aug 30, 2022 |
| HP            | 8103 A01                    | Mini pc     | [58a4089f3f](https://bsd-hardware.info/?probe=58a4089f3f) | Aug 30, 2022 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [e2ad4d8035](https://bsd-hardware.info/?probe=e2ad4d8035) | Aug 30, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [d455ed153a](https://bsd-hardware.info/?probe=d455ed153a) | Aug 30, 2022 |
| Intel         | DENLOW_WS                   | Desktop     | [067a217959](https://bsd-hardware.info/?probe=067a217959) | Aug 30, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [a47c1e0c84](https://bsd-hardware.info/?probe=a47c1e0c84) | Aug 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [98d9c506c9](https://bsd-hardware.info/?probe=98d9c506c9) | Aug 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [fc259fcf3e](https://bsd-hardware.info/?probe=fc259fcf3e) | Aug 30, 2022 |
| Dell          | Precision 5540              | Notebook    | [0c5089634d](https://bsd-hardware.info/?probe=0c5089634d) | Aug 30, 2022 |
| Dell          | Precision 5540              | Notebook    | [afb80a84fb](https://bsd-hardware.info/?probe=afb80a84fb) | Aug 30, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [9d367a6989](https://bsd-hardware.info/?probe=9d367a6989) | Aug 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [6bc59f4024](https://bsd-hardware.info/?probe=6bc59f4024) | Aug 30, 2022 |
| HP            | Unknown                     | Notebook    | [7bd69ee984](https://bsd-hardware.info/?probe=7bd69ee984) | Aug 29, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [b3a1456bb4](https://bsd-hardware.info/?probe=b3a1456bb4) | Aug 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [a01c1ad205](https://bsd-hardware.info/?probe=a01c1ad205) | Aug 29, 2022 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [567bfe0b9f](https://bsd-hardware.info/?probe=567bfe0b9f) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [a5c0fe3db8](https://bsd-hardware.info/?probe=a5c0fe3db8) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | Notebook    | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2349014a6c](https://bsd-hardware.info/?probe=2349014a6c) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | Notebook    | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| Intel         | X79 V2.72A                  | Desktop     | [435901d8c9](https://bsd-hardware.info/?probe=435901d8c9) | Aug 29, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [8d047e7667](https://bsd-hardware.info/?probe=8d047e7667) | Aug 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [411daea5f8](https://bsd-hardware.info/?probe=411daea5f8) | Aug 29, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [97bf732bfe](https://bsd-hardware.info/?probe=97bf732bfe) | Aug 29, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [19e3294fe9](https://bsd-hardware.info/?probe=19e3294fe9) | Aug 29, 2022 |
| Dell          | Latitude 7390               | Notebook    | [bc5eb8e237](https://bsd-hardware.info/?probe=bc5eb8e237) | Aug 29, 2022 |
| Acer          | FIH57                       | Desktop     | [78265cbc90](https://bsd-hardware.info/?probe=78265cbc90) | Aug 29, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [4d7efd6aa6](https://bsd-hardware.info/?probe=4d7efd6aa6) | Aug 28, 2022 |
| Dell          | 0654JC A02                  | Desktop     | [07144a803b](https://bsd-hardware.info/?probe=07144a803b) | Aug 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [525631a32f](https://bsd-hardware.info/?probe=525631a32f) | Aug 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [a3677591ec](https://bsd-hardware.info/?probe=a3677591ec) | Aug 28, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [75ec0260f9](https://bsd-hardware.info/?probe=75ec0260f9) | Aug 28, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [079adb24f8](https://bsd-hardware.info/?probe=079adb24f8) | Aug 28, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [e7dc9cc5ee](https://bsd-hardware.info/?probe=e7dc9cc5ee) | Aug 28, 2022 |
| Dell          | PowerEdge R610              | Server      | [6006aed07f](https://bsd-hardware.info/?probe=6006aed07f) | Aug 28, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [df3df2855b](https://bsd-hardware.info/?probe=df3df2855b) | Aug 28, 2022 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 368       | 3.69%   |
| OPNsense 21.7.7      | 281       | 2.81%   |
| helloSystem 0.5.0    | 244       | 2.44%   |
| OPNsense 21.1        | 240       | 2.4%    |
| OPNsense 21.7.1      | 229       | 2.29%   |
| OPNsense 22.1        | 227       | 2.27%   |
| OPNsense 21.7.3      | 225       | 2.25%   |
| OPNsense 21.1.5      | 225       | 2.25%   |
| FreeBSD 13.0         | 222       | 2.22%   |
| OPNsense 22.7.4      | 214       | 2.14%   |
| OPNsense 20.7.8      | 214       | 2.14%   |
| OpenBSD 6.8          | 208       | 2.08%   |
| OPNsense 21.1.3      | 205       | 2.05%   |
| OPNsense 22.1.6      | 191       | 1.91%   |
| helloSystem 0.4.0    | 190       | 1.9%    |
| OPNsense 22.1.8      | 187       | 1.87%   |
| OPNsense 21.1.4      | 175       | 1.75%   |
| OPNsense 22.7.6      | 172       | 1.72%   |
| FreeBSD 13.1         | 168       | 1.68%   |
| OPNsense 22.1.10     | 159       | 1.59%   |
| OPNsense 21.1.1      | 157       | 1.57%   |
| OPNsense 21.1.2      | 147       | 1.47%   |
| FreeBSD 12.2         | 141       | 1.41%   |
| helloSystem 0.6.0    | 136       | 1.36%   |
| OPNsense 22.1.4      | 134       | 1.34%   |
| OPNsense 21.7.6      | 131       | 1.31%   |
| OPNsense 21.1.6      | 129       | 1.29%   |
| OPNsense 22.7        | 128       | 1.28%   |
| OPNsense 21.1.7      | 127       | 1.27%   |
| OPNsense 22.7.2      | 122       | 1.22%   |
| OPNsense 21.1.8      | 122       | 1.22%   |
| OPNsense 22.1.2      | 120       | 1.2%    |
| OPNsense 22.1.1      | 115       | 1.15%   |
| OPNsense 21.7.5      | 113       | 1.13%   |
| GhostBSD 20.04.02    | 109       | 1.09%   |
| OPNsense 22.1.7      | 106       | 1.06%   |
| FreeBSD 14.0-CURRENT | 105       | 1.05%   |
| FreeBSD 12.2-p2      | 96        | 0.96%   |
| OPNsense 21.7.2      | 95        | 0.95%   |
| OPNsense 21.7.4      | 93        | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 3988      | 50.39%  |
| FreeBSD     | 1885      | 23.82%  |
| helloSystem | 981       | 12.39%  |
| OpenBSD     | 473       | 5.98%   |
| GhostBSD    | 204       | 2.58%   |
| NomadBSD    | 146       | 1.84%   |
| NetBSD      | 54        | 0.68%   |
| TrueNAS     | 41        | 0.52%   |
| FreeNAS     | 30        | 0.38%   |
| pfSense     | 25        | 0.32%   |
| HardenedBSD | 19        | 0.24%   |
| DragonFly   | 16        | 0.2%    |
| MidnightBSD | 12        | 0.15%   |
| FuryBSD     | 11        | 0.14%   |
| MyBee       | 10        | 0.13%   |
| XigmaNAS    | 6         | 0.08%   |
| OS108       | 4         | 0.05%   |
| PC-BSD      | 3         | 0.04%   |
| ClonOS      | 3         | 0.04%   |
| FuguIta     | 2         | 0.03%   |
| Ting        | 1         | 0.01%   |
| LibertyBSD  | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 7562      | 96.89%  |
| i386    | 120       | 1.54%   |
| arm64   | 91        | 1.17%   |
| arm     | 11        | 0.14%   |
| evbarm  | 6         | 0.08%   |
| macppc  | 5         | 0.06%   |
| sparc64 | 3         | 0.04%   |
| powerpc | 2         | 0.03%   |
| octeon  | 2         | 0.03%   |
| armv7   | 2         | 0.03%   |
| riscv   | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Console          | 4902      | 61.28%  |
| helloDesktop     | 1071      | 13.39%  |
| XFCE             | 374       | 4.68%   |
| KDE5             | 329       | 4.11%   |
| fvwm             | 274       | 3.43%   |
| MATE             | 269       | 3.36%   |
| Openbox          | 187       | 2.34%   |
| TWM              | 153       | 1.91%   |
| GNOME            | 153       | 1.91%   |
| i3               | 95        | 1.19%   |
| Cinnamon         | 31        | 0.39%   |
| AwesomeWM        | 24        | 0.3%    |
| LXQt             | 19        | 0.24%   |
| Fluxbox          | 19        | 0.24%   |
| LXDE             | 15        | 0.19%   |
| Enlightenment    | 15        | 0.19%   |
| Lumina           | 11        | 0.14%   |
| DWM              | 8         | 0.1%    |
| GNUstep          | 5         | 0.06%   |
| xfwm             | 4         | 0.05%   |
| CTWM             | 4         | 0.05%   |
| CDE              | 4         | 0.05%   |
| Window Maker     | 3         | 0.04%   |
| spectrwm         | 3         | 0.04%   |
| Picom            | 3         | 0.04%   |
| Xfwm4            | 2         | 0.03%   |
| X-Cinnamon       | 2         | 0.03%   |
| Mutter           | 2         | 0.03%   |
| Metacity (Marco) | 2         | 0.03%   |
| IceWM            | 2         | 0.03%   |
| Compton          | 2         | 0.03%   |
| awesome          | 2         | 0.03%   |
| xinitrc          | 1         | 0.01%   |
| StumpWM          | 1         | 0.01%   |
| Ratpoison        | 1         | 0.01%   |
| plasma           | 1         | 0.01%   |
| PekWM            | 1         | 0.01%   |
| KWin             | 1         | 0.01%   |
| KDE              | 1         | 0.01%   |
| iwm              | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 4989      | 63.58%  |
| X11     | 2826      | 36.01%  |
| Wayland | 32        | 0.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 5705      | 71.92%  |
| SLiM    | 1354      | 17.07%  |
| SDDM    | 310       | 3.91%   |
| LightDM | 306       | 3.86%   |
| XDM     | 132       | 1.66%   |
| GDM     | 112       | 1.41%   |
| Ly      | 10        | 0.13%   |
| PCDM    | 2         | 0.03%   |
| WDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 5087      | 63.58%  |
| en_US            | 1494      | 18.67%  |
| C                | 853       | 10.66%  |
| ru_RU            | 147       | 1.84%   |
| de_DE            | 83        | 1.04%   |
| fr_FR            | 50        | 0.62%   |
| en_GB            | 46        | 0.57%   |
| es_ES            | 21        | 0.26%   |
| zh_CN            | 18        | 0.22%   |
| pt_BR            | 15        | 0.19%   |
| it_IT            | 15        | 0.19%   |
| pl_PL            | 13        | 0.16%   |
| en_CA            | 13        | 0.16%   |
| en_AU            | 12        | 0.15%   |
| uk_UA            | 10        | 0.12%   |
| ja_JP            | 10        | 0.12%   |
| nb_NO            | 7         | 0.09%   |
| hu_HU            | 6         | 0.07%   |
| fi_FI            | 6         | 0.07%   |
| en_IE            | 6         | 0.07%   |
| es_AR            | 5         | 0.06%   |
| en_NZ            | 5         | 0.06%   |
| el_GR            | 5         | 0.06%   |
| sv_SE            | 4         | 0.05%   |
| en_US.ISO8859-1  | 4         | 0.05%   |
| cs_CZ            | 4         | 0.05%   |
| tr_TR            | 3         | 0.04%   |
| ru_RU.KOI8-R     | 3         | 0.04%   |
| en_US.US-ASCII   | 3         | 0.04%   |
| de_DE.ISO8859-1  | 3         | 0.04%   |
| de_CH            | 3         | 0.04%   |
| zh_TW            | 2         | 0.02%   |
| sl_SI            | 2         | 0.02%   |
| sk_SK            | 2         | 0.02%   |
| pt_PT            | 2         | 0.02%   |
| nl_NL            | 2         | 0.02%   |
| it_IT.ISO8859-15 | 2         | 0.02%   |
| es_CO            | 2         | 0.02%   |
| en_SG            | 2         | 0.02%   |
| en_GB.US-ASCII   | 2         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 6237      | 78.92%  |
| BIOS | 1666      | 21.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 4075      | 50.95%  |
| Zfs     | 3167      | 39.6%   |
| Ffs     | 476       | 5.95%   |
| Cd9660  | 254       | 3.18%   |
| Hammer2 | 15        | 0.19%   |
| Unknown | 6         | 0.08%   |
| XXX     | 3         | 0.04%   |
| Xfs     | 1         | 0.01%   |
| Nfs     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 6942      | 88.25%  |
| MBR     | 810       | 10.3%   |
| Unknown | 100       | 1.27%   |
| BSD     | 14        | 0.18%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 943       | 12.09%  |
| Lenovo                     | 814       | 10.43%  |
| ASUSTek Computer           | 697       | 8.93%   |
| Hewlett-Packard            | 676       | 8.66%   |
| Unknown                    | 564       | 7.23%   |
| Supermicro                 | 392       | 5.02%   |
| Intel                      | 379       | 4.86%   |
| Gigabyte Technology        | 345       | 4.42%   |
| ASRock                     | 336       | 4.31%   |
| PC Engines                 | 268       | 3.43%   |
| MSI                        | 230       | 2.95%   |
| Protectli                  | 228       | 2.92%   |
| AMI                        | 149       | 1.91%   |
| Acer                       | 143       | 1.83%   |
| Fujitsu                    | 135       | 1.73%   |
| Apple                      | 132       | 1.69%   |
| Sophos                     | 97        | 1.24%   |
| ZOTAC                      | 70        | 0.9%    |
| Deciso                     | 60        | 0.77%   |
| BESSTAR Tech               | 57        | 0.73%   |
| Shuttle                    | 55        | 0.7%    |
| Toshiba                    | 46        | 0.59%   |
| Biostar                    | 35        | 0.45%   |
| IBM                        | 34        | 0.44%   |
| Samsung Electronics        | 33        | 0.42%   |
| AWOW                       | 29        | 0.37%   |
| Sony                       | 28        | 0.36%   |
| HARDKERNEL                 | 27        | 0.35%   |
| ASRockRack                 | 27        | 0.35%   |
| CompuLab                   | 24        | 0.31%   |
| MW                         | 22        | 0.28%   |
| Raspberry Pi Foundation    | 20        | 0.26%   |
| Foxconn                    | 20        | 0.26%   |
| AZW                        | 20        | 0.26%   |
| Pegatron                   | 19        | 0.24%   |
| HPE                        | 17        | 0.22%   |
| System76                   | 15        | 0.19%   |
| YANYU                      | 14        | 0.18%   |
| ShenZhen MinWin Technology | 14        | 0.18%   |
| TUXEDO                     | 13        | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 592       | 7.59%   |
| PC Engines APU2                     | 131       | 1.68%   |
| AMI Aptio CRB                       | 118       | 1.51%   |
| Supermicro Super Server             | 104       | 1.33%   |
| Intel Q3XXG4-P V1.0                 | 95        | 1.22%   |
| Protectli FW4B                      | 93        | 1.19%   |
| PC Engines apu4                     | 86        | 1.1%    |
| Protectli FW6                       | 72        | 0.92%   |
| ASUS All Series                     | 67        | 0.86%   |
| Sophos SG                           | 45        | 0.58%   |
| HP t620 PLUS Quad Core TC           | 45        | 0.58%   |
| Dell PowerEdge R210 II              | 39        | 0.5%    |
| HP t730 Thin Client                 | 38        | 0.49%   |
| Dell OptiPlex 9020                  | 38        | 0.49%   |
| Fujitsu FUTRO S920                  | 35        | 0.45%   |
| Dell OptiPlex 3020                  | 32        | 0.41%   |
| Sophos XG                           | 30        | 0.38%   |
| Hardkernel ODROID-H2                | 26        | 0.33%   |
| Dell OptiPlex 7010                  | 25        | 0.32%   |
| Supermicro X9SCL/X9SCM              | 23        | 0.29%   |
| Sophos UTM                          | 22        | 0.28%   |
| MW GMLK-2_5G4L                      | 22        | 0.28%   |
| Supermicro A1SAi                    | 21        | 0.27%   |
| Deciso Netboard A20                 | 21        | 0.27%   |
| PC Engines APU                      | 20        | 0.26%   |
| HP ProLiant MicroServer Gen8        | 20        | 0.26%   |
| AWOW PC BOX                         | 20        | 0.26%   |
| PC Engines APU3                     | 19        | 0.24%   |
| HP EliteDesk 800 G1 SFF             | 19        | 0.24%   |
| CompuLab fitlet2                    | 19        | 0.24%   |
| Supermicro X10SLH-N6-ST031          | 18        | 0.23%   |
| Dell PowerEdge R710                 | 18        | 0.23%   |
| Dell Wyse 5070 Extended Thin Client | 17        | 0.22%   |
| Dell PowerEdge R610                 | 17        | 0.22%   |
| Protectli VP2410                    | 16        | 0.21%   |
| HP Compaq Elite 8300 SFF            | 15        | 0.19%   |
| Dell OptiPlex 790                   | 15        | 0.19%   |
| BESSTAR Tech GK41                   | 15        | 0.19%   |
| ZOTAC ZBOX-CI329NANO                | 14        | 0.18%   |
| RPi Raspberry Pi                    | 14        | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Unknown              | 592       | 7.59%   |
| Lenovo ThinkPad      | 501       | 6.42%   |
| Dell OptiPlex        | 283       | 3.63%   |
| Dell PowerEdge       | 242       | 3.1%    |
| Dell Latitude        | 133       | 1.7%    |
| Lenovo ThinkCentre   | 132       | 1.69%   |
| PC Engines APU2      | 131       | 1.68%   |
| HP ProLiant          | 122       | 1.56%   |
| AMI Aptio            | 120       | 1.54%   |
| Supermicro Super     | 104       | 1.33%   |
| Dell Inspiron        | 100       | 1.28%   |
| ASUS PRIME           | 99        | 1.27%   |
| Intel Q3XXG4-P       | 96        | 1.23%   |
| Protectli FW4B       | 93        | 1.19%   |
| Acer Aspire          | 92        | 1.18%   |
| PC Engines apu4      | 86        | 1.1%    |
| HP Compaq            | 85        | 1.09%   |
| Protectli FW6        | 72        | 0.92%   |
| Dell Precision       | 72        | 0.92%   |
| ASUS All             | 67        | 0.86%   |
| HP EliteDesk         | 56        | 0.72%   |
| HP ProDesk           | 55        | 0.7%    |
| Fujitsu FUTRO        | 52        | 0.67%   |
| Lenovo IdeaPad       | 49        | 0.63%   |
| HP t620              | 48        | 0.62%   |
| ASUS ROG             | 47        | 0.6%    |
| Sophos SG            | 45        | 0.58%   |
| ASUS TUF             | 45        | 0.58%   |
| Deciso Netboard      | 40        | 0.51%   |
| HP Pavilion          | 39        | 0.5%    |
| HP t730              | 38        | 0.49%   |
| HP EliteBook         | 37        | 0.47%   |
| Toshiba Satellite    | 32        | 0.41%   |
| Sophos XG            | 30        | 0.38%   |
| HP ProBook           | 27        | 0.35%   |
| HARDKERNEL ODROID-H2 | 26        | 0.33%   |
| Dell XPS             | 26        | 0.33%   |
| Fujitsu ESPRIMO      | 25        | 0.32%   |
| Supermicro X9SCL     | 23        | 0.29%   |
| Sophos UTM           | 22        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 936       | 12%     |
| 2019    | 841       | 10.78%  |
| 2020    | 831       | 10.65%  |
| 2021    | 614       | 7.87%   |
| 2016    | 601       | 7.7%    |
| 2014    | 561       | 7.19%   |
| 2013    | 507       | 6.5%    |
| 2017    | 453       | 5.81%   |
| 2015    | 447       | 5.73%   |
| 2011    | 430       | 5.51%   |
| 2012    | 396       | 5.07%   |
| 2010    | 292       | 3.74%   |
| 2009    | 231       | 2.96%   |
| 2022    | 202       | 2.59%   |
| 2008    | 151       | 1.94%   |
| Unknown | 148       | 1.9%    |
| 2007    | 83        | 1.06%   |
| 2006    | 42        | 0.54%   |
| 2005    | 11        | 0.14%   |
| 2004    | 11        | 0.14%   |
| 2003    | 8         | 0.1%    |
| 2002    | 5         | 0.06%   |
| 2001    | 2         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 4549      | 58.3%   |
| Notebook       | 1834      | 23.5%   |
| Server         | 636       | 8.15%   |
| Mini pc        | 526       | 6.74%   |
| Firewall       | 116       | 1.49%   |
| System on chip | 50        | 0.64%   |
| All in one     | 48        | 0.62%   |
| Convertible    | 39        | 0.5%    |
| Tablet         | 5         | 0.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7413      | 95%     |
| Yes  | 390       | 5%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 2755      | 34.74%  |
| 4.01-8.0        | 1778      | 22.42%  |
| 16.01-24.0      | 1630      | 20.55%  |
| 32.01-64.0      | 701       | 8.84%   |
| 64.01-256.0     | 321       | 4.05%   |
| 2.01-3.0        | 311       | 3.92%   |
| 3.01-4.0        | 137       | 1.73%   |
| 24.01-32.0      | 113       | 1.42%   |
| 0.51-1.0        | 78        | 0.98%   |
| 1.01-2.0        | 59        | 0.74%   |
| 0.01-0.5        | 27        | 0.34%   |
| More than 256.0 | 18        | 0.23%   |
| Unknown         | 2         | 0.03%   |
| 0               | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 0.01-0.5        | 4180      | 51.62%  |
| 0.51-1.0        | 2188      | 27.02%  |
| 1.01-2.0        | 840       | 10.37%  |
| 2.01-3.0        | 218       | 2.69%   |
| 4.01-8.0        | 178       | 2.2%    |
| 3.01-4.0        | 125       | 1.54%   |
| 8.01-16.0       | 93        | 1.15%   |
| Unknown         | 67        | 0.83%   |
| 0               | 61        | 0.75%   |
| 24.01-32.0      | 44        | 0.54%   |
| 16.01-24.0      | 44        | 0.54%   |
| 32.01-64.0      | 36        | 0.44%   |
| 64.01-256.0     | 23        | 0.28%   |
| More than 256.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 5296      | 66.08%  |
| 2      | 1192      | 14.87%  |
| 0      | 640       | 7.99%   |
| 3      | 343       | 4.28%   |
| 4      | 214       | 2.67%   |
| 5      | 101       | 1.26%   |
| 6      | 72        | 0.9%    |
| 7      | 37        | 0.46%   |
| 8      | 23        | 0.29%   |
| 14     | 16        | 0.2%    |
| 10     | 13        | 0.16%   |
| 12     | 12        | 0.15%   |
| 9      | 12        | 0.15%   |
| 11     | 9         | 0.11%   |
| 17     | 5         | 0.06%   |
| 25     | 3         | 0.04%   |
| 18     | 3         | 0.04%   |
| 15     | 3         | 0.04%   |
| 13     | 3         | 0.04%   |
| 40     | 2         | 0.02%   |
| 23     | 2         | 0.02%   |
| 21     | 2         | 0.02%   |
| 19     | 2         | 0.02%   |
| 16     | 2         | 0.02%   |
| 63     | 1         | 0.01%   |
| 58     | 1         | 0.01%   |
| 28     | 1         | 0.01%   |
| 27     | 1         | 0.01%   |
| 26     | 1         | 0.01%   |
| 24     | 1         | 0.01%   |
| 22     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 6219      | 79.07%  |
| Yes       | 1646      | 20.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7424      | 95.13%  |
| No        | 380       | 4.87%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4830      | 61.43%  |
| Yes       | 3033      | 38.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5891      | 74.91%  |
| Yes       | 1973      | 25.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1965      | 25.07%  |
| Germany      | 1318      | 16.82%  |
| Russia       | 419       | 5.35%   |
| France       | 321       | 4.1%    |
| UK           | 315       | 4.02%   |
| Canada       | 281       | 3.59%   |
| Netherlands  | 208       | 2.65%   |
| Poland       | 200       | 2.55%   |
| Brazil       | 185       | 2.36%   |
| Australia    | 181       | 2.31%   |
| Switzerland  | 157       | 2%      |
| Italy        | 156       | 1.99%   |
| Austria      | 143       | 1.82%   |
| China        | 132       | 1.68%   |
| Spain        | 123       | 1.57%   |
| Sweden       | 121       | 1.54%   |
| Ukraine      | 94        | 1.2%    |
| Czechia      | 79        | 1.01%   |
| Norway       | 74        | 0.94%   |
| Finland      | 68        | 0.87%   |
| Japan        | 67        | 0.85%   |
| India        | 65        | 0.83%   |
| Romania      | 61        | 0.78%   |
| Hungary      | 61        | 0.78%   |
| Indonesia    | 58        | 0.74%   |
| Portugal     | 54        | 0.69%   |
| Belgium      | 52        | 0.66%   |
| Denmark      | 46        | 0.59%   |
| Taiwan       | 44        | 0.56%   |
| Mexico       | 43        | 0.55%   |
| New Zealand  | 40        | 0.51%   |
| South Korea  | 35        | 0.45%   |
| South Africa | 35        | 0.45%   |
| Argentina    | 34        | 0.43%   |
| Greece       | 33        | 0.42%   |
| Bulgaria     | 28        | 0.36%   |
| Thailand     | 27        | 0.34%   |
| Turkey       | 26        | 0.33%   |
| Slovenia     | 22        | 0.28%   |
| Singapore    | 22        | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 134       | 1.57%   |
| Berlin            | 126       | 1.47%   |
| Vienna            | 81        | 0.95%   |
| Paris             | 72        | 0.84%   |
| Munich            | 59        | 0.69%   |
| Hamburg           | 51        | 0.6%    |
| Sydney            | 46        | 0.54%   |
| Zurich            | 45        | 0.53%   |
| Amsterdam         | 45        | 0.53%   |
| St Petersburg     | 42        | 0.49%   |
| Brooklyn          | 37        | 0.43%   |
| Kyiv              | 36        | 0.42%   |
| Frankfurt am Main | 36        | 0.42%   |
| London            | 35        | 0.41%   |
| Warsaw            | 34        | 0.4%    |
| Melbourne         | 33        | 0.39%   |
| Cologne           | 33        | 0.39%   |
| Chicago           | 33        | 0.39%   |
| Bucharest         | 32        | 0.37%   |
| Jakarta           | 31        | 0.36%   |
| Montreal          | 30        | 0.35%   |
| Toronto           | 29        | 0.34%   |
| Seattle           | 28        | 0.33%   |
| Denver            | 28        | 0.33%   |
| Prague            | 27        | 0.32%   |
| New York          | 27        | 0.32%   |
| Perth             | 26        | 0.3%    |
| Oslo              | 26        | 0.3%    |
| Helsinki          | 26        | 0.3%    |
| Madrid            | 25        | 0.29%   |
| Stuttgart         | 24        | 0.28%   |
| Portland          | 23        | 0.27%   |
| Milan             | 23        | 0.27%   |
| Dallas            | 23        | 0.27%   |
| Brisbane          | 23        | 0.27%   |
| Athens            | 22        | 0.26%   |
| Singapore         | 21        | 0.25%   |
| SГЈo Paulo      | 19        | 0.22%   |
| Rome              | 19        | 0.22%   |
| Rochester         | 19        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1438      | 2266   | 15.38%  |
| WDC                 | 1279      | 2713   | 13.68%  |
| Seagate             | 1003      | 2091   | 10.73%  |
| Kingston            | 684       | 947    | 7.32%   |
| Crucial             | 458       | 662    | 4.9%    |
| Toshiba             | 438       | 783    | 4.69%   |
| SanDisk             | 405       | 532    | 4.33%   |
| Intel               | 383       | 622    | 4.1%    |
| Transcend           | 362       | 506    | 3.87%   |
| Hitachi             | 239       | 478    | 2.56%   |
| A-DATA Technology   | 176       | 245    | 1.88%   |
| Hoodisk             | 162       | 234    | 1.73%   |
| HGST                | 156       | 403    | 1.67%   |
| Phison              | 154       | 216    | 1.65%   |
| China               | 121       | 167    | 1.29%   |
| Hewlett-Packard     | 104       | 318    | 1.11%   |
| Micron Technology   | 101       | 159    | 1.08%   |
| SK hynix            | 95        | 120    | 1.02%   |
| NVMe                | 91        | 122    | 0.97%   |
| SPCC                | 81        | 122    | 0.87%   |
| OCZ                 | 76        | 100    | 0.81%   |
| FORESEE             | 71        | 103    | 0.76%   |
| PNY                 | 68        | 110    | 0.73%   |
| Apacer              | 61        | 69     | 0.65%   |
| Corsair             | 53        | 82     | 0.57%   |
| Protectli           | 48        | 75     | 0.51%   |
| Dogfish             | 48        | 75     | 0.51%   |
| Intenso             | 47        | 74     | 0.5%    |
| Apple               | 46        | 50     | 0.49%   |
| KingSpec            | 39        | 47     | 0.42%   |
| Patriot             | 36        | 51     | 0.39%   |
| LITEON              | 36        | 48     | 0.39%   |
| BIWIN               | 34        | 49     | 0.36%   |
| LITEONIT            | 31        | 34     | 0.33%   |
| Innodisk            | 30        | 36     | 0.32%   |
| Gigabyte Technology | 30        | 41     | 0.32%   |
| Fujitsu             | 30        | 41     | 0.32%   |
| Plextor             | 26        | 39     | 0.28%   |
| Maxtor              | 25        | 31     | 0.27%   |
| Goodram             | 24        | 34     | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 109       | 1.06%   |
| Samsung SSD 850 EVO 250GB          | 97        | 0.94%   |
| Kingston SA400S37120G 120GB        | 89        | 0.87%   |
| Phison SATA SSD 16GB               | 74        | 0.72%   |
| Samsung SSD 860 EVO 500GB          | 65        | 0.63%   |
| Kingston SUV500MS120G 120GB        | 62        | 0.6%    |
| Samsung SSD 860 EVO 250GB          | 60        | 0.58%   |
| Crucial CT240BX500SSD1 240GB       | 56        | 0.55%   |
| Seagate ST500DM002-1BD142 500GB    | 53        | 0.52%   |
| Samsung SSD 850 EVO 500GB          | 49        | 0.48%   |
| Crucial CT250MX500SSD1 250GB       | 49        | 0.48%   |
| Hoodisk SSD 32GB                   | 45        | 0.44%   |
| Hoodisk SSD 128GB                  | 45        | 0.44%   |
| Crucial CT500MX500SSD1 500GB       | 45        | 0.44%   |
| Kingston SV300S37A120G 120GB       | 43        | 0.42%   |
| Crucial CT120BX500SSD1 120GB       | 43        | 0.42%   |
| Transcend TS128GMSA230S 128GB      | 42        | 0.41%   |
| Hoodisk SSD 64GB                   | 41        | 0.4%    |
| Seagate ST1000DM010-2EP102 1TB     | 40        | 0.39%   |
| Seagate ST1000LM035-1RK172 1TB     | 39        | 0.38%   |
| FORESEE 128GB SSD                  | 39        | 0.38%   |
| Toshiba DT01ACA100 1TB             | 37        | 0.36%   |
| HP RAID 1(1+0) 2TB                 | 37        | 0.36%   |
| Samsung SSD 840 EVO 250GB          | 36        | 0.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 35        | 0.34%   |
| WDC WD40EFRX-68N32N0 4TB           | 34        | 0.33%   |
| Kingston SUV500MS240G 240GB        | 34        | 0.33%   |
| Toshiba MQ01ABD100 1TB             | 33        | 0.32%   |
| Samsung SSD 860 EVO 1TB            | 33        | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB       | 32        | 0.31%   |
| Samsung SSD 970 EVO Plus 500GB     | 31        | 0.3%    |
| WDC WDS120G2G0A-00JH30 120GB       | 30        | 0.29%   |
| Kingston SA400S37480G 480GB        | 29        | 0.28%   |
| PNY CS900 120GB SSD                | 28        | 0.27%   |
| A-DATA SU650 120GB                 | 28        | 0.27%   |
| SanDisk SDSSDA120G 120GB           | 27        | 0.26%   |
| WDC WD10EZEX-08WN4A0 1TB           | 26        | 0.25%   |
| Seagate ST1000DM003-1CH162 1TB     | 26        | 0.25%   |
| SanDisk SSD PLUS 120GB             | 26        | 0.25%   |
| Samsung SSD 970 EVO Plus 250GB     | 26        | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC                                | 995       | 2217   | 31.38%  |
| Seagate                            | 978       | 2040   | 30.84%  |
| Toshiba                            | 344       | 637    | 10.85%  |
| Hitachi                            | 238       | 474    | 7.51%   |
| HGST                               | 156       | 403    | 4.92%   |
| Samsung Electronics                | 145       | 204    | 4.57%   |
| Hewlett-Packard                    | 80        | 268    | 2.52%   |
| NVMe                               | 60        | 80     | 1.89%   |
| Fujitsu                            | 29        | 39     | 0.91%   |
| Maxtor                             | 25        | 31     | 0.79%   |
| Apple                              | 16        | 19     | 0.5%    |
| OPENBSD                            | 14        | 19     | 0.44%   |
| Dell                               | 11        | 43     | 0.35%   |
| LSI                                | 8         | 14     | 0.25%   |
| HPE                                | 7         | 29     | 0.22%   |
| Generic                            | 5         | 5      | 0.16%   |
| USB                                | 4         | 4      | 0.13%   |
| Adaptec                            | 4         | 14     | 0.13%   |
| Lexar                              | 3         | 3      | 0.09%   |
| JetFlash                           | 3         | 3      | 0.09%   |
| HPT                                | 3         | 35     | 0.09%   |
| WD MediaMax                        | 2         | 5      | 0.06%   |
| StoreJet                           | 2         | 2      | 0.06%   |
| NETAPP                             | 2         | 4      | 0.06%   |
| Multiple                           | 2         | 2      | 0.06%   |
| MaxDigital                         | 2         | 2      | 0.06%   |
| LSILOGIC                           | 2         | 5      | 0.06%   |
| Lenovo                             | 2         | 4      | 0.06%   |
| IBM/Hitachi                        | 2         | 2      | 0.06%   |
| IBM                                | 2         | 2      | 0.06%   |
| Cisco                              | 2         | 3      | 0.06%   |
| China                              | 2         | 2      | 0.06%   |
| ASMT                               | 2         | 2      | 0.06%   |
| Areca                              | 2         | 3      | 0.06%   |
| UFD 2.0                            | 1         | 1      | 0.03%   |
| SYNOLOGY                           | 1         | 1      | 0.03%   |
| SSDPR-CX                           | 1         | 1      | 0.03%   |
| SABRENT                            | 1         | 1      | 0.03%   |
| QUANTUM                            | 1         | 2      | 0.03%   |
| Product:              USB DISK 3.0 | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 948       | 1455   | 18.44%  |
| Kingston            | 610       | 845    | 11.87%  |
| SanDisk             | 403       | 527    | 7.84%   |
| Crucial             | 400       | 584    | 7.78%   |
| Transcend           | 335       | 474    | 6.52%   |
| Intel               | 313       | 525    | 6.09%   |
| WDC                 | 184       | 282    | 3.58%   |
| Hoodisk             | 161       | 233    | 3.13%   |
| A-DATA Technology   | 144       | 193    | 2.8%    |
| China               | 119       | 165    | 2.31%   |
| Phison              | 118       | 157    | 2.3%    |
| Micron Technology   | 79        | 126    | 1.54%   |
| OCZ                 | 76        | 100    | 1.48%   |
| SPCC                | 71        | 106    | 1.38%   |
| FORESEE             | 69        | 101    | 1.34%   |
| PNY                 | 62        | 101    | 1.21%   |
| Apacer              | 61        | 69     | 1.19%   |
| Toshiba             | 60        | 84     | 1.17%   |
| Protectli           | 48        | 75     | 0.93%   |
| Dogfish             | 48        | 75     | 0.93%   |
| Intenso             | 46        | 73     | 0.89%   |
| SK hynix            | 45        | 55     | 0.88%   |
| Corsair             | 40        | 55     | 0.78%   |
| KingSpec            | 39        | 47     | 0.76%   |
| Patriot             | 34        | 49     | 0.66%   |
| LITEON              | 34        | 46     | 0.66%   |
| BIWIN               | 32        | 47     | 0.62%   |
| LITEONIT            | 31        | 34     | 0.6%    |
| Innodisk            | 30        | 36     | 0.58%   |
| Apple               | 29        | 30     | 0.56%   |
| NVMe                | 26        | 31     | 0.51%   |
| Plextor             | 23        | 32     | 0.45%   |
| Kston               | 20        | 25     | 0.39%   |
| GOODRAM             | 20        | 29     | 0.39%   |
| Gigabyte Technology | 18        | 27     | 0.35%   |
| Seagate             | 17        | 35     | 0.33%   |
| ATP                 | 16        | 16     | 0.31%   |
| Mushkin             | 15        | 19     | 0.29%   |
| Hewlett-Packard     | 14        | 21     | 0.27%   |
| Netac               | 13        | 17     | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 4680      | 7423   | 55.87%  |
| HDD  | 2602      | 6640   | 31.06%  |
| NVMe | 1095      | 1676   | 13.07%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6509      | 14063  | 85.6%   |
| NVMe | 1095      | 1676   | 14.4%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 5555      | 9045   | 72.77%  |
| 0.51-1.0        | 1136      | 1915   | 14.88%  |
| 1.01-2.0        | 426       | 985    | 5.58%   |
| 3.01-4.0        | 190       | 705    | 2.49%   |
| 4.01-10.0       | 166       | 811    | 2.17%   |
| 2.01-3.0        | 117       | 414    | 1.53%   |
| 10.01-20.0      | 38        | 179    | 0.5%    |
| 20.01-50.0      | 3         | 6      | 0.04%   |
| More than 100.0 | 2         | 2      | 0.03%   |
| 0               | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2971      | 36.62%  |
| 1-20           | 1293      | 15.94%  |
| 251-500        | 1287      | 15.87%  |
| 51-100         | 874       | 10.77%  |
| 21-50          | 769       | 9.48%   |
| 501-1000       | 576       | 7.1%    |
| 1001-2000      | 160       | 1.97%   |
| More than 3000 | 83        | 1.02%   |
| Unknown        | 60        | 0.74%   |
| 2001-3000      | 39        | 0.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 7006      | 87.04%  |
| 21-50          | 494       | 6.14%   |
| 51-100         | 199       | 2.47%   |
| 101-250        | 138       | 1.71%   |
| Unknown        | 60        | 0.75%   |
| 251-500        | 53        | 0.66%   |
| 501-1000       | 41        | 0.51%   |
| More than 3000 | 23        | 0.29%   |
| 1001-2000      | 21        | 0.26%   |
| 2001-3000      | 13        | 0.16%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 21        | 33     | 1.62%   |
| Kingston SV300S37A120G 120GB        | 14        | 16     | 1.08%   |
| HGST HTS725050A7E630 500GB          | 13        | 23     | 1%      |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 12        | 15     | 0.93%   |
| Seagate ST500LT012-9WS142 500GB     | 11        | 16     | 0.85%   |
| Seagate ST500LM021-1KJ152 500GB     | 11        | 11     | 0.85%   |
| Toshiba MQ01ABD100 1TB              | 9         | 9      | 0.69%   |
| Seagate ST3500418AS 500GB           | 9         | 18     | 0.69%   |
| Seagate ST3500413AS 500GB           | 9         | 23     | 0.69%   |
| Seagate ST9500420AS 500GB           | 8         | 11     | 0.62%   |
| Seagate ST500LT012-1DG142 500GB     | 8         | 9      | 0.62%   |
| Apacer 16GB SATA Flash Drive        | 8         | 10     | 0.62%   |
| Seagate ST9500325AS 500GB           | 7         | 8      | 0.54%   |
| Seagate ST320LT007-9ZV142 320GB     | 7         | 7      | 0.54%   |
| Samsung Electronics HD501LJ 500GB   | 7         | 9      | 0.54%   |
| Kingston SV300S37A60G 64GB          | 7         | 9      | 0.54%   |
| Kingston SMS200S3120G 120GB         | 7         | 8      | 0.54%   |
| Intel SSDSA2M080G2GC 80GB           | 7         | 8      | 0.54%   |
| WDC WD30EFRX-68EUZN0 3TB            | 6         | 18     | 0.46%   |
| WDC WD20EFRX-68EUZN0 2TB            | 6         | 14     | 0.46%   |
| Toshiba MQ01ABF050 500GB            | 6         | 8      | 0.46%   |
| Seagate ST9320423AS 320GB           | 6         | 6      | 0.46%   |
| Seagate ST9320325AS 320GB           | 6         | 6      | 0.46%   |
| Seagate ST3160815AS 160GB           | 6         | 7      | 0.46%   |
| Intel SSDSA2M160G2GC 160GB          | 6         | 8      | 0.46%   |
| Hitachi HTS541612J9SA00 120GB       | 6         | 7      | 0.46%   |
| Crucial CT525MX300SSD1 528GB        | 6         | 10     | 0.46%   |
| Crucial CT275MX300SSD1 275GB        | 6         | 9      | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB        | 5         | 5      | 0.39%   |
| WDC WD40EFRX-68WT0N0 4TB            | 5         | 13     | 0.39%   |
| Toshiba MQ01ABD075 752GB            | 5         | 5      | 0.39%   |
| Seagate ST380815AS 80GB             | 5         | 5      | 0.39%   |
| Seagate ST31000528AS 1TB            | 5         | 6      | 0.39%   |
| Seagate ST2000DL003-9VT166 2TB      | 5         | 16     | 0.39%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 6      | 0.39%   |
| Samsung Electronics SSD 870 EVO 1TB | 5         | 9      | 0.39%   |
| Samsung Electronics HM160HI 160GB   | 5         | 5      | 0.39%   |
| Samsung Electronics HD161HJ 160GB   | 5         | 5      | 0.39%   |
| Kingston SMS200S360G 64GB           | 5         | 5      | 0.39%   |
| HGST HTS721010A9E630 1TB            | 5         | 14     | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 294       | 430    | 23.54%  |
| WDC                 | 236       | 362    | 18.9%   |
| Hitachi             | 101       | 140    | 8.09%   |
| Samsung Electronics | 100       | 133    | 8.01%   |
| Toshiba             | 88        | 131    | 7.05%   |
| Intel               | 73        | 99     | 5.84%   |
| Kingston            | 65        | 81     | 5.2%    |
| HGST                | 39        | 63     | 3.12%   |
| Crucial             | 37        | 55     | 2.96%   |
| SanDisk             | 29        | 44     | 2.32%   |
| OCZ                 | 16        | 19     | 1.28%   |
| Micron Technology   | 16        | 22     | 1.28%   |
| A-DATA Technology   | 16        | 24     | 1.28%   |
| Apacer              | 13        | 15     | 1.04%   |
| Maxtor              | 11        | 15     | 0.88%   |
| SK hynix            | 10        | 13     | 0.8%    |
| Corsair             | 9         | 14     | 0.72%   |
| China               | 8         | 9      | 0.64%   |
| LITEON              | 6         | 7      | 0.48%   |
| Hewlett-Packard     | 6         | 12     | 0.48%   |
| Fujitsu             | 6         | 9      | 0.48%   |
| Apple               | 6         | 6      | 0.48%   |
| Dogfish             | 5         | 11     | 0.4%    |
| Transcend           | 4         | 8      | 0.32%   |
| VisionTek           | 3         | 7      | 0.24%   |
| SPCC                | 3         | 5      | 0.24%   |
| Phison              | 3         | 3      | 0.24%   |
| Intenso             | 3         | 3      | 0.24%   |
| BIWIN               | 3         | 5      | 0.24%   |
| SSSTC               | 2         | 2      | 0.16%   |
| SMI                 | 2         | 2      | 0.16%   |
| Plextor             | 2         | 2      | 0.16%   |
| MyDigitalSSD        | 2         | 4      | 0.16%   |
| KingSpec            | 2         | 2      | 0.16%   |
| KingDian            | 2         | 2      | 0.16%   |
| HP Phison           | 2         | 2      | 0.16%   |
| ZTC                 | 1         | 3      | 0.08%   |
| XrayDisk            | 1         | 1      | 0.08%   |
| XPG                 | 1         | 1      | 0.08%   |
| Wintec              | 1         | 1      | 0.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 293       | 429    | 35.43%  |
| WDC                  | 225       | 349    | 27.21%  |
| Hitachi              | 101       | 140    | 12.21%  |
| Toshiba              | 81        | 120    | 9.79%   |
| Samsung Electronics  | 55        | 70     | 6.65%   |
| HGST                 | 39        | 63     | 4.72%   |
| Maxtor               | 11        | 15     | 1.33%   |
| Fujitsu              | 6         | 9      | 0.73%   |
| Hewlett-Packard      | 5         | 10     | 0.6%    |
| Apple                | 4         | 4      | 0.48%   |
| WD MediaMax          | 1         | 3      | 0.12%   |
| InnoLite             | 1         | 1      | 0.12%   |
| IBM/Hitachi          | 1         | 1      | 0.12%   |
| HPE                  | 1         | 3      | 0.12%   |
| ExcelStor Technology | 1         | 2      | 0.12%   |
| China                | 1         | 1      | 0.12%   |
| Cactus               | 1         | 1      | 0.12%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 778       | 1221   | 64.94%  |
| SSD  | 409       | 560    | 34.14%  |
| NVMe | 11        | 14     | 0.92%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZYLN256HCHP-000L2 256GB | 2         | 2      | 9.52%   |
| WDC WD6400AARS-00Y5B1 640GB                  | 1         | 2      | 4.76%   |
| WDC WD3200AAJS-00YZCA0 320GB                 | 1         | 1      | 4.76%   |
| WDC WD20EARS-00MVWB0 2TB                     | 1         | 1      | 4.76%   |
| WDC WD10SPZX-00Z10T0 1TB                     | 1         | 1      | 4.76%   |
| Toshiba MG05ACA800E 8TB                      | 1         | 1      | 4.76%   |
| Seagate ST4000NM0025 4TB                     | 1         | 2      | 4.76%   |
| SanDisk pSSD 256GB                           | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 960 EVO 250GB        | 1         | 1      | 4.76%   |
| Samsung Electronics HM250JI 250GB            | 1         | 1      | 4.76%   |
| Samsung Electronics HD204UI 2TB              | 1         | 2      | 4.76%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB   | 1         | 1      | 4.76%   |
| Maxtor 6E040L0 41GB                          | 1         | 1      | 4.76%   |
| Kingston SV300S37A60G 64GB                   | 1         | 1      | 4.76%   |
| Intel SSDSC2BW120H6 120GB                    | 1         | 1      | 4.76%   |
| HPE MK000480GWUGF 480GB                      | 1         | 1      | 4.76%   |
| Hitachi HUS724040ALE641 4TB                  | 1         | 14     | 4.76%   |
| Hitachi HTS545025B9A300 250GB                | 1         | 1      | 4.76%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 4.76%   |
| Crucial M4-CT256M4SSD1 256GB                 | 1         | 1      | 4.76%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 23.81%  |
| WDC                 | 4         | 5      | 19.05%  |
| Hitachi             | 2         | 15     | 9.52%   |
| Toshiba             | 1         | 1      | 4.76%   |
| Seagate             | 1         | 2      | 4.76%   |
| SanDisk             | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| Maxtor              | 1         | 1      | 4.76%   |
| Kingston            | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |
| HPE                 | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |
| Crucial             | 1         | 1      | 4.76%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 6292      | 13241  | 80.67%  |
| Malfunc  | 1170      | 1795   | 15%     |
| Detected | 317       | 666    | 4.06%   |
| Failed   | 21        | 37     | 0.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5892      | 62.92%  |
| AMD                              | 1318      | 14.08%  |
| Samsung Electronics              | 466       | 4.98%   |
| Broadcom / LSI                   | 314       | 3.35%   |
| SanDisk                          | 180       | 1.92%   |
| ASMedia Technology               | 151       | 1.61%   |
| Marvell Technology Group         | 105       | 1.12%   |
| Phison Electronics               | 90        | 0.96%   |
| Nvidia                           | 80        | 0.85%   |
| Kingston Technology Company      | 80        | 0.85%   |
| Silicon Motion                   | 71        | 0.76%   |
| Hewlett-Packard                  | 68        | 0.73%   |
| SK hynix                         | 57        | 0.61%   |
| Micron/Crucial Technology        | 55        | 0.59%   |
| JMicron Technology               | 50        | 0.53%   |
| Toshiba                          | 37        | 0.4%    |
| KIOXIA                           | 32        | 0.34%   |
| ADATA Technology                 | 32        | 0.34%   |
| Chelsio Communications           | 29        | 0.31%   |
| Adaptec                          | 28        | 0.3%    |
| Micron Technology                | 27        | 0.29%   |
| Silicon Image                    | 22        | 0.23%   |
| Unknown                          | 21        | 0.22%   |
| VIA Technologies                 | 20        | 0.21%   |
| Seagate Technology               | 14        | 0.15%   |
| Realtek Semiconductor            | 13        | 0.14%   |
| Shenzhen Longsys Electronics     | 11        | 0.12%   |
| Silicon Integrated Systems [SiS] | 10        | 0.11%   |
| Areca Technology                 | 8         | 0.09%   |
| Union Memory (Shenzhen)          | 7         | 0.07%   |
| Solid State Storage Technology   | 7         | 0.07%   |
| Lite-On Technology               | 7         | 0.07%   |
| Lenovo                           | 7         | 0.07%   |
| Integrated Technology Express    | 6         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.05%   |
| Dell                             | 5         | 0.05%   |
| Biwin Storage Technology         | 5         | 0.05%   |
| ATP ELECTRONICS                  | 5         | 0.05%   |
| 3ware                            | 5         | 0.05%   |
| ULi Electronics                  | 4         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 881       | 8.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 533       | 4.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 449       | 4.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 313       | 2.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 280       | 2.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 279       | 2.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 276       | 2.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 270       | 2.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 243       | 2.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 224       | 2.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 192       | 1.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 179       | 1.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 178       | 1.66%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 170       | 1.58%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 166       | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 163       | 1.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 160       | 1.49%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 149       | 1.39%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 142       | 1.32%   |
| Unknown                                                                          | 134       | 1.25%   |
| AMD 400 Series Chipset SATA Controller                                           | 133       | 1.24%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 131       | 1.22%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 124       | 1.16%   |
| AMD FCH SATA Controller [IDE mode]                                               | 118       | 1.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 116       | 1.08%   |
| Intel SATA Controller [RAID mode]                                                | 112       | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 99        | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 98        | 0.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 93        | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 86        | 0.8%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 86        | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                            | 84        | 0.78%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 83        | 0.77%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 81        | 0.75%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 79        | 0.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 76        | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 75        | 0.7%    |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 69        | 0.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 65        | 0.61%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 65        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 6306      | 66.46%  |
| NVMe | 1225      | 12.91%  |
| IDE  | 1160      | 12.23%  |
| RAID | 560       | 5.9%    |
| SAS  | 155       | 1.63%   |
| SCSI | 82        | 0.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 6244      | 79.84%  |
| AMD                | 1443      | 18.45%  |
| ARM                | 93        | 1.19%   |
| Unknown            | 24        | 0.31%   |
| PowerPC            | 4         | 0.05%   |
| VIA                | 2         | 0.03%   |
| Rockchip           | 2         | 0.03%   |
| Sun                | 1         | 0.01%   |
| Research           | 1         | 0.01%   |
| Motorola           | 1         | 0.01%   |
| IBM                | 1         | 0.01%   |
| i                  | 1         | 0.01%   |
| Broadcom           | 1         | 0.01%   |
| Baikal Electronics | 1         | 0.01%   |
| 123456789ABC       | 1         | 0.01%   |
| 11th               | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                         | 236       | 2.99%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 146       | 1.85%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 143       | 1.81%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 140       | 1.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 81        | 1.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 59        | 0.75%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 59        | 0.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 58        | 0.73%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 56        | 0.71%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 53        | 0.67%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 52        | 0.66%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 47        | 0.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz        | 45        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 45        | 0.57%   |
| Intel Celeron N5105 @ 2.00GHz            | 44        | 0.56%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 43        | 0.54%   |
| Intel Atom CPU D525 @ 1.80GHz            | 43        | 0.54%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 41        | 0.52%   |
| Intel Core 2 Duo                         | 41        | 0.52%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 39        | 0.49%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 39        | 0.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 39        | 0.49%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 39        | 0.49%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 38        | 0.48%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 37        | 0.47%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 37        | 0.47%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 36        | 0.46%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 36        | 0.46%   |
| Intel CPU Version                        | 35        | 0.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 33        | 0.42%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 33        | 0.42%   |
| ARM Cortex-A72 r0p3                      | 33        | 0.42%   |
| Intel Xeon                               | 32        | 0.41%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 32        | 0.41%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 31        | 0.39%   |
| AMD G-T40E Processor                     | 31        | 0.39%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 30        | 0.38%   |
| ARM Cortex-A53 r0p4                      | 30        | 0.38%   |
| AMD Ryzen 5 3600 6-Core Processor        | 30        | 0.38%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 29        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1508      | 19.19%  |
| Intel Celeron           | 1091      | 13.88%  |
| Intel Xeon              | 872       | 11.1%   |
| Intel Core i7           | 862       | 10.97%  |
| Intel Core i3           | 604       | 7.69%   |
| Intel Atom              | 369       | 4.7%    |
| AMD GX                  | 359       | 4.57%   |
| Other                   | 245       | 3.12%   |
| Intel Core 2 Duo        | 231       | 2.94%   |
| Intel Pentium           | 203       | 2.58%   |
| AMD Ryzen 5             | 183       | 2.33%   |
| AMD Ryzen 7             | 168       | 2.14%   |
| ARM Cortex              | 85        | 1.08%   |
| AMD FX                  | 80        | 1.02%   |
| AMD Ryzen 3             | 56        | 0.71%   |
| AMD G                   | 56        | 0.71%   |
| Intel Core 2 Quad       | 54        | 0.69%   |
| Intel Pentium Dual-Core | 49        | 0.62%   |
| Intel Pentium Silver    | 46        | 0.59%   |
| AMD Ryzen 9             | 46        | 0.59%   |
| AMD EPYC                | 39        | 0.5%    |
| Intel Core 2            | 33        | 0.42%   |
| Intel Pentium 4         | 27        | 0.34%   |
| AMD Athlon              | 27        | 0.34%   |
| AMD Ryzen Embedded      | 26        | 0.33%   |
| Intel Genuine           | 25        | 0.32%   |
| Intel Xeon Silver       | 24        | 0.31%   |
| AMD Ryzen 5 PRO         | 24        | 0.31%   |
| AMD A6                  | 24        | 0.31%   |
| AMD A4                  | 24        | 0.31%   |
| Intel Pentium Gold      | 22        | 0.28%   |
| AMD A10                 | 21        | 0.27%   |
| Intel Core i9           | 20        | 0.25%   |
| AMD Phenom II X4        | 20        | 0.25%   |
| AMD Opteron             | 20        | 0.25%   |
| AMD E                   | 20        | 0.25%   |
| AMD Athlon 64 X2        | 20        | 0.25%   |
| AMD A8                  | 19        | 0.24%   |
| Intel Pentium M         | 18        | 0.23%   |
| Intel Pentium Dual      | 18        | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 3477      | 44.24%  |
| 2       | 2448      | 31.15%  |
| Unknown | 477       | 6.07%   |
| 8       | 456       | 5.8%    |
| 6       | 333       | 4.24%   |
| 16      | 206       | 2.62%   |
| 12      | 205       | 2.61%   |
| 1       | 127       | 1.62%   |
| 24      | 42        | 0.53%   |
| 32      | 21        | 0.27%   |
| 10      | 20        | 0.25%   |
| 20      | 15        | 0.19%   |
| 64      | 7         | 0.09%   |
| 3       | 7         | 0.09%   |
| 48      | 4         | 0.05%   |
| 28      | 4         | 0.05%   |
| 14      | 4         | 0.05%   |
| 36      | 3         | 0.04%   |
| 128     | 2         | 0.03%   |
| 40      | 1         | 0.01%   |
| 11      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7292      | 93.16%  |
| 2       | 312       | 3.99%   |
| Unknown | 218       | 2.79%   |
| 4       | 4         | 0.05%   |
| 8       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4097      | 52.28%  |
| 2       | 3206      | 40.91%  |
| Unknown | 533       | 6.8%    |
| 4       | 1         | 0.01%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 998       | 12.71%  |
| Haswell         | 825       | 10.5%   |
| Silvermont      | 640       | 8.15%   |
| IvyBridge       | 608       | 7.74%   |
| SandyBridge     | 523       | 6.66%   |
| Skylake         | 468       | 5.96%   |
| Penryn          | 323       | 4.11%   |
| Puma            | 287       | 3.65%   |
| Goldmont plus   | 285       | 3.63%   |
| Unknown         | 284       | 3.62%   |
| Broadwell       | 273       | 3.48%   |
| Goldmont        | 230       | 2.93%   |
| Westmere        | 224       | 2.85%   |
| Zen 2           | 184       | 2.34%   |
| Core            | 184       | 2.34%   |
| Bonnell         | 168       | 2.14%   |
| Zen             | 156       | 1.99%   |
| Zen+            | 149       | 1.9%    |
| Jaguar          | 128       | 1.63%   |
| CometLake       | 125       | 1.59%   |
| Nehalem         | 122       | 1.55%   |
| Piledriver      | 103       | 1.31%   |
| Bobcat          | 93        | 1.18%   |
| Zen 3           | 83        | 1.06%   |
| K10             | 83        | 1.06%   |
| Steamroller     | 49        | 0.62%   |
| NetBurst        | 46        | 0.59%   |
| TigerLake       | 45        | 0.57%   |
| Excavator       | 39        | 0.5%    |
| K8 Hammer       | 36        | 0.46%   |
| P6              | 35        | 0.45%   |
| IceLake         | 26        | 0.33%   |
| Bulldozer       | 14        | 0.18%   |
| K10 Llano       | 10        | 0.13%   |
| Geode           | 4         | 0.05%   |
| K8 & K10 hybrid | 3         | 0.04%   |
| K6              | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4608      | 59.71%  |
| AMD                                          | 1197      | 15.51%  |
| Nvidia                                       | 1036      | 13.42%  |
| Matrox Electronics Systems                   | 466       | 6.04%   |
| ASPEED Technology                            | 377       | 4.89%   |
| XGI Technology (eXtreme Graphics Innovation) | 8         | 0.1%    |
| Silicon Integrated Systems [SiS]             | 6         | 0.08%   |
| VIA Technologies                             | 5         | 0.06%   |
| S3 Graphics                                  | 4         | 0.05%   |
| Silicon Motion                               | 2         | 0.03%   |
| Cirrus Logic                                 | 2         | 0.03%   |
| Tseng Labs                                   | 1         | 0.01%   |
| Trident Microsystems                         | 1         | 0.01%   |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.01%   |
| Huawei Technologies                          | 1         | 0.01%   |
| ATI                                          | 1         | 0.01%   |
| 3DLabs                                       | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 377       | 4.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 328       | 4.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 297       | 3.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 287       | 3.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 276       | 3.51%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 245       | 3.11%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 208       | 2.64%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 201       | 2.55%   |
| Intel HD Graphics 620                                                                    | 199       | 2.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 179       | 2.28%   |
| Intel HD Graphics 530                                                                    | 172       | 2.19%   |
| Intel HD Graphics 500                                                                    | 149       | 1.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 148       | 1.88%   |
| Intel HD Graphics 5500                                                                   | 134       | 1.7%    |
| Intel UHD Graphics 620                                                                   | 130       | 1.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 120       | 1.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 120       | 1.53%   |
| Matrox Electronics Systems G200eR2                                                       | 99        | 1.26%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 99        | 1.26%   |
| Intel HD Graphics 630                                                                    | 89        | 1.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 86        | 1.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 83        | 1.05%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 81        | 1.03%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 77        | 0.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 77        | 0.98%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 76        | 0.97%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 73        | 0.93%   |
| AMD ES1000                                                                               | 72        | 0.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 68        | 0.86%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 65        | 0.83%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 65        | 0.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 64        | 0.81%   |
| Matrox Electronics Systems MGA G200EH                                                    | 60        | 0.76%   |
| AMD Renoir                                                                               | 60        | 0.76%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 59        | 0.75%   |
| Intel JasperLake [UHD Graphics]                                                          | 54        | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 53        | 0.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 48        | 0.61%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 47        | 0.6%    |
| AMD Kabini [Radeon HD 8400E]                                                             | 47        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 3947      | 50.27%  |
| 1 x AMD                                  | 1067      | 13.59%  |
| 1 x Nvidia                               | 715       | 9.11%   |
| Other                                    | 544       | 6.93%   |
| 1 x Matrox                               | 462       | 5.88%   |
| 1 x ASPEED                               | 349       | 4.44%   |
| 2 x Intel                                | 289       | 3.68%   |
| Intel + Nvidia                           | 278       | 3.54%   |
| Intel + AMD                              | 76        | 0.97%   |
| 2 x AMD                                  | 27        | 0.34%   |
| AMD + Nvidia                             | 25        | 0.32%   |
| Intel + ASPEED                           | 17        | 0.22%   |
| 2 x Nvidia                               | 9         | 0.11%   |
| 1 x XGI                                  | 8         | 0.1%    |
| Nvidia + ASPEED                          | 8         | 0.1%    |
| 1 x SiS                                  | 6         | 0.08%   |
| 1 x VIA                                  | 5         | 0.06%   |
| 1 x S3 Graphics                          | 4         | 0.05%   |
| AMD + ASPEED                             | 3         | 0.04%   |
| 1 x Silicon Motion                       | 2         | 0.03%   |
| 1 x Cirrus Logic                         | 2         | 0.03%   |
| 2 x Intel + 1 x Nvidia                   | 1         | 0.01%   |
| 1 x Tseng Labs                           | 1         | 0.01%   |
| 1 x Trident Microsystems                 | 1         | 0.01%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.01%   |
| Nvidia + Matrox                          | 1         | 0.01%   |
| Nvidia + Huawei Technologies             | 1         | 0.01%   |
| Intel + Matrox                           | 1         | 0.01%   |
| AMD + Matrox                             | 1         | 0.01%   |
| 1 x 3DLabs                               | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 6657      | 84.76%  |
| Unknown     | 670       | 8.53%   |
| Proprietary | 527       | 6.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6985      | 88.66%  |
| 1.01-2.0   | 253       | 3.21%   |
| 0.01-0.5   | 185       | 2.35%   |
| 0.51-1.0   | 147       | 1.87%   |
| 3.01-4.0   | 134       | 1.7%    |
| 7.01-8.0   | 89        | 1.13%   |
| 5.01-6.0   | 51        | 0.65%   |
| 2.01-3.0   | 19        | 0.24%   |
| 8.01-16.0  | 14        | 0.18%   |
| 4.01-5.0   | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 297       | 11.3%   |
| LG Display              | 297       | 11.3%   |
| AU Optronics            | 289       | 11%     |
| Dell                    | 183       | 6.96%   |
| Chimei Innolux          | 180       | 6.85%   |
| BOE                     | 159       | 6.05%   |
| Goldstar                | 149       | 5.67%   |
| Lenovo                  | 121       | 4.6%    |
| Acer                    | 83        | 3.16%   |
| Hewlett-Packard         | 82        | 3.12%   |
| BenQ                    | 67        | 2.55%   |
| Philips                 | 65        | 2.47%   |
| Apple                   | 65        | 2.47%   |
| AOC                     | 65        | 2.47%   |
| Ancor Communications    | 57        | 2.17%   |
| Sharp                   | 33        | 1.26%   |
| Iiyama                  | 33        | 1.26%   |
| ViewSonic               | 32        | 1.22%   |
| Chi Mei Optoelectronics | 30        | 1.14%   |
| InfoVision              | 22        | 0.84%   |
| Sony                    | 20        | 0.76%   |
| LG Electronics          | 20        | 0.76%   |
| ASUSTek Computer        | 19        | 0.72%   |
| NEC Computers           | 17        | 0.65%   |
| Eizo                    | 16        | 0.61%   |
| PANDA                   | 14        | 0.53%   |
| Fujitsu Siemens         | 14        | 0.53%   |
| LG Philips              | 12        | 0.46%   |
| HannStar                | 12        | 0.46%   |
| Toshiba                 | 11        | 0.42%   |
| Vizio                   | 9         | 0.34%   |
| Panasonic               | 9         | 0.34%   |
| Unknown                 | 8         | 0.3%    |
| Sceptre Tech            | 8         | 0.3%    |
| MSI                     | 7         | 0.27%   |
| LGD                     | 7         | 0.27%   |
| CSO                     | 6         | 0.23%   |
| CPT                     | 6         | 0.23%   |
| JDI                     | 5         | 0.19%   |
| Idek Iiyama             | 5         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 21        | 0.78%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 14        | 0.52%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 11        | 0.41%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 11        | 0.41%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 10        | 0.37%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch              | 9         | 0.33%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch              | 9         | 0.33%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 9         | 0.33%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 8         | 0.3%    |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 8         | 0.3%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 8         | 0.3%    |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch              | 8         | 0.3%    |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch              | 8         | 0.3%    |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 8         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 8         | 0.3%    |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 8         | 0.3%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 8         | 0.3%    |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 8         | 0.3%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 300x170mm 13.6-inch | 7         | 0.26%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                | 7         | 0.26%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 7         | 0.26%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 7         | 0.26%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch              | 7         | 0.26%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 7         | 0.26%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch              | 7         | 0.26%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 7         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch     | 7         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 7         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch      | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch        | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 7         | 0.26%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 6         | 0.22%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 6         | 0.22%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch              | 6         | 0.22%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 6         | 0.22%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch       | 6         | 0.22%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 5         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 999       | 38.69%  |
| 1366x768 (WXGA)    | 529       | 20.49%  |
| 3840x2160 (4K)     | 138       | 5.34%   |
| 2560x1440 (QHD)    | 132       | 5.11%   |
| 1600x900 (HD+)     | 125       | 4.84%   |
| 1280x1024 (SXGA)   | 107       | 4.14%   |
| 1280x800 (WXGA)    | 99        | 3.83%   |
| 1920x1200 (WUXGA)  | 75        | 2.9%    |
| 1440x900 (WXGA+)   | 67        | 2.59%   |
| 1680x1050 (WSXGA+) | 66        | 2.56%   |
| 3440x1440          | 28        | 1.08%   |
| 2560x1080          | 28        | 1.08%   |
| 1024x600           | 25        | 0.97%   |
| Unknown            | 24        | 0.93%   |
| 1024x768 (XGA)     | 15        | 0.58%   |
| 1360x768           | 13        | 0.5%    |
| 1920x540           | 11        | 0.43%   |
| 3200x1800 (QHD+)   | 10        | 0.39%   |
| 1600x1200          | 10        | 0.39%   |
| 2560x1600          | 8         | 0.31%   |
| 2880x1620          | 7         | 0.27%   |
| 2256x1504          | 7         | 0.27%   |
| 3840x1080          | 6         | 0.23%   |
| 2880x1800          | 4         | 0.15%   |
| 3840x1600          | 3         | 0.12%   |
| 3840x1200          | 3         | 0.12%   |
| 3000x2000          | 3         | 0.12%   |
| 2048x1152          | 3         | 0.12%   |
| 1400x1050          | 3         | 0.12%   |
| 5760x2160          | 2         | 0.08%   |
| 2736x1824          | 2         | 0.08%   |
| 2160x1440          | 2         | 0.08%   |
| 1280x720 (HD)      | 2         | 0.08%   |
| 7680x2160          | 1         | 0.04%   |
| 720x1280           | 1         | 0.04%   |
| 5760x1256          | 1         | 0.04%   |
| 5760x1200          | 1         | 0.04%   |
| 5760x1080          | 1         | 0.04%   |
| 5120x1440          | 1         | 0.04%   |
| 4480x1080          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 507       | 19.3%   |
| 13      | 467       | 17.78%  |
| 24      | 210       | 7.99%   |
| 27      | 185       | 7.04%   |
| 21      | 164       | 6.24%   |
| 12      | 149       | 5.67%   |
| 23      | 142       | 5.41%   |
| Unknown | 136       | 5.18%   |
| 19      | 121       | 4.61%   |
| 17      | 106       | 4.04%   |
| 14      | 58        | 2.21%   |
| 31      | 55        | 2.09%   |
| 11      | 49        | 1.87%   |
| 18      | 45        | 1.71%   |
| 22      | 37        | 1.41%   |
| 34      | 36        | 1.37%   |
| 20      | 27        | 1.03%   |
| 10      | 25        | 0.95%   |
| 40      | 9         | 0.34%   |
| 29      | 9         | 0.34%   |
| 54      | 7         | 0.27%   |
| 42      | 7         | 0.27%   |
| 16      | 7         | 0.27%   |
| 64      | 6         | 0.23%   |
| 9       | 6         | 0.23%   |
| 39      | 5         | 0.19%   |
| 25      | 5         | 0.19%   |
| 52      | 4         | 0.15%   |
| 32      | 4         | 0.15%   |
| 28      | 4         | 0.15%   |
| 26      | 4         | 0.15%   |
| 50      | 3         | 0.11%   |
| 49      | 3         | 0.11%   |
| 41      | 3         | 0.11%   |
| 37      | 3         | 0.11%   |
| 33      | 3         | 0.11%   |
| 48      | 2         | 0.08%   |
| 46      | 2         | 0.08%   |
| 43      | 2         | 0.08%   |
| 35      | 2         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 887       | 34.18%  |
| 501-600     | 503       | 19.38%  |
| 201-300     | 419       | 16.15%  |
| 401-500     | 331       | 12.76%  |
| Unknown     | 136       | 5.24%   |
| 351-400     | 117       | 4.51%   |
| 601-700     | 91        | 3.51%   |
| 701-800     | 44        | 1.7%    |
| 1001-1500   | 32        | 1.23%   |
| 801-900     | 18        | 0.69%   |
| 901-1000    | 12        | 0.46%   |
| 101-200     | 5         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1824      | 74.06%  |
| 16/10   | 301       | 12.22%  |
| Unknown | 111       | 4.51%   |
| 5/4     | 95        | 3.86%   |
| 21/9    | 52        | 2.11%   |
| 3/2     | 37        | 1.5%    |
| 4/3     | 32        | 1.3%    |
| 32/9    | 4         | 0.16%   |
| 6/5     | 3         | 0.12%   |
| 3.18    | 1         | 0.04%   |
| 11/10   | 1         | 0.04%   |
| 1.96    | 1         | 0.04%   |
| 1.00    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 466       | 17.86%  |
| 81-90          | 427       | 16.37%  |
| 91-100         | 392       | 15.02%  |
| 301-350        | 193       | 7.4%    |
| 151-200        | 161       | 6.17%   |
| 61-70          | 150       | 5.75%   |
| Unknown        | 136       | 5.21%   |
| 101-110        | 125       | 4.79%   |
| 351-500        | 105       | 4.02%   |
| 71-80          | 84        | 3.22%   |
| 141-150        | 84        | 3.22%   |
| 251-300        | 73        | 2.8%    |
| 121-130        | 56        | 2.15%   |
| 51-60          | 48        | 1.84%   |
| 501-1000       | 36        | 1.38%   |
| 41-50          | 27        | 1.03%   |
| More than 1000 | 25        | 0.96%   |
| 131-140        | 8         | 0.31%   |
| 111-120        | 8         | 0.31%   |
| 1-40           | 5         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 828       | 32.22%  |
| 101-120       | 689       | 26.81%  |
| 121-160       | 673       | 26.19%  |
| 161-240       | 183       | 7.12%   |
| Unknown       | 136       | 5.29%   |
| More than 240 | 41        | 1.6%    |
| 1-50          | 20        | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5368      | 67.95%  |
| 1     | 2251      | 28.49%  |
| 2     | 261       | 3.3%    |
| 3     | 19        | 0.24%   |
| 4     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 5535      | 50.63%  |
| Realtek Semiconductor             | 2803      | 25.64%  |
| Broadcom                          | 832       | 7.61%   |
| Qualcomm Atheros                  | 702       | 6.42%   |
| Marvell Technology Group          | 87        | 0.8%    |
| Ralink Technology                 | 78        | 0.71%   |
| TP-Link                           | 52        | 0.48%   |
| IMC Networks                      | 51        | 0.47%   |
| Ralink                            | 50        | 0.46%   |
| Mellanox Technologies             | 50        | 0.46%   |
| AMD                               | 41        | 0.38%   |
| Nvidia                            | 39        | 0.36%   |
| Chelsio Communications            | 39        | 0.36%   |
| D-Link System                     | 35        | 0.32%   |
| Edimax Technology                 | 32        | 0.29%   |
| Ericsson Business Mobile Networks | 27        | 0.25%   |
| MediaTek                          | 20        | 0.18%   |
| VIA Technologies                  | 19        | 0.17%   |
| U-Blox                            | 18        | 0.16%   |
| Sierra Wireless                   | 18        | 0.16%   |
| Qualcomm Atheros Communications   | 18        | 0.16%   |
| Huawei Technologies               | 18        | 0.16%   |
| Aquantia                          | 18        | 0.16%   |
| Xiaomi                            | 17        | 0.16%   |
| Samsung Electronics               | 17        | 0.16%   |
| American Megatrends               | 15        | 0.14%   |
| Solarflare Communications         | 13        | 0.12%   |
| Emulex                            | 13        | 0.12%   |
| ASUSTek Computer                  | 13        | 0.12%   |
| Apple                             | 13        | 0.12%   |
| IBM                               | 12        | 0.11%   |
| 3Com                              | 12        | 0.11%   |
| QLogic                            | 11        | 0.1%    |
| Hewlett-Packard                   | 11        | 0.1%    |
| Dell                              | 11        | 0.1%    |
| JMicron Technology                | 10        | 0.09%   |
| Google                            | 10        | 0.09%   |
| D-Link                            | 9         | 0.08%   |
| Qualcomm                          | 8         | 0.07%   |
| NetGear                           | 8         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 2284      | 16.87%  |
| Intel I211 Gigabit Network Connection                                         | 953       | 7.04%   |
| Intel I210 Gigabit Network Connection                                         | 661       | 4.88%   |
| Intel I350 Gigabit Network Connection                                         | 417       | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 405       | 2.99%   |
| Intel 82574L Gigabit Network Connection                                       | 362       | 2.67%   |
| Intel Ethernet Connection I217-LM                                             | 215       | 1.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 193       | 1.43%   |
| Intel 82583V Gigabit Network Connection                                       | 171       | 1.26%   |
| Intel 82576 Gigabit Network Connection                                        | 169       | 1.25%   |
| Intel Wi-Fi 6 AX200                                                           | 163       | 1.2%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 149       | 1.1%    |
| Intel Wireless 8265 / 8275                                                    | 148       | 1.09%   |
| Intel 82580 Gigabit Network Connection                                        | 147       | 1.09%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 147       | 1.09%   |
| Intel Wireless 7265                                                           | 143       | 1.06%   |
| Intel Ethernet Controller I225-V                                              | 130       | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 129       | 0.95%   |
| Intel Wireless 7260                                                           | 124       | 0.92%   |
| Realtek RTL8125 2.5GbE Controller                                             | 123       | 0.91%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 119       | 0.88%   |
| Intel Wireless 8260                                                           | 108       | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                         | 108       | 0.8%    |
| Intel Wireless 3165                                                           | 107       | 0.79%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 99        | 0.73%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 96        | 0.71%   |
| Intel Ethernet Connection (2) I219-V                                          | 86        | 0.64%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 84        | 0.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 82        | 0.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 80        | 0.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 76        | 0.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 70        | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 69        | 0.51%   |
| Intel Ethernet Connection I354                                                | 68        | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 67        | 0.49%   |
| Intel Ethernet Connection I219-LM                                             | 66        | 0.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 65        | 0.48%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 65        | 0.48%   |
| Intel 82579V Gigabit Network Connection                                       | 62        | 0.46%   |
| Intel Ethernet Connection (7) I219-V                                          | 59        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1683      | 51.34%  |
| Qualcomm Atheros                      | 572       | 17.45%  |
| Realtek Semiconductor                 | 393       | 11.99%  |
| Broadcom                              | 253       | 7.72%   |
| Ralink Technology                     | 78        | 2.38%   |
| TP-Link                               | 52        | 1.59%   |
| IMC Networks                          | 51        | 1.56%   |
| Ralink                                | 50        | 1.53%   |
| Edimax Technology                     | 32        | 0.98%   |
| Qualcomm Atheros Communications       | 18        | 0.55%   |
| Sierra Wireless                       | 16        | 0.49%   |
| MediaTek                              | 16        | 0.49%   |
| ASUSTek Computer                      | 13        | 0.4%    |
| D-Link                                | 9         | 0.27%   |
| NetGear                               | 8         | 0.24%   |
| D-Link System                         | 7         | 0.21%   |
| Dell                                  | 6         | 0.18%   |
| Mercucys                              | 3         | 0.09%   |
| Atheros                               | 3         | 0.09%   |
| AboCom Systems                        | 3         | 0.09%   |
| Belkin Components                     | 2         | 0.06%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Sagem                                 | 1         | 0.03%   |
| Qcom                                  | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| Marvell Technology Group              | 1         | 0.03%   |
| Linksys                               | 1         | 0.03%   |
| Gemtek                                | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 163       | 4.93%   |
| Intel Wireless 8265 / 8275                                              | 148       | 4.47%   |
| Intel Wireless 7265                                                     | 143       | 4.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 129       | 3.9%    |
| Intel Wireless 7260                                                     | 124       | 3.75%   |
| Intel Wireless 8260                                                     | 108       | 3.26%   |
| Intel Wireless 3165                                                     | 107       | 3.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 82        | 2.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 80        | 2.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 76        | 2.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 70        | 2.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 69        | 2.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 67        | 2.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 65        | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 56        | 1.69%   |
| Intel Wireless-AC 9260                                                  | 53        | 1.6%    |
| Intel Wireless 3160                                                     | 52        | 1.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 49        | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 48        | 1.45%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 47        | 1.42%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 47        | 1.42%   |
| Ralink RT5370 Wireless Adapter                                          | 38        | 1.15%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 37        | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 37        | 1.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 34        | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 33        | 1%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 32        | 0.97%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 31        | 0.94%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 31        | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 30        | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 30        | 0.91%   |
| Intel Centrino Advanced-N 6200                                          | 30        | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 29        | 0.88%   |
| Intel Centrino Advanced-N 6235                                          | 29        | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 28        | 0.85%   |
| Intel Centrino Ultimate-N 6300                                          | 28        | 0.85%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 28        | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 27        | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 27        | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 26        | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4712      | 54.48%  |
| Realtek Semiconductor            | 2631      | 30.42%  |
| Broadcom                         | 642       | 7.42%   |
| Qualcomm Atheros                 | 189       | 2.19%   |
| Marvell Technology Group         | 86        | 0.99%   |
| AMD                              | 41        | 0.47%   |
| Nvidia                           | 39        | 0.45%   |
| Chelsio Communications           | 29        | 0.34%   |
| D-Link System                    | 25        | 0.29%   |
| VIA Technologies                 | 19        | 0.22%   |
| Aquantia                         | 18        | 0.21%   |
| Xiaomi                           | 17        | 0.2%    |
| Samsung Electronics              | 17        | 0.2%    |
| American Megatrends              | 15        | 0.17%   |
| Solarflare Communications        | 13        | 0.15%   |
| Emulex                           | 13        | 0.15%   |
| IBM                              | 12        | 0.14%   |
| QLogic                           | 11        | 0.13%   |
| Apple                            | 11        | 0.13%   |
| 3Com                             | 11        | 0.13%   |
| JMicron Technology               | 10        | 0.12%   |
| Google                           | 9         | 0.1%    |
| Qualcomm                         | 8         | 0.09%   |
| Silicon Integrated Systems [SiS] | 6         | 0.07%   |
| ICS Advent                       | 6         | 0.07%   |
| Huawei Technologies              | 6         | 0.07%   |
| Novatel Wireless                 | 5         | 0.06%   |
| Insyde Software                  | 4         | 0.05%   |
| National Semiconductor           | 3         | 0.03%   |
| Microsoft                        | 3         | 0.03%   |
| Davicom Semiconductor            | 3         | 0.03%   |
| Cisco Systems                    | 3         | 0.03%   |
| ADMtek                           | 3         | 0.03%   |
| Silicom                          | 2         | 0.02%   |
| Realtek                          | 2         | 0.02%   |
| OPPO Electronics                 | 2         | 0.02%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.02%   |
| MYRICOM                          | 2         | 0.02%   |
| Lenovo                           | 2         | 0.02%   |
| Digital Equipment                | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 2284      | 22.95%  |
| Intel I211 Gigabit Network Connection                                         | 953       | 9.57%   |
| Intel I210 Gigabit Network Connection                                         | 661       | 6.64%   |
| Intel I350 Gigabit Network Connection                                         | 417       | 4.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 405       | 4.07%   |
| Intel 82574L Gigabit Network Connection                                       | 362       | 3.64%   |
| Intel Ethernet Connection I217-LM                                             | 215       | 2.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 193       | 1.94%   |
| Intel 82583V Gigabit Network Connection                                       | 171       | 1.72%   |
| Intel 82576 Gigabit Network Connection                                        | 169       | 1.7%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 149       | 1.5%    |
| Intel 82580 Gigabit Network Connection                                        | 147       | 1.48%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 147       | 1.48%   |
| Intel Ethernet Controller I225-V                                              | 130       | 1.31%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 119       | 1.2%    |
| Realtek RTL8125 2.5GbE Controller                                             | 115       | 1.16%   |
| Intel Ethernet Connection (2) I219-LM                                         | 108       | 1.08%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 99        | 0.99%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 96        | 0.96%   |
| Intel Ethernet Connection (2) I219-V                                          | 86        | 0.86%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 84        | 0.84%   |
| Intel Ethernet Connection I354                                                | 68        | 0.68%   |
| Intel Ethernet Connection I219-LM                                             | 66        | 0.66%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 65        | 0.65%   |
| Intel 82579V Gigabit Network Connection                                       | 62        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                                          | 59        | 0.59%   |
| Intel Ethernet Connection X553 1GbE                                           | 53        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 52        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                                         | 51        | 0.51%   |
| Intel Ethernet Connection I217-V                                              | 48        | 0.48%   |
| Intel 82577LM Gigabit Network Connection                                      | 45        | 0.45%   |
| Intel Ethernet Controller X550                                                | 43        | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                                         | 43        | 0.43%   |
| Intel Ethernet Connection (4) I219-LM                                         | 42        | 0.42%   |
| Intel Ethernet Connection I218-LM                                             | 40        | 0.4%    |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 40        | 0.4%    |
| Intel Ethernet Connection (4) I219-V                                          | 39        | 0.39%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 38        | 0.38%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 37        | 0.37%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 35        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 7424      | 69.2%   |
| WiFi     | 3033      | 28.27%  |
| Unknown  | 163       | 1.52%   |
| Modem    | 108       | 1.01%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6946      | 80.95%  |
| WiFi     | 1598      | 18.62%  |
| Unknown  | 24        | 0.28%   |
| Modem    | 13        | 0.15%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2815      | 35.65%  |
| 1     | 1363      | 17.26%  |
| 4     | 1147      | 14.52%  |
| 3     | 967       | 12.25%  |
| 6     | 614       | 7.78%   |
| 5     | 451       | 5.71%   |
| 8     | 167       | 2.11%   |
| 0     | 133       | 1.68%   |
| 7     | 101       | 1.28%   |
| 10    | 48        | 0.61%   |
| 9     | 42        | 0.53%   |
| 12    | 18        | 0.23%   |
| 14    | 10        | 0.13%   |
| 11    | 7         | 0.09%   |
| 13    | 6         | 0.08%   |
| 16    | 3         | 0.04%   |
| 15    | 3         | 0.04%   |
| 20    | 2         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6955      | 86.58%  |
| Yes  | 1078      | 13.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1115      | 55.81%  |
| Broadcom                        | 155       | 7.76%   |
| Apple                           | 124       | 6.21%   |
| Qualcomm Atheros Communications | 113       | 5.66%   |
| Realtek Semiconductor           | 102       | 5.11%   |
| IMC Networks                    | 102       | 5.11%   |
| Cambridge Silicon Radio         | 73        | 3.65%   |
| Lite-On Technology              | 44        | 2.2%    |
| Foxconn / Hon Hai               | 37        | 1.85%   |
| ASUSTek Computer                | 35        | 1.75%   |
| Dell                            | 30        | 1.5%    |
| Hewlett-Packard                 | 21        | 1.05%   |
| Alps Electric                   | 15        | 0.75%   |
| Ralink                          | 7         | 0.35%   |
| MediaTek                        | 6         | 0.3%    |
| Realtek                         | 5         | 0.25%   |
| Integrated System Solution      | 3         | 0.15%   |
| Toshiba                         | 2         | 0.1%    |
| HTC (High Tech Computer)        | 2         | 0.1%    |
| TP-Link                         | 1         | 0.05%   |
| Qcom                            | 1         | 0.05%   |
| Micro Star International        | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| Dynex                           | 1         | 0.05%   |
| Creative Technology             | 1         | 0.05%   |
| Bluetooth Device                | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 518       | 25.87%  |
| Intel AX200 Bluetooth                                       | 157       | 7.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 148       | 7.39%   |
| Intel AX201 Bluetooth                                       | 101       | 5.04%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 73        | 3.65%   |
| Intel Wireless-AC 3168 Bluetooth                            | 65        | 3.25%   |
| Apple Bluetooth Host Controller                             | 54        | 2.7%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 49        | 2.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 46        | 2.3%    |
| Broadcom BCM2045B (BDC-2.1)                                 | 45        | 2.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 44        | 2.2%    |
| Realtek  Bluetooth 4.2 Adapter                              | 37        | 1.85%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 27        | 1.35%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 26        | 1.3%    |
| Apple Apple Broadcom Built-in Bluetooth                     | 26        | 1.3%    |
| Realtek  Bluetooth Adapter                                  | 20        | 1%      |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 20        | 1%      |
| Intel AX210 Bluetooth                                       | 20        | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 19        | 0.95%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 17        | 0.85%   |
| IMC Networks Realtek Bluetooth Adapter                      | 17        | 0.85%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 16        | 0.8%    |
| Lite-On Atheros AR3012 Bluetooth                            | 15        | 0.75%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 15        | 0.75%   |
| Realtek  Bluetooth 4.0 Adapter                              | 13        | 0.65%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 12        | 0.6%    |
| Dell DW375 Bluetooth Module                                 | 12        | 0.6%    |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 12        | 0.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 11        | 0.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 11        | 0.55%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 11        | 0.55%   |
| Apple Built-in iSight (no firmware loaded)                  | 11        | 0.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 10        | 0.5%    |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 10        | 0.5%    |
| Realtek Bluetooth Radio                                     | 9         | 0.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 9         | 0.45%   |
| Alps Electric UGTZ4 Bluetooth                               | 9         | 0.45%   |
| Realtek RTL8723B Bluetooth                                  | 8         | 0.4%    |
| IMC Networks Bluetooth Radio                                | 8         | 0.4%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 8         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4569      | 66.18%  |
| AMD                                          | 1247      | 18.06%  |
| Nvidia                                       | 735       | 10.65%  |
| C-Media Electronics                          | 64        | 0.93%   |
| Logitech                                     | 28        | 0.41%   |
| Creative Labs                                | 25        | 0.36%   |
| Texas Instruments                            | 19        | 0.28%   |
| Realtek Semiconductor                        | 13        | 0.19%   |
| Lenovo                                       | 13        | 0.19%   |
| GN Netcom                                    | 13        | 0.19%   |
| SteelSeries ApS                              | 12        | 0.17%   |
| VIA Technologies                             | 11        | 0.16%   |
| Silicon Integrated Systems [SiS]             | 10        | 0.14%   |
| JMTek                                        | 10        | 0.14%   |
| Creative Technology                          | 8         | 0.12%   |
| Sony                                         | 6         | 0.09%   |
| Kingston Technology                          | 6         | 0.09%   |
| Yamaha                                       | 5         | 0.07%   |
| Generalplus Technology                       | 5         | 0.07%   |
| Focusrite-Novation                           | 5         | 0.07%   |
| ESS Technology                               | 5         | 0.07%   |
| Corsair                                      | 5         | 0.07%   |
| Blue Microphones                             | 5         | 0.07%   |
| Zoran Co. Personal Media Division (Nogatech) | 4         | 0.06%   |
| XMOS                                         | 4         | 0.06%   |
| Plantronics                                  | 4         | 0.06%   |
| Cambridge Silicon Radio                      | 4         | 0.06%   |
| BEHRINGER International                      | 4         | 0.06%   |
| ULi Electronics                              | 3         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 3         | 0.04%   |
| M-Audio                                      | 3         | 0.04%   |
| FiiO Electronics Technology                  | 3         | 0.04%   |
| Trust                                        | 2         | 0.03%   |
| RODE Microphones                             | 2         | 0.03%   |
| Microsoft                                    | 2         | 0.03%   |
| Google                                       | 2         | 0.03%   |
| Giga-Byte Technology                         | 2         | 0.03%   |
| Ensoniq                                      | 2         | 0.03%   |
| DSEA A/S                                     | 2         | 0.03%   |
| Audio-Technica                               | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 436       | 5.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 404       | 4.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 392       | 4.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 374       | 4.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 367       | 4.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 254       | 3.07%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 252       | 3.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 250       | 3.02%   |
| AMD FCH Azalia Controller                                                                         | 227       | 2.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 220       | 2.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 205       | 2.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 196       | 2.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 184       | 2.22%   |
| Intel 8 Series HD Audio Controller                                                                | 183       | 2.21%   |
| Intel Broadwell-U Audio Controller                                                                | 181       | 2.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 175       | 2.12%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 172       | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 171       | 2.07%   |
| AMD Kabini HDMI/DP Audio                                                                          | 162       | 1.96%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 148       | 1.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 129       | 1.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 129       | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 125       | 1.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 124       | 1.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 118       | 1.43%   |
| Intel 200 Series PCH HD Audio                                                                     | 114       | 1.38%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 114       | 1.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 100       | 1.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 97        | 1.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 88        | 1.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 75        | 0.91%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 71        | 0.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 65        | 0.79%   |
| Intel Comet Lake PCH cAVS                                                                         | 61        | 0.74%   |
| Intel Jasper Lake HD Audio                                                                        | 54        | 0.65%   |
| AMD Wrestler HDMI Audio                                                                           | 52        | 0.63%   |
| Nvidia High Definition Audio Controller                                                           | 51        | 0.62%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 48        | 0.58%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 47        | 0.57%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 45        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1484      | 18.49%  |
| SK hynix            | 1113      | 13.87%  |
| Kingston            | 1032      | 12.86%  |
| Unknown             | 1027      | 12.79%  |
| Micron Technology   | 655       | 8.16%   |
| Crucial             | 653       | 8.14%   |
| Corsair             | 351       | 4.37%   |
| G.Skill             | 254       | 3.16%   |
| Unknown             | 171       | 2.13%   |
| Transcend           | 123       | 1.53%   |
| Unknown (ABCD)      | 114       | 1.42%   |
| A-DATA Technology   | 107       | 1.33%   |
| Ramaxel Technology  | 101       | 1.26%   |
| Nanya Technology    | 96        | 1.2%    |
| Elpida              | 84        | 1.05%   |
| Patriot             | 55        | 0.69%   |
| Team                | 53        | 0.66%   |
| Apacer              | 38        | 0.47%   |
| Hewlett-Packard     | 34        | 0.42%   |
| Toshiba             | 32        | 0.4%    |
| Kimtigo             | 31        | 0.39%   |
| Smart               | 29        | 0.36%   |
| Goodram             | 25        | 0.31%   |
| PNY                 | 22        | 0.27%   |
| ATP                 | 19        | 0.24%   |
| Avant               | 17        | 0.21%   |
| TIMETEC             | 16        | 0.2%    |
| Teikon              | 16        | 0.2%    |
| Super Talent        | 12        | 0.15%   |
| Innodisk            | 11        | 0.14%   |
| Tigo                | 10        | 0.12%   |
| AMD                 | 10        | 0.12%   |
| HPE                 | 9         | 0.11%   |
| Silicon Power       | 8         | 0.1%    |
| GeIL                | 8         | 0.1%    |
| 48spaces            | 8         | 0.1%    |
| Qimonda             | 7         | 0.09%   |
| Neo Forza           | 7         | 0.09%   |
| Goldkey             | 7         | 0.09%   |
| Kingmax             | 6         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 171       | 1.98%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 114       | 1.32%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 107       | 1.24%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 63        | 0.73%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 59        | 0.68%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 51        | 0.59%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 48        | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 44        | 0.51%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 41        | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 38        | 0.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 38        | 0.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 35        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 34        | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 33        | 0.38%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 33        | 0.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 32        | 0.37%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 29        | 0.34%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 29        | 0.34%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 28        | 0.32%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s             | 28        | 0.32%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 26        | 0.3%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s               | 26        | 0.3%    |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s           | 26        | 0.3%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 25        | 0.29%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s             | 25        | 0.29%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 24        | 0.28%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 24        | 0.28%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s           | 24        | 0.28%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 23        | 0.27%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 23        | 0.27%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s             | 23        | 0.27%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s             | 23        | 0.27%   |
| Unknown RAM Module 1GB DIMM SDRAM                                 | 21        | 0.24%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 21        | 0.24%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s             | 21        | 0.24%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s             | 21        | 0.24%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s             | 21        | 0.24%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 21        | 0.24%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s             | 21        | 0.24%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                        | 20        | 0.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR3            | 3598      | 51.01%  |
| DDR4            | 2438      | 34.57%  |
| DDR2            | 401       | 5.69%   |
| Unknown         | 223       | 3.16%   |
| LPDDR4          | 154       | 2.18%   |
| SDRAM           | 93        | 1.32%   |
| LPDDR3          | 63        | 0.89%   |
| DDR             | 60        | 0.85%   |
| DRAM            | 15        | 0.21%   |
| RAM             | 4         | 0.06%   |
| LPDDR5          | 2         | 0.03%   |
| SRAM            | 1         | 0.01%   |
| Logical non-vol | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 3725      | 52.95%  |
| SODIMM       | 3081      | 43.8%   |
| Row Of Chips | 93        | 1.32%   |
| Unknown      | 58        | 0.82%   |
| Chip         | 46        | 0.65%   |
| FB-DIMM      | 23        | 0.33%   |
| RIMM         | 9         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 2589      | 34.08%  |
| 4096   | 2565      | 33.76%  |
| 2048   | 1073      | 14.12%  |
| 16384  | 932       | 12.27%  |
| 1024   | 235       | 3.09%   |
| 32768  | 139       | 1.83%   |
| 512    | 40        | 0.53%   |
| 256    | 8         | 0.11%   |
| 65536  | 4         | 0.05%   |
| 128    | 4         | 0.05%   |
| 129728 | 1         | 0.01%   |
| 32767  | 1         | 0.01%   |
| 6144   | 1         | 0.01%   |
| 4092   | 1         | 0.01%   |
| 2560   | 1         | 0.01%   |
| 1556   | 1         | 0.01%   |
| 64     | 1         | 0.01%   |
| 32     | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 2233      | 29.76%  |
| 1333    | 1138      | 15.17%  |
| 2400    | 888       | 11.84%  |
| 2667    | 638       | 8.5%    |
| 2133    | 515       | 6.86%   |
| 3200    | 441       | 5.88%   |
| 667     | 262       | 3.49%   |
| 800     | 256       | 3.41%   |
| Unknown | 160       | 2.13%   |
| 1334    | 139       | 1.85%   |
| 2666    | 135       | 1.8%    |
| 1067    | 121       | 1.61%   |
| 1066    | 118       | 1.57%   |
| 1867    | 109       | 1.45%   |
| 2933    | 52        | 0.69%   |
| 1866    | 51        | 0.68%   |
| 533     | 41        | 0.55%   |
| 3600    | 36        | 0.48%   |
| 3000    | 32        | 0.43%   |
| 400     | 25        | 0.33%   |
| 4267    | 12        | 0.16%   |
| 975     | 11        | 0.15%   |
| 333     | 9         | 0.12%   |
| 266     | 7         | 0.09%   |
| 1332    | 6         | 0.08%   |
| 65535   | 5         | 0.07%   |
| 2134    | 5         | 0.07%   |
| 1033    | 5         | 0.07%   |
| 4266    | 4         | 0.05%   |
| 3400    | 4         | 0.05%   |
| 1400    | 4         | 0.05%   |
| 1200    | 4         | 0.05%   |
| 3534    | 3         | 0.04%   |
| 6400    | 2         | 0.03%   |
| 5200    | 2         | 0.03%   |
| 2800    | 2         | 0.03%   |
| 2600    | 2         | 0.03%   |
| 2048    | 2         | 0.03%   |
| 1800    | 2         | 0.03%   |
| 1639    | 2         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 10        | 28.57%  |
| Brother Industries    | 10        | 28.57%  |
| Seiko Epson           | 2         | 5.71%   |
| Prolific Technology   | 2         | 5.71%   |
| Lexmark International | 2         | 5.71%   |
| ELGIN                 | 2         | 5.71%   |
| Samsung Electronics   | 1         | 2.86%   |
| Ricoh                 | 1         | 2.86%   |
| QinHeng Electronics   | 1         | 2.86%   |
| Kyocera               | 1         | 2.86%   |
| Dymo-CoStar           | 1         | 2.86%   |
| Canon                 | 1         | 2.86%   |
| Apple                 | 1         | 2.86%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Computers | Percent |
|-------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                                                                     | 2         | 5.41%   |
| ELGIN L42PRO                                                                                                      | 2         | 5.41%   |
| Brother MFC-7360N                                                                                                 | 2         | 5.41%   |
| Brother HL-1430 Laser Printer                                                                                     | 2         | 5.41%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                                                                             | 1         | 2.7%    |
| Seiko Epson Printer                                                                                               | 1         | 2.7%    |
| Samsung ML-1610 Mono Laser Printer                                                                                | 1         | 2.7%    |
| Ricoh SP 112                                                                                                      | 1         | 2.7%    |
| QinHeng CH340S                                                                                                    | 1         | 2.7%    |
| Lexmark International SINDOH A603_A608 Print                                                                      | 1         | 2.7%    |
| Lexmark International Lexmark MS710 Print                                                                         | 1         | 2.7%    |
| Kyocera FS-1025MFP                                                                                                | 1         | 2.7%    |
| HP PNP Fax Null                                                                                                   | 1         | 2.7%    |
| HP LaserJet P3005                                                                                                 | 1         | 2.7%    |
| HP LaserJet 2200                                                                                                  | 1         | 2.7%    |
| HP LaserJet 1200                                                                                                  | 1         | 2.7%    |
| HP LaserJet 1012                                                                                                  | 1         | 2.7%    |
| HP HP LaserJet P2035 HP Print                                                                                     | 1         | 2.7%    |
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1         | 2.7%    |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer                        | 1         | 2.7%    |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer                                          | 1         | 2.7%    |
| HP HP Laser 107w                                                                                                  | 1         | 2.7%    |
| HP DeskJet 5850c                                                                                                  | 1         | 2.7%    |
| HP Color LaserJet CP1215                                                                                          | 1         | 2.7%    |
| Dymo-CoStar DYMO LabelWriter 450 DUO                                                                              | 1         | 2.7%    |
| Canon LBP2900                                                                                                     | 1         | 2.7%    |
| Brother MFC-J485DW                                                                                                | 1         | 2.7%    |
| Brother MFC-J200                                                                                                  | 1         | 2.7%    |
| Brother HL-L5200DW series                                                                                         | 1         | 2.7%    |
| Brother HL-L2310D series                                                                                          | 1         | 2.7%    |
| Brother HL-2030 Laser Printer                                                                                     | 1         | 2.7%    |
| Brother DCP-J100                                                                                                  | 1         | 2.7%    |
| Apple Gamesir-G3s 2.10                                                                                            | 1         | 2.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 7         | 77.78%  |
| Seiko Epson     | 1         | 11.11%  |
| Hewlett-Packard | 1         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 4         | 44.44%  |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 11.11%  |
| HP ScanJet 5300c/5370c                                                              | 1         | 11.11%  |
| Canon CanoScan LIDE 25                                                              | 1         | 11.11%  |
| Canon CanoScan LiDE 220                                                             | 1         | 11.11%  |
| Canon CanoScan LiDE 210                                                             | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 411       | 28.04%  |
| Acer                                   | 139       | 9.48%   |
| IMC Networks                           | 130       | 8.87%   |
| Realtek Semiconductor                  | 128       | 8.73%   |
| Microdia                               | 118       | 8.05%   |
| Sunplus Innovation Technology          | 78        | 5.32%   |
| Logitech                               | 70        | 4.77%   |
| Suyin                                  | 51        | 3.48%   |
| Lite-On Technology                     | 49        | 3.34%   |
| Quanta                                 | 30        | 2.05%   |
| Apple                                  | 30        | 2.05%   |
| Cheng Uei Precision Industry (Foxlink) | 28        | 1.91%   |
| Syntek                                 | 25        | 1.71%   |
| Silicon Motion                         | 21        | 1.43%   |
| Lenovo                                 | 21        | 1.43%   |
| Alcor Micro                            | 18        | 1.23%   |
| Z-Star Microelectronics                | 15        | 1.02%   |
| Ricoh                                  | 12        | 0.82%   |
| Luxvisions Innotech Limited            | 11        | 0.75%   |
| ALi                                    | 11        | 0.75%   |
| Importek                               | 8         | 0.55%   |
| ARC International                      | 7         | 0.48%   |
| Intel                                  | 4         | 0.27%   |
| Sonix Technology                       | 3         | 0.2%    |
| Primax Electronics                     | 3         | 0.2%    |
| OmniVision Technologies                | 3         | 0.2%    |
| Arkmicro Technologies                  | 3         | 0.2%    |
| WCM_USB                                | 2         | 0.14%   |
| Unknown                                | 2         | 0.14%   |
| Tripath Technology                     | 2         | 0.14%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.14%   |
| Pixart Imaging                         | 2         | 0.14%   |
| Hewlett-Packard                        | 2         | 0.14%   |
| Genesys Logic                          | 2         | 0.14%   |
| Generalplus Technology                 | 2         | 0.14%   |
| GEMBIRD                                | 2         | 0.14%   |
| DigiTech                               | 2         | 0.14%   |
| Cubeternet                             | 2         | 0.14%   |
| Aveo Technology                        | 2         | 0.14%   |
| YGTek                                  | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 127       | 8.59%   |
| Acer Integrated Camera                    | 63        | 4.26%   |
| Realtek Integrated_Webcam_HD              | 43        | 2.91%   |
| IMC Networks Integrated Camera            | 41        | 2.77%   |
| Chicony HD Webcam                         | 34        | 2.3%    |
| Lite-On Integrated Camera                 | 31        | 2.1%    |
| Microdia Integrated Webcam                | 28        | 1.89%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 27        | 1.83%   |
| Microdia Integrated_Webcam_HD             | 26        | 1.76%   |
| Sunplus Integrated_Webcam_HD              | 25        | 1.69%   |
| Realtek Realtek USB2.0 PC Camera          | 23        | 1.56%   |
| IMC Networks USB2.0 HD UVC WebCam         | 20        | 1.35%   |
| Logitech Webcam C270                      | 18        | 1.22%   |
| Logitech HD Pro Webcam C920               | 18        | 1.22%   |
| Apple FaceTime HD Camera                  | 18        | 1.22%   |
| Acer Lenovo EasyCamera                    | 18        | 1.22%   |
| Chicony Integrated Camera (1280x720@30)   | 16        | 1.08%   |
| Chicony Chicony USB2.0 Camera             | 16        | 1.08%   |
| Chicony Integrated Camera [ThinkPad]      | 14        | 0.95%   |
| Syntek Lenovo EasyCamera                  | 13        | 0.88%   |
| Lenovo Integrated Webcam [R5U877]         | 13        | 0.88%   |
| IMC Networks EasyCamera                   | 13        | 0.88%   |
| Chicony HP HD Webcam [Fixed]              | 13        | 0.88%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 11        | 0.74%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 11        | 0.74%   |
| Realtek USB Camera                        | 10        | 0.68%   |
| Apple FaceTime HD Camera (Built-in)       | 10        | 0.68%   |
| Microdia Laptop_Integrated_Webcam_HD      | 9         | 0.61%   |
| Chicony USB2.0 VGA UVC WebCam             | 9         | 0.61%   |
| Chicony ThinkPad T490 Webcam              | 9         | 0.61%   |
| Chicony Lenovo EasyCamera                 | 9         | 0.61%   |
| Acer ThinkPad Integrated Camera           | 9         | 0.61%   |
| Acer SunplusIT Integrated Camera          | 9         | 0.61%   |
| Acer Lenovo Integrated Webcam             | 9         | 0.61%   |
| Microdia Dell Laptop Integrated Webcam HD | 8         | 0.54%   |
| IMC Networks USB2.0 UVC HD Webcam         | 8         | 0.54%   |
| Chicony USB2.0 HD UVC WebCam              | 8         | 0.54%   |
| Chicony EasyCamera                        | 8         | 0.54%   |
| ALi Gateway Webcam                        | 8         | 0.54%   |
| Syntek EasyCamera                         | 7         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 150       | 38.76%  |
| Synaptics                  | 71        | 18.35%  |
| Upek                       | 49        | 12.66%  |
| AuthenTec                  | 35        | 9.04%   |
| Shenzhen Goodix Technology | 28        | 7.24%   |
| STMicroelectronics         | 26        | 6.72%   |
| Broadcom                   | 14        | 3.62%   |
| LighTuning Technology      | 6         | 1.55%   |
| Elan Microelectronics      | 4         | 1.03%   |
| Samsung Electronics        | 2         | 0.52%   |
| Next Biometrics            | 1         | 0.26%   |
| Focal-systems.Corp         | 1         | 0.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 51        | 13.18%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 46        | 11.89%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 30        | 7.75%   |
| Validity Sensors Synaptics WBDI                                              | 28        | 7.24%   |
| STMicroelectronics Fingerprint Reader                                        | 26        | 6.72%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 20        | 5.17%   |
| Shenzhen Goodix Fingerprint Reader                                           | 19        | 4.91%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 18        | 4.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 14        | 3.62%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 3.62%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 12        | 3.1%    |
| AuthenTec AES2501 Fingerprint Sensor                                         | 10        | 2.58%   |
| AuthenTec AES2810                                                            | 9         | 2.33%   |
| Shenzhen Goodix  FingerPrint Device                                          | 7         | 1.81%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 6         | 1.55%   |
| Unknown                                                                      | 6         | 1.55%   |
| Validity Sensors VFS491                                                      | 5         | 1.29%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 5         | 1.29%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 5         | 1.29%   |
| AuthenTec AES1600                                                            | 5         | 1.29%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 4         | 1.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 4         | 1.03%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                    | 4         | 1.03%   |
| Elan ELAN WBF Fingerprint Sensor                                             | 4         | 1.03%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 3         | 0.78%   |
| Validity Sensors Fingerprint scanner                                         | 3         | 0.78%   |
| Upek TCS5B Fingerprint sensor                                                | 3         | 0.78%   |
| Synaptics  WBDI                                                              | 3         | 0.78%   |
| Synaptics product 0x00be                                                     | 3         | 0.78%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 3         | 0.78%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 3         | 0.78%   |
| Shenzhen Goodix FingerPrint                                                  | 2         | 0.52%   |
| AuthenTec AuthenTec Inc. AES2660                                             | 2         | 0.52%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 2         | 0.52%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 0.26%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 0.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 0.26%   |
| Samsung Fingerprint Sensor Device - 730B                                     | 1         | 0.26%   |
| Samsung Fingerprint Device                                                   | 1         | 0.26%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 0.26%   |

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
| 1     | 3003      | 37.23%  |
| 0     | 2732      | 33.87%  |
| 2     | 1425      | 17.67%  |
| 3     | 589       | 7.3%    |
| 4     | 233       | 2.89%   |
| 5     | 57        | 0.71%   |
| 6     | 17        | 0.21%   |
| 7     | 7         | 0.09%   |
| 9     | 1         | 0.01%   |
| 8     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 4378      | 56.86%  |
| Net/wireless             | 822       | 10.68%  |
| Bluetooth                | 745       | 9.68%   |
| Card reader              | 576       | 7.48%   |
| Fingerprint reader       | 326       | 4.23%   |
| Firewire controller      | 302       | 3.92%   |
| Sound                    | 140       | 1.82%   |
| Net/ethernet             | 107       | 1.39%   |
| Network                  | 103       | 1.34%   |
| Graphics card            | 96        | 1.25%   |
| Storage                  | 40        | 0.52%   |
| Modem                    | 22        | 0.29%   |
| Storage/ata              | 13        | 0.17%   |
| Storage/raid             | 12        | 0.16%   |
| Dvb card                 | 8         | 0.1%    |
| Storage/ide              | 6         | 0.08%   |
| Storage/nvme             | 3         | 0.04%   |
| Wireless                 | 1         | 0.01%   |

