helloSystem 0.5.0 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.5.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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
| MSI           | B450 TOMAHAWK MAX           | [14f1956220](https://bsd-hardware.info/?probe=14f1956220) | Dec 04, 2021 |
| Dell          | 0DR845                      | [4d07453a93](https://bsd-hardware.info/?probe=4d07453a93) | Nov 27, 2021 |
| Biostar       | B365MHC                     | [0c059bab3f](https://bsd-hardware.info/?probe=0c059bab3f) | Nov 11, 2021 |
| ASUSTek       | F2A85-M                     | [b4e3f33e5c](https://bsd-hardware.info/?probe=b4e3f33e5c) | Oct 14, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [b3b31d25b0](https://bsd-hardware.info/?probe=b3b31d25b0) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [5a7c1871b1](https://bsd-hardware.info/?probe=5a7c1871b1) | Oct 11, 2021 |
| Acer          | Aspire TC-780               | [77101a00b3](https://bsd-hardware.info/?probe=77101a00b3) | Oct 11, 2021 |
| ASUSTek       | D940MX                      | [4e798f3ef0](https://bsd-hardware.info/?probe=4e798f3ef0) | Oct 10, 2021 |
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
| amd64 | 113      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 113      | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 113      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 113      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 111      | 97.37%  |
| it_IT | 1        | 0.88%   |
| es_ES | 1        | 0.88%   |
| es_AR | 1        | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 89       | 78.76%  |
| BIOS | 24       | 21.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 113      | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 113      | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 35       | 30.97%  |
| Gigabyte Technology | 11       | 9.73%   |
| ASRock              | 11       | 9.73%   |
| Dell                | 10       | 8.85%   |
| Hewlett-Packard     | 8        | 7.08%   |
| MSI                 | 7        | 6.19%   |
| Lenovo              | 5        | 4.42%   |
| Biostar             | 5        | 4.42%   |
| Intel               | 4        | 3.54%   |
| Foxconn             | 4        | 3.54%   |
| Pegatron            | 2        | 1.77%   |
| Acer                | 2        | 1.77%   |
| Shuttle             | 1        | 0.88%   |
| Protectli           | 1        | 0.88%   |
| PCPartner           | 1        | 0.88%   |
| Packard Bell        | 1        | 0.88%   |
| Medion              | 1        | 0.88%   |
| Huanan              | 1        | 0.88%   |
| HC                  | 1        | 0.88%   |
| EVGA                | 1        | 0.88%   |
| Unknown             | 1        | 0.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell OptiPlex 755                   | 2        | 1.77%   |
| Biostar B365MHC                     | 2        | 1.77%   |
| ASUS All Series                     | 2        | 1.77%   |
| ASRock B550M Pro4                   | 2        | 1.77%   |
| ASRock B450M Pro4                   | 2        | 1.77%   |
| Shuttle NC10U                       | 1        | 0.88%   |
| Protectli FW2B                      | 1        | 0.88%   |
| Pegatron SAISHIAT2                  | 1        | 0.88%   |
| Pegatron IPM41-D3                   | 1        | 0.88%   |
| PCPartner DREAMSYS                  | 1        | 0.88%   |
| Packard Bell imedia S2110           | 1        | 0.88%   |
| MSI WC791AA-UUW HPE-119sc           | 1        | 0.88%   |
| MSI MS-7C37                         | 1        | 0.88%   |
| MSI MS-7C02                         | 1        | 0.88%   |
| MSI MS-7B86                         | 1        | 0.88%   |
| MSI MS-7B84                         | 1        | 0.88%   |
| MSI MS-7A15                         | 1        | 0.88%   |
| MSI MS-7982                         | 1        | 0.88%   |
| Medion H61H2-LM3                    | 1        | 0.88%   |
| Lenovo ThinkCentre M91p 7033DE6     | 1        | 0.88%   |
| Lenovo ThinkCentre M91p 7033D54     | 1        | 0.88%   |
| Lenovo ThinkCentre M83 10AHS35Q00   | 1        | 0.88%   |
| Lenovo ThinkCentre M720s 10SUS4WT00 | 1        | 0.88%   |
| Lenovo 70F8S01J00 ThinkServer RS140 | 1        | 0.88%   |
| Intel X79 V2.72A                    | 1        | 0.88%   |
| Intel DN2820FYK H24582-201          | 1        | 0.88%   |
| Intel DH67CL AAG10212-206           | 1        | 0.88%   |
| Intel D54250WYK H13922-304          | 1        | 0.88%   |
| Huanan X99-8M-F V1.2                | 1        | 0.88%   |
| HP Z600 Workstation                 | 1        | 0.88%   |
| HP Z420 Workstation                 | 1        | 0.88%   |
| HP Z400 Workstation                 | 1        | 0.88%   |
| HP Slim Desktop S01-pF1xxx          | 1        | 0.88%   |
| HP ProDesk 600 G1 SFF               | 1        | 0.88%   |
| HP Desktop M01-F1xxx                | 1        | 0.88%   |
| HP Compaq Elite 8300 SFF            | 1        | 0.88%   |
| HP Compaq dc5700 Small Form Factor  | 1        | 0.88%   |
| HC HCAR357-MI                       | 1        | 0.88%   |
| Gigabyte Z77X-UD5H                  | 1        | 0.88%   |
| Gigabyte PH67A-D3-B3                | 1        | 0.88%   |
| Gigabyte HA65M-D2H-B3               | 1        | 0.88%   |
| Gigabyte H97-D3H                    | 1        | 0.88%   |
| Gigabyte H61M-D2P-B3                | 1        | 0.88%   |
| Gigabyte H470M DS3H                 | 1        | 0.88%   |
| Gigabyte H110-D3A                   | 1        | 0.88%   |
| Gigabyte B360M-D3H                  | 1        | 0.88%   |
| Gigabyte AX370-Gaming               | 1        | 0.88%   |
| Gigabyte A75M-DS2                   | 1        | 0.88%   |
| Gigabyte 970A-DS3P                  | 1        | 0.88%   |
| Foxconn RS880M06-8KRS3HX            | 1        | 0.88%   |
| Foxconn Pro 3500 Series             | 1        | 0.88%   |
| Foxconn p6-2305elm                  | 1        | 0.88%   |
| Foxconn p6-2171a                    | 1        | 0.88%   |
| EVGA X299 MICRO                     | 1        | 0.88%   |
| Dell Precision WorkStation T7400    | 1        | 0.88%   |
| Dell Precision WorkStation T5500    | 1        | 0.88%   |
| Dell Precision WorkStation T3500    | 1        | 0.88%   |
| Dell OptiPlex 990                   | 1        | 0.88%   |
| Dell OptiPlex 7010                  | 1        | 0.88%   |
| Dell OptiPlex 5055 Ryzen CPU        | 1        | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| Dell OptiPlex            | 6        | 5.31%   |
| ASUS PRIME               | 5        | 4.42%   |
| Lenovo ThinkCentre       | 4        | 3.54%   |
| Dell Precision           | 3        | 2.65%   |
| ASUS M5A78L-M            | 3        | 2.65%   |
| HP Compaq                | 2        | 1.77%   |
| Biostar B365MHC          | 2        | 1.77%   |
| ASUS ROG                 | 2        | 1.77%   |
| ASUS P8Z77-V             | 2        | 1.77%   |
| ASUS All                 | 2        | 1.77%   |
| ASRock B550M             | 2        | 1.77%   |
| ASRock B450M             | 2        | 1.77%   |
| Acer Aspire              | 2        | 1.77%   |
| Shuttle NC10U            | 1        | 0.88%   |
| Protectli FW2B           | 1        | 0.88%   |
| Pegatron SAISHIAT2       | 1        | 0.88%   |
| Pegatron IPM41-D3        | 1        | 0.88%   |
| PCPartner DREAMSYS       | 1        | 0.88%   |
| Packard Bell imedia      | 1        | 0.88%   |
| MSI WC791AA-UUW          | 1        | 0.88%   |
| MSI MS-7C37              | 1        | 0.88%   |
| MSI MS-7C02              | 1        | 0.88%   |
| MSI MS-7B86              | 1        | 0.88%   |
| MSI MS-7B84              | 1        | 0.88%   |
| MSI MS-7A15              | 1        | 0.88%   |
| MSI MS-7982              | 1        | 0.88%   |
| Medion H61H2-LM3         | 1        | 0.88%   |
| Lenovo 70F8S01J00        | 1        | 0.88%   |
| Intel X79                | 1        | 0.88%   |
| Intel DN2820FYK          | 1        | 0.88%   |
| Intel DH67CL             | 1        | 0.88%   |
| Intel D54250WYK          | 1        | 0.88%   |
| Huanan X99-8M-F          | 1        | 0.88%   |
| HP Z600                  | 1        | 0.88%   |
| HP Z420                  | 1        | 0.88%   |
| HP Z400                  | 1        | 0.88%   |
| HP Slim                  | 1        | 0.88%   |
| HP ProDesk               | 1        | 0.88%   |
| HP Desktop               | 1        | 0.88%   |
| HC HCAR357-MI            | 1        | 0.88%   |
| Gigabyte Z77X-UD5H       | 1        | 0.88%   |
| Gigabyte PH67A-D3-B3     | 1        | 0.88%   |
| Gigabyte HA65M-D2H-B3    | 1        | 0.88%   |
| Gigabyte H97-D3H         | 1        | 0.88%   |
| Gigabyte H61M-D2P-B3     | 1        | 0.88%   |
| Gigabyte H470M           | 1        | 0.88%   |
| Gigabyte H110-D3A        | 1        | 0.88%   |
| Gigabyte B360M-D3H       | 1        | 0.88%   |
| Gigabyte AX370-Gaming    | 1        | 0.88%   |
| Gigabyte A75M-DS2        | 1        | 0.88%   |
| Gigabyte 970A-DS3P       | 1        | 0.88%   |
| Foxconn RS880M06-8KRS3HX | 1        | 0.88%   |
| Foxconn Pro              | 1        | 0.88%   |
| Foxconn p6-2305elm       | 1        | 0.88%   |
| Foxconn p6-2171a         | 1        | 0.88%   |
| EVGA X299                | 1        | 0.88%   |
| Dell Inspiron            | 1        | 0.88%   |
| Biostar N68S3+           | 1        | 0.88%   |
| Biostar B450MH           | 1        | 0.88%   |
| Biostar A770E3           | 1        | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 17       | 15.04%  |
| 2012 | 15       | 13.27%  |
| 2019 | 14       | 12.39%  |
| 2013 | 12       | 10.62%  |
| 2018 | 11       | 9.73%   |
| 2010 | 8        | 7.08%   |
| 2014 | 7        | 6.19%   |
| 2021 | 6        | 5.31%   |
| 2011 | 6        | 5.31%   |
| 2017 | 4        | 3.54%   |
| 2016 | 4        | 3.54%   |
| 2008 | 4        | 3.54%   |
| 2015 | 2        | 1.77%   |
| 2009 | 2        | 1.77%   |
| 2007 | 1        | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 113      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 113      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 36       | 31.86%  |
| 16.01-24.0  | 34       | 30.09%  |
| 8.01-16.0   | 33       | 29.2%   |
| 32.01-64.0  | 7        | 6.19%   |
| 64.01-256.0 | 2        | 1.77%   |
| 24.01-32.0  | 1        | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 62       | 54.39%  |
| 0.51-1.0 | 34       | 29.82%  |
| 1.01-2.0 | 15       | 13.16%  |
| 2.01-3.0 | 2        | 1.75%   |
| 4.01-8.0 | 1        | 0.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 51       | 44.35%  |
| 2      | 30       | 26.09%  |
| 3      | 13       | 11.3%   |
| 0      | 7        | 6.09%   |
| 4      | 6        | 5.22%   |
| 6      | 3        | 2.61%   |
| 5      | 3        | 2.61%   |
| 10     | 1        | 0.87%   |
| 8      | 1        | 0.87%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 61.06%  |
| Yes       | 44       | 38.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 111      | 98.23%  |
| No        | 2        | 1.77%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 78       | 68.42%  |
| Yes       | 36       | 31.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 87       | 76.32%  |
| Yes       | 27       | 23.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 18       | 15.93%  |
| Russia      | 9        | 7.96%   |
| UK          | 8        | 7.08%   |
| Canada      | 8        | 7.08%   |
| Germany     | 5        | 4.42%   |
| Ukraine     | 4        | 3.54%   |
| Italy       | 4        | 3.54%   |
| France      | 4        | 3.54%   |
| China       | 4        | 3.54%   |
| Brazil      | 4        | 3.54%   |
| Australia   | 4        | 3.54%   |
| Taiwan      | 3        | 2.65%   |
| South Korea | 3        | 2.65%   |
| Spain       | 2        | 1.77%   |
| Poland      | 2        | 1.77%   |
| Mexico      | 2        | 1.77%   |
| India       | 2        | 1.77%   |
| Guatemala   | 2        | 1.77%   |
| Finland     | 2        | 1.77%   |
| Argentina   | 2        | 1.77%   |
| Venezuela   | 1        | 0.88%   |
| Uruguay     | 1        | 0.88%   |
| Turkey      | 1        | 0.88%   |
| Thailand    | 1        | 0.88%   |
| Sweden      | 1        | 0.88%   |
| Slovenia    | 1        | 0.88%   |
| Slovakia    | 1        | 0.88%   |
| Portugal    | 1        | 0.88%   |
| Peru        | 1        | 0.88%   |
| Norway      | 1        | 0.88%   |
| New Zealand | 1        | 0.88%   |
| Netherlands | 1        | 0.88%   |
| Lithuania   | 1        | 0.88%   |
| Indonesia   | 1        | 0.88%   |
| Hungary     | 1        | 0.88%   |
| Greece      | 1        | 0.88%   |
| Eswatini    | 1        | 0.88%   |
| Egypt       | 1        | 0.88%   |
| Ecuador     | 1        | 0.88%   |
| Chile       | 1        | 0.88%   |
| Belarus     | 1        | 0.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| São Paulo             | 2        | 1.74%   |
| Guatemala City         | 2        | 1.74%   |
| Dnipropetrovsk         | 2        | 1.74%   |
| Calgary                | 2        | 1.74%   |
| Brisbane               | 2        | 1.74%   |
| Šiauliai              | 1        | 0.87%   |
| Zhongshan              | 1        | 0.87%   |
| York                   | 1        | 0.87%   |
| Yekaterinburg          | 1        | 0.87%   |
| Yarang                 | 1        | 0.87%   |
| Winnipeg               | 1        | 0.87%   |
| Vladivostok            | 1        | 0.87%   |
| Villeurbanne           | 1        | 0.87%   |
| Vawkavysk              | 1        | 0.87%   |
| Ufa                    | 1        | 0.87%   |
| Trujillo               | 1        | 0.87%   |
| Treviso                | 1        | 0.87%   |
| Toronto                | 1        | 0.87%   |
| Tettnang Castle        | 1        | 0.87%   |
| Tampere                | 1        | 0.87%   |
| Taichung               | 1        | 0.87%   |
| Taganrog               | 1        | 0.87%   |
| Sydney                 | 1        | 0.87%   |
| Suzhou                 | 1        | 0.87%   |
| St Petersburg          | 1        | 0.87%   |
| Simpsonville           | 1        | 0.87%   |
| Sheffield              | 1        | 0.87%   |
| Sevastopol             | 1        | 0.87%   |
| Seoul                  | 1        | 0.87%   |
| S??o Paulo             | 1        | 0.87%   |
| San Francisco          | 1        | 0.87%   |
| Saint-Laurent-de-Ceris | 1        | 0.87%   |
| Rome                   | 1        | 0.87%   |
| Ransbach-Baumbach      | 1        | 0.87%   |
| Portsmouth             | 1        | 0.87%   |
| Porto                  | 1        | 0.87%   |
| Pflugerville           | 1        | 0.87%   |
| Petergof               | 1        | 0.87%   |
| Paris                  | 1        | 0.87%   |
| Oslo                   | 1        | 0.87%   |
| Ortona                 | 1        | 0.87%   |
| Ogden                  | 1        | 0.87%   |
| North Vancouver        | 1        | 0.87%   |
| New York               | 1        | 0.87%   |
| New Taipei             | 1        | 0.87%   |
| Mumbai                 | 1        | 0.87%   |
| Mount Pleasant         | 1        | 0.87%   |
| Montevideo             | 1        | 0.87%   |
| Mokpo                  | 1        | 0.87%   |
| Minneapolis            | 1        | 0.87%   |
| Milton Keynes          | 1        | 0.87%   |
| Miami                  | 1        | 0.87%   |
| Mbabane                | 1        | 0.87%   |
| Marrickville           | 1        | 0.87%   |
| Mar del Plata          | 1        | 0.87%   |
| Mansfield              | 1        | 0.87%   |
| Mankato                | 1        | 0.87%   |
| Malton                 | 1        | 0.87%   |
| Malokaterynivka        | 1        | 0.87%   |
| Malo                   | 1        | 0.87%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 41       | 60     | 23.16%  |
| Seagate             | 33       | 54     | 18.64%  |
| Samsung Electronics | 29       | 40     | 16.38%  |
| Toshiba             | 8        | 9      | 4.52%   |
| Kingston            | 8        | 9      | 4.52%   |
| Hitachi             | 7        | 8      | 3.95%   |
| SanDisk             | 6        | 7      | 3.39%   |
| Intel               | 5        | 5      | 2.82%   |
| HGST                | 5        | 5      | 2.82%   |
| A-DATA Technology   | 5        | 9      | 2.82%   |
| Crucial             | 4        | 6      | 2.26%   |
| SPCC                | 2        | 3      | 1.13%   |
| SK Hynix            | 2        | 2      | 1.13%   |
| Silicon Motion      | 2        | 2      | 1.13%   |
| PNY                 | 2        | 10     | 1.13%   |
| Hewlett-Packard     | 2        | 2      | 1.13%   |
| Fujitsu             | 2        | 3      | 1.13%   |
| Apple               | 2        | 2      | 1.13%   |
| Apacer              | 2        | 2      | 1.13%   |
| Transcend           | 1        | 1      | 0.56%   |
| Phison              | 1        | 1      | 0.56%   |
| Patriot             | 1        | 1      | 0.56%   |
| ORICO               | 1        | 2      | 0.56%   |
| LSI                 | 1        | 1      | 0.56%   |
| LITEON              | 1        | 1      | 0.56%   |
| Lenovo              | 1        | 1      | 0.56%   |
| KingSpec            | 1        | 1      | 0.56%   |
| EMTEC               | 1        | 1      | 0.56%   |
| CLOVER              | 1        | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 860 EVO 250GB        | 4        | 1.94%   |
| Samsung SSD 850 EVO 250GB        | 4        | 1.94%   |
| Seagate ST500DM002-1BD142 500GB  | 3        | 1.46%   |
| Seagate ST3250410AS 250GB        | 3        | 1.46%   |
| A-DATA SU650 120GB               | 3        | 1.46%   |
| WDC WD20EARS-00MVWB0 2TB         | 2        | 0.97%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 0.97%   |
| Seagate ST4000DM004-2CV104 4TB   | 2        | 0.97%   |
| Seagate ST380815AS 80GB          | 2        | 0.97%   |
| Seagate ST3250318AS 250GB        | 2        | 0.97%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 0.97%   |
| HGST HTS725050A7E630 500GB       | 2        | 0.97%   |
| HGST HTS545032A7E380 320GB       | 2        | 0.97%   |
| A-DATA SX8200PNP 256GB           | 2        | 0.97%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.49%   |
| WDC WDS500G2B0A-00SM50 500GB     | 1        | 0.49%   |
| WDC WDS250G3X0C-00SJG0 250GB     | 1        | 0.49%   |
| WDC WDS250G1B0A-00H9H0 250GB     | 1        | 0.49%   |
| WDC WDS120G2G0A-00JH30 120GB     | 1        | 0.49%   |
| WDC WDS100T2B0A-00SM50 1TB       | 1        | 0.49%   |
| WDC WD80EZAZ-11TDBA0 8TB         | 1        | 0.49%   |
| WDC WD800JD-55MUA1 80GB          | 1        | 0.49%   |
| WDC WD7500BPKX-00HPJT0 752GB     | 1        | 0.49%   |
| WDC WD6400AAKS-22A7B0 640GB      | 1        | 0.49%   |
| WDC WD5002ABYS-02B1B0 500GB      | 1        | 0.49%   |
| WDC WD5000BEVT-22ZAT0 500GB      | 1        | 0.49%   |
| WDC WD5000AZRX-00L4HB0 500GB     | 1        | 0.49%   |
| WDC WD5000ABYS-01TNA0 500GB      | 1        | 0.49%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.49%   |
| WDC WD5000AAKX-083CA1 500GB      | 1        | 0.49%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 0.49%   |
| WDC WD5000AAKS-00A7B2 500GB      | 1        | 0.49%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.49%   |
| WDC WD400BD-75LRA0 40GB          | 1        | 0.49%   |
| WDC WD4004FZWX-00GBGB0 4TB       | 1        | 0.49%   |
| WDC WD3200BEVT-00A0RT0 233GB     | 1        | 0.49%   |
| WDC WD3200BEKT-60PVMT0 320GB     | 1        | 0.49%   |
| WDC WD3200BEKT-08PVMT1 320GB     | 1        | 0.49%   |
| WDC WD3200AAJS-00L7A0 320GB      | 1        | 0.49%   |
| WDC WD30EZRX-22D8PB0 3TB         | 1        | 0.49%   |
| WDC WD3003FZEX-00Z4SA0 3TB       | 1        | 0.49%   |
| WDC WD3000JS-63PDB1 304GB        | 1        | 0.49%   |
| WDC WD2500YS-01SHB1 256GB        | 1        | 0.49%   |
| WDC WD2500BEVS-22UST0 250GB      | 1        | 0.49%   |
| WDC WD2500AAKX-083CA1 250GB      | 1        | 0.49%   |
| WDC WD2500AAJS-75M0A0 250GB      | 1        | 0.49%   |
| WDC WD1600AAJS-60WAA0 160GB      | 1        | 0.49%   |
| WDC WD1600AAJS-00WAA0 160GB      | 1        | 0.49%   |
| WDC WD1500HLFS-01G6U4 150GB      | 1        | 0.49%   |
| WDC WD10SPZX-00Z10T0 1TB         | 1        | 0.49%   |
| WDC WD10JMVW-11AJGS4 1TB         | 1        | 0.49%   |
| WDC WD10EZRX-00A8LB0 1TB         | 1        | 0.49%   |
| WDC WD10EZEX-08Y20A0 1TB         | 1        | 0.49%   |
| WDC WD10EARS-00Y5B1 1TB          | 1        | 0.49%   |
| WDC WD10EADX-00TDHB0 1TB         | 1        | 0.49%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 1        | 0.49%   |
| WDC WD1001FALS-403AA0 1TB        | 1        | 0.49%   |
| WDC WD1001FALS-00J7B1 1TB        | 1        | 0.49%   |
| Transcend TS32GMTS400S 32GB      | 1        | 0.49%   |
| Toshiba THNSNK128GCS8 SATA 128GB | 1        | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 36       | 53     | 36.36%  |
| Seagate             | 33       | 54     | 33.33%  |
| Samsung Electronics | 10       | 12     | 10.1%   |
| Hitachi             | 7        | 8      | 7.07%   |
| Toshiba             | 5        | 5      | 5.05%   |
| HGST                | 5        | 5      | 5.05%   |
| Fujitsu             | 2        | 3      | 2.02%   |
| CLOVER              | 1        | 1      | 1.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 14       | 19     | 24.14%  |
| Kingston            | 7        | 7      | 12.07%  |
| SanDisk             | 6        | 7      | 10.34%  |
| WDC                 | 4        | 5      | 6.9%    |
| Intel               | 3        | 3      | 5.17%   |
| Crucial             | 3        | 5      | 5.17%   |
| A-DATA Technology   | 3        | 3      | 5.17%   |
| Toshiba             | 2        | 3      | 3.45%   |
| SPCC                | 2        | 3      | 3.45%   |
| PNY                 | 2        | 8      | 3.45%   |
| Apple               | 2        | 2      | 3.45%   |
| Apacer              | 2        | 2      | 3.45%   |
| Transcend           | 1        | 1      | 1.72%   |
| Patriot             | 1        | 1      | 1.72%   |
| ORICO               | 1        | 2      | 1.72%   |
| LSI                 | 1        | 1      | 1.72%   |
| LITEON              | 1        | 1      | 1.72%   |
| Lenovo              | 1        | 1      | 1.72%   |
| KingSpec            | 1        | 1      | 1.72%   |
| EMTEC               | 1        | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 80       | 141    | 52.29%  |
| SSD  | 48       | 76     | 31.37%  |
| NVMe | 25       | 32     | 16.34%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 103      | 217    | 80.47%  |
| NVMe | 25       | 32     | 19.53%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 86       | 141    | 61.43%  |
| 0.51-1.0   | 32       | 44     | 22.86%  |
| 1.01-2.0   | 10       | 14     | 7.14%   |
| 3.01-4.0   | 5        | 6      | 3.57%   |
| 4.01-10.0  | 4        | 6      | 2.86%   |
| 2.01-3.0   | 3        | 6      | 2.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 78       | 67.24%  |
| 101-250    | 15       | 12.93%  |
| 501-1000   | 10       | 8.62%   |
| 251-500    | 7        | 6.03%   |
| 51-100     | 3        | 2.59%   |
| 21-50      | 2        | 1.72%   |
| 1001-2000  | 1        | 0.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 113      | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST3250410AS 250GB         | 3        | 3      | 7.5%    |
| Seagate ST380815AS 80GB           | 2        | 2      | 5%      |
| HGST HTS545032A7E380 320GB        | 2        | 2      | 5%      |
| WDC WD800JD-55MUA1 80GB           | 1        | 1      | 2.5%    |
| WDC WD6400AAKS-22A7B0 640GB       | 1        | 1      | 2.5%    |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 1      | 2.5%    |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 2.5%    |
| WDC WD40EFRX-68WT0N0 4TB          | 1        | 1      | 2.5%    |
| WDC WD3200BEVT-00A0RT0 233GB      | 1        | 1      | 2.5%    |
| WDC WD3200AAJS-00L7A0 320GB       | 1        | 1      | 2.5%    |
| WDC WD30EZRX-22D8PB0 3TB          | 1        | 1      | 2.5%    |
| WDC WD2500AAKX-083CA1 250GB       | 1        | 1      | 2.5%    |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 1      | 2.5%    |
| WDC WD1600AAJS-60WAA0 160GB       | 1        | 1      | 2.5%    |
| WDC WD1600AAJS-00WAA0 160GB       | 1        | 1      | 2.5%    |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 2.5%    |
| Toshiba THNSNK128GCS8 SATA 128GB  | 1        | 1      | 2.5%    |
| Toshiba MK3276GSX 320GB           | 1        | 1      | 2.5%    |
| Seagate ST9500325AS 500GB         | 1        | 1      | 2.5%    |
| Seagate ST500VT000-1DK142 500GB   | 1        | 1      | 2.5%    |
| Seagate ST3750640AS 752GB         | 1        | 1      | 2.5%    |
| Seagate ST3500413AS 500GB         | 1        | 1      | 2.5%    |
| Seagate ST3250318AS 250GB         | 1        | 1      | 2.5%    |
| Seagate ST31000333AS 1TB          | 1        | 1      | 2.5%    |
| Samsung Electronics SP2004C 200GB | 1        | 1      | 2.5%    |
| Samsung Electronics HD642JJ 640GB | 1        | 1      | 2.5%    |
| Samsung Electronics HD321KJ 320GB | 1        | 1      | 2.5%    |
| Samsung Electronics HD161HJ 160GB | 1        | 1      | 2.5%    |
| Hitachi HTS727550A9E364 500GB     | 1        | 1      | 2.5%    |
| Hitachi HTS723232A7A364 320GB     | 1        | 1      | 2.5%    |
| Hitachi HDS721050CLA362 500GB     | 1        | 1      | 2.5%    |
| Hitachi HDP725025GLA380 250GB     | 1        | 1      | 2.5%    |
| HGST HTS725050A7E630 500GB        | 1        | 1      | 2.5%    |
| HGST HTS541010A9E680 1TB          | 1        | 1      | 2.5%    |
| Fujitsu MHZ2250BH G1 250GB        | 1        | 1      | 2.5%    |
| Crucial CT525MX300SSD1 528GB      | 1        | 2      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 13     | 33.33%  |
| Seagate             | 10       | 11     | 25.64%  |
| Samsung Electronics | 4        | 4      | 10.26%  |
| Hitachi             | 4        | 4      | 10.26%  |
| HGST                | 4        | 4      | 10.26%  |
| Toshiba             | 2        | 2      | 5.13%   |
| Fujitsu             | 1        | 1      | 2.56%   |
| Crucial             | 1        | 2      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 13     | 35.14%  |
| Seagate             | 10       | 11     | 27.03%  |
| Samsung Electronics | 4        | 4      | 10.81%  |
| Hitachi             | 4        | 4      | 10.81%  |
| HGST                | 4        | 4      | 10.81%  |
| Toshiba             | 1        | 1      | 2.7%    |
| Fujitsu             | 1        | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 33       | 38     | 94.29%  |
| SSD  | 2        | 3      | 5.71%   |

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
| Works    | 84       | 195    | 66.67%  |
| Malfunc  | 35       | 41     | 27.78%  |
| Detected | 6        | 12     | 4.76%   |
| Failed   | 1        | 1      | 0.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 81       | 51.59%  |
| AMD                         | 31       | 19.75%  |
| Samsung Electronics         | 9        | 5.73%   |
| ASMedia Technology          | 6        | 3.82%   |
| Silicon Motion              | 4        | 2.55%   |
| Broadcom / LSI              | 4        | 2.55%   |
| VIA Technologies            | 2        | 1.27%   |
| SK Hynix                    | 2        | 1.27%   |
| Sandisk                     | 2        | 1.27%   |
| Phison Electronics          | 2        | 1.27%   |
| Nvidia                      | 2        | 1.27%   |
| Kingston Technology Company | 2        | 1.27%   |
| JMicron Technology          | 2        | 1.27%   |
| ADATA Technology            | 2        | 1.27%   |
| Adaptec                     | 2        | 1.27%   |
| Toshiba                     | 1        | 0.64%   |
| Silicon Image               | 1        | 0.64%   |
| Micron/Crucial Technology   | 1        | 0.64%   |
| Marvell Technology Group    | 1        | 0.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 7.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 5.15%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10       | 5.15%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 4.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 3.61%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 3.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 3.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 3.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 2.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 2.58%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 2.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 2.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.58%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4        | 2.06%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 2.06%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 1.55%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.55%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.55%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3        | 1.55%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 1.03%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 1.03%   |
| Nvidia MCP61 IDE                                                                        | 2        | 1.03%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.03%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.03%   |
| Intel SSD 660P Series                                                                   | 2        | 1.03%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 1.03%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 1.03%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 1.03%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 1.03%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 1.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.03%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 2        | 1.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.03%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 2        | 1.03%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2        | 1.03%   |
| Adaptec AIC-7850T/7856T [AVA-2902/4/6 / AHA-2910]                                       | 2        | 1.03%   |
| Toshiba unknown                                                                         | 1        | 0.52%   |
| SK Hynix PC300 NVMe Solid State Drive 256GB                                             | 1        | 0.52%   |
| SK Hynix Gold P31 SSD                                                                   | 1        | 0.52%   |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.52%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.52%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.52%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.52%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.52%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.52%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.52%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 0.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.52%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1        | 0.52%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.52%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.52%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.52%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 0.52%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 0.52%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 88       | 55.35%  |
| IDE  | 31       | 19.5%   |
| NVMe | 25       | 15.72%  |
| RAID | 9        | 5.66%   |
| SAS  | 3        | 1.89%   |
| SCSI | 3        | 1.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 80       | 70.8%   |
| AMD    | 33       | 29.2%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Xeon                                  | 4        | 3.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2.65%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 1.77%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 1.77%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.77%   |
| Intel Celeron CPU G3930 @ 2.90GHz           | 2        | 1.77%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 1.77%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.77%   |
| AMD A10-5700 APU with Radeon HD Graphics    | 2        | 1.77%   |
| Intel Xeon CPU W3550 @ 3.07GHz              | 1        | 0.88%   |
| Intel Xeon CPU E5530 @ 2.40GHz              | 1        | 0.88%   |
| Intel Xeon CPU E5-2630L 0 @ 2.00GHz         | 1        | 0.88%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.88%   |
| Intel Xeon CPU E5-1603 @ 2.80GHz            | 1        | 0.88%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 0.88%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 0.88%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.88%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 0.88%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.88%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.88%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.88%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.88%   |
| Intel Pentium CPU G3460 @ 3.50GHz           | 1        | 0.88%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 1        | 0.88%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.88%   |
| Intel Pentium 4 CPU 3.60GHz                 | 1        | 0.88%   |
| Intel Genuine CPU 0000 @ 2.10GHz            | 1        | 0.88%   |
| Intel Core i9-7920X CPU @ 2.90GHz           | 1        | 0.88%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.88%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.88%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.88%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.88%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.88%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.88%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 0.88%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.88%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 0.88%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.88%   |
| Intel Core i5-7500T CPU @ 2.70GHz           | 1        | 0.88%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 0.88%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1        | 0.88%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1        | 0.88%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1        | 0.88%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 0.88%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 1        | 0.88%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 0.88%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 1        | 0.88%   |
| Intel Core i5-2500 CPU                      | 1        | 0.88%   |
| Intel Core i5-2400S CPU @ 2.50GH            | 1        | 0.88%   |
| Intel Core i5-2400S CPU                     | 1        | 0.88%   |
| Intel Core i5-10600 CPU @ 3.30GHz           | 1        | 0.88%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 0.88%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 0.88%   |
| Intel Core i3-9100F CPU @ 3.60GHz           | 1        | 0.88%   |
| Intel Core i3-6300 CPU @ 3.80GHz            | 1        | 0.88%   |
| Intel Core i3-4360 CPU @ 3.70GHz            | 1        | 0.88%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 1        | 0.88%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 1        | 0.88%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 1        | 0.88%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 23       | 20.35%  |
| Intel Core i3           | 16       | 14.16%  |
| Intel Xeon              | 11       | 9.73%   |
| Intel Core i7           | 7        | 6.19%   |
| Intel Celeron           | 7        | 6.19%   |
| AMD Ryzen 5             | 7        | 6.19%   |
| AMD FX                  | 5        | 4.42%   |
| Intel Pentium Dual-Core | 4        | 3.54%   |
| Intel Pentium           | 4        | 3.54%   |
| Intel Core 2 Duo        | 4        | 3.54%   |
| AMD Ryzen 7             | 3        | 2.65%   |
| AMD Ryzen 3             | 3        | 2.65%   |
| AMD Ryzen 9             | 2        | 1.77%   |
| AMD Phenom II X4        | 2        | 1.77%   |
| AMD Athlon II X4        | 2        | 1.77%   |
| AMD A10                 | 2        | 1.77%   |
| Intel Pentium Gold      | 1        | 0.88%   |
| Intel Pentium 4         | 1        | 0.88%   |
| Intel Genuine           | 1        | 0.88%   |
| Intel Core i9           | 1        | 0.88%   |
| AMD Sempron             | 1        | 0.88%   |
| AMD Phenom II X6        | 1        | 0.88%   |
| AMD E1                  | 1        | 0.88%   |
| AMD Athlon II X3        | 1        | 0.88%   |
| AMD Athlon II X2        | 1        | 0.88%   |
| AMD Athlon              | 1        | 0.88%   |
| AMD A6                  | 1        | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 39       | 34.51%  |
| 2       | 35       | 30.97%  |
| 6       | 14       | 12.39%  |
| 8       | 10       | 8.85%   |
| 12      | 5        | 4.42%   |
| 16      | 3        | 2.65%   |
| Unknown | 3        | 2.65%   |
| 24      | 2        | 1.77%   |
| 3       | 1        | 0.88%   |
| 1       | 1        | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 110      | 97.35%  |
| 2      | 3        | 2.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 74       | 65.49%  |
| 2       | 36       | 31.86%  |
| Unknown | 3        | 2.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 17       | 15.04%  |
| SandyBridge   | 12       | 10.62%  |
| IvyBridge     | 10       | 8.85%   |
| Haswell       | 10       | 8.85%   |
| Penryn        | 8        | 7.08%   |
| Zen 2         | 7        | 6.19%   |
| K10           | 7        | 6.19%   |
| Piledriver    | 6        | 5.31%   |
| Skylake       | 5        | 4.42%   |
| CometLake     | 5        | 4.42%   |
| Zen+          | 4        | 3.54%   |
| Zen           | 4        | 3.54%   |
| Westmere      | 3        | 2.65%   |
| Nehalem       | 3        | 2.65%   |
| Silvermont    | 2        | 1.77%   |
| Core          | 2        | 1.77%   |
| Bulldozer     | 2        | 1.77%   |
| Zen 3         | 1        | 0.88%   |
| NetBurst      | 1        | 0.88%   |
| K10 Llano     | 1        | 0.88%   |
| Goldmont plus | 1        | 0.88%   |
| Broadwell     | 1        | 0.88%   |
| Bobcat        | 1        | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 55       | 46.61%  |
| Intel  | 34       | 28.81%  |
| AMD    | 29       | 24.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 710]                                                           | 7        | 5.93%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6        | 5.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5        | 4.24%   |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 3.39%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 3.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4        | 3.39%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3        | 2.54%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3        | 2.54%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3        | 2.54%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2        | 1.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 1.69%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2        | 1.69%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2        | 1.69%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2        | 1.69%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 2        | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 1.69%   |
| Intel HD Graphics 630                                                                    | 2        | 1.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2        | 1.69%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.69%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 1.69%   |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 1.69%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.69%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 0.85%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 1        | 0.85%   |
| Nvidia TU104GL [Quadro RTX 4000]                                                         | 1        | 0.85%   |
| Nvidia NV43 [GeForce 6600]                                                               | 1        | 0.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.85%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 0.85%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 0.85%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.85%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                                     | 1        | 0.85%   |
| Nvidia GK107 [GeForce GT 740]                                                            | 1        | 0.85%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 0.85%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 0.85%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.85%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1        | 0.85%   |
| Nvidia GF119 [NVS 315]                                                                   | 1        | 0.85%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                                        | 1        | 0.85%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1        | 0.85%   |
| Nvidia GF108 [GeForce GT 530]                                                            | 1        | 0.85%   |
| Nvidia GF106GL [Quadro 2000]                                                             | 1        | 0.85%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1        | 0.85%   |
| Nvidia G86 [Quadro NVS 290]                                                              | 1        | 0.85%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1        | 0.85%   |
| Nvidia G80GL [Quadro FX 5600]                                                            | 1        | 0.85%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 0.85%   |
| Intel HD Graphics 610                                                                    | 1        | 0.85%   |
| Intel HD Graphics 530                                                                    | 1        | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1        | 0.85%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1        | 0.85%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                            | 1        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 0.85%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 1        | 0.85%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 0.85%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 0.85%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 0.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 0.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1        | 0.85%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1        | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 52       | 45.61%  |
| 1 x Intel      | 29       | 25.44%  |
| 1 x AMD        | 26       | 22.81%  |
| 2 x Intel      | 2        | 1.75%   |
| Intel + AMD    | 2        | 1.75%   |
| AMD + Nvidia   | 2        | 1.75%   |
| Intel + Nvidia | 1        | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 68       | 59.65%  |
| Proprietary | 35       | 30.7%   |
| Unknown     | 11       | 9.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 59       | 51.75%  |
| 1.01-2.0   | 20       | 17.54%  |
| 0.51-1.0   | 12       | 10.53%  |
| 3.01-4.0   | 8        | 7.02%   |
| 0.01-0.5   | 6        | 5.26%   |
| 7.01-8.0   | 4        | 3.51%   |
| 5.01-6.0   | 3        | 2.63%   |
| 2.01-3.0   | 2        | 1.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 21       | 23.6%   |
| Goldstar             | 12       | 13.48%  |
| Hewlett-Packard      | 8        | 8.99%   |
| Dell                 | 7        | 7.87%   |
| Acer                 | 6        | 6.74%   |
| AOC                  | 5        | 5.62%   |
| BenQ                 | 4        | 4.49%   |
| ViewSonic            | 3        | 3.37%   |
| Iiyama               | 3        | 3.37%   |
| Ancor Communications | 3        | 3.37%   |
| Vizio                | 1        | 1.12%   |
| VIE                  | 1        | 1.12%   |
| Videoseven           | 1        | 1.12%   |
| Toshiba              | 1        | 1.12%   |
| Sun                  | 1        | 1.12%   |
| Sony                 | 1        | 1.12%   |
| RS                   | 1        | 1.12%   |
| Philips              | 1        | 1.12%   |
| Medion               | 1        | 1.12%   |
| Lenovo               | 1        | 1.12%   |
| LED                  | 1        | 1.12%   |
| Insignia             | 1        | 1.12%   |
| Gateway              | 1        | 1.12%   |
| Fujitsu Siemens      | 1        | 1.12%   |
| CVT                  | 1        | 1.12%   |
| CAN                  | 1        | 1.12%   |
| ASUSTek Computer     | 1        | 1.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| AOC 22V2WG5 AOC2202 1920x1080 480x270mm 21.7-inch                      | 2        | 2.25%   |
| Vizio D32f-F1 VIZ1027 1920x1080 700x390mm 31.5-inch                    | 1        | 1.12%   |
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch                | 1        | 1.12%   |
| ViewSonic LCD Monitor VSCD824 1920x1080 520x290mm 23.4-inch            | 1        | 1.12%   |
| ViewSonic LCD Monitor VSC8724 1440x900 410x260mm 19.1-inch             | 1        | 1.12%   |
| VIE A/G2356 VIE2300 1920x1080 500x300mm 23.0-inch                      | 1        | 1.12%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1        | 1.12%   |
| Toshiba TV TSB0108 1360x768 480x270mm 21.7-inch                        | 1        | 1.12%   |
| Sun X7202A SUN0595 1280x1024 380x300mm 19.1-inch                       | 1        | 1.12%   |
| Sony TV SNYC901 1920x1080                                              | 1        | 1.12%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 700x390mm 31.5-inch      | 1        | 1.12%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 610x350mm 27.7-inch      | 1        | 1.12%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch      | 1        | 1.12%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch    | 1        | 1.12%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch    | 1        | 1.12%   |
| Samsung Electronics SyncMaster SAM03D7 1680x1050 470x300mm 22.0-inch   | 1        | 1.12%   |
| Samsung Electronics SyncMaster SAM0320 1680x1050 470x300mm 22.0-inch   | 1        | 1.12%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch   | 1        | 1.12%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 1        | 1.12%   |
| Samsung Electronics SE790C SAM0C62 2560x1080 700x310mm 30.1-inch       | 1        | 1.12%   |
| Samsung Electronics SA300/SA350 SAM078A 1366x768 410x230mm 18.5-inch   | 1        | 1.12%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 600x340mm 27.2-inch      | 1        | 1.12%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch      | 1        | 1.12%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch      | 1        | 1.12%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch   | 1        | 1.12%   |
| Samsung Electronics LCD Monitor SAM0F9F 3840x2160 1420x800mm 64.2-inch | 1        | 1.12%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 890x500mm 40.2-inch  | 1        | 1.12%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 1        | 1.12%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch  | 1        | 1.12%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 530x300mm 24.0-inch     | 1        | 1.12%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch      | 1        | 1.12%   |
| RS LE2262 BTC2262 1680x1050 470x290mm 21.7-inch                        | 1        | 1.12%   |
| Philips LCD Monitor PHLC0B1 1920x1080 480x270mm 21.7-inch              | 1        | 1.12%   |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                    | 1        | 1.12%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                  | 1        | 1.12%   |
| LED 2250W LED2250 1920x1080 480x270mm 21.7-inch                        | 1        | 1.12%   |
| Insignia LCD Monitor BBY0050 1920x1080 700x400mm 31.7-inch             | 1        | 1.12%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch                | 1        | 1.12%   |
| Iiyama PL4071UH IVM000A 3840x2160 880x490mm 39.7-inch                  | 1        | 1.12%   |
| Iiyama PL3270Q IVM7608 2560x1440 700x390mm 31.5-inch                   | 1        | 1.12%   |
| Hewlett-Packard Z27n G2 HPN348A 2560x1440 600x340mm 27.2-inch          | 1        | 1.12%   |
| Hewlett-Packard W2371b HWP3045 1920x1080 510x290mm 23.1-inch           | 1        | 1.12%   |
| Hewlett-Packard w20 HWP26AB 1680x1050 430x270mm 20.0-inch              | 1        | 1.12%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 410x260mm 19.1-inch             | 1        | 1.12%   |
| Hewlett-Packard LA1905 HWP2844 1440x900 410x260mm 19.1-inch            | 1        | 1.12%   |
| Hewlett-Packard 27er HWP3325 1920x1080 600x340mm 27.2-inch             | 1        | 1.12%   |
| Hewlett-Packard 2310e HWP2909 1920x1080 510x290mm 23.1-inch            | 1        | 1.12%   |
| Hewlett-Packard 2211 HWP2938 1920x1080 480x270mm 21.7-inch             | 1        | 1.12%   |
| Goldstar W2243 GSM56FE 1920x1080 480x270mm 21.7-inch                   | 1        | 1.12%   |
| Goldstar LG ULTRAWIDE GSM59F2 2560x1080 580x240mm 24.7-inch            | 1        | 1.12%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch             | 1        | 1.12%   |
| Goldstar LG QHD GSM772A 2560x1440 700x390mm 31.5-inch                  | 1        | 1.12%   |
| Goldstar LG HDR QHD GSM5B95 2560x1440 700x390mm 31.5-inch              | 1        | 1.12%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch               | 1        | 1.12%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 1.12%   |
| Goldstar LG FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch              | 1        | 1.12%   |
| Goldstar LCD Monitor GSM76F5 1920x1080 700x390mm 31.5-inch             | 1        | 1.12%   |
| Goldstar L1753T GSM4477 1280x1024 340x270mm 17.1-inch                  | 1        | 1.12%   |
| Goldstar E1941 GSM4BF0 1366x768 410x230mm 18.5-inch                    | 1        | 1.12%   |
| Goldstar 19M35 GSM4C24 1366x768 410x230mm 18.5-inch                    | 1        | 1.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 36       | 40.91%  |
| 1680x1050 (WSXGA+) | 10       | 11.36%  |
| 3840x2160 (4K)     | 9        | 10.23%  |
| 1280x1024 (SXGA)   | 8        | 9.09%   |
| 1366x768 (WXGA)    | 7        | 7.95%   |
| 2560x1440 (QHD)    | 5        | 5.68%   |
| 1440x900 (WXGA+)   | 5        | 5.68%   |
| 2560x1080          | 3        | 3.41%   |
| 3440x1440          | 1        | 1.14%   |
| 2048x1152          | 1        | 1.14%   |
| 1920x540           | 1        | 1.14%   |
| 1600x900 (HD+)     | 1        | 1.14%   |
| 1024x768 (XGA)     | 1        | 1.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 14       | 15.91%  |
| 19      | 13       | 14.77%  |
| 23      | 11       | 12.5%   |
| 27      | 9        | 10.23%  |
| 24      | 8        | 9.09%   |
| 31      | 7        | 7.95%   |
| 18      | 7        | 7.95%   |
| 22      | 3        | 3.41%   |
| 20      | 3        | 3.41%   |
| 17      | 2        | 2.27%   |
| 64      | 1        | 1.14%   |
| 54      | 1        | 1.14%   |
| 50      | 1        | 1.14%   |
| 40      | 1        | 1.14%   |
| 39      | 1        | 1.14%   |
| 34      | 1        | 1.14%   |
| 30      | 1        | 1.14%   |
| 28      | 1        | 1.14%   |
| 16      | 1        | 1.14%   |
| 14      | 1        | 1.14%   |
| Unknown | 1        | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 37       | 42.05%  |
| 501-600     | 25       | 28.41%  |
| 601-700     | 10       | 11.36%  |
| 351-400     | 6        | 6.82%   |
| 1001-1500   | 3        | 3.41%   |
| 801-900     | 2        | 2.27%   |
| 301-350     | 2        | 2.27%   |
| 701-800     | 1        | 1.14%   |
| 201-300     | 1        | 1.14%   |
| Unknown     | 1        | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 60       | 68.97%  |
| 16/10 | 14       | 16.09%  |
| 5/4   | 7        | 8.05%   |
| 21/9  | 4        | 4.6%    |
| 4/3   | 1        | 1.15%   |
| 3/2   | 1        | 1.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 34       | 39.53%  |
| 151-200        | 16       | 18.6%   |
| 301-350        | 10       | 11.63%  |
| 351-500        | 8        | 9.3%    |
| 141-150        | 8        | 9.3%    |
| More than 1000 | 3        | 3.49%   |
| 251-300        | 2        | 2.33%   |
| 501-1000       | 2        | 2.33%   |
| 111-120        | 1        | 1.16%   |
| 101-110        | 1        | 1.16%   |
| Unknown        | 1        | 1.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 56       | 65.88%  |
| 101-120 | 22       | 25.88%  |
| 161-240 | 3        | 3.53%   |
| 121-160 | 2        | 2.35%   |
| 1-50    | 1        | 1.18%   |
| Unknown | 1        | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 79       | 69.3%   |
| 0     | 30       | 26.32%  |
| 2     | 5        | 4.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 74       | 52.11%  |
| Intel                           | 37       | 26.06%  |
| Broadcom                        | 9        | 6.34%   |
| Qualcomm Atheros                | 7        | 4.93%   |
| Ralink                          | 4        | 2.82%   |
| Ralink Technology               | 2        | 1.41%   |
| VIA Technologies                | 1        | 0.7%    |
| Samsung Electronics             | 1        | 0.7%    |
| Qualcomm Atheros Communications | 1        | 0.7%    |
| Mellanox Technologies           | 1        | 0.7%    |
| Marvell Technology Group        | 1        | 0.7%    |
| D-Link System                   | 1        | 0.7%    |
| D-Link                          | 1        | 0.7%    |
| ASUSTek Computer                | 1        | 0.7%    |
| 3Com                            | 1        | 0.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 69       | 44.23%  |
| Intel Ethernet Connection (7) I219-V                                       | 6        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6        | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3        | 1.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3        | 1.92%   |
| Intel Wi-Fi 6 AX200                                                        | 3        | 1.92%   |
| Intel I211 Gigabit Network Connection                                      | 3        | 1.92%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 1.92%   |
| Intel 82579V Gigabit Network Connection                                    | 3        | 1.92%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                     | 2        | 1.28%   |
| Intel Wireless 7260                                                        | 2        | 1.28%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 2        | 1.28%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2        | 1.28%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 2        | 1.28%   |
| VIA VT6105/VT6106S [Rhine-III]                                             | 1        | 0.64%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.64%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 0.64%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1        | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1        | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1        | 0.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1        | 0.64%   |
| Ralink RT5370 Wireless Adapter                                             | 1        | 0.64%   |
| Ralink MT7601U Wireless Adapter                                            | 1        | 0.64%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                | 1        | 0.64%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                  | 1        | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1        | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.64%   |
| Qualcomm Atheros AR9271 802.11n                                            | 1        | 0.64%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                              | 1        | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 1        | 0.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 0.64%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.64%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]     | 1        | 0.64%   |
| Mellanox MT27500 Family [ConnectX-3]                                       | 1        | 0.64%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 1        | 0.64%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                          | 1        | 0.64%   |
| Intel Wireless-AC 9260                                                     | 1        | 0.64%   |
| Intel Wireless 3165                                                        | 1        | 0.64%   |
| Intel Wireless 3160                                                        | 1        | 0.64%   |
| Intel Ethernet Connection I218-V                                           | 1        | 0.64%   |
| Intel Ethernet Connection I217-V                                           | 1        | 0.64%   |
| Intel Ethernet Connection (2) I219-V                                       | 1        | 0.64%   |
| Intel Ethernet Connection (2) I218-V                                       | 1        | 0.64%   |
| Intel Ethernet Connection (12) I219-V                                      | 1        | 0.64%   |
| Intel Ethernet Connection (11) I219-V                                      | 1        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1        | 0.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 1        | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 1        | 0.64%   |
| Intel 82583V Gigabit Network Connection                                    | 1        | 0.64%   |
| Intel 82562V-2 10/100 Network Connection                                   | 1        | 0.64%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                       | 1        | 0.64%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1        | 0.64%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.B1) [Ralink RT5370]              | 1        | 0.64%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                           | 1        | 0.64%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                    | 1        | 0.64%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 1        | 0.64%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1        | 0.64%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 1        | 0.64%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                  | 1        | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 11       | 28.95%  |
| Intel                           | 11       | 28.95%  |
| Ralink                          | 4        | 10.53%  |
| Qualcomm Atheros                | 4        | 10.53%  |
| Ralink Technology               | 2        | 5.26%   |
| Broadcom                        | 2        | 5.26%   |
| Qualcomm Atheros Communications | 1        | 2.63%   |
| D-Link System                   | 1        | 2.63%   |
| D-Link                          | 1        | 2.63%   |
| ASUSTek Computer                | 1        | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3        | 7.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3        | 7.89%   |
| Intel Wi-Fi 6 AX200                                                        | 3        | 7.89%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                     | 2        | 5.26%   |
| Intel Wireless 7260                                                        | 2        | 5.26%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 2.63%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 2.63%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                     | 1        | 2.63%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1        | 2.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1        | 2.63%   |
| Ralink RT5370 Wireless Adapter                                             | 1        | 2.63%   |
| Ralink MT7601U Wireless Adapter                                            | 1        | 2.63%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                | 1        | 2.63%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                  | 1        | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1        | 2.63%   |
| Qualcomm Atheros AR9271 802.11n                                            | 1        | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 1        | 2.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 2.63%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]     | 1        | 2.63%   |
| Intel Wireless-AC 9260                                                     | 1        | 2.63%   |
| Intel Wireless 3165                                                        | 1        | 2.63%   |
| Intel Wireless 3160                                                        | 1        | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1        | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 1        | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 1        | 2.63%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1        | 2.63%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.B1) [Ralink RT5370]              | 1        | 2.63%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1        | 2.63%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 1        | 2.63%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                  | 1        | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 70       | 61.4%   |
| Intel                    | 31       | 27.19%  |
| Broadcom                 | 7        | 6.14%   |
| Qualcomm Atheros         | 3        | 2.63%   |
| VIA Technologies         | 1        | 0.88%   |
| Samsung Electronics      | 1        | 0.88%   |
| Marvell Technology Group | 1        | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69       | 59.48%  |
| Intel Ethernet Connection (7) I219-V                              | 6        | 5.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 5.17%   |
| Intel I211 Gigabit Network Connection                             | 3        | 2.59%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.59%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 2.59%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.72%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2        | 1.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 1.72%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.86%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.86%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.86%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.86%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.86%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.86%   |
| Intel Ethernet Connection I218-V                                  | 1        | 0.86%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.86%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 0.86%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.86%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.86%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.86%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.86%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.86%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 0.86%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.86%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 0.86%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 111      | 75%     |
| WiFi     | 35       | 23.65%  |
| Unknown  | 2        | 1.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 110      | 80.29%  |
| WiFi     | 25       | 18.25%  |
| Unknown  | 2        | 1.46%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 80       | 70.18%  |
| 2     | 30       | 26.32%  |
| 3     | 3        | 2.63%   |
| 0     | 1        | 0.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 112      | 98.25%  |
| Yes  | 2        | 1.75%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 9        | 32.14%  |
| Cambridge Silicon Radio         | 6        | 21.43%  |
| Realtek Semiconductor           | 3        | 10.71%  |
| Broadcom                        | 3        | 10.71%  |
| ASUSTek Computer                | 3        | 10.71%  |
| Qualcomm Atheros Communications | 1        | 3.57%   |
| Integrated System Solution      | 1        | 3.57%   |
| Edimax Technology               | 1        | 3.57%   |
| Apple                           | 1        | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 6        | 21.43%  |
| Intel Bluetooth wireless interface                      | 3        | 10.71%  |
| Intel AX200 Bluetooth                                   | 3        | 10.71%  |
| Realtek  Bluetooth 4.2 Adapter                          | 2        | 7.14%   |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 2        | 7.14%   |
| Realtek  Bluetooth Adapter                              | 1        | 3.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                   | 1        | 3.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 1        | 3.57%   |
| Intel Wireless-AC 3168 Bluetooth                        | 1        | 3.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1        | 3.57%   |
| Integrated System Solution Bluetooth Device             | 1        | 3.57%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1        | 3.57%   |
| Broadcom Bluetooth Device                               | 1        | 3.57%   |
| Broadcom Bluetooth 2.0+eDR dongle                       | 1        | 3.57%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 1        | 3.57%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip            | 1        | 3.57%   |
| Apple Apple Broadcom Built-in Bluetooth                 | 1        | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 80       | 44.2%   |
| Nvidia                      | 49       | 27.07%  |
| AMD                         | 39       | 21.55%  |
| Texas Instruments           | 2        | 1.1%    |
| C-Media Electronics         | 2        | 1.1%    |
| XMOS                        | 1        | 0.55%   |
| Steinberg Soft-und Hardware | 1        | 0.55%   |
| SteelSeries ApS             | 1        | 0.55%   |
| Realtek Semiconductor       | 1        | 0.55%   |
| Logitech                    | 1        | 0.55%   |
| Kingston Technology         | 1        | 0.55%   |
| Ensoniq                     | 1        | 0.55%   |
| Creative Technology         | 1        | 0.55%   |
| Creative Labs               | 1        | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 13       | 6.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 11       | 5.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 8        | 3.92%   |
| Intel Cannon Lake PCH cAVS                                                        | 7        | 3.43%   |
| Intel 200 Series PCH HD Audio                                                     | 7        | 3.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7        | 3.43%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 7        | 3.43%   |
| Nvidia GP108 High Definition Audio Controller                                     | 6        | 2.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 6        | 2.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6        | 2.94%   |
| Nvidia GF119 HDMI Audio Controller                                                | 5        | 2.45%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 5        | 2.45%   |
| AMD Starship/Matisse HD Audio Controller                                          | 5        | 2.45%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4        | 1.96%   |
| Nvidia GM206 High Definition Audio Controller                                     | 4        | 1.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 4        | 1.96%   |
| Intel Comet Lake PCH-V cAVS                                                       | 4        | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4        | 1.96%   |
| Nvidia High Definition Audio Controller                                           | 3        | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 1.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3        | 1.47%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 3        | 1.47%   |
| AMD FCH Azalia Controller                                                         | 3        | 1.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3        | 1.47%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3        | 1.47%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.47%   |
| Nvidia MCP61 High Definition Audio                                                | 2        | 0.98%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 0.98%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2        | 0.98%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 0.98%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2        | 0.98%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 0.98%   |
| Nvidia GF106 High Definition Audio Controller                                     | 2        | 0.98%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2        | 0.98%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 0.98%   |
| Intel 8 Series HD Audio Controller                                                | 2        | 0.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 0.98%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2        | 0.98%   |
| AMD Trinity HDMI Audio Controller                                                 | 2        | 0.98%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.98%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 0.98%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 0.98%   |
| XMOS Cyberdrive Audio Driver                                                      | 1        | 0.49%   |
| Texas Instruments SMSL Q5 AMP                                                     | 1        | 0.49%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1        | 0.49%   |
| Steinberg Soft-und Hardware MI4                                                   | 1        | 0.49%   |
| SteelSeries ApS Arctis 7 wireless adapter                                         | 1        | 0.49%   |
| Realtek Semiconductor Realtek Audio USB Realtek Audio USB Microphone              | 1        | 0.49%   |
| Nvidia TU104 HD Audio Controller                                                  | 1        | 0.49%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1        | 0.49%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 0.49%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 0.49%   |
| Logitech HD Webcam C910                                                           | 1        | 0.49%   |
| Kingston Technology HyperX 7.1 Audio                                              | 1        | 0.49%   |
| Intel USB PnP Sound Device                                                        | 1        | 0.49%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 0.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 0.49%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 1        | 0.49%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 1        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Kingston                   | 24       | 17.65%  |
| Unknown                    | 23       | 16.91%  |
| Crucial                    | 17       | 12.5%   |
| SK Hynix                   | 12       | 8.82%   |
| Samsung Electronics        | 12       | 8.82%   |
| Micron Technology          | 11       | 8.09%   |
| G.Skill                    | 8        | 5.88%   |
| Corsair                    | 6        | 4.41%   |
| Nanya Technology           | 4        | 2.94%   |
| Avant                      | 3        | 2.21%   |
| Team                       | 2        | 1.47%   |
| Ramaxel Technology         | 2        | 1.47%   |
| PNY                        | 2        | 1.47%   |
| Elpida                     | 2        | 1.47%   |
| AMD                        | 2        | 1.47%   |
| Unknown (7F7F7F94FFFFFFFF) | 1        | 0.74%   |
| Unknown (09A4)             | 1        | 0.74%   |
| Patriot                    | 1        | 0.74%   |
| Goldkey                    | 1        | 0.74%   |
| Apacer                     | 1        | 0.74%   |
| A-DATA Technology          | 1        | 0.74%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 1333MT/s                               | 4        | 2.68%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                               | 3        | 2.01%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s                | 2        | 1.34%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s               | 2        | 1.34%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s                  | 2        | 1.34%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                | 2        | 1.34%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s                 | 2        | 1.34%   |
| Avant RAM W641GU49J9266N6 8192MB DIMM DDR4 2667MT/s                | 2        | 1.34%   |
| Unknown RAM TMKS8G68ALFBCH-266 8192MB SODIMM DDR4 2400MT/s         | 1        | 0.67%   |
| Unknown RAM R9P5316-007.A02LF 2GB DIMM 533MT/s                     | 1        | 0.67%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                          | 1        | 0.67%   |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                          | 1        | 0.67%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                               | 1        | 0.67%   |
| Unknown RAM Module 4GB DIMM DDR3 1866MT/s                          | 1        | 0.67%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                           | 1        | 0.67%   |
| Unknown RAM Module 4GB DIMM 667MT/s                                | 1        | 0.67%   |
| Unknown RAM Module 4096MB DIMM DDR2                                | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM SDRAM                                  | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                          | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                           | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                           | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM 533MT/s                                | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                               | 1        | 0.67%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                       | 1        | 0.67%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                        | 1        | 0.67%   |
| Unknown RAM Module 2048MB DIMM DDR2                                | 1        | 0.67%   |
| Unknown RAM Module 1GB DIMM 1333MT/s                               | 1        | 0.67%   |
| Unknown RAM Module 1024MB DIMM SDRAM 667MT/s                       | 1        | 0.67%   |
| Unknown RAM 7TE39AA# 8GB DIMM DDR4 2667MT/s                        | 1        | 0.67%   |
| Unknown (7F7F7F94FFFFFFFF) RAM 996593PCGH 2048MB DIMM DDR2 800MT/s | 1        | 0.67%   |
| Unknown (09A4) RAM 08S2400CL170H 8192MB DIMM DDR4 2133MT/s         | 1        | 0.67%   |
| Team RAM TEAMGROUP-UD4-3000 4GB DIMM DDR4 2400MT/s                 | 1        | 0.67%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s                 | 1        | 0.67%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1066MT/s                         | 1        | 0.67%   |
| SK Hynix RAM HYMP525F72CP4N3-Y5 2048MB FB-DIMM DDR2 533MT/s        | 1        | 0.67%   |
| SK Hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s               | 1        | 0.67%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s               | 1        | 0.67%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s               | 1        | 0.67%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s               | 1        | 0.67%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s               | 1        | 0.67%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s               | 1        | 0.67%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s             | 1        | 0.67%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s               | 1        | 0.67%   |
| SK Hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s               | 1        | 0.67%   |
| SK Hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s               | 1        | 0.67%   |
| SK Hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s               | 1        | 0.67%   |
| SK Hynix RAM HMT125U6BFR8C-H9 2048MB DIMM DDR3 1333MT/s            | 1        | 0.67%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s              | 1        | 0.67%   |
| Samsung RAM M391B5673EH1-CF8 2GB DIMM DDR3 1066MT/s                | 1        | 0.67%   |
| Samsung RAM M391B5273DH0-YH9 4GB DIMM DDR3 1333MT/s                | 1        | 0.67%   |
| Samsung RAM M378B5773QB0-CK0 2GB DIMM DDR3 1600MT/s                | 1        | 0.67%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                | 1        | 0.67%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s                | 1        | 0.67%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s                | 1        | 0.67%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s                | 1        | 0.67%   |
| Samsung RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1333MT/s                | 1        | 0.67%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 2666MT/s                | 1        | 0.67%   |
| Samsung RAM M378A1G43TB1-CTD 8192MB DIMM DDR4 3200MT/s             | 1        | 0.67%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s                | 1        | 0.67%   |
| Samsung RAM M3 78T2953EZ3-CE6 1GB DIMM DDR2 667MT/s                | 1        | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 46       | 40.35%  |
| DDR3    | 45       | 39.47%  |
| Unknown | 11       | 9.65%   |
| DDR2    | 8        | 7.02%   |
| SDRAM   | 3        | 2.63%   |
| DDR     | 1        | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 104      | 92.04%  |
| SODIMM  | 8        | 7.08%   |
| FB-DIMM | 1        | 0.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 47       | 34.81%  |
| 8192  | 39       | 28.89%  |
| 2048  | 32       | 23.7%   |
| 16384 | 9        | 6.67%   |
| 1024  | 6        | 4.44%   |
| 32768 | 2        | 1.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 25       | 20%     |
| 1333    | 23       | 18.4%   |
| 2667    | 15       | 12%     |
| 2400    | 13       | 10.4%   |
| 2133    | 10       | 8%      |
| 667     | 7        | 5.6%    |
| 3200    | 6        | 4.8%    |
| 2666    | 6        | 4.8%    |
| 800     | 6        | 4.8%    |
| 533     | 3        | 2.4%    |
| 2933    | 2        | 1.6%    |
| 1866    | 2        | 1.6%    |
| 1066    | 2        | 1.6%    |
| Unknown | 2        | 1.6%    |
| 1867    | 1        | 0.8%    |
| 1800    | 1        | 0.8%    |
| 1400    | 1        | 0.8%    |

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
| Microdia               | 1        | 14.29%  |
| Logitech               | 1        | 14.29%  |
| Hewlett-Packard        | 1        | 14.29%  |
| HD WEBCAM              | 1        | 14.29%  |
| Generalplus Technology | 1        | 14.29%  |
| GEMBIRD                | 1        | 14.29%  |
| A4Tech                 | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Microdia ASUS USB2.0 Webcam                       | 1        | 14.29%  |
| Logitech Webcam C270                              | 1        | 14.29%  |
| HP Premium Starter Webcam                         | 1        | 14.29%  |
| HD WEBCAM HD WEBCAM                               | 1        | 14.29%  |
| Generalplus GENERAL WEBCAM                        | 1        | 14.29%  |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 14.29%  |
| A4Tech A4tech FHD 1080P PC Camera                 | 1        | 14.29%  |

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
| 1     | 56       | 49.12%  |
| 0     | 42       | 36.84%  |
| 2     | 13       | 11.4%   |
| 3     | 2        | 1.75%   |
| 4     | 1        | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 61       | 69.32%  |
| Net/wireless             | 15       | 17.05%  |
| Firewire controller      | 4        | 4.55%   |
| Sound                    | 3        | 3.41%   |
| Bluetooth                | 3        | 3.41%   |
| Storage/raid             | 1        | 1.14%   |
| Card reader              | 1        | 1.14%   |

