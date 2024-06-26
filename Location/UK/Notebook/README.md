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

Total: 276

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [89a61aca01](https://bsd-hardware.info/?probe=89a61aca01) | May 04, 2024 |
| HP            | ZBook 17 G2                 | [8558fc6b60](https://bsd-hardware.info/?probe=8558fc6b60) | May 04, 2024 |
| DFI           | Unknown                     | [1348838d15](https://bsd-hardware.info/?probe=1348838d15) | Apr 28, 2024 |
| Deciso        | NetBoard-A10                | [c2e1f3af3b](https://bsd-hardware.info/?probe=c2e1f3af3b) | Apr 18, 2024 |
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
| Deciso        | NetBoard-A10                | [2ea96f8806](https://bsd-hardware.info/?probe=2ea96f8806) | Nov 21, 2023 |
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
| Deciso        | NetBoard-A10                | [1cca4a556d](https://bsd-hardware.info/?probe=1cca4a556d) | Mar 07, 2023 |
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
| Deciso        | NetBoard-A10                | [9b95ddf7b9](https://bsd-hardware.info/?probe=9b95ddf7b9) | Oct 01, 2022 |
| Deciso        | NetBoard-A10                | [5cec3595a3](https://bsd-hardware.info/?probe=5cec3595a3) | Sep 21, 2022 |
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


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.8.1    | 10        | 5.99%   |
| helloSystem 0.7.0    | 10        | 5.99%   |
| FreeBSD 14.0-CURRENT | 8         | 4.79%   |
| FreeBSD 13.0         | 8         | 4.79%   |
| FreeBSD 13.1         | 6         | 3.59%   |
| NomadBSD 20221130    | 5         | 2.99%   |
| OpenBSD 7.2          | 4         | 2.4%    |
| helloSystem 0.5.0    | 4         | 2.4%    |
| helloSystem 0.4.0    | 4         | 2.4%    |
| GhostBSD 20.04.02    | 4         | 2.4%    |
| FreeBSD 13.2         | 4         | 2.4%    |
| FreeBSD 12.2         | 4         | 2.4%    |
| OpenBSD 7.1          | 3         | 1.8%    |
| OpenBSD 6.8          | 3         | 1.8%    |
| NomadBSD 1.4-RC1     | 3         | 1.8%    |
| NomadBSD 1.3.2       | 3         | 1.8%    |
| helloSystem 0.6.0    | 3         | 1.8%    |
| FreeBSD 14.0-p4      | 3         | 1.8%    |
| OPNsense 24.1.1      | 2         | 1.2%    |
| OPNsense 23.7.6      | 2         | 1.2%    |
| OPNsense 22.4.3      | 2         | 1.2%    |
| helloSystem 0.8.2    | 2         | 1.2%    |
| helloSystem 0.8.0    | 2         | 1.2%    |
| GhostBSD 23.02.02    | 2         | 1.2%    |
| FreeBSD 15.0-CURRENT | 2         | 1.2%    |
| FreeBSD 14.0-p1      | 2         | 1.2%    |
| FreeBSD 14.0         | 2         | 1.2%    |
| FreeBSD 13.2-p2      | 2         | 1.2%    |
| FreeBSD 13.0-p5      | 2         | 1.2%    |
| FreeBSD 13.0-CURRENT | 2         | 1.2%    |
| FreeBSD 12.2-p6      | 2         | 1.2%    |
| FreeBSD 12.2-p4      | 2         | 1.2%    |
| FreeBSD 12.2-p3      | 2         | 1.2%    |
| FreeBSD 12.2-p2      | 2         | 1.2%    |
| FreeBSD 12.1-p9      | 2         | 1.2%    |
| OPNsense 24.1.6      | 1         | 0.6%    |
| OPNsense 24.1.5      | 1         | 0.6%    |
| OPNsense 23.7.8      | 1         | 0.6%    |
| OPNsense 23.7.10     | 1         | 0.6%    |
| OPNsense 23.1.1      | 1         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 50        | 38.17%  |
| helloSystem | 32        | 24.43%  |
| OpenBSD     | 14        | 10.69%  |
| NomadBSD    | 12        | 9.16%   |
| OPNsense    | 11        | 8.4%    |
| GhostBSD    | 10        | 7.63%   |
| FuryBSD     | 1         | 0.76%   |
| DragonFly   | 1         | 0.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 123       | 98.4%   |
| i386  | 2         | 1.6%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 36        | 26.87%  |
| Console       | 20        | 14.93%  |
| KDE5          | 19        | 14.18%  |
| XFCE          | 17        | 12.69%  |
| MATE          | 13        | 9.7%    |
| Openbox       | 9         | 6.72%   |
| fvwm          | 5         | 3.73%   |
| GNOME         | 4         | 2.99%   |
| i3            | 3         | 2.24%   |
| xinitrc       | 2         | 1.49%   |
| Cinnamon      | 2         | 1.49%   |
| Budgie        | 2         | 1.49%   |
| Potato        | 1         | 0.75%   |
| Enlightenment | 1         | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 103       | 80.47%  |
| Console | 20        | 15.63%  |
| Wayland | 5         | 3.91%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 47        | 35.88%  |
| Console | 39        | 29.77%  |
| SDDM    | 26        | 19.85%  |
| LightDM | 15        | 11.45%  |
| XDM     | 3         | 2.29%   |
| GDM     | 1         | 0.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| C               | 41        | 30.15%  |
| en_US           | 37        | 27.21%  |
| Unknown         | 35        | 25.74%  |
| en_GB           | 17        | 12.5%   |
| ru_RU           | 1         | 0.74%   |
| it_CH           | 1         | 0.74%   |
| fr_FR           | 1         | 0.74%   |
| en_UK           | 1         | 0.74%   |
| en_GB.US-ASCII  | 1         | 0.74%   |
| en_GB.ISO8859-1 | 1         | 0.74%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 104       | 82.54%  |
| BIOS | 22        | 17.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 70        | 53.85%  |
| Ufs     | 33        | 25.38%  |
| Ffs     | 14        | 10.77%  |
| Cd9660  | 12        | 9.23%   |
| Hammer2 | 1         | 0.77%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 115       | 90.55%  |
| MBR     | 10        | 7.87%   |
| BSD     | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 38        | 30.4%   |
| Dell                | 17        | 13.6%   |
| Hewlett-Packard     | 16        | 12.8%   |
| Samsung Electronics | 6         | 4.8%    |
| Apple               | 6         | 4.8%    |
| Toshiba             | 5         | 4%      |
| ASUSTek Computer    | 5         | 4%      |
| Deciso              | 4         | 3.2%    |
| Star Labs           | 3         | 2.4%    |
| HUAWEI              | 3         | 2.4%    |
| OEGStone            | 2         | 1.6%    |
| Unknown             | 2         | 1.6%    |
| TUXEDO              | 1         | 0.8%    |
| System76            | 1         | 0.8%    |
| Sony                | 1         | 0.8%    |
| Shuttle             | 1         | 0.8%    |
| Pegatron            | 1         | 0.8%    |
| Panasonic           | 1         | 0.8%    |
| Packard Bell        | 1         | 0.8%    |
| Notebook            | 1         | 0.8%    |
| MSI                 | 1         | 0.8%    |
| Jumper              | 1         | 0.8%    |
| Google              | 1         | 0.8%    |
| GEO                 | 1         | 0.8%    |
| Fujitsu Siemens     | 1         | 0.8%    |
| Fujitsu             | 1         | 0.8%    |
| Dynabook Europe     | 1         | 0.8%    |
| DFI                 | 1         | 0.8%    |
| Alienware           | 1         | 0.8%    |
| Acer                | 1         | 0.8%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP EliteBook 8570p                    | 3         | 2.4%    |
| Deciso NetBoard-A10                   | 3         | 2.4%    |
| Unknown                               | 3         | 2.4%    |
| Dell XPS 13 9343                      | 2         | 1.6%    |
| Dell Latitude E6420                   | 2         | 1.6%    |
| Dell Inspiron 3793                    | 2         | 1.6%    |
| ASUS ZenBook S UX391UA                | 2         | 1.6%    |
| TUXEDO Aura 15 Gen1                   | 1         | 0.8%    |
| Toshiba TECRA M11                     | 1         | 0.8%    |
| Toshiba Satellite Pro U400            | 1         | 0.8%    |
| Toshiba Satellite L50-C               | 1         | 0.8%    |
| Toshiba Satellite C660                | 1         | 0.8%    |
| Toshiba Satellite C50-B               | 1         | 0.8%    |
| System76 Gazelle                      | 1         | 0.8%    |
| Star Labs StarBook                    | 1         | 0.8%    |
| Star Labs Lite                        | 1         | 0.8%    |
| Star Labs LabTop                      | 1         | 0.8%    |
| Sony VPCF12C5E                        | 1         | 0.8%    |
| Shuttle NC02U                         | 1         | 0.8%    |
| Samsung Q210                          | 1         | 0.8%    |
| Samsung NC10                          | 1         | 0.8%    |
| Samsung N150/N210/N220                | 1         | 0.8%    |
| Samsung N140                          | 1         | 0.8%    |
| Samsung 550P5C/550P7C                 | 1         | 0.8%    |
| Samsung 305E4A/305E5A/305E7A          | 1         | 0.8%    |
| Pegatron T12Ah                        | 1         | 0.8%    |
| Panasonic CF-C1BT02EGE                | 1         | 0.8%    |
| Packard Bell EasyNote_MX52-B-071      | 1         | 0.8%    |
| OEGStone W54_55SU1,SUW                | 1         | 0.8%    |
| OEGStone doceo 510                    | 1         | 0.8%    |
| Notebook NL5xRU                       | 1         | 0.8%    |
| MSI Modern 14 B11MOL                  | 1         | 0.8%    |
| Lenovo Z50-70 20354                   | 1         | 0.8%    |
| Lenovo ThinkPad Yoga 11e 20D9000QUK   | 1         | 0.8%    |
| Lenovo ThinkPad X280 20KESB4T00       | 1         | 0.8%    |
| Lenovo ThinkPad X270 W10DG 20K5S0DS00 | 1         | 0.8%    |
| Lenovo ThinkPad X270 W10DG 20K5S0DB05 | 1         | 0.8%    |
| Lenovo ThinkPad X240 20AMS1YG01       | 1         | 0.8%    |
| Lenovo ThinkPad X230 2325J67          | 1         | 0.8%    |
| Lenovo ThinkPad X230 2325IB1          | 1         | 0.8%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 33        | 26.4%   |
| Dell Latitude          | 9         | 7.2%    |
| Toshiba Satellite      | 4         | 3.2%    |
| HP EliteBook           | 4         | 3.2%    |
| Lenovo IdeaPad         | 3         | 2.4%    |
| Dell Inspiron          | 3         | 2.4%    |
| Deciso NetBoard-A10    | 3         | 2.4%    |
| Apple MacBookPro5      | 3         | 2.4%    |
| Unknown                | 3         | 2.4%    |
| HP ProBook             | 2         | 1.6%    |
| HP Pavilion            | 2         | 1.6%    |
| Dell XPS               | 2         | 1.6%    |
| Dell Precision         | 2         | 1.6%    |
| ASUS ZenBook           | 2         | 1.6%    |
| Apple MacBookPro8      | 2         | 1.6%    |
| TUXEDO Aura            | 1         | 0.8%    |
| Toshiba TECRA          | 1         | 0.8%    |
| System76 Gazelle       | 1         | 0.8%    |
| Star Labs StarBook     | 1         | 0.8%    |
| Star Labs Lite         | 1         | 0.8%    |
| Star Labs LabTop       | 1         | 0.8%    |
| Sony VPCF12C5E         | 1         | 0.8%    |
| Shuttle NC02U          | 1         | 0.8%    |
| Samsung Q210           | 1         | 0.8%    |
| Samsung NC10           | 1         | 0.8%    |
| Samsung N150           | 1         | 0.8%    |
| Samsung N140           | 1         | 0.8%    |
| Samsung 550P5C         | 1         | 0.8%    |
| Samsung 305E4A         | 1         | 0.8%    |
| Pegatron T12Ah         | 1         | 0.8%    |
| Panasonic CF-C1BT02EGE | 1         | 0.8%    |
| Packard Bell EasyNote  | 1         | 0.8%    |
| OEGStone W54           | 1         | 0.8%    |
| OEGStone doceo         | 1         | 0.8%    |
| Notebook NL5xRU        | 1         | 0.8%    |
| MSI Modern             | 1         | 0.8%    |
| Lenovo Z50-70          | 1         | 0.8%    |
| Lenovo Legion          | 1         | 0.8%    |
| Jumper EZbook          | 1         | 0.8%    |
| HUAWEI MACHD-WXX9      | 1         | 0.8%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 14        | 11.2%   |
| 2012 | 11        | 8.8%    |
| 2019 | 10        | 8%      |
| 2016 | 10        | 8%      |
| 2011 | 10        | 8%      |
| 2010 | 10        | 8%      |
| 2022 | 8         | 6.4%    |
| 2021 | 8         | 6.4%    |
| 2018 | 8         | 6.4%    |
| 2009 | 8         | 6.4%    |
| 2013 | 6         | 4.8%    |
| 2015 | 5         | 4%      |
| 2017 | 4         | 3.2%    |
| 2014 | 4         | 3.2%    |
| 2008 | 4         | 3.2%    |
| 2023 | 3         | 2.4%    |
| 2007 | 2         | 1.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 125       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 121       | 96.8%   |
| Yes  | 4         | 3.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 60        | 46.88%  |
| 4.01-8.0    | 28        | 21.88%  |
| 16.01-24.0  | 26        | 20.31%  |
| 32.01-64.0  | 6         | 4.69%   |
| 2.01-3.0    | 5         | 3.91%   |
| 64.01-256.0 | 2         | 1.56%   |
| 3.01-4.0    | 1         | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 77        | 58.33%  |
| 0.51-1.0  | 39        | 29.55%  |
| 1.01-2.0  | 9         | 6.82%   |
| 2.01-3.0  | 4         | 3.03%   |
| 4.01-8.0  | 1         | 0.76%   |
| 3.01-4.0  | 1         | 0.76%   |
| 8.01-16.0 | 1         | 0.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 101       | 74.81%  |
| 2      | 23        | 17.04%  |
| 0      | 7         | 5.19%   |
| 3      | 4         | 2.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 91        | 70.54%  |
| Yes       | 38        | 29.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 82.4%   |
| No        | 22        | 17.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 95.2%   |
| No        | 6         | 4.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 62.5%   |
| No        | 48        | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| UK      | 125       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| London          | 12        | 7.95%   |
| Brighton        | 7         | 4.64%   |
| Glasgow         | 6         | 3.97%   |
| Manchester      | 5         | 3.31%   |
| Swindon         | 3         | 1.99%   |
| Shoreham-by-Sea | 3         | 1.99%   |
| Oxford          | 3         | 1.99%   |
| Leatherhead     | 3         | 1.99%   |
| Haywards Heath  | 3         | 1.99%   |
| City of London  | 3         | 1.99%   |
| Worthing        | 2         | 1.32%   |
| Southampton     | 2         | 1.32%   |
| Reading         | 2         | 1.32%   |
| Plymouth        | 2         | 1.32%   |
| Peterborough    | 2         | 1.32%   |
| Ipswich         | 2         | 1.32%   |
| Hove            | 2         | 1.32%   |
| Greenwich       | 2         | 1.32%   |
| Gloucester      | 2         | 1.32%   |
| East Grinstead  | 2         | 1.32%   |
| Coventry        | 2         | 1.32%   |
| Addlestone      | 2         | 1.32%   |
| Wraysbury       | 1         | 0.66%   |
| Woking          | 1         | 0.66%   |
| West Bromwich   | 1         | 0.66%   |
| Watford         | 1         | 0.66%   |
| Walsall         | 1         | 0.66%   |
| Wakefield       | 1         | 0.66%   |
| Tottenham       | 1         | 0.66%   |
| Tatsfield       | 1         | 0.66%   |
| Sutton          | 1         | 0.66%   |
| Stretford       | 1         | 0.66%   |
| St Austell      | 1         | 0.66%   |
| St Albans       | 1         | 0.66%   |
| Southwark       | 1         | 0.66%   |
| Southall        | 1         | 0.66%   |
| South Croydon   | 1         | 0.66%   |
| Sheffield       | 1         | 0.66%   |
| Ruislip         | 1         | 0.66%   |
| Rugby           | 1         | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 58     | 23.18%  |
| WDC                 | 17        | 24     | 11.26%  |
| Toshiba             | 12        | 26     | 7.95%   |
| Seagate             | 11        | 15     | 7.28%   |
| Crucial             | 7         | 7      | 4.64%   |
| Kingston            | 6         | 6      | 3.97%   |
| Hitachi             | 6         | 6      | 3.97%   |
| HGST                | 6         | 42     | 3.97%   |
| SanDisk             | 5         | 5      | 3.31%   |
| NVMe                | 5         | 5      | 3.31%   |
| Intel               | 5         | 5      | 3.31%   |
| Transcend           | 4         | 9      | 2.65%   |
| SK hynix            | 3         | 3      | 1.99%   |
| XUM                 | 2         | 2      | 1.32%   |
| Star Drive          | 2         | 2      | 1.32%   |
| Phison              | 2         | 2      | 1.32%   |
| LITEON              | 2         | 2      | 1.32%   |
| Corsair             | 2         | 3      | 1.32%   |
| Apple               | 2         | 3      | 1.32%   |
| UMIS                | 1         | 1      | 0.66%   |
| SPCC                | 1         | 1      | 0.66%   |
| Solid State Storage | 1         | 1      | 0.66%   |
| SATA3 60            | 1         | 1      | 0.66%   |
| PNY                 | 1         | 1      | 0.66%   |
| OWC                 | 1         | 1      | 0.66%   |
| Micron Technology   | 1         | 1      | 0.66%   |
| MicroDream          | 1         | 1      | 0.66%   |
| Lexar               | 1         | 1      | 0.66%   |
| Intenso             | 1         | 1      | 0.66%   |
| Integral            | 1         | 1      | 0.66%   |
| Innodisk            | 1         | 1      | 0.66%   |
| Fujitsu             | 1         | 6      | 0.66%   |
| FORESEE             | 1         | 1      | 0.66%   |
| China               | 1         | 1      | 0.66%   |
| Apacer              | 1         | 1      | 0.66%   |
| A-DATA Technology   | 1         | 1      | 0.66%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                           | 6         | 3.85%   |
| HGST HTS725050A7E630 500GB                         | 4         | 2.56%   |
| Transcend TS256GMTE652T2 256GB                     | 3         | 1.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 3         | 1.92%   |
| Samsung HM251JX 250GB                              | 3         | 1.92%   |
| XUM HX256GSSDSATA3 256GB                           | 2         | 1.28%   |
| WDC WDS250G2B0B-00YS70 250GB                       | 2         | 1.28%   |
| WDC WDS240G2G0A-00JH30 240GB                       | 2         | 1.28%   |
| WDC WD3200BPVT-80JJ5T0 320GB                       | 2         | 1.28%   |
| WDC WD1600BEVT-80A23T0 160GB                       | 2         | 1.28%   |
| WDC WD1600BEVT-22ZCT0 160GB                        | 2         | 1.28%   |
| Seagate ST9320423AS 320GB                          | 2         | 1.28%   |
| Seagate ST1000LM035-1RK172 1TB                     | 2         | 1.28%   |
| Samsung SSD PM851 M.2 2280 256GB                   | 2         | 1.28%   |
| Samsung SSD 870 EVO 500GB                          | 2         | 1.28%   |
| Samsung SSD 860 EVO 500GB                          | 2         | 1.28%   |
| Samsung MZVLW512HMJP-00000 512GB                   | 2         | 1.28%   |
| HGST HTS721010A9E630 1TB                           | 2         | 1.28%   |
| Crucial CT500P2SSD8 500GB                          | 2         | 1.28%   |
| WDC WDS250G2B0A 250GB                              | 1         | 0.64%   |
| WDC WDS120G2G0A-00JH30 120GB                       | 1         | 0.64%   |
| WDC WD7500BPKX-00HPJT0 752GB                       | 1         | 0.64%   |
| WDC WD2500BEVT-80A23T0 250GB                       | 1         | 0.64%   |
| WDC WD2500BEVT-22ZCT0 250GB                        | 1         | 0.64%   |
| WDC WD1600BEVS-08VAT2 160GB                        | 1         | 0.64%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB               | 1         | 0.64%   |
| UMIS RPJTJ512MEE1OWX 512GB                         | 1         | 0.64%   |
| Transcend TS128GMTE110S 128GB                      | 1         | 0.64%   |
| Toshiba THNSNJ128GMCU 128GB                        | 1         | 0.64%   |
| Toshiba THNSF5256GPUK 256GB                        | 1         | 0.64%   |
| Toshiba MK8034GSX 80GB                             | 1         | 0.64%   |
| Toshiba MK5061GSY 500GB                            | 1         | 0.64%   |
| Toshiba KXG5AZNV256G 256GB                         | 1         | 0.64%   |
| Toshiba KBG30ZMV256G 256GB                         | 1         | 0.64%   |
| Star Drive SATA SSD 960GB                          | 1         | 0.64%   |
| Star Drive PCIe SSD 960GB                          | 1         | 0.64%   |
| SPCC Solid State Disk 128GB                        | 1         | 0.64%   |
| Solid State Storage CL1-3D128-Q11 NVMe SSSTC 128GB | 1         | 0.64%   |
| SK hynix SKHynix_HFS001TDE9X081N 1TB               | 1         | 0.64%   |
| SK hynix PC711 NVMe 512GB                          | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 15     | 21.57%  |
| WDC                 | 10        | 13     | 19.61%  |
| Toshiba             | 8         | 20     | 15.69%  |
| Hitachi             | 6         | 6      | 11.76%  |
| HGST                | 6         | 42     | 11.76%  |
| Samsung Electronics | 5         | 5      | 9.8%    |
| NVMe                | 4         | 4      | 7.84%   |
| Fujitsu             | 1         | 6      | 1.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 38     | 28.57%  |
| WDC                 | 6         | 10     | 8.57%   |
| Kingston            | 6         | 6      | 8.57%   |
| SanDisk             | 5         | 5      | 7.14%   |
| Crucial             | 4         | 4      | 5.71%   |
| Intel               | 3         | 3      | 4.29%   |
| XUM                 | 2         | 2      | 2.86%   |
| LITEON              | 2         | 2      | 2.86%   |
| Corsair             | 2         | 3      | 2.86%   |
| Apple               | 2         | 3      | 2.86%   |
| Toshiba             | 1         | 1      | 1.43%   |
| Star Drive          | 1         | 1      | 1.43%   |
| SPCC                | 1         | 1      | 1.43%   |
| SATA3 60            | 1         | 1      | 1.43%   |
| PNY                 | 1         | 1      | 1.43%   |
| Phison              | 1         | 1      | 1.43%   |
| OWC                 | 1         | 1      | 1.43%   |
| NVMe                | 1         | 1      | 1.43%   |
| Micron Technology   | 1         | 1      | 1.43%   |
| MicroDream          | 1         | 1      | 1.43%   |
| Lexar               | 1         | 1      | 1.43%   |
| Intenso             | 1         | 1      | 1.43%   |
| Integral            | 1         | 1      | 1.43%   |
| Innodisk            | 1         | 1      | 1.43%   |
| FORESEE             | 1         | 1      | 1.43%   |
| China               | 1         | 1      | 1.43%   |
| Apacer              | 1         | 1      | 1.43%   |
| A-DATA Technology   | 1         | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 65        | 94     | 47.1%   |
| HDD  | 43        | 111    | 31.16%  |
| NVMe | 30        | 42     | 21.74%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 96        | 205    | 76.19%  |
| NVMe | 30        | 42     | 23.81%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 85        | 151    | 81.73%  |
| 0.51-1.0   | 14        | 48     | 13.46%  |
| 1.01-2.0   | 4         | 5      | 3.85%   |
| 3.01-4.0   | 1         | 1      | 0.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 49        | 34.75%  |
| 251-500    | 30        | 21.28%  |
| 1-20       | 30        | 21.28%  |
| 501-1000   | 11        | 7.8%    |
| 51-100     | 9         | 6.38%   |
| 21-50      | 8         | 5.67%   |
| Unknown    | 3         | 2.13%   |
| 1001-2000  | 1         | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 108       | 78.26%  |
| 21-50   | 17        | 12.32%  |
| 51-100  | 6         | 4.35%   |
| 101-250 | 4         | 2.9%    |
| Unknown | 3         | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                       | 4         | 10     | 18.18%  |
| HGST HTS721010A9E630 1TB                         | 2         | 22     | 9.09%   |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 4.55%   |
| WDC WD1600BEVT-80A23T0 160GB                     | 1         | 1      | 4.55%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 4.55%   |
| Seagate ST9160821AS 160GB                        | 1         | 1      | 4.55%   |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 1         | 1      | 4.55%   |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 4.55%   |
| Samsung Electronics HM251JX 250GB                | 1         | 1      | 4.55%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 4.55%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 4.55%   |
| Kingston SV300S37A120G 120GB                     | 1         | 1      | 4.55%   |
| Hitachi HTS727575A9E362 752GB                    | 1         | 1      | 4.55%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 4.55%   |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 4.55%   |
| Hitachi HTS543232A7A384 320GB                    | 1         | 1      | 4.55%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 4.55%   |
| A-DATA Technology SP550 240GB                    | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 5         | 33     | 25%     |
| Samsung Electronics | 4         | 4      | 20%     |
| Hitachi             | 4         | 4      | 20%     |
| WDC                 | 2         | 2      | 10%     |
| Seagate             | 2         | 2      | 10%     |
| Micron Technology   | 1         | 1      | 5%      |
| Kingston            | 1         | 1      | 5%      |
| A-DATA Technology   | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 5         | 33     | 31.25%  |
| Hitachi             | 4         | 4      | 25%     |
| Samsung Electronics | 3         | 3      | 18.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| Seagate             | 2         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 44     | 78.95%  |
| SSD  | 4         | 4      | 21.05%  |

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
| Works    | 104       | 188    | 80%     |
| Malfunc  | 18        | 48     | 13.85%  |
| Detected | 7         | 10     | 5.38%   |
| Failed   | 1         | 1      | 0.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 91        | 64.54%  |
| Samsung Electronics                     | 15        | 10.64%  |
| AMD                                     | 7         | 4.96%   |
| Transcend                               | 4         | 2.84%   |
| Toshiba                                 | 4         | 2.84%   |
| Phison Electronics                      | 4         | 2.84%   |
| Nvidia                                  | 4         | 2.84%   |
| Micron/Crucial Technology               | 4         | 2.84%   |
| SK hynix                                | 3         | 2.13%   |
| Solid State Storage Technology          | 1         | 0.71%   |
| Shenzhen Unionmemory Information System | 1         | 0.71%   |
| SanDisk                                 | 1         | 0.71%   |
| Kingston Technology Company             | 1         | 0.71%   |
| ASMedia Technology                      | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 7.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 7.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 5.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 5.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 4.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 3.92%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 3.92%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5         | 3.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 3.27%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)    | 4         | 2.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 2.61%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 2.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 2.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 1.96%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 1.96%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.96%   |
| Toshiba XG5 NVMe SSD Controller                                                | 2         | 1.31%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 1.31%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 1.31%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.31%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.31%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.31%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 1.31%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 2         | 1.31%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 1.31%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.31%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 2         | 1.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.31%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 1.31%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 1.31%   |
| Toshiba XG4 NVMe SSD Controller                                                | 1         | 0.65%   |
| Toshiba BG3 x2 NVMe SSD Controller (DRAM-less)                                 | 1         | 0.65%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 1         | 0.65%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 0.65%   |
| Shenzhen Unionmemory Information System AM620 PCIe 3.0 NVMe SSD 512GB          | 1         | 0.65%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 0.65%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.65%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 1         | 0.65%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 87        | 59.59%  |
| NVMe | 37        | 25.34%  |
| RAID | 11        | 7.53%   |
| IDE  | 11        | 7.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 110       | 88%     |
| AMD    | 14        | 11.2%   |
| 11th   | 1         | 0.8%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel CPU Version                        | 4         | 3.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz        | 4         | 3.2%    |
| Intel Core i7-3520M CPU @ 2.90GHz        | 4         | 3.2%    |
| Intel Core i5-6300U CPU @ 2.40GHz        | 4         | 3.2%    |
| AMD Ryzen Embedded V1500B                | 4         | 3.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz        | 3         | 2.4%    |
| Intel Core i5-7300U CPU @ 2.60GHz        | 3         | 2.4%    |
| Intel Core i5-4300U CPU @ 1.90GHz        | 3         | 2.4%    |
| Intel Core i5-2520M CPU @ 2.50GHz        | 3         | 2.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz        | 2         | 1.6%    |
| Intel Core i7-5600U CPU @ 2.60GHz        | 2         | 1.6%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz       | 2         | 1.6%    |
| Intel Core i5-4210U CPU @ 1.70GHz        | 2         | 1.6%    |
| Intel Core i5-3320M CPU @ 2.60GHz        | 2         | 1.6%    |
| Intel Core i5-2540M CPU @ 2.60GHz        | 2         | 1.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz       | 2         | 1.6%    |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 2         | 1.6%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 2         | 1.6%    |
| Intel Celeron N4000 CPU @ 1.10GHz        | 2         | 1.6%    |
| Intel Atom CPU N450 @ 1.66GHz            | 2         | 1.6%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 2         | 1.6%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 2         | 1.6%    |
| AMD Ryzen 7 4700U with Radeon Graphics   | 2         | 1.6%    |
| Intel Xeon CPU E3-1535M v5 @ 2.90GHz     | 1         | 0.8%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 1         | 0.8%    |
| Intel Pentium Gold 7505 @ 2.00GHz        | 1         | 0.8%    |
| Intel Pentium Dual CPU T3200 @ 2.00GHz   | 1         | 0.8%    |
| Intel Pentium CPU N3700 @ 1.60GHz        | 1         | 0.8%    |
| Intel Pentium CPU 967 @ 1.30GHz          | 1         | 0.8%    |
| Intel Pentium CPU 3825U @ 1.90GHz        | 1         | 0.8%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz       | 1         | 0.8%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 1         | 0.8%    |
| Intel Core i7-6600U CPU @ 2.60GHz        | 1         | 0.8%    |
| Intel Core i7-4770HQ CPU @ 2.20GHz       | 1         | 0.8%    |
| Intel Core i7-4710MQ CPU @ 2.50GHz       | 1         | 0.8%    |
| Intel Core i7-4600U CPU @ 2.10GHz        | 1         | 0.8%    |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 1         | 0.8%    |
| Intel Core i7-3612QM CPU @ 2.10GHz       | 1         | 0.8%    |
| Intel Core i7-3540M CPU @ 3.00GHz        | 1         | 0.8%    |
| Intel Core i7-2820QM CPU @ 2.30GHz       | 1         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 37        | 29.6%   |
| Intel Core i7        | 31        | 24.8%   |
| Other                | 10        | 8%      |
| Intel Core 2 Duo     | 9         | 7.2%    |
| Intel Celeron        | 9         | 7.2%    |
| Intel Atom           | 4         | 3.2%    |
| AMD Ryzen Embedded   | 4         | 3.2%    |
| Intel Pentium        | 3         | 2.4%    |
| Intel Core i3        | 3         | 2.4%    |
| AMD Ryzen 7          | 3         | 2.4%    |
| AMD Ryzen 5          | 2         | 1.6%    |
| AMD A6               | 2         | 1.6%    |
| Intel Xeon           | 1         | 0.8%    |
| Intel Pentium Silver | 1         | 0.8%    |
| Intel Pentium Gold   | 1         | 0.8%    |
| Intel Pentium Dual   | 1         | 0.8%    |
| Intel Core 2         | 1         | 0.8%    |
| AMD Ryzen 3 PRO      | 1         | 0.8%    |
| AMD Ryzen 3          | 1         | 0.8%    |
| AMD Athlon 64 X2     | 1         | 0.8%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 63        | 50.4%   |
| 4       | 37        | 29.6%   |
| Unknown | 10        | 8%      |
| 8       | 8         | 6.4%    |
| 1       | 3         | 2.4%    |
| 16      | 2         | 1.6%    |
| 12      | 2         | 1.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 120       | 96%     |
| Unknown | 3         | 2.4%    |
| 2       | 2         | 1.6%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 82        | 65.6%   |
| 1       | 33        | 26.4%   |
| Unknown | 10        | 8%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 12.8%   |
| SandyBridge   | 13        | 10.4%   |
| IvyBridge     | 12        | 9.6%    |
| Haswell       | 12        | 9.6%    |
| Skylake       | 10        | 8%      |
| Penryn        | 9         | 7.2%    |
| Westmere      | 6         | 4.8%    |
| Zen           | 5         | 4%      |
| TigerLake     | 5         | 4%      |
| Bonnell       | 5         | 4%      |
| Goldmont plus | 4         | 3.2%    |
| Core          | 4         | 3.2%    |
| Broadwell     | 4         | 3.2%    |
| Unknown       | 4         | 3.2%    |
| Zen 2         | 3         | 2.4%    |
| Silvermont    | 3         | 2.4%    |
| IceLake       | 2         | 1.6%    |
| Goldmont      | 2         | 1.6%    |
| Zen 3         | 1         | 0.8%    |
| Nehalem       | 1         | 0.8%    |
| K8 Hammer     | 1         | 0.8%    |
| K10 Llano     | 1         | 0.8%    |
| Excavator     | 1         | 0.8%    |
| CometLake     | 1         | 0.8%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 100       | 74.07%  |
| Nvidia | 21        | 15.56%  |
| AMD    | 14        | 10.37%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 13        | 9.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 9         | 6.34%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 9         | 6.34%   |
| Intel UHD Graphics 620                                                        | 8         | 5.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 6         | 4.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 6         | 4.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 5         | 3.52%   |
| Intel Core Processor Integrated Graphics Controller                           | 5         | 3.52%   |
| Nvidia C79 [GeForce 9400M]                                                    | 3         | 2.11%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 2.11%   |
| Intel HD Graphics 620                                                         | 3         | 2.11%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 2.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 2.11%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 3         | 2.11%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                      | 3         | 2.11%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 3         | 2.11%   |
| Nvidia GP108M [GeForce MX230]                                                 | 2         | 1.41%   |
| Nvidia G96CM [GeForce 9600M GT]                                               | 2         | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 1.41%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 2         | 1.41%   |
| Intel Iris Plus Graphics G7                                                   | 2         | 1.41%   |
| Intel HD Graphics 5500                                                        | 2         | 1.41%   |
| Intel HD Graphics 530                                                         | 2         | 1.41%   |
| Intel HD Graphics                                                             | 2         | 1.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 1.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 2         | 1.41%   |
| AMD Lucienne                                                                  | 2         | 1.41%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                             | 1         | 0.7%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 0.7%    |
| Nvidia MCP79 [GeForce 8200M G]                                                | 1         | 0.7%    |
| Nvidia GT218M [NVS 3100M]                                                     | 1         | 0.7%    |
| Nvidia GT216M [GeForce GT 330M]                                               | 1         | 0.7%    |
| Nvidia GP108M [GeForce MX250]                                                 | 1         | 0.7%    |
| Nvidia GP108BM [GeForce MX250]                                                | 1         | 0.7%    |
| Nvidia GP107M [GeForce MX350]                                                 | 1         | 0.7%    |
| Nvidia GM204GLM [Quadro M4000M]                                               | 1         | 0.7%    |
| Nvidia GM107GLM [Quadro M2000M]                                               | 1         | 0.7%    |
| Nvidia GK107M [GeForce GT 650M]                                               | 1         | 0.7%    |
| Nvidia GK107GLM [Quadro K1100M]                                               | 1         | 0.7%    |
| Nvidia GF114M [GeForce GTX 580M]                                              | 1         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 73        | 57.94%  |
| 2 x Intel      | 13        | 10.32%  |
| Intel + Nvidia | 12        | 9.52%   |
| 1 x AMD        | 12        | 9.52%   |
| 1 x Nvidia     | 8         | 6.35%   |
| Other          | 4         | 3.17%   |
| 2 x Nvidia     | 2         | 1.59%   |
| Intel + AMD    | 2         | 1.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 113       | 89.68%  |
| Unknown     | 7         | 5.56%   |
| Proprietary | 6         | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 116       | 90.63%  |
| 0.51-1.0   | 4         | 3.13%   |
| 0.01-0.5   | 4         | 3.13%   |
| 1.01-2.0   | 3         | 2.34%   |
| 5.01-6.0   | 1         | 0.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 18        | 20.69%  |
| LG Display              | 11        | 12.64%  |
| BOE                     | 10        | 11.49%  |
| Lenovo                  | 8         | 9.2%    |
| Sharp                   | 6         | 6.9%    |
| Samsung Electronics     | 6         | 6.9%    |
| Chimei Innolux          | 6         | 6.9%    |
| Philips                 | 4         | 4.6%    |
| LG Philips              | 2         | 2.3%    |
| Hewlett-Packard         | 2         | 2.3%    |
| HannStar                | 2         | 2.3%    |
| Chi Mei Optoelectronics | 2         | 2.3%    |
| Apple                   | 2         | 2.3%    |
| Vestel Elektronik       | 1         | 1.15%   |
| Sony                    | 1         | 1.15%   |
| SDC                     | 1         | 1.15%   |
| PANDA                   | 1         | 1.15%   |
| InnoLux Display         | 1         | 1.15%   |
| InfoVision              | 1         | 1.15%   |
| HPN                     | 1         | 1.15%   |
| CPT                     | 1         | 1.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Philips 271P4 PHL08C3 1920x1080 600x340mm 27.2-inch                   | 3         | 3.26%   |
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch           | 3         | 3.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 3         | 3.26%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch               | 2         | 2.17%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 290x170mm 13.2-inch        | 2         | 2.17%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1         | 1.09%   |
| Sony SDM-HS95P SNY2500 1280x1024 380x300mm 19.1-inch                  | 1         | 1.09%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x170mm 13.9-inch               | 1         | 1.09%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 290x170mm 13.2-inch               | 1         | 1.09%   |
| Sharp LCD Monitor SHP14D1 1920x1200 340x210mm 15.7-inch               | 1         | 1.09%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch               | 1         | 1.09%   |
| SDC LCD Monitor 5440x1080                                             | 1         | 1.09%   |
| SDC LCD Monitor 3520x1080                                             | 1         | 1.09%   |
| SDC LCD Monitor 1600x900                                              | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch  | 1         | 1.09%   |
| Philips LCD Monitor 271P4 5440x1080                                   | 1         | 1.09%   |
| Philips LCD Monitor 271P4 3520x1080                                   | 1         | 1.09%   |
| Philips LCD Monitor 271P4                                             | 1         | 1.09%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch               | 1         | 1.09%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 1.09%   |
| LG Philips LCD Monitor LPL1279 1680x1050 330x210mm 15.4-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD0508 1366x768 310x170mm 13.9-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x170mm 13.9-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 1         | 1.09%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch              | 1         | 1.09%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 1         | 1.09%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch               | 1         | 1.09%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch               | 1         | 1.09%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 1         | 1.09%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch               | 1         | 1.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 29        | 33.72%  |
| 1366x768 (WXGA)    | 21        | 24.42%  |
| 1280x800 (WXGA)    | 8         | 9.3%    |
| 1600x900 (HD+)     | 6         | 6.98%   |
| 1024x600           | 4         | 4.65%   |
| 3200x1800 (QHD+)   | 3         | 3.49%   |
| 1920x1200 (WUXGA)  | 3         | 3.49%   |
| 1440x900 (WXGA+)   | 2         | 2.33%   |
| 5440x1080          | 1         | 1.16%   |
| 3840x2160 (4K)     | 1         | 1.16%   |
| 3520x1080          | 1         | 1.16%   |
| 2880x1800          | 1         | 1.16%   |
| 2560x1600          | 1         | 1.16%   |
| 2560x1440 (QHD)    | 1         | 1.16%   |
| 1920x540           | 1         | 1.16%   |
| 1680x1050 (WSXGA+) | 1         | 1.16%   |
| 1280x1024 (SXGA)   | 1         | 1.16%   |
| Unknown            | 1         | 1.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 30        | 35.29%  |
| 13      | 24        | 28.24%  |
| 12      | 7         | 8.24%   |
| 17      | 5         | 5.88%   |
| 27      | 4         | 4.71%   |
| 14      | 3         | 3.53%   |
| 10      | 3         | 3.53%   |
| 11      | 2         | 2.35%   |
| 42      | 1         | 1.18%   |
| 23      | 1         | 1.18%   |
| 22      | 1         | 1.18%   |
| 19      | 1         | 1.18%   |
| 18      | 1         | 1.18%   |
| 9       | 1         | 1.18%   |
| Unknown | 1         | 1.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 43        | 51.19%  |
| 201-300     | 27        | 32.14%  |
| 351-400     | 6         | 7.14%   |
| 501-600     | 4         | 4.76%   |
| 401-500     | 2         | 2.38%   |
| 901-1000    | 1         | 1.19%   |
| Unknown     | 1         | 1.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 60        | 75.95%  |
| 16/10   | 16        | 20.25%  |
| 5/4     | 1         | 1.27%   |
| 3/2     | 1         | 1.27%   |
| Unknown | 1         | 1.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 18        | 21.18%  |
| 91-100         | 17        | 20%     |
| 101-110        | 11        | 12.94%  |
| 71-80          | 9         | 10.59%  |
| 61-70          | 7         | 8.24%   |
| 121-130        | 5         | 5.88%   |
| 41-50          | 4         | 4.71%   |
| 301-350        | 4         | 4.71%   |
| 51-60          | 2         | 2.35%   |
| 201-250        | 2         | 2.35%   |
| 111-120        | 2         | 2.35%   |
| 151-200        | 1         | 1.18%   |
| 141-150        | 1         | 1.18%   |
| 501-1000       | 1         | 1.18%   |
| Unknown        | 1         | 1.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 33        | 39.76%  |
| 101-120       | 25        | 30.12%  |
| 51-100        | 11        | 13.25%  |
| 161-240       | 9         | 10.84%  |
| More than 240 | 4         | 4.82%   |
| Unknown       | 1         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 88        | 67.69%  |
| 0     | 36        | 27.69%  |
| 2     | 5         | 3.85%   |
| 3     | 1         | 0.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 92        | 48.42%  |
| Realtek Semiconductor             | 37        | 19.47%  |
| Qualcomm Atheros                  | 18        | 9.47%   |
| Broadcom                          | 10        | 5.26%   |
| Marvell Technology Group          | 6         | 3.16%   |
| Nvidia                            | 4         | 2.11%   |
| AMD                               | 4         | 2.11%   |
| Hewlett-Packard                   | 3         | 1.58%   |
| D-Link System                     | 3         | 1.58%   |
| Sierra Wireless                   | 2         | 1.05%   |
| Ericsson Business Mobile Networks | 2         | 1.05%   |
| Edimax Technology                 | 2         | 1.05%   |
| Dell                              | 2         | 1.05%   |
| ZyXEL Communications              | 1         | 0.53%   |
| TP-Link                           | 1         | 0.53%   |
| Ralink Technology                 | 1         | 0.53%   |
| Ralink                            | 1         | 0.53%   |
| Qualcomm                          | 1         | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller      | 22        | 8.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 17        | 6.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 13        | 5.18%   |
| Intel Wireless 8265 / 8275                                                  | 10        | 3.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 9         | 3.59%   |
| Intel Wireless 7260                                                         | 9         | 3.59%   |
| Intel Wireless 8260                                                         | 8         | 3.19%   |
| Intel Centrino Advanced-N 6200                                              | 7         | 2.79%   |
| Intel Wi-Fi 6 AX201                                                         | 6         | 2.39%   |
| Intel I211 Gigabit Network Connection                                       | 6         | 2.39%   |
| Intel Wi-Fi 6 AX200                                                         | 5         | 1.99%   |
| Intel Ethernet Connection I219-LM                                           | 5         | 1.99%   |
| Intel 82577LM Gigabit Network Connection                                    | 5         | 1.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 4         | 1.59%   |
| Nvidia MCP79 Ethernet                                                       | 4         | 1.59%   |
| Intel Ethernet Connection I218-LM                                           | 4         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                                       | 4         | 1.59%   |
| Intel Centrino Ultimate-N 6300                                              | 4         | 1.59%   |
| AMD XGMAC 10GbE Controller                                                  | 4         | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 3         | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 3         | 1.2%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                        | 3         | 1.2%    |
| Intel Wireless 3165                                                         | 3         | 1.2%    |
| Intel I210 Gigabit Network Connection                                       | 3         | 1.2%    |
| Intel Ethernet Connection (4) I219-V                                        | 3         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 3         | 1.2%    |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                     | 3         | 1.2%    |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]  | 3         | 1.2%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 3         | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 2         | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2         | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                                  | 2         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2         | 0.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 2         | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 0.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 2         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                       | 2         | 0.8%    |
| Intel 82567LM Gigabit Network Connection                                    | 2         | 0.8%    |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 2         | 0.8%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 80        | 62.02%  |
| Qualcomm Atheros      | 17        | 13.18%  |
| Realtek Semiconductor | 14        | 10.85%  |
| Broadcom              | 8         | 6.2%    |
| D-Link System         | 3         | 2.33%   |
| Edimax Technology     | 2         | 1.55%   |
| ZyXEL Communications  | 1         | 0.78%   |
| TP-Link               | 1         | 0.78%   |
| Sierra Wireless       | 1         | 0.78%   |
| Ralink Technology     | 1         | 0.78%   |
| Ralink                | 1         | 0.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 13        | 9.85%   |
| Intel Wireless 8265 / 8275                                                 | 10        | 7.58%   |
| Intel Wireless 7260                                                        | 9         | 6.82%   |
| Intel Wireless 8260                                                        | 8         | 6.06%   |
| Intel Centrino Advanced-N 6200                                             | 7         | 5.3%    |
| Intel Wi-Fi 6 AX201                                                        | 6         | 4.55%   |
| Intel Wi-Fi 6 AX200                                                        | 5         | 3.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)    | 4         | 3.03%   |
| Intel Centrino Ultimate-N 6300                                             | 4         | 3.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 3         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 3         | 2.27%   |
| Intel Wireless 3165                                                        | 3         | 2.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 3         | 2.27%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 3         | 2.27%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 3         | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 2         | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2         | 1.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 2         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 2         | 1.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 2         | 1.52%   |
| Broadcom BCM4331 802.11a/b/g/n                                             | 2         | 1.52%   |
| ZyXEL NWD2105 802.11bgn Wireless Adapter [Ralink RT3070]                   | 1         | 0.76%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1         | 0.76%   |
| Sierra Wireless EM7345 4G LTE                                              | 1         | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                                 | 1         | 0.76%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                         | 1         | 0.76%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1         | 0.76%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                      | 1         | 0.76%   |
| Ralink RT2501/RT2573 Wireless Adapter                                      | 1         | 0.76%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 1         | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1         | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 0.76%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 1         | 0.76%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)    | 1         | 0.76%   |
| Intel Wireless 3160                                                        | 1         | 0.76%   |
| Intel WiFi Link 5100                                                       | 1         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 54        | 49.54%  |
| Realtek Semiconductor    | 32        | 29.36%  |
| Marvell Technology Group | 6         | 5.5%    |
| Qualcomm Atheros         | 4         | 3.67%   |
| Nvidia                   | 4         | 3.67%   |
| Broadcom                 | 4         | 3.67%   |
| AMD                      | 4         | 3.67%   |
| Qualcomm                 | 1         | 0.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 22        | 19.82%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 17        | 15.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9         | 8.11%   |
| Intel I211 Gigabit Network Connection                                  | 6         | 5.41%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 4.5%    |
| Intel 82577LM Gigabit Network Connection                               | 5         | 4.5%    |
| Nvidia MCP79 Ethernet                                                  | 4         | 3.6%    |
| Intel Ethernet Connection I218-LM                                      | 4         | 3.6%    |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 3.6%    |
| AMD XGMAC 10GbE Controller                                             | 4         | 3.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 3         | 2.7%    |
| Intel I210 Gigabit Network Connection                                  | 3         | 2.7%    |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 2.7%    |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.8%    |
| Intel 82567LM Gigabit Network Connection                               | 2         | 1.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.9%    |
| Qualcomm FP3                                                           | 1         | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.9%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.9%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.9%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 0.9%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.9%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.9%    |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.9%    |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.9%    |
| Intel 82577LC Gigabit Network Connection                               | 1         | 0.9%    |
| Intel 82574L Gigabit Network Connection                                | 1         | 0.9%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1         | 0.9%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 0.9%    |
| Broadcom BCM4401-B0 100Base-TX                                         | 1         | 0.9%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 119       | 51.74%  |
| Ethernet | 103       | 44.78%  |
| Unknown  | 5         | 2.17%   |
| Modem    | 3         | 1.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 85        | 54.49%  |
| Ethernet | 68        | 43.59%  |
| Modem    | 3         | 1.92%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 95        | 75.4%   |
| 1     | 23        | 18.25%  |
| 5     | 4         | 3.17%   |
| 3     | 2         | 1.59%   |
| 6     | 1         | 0.79%   |
| 4     | 1         | 0.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 116       | 89.92%  |
| Yes  | 13        | 10.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 55%     |
| Broadcom                        | 11        | 13.75%  |
| Realtek Semiconductor           | 6         | 7.5%    |
| Apple                           | 6         | 7.5%    |
| Dell                            | 5         | 6.25%   |
| Qualcomm Atheros Communications | 2         | 2.5%    |
| Foxconn / Hon Hai               | 2         | 2.5%    |
| Skylight Digital                | 1         | 1.25%   |
| IMC Networks                    | 1         | 1.25%   |
| ASUSTek Computer                | 1         | 1.25%   |
| Alps Electric                   | 1         | 1.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 26        | 32.5%   |
| Intel AX201 Bluetooth                                                               | 6         | 7.5%    |
| Apple Bluetooth Host Controller                                                     | 6         | 7.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 6.25%   |
| Intel AX200 Bluetooth                                                               | 5         | 6.25%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 5%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 3.75%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 3.75%   |
| Realtek Bluetooth Adapter                                                           | 2         | 2.5%    |
| Realtek Bluetooth 4.0 Adapter                                                       | 2         | 2.5%    |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 2.5%    |
| Skylight Digital Realtek Bluetooth Adapter                                          | 1         | 1.25%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 1.25%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.25%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                                              | 1         | 1.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.25%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.25%   |
| Intel AX211 Bluetooth                                                               | 1         | 1.25%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS                             | 1         | 1.25%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.25%   |
| Foxconn / Hon Hai Bluetooth USB Module                                              | 1         | 1.25%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                                         | 1         | 1.25%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 1.25%   |
| Broadcom Bluetooth                                                                  | 1         | 1.25%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 1.25%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 1.25%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 1.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 106       | 75.18%  |
| AMD                 | 18        | 12.77%  |
| Nvidia              | 9         | 6.38%   |
| SteelSeries ApS     | 4         | 2.84%   |
| C-Media Electronics | 2         | 1.42%   |
| JMTek               | 1         | 0.71%   |
| GN Netcom           | 1         | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 11.11%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 8.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 8.02%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 6.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 5.56%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 5.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 4.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 4.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 3.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 3.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 3.09%   |
| SteelSeries ApS SteelSeries Siberia 350                                                           | 4         | 2.47%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 2.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 2.47%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 2.47%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 2.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.23%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.23%   |
| C-Media Electronics USB Audio Class 1.0 and 2.0 Device                                            | 2         | 1.23%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.62%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.62%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.62%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.62%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.62%   |
| JMTek audio controller                                                                            | 1         | 0.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.62%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.62%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.62%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.62%   |
| GN Netcom Jabra Evolve 65                                                                         | 1         | 0.62%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.62%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 40        | 30.3%   |
| SK hynix            | 27        | 20.45%  |
| Micron Technology   | 17        | 12.88%  |
| Unknown             | 11        | 8.33%   |
| Crucial             | 10        | 7.58%   |
| Kingston            | 7         | 5.3%    |
| Transcend           | 4         | 3.03%   |
| Unknown (ABCD)      | 3         | 2.27%   |
| Elpida              | 3         | 2.27%   |
| Unknown             | 3         | 2.27%   |
| Corsair             | 2         | 1.52%   |
| A-DATA Technology   | 2         | 1.52%   |
| GSkill              | 1         | 0.76%   |
| A Force             | 1         | 0.76%   |
| 48spaces            | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 3.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 3.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 3.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 3.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 2.78%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 2.08%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 3         | 2.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.08%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 2.08%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.08%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.08%   |
| Unknown                                                          | 3         | 2.08%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.39%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 1.39%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.39%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 1.39%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 2         | 1.39%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.39%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 2         | 1.39%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 1.39%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1.39%   |
| Elpida RAM 8KTS51264HDZ-1G6E1 4GB Chip DDR3 1600MT/s             | 2         | 1.39%   |
| Unknown SODIMM 2GB SODIMM DDR2 533MT/s                           | 1         | 0.69%   |
| Unknown SODIMM 2048MB SODIMM DDR2 533MT/s                        | 1         | 0.69%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.69%   |
| Unknown RAM Module 4096MB SODIMM 1066MT/s                        | 1         | 0.69%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                            | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.69%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s            | 1         | 0.69%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1333MT/s                     | 1         | 0.69%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 0.69%   |
| SK hynix RAM LX8GDDR3LS1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.69%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.69%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.69%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.69%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.69%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s          | 1         | 0.69%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 54        | 47.79%  |
| DDR4    | 38        | 33.63%  |
| DDR2    | 10        | 8.85%   |
| LPDDR4  | 4         | 3.54%   |
| Unknown | 4         | 3.54%   |
| LPDDR3  | 2         | 1.77%   |
| DDR     | 1         | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 102       | 91.07%  |
| Row Of Chips | 5         | 4.46%   |
| Chip         | 3         | 2.68%   |
| DIMM         | 1         | 0.89%   |
| Unknown      | 1         | 0.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 52        | 42.28%  |
| 8192  | 38        | 30.89%  |
| 2048  | 21        | 17.07%  |
| 16384 | 8         | 6.5%    |
| 32768 | 4         | 3.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 34        | 27.87%  |
| 2400  | 14        | 11.48%  |
| 2667  | 13        | 10.66%  |
| 3200  | 12        | 9.84%   |
| 1334  | 9         | 7.38%   |
| 1333  | 9         | 7.38%   |
| 667   | 7         | 5.74%   |
| 2133  | 6         | 4.92%   |
| 1867  | 5         | 4.1%    |
| 1067  | 4         | 3.28%   |
| 800   | 3         | 2.46%   |
| 1066  | 2         | 1.64%   |
| 533   | 2         | 1.64%   |
| 4267  | 1         | 0.82%   |
| 333   | 1         | 0.82%   |

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
| Chicony Electronics                    | 20        | 23.53%  |
| Realtek Semiconductor                  | 9         | 10.59%  |
| Bison Electronics                      | 8         | 9.41%   |
| IMC Networks                           | 6         | 7.06%   |
| Microdia                               | 5         | 5.88%   |
| Lite-On Technology                     | 5         | 5.88%   |
| Z-Star Microelectronics                | 4         | 4.71%   |
| Syntek                                 | 4         | 4.71%   |
| Suyin                                  | 3         | 3.53%   |
| Sunplus Innovation Technology          | 3         | 3.53%   |
| Luxvisions Innotech Limited            | 3         | 3.53%   |
| Lenovo                                 | 3         | 3.53%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.53%   |
| Silicon Motion                         | 2         | 2.35%   |
| Apple                                  | 2         | 2.35%   |
| Ricoh                                  | 1         | 1.18%   |
| Quanta                                 | 1         | 1.18%   |
| Logitech                               | 1         | 1.18%   |
| Creative Technology                    | 1         | 1.18%   |
| Alcor Micro                            | 1         | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 5         | 5.75%   |
| Realtek Integrated_Webcam_HD                  | 4         | 4.6%    |
| Chicony Lenovo Integrated Camera (0.3MP)      | 4         | 4.6%    |
| Chicony Integrated HP HD Webcam               | 3         | 3.45%   |
| Z-Star Webcam                                 | 2         | 2.3%    |
| Syntek Integrated Camera                      | 2         | 2.3%    |
| Realtek USB 2.0 Webcam                        | 2         | 2.3%    |
| Microdia USB 2.0 Camera                       | 2         | 2.3%    |
| Luxvisions Innotech Limited Integrated Camera | 2         | 2.3%    |
| Lenovo Integrated Webcam                      | 2         | 2.3%    |
| IMC Networks USB2.0 HD UVC WebCam             | 2         | 2.3%    |
| IMC Networks Integrated Camera                | 2         | 2.3%    |
| Bison Integrated Camera                       | 2         | 2.3%    |
| Apple FaceTime HD Camera                      | 2         | 2.3%    |
| Z-Star WebCam SC-03FFL11739P                  | 1         | 1.15%   |
| Z-Star Namuga 1.3M Webcam                     | 1         | 1.15%   |
| Syntek USB 2.0 UVC 1.3M WebCam                | 1         | 1.15%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera | 1         | 1.15%   |
| Suyin Laptop_Integrated_Webcam_3M             | 1         | 1.15%   |
| Suyin Acer Crystal Eye webcam                 | 1         | 1.15%   |
| Suyin 1.3M HD Webcam                          | 1         | 1.15%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 1         | 1.15%   |
| Sunplus Laptop_Integrated_Webcam_1.3M         | 1         | 1.15%   |
| Sunplus HP HD Camera                          | 1         | 1.15%   |
| Silicon Motion WebCam SC-13HDL11939N          | 1         | 1.15%   |
| Silicon Motion 300k Pixel Camera              | 1         | 1.15%   |
| Ricoh Laptop_Integrated_Webcam_3M             | 1         | 1.15%   |
| Realtek USB Camera                            | 1         | 1.15%   |
| Realtek USB 2.0 PC Camera                     | 1         | 1.15%   |
| Realtek PC Camera                             | 1         | 1.15%   |
| Quanta HD Camera                              | 1         | 1.15%   |
| Microdia Webcam Vitade AF                     | 1         | 1.15%   |
| Microdia Integrated_Webcam_HD                 | 1         | 1.15%   |
| Microdia Integrated Webcam                    | 1         | 1.15%   |
| Luxvisions Innotech Limited HP HD Camera      | 1         | 1.15%   |
| Logitech Webcam C930e                         | 1         | 1.15%   |
| Logitech B525 HD Webcam                       | 1         | 1.15%   |
| Lite-On TOSHIBA Web Camera - HD               | 1         | 1.15%   |
| Lite-On Realtek PC Camera                     | 1         | 1.15%   |
| Lite-On Integrated Camera                     | 1         | 1.15%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 22.22%  |
| Upek                       | 5         | 18.52%  |
| Synaptics                  | 5         | 18.52%  |
| Shenzhen Goodix Technology | 4         | 14.81%  |
| Elan Microelectronics      | 3         | 11.11%  |
| Broadcom                   | 2         | 7.41%   |
| AuthenTec                  | 2         | 7.41%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 5         | 18.52%  |
| Shenzhen Goodix Fingerprint Reader                                           | 4         | 14.81%  |
| Elan Fingerprint Sensor                                                      | 3         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 7.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 7.41%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 7.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 3.7%    |
| Validity Sensors Synaptics WBDI                                              | 1         | 3.7%    |
| Validity Sensors Swipe Fingerprint Sensor                                    | 1         | 3.7%    |
| Validity Sensors Fingerprint scanner                                         | 1         | 3.7%    |
| Synaptics UWP WBDI                                                           | 1         | 3.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 3.7%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 1         | 3.7%    |
| AuthenTec AES2810                                                            | 1         | 3.7%    |
| AuthenTec AES1660                                                            | 1         | 3.7%    |

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
| 2     | 44        | 32.59%  |
| 1     | 41        | 30.37%  |
| 0     | 22        | 16.3%   |
| 3     | 15        | 11.11%  |
| 4     | 9         | 6.67%   |
| 5     | 4         | 2.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 90        | 44.12%  |
| Bluetooth                | 32        | 15.69%  |
| Fingerprint reader       | 24        | 11.76%  |
| Net/wireless             | 19        | 9.31%   |
| Firewire controller      | 16        | 7.84%   |
| Card reader              | 15        | 7.35%   |
| Storage                  | 4         | 1.96%   |
| Network                  | 2         | 0.98%   |
| Sound                    | 1         | 0.49%   |
| Graphics card            | 1         | 0.49%   |

