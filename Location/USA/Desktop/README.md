BSD in USA - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for BSD in USA.

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

Total: 3872

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| AZW           | U59                         | [c8ffb92584](https://bsd-hardware.info/?probe=c8ffb92584) | Jan 02, 2024 |
| Protectli     | VP46xx                      | [f958569c30](https://bsd-hardware.info/?probe=f958569c30) | Jan 02, 2024 |
| Gowin Solu... | GW-MB-U01                   | [673266d486](https://bsd-hardware.info/?probe=673266d486) | Jan 01, 2024 |
| ASUSTek       | H97M-PLUS                   | [270a946916](https://bsd-hardware.info/?probe=270a946916) | Jan 01, 2024 |
| Alienware     | 07HV66 A00                  | [ea6a3f3020](https://bsd-hardware.info/?probe=ea6a3f3020) | Jan 01, 2024 |
| Protectli     | FW4B Ver                    | [3191952740](https://bsd-hardware.info/?probe=3191952740) | Jan 01, 2024 |
| MSI           | Z170A PC MATE               | [e05af13af9](https://bsd-hardware.info/?probe=e05af13af9) | Jan 01, 2024 |
| MSI           | Z270-A PRO                  | [2f2f406aa3](https://bsd-hardware.info/?probe=2f2f406aa3) | Dec 31, 2023 |
| MSI           | H81M-P33                    | [82e08820f2](https://bsd-hardware.info/?probe=82e08820f2) | Dec 31, 2023 |
| ASUSTek       | P5Q-E                       | [da3b88ef85](https://bsd-hardware.info/?probe=da3b88ef85) | Dec 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [391f4c0e0b](https://bsd-hardware.info/?probe=391f4c0e0b) | Dec 31, 2023 |
| Intel         | SHARKBAY                    | [bcbbfa0368](https://bsd-hardware.info/?probe=bcbbfa0368) | Dec 31, 2023 |
| Unknown       | Unknown                     | [56ecba336a](https://bsd-hardware.info/?probe=56ecba336a) | Dec 31, 2023 |
| ASUSTek       | CM6870                      | [1889675f37](https://bsd-hardware.info/?probe=1889675f37) | Dec 30, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | [715a274a2e](https://bsd-hardware.info/?probe=715a274a2e) | Dec 30, 2023 |
| Protectli     | FW4A Ver                    | [39c4ea3a24](https://bsd-hardware.info/?probe=39c4ea3a24) | Dec 30, 2023 |
| HP            | 3397                        | [46b6923bcd](https://bsd-hardware.info/?probe=46b6923bcd) | Dec 30, 2023 |
| Protectli     | FW2B Ver                    | [3dbf91e1d4](https://bsd-hardware.info/?probe=3dbf91e1d4) | Dec 30, 2023 |
| Unknown       | QDNV01                      | [d2fed4bb5f](https://bsd-hardware.info/?probe=d2fed4bb5f) | Dec 30, 2023 |
| HP            | 82B4                        | [de6046d060](https://bsd-hardware.info/?probe=de6046d060) | Dec 29, 2023 |
| PC Engines    | apu4                        | [3901782984](https://bsd-hardware.info/?probe=3901782984) | Dec 29, 2023 |
| Protectli     | VP2420                      | [39b80f6d35](https://bsd-hardware.info/?probe=39b80f6d35) | Dec 28, 2023 |
| HP            | 0B54h D                     | [0fc53a659f](https://bsd-hardware.info/?probe=0fc53a659f) | Dec 28, 2023 |
| Intel         | SHARKBAY                    | [55a9dc404b](https://bsd-hardware.info/?probe=55a9dc404b) | Dec 27, 2023 |
| Protectli     | VP2420                      | [a7e60ab925](https://bsd-hardware.info/?probe=a7e60ab925) | Dec 27, 2023 |
| HP            | 1998                        | [8bebbb8dab](https://bsd-hardware.info/?probe=8bebbb8dab) | Dec 27, 2023 |
| MSI           | Aspen                       | [ac6dd2b153](https://bsd-hardware.info/?probe=ac6dd2b153) | Dec 27, 2023 |
| Protectli     | FW4B                        | [cf4ead1922](https://bsd-hardware.info/?probe=cf4ead1922) | Dec 26, 2023 |
| Unknown       | Unknown                     | [48677111e5](https://bsd-hardware.info/?probe=48677111e5) | Dec 26, 2023 |
| Apple         | Mac-F221BEC8                | [d08712b71d](https://bsd-hardware.info/?probe=d08712b71d) | Dec 26, 2023 |
| Supermicro    | X11SDW-16C-TP13F+           | [49ed0c6dca](https://bsd-hardware.info/?probe=49ed0c6dca) | Dec 25, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | [304af7e00e](https://bsd-hardware.info/?probe=304af7e00e) | Dec 25, 2023 |
| Unknown       | QGLK03                      | [4be2a41109](https://bsd-hardware.info/?probe=4be2a41109) | Dec 25, 2023 |
| Unknown       | QGLK03                      | [b187a024cb](https://bsd-hardware.info/?probe=b187a024cb) | Dec 25, 2023 |
| Unknown       | QSKL01                      | [f69898815d](https://bsd-hardware.info/?probe=f69898815d) | Dec 25, 2023 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | [504fb1678f](https://bsd-hardware.info/?probe=504fb1678f) | Dec 24, 2023 |
| ASUSTek       | P5Q-E                       | [04675127c2](https://bsd-hardware.info/?probe=04675127c2) | Dec 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1ef7136151](https://bsd-hardware.info/?probe=1ef7136151) | Dec 24, 2023 |
| Dell          | 0KV62T A00                  | [5844adb190](https://bsd-hardware.info/?probe=5844adb190) | Dec 24, 2023 |
| ASRock        | Z77 Extreme3                | [1656e8f6b0](https://bsd-hardware.info/?probe=1656e8f6b0) | Dec 24, 2023 |
| Unknown       | QGLK03                      | [a586279dd0](https://bsd-hardware.info/?probe=a586279dd0) | Dec 24, 2023 |
| Unknown       | Unknown                     | [da2b7d434e](https://bsd-hardware.info/?probe=da2b7d434e) | Dec 24, 2023 |
| Dell          | 0NC2VH A01                  | [06828fbfed](https://bsd-hardware.info/?probe=06828fbfed) | Dec 23, 2023 |
| Dell          | 0NC2VH A01                  | [3c06ec4635](https://bsd-hardware.info/?probe=3c06ec4635) | Dec 23, 2023 |
| AZW           | EQ                          | [9818e5f996](https://bsd-hardware.info/?probe=9818e5f996) | Dec 23, 2023 |
| Unknown       | Unknown                     | [97559370a8](https://bsd-hardware.info/?probe=97559370a8) | Dec 23, 2023 |
| Protectli     | FW4B Ver                    | [4b6a62bebe](https://bsd-hardware.info/?probe=4b6a62bebe) | Dec 22, 2023 |
| Dell          | 00V62H A01                  | [c4e5366baa](https://bsd-hardware.info/?probe=c4e5366baa) | Dec 22, 2023 |
| Shuttle       | FS77U                       | [9c746c0d5c](https://bsd-hardware.info/?probe=9c746c0d5c) | Dec 21, 2023 |
| Dell          | 0KV62T A00                  | [8a2c7af96c](https://bsd-hardware.info/?probe=8a2c7af96c) | Dec 21, 2023 |
| PC Engines    | apu4                        | [7fa270657e](https://bsd-hardware.info/?probe=7fa270657e) | Dec 21, 2023 |
| Intel         | DH61AG AAG23736-400         | [e6a38faa07](https://bsd-hardware.info/?probe=e6a38faa07) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [f9fd749985](https://bsd-hardware.info/?probe=f9fd749985) | Dec 21, 2023 |
| Protectli     | VP2420                      | [9a4aba32a7](https://bsd-hardware.info/?probe=9a4aba32a7) | Dec 21, 2023 |
| Dell          | 0NV0M7 A01                  | [835ca2056c](https://bsd-hardware.info/?probe=835ca2056c) | Dec 21, 2023 |
| Protectli     | FW4B                        | [d67b8b063a](https://bsd-hardware.info/?probe=d67b8b063a) | Dec 21, 2023 |
| Dell          | 02YYK5 A01                  | [6e070fbb90](https://bsd-hardware.info/?probe=6e070fbb90) | Dec 20, 2023 |
| Acer          | Aspire XC-1660G V:1.1       | [54b2061c80](https://bsd-hardware.info/?probe=54b2061c80) | Dec 19, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [c00a69de7c](https://bsd-hardware.info/?probe=c00a69de7c) | Dec 19, 2023 |
| Advantech     | NAMB-3250 A102-1            | [bb91074237](https://bsd-hardware.info/?probe=bb91074237) | Dec 19, 2023 |
| Dell          | 04YP6J A02                  | [abcaede8e1](https://bsd-hardware.info/?probe=abcaede8e1) | Dec 19, 2023 |
| Protectli     | FW4A Ver                    | [9660edcc5c](https://bsd-hardware.info/?probe=9660edcc5c) | Dec 18, 2023 |
| Unknown       | Unknown                     | [107e747798](https://bsd-hardware.info/?probe=107e747798) | Dec 17, 2023 |
| ASUSTek       | P5Q-E                       | [5a4d01667e](https://bsd-hardware.info/?probe=5a4d01667e) | Dec 17, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ea79e98108](https://bsd-hardware.info/?probe=ea79e98108) | Dec 17, 2023 |
| ECS           | H81H3-WM                    | [9df1f030f9](https://bsd-hardware.info/?probe=9df1f030f9) | Dec 17, 2023 |
| Unknown       | Unknown                     | [88306fe484](https://bsd-hardware.info/?probe=88306fe484) | Dec 17, 2023 |
| Unknown       | Unknown                     | [6a3ef5165f](https://bsd-hardware.info/?probe=6a3ef5165f) | Dec 17, 2023 |
| Unknown       | Unknown                     | [cefdf7d9ca](https://bsd-hardware.info/?probe=cefdf7d9ca) | Dec 17, 2023 |
| Protectli     | FW4B                        | [b862c8c507](https://bsd-hardware.info/?probe=b862c8c507) | Dec 16, 2023 |
| Unknown       | Unknown                     | [df97b81bea](https://bsd-hardware.info/?probe=df97b81bea) | Dec 15, 2023 |
| AZW           | MINI S 10                   | [d8eee18baf](https://bsd-hardware.info/?probe=d8eee18baf) | Dec 15, 2023 |
| Unknown       | Unknown                     | [5adc44e122](https://bsd-hardware.info/?probe=5adc44e122) | Dec 15, 2023 |
| Techvision    | TVI7309X B0                 | [4b7be4588e](https://bsd-hardware.info/?probe=4b7be4588e) | Dec 15, 2023 |
| Unknown       | Unknown                     | [93f650efc3](https://bsd-hardware.info/?probe=93f650efc3) | Dec 15, 2023 |
| Gigabyte      | B75M-D3H                    | [9773ffcc27](https://bsd-hardware.info/?probe=9773ffcc27) | Dec 15, 2023 |
| Unknown       | Unknown                     | [a9f96c677c](https://bsd-hardware.info/?probe=a9f96c677c) | Dec 14, 2023 |
| CWWK          | MINIPC-G12                  | [e15a019715](https://bsd-hardware.info/?probe=e15a019715) | Dec 14, 2023 |
| Dell          | 0NK5PH A00                  | [60451d4e43](https://bsd-hardware.info/?probe=60451d4e43) | Dec 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [bc50d301fa](https://bsd-hardware.info/?probe=bc50d301fa) | Dec 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [dced442907](https://bsd-hardware.info/?probe=dced442907) | Dec 13, 2023 |
| Unknown       | Unknown                     | [b2407b8a31](https://bsd-hardware.info/?probe=b2407b8a31) | Dec 13, 2023 |
| Dell          | 02YYK5 A00                  | [8eb8c9eff3](https://bsd-hardware.info/?probe=8eb8c9eff3) | Dec 13, 2023 |
| Intel         | QHSW02                      | [da6b7c7115](https://bsd-hardware.info/?probe=da6b7c7115) | Dec 13, 2023 |
| ASRock        | H170M-ITX/DL                | [79039f6105](https://bsd-hardware.info/?probe=79039f6105) | Dec 13, 2023 |
| MSI           | B150 GAMING M3              | [b5dc4da596](https://bsd-hardware.info/?probe=b5dc4da596) | Dec 12, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | [c05c574f37](https://bsd-hardware.info/?probe=c05c574f37) | Dec 12, 2023 |
| EVGA          | X570 DARK.0                 | [1c84a8169b](https://bsd-hardware.info/?probe=1c84a8169b) | Dec 11, 2023 |
| Intel         | Q3XXG4-P V1.0               | [becfed036a](https://bsd-hardware.info/?probe=becfed036a) | Dec 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [68f73bf8ba](https://bsd-hardware.info/?probe=68f73bf8ba) | Dec 11, 2023 |
| ASRock        | H370M-ITX/ac                | [b806cc2a41](https://bsd-hardware.info/?probe=b806cc2a41) | Dec 10, 2023 |
| AZW           | EQ                          | [0280c1cdb9](https://bsd-hardware.info/?probe=0280c1cdb9) | Dec 10, 2023 |
| Unknown       | Unknown                     | [ec8c50c128](https://bsd-hardware.info/?probe=ec8c50c128) | Dec 10, 2023 |
| AZW           | EQ                          | [48537a5985](https://bsd-hardware.info/?probe=48537a5985) | Dec 10, 2023 |
| ASUSTek       | CM6870                      | [881ad2eacf](https://bsd-hardware.info/?probe=881ad2eacf) | Dec 10, 2023 |
| Dell          | 0YNVJG A02                  | [2d8992cd50](https://bsd-hardware.info/?probe=2d8992cd50) | Dec 10, 2023 |
| Unknown       | Unknown                     | [fc1097e9b0](https://bsd-hardware.info/?probe=fc1097e9b0) | Dec 10, 2023 |
| Unknown       | Unknown                     | [3e478d7459](https://bsd-hardware.info/?probe=3e478d7459) | Dec 10, 2023 |
| MSI           | H81M-P33                    | [2b1599aacd](https://bsd-hardware.info/?probe=2b1599aacd) | Dec 10, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [89f0463ec6](https://bsd-hardware.info/?probe=89f0463ec6) | Dec 10, 2023 |
| Unknown       | Unknown                     | [edfa10c0dd](https://bsd-hardware.info/?probe=edfa10c0dd) | Dec 10, 2023 |
| ASRock        | B660M Phantom Gaming 4      | [e71ffa9a86](https://bsd-hardware.info/?probe=e71ffa9a86) | Dec 10, 2023 |
| ASRock        | Q1900B-ITX                  | [b7e23a4ed4](https://bsd-hardware.info/?probe=b7e23a4ed4) | Dec 10, 2023 |
| Dell          | 0HD5W2 A01                  | [3b6c1c2fbb](https://bsd-hardware.info/?probe=3b6c1c2fbb) | Dec 09, 2023 |
| ASUSTek       | CM6870                      | [78399ba39e](https://bsd-hardware.info/?probe=78399ba39e) | Dec 09, 2023 |
| Gigabyte      | B650 AORUS ELITE AX V2      | [7a6cdb3f06](https://bsd-hardware.info/?probe=7a6cdb3f06) | Dec 09, 2023 |
| Protectli     | FW4B Ver                    | [55094840ea](https://bsd-hardware.info/?probe=55094840ea) | Dec 09, 2023 |
| Unknown       | Unknown                     | [76f58e8986](https://bsd-hardware.info/?probe=76f58e8986) | Dec 09, 2023 |
| Dell          | 0D28YY A00                  | [20dbd4481a](https://bsd-hardware.info/?probe=20dbd4481a) | Dec 09, 2023 |
| Techvision    | TVI7309X B0                 | [8422bc152b](https://bsd-hardware.info/?probe=8422bc152b) | Dec 08, 2023 |
| Dell          | 00V62H A01                  | [a0591ac105](https://bsd-hardware.info/?probe=a0591ac105) | Dec 08, 2023 |
| ASRock        | Z370 Gaming K6              | [2074ab8412](https://bsd-hardware.info/?probe=2074ab8412) | Dec 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | [050e7d8c01](https://bsd-hardware.info/?probe=050e7d8c01) | Dec 08, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | [cf3304bda2](https://bsd-hardware.info/?probe=cf3304bda2) | Dec 08, 2023 |
| Dell          | 03NVJ6 A03                  | [c119d3003e](https://bsd-hardware.info/?probe=c119d3003e) | Dec 07, 2023 |
| Protectli     | VP46xx                      | [5051678913](https://bsd-hardware.info/?probe=5051678913) | Dec 07, 2023 |
| PC Engines    | APU2                        | [92c3ba510a](https://bsd-hardware.info/?probe=92c3ba510a) | Dec 07, 2023 |
| Unknown       | Unknown                     | [23b689f778](https://bsd-hardware.info/?probe=23b689f778) | Dec 07, 2023 |
| Techvision    | TVI7309X B0                 | [c906f764b0](https://bsd-hardware.info/?probe=c906f764b0) | Dec 07, 2023 |
| HP            | 213D A01                    | [a7ded310e3](https://bsd-hardware.info/?probe=a7ded310e3) | Dec 07, 2023 |
| Unknown       | Unknown                     | [a11b04691d](https://bsd-hardware.info/?probe=a11b04691d) | Dec 07, 2023 |
| Unknown       | Unknown                     | [ac7f59dc32](https://bsd-hardware.info/?probe=ac7f59dc32) | Dec 06, 2023 |
| Unknown       | Unknown                     | [ef425e8732](https://bsd-hardware.info/?probe=ef425e8732) | Dec 05, 2023 |
| Unknown       | Unknown                     | [2301bb487f](https://bsd-hardware.info/?probe=2301bb487f) | Dec 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8c023b9c33](https://bsd-hardware.info/?probe=8c023b9c33) | Dec 05, 2023 |
| CWWK          | MINIPC-G12                  | [d6c18203b4](https://bsd-hardware.info/?probe=d6c18203b4) | Dec 04, 2023 |
| Lenovo        | XXXX FFFFFFFFFF             | [780619812e](https://bsd-hardware.info/?probe=780619812e) | Dec 04, 2023 |
| Lenovo        | XXXX FFFFFFFFFF             | [7ddfbf4af2](https://bsd-hardware.info/?probe=7ddfbf4af2) | Dec 04, 2023 |
| Protectli     | FW4B Ver                    | [267d300e4a](https://bsd-hardware.info/?probe=267d300e4a) | Dec 04, 2023 |
| GoWin Solu... | R86S                        | [494f638f4e](https://bsd-hardware.info/?probe=494f638f4e) | Dec 04, 2023 |
| Protectli     | FW6                         | [91d91ebf31](https://bsd-hardware.info/?probe=91d91ebf31) | Dec 04, 2023 |
| MiTAC         | UltraPoint                  | [346d03e78c](https://bsd-hardware.info/?probe=346d03e78c) | Dec 04, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [2fefe41bcd](https://bsd-hardware.info/?probe=2fefe41bcd) | Dec 03, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [d04fd54963](https://bsd-hardware.info/?probe=d04fd54963) | Dec 03, 2023 |
| AZW           | MINI S 10                   | [caf105bd1b](https://bsd-hardware.info/?probe=caf105bd1b) | Dec 02, 2023 |
| Intel         | D33217GKE G76540-207        | [761e1e0eae](https://bsd-hardware.info/?probe=761e1e0eae) | Dec 02, 2023 |
| Dell          | 0VRWRC A00                  | [8ffbff07d4](https://bsd-hardware.info/?probe=8ffbff07d4) | Dec 02, 2023 |
| HP            | 8265                        | [ec9e6fdd6e](https://bsd-hardware.info/?probe=ec9e6fdd6e) | Dec 02, 2023 |
| Protectli     | FW4C                        | [c3b8887f26](https://bsd-hardware.info/?probe=c3b8887f26) | Dec 02, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [baf3e413d0](https://bsd-hardware.info/?probe=baf3e413d0) | Dec 01, 2023 |
| AZW           | EQ                          | [1f66e98633](https://bsd-hardware.info/?probe=1f66e98633) | Dec 01, 2023 |
| ASRock        | H110M-HDS                   | [519a82f253](https://bsd-hardware.info/?probe=519a82f253) | Dec 01, 2023 |
| AZW           | EQ                          | [a2f18cb86e](https://bsd-hardware.info/?probe=a2f18cb86e) | Nov 30, 2023 |
| Protectli     | FW6 Ver                     | [78fef35503](https://bsd-hardware.info/?probe=78fef35503) | Nov 30, 2023 |
| MUCAI         | H61 V1.6A                   | [8dfd16da29](https://bsd-hardware.info/?probe=8dfd16da29) | Nov 29, 2023 |
| Deciso        | Netboard A8                 | [53d89587d0](https://bsd-hardware.info/?probe=53d89587d0) | Nov 28, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [d45a39836c](https://bsd-hardware.info/?probe=d45a39836c) | Nov 28, 2023 |
| Unknown       | Unknown                     | [97fc765ff5](https://bsd-hardware.info/?probe=97fc765ff5) | Nov 28, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [30e336f42f](https://bsd-hardware.info/?probe=30e336f42f) | Nov 28, 2023 |
| Intel         | Q3XXG4-P V1.0               | [be0344dcf2](https://bsd-hardware.info/?probe=be0344dcf2) | Nov 28, 2023 |
| GoWin Solu... | R86S-N                      | [1d40615c24](https://bsd-hardware.info/?probe=1d40615c24) | Nov 27, 2023 |
| WTM           | BKHD-N5105-5LAN B0          | [4d58c53d68](https://bsd-hardware.info/?probe=4d58c53d68) | Nov 27, 2023 |
| Lenovo        | ThinkServer TS140           | [af326ddda5](https://bsd-hardware.info/?probe=af326ddda5) | Nov 27, 2023 |
| Lenovo        | 1036 NO DPK                 | [3b18ff26c0](https://bsd-hardware.info/?probe=3b18ff26c0) | Nov 27, 2023 |
| Unknown       | Unknown                     | [14c7b94add](https://bsd-hardware.info/?probe=14c7b94add) | Nov 26, 2023 |
| Intel         | D33217GKE G76540-207        | [9b0af83da8](https://bsd-hardware.info/?probe=9b0af83da8) | Nov 26, 2023 |
| MSI           | H81M-P33                    | [b653e75063](https://bsd-hardware.info/?probe=b653e75063) | Nov 26, 2023 |
| ASUSTek       | P5Q-E                       | [1454187842](https://bsd-hardware.info/?probe=1454187842) | Nov 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [28f6ec2a7b](https://bsd-hardware.info/?probe=28f6ec2a7b) | Nov 26, 2023 |
| Protectli     | FW6 Ver                     | [7241023750](https://bsd-hardware.info/?probe=7241023750) | Nov 26, 2023 |
| Dell          | 0XCR8D A01                  | [de52fe9aef](https://bsd-hardware.info/?probe=de52fe9aef) | Nov 26, 2023 |
| Unknown       | Unknown                     | [c3dc51f3fe](https://bsd-hardware.info/?probe=c3dc51f3fe) | Nov 25, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [be568b54bf](https://bsd-hardware.info/?probe=be568b54bf) | Nov 25, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [ece72d8870](https://bsd-hardware.info/?probe=ece72d8870) | Nov 24, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | [b479df9cfc](https://bsd-hardware.info/?probe=b479df9cfc) | Nov 24, 2023 |
| Techvision    | TVI7309X B0                 | [b7e6b2579a](https://bsd-hardware.info/?probe=b7e6b2579a) | Nov 24, 2023 |
| ASRock        | X399 Professional Gaming    | [9c9645e87a](https://bsd-hardware.info/?probe=9c9645e87a) | Nov 23, 2023 |
| CWWK          | MINIPC-G12                  | [2756c10ff8](https://bsd-hardware.info/?probe=2756c10ff8) | Nov 23, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [d883d8bbd1](https://bsd-hardware.info/?probe=d883d8bbd1) | Nov 23, 2023 |
| HP            | 8767 A                      | [12aa6c74c7](https://bsd-hardware.info/?probe=12aa6c74c7) | Nov 23, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [086dd66ae7](https://bsd-hardware.info/?probe=086dd66ae7) | Nov 22, 2023 |
| Dell          | 0GY6Y8 A00                  | [8181170ec9](https://bsd-hardware.info/?probe=8181170ec9) | Nov 22, 2023 |
| Cisco         | ASA5525 A0                  | [0e4aa1cec5](https://bsd-hardware.info/?probe=0e4aa1cec5) | Nov 22, 2023 |
| ASRock        | Z490M-ITX/ac                | [2c256503f5](https://bsd-hardware.info/?probe=2c256503f5) | Nov 22, 2023 |
| MUCAI         | H61 V1.6A                   | [f750403713](https://bsd-hardware.info/?probe=f750403713) | Nov 21, 2023 |
| CWWK          | MINIPC-G4                   | [d9b122a533](https://bsd-hardware.info/?probe=d9b122a533) | Nov 21, 2023 |
| Pegatron      | TRUCKEE                     | [9f4c9969f1](https://bsd-hardware.info/?probe=9f4c9969f1) | Nov 21, 2023 |
| Pegatron      | TRUCKEE                     | [8c8daeff55](https://bsd-hardware.info/?probe=8c8daeff55) | Nov 21, 2023 |
| Protectli     | FW4C                        | [7fa5301a63](https://bsd-hardware.info/?probe=7fa5301a63) | Nov 20, 2023 |
| AZW           | EQ                          | [cb2efd436d](https://bsd-hardware.info/?probe=cb2efd436d) | Nov 20, 2023 |
| Unknown       | Unknown                     | [6e5266f2a1](https://bsd-hardware.info/?probe=6e5266f2a1) | Nov 20, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [4b6284d041](https://bsd-hardware.info/?probe=4b6284d041) | Nov 20, 2023 |
| AZW           | EQ                          | [adcc84f66a](https://bsd-hardware.info/?probe=adcc84f66a) | Nov 20, 2023 |
| Supermicro    | A2SAP-HA                    | [c912b74149](https://bsd-hardware.info/?probe=c912b74149) | Nov 20, 2023 |
| AZW           | EQ                          | [9f0dd7c0b4](https://bsd-hardware.info/?probe=9f0dd7c0b4) | Nov 20, 2023 |
| ASRock        | Z370 Gaming K6              | [0b219600a3](https://bsd-hardware.info/?probe=0b219600a3) | Nov 19, 2023 |
| Protectli     | VP2420                      | [42bac7a450](https://bsd-hardware.info/?probe=42bac7a450) | Nov 19, 2023 |
| Protectli     | FW4B Ver                    | [41bb4c277b](https://bsd-hardware.info/?probe=41bb4c277b) | Nov 19, 2023 |
| MSI           | H81M-P33                    | [6406980bbf](https://bsd-hardware.info/?probe=6406980bbf) | Nov 19, 2023 |
| ASUSTek       | P5Q-E                       | [e7ccb4156e](https://bsd-hardware.info/?probe=e7ccb4156e) | Nov 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a570c7994c](https://bsd-hardware.info/?probe=a570c7994c) | Nov 19, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [e6bfeee196](https://bsd-hardware.info/?probe=e6bfeee196) | Nov 19, 2023 |
| Dell          | 0Y7WYT A00                  | [72987e629d](https://bsd-hardware.info/?probe=72987e629d) | Nov 19, 2023 |
| Protectli     | VP2420                      | [05284d48bc](https://bsd-hardware.info/?probe=05284d48bc) | Nov 19, 2023 |
| Supermicro    | H8SML                       | [c4a58844c5](https://bsd-hardware.info/?probe=c4a58844c5) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [cfbda53125](https://bsd-hardware.info/?probe=cfbda53125) | Nov 18, 2023 |
| ASUSTek       | Maximus VIII HERO           | [9ca9377fee](https://bsd-hardware.info/?probe=9ca9377fee) | Nov 17, 2023 |
| Protectli     | VP2420                      | [ee1cbf5fd0](https://bsd-hardware.info/?probe=ee1cbf5fd0) | Nov 17, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | [1b811bacb7](https://bsd-hardware.info/?probe=1b811bacb7) | Nov 17, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | [204ee8891b](https://bsd-hardware.info/?probe=204ee8891b) | Nov 16, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | [b34836b090](https://bsd-hardware.info/?probe=b34836b090) | Nov 16, 2023 |
| HP            | 18E7                        | [3cbe1117fa](https://bsd-hardware.info/?probe=3cbe1117fa) | Nov 14, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [b858bd0986](https://bsd-hardware.info/?probe=b858bd0986) | Nov 14, 2023 |
| Unknown       | Unknown                     | [db926657cc](https://bsd-hardware.info/?probe=db926657cc) | Nov 14, 2023 |
| Techvision    | TVI7309X B0                 | [253d230fd3](https://bsd-hardware.info/?probe=253d230fd3) | Nov 14, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ea2d57ac16](https://bsd-hardware.info/?probe=ea2d57ac16) | Nov 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [771c13f8ea](https://bsd-hardware.info/?probe=771c13f8ea) | Nov 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [35ae423f7a](https://bsd-hardware.info/?probe=35ae423f7a) | Nov 13, 2023 |
| Dell          | 02YYK5 A00                  | [8b333abcaa](https://bsd-hardware.info/?probe=8b333abcaa) | Nov 13, 2023 |
| MUCAI         | H61 V1.6A                   | [bd3f1334ee](https://bsd-hardware.info/?probe=bd3f1334ee) | Nov 13, 2023 |
| Protectli     | VP4650                      | [0eeeb46242](https://bsd-hardware.info/?probe=0eeeb46242) | Nov 12, 2023 |
| Unknown       | Unknown                     | [a058c72d2c](https://bsd-hardware.info/?probe=a058c72d2c) | Nov 12, 2023 |
| Advantech     | NAMB-3250 A102-1            | [aabeab0c4f](https://bsd-hardware.info/?probe=aabeab0c4f) | Nov 12, 2023 |
| MSI           | H81M-P33                    | [a062354358](https://bsd-hardware.info/?probe=a062354358) | Nov 12, 2023 |
| ASUSTek       | P5Q-E                       | [0869172a54](https://bsd-hardware.info/?probe=0869172a54) | Nov 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b1e348523f](https://bsd-hardware.info/?probe=b1e348523f) | Nov 12, 2023 |
| Gigabyte      | C1037UN                     | [57a9aedd4e](https://bsd-hardware.info/?probe=57a9aedd4e) | Nov 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | [f32f8bdf95](https://bsd-hardware.info/?probe=f32f8bdf95) | Nov 12, 2023 |
| MSI           | MS-7360                     | [07d8a855f3](https://bsd-hardware.info/?probe=07d8a855f3) | Nov 11, 2023 |
| Dell          | 0WMJ54 A01                  | [0f681ab133](https://bsd-hardware.info/?probe=0f681ab133) | Nov 11, 2023 |
| HP            | 805D                        | [f39c87a2a3](https://bsd-hardware.info/?probe=f39c87a2a3) | Nov 11, 2023 |
| Dell          | 042P49 A01                  | [14493eb926](https://bsd-hardware.info/?probe=14493eb926) | Nov 11, 2023 |
| Intel         | HM570                       | [6079db8b21](https://bsd-hardware.info/?probe=6079db8b21) | Nov 11, 2023 |
| Protectli     | FW6                         | [823022b2b0](https://bsd-hardware.info/?probe=823022b2b0) | Nov 10, 2023 |
| HP            | 1495                        | [e92d919eff](https://bsd-hardware.info/?probe=e92d919eff) | Nov 10, 2023 |
| Protectli     | VP2420                      | [3921d18b28](https://bsd-hardware.info/?probe=3921d18b28) | Nov 09, 2023 |
| PC Engines    | apu4                        | [85202e5b6e](https://bsd-hardware.info/?probe=85202e5b6e) | Nov 09, 2023 |
| HP            | 1495                        | [8be7b95a27](https://bsd-hardware.info/?probe=8be7b95a27) | Nov 09, 2023 |
| Unknown       | Unknown                     | [41e181dd6f](https://bsd-hardware.info/?probe=41e181dd6f) | Nov 09, 2023 |
| Intel         | Q3XXG4-P V1.0               | [b6cd3662e9](https://bsd-hardware.info/?probe=b6cd3662e9) | Nov 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | [b7b9df03f3](https://bsd-hardware.info/?probe=b7b9df03f3) | Nov 09, 2023 |
| Intel         | QHSW02                      | [e06c922fda](https://bsd-hardware.info/?probe=e06c922fda) | Nov 08, 2023 |
| Unknown       | Unknown                     | [1987a99b64](https://bsd-hardware.info/?probe=1987a99b64) | Nov 07, 2023 |
| Dell          | 0M5DCD A00                  | [dfdd6ff4c4](https://bsd-hardware.info/?probe=dfdd6ff4c4) | Nov 07, 2023 |
| CncTion       | N6000-4L B0                 | [ed06cf2232](https://bsd-hardware.info/?probe=ed06cf2232) | Nov 07, 2023 |
| Apple         | MacPro4,1                   | [5960492992](https://bsd-hardware.info/?probe=5960492992) | Nov 07, 2023 |
| Unknown       | QSKL01                      | [46543dd22d](https://bsd-hardware.info/?probe=46543dd22d) | Nov 07, 2023 |
| Intel         | QHSW02                      | [3203d5ee34](https://bsd-hardware.info/?probe=3203d5ee34) | Nov 07, 2023 |
| Intel         | HM570                       | [004550243c](https://bsd-hardware.info/?probe=004550243c) | Nov 07, 2023 |
| Unknown       | Unknown                     | [624a69488f](https://bsd-hardware.info/?probe=624a69488f) | Nov 06, 2023 |
| ASUSTek       | AM1I-A                      | [a0580939a5](https://bsd-hardware.info/?probe=a0580939a5) | Nov 06, 2023 |
| HP            | 213D A01                    | [d475dfa7a4](https://bsd-hardware.info/?probe=d475dfa7a4) | Nov 06, 2023 |
| Protectli     | FW4B Ver                    | [bc88549a37](https://bsd-hardware.info/?probe=bc88549a37) | Nov 06, 2023 |
| Advantech     | NAMB-3250 A102-1            | [02f5e40f3d](https://bsd-hardware.info/?probe=02f5e40f3d) | Nov 06, 2023 |
| Cisco         | ASA5525 A0                  | [f6eb14f059](https://bsd-hardware.info/?probe=f6eb14f059) | Nov 06, 2023 |
| Unknown       | Unknown                     | [8b1079a297](https://bsd-hardware.info/?probe=8b1079a297) | Nov 06, 2023 |
| Dell          | 05XGC8 A01                  | [9e054bbcb2](https://bsd-hardware.info/?probe=9e054bbcb2) | Nov 06, 2023 |
| CncTion       | N6000-4L B0                 | [7ee545bad3](https://bsd-hardware.info/?probe=7ee545bad3) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e8c7d22b1f](https://bsd-hardware.info/?probe=e8c7d22b1f) | Nov 05, 2023 |
| MSI           | H81M-P33                    | [d44c30f985](https://bsd-hardware.info/?probe=d44c30f985) | Nov 05, 2023 |
| ASUSTek       | P5Q-E                       | [dac3ca2eca](https://bsd-hardware.info/?probe=dac3ca2eca) | Nov 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e744712416](https://bsd-hardware.info/?probe=e744712416) | Nov 05, 2023 |
| Supermicro    | H8SML                       | [ab650cfab8](https://bsd-hardware.info/?probe=ab650cfab8) | Nov 05, 2023 |
| Unknown       | Unknown                     | [2a768a9f63](https://bsd-hardware.info/?probe=2a768a9f63) | Nov 05, 2023 |
| Unknown       | Unknown                     | [5d0e537b3e](https://bsd-hardware.info/?probe=5d0e537b3e) | Nov 05, 2023 |
| HP            | ProLiant ML10               | [43badefe76](https://bsd-hardware.info/?probe=43badefe76) | Nov 05, 2023 |
| Dell          | 0XCR8D A03                  | [cc58b2f58f](https://bsd-hardware.info/?probe=cc58b2f58f) | Nov 05, 2023 |
| Dell          | 00V62H A00                  | [0b678c5e33](https://bsd-hardware.info/?probe=0b678c5e33) | Nov 04, 2023 |
| Techvision    | TVI7309X B0                 | [90a26f497a](https://bsd-hardware.info/?probe=90a26f497a) | Nov 04, 2023 |
| HP            | 18E4                        | [479b255034](https://bsd-hardware.info/?probe=479b255034) | Nov 03, 2023 |
| Protectli     | FW6                         | [2dc16f3849](https://bsd-hardware.info/?probe=2dc16f3849) | Nov 03, 2023 |
| Shenzhen M... | RPBNB                       | [db0f05f919](https://bsd-hardware.info/?probe=db0f05f919) | Nov 03, 2023 |
| Shenzhen M... | RPBNB                       | [b729c4137a](https://bsd-hardware.info/?probe=b729c4137a) | Nov 03, 2023 |
| CWWK          | MINIPC-G12                  | [4fd9e1d707](https://bsd-hardware.info/?probe=4fd9e1d707) | Nov 02, 2023 |
| Unknown       | Unknown                     | [f1e1a3e8c8](https://bsd-hardware.info/?probe=f1e1a3e8c8) | Nov 02, 2023 |
| MW            | GMLK-2_5G4L                 | [ff78edaee6](https://bsd-hardware.info/?probe=ff78edaee6) | Nov 02, 2023 |
| Dell          | 0XCR8D A01                  | [224cc728f5](https://bsd-hardware.info/?probe=224cc728f5) | Nov 02, 2023 |
| Dell          | 0XCR8D A02                  | [f9df1890fa](https://bsd-hardware.info/?probe=f9df1890fa) | Nov 02, 2023 |
| Dell          | 0XCR8D A01                  | [83c8ab8d4b](https://bsd-hardware.info/?probe=83c8ab8d4b) | Nov 02, 2023 |
| Protectli     | VP2420                      | [7621eb7370](https://bsd-hardware.info/?probe=7621eb7370) | Nov 01, 2023 |
| Shuttle       | FS61                        | [24158fbe17](https://bsd-hardware.info/?probe=24158fbe17) | Oct 31, 2023 |
| Shuttle       | FS61                        | [2efb16a5f4](https://bsd-hardware.info/?probe=2efb16a5f4) | Oct 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c163891517](https://bsd-hardware.info/?probe=c163891517) | Oct 31, 2023 |
| CheckPoint    | T-110-00                    | [970671ce27](https://bsd-hardware.info/?probe=970671ce27) | Oct 31, 2023 |
| Gigabyte      | H370M D3H-CF                | [6b2553e06c](https://bsd-hardware.info/?probe=6b2553e06c) | Oct 30, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [da2fa90c43](https://bsd-hardware.info/?probe=da2fa90c43) | Oct 30, 2023 |
| Dell          | 0KP561                      | [cd0ae50eb0](https://bsd-hardware.info/?probe=cd0ae50eb0) | Oct 30, 2023 |
| Dell          | 0WMJ54 A01                  | [10d46f39aa](https://bsd-hardware.info/?probe=10d46f39aa) | Oct 30, 2023 |
| Dell          | 0WMJ54 A01                  | [5995fa3115](https://bsd-hardware.info/?probe=5995fa3115) | Oct 30, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [9567268d28](https://bsd-hardware.info/?probe=9567268d28) | Oct 30, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [709f8e1566](https://bsd-hardware.info/?probe=709f8e1566) | Oct 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | [b60083ef1f](https://bsd-hardware.info/?probe=b60083ef1f) | Oct 28, 2023 |
| ASRock        | H370M-ITX/ac                | [ace25d235f](https://bsd-hardware.info/?probe=ace25d235f) | Oct 28, 2023 |
| HP            | 2AF7                        | [a45659c9d2](https://bsd-hardware.info/?probe=a45659c9d2) | Oct 28, 2023 |
| Unknown       | Unknown                     | [3e99a14af3](https://bsd-hardware.info/?probe=3e99a14af3) | Oct 28, 2023 |
| Dell          | 09WH54 A01                  | [a012c0e1c9](https://bsd-hardware.info/?probe=a012c0e1c9) | Oct 27, 2023 |
| Intel         | Q3XXG4-P V1.0               | [03ef00fab1](https://bsd-hardware.info/?probe=03ef00fab1) | Oct 27, 2023 |
| Unknown       | Unknown                     | [7a9e2d88ed](https://bsd-hardware.info/?probe=7a9e2d88ed) | Oct 27, 2023 |
| Dell          | 0M5DCD A00                  | [f8ae786555](https://bsd-hardware.info/?probe=f8ae786555) | Oct 27, 2023 |
| Shenzhen M... | AHBNB OEM                   | [8a1a0cdc32](https://bsd-hardware.info/?probe=8a1a0cdc32) | Oct 27, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [233d4d3b64](https://bsd-hardware.info/?probe=233d4d3b64) | Oct 26, 2023 |
| Unknown       | Unknown                     | [f06cbf02dc](https://bsd-hardware.info/?probe=f06cbf02dc) | Oct 25, 2023 |
| Protectli     | FW6 Ver                     | [66f5010f59](https://bsd-hardware.info/?probe=66f5010f59) | Oct 24, 2023 |
| Protectli     | FW6                         | [9ba0e874f4](https://bsd-hardware.info/?probe=9ba0e874f4) | Oct 24, 2023 |
| Unknown       | Unknown                     | [b42465c967](https://bsd-hardware.info/?probe=b42465c967) | Oct 23, 2023 |
| Techvision    | TVI7309X B0                 | [2424acbde7](https://bsd-hardware.info/?probe=2424acbde7) | Oct 23, 2023 |
| Supermicro    | X10SLM-F                    | [8e622421c6](https://bsd-hardware.info/?probe=8e622421c6) | Oct 23, 2023 |
| HP            | 3397                        | [2c004318d4](https://bsd-hardware.info/?probe=2c004318d4) | Oct 22, 2023 |
| Acer          | Aspire XC-830               | [6aea1130aa](https://bsd-hardware.info/?probe=6aea1130aa) | Oct 22, 2023 |
| Acer          | Aspire XC-830               | [3a4d822cfc](https://bsd-hardware.info/?probe=3a4d822cfc) | Oct 22, 2023 |
| MSI           | H81M-P33                    | [dd9ff802a9](https://bsd-hardware.info/?probe=dd9ff802a9) | Oct 22, 2023 |
| ASUSTek       | P5Q-E                       | [1b94fd9385](https://bsd-hardware.info/?probe=1b94fd9385) | Oct 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [cc7fb797f5](https://bsd-hardware.info/?probe=cc7fb797f5) | Oct 22, 2023 |
| Protectli     | FW6 Ver                     | [e12093f6bd](https://bsd-hardware.info/?probe=e12093f6bd) | Oct 22, 2023 |
| HP            | 8054                        | [71b61dc284](https://bsd-hardware.info/?probe=71b61dc284) | Oct 21, 2023 |
| Techvision    | TVI7309X B0                 | [48bb0077c3](https://bsd-hardware.info/?probe=48bb0077c3) | Oct 20, 2023 |
| Protectli     | FW4A Ver                    | [d40c67f9ca](https://bsd-hardware.info/?probe=d40c67f9ca) | Oct 20, 2023 |
| Dell          | 0HD5W2 A01                  | [3f7a4e2865](https://bsd-hardware.info/?probe=3f7a4e2865) | Oct 20, 2023 |
| Gigabyte      | B85M-DS3H                   | [bd9d649fb6](https://bsd-hardware.info/?probe=bd9d649fb6) | Oct 19, 2023 |
| Unknown       | Unknown                     | [94f0b39689](https://bsd-hardware.info/?probe=94f0b39689) | Oct 19, 2023 |
| Dell          | 0NW6H5 A00                  | [606ed441ae](https://bsd-hardware.info/?probe=606ed441ae) | Oct 19, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | [26a1b95e16](https://bsd-hardware.info/?probe=26a1b95e16) | Oct 19, 2023 |
| ASRock        | 970 Extreme3 R2.0           | [6f6f1bf009](https://bsd-hardware.info/?probe=6f6f1bf009) | Oct 18, 2023 |
| CncTion       | J4125-4L-I225               | [d8114642f5](https://bsd-hardware.info/?probe=d8114642f5) | Oct 18, 2023 |
| Dell          | 0YXT71 A00                  | [1bf1c3b807](https://bsd-hardware.info/?probe=1bf1c3b807) | Oct 18, 2023 |
| AZW           | EQ                          | [0d647b68a6](https://bsd-hardware.info/?probe=0d647b68a6) | Oct 18, 2023 |
| AZW           | EQ                          | [71f6a16f5a](https://bsd-hardware.info/?probe=71f6a16f5a) | Oct 18, 2023 |
| HP            | 8299                        | [b4ba6a7e52](https://bsd-hardware.info/?probe=b4ba6a7e52) | Oct 18, 2023 |
| CncTion       | N5105-4L B0                 | [0f18316a17](https://bsd-hardware.info/?probe=0f18316a17) | Oct 18, 2023 |
| ASRock        | 970 Extreme3 R2.0           | [3dffc4d445](https://bsd-hardware.info/?probe=3dffc4d445) | Oct 18, 2023 |
| HP            | 8299                        | [8da92e01e0](https://bsd-hardware.info/?probe=8da92e01e0) | Oct 17, 2023 |
| ASUSTek       | X99-A/USB                   | [0f914c6351](https://bsd-hardware.info/?probe=0f914c6351) | Oct 17, 2023 |
| Dell          | 00V62H A00                  | [8ff0ba4fcb](https://bsd-hardware.info/?probe=8ff0ba4fcb) | Oct 16, 2023 |
| Intel         | DH55TC AAE70932-206         | [745b988354](https://bsd-hardware.info/?probe=745b988354) | Oct 15, 2023 |
| Dell          | 0WR7PY A03                  | [128323ada4](https://bsd-hardware.info/?probe=128323ada4) | Oct 15, 2023 |
| Techvision    | TVI7309X B0                 | [bf66ef021e](https://bsd-hardware.info/?probe=bf66ef021e) | Oct 15, 2023 |
| MSI           | H81M-P33                    | [6902d492db](https://bsd-hardware.info/?probe=6902d492db) | Oct 15, 2023 |
| ASUSTek       | P5Q-E                       | [094b766a05](https://bsd-hardware.info/?probe=094b766a05) | Oct 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b502116394](https://bsd-hardware.info/?probe=b502116394) | Oct 15, 2023 |
| Protectli     | VP4650                      | [9c073eb854](https://bsd-hardware.info/?probe=9c073eb854) | Oct 15, 2023 |
| Gigabyte      | Z68AP-D3                    | [ca5e8cfb2b](https://bsd-hardware.info/?probe=ca5e8cfb2b) | Oct 15, 2023 |
| Protectli     | VP2410                      | [aaffd45671](https://bsd-hardware.info/?probe=aaffd45671) | Oct 15, 2023 |
| ASUSTek       | PRIME X370-PRO              | [697f24cf01](https://bsd-hardware.info/?probe=697f24cf01) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [d14ff47394](https://bsd-hardware.info/?probe=d14ff47394) | Oct 13, 2023 |
| ASUSTek       | PRIME Z690-P                | [95653dd42d](https://bsd-hardware.info/?probe=95653dd42d) | Oct 13, 2023 |
| Protectli     | FW4C                        | [16326174bb](https://bsd-hardware.info/?probe=16326174bb) | Oct 13, 2023 |
| Dell          | 02YYK5 A00                  | [b57183cbb0](https://bsd-hardware.info/?probe=b57183cbb0) | Oct 13, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [30f97615e6](https://bsd-hardware.info/?probe=30f97615e6) | Oct 13, 2023 |
| Unknown       | Unknown                     | [9145630ed9](https://bsd-hardware.info/?probe=9145630ed9) | Oct 12, 2023 |
| Pegatron      | 2AD5                        | [cdc40fe6a3](https://bsd-hardware.info/?probe=cdc40fe6a3) | Oct 11, 2023 |
| Dell          | 08WKV3 A00                  | [67379c4768](https://bsd-hardware.info/?probe=67379c4768) | Oct 11, 2023 |
| Intel         | Q3XXG4-P V1.0               | [3aa38e5b1f](https://bsd-hardware.info/?probe=3aa38e5b1f) | Oct 10, 2023 |
| AZW           | EQ                          | [ea7e5029de](https://bsd-hardware.info/?probe=ea7e5029de) | Oct 10, 2023 |
| Unknown       | Unknown                     | [89d680cba1](https://bsd-hardware.info/?probe=89d680cba1) | Oct 09, 2023 |
| HP            | 1497                        | [9ffee4ae55](https://bsd-hardware.info/?probe=9ffee4ae55) | Oct 09, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [f55c557bcf](https://bsd-hardware.info/?probe=f55c557bcf) | Oct 09, 2023 |
| EVGA          | X299 MICRO                  | [2907f2166d](https://bsd-hardware.info/?probe=2907f2166d) | Oct 09, 2023 |
| Gigabyte      | H470M DS3H                  | [80e01e48bf](https://bsd-hardware.info/?probe=80e01e48bf) | Oct 09, 2023 |
| ASRock        | Z690M Phantom Gaming 4      | [20ff855aec](https://bsd-hardware.info/?probe=20ff855aec) | Oct 08, 2023 |
| Unknown       | Unknown                     | [a64ed6b5d1](https://bsd-hardware.info/?probe=a64ed6b5d1) | Oct 08, 2023 |
| MSI           | H81M-P33                    | [a9729ebc38](https://bsd-hardware.info/?probe=a9729ebc38) | Oct 08, 2023 |
| ASUSTek       | P5Q-E                       | [06a76899d6](https://bsd-hardware.info/?probe=06a76899d6) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [cacbb83f98](https://bsd-hardware.info/?probe=cacbb83f98) | Oct 08, 2023 |
| Unknown       | Unknown                     | [bb66634f7c](https://bsd-hardware.info/?probe=bb66634f7c) | Oct 08, 2023 |
| MSI           | Aspen                       | [7bb665508f](https://bsd-hardware.info/?probe=7bb665508f) | Oct 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b3580a1e53](https://bsd-hardware.info/?probe=b3580a1e53) | Oct 07, 2023 |
| Intel         | CRESCENTBAY                 | [fb6d008bfc](https://bsd-hardware.info/?probe=fb6d008bfc) | Oct 06, 2023 |
| Intel         | QHSW02                      | [e0d4a273f5](https://bsd-hardware.info/?probe=e0d4a273f5) | Oct 06, 2023 |
| HP            | 8056                        | [7516a37588](https://bsd-hardware.info/?probe=7516a37588) | Oct 06, 2023 |
| Win elemen... | M600                        | [da4e03cd91](https://bsd-hardware.info/?probe=da4e03cd91) | Oct 05, 2023 |
| Win elemen... | M600                        | [27492e0298](https://bsd-hardware.info/?probe=27492e0298) | Oct 04, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [17406f5021](https://bsd-hardware.info/?probe=17406f5021) | Oct 04, 2023 |
| Protectli     | FW4C                        | [671429444f](https://bsd-hardware.info/?probe=671429444f) | Oct 04, 2023 |
| Supermicro    | A2SDi-TP8F                  | [1792df4520](https://bsd-hardware.info/?probe=1792df4520) | Oct 04, 2023 |
| HP            | 83E2                        | [dbb1010907](https://bsd-hardware.info/?probe=dbb1010907) | Oct 03, 2023 |
| ASUSTek       | PRIME B560-PLUS AC-HES      | [471133280c](https://bsd-hardware.info/?probe=471133280c) | Oct 03, 2023 |
| Unknown       | Unknown                     | [cab6cdb306](https://bsd-hardware.info/?probe=cab6cdb306) | Oct 02, 2023 |
| Protectli     | VP2420                      | [c77ef1792c](https://bsd-hardware.info/?probe=c77ef1792c) | Oct 02, 2023 |
| Protectli     | VP46xx                      | [4985863bd8](https://bsd-hardware.info/?probe=4985863bd8) | Oct 01, 2023 |
| MSI           | H81M-P33                    | [da12fe3c05](https://bsd-hardware.info/?probe=da12fe3c05) | Oct 01, 2023 |
| ASUSTek       | P5Q-E                       | [6975204e47](https://bsd-hardware.info/?probe=6975204e47) | Oct 01, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | [f97e242e6b](https://bsd-hardware.info/?probe=f97e242e6b) | Oct 01, 2023 |
| Win elemen... | M600                        | [b5caabfd31](https://bsd-hardware.info/?probe=b5caabfd31) | Oct 01, 2023 |
| Win elemen... | M600                        | [7a1378a001](https://bsd-hardware.info/?probe=7a1378a001) | Oct 01, 2023 |
| Win elemen... | M600                        | [93cc6a1173](https://bsd-hardware.info/?probe=93cc6a1173) | Oct 01, 2023 |
| Gigabyte      | H470M DS3H                  | [604bce28c1](https://bsd-hardware.info/?probe=604bce28c1) | Sep 30, 2023 |
| Win elemen... | M600                        | [abc175c93b](https://bsd-hardware.info/?probe=abc175c93b) | Sep 30, 2023 |
| Win elemen... | M600                        | [5b7606e786](https://bsd-hardware.info/?probe=5b7606e786) | Sep 30, 2023 |
| MUCAI         | H61 V1.6A                   | [2008598c7e](https://bsd-hardware.info/?probe=2008598c7e) | Sep 29, 2023 |
| Unknown       | Unknown                     | [6ed3c7314d](https://bsd-hardware.info/?probe=6ed3c7314d) | Sep 29, 2023 |
| HP            | 0B54h D                     | [55122a1908](https://bsd-hardware.info/?probe=55122a1908) | Sep 29, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [8a4596eefa](https://bsd-hardware.info/?probe=8a4596eefa) | Sep 27, 2023 |
| Intel         | DENLOW_REFRESH_WS           | [9ca318e043](https://bsd-hardware.info/?probe=9ca318e043) | Sep 27, 2023 |
| HP            | 8055                        | [b86f4f02a5](https://bsd-hardware.info/?probe=b86f4f02a5) | Sep 26, 2023 |
| Unknown       | Unknown                     | [a77db6c46a](https://bsd-hardware.info/?probe=a77db6c46a) | Sep 25, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [6153909c9e](https://bsd-hardware.info/?probe=6153909c9e) | Sep 25, 2023 |
| Unknown       | Unknown                     | [5232e5837b](https://bsd-hardware.info/?probe=5232e5837b) | Sep 25, 2023 |
| CncTion       | N4505-4L B0                 | [5880a22b30](https://bsd-hardware.info/?probe=5880a22b30) | Sep 25, 2023 |
| Protectli     | VP4630                      | [d5c0fe73ef](https://bsd-hardware.info/?probe=d5c0fe73ef) | Sep 24, 2023 |
| MSI           | H81M-P33                    | [971f3fdba1](https://bsd-hardware.info/?probe=971f3fdba1) | Sep 24, 2023 |
| ASUSTek       | P5Q-E                       | [6538212bd6](https://bsd-hardware.info/?probe=6538212bd6) | Sep 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f7aee1db53](https://bsd-hardware.info/?probe=f7aee1db53) | Sep 24, 2023 |
| Intel         | DQ77KB AAG40294-401         | [be147f7ff1](https://bsd-hardware.info/?probe=be147f7ff1) | Sep 24, 2023 |
| Protectli     | VP2420                      | [8644c80a4a](https://bsd-hardware.info/?probe=8644c80a4a) | Sep 24, 2023 |
| Protectli     | FW6 Ver                     | [d8ccddab5a](https://bsd-hardware.info/?probe=d8ccddab5a) | Sep 23, 2023 |
| Unknown       | Unknown                     | [3e1ef4a73c](https://bsd-hardware.info/?probe=3e1ef4a73c) | Sep 23, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | [8386219e8f](https://bsd-hardware.info/?probe=8386219e8f) | Sep 22, 2023 |
| Dell          | 0HD5W2 A01                  | [5478cff8a7](https://bsd-hardware.info/?probe=5478cff8a7) | Sep 21, 2023 |
| Premio        | BlueCat XMB3 00C            | [423687627b](https://bsd-hardware.info/?probe=423687627b) | Sep 21, 2023 |
| Protectli     | FW4C Ver                    | [eae9f87345](https://bsd-hardware.info/?probe=eae9f87345) | Sep 20, 2023 |
| Supermicro    | A1SRi-2758F                 | [6ee2f45613](https://bsd-hardware.info/?probe=6ee2f45613) | Sep 20, 2023 |
| Supermicro    | A1SRi-2758F                 | [34bffe0ed1](https://bsd-hardware.info/?probe=34bffe0ed1) | Sep 20, 2023 |
| Intel         | Q3XXG4-P V1.0               | [60a616adf4](https://bsd-hardware.info/?probe=60a616adf4) | Sep 20, 2023 |
| Shenzhen M... | RPBNB                       | [07698e61c2](https://bsd-hardware.info/?probe=07698e61c2) | Sep 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [0fe1aab1d8](https://bsd-hardware.info/?probe=0fe1aab1d8) | Sep 19, 2023 |
| Protectli     | VP2420                      | [c4599cac13](https://bsd-hardware.info/?probe=c4599cac13) | Sep 19, 2023 |
| Unknown       | Unknown                     | [0a9c074970](https://bsd-hardware.info/?probe=0a9c074970) | Sep 18, 2023 |
| Techvision    | TVI7309X B0                 | [5e7775568c](https://bsd-hardware.info/?probe=5e7775568c) | Sep 18, 2023 |
| Inventec      | DQ Class A02                | [e6e705b7cf](https://bsd-hardware.info/?probe=e6e705b7cf) | Sep 18, 2023 |
| Advantech     | NAMB-3250 A102-1            | [143c5f73fc](https://bsd-hardware.info/?probe=143c5f73fc) | Sep 17, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [31455b0d33](https://bsd-hardware.info/?probe=31455b0d33) | Sep 17, 2023 |
| Unknown       | Unknown                     | [31cf5dc87d](https://bsd-hardware.info/?probe=31cf5dc87d) | Sep 16, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [a054400ef6](https://bsd-hardware.info/?probe=a054400ef6) | Sep 16, 2023 |
| Dell          | 02YYK5 A00                  | [a2d011d2d7](https://bsd-hardware.info/?probe=a2d011d2d7) | Sep 16, 2023 |
| MW            | GMLK-2_5G4L                 | [d36ff6181c](https://bsd-hardware.info/?probe=d36ff6181c) | Sep 15, 2023 |
| Unknown       | Unknown                     | [3fcc5727d3](https://bsd-hardware.info/?probe=3fcc5727d3) | Sep 15, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [6fc18e3db7](https://bsd-hardware.info/?probe=6fc18e3db7) | Sep 15, 2023 |
| Protectli     | FW4B Ver                    | [9790cd72bc](https://bsd-hardware.info/?probe=9790cd72bc) | Sep 15, 2023 |
| Dell          | OptiPlex 3020               | [dfb6cce27d](https://bsd-hardware.info/?probe=dfb6cce27d) | Sep 14, 2023 |
| ASRock        | J1900D2Y                    | [2084583d47](https://bsd-hardware.info/?probe=2084583d47) | Sep 14, 2023 |
| ASRock        | J3455M                      | [f9809dfb0f](https://bsd-hardware.info/?probe=f9809dfb0f) | Sep 13, 2023 |
| Dell          | 04YP6J A02                  | [0933e1164a](https://bsd-hardware.info/?probe=0933e1164a) | Sep 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [5dee3a945f](https://bsd-hardware.info/?probe=5dee3a945f) | Sep 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [9fee6e83fc](https://bsd-hardware.info/?probe=9fee6e83fc) | Sep 13, 2023 |
| Dell          | 02YYK5 A00                  | [ae320bd7de](https://bsd-hardware.info/?probe=ae320bd7de) | Sep 13, 2023 |
| HP            | 212B                        | [3370718b29](https://bsd-hardware.info/?probe=3370718b29) | Sep 13, 2023 |
| Protectli     | FW4B Ver                    | [984a64677e](https://bsd-hardware.info/?probe=984a64677e) | Sep 13, 2023 |
| ASRockRack    | X470D4U                     | [b0cd1ce0f4](https://bsd-hardware.info/?probe=b0cd1ce0f4) | Sep 13, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | [89a601d720](https://bsd-hardware.info/?probe=89a601d720) | Sep 12, 2023 |
| MW            | GMLK-2_5G4L                 | [7923196f55](https://bsd-hardware.info/?probe=7923196f55) | Sep 11, 2023 |
| MSI           | A520M-A PRO                 | [8b541c71a9](https://bsd-hardware.info/?probe=8b541c71a9) | Sep 11, 2023 |
| Unknown       | Unknown                     | [6610a56ab4](https://bsd-hardware.info/?probe=6610a56ab4) | Sep 11, 2023 |
| Unknown       | Unknown                     | [ccc62ac366](https://bsd-hardware.info/?probe=ccc62ac366) | Sep 10, 2023 |
| ASRock        | 4X4-4000 Series             | [525ed7878c](https://bsd-hardware.info/?probe=525ed7878c) | Sep 10, 2023 |
| ASRock        | 4X4-4000 Series             | [0131f46755](https://bsd-hardware.info/?probe=0131f46755) | Sep 10, 2023 |
| AZW           | EQ                          | [c6f83de1e4](https://bsd-hardware.info/?probe=c6f83de1e4) | Sep 10, 2023 |
| MSI           | H81M-P33                    | [57a847859f](https://bsd-hardware.info/?probe=57a847859f) | Sep 10, 2023 |
| ASUSTek       | P5Q-E                       | [b7e0d87f47](https://bsd-hardware.info/?probe=b7e0d87f47) | Sep 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c2378b3e83](https://bsd-hardware.info/?probe=c2378b3e83) | Sep 10, 2023 |
| Unknown       | QGLK03                      | [42ea8dfb44](https://bsd-hardware.info/?probe=42ea8dfb44) | Sep 10, 2023 |
| CWWK          | CW-AD4L-N V1                | [52764da7d8](https://bsd-hardware.info/?probe=52764da7d8) | Sep 10, 2023 |
| Supermicro    | X10SLM-F                    | [332a3f8516](https://bsd-hardware.info/?probe=332a3f8516) | Sep 09, 2023 |
| Supermicro    | X8DTH-i/6/iF/6F             | [df114e1b94](https://bsd-hardware.info/?probe=df114e1b94) | Sep 09, 2023 |
| Unknown       | Unknown                     | [8579d5fa0d](https://bsd-hardware.info/?probe=8579d5fa0d) | Sep 09, 2023 |
| Protectli     | FW4C Ver                    | [7ea278ed7a](https://bsd-hardware.info/?probe=7ea278ed7a) | Sep 09, 2023 |
| Protectli     | FW4C Ver                    | [331f3de91a](https://bsd-hardware.info/?probe=331f3de91a) | Sep 09, 2023 |
| Unknown       | Unknown                     | [ee507594a0](https://bsd-hardware.info/?probe=ee507594a0) | Sep 09, 2023 |
| Intel         | Q3XXG4-P V1.0               | [07d197cf04](https://bsd-hardware.info/?probe=07d197cf04) | Sep 09, 2023 |
| Unknown       | Unknown                     | [2e51c11ed2](https://bsd-hardware.info/?probe=2e51c11ed2) | Sep 08, 2023 |
| Unknown       | Unknown                     | [480823e372](https://bsd-hardware.info/?probe=480823e372) | Sep 08, 2023 |
| Dell          | 0NC2VH A01                  | [122601f717](https://bsd-hardware.info/?probe=122601f717) | Sep 08, 2023 |
| AZW           | MINI S 10                   | [4580cb5481](https://bsd-hardware.info/?probe=4580cb5481) | Sep 08, 2023 |
| Techvision    | TVI7309X B0                 | [aaeb12b1c6](https://bsd-hardware.info/?probe=aaeb12b1c6) | Sep 08, 2023 |
| Protectli     | VP2420                      | [2a8eb1b056](https://bsd-hardware.info/?probe=2a8eb1b056) | Sep 08, 2023 |
| Unknown       | Unknown                     | [fa747c859f](https://bsd-hardware.info/?probe=fa747c859f) | Sep 08, 2023 |
| Intel         | MAHOBAY                     | [a3e54e7628](https://bsd-hardware.info/?probe=a3e54e7628) | Sep 08, 2023 |
| Techvision    | TVI7309X B0                 | [eff74e8df0](https://bsd-hardware.info/?probe=eff74e8df0) | Sep 07, 2023 |
| Dell          | 05XGC8 A01                  | [7c0acfa5b9](https://bsd-hardware.info/?probe=7c0acfa5b9) | Sep 07, 2023 |
| Unknown       | Unknown                     | [94d9b19ade](https://bsd-hardware.info/?probe=94d9b19ade) | Sep 07, 2023 |
| Lenovo        | 0B98401 PRO                 | [4397f70291](https://bsd-hardware.info/?probe=4397f70291) | Sep 06, 2023 |
| AZW           | MINI S 10                   | [2daf516a05](https://bsd-hardware.info/?probe=2daf516a05) | Sep 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [0b7d85b124](https://bsd-hardware.info/?probe=0b7d85b124) | Sep 06, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [3af68f2594](https://bsd-hardware.info/?probe=3af68f2594) | Sep 06, 2023 |
| Dell          | 096JG8 A01                  | [ec3e0338eb](https://bsd-hardware.info/?probe=ec3e0338eb) | Sep 06, 2023 |
| Dell          | 096JG8 A01                  | [84d768ee15](https://bsd-hardware.info/?probe=84d768ee15) | Sep 05, 2023 |
| Intel         | Q3XXG4-P V1.0               | [3fb536ecce](https://bsd-hardware.info/?probe=3fb536ecce) | Sep 05, 2023 |
| ASUSTek       | H97I-PLUS                   | [e92272bb87](https://bsd-hardware.info/?probe=e92272bb87) | Sep 05, 2023 |
| Supermicro    | X11SSH-F                    | [bff90e93d0](https://bsd-hardware.info/?probe=bff90e93d0) | Sep 05, 2023 |
| Unknown       | Unknown                     | [a4796e8170](https://bsd-hardware.info/?probe=a4796e8170) | Sep 04, 2023 |
| Dell          | 0NC2VH A01                  | [8cc0358a69](https://bsd-hardware.info/?probe=8cc0358a69) | Sep 04, 2023 |
| CWWK          | CW-AD4L-N V1                | [dd32d9d4e1](https://bsd-hardware.info/?probe=dd32d9d4e1) | Sep 04, 2023 |
| Unknown       | Unknown                     | [7d95befe6e](https://bsd-hardware.info/?probe=7d95befe6e) | Sep 04, 2023 |
| Intel         | S1200KP AAG34877-201        | [1b07865ce7](https://bsd-hardware.info/?probe=1b07865ce7) | Sep 04, 2023 |
| ASRock        | X570 Steel Legend WiFi a... | [a98f0b3d67](https://bsd-hardware.info/?probe=a98f0b3d67) | Sep 03, 2023 |
| Gigabyte      | A520I AC                    | [58e061f420](https://bsd-hardware.info/?probe=58e061f420) | Sep 03, 2023 |
| ASRock        | X570 Steel Legend WiFi a... | [d352ea60cf](https://bsd-hardware.info/?probe=d352ea60cf) | Sep 03, 2023 |
| MSI           | PRO Z790-P WIFI             | [fe53c55492](https://bsd-hardware.info/?probe=fe53c55492) | Sep 03, 2023 |
| MSI           | H81M-P33                    | [b47290007a](https://bsd-hardware.info/?probe=b47290007a) | Sep 03, 2023 |
| ASUSTek       | P5Q-E                       | [ef4604a40f](https://bsd-hardware.info/?probe=ef4604a40f) | Sep 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8d37c44440](https://bsd-hardware.info/?probe=8d37c44440) | Sep 03, 2023 |
| Unknown       | Unknown                     | [9c1891cda7](https://bsd-hardware.info/?probe=9c1891cda7) | Sep 03, 2023 |
| AAEON         | FWS-2363 V1.0               | [098bc5466b](https://bsd-hardware.info/?probe=098bc5466b) | Sep 03, 2023 |
| Dell          | 08NPPY A00                  | [1ae33cfe72](https://bsd-hardware.info/?probe=1ae33cfe72) | Sep 02, 2023 |
| ASRock        | J3455M                      | [762d4d9370](https://bsd-hardware.info/?probe=762d4d9370) | Sep 02, 2023 |
| Dell          | 0XCR8D A00                  | [b89126c9d9](https://bsd-hardware.info/?probe=b89126c9d9) | Sep 02, 2023 |
| MSI           | Z390-A PRO                  | [57925dc8bb](https://bsd-hardware.info/?probe=57925dc8bb) | Sep 02, 2023 |
| Unknown       | Unknown                     | [94487109c2](https://bsd-hardware.info/?probe=94487109c2) | Sep 01, 2023 |
| Shuttle       | FS77U                       | [149a8a1437](https://bsd-hardware.info/?probe=149a8a1437) | Sep 01, 2023 |
| Dell          | 0YXT71 A02                  | [b887caabe7](https://bsd-hardware.info/?probe=b887caabe7) | Aug 31, 2023 |
| Foxconn       | nT-A3000 series FAB         | [d9f360b4fe](https://bsd-hardware.info/?probe=d9f360b4fe) | Aug 31, 2023 |
| Dell          | 0WR7PY A02                  | [2557e04cf5](https://bsd-hardware.info/?probe=2557e04cf5) | Aug 31, 2023 |
| Biostar       | A68N-5545                   | [b2a1070e2d](https://bsd-hardware.info/?probe=b2a1070e2d) | Aug 31, 2023 |
| CWWK          | CW-AD4L-N V1                | [363a27fb74](https://bsd-hardware.info/?probe=363a27fb74) | Aug 31, 2023 |
| Infoblox      | IB-810                      | [34c0fa6bec](https://bsd-hardware.info/?probe=34c0fa6bec) | Aug 30, 2023 |
| Techvision    | TVI7309X B0                 | [259a7ec99d](https://bsd-hardware.info/?probe=259a7ec99d) | Aug 30, 2023 |
| Techvision    | TVI7309X B0                 | [20946147de](https://bsd-hardware.info/?probe=20946147de) | Aug 30, 2023 |
| Unknown       | Unknown                     | [8cfa60050b](https://bsd-hardware.info/?probe=8cfa60050b) | Aug 30, 2023 |
| Supermicro    | A1SRi-2758F                 | [c8b4f33fb1](https://bsd-hardware.info/?probe=c8b4f33fb1) | Aug 30, 2023 |
| Biostar       | A68N-5545                   | [c90edbc46a](https://bsd-hardware.info/?probe=c90edbc46a) | Aug 29, 2023 |
| Supermicro    | X9DRD-iF                    | [be36f2fe2b](https://bsd-hardware.info/?probe=be36f2fe2b) | Aug 28, 2023 |
| Dell          | 04Y8V0 A02                  | [a84c23941d](https://bsd-hardware.info/?probe=a84c23941d) | Aug 27, 2023 |
| Protectli     | FW6                         | [37b744ff79](https://bsd-hardware.info/?probe=37b744ff79) | Aug 27, 2023 |
| MSI           | H81M-P33                    | [2e9a066a01](https://bsd-hardware.info/?probe=2e9a066a01) | Aug 27, 2023 |
| ASUSTek       | P5Q-E                       | [9898ae1ead](https://bsd-hardware.info/?probe=9898ae1ead) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [0bb56ff672](https://bsd-hardware.info/?probe=0bb56ff672) | Aug 27, 2023 |
| Supermicro    | X11SDV-4C-TP8F-01           | [21e958a05d](https://bsd-hardware.info/?probe=21e958a05d) | Aug 26, 2023 |
| ASRock        | 970 Extreme3 R2.0           | [bf289c5941](https://bsd-hardware.info/?probe=bf289c5941) | Aug 26, 2023 |
| HP            | 8299                        | [77a077cb11](https://bsd-hardware.info/?probe=77a077cb11) | Aug 26, 2023 |
| Pegatron      | 2ACD                        | [c20fcb2b2f](https://bsd-hardware.info/?probe=c20fcb2b2f) | Aug 26, 2023 |
| Inventec      | Z CLASS A02                 | [8d7f83c319](https://bsd-hardware.info/?probe=8d7f83c319) | Aug 24, 2023 |
| MW            | GMLK-2_5G4L                 | [d07ade15d2](https://bsd-hardware.info/?probe=d07ade15d2) | Aug 23, 2023 |
| MSI           | PRO B550-VC                 | [005e9c7b4c](https://bsd-hardware.info/?probe=005e9c7b4c) | Aug 23, 2023 |
| AZW           | EQ                          | [a43bd92291](https://bsd-hardware.info/?probe=a43bd92291) | Aug 23, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [1fcc80636d](https://bsd-hardware.info/?probe=1fcc80636d) | Aug 22, 2023 |
| Techvision    | TVI7309X B0                 | [ff55eb5161](https://bsd-hardware.info/?probe=ff55eb5161) | Aug 22, 2023 |
| Protectli     | FW4B                        | [6041b7e153](https://bsd-hardware.info/?probe=6041b7e153) | Aug 21, 2023 |
| Intel         | JSL MRD                     | [0f3ef76fb8](https://bsd-hardware.info/?probe=0f3ef76fb8) | Aug 21, 2023 |
| Cisco         | ASA5525 A0                  | [7c88ca29f7](https://bsd-hardware.info/?probe=7c88ca29f7) | Aug 21, 2023 |
| ASUSTek       | B85M-G R2.0                 | [3941ce5fae](https://bsd-hardware.info/?probe=3941ce5fae) | Aug 21, 2023 |
| ASRock        | X570M Pro4                  | [c03bc6fa91](https://bsd-hardware.info/?probe=c03bc6fa91) | Aug 21, 2023 |
| MSI           | MEG X570 ACE                | [0d69491bdd](https://bsd-hardware.info/?probe=0d69491bdd) | Aug 21, 2023 |
| MSI           | MEG X570 ACE                | [913cc77381](https://bsd-hardware.info/?probe=913cc77381) | Aug 21, 2023 |
| Unknown       | Unknown                     | [e57d2d76d2](https://bsd-hardware.info/?probe=e57d2d76d2) | Aug 21, 2023 |
| Unknown       | J3160-4L                    | [cf30fa594f](https://bsd-hardware.info/?probe=cf30fa594f) | Aug 21, 2023 |
| Intel         | DQ67SW AAG12527-310         | [e6bfadb400](https://bsd-hardware.info/?probe=e6bfadb400) | Aug 21, 2023 |
| Inventec      | Z CLASS A02                 | [3194978ea5](https://bsd-hardware.info/?probe=3194978ea5) | Aug 20, 2023 |
| Gigabyte      | GA-880GA-UD3H               | [35eb7df9a7](https://bsd-hardware.info/?probe=35eb7df9a7) | Aug 20, 2023 |
| MSI           | 990FXA-GD80                 | [70c65a5a34](https://bsd-hardware.info/?probe=70c65a5a34) | Aug 20, 2023 |
| Unknown       | Unknown                     | [3296816fc1](https://bsd-hardware.info/?probe=3296816fc1) | Aug 20, 2023 |
| ASRock        | H110M-STX                   | [5c819b9ff1](https://bsd-hardware.info/?probe=5c819b9ff1) | Aug 20, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [1b53079f34](https://bsd-hardware.info/?probe=1b53079f34) | Aug 19, 2023 |
| Protectli     | FW1 Ver                     | [8b49278bbd](https://bsd-hardware.info/?probe=8b49278bbd) | Aug 19, 2023 |
| Supermicro    | A1SRi-2758F                 | [c9c0312302](https://bsd-hardware.info/?probe=c9c0312302) | Aug 19, 2023 |
| Protectli     | FW2B Ver                    | [b200aabc73](https://bsd-hardware.info/?probe=b200aabc73) | Aug 18, 2023 |
| Unknown       | Unknown                     | [f7c887c84f](https://bsd-hardware.info/?probe=f7c887c84f) | Aug 18, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [df095be4ba](https://bsd-hardware.info/?probe=df095be4ba) | Aug 18, 2023 |
| Dell          | 0GY6Y8 A00                  | [e982da98d2](https://bsd-hardware.info/?probe=e982da98d2) | Aug 18, 2023 |
| MSI           | MS-7721                     | [a577019634](https://bsd-hardware.info/?probe=a577019634) | Aug 18, 2023 |
| MSI           | MS-7721                     | [678c81c8c1](https://bsd-hardware.info/?probe=678c81c8c1) | Aug 18, 2023 |
| Unknown       | Unknown                     | [3521bed0e8](https://bsd-hardware.info/?probe=3521bed0e8) | Aug 18, 2023 |
| Unknown       | QSKL01                      | [b768029249](https://bsd-hardware.info/?probe=b768029249) | Aug 18, 2023 |
| ASRock        | B660M Steel Legend          | [c50e637bc2](https://bsd-hardware.info/?probe=c50e637bc2) | Aug 18, 2023 |
| Supermicro    | A1SRi-2758F                 | [71fff01c39](https://bsd-hardware.info/?probe=71fff01c39) | Aug 18, 2023 |
| Protectli     | FW4B                        | [880c0c7069](https://bsd-hardware.info/?probe=880c0c7069) | Aug 18, 2023 |
| HP            | 1495                        | [556a339a7e](https://bsd-hardware.info/?probe=556a339a7e) | Aug 17, 2023 |
| Unknown       | Unknown                     | [a574d1cce5](https://bsd-hardware.info/?probe=a574d1cce5) | Aug 17, 2023 |
| Unknown       | Unknown                     | [20348d2f47](https://bsd-hardware.info/?probe=20348d2f47) | Aug 17, 2023 |
| Unknown       | YL-E3854L4-V2               | [6b85b4a31c](https://bsd-hardware.info/?probe=6b85b4a31c) | Aug 16, 2023 |
| MSI           | PRO Z790-P WIFI             | [fcb3075158](https://bsd-hardware.info/?probe=fcb3075158) | Aug 16, 2023 |
| Unknown       | Unknown                     | [e457a41b4a](https://bsd-hardware.info/?probe=e457a41b4a) | Aug 16, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | [3b5ddbcb06](https://bsd-hardware.info/?probe=3b5ddbcb06) | Aug 16, 2023 |
| CncTion       | J4125-4L-I225               | [269cfa2253](https://bsd-hardware.info/?probe=269cfa2253) | Aug 16, 2023 |
| CWWK          | CW-AD4L-N V1                | [f710821a92](https://bsd-hardware.info/?probe=f710821a92) | Aug 16, 2023 |
| HP            | 18E7                        | [3c24defdf8](https://bsd-hardware.info/?probe=3c24defdf8) | Aug 16, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [fc152ce8d4](https://bsd-hardware.info/?probe=fc152ce8d4) | Aug 16, 2023 |
| Unknown       | Unknown                     | [86c4d1f8cf](https://bsd-hardware.info/?probe=86c4d1f8cf) | Aug 15, 2023 |
| Gigabyte      | G41M-ES2L                   | [30c58f7403](https://bsd-hardware.info/?probe=30c58f7403) | Aug 15, 2023 |
| PC Engines    | APU2                        | [c11fdc1cf9](https://bsd-hardware.info/?probe=c11fdc1cf9) | Aug 15, 2023 |
| Unknown       | Unknown                     | [99fd3696dd](https://bsd-hardware.info/?probe=99fd3696dd) | Aug 15, 2023 |
| AZW           | EQ                          | [5393736ae4](https://bsd-hardware.info/?probe=5393736ae4) | Aug 15, 2023 |
| Protectli     | FW4B Ver                    | [dbbd82bd80](https://bsd-hardware.info/?probe=dbbd82bd80) | Aug 15, 2023 |
| MSI           | B360M BAZOOKA               | [472c17f992](https://bsd-hardware.info/?probe=472c17f992) | Aug 15, 2023 |
| Dell          | 08NPPY A00                  | [aba7b573c1](https://bsd-hardware.info/?probe=aba7b573c1) | Aug 14, 2023 |
| MSI           | 990FXA-GD80                 | [169da97c61](https://bsd-hardware.info/?probe=169da97c61) | Aug 14, 2023 |
| Protectli     | FW4B                        | [417b740320](https://bsd-hardware.info/?probe=417b740320) | Aug 14, 2023 |
| Dell          | 0HY9JP A00                  | [c09110c605](https://bsd-hardware.info/?probe=c09110c605) | Aug 13, 2023 |
| Protectli     | VP2420                      | [b4bed593e9](https://bsd-hardware.info/?probe=b4bed593e9) | Aug 13, 2023 |
| Protectli     | VP2420                      | [b81c163920](https://bsd-hardware.info/?probe=b81c163920) | Aug 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [2529ce32a7](https://bsd-hardware.info/?probe=2529ce32a7) | Aug 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [80fbf43a6c](https://bsd-hardware.info/?probe=80fbf43a6c) | Aug 13, 2023 |
| ASUSTek       | P5Q-E                       | [fbb75a1ace](https://bsd-hardware.info/?probe=fbb75a1ace) | Aug 13, 2023 |
| MSI           | H81M-P33                    | [c7b0e4ca6c](https://bsd-hardware.info/?probe=c7b0e4ca6c) | Aug 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [245d908d1a](https://bsd-hardware.info/?probe=245d908d1a) | Aug 13, 2023 |
| Dell          | 02YYK5 A00                  | [fecdfd45c7](https://bsd-hardware.info/?probe=fecdfd45c7) | Aug 13, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [9d53e56e92](https://bsd-hardware.info/?probe=9d53e56e92) | Aug 13, 2023 |
| Supermicro    | X11SSH-F                    | [deb4e10cd2](https://bsd-hardware.info/?probe=deb4e10cd2) | Aug 13, 2023 |
| Supermicro    | X11SSH-F                    | [947caf3be1](https://bsd-hardware.info/?probe=947caf3be1) | Aug 13, 2023 |
| Unknown       | YL-E3854L4-V2               | [e21c4e8012](https://bsd-hardware.info/?probe=e21c4e8012) | Aug 13, 2023 |
| Unknown       | YL-E3854L4-V2               | [2b24029c25](https://bsd-hardware.info/?probe=2b24029c25) | Aug 12, 2023 |
| HP            | 8265                        | [cefac793c7](https://bsd-hardware.info/?probe=cefac793c7) | Aug 12, 2023 |
| MW            | GMLK-2_5G4L                 | [41f42269dc](https://bsd-hardware.info/?probe=41f42269dc) | Aug 12, 2023 |
| Protectli     | FW6 Ver                     | [edc2f0f879](https://bsd-hardware.info/?probe=edc2f0f879) | Aug 12, 2023 |
| Protectli     | FW4C Ver                    | [519987ec57](https://bsd-hardware.info/?probe=519987ec57) | Aug 12, 2023 |
| MW            | GMLK-2_5G4L                 | [2ee5b48d5c](https://bsd-hardware.info/?probe=2ee5b48d5c) | Aug 12, 2023 |
| Unknown       | Unknown                     | [e310e0d309](https://bsd-hardware.info/?probe=e310e0d309) | Aug 11, 2023 |
| HP            | 8054                        | [05cae0efcc](https://bsd-hardware.info/?probe=05cae0efcc) | Aug 11, 2023 |
| HP            | 8055                        | [d686196496](https://bsd-hardware.info/?probe=d686196496) | Aug 11, 2023 |
| HP            | 1495                        | [7591160534](https://bsd-hardware.info/?probe=7591160534) | Aug 11, 2023 |
| Shuttle       | FH270                       | [8b697be8be](https://bsd-hardware.info/?probe=8b697be8be) | Aug 11, 2023 |
| Unknown       | Unknown                     | [fdd28fbae2](https://bsd-hardware.info/?probe=fdd28fbae2) | Aug 10, 2023 |
| MSI           | B360M BAZOOKA               | [4b0b4b88a7](https://bsd-hardware.info/?probe=4b0b4b88a7) | Aug 10, 2023 |
| Gigabyte      | X570 UD                     | [d4b7006d24](https://bsd-hardware.info/?probe=d4b7006d24) | Aug 10, 2023 |
| Supermicro    | X12SDV-4C-SP6F              | [6a275811b8](https://bsd-hardware.info/?probe=6a275811b8) | Aug 10, 2023 |
| Techvision    | TVI7309X B0                 | [877307aa80](https://bsd-hardware.info/?probe=877307aa80) | Aug 09, 2023 |
| Premio        | BlueCat XMB3 00C            | [76abf23a1f](https://bsd-hardware.info/?probe=76abf23a1f) | Aug 08, 2023 |
| Dell          | 08NPPY A00                  | [c0884d7f16](https://bsd-hardware.info/?probe=c0884d7f16) | Aug 08, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [c54bdb8e4b](https://bsd-hardware.info/?probe=c54bdb8e4b) | Aug 08, 2023 |
| ASUSTek       | PRIME Z590M-PLUS            | [87810aceef](https://bsd-hardware.info/?probe=87810aceef) | Aug 08, 2023 |
| PC Engines    | apu4                        | [bb7ad49154](https://bsd-hardware.info/?probe=bb7ad49154) | Aug 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | [d880905ae7](https://bsd-hardware.info/?probe=d880905ae7) | Aug 07, 2023 |
| Intel         | SHARKBAY                    | [2a8896bb78](https://bsd-hardware.info/?probe=2a8896bb78) | Aug 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | [5b58edb60b](https://bsd-hardware.info/?probe=5b58edb60b) | Aug 07, 2023 |
| Unknown       | Unknown                     | [16e7763338](https://bsd-hardware.info/?probe=16e7763338) | Aug 07, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [19e34e504c](https://bsd-hardware.info/?probe=19e34e504c) | Aug 07, 2023 |
| PC Engines    | apu4                        | [57e0cc469e](https://bsd-hardware.info/?probe=57e0cc469e) | Aug 07, 2023 |
| Protectli     | FW6 Ver                     | [c05ddd6998](https://bsd-hardware.info/?probe=c05ddd6998) | Aug 07, 2023 |
| Protectli     | FW6 Ver                     | [4836027efd](https://bsd-hardware.info/?probe=4836027efd) | Aug 07, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [ec37cc1ba1](https://bsd-hardware.info/?probe=ec37cc1ba1) | Aug 07, 2023 |
| ZOTAC         | Unknown                     | [415f49b491](https://bsd-hardware.info/?probe=415f49b491) | Aug 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [d2ba7bbf34](https://bsd-hardware.info/?probe=d2ba7bbf34) | Aug 06, 2023 |
| Dell          | 0KWVT8 A03                  | [d203b32a8f](https://bsd-hardware.info/?probe=d203b32a8f) | Aug 06, 2023 |
| Supermicro    | X12SDV-4C-SP6F              | [5a87146725](https://bsd-hardware.info/?probe=5a87146725) | Aug 06, 2023 |
| MSI           | H81M-P33                    | [1f7493ada9](https://bsd-hardware.info/?probe=1f7493ada9) | Aug 06, 2023 |
| ASUSTek       | P5Q-E                       | [46b9ec2e56](https://bsd-hardware.info/?probe=46b9ec2e56) | Aug 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5bd8b552e6](https://bsd-hardware.info/?probe=5bd8b552e6) | Aug 06, 2023 |
| Acer          | Aspire TC-330               | [4d3de96309](https://bsd-hardware.info/?probe=4d3de96309) | Aug 05, 2023 |
| HP            | 843F                        | [d192efba82](https://bsd-hardware.info/?probe=d192efba82) | Aug 05, 2023 |
| Unknown       | Unknown                     | [0f6e0d9566](https://bsd-hardware.info/?probe=0f6e0d9566) | Aug 05, 2023 |
| Protectli     | FW4B Ver                    | [8446d61b81](https://bsd-hardware.info/?probe=8446d61b81) | Aug 04, 2023 |
| Dell          | 0NC2VH A01                  | [36d63888b2](https://bsd-hardware.info/?probe=36d63888b2) | Aug 04, 2023 |
| Dell          | 0NC2VH A01                  | [bee8eb05f2](https://bsd-hardware.info/?probe=bee8eb05f2) | Aug 04, 2023 |
| Protectli     | VP4650                      | [94d2d08a9d](https://bsd-hardware.info/?probe=94d2d08a9d) | Aug 04, 2023 |
| ASRock        | 4X4-4000 Series             | [da7d5e31aa](https://bsd-hardware.info/?probe=da7d5e31aa) | Aug 03, 2023 |
| Gigabyte      | X570 UD                     | [2bef587ef1](https://bsd-hardware.info/?probe=2bef587ef1) | Aug 03, 2023 |
| Unknown       | Unknown                     | [803f6b50b3](https://bsd-hardware.info/?probe=803f6b50b3) | Aug 03, 2023 |
| Unknown       | Unknown                     | [91dd6813a1](https://bsd-hardware.info/?probe=91dd6813a1) | Aug 03, 2023 |
| ASRock        | 4X4-4000 Series             | [d896138d30](https://bsd-hardware.info/?probe=d896138d30) | Aug 03, 2023 |
| HP            | 1495                        | [551688d163](https://bsd-hardware.info/?probe=551688d163) | Aug 03, 2023 |
| Shuttle       | FH270                       | [92c45a20de](https://bsd-hardware.info/?probe=92c45a20de) | Aug 02, 2023 |
| Dell          | 08NPPY A00                  | [249d4620d2](https://bsd-hardware.info/?probe=249d4620d2) | Aug 02, 2023 |
| ASRock        | B660-ITX                    | [c218c3c4d4](https://bsd-hardware.info/?probe=c218c3c4d4) | Aug 02, 2023 |
| Protectli     | VP2410 10                   | [3d653ab54c](https://bsd-hardware.info/?probe=3d653ab54c) | Aug 02, 2023 |
| Dell          | 0WR7PY A01                  | [54388809cd](https://bsd-hardware.info/?probe=54388809cd) | Aug 02, 2023 |
| ASRock        | B550M Steel Legend          | [ffc50e224c](https://bsd-hardware.info/?probe=ffc50e224c) | Aug 01, 2023 |
| Supermicro    | X7SPA-H                     | [de44613a90](https://bsd-hardware.info/?probe=de44613a90) | Aug 01, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | [bdb1c85615](https://bsd-hardware.info/?probe=bdb1c85615) | Aug 01, 2023 |
| CWWK          | CW-AD4L-N V1                | [9cf0b7fe7c](https://bsd-hardware.info/?probe=9cf0b7fe7c) | Aug 01, 2023 |
| AZW           | EQ                          | [24d56ab18f](https://bsd-hardware.info/?probe=24d56ab18f) | Aug 01, 2023 |
| ASRockRack    | X470D4U                     | [f26504cb5b](https://bsd-hardware.info/?probe=f26504cb5b) | Jul 31, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [c045012233](https://bsd-hardware.info/?probe=c045012233) | Jul 31, 2023 |
| Protectli     | FW6                         | [aa7b970016](https://bsd-hardware.info/?probe=aa7b970016) | Jul 31, 2023 |
| Protectli     | FW1 Ver                     | [1d6213fd35](https://bsd-hardware.info/?probe=1d6213fd35) | Jul 30, 2023 |
| MSI           | H81M-P33                    | [9c27c27611](https://bsd-hardware.info/?probe=9c27c27611) | Jul 30, 2023 |
| ASUSTek       | P5Q-E                       | [a2dbe84ed3](https://bsd-hardware.info/?probe=a2dbe84ed3) | Jul 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [591f8397a9](https://bsd-hardware.info/?probe=591f8397a9) | Jul 30, 2023 |
| Premio        | BlueCat XMB3 00C            | [c453573c71](https://bsd-hardware.info/?probe=c453573c71) | Jul 30, 2023 |
| Dell          | 05XGC8 A01                  | [38310a9c5e](https://bsd-hardware.info/?probe=38310a9c5e) | Jul 30, 2023 |
| HP            | 213D A01                    | [802a71b9f6](https://bsd-hardware.info/?probe=802a71b9f6) | Jul 29, 2023 |
| ASRockRack    | X470D4U                     | [fc2a96cc75](https://bsd-hardware.info/?probe=fc2a96cc75) | Jul 29, 2023 |
| Dell          | 0HD5W2 A00                  | [ce83168854](https://bsd-hardware.info/?probe=ce83168854) | Jul 29, 2023 |
| Dell          | 05XGC8 A01                  | [06e6afb4f1](https://bsd-hardware.info/?probe=06e6afb4f1) | Jul 28, 2023 |
| HP            | 18E4                        | [6a0ce7d626](https://bsd-hardware.info/?probe=6a0ce7d626) | Jul 28, 2023 |
| Techvision    | TVI7309X B0                 | [088f599199](https://bsd-hardware.info/?probe=088f599199) | Jul 28, 2023 |
| Dell          | 0NC2VH A01                  | [1595ce505c](https://bsd-hardware.info/?probe=1595ce505c) | Jul 28, 2023 |
| Unknown       | Unknown                     | [836d435712](https://bsd-hardware.info/?probe=836d435712) | Jul 28, 2023 |
| Unknown       | Unknown                     | [6d6a8cb863](https://bsd-hardware.info/?probe=6d6a8cb863) | Jul 28, 2023 |
| Dell          | 0KWVT8 A03                  | [fccf22f7a7](https://bsd-hardware.info/?probe=fccf22f7a7) | Jul 27, 2023 |
| Unknown       | Unknown                     | [9d078811ba](https://bsd-hardware.info/?probe=9d078811ba) | Jul 27, 2023 |
| Unknown       | Unknown                     | [dbb7d95d59](https://bsd-hardware.info/?probe=dbb7d95d59) | Jul 27, 2023 |
| Unknown       | Unknown                     | [7841057467](https://bsd-hardware.info/?probe=7841057467) | Jul 27, 2023 |
| Protectli     | VP2420                      | [87d17e77a8](https://bsd-hardware.info/?probe=87d17e77a8) | Jul 26, 2023 |
| CONTEC        | G1/EMB-CV1/iD2550           | [34f5c817fb](https://bsd-hardware.info/?probe=34f5c817fb) | Jul 26, 2023 |
| Dell          | 0NC2VH A01                  | [103e75cb64](https://bsd-hardware.info/?probe=103e75cb64) | Jul 25, 2023 |
| HP            | 339A                        | [b770568bae](https://bsd-hardware.info/?probe=b770568bae) | Jul 25, 2023 |
| Seeed Stud... | ODYSSEY-TGL-A               | [11ee31d0b3](https://bsd-hardware.info/?probe=11ee31d0b3) | Jul 24, 2023 |
| HP            | 1495                        | [3ddc49b877](https://bsd-hardware.info/?probe=3ddc49b877) | Jul 24, 2023 |
| Unknown       | Unknown                     | [bbae253aa2](https://bsd-hardware.info/?probe=bbae253aa2) | Jul 23, 2023 |
| HP            | 1495                        | [9de7021e50](https://bsd-hardware.info/?probe=9de7021e50) | Jul 23, 2023 |
| Protectli     | VP2420                      | [7f388b0128](https://bsd-hardware.info/?probe=7f388b0128) | Jul 23, 2023 |
| MSI           | H81M-P33                    | [14b1509851](https://bsd-hardware.info/?probe=14b1509851) | Jul 23, 2023 |
| ASUSTek       | P5Q-E                       | [7b725a65c4](https://bsd-hardware.info/?probe=7b725a65c4) | Jul 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [877ddd1995](https://bsd-hardware.info/?probe=877ddd1995) | Jul 23, 2023 |
| Premio        | BlueCat XMB3 00C            | [974c8673b7](https://bsd-hardware.info/?probe=974c8673b7) | Jul 23, 2023 |
| Techvision    | TVI7309X B0                 | [a2f320b278](https://bsd-hardware.info/?probe=a2f320b278) | Jul 23, 2023 |
| Unknown       | Unknown                     | [4d91799b3c](https://bsd-hardware.info/?probe=4d91799b3c) | Jul 23, 2023 |
| PC Engines    | APU2                        | [e02df69b63](https://bsd-hardware.info/?probe=e02df69b63) | Jul 23, 2023 |
| Unknown       | Unknown                     | [fb0affa930](https://bsd-hardware.info/?probe=fb0affa930) | Jul 23, 2023 |
| Intel         | S1200KP AAG34877-201        | [26d7c98e18](https://bsd-hardware.info/?probe=26d7c98e18) | Jul 22, 2023 |
| Unknown       | Unknown                     | [36ccde4a75](https://bsd-hardware.info/?probe=36ccde4a75) | Jul 22, 2023 |
| ASRock        | 970 Extreme3 R2.0           | [89f4d8e6a0](https://bsd-hardware.info/?probe=89f4d8e6a0) | Jul 22, 2023 |
| Unknown       | Unknown                     | [267063ed35](https://bsd-hardware.info/?probe=267063ed35) | Jul 22, 2023 |
| Dell          | 00V62H A00                  | [db56801c55](https://bsd-hardware.info/?probe=db56801c55) | Jul 21, 2023 |
| Unknown       | QGLK03                      | [d7396cc0e8](https://bsd-hardware.info/?probe=d7396cc0e8) | Jul 21, 2023 |
| Shuttle       | FX48 V10                    | [c0ac40d196](https://bsd-hardware.info/?probe=c0ac40d196) | Jul 21, 2023 |
| HP            | 3397                        | [c6d7ddd8e8](https://bsd-hardware.info/?probe=c6d7ddd8e8) | Jul 19, 2023 |
| Protectli     | FW4B Ver                    | [5b3f040896](https://bsd-hardware.info/?probe=5b3f040896) | Jul 19, 2023 |
| HP            | 81C5 MVB                    | [1a4fbc384d](https://bsd-hardware.info/?probe=1a4fbc384d) | Jul 19, 2023 |
| Intel         | HURONRIVER                  | [b7f28022b2](https://bsd-hardware.info/?probe=b7f28022b2) | Jul 19, 2023 |
| HP            | 1495                        | [174216c4d3](https://bsd-hardware.info/?probe=174216c4d3) | Jul 18, 2023 |
| Dell          | 0WMJ54 A01                  | [fe07363baa](https://bsd-hardware.info/?probe=fe07363baa) | Jul 18, 2023 |
| ASUSTek       | PRIME B560M-A AC            | [13985f2c0c](https://bsd-hardware.info/?probe=13985f2c0c) | Jul 18, 2023 |
| Lenovo        | ThinkServer TS140           | [b5f034579d](https://bsd-hardware.info/?probe=b5f034579d) | Jul 17, 2023 |
| Apple         | Mac-F221BEC8                | [3a5b0b3193](https://bsd-hardware.info/?probe=3a5b0b3193) | Jul 17, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [93dd663d57](https://bsd-hardware.info/?probe=93dd663d57) | Jul 16, 2023 |
| ASUSTek       | H97M-E                      | [82bc9b32bd](https://bsd-hardware.info/?probe=82bc9b32bd) | Jul 16, 2023 |
| Unknown       | Unknown                     | [a0b045dfd2](https://bsd-hardware.info/?probe=a0b045dfd2) | Jul 15, 2023 |
| HP            | 1495                        | [7756cc81eb](https://bsd-hardware.info/?probe=7756cc81eb) | Jul 15, 2023 |
| PC Engines    | APU2                        | [167d51d317](https://bsd-hardware.info/?probe=167d51d317) | Jul 14, 2023 |
| HP            | 8055                        | [1274fc1b5e](https://bsd-hardware.info/?probe=1274fc1b5e) | Jul 14, 2023 |
| Protectli     | VP2420                      | [26957c4a08](https://bsd-hardware.info/?probe=26957c4a08) | Jul 14, 2023 |
| HP            | 8299                        | [5874bc1020](https://bsd-hardware.info/?probe=5874bc1020) | Jul 14, 2023 |
| Protectli     | FW6                         | [f337c2d283](https://bsd-hardware.info/?probe=f337c2d283) | Jul 13, 2023 |
| PC Engines    | APU2                        | [a1af1a8c1d](https://bsd-hardware.info/?probe=a1af1a8c1d) | Jul 13, 2023 |
| ASUSTek       | STRIX H270I GAMING          | [f1899c02c1](https://bsd-hardware.info/?probe=f1899c02c1) | Jul 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [88fae8d98c](https://bsd-hardware.info/?probe=88fae8d98c) | Jul 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [1516e2960a](https://bsd-hardware.info/?probe=1516e2960a) | Jul 13, 2023 |
| Dell          | 02YYK5 A00                  | [32b118286e](https://bsd-hardware.info/?probe=32b118286e) | Jul 13, 2023 |
| Unknown       | Unknown                     | [c580a701d0](https://bsd-hardware.info/?probe=c580a701d0) | Jul 12, 2023 |
| Gigabyte      | B450M DS3H-CF               | [4ec99c1909](https://bsd-hardware.info/?probe=4ec99c1909) | Jul 12, 2023 |
| Unknown       | Unknown                     | [7e735a2b8f](https://bsd-hardware.info/?probe=7e735a2b8f) | Jul 12, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [d13984b682](https://bsd-hardware.info/?probe=d13984b682) | Jul 12, 2023 |
| Techvision    | TVI7309X B0                 | [3658cb969a](https://bsd-hardware.info/?probe=3658cb969a) | Jul 11, 2023 |
| Hardkernel    | ODROID-H3                   | [63f0cba062](https://bsd-hardware.info/?probe=63f0cba062) | Jul 10, 2023 |
| Unknown       | Unknown                     | [fe3184dd5b](https://bsd-hardware.info/?probe=fe3184dd5b) | Jul 10, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [a24f2cca34](https://bsd-hardware.info/?probe=a24f2cca34) | Jul 10, 2023 |
| PC Engines    | apu4                        | [8f0a65309f](https://bsd-hardware.info/?probe=8f0a65309f) | Jul 10, 2023 |
| HP            | 8299                        | [9cfe218328](https://bsd-hardware.info/?probe=9cfe218328) | Jul 10, 2023 |
| PC Engines    | apu4                        | [b82b8da585](https://bsd-hardware.info/?probe=b82b8da585) | Jul 10, 2023 |
| AZW           | EQ                          | [46754d358b](https://bsd-hardware.info/?probe=46754d358b) | Jul 10, 2023 |
| AZW           | EQ                          | [3f38b7c248](https://bsd-hardware.info/?probe=3f38b7c248) | Jul 10, 2023 |
| Protectli     | VP2420                      | [83135eaeca](https://bsd-hardware.info/?probe=83135eaeca) | Jul 10, 2023 |
| HP            | 802E                        | [298896b37a](https://bsd-hardware.info/?probe=298896b37a) | Jul 09, 2023 |
| Unknown       | QCML03                      | [63a27fdd5b](https://bsd-hardware.info/?probe=63a27fdd5b) | Jul 09, 2023 |
| Intel         | DH55TC AAE70932-206         | [bbfc2c35b1](https://bsd-hardware.info/?probe=bbfc2c35b1) | Jul 09, 2023 |
| MSI           | H81M-P33                    | [f0de15f4e2](https://bsd-hardware.info/?probe=f0de15f4e2) | Jul 09, 2023 |
| ASUSTek       | P5Q-E                       | [3bb3ebc39d](https://bsd-hardware.info/?probe=3bb3ebc39d) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [87bb7727a2](https://bsd-hardware.info/?probe=87bb7727a2) | Jul 09, 2023 |
| Seeed Stud... | ODYSSEY-TGL-A               | [264f689c35](https://bsd-hardware.info/?probe=264f689c35) | Jul 09, 2023 |
| Unknown       | Unknown                     | [7395b234bc](https://bsd-hardware.info/?probe=7395b234bc) | Jul 09, 2023 |
| Acer          | Aspire XC-830               | [b121db09fb](https://bsd-hardware.info/?probe=b121db09fb) | Jul 09, 2023 |
| Protectli     | FW1 Ver                     | [f5844f1fbd](https://bsd-hardware.info/?probe=f5844f1fbd) | Jul 09, 2023 |
| Protectli     | VP2410 10                   | [75f3eb7e81](https://bsd-hardware.info/?probe=75f3eb7e81) | Jul 08, 2023 |
| Unknown       | Unknown                     | [80eb767d39](https://bsd-hardware.info/?probe=80eb767d39) | Jul 08, 2023 |
| HP            | 3397                        | [3d32ba4cd9](https://bsd-hardware.info/?probe=3d32ba4cd9) | Jul 08, 2023 |
| Unknown       | Unknown                     | [a780f8f8ad](https://bsd-hardware.info/?probe=a780f8f8ad) | Jul 08, 2023 |
| Unknown       | Unknown                     | [273d642ff6](https://bsd-hardware.info/?probe=273d642ff6) | Jul 08, 2023 |
| Unknown       | Unknown                     | [b07e2a5b47](https://bsd-hardware.info/?probe=b07e2a5b47) | Jul 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | [2100c4c1d0](https://bsd-hardware.info/?probe=2100c4c1d0) | Jul 07, 2023 |
| HP            | 1495                        | [3e7cdee510](https://bsd-hardware.info/?probe=3e7cdee510) | Jul 07, 2023 |
| Lenovo        | ThinkCentre M81 7518E1U     | [2c818e6169](https://bsd-hardware.info/?probe=2c818e6169) | Jul 06, 2023 |
| AZW           | EQ                          | [158f9680b5](https://bsd-hardware.info/?probe=158f9680b5) | Jul 06, 2023 |
| Protectli     | FW4B Ver                    | [fd8e3ee5d6](https://bsd-hardware.info/?probe=fd8e3ee5d6) | Jul 06, 2023 |
| HP            | 8265                        | [c0f867283f](https://bsd-hardware.info/?probe=c0f867283f) | Jul 06, 2023 |
| Protectli     | FW4B Ver                    | [45dd8f839f](https://bsd-hardware.info/?probe=45dd8f839f) | Jul 06, 2023 |
| Dell          | 0WR7PY A01                  | [6a32c3663b](https://bsd-hardware.info/?probe=6a32c3663b) | Jul 05, 2023 |
| Unknown       | Unknown                     | [4060a343aa](https://bsd-hardware.info/?probe=4060a343aa) | Jul 05, 2023 |
| Dell          | 0J3C2F A02                  | [a97b53bcf5](https://bsd-hardware.info/?probe=a97b53bcf5) | Jul 05, 2023 |
| Dell          | 0NW6H5 A00                  | [2ac2980803](https://bsd-hardware.info/?probe=2ac2980803) | Jul 05, 2023 |
| Protectli     | FW4B                        | [b73a26aa23](https://bsd-hardware.info/?probe=b73a26aa23) | Jul 05, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [529a30afc2](https://bsd-hardware.info/?probe=529a30afc2) | Jul 04, 2023 |
| MW            | GMLK-2_5G4L                 | [8a446692ce](https://bsd-hardware.info/?probe=8a446692ce) | Jul 04, 2023 |
| Intel         | Q3XXG4-P V1.0               | [5838cc1cac](https://bsd-hardware.info/?probe=5838cc1cac) | Jul 04, 2023 |
| Protectli     | FW4B Ver                    | [37fd6c7e30](https://bsd-hardware.info/?probe=37fd6c7e30) | Jul 04, 2023 |
| Protectli     | FW4B Ver                    | [dc56a8a565](https://bsd-hardware.info/?probe=dc56a8a565) | Jul 04, 2023 |
| Dell          | 0WR7PY A01                  | [d1662eef0f](https://bsd-hardware.info/?probe=d1662eef0f) | Jul 04, 2023 |
| Intel         | CRESCENTBAY                 | [d919ca6b12](https://bsd-hardware.info/?probe=d919ca6b12) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [e212a51c70](https://bsd-hardware.info/?probe=e212a51c70) | Jul 03, 2023 |
| Protectli     | FW4C Ver                    | [3b591d1374](https://bsd-hardware.info/?probe=3b591d1374) | Jul 03, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [c265c181c2](https://bsd-hardware.info/?probe=c265c181c2) | Jul 03, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [4a7a333c20](https://bsd-hardware.info/?probe=4a7a333c20) | Jul 02, 2023 |
| MSI           | H81M-P33                    | [71edaf952e](https://bsd-hardware.info/?probe=71edaf952e) | Jul 02, 2023 |
| ASUSTek       | P5Q-E                       | [98254451c1](https://bsd-hardware.info/?probe=98254451c1) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [977d44457e](https://bsd-hardware.info/?probe=977d44457e) | Jul 02, 2023 |
| Dell          | 03KWTV A00                  | [d8f6429e70](https://bsd-hardware.info/?probe=d8f6429e70) | Jul 02, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | [496439b2aa](https://bsd-hardware.info/?probe=496439b2aa) | Jul 02, 2023 |
| Gigabyte      | MSQ87TN-00                  | [276b7100a2](https://bsd-hardware.info/?probe=276b7100a2) | Jul 01, 2023 |
| Gigabyte      | F2A68HM-H                   | [7cce12e9cf](https://bsd-hardware.info/?probe=7cce12e9cf) | Jul 01, 2023 |
| Protectli     | FW4A Ver                    | [997c72b98d](https://bsd-hardware.info/?probe=997c72b98d) | Jul 01, 2023 |
| Protectli     | FW6 Ver                     | [61c7be6541](https://bsd-hardware.info/?probe=61c7be6541) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [b6cfa09740](https://bsd-hardware.info/?probe=b6cfa09740) | Jun 30, 2023 |
| Protectli     | FW6 Ver                     | [5c6f36540d](https://bsd-hardware.info/?probe=5c6f36540d) | Jun 29, 2023 |
| Protectli     | VP2420                      | [950ff902c2](https://bsd-hardware.info/?probe=950ff902c2) | Jun 29, 2023 |
| Intel         | DQ67SW AAG12527-310         | [5b272b02cb](https://bsd-hardware.info/?probe=5b272b02cb) | Jun 29, 2023 |
| HP            | 8055                        | [94df572de4](https://bsd-hardware.info/?probe=94df572de4) | Jun 29, 2023 |
| Dell          | 0NW6H5 A00                  | [0cdc2b47b2](https://bsd-hardware.info/?probe=0cdc2b47b2) | Jun 29, 2023 |
| HP            | 8595                        | [e1a82ff0c5](https://bsd-hardware.info/?probe=e1a82ff0c5) | Jun 29, 2023 |
| Unknown       | Unknown                     | [41e020bc03](https://bsd-hardware.info/?probe=41e020bc03) | Jun 29, 2023 |
| Intel         | MAHOBAY                     | [4053bc358e](https://bsd-hardware.info/?probe=4053bc358e) | Jun 29, 2023 |
| Dell          | 0NC2VH A01                  | [d5a7320a8a](https://bsd-hardware.info/?probe=d5a7320a8a) | Jun 28, 2023 |
| HP            | 339A                        | [b08e1fc092](https://bsd-hardware.info/?probe=b08e1fc092) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | [4d99bc4b63](https://bsd-hardware.info/?probe=4d99bc4b63) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | [8866724f46](https://bsd-hardware.info/?probe=8866724f46) | Jun 27, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | [bc448a4c10](https://bsd-hardware.info/?probe=bc448a4c10) | Jun 27, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [489b7b6bae](https://bsd-hardware.info/?probe=489b7b6bae) | Jun 26, 2023 |
| Unknown       | Unknown                     | [cd3b925f27](https://bsd-hardware.info/?probe=cd3b925f27) | Jun 26, 2023 |
| Gigabyte      | C1037UN                     | [fccc3f4b80](https://bsd-hardware.info/?probe=fccc3f4b80) | Jun 26, 2023 |
| AZW           | EQ                          | [c410cd5c1c](https://bsd-hardware.info/?probe=c410cd5c1c) | Jun 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | [dc937eee63](https://bsd-hardware.info/?probe=dc937eee63) | Jun 25, 2023 |
| MSI           | H81M-P33                    | [80bd24461a](https://bsd-hardware.info/?probe=80bd24461a) | Jun 25, 2023 |
| ASUSTek       | P5Q-E                       | [e368d55893](https://bsd-hardware.info/?probe=e368d55893) | Jun 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [483865aca5](https://bsd-hardware.info/?probe=483865aca5) | Jun 25, 2023 |
| Unknown       | Unknown                     | [32e290d370](https://bsd-hardware.info/?probe=32e290d370) | Jun 25, 2023 |
| Protectli     | FW6 Ver                     | [6210e8f0bc](https://bsd-hardware.info/?probe=6210e8f0bc) | Jun 24, 2023 |
| Techvision    | TVI7309X B0                 | [93213fc931](https://bsd-hardware.info/?probe=93213fc931) | Jun 24, 2023 |
| Dell          | 0Y7WYT A00                  | [a931ed9f0a](https://bsd-hardware.info/?probe=a931ed9f0a) | Jun 23, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [b6916f61a8](https://bsd-hardware.info/?probe=b6916f61a8) | Jun 23, 2023 |
| AZW           | EQ                          | [8a85da80b2](https://bsd-hardware.info/?probe=8a85da80b2) | Jun 23, 2023 |
| CWWK          | CW-AD4L-N V1                | [b7ca7c7195](https://bsd-hardware.info/?probe=b7ca7c7195) | Jun 22, 2023 |
| Unknown       | Unknown                     | [f73625157c](https://bsd-hardware.info/?probe=f73625157c) | Jun 22, 2023 |
| Protectli     | VP2410                      | [94e2177a56](https://bsd-hardware.info/?probe=94e2177a56) | Jun 22, 2023 |
| Dell          | 0NW6H5 A00                  | [7d3a60d628](https://bsd-hardware.info/?probe=7d3a60d628) | Jun 22, 2023 |
| Techvision    | TVI7309X B0                 | [178a67ff39](https://bsd-hardware.info/?probe=178a67ff39) | Jun 21, 2023 |
| Dell          | 0NC2VH A01                  | [f094606e8f](https://bsd-hardware.info/?probe=f094606e8f) | Jun 21, 2023 |
| Hardkernel    | ODROID-H3                   | [8f550b0d75](https://bsd-hardware.info/?probe=8f550b0d75) | Jun 21, 2023 |
| BESSTAR Te... | TH50                        | [efc396837c](https://bsd-hardware.info/?probe=efc396837c) | Jun 21, 2023 |
| Techvision    | TVI7309X B0                 | [12d57aa9d9](https://bsd-hardware.info/?probe=12d57aa9d9) | Jun 21, 2023 |
| CWWK          | CW-AD4L-N V1                | [a09d71cc14](https://bsd-hardware.info/?probe=a09d71cc14) | Jun 21, 2023 |
| HP            | 802E                        | [595a5d4f60](https://bsd-hardware.info/?probe=595a5d4f60) | Jun 21, 2023 |
| Unknown       | Unknown                     | [d0c184ae86](https://bsd-hardware.info/?probe=d0c184ae86) | Jun 20, 2023 |
| Techvision    | TVI7309X B0                 | [1fa198f78d](https://bsd-hardware.info/?probe=1fa198f78d) | Jun 19, 2023 |
| Intel         | CRESCENTBAY                 | [e8c8da464a](https://bsd-hardware.info/?probe=e8c8da464a) | Jun 19, 2023 |
| Dell          | 07F37C A01                  | [16e5a062a2](https://bsd-hardware.info/?probe=16e5a062a2) | Jun 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [705c750691](https://bsd-hardware.info/?probe=705c750691) | Jun 17, 2023 |
| HP            | 83E9                        | [23ec260317](https://bsd-hardware.info/?probe=23ec260317) | Jun 16, 2023 |
| Unknown       | Unknown                     | [a6d5232f75](https://bsd-hardware.info/?probe=a6d5232f75) | Jun 16, 2023 |
| Unknown       | Unknown                     | [06754d9e71](https://bsd-hardware.info/?probe=06754d9e71) | Jun 15, 2023 |
| Dell          | 08NPPY A00                  | [8586467924](https://bsd-hardware.info/?probe=8586467924) | Jun 15, 2023 |
| MW            | GMLK-2_5G4L                 | [3274745a08](https://bsd-hardware.info/?probe=3274745a08) | Jun 15, 2023 |
| Protectli     | VP2420                      | [82ecf3a046](https://bsd-hardware.info/?probe=82ecf3a046) | Jun 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [6e8e70ddc2](https://bsd-hardware.info/?probe=6e8e70ddc2) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c19a29f083](https://bsd-hardware.info/?probe=c19a29f083) | Jun 13, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [33b64d3084](https://bsd-hardware.info/?probe=33b64d3084) | Jun 13, 2023 |
| Dell          | 02YYK5 A00                  | [0dc0eab687](https://bsd-hardware.info/?probe=0dc0eab687) | Jun 13, 2023 |
| Pegatron      | 2AD5                        | [751e307940](https://bsd-hardware.info/?probe=751e307940) | Jun 13, 2023 |
| HP            | 213D A01                    | [2a6603c79a](https://bsd-hardware.info/?probe=2a6603c79a) | Jun 12, 2023 |
| Dell          | 0D28YY A00                  | [9f14962984](https://bsd-hardware.info/?probe=9f14962984) | Jun 11, 2023 |
| MSI           | H81M-P33                    | [3d9a05635f](https://bsd-hardware.info/?probe=3d9a05635f) | Jun 11, 2023 |
| ASUSTek       | P5Q-E                       | [b8f3eeed4b](https://bsd-hardware.info/?probe=b8f3eeed4b) | Jun 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9c888141fb](https://bsd-hardware.info/?probe=9c888141fb) | Jun 11, 2023 |
| Protectli     | FW6 Ver                     | [3f8a97d0e7](https://bsd-hardware.info/?probe=3f8a97d0e7) | Jun 11, 2023 |
| Intel         | S1200KP AAG34877-201        | [39eba90e6a](https://bsd-hardware.info/?probe=39eba90e6a) | Jun 10, 2023 |
| Gigabyte      | C1037UN                     | [d8f7cea73b](https://bsd-hardware.info/?probe=d8f7cea73b) | Jun 10, 2023 |
| Intel         | S1200KP AAG34877-201        | [ec04f3f6d5](https://bsd-hardware.info/?probe=ec04f3f6d5) | Jun 10, 2023 |
| Protectli     | FW4B Ver                    | [af56081a76](https://bsd-hardware.info/?probe=af56081a76) | Jun 10, 2023 |
| Protectli     | FW6 Ver                     | [6cc2f54681](https://bsd-hardware.info/?probe=6cc2f54681) | Jun 10, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [7d23d1c91f](https://bsd-hardware.info/?probe=7d23d1c91f) | Jun 09, 2023 |
| PC Engines    | APU2                        | [24545e8f90](https://bsd-hardware.info/?probe=24545e8f90) | Jun 09, 2023 |
| Dell          | 0YXT71 A02                  | [e42082ba89](https://bsd-hardware.info/?probe=e42082ba89) | Jun 09, 2023 |
| MSI           | MS-7360                     | [f54096f3e5](https://bsd-hardware.info/?probe=f54096f3e5) | Jun 08, 2023 |
| ASUSTek       | M11AD                       | [7ffef5814d](https://bsd-hardware.info/?probe=7ffef5814d) | Jun 07, 2023 |
| MW            | GMLK-2_5G4L                 | [54c23902c7](https://bsd-hardware.info/?probe=54c23902c7) | Jun 07, 2023 |
| Pegatron      | 2AD5                        | [e50d3f9b86](https://bsd-hardware.info/?probe=e50d3f9b86) | Jun 06, 2023 |
| Dell          | 0NC2VH A01                  | [0b9ad8d7d8](https://bsd-hardware.info/?probe=0b9ad8d7d8) | Jun 06, 2023 |
| HP            | 843F                        | [57b6c258ad](https://bsd-hardware.info/?probe=57b6c258ad) | Jun 06, 2023 |
| Acer          | Aspire XC-1660G V:1.1       | [e07bfb044b](https://bsd-hardware.info/?probe=e07bfb044b) | Jun 06, 2023 |
| HP            | 212B                        | [4db61072c4](https://bsd-hardware.info/?probe=4db61072c4) | Jun 05, 2023 |
| MW            | GMLK-2_5G4L                 | [e137b3e686](https://bsd-hardware.info/?probe=e137b3e686) | Jun 05, 2023 |
| HP            | 339A                        | [74f857c400](https://bsd-hardware.info/?probe=74f857c400) | Jun 05, 2023 |
| MSI           | H81M-P33                    | [88598bfbf5](https://bsd-hardware.info/?probe=88598bfbf5) | Jun 04, 2023 |
| ASUSTek       | P5Q-E                       | [fac0ed387e](https://bsd-hardware.info/?probe=fac0ed387e) | Jun 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3c76deca15](https://bsd-hardware.info/?probe=3c76deca15) | Jun 04, 2023 |
| HP            | 802E                        | [2af6f8a101](https://bsd-hardware.info/?probe=2af6f8a101) | Jun 04, 2023 |
| Acer          | Aspire XC-1660G V:1.1       | [cf05481728](https://bsd-hardware.info/?probe=cf05481728) | Jun 04, 2023 |
| HP            | 805A                        | [3ad8551330](https://bsd-hardware.info/?probe=3ad8551330) | Jun 04, 2023 |
| Protectli     | FW4B Ver                    | [0f5b2ad316](https://bsd-hardware.info/?probe=0f5b2ad316) | Jun 03, 2023 |
| Unknown       | Unknown                     | [ffb4544d8c](https://bsd-hardware.info/?probe=ffb4544d8c) | Jun 03, 2023 |
| Protectli     | FW6 Ver                     | [a42fcbbc12](https://bsd-hardware.info/?probe=a42fcbbc12) | Jun 03, 2023 |
| Dell          | 08NPPY A00                  | [538e16bf08](https://bsd-hardware.info/?probe=538e16bf08) | Jun 03, 2023 |
| AAEON         | FWS-2360 V1.0               | [bcb707d6d0](https://bsd-hardware.info/?probe=bcb707d6d0) | Jun 02, 2023 |
| Unknown       | Unknown                     | [2702f3486a](https://bsd-hardware.info/?probe=2702f3486a) | Jun 02, 2023 |
| ASRockRack    | X570D4U-2L2T                | [4cada5d71b](https://bsd-hardware.info/?probe=4cada5d71b) | Jun 02, 2023 |
| Unknown       | Unknown                     | [09b74995b7](https://bsd-hardware.info/?probe=09b74995b7) | Jun 02, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [2348a2736e](https://bsd-hardware.info/?probe=2348a2736e) | Jun 02, 2023 |
| Unknown       | Unknown                     | [a3bc187a6b](https://bsd-hardware.info/?probe=a3bc187a6b) | Jun 02, 2023 |
| HP            | 805A                        | [b50fd38c94](https://bsd-hardware.info/?probe=b50fd38c94) | Jun 01, 2023 |
| Intel         | Q3XXG4-P V1.0               | [ef66603fb9](https://bsd-hardware.info/?probe=ef66603fb9) | Jun 01, 2023 |
| ASRock        | FM2A78M-ITX+                | [aecc8b1372](https://bsd-hardware.info/?probe=aecc8b1372) | Jun 01, 2023 |
| Dell          | 05XGC8 A01                  | [c40e01cab3](https://bsd-hardware.info/?probe=c40e01cab3) | Jun 01, 2023 |
| Acer          | Aspire XC-1660G V:1.1       | [8b0669a87d](https://bsd-hardware.info/?probe=8b0669a87d) | May 31, 2023 |
| HP            | 802E                        | [2b1f2776cd](https://bsd-hardware.info/?probe=2b1f2776cd) | May 31, 2023 |
| Gigabyte      | C1037UN                     | [7502577edc](https://bsd-hardware.info/?probe=7502577edc) | May 31, 2023 |
| CWWK          | CW-AD4L-N V1                | [d5a2882e49](https://bsd-hardware.info/?probe=d5a2882e49) | May 31, 2023 |
| Unknown       | Unknown                     | [f6643f3b06](https://bsd-hardware.info/?probe=f6643f3b06) | May 31, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [c7f2f78173](https://bsd-hardware.info/?probe=c7f2f78173) | May 31, 2023 |
| Gigabyte      | C1037UN                     | [79e0162b9c](https://bsd-hardware.info/?probe=79e0162b9c) | May 30, 2023 |
| Intel         | S1200KP AAG34877-201        | [b264e962d0](https://bsd-hardware.info/?probe=b264e962d0) | May 30, 2023 |
| Dell          | 00V62H A01                  | [7d2e30807a](https://bsd-hardware.info/?probe=7d2e30807a) | May 30, 2023 |
| Protectli     | FW6 Ver                     | [21bad05407](https://bsd-hardware.info/?probe=21bad05407) | May 29, 2023 |
| Intel         | SKYBAY                      | [86747c5b22](https://bsd-hardware.info/?probe=86747c5b22) | May 29, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [a12b5d1715](https://bsd-hardware.info/?probe=a12b5d1715) | May 29, 2023 |
| Intel         | JSL MRD                     | [6fa703d206](https://bsd-hardware.info/?probe=6fa703d206) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [28c84f71fd](https://bsd-hardware.info/?probe=28c84f71fd) | May 28, 2023 |
| ASUSTek       | P5Q-E                       | [cf8b2af78b](https://bsd-hardware.info/?probe=cf8b2af78b) | May 28, 2023 |
| Intel         | JSL MRD                     | [fc7970abd1](https://bsd-hardware.info/?probe=fc7970abd1) | May 28, 2023 |
| PC Engines    | APU2                        | [4c27451012](https://bsd-hardware.info/?probe=4c27451012) | May 28, 2023 |
| PC Engines    | APU2                        | [6b276a70c5](https://bsd-hardware.info/?probe=6b276a70c5) | May 28, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [3560dcfedc](https://bsd-hardware.info/?probe=3560dcfedc) | May 27, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [2caaa9f6cf](https://bsd-hardware.info/?probe=2caaa9f6cf) | May 27, 2023 |
| ASRock        | H270M-ITX/ac                | [69aaebd77e](https://bsd-hardware.info/?probe=69aaebd77e) | May 27, 2023 |
| Unknown       | Unknown                     | [0918049f45](https://bsd-hardware.info/?probe=0918049f45) | May 27, 2023 |
| Intel         | S1200KP AAG34877-201        | [5bf84ec376](https://bsd-hardware.info/?probe=5bf84ec376) | May 27, 2023 |
| Protectli     | FW6                         | [f7626db73e](https://bsd-hardware.info/?probe=f7626db73e) | May 27, 2023 |
| ASUSTek       | Z97-E/USB                   | [dbda738a56](https://bsd-hardware.info/?probe=dbda738a56) | May 27, 2023 |
| Dell          | 051FJ8 A02                  | [d0d211e4e7](https://bsd-hardware.info/?probe=d0d211e4e7) | May 27, 2023 |
| ChangWang     | CW56-58                     | [b6b902639c](https://bsd-hardware.info/?probe=b6b902639c) | May 27, 2023 |
| Dell          | 051FJ8 A02                  | [8ba976666f](https://bsd-hardware.info/?probe=8ba976666f) | May 27, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [8514299fe4](https://bsd-hardware.info/?probe=8514299fe4) | May 26, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [19c6226530](https://bsd-hardware.info/?probe=19c6226530) | May 26, 2023 |
| Protectli     | VP2420                      | [2b716b3dd3](https://bsd-hardware.info/?probe=2b716b3dd3) | May 26, 2023 |
| Protectli     | FW4B Ver                    | [90b4ae806f](https://bsd-hardware.info/?probe=90b4ae806f) | May 25, 2023 |
| HP            | 8299                        | [14a7b5fc70](https://bsd-hardware.info/?probe=14a7b5fc70) | May 24, 2023 |
| Unknown       | Unknown                     | [a9d20f955e](https://bsd-hardware.info/?probe=a9d20f955e) | May 24, 2023 |
| Dell          | 0NC2VH A01                  | [572d966731](https://bsd-hardware.info/?probe=572d966731) | May 24, 2023 |
| ASUSTek       | PRIME A520M-A II            | [eba55377e0](https://bsd-hardware.info/?probe=eba55377e0) | May 22, 2023 |
| Supermicro    | X8SIL                       | [21823c6dbd](https://bsd-hardware.info/?probe=21823c6dbd) | May 22, 2023 |
| Unknown       | Unknown                     | [b5e5e8e2cc](https://bsd-hardware.info/?probe=b5e5e8e2cc) | May 21, 2023 |
| MSI           | H81M-P33                    | [cadb0f588f](https://bsd-hardware.info/?probe=cadb0f588f) | May 21, 2023 |
| ASUSTek       | P5Q-E                       | [4a55c4a669](https://bsd-hardware.info/?probe=4a55c4a669) | May 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f2fb56c7dc](https://bsd-hardware.info/?probe=f2fb56c7dc) | May 21, 2023 |
| Intel         | Q3XXG4-P V1.0               | [7c28bf2d83](https://bsd-hardware.info/?probe=7c28bf2d83) | May 20, 2023 |
| Gigabyte      | X570 UD                     | [5576c293d8](https://bsd-hardware.info/?probe=5576c293d8) | May 20, 2023 |
| ASUSTek       | Z87M-PLUS                   | [58da7daed7](https://bsd-hardware.info/?probe=58da7daed7) | May 20, 2023 |
| ASUSTek       | Z97-E/USB                   | [484774ff19](https://bsd-hardware.info/?probe=484774ff19) | May 19, 2023 |
| HP            | 18E7                        | [477f3d4c80](https://bsd-hardware.info/?probe=477f3d4c80) | May 19, 2023 |
| Shuttle       | FH270                       | [95b532312a](https://bsd-hardware.info/?probe=95b532312a) | May 18, 2023 |
| Supermicro    | X7SBL                       | [b5ba4ba0e8](https://bsd-hardware.info/?probe=b5ba4ba0e8) | May 18, 2023 |
| Protectli     | FW4C                        | [a8252edc71](https://bsd-hardware.info/?probe=a8252edc71) | May 18, 2023 |
| HP            | 8299                        | [6d2f149a51](https://bsd-hardware.info/?probe=6d2f149a51) | May 18, 2023 |
| Techvision    | TVI7309X B0                 | [c4546c2b83](https://bsd-hardware.info/?probe=c4546c2b83) | May 17, 2023 |
| MW            | GMLK-2_5G4L                 | [39516c2e91](https://bsd-hardware.info/?probe=39516c2e91) | May 16, 2023 |
| MSI           | Z170A PC MATE               | [9c08a669ab](https://bsd-hardware.info/?probe=9c08a669ab) | May 16, 2023 |
| MSI           | Z170A PC MATE               | [75a9fd684a](https://bsd-hardware.info/?probe=75a9fd684a) | May 16, 2023 |
| MSI           | H81TI                       | [798ddd2aa1](https://bsd-hardware.info/?probe=798ddd2aa1) | May 16, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [27be69ed61](https://bsd-hardware.info/?probe=27be69ed61) | May 15, 2023 |
| MW            | GMLK-2_5G4L                 | [bc475b9528](https://bsd-hardware.info/?probe=bc475b9528) | May 15, 2023 |
| Protectli     | FW6 Ver                     | [ea9ff40bdb](https://bsd-hardware.info/?probe=ea9ff40bdb) | May 14, 2023 |
| ASRock        | 4X4-V1000                   | [189073c58e](https://bsd-hardware.info/?probe=189073c58e) | May 14, 2023 |
| HP            | 8054                        | [1ffc97728a](https://bsd-hardware.info/?probe=1ffc97728a) | May 14, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [cb87f3725f](https://bsd-hardware.info/?probe=cb87f3725f) | May 14, 2023 |
| MSI           | H81M-P33                    | [ebf1ee8152](https://bsd-hardware.info/?probe=ebf1ee8152) | May 14, 2023 |
| ASUSTek       | P5Q-E                       | [2bf04b4cf1](https://bsd-hardware.info/?probe=2bf04b4cf1) | May 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ae7796a444](https://bsd-hardware.info/?probe=ae7796a444) | May 14, 2023 |
| Protectli     | FW1 Ver                     | [824016ccf0](https://bsd-hardware.info/?probe=824016ccf0) | May 14, 2023 |
| Dell          | 0MGK50 A01                  | [4222f2f8a5](https://bsd-hardware.info/?probe=4222f2f8a5) | May 13, 2023 |
| Unknown       | N4000                       | [48742290f1](https://bsd-hardware.info/?probe=48742290f1) | May 13, 2023 |
| Dell          | 0PC5F7 A02                  | [b22c9a0cdf](https://bsd-hardware.info/?probe=b22c9a0cdf) | May 13, 2023 |
| Unknown       | Unknown                     | [00a94d98fb](https://bsd-hardware.info/?probe=00a94d98fb) | May 13, 2023 |
| Unknown       | Unknown                     | [2e9d95aed5](https://bsd-hardware.info/?probe=2e9d95aed5) | May 13, 2023 |
| MSI           | PRO B550M-VC WIFI           | [1daa68fb84](https://bsd-hardware.info/?probe=1daa68fb84) | May 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [a477479a00](https://bsd-hardware.info/?probe=a477479a00) | May 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [de9fcd9543](https://bsd-hardware.info/?probe=de9fcd9543) | May 13, 2023 |
| Dell          | 02YYK5 A00                  | [71e4a5f1ec](https://bsd-hardware.info/?probe=71e4a5f1ec) | May 13, 2023 |
| BCM Advanc... | MX81HV/MX81H 10             | [f58c8bdd86](https://bsd-hardware.info/?probe=f58c8bdd86) | May 13, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [a7fe22ce82](https://bsd-hardware.info/?probe=a7fe22ce82) | May 13, 2023 |
| Biostar       | H61MGC                      | [001611da7e](https://bsd-hardware.info/?probe=001611da7e) | May 12, 2023 |
| Unknown       | YL-J3160L4                  | [fc9a0ecef6](https://bsd-hardware.info/?probe=fc9a0ecef6) | May 12, 2023 |
| JHZD          | BQM5                        | [6b32c22615](https://bsd-hardware.info/?probe=6b32c22615) | May 12, 2023 |
| JHZD          | BQM5                        | [fbbaf0b924](https://bsd-hardware.info/?probe=fbbaf0b924) | May 11, 2023 |
| Protectli     | FW6 Ver                     | [fc8375381d](https://bsd-hardware.info/?probe=fc8375381d) | May 11, 2023 |
| ASRock        | H370M-ITX/ac                | [1e9cfaf845](https://bsd-hardware.info/?probe=1e9cfaf845) | May 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [834174a5a8](https://bsd-hardware.info/?probe=834174a5a8) | May 11, 2023 |
| HP            | 1588h                       | [f1d543fb77](https://bsd-hardware.info/?probe=f1d543fb77) | May 11, 2023 |
| Protectli     | FW6 Ver                     | [f76a340f4a](https://bsd-hardware.info/?probe=f76a340f4a) | May 11, 2023 |
| Protectli     | FW6                         | [37432c6de1](https://bsd-hardware.info/?probe=37432c6de1) | May 10, 2023 |
| Dell          | 0Y7WYT A00                  | [89abd9548b](https://bsd-hardware.info/?probe=89abd9548b) | May 10, 2023 |
| Lenovo        | 3111 SDK0J40705 WIN 3425... | [42b97c3277](https://bsd-hardware.info/?probe=42b97c3277) | May 10, 2023 |
| Dell          | 0NV0M7 A01                  | [72cdd452c8](https://bsd-hardware.info/?probe=72cdd452c8) | May 10, 2023 |
| Intel         | Q3XXG4-P V1.0               | [3359e9a10e](https://bsd-hardware.info/?probe=3359e9a10e) | May 10, 2023 |
| Lenovo        | 3111 SDK0J40705 WIN 3425... | [df84be1ef9](https://bsd-hardware.info/?probe=df84be1ef9) | May 10, 2023 |
| ASUSTek       | P10S-E Series               | [37451da8a7](https://bsd-hardware.info/?probe=37451da8a7) | May 08, 2023 |
| Dell          | 040DDP A01                  | [d5fa48cd90](https://bsd-hardware.info/?probe=d5fa48cd90) | May 07, 2023 |
| MSI           | H81M-P33                    | [55cfed4de4](https://bsd-hardware.info/?probe=55cfed4de4) | May 07, 2023 |
| ASUSTek       | P5Q-E                       | [0cb51a327e](https://bsd-hardware.info/?probe=0cb51a327e) | May 07, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7e41914431](https://bsd-hardware.info/?probe=7e41914431) | May 07, 2023 |
| Supermicro    | X11SDV-4C-TP8F-01           | [733c921923](https://bsd-hardware.info/?probe=733c921923) | May 07, 2023 |
| Dell          | 0HD5W2 A01                  | [a583770abc](https://bsd-hardware.info/?probe=a583770abc) | May 07, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f2ea102ee1](https://bsd-hardware.info/?probe=f2ea102ee1) | May 06, 2023 |
| ASRock        | X570 PG Velocita            | [46925c3dda](https://bsd-hardware.info/?probe=46925c3dda) | May 06, 2023 |
| AZW           | MINI S 10                   | [123024f70d](https://bsd-hardware.info/?probe=123024f70d) | May 06, 2023 |
| Dell          | 0Y7WYT A00                  | [dfb339020a](https://bsd-hardware.info/?probe=dfb339020a) | May 06, 2023 |
| Dell          | 0NV0M7 A01                  | [85256a78f6](https://bsd-hardware.info/?probe=85256a78f6) | May 05, 2023 |
| Unknown       | Unknown                     | [2002ddd198](https://bsd-hardware.info/?probe=2002ddd198) | May 05, 2023 |
| Protectli     | VP2420                      | [3fcbd494fc](https://bsd-hardware.info/?probe=3fcbd494fc) | May 05, 2023 |
| Supermicro    | X11SCV-Q                    | [7a6949713d](https://bsd-hardware.info/?probe=7a6949713d) | May 05, 2023 |
| CWWK          | MINIPC-G12                  | [f2ab15324b](https://bsd-hardware.info/?probe=f2ab15324b) | May 05, 2023 |
| ASUSTek       | PRIME B560M-A AC            | [bdd112ce9b](https://bsd-hardware.info/?probe=bdd112ce9b) | May 05, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [982f87fd4d](https://bsd-hardware.info/?probe=982f87fd4d) | May 05, 2023 |
| Dell          | 0F6X5P A00                  | [ba619e879e](https://bsd-hardware.info/?probe=ba619e879e) | May 04, 2023 |
| GoWin Solu... | R86S                        | [a1274a9d0c](https://bsd-hardware.info/?probe=a1274a9d0c) | May 04, 2023 |
| Intel         | DQ77KB AAG81483-501         | [38f47bf53f](https://bsd-hardware.info/?probe=38f47bf53f) | May 04, 2023 |
| Protectli     | FW6 Ver                     | [5e30b0e6b1](https://bsd-hardware.info/?probe=5e30b0e6b1) | May 04, 2023 |
| Unknown       | Unknown                     | [c430ceb253](https://bsd-hardware.info/?probe=c430ceb253) | May 04, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [31c9c606ab](https://bsd-hardware.info/?probe=31c9c606ab) | May 04, 2023 |
| Unknown       | QSKL01                      | [4277dc49d0](https://bsd-hardware.info/?probe=4277dc49d0) | May 04, 2023 |
| Dell          | 0252PH A04                  | [0cc9ef6521](https://bsd-hardware.info/?probe=0cc9ef6521) | May 03, 2023 |
| Dell          | 0252PH A04                  | [acaf59c3d5](https://bsd-hardware.info/?probe=acaf59c3d5) | May 03, 2023 |
| HP            | 82B4                        | [1bcefd3823](https://bsd-hardware.info/?probe=1bcefd3823) | May 02, 2023 |
| Dell          | 0T7D40 A00                  | [83ccb5ff07](https://bsd-hardware.info/?probe=83ccb5ff07) | May 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3f089673e0](https://bsd-hardware.info/?probe=3f089673e0) | May 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [396d7f268c](https://bsd-hardware.info/?probe=396d7f268c) | May 01, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [a59b6fc6dc](https://bsd-hardware.info/?probe=a59b6fc6dc) | Apr 30, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [2cc6521d1f](https://bsd-hardware.info/?probe=2cc6521d1f) | Apr 30, 2023 |
| Dell          | 0FF3FN A00                  | [717b46840a](https://bsd-hardware.info/?probe=717b46840a) | Apr 30, 2023 |
| Dell          | 0H634K A00                  | [5e783a1c2e](https://bsd-hardware.info/?probe=5e783a1c2e) | Apr 30, 2023 |
| MSI           | H81M-P33                    | [e28acf1164](https://bsd-hardware.info/?probe=e28acf1164) | Apr 30, 2023 |
| ASUSTek       | P5Q-E                       | [33d1b6e2d2](https://bsd-hardware.info/?probe=33d1b6e2d2) | Apr 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b0d9eaaceb](https://bsd-hardware.info/?probe=b0d9eaaceb) | Apr 30, 2023 |
| Gigabyte      | B450M DS3H-CF               | [2b922b7925](https://bsd-hardware.info/?probe=2b922b7925) | Apr 30, 2023 |
| HP            | 83E1                        | [d3e5e9a563](https://bsd-hardware.info/?probe=d3e5e9a563) | Apr 30, 2023 |
| Dell          | 00V62H A00                  | [ad97036f62](https://bsd-hardware.info/?probe=ad97036f62) | Apr 29, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | [dbdb6539fb](https://bsd-hardware.info/?probe=dbdb6539fb) | Apr 29, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/USA/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| OPNsense 23.1.11 | 96       | 3.22%   |
| OPNsense 21.7.7  | 67       | 2.25%   |
| OPNsense 22.7.10 | 63       | 2.12%   |
| OPNsense 23.1    | 58       | 1.95%   |
| OPNsense 23.1.7  | 56       | 1.88%   |
| OPNsense 21.7.3  | 56       | 1.88%   |
| OPNsense 22.1.10 | 54       | 1.81%   |
| OPNsense 23.1.5  | 52       | 1.75%   |
| OPNsense 23.7.10 | 51       | 1.71%   |
| OPNsense 23.7.1  | 51       | 1.71%   |
| OPNsense 22.7.4  | 51       | 1.71%   |
| OPNsense 23.7.9  | 49       | 1.65%   |
| OPNsense 21.1.5  | 49       | 1.65%   |
| OPNsense 23.7.7  | 47       | 1.58%   |
| OPNsense 22.1    | 47       | 1.58%   |
| OPNsense 23.1.1  | 46       | 1.54%   |
| OPNsense 20.7.8  | 46       | 1.54%   |
| OPNsense 21.7.1  | 45       | 1.51%   |
| OPNsense 22.1.8  | 44       | 1.48%   |
| OPNsense 21.1.3  | 43       | 1.44%   |
| OPNsense 23.7.3  | 42       | 1.41%   |
| OPNsense 23.1.6  | 41       | 1.38%   |
| OPNsense 21.1.4  | 40       | 1.34%   |
| OPNsense 23.1.9  | 39       | 1.31%   |
| OPNsense 22.7.8  | 38       | 1.28%   |
| OPNsense 21.1    | 38       | 1.28%   |
| OPNsense 21.1.8  | 37       | 1.24%   |
| OPNsense 23.7.8  | 35       | 1.18%   |
| OPNsense 23.7    | 35       | 1.18%   |
| OPNsense 22.7.11 | 34       | 1.14%   |
| OPNsense 22.1.6  | 34       | 1.14%   |
| OPNsense 22.1.2  | 34       | 1.14%   |
| OPNsense 22.7.6  | 33       | 1.11%   |
| OPNsense 23.1.3  | 32       | 1.07%   |
| OPNsense 22.7.7  | 32       | 1.07%   |
| OPNsense 22.7.9  | 31       | 1.04%   |
| OPNsense 22.1.4  | 31       | 1.04%   |
| OPNsense 21.1.1  | 30       | 1.01%   |
| OPNsense 21.7.6  | 29       | 0.97%   |
| OPNsense 23.7.4  | 28       | 0.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 1536     | 74.89%  |
| FreeBSD     | 249      | 12.14%  |
| helloSystem | 119      | 5.8%    |
| OpenBSD     | 41       | 2%      |
| GhostBSD    | 23       | 1.12%   |
| NomadBSD    | 17       | 0.83%   |
| pfSense     | 15       | 0.73%   |
| FreeNAS     | 14       | 0.68%   |
| MidnightBSD | 13       | 0.63%   |
| TrueNAS     | 9        | 0.44%   |
| NetBSD      | 5        | 0.24%   |
| XigmaNAS    | 2        | 0.1%    |
| OS108       | 2        | 0.1%    |
| HardenedBSD | 2        | 0.1%    |
| MyBee       | 1        | 0.05%   |
| FuryBSD     | 1        | 0.05%   |
| DragonFly   | 1        | 0.05%   |
| ClonOS      | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 2015     | 98.92%  |
| i386    | 9        | 0.44%   |
| arm64   | 9        | 0.44%   |
| powerpc | 3        | 0.15%   |
| sparc64 | 1        | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 1710     | 82.57%  |
| helloDesktop  | 129      | 6.23%   |
| XFCE          | 41       | 1.98%   |
| KDE5          | 39       | 1.88%   |
| MATE          | 35       | 1.69%   |
| TWM           | 27       | 1.3%    |
| GNOME         | 23       | 1.11%   |
| Openbox       | 20       | 0.97%   |
| fvwm          | 18       | 0.87%   |
| i3            | 12       | 0.58%   |
| Cinnamon      | 4        | 0.19%   |
| Lumina        | 3        | 0.14%   |
| Enlightenment | 3        | 0.14%   |
| Picom         | 2        | 0.1%    |
| Xfwm4         | 1        | 0.05%   |
| Window Maker  | 1        | 0.05%   |
| fvwm2         | 1        | 0.05%   |
| Fluxbox       | 1        | 0.05%   |
| DWM           | 1        | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 1719     | 83.89%  |
| X11     | 329      | 16.06%  |
| Wayland | 1        | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 1790     | 87.27%  |
| SLiM    | 151      | 7.36%   |
| LightDM | 38       | 1.85%   |
| SDDM    | 34       | 1.66%   |
| XDM     | 24       | 1.17%   |
| GDM     | 14       | 0.68%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Desktops | Percent |
|-----------------|----------|---------|
| Unknown         | 1697     | 81.47%  |
| en_US           | 200      | 9.6%    |
| C               | 159      | 7.63%   |
| en              | 13       | 0.62%   |
| fr_FR           | 5        | 0.24%   |
| fr              | 4        | 0.19%   |
| ru_RU           | 1        | 0.05%   |
| ru              | 1        | 0.05%   |
| en_US.utf-8     | 1        | 0.05%   |
| en_US.ISO8859-1 | 1        | 0.05%   |
| en_GB           | 1        | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 1819     | 87.79%  |
| BIOS | 253      | 12.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 1143     | 54.25%  |
| Zfs     | 878      | 41.67%  |
| Cd9660  | 43       | 2.04%   |
| Ffs     | 41       | 1.95%   |
| Hammer2 | 1        | 0.05%   |
| Unknown | 1        | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1927     | 93.63%  |
| MBR     | 117      | 5.69%   |
| Unknown | 11       | 0.53%   |
| BSD     | 3        | 0.15%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Dell                       | 268      | 13.16%  |
| Unknown                    | 244      | 11.98%  |
| Protectli                  | 235      | 11.54%  |
| Hewlett-Packard            | 184      | 9.03%   |
| ASUSTek Computer           | 172      | 8.44%   |
| ASRock                     | 115      | 5.65%   |
| Intel                      | 110      | 5.4%    |
| Supermicro                 | 106      | 5.2%    |
| Gigabyte Technology        | 88       | 4.32%   |
| MSI                        | 78       | 3.83%   |
| Lenovo                     | 70       | 3.44%   |
| PC Engines                 | 42       | 2.06%   |
| Techvision                 | 27       | 1.33%   |
| AZW                        | 26       | 1.28%   |
| MW                         | 15       | 0.74%   |
| CWWK                       | 14       | 0.69%   |
| Biostar                    | 13       | 0.64%   |
| Acer                       | 13       | 0.64%   |
| ASRockRack                 | 11       | 0.54%   |
| Shuttle                    | 10       | 0.49%   |
| Seeed Studio               | 9        | 0.44%   |
| Apple                      | 9        | 0.44%   |
| Foxconn                    | 8        | 0.39%   |
| HARDKERNEL                 | 7        | 0.34%   |
| GoWin Solution             | 7        | 0.34%   |
| Fujitsu                    | 7        | 0.34%   |
| CheckPoint                 | 7        | 0.34%   |
| IceWhale Technology        | 6        | 0.29%   |
| AAEON                      | 6        | 0.29%   |
| SeeedStudio                | 5        | 0.25%   |
| Pegatron                   | 5        | 0.25%   |
| CncTion                    | 5        | 0.25%   |
| Cisco                      | 5        | 0.25%   |
| BESSTAR Tech               | 5        | 0.25%   |
| TYAN Computer              | 4        | 0.2%    |
| ShenZhen MinWin Technology | 4        | 0.2%    |
| MiTAC                      | 4        | 0.2%    |
| Google                     | 4        | 0.2%    |
| ECS                        | 4        | 0.2%    |
| Alienware                  | 4        | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Unknown                     | 247      | 12.13%  |
| Protectli FW4B              | 75       | 3.68%   |
| Protectli FW6               | 62       | 3.04%   |
| Intel Q3XXG4-P V1.0         | 42       | 2.06%   |
| Dell OptiPlex 9020          | 28       | 1.37%   |
| Techvision TVI7309X         | 27       | 1.33%   |
| Dell OptiPlex 3020          | 26       | 1.28%   |
| HP t620 PLUS Quad Core TC   | 25       | 1.23%   |
| ASUS All Series             | 25       | 1.23%   |
| Supermicro X9SCL/X9SCM      | 21       | 1.03%   |
| PC Engines APU2             | 20       | 0.98%   |
| Dell OptiPlex 7010          | 20       | 0.98%   |
| PC Engines apu4             | 17       | 0.83%   |
| Protectli VP2420            | 15       | 0.74%   |
| Protectli VP2410            | 15       | 0.74%   |
| MW GMLK-2_5G4L              | 15       | 0.74%   |
| Protectli FW4C              | 14       | 0.69%   |
| Protectli FW2B              | 14       | 0.69%   |
| Dell OptiPlex 7040          | 14       | 0.69%   |
| Dell OptiPlex 990           | 13       | 0.64%   |
| HP EliteDesk 800 G1 SFF     | 12       | 0.59%   |
| Protectli FW1               | 11       | 0.54%   |
| HP EliteDesk 800 G3 SFF     | 11       | 0.54%   |
| AZW EQ                      | 11       | 0.54%   |
| Dell OptiPlex 9010          | 10       | 0.49%   |
| Dell OptiPlex 790           | 10       | 0.49%   |
| Dell OptiPlex 3040          | 10       | 0.49%   |
| Intel Nobilis               | 9        | 0.44%   |
| HP ProDesk 600 G1 SFF       | 9        | 0.44%   |
| HP Compaq Elite 8300 SFF    | 9        | 0.44%   |
| Dell OptiPlex 390           | 9        | 0.44%   |
| Protectli FW4A              | 8        | 0.39%   |
| Dell OptiPlex 7020          | 8        | 0.39%   |
| ASUS TUF Gaming X570-PLUS   | 8        | 0.39%   |
| Protectli FW6E              | 7        | 0.34%   |
| Protectli FW6D              | 7        | 0.34%   |
| HP EliteDesk 800 G2 SFF     | 7        | 0.34%   |
| HP Compaq 8200 Elite SFF PC | 7        | 0.34%   |
| Dell OptiPlex 3060          | 7        | 0.34%   |
| CWWK CW-AD4L-N V1           | 7        | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 247      | 12.13%  |
| Dell OptiPlex       | 214      | 10.51%  |
| Protectli FW4B      | 75       | 3.68%   |
| Protectli FW6       | 62       | 3.04%   |
| Lenovo ThinkCentre  | 49       | 2.41%   |
| HP EliteDesk        | 49       | 2.41%   |
| Intel Q3XXG4-P      | 43       | 2.11%   |
| HP ProDesk          | 33       | 1.62%   |
| ASUS ROG            | 31       | 1.52%   |
| Techvision TVI7309X | 27       | 1.33%   |
| HP t620             | 27       | 1.33%   |
| ASUS TUF            | 27       | 1.33%   |
| ASUS PRIME          | 27       | 1.33%   |
| HP Compaq           | 25       | 1.23%   |
| ASUS All            | 25       | 1.23%   |
| Supermicro X9SCL    | 21       | 1.03%   |
| PC Engines APU2     | 20       | 0.98%   |
| Dell Precision      | 18       | 0.88%   |
| Dell Inspiron       | 18       | 0.88%   |
| PC Engines apu4     | 17       | 0.83%   |
| Protectli VP2420    | 15       | 0.74%   |
| Protectli VP2410    | 15       | 0.74%   |
| MW GMLK-2           | 15       | 0.74%   |
| ASRock X570         | 15       | 0.74%   |
| Protectli FW4C      | 14       | 0.69%   |
| Protectli FW2B      | 14       | 0.69%   |
| Protectli FW1       | 11       | 0.54%   |
| AZW EQ              | 11       | 0.54%   |
| Acer Aspire         | 10       | 0.49%   |
| Intel Nobilis       | 9        | 0.44%   |
| Protectli FW4A      | 8        | 0.39%   |
| HP Slim             | 8        | 0.39%   |
| Protectli FW6E      | 7        | 0.34%   |
| Protectli FW6D      | 7        | 0.34%   |
| Lenovo IdeaCentre   | 7        | 0.34%   |
| HP Pavilion         | 7        | 0.34%   |
| Gigabyte X570       | 7        | 0.34%   |
| CWWK CW-AD4L-N      | 7        | 0.34%   |
| AZW GK55            | 7        | 0.34%   |
| Supermicro X7SPA-HF | 6        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 274      | 13.45%  |
| 2022    | 225      | 11.05%  |
| 2019    | 201      | 9.87%   |
| 2016    | 181      | 8.89%   |
| 2021    | 160      | 7.85%   |
| 2014    | 153      | 7.51%   |
| 2020    | 135      | 6.63%   |
| 2013    | 114      | 5.6%    |
| 2011    | 102      | 5.01%   |
| 2012    | 95       | 4.66%   |
| 2017    | 92       | 4.52%   |
| 2023    | 91       | 4.47%   |
| 2015    | 70       | 3.44%   |
| 2010    | 46       | 2.26%   |
| 2008    | 31       | 1.52%   |
| Unknown | 28       | 1.37%   |
| 2009    | 25       | 1.23%   |
| 2007    | 8        | 0.39%   |
| 2006    | 2        | 0.1%    |
| 2004    | 2        | 0.1%    |
| 2003    | 1        | 0.05%   |
| 2001    | 1        | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2037     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1934     | 94.94%  |
| Yes  | 103      | 5.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 755      | 35.95%  |
| 16.01-24.0      | 577      | 27.48%  |
| 4.01-8.0        | 288      | 13.71%  |
| 32.01-64.0      | 278      | 13.24%  |
| 64.01-256.0     | 95       | 4.52%   |
| 24.01-32.0      | 43       | 2.05%   |
| 2.01-3.0        | 36       | 1.71%   |
| 3.01-4.0        | 9        | 0.43%   |
| 0.51-1.0        | 8        | 0.38%   |
| 1.01-2.0        | 5        | 0.24%   |
| 0.01-0.5        | 4        | 0.19%   |
| More than 256.0 | 2        | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 895      | 41.9%   |
| 0.51-1.0    | 715      | 33.47%  |
| 1.01-2.0    | 336      | 15.73%  |
| 2.01-3.0    | 56       | 2.62%   |
| 4.01-8.0    | 39       | 1.83%   |
| 3.01-4.0    | 28       | 1.31%   |
| 8.01-16.0   | 20       | 0.94%   |
| 16.01-24.0  | 11       | 0.51%   |
| Unknown     | 10       | 0.47%   |
| 32.01-64.0  | 8        | 0.37%   |
| 24.01-32.0  | 8        | 0.37%   |
| 64.01-256.0 | 5        | 0.23%   |
| 0           | 5        | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1457     | 68.63%  |
| 2      | 259      | 12.2%   |
| 0      | 174      | 8.2%    |
| 3      | 88       | 4.15%   |
| 4      | 44       | 2.07%   |
| 5      | 31       | 1.46%   |
| 6      | 21       | 0.99%   |
| 7      | 13       | 0.61%   |
| 8      | 7        | 0.33%   |
| 9      | 6        | 0.28%   |
| 10     | 5        | 0.24%   |
| 12     | 3        | 0.14%   |
| 11     | 3        | 0.14%   |
| 21     | 2        | 0.09%   |
| 17     | 2        | 0.09%   |
| 14     | 2        | 0.09%   |
| 40     | 1        | 0.05%   |
| 26     | 1        | 0.05%   |
| 22     | 1        | 0.05%   |
| 19     | 1        | 0.05%   |
| 18     | 1        | 0.05%   |
| 13     | 1        | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1644     | 79.57%  |
| Yes       | 422      | 20.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2021     | 99.21%  |
| No        | 16       | 0.79%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1630     | 79.05%  |
| Yes       | 432      | 20.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1765     | 85.93%  |
| Yes       | 289      | 14.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| USA     | 2037     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Denver         | 36       | 1.58%   |
| Seattle        | 34       | 1.49%   |
| New York       | 30       | 1.31%   |
| Chicago        | 24       | 1.05%   |
| Austin         | 23       | 1.01%   |
| Brooklyn       | 22       | 0.96%   |
| Portland       | 21       | 0.92%   |
| Los Angeles    | 19       | 0.83%   |
| Dallas         | 18       | 0.79%   |
| Atlanta        | 18       | 0.79%   |
| Grand Rapids   | 17       | 0.74%   |
| Columbus       | 17       | 0.74%   |
| Rochester      | 16       | 0.7%    |
| Mountain View  | 15       | 0.66%   |
| Houston        | 15       | 0.66%   |
| Springfield    | 14       | 0.61%   |
| Phoenix        | 14       | 0.61%   |
| Oakland        | 13       | 0.57%   |
| Ypsilanti      | 12       | 0.53%   |
| San Francisco  | 12       | 0.53%   |
| Pittsburgh     | 11       | 0.48%   |
| Fort Worth     | 11       | 0.48%   |
| Raleigh        | 10       | 0.44%   |
| Philadelphia   | 10       | 0.44%   |
| Oklahoma City  | 10       | 0.44%   |
| Minneapolis    | 10       | 0.44%   |
| Miami          | 10       | 0.44%   |
| San Jose       | 9        | 0.39%   |
| San Antonio    | 9        | 0.39%   |
| Salt Lake City | 9        | 0.39%   |
| Orlando        | 9        | 0.39%   |
| Milwaukee      | 9        | 0.39%   |
| Jacksonville   | 9        | 0.39%   |
| Charlotte      | 9        | 0.39%   |
| Tampa          | 8        | 0.35%   |
| Salem          | 8        | 0.35%   |
| Indianapolis   | 8        | 0.35%   |
| Boston         | 8        | 0.35%   |
| Tucson         | 7        | 0.31%   |
| St Louis       | 7        | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 402      | 888    | 16.34%  |
| WDC                 | 295      | 1025   | 11.99%  |
| Seagate             | 234      | 617    | 9.51%   |
| Kingston            | 191      | 272    | 7.76%   |
| Crucial             | 121      | 181    | 4.92%   |
| Intel               | 95       | 209    | 3.86%   |
| SanDisk             | 91       | 125    | 3.7%    |
| Toshiba             | 74       | 121    | 3.01%   |
| Transcend           | 72       | 136    | 2.93%   |
| Hoodisk             | 68       | 97     | 2.76%   |
| Protectli           | 66       | 108    | 2.68%   |
| China               | 58       | 76     | 2.36%   |
| SK hynix            | 49       | 71     | 1.99%   |
| Phison              | 49       | 79     | 1.99%   |
| A-DATA Technology   | 48       | 76     | 1.95%   |
| SPCC                | 47       | 90     | 1.91%   |
| PNY                 | 46       | 70     | 1.87%   |
| Hitachi             | 40       | 99     | 1.63%   |
| Dogfish             | 29       | 52     | 1.18%   |
| BIWIN               | 24       | 41     | 0.98%   |
| Team                | 23       | 45     | 0.93%   |
| HGST                | 23       | 70     | 0.93%   |
| Hewlett-Packard     | 20       | 49     | 0.81%   |
| Micron Technology   | 17       | 24     | 0.69%   |
| OCZ                 | 16       | 24     | 0.65%   |
| Silicon Motion      | 15       | 24     | 0.61%   |
| FORESEE             | 15       | 24     | 0.61%   |
| Fanxiang            | 12       | 18     | 0.49%   |
| Apacer              | 11       | 14     | 0.45%   |
| Mushkin             | 10       | 16     | 0.41%   |
| NVMe                | 9        | 15     | 0.37%   |
| Lexar               | 9        | 10     | 0.37%   |
| Corsair             | 9        | 38     | 0.37%   |
| KIOXIA              | 8        | 14     | 0.33%   |
| KingSpec            | 8        | 12     | 0.33%   |
| Patriot             | 7        | 8      | 0.28%   |
| Innodisk            | 7        | 9      | 0.28%   |
| CWDISK              | 7        | 8      | 0.28%   |
| Zheino              | 6        | 11     | 0.24%   |
| Plextor             | 6        | 11     | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Hoodisk SSD 32GB                | 30       | 1.1%    |
| Kingston SUV500MS240G 240GB     | 24       | 0.88%   |
| Samsung SSD 850 EVO 250GB       | 23       | 0.85%   |
| Seagate ST500DM002-1BD142 500GB | 22       | 0.81%   |
| Kingston SUV500MS120G 120GB     | 21       | 0.77%   |
| Samsung SSD 860 EVO 500GB       | 20       | 0.74%   |
| Kingston SA400S37240G 240GB     | 20       | 0.74%   |
| Hoodisk SSD 128GB               | 20       | 0.74%   |
| Samsung SSD 970 EVO Plus 500GB  | 19       | 0.7%    |
| Samsung SSD 860 EVO 250GB       | 19       | 0.7%    |
| Protectli 120GB mSATA           | 19       | 0.7%    |
| BIWIN SSD 128GB                 | 18       | 0.66%   |
| Kingston SA400S37120G 120GB     | 17       | 0.63%   |
| Samsung SSD 860 EVO 1TB         | 16       | 0.59%   |
| PNY CS900 120GB SSD             | 16       | 0.59%   |
| Samsung SSD 850 EVO 500GB       | 15       | 0.55%   |
| Kingston SV300S37A120G 120GB    | 15       | 0.55%   |
| WDC WD800JD-75MSA3 80GB         | 14       | 0.51%   |
| Samsung SSD 970 EVO Plus 1TB    | 14       | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB        | 13       | 0.48%   |
| Samsung SSD 870 EVO 500GB       | 13       | 0.48%   |
| Crucial CT250MX500SSD1 250GB    | 13       | 0.48%   |
| Protectli 64GB mSATA            | 12       | 0.44%   |
| Transcend TS128GMSA230S 128GB   | 11       | 0.4%    |
| Toshiba DT01ACA100 1TB          | 11       | 0.4%    |
| SPCC Solid State Disk 128GB     | 11       | 0.4%    |
| Protectli 240GB mSATA           | 11       | 0.4%    |
| Phison Sabrent 1TB              | 11       | 0.4%    |
| Hoodisk SSD 64GB                | 11       | 0.4%    |
| China SATA SSD 120GB            | 11       | 0.4%    |
| Team TM8FP6256G 256GB           | 10       | 0.37%   |
| Seagate ST2000DM008-2FR102 2TB  | 10       | 0.37%   |
| Samsung SSD 980 500GB           | 10       | 0.37%   |
| Kingston SKC600MS256G 256GB     | 10       | 0.37%   |
| Crucial CT240BX500SSD1 240GB    | 10       | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB  | 9        | 0.33%   |
| SanDisk SDSA6MM-016G-1006 16GB  | 9        | 0.33%   |
| Dogfish SSD 128GB               | 9        | 0.33%   |
| Crucial CT500MX500SSD1 500GB    | 9        | 0.33%   |
| WDC WDS500G2B0A-00SM50 500GB    | 8        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC                                | 234      | 891    | 37.44%  |
| Seagate                            | 227      | 600    | 36.32%  |
| Toshiba                            | 56       | 97     | 8.96%   |
| Hitachi                            | 39       | 98     | 6.24%   |
| HGST                               | 23       | 70     | 3.68%   |
| Samsung Electronics                | 9        | 11     | 1.44%   |
| Hewlett-Packard                    | 5        | 15     | 0.8%    |
| Maxtor                             | 4        | 7      | 0.64%   |
| Apple                              | 4        | 5      | 0.64%   |
| NVMe                               | 3        | 7      | 0.48%   |
| Lexar                              | 3        | 3      | 0.48%   |
| HPE                                | 2        | 7      | 0.32%   |
| Fujitsu                            | 2        | 3      | 0.32%   |
| Adaptec                            | 2        | 2      | 0.32%   |
| WD MediaMax                        | 1        | 3      | 0.16%   |
| QUANTUM                            | 1        | 2      | 0.16%   |
| Product:              USB DISK 3.0 | 1        | 1      | 0.16%   |
| Memorex                            | 1        | 1      | 0.16%   |
| MaxDigital                         | 1        | 1      | 0.16%   |
| MARVELL                            | 1        | 1      | 0.16%   |
| LSI                                | 1        | 4      | 0.16%   |
| IBM-ESXS                           | 1        | 1      | 0.16%   |
| IBM-207x                           | 1        | 1      | 0.16%   |
| HPT                                | 1        | 8      | 0.16%   |
| ExcelStor Technology               | 1        | 4      | 0.16%   |
| ASMT                               | 1        | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 267      | 612    | 18.84%  |
| Kingston            | 171      | 250    | 12.07%  |
| Crucial             | 93       | 144    | 6.56%   |
| SanDisk             | 89       | 119    | 6.28%   |
| Transcend           | 70       | 134    | 4.94%   |
| Hoodisk             | 67       | 96     | 4.73%   |
| Protectli           | 66       | 108    | 4.66%   |
| Intel               | 66       | 162    | 4.66%   |
| China               | 58       | 76     | 4.09%   |
| PNY                 | 41       | 64     | 2.89%   |
| A-DATA Technology   | 40       | 61     | 2.82%   |
| WDC                 | 33       | 65     | 2.33%   |
| SPCC                | 32       | 71     | 2.26%   |
| Dogfish             | 29       | 52     | 2.05%   |
| SK hynix            | 24       | 30     | 1.69%   |
| BIWIN               | 24       | 41     | 1.69%   |
| Phison              | 19       | 26     | 1.34%   |
| OCZ                 | 16       | 24     | 1.13%   |
| Micron Technology   | 13       | 18     | 0.92%   |
| FORESEE             | 13       | 22     | 0.92%   |
| Toshiba             | 11       | 16     | 0.78%   |
| Apacer              | 11       | 14     | 0.78%   |
| Team                | 8        | 27     | 0.56%   |
| Mushkin             | 8        | 13     | 0.56%   |
| KingSpec            | 8        | 12     | 0.56%   |
| Innodisk            | 7        | 9      | 0.49%   |
| Hewlett-Packard     | 7        | 12     | 0.49%   |
| Zheino              | 6        | 11     | 0.42%   |
| Seagate             | 6        | 12     | 0.42%   |
| Patriot             | 6        | 7      | 0.42%   |
| Lexar               | 6        | 7      | 0.42%   |
| CWDISK              | 6        | 7      | 0.42%   |
| Corsair             | 6        | 11     | 0.42%   |
| ShiJi               | 5        | 6      | 0.35%   |
| NVMe                | 5        | 7      | 0.35%   |
| LITEONIT            | 5        | 8      | 0.35%   |
| LITEON              | 5        | 8      | 0.35%   |
| Intenso             | 5        | 11     | 0.35%   |
| Vaseky              | 4        | 4      | 0.28%   |
| Plextor             | 4        | 6      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1275     | 2479   | 57.9%   |
| HDD  | 501      | 1844   | 22.75%  |
| NVMe | 426      | 760    | 19.35%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1596     | 4323   | 78.93%  |
| NVMe | 426      | 760    | 21.07%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1352     | 2547   | 72.3%   |
| 0.51-1.0   | 260      | 580    | 13.9%   |
| 1.01-2.0   | 110      | 327    | 5.88%   |
| 4.01-10.0  | 53       | 439    | 2.83%   |
| 3.01-4.0   | 48       | 201    | 2.57%   |
| 2.01-3.0   | 31       | 116    | 1.66%   |
| 10.01-20.0 | 16       | 113    | 0.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 867      | 40.78%  |
| 251-500        | 392      | 18.44%  |
| 51-100         | 210      | 9.88%   |
| 21-50          | 207      | 9.74%   |
| 501-1000       | 197      | 9.27%   |
| 1-20           | 172      | 8.09%   |
| 1001-2000      | 47       | 2.21%   |
| More than 3000 | 23       | 1.08%   |
| Unknown        | 6        | 0.28%   |
| 2001-3000      | 5        | 0.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1916     | 90.72%  |
| 21-50          | 108      | 5.11%   |
| 51-100         | 37       | 1.75%   |
| 101-250        | 18       | 0.85%   |
| 251-500        | 10       | 0.47%   |
| More than 3000 | 7        | 0.33%   |
| Unknown        | 6        | 0.28%   |
| 501-1000       | 4        | 0.19%   |
| 1001-2000      | 3        | 0.14%   |
| 2001-3000      | 2        | 0.09%   |
| 0              | 1        | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 8        | 12     | 2.87%   |
| Crucial CT275MX300SSD1 275GB          | 5        | 8      | 1.79%   |
| Seagate ST3500418AS 500GB             | 4        | 11     | 1.43%   |
| Kingston SV300S37A120G 120GB          | 4        | 5      | 1.43%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 3        | 4      | 1.08%   |
| Seagate ST2000DM008-2FR102 2TB        | 3        | 3      | 1.08%   |
| Seagate ST1000DM003-9YN162 1TB        | 3        | 7      | 1.08%   |
| Kingston SV300S37A60G 64GB            | 3        | 3      | 1.08%   |
| WDC WD5000AAKX-001CA0 500GB           | 2        | 4      | 0.72%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2        | 9      | 0.72%   |
| WDC WD20EARS-00MVWB0 2TB              | 2        | 2      | 0.72%   |
| WDC WD2001FASS-00W2B0 2TB             | 2        | 3      | 0.72%   |
| WDC WD1600AAJS-75M0A0 160GB           | 2        | 2      | 0.72%   |
| Toshiba DT01ACA050 500GB              | 2        | 2      | 0.72%   |
| SPCC Solid State Disk 512GB           | 2        | 3      | 0.72%   |
| SK hynix SC210 mSATA 256GB            | 2        | 3      | 0.72%   |
| Seagate ST500LT012-1DG142 500GB       | 2        | 3      | 0.72%   |
| Seagate ST5000DM000-1FK178 5TB        | 2        | 3      | 0.72%   |
| Seagate ST3500413AS 500GB             | 2        | 10     | 0.72%   |
| Seagate ST31000528AS 1TB              | 2        | 2      | 0.72%   |
| Seagate ST2000DL001-9VT156 2TB        | 2        | 2      | 0.72%   |
| Samsung Electronics SSD 950 PRO 256GB | 2        | 2      | 0.72%   |
| Samsung Electronics SSD 850 EVO 500GB | 2        | 2      | 0.72%   |
| MyDigitalSSD SB2 256GB                | 2        | 4      | 0.72%   |
| Kingston SUV400S37120G 120GB          | 2        | 3      | 0.72%   |
| Kingston SNS4151S316G 16GB            | 2        | 3      | 0.72%   |
| Kingston SMS200S360G 64GB             | 2        | 2      | 0.72%   |
| Kingston SMS200S3120G 120GB           | 2        | 2      | 0.72%   |
| Intel SSDSC2BF180A4L 180GB            | 2        | 2      | 0.72%   |
| Intel SSDSA2M120G2GC 120GB            | 2        | 2      | 0.72%   |
| Hitachi HUA722020ALA330 2TB           | 2        | 5      | 0.72%   |
| Hitachi HTS725032A9A364 320GB         | 2        | 2      | 0.72%   |
| HGST HTS725050A7E630 500GB            | 2        | 2      | 0.72%   |
| Crucial CT512M550SSD1 512GB           | 2        | 5      | 0.72%   |
| Crucial CT240M500SSD1 240GB           | 2        | 3      | 0.72%   |
| Crucial CT1050MX300SSD4 1TB           | 2        | 2      | 0.72%   |
| Apacer 32GB SATA Flash Drive          | 2        | 2      | 0.72%   |
| Apacer 16GB SATA Flash Drive          | 2        | 3      | 0.72%   |
| WDC WDS500G2B0A-00SM50 500GB          | 1        | 1      | 0.36%   |
| WDC WD80EDAZ-11TA3A0 8TB              | 1        | 4      | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| Seagate              | 59       | 105    | 22.01%  |
| WDC                  | 49       | 85     | 18.28%  |
| Kingston             | 23       | 30     | 8.58%   |
| Samsung Electronics  | 19       | 27     | 7.09%   |
| Crucial              | 16       | 23     | 5.97%   |
| Intel                | 15       | 17     | 5.6%    |
| Hitachi              | 13       | 19     | 4.85%   |
| Toshiba              | 11       | 11     | 4.1%    |
| SanDisk              | 9        | 11     | 3.36%   |
| SK hynix             | 7        | 11     | 2.61%   |
| HGST                 | 6        | 6      | 2.24%   |
| Apacer               | 4        | 5      | 1.49%   |
| SPCC                 | 3        | 6      | 1.12%   |
| OCZ                  | 3        | 3      | 1.12%   |
| Maxtor               | 3        | 6      | 1.12%   |
| LITEON               | 3        | 4      | 1.12%   |
| PNY                  | 2        | 2      | 0.75%   |
| MyDigitalSSD         | 2        | 4      | 0.75%   |
| A-DATA Technology    | 2        | 2      | 0.75%   |
| WD MediaMax          | 1        | 3      | 0.37%   |
| VisionTek            | 1        | 1      | 0.37%   |
| Transcend            | 1        | 4      | 0.37%   |
| Plextor              | 1        | 1      | 0.37%   |
| Phison               | 1        | 1      | 0.37%   |
| Patriot              | 1        | 1      | 0.37%   |
| Micron Technology    | 1        | 1      | 0.37%   |
| LITEONIT             | 1        | 3      | 0.37%   |
| KingDian             | 1        | 1      | 0.37%   |
| KeepData             | 1        | 1      | 0.37%   |
| INDMEM               | 1        | 1      | 0.37%   |
| HPE                  | 1        | 3      | 0.37%   |
| Hewlett-Packard      | 1        | 4      | 0.37%   |
| Fujitsu              | 1        | 1      | 0.37%   |
| ExcelStor Technology | 1        | 2      | 0.37%   |
| EDGE                 | 1        | 1      | 0.37%   |
| Dogfish              | 1        | 5      | 0.37%   |
| Corsair              | 1        | 1      | 0.37%   |
| BIWIN                | 1        | 1      | 0.37%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| Seagate              | 59       | 105    | 40.41%  |
| WDC                  | 48       | 84     | 32.88%  |
| Hitachi              | 13       | 19     | 8.9%    |
| Toshiba              | 9        | 9      | 6.16%   |
| HGST                 | 6        | 6      | 4.11%   |
| Samsung Electronics  | 3        | 3      | 2.05%   |
| Maxtor               | 3        | 6      | 2.05%   |
| WD MediaMax          | 1        | 3      | 0.68%   |
| HPE                  | 1        | 3      | 0.68%   |
| Hewlett-Packard      | 1        | 4      | 0.68%   |
| Fujitsu              | 1        | 1      | 0.68%   |
| ExcelStor Technology | 1        | 2      | 0.68%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 140      | 245    | 53.64%  |
| SSD  | 116      | 163    | 44.44%  |
| NVMe | 5        | 5      | 1.92%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WD3200L 320GB                            | 1        | 1      | 11.11%  |
| SK hynix SC308 SATA 256GB                    | 1        | 1      | 11.11%  |
| Seagate ST3500418AS 500GB                    | 1        | 2      | 11.11%  |
| Samsung Electronics SSD 970 EVO Plus 500GB   | 1        | 1      | 11.11%  |
| Samsung Electronics PM981 NVMe 256GB         | 1        | 1      | 11.11%  |
| Samsung Electronics MZVLB256HBHQ-000H1 256GB | 1        | 1      | 11.11%  |
| Samsung Electronics HD204UI 2TB              | 1        | 2      | 11.11%  |
| Kingston SA2000M8500G 500GB                  | 1        | 2      | 11.11%  |
| Intel SSDSC2KB019T8 1.9TB                    | 1        | 2      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 5      | 44.44%  |
| WDC                 | 1        | 1      | 11.11%  |
| SK hynix            | 1        | 1      | 11.11%  |
| Seagate             | 1        | 2      | 11.11%  |
| Kingston            | 1        | 2      | 11.11%  |
| Intel               | 1        | 2      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1721     | 4563   | 84.61%  |
| Malfunc  | 256      | 413    | 12.59%  |
| Detected | 48       | 94     | 2.36%   |
| Failed   | 9        | 13     | 0.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel                                   | 1609     | 60.13%  |
| AMD                                     | 362      | 13.53%  |
| Samsung Electronics                     | 162      | 6.05%   |
| SanDisk                                 | 76       | 2.84%   |
| ASMedia Technology                      | 60       | 2.24%   |
| Phison Electronics                      | 54       | 2.02%   |
| Silicon Motion                          | 49       | 1.83%   |
| Broadcom / LSI                          | 44       | 1.64%   |
| Marvell Technology Group                | 33       | 1.23%   |
| Micron/Crucial Technology               | 28       | 1.05%   |
| SK hynix                                | 27       | 1.01%   |
| MAXIO Technology (Hangzhou)             | 23       | 0.86%   |
| Kingston Technology Company             | 21       | 0.78%   |
| JMicron Technology                      | 16       | 0.6%    |
| Chelsio Communications                  | 15       | 0.56%   |
| Realtek Semiconductor                   | 12       | 0.45%   |
| Nvidia                                  | 9        | 0.34%   |
| KIOXIA                                  | 9        | 0.34%   |
| Adaptec                                 | 7        | 0.26%   |
| Toshiba                                 | 6        | 0.22%   |
| ADATA Technology                        | 6        | 0.22%   |
| Shenzhen Longsys Electronics            | 5        | 0.19%   |
| Seagate Technology                      | 5        | 0.19%   |
| Micron Technology                       | 5        | 0.19%   |
| VIA Technologies                        | 3        | 0.11%   |
| Silicon Image                           | 3        | 0.11%   |
| Lite-On Technology                      | 3        | 0.11%   |
| Hosin Global Electronics                | 3        | 0.11%   |
| Transcend                               | 2        | 0.07%   |
| Solid State Storage Technology          | 2        | 0.07%   |
| Silicon Integrated Systems [SiS]        | 2        | 0.07%   |
| Shenzhen Unionmemory Information System | 2        | 0.07%   |
| HighPoint Technologies                  | 2        | 0.07%   |
| Hewlett-Packard                         | 2        | 0.07%   |
| Biwin Storage Technology                | 2        | 0.07%   |
| Union Memory (Shenzhen)                 | 1        | 0.04%   |
| Solidigm                                | 1        | 0.04%   |
| O2 Micro                                | 1        | 0.04%   |
| Innodisk                                | 1        | 0.04%   |
| Broadcom                                | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 236      | 7.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 163      | 5.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 121      | 4%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 120      | 3.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 103      | 3.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 102      | 3.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 100      | 3.31%   |
| Intel SATA Controller [RAID mode]                                                       | 85       | 2.81%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 83       | 2.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 81       | 2.68%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 67       | 2.22%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 65       | 2.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 63       | 2.08%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 51       | 1.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 50       | 1.65%   |
| AMD 400 Series Chipset SATA Controller                                                  | 49       | 1.62%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 48       | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 39       | 1.29%   |
| AMD 500 Series Chipset SATA Controller                                                  | 39       | 1.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 36       | 1.19%   |
| Intel unknown                                                                           | 31       | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 28       | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 26       | 0.86%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 26       | 0.86%   |
| Phison E12 NVMe Controller                                                              | 26       | 0.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 26       | 0.86%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 23       | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 22       | 0.73%   |
| Intel Elkhart Lake SATA AHCI                                                            | 22       | 0.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 21       | 0.69%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 20       | 0.66%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 20       | 0.66%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 20       | 0.66%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 20       | 0.66%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 19       | 0.63%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 19       | 0.63%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 18       | 0.6%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 18       | 0.6%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 18       | 0.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 18       | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1750     | 66.14%  |
| NVMe | 492      | 18.59%  |
| IDE  | 209      | 7.9%    |
| RAID | 126      | 4.76%   |
| SAS  | 43       | 1.63%   |
| SCSI | 26       | 0.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 1648     | 80.78%  |
| AMD      | 378      | 18.53%  |
| ARM      | 6        | 0.29%   |
| Unknown  | 3        | 0.15%   |
| IBM      | 2        | 0.1%    |
| NXP      | 1        | 0.05%   |
| Motorola | 1        | 0.05%   |
| i        | 1        | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Celeron J4125 CPU @ 2.00GHz        | 83       | 4%      |
| Intel Celeron CPU J3160 @ 1.60GHz        | 77       | 3.71%   |
| Intel Celeron N5105 @ 2.00GHz            | 75       | 3.61%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 44       | 2.12%   |
| AMD GX-412TC SOC                         | 38       | 1.83%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 34       | 1.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 32       | 1.54%   |
| Intel N100                               | 31       | 1.49%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 29       | 1.4%    |
| Intel Celeron CPU J1900 @ 1.99GHz        | 28       | 1.35%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 25       | 1.2%    |
| Intel Core i5-4590 CPU @ 3.30GHz         | 25       | 1.2%    |
| AMD GX-420CA SOC with Radeon HD Graphics | 25       | 1.2%    |
| Intel Atom CPU D525 @ 1.80GHz            | 20       | 0.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 19       | 0.92%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 18       | 0.87%   |
| Intel Core i7-6700 CPU @ 3.40GHz         | 17       | 0.82%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 17       | 0.82%   |
| Intel Pentium Silver N6005 @ 2.00GHz     | 16       | 0.77%   |
| Intel Core i7-4770 CPU @ 3.40GHz         | 16       | 0.77%   |
| Intel Core i5-7500 CPU @ 3.40GHz         | 16       | 0.77%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 16       | 0.77%   |
| Intel Pentium CPU J3710 @ 1.60GHz        | 15       | 0.72%   |
| Intel Celeron J6412 @ 2.00GHz            | 15       | 0.72%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 15       | 0.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 14       | 0.67%   |
| Intel Core i7-4790 CPU @ 3.60GHz         | 14       | 0.67%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 14       | 0.67%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 14       | 0.67%   |
| AMD Ryzen 7 5700G with Radeon Graphics   | 14       | 0.67%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz        | 13       | 0.63%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 13       | 0.63%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 12       | 0.58%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 12       | 0.58%   |
| AMD Ryzen 7 2700 Eight-Core Processor    | 12       | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 11       | 0.53%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 11       | 0.53%   |
| Intel Core i3-10100 CPU @ 3.60GHz        | 11       | 0.53%   |
| AMD Ryzen 7 5800X 8-Core Processor       | 11       | 0.53%   |
| AMD Ryzen 5 5600G with Radeon Graphics   | 11       | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 438      | 21.24%  |
| Intel Celeron           | 397      | 19.25%  |
| Intel Core i7           | 218      | 10.57%  |
| Intel Xeon              | 161      | 7.81%   |
| Intel Core i3           | 150      | 7.27%   |
| Other                   | 99       | 4.8%    |
| Intel Atom              | 85       | 4.12%   |
| AMD Ryzen 7             | 76       | 3.69%   |
| AMD GX                  | 75       | 3.64%   |
| AMD Ryzen 5             | 57       | 2.76%   |
| Intel Pentium           | 44       | 2.13%   |
| AMD Ryzen 9             | 29       | 1.41%   |
| AMD FX                  | 23       | 1.12%   |
| Intel Core 2 Duo        | 18       | 0.87%   |
| Intel Pentium Silver    | 17       | 0.82%   |
| AMD Ryzen 3             | 15       | 0.73%   |
| Intel Core 2 Quad       | 13       | 0.63%   |
| AMD A10                 | 13       | 0.63%   |
| AMD Phenom II X4        | 10       | 0.48%   |
| AMD Athlon              | 10       | 0.48%   |
| Intel Core i9           | 9        | 0.44%   |
| Intel Pentium Dual-Core | 7        | 0.34%   |
| AMD Ryzen 5 PRO         | 7        | 0.34%   |
| AMD A8                  | 7        | 0.34%   |
| ARM Cortex              | 6        | 0.29%   |
| AMD Ryzen Threadripper  | 6        | 0.29%   |
| AMD Opteron             | 6        | 0.29%   |
| AMD G                   | 6        | 0.29%   |
| AMD Phenom II X6        | 5        | 0.24%   |
| AMD A6                  | 5        | 0.24%   |
| AMD A4                  | 5        | 0.24%   |
| Intel Pentium 4         | 4        | 0.19%   |
| Intel Core 2            | 4        | 0.19%   |
| Intel Pentium Gold      | 3        | 0.15%   |
| Intel 686-class         | 3        | 0.15%   |
| AMD E2                  | 3        | 0.15%   |
| AMD Athlon 64 X2        | 3        | 0.15%   |
| Intel Pentium D         | 2        | 0.1%    |
| Intel Genuine           | 2        | 0.1%    |
| AMD Sempron             | 2        | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1188     | 57.53%  |
| 2       | 408      | 19.76%  |
| 8       | 113      | 5.47%   |
| 6       | 102      | 4.94%   |
| 16      | 80       | 3.87%   |
| 12      | 66       | 3.2%    |
| Unknown | 49       | 2.37%   |
| 32      | 16       | 0.77%   |
| 24      | 15       | 0.73%   |
| 1       | 10       | 0.48%   |
| 10      | 7        | 0.34%   |
| 14      | 3        | 0.15%   |
| 48      | 2        | 0.1%    |
| 3       | 2        | 0.1%    |
| 64      | 1        | 0.05%   |
| 36      | 1        | 0.05%   |
| 28      | 1        | 0.05%   |
| 20      | 1        | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1992     | 97.69%  |
| 2       | 26       | 1.28%   |
| Unknown | 19       | 0.93%   |
| 8       | 1        | 0.05%   |
| 4       | 1        | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1334     | 65.01%  |
| 2       | 666      | 32.46%  |
| Unknown | 52       | 2.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 256      | 12.39%  |
| Haswell       | 236      | 11.42%  |
| Unknown       | 229      | 11.08%  |
| Silvermont    | 184      | 8.91%   |
| Skylake       | 148      | 7.16%   |
| IvyBridge     | 140      | 6.78%   |
| SandyBridge   | 104      | 5.03%   |
| Goldmont plus | 102      | 4.94%   |
| Zen 3         | 60       | 2.9%    |
| Zen 2         | 53       | 2.57%   |
| Broadwell     | 53       | 2.57%   |
| Zen+          | 49       | 2.37%   |
| CometLake     | 45       | 2.18%   |
| Puma          | 44       | 2.13%   |
| Jaguar        | 42       | 2.03%   |
| Bonnell       | 39       | 1.89%   |
| Piledriver    | 36       | 1.74%   |
| Penryn        | 34       | 1.65%   |
| Goldmont      | 31       | 1.5%    |
| Zen           | 29       | 1.4%    |
| Nehalem       | 29       | 1.4%    |
| K10           | 22       | 1.06%   |
| Core          | 21       | 1.02%   |
| Westmere      | 18       | 0.87%   |
| TigerLake     | 12       | 0.58%   |
| Bobcat        | 11       | 0.53%   |
| Steamroller   | 10       | 0.48%   |
| NetBurst      | 8        | 0.39%   |
| Excavator     | 8        | 0.39%   |
| K8 Hammer     | 7        | 0.34%   |
| K10 Llano     | 2        | 0.1%    |
| Bulldozer     | 2        | 0.1%    |
| P6            | 1        | 0.05%   |
| Geode         | 1        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1345     | 67.35%  |
| AMD                                          | 311      | 15.57%  |
| Nvidia                                       | 208      | 10.42%  |
| ASPEED Technology                            | 77       | 3.86%   |
| Matrox Electronics Systems                   | 50       | 2.5%    |
| XGI Technology (eXtreme Graphics Innovation) | 4        | 0.2%    |
| Silicon Integrated Systems [SiS]             | 2        | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 135      | 6.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 120      | 5.92%   |
| Intel HD Graphics 530                                                                    | 106      | 5.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 102      | 5.03%   |
| Intel JasperLake [UHD Graphics]                                                          | 97       | 4.79%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 77       | 3.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 71       | 3.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 68       | 3.35%   |
| Intel HD Graphics 620                                                                    | 63       | 3.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 56       | 2.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 50       | 2.47%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 47       | 2.32%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 45       | 2.22%   |
| Intel HD Graphics 630                                                                    | 39       | 1.92%   |
| Intel UHD Graphics 620                                                                   | 33       | 1.63%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 31       | 1.53%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 30       | 1.48%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 27       | 1.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 26       | 1.28%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 26       | 1.28%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 25       | 1.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 25       | 1.23%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 25       | 1.23%   |
| Intel HD Graphics 610                                                                    | 23       | 1.13%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 22       | 1.09%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 20       | 0.99%   |
| Intel HD Graphics 5500                                                                   | 19       | 0.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18       | 0.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17       | 0.84%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 15       | 0.74%   |
| Intel HD Graphics 500                                                                    | 14       | 0.69%   |
| Intel HD Graphics 6000                                                                   | 13       | 0.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10       | 0.49%   |
| AMD RV730 XT [Radeon HD 4670]                                                            | 9        | 0.44%   |
| AMD RS780L [Radeon 3000]                                                                 | 9        | 0.44%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9        | 0.44%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 8        | 0.39%   |
| Intel Comet Lake UHD Graphics                                                            | 8        | 0.39%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 8        | 0.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8        | 0.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 1291     | 62.61%  |
| 1 x AMD         | 290      | 14.06%  |
| 1 x Nvidia      | 183      | 8.87%   |
| Other           | 96       | 4.66%   |
| 1 x ASPEED      | 74       | 3.59%   |
| 1 x Matrox      | 48       | 2.33%   |
| 2 x Intel       | 31       | 1.5%    |
| Intel + Nvidia  | 16       | 0.78%   |
| 2 x AMD         | 8        | 0.39%   |
| Intel + AMD     | 5        | 0.24%   |
| AMD + Nvidia    | 5        | 0.24%   |
| 1 x XGI         | 4        | 0.19%   |
| 2 x Nvidia      | 3        | 0.15%   |
| 1 x SiS         | 2        | 0.1%    |
| Intel + ASPEED  | 2        | 0.1%    |
| Nvidia + ASPEED | 1        | 0.05%   |
| Intel + 2 x AMD | 1        | 0.05%   |
| AMD + Matrox    | 1        | 0.05%   |
| AMD + ASPEED    | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1827     | 89.08%  |
| Proprietary | 116      | 5.66%   |
| Unknown     | 108      | 5.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1870     | 90.95%  |
| 1.01-2.0   | 48       | 2.33%   |
| 3.01-4.0   | 35       | 1.7%    |
| 7.01-8.0   | 32       | 1.56%   |
| 0.51-1.0   | 25       | 1.22%   |
| 0.01-0.5   | 17       | 0.83%   |
| 5.01-6.0   | 14       | 0.68%   |
| 8.01-16.0  | 12       | 0.58%   |
| 2.01-3.0   | 2        | 0.1%    |
| 4.01-5.0   | 1        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 58       | 19.93%  |
| Goldstar             | 34       | 11.68%  |
| Acer                 | 34       | 11.68%  |
| Samsung Electronics  | 33       | 11.34%  |
| Hewlett-Packard      | 20       | 6.87%   |
| Ancor Communications | 17       | 5.84%   |
| ASUSTek Computer     | 10       | 3.44%   |
| AOC                  | 10       | 3.44%   |
| Vizio                | 8        | 2.75%   |
| Lenovo               | 8        | 2.75%   |
| ViewSonic            | 6        | 2.06%   |
| LG Electronics       | 6        | 2.06%   |
| BenQ                 | 5        | 1.72%   |
| Sceptre Tech         | 4        | 1.37%   |
| Apple                | 4        | 1.37%   |
| Sony                 | 3        | 1.03%   |
| Philips              | 3        | 1.03%   |
| MSI                  | 3        | 1.03%   |
| Insignia             | 3        | 1.03%   |
| Westinghouse         | 2        | 0.69%   |
| Wacom                | 1        | 0.34%   |
| unknown              | 1        | 0.34%   |
| SHI                  | 1        | 0.34%   |
| SGT                  | 1        | 0.34%   |
| RS                   | 1        | 0.34%   |
| Pioneer Electronic   | 1        | 0.34%   |
| NEC Computers        | 1        | 0.34%   |
| Lenovo Group Limited | 1        | 0.34%   |
| ITE                  | 1        | 0.34%   |
| Impression           | 1        | 0.34%   |
| Hitachi              | 1        | 0.34%   |
| HannStar             | 1        | 0.34%   |
| Gigabyte Technology  | 1        | 0.34%   |
| Gateway              | 1        | 0.34%   |
| Envision             | 1        | 0.34%   |
| DENON                | 1        | 0.34%   |
| Chimei Innolux       | 1        | 0.34%   |
| AU Optronics         | 1        | 0.34%   |
| ASRock               | 1        | 0.34%   |
| Unknown              | 1        | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch               | 5        | 1.59%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 300x230mm 14.9-inch | 3        | 0.96%   |
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                     | 3        | 0.96%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                   | 3        | 0.96%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                   | 3        | 0.96%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch        | 3        | 0.96%   |
| Sony TV SNY9C01 1360x768                                            | 2        | 0.64%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch   | 2        | 0.64%   |
| Samsung Electronics S27C750 SAM0A60 1920x1080 600x340mm 27.2-inch   | 2        | 0.64%   |
| Hewlett-Packard All-in-One HWP4218 1600x900 440x250mm 19.9-inch     | 2        | 0.64%   |
| Goldstar W2246 GSM5784 1920x1080 480x270mm 21.7-inch                | 2        | 0.64%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch          | 2        | 0.64%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch           | 2        | 0.64%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                   | 2        | 0.64%   |
| Dell S2716DG DELA0D1 2560x1440 600x340mm 27.2-inch                  | 2        | 0.64%   |
| Dell S2418HN/NX DEL4123 1920x1080 530x300mm 24.0-inch               | 2        | 0.64%   |
| ASUSTek Computer VP247 AUS24CA 1920x1080 520x290mm 23.4-inch        | 2        | 0.64%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                  | 2        | 0.64%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch    | 2        | 0.64%   |
| Acer X183H ACR006A 1366x768 410x230mm 18.5-inch                     | 2        | 0.64%   |
| Acer V246HL ACR032E 1920x1080 530x300mm 24.0-inch                   | 2        | 0.64%   |
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                   | 2        | 0.64%   |
| Westinghouse LCM-19w4 WDE1904 1440x900 410x260mm 19.1-inch          | 1        | 0.32%   |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch        | 1        | 0.32%   |
| Wacom One 13 WAC1070 1920x1080 290x170mm 13.2-inch                  | 1        | 0.32%   |
| Vizio SV370XVT VIZ0057 1920x1080 820x460mm 37.0-inch                | 1        | 0.32%   |
| Vizio LCD Monitor VIZ0022 1920x540 480x270mm 21.7-inch              | 1        | 0.32%   |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                   | 1        | 0.32%   |
| Vizio E320i-B2 VIZ1002 1360x768 700x400mm 31.7-inch                 | 1        | 0.32%   |
| Vizio E320i-A0 VIZ0091 1366x768 700x390mm 31.5-inch                 | 1        | 0.32%   |
| Vizio D43-D2 VIZ1004 1920x1080 930x520mm 41.9-inch                  | 1        | 0.32%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                 | 1        | 0.32%   |
| Vizio D32f-F1 VIZ1027 1920x1080 700x390mm 31.5-inch                 | 1        | 0.32%   |
| ViewSonic VX910 VSC3C19 1280x1024 380x300mm 19.1-inch               | 1        | 0.32%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 480x270mm 21.7-inch       | 1        | 0.32%   |
| ViewSonic N2635w-3M VSC1B24 1360x768 580x330mm 26.3-inch            | 1        | 0.32%   |
| ViewSonic LCD Monitor VSCE032 2560x1440 530x300mm 24.0-inch         | 1        | 0.32%   |
| ViewSonic LCD Monitor VSCDC2E 1920x1080 480x270mm 21.7-inch         | 1        | 0.32%   |
| ViewSonic LCD Monitor VA1938 Series                                 | 1        | 0.32%   |
| unknown LCD Monitor Dell SE2717H/HX 1920x1080                       | 1        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 108      | 37.63%  |
| 2560x1440 (QHD)    | 27       | 9.41%   |
| 3840x2160 (4K)     | 25       | 8.71%   |
| 1920x1200 (WUXGA)  | 18       | 6.27%   |
| 1280x1024 (SXGA)   | 15       | 5.23%   |
| 1680x1050 (WSXGA+) | 13       | 4.53%   |
| 2560x1080          | 10       | 3.48%   |
| 1600x900 (HD+)     | 10       | 3.48%   |
| 3440x1440          | 9        | 3.14%   |
| 1366x768 (WXGA)    | 9        | 3.14%   |
| 1440x900 (WXGA+)   | 8        | 2.79%   |
| Unknown            | 7        | 2.44%   |
| 1360x768           | 6        | 2.09%   |
| 1024x768 (XGA)     | 5        | 1.74%   |
| 3840x1080          | 3        | 1.05%   |
| 2560x1600          | 3        | 1.05%   |
| 1600x1200          | 3        | 1.05%   |
| 7860x2400          | 1        | 0.35%   |
| 5760x1080          | 1        | 0.35%   |
| 4640x1080          | 1        | 0.35%   |
| 3840x1600          | 1        | 0.35%   |
| 3520x1080          | 1        | 0.35%   |
| 2806x900           | 1        | 0.35%   |
| 1920x540           | 1        | 0.35%   |
| 1024x600           | 1        | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 53       | 18.21%  |
| 27      | 41       | 14.09%  |
| Unknown | 33       | 11.34%  |
| 31      | 25       | 8.59%   |
| 21      | 23       | 7.9%    |
| 19      | 23       | 7.9%    |
| 23      | 20       | 6.87%   |
| 34      | 13       | 4.47%   |
| 22      | 9        | 3.09%   |
| 17      | 8        | 2.75%   |
| 18      | 6        | 2.06%   |
| 20      | 5        | 1.72%   |
| 29      | 4        | 1.37%   |
| 14      | 4        | 1.37%   |
| 15      | 3        | 1.03%   |
| 13      | 3        | 1.03%   |
| 64      | 2        | 0.69%   |
| 42      | 2        | 0.69%   |
| 28      | 2        | 0.69%   |
| 52      | 1        | 0.34%   |
| 49      | 1        | 0.34%   |
| 43      | 1        | 0.34%   |
| 41      | 1        | 0.34%   |
| 39      | 1        | 0.34%   |
| 37      | 1        | 0.34%   |
| 35      | 1        | 0.34%   |
| 32      | 1        | 0.34%   |
| 26      | 1        | 0.34%   |
| 25      | 1        | 0.34%   |
| 16      | 1        | 0.34%   |
| 9       | 1        | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 106      | 37.72%  |
| 401-500     | 58       | 20.64%  |
| 601-700     | 34       | 12.1%   |
| Unknown     | 33       | 11.74%  |
| 701-800     | 14       | 4.98%   |
| 301-350     | 12       | 4.27%   |
| 201-300     | 7        | 2.49%   |
| 351-400     | 5        | 1.78%   |
| 1001-1500   | 4        | 1.42%   |
| 901-1000    | 4        | 1.42%   |
| 801-900     | 3        | 1.07%   |
| 101-200     | 1        | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 165      | 60.89%  |
| 16/10   | 34       | 12.55%  |
| Unknown | 30       | 11.07%  |
| 21/9    | 18       | 6.64%   |
| 5/4     | 12       | 4.43%   |
| 4/3     | 8        | 2.95%   |
| 6/5     | 2        | 0.74%   |
| 32/9    | 1        | 0.37%   |
| 3/2     | 1        | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 83       | 28.92%  |
| 301-350        | 43       | 14.98%  |
| 351-500        | 42       | 14.63%  |
| Unknown        | 33       | 11.5%   |
| 151-200        | 28       | 9.76%   |
| 251-300        | 22       | 7.67%   |
| 141-150        | 14       | 4.88%   |
| 501-1000       | 7        | 2.44%   |
| 101-110        | 4        | 1.39%   |
| More than 1000 | 3        | 1.05%   |
| 81-90          | 2        | 0.7%    |
| 121-130        | 2        | 0.7%    |
| 111-120        | 2        | 0.7%    |
| 71-80          | 1        | 0.35%   |
| 1-40           | 1        | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 165      | 60.66%  |
| 101-120 | 47       | 17.28%  |
| Unknown | 33       | 12.13%  |
| 121-160 | 12       | 4.41%   |
| 161-240 | 11       | 4.04%   |
| 1-50    | 4        | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1768     | 86.12%  |
| 1     | 243      | 11.84%  |
| 2     | 35       | 1.7%    |
| 3     | 6        | 0.29%   |
| 4     | 1        | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 1741     | 62.47%  |
| Realtek Semiconductor           | 616      | 22.1%   |
| Qualcomm Atheros                | 105      | 3.77%   |
| Broadcom                        | 97       | 3.48%   |
| Mellanox Technologies           | 40       | 1.44%   |
| Ralink Technology               | 24       | 0.86%   |
| Chelsio Communications          | 17       | 0.61%   |
| IMC Networks                    | 16       | 0.57%   |
| U-Blox                          | 15       | 0.54%   |
| Ralink                          | 11       | 0.39%   |
| Aquantia                        | 10       | 0.36%   |
| Solarflare Communications       | 9        | 0.32%   |
| MediaTek                        | 8        | 0.29%   |
| Marvell Technology Group        | 7        | 0.25%   |
| D-Link System                   | 7        | 0.25%   |
| Seeed Technology                | 6        | 0.22%   |
| American Megatrends             | 5        | 0.18%   |
| TP-Link                         | 4        | 0.14%   |
| Sequans Communications          | 3        | 0.11%   |
| Novatel Wireless                | 3        | 0.11%   |
| Emulex                          | 3        | 0.11%   |
| Edimax Technology               | 3        | 0.11%   |
| VIA Technologies                | 2        | 0.07%   |
| Qualcomm Atheros Communications | 2        | 0.07%   |
| Linksys                         | 2        | 0.07%   |
| ICS Advent                      | 2        | 0.07%   |
| Belkin Components               | 2        | 0.07%   |
| Apple                           | 2        | 0.07%   |
| Accton Technology               | 2        | 0.07%   |
| 3Com                            | 2        | 0.07%   |
| ZyXEL Communications            | 1        | 0.04%   |
| Xiaomi                          | 1        | 0.04%   |
| Tehuti Networks                 | 1        | 0.04%   |
| Silicom                         | 1        | 0.04%   |
| Sierra Wireless                 | 1        | 0.04%   |
| Pulse-Eight                     | 1        | 0.04%   |
| Oracle/SUN                      | 1        | 0.04%   |
| OPPO Electronics                | 1        | 0.04%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.04%   |
| Nvidia                          | 1        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 505      | 14.23%  |
| Intel I211 Gigabit Network Connection                                         | 297      | 8.37%   |
| Intel I210 Gigabit Network Connection                                         | 175      | 4.93%   |
| Intel Ethernet Controller I225-V                                              | 167      | 4.71%   |
| Intel 82574L Gigabit Network Connection                                       | 135      | 3.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 132      | 3.72%   |
| Intel Ethernet Controller I226-V                                              | 126      | 3.55%   |
| Intel I350 Gigabit Network Connection                                         | 123      | 3.47%   |
| Intel Ethernet Connection I217-LM                                             | 106      | 2.99%   |
| Intel 82583V Gigabit Network Connection                                       | 88       | 2.48%   |
| Intel 82580 Gigabit Network Connection                                        | 81       | 2.28%   |
| Realtek RTL8125 2.5GbE Controller                                             | 80       | 2.25%   |
| Intel 82576 Gigabit Network Connection                                        | 67       | 1.89%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 67       | 1.89%   |
| Intel Ethernet Connection (2) I219-LM                                         | 60       | 1.69%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 53       | 1.49%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 52       | 1.47%   |
| Intel Wi-Fi 6 AX200                                                           | 51       | 1.44%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 51       | 1.44%   |
| Intel Ethernet Connection (2) I219-V                                          | 38       | 1.07%   |
| Intel Ethernet Controller X550                                                | 25       | 0.7%    |
| Mellanox MT27500 Family [ConnectX-3]                                          | 24       | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                                         | 24       | 0.68%   |
| Intel 82575EB Gigabit Network Connection                                      | 23       | 0.65%   |
| Intel 82579V Gigabit Network Connection                                       | 21       | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 20       | 0.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 18       | 0.51%   |
| Intel Ethernet Connection (7) I219-V                                          | 18       | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                                         | 18       | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 17       | 0.48%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 17       | 0.48%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 16       | 0.45%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 16       | 0.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 15       | 0.42%   |
| Intel Wireless 3165                                                           | 15       | 0.42%   |
| Intel Ethernet Controller I225-LM                                             | 15       | 0.42%   |
| Intel Ethernet Connection (2) I218-V                                          | 15       | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 14       | 0.39%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 14       | 0.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 13       | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 210      | 46.46%  |
| Qualcomm Atheros                | 86       | 19.03%  |
| Realtek Semiconductor           | 60       | 13.27%  |
| Ralink Technology               | 24       | 5.31%   |
| Broadcom                        | 20       | 4.42%   |
| IMC Networks                    | 16       | 3.54%   |
| Ralink                          | 11       | 2.43%   |
| MediaTek                        | 8        | 1.77%   |
| TP-Link                         | 4        | 0.88%   |
| Edimax Technology               | 3        | 0.66%   |
| Qualcomm Atheros Communications | 2        | 0.44%   |
| Belkin Components               | 2        | 0.44%   |
| ZyXEL Communications            | 1        | 0.22%   |
| Sierra Wireless                 | 1        | 0.22%   |
| Linksys                         | 1        | 0.22%   |
| D-Link System                   | 1        | 0.22%   |
| D-Link                          | 1        | 0.22%   |
| ASUSTek Computer                | 1        | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 51       | 11.16%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 20       | 4.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 18       | 3.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 17       | 3.72%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 16       | 3.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 15       | 3.28%   |
| Intel Wireless 3165                                             | 15       | 3.28%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 14       | 3.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 13       | 2.84%   |
| Intel Wireless-AC 9260                                          | 12       | 2.63%   |
| Intel Wireless 7260                                             | 11       | 2.41%   |
| Intel Wireless 7265                                             | 10       | 2.19%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 10       | 2.19%   |
| Intel CNVi: Wi-Fi                                               | 10       | 2.19%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 9        | 1.97%   |
| Ralink RT5370 Wireless Adapter                                  | 8        | 1.75%   |
| Intel Wireless 8260                                             | 8        | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 7        | 1.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 7        | 1.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 7        | 1.53%   |
| Ralink RT5572 Wireless Adapter                                  | 6        | 1.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 6        | 1.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 6        | 1.31%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 6        | 1.31%   |
| Intel Tiger Lake PCH CNVi WiFi                                  | 6        | 1.31%   |
| Intel Wireless 3160                                             | 5        | 1.09%   |
| Intel Centrino Wireless-N 2230                                  | 5        | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 4        | 0.88%   |
| Ralink MT7601U Wireless Adapter                                 | 4        | 0.88%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter          | 4        | 0.88%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 4        | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 4        | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 4        | 0.88%   |
| Intel Wireless 8265 / 8275                                      | 4        | 0.88%   |
| Intel Centrino Wireless-N 105                                   | 4        | 0.88%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter    | 4        | 0.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller          | 4        | 0.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 3        | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                 | 3        | 0.66%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 3        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 1684     | 68.79%  |
| Realtek Semiconductor         | 588      | 24.02%  |
| Broadcom                      | 79       | 3.23%   |
| Qualcomm Atheros              | 21       | 0.86%   |
| Chelsio Communications        | 15       | 0.61%   |
| Solarflare Communications     | 9        | 0.37%   |
| Aquantia                      | 9        | 0.37%   |
| Marvell Technology Group      | 7        | 0.29%   |
| D-Link System                 | 6        | 0.25%   |
| American Megatrends           | 5        | 0.2%    |
| Novatel Wireless              | 3        | 0.12%   |
| Emulex                        | 3        | 0.12%   |
| VIA Technologies              | 2        | 0.08%   |
| ICS Advent                    | 2        | 0.08%   |
| 3Com                          | 2        | 0.08%   |
| Xiaomi                        | 1        | 0.04%   |
| Tehuti Networks               | 1        | 0.04%   |
| Silicom                       | 1        | 0.04%   |
| Oracle/SUN                    | 1        | 0.04%   |
| OPPO Electronics              | 1        | 0.04%   |
| OnePlus Technology (Shenzhen) | 1        | 0.04%   |
| Nvidia                        | 1        | 0.04%   |
| National Semiconductor        | 1        | 0.04%   |
| Linksys                       | 1        | 0.04%   |
| Insyde Software               | 1        | 0.04%   |
| Apple                         | 1        | 0.04%   |
| ADMtek                        | 1        | 0.04%   |
| Accton Technology             | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 505      | 16.81%  |
| Intel I211 Gigabit Network Connection                                         | 297      | 9.89%   |
| Intel I210 Gigabit Network Connection                                         | 175      | 5.83%   |
| Intel Ethernet Controller I225-V                                              | 167      | 5.56%   |
| Intel 82574L Gigabit Network Connection                                       | 135      | 4.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 132      | 4.39%   |
| Intel Ethernet Controller I226-V                                              | 126      | 4.19%   |
| Intel I350 Gigabit Network Connection                                         | 123      | 4.09%   |
| Intel Ethernet Connection I217-LM                                             | 106      | 3.53%   |
| Intel 82583V Gigabit Network Connection                                       | 88       | 2.93%   |
| Intel 82580 Gigabit Network Connection                                        | 81       | 2.7%    |
| Realtek RTL8125 2.5GbE Controller                                             | 77       | 2.56%   |
| Intel 82576 Gigabit Network Connection                                        | 67       | 2.23%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 67       | 2.23%   |
| Intel Ethernet Connection (2) I219-LM                                         | 60       | 2%      |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 53       | 1.76%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 52       | 1.73%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 51       | 1.7%    |
| Intel Ethernet Connection (2) I219-V                                          | 38       | 1.26%   |
| Intel Ethernet Controller X550                                                | 25       | 0.83%   |
| Intel Ethernet Connection (7) I219-LM                                         | 24       | 0.8%    |
| Intel 82575EB Gigabit Network Connection                                      | 23       | 0.77%   |
| Intel 82579V Gigabit Network Connection                                       | 21       | 0.7%    |
| Intel Ethernet Connection (7) I219-V                                          | 18       | 0.6%    |
| Intel Ethernet Connection (5) I219-LM                                         | 18       | 0.6%    |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 17       | 0.57%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 16       | 0.53%   |
| Intel Ethernet Controller I225-LM                                             | 15       | 0.5%    |
| Intel Ethernet Connection (2) I218-V                                          | 15       | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 14       | 0.47%   |
| Intel Ethernet Connection I217-V                                              | 12       | 0.4%    |
| Intel Ethernet Connection X553 1GbE                                           | 11       | 0.37%   |
| Intel 82575GB Gigabit Network Connection                                      | 11       | 0.37%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 11       | 0.37%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 11       | 0.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10       | 0.33%   |
| Intel Ethernet Connection I354                                                | 10       | 0.33%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 10       | 0.33%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 9        | 0.3%    |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 9        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2020     | 79.59%  |
| WiFi     | 433      | 17.06%  |
| Unknown  | 62       | 2.44%   |
| Modem    | 23       | 0.91%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1972     | 96.52%  |
| WiFi     | 64       | 3.13%   |
| Unknown  | 7        | 0.34%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 487      | 23.28%  |
| 2     | 390      | 18.64%  |
| 3     | 344      | 16.44%  |
| 1     | 263      | 12.57%  |
| 6     | 254      | 12.14%  |
| 5     | 202      | 9.66%   |
| 7     | 56       | 2.68%   |
| 8     | 36       | 1.72%   |
| 9     | 20       | 0.96%   |
| 10    | 11       | 0.53%   |
| 0     | 11       | 0.53%   |
| 11    | 4        | 0.19%   |
| 16    | 3        | 0.14%   |
| 15    | 3        | 0.14%   |
| 14    | 2        | 0.1%    |
| 13    | 2        | 0.1%    |
| 12    | 2        | 0.1%    |
| 20    | 1        | 0.05%   |
| 17    | 1        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1644     | 76.82%  |
| Yes  | 496      | 23.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 184      | 62.16%  |
| Realtek Semiconductor           | 30       | 10.14%  |
| Qualcomm Atheros Communications | 14       | 4.73%   |
| Cambridge Silicon Radio         | 13       | 4.39%   |
| ASUSTek Computer                | 11       | 3.72%   |
| Broadcom                        | 10       | 3.38%   |
| Apple                           | 10       | 3.38%   |
| IMC Networks                    | 7        | 2.36%   |
| MediaTek                        | 6        | 2.03%   |
| Lite-On Technology              | 5        | 1.69%   |
| TP-Link                         | 1        | 0.34%   |
| Ralink                          | 1        | 0.34%   |
| Primax Electronics              | 1        | 0.34%   |
| Foxconn / Hon Hai               | 1        | 0.34%   |
| Dynex                           | 1        | 0.34%   |
| Corsair                         | 1        | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                       | 45       | 15.15%  |
| Intel Bluetooth wireless interface                          | 44       | 14.81%  |
| Intel AX201 Bluetooth                                       | 23       | 7.74%   |
| Intel Wireless-AC 3168 Bluetooth                            | 21       | 7.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 20       | 6.73%   |
| Intel AX210 Bluetooth                                       | 14       | 4.71%   |
| Realtek Bluetooth Adapter                                   | 13       | 4.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 13       | 4.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 10       | 3.37%   |
| Realtek  Bluetooth 4.2 Adapter                              | 9        | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 8        | 2.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 7        | 2.36%   |
| Realtek Bluetooth 4.2 Adapter                               | 6        | 2.02%   |
| MediaTek RZ608 Bluetooth Adapter                            | 6        | 2.02%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 6        | 2.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3        | 1.01%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 3        | 1.01%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2        | 0.67%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 2        | 0.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 2        | 0.67%   |
| Lite-On Bluetooth USB Module                                | 2        | 0.67%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 2        | 0.67%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS     | 2        | 0.67%   |
| Broadcom 20702 Bluetooth 4.0 Adapter                        | 2        | 0.67%   |
| ASUS USB-BT500                                              | 2        | 0.67%   |
| ASUS Qualcomm Bluetooth 4.1                                 | 2        | 0.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 2        | 0.67%   |
| ASUS Bluetooth USB module                                   | 2        | 0.67%   |
| ASUS Bluetooth Controller                                   | 2        | 0.67%   |
| Apple Bluetooth Host Controller                             | 2        | 0.67%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 1        | 0.34%   |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE                 | 1        | 0.34%   |
| Realtek Bluetooth 4.0 Adapter                               | 1        | 0.34%   |
| Ralink RT3290 Bluetooth                                     | 1        | 0.34%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1        | 0.34%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 1        | 0.34%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1        | 0.34%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1        | 0.34%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter               | 1        | 0.34%   |
| Lite-On Atheros AR9462 Bluetooth 4.0 + HS                   | 1        | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1267     | 65.75%  |
| AMD                                          | 368      | 19.1%   |
| Nvidia                                       | 185      | 9.6%    |
| C-Media Electronics                          | 34       | 1.76%   |
| Creative Labs                                | 13       | 0.67%   |
| SteelSeries ApS                              | 6        | 0.31%   |
| Logitech                                     | 5        | 0.26%   |
| Texas Instruments                            | 4        | 0.21%   |
| Blue Microphones                             | 4        | 0.21%   |
| Corsair                                      | 3        | 0.16%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.1%    |
| Yamaha                                       | 2        | 0.1%    |
| Realtek Semiconductor                        | 2        | 0.1%    |
| Razer USA                                    | 2        | 0.1%    |
| Google                                       | 2        | 0.1%    |
| Creative Technology                          | 2        | 0.1%    |
| ASUSTek Computer                             | 2        | 0.1%    |
| XMOS                                         | 1        | 0.05%   |
| VIA Technologies                             | 1        | 0.05%   |
| Universal Audio                              | 1        | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.05%   |
| Tenx Technology                              | 1        | 0.05%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.05%   |
| Quanta                                       | 1        | 0.05%   |
| Nektar                                       | 1        | 0.05%   |
| LG Electronics                               | 1        | 0.05%   |
| KTMicro                                      | 1        | 0.05%   |
| KORG                                         | 1        | 0.05%   |
| Kingston Technology                          | 1        | 0.05%   |
| Hewlett-Packard                              | 1        | 0.05%   |
| Harman                                       | 1        | 0.05%   |
| Genesys Logic                                | 1        | 0.05%   |
| Generalplus Technology                       | 1        | 0.05%   |
| Focusrite-Novation                           | 1        | 0.05%   |
| Dell                                         | 1        | 0.05%   |
| Cirrus Logic                                 | 1        | 0.05%   |
| Cambridge Silicon Radio                      | 1        | 0.05%   |
| AudioQuest                                   | 1        | 0.05%   |
| Astro Gaming                                 | 1        | 0.05%   |
| Apple                                        | 1        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 157      | 6.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 146      | 6.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 115      | 4.91%   |
| Intel Jasper Lake HD Audio                                                                        | 97       | 4.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 95       | 4.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 90       | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 83       | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 83       | 3.55%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 71       | 3.03%   |
| Intel 200 Series PCH HD Audio                                                                     | 64       | 2.74%   |
| AMD FCH Azalia Controller                                                                         | 64       | 2.74%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 62       | 2.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 61       | 2.61%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 58       | 2.48%   |
| AMD Kabini HDMI/DP Audio                                                                          | 44       | 1.88%   |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 43       | 1.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 43       | 1.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 42       | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 36       | 1.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 34       | 1.45%   |
| Intel Broadwell-U Audio Controller                                                                | 34       | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 34       | 1.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 33       | 1.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 27       | 1.15%   |
| Intel 8 Series HD Audio Controller                                                                | 26       | 1.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 26       | 1.11%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 24       | 1.03%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 22       | 0.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 21       | 0.9%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 19       | 0.81%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 19       | 0.81%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 15       | 0.64%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 15       | 0.64%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 15       | 0.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 15       | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 14       | 0.6%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 14       | 0.6%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 14       | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 13       | 0.56%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 13       | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Electronics                     | 326      | 14.76%  |
| Crucial                                 | 296      | 13.4%   |
| SK hynix                                | 267      | 12.09%  |
| Kingston                                | 223      | 10.1%   |
| Micron Technology                       | 200      | 9.05%   |
| Unknown                                 | 191      | 8.65%   |
| G.Skill                                 | 151      | 6.84%   |
| Corsair                                 | 127      | 5.75%   |
| Unknown                                 | 68       | 3.08%   |
| Team                                    | 60       | 2.72%   |
| Patriot                                 | 27       | 1.22%   |
| Ramaxel Technology                      | 26       | 1.18%   |
| A-DATA Technology                       | 23       | 1.04%   |
| Unknown (ABCD)                          | 22       | 1%      |
| Nanya Technology                        | 22       | 1%      |
| PNY                                     | 20       | 0.91%   |
| Transcend                               | 15       | 0.68%   |
| Kimtigo                                 | 15       | 0.68%   |
| Timetec                                 | 10       | 0.45%   |
| Silicon Power                           | 9        | 0.41%   |
| Super Talent                            | 7        | 0.32%   |
| Innodisk                                | 6        | 0.27%   |
| Elpida                                  | 6        | 0.27%   |
| Avant                                   | 6        | 0.27%   |
| SK_Hynix                                | 5        | 0.23%   |
| Silicon Power Computer & Communications | 5        | 0.23%   |
| GeIL                                    | 5        | 0.23%   |
| Sesame                                  | 4        | 0.18%   |
| Patriot Memory (PDP Systems)            | 4        | 0.18%   |
| Toshiba                                 | 3        | 0.14%   |
| Ramsta                                  | 3        | 0.14%   |
| Mushkin                                 | 3        | 0.14%   |
| Vasekey                                 | 2        | 0.09%   |
| Unknown (AB)                            | 2        | 0.09%   |
| Shenzhen Giant Hui Kang Tech            | 2        | 0.09%   |
| Neo Forza                               | 2        | 0.09%   |
| J&A Information                         | 2        | 0.09%   |
| GSkill                                  | 2        | 0.09%   |
| CSX                                     | 2        | 0.09%   |
| Apacer                                  | 2        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown                                                           | 68       | 2.92%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 22       | 0.94%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 21       | 0.9%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 18       | 0.77%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 17       | 0.73%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 16       | 0.69%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s               | 16       | 0.69%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 15       | 0.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 14       | 0.6%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 12       | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 12       | 0.52%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 11       | 0.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 11       | 0.47%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                    | 11       | 0.47%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s             | 11       | 0.47%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s              | 10       | 0.43%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s              | 10       | 0.43%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s             | 10       | 0.43%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s              | 9        | 0.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 9        | 0.39%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s              | 9        | 0.39%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s              | 9        | 0.39%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s               | 9        | 0.39%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s             | 9        | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 8        | 0.34%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s               | 8        | 0.34%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s                        | 8        | 0.34%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s              | 8        | 0.34%   |
| Samsung RAM M471B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s               | 8        | 0.34%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s               | 8        | 0.34%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s             | 8        | 0.34%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s             | 8        | 0.34%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 7        | 0.3%    |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                        | 7        | 0.3%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 7        | 0.3%    |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s             | 7        | 0.3%    |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s             | 7        | 0.3%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s               | 7        | 0.3%    |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s             | 7        | 0.3%    |
| Crucial RAM CT16G56C46S5.M8G1 16GB SODIMM DDR5 5600MT/s           | 7        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 870      | 44.8%   |
| DDR3         | 837      | 43.1%   |
| Unknown      | 60       | 3.09%   |
| DDR2         | 54       | 2.78%   |
| DDR5         | 48       | 2.47%   |
| LPDDR4       | 36       | 1.85%   |
| SDRAM        | 22       | 1.13%   |
| DDR          | 9        | 0.46%   |
| LPDDR5       | 4        | 0.21%   |
| LPDDR3       | 1        | 0.05%   |
| DDR2 FB-DIMM | 1        | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1240     | 64.45%  |
| SODIMM       | 620      | 32.22%  |
| Unknown      | 40       | 2.08%   |
| Row Of Chips | 17       | 0.88%   |
| RIMM         | 6        | 0.31%   |
| FB-DIMM      | 1        | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 870      | 42.11%  |
| 4096  | 565      | 27.35%  |
| 16384 | 324      | 15.68%  |
| 2048  | 174      | 8.42%   |
| 32768 | 95       | 4.6%    |
| 1024  | 31       | 1.5%    |
| 512   | 5        | 0.24%   |
| 65536 | 2        | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 622      | 30.14%  |
| 2400    | 264      | 12.79%  |
| 3200    | 236      | 11.43%  |
| 1333    | 219      | 10.61%  |
| 2667    | 180      | 8.72%   |
| 2133    | 174      | 8.43%   |
| 800     | 58       | 2.81%   |
| 2666    | 45       | 2.18%   |
| 4800    | 38       | 1.84%   |
| 3600    | 33       | 1.6%    |
| 3000    | 29       | 1.41%   |
| 667     | 29       | 1.41%   |
| 1066    | 26       | 1.26%   |
| Unknown | 19       | 0.92%   |
| 1867    | 18       | 0.87%   |
| 1067    | 13       | 0.63%   |
| 2933    | 11       | 0.53%   |
| 5600    | 9        | 0.44%   |
| 1334    | 9        | 0.44%   |
| 1866    | 7        | 0.34%   |
| 533     | 6        | 0.29%   |
| 6400    | 5        | 0.24%   |
| 4000    | 3        | 0.15%   |
| 4267    | 2        | 0.1%    |
| 4133    | 1        | 0.05%   |
| 3534    | 1        | 0.05%   |
| 3333    | 1        | 0.05%   |
| 2866    | 1        | 0.05%   |
| 1639    | 1        | 0.05%   |
| 1400    | 1        | 0.05%   |
| 1033    | 1        | 0.05%   |
| 400     | 1        | 0.05%   |
| 266     | 1        | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 2        | 28.57%  |
| Brother Industries    | 2        | 28.57%  |
| Prolific Technology   | 1        | 14.29%  |
| Lexmark International | 1        | 14.29%  |
| Apple                 | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port                                            | 1        | 12.5%   |
| Lexmark International Lexmark MS710 Print                                | 1        | 12.5%   |
| HP PNP Fax Null                                                          | 1        | 12.5%   |
| HP LaserJet 1012                                                         | 1        | 12.5%   |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer | 1        | 12.5%   |
| Brother MFC-L2685DW                                                      | 1        | 12.5%   |
| Brother MFC-J485DW                                                       | 1        | 12.5%   |
| Apple Gamesir-G3s 2.10                                                   | 1        | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 2        | 66.67%  |
| Hewlett-Packard | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Desktops | Percent |
|-------------------------------------------------------------------------------------|----------|---------|
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 2        | 66.67%  |
| HP ScanJet 5300c/5370c                                                              | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 21       | 48.84%  |
| Microdia                      | 5        | 11.63%  |
| Sunplus Innovation Technology | 3        | 6.98%   |
| WCM_USB                       | 2        | 4.65%   |
| SHENZHEN EMEET TECHNOLOGY     | 2        | 4.65%   |
| Generalplus Technology        | 2        | 4.65%   |
| Chicony Electronics           | 2        | 4.65%   |
| Xiongmai                      | 1        | 2.33%   |
| Suyin                         | 1        | 2.33%   |
| Quanta                        | 1        | 2.33%   |
| Lenovo                        | 1        | 2.33%   |
| Arkmicro Technologies         | 1        | 2.33%   |
| ARC International             | 1        | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 6        | 13.95%  |
| Logitech HD Pro Webcam C920                    | 6        | 13.95%  |
| Microdia Webcam Vitade AF                      | 3        | 6.98%   |
| Logitech C922 Pro Stream Webcam                | 3        | 6.98%   |
| WCM_USB WEB CAM                                | 2        | 4.65%   |
| Sunplus USB 2.0 Camera                         | 2        | 4.65%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 2        | 4.65%   |
| Logitech Webcam C310                           | 2        | 4.65%   |
| Logitech BRIO Ultra HD Webcam                  | 2        | 4.65%   |
| Generalplus HD Webcam                          | 2        | 4.65%   |
| Xiongmai web camera                            | 1        | 2.33%   |
| Suyin Acer CrystalEye Webcam                   | 1        | 2.33%   |
| Sunplus hama C-600 Pro Webcam                  | 1        | 2.33%   |
| Quanta Realtek DMFT RGB                        | 1        | 2.33%   |
| Microdia Ltd., USB  Live camera                | 1        | 2.33%   |
| Microdia Camera                                | 1        | 2.33%   |
| Logitech HD Webcam C615                        | 1        | 2.33%   |
| Logitech HD Webcam C525                        | 1        | 2.33%   |
| Lenovo Integrated Camera                       | 1        | 2.33%   |
| Chicony Ltd., HP 0.3MP Webcam                  | 1        | 2.33%   |
| Chicony HP High Definition 1MP Webcam          | 1        | 2.33%   |
| Arkmicro USB 2.0 PC CAMERA                     | 1        | 2.33%   |
| ARC International Camera                       | 1        | 2.33%   |

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
| 1     | 1068     | 50.95%  |
| 0     | 633      | 30.2%   |
| 2     | 281      | 13.41%  |
| 3     | 90       | 4.29%   |
| 4     | 20       | 0.95%   |
| 7     | 2        | 0.1%    |
| 6     | 1        | 0.05%   |
| 5     | 1        | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 1262     | 72.03%  |
| Net/wireless             | 144      | 8.22%   |
| Bluetooth                | 127      | 7.25%   |
| Firewire controller      | 60       | 3.42%   |
| Net/ethernet             | 40       | 2.28%   |
| Sound                    | 37       | 2.11%   |
| Card reader              | 34       | 1.94%   |
| Network                  | 32       | 1.83%   |
| Graphics card            | 8        | 0.46%   |
| Storage/raid             | 6        | 0.34%   |
| Storage/ata              | 1        | 0.06%   |
| Dvb card                 | 1        | 0.06%   |

