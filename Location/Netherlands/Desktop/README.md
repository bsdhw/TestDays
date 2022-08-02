BSD in Netherlands - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for BSD in Netherlands.

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

Total: 199

| Vendor     | Model                       | Probe                                                     | Date         |
|------------|-----------------------------|-----------------------------------------------------------|--------------|
| Gigabyte   | X570 AORUS PRO              | [ad56307789](https://bsd-hardware.info/?probe=ad56307789) | Aug 01, 2022 |
| Gigabyte   | H310M S2H                   | [03d0919731](https://bsd-hardware.info/?probe=03d0919731) | Jul 29, 2022 |
| Deciso     | Netboard A10                | [3f548f31e3](https://bsd-hardware.info/?probe=3f548f31e3) | Jul 25, 2022 |
| Intel      | Q3XXG4-P V1.0               | [6daa6d0060](https://bsd-hardware.info/?probe=6daa6d0060) | Jul 24, 2022 |
| Protectli  | FW4B                        | [b1ac4ad0dd](https://bsd-hardware.info/?probe=b1ac4ad0dd) | Jul 18, 2022 |
| Pegatron   | 2AB5                        | [d48d3e4777](https://bsd-hardware.info/?probe=d48d3e4777) | Jul 05, 2022 |
| Protectli  | FW4B                        | [c4e6db8739](https://bsd-hardware.info/?probe=c4e6db8739) | Jul 03, 2022 |
| ASRock     | X300M-STX                   | [a76b64487b](https://bsd-hardware.info/?probe=a76b64487b) | Jul 01, 2022 |
| ASRock     | B550 Phantom Gaming-ITX/... | [ff3865e01f](https://bsd-hardware.info/?probe=ff3865e01f) | Jun 05, 2022 |
| ASRock     | Z77 Pro4-M                  | [4be827d8fe](https://bsd-hardware.info/?probe=4be827d8fe) | Jun 01, 2022 |
| MW         | GMLK-2_5G4L                 | [5893942a80](https://bsd-hardware.info/?probe=5893942a80) | May 30, 2022 |
| Unknown    | Raspberry Pi 4 Model B R... | [ade09344b8](https://bsd-hardware.info/?probe=ade09344b8) | May 26, 2022 |
| Unknown    | Raspberry Pi 4 Model B R... | [cc37ea1b7d](https://bsd-hardware.info/?probe=cc37ea1b7d) | May 26, 2022 |
| Unknown    | Raspberry Pi 4 Model B R... | [abacee12a9](https://bsd-hardware.info/?probe=abacee12a9) | May 26, 2022 |
| Unknown    | Raspberry Pi 3 Model B P... | [21fa41e4c1](https://bsd-hardware.info/?probe=21fa41e4c1) | May 26, 2022 |
| ASRock     | B550 Phantom Gaming-ITX/... | [3dc5a6f7d2](https://bsd-hardware.info/?probe=3dc5a6f7d2) | May 24, 2022 |
| Pegatron   | 2AB5                        | [5cc0eb3e94](https://bsd-hardware.info/?probe=5cc0eb3e94) | May 11, 2022 |
| Unknown    | Unknown                     | [66432302a4](https://bsd-hardware.info/?probe=66432302a4) | May 07, 2022 |
| PC Engines | APU2                        | [26be7dfcb8](https://bsd-hardware.info/?probe=26be7dfcb8) | Apr 28, 2022 |
| PC Engines | APU2                        | [4405a65be4](https://bsd-hardware.info/?probe=4405a65be4) | Apr 28, 2022 |
| PC Engines | APU2                        | [5d79f85176](https://bsd-hardware.info/?probe=5d79f85176) | Apr 27, 2022 |
| PC Engines | APU2                        | [3fe99889aa](https://bsd-hardware.info/?probe=3fe99889aa) | Apr 26, 2022 |
| Unknown    | Unknown                     | [095a279c7b](https://bsd-hardware.info/?probe=095a279c7b) | Apr 25, 2022 |
| Gigabyte   | X570 AORUS PRO              | [4e7d57df3b](https://bsd-hardware.info/?probe=4e7d57df3b) | Apr 18, 2022 |
| HP         | 1998                        | [4f15447536](https://bsd-hardware.info/?probe=4f15447536) | Apr 18, 2022 |
| Unknown    | Unknown                     | [f58e088df2](https://bsd-hardware.info/?probe=f58e088df2) | Apr 16, 2022 |
| Protectli  | FW6D                        | [e79304e1dc](https://bsd-hardware.info/?probe=e79304e1dc) | Apr 07, 2022 |
| Gigabyte   | B560M D3H                   | [99343fc0da](https://bsd-hardware.info/?probe=99343fc0da) | Apr 06, 2022 |
| HPE        | ProLiant MicroServer Gen... | [7db1501c5c](https://bsd-hardware.info/?probe=7db1501c5c) | Apr 06, 2022 |
| ASRock     | H61DE/S3                    | [00183a69ec](https://bsd-hardware.info/?probe=00183a69ec) | Apr 05, 2022 |
| Biostar    | H61MGV3                     | [1ef10e5e36](https://bsd-hardware.info/?probe=1ef10e5e36) | Apr 03, 2022 |
| PC Engines | apu4                        | [618b2c7955](https://bsd-hardware.info/?probe=618b2c7955) | Mar 27, 2022 |
| HARDKERNEL | ODROID-H2                   | [a1700b0347](https://bsd-hardware.info/?probe=a1700b0347) | Mar 21, 2022 |
| Deciso     | Netboard A10 V2.1           | [671c66ca19](https://bsd-hardware.info/?probe=671c66ca19) | Mar 21, 2022 |
| Protectli  | FW4B                        | [5323027ba0](https://bsd-hardware.info/?probe=5323027ba0) | Mar 13, 2022 |
| Gigabyte   | J1900N-D3V                  | [ec336ddab4](https://bsd-hardware.info/?probe=ec336ddab4) | Mar 08, 2022 |
| Unknown    | Unknown                     | [c91c5fe588](https://bsd-hardware.info/?probe=c91c5fe588) | Mar 03, 2022 |
| Supermicro | M11SDV-8C-LN4F              | [e4f7f31828](https://bsd-hardware.info/?probe=e4f7f31828) | Feb 28, 2022 |
| Intel      | Q3XXG4-P V1.0               | [74f28d34fd](https://bsd-hardware.info/?probe=74f28d34fd) | Feb 27, 2022 |
| Dell       | 0R230R A00                  | [f3444924fd](https://bsd-hardware.info/?probe=f3444924fd) | Feb 17, 2022 |
| Dell       | 0R230R A00                  | [91870de9fe](https://bsd-hardware.info/?probe=91870de9fe) | Feb 06, 2022 |
| MSI        | H81I                        | [fe3a834f0b](https://bsd-hardware.info/?probe=fe3a834f0b) | Feb 05, 2022 |
| MW         | GMLK-2_5G4L                 | [f785bcb17a](https://bsd-hardware.info/?probe=f785bcb17a) | Feb 04, 2022 |
| MW         | GMLK-2_5G4L                 | [96436a1882](https://bsd-hardware.info/?probe=96436a1882) | Feb 03, 2022 |
| Dell       | 0R230R A00                  | [cb50949dca](https://bsd-hardware.info/?probe=cb50949dca) | Jan 28, 2022 |
| ASUSTek    | PRIME H410M-A               | [c7ef0e518f](https://bsd-hardware.info/?probe=c7ef0e518f) | Jan 27, 2022 |
| ASUSTek    | PRIME H410M-A               | [c2d7238521](https://bsd-hardware.info/?probe=c2d7238521) | Jan 27, 2022 |
| Intel      | Q3XXG4-P V1.0               | [04afa3aa4f](https://bsd-hardware.info/?probe=04afa3aa4f) | Jan 23, 2022 |
| ASUSTek    | PRIME H410M-A               | [625c8f0f2c](https://bsd-hardware.info/?probe=625c8f0f2c) | Jan 14, 2022 |
| ASUSTek    | PRIME H410M-A               | [d09cf2e0a7](https://bsd-hardware.info/?probe=d09cf2e0a7) | Jan 14, 2022 |
| MSI        | H61I-E35 V2/W8              | [8ae05f9d72](https://bsd-hardware.info/?probe=8ae05f9d72) | Jan 05, 2022 |
| XtReAmEr   | Unknown                     | [bd1315aa70](https://bsd-hardware.info/?probe=bd1315aa70) | Jan 04, 2022 |
| Unknown    | Unknown                     | [0efa2c0531](https://bsd-hardware.info/?probe=0efa2c0531) | Dec 31, 2021 |
| Unknown    | Unknown                     | [79370c33df](https://bsd-hardware.info/?probe=79370c33df) | Dec 28, 2021 |
| Unknown    | Unknown                     | [c5e31aaf52](https://bsd-hardware.info/?probe=c5e31aaf52) | Dec 28, 2021 |
| Intel      | Q3XXG4-P V1.0               | [30aab74fbc](https://bsd-hardware.info/?probe=30aab74fbc) | Dec 24, 2021 |
| Unknown    | Raspberry Pi 4 Model B R... | [69bf80f0c6](https://bsd-hardware.info/?probe=69bf80f0c6) | Dec 20, 2021 |
| Unknown    | Raspberry Pi 3 Model B P... | [ef0dcfaccf](https://bsd-hardware.info/?probe=ef0dcfaccf) | Dec 20, 2021 |
| Gigabyte   | X570 AORUS PRO              | [17cad87a0d](https://bsd-hardware.info/?probe=17cad87a0d) | Dec 19, 2021 |
| PC Engines | apu4                        | [f72343bec1](https://bsd-hardware.info/?probe=f72343bec1) | Dec 19, 2021 |
| Unknown    | Unknown                     | [cd27dd3e2b](https://bsd-hardware.info/?probe=cd27dd3e2b) | Dec 17, 2021 |
| Fujitsu    | D3313-A1 S26361-D3313-A1    | [fd05f5bf41](https://bsd-hardware.info/?probe=fd05f5bf41) | Dec 11, 2021 |
| HP         | 8105                        | [e38c91e91e](https://bsd-hardware.info/?probe=e38c91e91e) | Dec 11, 2021 |
| HP         | 8105                        | [0b923d55bc](https://bsd-hardware.info/?probe=0b923d55bc) | Dec 11, 2021 |
| Protectli  | FW6D                        | [33731d5933](https://bsd-hardware.info/?probe=33731d5933) | Dec 11, 2021 |
| Unknown    | Raspberry Pi 4 Model B R... | [5dbff17614](https://bsd-hardware.info/?probe=5dbff17614) | Dec 06, 2021 |
| Unknown    | Raspberry Pi 3 Model B P... | [646ca92a69](https://bsd-hardware.info/?probe=646ca92a69) | Dec 06, 2021 |
| Alienware  | 01NYPT A00                  | [75aa0c00fb](https://bsd-hardware.info/?probe=75aa0c00fb) | Dec 06, 2021 |
| Lenovo     | MAHOBAY                     | [b77016bee5](https://bsd-hardware.info/?probe=b77016bee5) | Nov 25, 2021 |
| ASRock     | IMB-195                     | [58e7426808](https://bsd-hardware.info/?probe=58e7426808) | Nov 24, 2021 |
| HP         | 339A                        | [a123d76249](https://bsd-hardware.info/?probe=a123d76249) | Nov 19, 2021 |
| HP         | 1497                        | [24a8d1bb7a](https://bsd-hardware.info/?probe=24a8d1bb7a) | Nov 17, 2021 |
| PC Engines | APU                         | [ca05f41685](https://bsd-hardware.info/?probe=ca05f41685) | Nov 16, 2021 |
| Dell       | 0R230R A00                  | [c2c6cf4b4d](https://bsd-hardware.info/?probe=c2c6cf4b4d) | Nov 16, 2021 |
| Unknown    | Unknown                     | [c473c704a9](https://bsd-hardware.info/?probe=c473c704a9) | Nov 14, 2021 |
| Unknown    | Unknown                     | [ec7dfabb51](https://bsd-hardware.info/?probe=ec7dfabb51) | Nov 12, 2021 |
| Protectli  | FW4B                        | [cb7b87cd57](https://bsd-hardware.info/?probe=cb7b87cd57) | Nov 09, 2021 |
| Unknown    | Unknown                     | [f80c884b6f](https://bsd-hardware.info/?probe=f80c884b6f) | Oct 31, 2021 |
| Gigabyte   | J1900N-D3V                  | [e4958e59b0](https://bsd-hardware.info/?probe=e4958e59b0) | Oct 29, 2021 |
| Unknown    | YL-J3160L4                  | [bc4b7f33d5](https://bsd-hardware.info/?probe=bc4b7f33d5) | Oct 25, 2021 |
| Supermicro | M11SDV-8C-LN4F              | [54c792ac8a](https://bsd-hardware.info/?probe=54c792ac8a) | Oct 20, 2021 |
| Intel      | Q3XXG4-P V1.0               | [67e62d9dd3](https://bsd-hardware.info/?probe=67e62d9dd3) | Oct 11, 2021 |
| Unknown    | Unknown                     | [b3b0308132](https://bsd-hardware.info/?probe=b3b0308132) | Oct 02, 2021 |
| Intel      | CRESCENTBAY                 | [712bbd0635](https://bsd-hardware.info/?probe=712bbd0635) | Sep 29, 2021 |
| Protectli  | FW6D                        | [ee70d4b2fe](https://bsd-hardware.info/?probe=ee70d4b2fe) | Sep 25, 2021 |
| MSI        | H61I-E35 V2/W8              | [359cb66936](https://bsd-hardware.info/?probe=359cb66936) | Sep 24, 2021 |
| Intel      | Q3XXG4-P V1.0               | [1afa203e69](https://bsd-hardware.info/?probe=1afa203e69) | Sep 22, 2021 |
| Sapphire   | EDGE-FT1M1 E450 1AOVU044    | [ea8fefdf4e](https://bsd-hardware.info/?probe=ea8fefdf4e) | Sep 20, 2021 |
| Shuttle    | XH310V2                     | [f37b485384](https://bsd-hardware.info/?probe=f37b485384) | Sep 19, 2021 |
| Unknown    | Unknown                     | [ba40cc9f75](https://bsd-hardware.info/?probe=ba40cc9f75) | Sep 17, 2021 |
| Intel      | SHARKBAY                    | [70d35afae8](https://bsd-hardware.info/?probe=70d35afae8) | Sep 15, 2021 |
| Sapphire   | EDGE-FT1M1 E450 1AOVU044    | [85ed325446](https://bsd-hardware.info/?probe=85ed325446) | Sep 11, 2021 |
| Fujitsu    | D3003-S2 S26361-D3003-S2    | [0510213747](https://bsd-hardware.info/?probe=0510213747) | Aug 30, 2021 |
| Unknown    | YL-J3160L4                  | [b3a20bafca](https://bsd-hardware.info/?probe=b3a20bafca) | Aug 29, 2021 |
| Unknown    | YL-J3160L4                  | [03e08762a6](https://bsd-hardware.info/?probe=03e08762a6) | Aug 27, 2021 |
| Shuttle    | DH370                       | [dea088a5bd](https://bsd-hardware.info/?probe=dea088a5bd) | Aug 20, 2021 |
| Protectli  | FW4B                        | [ab6695bb0b](https://bsd-hardware.info/?probe=ab6695bb0b) | Aug 18, 2021 |
| HP         | 213D A01                    | [6e52020062](https://bsd-hardware.info/?probe=6e52020062) | Aug 10, 2021 |
| Shuttle    | DH370                       | [6d81fef4fb](https://bsd-hardware.info/?probe=6d81fef4fb) | Aug 09, 2021 |
| Unknown    | Unknown                     | [164b888dbe](https://bsd-hardware.info/?probe=164b888dbe) | Aug 08, 2021 |
| Intel      | Q3XXG4-P V1.0               | [a6de85de91](https://bsd-hardware.info/?probe=a6de85de91) | Jul 29, 2021 |
| Intel      | Q3XXG4-P V1.0               | [1e337fe131](https://bsd-hardware.info/?probe=1e337fe131) | Jul 29, 2021 |
| Unknown    | Unknown                     | [dd66bc21f6](https://bsd-hardware.info/?probe=dd66bc21f6) | Jul 27, 2021 |
| Unknown    | Unknown                     | [b7edcfabb6](https://bsd-hardware.info/?probe=b7edcfabb6) | Jul 25, 2021 |
| PC Engines | apu4                        | [027bbc5028](https://bsd-hardware.info/?probe=027bbc5028) | Jul 14, 2021 |
| HP         | 18E9                        | [7bac3be335](https://bsd-hardware.info/?probe=7bac3be335) | Jun 29, 2021 |
| Dell EMC   | VEP1425-V210-CPU A00        | [ad34d48259](https://bsd-hardware.info/?probe=ad34d48259) | Jun 27, 2021 |
| Dell       | 0WR7PY A02                  | [ad5db0563f](https://bsd-hardware.info/?probe=ad5db0563f) | Jun 26, 2021 |
| Intel      | Q3XXG4-P V1.0               | [ee8a47b051](https://bsd-hardware.info/?probe=ee8a47b051) | Jun 17, 2021 |
| HP         | 3397                        | [3dd97c60ca](https://bsd-hardware.info/?probe=3dd97c60ca) | Jun 16, 2021 |
| MSI        | B85M-P33 V2                 | [0633d1c78e](https://bsd-hardware.info/?probe=0633d1c78e) | Jun 10, 2021 |
| ASUSTek    | PRIME Z590M-PLUS            | [db12a78352](https://bsd-hardware.info/?probe=db12a78352) | Jun 08, 2021 |
| ASRock     | B450M Pro4                  | [9a7adb8860](https://bsd-hardware.info/?probe=9a7adb8860) | Jun 06, 2021 |
| Inventec   | R CLASS A02                 | [b621aeaac3](https://bsd-hardware.info/?probe=b621aeaac3) | May 30, 2021 |
| Gigabyte   | B85-HD3                     | [331da3091c](https://bsd-hardware.info/?probe=331da3091c) | May 28, 2021 |
| Dell       | 0200DY A02                  | [fcbfbc2dfa](https://bsd-hardware.info/?probe=fcbfbc2dfa) | May 25, 2021 |
| Unknown    | YL-J3160L4                  | [8448df79cd](https://bsd-hardware.info/?probe=8448df79cd) | May 21, 2021 |
| Unknown    | YL-J3160L4                  | [594c0438a0](https://bsd-hardware.info/?probe=594c0438a0) | May 21, 2021 |
| Shuttle    | FH87                        | [bf5457ff02](https://bsd-hardware.info/?probe=bf5457ff02) | May 09, 2021 |
| Dell       | 0FJ030                      | [91418a4965](https://bsd-hardware.info/?probe=91418a4965) | Apr 30, 2021 |
| Dell       | 0FJ030                      | [7bee24ee8a](https://bsd-hardware.info/?probe=7bee24ee8a) | Apr 30, 2021 |
| Dell       | 0FJ030                      | [d5277ad9e1](https://bsd-hardware.info/?probe=d5277ad9e1) | Apr 30, 2021 |
| Dell       | 0FJ030                      | [63b1980830](https://bsd-hardware.info/?probe=63b1980830) | Apr 30, 2021 |
| HP         | 1998                        | [f6b53096d4](https://bsd-hardware.info/?probe=f6b53096d4) | Apr 28, 2021 |
| Intel      | Q3XXG4-P V1.0               | [a90eea4001](https://bsd-hardware.info/?probe=a90eea4001) | Apr 27, 2021 |
| HP         | 1497                        | [26724735db](https://bsd-hardware.info/?probe=26724735db) | Apr 24, 2021 |
| HP         | 1998                        | [051c63e153](https://bsd-hardware.info/?probe=051c63e153) | Apr 24, 2021 |
| ASRock     | J4105-ITX                   | [66eee76b50](https://bsd-hardware.info/?probe=66eee76b50) | Apr 21, 2021 |
| HP         | 1998                        | [7207f742d6](https://bsd-hardware.info/?probe=7207f742d6) | Apr 20, 2021 |
| Intel      | Q3XXG4-P V1.0               | [634521b082](https://bsd-hardware.info/?probe=634521b082) | Apr 07, 2021 |
| Unknown    | Unknown                     | [15e5f7932e](https://bsd-hardware.info/?probe=15e5f7932e) | Apr 06, 2021 |
| PC Engines | apu4                        | [06a59860a8](https://bsd-hardware.info/?probe=06a59860a8) | Apr 04, 2021 |
| Dell       | 0200DY A02                  | [060ebba6d2](https://bsd-hardware.info/?probe=060ebba6d2) | Mar 30, 2021 |
| MSI        | H410M-A PRO                 | [88f2766975](https://bsd-hardware.info/?probe=88f2766975) | Mar 27, 2021 |
| Shuttle    | FS310                       | [6514807d96](https://bsd-hardware.info/?probe=6514807d96) | Mar 25, 2021 |
| ASRock     | Z77 Pro4-M                  | [b8f568202d](https://bsd-hardware.info/?probe=b8f568202d) | Mar 22, 2021 |
| HP         | ProLiant DL360 Gen9         | [b283b34881](https://bsd-hardware.info/?probe=b283b34881) | Mar 17, 2021 |
| iEi        | E452 V1.00                  | [b5665d0df2](https://bsd-hardware.info/?probe=b5665d0df2) | Mar 17, 2021 |
| HP         | ProLiant DL360 Gen9         | [bf440e72a1](https://bsd-hardware.info/?probe=bf440e72a1) | Mar 17, 2021 |
| HP         | EliteDesk 800 G5 SFF        | [aaf9bc1c12](https://bsd-hardware.info/?probe=aaf9bc1c12) | Mar 17, 2021 |
| ASRock     | Z490M Pro4                  | [6e0891ce80](https://bsd-hardware.info/?probe=6e0891ce80) | Mar 17, 2021 |
| ASRock     | Z490M-ITX/ac                | [ee59c99fe4](https://bsd-hardware.info/?probe=ee59c99fe4) | Mar 15, 2021 |
| Unknown    | YL-J3160L4                  | [359c03f28d](https://bsd-hardware.info/?probe=359c03f28d) | Mar 12, 2021 |
| HP         | 18E9                        | [cc435f4cd1](https://bsd-hardware.info/?probe=cc435f4cd1) | Mar 10, 2021 |
| Unknown    | Unknown                     | [2093895427](https://bsd-hardware.info/?probe=2093895427) | Mar 10, 2021 |
| Pegatron   | 2AB5                        | [f30a9505dd](https://bsd-hardware.info/?probe=f30a9505dd) | Mar 07, 2021 |
| Unknown    | Unknown                     | [2abc226441](https://bsd-hardware.info/?probe=2abc226441) | Mar 05, 2021 |
| Unknown    | Unknown                     | [60e0b1d346](https://bsd-hardware.info/?probe=60e0b1d346) | Mar 04, 2021 |
| Unknown    | Unknown                     | [db37dfcbf3](https://bsd-hardware.info/?probe=db37dfcbf3) | Mar 02, 2021 |
| MSI        | H410M-A PRO                 | [64bf9eb4cf](https://bsd-hardware.info/?probe=64bf9eb4cf) | Mar 01, 2021 |
| MSI        | H410M-A PRO                 | [eacaff1fff](https://bsd-hardware.info/?probe=eacaff1fff) | Feb 28, 2021 |
| Unknown    | YL-J3160L4                  | [47c08e3817](https://bsd-hardware.info/?probe=47c08e3817) | Feb 27, 2021 |
| ASRock     | Z490M-ITX/ac                | [9901302790](https://bsd-hardware.info/?probe=9901302790) | Feb 27, 2021 |
| Dell       | 00V62H A00                  | [441133db7f](https://bsd-hardware.info/?probe=441133db7f) | Feb 24, 2021 |
| Unknown    | Unknown                     | [1008505c8a](https://bsd-hardware.info/?probe=1008505c8a) | Feb 23, 2021 |
| MSI        | H410M-A PRO                 | [7d9e05b2fd](https://bsd-hardware.info/?probe=7d9e05b2fd) | Feb 21, 2021 |
| MSI        | H410M-A PRO                 | [408ba48f1f](https://bsd-hardware.info/?probe=408ba48f1f) | Feb 21, 2021 |
| Unknown    | Unknown                     | [6c0a1e1154](https://bsd-hardware.info/?probe=6c0a1e1154) | Feb 20, 2021 |
| Supermicro | X8SIL                       | [6318953f01](https://bsd-hardware.info/?probe=6318953f01) | Feb 18, 2021 |
| Supermicro | X9SCL/X9SCM                 | [a57dba0cb2](https://bsd-hardware.info/?probe=a57dba0cb2) | Feb 16, 2021 |
| Dell       | 0T7D40 A01                  | [301fc86371](https://bsd-hardware.info/?probe=301fc86371) | Feb 15, 2021 |
| Protectli  | FW2B Ver                    | [57ca4c3cac](https://bsd-hardware.info/?probe=57ca4c3cac) | Feb 15, 2021 |
| Unknown    | Unknown                     | [994b94b7f5](https://bsd-hardware.info/?probe=994b94b7f5) | Feb 13, 2021 |
| ASUSTek    | P5Q-PRO                     | [9ff4167171](https://bsd-hardware.info/?probe=9ff4167171) | Feb 12, 2021 |
| PC Engines | apu4                        | [67e0b30093](https://bsd-hardware.info/?probe=67e0b30093) | Feb 05, 2021 |
| PC Engines | apu4                        | [d4b1d0ae99](https://bsd-hardware.info/?probe=d4b1d0ae99) | Feb 03, 2021 |
| PC Engines | APU                         | [91da54ca8c](https://bsd-hardware.info/?probe=91da54ca8c) | Feb 02, 2021 |
| Dell       | 0T7D40 A01                  | [1f5bf7092c](https://bsd-hardware.info/?probe=1f5bf7092c) | Feb 01, 2021 |
| Inventec   | VXC Class A02               | [22d0861af3](https://bsd-hardware.info/?probe=22d0861af3) | Jan 29, 2021 |
| Unknown    | Unknown                     | [f4b460a5e4](https://bsd-hardware.info/?probe=f4b460a5e4) | Jan 28, 2021 |
| Inventec   | VXC Class A02               | [8c298fa5bf](https://bsd-hardware.info/?probe=8c298fa5bf) | Jan 28, 2021 |
| Inventec   | VXC Class A02               | [6127d635de](https://bsd-hardware.info/?probe=6127d635de) | Jan 27, 2021 |
| Unknown    | Unknown                     | [f76df86f03](https://bsd-hardware.info/?probe=f76df86f03) | Jan 26, 2021 |
| HPE        | ProLiant MicroServer Gen... | [881d50fc9e](https://bsd-hardware.info/?probe=881d50fc9e) | Jan 26, 2021 |
| ASRock     | Z490M-ITX/ac                | [97fd3d11e8](https://bsd-hardware.info/?probe=97fd3d11e8) | Jan 25, 2021 |
| ASRock     | Z490M-ITX/ac                | [2577292fe1](https://bsd-hardware.info/?probe=2577292fe1) | Jan 25, 2021 |
| Inventec   | R CLASS A02                 | [545854fcfd](https://bsd-hardware.info/?probe=545854fcfd) | Jan 24, 2021 |
| Intel      | Q3XXG4-P V1.0               | [5b00abed29](https://bsd-hardware.info/?probe=5b00abed29) | Jan 23, 2021 |
| Intel      | CRESCENTBAY                 | [f8e3f072fc](https://bsd-hardware.info/?probe=f8e3f072fc) | Jan 23, 2021 |
| Intel      | Q3XXG4-P V1.0               | [3c0683ff11](https://bsd-hardware.info/?probe=3c0683ff11) | Jan 22, 2021 |
| Intel      | Q3XXG4-P V1.0               | [5d556cc47f](https://bsd-hardware.info/?probe=5d556cc47f) | Jan 22, 2021 |
| AMI        | PEISIA E3845 VER1.0         | [4b2e64662e](https://bsd-hardware.info/?probe=4b2e64662e) | Jan 21, 2021 |
| Unknown    | Unknown                     | [951a898a3f](https://bsd-hardware.info/?probe=951a898a3f) | Jan 21, 2021 |
| Unknown    | Unknown                     | [a1b0841493](https://bsd-hardware.info/?probe=a1b0841493) | Jan 21, 2021 |
| ASRock     | Z77 Pro4-M                  | [064e82b131](https://bsd-hardware.info/?probe=064e82b131) | Jan 21, 2021 |
| ASRockRack | EPC612D4U-8R                | [617694f591](https://bsd-hardware.info/?probe=617694f591) | Dec 19, 2020 |
| ASRock     | B360 Pro4                   | [05d3ab8d4b](https://bsd-hardware.info/?probe=05d3ab8d4b) | Oct 29, 2020 |
| ASUSTek    | H110I-PLUS                  | [57ecc0c410](https://bsd-hardware.info/?probe=57ecc0c410) | Oct 29, 2020 |
| HPE        | ProLiant MicroServer Gen... | [3cebf4d7db](https://bsd-hardware.info/?probe=3cebf4d7db) | Oct 29, 2020 |
| ASRockRack | EPC612D4U-8R                | [b9ecd0e2b3](https://bsd-hardware.info/?probe=b9ecd0e2b3) | Oct 29, 2020 |
| Dell       | Precision WorkStation T7... | [c01ce9ec81](https://bsd-hardware.info/?probe=c01ce9ec81) | Oct 24, 2020 |
| Gigabyte   | Z97-D3H-CF                  | [dc33c84287](https://bsd-hardware.info/?probe=dc33c84287) | Oct 22, 2020 |
| Dell       | PowerEdge R620              | [7671a495d1](https://bsd-hardware.info/?probe=7671a495d1) | Oct 19, 2020 |
| Dell       | PowerEdge R620              | [c1a2bc7a51](https://bsd-hardware.info/?probe=c1a2bc7a51) | Oct 19, 2020 |
| Dell       | PowerEdge R620              | [c1c5ee566c](https://bsd-hardware.info/?probe=c1c5ee566c) | Oct 19, 2020 |
| Dell       | PowerEdge R620              | [af87ddbbaa](https://bsd-hardware.info/?probe=af87ddbbaa) | Oct 19, 2020 |
| Gigabyte   | MQLP7AP-00                  | [07036eab43](https://bsd-hardware.info/?probe=07036eab43) | May 28, 2020 |
| Gigabyte   | Z68MA-D2H-B3                | [85bebeaea0](https://bsd-hardware.info/?probe=85bebeaea0) | May 25, 2020 |
| Gigabyte   | Z68MA-D2H-B3                | [9fea968a19](https://bsd-hardware.info/?probe=9fea968a19) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| OPNsense 21.7.7              | 8        | 5%      |
| OPNsense 21.1.1              | 7        | 4.38%   |
| OPNsense 20.7.8              | 7        | 4.38%   |
| OPNsense 21.7.5              | 6        | 3.75%   |
| OPNsense 21.7.3              | 6        | 3.75%   |
| OPNsense 21.7.2              | 6        | 3.75%   |
| OPNsense 21.7.1              | 6        | 3.75%   |
| OPNsense 21.1.2              | 6        | 3.75%   |
| OPNsense 22.1.6              | 5        | 3.13%   |
| OPNsense 21.1.7              | 5        | 3.13%   |
| OPNsense 21.1.3              | 5        | 3.13%   |
| OPNsense 21.1                | 5        | 3.13%   |
| OpenBSD 6.8                  | 5        | 3.13%   |
| FreeBSD 13.0                 | 5        | 3.13%   |
| OPNsense 22.1.4              | 4        | 2.5%    |
| OPNsense 21.1.5              | 4        | 2.5%    |
| OpenBSD 7.1                  | 4        | 2.5%    |
| OPNsense 22.1.10             | 3        | 1.88%   |
| OPNsense 22.1.1              | 3        | 1.88%   |
| OPNsense 22.1                | 3        | 1.88%   |
| OPNsense 21.7.8              | 3        | 1.88%   |
| OPNsense 21.7.6              | 3        | 1.88%   |
| OPNsense 21.7.4              | 3        | 1.88%   |
| OPNsense 21.1.4              | 3        | 1.88%   |
| FreeBSD 13.0-p5              | 3        | 1.88%   |
| FreeBSD 12.1-p10             | 3        | 1.88%   |
| OPNsense 22.1.8              | 2        | 1.25%   |
| OPNsense 21.1.9              | 2        | 1.25%   |
| OPNsense 21.1.6              | 2        | 1.25%   |
| OPNsense 20.7.7              | 2        | 1.25%   |
| OpenBSD 6.9                  | 2        | 1.25%   |
| FreeBSD 13.1                 | 2        | 1.25%   |
| FreeBSD 12.2-p2              | 2        | 1.25%   |
| FreeBSD 12.1-p5              | 2        | 1.25%   |
| pfSense 12.2-STABLE          | 1        | 0.63%   |
| OPNsense 22.7                | 1        | 0.63%   |
| OPNsense 22.1.9              | 1        | 0.63%   |
| OPNsense 22.1.7              | 1        | 0.63%   |
| OPNsense 22.1.3              | 1        | 0.63%   |
| OPNsense 22.1.2              | 1        | 0.63%   |
| OPNsense 21.1.8              | 1        | 0.63%   |
| OPNsense 20.7                | 1        | 0.63%   |
| NetBSD 9.99.94               | 1        | 0.63%   |
| helloSystem 0.7.0            | 1        | 0.63%   |
| helloSystem 0.6.0            | 1        | 0.63%   |
| helloSystem 0.5.0            | 1        | 0.63%   |
| HardenedBSD 13.0-STABLE-HBSD | 1        | 0.63%   |
| GhostBSD 21.08.27            | 1        | 0.63%   |
| GhostBSD 20.04.02            | 1        | 0.63%   |
| FreeBSD 14.0-CURRENT         | 1        | 0.63%   |
| FreeBSD 13.0-RC2             | 1        | 0.63%   |
| FreeBSD 13.0-p6              | 1        | 0.63%   |
| FreeBSD 13.0-p2              | 1        | 0.63%   |
| FreeBSD 13.0-p11             | 1        | 0.63%   |
| FreeBSD 13.0-p10             | 1        | 0.63%   |
| FreeBSD 12.2-p11             | 1        | 0.63%   |
| FreeBSD 12.2                 | 1        | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 75       | 65.22%  |
| FreeBSD     | 21       | 18.26%  |
| OpenBSD     | 11       | 9.57%   |
| helloSystem | 3        | 2.61%   |
| GhostBSD    | 2        | 1.74%   |
| pfSense     | 1        | 0.87%   |
| NetBSD      | 1        | 0.87%   |
| HardenedBSD | 1        | 0.87%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 106      | 94.64%  |
| arm64 | 5        | 4.46%   |
| i386  | 1        | 0.89%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 94       | 81.74%  |
| helloDesktop | 8        | 6.96%   |
| KDE5         | 5        | 4.35%   |
| GNOME        | 2        | 1.74%   |
| fvwm         | 2        | 1.74%   |
| XFCE         | 1        | 0.87%   |
| MATE         | 1        | 0.87%   |
| LXQt         | 1        | 0.87%   |
| i3           | 1        | 0.87%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 96       | 85.71%  |
| X11     | 15       | 13.39%  |
| Wayland | 1        | 0.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 99       | 87.61%  |
| SLiM    | 4        | 3.54%   |
| SDDM    | 4        | 3.54%   |
| LightDM | 3        | 2.65%   |
| GDM     | 2        | 1.77%   |
| XDM     | 1        | 0.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 91       | 78.45%  |
| C       | 13       | 11.21%  |
| en_US   | 11       | 9.48%   |
| nl_NL   | 1        | 0.86%   |

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


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 66       | 56.9%   |
| Zfs    | 38       | 32.76%  |
| Ffs    | 11       | 9.48%   |
| Cd9660 | 1        | 0.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 95       | 84.07%  |
| MBR  | 18       | 15.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 19       | 16.96%  |
| Dell                | 11       | 9.82%   |
| Hewlett-Packard     | 10       | 8.93%   |
| ASRock              | 10       | 8.93%   |
| Gigabyte Technology | 9        | 8.04%   |
| PC Engines          | 7        | 6.25%   |
| Intel               | 7        | 6.25%   |
| Supermicro          | 4        | 3.57%   |
| Shuttle             | 4        | 3.57%   |
| MSI                 | 4        | 3.57%   |
| ASUSTek Computer    | 4        | 3.57%   |
| Protectli           | 3        | 2.68%   |
| Inventec            | 3        | 2.68%   |
| Fujitsu             | 2        | 1.79%   |
| Deciso              | 2        | 1.79%   |
| XtReAmEr            | 1        | 0.89%   |
| Sapphire            | 1        | 0.89%   |
| Pegatron            | 1        | 0.89%   |
| MW                  | 1        | 0.89%   |
| Lenovo              | 1        | 0.89%   |
| iEi                 | 1        | 0.89%   |
| HPE                 | 1        | 0.89%   |
| HARDKERNEL          | 1        | 0.89%   |
| Dell EMC            | 1        | 0.89%   |
| Biostar             | 1        | 0.89%   |
| ASRockRack          | 1        | 0.89%   |
| AMI                 | 1        | 0.89%   |
| Alienware           | 1        | 0.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 20       | 17.86%  |
| Intel Q3XXG4-P V1.0                 | 5        | 4.46%   |
| Dell PowerEdge R620                 | 4        | 3.57%   |
| PC Engines apu4                     | 3        | 2.68%   |
| PC Engines APU2                     | 2        | 1.79%   |
| PC Engines APU                      | 2        | 1.79%   |
| Inventec VXC Class                  | 2        | 1.79%   |
| HP EliteDesk 800 G1 SFF             | 2        | 1.79%   |
| Gigabyte X570 AORUS PRO             | 2        | 1.79%   |
| Supermicro X9SCL/X9SCM              | 1        | 0.89%   |
| Supermicro X8SIL                    | 1        | 0.89%   |
| Supermicro AS -E301-9D-8CN4         | 1        | 0.89%   |
| Supermicro AS -5019D-FTN4           | 1        | 0.89%   |
| Shuttle XH310V2                     | 1        | 0.89%   |
| Shuttle SH87R                       | 1        | 0.89%   |
| Shuttle DH370                       | 1        | 0.89%   |
| Shuttle DH310                       | 1        | 0.89%   |
| Sapphire EDGE-FT1M1 E450 1AOVU044   | 1        | 0.89%   |
| Protectli FW6D                      | 1        | 0.89%   |
| Protectli FW4B                      | 1        | 0.89%   |
| Protectli FW2B                      | 1        | 0.89%   |
| Pegatron h8-1102nl                  | 1        | 0.89%   |
| MW GMLK-2_5G4L                      | 1        | 0.89%   |
| MSI MS-7C89                         | 1        | 0.89%   |
| MSI MS-7851                         | 1        | 0.89%   |
| MSI MS-7846                         | 1        | 0.89%   |
| MSI MS-7677                         | 1        | 0.89%   |
| Lenovo ThinkStation E31 255526G     | 1        | 0.89%   |
| Inventec R CLASS                    | 1        | 0.89%   |
| Intel SHARKBAY                      | 1        | 0.89%   |
| Intel CRESCENTBAY                   | 1        | 0.89%   |
| iEi E452                            | 1        | 0.89%   |
| HPE ProLiant MicroServer Gen10 Plus | 1        | 0.89%   |
| HP t620 PLUS Quad Core TC           | 1        | 0.89%   |
| HP ProLiant DL360 Gen9              | 1        | 0.89%   |
| HP ProDesk 400 G2.5 SFF             | 1        | 0.89%   |
| HP ProDesk 400 G1 SFF               | 1        | 0.89%   |
| HP EliteDesk 800 G5 SFF             | 1        | 0.89%   |
| HP Compaq Pro 6300 SFF              | 1        | 0.89%   |
| HP Compaq Elite 8300 SFF            | 1        | 0.89%   |
| HP Compaq 6200 Pro SFF PC           | 1        | 0.89%   |
| HARDKERNEL ODROID-H2                | 1        | 0.89%   |
| Gigabyte Z97-D3H                    | 1        | 0.89%   |
| Gigabyte Z68MA-D2H-B3               | 1        | 0.89%   |
| Gigabyte J1900N-D3V                 | 1        | 0.89%   |
| Gigabyte H310M S2H                  | 1        | 0.89%   |
| Gigabyte GB-BXi7-5500               | 1        | 0.89%   |
| Gigabyte B85-HD3                    | 1        | 0.89%   |
| Gigabyte B560M D3H                  | 1        | 0.89%   |
| Fujitsu FUTRO S920                  | 1        | 0.89%   |
| Fujitsu D3003-S2                    | 1        | 0.89%   |
| Dell Precision WorkStation T7500    | 1        | 0.89%   |
| Dell OptiPlex 9020                  | 1        | 0.89%   |
| Dell OptiPlex 780                   | 1        | 0.89%   |
| Dell OptiPlex 760                   | 1        | 0.89%   |
| Dell OptiPlex 7010                  | 1        | 0.89%   |
| Dell OptiPlex 5040                  | 1        | 0.89%   |
| Dell EMC VEP1425-V210               | 1        | 0.89%   |
| Dell DXP051                         | 1        | 0.89%   |
| Deciso Netboard A10 V2              | 1        | 0.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Unknown                 | 20       | 17.86%  |
| Intel Q3XXG4-P          | 5        | 4.46%   |
| Dell OptiPlex           | 5        | 4.46%   |
| Dell PowerEdge          | 4        | 3.57%   |
| PC Engines apu4         | 3        | 2.68%   |
| HP EliteDesk            | 3        | 2.68%   |
| HP Compaq               | 3        | 2.68%   |
| Supermicro AS           | 2        | 1.79%   |
| PC Engines APU2         | 2        | 1.79%   |
| PC Engines APU          | 2        | 1.79%   |
| Inventec VXC            | 2        | 1.79%   |
| HP ProDesk              | 2        | 1.79%   |
| Gigabyte X570           | 2        | 1.79%   |
| Deciso Netboard         | 2        | 1.79%   |
| ASUS PRIME              | 2        | 1.79%   |
| Supermicro X9SCL        | 1        | 0.89%   |
| Supermicro X8SIL        | 1        | 0.89%   |
| Shuttle XH310V2         | 1        | 0.89%   |
| Shuttle SH87R           | 1        | 0.89%   |
| Shuttle DH370           | 1        | 0.89%   |
| Shuttle DH310           | 1        | 0.89%   |
| Sapphire EDGE-FT1M1     | 1        | 0.89%   |
| Protectli FW6D          | 1        | 0.89%   |
| Protectli FW4B          | 1        | 0.89%   |
| Protectli FW2B          | 1        | 0.89%   |
| Pegatron h8-1102nl      | 1        | 0.89%   |
| MW GMLK-2               | 1        | 0.89%   |
| MSI MS-7C89             | 1        | 0.89%   |
| MSI MS-7851             | 1        | 0.89%   |
| MSI MS-7846             | 1        | 0.89%   |
| MSI MS-7677             | 1        | 0.89%   |
| Lenovo ThinkStation     | 1        | 0.89%   |
| Inventec R              | 1        | 0.89%   |
| Intel SHARKBAY          | 1        | 0.89%   |
| Intel CRESCENTBAY       | 1        | 0.89%   |
| iEi E452                | 1        | 0.89%   |
| HPE ProLiant            | 1        | 0.89%   |
| HP t620                 | 1        | 0.89%   |
| HP ProLiant             | 1        | 0.89%   |
| HARDKERNEL ODROID-H2    | 1        | 0.89%   |
| Gigabyte Z97-D3H        | 1        | 0.89%   |
| Gigabyte Z68MA-D2H-B3   | 1        | 0.89%   |
| Gigabyte J1900N-D3V     | 1        | 0.89%   |
| Gigabyte H310M          | 1        | 0.89%   |
| Gigabyte GB-BXi7-5500   | 1        | 0.89%   |
| Gigabyte B85-HD3        | 1        | 0.89%   |
| Gigabyte B560M          | 1        | 0.89%   |
| Fujitsu FUTRO           | 1        | 0.89%   |
| Fujitsu D3003-S2        | 1        | 0.89%   |
| Dell Precision          | 1        | 0.89%   |
| Dell EMC VEP1425-V210   | 1        | 0.89%   |
| Dell DXP051             | 1        | 0.89%   |
| Biostar H61MGV3         | 1        | 0.89%   |
| ASUS P5Q-PRO            | 1        | 0.89%   |
| ASUS H110I-PLUS         | 1        | 0.89%   |
| ASRockRack EPC612D4U-8R | 1        | 0.89%   |
| ASRock Z77              | 1        | 0.89%   |
| ASRock Z490M-ITX        | 1        | 0.89%   |
| ASRock Z490M            | 1        | 0.89%   |
| ASRock X300M-STX        | 1        | 0.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 16       | 14.29%  |
| 2020    | 15       | 13.39%  |
| 2019    | 12       | 10.71%  |
| 2016    | 12       | 10.71%  |
| 2014    | 12       | 10.71%  |
| 2013    | 8        | 7.14%   |
| 2021    | 7        | 6.25%   |
| 2011    | 7        | 6.25%   |
| 2015    | 5        | 4.46%   |
| Unknown | 5        | 4.46%   |
| 2017    | 4        | 3.57%   |
| 2009    | 4        | 3.57%   |
| 2012    | 3        | 2.68%   |
| 2010    | 1        | 0.89%   |
| 2006    | 1        | 0.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 112      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 102      | 91.07%  |
| Yes  | 10       | 8.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 38       | 33.63%  |
| 4.01-8.0        | 28       | 24.78%  |
| 16.01-24.0      | 19       | 16.81%  |
| 32.01-64.0      | 9        | 7.96%   |
| 64.01-256.0     | 6        | 5.31%   |
| 2.01-3.0        | 5        | 4.42%   |
| 3.01-4.0        | 3        | 2.65%   |
| 1.01-2.0        | 2        | 1.77%   |
| More than 256.0 | 1        | 0.88%   |
| 24.01-32.0      | 1        | 0.88%   |
| 0.51-1.0        | 1        | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 61       | 52.14%  |
| 0.51-1.0   | 32       | 27.35%  |
| 1.01-2.0   | 7        | 5.98%   |
| 4.01-8.0   | 6        | 5.13%   |
| 2.01-3.0   | 3        | 2.56%   |
| 8.01-16.0  | 3        | 2.56%   |
| 32.01-64.0 | 1        | 0.85%   |
| 3.01-4.0   | 1        | 0.85%   |
| 24.01-32.0 | 1        | 0.85%   |
| 0          | 1        | 0.85%   |
| Unknown    | 1        | 0.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 76       | 67.86%  |
| 2      | 15       | 13.39%  |
| 0      | 6        | 5.36%   |
| 4      | 4        | 3.57%   |
| 5      | 3        | 2.68%   |
| 3      | 3        | 2.68%   |
| 15     | 1        | 0.89%   |
| 12     | 1        | 0.89%   |
| 10     | 1        | 0.89%   |
| 7      | 1        | 0.89%   |
| 6      | 1        | 0.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 100      | 89.29%  |
| Yes       | 12       | 10.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 108      | 96.43%  |
| No        | 4        | 3.57%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 82.46%  |
| Yes       | 20       | 17.54%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 104      | 92.86%  |
| Yes       | 8        | 7.14%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Netherlands | 112      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Amsterdam               | 21       | 15.91%  |
| Rotterdam               | 4        | 3.03%   |
| Poortugaal              | 4        | 3.03%   |
| Ospel                   | 3        | 2.27%   |
| Groningen               | 3        | 2.27%   |
| Barneveld               | 3        | 2.27%   |
| Amersfoort              | 3        | 2.27%   |
| Zeist                   | 2        | 1.52%   |
| Zaandam                 | 2        | 1.52%   |
| Vlaardingen             | 2        | 1.52%   |
| Veenendaal              | 2        | 1.52%   |
| The Hague               | 2        | 1.52%   |
| Nieuwegein              | 2        | 1.52%   |
| Maastricht              | 2        | 1.52%   |
| IJsselstein             | 2        | 1.52%   |
| Hengelo                 | 2        | 1.52%   |
| Delft                   | 2        | 1.52%   |
| Breda                   | 2        | 1.52%   |
| Alphen aan den Rijn     | 2        | 1.52%   |
| Almere Stad             | 2        | 1.52%   |
| Almere Poort            | 2        | 1.52%   |
| Almelo                  | 2        | 1.52%   |
| Aalsmeer                | 2        | 1.52%   |
| Zutphen                 | 1        | 0.76%   |
| Zuidhorn                | 1        | 0.76%   |
| Zoetermeer              | 1        | 0.76%   |
| Zetten                  | 1        | 0.76%   |
| Zaltbommel              | 1        | 0.76%   |
| Wassenaar               | 1        | 0.76%   |
| Vleuten                 | 1        | 0.76%   |
| Valkenswaard            | 1        | 0.76%   |
| Utrecht                 | 1        | 0.76%   |
| Tilburg                 | 1        | 0.76%   |
| Tiel                    | 1        | 0.76%   |
| Ten Boer                | 1        | 0.76%   |
| Swalmen                 | 1        | 0.76%   |
| Steenbergen             | 1        | 0.76%   |
| Spaubeek                | 1        | 0.76%   |
| Soest                   | 1        | 0.76%   |
| Sneek                   | 1        | 0.76%   |
| Schalkhaar              | 1        | 0.76%   |
| Ruurlo                  | 1        | 0.76%   |
| Rozenburg               | 1        | 0.76%   |
| Ridderkerk              | 1        | 0.76%   |
| Pijnacker               | 1        | 0.76%   |
| Oudheusden              | 1        | 0.76%   |
| Ouderkerk aan de Amstel | 1        | 0.76%   |
| Oud Gastel              | 1        | 0.76%   |
| Nuenen                  | 1        | 0.76%   |
| Noordwijk aan Zee       | 1        | 0.76%   |
| Neede                   | 1        | 0.76%   |
| Naaldwijk               | 1        | 0.76%   |
| Marken                  | 1        | 0.76%   |
| Lopik                   | 1        | 0.76%   |
| Leiden                  | 1        | 0.76%   |
| Leersum                 | 1        | 0.76%   |
| Krommenie               | 1        | 0.76%   |
| Klazienaveen            | 1        | 0.76%   |
| Kampen                  | 1        | 0.76%   |
| Houten                  | 1        | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 24       | 34     | 18.05%  |
| Crucial             | 16       | 30     | 12.03%  |
| WDC                 | 15       | 51     | 11.28%  |
| Kingston            | 11       | 15     | 8.27%   |
| Transcend           | 8        | 12     | 6.02%   |
| Seagate             | 5        | 32     | 3.76%   |
| Hoodisk             | 5        | 8      | 3.76%   |
| HGST                | 4        | 6      | 3.01%   |
| Dell                | 4        | 8      | 3.01%   |
| Toshiba             | 3        | 13     | 2.26%   |
| SanDisk             | 3        | 3      | 2.26%   |
| LITEON              | 3        | 4      | 2.26%   |
| Intel               | 3        | 6      | 2.26%   |
| Hitachi             | 3        | 5      | 2.26%   |
| Hewlett-Packard     | 3        | 5      | 2.26%   |
| Gigabyte Technology | 3        | 3      | 2.26%   |
| FORESEE             | 3        | 6      | 2.26%   |
| China               | 3        | 7      | 2.26%   |
| Phison              | 2        | 2      | 1.5%    |
| Kston               | 2        | 5      | 1.5%    |
| StoreJet            | 1        | 1      | 0.75%   |
| Silicon Motion      | 1        | 1      | 0.75%   |
| Protectli           | 1        | 4      | 0.75%   |
| PNY                 | 1        | 1      | 0.75%   |
| ORICO               | 1        | 1      | 0.75%   |
| OCZ                 | 1        | 1      | 0.75%   |
| NVMe                | 1        | 1      | 0.75%   |
| NETAPP              | 1        | 4      | 0.75%   |
| Intenso             | 1        | 1      | 0.75%   |
| BAITITON            | 1        | 2      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB             | 6        | 4.05%   |
| Kingston SUV500MS120G 120GB           | 4        | 2.7%    |
| Hoodisk SSD 128GB                     | 4        | 2.7%    |
| Dell PERC H710 282GB                  | 4        | 2.7%    |
| Crucial CT250MX500SSD1 250GB          | 3        | 2.03%   |
| Crucial CT240BX500SSD1 240GB          | 3        | 2.03%   |
| WDC WD40EFRX-68WT0N0 4TB              | 2        | 1.35%   |
| WDC WD40EFRX-68N32N0 4TB              | 2        | 1.35%   |
| Transcend TS32GSSD370S 32GB           | 2        | 1.35%   |
| Samsung SSD 970 EVO 1TB               | 2        | 1.35%   |
| Samsung SSD 850 EVO 500GB             | 2        | 1.35%   |
| Samsung SSD 840 Series 120GB          | 2        | 1.35%   |
| LITEON CS1-SP16-11 M.2 2242 16GB      | 2        | 1.35%   |
| Kston SSD 128GB                       | 2        | 1.35%   |
| HGST HTS725050A7E630 500GB            | 2        | 1.35%   |
| Crucial M4-CT128M4SSD2 128GB          | 2        | 1.35%   |
| Crucial CT480M500SSD1 480GB           | 2        | 1.35%   |
| Crucial CT120BX500SSD1 120GB          | 2        | 1.35%   |
| China SATA SSD 16GB                   | 2        | 1.35%   |
| WDC WDS500G1X0E-00AFY0 500GB          | 1        | 0.68%   |
| WDC WDS240G2G0B-00EPW0 240GB          | 1        | 0.68%   |
| WDC WDS100T3X0C-00SJG0 1TB            | 1        | 0.68%   |
| WDC WD8003FFBX-68B9AN0 8TB            | 1        | 0.68%   |
| WDC WD7500AYYS-01RCA0 752GB           | 1        | 0.68%   |
| WDC WD60EFRX-68L0BN1 6TB              | 1        | 0.68%   |
| WDC WD5000AAKS-00A7B0 500GB           | 1        | 0.68%   |
| WDC WD5000AACS-00ZUB0 500GB           | 1        | 0.68%   |
| WDC WD4004FZWX-00GBGB0 4TB            | 1        | 0.68%   |
| WDC WD3200JS-22PDB0 320GB             | 1        | 0.68%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1        | 0.68%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 0.68%   |
| WDC WD10JFCX-68N6GN0 1TB              | 1        | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 0.68%   |
| WDC WD10EFRX-68PJCN0 1TB              | 1        | 0.68%   |
| WDC WD10EADS-00L5B1 1TB               | 1        | 0.68%   |
| Transcend TS64GMSA230S 64GB           | 1        | 0.68%   |
| Transcend TS256GMSA452T2 256GB        | 1        | 0.68%   |
| Transcend TS128GMTE110S 128GB         | 1        | 0.68%   |
| Transcend TS128GMSA230S 128GB         | 1        | 0.68%   |
| Transcend TS120GMTS420S 120GB         | 1        | 0.68%   |
| Transcend TS120GESD240C 120GB         | 1        | 0.68%   |
| Toshiba THNSNH256GMCT 256GB           | 1        | 0.68%   |
| Toshiba MQ04ABF100 1TB                | 1        | 0.68%   |
| Toshiba HDWN180 8TB                   | 1        | 0.68%   |
| StoreJet Transcend 120GB              | 1        | 0.68%   |
| Silicon Motion 512GB PCS PCIe M.2 SSD | 1        | 0.68%   |
| Seagate ST500LT012-9WS142 500GB       | 1        | 0.68%   |
| Seagate ST5000LM000-2U8170 5TB        | 1        | 0.68%   |
| Seagate ST5000LM000-2AN170 5TB        | 1        | 0.68%   |
| Seagate ST4000DM000-1F2168 4TB        | 1        | 0.68%   |
| Seagate ST3160812AS 160GB             | 1        | 0.68%   |
| Seagate ST3160318AS 160GB             | 1        | 0.68%   |
| SanDisk SDSSDA240G 240GB              | 1        | 0.68%   |
| SanDisk SDSA6MM-016G-1006 16GB        | 1        | 0.68%   |
| SanDisk Extreme Pro 128GB             | 1        | 0.68%   |
| Samsung SSD PM851 mSATA 256GB         | 1        | 0.68%   |
| Samsung SSD 980 PRO 1TB               | 1        | 0.68%   |
| Samsung SSD 870 EVO 1TB               | 1        | 0.68%   |
| Samsung SSD 860 QVO 2TB               | 1        | 0.68%   |
| Samsung SSD 860 EVO mSATA 250GB       | 1        | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 46     | 35%     |
| Seagate             | 5        | 32     | 12.5%   |
| Samsung Electronics | 4        | 7      | 10%     |
| HGST                | 4        | 6      | 10%     |
| Dell                | 4        | 8      | 10%     |
| Hitachi             | 3        | 5      | 7.5%    |
| Toshiba             | 2        | 10     | 5%      |
| Hewlett-Packard     | 2        | 4      | 5%      |
| StoreJet            | 1        | 1      | 2.5%    |
| NVMe                | 1        | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 19       | 21     | 22.62%  |
| Crucial             | 16       | 26     | 19.05%  |
| Kingston            | 8        | 12     | 9.52%   |
| Transcend           | 7        | 11     | 8.33%   |
| Hoodisk             | 5        | 8      | 5.95%   |
| SanDisk             | 3        | 3      | 3.57%   |
| LITEON              | 3        | 4      | 3.57%   |
| Intel               | 3        | 6      | 3.57%   |
| FORESEE             | 3        | 6      | 3.57%   |
| China               | 3        | 7      | 3.57%   |
| Phison              | 2        | 2      | 2.38%   |
| Kston               | 2        | 5      | 2.38%   |
| WDC                 | 1        | 2      | 1.19%   |
| Toshiba             | 1        | 3      | 1.19%   |
| Protectli           | 1        | 4      | 1.19%   |
| PNY                 | 1        | 1      | 1.19%   |
| ORICO               | 1        | 1      | 1.19%   |
| OCZ                 | 1        | 1      | 1.19%   |
| NETAPP              | 1        | 4      | 1.19%   |
| Intenso             | 1        | 1      | 1.19%   |
| Hewlett-Packard     | 1        | 1      | 1.19%   |
| BAITITON            | 1        | 2      | 1.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 78       | 131    | 62.9%   |
| HDD  | 34       | 120    | 27.42%  |
| NVMe | 12       | 21     | 9.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 99       | 251    | 89.19%  |
| NVMe | 12       | 21     | 10.81%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 91       | 154    | 77.12%  |
| 0.51-1.0   | 12       | 33     | 10.17%  |
| 3.01-4.0   | 7        | 18     | 5.93%   |
| 4.01-10.0  | 5        | 40     | 4.24%   |
| 1.01-2.0   | 3        | 6      | 2.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 49       | 42.24%  |
| 51-100         | 19       | 16.38%  |
| 251-500        | 14       | 12.07%  |
| 1-20           | 14       | 12.07%  |
| 21-50          | 7        | 6.03%   |
| 501-1000       | 5        | 4.31%   |
| 1001-2000      | 4        | 3.45%   |
| 2001-3000      | 2        | 1.72%   |
| More than 3000 | 1        | 0.86%   |
| Unknown        | 1        | 0.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 98       | 85.96%  |
| 21-50    | 5        | 4.39%   |
| 101-250  | 3        | 2.63%   |
| 51-100   | 3        | 2.63%   |
| 251-500  | 2        | 1.75%   |
| 501-1000 | 2        | 1.75%   |
| Unknown  | 1        | 0.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Desktops | Drives | Percent |
|-------------------------------------------|----------|--------|---------|
| Crucial CT480M500SSD1 480GB               | 2        | 3      | 10.53%  |
| Seagate ST500LT012-9WS142 500GB           | 1        | 2      | 5.26%   |
| Seagate ST3160318AS 160GB                 | 1        | 3      | 5.26%   |
| Samsung Electronics SSD 870 EVO 1TB       | 1        | 1      | 5.26%   |
| Samsung Electronics SSD 850 EVO mSATA 1TB | 1        | 1      | 5.26%   |
| Samsung Electronics SSD 850 EVO 1TB       | 1        | 1      | 5.26%   |
| Samsung Electronics SSD 840 Series 120GB  | 1        | 1      | 5.26%   |
| Samsung Electronics SSD 840 EVO 120GB     | 1        | 1      | 5.26%   |
| Samsung Electronics HD322HJ 320GB         | 1        | 1      | 5.26%   |
| Samsung Electronics HD103SJ 1TB           | 1        | 2      | 5.26%   |
| Kingston SMS200S3120G 120GB               | 1        | 1      | 5.26%   |
| Intel SSDSC2BA200G3T 200GB                | 1        | 4      | 5.26%   |
| Hitachi HTS543232A7A384 320GB             | 1        | 1      | 5.26%   |
| Hitachi HDS723015BLA642 1.5TB             | 1        | 3      | 5.26%   |
| HGST HTS725050A7E630 500GB                | 1        | 1      | 5.26%   |
| HGST HDN726060ALE614 6TB                  | 1        | 2      | 5.26%   |
| Hewlett-Packard FB160C4081 160GB          | 1        | 2      | 5.26%   |
| Crucial CT128MX100SSD1 128GB              | 1        | 2      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 8      | 33.33%  |
| Crucial             | 3        | 5      | 16.67%  |
| Seagate             | 2        | 5      | 11.11%  |
| Hitachi             | 2        | 4      | 11.11%  |
| HGST                | 2        | 3      | 11.11%  |
| Kingston            | 1        | 1      | 5.56%   |
| Intel               | 1        | 4      | 5.56%   |
| Hewlett-Packard     | 1        | 2      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 5      | 22.22%  |
| Samsung Electronics | 2        | 3      | 22.22%  |
| Hitachi             | 2        | 4      | 22.22%  |
| HGST                | 2        | 3      | 22.22%  |
| Hewlett-Packard     | 1        | 2      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 17     | 52.94%  |
| SSD  | 8        | 15     | 47.06%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 92       | 231    | 80.7%   |
| Malfunc  | 17       | 32     | 14.91%  |
| Detected | 5        | 9      | 4.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 82       | 61.65%  |
| AMD                         | 22       | 16.54%  |
| Broadcom / LSI              | 6        | 4.51%   |
| Phison Electronics          | 5        | 3.76%   |
| ASMedia Technology          | 5        | 3.76%   |
| Samsung Electronics         | 4        | 3.01%   |
| Kingston Technology Company | 2        | 1.5%    |
| Silicon Motion              | 1        | 0.75%   |
| SanDisk                     | 1        | 0.75%   |
| Micron/Crucial Technology   | 1        | 0.75%   |
| Marvell Technology Group    | 1        | 0.75%   |
| JMicron Technology          | 1        | 0.75%   |
| Hewlett-Packard             | 1        | 0.75%   |
| Chelsio Communications      | 1        | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 13       | 9.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10       | 7.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7        | 4.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 7        | 4.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6        | 4.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 6        | 4.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6        | 4.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6        | 4.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5        | 3.55%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 4        | 2.84%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4        | 2.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3        | 2.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3        | 2.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3        | 2.13%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 3        | 2.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3        | 2.13%   |
| Phison PS5013 E13 NVMe Controller                                                | 2        | 1.42%   |
| Intel SATA Controller [RAID mode]                                                | 2        | 1.42%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2        | 1.42%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2        | 1.42%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2        | 1.42%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 2        | 1.42%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2        | 1.42%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2        | 1.42%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1        | 0.71%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1        | 0.71%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1        | 0.71%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1        | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1        | 0.71%   |
| Phison NVMe Storage Controller                                                   | 1        | 0.71%   |
| Phison E7 NVMe Controller                                                        | 1        | 0.71%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1        | 0.71%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1        | 0.71%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1        | 0.71%   |
| Kingston Company A2000 NVMe SSD                                                  | 1        | 0.71%   |
| JMicron JMB360 AHCI Controller                                                   | 1        | 0.71%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1        | 0.71%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 1        | 0.71%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1        | 0.71%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1        | 0.71%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 1        | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1        | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1        | 0.71%   |
| Intel 82801GR/GDH (ICH7R/ICH7DH) SATA Controller [RAID mode]                     | 1        | 0.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1        | 0.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1        | 0.71%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 1        | 0.71%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1        | 0.71%   |
| HP Smart Array Gen9 Controllers                                                  | 1        | 0.71%   |
| Chelsio T520-CR Unified Wire Storage Controller                                  | 1        | 0.71%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                              | 1        | 0.71%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 1        | 0.71%   |
| ASMedia ASM1166 Serial ATA Controller                                            | 1        | 0.71%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1        | 0.71%   |
| AMD SB600 IDE                                                                    | 1        | 0.71%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1        | 0.71%   |
| AMD 500 Series Chipset SATA Controller                                           | 1        | 0.71%   |
| AMD 400 Series Chipset SATA Controller                                           | 1        | 0.71%   |
| Unknown                                                                          | 1        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 100      | 78.13%  |
| NVMe | 13       | 10.16%  |
| RAID | 8        | 6.25%   |
| IDE  | 4        | 3.13%   |
| SAS  | 2        | 1.56%   |
| SCSI | 1        | 0.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 83       | 74.11%  |
| AMD    | 24       | 21.43%  |
| ARM    | 5        | 4.46%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz      | 5        | 4.46%   |
| AMD GX-412TC SOC                       | 5        | 4.46%   |
| ARM Cortex-A72 r0p3                    | 3        | 2.68%   |
| AMD G-T56N Processor                   | 3        | 2.68%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz     | 2        | 1.79%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 2        | 1.79%   |
| Intel Core i5-8600 CPU @ 3.10GHz       | 2        | 1.79%   |
| Intel Core i5-5250U CPU @ 1.60GHz      | 2        | 1.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 2        | 1.79%   |
| Intel Core i5-4690 CPU @ 3.50GHz       | 2        | 1.79%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 2        | 1.79%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 2        | 1.79%   |
| Intel Core i5-10400 CPU @ 2.90GHz      | 2        | 1.79%   |
| Intel Core 2 Duo                       | 2        | 1.79%   |
| Intel Celeron CPU J1900 @ 1.99GHz      | 2        | 1.79%   |
| ARM Cortex-A53 r0p4                    | 2        | 1.79%   |
| AMD G-T40E Processor                   | 2        | 1.79%   |
| AMD EPYC 3251 8-Core Processor         | 2        | 1.79%   |
| Intel Xeon E-2224 CPU @ 3.40GHz        | 1        | 0.89%   |
| Intel Xeon CPU X5680 @ 3.33GHz         | 1        | 0.89%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz     | 1        | 0.89%   |
| Intel Xeon CPU E5-2650L v3 @ 1.80GHz   | 1        | 0.89%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz     | 1        | 0.89%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz    | 1        | 0.89%   |
| Intel Xeon CPU E31270 @ 3.40GHz        | 1        | 0.89%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz    | 1        | 0.89%   |
| Intel Pentium Gold G6500 CPU @ 4.10GHz | 1        | 0.89%   |
| Intel Pentium Gold G5600 CPU @ 3.90GHz | 1        | 0.89%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz | 1        | 0.89%   |
| Intel Pentium CPU G4560 @ 3.50GHz      | 1        | 0.89%   |
| Intel Pentium CPU G3220 @ 3.00GHz      | 1        | 0.89%   |
| Intel Pentium CPU 5405U @ 2.30GHz      | 1        | 0.89%   |
| Intel Pentium 4                        | 1        | 0.89%   |
| Intel Core i7-6700TE CPU @ 2.40GHz     | 1        | 0.89%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 1        | 0.89%   |
| Intel Core i7-5550U CPU @ 2.00GHz      | 1        | 0.89%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1        | 0.89%   |
| Intel Core i7-4770T CPU @ 2.50GHz      | 1        | 0.89%   |
| Intel Core i7-4500U CPU @ 1.80GHz      | 1        | 0.89%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 1        | 0.89%   |
| Intel Core i5-9500 CPU @ 3.00GHz       | 1        | 0.89%   |
| Intel Core i5-8365U CPU @ 1.60GHz      | 1        | 0.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 1        | 0.89%   |
| Intel Core i5-7300U CPU @ 2.60GHz      | 1        | 0.89%   |
| Intel Core i5-7267U CPU @ 3.10GHz      | 1        | 0.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 1        | 0.89%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 1        | 0.89%   |
| Intel Core i5-6200U CPU @ 2.30GHz      | 1        | 0.89%   |
| Intel Core i5-4590S CPU @ 3.00GHz      | 1        | 0.89%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 1        | 0.89%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 1        | 0.89%   |
| Intel Core i5-4440 CPU @ 3.10GHz       | 1        | 0.89%   |
| Intel Core i5-3570K CPU @ 3.40GHz      | 1        | 0.89%   |
| Intel Core i5-3550 CPU @ 3.30GHz       | 1        | 0.89%   |
| Intel Core i5-2320 CPU @ 3.00GHz       | 1        | 0.89%   |
| Intel Core i5-10600K CPU @ 4.10GHz     | 1        | 0.89%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 1        | 0.89%   |
| Intel Core i3-9100 CPU @ 3.60GHz       | 1        | 0.89%   |
| Intel Core i3-3240 CPU @ 3.40GHz       | 1        | 0.89%   |
| Intel Core i3-3225 CPU @ 3.30GHz       | 1        | 0.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 31       | 27.68%  |
| Intel Celeron      | 14       | 12.5%   |
| Intel Xeon         | 10       | 8.93%   |
| AMD GX             | 10       | 8.93%   |
| Intel Core i7      | 9        | 8.04%   |
| ARM Cortex         | 5        | 4.46%   |
| AMD G              | 5        | 4.46%   |
| Intel Core i3      | 4        | 3.57%   |
| Intel Atom         | 4        | 3.57%   |
| Intel Pentium Gold | 3        | 2.68%   |
| Intel Pentium      | 3        | 2.68%   |
| Intel Core 2 Duo   | 3        | 2.68%   |
| Other              | 2        | 1.79%   |
| AMD Ryzen 5        | 2        | 1.79%   |
| AMD EPYC           | 2        | 1.79%   |
| Intel Pentium 4    | 1        | 0.89%   |
| AMD Ryzen 9        | 1        | 0.89%   |
| AMD Ryzen 7 PRO    | 1        | 0.89%   |
| AMD Ryzen 7        | 1        | 0.89%   |
| AMD E              | 1        | 0.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 47       | 41.96%  |
| 2       | 35       | 31.25%  |
| 6       | 9        | 8.04%   |
| 12      | 6        | 5.36%   |
| Unknown | 6        | 5.36%   |
| 8       | 4        | 3.57%   |
| 16      | 3        | 2.68%   |
| 1       | 2        | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 104      | 92.86%  |
| Unknown | 5        | 4.46%   |
| 2       | 3        | 2.68%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 63       | 56.25%  |
| 2       | 43       | 38.39%  |
| Unknown | 6        | 5.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 16       | 14.29%  |
| Haswell       | 14       | 12.5%   |
| Silvermont    | 9        | 8.04%   |
| SandyBridge   | 9        | 8.04%   |
| IvyBridge     | 7        | 6.25%   |
| Puma          | 6        | 5.36%   |
| Broadwell     | 6        | 5.36%   |
| Bobcat        | 6        | 5.36%   |
| Unknown       | 6        | 5.36%   |
| CometLake     | 5        | 4.46%   |
| Skylake       | 4        | 3.57%   |
| Jaguar        | 4        | 3.57%   |
| Zen 2         | 3        | 2.68%   |
| Zen           | 3        | 2.68%   |
| Penryn        | 3        | 2.68%   |
| Goldmont plus | 3        | 2.68%   |
| Westmere      | 2        | 1.79%   |
| Bonnell       | 2        | 1.79%   |
| Zen 3         | 1        | 0.89%   |
| NetBurst      | 1        | 0.89%   |
| K8 Hammer     | 1        | 0.89%   |
| Goldmont      | 1        | 0.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 62       | 63.27%  |
| AMD                        | 15       | 15.31%  |
| Nvidia                     | 10       | 10.2%   |
| Matrox Electronics Systems | 8        | 8.16%   |
| ASPEED Technology          | 3        | 3.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8        | 8.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6        | 6.12%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 5.1%    |
| Matrox Electronics Systems G200eR2                                                       | 4        | 4.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4        | 4.08%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4        | 4.08%   |
| Intel HD Graphics 6000                                                                   | 3        | 3.06%   |
| Intel HD Graphics 5500                                                                   | 3        | 3.06%   |
| Intel HD Graphics 530                                                                    | 3        | 3.06%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 3.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 3.06%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 3        | 3.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3        | 3.06%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2        | 2.04%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2        | 2.04%   |
| Intel HD Graphics 620                                                                    | 2        | 2.04%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 2.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 2.04%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2        | 2.04%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2        | 2.04%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 1.02%   |
| Nvidia GT218 [ION]                                                                       | 1        | 1.02%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 1.02%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 1.02%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1        | 1.02%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 1.02%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.02%   |
| Nvidia GF108 [GeForce GT 530]                                                            | 1        | 1.02%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 1        | 1.02%   |
| Nvidia G72 [GeForce 7300 LE]                                                             | 1        | 1.02%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1        | 1.02%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 1.02%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1        | 1.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1        | 1.02%   |
| Intel UHD Graphics 620                                                                   | 1        | 1.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1        | 1.02%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 1.02%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.02%   |
| Intel Iris Plus Graphics 650                                                             | 1        | 1.02%   |
| Intel HD Graphics 610                                                                    | 1        | 1.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1        | 1.02%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 1        | 1.02%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                            | 1        | 1.02%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 1.02%   |
| AMD RS690 [Radeon X1200]                                                                 | 1        | 1.02%   |
| AMD Renoir                                                                               | 1        | 1.02%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.02%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1        | 1.02%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 1        | 1.02%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 1        | 1.02%   |
| AMD Cezanne                                                                              | 1        | 1.02%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 1.02%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 57       | 50.89%  |
| Other          | 16       | 14.29%  |
| 1 x AMD        | 15       | 13.39%  |
| 1 x Nvidia     | 8        | 7.14%   |
| 1 x Matrox     | 8        | 7.14%   |
| 2 x Intel      | 3        | 2.68%   |
| 1 x ASPEED     | 3        | 2.68%   |
| Intel + Nvidia | 2        | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 90       | 80.36%  |
| Unknown     | 17       | 15.18%  |
| Proprietary | 5        | 4.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 104      | 92.04%  |
| 1.01-2.0   | 4        | 3.54%   |
| 7.01-8.0   | 3        | 2.65%   |
| 3.01-4.0   | 1        | 0.88%   |
| 0.01-0.5   | 1        | 0.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Iiyama              | 4        | 26.67%  |
| Samsung Electronics | 3        | 20%     |
| Goldstar            | 2        | 13.33%  |
| Dell                | 2        | 13.33%  |
| ViewSonic           | 1        | 6.67%   |
| Sony                | 1        | 6.67%   |
| Philips             | 1        | 6.67%   |
| ASUSTek Computer    | 1        | 6.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ViewSonic LCD Monitor VX3276-QHD 2560x1440                           | 1        | 6.67%   |
| Sony TV SNYC901 1920x1080                                            | 1        | 6.67%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 470x300mm 22.0-inch | 1        | 6.67%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch | 1        | 6.67%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 530x300mm 24.0-inch    | 1        | 6.67%   |
| Philips PHL 328E1 PHLC204 3840x2160 700x390mm 31.5-inch              | 1        | 6.67%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch              | 1        | 6.67%   |
| Iiyama PL2740HS IVM6662 1920x1080 600x340mm 27.2-inch                | 1        | 6.67%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                 | 1        | 6.67%   |
| Iiyama PL2209HD IVM560B 1920x1080 480x270mm 21.7-inch                | 1        | 6.67%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch          | 1        | 6.67%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 1        | 6.67%   |
| Dell UP2716D DEL40DD 2560x1440 600x340mm 27.2-inch                   | 1        | 6.67%   |
| Dell U2715H DELD065 2560x1440 600x340mm 27.2-inch                    | 1        | 6.67%   |
| ASUSTek Computer VG259 AUS25A6 1920x1080 540x300mm 24.3-inch         | 1        | 6.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 6        | 40%     |
| 2560x1440 (QHD)    | 4        | 26.67%  |
| 3840x2160 (4K)     | 2        | 13.33%  |
| 3440x1440          | 1        | 6.67%   |
| 1680x1050 (WSXGA+) | 1        | 6.67%   |
| 1600x1200          | 1        | 6.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 4        | 26.67%  |
| 24      | 3        | 20%     |
| Unknown | 2        | 13.33%  |
| 34      | 1        | 6.67%   |
| 31      | 1        | 6.67%   |
| 23      | 1        | 6.67%   |
| 22      | 1        | 6.67%   |
| 21      | 1        | 6.67%   |
| 20      | 1        | 6.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 8        | 53.33%  |
| 401-500     | 3        | 20%     |
| Unknown     | 2        | 13.33%  |
| 701-800     | 1        | 6.67%   |
| 601-700     | 1        | 6.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 11       | 73.33%  |
| 4/3     | 1        | 6.67%   |
| 21/9    | 1        | 6.67%   |
| 16/10   | 1        | 6.67%   |
| Unknown | 1        | 6.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 5        | 33.33%  |
| 301-350        | 4        | 26.67%  |
| 351-500        | 2        | 13.33%  |
| Unknown        | 2        | 13.33%  |
| 251-300        | 1        | 6.67%   |
| 151-200        | 1        | 6.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 6        | 40%     |
| 101-120 | 4        | 26.67%  |
| 121-160 | 2        | 13.33%  |
| Unknown | 2        | 13.33%  |
| 161-240 | 1        | 6.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 97       | 86.61%  |
| 1     | 15       | 13.39%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 92       | 63.01%  |
| Realtek Semiconductor    | 33       | 22.6%   |
| Qualcomm Atheros         | 7        | 4.79%   |
| Broadcom                 | 4        | 2.74%   |
| IMC Networks             | 3        | 2.05%   |
| Ralink Technology        | 1        | 0.68%   |
| Ralink                   | 1        | 0.68%   |
| Marvell Technology Group | 1        | 0.68%   |
| Hewlett-Packard          | 1        | 0.68%   |
| Edimax Technology        | 1        | 0.68%   |
| Chelsio Communications   | 1        | 0.68%   |
| ADMtek                   | 1        | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 29       | 16.96%  |
| Intel I211 Gigabit Network Connection                                          | 22       | 12.87%  |
| Intel I350 Gigabit Network Connection                                          | 15       | 8.77%   |
| Intel I210 Gigabit Network Connection                                          | 15       | 8.77%   |
| Intel 82574L Gigabit Network Connection                                        | 11       | 6.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6        | 3.51%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 4        | 2.34%   |
| Intel Wi-Fi 6 AX200                                                            | 3        | 1.75%   |
| Intel Ethernet Connection I217-LM                                              | 3        | 1.75%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                | 2        | 1.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 2        | 1.17%   |
| Intel Ethernet Controller I225-V                                               | 2        | 1.17%   |
| Intel Ethernet Connection (2) I219-V                                           | 2        | 1.17%   |
| Intel Ethernet Connection (14) I219-V                                          | 2        | 1.17%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 2        | 1.17%   |
| Intel 82583V Gigabit Network Connection                                        | 2        | 1.17%   |
| Intel 82575GB Gigabit Network Connection                                       | 2        | 1.17%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                             | 2        | 1.17%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2        | 1.17%   |
| Intel 82541PI Gigabit Ethernet Controller                                      | 2        | 1.17%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                           | 2        | 1.17%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 2        | 1.17%   |
| Realtek RTL8192SU 802.11n WLAN Adapter                                         | 1        | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1        | 0.58%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1        | 0.58%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.58%   |
| Ralink RT5370 Wireless Adapter                                                 | 1        | 0.58%   |
| Ralink RT2500 Wireless 802.11bg                                                | 1        | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1        | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 0.58%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.58%   |
| Intel Wireless 3165                                                            | 1        | 0.58%   |
| Intel Wireless 3160                                                            | 1        | 0.58%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                        | 1        | 0.58%   |
| Intel Gemini Lake PCH CNVi WiFi                                                | 1        | 0.58%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1        | 0.58%   |
| Intel Ethernet Connection X553 1GbE                                            | 1        | 0.58%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                     | 1        | 0.58%   |
| Intel Ethernet Connection I217-V                                               | 1        | 0.58%   |
| Intel Ethernet Connection (7) I219-V                                           | 1        | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.58%   |
| Intel Ethernet Connection (12) I219-V                                          | 1        | 0.58%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 1        | 0.58%   |
| Intel 82580 Gigabit Network Connection                                         | 1        | 0.58%   |
| Intel 82576 Gigabit Network Connection                                         | 1        | 0.58%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1        | 0.58%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                     | 1        | 0.58%   |
| Intel 82567V-3 Gigabit Network Connection                                      | 1        | 0.58%   |
| Intel 82545GM Gigabit Ethernet Controller                                      | 1        | 0.58%   |
| Intel 82541GI Gigabit Ethernet Controller                                      | 1        | 0.58%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter    | 1        | 0.58%   |
| HP Virtual NIC                                                                 | 1        | 0.58%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                 | 1        | 0.58%   |
| Chelsio T520-CR Unified Wire Ethernet Controller                               | 1        | 0.58%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1        | 0.58%   |
| Broadcom BCM43228 802.11a/b/g/n                                                | 1        | 0.58%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100                           | 1        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 38.1%   |
| Qualcomm Atheros      | 4        | 19.05%  |
| IMC Networks          | 3        | 14.29%  |
| Realtek Semiconductor | 2        | 9.52%   |
| Ralink Technology     | 1        | 4.76%   |
| Ralink                | 1        | 4.76%   |
| Edimax Technology     | 1        | 4.76%   |
| Broadcom              | 1        | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                         | 3        | 14.29%  |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter             | 2        | 9.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 2        | 9.52%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                        | 2        | 9.52%   |
| Realtek RTL8192SU 802.11n WLAN Adapter                                      | 1        | 4.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1        | 4.76%   |
| Ralink RT5370 Wireless Adapter                                              | 1        | 4.76%   |
| Ralink RT2500 Wireless 802.11bg                                             | 1        | 4.76%   |
| Intel Wireless 3165                                                         | 1        | 4.76%   |
| Intel Wireless 3160                                                         | 1        | 4.76%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 1        | 4.76%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1        | 4.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 1        | 4.76%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1        | 4.76%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 1        | 4.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1        | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 88       | 68.75%  |
| Realtek Semiconductor    | 31       | 24.22%  |
| Qualcomm Atheros         | 3        | 2.34%   |
| Broadcom                 | 3        | 2.34%   |
| Marvell Technology Group | 1        | 0.78%   |
| Chelsio Communications   | 1        | 0.78%   |
| ADMtek                   | 1        | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 29       | 19.46%  |
| Intel I211 Gigabit Network Connection                                          | 22       | 14.77%  |
| Intel I350 Gigabit Network Connection                                          | 15       | 10.07%  |
| Intel I210 Gigabit Network Connection                                          | 15       | 10.07%  |
| Intel 82574L Gigabit Network Connection                                        | 11       | 7.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6        | 4.03%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 4        | 2.68%   |
| Intel Ethernet Connection I217-LM                                              | 3        | 2.01%   |
| Intel Ethernet Controller I225-V                                               | 2        | 1.34%   |
| Intel Ethernet Connection (2) I219-V                                           | 2        | 1.34%   |
| Intel Ethernet Connection (14) I219-V                                          | 2        | 1.34%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 2        | 1.34%   |
| Intel 82583V Gigabit Network Connection                                        | 2        | 1.34%   |
| Intel 82575GB Gigabit Network Connection                                       | 2        | 1.34%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                             | 2        | 1.34%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2        | 1.34%   |
| Intel 82541PI Gigabit Ethernet Controller                                      | 2        | 1.34%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 2        | 1.34%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1        | 0.67%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1        | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1        | 0.67%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 0.67%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.67%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1        | 0.67%   |
| Intel Ethernet Connection X553 1GbE                                            | 1        | 0.67%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                     | 1        | 0.67%   |
| Intel Ethernet Connection I217-V                                               | 1        | 0.67%   |
| Intel Ethernet Connection (7) I219-V                                           | 1        | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.67%   |
| Intel Ethernet Connection (12) I219-V                                          | 1        | 0.67%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.67%   |
| Intel 82580 Gigabit Network Connection                                         | 1        | 0.67%   |
| Intel 82576 Gigabit Network Connection                                         | 1        | 0.67%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1        | 0.67%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                     | 1        | 0.67%   |
| Intel 82567V-3 Gigabit Network Connection                                      | 1        | 0.67%   |
| Intel 82545GM Gigabit Ethernet Controller                                      | 1        | 0.67%   |
| Intel 82541GI Gigabit Ethernet Controller                                      | 1        | 0.67%   |
| Chelsio T520-CR Unified Wire Ethernet Controller                               | 1        | 0.67%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1        | 0.67%   |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100                           | 1        | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 108      | 83.72%  |
| WiFi     | 20       | 15.5%   |
| Unknown  | 1        | 0.78%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 102      | 96.23%  |
| WiFi     | 4        | 3.77%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 29       | 25.66%  |
| 2     | 29       | 25.66%  |
| 1     | 17       | 15.04%  |
| 3     | 11       | 9.73%   |
| 6     | 10       | 8.85%   |
| 5     | 9        | 7.96%   |
| 0     | 4        | 3.54%   |
| 9     | 2        | 1.77%   |
| 12    | 1        | 0.88%   |
| 8     | 1        | 0.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 99       | 84.62%  |
| Yes  | 18       | 15.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 66.67%  |
| Cambridge Silicon Radio | 2        | 22.22%  |
| TP-Link                 | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 3        | 33.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 22.22%  |
| TP-Link TP-Link UB500 Adapter                       | 1        | 11.11%  |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 11.11%  |
| Intel Bluetooth wireless interface                  | 1        | 11.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 61       | 67.78%  |
| AMD                         | 17       | 18.89%  |
| Nvidia                      | 8        | 8.89%   |
| VIA Technologies            | 1        | 1.11%   |
| Steinberg Soft-und Hardware | 1        | 1.11%   |
| Creative Labs               | 1        | 1.11%   |
| Corsair                     | 1        | 1.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8        | 7.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7        | 6.31%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6        | 5.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6        | 5.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5        | 4.5%    |
| Intel Broadwell-U Audio Controller                                                                | 5        | 4.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5        | 4.5%    |
| Intel Cannon Lake PCH cAVS                                                                        | 4        | 3.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4        | 3.6%    |
| AMD Wrestler HDMI Audio                                                                           | 4        | 3.6%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4        | 3.6%    |
| AMD FCH Azalia Controller                                                                         | 4        | 3.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3        | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3        | 2.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3        | 2.7%    |
| AMD Kabini HDMI/DP Audio                                                                          | 3        | 2.7%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 2.7%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3        | 2.7%    |
| Nvidia High Definition Audio Controller                                                           | 2        | 1.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2        | 1.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2        | 1.8%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 1.8%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 2        | 1.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 1.8%    |
| VIA Technologies USB Audio Device                                                                 | 1        | 0.9%    |
| Steinberg Soft-und Hardware MI4                                                                   | 1        | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1        | 0.9%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 1        | 0.9%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 0.9%    |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 0.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 1        | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1        | 0.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 0.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 1        | 0.9%    |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 0.9%    |
| Intel Comet Lake PCH cAVS                                                                         | 1        | 0.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1        | 0.9%    |
| Intel 8 Series HD Audio Controller                                                                | 1        | 0.9%    |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 1        | 0.9%    |
| Corsair Corsair VOID PRO Wireless Gaming Headset                                                  | 1        | 0.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1        | 0.9%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1        | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 21       | 20.79%  |
| Unknown             | 13       | 12.87%  |
| Samsung Electronics | 13       | 12.87%  |
| Corsair             | 13       | 12.87%  |
| Crucial             | 8        | 7.92%   |
| SK hynix            | 7        | 6.93%   |
| Micron Technology   | 7        | 6.93%   |
| Transcend           | 3        | 2.97%   |
| Kimtigo             | 3        | 2.97%   |
| Nanya Technology    | 2        | 1.98%   |
| G.Skill             | 2        | 1.98%   |
| Apacer              | 2        | 1.98%   |
| Unknown (ABCD)      | 1        | 0.99%   |
| Unknown (07FB)      | 1        | 0.99%   |
| Tigo                | 1        | 0.99%   |
| Team                | 1        | 0.99%   |
| Ramaxel Technology  | 1        | 0.99%   |
| Patriot             | 1        | 0.99%   |
| HPE                 | 1        | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 4        | 3.67%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s             | 3        | 2.75%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                          | 2        | 1.83%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s              | 2        | 1.83%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s               | 2        | 1.83%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 2        | 1.83%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s               | 2        | 1.83%   |
| Corsair RAM CMSO8GX4M1A2133C15 8GB SODIMM DDR4 2133MT/s           | 2        | 1.83%   |
| Apacer RAM 37352E4138334331 2GB SODIMM DDR3 1333MT/s              | 2        | 1.83%   |
| Unknown RAM WPBS16D308SWD-4G 4GB DIMM DDR3 1600MT/s               | 1        | 0.92%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                       | 1        | 0.92%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                         | 1        | 0.92%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1        | 0.92%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 1        | 0.92%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                        | 1        | 0.92%   |
| Unknown RAM Module 2GB DIMM DDR2                                  | 1        | 0.92%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                          | 1        | 0.92%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1        | 0.92%   |
| Unknown (07FB) RAM GSA8G4SCL156P-21 8GB SODIMM DDR4 2133MT/s      | 1        | 0.92%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s               | 1        | 0.92%   |
| Transcend RAM JM1600KLN-4G 4GB DIMM DDR3 1600MT/s                 | 1        | 0.92%   |
| Transcend RAM JM1333KSN-4G 4GB DIMM DDR3 1333MT/s                 | 1        | 0.92%   |
| Tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s                      | 1        | 0.92%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 2400MT/s              | 1        | 0.92%   |
| SK hynix RAM Module 8GB DIMM DDR3 1600MT/s                        | 1        | 0.92%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1        | 0.92%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s              | 1        | 0.92%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1        | 0.92%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 1        | 0.92%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                         | 1        | 0.92%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 1        | 0.92%   |
| Samsung RAM M471B5173EB0-YK0 4GB DIMM DDR3 1600MT/s               | 1        | 0.92%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 1        | 0.92%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s               | 1        | 0.92%   |
| Samsung RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1333MT/s               | 1        | 0.92%   |
| Samsung RAM M378A1K43BB1-CPB 8GB DIMM DDR4 3000MT/s               | 1        | 0.92%   |
| Ramaxel RAM RMR1810EC58E8F1333 2GB DIMM DDR3 1067MT/s             | 1        | 0.92%   |
| Patriot RAM PSD48G213381S 8GB SODIMM DDR4 2133MT/s                | 1        | 0.92%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 800MT/s                 | 1        | 0.92%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4GB DIMM DDR3 1333MT/s                | 1        | 0.92%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                          | 1        | 0.92%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 1        | 0.92%   |
| Micron RAM 8ATF1G64HZ-2G6J1 8GB SODIMM DDR4 2667MT/s              | 1        | 0.92%   |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s              | 1        | 0.92%   |
| Micron RAM 16JTF25664AZ-1G4G1 2GB DIMM DDR3 1067MT/s              | 1        | 0.92%   |
| Micron RAM 16JTF25664AZ-1G1F1 2GB DIMM DDR3 1067MT/s              | 1        | 0.92%   |
| Micron RAM 16HTF12864AY-53ED4 1GB DIMM DDR 533MT/s                | 1        | 0.92%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s               | 1        | 0.92%   |
| Kingston RAM KP4T2F-PSB 4GB DIMM DDR3 1600MT/s                    | 1        | 0.92%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s            | 1        | 0.92%   |
| Kingston RAM KHX16LC9/8GX 8GB DIMM DDR3 1600MT/s                  | 1        | 0.92%   |
| Kingston RAM KHX1600C9S3L/4G 4GB SODIMM DDR3 1600MT/s             | 1        | 0.92%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s             | 1        | 0.92%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s             | 1        | 0.92%   |
| Kingston RAM 99U5428-040.A01LF 4GB SODIMM DDR3 1333MT/s           | 1        | 0.92%   |
| Kingston RAM 99U5428-018.A00LF 8GB DIMM DDR3 1600MT/s             | 1        | 0.92%   |
| Kingston RAM 9965684-040.A00G 8GB DIMM DDR4 2667MT/s              | 1        | 0.92%   |
| Kingston RAM 9965589-069.E00G 16GB DIMM DDR4 2400MT/s             | 1        | 0.92%   |
| Kingston RAM 9965589-014.E00G 8GB DIMM 2133MT/s                   | 1        | 0.92%   |
| Kingston RAM 9965589-008.D01G 8GB DIMM 2133MT/s                   | 1        | 0.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 50       | 54.35%  |
| DDR4    | 33       | 35.87%  |
| DDR2    | 5        | 5.43%   |
| Unknown | 2        | 2.17%   |
| LPDDR4  | 1        | 1.09%   |
| DDR     | 1        | 1.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 59       | 64.13%  |
| SODIMM  | 32       | 34.78%  |
| Unknown | 1        | 1.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 39       | 39.8%   |
| 4096  | 34       | 34.69%  |
| 2048  | 14       | 14.29%  |
| 16384 | 8        | 8.16%   |
| 1024  | 2        | 2.04%   |
| 32768 | 1        | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 31       | 32.63%  |
| 1333    | 21       | 22.11%  |
| 2400    | 10       | 10.53%  |
| 2133    | 9        | 9.47%   |
| 2667    | 7        | 7.37%   |
| 3200    | 3        | 3.16%   |
| 800     | 3        | 3.16%   |
| 2666    | 2        | 2.11%   |
| 667     | 2        | 2.11%   |
| 3400    | 1        | 1.05%   |
| 3000    | 1        | 1.05%   |
| 2933    | 1        | 1.05%   |
| 2134    | 1        | 1.05%   |
| 1067    | 1        | 1.05%   |
| 533     | 1        | 1.05%   |
| Unknown | 1        | 1.05%   |

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

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Sonix Technology | 1        | 50%     |
| Logitech         | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Sonix FHD Webcam            | 1        | 50%     |
| Logitech HD Pro Webcam C920 | 1        | 50%     |

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
| 1     | 55       | 48.25%  |
| 0     | 42       | 36.84%  |
| 2     | 15       | 13.16%  |
| 3     | 2        | 1.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 64       | 75.29%  |
| Net/wireless             | 8        | 9.41%   |
| Bluetooth                | 5        | 5.88%   |
| Net/ethernet             | 2        | 2.35%   |
| Card reader              | 2        | 2.35%   |
| Storage/ata              | 1        | 1.18%   |
| Storage                  | 1        | 1.18%   |
| Graphics card            | 1        | 1.18%   |
| Firewire controller      | 1        | 1.18%   |

