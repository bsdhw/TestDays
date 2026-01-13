BSD in UK - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for BSD in UK.

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

Total: 371

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [c1426aac21](https://bsd-hardware.info/?probe=c1426aac21) | Jan 03, 2026 |
| HP            | EliteBook Folio 9470m       | [e5cd4a5c15](https://bsd-hardware.info/?probe=e5cd4a5c15) | Dec 28, 2025 |
| HP            | EliteBook 840 G7 Noteboo... | [ca65a8537b](https://bsd-hardware.info/?probe=ca65a8537b) | Dec 25, 2025 |
| Lenovo        | ThinkPad T480 20L6S9UJ0Y    | [6799072e37](https://bsd-hardware.info/?probe=6799072e37) | Dec 21, 2025 |
| Lenovo        | ThinkPad T480 20L6S9UJ0Y    | [e523952624](https://bsd-hardware.info/?probe=e523952624) | Dec 21, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [d811e53da8](https://bsd-hardware.info/?probe=d811e53da8) | Dec 21, 2025 |
| Deciso        | NetBoard-A10_Gen.3          | [937bc95626](https://bsd-hardware.info/?probe=937bc95626) | Dec 14, 2025 |
| Dell          | Latitude 5410               | [0754c58554](https://bsd-hardware.info/?probe=0754c58554) | Dec 13, 2025 |
| HP            | ProBook 455 G2              | [ee7f7ebedd](https://bsd-hardware.info/?probe=ee7f7ebedd) | Dec 12, 2025 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [28e7de1846](https://bsd-hardware.info/?probe=28e7de1846) | Dec 08, 2025 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [bea927e2fd](https://bsd-hardware.info/?probe=bea927e2fd) | Dec 08, 2025 |
| Dell          | Precision 3561              | [54c5a30bf4](https://bsd-hardware.info/?probe=54c5a30bf4) | Dec 08, 2025 |
| Dell          | Precision 3561              | [fcedc4b737](https://bsd-hardware.info/?probe=fcedc4b737) | Dec 08, 2025 |
| Dell          | Latitude 5520               | [a8c5ee2142](https://bsd-hardware.info/?probe=a8c5ee2142) | Dec 08, 2025 |
| Dell          | Latitude 5520               | [05c34d8bb3](https://bsd-hardware.info/?probe=05c34d8bb3) | Dec 08, 2025 |
| HP            | Stream Laptop 14-ax0XX      | [fa039e4311](https://bsd-hardware.info/?probe=fa039e4311) | Oct 16, 2025 |
| Samsung       | NC10                        | [509d4a9b20](https://bsd-hardware.info/?probe=509d4a9b20) | Oct 16, 2025 |
| ASUSTek       | ROG Strix G16 G614JVR_G6... | [429aa7318f](https://bsd-hardware.info/?probe=429aa7318f) | Oct 14, 2025 |
| Apple         | MacBookAir6,1               | [2e6c5389c6](https://bsd-hardware.info/?probe=2e6c5389c6) | Sep 29, 2025 |
| HP            | EliteBook 840 G8 Noteboo... | [24ce6e8685](https://bsd-hardware.info/?probe=24ce6e8685) | Sep 21, 2025 |
| Lenovo        | ThinkPad X61s 76693JG       | [51e66f1bd2](https://bsd-hardware.info/?probe=51e66f1bd2) | Sep 01, 2025 |
| Google        | Reef                        | [ff4733298b](https://bsd-hardware.info/?probe=ff4733298b) | Aug 20, 2025 |
| ASUSTek       | BU403UA                     | [e654f9bd9f](https://bsd-hardware.info/?probe=e654f9bd9f) | Aug 19, 2025 |
| ASUSTek       | BU403UA                     | [dde40f3528](https://bsd-hardware.info/?probe=dde40f3528) | Aug 17, 2025 |
| Lenovo        | ThinkPad X390 20Q0003VUK    | [f60a291978](https://bsd-hardware.info/?probe=f60a291978) | Aug 04, 2025 |
| Panasonic     | CF-52VDC1FDE                | [ca727a60e1](https://bsd-hardware.info/?probe=ca727a60e1) | Aug 01, 2025 |
| HP            | EliteBook 660 16 inch G1... | [b45a4fd15d](https://bsd-hardware.info/?probe=b45a4fd15d) | Aug 01, 2025 |
| Lenovo        | ThinkPad X61s 76693JG       | [b88b84b626](https://bsd-hardware.info/?probe=b88b84b626) | Jul 20, 2025 |
| HP            | Pavilion Notebook           | [1bc8976b6b](https://bsd-hardware.info/?probe=1bc8976b6b) | Jun 05, 2025 |
| HP            | ZBook 17 G2                 | [b831bd1de5](https://bsd-hardware.info/?probe=b831bd1de5) | Apr 27, 2025 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [ef103d1a10](https://bsd-hardware.info/?probe=ef103d1a10) | Apr 24, 2025 |
| HP            | ZBook 17 G2                 | [0290af8d17](https://bsd-hardware.info/?probe=0290af8d17) | Apr 20, 2025 |
| Acer          | Aspire 5742Z                | [988a8ec99a](https://bsd-hardware.info/?probe=988a8ec99a) | Apr 15, 2025 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8e3bae7f65](https://bsd-hardware.info/?probe=8e3bae7f65) | Apr 07, 2025 |
| Lenovo        | ThinkPad T550 20CJS00X00    | [c766b545db](https://bsd-hardware.info/?probe=c766b545db) | Apr 02, 2025 |
| Apple         | MacBookPro8,3               | [1a6d755f2f](https://bsd-hardware.info/?probe=1a6d755f2f) | Mar 25, 2025 |
| Apple         | MacBookPro8,3               | [274cca0d30](https://bsd-hardware.info/?probe=274cca0d30) | Mar 22, 2025 |
| HP            | ZBook 17 G2                 | [3ac44e90e5](https://bsd-hardware.info/?probe=3ac44e90e5) | Mar 16, 2025 |
| Panasonic     | CFSZ6-2                     | [1b784b035f](https://bsd-hardware.info/?probe=1b784b035f) | Mar 15, 2025 |
| HP            | ZBook 17 G2                 | [67bcbc3b4c](https://bsd-hardware.info/?probe=67bcbc3b4c) | Mar 12, 2025 |
| Lenovo        | ThinkPad T495 20NKS01W0K    | [c273be5c22](https://bsd-hardware.info/?probe=c273be5c22) | Mar 12, 2025 |
| HP            | ZBook 17 G2                 | [ce7dcfac1b](https://bsd-hardware.info/?probe=ce7dcfac1b) | Mar 09, 2025 |
| HP            | ProBook 430 G8 Notebook ... | [7aa930ff64](https://bsd-hardware.info/?probe=7aa930ff64) | Feb 22, 2025 |
| Lenovo        | ThinkPad T460 20FN003LUK    | [8d5ce1eca6](https://bsd-hardware.info/?probe=8d5ce1eca6) | Feb 15, 2025 |
| Apple         | MacBookPro8,3               | [959c936cc1](https://bsd-hardware.info/?probe=959c936cc1) | Feb 15, 2025 |
| MSI           | Modern 15 F13MG             | [b7f27b9528](https://bsd-hardware.info/?probe=b7f27b9528) | Feb 13, 2025 |
| Dell          | XPS 15 9500                 | [d10ad4bd32](https://bsd-hardware.info/?probe=d10ad4bd32) | Feb 03, 2025 |
| PC Special... | L140CU                      | [8ea58ac37a](https://bsd-hardware.info/?probe=8ea58ac37a) | Jan 27, 2025 |
| PC Special... | L140CU                      | [e7e0fcf140](https://bsd-hardware.info/?probe=e7e0fcf140) | Jan 27, 2025 |
| Lenovo        | ThinkPad L380 20M6S2FU00    | [8cb99e3fe8](https://bsd-hardware.info/?probe=8cb99e3fe8) | Jan 20, 2025 |
| Deciso        | DEC2700 - OPNsense Appli... | [26031e117a](https://bsd-hardware.info/?probe=26031e117a) | Jan 20, 2025 |
| HP            | EliteBook 650 15.6 inch ... | [24a6ddb8c4](https://bsd-hardware.info/?probe=24a6ddb8c4) | Jan 13, 2025 |
| Deciso        | DEC2700 - OPNsense Appli... | [e7e6ec6c7f](https://bsd-hardware.info/?probe=e7e6ec6c7f) | Jan 09, 2025 |
| Apple         | MacBookPro8,3               | [af06d6afc4](https://bsd-hardware.info/?probe=af06d6afc4) | Dec 24, 2024 |
| HP            | ZBook 17 G2                 | [c8d95da1f8](https://bsd-hardware.info/?probe=c8d95da1f8) | Nov 26, 2024 |
| Acer          | Nitro AN515-42              | [0cd9c4bf36](https://bsd-hardware.info/?probe=0cd9c4bf36) | Nov 11, 2024 |
| Apple         | MacBookPro8,3               | [f3bbee2559](https://bsd-hardware.info/?probe=f3bbee2559) | Nov 10, 2024 |
| Lenovo        | ThinkPad T420 4236MA3       | [1fe30aef50](https://bsd-hardware.info/?probe=1fe30aef50) | Oct 24, 2024 |
| GPD           | P2 MAX                      | [884f11539a](https://bsd-hardware.info/?probe=884f11539a) | Oct 12, 2024 |
| Apple         | MacBookPro11,1              | [7fef5366cf](https://bsd-hardware.info/?probe=7fef5366cf) | Oct 10, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [52ca4ac8cd](https://bsd-hardware.info/?probe=52ca4ac8cd) | Oct 05, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [402e2d6b51](https://bsd-hardware.info/?probe=402e2d6b51) | Oct 05, 2024 |
| TUXEDO        | Aura 15 Gen1                | [0f0cf20fe9](https://bsd-hardware.info/?probe=0f0cf20fe9) | Sep 28, 2024 |
| Apple         | MacBookPro8,3               | [15c24e17a2](https://bsd-hardware.info/?probe=15c24e17a2) | Sep 28, 2024 |
| Acer          | Aspire 4820                 | [2ba56db0c4](https://bsd-hardware.info/?probe=2ba56db0c4) | Sep 26, 2024 |
| HP            | ZBook 17 G2                 | [24de39a693](https://bsd-hardware.info/?probe=24de39a693) | Sep 26, 2024 |
| HP            | ZBook 17 G2                 | [fbfc038a2d](https://bsd-hardware.info/?probe=fbfc038a2d) | Sep 18, 2024 |
| HP            | ZBook 17 G2                 | [a0946e4145](https://bsd-hardware.info/?probe=a0946e4145) | Sep 07, 2024 |
| Panasonic     | CF-C1BT02EGE                | [e2dcfb8821](https://bsd-hardware.info/?probe=e2dcfb8821) | Sep 06, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c6c35c6a96](https://bsd-hardware.info/?probe=c6c35c6a96) | Sep 05, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [cd17d71b66](https://bsd-hardware.info/?probe=cd17d71b66) | Sep 05, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | [272dd56725](https://bsd-hardware.info/?probe=272dd56725) | Aug 22, 2024 |
| Datto         | 1000                        | [ff45190084](https://bsd-hardware.info/?probe=ff45190084) | Aug 15, 2024 |
| PC Special... | L140CU                      | [41e8ed9ff2](https://bsd-hardware.info/?probe=41e8ed9ff2) | Aug 04, 2024 |
| Apple         | MacBookPro14,1              | [e7cfb93b94](https://bsd-hardware.info/?probe=e7cfb93b94) | Jul 29, 2024 |
| Lenovo        | ThinkPad X230 23066CC       | [fad7a780db](https://bsd-hardware.info/?probe=fad7a780db) | Jul 29, 2024 |
| Apple         | MacBookPro14,1              | [8ab282bab2](https://bsd-hardware.info/?probe=8ab282bab2) | Jul 28, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [b671ec6c8d](https://bsd-hardware.info/?probe=b671ec6c8d) | Jul 21, 2024 |
| Lenovo        | ThinkPad T400 6475FA4       | [ebe23829a9](https://bsd-hardware.info/?probe=ebe23829a9) | Jul 18, 2024 |
| Lenovo        | ThinkPad X220 429137G       | [f6d3e4a448](https://bsd-hardware.info/?probe=f6d3e4a448) | Jul 13, 2024 |
| Lenovo        | ThinkPad X220 429137G       | [1e0500cb46](https://bsd-hardware.info/?probe=1e0500cb46) | Jul 09, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | [3ecc86438d](https://bsd-hardware.info/?probe=3ecc86438d) | Jul 08, 2024 |
| Lenovo        | ThinkPad X220 429137G       | [2d398edd49](https://bsd-hardware.info/?probe=2d398edd49) | Jul 02, 2024 |
| Lenovo        | ThinkPad X220 429137G       | [c78a57178a](https://bsd-hardware.info/?probe=c78a57178a) | Jul 02, 2024 |
| Lenovo        | ThinkPad X220 429137G       | [f8dbb73971](https://bsd-hardware.info/?probe=f8dbb73971) | Jun 27, 2024 |
| Dell          | XPS 15 9560                 | [f3b5f883fb](https://bsd-hardware.info/?probe=f3b5f883fb) | Jun 21, 2024 |
| HP            | Pavilion 15                 | [36a75dbcf3](https://bsd-hardware.info/?probe=36a75dbcf3) | Jun 18, 2024 |
| ASUSTek       | 1001P                       | [757aec0ac5](https://bsd-hardware.info/?probe=757aec0ac5) | Jun 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [7738e5ded1](https://bsd-hardware.info/?probe=7738e5ded1) | May 25, 2024 |
| HP            | ZBook 17 G2                 | [6c9cc5620b](https://bsd-hardware.info/?probe=6c9cc5620b) | May 22, 2024 |
| Dell          | Inspiron 1545               | [84bb977e77](https://bsd-hardware.info/?probe=84bb977e77) | May 22, 2024 |
| Dell          | Inspiron 1545               | [6fa29eb23c](https://bsd-hardware.info/?probe=6fa29eb23c) | May 22, 2024 |
| Dell          | Inspiron 1545               | [e123332fb8](https://bsd-hardware.info/?probe=e123332fb8) | May 16, 2024 |
| Dell          | Inspiron 1545               | [d5f43a27aa](https://bsd-hardware.info/?probe=d5f43a27aa) | May 12, 2024 |
| Dell          | Inspiron 1545               | [3c3432b2c0](https://bsd-hardware.info/?probe=3c3432b2c0) | May 11, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [89a61aca01](https://bsd-hardware.info/?probe=89a61aca01) | May 04, 2024 |
| HP            | ZBook 17 G2                 | [8558fc6b60](https://bsd-hardware.info/?probe=8558fc6b60) | May 04, 2024 |
| DFI           | Unknown                     | [1348838d15](https://bsd-hardware.info/?probe=1348838d15) | Apr 28, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | [c2e1f3af3b](https://bsd-hardware.info/?probe=c2e1f3af3b) | Apr 18, 2024 |
| Lenovo        | ThinkPad T400 6475FA4       | [4318a318e5](https://bsd-hardware.info/?probe=4318a318e5) | Apr 11, 2024 |
| Lenovo        | ThinkPad S5-S531 20B0000... | [cf65a95f23](https://bsd-hardware.info/?probe=cf65a95f23) | Apr 08, 2024 |
| Lenovo        | ThinkPad S5-S531 20B0000... | [bea4d85189](https://bsd-hardware.info/?probe=bea4d85189) | Apr 08, 2024 |
| HP            | ZBook 17 G2                 | [8a5397997e](https://bsd-hardware.info/?probe=8a5397997e) | Mar 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [637e2678c5](https://bsd-hardware.info/?probe=637e2678c5) | Mar 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [f6e67c7e6e](https://bsd-hardware.info/?probe=f6e67c7e6e) | Mar 09, 2024 |
| Apple         | MacBookPro8,3               | [89647876db](https://bsd-hardware.info/?probe=89647876db) | Mar 02, 2024 |
| Shuttle       | NC02U                       | [d559b380f0](https://bsd-hardware.info/?probe=d559b380f0) | Feb 14, 2024 |
| Lenovo        | ThinkPad T410 2522WAR       | [caccf07908](https://bsd-hardware.info/?probe=caccf07908) | Feb 12, 2024 |
| Unknown       | Unknown                     | [f5ad3c2512](https://bsd-hardware.info/?probe=f5ad3c2512) | Feb 08, 2024 |
| HP            | ZBook 17 G2                 | [db2c57b081](https://bsd-hardware.info/?probe=db2c57b081) | Jan 24, 2024 |
| Dell          | Latitude 7480               | [d9b4d836e7](https://bsd-hardware.info/?probe=d9b4d836e7) | Jan 17, 2024 |
| HP            | 255 G7 Notebook PC          | [2c7e743906](https://bsd-hardware.info/?probe=2c7e743906) | Jan 10, 2024 |
| HP            | 255 G7 Notebook PC          | [ef0d0a61f8](https://bsd-hardware.info/?probe=ef0d0a61f8) | Jan 10, 2024 |
| Deciso        | NetBoard-A10                | [1545839e21](https://bsd-hardware.info/?probe=1545839e21) | Dec 29, 2023 |
| Dell          | Latitude E6510              | [86c4864c0a](https://bsd-hardware.info/?probe=86c4864c0a) | Dec 11, 2023 |
| Dell          | Latitude E6510              | [dc2d54a168](https://bsd-hardware.info/?probe=dc2d54a168) | Dec 11, 2023 |
| HP            | ZBook 17 G2                 | [406d7a0572](https://bsd-hardware.info/?probe=406d7a0572) | Dec 07, 2023 |
| Lenovo        | ThinkPad W520 4270CTO       | [e63bc464f2](https://bsd-hardware.info/?probe=e63bc464f2) | Dec 05, 2023 |
| HP            | ZBook 17 G2                 | [cc4538374c](https://bsd-hardware.info/?probe=cc4538374c) | Dec 05, 2023 |
| Toshiba       | Satellite C50-B             | [34db2bdd7d](https://bsd-hardware.info/?probe=34db2bdd7d) | Dec 03, 2023 |
| Star Labs     | LabTop                      | [e8dcf01d78](https://bsd-hardware.info/?probe=e8dcf01d78) | Dec 02, 2023 |
| HP            | Notebook                    | [aff6430eb2](https://bsd-hardware.info/?probe=aff6430eb2) | Nov 24, 2023 |
| Deciso        | NetBoard-A10_Gen.3          | [2ea96f8806](https://bsd-hardware.info/?probe=2ea96f8806) | Nov 21, 2023 |
| TUXEDO        | Aura 15 Gen1                | [7a6b4537f3](https://bsd-hardware.info/?probe=7a6b4537f3) | Oct 29, 2023 |
| Deciso        | NetBoard-A10                | [d0ee609c75](https://bsd-hardware.info/?probe=d0ee609c75) | Oct 25, 2023 |
| Unknown       | Unknown                     | [ea04f97748](https://bsd-hardware.info/?probe=ea04f97748) | Oct 17, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [5be3eb1296](https://bsd-hardware.info/?probe=5be3eb1296) | Oct 08, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [0aac5f52c9](https://bsd-hardware.info/?probe=0aac5f52c9) | Oct 08, 2023 |
| Lenovo        | ThinkPad X230 2325J67       | [bfbc6beca8](https://bsd-hardware.info/?probe=bfbc6beca8) | Oct 04, 2023 |
| HP            | ZBook 17 G2                 | [4e12d36770](https://bsd-hardware.info/?probe=4e12d36770) | Oct 03, 2023 |
| HP            | ZBook 17 G2                 | [f29233649e](https://bsd-hardware.info/?probe=f29233649e) | Sep 20, 2023 |
| OEGStone      | doceo 510                   | [9f3b47e30f](https://bsd-hardware.info/?probe=9f3b47e30f) | Sep 13, 2023 |
| HP            | ZBook 17 G2                 | [e2d694053a](https://bsd-hardware.info/?probe=e2d694053a) | Sep 10, 2023 |
| HP            | EliteBook 8570p             | [cfecf51114](https://bsd-hardware.info/?probe=cfecf51114) | Sep 04, 2023 |
| HP            | EliteBook 8570p             | [d240fba8b7](https://bsd-hardware.info/?probe=d240fba8b7) | Sep 03, 2023 |
| HP            | EliteBook 8570p             | [0dda7a609c](https://bsd-hardware.info/?probe=0dda7a609c) | Aug 29, 2023 |
| Lenovo        | ThinkPad X230 2325IB1       | [41fbf7d1ca](https://bsd-hardware.info/?probe=41fbf7d1ca) | Aug 26, 2023 |
| Dell          | Latitude E6420              | [a085ba3865](https://bsd-hardware.info/?probe=a085ba3865) | Aug 25, 2023 |
| Lenovo        | ThinkPad P50 20EN0009MS     | [4b3fcfa17e](https://bsd-hardware.info/?probe=4b3fcfa17e) | Aug 25, 2023 |
| ASUSTek       | S500CA                      | [019366a664](https://bsd-hardware.info/?probe=019366a664) | Aug 25, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0UD0... | [3c3610a93f](https://bsd-hardware.info/?probe=3c3610a93f) | Aug 19, 2023 |
| HP            | EliteBook 8570p             | [434ec73823](https://bsd-hardware.info/?probe=434ec73823) | Aug 18, 2023 |
| ASUSTek       | 1001P                       | [ac53dba211](https://bsd-hardware.info/?probe=ac53dba211) | Aug 11, 2023 |
| ASUSTek       | 1001P                       | [2424d8acdc](https://bsd-hardware.info/?probe=2424d8acdc) | Aug 11, 2023 |
| Samsung       | Q210                        | [2e25c6d2ec](https://bsd-hardware.info/?probe=2e25c6d2ec) | Aug 03, 2023 |
| Samsung       | Q210                        | [d3c5ab902d](https://bsd-hardware.info/?probe=d3c5ab902d) | Aug 03, 2023 |
| HP            | EliteBook 8570p             | [2619fadb11](https://bsd-hardware.info/?probe=2619fadb11) | Jul 29, 2023 |
| Dell          | Latitude 5480               | [e1521ed9d2](https://bsd-hardware.info/?probe=e1521ed9d2) | Jul 26, 2023 |
| ASUSTek       | 1015PX                      | [b0745153e4](https://bsd-hardware.info/?probe=b0745153e4) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [56fc67d3eb](https://bsd-hardware.info/?probe=56fc67d3eb) | Jul 22, 2023 |
| HP            | EliteBook 8570p             | [9f4f71236e](https://bsd-hardware.info/?probe=9f4f71236e) | Jul 21, 2023 |
| Dell          | Precision 5550              | [4c9dd227a7](https://bsd-hardware.info/?probe=4c9dd227a7) | Jul 20, 2023 |
| ASUSTek       | 1015PX                      | [dc06c76cf9](https://bsd-hardware.info/?probe=dc06c76cf9) | Jul 19, 2023 |
| HP            | EliteBook 8570p             | [44b85aad5e](https://bsd-hardware.info/?probe=44b85aad5e) | Jul 07, 2023 |
| HP            | EliteBook 8570p             | [03c29939fc](https://bsd-hardware.info/?probe=03c29939fc) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | [748ae83ba1](https://bsd-hardware.info/?probe=748ae83ba1) | Jun 27, 2023 |
| HP            | EliteBook 850 G5            | [4bae8cd192](https://bsd-hardware.info/?probe=4bae8cd192) | Jun 27, 2023 |
| HP            | EliteBook 8570p             | [e7dfbf94d0](https://bsd-hardware.info/?probe=e7dfbf94d0) | Jun 25, 2023 |
| HP            | EliteBook 8570p             | [53bbc07cc8](https://bsd-hardware.info/?probe=53bbc07cc8) | Jun 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | [d8079e6155](https://bsd-hardware.info/?probe=d8079e6155) | Jun 16, 2023 |
| Notebook      | NL5xRU                      | [04ca736537](https://bsd-hardware.info/?probe=04ca736537) | Jun 15, 2023 |
| Fujitsu Si... | AMILO Li3710                | [f6540a4d85](https://bsd-hardware.info/?probe=f6540a4d85) | Jun 13, 2023 |
| HP            | EliteBook 8570p             | [22572f1df6](https://bsd-hardware.info/?probe=22572f1df6) | Jun 01, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [6701dce30e](https://bsd-hardware.info/?probe=6701dce30e) | May 28, 2023 |
| HP            | EliteBook 8570p             | [65376d6b42](https://bsd-hardware.info/?probe=65376d6b42) | May 27, 2023 |
| HP            | EliteBook 8570p             | [a1a68c0f7d](https://bsd-hardware.info/?probe=a1a68c0f7d) | May 24, 2023 |
| HP            | EliteBook 8570p             | [70d54595c2](https://bsd-hardware.info/?probe=70d54595c2) | May 19, 2023 |
| HP            | EliteBook 8570p             | [e252dc5ff2](https://bsd-hardware.info/?probe=e252dc5ff2) | May 15, 2023 |
| TUXEDO        | Aura 15 Gen1                | [3d889e8b9b](https://bsd-hardware.info/?probe=3d889e8b9b) | May 11, 2023 |
| Fujitsu Si... | AMILO Li3710                | [214b0c30e0](https://bsd-hardware.info/?probe=214b0c30e0) | Apr 23, 2023 |
| HP            | EliteBook 8570p             | [6e82f69c4c](https://bsd-hardware.info/?probe=6e82f69c4c) | Apr 20, 2023 |
| Samsung       | N150/N210/N220              | [f6e5189f54](https://bsd-hardware.info/?probe=f6e5189f54) | Apr 11, 2023 |
| Lenovo        | ThinkPad X280 20KESB4T00    | [fb6c7b3b09](https://bsd-hardware.info/?probe=fb6c7b3b09) | Apr 11, 2023 |
| Fujitsu Si... | AMILO Li3710                | [6dabd5d84a](https://bsd-hardware.info/?probe=6dabd5d84a) | Apr 08, 2023 |
| Lenovo        | ThinkPad X230 23255NG       | [2ef93a7621](https://bsd-hardware.info/?probe=2ef93a7621) | Mar 29, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [c83b0dda87](https://bsd-hardware.info/?probe=c83b0dda87) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [9ac4738956](https://bsd-hardware.info/?probe=9ac4738956) | Mar 18, 2023 |
| OEGStone      | W54_55SU1,SUW               | [7a2b28c47f](https://bsd-hardware.info/?probe=7a2b28c47f) | Mar 17, 2023 |
| ASUSTek       | 1001P                       | [76eae56ba3](https://bsd-hardware.info/?probe=76eae56ba3) | Mar 15, 2023 |
| OEGStone      | W54_55SU1,SUW               | [64316408f0](https://bsd-hardware.info/?probe=64316408f0) | Mar 15, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [89a5ee25f9](https://bsd-hardware.info/?probe=89a5ee25f9) | Mar 14, 2023 |
| Dynabook E... | Satellite Pro E10-G-101     | [c58a37ef03](https://bsd-hardware.info/?probe=c58a37ef03) | Mar 14, 2023 |
| Star Labs     | StarBook                    | [80f6445f54](https://bsd-hardware.info/?probe=80f6445f54) | Mar 10, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9466e6d4f4](https://bsd-hardware.info/?probe=9466e6d4f4) | Mar 07, 2023 |
| Deciso        | NetBoard-A10_Gen.3          | [1cca4a556d](https://bsd-hardware.info/?probe=1cca4a556d) | Mar 07, 2023 |
| HP            | EliteBook 8570p             | [1a4897cb53](https://bsd-hardware.info/?probe=1a4897cb53) | Feb 26, 2023 |
| HP            | EliteBook 8570p             | [1e548fa114](https://bsd-hardware.info/?probe=1e548fa114) | Feb 24, 2023 |
| Lenovo        | ThinkPad T460 20FMS3320G    | [c85f94d574](https://bsd-hardware.info/?probe=c85f94d574) | Feb 19, 2023 |
| HP            | EliteBook 8570p             | [1ba2a827d9](https://bsd-hardware.info/?probe=1ba2a827d9) | Feb 18, 2023 |
| Apple         | MacBookPro11,1              | [673f6c0a01](https://bsd-hardware.info/?probe=673f6c0a01) | Feb 17, 2023 |
| Lenovo        | ThinkPad W520 42844DG       | [d341f3c6f6](https://bsd-hardware.info/?probe=d341f3c6f6) | Feb 11, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [b7a491a010](https://bsd-hardware.info/?probe=b7a491a010) | Feb 03, 2023 |
| HP            | EliteBook 8570p             | [17f5e2e3d2](https://bsd-hardware.info/?probe=17f5e2e3d2) | Jan 04, 2023 |
| Star Labs     | Lite                        | [9ad15636dd](https://bsd-hardware.info/?probe=9ad15636dd) | Dec 25, 2022 |
| HP            | EliteBook 8570p             | [7cf06451fd](https://bsd-hardware.info/?probe=7cf06451fd) | Dec 17, 2022 |
| HP            | EliteBook 8570p             | [64c92d49d9](https://bsd-hardware.info/?probe=64c92d49d9) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | [6d10b2a0b4](https://bsd-hardware.info/?probe=6d10b2a0b4) | Dec 11, 2022 |
| HP            | EliteBook 8570p             | [3ad7cec298](https://bsd-hardware.info/?probe=3ad7cec298) | Nov 26, 2022 |
| Dell          | XPS 13 9343                 | [8ec61db3f0](https://bsd-hardware.info/?probe=8ec61db3f0) | Nov 22, 2022 |
| HP            | EliteBook 8570p             | [436a2d30f6](https://bsd-hardware.info/?probe=436a2d30f6) | Nov 16, 2022 |
| Deciso        | NetBoard-A10                | [5d4c95dcac](https://bsd-hardware.info/?probe=5d4c95dcac) | Oct 26, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Fujitsu       | LIFEBOOK U904               | [3a86733538](https://bsd-hardware.info/?probe=3a86733538) | Oct 09, 2022 |
| TUXEDO        | Aura 15 Gen1                | [a49ac2701d](https://bsd-hardware.info/?probe=a49ac2701d) | Oct 02, 2022 |
| Deciso        | NetBoard-A10_Gen.3          | [9b95ddf7b9](https://bsd-hardware.info/?probe=9b95ddf7b9) | Oct 01, 2022 |
| Deciso        | NetBoard-A10_Gen.3          | [5cec3595a3](https://bsd-hardware.info/?probe=5cec3595a3) | Sep 21, 2022 |
| HP            | EliteBook 8570p             | [7c6751649b](https://bsd-hardware.info/?probe=7c6751649b) | Sep 07, 2022 |
| Dell          | XPS 13 9343                 | [ec74af083f](https://bsd-hardware.info/?probe=ec74af083f) | Sep 04, 2022 |
| Dell          | Precision 7710              | [339099bbf0](https://bsd-hardware.info/?probe=339099bbf0) | Sep 01, 2022 |
| Dell          | Inspiron 1545               | [e1a29d8008](https://bsd-hardware.info/?probe=e1a29d8008) | Aug 14, 2022 |
| HUAWEI        | BOM-WXX9                    | [4ba15a31d9](https://bsd-hardware.info/?probe=4ba15a31d9) | Aug 10, 2022 |
| HP            | EliteBook 8570p             | [978f01c546](https://bsd-hardware.info/?probe=978f01c546) | Jul 16, 2022 |
| Deciso        | OPNsense Appliance          | [05fb88304d](https://bsd-hardware.info/?probe=05fb88304d) | Jul 13, 2022 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [866724656a](https://bsd-hardware.info/?probe=866724656a) | Jul 06, 2022 |
| System76      | Gazelle                     | [7e2dbb0a5b](https://bsd-hardware.info/?probe=7e2dbb0a5b) | Jun 28, 2022 |
| System76      | Gazelle                     | [8cb2a30786](https://bsd-hardware.info/?probe=8cb2a30786) | Jun 28, 2022 |
| Fujitsu Si... | AMILO Li3710                | [6d4bc39638](https://bsd-hardware.info/?probe=6d4bc39638) | Jun 18, 2022 |
| HP            | Pavilion Notebook           | [6116216a6d](https://bsd-hardware.info/?probe=6116216a6d) | Jun 15, 2022 |
| Fujitsu Si... | AMILO Li3710                | [387bf3d18f](https://bsd-hardware.info/?probe=387bf3d18f) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | [edebcb2719](https://bsd-hardware.info/?probe=edebcb2719) | Jun 12, 2022 |
| HP            | EliteBook 8570p             | [1067f6ab27](https://bsd-hardware.info/?probe=1067f6ab27) | Jun 03, 2022 |
| Apple         | MacBookPro5,3               | [3b03bdf595](https://bsd-hardware.info/?probe=3b03bdf595) | May 29, 2022 |
| Dell          | XPS 13 9343                 | [44abecc1ef](https://bsd-hardware.info/?probe=44abecc1ef) | May 20, 2022 |
| ASUSTek       | 1001P                       | [6ffa9529a3](https://bsd-hardware.info/?probe=6ffa9529a3) | May 20, 2022 |
| ASUSTek       | 1001P                       | [2820584223](https://bsd-hardware.info/?probe=2820584223) | May 20, 2022 |
| Lenovo        | ThinkPad X230 2325J67       | [3ee0f54d2f](https://bsd-hardware.info/?probe=3ee0f54d2f) | May 12, 2022 |
| TUXEDO        | Aura 15 Gen1                | [49d1cd3009](https://bsd-hardware.info/?probe=49d1cd3009) | May 10, 2022 |
| Packard Be... | EasyNote_MX52-B-071         | [277c9e0a0a](https://bsd-hardware.info/?probe=277c9e0a0a) | May 08, 2022 |
| Dell          | Vostro 5590                 | [1f23973fb4](https://bsd-hardware.info/?probe=1f23973fb4) | May 04, 2022 |
| HP            | Pavilion m6                 | [c720817018](https://bsd-hardware.info/?probe=c720817018) | May 03, 2022 |
| Lenovo        | ThinkPad X240 20AMS1YG01    | [6e38eb1a4e](https://bsd-hardware.info/?probe=6e38eb1a4e) | May 01, 2022 |
| MSI           | Modern 14 B11MOL            | [9a61443be9](https://bsd-hardware.info/?probe=9a61443be9) | Apr 25, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [f7aa3576ae](https://bsd-hardware.info/?probe=f7aa3576ae) | Apr 13, 2022 |
| Lenovo        | ThinkPad X201 3680MG1       | [a2b9975fe2](https://bsd-hardware.info/?probe=a2b9975fe2) | Apr 11, 2022 |
| HP            | EliteBook 8570p             | [0c73871c49](https://bsd-hardware.info/?probe=0c73871c49) | Apr 04, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1be95af210](https://bsd-hardware.info/?probe=1be95af210) | Apr 01, 2022 |
| HP            | EliteBook 8570p             | [7e1e137c8f](https://bsd-hardware.info/?probe=7e1e137c8f) | Mar 20, 2022 |
| Dell          | Latitude E7440              | [a776ebf7f4](https://bsd-hardware.info/?probe=a776ebf7f4) | Mar 19, 2022 |
| Lenovo        | Z50-70 20354                | [a1f85aff27](https://bsd-hardware.info/?probe=a1f85aff27) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | [ab71ed7239](https://bsd-hardware.info/?probe=ab71ed7239) | Mar 10, 2022 |
| Jumper        | EZbook                      | [35869ff0db](https://bsd-hardware.info/?probe=35869ff0db) | Feb 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | [3debf6433b](https://bsd-hardware.info/?probe=3debf6433b) | Feb 02, 2022 |
| Lenovo        | ThinkPad X220 4291H77       | [dd4d3a9dcc](https://bsd-hardware.info/?probe=dd4d3a9dcc) | Feb 02, 2022 |
| HP            | EliteBook 8570p             | [f47789d894](https://bsd-hardware.info/?probe=f47789d894) | Jan 29, 2022 |
| HP            | EliteBook 8570p             | [61406080a7](https://bsd-hardware.info/?probe=61406080a7) | Jan 18, 2022 |
| Jumper        | EZbook                      | [7d648bcdc7](https://bsd-hardware.info/?probe=7d648bcdc7) | Jan 17, 2022 |
| Lenovo        | ThinkPad T410 2522E38       | [2dbb2679f1](https://bsd-hardware.info/?probe=2dbb2679f1) | Jan 17, 2022 |
| Lenovo        | ThinkPad R61 8935WCS        | [9cc0f26f6f](https://bsd-hardware.info/?probe=9cc0f26f6f) | Jan 16, 2022 |
| HP            | EliteBook 8570p             | [1bbb37d4c6](https://bsd-hardware.info/?probe=1bbb37d4c6) | Jan 03, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [5188a12b26](https://bsd-hardware.info/?probe=5188a12b26) | Dec 21, 2021 |
| HP            | Laptop 15-db0xxx            | [812c7f3e36](https://bsd-hardware.info/?probe=812c7f3e36) | Nov 29, 2021 |
| HP            | EliteBook 8570p             | [822a2481bb](https://bsd-hardware.info/?probe=822a2481bb) | Nov 17, 2021 |
| ASUSTek       | 1001P                       | [648081d75b](https://bsd-hardware.info/?probe=648081d75b) | Nov 09, 2021 |
| Dell          | XPS 13 9343                 | [227c2380d0](https://bsd-hardware.info/?probe=227c2380d0) | Nov 04, 2021 |
| Samsung       | 550P5C/550P7C               | [69fe175fb8](https://bsd-hardware.info/?probe=69fe175fb8) | Oct 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9996e06a3d](https://bsd-hardware.info/?probe=9996e06a3d) | Oct 22, 2021 |
| Dell          | XPS 13 9343                 | [4b8421b910](https://bsd-hardware.info/?probe=4b8421b910) | Oct 21, 2021 |
| HP            | 15                          | [e3f26d7245](https://bsd-hardware.info/?probe=e3f26d7245) | Oct 18, 2021 |
| HP            | EliteBook 8570p             | [86613b04d3](https://bsd-hardware.info/?probe=86613b04d3) | Oct 17, 2021 |
| Dell          | XPS 13 9343                 | [7dd8f42ab1](https://bsd-hardware.info/?probe=7dd8f42ab1) | Oct 15, 2021 |
| HP            | EliteBook 8570p             | [27f01061f2](https://bsd-hardware.info/?probe=27f01061f2) | Sep 12, 2021 |
| Dell          | XPS 13 9343                 | [1f9857aa23](https://bsd-hardware.info/?probe=1f9857aa23) | Sep 08, 2021 |
| Apple         | MacBookPro5,1               | [2cba98f24b](https://bsd-hardware.info/?probe=2cba98f24b) | Sep 04, 2021 |
| HP            | EliteBook 8570p             | [fae9e84f60](https://bsd-hardware.info/?probe=fae9e84f60) | Aug 27, 2021 |
| Toshiba       | Satellite L50-C             | [250db17f57](https://bsd-hardware.info/?probe=250db17f57) | Aug 20, 2021 |
| Toshiba       | Satellite L50-C             | [a2e1cbd3d8](https://bsd-hardware.info/?probe=a2e1cbd3d8) | Aug 20, 2021 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | [f7725f06df](https://bsd-hardware.info/?probe=f7725f06df) | Aug 18, 2021 |
| HP            | EliteBook 8570p             | [71092e78e2](https://bsd-hardware.info/?probe=71092e78e2) | Aug 17, 2021 |
| HP            | EliteBook 8570p             | [6e97c9a59e](https://bsd-hardware.info/?probe=6e97c9a59e) | Aug 14, 2021 |
| HP            | ZBook 17 G2                 | [f2d911563a](https://bsd-hardware.info/?probe=f2d911563a) | Aug 07, 2021 |
| HP            | ZBook 17 G2                 | [2faf8af7be](https://bsd-hardware.info/?probe=2faf8af7be) | Jul 30, 2021 |
| HP            | ZBook 17 G2                 | [c7fb9e9dee](https://bsd-hardware.info/?probe=c7fb9e9dee) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | [50c349b7b5](https://bsd-hardware.info/?probe=50c349b7b5) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | [6149ab50a8](https://bsd-hardware.info/?probe=6149ab50a8) | Jul 24, 2021 |
| HP            | ZBook 17 G2                 | [1ef99f31dd](https://bsd-hardware.info/?probe=1ef99f31dd) | Jul 23, 2021 |
| HP            | ProBook 440 G7              | [63dc88528c](https://bsd-hardware.info/?probe=63dc88528c) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | [7138e2a9e7](https://bsd-hardware.info/?probe=7138e2a9e7) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | [b73eb50747](https://bsd-hardware.info/?probe=b73eb50747) | Jul 16, 2021 |
| HP            | EliteBook 8570p             | [462fc329a9](https://bsd-hardware.info/?probe=462fc329a9) | Jul 16, 2021 |
| HP            | ProBook 440 G7              | [d2866f01b5](https://bsd-hardware.info/?probe=d2866f01b5) | Jul 16, 2021 |
| Dell          | Latitude E6410              | [8c904d84e0](https://bsd-hardware.info/?probe=8c904d84e0) | Jun 28, 2021 |
| Lenovo        | ThinkPad T420 4236NHG       | [ea00bc1f1f](https://bsd-hardware.info/?probe=ea00bc1f1f) | Jun 20, 2021 |
| HP            | EliteBook 8570p             | [cc24e867fc](https://bsd-hardware.info/?probe=cc24e867fc) | Jun 19, 2021 |
| Pegatron      | T12Ah                       | [50d37406df](https://bsd-hardware.info/?probe=50d37406df) | Jun 06, 2021 |
| HP            | EliteBook 8570p             | [52ba4e835f](https://bsd-hardware.info/?probe=52ba4e835f) | Jun 03, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [e27342ab94](https://bsd-hardware.info/?probe=e27342ab94) | May 13, 2021 |
| Toshiba       | TECRA M11                   | [6357d0d51f](https://bsd-hardware.info/?probe=6357d0d51f) | May 08, 2021 |
| Pegatron      | T12Ah                       | [ce8d45af17](https://bsd-hardware.info/?probe=ce8d45af17) | May 03, 2021 |
| Acer          | Aspire V5-531               | [edbf1ff1c6](https://bsd-hardware.info/?probe=edbf1ff1c6) | May 01, 2021 |
| Acer          | Aspire V5-531               | [8282b3e5fb](https://bsd-hardware.info/?probe=8282b3e5fb) | May 01, 2021 |
| Dell          | Inspiron 3793               | [c2d56fc369](https://bsd-hardware.info/?probe=c2d56fc369) | Apr 29, 2021 |
| Apple         | MacBookPro8,1               | [d1aaeaad42](https://bsd-hardware.info/?probe=d1aaeaad42) | Apr 26, 2021 |
| Dell          | Inspiron 3793               | [c784e7b290](https://bsd-hardware.info/?probe=c784e7b290) | Apr 25, 2021 |
| Toshiba       | Satellite L50-C             | [9cf9861053](https://bsd-hardware.info/?probe=9cf9861053) | Apr 23, 2021 |
| Pegatron      | T12Ah                       | [5de4060089](https://bsd-hardware.info/?probe=5de4060089) | Apr 23, 2021 |
| Toshiba       | Satellite L50-C             | [94b2e5d5ff](https://bsd-hardware.info/?probe=94b2e5d5ff) | Apr 23, 2021 |
| Samsung       | NC10                        | [3307e80418](https://bsd-hardware.info/?probe=3307e80418) | Apr 17, 2021 |
| Samsung       | NC10                        | [dd4310d56f](https://bsd-hardware.info/?probe=dd4310d56f) | Apr 13, 2021 |
| Apple         | MacBookPro8,1               | [0621acab4e](https://bsd-hardware.info/?probe=0621acab4e) | Apr 09, 2021 |
| Dell          | Latitude E6430s             | [563ad840b0](https://bsd-hardware.info/?probe=563ad840b0) | Apr 07, 2021 |
| Toshiba       | Satellite L50-C             | [ff59142f85](https://bsd-hardware.info/?probe=ff59142f85) | Apr 03, 2021 |
| Apple         | MacBookPro8,1               | [e4e3731289](https://bsd-hardware.info/?probe=e4e3731289) | Apr 01, 2021 |
| Toshiba       | Satellite L50-C             | [32f33a7a8b](https://bsd-hardware.info/?probe=32f33a7a8b) | Mar 31, 2021 |
| Dell          | Latitude E6430s             | [c366bef9bf](https://bsd-hardware.info/?probe=c366bef9bf) | Mar 28, 2021 |
| HP            | EliteBook 8570p             | [ed80dc9019](https://bsd-hardware.info/?probe=ed80dc9019) | Mar 27, 2021 |
| Toshiba       | Satellite L50-C             | [70cf274538](https://bsd-hardware.info/?probe=70cf274538) | Mar 23, 2021 |
| Toshiba       | Satellite C660              | [7d64801e2b](https://bsd-hardware.info/?probe=7d64801e2b) | Mar 21, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [b9eeb28ada](https://bsd-hardware.info/?probe=b9eeb28ada) | Mar 16, 2021 |
| TUXEDO        | Aura 15 Gen1                | [860b1cd65b](https://bsd-hardware.info/?probe=860b1cd65b) | Mar 15, 2021 |
| Toshiba       | Satellite C660              | [83f9d05407](https://bsd-hardware.info/?probe=83f9d05407) | Mar 14, 2021 |
| TUXEDO        | Aura 15 Gen1                | [9a7f08f8c1](https://bsd-hardware.info/?probe=9a7f08f8c1) | Mar 11, 2021 |
| TUXEDO        | Aura 15 Gen1                | [d9661207d7](https://bsd-hardware.info/?probe=d9661207d7) | Mar 11, 2021 |
| Toshiba       | Satellite Pro U400          | [71fd81df30](https://bsd-hardware.info/?probe=71fd81df30) | Mar 07, 2021 |
| Apple         | MacBookPro5,5               | [50ac436475](https://bsd-hardware.info/?probe=50ac436475) | Mar 06, 2021 |
| Dell          | Latitude E5570              | [12eae7a62e](https://bsd-hardware.info/?probe=12eae7a62e) | Mar 05, 2021 |
| Toshiba       | Satellite L50-C             | [3af26c7a29](https://bsd-hardware.info/?probe=3af26c7a29) | Feb 25, 2021 |
| Acer          | Aspire V5-531               | [fc868b6179](https://bsd-hardware.info/?probe=fc868b6179) | Feb 25, 2021 |
| GEO           | GeoBook3                    | [ba18b9bf80](https://bsd-hardware.info/?probe=ba18b9bf80) | Feb 19, 2021 |
| HP            | 250 G7 Notebook PC          | [366f8d1eaf](https://bsd-hardware.info/?probe=366f8d1eaf) | Feb 18, 2021 |
| Acer          | Aspire V5-531               | [ad4634140e](https://bsd-hardware.info/?probe=ad4634140e) | Feb 16, 2021 |
| HP            | 250 G7 Notebook PC          | [a3380d4b0c](https://bsd-hardware.info/?probe=a3380d4b0c) | Feb 16, 2021 |
| Pegatron      | T12Ah                       | [a5ab7068dc](https://bsd-hardware.info/?probe=a5ab7068dc) | Feb 14, 2021 |
| Lenovo        | ThinkPad X200 7459ZLW       | [9fbba84be0](https://bsd-hardware.info/?probe=9fbba84be0) | Feb 13, 2021 |
| Dell          | Latitude E6420              | [6bf1f5fe84](https://bsd-hardware.info/?probe=6bf1f5fe84) | Feb 12, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2b0f35d7a9](https://bsd-hardware.info/?probe=2b0f35d7a9) | Feb 12, 2021 |
| HP            | EliteBook 8570p             | [72137c63f8](https://bsd-hardware.info/?probe=72137c63f8) | Feb 09, 2021 |
| Alienware     | M18xR1                      | [67a336fac6](https://bsd-hardware.info/?probe=67a336fac6) | Feb 08, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [39c8cd6d0c](https://bsd-hardware.info/?probe=39c8cd6d0c) | Feb 08, 2021 |
| Sony          | VPCF12C5E                   | [df8c1de8a5](https://bsd-hardware.info/?probe=df8c1de8a5) | Feb 07, 2021 |
| Toshiba       | Satellite L50-C             | [7a5a694be1](https://bsd-hardware.info/?probe=7a5a694be1) | Feb 06, 2021 |
| Apple         | MacBookPro5,5               | [254e518190](https://bsd-hardware.info/?probe=254e518190) | Feb 03, 2021 |
| HP            | EliteBook 8570p             | [46c938b853](https://bsd-hardware.info/?probe=46c938b853) | Feb 01, 2021 |
| HP            | EliteBook 8570p             | [b3eb492602](https://bsd-hardware.info/?probe=b3eb492602) | Jan 31, 2021 |
| Pegatron      | T12Ah                       | [4bda74f229](https://bsd-hardware.info/?probe=4bda74f229) | Jan 31, 2021 |
| Acer          | Aspire V5-531               | [b917d2b6ad](https://bsd-hardware.info/?probe=b917d2b6ad) | Jan 30, 2021 |
| Toshiba       | Satellite L50-C             | [98af88dfe6](https://bsd-hardware.info/?probe=98af88dfe6) | Jan 30, 2021 |
| Toshiba       | Satellite L50-C             | [f76ea8946b](https://bsd-hardware.info/?probe=f76ea8946b) | Jan 28, 2021 |
| Acer          | Aspire V5-531               | [41caa6acaa](https://bsd-hardware.info/?probe=41caa6acaa) | Jan 24, 2021 |
| HP            | EliteBook 8570p             | [c2e361eeff](https://bsd-hardware.info/?probe=c2e361eeff) | Jan 23, 2021 |
| Pegatron      | T12Ah                       | [e9c5982872](https://bsd-hardware.info/?probe=e9c5982872) | Jan 23, 2021 |
| HP            | EliteBook 8570p             | [86e5ba4c5b](https://bsd-hardware.info/?probe=86e5ba4c5b) | Jan 22, 2021 |
| HP            | EliteBook 8570p             | [fcedf7a28d](https://bsd-hardware.info/?probe=fcedf7a28d) | Jan 19, 2021 |
| HP            | EliteBook 8570p             | [bb4f8afc82](https://bsd-hardware.info/?probe=bb4f8afc82) | Jan 09, 2021 |
| HP            | EliteBook 8570p             | [97a3ac7e36](https://bsd-hardware.info/?probe=97a3ac7e36) | Jan 08, 2021 |
| HP            | EliteBook 8570p             | [60d9540d35](https://bsd-hardware.info/?probe=60d9540d35) | Dec 31, 2020 |
| Pegatron      | T12Ah                       | [427bb18c90](https://bsd-hardware.info/?probe=427bb18c90) | Dec 27, 2020 |
| Toshiba       | Satellite L50-C             | [8195760dd6](https://bsd-hardware.info/?probe=8195760dd6) | Dec 23, 2020 |
| Samsung       | N140                        | [cab912c576](https://bsd-hardware.info/?probe=cab912c576) | Dec 21, 2020 |
| Toshiba       | Satellite L50-C             | [2b478c0d01](https://bsd-hardware.info/?probe=2b478c0d01) | Dec 08, 2020 |
| Acer          | Aspire V5-531               | [f62cab95dd](https://bsd-hardware.info/?probe=f62cab95dd) | Dec 03, 2020 |
| HP            | EliteBook 8570p             | [1f3fa432dc](https://bsd-hardware.info/?probe=1f3fa432dc) | Nov 21, 2020 |
| HP            | Compaq nx7400 (RU430ET#A... | [c9c7bae008](https://bsd-hardware.info/?probe=c9c7bae008) | Nov 01, 2020 |
| Toshiba       | Satellite L50-C             | [e5c99b958d](https://bsd-hardware.info/?probe=e5c99b958d) | Oct 31, 2020 |
| Acer          | Aspire V5-531               | [f9a374a310](https://bsd-hardware.info/?probe=f9a374a310) | Oct 30, 2020 |
| Lenovo        | ThinkPad T560 20FJS0CE00    | [be16cb1839](https://bsd-hardware.info/?probe=be16cb1839) | Oct 19, 2020 |
| Panasonic     | CF-C1BT02EGE                | [8a80fb614e](https://bsd-hardware.info/?probe=8a80fb614e) | Oct 19, 2020 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | [6cd0b0ed25](https://bsd-hardware.info/?probe=6cd0b0ed25) | Sep 28, 2020 |
| Lenovo        | ThinkPad T430 2347C32       | [339c63a941](https://bsd-hardware.info/?probe=339c63a941) | Sep 22, 2020 |
| Apple         | MacBookPro8,1               | [89bb299f1e](https://bsd-hardware.info/?probe=89bb299f1e) | Sep 22, 2020 |
| ASUSTek       | ZenBook S UX391UA           | [d7d299f9fc](https://bsd-hardware.info/?probe=d7d299f9fc) | Sep 14, 2020 |
| ASUSTek       | ZenBook S UX391UA           | [ec434bfdcd](https://bsd-hardware.info/?probe=ec434bfdcd) | Sep 14, 2020 |
| ASUSTek       | ZenBook S UX391UA           | [628b379afb](https://bsd-hardware.info/?probe=628b379afb) | Sep 14, 2020 |
| ASUSTek       | ZenBook S UX391UA           | [decfd42a65](https://bsd-hardware.info/?probe=decfd42a65) | Sep 13, 2020 |
| Acer          | Aspire V5-531               | [9168df8552](https://bsd-hardware.info/?probe=9168df8552) | Aug 08, 2020 |
| Google        | Lulu                        | [64aef60e6b](https://bsd-hardware.info/?probe=64aef60e6b) | Aug 02, 2020 |
| Toshiba       | Satellite L50-C             | [cef5a64eb8](https://bsd-hardware.info/?probe=cef5a64eb8) | Jul 11, 2020 |
| Acer          | Aspire V5-531               | [2394ca7e03](https://bsd-hardware.info/?probe=2394ca7e03) | Jul 03, 2020 |
| Toshiba       | Satellite L50-C             | [4f34d107bc](https://bsd-hardware.info/?probe=4f34d107bc) | Jul 03, 2020 |
| Toshiba       | Satellite L50-C             | [067478e4be](https://bsd-hardware.info/?probe=067478e4be) | Jul 03, 2020 |
| Lenovo        | ThinkPad X220 42902WU       | [e8a2f44b21](https://bsd-hardware.info/?probe=e8a2f44b21) | May 24, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| helloSystem 0.8.1      | 12        | 5.11%   |
| helloSystem 0.7.0      | 10        | 4.26%   |
| FreeBSD 14.0-CURRENT   | 8         | 3.4%    |
| FreeBSD 13.0           | 8         | 3.4%    |
| FreeBSD 15.0-CURRENT   | 7         | 2.98%   |
| OpenBSD 7.5            | 6         | 2.55%   |
| GhostBSD 25.02-R14.3p2 | 6         | 2.55%   |
| FreeBSD 13.1           | 6         | 2.55%   |
| NomadBSD 20221130      | 5         | 2.13%   |
| OpenBSD 7.2            | 4         | 1.7%    |
| helloSystem 0.5.0      | 4         | 1.7%    |
| helloSystem 0.4.0      | 4         | 1.7%    |
| GhostBSD 20.04.02      | 4         | 1.7%    |
| FreeBSD 14.0           | 4         | 1.7%    |
| FreeBSD 13.2           | 4         | 1.7%    |
| FreeBSD 12.2           | 4         | 1.7%    |
| OpenBSD 7.6            | 3         | 1.28%   |
| OpenBSD 7.1            | 3         | 1.28%   |
| OpenBSD 6.8            | 3         | 1.28%   |
| NomadBSD 20240711      | 3         | 1.28%   |
| NomadBSD 1.4-RC1       | 3         | 1.28%   |
| NomadBSD 1.3.2         | 3         | 1.28%   |
| helloSystem 0.6.0      | 3         | 1.28%   |
| FreeBSD 14.2-p1        | 3         | 1.28%   |
| FreeBSD 14.2           | 3         | 1.28%   |
| FreeBSD 14.1-p2        | 3         | 1.28%   |
| FreeBSD 14.1           | 3         | 1.28%   |
| FreeBSD 14.0-p4        | 3         | 1.28%   |
| OPNsense 24.1.1        | 2         | 0.85%   |
| OPNsense 23.7.6        | 2         | 0.85%   |
| OPNsense 22.4.3        | 2         | 0.85%   |
| helloSystem 0.9.0      | 2         | 0.85%   |
| helloSystem 0.8.2      | 2         | 0.85%   |
| helloSystem 0.8.0      | 2         | 0.85%   |
| GhostBSD 23.02.02      | 2         | 0.85%   |
| FreeBSD 16.0-CURRENT   | 2         | 0.85%   |
| FreeBSD 14.3           | 2         | 0.85%   |
| FreeBSD 14.0-p1        | 2         | 0.85%   |
| FreeBSD 13.2-p2        | 2         | 0.85%   |
| FreeBSD 13.0-p5        | 2         | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 76        | 40.64%  |
| helloSystem | 35        | 18.72%  |
| OpenBSD     | 22        | 11.76%  |
| GhostBSD    | 19        | 10.16%  |
| OPNsense    | 16        | 8.56%   |
| NomadBSD    | 16        | 8.56%   |
| NetBSD      | 1         | 0.53%   |
| FuryBSD     | 1         | 0.53%   |
| DragonFly   | 1         | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 174       | 97.75%  |
| i386  | 4         | 2.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 45        | 23.32%  |
| XFCE          | 31        | 16.06%  |
| Console       | 30        | 15.54%  |
| MATE          | 24        | 12.44%  |
| KDE5          | 20        | 10.36%  |
| Openbox       | 9         | 4.66%   |
| TWM           | 5         | 2.59%   |
| GNOME         | 5         | 2.59%   |
| fvwm          | 5         | 2.59%   |
| i3            | 4         | 2.07%   |
| Cinnamon      | 3         | 1.55%   |
| xinitrc       | 2         | 1.04%   |
| LXQt          | 2         | 1.04%   |
| Budgie        | 2         | 1.04%   |
| X-Cinnamon    | 1         | 0.52%   |
| Potato        | 1         | 0.52%   |
| LXDE          | 1         | 0.52%   |
| KDE6          | 1         | 0.52%   |
| Fluxbox       | 1         | 0.52%   |
| Enlightenment | 1         | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 143       | 79.01%  |
| Console | 33        | 18.23%  |
| Wayland | 5         | 2.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 67        | 35.83%  |
| SLiM    | 50        | 26.74%  |
| SDDM    | 37        | 19.79%  |
| LightDM | 29        | 15.51%  |
| XDM     | 3         | 1.6%    |
| GDM     | 1         | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| C               | 66        | 34.38%  |
| Unknown         | 48        | 25%     |
| en_US           | 44        | 22.92%  |
| en_GB           | 27        | 14.06%  |
| ru_RU           | 1         | 0.52%   |
| it_CH           | 1         | 0.52%   |
| fr_FR           | 1         | 0.52%   |
| en_UK           | 1         | 0.52%   |
| en_GB.US-ASCII  | 1         | 0.52%   |
| en_GB.ISO8859-1 | 1         | 0.52%   |
| be_BY           | 1         | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 147       | 82.58%  |
| BIOS | 31        | 17.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 103       | 55.68%  |
| Ufs     | 46        | 24.86%  |
| Ffs     | 22        | 11.89%  |
| Cd9660  | 13        | 7.03%   |
| Hammer2 | 1         | 0.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 161       | 88.95%  |
| MBR     | 17        | 9.39%   |
| Unknown | 2         | 1.1%    |
| BSD     | 1         | 0.55%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 54        | 30.51%  |
| Hewlett-Packard     | 26        | 14.69%  |
| Dell                | 23        | 12.99%  |
| ASUSTek Computer    | 8         | 4.52%   |
| Apple               | 8         | 4.52%   |
| Samsung Electronics | 7         | 3.95%   |
| Deciso              | 7         | 3.95%   |
| Toshiba             | 5         | 2.82%   |
| Panasonic           | 4         | 2.26%   |
| Acer                | 4         | 2.26%   |
| Star Labs           | 3         | 1.69%   |
| HUAWEI              | 3         | 1.69%   |
| OEGStone            | 2         | 1.13%   |
| MSI                 | 2         | 1.13%   |
| Google              | 2         | 1.13%   |
| Unknown             | 2         | 1.13%   |
| TUXEDO              | 1         | 0.56%   |
| System76            | 1         | 0.56%   |
| Sony                | 1         | 0.56%   |
| Shuttle             | 1         | 0.56%   |
| Pegatron            | 1         | 0.56%   |
| PC Specialist       | 1         | 0.56%   |
| Packard Bell        | 1         | 0.56%   |
| Notebook            | 1         | 0.56%   |
| Jumper              | 1         | 0.56%   |
| GPD                 | 1         | 0.56%   |
| GEO                 | 1         | 0.56%   |
| Fujitsu Siemens     | 1         | 0.56%   |
| Fujitsu             | 1         | 0.56%   |
| Dynabook Europe     | 1         | 0.56%   |
| DFI                 | 1         | 0.56%   |
| Datto               | 1         | 0.56%   |
| Alienware           | 1         | 0.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP EliteBook 8570p                    | 3         | 1.69%   |
| Unknown                               | 3         | 1.69%   |
| Samsung NC10                          | 2         | 1.13%   |
| Panasonic CF-C1BT02EGE                | 2         | 1.13%   |
| Lenovo ThinkPad P14s Gen 1 20Y1000SUK | 2         | 1.13%   |
| HP Pavilion Notebook                  | 2         | 1.13%   |
| Dell XPS 13 9343                      | 2         | 1.13%   |
| Dell Latitude E6420                   | 2         | 1.13%   |
| Dell Inspiron 3793                    | 2         | 1.13%   |
| Dell Inspiron 1545                    | 2         | 1.13%   |
| Deciso NetBoard-A10_Gen.3             | 2         | 1.13%   |
| Deciso NetBoard-A10                   | 2         | 1.13%   |
| Deciso DEC2700 - OPNsense Appliance   | 2         | 1.13%   |
| ASUS ZenBook S UX391UA                | 2         | 1.13%   |
| TUXEDO Aura 15 Gen1                   | 1         | 0.56%   |
| Toshiba TECRA M11                     | 1         | 0.56%   |
| Toshiba Satellite Pro U400            | 1         | 0.56%   |
| Toshiba Satellite L50-C               | 1         | 0.56%   |
| Toshiba Satellite C660                | 1         | 0.56%   |
| Toshiba Satellite C50-B               | 1         | 0.56%   |
| System76 Gazelle                      | 1         | 0.56%   |
| Star Labs StarBook                    | 1         | 0.56%   |
| Star Labs Lite                        | 1         | 0.56%   |
| Star Labs LabTop                      | 1         | 0.56%   |
| Sony VPCF12C5E                        | 1         | 0.56%   |
| Shuttle NC02U                         | 1         | 0.56%   |
| Samsung Q210                          | 1         | 0.56%   |
| Samsung N150/N210/N220                | 1         | 0.56%   |
| Samsung N140                          | 1         | 0.56%   |
| Samsung 550P5C/550P7C                 | 1         | 0.56%   |
| Samsung 305E4A/305E5A/305E7A          | 1         | 0.56%   |
| Pegatron T12Ah                        | 1         | 0.56%   |
| PC Specialist L140CU                  | 1         | 0.56%   |
| Panasonic CFSZ6-2                     | 1         | 0.56%   |
| Panasonic CF-52VDC1FDE                | 1         | 0.56%   |
| Packard Bell EasyNote_MX52-B-071      | 1         | 0.56%   |
| OEGStone W54_55SU1,SUW                | 1         | 0.56%   |
| OEGStone doceo 510                    | 1         | 0.56%   |
| Notebook NL5xRU                       | 1         | 0.56%   |
| MSI Modern 15 F13MG                   | 1         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 49        | 27.68%  |
| Dell Latitude          | 11        | 6.21%   |
| HP EliteBook           | 9         | 5.08%   |
| Toshiba Satellite      | 4         | 2.26%   |
| HP ProBook             | 4         | 2.26%   |
| HP Pavilion            | 4         | 2.26%   |
| Dell XPS               | 4         | 2.26%   |
| Dell Inspiron          | 4         | 2.26%   |
| Deciso NetBoard-A10    | 4         | 2.26%   |
| Lenovo IdeaPad         | 3         | 1.69%   |
| Dell Precision         | 3         | 1.69%   |
| Apple MacBookPro5      | 3         | 1.69%   |
| Acer Aspire            | 3         | 1.69%   |
| Unknown                | 3         | 1.69%   |
| Samsung NC10           | 2         | 1.13%   |
| Panasonic CF-C1BT02EGE | 2         | 1.13%   |
| MSI Modern             | 2         | 1.13%   |
| Deciso DEC2700         | 2         | 1.13%   |
| ASUS ZenBook           | 2         | 1.13%   |
| Apple MacBookPro8      | 2         | 1.13%   |
| TUXEDO Aura            | 1         | 0.56%   |
| Toshiba TECRA          | 1         | 0.56%   |
| System76 Gazelle       | 1         | 0.56%   |
| Star Labs StarBook     | 1         | 0.56%   |
| Star Labs Lite         | 1         | 0.56%   |
| Star Labs LabTop       | 1         | 0.56%   |
| Sony VPCF12C5E         | 1         | 0.56%   |
| Shuttle NC02U          | 1         | 0.56%   |
| Samsung Q210           | 1         | 0.56%   |
| Samsung N150           | 1         | 0.56%   |
| Samsung N140           | 1         | 0.56%   |
| Samsung 550P5C         | 1         | 0.56%   |
| Samsung 305E4A         | 1         | 0.56%   |
| Pegatron T12Ah         | 1         | 0.56%   |
| PC Specialist L140CU   | 1         | 0.56%   |
| Panasonic CFSZ6-2      | 1         | 0.56%   |
| Panasonic CF-52VDC1FDE | 1         | 0.56%   |
| Packard Bell EasyNote  | 1         | 0.56%   |
| OEGStone W54           | 1         | 0.56%   |
| OEGStone doceo         | 1         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 22        | 12.43%  |
| 2019 | 15        | 8.47%   |
| 2011 | 15        | 8.47%   |
| 2021 | 13        | 7.34%   |
| 2012 | 12        | 6.78%   |
| 2022 | 11        | 6.21%   |
| 2016 | 11        | 6.21%   |
| 2018 | 10        | 5.65%   |
| 2010 | 10        | 5.65%   |
| 2009 | 9         | 5.08%   |
| 2013 | 8         | 4.52%   |
| 2017 | 7         | 3.95%   |
| 2015 | 7         | 3.95%   |
| 2024 | 6         | 3.39%   |
| 2014 | 6         | 3.39%   |
| 2008 | 6         | 3.39%   |
| 2023 | 5         | 2.82%   |
| 2025 | 2         | 1.13%   |
| 2007 | 2         | 1.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 177       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 172       | 97.18%  |
| Yes  | 5         | 2.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 75        | 41.67%  |
| 16.01-24.0  | 48        | 26.67%  |
| 4.01-8.0    | 36        | 20%     |
| 32.01-64.0  | 10        | 5.56%   |
| 2.01-3.0    | 5         | 2.78%   |
| 3.01-4.0    | 2         | 1.11%   |
| 64.01-256.0 | 2         | 1.11%   |
| 24.01-32.0  | 1         | 0.56%   |
| 0.01-0.5    | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 96        | 52.17%  |
| 0.51-1.0  | 61        | 33.15%  |
| 1.01-2.0  | 16        | 8.7%    |
| 2.01-3.0  | 7         | 3.8%    |
| 4.01-8.0  | 1         | 0.54%   |
| 3.01-4.0  | 1         | 0.54%   |
| 8.01-16.0 | 1         | 0.54%   |
| Unknown   | 1         | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 118       | 62.43%  |
| 0      | 33        | 17.46%  |
| 2      | 31        | 16.4%   |
| 3      | 6         | 3.17%   |
| 4      | 1         | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 138       | 75.82%  |
| Yes       | 44        | 24.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 143       | 80.79%  |
| No        | 34        | 19.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 168       | 94.92%  |
| No        | 9         | 5.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 66.11%  |
| No        | 61        | 33.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| UK      | 177       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| London              | 15        | 7.01%   |
| Brighton            | 9         | 4.21%   |
| Manchester          | 8         | 3.74%   |
| Glasgow             | 6         | 2.8%    |
| Edgware             | 6         | 2.8%    |
| Haywards Heath      | 4         | 1.87%   |
| City of London      | 4         | 1.87%   |
| Swindon             | 3         | 1.4%    |
| Shoreham-by-Sea     | 3         | 1.4%    |
| Oxford              | 3         | 1.4%    |
| Leatherhead         | 3         | 1.4%    |
| Hove                | 3         | 1.4%    |
| Harringay           | 3         | 1.4%    |
| Bognor Regis        | 3         | 1.4%    |
| Worthing            | 2         | 0.93%   |
| Sutton              | 2         | 0.93%   |
| Sunderland          | 2         | 0.93%   |
| Stockport           | 2         | 0.93%   |
| Southwark           | 2         | 0.93%   |
| Southampton         | 2         | 0.93%   |
| Sheffield           | 2         | 0.93%   |
| Rugby               | 2         | 0.93%   |
| Reading             | 2         | 0.93%   |
| Plymouth            | 2         | 0.93%   |
| Peterborough        | 2         | 0.93%   |
| Newham              | 2         | 0.93%   |
| Morden              | 2         | 0.93%   |
| Lewes               | 2         | 0.93%   |
| Lambeth             | 2         | 0.93%   |
| Ipswich             | 2         | 0.93%   |
| Greenwich           | 2         | 0.93%   |
| Gloucester          | 2         | 0.93%   |
| East Grinstead      | 2         | 0.93%   |
| Coventry            | 2         | 0.93%   |
| City of Westminster | 2         | 0.93%   |
| Bradford            | 2         | 0.93%   |
| Addlestone          | 2         | 0.93%   |
| Wraysbury           | 1         | 0.47%   |
| Woking              | 1         | 0.47%   |
| West Bromwich       | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 43        | 67     | 23.12%  |
| WDC                 | 19        | 26     | 10.22%  |
| Toshiba             | 14        | 28     | 7.53%   |
| Seagate             | 14        | 21     | 7.53%   |
| Kingston            | 9         | 13     | 4.84%   |
| Crucial             | 9         | 10     | 4.84%   |
| Intel               | 7         | 7      | 3.76%   |
| Hitachi             | 7         | 12     | 3.76%   |
| SanDisk             | 6         | 6      | 3.23%   |
| HGST                | 6         | 46     | 3.23%   |
| NVMe                | 5         | 5      | 2.69%   |
| Transcend           | 4         | 9      | 2.15%   |
| SK hynix            | 4         | 5      | 2.15%   |
| Micron Technology   | 3         | 3      | 1.61%   |
| LITEON              | 3         | 4      | 1.61%   |
| Apple               | 3         | 5      | 1.61%   |
| XUM                 | 2         | 2      | 1.08%   |
| Star Drive          | 2         | 2      | 1.08%   |
| Phison              | 2         | 2      | 1.08%   |
| Fujitsu             | 2         | 7      | 1.08%   |
| Corsair             | 2         | 4      | 1.08%   |
| UMIS                | 1         | 1      | 0.54%   |
| SPCC                | 1         | 1      | 0.54%   |
| Solid State Storage | 1         | 1      | 0.54%   |
| SATA3 60            | 1         | 1      | 0.54%   |
| PNY                 | 1         | 1      | 0.54%   |
| OWC                 | 1         | 1      | 0.54%   |
| OCZ                 | 1         | 2      | 0.54%   |
| MicroDream          | 1         | 1      | 0.54%   |
| Lexar               | 1         | 1      | 0.54%   |
| Intenso             | 1         | 1      | 0.54%   |
| Integral            | 1         | 1      | 0.54%   |
| Innodisk            | 1         | 1      | 0.54%   |
| FORESEE             | 1         | 1      | 0.54%   |
| FIKWOT              | 1         | 1      | 0.54%   |
| External            | 1         | 1      | 0.54%   |
| CT2000P3            | 1         | 1      | 0.54%   |
| China               | 1         | 1      | 0.54%   |
| BIWIN               | 1         | 2      | 0.54%   |
| Apacer              | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 7         | 3.66%   |
| HGST HTS725050A7E630 500GB           | 4         | 2.09%   |
| Transcend TS256GMTE652T2 256GB       | 3         | 1.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.57%   |
| Samsung HM251JX 250GB                | 3         | 1.57%   |
| XUM HX256GSSDSATA3 256GB             | 2         | 1.05%   |
| WDC WDS250G2B0B-00YS70 250GB         | 2         | 1.05%   |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 1.05%   |
| WDC WD3200BPVT-80JJ5T0 320GB         | 2         | 1.05%   |
| WDC WD1600BEVT-80A23T0 160GB         | 2         | 1.05%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 1.05%   |
| Seagate ST9320423AS 320GB            | 2         | 1.05%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.05%   |
| Samsung SSD PM851 M.2 2280 256GB     | 2         | 1.05%   |
| Samsung SSD 980 1TB                  | 2         | 1.05%   |
| Samsung SSD 870 EVO 500GB            | 2         | 1.05%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.05%   |
| Samsung SSD 840 EVO 120GB            | 2         | 1.05%   |
| Samsung MZVLW512HMJP-00000 512GB     | 2         | 1.05%   |
| Kingston SMS200S360G 64GB            | 2         | 1.05%   |
| Hitachi HTS725032A9A364 320GB        | 2         | 1.05%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.05%   |
| Crucial CT500P2SSD8 500GB            | 2         | 1.05%   |
| WDC WDS250G2B0A 250GB                | 1         | 0.52%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.52%   |
| WDC WD7500BPKX-60HPJT0 752GB         | 1         | 0.52%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.52%   |
| WDC WD3200BPVT-75JJ5T0 320GB         | 1         | 0.52%   |
| WDC WD2500BEVT-80A23T0 250GB         | 1         | 0.52%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 1         | 0.52%   |
| WDC WD1600BEVS-08VAT2 160GB          | 1         | 0.52%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.52%   |
| UMIS RPJTJ512MEE1OWX 512GB           | 1         | 0.52%   |
| Transcend TS128GMTE110S 128GB        | 1         | 0.52%   |
| Toshiba THNSNJ128GMCU 128GB          | 1         | 0.52%   |
| Toshiba THNSF5256GPUK 256GB          | 1         | 0.52%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.52%   |
| Toshiba MK8034GSX 80GB               | 1         | 0.52%   |
| Toshiba MK5061GSY 500GB              | 1         | 0.52%   |
| Toshiba KXG5AZNV256G 256GB           | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 21     | 23.33%  |
| WDC                 | 12        | 15     | 20%     |
| Toshiba             | 10        | 22     | 16.67%  |
| Hitachi             | 7         | 12     | 11.67%  |
| HGST                | 6         | 46     | 10%     |
| Samsung Electronics | 5         | 5      | 8.33%   |
| NVMe                | 4         | 4      | 6.67%   |
| Fujitsu             | 2         | 7      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 46     | 29.03%  |
| Kingston            | 9         | 13     | 9.68%   |
| WDC                 | 6         | 10     | 6.45%   |
| SanDisk             | 6         | 6      | 6.45%   |
| Intel               | 5         | 5      | 5.38%   |
| Crucial             | 5         | 6      | 5.38%   |
| Micron Technology   | 3         | 3      | 3.23%   |
| LITEON              | 3         | 4      | 3.23%   |
| Apple               | 3         | 5      | 3.23%   |
| XUM                 | 2         | 2      | 2.15%   |
| Corsair             | 2         | 4      | 2.15%   |
| Toshiba             | 1         | 1      | 1.08%   |
| Star Drive          | 1         | 1      | 1.08%   |
| SPCC                | 1         | 1      | 1.08%   |
| SATA3 60            | 1         | 1      | 1.08%   |
| PNY                 | 1         | 1      | 1.08%   |
| Phison              | 1         | 1      | 1.08%   |
| OWC                 | 1         | 1      | 1.08%   |
| OCZ                 | 1         | 2      | 1.08%   |
| NVMe                | 1         | 1      | 1.08%   |
| MicroDream          | 1         | 1      | 1.08%   |
| Lexar               | 1         | 1      | 1.08%   |
| Intenso             | 1         | 1      | 1.08%   |
| Integral            | 1         | 1      | 1.08%   |
| Innodisk            | 1         | 1      | 1.08%   |
| FORESEE             | 1         | 1      | 1.08%   |
| FIKWOT              | 1         | 1      | 1.08%   |
| External            | 1         | 1      | 1.08%   |
| CT2000P3            | 1         | 1      | 1.08%   |
| China               | 1         | 1      | 1.08%   |
| BIWIN               | 1         | 2      | 1.08%   |
| Apacer              | 1         | 1      | 1.08%   |
| A-DATA Technology   | 1         | 1      | 1.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 84        | 128    | 49.7%   |
| HDD  | 52        | 132    | 30.77%  |
| NVMe | 33        | 46     | 19.53%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 123       | 260    | 78.85%  |
| NVMe | 33        | 46     | 21.15%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 106       | 186    | 79.7%   |
| 0.51-1.0   | 18        | 64     | 13.53%  |
| 1.01-2.0   | 8         | 9      | 6.02%   |
| 3.01-4.0   | 1         | 1      | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 68        | 34.52%  |
| 251-500    | 37        | 18.78%  |
| 1-20       | 37        | 18.78%  |
| 21-50      | 19        | 9.64%   |
| 51-100     | 17        | 8.63%   |
| 501-1000   | 14        | 7.11%   |
| Unknown    | 3         | 1.52%   |
| 1001-2000  | 2         | 1.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 156       | 81.25%  |
| 21-50   | 19        | 9.9%    |
| 51-100  | 8         | 4.17%   |
| 101-250 | 6         | 3.13%   |
| Unknown | 3         | 1.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                       | 4         | 10     | 13.79%  |
| HGST HTS721010A9E630 1TB                         | 2         | 26     | 6.9%    |
| WDC WD7500BPKX-60HPJT0 752GB                     | 1         | 1      | 3.45%   |
| WDC WD3200BPVT-75JJ5T0 320GB                     | 1         | 1      | 3.45%   |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 3.45%   |
| WDC WD1600BEVT-80A23T0 160GB                     | 1         | 1      | 3.45%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 3.45%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 3.45%   |
| Seagate ST9160821AS 160GB                        | 1         | 1      | 3.45%   |
| Seagate ST2000LM003 HN-M201RAD 2TB               | 1         | 1      | 3.45%   |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 1         | 1      | 3.45%   |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 3.45%   |
| Samsung Electronics HM251JX 250GB                | 1         | 1      | 3.45%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 3.45%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 3.45%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB       | 1         | 1      | 3.45%   |
| Kingston SV300S37A120G 120GB                     | 1         | 3      | 3.45%   |
| Kingston SUV400S37120G 120GB                     | 1         | 1      | 3.45%   |
| Intel SSDSC2BB480G4T 480GB                       | 1         | 1      | 3.45%   |
| Hitachi HTS727575A9E362 752GB                    | 1         | 6      | 3.45%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 3.45%   |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 3.45%   |
| Hitachi HTS543232A7A384 320GB                    | 1         | 1      | 3.45%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 3.45%   |
| A-DATA Technology SP550 240GB                    | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 5         | 37     | 18.52%  |
| WDC                 | 4         | 4      | 14.81%  |
| Seagate             | 4         | 4      | 14.81%  |
| Samsung Electronics | 4         | 4      | 14.81%  |
| Hitachi             | 4         | 9      | 14.81%  |
| Micron Technology   | 2         | 2      | 7.41%   |
| Kingston            | 2         | 4      | 7.41%   |
| Intel               | 1         | 1      | 3.7%    |
| A-DATA Technology   | 1         | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 5         | 37     | 25%     |
| WDC                 | 4         | 4      | 20%     |
| Seagate             | 4         | 4      | 20%     |
| Hitachi             | 4         | 9      | 20%     |
| Samsung Electronics | 3         | 3      | 15%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 57     | 73.08%  |
| SSD  | 7         | 9      | 26.92%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Transcend TS128GMTE110S 128GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor    | Notebooks | Drives | Percent |
|-----------|-----------|--------|---------|
| Transcend | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 126       | 228    | 78.75%  |
| Malfunc  | 25        | 66     | 15.63%  |
| Detected | 8         | 11     | 5%      |
| Failed   | 1         | 1      | 0.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 117       | 58.79%  |
| Samsung Electronics                     | 20        | 10.05%  |
| AMD                                     | 11        | 5.53%   |
| SK hynix                                | 8         | 4.02%   |
| Transcend                               | 7         | 3.52%   |
| SanDisk                                 | 6         | 3.02%   |
| Phison Electronics                      | 5         | 2.51%   |
| Micron/Crucial Technology               | 5         | 2.51%   |
| Toshiba                                 | 4         | 2.01%   |
| Nvidia                                  | 4         | 2.01%   |
| Solid State Storage Technology          | 2         | 1.01%   |
| Shenzhen Unionmemory Information System | 2         | 1.01%   |
| Micron Technology                       | 2         | 1.01%   |
| Kingston Technology Company             | 2         | 1.01%   |
| Silicon Motion                          | 1         | 0.5%    |
| Shenzhen Techwinsemi Technology         | 1         | 0.5%    |
| Marvell Technology Group                | 1         | 0.5%    |
| ASMedia Technology                      | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 6.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 6.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 6.02%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 4.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 4.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 3.7%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 7         | 3.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 3.24%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)    | 5         | 2.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.31%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 2.31%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 2.31%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 1.85%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 1.85%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4         | 1.85%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 1.39%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.39%   |
| Intel SSD 660P Series                                                          | 3         | 1.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.39%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 1.39%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 3         | 1.39%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 3         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.39%   |
| Transcend NVMe PCIe SSD 220S/240S/MTE710T                                      | 2         | 0.93%   |
| Toshiba XG5 NVMe SSD Controller                                                | 2         | 0.93%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 0.93%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 2         | 0.93%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 0.93%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 0.93%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 2         | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 112       | 54.37%  |
| NVMe | 65        | 31.55%  |
| IDE  | 15        | 7.28%   |
| RAID | 14        | 6.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 151       | 85.31%  |
| AMD    | 25        | 14.12%  |
| 11th   | 1         | 0.56%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| AMD Ryzen Embedded V1500B                  | 7         | 3.93%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 6         | 3.37%   |
| Intel CPU Version                          | 5         | 2.81%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 4         | 2.25%   |
| Intel Core i7-3520M CPU @ 2.90GHz          | 4         | 2.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 4         | 2.25%   |
| Intel Core i5-7300U CPU @ 2.60GHz          | 4         | 2.25%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 4         | 2.25%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 4         | 2.25%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 4         | 2.25%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 3         | 1.69%   |
| Intel Core i5-4300U CPU @ 1.90GHz          | 3         | 1.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 3         | 1.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 2         | 1.12%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz         | 2         | 1.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 1.12%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 2         | 1.12%   |
| Intel Core i5-4288U CPU @ 2.60GHz          | 2         | 1.12%   |
| Intel Core i5-4210U CPU @ 1.70GHz          | 2         | 1.12%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 2         | 1.12%   |
| Intel Core i5-2540M CPU @ 2.60GHz          | 2         | 1.12%   |
| Intel Core i5 CPU M 520 @ 2.40GHz          | 2         | 1.12%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz       | 2         | 1.12%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz       | 2         | 1.12%   |
| Intel Celeron N4000 CPU @ 1.10GHz          | 2         | 1.12%   |
| Intel Celeron CPU N3350 @ 1.10GHz          | 2         | 1.12%   |
| Intel Atom CPU N450 @ 1.66GHz              | 2         | 1.12%   |
| Intel 13th Gen Core i5-1335U               | 2         | 1.12%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 2         | 1.12%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz    | 2         | 1.12%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 1.12%   |
| AMD Ryzen 7 4700U with Radeon Graphics     | 2         | 1.12%   |
| Intel Xeon CPU E3-1535M v5 @ 2.90GHz       | 1         | 0.56%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz   | 1         | 0.56%   |
| Intel Pentium Gold 7505 @ 2.00GHz          | 1         | 0.56%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz     | 1         | 0.56%   |
| Intel Pentium CPU P6100 @ 2.00GHz          | 1         | 0.56%   |
| Intel Pentium CPU N3700 @ 1.60GHz          | 1         | 0.56%   |
| Intel Pentium CPU 967 @ 1.30GHz            | 1         | 0.56%   |
| Intel Pentium CPU 3825U @ 1.90GHz          | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 53        | 29.94%  |
| Intel Core i7        | 38        | 21.47%  |
| Other                | 19        | 10.73%  |
| Intel Core 2 Duo     | 11        | 6.21%   |
| Intel Celeron        | 11        | 6.21%   |
| AMD Ryzen Embedded   | 7         | 3.95%   |
| AMD Ryzen 5          | 5         | 2.82%   |
| Intel Pentium        | 4         | 2.26%   |
| Intel Core i3        | 4         | 2.26%   |
| Intel Atom           | 4         | 2.26%   |
| AMD Ryzen 7          | 3         | 1.69%   |
| AMD Ryzen 7 PRO      | 2         | 1.13%   |
| AMD A6               | 2         | 1.13%   |
| Intel Xeon           | 1         | 0.56%   |
| Intel Pentium Silver | 1         | 0.56%   |
| Intel Pentium Gold   | 1         | 0.56%   |
| Intel Pentium Dual   | 1         | 0.56%   |
| Intel Core m3        | 1         | 0.56%   |
| Intel Core i9        | 1         | 0.56%   |
| Intel Core 2         | 1         | 0.56%   |
| Intel Core           | 1         | 0.56%   |
| AMD Ryzen 5 PRO      | 1         | 0.56%   |
| AMD Ryzen 3 PRO      | 1         | 0.56%   |
| AMD Ryzen 3          | 1         | 0.56%   |
| AMD GX               | 1         | 0.56%   |
| AMD Athlon 64 X2     | 1         | 0.56%   |
| AMD A8               | 1         | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 83        | 46.63%  |
| 4       | 57        | 32.02%  |
| Unknown | 12        | 6.74%   |
| 8       | 10        | 5.62%   |
| 16      | 4         | 2.25%   |
| 12      | 4         | 2.25%   |
| 1       | 4         | 2.25%   |
| 6       | 2         | 1.12%   |
| 32      | 1         | 0.56%   |
| 14      | 1         | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 171       | 96.07%  |
| Unknown | 5         | 2.81%   |
| 2       | 2         | 1.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 118       | 66.67%  |
| 1       | 47        | 26.55%  |
| Unknown | 12        | 6.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 14.69%  |
| SandyBridge   | 16        | 9.04%   |
| IvyBridge     | 15        | 8.47%   |
| Skylake       | 14        | 7.91%   |
| Haswell       | 14        | 7.91%   |
| Penryn        | 10        | 5.65%   |
| Unknown       | 10        | 5.65%   |
| Zen           | 9         | 5.08%   |
| TigerLake     | 9         | 5.08%   |
| Westmere      | 8         | 4.52%   |
| Zen 2         | 6         | 3.39%   |
| Bonnell       | 6         | 3.39%   |
| Core          | 5         | 2.82%   |
| Broadwell     | 5         | 2.82%   |
| Silvermont    | 4         | 2.26%   |
| Goldmont plus | 4         | 2.26%   |
| Goldmont      | 3         | 1.69%   |
| Zen+          | 2         | 1.13%   |
| IceLake       | 2         | 1.13%   |
| CometLake     | 2         | 1.13%   |
| Zen 3         | 1         | 0.56%   |
| Steamroller   | 1         | 0.56%   |
| Nehalem       | 1         | 0.56%   |
| K8 Hammer     | 1         | 0.56%   |
| K10 Llano     | 1         | 0.56%   |
| Jaguar        | 1         | 0.56%   |
| Excavator     | 1         | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 140       | 74.07%  |
| Nvidia | 26        | 13.76%  |
| AMD    | 23        | 12.17%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 8.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 5.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 5.53%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 10        | 5.03%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 10        | 5.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 4.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 3.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 3.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 3.02%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 6         | 3.02%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 2.01%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 4         | 2.01%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 1.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.51%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 1.51%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.51%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 3         | 1.51%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.51%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 1.51%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 1.01%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 2         | 1.01%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 2         | 1.01%   |
| Intel Raptor Lake-P [UHD Graphics]                                                       | 2         | 1.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.01%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 1.01%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.01%   |
| Intel Broadwell-U GT1 [HD Graphics]                                                      | 2         | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.01%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 2         | 1.01%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.01%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.01%   |
| AMD Lucienne                                                                             | 2         | 1.01%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.5%    |
| Nvidia TU117GLM [T550 Laptop GPU]                                                        | 1         | 0.5%    |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.5%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.5%    |
| Nvidia MCP79 [GeForce 8200M G]                                                           | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 105       | 58.99%  |
| 1 x AMD        | 20        | 11.24%  |
| Intel + Nvidia | 17        | 9.55%   |
| 2 x Intel      | 16        | 8.99%   |
| 1 x Nvidia     | 8         | 4.49%   |
| Other          | 7         | 3.93%   |
| 2 x Nvidia     | 2         | 1.12%   |
| Intel + AMD    | 2         | 1.12%   |
| 2 x AMD        | 1         | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 163       | 91.06%  |
| Unknown     | 10        | 5.59%   |
| Proprietary | 6         | 3.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 166       | 92.22%  |
| 1.01-2.0   | 5         | 2.78%   |
| 0.51-1.0   | 4         | 2.22%   |
| 0.01-0.5   | 4         | 2.22%   |
| 5.01-6.0   | 1         | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 22.31%  |
| LG Display              | 19        | 14.62%  |
| BOE                     | 16        | 12.31%  |
| Chimei Innolux          | 13        | 10%     |
| Samsung Electronics     | 8         | 6.15%   |
| Lenovo                  | 8         | 6.15%   |
| Sharp                   | 7         | 5.38%   |
| Philips                 | 4         | 3.08%   |
| Apple                   | 4         | 3.08%   |
| Sony                    | 2         | 1.54%   |
| LG Philips              | 2         | 1.54%   |
| Hewlett-Packard         | 2         | 1.54%   |
| HannStar                | 2         | 1.54%   |
| CPT                     | 2         | 1.54%   |
| Chi Mei Optoelectronics | 2         | 1.54%   |
| Vestel Elektronik       | 1         | 0.77%   |
| SDC                     | 1         | 0.77%   |
| PANDA                   | 1         | 0.77%   |
| Panasonic               | 1         | 0.77%   |
| InnoLux Display         | 1         | 0.77%   |
| InfoVision              | 1         | 0.77%   |
| Iiyama                  | 1         | 0.77%   |
| HPN                     | 1         | 0.77%   |
| Goldstar                | 1         | 0.77%   |
| Gigabyte Technology     | 1         | 0.77%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Philips 271P4 PHL08C3 1920x1080 600x340mm 27.2-inch                   | 4         | 2.92%   |
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch           | 3         | 2.19%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 3         | 2.19%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch               | 2         | 1.46%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch           | 2         | 1.46%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch          | 2         | 1.46%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 2         | 1.46%   |
| CPT LCD Monitor CPT04C4 1024x600 230x140mm 10.6-inch                  | 2         | 1.46%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 340x190mm 15.3-inch      | 2         | 1.46%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 290x170mm 13.2-inch        | 2         | 1.46%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1         | 0.73%   |
| Sony SDM-HS95P SNY2500 1280x1024 380x300mm 19.1-inch                  | 1         | 0.73%   |
| Sony LCD Monitor MS_9005 1920x1200 330x210mm 15.4-inch                | 1         | 0.73%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x170mm 13.9-inch               | 1         | 0.73%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 290x170mm 13.2-inch               | 1         | 0.73%   |
| Sharp LCD Monitor SHP14D1 1920x1200 340x210mm 15.7-inch               | 1         | 0.73%   |
| Sharp LCD Monitor SHP1453 1920x1080 350x190mm 15.7-inch               | 1         | 0.73%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch               | 1         | 0.73%   |
| SDC LCD Monitor 5440x1080                                             | 1         | 0.73%   |
| SDC LCD Monitor 3520x1080                                             | 1         | 0.73%   |
| SDC LCD Monitor 1600x900                                              | 1         | 0.73%   |
| SDC LCD Monitor                                                       | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch  | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 340x190mm 15.3-inch  | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch  | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch  | 1         | 0.73%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 700x390mm 31.5-inch | 1         | 0.73%   |
| Philips LCD Monitor 271P4 5440x1080                                   | 1         | 0.73%   |
| Philips LCD Monitor 271P4 3520x1080                                   | 1         | 0.73%   |
| Philips LCD Monitor 271P4                                             | 1         | 0.73%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch               | 1         | 0.73%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 340x190mm 15.3-inch           | 1         | 0.73%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 0.73%   |
| LG Philips LCD Monitor LPL1279 1680x1050 330x210mm 15.4-inch          | 1         | 0.73%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch          | 1         | 0.73%   |
| LG Display LCD Monitor LGD053B 1920x1080 290x170mm 13.2-inch          | 1         | 0.73%   |
| LG Display LCD Monitor LGD0508 1366x768 310x170mm 13.9-inch           | 1         | 0.73%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 53        | 41.41%  |
| 1366x768 (WXGA)    | 31        | 24.22%  |
| 1280x800 (WXGA)    | 8         | 6.25%   |
| 1600x900 (HD+)     | 7         | 5.47%   |
| 1920x1200 (WUXGA)  | 5         | 3.91%   |
| 1024x600           | 5         | 3.91%   |
| 3200x1800 (QHD+)   | 3         | 2.34%   |
| 3840x2160 (4K)     | 2         | 1.56%   |
| 2880x1800          | 2         | 1.56%   |
| 2560x1600          | 2         | 1.56%   |
| 2560x1440 (QHD)    | 2         | 1.56%   |
| 1440x900 (WXGA+)   | 2         | 1.56%   |
| 5440x1080          | 1         | 0.78%   |
| 3520x1080          | 1         | 0.78%   |
| 1920x540           | 1         | 0.78%   |
| 1680x1050 (WSXGA+) | 1         | 0.78%   |
| 1280x1024 (SXGA)   | 1         | 0.78%   |
| Unknown            | 1         | 0.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 44        | 34.11%  |
| 15      | 42        | 32.56%  |
| 12      | 11        | 8.53%   |
| 17      | 6         | 4.65%   |
| 27      | 5         | 3.88%   |
| 10      | 4         | 3.1%    |
| 14      | 3         | 2.33%   |
| 11      | 3         | 2.33%   |
| 31      | 2         | 1.55%   |
| 42      | 1         | 0.78%   |
| 24      | 1         | 0.78%   |
| 23      | 1         | 0.78%   |
| 22      | 1         | 0.78%   |
| 21      | 1         | 0.78%   |
| 19      | 1         | 0.78%   |
| 18      | 1         | 0.78%   |
| 9       | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 71        | 55.47%  |
| 201-300     | 37        | 28.91%  |
| 351-400     | 7         | 5.47%   |
| 501-600     | 6         | 4.69%   |
| 401-500     | 3         | 2.34%   |
| 601-700     | 2         | 1.56%   |
| 901-1000    | 1         | 0.78%   |
| Unknown     | 1         | 0.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 94        | 79.66%  |
| 16/10   | 20        | 16.95%  |
| 3/2     | 2         | 1.69%   |
| 5/4     | 1         | 0.85%   |
| Unknown | 1         | 0.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 36        | 27.91%  |
| 91-100         | 27        | 20.93%  |
| 101-110        | 13        | 10.08%  |
| 71-80          | 11        | 8.53%   |
| 61-70          | 11        | 8.53%   |
| 121-130        | 6         | 4.65%   |
| 41-50          | 5         | 3.88%   |
| 301-350        | 5         | 3.88%   |
| 201-250        | 4         | 3.1%    |
| 51-60          | 3         | 2.33%   |
| 351-500        | 2         | 1.55%   |
| 111-120        | 2         | 1.55%   |
| 151-200        | 1         | 0.78%   |
| 141-150        | 1         | 0.78%   |
| 501-1000       | 1         | 0.78%   |
| Unknown        | 1         | 0.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 57        | 44.88%  |
| 101-120       | 34        | 26.77%  |
| 51-100        | 15        | 11.81%  |
| 161-240       | 14        | 11.02%  |
| More than 240 | 6         | 4.72%   |
| Unknown       | 1         | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 122       | 67.03%  |
| 0     | 49        | 26.92%  |
| 2     | 10        | 5.49%   |
| 3     | 1         | 0.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 134       | 50.76%  |
| Realtek Semiconductor             | 49        | 18.56%  |
| Qualcomm Atheros                  | 22        | 8.33%   |
| Broadcom                          | 14        | 5.3%    |
| Marvell Technology Group          | 8         | 3.03%   |
| AMD                               | 7         | 2.65%   |
| Nvidia                            | 4         | 1.52%   |
| D-Link System                     | 4         | 1.52%   |
| Hewlett-Packard                   | 3         | 1.14%   |
| Ericsson Business Mobile Networks | 3         | 1.14%   |
| Sierra Wireless                   | 2         | 0.76%   |
| Ralink Technology                 | 2         | 0.76%   |
| Edimax Technology                 | 2         | 0.76%   |
| Dell                              | 2         | 0.76%   |
| ZyXEL Communications              | 1         | 0.38%   |
| TP-Link                           | 1         | 0.38%   |
| Samsung Electronics               | 1         | 0.38%   |
| Ralink                            | 1         | 0.38%   |
| Qualcomm                          | 1         | 0.38%   |
| Lenovo                            | 1         | 0.38%   |
| Fibocom                           | 1         | 0.38%   |
| Apple                             | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 31        | 8.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 23        | 6.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 18        | 5.13%   |
| Intel Wireless 8265 / 8275                                                 | 15        | 4.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 11        | 3.13%   |
| Intel Wireless 8260                                                        | 10        | 2.85%   |
| Intel Wi-Fi 6 AX201                                                        | 10        | 2.85%   |
| Intel Wireless 7260                                                        | 9         | 2.56%   |
| Intel Wi-Fi 6 AX200                                                        | 8         | 2.28%   |
| Intel Centrino Advanced-N 6200                                             | 7         | 1.99%   |
| AMD XGMAC 10GbE Controller                                                 | 7         | 1.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 6         | 1.71%   |
| Intel I211 Gigabit Network Connection                                      | 6         | 1.71%   |
| Intel Ethernet Connection (4) I219-LM                                      | 6         | 1.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)    | 5         | 1.42%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                       | 5         | 1.42%   |
| Intel I210 Gigabit Network Connection                                      | 5         | 1.42%   |
| Intel Ethernet Connection I219-LM                                          | 5         | 1.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 5         | 1.42%   |
| Intel Centrino Ultimate-N 6300                                             | 5         | 1.42%   |
| Intel 82577LM Gigabit Network Connection                                   | 5         | 1.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 4         | 1.14%   |
| Nvidia MCP79 Ethernet                                                      | 4         | 1.14%   |
| Intel Wireless 7265                                                        | 4         | 1.14%   |
| Intel Ethernet Connection I218-LM                                          | 4         | 1.14%   |
| Intel Ethernet Connection (4) I219-V                                       | 4         | 1.14%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 4         | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 0.85%   |
| Intel Wireless 3165                                                        | 3         | 0.85%   |
| Intel Raptor Lake PCH CNVi WiFi                                            | 3         | 0.85%   |
| Intel Ethernet Connection I219-V                                           | 3         | 0.85%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                    | 3         | 0.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 3         | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 2         | 0.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 0.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2         | 0.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 2         | 0.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 2         | 0.57%   |
| Intel Wireless 3160                                                        | 2         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 118       | 64.84%  |
| Qualcomm Atheros      | 21        | 11.54%  |
| Realtek Semiconductor | 19        | 10.44%  |
| Broadcom              | 12        | 6.59%   |
| D-Link System         | 4         | 2.2%    |
| Ralink Technology     | 2         | 1.1%    |
| Edimax Technology     | 2         | 1.1%    |
| ZyXEL Communications  | 1         | 0.55%   |
| TP-Link               | 1         | 0.55%   |
| Sierra Wireless       | 1         | 0.55%   |
| Ralink                | 1         | 0.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 18        | 9.73%   |
| Intel Wireless 8265 / 8275                                                 | 15        | 8.11%   |
| Intel Wireless 8260                                                        | 10        | 5.41%   |
| Intel Wi-Fi 6 AX201                                                        | 10        | 5.41%   |
| Intel Wireless 7260                                                        | 9         | 4.86%   |
| Intel Wi-Fi 6 AX200                                                        | 8         | 4.32%   |
| Intel Centrino Advanced-N 6200                                             | 7         | 3.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 6         | 3.24%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)    | 5         | 2.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 5         | 2.7%    |
| Intel Centrino Ultimate-N 6300                                             | 5         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 4         | 2.16%   |
| Intel Wireless 7265                                                        | 4         | 2.16%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 4         | 2.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 1.62%   |
| Intel Wireless 3165                                                        | 3         | 1.62%   |
| Intel Raptor Lake PCH CNVi WiFi                                            | 3         | 1.62%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 3         | 1.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 2         | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2         | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 2         | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 2         | 1.08%   |
| Intel Wireless 3160                                                        | 2         | 1.08%   |
| Intel WiFi Link 5100                                                       | 2         | 1.08%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                    | 2         | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 2         | 1.08%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 2         | 1.08%   |
| Intel Centrino Advanced-N 6235                                             | 2         | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 2         | 1.08%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter               | 2         | 1.08%   |
| Broadcom BCM4331 802.11a/b/g/n                                             | 2         | 1.08%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                          | 2         | 1.08%   |
| ZyXEL NWD2105 802.11bgn Wireless Adapter [Ralink RT3070]                   | 1         | 0.54%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1         | 0.54%   |
| Sierra Wireless EM7345 4G LTE                                              | 1         | 0.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                                 | 1         | 0.54%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                         | 1         | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 78        | 50.65%  |
| Realtek Semiconductor    | 43        | 27.92%  |
| Marvell Technology Group | 8         | 5.19%   |
| AMD                      | 7         | 4.55%   |
| Qualcomm Atheros         | 5         | 3.25%   |
| Broadcom                 | 5         | 3.25%   |
| Nvidia                   | 4         | 2.6%    |
| Samsung Electronics      | 1         | 0.65%   |
| Qualcomm                 | 1         | 0.65%   |
| Lenovo                   | 1         | 0.65%   |
| Apple                    | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 31        | 19.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 23        | 14.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11        | 7.05%   |
| AMD XGMAC 10GbE Controller                                             | 7         | 4.49%   |
| Intel I211 Gigabit Network Connection                                  | 6         | 3.85%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 3.85%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 5         | 3.21%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 3.21%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 3.21%   |
| Intel 82577LM Gigabit Network Connection                               | 5         | 3.21%   |
| Nvidia MCP79 Ethernet                                                  | 4         | 2.56%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 2.56%   |
| Intel Ethernet Connection (4) I219-V                                   | 4         | 2.56%   |
| Intel Ethernet Connection I219-V                                       | 3         | 1.92%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.28%   |
| Intel Ethernet Connection (16) I219-V                                  | 2         | 1.28%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 1.28%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.28%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.64%   |
| Qualcomm FP3                                                           | 1         | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.64%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 0.64%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.64%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 0.64%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.64%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.64%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 0.64%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.64%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.64%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.64%   |
| Intel Ethernet Connection (23) I219-V                                  | 1         | 0.64%   |
| Intel Ethernet Connection (18) I219-LM                                 | 1         | 0.64%   |
| Intel Ethernet Connection (14) I219-V                                  | 1         | 0.64%   |
| Intel Ethernet Connection (13) I219-LM                                 | 1         | 0.64%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 0.64%   |
| Intel 82577LC Gigabit Network Connection                               | 1         | 0.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 168       | 52.34%  |
| Ethernet | 143       | 44.55%  |
| Unknown  | 6         | 1.87%   |
| Modem    | 4         | 1.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 118       | 57.84%  |
| Ethernet | 83        | 40.69%  |
| Modem    | 3         | 1.47%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 127       | 71.35%  |
| 1     | 36        | 20.22%  |
| 5     | 7         | 3.93%   |
| 3     | 6         | 3.37%   |
| 6     | 1         | 0.56%   |
| 4     | 1         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 159       | 86.89%  |
| Yes  | 24        | 13.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 62.18%  |
| Broadcom                        | 13        | 10.92%  |
| Realtek Semiconductor           | 10        | 8.4%    |
| Apple                           | 7         | 5.88%   |
| Dell                            | 5         | 4.2%    |
| Qualcomm Atheros Communications | 2         | 1.68%   |
| IMC Networks                    | 2         | 1.68%   |
| Foxconn / Hon Hai               | 2         | 1.68%   |
| Skylight Digital                | 1         | 0.84%   |
| Lite-On Technology              | 1         | 0.84%   |
| ASUSTek Computer                | 1         | 0.84%   |
| Alps Electric                   | 1         | 0.84%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 37        | 31.09%  |
| Intel AX201 Bluetooth                                                               | 14        | 11.76%  |
| Intel AX200 Bluetooth                                                               | 8         | 6.72%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 5.04%   |
| Apple Bluetooth Host Controller                                                     | 6         | 5.04%   |
| Intel AX211 Bluetooth                                                               | 5         | 4.2%    |
| Dell DW375 Bluetooth Module                                                         | 4         | 3.36%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 3.36%   |
| Realtek Bluetooth Adapter                                                           | 3         | 2.52%   |
| Realtek Bluetooth 4.0 Adapter                                                       | 3         | 2.52%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 2.52%   |
| Realtek Bluetooth 4.0 + High Speed Chip                                             | 2         | 1.68%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.68%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.68%   |
| Broadcom Bluetooth                                                                  | 2         | 1.68%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 1.68%   |
| Skylight Digital Realtek Bluetooth Adapter                                          | 1         | 0.84%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.84%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.84%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                                              | 1         | 0.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.84%   |
| Lite-On Bluetooth USB Module                                                        | 1         | 0.84%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                                         | 1         | 0.84%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS                             | 1         | 0.84%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.84%   |
| Foxconn / Hon Hai Bluetooth USB Module                                              | 1         | 0.84%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                                         | 1         | 0.84%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.84%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.84%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.84%   |
| Apple Broadcom Built-in Bluetooth                                                   | 1         | 0.84%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 0.84%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 147       | 73.87%  |
| AMD                 | 30        | 15.08%  |
| Nvidia              | 10        | 5.03%   |
| SteelSeries ApS     | 4         | 2.01%   |
| C-Media Electronics | 3         | 1.51%   |
| Trust               | 1         | 0.5%    |
| Lenovo              | 1         | 0.5%    |
| JMTek               | 1         | 0.5%    |
| GN Netcom           | 1         | 0.5%    |
| Focusrite-Novation  | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 27        | 11.69%  |
| AMD Ryzen HD Audio Controller                                                                     | 19        | 8.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 6.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 6.93%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 4.76%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 4.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 4.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 3.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 3.46%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 8         | 3.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 3.03%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.16%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 2.16%   |
| SteelSeries ApS SteelSeries Siberia 350                                                           | 4         | 1.73%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 1.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.73%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 1.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.3%    |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 3         | 1.3%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.3%    |
| AMD FCH Azalia Controller                                                                         | 3         | 1.3%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.87%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.87%   |
| C-Media Electronics USB Audio Class 1.0 and 2.0 Device                                            | 2         | 0.87%   |
| Trust Trust AYDA                                                                                  | 1         | 0.43%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.43%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.43%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.43%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.43%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.43%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 1         | 0.43%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 1         | 0.43%   |
| JMTek audio controller                                                                            | 1         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 66        | 34.02%  |
| SK hynix            | 39        | 20.1%   |
| Micron Technology   | 24        | 12.37%  |
| Unknown             | 16        | 8.25%   |
| Kingston            | 13        | 6.7%    |
| Crucial             | 12        | 6.19%   |
| Transcend           | 6         | 3.09%   |
| Unknown (ABCD)      | 3         | 1.55%   |
| Elpida              | 3         | 1.55%   |
| Unknown             | 3         | 1.55%   |
| Corsair             | 2         | 1.03%   |
| A-DATA Technology   | 2         | 1.03%   |
| Ramaxel Technology  | 1         | 0.52%   |
| GSkill              | 1         | 0.52%   |
| fef5                | 1         | 0.52%   |
| A Force             | 1         | 0.52%   |
| 48spaces            | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 6         | 2.84%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 2.84%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 5         | 2.37%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 2.37%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 2.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 1.9%    |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 4         | 1.9%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.9%    |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 3         | 1.42%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.42%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.42%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 3         | 1.42%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 3         | 1.42%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.42%   |
| Unknown                                                          | 3         | 1.42%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.95%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.95%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.95%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.95%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 2         | 0.95%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.95%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.95%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.95%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.95%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3200MT/s            | 2         | 0.95%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 2         | 0.95%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.95%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.95%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.95%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.95%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 0.95%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 0.95%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s          | 2         | 0.95%   |
| Elpida RAM 8KTS51264HDZ-1G6E1 4GB Chip DDR3 1600MT/s             | 2         | 0.95%   |
| Crucial RAM CT8G4SFRA32A.C8FT 8GB SODIMM DDR4 3200MT/s           | 2         | 0.95%   |
| Unknown SODIMM 2GB SODIMM DDR2 533MT/s                           | 1         | 0.47%   |
| Unknown SODIMM 2048MB SODIMM DDR2 533MT/s                        | 1         | 0.47%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 69        | 43.13%  |
| DDR4    | 62        | 38.75%  |
| DDR2    | 13        | 8.13%   |
| Unknown | 5         | 3.13%   |
| LPDDR4  | 4         | 2.5%    |
| LPDDR3  | 4         | 2.5%    |
| DDR5    | 2         | 1.25%   |
| DDR     | 1         | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 147       | 92.45%  |
| Row Of Chips | 6         | 3.77%   |
| Chip         | 3         | 1.89%   |
| Unknown      | 2         | 1.26%   |
| DIMM         | 1         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 63        | 35.8%   |
| 4096  | 62        | 35.23%  |
| 2048  | 26        | 14.77%  |
| 16384 | 16        | 9.09%   |
| 32768 | 6         | 3.41%   |
| 1024  | 2         | 1.14%   |
| 512   | 1         | 0.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 47        | 26.86%  |
| 3200  | 30        | 17.14%  |
| 2667  | 20        | 11.43%  |
| 2400  | 17        | 9.71%   |
| 1333  | 13        | 7.43%   |
| 1334  | 9         | 5.14%   |
| 2133  | 8         | 4.57%   |
| 667   | 8         | 4.57%   |
| 1867  | 6         | 3.43%   |
| 1067  | 4         | 2.29%   |
| 800   | 3         | 1.71%   |
| 533   | 3         | 1.71%   |
| 5600  | 2         | 1.14%   |
| 1066  | 2         | 1.14%   |
| 4267  | 1         | 0.57%   |
| 975   | 1         | 0.57%   |
| 333   | 1         | 0.57%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 28        | 22.4%   |
| Bison Electronics                      | 14        | 11.2%   |
| Realtek Semiconductor                  | 11        | 8.8%    |
| IMC Networks                           | 11        | 8.8%    |
| Sunplus Innovation Technology          | 7         | 5.6%    |
| Lite-On Technology                     | 7         | 5.6%    |
| Z-Star Microelectronics                | 5         | 4%      |
| Suyin                                  | 5         | 4%      |
| Quanta                                 | 5         | 4%      |
| Microdia                               | 5         | 4%      |
| Luxvisions Innotech Limited            | 5         | 4%      |
| Syntek                                 | 4         | 3.2%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.2%    |
| Silicon Motion                         | 3         | 2.4%    |
| Lenovo                                 | 3         | 2.4%    |
| Logitech                               | 2         | 1.6%    |
| Apple                                  | 2         | 1.6%    |
| Supreme Electronics                    | 1         | 0.8%    |
| Ricoh                                  | 1         | 0.8%    |
| Creative Technology                    | 1         | 0.8%    |
| Alcor Micro                            | 1         | 0.8%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 7         | 5.51%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 5         | 3.94%   |
| Realtek Integrated_Webcam_HD                                | 4         | 3.15%   |
| IMC Networks Integrated Camera                              | 4         | 3.15%   |
| Sunplus Integrated_Webcam_HD                                | 3         | 2.36%   |
| Luxvisions Innotech Limited Integrated Camera               | 3         | 2.36%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 3         | 2.36%   |
| Chicony Integrated HP HD Webcam                             | 3         | 2.36%   |
| Bison SunplusIT Integrated Camera                           | 3         | 2.36%   |
| Bison Integrated Camera                                     | 3         | 2.36%   |
| Z-Star Webcam                                               | 2         | 1.57%   |
| Z-Star Namuga 1.3M Webcam                                   | 2         | 1.57%   |
| Syntek Integrated Camera                                    | 2         | 1.57%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 1.57%   |
| Silicon Motion 300k Pixel Camera                            | 2         | 1.57%   |
| Realtek USB 2.0 Webcam                                      | 2         | 1.57%   |
| Realtek PC Camera                                           | 2         | 1.57%   |
| Quanta HP Universal Camera                                  | 2         | 1.57%   |
| Microdia USB 2.0 Camera                                     | 2         | 1.57%   |
| Luxvisions Innotech Limited HP HD Camera                    | 2         | 1.57%   |
| Lite-On Integrated Camera                                   | 2         | 1.57%   |
| Lenovo Integrated Webcam                                    | 2         | 1.57%   |
| Bison ThinkPad P50 Integrated Camera                        | 2         | 1.57%   |
| Bison ThinkPad Integrated Camera                            | 2         | 1.57%   |
| Apple FaceTime HD Camera                                    | 2         | 1.57%   |
| Z-Star WebCam SC-03FFL11739P                                | 1         | 0.79%   |
| Syntek USB 2.0 UVC 1.3M WebCam                              | 1         | 0.79%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera               | 1         | 0.79%   |
| Suyin Laptop_Integrated_Webcam_3M                           | 1         | 0.79%   |
| Suyin Acer Crystal Eye webcam                               | 1         | 0.79%   |
| Suyin 1.3M HD Webcam                                        | 1         | 0.79%   |
| Supreme Integrated Camera                                   | 1         | 0.79%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 0.79%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                       | 1         | 0.79%   |
| Sunplus Integrated_Webcam_FHD                               | 1         | 0.79%   |
| Sunplus HP HD Camera                                        | 1         | 0.79%   |
| Silicon Motion WebCam SC-13HDL11939N                        | 1         | 0.79%   |
| Ricoh Laptop_Integrated_Webcam_3M                           | 1         | 0.79%   |
| Realtek USB2.0 HD UVC WebCam                                | 1         | 0.79%   |
| Realtek USB Camera                                          | 1         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 13        | 30.23%  |
| Validity Sensors           | 10        | 23.26%  |
| Upek                       | 6         | 13.95%  |
| Shenzhen Goodix Technology | 5         | 11.63%  |
| Elan Microelectronics      | 4         | 9.3%    |
| Broadcom                   | 2         | 4.65%   |
| AuthenTec                  | 2         | 4.65%   |
| STMicroelectronics         | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 6         | 13.95%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 5         | 11.63%  |
| Shenzhen Goodix Fingerprint Reader                                           | 5         | 11.63%  |
| Elan Fingerprint Sensor                                                      | 4         | 9.3%    |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 6.98%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 3         | 6.98%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 2         | 4.65%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 2         | 4.65%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 4.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 2.33%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 2.33%   |
| Validity Sensors VFS491                                                      | 1         | 2.33%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 2.33%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 2.33%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 1         | 2.33%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 2.33%   |
| Synaptics UWP WBDI                                                           | 1         | 2.33%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 2.33%   |
| AuthenTec AES2810                                                            | 1         | 2.33%   |
| AuthenTec AES1660                                                            | 1         | 2.33%   |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 59        | 31.05%  |
| 1     | 58        | 30.53%  |
| 3     | 28        | 14.74%  |
| 0     | 26        | 13.68%  |
| 4     | 12        | 6.32%   |
| 5     | 7         | 3.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 130       | 43.62%  |
| Bluetooth                | 54        | 18.12%  |
| Fingerprint reader       | 38        | 12.75%  |
| Net/wireless             | 26        | 8.72%   |
| Card reader              | 20        | 6.71%   |
| Firewire controller      | 18        | 6.04%   |
| Graphics card            | 5         | 1.68%   |
| Storage                  | 4         | 1.34%   |
| Network                  | 2         | 0.67%   |
| Sound                    | 1         | 0.34%   |

