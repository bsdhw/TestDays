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

Total: 1387

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| Intel         | CRESCENTBAY                 | [b0ad128162](https://bsd-hardware.info/?probe=b0ad128162) | Sep 02, 2022 |
| Dell          | 0G261D A00                  | [c77b23d1a7](https://bsd-hardware.info/?probe=c77b23d1a7) | Aug 31, 2022 |
| Intel         | DENLOW_WS                   | [067a217959](https://bsd-hardware.info/?probe=067a217959) | Aug 30, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [df3df2855b](https://bsd-hardware.info/?probe=df3df2855b) | Aug 28, 2022 |
| ASUSTek       | PRIME X570-P                | [0f1eabf01e](https://bsd-hardware.info/?probe=0f1eabf01e) | Aug 27, 2022 |
| Intel         | CRESCENTBAY                 | [184a8697e9](https://bsd-hardware.info/?probe=184a8697e9) | Aug 27, 2022 |
| Intel         | CRESCENTBAY                 | [1765bd0426](https://bsd-hardware.info/?probe=1765bd0426) | Aug 27, 2022 |
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
| Intel         | CRESCENTBAY                 | [8f910e599b](https://bsd-hardware.info/?probe=8f910e599b) | Jul 21, 2022 |
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
| Intel         | CRESCENTBAY                 | [e7d923f138](https://bsd-hardware.info/?probe=e7d923f138) | Jul 07, 2022 |
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
| Intel         | CRESCENTBAY                 | [28928d9ad4](https://bsd-hardware.info/?probe=28928d9ad4) | Jun 28, 2022 |
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
| Intel         | CRESCENTBAY                 | [e4c8d6c787](https://bsd-hardware.info/?probe=e4c8d6c787) | May 01, 2022 |
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
| Unknown       | Unknown                     | [ad85192939](https://bsd-hardware.info/?probe=ad85192939) | Dec 27, 2021 |
| Advantech     | SYS-2USM02-6M01E            | [11ac580b34](https://bsd-hardware.info/?probe=11ac580b34) | Dec 25, 2021 |
| ASUSTek       | H81M-A                      | [2197e2ef44](https://bsd-hardware.info/?probe=2197e2ef44) | Dec 24, 2021 |
| Unknown       | J3160-4L                    | [e6a780468e](https://bsd-hardware.info/?probe=e6a780468e) | Dec 23, 2021 |
| Unknown       | MANIFOLD 2-C                | [1008aaa183](https://bsd-hardware.info/?probe=1008aaa183) | Dec 21, 2021 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [7e2700c4da](https://bsd-hardware.info/?probe=7e2700c4da) | Dec 19, 2021 |
| MSI           | G41M-P25                    | [841cce11e6](https://bsd-hardware.info/?probe=841cce11e6) | Dec 19, 2021 |
| PC Engines    | APU                         | [a80dfddf5d](https://bsd-hardware.info/?probe=a80dfddf5d) | Dec 19, 2021 |
| PC Engines    | APU                         | [062a321fcc](https://bsd-hardware.info/?probe=062a321fcc) | Dec 19, 2021 |
| Unknown       | Unknown                     | [a684bd3927](https://bsd-hardware.info/?probe=a684bd3927) | Dec 18, 2021 |
| Unknown       | MANIFOLD 2-C                | [2c117a5a05](https://bsd-hardware.info/?probe=2c117a5a05) | Dec 18, 2021 |
| Intel         | CRESCENTBAY                 | [9e0ffaee60](https://bsd-hardware.info/?probe=9e0ffaee60) | Dec 17, 2021 |
| Jetway        | 1.0                         | [da30ee0b65](https://bsd-hardware.info/?probe=da30ee0b65) | Dec 17, 2021 |
| HPE           | ProLiant MicroServer Gen... | [eb69483087](https://bsd-hardware.info/?probe=eb69483087) | Dec 17, 2021 |
| ASRock        | J5005-ITX                   | [8da08352a2](https://bsd-hardware.info/?probe=8da08352a2) | Dec 16, 2021 |
| PC Engines    | apu4                        | [3b69286939](https://bsd-hardware.info/?probe=3b69286939) | Dec 16, 2021 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [cd29b33f3b](https://bsd-hardware.info/?probe=cd29b33f3b) | Dec 15, 2021 |
| Unknown       | J3160-4L                    | [146a32975f](https://bsd-hardware.info/?probe=146a32975f) | Dec 14, 2021 |
| Unknown       | Unknown                     | [170ca711c2](https://bsd-hardware.info/?probe=170ca711c2) | Dec 12, 2021 |
| Protectli     | FW4B Ver                    | [88467fcb17](https://bsd-hardware.info/?probe=88467fcb17) | Dec 11, 2021 |
| CheckPoint    | T-120-00                    | [39b54429ed](https://bsd-hardware.info/?probe=39b54429ed) | Dec 11, 2021 |
| ASUSTek       | AT5NM10-I                   | [99395ceca8](https://bsd-hardware.info/?probe=99395ceca8) | Dec 10, 2021 |
| Acer          | RevoOne RL85                | [a1e32de7da](https://bsd-hardware.info/?probe=a1e32de7da) | Dec 10, 2021 |
| PC Engines    | APU2                        | [4f7fed5b1e](https://bsd-hardware.info/?probe=4f7fed5b1e) | Dec 09, 2021 |
| Unknown       | YL-J3160L4                  | [51a0e11a8e](https://bsd-hardware.info/?probe=51a0e11a8e) | Dec 09, 2021 |
| NU591         | 1.0                         | [4294dc97ee](https://bsd-hardware.info/?probe=4294dc97ee) | Dec 08, 2021 |
| PC Engines    | APU2                        | [dd0f74fd49](https://bsd-hardware.info/?probe=dd0f74fd49) | Dec 08, 2021 |
| Lex           | Pineview-D                  | [6cdb060f85](https://bsd-hardware.info/?probe=6cdb060f85) | Dec 08, 2021 |
| Unknown       | J3160-4L                    | [041d4640ec](https://bsd-hardware.info/?probe=041d4640ec) | Dec 08, 2021 |
| Intel         | D34010WYK H14771-304        | [49e201295e](https://bsd-hardware.info/?probe=49e201295e) | Dec 08, 2021 |
| Intel         | CRESCENTBAY                 | [320af631dc](https://bsd-hardware.info/?probe=320af631dc) | Dec 08, 2021 |
| Unknown       | MANIFOLD 2-C                | [0b875499eb](https://bsd-hardware.info/?probe=0b875499eb) | Dec 06, 2021 |
| MSI           | G41M-P25                    | [c123efb259](https://bsd-hardware.info/?probe=c123efb259) | Dec 06, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [35b01f0f56](https://bsd-hardware.info/?probe=35b01f0f56) | Dec 05, 2021 |
| PC Engines    | apu4                        | [044ab6e8f7](https://bsd-hardware.info/?probe=044ab6e8f7) | Dec 04, 2021 |
| PC Engines    | apu4                        | [b30e9d3491](https://bsd-hardware.info/?probe=b30e9d3491) | Dec 03, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [13491e4533](https://bsd-hardware.info/?probe=13491e4533) | Dec 03, 2021 |
| ASUSTek       | E45M1-I DELUXE              | [733cb90db6](https://bsd-hardware.info/?probe=733cb90db6) | Nov 30, 2021 |
| ASUSTek       | P10S-I Series               | [f9eb65c467](https://bsd-hardware.info/?probe=f9eb65c467) | Nov 30, 2021 |
| PC Engines    | APU2                        | [9d8179e835](https://bsd-hardware.info/?probe=9d8179e835) | Nov 30, 2021 |
| Shuttle       | DH370                       | [1bb8118acd](https://bsd-hardware.info/?probe=1bb8118acd) | Nov 29, 2021 |
| ASRock        | H570M-ITX/ac                | [015b50de55](https://bsd-hardware.info/?probe=015b50de55) | Nov 29, 2021 |
| ASRockRack    | X570D4I-2T                  | [7e937017e8](https://bsd-hardware.info/?probe=7e937017e8) | Nov 29, 2021 |
| HARDKERNEL    | ODROID-H2                   | [090f75c486](https://bsd-hardware.info/?probe=090f75c486) | Nov 28, 2021 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [d5adfcc6da](https://bsd-hardware.info/?probe=d5adfcc6da) | Nov 28, 2021 |
| PC Engines    | apu4                        | [ecf1eda1a7](https://bsd-hardware.info/?probe=ecf1eda1a7) | Nov 28, 2021 |
| PC Engines    | APU2                        | [93d5a9f80b](https://bsd-hardware.info/?probe=93d5a9f80b) | Nov 28, 2021 |
| HPE           | ProLiant MicroServer Gen... | [d4146fde77](https://bsd-hardware.info/?probe=d4146fde77) | Nov 27, 2021 |
| Unknown       | Unknown                     | [5b6fe36e9f](https://bsd-hardware.info/?probe=5b6fe36e9f) | Nov 27, 2021 |
| Fujitsu       | D3402-B2 S26361-D3402-B2    | [d7adca8cac](https://bsd-hardware.info/?probe=d7adca8cac) | Nov 27, 2021 |
| MSI           | MS-9899 11                  | [8fa11e9966](https://bsd-hardware.info/?probe=8fa11e9966) | Nov 27, 2021 |
| ASRock        | 775i945GZ                   | [16fc4ee10d](https://bsd-hardware.info/?probe=16fc4ee10d) | Nov 26, 2021 |
| Dell          | 0YNVJG A01                  | [d42bf7df26](https://bsd-hardware.info/?probe=d42bf7df26) | Nov 25, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [18fea5f65d](https://bsd-hardware.info/?probe=18fea5f65d) | Nov 24, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [6b5b37db47](https://bsd-hardware.info/?probe=6b5b37db47) | Nov 24, 2021 |
| Unknown       | YL-J1900L4-V2               | [62b059e980](https://bsd-hardware.info/?probe=62b059e980) | Nov 24, 2021 |
| Unknown       | Unknown                     | [47b9ef1995](https://bsd-hardware.info/?probe=47b9ef1995) | Nov 24, 2021 |
| Unknown       | Unknown                     | [8a14d605ba](https://bsd-hardware.info/?probe=8a14d605ba) | Nov 22, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [716ff29660](https://bsd-hardware.info/?probe=716ff29660) | Nov 21, 2021 |
| Supermicro    | X9SRE/X9SRE-3F/X9SRi/X9S... | [fe64c7bb21](https://bsd-hardware.info/?probe=fe64c7bb21) | Nov 21, 2021 |
| ASRockRack    | E3C246D4U2-2T               | [fd00b64a4c](https://bsd-hardware.info/?probe=fd00b64a4c) | Nov 21, 2021 |
| HP            | ProLiant MicroServer Gen... | [ce24594597](https://bsd-hardware.info/?probe=ce24594597) | Nov 21, 2021 |
| ASRock        | Z170 OC Formula             | [afc55af8dc](https://bsd-hardware.info/?probe=afc55af8dc) | Nov 20, 2021 |
| Unknown       | YL-J3160L4                  | [773774770a](https://bsd-hardware.info/?probe=773774770a) | Nov 20, 2021 |
| Fujitsu       | D3313-S3 S26361-D3313-S3    | [58befdd80b](https://bsd-hardware.info/?probe=58befdd80b) | Nov 19, 2021 |
| Hardkernel    | ODROID-H2                   | [dc97551c6f](https://bsd-hardware.info/?probe=dc97551c6f) | Nov 19, 2021 |
| Supermicro    | X7SPA-HF                    | [7263f34697](https://bsd-hardware.info/?probe=7263f34697) | Nov 19, 2021 |
| Fujitsu       | D3003-B1 S26361-D3003-B1    | [09480528a6](https://bsd-hardware.info/?probe=09480528a6) | Nov 17, 2021 |
| PC Engines    | apu4                        | [ec71343e71](https://bsd-hardware.info/?probe=ec71343e71) | Nov 17, 2021 |
| Dell          | 05YDCW A01                  | [435e4bef92](https://bsd-hardware.info/?probe=435e4bef92) | Nov 16, 2021 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a1b5a42cc1](https://bsd-hardware.info/?probe=a1b5a42cc1) | Nov 16, 2021 |
| Unknown       | Unknown                     | [e83cc2a4e7](https://bsd-hardware.info/?probe=e83cc2a4e7) | Nov 16, 2021 |
| Dell          | 0YNVJG A01                  | [1e96a8e633](https://bsd-hardware.info/?probe=1e96a8e633) | Nov 16, 2021 |
| Dell          | 05XGC8 A01                  | [4b1a5f0ab0](https://bsd-hardware.info/?probe=4b1a5f0ab0) | Nov 15, 2021 |
| PC Engines    | APU                         | [092ef089e7](https://bsd-hardware.info/?probe=092ef089e7) | Nov 14, 2021 |
| Lex           | Pineview-D                  | [ad05a6ff99](https://bsd-hardware.info/?probe=ad05a6ff99) | Nov 14, 2021 |
| HP            | 0A58h                       | [779ae4c4f5](https://bsd-hardware.info/?probe=779ae4c4f5) | Nov 13, 2021 |
| PC Engines    | APU2                        | [32a291cf82](https://bsd-hardware.info/?probe=32a291cf82) | Nov 13, 2021 |
| HARDKERNEL    | ODROID-H2                   | [9268d91d01](https://bsd-hardware.info/?probe=9268d91d01) | Nov 13, 2021 |
| Supermicro    | A2SDi-4C-HLN4F              | [4401dfa800](https://bsd-hardware.info/?probe=4401dfa800) | Nov 12, 2021 |
| NF841         | 1.0                         | [b1c784d41a](https://bsd-hardware.info/?probe=b1c784d41a) | Nov 11, 2021 |
| BESSTAR Te... | UM340 V1.0                  | [a14a31115f](https://bsd-hardware.info/?probe=a14a31115f) | Nov 10, 2021 |
| Shuttle       | DH470                       | [9db52efae6](https://bsd-hardware.info/?probe=9db52efae6) | Nov 09, 2021 |
| PC Engines    | APU2                        | [e02c6cd460](https://bsd-hardware.info/?probe=e02c6cd460) | Nov 09, 2021 |
| Intel         | CRESCENTBAY                 | [ad0e7916b8](https://bsd-hardware.info/?probe=ad0e7916b8) | Nov 09, 2021 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [27c22e7539](https://bsd-hardware.info/?probe=27c22e7539) | Nov 08, 2021 |
| Shuttle       | FH61R                       | [a231590743](https://bsd-hardware.info/?probe=a231590743) | Nov 07, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [7e27b1bc46](https://bsd-hardware.info/?probe=7e27b1bc46) | Nov 07, 2021 |
| MSI           | MS-9899 11                  | [87e3cf51e8](https://bsd-hardware.info/?probe=87e3cf51e8) | Nov 06, 2021 |
| Intel         | D2500CC AAG81477-400        | [d72502a707](https://bsd-hardware.info/?probe=d72502a707) | Nov 06, 2021 |
| Unknown       | Hardkernel ODROID-N2        | [42f6e357c9](https://bsd-hardware.info/?probe=42f6e357c9) | Nov 05, 2021 |
| ASRock        | H570M-ITX/ac                | [0eacc5ecb8](https://bsd-hardware.info/?probe=0eacc5ecb8) | Nov 05, 2021 |
| Shuttle       | XS35V3                      | [0d40b0f9eb](https://bsd-hardware.info/?probe=0d40b0f9eb) | Nov 05, 2021 |
| Dell          | 05XGC8 A01                  | [bec9a0c92f](https://bsd-hardware.info/?probe=bec9a0c92f) | Nov 03, 2021 |
| Acer          | Aspire X3990                | [3d2d538b68](https://bsd-hardware.info/?probe=3d2d538b68) | Nov 02, 2021 |
| Medion        | MS-7728                     | [5b5a847fdd](https://bsd-hardware.info/?probe=5b5a847fdd) | Nov 02, 2021 |
| Unknown       | J3160-4L                    | [b488be90bf](https://bsd-hardware.info/?probe=b488be90bf) | Nov 02, 2021 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [7539eb5fc7](https://bsd-hardware.info/?probe=7539eb5fc7) | Oct 31, 2021 |
| Unknown       | Unknown                     | [4ed65ba418](https://bsd-hardware.info/?probe=4ed65ba418) | Oct 30, 2021 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [feed581ab2](https://bsd-hardware.info/?probe=feed581ab2) | Oct 30, 2021 |
| Dell          | 0KC9NP A01                  | [d80d739506](https://bsd-hardware.info/?probe=d80d739506) | Oct 28, 2021 |
| BESSTAR Te... | IB9                         | [4f53f8feed](https://bsd-hardware.info/?probe=4f53f8feed) | Oct 28, 2021 |
| Unknown       | MANIFOLD 2-C                | [d2b7af2b7d](https://bsd-hardware.info/?probe=d2b7af2b7d) | Oct 27, 2021 |
| PC Engines    | APU2                        | [523db771da](https://bsd-hardware.info/?probe=523db771da) | Oct 26, 2021 |
| Unknown       | Unknown                     | [e0fdc6e80c](https://bsd-hardware.info/?probe=e0fdc6e80c) | Oct 26, 2021 |
| Beckhoff A... | CX51x0 G3                   | [6db720018b](https://bsd-hardware.info/?probe=6db720018b) | Oct 25, 2021 |
| Beckhoff A... | CX20x3 G1                   | [a49fbd5ce3](https://bsd-hardware.info/?probe=a49fbd5ce3) | Oct 25, 2021 |
| Gigabyte      | J1900N-D3V                  | [f004879c80](https://bsd-hardware.info/?probe=f004879c80) | Oct 24, 2021 |
| Acer          | Aspire X3990                | [5bb633147c](https://bsd-hardware.info/?probe=5bb633147c) | Oct 23, 2021 |
| Supermicro    | X8SIL                       | [51ab552166](https://bsd-hardware.info/?probe=51ab552166) | Oct 23, 2021 |
| ASRock        | 4X4-V1000                   | [dad41d7334](https://bsd-hardware.info/?probe=dad41d7334) | Oct 22, 2021 |
| HP            | 18E7                        | [bc3f111ee4](https://bsd-hardware.info/?probe=bc3f111ee4) | Oct 22, 2021 |
| Foxconn       | 45CS                        | [a6c12cc8dd](https://bsd-hardware.info/?probe=a6c12cc8dd) | Oct 20, 2021 |
| PC Engines    | APU                         | [e650814990](https://bsd-hardware.info/?probe=e650814990) | Oct 19, 2021 |
| Dell          | 05XGC8 A01                  | [8d7a4f8aec](https://bsd-hardware.info/?probe=8d7a4f8aec) | Oct 18, 2021 |
| Unknown       | YL-J1900L4-V2               | [160efd232c](https://bsd-hardware.info/?probe=160efd232c) | Oct 17, 2021 |
| AOpen         | i67QMx-DV R1.00TS2 55MP6... | [c5a904869c](https://bsd-hardware.info/?probe=c5a904869c) | Oct 16, 2021 |
| AOpen         | D1007 0BBB                  | [c774c3d39f](https://bsd-hardware.info/?probe=c774c3d39f) | Oct 15, 2021 |
| PC Engines    | APU                         | [92830ddc69](https://bsd-hardware.info/?probe=92830ddc69) | Oct 14, 2021 |
| ASRock        | X570 Pro4                   | [97ee657402](https://bsd-hardware.info/?probe=97ee657402) | Oct 11, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [f842095195](https://bsd-hardware.info/?probe=f842095195) | Oct 11, 2021 |
| ASRock        | A520M-ITX/ac                | [847d5b709c](https://bsd-hardware.info/?probe=847d5b709c) | Oct 10, 2021 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [8092d9074e](https://bsd-hardware.info/?probe=8092d9074e) | Oct 09, 2021 |
| Intel         | Q3XXG4-P V1.0               | [8919eb9ecf](https://bsd-hardware.info/?probe=8919eb9ecf) | Oct 08, 2021 |
| Unknown       | Unknown                     | [93783e754a](https://bsd-hardware.info/?probe=93783e754a) | Oct 08, 2021 |
| ASRock        | J4125B-ITX                  | [53fd304513](https://bsd-hardware.info/?probe=53fd304513) | Oct 07, 2021 |
| Supermicro    | X9SCI/X9SCA                 | [105614d0b7](https://bsd-hardware.info/?probe=105614d0b7) | Oct 07, 2021 |
| Unknown       | Unknown                     | [b20c94e68f](https://bsd-hardware.info/?probe=b20c94e68f) | Oct 06, 2021 |
| ASRock        | J4125B-ITX                  | [e70b3a12ce](https://bsd-hardware.info/?probe=e70b3a12ce) | Oct 06, 2021 |
| MSI           | 970A-G43                    | [5664e84f3c](https://bsd-hardware.info/?probe=5664e84f3c) | Oct 06, 2021 |
| HP            | 3397                        | [4c71aae5bf](https://bsd-hardware.info/?probe=4c71aae5bf) | Oct 05, 2021 |
| Fujitsu       | D3003-A1 S26361-D3003-A1    | [b70c576fc9](https://bsd-hardware.info/?probe=b70c576fc9) | Oct 05, 2021 |
| HP            | ProLiant ML350 G5           | [4d525cba3e](https://bsd-hardware.info/?probe=4d525cba3e) | Oct 03, 2021 |
| ASUSTek       | P7H55-M                     | [9b77e2fe70](https://bsd-hardware.info/?probe=9b77e2fe70) | Oct 01, 2021 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [8caa25b1e6](https://bsd-hardware.info/?probe=8caa25b1e6) | Sep 29, 2021 |
| PC Engines    | APU2                        | [f92f0d6794](https://bsd-hardware.info/?probe=f92f0d6794) | Sep 29, 2021 |
| Dell          | 06X1TJ A00                  | [ab93f4d860](https://bsd-hardware.info/?probe=ab93f4d860) | Sep 29, 2021 |
| PC Engines    | APU2                        | [8f5ae62d4f](https://bsd-hardware.info/?probe=8f5ae62d4f) | Sep 29, 2021 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [373aa0778c](https://bsd-hardware.info/?probe=373aa0778c) | Sep 28, 2021 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [b569bb4f32](https://bsd-hardware.info/?probe=b569bb4f32) | Sep 28, 2021 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [bd970d8539](https://bsd-hardware.info/?probe=bd970d8539) | Sep 26, 2021 |
| BESSTAR Te... | IB9                         | [123d566fcc](https://bsd-hardware.info/?probe=123d566fcc) | Sep 25, 2021 |
| BESSTAR Te... | IB9                         | [deaaf06879](https://bsd-hardware.info/?probe=deaaf06879) | Sep 25, 2021 |
| Unknown       | Unknown                     | [4041c95064](https://bsd-hardware.info/?probe=4041c95064) | Sep 25, 2021 |
| Deciso        | Netboard A10 GEN2 Model ... | [cd6d2f5d88](https://bsd-hardware.info/?probe=cd6d2f5d88) | Sep 25, 2021 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [b3c1bdf977](https://bsd-hardware.info/?probe=b3c1bdf977) | Sep 25, 2021 |
| Unknown       | Unknown                     | [4d1167c012](https://bsd-hardware.info/?probe=4d1167c012) | Sep 23, 2021 |
| Unknown       | YL-SKUL6                    | [830cab62b4](https://bsd-hardware.info/?probe=830cab62b4) | Sep 23, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [ec9df68353](https://bsd-hardware.info/?probe=ec9df68353) | Sep 23, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [e6402caa3b](https://bsd-hardware.info/?probe=e6402caa3b) | Sep 23, 2021 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [ee636f7116](https://bsd-hardware.info/?probe=ee636f7116) | Sep 23, 2021 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [6dd770e162](https://bsd-hardware.info/?probe=6dd770e162) | Sep 23, 2021 |
| AOpen         | i67QMx-DV R1.00TS2 55MP6... | [12840f112c](https://bsd-hardware.info/?probe=12840f112c) | Sep 22, 2021 |
| Unknown       | Unknown                     | [2535006bea](https://bsd-hardware.info/?probe=2535006bea) | Sep 22, 2021 |
| Unknown       | J3160-4L                    | [b523fa234d](https://bsd-hardware.info/?probe=b523fa234d) | Sep 21, 2021 |
| Unknown       | Unknown                     | [248019674c](https://bsd-hardware.info/?probe=248019674c) | Sep 21, 2021 |
| BESSTAR Te... | IB9                         | [b87b166f6b](https://bsd-hardware.info/?probe=b87b166f6b) | Sep 20, 2021 |
| Supermicro    | X7SLA                       | [ad69a62704](https://bsd-hardware.info/?probe=ad69a62704) | Sep 20, 2021 |
| Gigabyte      | J1900N-D3V                  | [cd6ce715f4](https://bsd-hardware.info/?probe=cd6ce715f4) | Sep 20, 2021 |
| Unknown       | Unknown                     | [1c60dcac9d](https://bsd-hardware.info/?probe=1c60dcac9d) | Sep 19, 2021 |
| Lex           | Pineview-D                  | [008639e137](https://bsd-hardware.info/?probe=008639e137) | Sep 19, 2021 |
| Gigabyte      | J1900N-D3V                  | [c194a7a0c3](https://bsd-hardware.info/?probe=c194a7a0c3) | Sep 18, 2021 |
| ASUSTek       | P11C-M Series               | [84501a5e10](https://bsd-hardware.info/?probe=84501a5e10) | Sep 18, 2021 |
| HP            | 1496                        | [9a37622638](https://bsd-hardware.info/?probe=9a37622638) | Sep 16, 2021 |
| PC Engines    | apu4                        | [536d7f4179](https://bsd-hardware.info/?probe=536d7f4179) | Sep 16, 2021 |
| Acer          | Aspire X3990                | [efa6b58597](https://bsd-hardware.info/?probe=efa6b58597) | Sep 15, 2021 |
| Intel         | DENLOW_REFRESH_WS           | [7244afab89](https://bsd-hardware.info/?probe=7244afab89) | Sep 15, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [8fff74c89c](https://bsd-hardware.info/?probe=8fff74c89c) | Sep 13, 2021 |
| PC Engines    | apu4                        | [a3210b9ccb](https://bsd-hardware.info/?probe=a3210b9ccb) | Sep 12, 2021 |
| ASUSTek       | PRIME B360M-C               | [0f6e7e26fc](https://bsd-hardware.info/?probe=0f6e7e26fc) | Sep 11, 2021 |
| MSI           | MS-7A34                     | [decfe43121](https://bsd-hardware.info/?probe=decfe43121) | Sep 10, 2021 |
| BESSTAR Te... | IB9                         | [47d18cf621](https://bsd-hardware.info/?probe=47d18cf621) | Sep 10, 2021 |
| PC Engines    | APU2                        | [0151df253f](https://bsd-hardware.info/?probe=0151df253f) | Sep 06, 2021 |
| Supermicro    | X8SIL                       | [57900cf5dd](https://bsd-hardware.info/?probe=57900cf5dd) | Sep 06, 2021 |
| HP            | 3397                        | [5d95b75768](https://bsd-hardware.info/?probe=5d95b75768) | Sep 06, 2021 |
| Dell          | 00F82W A00                  | [31a5a81a90](https://bsd-hardware.info/?probe=31a5a81a90) | Sep 04, 2021 |
| Gigabyte      | B75M-D3V                    | [c15a4ebbd5](https://bsd-hardware.info/?probe=c15a4ebbd5) | Sep 03, 2021 |
| Biostar       | B250MHC                     | [fd3bed8c81](https://bsd-hardware.info/?probe=fd3bed8c81) | Sep 02, 2021 |
| BESSTAR Te... | IB9                         | [40b84f8293](https://bsd-hardware.info/?probe=40b84f8293) | Sep 01, 2021 |
| AWOW Techo... | AK41                        | [3b77aba5a0](https://bsd-hardware.info/?probe=3b77aba5a0) | Aug 31, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [0ee3fe080c](https://bsd-hardware.info/?probe=0ee3fe080c) | Aug 30, 2021 |
| NF541         | 1.0                         | [14eb176b48](https://bsd-hardware.info/?probe=14eb176b48) | Aug 30, 2021 |
| Intel         | D2500CC AAG81477-400        | [7f8d2bb97c](https://bsd-hardware.info/?probe=7f8d2bb97c) | Aug 30, 2021 |
| Supermicro    | X8SIL                       | [680b0e9899](https://bsd-hardware.info/?probe=680b0e9899) | Aug 30, 2021 |
| Protectli     | FW6                         | [5372daa4af](https://bsd-hardware.info/?probe=5372daa4af) | Aug 29, 2021 |
| Gigabyte      | Z77M-D3H                    | [d60f1bc575](https://bsd-hardware.info/?probe=d60f1bc575) | Aug 29, 2021 |
| ASUSTek       | AT5NM10-I                   | [8adafbbd4c](https://bsd-hardware.info/?probe=8adafbbd4c) | Aug 28, 2021 |
| PC Engines    | APU2                        | [fe69045e72](https://bsd-hardware.info/?probe=fe69045e72) | Aug 27, 2021 |
| Medion        | MS-7616                     | [98f0e21e6c](https://bsd-hardware.info/?probe=98f0e21e6c) | Aug 26, 2021 |
| Medion        | MS-7616                     | [663b50102d](https://bsd-hardware.info/?probe=663b50102d) | Aug 26, 2021 |
| HP            | ProLiant MicroServer Gen... | [7de1659954](https://bsd-hardware.info/?probe=7de1659954) | Aug 26, 2021 |
| HP            | 8105                        | [e45f1e146b](https://bsd-hardware.info/?probe=e45f1e146b) | Aug 26, 2021 |
| Unknown       | Unknown                     | [474aaa7216](https://bsd-hardware.info/?probe=474aaa7216) | Aug 25, 2021 |
| Unknown       | YL-SKUL6                    | [7f51c2bc1c](https://bsd-hardware.info/?probe=7f51c2bc1c) | Aug 24, 2021 |
| PC Engines    | APU2                        | [79a4cc75ca](https://bsd-hardware.info/?probe=79a4cc75ca) | Aug 23, 2021 |
| Supermicro    | X11SDV-4C-TLN2F             | [fefc14abad](https://bsd-hardware.info/?probe=fefc14abad) | Aug 22, 2021 |
| HP            | ProLiant MicroServer Gen... | [76df8356a9](https://bsd-hardware.info/?probe=76df8356a9) | Aug 21, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [5bf55e14a4](https://bsd-hardware.info/?probe=5bf55e14a4) | Aug 21, 2021 |
| Unknown       | Unknown                     | [58e4c44013](https://bsd-hardware.info/?probe=58e4c44013) | Aug 21, 2021 |
| PC Engines    | apu4                        | [45b3fcec31](https://bsd-hardware.info/?probe=45b3fcec31) | Aug 20, 2021 |
| HP            | ProLiant MicroServer Gen... | [95d0463b85](https://bsd-hardware.info/?probe=95d0463b85) | Aug 20, 2021 |
| Yanling       | YL-KBRL2 Series Ver:1.02    | [32618f05a4](https://bsd-hardware.info/?probe=32618f05a4) | Aug 19, 2021 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [296225ee3d](https://bsd-hardware.info/?probe=296225ee3d) | Aug 19, 2021 |
| BESSTAR Te... | IB9                         | [9918bc1a9c](https://bsd-hardware.info/?probe=9918bc1a9c) | Aug 18, 2021 |
| Gigabyte      | MZBSWBP-00                  | [3083ea5251](https://bsd-hardware.info/?probe=3083ea5251) | Aug 18, 2021 |
| Shuttle       | FH87                        | [3898540e06](https://bsd-hardware.info/?probe=3898540e06) | Aug 17, 2021 |
| HP            | 158A                        | [e2c79dfa71](https://bsd-hardware.info/?probe=e2c79dfa71) | Aug 16, 2021 |
| Hardkernel    | ODROID-H2                   | [b06da7d742](https://bsd-hardware.info/?probe=b06da7d742) | Aug 15, 2021 |
| Gigabyte      | H97N-WIFI                   | [33f2b694c4](https://bsd-hardware.info/?probe=33f2b694c4) | Aug 14, 2021 |
| ASRock        | Q2900M                      | [04033ae838](https://bsd-hardware.info/?probe=04033ae838) | Aug 14, 2021 |
| ASUSTek       | AT5NM10-I                   | [27bc066fd6](https://bsd-hardware.info/?probe=27bc066fd6) | Aug 13, 2021 |
| PC Engines    | apu4                        | [bd8c2391bf](https://bsd-hardware.info/?probe=bd8c2391bf) | Aug 11, 2021 |
| Intel         | Q3XXG4-P V1.0               | [1b786e9896](https://bsd-hardware.info/?probe=1b786e9896) | Aug 09, 2021 |
| Protectli     | FW4B                        | [0888981f79](https://bsd-hardware.info/?probe=0888981f79) | Aug 09, 2021 |
| Intel         | DENLOW_REFRESH_WS           | [52e97cac72](https://bsd-hardware.info/?probe=52e97cac72) | Aug 09, 2021 |
| BESSTAR Te... | IB9                         | [f834dde818](https://bsd-hardware.info/?probe=f834dde818) | Aug 09, 2021 |
| BESSTAR Te... | IB9                         | [c78b8b64b2](https://bsd-hardware.info/?probe=c78b8b64b2) | Aug 09, 2021 |
| Unknown       | Unknown                     | [b7d5400099](https://bsd-hardware.info/?probe=b7d5400099) | Aug 08, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [1a89e4b6d7](https://bsd-hardware.info/?probe=1a89e4b6d7) | Aug 07, 2021 |
| PC Engines    | APU2                        | [1d41b9e323](https://bsd-hardware.info/?probe=1d41b9e323) | Aug 07, 2021 |
| NEXCOM        | NSA3110 B                   | [fe24a88c9a](https://bsd-hardware.info/?probe=fe24a88c9a) | Aug 06, 2021 |
| Unknown       | Unknown                     | [9ac4fdabae](https://bsd-hardware.info/?probe=9ac4fdabae) | Aug 05, 2021 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [c9e6972fca](https://bsd-hardware.info/?probe=c9e6972fca) | Aug 05, 2021 |
| PC Engines    | APU2                        | [beb4b79b2e](https://bsd-hardware.info/?probe=beb4b79b2e) | Aug 05, 2021 |
| Intel         | DH67BL AAG10189-211         | [bc165b5a3e](https://bsd-hardware.info/?probe=bc165b5a3e) | Aug 05, 2021 |
| NF541         | 1.0                         | [1b4b4e63f1](https://bsd-hardware.info/?probe=1b4b4e63f1) | Aug 05, 2021 |
| NF541         | 1.0                         | [e7162d7e5c](https://bsd-hardware.info/?probe=e7162d7e5c) | Aug 05, 2021 |
| NU941         | 1.0                         | [9115075fde](https://bsd-hardware.info/?probe=9115075fde) | Aug 03, 2021 |
| MSI           | MS-7418 100                 | [ff87e2d542](https://bsd-hardware.info/?probe=ff87e2d542) | Aug 02, 2021 |
| Unknown       | Unknown                     | [d3189294c9](https://bsd-hardware.info/?probe=d3189294c9) | Jul 31, 2021 |
| Unknown       | YL-J3160L4                  | [334b0cdfa0](https://bsd-hardware.info/?probe=334b0cdfa0) | Jul 29, 2021 |
| Intel         | Q3XXG4-P V1.0               | [5ebe973acb](https://bsd-hardware.info/?probe=5ebe973acb) | Jul 29, 2021 |
| ASUSTek       | E35M1-I DELUXE              | [4b5538272b](https://bsd-hardware.info/?probe=4b5538272b) | Jul 29, 2021 |
| Unknown       | Unknown                     | [ed24578084](https://bsd-hardware.info/?probe=ed24578084) | Jul 29, 2021 |
| ASRock        | H570M-ITX/ac                | [aa223b779b](https://bsd-hardware.info/?probe=aa223b779b) | Jul 28, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [66a84838ac](https://bsd-hardware.info/?probe=66a84838ac) | Jul 28, 2021 |
| Thomas-Kre... | LES network+                | [03ee17343d](https://bsd-hardware.info/?probe=03ee17343d) | Jul 25, 2021 |
| NEXCOM        | NSA3110 B                   | [49a54e3b3d](https://bsd-hardware.info/?probe=49a54e3b3d) | Jul 24, 2021 |
| Unknown       | Unknown                     | [6aa3325078](https://bsd-hardware.info/?probe=6aa3325078) | Jul 23, 2021 |
| MSI           | B85-G43                     | [80b435d1ab](https://bsd-hardware.info/?probe=80b435d1ab) | Jul 22, 2021 |
| PC Engines    | APU2                        | [b7a2fd6286](https://bsd-hardware.info/?probe=b7a2fd6286) | Jul 22, 2021 |
| ASUSTek       | B202                        | [9f5f0a4117](https://bsd-hardware.info/?probe=9f5f0a4117) | Jul 21, 2021 |
| ASUSTek       | P11C-M Series               | [9d193c1b29](https://bsd-hardware.info/?probe=9d193c1b29) | Jul 21, 2021 |
| ASUSTek       | P10S-I Series               | [4ea7a145d9](https://bsd-hardware.info/?probe=4ea7a145d9) | Jul 21, 2021 |
| ASUSTek       | AT5NM10-I                   | [9b451f0cd2](https://bsd-hardware.info/?probe=9b451f0cd2) | Jul 20, 2021 |
| Unknown       | PICO PC                     | [f3fc1a12b3](https://bsd-hardware.info/?probe=f3fc1a12b3) | Jul 19, 2021 |
| Unknown       | Unknown                     | [a73757a6ce](https://bsd-hardware.info/?probe=a73757a6ce) | Jul 14, 2021 |
| Unknown       | Unknown                     | [94844cb867](https://bsd-hardware.info/?probe=94844cb867) | Jul 14, 2021 |
| HP            | ProLiant MicroServer Gen... | [250fc347ce](https://bsd-hardware.info/?probe=250fc347ce) | Jul 11, 2021 |
| HP            | ProLiant MicroServer Gen... | [93b487fc6a](https://bsd-hardware.info/?probe=93b487fc6a) | Jul 11, 2021 |
| Unknown       | Unknown                     | [85b3c02f13](https://bsd-hardware.info/?probe=85b3c02f13) | Jul 10, 2021 |
| Protectli     | FW4B Ver                    | [5ac2faefa9](https://bsd-hardware.info/?probe=5ac2faefa9) | Jul 10, 2021 |
| HP            | 158A                        | [01d7f3bfd3](https://bsd-hardware.info/?probe=01d7f3bfd3) | Jul 10, 2021 |
| ASUSTek       | P11C-M Series               | [aa3c998220](https://bsd-hardware.info/?probe=aa3c998220) | Jul 08, 2021 |
| ASUSTek       | PRIME B560M-A               | [55f46bc85d](https://bsd-hardware.info/?probe=55f46bc85d) | Jul 07, 2021 |
| Dell          | 0GXM1W A02                  | [269edf2dcf](https://bsd-hardware.info/?probe=269edf2dcf) | Jul 06, 2021 |
| PC Engines    | apu4                        | [7d65193973](https://bsd-hardware.info/?probe=7d65193973) | Jul 06, 2021 |
| NF841         | 1.0                         | [f51815bfa0](https://bsd-hardware.info/?probe=f51815bfa0) | Jul 05, 2021 |
| ASUSTek       | P11C-E Series               | [205d6e0194](https://bsd-hardware.info/?probe=205d6e0194) | Jul 04, 2021 |
| Fujitsu       | D3431-A1 S26361-D3431-A1    | [2246af81d3](https://bsd-hardware.info/?probe=2246af81d3) | Jul 03, 2021 |
| PC Engines    | APU2                        | [c7011f8713](https://bsd-hardware.info/?probe=c7011f8713) | Jul 03, 2021 |
| Fujitsu       | D3431-A1 S26361-D3431-A1    | [5fd85312eb](https://bsd-hardware.info/?probe=5fd85312eb) | Jul 02, 2021 |
| Gigabyte      | B365M D3H-CF                | [5fa56e5e0f](https://bsd-hardware.info/?probe=5fa56e5e0f) | Jul 02, 2021 |
| Gigabyte      | B365M D3H-CF                | [cccc6e20dd](https://bsd-hardware.info/?probe=cccc6e20dd) | Jul 02, 2021 |
| PC Engines    | APU2                        | [287f91d7ad](https://bsd-hardware.info/?probe=287f91d7ad) | Jul 01, 2021 |
| Unknown       | YL-J3160L4                  | [2dc18261c1](https://bsd-hardware.info/?probe=2dc18261c1) | Jun 29, 2021 |
| HP            | ProLiant ML310 G5p          | [e20e168df8](https://bsd-hardware.info/?probe=e20e168df8) | Jun 27, 2021 |
| PC Engines    | APU2                        | [6d83dc0715](https://bsd-hardware.info/?probe=6d83dc0715) | Jun 26, 2021 |
| PC Engines    | APU2                        | [5d14705e2d](https://bsd-hardware.info/?probe=5d14705e2d) | Jun 26, 2021 |
| MSI           | G41M-P25                    | [5cc75b4df0](https://bsd-hardware.info/?probe=5cc75b4df0) | Jun 25, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [077394b9b0](https://bsd-hardware.info/?probe=077394b9b0) | Jun 25, 2021 |
| Unknown       | Unknown                     | [f0b6822e10](https://bsd-hardware.info/?probe=f0b6822e10) | Jun 23, 2021 |
| MSI           | B450-A PRO MAX              | [4e3b1f226b](https://bsd-hardware.info/?probe=4e3b1f226b) | Jun 22, 2021 |
| ASUSTek       | P8H67-M PRO                 | [616c7043bd](https://bsd-hardware.info/?probe=616c7043bd) | Jun 22, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [9f4ce06dce](https://bsd-hardware.info/?probe=9f4ce06dce) | Jun 22, 2021 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | [ccb9856049](https://bsd-hardware.info/?probe=ccb9856049) | Jun 21, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [a301a955cd](https://bsd-hardware.info/?probe=a301a955cd) | Jun 20, 2021 |
| PC Engines    | apu4                        | [d362328239](https://bsd-hardware.info/?probe=d362328239) | Jun 19, 2021 |
| PC Engines    | apu4                        | [7306e790c1](https://bsd-hardware.info/?probe=7306e790c1) | Jun 19, 2021 |
| PC Engines    | apu4                        | [02fa2b9f5a](https://bsd-hardware.info/?probe=02fa2b9f5a) | Jun 17, 2021 |
| PC Engines    | apu4                        | [0a186012b6](https://bsd-hardware.info/?probe=0a186012b6) | Jun 17, 2021 |
| Unknown       | Unknown                     | [742980015c](https://bsd-hardware.info/?probe=742980015c) | Jun 17, 2021 |
| Advantech     | SYS-2USM02-6M01E            | [4ff7729857](https://bsd-hardware.info/?probe=4ff7729857) | Jun 16, 2021 |
| ASRock        | FM2A68M-HD+                 | [8bb0d23eb4](https://bsd-hardware.info/?probe=8bb0d23eb4) | Jun 13, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [cba4979cdc](https://bsd-hardware.info/?probe=cba4979cdc) | Jun 12, 2021 |
| ASUSTek       | Maximus VIII EXTREME        | [82f02ef145](https://bsd-hardware.info/?probe=82f02ef145) | Jun 10, 2021 |
| Unknown       | J3160-4L                    | [083c6a59af](https://bsd-hardware.info/?probe=083c6a59af) | Jun 09, 2021 |
| ASUSTek       | PRIME X470-PRO              | [e13854338f](https://bsd-hardware.info/?probe=e13854338f) | Jun 03, 2021 |
| Unknown       | PICO PC                     | [4c7a7ed7f9](https://bsd-hardware.info/?probe=4c7a7ed7f9) | Jun 03, 2021 |
| Unknown       | Unknown                     | [968859e99d](https://bsd-hardware.info/?probe=968859e99d) | Jun 03, 2021 |
| Protectli     | FW4B Ver                    | [9df73013ef](https://bsd-hardware.info/?probe=9df73013ef) | May 31, 2021 |
| Shuttle       | DS77U                       | [5d1c78145e](https://bsd-hardware.info/?probe=5d1c78145e) | May 30, 2021 |
| ASUSTek       | PRIME B560M-A               | [ca05acd52f](https://bsd-hardware.info/?probe=ca05acd52f) | May 30, 2021 |
| Shuttle       | FS81                        | [e9d36a0a00](https://bsd-hardware.info/?probe=e9d36a0a00) | May 30, 2021 |
| PC Engines    | apu4                        | [504997c201](https://bsd-hardware.info/?probe=504997c201) | May 28, 2021 |
| ASRock        | X570M Pro4                  | [1d1a5afcfb](https://bsd-hardware.info/?probe=1d1a5afcfb) | May 28, 2021 |
| Intel         | Q3XXG4-P V1.0               | [a5f628eb76](https://bsd-hardware.info/?probe=a5f628eb76) | May 28, 2021 |
| ASRockRack    | X470D4U2-2T                 | [0eeca5b2fd](https://bsd-hardware.info/?probe=0eeca5b2fd) | May 28, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | [20052b0d55](https://bsd-hardware.info/?probe=20052b0d55) | May 27, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [d8b645d95d](https://bsd-hardware.info/?probe=d8b645d95d) | May 26, 2021 |
| NU941         | 1.0                         | [274326be4a](https://bsd-hardware.info/?probe=274326be4a) | May 26, 2021 |
| BESSTAR Te... | IB9                         | [ae1bfccf22](https://bsd-hardware.info/?probe=ae1bfccf22) | May 26, 2021 |
| MSI           | B85M-G43                    | [24b107b13c](https://bsd-hardware.info/?probe=24b107b13c) | May 26, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [c6a1c1fa15](https://bsd-hardware.info/?probe=c6a1c1fa15) | May 25, 2021 |
| ASRockRack    | X570D4U                     | [683f52d248](https://bsd-hardware.info/?probe=683f52d248) | May 25, 2021 |
| ASRockRack    | X570D4U                     | [13658ebb37](https://bsd-hardware.info/?probe=13658ebb37) | May 25, 2021 |
| Gigabyte      | H97N-WIFI                   | [1de8945dca](https://bsd-hardware.info/?probe=1de8945dca) | May 25, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [f035aab141](https://bsd-hardware.info/?probe=f035aab141) | May 24, 2021 |
| Lex           | Pineview-D                  | [901faae6df](https://bsd-hardware.info/?probe=901faae6df) | May 24, 2021 |
| ASRock        | B85M Pro4                   | [7e86969dcb](https://bsd-hardware.info/?probe=7e86969dcb) | May 23, 2021 |
| ASUSTek       | TUF H370-PRO GAMING         | [dc7d89ab64](https://bsd-hardware.info/?probe=dc7d89ab64) | May 23, 2021 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [195358c8a7](https://bsd-hardware.info/?probe=195358c8a7) | May 23, 2021 |
| Gigabyte      | Z68X-UD4-B3                 | [f1a0cec414](https://bsd-hardware.info/?probe=f1a0cec414) | May 22, 2021 |
| Unknown       | Unknown                     | [80122a9f4a](https://bsd-hardware.info/?probe=80122a9f4a) | May 22, 2021 |
| ASUSTek       | V-P7H55E                    | [8cf113ac55](https://bsd-hardware.info/?probe=8cf113ac55) | May 22, 2021 |
| MSI           | MS-9877 10                  | [36f350e3d0](https://bsd-hardware.info/?probe=36f350e3d0) | May 22, 2021 |
| HP            | ProLiant MicroServer Gen... | [80cf566074](https://bsd-hardware.info/?probe=80cf566074) | May 21, 2021 |
| ASUSTek       | B202                        | [0b66a5fd20](https://bsd-hardware.info/?probe=0b66a5fd20) | May 21, 2021 |
| PC Engines    | apu4                        | [5b2dddd6ca](https://bsd-hardware.info/?probe=5b2dddd6ca) | May 21, 2021 |
| ASRock        | A520M-ITX/ac                | [3c6b3d4ce8](https://bsd-hardware.info/?probe=3c6b3d4ce8) | May 21, 2021 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | [9478973d4c](https://bsd-hardware.info/?probe=9478973d4c) | May 20, 2021 |
| ASRock        | H570M-ITX/ac                | [4427b4ba61](https://bsd-hardware.info/?probe=4427b4ba61) | May 20, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [5c69ad04aa](https://bsd-hardware.info/?probe=5c69ad04aa) | May 19, 2021 |
| NU591         | 1.0                         | [b736031bfd](https://bsd-hardware.info/?probe=b736031bfd) | May 18, 2021 |
| MSI           | MS-9877 10                  | [119095c02a](https://bsd-hardware.info/?probe=119095c02a) | May 18, 2021 |
| Unknown       | Unknown                     | [c677630369](https://bsd-hardware.info/?probe=c677630369) | May 16, 2021 |
| Unknown       | RS780-SB700 Unknox          | [c7668c5b0c](https://bsd-hardware.info/?probe=c7668c5b0c) | May 16, 2021 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [cdf0c1c8ce](https://bsd-hardware.info/?probe=cdf0c1c8ce) | May 15, 2021 |
| ASRock        | B85M Pro4                   | [6b8fcc4ba0](https://bsd-hardware.info/?probe=6b8fcc4ba0) | May 15, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [57bd6d4d0c](https://bsd-hardware.info/?probe=57bd6d4d0c) | May 14, 2021 |
| ASUSTek       | V-P7H55E                    | [7634d3b6ca](https://bsd-hardware.info/?probe=7634d3b6ca) | May 12, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [a9a897258e](https://bsd-hardware.info/?probe=a9a897258e) | May 11, 2021 |
| Unknown       | Unknown                     | [9a399621a9](https://bsd-hardware.info/?probe=9a399621a9) | May 11, 2021 |
| PC Engines    | APU2                        | [131c1bc480](https://bsd-hardware.info/?probe=131c1bc480) | May 11, 2021 |
| ASUSTek       | V-P7H55E                    | [f2e42a5ca3](https://bsd-hardware.info/?probe=f2e42a5ca3) | May 10, 2021 |
| ASUSTek       | V-P7H55E                    | [0af6399c18](https://bsd-hardware.info/?probe=0af6399c18) | May 10, 2021 |
| Foxconn       | TPS01                       | [c59be618ed](https://bsd-hardware.info/?probe=c59be618ed) | May 09, 2021 |
| Foxconn       | TPS01                       | [d1e286717c](https://bsd-hardware.info/?probe=d1e286717c) | May 07, 2021 |
| Foxconn       | TPS01                       | [d07decc0e6](https://bsd-hardware.info/?probe=d07decc0e6) | May 07, 2021 |
| Advantech     | SYS-2USM02-6M01E            | [f05ff4a687](https://bsd-hardware.info/?probe=f05ff4a687) | May 07, 2021 |
| PC Engines    | APU                         | [c1de9809dd](https://bsd-hardware.info/?probe=c1de9809dd) | May 07, 2021 |
| Unknown       | YL-SKUL6                    | [526c031a99](https://bsd-hardware.info/?probe=526c031a99) | May 05, 2021 |
| Unknown       | Unknown                     | [81d1eaf93d](https://bsd-hardware.info/?probe=81d1eaf93d) | May 04, 2021 |
| Unknown       | Unknown                     | [4f91060920](https://bsd-hardware.info/?probe=4f91060920) | May 04, 2021 |
| PC Engines    | apu4                        | [65dbb75598](https://bsd-hardware.info/?probe=65dbb75598) | May 03, 2021 |
| NEXCOM        | NSA3110 B                   | [df2d210d67](https://bsd-hardware.info/?probe=df2d210d67) | May 03, 2021 |
| Intel         | DQ57TM AAE70931-402         | [12058880bc](https://bsd-hardware.info/?probe=12058880bc) | May 03, 2021 |
| Unknown       | Unknown                     | [5b1c1182df](https://bsd-hardware.info/?probe=5b1c1182df) | May 03, 2021 |
| Fujitsu       | D3313-F1 S26361-D3313-F1    | [de1f3fdb0f](https://bsd-hardware.info/?probe=de1f3fdb0f) | May 03, 2021 |
| HP            | ProLiant MicroServer Gen... | [ec72647c2b](https://bsd-hardware.info/?probe=ec72647c2b) | May 03, 2021 |
| Beckhoff A... | CB3056 G4                   | [120665d4d3](https://bsd-hardware.info/?probe=120665d4d3) | Apr 30, 2021 |
| ASRock        | Q1900-ITX                   | [62e1c023ed](https://bsd-hardware.info/?probe=62e1c023ed) | Apr 29, 2021 |
| Intel         | DQ57TM AAE70931-402         | [f308ae78ea](https://bsd-hardware.info/?probe=f308ae78ea) | Apr 29, 2021 |
| ASRock        | Q2900M                      | [c96913c9ed](https://bsd-hardware.info/?probe=c96913c9ed) | Apr 28, 2021 |
| HP            | ProLiant MicroServer Gen... | [7f0b39e526](https://bsd-hardware.info/?probe=7f0b39e526) | Apr 27, 2021 |

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
| OPNsense 21.7.7   | 43       | 3.77%   |
| OPNsense 21.1     | 42       | 3.68%   |
| OPNsense 22.7.10  | 40       | 3.5%    |
| OPNsense 21.7.1   | 38       | 3.33%   |
| OPNsense 21.1.5   | 38       | 3.33%   |
| OPNsense 22.1     | 36       | 3.15%   |
| OPNsense 20.7.8   | 34       | 2.98%   |
| OPNsense 21.7.3   | 33       | 2.89%   |
| OPNsense 21.1.3   | 32       | 2.8%    |
| OPNsense 22.7.9   | 31       | 2.71%   |
| OPNsense 21.1.4   | 31       | 2.71%   |
| OPNsense 22.1.8   | 30       | 2.63%   |
| OPNsense 21.7.6   | 30       | 2.63%   |
| OPNsense 22.7.4   | 29       | 2.54%   |
| OPNsense 21.1.2   | 29       | 2.54%   |
| OPNsense 21.1.1   | 29       | 2.54%   |
| OPNsense 22.7.6   | 27       | 2.36%   |
| OPNsense 22.1.6   | 24       | 2.1%    |
| OPNsense 21.7.5   | 24       | 2.1%    |
| OPNsense 22.1.10  | 20       | 1.75%   |
| OPNsense 22.1.2   | 18       | 1.58%   |
| helloSystem 0.4.0 | 18       | 1.58%   |
| OPNsense 22.7.7   | 17       | 1.49%   |
| OPNsense 22.7     | 17       | 1.49%   |
| OPNsense 22.1.4   | 17       | 1.49%   |
| OPNsense 22.1.1   | 17       | 1.49%   |
| OPNsense 22.1.9   | 15       | 1.31%   |
| OpenBSD 6.8       | 15       | 1.31%   |
| OPNsense 22.7.2   | 13       | 1.14%   |
| OPNsense 21.7.2   | 13       | 1.14%   |
| OPNsense 21.1.7   | 13       | 1.14%   |
| OPNsense 21.7.4   | 12       | 1.05%   |
| OPNsense 21.1.8   | 12       | 1.05%   |
| OPNsense 22.7.8   | 11       | 0.96%   |
| OPNsense 21.7     | 11       | 0.96%   |
| OPNsense 21.1.6   | 11       | 0.96%   |
| OPNsense 22.1.7   | 10       | 0.88%   |
| FreeBSD 13.1      | 10       | 0.88%   |
| FreeBSD 13.0      | 9        | 0.79%   |
| OPNsense 22.7.5   | 8        | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 682      | 77.32%  |
| FreeBSD     | 95       | 10.77%  |
| helloSystem | 39       | 4.42%   |
| OpenBSD     | 32       | 3.63%   |
| GhostBSD    | 14       | 1.59%   |
| NomadBSD    | 5        | 0.57%   |
| NetBSD      | 4        | 0.45%   |
| TrueNAS     | 3        | 0.34%   |
| MyBee       | 2        | 0.23%   |
| pfSense     | 1        | 0.11%   |
| PC-BSD      | 1        | 0.11%   |
| HardenedBSD | 1        | 0.11%   |
| FreeNAS     | 1        | 0.11%   |
| DragonFly   | 1        | 0.11%   |
| ClonOS      | 1        | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 869      | 99.09%  |
| arm64   | 4        | 0.46%   |
| arm     | 2        | 0.23%   |
| sparc64 | 1        | 0.11%   |
| i386    | 1        | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 757      | 85.54%  |
| helloDesktop  | 47       | 5.31%   |
| MATE          | 18       | 2.03%   |
| KDE5          | 14       | 1.58%   |
| fvwm          | 12       | 1.36%   |
| XFCE          | 8        | 0.9%    |
| TWM           | 7        | 0.79%   |
| AwesomeWM     | 5        | 0.56%   |
| Openbox       | 4        | 0.45%   |
| i3            | 3        | 0.34%   |
| GNOME         | 3        | 0.34%   |
| LXDE          | 1        | 0.11%   |
| GNUstep       | 1        | 0.11%   |
| Fluxbox       | 1        | 0.11%   |
| filer         | 1        | 0.11%   |
| Enlightenment | 1        | 0.11%   |
| Compton       | 1        | 0.11%   |
| Cinnamon      | 1        | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 766      | 87.14%  |
| X11     | 113      | 12.86%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 789      | 89.35%  |
| SLiM    | 52       | 5.89%   |
| LightDM | 16       | 1.81%   |
| SDDM    | 13       | 1.47%   |
| XDM     | 7        | 0.79%   |
| GDM     | 5        | 0.57%   |
| Ly      | 1        | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Desktops | Percent |
|-----------------|----------|---------|
| Unknown         | 739      | 83.69%  |
| en_US           | 61       | 6.91%   |
| C               | 46       | 5.21%   |
| de_DE           | 31       | 3.51%   |
| en_GB           | 2        | 0.23%   |
| ru_RU           | 1        | 0.11%   |
| ISO8859-15      | 1        | 0.11%   |
| en_DE           | 1        | 0.11%   |
| de_DE.ISO8859-1 | 1        | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 743      | 84.34%  |
| BIOS | 138      | 15.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 587      | 65.59%  |
| Zfs     | 271      | 30.28%  |
| Ffs     | 32       | 3.58%   |
| Cd9660  | 4        | 0.45%   |
| Hammer2 | 1        | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 800      | 90.91%  |
| MBR     | 64       | 7.27%   |
| Unknown | 15       | 1.7%    |
| BSD     | 1        | 0.11%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 146      | 16.65%  |
| PC Engines                 | 100      | 11.4%   |
| ASUSTek Computer           | 64       | 7.3%    |
| Fujitsu                    | 63       | 7.18%   |
| ASRock                     | 58       | 6.61%   |
| Hewlett-Packard            | 56       | 6.39%   |
| Intel                      | 43       | 4.9%    |
| Gigabyte Technology        | 41       | 4.68%   |
| MSI                        | 37       | 4.22%   |
| Dell                       | 36       | 4.1%    |
| Supermicro                 | 23       | 2.62%   |
| BESSTAR Tech               | 19       | 2.17%   |
| Protectli                  | 18       | 2.05%   |
| Shuttle                    | 16       | 1.82%   |
| HARDKERNEL                 | 13       | 1.48%   |
| Lenovo                     | 12       | 1.37%   |
| Thomas-Krenn.AG            | 9        | 1.03%   |
| CncTion                    | 9        | 1.03%   |
| ASRockRack                 | 8        | 0.91%   |
| CheckPoint                 | 7        | 0.8%    |
| NF541                      | 6        | 0.68%   |
| MW                         | 6        | 0.68%   |
| Biostar                    | 6        | 0.68%   |
| Deciso                     | 5        | 0.57%   |
| Beckhoff Automation        | 5        | 0.57%   |
| Techvision                 | 4        | 0.46%   |
| NEXCOM                     | 4        | 0.46%   |
| ShenZhen MinWin Technology | 3        | 0.34%   |
| Lex                        | 3        | 0.34%   |
| IceWhale Technology        | 3        | 0.34%   |
| Foxconn                    | 3        | 0.34%   |
| Advantech                  | 3        | 0.34%   |
| Acer                       | 3        | 0.34%   |
| YANYU                      | 2        | 0.23%   |
| Yanling                    | 2        | 0.23%   |
| OEM                        | 2        | 0.23%   |
| NU591                      | 2        | 0.23%   |
| NF841                      | 2        | 0.23%   |
| Medion                     | 2        | 0.23%   |
| Lanner                     | 2        | 0.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 149      | 16.99%  |
| PC Engines APU2                | 50       | 5.7%    |
| PC Engines apu4                | 32       | 3.65%   |
| Fujitsu FUTRO S920             | 30       | 3.42%   |
| Intel Q3XXG4-P V1.0            | 15       | 1.71%   |
| HARDKERNEL ODROID-H2           | 12       | 1.37%   |
| HP ProLiant MicroServer Gen8   | 9        | 1.03%   |
| BESSTAR Tech X35G              | 9        | 1.03%   |
| Protectli FW4B                 | 8        | 0.91%   |
| PC Engines APU3                | 8        | 0.91%   |
| PC Engines APU                 | 8        | 0.91%   |
| Protectli FW6                  | 7        | 0.8%    |
| NF541 1.0                      | 6        | 0.68%   |
| MW GMLK-2_5G4L                 | 6        | 0.68%   |
| HP t620 PLUS Quad Core TC      | 6        | 0.68%   |
| CncTion N5105-4L               | 6        | 0.68%   |
| Thomas-Krenn.AG LES network+   | 5        | 0.57%   |
| Techvision TVI7309X            | 4        | 0.46%   |
| NEXCOM ASG                     | 4        | 0.46%   |
| MSI MS-7816                    | 4        | 0.46%   |
| Fujitsu FUTRO S930             | 4        | 0.46%   |
| Dell OptiPlex 7010             | 4        | 0.46%   |
| Deciso Netboard A10 V2         | 4        | 0.46%   |
| ASUS M5A78L-M/USB3             | 4        | 0.46%   |
| ASUS All Series                | 4        | 0.46%   |
| Thomas-Krenn.AG LES network 6L | 3        | 0.34%   |
| Supermicro X8SIL               | 3        | 0.34%   |
| Supermicro X7SPA-HF            | 3        | 0.34%   |
| MSI MS-7592                    | 3        | 0.34%   |
| Lex Pineview-D                 | 3        | 0.34%   |
| Intel CRESCENTBAY              | 3        | 0.34%   |
| IceWhale ZimaBoard 832 ZMB     | 3        | 0.34%   |
| HP t620 Quad Core TC           | 3        | 0.34%   |
| HP ProLiant MicroServer        | 3        | 0.34%   |
| HP EliteDesk 800 G3 SFF        | 3        | 0.34%   |
| Fujitsu ESPRIMO C720           | 3        | 0.34%   |
| Dell OptiPlex 9020             | 3        | 0.34%   |
| ASRockRack 520001              | 3        | 0.34%   |
| ASRock H570M-ITX/ac            | 3        | 0.34%   |
| Advantech SYS-2USM02-6M01E     | 3        | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Unknown              | 149      | 16.99%  |
| PC Engines APU2      | 50       | 5.7%    |
| Fujitsu FUTRO        | 41       | 4.68%   |
| PC Engines apu4      | 32       | 3.65%   |
| Dell OptiPlex        | 28       | 3.19%   |
| Intel Q3XXG4-P       | 15       | 1.71%   |
| HP ProLiant          | 15       | 1.71%   |
| HARDKERNEL ODROID-H2 | 12       | 1.37%   |
| HP ProDesk           | 11       | 1.25%   |
| HP t620              | 10       | 1.14%   |
| HP Compaq            | 10       | 1.14%   |
| ASUS PRIME           | 10       | 1.14%   |
| Lenovo ThinkCentre   | 9        | 1.03%   |
| Fujitsu ESPRIMO      | 9        | 1.03%   |
| BESSTAR Tech X35G    | 9        | 1.03%   |
| Thomas-Krenn.AG LES  | 8        | 0.91%   |
| Protectli FW4B       | 8        | 0.91%   |
| PC Engines APU3      | 8        | 0.91%   |
| PC Engines APU       | 8        | 0.91%   |
| Protectli FW6        | 7        | 0.8%    |
| ASUS TUF             | 7        | 0.8%    |
| NF541 1.0            | 6        | 0.68%   |
| MW GMLK-2            | 6        | 0.68%   |
| CncTion N5105-4L     | 6        | 0.68%   |
| HP EliteDesk         | 5        | 0.57%   |
| Deciso Netboard      | 5        | 0.57%   |
| ASUS ROG             | 5        | 0.57%   |
| Techvision TVI7309X  | 4        | 0.46%   |
| NEXCOM ASG           | 4        | 0.46%   |
| MSI MS-7816          | 4        | 0.46%   |
| Gigabyte X570        | 4        | 0.46%   |
| Dell Precision       | 4        | 0.46%   |
| ASUS M5A78L-M        | 4        | 0.46%   |
| ASUS All             | 4        | 0.46%   |
| Supermicro X8SIL     | 3        | 0.34%   |
| Supermicro X7SPA-HF  | 3        | 0.34%   |
| MSI MS-7592          | 3        | 0.34%   |
| Lex Pineview-D       | 3        | 0.34%   |
| Intel CRESCENTBAY    | 3        | 0.34%   |
| IceWhale ZimaBoard   | 3        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 124      | 14.14%  |
| 2020    | 104      | 11.86%  |
| 2016    | 97       | 11.06%  |
| 2019    | 90       | 10.26%  |
| 2021    | 85       | 9.69%   |
| 2014    | 73       | 8.32%   |
| 2013    | 53       | 6.04%   |
| 2022    | 49       | 5.59%   |
| 2017    | 49       | 5.59%   |
| 2012    | 43       | 4.9%    |
| 2011    | 32       | 3.65%   |
| 2010    | 24       | 2.74%   |
| 2009    | 19       | 2.17%   |
| 2015    | 16       | 1.82%   |
| 2008    | 8        | 0.91%   |
| Unknown | 7        | 0.8%    |
| 2007    | 3        | 0.34%   |
| 2006    | 1        | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 877      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 766      | 87.34%  |
| Yes  | 111      | 12.66%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 317      | 35.82%  |
| 4.01-8.0        | 237      | 26.78%  |
| 16.01-24.0      | 180      | 20.34%  |
| 32.01-64.0      | 67       | 7.57%   |
| 2.01-3.0        | 36       | 4.07%   |
| 64.01-256.0     | 24       | 2.71%   |
| 24.01-32.0      | 8        | 0.9%    |
| 3.01-4.0        | 6        | 0.68%   |
| 1.01-2.0        | 4        | 0.45%   |
| 0.51-1.0        | 3        | 0.34%   |
| 0.01-0.5        | 2        | 0.23%   |
| More than 256.0 | 1        | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 492      | 54.42%  |
| 0.51-1.0    | 283      | 31.31%  |
| 1.01-2.0    | 70       | 7.74%   |
| 2.01-3.0    | 16       | 1.77%   |
| 3.01-4.0    | 12       | 1.33%   |
| 4.01-8.0    | 11       | 1.22%   |
| 16.01-24.0  | 4        | 0.44%   |
| 0           | 4        | 0.44%   |
| Unknown     | 4        | 0.44%   |
| 8.01-16.0   | 3        | 0.33%   |
| 24.01-32.0  | 2        | 0.22%   |
| 64.01-256.0 | 2        | 0.22%   |
| 32.01-64.0  | 1        | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 666      | 74.25%  |
| 2      | 92       | 10.26%  |
| 0      | 58       | 6.47%   |
| 3      | 36       | 4.01%   |
| 4      | 22       | 2.45%   |
| 5      | 10       | 1.11%   |
| 6      | 6        | 0.67%   |
| 7      | 5        | 0.56%   |
| 9      | 1        | 0.11%   |
| 8      | 1        | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 770      | 87.4%   |
| Yes       | 111      | 12.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 870      | 99.2%   |
| No        | 7        | 0.8%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 724      | 81.9%   |
| Yes       | 160      | 18.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 797      | 90.57%  |
| Yes       | 83       | 9.43%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Germany | 877      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Berlin            | 83       | 8.57%   |
| Munich            | 43       | 4.44%   |
| Hamburg           | 31       | 3.2%    |
| Frankfurt am Main | 25       | 2.58%   |
| Cologne           | 24       | 2.48%   |
| Stuttgart         | 15       | 1.55%   |
| Karlsruhe         | 14       | 1.44%   |
| Ludwigsburg       | 13       | 1.34%   |
| Hanover           | 10       | 1.03%   |
| Falkenstein       | 10       | 1.03%   |
| Nuremberg         | 8        | 0.83%   |
| Dortmund          | 8        | 0.83%   |
| Bonn              | 8        | 0.83%   |
| Reutlingen        | 7        | 0.72%   |
| Mannheim          | 7        | 0.72%   |
| Heidelberg        | 7        | 0.72%   |
| Dresden           | 7        | 0.72%   |
| Bielefeld         | 7        | 0.72%   |
| Wiesbaden         | 6        | 0.62%   |
| Ulm               | 6        | 0.62%   |
| Paderborn         | 6        | 0.62%   |
| Leipzig           | 6        | 0.62%   |
| Kiel              | 6        | 0.62%   |
| Darmstadt         | 6        | 0.62%   |
| Chemnitz          | 6        | 0.62%   |
| Bochum            | 6        | 0.62%   |
| Siegen            | 5        | 0.52%   |
| Jena              | 5        | 0.52%   |
| DГјsseldorf     | 5        | 0.52%   |
| Duisburg          | 5        | 0.52%   |
| Braunschweig      | 5        | 0.52%   |
| Wuppertal         | 4        | 0.41%   |
| Wernigerode       | 4        | 0.41%   |
| Tamm              | 4        | 0.41%   |
| Rietberg          | 4        | 0.41%   |
| Peine             | 4        | 0.41%   |
| Oldenburg         | 4        | 0.41%   |
| Neuss             | 4        | 0.41%   |
| Mainz             | 4        | 0.41%   |
| Magdeburg         | 4        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 157      | 255    | 15.53%  |
| Transcend           | 93       | 130    | 9.2%    |
| WDC                 | 91       | 162    | 9%      |
| Kingston            | 83       | 138    | 8.21%   |
| SanDisk             | 61       | 86     | 6.03%   |
| Crucial             | 58       | 79     | 5.74%   |
| Seagate             | 54       | 85     | 5.34%   |
| Intel               | 44       | 58     | 4.35%   |
| Toshiba             | 40       | 62     | 3.96%   |
| Phison              | 36       | 51     | 3.56%   |
| Hoodisk             | 25       | 43     | 2.47%   |
| China               | 25       | 28     | 2.47%   |
| Intenso             | 24       | 38     | 2.37%   |
| HGST                | 19       | 35     | 1.88%   |
| Hitachi             | 16       | 27     | 1.58%   |
| A-DATA Technology   | 13       | 15     | 1.29%   |
| Micron Technology   | 12       | 25     | 1.19%   |
| Innodisk            | 12       | 12     | 1.19%   |
| FORESEE             | 11       | 15     | 1.09%   |
| OCZ                 | 9        | 13     | 0.89%   |
| NVMe                | 9        | 13     | 0.89%   |
| Apacer              | 7        | 10     | 0.69%   |
| SPCC                | 6        | 9      | 0.59%   |
| Patriot             | 6        | 8      | 0.59%   |
| ATP                 | 6        | 6      | 0.59%   |
| Dogfish             | 5        | 6      | 0.49%   |
| LITEONIT            | 4        | 5      | 0.4%    |
| KingDian            | 4        | 8      | 0.4%    |
| Gigabyte Technology | 4        | 5      | 0.4%    |
| Corsair             | 4        | 8      | 0.4%    |
| Team                | 3        | 3      | 0.3%    |
| TCSUNBOW            | 3        | 4      | 0.3%    |
| SK hynix            | 3        | 3      | 0.3%    |
| PNY                 | 3        | 3      | 0.3%    |
| OPENBSD             | 3        | 3      | 0.3%    |
| MEMXPRO             | 3        | 4      | 0.3%    |
| KIOXIA-EXCERIA      | 3        | 6      | 0.3%    |
| Hewlett-Packard     | 3        | 4      | 0.3%    |
| Advantech           | 3        | 5      | 0.3%    |
| Verbatim            | 2        | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Phison SATA SSD 16GB            | 31       | 2.91%   |
| Transcend TS128GMSA230S 128GB   | 21       | 1.97%   |
| Transcend TS64GMSA230S 64GB     | 12       | 1.12%   |
| Samsung SSD 860 EVO 500GB       | 12       | 1.12%   |
| Samsung SSD 850 EVO 250GB       | 12       | 1.12%   |
| China SATA SSD 16GB             | 12       | 1.12%   |
| Kingston SUV500MS120G 120GB     | 11       | 1.03%   |
| Transcend TS256GMSA230S 256GB   | 10       | 0.94%   |
| Samsung SSD 870 EVO 250GB       | 9        | 0.84%   |
| Kingston SA400S37120G 120GB     | 9        | 0.84%   |
| Hoodisk SSD 64GB                | 8        | 0.75%   |
| Crucial CT240BX500SSD1 240GB    | 8        | 0.75%   |
| Transcend TS32GMSA370 32GB      | 7        | 0.66%   |
| Transcend TS128GMSA370 128GB    | 7        | 0.66%   |
| Kingston OM8PDP3512B-A01 512GB  | 7        | 0.66%   |
| Hoodisk SSD 256GB               | 7        | 0.66%   |
| Hoodisk SSD 128GB               | 7        | 0.66%   |
| Transcend TS64GMSA370 64GB      | 6        | 0.56%   |
| Transcend TS32GSSD370S 32GB     | 6        | 0.56%   |
| SanDisk SSD PLUS 120GB          | 6        | 0.56%   |
| SanDisk SDSSDA120G 120GB        | 6        | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB  | 6        | 0.56%   |
| Samsung SSD 840 EVO 250GB       | 6        | 0.56%   |
| Samsung SSD 840 EVO 120GB       | 6        | 0.56%   |
| Kingston SA400S37240G 240GB     | 6        | 0.56%   |
| Innodisk DEMSR- 08GB mSATA 3ME3 | 6        | 0.56%   |
| Crucial CT500MX500SSD1 500GB    | 6        | 0.56%   |
| WDC WD40EFRX-68N32N0 4TB        | 5        | 0.47%   |
| Samsung SSD 860 EVO mSATA 250GB | 5        | 0.47%   |
| Samsung SSD 850 PRO 256GB       | 5        | 0.47%   |
| Samsung SSD 830 Series 128GB    | 5        | 0.47%   |
| Kingston SV300S37A60G 64GB      | 5        | 0.47%   |
| Kingston SV300S37A120G 120GB    | 5        | 0.47%   |
| Intenso SSD 120GB               | 5        | 0.47%   |
| Intel SSDSC2KG240G8 240GB       | 5        | 0.47%   |
| Crucial CT120BX500SSD1 120GB    | 5        | 0.47%   |
| China XJH-128GB                 | 5        | 0.47%   |
| WDC WD2000FYYZ-01UL1B1 2TB      | 4        | 0.37%   |
| Toshiba DT01ACA050 500GB        | 4        | 0.37%   |
| Samsung SSD 970 PRO 512GB       | 4        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 72       | 133    | 32.29%  |
| Seagate             | 51       | 81     | 22.87%  |
| Toshiba             | 25       | 45     | 11.21%  |
| HGST                | 19       | 35     | 8.52%   |
| Hitachi             | 16       | 27     | 7.17%   |
| Samsung Electronics | 14       | 18     | 6.28%   |
| NVMe                | 6        | 7      | 2.69%   |
| OPENBSD             | 3        | 3      | 1.35%   |
| JetFlash            | 2        | 2      | 0.9%    |
| Hewlett-Packard     | 2        | 2      | 0.9%    |
| Fujitsu             | 2        | 2      | 0.9%    |
| WD MediaMax         | 1        | 2      | 0.45%   |
| Product:            | 1        | 1      | 0.45%   |
| Maxtor              | 1        | 1      | 0.45%   |
| LSI                 | 1        | 1      | 0.45%   |
| Intenso             | 1        | 1      | 0.45%   |
| IBM/Hitachi         | 1        | 1      | 0.45%   |
| IBM                 | 1        | 1      | 0.45%   |
| Generic             | 1        | 1      | 0.45%   |
| General             | 1        | 1      | 0.45%   |
| ASMT                | 1        | 1      | 0.45%   |
| Apple               | 1        | 1      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 119      | 183    | 17.12%  |
| Transcend           | 91       | 127    | 13.09%  |
| Kingston            | 64       | 101    | 9.21%   |
| SanDisk             | 61       | 86     | 8.78%   |
| Crucial             | 53       | 70     | 7.63%   |
| Intel               | 37       | 48     | 5.32%   |
| Phison              | 35       | 50     | 5.04%   |
| Hoodisk             | 25       | 43     | 3.6%    |
| China               | 25       | 28     | 3.6%    |
| Intenso             | 23       | 37     | 3.31%   |
| A-DATA Technology   | 13       | 15     | 1.87%   |
| Toshiba             | 12       | 13     | 1.73%   |
| Innodisk            | 12       | 12     | 1.73%   |
| WDC                 | 11       | 12     | 1.58%   |
| Micron Technology   | 10       | 21     | 1.44%   |
| OCZ                 | 9        | 13     | 1.29%   |
| FORESEE             | 9        | 12     | 1.29%   |
| Apacer              | 7        | 10     | 1.01%   |
| ATP                 | 6        | 6      | 0.86%   |
| SPCC                | 5        | 8      | 0.72%   |
| NVMe                | 5        | 6      | 0.72%   |
| Dogfish             | 5        | 6      | 0.72%   |
| Patriot             | 4        | 6      | 0.58%   |
| LITEONIT            | 4        | 5      | 0.58%   |
| KingDian            | 4        | 8      | 0.58%   |
| Team                | 3        | 3      | 0.43%   |
| TCSUNBOW            | 3        | 4      | 0.43%   |
| MEMXPRO             | 3        | 4      | 0.43%   |
| Corsair             | 3        | 7      | 0.43%   |
| Advantech           | 3        | 5      | 0.43%   |
| Verbatim            | 2        | 2      | 0.29%   |
| Vaseky              | 2        | 2      | 0.29%   |
| ShiJi               | 2        | 3      | 0.29%   |
| Seagate             | 2        | 3      | 0.29%   |
| Protectli           | 2        | 3      | 0.29%   |
| PNY                 | 2        | 2      | 0.29%   |
| Plextor             | 2        | 2      | 0.29%   |
| Leven               | 2        | 4      | 0.29%   |
| KingSpec            | 2        | 2      | 0.29%   |
| BORY                | 2        | 3      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 639      | 988    | 69.38%  |
| HDD  | 178      | 367    | 19.33%  |
| NVMe | 104      | 168    | 11.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 747      | 1355   | 87.78%  |
| NVMe | 104      | 168    | 12.22%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 685      | 1046   | 81.74%  |
| 0.51-1.0        | 79       | 128    | 9.43%   |
| 1.01-2.0        | 31       | 74     | 3.7%    |
| 3.01-4.0        | 18       | 44     | 2.15%   |
| 2.01-3.0        | 11       | 32     | 1.31%   |
| 4.01-10.0       | 10       | 19     | 1.19%   |
| 10.01-20.0      | 3        | 11     | 0.36%   |
| More than 100.0 | 1        | 1      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 362      | 40.36%  |
| 1-20           | 128      | 14.27%  |
| 251-500        | 126      | 14.05%  |
| 21-50          | 117      | 13.04%  |
| 51-100         | 96       | 10.7%   |
| 501-1000       | 42       | 4.68%   |
| More than 3000 | 11       | 1.23%   |
| 2001-3000      | 5        | 0.56%   |
| 1001-2000      | 5        | 0.56%   |
| Unknown        | 5        | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 833      | 92.25%  |
| 21-50          | 38       | 4.21%   |
| 51-100         | 10       | 1.11%   |
| Unknown        | 5        | 0.55%   |
| 251-500        | 4        | 0.44%   |
| 101-250        | 4        | 0.44%   |
| 1001-2000      | 4        | 0.44%   |
| 2001-3000      | 2        | 0.22%   |
| 501-1000       | 2        | 0.22%   |
| More than 3000 | 1        | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| Kingston SV300S37A60G 64GB                 | 3        | 5      | 3.45%   |
| WDC WDS240G2G0A-00JH30 240GB               | 2        | 3      | 2.3%    |
| WDC WD30EFRX-68EUZN0 3TB                   | 2        | 7      | 2.3%    |
| WDC WD2000FYYZ-01UL1B2 2TB                 | 2        | 4      | 2.3%    |
| WDC WD2000FYYZ-01UL1B1 2TB                 | 2        | 4      | 2.3%    |
| WDC WD1600AAJS-75M0A0 160GB                | 2        | 2      | 2.3%    |
| Toshiba THNSNK128GCS8 SATA 128GB           | 2        | 2      | 2.3%    |
| Seagate ST3160318AS 160GB                  | 2        | 2      | 2.3%    |
| Samsung Electronics HD501LJ 500GB          | 2        | 2      | 2.3%    |
| Micron Technology 1100_MTFDDAK512TBN 512GB | 2        | 4      | 2.3%    |
| Kingston SMS200S360G 64GB                  | 2        | 2      | 2.3%    |
| Kingston SMS200S3120G 120GB                | 2        | 3      | 2.3%    |
| Intenso SSD SATAIII 128GB                  | 2        | 2      | 2.3%    |
| HGST HTS541010A7E630 1TB                   | 2        | 4      | 2.3%    |
| Crucial CT275MX300SSD1 275GB               | 2        | 2      | 2.3%    |
| WDC WD60EFRX-68TGBN1 6TB                   | 1        | 3      | 1.15%   |
| WDC WD2503ABYX-01WERA0 256GB               | 1        | 1      | 1.15%   |
| WDC WD1600AAJS-08L7A0 160GB                | 1        | 1      | 1.15%   |
| WDC WD1600AABS-00PRA0 160GB                | 1        | 1      | 1.15%   |
| WDC WD10EZEX-60WN4A0 1TB                   | 1        | 1      | 1.15%   |
| WDC WD10EAVS-00D7B0 1TB                    | 1        | 1      | 1.15%   |
| Toshiba MQ02ABD100H 1TB                    | 1        | 4      | 1.15%   |
| SMI SSD DISK 120GB                         | 1        | 1      | 1.15%   |
| Seagate ST9500620NS 500GB                  | 1        | 1      | 1.15%   |
| Seagate ST9320325AS 320GB                  | 1        | 1      | 1.15%   |
| Seagate ST9250827AS 250GB                  | 1        | 2      | 1.15%   |
| Seagate ST9160310AS 160GB                  | 1        | 2      | 1.15%   |
| Seagate ST500DM002-1BD142 500GB            | 1        | 2      | 1.15%   |
| Seagate ST4000NM0033-9ZM170 4TB            | 1        | 2      | 1.15%   |
| Seagate ST4000DM004-2CV104 4TB             | 1        | 1      | 1.15%   |
| Seagate ST380013AS 80GB                    | 1        | 1      | 1.15%   |
| Seagate ST3250410AS 250GB                  | 1        | 1      | 1.15%   |
| Seagate ST320LT007-9ZV142 320GB            | 1        | 1      | 1.15%   |
| Seagate ST3160815AS 160GB                  | 1        | 1      | 1.15%   |
| Seagate ST3000DM001-1ER166 3TB             | 1        | 1      | 1.15%   |
| Seagate ST250DM000-1BD141 250GB            | 1        | 1      | 1.15%   |
| Seagate ST1000LM024 HN-M101MBB 1TB         | 1        | 1      | 1.15%   |
| Seagate ST1000DX001-1CM162 1TB             | 1        | 1      | 1.15%   |
| SanDisk SDCFHS-016G                        | 1        | 2      | 1.15%   |
| Samsung Electronics SSD 870 EVO 1TB        | 1        | 1      | 1.15%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 21     | 19.54%  |
| WDC                 | 16       | 28     | 18.39%  |
| Kingston            | 8        | 12     | 9.2%    |
| Intel               | 8        | 9      | 9.2%    |
| Samsung Electronics | 7        | 10     | 8.05%   |
| Crucial             | 7        | 11     | 8.05%   |
| HGST                | 4        | 6      | 4.6%    |
| Toshiba             | 3        | 6      | 3.45%   |
| Micron Technology   | 3        | 5      | 3.45%   |
| OCZ                 | 2        | 2      | 2.3%    |
| Intenso             | 2        | 2      | 2.3%    |
| Hitachi             | 2        | 2      | 2.3%    |
| SMI                 | 1        | 1      | 1.15%   |
| SanDisk             | 1        | 2      | 1.15%   |
| Maxtor              | 1        | 1      | 1.15%   |
| KingSpec            | 1        | 1      | 1.15%   |
| KingDian            | 1        | 1      | 1.15%   |
| Corsair             | 1        | 3      | 1.15%   |
| Apacer              | 1        | 1      | 1.15%   |
| A-DATA Technology   | 1        | 2      | 1.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 21     | 39.53%  |
| WDC                 | 14       | 25     | 32.56%  |
| Samsung Electronics | 4        | 5      | 9.3%    |
| HGST                | 4        | 6      | 9.3%    |
| Hitachi             | 2        | 2      | 4.65%   |
| Toshiba             | 1        | 4      | 2.33%   |
| Maxtor              | 1        | 1      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 44       | 62     | 51.76%  |
| HDD  | 41       | 64     | 48.24%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD3200BPVT-16JJ5T0 320GB      | 1        | 1      | 25%     |
| Transcend TS32GSSD370S 32GB       | 1        | 1      | 25%     |
| Samsung Electronics SSD 980 250GB | 1        | 1      | 25%     |
| Kingston SV300S37A60G 64GB        | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 25%     |
| Transcend           | 1        | 1      | 25%     |
| Samsung Electronics | 1        | 1      | 25%     |
| Kingston            | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 752      | 1349   | 86.54%  |
| Malfunc  | 83       | 126    | 9.55%   |
| Detected | 30       | 44     | 3.45%   |
| Failed   | 4        | 4      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 613      | 59.75%  |
| AMD                            | 245      | 23.88%  |
| Samsung Electronics            | 38       | 3.7%    |
| ASMedia Technology             | 19       | 1.85%   |
| Kingston Technology Company    | 18       | 1.75%   |
| SanDisk                        | 15       | 1.46%   |
| Phison Electronics             | 11       | 1.07%   |
| Marvell Technology Group       | 9        | 0.88%   |
| Broadcom / LSI                 | 7        | 0.68%   |
| Micron/Crucial Technology      | 6        | 0.58%   |
| Silicon Motion                 | 5        | 0.49%   |
| VIA Technologies               | 4        | 0.39%   |
| Toshiba                        | 3        | 0.29%   |
| SK hynix                       | 3        | 0.29%   |
| Silicon Image                  | 3        | 0.29%   |
| Shenzhen Longsys Electronics   | 3        | 0.29%   |
| Nvidia                         | 3        | 0.29%   |
| KIOXIA                         | 3        | 0.29%   |
| Hewlett-Packard                | 3        | 0.29%   |
| Micron Technology              | 2        | 0.19%   |
| MAXIO Technology (Hangzhou)    | 2        | 0.19%   |
| Yangtze Memory Technologies    | 1        | 0.1%    |
| ULi Electronics                | 1        | 0.1%    |
| Solid State Storage Technology | 1        | 0.1%    |
| Seagate Technology             | 1        | 0.1%    |
| Realtek Semiconductor          | 1        | 0.1%    |
| JMicron Technology             | 1        | 0.1%    |
| Integrated Technology Express  | 1        | 0.1%    |
| Enmotus                        | 1        | 0.1%    |
| Adaptec                        | 1        | 0.1%    |
| 3ware                          | 1        | 0.1%    |
| Unknown                        | 1        | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 156      | 13.25%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 63       | 5.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 59       | 5.01%   |
| AMD FCH SATA Controller [IDE mode]                                               | 46       | 3.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 40       | 3.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 35       | 2.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 35       | 2.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 33       | 2.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 33       | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 30       | 2.55%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 26       | 2.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 26       | 2.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 23       | 1.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 22       | 1.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 19       | 1.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 18       | 1.53%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 18       | 1.53%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 18       | 1.53%   |
| AMD 400 Series Chipset SATA Controller                                           | 18       | 1.53%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 17       | 1.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 17       | 1.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 15       | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 15       | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 14       | 1.19%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 13       | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 13       | 1.1%    |
| Unknown                                                                          | 13       | 1.1%    |
| Intel SATA Controller [RAID mode]                                                | 12       | 1.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12       | 1.02%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 10       | 0.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10       | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                            | 9        | 0.76%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 9        | 0.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8        | 0.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8        | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 7        | 0.59%   |
| Samsung NVMe SSD Controller 980                                                  | 7        | 0.59%   |
| Phison PS5013 E13 NVMe Controller                                                | 7        | 0.59%   |
| Kingston Company A2000 NVMe SSD                                                  | 7        | 0.59%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 7        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 739      | 70.65%  |
| IDE  | 140      | 13.38%  |
| NVMe | 120      | 11.47%  |
| RAID | 39       | 3.73%   |
| SCSI | 5        | 0.48%   |
| SAS  | 3        | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 621      | 70.73%  |
| AMD    | 248      | 28.25%  |
| ARM    | 6        | 0.68%   |
| VIA    | 2        | 0.23%   |
| Sun    | 1        | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| AMD GX-412TC SOC                          | 91       | 10.31%  |
| Intel Celeron J4125 CPU @ 2.00GHz         | 36       | 4.08%   |
| Intel Celeron CPU J3160 @ 1.60GHz         | 20       | 2.27%   |
| Intel Celeron CPU J1900 @ 1.99GHz         | 20       | 2.27%   |
| AMD GX-415GA SOC with Radeon HD Graphics  | 20       | 2.27%   |
| Intel Celeron N5105 @ 2.00GHz             | 15       | 1.7%    |
| AMD GX-222GC SOC with Radeon R5E Graphics | 15       | 1.7%    |
| Intel Atom CPU D525 @ 1.80GHz             | 14       | 1.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz         | 11       | 1.25%   |
| Intel Celeron J4105 CPU @ 1.50GHz         | 11       | 1.25%   |
| Intel Core i7-7500U CPU @ 2.70GHz         | 10       | 1.13%   |
| Intel Celeron CPU J3455 @ 1.50GHz         | 10       | 1.13%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz        | 9        | 1.02%   |
| AMD G-T40E Processor                      | 9        | 1.02%   |
| Intel Core i5-8365U CPU @ 1.60GHz         | 8        | 0.91%   |
| Intel Core i5-6500 CPU @ 3.20GHz          | 8        | 0.91%   |
| Intel Celeron J4115 CPU @ 1.80GHz         | 8        | 0.91%   |
| Intel Core i7-7700 CPU @ 3.60GHz          | 7        | 0.79%   |
| Intel Core i5-3470 CPU @ 3.20GHz          | 7        | 0.79%   |
| Intel Celeron CPU N3150 @ 1.60GHz         | 7        | 0.79%   |
| AMD GX-420CA SOC with Radeon HD Graphics  | 7        | 0.79%   |
| Intel Core i3-7100U CPU @ 2.40GHz         | 6        | 0.68%   |
| Intel Atom CPU E3845 @ 1.91GHz            | 6        | 0.68%   |
| Intel Atom CPU C3558 @ 2.20GHz            | 6        | 0.68%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz       | 5        | 0.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz         | 5        | 0.57%   |
| Intel Core i7-4770 CPU @ 3.40GHz          | 5        | 0.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz          | 5        | 0.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz         | 5        | 0.57%   |
| Intel Core i5-8250U CPU @ 1.60GHz         | 5        | 0.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz         | 5        | 0.57%   |
| Intel Core i3-4130 CPU @ 3.40GHz          | 5        | 0.57%   |
| Intel Celeron CPU N3160 @ 1.60GHz         | 5        | 0.57%   |
| Intel Celeron CPU 3865U @ 1.80GHz         | 5        | 0.57%   |
| AMD FX-8350 Eight-Core Processor          | 5        | 0.57%   |
| Intel Xeon                                | 4        | 0.45%   |
| Intel Core i5-6400 CPU @ 2.70GHz          | 4        | 0.45%   |
| Intel Core i5-4590S CPU @ 3.00GHz         | 4        | 0.45%   |
| Intel Core i5 CPU 650 @ 3.20GHz           | 4        | 0.45%   |
| Intel Core i3-6100 CPU @ 3.70GHz          | 4        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 181      | 20.52%  |
| AMD GX                  | 144      | 16.33%  |
| Intel Core i5           | 138      | 15.65%  |
| Intel Core i3           | 77       | 8.73%   |
| Intel Core i7           | 62       | 7.03%   |
| Intel Xeon              | 54       | 6.12%   |
| Intel Atom              | 51       | 5.78%   |
| AMD Ryzen 7             | 18       | 2.04%   |
| AMD Ryzen 5             | 18       | 2.04%   |
| Other                   | 17       | 1.93%   |
| AMD G                   | 14       | 1.59%   |
| AMD FX                  | 14       | 1.59%   |
| Intel Pentium           | 13       | 1.47%   |
| Intel Core 2 Quad       | 8        | 0.91%   |
| Intel Pentium Silver    | 7        | 0.79%   |
| Intel Core 2 Duo        | 6        | 0.68%   |
| AMD Ryzen 5 PRO         | 6        | 0.68%   |
| Intel Pentium Gold      | 5        | 0.57%   |
| Intel Pentium Dual-Core | 4        | 0.45%   |
| ARM Cortex              | 4        | 0.45%   |
| AMD Ryzen 9             | 4        | 0.45%   |
| Intel Core i9           | 3        | 0.34%   |
| AMD Turion II Neo       | 3        | 0.34%   |
| AMD Ryzen Embedded      | 3        | 0.34%   |
| AMD Ryzen 3             | 3        | 0.34%   |
| AMD E                   | 3        | 0.34%   |
| AMD Athlon 64 X2        | 3        | 0.34%   |
| AMD A10                 | 3        | 0.34%   |
| AMD Ryzen Threadripper  | 2        | 0.23%   |
| AMD Ryzen 7 PRO         | 2        | 0.23%   |
| AMD Athlon Dual Core    | 2        | 0.23%   |
| AMD A8                  | 2        | 0.23%   |
| Intel Xeon Gold         | 1        | 0.11%   |
| Intel Pentium Dual      | 1        | 0.11%   |
| Intel Pentium 4         | 1        | 0.11%   |
| Intel Core 2            | 1        | 0.11%   |
| AMD Opteron             | 1        | 0.11%   |
| AMD Athlon X4           | 1        | 0.11%   |
| AMD Athlon              | 1        | 0.11%   |
| AMD A4                  | 1        | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 495      | 56.12%  |
| 2       | 246      | 27.89%  |
| 8       | 36       | 4.08%   |
| 6       | 32       | 3.63%   |
| 16      | 23       | 2.61%   |
| Unknown | 22       | 2.49%   |
| 12      | 14       | 1.59%   |
| 1       | 8        | 0.91%   |
| 32      | 4        | 0.45%   |
| 36      | 1        | 0.11%   |
| 10      | 1        | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 858      | 97.72%  |
| Unknown | 11       | 1.25%   |
| 2       | 9        | 1.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 583      | 66.4%   |
| 2       | 272      | 30.98%  |
| Unknown | 23       | 2.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 124      | 14.07%  |
| Puma          | 113      | 12.83%  |
| Silvermont    | 72       | 8.17%   |
| Haswell       | 63       | 7.15%   |
| Goldmont plus | 60       | 6.81%   |
| IvyBridge     | 52       | 5.9%    |
| Skylake       | 47       | 5.33%   |
| Unknown       | 40       | 4.54%   |
| Jaguar        | 32       | 3.63%   |
| Bonnell       | 32       | 3.63%   |
| Goldmont      | 27       | 3.06%   |
| Penryn        | 23       | 2.61%   |
| SandyBridge   | 22       | 2.5%    |
| Zen 2         | 18       | 2.04%   |
| Zen+          | 17       | 1.93%   |
| Bobcat        | 17       | 1.93%   |
| Zen           | 16       | 1.82%   |
| Piledriver    | 14       | 1.59%   |
| Core          | 13       | 1.48%   |
| Westmere      | 12       | 1.36%   |
| CometLake     | 11       | 1.25%   |
| Broadwell     | 11       | 1.25%   |
| IceLake       | 9        | 1.02%   |
| Nehalem       | 8        | 0.91%   |
| Zen 3         | 6        | 0.68%   |
| TigerLake     | 6        | 0.68%   |
| K8 Hammer     | 5        | 0.57%   |
| Bulldozer     | 4        | 0.45%   |
| K10           | 3        | 0.34%   |
| Steamroller   | 1        | 0.11%   |
| NetBurst      | 1        | 0.11%   |
| K10 Llano     | 1        | 0.11%   |
| Excavator     | 1        | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 514      | 67.72%  |
| AMD                                          | 126      | 16.6%   |
| Nvidia                                       | 66       | 8.7%    |
| ASPEED Technology                            | 27       | 3.56%   |
| Matrox Electronics Systems                   | 23       | 3.03%   |
| VIA Technologies                             | 2        | 0.26%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                      | 55       | 7.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 36       | 4.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 35       | 4.56%   |
| Intel HD Graphics 620                                                                    | 30       | 3.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 28       | 3.65%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 27       | 3.52%   |
| Intel HD Graphics 530                                                                    | 20       | 2.6%    |
| AMD Kabini [Radeon HD 8330E]                                                             | 20       | 2.6%    |
| Intel JasperLake [UHD Graphics]                                                          | 19       | 2.47%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 19       | 2.47%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 19       | 2.47%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 19       | 2.47%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18       | 2.34%   |
| Intel HD Graphics 500                                                                    | 17       | 2.21%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 15       | 1.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15       | 1.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13       | 1.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 12       | 1.56%   |
| Intel HD Graphics 630                                                                    | 11       | 1.43%   |
| Matrox Electronics Systems MGA G200EH                                                    | 10       | 1.3%    |
| Intel UHD Graphics 620                                                                   | 10       | 1.3%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 9        | 1.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9        | 1.17%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9        | 1.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9        | 1.17%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 9        | 1.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9        | 1.17%   |
| Intel HD Graphics 610                                                                    | 8        | 1.04%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8        | 1.04%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8        | 1.04%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 7        | 0.91%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 7        | 0.91%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 7        | 0.91%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7        | 0.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6        | 0.78%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 6        | 0.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6        | 0.78%   |
| Intel HD Graphics 5500                                                                   | 6        | 0.78%   |
| Intel HD Graphics 510                                                                    | 6        | 0.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 478      | 54.38%  |
| Other          | 131      | 14.9%   |
| 1 x AMD        | 124      | 14.11%  |
| 1 x Nvidia     | 59       | 6.71%   |
| 2 x Intel      | 25       | 2.84%   |
| 1 x ASPEED     | 25       | 2.84%   |
| 1 x Matrox     | 22       | 2.5%    |
| Intel + Nvidia | 7        | 0.8%    |
| 1 x VIA        | 2        | 0.23%   |
| Intel + ASPEED | 2        | 0.23%   |
| 2 x AMD        | 1        | 0.11%   |
| 1 x XGI        | 1        | 0.11%   |
| Intel + Matrox | 1        | 0.11%   |
| Intel + AMD    | 1        | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 700      | 79.64%  |
| Unknown     | 138      | 15.7%   |
| Proprietary | 41       | 4.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 819      | 92.44%  |
| 1.01-2.0   | 24       | 2.71%   |
| 3.01-4.0   | 12       | 1.35%   |
| 0.51-1.0   | 8        | 0.9%    |
| 7.01-8.0   | 7        | 0.79%   |
| 0.01-0.5   | 7        | 0.79%   |
| 5.01-6.0   | 5        | 0.56%   |
| 2.01-3.0   | 4        | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 18       | 17.82%  |
| Goldstar             | 11       | 10.89%  |
| Dell                 | 11       | 10.89%  |
| BenQ                 | 10       | 9.9%    |
| Ancor Communications | 7        | 6.93%   |
| Acer                 | 7        | 6.93%   |
| Eizo                 | 6        | 5.94%   |
| LG Electronics       | 5        | 4.95%   |
| Hewlett-Packard      | 5        | 4.95%   |
| Iiyama               | 4        | 3.96%   |
| NEC Computers        | 3        | 2.97%   |
| HannStar             | 2        | 1.98%   |
| Fujitsu Siemens      | 2        | 1.98%   |
| AOC                  | 2        | 1.98%   |
| WYT                  | 1        | 0.99%   |
| Philips              | 1        | 0.99%   |
| Mi                   | 1        | 0.99%   |
| LG Display           | 1        | 0.99%   |
| Lenovo               | 1        | 0.99%   |
| Idek Iiyama          | 1        | 0.99%   |
| Belinea              | 1        | 0.99%   |
| ASUSTek Computer     | 1        | 0.99%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch            | 3        | 2.73%   |
| Samsung Electronics C32JG5x SAM0FDE 2560x1440 700x390mm 31.5-inch     | 2        | 1.82%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch          | 2        | 1.82%   |
| Goldstar E2441 GSM581F 1920x1080 530x300mm 24.0-inch                  | 2        | 1.82%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                     | 2        | 1.82%   |
| Dell LCD Monitor U2412M 3840x1200                                     | 2        | 1.82%   |
| Dell LCD Monitor U2412M                                               | 2        | 1.82%   |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                     | 2        | 1.82%   |
| BenQ GL2760 BNQ78D5 1920x1080 600x340mm 27.2-inch                     | 2        | 1.82%   |
| BenQ GL2450H BNQ78A6 1920x1080 530x300mm 24.0-inch                    | 2        | 1.82%   |
| Ancor Communications MX27AQ ACI27A5 2560x1440 600x340mm 27.2-inch     | 2        | 1.82%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                  | 1        | 0.91%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1        | 0.91%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1        | 0.91%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 0.91%   |
| Samsung Electronics SyncMaster SAM036C 1920x1200 550x340mm 25.5-inch  | 1        | 0.91%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 600x340mm 27.2-inch   | 1        | 0.91%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 520x320mm 24.0-inch   | 1        | 0.91%   |
| Samsung Electronics SAMTRON STN0028 1280x1024 380x300mm 19.1-inch     | 1        | 0.91%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 480x270mm 21.7-inch | 1        | 0.91%   |
| Samsung Electronics S24C650 SAM09E9 1920x1080 520x290mm 23.4-inch     | 1        | 0.91%   |
| Samsung Electronics S24C650 SAM09E8 1920x1080 520x290mm 23.4-inch     | 1        | 0.91%   |
| Samsung Electronics S24C650 SAM09E7 1920x1080 520x290mm 23.4-inch     | 1        | 0.91%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 480x270mm 21.7-inch     | 1        | 0.91%   |
| Samsung Electronics LCD Monitor T27C370 1920x1080                     | 1        | 0.91%   |
| Samsung Electronics LCD Monitor SMB2430L 1920x1080                    | 1        | 0.91%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 890x500mm 40.2-inch | 1        | 0.91%   |
| Samsung Electronics LCD Monitor CF791 3440x1440                       | 1        | 0.91%   |
| Samsung Electronics CF791 SAM0DC3 3440x1440 800x330mm 34.1-inch       | 1        | 0.91%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 600x340mm 27.2-inch     | 1        | 0.91%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1        | 0.91%   |
| Philips LCD Monitor PHL086D 1440x900 400x250mm 18.6-inch              | 1        | 0.91%   |
| NEC Computers LCD1970NX NEC6662 1280x1024 380x300mm 19.1-inch         | 1        | 0.91%   |
| NEC Computers EX341R NEC2C7A 3440x1440 800x330mm 34.1-inch            | 1        | 0.91%   |
| NEC Computers EA243WM NEC6866 1920x1200 520x320mm 24.0-inch           | 1        | 0.91%   |
| Mi Monitor XMI23C3 1920x1080 530x290mm 23.8-inch                      | 1        | 0.91%   |
| LG Electronics LCD Monitor W2443 3600x1080                            | 1        | 0.91%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 3440x1440                     | 1        | 0.91%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                      | 1        | 0.91%   |
| LG Electronics LCD Monitor LG TV SSCR 1280x1024                       | 1        | 0.91%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 42       | 40.78%  |
| 3840x2160 (4K)     | 12       | 11.65%  |
| 2560x1440 (QHD)    | 12       | 11.65%  |
| 1920x1200 (WUXGA)  | 12       | 11.65%  |
| 1280x1024 (SXGA)   | 7        | 6.8%    |
| 3440x1440          | 4        | 3.88%   |
| 1680x1050 (WSXGA+) | 3        | 2.91%   |
| Unknown            | 3        | 2.91%   |
| 3840x1200          | 2        | 1.94%   |
| 2560x1080          | 2        | 1.94%   |
| 1440x900 (WXGA+)   | 2        | 1.94%   |
| 3600x1080          | 1        | 0.97%   |
| 1366x768 (WXGA)    | 1        | 0.97%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 25       | 24.75%  |
| 24      | 24       | 23.76%  |
| Unknown | 12       | 11.88%  |
| 21      | 10       | 9.9%    |
| 23      | 8        | 7.92%   |
| 19      | 5        | 4.95%   |
| 34      | 4        | 3.96%   |
| 22      | 3        | 2.97%   |
| 31      | 2        | 1.98%   |
| 25      | 2        | 1.98%   |
| 46      | 1        | 0.99%   |
| 32      | 1        | 0.99%   |
| 18      | 1        | 0.99%   |
| 17      | 1        | 0.99%   |
| 16      | 1        | 0.99%   |
| 13      | 1        | 0.99%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 55       | 55%     |
| 401-500     | 13       | 13%     |
| Unknown     | 12       | 12%     |
| 601-700     | 6        | 6%      |
| 701-800     | 5        | 5%      |
| 351-400     | 5        | 5%      |
| 301-350     | 3        | 3%      |
| 1001-1500   | 1        | 1%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 60       | 61.22%  |
| 16/10   | 16       | 16.33%  |
| Unknown | 11       | 11.22%  |
| 5/4     | 5        | 5.1%    |
| 21/9    | 4        | 4.08%   |
| 6/5     | 1        | 1.02%   |
| 3/2     | 1        | 1.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 34       | 34%     |
| 301-350        | 25       | 25%     |
| 251-300        | 12       | 12%     |
| Unknown        | 12       | 12%     |
| 351-500        | 7        | 7%      |
| 151-200        | 6        | 6%      |
| 81-90          | 1        | 1%      |
| 141-150        | 1        | 1%      |
| 131-140        | 1        | 1%      |
| 501-1000       | 1        | 1%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 56       | 55.45%  |
| 101-120 | 21       | 20.79%  |
| Unknown | 12       | 11.88%  |
| 161-240 | 6        | 5.94%   |
| 121-160 | 5        | 4.95%   |
| 1-50    | 1        | 0.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 782      | 88.76%  |
| 1     | 88       | 9.99%   |
| 2     | 10       | 1.14%   |
| 3     | 1        | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 695      | 59.1%   |
| Realtek Semiconductor             | 306      | 26.02%  |
| Qualcomm Atheros                  | 52       | 4.42%   |
| Broadcom                          | 41       | 3.49%   |
| IMC Networks                      | 13       | 1.11%   |
| American Megatrends               | 7        | 0.6%    |
| Mellanox Technologies             | 6        | 0.51%   |
| D-Link System                     | 6        | 0.51%   |
| TP-Link                           | 5        | 0.43%   |
| Marvell Technology Group          | 5        | 0.43%   |
| U-Blox                            | 4        | 0.34%   |
| Ralink                            | 4        | 0.34%   |
| Edimax Technology                 | 4        | 0.34%   |
| MediaTek                          | 3        | 0.26%   |
| ICS Advent                        | 2        | 0.17%   |
| Aquantia                          | 2        | 0.17%   |
| Xiaomi                            | 1        | 0.09%   |
| T & A Mobile Phones               | 1        | 0.09%   |
| SysKonnect                        | 1        | 0.09%   |
| Standard Microsystems [SMC]       | 1        | 0.09%   |
| Samsung Electronics               | 1        | 0.09%   |
| Ralink Technology                 | 1        | 0.09%   |
| Qualcomm Atheros Communications   | 1        | 0.09%   |
| QLogic                            | 1        | 0.09%   |
| Oculus VR                         | 1        | 0.09%   |
| NetXen Incorporated               | 1        | 0.09%   |
| Huawei Technologies               | 1        | 0.09%   |
| Ericsson Business Mobile Networks | 1        | 0.09%   |
| Emulex                            | 1        | 0.09%   |
| Dresden Elektronik                | 1        | 0.09%   |
| Digium                            | 1        | 0.09%   |
| Digital Equipment                 | 1        | 0.09%   |
| Dell                              | 1        | 0.09%   |
| Davicom Semiconductor             | 1        | 0.09%   |
| Chelsio Communications            | 1        | 0.09%   |
| ASUSTek Computer                  | 1        | 0.09%   |
| Accton Technology                 | 1        | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 265      | 19.16%  |
| Intel I211 Gigabit Network Connection                                         | 197      | 14.24%  |
| Intel I210 Gigabit Network Connection                                         | 119      | 8.6%    |
| Intel 82574L Gigabit Network Connection                                       | 54       | 3.9%    |
| Intel I350 Gigabit Network Connection                                         | 52       | 3.76%   |
| Intel Ethernet Controller I225-V                                              | 40       | 2.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 30       | 2.17%   |
| Realtek RTL8125 2.5GbE Controller                                             | 25       | 1.81%   |
| Intel 82580 Gigabit Network Connection                                        | 24       | 1.74%   |
| Intel 82576 Gigabit Network Connection                                        | 24       | 1.74%   |
| Intel 82583V Gigabit Network Connection                                       | 23       | 1.66%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 20       | 1.45%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 17       | 1.23%   |
| Intel Wi-Fi 6 AX200                                                           | 16       | 1.16%   |
| Intel Ethernet Connection (2) I219-V                                          | 15       | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 14       | 1.01%   |
| Intel Ethernet Connection I217-LM                                             | 13       | 0.94%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 12       | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                                         | 10       | 0.72%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 10       | 0.72%   |
| Intel Ethernet Connection (7) I219-V                                          | 9        | 0.65%   |
| Intel Ethernet Controller X550                                                | 8        | 0.58%   |
| Intel Ethernet Controller I226-V                                              | 8        | 0.58%   |
| Intel Ethernet Connection I219-LM                                             | 8        | 0.58%   |
| Intel Ethernet Connection I217-V                                              | 8        | 0.58%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 8        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 7        | 0.51%   |
| Intel Ethernet Connection X553 1GbE                                           | 7        | 0.51%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 7        | 0.51%   |
| American Megatrends Virtual Ethernet                                          | 7        | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 6        | 0.43%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 6        | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                                         | 6        | 0.43%   |
| Intel Centrino Advanced-N 6235                                                | 6        | 0.43%   |
| Intel 82579V Gigabit Network Connection                                       | 6        | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 5        | 0.36%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 5        | 0.36%   |
| Intel Wireless-AC 9260                                                        | 5        | 0.36%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 5        | 0.36%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 5        | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 57       | 33.33%  |
| Qualcomm Atheros                | 45       | 26.32%  |
| Realtek Semiconductor           | 26       | 15.2%   |
| IMC Networks                    | 13       | 7.6%    |
| Broadcom                        | 9        | 5.26%   |
| TP-Link                         | 5        | 2.92%   |
| Ralink                          | 4        | 2.34%   |
| Edimax Technology               | 4        | 2.34%   |
| MediaTek                        | 3        | 1.75%   |
| Ralink Technology               | 1        | 0.58%   |
| Qualcomm Atheros Communications | 1        | 0.58%   |
| Dell                            | 1        | 0.58%   |
| ASUSTek Computer                | 1        | 0.58%   |
| Accton Technology               | 1        | 0.58%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 16       | 9.2%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 14       | 8.05%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 12       | 6.9%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 6        | 3.45%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 6        | 3.45%   |
| Intel Centrino Advanced-N 6235                                  | 6        | 3.45%   |
| Intel Wireless-AC 9260                                          | 5        | 2.87%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 4        | 2.3%    |
| Intel Wireless 3160                                             | 4        | 2.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 4        | 2.3%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 3        | 1.72%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                       | 3        | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 3        | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 3        | 1.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 3        | 1.72%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 3        | 1.72%   |
| Intel Wireless 7265                                             | 3        | 1.72%   |
| Intel Wireless 7260                                             | 3        | 1.72%   |
| Intel Wireless 3165                                             | 3        | 1.72%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 3        | 1.72%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                             | 2        | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2        | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 2        | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 2        | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 2        | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 2        | 1.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 2        | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 2        | 1.15%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter      | 2        | 1.15%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 2        | 1.15%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]        | 2        | 1.15%   |
| Broadcom BCM43228 802.11a/b/g/n                                 | 2        | 1.15%   |
| Broadcom BCM43224 802.11a/b/g/n                                 | 2        | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter             | 2        | 1.15%   |
| TP-Link TP-Link Wireless MU-MIMO USB Adapter                    | 1        | 0.57%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                     | 1        | 0.57%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                           | 1        | 0.57%   |
| TP-Link 802.11ac WLAN Adapter 802.11ac WLAN Adapter             | 1        | 0.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 1        | 0.57%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter             | 1        | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 661      | 64.68%  |
| Realtek Semiconductor       | 294      | 28.77%  |
| Broadcom                    | 32       | 3.13%   |
| Qualcomm Atheros            | 7        | 0.68%   |
| American Megatrends         | 7        | 0.68%   |
| Marvell Technology Group    | 5        | 0.49%   |
| D-Link System               | 4        | 0.39%   |
| ICS Advent                  | 2        | 0.2%    |
| Aquantia                    | 2        | 0.2%    |
| Xiaomi                      | 1        | 0.1%    |
| T & A Mobile Phones         | 1        | 0.1%    |
| SysKonnect                  | 1        | 0.1%    |
| Standard Microsystems [SMC] | 1        | 0.1%    |
| Samsung Electronics         | 1        | 0.1%    |
| QLogic                      | 1        | 0.1%    |
| Digital Equipment           | 1        | 0.1%    |
| Davicom Semiconductor       | 1        | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 265      | 22.36%  |
| Intel I211 Gigabit Network Connection                                         | 197      | 16.62%  |
| Intel I210 Gigabit Network Connection                                         | 119      | 10.04%  |
| Intel 82574L Gigabit Network Connection                                       | 54       | 4.56%   |
| Intel I350 Gigabit Network Connection                                         | 52       | 4.39%   |
| Intel Ethernet Controller I225-V                                              | 40       | 3.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 30       | 2.53%   |
| Realtek RTL8125 2.5GbE Controller                                             | 24       | 2.03%   |
| Intel 82580 Gigabit Network Connection                                        | 24       | 2.03%   |
| Intel 82576 Gigabit Network Connection                                        | 24       | 2.03%   |
| Intel 82583V Gigabit Network Connection                                       | 23       | 1.94%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 20       | 1.69%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 17       | 1.43%   |
| Intel Ethernet Connection (2) I219-V                                          | 15       | 1.27%   |
| Intel Ethernet Connection I217-LM                                             | 13       | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                                         | 10       | 0.84%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 10       | 0.84%   |
| Intel Ethernet Connection (7) I219-V                                          | 9        | 0.76%   |
| Intel Ethernet Controller X550                                                | 8        | 0.68%   |
| Intel Ethernet Controller I226-V                                              | 8        | 0.68%   |
| Intel Ethernet Connection I219-LM                                             | 8        | 0.68%   |
| Intel Ethernet Connection I217-V                                              | 8        | 0.68%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 8        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 7        | 0.59%   |
| Intel Ethernet Connection X553 1GbE                                           | 7        | 0.59%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 7        | 0.59%   |
| American Megatrends Virtual Ethernet                                          | 7        | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                                         | 6        | 0.51%   |
| Intel 82579V Gigabit Network Connection                                       | 6        | 0.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 5        | 0.42%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 5        | 0.42%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 5        | 0.42%   |
| Intel Ethernet Connection (14) I219-V                                         | 5        | 0.42%   |
| Intel 82578DM Gigabit Network Connection                                      | 5        | 0.42%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 4        | 0.34%   |
| Intel 82576NS Gigabit Network Connection                                      | 4        | 0.34%   |
| Intel 82567V-3 Gigabit Network Connection                                     | 4        | 0.34%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 4        | 0.34%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 4        | 0.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 3        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 870      | 82.7%   |
| WiFi     | 160      | 15.21%  |
| Unknown  | 15       | 1.43%   |
| Modem    | 7        | 0.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 854      | 97.49%  |
| WiFi     | 21       | 2.4%    |
| Unknown  | 1        | 0.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 185      | 20.88%  |
| 3     | 164      | 18.51%  |
| 2     | 146      | 16.48%  |
| 1     | 132      | 14.9%   |
| 6     | 114      | 12.87%  |
| 5     | 82       | 9.26%   |
| 8     | 20       | 2.26%   |
| 7     | 16       | 1.81%   |
| 10    | 11       | 1.24%   |
| 0     | 7        | 0.79%   |
| 9     | 6        | 0.68%   |
| 12    | 2        | 0.23%   |
| 11    | 1        | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 721      | 78.88%  |
| Yes  | 193      | 21.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 49       | 56.98%  |
| Qualcomm Atheros Communications | 10       | 11.63%  |
| IMC Networks                    | 9        | 10.47%  |
| ASUSTek Computer                | 5        | 5.81%   |
| Broadcom                        | 4        | 4.65%   |
| MediaTek                        | 3        | 3.49%   |
| Realtek Semiconductor           | 2        | 2.33%   |
| Apple                           | 2        | 2.33%   |
| Micro Star International        | 1        | 1.16%   |
| Foxconn / Hon Hai               | 1        | 1.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                       | 17       | 19.54%  |
| Intel Bluetooth wireless interface                          | 10       | 11.49%  |
| Intel Centrino Bluetooth Wireless Transceiver               | 8        | 9.2%    |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 6        | 6.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 5        | 5.75%   |
| Intel Wireless-AC 3168 Bluetooth                            | 4        | 4.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4        | 4.6%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3        | 3.45%   |
| MediaTek Wireless_Device                                    | 3        | 3.45%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 2        | 2.3%    |
| Broadcom BCM2045 Bluetooth                                  | 2        | 2.3%    |
| ASUS ASUS USB-BT500                                         | 2        | 2.3%    |
| Realtek  Bluetooth Adapter                                  | 1        | 1.15%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1        | 1.15%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1        | 1.15%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1        | 1.15%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1        | 1.15%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1        | 1.15%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1        | 1.15%   |
| Micro Star International MS-6970 BToes Bluetooth adapter    | 1        | 1.15%   |
| Intel AX210 Bluetooth                                       | 1        | 1.15%   |
| Intel AX201 Bluetooth                                       | 1        | 1.15%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1        | 1.15%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                  | 1        | 1.15%   |
| IMC Networks Bluetooth                                      | 1        | 1.15%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1        | 1.15%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1        | 1.15%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1        | 1.15%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                | 1        | 1.15%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 1.15%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE       | 1        | 1.15%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 1.15%   |
| Apple Bluetooth Host Controller                             | 1        | 1.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 441      | 64.19%  |
| AMD                                          | 148      | 21.54%  |
| Nvidia                                       | 58       | 8.44%   |
| C-Media Electronics                          | 9        | 1.31%   |
| Logitech                                     | 4        | 0.58%   |
| JMTek                                        | 4        | 0.58%   |
| VIA Technologies                             | 3        | 0.44%   |
| Texas Instruments                            | 2        | 0.29%   |
| Kingston Technology                          | 2        | 0.29%   |
| GN Netcom                                    | 2        | 0.29%   |
| Creative Labs                                | 2        | 0.29%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.15%   |
| ZOOM                                         | 1        | 0.15%   |
| Yamaha                                       | 1        | 0.15%   |
| Trust                                        | 1        | 0.15%   |
| Tenx Technology                              | 1        | 0.15%   |
| Native Instruments                           | 1        | 0.15%   |
| M-Audio                                      | 1        | 0.15%   |
| Creative Technology                          | 1        | 0.15%   |
| Corsair                                      | 1        | 0.15%   |
| Blue Microphones                             | 1        | 0.15%   |
| AudioQuest                                   | 1        | 0.15%   |
| Audient                                      | 1        | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 51       | 6.26%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 49       | 6.01%   |
| AMD Kabini HDMI/DP Audio                                                                          | 49       | 6.01%   |
| AMD FCH Azalia Controller                                                                         | 38       | 4.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 36       | 4.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 30       | 3.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 29       | 3.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23       | 2.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 23       | 2.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 20       | 2.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 20       | 2.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20       | 2.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 20       | 2.45%   |
| Intel Jasper Lake HD Audio                                                                        | 19       | 2.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 17       | 2.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 17       | 2.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 17       | 2.09%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 16       | 1.96%   |
| Intel 200 Series PCH HD Audio                                                                     | 15       | 1.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 15       | 1.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 15       | 1.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14       | 1.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 11       | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11       | 1.35%   |
| Intel 8 Series HD Audio Controller                                                                | 10       | 1.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9        | 1.1%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9        | 1.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9        | 1.1%    |
| Intel Broadwell-U Audio Controller                                                                | 8        | 0.98%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8        | 0.98%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 7        | 0.86%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7        | 0.86%   |
| AMD Wrestler HDMI Audio                                                                           | 7        | 0.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7        | 0.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7        | 0.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 7        | 0.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6        | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5        | 0.61%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5        | 0.61%   |
| Intel Comet Lake PCH cAVS                                                                         | 5        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Samsung Electronics        | 149      | 17.33%  |
| Unknown                    | 147      | 17.09%  |
| Kingston                   | 110      | 12.79%  |
| Crucial                    | 108      | 12.56%  |
| SK hynix                   | 75       | 8.72%   |
| Micron Technology          | 60       | 6.98%   |
| G.Skill                    | 60       | 6.98%   |
| Corsair                    | 38       | 4.42%   |
| Unknown                    | 19       | 2.21%   |
| Unknown (ABCD)             | 12       | 1.4%    |
| Nanya Technology           | 12       | 1.4%    |
| ATP                        | 12       | 1.4%    |
| A-DATA Technology          | 8        | 0.93%   |
| Transcend                  | 7        | 0.81%   |
| Ramaxel Technology         | 5        | 0.58%   |
| Hewlett-Packard            | 5        | 0.58%   |
| Apacer                     | 5        | 0.58%   |
| Shenzhen Jinge Information | 3        | 0.35%   |
| Kimtigo                    | 3        | 0.35%   |
| Avant                      | 3        | 0.35%   |
| Teikon                     | 2        | 0.23%   |
| Patriot                    | 2        | 0.23%   |
| Unknown (7F7F7F94FFFFFFFF) | 1        | 0.12%   |
| Unknown (0x0C26)           | 1        | 0.12%   |
| Unknown (09C7)             | 1        | 0.12%   |
| Tigo                       | 1        | 0.12%   |
| TakeMS                     | 1        | 0.12%   |
| Qimonda                    | 1        | 0.12%   |
| Kingmax                    | 1        | 0.12%   |
| Innodisk                   | 1        | 0.12%   |
| Hyundai lnc                | 1        | 0.12%   |
| HPE                        | 1        | 0.12%   |
| Goldenmars                 | 1        | 0.12%   |
| GeIL                       | 1        | 0.12%   |
| Elpida                     | 1        | 0.12%   |
| DSL Memory                 | 1        | 0.12%   |
| DSL                        | 1        | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 35       | 3.85%   |
| Unknown                                                      | 19       | 2.09%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 12       | 1.32%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 10       | 1.1%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 9        | 0.99%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s           | 9        | 0.99%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 7        | 0.77%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 7        | 0.77%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 7        | 0.77%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s        | 7        | 0.77%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s        | 7        | 0.77%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                   | 6        | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 6        | 0.66%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3200MT/s         | 6        | 0.66%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s            | 6        | 0.66%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s        | 6        | 0.66%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                   | 5        | 0.55%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 5        | 0.55%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 5        | 0.55%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 5        | 0.55%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s        | 5        | 0.55%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s        | 5        | 0.55%   |
| ATP RAM X4G08QA8BNWESO-7-TO1 8GB SODIMM DDR4 3200MT/s        | 5        | 0.55%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 4        | 0.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 4        | 0.44%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 4        | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                     | 4        | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                   | 4        | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                  | 4        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                     | 4        | 0.44%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 4        | 0.44%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 4        | 0.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s          | 4        | 0.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 4        | 0.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 4        | 0.44%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 4        | 0.44%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s          | 4        | 0.44%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3                   | 4        | 0.44%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s        | 4        | 0.44%   |
| G.Skill RAM F4-2400C16-8GRS 8GB SODIMM DDR4 2400MT/s         | 4        | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 372      | 47.09%  |
| DDR4    | 316      | 40%     |
| DDR2    | 35       | 4.43%   |
| LPDDR4  | 23       | 2.91%   |
| Unknown | 22       | 2.78%   |
| SDRAM   | 18       | 2.28%   |
| DDR     | 4        | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 426      | 54.27%  |
| SODIMM       | 342      | 43.57%  |
| Row Of Chips | 11       | 1.4%    |
| Unknown      | 5        | 0.64%   |
| FB-DIMM      | 1        | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 294      | 35.51%  |
| 4096  | 291      | 35.14%  |
| 16384 | 112      | 13.53%  |
| 2048  | 98       | 11.84%  |
| 32768 | 16       | 1.93%   |
| 1024  | 15       | 1.81%   |
| 512   | 2        | 0.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 225      | 27.31%  |
| 1333    | 125      | 15.17%  |
| 2400    | 122      | 14.81%  |
| 2667    | 86       | 10.44%  |
| 3200    | 73       | 8.86%   |
| 2133    | 39       | 4.73%   |
| 800     | 32       | 3.88%   |
| 667     | 27       | 3.28%   |
| Unknown | 21       | 2.55%   |
| 1867    | 14       | 1.7%    |
| 1066    | 13       | 1.58%   |
| 2666    | 11       | 1.33%   |
| 3000    | 8        | 0.97%   |
| 2933    | 6        | 0.73%   |
| 1866    | 6        | 0.73%   |
| 3600    | 4        | 0.49%   |
| 1334    | 3        | 0.36%   |
| 533     | 2        | 0.24%   |
| 65535   | 1        | 0.12%   |
| 3534    | 1        | 0.12%   |
| 3500    | 1        | 0.12%   |
| 1419    | 1        | 0.12%   |
| 1067    | 1        | 0.12%   |
| 1033    | 1        | 0.12%   |
| 333     | 1        | 0.12%   |

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
| 1     | 405      | 45.3%   |
| 0     | 371      | 41.5%   |
| 2     | 72       | 8.05%   |
| 3     | 25       | 2.8%    |
| 4     | 12       | 1.34%   |
| 5     | 9        | 1.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 448      | 71%     |
| Net/wireless             | 59       | 9.35%   |
| Bluetooth                | 41       | 6.5%    |
| Card reader              | 31       | 4.91%   |
| Firewire controller      | 14       | 2.22%   |
| Net/ethernet             | 12       | 1.9%    |
| Network                  | 9        | 1.43%   |
| Sound                    | 8        | 1.27%   |
| Graphics card            | 4        | 0.63%   |
| Storage/raid             | 1        | 0.16%   |
| Storage/ide              | 1        | 0.16%   |
| Storage/ata              | 1        | 0.16%   |
| Fingerprint reader       | 1        | 0.16%   |
| Dvb card                 | 1        | 0.16%   |

