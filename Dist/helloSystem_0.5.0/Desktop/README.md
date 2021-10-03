helloSystem 0.5.0 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.5.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends&rel=hellosystem-0.5.0

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | 87D6 SMVB                   | [90d91bc113](https://bsd-hardware.info/?probe=90d91bc113) | Sep 26, 2021 |
| Gigabyte      | H61M-D2P-B3                 | [c6da80d54b](https://bsd-hardware.info/?probe=c6da80d54b) | Sep 25, 2021 |
| ASUSTek       | M5A78L-M LX3                | [f336d13e01](https://bsd-hardware.info/?probe=f336d13e01) | Sep 24, 2021 |
| Gigabyte      | H61M-D2P-B3                 | [6ed62a3798](https://bsd-hardware.info/?probe=6ed62a3798) | Sep 23, 2021 |
| Foxconn       | A88GMX FAB                  | [b46845b69f](https://bsd-hardware.info/?probe=b46845b69f) | Sep 19, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [bc2a287495](https://bsd-hardware.info/?probe=bc2a287495) | Sep 13, 2021 |
| HP            | 87D6 SMVB                   | [61fc69edfe](https://bsd-hardware.info/?probe=61fc69edfe) | Sep 13, 2021 |
| ASUSTek       | P8H77-I                     | [1feb22dc52](https://bsd-hardware.info/?probe=1feb22dc52) | Sep 12, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | [85ed325446](https://bsd-hardware.info/?probe=85ed325446) | Sep 11, 2021 |
| ASRock        | B460M Pro4                  | [cfc7818691](https://bsd-hardware.info/?probe=cfc7818691) | Sep 10, 2021 |
| ASUSTek       | H110M-PLUS                  | [08b4825275](https://bsd-hardware.info/?probe=08b4825275) | Sep 09, 2021 |
| ASRock        | B550M Pro4                  | [dc582ea4d3](https://bsd-hardware.info/?probe=dc582ea4d3) | Sep 09, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [c729f82f4c](https://bsd-hardware.info/?probe=c729f82f4c) | Sep 08, 2021 |
| Packard Be... | imedia S2110A               | [d62a38660c](https://bsd-hardware.info/?probe=d62a38660c) | Sep 08, 2021 |
| Lenovo        | Board                       | [685abcc739](https://bsd-hardware.info/?probe=685abcc739) | Sep 07, 2021 |
| Medion        | H61H2-LM3                   | [7a42009a08](https://bsd-hardware.info/?probe=7a42009a08) | Sep 02, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9e13729a12](https://bsd-hardware.info/?probe=9e13729a12) | Sep 02, 2021 |
| HP            | 0A60h                       | [0f28538e3d](https://bsd-hardware.info/?probe=0f28538e3d) | Aug 25, 2021 |
| HP            | 1589                        | [4d51cc9c4b](https://bsd-hardware.info/?probe=4d51cc9c4b) | Aug 24, 2021 |
| Acer          | Aspire TC-895 V:1.0         | [da3e8986a3](https://bsd-hardware.info/?probe=da3e8986a3) | Aug 22, 2021 |
| EVGA          | X299 MICRO                  | [d04b55d1f6](https://bsd-hardware.info/?probe=d04b55d1f6) | Aug 19, 2021 |
| ASRock        | Z390 Pro4                   | [aca402061b](https://bsd-hardware.info/?probe=aca402061b) | Aug 18, 2021 |
| Foxconn       | 2ADA                        | [e96976b2cc](https://bsd-hardware.info/?probe=e96976b2cc) | Aug 18, 2021 |
| HC            | HCAR357-MI V1.0             | [3293b7bad9](https://bsd-hardware.info/?probe=3293b7bad9) | Aug 17, 2021 |
| Gigabyte      | HA65M-D2H-B3                | [fc9b50bb85](https://bsd-hardware.info/?probe=fc9b50bb85) | Aug 16, 2021 |
| Gigabyte      | B360M D3H-CF                | [1c88ce5779](https://bsd-hardware.info/?probe=1c88ce5779) | Aug 10, 2021 |
| Pegatron      | IPPCR-SS                    | [8a7fc2689b](https://bsd-hardware.info/?probe=8a7fc2689b) | Aug 09, 2021 |
| Gigabyte      | A75M-DS2                    | [2010fe5fab](https://bsd-hardware.info/?probe=2010fe5fab) | Aug 09, 2021 |
| ASUSTek       | P7H55-M LX                  | [df393cc673](https://bsd-hardware.info/?probe=df393cc673) | Aug 08, 2021 |
| Intel         | D54250WYK H13922-304        | [45c86d174e](https://bsd-hardware.info/?probe=45c86d174e) | Aug 08, 2021 |
| ASUSTek       | M5A78L LE                   | [7a1d31be72](https://bsd-hardware.info/?probe=7a1d31be72) | Aug 07, 2021 |
| ASUSTek       | H81M-A                      | [bb65c30be3](https://bsd-hardware.info/?probe=bb65c30be3) | Aug 07, 2021 |
| ASUSTek       | H81M-A                      | [9e0c8e8024](https://bsd-hardware.info/?probe=9e0c8e8024) | Aug 07, 2021 |
| ASUSTek       | Crosshair V Formula         | [90c27497d9](https://bsd-hardware.info/?probe=90c27497d9) | Aug 05, 2021 |
| PCPartner     | MILANO-P Rev.00             | [526390c559](https://bsd-hardware.info/?probe=526390c559) | Aug 04, 2021 |
| PCPartner     | MILANO-P Rev.00             | [071eac9b1b](https://bsd-hardware.info/?probe=071eac9b1b) | Aug 04, 2021 |
| Biostar       | A770E3                      | [4d0ac19b8e](https://bsd-hardware.info/?probe=4d0ac19b8e) | Aug 03, 2021 |
| Dell          | 0RY007                      | [c67ccf8bc6](https://bsd-hardware.info/?probe=c67ccf8bc6) | Aug 01, 2021 |
| PCPartner     | MILANO-P Rev.00             | [ef40df391b](https://bsd-hardware.info/?probe=ef40df391b) | Aug 01, 2021 |
| Gigabyte      | H110-D3A-CF                 | [7923f57fbe](https://bsd-hardware.info/?probe=7923f57fbe) | Aug 01, 2021 |
| ASUSTek       | A58M-A/USB3                 | [9ffd4220e8](https://bsd-hardware.info/?probe=9ffd4220e8) | Aug 01, 2021 |
| Biostar       | N68S3+                      | [528c9d6eab](https://bsd-hardware.info/?probe=528c9d6eab) | Jul 26, 2021 |
| Gigabyte      | PH67A-D3-B3                 | [73dff53f04](https://bsd-hardware.info/?probe=73dff53f04) | Jul 23, 2021 |
| Gigabyte      | H110-D3A-CF                 | [58e49f458e](https://bsd-hardware.info/?probe=58e49f458e) | Jul 19, 2021 |
| PCPartner     | MILANO-P Rev.00             | [f20ac8df75](https://bsd-hardware.info/?probe=f20ac8df75) | Jul 19, 2021 |
| MSI           | IONA                        | [bb2c6b383b](https://bsd-hardware.info/?probe=bb2c6b383b) | Jul 17, 2021 |
| ASRock        | N68C-GS FX                  | [012356047f](https://bsd-hardware.info/?probe=012356047f) | Jul 17, 2021 |
| ASRock        | N68C-GS FX                  | [e1f439def9](https://bsd-hardware.info/?probe=e1f439def9) | Jul 17, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [20fc88018b](https://bsd-hardware.info/?probe=20fc88018b) | Jul 16, 2021 |
| HP            | 0AE8h C                     | [23df6b2e94](https://bsd-hardware.info/?probe=23df6b2e94) | Jul 12, 2021 |
| Dell          | 0GXM1W A02                  | [269edf2dcf](https://bsd-hardware.info/?probe=269edf2dcf) | Jul 06, 2021 |
| ASRock        | B450M-HDV                   | [dca41aa10a](https://bsd-hardware.info/?probe=dca41aa10a) | Jul 05, 2021 |
| ASRock        | X99 Taichi                  | [149d7abd05](https://bsd-hardware.info/?probe=149d7abd05) | Jul 04, 2021 |
| ASUSTek       | PRIME Z390-P                | [4060cdec72](https://bsd-hardware.info/?probe=4060cdec72) | Jul 04, 2021 |
| ASRock        | Z390 Pro4                   | [dc4eb674ea](https://bsd-hardware.info/?probe=dc4eb674ea) | Jul 03, 2021 |
| Shuttle       | NC10U                       | [5d2d20dd04](https://bsd-hardware.info/?probe=5d2d20dd04) | Jul 02, 2021 |
| Protectli     | FW2B Ver                    | [7b6f704247](https://bsd-hardware.info/?probe=7b6f704247) | Jun 30, 2021 |
| HP            | 0B4Ch D                     | [b56bd19073](https://bsd-hardware.info/?probe=b56bd19073) | Jun 30, 2021 |
| Biostar       | B450MH                      | [167f09a25c](https://bsd-hardware.info/?probe=167f09a25c) | Jun 29, 2021 |
| Huanan        | X99-8M-F V1.2               | [6477b9ef24](https://bsd-hardware.info/?probe=6477b9ef24) | Jun 28, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [f0e80b0788](https://bsd-hardware.info/?probe=f0e80b0788) | Jun 28, 2021 |
| ASUSTek       | H110M-E/M.2                 | [f3b0bb0930](https://bsd-hardware.info/?probe=f3b0bb0930) | Jun 28, 2021 |
| ASUSTek       | PRIME H410M-D               | [8ea103b783](https://bsd-hardware.info/?probe=8ea103b783) | Jun 26, 2021 |
| Dell          | 0P03DX A03                  | [b2f0c90d79](https://bsd-hardware.info/?probe=b2f0c90d79) | Jun 24, 2021 |
| ASUSTek       | P7H55                       | [c33ec074f8](https://bsd-hardware.info/?probe=c33ec074f8) | Jun 22, 2021 |
| ASUSTek       | P8H67-M PRO                 | [616c7043bd](https://bsd-hardware.info/?probe=616c7043bd) | Jun 22, 2021 |
| ASUSTek       | CP5141                      | [73c62835c1](https://bsd-hardware.info/?probe=73c62835c1) | Jun 21, 2021 |
| Foxconn       | 2ABF                        | [d30b2629eb](https://bsd-hardware.info/?probe=d30b2629eb) | Jun 21, 2021 |
| Intel         | DH67CL AAG10212-206         | [f2367a4249](https://bsd-hardware.info/?probe=f2367a4249) | Jun 21, 2021 |
| Gigabyte      | H97-D3H-CF                  | [a326fd4061](https://bsd-hardware.info/?probe=a326fd4061) | Jun 20, 2021 |
| Dell          | 0PGKWF A01                  | [9f09d62462](https://bsd-hardware.info/?probe=9f09d62462) | Jun 20, 2021 |
| MSI           | H110M PRO-VH PLUS           | [45b842180e](https://bsd-hardware.info/?probe=45b842180e) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [d2dd261a2a](https://bsd-hardware.info/?probe=d2dd261a2a) | Jun 20, 2021 |
| MSI           | B450M PRO-M2 MAX            | [edcbaf755f](https://bsd-hardware.info/?probe=edcbaf755f) | Jun 19, 2021 |
| Dell          | 0XPDFK A01                  | [631dbb841b](https://bsd-hardware.info/?probe=631dbb841b) | Jun 19, 2021 |
| Lenovo        | ThinkServer RS140           | [0f5d669e9f](https://bsd-hardware.info/?probe=0f5d669e9f) | Jun 18, 2021 |
| Lenovo        | ThinkServer RS140           | [63ba615299](https://bsd-hardware.info/?probe=63ba615299) | Jun 18, 2021 |
| Gigabyte      | AX370-Gaming-CF             | [d77be09267](https://bsd-hardware.info/?probe=d77be09267) | Jun 18, 2021 |
| Dell          | 0XPDFK A01                  | [7a1c26edeb](https://bsd-hardware.info/?probe=7a1c26edeb) | Jun 18, 2021 |
| ASUSTek       | H110I-PLUS                  | [0cb30b464d](https://bsd-hardware.info/?probe=0cb30b464d) | Jun 17, 2021 |
| HP            | 3397                        | [3dd97c60ca](https://bsd-hardware.info/?probe=3dd97c60ca) | Jun 16, 2021 |
| Lenovo        | Board                       | [c981ffdff7](https://bsd-hardware.info/?probe=c981ffdff7) | Jun 15, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [5f9b56c8ae](https://bsd-hardware.info/?probe=5f9b56c8ae) | Jun 15, 2021 |
| ASUSTek       | M4A78LT-M                   | [0c8d6cd661](https://bsd-hardware.info/?probe=0c8d6cd661) | Jun 14, 2021 |
| ASUSTek       | PRIME A320M-K               | [fea57181b5](https://bsd-hardware.info/?probe=fea57181b5) | Jun 14, 2021 |
| ASRock        | G31M-VS2                    | [f2f5b95f4b](https://bsd-hardware.info/?probe=f2f5b95f4b) | Jun 14, 2021 |
| Intel         | X79 V2.72A                  | [88173bcf06](https://bsd-hardware.info/?probe=88173bcf06) | Jun 14, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [eeb4489d2f](https://bsd-hardware.info/?probe=eeb4489d2f) | Jun 13, 2021 |
| Gigabyte      | H470M DS3H                  | [7c37a0319b](https://bsd-hardware.info/?probe=7c37a0319b) | Jun 13, 2021 |
| ASRock        | FM2A68M-HD+                 | [8bb0d23eb4](https://bsd-hardware.info/?probe=8bb0d23eb4) | Jun 13, 2021 |
| ASUSTek       | P5G41T-M LX3                | [1759329ae3](https://bsd-hardware.info/?probe=1759329ae3) | Apr 12, 2021 |
| Dell          | 0RW199                      | [e78392bc4c](https://bsd-hardware.info/?probe=e78392bc4c) | Apr 02, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [62376c16a4](https://bsd-hardware.info/?probe=62376c16a4) | Mar 31, 2021 |
| Medion        | H61H2-LM3                   | [6483c8390f](https://bsd-hardware.info/?probe=6483c8390f) | Mar 31, 2021 |
| Pegatron      | IPM41-D3                    | [687047b3d2](https://bsd-hardware.info/?probe=687047b3d2) | Mar 30, 2021 |
| Gigabyte      | Z77X-UD5H                   | [d3742d3898](https://bsd-hardware.info/?probe=d3742d3898) | Mar 29, 2021 |
| HP            | 18E7                        | [0e835b61ff](https://bsd-hardware.info/?probe=0e835b61ff) | Mar 24, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [78a7c7b8cb](https://bsd-hardware.info/?probe=78a7c7b8cb) | Mar 23, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5ae508dfa8](https://bsd-hardware.info/?probe=5ae508dfa8) | Mar 19, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [8964a02114](https://bsd-hardware.info/?probe=8964a02114) | Mar 15, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [0a3b290f9f](https://bsd-hardware.info/?probe=0a3b290f9f) | Mar 15, 2021 |
| ASUSTek       | H110M-PLUS                  | [80e7c230d7](https://bsd-hardware.info/?probe=80e7c230d7) | Mar 12, 2021 |
| Dell          | 0W2PJY A01                  | [f162510a27](https://bsd-hardware.info/?probe=f162510a27) | Mar 12, 2021 |
| MSI           | B150M PRO-VDH               | [bc75a3ab13](https://bsd-hardware.info/?probe=bc75a3ab13) | Mar 11, 2021 |
| ASUSTek       | H110M-PLUS                  | [cf00023cef](https://bsd-hardware.info/?probe=cf00023cef) | Mar 11, 2021 |
| ASRock        | B450M Pro4                  | [e9ca160a2d](https://bsd-hardware.info/?probe=e9ca160a2d) | Mar 11, 2021 |
| Gigabyte      | 970A-DS3P                   | [47d17e6983](https://bsd-hardware.info/?probe=47d17e6983) | Mar 10, 2021 |
| Dell          | 0JP3NX A01                  | [fc94b8c422](https://bsd-hardware.info/?probe=fc94b8c422) | Mar 09, 2021 |
| ASUSTek       | P8Z77-V                     | [88ee81b089](https://bsd-hardware.info/?probe=88ee81b089) | Mar 06, 2021 |
| Dell          | 0W2PJY A01                  | [d8c2f0b19f](https://bsd-hardware.info/?probe=d8c2f0b19f) | Mar 04, 2021 |
| Foxconn       | 2ADA                        | [10d02d0982](https://bsd-hardware.info/?probe=10d02d0982) | Mar 03, 2021 |
| ASUSTek       | P8Z77-V LX2                 | [0aeea0fec9](https://bsd-hardware.info/?probe=0aeea0fec9) | Feb 23, 2021 |
| ASUSTek       | P5Q                         | [22fa0d8178](https://bsd-hardware.info/?probe=22fa0d8178) | Feb 23, 2021 |
| Biostar       | B365MHC                     | [adb029c65f](https://bsd-hardware.info/?probe=adb029c65f) | Feb 22, 2021 |
| Dell          | 0RW199                      | [e0ecb4caa7](https://bsd-hardware.info/?probe=e0ecb4caa7) | Feb 21, 2021 |
| ASUSTek       | P5B-Deluxe                  | [a471763f19](https://bsd-hardware.info/?probe=a471763f19) | Feb 20, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [0b5194e68e](https://bsd-hardware.info/?probe=0b5194e68e) | Feb 19, 2021 |
| Unknown       | Unknown                     | [22af66ce96](https://bsd-hardware.info/?probe=22af66ce96) | Feb 18, 2021 |
| Dell          | 0GM819                      | [836d0f9057](https://bsd-hardware.info/?probe=836d0f9057) | Feb 17, 2021 |
| ASUSTek       | P8H61-MX R2.0               | [e601d28f5e](https://bsd-hardware.info/?probe=e601d28f5e) | Feb 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [b087324f05](https://bsd-hardware.info/?probe=b087324f05) | Feb 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [d03a5bbea5](https://bsd-hardware.info/?probe=d03a5bbea5) | Feb 17, 2021 |
| Pegatron      | IPM41-D3                    | [6e5c330c9c](https://bsd-hardware.info/?probe=6e5c330c9c) | Feb 16, 2021 |
| ASUSTek       | VM62                        | [4d02a33fec](https://bsd-hardware.info/?probe=4d02a33fec) | Feb 16, 2021 |
| ASUSTek       | P5B SE                      | [425210021c](https://bsd-hardware.info/?probe=425210021c) | Feb 16, 2021 |
| HP            | 8768 A                      | [f2be4b7b65](https://bsd-hardware.info/?probe=f2be4b7b65) | Feb 16, 2021 |
| Intel         | DN2820FYK H24582-201        | [be56203e79](https://bsd-hardware.info/?probe=be56203e79) | Feb 15, 2021 |
| ASUSTek       | EX-B85M-V                   | [54c319f2c0](https://bsd-hardware.info/?probe=54c319f2c0) | Feb 15, 2021 |
| ASRock        | B450M Pro4                  | [ef29c46355](https://bsd-hardware.info/?probe=ef29c46355) | Feb 15, 2021 |
| ASRock        | B550M Pro4                  | [61a5641019](https://bsd-hardware.info/?probe=61a5641019) | Feb 14, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [8082fefc2e](https://bsd-hardware.info/?probe=8082fefc2e) | Feb 14, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [565ceb36f0](https://bsd-hardware.info/?probe=565ceb36f0) | Feb 14, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 107      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 107      | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 107      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 107      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 105      | 97.22%  |
| it_IT | 1        | 0.93%   |
| es_ES | 1        | 0.93%   |
| es_AR | 1        | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 86       | 80.37%  |
| BIOS | 21       | 19.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 107      | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 107      | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 33       | 30.84%  |
| Gigabyte Technology | 11       | 10.28%  |
| ASRock              | 11       | 10.28%  |
| Dell                | 9        | 8.41%   |
| Hewlett-Packard     | 8        | 7.48%   |
| MSI                 | 6        | 5.61%   |
| Lenovo              | 5        | 4.67%   |
| Intel               | 4        | 3.74%   |
| Foxconn             | 4        | 3.74%   |
| Biostar             | 4        | 3.74%   |
| Pegatron            | 2        | 1.87%   |
| Shuttle             | 1        | 0.93%   |
| Protectli           | 1        | 0.93%   |
| PCPartner           | 1        | 0.93%   |
| Packard Bell        | 1        | 0.93%   |
| Medion              | 1        | 0.93%   |
| Huanan              | 1        | 0.93%   |
| HC                  | 1        | 0.93%   |
| EVGA                | 1        | 0.93%   |
| Acer                | 1        | 0.93%   |
| Unknown             | 1        | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 2        | 1.87%   |
| ASRock B550M Pro4                   | 2        | 1.87%   |
| ASRock B450M Pro4                   | 2        | 1.87%   |
| Shuttle NC10U                       | 1        | 0.93%   |
| Protectli FW2B                      | 1        | 0.93%   |
| Pegatron SAISHIAT2                  | 1        | 0.93%   |
| Pegatron IPM41-D3                   | 1        | 0.93%   |
| PCPartner DREAMSYS                  | 1        | 0.93%   |
| Packard Bell imedia S2110           | 1        | 0.93%   |
| MSI WC791AA-UUW HPE-119sc           | 1        | 0.93%   |
| MSI MS-7C37                         | 1        | 0.93%   |
| MSI MS-7B86                         | 1        | 0.93%   |
| MSI MS-7B84                         | 1        | 0.93%   |
| MSI MS-7A15                         | 1        | 0.93%   |
| MSI MS-7982                         | 1        | 0.93%   |
| Medion H61H2-LM3                    | 1        | 0.93%   |
| Lenovo ThinkCentre M91p 7033DE6     | 1        | 0.93%   |
| Lenovo ThinkCentre M91p 7033D54     | 1        | 0.93%   |
| Lenovo ThinkCentre M83 10AHS35Q00   | 1        | 0.93%   |
| Lenovo ThinkCentre M720s 10SUS4WT00 | 1        | 0.93%   |
| Lenovo 70F8S01J00 ThinkServer RS140 | 1        | 0.93%   |
| Intel X79 V2.72A                    | 1        | 0.93%   |
| Intel DN2820FYK H24582-201          | 1        | 0.93%   |
| Intel DH67CL AAG10212-206           | 1        | 0.93%   |
| Intel D54250WYK H13922-304          | 1        | 0.93%   |
| Huanan X99-8M-F V1.2                | 1        | 0.93%   |
| HP Z600 Workstation                 | 1        | 0.93%   |
| HP Z420 Workstation                 | 1        | 0.93%   |
| HP Z400 Workstation                 | 1        | 0.93%   |
| HP Slim Desktop S01-pF1xxx          | 1        | 0.93%   |
| HP ProDesk 600 G1 SFF               | 1        | 0.93%   |
| HP Desktop M01-F1xxx                | 1        | 0.93%   |
| HP Compaq Elite 8300 SFF            | 1        | 0.93%   |
| HP Compaq dc5700 Small Form Factor  | 1        | 0.93%   |
| HC HCAR357-MI                       | 1        | 0.93%   |
| Gigabyte Z77X-UD5H                  | 1        | 0.93%   |
| Gigabyte PH67A-D3-B3                | 1        | 0.93%   |
| Gigabyte HA65M-D2H-B3               | 1        | 0.93%   |
| Gigabyte H97-D3H                    | 1        | 0.93%   |
| Gigabyte H61M-D2P-B3                | 1        | 0.93%   |
| Gigabyte H470M DS3H                 | 1        | 0.93%   |
| Gigabyte H110-D3A                   | 1        | 0.93%   |
| Gigabyte B360M-D3H                  | 1        | 0.93%   |
| Gigabyte AX370-Gaming               | 1        | 0.93%   |
| Gigabyte A75M-DS2                   | 1        | 0.93%   |
| Gigabyte 970A-DS3P                  | 1        | 0.93%   |
| Foxconn RS880M06-8KRS3HX            | 1        | 0.93%   |
| Foxconn Pro 3500 Series             | 1        | 0.93%   |
| Foxconn p6-2305elm                  | 1        | 0.93%   |
| Foxconn p6-2171a                    | 1        | 0.93%   |
| EVGA X299 MICRO                     | 1        | 0.93%   |
| Dell Precision WorkStation T7400    | 1        | 0.93%   |
| Dell Precision WorkStation T5500    | 1        | 0.93%   |
| Dell Precision WorkStation T3500    | 1        | 0.93%   |
| Dell OptiPlex 990                   | 1        | 0.93%   |
| Dell OptiPlex 755                   | 1        | 0.93%   |
| Dell OptiPlex 7010                  | 1        | 0.93%   |
| Dell OptiPlex 5055 Ryzen CPU        | 1        | 0.93%   |
| Dell OptiPlex 3050                  | 1        | 0.93%   |
| Dell Inspiron 530                   | 1        | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| Dell OptiPlex            | 5        | 4.67%   |
| ASUS PRIME               | 5        | 4.67%   |
| Lenovo ThinkCentre       | 4        | 3.74%   |
| Dell Precision           | 3        | 2.8%    |
| ASUS M5A78L-M            | 3        | 2.8%    |
| HP Compaq                | 2        | 1.87%   |
| ASUS ROG                 | 2        | 1.87%   |
| ASUS P8Z77-V             | 2        | 1.87%   |
| ASUS All                 | 2        | 1.87%   |
| ASRock B550M             | 2        | 1.87%   |
| ASRock B450M             | 2        | 1.87%   |
| Shuttle NC10U            | 1        | 0.93%   |
| Protectli FW2B           | 1        | 0.93%   |
| Pegatron SAISHIAT2       | 1        | 0.93%   |
| Pegatron IPM41-D3        | 1        | 0.93%   |
| PCPartner DREAMSYS       | 1        | 0.93%   |
| Packard Bell imedia      | 1        | 0.93%   |
| MSI WC791AA-UUW          | 1        | 0.93%   |
| MSI MS-7C37              | 1        | 0.93%   |
| MSI MS-7B86              | 1        | 0.93%   |
| MSI MS-7B84              | 1        | 0.93%   |
| MSI MS-7A15              | 1        | 0.93%   |
| MSI MS-7982              | 1        | 0.93%   |
| Medion H61H2-LM3         | 1        | 0.93%   |
| Lenovo 70F8S01J00        | 1        | 0.93%   |
| Intel X79                | 1        | 0.93%   |
| Intel DN2820FYK          | 1        | 0.93%   |
| Intel DH67CL             | 1        | 0.93%   |
| Intel D54250WYK          | 1        | 0.93%   |
| Huanan X99-8M-F          | 1        | 0.93%   |
| HP Z600                  | 1        | 0.93%   |
| HP Z420                  | 1        | 0.93%   |
| HP Z400                  | 1        | 0.93%   |
| HP Slim                  | 1        | 0.93%   |
| HP ProDesk               | 1        | 0.93%   |
| HP Desktop               | 1        | 0.93%   |
| HC HCAR357-MI            | 1        | 0.93%   |
| Gigabyte Z77X-UD5H       | 1        | 0.93%   |
| Gigabyte PH67A-D3-B3     | 1        | 0.93%   |
| Gigabyte HA65M-D2H-B3    | 1        | 0.93%   |
| Gigabyte H97-D3H         | 1        | 0.93%   |
| Gigabyte H61M-D2P-B3     | 1        | 0.93%   |
| Gigabyte H470M           | 1        | 0.93%   |
| Gigabyte H110-D3A        | 1        | 0.93%   |
| Gigabyte B360M-D3H       | 1        | 0.93%   |
| Gigabyte AX370-Gaming    | 1        | 0.93%   |
| Gigabyte A75M-DS2        | 1        | 0.93%   |
| Gigabyte 970A-DS3P       | 1        | 0.93%   |
| Foxconn RS880M06-8KRS3HX | 1        | 0.93%   |
| Foxconn Pro              | 1        | 0.93%   |
| Foxconn p6-2305elm       | 1        | 0.93%   |
| Foxconn p6-2171a         | 1        | 0.93%   |
| EVGA X299                | 1        | 0.93%   |
| Dell Inspiron            | 1        | 0.93%   |
| Biostar N68S3+           | 1        | 0.93%   |
| Biostar B450MH           | 1        | 0.93%   |
| Biostar B365MHC          | 1        | 0.93%   |
| Biostar A770E3           | 1        | 0.93%   |
| ASUS VM62                | 1        | 0.93%   |
| ASUS TUF                 | 1        | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 14       | 13.08%  |
| 2012 | 14       | 13.08%  |
| 2019 | 13       | 12.15%  |
| 2018 | 11       | 10.28%  |
| 2021 | 10       | 9.35%   |
| 2013 | 9        | 8.41%   |
| 2010 | 9        | 8.41%   |
| 2014 | 6        | 5.61%   |
| 2011 | 6        | 5.61%   |
| 2016 | 5        | 4.67%   |
| 2017 | 3        | 2.8%    |
| 2015 | 3        | 2.8%    |
| 2009 | 2        | 1.87%   |
| 2008 | 2        | 1.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 107      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 107      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 34       | 31.78%  |
| 16.01-24.0  | 32       | 29.91%  |
| 8.01-16.0   | 32       | 29.91%  |
| 32.01-64.0  | 7        | 6.54%   |
| 24.01-32.0  | 1        | 0.93%   |
| 64.01-256.0 | 1        | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 60       | 55.56%  |
| 0.51-1.0 | 32       | 29.63%  |
| 1.01-2.0 | 13       | 12.04%  |
| 2.01-3.0 | 2        | 1.85%   |
| 4.01-8.0 | 1        | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 49       | 44.95%  |
| 2      | 29       | 26.61%  |
| 3      | 11       | 10.09%  |
| 4      | 7        | 6.42%   |
| 0      | 7        | 6.42%   |
| 6      | 3        | 2.75%   |
| 10     | 1        | 0.92%   |
| 8      | 1        | 0.92%   |
| 5      | 1        | 0.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 65       | 60.75%  |
| Yes       | 42       | 39.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 105      | 98.13%  |
| No        | 2        | 1.87%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 68.52%  |
| Yes       | 34       | 31.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 77.57%  |
| Yes       | 24       | 22.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 18       | 16.82%  |
| UK          | 8        | 7.48%   |
| Russia      | 8        | 7.48%   |
| Canada      | 7        | 6.54%   |
| Germany     | 5        | 4.67%   |
| Ukraine     | 4        | 3.74%   |
| Italy       | 4        | 3.74%   |
| France      | 4        | 3.74%   |
| China       | 4        | 3.74%   |
| Brazil      | 4        | 3.74%   |
| Australia   | 4        | 3.74%   |
| Taiwan      | 3        | 2.8%    |
| South Korea | 3        | 2.8%    |
| Poland      | 2        | 1.87%   |
| Mexico      | 2        | 1.87%   |
| Finland     | 2        | 1.87%   |
| Argentina   | 2        | 1.87%   |
| Venezuela   | 1        | 0.93%   |
| Uruguay     | 1        | 0.93%   |
| Turkey      | 1        | 0.93%   |
| Thailand    | 1        | 0.93%   |
| Sweden      | 1        | 0.93%   |
| Spain       | 1        | 0.93%   |
| Slovakia    | 1        | 0.93%   |
| Portugal    | 1        | 0.93%   |
| Peru        | 1        | 0.93%   |
| Norway      | 1        | 0.93%   |
| New Zealand | 1        | 0.93%   |
| Netherlands | 1        | 0.93%   |
| Lithuania   | 1        | 0.93%   |
| Indonesia   | 1        | 0.93%   |
| India       | 1        | 0.93%   |
| Hungary     | 1        | 0.93%   |
| Guatemala   | 1        | 0.93%   |
| Greece      | 1        | 0.93%   |
| Eswatini    | 1        | 0.93%   |
| Egypt       | 1        | 0.93%   |
| Ecuador     | 1        | 0.93%   |
| Chile       | 1        | 0.93%   |
| Belarus     | 1        | 0.93%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| São Paulo             | 2        | 1.85%   |
| Dnipropetrovsk         | 2        | 1.85%   |
| Calgary                | 2        | 1.85%   |
| Brisbane               | 2        | 1.85%   |
| Šiauliai              | 1        | 0.93%   |
| Zhongshan              | 1        | 0.93%   |
| York                   | 1        | 0.93%   |
| Yekaterinburg          | 1        | 0.93%   |
| Yarang                 | 1        | 0.93%   |
| Winnipeg               | 1        | 0.93%   |
| Vladivostok            | 1        | 0.93%   |
| Villeurbanne           | 1        | 0.93%   |
| Vawkavysk              | 1        | 0.93%   |
| Ufa                    | 1        | 0.93%   |
| Trujillo               | 1        | 0.93%   |
| Treviso                | 1        | 0.93%   |
| Toronto                | 1        | 0.93%   |
| Tettnang Castle        | 1        | 0.93%   |
| Tampere                | 1        | 0.93%   |
| Taichung               | 1        | 0.93%   |
| Taganrog               | 1        | 0.93%   |
| Sydney                 | 1        | 0.93%   |
| Suzhou                 | 1        | 0.93%   |
| St Petersburg          | 1        | 0.93%   |
| Simpsonville           | 1        | 0.93%   |
| Sheffield              | 1        | 0.93%   |
| Sevastopol             | 1        | 0.93%   |
| Seoul                  | 1        | 0.93%   |
| S??o Paulo             | 1        | 0.93%   |
| San Francisco          | 1        | 0.93%   |
| Saint-Laurent-de-Ceris | 1        | 0.93%   |
| Rome                   | 1        | 0.93%   |
| Ransbach-Baumbach      | 1        | 0.93%   |
| Portsmouth             | 1        | 0.93%   |
| Porto                  | 1        | 0.93%   |
| Pflugerville           | 1        | 0.93%   |
| Paris                  | 1        | 0.93%   |
| Oslo                   | 1        | 0.93%   |
| Ortona                 | 1        | 0.93%   |
| Ogden                  | 1        | 0.93%   |
| North Vancouver        | 1        | 0.93%   |
| New York               | 1        | 0.93%   |
| New Taipei             | 1        | 0.93%   |
| Mumbai                 | 1        | 0.93%   |
| Mount Pleasant         | 1        | 0.93%   |
| Montevideo             | 1        | 0.93%   |
| Mokpo                  | 1        | 0.93%   |
| Minneapolis            | 1        | 0.93%   |
| Milton Keynes          | 1        | 0.93%   |
| Miami                  | 1        | 0.93%   |
| Mbabane                | 1        | 0.93%   |
| Marrickville           | 1        | 0.93%   |
| Mar del Plata          | 1        | 0.93%   |
| Mansfield              | 1        | 0.93%   |
| Mankato                | 1        | 0.93%   |
| Malton                 | 1        | 0.93%   |
| Malokaterynivka        | 1        | 0.93%   |
| London                 | 1        | 0.93%   |
| Langwedel              | 1        | 0.93%   |
| Kyiv                   | 1        | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 37       | 54     | 22.29%  |
| Seagate             | 30       | 49     | 18.07%  |
| Samsung Electronics | 27       | 36     | 16.27%  |
| Toshiba             | 8        | 8      | 4.82%   |
| Kingston            | 8        | 9      | 4.82%   |
| Hitachi             | 7        | 8      | 4.22%   |
| SanDisk             | 6        | 7      | 3.61%   |
| Intel               | 5        | 5      | 3.01%   |
| HGST                | 5        | 5      | 3.01%   |
| A-DATA Technology   | 5        | 9      | 3.01%   |
| Crucial             | 4        | 5      | 2.41%   |
| SPCC                | 2        | 3      | 1.2%    |
| SK Hynix            | 2        | 2      | 1.2%    |
| Silicon Motion      | 2        | 2      | 1.2%    |
| PNY                 | 2        | 9      | 1.2%    |
| Hewlett-Packard     | 2        | 2      | 1.2%    |
| Fujitsu             | 2        | 3      | 1.2%    |
| Apple               | 2        | 2      | 1.2%    |
| Apacer              | 2        | 2      | 1.2%    |
| Transcend           | 1        | 1      | 0.6%    |
| Phison              | 1        | 1      | 0.6%    |
| ORICO               | 1        | 2      | 0.6%    |
| LSI                 | 1        | 1      | 0.6%    |
| LITEON              | 1        | 1      | 0.6%    |
| Lenovo              | 1        | 1      | 0.6%    |
| KingSpec            | 1        | 1      | 0.6%    |
| CLOVER              | 1        | 1      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB        | 4        | 2.09%   |
| Seagate ST500DM002-1BD142 500GB  | 3        | 1.57%   |
| Seagate ST3250410AS 250GB        | 3        | 1.57%   |
| Samsung SSD 860 EVO 250GB        | 3        | 1.57%   |
| A-DATA SU650 120GB               | 3        | 1.57%   |
| WDC WD20EARS-00MVWB0 2TB         | 2        | 1.05%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 1.05%   |
| Seagate ST380815AS 80GB          | 2        | 1.05%   |
| Seagate ST3250318AS 250GB        | 2        | 1.05%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 1.05%   |
| HGST HTS725050A7E630 500GB       | 2        | 1.05%   |
| HGST HTS545032A7E380 320GB       | 2        | 1.05%   |
| A-DATA SX8200PNP 256GB           | 2        | 1.05%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.52%   |
| WDC WDS500G2B0A-00SM50 500GB     | 1        | 0.52%   |
| WDC WDS250G3X0C-00SJG0 250GB     | 1        | 0.52%   |
| WDC WDS250G1B0A-00H9H0 250GB     | 1        | 0.52%   |
| WDC WDS120G2G0A-00JH30 120GB     | 1        | 0.52%   |
| WDC WDS100T2B0A-00SM50 1TB       | 1        | 0.52%   |
| WDC WD800JD-55MUA1 80GB          | 1        | 0.52%   |
| WDC WD7500BPKX-00HPJT0 752GB     | 1        | 0.52%   |
| WDC WD6400AAKS-22A7B0 640GB      | 1        | 0.52%   |
| WDC WD5002ABYS-02B1B0 500GB      | 1        | 0.52%   |
| WDC WD5000BEVT-22ZAT0 500GB      | 1        | 0.52%   |
| WDC WD5000AZRX-00L4HB0 500GB     | 1        | 0.52%   |
| WDC WD5000ABYS-01TNA0 500GB      | 1        | 0.52%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.52%   |
| WDC WD5000AAKX-083CA1 500GB      | 1        | 0.52%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 0.52%   |
| WDC WD5000AAKS-00A7B2 500GB      | 1        | 0.52%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.52%   |
| WDC WD400BD-75LRA0 40GB          | 1        | 0.52%   |
| WDC WD4004FZWX-00GBGB0 4TB       | 1        | 0.52%   |
| WDC WD3200BEVT-00A0RT0 233GB     | 1        | 0.52%   |
| WDC WD3200BEKT-60PVMT0 320GB     | 1        | 0.52%   |
| WDC WD3200BEKT-08PVMT1 320GB     | 1        | 0.52%   |
| WDC WD3200AAJS-00L7A0 320GB      | 1        | 0.52%   |
| WDC WD3003FZEX-00Z4SA0 3TB       | 1        | 0.52%   |
| WDC WD3000JS-63PDB1 304GB        | 1        | 0.52%   |
| WDC WD2500YS-01SHB1 256GB        | 1        | 0.52%   |
| WDC WD2500BEVS-22UST0 250GB      | 1        | 0.52%   |
| WDC WD2500AAKX-083CA1 250GB      | 1        | 0.52%   |
| WDC WD2500AAJS-75M0A0 250GB      | 1        | 0.52%   |
| WDC WD1600AAJS-60WAA0 160GB      | 1        | 0.52%   |
| WDC WD1600AAJS-00WAA0 160GB      | 1        | 0.52%   |
| WDC WD10SPZX-00Z10T0 1TB         | 1        | 0.52%   |
| WDC WD10EZRX-00A8LB0 1TB         | 1        | 0.52%   |
| WDC WD10EZEX-08Y20A0 1TB         | 1        | 0.52%   |
| WDC WD10EARS-00Y5B1 1TB          | 1        | 0.52%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 1        | 0.52%   |
| WDC WD1001FALS-403AA0 1TB        | 1        | 0.52%   |
| WDC WD1001FALS-00J7B1 1TB        | 1        | 0.52%   |
| Transcend TS32GMTS400S 32GB      | 1        | 0.52%   |
| Toshiba THNSNK128GCS8 SATA 128GB | 1        | 0.52%   |
| Toshiba Q300 240GB               | 1        | 0.52%   |
| Toshiba MQ01ABF050M 500GB        | 1        | 0.52%   |
| Toshiba MK3276GSX 320GB          | 1        | 0.52%   |
| Toshiba MG04ACA200E 2TB          | 1        | 0.52%   |
| Toshiba KXG5AZNV256G 256GB       | 1        | 0.52%   |
| Toshiba DT01ACA300 3TB           | 1        | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 32       | 47     | 34.41%  |
| Seagate             | 30       | 49     | 32.26%  |
| Samsung Electronics | 10       | 12     | 10.75%  |
| Hitachi             | 7        | 8      | 7.53%   |
| Toshiba             | 5        | 5      | 5.38%   |
| HGST                | 5        | 5      | 5.38%   |
| Fujitsu             | 2        | 3      | 2.15%   |
| LSI                 | 1        | 1      | 1.08%   |
| CLOVER              | 1        | 1      | 1.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 17     | 24.07%  |
| Kingston            | 7        | 7      | 12.96%  |
| SanDisk             | 6        | 7      | 11.11%  |
| WDC                 | 4        | 5      | 7.41%   |
| Intel               | 3        | 3      | 5.56%   |
| Crucial             | 3        | 4      | 5.56%   |
| A-DATA Technology   | 3        | 3      | 5.56%   |
| Toshiba             | 2        | 2      | 3.7%    |
| SPCC                | 2        | 3      | 3.7%    |
| PNY                 | 2        | 7      | 3.7%    |
| Apple               | 2        | 2      | 3.7%    |
| Apacer              | 2        | 2      | 3.7%    |
| Transcend           | 1        | 1      | 1.85%   |
| ORICO               | 1        | 2      | 1.85%   |
| LITEON              | 1        | 1      | 1.85%   |
| Lenovo              | 1        | 1      | 1.85%   |
| KingSpec            | 1        | 1      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 75       | 131    | 52.08%  |
| SSD  | 46       | 68     | 31.94%  |
| NVMe | 23       | 30     | 15.97%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 97       | 199    | 80.83%  |
| NVMe | 23       | 30     | 19.17%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 84       | 134    | 65.12%  |
| 0.51-1.0   | 29       | 40     | 22.48%  |
| 1.01-2.0   | 8        | 12     | 6.2%    |
| 3.01-4.0   | 4        | 5      | 3.1%    |
| 2.01-3.0   | 2        | 5      | 1.55%   |
| 4.01-10.0  | 2        | 3      | 1.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 75       | 68.18%  |
| 101-250    | 14       | 12.73%  |
| 501-1000   | 9        | 8.18%   |
| 251-500    | 6        | 5.45%   |
| 51-100     | 3        | 2.73%   |
| 21-50      | 2        | 1.82%   |
| 1001-2000  | 1        | 0.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 107      | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST3250410AS 250GB         | 3        | 3      | 7.89%   |
| Seagate ST380815AS 80GB           | 2        | 2      | 5.26%   |
| HGST HTS545032A7E380 320GB        | 2        | 2      | 5.26%   |
| WDC WD800JD-55MUA1 80GB           | 1        | 1      | 2.63%   |
| WDC WD6400AAKS-22A7B0 640GB       | 1        | 1      | 2.63%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 1      | 2.63%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 2.63%   |
| WDC WD40EFRX-68WT0N0 4TB          | 1        | 1      | 2.63%   |
| WDC WD3200BEVT-00A0RT0 233GB      | 1        | 1      | 2.63%   |
| WDC WD3200AAJS-00L7A0 320GB       | 1        | 1      | 2.63%   |
| WDC WD2500AAKX-083CA1 250GB       | 1        | 1      | 2.63%   |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 1      | 2.63%   |
| WDC WD1600AAJS-60WAA0 160GB       | 1        | 1      | 2.63%   |
| WDC WD1600AAJS-00WAA0 160GB       | 1        | 1      | 2.63%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 2.63%   |
| Toshiba THNSNK128GCS8 SATA 128GB  | 1        | 1      | 2.63%   |
| Toshiba MK3276GSX 320GB           | 1        | 1      | 2.63%   |
| Seagate ST9500325AS 500GB         | 1        | 1      | 2.63%   |
| Seagate ST500VT000-1DK142 500GB   | 1        | 1      | 2.63%   |
| Seagate ST3500413AS 500GB         | 1        | 1      | 2.63%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 2.63%   |
| Seagate ST31000333AS 1TB          | 1        | 1      | 2.63%   |
| Samsung Electronics SP2004C 200GB | 1        | 1      | 2.63%   |
| Samsung Electronics HD642JJ 640GB | 1        | 1      | 2.63%   |
| Samsung Electronics HD321KJ 320GB | 1        | 1      | 2.63%   |
| Samsung Electronics HD161HJ 160GB | 1        | 1      | 2.63%   |
| Hitachi HTS727550A9E364 500GB     | 1        | 1      | 2.63%   |
| Hitachi HTS723232A7A364 320GB     | 1        | 1      | 2.63%   |
| Hitachi HDS721050CLA362 500GB     | 1        | 1      | 2.63%   |
| Hitachi HDP725025GLA380 250GB     | 1        | 1      | 2.63%   |
| HGST HTS725050A7E630 500GB        | 1        | 1      | 2.63%   |
| HGST HTS541010A9E680 1TB          | 1        | 1      | 2.63%   |
| Fujitsu MHZ2250BH G1 250GB        | 1        | 1      | 2.63%   |
| Crucial CT525MX300SSD1 528GB      | 1        | 2      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 12     | 32.43%  |
| Seagate             | 9        | 10     | 24.32%  |
| Samsung Electronics | 4        | 4      | 10.81%  |
| Hitachi             | 4        | 4      | 10.81%  |
| HGST                | 4        | 4      | 10.81%  |
| Toshiba             | 2        | 2      | 5.41%   |
| Fujitsu             | 1        | 1      | 2.7%    |
| Crucial             | 1        | 2      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 12     | 34.29%  |
| Seagate             | 9        | 10     | 25.71%  |
| Samsung Electronics | 4        | 4      | 11.43%  |
| Hitachi             | 4        | 4      | 11.43%  |
| HGST                | 4        | 4      | 11.43%  |
| Toshiba             | 1        | 1      | 2.86%   |
| Fujitsu             | 1        | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 31       | 36     | 93.94%  |
| SSD  | 2        | 3      | 6.06%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                      | Desktops | Drives | Percent |
|----------------------------|----------|--------|---------|
| HGST HTS725050A7E630 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| HGST   | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 79       | 177    | 66.39%  |
| Malfunc  | 33       | 39     | 27.73%  |
| Detected | 6        | 12     | 5.04%   |
| Failed   | 1        | 1      | 0.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 77       | 51.68%  |
| AMD                         | 29       | 19.46%  |
| Samsung Electronics         | 7        | 4.7%    |
| ASMedia Technology          | 6        | 4.03%   |
| Silicon Motion              | 4        | 2.68%   |
| Broadcom / LSI              | 4        | 2.68%   |
| VIA Technologies            | 2        | 1.34%   |
| SK Hynix                    | 2        | 1.34%   |
| Sandisk                     | 2        | 1.34%   |
| Phison Electronics          | 2        | 1.34%   |
| Nvidia                      | 2        | 1.34%   |
| Kingston Technology Company | 2        | 1.34%   |
| JMicron Technology          | 2        | 1.34%   |
| ADATA Technology            | 2        | 1.34%   |
| Adaptec                     | 2        | 1.34%   |
| Toshiba                     | 1        | 0.67%   |
| Silicon Image               | 1        | 0.67%   |
| Micron/Crucial Technology   | 1        | 0.67%   |
| Marvell Technology Group    | 1        | 0.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 7.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 5.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10       | 5.41%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 3.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 3.24%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 3.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 3.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 3.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 2.7%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4        | 2.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 1.62%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.62%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 1.62%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.62%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.62%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3        | 1.62%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 1.08%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 1.08%   |
| Nvidia MCP61 IDE                                                                        | 2        | 1.08%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.08%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.08%   |
| Intel SSD 660P Series                                                                   | 2        | 1.08%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 1.08%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 1.08%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 1.08%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 1.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.08%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 1.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.08%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 2        | 1.08%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2        | 1.08%   |
| Adaptec AIC-7850T/7856T [AVA-2902/4/6 / AHA-2910]                                       | 2        | 1.08%   |
| Toshiba unknown                                                                         | 1        | 0.54%   |
| SK Hynix PC300 NVMe Solid State Drive 256GB                                             | 1        | 0.54%   |
| SK Hynix Gold P31 SSD                                                                   | 1        | 0.54%   |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.54%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.54%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.54%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.54%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.54%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.54%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.54%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 0.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.54%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1        | 0.54%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.54%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.54%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.54%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 0.54%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 0.54%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 83       | 55.33%  |
| IDE  | 30       | 20%     |
| NVMe | 23       | 15.33%  |
| RAID | 8        | 5.33%   |
| SAS  | 3        | 2%      |
| SCSI | 3        | 2%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 76       | 71.03%  |
| AMD    | 31       | 28.97%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Xeon                                  | 4        | 3.74%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2.8%    |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 1.87%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.87%   |
| Intel Celeron CPU G3930 @ 2.90GHz           | 2        | 1.87%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 1.87%   |
| Intel Xeon CPU W3550 @ 3.07GHz              | 1        | 0.93%   |
| Intel Xeon CPU E5530 @ 2.40GHz              | 1        | 0.93%   |
| Intel Xeon CPU E5-2630L 0 @ 2.00GHz         | 1        | 0.93%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.93%   |
| Intel Xeon CPU E5-1603 @ 2.80GHz            | 1        | 0.93%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 0.93%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 0.93%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.93%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 0.93%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.93%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.93%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.93%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.93%   |
| Intel Pentium CPU G3460 @ 3.50GHz           | 1        | 0.93%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 1        | 0.93%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.93%   |
| Intel Pentium 4 CPU 3.60GHz                 | 1        | 0.93%   |
| Intel Genuine CPU 0000 @ 2.10GHz            | 1        | 0.93%   |
| Intel Core i9-7920X CPU @ 2.90GHz           | 1        | 0.93%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.93%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.93%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.93%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.93%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 0.93%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 0.93%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.93%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 0.93%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.93%   |
| Intel Core i5-7500T CPU @ 2.70GHz           | 1        | 0.93%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 0.93%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1        | 0.93%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1        | 0.93%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1        | 0.93%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 0.93%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 1        | 0.93%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 0.93%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 1        | 0.93%   |
| Intel Core i5-2500 CPU                      | 1        | 0.93%   |
| Intel Core i5-2400S CPU @ 2.50GH            | 1        | 0.93%   |
| Intel Core i5-2400S CPU                     | 1        | 0.93%   |
| Intel Core i5-10600 CPU @ 3.30GHz           | 1        | 0.93%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 0.93%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 0.93%   |
| Intel Core i3-9100F CPU @ 3.60GHz           | 1        | 0.93%   |
| Intel Core i3-6300 CPU @ 3.80GHz            | 1        | 0.93%   |
| Intel Core i3-4360 CPU @ 3.70GHz            | 1        | 0.93%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 1        | 0.93%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 1        | 0.93%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 1        | 0.93%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 0.93%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 0.93%   |
| Intel Core i3-2105 CPU                      | 1        | 0.93%   |
| Intel Core i3-2100T CPU @ 2.50GHz           | 1        | 0.93%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 1        | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 22       | 20.56%  |
| Intel Core i3           | 16       | 14.95%  |
| Intel Xeon              | 11       | 10.28%  |
| Intel Celeron           | 7        | 6.54%   |
| AMD Ryzen 5             | 6        | 5.61%   |
| Intel Core i7           | 5        | 4.67%   |
| AMD FX                  | 5        | 4.67%   |
| Intel Pentium Dual-Core | 4        | 3.74%   |
| Intel Pentium           | 4        | 3.74%   |
| Intel Core 2 Duo        | 3        | 2.8%    |
| AMD Ryzen 7             | 3        | 2.8%    |
| AMD Ryzen 3             | 3        | 2.8%    |
| AMD Ryzen 9             | 2        | 1.87%   |
| AMD Phenom II X4        | 2        | 1.87%   |
| AMD Athlon II X4        | 2        | 1.87%   |
| Intel Pentium Gold      | 1        | 0.93%   |
| Intel Pentium 4         | 1        | 0.93%   |
| Intel Genuine           | 1        | 0.93%   |
| Intel Core i9           | 1        | 0.93%   |
| AMD Sempron             | 1        | 0.93%   |
| AMD Phenom II X6        | 1        | 0.93%   |
| AMD E1                  | 1        | 0.93%   |
| AMD Athlon II X3        | 1        | 0.93%   |
| AMD Athlon II X2        | 1        | 0.93%   |
| AMD Athlon              | 1        | 0.93%   |
| AMD A6                  | 1        | 0.93%   |
| AMD A10                 | 1        | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 37       | 34.58%  |
| 2       | 34       | 31.78%  |
| 6       | 13       | 12.15%  |
| 8       | 9        | 8.41%   |
| 12      | 4        | 3.74%   |
| 16      | 3        | 2.8%    |
| Unknown | 3        | 2.8%    |
| 24      | 2        | 1.87%   |
| 3       | 1        | 0.93%   |
| 1       | 1        | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 104      | 97.2%   |
| 2      | 3        | 2.8%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 69       | 64.49%  |
| 2       | 35       | 32.71%  |
| Unknown | 3        | 2.8%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 14       | 13.08%  |
| SandyBridge   | 12       | 11.21%  |
| IvyBridge     | 10       | 9.35%   |
| Haswell       | 10       | 9.35%   |
| Penryn        | 8        | 7.48%   |
| K10           | 7        | 6.54%   |
| Zen 2         | 6        | 5.61%   |
| Skylake       | 5        | 4.67%   |
| Piledriver    | 5        | 4.67%   |
| CometLake     | 5        | 4.67%   |
| Zen+          | 4        | 3.74%   |
| Zen           | 4        | 3.74%   |
| Westmere      | 3        | 2.8%    |
| Nehalem       | 3        | 2.8%    |
| Silvermont    | 2        | 1.87%   |
| Bulldozer     | 2        | 1.87%   |
| Zen 3         | 1        | 0.93%   |
| NetBurst      | 1        | 0.93%   |
| K10 Llano     | 1        | 0.93%   |
| Goldmont plus | 1        | 0.93%   |
| Core          | 1        | 0.93%   |
| Broadwell     | 1        | 0.93%   |
| Bobcat        | 1        | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 52       | 46.85%  |
| Intel  | 31       | 27.93%  |
| AMD    | 28       | 25.23%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GP108 [GeForce GT 1030]                                                           | 6        | 5.41%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 6        | 5.41%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5        | 4.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5        | 4.5%    |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 3.6%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4        | 3.6%    |
| AMD Picasso                                                                              | 4        | 3.6%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 3        | 2.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3        | 2.7%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2        | 1.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 1.8%    |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2        | 1.8%    |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2        | 1.8%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2        | 1.8%    |
| Nvidia G92 [GeForce GTS 250]                                                             | 2        | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 1.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2        | 1.8%    |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 1.8%    |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 1.8%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.8%    |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 0.9%    |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 1        | 0.9%    |
| Nvidia NV43 [GeForce 6600]                                                               | 1        | 0.9%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.9%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 0.9%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.9%    |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                                     | 1        | 0.9%    |
| Nvidia GK107 [GeForce GT 740]                                                            | 1        | 0.9%    |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 0.9%    |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 0.9%    |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.9%    |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1        | 0.9%    |
| Nvidia GF119 [NVS 315]                                                                   | 1        | 0.9%    |
| Nvidia GF119 [GeForce GT 625 OEM]                                                        | 1        | 0.9%    |
| Nvidia GF108 [GeForce GT 630]                                                            | 1        | 0.9%    |
| Nvidia GF108 [GeForce GT 530]                                                            | 1        | 0.9%    |
| Nvidia GF106GL [Quadro 2000]                                                             | 1        | 0.9%    |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1        | 0.9%    |
| Nvidia G86 [Quadro NVS 290]                                                              | 1        | 0.9%    |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1        | 0.9%    |
| Nvidia G80GL [Quadro FX 5600]                                                            | 1        | 0.9%    |
| Intel HD Graphics 630                                                                    | 1        | 0.9%    |
| Intel HD Graphics 610                                                                    | 1        | 0.9%    |
| Intel HD Graphics 530                                                                    | 1        | 0.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1        | 0.9%    |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1        | 0.9%    |
| Intel Coffee Lake UHD 610 Graphics Controller                                            | 1        | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 0.9%    |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 1        | 0.9%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 0.9%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 0.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 0.9%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1        | 0.9%    |
| AMD Wrestler [Radeon HD 7310]                                                            | 1        | 0.9%    |
| AMD Whistler LE [Radeon HD 6610M/7610M]                                                  | 1        | 0.9%    |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 1        | 0.9%    |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                                        | 1        | 0.9%    |
| AMD RV670 [Radeon HD 3690/3850]                                                          | 1        | 0.9%    |
| AMD RV620 GL [FirePro 2260]                                                              | 1        | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 50       | 46.3%   |
| 1 x Intel    | 28       | 25.93%  |
| 1 x AMD      | 25       | 23.15%  |
| Intel + AMD  | 2        | 1.85%   |
| AMD + Nvidia | 2        | 1.85%   |
| 2 x Intel    | 1        | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 65       | 60.75%  |
| Proprietary | 31       | 28.97%  |
| Unknown     | 11       | 10.28%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 57       | 53.27%  |
| 1.01-2.0   | 19       | 17.76%  |
| 0.51-1.0   | 11       | 10.28%  |
| 3.01-4.0   | 8        | 7.48%   |
| 0.01-0.5   | 6        | 5.61%   |
| 7.01-8.0   | 2        | 1.87%   |
| 5.01-6.0   | 2        | 1.87%   |
| 2.01-3.0   | 2        | 1.87%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 21       | 25.61%  |
| Goldstar             | 11       | 13.41%  |
| Hewlett-Packard      | 8        | 9.76%   |
| Dell                 | 7        | 8.54%   |
| Acer                 | 4        | 4.88%   |
| ViewSonic            | 3        | 3.66%   |
| Iiyama               | 3        | 3.66%   |
| BenQ                 | 3        | 3.66%   |
| AOC                  | 3        | 3.66%   |
| Ancor Communications | 3        | 3.66%   |
| Vizio                | 1        | 1.22%   |
| VIE                  | 1        | 1.22%   |
| Videoseven           | 1        | 1.22%   |
| Toshiba              | 1        | 1.22%   |
| Sun                  | 1        | 1.22%   |
| Sony                 | 1        | 1.22%   |
| RS                   | 1        | 1.22%   |
| Philips              | 1        | 1.22%   |
| Medion               | 1        | 1.22%   |
| Lenovo               | 1        | 1.22%   |
| LED                  | 1        | 1.22%   |
| Insignia             | 1        | 1.22%   |
| Gateway              | 1        | 1.22%   |
| Fujitsu Siemens      | 1        | 1.22%   |
| CVT                  | 1        | 1.22%   |
| CAN                  | 1        | 1.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Vizio D32f-F1 VIZ1027 1920x1080 700x390mm 31.5-inch                    | 1        | 1.22%   |
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch                | 1        | 1.22%   |
| ViewSonic LCD Monitor VSCD824 1920x1080 520x290mm 23.4-inch            | 1        | 1.22%   |
| ViewSonic LCD Monitor VSC8724 1440x900 410x260mm 19.1-inch             | 1        | 1.22%   |
| VIE A/G2356 VIE2300 1920x1080 500x300mm 23.0-inch                      | 1        | 1.22%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1        | 1.22%   |
| Toshiba TV TSB0108 1360x768 480x270mm 21.7-inch                        | 1        | 1.22%   |
| Sun X7202A SUN0595 1280x1024 380x300mm 19.1-inch                       | 1        | 1.22%   |
| Sony TV SNYC901 1920x1080                                              | 1        | 1.22%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 700x390mm 31.5-inch      | 1        | 1.22%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 610x350mm 27.7-inch      | 1        | 1.22%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch      | 1        | 1.22%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch    | 1        | 1.22%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch    | 1        | 1.22%   |
| Samsung Electronics SyncMaster SAM03D7 1680x1050 470x300mm 22.0-inch   | 1        | 1.22%   |
| Samsung Electronics SyncMaster SAM0320 1680x1050 470x300mm 22.0-inch   | 1        | 1.22%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch   | 1        | 1.22%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 1        | 1.22%   |
| Samsung Electronics SE790C SAM0C62 2560x1080 700x310mm 30.1-inch       | 1        | 1.22%   |
| Samsung Electronics SA300/SA350 SAM078A 1366x768 410x230mm 18.5-inch   | 1        | 1.22%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 600x340mm 27.2-inch      | 1        | 1.22%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch      | 1        | 1.22%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch      | 1        | 1.22%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch   | 1        | 1.22%   |
| Samsung Electronics LCD Monitor SAM0F9F 3840x2160 1420x800mm 64.2-inch | 1        | 1.22%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 890x500mm 40.2-inch  | 1        | 1.22%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 700x390mm 31.5-inch  | 1        | 1.22%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch  | 1        | 1.22%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 530x300mm 24.0-inch     | 1        | 1.22%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch      | 1        | 1.22%   |
| RS LE2262 BTC2262 1680x1050 470x290mm 21.7-inch                        | 1        | 1.22%   |
| Philips LCD Monitor PHLC0B1 1920x1080 480x270mm 21.7-inch              | 1        | 1.22%   |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                    | 1        | 1.22%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                  | 1        | 1.22%   |
| LED 2250W LED2250 1920x1080 480x270mm 21.7-inch                        | 1        | 1.22%   |
| Insignia LCD Monitor BBY0050 1920x1080 700x400mm 31.7-inch             | 1        | 1.22%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                | 1        | 1.22%   |
| Iiyama PL4071UH IVM000A 3840x2160 880x490mm 39.7-inch                  | 1        | 1.22%   |
| Iiyama PL3270Q IVM7608 2560x1440 700x390mm 31.5-inch                   | 1        | 1.22%   |
| Hewlett-Packard Z27n G2 HPN348A 2560x1440 600x340mm 27.2-inch          | 1        | 1.22%   |
| Hewlett-Packard W2371b HWP3045 1920x1080 510x290mm 23.1-inch           | 1        | 1.22%   |
| Hewlett-Packard w20 HWP26AB 1680x1050 430x270mm 20.0-inch              | 1        | 1.22%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 410x260mm 19.1-inch             | 1        | 1.22%   |
| Hewlett-Packard LA1905 HWP2844 1440x900 410x260mm 19.1-inch            | 1        | 1.22%   |
| Hewlett-Packard 27er HWP3325 1920x1080 600x340mm 27.2-inch             | 1        | 1.22%   |
| Hewlett-Packard 2310e HWP2909 1920x1080 510x290mm 23.1-inch            | 1        | 1.22%   |
| Hewlett-Packard 2211 HWP2938 1920x1080 480x270mm 21.7-inch             | 1        | 1.22%   |
| Goldstar W2243 GSM56FE 1920x1080 480x270mm 21.7-inch                   | 1        | 1.22%   |
| Goldstar LG ULTRAWIDE GSM59F2 2560x1080 580x240mm 24.7-inch            | 1        | 1.22%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch             | 1        | 1.22%   |
| Goldstar LG QHD GSM772A 2560x1440 700x390mm 31.5-inch                  | 1        | 1.22%   |
| Goldstar LG HDR QHD GSM5B95 2560x1440 700x390mm 31.5-inch              | 1        | 1.22%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 1.22%   |
| Goldstar LG FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch              | 1        | 1.22%   |
| Goldstar LCD Monitor GSM76F5 1920x1080 700x390mm 31.5-inch             | 1        | 1.22%   |
| Goldstar L1753T GSM4477 1280x1024 340x270mm 17.1-inch                  | 1        | 1.22%   |
| Goldstar E1941 GSM4BF0 1366x768 410x230mm 18.5-inch                    | 1        | 1.22%   |
| Goldstar 19M35 GSM4C24 1366x768 410x230mm 18.5-inch                    | 1        | 1.22%   |
| Gateway FPD1775W GWY06B0 1280x1024 370x210mm 16.7-inch                 | 1        | 1.22%   |
| Fujitsu Siemens B19-6 LED FUS07F2 1280x1024 380x300mm 19.1-inch        | 1        | 1.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 30       | 37.04%  |
| 1680x1050 (WSXGA+) | 10       | 12.35%  |
| 3840x2160 (4K)     | 8        | 9.88%   |
| 1280x1024 (SXGA)   | 8        | 9.88%   |
| 1366x768 (WXGA)    | 7        | 8.64%   |
| 2560x1440 (QHD)    | 5        | 6.17%   |
| 1440x900 (WXGA+)   | 5        | 6.17%   |
| 2560x1080          | 3        | 3.7%    |
| 3440x1440          | 1        | 1.23%   |
| 2048x1152          | 1        | 1.23%   |
| 1600x900 (HD+)     | 1        | 1.23%   |
| 1360x768           | 1        | 1.23%   |
| 1024x768 (XGA)     | 1        | 1.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 13       | 16.05%  |
| 23      | 11       | 13.58%  |
| 21      | 11       | 13.58%  |
| 31      | 7        | 8.64%   |
| 27      | 7        | 8.64%   |
| 24      | 7        | 8.64%   |
| 18      | 7        | 8.64%   |
| 22      | 3        | 3.7%    |
| 20      | 3        | 3.7%    |
| 17      | 2        | 2.47%   |
| 64      | 1        | 1.23%   |
| 54      | 1        | 1.23%   |
| 40      | 1        | 1.23%   |
| 39      | 1        | 1.23%   |
| 34      | 1        | 1.23%   |
| 30      | 1        | 1.23%   |
| 28      | 1        | 1.23%   |
| 16      | 1        | 1.23%   |
| 14      | 1        | 1.23%   |
| Unknown | 1        | 1.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 34       | 41.98%  |
| 501-600     | 22       | 27.16%  |
| 601-700     | 10       | 12.35%  |
| 351-400     | 6        | 7.41%   |
| 801-900     | 2        | 2.47%   |
| 301-350     | 2        | 2.47%   |
| 1001-1500   | 2        | 2.47%   |
| 701-800     | 1        | 1.23%   |
| 201-300     | 1        | 1.23%   |
| Unknown     | 1        | 1.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 53       | 66.25%  |
| 16/10 | 14       | 17.5%   |
| 5/4   | 7        | 8.75%   |
| 21/9  | 4        | 5%      |
| 4/3   | 1        | 1.25%   |
| 3/2   | 1        | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 30       | 37.97%  |
| 151-200        | 16       | 20.25%  |
| 351-500        | 8        | 10.13%  |
| 301-350        | 8        | 10.13%  |
| 141-150        | 8        | 10.13%  |
| More than 1000 | 2        | 2.53%   |
| 251-300        | 2        | 2.53%   |
| 501-1000       | 2        | 2.53%   |
| 111-120        | 1        | 1.27%   |
| 101-110        | 1        | 1.27%   |
| Unknown        | 1        | 1.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 55       | 70.51%  |
| 101-120 | 18       | 23.08%  |
| 161-240 | 2        | 2.56%   |
| 121-160 | 2        | 2.56%   |
| Unknown | 1        | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 72       | 67.29%  |
| 0     | 30       | 28.04%  |
| 2     | 5        | 4.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 70       | 52.63%  |
| Intel                           | 34       | 25.56%  |
| Broadcom                        | 9        | 6.77%   |
| Qualcomm Atheros                | 7        | 5.26%   |
| Ralink                          | 4        | 3.01%   |
| Ralink Technology               | 2        | 1.5%    |
| Qualcomm Atheros Communications | 1        | 0.75%   |
| Mellanox Technologies           | 1        | 0.75%   |
| Marvell Technology Group        | 1        | 0.75%   |
| D-Link System                   | 1        | 0.75%   |
| D-Link                          | 1        | 0.75%   |
| ASUSTek Computer                | 1        | 0.75%   |
| 3Com                            | 1        | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 65       | 44.52%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6        | 4.11%   |
| Intel Ethernet Connection (7) I219-V                                       | 5        | 3.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3        | 2.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3        | 2.05%   |
| Intel I211 Gigabit Network Connection                                      | 3        | 2.05%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 2.05%   |
| Intel 82579V Gigabit Network Connection                                    | 3        | 2.05%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                     | 2        | 1.37%   |
| Intel Wireless 7260                                                        | 2        | 1.37%   |
| Intel Wi-Fi 6 AX200                                                        | 2        | 1.37%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2        | 1.37%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 2        | 1.37%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.68%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 0.68%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1        | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1        | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1        | 0.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1        | 0.68%   |
| Ralink RT5370 Wireless Adapter                                             | 1        | 0.68%   |
| Ralink MT7601U Wireless Adapter                                            | 1        | 0.68%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                | 1        | 0.68%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                  | 1        | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1        | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.68%   |
| Qualcomm Atheros AR9271 802.11n                                            | 1        | 0.68%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                              | 1        | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 1        | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 0.68%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.68%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]     | 1        | 0.68%   |
| Mellanox MT27500 Family [ConnectX-3]                                       | 1        | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 1        | 0.68%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                          | 1        | 0.68%   |
| Intel Wireless-AC 9260                                                     | 1        | 0.68%   |
| Intel Wireless 3165                                                        | 1        | 0.68%   |
| Intel Wireless 3160                                                        | 1        | 0.68%   |
| Intel Ethernet Connection I218-V                                           | 1        | 0.68%   |
| Intel Ethernet Connection I217-V                                           | 1        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                                       | 1        | 0.68%   |
| Intel Ethernet Connection (2) I218-V                                       | 1        | 0.68%   |
| Intel Ethernet Connection (12) I219-V                                      | 1        | 0.68%   |
| Intel Ethernet Connection (11) I219-V                                      | 1        | 0.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 1        | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 1        | 0.68%   |
| Intel 82583V Gigabit Network Connection                                    | 1        | 0.68%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 1        | 0.68%   |
| Intel 82562V-2 10/100 Network Connection                                   | 1        | 0.68%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                       | 1        | 0.68%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1        | 0.68%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.B1) [Ralink RT5370]              | 1        | 0.68%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                           | 1        | 0.68%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                    | 1        | 0.68%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 1        | 0.68%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1        | 0.68%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 1        | 0.68%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                  | 1        | 0.68%   |
| 3Com 3c940 10/100/1000Base-T [Marvell]                                     | 1        | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 11       | 30.56%  |
| Intel                           | 9        | 25%     |
| Ralink                          | 4        | 11.11%  |
| Qualcomm Atheros                | 4        | 11.11%  |
| Ralink Technology               | 2        | 5.56%   |
| Broadcom                        | 2        | 5.56%   |
| Qualcomm Atheros Communications | 1        | 2.78%   |
| D-Link System                   | 1        | 2.78%   |
| D-Link                          | 1        | 2.78%   |
| ASUSTek Computer                | 1        | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3        | 8.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3        | 8.33%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                     | 2        | 5.56%   |
| Intel Wireless 7260                                                        | 2        | 5.56%   |
| Intel Wi-Fi 6 AX200                                                        | 2        | 5.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 2.78%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 2.78%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1        | 2.78%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1        | 2.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1        | 2.78%   |
| Ralink RT5370 Wireless Adapter                                             | 1        | 2.78%   |
| Ralink MT7601U Wireless Adapter                                            | 1        | 2.78%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                | 1        | 2.78%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                  | 1        | 2.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1        | 2.78%   |
| Qualcomm Atheros AR9271 802.11n                                            | 1        | 2.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 1        | 2.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 2.78%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]     | 1        | 2.78%   |
| Intel Wireless-AC 9260                                                     | 1        | 2.78%   |
| Intel Wireless 3165                                                        | 1        | 2.78%   |
| Intel Wireless 3160                                                        | 1        | 2.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 1        | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 1        | 2.78%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1        | 2.78%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.B1) [Ralink RT5370]              | 1        | 2.78%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1        | 2.78%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 1        | 2.78%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                  | 1        | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 66       | 62.26%  |
| Intel                    | 29       | 27.36%  |
| Broadcom                 | 7        | 6.6%    |
| Qualcomm Atheros         | 3        | 2.83%   |
| Marvell Technology Group | 1        | 0.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 65       | 60.19%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 5.56%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 4.63%   |
| Intel I211 Gigabit Network Connection                             | 3        | 2.78%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.78%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 2.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2        | 1.85%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 1.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.93%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.93%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.93%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.93%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.93%   |
| Intel Ethernet Connection I218-V                                  | 1        | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.93%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 0.93%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.93%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.93%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.93%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.93%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.93%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.93%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 0.93%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.93%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 0.93%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 105      | 75%     |
| WiFi     | 33       | 23.57%  |
| Unknown  | 2        | 1.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 104      | 80%     |
| WiFi     | 24       | 18.46%  |
| Unknown  | 2        | 1.54%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 77       | 71.3%   |
| 2     | 27       | 25%     |
| 3     | 3        | 2.78%   |
| 0     | 1        | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 106      | 98.15%  |
| Yes  | 2        | 1.85%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 28%     |
| Cambridge Silicon Radio         | 5        | 20%     |
| Realtek Semiconductor           | 3        | 12%     |
| Broadcom                        | 3        | 12%     |
| ASUSTek Computer                | 3        | 12%     |
| Qualcomm Atheros Communications | 1        | 4%      |
| Integrated System Solution      | 1        | 4%      |
| Edimax Technology               | 1        | 4%      |
| Apple                           | 1        | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 5        | 20%     |
| Intel Bluetooth wireless interface                      | 3        | 12%     |
| Realtek  Bluetooth 4.2 Adapter                          | 2        | 8%      |
| Intel AX200 Bluetooth                                   | 2        | 8%      |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 2        | 8%      |
| Realtek  Bluetooth Adapter                              | 1        | 4%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                   | 1        | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 1        | 4%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1        | 4%      |
| Integrated System Solution Bluetooth Device             | 1        | 4%      |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1        | 4%      |
| Broadcom Bluetooth Device                               | 1        | 4%      |
| Broadcom Bluetooth 2.0+eDR dongle                       | 1        | 4%      |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 1        | 4%      |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip            | 1        | 4%      |
| Apple Apple Broadcom Built-in Bluetooth                 | 1        | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 76       | 44.19%  |
| Nvidia                      | 46       | 26.74%  |
| AMD                         | 38       | 22.09%  |
| Texas Instruments           | 2        | 1.16%   |
| C-Media Electronics         | 2        | 1.16%   |
| XMOS                        | 1        | 0.58%   |
| Steinberg Soft-und Hardware | 1        | 0.58%   |
| SteelSeries ApS             | 1        | 0.58%   |
| Realtek Semiconductor       | 1        | 0.58%   |
| Logitech                    | 1        | 0.58%   |
| Ensoniq                     | 1        | 0.58%   |
| Creative Technology         | 1        | 0.58%   |
| Creative Labs               | 1        | 0.58%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13       | 6.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11       | 5.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7        | 3.61%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 7        | 3.61%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 6        | 3.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6        | 3.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6        | 3.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6        | 3.09%   |
| Intel 200 Series PCH HD Audio                                                                     | 6        | 3.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6        | 3.09%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5        | 2.58%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5        | 2.58%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5        | 2.58%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4        | 2.06%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 4        | 2.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4        | 2.06%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller                                    | 4        | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4        | 2.06%   |
| Nvidia High Definition Audio Controller                                                           | 3        | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3        | 1.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3        | 1.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3        | 1.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3        | 1.55%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3        | 1.55%   |
| Nvidia MCP61 High Definition Audio                                                                | 2        | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 1.03%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 1.03%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2        | 1.03%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2        | 1.03%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2        | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2        | 1.03%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2        | 1.03%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2        | 1.03%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2        | 1.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2        | 1.03%   |
| Intel 8 Series HD Audio Controller                                                                | 2        | 1.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2        | 1.03%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2        | 1.03%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2        | 1.03%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 1.03%   |
| AMD FCH Azalia Controller                                                                         | 2        | 1.03%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 1.03%   |
| XMOS Cyberdrive Audio Driver                                                                      | 1        | 0.52%   |
| Texas Instruments SMSL Q5 AMP                                                                     | 1        | 0.52%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1        | 0.52%   |
| Steinberg Soft-und Hardware MI4                                                                   | 1        | 0.52%   |
| SteelSeries ApS Arctis 7 wireless adapter                                                         | 1        | 0.52%   |
| Realtek Semiconductor Realtek Audio USB Realtek Audio USB Microphone                              | 1        | 0.52%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 0.52%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1        | 0.52%   |
| Logitech HD Webcam C910                                                                           | 1        | 0.52%   |
| Intel USB PnP Sound Device                                                                        | 1        | 0.52%   |
| Intel Comet Lake PCH cAVS                                                                         | 1        | 0.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1        | 0.52%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1        | 0.52%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1        | 0.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 0.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1        | 0.52%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1        | 0.52%   |
| Intel 631xESB/632xESB High Definition Audio Controller                                            | 1        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 22       | 17.19%  |
| Kingston                   | 22       | 17.19%  |
| Crucial                    | 17       | 13.28%  |
| SK Hynix                   | 12       | 9.38%   |
| Samsung Electronics        | 11       | 8.59%   |
| Micron Technology          | 10       | 7.81%   |
| G.Skill                    | 7        | 5.47%   |
| Corsair                    | 6        | 4.69%   |
| Nanya Technology           | 3        | 2.34%   |
| Team                       | 2        | 1.56%   |
| Ramaxel Technology         | 2        | 1.56%   |
| PNY                        | 2        | 1.56%   |
| Elpida                     | 2        | 1.56%   |
| Avant                      | 2        | 1.56%   |
| AMD                        | 2        | 1.56%   |
| Unknown (7F7F7F94FFFFFFFF) | 1        | 0.78%   |
| Unknown (09A4)             | 1        | 0.78%   |
| Patriot                    | 1        | 0.78%   |
| Goldkey                    | 1        | 0.78%   |
| Apacer                     | 1        | 0.78%   |
| A-DATA Technology          | 1        | 0.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 1333MT/s                               | 4        | 2.84%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                               | 3        | 2.13%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s                | 2        | 1.42%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s               | 2        | 1.42%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s                  | 2        | 1.42%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                | 2        | 1.42%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s                 | 2        | 1.42%   |
| Unknown RAM TMKS8G68ALFBCH-266 8192MB SODIMM DDR4 2400MT/s         | 1        | 0.71%   |
| Unknown RAM R9P5316-007.A02LF 2GB DIMM 533MT/s                     | 1        | 0.71%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                          | 1        | 0.71%   |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                          | 1        | 0.71%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                               | 1        | 0.71%   |
| Unknown RAM Module 4GB DIMM DDR3 1866MT/s                          | 1        | 0.71%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                           | 1        | 0.71%   |
| Unknown RAM Module 4GB DIMM 667MT/s                                | 1        | 0.71%   |
| Unknown RAM Module 4096MB DIMM DDR2                                | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM SDRAM                                  | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                           | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                           | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM 533MT/s                                | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                               | 1        | 0.71%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                       | 1        | 0.71%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                        | 1        | 0.71%   |
| Unknown RAM Module 2048MB DIMM DDR2                                | 1        | 0.71%   |
| Unknown RAM Module 1GB DIMM 1333MT/s                               | 1        | 0.71%   |
| Unknown RAM Module 1024MB DIMM SDRAM 667MT/s                       | 1        | 0.71%   |
| Unknown RAM 7TE39AA# 8GB DIMM DDR4 2667MT/s                        | 1        | 0.71%   |
| Unknown (7F7F7F94FFFFFFFF) RAM 996593PCGH 2048MB DIMM DDR2 800MT/s | 1        | 0.71%   |
| Unknown (09A4) RAM 08S2400CL170H 8192MB DIMM DDR4 2133MT/s         | 1        | 0.71%   |
| Team RAM TEAMGROUP-UD4-3000 4GB DIMM DDR4 2400MT/s                 | 1        | 0.71%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s                 | 1        | 0.71%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1066MT/s                         | 1        | 0.71%   |
| SK Hynix RAM HYMP525F72CP4N3-Y5 2048MB FB-DIMM DDR2 533MT/s        | 1        | 0.71%   |
| SK Hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s               | 1        | 0.71%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s               | 1        | 0.71%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s               | 1        | 0.71%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s               | 1        | 0.71%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s               | 1        | 0.71%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s               | 1        | 0.71%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s             | 1        | 0.71%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s               | 1        | 0.71%   |
| SK Hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s               | 1        | 0.71%   |
| SK Hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s               | 1        | 0.71%   |
| SK Hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s               | 1        | 0.71%   |
| SK Hynix RAM HMT125U6BFR8C-H9 2048MB DIMM DDR3 1333MT/s            | 1        | 0.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s              | 1        | 0.71%   |
| Samsung RAM M391B5673EH1-CF8 2GB DIMM DDR3 1066MT/s                | 1        | 0.71%   |
| Samsung RAM M391B5273DH0-YH9 4096MB DIMM DDR3 1333MT/s             | 1        | 0.71%   |
| Samsung RAM M378B5773QB0-CK0 2GB DIMM DDR3 1600MT/s                | 1        | 0.71%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                | 1        | 0.71%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s                | 1        | 0.71%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s                | 1        | 0.71%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s                | 1        | 0.71%   |
| Samsung RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1333MT/s                | 1        | 0.71%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 2400MT/s                | 1        | 0.71%   |
| Samsung RAM M378A1G43TB1-CTD 8192MB DIMM DDR4 3200MT/s             | 1        | 0.71%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s                | 1        | 0.71%   |
| Ramaxel RAM RMUA5110MD78HAF-2666 8GB DIMM DDR4 2667MT/s            | 1        | 0.71%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s              | 1        | 0.71%   |
| PNY RAM 8GBF1X08QFHH38-135 8GB DIMM DDR4 2133MT/s                  | 1        | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 44       | 40.74%  |
| DDR4    | 42       | 38.89%  |
| Unknown | 11       | 10.19%  |
| DDR2    | 7        | 6.48%   |
| SDRAM   | 3        | 2.78%   |
| DDR     | 1        | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 99       | 92.52%  |
| SODIMM  | 7        | 6.54%   |
| FB-DIMM | 1        | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 48       | 37.21%  |
| 8192  | 37       | 28.68%  |
| 2048  | 31       | 24.03%  |
| 16384 | 7        | 5.43%   |
| 1024  | 5        | 3.88%   |
| 32768 | 1        | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 25       | 21.01%  |
| 1333    | 22       | 18.49%  |
| 2400    | 13       | 10.92%  |
| 2667    | 12       | 10.08%  |
| 2133    | 11       | 9.24%   |
| 800     | 6        | 5.04%   |
| 667     | 6        | 5.04%   |
| 3200    | 5        | 4.2%    |
| 2666    | 5        | 4.2%    |
| 533     | 3        | 2.52%   |
| 2933    | 2        | 1.68%   |
| 1866    | 2        | 1.68%   |
| 1066    | 2        | 1.68%   |
| Unknown | 2        | 1.68%   |
| 1867    | 1        | 0.84%   |
| 1800    | 1        | 0.84%   |
| 1400    | 1        | 0.84%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 4        | 57.14%  |
| Lexmark International | 2        | 28.57%  |
| Seiko Epson           | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed)        | 1        | 12.5%   |
| Lexmark International SINDOH A603_A608 Print | 1        | 12.5%   |
| Lexmark International Lexmark MS710 Print    | 1        | 12.5%   |
| HP LaserJet 2200                             | 1        | 12.5%   |
| HP LaserJet 1200                             | 1        | 12.5%   |
| HP HP LaserJet P2035 HP Print                | 1        | 12.5%   |
| HP DeskJet 5850c                             | 1        | 12.5%   |
| HP Color LaserJet CP1215                     | 1        | 12.5%   |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Microdia               | 1        | 16.67%  |
| Logitech               | 1        | 16.67%  |
| Hewlett-Packard        | 1        | 16.67%  |
| Generalplus Technology | 1        | 16.67%  |
| GEMBIRD                | 1        | 16.67%  |
| A4Tech                 | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Microdia ASUS USB2.0 Webcam                       | 1        | 16.67%  |
| Logitech Webcam C270                              | 1        | 16.67%  |
| HP Premium Starter Webcam                         | 1        | 16.67%  |
| Generalplus GENERAL WEBCAM                        | 1        | 16.67%  |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 16.67%  |
| A4Tech A4tech FHD 1080P PC Camera                 | 1        | 16.67%  |

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
| 1     | 53       | 49.07%  |
| 0     | 41       | 37.96%  |
| 2     | 11       | 10.19%  |
| 3     | 2        | 1.85%   |
| 4     | 1        | 0.93%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 57       | 69.51%  |
| Net/wireless             | 14       | 17.07%  |
| Firewire controller      | 4        | 4.88%   |
| Bluetooth                | 3        | 3.66%   |
| Sound                    | 2        | 2.44%   |
| Storage/raid             | 1        | 1.22%   |
| Card reader              | 1        | 1.22%   |

