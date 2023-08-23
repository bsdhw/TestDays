BSD in Australia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for BSD in Australia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Australia/Desktop/README.md) and [notebooks](/Location/Australia/Notebook/README.md).

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

Total: 406

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Protectli     | FW4B Ver                    | Desktop     | [064ee65b5c](https://bsd-hardware.info/?probe=064ee65b5c) | Aug 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [fd4046c4d9](https://bsd-hardware.info/?probe=fd4046c4d9) | Aug 07, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [f65647a6be](https://bsd-hardware.info/?probe=f65647a6be) | Aug 06, 2023 |
| Sophos        | XG                          | Firewall    | [a452891edc](https://bsd-hardware.info/?probe=a452891edc) | Aug 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [eee3c082b5](https://bsd-hardware.info/?probe=eee3c082b5) | Aug 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [e9977bfffe](https://bsd-hardware.info/?probe=e9977bfffe) | Aug 02, 2023 |
| HP            | 18E9                        | Desktop     | [04c971a0de](https://bsd-hardware.info/?probe=04c971a0de) | Jul 31, 2023 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [76ce6888f7](https://bsd-hardware.info/?probe=76ce6888f7) | Jul 29, 2023 |
| HP            | 83E1                        | Desktop     | [b211795736](https://bsd-hardware.info/?probe=b211795736) | Jul 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [64c9b0f743](https://bsd-hardware.info/?probe=64c9b0f743) | Jul 25, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [60dac781b2](https://bsd-hardware.info/?probe=60dac781b2) | Jul 24, 2023 |
| ASRock        | H570M-ITX/ac                | Desktop     | [8ac2939575](https://bsd-hardware.info/?probe=8ac2939575) | Jul 23, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [6d25aa067d](https://bsd-hardware.info/?probe=6d25aa067d) | Jul 22, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [63ab45fcb1](https://bsd-hardware.info/?probe=63ab45fcb1) | Jul 21, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BK0... | Notebook    | [01f4886e09](https://bsd-hardware.info/?probe=01f4886e09) | Jul 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [5bea9c433e](https://bsd-hardware.info/?probe=5bea9c433e) | Jul 17, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [babdc9e843](https://bsd-hardware.info/?probe=babdc9e843) | Jul 15, 2023 |
| YANYU         | H67SL                       | Desktop     | [699da6c722](https://bsd-hardware.info/?probe=699da6c722) | Jul 13, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [4274ca291e](https://bsd-hardware.info/?probe=4274ca291e) | Jul 08, 2023 |
| Gigabyte      | M85M-US2H                   | Desktop     | [e0a38ef6ad](https://bsd-hardware.info/?probe=e0a38ef6ad) | Jul 03, 2023 |
| PC Engines    | APU2                        | Desktop     | [c1272678e6](https://bsd-hardware.info/?probe=c1272678e6) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [9f6d45e43e](https://bsd-hardware.info/?probe=9f6d45e43e) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [3eb03fa8a7](https://bsd-hardware.info/?probe=3eb03fa8a7) | Jul 02, 2023 |
| HP            | 82A2                        | Desktop     | [4b8d139419](https://bsd-hardware.info/?probe=4b8d139419) | Jun 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [23cdf1d4af](https://bsd-hardware.info/?probe=23cdf1d4af) | Jun 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [a548b021da](https://bsd-hardware.info/?probe=a548b021da) | Jun 27, 2023 |
| YANYU         | H67SL                       | Desktop     | [5d5fd8a8cd](https://bsd-hardware.info/?probe=5d5fd8a8cd) | Jun 27, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [648c09752f](https://bsd-hardware.info/?probe=648c09752f) | Jun 27, 2023 |
| HP            | 18E9                        | Desktop     | [aba608120b](https://bsd-hardware.info/?probe=aba608120b) | Jun 26, 2023 |
| Shuttle       | DH370                       | Desktop     | [95eb3bd4a8](https://bsd-hardware.info/?probe=95eb3bd4a8) | Jun 24, 2023 |
| Protectli     | FW4B                        | Desktop     | [6c993e8f34](https://bsd-hardware.info/?probe=6c993e8f34) | Jun 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [940adce39f](https://bsd-hardware.info/?probe=940adce39f) | Jun 23, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [c9420276e7](https://bsd-hardware.info/?probe=c9420276e7) | Jun 23, 2023 |
| Intel         | J1900                       | Desktop     | [4a3a52030b](https://bsd-hardware.info/?probe=4a3a52030b) | Jun 15, 2023 |
| HP            | Compaq 6830s                | Notebook    | [1a06917a0f](https://bsd-hardware.info/?probe=1a06917a0f) | Jun 14, 2023 |
| Acer          | Aspire TC-230               | Desktop     | [d7eacfafe1](https://bsd-hardware.info/?probe=d7eacfafe1) | Jun 04, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [d4247f35c8](https://bsd-hardware.info/?probe=d4247f35c8) | Jun 02, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [a87429607b](https://bsd-hardware.info/?probe=a87429607b) | Jun 01, 2023 |
| Intel         | QHSW02                      | Desktop     | [ed6d01bc2b](https://bsd-hardware.info/?probe=ed6d01bc2b) | May 31, 2023 |
| Intel         | QHSW02                      | Desktop     | [9f3d95a494](https://bsd-hardware.info/?probe=9f3d95a494) | May 31, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [1587da94da](https://bsd-hardware.info/?probe=1587da94da) | May 30, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [bd3ea7e1d6](https://bsd-hardware.info/?probe=bd3ea7e1d6) | May 28, 2023 |
| Intel         | J1900                       | Desktop     | [4d849f4f34](https://bsd-hardware.info/?probe=4d849f4f34) | May 27, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [310da4e6e5](https://bsd-hardware.info/?probe=310da4e6e5) | May 26, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [f350405f61](https://bsd-hardware.info/?probe=f350405f61) | May 26, 2023 |
| Timi          | TM1701                      | Notebook    | [1dd768a721](https://bsd-hardware.info/?probe=1dd768a721) | May 25, 2023 |
| Inventec      | R CLASS A02                 | Desktop     | [85f3673aa8](https://bsd-hardware.info/?probe=85f3673aa8) | May 24, 2023 |
| Intel         | J1900                       | Desktop     | [52081bc55b](https://bsd-hardware.info/?probe=52081bc55b) | May 24, 2023 |
| Dell          | 0M9KCM A02                  | Desktop     | [932e96060f](https://bsd-hardware.info/?probe=932e96060f) | May 21, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [3abf2c7ee2](https://bsd-hardware.info/?probe=3abf2c7ee2) | May 19, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [6f7bcae20b](https://bsd-hardware.info/?probe=6f7bcae20b) | May 19, 2023 |
| Protectli     | FW2B                        | Desktop     | [aa52b30ddf](https://bsd-hardware.info/?probe=aa52b30ddf) | May 14, 2023 |
| Dell          | 07F37C A00                  | Desktop     | [a23a95f97a](https://bsd-hardware.info/?probe=a23a95f97a) | May 07, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [633fa55df0](https://bsd-hardware.info/?probe=633fa55df0) | May 07, 2023 |
| Dell          | 0YC03K A04                  | Desktop     | [979aea14cc](https://bsd-hardware.info/?probe=979aea14cc) | May 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [28253dd080](https://bsd-hardware.info/?probe=28253dd080) | Apr 28, 2023 |
| Sophos        | XG                          | Firewall    | [5202fd70b1](https://bsd-hardware.info/?probe=5202fd70b1) | Apr 23, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [68b1300903](https://bsd-hardware.info/?probe=68b1300903) | Apr 22, 2023 |
| HP            | 82B4                        | Desktop     | [b75bb5fe83](https://bsd-hardware.info/?probe=b75bb5fe83) | Apr 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [28c2a703c7](https://bsd-hardware.info/?probe=28c2a703c7) | Apr 18, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [737250a1c8](https://bsd-hardware.info/?probe=737250a1c8) | Apr 15, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [1835073ded](https://bsd-hardware.info/?probe=1835073ded) | Apr 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [41bf2600a5](https://bsd-hardware.info/?probe=41bf2600a5) | Apr 13, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [036b48e4c3](https://bsd-hardware.info/?probe=036b48e4c3) | Apr 13, 2023 |
| Acer          | Veriton X4630G              | Desktop     | [93987b345d](https://bsd-hardware.info/?probe=93987b345d) | Apr 12, 2023 |
| Acer          | Veriton M6620G              | Desktop     | [13f7e5c23b](https://bsd-hardware.info/?probe=13f7e5c23b) | Apr 07, 2023 |
| Dell          | 08VT7V A00                  | Server      | [e801f9c0de](https://bsd-hardware.info/?probe=e801f9c0de) | Apr 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [ee06e14aa2](https://bsd-hardware.info/?probe=ee06e14aa2) | Mar 29, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [459fdd8cdd](https://bsd-hardware.info/?probe=459fdd8cdd) | Mar 28, 2023 |
| HP            | 82B4                        | Desktop     | [6edc033f79](https://bsd-hardware.info/?probe=6edc033f79) | Mar 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a66dffcb5c](https://bsd-hardware.info/?probe=a66dffcb5c) | Mar 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [7db8753b08](https://bsd-hardware.info/?probe=7db8753b08) | Mar 17, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [e023282dcd](https://bsd-hardware.info/?probe=e023282dcd) | Mar 13, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [6b7cf8fcac](https://bsd-hardware.info/?probe=6b7cf8fcac) | Mar 13, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [b2176fafcf](https://bsd-hardware.info/?probe=b2176fafcf) | Mar 07, 2023 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [ca70bceb83](https://bsd-hardware.info/?probe=ca70bceb83) | Mar 05, 2023 |
| AMD           | Kabini CRB                  | Desktop     | [c9e69ff953](https://bsd-hardware.info/?probe=c9e69ff953) | Mar 03, 2023 |
| Protectli     | VP2410 10                   | Desktop     | [74eedb42ea](https://bsd-hardware.info/?probe=74eedb42ea) | Mar 03, 2023 |
| Gigabyte      | Z87X-OC-CF                  | Desktop     | [dca82c50d0](https://bsd-hardware.info/?probe=dca82c50d0) | Feb 23, 2023 |
| Acer          | Aspire TC-230               | Desktop     | [f3f963fb6a](https://bsd-hardware.info/?probe=f3f963fb6a) | Feb 22, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [02970305db](https://bsd-hardware.info/?probe=02970305db) | Feb 21, 2023 |
| ASUSTek       | H110I-PLUS D3               | Desktop     | [1f347f15e2](https://bsd-hardware.info/?probe=1f347f15e2) | Feb 19, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [81911bb61f](https://bsd-hardware.info/?probe=81911bb61f) | Feb 17, 2023 |
| ASUSTek       | H110I-PLUS D3               | Desktop     | [4d3dee18a0](https://bsd-hardware.info/?probe=4d3dee18a0) | Feb 16, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [67d58b9cde](https://bsd-hardware.info/?probe=67d58b9cde) | Feb 14, 2023 |
| Acer          | Aspire TC-230               | Desktop     | [a8ce4299ae](https://bsd-hardware.info/?probe=a8ce4299ae) | Feb 13, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [4d69517a13](https://bsd-hardware.info/?probe=4d69517a13) | Feb 07, 2023 |
| Intel         | S1200BTL E98681-352         | Server      | [31989714d5](https://bsd-hardware.info/?probe=31989714d5) | Feb 04, 2023 |
| Intel         | S1200BTL E98681-352         | Server      | [5459c67905](https://bsd-hardware.info/?probe=5459c67905) | Feb 04, 2023 |
| PC Engines    | APU2                        | Desktop     | [3bc47445d4](https://bsd-hardware.info/?probe=3bc47445d4) | Jan 26, 2023 |
| IBM           | 9210MML                     | Desktop     | [8b7e2413ee](https://bsd-hardware.info/?probe=8b7e2413ee) | Jan 25, 2023 |
| ADI Engine... | RCC-VE                      | Desktop     | [e2941c00fc](https://bsd-hardware.info/?probe=e2941c00fc) | Jan 25, 2023 |
| Supermicro    | X11SSH-F                    | Server      | [106cf811d8](https://bsd-hardware.info/?probe=106cf811d8) | Jan 25, 2023 |
| Dell          | OptiPlex 3040               | Desktop     | [9c925f4e7f](https://bsd-hardware.info/?probe=9c925f4e7f) | Jan 23, 2023 |
| Dell          | 0R5KP9 A04                  | Server      | [7b811598b5](https://bsd-hardware.info/?probe=7b811598b5) | Jan 22, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [0d3e0df928](https://bsd-hardware.info/?probe=0d3e0df928) | Jan 20, 2023 |
| Dell          | 0R5KP9 A04                  | Server      | [03a26b8a34](https://bsd-hardware.info/?probe=03a26b8a34) | Jan 20, 2023 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [6bb5667269](https://bsd-hardware.info/?probe=6bb5667269) | Jan 17, 2023 |
| HP            | 8299                        | Desktop     | [d7afab37f3](https://bsd-hardware.info/?probe=d7afab37f3) | Jan 15, 2023 |
| HP            | 8299                        | Desktop     | [7a5bbc7546](https://bsd-hardware.info/?probe=7a5bbc7546) | Jan 15, 2023 |
| Dell          | OptiPlex 3040               | Desktop     | [07abf8e8b2](https://bsd-hardware.info/?probe=07abf8e8b2) | Jan 14, 2023 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [9c1f7ead89](https://bsd-hardware.info/?probe=9c1f7ead89) | Jan 06, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b1ee757669](https://bsd-hardware.info/?probe=b1ee757669) | Jan 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5d360961d4](https://bsd-hardware.info/?probe=5d360961d4) | Jan 02, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [d5f8e71171](https://bsd-hardware.info/?probe=d5f8e71171) | Jan 02, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [50c8cb79f7](https://bsd-hardware.info/?probe=50c8cb79f7) | Dec 26, 2022 |
| HP            | 8299                        | Desktop     | [6715ee2886](https://bsd-hardware.info/?probe=6715ee2886) | Dec 24, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b19a4d1696](https://bsd-hardware.info/?probe=b19a4d1696) | Dec 23, 2022 |
| HP            | 8299                        | Desktop     | [d9eec3c9f5](https://bsd-hardware.info/?probe=d9eec3c9f5) | Dec 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [0f03a7f2ce](https://bsd-hardware.info/?probe=0f03a7f2ce) | Dec 22, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [f241237f76](https://bsd-hardware.info/?probe=f241237f76) | Dec 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [a8ec4c3ae4](https://bsd-hardware.info/?probe=a8ec4c3ae4) | Dec 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [4667028e67](https://bsd-hardware.info/?probe=4667028e67) | Dec 20, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b730e64d4a](https://bsd-hardware.info/?probe=b730e64d4a) | Dec 19, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [92593f4e79](https://bsd-hardware.info/?probe=92593f4e79) | Dec 17, 2022 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [d44c580408](https://bsd-hardware.info/?probe=d44c580408) | Dec 16, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [e199c0ec3d](https://bsd-hardware.info/?probe=e199c0ec3d) | Dec 15, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [d7d0ebf605](https://bsd-hardware.info/?probe=d7d0ebf605) | Dec 15, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [617f431099](https://bsd-hardware.info/?probe=617f431099) | Dec 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [85520bf6bf](https://bsd-hardware.info/?probe=85520bf6bf) | Dec 14, 2022 |
| HP            | 82A2                        | Desktop     | [c612b7e283](https://bsd-hardware.info/?probe=c612b7e283) | Dec 06, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [4bf1aae972](https://bsd-hardware.info/?probe=4bf1aae972) | Dec 02, 2022 |
| Shuttle       | FS81                        | Desktop     | [f714ba647f](https://bsd-hardware.info/?probe=f714ba647f) | Nov 28, 2022 |
| Protectli     | FW2B                        | Desktop     | [d15326180f](https://bsd-hardware.info/?probe=d15326180f) | Nov 10, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [9945b6b3e7](https://bsd-hardware.info/?probe=9945b6b3e7) | Nov 09, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [798219138a](https://bsd-hardware.info/?probe=798219138a) | Nov 07, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [394e873da0](https://bsd-hardware.info/?probe=394e873da0) | Nov 07, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [06a8abdbf4](https://bsd-hardware.info/?probe=06a8abdbf4) | Oct 29, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [7b330abf44](https://bsd-hardware.info/?probe=7b330abf44) | Oct 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [1f2cd1f9ea](https://bsd-hardware.info/?probe=1f2cd1f9ea) | Oct 24, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [607fcd2571](https://bsd-hardware.info/?probe=607fcd2571) | Oct 24, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [d32449b8c4](https://bsd-hardware.info/?probe=d32449b8c4) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f80953ee2f](https://bsd-hardware.info/?probe=f80953ee2f) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f27ffa7217](https://bsd-hardware.info/?probe=f27ffa7217) | Oct 16, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ae4868c65b](https://bsd-hardware.info/?probe=ae4868c65b) | Oct 15, 2022 |
| PC Engines    | apu1                        | Desktop     | [06debf0076](https://bsd-hardware.info/?probe=06debf0076) | Oct 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [6c330d9bab](https://bsd-hardware.info/?probe=6c330d9bab) | Oct 14, 2022 |
| Unknown       | YL-1900L4-V2                | Desktop     | [1f55db62cc](https://bsd-hardware.info/?probe=1f55db62cc) | Oct 12, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [ea8b1fd760](https://bsd-hardware.info/?probe=ea8b1fd760) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [9d3b9cb318](https://bsd-hardware.info/?probe=9d3b9cb318) | Oct 11, 2022 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [b164bfcf33](https://bsd-hardware.info/?probe=b164bfcf33) | Oct 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [7718c8e9ca](https://bsd-hardware.info/?probe=7718c8e9ca) | Oct 05, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [63b36c077a](https://bsd-hardware.info/?probe=63b36c077a) | Oct 05, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Desktop     | [e001150f93](https://bsd-hardware.info/?probe=e001150f93) | Oct 03, 2022 |
| IBM           | 9210MML                     | Desktop     | [a6e7d7483f](https://bsd-hardware.info/?probe=a6e7d7483f) | Oct 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [9f998deaa4](https://bsd-hardware.info/?probe=9f998deaa4) | Sep 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [ffa40a08e8](https://bsd-hardware.info/?probe=ffa40a08e8) | Sep 23, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [58caab8946](https://bsd-hardware.info/?probe=58caab8946) | Sep 14, 2022 |
| Sophos        | XG                          | Firewall    | [1540138670](https://bsd-hardware.info/?probe=1540138670) | Sep 13, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [05b5d1e01a](https://bsd-hardware.info/?probe=05b5d1e01a) | Sep 12, 2022 |
| AOpen         | iBTMx-DS R1.03 55DED10A0... | Desktop     | [50ac5c0aaf](https://bsd-hardware.info/?probe=50ac5c0aaf) | Sep 10, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [cd90f548c8](https://bsd-hardware.info/?probe=cd90f548c8) | Sep 06, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [91664c3bc1](https://bsd-hardware.info/?probe=91664c3bc1) | Sep 05, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [bb379f7083](https://bsd-hardware.info/?probe=bb379f7083) | Sep 03, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [75ec0260f9](https://bsd-hardware.info/?probe=75ec0260f9) | Aug 28, 2022 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [d448c2dd6c](https://bsd-hardware.info/?probe=d448c2dd6c) | Aug 19, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [4cc4d44e43](https://bsd-hardware.info/?probe=4cc4d44e43) | Aug 15, 2022 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [eee1d83783](https://bsd-hardware.info/?probe=eee1d83783) | Aug 14, 2022 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [9130257c6a](https://bsd-hardware.info/?probe=9130257c6a) | Aug 09, 2022 |
| Unknown       | YL-J3160L4                  | Desktop     | [aad241ba36](https://bsd-hardware.info/?probe=aad241ba36) | Aug 08, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5b88dea745](https://bsd-hardware.info/?probe=5b88dea745) | Aug 06, 2022 |
| Protectli     | VP2410                      | Desktop     | [f9b42e4a75](https://bsd-hardware.info/?probe=f9b42e4a75) | Jul 27, 2022 |
| Protectli     | VP2410                      | Desktop     | [db66cc446e](https://bsd-hardware.info/?probe=db66cc446e) | Jul 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [ee70a58bd6](https://bsd-hardware.info/?probe=ee70a58bd6) | Jul 26, 2022 |
| HP            | 8055                        | Desktop     | [269b4f3210](https://bsd-hardware.info/?probe=269b4f3210) | Jul 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [607a66e533](https://bsd-hardware.info/?probe=607a66e533) | Jul 14, 2022 |
| AZW           | GK55                        | Desktop     | [40d9df6faa](https://bsd-hardware.info/?probe=40d9df6faa) | Jul 12, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f68c3695ea](https://bsd-hardware.info/?probe=f68c3695ea) | Jul 08, 2022 |
| Firewalla     | FirewallaGold               | Firewall    | [e7d2dca92d](https://bsd-hardware.info/?probe=e7d2dca92d) | Jul 02, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [a3aff65df2](https://bsd-hardware.info/?probe=a3aff65df2) | Jun 27, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [4d4993a732](https://bsd-hardware.info/?probe=4d4993a732) | Jun 24, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7d054ce34f](https://bsd-hardware.info/?probe=7d054ce34f) | Jun 23, 2022 |
| HP            | ProLiant ML10 v2            | Desktop     | [72254b033d](https://bsd-hardware.info/?probe=72254b033d) | Jun 06, 2022 |
| Dell          | 0MGK50 A02                  | Desktop     | [1de9982d19](https://bsd-hardware.info/?probe=1de9982d19) | Jun 05, 2022 |
| AOpen         | iBTMx-DS R1.03 55DED10A0... | Desktop     | [94bdba6302](https://bsd-hardware.info/?probe=94bdba6302) | Jun 04, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [f1838b29ff](https://bsd-hardware.info/?probe=f1838b29ff) | Jun 01, 2022 |
| Dell          | G5 5590                     | Notebook    | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| Intel         | NUC9i7QNB K49245-402        | Mini pc     | [92881489e1](https://bsd-hardware.info/?probe=92881489e1) | May 22, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [fdab123532](https://bsd-hardware.info/?probe=fdab123532) | May 07, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [59083ac5ac](https://bsd-hardware.info/?probe=59083ac5ac) | May 06, 2022 |
| MSI           | 2A9C                        | Desktop     | [506b970279](https://bsd-hardware.info/?probe=506b970279) | May 03, 2022 |
| HP            | ZBook 14                    | Notebook    | [a646255b51](https://bsd-hardware.info/?probe=a646255b51) | May 02, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [3f170bdee6](https://bsd-hardware.info/?probe=3f170bdee6) | May 01, 2022 |
| Lenovo        | ThinkPad T470 20HES0ES1F    | Notebook    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| HP            | Notebook                    | Notebook    | [eea4cff90b](https://bsd-hardware.info/?probe=eea4cff90b) | Apr 27, 2022 |
| ASUSTek       | P9D-C Series                | Server      | [ac16999995](https://bsd-hardware.info/?probe=ac16999995) | Apr 22, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [76a2d4f148](https://bsd-hardware.info/?probe=76a2d4f148) | Apr 22, 2022 |
| HP            | Notebook                    | Notebook    | [eaff4f0fbf](https://bsd-hardware.info/?probe=eaff4f0fbf) | Apr 19, 2022 |
| MSI           | 2A9C                        | Desktop     | [595c9a1da2](https://bsd-hardware.info/?probe=595c9a1da2) | Apr 18, 2022 |
| MSI           | 2A9C                        | Desktop     | [7f44d30f83](https://bsd-hardware.info/?probe=7f44d30f83) | Apr 15, 2022 |
| HP            | Notebook                    | Notebook    | [6a112cfe6c](https://bsd-hardware.info/?probe=6a112cfe6c) | Apr 11, 2022 |
| HP            | Notebook                    | Notebook    | [a31dd5f48d](https://bsd-hardware.info/?probe=a31dd5f48d) | Apr 11, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e32f0f2130](https://bsd-hardware.info/?probe=e32f0f2130) | Apr 08, 2022 |
| Lenovo        | 7X08CTO1WW                  | Server      | [46c59d0de8](https://bsd-hardware.info/?probe=46c59d0de8) | Apr 08, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [c807e1d8eb](https://bsd-hardware.info/?probe=c807e1d8eb) | Apr 07, 2022 |
| Protectli     | FW4B                        | Desktop     | [a2f902524b](https://bsd-hardware.info/?probe=a2f902524b) | Apr 06, 2022 |
| Protectli     | FW4B                        | Desktop     | [af9f2d81b5](https://bsd-hardware.info/?probe=af9f2d81b5) | Apr 06, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [1800a41f61](https://bsd-hardware.info/?probe=1800a41f61) | Mar 28, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [2ea328c95d](https://bsd-hardware.info/?probe=2ea328c95d) | Mar 28, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [8f20a3214b](https://bsd-hardware.info/?probe=8f20a3214b) | Mar 25, 2022 |
| Dell          | 0F0XJ6 A06                  | Server      | [e0599f5c69](https://bsd-hardware.info/?probe=e0599f5c69) | Mar 21, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1e9ea7cdbc](https://bsd-hardware.info/?probe=1e9ea7cdbc) | Mar 19, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [8da46f8dd0](https://bsd-hardware.info/?probe=8da46f8dd0) | Mar 18, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [fa03bdabb6](https://bsd-hardware.info/?probe=fa03bdabb6) | Mar 15, 2022 |
| MSI           | MS-B1831                    | Desktop     | [346c445c21](https://bsd-hardware.info/?probe=346c445c21) | Mar 12, 2022 |
| HP            | 8103 A01                    | Mini pc     | [23b35e5b18](https://bsd-hardware.info/?probe=23b35e5b18) | Mar 10, 2022 |
| Dell          | G5 5590                     | Notebook    | [0871c1269b](https://bsd-hardware.info/?probe=0871c1269b) | Mar 07, 2022 |
| MSI           | MS-B1831                    | Desktop     | [572bb2c98c](https://bsd-hardware.info/?probe=572bb2c98c) | Mar 02, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [8d5986c1f4](https://bsd-hardware.info/?probe=8d5986c1f4) | Feb 26, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [68f6eb4328](https://bsd-hardware.info/?probe=68f6eb4328) | Feb 23, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [c1397b851e](https://bsd-hardware.info/?probe=c1397b851e) | Feb 22, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [51b0a953b5](https://bsd-hardware.info/?probe=51b0a953b5) | Feb 22, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [85441a65a9](https://bsd-hardware.info/?probe=85441a65a9) | Feb 21, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [1d9eaaaf62](https://bsd-hardware.info/?probe=1d9eaaaf62) | Feb 18, 2022 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [adcfe67709](https://bsd-hardware.info/?probe=adcfe67709) | Feb 16, 2022 |
| HP            | 8103 A01                    | Mini pc     | [d9222c59e5](https://bsd-hardware.info/?probe=d9222c59e5) | Feb 12, 2022 |
| MSI           | MS-B1831                    | Desktop     | [5bdc589f33](https://bsd-hardware.info/?probe=5bdc589f33) | Feb 10, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0cc80ca4ec](https://bsd-hardware.info/?probe=0cc80ca4ec) | Feb 07, 2022 |
| MSI           | MS-B1831                    | Desktop     | [c8072d090e](https://bsd-hardware.info/?probe=c8072d090e) | Feb 06, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [6eecbfde04](https://bsd-hardware.info/?probe=6eecbfde04) | Feb 05, 2022 |
| Dell          | Latitude E7450              | Notebook    | [8a3867f171](https://bsd-hardware.info/?probe=8a3867f171) | Feb 03, 2022 |
| Lenovo        | ThinkCentre M58 7360BB6     | Desktop     | [8751a2776e](https://bsd-hardware.info/?probe=8751a2776e) | Jan 31, 2022 |
| Dell          | 0CN7CM A09                  | Server      | [3ec53e21df](https://bsd-hardware.info/?probe=3ec53e21df) | Jan 29, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [21e1806645](https://bsd-hardware.info/?probe=21e1806645) | Jan 29, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [50b7edb511](https://bsd-hardware.info/?probe=50b7edb511) | Jan 29, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [8587a16b51](https://bsd-hardware.info/?probe=8587a16b51) | Jan 29, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [6ea3284f28](https://bsd-hardware.info/?probe=6ea3284f28) | Jan 29, 2022 |
| Lenovo        | ThinkCentre M58 7360BB6     | Desktop     | [f53622f02b](https://bsd-hardware.info/?probe=f53622f02b) | Jan 27, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b62251041b](https://bsd-hardware.info/?probe=b62251041b) | Jan 26, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d180b0d394](https://bsd-hardware.info/?probe=d180b0d394) | Jan 25, 2022 |
| HP            | 8103 A01                    | Mini pc     | [147f49ca42](https://bsd-hardware.info/?probe=147f49ca42) | Jan 22, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [94b87158aa](https://bsd-hardware.info/?probe=94b87158aa) | Jan 21, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [99d276f574](https://bsd-hardware.info/?probe=99d276f574) | Jan 18, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [53b106bbb6](https://bsd-hardware.info/?probe=53b106bbb6) | Jan 16, 2022 |
| Dell          | 0XCR8D A03                  | Desktop     | [48e9447b37](https://bsd-hardware.info/?probe=48e9447b37) | Jan 15, 2022 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [459bb6486d](https://bsd-hardware.info/?probe=459bb6486d) | Jan 13, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [e0eb7a3239](https://bsd-hardware.info/?probe=e0eb7a3239) | Jan 13, 2022 |
| HP            | 8103 A01                    | Mini pc     | [2f22679aa6](https://bsd-hardware.info/?probe=2f22679aa6) | Jan 10, 2022 |
| HP            | 1998                        | Desktop     | [1d46974005](https://bsd-hardware.info/?probe=1d46974005) | Jan 03, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [d641a4bea9](https://bsd-hardware.info/?probe=d641a4bea9) | Dec 30, 2021 |
| ASUSTek       | X99-E-10G WS                | Desktop     | [dacf7f604c](https://bsd-hardware.info/?probe=dacf7f604c) | Dec 20, 2021 |
| Intel         | SKYBAY                      | Desktop     | [40d8768e52](https://bsd-hardware.info/?probe=40d8768e52) | Dec 20, 2021 |
| Protectli     | FW6 Ver                     | Desktop     | [52ba0807f9](https://bsd-hardware.info/?probe=52ba0807f9) | Dec 17, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [bc910b229a](https://bsd-hardware.info/?probe=bc910b229a) | Dec 12, 2021 |
| Intel         | NUC7JYB J67970-400          | Mini pc     | [c55f468566](https://bsd-hardware.info/?probe=c55f468566) | Dec 12, 2021 |
| Intel         | NUC7JYB J67970-400          | Mini pc     | [82c010f13c](https://bsd-hardware.info/?probe=82c010f13c) | Dec 09, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ab56e6eca2](https://bsd-hardware.info/?probe=ab56e6eca2) | Nov 23, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [645f845f43](https://bsd-hardware.info/?probe=645f845f43) | Nov 21, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [8a8efba0b3](https://bsd-hardware.info/?probe=8a8efba0b3) | Nov 19, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [8ebeac18ca](https://bsd-hardware.info/?probe=8ebeac18ca) | Nov 19, 2021 |
| HP            | 8103 A01                    | Mini pc     | [12763190f5](https://bsd-hardware.info/?probe=12763190f5) | Nov 16, 2021 |
| HP            | 8103 A01                    | Mini pc     | [8e779b15f3](https://bsd-hardware.info/?probe=8e779b15f3) | Nov 15, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [ae2203b146](https://bsd-hardware.info/?probe=ae2203b146) | Nov 12, 2021 |
| AAEON         | EMB-H61A V1.0               | Desktop     | [f13f63617f](https://bsd-hardware.info/?probe=f13f63617f) | Nov 11, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [fc32ac51e4](https://bsd-hardware.info/?probe=fc32ac51e4) | Nov 10, 2021 |
| HP            | 8103 A01                    | Mini pc     | [a6c494cc8f](https://bsd-hardware.info/?probe=a6c494cc8f) | Nov 08, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [4d9532acfa](https://bsd-hardware.info/?probe=4d9532acfa) | Nov 07, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [2a874a33dd](https://bsd-hardware.info/?probe=2a874a33dd) | Nov 05, 2021 |
| Gateway       | DX4840                      | Desktop     | [1d2e9e175c](https://bsd-hardware.info/?probe=1d2e9e175c) | Nov 01, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [1f3657128e](https://bsd-hardware.info/?probe=1f3657128e) | Oct 30, 2021 |
| ADI Engine... | RCC-VE                      | Desktop     | [9744b5eca0](https://bsd-hardware.info/?probe=9744b5eca0) | Oct 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d2ffea0e21](https://bsd-hardware.info/?probe=d2ffea0e21) | Oct 29, 2021 |
| Supermicro    | X11SSH-F                    | Server      | [06db2a9c2f](https://bsd-hardware.info/?probe=06db2a9c2f) | Oct 29, 2021 |
| HP            | 18E9                        | Desktop     | [9c9a3a0297](https://bsd-hardware.info/?probe=9c9a3a0297) | Oct 27, 2021 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [ced0819a8e](https://bsd-hardware.info/?probe=ced0819a8e) | Oct 24, 2021 |
| ASUSTek       | P10S WS                     | Desktop     | [e2d86f8c45](https://bsd-hardware.info/?probe=e2d86f8c45) | Oct 23, 2021 |
| HP            | ProLiant ML150 G6           | Desktop     | [06b8fc5c06](https://bsd-hardware.info/?probe=06b8fc5c06) | Oct 18, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [63850e668d](https://bsd-hardware.info/?probe=63850e668d) | Oct 16, 2021 |
| Protectli     | FW4B                        | Desktop     | [e20e889703](https://bsd-hardware.info/?probe=e20e889703) | Oct 16, 2021 |
| Acer          | Veriton X4610G              | Desktop     | [2ca4d093d3](https://bsd-hardware.info/?probe=2ca4d093d3) | Oct 01, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [3fafbcecc5](https://bsd-hardware.info/?probe=3fafbcecc5) | Sep 30, 2021 |
| Dell          | 0NRF6V A01                  | Server      | [c08c97aacc](https://bsd-hardware.info/?probe=c08c97aacc) | Sep 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [2494d9d2db](https://bsd-hardware.info/?probe=2494d9d2db) | Sep 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [28bbeb8b2e](https://bsd-hardware.info/?probe=28bbeb8b2e) | Sep 26, 2021 |
| ASRock        | B560M Pro4/ac               | Desktop     | [1b057f3b7d](https://bsd-hardware.info/?probe=1b057f3b7d) | Sep 23, 2021 |
| ASRock        | B560M Pro4/ac               | Desktop     | [fcf75fc410](https://bsd-hardware.info/?probe=fcf75fc410) | Sep 23, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [be32d2981b](https://bsd-hardware.info/?probe=be32d2981b) | Sep 19, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [21e4a40d62](https://bsd-hardware.info/?probe=21e4a40d62) | Sep 18, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [49f080ea2e](https://bsd-hardware.info/?probe=49f080ea2e) | Sep 12, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [8125c50b2a](https://bsd-hardware.info/?probe=8125c50b2a) | Sep 11, 2021 |
| Protectli     | FW4B                        | Desktop     | [941392a0bb](https://bsd-hardware.info/?probe=941392a0bb) | Sep 11, 2021 |
| HP            | 8103 A01                    | Mini pc     | [341ca2f887](https://bsd-hardware.info/?probe=341ca2f887) | Sep 03, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [fa4da2509b](https://bsd-hardware.info/?probe=fa4da2509b) | Sep 03, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [97035edd33](https://bsd-hardware.info/?probe=97035edd33) | Sep 03, 2021 |
| Intel         | SandyBridge Platform        | Notebook    | [f0aaf635c3](https://bsd-hardware.info/?probe=f0aaf635c3) | Sep 02, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [ecbf097bc5](https://bsd-hardware.info/?probe=ecbf097bc5) | Sep 02, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [114ef9a519](https://bsd-hardware.info/?probe=114ef9a519) | Aug 30, 2021 |
| ASRock        | 990FX Killer                | Desktop     | [9f6f8fe218](https://bsd-hardware.info/?probe=9f6f8fe218) | Aug 22, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [aca402061b](https://bsd-hardware.info/?probe=aca402061b) | Aug 18, 2021 |
| HP            | 8103 A01                    | Mini pc     | [f02d97dbeb](https://bsd-hardware.info/?probe=f02d97dbeb) | Aug 18, 2021 |
| Foxconn       | 2ADA                        | Desktop     | [e96976b2cc](https://bsd-hardware.info/?probe=e96976b2cc) | Aug 18, 2021 |
| HP            | 1825                        | Desktop     | [970bb6f787](https://bsd-hardware.info/?probe=970bb6f787) | Aug 17, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [7b20265c8e](https://bsd-hardware.info/?probe=7b20265c8e) | Aug 14, 2021 |
| Acer          | Veriton X4610G              | Desktop     | [619dedc13e](https://bsd-hardware.info/?probe=619dedc13e) | Aug 11, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [97781253f2](https://bsd-hardware.info/?probe=97781253f2) | Aug 03, 2021 |
| Microsoft     | Surface Go                  | Tablet      | [1dfbc72509](https://bsd-hardware.info/?probe=1dfbc72509) | Jul 30, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [8e67b63c6a](https://bsd-hardware.info/?probe=8e67b63c6a) | Jul 19, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [cfb68fd411](https://bsd-hardware.info/?probe=cfb68fd411) | Jul 14, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [519168441f](https://bsd-hardware.info/?probe=519168441f) | Jul 10, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d713cecb20](https://bsd-hardware.info/?probe=d713cecb20) | Jul 10, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [dc4eb674ea](https://bsd-hardware.info/?probe=dc4eb674ea) | Jul 03, 2021 |
| Protectli     | FW2B Ver                    | Desktop     | [7b6f704247](https://bsd-hardware.info/?probe=7b6f704247) | Jun 30, 2021 |
| Dell          | 0NRF6V A01                  | Server      | [70fffc6930](https://bsd-hardware.info/?probe=70fffc6930) | Jun 22, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [53f4f785ba](https://bsd-hardware.info/?probe=53f4f785ba) | Jun 22, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [bb610333d0](https://bsd-hardware.info/?probe=bb610333d0) | Jun 22, 2021 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [cb7cbd17d0](https://bsd-hardware.info/?probe=cb7cbd17d0) | Jun 20, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [2a6f8cdb64](https://bsd-hardware.info/?probe=2a6f8cdb64) | Jun 20, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [c2cdbdb012](https://bsd-hardware.info/?probe=c2cdbdb012) | Jun 15, 2021 |
| HP            | 8103 A01                    | Mini pc     | [ffd1dd6fb1](https://bsd-hardware.info/?probe=ffd1dd6fb1) | Jun 14, 2021 |
| Protectli     | VP2410 10                   | Desktop     | [27a4d07d70](https://bsd-hardware.info/?probe=27a4d07d70) | Jun 12, 2021 |
| Protectli     | VP2410 10                   | Desktop     | [5dd0792386](https://bsd-hardware.info/?probe=5dd0792386) | Jun 12, 2021 |
| HP            | 8103 A01                    | Mini pc     | [8549e8b3c4](https://bsd-hardware.info/?probe=8549e8b3c4) | Jun 09, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [3e773132b3](https://bsd-hardware.info/?probe=3e773132b3) | Jun 06, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [700ba3f063](https://bsd-hardware.info/?probe=700ba3f063) | May 31, 2021 |
| HP            | 8103 A01                    | Mini pc     | [1b26a44944](https://bsd-hardware.info/?probe=1b26a44944) | May 31, 2021 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [10d9e99990](https://bsd-hardware.info/?probe=10d9e99990) | May 31, 2021 |
| Dell          | 0CN7CM A09                  | Server      | [92a93d51c5](https://bsd-hardware.info/?probe=92a93d51c5) | May 23, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [33b86a7df2](https://bsd-hardware.info/?probe=33b86a7df2) | May 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [7ea373882a](https://bsd-hardware.info/?probe=7ea373882a) | May 19, 2021 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [a09fbe5fcc](https://bsd-hardware.info/?probe=a09fbe5fcc) | May 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [72eb276213](https://bsd-hardware.info/?probe=72eb276213) | May 05, 2021 |
| Shuttle       | DH370                       | Desktop     | [ad380cb985](https://bsd-hardware.info/?probe=ad380cb985) | May 04, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [1c9feef8e7](https://bsd-hardware.info/?probe=1c9feef8e7) | May 03, 2021 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | Desktop     | [6a62687665](https://bsd-hardware.info/?probe=6a62687665) | May 03, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [3e211c52ea](https://bsd-hardware.info/?probe=3e211c52ea) | Apr 21, 2021 |
| Sophos        | SG                          | Firewall    | [88ea908224](https://bsd-hardware.info/?probe=88ea908224) | Apr 14, 2021 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [cb97f230b8](https://bsd-hardware.info/?probe=cb97f230b8) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [821c81e652](https://bsd-hardware.info/?probe=821c81e652) | Apr 09, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [bc3913fead](https://bsd-hardware.info/?probe=bc3913fead) | Apr 06, 2021 |
| ASUSTek       | TP500LNG                    | Notebook    | [6501322932](https://bsd-hardware.info/?probe=6501322932) | Apr 06, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [bcaa207f9b](https://bsd-hardware.info/?probe=bcaa207f9b) | Apr 05, 2021 |
| Dell          | G5 5590                     | Notebook    | [18863bc535](https://bsd-hardware.info/?probe=18863bc535) | Apr 05, 2021 |
| Sophos        | SG                          | Firewall    | [76a33ea7ea](https://bsd-hardware.info/?probe=76a33ea7ea) | Mar 28, 2021 |
| Sophos        | SG                          | Firewall    | [487e450695](https://bsd-hardware.info/?probe=487e450695) | Mar 23, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [32dfd5e52a](https://bsd-hardware.info/?probe=32dfd5e52a) | Mar 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [e66fe7a153](https://bsd-hardware.info/?probe=e66fe7a153) | Mar 21, 2021 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [bf9f69e68b](https://bsd-hardware.info/?probe=bf9f69e68b) | Mar 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [70304f9c5d](https://bsd-hardware.info/?probe=70304f9c5d) | Mar 11, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [bb7f6e1db9](https://bsd-hardware.info/?probe=bb7f6e1db9) | Mar 10, 2021 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [c88b021c05](https://bsd-hardware.info/?probe=c88b021c05) | Mar 09, 2021 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [7201058b50](https://bsd-hardware.info/?probe=7201058b50) | Mar 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [635419dc18](https://bsd-hardware.info/?probe=635419dc18) | Mar 07, 2021 |
| ASUSTek       | X99-E-10G WS                | Desktop     | [4e73497945](https://bsd-hardware.info/?probe=4e73497945) | Mar 06, 2021 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [953b768755](https://bsd-hardware.info/?probe=953b768755) | Mar 03, 2021 |
| PC Engines    | apu4                        | Desktop     | [2a3c8a81d5](https://bsd-hardware.info/?probe=2a3c8a81d5) | Mar 02, 2021 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [0951c73dba](https://bsd-hardware.info/?probe=0951c73dba) | Mar 01, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [ec20bc7cea](https://bsd-hardware.info/?probe=ec20bc7cea) | Feb 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [950cf51db1](https://bsd-hardware.info/?probe=950cf51db1) | Feb 28, 2021 |
| HP            | 8103 A01                    | Mini pc     | [d436c0a897](https://bsd-hardware.info/?probe=d436c0a897) | Feb 27, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [8fda503f16](https://bsd-hardware.info/?probe=8fda503f16) | Feb 27, 2021 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [8379cc790c](https://bsd-hardware.info/?probe=8379cc790c) | Feb 25, 2021 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [13c1f72630](https://bsd-hardware.info/?probe=13c1f72630) | Feb 24, 2021 |
| Dell          | 0XCR8D A03                  | Desktop     | [8aa33e35ad](https://bsd-hardware.info/?probe=8aa33e35ad) | Feb 21, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [1f25ddeb54](https://bsd-hardware.info/?probe=1f25ddeb54) | Feb 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [6b724a36cd](https://bsd-hardware.info/?probe=6b724a36cd) | Feb 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [baf854930a](https://bsd-hardware.info/?probe=baf854930a) | Feb 19, 2021 |
| ASRock        | B365M Pro4                  | Desktop     | [1c438d977e](https://bsd-hardware.info/?probe=1c438d977e) | Feb 18, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [be56203e79](https://bsd-hardware.info/?probe=be56203e79) | Feb 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a2833c6695](https://bsd-hardware.info/?probe=a2833c6695) | Feb 08, 2021 |
| ASUSTek       | P5E3                        | Desktop     | [1d1edd3551](https://bsd-hardware.info/?probe=1d1edd3551) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | Notebook    | [a201c5f713](https://bsd-hardware.info/?probe=a201c5f713) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | Notebook    | [d0a5d1cb86](https://bsd-hardware.info/?probe=d0a5d1cb86) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | Notebook    | [a51cf81e58](https://bsd-hardware.info/?probe=a51cf81e58) | Feb 06, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [98e358b324](https://bsd-hardware.info/?probe=98e358b324) | Feb 05, 2021 |
| Radxa         | ROCK Pi X v1.4              | Desktop     | [688c95bda6](https://bsd-hardware.info/?probe=688c95bda6) | Feb 05, 2021 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [a7b2c5457c](https://bsd-hardware.info/?probe=a7b2c5457c) | Jan 29, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [40793aaedb](https://bsd-hardware.info/?probe=40793aaedb) | Jan 26, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [a2c7bfe3a1](https://bsd-hardware.info/?probe=a2c7bfe3a1) | Jan 26, 2021 |
| Lenovo        | 312D SDK0J40700 WIN 3258... | Mini pc     | [d15116d2eb](https://bsd-hardware.info/?probe=d15116d2eb) | Jan 25, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [a344f83f2e](https://bsd-hardware.info/?probe=a344f83f2e) | Jan 25, 2021 |
| Acer          | Veriton S6610G              | Desktop     | [64587ce287](https://bsd-hardware.info/?probe=64587ce287) | Jan 23, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [a78907417f](https://bsd-hardware.info/?probe=a78907417f) | Jan 22, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [4afdd92b10](https://bsd-hardware.info/?probe=4afdd92b10) | Jan 20, 2021 |
| Toshiba       | KIRA                        | Notebook    | [1ee77fde0b](https://bsd-hardware.info/?probe=1ee77fde0b) | Jan 18, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [f51f3873ce](https://bsd-hardware.info/?probe=f51f3873ce) | Dec 25, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e8506d20e](https://bsd-hardware.info/?probe=5e8506d20e) | Dec 24, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [bf0d7fe4f1](https://bsd-hardware.info/?probe=bf0d7fe4f1) | Dec 22, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [de7d8622aa](https://bsd-hardware.info/?probe=de7d8622aa) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7f6ebffad8](https://bsd-hardware.info/?probe=7f6ebffad8) | Dec 18, 2020 |
| Lenovo        | ThinkPad T460p 20FXCTO1W... | Notebook    | [ddc907ccf4](https://bsd-hardware.info/?probe=ddc907ccf4) | Dec 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [1414d7ae80](https://bsd-hardware.info/?probe=1414d7ae80) | Dec 16, 2020 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [4e217288fe](https://bsd-hardware.info/?probe=4e217288fe) | Dec 16, 2020 |
| ASUSTek       | K72F                        | Notebook    | [321cd9d139](https://bsd-hardware.info/?probe=321cd9d139) | Dec 08, 2020 |
| ASUSTek       | K72F                        | Notebook    | [b36ff0b052](https://bsd-hardware.info/?probe=b36ff0b052) | Dec 08, 2020 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [33724c243d](https://bsd-hardware.info/?probe=33724c243d) | Dec 06, 2020 |
| HP            | Setzer                      | Notebook    | [da7914cdd5](https://bsd-hardware.info/?probe=da7914cdd5) | Nov 22, 2020 |
| Lenovo        | ThinkPad T450 20BVA020AU    | Notebook    | [5d8bce59e8](https://bsd-hardware.info/?probe=5d8bce59e8) | Nov 16, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [ec13cfdd0d](https://bsd-hardware.info/?probe=ec13cfdd0d) | Oct 29, 2020 |
| Dell          | 0TW856 A02                  | Server      | [f181777604](https://bsd-hardware.info/?probe=f181777604) | Oct 29, 2020 |
| Dell          | 042P49 A02                  | Desktop     | [c34a9c7091](https://bsd-hardware.info/?probe=c34a9c7091) | Oct 29, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [c1c3ffb720](https://bsd-hardware.info/?probe=c1c3ffb720) | Oct 29, 2020 |
| Lenovo        | ThinkPad X230 2320JXM       | Notebook    | [cdbf62a168](https://bsd-hardware.info/?probe=cdbf62a168) | Oct 29, 2020 |
| Lenovo        | ThinkPad X60s 17033JM       | Notebook    | [67e701adb7](https://bsd-hardware.info/?probe=67e701adb7) | Oct 21, 2020 |
| Unknown       | Unknown                     | Desktop     | [a28ef1d2b8](https://bsd-hardware.info/?probe=a28ef1d2b8) | Oct 20, 2020 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [af179a268f](https://bsd-hardware.info/?probe=af179a268f) | Oct 19, 2020 |
| Acer          | Peppy                       | Notebook    | [d68bd5cbb5](https://bsd-hardware.info/?probe=d68bd5cbb5) | Oct 02, 2020 |
| Acer          | Peppy                       | Notebook    | [26058cddbf](https://bsd-hardware.info/?probe=26058cddbf) | Oct 02, 2020 |
| Unknown       | Unknown                     | Desktop     | [864589fce0](https://bsd-hardware.info/?probe=864589fce0) | Oct 02, 2020 |
| Apple         | MacBookAir5,1               | Notebook    | [6cced6fcf0](https://bsd-hardware.info/?probe=6cced6fcf0) | Sep 23, 2020 |
| Lenovo        | ThinkPad T460p 20FXCTO1W... | Notebook    | [b62876dd94](https://bsd-hardware.info/?probe=b62876dd94) | Aug 04, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [e4d2dcda5b](https://bsd-hardware.info/?probe=e4d2dcda5b) | Jul 31, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [764aaaa200](https://bsd-hardware.info/?probe=764aaaa200) | Jun 04, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [158ff0f1b6](https://bsd-hardware.info/?probe=158ff0f1b6) | Jun 04, 2020 |
| Lenovo        | ThinkPad X220 4291C35       | Notebook    | [f22c83f68b](https://bsd-hardware.info/?probe=f22c83f68b) | May 31, 2020 |
| HP            | ProLiant ML10 v2            | Desktop     | [aea3696f41](https://bsd-hardware.info/?probe=aea3696f41) | May 24, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 23.1.11  | 10        | 3.01%   |
| OPNsense 22.1     | 9         | 2.71%   |
| OPNsense 22.7.10  | 8         | 2.41%   |
| OPNsense 21.7.7   | 8         | 2.41%   |
| helloSystem 0.8.1 | 8         | 2.41%   |
| helloSystem 0.5.0 | 8         | 2.41%   |
| OPNsense 22.7.6   | 7         | 2.11%   |
| OPNsense 22.1.6   | 7         | 2.11%   |
| OPNsense 23.1.8   | 6         | 1.81%   |
| OPNsense 23.1.5   | 6         | 1.81%   |
| OPNsense 23.1.10  | 6         | 1.81%   |
| OPNsense 22.7.4   | 6         | 1.81%   |
| OPNsense 21.7.1   | 6         | 1.81%   |
| OPNsense 21.1.5   | 6         | 1.81%   |
| OPNsense 21.1.4   | 6         | 1.81%   |
| OPNsense 21.1.3   | 6         | 1.81%   |
| OPNsense 20.7.8   | 6         | 1.81%   |
| helloSystem 0.4.0 | 6         | 1.81%   |
| OPNsense 23.7     | 5         | 1.51%   |
| OPNsense 22.1.10  | 5         | 1.51%   |
| OPNsense 21.7.3   | 5         | 1.51%   |
| OPNsense 21.7.2   | 5         | 1.51%   |
| OPNsense 21.1.6   | 5         | 1.51%   |
| OPNsense 21.1.2   | 5         | 1.51%   |
| helloSystem 0.6.0 | 5         | 1.51%   |
| FreeBSD 13.0      | 5         | 1.51%   |
| FreeBSD 12.2      | 5         | 1.51%   |
| FreeBSD 12.1-p10  | 5         | 1.51%   |
| OPNsense 23.1.7   | 4         | 1.2%    |
| OPNsense 23.1.4   | 4         | 1.2%    |
| OPNsense 23.1.1   | 4         | 1.2%    |
| OPNsense 23.1     | 4         | 1.2%    |
| OPNsense 22.7.9   | 4         | 1.2%    |
| OPNsense 22.1.4   | 4         | 1.2%    |
| OPNsense 21.1.1   | 4         | 1.2%    |
| OPNsense 21.1     | 4         | 1.2%    |
| OpenBSD 7.2       | 4         | 1.2%    |
| OpenBSD 6.8       | 4         | 1.2%    |
| helloSystem 0.7.0 | 4         | 1.2%    |
| FreeBSD 13.1-p5   | 4         | 1.2%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 157       | 59.92%  |
| FreeBSD     | 47        | 17.94%  |
| helloSystem | 32        | 12.21%  |
| OpenBSD     | 9         | 3.44%   |
| TrueNAS     | 5         | 1.91%   |
| NomadBSD    | 3         | 1.15%   |
| GhostBSD    | 3         | 1.15%   |
| FreeNAS     | 2         | 0.76%   |
| XigmaNAS    | 1         | 0.38%   |
| NetBSD      | 1         | 0.38%   |
| FuguIta     | 1         | 0.38%   |
| ClonOS      | 1         | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 258       | 98.85%  |
| i386  | 2         | 0.77%   |
| arm64 | 1         | 0.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 182       | 68.94%  |
| helloDesktop | 38        | 14.39%  |
| KDE5         | 12        | 4.55%   |
| XFCE         | 8         | 3.03%   |
| GNOME        | 6         | 2.27%   |
| TWM          | 4         | 1.52%   |
| fvwm         | 4         | 1.52%   |
| Openbox      | 3         | 1.14%   |
| i3           | 3         | 1.14%   |
| MATE         | 1         | 0.38%   |
| Lumina       | 1         | 0.38%   |
| Fluxbox      | 1         | 0.38%   |
| AwesomeWM    | 1         | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 187       | 71.37%  |
| X11     | 71        | 27.1%   |
| Wayland | 4         | 1.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 201       | 76.72%  |
| SLiM    | 35        | 13.36%  |
| SDDM    | 12        | 4.58%   |
| LightDM | 6         | 2.29%   |
| XDM     | 4         | 1.53%   |
| Ly      | 2         | 0.76%   |
| PCDM    | 1         | 0.38%   |
| GDM     | 1         | 0.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 181       | 68.05%  |
| en_US           | 41        | 15.41%  |
| C               | 25        | 9.4%    |
| en_AU           | 14        | 5.26%   |
| fr_FR           | 1         | 0.38%   |
| fr              | 1         | 0.38%   |
| en_AU.US-ASCII  | 1         | 0.38%   |
| en_AU.ISO8859-1 | 1         | 0.38%   |
| en              | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 214       | 81.99%  |
| BIOS | 47        | 18.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 139       | 52.26%  |
| Zfs    | 105       | 39.47%  |
| Cd9660 | 12        | 4.51%   |
| Ffs    | 10        | 3.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 239       | 91.57%  |
| MBR     | 20        | 7.66%   |
| BSD     | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo                     | 32        | 12.26%  |
| Hewlett-Packard            | 32        | 12.26%  |
| Dell                       | 32        | 12.26%  |
| ASUSTek Computer           | 19        | 7.28%   |
| Unknown                    | 19        | 7.28%   |
| Intel                      | 17        | 6.51%   |
| Protectli                  | 16        | 6.13%   |
| Gigabyte Technology        | 14        | 5.36%   |
| ASRock                     | 11        | 4.21%   |
| Acer                       | 8         | 3.07%   |
| Apple                      | 7         | 2.68%   |
| Techvision                 | 4         | 1.53%   |
| Sophos                     | 4         | 1.53%   |
| PC Engines                 | 4         | 1.53%   |
| MSI                        | 4         | 1.53%   |
| Toshiba                    | 3         | 1.15%   |
| AMI                        | 3         | 1.15%   |
| Shuttle                    | 2         | 0.77%   |
| MW                         | 2         | 0.77%   |
| Inventec                   | 2         | 0.77%   |
| ZOTAC                      | 1         | 0.38%   |
| YANYU                      | 1         | 0.38%   |
| Yanling                    | 1         | 0.38%   |
| Unknown                    | 1         | 0.38%   |
| Timi                       | 1         | 0.38%   |
| Supermicro                 | 1         | 0.38%   |
| ShenZhen MinWin Technology | 1         | 0.38%   |
| SeeedStudio                | 1         | 0.38%   |
| Samsung Electronics        | 1         | 0.38%   |
| Raspberry Pi Foundation    | 1         | 0.38%   |
| Radxa                      | 1         | 0.38%   |
| Microsoft                  | 1         | 0.38%   |
| Intel Client Systems       | 1         | 0.38%   |
| IBM                        | 1         | 0.38%   |
| HARDKERNEL                 | 1         | 0.38%   |
| Gateway                    | 1         | 0.38%   |
| Framework                  | 1         | 0.38%   |
| Foxconn                    | 1         | 0.38%   |
| Firewalla                  | 1         | 0.38%   |
| CWWK                       | 1         | 0.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 20        | 7.66%   |
| Protectli FW4B                                                                           | 10        | 3.83%   |
| HP t730 Thin Client                                                                      | 7         | 2.68%   |
| Techvision TVI7309X                                                                      | 4         | 1.53%   |
| HP ProLiant MicroServer                                                                  | 4         | 1.53%   |
| Dell OptiPlex 9020                                                                       | 4         | 1.53%   |
| Dell OptiPlex 7040                                                                       | 4         | 1.53%   |
| Sophos XG                                                                                | 3         | 1.15%   |
| Protectli VP2410                                                                         | 3         | 1.15%   |
| Dell PowerEdge R320                                                                      | 3         | 1.15%   |
| Protectli FW2B                                                                           | 2         | 0.77%   |
| PC Engines APU2                                                                          | 2         | 0.77%   |
| MW GMLK-2_5G4L                                                                           | 2         | 0.77%   |
| Intel Q3XXG4-P V1.0                                                                      | 2         | 0.77%   |
| Intel NUC10i5FNH                                                                         | 2         | 0.77%   |
| HP ProLiant MicroServer Gen8                                                             | 2         | 0.77%   |
| HP ProDesk 400 G4 SFF                                                                    | 2         | 0.77%   |
| Dell OptiPlex 3040                                                                       | 2         | 0.77%   |
| Dell OptiPlex 3010                                                                       | 2         | 0.77%   |
| ASUS STRIX Z270I GAMING                                                                  | 2         | 0.77%   |
| ASUS All Series                                                                          | 2         | 0.77%   |
| AMI Aptio CRB                                                                            | 2         | 0.77%   |
| ZOTAC ZBOX-CI323NANO                                                                     | 1         | 0.38%   |
| YANYU H67SL                                                                              | 1         | 0.38%   |
| Yanling YL-KBR6L                                                                         | 1         | 0.38%   |
| Toshiba Satellite L50-A                                                                  | 1         | 0.38%   |
| Toshiba PORTEGE Z10t-A                                                                   | 1         | 0.38%   |
| Toshiba KIRA                                                                             | 1         | 0.38%   |
| Timi TM1701                                                                              | 1         | 0.38%   |
| Supermicro Super Server                                                                  | 1         | 0.38%   |
| Sophos SG                                                                                | 1         | 0.38%   |
| Shuttle DS81D                                                                            | 1         | 0.38%   |
| Shuttle DH370                                                                            | 1         | 0.38%   |
| ShenZhen MinWin MW-NANO-APL-4L                                                           | 1         | 0.38%   |
| SeeedStudio ODYSSEY-X86J4125                                                             | 1         | 0.38%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 0.38%   |
| RPi Raspberry Pi                                                                         | 1         | 0.38%   |
| Radxa ROCK Pi X                                                                          | 1         | 0.38%   |
| Protectli FW6                                                                            | 1         | 0.38%   |
| PC Engines apu4                                                                          | 1         | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell OptiPlex                  | 20        | 7.66%   |
| Unknown                        | 20        | 7.66%   |
| Lenovo ThinkPad                | 16        | 6.13%   |
| Lenovo ThinkCentre             | 11        | 4.21%   |
| Protectli FW4B                 | 10        | 3.83%   |
| HP ProLiant                    | 8         | 3.07%   |
| HP t730                        | 7         | 2.68%   |
| Dell PowerEdge                 | 7         | 2.68%   |
| HP ProDesk                     | 5         | 1.92%   |
| HP EliteDesk                   | 5         | 1.92%   |
| Acer Veriton                   | 5         | 1.92%   |
| Techvision TVI7309X            | 4         | 1.53%   |
| Sophos XG                      | 3         | 1.15%   |
| Protectli VP2410               | 3         | 1.15%   |
| ASUS ROG                       | 3         | 1.15%   |
| ASUS PRIME                     | 3         | 1.15%   |
| Protectli FW2B                 | 2         | 0.77%   |
| PC Engines APU2                | 2         | 0.77%   |
| MW GMLK-2                      | 2         | 0.77%   |
| Lenovo IdeaPad                 | 2         | 0.77%   |
| Intel Q3XXG4-P                 | 2         | 0.77%   |
| Intel NUC10i5FNH               | 2         | 0.77%   |
| ASUS STRIX                     | 2         | 0.77%   |
| ASUS All                       | 2         | 0.77%   |
| ASRock X370                    | 2         | 0.77%   |
| AMI Aptio                      | 2         | 0.77%   |
| ZOTAC ZBOX-CI323NANO           | 1         | 0.38%   |
| YANYU H67SL                    | 1         | 0.38%   |
| Yanling YL-KBR6L               | 1         | 0.38%   |
| Toshiba Satellite              | 1         | 0.38%   |
| Toshiba PORTEGE                | 1         | 0.38%   |
| Toshiba KIRA                   | 1         | 0.38%   |
| Timi TM1701                    | 1         | 0.38%   |
| Supermicro Super               | 1         | 0.38%   |
| Sophos SG                      | 1         | 0.38%   |
| Shuttle DS81D                  | 1         | 0.38%   |
| Shuttle DH370                  | 1         | 0.38%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.38%   |
| SeeedStudio ODYSSEY-X86J4125   | 1         | 0.38%   |
| Samsung 350V5C                 | 1         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 31        | 11.88%  |
| 2019    | 28        | 10.73%  |
| 2020    | 25        | 9.58%   |
| 2021    | 21        | 8.05%   |
| 2015    | 21        | 8.05%   |
| 2016    | 20        | 7.66%   |
| 2014    | 19        | 7.28%   |
| 2013    | 19        | 7.28%   |
| 2017    | 16        | 6.13%   |
| 2022    | 14        | 5.36%   |
| 2012    | 11        | 4.21%   |
| 2011    | 11        | 4.21%   |
| 2009    | 6         | 2.3%    |
| 2010    | 5         | 1.92%   |
| 2008    | 4         | 1.53%   |
| Unknown | 4         | 1.53%   |
| 2023    | 3         | 1.15%   |
| 2007    | 2         | 0.77%   |
| 2006    | 1         | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 176       | 67.43%  |
| Notebook       | 45        | 17.24%  |
| Mini pc        | 21        | 8.05%   |
| Server         | 10        | 3.83%   |
| Firewall       | 5         | 1.92%   |
| All in one     | 2         | 0.77%   |
| System on chip | 1         | 0.38%   |
| Tablet         | 1         | 0.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 249       | 95.4%   |
| Yes  | 12        | 4.6%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 116       | 43.28%  |
| 16.01-24.0  | 68        | 25.37%  |
| 4.01-8.0    | 42        | 15.67%  |
| 32.01-64.0  | 17        | 6.34%   |
| 64.01-256.0 | 10        | 3.73%   |
| 2.01-3.0    | 6         | 2.24%   |
| 3.01-4.0    | 3         | 1.12%   |
| 24.01-32.0  | 3         | 1.12%   |
| 1.01-2.0    | 2         | 0.75%   |
| 0.51-1.0    | 1         | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 133       | 48.36%  |
| 0.51-1.0   | 83        | 30.18%  |
| 1.01-2.0   | 28        | 10.18%  |
| 2.01-3.0   | 11        | 4%      |
| 4.01-8.0   | 9         | 3.27%   |
| 8.01-16.0  | 3         | 1.09%   |
| 3.01-4.0   | 2         | 0.73%   |
| 16.01-24.0 | 2         | 0.73%   |
| 32.01-64.0 | 1         | 0.36%   |
| 24.01-32.0 | 1         | 0.36%   |
| 0          | 1         | 0.36%   |
| Unknown    | 1         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 193       | 73.11%  |
| 2      | 25        | 9.47%   |
| 0      | 18        | 6.82%   |
| 3      | 13        | 4.92%   |
| 4      | 7         | 2.65%   |
| 5      | 4         | 1.52%   |
| 7      | 2         | 0.76%   |
| 10     | 1         | 0.38%   |
| 6      | 1         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 214       | 81.99%  |
| Yes       | 47        | 18.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 248       | 95.02%  |
| No        | 13        | 4.98%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 166       | 63.36%  |
| Yes       | 96        | 36.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 191       | 72.9%   |
| Yes       | 71        | 27.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 261       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 75        | 26.69%  |
| Melbourne      | 48        | 17.08%  |
| Brisbane       | 33        | 11.74%  |
| Perth          | 31        | 11.03%  |
| Adelaide       | 14        | 4.98%   |
| Canberra       | 7         | 2.49%   |
| Hobart         | 5         | 1.78%   |
| Morwell        | 3         | 1.07%   |
| Blackburn      | 3         | 1.07%   |
| Southport      | 2         | 0.71%   |
| Ryde           | 2         | 0.71%   |
| Nyngan         | 2         | 0.71%   |
| Marrickville   | 2         | 0.71%   |
| Kooyong        | 2         | 0.71%   |
| Kellyville     | 2         | 0.71%   |
| Ipswich        | 2         | 0.71%   |
| Gold Coast     | 2         | 0.71%   |
| East Malvern   | 2         | 0.71%   |
| Burwood        | 2         | 0.71%   |
| Unknown        | 2         | 0.71%   |
| Wollongong     | 1         | 0.36%   |
| Whitebridge    | 1         | 0.36%   |
| Wheelers Hill  | 1         | 0.36%   |
| Warrnambool    | 1         | 0.36%   |
| Wallan         | 1         | 0.36%   |
| Townsville     | 1         | 0.36%   |
| South Yarra    | 1         | 0.36%   |
| Shell Cove     | 1         | 0.36%   |
| Roxby Downs    | 1         | 0.36%   |
| Rosanna        | 1         | 0.36%   |
| Ringwood       | 1         | 0.36%   |
| Port Fairy     | 1         | 0.36%   |
| Northcote      | 1         | 0.36%   |
| North Shore    | 1         | 0.36%   |
| Noble Park     | 1         | 0.36%   |
| Nickol         | 1         | 0.36%   |
| Mount Waverley | 1         | 0.36%   |
| Mount Eliza    | 1         | 0.36%   |
| Mooroolbark    | 1         | 0.36%   |
| Mandurah       | 1         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 49        | 68     | 16.28%  |
| Seagate             | 37        | 53     | 12.29%  |
| WDC                 | 32        | 81     | 10.63%  |
| Crucial             | 21        | 28     | 6.98%   |
| Kingston            | 19        | 27     | 6.31%   |
| Intel               | 19        | 29     | 6.31%   |
| Toshiba             | 16        | 22     | 5.32%   |
| SanDisk             | 12        | 20     | 3.99%   |
| Hoodisk             | 10        | 20     | 3.32%   |
| OCZ                 | 6         | 7      | 1.99%   |
| Micron Technology   | 6         | 8      | 1.99%   |
| China               | 6         | 7      | 1.99%   |
| A-DATA Technology   | 6         | 11     | 1.99%   |
| Protectli           | 4         | 4      | 1.33%   |
| SK hynix            | 3         | 5      | 1%      |
| Phison              | 3         | 3      | 1%      |
| NVMe                | 3         | 4      | 1%      |
| Hitachi             | 3         | 6      | 1%      |
| Hewlett-Packard     | 3         | 6      | 1%      |
| Dogfish             | 3         | 4      | 1%      |
| Transcend           | 2         | 4      | 0.66%   |
| SPCC                | 2         | 6      | 0.66%   |
| Silicon Motion      | 2         | 2      | 0.66%   |
| Patriot             | 2         | 2      | 0.66%   |
| KIOXIA              | 2         | 2      | 0.66%   |
| KingDian            | 2         | 2      | 0.66%   |
| HGST                | 2         | 2      | 0.66%   |
| Gigabyte Technology | 2         | 3      | 0.66%   |
| FORESEE             | 2         | 3      | 0.66%   |
| BIWIN               | 2         | 2      | 0.66%   |
| Apple               | 2         | 2      | 0.66%   |
| ZOTAC               | 1         | 1      | 0.33%   |
| XUNZHE              | 1         | 1      | 0.33%   |
| Vaseky              | 1         | 4      | 0.33%   |
| Union Memory        | 1         | 1      | 0.33%   |
| ShiJi               | 1         | 1      | 0.33%   |
| Qunion              | 1         | 2      | 0.33%   |
| PNY                 | 1         | 1      | 0.33%   |
| Plextor             | 1         | 2      | 0.33%   |
| Maxtor              | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Hoodisk SSD 128GB                           | 7         | 2.14%   |
| Samsung SSD 850 EVO 500GB                   | 4         | 1.22%   |
| Crucial CT250MX500SSD1 250GB                | 4         | 1.22%   |
| WDC WD30EFRX-68EUZN0 3TB                    | 3         | 0.92%   |
| Seagate ST500LM021-1KJ152 500GB             | 3         | 0.92%   |
| Seagate FireCuda 520 SSD ZP500GM30002 500GB | 3         | 0.92%   |
| Samsung SSD 860 EVO 500GB                   | 3         | 0.92%   |
| Samsung SSD 840 EVO 250GB                   | 3         | 0.92%   |
| Samsung SSD 840 EVO 120GB                   | 3         | 0.92%   |
| Kingston SA400S37480G 480GB                 | 3         | 0.92%   |
| Kingston SA400S37240G 240GB                 | 3         | 0.92%   |
| Kingston SA400S37120G 120GB                 | 3         | 0.92%   |
| Intel SSDSCKKW240H6 240GB                   | 3         | 0.92%   |
| Crucial CT500MX500SSD1 500GB                | 3         | 0.92%   |
| Crucial CT250P2SSD8 250GB                   | 3         | 0.92%   |
| China SATA SSD 16GB                         | 3         | 0.92%   |
| WDC WDS250G2B0A-00SM50 250GB                | 2         | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB                | 2         | 0.61%   |
| WDC WDS120G2G0B-00EPW0 120GB                | 2         | 0.61%   |
| WDC WD40EFRX-68WT0N0 4TB                    | 2         | 0.61%   |
| WDC WD40EFRX-68N32N0 4TB                    | 2         | 0.61%   |
| WDC WD20EZRX-00D8PB0 2TB                    | 2         | 0.61%   |
| WDC WD20EZAZ-00GGJB0 2TB                    | 2         | 0.61%   |
| Toshiba THNSF5256GPUK 256GB                 | 2         | 0.61%   |
| Toshiba MQ01ABD100 1TB                      | 2         | 0.61%   |
| Toshiba MK6475GSX 640GB                     | 2         | 0.61%   |
| SPCC M.2 PCIe SSD 256GB                     | 2         | 0.61%   |
| Seagate ST9500325AS 500GB                   | 2         | 0.61%   |
| Seagate ST1000DM010-2EP102 1TB              | 2         | 0.61%   |
| SanDisk SDSA6MM-032G-1006 32GB              | 2         | 0.61%   |
| Samsung SSD 980 500GB                       | 2         | 0.61%   |
| Samsung SSD 970 EVO Plus 250GB              | 2         | 0.61%   |
| Samsung MZ7LN128HCHP-000H1 128GB            | 2         | 0.61%   |
| Protectli 120GB mSATA                       | 2         | 0.61%   |
| Micron MTFDDAK256MAM-1K1 256GB              | 2         | 0.61%   |
| KIOXIA KXG60ZNV256G 256GB                   | 2         | 0.61%   |
| Dogfish SSD 64GB                            | 2         | 0.61%   |
| Crucial CT480BX500SSD1 480GB                | 2         | 0.61%   |
| A-DATA IM2S3134N-064GM 64GB                 | 2         | 0.61%   |
| ZOTAC ZTSSD-S11-120G-P 120GB                | 1         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 50     | 41.46%  |
| WDC                 | 22        | 64     | 26.83%  |
| Toshiba             | 8         | 10     | 9.76%   |
| Samsung Electronics | 3         | 5      | 3.66%   |
| NVMe                | 3         | 3      | 3.66%   |
| Hitachi             | 3         | 6      | 3.66%   |
| Hewlett-Packard     | 3         | 6      | 3.66%   |
| HGST                | 2         | 2      | 2.44%   |
| Maxtor              | 1         | 1      | 1.22%   |
| Jetflash            | 1         | 1      | 1.22%   |
| Fujitsu             | 1         | 1      | 1.22%   |
| China               | 1         | 1      | 1.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 45     | 18.93%  |
| Kingston            | 18        | 25     | 10.65%  |
| Intel               | 16        | 26     | 9.47%   |
| Crucial             | 16        | 20     | 9.47%   |
| SanDisk             | 12        | 20     | 7.1%    |
| Hoodisk             | 10        | 20     | 5.92%   |
| WDC                 | 9         | 15     | 5.33%   |
| OCZ                 | 6         | 7      | 3.55%   |
| Micron Technology   | 5         | 7      | 2.96%   |
| China               | 5         | 6      | 2.96%   |
| Toshiba             | 4         | 7      | 2.37%   |
| Protectli           | 4         | 4      | 2.37%   |
| A-DATA Technology   | 4         | 4      | 2.37%   |
| Dogfish             | 3         | 4      | 1.78%   |
| Transcend           | 2         | 4      | 1.18%   |
| Phison              | 2         | 2      | 1.18%   |
| KingDian            | 2         | 2      | 1.18%   |
| FORESEE             | 2         | 3      | 1.18%   |
| ZOTAC               | 1         | 1      | 0.59%   |
| XUNZHE              | 1         | 1      | 0.59%   |
| Vaseky              | 1         | 4      | 0.59%   |
| SK hynix            | 1         | 1      | 0.59%   |
| ShiJi               | 1         | 1      | 0.59%   |
| Qunion              | 1         | 2      | 0.59%   |
| Plextor             | 1         | 2      | 0.59%   |
| Patriot             | 1         | 1      | 0.59%   |
| NVMe                | 1         | 1      | 0.59%   |
| LITEONIT            | 1         | 1      | 0.59%   |
| Lenovo              | 1         | 1      | 0.59%   |
| KingSpec            | 1         | 1      | 0.59%   |
| Fordisk             | 1         | 1      | 0.59%   |
| Corsair             | 1         | 1      | 0.59%   |
| BIWIN               | 1         | 1      | 0.59%   |
| Apple               | 1         | 1      | 0.59%   |
| Apacer              | 1         | 1      | 0.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 154       | 243    | 56.83%  |
| HDD  | 66        | 150    | 24.35%  |
| NVMe | 51        | 73     | 18.82%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 204       | 393    | 80%     |
| NVMe | 51        | 73     | 20%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 178       | 286    | 77.73%  |
| 0.51-1.0   | 24        | 35     | 10.48%  |
| 1.01-2.0   | 14        | 40     | 6.11%   |
| 3.01-4.0   | 7         | 13     | 3.06%   |
| 2.01-3.0   | 3         | 12     | 1.31%   |
| 4.01-10.0  | 2         | 5      | 0.87%   |
| 10.01-20.0 | 1         | 2      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 112       | 42.26%  |
| 251-500        | 45        | 16.98%  |
| 1-20           | 37        | 13.96%  |
| 51-100         | 26        | 9.81%   |
| 21-50          | 19        | 7.17%   |
| 501-1000       | 17        | 6.42%   |
| 1001-2000      | 6         | 2.26%   |
| 2001-3000      | 2         | 0.75%   |
| More than 3000 | 1         | 0.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 242       | 89.63%  |
| 21-50     | 19        | 7.04%   |
| 51-100    | 5         | 1.85%   |
| 101-250   | 3         | 1.11%   |
| 1001-2000 | 1         | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB              | 2         | 5      | 6.45%   |
| Seagate ST500LM021-1KJ152 500GB           | 2         | 2      | 6.45%   |
| WDC WD30EFRX-68EUZN0 3TB                  | 1         | 1      | 3.23%   |
| WDC WD20EZRX-00D8PB0 2TB                  | 1         | 2      | 3.23%   |
| WDC WD20EARX-008FB0 2TB                   | 1         | 4      | 3.23%   |
| WDC WD20EARS-00MVWB0 2TB                  | 1         | 1      | 3.23%   |
| Toshiba KSG60ZSE256G SATA 256GB           | 1         | 1      | 3.23%   |
| Seagate ST9160314AS 160GB                 | 1         | 1      | 3.23%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1      | 3.23%   |
| Seagate ST3250310AS 250GB                 | 1         | 1      | 3.23%   |
| Seagate ST2000LM015-2E8174 2TB            | 1         | 1      | 3.23%   |
| Seagate ST2000DL003-9VT166 2TB            | 1         | 1      | 3.23%   |
| Seagate ST1000DM003-1CH162 1TB            | 1         | 1      | 3.23%   |
| SanDisk SDSSDA240G 240GB                  | 1         | 1      | 3.23%   |
| Samsung Electronics HM500LI 500GB         | 1         | 2      | 3.23%   |
| Phison SATA SSD 32GB                      | 1         | 1      | 3.23%   |
| Micron Technology C400-MTFDDAT064MAM 64GB | 1         | 1      | 3.23%   |
| Kingston SNS4151S316G 16GB                | 1         | 1      | 3.23%   |
| Kingston SA400S37480G 480GB               | 1         | 1      | 3.23%   |
| Intel SSDSC2BW120H6 120GB                 | 1         | 1      | 3.23%   |
| Intel SSDSC2BF180A4L 180GB                | 1         | 1      | 3.23%   |
| Hitachi HTS542525K9A300 250GB             | 1         | 1      | 3.23%   |
| Hitachi HDS721010KLA330 1TB               | 1         | 1      | 3.23%   |
| HGST HTS725050A7E630 500GB                | 1         | 1      | 3.23%   |
| Hewlett-Packard VB0250EAVER 250GB         | 1         | 1      | 3.23%   |
| Crucial CT275MX300SSD4 275GB              | 1         | 1      | 3.23%   |
| BIWIN SSD 8GB                             | 1         | 1      | 3.23%   |
| Apple SSD SM256E 256GB                    | 1         | 1      | 3.23%   |
| Apacer AS330 240GB                        | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 26.67%  |
| WDC                 | 5         | 13     | 16.67%  |
| Kingston            | 2         | 2      | 6.67%   |
| Intel               | 2         | 2      | 6.67%   |
| Hitachi             | 2         | 2      | 6.67%   |
| Toshiba             | 1         | 1      | 3.33%   |
| SanDisk             | 1         | 1      | 3.33%   |
| Samsung Electronics | 1         | 2      | 3.33%   |
| Phison              | 1         | 1      | 3.33%   |
| Micron Technology   | 1         | 1      | 3.33%   |
| HGST                | 1         | 1      | 3.33%   |
| Hewlett-Packard     | 1         | 1      | 3.33%   |
| Crucial             | 1         | 1      | 3.33%   |
| BIWIN               | 1         | 1      | 3.33%   |
| Apple               | 1         | 1      | 3.33%   |
| Apacer              | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 50%     |
| WDC                 | 3         | 8      | 18.75%  |
| Hitachi             | 2         | 2      | 12.5%   |
| Samsung Electronics | 1         | 2      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |
| Hewlett-Packard     | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 22     | 53.33%  |
| SSD  | 14        | 17     | 46.67%  |

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
| Works    | 219       | 422    | 86.56%  |
| Malfunc  | 30        | 39     | 11.86%  |
| Detected | 4         | 5      | 1.58%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 206       | 64.98%  |
| AMD                         | 36        | 11.36%  |
| Samsung Electronics         | 17        | 5.36%   |
| Broadcom / LSI              | 10        | 3.15%   |
| Phison Electronics          | 7         | 2.21%   |
| Toshiba                     | 6         | 1.89%   |
| Micron/Crucial Technology   | 6         | 1.89%   |
| Silicon Motion              | 4         | 1.26%   |
| Sandisk                     | 4         | 1.26%   |
| Seagate Technology          | 3         | 0.95%   |
| Nvidia                      | 2         | 0.63%   |
| Micron Technology           | 2         | 0.63%   |
| Kingston Technology Company | 2         | 0.63%   |
| ASMedia Technology          | 2         | 0.63%   |
| Union Memory (Shenzhen)     | 1         | 0.32%   |
| SK hynix                    | 1         | 0.32%   |
| Silicon Image               | 1         | 0.32%   |
| Realtek Semiconductor       | 1         | 0.32%   |
| QLogic                      | 1         | 0.32%   |
| Marvell Technology Group    | 1         | 0.32%   |
| JMicron Technology          | 1         | 0.32%   |
| Hewlett-Packard             | 1         | 0.32%   |
| ADATA Technology            | 1         | 0.32%   |
| Adaptec                     | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 23        | 6.44%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 22        | 6.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 18        | 5.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 17        | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13        | 3.64%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11        | 3.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 10        | 2.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 9         | 2.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9         | 2.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8         | 2.24%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 8         | 2.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8         | 2.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 2.24%   |
| AMD FCH IDE Controller                                                                  | 8         | 2.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7         | 1.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 7         | 1.96%   |
| Intel SATA Controller [RAID mode]                                                       | 7         | 1.96%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 7         | 1.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 6         | 1.68%   |
| Phison PS5013 E13 NVMe Controller                                                       | 5         | 1.4%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 5         | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 1.4%    |
| Samsung NVMe SSD Controller 980                                                         | 4         | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 1.12%   |
| AMD FCH SATA Controller D                                                               | 4         | 1.12%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3         | 0.84%   |
| Seagate FireCuda 520 SSD                                                                | 3         | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 0.84%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3         | 0.84%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 0.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.84%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 3         | 0.84%   |
| Toshiba XG6 NVMe SSD Controller                                                         | 2         | 0.56%   |
| Toshiba XG4 NVMe SSD Controller                                                         | 2         | 0.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.56%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 0.56%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 0.56%   |
| Intel Atom Processor C3000 Series SATA Controller 0                                     | 2         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 224       | 67.67%  |
| NVMe | 53        | 16.01%  |
| IDE  | 30        | 9.06%   |
| RAID | 16        | 4.83%   |
| SAS  | 5         | 1.51%   |
| SCSI | 3         | 0.91%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 222       | 85.06%  |
| AMD    | 38        | 14.56%  |
| ARM    | 1         | 0.38%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz          | 12        | 4.53%   |
| Intel Celeron J4125 CPU @ 2.00GHz          | 7         | 2.64%   |
| AMD RX-427BB with AMD Radeon R7 Graphics   | 7         | 2.64%   |
| Intel Celeron N5105 @ 2.00GHz              | 6         | 2.26%   |
| Intel Core i5-6500T CPU @ 2.50GHz          | 5         | 1.89%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 4         | 1.51%   |
| Intel Celeron CPU J1900 @ 1.99GHz          | 4         | 1.51%   |
| Intel Pentium CPU G4560 @ 3.50GHz          | 3         | 1.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 3         | 1.13%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 3         | 1.13%   |
| Intel Core i5-7400 CPU @ 3.00GHz           | 3         | 1.13%   |
| Intel Core i5-5300U CPU @ 2.30GHz          | 3         | 1.13%   |
| Intel Core i5-4570T CPU @ 2.90GHz          | 3         | 1.13%   |
| Intel Core i5-4570 CPU @ 3.20GHz           | 3         | 1.13%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 3         | 1.13%   |
| Intel Celeron CPU G3900 @ 2.80GHz          | 3         | 1.13%   |
| AMD GX-412TC SOC                           | 3         | 1.13%   |
| Intel Xeon CPU E5504 @ 2.00GHz             | 2         | 0.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 2         | 0.75%   |
| Intel Core i7-7700 CPU @ 3.60GHz           | 2         | 0.75%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 2         | 0.75%   |
| Intel Core i7-4510U CPU @ 2.00GHz          | 2         | 0.75%   |
| Intel Core i7-3667U CPU @ 2.00GHz          | 2         | 0.75%   |
| Intel Core i5-7500 CPU @ 3.40GHz           | 2         | 0.75%   |
| Intel Core i5-6500 CPU @ 3.20GHz           | 2         | 0.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 2         | 0.75%   |
| Intel Core i5-5250U CPU @ 1.60GHz          | 2         | 0.75%   |
| Intel Core i5-4590T CPU @ 2.00GHz          | 2         | 0.75%   |
| Intel Core i5-4590 CPU @ 3.30GHz           | 2         | 0.75%   |
| Intel Core i5-2400 CPU @ 3.10GHz           | 2         | 0.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 2         | 0.75%   |
| Intel Core i3-6100U CPU @ 2.30GHz          | 2         | 0.75%   |
| Intel Core i3-6100 CPU @ 3.70GHz           | 2         | 0.75%   |
| Intel Core i3-4150 CPU @ 3.50GHz           | 2         | 0.75%   |
| Intel Celeron CPU J3060 @ 1.60GHz          | 2         | 0.75%   |
| Intel Atom CPU C3508 @ 1.60GHz             | 2         | 0.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 2         | 0.75%   |
| AMD Turion II Neo N54L Dual-Core Processor | 2         | 0.75%   |
| AMD Turion II Neo N40L Dual-Core Processor | 2         | 0.75%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 2         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 64        | 24.33%  |
| Intel Celeron           | 53        | 20.15%  |
| Intel Core i7           | 36        | 13.69%  |
| Intel Xeon              | 23        | 8.75%   |
| Intel Core i3           | 18        | 6.84%   |
| Other                   | 15        | 5.7%    |
| Intel Pentium           | 8         | 3.04%   |
| Intel Atom              | 5         | 1.9%    |
| AMD Ryzen 5             | 5         | 1.9%    |
| AMD Ryzen 3             | 5         | 1.9%    |
| AMD Turion II Neo       | 4         | 1.52%   |
| AMD GX                  | 4         | 1.52%   |
| Intel Core 2 Quad       | 3         | 1.14%   |
| AMD FX                  | 3         | 1.14%   |
| Intel Core 2 Duo        | 2         | 0.76%   |
| AMD G                   | 2         | 0.76%   |
| AMD Athlon              | 2         | 0.76%   |
| Intel Xeon Silver       | 1         | 0.38%   |
| Intel Pentium Silver    | 1         | 0.38%   |
| Intel Pentium Dual-Core | 1         | 0.38%   |
| Intel Pentium 4         | 1         | 0.38%   |
| Intel Core Duo          | 1         | 0.38%   |
| ARM Cortex              | 1         | 0.38%   |
| AMD Ryzen 9             | 1         | 0.38%   |
| AMD E2                  | 1         | 0.38%   |
| AMD Athlon X2           | 1         | 0.38%   |
| AMD A6                  | 1         | 0.38%   |
| AMD A4                  | 1         | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 141       | 53.61%  |
| 2       | 81        | 30.8%   |
| 8       | 13        | 4.94%   |
| 6       | 12        | 4.56%   |
| Unknown | 7         | 2.66%   |
| 12      | 4         | 1.52%   |
| 1       | 2         | 0.76%   |
| 32      | 1         | 0.38%   |
| 16      | 1         | 0.38%   |
| 10      | 1         | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 254       | 97.32%  |
| 2       | 5         | 1.92%   |
| Unknown | 2         | 0.77%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 157       | 59.7%   |
| 2       | 99        | 37.64%  |
| Unknown | 7         | 2.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 35        | 13.31%  |
| Haswell       | 33        | 12.55%  |
| Skylake       | 28        | 10.65%  |
| Silvermont    | 28        | 10.65%  |
| IvyBridge     | 26        | 9.89%   |
| SandyBridge   | 17        | 6.46%   |
| Unknown       | 13        | 4.94%   |
| Goldmont plus | 10        | 3.8%    |
| Broadwell     | 8         | 3.04%   |
| Steamroller   | 7         | 2.66%   |
| Puma          | 5         | 1.9%    |
| Nehalem       | 5         | 1.9%    |
| K10           | 5         | 1.9%    |
| Westmere      | 4         | 1.52%   |
| Penryn        | 4         | 1.52%   |
| Zen 3         | 3         | 1.14%   |
| Zen 2         | 3         | 1.14%   |
| Zen           | 3         | 1.14%   |
| TigerLake     | 3         | 1.14%   |
| Piledriver    | 3         | 1.14%   |
| Goldmont      | 3         | 1.14%   |
| Core          | 3         | 1.14%   |
| CometLake     | 3         | 1.14%   |
| Bobcat        | 3         | 1.14%   |
| Zen+          | 2         | 0.76%   |
| Jaguar        | 2         | 0.76%   |
| P6            | 1         | 0.38%   |
| NetBurst      | 1         | 0.38%   |
| K8 Hammer     | 1         | 0.38%   |
| Bonnell       | 1         | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 178       | 65.93%  |
| AMD                        | 42        | 15.56%  |
| Nvidia                     | 30        | 11.11%  |
| Matrox Electronics Systems | 13        | 4.81%   |
| ASPEED Technology          | 5         | 1.85%   |
| Tseng Labs                 | 1         | 0.37%   |
| Silicon Motion             | 1         | 0.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 19        | 6.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 6.91%   |
| Intel HD Graphics 530                                                                    | 11        | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 4%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 3.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 8         | 2.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.91%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 2.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 2.55%   |
| Intel JasperLake [UHD Graphics]                                                          | 7         | 2.55%   |
| Intel HD Graphics 630                                                                    | 7         | 2.55%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 7         | 2.55%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 5         | 1.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 1.82%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 5         | 1.82%   |
| Matrox Electronics Systems G200eR2                                                       | 4         | 1.45%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.45%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.45%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 4         | 1.45%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3         | 1.09%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.09%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 1.09%   |
| Intel HD Graphics 610                                                                    | 3         | 1.09%   |
| Intel HD Graphics 510                                                                    | 3         | 1.09%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.73%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.73%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.73%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 0.73%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 0.73%   |
| Intel HD Graphics 620                                                                    | 2         | 0.73%   |
| Intel HD Graphics 6000                                                                   | 2         | 0.73%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.73%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.73%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.73%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2         | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 156       | 59.32%  |
| 1 x AMD            | 35        | 13.31%  |
| 1 x Nvidia         | 20        | 7.6%    |
| 1 x Matrox         | 13        | 4.94%   |
| Intel + Nvidia     | 10        | 3.8%    |
| Other              | 9         | 3.42%   |
| Intel + AMD        | 7         | 2.66%   |
| 2 x Intel          | 5         | 1.9%    |
| 1 x ASPEED         | 5         | 1.9%    |
| 2 x AMD            | 1         | 0.38%   |
| 1 x Tseng Labs     | 1         | 0.38%   |
| 1 x Silicon Motion | 1         | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 240       | 91.6%   |
| Proprietary | 11        | 4.2%    |
| Unknown     | 11        | 4.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 239       | 91.22%  |
| 1.01-2.0   | 10        | 3.82%   |
| 0.51-1.0   | 5         | 1.91%   |
| 0.01-0.5   | 4         | 1.53%   |
| 7.01-8.0   | 2         | 0.76%   |
| 3.01-4.0   | 2         | 0.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 7         | 11.86%  |
| Samsung Electronics | 5         | 8.47%   |
| LG Display          | 5         | 8.47%   |
| Acer                | 5         | 8.47%   |
| Hewlett-Packard     | 4         | 6.78%   |
| Dell                | 4         | 6.78%   |
| ViewSonic           | 3         | 5.08%   |
| Sharp               | 3         | 5.08%   |
| Philips             | 3         | 5.08%   |
| Lenovo              | 3         | 5.08%   |
| BOE                 | 3         | 5.08%   |
| Chimei Innolux      | 2         | 3.39%   |
| ASUSTek Computer    | 2         | 3.39%   |
| AOC                 | 2         | 3.39%   |
| ___                 | 1         | 1.69%   |
| Toshiba             | 1         | 1.69%   |
| Panasonic           | 1         | 1.69%   |
| Konka               | 1         | 1.69%   |
| Goldstar            | 1         | 1.69%   |
| Compal              | 1         | 1.69%   |
| BenQ                | 1         | 1.69%   |
| Apple               | 1         | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Lenovo D27-30 LEN66B8 1920x1080 600x340mm 27.2-inch                  | 2         | 3.33%   |
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 600x340mm 27.2-inch    | 2         | 3.33%   |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 1.67%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch            | 1         | 1.67%   |
| ViewSonic VA2026w VSC5020 1680x1050 430x270mm 20.0-inch              | 1         | 1.67%   |
| ViewSonic VA1912w-3 VSC711C 1440x900 410x260mm 19.1-inch             | 1         | 1.67%   |
| Toshiba TV TSB010E 1920x1080 1040x590mm 47.1-inch                    | 1         | 1.67%   |
| Sharp LQ133T1JX03 SHP140F 2560x1440 290x170mm 13.2-inch              | 1         | 1.67%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 210x140mm 9.9-inch               | 1         | 1.67%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch              | 1         | 1.67%   |
| Samsung Electronics SyncMaster SAM056A 1680x1050 470x300mm 22.0-inch | 1         | 1.67%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch | 1         | 1.67%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch    | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC4445 1366x768 340x190mm 15.3-inch | 1         | 1.67%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1         | 1.67%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 1         | 1.67%   |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch              | 1         | 1.67%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 1         | 1.67%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 1         | 1.67%   |
| LG Display LCD Monitor LGD04A9 1920x1080 310x170mm 13.9-inch         | 1         | 1.67%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x170mm 13.9-inch         | 1         | 1.67%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch         | 1         | 1.67%   |
| LG Display LCD Monitor LGD01DD 1600x900 380x210mm 17.1-inch          | 1         | 1.67%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch              | 1         | 1.67%   |
| Konka TV_MONITOR KOA0030 2288x1430 1150x650mm 52.0-inch              | 1         | 1.67%   |
| Hewlett-Packard W2072a HWP299F 1600x900 440x250mm 19.9-inch          | 1         | 1.67%   |
| Hewlett-Packard LCD Monitor HWP2915 1920x1080 510x290mm 23.1-inch    | 1         | 1.67%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch         | 1         | 1.67%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch           | 1         | 1.67%   |
| Goldstar LG HDR WQHD GSM7716 3840x1600 880x370mm 37.6-inch           | 1         | 1.67%   |
| Dell U2212HM DELD048 1920x1080 480x270mm 21.7-inch                   | 1         | 1.67%   |
| Dell SP2309W DELD01C 2048x1152 510x290mm 23.1-inch                   | 1         | 1.67%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                    | 1         | 1.67%   |
| Dell E248WFP DELA02D 1920x1200 520x320mm 24.0-inch                   | 1         | 1.67%   |
| Compal LCD Monitor WOR2760 2560x1440 600x340mm 27.2-inch             | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 1         | 1.67%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                | 1         | 1.67%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                | 1         | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 51.72%  |
| 2560x1440 (QHD)    | 7         | 12.07%  |
| 1366x768 (WXGA)    | 7         | 12.07%  |
| 1680x1050 (WSXGA+) | 3         | 5.17%   |
| 1600x900 (HD+)     | 2         | 3.45%   |
| 3840x1600          | 1         | 1.72%   |
| 2880x1620          | 1         | 1.72%   |
| 2560x1080          | 1         | 1.72%   |
| 2288x1430          | 1         | 1.72%   |
| 2048x1152          | 1         | 1.72%   |
| 1920x1200 (WUXGA)  | 1         | 1.72%   |
| 1800x1200          | 1         | 1.72%   |
| 1440x900 (WXGA+)   | 1         | 1.72%   |
| 1280x720 (HD)      | 1         | 1.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 27      | 10        | 16.95%  |
| 13      | 9         | 15.25%  |
| 15      | 7         | 11.86%  |
| 24      | 5         | 8.47%   |
| 21      | 5         | 8.47%   |
| 23      | 3         | 5.08%   |
| 11      | 3         | 5.08%   |
| 22      | 2         | 3.39%   |
| 19      | 2         | 3.39%   |
| 12      | 2         | 3.39%   |
| Unknown | 2         | 3.39%   |
| 52      | 1         | 1.69%   |
| 47      | 1         | 1.69%   |
| 37      | 1         | 1.69%   |
| 31      | 1         | 1.69%   |
| 28      | 1         | 1.69%   |
| 20      | 1         | 1.69%   |
| 17      | 1         | 1.69%   |
| 10      | 1         | 1.69%   |
| 9       | 1         | 1.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 18        | 31.03%  |
| 301-350     | 14        | 24.14%  |
| 401-500     | 9         | 15.52%  |
| 201-300     | 9         | 15.52%  |
| 601-700     | 2         | 3.45%   |
| 1001-1500   | 2         | 3.45%   |
| Unknown     | 2         | 3.45%   |
| 801-900     | 1         | 1.72%   |
| 351-400     | 1         | 1.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 48        | 85.71%  |
| 16/10   | 4         | 7.14%   |
| 21/9    | 2         | 3.57%   |
| 3/2     | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 13        | 22.41%  |
| 301-350        | 10        | 17.24%  |
| 81-90          | 7         | 12.07%  |
| 91-100         | 6         | 10.34%  |
| 51-60          | 3         | 5.17%   |
| 151-200        | 3         | 5.17%   |
| 71-80          | 2         | 3.45%   |
| 61-70          | 2         | 3.45%   |
| 41-50          | 2         | 3.45%   |
| 251-300        | 2         | 3.45%   |
| 501-1000       | 2         | 3.45%   |
| Unknown        | 2         | 3.45%   |
| More than 1000 | 1         | 1.72%   |
| 351-500        | 1         | 1.72%   |
| 121-130        | 1         | 1.72%   |
| 101-110        | 1         | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 21        | 36.84%  |
| 121-160 | 14        | 24.56%  |
| 101-120 | 13        | 22.81%  |
| 161-240 | 6         | 10.53%  |
| Unknown | 2         | 3.51%   |
| 1-50    | 1         | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 197       | 75.19%  |
| 1     | 62        | 23.66%  |
| 2     | 3         | 1.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 188       | 52.96%  |
| Realtek Semiconductor             | 88        | 24.79%  |
| Broadcom                          | 31        | 8.73%   |
| Qualcomm Atheros                  | 20        | 5.63%   |
| U-Blox                            | 3         | 0.85%   |
| TP-Link                           | 2         | 0.56%   |
| Ralink Technology                 | 2         | 0.56%   |
| Nvidia                            | 2         | 0.56%   |
| Marvell Technology Group          | 2         | 0.56%   |
| IMC Networks                      | 2         | 0.56%   |
| Ericsson Business Mobile Networks | 2         | 0.56%   |
| D-Link System                     | 2         | 0.56%   |
| TRENDnet                          | 1         | 0.28%   |
| Sierra Wireless                   | 1         | 0.28%   |
| Seeed Technology                  | 1         | 0.28%   |
| Samsung Electronics               | 1         | 0.28%   |
| Ralink                            | 1         | 0.28%   |
| NetGear                           | 1         | 0.28%   |
| Microsoft                         | 1         | 0.28%   |
| Mellanox Technologies             | 1         | 0.28%   |
| MediaTek                          | 1         | 0.28%   |
| Emulex                            | 1         | 0.28%   |
| Aquantia                          | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 77        | 17.38%  |
| Intel I211 Gigabit Network Connection                                         | 37        | 8.35%   |
| Intel I210 Gigabit Network Connection                                         | 15        | 3.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 13        | 2.93%   |
| Intel 82574L Gigabit Network Connection                                       | 11        | 2.48%   |
| Intel Wireless 8260                                                           | 10        | 2.26%   |
| Intel Ethernet Connection I217-LM                                             | 9         | 2.03%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 9         | 2.03%   |
| Intel 82576 Gigabit Network Connection                                        | 8         | 1.81%   |
| Intel Wireless 7260                                                           | 7         | 1.58%   |
| Intel Ethernet Controller I226-V                                              | 7         | 1.58%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7         | 1.58%   |
| Intel Wireless 8265 / 8275                                                    | 6         | 1.35%   |
| Intel I350 Gigabit Network Connection                                         | 6         | 1.35%   |
| Intel Ethernet Controller I225-V                                              | 6         | 1.35%   |
| Intel Ethernet Connection (2) I219-V                                          | 6         | 1.35%   |
| Intel 82580 Gigabit Network Connection                                        | 6         | 1.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 1.35%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 5         | 1.13%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5         | 1.13%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4         | 0.9%    |
| Intel Wireless 7265                                                           | 4         | 0.9%    |
| Intel Ethernet Connection I217-V                                              | 4         | 0.9%    |
| Intel Ethernet Connection (7) I219-LM                                         | 4         | 0.9%    |
| U-Blox [u-blox 7]                                                             | 3         | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 3         | 0.68%   |
| Intel Wireless 3165                                                           | 3         | 0.68%   |
| Intel Wi-Fi 6 AX200                                                           | 3         | 0.68%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 3         | 0.68%   |
| Intel Ethernet Connection I219-V                                              | 3         | 0.68%   |
| Intel Ethernet Connection (7) I219-V                                          | 3         | 0.68%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3         | 0.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 0.68%   |
| Intel 82583V Gigabit Network Connection                                       | 3         | 0.68%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3         | 0.68%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 3         | 0.68%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 3         | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 56        | 55.45%  |
| Qualcomm Atheros      | 17        | 16.83%  |
| Realtek Semiconductor | 9         | 8.91%   |
| Broadcom              | 9         | 8.91%   |
| TP-Link               | 2         | 1.98%   |
| Ralink Technology     | 2         | 1.98%   |
| IMC Networks          | 2         | 1.98%   |
| Sierra Wireless       | 1         | 0.99%   |
| Ralink                | 1         | 0.99%   |
| NetGear               | 1         | 0.99%   |
| MediaTek              | 1         | 0.99%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                             | 10        | 9.71%   |
| Intel Wireless 7260                                             | 7         | 6.8%    |
| Intel Wireless 8265 / 8275                                      | 6         | 5.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 5         | 4.85%   |
| Intel Wireless 7265                                             | 4         | 3.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 3         | 2.91%   |
| Intel Wireless 3165                                             | 3         | 2.91%   |
| Intel Wi-Fi 6 AX200                                             | 3         | 2.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 3         | 2.91%   |
| Broadcom BCM4331 802.11a/b/g/n                                  | 3         | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2         | 1.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 2         | 1.94%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 2         | 1.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 2         | 1.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 2         | 1.94%   |
| Intel Wi-Fi 6 AX201                                             | 2         | 1.94%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection         | 2         | 1.94%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 2         | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 2         | 1.94%   |
| Intel Centrino Wireless-N 2230                                  | 2         | 1.94%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 2         | 1.94%   |
| Broadcom BCM43224 802.11a/b/g/n                                 | 2         | 1.94%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                             | 1         | 0.97%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                             | 1         | 0.97%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]      | 1         | 0.97%   |
| Sierra Wireless EM7455                                          | 1         | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 1         | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                 | 1         | 0.97%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter         | 1         | 0.97%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 1         | 0.97%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                 | 1         | 0.97%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1         | 0.97%   |
| Ralink RT5572 Wireless Adapter                                  | 1         | 0.97%   |
| Ralink RT5370 Wireless Adapter                                  | 1         | 0.97%   |
| Ralink RT5392 PCIe Wireless Network Adapter                     | 1         | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1         | 0.97%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 1         | 0.97%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 1         | 0.97%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                 | 1         | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter   | 1         | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 164       | 56.16%  |
| Realtek Semiconductor    | 84        | 28.77%  |
| Broadcom                 | 27        | 9.25%   |
| Qualcomm Atheros         | 6         | 2.05%   |
| Nvidia                   | 2         | 0.68%   |
| Marvell Technology Group | 2         | 0.68%   |
| D-Link System            | 2         | 0.68%   |
| TRENDnet                 | 1         | 0.34%   |
| Samsung Electronics      | 1         | 0.34%   |
| Microsoft                | 1         | 0.34%   |
| Emulex                   | 1         | 0.34%   |
| Aquantia                 | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 77        | 23.19%  |
| Intel I211 Gigabit Network Connection                                         | 37        | 11.14%  |
| Intel I210 Gigabit Network Connection                                         | 15        | 4.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 13        | 3.92%   |
| Intel 82574L Gigabit Network Connection                                       | 11        | 3.31%   |
| Intel Ethernet Connection I217-LM                                             | 9         | 2.71%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 9         | 2.71%   |
| Intel 82576 Gigabit Network Connection                                        | 8         | 2.41%   |
| Intel Ethernet Controller I226-V                                              | 7         | 2.11%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7         | 2.11%   |
| Intel I350 Gigabit Network Connection                                         | 6         | 1.81%   |
| Intel Ethernet Controller I225-V                                              | 6         | 1.81%   |
| Intel Ethernet Connection (2) I219-V                                          | 6         | 1.81%   |
| Intel 82580 Gigabit Network Connection                                        | 6         | 1.81%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 1.81%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6         | 1.81%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5         | 1.51%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4         | 1.2%    |
| Intel Ethernet Connection I217-V                                              | 4         | 1.2%    |
| Intel Ethernet Connection (7) I219-LM                                         | 4         | 1.2%    |
| Intel I210 Gigabit Fiber Network Connection                                   | 3         | 0.9%    |
| Intel Ethernet Connection I219-V                                              | 3         | 0.9%    |
| Intel Ethernet Connection (7) I219-V                                          | 3         | 0.9%    |
| Intel Ethernet Connection (5) I219-LM                                         | 3         | 0.9%    |
| Intel 82583V Gigabit Network Connection                                       | 3         | 0.9%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3         | 0.9%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 3         | 0.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2         | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 0.6%    |
| Intel Ethernet Connection X553 1GbE                                           | 2         | 0.6%    |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.6%    |
| Intel Ethernet Connection I218-LM                                             | 2         | 0.6%    |
| Intel Ethernet Connection (6) I219-V                                          | 2         | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.6%    |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 0.6%    |
| Intel Ethernet 10G 2P X520 Adapter                                            | 2         | 0.6%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2         | 0.6%    |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 2         | 0.6%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2         | 0.6%    |
| TRENDnet TRENDnet USB 5G Adapter ethernet                                     | 1         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 248       | 70.45%  |
| WiFi     | 96        | 27.27%  |
| Modem    | 6         | 1.7%    |
| Unknown  | 2         | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 235       | 84.53%  |
| WiFi     | 42        | 15.11%  |
| Modem    | 1         | 0.36%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 95        | 35.98%  |
| 1     | 51        | 19.32%  |
| 4     | 44        | 16.67%  |
| 3     | 28        | 10.61%  |
| 5     | 18        | 6.82%   |
| 6     | 16        | 6.06%   |
| 9     | 3         | 1.14%   |
| 8     | 3         | 1.14%   |
| 7     | 3         | 1.14%   |
| 10    | 2         | 0.76%   |
| 0     | 1         | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 224       | 83.9%   |
| Yes  | 43        | 16.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 57.53%  |
| Apple                           | 7         | 9.59%   |
| Qualcomm Atheros Communications | 5         | 6.85%   |
| Broadcom                        | 5         | 6.85%   |
| Realtek Semiconductor           | 4         | 5.48%   |
| Cambridge Silicon Radio         | 4         | 5.48%   |
| Foxconn / Hon Hai               | 2         | 2.74%   |
| ASUSTek Computer                | 2         | 2.74%   |
| IMC Networks                    | 1         | 1.37%   |
| Hewlett-Packard                 | 1         | 1.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 25        | 34.25%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 6.85%   |
| Intel AX201 Bluetooth                                       | 5         | 6.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 5.48%   |
| Intel AX200 Bluetooth                                       | 3         | 4.11%   |
| Apple Broadcom Built-in Bluetooth                           | 3         | 4.11%   |
| Apple Bluetooth Host Controller                             | 3         | 4.11%   |
| Realtek Bluetooth Adapter                                   | 2         | 2.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 2.74%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2         | 2.74%   |
| ASUS Qualcomm Bluetooth 4.1                                 | 2         | 2.74%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.37%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.37%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 1         | 1.37%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.37%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.37%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.37%   |
| Intel AX210 Bluetooth                                       | 1         | 1.37%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]      | 1         | 1.37%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.37%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 1.37%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.37%   |
| Broadcom Bluetooth 4.0                                      | 1         | 1.37%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 1.37%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.37%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 177       | 73.44%  |
| AMD                         | 35        | 14.52%  |
| Nvidia                      | 22        | 9.13%   |
| Texas Instruments           | 2         | 0.83%   |
| Focusrite-Novation          | 2         | 0.83%   |
| Logitech                    | 1         | 0.41%   |
| FiiO Electronics Technology | 1         | 0.41%   |
| C-Media Electronics         | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 22        | 7.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 20        | 6.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 5.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 16        | 5.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15        | 5.07%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 4.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 4.39%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 3.38%   |
| Intel 200 Series PCH HD Audio                                                                     | 10        | 3.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 3.04%   |
| AMD FCH Azalia Controller                                                                         | 9         | 3.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 2.36%   |
| Intel Jasper Lake HD Audio                                                                        | 7         | 2.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 2.36%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 7         | 2.36%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 2.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.03%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.69%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 1.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.35%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 1.35%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4         | 1.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.01%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.01%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.01%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.01%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.68%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.68%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.68%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.68%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.68%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.68%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.68%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 0.68%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 57        | 20.73%  |
| Kingston                     | 35        | 12.73%  |
| SK hynix                     | 31        | 11.27%  |
| Micron Technology            | 30        | 10.91%  |
| Crucial                      | 24        | 8.73%   |
| Unknown                      | 21        | 7.64%   |
| Corsair                      | 20        | 7.27%   |
| G.Skill                      | 9         | 3.27%   |
| Transcend                    | 4         | 1.45%   |
| Ramaxel Technology           | 4         | 1.45%   |
| Apacer                       | 4         | 1.45%   |
| A-DATA Technology            | 4         | 1.45%   |
| TIMETEC                      | 3         | 1.09%   |
| Team                         | 3         | 1.09%   |
| GeIL                         | 3         | 1.09%   |
| Unknown                      | 3         | 1.09%   |
| Unknown (ABCD)               | 2         | 0.73%   |
| Patriot                      | 2         | 0.73%   |
| Kimtigo                      | 2         | 0.73%   |
| Elpida                       | 2         | 0.73%   |
| Vasekey                      | 1         | 0.36%   |
| Uroad                        | 1         | 0.36%   |
| Smart Modular                | 1         | 0.36%   |
| Silicon Power                | 1         | 0.36%   |
| PNY                          | 1         | 0.36%   |
| Patriot Memory (PDP Systems) | 1         | 0.36%   |
| Nanya Technology             | 1         | 0.36%   |
| Kingmax                      | 1         | 0.36%   |
| Innodisk                     | 1         | 0.36%   |
| Hewlett-Packard              | 1         | 0.36%   |
| Heoriady                     | 1         | 0.36%   |
| ASint Technology             | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 5         | 1.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 1.41%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 4         | 1.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s            | 4         | 1.41%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 3         | 1.06%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 1.06%   |
| Samsung RAM M471A1K43BB1-CRC 16GB SODIMM DDR4 2400MT/s         | 3         | 1.06%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 3         | 1.06%   |
| Unknown                                                        | 3         | 1.06%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 2         | 0.7%    |
| Unknown RAM Module 8GB 1600MT/s                                | 2         | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 2         | 0.7%    |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 2         | 0.7%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2         | 0.7%    |
| Timetec RAM SD3-1600 8GB DIMM DDR3 1600MT/s                    | 2         | 0.7%    |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                | 2         | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.7%    |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s         | 2         | 0.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.7%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 0.7%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 2         | 0.7%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 2         | 0.7%    |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2400MT/s             | 2         | 0.7%    |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s          | 2         | 0.7%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s              | 2         | 0.7%    |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s          | 2         | 0.7%    |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                 | 2         | 0.7%    |
| GeIL RAM CL19-19-19 D4-2666 8GB DIMM DDR4 2667MT/s             | 2         | 0.7%    |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s           | 2         | 0.7%    |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s          | 2         | 0.7%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 2         | 0.7%    |
| Corsair RAM Module 8GB DIMM DDR4 2133MT/s                      | 2         | 0.7%    |
| Corsair RAM CMZ16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s           | 2         | 0.7%    |
| Corsair RAM CMSX64GX4M2A2666C18 32GB SODIMM DDR4 2667MT/s      | 2         | 0.7%    |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s        | 2         | 0.7%    |
| A-DATA RAM Module 4GB DIMM DDR4 1866MT/s                       | 2         | 0.7%    |
| Vasekey RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 1         | 0.35%   |
| Uroad RAM WJD4G8M16N12800 4GB DIMM DDR3 1600MT/s               | 1         | 0.35%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.35%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 130       | 54.17%  |
| DDR4    | 84        | 35%     |
| Unknown | 11        | 4.58%   |
| LPDDR3  | 6         | 2.5%    |
| LPDDR4  | 3         | 1.25%   |
| DDR2    | 3         | 1.25%   |
| DDR     | 2         | 0.83%   |
| DDR5    | 1         | 0.42%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 127       | 52.7%   |
| SODIMM       | 95        | 39.42%  |
| Unknown      | 7         | 2.9%    |
| Row Of Chips | 6         | 2.49%   |
| Chip         | 5         | 2.07%   |
| RIMM         | 1         | 0.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 101       | 40.08%  |
| 4096  | 88        | 34.92%  |
| 2048  | 27        | 10.71%  |
| 16384 | 25        | 9.92%   |
| 32768 | 8         | 3.17%   |
| 1024  | 3         | 1.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 95        | 37.85%  |
| 1333    | 36        | 14.34%  |
| 2133    | 27        | 10.76%  |
| 2400    | 25        | 9.96%   |
| 2667    | 24        | 9.56%   |
| 3200    | 9         | 3.59%   |
| 1867    | 8         | 3.19%   |
| 800     | 7         | 2.79%   |
| 1066    | 5         | 1.99%   |
| 3600    | 2         | 0.8%    |
| 2666    | 2         | 0.8%    |
| 1866    | 2         | 0.8%    |
| 667     | 2         | 0.8%    |
| 59392   | 1         | 0.4%    |
| 5600    | 1         | 0.4%    |
| 4267    | 1         | 0.4%    |
| 3000    | 1         | 0.4%    |
| 1067    | 1         | 0.4%    |
| 400     | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP LaserJet 3390 | 1         | 100%    |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 10        | 31.25%  |
| Bison Electronics                      | 5         | 15.63%  |
| IMC Networks                           | 4         | 12.5%   |
| Apple                                  | 3         | 9.38%   |
| Sunplus Innovation Technology          | 2         | 6.25%   |
| Microdia                               | 2         | 6.25%   |
| Z-Star Microelectronics                | 1         | 3.13%   |
| Suyin                                  | 1         | 3.13%   |
| Realtek Semiconductor                  | 1         | 3.13%   |
| Luxvisions Innotech Limited            | 1         | 3.13%   |
| Logitech                               | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 6         | 18.18%  |
| Bison Integrated Camera                                      | 3         | 9.09%   |
| Apple FaceTime HD Camera (Built-in)                          | 3         | 9.09%   |
| IMC Networks Integrated Webcam                               | 2         | 6.06%   |
| Z-Star WebCam SC-03FFL11739P                                 | 1         | 3.03%   |
| Suyin Lenovo Integrated Webcam                               | 1         | 3.03%   |
| Sunplus Laptop Integrated Webcam HD                          | 1         | 3.03%   |
| Sunplus HD WebCam                                            | 1         | 3.03%   |
| Realtek Integrated_Webcam_HD                                 | 1         | 3.03%   |
| Microdia REDRAGON Live Camera Audio                          | 1         | 3.03%   |
| Microdia Integrated_Webcam_HD                                | 1         | 3.03%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera          | 1         | 3.03%   |
| Logitech C922 Pro Stream Webcam                              | 1         | 3.03%   |
| IMC Networks SunplusIT Integrated Camera                     | 1         | 3.03%   |
| IMC Networks EasyCamera                                      | 1         | 3.03%   |
| Chicony USB2.0 VGA UVC WebCam                                | 1         | 3.03%   |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 3.03%   |
| Chicony TOSHIBA Web Camera - 3M                              | 1         | 3.03%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 3.03%   |
| Chicony Lenovo Integrated Camera                             | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 3.03%   |
| Bison Lenovo Integrated Webcam                               | 1         | 3.03%   |
| Bison Lenovo EasyCamera                                      | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 69.23%  |
| Elan Microelectronics      | 2         | 15.38%  |
| Upek                       | 1         | 7.69%   |
| Shenzhen Goodix Technology | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 4         | 30.77%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 3         | 23.08%  |
| Elan Fingerprint Sensor                                | 2         | 15.38%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor      | 1         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 7.69%   |

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
| 1     | 116       | 43.94%  |
| 0     | 76        | 28.79%  |
| 2     | 39        | 14.77%  |
| 3     | 26        | 9.85%   |
| 4     | 4         | 1.52%   |
| 5     | 2         | 0.76%   |
| 6     | 1         | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 168       | 61.31%  |
| Bluetooth                | 31        | 11.31%  |
| Net/wireless             | 22        | 8.03%   |
| Card reader              | 17        | 6.2%    |
| Fingerprint reader       | 10        | 3.65%   |
| Firewire controller      | 7         | 2.55%   |
| Sound                    | 6         | 2.19%   |
| Network                  | 4         | 1.46%   |
| Net/ethernet             | 3         | 1.09%   |
| Graphics card            | 3         | 1.09%   |
| Dvb card                 | 2         | 0.73%   |
| Storage/raid             | 1         | 0.36%   |

