FreeBSD - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for FreeBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/FreeBSD/Desktop/README.md) and [notebooks](/Dist/FreeBSD/Notebook/README.md).

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

Total: 4363

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Acer          | TravelMate B118-M           | Notebook    | [216637ad84](https://bsd-hardware.info/?probe=216637ad84) | May 08, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [c23ee67c69](https://bsd-hardware.info/?probe=c23ee67c69) | May 08, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [b97dcbade6](https://bsd-hardware.info/?probe=b97dcbade6) | May 07, 2024 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [0990e7253e](https://bsd-hardware.info/?probe=0990e7253e) | May 07, 2024 |
| Dell          | 072T6D A01                  | Server      | [a7a95f387b](https://bsd-hardware.info/?probe=a7a95f387b) | May 07, 2024 |
| MSI           | MS-7097                     | Desktop     | [df5c7407fd](https://bsd-hardware.info/?probe=df5c7407fd) | May 06, 2024 |
| Dell          | 0GXM1W A01                  | Desktop     | [1238d729a7](https://bsd-hardware.info/?probe=1238d729a7) | May 06, 2024 |
| ASUSTek       | G11CD                       | Desktop     | [e4d4f0e1b2](https://bsd-hardware.info/?probe=e4d4f0e1b2) | May 06, 2024 |
| Dell          | Precision 7560              | Notebook    | [62956576cd](https://bsd-hardware.info/?probe=62956576cd) | May 06, 2024 |
| Lenovo        | 500w Gen 3 82J3             | Convertible | [02317ba035](https://bsd-hardware.info/?probe=02317ba035) | May 05, 2024 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [e7a48c0ebb](https://bsd-hardware.info/?probe=e7a48c0ebb) | May 05, 2024 |
| MSI           | H81M-P33                    | Desktop     | [db35e993b4](https://bsd-hardware.info/?probe=db35e993b4) | May 05, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [76bd355935](https://bsd-hardware.info/?probe=76bd355935) | May 05, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [4e42133f58](https://bsd-hardware.info/?probe=4e42133f58) | May 05, 2024 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [f67c0c6b18](https://bsd-hardware.info/?probe=f67c0c6b18) | May 05, 2024 |
| Protectli     | FW2B                        | Desktop     | [92725f96b8](https://bsd-hardware.info/?probe=92725f96b8) | May 05, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [89a61aca01](https://bsd-hardware.info/?probe=89a61aca01) | May 04, 2024 |
| HP            | ZBook 17 G2                 | Notebook    | [8558fc6b60](https://bsd-hardware.info/?probe=8558fc6b60) | May 04, 2024 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [89beae510f](https://bsd-hardware.info/?probe=89beae510f) | May 04, 2024 |
| Chuwi         | GemiBook Pro                | Notebook    | [2656d00123](https://bsd-hardware.info/?probe=2656d00123) | May 03, 2024 |
| Dell          | 0MGK50 A02                  | Desktop     | [6f9b5b3cad](https://bsd-hardware.info/?probe=6f9b5b3cad) | May 03, 2024 |
| Dell          | Precision 3571              | Notebook    | [d8015bf7e8](https://bsd-hardware.info/?probe=d8015bf7e8) | May 03, 2024 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [591ac5deba](https://bsd-hardware.info/?probe=591ac5deba) | May 03, 2024 |
| Lenovo        | B40-30 80F1                 | Notebook    | [98be66c2e6](https://bsd-hardware.info/?probe=98be66c2e6) | May 03, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [5240c726c5](https://bsd-hardware.info/?probe=5240c726c5) | May 03, 2024 |
| ASUSTek       | TUF Gaming A620-PRO WIFI    | Desktop     | [a186355a65](https://bsd-hardware.info/?probe=a186355a65) | May 02, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [db2e2d1fbc](https://bsd-hardware.info/?probe=db2e2d1fbc) | May 02, 2024 |
| Dell          | Inspiron 15-3552            | Notebook    | [0a47152038](https://bsd-hardware.info/?probe=0a47152038) | May 02, 2024 |
| Quanta        | S5HF MB 31S5HMB0010         | Server      | [cdfd36bbab](https://bsd-hardware.info/?probe=cdfd36bbab) | May 02, 2024 |
| Dell          | Precision 7560              | Notebook    | [2f6e45641d](https://bsd-hardware.info/?probe=2f6e45641d) | May 02, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [a9ec0cba48](https://bsd-hardware.info/?probe=a9ec0cba48) | May 02, 2024 |
| Supermicro    | X10DRH-iT                   | Server      | [87e2dda1f8](https://bsd-hardware.info/?probe=87e2dda1f8) | May 02, 2024 |
| Dell          | Latitude 7490               | Notebook    | [e55889ef1e](https://bsd-hardware.info/?probe=e55889ef1e) | May 02, 2024 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [671adbdfc4](https://bsd-hardware.info/?probe=671adbdfc4) | May 01, 2024 |
| Lenovo        | ThinkPad E490 20N9S48S00    | Notebook    | [f70fb4bd81](https://bsd-hardware.info/?probe=f70fb4bd81) | May 01, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [15e26ac086](https://bsd-hardware.info/?probe=15e26ac086) | Apr 30, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [72deae70f8](https://bsd-hardware.info/?probe=72deae70f8) | Apr 29, 2024 |
| Acer          | Aspire 5551                 | Notebook    | [ee15a7d2b5](https://bsd-hardware.info/?probe=ee15a7d2b5) | Apr 29, 2024 |
| Dell          | 07N90W A02                  | Desktop     | [f0520bbeb9](https://bsd-hardware.info/?probe=f0520bbeb9) | Apr 29, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [26a2dbed23](https://bsd-hardware.info/?probe=26a2dbed23) | Apr 28, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [126d9918f3](https://bsd-hardware.info/?probe=126d9918f3) | Apr 28, 2024 |
| Quantum en... | HackBoard 2                 | Desktop     | [a7b0ea1eca](https://bsd-hardware.info/?probe=a7b0ea1eca) | Apr 28, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [5bb2644b89](https://bsd-hardware.info/?probe=5bb2644b89) | Apr 28, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [eb205801e7](https://bsd-hardware.info/?probe=eb205801e7) | Apr 27, 2024 |
| HP            | ZBook 15 G6                 | Notebook    | [95aadf59d9](https://bsd-hardware.info/?probe=95aadf59d9) | Apr 27, 2024 |
| ASUSTek       | K43E                        | Notebook    | [19049c7899](https://bsd-hardware.info/?probe=19049c7899) | Apr 27, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [1c5398a208](https://bsd-hardware.info/?probe=1c5398a208) | Apr 26, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [2b066c44b9](https://bsd-hardware.info/?probe=2b066c44b9) | Apr 26, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [a206641c60](https://bsd-hardware.info/?probe=a206641c60) | Apr 26, 2024 |
| System76      | Pangolin                    | Notebook    | [d47c9a5d44](https://bsd-hardware.info/?probe=d47c9a5d44) | Apr 26, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [ac75273460](https://bsd-hardware.info/?probe=ac75273460) | Apr 25, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [ae0802fcda](https://bsd-hardware.info/?probe=ae0802fcda) | Apr 25, 2024 |
| ASRockRack    | W680D4U-2L2T/G5             | Server      | [3f6efbf89d](https://bsd-hardware.info/?probe=3f6efbf89d) | Apr 24, 2024 |
| Supermicro    | X10SDV-F                    | Server      | [89b351b2c6](https://bsd-hardware.info/?probe=89b351b2c6) | Apr 24, 2024 |
| Dell          | 048DY8 A00                  | Desktop     | [9604806e18](https://bsd-hardware.info/?probe=9604806e18) | Apr 24, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [0b322f0da8](https://bsd-hardware.info/?probe=0b322f0da8) | Apr 24, 2024 |
| HP            | ProBook 440 G2              | Notebook    | [459837155f](https://bsd-hardware.info/?probe=459837155f) | Apr 24, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [f5683de21a](https://bsd-hardware.info/?probe=f5683de21a) | Apr 24, 2024 |
| Dell          | 03X6X0 A07                  | Server      | [fcb58713da](https://bsd-hardware.info/?probe=fcb58713da) | Apr 24, 2024 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [d76cb40918](https://bsd-hardware.info/?probe=d76cb40918) | Apr 23, 2024 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [eaee094e07](https://bsd-hardware.info/?probe=eaee094e07) | Apr 23, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [7ae4c9320c](https://bsd-hardware.info/?probe=7ae4c9320c) | Apr 23, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [58a64ecc64](https://bsd-hardware.info/?probe=58a64ecc64) | Apr 23, 2024 |
| ASUSTek       | K43E                        | Notebook    | [cf2e60227c](https://bsd-hardware.info/?probe=cf2e60227c) | Apr 22, 2024 |
| Lenovo        | ThinkBook 16 G5+ APH 21K... | Notebook    | [428f8cd2c7](https://bsd-hardware.info/?probe=428f8cd2c7) | Apr 22, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4f57a0fe86](https://bsd-hardware.info/?probe=4f57a0fe86) | Apr 22, 2024 |
| Lenovo        | ThinkPad T440 20B7S01V00    | Notebook    | [3008b64c82](https://bsd-hardware.info/?probe=3008b64c82) | Apr 22, 2024 |
| Dell          | Precision 7680              | Notebook    | [4987815b22](https://bsd-hardware.info/?probe=4987815b22) | Apr 21, 2024 |
| Lenovo        | ThinkPad T400 6474E18       | Notebook    | [fcd3339ec5](https://bsd-hardware.info/?probe=fcd3339ec5) | Apr 21, 2024 |
| Lenovo        | ThinkPad T530 23942U1       | Notebook    | [a3b075c680](https://bsd-hardware.info/?probe=a3b075c680) | Apr 21, 2024 |
| Lenovo        | 367D 31900059 STD           | Desktop     | [eed4d35722](https://bsd-hardware.info/?probe=eed4d35722) | Apr 21, 2024 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [0384fe830f](https://bsd-hardware.info/?probe=0384fe830f) | Apr 21, 2024 |
| Gigabyte      | B460 AORUS PRO AC           | Desktop     | [fe0730cde5](https://bsd-hardware.info/?probe=fe0730cde5) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [572876d341](https://bsd-hardware.info/?probe=572876d341) | Apr 20, 2024 |
| AZW           | SER V1                      | Desktop     | [4e085db4ef](https://bsd-hardware.info/?probe=4e085db4ef) | Apr 19, 2024 |
| HP            | 3646h                       | Desktop     | [615b37fb0f](https://bsd-hardware.info/?probe=615b37fb0f) | Apr 19, 2024 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [909b53a869](https://bsd-hardware.info/?probe=909b53a869) | Apr 19, 2024 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [bf06ab7481](https://bsd-hardware.info/?probe=bf06ab7481) | Apr 19, 2024 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [2400099ef5](https://bsd-hardware.info/?probe=2400099ef5) | Apr 19, 2024 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [0a6e2a3b33](https://bsd-hardware.info/?probe=0a6e2a3b33) | Apr 18, 2024 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [b874667e73](https://bsd-hardware.info/?probe=b874667e73) | Apr 17, 2024 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [1bc36f8af1](https://bsd-hardware.info/?probe=1bc36f8af1) | Apr 17, 2024 |
| Lenovo        | 367D 31900059 STD           | Desktop     | [b6e893449c](https://bsd-hardware.info/?probe=b6e893449c) | Apr 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [20d7b596db](https://bsd-hardware.info/?probe=20d7b596db) | Apr 17, 2024 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | Notebook    | [ec41825788](https://bsd-hardware.info/?probe=ec41825788) | Apr 17, 2024 |
| Intel         | DP965LT AAD41694-210        | Desktop     | [90e9ba9d77](https://bsd-hardware.info/?probe=90e9ba9d77) | Apr 16, 2024 |
| Intel         | MAHOBAY                     | Desktop     | [c76dc714f2](https://bsd-hardware.info/?probe=c76dc714f2) | Apr 15, 2024 |
| Dell          | 0H21J3 A07                  | Server      | [9315b36ed5](https://bsd-hardware.info/?probe=9315b36ed5) | Apr 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [08cdf907e4](https://bsd-hardware.info/?probe=08cdf907e4) | Apr 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [75fccc1dbe](https://bsd-hardware.info/?probe=75fccc1dbe) | Apr 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [ba545bb931](https://bsd-hardware.info/?probe=ba545bb931) | Apr 15, 2024 |
| Lenovo        | ThinkPad T460 20FMA09CGE    | Notebook    | [c7219eb82e](https://bsd-hardware.info/?probe=c7219eb82e) | Apr 15, 2024 |
| Lenovo        | ThinkPad E550 20DF005VRT    | Notebook    | [5c50bf1b60](https://bsd-hardware.info/?probe=5c50bf1b60) | Apr 14, 2024 |
| MSI           | B450I GAMING PLUS MAX WI... | Desktop     | [7ab7294373](https://bsd-hardware.info/?probe=7ab7294373) | Apr 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [34d08de74d](https://bsd-hardware.info/?probe=34d08de74d) | Apr 13, 2024 |
| ASRock        | X99 Extreme4                | Desktop     | [8d5a19e786](https://bsd-hardware.info/?probe=8d5a19e786) | Apr 13, 2024 |
| ASRock        | X99 Extreme4                | Desktop     | [f2fdbc8d66](https://bsd-hardware.info/?probe=f2fdbc8d66) | Apr 13, 2024 |
| HUAWEI        | MRGFG-XX                    | Notebook    | [94b19fd1c0](https://bsd-hardware.info/?probe=94b19fd1c0) | Apr 13, 2024 |
| Lenovo        | ThinkPad E490 20N9S48S00    | Notebook    | [a755c9e288](https://bsd-hardware.info/?probe=a755c9e288) | Apr 13, 2024 |
| Fujitsu       | FARQ18004                   | Tablet      | [dd8f55bb7e](https://bsd-hardware.info/?probe=dd8f55bb7e) | Apr 13, 2024 |
| Fujitsu       | FARQ18004                   | Tablet      | [fbebb1537a](https://bsd-hardware.info/?probe=fbebb1537a) | Apr 13, 2024 |
| Fujitsu       | D3427-A1 S26361-D3427-A1    | Desktop     | [0f9af3b2b5](https://bsd-hardware.info/?probe=0f9af3b2b5) | Apr 13, 2024 |
| Lenovo        | ThinkBook 16 G6+ IMH 21L... | Notebook    | [7ae1277ce9](https://bsd-hardware.info/?probe=7ae1277ce9) | Apr 12, 2024 |
| Dell          | 0GM819                      | Desktop     | [6140b5e6ad](https://bsd-hardware.info/?probe=6140b5e6ad) | Apr 12, 2024 |
| Sony          | VGN-FZ4000E                 | Notebook    | [f3d6322ab6](https://bsd-hardware.info/?probe=f3d6322ab6) | Apr 12, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [ad2494f0c0](https://bsd-hardware.info/?probe=ad2494f0c0) | Apr 11, 2024 |
| Lenovo        | ThinkPad T400 6475FA4       | Notebook    | [4318a318e5](https://bsd-hardware.info/?probe=4318a318e5) | Apr 11, 2024 |
| ASUSTek       | Z97-A                       | Desktop     | [2f83e16bd9](https://bsd-hardware.info/?probe=2f83e16bd9) | Apr 11, 2024 |
| Dell          | 0TWW5Y A02                  | Server      | [7f7aa552e1](https://bsd-hardware.info/?probe=7f7aa552e1) | Apr 10, 2024 |
| Gigabyte      | H97M-D3H                    | Desktop     | [8c0a605e99](https://bsd-hardware.info/?probe=8c0a605e99) | Apr 10, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [3fb8a577ad](https://bsd-hardware.info/?probe=3fb8a577ad) | Apr 10, 2024 |
| System76      | Pangolin                    | Notebook    | [faa2fc0480](https://bsd-hardware.info/?probe=faa2fc0480) | Apr 09, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [816bfd4777](https://bsd-hardware.info/?probe=816bfd4777) | Apr 09, 2024 |
| Intel         | D525MW AAE93082-401         | Desktop     | [9a37f5660f](https://bsd-hardware.info/?probe=9a37f5660f) | Apr 09, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [1335666f76](https://bsd-hardware.info/?probe=1335666f76) | Apr 09, 2024 |
| System76      | Pangolin                    | Notebook    | [e6feb0adcc](https://bsd-hardware.info/?probe=e6feb0adcc) | Apr 09, 2024 |
| ASRock        | AMD BC-250                  | Desktop     | [3b38d89497](https://bsd-hardware.info/?probe=3b38d89497) | Apr 09, 2024 |
| Lenovo        | ThinkPad S5-S531 20B0000... | Notebook    | [cf65a95f23](https://bsd-hardware.info/?probe=cf65a95f23) | Apr 08, 2024 |
| Lenovo        | ThinkPad S5-S531 20B0000... | Notebook    | [bea4d85189](https://bsd-hardware.info/?probe=bea4d85189) | Apr 08, 2024 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [040c686c32](https://bsd-hardware.info/?probe=040c686c32) | Apr 07, 2024 |
| Foxconn       | H61MXV/H67MXV               | Desktop     | [53663c4ae5](https://bsd-hardware.info/?probe=53663c4ae5) | Apr 07, 2024 |
| SolidRun      | CEX7 Platform               | Desktop     | [7c5ed3c2fe](https://bsd-hardware.info/?probe=7c5ed3c2fe) | Apr 06, 2024 |
| HP            | 2B28                        | Desktop     | [b4f2207b5d](https://bsd-hardware.info/?probe=b4f2207b5d) | Apr 06, 2024 |
| HP            | 2B28                        | Desktop     | [5a64d57e01](https://bsd-hardware.info/?probe=5a64d57e01) | Apr 05, 2024 |
| Unknown       | AHP958                      | Notebook    | [69cf299159](https://bsd-hardware.info/?probe=69cf299159) | Apr 04, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [1458ea15f4](https://bsd-hardware.info/?probe=1458ea15f4) | Apr 04, 2024 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [b2bbe7eb8d](https://bsd-hardware.info/?probe=b2bbe7eb8d) | Apr 04, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0ab49168ee](https://bsd-hardware.info/?probe=0ab49168ee) | Apr 02, 2024 |
| ASUSTek       | K43E                        | Notebook    | [f35f5d82f5](https://bsd-hardware.info/?probe=f35f5d82f5) | Mar 31, 2024 |
| Dell          | Latitude 5480               | Notebook    | [ba2a2a829e](https://bsd-hardware.info/?probe=ba2a2a829e) | Mar 31, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [a596a6f2fc](https://bsd-hardware.info/?probe=a596a6f2fc) | Mar 30, 2024 |
| ASRock        | Q1900-ITX                   | Desktop     | [cfceb60c9e](https://bsd-hardware.info/?probe=cfceb60c9e) | Mar 28, 2024 |
| ASRock        | Q1900-ITX                   | Desktop     | [d29def9398](https://bsd-hardware.info/?probe=d29def9398) | Mar 28, 2024 |
| Acer          | Aspire 4730Z                | Notebook    | [18c48b4f53](https://bsd-hardware.info/?probe=18c48b4f53) | Mar 28, 2024 |
| Toshiba       | Satellite C645              | Notebook    | [a5d1838130](https://bsd-hardware.info/?probe=a5d1838130) | Mar 28, 2024 |
| Acer          | Aspire 7730Z                | Notebook    | [7ee3036a24](https://bsd-hardware.info/?probe=7ee3036a24) | Mar 27, 2024 |
| Fujitsu       | LIFEBOOK U727               | Notebook    | [76e6dff995](https://bsd-hardware.info/?probe=76e6dff995) | Mar 27, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS        | Desktop     | [f960805584](https://bsd-hardware.info/?probe=f960805584) | Mar 26, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [6891d04d9b](https://bsd-hardware.info/?probe=6891d04d9b) | Mar 26, 2024 |
| Dell          | 0WXD1Y A00                  | Server      | [e485076a3c](https://bsd-hardware.info/?probe=e485076a3c) | Mar 25, 2024 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [c1d0a393a3](https://bsd-hardware.info/?probe=c1d0a393a3) | Mar 25, 2024 |
| ASRock        | J5040-ITX                   | Desktop     | [075487240d](https://bsd-hardware.info/?probe=075487240d) | Mar 25, 2024 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [33c6bf6200](https://bsd-hardware.info/?probe=33c6bf6200) | Mar 25, 2024 |
| Dell          | Latitude 5580               | Notebook    | [b1969a4408](https://bsd-hardware.info/?probe=b1969a4408) | Mar 25, 2024 |
| MSI           | MS-N014                     | Notebook    | [372cc157f0](https://bsd-hardware.info/?probe=372cc157f0) | Mar 24, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [c2fcfcd39d](https://bsd-hardware.info/?probe=c2fcfcd39d) | Mar 24, 2024 |
| Intel         | D53427RKE G87971-403        | Desktop     | [5cf0576fee](https://bsd-hardware.info/?probe=5cf0576fee) | Mar 23, 2024 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [c27c12203e](https://bsd-hardware.info/?probe=c27c12203e) | Mar 23, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [c00f4d37cc](https://bsd-hardware.info/?probe=c00f4d37cc) | Mar 22, 2024 |
| HP            | ProLiant MicroServer        | Desktop     | [7fa3a9e12a](https://bsd-hardware.info/?probe=7fa3a9e12a) | Mar 22, 2024 |
| HP            | ProLiant MicroServer        | Desktop     | [c158a70e91](https://bsd-hardware.info/?probe=c158a70e91) | Mar 22, 2024 |
| PC Engines    | APU2                        | Desktop     | [1f2d9aef5b](https://bsd-hardware.info/?probe=1f2d9aef5b) | Mar 22, 2024 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f04f1f2154](https://bsd-hardware.info/?probe=f04f1f2154) | Mar 20, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [aeaeb5bff5](https://bsd-hardware.info/?probe=aeaeb5bff5) | Mar 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [9acbce6ef2](https://bsd-hardware.info/?probe=9acbce6ef2) | Mar 19, 2024 |
| Protectli     | FW6 Ver                     | Desktop     | [bab06633ba](https://bsd-hardware.info/?probe=bab06633ba) | Mar 19, 2024 |
| HP            | ZBook 17 G2                 | Notebook    | [8a5397997e](https://bsd-hardware.info/?probe=8a5397997e) | Mar 18, 2024 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | Desktop     | [139d9be65a](https://bsd-hardware.info/?probe=139d9be65a) | Mar 18, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [bbc697af5e](https://bsd-hardware.info/?probe=bbc697af5e) | Mar 17, 2024 |
| Dell          | Latitude D830               | Notebook    | [832440d0c3](https://bsd-hardware.info/?probe=832440d0c3) | Mar 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [2776bdbd27](https://bsd-hardware.info/?probe=2776bdbd27) | Mar 16, 2024 |
| Alienware     | 0446JC A01                  | Desktop     | [d207e3f488](https://bsd-hardware.info/?probe=d207e3f488) | Mar 16, 2024 |
| Acer          | Aspire 4730Z                | Notebook    | [c2025d1b60](https://bsd-hardware.info/?probe=c2025d1b60) | Mar 15, 2024 |
| Lenovo        | IdeaPad 500-14ISK 80NS      | Notebook    | [34ab895e86](https://bsd-hardware.info/?probe=34ab895e86) | Mar 15, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [5b8f4fe788](https://bsd-hardware.info/?probe=5b8f4fe788) | Mar 14, 2024 |
| Maibenben     | MaiBook M                   | Notebook    | [48e337257c](https://bsd-hardware.info/?probe=48e337257c) | Mar 14, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [58cc0f695b](https://bsd-hardware.info/?probe=58cc0f695b) | Mar 14, 2024 |
| ASUSTek       | K43E                        | Notebook    | [1bcbc3c82b](https://bsd-hardware.info/?probe=1bcbc3c82b) | Mar 14, 2024 |
| Dell          | Inspiron 15 3511            | Notebook    | [7ac9f4bd85](https://bsd-hardware.info/?probe=7ac9f4bd85) | Mar 14, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [e97bd00aad](https://bsd-hardware.info/?probe=e97bd00aad) | Mar 13, 2024 |
| TULPAR        | A5 V20.3                    | Notebook    | [476d91b2cf](https://bsd-hardware.info/?probe=476d91b2cf) | Mar 13, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [4b52e91e24](https://bsd-hardware.info/?probe=4b52e91e24) | Mar 13, 2024 |
| Acer          | Aspire V5-573G              | Notebook    | [59445c5f19](https://bsd-hardware.info/?probe=59445c5f19) | Mar 12, 2024 |
| HP            | 829E                        | Mini pc     | [9a88100331](https://bsd-hardware.info/?probe=9a88100331) | Mar 12, 2024 |
| Lenovo        | 310C SDK0J40697 WIN 3305... | Mini pc     | [21ccd8ebd4](https://bsd-hardware.info/?probe=21ccd8ebd4) | Mar 12, 2024 |
| Dell          | 08NPPY A00                  | Desktop     | [adcbf8a526](https://bsd-hardware.info/?probe=adcbf8a526) | Mar 12, 2024 |
| Framework     | Laptop                      | Notebook    | [2c49c1b561](https://bsd-hardware.info/?probe=2c49c1b561) | Mar 12, 2024 |
| Acer          | Nitro AN16-41               | Notebook    | [6ffc9c7b00](https://bsd-hardware.info/?probe=6ffc9c7b00) | Mar 11, 2024 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [6b569c8620](https://bsd-hardware.info/?probe=6b569c8620) | Mar 11, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [93771fbea1](https://bsd-hardware.info/?probe=93771fbea1) | Mar 11, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [322c6ac646](https://bsd-hardware.info/?probe=322c6ac646) | Mar 11, 2024 |
| MSI           | Bravo 15 C7VFKP             | Notebook    | [4efb48cb1c](https://bsd-hardware.info/?probe=4efb48cb1c) | Mar 11, 2024 |
| Acer          | Aspire A514-54              | Notebook    | [926fbd1fcf](https://bsd-hardware.info/?probe=926fbd1fcf) | Mar 11, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0ceb5cfbf8](https://bsd-hardware.info/?probe=0ceb5cfbf8) | Mar 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [820c6cbe0c](https://bsd-hardware.info/?probe=820c6cbe0c) | Mar 10, 2024 |
| ZOTAC         | Unknown                     | Desktop     | [9217678a4f](https://bsd-hardware.info/?probe=9217678a4f) | Mar 10, 2024 |
| HP            | Compaq Presario C700        | Notebook    | [ae4a5bc366](https://bsd-hardware.info/?probe=ae4a5bc366) | Mar 09, 2024 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [7158ba18d1](https://bsd-hardware.info/?probe=7158ba18d1) | Mar 07, 2024 |
| Dell          | 002KVM A01                  | Desktop     | [92ae9e6766](https://bsd-hardware.info/?probe=92ae9e6766) | Mar 07, 2024 |
| HUAWEI        | CREFG-XX                    | Notebook    | [b16b7180ee](https://bsd-hardware.info/?probe=b16b7180ee) | Mar 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop S560... | Notebook    | [fa7a3ad31d](https://bsd-hardware.info/?probe=fa7a3ad31d) | Mar 05, 2024 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [b0e5a68883](https://bsd-hardware.info/?probe=b0e5a68883) | Mar 03, 2024 |
| Dell          | Inspiron 5559               | Notebook    | [2010f287bf](https://bsd-hardware.info/?probe=2010f287bf) | Mar 03, 2024 |
| Toshiba       | Satellite P300              | Notebook    | [3ecfa61763](https://bsd-hardware.info/?probe=3ecfa61763) | Mar 03, 2024 |
| Lenovo        | ThinkPad X230 23254S6       | Notebook    | [cae99ac427](https://bsd-hardware.info/?probe=cae99ac427) | Mar 03, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [89647876db](https://bsd-hardware.info/?probe=89647876db) | Mar 02, 2024 |
| Lenovo        | ThinkPad T495 20NJ0000US    | Notebook    | [052c7d6fdf](https://bsd-hardware.info/?probe=052c7d6fdf) | Mar 01, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [cd922b0100](https://bsd-hardware.info/?probe=cd922b0100) | Feb 29, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [f2248d5411](https://bsd-hardware.info/?probe=f2248d5411) | Feb 28, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0857785c6d](https://bsd-hardware.info/?probe=0857785c6d) | Feb 27, 2024 |
| ASUSTek       | P8P67                       | Desktop     | [1971d6c84c](https://bsd-hardware.info/?probe=1971d6c84c) | Feb 27, 2024 |
| Supermicro    | X7DWE                       | Desktop     | [23e991022f](https://bsd-hardware.info/?probe=23e991022f) | Feb 27, 2024 |
| Lenovo        | B40-30 80F1                 | Notebook    | [9e435212e2](https://bsd-hardware.info/?probe=9e435212e2) | Feb 27, 2024 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [c0561cccdd](https://bsd-hardware.info/?probe=c0561cccdd) | Feb 26, 2024 |
| Supermicro    | X10DRH-iT                   | Server      | [8aa7f1166e](https://bsd-hardware.info/?probe=8aa7f1166e) | Feb 26, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [4d63500465](https://bsd-hardware.info/?probe=4d63500465) | Feb 26, 2024 |
| IP3 Techno... | ARN39E                      | Notebook    | [e6405ae506](https://bsd-hardware.info/?probe=e6405ae506) | Feb 26, 2024 |
| MSI           | H81M-P33                    | Desktop     | [7e215d6165](https://bsd-hardware.info/?probe=7e215d6165) | Feb 25, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [d86a9bc700](https://bsd-hardware.info/?probe=d86a9bc700) | Feb 25, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7c8bd6104e](https://bsd-hardware.info/?probe=7c8bd6104e) | Feb 25, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [101b5912bf](https://bsd-hardware.info/?probe=101b5912bf) | Feb 25, 2024 |
| Dell          | 086D43 A10                  | Server      | [b8c86900b6](https://bsd-hardware.info/?probe=b8c86900b6) | Feb 25, 2024 |
| Dell          | Precision M4800             | Notebook    | [2fb6088a6c](https://bsd-hardware.info/?probe=2fb6088a6c) | Feb 25, 2024 |
| Dell          | Precision M4800             | Notebook    | [8b92089beb](https://bsd-hardware.info/?probe=8b92089beb) | Feb 25, 2024 |
| Acer          | Aspire A315-22              | Notebook    | [809d582231](https://bsd-hardware.info/?probe=809d582231) | Feb 24, 2024 |
| Lenovo        | G50-80 80E5                 | Notebook    | [518698bce2](https://bsd-hardware.info/?probe=518698bce2) | Feb 24, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [151b04e792](https://bsd-hardware.info/?probe=151b04e792) | Feb 23, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [8e96322919](https://bsd-hardware.info/?probe=8e96322919) | Feb 22, 2024 |
| HP            | ProBook 430 G4              | Notebook    | [9d55da54e7](https://bsd-hardware.info/?probe=9d55da54e7) | Feb 22, 2024 |
| Advatronix... | C2750D4I v1.0               | Desktop     | [ba0ab14231](https://bsd-hardware.info/?probe=ba0ab14231) | Feb 22, 2024 |
| Dell          | Latitude E7250              | Notebook    | [ffc8dcf395](https://bsd-hardware.info/?probe=ffc8dcf395) | Feb 22, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [28e6ba3f75](https://bsd-hardware.info/?probe=28e6ba3f75) | Feb 22, 2024 |
| ASRock        | B650 PG Lightning           | Desktop     | [54d6c96d25](https://bsd-hardware.info/?probe=54d6c96d25) | Feb 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [a5ae8a1c9d](https://bsd-hardware.info/?probe=a5ae8a1c9d) | Feb 21, 2024 |
| ASRock        | 4X4-5000 Series             | Desktop     | [dc9ef8f030](https://bsd-hardware.info/?probe=dc9ef8f030) | Feb 21, 2024 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [054056b5fa](https://bsd-hardware.info/?probe=054056b5fa) | Feb 21, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [d64816723d](https://bsd-hardware.info/?probe=d64816723d) | Feb 20, 2024 |
| Infinix       | INBook X1                   | Notebook    | [dd3185320b](https://bsd-hardware.info/?probe=dd3185320b) | Feb 20, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [3cd6bbf6be](https://bsd-hardware.info/?probe=3cd6bbf6be) | Feb 19, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [59c7610a80](https://bsd-hardware.info/?probe=59c7610a80) | Feb 19, 2024 |
| Dell          | 0FF3FN A00                  | Desktop     | [cb83e35a3e](https://bsd-hardware.info/?probe=cb83e35a3e) | Feb 19, 2024 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [d84e00c746](https://bsd-hardware.info/?probe=d84e00c746) | Feb 19, 2024 |
| Gigabyte      | G1.Sniper H6                | Desktop     | [471f2213f0](https://bsd-hardware.info/?probe=471f2213f0) | Feb 19, 2024 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [057ab23bee](https://bsd-hardware.info/?probe=057ab23bee) | Feb 18, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [7aeebe2c82](https://bsd-hardware.info/?probe=7aeebe2c82) | Feb 18, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [6c06931b93](https://bsd-hardware.info/?probe=6c06931b93) | Feb 18, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [84aa76dfc8](https://bsd-hardware.info/?probe=84aa76dfc8) | Feb 18, 2024 |
| Dell          | Latitude E6430              | Notebook    | [1f9f417c2f](https://bsd-hardware.info/?probe=1f9f417c2f) | Feb 18, 2024 |
| HP            | 83E9                        | Desktop     | [f5a6f9001d](https://bsd-hardware.info/?probe=f5a6f9001d) | Feb 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [a7aada8678](https://bsd-hardware.info/?probe=a7aada8678) | Feb 17, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [fb1f5f8545](https://bsd-hardware.info/?probe=fb1f5f8545) | Feb 16, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [cc65de13e8](https://bsd-hardware.info/?probe=cc65de13e8) | Feb 16, 2024 |
| Dell          | Latitude E7470              | Notebook    | [3a08bc08be](https://bsd-hardware.info/?probe=3a08bc08be) | Feb 15, 2024 |
| Google        | Ultima                      | Notebook    | [732adeb5e4](https://bsd-hardware.info/?probe=732adeb5e4) | Feb 15, 2024 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [7fcc4087e9](https://bsd-hardware.info/?probe=7fcc4087e9) | Feb 15, 2024 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [f9ad9d25e3](https://bsd-hardware.info/?probe=f9ad9d25e3) | Feb 14, 2024 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [c56fc3f2fc](https://bsd-hardware.info/?probe=c56fc3f2fc) | Feb 14, 2024 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [acb70accb8](https://bsd-hardware.info/?probe=acb70accb8) | Feb 14, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [7a18edf610](https://bsd-hardware.info/?probe=7a18edf610) | Feb 13, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [d24c0ab2c0](https://bsd-hardware.info/?probe=d24c0ab2c0) | Feb 13, 2024 |
| Dell          | Inspiron 3558               | Notebook    | [e0e665c1b5](https://bsd-hardware.info/?probe=e0e665c1b5) | Feb 13, 2024 |
| Dell          | 0PC10G A00                  | Mini pc     | [836dac7d2c](https://bsd-hardware.info/?probe=836dac7d2c) | Feb 13, 2024 |
| ASRock        | Z590 Steel Legend           | Desktop     | [e7dfc1ffe5](https://bsd-hardware.info/?probe=e7dfc1ffe5) | Feb 13, 2024 |
| ASRock        | Z590 Steel Legend           | Desktop     | [30702fa4b5](https://bsd-hardware.info/?probe=30702fa4b5) | Feb 13, 2024 |
| Lenovo        | ThinkPad T410 2522WAR       | Notebook    | [caccf07908](https://bsd-hardware.info/?probe=caccf07908) | Feb 12, 2024 |
| Dell          | 0FF3FN A00                  | Desktop     | [56b53a9e68](https://bsd-hardware.info/?probe=56b53a9e68) | Feb 11, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [fa2107c718](https://bsd-hardware.info/?probe=fa2107c718) | Feb 11, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [08506a1aff](https://bsd-hardware.info/?probe=08506a1aff) | Feb 11, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5f3d8e3288](https://bsd-hardware.info/?probe=5f3d8e3288) | Feb 11, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [977c74f4c0](https://bsd-hardware.info/?probe=977c74f4c0) | Feb 08, 2024 |
| HP            | ProLiant DL180 G6           | Server      | [bf8b98f373](https://bsd-hardware.info/?probe=bf8b98f373) | Feb 08, 2024 |
| Gigabyte      | H81M-D2V                    | Desktop     | [1b2b064c64](https://bsd-hardware.info/?probe=1b2b064c64) | Feb 08, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [2a4911715a](https://bsd-hardware.info/?probe=2a4911715a) | Feb 07, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [365bb9e521](https://bsd-hardware.info/?probe=365bb9e521) | Feb 07, 2024 |
| Panasonic     | CF-52VDA131M                | Notebook    | [1ebdac9598](https://bsd-hardware.info/?probe=1ebdac9598) | Feb 07, 2024 |
| ASRock        | B450M-HDV                   | Desktop     | [841a005fc8](https://bsd-hardware.info/?probe=841a005fc8) | Feb 06, 2024 |
| Supermicro    | A1SRM-2758F                 | Server      | [aa8f6d0d16](https://bsd-hardware.info/?probe=aa8f6d0d16) | Feb 06, 2024 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [6a6b1dbe8f](https://bsd-hardware.info/?probe=6a6b1dbe8f) | Feb 06, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [e7c9d50432](https://bsd-hardware.info/?probe=e7c9d50432) | Feb 05, 2024 |
| Lenovo        | ThinkCentre M90p 3853RN9    | Desktop     | [c0395ca728](https://bsd-hardware.info/?probe=c0395ca728) | Feb 05, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [c77173c2f3](https://bsd-hardware.info/?probe=c77173c2f3) | Feb 04, 2024 |
| MSI           | H81M-P33                    | Desktop     | [444eaddd27](https://bsd-hardware.info/?probe=444eaddd27) | Feb 04, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [87358bcf94](https://bsd-hardware.info/?probe=87358bcf94) | Feb 04, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [94f15f8857](https://bsd-hardware.info/?probe=94f15f8857) | Feb 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [6a78256797](https://bsd-hardware.info/?probe=6a78256797) | Feb 04, 2024 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [676019447d](https://bsd-hardware.info/?probe=676019447d) | Feb 03, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [95f19036db](https://bsd-hardware.info/?probe=95f19036db) | Feb 03, 2024 |
| Acer          | Aspire A315-22              | Notebook    | [0bd7a59dfe](https://bsd-hardware.info/?probe=0bd7a59dfe) | Feb 02, 2024 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [c0ca7a18ae](https://bsd-hardware.info/?probe=c0ca7a18ae) | Feb 01, 2024 |
| Gigabyte      | Z97-HD3                     | Desktop     | [b41ed8f957](https://bsd-hardware.info/?probe=b41ed8f957) | Feb 01, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [c8d68d0eec](https://bsd-hardware.info/?probe=c8d68d0eec) | Feb 01, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [aae98167a1](https://bsd-hardware.info/?probe=aae98167a1) | Jan 31, 2024 |
| Acer          | TravelMate P645-SG          | Notebook    | [5765a3732f](https://bsd-hardware.info/?probe=5765a3732f) | Jan 31, 2024 |
| Acer          | TravelMate P645-SG          | Notebook    | [32dc9a4b1b](https://bsd-hardware.info/?probe=32dc9a4b1b) | Jan 31, 2024 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | Notebook    | [a1fc491614](https://bsd-hardware.info/?probe=a1fc491614) | Jan 31, 2024 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [a2d3483ef9](https://bsd-hardware.info/?probe=a2d3483ef9) | Jan 30, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [8b93ca6177](https://bsd-hardware.info/?probe=8b93ca6177) | Jan 29, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [5d0e727014](https://bsd-hardware.info/?probe=5d0e727014) | Jan 29, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [19ab947fb4](https://bsd-hardware.info/?probe=19ab947fb4) | Jan 29, 2024 |
| MSI           | H81M-P33                    | Desktop     | [d411f5eb4b](https://bsd-hardware.info/?probe=d411f5eb4b) | Jan 28, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [22436fad84](https://bsd-hardware.info/?probe=22436fad84) | Jan 28, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ec38d3e15f](https://bsd-hardware.info/?probe=ec38d3e15f) | Jan 28, 2024 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [4f45811a17](https://bsd-hardware.info/?probe=4f45811a17) | Jan 27, 2024 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [47783e5e00](https://bsd-hardware.info/?probe=47783e5e00) | Jan 26, 2024 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [713a924dbc](https://bsd-hardware.info/?probe=713a924dbc) | Jan 26, 2024 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [70f47b16e5](https://bsd-hardware.info/?probe=70f47b16e5) | Jan 25, 2024 |
| ASUSTek       | PN50                        | Mini pc     | [5e0f98bff5](https://bsd-hardware.info/?probe=5e0f98bff5) | Jan 25, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [d1da11d4cd](https://bsd-hardware.info/?probe=d1da11d4cd) | Jan 24, 2024 |
| HP            | ProLiant DL180 G6           | Server      | [8682cccdcb](https://bsd-hardware.info/?probe=8682cccdcb) | Jan 24, 2024 |
| HP            | ZBook 17 G2                 | Notebook    | [db2c57b081](https://bsd-hardware.info/?probe=db2c57b081) | Jan 24, 2024 |
| ASRock        | B660M-STX                   | Desktop     | [5ee66bbf7a](https://bsd-hardware.info/?probe=5ee66bbf7a) | Jan 23, 2024 |
| Lenovo        | Legion Y9000X 2020 81TH     | Notebook    | [3711b11e8a](https://bsd-hardware.info/?probe=3711b11e8a) | Jan 23, 2024 |
| SolidRun      | CEX7 Platform               | Desktop     | [ae1a4bcbae](https://bsd-hardware.info/?probe=ae1a4bcbae) | Jan 23, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [50888a6e05](https://bsd-hardware.info/?probe=50888a6e05) | Jan 22, 2024 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [60fb8ff088](https://bsd-hardware.info/?probe=60fb8ff088) | Jan 21, 2024 |
| SolidRun      | CEX7 Platform               | Desktop     | [d876c335eb](https://bsd-hardware.info/?probe=d876c335eb) | Jan 21, 2024 |
| AZW           | SER                         | Mini pc     | [be54157bac](https://bsd-hardware.info/?probe=be54157bac) | Jan 21, 2024 |
| Dell          | Latitude E7450              | Notebook    | [f2216c5d0f](https://bsd-hardware.info/?probe=f2216c5d0f) | Jan 21, 2024 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [d238dc01c7](https://bsd-hardware.info/?probe=d238dc01c7) | Jan 20, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [86b81c8374](https://bsd-hardware.info/?probe=86b81c8374) | Jan 19, 2024 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [32bc5e823d](https://bsd-hardware.info/?probe=32bc5e823d) | Jan 17, 2024 |
| Lenovo        | ThinkPad X220 42912Z1       | Notebook    | [1abc94b4b1](https://bsd-hardware.info/?probe=1abc94b4b1) | Jan 17, 2024 |
| Lenovo        | G50-80 80E5                 | Notebook    | [2330f23f1a](https://bsd-hardware.info/?probe=2330f23f1a) | Jan 16, 2024 |
| Dell          | Precision 7510              | Notebook    | [b5d52d8750](https://bsd-hardware.info/?probe=b5d52d8750) | Jan 16, 2024 |
| Razer         | Blade 16 - RZ09-0483        | Notebook    | [d81973c8bc](https://bsd-hardware.info/?probe=d81973c8bc) | Jan 16, 2024 |
| LG Electro... | 16UD70R-G.AX59B             | Notebook    | [0b08d5b203](https://bsd-hardware.info/?probe=0b08d5b203) | Jan 16, 2024 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [e2053919c4](https://bsd-hardware.info/?probe=e2053919c4) | Jan 15, 2024 |
| Dell          | Latitude 7490               | Notebook    | [e2c44b78da](https://bsd-hardware.info/?probe=e2c44b78da) | Jan 14, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [a95eae54ba](https://bsd-hardware.info/?probe=a95eae54ba) | Jan 13, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [f1224c8ebd](https://bsd-hardware.info/?probe=f1224c8ebd) | Jan 13, 2024 |
| Dell          | Latitude 7490               | Notebook    | [ed2a38e9f5](https://bsd-hardware.info/?probe=ed2a38e9f5) | Jan 13, 2024 |
| Dell          | Latitude E5420              | Notebook    | [eabdd44efe](https://bsd-hardware.info/?probe=eabdd44efe) | Jan 13, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [9736c485c9](https://bsd-hardware.info/?probe=9736c485c9) | Jan 12, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [33704d0025](https://bsd-hardware.info/?probe=33704d0025) | Jan 12, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [c339ed2db4](https://bsd-hardware.info/?probe=c339ed2db4) | Jan 12, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [79707e220e](https://bsd-hardware.info/?probe=79707e220e) | Jan 11, 2024 |
| ASUSTek       | X441UV                      | Notebook    | [6cdd70da49](https://bsd-hardware.info/?probe=6cdd70da49) | Jan 11, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [e6c13bf584](https://bsd-hardware.info/?probe=e6c13bf584) | Jan 11, 2024 |
| Dell          | 0MGK50 A02                  | Desktop     | [311083cbe9](https://bsd-hardware.info/?probe=311083cbe9) | Jan 11, 2024 |
| Dell          | 0MGK50 A02                  | Desktop     | [7c2faad499](https://bsd-hardware.info/?probe=7c2faad499) | Jan 11, 2024 |
| HP            | 255 G7 Notebook PC          | Notebook    | [2c7e743906](https://bsd-hardware.info/?probe=2c7e743906) | Jan 10, 2024 |
| ASRock        | B450M-HDV                   | Desktop     | [c15701f2a9](https://bsd-hardware.info/?probe=c15701f2a9) | Jan 10, 2024 |
| ASRock        | B450M-HDV                   | Desktop     | [82d5d6af92](https://bsd-hardware.info/?probe=82d5d6af92) | Jan 10, 2024 |
| HP            | 255 G7 Notebook PC          | Notebook    | [ef0d0a61f8](https://bsd-hardware.info/?probe=ef0d0a61f8) | Jan 10, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [fa7b4f0216](https://bsd-hardware.info/?probe=fa7b4f0216) | Jan 10, 2024 |
| Rembrandt     | ARB928                      | Notebook    | [47621d7796](https://bsd-hardware.info/?probe=47621d7796) | Jan 10, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [0f475f8e5d](https://bsd-hardware.info/?probe=0f475f8e5d) | Jan 10, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [6b21d0ae92](https://bsd-hardware.info/?probe=6b21d0ae92) | Jan 09, 2024 |
| Dell          | Edge Gateway 5100           | Mini pc     | [908b67bf32](https://bsd-hardware.info/?probe=908b67bf32) | Jan 09, 2024 |
| HP            | 3641h                       | Desktop     | [90626880cf](https://bsd-hardware.info/?probe=90626880cf) | Jan 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [821748c324](https://bsd-hardware.info/?probe=821748c324) | Jan 08, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [1fd0c4124b](https://bsd-hardware.info/?probe=1fd0c4124b) | Jan 08, 2024 |
| Dell          | Inspiron 5555               | Notebook    | [1449593b79](https://bsd-hardware.info/?probe=1449593b79) | Jan 07, 2024 |
| MSI           | B450-A PRO                  | Desktop     | [f7e3102e87](https://bsd-hardware.info/?probe=f7e3102e87) | Jan 07, 2024 |
| MSI           | H81M-P33                    | Desktop     | [e2407e0579](https://bsd-hardware.info/?probe=e2407e0579) | Jan 07, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [e97b058f7c](https://bsd-hardware.info/?probe=e97b058f7c) | Jan 07, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d429a5298b](https://bsd-hardware.info/?probe=d429a5298b) | Jan 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [6564d3ecfe](https://bsd-hardware.info/?probe=6564d3ecfe) | Jan 07, 2024 |
| HP            | Pavilion g6                 | Notebook    | [77f3d49b2e](https://bsd-hardware.info/?probe=77f3d49b2e) | Jan 06, 2024 |
| Roqos         | Core RC10                   | Desktop     | [3f3aabf270](https://bsd-hardware.info/?probe=3f3aabf270) | Jan 06, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [63dc88d57d](https://bsd-hardware.info/?probe=63dc88d57d) | Jan 06, 2024 |
| Lenovo        | ThinkPad 11e 20D90020US     | Notebook    | [7d7f564886](https://bsd-hardware.info/?probe=7d7f564886) | Jan 05, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [90346c6fe3](https://bsd-hardware.info/?probe=90346c6fe3) | Jan 04, 2024 |
| Lenovo        | G50-80 80E5                 | Notebook    | [a678ec59e8](https://bsd-hardware.info/?probe=a678ec59e8) | Jan 04, 2024 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [5c583e5a9d](https://bsd-hardware.info/?probe=5c583e5a9d) | Jan 04, 2024 |
| ASUSTek       | X441UV                      | Notebook    | [29b63ed6a8](https://bsd-hardware.info/?probe=29b63ed6a8) | Jan 04, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [67a65520e6](https://bsd-hardware.info/?probe=67a65520e6) | Jan 03, 2024 |
| Dell          | 0D24M8 A01                  | Desktop     | [17862ade20](https://bsd-hardware.info/?probe=17862ade20) | Jan 03, 2024 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [7ac885382c](https://bsd-hardware.info/?probe=7ac885382c) | Jan 03, 2024 |
| HP            | Laptop 15t-dy100            | Notebook    | [61130d2b74](https://bsd-hardware.info/?probe=61130d2b74) | Jan 03, 2024 |
| ASUSTek       | CM6870                      | Desktop     | [d7b4e67cdc](https://bsd-hardware.info/?probe=d7b4e67cdc) | Jan 03, 2024 |
| Lenovo        | ThinkPad T490s 20NX000MU... | Notebook    | [1271688c43](https://bsd-hardware.info/?probe=1271688c43) | Jan 02, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [a29eec0aa5](https://bsd-hardware.info/?probe=a29eec0aa5) | Jan 02, 2024 |
| Alienware     | 07HV66 A00                  | Desktop     | [ea6a3f3020](https://bsd-hardware.info/?probe=ea6a3f3020) | Jan 01, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [7e2b858339](https://bsd-hardware.info/?probe=7e2b858339) | Dec 31, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [84985aa669](https://bsd-hardware.info/?probe=84985aa669) | Dec 31, 2023 |
| MSI           | H81M-P33                    | Desktop     | [82e08820f2](https://bsd-hardware.info/?probe=82e08820f2) | Dec 31, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [da3b88ef85](https://bsd-hardware.info/?probe=da3b88ef85) | Dec 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [391f4c0e0b](https://bsd-hardware.info/?probe=391f4c0e0b) | Dec 31, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [1889675f37](https://bsd-hardware.info/?probe=1889675f37) | Dec 30, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [56472e8f51](https://bsd-hardware.info/?probe=56472e8f51) | Dec 30, 2023 |
| HP            | 3397                        | Desktop     | [46b6923bcd](https://bsd-hardware.info/?probe=46b6923bcd) | Dec 30, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [fe3a4e49ee](https://bsd-hardware.info/?probe=fe3a4e49ee) | Dec 29, 2023 |
| Dell          | Inspiron 3195               | Convertible | [fb2acd7e84](https://bsd-hardware.info/?probe=fb2acd7e84) | Dec 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [ba78787dff](https://bsd-hardware.info/?probe=ba78787dff) | Dec 29, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [f34b5d84dd](https://bsd-hardware.info/?probe=f34b5d84dd) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B460-G GAMING     | Desktop     | [6b9d713fe0](https://bsd-hardware.info/?probe=6b9d713fe0) | Dec 28, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [4ddf360812](https://bsd-hardware.info/?probe=4ddf360812) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [0a2c02f944](https://bsd-hardware.info/?probe=0a2c02f944) | Dec 27, 2023 |
| Rembrandt     | ARB928                      | Notebook    | [c9a9bfd4aa](https://bsd-hardware.info/?probe=c9a9bfd4aa) | Dec 27, 2023 |
| MSI           | Aspen                       | Desktop     | [ac6dd2b153](https://bsd-hardware.info/?probe=ac6dd2b153) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [4b1250f831](https://bsd-hardware.info/?probe=4b1250f831) | Dec 26, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [533a831b97](https://bsd-hardware.info/?probe=533a831b97) | Dec 26, 2023 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | Desktop     | [504fb1678f](https://bsd-hardware.info/?probe=504fb1678f) | Dec 24, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [a740494857](https://bsd-hardware.info/?probe=a740494857) | Dec 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [278ab700ae](https://bsd-hardware.info/?probe=278ab700ae) | Dec 24, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [7e4cee9689](https://bsd-hardware.info/?probe=7e4cee9689) | Dec 24, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [04675127c2](https://bsd-hardware.info/?probe=04675127c2) | Dec 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1ef7136151](https://bsd-hardware.info/?probe=1ef7136151) | Dec 24, 2023 |
| Acer          | Veriton X490G               | Desktop     | [3f4dbee6d1](https://bsd-hardware.info/?probe=3f4dbee6d1) | Dec 24, 2023 |
| Acer          | Veriton X490G               | Desktop     | [1865afdae1](https://bsd-hardware.info/?probe=1865afdae1) | Dec 24, 2023 |
| Dell          | Precision 5510              | Notebook    | [4bad5ad995](https://bsd-hardware.info/?probe=4bad5ad995) | Dec 23, 2023 |
| Dell          | Precision 7720              | Notebook    | [a30d05e373](https://bsd-hardware.info/?probe=a30d05e373) | Dec 23, 2023 |
| TULPAR        | A5 V20.3                    | Notebook    | [89b65e7036](https://bsd-hardware.info/?probe=89b65e7036) | Dec 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [85ec93f4cd](https://bsd-hardware.info/?probe=85ec93f4cd) | Dec 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [34f3eb8059](https://bsd-hardware.info/?probe=34f3eb8059) | Dec 22, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [06457349dc](https://bsd-hardware.info/?probe=06457349dc) | Dec 22, 2023 |
| Clevo         | W240BU                      | Notebook    | [19bb603cab](https://bsd-hardware.info/?probe=19bb603cab) | Dec 20, 2023 |
| Lenovo        | ThinkPad T490s 20NYS4HL1... | Notebook    | [97fb2e025e](https://bsd-hardware.info/?probe=97fb2e025e) | Dec 20, 2023 |
| Dell          | 0VD5HY A00                  | Desktop     | [03b0e973ca](https://bsd-hardware.info/?probe=03b0e973ca) | Dec 19, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | Notebook    | [4bc98299dd](https://bsd-hardware.info/?probe=4bc98299dd) | Dec 18, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YV... | Notebook    | [10fb96c00d](https://bsd-hardware.info/?probe=10fb96c00d) | Dec 18, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [5a4d01667e](https://bsd-hardware.info/?probe=5a4d01667e) | Dec 17, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ea79e98108](https://bsd-hardware.info/?probe=ea79e98108) | Dec 17, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [1eb8cc9d76](https://bsd-hardware.info/?probe=1eb8cc9d76) | Dec 17, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [11e5e87b70](https://bsd-hardware.info/?probe=11e5e87b70) | Dec 16, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [2c652aa0a1](https://bsd-hardware.info/?probe=2c652aa0a1) | Dec 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [4b134e7787](https://bsd-hardware.info/?probe=4b134e7787) | Dec 16, 2023 |
| CSL-Comput... | C15 v3                      | Notebook    | [dd93594896](https://bsd-hardware.info/?probe=dd93594896) | Dec 16, 2023 |
| Lenovo        | ThinkPad P1 20MD002MUS      | Notebook    | [c0dcfec41d](https://bsd-hardware.info/?probe=c0dcfec41d) | Dec 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7a5e6024cd](https://bsd-hardware.info/?probe=7a5e6024cd) | Dec 15, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [7a32a123f6](https://bsd-hardware.info/?probe=7a32a123f6) | Dec 15, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [b6845a3e54](https://bsd-hardware.info/?probe=b6845a3e54) | Dec 15, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [e1867819f3](https://bsd-hardware.info/?probe=e1867819f3) | Dec 15, 2023 |
| Dell          | Latitude E6220              | Notebook    | [372070b2f2](https://bsd-hardware.info/?probe=372070b2f2) | Dec 15, 2023 |
| Google        | Kohaku                      | Notebook    | [0b945d8f38](https://bsd-hardware.info/?probe=0b945d8f38) | Dec 15, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [c197b26909](https://bsd-hardware.info/?probe=c197b26909) | Dec 14, 2023 |
| Dell          | Latitude 3420               | Notebook    | [3767d653b9](https://bsd-hardware.info/?probe=3767d653b9) | Dec 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [88d2ae1175](https://bsd-hardware.info/?probe=88d2ae1175) | Dec 14, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [60451d4e43](https://bsd-hardware.info/?probe=60451d4e43) | Dec 14, 2023 |
| Dell          | Latitude E6540              | Notebook    | [77a9b10ab9](https://bsd-hardware.info/?probe=77a9b10ab9) | Dec 13, 2023 |
| AZW           | EQ                          | Desktop     | [d83e11a7dc](https://bsd-hardware.info/?probe=d83e11a7dc) | Dec 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [bc50d301fa](https://bsd-hardware.info/?probe=bc50d301fa) | Dec 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [dced442907](https://bsd-hardware.info/?probe=dced442907) | Dec 13, 2023 |
| Google        | Lindar rev3                 | Notebook    | [2e748fc42c](https://bsd-hardware.info/?probe=2e748fc42c) | Dec 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [a7fcca51be](https://bsd-hardware.info/?probe=a7fcca51be) | Dec 13, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [357a808604](https://bsd-hardware.info/?probe=357a808604) | Dec 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [9a842bf3c8](https://bsd-hardware.info/?probe=9a842bf3c8) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [123088175c](https://bsd-hardware.info/?probe=123088175c) | Dec 11, 2023 |
| Dell          | 0N051F A04                  | Server      | [38535e6878](https://bsd-hardware.info/?probe=38535e6878) | Dec 11, 2023 |
| Dell          | 0XDN97 A09                  | Server      | [129a73f16f](https://bsd-hardware.info/?probe=129a73f16f) | Dec 11, 2023 |
| EVGA          | X570 DARK.0                 | Desktop     | [1c84a8169b](https://bsd-hardware.info/?probe=1c84a8169b) | Dec 11, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [6e876a349f](https://bsd-hardware.info/?probe=6e876a349f) | Dec 11, 2023 |
| Dell          | 084XW4 A05                  | Server      | [951a41f88c](https://bsd-hardware.info/?probe=951a41f88c) | Dec 11, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [2febbeffc2](https://bsd-hardware.info/?probe=2febbeffc2) | Dec 11, 2023 |
| Dell          | 084XW4 A06                  | Server      | [961b6ac6f7](https://bsd-hardware.info/?probe=961b6ac6f7) | Dec 11, 2023 |
| Dell          | Latitude E6510              | Notebook    | [86c4864c0a](https://bsd-hardware.info/?probe=86c4864c0a) | Dec 11, 2023 |
| Dell          | Latitude E6510              | Notebook    | [dc2d54a168](https://bsd-hardware.info/?probe=dc2d54a168) | Dec 11, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [9368c19a35](https://bsd-hardware.info/?probe=9368c19a35) | Dec 11, 2023 |
| AZW           | EQ                          | Desktop     | [0280c1cdb9](https://bsd-hardware.info/?probe=0280c1cdb9) | Dec 10, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [881ad2eacf](https://bsd-hardware.info/?probe=881ad2eacf) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [47480f848d](https://bsd-hardware.info/?probe=47480f848d) | Dec 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [2b1599aacd](https://bsd-hardware.info/?probe=2b1599aacd) | Dec 10, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [89f0463ec6](https://bsd-hardware.info/?probe=89f0463ec6) | Dec 10, 2023 |
| Google        | Parrot                      | Notebook    | [c10a95cbcc](https://bsd-hardware.info/?probe=c10a95cbcc) | Dec 10, 2023 |
| Google        | Parrot                      | Notebook    | [3a69ea2682](https://bsd-hardware.info/?probe=3a69ea2682) | Dec 10, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [78399ba39e](https://bsd-hardware.info/?probe=78399ba39e) | Dec 09, 2023 |
| Gigabyte      | B650 AORUS ELITE AX V2      | Desktop     | [7a6cdb3f06](https://bsd-hardware.info/?probe=7a6cdb3f06) | Dec 09, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [d62ad0d622](https://bsd-hardware.info/?probe=d62ad0d622) | Dec 09, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [5b31c551ae](https://bsd-hardware.info/?probe=5b31c551ae) | Dec 09, 2023 |
| Dell          | Latitude 7414               | Notebook    | [2d57c22982](https://bsd-hardware.info/?probe=2d57c22982) | Dec 08, 2023 |
| Dell          | Precision 7560              | Notebook    | [13f7324bd9](https://bsd-hardware.info/?probe=13f7324bd9) | Dec 07, 2023 |
| Dell          | Precision 7560              | Notebook    | [5d3e6e3bd4](https://bsd-hardware.info/?probe=5d3e6e3bd4) | Dec 07, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [7fd4743b86](https://bsd-hardware.info/?probe=7fd4743b86) | Dec 07, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [406d7a0572](https://bsd-hardware.info/?probe=406d7a0572) | Dec 07, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [7476cc6440](https://bsd-hardware.info/?probe=7476cc6440) | Dec 06, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [41e61ade9a](https://bsd-hardware.info/?probe=41e61ade9a) | Dec 06, 2023 |
| Lenovo        | ThinkPad W520 4270CTO       | Notebook    | [e63bc464f2](https://bsd-hardware.info/?probe=e63bc464f2) | Dec 05, 2023 |
| MECHREVO      | F7BSC V1.0                  | Mini pc     | [d1104aa676](https://bsd-hardware.info/?probe=d1104aa676) | Dec 05, 2023 |
| ECS           | MCP61M-M3                   | Desktop     | [6d6c04c278](https://bsd-hardware.info/?probe=6d6c04c278) | Dec 05, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [cc4538374c](https://bsd-hardware.info/?probe=cc4538374c) | Dec 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8c023b9c33](https://bsd-hardware.info/?probe=8c023b9c33) | Dec 05, 2023 |
| Wortmann      | TERRA_MOBILE_1541           | Notebook    | [63f1a71855](https://bsd-hardware.info/?probe=63f1a71855) | Dec 04, 2023 |
| Lenovo        | ThinkPad T430s 23532QG      | Notebook    | [b456c01e0f](https://bsd-hardware.info/?probe=b456c01e0f) | Dec 04, 2023 |
| ASUSTek       | X555LB                      | Notebook    | [0df52370a2](https://bsd-hardware.info/?probe=0df52370a2) | Dec 04, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [ea8b5e1c14](https://bsd-hardware.info/?probe=ea8b5e1c14) | Dec 03, 2023 |
| Acidanther... | MacBookPro16,3              | Notebook    | [322ea11f6c](https://bsd-hardware.info/?probe=322ea11f6c) | Dec 03, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [a13be946a5](https://bsd-hardware.info/?probe=a13be946a5) | Dec 03, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [4f5b576aff](https://bsd-hardware.info/?probe=4f5b576aff) | Dec 03, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [34db2bdd7d](https://bsd-hardware.info/?probe=34db2bdd7d) | Dec 03, 2023 |
| Lenovo        | ThinkPad X280 20KES5M300    | Notebook    | [28d67ab74a](https://bsd-hardware.info/?probe=28d67ab74a) | Dec 02, 2023 |
| ASUSTek       | X555LB                      | Notebook    | [e96bb84b37](https://bsd-hardware.info/?probe=e96bb84b37) | Dec 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a9b3beae66](https://bsd-hardware.info/?probe=a9b3beae66) | Dec 02, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [0457bab107](https://bsd-hardware.info/?probe=0457bab107) | Dec 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [f1cb9a41ba](https://bsd-hardware.info/?probe=f1cb9a41ba) | Nov 30, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [ae4c6d7097](https://bsd-hardware.info/?probe=ae4c6d7097) | Nov 29, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [4017ce5221](https://bsd-hardware.info/?probe=4017ce5221) | Nov 29, 2023 |
| CNCTION-IA... | Unknown                     | Desktop     | [1b4871792b](https://bsd-hardware.info/?probe=1b4871792b) | Nov 28, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [8d7c03be2f](https://bsd-hardware.info/?probe=8d7c03be2f) | Nov 28, 2023 |
| Dell          | Precision 5510              | Notebook    | [3a7b2ae214](https://bsd-hardware.info/?probe=3a7b2ae214) | Nov 28, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [806a29d40a](https://bsd-hardware.info/?probe=806a29d40a) | Nov 28, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [b32ded6bb9](https://bsd-hardware.info/?probe=b32ded6bb9) | Nov 27, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [c9f6264329](https://bsd-hardware.info/?probe=c9f6264329) | Nov 27, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [1e9f19c4ae](https://bsd-hardware.info/?probe=1e9f19c4ae) | Nov 27, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [3b18ff26c0](https://bsd-hardware.info/?probe=3b18ff26c0) | Nov 27, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [42bddda351](https://bsd-hardware.info/?probe=42bddda351) | Nov 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [55339dbfab](https://bsd-hardware.info/?probe=55339dbfab) | Nov 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b653e75063](https://bsd-hardware.info/?probe=b653e75063) | Nov 26, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1454187842](https://bsd-hardware.info/?probe=1454187842) | Nov 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [28f6ec2a7b](https://bsd-hardware.info/?probe=28f6ec2a7b) | Nov 26, 2023 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | Notebook    | [3517ce2745](https://bsd-hardware.info/?probe=3517ce2745) | Nov 26, 2023 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | Notebook    | [5f336b9d93](https://bsd-hardware.info/?probe=5f336b9d93) | Nov 26, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [f2aa7b3ebf](https://bsd-hardware.info/?probe=f2aa7b3ebf) | Nov 25, 2023 |
| Dell          | Latitude 5480               | Notebook    | [639ffb1573](https://bsd-hardware.info/?probe=639ffb1573) | Nov 25, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [24f4b0ec7e](https://bsd-hardware.info/?probe=24f4b0ec7e) | Nov 24, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [e0d8200dfa](https://bsd-hardware.info/?probe=e0d8200dfa) | Nov 24, 2023 |
| Google        | Dragonair                   | Notebook    | [713cf1bc38](https://bsd-hardware.info/?probe=713cf1bc38) | Nov 24, 2023 |
| HP            | Notebook                    | Notebook    | [aff6430eb2](https://bsd-hardware.info/?probe=aff6430eb2) | Nov 24, 2023 |
| Silicom       | 80300-0214-G16 R310         | Desktop     | [34382c8f4b](https://bsd-hardware.info/?probe=34382c8f4b) | Nov 24, 2023 |
| Acer          | JM11-MS                     | Notebook    | [0490895189](https://bsd-hardware.info/?probe=0490895189) | Nov 23, 2023 |
| Acidanther... | MacBookPro16,3              | Notebook    | [5f89fa2cd2](https://bsd-hardware.info/?probe=5f89fa2cd2) | Nov 22, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [4c80855e88](https://bsd-hardware.info/?probe=4c80855e88) | Nov 22, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [a37a33268d](https://bsd-hardware.info/?probe=a37a33268d) | Nov 21, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [fb283e956a](https://bsd-hardware.info/?probe=fb283e956a) | Nov 21, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4b6284d041](https://bsd-hardware.info/?probe=4b6284d041) | Nov 20, 2023 |
| PICO PC       | MNHO-113                    | Desktop     | [c9a12372b4](https://bsd-hardware.info/?probe=c9a12372b4) | Nov 20, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [96562d6513](https://bsd-hardware.info/?probe=96562d6513) | Nov 20, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [fdb7c00df7](https://bsd-hardware.info/?probe=fdb7c00df7) | Nov 20, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [5caaad73bd](https://bsd-hardware.info/?probe=5caaad73bd) | Nov 19, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [17d29b1055](https://bsd-hardware.info/?probe=17d29b1055) | Nov 19, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6406980bbf](https://bsd-hardware.info/?probe=6406980bbf) | Nov 19, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [e7ccb4156e](https://bsd-hardware.info/?probe=e7ccb4156e) | Nov 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a570c7994c](https://bsd-hardware.info/?probe=a570c7994c) | Nov 19, 2023 |
| Lenovo        | ThinkPad W530 24411M9       | Notebook    | [0272396725](https://bsd-hardware.info/?probe=0272396725) | Nov 19, 2023 |
| MSI           | B560-A PRO                  | Desktop     | [cf9b5a14ce](https://bsd-hardware.info/?probe=cf9b5a14ce) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [2c33e6e9e7](https://bsd-hardware.info/?probe=2c33e6e9e7) | Nov 19, 2023 |
| Dell          | Latitude 5440               | Notebook    | [9daa44aacf](https://bsd-hardware.info/?probe=9daa44aacf) | Nov 18, 2023 |
| Panasonic     | CF-31-5                     | Notebook    | [8771ab6139](https://bsd-hardware.info/?probe=8771ab6139) | Nov 18, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [9eab94b4f7](https://bsd-hardware.info/?probe=9eab94b4f7) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [cfbda53125](https://bsd-hardware.info/?probe=cfbda53125) | Nov 18, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [9061ad4228](https://bsd-hardware.info/?probe=9061ad4228) | Nov 17, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [ece5171a1d](https://bsd-hardware.info/?probe=ece5171a1d) | Nov 17, 2023 |
| HP            | Notebook                    | Notebook    | [5d2df329aa](https://bsd-hardware.info/?probe=5d2df329aa) | Nov 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [918706e110](https://bsd-hardware.info/?probe=918706e110) | Nov 15, 2023 |
| Supermicro    | H8DGU                       | Server      | [aa3a09d113](https://bsd-hardware.info/?probe=aa3a09d113) | Nov 15, 2023 |
| Supermicro    | H8DGU                       | Server      | [5ca736990f](https://bsd-hardware.info/?probe=5ca736990f) | Nov 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0e4ea9ccbf](https://bsd-hardware.info/?probe=0e4ea9ccbf) | Nov 15, 2023 |
| Dell          | G5 5505                     | Notebook    | [088aea32c0](https://bsd-hardware.info/?probe=088aea32c0) | Nov 15, 2023 |
| HP            | 18E7                        | Desktop     | [3cbe1117fa](https://bsd-hardware.info/?probe=3cbe1117fa) | Nov 14, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [2487233a5d](https://bsd-hardware.info/?probe=2487233a5d) | Nov 13, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [ee4c8ddddc](https://bsd-hardware.info/?probe=ee4c8ddddc) | Nov 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [771c13f8ea](https://bsd-hardware.info/?probe=771c13f8ea) | Nov 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [35ae423f7a](https://bsd-hardware.info/?probe=35ae423f7a) | Nov 13, 2023 |
| MSI           | H81M-P33                    | Desktop     | [a062354358](https://bsd-hardware.info/?probe=a062354358) | Nov 12, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [0869172a54](https://bsd-hardware.info/?probe=0869172a54) | Nov 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b1e348523f](https://bsd-hardware.info/?probe=b1e348523f) | Nov 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f32f8bdf95](https://bsd-hardware.info/?probe=f32f8bdf95) | Nov 12, 2023 |
| OnLogic       | HX401                       | Notebook    | [b000c6d264](https://bsd-hardware.info/?probe=b000c6d264) | Nov 12, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [8d4f2c439a](https://bsd-hardware.info/?probe=8d4f2c439a) | Nov 11, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [3ce8e78453](https://bsd-hardware.info/?probe=3ce8e78453) | Nov 11, 2023 |
| Lenovo        | ThinkPad X270 20HN006CUS    | Notebook    | [dc8d596ea1](https://bsd-hardware.info/?probe=dc8d596ea1) | Nov 11, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [823bdd1b43](https://bsd-hardware.info/?probe=823bdd1b43) | Nov 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [c535fae89f](https://bsd-hardware.info/?probe=c535fae89f) | Nov 10, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [81e93afe2e](https://bsd-hardware.info/?probe=81e93afe2e) | Nov 10, 2023 |
| ASRock        | B460M Steel Legend          | Desktop     | [13bdfc626b](https://bsd-hardware.info/?probe=13bdfc626b) | Nov 09, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [3c3b2abb3d](https://bsd-hardware.info/?probe=3c3b2abb3d) | Nov 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP00    | Notebook    | [5eb914094b](https://bsd-hardware.info/?probe=5eb914094b) | Nov 09, 2023 |
| Dell          | Precision 7560              | Notebook    | [a0e5297849](https://bsd-hardware.info/?probe=a0e5297849) | Nov 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b7b9df03f3](https://bsd-hardware.info/?probe=b7b9df03f3) | Nov 09, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [9d4170e2d2](https://bsd-hardware.info/?probe=9d4170e2d2) | Nov 08, 2023 |
| Samsung       | 740U5M                      | Convertible | [1a996f2f48](https://bsd-hardware.info/?probe=1a996f2f48) | Nov 08, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [6588258570](https://bsd-hardware.info/?probe=6588258570) | Nov 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [61c7e94f23](https://bsd-hardware.info/?probe=61c7e94f23) | Nov 06, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [36a87f24f7](https://bsd-hardware.info/?probe=36a87f24f7) | Nov 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [316be7bb33](https://bsd-hardware.info/?probe=316be7bb33) | Nov 06, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a26912fd0d](https://bsd-hardware.info/?probe=a26912fd0d) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e8c7d22b1f](https://bsd-hardware.info/?probe=e8c7d22b1f) | Nov 05, 2023 |
| ZOTAC         | ZBOX-CI320NANO series Re... | Mini pc     | [9de790eac0](https://bsd-hardware.info/?probe=9de790eac0) | Nov 05, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [7d6d03a42b](https://bsd-hardware.info/?probe=7d6d03a42b) | Nov 05, 2023 |
| Dell          | 0MD99X A12                  | Server      | [c137d2d6da](https://bsd-hardware.info/?probe=c137d2d6da) | Nov 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [d44c30f985](https://bsd-hardware.info/?probe=d44c30f985) | Nov 05, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [dac3ca2eca](https://bsd-hardware.info/?probe=dac3ca2eca) | Nov 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e744712416](https://bsd-hardware.info/?probe=e744712416) | Nov 05, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [a8aad4a386](https://bsd-hardware.info/?probe=a8aad4a386) | Nov 04, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [c7d016caa9](https://bsd-hardware.info/?probe=c7d016caa9) | Nov 04, 2023 |
| LG Electro... | 16UD70R-G.AX59B             | Notebook    | [a7df4f645f](https://bsd-hardware.info/?probe=a7df4f645f) | Nov 04, 2023 |
| Dell          | 0Y2V0C A03                  | Desktop     | [5c7de92bb3](https://bsd-hardware.info/?probe=5c7de92bb3) | Nov 03, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [538444f1d2](https://bsd-hardware.info/?probe=538444f1d2) | Nov 02, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [2fab5b5adf](https://bsd-hardware.info/?probe=2fab5b5adf) | Nov 01, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [03fa12a885](https://bsd-hardware.info/?probe=03fa12a885) | Nov 01, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [f93d5865b8](https://bsd-hardware.info/?probe=f93d5865b8) | Nov 01, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [91d07ef080](https://bsd-hardware.info/?probe=91d07ef080) | Nov 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [1a63df656e](https://bsd-hardware.info/?probe=1a63df656e) | Oct 31, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [87e3260963](https://bsd-hardware.info/?probe=87e3260963) | Oct 31, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [c60aeb219e](https://bsd-hardware.info/?probe=c60aeb219e) | Oct 31, 2023 |
| Lenovo        | ThinkPad T480 20L5000WUS    | Notebook    | [4dcf84c76c](https://bsd-hardware.info/?probe=4dcf84c76c) | Oct 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c163891517](https://bsd-hardware.info/?probe=c163891517) | Oct 31, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [ebdc124789](https://bsd-hardware.info/?probe=ebdc124789) | Oct 30, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [c7e5f79b34](https://bsd-hardware.info/?probe=c7e5f79b34) | Oct 30, 2023 |
| Intel         | DCP847SKE                   | Desktop     | [ba44d23972](https://bsd-hardware.info/?probe=ba44d23972) | Oct 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [1f6542c47d](https://bsd-hardware.info/?probe=1f6542c47d) | Oct 29, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [49d23c8fda](https://bsd-hardware.info/?probe=49d23c8fda) | Oct 28, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [a133633304](https://bsd-hardware.info/?probe=a133633304) | Oct 28, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [09cf753c7a](https://bsd-hardware.info/?probe=09cf753c7a) | Oct 26, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [1b42e4a912](https://bsd-hardware.info/?probe=1b42e4a912) | Oct 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b3f2cf24c](https://bsd-hardware.info/?probe=6b3f2cf24c) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [8e245ccb85](https://bsd-hardware.info/?probe=8e245ccb85) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [db96ffb93a](https://bsd-hardware.info/?probe=db96ffb93a) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [06f91445cb](https://bsd-hardware.info/?probe=06f91445cb) | Oct 24, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [e2dad0b43a](https://bsd-hardware.info/?probe=e2dad0b43a) | Oct 24, 2023 |
| Lenovo        | ThinkPad T490 20N3X50500    | Notebook    | [364c7828be](https://bsd-hardware.info/?probe=364c7828be) | Oct 24, 2023 |
| Shuttle       | FZ270                       | Desktop     | [1aa4ad0971](https://bsd-hardware.info/?probe=1aa4ad0971) | Oct 23, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [ab44e043d2](https://bsd-hardware.info/?probe=ab44e043d2) | Oct 23, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [8f62c35aa0](https://bsd-hardware.info/?probe=8f62c35aa0) | Oct 23, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [1f76a6c28c](https://bsd-hardware.info/?probe=1f76a6c28c) | Oct 22, 2023 |
| MSI           | H81M-P33                    | Desktop     | [dd9ff802a9](https://bsd-hardware.info/?probe=dd9ff802a9) | Oct 22, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1b94fd9385](https://bsd-hardware.info/?probe=1b94fd9385) | Oct 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [cc7fb797f5](https://bsd-hardware.info/?probe=cc7fb797f5) | Oct 22, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [6569410f91](https://bsd-hardware.info/?probe=6569410f91) | Oct 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [7a57e0a112](https://bsd-hardware.info/?probe=7a57e0a112) | Oct 21, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [5a7e4222f1](https://bsd-hardware.info/?probe=5a7e4222f1) | Oct 21, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [7148ec01b2](https://bsd-hardware.info/?probe=7148ec01b2) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [629eefe0c2](https://bsd-hardware.info/?probe=629eefe0c2) | Oct 21, 2023 |
| Dell          | G16 7630                    | Notebook    | [deb5f3bd32](https://bsd-hardware.info/?probe=deb5f3bd32) | Oct 21, 2023 |
| ASUSTek       | PRIME H470M-PLUS            | Desktop     | [88cdd6135f](https://bsd-hardware.info/?probe=88cdd6135f) | Oct 20, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [a8727c3ee3](https://bsd-hardware.info/?probe=a8727c3ee3) | Oct 19, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1cc822b8c1](https://bsd-hardware.info/?probe=1cc822b8c1) | Oct 19, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [606ed441ae](https://bsd-hardware.info/?probe=606ed441ae) | Oct 19, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [0f914c6351](https://bsd-hardware.info/?probe=0f914c6351) | Oct 17, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [b08dc9fc91](https://bsd-hardware.info/?probe=b08dc9fc91) | Oct 16, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6902d492db](https://bsd-hardware.info/?probe=6902d492db) | Oct 15, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [094b766a05](https://bsd-hardware.info/?probe=094b766a05) | Oct 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b502116394](https://bsd-hardware.info/?probe=b502116394) | Oct 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [0f3cd5aa25](https://bsd-hardware.info/?probe=0f3cd5aa25) | Oct 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [697f24cf01](https://bsd-hardware.info/?probe=697f24cf01) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [d14ff47394](https://bsd-hardware.info/?probe=d14ff47394) | Oct 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [0fd1a7196f](https://bsd-hardware.info/?probe=0fd1a7196f) | Oct 13, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [a7307b8de1](https://bsd-hardware.info/?probe=a7307b8de1) | Oct 12, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [6dfadd1ff2](https://bsd-hardware.info/?probe=6dfadd1ff2) | Oct 11, 2023 |
| Dell          | Precision 7550              | Notebook    | [a21e06c16c](https://bsd-hardware.info/?probe=a21e06c16c) | Oct 11, 2023 |
| ANGXUN        | X79-VG2 V1.3                | Desktop     | [c823cbad48](https://bsd-hardware.info/?probe=c823cbad48) | Oct 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [9c6c7f9d6b](https://bsd-hardware.info/?probe=9c6c7f9d6b) | Oct 10, 2023 |
| Dell          | Inspiron 13 5320            | Notebook    | [43c1b405d0](https://bsd-hardware.info/?probe=43c1b405d0) | Oct 09, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [f55c557bcf](https://bsd-hardware.info/?probe=f55c557bcf) | Oct 09, 2023 |
| EVGA          | X299 MICRO                  | Desktop     | [2907f2166d](https://bsd-hardware.info/?probe=2907f2166d) | Oct 09, 2023 |
| MSI           | H81M-P33                    | Desktop     | [a9729ebc38](https://bsd-hardware.info/?probe=a9729ebc38) | Oct 08, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [06a76899d6](https://bsd-hardware.info/?probe=06a76899d6) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [cacbb83f98](https://bsd-hardware.info/?probe=cacbb83f98) | Oct 08, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | Notebook    | [0aac5f52c9](https://bsd-hardware.info/?probe=0aac5f52c9) | Oct 08, 2023 |
| MSI           | Aspen                       | Desktop     | [7bb665508f](https://bsd-hardware.info/?probe=7bb665508f) | Oct 07, 2023 |
| GVC           | DR 738                      | Desktop     | [1aa25f04a8](https://bsd-hardware.info/?probe=1aa25f04a8) | Oct 07, 2023 |
| Timi          | A34R                        | Notebook    | [3cd3f35eaa](https://bsd-hardware.info/?probe=3cd3f35eaa) | Oct 07, 2023 |
| Timi          | A34R                        | Notebook    | [03f00603f7](https://bsd-hardware.info/?probe=03f00603f7) | Oct 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b3580a1e53](https://bsd-hardware.info/?probe=b3580a1e53) | Oct 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [9d236eb8bb](https://bsd-hardware.info/?probe=9d236eb8bb) | Oct 06, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [85e94bd511](https://bsd-hardware.info/?probe=85e94bd511) | Oct 06, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [3f63740c0e](https://bsd-hardware.info/?probe=3f63740c0e) | Oct 05, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [88e8c64b6f](https://bsd-hardware.info/?probe=88e8c64b6f) | Oct 04, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [aecfeaa518](https://bsd-hardware.info/?probe=aecfeaa518) | Oct 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [9ad768a37a](https://bsd-hardware.info/?probe=9ad768a37a) | Oct 04, 2023 |
| Lenovo        | ThinkPad X230 2325J67       | Notebook    | [bfbc6beca8](https://bsd-hardware.info/?probe=bfbc6beca8) | Oct 04, 2023 |
| ASUSTek       | Pro WS W680-ACE IPMI        | Desktop     | [6a98aea3f9](https://bsd-hardware.info/?probe=6a98aea3f9) | Oct 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [25fecdaad5](https://bsd-hardware.info/?probe=25fecdaad5) | Oct 03, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [4e12d36770](https://bsd-hardware.info/?probe=4e12d36770) | Oct 03, 2023 |
| Lenovo        | B40-30 80F1                 | Notebook    | [00c5e6adda](https://bsd-hardware.info/?probe=00c5e6adda) | Oct 03, 2023 |
| Platform      | ARB938                      | Notebook    | [141d043221](https://bsd-hardware.info/?probe=141d043221) | Oct 02, 2023 |
| Google        | Auron_Paine                 | Notebook    | [d202b4dd6f](https://bsd-hardware.info/?probe=d202b4dd6f) | Oct 02, 2023 |
| Google        | Auron_Paine                 | Notebook    | [1c44cf70e8](https://bsd-hardware.info/?probe=1c44cf70e8) | Oct 02, 2023 |
| Intel         | NUC8BEB J72692-307          | Mini pc     | [e43673f564](https://bsd-hardware.info/?probe=e43673f564) | Oct 01, 2023 |
| Google        | Auron_Paine                 | Notebook    | [021624028a](https://bsd-hardware.info/?probe=021624028a) | Oct 01, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [7a6b97e997](https://bsd-hardware.info/?probe=7a6b97e997) | Oct 01, 2023 |
| MSI           | H81M-P33                    | Desktop     | [da12fe3c05](https://bsd-hardware.info/?probe=da12fe3c05) | Oct 01, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [6975204e47](https://bsd-hardware.info/?probe=6975204e47) | Oct 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [c6903de57a](https://bsd-hardware.info/?probe=c6903de57a) | Sep 30, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [31da8655d1](https://bsd-hardware.info/?probe=31da8655d1) | Sep 28, 2023 |
| Dell          | 0J555H A00                  | Server      | [3c395551d4](https://bsd-hardware.info/?probe=3c395551d4) | Sep 28, 2023 |
| Supermicro    | M11SDV-8C+-LN4F             | Server      | [c35034519a](https://bsd-hardware.info/?probe=c35034519a) | Sep 28, 2023 |
| Biostar       | A55MLC2                     | Desktop     | [fac0f247d0](https://bsd-hardware.info/?probe=fac0f247d0) | Sep 28, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [0c56aeb6b5](https://bsd-hardware.info/?probe=0c56aeb6b5) | Sep 27, 2023 |
| ASUSTek       | P9D-MV Series               | Server      | [0a035e25a9](https://bsd-hardware.info/?probe=0a035e25a9) | Sep 26, 2023 |
| Dell          | 07T4MC A09                  | Desktop     | [bde8cc45df](https://bsd-hardware.info/?probe=bde8cc45df) | Sep 26, 2023 |
| Dell          | 07T4MC A09                  | Desktop     | [0ce8f84155](https://bsd-hardware.info/?probe=0ce8f84155) | Sep 26, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [231aedbf9e](https://bsd-hardware.info/?probe=231aedbf9e) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [1ba135fef1](https://bsd-hardware.info/?probe=1ba135fef1) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9c8516c8a8](https://bsd-hardware.info/?probe=9c8516c8a8) | Sep 24, 2023 |
| Dell          | Latitude 3410               | Notebook    | [1bd71b0bf0](https://bsd-hardware.info/?probe=1bd71b0bf0) | Sep 24, 2023 |
| MSI           | H81M-P33                    | Desktop     | [971f3fdba1](https://bsd-hardware.info/?probe=971f3fdba1) | Sep 24, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [6538212bd6](https://bsd-hardware.info/?probe=6538212bd6) | Sep 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f7aee1db53](https://bsd-hardware.info/?probe=f7aee1db53) | Sep 24, 2023 |
| AZW           | SEi V1.0                    | Desktop     | [1d0307b36d](https://bsd-hardware.info/?probe=1d0307b36d) | Sep 23, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [de1bdf0601](https://bsd-hardware.info/?probe=de1bdf0601) | Sep 21, 2023 |
| Dell          | G16 7630                    | Notebook    | [4e39a5ebdf](https://bsd-hardware.info/?probe=4e39a5ebdf) | Sep 21, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [f29233649e](https://bsd-hardware.info/?probe=f29233649e) | Sep 20, 2023 |
| Lenovo        | ThinkPad L390 20NRS00Q00    | Notebook    | [b9885ea126](https://bsd-hardware.info/?probe=b9885ea126) | Sep 17, 2023 |
| ASUSTek       | PRIME B550M-A (WI-FI)       | Desktop     | [ab77dcfd74](https://bsd-hardware.info/?probe=ab77dcfd74) | Sep 15, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6fc18e3db7](https://bsd-hardware.info/?probe=6fc18e3db7) | Sep 15, 2023 |
| Lenovo        | ThinkPad T480s 20L7S24F0... | Notebook    | [bb7eb8b380](https://bsd-hardware.info/?probe=bb7eb8b380) | Sep 15, 2023 |
| Platform      | ARB938                      | Notebook    | [17b7c850c4](https://bsd-hardware.info/?probe=17b7c850c4) | Sep 14, 2023 |
| Alienware     | m15                         | Notebook    | [609d2ce1ce](https://bsd-hardware.info/?probe=609d2ce1ce) | Sep 14, 2023 |
| HP            | Pavilion dv5                | Notebook    | [b7dad77d0d](https://bsd-hardware.info/?probe=b7dad77d0d) | Sep 14, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [03a8809fe4](https://bsd-hardware.info/?probe=03a8809fe4) | Sep 13, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [67d1f42d7c](https://bsd-hardware.info/?probe=67d1f42d7c) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [7ba189ff8a](https://bsd-hardware.info/?probe=7ba189ff8a) | Sep 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5dee3a945f](https://bsd-hardware.info/?probe=5dee3a945f) | Sep 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [9fee6e83fc](https://bsd-hardware.info/?probe=9fee6e83fc) | Sep 13, 2023 |
| HP            | 212B                        | Desktop     | [3370718b29](https://bsd-hardware.info/?probe=3370718b29) | Sep 13, 2023 |
| HP            | ProBook 4530s               | Notebook    | [0b47c15c42](https://bsd-hardware.info/?probe=0b47c15c42) | Sep 12, 2023 |
| HP            | ProBook 4530s               | Notebook    | [4b6daa1f1c](https://bsd-hardware.info/?probe=4b6daa1f1c) | Sep 12, 2023 |
| ASUSTek       | PRIME B550M-A (WI-FI)       | Desktop     | [78bc36f5a9](https://bsd-hardware.info/?probe=78bc36f5a9) | Sep 11, 2023 |
| Dell          | BlackfordESB2               | Server      | [36b37267be](https://bsd-hardware.info/?probe=36b37267be) | Sep 11, 2023 |
| HP            | Mini 110-3100               | Notebook    | [14f75b6704](https://bsd-hardware.info/?probe=14f75b6704) | Sep 11, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [095b8aa8fb](https://bsd-hardware.info/?probe=095b8aa8fb) | Sep 11, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [e2d694053a](https://bsd-hardware.info/?probe=e2d694053a) | Sep 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [57a847859f](https://bsd-hardware.info/?probe=57a847859f) | Sep 10, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b7e0d87f47](https://bsd-hardware.info/?probe=b7e0d87f47) | Sep 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c2378b3e83](https://bsd-hardware.info/?probe=c2378b3e83) | Sep 10, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3LR0... | Notebook    | [cbac96a24f](https://bsd-hardware.info/?probe=cbac96a24f) | Sep 09, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [6be22d7887](https://bsd-hardware.info/?probe=6be22d7887) | Sep 09, 2023 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [7947ecdca3](https://bsd-hardware.info/?probe=7947ecdca3) | Sep 08, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [d331bd9a11](https://bsd-hardware.info/?probe=d331bd9a11) | Sep 08, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [d9d6fc45f8](https://bsd-hardware.info/?probe=d9d6fc45f8) | Sep 08, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [24e745026c](https://bsd-hardware.info/?probe=24e745026c) | Sep 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [29578638c1](https://bsd-hardware.info/?probe=29578638c1) | Sep 08, 2023 |
| HP            | 8158 A01                    | Mini pc     | [ae22c1bea5](https://bsd-hardware.info/?probe=ae22c1bea5) | Sep 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [cbde759aa2](https://bsd-hardware.info/?probe=cbde759aa2) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [22ec8197cc](https://bsd-hardware.info/?probe=22ec8197cc) | Sep 07, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e011df1d78](https://bsd-hardware.info/?probe=e011df1d78) | Sep 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [516b89740b](https://bsd-hardware.info/?probe=516b89740b) | Sep 06, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [40b4e58c88](https://bsd-hardware.info/?probe=40b4e58c88) | Sep 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [0b7d85b124](https://bsd-hardware.info/?probe=0b7d85b124) | Sep 06, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [67e9eafa7e](https://bsd-hardware.info/?probe=67e9eafa7e) | Sep 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [50f509c032](https://bsd-hardware.info/?probe=50f509c032) | Sep 05, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [cfecf51114](https://bsd-hardware.info/?probe=cfecf51114) | Sep 04, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [1bde5a65b6](https://bsd-hardware.info/?probe=1bde5a65b6) | Sep 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [e4f0ac6bb9](https://bsd-hardware.info/?probe=e4f0ac6bb9) | Sep 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [4bce25bd89](https://bsd-hardware.info/?probe=4bce25bd89) | Sep 03, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [d240fba8b7](https://bsd-hardware.info/?probe=d240fba8b7) | Sep 03, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b47290007a](https://bsd-hardware.info/?probe=b47290007a) | Sep 03, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [ef4604a40f](https://bsd-hardware.info/?probe=ef4604a40f) | Sep 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8d37c44440](https://bsd-hardware.info/?probe=8d37c44440) | Sep 03, 2023 |
| AAEON         | FWS-2363 V1.0               | Desktop     | [098bc5466b](https://bsd-hardware.info/?probe=098bc5466b) | Sep 03, 2023 |
| Shuttle       | DS20U                       | Desktop     | [d034a8e5b8](https://bsd-hardware.info/?probe=d034a8e5b8) | Sep 02, 2023 |
| Intel         | HM570                       | Desktop     | [de018603ae](https://bsd-hardware.info/?probe=de018603ae) | Sep 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [1bfe26df6e](https://bsd-hardware.info/?probe=1bfe26df6e) | Sep 02, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [82ac08abc0](https://bsd-hardware.info/?probe=82ac08abc0) | Aug 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [0ebdda5146](https://bsd-hardware.info/?probe=0ebdda5146) | Aug 31, 2023 |
| HP            | 802F                        | Desktop     | [1f64f7e11f](https://bsd-hardware.info/?probe=1f64f7e11f) | Aug 30, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [b83ebfd33b](https://bsd-hardware.info/?probe=b83ebfd33b) | Aug 29, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [0dda7a609c](https://bsd-hardware.info/?probe=0dda7a609c) | Aug 29, 2023 |
| Nvidia        | MCP79                       | Desktop     | [0897b3a117](https://bsd-hardware.info/?probe=0897b3a117) | Aug 29, 2023 |
| Supermicro    | X9DRD-iF                    | Desktop     | [be36f2fe2b](https://bsd-hardware.info/?probe=be36f2fe2b) | Aug 28, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [f0fb53394d](https://bsd-hardware.info/?probe=f0fb53394d) | Aug 28, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [dc8ad6c7c5](https://bsd-hardware.info/?probe=dc8ad6c7c5) | Aug 28, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [c8c17a9db2](https://bsd-hardware.info/?probe=c8c17a9db2) | Aug 28, 2023 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [df915d5ab9](https://bsd-hardware.info/?probe=df915d5ab9) | Aug 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [2e9a066a01](https://bsd-hardware.info/?probe=2e9a066a01) | Aug 27, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [9898ae1ead](https://bsd-hardware.info/?probe=9898ae1ead) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [0bb56ff672](https://bsd-hardware.info/?probe=0bb56ff672) | Aug 27, 2023 |
| Dell          | G5 5590                     | Notebook    | [2e496efada](https://bsd-hardware.info/?probe=2e496efada) | Aug 26, 2023 |
| Dell          | G5 5590                     | Notebook    | [fd4f457391](https://bsd-hardware.info/?probe=fd4f457391) | Aug 26, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [4d51e18ce4](https://bsd-hardware.info/?probe=4d51e18ce4) | Aug 25, 2023 |
| Supermicro    | X10DRi-LN4+                 | Server      | [4978b62b97](https://bsd-hardware.info/?probe=4978b62b97) | Aug 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f1a43ebe23](https://bsd-hardware.info/?probe=f1a43ebe23) | Aug 24, 2023 |
| MSI           | G31M3-L V2                  | Desktop     | [7335b3dea2](https://bsd-hardware.info/?probe=7335b3dea2) | Aug 22, 2023 |
| Dell          | 068CDY A01                  | Server      | [c3e69db640](https://bsd-hardware.info/?probe=c3e69db640) | Aug 22, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [0d69491bdd](https://bsd-hardware.info/?probe=0d69491bdd) | Aug 21, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [913cc77381](https://bsd-hardware.info/?probe=913cc77381) | Aug 21, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [3ac93594a2](https://bsd-hardware.info/?probe=3ac93594a2) | Aug 20, 2023 |
| Lenovo        | ThinkCentre M90p 3853RN9    | Desktop     | [818c1b5f31](https://bsd-hardware.info/?probe=818c1b5f31) | Aug 20, 2023 |
| Shuttle       | DS20U                       | Desktop     | [5c511e0613](https://bsd-hardware.info/?probe=5c511e0613) | Aug 20, 2023 |
| AZW           | SER                         | Mini pc     | [db297e2cda](https://bsd-hardware.info/?probe=db297e2cda) | Aug 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0UD0... | Notebook    | [3c3610a93f](https://bsd-hardware.info/?probe=3c3610a93f) | Aug 19, 2023 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [0238ea2cab](https://bsd-hardware.info/?probe=0238ea2cab) | Aug 19, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [301a7c7b63](https://bsd-hardware.info/?probe=301a7c7b63) | Aug 19, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [3b430afdad](https://bsd-hardware.info/?probe=3b430afdad) | Aug 18, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [66449212d1](https://bsd-hardware.info/?probe=66449212d1) | Aug 18, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [434ec73823](https://bsd-hardware.info/?probe=434ec73823) | Aug 18, 2023 |
| Dell          | Latitude 3420               | Notebook    | [0e171f3f87](https://bsd-hardware.info/?probe=0e171f3f87) | Aug 18, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | Desktop     | [9e92903663](https://bsd-hardware.info/?probe=9e92903663) | Aug 18, 2023 |
| MSI           | MS-7721                     | Desktop     | [678c81c8c1](https://bsd-hardware.info/?probe=678c81c8c1) | Aug 18, 2023 |
| Dell          | 05FT2M A04                  | Server      | [73afce6eeb](https://bsd-hardware.info/?probe=73afce6eeb) | Aug 17, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [7aa7ba9ea9](https://bsd-hardware.info/?probe=7aa7ba9ea9) | Aug 17, 2023 |
| Supermicro    | M12SWA-TF                   | Desktop     | [2e38f0b91a](https://bsd-hardware.info/?probe=2e38f0b91a) | Aug 16, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [9a8ad54cd3](https://bsd-hardware.info/?probe=9a8ad54cd3) | Aug 16, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [fc152ce8d4](https://bsd-hardware.info/?probe=fc152ce8d4) | Aug 16, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [be7bd4b126](https://bsd-hardware.info/?probe=be7bd4b126) | Aug 15, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [cc946b2a89](https://bsd-hardware.info/?probe=cc946b2a89) | Aug 15, 2023 |
| Lenovo        | ThinkPad T460p 20FXS06A1... | Notebook    | [378d093019](https://bsd-hardware.info/?probe=378d093019) | Aug 15, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [664ee85747](https://bsd-hardware.info/?probe=664ee85747) | Aug 15, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2529ce32a7](https://bsd-hardware.info/?probe=2529ce32a7) | Aug 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [80fbf43a6c](https://bsd-hardware.info/?probe=80fbf43a6c) | Aug 13, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [fbb75a1ace](https://bsd-hardware.info/?probe=fbb75a1ace) | Aug 13, 2023 |
| MSI           | H81M-P33                    | Desktop     | [c7b0e4ca6c](https://bsd-hardware.info/?probe=c7b0e4ca6c) | Aug 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [245d908d1a](https://bsd-hardware.info/?probe=245d908d1a) | Aug 13, 2023 |
| MSI           | Modern 14 B11SBL            | Notebook    | [1e02b41824](https://bsd-hardware.info/?probe=1e02b41824) | Aug 12, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [46a6b88b33](https://bsd-hardware.info/?probe=46a6b88b33) | Aug 11, 2023 |
| ASUSTek       | 1001P                       | Notebook    | [ac53dba211](https://bsd-hardware.info/?probe=ac53dba211) | Aug 11, 2023 |
| PC Engines    | APU2                        | Desktop     | [2e9106fc92](https://bsd-hardware.info/?probe=2e9106fc92) | Aug 11, 2023 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [7b00ddd0a1](https://bsd-hardware.info/?probe=7b00ddd0a1) | Aug 11, 2023 |
| PC Engines    | apu1                        | Desktop     | [0b3594d9a3](https://bsd-hardware.info/?probe=0b3594d9a3) | Aug 11, 2023 |
| ASUSTek       | 1001P                       | Notebook    | [2424d8acdc](https://bsd-hardware.info/?probe=2424d8acdc) | Aug 11, 2023 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [65092dde79](https://bsd-hardware.info/?probe=65092dde79) | Aug 09, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [418b98798e](https://bsd-hardware.info/?probe=418b98798e) | Aug 09, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [60d49b408a](https://bsd-hardware.info/?probe=60d49b408a) | Aug 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2f6574d368](https://bsd-hardware.info/?probe=2f6574d368) | Aug 08, 2023 |
| MSI           | Modern 14 B11SBL            | Notebook    | [ba3ab230dc](https://bsd-hardware.info/?probe=ba3ab230dc) | Aug 08, 2023 |
| MSI           | Modern 14 B11SBL            | Notebook    | [48483213f9](https://bsd-hardware.info/?probe=48483213f9) | Aug 06, 2023 |
| Supermicro    | X10DRI-TB                   | Server      | [d4e7a4dde7](https://bsd-hardware.info/?probe=d4e7a4dde7) | Aug 06, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1f7493ada9](https://bsd-hardware.info/?probe=1f7493ada9) | Aug 06, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [46b9ec2e56](https://bsd-hardware.info/?probe=46b9ec2e56) | Aug 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5bd8b552e6](https://bsd-hardware.info/?probe=5bd8b552e6) | Aug 06, 2023 |
| Dell          | Inspiron 14-3467            | Notebook    | [5db7e9b7a1](https://bsd-hardware.info/?probe=5db7e9b7a1) | Aug 05, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [b90e62e27d](https://bsd-hardware.info/?probe=b90e62e27d) | Aug 04, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [4a2c98005b](https://bsd-hardware.info/?probe=4a2c98005b) | Aug 04, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [f809d834df](https://bsd-hardware.info/?probe=f809d834df) | Aug 03, 2023 |
| ASRock        | B550 PG Velocita            | Desktop     | [3ff5fcfbc0](https://bsd-hardware.info/?probe=3ff5fcfbc0) | Aug 02, 2023 |
| HP            | 8298                        | Desktop     | [961bfad69a](https://bsd-hardware.info/?probe=961bfad69a) | Aug 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [be9b9caa66](https://bsd-hardware.info/?probe=be9b9caa66) | Jul 31, 2023 |
| AZW           | SER                         | Mini pc     | [287fdf7e70](https://bsd-hardware.info/?probe=287fdf7e70) | Jul 30, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [09f173d4b6](https://bsd-hardware.info/?probe=09f173d4b6) | Jul 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [9c27c27611](https://bsd-hardware.info/?probe=9c27c27611) | Jul 30, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [a2dbe84ed3](https://bsd-hardware.info/?probe=a2dbe84ed3) | Jul 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [591f8397a9](https://bsd-hardware.info/?probe=591f8397a9) | Jul 30, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [93faaaff91](https://bsd-hardware.info/?probe=93faaaff91) | Jul 30, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [2619fadb11](https://bsd-hardware.info/?probe=2619fadb11) | Jul 29, 2023 |
| ASUSTek       | P8P67                       | Desktop     | [0e10359af8](https://bsd-hardware.info/?probe=0e10359af8) | Jul 29, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [64137e0eec](https://bsd-hardware.info/?probe=64137e0eec) | Jul 29, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [14d1fdc0b1](https://bsd-hardware.info/?probe=14d1fdc0b1) | Jul 24, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [a3624fdcfc](https://bsd-hardware.info/?probe=a3624fdcfc) | Jul 24, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [f54cfd9d27](https://bsd-hardware.info/?probe=f54cfd9d27) | Jul 23, 2023 |
| MSI           | H81M-P33                    | Desktop     | [14b1509851](https://bsd-hardware.info/?probe=14b1509851) | Jul 23, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [7b725a65c4](https://bsd-hardware.info/?probe=7b725a65c4) | Jul 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [877ddd1995](https://bsd-hardware.info/?probe=877ddd1995) | Jul 23, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [f77e9a46c3](https://bsd-hardware.info/?probe=f77e9a46c3) | Jul 22, 2023 |
| HP            | ProBook x360 11 G7 Educa... | Convertible | [22e1b9f0d5](https://bsd-hardware.info/?probe=22e1b9f0d5) | Jul 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [56fc67d3eb](https://bsd-hardware.info/?probe=56fc67d3eb) | Jul 22, 2023 |
| NOBLEX        | SF20BA                      | Notebook    | [a6a17eb5ca](https://bsd-hardware.info/?probe=a6a17eb5ca) | Jul 21, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [9f4f71236e](https://bsd-hardware.info/?probe=9f4f71236e) | Jul 21, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BK0... | Notebook    | [01f4886e09](https://bsd-hardware.info/?probe=01f4886e09) | Jul 21, 2023 |
| HPE           | ProLiant DL360 Gen10        | Server      | [115edf7c58](https://bsd-hardware.info/?probe=115edf7c58) | Jul 20, 2023 |
| Dell          | Precision 5550              | Notebook    | [4c9dd227a7](https://bsd-hardware.info/?probe=4c9dd227a7) | Jul 20, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [ce0f05e871](https://bsd-hardware.info/?probe=ce0f05e871) | Jul 18, 2023 |
| Samsung       | 100NZB                      | Notebook    | [5515e88fc1](https://bsd-hardware.info/?probe=5515e88fc1) | Jul 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [4a82a6a375](https://bsd-hardware.info/?probe=4a82a6a375) | Jul 17, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [ff4dbbacdf](https://bsd-hardware.info/?probe=ff4dbbacdf) | Jul 15, 2023 |
| Intel         | HM570                       | Desktop     | [a9abbf1e12](https://bsd-hardware.info/?probe=a9abbf1e12) | Jul 15, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [12124d8753](https://bsd-hardware.info/?probe=12124d8753) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470s 20HGS3AX0... | Notebook    | [785b9af1f4](https://bsd-hardware.info/?probe=785b9af1f4) | Jul 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [a322b1ee22](https://bsd-hardware.info/?probe=a322b1ee22) | Jul 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [88fae8d98c](https://bsd-hardware.info/?probe=88fae8d98c) | Jul 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1516e2960a](https://bsd-hardware.info/?probe=1516e2960a) | Jul 13, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [91965a9c00](https://bsd-hardware.info/?probe=91965a9c00) | Jul 13, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [bc36695565](https://bsd-hardware.info/?probe=bc36695565) | Jul 13, 2023 |
| Radxa         | rock-pi-n10a                | Desktop     | [a9767501e2](https://bsd-hardware.info/?probe=a9767501e2) | Jul 12, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [08b0409497](https://bsd-hardware.info/?probe=08b0409497) | Jul 12, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [f573d1d5c4](https://bsd-hardware.info/?probe=f573d1d5c4) | Jul 11, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [d0f09cc8c4](https://bsd-hardware.info/?probe=d0f09cc8c4) | Jul 11, 2023 |
| ASRock        | Z690 PG Riptide             | Desktop     | [813e46e924](https://bsd-hardware.info/?probe=813e46e924) | Jul 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [f0de15f4e2](https://bsd-hardware.info/?probe=f0de15f4e2) | Jul 09, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [3bb3ebc39d](https://bsd-hardware.info/?probe=3bb3ebc39d) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [87bb7727a2](https://bsd-hardware.info/?probe=87bb7727a2) | Jul 09, 2023 |
| Getac         | F110G2                      | Notebook    | [b7b9efc38d](https://bsd-hardware.info/?probe=b7b9efc38d) | Jul 09, 2023 |
| Lenovo        | ThinkPad X250 20CLS13Q06    | Notebook    | [c318ab3cc7](https://bsd-hardware.info/?probe=c318ab3cc7) | Jul 09, 2023 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | Notebook    | [80ac9dddda](https://bsd-hardware.info/?probe=80ac9dddda) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [4274ca291e](https://bsd-hardware.info/?probe=4274ca291e) | Jul 08, 2023 |
| HP            | 3397                        | Desktop     | [3d32ba4cd9](https://bsd-hardware.info/?probe=3d32ba4cd9) | Jul 08, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [0f55bad1af](https://bsd-hardware.info/?probe=0f55bad1af) | Jul 08, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [7119cd7ae3](https://bsd-hardware.info/?probe=7119cd7ae3) | Jul 08, 2023 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [e0d3f841c7](https://bsd-hardware.info/?probe=e0d3f841c7) | Jul 07, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [44b85aad5e](https://bsd-hardware.info/?probe=44b85aad5e) | Jul 07, 2023 |
| MSI           | H510I PRO WIFI              | Desktop     | [743d249ba5](https://bsd-hardware.info/?probe=743d249ba5) | Jul 07, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [e36e748937](https://bsd-hardware.info/?probe=e36e748937) | Jul 06, 2023 |
| ASRock        | Z690 PG Riptide             | Desktop     | [364cf5800b](https://bsd-hardware.info/?probe=364cf5800b) | Jul 06, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | Notebook    | [9e3b26b01b](https://bsd-hardware.info/?probe=9e3b26b01b) | Jul 06, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [2519fb81d6](https://bsd-hardware.info/?probe=2519fb81d6) | Jul 05, 2023 |
| HP            | 82F2 A01                    | Desktop     | [a77d73b637](https://bsd-hardware.info/?probe=a77d73b637) | Jul 04, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1HL0... | Notebook    | [f7b57506f0](https://bsd-hardware.info/?probe=f7b57506f0) | Jul 04, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [f74b33bc25](https://bsd-hardware.info/?probe=f74b33bc25) | Jul 03, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [fd5fa70fb7](https://bsd-hardware.info/?probe=fd5fa70fb7) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [e569621be2](https://bsd-hardware.info/?probe=e569621be2) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [553cd9ecae](https://bsd-hardware.info/?probe=553cd9ecae) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | Desktop     | [3c80c960d3](https://bsd-hardware.info/?probe=3c80c960d3) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | Desktop     | [051ddf6f8d](https://bsd-hardware.info/?probe=051ddf6f8d) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [dfdb0bd650](https://bsd-hardware.info/?probe=dfdb0bd650) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [e68bb73773](https://bsd-hardware.info/?probe=e68bb73773) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [3b4a248520](https://bsd-hardware.info/?probe=3b4a248520) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [0a2a221aae](https://bsd-hardware.info/?probe=0a2a221aae) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [7e5ee8de12](https://bsd-hardware.info/?probe=7e5ee8de12) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [3b50a90ebc](https://bsd-hardware.info/?probe=3b50a90ebc) | Jul 03, 2023 |
| Gigabyte      | M85M-US2H                   | Desktop     | [e0a38ef6ad](https://bsd-hardware.info/?probe=e0a38ef6ad) | Jul 03, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [f9f815c60e](https://bsd-hardware.info/?probe=f9f815c60e) | Jul 02, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [39e46fd477](https://bsd-hardware.info/?probe=39e46fd477) | Jul 02, 2023 |
| MSI           | H81M-P33                    | Desktop     | [71edaf952e](https://bsd-hardware.info/?probe=71edaf952e) | Jul 02, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [98254451c1](https://bsd-hardware.info/?probe=98254451c1) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [977d44457e](https://bsd-hardware.info/?probe=977d44457e) | Jul 02, 2023 |
| Dell          | 03KWTV A00                  | Desktop     | [d8f6429e70](https://bsd-hardware.info/?probe=d8f6429e70) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [9f6d45e43e](https://bsd-hardware.info/?probe=9f6d45e43e) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [3eb03fa8a7](https://bsd-hardware.info/?probe=3eb03fa8a7) | Jul 02, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [bf5f6fd6dd](https://bsd-hardware.info/?probe=bf5f6fd6dd) | Jun 30, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [6479d60da2](https://bsd-hardware.info/?probe=6479d60da2) | Jun 30, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [b6cfa09740](https://bsd-hardware.info/?probe=b6cfa09740) | Jun 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [c07f4ffa1e](https://bsd-hardware.info/?probe=c07f4ffa1e) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [1aff07438c](https://bsd-hardware.info/?probe=1aff07438c) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [03c29939fc](https://bsd-hardware.info/?probe=03c29939fc) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [748ae83ba1](https://bsd-hardware.info/?probe=748ae83ba1) | Jun 27, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [4bae8cd192](https://bsd-hardware.info/?probe=4bae8cd192) | Jun 27, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [6823b41760](https://bsd-hardware.info/?probe=6823b41760) | Jun 27, 2023 |
| Dell          | Latitude 3420               | Notebook    | [057f065baa](https://bsd-hardware.info/?probe=057f065baa) | Jun 26, 2023 |
| Lenovo        | ThinkPad T440p 20AW000BU... | Notebook    | [9a7628d17b](https://bsd-hardware.info/?probe=9a7628d17b) | Jun 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [80bd24461a](https://bsd-hardware.info/?probe=80bd24461a) | Jun 25, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [e368d55893](https://bsd-hardware.info/?probe=e368d55893) | Jun 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [483865aca5](https://bsd-hardware.info/?probe=483865aca5) | Jun 25, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [e7dfbf94d0](https://bsd-hardware.info/?probe=e7dfbf94d0) | Jun 25, 2023 |
| HP            | Pavilion g4                 | Notebook    | [ef66b5588a](https://bsd-hardware.info/?probe=ef66b5588a) | Jun 23, 2023 |
| HP            | 1000                        | Notebook    | [21faecd7a6](https://bsd-hardware.info/?probe=21faecd7a6) | Jun 23, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [d194e8bc0d](https://bsd-hardware.info/?probe=d194e8bc0d) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [6172c8b66f](https://bsd-hardware.info/?probe=6172c8b66f) | Jun 22, 2023 |
| ASUSTek       | P5K PRO                     | Desktop     | [f0b283fdaf](https://bsd-hardware.info/?probe=f0b283fdaf) | Jun 19, 2023 |
| Apple         | MacBook2,1                  | Notebook    | [9e864bfe3b](https://bsd-hardware.info/?probe=9e864bfe3b) | Jun 18, 2023 |
| Dell          | Latitude E6520              | Notebook    | [98868960d5](https://bsd-hardware.info/?probe=98868960d5) | Jun 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [b0659ff5bf](https://bsd-hardware.info/?probe=b0659ff5bf) | Jun 18, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [53bbc07cc8](https://bsd-hardware.info/?probe=53bbc07cc8) | Jun 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [705c750691](https://bsd-hardware.info/?probe=705c750691) | Jun 17, 2023 |
| AZW           | SER                         | Mini pc     | [278b419d40](https://bsd-hardware.info/?probe=278b419d40) | Jun 17, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | Desktop     | [4e827b2cbf](https://bsd-hardware.info/?probe=4e827b2cbf) | Jun 16, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | Desktop     | [3d71827388](https://bsd-hardware.info/?probe=3d71827388) | Jun 16, 2023 |
| IBM           | 69Y5698                     | Server      | [9f5eb975e0](https://bsd-hardware.info/?probe=9f5eb975e0) | Jun 16, 2023 |
| Dell          | 053CWD A00                  | Desktop     | [7a5418ac7e](https://bsd-hardware.info/?probe=7a5418ac7e) | Jun 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b4f214b72](https://bsd-hardware.info/?probe=6b4f214b72) | Jun 15, 2023 |
| Notebook      | NL5xRU                      | Notebook    | [04ca736537](https://bsd-hardware.info/?probe=04ca736537) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [615e7cbf52](https://bsd-hardware.info/?probe=615e7cbf52) | Jun 15, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | Notebook    | [722403df31](https://bsd-hardware.info/?probe=722403df31) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [8357f0f72e](https://bsd-hardware.info/?probe=8357f0f72e) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [834f9f8748](https://bsd-hardware.info/?probe=834f9f8748) | Jun 15, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [7e1aa76e45](https://bsd-hardware.info/?probe=7e1aa76e45) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [f41e1f2b83](https://bsd-hardware.info/?probe=f41e1f2b83) | Jun 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4841a6b1d2](https://bsd-hardware.info/?probe=4841a6b1d2) | Jun 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6e8e70ddc2](https://bsd-hardware.info/?probe=6e8e70ddc2) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c19a29f083](https://bsd-hardware.info/?probe=c19a29f083) | Jun 13, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [f6540a4d85](https://bsd-hardware.info/?probe=f6540a4d85) | Jun 13, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [5a21ed950e](https://bsd-hardware.info/?probe=5a21ed950e) | Jun 13, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [1d3675e09e](https://bsd-hardware.info/?probe=1d3675e09e) | Jun 11, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [9279b8ab4e](https://bsd-hardware.info/?probe=9279b8ab4e) | Jun 11, 2023 |
| MSI           | H81M-P33                    | Desktop     | [3d9a05635f](https://bsd-hardware.info/?probe=3d9a05635f) | Jun 11, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b8f3eeed4b](https://bsd-hardware.info/?probe=b8f3eeed4b) | Jun 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9c888141fb](https://bsd-hardware.info/?probe=9c888141fb) | Jun 11, 2023 |
| Lenovo        | B40-30 80F1                 | Notebook    | [769c678314](https://bsd-hardware.info/?probe=769c678314) | Jun 10, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [439e6a5034](https://bsd-hardware.info/?probe=439e6a5034) | Jun 10, 2023 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [7e0151a93f](https://bsd-hardware.info/?probe=7e0151a93f) | Jun 10, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [27ba75252a](https://bsd-hardware.info/?probe=27ba75252a) | Jun 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP4C    | Notebook    | [b891388109](https://bsd-hardware.info/?probe=b891388109) | Jun 07, 2023 |
| Lenovo        | ThinkPad T500 2082BNU       | Notebook    | [dedd066084](https://bsd-hardware.info/?probe=dedd066084) | Jun 06, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [d04a63aa31](https://bsd-hardware.info/?probe=d04a63aa31) | Jun 06, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [03e1e6d302](https://bsd-hardware.info/?probe=03e1e6d302) | Jun 05, 2023 |
| HP            | 212B                        | Desktop     | [4db61072c4](https://bsd-hardware.info/?probe=4db61072c4) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [cf9ed85e65](https://bsd-hardware.info/?probe=cf9ed85e65) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [fc66ebba25](https://bsd-hardware.info/?probe=fc66ebba25) | Jun 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [88598bfbf5](https://bsd-hardware.info/?probe=88598bfbf5) | Jun 04, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [fac0ed387e](https://bsd-hardware.info/?probe=fac0ed387e) | Jun 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [3c76deca15](https://bsd-hardware.info/?probe=3c76deca15) | Jun 04, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [dc65d735c8](https://bsd-hardware.info/?probe=dc65d735c8) | Jun 04, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [314d462dcd](https://bsd-hardware.info/?probe=314d462dcd) | Jun 04, 2023 |
| Dell          | G5 5505                     | Notebook    | [5a3c1f19a0](https://bsd-hardware.info/?probe=5a3c1f19a0) | Jun 03, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [d4247f35c8](https://bsd-hardware.info/?probe=d4247f35c8) | Jun 02, 2023 |
| Dell          | G5 5505                     | Notebook    | [1b10aecc38](https://bsd-hardware.info/?probe=1b10aecc38) | Jun 02, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [22572f1df6](https://bsd-hardware.info/?probe=22572f1df6) | Jun 01, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [8cc6299ba9](https://bsd-hardware.info/?probe=8cc6299ba9) | May 31, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [2445651c96](https://bsd-hardware.info/?probe=2445651c96) | May 31, 2023 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | Notebook    | [b5f507c034](https://bsd-hardware.info/?probe=b5f507c034) | May 31, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [a9b9a2e045](https://bsd-hardware.info/?probe=a9b9a2e045) | May 29, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [e63f1f4874](https://bsd-hardware.info/?probe=e63f1f4874) | May 29, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [382fe30ec1](https://bsd-hardware.info/?probe=382fe30ec1) | May 28, 2023 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [d5fdf2ff2c](https://bsd-hardware.info/?probe=d5fdf2ff2c) | May 28, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [6701dce30e](https://bsd-hardware.info/?probe=6701dce30e) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [28c84f71fd](https://bsd-hardware.info/?probe=28c84f71fd) | May 28, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [cf8b2af78b](https://bsd-hardware.info/?probe=cf8b2af78b) | May 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [3944241750](https://bsd-hardware.info/?probe=3944241750) | May 27, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [65376d6b42](https://bsd-hardware.info/?probe=65376d6b42) | May 27, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [8514299fe4](https://bsd-hardware.info/?probe=8514299fe4) | May 26, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [adc687fcfe](https://bsd-hardware.info/?probe=adc687fcfe) | May 26, 2023 |
| ASRockRack    | GENOAD8UD-2T/X550           | Desktop     | [c6b62c6b5b](https://bsd-hardware.info/?probe=c6b62c6b5b) | May 26, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [81775d5ca1](https://bsd-hardware.info/?probe=81775d5ca1) | May 26, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [3797f9d0a9](https://bsd-hardware.info/?probe=3797f9d0a9) | May 24, 2023 |
| Lenovo        | ThinkPad T430 2347CTO       | Notebook    | [68937b1686](https://bsd-hardware.info/?probe=68937b1686) | May 24, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [a1a68c0f7d](https://bsd-hardware.info/?probe=a1a68c0f7d) | May 24, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [7bcb7c96be](https://bsd-hardware.info/?probe=7bcb7c96be) | May 23, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [9a2c066dfa](https://bsd-hardware.info/?probe=9a2c066dfa) | May 23, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [b5f17b6bf8](https://bsd-hardware.info/?probe=b5f17b6bf8) | May 23, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [eba55377e0](https://bsd-hardware.info/?probe=eba55377e0) | May 22, 2023 |
| MSI           | H81M-P33                    | Desktop     | [cadb0f588f](https://bsd-hardware.info/?probe=cadb0f588f) | May 21, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [4a55c4a669](https://bsd-hardware.info/?probe=4a55c4a669) | May 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f2fb56c7dc](https://bsd-hardware.info/?probe=f2fb56c7dc) | May 21, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [7aed9d938a](https://bsd-hardware.info/?probe=7aed9d938a) | May 21, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [a87acae699](https://bsd-hardware.info/?probe=a87acae699) | May 21, 2023 |
| HP            | 158B                        | Desktop     | [1ef3762103](https://bsd-hardware.info/?probe=1ef3762103) | May 20, 2023 |
| HP            | 158B                        | Desktop     | [a9c63041a6](https://bsd-hardware.info/?probe=a9c63041a6) | May 20, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [186e5d4e15](https://bsd-hardware.info/?probe=186e5d4e15) | May 19, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [47d985333c](https://bsd-hardware.info/?probe=47d985333c) | May 19, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [70d54595c2](https://bsd-hardware.info/?probe=70d54595c2) | May 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [7be0869603](https://bsd-hardware.info/?probe=7be0869603) | May 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [ef56a2bd17](https://bsd-hardware.info/?probe=ef56a2bd17) | May 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [9350bb37db](https://bsd-hardware.info/?probe=9350bb37db) | May 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS03Q00    | Notebook    | [a2110471aa](https://bsd-hardware.info/?probe=a2110471aa) | May 18, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [73335cbb47](https://bsd-hardware.info/?probe=73335cbb47) | May 17, 2023 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [830100249f](https://bsd-hardware.info/?probe=830100249f) | May 17, 2023 |
| Panasonic     | CF-30KAPAXAM                | Notebook    | [62910ad9d9](https://bsd-hardware.info/?probe=62910ad9d9) | May 17, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [12b0e44025](https://bsd-hardware.info/?probe=12b0e44025) | May 17, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [27be69ed61](https://bsd-hardware.info/?probe=27be69ed61) | May 15, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [25c403ca33](https://bsd-hardware.info/?probe=25c403ca33) | May 15, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [e252dc5ff2](https://bsd-hardware.info/?probe=e252dc5ff2) | May 15, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [8d445a3fb3](https://bsd-hardware.info/?probe=8d445a3fb3) | May 14, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [3bf2cd6d1e](https://bsd-hardware.info/?probe=3bf2cd6d1e) | May 14, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [7d0fe109f0](https://bsd-hardware.info/?probe=7d0fe109f0) | May 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [526906c806](https://bsd-hardware.info/?probe=526906c806) | May 14, 2023 |
| MSI           | B85M-G43                    | Desktop     | [6d2160dcee](https://bsd-hardware.info/?probe=6d2160dcee) | May 14, 2023 |
| Alienware     | 17 R4                       | Notebook    | [df734c8e64](https://bsd-hardware.info/?probe=df734c8e64) | May 14, 2023 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [47800f4d42](https://bsd-hardware.info/?probe=47800f4d42) | May 14, 2023 |
| MSI           | H81M-P33                    | Desktop     | [ebf1ee8152](https://bsd-hardware.info/?probe=ebf1ee8152) | May 14, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [2bf04b4cf1](https://bsd-hardware.info/?probe=2bf04b4cf1) | May 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ae7796a444](https://bsd-hardware.info/?probe=ae7796a444) | May 14, 2023 |
| HP            | 802F                        | Desktop     | [fdf293f78f](https://bsd-hardware.info/?probe=fdf293f78f) | May 14, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/FreeBSD/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| FreeBSD 13.1         | 236       | 7.05%   |
| FreeBSD 13.0         | 223       | 6.66%   |
| FreeBSD 13.2         | 157       | 4.69%   |
| FreeBSD 14.0-CURRENT | 152       | 4.54%   |
| FreeBSD 12.2         | 141       | 4.21%   |
| FreeBSD 14.0         | 109       | 3.25%   |
| FreeBSD 12.2-p2      | 96        | 2.87%   |
| FreeBSD 13.0-p4      | 85        | 2.54%   |
| FreeBSD 13.1-p5      | 83        | 2.48%   |
| FreeBSD 12.1-p10     | 80        | 2.39%   |
| FreeBSD 13.0-p5      | 76        | 2.27%   |
| FreeBSD 13.0-STABLE  | 72        | 2.15%   |
| FreeBSD 13.1-p2      | 71        | 2.12%   |
| FreeBSD 12.1-p8      | 69        | 2.06%   |
| FreeBSD 13.0-CURRENT | 66        | 1.97%   |
| FreeBSD 12.1         | 58        | 1.73%   |
| FreeBSD 12.1-p5      | 55        | 1.64%   |
| FreeBSD 14.0-p6      | 54        | 1.61%   |
| FreeBSD 13.1-p7      | 53        | 1.58%   |
| FreeBSD 12.2-p3      | 52        | 1.55%   |
| FreeBSD 14.0-p4      | 49        | 1.46%   |
| FreeBSD 12.1-STABLE  | 49        | 1.46%   |
| FreeBSD 12.1-p7      | 48        | 1.43%   |
| FreeBSD 13.0-p3      | 47        | 1.4%    |
| FreeBSD 12.2-p4      | 47        | 1.4%    |
| FreeBSD 14.0-p5      | 45        | 1.34%   |
| FreeBSD 13.0-p7      | 45        | 1.34%   |
| FreeBSD 13.0-p11     | 37        | 1.1%    |
| FreeBSD 12.2-p6      | 35        | 1.05%   |
| FreeBSD 13.1-STABLE  | 34        | 1.02%   |
| FreeBSD 13.2-p2      | 33        | 0.99%   |
| FreeBSD 13.0-p2      | 33        | 0.99%   |
| FreeBSD 12.2-STABLE  | 32        | 0.96%   |
| FreeBSD 13.1-p1      | 28        | 0.84%   |
| FreeBSD 13.0-p6      | 25        | 0.75%   |
| FreeBSD 15.0-CURRENT | 23        | 0.69%   |
| FreeBSD 13.2-p4      | 23        | 0.69%   |
| FreeBSD 12.3         | 23        | 0.69%   |
| FreeBSD 13.2-p3      | 22        | 0.66%   |
| FreeBSD 13.2-p1      | 22        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| FreeBSD | 2745      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 2551      | 92.86%  |
| arm64   | 95        | 3.46%   |
| i386    | 80        | 2.91%   |
| arm     | 13        | 0.47%   |
| powerpc | 6         | 0.22%   |
| sparc64 | 1         | 0.04%   |
| riscv   | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 937       | 32.66%  |
| KDE5          | 480       | 16.73%  |
| XFCE          | 461       | 16.07%  |
| GNOME         | 202       | 7.04%   |
| TWM           | 197       | 6.87%   |
| MATE          | 150       | 5.23%   |
| i3            | 118       | 4.11%   |
| Openbox       | 71        | 2.47%   |
| LXQt          | 36        | 1.25%   |
| Cinnamon      | 32        | 1.12%   |
| AwesomeWM     | 29        | 1.01%   |
| Fluxbox       | 20        | 0.7%    |
| Enlightenment | 19        | 0.66%   |
| LXDE          | 16        | 0.56%   |
| Lumina        | 11        | 0.38%   |
| DWM           | 11        | 0.38%   |
| X-Cinnamon    | 8         | 0.28%   |
| Picom         | 7         | 0.24%   |
| GNUstep       | 6         | 0.21%   |
| KDE           | 5         | 0.17%   |
| IceWM         | 5         | 0.17%   |
| Budgie        | 5         | 0.17%   |
| xfwm          | 4         | 0.14%   |
| spectrwm      | 4         | 0.14%   |
| CDE           | 4         | 0.14%   |
| Window Maker  | 3         | 0.1%    |
| xinitrc       | 2         | 0.07%   |
| wlroots       | 2         | 0.07%   |
| sway          | 2         | 0.07%   |
| StumpWM       | 2         | 0.07%   |
| Hyprland      | 2         | 0.07%   |
| helloDesktop  | 2         | 0.07%   |
| Compton       | 2         | 0.07%   |
| Blackbox      | 2         | 0.07%   |
| Xfwm4         | 1         | 0.03%   |
| Wayfire       | 1         | 0.03%   |
| Potato        | 1         | 0.03%   |
| plasma        | 1         | 0.03%   |
| KWin          | 1         | 0.03%   |
| KDE6          | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1718      | 61.49%  |
| Console | 1002      | 35.86%  |
| Wayland | 73        | 2.61%   |
| Tty     | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1531      | 53.91%  |
| SDDM    | 485       | 17.08%  |
| SLiM    | 275       | 9.68%   |
| LightDM | 211       | 7.43%   |
| XDM     | 180       | 6.34%   |
| GDM     | 131       | 4.61%   |
| Ly      | 24        | 0.85%   |
| PCDM    | 2         | 0.07%   |
| WDM     | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 1273      | 44.25%  |
| Unknown          | 693       | 24.09%  |
| en_US            | 408       | 14.18%  |
| ru_RU            | 145       | 5.04%   |
| de_DE            | 54        | 1.88%   |
| fr_FR            | 46        | 1.6%    |
| en_GB            | 36        | 1.25%   |
| zh_CN            | 19        | 0.66%   |
| en_CA            | 18        | 0.63%   |
| pt_BR            | 14        | 0.49%   |
| pl_PL            | 13        | 0.45%   |
| ja_JP            | 13        | 0.45%   |
| es_ES            | 11        | 0.38%   |
| en_AU            | 10        | 0.35%   |
| uk_UA            | 9         | 0.31%   |
| it_IT            | 8         | 0.28%   |
| en_IE            | 8         | 0.28%   |
| nb_NO            | 7         | 0.24%   |
| es_AR            | 5         | 0.17%   |
| en_US.ISO8859-1  | 5         | 0.17%   |
| cs_CZ            | 5         | 0.17%   |
| ru_RU.KOI8-R     | 4         | 0.14%   |
| fi_FI            | 4         | 0.14%   |
| en_NZ            | 4         | 0.14%   |
| el_GR            | 4         | 0.14%   |
| de_CH            | 4         | 0.14%   |
| zh_TW            | 3         | 0.1%    |
| en_US.US-ASCII   | 3         | 0.1%    |
| de_DE.ISO8859-1  | 3         | 0.1%    |
| sv_SE            | 2         | 0.07%   |
| pt_PT            | 2         | 0.07%   |
| nl_NL            | 2         | 0.07%   |
| ko_KR            | 2         | 0.07%   |
| it_IT.ISO8859-15 | 2         | 0.07%   |
| es_MX            | 2         | 0.07%   |
| en_SG            | 2         | 0.07%   |
| en_GB.US-ASCII   | 2         | 0.07%   |
| en_GB.ISO8859-1  | 2         | 0.07%   |
| de               | 2         | 0.07%   |
| zh_CN.GB2312     | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1815      | 65.45%  |
| BIOS | 958       | 34.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 1794      | 64.51%  |
| Ufs     | 981       | 35.28%  |
| Nfs     | 2         | 0.07%   |
| Cd9660  | 2         | 0.07%   |
| Xfs     | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2453      | 88.88%  |
| MBR     | 279       | 10.11%  |
| BSD     | 15        | 0.54%   |
| Unknown | 13        | 0.47%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 470       | 17.12%  |
| Dell                    | 389       | 14.17%  |
| ASUSTek Computer        | 349       | 12.71%  |
| Hewlett-Packard         | 240       | 8.74%   |
| Gigabyte Technology     | 155       | 5.65%   |
| ASRock                  | 123       | 4.48%   |
| MSI                     | 111       | 4.04%   |
| Unknown                 | 109       | 3.97%   |
| Intel                   | 95        | 3.46%   |
| Supermicro              | 93        | 3.39%   |
| Acer                    | 78        | 2.84%   |
| Apple                   | 63        | 2.3%    |
| Fujitsu                 | 36        | 1.31%   |
| Raspberry Pi Foundation | 28        | 1.02%   |
| Toshiba                 | 25        | 0.91%   |
| Samsung Electronics     | 20        | 0.73%   |
| IBM                     | 19        | 0.69%   |
| PC Engines              | 17        | 0.62%   |
| Google                  | 17        | 0.62%   |
| ASRockRack              | 17        | 0.62%   |
| System76                | 14        | 0.51%   |
| HUAWEI                  | 14        | 0.51%   |
| Sony                    | 10        | 0.36%   |
| AZW                     | 10        | 0.36%   |
| TUXEDO                  | 9         | 0.33%   |
| Shuttle                 | 8         | 0.29%   |
| HPE                     | 8         | 0.29%   |
| Alienware               | 8         | 0.29%   |
| Sun Microsystems        | 6         | 0.22%   |
| Panasonic               | 6         | 0.22%   |
| Notebook                | 6         | 0.22%   |
| Framework               | 6         | 0.22%   |
| Biostar                 | 6         | 0.22%   |
| AMI                     | 6         | 0.22%   |
| Gateway                 | 5         | 0.18%   |
| Foxconn                 | 5         | 0.18%   |
| Deciso                  | 5         | 0.18%   |
| Cisco Systems           | 5         | 0.18%   |
| Beckhoff Automation     | 5         | 0.18%   |
| Wistron                 | 4         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 115       | 4.19%   |
| ASUS All Series                  | 30        | 1.09%   |
| RPi Raspberry Pi                 | 27        | 0.98%   |
| Supermicro Super Server          | 25        | 0.91%   |
| Dell OEM-R 720xd                 | 13        | 0.47%   |
| HP ProLiant MicroServer Gen8     | 10        | 0.36%   |
| PC Engines APU2                  | 9         | 0.33%   |
| Intel Nobilis                    | 9         | 0.33%   |
| ASUS TUF Gaming X570-PLUS        | 9         | 0.33%   |
| HP ProLiant MicroServer          | 8         | 0.29%   |
| Dell PowerEdge R710              | 8         | 0.29%   |
| MSI MS-7B89                      | 7         | 0.26%   |
| Framework Laptop                 | 6         | 0.22%   |
| ASRock Z590 Pro4                 | 6         | 0.22%   |
| MSI MS-7C02                      | 5         | 0.18%   |
| HP Z440 Workstation              | 5         | 0.18%   |
| HP EliteBook 840 G3              | 5         | 0.18%   |
| Gigabyte B360N WIFI              | 5         | 0.18%   |
| Fujitsu D3401-H2 S26361-D3401-H2 | 5         | 0.18%   |
| Dell PowerEdge R720              | 5         | 0.18%   |
| Dell PowerEdge R610              | 5         | 0.18%   |
| Dell OptiPlex 9020               | 5         | 0.18%   |
| Dell OptiPlex 7050               | 5         | 0.18%   |
| Dell Latitude E7240              | 5         | 0.18%   |
| Dell Latitude E6430              | 5         | 0.18%   |
| AZW SER                          | 5         | 0.18%   |
| ASRock X570 Phantom Gaming 4     | 5         | 0.18%   |
| System76 Lemur Pro               | 4         | 0.15%   |
| Supermicro X9SCL/X9SCM           | 4         | 0.15%   |
| Supermicro X10SLL-F              | 4         | 0.15%   |
| Sun Microsystems SUN FIRE X4150  | 4         | 0.15%   |
| MSI MS-7693                      | 4         | 0.15%   |
| HPE ProLiant MicroServer Gen10   | 4         | 0.15%   |
| HP Z620 Workstation              | 4         | 0.15%   |
| HP Z420 Workstation              | 4         | 0.15%   |
| HP t620 Quad Core TC             | 4         | 0.15%   |
| HP EliteBook 8570p               | 4         | 0.15%   |
| HP Compaq Elite 8300 SFF         | 4         | 0.15%   |
| Gigabyte X570 I AORUS PRO WIFI   | 4         | 0.15%   |
| Gigabyte B450M DS3H              | 4         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 333       | 12.13%  |
| Unknown            | 115       | 4.19%   |
| Dell Latitude      | 89        | 3.24%   |
| Dell PowerEdge     | 70        | 2.55%   |
| Dell Inspiron      | 59        | 2.15%   |
| Dell OptiPlex      | 54        | 1.97%   |
| ASUS PRIME         | 51        | 1.86%   |
| Acer Aspire        | 46        | 1.68%   |
| Lenovo IdeaPad     | 44        | 1.6%    |
| Dell Precision     | 44        | 1.6%    |
| HP ProLiant        | 41        | 1.49%   |
| ASUS TUF           | 33        | 1.2%    |
| ASUS ROG           | 33        | 1.2%    |
| HP Compaq          | 31        | 1.13%   |
| ASUS All           | 30        | 1.09%   |
| RPi Raspberry      | 27        | 0.98%   |
| Supermicro Super   | 25        | 0.91%   |
| HP ProBook         | 23        | 0.84%   |
| Dell XPS           | 22        | 0.8%    |
| HP EliteBook       | 21        | 0.77%   |
| Lenovo ThinkCentre | 19        | 0.69%   |
| Toshiba Satellite  | 17        | 0.62%   |
| Dell Vostro        | 17        | 0.62%   |
| HP Pavilion        | 15        | 0.55%   |
| Lenovo Legion      | 13        | 0.47%   |
| HP Laptop          | 13        | 0.47%   |
| Dell OEM-R         | 13        | 0.47%   |
| ASRock X570        | 13        | 0.47%   |
| IBM System         | 12        | 0.44%   |
| HP EliteDesk       | 10        | 0.36%   |
| Gigabyte X570      | 10        | 0.36%   |
| ASUS ZenBook       | 10        | 0.36%   |
| ASUS ASUS          | 10        | 0.36%   |
| PC Engines APU2    | 9         | 0.33%   |
| Intel Nobilis      | 9         | 0.33%   |
| ASUS VivoBook      | 9         | 0.33%   |
| ASUS PRO           | 9         | 0.33%   |
| Lenovo ThinkBook   | 8         | 0.29%   |
| HPE ProLiant       | 8         | 0.29%   |
| HP ENVY            | 8         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 299       | 10.89%  |
| 2019    | 251       | 9.14%   |
| 2021    | 239       | 8.71%   |
| 2018    | 225       | 8.2%    |
| 2011    | 168       | 6.12%   |
| 2013    | 162       | 5.9%    |
| 2014    | 147       | 5.36%   |
| 2016    | 144       | 5.25%   |
| 2017    | 143       | 5.21%   |
| 2015    | 142       | 5.17%   |
| 2022    | 140       | 5.1%    |
| 2012    | 137       | 4.99%   |
| 2010    | 110       | 4.01%   |
| Unknown | 105       | 3.83%   |
| 2023    | 95        | 3.46%   |
| 2009    | 79        | 2.88%   |
| 2008    | 75        | 2.73%   |
| 2007    | 36        | 1.31%   |
| 2006    | 16        | 0.58%   |
| 2024    | 9         | 0.33%   |
| 2005    | 7         | 0.26%   |
| 2004    | 6         | 0.22%   |
| 2003    | 5         | 0.18%   |
| 2002    | 4         | 0.15%   |
| 2001    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1178      | 42.91%  |
| Notebook       | 1166      | 42.48%  |
| Server         | 208       | 7.58%   |
| Mini pc        | 83        | 3.02%   |
| System on chip | 58        | 2.11%   |
| Convertible    | 29        | 1.06%   |
| All in one     | 21        | 0.77%   |
| Tablet         | 2         | 0.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2692      | 98.07%  |
| Yes  | 53        | 1.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 717       | 25.76%  |
| 16.01-24.0      | 709       | 25.48%  |
| 32.01-64.0      | 412       | 14.8%   |
| 4.01-8.0        | 351       | 12.61%  |
| 64.01-256.0     | 273       | 9.81%   |
| 2.01-3.0        | 96        | 3.45%   |
| 3.01-4.0        | 59        | 2.12%   |
| 0.51-1.0        | 55        | 1.98%   |
| 24.01-32.0      | 53        | 1.9%    |
| More than 256.0 | 21        | 0.75%   |
| 1.01-2.0        | 18        | 0.65%   |
| 0.01-0.5        | 18        | 0.65%   |
| Unknown         | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 0.01-0.5        | 933       | 32.84%  |
| 0.51-1.0        | 864       | 30.41%  |
| 1.01-2.0        | 527       | 18.55%  |
| 2.01-3.0        | 147       | 5.17%   |
| 4.01-8.0        | 103       | 3.63%   |
| 3.01-4.0        | 81        | 2.85%   |
| 8.01-16.0       | 53        | 1.87%   |
| 0               | 34        | 1.2%    |
| 24.01-32.0      | 31        | 1.09%   |
| 32.01-64.0      | 23        | 0.81%   |
| 16.01-24.0      | 23        | 0.81%   |
| 64.01-256.0     | 20        | 0.7%    |
| More than 256.0 | 1         | 0.04%   |
| Unknown         | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1316      | 45.81%  |
| 2      | 588       | 20.47%  |
| 0      | 300       | 10.44%  |
| 3      | 235       | 8.18%   |
| 4      | 149       | 5.19%   |
| 5      | 94        | 3.27%   |
| 6      | 58        | 2.02%   |
| 7      | 32        | 1.11%   |
| 8      | 21        | 0.73%   |
| 10     | 13        | 0.45%   |
| 12     | 12        | 0.42%   |
| 14     | 11        | 0.38%   |
| 9      | 9         | 0.31%   |
| 11     | 8         | 0.28%   |
| 18     | 3         | 0.1%    |
| 17     | 3         | 0.1%    |
| 16     | 3         | 0.1%    |
| 58     | 2         | 0.07%   |
| 25     | 2         | 0.07%   |
| 24     | 2         | 0.07%   |
| 23     | 2         | 0.07%   |
| 15     | 2         | 0.07%   |
| 13     | 2         | 0.07%   |
| 63     | 1         | 0.03%   |
| 40     | 1         | 0.03%   |
| 30     | 1         | 0.03%   |
| 28     | 1         | 0.03%   |
| 21     | 1         | 0.03%   |
| 19     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2019      | 72.97%  |
| Yes       | 748       | 27.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2395      | 87.22%  |
| No        | 351       | 12.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1571      | 56.82%  |
| No        | 1194      | 43.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1598      | 57.65%  |
| Yes       | 1174      | 42.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 611       | 22.05%  |
| Russia      | 308       | 11.12%  |
| Germany     | 271       | 9.78%   |
| France      | 150       | 5.41%   |
| UK          | 104       | 3.75%   |
| Canada      | 99        | 3.57%   |
| Poland      | 97        | 3.5%    |
| China       | 63        | 2.27%   |
| Brazil      | 61        | 2.2%    |
| Australia   | 61        | 2.2%    |
| Netherlands | 56        | 2.02%   |
| Czechia     | 52        | 1.88%   |
| Ukraine     | 48        | 1.73%   |
| Switzerland | 48        | 1.73%   |
| Japan       | 46        | 1.66%   |
| Austria     | 41        | 1.48%   |
| Spain       | 40        | 1.44%   |
| Italy       | 39        | 1.41%   |
| Sweden      | 36        | 1.3%    |
| Indonesia   | 32        | 1.15%   |
| India       | 28        | 1.01%   |
| Norway      | 26        | 0.94%   |
| Romania     | 25        | 0.9%    |
| Finland     | 25        | 0.9%    |
| Ireland     | 23        | 0.83%   |
| Argentina   | 20        | 0.72%   |
| Mexico      | 17        | 0.61%   |
| Greece      | 17        | 0.61%   |
| Thailand    | 16        | 0.58%   |
| Bulgaria    | 16        | 0.58%   |
| New Zealand | 15        | 0.54%   |
| Hungary     | 15        | 0.54%   |
| Vietnam     | 14        | 0.51%   |
| Portugal    | 14        | 0.51%   |
| Denmark     | 14        | 0.51%   |
| Belgium     | 14        | 0.51%   |
| Taiwan      | 12        | 0.43%   |
| Turkey      | 11        | 0.4%    |
| Croatia     | 11        | 0.4%    |
| Slovenia    | 9         | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Moscow        | 117       | 3.94%   |
| Vienna        | 34        | 1.14%   |
| Berlin        | 33        | 1.11%   |
| St Petersburg | 31        | 1.04%   |
| Sydney        | 28        | 0.94%   |
| Brooklyn      | 27        | 0.91%   |
| Paris         | 23        | 0.77%   |
| Kyiv          | 23        | 0.77%   |
| Warsaw        | 19        | 0.64%   |
| London        | 18        | 0.61%   |
| Krasnodar     | 18        | 0.61%   |
| Gdynia        | 18        | 0.61%   |
| Amsterdam     | 17        | 0.57%   |
| Yekaterinburg | 16        | 0.54%   |
| Ludwigsburg   | 16        | 0.54%   |
| Grand Rapids  | 16        | 0.54%   |
| Dublin        | 16        | 0.54%   |
| Chicago       | 16        | 0.54%   |
| Zurich        | 15        | 0.5%    |
| Prague        | 15        | 0.5%    |
| Montreal      | 15        | 0.5%    |
| Helsinki      | 15        | 0.5%    |
| Portland      | 14        | 0.47%   |
| Seattle       | 13        | 0.44%   |
| Tuklaty       | 12        | 0.4%    |
| Jakarta       | 12        | 0.4%    |
| Madrid        | 11        | 0.37%   |
| Stockholm     | 10        | 0.34%   |
| Sofia         | 10        | 0.34%   |
| Ozersk        | 10        | 0.34%   |
| Munich        | 10        | 0.34%   |
| Hamburg       | 10        | 0.34%   |
| Shenzhen      | 9         | 0.3%    |
| Oslo          | 9         | 0.3%    |
| Novosibirsk   | 9         | 0.3%    |
| New York      | 9         | 0.3%    |
| Milan         | 9         | 0.3%    |
| Lexington     | 9         | 0.3%    |
| Falkenstein   | 9         | 0.3%    |
| Brno          | 9         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 695       | 2106   | 18.33%  |
| Samsung Electronics | 646       | 1289   | 17.04%  |
| Seagate             | 529       | 1375   | 13.95%  |
| Toshiba             | 248       | 524    | 6.54%   |
| Kingston            | 225       | 297    | 5.94%   |
| Crucial             | 209       | 332    | 5.51%   |
| Intel               | 152       | 293    | 4.01%   |
| Hitachi             | 116       | 292    | 3.06%   |
| SanDisk             | 107       | 147    | 2.82%   |
| HGST                | 99        | 388    | 2.61%   |
| A-DATA Technology   | 63        | 79     | 1.66%   |
| SK hynix            | 59        | 78     | 1.56%   |
| Micron Technology   | 50        | 87     | 1.32%   |
| Transcend           | 47        | 62     | 1.24%   |
| Hewlett-Packard     | 37        | 191    | 0.98%   |
| Apple               | 26        | 28     | 0.69%   |
| Phison              | 25        | 36     | 0.66%   |
| SPCC                | 23        | 42     | 0.61%   |
| PNY                 | 22        | 33     | 0.58%   |
| KIOXIA              | 19        | 19     | 0.5%    |
| Gigabyte Technology | 19        | 27     | 0.5%    |
| Corsair             | 19        | 50     | 0.5%    |
| OCZ                 | 18        | 22     | 0.47%   |
| LITEON              | 14        | 19     | 0.37%   |
| KingSpec            | 14        | 20     | 0.37%   |
| Silicon Motion      | 12        | 14     | 0.32%   |
| Fujitsu             | 12        | 18     | 0.32%   |
| Patriot             | 11        | 16     | 0.29%   |
| GOODRAM             | 11        | 23     | 0.29%   |
| China               | 11        | 17     | 0.29%   |
| Maxtor              | 10        | 14     | 0.26%   |
| Apacer              | 10        | 11     | 0.26%   |
| OWC                 | 9         | 15     | 0.24%   |
| Intenso             | 9         | 10     | 0.24%   |
| Team                | 8         | 11     | 0.21%   |
| SSSTC               | 8         | 11     | 0.21%   |
| Plextor             | 8         | 14     | 0.21%   |
| Mushkin             | 8         | 9      | 0.21%   |
| MidasForce          | 8         | 10     | 0.21%   |
| Lenovo              | 8         | 9      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 49        | 1.09%   |
| Samsung SSD 850 EVO 250GB          | 35        | 0.78%   |
| Samsung SSD 970 EVO Plus 1TB       | 26        | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB           | 25        | 0.56%   |
| Samsung SSD 860 EVO 500GB          | 25        | 0.56%   |
| Samsung SSD 850 EVO 500GB          | 25        | 0.56%   |
| WDC WD40EFRX-68N32N0 4TB           | 24        | 0.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 24        | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB     | 24        | 0.53%   |
| Kingston SA400S37120G 120GB        | 24        | 0.53%   |
| Kingston SA400S37480G 480GB        | 23        | 0.51%   |
| WDC WD30EFRX-68EUZN0 3TB           | 22        | 0.49%   |
| Samsung SSD 870 EVO 1TB            | 22        | 0.49%   |
| Samsung SSD 860 EVO 250GB          | 22        | 0.49%   |
| Seagate ST2000DM008-2FR102 2TB     | 21        | 0.47%   |
| Crucial CT500MX500SSD1 500GB       | 21        | 0.47%   |
| Toshiba DT01ACA100 1TB             | 19        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB        | 19        | 0.42%   |
| Toshiba MQ01ABD100 1TB             | 18        | 0.4%    |
| Samsung SSD 860 EVO 1TB            | 18        | 0.4%    |
| Crucial CT250MX500SSD1 250GB       | 18        | 0.4%    |
| Crucial CT240BX500SSD1 240GB       | 18        | 0.4%    |
| WDC WD800JD-75MSA3 80GB            | 17        | 0.38%   |
| Seagate ST1000LM035-1RK172 1TB     | 17        | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB     | 17        | 0.38%   |
| HGST HTS721010A9E630 1TB           | 17        | 0.38%   |
| WDC WD20EFRX-68EUZN0 2TB           | 16        | 0.36%   |
| Toshiba MQ01ABF050 500GB           | 16        | 0.36%   |
| Seagate ST4000DM000-1F2168 4TB     | 16        | 0.36%   |
| Samsung SSD 870 EVO 500GB          | 16        | 0.36%   |
| Kingston SV300S37A120G 120GB       | 16        | 0.36%   |
| Samsung SSD 980 1TB                | 14        | 0.31%   |
| Samsung SSD 850 EVO 1TB            | 14        | 0.31%   |
| Seagate ST4000VN008-2DR166 4TB     | 13        | 0.29%   |
| Seagate ST1000DM003-1CH162 1TB     | 13        | 0.29%   |
| Samsung SSD 970 EVO 500GB          | 13        | 0.29%   |
| WDC WD40EFRX-68WT0N0 4TB           | 12        | 0.27%   |
| Toshiba MQ04ABF100 1TB             | 12        | 0.27%   |
| Seagate ST500DM002-1BD142 500GB    | 12        | 0.27%   |
| Seagate ST4000DM004-2CV104 4TB     | 12        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| WDC                  | 562       | 1824   | 34.39%  |
| Seagate              | 519       | 1356   | 31.76%  |
| Toshiba              | 208       | 462    | 12.73%  |
| Hitachi              | 115       | 288    | 7.04%   |
| HGST                 | 99        | 384    | 6.06%   |
| Samsung Electronics  | 54        | 88     | 3.3%    |
| Hewlett-Packard      | 24        | 175    | 1.47%   |
| Fujitsu              | 12        | 18     | 0.73%   |
| Maxtor               | 10        | 14     | 0.61%   |
| Apple                | 7         | 8      | 0.43%   |
| HPE                  | 4         | 21     | 0.24%   |
| LSI                  | 3         | 6      | 0.18%   |
| IBM/Hitachi          | 2         | 2      | 0.12%   |
| HPT                  | 2         | 9      | 0.12%   |
| Dell                 | 2         | 5      | 0.12%   |
| Areca                | 2         | 3      | 0.12%   |
| Adaptec              | 2         | 12     | 0.12%   |
| WD MediaMax          | 1         | 3      | 0.06%   |
| SYNOLOGY             | 1         | 1      | 0.06%   |
| QUANTUM              | 1         | 2      | 0.06%   |
| NETAPP               | 1         | 2      | 0.06%   |
| MaxDigital           | 1         | 1      | 0.06%   |
| IBM                  | 1         | 1      | 0.06%   |
| ExcelStor Technology | 1         | 4      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 367       | 790    | 24.19%  |
| Kingston            | 188       | 248    | 12.39%  |
| Crucial             | 169       | 263    | 11.14%  |
| SanDisk             | 106       | 146    | 6.99%   |
| Intel               | 102       | 229    | 6.72%   |
| WDC                 | 83        | 137    | 5.47%   |
| A-DATA Technology   | 45        | 57     | 2.97%   |
| Transcend           | 42        | 55     | 2.77%   |
| Micron Technology   | 30        | 57     | 1.98%   |
| SK hynix            | 25        | 31     | 1.65%   |
| Toshiba             | 20        | 23     | 1.32%   |
| Apple               | 19        | 20     | 1.25%   |
| OCZ                 | 18        | 22     | 1.19%   |
| SPCC                | 17        | 34     | 1.12%   |
| PNY                 | 17        | 27     | 1.12%   |
| KingSpec            | 14        | 20     | 0.92%   |
| Gigabyte Technology | 14        | 20     | 0.92%   |
| LITEON              | 13        | 18     | 0.86%   |
| Corsair             | 13        | 18     | 0.86%   |
| Patriot             | 11        | 16     | 0.73%   |
| China               | 11        | 17     | 0.73%   |
| Apacer              | 10        | 11     | 0.66%   |
| Seagate             | 9         | 12     | 0.59%   |
| OWC                 | 9         | 15     | 0.59%   |
| Intenso             | 9         | 10     | 0.59%   |
| MidasForce          | 8         | 10     | 0.53%   |
| Hewlett-Packard     | 8         | 8      | 0.53%   |
| GOODRAM             | 8         | 19     | 0.53%   |
| Team                | 7         | 10     | 0.46%   |
| Plextor             | 6         | 9      | 0.4%    |
| Mushkin             | 6         | 6      | 0.4%    |
| Lexar               | 6         | 15     | 0.4%    |
| Verbatim            | 5         | 5      | 0.33%   |
| Phison              | 4         | 5      | 0.26%   |
| Netac               | 4         | 4      | 0.26%   |
| LITEONIT            | 4         | 4      | 0.26%   |
| Lenovo              | 4         | 5      | 0.26%   |
| Hoodisk             | 4         | 6      | 0.26%   |
| Hikvision           | 4         | 5      | 0.26%   |
| Zheino              | 3         | 4      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1309      | 2518   | 40.03%  |
| HDD  | 1275      | 4689   | 38.99%  |
| NVMe | 686       | 1093   | 20.98%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2079      | 7207   | 75.19%  |
| NVMe | 686       | 1093   | 24.81%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1504      | 2903   | 51.72%  |
| 0.51-1.0   | 646       | 1257   | 22.21%  |
| 1.01-2.0   | 299       | 802    | 10.28%  |
| 3.01-4.0   | 174       | 800    | 5.98%   |
| 4.01-10.0  | 149       | 894    | 5.12%   |
| 2.01-3.0   | 90        | 323    | 3.09%   |
| 10.01-20.0 | 43        | 222    | 1.48%   |
| 20.01-50.0 | 3         | 6      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 870       | 30.27%  |
| 251-500        | 660       | 22.96%  |
| 501-1000       | 432       | 15.03%  |
| 51-100         | 292       | 10.16%  |
| 21-50          | 194       | 6.75%   |
| 1001-2000      | 149       | 5.18%   |
| 1-20           | 139       | 4.84%   |
| More than 3000 | 79        | 2.75%   |
| 2001-3000      | 32        | 1.11%   |
| Unknown        | 27        | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2036      | 71.11%  |
| 21-50          | 390       | 13.62%  |
| 51-100         | 141       | 4.92%   |
| 101-250        | 114       | 3.98%   |
| 251-500        | 58        | 2.03%   |
| 501-1000       | 41        | 1.43%   |
| Unknown        | 27        | 0.94%   |
| More than 3000 | 25        | 0.87%   |
| 1001-2000      | 17        | 0.59%   |
| 2001-3000      | 12        | 0.42%   |
| 0              | 2         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB     | 8         | 8      | 1.41%   |
| Samsung Electronics SSD 870 EVO 1TB | 8         | 10     | 1.41%   |
| HGST HTS725050A7E630 500GB          | 8         | 19     | 1.41%   |
| WDC WD30EFRX-68EUZN0 3TB            | 7         | 24     | 1.24%   |
| WDC WD40EFRX-68WT0N0 4TB            | 6         | 19     | 1.06%   |
| Seagate ST3500413AS 500GB           | 6         | 9      | 1.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 6         | 7      | 1.06%   |
| Kingston SV300S37A120G 120GB        | 6         | 6      | 1.06%   |
| WDC WD20EFRX-68EUZN0 2TB            | 5         | 12     | 0.88%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 4         | 4      | 0.71%   |
| Toshiba MQ01ABF050 500GB            | 4         | 4      | 0.71%   |
| Toshiba MQ01ABD100 1TB              | 4         | 4      | 0.71%   |
| Seagate ST9500420AS 500GB           | 4         | 6      | 0.71%   |
| Seagate ST9500325AS 500GB           | 4         | 7      | 0.71%   |
| Seagate ST9250315AS 250GB           | 4         | 5      | 0.71%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 7      | 0.71%   |
| Seagate ST320LT007-9ZV142 320GB     | 4         | 4      | 0.71%   |
| Samsung Electronics HD501LJ 500GB   | 4         | 6      | 0.71%   |
| Hitachi HTS547550A9E384 500GB       | 4         | 5      | 0.71%   |
| HGST HTS721010A9E630 1TB            | 4         | 23     | 0.71%   |
| Crucial CT525MX300SSD1 528GB        | 4         | 4      | 0.71%   |
| WDC WD2000FYYZ-01UL1B2 2TB          | 3         | 5      | 0.53%   |
| Seagate ST500LM021-1KJ152 500GB     | 3         | 4      | 0.53%   |
| Seagate ST380013AS 80GB             | 3         | 4      | 0.53%   |
| Seagate ST3500418AS 500GB           | 3         | 6      | 0.53%   |
| Seagate ST2000DM001-9YN164 2TB      | 3         | 3      | 0.53%   |
| Seagate ST1000DM003-1CH162 1TB      | 3         | 4      | 0.53%   |
| Samsung Electronics HD154UI 1.5TB   | 3         | 4      | 0.53%   |
| Samsung Electronics HD103UJ 1TB     | 3         | 6      | 0.53%   |
| Kingston SNS4151S316GD 16GB         | 3         | 3      | 0.53%   |
| Intel SSDSA2M080G2GC 80GB           | 3         | 3      | 0.53%   |
| Hitachi HTS545032B9A300 320GB       | 3         | 4      | 0.53%   |
| Crucial CT480M500SSD1 480GB         | 3         | 4      | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 2      | 0.35%   |
| WDC WD5003AZEX-00MK2A0 500GB        | 2         | 2      | 0.35%   |
| WDC WD5000LPLX-22ZNTT0 500GB        | 2         | 2      | 0.35%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 2         | 3      | 0.35%   |
| WDC WD5000AAKX-083CA0 500GB         | 2         | 2      | 0.35%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2         | 2      | 0.35%   |
| WDC WD40EFRX-68N32N0 4TB            | 2         | 5      | 0.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 129       | 186    | 24.07%  |
| WDC                  | 121       | 228    | 22.57%  |
| Samsung Electronics  | 51        | 67     | 9.51%   |
| Hitachi              | 44        | 72     | 8.21%   |
| Toshiba              | 42        | 72     | 7.84%   |
| Kingston             | 24        | 27     | 4.48%   |
| Intel                | 22        | 31     | 4.1%    |
| HGST                 | 18        | 52     | 3.36%   |
| Crucial              | 17        | 24     | 3.17%   |
| SanDisk              | 8         | 10     | 1.49%   |
| Micron Technology    | 7         | 13     | 1.31%   |
| Maxtor               | 7         | 11     | 1.31%   |
| A-DATA Technology    | 7         | 9      | 1.31%   |
| SK hynix             | 5         | 10     | 0.93%   |
| Hewlett-Packard      | 4         | 7      | 0.75%   |
| OCZ                  | 3         | 4      | 0.56%   |
| Fujitsu              | 3         | 6      | 0.56%   |
| Apple                | 3         | 3      | 0.56%   |
| LITEON               | 2         | 2      | 0.37%   |
| Corsair              | 2         | 4      | 0.37%   |
| walram               | 1         | 1      | 0.19%   |
| Transcend            | 1         | 1      | 0.19%   |
| SSSTC                | 1         | 1      | 0.19%   |
| SPCC                 | 1         | 1      | 0.19%   |
| SMI                  | 1         | 1      | 0.19%   |
| Plextor              | 1         | 1      | 0.19%   |
| Phison               | 1         | 1      | 0.19%   |
| Netac                | 1         | 1      | 0.19%   |
| Lexar                | 1         | 2      | 0.19%   |
| Lenovo               | 1         | 1      | 0.19%   |
| IBM/Hitachi          | 1         | 1      | 0.19%   |
| HPE                  | 1         | 4      | 0.19%   |
| GK                   | 1         | 1      | 0.19%   |
| Fanxiang             | 1         | 1      | 0.19%   |
| ExcelStor Technology | 1         | 2      | 0.19%   |
| Apacer               | 1         | 1      | 0.19%   |
| AMD                  | 1         | 2      | 0.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 128       | 185    | 32.74%  |
| WDC                  | 118       | 225    | 30.18%  |
| Hitachi              | 44        | 72     | 11.25%  |
| Toshiba              | 41        | 71     | 10.49%  |
| Samsung Electronics  | 24        | 33     | 6.14%   |
| HGST                 | 18        | 52     | 4.6%    |
| Maxtor               | 7         | 11     | 1.79%   |
| Hewlett-Packard      | 3         | 6      | 0.77%   |
| Fujitsu              | 3         | 6      | 0.77%   |
| Apple                | 2         | 2      | 0.51%   |
| IBM/Hitachi          | 1         | 1      | 0.26%   |
| HPE                  | 1         | 4      | 0.26%   |
| ExcelStor Technology | 1         | 2      | 0.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 365       | 670    | 71.85%  |
| SSD  | 138       | 186    | 27.17%  |
| NVMe | 5         | 5      | 0.98%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB          | 1         | 1      | 14.29%  |
| Toshiba MG05ACA800E 8TB           | 1         | 1      | 14.29%  |
| SanDisk pSSD 16GB                 | 1         | 1      | 14.29%  |
| Samsung Electronics HM250JI 250GB | 1         | 1      | 14.29%  |
| Maxtor 6E040L0 40GB               | 1         | 1      | 14.29%  |
| Hitachi HUS724040ALE641 4TB       | 1         | 14     | 14.29%  |
| Crucial M4-CT256M4SSD1 256GB      | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| SanDisk             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Maxtor              | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 14     | 14.29%  |
| Crucial             | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2235      | 7162   | 79.76%  |
| Malfunc  | 489       | 861    | 17.45%  |
| Detected | 71        | 257    | 2.53%   |
| Failed   | 7         | 20     | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1773      | 48.92%  |
| AMD                                     | 482       | 13.3%   |
| Samsung Electronics                     | 320       | 8.83%   |
| Broadcom / LSI                          | 179       | 4.94%   |
| SanDisk                                 | 131       | 3.61%   |
| Marvell Technology Group                | 74        | 2.04%   |
| ASMedia Technology                      | 74        | 2.04%   |
| Phison Electronics                      | 57        | 1.57%   |
| Kingston Technology Company             | 52        | 1.43%   |
| Silicon Motion                          | 49        | 1.35%   |
| Micron/Crucial Technology               | 45        | 1.24%   |
| SK hynix                                | 44        | 1.21%   |
| Nvidia                                  | 35        | 0.97%   |
| Toshiba                                 | 31        | 0.86%   |
| JMicron Technology                      | 30        | 0.83%   |
| Micron Technology                       | 28        | 0.77%   |
| KIOXIA                                  | 24        | 0.66%   |
| Adaptec                                 | 23        | 0.63%   |
| Hewlett-Packard                         | 19        | 0.52%   |
| ADATA Technology                        | 19        | 0.52%   |
| Realtek Semiconductor                   | 11        | 0.3%    |
| Solid State Storage Technology          | 9         | 0.25%   |
| Silicon Image                           | 9         | 0.25%   |
| MAXIO Technology (Hangzhou)             | 9         | 0.25%   |
| Shenzhen Longsys Electronics            | 8         | 0.22%   |
| VIA Technologies                        | 7         | 0.19%   |
| Union Memory (Shenzhen)                 | 7         | 0.19%   |
| Seagate Technology                      | 7         | 0.19%   |
| Lite-On Technology                      | 7         | 0.19%   |
| Chelsio Communications                  | 7         | 0.19%   |
| Areca Technology                        | 7         | 0.19%   |
| Silicon Integrated Systems [SiS]        | 6         | 0.17%   |
| Shenzhen Unionmemory Information System | 5         | 0.14%   |
| 3ware                                   | 5         | 0.14%   |
| Transcend                               | 4         | 0.11%   |
| Lenovo                                  | 4         | 0.11%   |
| INNOGRIT                                | 4         | 0.11%   |
| Integrated Technology Express           | 3         | 0.08%   |
| Broadcom                                | 3         | 0.08%   |
| ULi Electronics                         | 2         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 304       | 7.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 168       | 4.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 121       | 2.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 113       | 2.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 96        | 2.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 89        | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 85        | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 82        | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 74        | 1.77%   |
| AMD 400 Series Chipset SATA Controller                                         | 71        | 1.7%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 63        | 1.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 62        | 1.49%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 57        | 1.37%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 55        | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 50        | 1.2%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 47        | 1.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 47        | 1.13%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 46        | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                          | 46        | 1.1%    |
| Intel SATA Controller [RAID mode]                                              | 44        | 1.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 44        | 1.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 44        | 1.05%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 43        | 1.03%   |
| AMD 500 Series Chipset SATA Controller                                         | 43        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 42        | 1.01%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 41        | 0.98%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 40        | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 39        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 38        | 0.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 36        | 0.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 35        | 0.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 35        | 0.84%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 34        | 0.81%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 33        | 0.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 33        | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 32        | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 32        | 0.77%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 32        | 0.77%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 29        | 0.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 28        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1967      | 54.65%  |
| NVMe | 861       | 23.92%  |
| IDE  | 373       | 10.36%  |
| RAID | 246       | 6.84%   |
| SAS  | 113       | 3.14%   |
| SCSI | 39        | 1.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 2039      | 74.09%  |
| AMD                | 591       | 21.48%  |
| ARM                | 96        | 3.49%   |
| Unknown            | 15        | 0.55%   |
| IBM                | 3         | 0.11%   |
| VIA                | 1         | 0.04%   |
| Sun                | 1         | 0.04%   |
| Rockchip           | 1         | 0.04%   |
| Research           | 1         | 0.04%   |
| NXP                | 1         | 0.04%   |
| Motorola           | 1         | 0.04%   |
| i                  | 1         | 0.04%   |
| Baikal Electronics | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ARM Cortex-A72 r0p3                     | 33        | 1.19%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 25        | 0.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 24        | 0.87%   |
| ARM Cortex-A53 r0p4                     | 24        | 0.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 21        | 0.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 20        | 0.72%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 20        | 0.72%   |
| Intel CPU Version                       | 19        | 0.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 18        | 0.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 18        | 0.65%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 18        | 0.65%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 18        | 0.65%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 17        | 0.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 17        | 0.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 17        | 0.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 16        | 0.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 16        | 0.58%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 16        | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 16        | 0.58%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 15        | 0.54%   |
| ARM Cortex-A55 r2p0                     | 15        | 0.54%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 15        | 0.54%   |
|                                         | 15        | 0.54%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 14        | 0.51%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 14        | 0.51%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 13        | 0.47%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 13        | 0.47%   |
| AMD GX-412TC SOC                        | 13        | 0.47%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 12        | 0.43%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 12        | 0.43%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 12        | 0.43%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 12        | 0.43%   |
| Intel Xeon                              | 11        | 0.4%    |
| Intel Core i7-10700K CPU @ 3.80GHz      | 11        | 0.4%    |
| Intel Core i7-10510U CPU @ 1.80GHz      | 11        | 0.4%    |
| Intel Core i5-7300U CPU @ 2.60GHz       | 11        | 0.4%    |
| AMD Ryzen 9 5950X 16-Core Processor     | 11        | 0.4%    |
| AMD Ryzen 7 4800H with Radeon Graphics  | 11        | 0.4%    |
| AMD Ryzen 7 2700X Eight-Core Processor  | 11        | 0.4%    |
| AMD FX-8350 Eight-Core Processor        | 11        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 539       | 19.54%  |
| Intel Core i7          | 449       | 16.28%  |
| Intel Xeon             | 288       | 10.44%  |
| Other                  | 205       | 7.43%   |
| AMD Ryzen 7            | 140       | 5.08%   |
| Intel Core i3          | 128       | 4.64%   |
| Intel Celeron          | 127       | 4.6%    |
| AMD Ryzen 5            | 106       | 3.84%   |
| ARM Cortex             | 88        | 3.19%   |
| Intel Core 2 Duo       | 84        | 3.05%   |
| Intel Atom             | 65        | 2.36%   |
| AMD Ryzen 9            | 59        | 2.14%   |
| Intel Pentium          | 52        | 1.89%   |
| AMD FX                 | 32        | 1.16%   |
| AMD Ryzen 3            | 29        | 1.05%   |
| AMD GX                 | 25        | 0.91%   |
| Intel Core 2 Quad      | 17        | 0.62%   |
| AMD Ryzen 7 PRO        | 17        | 0.62%   |
| Intel Xeon Silver      | 16        | 0.58%   |
| Intel Pentium 4        | 16        | 0.58%   |
| Intel Core 2           | 14        | 0.51%   |
| AMD Ryzen 5 PRO        | 14        | 0.51%   |
| AMD EPYC               | 14        | 0.51%   |
| Intel Pentium M        | 13        | 0.47%   |
| Intel Core i9          | 13        | 0.47%   |
| AMD Opteron            | 12        | 0.44%   |
| Intel Pentium Silver   | 11        | 0.4%    |
| AMD Ryzen Threadripper | 11        | 0.4%    |
| AMD Athlon             | 10        | 0.36%   |
| AMD Athlon 64 X2       | 9         | 0.33%   |
| AMD Turion II Neo      | 8         | 0.29%   |
| Intel Pentium Dual     | 7         | 0.25%   |
| Intel Genuine          | 7         | 0.25%   |
| AMD Phenom II X6       | 7         | 0.25%   |
| AMD Phenom II X4       | 7         | 0.25%   |
| AMD E                  | 7         | 0.25%   |
| AMD A6                 | 7         | 0.25%   |
| AMD A4                 | 7         | 0.25%   |
| AMD A10                | 7         | 0.25%   |
| Intel Xeon Gold        | 6         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 876       | 31.73%  |
| 2       | 753       | 27.27%  |
| Unknown | 253       | 9.16%   |
| 8       | 204       | 7.39%   |
| 16      | 193       | 6.99%   |
| 6       | 160       | 5.8%    |
| 12      | 121       | 4.38%   |
| 1       | 60        | 2.17%   |
| 24      | 42        | 1.52%   |
| 32      | 33        | 1.2%    |
| 10      | 24        | 0.87%   |
| 20      | 15        | 0.54%   |
| 64      | 6         | 0.22%   |
| 14      | 6         | 0.22%   |
| 28      | 4         | 0.14%   |
| 48      | 2         | 0.07%   |
| 22      | 2         | 0.07%   |
| 3       | 2         | 0.07%   |
| 128     | 1         | 0.04%   |
| 40      | 1         | 0.04%   |
| 36      | 1         | 0.04%   |
| 11      | 1         | 0.04%   |
| 5       | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2487      | 90.4%   |
| 2       | 154       | 5.6%    |
| Unknown | 109       | 3.96%   |
| 4       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1371      | 49.76%  |
| 1       | 1102      | 40%     |
| Unknown | 282       | 10.24%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 392       | 14.22%  |
| Unknown         | 272       | 9.87%   |
| Haswell         | 226       | 8.2%    |
| IvyBridge       | 214       | 7.76%   |
| SandyBridge     | 185       | 6.71%   |
| Skylake         | 176       | 6.39%   |
| Zen 2           | 121       | 4.39%   |
| Broadwell       | 102       | 3.7%    |
| Penryn          | 101       | 3.66%   |
| Zen 3           | 88        | 3.19%   |
| Westmere        | 82        | 2.98%   |
| Silvermont      | 76        | 2.76%   |
| Zen+            | 75        | 2.72%   |
| Core            | 72        | 2.61%   |
| CometLake       | 68        | 2.47%   |
| TigerLake       | 63        | 2.29%   |
| Zen             | 60        | 2.18%   |
| Bonnell         | 56        | 2.03%   |
| K10             | 44        | 1.6%    |
| Piledriver      | 39        | 1.42%   |
| Nehalem         | 34        | 1.23%   |
| Puma            | 29        | 1.05%   |
| Goldmont plus   | 29        | 1.05%   |
| NetBurst        | 25        | 0.91%   |
| P6              | 19        | 0.69%   |
| Goldmont        | 19        | 0.69%   |
| Excavator       | 19        | 0.69%   |
| Bobcat          | 17        | 0.62%   |
| K8 Hammer       | 16        | 0.58%   |
| Jaguar          | 13        | 0.47%   |
| IceLake         | 11        | 0.4%    |
| Bulldozer       | 4         | 0.15%   |
| Steamroller     | 3         | 0.11%   |
| K8 & K10 hybrid | 2         | 0.07%   |
| K10 Llano       | 2         | 0.07%   |
| Geode           | 2         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1419      | 48.6%   |
| Nvidia                                       | 647       | 22.16%  |
| AMD                                          | 589       | 20.17%  |
| Matrox Electronics Systems                   | 157       | 5.38%   |
| ASPEED Technology                            | 96        | 3.29%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.1%    |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.07%   |
| VIA Technologies                             | 2         | 0.07%   |
| S3 Graphics                                  | 2         | 0.07%   |
| Silicon Motion                               | 1         | 0.03%   |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.03%   |
| Huawei Technologies                          | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 115       | 3.81%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 96        | 3.18%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 90        | 2.98%   |
| Intel UHD Graphics 620                                                                   | 66        | 2.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 61        | 2.02%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 58        | 1.92%   |
| Intel HD Graphics 5500                                                                   | 58        | 1.92%   |
| Intel HD Graphics 620                                                                    | 55        | 1.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 54        | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 53        | 1.76%   |
| Intel HD Graphics 530                                                                    | 49        | 1.62%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 46        | 1.53%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 46        | 1.53%   |
| Intel HD Graphics 630                                                                    | 44        | 1.46%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 44        | 1.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 42        | 1.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 40        | 1.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 40        | 1.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 39        | 1.29%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 37        | 1.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 37        | 1.23%   |
| Matrox Electronics Systems G200eR2                                                       | 35        | 1.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 35        | 1.16%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 33        | 1.09%   |
| Intel Core Processor Integrated Graphics Controller                                      | 32        | 1.06%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 31        | 1.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 28        | 0.93%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 28        | 0.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 28        | 0.93%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 26        | 0.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 26        | 0.86%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 25        | 0.83%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 25        | 0.83%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 23        | 0.76%   |
| Matrox Electronics Systems MGA G200EH                                                    | 23        | 0.76%   |
| AMD Lucienne                                                                             | 23        | 0.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 22        | 0.73%   |
| AMD ES1000                                                                               | 21        | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 20        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 1059      | 38.26%  |
| 1 x AMD                                  | 480       | 17.34%  |
| 1 x Nvidia                               | 400       | 14.45%  |
| Intel + Nvidia                           | 205       | 7.41%   |
| 1 x Matrox                               | 156       | 5.64%   |
| Other                                    | 141       | 5.09%   |
| 2 x Intel                                | 107       | 3.87%   |
| 1 x ASPEED                               | 83        | 3%      |
| Intel + AMD                              | 43        | 1.55%   |
| 2 x AMD                                  | 33        | 1.19%   |
| AMD + Nvidia                             | 28        | 1.01%   |
| Nvidia + ASPEED                          | 10        | 0.36%   |
| 2 x Nvidia                               | 5         | 0.18%   |
| 1 x SiS                                  | 3         | 0.11%   |
| 1 x XGI                                  | 2         | 0.07%   |
| 1 x VIA                                  | 2         | 0.07%   |
| 1 x S3 Graphics                          | 2         | 0.07%   |
| Intel + ASPEED                           | 2         | 0.07%   |
| AMD + ASPEED                             | 2         | 0.07%   |
| 1 x Silicon Motion                       | 1         | 0.04%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.04%   |
| Nvidia + Huawei Technologies             | 1         | 0.04%   |
| Intel + Matrox                           | 1         | 0.04%   |
| Intel + AMD + 1 x Nvidia                 | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2196      | 79.31%  |
| Proprietary | 418       | 15.1%   |
| Unknown     | 155       | 5.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2105      | 75.26%  |
| 1.01-2.0   | 163       | 5.83%   |
| 0.01-0.5   | 151       | 5.4%    |
| 0.51-1.0   | 100       | 3.58%   |
| 3.01-4.0   | 99        | 3.54%   |
| 7.01-8.0   | 97        | 3.47%   |
| 5.01-6.0   | 41        | 1.47%   |
| 8.01-16.0  | 22        | 0.79%   |
| 2.01-3.0   | 16        | 0.57%   |
| 4.01-5.0   | 2         | 0.07%   |
| 16.01-24.0 | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 198       | 11.7%   |
| Samsung Electronics     | 178       | 10.51%  |
| LG Display              | 155       | 9.16%   |
| Dell                    | 139       | 8.21%   |
| BOE                     | 121       | 7.15%   |
| Chimei Innolux          | 112       | 6.62%   |
| Goldstar                | 81        | 4.78%   |
| Lenovo                  | 62        | 3.66%   |
| Hewlett-Packard         | 53        | 3.13%   |
| Acer                    | 52        | 3.07%   |
| AOC                     | 45        | 2.66%   |
| Apple                   | 37        | 2.19%   |
| BenQ                    | 34        | 2.01%   |
| Philips                 | 32        | 1.89%   |
| Sharp                   | 31        | 1.83%   |
| Ancor Communications    | 31        | 1.83%   |
| Iiyama                  | 27        | 1.59%   |
| ViewSonic               | 24        | 1.42%   |
| LG Electronics          | 21        | 1.24%   |
| Sony                    | 15        | 0.89%   |
| InfoVision              | 13        | 0.77%   |
| Chi Mei Optoelectronics | 12        | 0.71%   |
| NEC Computers           | 11        | 0.65%   |
| Eizo                    | 11        | 0.65%   |
| Unknown                 | 9         | 0.53%   |
| LG Philips              | 9         | 0.53%   |
| ASUSTek Computer        | 9         | 0.53%   |
| Sceptre Tech            | 8         | 0.47%   |
| PANDA                   | 8         | 0.47%   |
| LGD                     | 8         | 0.47%   |
| Idek Iiyama             | 8         | 0.47%   |
| CSO                     | 8         | 0.47%   |
| Unknown                 | 8         | 0.47%   |
| Toshiba                 | 6         | 0.35%   |
| MSI                     | 6         | 0.35%   |
| Panasonic               | 5         | 0.3%    |
| JDI                     | 5         | 0.3%    |
| BOE Technology Group    | 5         | 0.3%    |
| Lenovo Group Limited    | 4         | 0.24%   |
| HPN                     | 4         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 12        | 0.68%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 8         | 0.45%   |
| Unknown                                                              | 8         | 0.45%   |
| MSI G241 MSI3BA4 1920x1080 530x300mm 24.0-inch                       | 6         | 0.34%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch              | 6         | 0.34%   |
| Iiyama PL2775HD IVM6604 1920x1080 600x340mm 27.2-inch                | 6         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 6         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 6         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 6         | 0.34%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 6         | 0.34%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 6         | 0.34%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 5         | 0.28%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 5         | 0.28%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 5         | 0.28%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 5         | 0.28%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 5         | 0.28%   |
| BOE Technology Group LCD Monitor 1920x1080                           | 5         | 0.28%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch       | 5         | 0.28%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch        | 5         | 0.28%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 5         | 0.28%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 5         | 0.28%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch       | 5         | 0.28%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch        | 4         | 0.23%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch              | 4         | 0.23%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch       | 4         | 0.23%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 4         | 0.23%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 4         | 0.23%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 4         | 0.23%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch          | 4         | 0.23%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch          | 4         | 0.23%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                | 4         | 0.23%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch             | 4         | 0.23%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 4         | 0.23%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch              | 4         | 0.23%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 4         | 0.23%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                | 4         | 0.23%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 4         | 0.23%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                    | 4         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch     | 4         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 310x170mm 13.9-inch     | 4         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 700       | 42.32%  |
| 1366x768 (WXGA)    | 246       | 14.87%  |
| 3840x2160 (4K)     | 113       | 6.83%   |
| 2560x1440 (QHD)    | 103       | 6.23%   |
| 1920x1200 (WUXGA)  | 77        | 4.66%   |
| 1600x900 (HD+)     | 65        | 3.93%   |
| 1280x1024 (SXGA)   | 49        | 2.96%   |
| 1280x800 (WXGA)    | 38        | 2.3%    |
| 1440x900 (WXGA+)   | 31        | 1.87%   |
| 1680x1050 (WSXGA+) | 30        | 1.81%   |
| Unknown            | 30        | 1.81%   |
| 2560x1600          | 21        | 1.27%   |
| 2560x1080          | 19        | 1.15%   |
| 3440x1440          | 17        | 1.03%   |
| 1024x600           | 17        | 1.03%   |
| 1024x768 (XGA)     | 9         | 0.54%   |
| 1600x1200          | 8         | 0.48%   |
| 3840x1080          | 7         | 0.42%   |
| 2256x1504          | 7         | 0.42%   |
| 3200x1800 (QHD+)   | 5         | 0.3%    |
| 2880x1800          | 5         | 0.3%    |
| 2160x1440          | 4         | 0.24%   |
| 1920x540           | 4         | 0.24%   |
| 3840x1200          | 3         | 0.18%   |
| 3000x2000          | 3         | 0.18%   |
| 1360x768           | 3         | 0.18%   |
| 1280x720 (HD)      | 3         | 0.18%   |
| 5760x2160          | 2         | 0.12%   |
| 5760x1080          | 2         | 0.12%   |
| 3840x1600          | 2         | 0.12%   |
| 1400x1050          | 2         | 0.12%   |
| 8960x1440          | 1         | 0.06%   |
| 7860x2400          | 1         | 0.06%   |
| 7680x2160          | 1         | 0.06%   |
| 5760x1256          | 1         | 0.06%   |
| 5760x1200          | 1         | 0.06%   |
| 5440x1080          | 1         | 0.06%   |
| 5120x1440          | 1         | 0.06%   |
| 4480x1440          | 1         | 0.06%   |
| 4480x1080          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 320       | 19.06%  |
| 15      | 304       | 18.11%  |
| Unknown | 160       | 9.53%   |
| 24      | 143       | 8.52%   |
| 27      | 141       | 8.4%    |
| 21      | 83        | 4.94%   |
| 23      | 80        | 4.76%   |
| 12      | 74        | 4.41%   |
| 17      | 52        | 3.1%    |
| 19      | 45        | 2.68%   |
| 14      | 44        | 2.62%   |
| 31      | 37        | 2.2%    |
| 11      | 28        | 1.67%   |
| 22      | 22        | 1.31%   |
| 18      | 21        | 1.25%   |
| 34      | 20        | 1.19%   |
| 10      | 14        | 0.83%   |
| 20      | 12        | 0.71%   |
| 29      | 9         | 0.54%   |
| 42      | 5         | 0.3%    |
| 26      | 5         | 0.3%    |
| 25      | 5         | 0.3%    |
| 64      | 4         | 0.24%   |
| 46      | 4         | 0.24%   |
| 40      | 4         | 0.24%   |
| 32      | 4         | 0.24%   |
| 16      | 4         | 0.24%   |
| 9       | 4         | 0.24%   |
| 52      | 3         | 0.18%   |
| 43      | 3         | 0.18%   |
| 28      | 3         | 0.18%   |
| 54      | 2         | 0.12%   |
| 49      | 2         | 0.12%   |
| 48      | 2         | 0.12%   |
| 41      | 2         | 0.12%   |
| 39      | 2         | 0.12%   |
| 35      | 2         | 0.12%   |
| 33      | 2         | 0.12%   |
| 74      | 1         | 0.06%   |
| 57      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 559       | 33.78%  |
| 501-600     | 343       | 20.73%  |
| 201-300     | 247       | 14.92%  |
| Unknown     | 160       | 9.67%   |
| 401-500     | 155       | 9.37%   |
| 601-700     | 62        | 3.75%   |
| 351-400     | 58        | 3.5%    |
| 701-800     | 27        | 1.63%   |
| 1001-1500   | 20        | 1.21%   |
| 901-1000    | 11        | 0.66%   |
| 801-900     | 8         | 0.48%   |
| 101-200     | 3         | 0.18%   |
| 1501-2000   | 1         | 0.06%   |
| 1-100       | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1082      | 69.67%  |
| 16/10   | 182       | 11.72%  |
| Unknown | 150       | 9.66%   |
| 5/4     | 38        | 2.45%   |
| 3/2     | 33        | 2.12%   |
| 21/9    | 31        | 2%      |
| 4/3     | 26        | 1.67%   |
| 6/5     | 4         | 0.26%   |
| 32/9    | 2         | 0.13%   |
| 3.18    | 1         | 0.06%   |
| 11/10   | 1         | 0.06%   |
| 1.96    | 1         | 0.06%   |
| 1.00    | 1         | 0.06%   |
| 0.46    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 299       | 17.95%  |
| 201-250        | 264       | 15.85%  |
| 91-100         | 223       | 13.39%  |
| Unknown        | 160       | 9.6%    |
| 301-350        | 148       | 8.88%   |
| 101-110        | 76        | 4.56%   |
| 61-70          | 73        | 4.38%   |
| 351-500        | 71        | 4.26%   |
| 151-200        | 64        | 3.84%   |
| 251-300        | 58        | 3.48%   |
| 71-80          | 50        | 3%      |
| 141-150        | 35        | 2.1%    |
| 121-130        | 34        | 2.04%   |
| 51-60          | 28        | 1.68%   |
| 501-1000       | 25        | 1.5%    |
| 111-120        | 21        | 1.26%   |
| 41-50          | 15        | 0.9%    |
| More than 1000 | 14        | 0.84%   |
| 1-40           | 4         | 0.24%   |
| 131-140        | 4         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 471       | 28.75%  |
| 121-160       | 463       | 28.27%  |
| 101-120       | 350       | 21.37%  |
| Unknown       | 160       | 9.77%   |
| 161-240       | 141       | 8.61%   |
| More than 240 | 40        | 2.44%   |
| 1-50          | 13        | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1368      | 48.63%  |
| 0     | 1222      | 43.44%  |
| 2     | 201       | 7.15%   |
| 3     | 20        | 0.71%   |
| 4     | 2         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1662      | 43.95%  |
| Realtek Semiconductor             | 1061      | 28.05%  |
| Broadcom                          | 302       | 7.99%   |
| Qualcomm Atheros                  | 294       | 7.77%   |
| TP-Link                           | 39        | 1.03%   |
| Marvell Technology Group          | 39        | 1.03%   |
| Ralink Technology                 | 33        | 0.87%   |
| MediaTek                          | 24        | 0.63%   |
| Mellanox Technologies             | 22        | 0.58%   |
| Ralink                            | 20        | 0.53%   |
| Samsung Electronics               | 17        | 0.45%   |
| Edimax Technology                 | 16        | 0.42%   |
| Sierra Wireless                   | 15        | 0.4%    |
| Nvidia                            | 15        | 0.4%    |
| Xiaomi                            | 13        | 0.34%   |
| D-Link System                     | 11        | 0.29%   |
| Aquantia                          | 11        | 0.29%   |
| Dell                              | 10        | 0.26%   |
| VIA Technologies                  | 9         | 0.24%   |
| Hewlett-Packard                   | 9         | 0.24%   |
| Ericsson Business Mobile Networks | 9         | 0.24%   |
| American Megatrends               | 9         | 0.24%   |
| Chelsio Communications            | 7         | 0.19%   |
| IBM                               | 6         | 0.16%   |
| Huawei Technologies               | 6         | 0.16%   |
| Google                            | 6         | 0.16%   |
| ASUSTek Computer                  | 6         | 0.16%   |
| Apple                             | 6         | 0.16%   |
| Qualcomm                          | 5         | 0.13%   |
| D-Link                            | 5         | 0.13%   |
| Arduino SA                        | 5         | 0.13%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.11%   |
| NetGear                           | 4         | 0.11%   |
| Emulex                            | 4         | 0.11%   |
| 3Com                              | 4         | 0.11%   |
| Qualcomm Technologies             | 3         | 0.08%   |
| OPPO Electronics                  | 3         | 0.08%   |
| JMicron Technology                | 3         | 0.08%   |
| IMC Networks                      | 3         | 0.08%   |
| Dresden Elektronik                | 3         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 764       | 16.38%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 150       | 3.22%   |
| Intel I211 Gigabit Network Connection                                  | 113       | 2.42%   |
| Intel Wireless 8265 / 8275                                             | 108       | 2.32%   |
| Intel Wi-Fi 6 AX200                                                    | 106       | 2.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 103       | 2.21%   |
| Intel I210 Gigabit Network Connection                                  | 84        | 1.8%    |
| Intel Wireless 8260                                                    | 69        | 1.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 69        | 1.48%   |
| Intel 82574L Gigabit Network Connection                                | 69        | 1.48%   |
| Realtek RTL8125 2.5GbE Controller                                      | 68        | 1.46%   |
| Intel Wireless 7265                                                    | 66        | 1.41%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 62        | 1.33%   |
| Intel I350 Gigabit Network Connection                                  | 56        | 1.2%    |
| Intel Wi-Fi 6 AX201                                                    | 51        | 1.09%   |
| Intel Ethernet Connection I217-LM                                      | 51        | 1.09%   |
| Intel Wireless 7260                                                    | 50        | 1.07%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 43        | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                  | 42        | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 41        | 0.88%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 40        | 0.86%   |
| Intel Ethernet Controller I225-V                                       | 39        | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 38        | 0.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 37        | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                                  | 37        | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 37        | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 32        | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 32        | 0.69%   |
| Intel Ethernet Connection I219-LM                                      | 31        | 0.66%   |
| Intel Ethernet Connection (4) I219-V                                   | 31        | 0.66%   |
| Intel Ethernet Connection (2) I219-V                                   | 29        | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 29        | 0.62%   |
| Intel 82579V Gigabit Network Connection                                | 29        | 0.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 28        | 0.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 28        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 28        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                                  | 27        | 0.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 25        | 0.54%   |
| Intel Ethernet Connection (7) I219-V                                   | 25        | 0.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 24        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 995       | 57.45%  |
| Qualcomm Atheros                      | 242       | 13.97%  |
| Realtek Semiconductor                 | 193       | 11.14%  |
| Broadcom                              | 117       | 6.76%   |
| TP-Link                               | 39        | 2.25%   |
| Ralink Technology                     | 33        | 1.91%   |
| MediaTek                              | 23        | 1.33%   |
| Ralink                                | 20        | 1.15%   |
| Edimax Technology                     | 16        | 0.92%   |
| Sierra Wireless                       | 11        | 0.64%   |
| ASUSTek Computer                      | 6         | 0.35%   |
| Dell                                  | 5         | 0.29%   |
| D-Link System                         | 5         | 0.29%   |
| D-Link                                | 5         | 0.29%   |
| NetGear                               | 4         | 0.23%   |
| Qualcomm Technologies                 | 3         | 0.17%   |
| IMC Networks                          | 3         | 0.17%   |
| Qualcomm Atheros Communications       | 2         | 0.12%   |
| Atheros                               | 2         | 0.12%   |
| AboCom Systems                        | 2         | 0.12%   |
| ZyXEL Communications                  | 1         | 0.06%   |
| Sagem                                 | 1         | 0.06%   |
| Marvell Technology Group              | 1         | 0.06%   |
| Linksys                               | 1         | 0.06%   |
| BUFFALO                               | 1         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 108       | 6.17%   |
| Intel Wi-Fi 6 AX200                                                     | 106       | 6.05%   |
| Intel Wireless 8260                                                     | 69        | 3.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 69        | 3.94%   |
| Intel Wireless 7265                                                     | 66        | 3.77%   |
| Intel Wi-Fi 6 AX201                                                     | 51        | 2.91%   |
| Intel Wireless 7260                                                     | 50        | 2.86%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 43        | 2.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 41        | 2.34%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 40        | 2.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 38        | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 37        | 2.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 37        | 2.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 32        | 1.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 32        | 1.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 29        | 1.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 28        | 1.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 28        | 1.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 28        | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 25        | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 24        | 1.37%   |
| Intel Wireless 3165                                                     | 22        | 1.26%   |
| Intel Centrino Ultimate-N 6300                                          | 22        | 1.26%   |
| Intel Wireless 3160                                                     | 21        | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 20        | 1.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 18        | 1.03%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 17        | 0.97%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 17        | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 0.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 16        | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 16        | 0.91%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 16        | 0.91%   |
| Ralink RT5370 Wireless Adapter                                          | 15        | 0.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 14        | 0.8%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 13        | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 0.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.69%   |
| Intel Centrino Advanced-N 6235                                          | 12        | 0.69%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 12        | 0.69%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 11        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 1158      | 44.33%  |
| Realtek Semiconductor                  | 959       | 36.72%  |
| Broadcom                               | 222       | 8.5%    |
| Qualcomm Atheros                       | 82        | 3.14%   |
| Marvell Technology Group               | 38        | 1.45%   |
| Samsung Electronics                    | 17        | 0.65%   |
| Nvidia                                 | 15        | 0.57%   |
| Xiaomi                                 | 13        | 0.5%    |
| Aquantia                               | 11        | 0.42%   |
| VIA Technologies                       | 9         | 0.34%   |
| American Megatrends                    | 9         | 0.34%   |
| Chelsio Communications                 | 7         | 0.27%   |
| D-Link System                          | 6         | 0.23%   |
| Qualcomm                               | 5         | 0.19%   |
| Google                                 | 5         | 0.19%   |
| Apple                                  | 5         | 0.19%   |
| Emulex                                 | 4         | 0.15%   |
| 3Com                                   | 4         | 0.15%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.11%   |
| OPPO Electronics                       | 3         | 0.11%   |
| JMicron Technology                     | 3         | 0.11%   |
| Cisco Systems                          | 3         | 0.11%   |
| AMD                                    | 3         | 0.11%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.08%   |
| Solarflare Communications              | 2         | 0.08%   |
| QLogic                                 | 2         | 0.08%   |
| MYRICOM                                | 2         | 0.08%   |
| MediaTek                               | 2         | 0.08%   |
| Lenovo                                 | 2         | 0.08%   |
| Huawei Technologies                    | 2         | 0.08%   |
| ADMtek                                 | 2         | 0.08%   |
| Accton Technology                      | 2         | 0.08%   |
| U.S. Robotics                          | 1         | 0.04%   |
| Tehuti Networks                        | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Realtek                                | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| National Semiconductor                 | 1         | 0.04%   |
| Insyde Software                        | 1         | 0.04%   |
| HMD Global                             | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 764       | 27.31%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 150       | 5.36%   |
| Intel I211 Gigabit Network Connection                                         | 113       | 4.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 103       | 3.68%   |
| Intel I210 Gigabit Network Connection                                         | 84        | 3%      |
| Intel 82574L Gigabit Network Connection                                       | 69        | 2.47%   |
| Realtek RTL8125 2.5GbE Controller                                             | 63        | 2.25%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 62        | 2.22%   |
| Intel I350 Gigabit Network Connection                                         | 56        | 2%      |
| Intel Ethernet Connection I217-LM                                             | 51        | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                                         | 42        | 1.5%    |
| Intel Ethernet Controller I225-V                                              | 39        | 1.39%   |
| Intel Ethernet Connection (4) I219-LM                                         | 37        | 1.32%   |
| Intel Ethernet Connection I219-LM                                             | 31        | 1.11%   |
| Intel Ethernet Connection (4) I219-V                                          | 31        | 1.11%   |
| Intel Ethernet Connection (2) I219-V                                          | 29        | 1.04%   |
| Intel 82579V Gigabit Network Connection                                       | 29        | 1.04%   |
| Intel Ethernet Connection (3) I218-LM                                         | 27        | 0.96%   |
| Intel Ethernet Connection (7) I219-V                                          | 25        | 0.89%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 23        | 0.82%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 23        | 0.82%   |
| Intel Ethernet Connection (7) I219-LM                                         | 20        | 0.71%   |
| Intel 82576 Gigabit Network Connection                                        | 20        | 0.71%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 19        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 17        | 0.61%   |
| Intel Ethernet Connection I218-LM                                             | 16        | 0.57%   |
| Intel Ethernet Connection (2) I218-V                                          | 16        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                                      | 15        | 0.54%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 14        | 0.5%    |
| Intel Ethernet Connection I219-V                                              | 14        | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                                         | 14        | 0.5%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 14        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                                 | 13        | 0.46%   |
| Nvidia MCP79 Ethernet                                                         | 13        | 0.46%   |
| Intel Ethernet Controller X550                                                | 13        | 0.46%   |
| Intel Ethernet Connection (6) I219-V                                          | 13        | 0.46%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 13        | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 12        | 0.43%   |
| Intel Ethernet Connection I217-V                                              | 12        | 0.43%   |
| Intel Ethernet Connection (10) I219-V                                         | 12        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2398      | 58.66%  |
| WiFi     | 1575      | 38.53%  |
| Unknown  | 63        | 1.54%   |
| Modem    | 52        | 1.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2037      | 67.14%  |
| WiFi     | 982       | 32.37%  |
| Unknown  | 10        | 0.33%   |
| Modem    | 5         | 0.16%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1411      | 51.01%  |
| 1     | 889       | 32.14%  |
| 3     | 158       | 5.71%   |
| 4     | 130       | 4.7%    |
| 0     | 106       | 3.83%   |
| 6     | 30        | 1.08%   |
| 5     | 24        | 0.87%   |
| 8     | 7         | 0.25%   |
| 7     | 7         | 0.25%   |
| 10    | 3         | 0.11%   |
| 9     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2481      | 88.61%  |
| Yes  | 319       | 11.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 725       | 60.72%  |
| Realtek Semiconductor           | 71        | 5.95%   |
| Broadcom                        | 70        | 5.86%   |
| Qualcomm Atheros Communications | 63        | 5.28%   |
| Apple                           | 62        | 5.19%   |
| Cambridge Silicon Radio         | 39        | 3.27%   |
| IMC Networks                    | 30        | 2.51%   |
| Foxconn / Hon Hai               | 29        | 2.43%   |
| Lite-On Technology              | 22        | 1.84%   |
| ASUSTek Computer                | 20        | 1.68%   |
| Dell                            | 16        | 1.34%   |
| Hewlett-Packard                 | 12        | 1.01%   |
| MediaTek                        | 6         | 0.5%    |
| Skylight Digital                | 5         | 0.42%   |
| Alps Electric                   | 4         | 0.34%   |
| TP-Link                         | 3         | 0.25%   |
| Ralink                          | 3         | 0.25%   |
| USI                             | 2         | 0.17%   |
| Toshiba                         | 1         | 0.08%   |
| Sino Wealth Electronic          | 1         | 0.08%   |
| Shenzhen Goodix Technology      | 1         | 0.08%   |
| Realtek                         | 1         | 0.08%   |
| Ralink Technology               | 1         | 0.08%   |
| Opticis                         | 1         | 0.08%   |
| Micro Star International        | 1         | 0.08%   |
| Fujitsu                         | 1         | 0.08%   |
| Esel International              | 1         | 0.08%   |
| Creative Technology             | 1         | 0.08%   |
| Corsair                         | 1         | 0.08%   |
| Unknown                         | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 270       | 22.56%  |
| Intel AX201 Bluetooth                                       | 116       | 9.69%   |
| Intel AX200 Bluetooth                                       | 103       | 8.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 95        | 7.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 39        | 3.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 37        | 3.09%   |
| Intel AX210 Bluetooth                                       | 37        | 3.09%   |
| Realtek Bluetooth Adapter                                   | 34        | 2.84%   |
| Apple Bluetooth Host Controller                             | 32        | 2.67%   |
| Intel Wireless-AC 3168 Bluetooth                            | 28        | 2.34%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 24        | 2.01%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 23        | 1.92%   |
| Intel AX211 Bluetooth                                       | 20        | 1.67%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 15        | 1.25%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 14        | 1.17%   |
| Realtek  Bluetooth 4.2 Adapter                              | 13        | 1.09%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 11        | 0.92%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 11        | 0.92%   |
| IMC Networks Realtek Bluetooth Adapter                      | 10        | 0.84%   |
| Apple Broadcom Built-in Bluetooth                           | 10        | 0.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 9         | 0.75%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 8         | 0.67%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 8         | 0.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 8         | 0.67%   |
| Dell DW375 Bluetooth Module                                 | 8         | 0.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 7         | 0.58%   |
| Lite-On Atheros AR3012 Bluetooth                            | 7         | 0.58%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 7         | 0.58%   |
| Realtek Bluetooth 4.2 Adapter                               | 6         | 0.5%    |
| Realtek Bluetooth 4.0 Adapter                               | 6         | 0.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 6         | 0.5%    |
| Apple Built-in iSight (no firmware loaded)                  | 6         | 0.5%    |
| Skylight Digital Realtek Bluetooth Adapter                  | 5         | 0.42%   |
| Realtek RTL8723B Bluetooth                                  | 5         | 0.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 5         | 0.42%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 5         | 0.42%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 5         | 0.42%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 5         | 0.42%   |
| MediaTek RZ608 Bluetooth Adapter                            | 4         | 0.33%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 4         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1648      | 54.82%  |
| AMD                                          | 622       | 20.69%  |
| Nvidia                                       | 475       | 15.8%   |
| C-Media Electronics                          | 36        | 1.2%    |
| Logitech                                     | 26        | 0.86%   |
| Creative Labs                                | 18        | 0.6%    |
| Texas Instruments                            | 14        | 0.47%   |
| Lenovo                                       | 13        | 0.43%   |
| Realtek Semiconductor                        | 11        | 0.37%   |
| ASUSTek Computer                             | 8         | 0.27%   |
| Plantronics                                  | 7         | 0.23%   |
| GN Netcom                                    | 7         | 0.23%   |
| Generalplus Technology                       | 7         | 0.23%   |
| SteelSeries ApS                              | 6         | 0.2%    |
| Silicon Integrated Systems [SiS]             | 6         | 0.2%    |
| Kingston Technology                          | 6         | 0.2%    |
| JMTek                                        | 6         | 0.2%    |
| Focusrite-Novation                           | 6         | 0.2%    |
| Sony                                         | 5         | 0.17%   |
| BEHRINGER International                      | 5         | 0.17%   |
| Creative Technology                          | 4         | 0.13%   |
| Blue Microphones                             | 4         | 0.13%   |
| Thesycon Systemsoftware & Consulting         | 3         | 0.1%    |
| Tenx Technology                              | 3         | 0.1%    |
| M-Audio                                      | 3         | 0.1%    |
| Cambridge Silicon Radio                      | 3         | 0.1%    |
| Yamaha                                       | 2         | 0.07%   |
| VIA Technologies                             | 2         | 0.07%   |
| Trust                                        | 2         | 0.07%   |
| Samsung Electronics                          | 2         | 0.07%   |
| Microsoft                                    | 2         | 0.07%   |
| Micro Star International                     | 2         | 0.07%   |
| Huawei Technologies                          | 2         | 0.07%   |
| FiiO Electronics Technology                  | 2         | 0.07%   |
| Corsair                                      | 2         | 0.07%   |
| CMX Systems                                  | 2         | 0.07%   |
| Apple                                        | 2         | 0.07%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.03%   |
| XMOS                                         | 1         | 0.03%   |
| Xilinx                                       | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 214       | 5.97%   |
| Intel Sunrise Point-LP HD Audio                                            | 198       | 5.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 150       | 4.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 148       | 4.13%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 112       | 3.12%   |
| AMD Starship/Matisse HD Audio Controller                                   | 103       | 2.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 91        | 2.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 78        | 2.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 78        | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 78        | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 71        | 1.98%   |
| Intel Broadwell-U Audio Controller                                         | 69        | 1.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 64        | 1.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 64        | 1.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 62        | 1.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 60        | 1.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 56        | 1.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 55        | 1.53%   |
| Intel 8 Series HD Audio Controller                                         | 55        | 1.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 52        | 1.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 47        | 1.31%   |
| Intel 200 Series PCH HD Audio                                              | 47        | 1.31%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 46        | 1.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 46        | 1.28%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 45        | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                               | 43        | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 39        | 1.09%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 38        | 1.06%   |
| Intel Comet Lake PCH cAVS                                                  | 36        | 1%      |
| AMD FCH Azalia Controller                                                  | 36        | 1%      |
| Nvidia GP107GL High Definition Audio Controller                            | 35        | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 33        | 0.92%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 31        | 0.86%   |
| AMD Kabini HDMI/DP Audio                                                   | 30        | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 28        | 0.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 27        | 0.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 26        | 0.72%   |
| Nvidia GP108 High Definition Audio Controller                              | 25        | 0.7%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 25        | 0.7%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 25        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 635       | 21.07%  |
| SK hynix                     | 503       | 16.69%  |
| Kingston                     | 360       | 11.94%  |
| Unknown                      | 293       | 9.72%   |
| Micron Technology            | 287       | 9.52%   |
| Crucial                      | 197       | 6.54%   |
| Corsair                      | 172       | 5.71%   |
| G.Skill                      | 95        | 3.15%   |
| Unknown                      | 69        | 2.29%   |
| Ramaxel Technology           | 48        | 1.59%   |
| A-DATA Technology            | 44        | 1.46%   |
| Elpida                       | 31        | 1.03%   |
| Nanya Technology             | 27        | 0.9%    |
| Team                         | 23        | 0.76%   |
| Transcend                    | 21        | 0.7%    |
| Patriot                      | 18        | 0.6%    |
| Hewlett-Packard              | 16        | 0.53%   |
| GOODRAM                      | 16        | 0.53%   |
| Unknown (ABCD)               | 12        | 0.4%    |
| Smart                        | 10        | 0.33%   |
| Avant                        | 9         | 0.3%    |
| PNY                          | 7         | 0.23%   |
| Patriot Memory (PDP Systems) | 7         | 0.23%   |
| Super Talent                 | 6         | 0.2%    |
| Goldkey                      | 6         | 0.2%    |
| AMD                          | 6         | 0.2%    |
| Neo Forza                    | 5         | 0.17%   |
| Apacer                       | 5         | 0.17%   |
| Toshiba                      | 4         | 0.13%   |
| Qimonda                      | 4         | 0.13%   |
| HPE                          | 4         | 0.13%   |
| 48spaces                     | 4         | 0.13%   |
| Kllisre                      | 3         | 0.1%    |
| Kingmax                      | 3         | 0.1%    |
| Golden Empire                | 3         | 0.1%    |
| ASint Technology             | 3         | 0.1%    |
| V-GeN                        | 2         | 0.07%   |
| V-Color                      | 2         | 0.07%   |
| tigo                         | 2         | 0.07%   |
| Silicon Power                | 2         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown                                                     | 69        | 2.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 23        | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 23        | 0.7%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 22        | 0.67%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s      | 19        | 0.58%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 19        | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 18        | 0.55%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s       | 18        | 0.55%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 16        | 0.49%   |
| Samsung RAM M393B1G70QH0-YK0 8192MB DIMM DDR3 1600MT/s      | 15        | 0.46%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 14        | 0.43%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s       | 14        | 0.43%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                        | 13        | 0.4%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 13        | 0.4%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 13        | 0.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 13        | 0.4%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s       | 13        | 0.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 12        | 0.37%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 11        | 0.33%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s     | 11        | 0.33%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s       | 11        | 0.33%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 11        | 0.33%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 10        | 0.3%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 10        | 0.3%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s       | 10        | 0.3%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                   | 9         | 0.27%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                        | 9         | 0.27%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 9         | 0.27%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 9         | 0.27%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 9         | 0.27%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s       | 9         | 0.27%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 8         | 0.24%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 8         | 0.24%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 8         | 0.24%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s       | 8         | 0.24%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s       | 8         | 0.24%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s      | 8         | 0.24%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 8         | 0.24%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 8         | 0.24%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 8         | 0.24%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 1117      | 42.63%  |
| DDR3         | 996       | 38.02%  |
| DDR2         | 157       | 5.99%   |
| Unknown      | 79        | 3.02%   |
| LPDDR3       | 60        | 2.29%   |
| LPDDR4       | 55        | 2.1%    |
| DDR5         | 48        | 1.83%   |
| SDRAM        | 43        | 1.64%   |
| DDR          | 36        | 1.37%   |
| LPDDR5       | 19        | 0.73%   |
| DRAM         | 7         | 0.27%   |
| SRAM         | 1         | 0.04%   |
| RAM          | 1         | 0.04%   |
| DDR2 FB-DIMM | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1252      | 47.73%  |
| DIMM            | 1191      | 45.41%  |
| Row Of Chips    | 117       | 4.46%   |
| Chip            | 35        | 1.33%   |
| Unknown         | 12        | 0.46%   |
| RIMM            | 8         | 0.3%    |
| FB-DIMM         | 7         | 0.27%   |
| Proprietary Car | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 998       | 34.81%  |
| 4096   | 722       | 25.18%  |
| 16384  | 475       | 16.57%  |
| 2048   | 361       | 12.59%  |
| 32768  | 162       | 5.65%   |
| 1024   | 105       | 3.66%   |
| 512    | 24        | 0.84%   |
| 65536  | 6         | 0.21%   |
| 256    | 5         | 0.17%   |
| 3072   | 2         | 0.07%   |
| 128    | 2         | 0.07%   |
| 131072 | 1         | 0.03%   |
| 2560   | 1         | 0.03%   |
| 64     | 1         | 0.03%   |
| 32     | 1         | 0.03%   |
| 8      | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 617       | 22.11%  |
| 3200    | 361       | 12.94%  |
| 1333    | 297       | 10.65%  |
| 2400    | 282       | 10.11%  |
| 2667    | 269       | 9.64%   |
| 2133    | 209       | 7.49%   |
| 800     | 88        | 3.15%   |
| 667     | 87        | 3.12%   |
| Unknown | 64        | 2.29%   |
| 1334    | 60        | 2.15%   |
| 1867    | 53        | 1.9%    |
| 2666    | 46        | 1.65%   |
| 1067    | 39        | 1.4%    |
| 4800    | 33        | 1.18%   |
| 1066    | 32        | 1.15%   |
| 4267    | 29        | 1.04%   |
| 2933    | 29        | 1.04%   |
| 533     | 27        | 0.97%   |
| 3600    | 25        | 0.9%    |
| 3000    | 24        | 0.86%   |
| 6400    | 18        | 0.65%   |
| 1866    | 18        | 0.65%   |
| 5600    | 12        | 0.43%   |
| 400     | 8         | 0.29%   |
| 4266    | 7         | 0.25%   |
| 975     | 7         | 0.25%   |
| 266     | 6         | 0.22%   |
| 2048    | 5         | 0.18%   |
| 3400    | 4         | 0.14%   |
| 4000    | 3         | 0.11%   |
| 1639    | 3         | 0.11%   |
| 333     | 3         | 0.11%   |
| 5200    | 2         | 0.07%   |
| 3733    | 2         | 0.07%   |
| 3534    | 2         | 0.07%   |
| 1400    | 2         | 0.07%   |
| 1332    | 2         | 0.07%   |
| 65535   | 1         | 0.04%   |
| 7500    | 1         | 0.04%   |
| 4133    | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 4         | 25%     |
| Prolific Technology | 3         | 18.75%  |
| Hewlett-Packard     | 2         | 12.5%   |
| ELGIN               | 2         | 12.5%   |
| Seiko Epson         | 1         | 6.25%   |
| Samsung Electronics | 1         | 6.25%   |
| QinHeng Electronics | 1         | 6.25%   |
| Dymo-CoStar         | 1         | 6.25%   |
| Canon               | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                                              | 3         | 18.75%  |
| ELGIN L42PRO                                                                               | 2         | 12.5%   |
| Seiko Epson Printer                                                                        | 1         | 6.25%   |
| Samsung ML-1610 Mono Laser Printer                                                         | 1         | 6.25%   |
| QinHeng CH340S                                                                             | 1         | 6.25%   |
| HP LaserJet 1012                                                                           | 1         | 6.25%   |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer | 1         | 6.25%   |
| Dymo-CoStar LabelWriter 450                                                                | 1         | 6.25%   |
| Canon LBP2900                                                                              | 1         | 6.25%   |
| Brother MFC-7360N                                                                          | 1         | 6.25%   |
| Brother HL-L5200DW series                                                                  | 1         | 6.25%   |
| Brother HL-2030 Laser Printer                                                              | 1         | 6.25%   |
| Brother HL-1430 Laser Printer                                                              | 1         | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 62.5%   |
| Seiko Epson     | 2         | 25%     |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 2         | 25%     |
| Canon CanoScan LiDE 110                                                             | 2         | 25%     |
| HP ScanJet 5300c/5370c                                                              | 1         | 12.5%   |
| Canon CanoScan LIDE 25                                                              | 1         | 12.5%   |
| Canon CanoScan LiDE 220                                                             | 1         | 12.5%   |
| Canon CanoScan LiDE 120                                                             | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 281       | 27.55%  |
| IMC Networks                           | 107       | 10.49%  |
| Microdia                               | 99        | 9.71%   |
| Bison Electronics                      | 94        | 9.22%   |
| Realtek Semiconductor                  | 78        | 7.65%   |
| Sunplus Innovation Technology          | 62        | 6.08%   |
| Logitech                               | 52        | 5.1%    |
| Lite-On Technology                     | 30        | 2.94%   |
| Suyin                                  | 26        | 2.55%   |
| Quanta                                 | 21        | 2.06%   |
| Syntek                                 | 20        | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) | 20        | 1.96%   |
| Apple                                  | 18        | 1.76%   |
| Luxvisions Innotech Limited            | 16        | 1.57%   |
| Silicon Motion                         | 10        | 0.98%   |
| Lenovo                                 | 10        | 0.98%   |
| Shenzhen Kingcome Optoelectronic       | 8         | 0.78%   |
| Z-Star Microelectronics                | 7         | 0.69%   |
| ALi                                    | 6         | 0.59%   |
| Importek                               | 5         | 0.49%   |
| Alcor Micro                            | 5         | 0.49%   |
| Ricoh                                  | 4         | 0.39%   |
| Supreme Electronics                    | 3         | 0.29%   |
| OmniVision Technologies                | 3         | 0.29%   |
| ARC International                      | 3         | 0.29%   |
| WCM_USB                                | 2         | 0.2%    |
| Unknown (3730304233435731375051)       | 2         | 0.2%    |
| Unknown                                | 2         | 0.2%    |
| Trust                                  | 2         | 0.2%    |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.2%    |
| Primax Electronics                     | 2         | 0.2%    |
| Pixart Imaging                         | 2         | 0.2%    |
| Jiangxi Shinetech Optical              | 2         | 0.2%    |
| Intel                                  | 2         | 0.2%    |
| Cubeternet                             | 2         | 0.2%    |
| YGTek                                  | 1         | 0.1%    |
| Valve Software                         | 1         | 0.1%    |
| USB Camera                             | 1         | 0.1%    |
| Sonix Technology                       | 1         | 0.1%    |
| Nam Tai E&E Products                   | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 93        | 9.01%   |
| Bison Integrated Camera                       | 52        | 5.04%   |
| IMC Networks Integrated Camera                | 41        | 3.97%   |
| Microdia Integrated_Webcam_HD                 | 28        | 2.71%   |
| Chicony HD Webcam                             | 22        | 2.13%   |
| Sunplus Integrated_Webcam_HD                  | 21        | 2.03%   |
| Realtek Integrated_Webcam_HD                  | 20        | 1.94%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 20        | 1.94%   |
| Microdia Integrated Webcam                    | 19        | 1.84%   |
| Chicony Integrated Camera (1280x720@30)       | 18        | 1.74%   |
| Logitech Webcam C270                          | 16        | 1.55%   |
| Lite-On Integrated Camera                     | 16        | 1.55%   |
| Realtek USB 2.0 PC Camera                     | 14        | 1.36%   |
| IMC Networks Realtek PC Camera                | 13        | 1.26%   |
| IMC Networks EasyCamera                       | 11        | 1.07%   |
| Bison SunplusIT Integrated Camera             | 11        | 1.07%   |
| Syntek Integrated Camera                      | 10        | 0.97%   |
| Bison Lenovo EasyCamera                       | 10        | 0.97%   |
| Luxvisions Innotech Limited Integrated Camera | 9         | 0.87%   |
| Logitech HD Pro Webcam C920                   | 9         | 0.87%   |
| Chicony Realtek DMFT RGB                      | 9         | 0.87%   |
| Chicony Integrated IR Camera                  | 9         | 0.87%   |
| Apple FaceTime HD Camera                      | 9         | 0.87%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 8         | 0.78%   |
| Chicony Chicony USB2.0 Camera                 | 8         | 0.78%   |
| Apple FaceTime HD Camera (Built-in)           | 8         | 0.78%   |
| Microdia Integrated Webcam HD                 | 7         | 0.68%   |
| Chicony ThinkPad T490 Webcam                  | 7         | 0.68%   |
| Chicony Integrated Camera [ThinkPad]          | 7         | 0.68%   |
| Chicony EasyCamera                            | 7         | 0.68%   |
| Sunplus Laptop Integrated Webcam HD           | 6         | 0.58%   |
| Realtek Integrated Webcam                     | 6         | 0.58%   |
| Quanta HD Webcam                              | 6         | 0.58%   |
| Lenovo Integrated Webcam [R5U877]             | 6         | 0.58%   |
| IMC Networks Integrated Webcam                | 6         | 0.58%   |
| Chicony Integrated HP HD Webcam               | 6         | 0.58%   |
| Syntek EasyCamera                             | 5         | 0.48%   |
| Sunplus HD WebCam                             | 5         | 0.48%   |
| Microdia USB 2.0 Camera                       | 5         | 0.48%   |
| Microdia Lenovo EasyCamera                    | 5         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 88        | 30.24%  |
| Synaptics                  | 79        | 27.15%  |
| Shenzhen Goodix Technology | 37        | 12.71%  |
| Upek                       | 22        | 7.56%   |
| Elan Microelectronics      | 14        | 4.81%   |
| AuthenTec                  | 13        | 4.47%   |
| STMicroelectronics         | 10        | 3.44%   |
| Broadcom                   | 9         | 3.09%   |
| LighTuning Technology      | 8         | 2.75%   |
| FocalTech Systems          | 8         | 2.75%   |
| Samsung Electronics        | 1         | 0.34%   |
| Fingerprint Cards          | 1         | 0.34%   |
| DigitalPersona             | 1         | 0.34%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                                 | 33        | 11.34%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                                  | 27        | 9.28%   |
| Validity Sensors VFS 5011 fingerprint sensor                                      | 26        | 8.93%   |
| Shenzhen Goodix Fingerprint Reader                                                | 26        | 8.93%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                            | 22        | 7.56%   |
| Validity Sensors Synaptics WBDI                                                   | 21        | 7.22%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                                 | 13        | 4.47%   |
| Elan Fingerprint Sensor                                                           | 12        | 4.12%   |
| STMicroelectronics Fingerprint Reader                                             | 10        | 3.44%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor      | 9         | 3.09%   |
| Validity Sensors VFS5011 Fingerprint Reader                                       | 8         | 2.75%   |
| Validity Sensors VFS495 Fingerprint Reader                                        | 7         | 2.41%   |
| Shenzhen Goodix  Fingerprint Device                                               | 7         | 2.41%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                                  | 6         | 2.06%   |
| FocalTech Systems Fingerprint Reader                                              | 6         | 2.06%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                       | 5         | 1.72%   |
| AuthenTec AES2810                                                                 | 5         | 1.72%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                          | 4         | 1.37%   |
| Shenzhen Goodix Fingerprint Reader SGX                                            | 4         | 1.37%   |
| AuthenTec AES1660                                                                 | 4         | 1.37%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                         | 3         | 1.03%   |
| AuthenTec AES2501 Fingerprint Sensor                                              | 3         | 1.03%   |
| Validity Sensors VFS491                                                           | 2         | 0.69%   |
| Validity Sensors VFS471 Fingerprint Reader                                        | 2         | 0.69%   |
| Validity Sensors VFS Fingerprint sensor                                           | 2         | 0.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint        | 2         | 0.69%   |
| Synaptics WBDI                                                                    | 2         | 0.69%   |
| Synaptics UWP WBDI                                                                | 2         | 0.69%   |
| Synaptics Fingerprint reader [HP G6]                                              | 2         | 0.69%   |
| Elan WBF Fingerprint Sensor                                                       | 2         | 0.69%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                                 | 1         | 0.34%   |
| Validity Sensors VFS451 Fingerprint Reader                                        | 1         | 0.34%   |
| Validity Sensors VFS101 Fingerprint Reader                                        | 1         | 0.34%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                       | 1         | 0.34%   |
| Validity Sensors Fingerprint scanner                                              | 1         | 0.34%   |
| Synaptics WBDI Fingerprint Reader USB 102                                         | 1         | 0.34%   |
| Synaptics UWP WBDI Device                                                         | 1         | 0.34%   |
| Synaptics TouchPad                                                                | 1         | 0.34%   |
| Samsung CanvasBio Fingerprint Reader                                              | 1         | 0.34%   |
| FocalTech Systems FocalTech Fingerprint Device Realtek USB2.0 Finger Print Bridge | 1         | 0.34%   |

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
| 1     | 882       | 30.96%  |
| 0     | 785       | 27.55%  |
| 2     | 670       | 23.52%  |
| 3     | 345       | 12.11%  |
| 4     | 126       | 4.42%   |
| 5     | 27        | 0.95%   |
| 6     | 11        | 0.39%   |
| 7     | 2         | 0.07%   |
| 9     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1574      | 46.09%  |
| Bluetooth                | 532       | 15.58%  |
| Net/wireless             | 368       | 10.78%  |
| Fingerprint reader       | 282       | 8.26%   |
| Card reader              | 281       | 8.23%   |
| Firewire controller      | 187       | 5.48%   |
| Net/ethernet             | 53        | 1.55%   |
| Sound                    | 47        | 1.38%   |
| Network                  | 41        | 1.2%    |
| Storage                  | 24        | 0.7%    |
| Modem                    | 14        | 0.41%   |
| Dvb card                 | 6         | 0.18%   |
| Storage/raid             | 2         | 0.06%   |
| Storage/ide              | 2         | 0.06%   |
| Storage/nvme             | 1         | 0.03%   |
| Graphics card            | 1         | 0.03%   |

