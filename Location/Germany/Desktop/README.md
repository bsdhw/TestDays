BSD in Germany - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Germany.

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

Total: 1742

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| CncTion       | N5105-4L B0                 | [27f84c75b5](https://bsd-hardware.info/?probe=27f84c75b5) | Aug 11, 2023 |
| PC Engines    | APU2                        | [2e9106fc92](https://bsd-hardware.info/?probe=2e9106fc92) | Aug 11, 2023 |
| Gigabyte      | AX370M-DS3H-CF              | [7b00ddd0a1](https://bsd-hardware.info/?probe=7b00ddd0a1) | Aug 11, 2023 |
| PC Engines    | apu1                        | [0b3594d9a3](https://bsd-hardware.info/?probe=0b3594d9a3) | Aug 11, 2023 |
| PC Engines    | apu4                        | [b81f51408d](https://bsd-hardware.info/?probe=b81f51408d) | Aug 10, 2023 |
| PC Engines    | APU2                        | [be0e8bf959](https://bsd-hardware.info/?probe=be0e8bf959) | Aug 09, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [fac2fa5cbe](https://bsd-hardware.info/?probe=fac2fa5cbe) | Aug 08, 2023 |
| Acer          | Veriton N2620G              | [2acf1e4557](https://bsd-hardware.info/?probe=2acf1e4557) | Aug 08, 2023 |
| Techvision    | TVI7309X B0                 | [aeccb6e70c](https://bsd-hardware.info/?probe=aeccb6e70c) | Aug 07, 2023 |
| Lanner        | FW-7543 B-GA                | [dadf592128](https://bsd-hardware.info/?probe=dadf592128) | Aug 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [eceed9eb7a](https://bsd-hardware.info/?probe=eceed9eb7a) | Aug 05, 2023 |
| Unknown       | Unknown                     | [9c4dbcfd67](https://bsd-hardware.info/?probe=9c4dbcfd67) | Aug 05, 2023 |
| Lanner        | FW-7543 B-GA                | [6236e692de](https://bsd-hardware.info/?probe=6236e692de) | Aug 05, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [283fce4c68](https://bsd-hardware.info/?probe=283fce4c68) | Aug 05, 2023 |
| CWWK          | MINIPC-G12                  | [c449203453](https://bsd-hardware.info/?probe=c449203453) | Aug 04, 2023 |
| Lenovo        | SHARKBAY NO DPK             | [62ed2f59f6](https://bsd-hardware.info/?probe=62ed2f59f6) | Aug 04, 2023 |
| PC Engines    | APU2                        | [78c8ed6a89](https://bsd-hardware.info/?probe=78c8ed6a89) | Aug 03, 2023 |
| Shuttle       | DH610                       | [bbdd78fe4b](https://bsd-hardware.info/?probe=bbdd78fe4b) | Aug 01, 2023 |
| Unknown       | Unknown                     | [42c65b8b8b](https://bsd-hardware.info/?probe=42c65b8b8b) | Aug 01, 2023 |
| Hardkernel    | ODROID-H3                   | [aa708122cf](https://bsd-hardware.info/?probe=aa708122cf) | Aug 01, 2023 |
| Shuttle       | DH610                       | [e7c63c97d3](https://bsd-hardware.info/?probe=e7c63c97d3) | Aug 01, 2023 |
| Shuttle       | DH370                       | [a3ab1c6344](https://bsd-hardware.info/?probe=a3ab1c6344) | Jul 31, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [64137e0eec](https://bsd-hardware.info/?probe=64137e0eec) | Jul 29, 2023 |
| PC Engines    | APU2                        | [5eddd5369a](https://bsd-hardware.info/?probe=5eddd5369a) | Jul 28, 2023 |
| Hardkernel    | ODROID-H3                   | [0bb6b16689](https://bsd-hardware.info/?probe=0bb6b16689) | Jul 28, 2023 |
| Unknown       | Unknown                     | [1c6ab6b999](https://bsd-hardware.info/?probe=1c6ab6b999) | Jul 28, 2023 |
| PC Engines    | apu1                        | [8bc97daada](https://bsd-hardware.info/?probe=8bc97daada) | Jul 27, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [64b577cd8e](https://bsd-hardware.info/?probe=64b577cd8e) | Jul 27, 2023 |
| NF541         | 1.0                         | [ba959613a5](https://bsd-hardware.info/?probe=ba959613a5) | Jul 26, 2023 |
| Cisco         | ASA5525 A0                  | [f4409bdc8f](https://bsd-hardware.info/?probe=f4409bdc8f) | Jul 26, 2023 |
| Unknown       | Unknown                     | [f7728cee03](https://bsd-hardware.info/?probe=f7728cee03) | Jul 25, 2023 |
| Unknown       | MANIFOLD 2-C                | [8aa3f5491e](https://bsd-hardware.info/?probe=8aa3f5491e) | Jul 25, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [af215ad226](https://bsd-hardware.info/?probe=af215ad226) | Jul 24, 2023 |
| PC Engines    | apu4                        | [0aa9951131](https://bsd-hardware.info/?probe=0aa9951131) | Jul 24, 2023 |
| PC Engines    | apu4                        | [514dc1e9f9](https://bsd-hardware.info/?probe=514dc1e9f9) | Jul 24, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [dec2c34899](https://bsd-hardware.info/?probe=dec2c34899) | Jul 24, 2023 |
| Unknown       | Unknown                     | [aab49bd228](https://bsd-hardware.info/?probe=aab49bd228) | Jul 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [438424a9d9](https://bsd-hardware.info/?probe=438424a9d9) | Jul 23, 2023 |
| PC Engines    | apu4                        | [ea9a81b423](https://bsd-hardware.info/?probe=ea9a81b423) | Jul 23, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [3b16dab962](https://bsd-hardware.info/?probe=3b16dab962) | Jul 22, 2023 |
| Protectli     | FW6 Ver                     | [7e1b416d09](https://bsd-hardware.info/?probe=7e1b416d09) | Jul 21, 2023 |
| Yanling       | YL-CLU6L-V1                 | [489c685ec4](https://bsd-hardware.info/?probe=489c685ec4) | Jul 21, 2023 |
| AZW           | EQ                          | [9883a89b8d](https://bsd-hardware.info/?probe=9883a89b8d) | Jul 21, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [efe49f9e5d](https://bsd-hardware.info/?probe=efe49f9e5d) | Jul 20, 2023 |
| Unknown       | Unknown                     | [cce6d65dfb](https://bsd-hardware.info/?probe=cce6d65dfb) | Jul 20, 2023 |
| Unknown       | Unknown                     | [e487955dea](https://bsd-hardware.info/?probe=e487955dea) | Jul 18, 2023 |
| ASUSTek       | Maximus VIII HERO           | [35ab9e002d](https://bsd-hardware.info/?probe=35ab9e002d) | Jul 17, 2023 |
| Unknown       | Unknown                     | [8d82f25df2](https://bsd-hardware.info/?probe=8d82f25df2) | Jul 16, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a2602b7fbf](https://bsd-hardware.info/?probe=a2602b7fbf) | Jul 16, 2023 |
| Gigabyte      | GB-BSi7-1165G7              | [c5f92a4c5e](https://bsd-hardware.info/?probe=c5f92a4c5e) | Jul 14, 2023 |
| MW            | GMLK-2_5G4L                 | [0b90f241cd](https://bsd-hardware.info/?probe=0b90f241cd) | Jul 13, 2023 |
| PICO PC       | JSL-4L                      | [d93e338744](https://bsd-hardware.info/?probe=d93e338744) | Jul 13, 2023 |
| Gigabyte      | B450M H                     | [c2cb1e21fa](https://bsd-hardware.info/?probe=c2cb1e21fa) | Jul 11, 2023 |
| ASRock        | A520M-ITX/ac                | [96bda9f774](https://bsd-hardware.info/?probe=96bda9f774) | Jul 11, 2023 |
| Unknown       | Unknown                     | [5625dd24f6](https://bsd-hardware.info/?probe=5625dd24f6) | Jul 11, 2023 |
| PICO PC       | JSL-4L                      | [d8c9a61dcf](https://bsd-hardware.info/?probe=d8c9a61dcf) | Jul 10, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [3a544928aa](https://bsd-hardware.info/?probe=3a544928aa) | Jul 09, 2023 |
| MiTAC         | PH13CMI                     | [6d0cd37fce](https://bsd-hardware.info/?probe=6d0cd37fce) | Jul 09, 2023 |
| Biostar       | A68N-2100K                  | [20cb208208](https://bsd-hardware.info/?probe=20cb208208) | Jul 09, 2023 |
| Lex           | Pineview-D                  | [290c53a822](https://bsd-hardware.info/?probe=290c53a822) | Jul 09, 2023 |
| Yanling       | YL-ELU3L                    | [0a3c74b25c](https://bsd-hardware.info/?probe=0a3c74b25c) | Jul 07, 2023 |
| ASRock        | A300M-STX                   | [5d896a607e](https://bsd-hardware.info/?probe=5d896a607e) | Jul 06, 2023 |
| Unknown       | Unknown                     | [3644875d54](https://bsd-hardware.info/?probe=3644875d54) | Jul 03, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [2053dbb697](https://bsd-hardware.info/?probe=2053dbb697) | Jul 03, 2023 |
| PC Engines    | apu4                        | [62f0b60653](https://bsd-hardware.info/?probe=62f0b60653) | Jun 30, 2023 |
| Dell          | 00V62H A01                  | [d60c967edb](https://bsd-hardware.info/?probe=d60c967edb) | Jun 29, 2023 |
| Unknown       | Unknown                     | [075deef24f](https://bsd-hardware.info/?probe=075deef24f) | Jun 28, 2023 |
| CncTion       | J4125-4L-I225               | [1785cb2fa3](https://bsd-hardware.info/?probe=1785cb2fa3) | Jun 28, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [bcad942162](https://bsd-hardware.info/?probe=bcad942162) | Jun 26, 2023 |
| Unknown       | YL-SKUL6                    | [1512f63972](https://bsd-hardware.info/?probe=1512f63972) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | [fa177a2538](https://bsd-hardware.info/?probe=fa177a2538) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | [54ef7dc131](https://bsd-hardware.info/?probe=54ef7dc131) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | [b056cd0426](https://bsd-hardware.info/?probe=b056cd0426) | Jun 26, 2023 |
| Unknown       | J3160-4L                    | [5ad411cd6b](https://bsd-hardware.info/?probe=5ad411cd6b) | Jun 25, 2023 |
| Hardkernel    | ODROID-H3                   | [8a2ea60929](https://bsd-hardware.info/?probe=8a2ea60929) | Jun 25, 2023 |
| Techvision    | TVI7309X B0                 | [18cf91f3a4](https://bsd-hardware.info/?probe=18cf91f3a4) | Jun 23, 2023 |
| Intel         | Q3XXG4-P V1.0               | [bb4dc2b1a2](https://bsd-hardware.info/?probe=bb4dc2b1a2) | Jun 23, 2023 |
| Unknown       | Unknown                     | [16ceade742](https://bsd-hardware.info/?probe=16ceade742) | Jun 23, 2023 |
| Unknown       | Unknown                     | [508aa0bdb4](https://bsd-hardware.info/?probe=508aa0bdb4) | Jun 23, 2023 |
| Yanling       | YL-KBRL2 Series Ver:1.02    | [9e8d6110f4](https://bsd-hardware.info/?probe=9e8d6110f4) | Jun 19, 2023 |
| LANCOM Sys... | UF-60                       | [96904b8bdd](https://bsd-hardware.info/?probe=96904b8bdd) | Jun 19, 2023 |
| Unknown       | Unknown                     | [5fc629699d](https://bsd-hardware.info/?probe=5fc629699d) | Jun 18, 2023 |
| ASRock        | Z97 Professional            | [c978ddda86](https://bsd-hardware.info/?probe=c978ddda86) | Jun 18, 2023 |
| AMD           | Kabini CRB                  | [b774a8b586](https://bsd-hardware.info/?probe=b774a8b586) | Jun 16, 2023 |
| CncTion       | N5105-4L B0                 | [b9c5b6ec05](https://bsd-hardware.info/?probe=b9c5b6ec05) | Jun 15, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [70b0e8172d](https://bsd-hardware.info/?probe=70b0e8172d) | Jun 14, 2023 |
| PC Engines    | apu4                        | [ea036662ca](https://bsd-hardware.info/?probe=ea036662ca) | Jun 14, 2023 |
| Unknown       | J3160-4L                    | [4a6667249e](https://bsd-hardware.info/?probe=4a6667249e) | Jun 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [015a5d839a](https://bsd-hardware.info/?probe=015a5d839a) | Jun 13, 2023 |
| Unknown       | Unknown                     | [27617e1ca6](https://bsd-hardware.info/?probe=27617e1ca6) | Jun 13, 2023 |
| HP            | 3397                        | [a918ce0c4b](https://bsd-hardware.info/?probe=a918ce0c4b) | Jun 12, 2023 |
| CWWK          | MINIPC-G12                  | [04ae7435e5](https://bsd-hardware.info/?probe=04ae7435e5) | Jun 12, 2023 |
| MSI           | A320M GRENADE               | [6e0b1f598f](https://bsd-hardware.info/?probe=6e0b1f598f) | Jun 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [02509df772](https://bsd-hardware.info/?probe=02509df772) | Jun 12, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [2d2052de27](https://bsd-hardware.info/?probe=2d2052de27) | Jun 11, 2023 |
| Unknown       | Unknown                     | [8988baa83b](https://bsd-hardware.info/?probe=8988baa83b) | Jun 10, 2023 |
| Unknown       | Unknown                     | [40bb474319](https://bsd-hardware.info/?probe=40bb474319) | Jun 10, 2023 |
| ASRock        | B85M-HDS                    | [09a4700a14](https://bsd-hardware.info/?probe=09a4700a14) | Jun 09, 2023 |
| Wortmann      | terra Nettop 2700           | [e4a90ea530](https://bsd-hardware.info/?probe=e4a90ea530) | Jun 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | [1ae49c4706](https://bsd-hardware.info/?probe=1ae49c4706) | Jun 08, 2023 |
| Intel         | SKYBAY                      | [f1b649ed11](https://bsd-hardware.info/?probe=f1b649ed11) | Jun 08, 2023 |
| Lanner        | FW-7543 B-GA                | [ee85efd1c0](https://bsd-hardware.info/?probe=ee85efd1c0) | Jun 08, 2023 |
| LANCOM Sys... | UF-60                       | [204f10b60f](https://bsd-hardware.info/?probe=204f10b60f) | Jun 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | [4e57bbcdb5](https://bsd-hardware.info/?probe=4e57bbcdb5) | Jun 06, 2023 |
| Intel         | DENLOW_WS                   | [ce3bef7b5a](https://bsd-hardware.info/?probe=ce3bef7b5a) | Jun 06, 2023 |
| CncTion       | N6000-4L B0                 | [c9ec51aa84](https://bsd-hardware.info/?probe=c9ec51aa84) | Jun 05, 2023 |
| HP            | 3397                        | [6783902b93](https://bsd-hardware.info/?probe=6783902b93) | Jun 05, 2023 |
| Hardkernel    | ODROID-H3                   | [42e80f8003](https://bsd-hardware.info/?probe=42e80f8003) | Jun 05, 2023 |
| Dell          | 0PC5F7 A03                  | [23bd5ef252](https://bsd-hardware.info/?probe=23bd5ef252) | Jun 04, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [56a9981ff3](https://bsd-hardware.info/?probe=56a9981ff3) | Jun 03, 2023 |
| PC Engines    | APU2                        | [31c697459b](https://bsd-hardware.info/?probe=31c697459b) | Jun 02, 2023 |
| HP            | 3397                        | [1f8a9a4f27](https://bsd-hardware.info/?probe=1f8a9a4f27) | May 29, 2023 |
| ASRock        | H410M/ac                    | [d3e3d20cc4](https://bsd-hardware.info/?probe=d3e3d20cc4) | May 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | [2827d90215](https://bsd-hardware.info/?probe=2827d90215) | May 28, 2023 |
| HP            | 3397                        | [036d4e087c](https://bsd-hardware.info/?probe=036d4e087c) | May 27, 2023 |
| HP            | 3397                        | [19abd8768e](https://bsd-hardware.info/?probe=19abd8768e) | May 27, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [81775d5ca1](https://bsd-hardware.info/?probe=81775d5ca1) | May 26, 2023 |
| Nitrokey      | NitroWall                   | [1b3b451dee](https://bsd-hardware.info/?probe=1b3b451dee) | May 24, 2023 |
| Unknown       | Unknown                     | [4c7e1d476d](https://bsd-hardware.info/?probe=4c7e1d476d) | May 23, 2023 |
| Nitrokey      | NitroWall                   | [ef701f3991](https://bsd-hardware.info/?probe=ef701f3991) | May 23, 2023 |
| Unknown       | QD-WHLU01                   | [700bcad7cc](https://bsd-hardware.info/?probe=700bcad7cc) | May 22, 2023 |
| HP            | 158B                        | [1ef3762103](https://bsd-hardware.info/?probe=1ef3762103) | May 20, 2023 |
| HP            | 158B                        | [a9c63041a6](https://bsd-hardware.info/?probe=a9c63041a6) | May 20, 2023 |
| ZOTAC         | Unknown                     | [8156e3fede](https://bsd-hardware.info/?probe=8156e3fede) | May 19, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [612e3a21d4](https://bsd-hardware.info/?probe=612e3a21d4) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [8f3c5de741](https://bsd-hardware.info/?probe=8f3c5de741) | May 19, 2023 |
| VIA Techno... | VT82C597                    | [d73db58e48](https://bsd-hardware.info/?probe=d73db58e48) | May 19, 2023 |
| ASUSTek       | PRO B460M-C                 | [9350bb37db](https://bsd-hardware.info/?probe=9350bb37db) | May 18, 2023 |
| Medion        | MS-7633                     | [c01f7b9894](https://bsd-hardware.info/?probe=c01f7b9894) | May 18, 2023 |
| Supermicro    | H8DM8-2                     | [68c51b6006](https://bsd-hardware.info/?probe=68c51b6006) | May 18, 2023 |
| CncTion       | N5105-4L-I226 B0            | [75f5674d44](https://bsd-hardware.info/?probe=75f5674d44) | May 18, 2023 |
| HP            | 3397                        | [d405f14bb9](https://bsd-hardware.info/?probe=d405f14bb9) | May 18, 2023 |
| Unknown       | Unknown                     | [fff8127c3f](https://bsd-hardware.info/?probe=fff8127c3f) | May 17, 2023 |
| Unknown       | Unknown                     | [cc27c738be](https://bsd-hardware.info/?probe=cc27c738be) | May 17, 2023 |
| PC Engines    | apu4                        | [7fe2bf9ad6](https://bsd-hardware.info/?probe=7fe2bf9ad6) | May 16, 2023 |
| PC Engines    | apu4                        | [7723fe0a0a](https://bsd-hardware.info/?probe=7723fe0a0a) | May 16, 2023 |
| ASUSTek       | H110I-PLUS                  | [37922a69a6](https://bsd-hardware.info/?probe=37922a69a6) | May 15, 2023 |
| Lenovo        | SHARKBAY NOK                | [2b4ece70c9](https://bsd-hardware.info/?probe=2b4ece70c9) | May 15, 2023 |
| ASRock        | AM1B-ITX                    | [8ad16a1805](https://bsd-hardware.info/?probe=8ad16a1805) | May 15, 2023 |
| PC Engines    | APU2                        | [62fef2616b](https://bsd-hardware.info/?probe=62fef2616b) | May 15, 2023 |
| MSI           | B85M-G43                    | [6d2160dcee](https://bsd-hardware.info/?probe=6d2160dcee) | May 14, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [7332aba586](https://bsd-hardware.info/?probe=7332aba586) | May 14, 2023 |
| Fujitsu       | D3823-A2 S26361-D3823-Ax... | [2528087de1](https://bsd-hardware.info/?probe=2528087de1) | May 11, 2023 |
| Unknown       | Unknown                     | [eee23dec87](https://bsd-hardware.info/?probe=eee23dec87) | May 11, 2023 |
| ASUSTek       | H110I-PLUS                  | [2543ed83b9](https://bsd-hardware.info/?probe=2543ed83b9) | May 10, 2023 |
| Fujitsu       | D3644-B1 S26361-D3644-B1    | [b2e52b5677](https://bsd-hardware.info/?probe=b2e52b5677) | May 10, 2023 |
| Techvision    | TVI7309X B0                 | [fbf3fde510](https://bsd-hardware.info/?probe=fbf3fde510) | May 09, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [96abd89bab](https://bsd-hardware.info/?probe=96abd89bab) | May 09, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [38243e0313](https://bsd-hardware.info/?probe=38243e0313) | May 09, 2023 |
| PC Engines    | APU2                        | [6aff35010a](https://bsd-hardware.info/?probe=6aff35010a) | May 08, 2023 |
| Hardkernel    | ODROID-H3                   | [5b669f261f](https://bsd-hardware.info/?probe=5b669f261f) | May 08, 2023 |
| Unknown       | T100                        | [fb9c6bff7b](https://bsd-hardware.info/?probe=fb9c6bff7b) | May 07, 2023 |
| Supermicro    | X12STN-C-WOHS               | [d8cf344aee](https://bsd-hardware.info/?probe=d8cf344aee) | May 06, 2023 |
| Unknown       | Unknown                     | [349e1709cd](https://bsd-hardware.info/?probe=349e1709cd) | May 06, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [c29d140ee6](https://bsd-hardware.info/?probe=c29d140ee6) | May 06, 2023 |
| Lanner        | FW-7543 B-GA                | [8346fdf608](https://bsd-hardware.info/?probe=8346fdf608) | May 03, 2023 |
| HP            | 1589                        | [4aee1909c8](https://bsd-hardware.info/?probe=4aee1909c8) | May 03, 2023 |
| ASRock        | A520M-ITX/ac                | [70b09db335](https://bsd-hardware.info/?probe=70b09db335) | May 02, 2023 |
| ASRock        | A520M-ITX/ac                | [eb61af55d5](https://bsd-hardware.info/?probe=eb61af55d5) | May 01, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [8227d6d32c](https://bsd-hardware.info/?probe=8227d6d32c) | Apr 30, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [f86a94eb66](https://bsd-hardware.info/?probe=f86a94eb66) | Apr 30, 2023 |
| Protectli     | VP2420                      | [4ea8453453](https://bsd-hardware.info/?probe=4ea8453453) | Apr 30, 2023 |
| Protectli     | VP2420                      | [46a00b21d9](https://bsd-hardware.info/?probe=46a00b21d9) | Apr 30, 2023 |
| Protectli     | FW4B                        | [048da71e18](https://bsd-hardware.info/?probe=048da71e18) | Apr 29, 2023 |
| PC Engines    | apu1                        | [1a37e9d978](https://bsd-hardware.info/?probe=1a37e9d978) | Apr 27, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [989f3b44bf](https://bsd-hardware.info/?probe=989f3b44bf) | Apr 26, 2023 |
| Supermicro    | X11SDW-8C-TP13F             | [94316d20c8](https://bsd-hardware.info/?probe=94316d20c8) | Apr 26, 2023 |
| MiTAC         | PH13CMI                     | [5d3e954049](https://bsd-hardware.info/?probe=5d3e954049) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [0c8a0100c5](https://bsd-hardware.info/?probe=0c8a0100c5) | Apr 23, 2023 |
| Techvision    | TVI7309X B0                 | [ad73cda832](https://bsd-hardware.info/?probe=ad73cda832) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [775424cbff](https://bsd-hardware.info/?probe=775424cbff) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c26c1111c6](https://bsd-hardware.info/?probe=c26c1111c6) | Apr 21, 2023 |
| Techvision    | TVI7309X B0                 | [215364d870](https://bsd-hardware.info/?probe=215364d870) | Apr 21, 2023 |
| Techvision    | TVI7309X B0                 | [fdbbde509c](https://bsd-hardware.info/?probe=fdbbde509c) | Apr 20, 2023 |
| PC Engines    | APU2                        | [59b3a3eebf](https://bsd-hardware.info/?probe=59b3a3eebf) | Apr 19, 2023 |
| ASUSTek       | Pro B560M-C                 | [b341a9c9c9](https://bsd-hardware.info/?probe=b341a9c9c9) | Apr 19, 2023 |
| Unknown       | Unknown                     | [311e89be7a](https://bsd-hardware.info/?probe=311e89be7a) | Apr 18, 2023 |
| CncTion       | J4125-4L-I225               | [b4fd4e35b2](https://bsd-hardware.info/?probe=b4fd4e35b2) | Apr 18, 2023 |
| Supermicro    | X11SDW-8C-TP13F             | [20fac0b7a5](https://bsd-hardware.info/?probe=20fac0b7a5) | Apr 18, 2023 |
| Unknown       | Unknown                     | [f5153e1b18](https://bsd-hardware.info/?probe=f5153e1b18) | Apr 17, 2023 |
| CncTion       | N5105-4L B0                 | [6de7890035](https://bsd-hardware.info/?probe=6de7890035) | Apr 17, 2023 |
| Unknown       | Unknown                     | [56505e8956](https://bsd-hardware.info/?probe=56505e8956) | Apr 16, 2023 |
| Intel         | Q3XXG4-P V1.0               | [4fbc5291d9](https://bsd-hardware.info/?probe=4fbc5291d9) | Apr 16, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a29966f9ee](https://bsd-hardware.info/?probe=a29966f9ee) | Apr 16, 2023 |
| Unknown       | Unknown                     | [94151c41f1](https://bsd-hardware.info/?probe=94151c41f1) | Apr 14, 2023 |
| Unknown       | YL-SKUL6-7 Series           | [627e7a86c6](https://bsd-hardware.info/?probe=627e7a86c6) | Apr 13, 2023 |
| CncTion       | N5105-4L-I226 B0            | [0c7855ee11](https://bsd-hardware.info/?probe=0c7855ee11) | Apr 13, 2023 |
| Advantech     | UNO-2271G_V2                | [23e4b8d9b1](https://bsd-hardware.info/?probe=23e4b8d9b1) | Apr 12, 2023 |
| ASUSTek       | P10S-M Series               | [0b060edc48](https://bsd-hardware.info/?probe=0b060edc48) | Apr 12, 2023 |
| MW            | GMLK-2_5G4L                 | [9b1dbe0b9a](https://bsd-hardware.info/?probe=9b1dbe0b9a) | Apr 11, 2023 |
| Unknown       | Unknown                     | [cfa755bf6d](https://bsd-hardware.info/?probe=cfa755bf6d) | Apr 11, 2023 |
| CncTion       | N5105-4L-I226 B0            | [65d80d8aeb](https://bsd-hardware.info/?probe=65d80d8aeb) | Apr 09, 2023 |
| Gigabyte      | H610I DDR4                  | [59d65282c3](https://bsd-hardware.info/?probe=59d65282c3) | Apr 08, 2023 |
| ASRock        | A520M-ITX/ac                | [7a0ca560df](https://bsd-hardware.info/?probe=7a0ca560df) | Apr 08, 2023 |
| Unknown       | MANIFOLD 2-C                | [8fb3cbee23](https://bsd-hardware.info/?probe=8fb3cbee23) | Apr 07, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [f1cabdb067](https://bsd-hardware.info/?probe=f1cabdb067) | Apr 06, 2023 |
| Dell          | 04Y8V0 A02                  | [b4dab62ac2](https://bsd-hardware.info/?probe=b4dab62ac2) | Apr 05, 2023 |
| Dell          | 04Y8V0 A02                  | [24d7b97629](https://bsd-hardware.info/?probe=24d7b97629) | Apr 05, 2023 |
| Lanner        | FW-8771 C-GA                | [90d7028263](https://bsd-hardware.info/?probe=90d7028263) | Apr 05, 2023 |
| PC Engines    | apu4                        | [e91a75d782](https://bsd-hardware.info/?probe=e91a75d782) | Apr 05, 2023 |
| Intel         | SKYBAY                      | [81655c4fd5](https://bsd-hardware.info/?probe=81655c4fd5) | Apr 05, 2023 |
| maiyunda      | www.maiyunda.com            | [7cf52a3977](https://bsd-hardware.info/?probe=7cf52a3977) | Apr 03, 2023 |
| Techvision    | TVI7309X B0                 | [ca1360b939](https://bsd-hardware.info/?probe=ca1360b939) | Apr 03, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [bea5641594](https://bsd-hardware.info/?probe=bea5641594) | Apr 02, 2023 |
| MSI           | B450M MORTAR MAX            | [01bf5e8678](https://bsd-hardware.info/?probe=01bf5e8678) | Apr 02, 2023 |
| Gigabyte      | H55M-S2H                    | [60c66c5066](https://bsd-hardware.info/?probe=60c66c5066) | Mar 30, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [bde9fd671b](https://bsd-hardware.info/?probe=bde9fd671b) | Mar 30, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a160027cc2](https://bsd-hardware.info/?probe=a160027cc2) | Mar 30, 2023 |
| Dell          | 0VG93V A00                  | [1f3e086401](https://bsd-hardware.info/?probe=1f3e086401) | Mar 30, 2023 |
| Intel         | JSL MRD                     | [07adf23a3d](https://bsd-hardware.info/?probe=07adf23a3d) | Mar 28, 2023 |
| CncTion       | N5105-4L B0                 | [b6fd7cd6ae](https://bsd-hardware.info/?probe=b6fd7cd6ae) | Mar 27, 2023 |
| Shuttle       | FS81                        | [b80626e045](https://bsd-hardware.info/?probe=b80626e045) | Mar 26, 2023 |
| Lanner        | FW-7543 B-GA                | [3ed4cfc9c8](https://bsd-hardware.info/?probe=3ed4cfc9c8) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [15e452d25d](https://bsd-hardware.info/?probe=15e452d25d) | Mar 26, 2023 |
| Intel         | Q3XXG4-P V1.0               | [2f16e29f78](https://bsd-hardware.info/?probe=2f16e29f78) | Mar 26, 2023 |
| Protectli     | FW4B Ver                    | [fc5ab682fc](https://bsd-hardware.info/?probe=fc5ab682fc) | Mar 26, 2023 |
| Protectli     | FW4B Ver                    | [5082d62025](https://bsd-hardware.info/?probe=5082d62025) | Mar 25, 2023 |
| MW            | GMLK-2_5G4L                 | [41fa3f51d3](https://bsd-hardware.info/?probe=41fa3f51d3) | Mar 25, 2023 |
| Unknown       | Unknown                     | [387c27f1d7](https://bsd-hardware.info/?probe=387c27f1d7) | Mar 25, 2023 |
| PC Engines    | APU2                        | [4e4a81e456](https://bsd-hardware.info/?probe=4e4a81e456) | Mar 24, 2023 |
| Lex           | Pineview-D                  | [ca2fbb614d](https://bsd-hardware.info/?probe=ca2fbb614d) | Mar 24, 2023 |
| CncTion       | N5105-4L B0                 | [9561c72b9c](https://bsd-hardware.info/?probe=9561c72b9c) | Mar 24, 2023 |
| Intel         | Q3XXG4-P V1.0               | [083d2e65da](https://bsd-hardware.info/?probe=083d2e65da) | Mar 24, 2023 |
| ASRock        | A520M-ITX/ac                | [18877701a6](https://bsd-hardware.info/?probe=18877701a6) | Mar 24, 2023 |
| Protectli     | VP2420                      | [f07553b02c](https://bsd-hardware.info/?probe=f07553b02c) | Mar 23, 2023 |
| Protectli     | VP2420                      | [dfad78899e](https://bsd-hardware.info/?probe=dfad78899e) | Mar 23, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [720f15a1ce](https://bsd-hardware.info/?probe=720f15a1ce) | Mar 23, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [491c0ca78a](https://bsd-hardware.info/?probe=491c0ca78a) | Mar 22, 2023 |
| Intel         | Q3XXG4-P V1.0               | [680002292e](https://bsd-hardware.info/?probe=680002292e) | Mar 22, 2023 |
| MW            | GMLK-2_5G4L                 | [b3f0879ebf](https://bsd-hardware.info/?probe=b3f0879ebf) | Mar 22, 2023 |
| Intel         | SKYBAY                      | [83ea0b27b1](https://bsd-hardware.info/?probe=83ea0b27b1) | Mar 21, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [bcada44b09](https://bsd-hardware.info/?probe=bcada44b09) | Mar 21, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | [7ae004c035](https://bsd-hardware.info/?probe=7ae004c035) | Mar 21, 2023 |
| Unknown       | Unknown                     | [e4365dfa60](https://bsd-hardware.info/?probe=e4365dfa60) | Mar 20, 2023 |
| ASRock        | B550M Pro4                  | [4dc54510d2](https://bsd-hardware.info/?probe=4dc54510d2) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | [cab50cddd5](https://bsd-hardware.info/?probe=cab50cddd5) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | [ff4dda40eb](https://bsd-hardware.info/?probe=ff4dda40eb) | Mar 19, 2023 |
| Intel         | SKYBAY                      | [7bd7f393b1](https://bsd-hardware.info/?probe=7bd7f393b1) | Mar 18, 2023 |
| Intel         | SKYBAY                      | [a8f1d29e24](https://bsd-hardware.info/?probe=a8f1d29e24) | Mar 18, 2023 |
| MSI           | X299 PRO                    | [a26d096ecb](https://bsd-hardware.info/?probe=a26d096ecb) | Mar 18, 2023 |
| Fujitsu       | D3313-S3 S26361-D3313-S3    | [1bf34a929a](https://bsd-hardware.info/?probe=1bf34a929a) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2ceda5b586](https://bsd-hardware.info/?probe=2ceda5b586) | Mar 17, 2023 |
| ASRock        | J5040-ITX                   | [435dc7ee7b](https://bsd-hardware.info/?probe=435dc7ee7b) | Mar 15, 2023 |
| Unknown       | Unknown                     | [68b45d5083](https://bsd-hardware.info/?probe=68b45d5083) | Mar 15, 2023 |
| ASRock        | A520M-ITX/ac                | [1ccc8081fd](https://bsd-hardware.info/?probe=1ccc8081fd) | Mar 15, 2023 |
| Foxconn       | H61M/H61M-S                 | [865fbff42a](https://bsd-hardware.info/?probe=865fbff42a) | Mar 14, 2023 |
| ASRock        | Q1900M                      | [9570525d52](https://bsd-hardware.info/?probe=9570525d52) | Mar 14, 2023 |
| MW            | GMLK-2_5G4L                 | [5211185a2a](https://bsd-hardware.info/?probe=5211185a2a) | Mar 14, 2023 |
| HP            | 8056                        | [e1d2423153](https://bsd-hardware.info/?probe=e1d2423153) | Mar 13, 2023 |
| HP            | 8056                        | [d89b45ea6d](https://bsd-hardware.info/?probe=d89b45ea6d) | Mar 13, 2023 |
| Dell          | 0W0CHX A00                  | [85a9fddd44](https://bsd-hardware.info/?probe=85a9fddd44) | Mar 12, 2023 |
| MW            | GMLK-2_5G4L                 | [fee0ff7804](https://bsd-hardware.info/?probe=fee0ff7804) | Mar 12, 2023 |
| Acer          | Veriton N2620G              | [fa57448331](https://bsd-hardware.info/?probe=fa57448331) | Mar 12, 2023 |
| ASUSTek       | P8Z68-V                     | [3d8ef63e18](https://bsd-hardware.info/?probe=3d8ef63e18) | Mar 11, 2023 |
| ASUSTek       | H110I-PLUS                  | [8736b12c9a](https://bsd-hardware.info/?probe=8736b12c9a) | Mar 11, 2023 |
| MSI           | X299 PRO                    | [0cebc094ca](https://bsd-hardware.info/?probe=0cebc094ca) | Mar 10, 2023 |
| Unknown       | Unknown                     | [2a55137e71](https://bsd-hardware.info/?probe=2a55137e71) | Mar 10, 2023 |
| CheckPoint    | PH-30-00                    | [ec7a5f05fd](https://bsd-hardware.info/?probe=ec7a5f05fd) | Mar 09, 2023 |
| Unknown       | Unknown                     | [d7b171d0bb](https://bsd-hardware.info/?probe=d7b171d0bb) | Mar 09, 2023 |
| Protectli     | VP2420                      | [21d2214da6](https://bsd-hardware.info/?probe=21d2214da6) | Mar 08, 2023 |
| Unknown       | Unknown                     | [86c132c242](https://bsd-hardware.info/?probe=86c132c242) | Mar 07, 2023 |
| MW            | GMLK-2_5G4L                 | [b91b7cf52d](https://bsd-hardware.info/?probe=b91b7cf52d) | Mar 06, 2023 |
| Techvision    | TVI7309X B0                 | [789ae683f7](https://bsd-hardware.info/?probe=789ae683f7) | Mar 05, 2023 |
| ASUSTek       | PRO B460M-C                 | [a3f77b82cc](https://bsd-hardware.info/?probe=a3f77b82cc) | Mar 05, 2023 |
| Dell          | VEP-4600-V910 0PDG1JA02     | [5070c11c54](https://bsd-hardware.info/?probe=5070c11c54) | Mar 05, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [3d912f92aa](https://bsd-hardware.info/?probe=3d912f92aa) | Mar 05, 2023 |
| ASRock        | E350M1                      | [461f8cca23](https://bsd-hardware.info/?probe=461f8cca23) | Mar 04, 2023 |
| Techvision    | TVI7309X B0                 | [6067b3f58d](https://bsd-hardware.info/?probe=6067b3f58d) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | [bbbd05a4c3](https://bsd-hardware.info/?probe=bbbd05a4c3) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | [9ab07ae7f1](https://bsd-hardware.info/?probe=9ab07ae7f1) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | [228816d44e](https://bsd-hardware.info/?probe=228816d44e) | Mar 03, 2023 |
| Unknown       | Unknown                     | [81bf3cf726](https://bsd-hardware.info/?probe=81bf3cf726) | Mar 03, 2023 |
| Intel         | DENLOW_WS                   | [2b70fdb96a](https://bsd-hardware.info/?probe=2b70fdb96a) | Mar 02, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [29290b1b9c](https://bsd-hardware.info/?probe=29290b1b9c) | Mar 01, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [5eb87a21db](https://bsd-hardware.info/?probe=5eb87a21db) | Mar 01, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [39d5f658ce](https://bsd-hardware.info/?probe=39d5f658ce) | Feb 28, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [dcf3f03ddc](https://bsd-hardware.info/?probe=dcf3f03ddc) | Feb 28, 2023 |
| Supermicro    | PDSBM                       | [1dea83dd64](https://bsd-hardware.info/?probe=1dea83dd64) | Feb 26, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [27e756f63d](https://bsd-hardware.info/?probe=27e756f63d) | Feb 26, 2023 |
| Foxconn       | 2A8Ch                       | [96a8673b26](https://bsd-hardware.info/?probe=96a8673b26) | Feb 26, 2023 |
| NF541         | 1.0                         | [863e6235d4](https://bsd-hardware.info/?probe=863e6235d4) | Feb 26, 2023 |
| Unknown       | YL-J3160L4                  | [b774e80761](https://bsd-hardware.info/?probe=b774e80761) | Feb 25, 2023 |
| ASRock        | X470 Gaming K4              | [fbff29a62a](https://bsd-hardware.info/?probe=fbff29a62a) | Feb 25, 2023 |
| Unknown       | Unknown                     | [87ad08a144](https://bsd-hardware.info/?probe=87ad08a144) | Feb 25, 2023 |
| Lenovo        | ThinkCentre M91p 7033A2G    | [25528a00f3](https://bsd-hardware.info/?probe=25528a00f3) | Feb 24, 2023 |
| MSI           | X299 PRO                    | [3ca12f88d9](https://bsd-hardware.info/?probe=3ca12f88d9) | Feb 24, 2023 |
| Unknown       | Unknown                     | [efab6dedba](https://bsd-hardware.info/?probe=efab6dedba) | Feb 24, 2023 |
| Protectli     | VP2420                      | [ac2228fa2b](https://bsd-hardware.info/?probe=ac2228fa2b) | Feb 24, 2023 |
| Dell          | 0C27VV A02                  | [5899533edd](https://bsd-hardware.info/?probe=5899533edd) | Feb 23, 2023 |
| Fujitsu       | D3543-A2 S26361-D3543-A2... | [68165a639f](https://bsd-hardware.info/?probe=68165a639f) | Feb 22, 2023 |
| PC Engines    | APU2                        | [05966fb4dc](https://bsd-hardware.info/?probe=05966fb4dc) | Feb 22, 2023 |
| Protectli     | VP2420                      | [541c13b778](https://bsd-hardware.info/?probe=541c13b778) | Feb 22, 2023 |
| Dell          | 0C27VV A02                  | [a10df954b7](https://bsd-hardware.info/?probe=a10df954b7) | Feb 22, 2023 |
| Intel         | QHSW02                      | [6bec4024a8](https://bsd-hardware.info/?probe=6bec4024a8) | Feb 22, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [3f78b1a6c7](https://bsd-hardware.info/?probe=3f78b1a6c7) | Feb 20, 2023 |
| Protectli     | VP2420                      | [5d8285d184](https://bsd-hardware.info/?probe=5d8285d184) | Feb 19, 2023 |
| CncTion       | J4125-4L-I225               | [6d2c693305](https://bsd-hardware.info/?probe=6d2c693305) | Feb 19, 2023 |
| Yanling       | YL-CLU6L-V1                 | [8d1fa6606b](https://bsd-hardware.info/?probe=8d1fa6606b) | Feb 19, 2023 |
| Unknown       | Unknown                     | [1478bc453d](https://bsd-hardware.info/?probe=1478bc453d) | Feb 17, 2023 |
| Unknown       | Unknown                     | [ac4b0186ff](https://bsd-hardware.info/?probe=ac4b0186ff) | Feb 17, 2023 |
| ZOTAC         | Unknown                     | [0adf0ca671](https://bsd-hardware.info/?probe=0adf0ca671) | Feb 17, 2023 |
| ASUSTek       | N3050M-E                    | [7d6e696fb4](https://bsd-hardware.info/?probe=7d6e696fb4) | Feb 17, 2023 |
| Unknown       | Unknown                     | [71cc084a9c](https://bsd-hardware.info/?probe=71cc084a9c) | Feb 16, 2023 |
| PC Engines    | APU                         | [1162545537](https://bsd-hardware.info/?probe=1162545537) | Feb 15, 2023 |
| ASUSTek       | PRIME A320M-K               | [35aa7d7f04](https://bsd-hardware.info/?probe=35aa7d7f04) | Feb 15, 2023 |
| Supermicro    | X7SPA-HF                    | [6a91635684](https://bsd-hardware.info/?probe=6a91635684) | Feb 14, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a9d6421d3c](https://bsd-hardware.info/?probe=a9d6421d3c) | Feb 14, 2023 |
| Yanling       | YL-CLU6L-V1                 | [9c12ee263f](https://bsd-hardware.info/?probe=9c12ee263f) | Feb 14, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | [d69aba5432](https://bsd-hardware.info/?probe=d69aba5432) | Feb 14, 2023 |
| Unknown       | Unknown                     | [98819b1db5](https://bsd-hardware.info/?probe=98819b1db5) | Feb 13, 2023 |
| Unknown       | Unknown                     | [dbe1c51575](https://bsd-hardware.info/?probe=dbe1c51575) | Feb 12, 2023 |
| ASUSTek       | P8Z68-V                     | [74ebc950e2](https://bsd-hardware.info/?probe=74ebc950e2) | Feb 11, 2023 |
| Yanling       | YL-KBR6L Ver:1.00           | [516c778d65](https://bsd-hardware.info/?probe=516c778d65) | Feb 11, 2023 |
| Foxconn       | 2A8Ch                       | [2874f7a7fa](https://bsd-hardware.info/?probe=2874f7a7fa) | Feb 11, 2023 |
| Gigabyte      | Z490 VISION G               | [6f8ad1a8b9](https://bsd-hardware.info/?probe=6f8ad1a8b9) | Feb 11, 2023 |
| Techvision    | TVI7309X B0                 | [c4c07aec07](https://bsd-hardware.info/?probe=c4c07aec07) | Feb 11, 2023 |
| Unknown       | Unknown                     | [18362d0f11](https://bsd-hardware.info/?probe=18362d0f11) | Feb 10, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [12e4e26e40](https://bsd-hardware.info/?probe=12e4e26e40) | Feb 10, 2023 |
| Foxconn       | 2A8Ch                       | [84c0208f8d](https://bsd-hardware.info/?probe=84c0208f8d) | Feb 10, 2023 |
| ASUSTek       | P7P55D DELUXE               | [dd9685a909](https://bsd-hardware.info/?probe=dd9685a909) | Feb 09, 2023 |
| ASUSTek       | H110I-PLUS                  | [4347c8c716](https://bsd-hardware.info/?probe=4347c8c716) | Feb 09, 2023 |
| ASRock        | A520M-ITX/ac                | [e5b2e1bb9d](https://bsd-hardware.info/?probe=e5b2e1bb9d) | Feb 09, 2023 |
| ASRock        | A520M-ITX/ac                | [f66883c5c2](https://bsd-hardware.info/?probe=f66883c5c2) | Feb 09, 2023 |
| ASUSTek       | P10S-M Series               | [78975e45b7](https://bsd-hardware.info/?probe=78975e45b7) | Feb 09, 2023 |
| Unknown       | MANIFOLD 2-C                | [1a23b05eca](https://bsd-hardware.info/?probe=1a23b05eca) | Feb 07, 2023 |
| Unknown       | Unknown                     | [f4978c3575](https://bsd-hardware.info/?probe=f4978c3575) | Feb 07, 2023 |
| ASUSTek       | P10S-M Series               | [24b74b8ce3](https://bsd-hardware.info/?probe=24b74b8ce3) | Feb 07, 2023 |
| MW            | GMLK-2_5G4L                 | [39fa7db109](https://bsd-hardware.info/?probe=39fa7db109) | Feb 07, 2023 |
| Unknown       | MANIFOLD 2-C                | [923b6d85fd](https://bsd-hardware.info/?probe=923b6d85fd) | Feb 06, 2023 |
| PC Engines    | APU2                        | [e4e00e259c](https://bsd-hardware.info/?probe=e4e00e259c) | Feb 06, 2023 |
| ASUSTek       | P8Z77-M                     | [627bdfafb7](https://bsd-hardware.info/?probe=627bdfafb7) | Feb 06, 2023 |
| MSI           | B450M MORTAR MAX            | [ec37957aed](https://bsd-hardware.info/?probe=ec37957aed) | Feb 05, 2023 |
| Intel         | QHSW02                      | [16722b7429](https://bsd-hardware.info/?probe=16722b7429) | Feb 04, 2023 |
| Unknown       | Unknown                     | [8fdace282e](https://bsd-hardware.info/?probe=8fdace282e) | Feb 04, 2023 |
| ASUSTek       | P10S-M Series               | [c6fc0a639d](https://bsd-hardware.info/?probe=c6fc0a639d) | Feb 03, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [77c7c36f87](https://bsd-hardware.info/?probe=77c7c36f87) | Feb 03, 2023 |
| Unknown       | Unknown                     | [433e29e7bd](https://bsd-hardware.info/?probe=433e29e7bd) | Feb 01, 2023 |
| Supermicro    | X7SPA-HF                    | [2d410c6882](https://bsd-hardware.info/?probe=2d410c6882) | Feb 01, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [9fa25e53f1](https://bsd-hardware.info/?probe=9fa25e53f1) | Feb 01, 2023 |
| PC Engines    | apu4                        | [0d1561fea9](https://bsd-hardware.info/?probe=0d1561fea9) | Jan 31, 2023 |
| Intel         | Q3XXG4-P V1.0               | [418694e14d](https://bsd-hardware.info/?probe=418694e14d) | Jan 31, 2023 |
| Lanner        | FW-7543 B-GA                | [149345d14c](https://bsd-hardware.info/?probe=149345d14c) | Jan 30, 2023 |
| HP            | 1825                        | [717279c19f](https://bsd-hardware.info/?probe=717279c19f) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4c25e80924](https://bsd-hardware.info/?probe=4c25e80924) | Jan 29, 2023 |
| Shenzhen M... | F4BHD                       | [b2540f3beb](https://bsd-hardware.info/?probe=b2540f3beb) | Jan 29, 2023 |
| HP            | 21B4 A01                    | [8df824afd4](https://bsd-hardware.info/?probe=8df824afd4) | Jan 28, 2023 |
| Gigabyte      | B550 AORUS PRO              | [8fd7f80256](https://bsd-hardware.info/?probe=8fd7f80256) | Jan 28, 2023 |
| ASUSTek       | M4A89TD PRO USB3            | [1328d01296](https://bsd-hardware.info/?probe=1328d01296) | Jan 28, 2023 |
| Techvision    | TVI7309X B0                 | [937a255571](https://bsd-hardware.info/?probe=937a255571) | Jan 28, 2023 |
| CncTion       | N5105-4L B0                 | [a7fe868f42](https://bsd-hardware.info/?probe=a7fe868f42) | Jan 27, 2023 |
| Unknown       | Unknown                     | [d3750005c2](https://bsd-hardware.info/?probe=d3750005c2) | Jan 27, 2023 |
| ASUSTek       | PRIME X570-P                | [232a81d2ed](https://bsd-hardware.info/?probe=232a81d2ed) | Jan 27, 2023 |
| ASRock        | H570M-ITX/ac                | [4ebeac2699](https://bsd-hardware.info/?probe=4ebeac2699) | Jan 26, 2023 |
| PC Engines    | APU2                        | [436e596f40](https://bsd-hardware.info/?probe=436e596f40) | Jan 26, 2023 |
| ASUSTek       | PRIME A320M-K               | [cdad2f0001](https://bsd-hardware.info/?probe=cdad2f0001) | Jan 23, 2023 |
| AWOW          | AK50                        | [8c983f91e4](https://bsd-hardware.info/?probe=8c983f91e4) | Jan 22, 2023 |
| PC Engines    | APU2                        | [658569ae16](https://bsd-hardware.info/?probe=658569ae16) | Jan 22, 2023 |
| HP            | 1825                        | [2705218636](https://bsd-hardware.info/?probe=2705218636) | Jan 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [59c83cb9ee](https://bsd-hardware.info/?probe=59c83cb9ee) | Jan 21, 2023 |
| Fujitsu       | D3243-S1 S26361-D3243-S1    | [d69c3cae4c](https://bsd-hardware.info/?probe=d69c3cae4c) | Jan 21, 2023 |
| ASRock        | A520M-ITX/ac                | [e6873fe42f](https://bsd-hardware.info/?probe=e6873fe42f) | Jan 21, 2023 |
| Techvision    | TVI7309X B0                 | [495563926c](https://bsd-hardware.info/?probe=495563926c) | Jan 21, 2023 |
| ASRock        | A520M-ITX/ac                | [f862df1689](https://bsd-hardware.info/?probe=f862df1689) | Jan 20, 2023 |
| Techvision    | TVI7309X B0                 | [d4018ae0f3](https://bsd-hardware.info/?probe=d4018ae0f3) | Jan 20, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [4bcc8752f4](https://bsd-hardware.info/?probe=4bcc8752f4) | Jan 20, 2023 |
| ShenZhen M... | MW-NANO-APL-4L              | [48206a7d4a](https://bsd-hardware.info/?probe=48206a7d4a) | Jan 19, 2023 |
| Unknown       | Unknown                     | [35e269ef1c](https://bsd-hardware.info/?probe=35e269ef1c) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [b528c0bbe3](https://bsd-hardware.info/?probe=b528c0bbe3) | Jan 18, 2023 |
| BESSTAR Te... | TH50                        | [b9de543167](https://bsd-hardware.info/?probe=b9de543167) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | [11948a0ab1](https://bsd-hardware.info/?probe=11948a0ab1) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [f7de27b0ca](https://bsd-hardware.info/?probe=f7de27b0ca) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [9eee9cc526](https://bsd-hardware.info/?probe=9eee9cc526) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | [46178567ff](https://bsd-hardware.info/?probe=46178567ff) | Jan 18, 2023 |
| Wortmann      | terra MiniPC                | [be22193265](https://bsd-hardware.info/?probe=be22193265) | Jan 17, 2023 |
| MSI           | MS-9897                     | [8aa91d17fa](https://bsd-hardware.info/?probe=8aa91d17fa) | Jan 17, 2023 |
| MSI           | MS-9897                     | [0ccc361bd9](https://bsd-hardware.info/?probe=0ccc361bd9) | Jan 17, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [1ef7026e21](https://bsd-hardware.info/?probe=1ef7026e21) | Jan 15, 2023 |
| Techvision    | TVI7309X B0                 | [8aebf3b22a](https://bsd-hardware.info/?probe=8aebf3b22a) | Jan 15, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [17d73c4d40](https://bsd-hardware.info/?probe=17d73c4d40) | Jan 14, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [ad7329411a](https://bsd-hardware.info/?probe=ad7329411a) | Jan 14, 2023 |
| Unknown       | Unknown                     | [fba3e00878](https://bsd-hardware.info/?probe=fba3e00878) | Jan 13, 2023 |
| HP            | 82A1                        | [567894a0bb](https://bsd-hardware.info/?probe=567894a0bb) | Jan 12, 2023 |
| PC Engines    | APU3                        | [b080710198](https://bsd-hardware.info/?probe=b080710198) | Jan 12, 2023 |
| ASRockRack    | X470D4U2/1N1                | [07f15d0014](https://bsd-hardware.info/?probe=07f15d0014) | Jan 11, 2023 |
| CncTion       | J4125-4L-I225               | [56a5c0de6e](https://bsd-hardware.info/?probe=56a5c0de6e) | Jan 11, 2023 |
| PC Engines    | APU2                        | [1e65573dfa](https://bsd-hardware.info/?probe=1e65573dfa) | Jan 10, 2023 |
| Unknown       | Unknown                     | [e870cfc473](https://bsd-hardware.info/?probe=e870cfc473) | Jan 10, 2023 |
| MW            | GMLK-2_5G4L                 | [55bd6297fa](https://bsd-hardware.info/?probe=55bd6297fa) | Jan 10, 2023 |
| MSI           | X299 PRO                    | [a1f37f69d9](https://bsd-hardware.info/?probe=a1f37f69d9) | Jan 08, 2023 |
| Dell          | 0YNVJG A01                  | [8bb9472e6b](https://bsd-hardware.info/?probe=8bb9472e6b) | Jan 08, 2023 |
| Unknown       | Unknown                     | [7b5333020a](https://bsd-hardware.info/?probe=7b5333020a) | Jan 08, 2023 |
| Unknown       | Unknown                     | [1e3ebde983](https://bsd-hardware.info/?probe=1e3ebde983) | Jan 07, 2023 |
| ASUSTek       | F2A85-M                     | [e25da8b10a](https://bsd-hardware.info/?probe=e25da8b10a) | Jan 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | [fa12ea67eb](https://bsd-hardware.info/?probe=fa12ea67eb) | Jan 06, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [92c2e73bd4](https://bsd-hardware.info/?probe=92c2e73bd4) | Jan 06, 2023 |
| Unknown       | Unknown                     | [cc8588d977](https://bsd-hardware.info/?probe=cc8588d977) | Jan 05, 2023 |
| MW            | GMLK-2_5G4L                 | [39149acdbd](https://bsd-hardware.info/?probe=39149acdbd) | Jan 04, 2023 |
| Unknown       | J3160-4L                    | [849af12174](https://bsd-hardware.info/?probe=849af12174) | Jan 02, 2023 |
| CncTion       | N5105-4L B0                 | [70b1ca485d](https://bsd-hardware.info/?probe=70b1ca485d) | Jan 02, 2023 |
| ASRock        | E350M1                      | [6a7e5c8d0c](https://bsd-hardware.info/?probe=6a7e5c8d0c) | Jan 01, 2023 |
| HP            | 1825                        | [f7e94decd0](https://bsd-hardware.info/?probe=f7e94decd0) | Dec 31, 2022 |
| HP            | 1825                        | [afc1259508](https://bsd-hardware.info/?probe=afc1259508) | Dec 31, 2022 |
| CncTion       | N5105-4L B0                 | [cd3e4f7122](https://bsd-hardware.info/?probe=cd3e4f7122) | Dec 30, 2022 |
| Protectli     | FW4B                        | [406fe72c22](https://bsd-hardware.info/?probe=406fe72c22) | Dec 30, 2022 |
| PC Engines    | APU2                        | [7aaf2d91ba](https://bsd-hardware.info/?probe=7aaf2d91ba) | Dec 29, 2022 |
| Lanner        | FW-7543 B-GA                | [6c145361a3](https://bsd-hardware.info/?probe=6c145361a3) | Dec 29, 2022 |
| Unknown       | Unknown                     | [5b8ad02694](https://bsd-hardware.info/?probe=5b8ad02694) | Dec 28, 2022 |
| Unknown       | Unknown                     | [c3b95220d7](https://bsd-hardware.info/?probe=c3b95220d7) | Dec 28, 2022 |
| ASUSTek       | H97-PLUS                    | [f2a248dcfe](https://bsd-hardware.info/?probe=f2a248dcfe) | Dec 26, 2022 |
| HP            | 8062                        | [f4d3eb024d](https://bsd-hardware.info/?probe=f4d3eb024d) | Dec 25, 2022 |
| Biostar       | A10N-8800E                  | [d3d1107f77](https://bsd-hardware.info/?probe=d3d1107f77) | Dec 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | [58b47341c9](https://bsd-hardware.info/?probe=58b47341c9) | Dec 23, 2022 |
| ASRock        | B75M R2.0                   | [3a8d5c61b6](https://bsd-hardware.info/?probe=3a8d5c61b6) | Dec 23, 2022 |
| Unknown       | QD-WHLU01                   | [a0fb185069](https://bsd-hardware.info/?probe=a0fb185069) | Dec 23, 2022 |
| Unknown       | MANIFOLD 2-C                | [bc2c536004](https://bsd-hardware.info/?probe=bc2c536004) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | [daaad6a386](https://bsd-hardware.info/?probe=daaad6a386) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | [67bc182d1d](https://bsd-hardware.info/?probe=67bc182d1d) | Dec 23, 2022 |
| CncTion       | N5105-4L B0                 | [78bcccda01](https://bsd-hardware.info/?probe=78bcccda01) | Dec 22, 2022 |
| ASRock        | A75M-HVS                    | [01d8e43ee1](https://bsd-hardware.info/?probe=01d8e43ee1) | Dec 22, 2022 |
| AAEON         | FWS-2251 V1.0               | [a4ff0a7ec5](https://bsd-hardware.info/?probe=a4ff0a7ec5) | Dec 22, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [2ac107df0f](https://bsd-hardware.info/?probe=2ac107df0f) | Dec 22, 2022 |
| Dell          | 0WR7PY A02                  | [0c3fea5eb0](https://bsd-hardware.info/?probe=0c3fea5eb0) | Dec 22, 2022 |
| ASRock        | 4X4-4000 Series             | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [2ea413db31](https://bsd-hardware.info/?probe=2ea413db31) | Dec 20, 2022 |
| HP            | ProLiant MicroServer Gen... | [8de4ff8626](https://bsd-hardware.info/?probe=8de4ff8626) | Dec 20, 2022 |
| Unknown       | Unknown                     | [5d37a0669c](https://bsd-hardware.info/?probe=5d37a0669c) | Dec 19, 2022 |
| Dell          | 0WR7PY A02                  | [67baacfc7d](https://bsd-hardware.info/?probe=67baacfc7d) | Dec 19, 2022 |
| ASUSTek       | H97-PLUS                    | [c9de65beeb](https://bsd-hardware.info/?probe=c9de65beeb) | Dec 19, 2022 |
| PC Engines    | APU2                        | [5de84cb508](https://bsd-hardware.info/?probe=5de84cb508) | Dec 19, 2022 |
| Gigabyte      | J3455N-D3H                  | [fc7928dfe9](https://bsd-hardware.info/?probe=fc7928dfe9) | Dec 18, 2022 |
| MSI           | X299 PRO                    | [beec8001a1](https://bsd-hardware.info/?probe=beec8001a1) | Dec 17, 2022 |
| Intel         | CRESCENTBAY                 | [7981529337](https://bsd-hardware.info/?probe=7981529337) | Dec 17, 2022 |
| ASRock        | Q2900M                      | [42a53e5201](https://bsd-hardware.info/?probe=42a53e5201) | Dec 16, 2022 |
| ASRock        | A75M-HVS                    | [fa8c102cfd](https://bsd-hardware.info/?probe=fa8c102cfd) | Dec 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | [3faaaa8209](https://bsd-hardware.info/?probe=3faaaa8209) | Dec 16, 2022 |
| Unknown       | Unknown                     | [01e26ec145](https://bsd-hardware.info/?probe=01e26ec145) | Dec 15, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [40911b66e2](https://bsd-hardware.info/?probe=40911b66e2) | Dec 15, 2022 |
| Unknown       | Unknown                     | [e3508ce360](https://bsd-hardware.info/?probe=e3508ce360) | Dec 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [35ecaf0406](https://bsd-hardware.info/?probe=35ecaf0406) | Dec 15, 2022 |
| Unknown       | Unknown                     | [210418cc84](https://bsd-hardware.info/?probe=210418cc84) | Dec 15, 2022 |
| MW            | GMLK-2_5G4L                 | [cb16bb9431](https://bsd-hardware.info/?probe=cb16bb9431) | Dec 14, 2022 |
| NF541         | 1.0                         | [b0644bada6](https://bsd-hardware.info/?probe=b0644bada6) | Dec 14, 2022 |
| Unknown       | Unknown                     | [ec6827e543](https://bsd-hardware.info/?probe=ec6827e543) | Dec 13, 2022 |
| Techvision    | TVI7309X B0                 | [af9df0d2c9](https://bsd-hardware.info/?probe=af9df0d2c9) | Dec 13, 2022 |
| Unknown       | Unknown                     | [9ee8d1082b](https://bsd-hardware.info/?probe=9ee8d1082b) | Dec 12, 2022 |
| Shuttle       | DH370                       | [1b938aa1a4](https://bsd-hardware.info/?probe=1b938aa1a4) | Dec 12, 2022 |
| Unknown       | MANIFOLD 2-C                | [ba191bd994](https://bsd-hardware.info/?probe=ba191bd994) | Dec 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [3124aaaf95](https://bsd-hardware.info/?probe=3124aaaf95) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [b1bd01549a](https://bsd-hardware.info/?probe=b1bd01549a) | Dec 11, 2022 |
| Unknown       | Unknown                     | [def65f518e](https://bsd-hardware.info/?probe=def65f518e) | Dec 10, 2022 |
| MSI           | B450M MORTAR MAX            | [d8d6af9e56](https://bsd-hardware.info/?probe=d8d6af9e56) | Dec 10, 2022 |
| Protectli     | FW4B Ver                    | [33395e819a](https://bsd-hardware.info/?probe=33395e819a) | Dec 10, 2022 |
| Hardkernel    | ODROID-H3                   | [cd6aa62212](https://bsd-hardware.info/?probe=cd6aa62212) | Dec 09, 2022 |
| Unknown       | Unknown                     | [493df1f529](https://bsd-hardware.info/?probe=493df1f529) | Dec 09, 2022 |
| PC Engines    | apu4                        | [3e3ab7f196](https://bsd-hardware.info/?probe=3e3ab7f196) | Dec 09, 2022 |
| MW            | GMLK-2_5G4L                 | [84f8198c18](https://bsd-hardware.info/?probe=84f8198c18) | Dec 08, 2022 |
| Dell          | 0G261D A00                  | [24b9490c77](https://bsd-hardware.info/?probe=24b9490c77) | Dec 06, 2022 |
| Protectli     | FW4B Ver                    | [eaa3b9783e](https://bsd-hardware.info/?probe=eaa3b9783e) | Dec 05, 2022 |
| PC Engines    | apu4                        | [72061eb254](https://bsd-hardware.info/?probe=72061eb254) | Dec 05, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [aa9482884f](https://bsd-hardware.info/?probe=aa9482884f) | Dec 05, 2022 |
| Shuttle       | FS77U                       | [4172b79cfc](https://bsd-hardware.info/?probe=4172b79cfc) | Dec 04, 2022 |
| Unknown       | Unknown                     | [af4f0984ae](https://bsd-hardware.info/?probe=af4f0984ae) | Dec 04, 2022 |
| ASUSTek       | E35M1-I DELUXE              | [1a183385c7](https://bsd-hardware.info/?probe=1a183385c7) | Dec 04, 2022 |
| Unknown       | Unknown                     | [d9113585f0](https://bsd-hardware.info/?probe=d9113585f0) | Dec 04, 2022 |
| Intel         | D33217CK G76541-300         | [545a39b1e4](https://bsd-hardware.info/?probe=545a39b1e4) | Dec 02, 2022 |
| Intel         | D33217CK G76541-300         | [bbdd9a1b98](https://bsd-hardware.info/?probe=bbdd9a1b98) | Nov 30, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [ae55a799e8](https://bsd-hardware.info/?probe=ae55a799e8) | Nov 28, 2022 |
| PC Engines    | apu6                        | [13dcbe5748](https://bsd-hardware.info/?probe=13dcbe5748) | Nov 27, 2022 |
| Unknown       | Unknown                     | [d4246caa0f](https://bsd-hardware.info/?probe=d4246caa0f) | Nov 24, 2022 |
| MW            | GMLK-2_5G4L                 | [b6bbaa13e8](https://bsd-hardware.info/?probe=b6bbaa13e8) | Nov 24, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [1860d18e39](https://bsd-hardware.info/?probe=1860d18e39) | Nov 23, 2022 |
| PC Engines    | apu6                        | [bc334caa03](https://bsd-hardware.info/?probe=bc334caa03) | Nov 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d893e02d90](https://bsd-hardware.info/?probe=d893e02d90) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [7518e4f06a](https://bsd-hardware.info/?probe=7518e4f06a) | Nov 21, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [298fde4e33](https://bsd-hardware.info/?probe=298fde4e33) | Nov 21, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [f6491f1950](https://bsd-hardware.info/?probe=f6491f1950) | Nov 20, 2022 |
| Dell          | 0YNVJG A01                  | [15d32e1e36](https://bsd-hardware.info/?probe=15d32e1e36) | Nov 20, 2022 |
| PC Engines    | apu6                        | [1e9acc3ae6](https://bsd-hardware.info/?probe=1e9acc3ae6) | Nov 18, 2022 |
| Fujitsu       | D3289-A1 S26361-D3289-A1... | [dae7027898](https://bsd-hardware.info/?probe=dae7027898) | Nov 18, 2022 |
| ASRock        | N3150M                      | [d3b3be7936](https://bsd-hardware.info/?probe=d3b3be7936) | Nov 17, 2022 |
| ASUSTek       | H110I-PLUS                  | [f1f56fe86c](https://bsd-hardware.info/?probe=f1f56fe86c) | Nov 17, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [64d8291a91](https://bsd-hardware.info/?probe=64d8291a91) | Nov 17, 2022 |
| PC Engines    | apu4                        | [212f27d85a](https://bsd-hardware.info/?probe=212f27d85a) | Nov 17, 2022 |
| MSI           | X299 PRO                    | [d615157be7](https://bsd-hardware.info/?probe=d615157be7) | Nov 16, 2022 |
| ASRock        | J5040-ITX                   | [753c68cfb9](https://bsd-hardware.info/?probe=753c68cfb9) | Nov 16, 2022 |
| MSI           | B450M MORTAR MAX            | [15657b37e2](https://bsd-hardware.info/?probe=15657b37e2) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | [f4a8c42773](https://bsd-hardware.info/?probe=f4a8c42773) | Nov 15, 2022 |
| PC Engines    | apu4                        | [589dec199e](https://bsd-hardware.info/?probe=589dec199e) | Nov 15, 2022 |
| Shuttle       | FH61V                       | [012a5c0fcc](https://bsd-hardware.info/?probe=012a5c0fcc) | Nov 14, 2022 |
| ASUSTek       | H110I-PLUS                  | [0079838512](https://bsd-hardware.info/?probe=0079838512) | Nov 13, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [ee16ad1ffb](https://bsd-hardware.info/?probe=ee16ad1ffb) | Nov 12, 2022 |
| PC Engines    | APU2                        | [34960ed27c](https://bsd-hardware.info/?probe=34960ed27c) | Nov 12, 2022 |
| ASUSTek       | H110I-PLUS                  | [e3161d12c5](https://bsd-hardware.info/?probe=e3161d12c5) | Nov 11, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [0fcbc68304](https://bsd-hardware.info/?probe=0fcbc68304) | Nov 11, 2022 |
| HP            | 18E9                        | [b9df70f7eb](https://bsd-hardware.info/?probe=b9df70f7eb) | Nov 11, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [569d5b0cca](https://bsd-hardware.info/?probe=569d5b0cca) | Nov 10, 2022 |
| CheckPoint    | PH-30-00                    | [e42768cd01](https://bsd-hardware.info/?probe=e42768cd01) | Nov 10, 2022 |
| HP            | 21B4 A01                    | [c064c50fea](https://bsd-hardware.info/?probe=c064c50fea) | Nov 09, 2022 |
| HP            | 21B4 A01                    | [e5c599dfab](https://bsd-hardware.info/?probe=e5c599dfab) | Nov 09, 2022 |
| HP            | 21B4 A01                    | [0a3ba5478b](https://bsd-hardware.info/?probe=0a3ba5478b) | Nov 09, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [c32a7b407d](https://bsd-hardware.info/?probe=c32a7b407d) | Nov 09, 2022 |
| ASRock        | H570M-ITX/ac                | [8addd09aa7](https://bsd-hardware.info/?probe=8addd09aa7) | Nov 09, 2022 |
| HP            | 1632                        | [96d60382b7](https://bsd-hardware.info/?probe=96d60382b7) | Nov 09, 2022 |
| Dell          | 0G261D A00                  | [c3eb1a6caf](https://bsd-hardware.info/?probe=c3eb1a6caf) | Nov 08, 2022 |
| HP            | ProLiant ML310e Gen8        | [cb5bb2c3b5](https://bsd-hardware.info/?probe=cb5bb2c3b5) | Nov 07, 2022 |
| ASUSTek       | A88XM-E                     | [fde1fa45b8](https://bsd-hardware.info/?probe=fde1fa45b8) | Nov 07, 2022 |
| Unknown       | Unknown                     | [659ec0b365](https://bsd-hardware.info/?probe=659ec0b365) | Nov 07, 2022 |
| PC Engines    | APU2                        | [2a913e7a43](https://bsd-hardware.info/?probe=2a913e7a43) | Nov 06, 2022 |
| Protectli     | VP2410                      | [de5de1ca21](https://bsd-hardware.info/?probe=de5de1ca21) | Nov 06, 2022 |
| ASUSTek       | PRIME B560M-A               | [95d5580fd7](https://bsd-hardware.info/?probe=95d5580fd7) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d27fd3b1a7](https://bsd-hardware.info/?probe=d27fd3b1a7) | Nov 04, 2022 |
| MW            | GMLK-2_5G4L                 | [73230496b2](https://bsd-hardware.info/?probe=73230496b2) | Nov 04, 2022 |
| Unknown       | 1.0                         | [9fe6ac4e68](https://bsd-hardware.info/?probe=9fe6ac4e68) | Nov 03, 2022 |
| Hardkernel    | ODROID-H2                   | [f0e3f3177a](https://bsd-hardware.info/?probe=f0e3f3177a) | Nov 02, 2022 |
| Protectli     | FW6 Ver                     | [6f21c02bba](https://bsd-hardware.info/?probe=6f21c02bba) | Oct 31, 2022 |
| Unknown       | Unknown                     | [9737a80a1c](https://bsd-hardware.info/?probe=9737a80a1c) | Oct 31, 2022 |
| Protectli     | FW6 Ver                     | [a52d7dda08](https://bsd-hardware.info/?probe=a52d7dda08) | Oct 30, 2022 |
| Protectli     | FW6 Ver                     | [4aecc55dcc](https://bsd-hardware.info/?probe=4aecc55dcc) | Oct 30, 2022 |
| Thomas-Kre... | LES network 6L              | [0816f2da97](https://bsd-hardware.info/?probe=0816f2da97) | Oct 30, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [85be4177d6](https://bsd-hardware.info/?probe=85be4177d6) | Oct 29, 2022 |
| Unknown       | Unknown                     | [c483de83a9](https://bsd-hardware.info/?probe=c483de83a9) | Oct 28, 2022 |
| Unknown       | Unknown                     | [c03e63a0a8](https://bsd-hardware.info/?probe=c03e63a0a8) | Oct 28, 2022 |
| ASUSTek       | P5BV-M                      | [c5277ae3cd](https://bsd-hardware.info/?probe=c5277ae3cd) | Oct 27, 2022 |
| CncTion       | N5105-4L B0                 | [d2adcc8230](https://bsd-hardware.info/?probe=d2adcc8230) | Oct 26, 2022 |
| PC Engines    | apu1                        | [b8643f364d](https://bsd-hardware.info/?probe=b8643f364d) | Oct 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | [51ec4ce710](https://bsd-hardware.info/?probe=51ec4ce710) | Oct 24, 2022 |
| ASUSTek       | P5BV-M                      | [f7bfa3deed](https://bsd-hardware.info/?probe=f7bfa3deed) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | [6f0d5a7497](https://bsd-hardware.info/?probe=6f0d5a7497) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | [d7829c8f35](https://bsd-hardware.info/?probe=d7829c8f35) | Oct 22, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [a1b0ef3b39](https://bsd-hardware.info/?probe=a1b0ef3b39) | Oct 22, 2022 |
| Unknown       | Unknown                     | [410283dd4f](https://bsd-hardware.info/?probe=410283dd4f) | Oct 22, 2022 |
| Protectli     | FW6 Ver                     | [d04ef8c45b](https://bsd-hardware.info/?probe=d04ef8c45b) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7ecffc1ca3](https://bsd-hardware.info/?probe=7ecffc1ca3) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [eb6eda641d](https://bsd-hardware.info/?probe=eb6eda641d) | Oct 20, 2022 |
| Hardkernel    | ODROID-H3                   | [304db9bbbf](https://bsd-hardware.info/?probe=304db9bbbf) | Oct 20, 2022 |
| PC Engines    | APU2                        | [c2e7b76bdf](https://bsd-hardware.info/?probe=c2e7b76bdf) | Oct 20, 2022 |
| PC Engines    | APU2                        | [ade8432e80](https://bsd-hardware.info/?probe=ade8432e80) | Oct 20, 2022 |
| Protectli     | FW6                         | [a7dabc97b0](https://bsd-hardware.info/?probe=a7dabc97b0) | Oct 19, 2022 |
| Protectli     | FW4B                        | [0acd6e1143](https://bsd-hardware.info/?probe=0acd6e1143) | Oct 19, 2022 |
| Unknown       | MANIFOLD 2-C                | [a6c8096599](https://bsd-hardware.info/?probe=a6c8096599) | Oct 19, 2022 |
| Lenovo        | 30D0 NOK                    | [d1fab8bd54](https://bsd-hardware.info/?probe=d1fab8bd54) | Oct 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [c7971db0b8](https://bsd-hardware.info/?probe=c7971db0b8) | Oct 18, 2022 |
| NF541         | 1.0                         | [6f4f72398d](https://bsd-hardware.info/?probe=6f4f72398d) | Oct 17, 2022 |
| Unknown       | Unknown                     | [83ceb2fb33](https://bsd-hardware.info/?probe=83ceb2fb33) | Oct 15, 2022 |
| PC Engines    | apu4                        | [cefbafec73](https://bsd-hardware.info/?probe=cefbafec73) | Oct 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [a8bdbe4d1b](https://bsd-hardware.info/?probe=a8bdbe4d1b) | Oct 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [5a56504b92](https://bsd-hardware.info/?probe=5a56504b92) | Oct 15, 2022 |
| Dell          | 0WMJ54 A01                  | [5acdcd628d](https://bsd-hardware.info/?probe=5acdcd628d) | Oct 14, 2022 |
| PC Engines    | APU2                        | [0e09ac984a](https://bsd-hardware.info/?probe=0e09ac984a) | Oct 14, 2022 |
| PC Engines    | APU2                        | [a06a344954](https://bsd-hardware.info/?probe=a06a344954) | Oct 12, 2022 |
| ASUSTek       | P8Z68-V                     | [6674bbf7f3](https://bsd-hardware.info/?probe=6674bbf7f3) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | [869687f6f0](https://bsd-hardware.info/?probe=869687f6f0) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | [f4b5bf9026](https://bsd-hardware.info/?probe=f4b5bf9026) | Oct 11, 2022 |
| CncTion       | Jasper-4L B0                | [53c643dc95](https://bsd-hardware.info/?probe=53c643dc95) | Oct 10, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [5d929362ca](https://bsd-hardware.info/?probe=5d929362ca) | Oct 09, 2022 |
| Hardkernel    | ODROID-H2                   | [73c9bfe38b](https://bsd-hardware.info/?probe=73c9bfe38b) | Oct 09, 2022 |
| Unknown       | Unknown                     | [d6396a74dd](https://bsd-hardware.info/?probe=d6396a74dd) | Oct 08, 2022 |
| Unknown       | Unknown                     | [d25832111e](https://bsd-hardware.info/?probe=d25832111e) | Oct 07, 2022 |
| Unknown       | Unknown                     | [a34c1b8ccd](https://bsd-hardware.info/?probe=a34c1b8ccd) | Oct 07, 2022 |
| Unknown       | Unknown                     | [7658e5e20d](https://bsd-hardware.info/?probe=7658e5e20d) | Oct 06, 2022 |
| PC Engines    | APU2                        | [02416f3157](https://bsd-hardware.info/?probe=02416f3157) | Oct 06, 2022 |
| CncTion       | J4125-4L-I225               | [eb746dc4a1](https://bsd-hardware.info/?probe=eb746dc4a1) | Oct 05, 2022 |
| ASRock        | Z77 Extreme4                | [459c674b3b](https://bsd-hardware.info/?probe=459c674b3b) | Oct 04, 2022 |
| Protectli     | FW4B                        | [36c62d7ffe](https://bsd-hardware.info/?probe=36c62d7ffe) | Oct 03, 2022 |
| Unknown       | Unknown                     | [dac9b93a46](https://bsd-hardware.info/?probe=dac9b93a46) | Oct 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bb4a59dd43](https://bsd-hardware.info/?probe=bb4a59dd43) | Oct 03, 2022 |
| Protectli     | FW6 Ver                     | [23450789e4](https://bsd-hardware.info/?probe=23450789e4) | Oct 01, 2022 |
| AMI           | PICO PC                     | [ab45092607](https://bsd-hardware.info/?probe=ab45092607) | Oct 01, 2022 |
| Unknown       | Unknown                     | [c4e771c07c](https://bsd-hardware.info/?probe=c4e771c07c) | Oct 01, 2022 |
| BESSTAR Te... | IB9                         | [0cb7bacc88](https://bsd-hardware.info/?probe=0cb7bacc88) | Oct 01, 2022 |
| BESSTAR Te... | IB9                         | [eb0e449150](https://bsd-hardware.info/?probe=eb0e449150) | Sep 29, 2022 |
| AMI           | MNHO-048                    | [2ec6e55a75](https://bsd-hardware.info/?probe=2ec6e55a75) | Sep 28, 2022 |
| ASRock        | Z97 Professional            | [8936497eed](https://bsd-hardware.info/?probe=8936497eed) | Sep 27, 2022 |
| MSI           | A520M-A PRO                 | [7e75a1888b](https://bsd-hardware.info/?probe=7e75a1888b) | Sep 27, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [a605b4582c](https://bsd-hardware.info/?probe=a605b4582c) | Sep 27, 2022 |
| CncTion       | Jasper-4L B0                | [2998faa879](https://bsd-hardware.info/?probe=2998faa879) | Sep 25, 2022 |
| Pegatron      | H81-X1                      | [a27c76c490](https://bsd-hardware.info/?probe=a27c76c490) | Sep 25, 2022 |
| Supermicro    | X7DB8                       | [6ebc173873](https://bsd-hardware.info/?probe=6ebc173873) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | [8bbf714f6d](https://bsd-hardware.info/?probe=8bbf714f6d) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | [60d4585ece](https://bsd-hardware.info/?probe=60d4585ece) | Sep 25, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [6e2d053e1c](https://bsd-hardware.info/?probe=6e2d053e1c) | Sep 25, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8ed018c141](https://bsd-hardware.info/?probe=8ed018c141) | Sep 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [a0672c6af1](https://bsd-hardware.info/?probe=a0672c6af1) | Sep 23, 2022 |
| Protectli     | FW4B Ver                    | [036004bbfe](https://bsd-hardware.info/?probe=036004bbfe) | Sep 22, 2022 |
| PC Engines    | APU                         | [a65b17ba04](https://bsd-hardware.info/?probe=a65b17ba04) | Sep 21, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [3c74fc1690](https://bsd-hardware.info/?probe=3c74fc1690) | Sep 20, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | [c057b7ab09](https://bsd-hardware.info/?probe=c057b7ab09) | Sep 20, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [393da0c00c](https://bsd-hardware.info/?probe=393da0c00c) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-P                | [a2f56848a9](https://bsd-hardware.info/?probe=a2f56848a9) | Sep 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [cad2b5fd02](https://bsd-hardware.info/?probe=cad2b5fd02) | Sep 18, 2022 |
| BESSTAR Te... | TH50                        | [d027a503a5](https://bsd-hardware.info/?probe=d027a503a5) | Sep 18, 2022 |
| Unknown       | Unknown                     | [af8f180c2c](https://bsd-hardware.info/?probe=af8f180c2c) | Sep 17, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a9da12dec0](https://bsd-hardware.info/?probe=a9da12dec0) | Sep 17, 2022 |
| ASUSTek       | PRIME X570-P                | [9fc1f66fcc](https://bsd-hardware.info/?probe=9fc1f66fcc) | Sep 16, 2022 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | [eb09d789de](https://bsd-hardware.info/?probe=eb09d789de) | Sep 16, 2022 |
| Unknown       | Unknown                     | [3b66741f97](https://bsd-hardware.info/?probe=3b66741f97) | Sep 16, 2022 |
| Unknown       | Unknown                     | [83e48aa232](https://bsd-hardware.info/?probe=83e48aa232) | Sep 16, 2022 |
| Intel         | ChiefRiver                  | [5361453e6a](https://bsd-hardware.info/?probe=5361453e6a) | Sep 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [e8848edf41](https://bsd-hardware.info/?probe=e8848edf41) | Sep 13, 2022 |
| HP            | 18E7                        | [f09635a7ee](https://bsd-hardware.info/?probe=f09635a7ee) | Sep 12, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [2b4e2212dc](https://bsd-hardware.info/?probe=2b4e2212dc) | Sep 12, 2022 |
| BESSTAR Te... | TH50                        | [71e53af7f9](https://bsd-hardware.info/?probe=71e53af7f9) | Sep 12, 2022 |
| Unknown       | Unknown                     | [37588a8565](https://bsd-hardware.info/?probe=37588a8565) | Sep 11, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [836927cf63](https://bsd-hardware.info/?probe=836927cf63) | Sep 10, 2022 |
| ASUSTek       | PRIME X570-P                | [8eb8bf52d4](https://bsd-hardware.info/?probe=8eb8bf52d4) | Sep 10, 2022 |
| ASRock        | H81M-DGS                    | [3c2b784001](https://bsd-hardware.info/?probe=3c2b784001) | Sep 09, 2022 |
| ASRock        | H81M-DGS                    | [581219cbc5](https://bsd-hardware.info/?probe=581219cbc5) | Sep 09, 2022 |
| ASRockRack    | X470D4U2/1N1                | [f91afdb2f3](https://bsd-hardware.info/?probe=f91afdb2f3) | Sep 09, 2022 |
| ASRockRack    | X470D4U2/1N1                | [b0965df7e1](https://bsd-hardware.info/?probe=b0965df7e1) | Sep 08, 2022 |
| Techvision    | TVI7309X B0                 | [1d81b77310](https://bsd-hardware.info/?probe=1d81b77310) | Sep 07, 2022 |
| Intel         | SYS-2USM03-6M01E            | [d4f98f18b9](https://bsd-hardware.info/?probe=d4f98f18b9) | Sep 07, 2022 |
| Techvision    | TVI7309X B0                 | [b803a767af](https://bsd-hardware.info/?probe=b803a767af) | Sep 06, 2022 |
| CncTion       | N5105-4L                    | [2a34dc3fe0](https://bsd-hardware.info/?probe=2a34dc3fe0) | Sep 05, 2022 |
| BESSTAR Te... | TH50                        | [734a8e61c4](https://bsd-hardware.info/?probe=734a8e61c4) | Sep 05, 2022 |
| Unknown       | Unknown                     | [c1967c7cf8](https://bsd-hardware.info/?probe=c1967c7cf8) | Sep 04, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [72cdc4123c](https://bsd-hardware.info/?probe=72cdc4123c) | Sep 03, 2022 |
| Lenovo        | ThinkCentre M70e 0833A29    | [b7c5b9a51d](https://bsd-hardware.info/?probe=b7c5b9a51d) | Sep 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [1e05b51bf1](https://bsd-hardware.info/?probe=1e05b51bf1) | Sep 02, 2022 |
| Intel         | QHSW02                      | [b0ad128162](https://bsd-hardware.info/?probe=b0ad128162) | Sep 02, 2022 |
| Dell          | 0G261D A00                  | [c77b23d1a7](https://bsd-hardware.info/?probe=c77b23d1a7) | Aug 31, 2022 |
| Intel         | DENLOW_WS                   | [067a217959](https://bsd-hardware.info/?probe=067a217959) | Aug 30, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [df3df2855b](https://bsd-hardware.info/?probe=df3df2855b) | Aug 28, 2022 |
| ASUSTek       | PRIME X570-P                | [0f1eabf01e](https://bsd-hardware.info/?probe=0f1eabf01e) | Aug 27, 2022 |
| Intel         | QHSW02                      | [184a8697e9](https://bsd-hardware.info/?probe=184a8697e9) | Aug 27, 2022 |
| Intel         | QHSW02                      | [1765bd0426](https://bsd-hardware.info/?probe=1765bd0426) | Aug 27, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [3465c46b7d](https://bsd-hardware.info/?probe=3465c46b7d) | Aug 26, 2022 |
| PC Engines    | APU2                        | [97da53ff14](https://bsd-hardware.info/?probe=97da53ff14) | Aug 25, 2022 |
| ASRock        | AD2550-ITX                  | [43d0101ac4](https://bsd-hardware.info/?probe=43d0101ac4) | Aug 24, 2022 |
| HP            | 82B4                        | [5e07fc9831](https://bsd-hardware.info/?probe=5e07fc9831) | Aug 22, 2022 |
| Unknown       | Unknown                     | [7d059d1d0a](https://bsd-hardware.info/?probe=7d059d1d0a) | Aug 22, 2022 |
| Gigabyte      | H310M S2H                   | [b32f197fe9](https://bsd-hardware.info/?probe=b32f197fe9) | Aug 21, 2022 |
| PC Engines    | APU2                        | [92bff81bb5](https://bsd-hardware.info/?probe=92bff81bb5) | Aug 20, 2022 |
| PC Engines    | APU2                        | [ccdff6fbea](https://bsd-hardware.info/?probe=ccdff6fbea) | Aug 20, 2022 |
| Protectli     | FW4B                        | [8eb0c6ffbe](https://bsd-hardware.info/?probe=8eb0c6ffbe) | Aug 19, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [fb02323793](https://bsd-hardware.info/?probe=fb02323793) | Aug 19, 2022 |
| Inventec      | Z CLASS A02                 | [290a94a907](https://bsd-hardware.info/?probe=290a94a907) | Aug 18, 2022 |
| Dell          | 0VG93V A00                  | [8de9fa2319](https://bsd-hardware.info/?probe=8de9fa2319) | Aug 18, 2022 |
| Dell          | 0FDY5C A00                  | [2c0bb11a7b](https://bsd-hardware.info/?probe=2c0bb11a7b) | Aug 17, 2022 |
| Dell          | 042P49 A00                  | [7130975fe3](https://bsd-hardware.info/?probe=7130975fe3) | Aug 17, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [e67200aee1](https://bsd-hardware.info/?probe=e67200aee1) | Aug 15, 2022 |
| Unknown       | Unknown                     | [ef2a61855a](https://bsd-hardware.info/?probe=ef2a61855a) | Aug 15, 2022 |
| Unknown       | Unknown                     | [e23ed854ed](https://bsd-hardware.info/?probe=e23ed854ed) | Aug 14, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | [9267873961](https://bsd-hardware.info/?probe=9267873961) | Aug 13, 2022 |
| Supermicro    | X9SCI/X9SCA                 | [6e7e782b00](https://bsd-hardware.info/?probe=6e7e782b00) | Aug 13, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | [6884e940a1](https://bsd-hardware.info/?probe=6884e940a1) | Aug 13, 2022 |
| Dell          | 0T7D40 A01                  | [d06e05c67a](https://bsd-hardware.info/?probe=d06e05c67a) | Aug 12, 2022 |
| HP            | 82B4                        | [d3fd85a7b6](https://bsd-hardware.info/?probe=d3fd85a7b6) | Aug 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [fe8deedda3](https://bsd-hardware.info/?probe=fe8deedda3) | Aug 11, 2022 |
| Intel         | Q3XXG4-P V1.0               | [d3f51a01b1](https://bsd-hardware.info/?probe=d3f51a01b1) | Aug 11, 2022 |
| Unknown       | Unknown                     | [80e867e04c](https://bsd-hardware.info/?probe=80e867e04c) | Aug 10, 2022 |
| BESSTAR Te... | TH50                        | [afca16a0bd](https://bsd-hardware.info/?probe=afca16a0bd) | Aug 09, 2022 |
| NF541         | 1.0                         | [dcde0e7a44](https://bsd-hardware.info/?probe=dcde0e7a44) | Aug 09, 2022 |
| Dell          | 042P49 A00                  | [a38375fa97](https://bsd-hardware.info/?probe=a38375fa97) | Aug 08, 2022 |
| Dell          | 042P49 A00                  | [81a5e313cd](https://bsd-hardware.info/?probe=81a5e313cd) | Aug 08, 2022 |
| Unknown       | Unknown                     | [64768cfe88](https://bsd-hardware.info/?probe=64768cfe88) | Aug 07, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | [75ffbbae85](https://bsd-hardware.info/?probe=75ffbbae85) | Aug 07, 2022 |
| HP            | 18E4                        | [7408fe969c](https://bsd-hardware.info/?probe=7408fe969c) | Aug 07, 2022 |
| HP            | 213D A01                    | [383712cf94](https://bsd-hardware.info/?probe=383712cf94) | Aug 06, 2022 |
| HP            | 213D A01                    | [e28886f86e](https://bsd-hardware.info/?probe=e28886f86e) | Aug 06, 2022 |
| Gigabyte      | H97M-HD3                    | [4a7705414f](https://bsd-hardware.info/?probe=4a7705414f) | Aug 06, 2022 |
| BESSTAR Te... | TH50                        | [9e69d3a39f](https://bsd-hardware.info/?probe=9e69d3a39f) | Aug 06, 2022 |
| BESSTAR Te... | TH50                        | [e68fb8c88e](https://bsd-hardware.info/?probe=e68fb8c88e) | Aug 06, 2022 |
| Unknown       | Unknown                     | [ae62a89080](https://bsd-hardware.info/?probe=ae62a89080) | Aug 05, 2022 |
| ASUSTek       | PRIME Z270-A                | [69214b0c79](https://bsd-hardware.info/?probe=69214b0c79) | Aug 04, 2022 |
| PC Engines    | apu4                        | [2ae838d489](https://bsd-hardware.info/?probe=2ae838d489) | Aug 02, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f2590dea4b](https://bsd-hardware.info/?probe=f2590dea4b) | Aug 01, 2022 |
| Gigabyte      | H610I DDR4                  | [d50ffab1cc](https://bsd-hardware.info/?probe=d50ffab1cc) | Aug 01, 2022 |
| ASUSTek       | P5W64 WS Pro                | [f05a901a30](https://bsd-hardware.info/?probe=f05a901a30) | Aug 01, 2022 |
| Unknown       | Unknown                     | [f891511390](https://bsd-hardware.info/?probe=f891511390) | Jul 30, 2022 |
| AMD           | Inagua CRB                  | [0d0b0c3f9e](https://bsd-hardware.info/?probe=0d0b0c3f9e) | Jul 29, 2022 |
| Dell          | 0PC5F7 A03                  | [7cc4f8754f](https://bsd-hardware.info/?probe=7cc4f8754f) | Jul 27, 2022 |
| CNCTION-IA... | Unknown                     | [91165a8899](https://bsd-hardware.info/?probe=91165a8899) | Jul 27, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [9df3c644b9](https://bsd-hardware.info/?probe=9df3c644b9) | Jul 27, 2022 |
| MW            | GMLK-2_5G4L                 | [fd67eb14ae](https://bsd-hardware.info/?probe=fd67eb14ae) | Jul 26, 2022 |
| ZOTAC         | Unknown                     | [2f701b55fc](https://bsd-hardware.info/?probe=2f701b55fc) | Jul 25, 2022 |
| Unknown       | Unknown                     | [8830b5ba19](https://bsd-hardware.info/?probe=8830b5ba19) | Jul 24, 2022 |
| ASRock        | J3455B-ITX                  | [37ce098399](https://bsd-hardware.info/?probe=37ce098399) | Jul 23, 2022 |
| Intel         | DH77KC AAG39641-400         | [df31840a7e](https://bsd-hardware.info/?probe=df31840a7e) | Jul 22, 2022 |
| Intel         | QHSW02                      | [8f910e599b](https://bsd-hardware.info/?probe=8f910e599b) | Jul 21, 2022 |
| ASRock        | A520M-ITX/ac                | [48854ed05e](https://bsd-hardware.info/?probe=48854ed05e) | Jul 21, 2022 |
| Biostar       | J4105NHU                    | [1b6748d4f7](https://bsd-hardware.info/?probe=1b6748d4f7) | Jul 19, 2022 |
| ASRock        | H570M-ITX/ac                | [4b0bdf58dd](https://bsd-hardware.info/?probe=4b0bdf58dd) | Jul 18, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [e3461d0ff8](https://bsd-hardware.info/?probe=e3461d0ff8) | Jul 17, 2022 |
| Supermicro    | A2SAP-HA                    | [27c6228555](https://bsd-hardware.info/?probe=27c6228555) | Jul 17, 2022 |
| YANYU         | H87SL VER:1.3               | [fda62409ee](https://bsd-hardware.info/?probe=fda62409ee) | Jul 17, 2022 |
| MSI           | B85M-E45                    | [80f2d74d1a](https://bsd-hardware.info/?probe=80f2d74d1a) | Jul 16, 2022 |
| PC Engines    | APU3                        | [2b20f47024](https://bsd-hardware.info/?probe=2b20f47024) | Jul 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [2a52f27ffe](https://bsd-hardware.info/?probe=2a52f27ffe) | Jul 13, 2022 |
| ASRock        | A520M-ITX/ac                | [be86d81d29](https://bsd-hardware.info/?probe=be86d81d29) | Jul 13, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [75132f9078](https://bsd-hardware.info/?probe=75132f9078) | Jul 13, 2022 |
| ASRock        | Z97 Professional            | [c1c177fbb0](https://bsd-hardware.info/?probe=c1c177fbb0) | Jul 12, 2022 |
| HP            | 1790                        | [bc5988d764](https://bsd-hardware.info/?probe=bc5988d764) | Jul 11, 2022 |
| NF541         | 1.0                         | [00cab93f40](https://bsd-hardware.info/?probe=00cab93f40) | Jul 10, 2022 |
| Unknown       | Unknown                     | [947d413e10](https://bsd-hardware.info/?probe=947d413e10) | Jul 09, 2022 |
| Unknown       | Unknown                     | [e42f50fe0f](https://bsd-hardware.info/?probe=e42f50fe0f) | Jul 09, 2022 |
| Unknown       | Unknown                     | [b0380fb22c](https://bsd-hardware.info/?probe=b0380fb22c) | Jul 09, 2022 |
| Intel         | QHSW02                      | [e7d923f138](https://bsd-hardware.info/?probe=e7d923f138) | Jul 07, 2022 |
| Intel         | CRESCENTBAY                 | [71efa2b0b9](https://bsd-hardware.info/?probe=71efa2b0b9) | Jul 06, 2022 |
| ASUSTek       | H110I-PLUS                  | [342ef61cdc](https://bsd-hardware.info/?probe=342ef61cdc) | Jul 05, 2022 |
| NF541S        | 1.0                         | [937fe3af39](https://bsd-hardware.info/?probe=937fe3af39) | Jul 04, 2022 |
| ASUSTek       | PRIME X570-P                | [c8a69b3805](https://bsd-hardware.info/?probe=c8a69b3805) | Jul 04, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [aeee3a91e6](https://bsd-hardware.info/?probe=aeee3a91e6) | Jul 03, 2022 |
| ASRock        | H310CM-DVS                  | [907e22dbb6](https://bsd-hardware.info/?probe=907e22dbb6) | Jul 03, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [40c8fdfafa](https://bsd-hardware.info/?probe=40c8fdfafa) | Jul 02, 2022 |
| HP            | 213D A01                    | [21af8c270f](https://bsd-hardware.info/?probe=21af8c270f) | Jul 01, 2022 |
| Unknown       | J3160-4L                    | [adaa197bf6](https://bsd-hardware.info/?probe=adaa197bf6) | Jul 01, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [77acc9f5cf](https://bsd-hardware.info/?probe=77acc9f5cf) | Jul 01, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ffa0086c70](https://bsd-hardware.info/?probe=ffa0086c70) | Jul 01, 2022 |
| Unknown       | Unknown                     | [35f24d802a](https://bsd-hardware.info/?probe=35f24d802a) | Jun 30, 2022 |
| ASUSTek       | H110I-PLUS                  | [e8f496791d](https://bsd-hardware.info/?probe=e8f496791d) | Jun 30, 2022 |
| Unknown       | Unknown                     | [8e6519f26f](https://bsd-hardware.info/?probe=8e6519f26f) | Jun 30, 2022 |
| Unknown       | Unknown                     | [85c0c08d91](https://bsd-hardware.info/?probe=85c0c08d91) | Jun 29, 2022 |
| ASRock        | N3700M                      | [3896fd5bc2](https://bsd-hardware.info/?probe=3896fd5bc2) | Jun 29, 2022 |
| Intel         | QHSW02                      | [28928d9ad4](https://bsd-hardware.info/?probe=28928d9ad4) | Jun 28, 2022 |
| Intel         | Q3XXG4-P V1.0               | [7fcdb93a4b](https://bsd-hardware.info/?probe=7fcdb93a4b) | Jun 27, 2022 |
| Unknown       | Unknown                     | [8ab4302d97](https://bsd-hardware.info/?probe=8ab4302d97) | Jun 26, 2022 |
| PC Engines    | APU2                        | [3e4fbe09f1](https://bsd-hardware.info/?probe=3e4fbe09f1) | Jun 26, 2022 |
| Biostar       | J4105NHU                    | [9419973ba0](https://bsd-hardware.info/?probe=9419973ba0) | Jun 25, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [6c72a0dca7](https://bsd-hardware.info/?probe=6c72a0dca7) | Jun 24, 2022 |
| Gigabyte      | H610I DDR4                  | [bfcc8f1f66](https://bsd-hardware.info/?probe=bfcc8f1f66) | Jun 24, 2022 |
| ASUSTek       | PRIME X570-P                | [18f9e5bf9c](https://bsd-hardware.info/?probe=18f9e5bf9c) | Jun 23, 2022 |
| PC Engines    | APU2                        | [de9163945f](https://bsd-hardware.info/?probe=de9163945f) | Jun 23, 2022 |
| PC Engines    | apu4                        | [d7e6f088d0](https://bsd-hardware.info/?probe=d7e6f088d0) | Jun 22, 2022 |
| Supermicro    | A2SDi-LN4F                  | [72860a723c](https://bsd-hardware.info/?probe=72860a723c) | Jun 22, 2022 |
| Unknown       | Unknown                     | [62a2455a8b](https://bsd-hardware.info/?probe=62a2455a8b) | Jun 22, 2022 |
| Unknown       | Unknown                     | [fb1ffe9c0d](https://bsd-hardware.info/?probe=fb1ffe9c0d) | Jun 22, 2022 |
| Unknown       | Unknown                     | [24b47422c7](https://bsd-hardware.info/?probe=24b47422c7) | Jun 22, 2022 |
| MSI           | B85M-E45                    | [d9cc6cee6b](https://bsd-hardware.info/?probe=d9cc6cee6b) | Jun 21, 2022 |
| ASUSTek       | H110T                       | [a4a51d110b](https://bsd-hardware.info/?probe=a4a51d110b) | Jun 20, 2022 |
| Unknown       | Unknown                     | [c9303dab91](https://bsd-hardware.info/?probe=c9303dab91) | Jun 19, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [b576f09eec](https://bsd-hardware.info/?probe=b576f09eec) | Jun 17, 2022 |
| Biostar       | A10N-8800E                  | [60df3db3ab](https://bsd-hardware.info/?probe=60df3db3ab) | Jun 16, 2022 |
| Unknown       | Unknown                     | [b7540c1e4a](https://bsd-hardware.info/?probe=b7540c1e4a) | Jun 14, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [7626993227](https://bsd-hardware.info/?probe=7626993227) | Jun 13, 2022 |
| Unknown       | Unknown                     | [1cc180ad27](https://bsd-hardware.info/?probe=1cc180ad27) | Jun 13, 2022 |
| Unknown       | Unknown                     | [36f6b6f077](https://bsd-hardware.info/?probe=36f6b6f077) | Jun 11, 2022 |
| Lanner        | FW-7543 B-GA                | [bf1e373f8a](https://bsd-hardware.info/?probe=bf1e373f8a) | Jun 10, 2022 |
| HP            | 806A                        | [c3051ac63e](https://bsd-hardware.info/?probe=c3051ac63e) | Jun 10, 2022 |
| Unknown       | Unknown                     | [23d5c4d92d](https://bsd-hardware.info/?probe=23d5c4d92d) | Jun 10, 2022 |
| Intel         | MAHOBAY                     | [cf146946d3](https://bsd-hardware.info/?probe=cf146946d3) | Jun 09, 2022 |
| ASUSTek       | TUF B360M-E GAMING          | [26375bae48](https://bsd-hardware.info/?probe=26375bae48) | Jun 08, 2022 |
| ASRock        | J4125B-ITX                  | [fd96faf8aa](https://bsd-hardware.info/?probe=fd96faf8aa) | Jun 08, 2022 |
| HP            | 18E4                        | [d63cd86fb5](https://bsd-hardware.info/?probe=d63cd86fb5) | Jun 08, 2022 |
| Supermicro    | X7SPA-HF                    | [37a918bd43](https://bsd-hardware.info/?probe=37a918bd43) | Jun 08, 2022 |
| MSI           | B85M-E45                    | [10e7bbf38a](https://bsd-hardware.info/?probe=10e7bbf38a) | Jun 08, 2022 |
| MW            | GMLK-2_5G4L                 | [6c9ccc6963](https://bsd-hardware.info/?probe=6c9ccc6963) | Jun 06, 2022 |
| PC Engines    | APU2                        | [ad2b0dd980](https://bsd-hardware.info/?probe=ad2b0dd980) | Jun 06, 2022 |
| Unknown       | Unknown                     | [d8cd85e3d7](https://bsd-hardware.info/?probe=d8cd85e3d7) | Jun 05, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [b98e41f6a4](https://bsd-hardware.info/?probe=b98e41f6a4) | Jun 05, 2022 |
| Thomas-Kre... | LES network 6L              | [a3023b3f39](https://bsd-hardware.info/?probe=a3023b3f39) | Jun 04, 2022 |
| HP            | 806A                        | [cc091ee2e2](https://bsd-hardware.info/?probe=cc091ee2e2) | Jun 03, 2022 |
| Unknown       | Unknown                     | [4294ad5419](https://bsd-hardware.info/?probe=4294ad5419) | Jun 01, 2022 |
| Unknown       | Unknown                     | [2da72109a6](https://bsd-hardware.info/?probe=2da72109a6) | Jun 01, 2022 |
| Unknown       | Unknown                     | [9ad9772ac7](https://bsd-hardware.info/?probe=9ad9772ac7) | May 31, 2022 |
| ASUSTek       | PRIME X570-P                | [fa3ea36bad](https://bsd-hardware.info/?probe=fa3ea36bad) | May 31, 2022 |
| Deciso        | Netboard A10 V2.1           | [6beacad396](https://bsd-hardware.info/?probe=6beacad396) | May 31, 2022 |
| Unknown       | Unknown                     | [ef87e699fb](https://bsd-hardware.info/?probe=ef87e699fb) | May 30, 2022 |
| Intel         | Q3XXG4-P V1.0               | [95234abead](https://bsd-hardware.info/?probe=95234abead) | May 28, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [cdddbb5d23](https://bsd-hardware.info/?probe=cdddbb5d23) | May 27, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [7a47fcd920](https://bsd-hardware.info/?probe=7a47fcd920) | May 27, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a5446262b3](https://bsd-hardware.info/?probe=a5446262b3) | May 27, 2022 |
| ASRock        | B660M-HDV                   | [fadb382a5a](https://bsd-hardware.info/?probe=fadb382a5a) | May 26, 2022 |
| ASRockRack    | E3C242D4U2-2T               | [d35f1fb7e0](https://bsd-hardware.info/?probe=d35f1fb7e0) | May 25, 2022 |
| ASRockRack    | E3C242D4U2-2T               | [66f9070856](https://bsd-hardware.info/?probe=66f9070856) | May 23, 2022 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | [e9e497fc7b](https://bsd-hardware.info/?probe=e9e497fc7b) | May 22, 2022 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | [b05a8f6ed8](https://bsd-hardware.info/?probe=b05a8f6ed8) | May 22, 2022 |
| Biostar       | J4105NHU                    | [88b74aaf3b](https://bsd-hardware.info/?probe=88b74aaf3b) | May 22, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [e9524e612d](https://bsd-hardware.info/?probe=e9524e612d) | May 22, 2022 |
| HP            | 339A                        | [e6a9b68262](https://bsd-hardware.info/?probe=e6a9b68262) | May 20, 2022 |
| Intel         | Q3XXG4-P V1.0               | [24d2bf3524](https://bsd-hardware.info/?probe=24d2bf3524) | May 19, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [ea6146e013](https://bsd-hardware.info/?probe=ea6146e013) | May 19, 2022 |
| Supermicro    | A2SDi-LN4F                  | [acc4101dc1](https://bsd-hardware.info/?probe=acc4101dc1) | May 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [edcd612c83](https://bsd-hardware.info/?probe=edcd612c83) | May 18, 2022 |
| Biostar       | H410MH S2                   | [1b218204b8](https://bsd-hardware.info/?probe=1b218204b8) | May 18, 2022 |
| MSI           | B85M-E45                    | [83ab25156c](https://bsd-hardware.info/?probe=83ab25156c) | May 18, 2022 |
| Unknown       | Unknown                     | [e13c8baa2d](https://bsd-hardware.info/?probe=e13c8baa2d) | May 17, 2022 |
| Unknown       | Unknown                     | [b8579c7f84](https://bsd-hardware.info/?probe=b8579c7f84) | May 17, 2022 |
| Unknown       | Unknown                     | [98b4dea15a](https://bsd-hardware.info/?probe=98b4dea15a) | May 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | [8c2f853975](https://bsd-hardware.info/?probe=8c2f853975) | May 17, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [b87692aeb4](https://bsd-hardware.info/?probe=b87692aeb4) | May 15, 2022 |
| MSI           | MS-7C82                     | [2ad883afec](https://bsd-hardware.info/?probe=2ad883afec) | May 15, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [6974f0958e](https://bsd-hardware.info/?probe=6974f0958e) | May 15, 2022 |
| Unknown       | Unknown                     | [4fad520626](https://bsd-hardware.info/?probe=4fad520626) | May 14, 2022 |
| ASRock        | E350M1                      | [1850fa38e0](https://bsd-hardware.info/?probe=1850fa38e0) | May 14, 2022 |
| ASRock        | E350M1                      | [4520b5034e](https://bsd-hardware.info/?probe=4520b5034e) | May 13, 2022 |
| HP            | 213D A01                    | [89955ba84f](https://bsd-hardware.info/?probe=89955ba84f) | May 11, 2022 |
| HP            | 82A1                        | [34cb091e26](https://bsd-hardware.info/?probe=34cb091e26) | May 08, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | [dc534266df](https://bsd-hardware.info/?probe=dc534266df) | May 06, 2022 |
| BESSTAR Te... | IB9                         | [4a4e45585d](https://bsd-hardware.info/?probe=4a4e45585d) | May 06, 2022 |
| friendlyel... | nanopi-r4s                  | [3db2ec8973](https://bsd-hardware.info/?probe=3db2ec8973) | May 04, 2022 |
| Unknown       | Unknown                     | [b96fd74ab0](https://bsd-hardware.info/?probe=b96fd74ab0) | May 03, 2022 |
| ASRock        | J4125B-ITX                  | [14d02a8209](https://bsd-hardware.info/?probe=14d02a8209) | May 03, 2022 |
| Intel         | QHSW02                      | [e4c8d6c787](https://bsd-hardware.info/?probe=e4c8d6c787) | May 01, 2022 |
| MSI           | MEG X570 UNIFY              | [5e8168a980](https://bsd-hardware.info/?probe=5e8168a980) | Apr 30, 2022 |
| OEM           | 1.0                         | [36e78ab638](https://bsd-hardware.info/?probe=36e78ab638) | Apr 29, 2022 |
| Unknown       | YL-J1900-V1                 | [54fe9e7529](https://bsd-hardware.info/?probe=54fe9e7529) | Apr 29, 2022 |
| MSI           | A520M-A PRO                 | [336add4fcb](https://bsd-hardware.info/?probe=336add4fcb) | Apr 28, 2022 |
| MSI           | A520M-A PRO                 | [34f2ba40e7](https://bsd-hardware.info/?probe=34f2ba40e7) | Apr 27, 2022 |
| PC Engines    | APU2                        | [920eae6f2e](https://bsd-hardware.info/?probe=920eae6f2e) | Apr 27, 2022 |
| MSI           | 970A GAMING PRO CARBON      | [c36f9d6c1d](https://bsd-hardware.info/?probe=c36f9d6c1d) | Apr 26, 2022 |
| Unknown       | MANIFOLD 2-C                | [637c28d728](https://bsd-hardware.info/?probe=637c28d728) | Apr 25, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | [86c4af7ca4](https://bsd-hardware.info/?probe=86c4af7ca4) | Apr 25, 2022 |
| MSI           | MEG X570 UNIFY              | [6afa33e8f8](https://bsd-hardware.info/?probe=6afa33e8f8) | Apr 24, 2022 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [1ce660f88e](https://bsd-hardware.info/?probe=1ce660f88e) | Apr 24, 2022 |
| PC Engines    | apu4                        | [ae39e5adc0](https://bsd-hardware.info/?probe=ae39e5adc0) | Apr 22, 2022 |
| ASRock        | X79 Extreme6/GB             | [cd85d68dcd](https://bsd-hardware.info/?probe=cd85d68dcd) | Apr 21, 2022 |
| CheckPoint    | T-140-00                    | [8e2c861ecf](https://bsd-hardware.info/?probe=8e2c861ecf) | Apr 19, 2022 |
| CheckPoint    | T-140-00                    | [8f0c5b5334](https://bsd-hardware.info/?probe=8f0c5b5334) | Apr 19, 2022 |
| PC Engines    | APU2                        | [47ddf6b2bd](https://bsd-hardware.info/?probe=47ddf6b2bd) | Apr 19, 2022 |
| Gigabyte      | B85M-D3H                    | [8d7236247d](https://bsd-hardware.info/?probe=8d7236247d) | Apr 18, 2022 |
| ASRock        | B85M Pro3                   | [9ff2cbdcf1](https://bsd-hardware.info/?probe=9ff2cbdcf1) | Apr 18, 2022 |
| Unknown       | Unknown                     | [0914d63c72](https://bsd-hardware.info/?probe=0914d63c72) | Apr 16, 2022 |
| Biostar       | H410MH S2                   | [d045a4acad](https://bsd-hardware.info/?probe=d045a4acad) | Apr 14, 2022 |
| Gigabyte      | B85M-D3H                    | [3365444265](https://bsd-hardware.info/?probe=3365444265) | Apr 14, 2022 |
| Unknown       | Unknown                     | [4ec1e3548c](https://bsd-hardware.info/?probe=4ec1e3548c) | Apr 14, 2022 |
| Intel         | Q3XXG4-P V1.0               | [efb76ec7fe](https://bsd-hardware.info/?probe=efb76ec7fe) | Apr 13, 2022 |
| Unknown       | Unknown                     | [ad14582532](https://bsd-hardware.info/?probe=ad14582532) | Apr 13, 2022 |
| Intel         | D53427RKE G87971-403        | [1a1de076c7](https://bsd-hardware.info/?probe=1a1de076c7) | Apr 13, 2022 |
| Intel         | SKYBAY                      | [5f2a882529](https://bsd-hardware.info/?probe=5f2a882529) | Apr 11, 2022 |
| Gigabyte      | MZBSWAP-K4                  | [752f962123](https://bsd-hardware.info/?probe=752f962123) | Apr 10, 2022 |
| PC Engines    | APU2                        | [ae2d120c7c](https://bsd-hardware.info/?probe=ae2d120c7c) | Apr 10, 2022 |
| Shuttle       | DS10U                       | [7d5919eb2b](https://bsd-hardware.info/?probe=7d5919eb2b) | Apr 10, 2022 |
| Unknown       | Unknown                     | [6835aa43e3](https://bsd-hardware.info/?probe=6835aa43e3) | Apr 09, 2022 |
| Intel         | MAHOBAY                     | [8b21109cd4](https://bsd-hardware.info/?probe=8b21109cd4) | Apr 08, 2022 |
| MSI           | MS-7369                     | [25f2161cac](https://bsd-hardware.info/?probe=25f2161cac) | Apr 08, 2022 |
| ASRock        | H570M-ITX/ac                | [44327ad768](https://bsd-hardware.info/?probe=44327ad768) | Apr 07, 2022 |
| HP            | 213D A01                    | [3f6e05c14d](https://bsd-hardware.info/?probe=3f6e05c14d) | Apr 07, 2022 |
| ASRock        | B660M-HDV                   | [9ffa0cc352](https://bsd-hardware.info/?probe=9ffa0cc352) | Apr 06, 2022 |
| PC Engines    | APU2                        | [69304a74cc](https://bsd-hardware.info/?probe=69304a74cc) | Apr 06, 2022 |
| Unknown       | Unknown                     | [4cf896e25a](https://bsd-hardware.info/?probe=4cf896e25a) | Apr 06, 2022 |
| ASUSTek       | PRIME B360M-A               | [90663f7aa0](https://bsd-hardware.info/?probe=90663f7aa0) | Apr 05, 2022 |
| HP            | 213D A01                    | [238d8bbcde](https://bsd-hardware.info/?probe=238d8bbcde) | Apr 04, 2022 |
| PC Engines    | APU2                        | [69cb42c07b](https://bsd-hardware.info/?probe=69cb42c07b) | Apr 02, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [1bdaf4bb77](https://bsd-hardware.info/?probe=1bdaf4bb77) | Apr 01, 2022 |
| HP            | 3396                        | [7a60daeaef](https://bsd-hardware.info/?probe=7a60daeaef) | Apr 01, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [9b6f9eac6f](https://bsd-hardware.info/?probe=9b6f9eac6f) | Apr 01, 2022 |
| PC Engines    | APU                         | [c71152505f](https://bsd-hardware.info/?probe=c71152505f) | Apr 01, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [3df6a01030](https://bsd-hardware.info/?probe=3df6a01030) | Mar 31, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [b5ea7eaeb0](https://bsd-hardware.info/?probe=b5ea7eaeb0) | Mar 31, 2022 |
| ASUSTek       | PRO B460M-C                 | [0542f7a16d](https://bsd-hardware.info/?probe=0542f7a16d) | Mar 29, 2022 |
| Unknown       | Unknown                     | [4383e28183](https://bsd-hardware.info/?probe=4383e28183) | Mar 29, 2022 |
| Intel         | DENLOW_REFRESH_WS           | [36896a719d](https://bsd-hardware.info/?probe=36896a719d) | Mar 29, 2022 |
| ASRock        | X79 Extreme6/GB             | [0646607953](https://bsd-hardware.info/?probe=0646607953) | Mar 28, 2022 |
| PC Engines    | apu4                        | [a35c56ca36](https://bsd-hardware.info/?probe=a35c56ca36) | Mar 28, 2022 |
| Protectli     | FW6 Ver                     | [f09a26de6f](https://bsd-hardware.info/?probe=f09a26de6f) | Mar 27, 2022 |
| Gigabyte      | MZBSWBP-00                  | [9e5d1c9daa](https://bsd-hardware.info/?probe=9e5d1c9daa) | Mar 26, 2022 |
| Unknown       | Unknown                     | [da94141898](https://bsd-hardware.info/?probe=da94141898) | Mar 26, 2022 |
| PC Engines    | apu4                        | [d95599aa97](https://bsd-hardware.info/?probe=d95599aa97) | Mar 25, 2022 |
| ASUSTek       | P10S-I Series               | [190fe4d13f](https://bsd-hardware.info/?probe=190fe4d13f) | Mar 24, 2022 |
| MSI           | MS-A6221 100                | [ba62f48990](https://bsd-hardware.info/?probe=ba62f48990) | Mar 23, 2022 |
| PC Engines    | APU3                        | [0a68bdf721](https://bsd-hardware.info/?probe=0a68bdf721) | Mar 23, 2022 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | [e0a7c6b62f](https://bsd-hardware.info/?probe=e0a7c6b62f) | Mar 23, 2022 |
| PC Engines    | apu4                        | [4f2d362dd2](https://bsd-hardware.info/?probe=4f2d362dd2) | Mar 22, 2022 |
| ASUSTek       | PRO B460M-C                 | [6ceff4eca1](https://bsd-hardware.info/?probe=6ceff4eca1) | Mar 21, 2022 |
| ASRock        | H570M-ITX/ac                | [c81d79bbe7](https://bsd-hardware.info/?probe=c81d79bbe7) | Mar 18, 2022 |
| Unknown       | Unknown                     | [f41d89a7e9](https://bsd-hardware.info/?probe=f41d89a7e9) | Mar 17, 2022 |
| ASRock        | B75M R2.0                   | [7aac0f4b94](https://bsd-hardware.info/?probe=7aac0f4b94) | Mar 16, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [aa18c11016](https://bsd-hardware.info/?probe=aa18c11016) | Mar 16, 2022 |
| HP            | 8299                        | [6876d2d37d](https://bsd-hardware.info/?probe=6876d2d37d) | Mar 16, 2022 |
| PC Engines    | APU2                        | [6ea85fac4f](https://bsd-hardware.info/?probe=6ea85fac4f) | Mar 15, 2022 |
| Unknown       | YL-J3160L4                  | [2c002dc6a8](https://bsd-hardware.info/?probe=2c002dc6a8) | Mar 15, 2022 |
| Unknown       | Unknown                     | [c2b8c7eebb](https://bsd-hardware.info/?probe=c2b8c7eebb) | Mar 14, 2022 |
| HP            | ProLiant MicroServer Gen... | [f9045f060a](https://bsd-hardware.info/?probe=f9045f060a) | Mar 13, 2022 |
| BESSTAR Te... | IB9                         | [d60b00e2c6](https://bsd-hardware.info/?probe=d60b00e2c6) | Mar 13, 2022 |
| Unknown       | Unknown                     | [8152ca0911](https://bsd-hardware.info/?probe=8152ca0911) | Mar 13, 2022 |
| Gigabyte      | N3150ND3V                   | [382a3e1fbb](https://bsd-hardware.info/?probe=382a3e1fbb) | Mar 12, 2022 |
| Unknown       | YL-J3160L4                  | [592ff80875](https://bsd-hardware.info/?probe=592ff80875) | Mar 12, 2022 |
| PC Engines    | APU2                        | [b8303d5089](https://bsd-hardware.info/?probe=b8303d5089) | Mar 12, 2022 |
| ASUSTek       | P5Q DELUXE                  | [b4234170e8](https://bsd-hardware.info/?probe=b4234170e8) | Mar 10, 2022 |
| NF541         | 1.0                         | [fc2b2bb98d](https://bsd-hardware.info/?probe=fc2b2bb98d) | Mar 09, 2022 |
| Unknown       | Unknown                     | [3ee10c1ab2](https://bsd-hardware.info/?probe=3ee10c1ab2) | Mar 09, 2022 |
| Koloe         | X58                         | [58e098eca2](https://bsd-hardware.info/?probe=58e098eca2) | Mar 09, 2022 |
| Unknown       | Unknown                     | [fea4a692a9](https://bsd-hardware.info/?probe=fea4a692a9) | Mar 09, 2022 |
| Unknown       | Unknown                     | [e89b377c53](https://bsd-hardware.info/?probe=e89b377c53) | Mar 08, 2022 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | [bc73c8dc68](https://bsd-hardware.info/?probe=bc73c8dc68) | Mar 08, 2022 |
| Intel         | DENLOW_WS                   | [bab9d9dd6d](https://bsd-hardware.info/?probe=bab9d9dd6d) | Mar 08, 2022 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | [e3698a706b](https://bsd-hardware.info/?probe=e3698a706b) | Mar 07, 2022 |
| Koloe         | X58                         | [c501dfa5c8](https://bsd-hardware.info/?probe=c501dfa5c8) | Mar 07, 2022 |
| Intel         | DX79TO AAG28805-401         | [431b37f050](https://bsd-hardware.info/?probe=431b37f050) | Mar 06, 2022 |
| CheckPoint    | T-110-00                    | [ecbdeaf92b](https://bsd-hardware.info/?probe=ecbdeaf92b) | Mar 05, 2022 |
| Lanner        | FW-7543 B-GA                | [8ae57434a2](https://bsd-hardware.info/?probe=8ae57434a2) | Mar 03, 2022 |
| Gigabyte      | N3150ND3V                   | [bdf7beae56](https://bsd-hardware.info/?probe=bdf7beae56) | Mar 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | [f5eef026f2](https://bsd-hardware.info/?probe=f5eef026f2) | Mar 02, 2022 |
| Protectli     | VP2410                      | [880c57201a](https://bsd-hardware.info/?probe=880c57201a) | Mar 01, 2022 |
| Supermicro    | A2SDi-LN4F                  | [b10f6655d9](https://bsd-hardware.info/?probe=b10f6655d9) | Mar 01, 2022 |
| BESSTAR Te... | HM90                        | [2d1bf5a79a](https://bsd-hardware.info/?probe=2d1bf5a79a) | Mar 01, 2022 |
| Hardkernel    | ODROID-H2                   | [df62b83093](https://bsd-hardware.info/?probe=df62b83093) | Feb 28, 2022 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [1e8ac02926](https://bsd-hardware.info/?probe=1e8ac02926) | Feb 26, 2022 |
| AAEON         | FWS-2280 V1.0               | [9fba128986](https://bsd-hardware.info/?probe=9fba128986) | Feb 26, 2022 |
| Unknown       | Unknown                     | [a771f78447](https://bsd-hardware.info/?probe=a771f78447) | Feb 26, 2022 |
| PC Engines    | apu4                        | [74c708a6cf](https://bsd-hardware.info/?probe=74c708a6cf) | Feb 25, 2022 |
| Unknown       | Unknown                     | [2bbb963d9f](https://bsd-hardware.info/?probe=2bbb963d9f) | Feb 25, 2022 |
| Unknown       | Unknown                     | [c559dbe233](https://bsd-hardware.info/?probe=c559dbe233) | Feb 25, 2022 |
| PC Engines    | apu4                        | [ed16e6ac1f](https://bsd-hardware.info/?probe=ed16e6ac1f) | Feb 24, 2022 |
| YANYU         | M9F baytrail                | [3804d3fb1d](https://bsd-hardware.info/?probe=3804d3fb1d) | Feb 24, 2022 |
| ASUSTek       | P11C-I Series               | [f768f45dc2](https://bsd-hardware.info/?probe=f768f45dc2) | Feb 23, 2022 |
| BESSTAR Te... | JB9                         | [e788cec5f5](https://bsd-hardware.info/?probe=e788cec5f5) | Feb 22, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [e55cb672b2](https://bsd-hardware.info/?probe=e55cb672b2) | Feb 21, 2022 |
| Unknown       | Unknown                     | [db8e4dc1f5](https://bsd-hardware.info/?probe=db8e4dc1f5) | Feb 21, 2022 |
| Unknown       | Unknown                     | [9a280f5e25](https://bsd-hardware.info/?probe=9a280f5e25) | Feb 21, 2022 |
| BESSTAR Te... | JB9                         | [7df0c12efe](https://bsd-hardware.info/?probe=7df0c12efe) | Feb 19, 2022 |
| Unknown       | Unknown                     | [883cf2382b](https://bsd-hardware.info/?probe=883cf2382b) | Feb 17, 2022 |
| ASRock        | H570M-ITX/ac                | [1e54f9ca54](https://bsd-hardware.info/?probe=1e54f9ca54) | Feb 17, 2022 |
| ASRock        | 4X4-R1000                   | [c25f53782a](https://bsd-hardware.info/?probe=c25f53782a) | Feb 17, 2022 |
| YANYU         | M9F baytrail                | [a568d8241d](https://bsd-hardware.info/?probe=a568d8241d) | Feb 16, 2022 |
| ASUSTek       | P11C-M Series               | [459ff0f748](https://bsd-hardware.info/?probe=459ff0f748) | Feb 16, 2022 |
| Gigabyte      | C246M-WU4-CF                | [4b6c6d8bde](https://bsd-hardware.info/?probe=4b6c6d8bde) | Feb 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [cb2ab6f97a](https://bsd-hardware.info/?probe=cb2ab6f97a) | Feb 15, 2022 |
| Unknown       | MANIFOLD 2-C                | [4980cae3eb](https://bsd-hardware.info/?probe=4980cae3eb) | Feb 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [53ec9f2960](https://bsd-hardware.info/?probe=53ec9f2960) | Feb 14, 2022 |
| Intel         | MAHOBAY                     | [d3d818c49f](https://bsd-hardware.info/?probe=d3d818c49f) | Feb 13, 2022 |
| Unknown       | Unknown                     | [923aba4efb](https://bsd-hardware.info/?probe=923aba4efb) | Feb 12, 2022 |
| AOpen         | i67QMx-DV R1.00TS2 55MP6... | [c3b6cdf519](https://bsd-hardware.info/?probe=c3b6cdf519) | Feb 12, 2022 |
| CheckPoint    | T-140-00                    | [e41ba68aa2](https://bsd-hardware.info/?probe=e41ba68aa2) | Feb 11, 2022 |
| Unknown       | Unknown                     | [64cb6534ff](https://bsd-hardware.info/?probe=64cb6534ff) | Feb 11, 2022 |
| Supermicro    | X11SBA-LN4FA                | [e547e2343a](https://bsd-hardware.info/?probe=e547e2343a) | Feb 10, 2022 |
| Thomas-Kre... | LES network 6L              | [18df27c327](https://bsd-hardware.info/?probe=18df27c327) | Feb 10, 2022 |
| Unknown       | Q2XX V1.0                   | [1e3cfd4559](https://bsd-hardware.info/?probe=1e3cfd4559) | Feb 09, 2022 |
| ASRock        | J5040-ITX                   | [5a614c6238](https://bsd-hardware.info/?probe=5a614c6238) | Feb 08, 2022 |
| Unknown       | Unknown                     | [aff2852632](https://bsd-hardware.info/?probe=aff2852632) | Feb 07, 2022 |
| BESSTAR Te... | HM90                        | [619b239937](https://bsd-hardware.info/?probe=619b239937) | Feb 07, 2022 |
| ASRock        | Q1900M                      | [1bb0094772](https://bsd-hardware.info/?probe=1bb0094772) | Feb 07, 2022 |
| Fujitsu       | D3544-Sx S26361-D3544-Sx... | [e279b10250](https://bsd-hardware.info/?probe=e279b10250) | Feb 07, 2022 |
| PC Engines    | apu4                        | [1bde386ab2](https://bsd-hardware.info/?probe=1bde386ab2) | Feb 06, 2022 |
| Gigabyte      | X570 GAMING X               | [0eb520b964](https://bsd-hardware.info/?probe=0eb520b964) | Feb 06, 2022 |
| ASRock        | Q1900M                      | [1840d289c9](https://bsd-hardware.info/?probe=1840d289c9) | Feb 06, 2022 |
| Intel         | CRESCENTBAY                 | [2764fb2282](https://bsd-hardware.info/?probe=2764fb2282) | Feb 06, 2022 |
| Unknown       | Unknown                     | [8d38089ced](https://bsd-hardware.info/?probe=8d38089ced) | Feb 06, 2022 |
| Unknown       | Unknown                     | [12e979c82a](https://bsd-hardware.info/?probe=12e979c82a) | Feb 06, 2022 |
| Unknown       | Unknown                     | [2a3867a849](https://bsd-hardware.info/?probe=2a3867a849) | Feb 06, 2022 |
| Unknown       | Q2XX V1.0                   | [633ad33c05](https://bsd-hardware.info/?probe=633ad33c05) | Feb 06, 2022 |
| CheckPoint    | T-140-00                    | [92af3888c0](https://bsd-hardware.info/?probe=92af3888c0) | Feb 04, 2022 |
| CheckPoint    | T-110-00                    | [65f271c2c8](https://bsd-hardware.info/?probe=65f271c2c8) | Feb 04, 2022 |
| ASUSTek       | H81M-A                      | [d0c6e027a0](https://bsd-hardware.info/?probe=d0c6e027a0) | Feb 04, 2022 |
| ASRock        | A520M-ITX/ac                | [45d4853cd4](https://bsd-hardware.info/?probe=45d4853cd4) | Feb 03, 2022 |
| ASRock        | B85M Pro3                   | [6d1223c3d1](https://bsd-hardware.info/?probe=6d1223c3d1) | Feb 02, 2022 |
| PC Engines    | APU2                        | [c2337ada02](https://bsd-hardware.info/?probe=c2337ada02) | Feb 02, 2022 |
| Unknown       | MANIFOLD 2-C                | [faff4c7609](https://bsd-hardware.info/?probe=faff4c7609) | Feb 01, 2022 |
| Unknown       | Unknown                     | [82d9df0427](https://bsd-hardware.info/?probe=82d9df0427) | Feb 01, 2022 |
| BESSTAR Te... | JB9                         | [8f1ac8e4bc](https://bsd-hardware.info/?probe=8f1ac8e4bc) | Jan 31, 2022 |
| Supermicro    | X11SBA-LN4FA                | [d040ad4922](https://bsd-hardware.info/?probe=d040ad4922) | Jan 31, 2022 |
| PC Engines    | APU3                        | [b03f53313d](https://bsd-hardware.info/?probe=b03f53313d) | Jan 31, 2022 |
| PC Engines    | apu4                        | [1f02497c18](https://bsd-hardware.info/?probe=1f02497c18) | Jan 30, 2022 |
| SIEMENS       | A5E38156881 RS-AE           | [d1d16a420e](https://bsd-hardware.info/?probe=d1d16a420e) | Jan 30, 2022 |
| Hardkernel    | ODROID-H2                   | [b27a7274cf](https://bsd-hardware.info/?probe=b27a7274cf) | Jan 30, 2022 |
| HARDKERNEL    | ODROID-H2                   | [292cb706a0](https://bsd-hardware.info/?probe=292cb706a0) | Jan 30, 2022 |
| BESSTAR Te... | HM90                        | [74c01cf184](https://bsd-hardware.info/?probe=74c01cf184) | Jan 30, 2022 |
| PC Engines    | APU2                        | [f65e5a625b](https://bsd-hardware.info/?probe=f65e5a625b) | Jan 30, 2022 |
| CheckPoint    | T-120-00                    | [8777e1a17d](https://bsd-hardware.info/?probe=8777e1a17d) | Jan 29, 2022 |
| Protectli     | FW4B Ver                    | [cee618086f](https://bsd-hardware.info/?probe=cee618086f) | Jan 29, 2022 |
| Hardkernel    | ODROID-H2                   | [540757d1b7](https://bsd-hardware.info/?probe=540757d1b7) | Jan 29, 2022 |
| PC Engines    | APU2                        | [0a504f17ee](https://bsd-hardware.info/?probe=0a504f17ee) | Jan 29, 2022 |
| Gigabyte      | Z590 VISION G               | [9c73c01062](https://bsd-hardware.info/?probe=9c73c01062) | Jan 28, 2022 |
| Protectli     | FW4B Ver                    | [ba4865faf2](https://bsd-hardware.info/?probe=ba4865faf2) | Jan 28, 2022 |
| PC Engines    | apu1                        | [33819c7652](https://bsd-hardware.info/?probe=33819c7652) | Jan 27, 2022 |
| Supermicro    | A2SDi-LN4F                  | [38f999c445](https://bsd-hardware.info/?probe=38f999c445) | Jan 27, 2022 |
| HP            | 18E4                        | [67080049c6](https://bsd-hardware.info/?probe=67080049c6) | Jan 27, 2022 |
| HP            | 213D A01                    | [659a73beac](https://bsd-hardware.info/?probe=659a73beac) | Jan 26, 2022 |
| Unknown       | Unknown                     | [6831896a2b](https://bsd-hardware.info/?probe=6831896a2b) | Jan 26, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [c9f915399a](https://bsd-hardware.info/?probe=c9f915399a) | Jan 25, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [6ca20b88e7](https://bsd-hardware.info/?probe=6ca20b88e7) | Jan 25, 2022 |
| Deciso        | Netboard A10 V2.1           | [f4e3c83813](https://bsd-hardware.info/?probe=f4e3c83813) | Jan 24, 2022 |
| Biostar       | J4105NHU                    | [8513067567](https://bsd-hardware.info/?probe=8513067567) | Jan 24, 2022 |
| Intel         | MAHOBAY                     | [9ad0c66586](https://bsd-hardware.info/?probe=9ad0c66586) | Jan 23, 2022 |
| HP            | 8648                        | [b0adf55067](https://bsd-hardware.info/?probe=b0adf55067) | Jan 23, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [8597e1c1e4](https://bsd-hardware.info/?probe=8597e1c1e4) | Jan 22, 2022 |
| Dell          | VEP-4600-V910 0PDG1JA02     | [63699d431a](https://bsd-hardware.info/?probe=63699d431a) | Jan 21, 2022 |
| Dell          | 0NNNCT A01                  | [290f10c785](https://bsd-hardware.info/?probe=290f10c785) | Jan 21, 2022 |
| Unknown       | PICO PC                     | [70dca31596](https://bsd-hardware.info/?probe=70dca31596) | Jan 19, 2022 |
| ASUSTek       | AT5NM10-I                   | [dea1ec292d](https://bsd-hardware.info/?probe=dea1ec292d) | Jan 18, 2022 |
| Unknown       | Unknown                     | [9c34dd06dc](https://bsd-hardware.info/?probe=9c34dd06dc) | Jan 18, 2022 |
| ASRock        | H570M-ITX/ac                | [a188e2d1bc](https://bsd-hardware.info/?probe=a188e2d1bc) | Jan 17, 2022 |
| Unknown       | Unknown                     | [92ee8c8c45](https://bsd-hardware.info/?probe=92ee8c8c45) | Jan 17, 2022 |
| Gigabyte      | MZBSWBP-00                  | [5e980b75bc](https://bsd-hardware.info/?probe=5e980b75bc) | Jan 16, 2022 |
| Unknown       | Unknown                     | [010c0f9489](https://bsd-hardware.info/?probe=010c0f9489) | Jan 15, 2022 |
| OEM           | 1.0                         | [2bc6be75f3](https://bsd-hardware.info/?probe=2bc6be75f3) | Jan 13, 2022 |
| Protectli     | VP2410                      | [4dd1b9065c](https://bsd-hardware.info/?probe=4dd1b9065c) | Jan 13, 2022 |
| PC Engines    | APU2                        | [b1f37f5ec0](https://bsd-hardware.info/?probe=b1f37f5ec0) | Jan 12, 2022 |
| SIEMENS       | A5E38156881 RS-AE           | [9940cdeaae](https://bsd-hardware.info/?probe=9940cdeaae) | Jan 12, 2022 |
| HP            | ProLiant MicroServer        | [0da2a93271](https://bsd-hardware.info/?probe=0da2a93271) | Jan 11, 2022 |
| Lanner        | FW-7543 B-GA                | [20834b9ab3](https://bsd-hardware.info/?probe=20834b9ab3) | Jan 11, 2022 |
| HP            | ProLiant MicroServer        | [e95a3dd5ec](https://bsd-hardware.info/?probe=e95a3dd5ec) | Jan 10, 2022 |
| PC Engines    | apu1                        | [1d0acc276d](https://bsd-hardware.info/?probe=1d0acc276d) | Jan 10, 2022 |
| HP            | 3397                        | [7740208542](https://bsd-hardware.info/?probe=7740208542) | Jan 09, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [db01451a9c](https://bsd-hardware.info/?probe=db01451a9c) | Jan 08, 2022 |
| ASRock        | Q1900M                      | [c10bf0783b](https://bsd-hardware.info/?probe=c10bf0783b) | Jan 08, 2022 |
| HP            | 213D A01                    | [b11b8d0a83](https://bsd-hardware.info/?probe=b11b8d0a83) | Jan 06, 2022 |
| Dell          | 0MN1TX A03                  | [89308fe374](https://bsd-hardware.info/?probe=89308fe374) | Jan 05, 2022 |
| ASUSTek       | TUF GAMING B550-PLUS        | [ea4719600a](https://bsd-hardware.info/?probe=ea4719600a) | Jan 05, 2022 |
| Lenovo        | SHARKBAY NOK                | [00a423476f](https://bsd-hardware.info/?probe=00a423476f) | Dec 31, 2021 |
| Lenovo        | SHARKBAY NOK                | [a5cc2ac2e5](https://bsd-hardware.info/?probe=a5cc2ac2e5) | Dec 30, 2021 |
| Supermicro    | X8SIL                       | [447f2bd30c](https://bsd-hardware.info/?probe=447f2bd30c) | Dec 30, 2021 |
| Unknown       | Unknown                     | [1c45cd1b45](https://bsd-hardware.info/?probe=1c45cd1b45) | Dec 29, 2021 |
| Advantech     | SYS-2USM02-6M01E            | [6952d74233](https://bsd-hardware.info/?probe=6952d74233) | Dec 29, 2021 |
| ASRock        | X470 Gaming-ITX/ac          | [18eeaf2963](https://bsd-hardware.info/?probe=18eeaf2963) | Dec 29, 2021 |
| ASUSTek       | AT5NM10-I                   | [07903fe3b2](https://bsd-hardware.info/?probe=07903fe3b2) | Dec 28, 2021 |
| NEXCOM        | NSA3110 B                   | [213dc9c3ef](https://bsd-hardware.info/?probe=213dc9c3ef) | Dec 28, 2021 |
| Intel         | DQ67OW AAG12528-310         | [7a41b1560b](https://bsd-hardware.info/?probe=7a41b1560b) | Dec 28, 2021 |
| Unknown       | Unknown                     | [a3bbd9d497](https://bsd-hardware.info/?probe=a3bbd9d497) | Dec 28, 2021 |
| Unknown       | Unknown                     | [e8ea8ca2d4](https://bsd-hardware.info/?probe=e8ea8ca2d4) | Dec 27, 2021 |
| Unknown       | Unknown                     | [8081818610](https://bsd-hardware.info/?probe=8081818610) | Dec 27, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OPNsense 21.7.7   | 43       | 3%      |
| OPNsense 21.1     | 42       | 2.94%   |
| OPNsense 22.7.10  | 40       | 2.8%    |
| OPNsense 21.7.1   | 38       | 2.66%   |
| OPNsense 21.1.5   | 38       | 2.66%   |
| OPNsense 22.1     | 36       | 2.52%   |
| OPNsense 20.7.8   | 34       | 2.38%   |
| OPNsense 21.7.3   | 33       | 2.31%   |
| OPNsense 21.1.3   | 32       | 2.24%   |
| OPNsense 23.1.11  | 31       | 2.17%   |
| OPNsense 22.7.9   | 31       | 2.17%   |
| OPNsense 21.1.4   | 31       | 2.17%   |
| OPNsense 22.1.8   | 30       | 2.1%    |
| OPNsense 21.7.6   | 30       | 2.1%    |
| OPNsense 22.7.4   | 29       | 2.03%   |
| OPNsense 21.1.2   | 29       | 2.03%   |
| OPNsense 21.1.1   | 29       | 2.03%   |
| OPNsense 23.1.5   | 28       | 1.96%   |
| OPNsense 23.1.1   | 28       | 1.96%   |
| OPNsense 22.7.6   | 27       | 1.89%   |
| OPNsense 23.1     | 26       | 1.82%   |
| OPNsense 23.1.7   | 24       | 1.68%   |
| OPNsense 22.1.6   | 24       | 1.68%   |
| OPNsense 21.7.5   | 24       | 1.68%   |
| OPNsense 23.1.9   | 23       | 1.61%   |
| OPNsense 22.1.10  | 21       | 1.47%   |
| OPNsense 22.1.2   | 18       | 1.26%   |
| helloSystem 0.4.0 | 18       | 1.26%   |
| OPNsense 22.7.7   | 17       | 1.19%   |
| OPNsense 22.7.11  | 17       | 1.19%   |
| OPNsense 22.7     | 17       | 1.19%   |
| OPNsense 22.1.4   | 17       | 1.19%   |
| OPNsense 22.1.1   | 17       | 1.19%   |
| OPNsense 23.1.4   | 16       | 1.12%   |
| OPNsense 23.7     | 15       | 1.05%   |
| OPNsense 22.1.9   | 15       | 1.05%   |
| OpenBSD 6.8       | 15       | 1.05%   |
| OPNsense 22.7.2   | 13       | 0.91%   |
| OPNsense 21.7.2   | 13       | 0.91%   |
| OPNsense 21.1.7   | 13       | 0.91%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 847      | 78.14%  |
| FreeBSD     | 112      | 10.33%  |
| helloSystem | 56       | 5.17%   |
| OpenBSD     | 34       | 3.14%   |
| GhostBSD    | 14       | 1.29%   |
| NomadBSD    | 5        | 0.46%   |
| NetBSD      | 4        | 0.37%   |
| TrueNAS     | 3        | 0.28%   |
| pfSense     | 2        | 0.18%   |
| MyBee       | 2        | 0.18%   |
| PC-BSD      | 1        | 0.09%   |
| HardenedBSD | 1        | 0.09%   |
| FreeNAS     | 1        | 0.09%   |
| DragonFly   | 1        | 0.09%   |
| ClonOS      | 1        | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 1068     | 99.16%  |
| arm64   | 4        | 0.37%   |
| i386    | 2        | 0.19%   |
| arm     | 2        | 0.19%   |
| sparc64 | 1        | 0.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 929      | 85.39%  |
| helloDesktop  | 66       | 6.07%   |
| MATE          | 19       | 1.75%   |
| KDE5          | 16       | 1.47%   |
| fvwm          | 12       | 1.1%    |
| XFCE          | 11       | 1.01%   |
| TWM           | 7        | 0.64%   |
| AwesomeWM     | 7        | 0.64%   |
| GNOME         | 6        | 0.55%   |
| Openbox       | 4        | 0.37%   |
| i3            | 3        | 0.28%   |
| LXQt          | 1        | 0.09%   |
| LXDE          | 1        | 0.09%   |
| GNUstep       | 1        | 0.09%   |
| Fluxbox       | 1        | 0.09%   |
| filer         | 1        | 0.09%   |
| Enlightenment | 1        | 0.09%   |
| Compton       | 1        | 0.09%   |
| Cinnamon      | 1        | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 939      | 87.03%  |
| X11     | 139      | 12.88%  |
| Tty     | 1        | 0.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 965      | 88.86%  |
| SLiM    | 71       | 6.54%   |
| LightDM | 17       | 1.57%   |
| SDDM    | 15       | 1.38%   |
| XDM     | 10       | 0.92%   |
| GDM     | 6        | 0.55%   |
| Ly      | 2        | 0.18%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Desktops | Percent |
|-----------------|----------|---------|
| Unknown         | 903      | 82.92%  |
| en_US           | 64       | 5.88%   |
| C               | 64       | 5.88%   |
| de_DE           | 43       | 3.95%   |
| fr_FR           | 4        | 0.37%   |
| en              | 3        | 0.28%   |
| en_GB           | 2        | 0.18%   |
| ru_RU           | 1        | 0.09%   |
| ISO8859-15      | 1        | 0.09%   |
| fr              | 1        | 0.09%   |
| en_DE           | 1        | 0.09%   |
| de_DE.ISO8859-1 | 1        | 0.09%   |
| de              | 1        | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 931      | 85.96%  |
| BIOS | 152      | 14.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 696      | 63.04%  |
| Zfs     | 355      | 32.16%  |
| Ffs     | 34       | 3.08%   |
| Cd9660  | 18       | 1.63%   |
| Hammer2 | 1        | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 994      | 91.87%  |
| MBR     | 69       | 6.38%   |
| Unknown | 18       | 1.66%   |
| BSD     | 1        | 0.09%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 181      | 16.81%  |
| PC Engines                 | 117      | 10.86%  |
| Fujitsu                    | 85       | 7.89%   |
| ASUSTek Computer           | 76       | 7.06%   |
| ASRock                     | 67       | 6.22%   |
| Hewlett-Packard            | 61       | 5.66%   |
| Intel                      | 51       | 4.74%   |
| Gigabyte Technology        | 51       | 4.74%   |
| MSI                        | 40       | 3.71%   |
| Dell                       | 40       | 3.71%   |
| Supermicro                 | 29       | 2.69%   |
| Protectli                  | 25       | 2.32%   |
| BESSTAR Tech               | 19       | 1.76%   |
| Shuttle                    | 18       | 1.67%   |
| CncTion                    | 18       | 1.67%   |
| Lenovo                     | 17       | 1.58%   |
| Techvision                 | 15       | 1.39%   |
| Hardkernel                 | 13       | 1.21%   |
| Thomas-Krenn.AG            | 9        | 0.84%   |
| MW                         | 9        | 0.84%   |
| NF541                      | 8        | 0.74%   |
| CheckPoint                 | 8        | 0.74%   |
| ASRockRack                 | 8        | 0.74%   |
| Biostar                    | 7        | 0.65%   |
| Yanling                    | 5        | 0.46%   |
| Lanner                     | 5        | 0.46%   |
| Deciso                     | 5        | 0.46%   |
| Beckhoff Automation        | 5        | 0.46%   |
| NEXCOM                     | 4        | 0.37%   |
| Lex                        | 4        | 0.37%   |
| IceWhale Technology        | 4        | 0.37%   |
| Foxconn                    | 4        | 0.37%   |
| Advantech                  | 4        | 0.37%   |
| Acer                       | 4        | 0.37%   |
| ZOTAC                      | 3        | 0.28%   |
| ShenZhen MinWin Technology | 3        | 0.28%   |
| Medion                     | 3        | 0.28%   |
| YANYU                      | 2        | 0.19%   |
| Wortmann AG                | 2        | 0.19%   |
| OEM                        | 2        | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 186      | 17.27%  |
| PC Engines APU2                | 57       | 5.29%   |
| Fujitsu FUTRO S920             | 42       | 3.9%    |
| PC Engines apu4                | 38       | 3.53%   |
| Intel Q3XXG4-P V1.0            | 18       | 1.67%   |
| Techvision TVI7309X            | 15       | 1.39%   |
| HARDKERNEL ODROID-H2           | 12       | 1.11%   |
| Protectli FW6                  | 9        | 0.84%   |
| Protectli FW4B                 | 9        | 0.84%   |
| PC Engines APU                 | 9        | 0.84%   |
| MW GMLK-2_5G4L                 | 9        | 0.84%   |
| HP ProLiant MicroServer Gen8   | 9        | 0.84%   |
| CncTion N5105-4L               | 9        | 0.84%   |
| BESSTAR Tech X35G              | 9        | 0.84%   |
| PC Engines APU3                | 8        | 0.74%   |
| NF541 1.0                      | 7        | 0.65%   |
| HP t620 PLUS Quad Core TC      | 6        | 0.56%   |
| Fujitsu FUTRO S930             | 6        | 0.56%   |
| Thomas-Krenn.AG LES network+   | 5        | 0.46%   |
| CncTion J4125-4L-I225          | 5        | 0.46%   |
| ASUS All Series                | 5        | 0.46%   |
| Supermicro X7SPA-HF            | 4        | 0.37%   |
| Protectli VP2420               | 4        | 0.37%   |
| PC Engines apu1                | 4        | 0.37%   |
| NEXCOM ASG                     | 4        | 0.37%   |
| MSI MS-7816                    | 4        | 0.37%   |
| Lex Pineview-D                 | 4        | 0.37%   |
| Lanner GP-7543                 | 4        | 0.37%   |
| IceWhale ZimaBoard 832 ZMB     | 4        | 0.37%   |
| HP t620 Quad Core TC           | 4        | 0.37%   |
| HP Compaq Elite 8300 SFF       | 4        | 0.37%   |
| Dell OptiPlex 9020             | 4        | 0.37%   |
| Dell OptiPlex 7010             | 4        | 0.37%   |
| Deciso Netboard A10 V2         | 4        | 0.37%   |
| ASUS M5A78L-M/USB3             | 4        | 0.37%   |
| Thomas-Krenn.AG LES network 6L | 3        | 0.28%   |
| Supermicro X8SIL               | 3        | 0.28%   |
| MSI MS-7B89                    | 3        | 0.28%   |
| MSI MS-7592                    | 3        | 0.28%   |
| Intel DENLOW_WS                | 3        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Unknown               | 186      | 17.27%  |
| PC Engines APU2       | 57       | 5.29%   |
| Fujitsu FUTRO         | 57       | 5.29%   |
| PC Engines apu4       | 38       | 3.53%   |
| Dell OptiPlex         | 32       | 2.97%   |
| Intel Q3XXG4-P        | 18       | 1.67%   |
| Techvision TVI7309X   | 15       | 1.39%   |
| HP ProLiant           | 14       | 1.3%    |
| Lenovo ThinkCentre    | 13       | 1.21%   |
| Fujitsu ESPRIMO       | 13       | 1.21%   |
| HP Compaq             | 12       | 1.11%   |
| HARDKERNEL ODROID-H2  | 12       | 1.11%   |
| HP t620               | 11       | 1.02%   |
| HP ProDesk            | 11       | 1.02%   |
| ASUS PRIME            | 10       | 0.93%   |
| Protectli FW6         | 9        | 0.84%   |
| Protectli FW4B        | 9        | 0.84%   |
| PC Engines APU        | 9        | 0.84%   |
| MW GMLK-2             | 9        | 0.84%   |
| CncTion N5105-4L      | 9        | 0.84%   |
| BESSTAR Tech X35G     | 9        | 0.84%   |
| ASUS TUF              | 9        | 0.84%   |
| Thomas-Krenn.AG LES   | 8        | 0.74%   |
| PC Engines APU3       | 8        | 0.74%   |
| NF541 1.0             | 7        | 0.65%   |
| HP EliteDesk          | 6        | 0.56%   |
| Deciso Netboard       | 5        | 0.46%   |
| CncTion J4125-4L-I225 | 5        | 0.46%   |
| ASUS ROG              | 5        | 0.46%   |
| ASUS PRO              | 5        | 0.46%   |
| ASUS All              | 5        | 0.46%   |
| Supermicro X7SPA-HF   | 4        | 0.37%   |
| Protectli VP2420      | 4        | 0.37%   |
| PC Engines apu1       | 4        | 0.37%   |
| NEXCOM ASG            | 4        | 0.37%   |
| MSI MS-7816           | 4        | 0.37%   |
| Lex Pineview-D        | 4        | 0.37%   |
| Lanner GP-7543        | 4        | 0.37%   |
| IceWhale ZimaBoard    | 4        | 0.37%   |
| Gigabyte X570         | 4        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 136      | 12.63%  |
| 2016    | 118      | 10.96%  |
| 2020    | 113      | 10.49%  |
| 2021    | 107      | 9.94%   |
| 2022    | 103      | 9.56%   |
| 2019    | 97       | 9.01%   |
| 2014    | 91       | 8.45%   |
| 2017    | 64       | 5.94%   |
| 2013    | 60       | 5.57%   |
| 2012    | 50       | 4.64%   |
| 2011    | 36       | 3.34%   |
| 2010    | 27       | 2.51%   |
| 2015    | 22       | 2.04%   |
| 2009    | 21       | 1.95%   |
| 2023    | 10       | 0.93%   |
| 2008    | 8        | 0.74%   |
| Unknown | 8        | 0.74%   |
| 2007    | 4        | 0.37%   |
| 2006    | 2        | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1077     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 947      | 87.93%  |
| Yes  | 130      | 12.07%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 399      | 36.37%  |
| 4.01-8.0        | 284      | 25.89%  |
| 16.01-24.0      | 228      | 20.78%  |
| 32.01-64.0      | 87       | 7.93%   |
| 2.01-3.0        | 40       | 3.65%   |
| 64.01-256.0     | 31       | 2.83%   |
| 24.01-32.0      | 9        | 0.82%   |
| 3.01-4.0        | 7        | 0.64%   |
| 1.01-2.0        | 4        | 0.36%   |
| 0.51-1.0        | 3        | 0.27%   |
| 0.01-0.5        | 3        | 0.27%   |
| More than 256.0 | 2        | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 598      | 53.54%  |
| 0.51-1.0    | 360      | 32.23%  |
| 1.01-2.0    | 90       | 8.06%   |
| 2.01-3.0    | 23       | 2.06%   |
| 3.01-4.0    | 13       | 1.16%   |
| 4.01-8.0    | 12       | 1.07%   |
| 0           | 5        | 0.45%   |
| 16.01-24.0  | 4        | 0.36%   |
| Unknown     | 4        | 0.36%   |
| 8.01-16.0   | 3        | 0.27%   |
| 24.01-32.0  | 2        | 0.18%   |
| 64.01-256.0 | 2        | 0.18%   |
| 32.01-64.0  | 1        | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 821      | 74.23%  |
| 2      | 108      | 9.76%   |
| 0      | 80       | 7.23%   |
| 3      | 41       | 3.71%   |
| 4      | 28       | 2.53%   |
| 5      | 13       | 1.18%   |
| 6      | 7        | 0.63%   |
| 7      | 5        | 0.45%   |
| 8      | 2        | 0.18%   |
| 9      | 1        | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 943      | 86.99%  |
| Yes       | 141      | 13.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1069     | 99.26%  |
| No        | 8        | 0.74%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 886      | 81.43%  |
| Yes       | 202      | 18.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 972      | 89.92%  |
| Yes       | 109      | 10.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Germany | 1077     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Berlin            | 99       | 8.16%   |
| Munich            | 48       | 3.96%   |
| Hamburg           | 41       | 3.38%   |
| Cologne           | 32       | 2.64%   |
| Frankfurt am Main | 29       | 2.39%   |
| Stuttgart         | 21       | 1.73%   |
| Ludwigsburg       | 18       | 1.48%   |
| Karlsruhe         | 14       | 1.15%   |
| Hanover           | 12       | 0.99%   |
| Nuremberg         | 11       | 0.91%   |
| Falkenstein       | 11       | 0.91%   |
| Dresden           | 10       | 0.82%   |
| Dortmund          | 10       | 0.82%   |
| Mannheim          | 9        | 0.74%   |
| Bonn              | 9        | 0.74%   |
| Wiesbaden         | 8        | 0.66%   |
| Duisburg          | 8        | 0.66%   |
| Braunschweig      | 8        | 0.66%   |
| Bochum            | 8        | 0.66%   |
| Bielefeld         | 8        | 0.66%   |
| Ulm               | 7        | 0.58%   |
| Reutlingen        | 7        | 0.58%   |
| Leipzig           | 7        | 0.58%   |
| Heidelberg        | 7        | 0.58%   |
| Darmstadt         | 7        | 0.58%   |
| Chemnitz          | 7        | 0.58%   |
| Wuppertal         | 6        | 0.49%   |
| Paderborn         | 6        | 0.49%   |
| Kiel              | 6        | 0.49%   |
| Augsburg          | 6        | 0.49%   |
| Siegen            | 5        | 0.41%   |
| Magdeburg         | 5        | 0.41%   |
| Kassel            | 5        | 0.41%   |
| Jena              | 5        | 0.41%   |
| Heilbronn         | 5        | 0.41%   |
| Hamm              | 5        | 0.41%   |
| DГјsseldorf     | 5        | 0.41%   |
| Düsseldorf       | 5        | 0.41%   |
| Bremen            | 5        | 0.41%   |
| Borken            | 5        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 190      | 317    | 15.47%  |
| WDC                 | 107      | 188    | 8.71%   |
| Transcend           | 106      | 152    | 8.63%   |
| Kingston            | 101      | 171    | 8.22%   |
| Crucial             | 71       | 105    | 5.78%   |
| SanDisk             | 70       | 101    | 5.7%    |
| Seagate             | 62       | 101    | 5.05%   |
| Intel               | 55       | 79     | 4.48%   |
| Toshiba             | 45       | 75     | 3.66%   |
| China               | 43       | 50     | 3.5%    |
| Phison              | 38       | 54     | 3.09%   |
| Hoodisk             | 29       | 51     | 2.36%   |
| Intenso             | 26       | 42     | 2.12%   |
| Hitachi             | 21       | 41     | 1.71%   |
| Innodisk            | 20       | 22     | 1.63%   |
| HGST                | 20       | 37     | 1.63%   |
| Micron Technology   | 14       | 28     | 1.14%   |
| FORESEE             | 13       | 18     | 1.06%   |
| A-DATA Technology   | 13       | 16     | 1.06%   |
| OCZ                 | 10       | 14     | 0.81%   |
| NVMe                | 9        | 15     | 0.73%   |
| SPCC                | 8        | 12     | 0.65%   |
| Apacer              | 8        | 14     | 0.65%   |
| Patriot             | 7        | 9      | 0.57%   |
| Protectli           | 6        | 8      | 0.49%   |
| Dogfish             | 6        | 7      | 0.49%   |
| Corsair             | 6        | 10     | 0.49%   |
| ATP                 | 6        | 6      | 0.49%   |
| TCSUNBOW            | 5        | 6      | 0.41%   |
| SK hynix            | 5        | 5      | 0.41%   |
| LITEONIT            | 5        | 6      | 0.41%   |
| KIOXIA-EXCERIA      | 5        | 11     | 0.41%   |
| Gigabyte Technology | 5        | 6      | 0.41%   |
| Vaseky              | 4        | 4      | 0.33%   |
| ShiJi               | 4        | 5      | 0.33%   |
| KingDian            | 4        | 10     | 0.33%   |
| Hewlett-Packard     | 4        | 5      | 0.33%   |
| Verbatim            | 3        | 4      | 0.24%   |
| Team                | 3        | 3      | 0.24%   |
| PNY                 | 3        | 3      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Phison SATA SSD 16GB             | 31       | 2.39%   |
| Transcend TS128GMSA230S 128GB    | 27       | 2.08%   |
| China SATA SSD 16GB              | 20       | 1.54%   |
| Samsung SSD 850 EVO 250GB        | 14       | 1.08%   |
| Transcend TS64GMSA230S 64GB      | 13       | 1%      |
| Samsung SSD 860 EVO 500GB        | 13       | 1%      |
| Crucial CT240BX500SSD1 240GB     | 13       | 1%      |
| Transcend TS256GMSA230S 256GB    | 11       | 0.85%   |
| Kingston SUV500MS120G 120GB      | 11       | 0.85%   |
| Innodisk DEMSR- 08GB mSATA 3ME3  | 11       | 0.85%   |
| Samsung SSD 870 EVO 250GB        | 10       | 0.77%   |
| Hoodisk SSD 64GB                 | 10       | 0.77%   |
| Kingston SA400S37120G 120GB      | 9        | 0.69%   |
| Transcend TS32GMSA370 32GB       | 8        | 0.62%   |
| Kingston SA400S37240G 240GB      | 8        | 0.62%   |
| Transcend TS32GSSD370S 32GB      | 7        | 0.54%   |
| Transcend TS128GMSA370 128GB     | 7        | 0.54%   |
| Samsung SSD 970 EVO Plus 500GB   | 7        | 0.54%   |
| Samsung SSD 840 EVO 250GB        | 7        | 0.54%   |
| Kingston SV300S37A120G 120GB     | 7        | 0.54%   |
| Kingston OM8PDP3512B-A01 512GB   | 7        | 0.54%   |
| Hoodisk SSD 256GB                | 7        | 0.54%   |
| Hoodisk SSD 128GB                | 7        | 0.54%   |
| Crucial CT500MX500SSD1 500GB     | 7        | 0.54%   |
| Transcend TS64GMSA370 64GB       | 6        | 0.46%   |
| SanDisk SSD PLUS 120GB           | 6        | 0.46%   |
| SanDisk SDSSDA120G 120GB         | 6        | 0.46%   |
| Samsung SSD 850 PRO 256GB        | 6        | 0.46%   |
| Samsung SSD 840 EVO 120GB        | 6        | 0.46%   |
| Kingston SV300S37A60G 64GB       | 6        | 0.46%   |
| Intenso SSD 120GB                | 6        | 0.46%   |
| FORESEE 64GB SSD                 | 6        | 0.46%   |
| Crucial CT120BX500SSD1 120GB     | 6        | 0.46%   |
| WDC WD40EFRX-68N32N0 4TB         | 5        | 0.39%   |
| Toshiba DT01ACA050 500GB         | 5        | 0.39%   |
| SanDisk SSD PLUS 240GB           | 5        | 0.39%   |
| Samsung SSD 860 EVO mSATA 250GB  | 5        | 0.39%   |
| Samsung SSD 860 EVO 250GB        | 5        | 0.39%   |
| Samsung SSD 850 EVO 120GB        | 5        | 0.39%   |
| Samsung SSD 840 PRO Series 256GB | 5        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 82       | 151    | 32.54%  |
| Seagate             | 58       | 93     | 23.02%  |
| Toshiba             | 30       | 58     | 11.9%   |
| Hitachi             | 21       | 41     | 8.33%   |
| HGST                | 20       | 37     | 7.94%   |
| Samsung Electronics | 15       | 19     | 5.95%   |
| NVMe                | 6        | 7      | 2.38%   |
| OPENBSD             | 3        | 5      | 1.19%   |
| JetFlash            | 2        | 2      | 0.79%   |
| Hewlett-Packard     | 2        | 2      | 0.79%   |
| Fujitsu             | 2        | 2      | 0.79%   |
| WD MediaMax         | 1        | 2      | 0.4%    |
| Product:            | 1        | 1      | 0.4%    |
| Maxtor              | 1        | 1      | 0.4%    |
| LSI                 | 1        | 1      | 0.4%    |
| Intenso             | 1        | 1      | 0.4%    |
| IBM/Hitachi         | 1        | 1      | 0.4%    |
| IBM                 | 1        | 1      | 0.4%    |
| Generic             | 1        | 1      | 0.4%    |
| General             | 1        | 1      | 0.4%    |
| ASMT                | 1        | 1      | 0.4%    |
| Apple               | 1        | 1      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 146      | 235    | 17.24%  |
| Transcend           | 104      | 149    | 12.28%  |
| Kingston            | 76       | 127    | 8.97%   |
| SanDisk             | 70       | 101    | 8.26%   |
| Crucial             | 64       | 92     | 7.56%   |
| Intel               | 47       | 68     | 5.55%   |
| China               | 43       | 50     | 5.08%   |
| Phison              | 35       | 50     | 4.13%   |
| Hoodisk             | 29       | 51     | 3.42%   |
| Intenso             | 25       | 41     | 2.95%   |
| Innodisk            | 20       | 22     | 2.36%   |
| WDC                 | 14       | 15     | 1.65%   |
| A-DATA Technology   | 13       | 16     | 1.53%   |
| Toshiba             | 12       | 13     | 1.42%   |
| Micron Technology   | 11       | 22     | 1.3%    |
| FORESEE             | 11       | 15     | 1.3%    |
| OCZ                 | 10       | 14     | 1.18%   |
| Apacer              | 8        | 14     | 0.94%   |
| Protectli           | 6        | 8      | 0.71%   |
| Dogfish             | 6        | 7      | 0.71%   |
| ATP                 | 6        | 6      | 0.71%   |
| TCSUNBOW            | 5        | 6      | 0.59%   |
| SPCC                | 5        | 9      | 0.59%   |
| Patriot             | 5        | 7      | 0.59%   |
| NVMe                | 5        | 8      | 0.59%   |
| LITEONIT            | 5        | 6      | 0.59%   |
| Vaseky              | 4        | 4      | 0.47%   |
| ShiJi               | 4        | 5      | 0.47%   |
| KingDian            | 4        | 10     | 0.47%   |
| Verbatim            | 3        | 4      | 0.35%   |
| Team                | 3        | 3      | 0.35%   |
| Seagate             | 3        | 7      | 0.35%   |
| MEMXPRO             | 3        | 4      | 0.35%   |
| LITEON              | 3        | 3      | 0.35%   |
| Leven               | 3        | 5      | 0.35%   |
| KingSpec            | 3        | 3      | 0.35%   |
| Corsair             | 3        | 7      | 0.35%   |
| BORY                | 3        | 4      | 0.35%   |
| Advantech           | 3        | 5      | 0.35%   |
| SK hynix            | 2        | 2      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 782      | 1244   | 69.39%  |
| HDD  | 204      | 429    | 18.1%   |
| NVMe | 141      | 222    | 12.51%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 903      | 1673   | 86.49%  |
| NVMe | 141      | 222    | 13.51%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 827      | 1292   | 81.56%  |
| 0.51-1.0        | 97       | 158    | 9.57%   |
| 1.01-2.0        | 42       | 104    | 4.14%   |
| 3.01-4.0        | 20       | 51     | 1.97%   |
| 2.01-3.0        | 12       | 33     | 1.18%   |
| 4.01-10.0       | 12       | 23     | 1.18%   |
| 10.01-20.0      | 3        | 11     | 0.3%    |
| More than 100.0 | 1        | 1      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 464      | 41.95%  |
| 1-20           | 160      | 14.47%  |
| 251-500        | 145      | 13.11%  |
| 21-50          | 134      | 12.12%  |
| 51-100         | 118      | 10.67%  |
| 501-1000       | 52       | 4.7%    |
| More than 3000 | 11       | 0.99%   |
| 1001-2000      | 11       | 0.99%   |
| 2001-3000      | 6        | 0.54%   |
| Unknown        | 5        | 0.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1028     | 92.28%  |
| 21-50          | 48       | 4.31%   |
| 51-100         | 12       | 1.08%   |
| 101-250        | 6        | 0.54%   |
| Unknown        | 5        | 0.45%   |
| 251-500        | 4        | 0.36%   |
| 1001-2000      | 4        | 0.36%   |
| 501-1000       | 3        | 0.27%   |
| More than 3000 | 2        | 0.18%   |
| 2001-3000      | 2        | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| Kingston SV300S37A60G 64GB                   | 4        | 6      | 3.96%   |
| WDC WD2000FYYZ-01UL1B2 2TB                   | 3        | 5      | 2.97%   |
| Kingston SMS200S360G 64GB                    | 3        | 3      | 2.97%   |
| WDC WDS240G2G0A-00JH30 240GB                 | 2        | 3      | 1.98%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 2        | 7      | 1.98%   |
| WDC WD2000FYYZ-01UL1B1 2TB                   | 2        | 4      | 1.98%   |
| WDC WD1600AAJS-75M0A0 160GB                  | 2        | 2      | 1.98%   |
| Toshiba THNSNK128GCS8 SATA 128GB             | 2        | 2      | 1.98%   |
| Seagate ST3160318AS 160GB                    | 2        | 2      | 1.98%   |
| Seagate ST1000DX001-1CM162 1TB               | 2        | 2      | 1.98%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 2        | 4      | 1.98%   |
| Samsung Electronics HD501LJ 500GB            | 2        | 2      | 1.98%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB   | 2        | 4      | 1.98%   |
| Kingston SMS200S3120G 120GB                  | 2        | 3      | 1.98%   |
| Intenso SSD SATAIII 120GB                    | 2        | 2      | 1.98%   |
| Intel SSDSC2CT120A3 120GB                    | 2        | 2      | 1.98%   |
| HGST HTS541010A7E630 1TB                     | 2        | 4      | 1.98%   |
| Crucial CT275MX300SSD1 275GB                 | 2        | 2      | 1.98%   |
| WDC WD60EFRX-68TGBN1 6TB                     | 1        | 3      | 0.99%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1        | 1      | 0.99%   |
| WDC WD2503ABYX-01WERA0 256GB                 | 1        | 2      | 0.99%   |
| WDC WD1600AAJS-08L7A0 160GB                  | 1        | 1      | 0.99%   |
| WDC WD1600AABS-00PRA0 160GB                  | 1        | 1      | 0.99%   |
| WDC WD10EZEX-60WN4A0 1TB                     | 1        | 1      | 0.99%   |
| WDC WD10EAVS-00D7B0 1TB                      | 1        | 1      | 0.99%   |
| WDC WD10EACS-00D6B1 1TB                      | 1        | 2      | 0.99%   |
| Toshiba MQ02ABD100H 1TB                      | 1        | 4      | 0.99%   |
| SPCC M.2 PCIe SSD 256GB                      | 1        | 1      | 0.99%   |
| SMI SSD DISK 120GB                           | 1        | 1      | 0.99%   |
| Seagate ST9500620NS 500GB                    | 1        | 1      | 0.99%   |
| Seagate ST9320325AS 320GB                    | 1        | 1      | 0.99%   |
| Seagate ST9250827AS 250GB                    | 1        | 2      | 0.99%   |
| Seagate ST9160310AS 160GB                    | 1        | 2      | 0.99%   |
| Seagate ST500DM002-1BD142 496GB              | 1        | 2      | 0.99%   |
| Seagate ST4000NM0033-9ZM170 4TB              | 1        | 2      | 0.99%   |
| Seagate ST4000DM004-2CV104 4TB               | 1        | 1      | 0.99%   |
| Seagate ST380013AS 80GB                      | 1        | 1      | 0.99%   |
| Seagate ST3250410AS 250GB                    | 1        | 1      | 0.99%   |
| Seagate ST3250310NS 250GB                    | 1        | 2      | 0.99%   |
| Seagate ST320LT007-9ZV142 320GB              | 1        | 1      | 0.99%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 19       | 33     | 19%     |
| Seagate             | 18       | 24     | 18%     |
| Samsung Electronics | 11       | 14     | 11%     |
| Kingston            | 10       | 14     | 10%     |
| Intel               | 9        | 10     | 9%      |
| Crucial             | 7        | 17     | 7%      |
| HGST                | 4        | 6      | 4%      |
| Toshiba             | 3        | 6      | 3%      |
| Micron Technology   | 3        | 5      | 3%      |
| Hitachi             | 3        | 3      | 3%      |
| OCZ                 | 2        | 2      | 2%      |
| Intenso             | 2        | 2      | 2%      |
| SPCC                | 1        | 1      | 1%      |
| SMI                 | 1        | 1      | 1%      |
| SanDisk             | 1        | 2      | 1%      |
| Maxtor              | 1        | 1      | 1%      |
| KingSpec            | 1        | 1      | 1%      |
| KingDian            | 1        | 3      | 1%      |
| Corsair             | 1        | 3      | 1%      |
| Apacer              | 1        | 1      | 1%      |
| A-DATA Technology   | 1        | 2      | 1%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 24     | 37.5%   |
| WDC                 | 17       | 30     | 35.42%  |
| Samsung Electronics | 4        | 5      | 8.33%   |
| HGST                | 4        | 6      | 8.33%   |
| Hitachi             | 3        | 3      | 6.25%   |
| Toshiba             | 1        | 4      | 2.08%   |
| Maxtor              | 1        | 1      | 2.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 50       | 76     | 51.02%  |
| HDD  | 46       | 73     | 46.94%  |
| NVMe | 2        | 2      | 2.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD3200BPVT-16JJ5T0 320GB      | 1        | 1      | 25%     |
| Transcend TS32GSSD370S 32GB       | 1        | 2      | 25%     |
| Samsung Electronics SSD 980 250GB | 1        | 2      | 25%     |
| Kingston SV300S37A60G 64GB        | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 25%     |
| Transcend           | 1        | 2      | 25%     |
| Samsung Electronics | 1        | 2      | 25%     |
| Kingston            | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 927      | 1685   | 87.54%  |
| Malfunc  | 96       | 151    | 9.07%   |
| Detected | 32       | 53     | 3.02%   |
| Failed   | 4        | 6      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 754      | 59.09%  |
| AMD                            | 298      | 23.35%  |
| Samsung Electronics            | 45       | 3.53%   |
| Kingston Technology Company    | 24       | 1.88%   |
| ASMedia Technology             | 24       | 1.88%   |
| SanDisk                        | 23       | 1.8%    |
| Phison Electronics             | 17       | 1.33%   |
| Silicon Motion                 | 9        | 0.71%   |
| Marvell Technology Group       | 9        | 0.71%   |
| Broadcom / LSI                 | 9        | 0.71%   |
| Micron/Crucial Technology      | 8        | 0.63%   |
| MAXIO Technology (Hangzhou)    | 6        | 0.47%   |
| KIOXIA                         | 6        | 0.47%   |
| VIA Technologies               | 5        | 0.39%   |
| JMicron Technology             | 4        | 0.31%   |
| Toshiba                        | 3        | 0.24%   |
| SK hynix                       | 3        | 0.24%   |
| Silicon Image                  | 3        | 0.24%   |
| Shenzhen Longsys Electronics   | 3        | 0.24%   |
| Nvidia                         | 3        | 0.24%   |
| Micron Technology              | 3        | 0.24%   |
| Hewlett-Packard                | 3        | 0.24%   |
| Yangtze Memory Technologies    | 2        | 0.16%   |
| Realtek Semiconductor          | 2        | 0.16%   |
| Adaptec                        | 2        | 0.16%   |
| ULi Electronics                | 1        | 0.08%   |
| Solid State Storage Technology | 1        | 0.08%   |
| Seagate Technology             | 1        | 0.08%   |
| Integrated Technology Express  | 1        | 0.08%   |
| Enmotus                        | 1        | 0.08%   |
| Artop Electronic               | 1        | 0.08%   |
| 3ware                          | 1        | 0.08%   |
| Unknown                        | 1        | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 194      | 13.35%  |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 79       | 5.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 69       | 4.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 50       | 3.44%   |
| AMD FCH SATA Controller [IDE mode]                                               | 50       | 3.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 45       | 3.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 41       | 2.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 41       | 2.82%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 39       | 2.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 38       | 2.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 32       | 2.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 29       | 2%      |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 28       | 1.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 27       | 1.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 26       | 1.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 22       | 1.51%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 22       | 1.51%   |
| AMD 400 Series Chipset SATA Controller                                           | 21       | 1.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 20       | 1.38%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 20       | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 17       | 1.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 17       | 1.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 17       | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 17       | 1.17%   |
| Intel Comet Lake SATA AHCI Controller                                            | 14       | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 14       | 0.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14       | 0.96%   |
| Intel SATA Controller [RAID mode]                                                | 13       | 0.89%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 13       | 0.89%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 11       | 0.76%   |
| Phison PS5013 E13 NVMe Controller                                                | 10       | 0.69%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 10       | 0.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10       | 0.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10       | 0.69%   |
| Kingston Company A2000 NVMe SSD                                                  | 9        | 0.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9        | 0.62%   |
| Intel Tiger Lake-LP SATA Controller                                              | 9        | 0.62%   |
| Intel Elkhart Lake SATA AHCI                                                     | 9        | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 8        | 0.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 8        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 917      | 70.87%  |
| NVMe | 162      | 12.52%  |
| IDE  | 160      | 12.36%  |
| RAID | 43       | 3.32%   |
| SCSI | 7        | 0.54%   |
| SAS  | 5        | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 768      | 71.11%  |
| AMD    | 303      | 28.06%  |
| ARM    | 6        | 0.56%   |
| VIA    | 2        | 0.19%   |
| Sun    | 1        | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| AMD GX-412TC SOC                          | 104      | 9.57%   |
| Intel Celeron J4125 CPU @ 2.00GHz         | 52       | 4.78%   |
| Intel Celeron N5105 @ 2.00GHz             | 35       | 3.22%   |
| AMD GX-415GA SOC with Radeon HD Graphics  | 29       | 2.67%   |
| Intel Celeron CPU J1900 @ 1.99GHz         | 25       | 2.3%    |
| Intel Celeron CPU J3160 @ 1.60GHz         | 23       | 2.12%   |
| AMD GX-222GC SOC with Radeon R5E Graphics | 19       | 1.75%   |
| Intel Atom CPU D525 @ 1.80GHz             | 16       | 1.47%   |
| Intel Core i5-6500 CPU @ 3.20GHz          | 13       | 1.2%    |
| AMD G-T40E Processor                      | 13       | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz         | 12       | 1.1%    |
| Intel Core i7-7500U CPU @ 2.70GHz         | 11       | 1.01%   |
| Intel Celeron J4105 CPU @ 1.50GHz         | 11       | 1.01%   |
| Intel Celeron CPU J3455 @ 1.50GHz         | 10       | 0.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz          | 9        | 0.83%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz        | 9        | 0.83%   |
| Intel Celeron CPU N3150 @ 1.60GHz         | 9        | 0.83%   |
| Intel Core i5-8365U CPU @ 1.60GHz         | 8        | 0.74%   |
| Intel Celeron J4115 CPU @ 1.80GHz         | 8        | 0.74%   |
| AMD GX-420CA SOC with Radeon HD Graphics  | 8        | 0.74%   |
| Intel Core i7-7700 CPU @ 3.60GHz          | 7        | 0.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz         | 7        | 0.64%   |
| Intel Core i3-7100U CPU @ 2.40GHz         | 7        | 0.64%   |
| Intel Celeron J6412 @ 2.00GHz             | 7        | 0.64%   |
| Intel Atom CPU C3558 @ 2.20GHz            | 7        | 0.64%   |
| AMD GX-424CC SOC with Radeon R5E Graphics | 7        | 0.64%   |
| Intel Celeron CPU 3865U @ 1.80GHz         | 6        | 0.55%   |
| Intel Atom CPU E3845 @ 1.91GHz            | 6        | 0.55%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz   | 6        | 0.55%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz       | 5        | 0.46%   |
| Intel Pentium Silver N6005 @ 2.00GHz      | 5        | 0.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz         | 5        | 0.46%   |
| Intel Core i7-4770 CPU @ 3.40GHz          | 5        | 0.46%   |
| Intel Core i7-3770 CPU @ 3.40GHz          | 5        | 0.46%   |
| Intel Core i5-8265U CPU @ 1.60GHz         | 5        | 0.46%   |
| Intel Core i5-6500T CPU @ 2.50GHz         | 5        | 0.46%   |
| Intel Core i5-6200U CPU @ 2.30GHz         | 5        | 0.46%   |
| Intel Core i3-6100 CPU @ 3.70GHz          | 5        | 0.46%   |
| Intel Core i3-4160 CPU @ 3.60GHz          | 5        | 0.46%   |
| Intel Core i3-4130 CPU @ 3.40GHz          | 5        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 245      | 22.56%  |
| AMD GX                  | 175      | 16.11%  |
| Intel Core i5           | 168      | 15.47%  |
| Intel Core i3           | 86       | 7.92%   |
| Intel Core i7           | 69       | 6.35%   |
| Intel Xeon              | 66       | 6.08%   |
| Intel Atom              | 55       | 5.06%   |
| Other                   | 30       | 2.76%   |
| AMD Ryzen 7             | 25       | 2.3%    |
| AMD Ryzen 5             | 20       | 1.84%   |
| AMD G                   | 18       | 1.66%   |
| AMD FX                  | 15       | 1.38%   |
| Intel Pentium Silver    | 13       | 1.2%    |
| Intel Pentium           | 13       | 1.2%    |
| Intel Core 2 Quad       | 10       | 0.92%   |
| Intel Pentium Dual-Core | 6        | 0.55%   |
| Intel Core 2 Duo        | 6        | 0.55%   |
| AMD Ryzen 5 PRO         | 6        | 0.55%   |
| Intel Pentium Gold      | 5        | 0.46%   |
| AMD Ryzen 9             | 5        | 0.46%   |
| AMD Ryzen 3             | 5        | 0.46%   |
| ARM Cortex              | 4        | 0.37%   |
| AMD E                   | 4        | 0.37%   |
| Intel Core i9           | 3        | 0.28%   |
| AMD Turion II Neo       | 3        | 0.28%   |
| AMD Ryzen Embedded      | 3        | 0.28%   |
| AMD Athlon 64 X2        | 3        | 0.28%   |
| AMD Athlon              | 3        | 0.28%   |
| AMD A10                 | 3        | 0.28%   |
| AMD Ryzen Threadripper  | 2        | 0.18%   |
| AMD Ryzen 7 PRO         | 2        | 0.18%   |
| AMD Athlon Dual Core    | 2        | 0.18%   |
| AMD A8                  | 2        | 0.18%   |
| AMD A4                  | 2        | 0.18%   |
| Intel Xeon Gold         | 1        | 0.09%   |
| Intel Pentium Dual      | 1        | 0.09%   |
| Intel Pentium 4         | 1        | 0.09%   |
| Intel Core 2            | 1        | 0.09%   |
| AMD Phenom II X4        | 1        | 0.09%   |
| AMD Opteron             | 1        | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 632      | 58.2%   |
| 2       | 285      | 26.24%  |
| 6       | 41       | 3.78%   |
| 8       | 40       | 3.68%   |
| 16      | 31       | 2.85%   |
| Unknown | 23       | 2.12%   |
| 12      | 18       | 1.66%   |
| 1       | 9        | 0.83%   |
| 32      | 5        | 0.46%   |
| 36      | 1        | 0.09%   |
| 10      | 1        | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1056     | 97.96%  |
| 2       | 11       | 1.02%   |
| Unknown | 11       | 1.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 737      | 68.3%   |
| 2       | 318      | 29.47%  |
| Unknown | 24       | 2.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 139      | 12.81%  |
| Puma          | 134      | 12.35%  |
| Silvermont    | 83       | 7.65%   |
| Unknown       | 81       | 7.47%   |
| Goldmont plus | 80       | 7.37%   |
| Haswell       | 76       | 7%      |
| Skylake       | 59       | 5.44%   |
| IvyBridge     | 57       | 5.25%   |
| Jaguar        | 44       | 4.06%   |
| Bonnell       | 35       | 3.23%   |
| Goldmont      | 30       | 2.76%   |
| SandyBridge   | 27       | 2.49%   |
| Penryn        | 27       | 2.49%   |
| Bobcat        | 22       | 2.03%   |
| Zen+          | 20       | 1.84%   |
| Zen 2         | 20       | 1.84%   |
| Zen           | 19       | 1.75%   |
| CometLake     | 17       | 1.57%   |
| Piledriver    | 15       | 1.38%   |
| Core          | 14       | 1.29%   |
| Westmere      | 12       | 1.11%   |
| Broadwell     | 12       | 1.11%   |
| TigerLake     | 11       | 1.01%   |
| Nehalem       | 11       | 1.01%   |
| Zen 3         | 10       | 0.92%   |
| IceLake       | 9        | 0.83%   |
| K8 Hammer     | 6        | 0.55%   |
| K10           | 5        | 0.46%   |
| Bulldozer     | 4        | 0.37%   |
| Excavator     | 2        | 0.18%   |
| Steamroller   | 1        | 0.09%   |
| NetBurst      | 1        | 0.09%   |
| K10 Llano     | 1        | 0.09%   |
| Geode         | 1        | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 642      | 68.52%  |
| AMD                                          | 159      | 16.97%  |
| Nvidia                                       | 76       | 8.11%   |
| ASPEED Technology                            | 33       | 3.52%   |
| Matrox Electronics Systems                   | 24       | 2.56%   |
| VIA Technologies                             | 2        | 0.21%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                      | 73       | 7.71%   |
| Intel JasperLake [UHD Graphics]                                                          | 45       | 4.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 42       | 4.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 40       | 4.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 34       | 3.59%   |
| Intel HD Graphics 620                                                                    | 33       | 3.48%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 33       | 3.48%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 29       | 3.06%   |
| Intel HD Graphics 530                                                                    | 27       | 2.85%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 26       | 2.75%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 22       | 2.32%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 21       | 2.22%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 21       | 2.22%   |
| Intel HD Graphics 500                                                                    | 19       | 2.01%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 17       | 1.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17       | 1.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15       | 1.58%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 13       | 1.37%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 13       | 1.37%   |
| Intel UHD Graphics 620                                                                   | 12       | 1.27%   |
| Intel HD Graphics 630                                                                    | 12       | 1.27%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 10       | 1.06%   |
| Matrox Electronics Systems MGA G200EH                                                    | 10       | 1.06%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10       | 1.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10       | 1.06%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 9        | 0.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9        | 0.95%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9        | 0.95%   |
| Intel HD Graphics 610                                                                    | 9        | 0.95%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 9        | 0.95%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9        | 0.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9        | 0.95%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9        | 0.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8        | 0.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8        | 0.84%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 8        | 0.84%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 7        | 0.74%   |
| Intel HD Graphics 5500                                                                   | 7        | 0.74%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 7        | 0.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7        | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 602      | 55.69%  |
| 1 x AMD        | 157      | 14.52%  |
| Other          | 156      | 14.43%  |
| 1 x Nvidia     | 68       | 6.29%   |
| 1 x ASPEED     | 31       | 2.87%   |
| 2 x Intel      | 28       | 2.59%   |
| 1 x Matrox     | 23       | 2.13%   |
| Intel + Nvidia | 8        | 0.74%   |
| 1 x VIA        | 2        | 0.19%   |
| Intel + ASPEED | 2        | 0.19%   |
| 2 x AMD        | 1        | 0.09%   |
| 1 x XGI        | 1        | 0.09%   |
| Intel + Matrox | 1        | 0.09%   |
| Intel + AMD    | 1        | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 866      | 80.26%  |
| Unknown     | 163      | 15.11%  |
| Proprietary | 50       | 4.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1004     | 92.36%  |
| 1.01-2.0   | 28       | 2.58%   |
| 3.01-4.0   | 14       | 1.29%   |
| 0.01-0.5   | 11       | 1.01%   |
| 0.51-1.0   | 10       | 0.92%   |
| 7.01-8.0   | 8        | 0.74%   |
| 5.01-6.0   | 8        | 0.74%   |
| 2.01-3.0   | 4        | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 20       | 16.67%  |
| Goldstar             | 12       | 10%     |
| Dell                 | 12       | 10%     |
| BenQ                 | 10       | 8.33%   |
| Acer                 | 10       | 8.33%   |
| Hewlett-Packard      | 7        | 5.83%   |
| Eizo                 | 7        | 5.83%   |
| Ancor Communications | 7        | 5.83%   |
| LG Electronics       | 6        | 5%      |
| Iiyama               | 5        | 4.17%   |
| NEC Computers        | 4        | 3.33%   |
| Philips              | 3        | 2.5%    |
| Idek Iiyama          | 3        | 2.5%    |
| HannStar             | 2        | 1.67%   |
| Fujitsu Siemens      | 2        | 1.67%   |
| ASUSTek Computer     | 2        | 1.67%   |
| AOC                  | 2        | 1.67%   |
| WYT                  | 1        | 0.83%   |
| Mi                   | 1        | 0.83%   |
| LG Display           | 1        | 0.83%   |
| Lenovo               | 1        | 0.83%   |
| CHD                  | 1        | 0.83%   |
| Belinea              | 1        | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch            | 3        | 2.27%   |
| Samsung Electronics C32JG5x SAM0FDE 2560x1440 700x390mm 31.5-inch     | 2        | 1.52%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 540x350mm 25.3-inch         | 2        | 1.52%   |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 540x350mm 25.3-inch         | 2        | 1.52%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch          | 2        | 1.52%   |
| Goldstar E2441 GSM581F 1920x1080 530x300mm 24.0-inch                  | 2        | 1.52%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                     | 2        | 1.52%   |
| Dell LCD Monitor U2412M 3840x1200                                     | 2        | 1.52%   |
| Dell LCD Monitor U2412M                                               | 2        | 1.52%   |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                     | 2        | 1.52%   |
| BenQ GL2760 BNQ78D5 1920x1080 600x340mm 27.2-inch                     | 2        | 1.52%   |
| BenQ GL2450H BNQ78A6 1920x1080 530x300mm 24.0-inch                    | 2        | 1.52%   |
| Ancor Communications MX27AQ ACI27A5 2560x1440 600x340mm 27.2-inch     | 2        | 1.52%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                  | 1        | 0.76%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1        | 0.76%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM036C 1920x1200 550x340mm 25.5-inch  | 1        | 0.76%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 600x340mm 27.2-inch   | 1        | 0.76%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 520x320mm 24.0-inch   | 1        | 0.76%   |
| Samsung Electronics SAMTRON STN0028 1280x1024 380x300mm 19.1-inch     | 1        | 0.76%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 480x270mm 21.7-inch | 1        | 0.76%   |
| Samsung Electronics S24C650 SAM09E9 1920x1080 520x290mm 23.4-inch     | 1        | 0.76%   |
| Samsung Electronics S24C650 SAM09E8 1920x1080 520x290mm 23.4-inch     | 1        | 0.76%   |
| Samsung Electronics S24C650 SAM09E7 1920x1080 520x290mm 23.4-inch     | 1        | 0.76%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 480x270mm 21.7-inch     | 1        | 0.76%   |
| Samsung Electronics LCD Monitor T27C370 1920x1080                     | 1        | 0.76%   |
| Samsung Electronics LCD Monitor SMB2430L 1920x1080                    | 1        | 0.76%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 890x500mm 40.2-inch | 1        | 0.76%   |
| Samsung Electronics LCD Monitor S22C300 1920x1080                     | 1        | 0.76%   |
| Samsung Electronics LCD Monitor CF791 3440x1440                       | 1        | 0.76%   |
| Samsung Electronics CF791 SAM0DC3 3440x1440 800x330mm 34.1-inch       | 1        | 0.76%   |
| Samsung Electronics C27FG7x SAM0E42 1920x1080 600x340mm 27.2-inch     | 1        | 0.76%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 600x340mm 27.2-inch     | 1        | 0.76%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1        | 0.76%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch               | 1        | 0.76%   |
| Philips LCD Monitor PHL086D 1440x900 400x250mm 18.6-inch              | 1        | 0.76%   |
| Philips LCD Monitor PHL 243V7 3840x1080                               | 1        | 0.76%   |
| NEC Computers LCD1970NX NEC6662 1280x1024 380x300mm 19.1-inch         | 1        | 0.76%   |
| NEC Computers EX341R NEC2C7A 3440x1440 800x330mm 34.1-inch            | 1        | 0.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 50       | 41.32%  |
| 2560x1440 (QHD)    | 17       | 14.05%  |
| 3840x2160 (4K)     | 14       | 11.57%  |
| 1920x1200 (WUXGA)  | 13       | 10.74%  |
| 1280x1024 (SXGA)   | 7        | 5.79%   |
| 3440x1440          | 4        | 3.31%   |
| 1680x1050 (WSXGA+) | 4        | 3.31%   |
| Unknown            | 3        | 2.48%   |
| 3840x1200          | 2        | 1.65%   |
| 2560x1080          | 2        | 1.65%   |
| 1440x900 (WXGA+)   | 2        | 1.65%   |
| 3840x1080          | 1        | 0.83%   |
| 3600x1080          | 1        | 0.83%   |
| 1366x768 (WXGA)    | 1        | 0.83%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 29       | 24.17%  |
| 24      | 25       | 20.83%  |
| Unknown | 19       | 15.83%  |
| 23      | 11       | 9.17%   |
| 21      | 11       | 9.17%   |
| 19      | 5        | 4.17%   |
| 34      | 4        | 3.33%   |
| 22      | 4        | 3.33%   |
| 31      | 3        | 2.5%    |
| 25      | 3        | 2.5%    |
| 46      | 1        | 0.83%   |
| 32      | 1        | 0.83%   |
| 18      | 1        | 0.83%   |
| 17      | 1        | 0.83%   |
| 16      | 1        | 0.83%   |
| 13      | 1        | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 64       | 53.78%  |
| Unknown     | 19       | 15.97%  |
| 401-500     | 15       | 12.61%  |
| 601-700     | 7        | 5.88%   |
| 701-800     | 5        | 4.2%    |
| 351-400     | 5        | 4.2%    |
| 301-350     | 3        | 2.52%   |
| 1001-1500   | 1        | 0.84%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 70       | 59.83%  |
| Unknown | 18       | 15.38%  |
| 16/10   | 17       | 14.53%  |
| 5/4     | 5        | 4.27%   |
| 21/9    | 4        | 3.42%   |
| 3/2     | 2        | 1.71%   |
| 6/5     | 1        | 0.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 39       | 32.77%  |
| 301-350        | 29       | 24.37%  |
| Unknown        | 19       | 15.97%  |
| 251-300        | 14       | 11.76%  |
| 351-500        | 8        | 6.72%   |
| 151-200        | 6        | 5.04%   |
| 81-90          | 1        | 0.84%   |
| 141-150        | 1        | 0.84%   |
| 131-140        | 1        | 0.84%   |
| 501-1000       | 1        | 0.84%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 65       | 54.17%  |
| 101-120 | 23       | 19.17%  |
| Unknown | 19       | 15.83%  |
| 161-240 | 7        | 5.83%   |
| 121-160 | 5        | 4.17%   |
| 1-50    | 1        | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 960      | 88.81%  |
| 1     | 108      | 9.99%   |
| 2     | 12       | 1.11%   |
| 3     | 1        | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 863      | 60.27%  |
| Realtek Semiconductor             | 370      | 25.84%  |
| Qualcomm Atheros                  | 62       | 4.33%   |
| Broadcom                          | 45       | 3.14%   |
| IMC Networks                      | 13       | 0.91%   |
| Mellanox Technologies             | 8        | 0.56%   |
| American Megatrends               | 7        | 0.49%   |
| TP-Link                           | 6        | 0.42%   |
| D-Link System                     | 6        | 0.42%   |
| Marvell Technology Group          | 5        | 0.35%   |
| U-Blox                            | 4        | 0.28%   |
| Ralink                            | 4        | 0.28%   |
| MediaTek                          | 4        | 0.28%   |
| Edimax Technology                 | 4        | 0.28%   |
| Ralink Technology                 | 2        | 0.14%   |
| ICS Advent                        | 2        | 0.14%   |
| Emulex                            | 2        | 0.14%   |
| Dresden Elektronik                | 2        | 0.14%   |
| Aquantia                          | 2        | 0.14%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.07%   |
| Xiaomi                            | 1        | 0.07%   |
| T & A Mobile Phones               | 1        | 0.07%   |
| SysKonnect                        | 1        | 0.07%   |
| Standard Microsystems [SMC]       | 1        | 0.07%   |
| Samsung Electronics               | 1        | 0.07%   |
| Qualcomm Atheros Communications   | 1        | 0.07%   |
| QLogic                            | 1        | 0.07%   |
| Oculus VR                         | 1        | 0.07%   |
| NetXen Incorporated               | 1        | 0.07%   |
| Motorola                          | 1        | 0.07%   |
| Huawei Technologies               | 1        | 0.07%   |
| Ericsson Business Mobile Networks | 1        | 0.07%   |
| Digium                            | 1        | 0.07%   |
| Digital Equipment                 | 1        | 0.07%   |
| Dell                              | 1        | 0.07%   |
| Davicom Semiconductor             | 1        | 0.07%   |
| Chelsio Communications            | 1        | 0.07%   |
| AVM                               | 1        | 0.07%   |
| ASUSTek Computer                  | 1        | 0.07%   |
| Accton Technology                 | 1        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 323      | 19.03%  |
| Intel I211 Gigabit Network Connection                                         | 228      | 13.44%  |
| Intel I210 Gigabit Network Connection                                         | 135      | 7.96%   |
| Intel Ethernet Controller I225-V                                              | 77       | 4.54%   |
| Intel I350 Gigabit Network Connection                                         | 64       | 3.77%   |
| Intel 82574L Gigabit Network Connection                                       | 60       | 3.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 35       | 2.06%   |
| Intel 82580 Gigabit Network Connection                                        | 31       | 1.83%   |
| Intel Ethernet Controller I226-V                                              | 30       | 1.77%   |
| Intel 82576 Gigabit Network Connection                                        | 29       | 1.71%   |
| Realtek RTL8125 2.5GbE Controller                                             | 27       | 1.59%   |
| Intel 82583V Gigabit Network Connection                                       | 26       | 1.53%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 23       | 1.36%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 19       | 1.12%   |
| Intel Wi-Fi 6 AX200                                                           | 18       | 1.06%   |
| Intel Ethernet Connection (2) I219-V                                          | 18       | 1.06%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 17       | 1%      |
| Intel Ethernet Connection I217-LM                                             | 16       | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                                         | 14       | 0.82%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 12       | 0.71%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 11       | 0.65%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 11       | 0.65%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 10       | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 9        | 0.53%   |
| Intel Ethernet Controller X550                                                | 9        | 0.53%   |
| Intel Ethernet Connection (7) I219-V                                          | 9        | 0.53%   |
| Intel Centrino Advanced-N 6235                                                | 9        | 0.53%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 8        | 0.47%   |
| Intel Ethernet Connection X553 1GbE                                           | 8        | 0.47%   |
| Intel Ethernet Connection I219-LM                                             | 8        | 0.47%   |
| Intel Ethernet Connection I217-V                                              | 8        | 0.47%   |
| Intel 82579V Gigabit Network Connection                                       | 8        | 0.47%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 8        | 0.47%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 7        | 0.41%   |
| Intel Wireless-AC 9260                                                        | 7        | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                                         | 7        | 0.41%   |
| American Megatrends Virtual Ethernet                                          | 7        | 0.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 6        | 0.35%   |
| Intel Wireless 3160                                                           | 6        | 0.35%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 6        | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 78       | 36.45%  |
| Qualcomm Atheros                | 54       | 25.23%  |
| Realtek Semiconductor           | 36       | 16.82%  |
| IMC Networks                    | 13       | 6.07%   |
| Broadcom                        | 9        | 4.21%   |
| TP-Link                         | 6        | 2.8%    |
| Ralink                          | 4        | 1.87%   |
| MediaTek                        | 4        | 1.87%   |
| Edimax Technology               | 4        | 1.87%   |
| Ralink Technology               | 2        | 0.93%   |
| Qualcomm Atheros Communications | 1        | 0.47%   |
| Dell                            | 1        | 0.47%   |
| ASUSTek Computer                | 1        | 0.47%   |
| Accton Technology               | 1        | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 18       | 8.29%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 17       | 7.83%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 12       | 5.53%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 10       | 4.61%   |
| Intel Centrino Advanced-N 6235                                          | 9        | 4.15%   |
| Intel Wireless-AC 9260                                                  | 7        | 3.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 6        | 2.76%   |
| Intel Wireless 3160                                                     | 6        | 2.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5        | 2.3%    |
| Intel Wireless 7265                                                     | 5        | 2.3%    |
| Intel Wireless 7260                                                     | 5        | 2.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5        | 2.3%    |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter         | 4        | 1.84%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 3        | 1.38%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3        | 1.38%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 3        | 1.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3        | 1.38%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 3        | 1.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3        | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3        | 1.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3        | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3        | 1.38%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3        | 1.38%   |
| Intel Wireless 3165                                                     | 3        | 1.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3        | 1.38%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3        | 1.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2        | 0.92%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2        | 0.92%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2        | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2        | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2        | 0.92%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 2        | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2        | 0.92%   |
| Intel Wireless 8265 / 8275                                              | 2        | 0.92%   |
| Intel Wireless 8260                                                     | 2        | 0.92%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                | 2        | 0.92%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2        | 0.92%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2        | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 824      | 65.81%  |
| Realtek Semiconductor       | 355      | 28.35%  |
| Broadcom                    | 36       | 2.88%   |
| Qualcomm Atheros            | 8        | 0.64%   |
| American Megatrends         | 7        | 0.56%   |
| Marvell Technology Group    | 5        | 0.4%    |
| D-Link System               | 4        | 0.32%   |
| ICS Advent                  | 2        | 0.16%   |
| Aquantia                    | 2        | 0.16%   |
| Xiaomi                      | 1        | 0.08%   |
| T & A Mobile Phones         | 1        | 0.08%   |
| SysKonnect                  | 1        | 0.08%   |
| Standard Microsystems [SMC] | 1        | 0.08%   |
| Samsung Electronics         | 1        | 0.08%   |
| QLogic                      | 1        | 0.08%   |
| Emulex                      | 1        | 0.08%   |
| Digital Equipment           | 1        | 0.08%   |
| Davicom Semiconductor       | 1        | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 323      | 22.31%  |
| Intel I211 Gigabit Network Connection                                         | 228      | 15.75%  |
| Intel I210 Gigabit Network Connection                                         | 135      | 9.32%   |
| Intel Ethernet Controller I225-V                                              | 77       | 5.32%   |
| Intel I350 Gigabit Network Connection                                         | 64       | 4.42%   |
| Intel 82574L Gigabit Network Connection                                       | 60       | 4.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 35       | 2.42%   |
| Intel 82580 Gigabit Network Connection                                        | 31       | 2.14%   |
| Intel Ethernet Controller I226-V                                              | 30       | 2.07%   |
| Intel 82576 Gigabit Network Connection                                        | 29       | 2%      |
| Realtek RTL8125 2.5GbE Controller                                             | 26       | 1.8%    |
| Intel 82583V Gigabit Network Connection                                       | 26       | 1.8%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 23       | 1.59%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 19       | 1.31%   |
| Intel Ethernet Connection (2) I219-V                                          | 18       | 1.24%   |
| Intel Ethernet Connection I217-LM                                             | 16       | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                                         | 14       | 0.97%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 11       | 0.76%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 11       | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 9        | 0.62%   |
| Intel Ethernet Controller X550                                                | 9        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                                          | 9        | 0.62%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 8        | 0.55%   |
| Intel Ethernet Connection X553 1GbE                                           | 8        | 0.55%   |
| Intel Ethernet Connection I219-LM                                             | 8        | 0.55%   |
| Intel Ethernet Connection I217-V                                              | 8        | 0.55%   |
| Intel 82579V Gigabit Network Connection                                       | 8        | 0.55%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 8        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                                         | 7        | 0.48%   |
| American Megatrends Virtual Ethernet                                          | 7        | 0.48%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 6        | 0.41%   |
| Intel Ethernet Connection (14) I219-V                                         | 6        | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 5        | 0.35%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 5        | 0.35%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 5        | 0.35%   |
| Intel 82578DM Gigabit Network Connection                                      | 5        | 0.35%   |
| Intel 82575EB Gigabit Network Connection                                      | 5        | 0.35%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 4        | 0.28%   |
| Intel Ethernet Connection (12) I219-V                                         | 4        | 0.28%   |
| Intel 82576NS Gigabit Network Connection                                      | 4        | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1069     | 82.17%  |
| WiFi     | 202      | 15.53%  |
| Unknown  | 20       | 1.54%   |
| Modem    | 10       | 0.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1053     | 97.95%  |
| WiFi     | 21       | 1.95%   |
| Unknown  | 1        | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 242      | 22.06%  |
| 3     | 194      | 17.68%  |
| 2     | 168      | 15.31%  |
| 1     | 161      | 14.68%  |
| 6     | 142      | 12.94%  |
| 5     | 109      | 9.94%   |
| 8     | 23       | 2.1%    |
| 7     | 20       | 1.82%   |
| 10    | 14       | 1.28%   |
| 9     | 9        | 0.82%   |
| 0     | 8        | 0.73%   |
| 12    | 2        | 0.18%   |
| 11    | 2        | 0.18%   |
| 20    | 1        | 0.09%   |
| 17    | 1        | 0.09%   |
| 14    | 1        | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 871      | 76.88%  |
| Yes  | 262      | 23.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 70       | 61.95%  |
| Qualcomm Atheros Communications | 11       | 9.73%   |
| IMC Networks                    | 9        | 7.96%   |
| Realtek Semiconductor           | 6        | 5.31%   |
| ASUSTek Computer                | 5        | 4.42%   |
| Broadcom                        | 4        | 3.54%   |
| MediaTek                        | 3        | 2.65%   |
| Apple                           | 2        | 1.77%   |
| Micro Star International        | 1        | 0.88%   |
| Foxconn / Hon Hai               | 1        | 0.88%   |
| Cambridge Silicon Radio         | 1        | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 20       | 17.54%  |
| Intel AX200 Bluetooth                                       | 19       | 16.67%  |
| Intel Centrino Bluetooth Wireless Transceiver               | 11       | 9.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 7        | 6.14%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 6        | 5.26%   |
| Intel Wireless-AC 3168 Bluetooth                            | 5        | 4.39%   |
| Realtek Bluetooth Adapter                                   | 4        | 3.51%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 4        | 3.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4        | 3.51%   |
| MediaTek RZ608 Bluetooth Adapter                            | 3        | 2.63%   |
| Intel AX201 Bluetooth                                       | 3        | 2.63%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 2        | 1.75%   |
| Intel AX210 Bluetooth                                       | 2        | 1.75%   |
| Broadcom BCM2045 Bluetooth                                  | 2        | 1.75%   |
| ASUS USB-BT500                                              | 2        | 1.75%   |
| Realtek RTL8723A Bluetooth                                  | 1        | 0.88%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1        | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1        | 0.88%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1        | 0.88%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1        | 0.88%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1        | 0.88%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1        | 0.88%   |
| Micro Star International MS-6970 BToes Bluetooth adapter    | 1        | 0.88%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1        | 0.88%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                  | 1        | 0.88%   |
| IMC Networks Bluetooth                                      | 1        | 0.88%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1        | 0.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1        | 0.88%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1        | 0.88%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1        | 0.88%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                | 1        | 0.88%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 0.88%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE       | 1        | 0.88%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 0.88%   |
| Apple Bluetooth Host Controller                             | 1        | 0.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 558      | 64.96%  |
| AMD                                          | 183      | 21.3%   |
| Nvidia                                       | 68       | 7.92%   |
| C-Media Electronics                          | 12       | 1.4%    |
| Logitech                                     | 5        | 0.58%   |
| JMTek                                        | 4        | 0.47%   |
| VIA Technologies                             | 3        | 0.35%   |
| Tenx Technology                              | 3        | 0.35%   |
| Creative Labs                                | 3        | 0.35%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.23%   |
| Texas Instruments                            | 2        | 0.23%   |
| Kingston Technology                          | 2        | 0.23%   |
| GN Netcom                                    | 2        | 0.23%   |
| ZOOM                                         | 1        | 0.12%   |
| Yamaha                                       | 1        | 0.12%   |
| Trust                                        | 1        | 0.12%   |
| RME                                          | 1        | 0.12%   |
| Native Instruments                           | 1        | 0.12%   |
| M-Audio                                      | 1        | 0.12%   |
| Generalplus Technology                       | 1        | 0.12%   |
| Creative Technology                          | 1        | 0.12%   |
| Corsair                                      | 1        | 0.12%   |
| Blue Microphones                             | 1        | 0.12%   |
| AudioQuest                                   | 1        | 0.12%   |
| Audient                                      | 1        | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Kabini HDMI/DP Audio                                                                          | 68       | 6.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 67       | 6.59%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 56       | 5.51%   |
| AMD FCH Azalia Controller                                                                         | 51       | 5.02%   |
| Intel Jasper Lake HD Audio                                                                        | 45       | 4.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 41       | 4.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 35       | 3.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 35       | 3.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 29       | 2.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 28       | 2.76%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 25       | 2.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 22       | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 22       | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 21       | 2.07%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 20       | 1.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 19       | 1.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 18       | 1.77%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 18       | 1.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 18       | 1.77%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 17       | 1.67%   |
| Intel 200 Series PCH HD Audio                                                                     | 16       | 1.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 15       | 1.48%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13       | 1.28%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 12       | 1.18%   |
| Intel 8 Series HD Audio Controller                                                                | 12       | 1.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11       | 1.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11       | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10       | 0.98%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 9        | 0.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9        | 0.89%   |
| Intel Broadwell-U Audio Controller                                                                | 9        | 0.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9        | 0.89%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9        | 0.89%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9        | 0.89%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 8        | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7        | 0.69%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7        | 0.69%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 7        | 0.69%   |
| AMD Wrestler HDMI Audio                                                                           | 7        | 0.69%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 7        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Samsung Electronics        | 184      | 17.01%  |
| Unknown                    | 173      | 15.99%  |
| Crucial                    | 145      | 13.4%   |
| Kingston                   | 127      | 11.74%  |
| SK hynix                   | 93       | 8.6%    |
| Micron Technology          | 79       | 7.3%    |
| G.Skill                    | 72       | 6.65%   |
| Corsair                    | 46       | 4.25%   |
| Unknown                    | 33       | 3.05%   |
| Nanya Technology           | 16       | 1.48%   |
| ATP                        | 16       | 1.48%   |
| Unknown (ABCD)             | 13       | 1.2%    |
| A-DATA Technology          | 10       | 0.92%   |
| Transcend                  | 9        | 0.83%   |
| Ramaxel Technology         | 7        | 0.65%   |
| Apacer                     | 7        | 0.65%   |
| Kimtigo                    | 6        | 0.55%   |
| Hewlett-Packard            | 5        | 0.46%   |
| Shenzhen Jinge Information | 4        | 0.37%   |
| Patriot                    | 4        | 0.37%   |
| Avant                      | 3        | 0.28%   |
| Wodposit                   | 2        | 0.18%   |
| Unknown (09C7)             | 2        | 0.18%   |
| Teikon                     | 2        | 0.18%   |
| GeIL                       | 2        | 0.18%   |
| Vasekey                    | 1        | 0.09%   |
| Unknown (8A5D)             | 1        | 0.09%   |
| Unknown (8A02)             | 1        | 0.09%   |
| Unknown (7F7F7F94FFFFFFFF) | 1        | 0.09%   |
| Unknown (0x1636)           | 1        | 0.09%   |
| Unknown (0x0C26)           | 1        | 0.09%   |
| Timetec                    | 1        | 0.09%   |
| Tigo                       | 1        | 0.09%   |
| TakeMS                     | 1        | 0.09%   |
| SK_Hynix                   | 1        | 0.09%   |
| Qimonda                    | 1        | 0.09%   |
| PDPSystems                 | 1        | 0.09%   |
| Kingmax                    | 1        | 0.09%   |
| Innodisk                   | 1        | 0.09%   |
| Hyundai lnc                | 1        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 47       | 4.11%   |
| Unknown                                                        | 33       | 2.88%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 13       | 1.14%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 13       | 1.14%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 12       | 1.05%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 10       | 0.87%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 9        | 0.79%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s          | 9        | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 8        | 0.7%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s          | 8        | 0.7%    |
| ATP RAM X4G08QA8BNWESO-7-TO1 8GB SODIMM DDR4 3200MT/s          | 8        | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                     | 7        | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 7        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 7        | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 7        | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                     | 6        | 0.52%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 6        | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 6        | 0.52%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3200MT/s           | 6        | 0.52%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s            | 6        | 0.52%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s              | 6        | 0.52%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s          | 6        | 0.52%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 5        | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                     | 5        | 0.44%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 5        | 0.44%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 5        | 0.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 5        | 0.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 5        | 0.44%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 5        | 0.44%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s           | 5        | 0.44%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                 | 5        | 0.44%   |
| G.Skill RAM F4-2400C16-8GRS 8GB SODIMM DDR4 2400MT/s           | 5        | 0.44%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s          | 5        | 0.44%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s          | 5        | 0.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 4        | 0.35%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 4        | 0.35%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                       | 4        | 0.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 4        | 0.35%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                    | 4        | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 4        | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 443      | 44.66%  |
| DDR4    | 423      | 42.64%  |
| DDR2    | 41       | 4.13%   |
| Unknown | 28       | 2.82%   |
| LPDDR4  | 25       | 2.52%   |
| SDRAM   | 23       | 2.32%   |
| DDR     | 5        | 0.5%    |
| LPDDR5  | 2        | 0.2%    |
| DDR5    | 2        | 0.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 499      | 50.81%  |
| SODIMM       | 461      | 46.95%  |
| Row Of Chips | 14       | 1.43%   |
| Unknown      | 7        | 0.71%   |
| FB-DIMM      | 1        | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 386      | 37.04%  |
| 4096  | 354      | 33.97%  |
| 16384 | 141      | 13.53%  |
| 2048  | 117      | 11.23%  |
| 32768 | 25       | 2.4%    |
| 1024  | 17       | 1.63%   |
| 512   | 2        | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 265      | 25.75%  |
| 1333    | 153      | 14.87%  |
| 2400    | 150      | 14.58%  |
| 3200    | 117      | 11.37%  |
| 2667    | 115      | 11.18%  |
| 2133    | 46       | 4.47%   |
| 800     | 38       | 3.69%   |
| 667     | 32       | 3.11%   |
| Unknown | 24       | 2.33%   |
| 1867    | 16       | 1.55%   |
| 2666    | 14       | 1.36%   |
| 1066    | 13       | 1.26%   |
| 3000    | 9        | 0.87%   |
| 1866    | 9        | 0.87%   |
| 2933    | 6        | 0.58%   |
| 3600    | 5        | 0.49%   |
| 1334    | 3        | 0.29%   |
| 6400    | 2        | 0.19%   |
| 4800    | 2        | 0.19%   |
| 533     | 2        | 0.19%   |
| 333     | 2        | 0.19%   |
| 65535   | 1        | 0.1%    |
| 3534    | 1        | 0.1%    |
| 3500    | 1        | 0.1%    |
| 1419    | 1        | 0.1%    |
| 1067    | 1        | 0.1%    |
| 1033    | 1        | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 3        | 50%     |
| Ricoh               | 1        | 16.67%  |
| QinHeng Electronics | 1        | 16.67%  |
| Hewlett-Packard     | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Brother MFC-7360N             | 2        | 33.33%  |
| Ricoh SP 112                  | 1        | 16.67%  |
| QinHeng CH340S                | 1        | 16.67%  |
| HP HP LaserJet P2035 HP Print | 1        | 16.67%  |
| Brother HL-L2310D series      | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 2        | 66.67%  |
| Seiko Epson | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Desktops | Percent |
|-------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                             | 2        | 66.67%  |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 8        | 61.54%  |
| ARC International       | 2        | 15.38%  |
| Z-Star Microelectronics | 1        | 7.69%   |
| Trust                   | 1        | 7.69%   |
| Chicony Electronics     | 1        | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Logitech Webcam C270         | 2        | 15.38%  |
| Logitech C920 PRO HD Webcam  | 2        | 15.38%  |
| Logitech C920 HD Pro Webcam  | 2        | 15.38%  |
| ARC International Camera     | 2        | 15.38%  |
| Z-Star Venus USB2.0 Camera   | 1        | 7.69%   |
| Trust Trust USB Camera       | 1        | 7.69%   |
| Logitech HD Webcam C525      | 1        | 7.69%   |
| Logitech HD Pro Webcam C920  | 1        | 7.69%   |
| Chicony HP HD Webcam [Fixed] | 1        | 7.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 1        | 100%    |

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
| 1     | 514      | 46.6%   |
| 0     | 437      | 39.62%  |
| 2     | 97       | 8.79%   |
| 3     | 32       | 2.9%    |
| 4     | 13       | 1.18%   |
| 5     | 9        | 0.82%   |
| 6     | 1        | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 572      | 71.59%  |
| Net/wireless             | 72       | 9.01%   |
| Bluetooth                | 58       | 7.26%   |
| Card reader              | 33       | 4.13%   |
| Firewire controller      | 17       | 2.13%   |
| Net/ethernet             | 15       | 1.88%   |
| Network                  | 12       | 1.5%    |
| Sound                    | 9        | 1.13%   |
| Graphics card            | 4        | 0.5%    |
| Storage/raid             | 1        | 0.13%   |
| Storage/ide              | 1        | 0.13%   |
| Storage/ata              | 1        | 0.13%   |
| Storage                  | 1        | 0.13%   |
| Modem                    | 1        | 0.13%   |
| Fingerprint reader       | 1        | 0.13%   |
| Dvb card                 | 1        | 0.13%   |

