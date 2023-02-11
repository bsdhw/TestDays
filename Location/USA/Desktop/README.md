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

Total: 2471

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Supermicro    | X9SCL/X9SCMA                | [af957bb4fa](https://bsd-hardware.info/?probe=af957bb4fa) | Feb 01, 2023 |
| Dell          | 0J584C A00                  | [3f5428623d](https://bsd-hardware.info/?probe=3f5428623d) | Feb 01, 2023 |
| ASRock        | B450M Pro4                  | [27f3968fd4](https://bsd-hardware.info/?probe=27f3968fd4) | Jan 31, 2023 |
| Unknown       | Unknown                     | [c00728e738](https://bsd-hardware.info/?probe=c00728e738) | Jan 31, 2023 |
| Hardkernel    | ODROID-H3                   | [28530f37ec](https://bsd-hardware.info/?probe=28530f37ec) | Jan 31, 2023 |
| ASUSTek       | M5A99X EVO                  | [1e97ee1c05](https://bsd-hardware.info/?probe=1e97ee1c05) | Jan 31, 2023 |
| ASRock        | 970 Extreme3                | [5e2fd4b48f](https://bsd-hardware.info/?probe=5e2fd4b48f) | Jan 30, 2023 |
| Unknown       | Unknown                     | [348805aada](https://bsd-hardware.info/?probe=348805aada) | Jan 30, 2023 |
| Protectli     | FW6                         | [5a05c9fe40](https://bsd-hardware.info/?probe=5a05c9fe40) | Jan 30, 2023 |
| Dell          | 0WMJ54 A01                  | [5b55b50956](https://bsd-hardware.info/?probe=5b55b50956) | Jan 30, 2023 |
| Gigabyte      | H110M-A-CF                  | [27e7ae6041](https://bsd-hardware.info/?probe=27e7ae6041) | Jan 30, 2023 |
| MSI           | A88XM-E45                   | [f7eb6735d3](https://bsd-hardware.info/?probe=f7eb6735d3) | Jan 29, 2023 |
| MSI           | H81M-P33                    | [e6626da98c](https://bsd-hardware.info/?probe=e6626da98c) | Jan 29, 2023 |
| ASUSTek       | P5Q-E                       | [3d5ea9f313](https://bsd-hardware.info/?probe=3d5ea9f313) | Jan 29, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9b7532b795](https://bsd-hardware.info/?probe=9b7532b795) | Jan 29, 2023 |
| Techvision    | TVI7309X B0                 | [7cfdbb0e90](https://bsd-hardware.info/?probe=7cfdbb0e90) | Jan 29, 2023 |
| Protectli     | FW4B Ver                    | [7db7965ebb](https://bsd-hardware.info/?probe=7db7965ebb) | Jan 29, 2023 |
| HP            | 213D A01                    | [dea507ebe0](https://bsd-hardware.info/?probe=dea507ebe0) | Jan 29, 2023 |
| Protectli     | FW4B Ver                    | [ac63fa59a6](https://bsd-hardware.info/?probe=ac63fa59a6) | Jan 29, 2023 |
| Biostar       | Hi-Fi A85S3                 | [f4b661ad85](https://bsd-hardware.info/?probe=f4b661ad85) | Jan 28, 2023 |
| Dell          | 08NPPY A00                  | [1c4edf62e6](https://bsd-hardware.info/?probe=1c4edf62e6) | Jan 28, 2023 |
| ASRock        | B550M Phantom Gaming 4      | [a0a26f529c](https://bsd-hardware.info/?probe=a0a26f529c) | Jan 27, 2023 |
| HP            | 8299                        | [61b1c41f22](https://bsd-hardware.info/?probe=61b1c41f22) | Jan 27, 2023 |
| Protectli     | FW4B                        | [06eeeaa67b](https://bsd-hardware.info/?probe=06eeeaa67b) | Jan 27, 2023 |
| Dell          | 0HD5W2 A00                  | [226f25a086](https://bsd-hardware.info/?probe=226f25a086) | Jan 27, 2023 |
| Dell          | 02YYK5 A01                  | [56fea0c931](https://bsd-hardware.info/?probe=56fea0c931) | Jan 27, 2023 |
| ASUSTek       | M5A99X EVO                  | [18e688307e](https://bsd-hardware.info/?probe=18e688307e) | Jan 27, 2023 |
| AMD           | Kabini CRB                  | [3405de1629](https://bsd-hardware.info/?probe=3405de1629) | Jan 27, 2023 |
| Dell          | 0NC2VH A01                  | [d1e71effc5](https://bsd-hardware.info/?probe=d1e71effc5) | Jan 26, 2023 |
| Unknown       | Unknown                     | [bc41bdb431](https://bsd-hardware.info/?probe=bc41bdb431) | Jan 26, 2023 |
| Techvision    | TVI7309X B0                 | [1803740ba6](https://bsd-hardware.info/?probe=1803740ba6) | Jan 25, 2023 |
| Dell          | 02YYK5 A01                  | [82718999a8](https://bsd-hardware.info/?probe=82718999a8) | Jan 25, 2023 |
| HP            | 802E                        | [1f3bf517af](https://bsd-hardware.info/?probe=1f3bf517af) | Jan 25, 2023 |
| Google        | Panther                     | [73d3147166](https://bsd-hardware.info/?probe=73d3147166) | Jan 24, 2023 |
| Gigabyte      | H110M-A-CF                  | [54be5c792e](https://bsd-hardware.info/?probe=54be5c792e) | Jan 24, 2023 |
| HP            | 83F2                        | [970c786b06](https://bsd-hardware.info/?probe=970c786b06) | Jan 24, 2023 |
| Apple         | Mac-F221BEC8                | [556e872ffe](https://bsd-hardware.info/?probe=556e872ffe) | Jan 24, 2023 |
| Protectli     | FW4A Ver                    | [b91fe4d66f](https://bsd-hardware.info/?probe=b91fe4d66f) | Jan 23, 2023 |
| Dell          | 05GD68 A00                  | [f2f100ee10](https://bsd-hardware.info/?probe=f2f100ee10) | Jan 23, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [d03f9c19f8](https://bsd-hardware.info/?probe=d03f9c19f8) | Jan 23, 2023 |
| Dell          | 0HHV7N A00                  | [771f2c4d96](https://bsd-hardware.info/?probe=771f2c4d96) | Jan 23, 2023 |
| ASUSTek       | X99-A/USB                   | [006553f965](https://bsd-hardware.info/?probe=006553f965) | Jan 23, 2023 |
| ASUSTek       | P5Q-E                       | [26d1d923d6](https://bsd-hardware.info/?probe=26d1d923d6) | Jan 22, 2023 |
| MSI           | H81M-P33                    | [0bbc074f1c](https://bsd-hardware.info/?probe=0bbc074f1c) | Jan 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [28d8d82d34](https://bsd-hardware.info/?probe=28d8d82d34) | Jan 22, 2023 |
| AZW           | Green G1                    | [80498a4090](https://bsd-hardware.info/?probe=80498a4090) | Jan 21, 2023 |
| AZW           | Green G1                    | [0c84e93ba7](https://bsd-hardware.info/?probe=0c84e93ba7) | Jan 21, 2023 |
| MSI           | Z87-G41 PC Mate             | [7a21bfbfb9](https://bsd-hardware.info/?probe=7a21bfbfb9) | Jan 20, 2023 |
| Gigabyte      | F2A75M-HD2                  | [4770b980d6](https://bsd-hardware.info/?probe=4770b980d6) | Jan 20, 2023 |
| Intel         | DQ67SW AAG12527-310         | [a4688e4059](https://bsd-hardware.info/?probe=a4688e4059) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2ea8c1d1a4](https://bsd-hardware.info/?probe=2ea8c1d1a4) | Jan 20, 2023 |
| Intel         | SHARKBAY                    | [47742b68d5](https://bsd-hardware.info/?probe=47742b68d5) | Jan 19, 2023 |
| Unknown       | Unknown                     | [62bad8c9f8](https://bsd-hardware.info/?probe=62bad8c9f8) | Jan 19, 2023 |
| Unknown       | Unknown                     | [28bb1a7282](https://bsd-hardware.info/?probe=28bb1a7282) | Jan 19, 2023 |
| Intel         | DQ77KB AAG81483-501         | [c5d050f0d6](https://bsd-hardware.info/?probe=c5d050f0d6) | Jan 18, 2023 |
| Dell          | 05XGC8 A01                  | [f929122d8a](https://bsd-hardware.info/?probe=f929122d8a) | Jan 18, 2023 |
| Intel         | DH67BL AAG10189-206         | [37ae895d75](https://bsd-hardware.info/?probe=37ae895d75) | Jan 17, 2023 |
| Intel         | DQ45CB AAE30148-302         | [349da05405](https://bsd-hardware.info/?probe=349da05405) | Jan 17, 2023 |
| Dell          | 0J584C A00                  | [65ce4b26be](https://bsd-hardware.info/?probe=65ce4b26be) | Jan 17, 2023 |
| Dell          | 0NW6H5 A00                  | [11943e270e](https://bsd-hardware.info/?probe=11943e270e) | Jan 17, 2023 |
| HP            | 1998                        | [6c36e5e82e](https://bsd-hardware.info/?probe=6c36e5e82e) | Jan 17, 2023 |
| Unknown       | Unknown                     | [63689d3fbc](https://bsd-hardware.info/?probe=63689d3fbc) | Jan 17, 2023 |
| Intel         | DQ67SW AAG12527-310         | [78a4659386](https://bsd-hardware.info/?probe=78a4659386) | Jan 16, 2023 |
| Unknown       | QD-CMU01                    | [768a10819b](https://bsd-hardware.info/?probe=768a10819b) | Jan 16, 2023 |
| HP            | 0AECh D                     | [25b7a10166](https://bsd-hardware.info/?probe=25b7a10166) | Jan 16, 2023 |
| ASRock        | H370M-ITX/ac                | [e25304fa01](https://bsd-hardware.info/?probe=e25304fa01) | Jan 15, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | [af7a4d3493](https://bsd-hardware.info/?probe=af7a4d3493) | Jan 15, 2023 |
| MSI           | H81M-P33                    | [800b3bc34b](https://bsd-hardware.info/?probe=800b3bc34b) | Jan 15, 2023 |
| ASUSTek       | P5Q-E                       | [ffbcac312f](https://bsd-hardware.info/?probe=ffbcac312f) | Jan 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [48e7397e29](https://bsd-hardware.info/?probe=48e7397e29) | Jan 15, 2023 |
| Silicom       | 80300-0214-G01 R311         | [547b59be2b](https://bsd-hardware.info/?probe=547b59be2b) | Jan 15, 2023 |
| Dell          | 0C2KJT A00                  | [9364056dac](https://bsd-hardware.info/?probe=9364056dac) | Jan 15, 2023 |
| ASUSTek       | Z97-A                       | [a975d143b8](https://bsd-hardware.info/?probe=a975d143b8) | Jan 15, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [05cc17947c](https://bsd-hardware.info/?probe=05cc17947c) | Jan 15, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [9c70b7e4e1](https://bsd-hardware.info/?probe=9c70b7e4e1) | Jan 15, 2023 |
| ASUSTek       | PRIME X370-PRO              | [f682e06d06](https://bsd-hardware.info/?probe=f682e06d06) | Jan 13, 2023 |
| Intel         | Q3XXG4-P V1.0               | [c5769bcae3](https://bsd-hardware.info/?probe=c5769bcae3) | Jan 13, 2023 |
| Dell          | 0T7D40 A01                  | [82f4b97203](https://bsd-hardware.info/?probe=82f4b97203) | Jan 13, 2023 |
| Dell          | 04Y8V0 A02                  | [a18d3bf0ea](https://bsd-hardware.info/?probe=a18d3bf0ea) | Jan 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [95ebd841b2](https://bsd-hardware.info/?probe=95ebd841b2) | Jan 12, 2023 |
| Dell          | 051FJ8 A01                  | [8d5c03acf1](https://bsd-hardware.info/?probe=8d5c03acf1) | Jan 12, 2023 |
| Dell          | 0773VG A00                  | [8f3e58f2bc](https://bsd-hardware.info/?probe=8f3e58f2bc) | Jan 12, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [4154475f49](https://bsd-hardware.info/?probe=4154475f49) | Jan 12, 2023 |
| Gigabyte      | Z390 AORUS ELITE            | [53a5719c6a](https://bsd-hardware.info/?probe=53a5719c6a) | Jan 12, 2023 |
| Dell          | 0NW6H5 A00                  | [b1b7d05863](https://bsd-hardware.info/?probe=b1b7d05863) | Jan 12, 2023 |
| Protectli     | FW6 Ver                     | [619a877f82](https://bsd-hardware.info/?probe=619a877f82) | Jan 12, 2023 |
| HP            | 843B                        | [3e2070415f](https://bsd-hardware.info/?probe=3e2070415f) | Jan 11, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [5eedf320f8](https://bsd-hardware.info/?probe=5eedf320f8) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [5386547734](https://bsd-hardware.info/?probe=5386547734) | Jan 11, 2023 |
| Unknown       | Unknown                     | [9b1707aed4](https://bsd-hardware.info/?probe=9b1707aed4) | Jan 11, 2023 |
| HP            | 805D                        | [4912ca5cd6](https://bsd-hardware.info/?probe=4912ca5cd6) | Jan 11, 2023 |
| MSI           | H110M-A PRO M2              | [3cf7d4a076](https://bsd-hardware.info/?probe=3cf7d4a076) | Jan 11, 2023 |
| HP            | 805D                        | [3da9c57f1f](https://bsd-hardware.info/?probe=3da9c57f1f) | Jan 11, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [e4af143188](https://bsd-hardware.info/?probe=e4af143188) | Jan 10, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [0b16265d11](https://bsd-hardware.info/?probe=0b16265d11) | Jan 10, 2023 |
| Techvision    | TVI7309X B0                 | [6b37f8e185](https://bsd-hardware.info/?probe=6b37f8e185) | Jan 10, 2023 |
| Protectli     | FW6 Ver                     | [c554f29fbb](https://bsd-hardware.info/?probe=c554f29fbb) | Jan 10, 2023 |
| Unknown       | Unknown                     | [2db049304e](https://bsd-hardware.info/?probe=2db049304e) | Jan 10, 2023 |
| MW            | GMLK-2_5G4L                 | [12a726c7f3](https://bsd-hardware.info/?probe=12a726c7f3) | Jan 10, 2023 |
| HP            | 8054                        | [7a7dd659c8](https://bsd-hardware.info/?probe=7a7dd659c8) | Jan 09, 2023 |
| Protectli     | FW6                         | [606f595213](https://bsd-hardware.info/?probe=606f595213) | Jan 09, 2023 |
| Protectli     | FW6                         | [6db7b1f01d](https://bsd-hardware.info/?probe=6db7b1f01d) | Jan 09, 2023 |
| Dell          | 04Y8V0 A02                  | [1ebacfe659](https://bsd-hardware.info/?probe=1ebacfe659) | Jan 09, 2023 |
| HP            | 8299                        | [f80e368b24](https://bsd-hardware.info/?probe=f80e368b24) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [917b19fbeb](https://bsd-hardware.info/?probe=917b19fbeb) | Jan 09, 2023 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [c86fd3a6ff](https://bsd-hardware.info/?probe=c86fd3a6ff) | Jan 08, 2023 |
| Unknown       | Unknown                     | [0714b46000](https://bsd-hardware.info/?probe=0714b46000) | Jan 08, 2023 |
| Dell          | 0WMJ54 A01                  | [011121c9a5](https://bsd-hardware.info/?probe=011121c9a5) | Jan 08, 2023 |
| MSI           | H81M-P33                    | [585a3dc78c](https://bsd-hardware.info/?probe=585a3dc78c) | Jan 08, 2023 |
| ASUSTek       | P5Q-E                       | [1e9d8cc278](https://bsd-hardware.info/?probe=1e9d8cc278) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [490261883c](https://bsd-hardware.info/?probe=490261883c) | Jan 08, 2023 |
| CheckPoint    | T-180-00                    | [5cee1fe8d6](https://bsd-hardware.info/?probe=5cee1fe8d6) | Jan 08, 2023 |
| Unknown       | Unknown                     | [8c877bf16e](https://bsd-hardware.info/?probe=8c877bf16e) | Jan 08, 2023 |
| Protectli     | FW6                         | [6ce513ba71](https://bsd-hardware.info/?probe=6ce513ba71) | Jan 08, 2023 |
| Dell          | 05GD68 A00                  | [c42af2bdc3](https://bsd-hardware.info/?probe=c42af2bdc3) | Jan 08, 2023 |
| HP            | 3397                        | [516464d7ef](https://bsd-hardware.info/?probe=516464d7ef) | Jan 08, 2023 |
| Unknown       | Unknown                     | [bb243a8862](https://bsd-hardware.info/?probe=bb243a8862) | Jan 08, 2023 |
| HP            | 8617                        | [2dd1830de4](https://bsd-hardware.info/?probe=2dd1830de4) | Jan 07, 2023 |
| Dell          | 02K9CR A02                  | [3547d6c126](https://bsd-hardware.info/?probe=3547d6c126) | Jan 06, 2023 |
| Dell          | 0K240Y A02                  | [379b59f079](https://bsd-hardware.info/?probe=379b59f079) | Jan 05, 2023 |
| Unknown       | Unknown                     | [b3295065c3](https://bsd-hardware.info/?probe=b3295065c3) | Jan 05, 2023 |
| MW            | GMLK-2_5G4L                 | [e3f89954bd](https://bsd-hardware.info/?probe=e3f89954bd) | Jan 05, 2023 |
| ASUSTek       | X99-DELUXE                  | [9dc3183152](https://bsd-hardware.info/?probe=9dc3183152) | Jan 04, 2023 |
| Supermicro    | X10DRiB                     | [d120c268f7](https://bsd-hardware.info/?probe=d120c268f7) | Jan 04, 2023 |
| Supermicro    | X10DRi-T                    | [3bd4e1dc9c](https://bsd-hardware.info/?probe=3bd4e1dc9c) | Jan 04, 2023 |
| Unknown       | Unknown                     | [6062f9823e](https://bsd-hardware.info/?probe=6062f9823e) | Jan 04, 2023 |
| MW            | GMLK-2_5G4L                 | [f10075e5d1](https://bsd-hardware.info/?probe=f10075e5d1) | Jan 04, 2023 |
| Unknown       | Unknown                     | [42277bd8ff](https://bsd-hardware.info/?probe=42277bd8ff) | Jan 04, 2023 |
| Protectli     | FW6 Ver                     | [8069ed414b](https://bsd-hardware.info/?probe=8069ed414b) | Jan 03, 2023 |
| Intel         | Q3XXG4-P V1.0               | [7d6e899adb](https://bsd-hardware.info/?probe=7d6e899adb) | Jan 03, 2023 |
| HP            | 213D A01                    | [3a1fd3f0a0](https://bsd-hardware.info/?probe=3a1fd3f0a0) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [5159265605](https://bsd-hardware.info/?probe=5159265605) | Jan 02, 2023 |
| HP            | 8055                        | [c8f3d3687d](https://bsd-hardware.info/?probe=c8f3d3687d) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [1697219032](https://bsd-hardware.info/?probe=1697219032) | Jan 02, 2023 |
| Gigabyte      | Z390 AORUS ELITE            | [dcf6e2df1a](https://bsd-hardware.info/?probe=dcf6e2df1a) | Jan 02, 2023 |
| SmbiosType... | SmbiosType2_BoardProduct... | [d8d62a103a](https://bsd-hardware.info/?probe=d8d62a103a) | Jan 02, 2023 |
| MSI           | H81M-P33                    | [0a57dcce99](https://bsd-hardware.info/?probe=0a57dcce99) | Jan 01, 2023 |
| ASUSTek       | P5Q-E                       | [d3306559de](https://bsd-hardware.info/?probe=d3306559de) | Jan 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [772779fadf](https://bsd-hardware.info/?probe=772779fadf) | Jan 01, 2023 |
| Dell          | 0FDY5C A00                  | [6345f92400](https://bsd-hardware.info/?probe=6345f92400) | Jan 01, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [0bf1c2abef](https://bsd-hardware.info/?probe=0bf1c2abef) | Dec 31, 2022 |
| Unknown       | Unknown                     | [68a847f5c2](https://bsd-hardware.info/?probe=68a847f5c2) | Dec 31, 2022 |
| GoWin Solu... | R86S                        | [4243d313a1](https://bsd-hardware.info/?probe=4243d313a1) | Dec 31, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [4d9a4bfc40](https://bsd-hardware.info/?probe=4d9a4bfc40) | Dec 30, 2022 |
| Protectli     | FW6                         | [0d62222b7a](https://bsd-hardware.info/?probe=0d62222b7a) | Dec 30, 2022 |
| Dell          | 0GN4PW A00                  | [77e235d9f8](https://bsd-hardware.info/?probe=77e235d9f8) | Dec 29, 2022 |
| Unknown       | Unknown                     | [1dab2c420a](https://bsd-hardware.info/?probe=1dab2c420a) | Dec 28, 2022 |
| Intel         | DENLOW_REFRESH_WS           | [4f86e686d2](https://bsd-hardware.info/?probe=4f86e686d2) | Dec 28, 2022 |
| Dell          | 0WMJ54 A01                  | [d4296fd9d8](https://bsd-hardware.info/?probe=d4296fd9d8) | Dec 26, 2022 |
| Unknown       | Unknown                     | [39bce6117f](https://bsd-hardware.info/?probe=39bce6117f) | Dec 26, 2022 |
| Dell          | 051FJ8 A01                  | [7f66a21d24](https://bsd-hardware.info/?probe=7f66a21d24) | Dec 26, 2022 |
| Unknown       | Unknown                     | [e52abbf1b8](https://bsd-hardware.info/?probe=e52abbf1b8) | Dec 26, 2022 |
| Protectli     | FW6                         | [90758fca97](https://bsd-hardware.info/?probe=90758fca97) | Dec 26, 2022 |
| ASUSTek       | P5Q-E                       | [bc829dbb1a](https://bsd-hardware.info/?probe=bc829dbb1a) | Dec 25, 2022 |
| MSI           | H81M-P33                    | [f73a37ab81](https://bsd-hardware.info/?probe=f73a37ab81) | Dec 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2e842ddb27](https://bsd-hardware.info/?probe=2e842ddb27) | Dec 25, 2022 |
| Cisco         | ASA5515 A0                  | [9e587b9499](https://bsd-hardware.info/?probe=9e587b9499) | Dec 25, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | [1769da5143](https://bsd-hardware.info/?probe=1769da5143) | Dec 25, 2022 |
| HP            | 213D A01                    | [bd620f0fc0](https://bsd-hardware.info/?probe=bd620f0fc0) | Dec 25, 2022 |
| Unknown       | Unknown                     | [bd212706ad](https://bsd-hardware.info/?probe=bd212706ad) | Dec 24, 2022 |
| Supermicro    | X10SRH-CLN4FA               | [84c360ad02](https://bsd-hardware.info/?probe=84c360ad02) | Dec 24, 2022 |
| ASUSTek       | GRYPHON Z87                 | [b29f2e4573](https://bsd-hardware.info/?probe=b29f2e4573) | Dec 24, 2022 |
| Dell          | 02YYK5 A01                  | [701c6e95d6](https://bsd-hardware.info/?probe=701c6e95d6) | Dec 24, 2022 |
| Gigabyte      | Z390 AORUS ELITE            | [91b7417b84](https://bsd-hardware.info/?probe=91b7417b84) | Dec 24, 2022 |
| MSI           | A78M-E35                    | [03176e6683](https://bsd-hardware.info/?probe=03176e6683) | Dec 23, 2022 |
| Intel         | SHARKBAY                    | [df221cefbc](https://bsd-hardware.info/?probe=df221cefbc) | Dec 22, 2022 |
| Dell          | 0UW457 A03                  | [47b66a0d86](https://bsd-hardware.info/?probe=47b66a0d86) | Dec 21, 2022 |
| Protectli     | FW2B Ver                    | [9596576df7](https://bsd-hardware.info/?probe=9596576df7) | Dec 20, 2022 |
| ASRock        | 4X4-4000 Series             | [31f17adc5b](https://bsd-hardware.info/?probe=31f17adc5b) | Dec 20, 2022 |
| Unknown       | Unknown                     | [4c5ccd04d0](https://bsd-hardware.info/?probe=4c5ccd04d0) | Dec 19, 2022 |
| Dell          | 0WMJ54 A01                  | [b84941cdd5](https://bsd-hardware.info/?probe=b84941cdd5) | Dec 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c1b0b83306](https://bsd-hardware.info/?probe=c1b0b83306) | Dec 18, 2022 |
| MSI           | H81M-P33                    | [78e4743abd](https://bsd-hardware.info/?probe=78e4743abd) | Dec 18, 2022 |
| ASUSTek       | P5Q-E                       | [f232e5746e](https://bsd-hardware.info/?probe=f232e5746e) | Dec 18, 2022 |
| ASRock        | H370M-ITX/ac                | [a40ada7f7f](https://bsd-hardware.info/?probe=a40ada7f7f) | Dec 18, 2022 |
| Unknown       | Unknown                     | [f6fababc22](https://bsd-hardware.info/?probe=f6fababc22) | Dec 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a1b29c356e](https://bsd-hardware.info/?probe=a1b29c356e) | Dec 17, 2022 |
| Protectli     | FW6                         | [56f62226e7](https://bsd-hardware.info/?probe=56f62226e7) | Dec 17, 2022 |
| HP            | 213D A01                    | [088766f04d](https://bsd-hardware.info/?probe=088766f04d) | Dec 17, 2022 |
| Dell          | 0FDY5C A00                  | [afef2952f9](https://bsd-hardware.info/?probe=afef2952f9) | Dec 17, 2022 |
| BESSTAR Te... | UM350                       | [b7e599f99d](https://bsd-hardware.info/?probe=b7e599f99d) | Dec 17, 2022 |
| CncTion       | N5105-4L B0                 | [0da9ef9752](https://bsd-hardware.info/?probe=0da9ef9752) | Dec 17, 2022 |
| Unknown       | Unknown                     | [a94bfdaa5c](https://bsd-hardware.info/?probe=a94bfdaa5c) | Dec 16, 2022 |
| Intel         | DQ77KB AAG81483-501         | [cc51093e02](https://bsd-hardware.info/?probe=cc51093e02) | Dec 16, 2022 |
| HP            | 2215                        | [76f607b100](https://bsd-hardware.info/?probe=76f607b100) | Dec 14, 2022 |
| Techvision    | TVI7309X B0                 | [a77d60297f](https://bsd-hardware.info/?probe=a77d60297f) | Dec 14, 2022 |
| Apple         | Mac-F221BEC8                | [bc15367e9f](https://bsd-hardware.info/?probe=bc15367e9f) | Dec 14, 2022 |
| Unknown       | Unknown                     | [ad7f977515](https://bsd-hardware.info/?probe=ad7f977515) | Dec 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [f52a3d3fa6](https://bsd-hardware.info/?probe=f52a3d3fa6) | Dec 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | [abed96a938](https://bsd-hardware.info/?probe=abed96a938) | Dec 13, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | [66e0c118d2](https://bsd-hardware.info/?probe=66e0c118d2) | Dec 13, 2022 |
| Unknown       | Unknown                     | [128ce54404](https://bsd-hardware.info/?probe=128ce54404) | Dec 12, 2022 |
| Gigabyte      | X99-Designare EX-CF         | [de5bf4b420](https://bsd-hardware.info/?probe=de5bf4b420) | Dec 12, 2022 |
| MSI           | H81M-P33                    | [1f110891d0](https://bsd-hardware.info/?probe=1f110891d0) | Dec 11, 2022 |
| ASUSTek       | P5Q-E                       | [028383847e](https://bsd-hardware.info/?probe=028383847e) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [99502ebe9a](https://bsd-hardware.info/?probe=99502ebe9a) | Dec 11, 2022 |
| Lenovo        | MAHOBAY NOK                 | [ad71b00b0d](https://bsd-hardware.info/?probe=ad71b00b0d) | Dec 11, 2022 |
| Dell          | 0WMJ54 A01                  | [4b14039072](https://bsd-hardware.info/?probe=4b14039072) | Dec 11, 2022 |
| Protectli     | FW4B Ver                    | [808108016d](https://bsd-hardware.info/?probe=808108016d) | Dec 10, 2022 |
| Intel         | Q3XXG4-P V1.0               | [0b08951f1c](https://bsd-hardware.info/?probe=0b08951f1c) | Dec 10, 2022 |
| Protectli     | VP2410 10                   | [3f55143fd9](https://bsd-hardware.info/?probe=3f55143fd9) | Dec 09, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | [6b03cb139e](https://bsd-hardware.info/?probe=6b03cb139e) | Dec 09, 2022 |
| Dell          | 05GD68 A00                  | [b2f0da8246](https://bsd-hardware.info/?probe=b2f0da8246) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [48d5feacf2](https://bsd-hardware.info/?probe=48d5feacf2) | Dec 08, 2022 |
| Protectli     | FW4C Ver                    | [71368e5cde](https://bsd-hardware.info/?probe=71368e5cde) | Dec 08, 2022 |
| ASRock        | 4X4-4000 Series             | [8ac499a511](https://bsd-hardware.info/?probe=8ac499a511) | Dec 07, 2022 |
| HP            | 1495                        | [3f033cb7f5](https://bsd-hardware.info/?probe=3f033cb7f5) | Dec 07, 2022 |
| Dell          | 0WMJ54 A01                  | [61347ab3e9](https://bsd-hardware.info/?probe=61347ab3e9) | Dec 06, 2022 |
| Unknown       | Unknown                     | [e3dad11b11](https://bsd-hardware.info/?probe=e3dad11b11) | Dec 06, 2022 |
| Dell          | 0WMJ54 A01                  | [5441995e7b](https://bsd-hardware.info/?probe=5441995e7b) | Dec 05, 2022 |
| Intel         | Q3XXG4-P V1.0               | [f130844e1e](https://bsd-hardware.info/?probe=f130844e1e) | Dec 05, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | [05566134f9](https://bsd-hardware.info/?probe=05566134f9) | Dec 05, 2022 |
| Dell          | 02YYK5 A01                  | [54d1511b82](https://bsd-hardware.info/?probe=54d1511b82) | Dec 04, 2022 |
| MSI           | H81M-P33                    | [d72a45fb8f](https://bsd-hardware.info/?probe=d72a45fb8f) | Dec 04, 2022 |
| ASUSTek       | P5Q-E                       | [595d174631](https://bsd-hardware.info/?probe=595d174631) | Dec 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8ee41750dc](https://bsd-hardware.info/?probe=8ee41750dc) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [aeb690b9f3](https://bsd-hardware.info/?probe=aeb690b9f3) | Dec 03, 2022 |
| Dell          | 0PTTT9 A01                  | [1916a4064b](https://bsd-hardware.info/?probe=1916a4064b) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [d4e60c5984](https://bsd-hardware.info/?probe=d4e60c5984) | Dec 03, 2022 |
| Unknown       | Unknown                     | [90de1777bc](https://bsd-hardware.info/?probe=90de1777bc) | Dec 02, 2022 |
| Techvision    | TVI7309X B0                 | [f8719b2320](https://bsd-hardware.info/?probe=f8719b2320) | Dec 02, 2022 |
| Unknown       | Unknown                     | [243e309a04](https://bsd-hardware.info/?probe=243e309a04) | Dec 01, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [03708406e8](https://bsd-hardware.info/?probe=03708406e8) | Dec 01, 2022 |
| HP            | 8054                        | [c25adeb2ff](https://bsd-hardware.info/?probe=c25adeb2ff) | Dec 01, 2022 |
| Unknown       | Unknown                     | [504a659236](https://bsd-hardware.info/?probe=504a659236) | Dec 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [794e041b13](https://bsd-hardware.info/?probe=794e041b13) | Nov 30, 2022 |
| Protectli     | FW6                         | [95f3201109](https://bsd-hardware.info/?probe=95f3201109) | Nov 30, 2022 |
| Protectli     | FW4A Ver                    | [9e6e0f5548](https://bsd-hardware.info/?probe=9e6e0f5548) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7308d658dc](https://bsd-hardware.info/?probe=7308d658dc) | Nov 29, 2022 |
| HP            | 8299                        | [d697a2e953](https://bsd-hardware.info/?probe=d697a2e953) | Nov 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | [b1f32ca8a1](https://bsd-hardware.info/?probe=b1f32ca8a1) | Nov 28, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [b4cc780c40](https://bsd-hardware.info/?probe=b4cc780c40) | Nov 28, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [fd111870fa](https://bsd-hardware.info/?probe=fd111870fa) | Nov 28, 2022 |
| ASUSTek       | H97-PLUS                    | [39ece5deaf](https://bsd-hardware.info/?probe=39ece5deaf) | Nov 27, 2022 |
| MSI           | H81M-P33                    | [597d48d1c9](https://bsd-hardware.info/?probe=597d48d1c9) | Nov 27, 2022 |
| ASUSTek       | P5Q-E                       | [10d76fd431](https://bsd-hardware.info/?probe=10d76fd431) | Nov 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [383341b2f1](https://bsd-hardware.info/?probe=383341b2f1) | Nov 27, 2022 |
| HP            | 18E7                        | [c7635c715f](https://bsd-hardware.info/?probe=c7635c715f) | Nov 26, 2022 |
| Intel         | DH87MC AAG74242-401         | [33c1878560](https://bsd-hardware.info/?probe=33c1878560) | Nov 26, 2022 |
| ASUSTek       | P5K-E                       | [2b00248458](https://bsd-hardware.info/?probe=2b00248458) | Nov 26, 2022 |
| Dell          | 0M017G A00                  | [3acaad9a7d](https://bsd-hardware.info/?probe=3acaad9a7d) | Nov 26, 2022 |
| Unknown       | Unknown                     | [6de307244e](https://bsd-hardware.info/?probe=6de307244e) | Nov 26, 2022 |
| Protectli     | FW2B Ver                    | [e03929e52f](https://bsd-hardware.info/?probe=e03929e52f) | Nov 25, 2022 |
| MSI           | Z170A GAMING M5             | [5740972ddc](https://bsd-hardware.info/?probe=5740972ddc) | Nov 25, 2022 |
| MW            | GMLK-2_5G4L                 | [de7f2ee053](https://bsd-hardware.info/?probe=de7f2ee053) | Nov 25, 2022 |
| Unknown       | Unknown                     | [5aa1f0193a](https://bsd-hardware.info/?probe=5aa1f0193a) | Nov 24, 2022 |
| Dell          | 07F37C A01                  | [08d048da80](https://bsd-hardware.info/?probe=08d048da80) | Nov 24, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [1b6870d481](https://bsd-hardware.info/?probe=1b6870d481) | Nov 23, 2022 |
| Dell          | 06D7TR A00                  | [7fabc0cb8a](https://bsd-hardware.info/?probe=7fabc0cb8a) | Nov 23, 2022 |
| Unknown       | Unknown                     | [337d5f0f4b](https://bsd-hardware.info/?probe=337d5f0f4b) | Nov 23, 2022 |
| Protectli     | FW4B                        | [d3090c9e8e](https://bsd-hardware.info/?probe=d3090c9e8e) | Nov 23, 2022 |
| PC Engines    | APU2                        | [4d33b6da51](https://bsd-hardware.info/?probe=4d33b6da51) | Nov 23, 2022 |
| CncTion       | N5105-4L B0                 | [d4791d1dfc](https://bsd-hardware.info/?probe=d4791d1dfc) | Nov 22, 2022 |
| Unknown       | Unknown                     | [fdffbdb940](https://bsd-hardware.info/?probe=fdffbdb940) | Nov 22, 2022 |
| Protectli     | FW4B Ver                    | [77fa42b66c](https://bsd-hardware.info/?probe=77fa42b66c) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f7129f1c87](https://bsd-hardware.info/?probe=f7129f1c87) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [17aa370584](https://bsd-hardware.info/?probe=17aa370584) | Nov 21, 2022 |
| Unknown       | SKYBAY                      | [5030575f0a](https://bsd-hardware.info/?probe=5030575f0a) | Nov 20, 2022 |
| Dell          | 07F37C A01                  | [efb5c9d03d](https://bsd-hardware.info/?probe=efb5c9d03d) | Nov 20, 2022 |
| MSI           | H81M-P33                    | [d3303d1962](https://bsd-hardware.info/?probe=d3303d1962) | Nov 20, 2022 |
| ASUSTek       | P5Q-E                       | [b1512a254c](https://bsd-hardware.info/?probe=b1512a254c) | Nov 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [521e5ffa8e](https://bsd-hardware.info/?probe=521e5ffa8e) | Nov 20, 2022 |
| HP            | 8054                        | [2c1e20c9e7](https://bsd-hardware.info/?probe=2c1e20c9e7) | Nov 20, 2022 |
| Hardkernel    | ODROID-H3                   | [ec7611edd1](https://bsd-hardware.info/?probe=ec7611edd1) | Nov 20, 2022 |
| Techvision    | TVI7309X B0                 | [c226ac3d9b](https://bsd-hardware.info/?probe=c226ac3d9b) | Nov 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | [5d3ccb6891](https://bsd-hardware.info/?probe=5d3ccb6891) | Nov 20, 2022 |
| CncTion       | N5105-4L B0                 | [449dcd1463](https://bsd-hardware.info/?probe=449dcd1463) | Nov 19, 2022 |
| Dell          | 09D2HH A00                  | [794fe8eb65](https://bsd-hardware.info/?probe=794fe8eb65) | Nov 19, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | [402a623ed0](https://bsd-hardware.info/?probe=402a623ed0) | Nov 19, 2022 |
| Foxconn       | H67S/H61SP                  | [80ad331089](https://bsd-hardware.info/?probe=80ad331089) | Nov 19, 2022 |
| Lenovo        | MAHOBAY NOK                 | [18062e5bd5](https://bsd-hardware.info/?probe=18062e5bd5) | Nov 19, 2022 |
| Dell          | 0GN4PW A00                  | [9127ec4dac](https://bsd-hardware.info/?probe=9127ec4dac) | Nov 19, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [2eba32390f](https://bsd-hardware.info/?probe=2eba32390f) | Nov 19, 2022 |
| MSI           | Z97S SLI Krait Edition      | [f25480c54a](https://bsd-hardware.info/?probe=f25480c54a) | Nov 18, 2022 |
| HP            | 82FE 11                     | [547e5e3ce1](https://bsd-hardware.info/?probe=547e5e3ce1) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | [f732942dd9](https://bsd-hardware.info/?probe=f732942dd9) | Nov 18, 2022 |
| Dell          | 051FJ8 A02                  | [296b446a8f](https://bsd-hardware.info/?probe=296b446a8f) | Nov 18, 2022 |
| MSI           | Z97S SLI Krait Edition      | [ddf3f8603a](https://bsd-hardware.info/?probe=ddf3f8603a) | Nov 17, 2022 |
| AAEON         | MF-001 V1.0                 | [d98d84f1a4](https://bsd-hardware.info/?probe=d98d84f1a4) | Nov 17, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | [9cd1c1fc21](https://bsd-hardware.info/?probe=9cd1c1fc21) | Nov 17, 2022 |
| Dell          | 05XGC8 A00                  | [15458aff84](https://bsd-hardware.info/?probe=15458aff84) | Nov 16, 2022 |
| MSI           | Z97S SLI Krait Edition      | [47f82850da](https://bsd-hardware.info/?probe=47f82850da) | Nov 16, 2022 |
| Dell          | 05XGC8 A00                  | [94afb24fbc](https://bsd-hardware.info/?probe=94afb24fbc) | Nov 16, 2022 |
| Intel         | Q3XXG4-P V1.0               | [5096994f99](https://bsd-hardware.info/?probe=5096994f99) | Nov 16, 2022 |
| ASUSTek       | P6T DELUXE V2               | [314916c885](https://bsd-hardware.info/?probe=314916c885) | Nov 15, 2022 |
| Protectli     | FW4B Ver                    | [dd637e0562](https://bsd-hardware.info/?probe=dd637e0562) | Nov 15, 2022 |
| Dell          | 06D7TR A00                  | [9e568eb5ee](https://bsd-hardware.info/?probe=9e568eb5ee) | Nov 14, 2022 |
| Intel         | Q3XXG4-P V1.0               | [74a717c2e6](https://bsd-hardware.info/?probe=74a717c2e6) | Nov 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [6f1e732a53](https://bsd-hardware.info/?probe=6f1e732a53) | Nov 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [15e38a5ca8](https://bsd-hardware.info/?probe=15e38a5ca8) | Nov 13, 2022 |
| ASUSTek       | P5Q-E                       | [2b1175a4df](https://bsd-hardware.info/?probe=2b1175a4df) | Nov 13, 2022 |
| MSI           | H81M-P33                    | [98b0980231](https://bsd-hardware.info/?probe=98b0980231) | Nov 13, 2022 |
| Protectli     | FW4B Ver                    | [80c0d775a7](https://bsd-hardware.info/?probe=80c0d775a7) | Nov 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [072f2a6c27](https://bsd-hardware.info/?probe=072f2a6c27) | Nov 13, 2022 |
| Unknown       | Unknown                     | [838256315e](https://bsd-hardware.info/?probe=838256315e) | Nov 13, 2022 |
| HP            | 8169                        | [e80c8a40a5](https://bsd-hardware.info/?probe=e80c8a40a5) | Nov 12, 2022 |
| Protectli     | FW4B Ver                    | [75b586fdfc](https://bsd-hardware.info/?probe=75b586fdfc) | Nov 12, 2022 |
| Unknown       | Unknown                     | [817c69a4b0](https://bsd-hardware.info/?probe=817c69a4b0) | Nov 12, 2022 |
| MSI           | MS-9897                     | [2527ac44f4](https://bsd-hardware.info/?probe=2527ac44f4) | Nov 12, 2022 |
| Unknown       | Unknown                     | [790e616e22](https://bsd-hardware.info/?probe=790e616e22) | Nov 12, 2022 |
| Dell          | 06D7TR A00                  | [b8ee0562af](https://bsd-hardware.info/?probe=b8ee0562af) | Nov 12, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [54dd33114e](https://bsd-hardware.info/?probe=54dd33114e) | Nov 12, 2022 |
| Protectli     | FW6 Ver                     | [23a0c08442](https://bsd-hardware.info/?probe=23a0c08442) | Nov 12, 2022 |
| Unknown       | Unknown                     | [a2b2bb3a77](https://bsd-hardware.info/?probe=a2b2bb3a77) | Nov 11, 2022 |
| ASRock        | J4005B-ITX                  | [554b92cae5](https://bsd-hardware.info/?probe=554b92cae5) | Nov 10, 2022 |
| BESSTAR Te... | TH50                        | [1300135627](https://bsd-hardware.info/?probe=1300135627) | Nov 10, 2022 |
| Cisco         | C170 A0                     | [3ba579a78c](https://bsd-hardware.info/?probe=3ba579a78c) | Nov 10, 2022 |
| AZW           | GK55                        | [d73ef4f4fc](https://bsd-hardware.info/?probe=d73ef4f4fc) | Nov 10, 2022 |
| Dell          | 0M5DCD A00                  | [4bb9a9324b](https://bsd-hardware.info/?probe=4bb9a9324b) | Nov 10, 2022 |
| Protectli     | FW6 Ver                     | [d75162607b](https://bsd-hardware.info/?probe=d75162607b) | Nov 09, 2022 |
| Intel         | JSL MRD                     | [5800246e28](https://bsd-hardware.info/?probe=5800246e28) | Nov 08, 2022 |
| Google        | Zako                        | [5d4b53e2d4](https://bsd-hardware.info/?probe=5d4b53e2d4) | Nov 08, 2022 |
| Unknown       | Unknown                     | [31ff384824](https://bsd-hardware.info/?probe=31ff384824) | Nov 07, 2022 |
| HP            | 8768 A                      | [c8a44e84c6](https://bsd-hardware.info/?probe=c8a44e84c6) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [70e257e360](https://bsd-hardware.info/?probe=70e257e360) | Nov 06, 2022 |
| Unknown       | Unknown                     | [fed7f55a01](https://bsd-hardware.info/?probe=fed7f55a01) | Nov 06, 2022 |
| HP            | 18E7                        | [6a80fc5241](https://bsd-hardware.info/?probe=6a80fc5241) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [59b8857bba](https://bsd-hardware.info/?probe=59b8857bba) | Nov 06, 2022 |
| MSI           | H81M-P33                    | [750d2f53c7](https://bsd-hardware.info/?probe=750d2f53c7) | Nov 06, 2022 |
| ASUSTek       | P5Q-E                       | [e427ea787e](https://bsd-hardware.info/?probe=e427ea787e) | Nov 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c6abe84145](https://bsd-hardware.info/?probe=c6abe84145) | Nov 06, 2022 |
| Protectli     | FW6                         | [654e223853](https://bsd-hardware.info/?probe=654e223853) | Nov 06, 2022 |
| Unknown       | Unknown                     | [a33d1a4123](https://bsd-hardware.info/?probe=a33d1a4123) | Nov 06, 2022 |
| Unknown       | Unknown                     | [6fb650e2e8](https://bsd-hardware.info/?probe=6fb650e2e8) | Nov 06, 2022 |
| Unknown       | Unknown                     | [3771535d50](https://bsd-hardware.info/?probe=3771535d50) | Nov 06, 2022 |
| Dell          | OptiPlex 5050               | [cfd442a25d](https://bsd-hardware.info/?probe=cfd442a25d) | Nov 06, 2022 |
| Protectli     | FW4B Ver                    | [33eea3a422](https://bsd-hardware.info/?probe=33eea3a422) | Nov 05, 2022 |
| Protectli     | FW4C Ver                    | [71c0c846f1](https://bsd-hardware.info/?probe=71c0c846f1) | Nov 05, 2022 |
| Dell          | 05GD68 A00                  | [946c93ec7b](https://bsd-hardware.info/?probe=946c93ec7b) | Nov 05, 2022 |
| Unknown       | Unknown                     | [4f58f89a6e](https://bsd-hardware.info/?probe=4f58f89a6e) | Nov 04, 2022 |
| HP            | 82A2                        | [d83974a5ed](https://bsd-hardware.info/?probe=d83974a5ed) | Nov 03, 2022 |
| HP            | 339A                        | [a1e829d9d9](https://bsd-hardware.info/?probe=a1e829d9d9) | Nov 03, 2022 |
| Dell          | 05GD68 A00                  | [8e0c8344af](https://bsd-hardware.info/?probe=8e0c8344af) | Nov 03, 2022 |
| HP            | 843F                        | [f921634ea0](https://bsd-hardware.info/?probe=f921634ea0) | Nov 02, 2022 |
| HP            | 843F                        | [bba76c5ce6](https://bsd-hardware.info/?probe=bba76c5ce6) | Nov 02, 2022 |
| Dell          | 05GD68 A00                  | [23483285a8](https://bsd-hardware.info/?probe=23483285a8) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6afa103d09](https://bsd-hardware.info/?probe=6afa103d09) | Oct 31, 2022 |
| Supermicro    | X10DRU-i+                   | [1ffd63a929](https://bsd-hardware.info/?probe=1ffd63a929) | Oct 31, 2022 |
| Unknown       | Unknown                     | [c14a3eb06b](https://bsd-hardware.info/?probe=c14a3eb06b) | Oct 31, 2022 |
| MSI           | H81M-P33                    | [b67d6a7bb2](https://bsd-hardware.info/?probe=b67d6a7bb2) | Oct 30, 2022 |
| ASUSTek       | P5Q-E                       | [8161bfd24d](https://bsd-hardware.info/?probe=8161bfd24d) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a0896f17e4](https://bsd-hardware.info/?probe=a0896f17e4) | Oct 30, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | [d20bfb6d64](https://bsd-hardware.info/?probe=d20bfb6d64) | Oct 30, 2022 |
| HP            | 843B                        | [d7d572f9ad](https://bsd-hardware.info/?probe=d7d572f9ad) | Oct 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | [02d617a604](https://bsd-hardware.info/?probe=02d617a604) | Oct 29, 2022 |
| Dell          | 0XCR8D A01                  | [a019244c85](https://bsd-hardware.info/?probe=a019244c85) | Oct 29, 2022 |
| Unknown       | Unknown                     | [9a12cd02f0](https://bsd-hardware.info/?probe=9a12cd02f0) | Oct 28, 2022 |
| MSI           | B360I GMAING PRO AC         | [7287c670f0](https://bsd-hardware.info/?probe=7287c670f0) | Oct 28, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [16c226553c](https://bsd-hardware.info/?probe=16c226553c) | Oct 27, 2022 |
| Dell          | 0WMJ54 A01                  | [f89024b7be](https://bsd-hardware.info/?probe=f89024b7be) | Oct 27, 2022 |
| Protectli     | FW4B Ver                    | [766ee6f4eb](https://bsd-hardware.info/?probe=766ee6f4eb) | Oct 27, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | [f6df7bf1e8](https://bsd-hardware.info/?probe=f6df7bf1e8) | Oct 26, 2022 |
| Dell          | 05XGC8 A01                  | [97947568ee](https://bsd-hardware.info/?probe=97947568ee) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [09e5063724](https://bsd-hardware.info/?probe=09e5063724) | Oct 24, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [eea9a0bef3](https://bsd-hardware.info/?probe=eea9a0bef3) | Oct 24, 2022 |
| Intel         | DQ77MK AAG39642-500         | [0708c0f089](https://bsd-hardware.info/?probe=0708c0f089) | Oct 24, 2022 |
| Unknown       | YL-J3160L4                  | [746694bb1d](https://bsd-hardware.info/?probe=746694bb1d) | Oct 24, 2022 |
| MSI           | H81M-P33                    | [626f503cad](https://bsd-hardware.info/?probe=626f503cad) | Oct 23, 2022 |
| ASUSTek       | P5Q-E                       | [2b98739799](https://bsd-hardware.info/?probe=2b98739799) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [56dac6bc80](https://bsd-hardware.info/?probe=56dac6bc80) | Oct 23, 2022 |
| HP            | 843B                        | [9ea2590610](https://bsd-hardware.info/?probe=9ea2590610) | Oct 23, 2022 |
| Unknown       | 1.21                        | [f8a845fcda](https://bsd-hardware.info/?probe=f8a845fcda) | Oct 23, 2022 |
| Unknown       | Unknown                     | [89d0639a68](https://bsd-hardware.info/?probe=89d0639a68) | Oct 23, 2022 |
| ASRock        | B250M-HDV                   | [803b44339b](https://bsd-hardware.info/?probe=803b44339b) | Oct 22, 2022 |
| MSI           | 890GXM-G65                  | [03c116d78f](https://bsd-hardware.info/?probe=03c116d78f) | Oct 22, 2022 |
| Alienware     | 0PGRP5 A01                  | [e34219da0f](https://bsd-hardware.info/?probe=e34219da0f) | Oct 22, 2022 |
| Supermicro    | X8DTH-i/6/iF/6F             | [12f7ac40ac](https://bsd-hardware.info/?probe=12f7ac40ac) | Oct 21, 2022 |
| Dell          | 0FDY5C A00                  | [a47e59ad6b](https://bsd-hardware.info/?probe=a47e59ad6b) | Oct 21, 2022 |
| Dell          | 0FDY5C A00                  | [eb9ffe08e7](https://bsd-hardware.info/?probe=eb9ffe08e7) | Oct 21, 2022 |
| Protectli     | FW6                         | [528ef94fb5](https://bsd-hardware.info/?probe=528ef94fb5) | Oct 21, 2022 |
| Unknown       | Unknown                     | [1778396ba9](https://bsd-hardware.info/?probe=1778396ba9) | Oct 20, 2022 |
| Protectli     | FW4B Ver                    | [c75bcb519e](https://bsd-hardware.info/?probe=c75bcb519e) | Oct 18, 2022 |
| CncTion       | N5105-4L B0                 | [45d6590312](https://bsd-hardware.info/?probe=45d6590312) | Oct 18, 2022 |
| Dell          | 02K9CR A02                  | [a5cda6c49e](https://bsd-hardware.info/?probe=a5cda6c49e) | Oct 18, 2022 |
| Supermicro    | X10SLH-N6-ST031             | [2e4cd910d7](https://bsd-hardware.info/?probe=2e4cd910d7) | Oct 17, 2022 |
| Intel         | DH57DD AAE82022-202         | [01622a2528](https://bsd-hardware.info/?probe=01622a2528) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2885a5ce85](https://bsd-hardware.info/?probe=2885a5ce85) | Oct 17, 2022 |
| HP            | 1588h                       | [e78a0308c7](https://bsd-hardware.info/?probe=e78a0308c7) | Oct 16, 2022 |
| Protectli     | FW4B                        | [57ae1d8cda](https://bsd-hardware.info/?probe=57ae1d8cda) | Oct 15, 2022 |
| HP            | 8169                        | [86b1fbf917](https://bsd-hardware.info/?probe=86b1fbf917) | Oct 15, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [76a1007c46](https://bsd-hardware.info/?probe=76a1007c46) | Oct 15, 2022 |
| Protectli     | FW6 Ver                     | [55967e02f6](https://bsd-hardware.info/?probe=55967e02f6) | Oct 15, 2022 |
| TYAN Compu... | Tiger K8W Dual AMD Opter... | [bbd42243ae](https://bsd-hardware.info/?probe=bbd42243ae) | Oct 15, 2022 |
| Techvision    | TVI7309X B0                 | [b02dcbb7b5](https://bsd-hardware.info/?probe=b02dcbb7b5) | Oct 15, 2022 |
| TYAN Compu... | Tiger K8W Dual AMD Opter... | [0e9ac1e935](https://bsd-hardware.info/?probe=0e9ac1e935) | Oct 15, 2022 |
| TYAN Compu... | Intel 440BX/GX Rev. 4       | [8d99f317e4](https://bsd-hardware.info/?probe=8d99f317e4) | Oct 15, 2022 |
| Dell          | 0G1548 A00                  | [226af33d5b](https://bsd-hardware.info/?probe=226af33d5b) | Oct 15, 2022 |
| ASRock        | G41C-GS R2.0                | [06214241b3](https://bsd-hardware.info/?probe=06214241b3) | Oct 15, 2022 |
| AZW           | Green G1                    | [f6f16c5141](https://bsd-hardware.info/?probe=f6f16c5141) | Oct 15, 2022 |
| Supermicro    | X10SLL-F                    | [3b13ea475b](https://bsd-hardware.info/?probe=3b13ea475b) | Oct 14, 2022 |
| Dell          | 00V62H A00                  | [17a6b61af7](https://bsd-hardware.info/?probe=17a6b61af7) | Oct 14, 2022 |
| PC Engines    | APU2                        | [856e29140e](https://bsd-hardware.info/?probe=856e29140e) | Oct 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [10358c7207](https://bsd-hardware.info/?probe=10358c7207) | Oct 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [b20b6c7997](https://bsd-hardware.info/?probe=b20b6c7997) | Oct 13, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [0da821d451](https://bsd-hardware.info/?probe=0da821d451) | Oct 13, 2022 |
| Unknown       | Unknown                     | [7000ef7aeb](https://bsd-hardware.info/?probe=7000ef7aeb) | Oct 12, 2022 |
| Unknown       | Unknown                     | [94915735cc](https://bsd-hardware.info/?probe=94915735cc) | Oct 11, 2022 |
| MW            | GMLK-2_5G4L                 | [ff2b9a916f](https://bsd-hardware.info/?probe=ff2b9a916f) | Oct 11, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | [2cba6fbbb7](https://bsd-hardware.info/?probe=2cba6fbbb7) | Oct 11, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [4c9069df20](https://bsd-hardware.info/?probe=4c9069df20) | Oct 10, 2022 |
| HP            | 1495                        | [cfa8ab5df3](https://bsd-hardware.info/?probe=cfa8ab5df3) | Oct 10, 2022 |
| Protectli     | FW1 Ver                     | [1015ef5e66](https://bsd-hardware.info/?probe=1015ef5e66) | Oct 09, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [e08e2ca6e0](https://bsd-hardware.info/?probe=e08e2ca6e0) | Oct 09, 2022 |
| ASRock        | X399 Taichi                 | [c79fa6f001](https://bsd-hardware.info/?probe=c79fa6f001) | Oct 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [e595ade938](https://bsd-hardware.info/?probe=e595ade938) | Oct 09, 2022 |
| MiTAC         | PH11CMI                     | [71802cdcad](https://bsd-hardware.info/?probe=71802cdcad) | Oct 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [464739212c](https://bsd-hardware.info/?probe=464739212c) | Oct 08, 2022 |
| Lenovo        | ThinkCentre M72e 3664AD9    | [f6fded284d](https://bsd-hardware.info/?probe=f6fded284d) | Oct 08, 2022 |
| Unknown       | Unknown                     | [e4e47282a9](https://bsd-hardware.info/?probe=e4e47282a9) | Oct 08, 2022 |
| Techvision    | TVI7309X B0                 | [384de92279](https://bsd-hardware.info/?probe=384de92279) | Oct 07, 2022 |
| Intel         | SHARKBAY                    | [9d3eed2bec](https://bsd-hardware.info/?probe=9d3eed2bec) | Oct 07, 2022 |
| Unknown       | Unknown                     | [ad8b88d10b](https://bsd-hardware.info/?probe=ad8b88d10b) | Oct 07, 2022 |
| ASRock        | B450M-HDV                   | [84300e7dcc](https://bsd-hardware.info/?probe=84300e7dcc) | Oct 07, 2022 |
| ADI Engine... | RCC-VE                      | [f6a9012bb2](https://bsd-hardware.info/?probe=f6a9012bb2) | Oct 07, 2022 |
| Jingsha       | x79-P3 by xUz               | [7e24ab5841](https://bsd-hardware.info/?probe=7e24ab5841) | Oct 07, 2022 |
| Jingsha       | x79-P3 by xUz               | [11e04b0c73](https://bsd-hardware.info/?probe=11e04b0c73) | Oct 07, 2022 |
| Protectli     | FW4B                        | [89a0375ecb](https://bsd-hardware.info/?probe=89a0375ecb) | Oct 06, 2022 |
| Protectli     | VP4650                      | [c9f3c90f23](https://bsd-hardware.info/?probe=c9f3c90f23) | Oct 06, 2022 |
| HP            | 8299                        | [e0f84d2500](https://bsd-hardware.info/?probe=e0f84d2500) | Oct 05, 2022 |
| Dell          | 05GD68 A00                  | [ec799eed0c](https://bsd-hardware.info/?probe=ec799eed0c) | Oct 05, 2022 |
| Dell          | 0WMJ54 A00                  | [541e5011d9](https://bsd-hardware.info/?probe=541e5011d9) | Oct 04, 2022 |
| HP            | 18E7                        | [ad345682d8](https://bsd-hardware.info/?probe=ad345682d8) | Oct 04, 2022 |
| ASRock        | AM1H-ITX                    | [8123ab15ec](https://bsd-hardware.info/?probe=8123ab15ec) | Oct 03, 2022 |
| maiyunda      | www.maiyunda.com            | [d30234a34e](https://bsd-hardware.info/?probe=d30234a34e) | Oct 03, 2022 |
| Unknown       | Unknown                     | [f2647037ec](https://bsd-hardware.info/?probe=f2647037ec) | Oct 02, 2022 |
| HPE           | ProLiant ML30 Gen10         | [f1b45790d4](https://bsd-hardware.info/?probe=f1b45790d4) | Oct 02, 2022 |
| HP            | 8767 A                      | [9d98b3baa4](https://bsd-hardware.info/?probe=9d98b3baa4) | Oct 02, 2022 |
| HP            | 212B                        | [7bc6506336](https://bsd-hardware.info/?probe=7bc6506336) | Oct 01, 2022 |
| AAEON         | FWS-2350 V1.0               | [00cc54cbad](https://bsd-hardware.info/?probe=00cc54cbad) | Oct 01, 2022 |
| Unknown       | Unknown                     | [01566cd078](https://bsd-hardware.info/?probe=01566cd078) | Oct 01, 2022 |
| Dell          | 0PC5F7 A00                  | [376550557f](https://bsd-hardware.info/?probe=376550557f) | Sep 30, 2022 |
| Jingsha       | x79-P3 by xUz               | [6853ba1191](https://bsd-hardware.info/?probe=6853ba1191) | Sep 30, 2022 |
| Biostar       | N68S3B                      | [24c8fcee9a](https://bsd-hardware.info/?probe=24c8fcee9a) | Sep 29, 2022 |
| ASRock        | B450M-HDV                   | [a3e25236fc](https://bsd-hardware.info/?probe=a3e25236fc) | Sep 28, 2022 |
| Unknown       | Unknown                     | [2926e2dc6f](https://bsd-hardware.info/?probe=2926e2dc6f) | Sep 28, 2022 |
| Unknown       | Unknown                     | [c3f8e853ef](https://bsd-hardware.info/?probe=c3f8e853ef) | Sep 28, 2022 |
| Techvision    | TVI7309X B0                 | [441eb24fd2](https://bsd-hardware.info/?probe=441eb24fd2) | Sep 28, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [3234a0b453](https://bsd-hardware.info/?probe=3234a0b453) | Sep 28, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | [390f4301dd](https://bsd-hardware.info/?probe=390f4301dd) | Sep 27, 2022 |
| Intel         | DH87MC AAG74242-401         | [5e823b71da](https://bsd-hardware.info/?probe=5e823b71da) | Sep 27, 2022 |
| Supermicro    | X11SBA-LN4F                 | [4c7f997199](https://bsd-hardware.info/?probe=4c7f997199) | Sep 26, 2022 |
| Unknown       | Unknown                     | [69a8b9b8d9](https://bsd-hardware.info/?probe=69a8b9b8d9) | Sep 26, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [cfcfd2a636](https://bsd-hardware.info/?probe=cfcfd2a636) | Sep 26, 2022 |
| ASRock        | 990FX Extreme3              | [68d99cffe1](https://bsd-hardware.info/?probe=68d99cffe1) | Sep 26, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [83607fc711](https://bsd-hardware.info/?probe=83607fc711) | Sep 25, 2022 |
| HP            | 3397                        | [8b019e6a96](https://bsd-hardware.info/?probe=8b019e6a96) | Sep 25, 2022 |
| ASRock        | 990FX Extreme3              | [c81d389fd2](https://bsd-hardware.info/?probe=c81d389fd2) | Sep 25, 2022 |
| Biostar       | N68S3B                      | [59bd37df63](https://bsd-hardware.info/?probe=59bd37df63) | Sep 25, 2022 |
| MSI           | A88XM-E45                   | [d9d06daa51](https://bsd-hardware.info/?probe=d9d06daa51) | Sep 24, 2022 |
| HP            | 18E7                        | [02ac7695d7](https://bsd-hardware.info/?probe=02ac7695d7) | Sep 24, 2022 |
| Unknown       | Unknown                     | [8f42ff0969](https://bsd-hardware.info/?probe=8f42ff0969) | Sep 24, 2022 |
| Unknown       | Unknown                     | [95b1404339](https://bsd-hardware.info/?probe=95b1404339) | Sep 23, 2022 |
| Dell          | 042P49 A01                  | [13f6367ce8](https://bsd-hardware.info/?probe=13f6367ce8) | Sep 22, 2022 |
| Unknown       | Unknown                     | [b7bfcbef72](https://bsd-hardware.info/?probe=b7bfcbef72) | Sep 22, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [1a89d78fa4](https://bsd-hardware.info/?probe=1a89d78fa4) | Sep 22, 2022 |
| Unknown       | Unknown                     | [8e55c8e637](https://bsd-hardware.info/?probe=8e55c8e637) | Sep 20, 2022 |
| HP            | 1495                        | [163ac0a58b](https://bsd-hardware.info/?probe=163ac0a58b) | Sep 20, 2022 |
| Supermicro    | X9SCL/X9SCMA                | [16479f1a2c](https://bsd-hardware.info/?probe=16479f1a2c) | Sep 20, 2022 |
| Unknown       | Unknown                     | [1ceba97eb9](https://bsd-hardware.info/?probe=1ceba97eb9) | Sep 20, 2022 |
| Intel         | SHARKBAY                    | [afbedcb189](https://bsd-hardware.info/?probe=afbedcb189) | Sep 20, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [b394504429](https://bsd-hardware.info/?probe=b394504429) | Sep 19, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [d1c81ef222](https://bsd-hardware.info/?probe=d1c81ef222) | Sep 19, 2022 |
| Dell          | 01TJ2K A02                  | [b34cf533f3](https://bsd-hardware.info/?probe=b34cf533f3) | Sep 19, 2022 |
| Lenovo        | ThinkStation D10 6493WEU    | [526e5eea0b](https://bsd-hardware.info/?probe=526e5eea0b) | Sep 18, 2022 |
| Supermicro    | A2SDi-TP8F                  | [db2194c9b9](https://bsd-hardware.info/?probe=db2194c9b9) | Sep 18, 2022 |
| HP            | 213D A01                    | [6e8a38b6ca](https://bsd-hardware.info/?probe=6e8a38b6ca) | Sep 18, 2022 |
| EAGLE EYE ... | BayTrail-D Rev.00           | [261f623516](https://bsd-hardware.info/?probe=261f623516) | Sep 18, 2022 |
| CONTEC        | G1/EMB-CV1/iD2550           | [266ef0ca6a](https://bsd-hardware.info/?probe=266ef0ca6a) | Sep 18, 2022 |
| Supermicro    | A2SDi-TP8F                  | [8c67aa0f6e](https://bsd-hardware.info/?probe=8c67aa0f6e) | Sep 15, 2022 |
| Gigabyte      | H270-HD3-CF                 | [0157925fad](https://bsd-hardware.info/?probe=0157925fad) | Sep 15, 2022 |
| AZW           | Green G1                    | [1ccd8f86b3](https://bsd-hardware.info/?probe=1ccd8f86b3) | Sep 14, 2022 |
| Protectli     | FW6                         | [23227c99a0](https://bsd-hardware.info/?probe=23227c99a0) | Sep 14, 2022 |
| Dell          | 0FDY5C A00                  | [cce6101086](https://bsd-hardware.info/?probe=cce6101086) | Sep 14, 2022 |
| Techvision    | TVI7309X B0                 | [a444259756](https://bsd-hardware.info/?probe=a444259756) | Sep 14, 2022 |
| Unknown       | Unknown                     | [992ddc4118](https://bsd-hardware.info/?probe=992ddc4118) | Sep 14, 2022 |
| Intel         | D945GCLF2 AAE46416-106      | [8e2f7792eb](https://bsd-hardware.info/?probe=8e2f7792eb) | Sep 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [f023ae7ed2](https://bsd-hardware.info/?probe=f023ae7ed2) | Sep 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [baaf9cbda6](https://bsd-hardware.info/?probe=baaf9cbda6) | Sep 13, 2022 |
| Protectli     | FW4B                        | [0553a226de](https://bsd-hardware.info/?probe=0553a226de) | Sep 13, 2022 |
| Protectli     | FW4B                        | [0ccd9a9f2c](https://bsd-hardware.info/?probe=0ccd9a9f2c) | Sep 12, 2022 |
| HP            | 8054                        | [3385f78f9c](https://bsd-hardware.info/?probe=3385f78f9c) | Sep 12, 2022 |
| MSI           | H81M-E33                    | [b80a45410b](https://bsd-hardware.info/?probe=b80a45410b) | Sep 12, 2022 |
| Unknown       | Unknown                     | [700e6ba6a9](https://bsd-hardware.info/?probe=700e6ba6a9) | Sep 11, 2022 |
| MSI           | H81M-E33                    | [66d179c5f4](https://bsd-hardware.info/?probe=66d179c5f4) | Sep 11, 2022 |
| ASUSTek       | P5Q-E                       | [1cbbe33027](https://bsd-hardware.info/?probe=1cbbe33027) | Sep 11, 2022 |
| MSI           | H81M-P33                    | [3b668ace72](https://bsd-hardware.info/?probe=3b668ace72) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [62c287a993](https://bsd-hardware.info/?probe=62c287a993) | Sep 11, 2022 |
| Dell          | 0NW6H5 A00                  | [ce6906d604](https://bsd-hardware.info/?probe=ce6906d604) | Sep 10, 2022 |
| MSI           | A88XM-E45                   | [2df6d013e9](https://bsd-hardware.info/?probe=2df6d013e9) | Sep 10, 2022 |
| CONTEC        | G1/EMB-CV1/iD2550           | [0df35f9c64](https://bsd-hardware.info/?probe=0df35f9c64) | Sep 10, 2022 |
| Intel         | DH87MC AAG74242-401         | [6b449e63d3](https://bsd-hardware.info/?probe=6b449e63d3) | Sep 10, 2022 |
| AZW           | Green G1                    | [b9e82f5157](https://bsd-hardware.info/?probe=b9e82f5157) | Sep 09, 2022 |
| EAGLE EYE ... | BayTrail-D Rev.00           | [1e62e2ea85](https://bsd-hardware.info/?probe=1e62e2ea85) | Sep 09, 2022 |
| Techvision    | TVI7309X B0                 | [4e393e3814](https://bsd-hardware.info/?probe=4e393e3814) | Sep 08, 2022 |
| Protectli     | FW4B                        | [b934171c54](https://bsd-hardware.info/?probe=b934171c54) | Sep 07, 2022 |
| Techvision    | TVI7309X B0                 | [3c3c40a10f](https://bsd-hardware.info/?probe=3c3c40a10f) | Sep 07, 2022 |
| Protectli     | VP2410 10                   | [f431032a32](https://bsd-hardware.info/?probe=f431032a32) | Sep 07, 2022 |
| HP            | 1495                        | [4ba1b5820e](https://bsd-hardware.info/?probe=4ba1b5820e) | Sep 06, 2022 |
| ASRock        | 4X4-4000 Series             | [00ee0319aa](https://bsd-hardware.info/?probe=00ee0319aa) | Sep 06, 2022 |
| Unknown       | J3160-4L                    | [817b37c259](https://bsd-hardware.info/?probe=817b37c259) | Sep 06, 2022 |
| Supermicro    | X10SLH-N6-ST031             | [34bc2f5c5b](https://bsd-hardware.info/?probe=34bc2f5c5b) | Sep 04, 2022 |
| MSI           | H81M-P33                    | [3f7258c807](https://bsd-hardware.info/?probe=3f7258c807) | Sep 04, 2022 |
| ASUSTek       | P5Q-E                       | [cced3168c8](https://bsd-hardware.info/?probe=cced3168c8) | Sep 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [61b82d5ebb](https://bsd-hardware.info/?probe=61b82d5ebb) | Sep 04, 2022 |
| Protectli     | FW4B Ver                    | [a769499d94](https://bsd-hardware.info/?probe=a769499d94) | Sep 04, 2022 |
| MSI           | A68HM-E33 V2                | [0f35d398cb](https://bsd-hardware.info/?probe=0f35d398cb) | Sep 04, 2022 |
| Protectli     | FW4B                        | [86a4422a0f](https://bsd-hardware.info/?probe=86a4422a0f) | Sep 04, 2022 |
| Unknown       | Unknown                     | [4034fae93d](https://bsd-hardware.info/?probe=4034fae93d) | Sep 04, 2022 |
| Dell          | 0WMJ54 A00                  | [39ee331ecb](https://bsd-hardware.info/?probe=39ee331ecb) | Sep 03, 2022 |
| Unknown       | Unknown                     | [b2e4674180](https://bsd-hardware.info/?probe=b2e4674180) | Sep 03, 2022 |
| Protectli     | FW4B                        | [1e384b1cf6](https://bsd-hardware.info/?probe=1e384b1cf6) | Sep 02, 2022 |
| Gigabyte      | H270-HD3-CF                 | [ce9dc034c9](https://bsd-hardware.info/?probe=ce9dc034c9) | Sep 02, 2022 |
| HP            | 213D A01                    | [5e8fa931ef](https://bsd-hardware.info/?probe=5e8fa931ef) | Sep 02, 2022 |
| Supermicro    | X10SLH-N6-ST031             | [73304d07bb](https://bsd-hardware.info/?probe=73304d07bb) | Sep 01, 2022 |
| Jingsha       | x79-P3 by xUz               | [9148bf85ec](https://bsd-hardware.info/?probe=9148bf85ec) | Sep 01, 2022 |
| Unknown       | Unknown                     | [b62a001fe9](https://bsd-hardware.info/?probe=b62a001fe9) | Sep 01, 2022 |
| Dell          | 07F37C A01                  | [53de9cce89](https://bsd-hardware.info/?probe=53de9cce89) | Sep 01, 2022 |
| Intel         | MAHOBAY                     | [78b1cb4ae5](https://bsd-hardware.info/?probe=78b1cb4ae5) | Aug 31, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [0563755b0d](https://bsd-hardware.info/?probe=0563755b0d) | Aug 31, 2022 |
| Unknown       | Unknown                     | [e8259494a3](https://bsd-hardware.info/?probe=e8259494a3) | Aug 31, 2022 |
| Unknown       | Unknown                     | [98d9c506c9](https://bsd-hardware.info/?probe=98d9c506c9) | Aug 30, 2022 |
| Unknown       | Unknown                     | [6bc59f4024](https://bsd-hardware.info/?probe=6bc59f4024) | Aug 30, 2022 |
| Dell          | 0NW6H5 A00                  | [8d047e7667](https://bsd-hardware.info/?probe=8d047e7667) | Aug 29, 2022 |
| Unknown       | Unknown                     | [411daea5f8](https://bsd-hardware.info/?probe=411daea5f8) | Aug 29, 2022 |
| MW            | GMLK-2_5G4L                 | [19e3294fe9](https://bsd-hardware.info/?probe=19e3294fe9) | Aug 29, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [4d7efd6aa6](https://bsd-hardware.info/?probe=4d7efd6aa6) | Aug 28, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [079adb24f8](https://bsd-hardware.info/?probe=079adb24f8) | Aug 28, 2022 |
| MW            | GMLK-2_5G4L                 | [29d63f7027](https://bsd-hardware.info/?probe=29d63f7027) | Aug 27, 2022 |
| Dell          | 030VXY A02                  | [9acd691261](https://bsd-hardware.info/?probe=9acd691261) | Aug 26, 2022 |
| HP            | 21B4 A01                    | [93eab13f35](https://bsd-hardware.info/?probe=93eab13f35) | Aug 26, 2022 |
| Supermicro    | X10SLH-N6-ST031             | [05d009b0df](https://bsd-hardware.info/?probe=05d009b0df) | Aug 26, 2022 |
| Unknown       | YL-E3845L4-V2               | [ee6fe793f2](https://bsd-hardware.info/?probe=ee6fe793f2) | Aug 24, 2022 |
| Dell          | 04YP6J A02                  | [38269a215a](https://bsd-hardware.info/?probe=38269a215a) | Aug 24, 2022 |
| Protectli     | VP2410                      | [67a5cd38d0](https://bsd-hardware.info/?probe=67a5cd38d0) | Aug 24, 2022 |
| Dell          | 088DT1 A01                  | [55090e4971](https://bsd-hardware.info/?probe=55090e4971) | Aug 24, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | [f237a01839](https://bsd-hardware.info/?probe=f237a01839) | Aug 24, 2022 |
| Supermicro    | X11SDW-4C-TP13F             | [84a08c6936](https://bsd-hardware.info/?probe=84a08c6936) | Aug 23, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [17f4ac1979](https://bsd-hardware.info/?probe=17f4ac1979) | Aug 23, 2022 |
| Unknown       | Unknown                     | [8d3dee7258](https://bsd-hardware.info/?probe=8d3dee7258) | Aug 23, 2022 |
| Protectli     | FW4B                        | [d2dd7771d2](https://bsd-hardware.info/?probe=d2dd7771d2) | Aug 22, 2022 |
| Dell          | 0PC5F7 A00                  | [27049ee122](https://bsd-hardware.info/?probe=27049ee122) | Aug 21, 2022 |
| MSI           | H81M-P33                    | [89535fc84c](https://bsd-hardware.info/?probe=89535fc84c) | Aug 21, 2022 |
| ASUSTek       | P5Q-E                       | [ac2d88c2dd](https://bsd-hardware.info/?probe=ac2d88c2dd) | Aug 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b5786b8119](https://bsd-hardware.info/?probe=b5786b8119) | Aug 21, 2022 |
| Cisco         | ASA5525 A0                  | [5a8641fc9d](https://bsd-hardware.info/?probe=5a8641fc9d) | Aug 21, 2022 |
| Unknown       | Unknown                     | [15a2225cc6](https://bsd-hardware.info/?probe=15a2225cc6) | Aug 20, 2022 |
| Cisco         | ASA5525 A0                  | [80152a4fc3](https://bsd-hardware.info/?probe=80152a4fc3) | Aug 20, 2022 |
| ASRock        | B550 Extreme4               | [ce0d33d973](https://bsd-hardware.info/?probe=ce0d33d973) | Aug 19, 2022 |
| Protectli     | FW4B                        | [2fdd88b8b8](https://bsd-hardware.info/?probe=2fdd88b8b8) | Aug 19, 2022 |
| Dell          | 0PTTT9 A00                  | [c7490e7180](https://bsd-hardware.info/?probe=c7490e7180) | Aug 18, 2022 |
| Unknown       | Unknown                     | [52da85a309](https://bsd-hardware.info/?probe=52da85a309) | Aug 18, 2022 |
| Unknown       | Unknown                     | [029b31e61f](https://bsd-hardware.info/?probe=029b31e61f) | Aug 17, 2022 |
| CncTion       | J4125-4L-I225               | [ec4f43e1bb](https://bsd-hardware.info/?probe=ec4f43e1bb) | Aug 17, 2022 |
| Unknown       | Unknown                     | [db2cb12805](https://bsd-hardware.info/?probe=db2cb12805) | Aug 17, 2022 |
| Dell          | 0D6H9T A03                  | [16e5b72b64](https://bsd-hardware.info/?probe=16e5b72b64) | Aug 16, 2022 |
| ASRock        | B460M-HDV                   | [9b48c66296](https://bsd-hardware.info/?probe=9b48c66296) | Aug 15, 2022 |
| Dell          | 0VHWTR A02                  | [29c3379293](https://bsd-hardware.info/?probe=29c3379293) | Aug 15, 2022 |
| MSI           | H81M-P33                    | [3d0836d403](https://bsd-hardware.info/?probe=3d0836d403) | Aug 14, 2022 |
| ASUSTek       | P5Q-E                       | [c50be0ecae](https://bsd-hardware.info/?probe=c50be0ecae) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4b6ad32189](https://bsd-hardware.info/?probe=4b6ad32189) | Aug 14, 2022 |
| Dell          | 0WMJ54 A01                  | [f453f94dd3](https://bsd-hardware.info/?probe=f453f94dd3) | Aug 14, 2022 |
| MiTAC         | PH11CMI                     | [8656b8a7b9](https://bsd-hardware.info/?probe=8656b8a7b9) | Aug 14, 2022 |
| HP            | 82B4                        | [f8c65040bf](https://bsd-hardware.info/?probe=f8c65040bf) | Aug 13, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [35f0eac5f1](https://bsd-hardware.info/?probe=35f0eac5f1) | Aug 13, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [6d6e03307e](https://bsd-hardware.info/?probe=6d6e03307e) | Aug 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [5d4af4fba9](https://bsd-hardware.info/?probe=5d4af4fba9) | Aug 13, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [95c42fcc82](https://bsd-hardware.info/?probe=95c42fcc82) | Aug 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [1292c617d2](https://bsd-hardware.info/?probe=1292c617d2) | Aug 13, 2022 |
| AZW           | GK55                        | [b34aad2082](https://bsd-hardware.info/?probe=b34aad2082) | Aug 12, 2022 |
| Supermicro    | X10DRU-i+                   | [f3ca1d1814](https://bsd-hardware.info/?probe=f3ca1d1814) | Aug 12, 2022 |
| Intel         | SHARKBAY                    | [9fa2ad6213](https://bsd-hardware.info/?probe=9fa2ad6213) | Aug 12, 2022 |
| Protectli     | FW6 Ver                     | [12ec460778](https://bsd-hardware.info/?probe=12ec460778) | Aug 12, 2022 |
| ASRock        | X570 PG Velocita            | [a91ccd3112](https://bsd-hardware.info/?probe=a91ccd3112) | Aug 11, 2022 |
| Jingsha       | x79-P3 by xUz               | [8bcb2eaddc](https://bsd-hardware.info/?probe=8bcb2eaddc) | Aug 11, 2022 |
| HP            | 1495                        | [fbfa0fdedc](https://bsd-hardware.info/?probe=fbfa0fdedc) | Aug 11, 2022 |
| Dell          | 07F37C A01                  | [d263572380](https://bsd-hardware.info/?probe=d263572380) | Aug 10, 2022 |
| Jingsha       | x79-P3 by xUz               | [6fb93918f0](https://bsd-hardware.info/?probe=6fb93918f0) | Aug 10, 2022 |
| Protectli     | VP2410                      | [a9ecca1096](https://bsd-hardware.info/?probe=a9ecca1096) | Aug 09, 2022 |
| ASRock        | J3455-ITX                   | [b26884e164](https://bsd-hardware.info/?probe=b26884e164) | Aug 07, 2022 |
| Unknown       | Unknown                     | [0185519e19](https://bsd-hardware.info/?probe=0185519e19) | Aug 06, 2022 |
| ASRock        | 970A-G                      | [5014e97cb5](https://bsd-hardware.info/?probe=5014e97cb5) | Aug 06, 2022 |
| Unknown       | Unknown                     | [4444668ecb](https://bsd-hardware.info/?probe=4444668ecb) | Aug 06, 2022 |
| Protectli     | FW4B Ver                    | [67619bab07](https://bsd-hardware.info/?probe=67619bab07) | Aug 06, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [cdd6baad68](https://bsd-hardware.info/?probe=cdd6baad68) | Aug 05, 2022 |
| PC Engines    | APU2                        | [9bc1aa868e](https://bsd-hardware.info/?probe=9bc1aa868e) | Aug 05, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [850198c512](https://bsd-hardware.info/?probe=850198c512) | Aug 05, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [cddf42b097](https://bsd-hardware.info/?probe=cddf42b097) | Aug 05, 2022 |
| Unknown       | YL-E3845L4-V2               | [7b27220307](https://bsd-hardware.info/?probe=7b27220307) | Aug 04, 2022 |
| Dell          | 042P49 A01                  | [fe87e22e26](https://bsd-hardware.info/?probe=fe87e22e26) | Aug 04, 2022 |
| Dell          | 042P49 A01                  | [2980d9d398](https://bsd-hardware.info/?probe=2980d9d398) | Aug 04, 2022 |
| ASRockRack    | X470D4U                     | [a32da79434](https://bsd-hardware.info/?probe=a32da79434) | Aug 04, 2022 |
| SmbiosType... | SmbiosType2_BoardProduct... | [3c63a3a259](https://bsd-hardware.info/?probe=3c63a3a259) | Aug 03, 2022 |
| Protectli     | VP2410 10                   | [4c0ff1f949](https://bsd-hardware.info/?probe=4c0ff1f949) | Aug 03, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [d4462c2aca](https://bsd-hardware.info/?probe=d4462c2aca) | Aug 03, 2022 |
| NF792         | 1.0                         | [93f777a0ae](https://bsd-hardware.info/?probe=93f777a0ae) | Aug 02, 2022 |
| Intel         | Q3XXG4-P V1.0               | [f89554f1b3](https://bsd-hardware.info/?probe=f89554f1b3) | Aug 02, 2022 |
| Protectli     | FW6 Ver                     | [b4745f3fbf](https://bsd-hardware.info/?probe=b4745f3fbf) | Aug 01, 2022 |
| Dell          | 0GY6Y8 A03                  | [910403ba69](https://bsd-hardware.info/?probe=910403ba69) | Aug 01, 2022 |
| Dell          | 0GY6Y8 A03                  | [2257be098f](https://bsd-hardware.info/?probe=2257be098f) | Aug 01, 2022 |
| Protectli     | FW4A Ver                    | [47bd308b5f](https://bsd-hardware.info/?probe=47bd308b5f) | Jul 31, 2022 |
| Intel         | Q3XXG4-P V1.0               | [5b73e61a78](https://bsd-hardware.info/?probe=5b73e61a78) | Jul 31, 2022 |
| Unknown       | Unknown                     | [125a4a6501](https://bsd-hardware.info/?probe=125a4a6501) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [7c5137f2f8](https://bsd-hardware.info/?probe=7c5137f2f8) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [3f6e556a7c](https://bsd-hardware.info/?probe=3f6e556a7c) | Jul 30, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [0887dc2e0e](https://bsd-hardware.info/?probe=0887dc2e0e) | Jul 30, 2022 |
| Unknown       | Unknown                     | [d6920a8af5](https://bsd-hardware.info/?probe=d6920a8af5) | Jul 30, 2022 |
| Dell          | 05GD68 A00                  | [4e108a3b49](https://bsd-hardware.info/?probe=4e108a3b49) | Jul 30, 2022 |
| Intel         | D54250WYK H13922-303        | [168056c169](https://bsd-hardware.info/?probe=168056c169) | Jul 30, 2022 |
| WesternDig... | BBC 0001                    | [5673b5c8e8](https://bsd-hardware.info/?probe=5673b5c8e8) | Jul 29, 2022 |
| HP            | 213D A01                    | [c24cba449b](https://bsd-hardware.info/?probe=c24cba449b) | Jul 29, 2022 |
| Acer          | Veriton X275                | [8fdb6785a9](https://bsd-hardware.info/?probe=8fdb6785a9) | Jul 29, 2022 |
| Dell          | 040DDP A01                  | [5d4d3d7553](https://bsd-hardware.info/?probe=5d4d3d7553) | Jul 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | [cd35c4b6ce](https://bsd-hardware.info/?probe=cd35c4b6ce) | Jul 29, 2022 |
| AAEON         | MIX-TLUD1 V1.0              | [6b1ea56289](https://bsd-hardware.info/?probe=6b1ea56289) | Jul 29, 2022 |
| Dell          | 0VHWTR A02                  | [eb7ac52c45](https://bsd-hardware.info/?probe=eb7ac52c45) | Jul 28, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | [d7b0e73f03](https://bsd-hardware.info/?probe=d7b0e73f03) | Jul 27, 2022 |
| Dell          | 0T7D40 A01                  | [3db94efbf6](https://bsd-hardware.info/?probe=3db94efbf6) | Jul 27, 2022 |
| Jingsha       | x79-P3 by xUz               | [32ed0bcfa9](https://bsd-hardware.info/?probe=32ed0bcfa9) | Jul 26, 2022 |
| HP            | 18E7                        | [0d18e24e2e](https://bsd-hardware.info/?probe=0d18e24e2e) | Jul 26, 2022 |
| Dell          | 07F37C A01                  | [dfea879cdc](https://bsd-hardware.info/?probe=dfea879cdc) | Jul 26, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | [9b3459c1ec](https://bsd-hardware.info/?probe=9b3459c1ec) | Jul 25, 2022 |
| Shuttle       | FS310                       | [4dd7894e83](https://bsd-hardware.info/?probe=4dd7894e83) | Jul 25, 2022 |
| Acer          | Aspire XC-830               | [84cfd4b073](https://bsd-hardware.info/?probe=84cfd4b073) | Jul 24, 2022 |
| AAEON         | FWS-2350 V1.0               | [e16dd36daf](https://bsd-hardware.info/?probe=e16dd36daf) | Jul 24, 2022 |
| Dell          | 04Y8V0 A02                  | [4ab59b9029](https://bsd-hardware.info/?probe=4ab59b9029) | Jul 24, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [b392e9fcc9](https://bsd-hardware.info/?probe=b392e9fcc9) | Jul 23, 2022 |
| HP            | 213D A01                    | [26c8ae3969](https://bsd-hardware.info/?probe=26c8ae3969) | Jul 22, 2022 |
| Protectli     | FW4B Ver                    | [224d08a214](https://bsd-hardware.info/?probe=224d08a214) | Jul 22, 2022 |
| HP            | 82A2                        | [7ec5ec44a5](https://bsd-hardware.info/?probe=7ec5ec44a5) | Jul 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [52cc45aba9](https://bsd-hardware.info/?probe=52cc45aba9) | Jul 21, 2022 |
| Protectli     | FW6                         | [5a13dd0c28](https://bsd-hardware.info/?probe=5a13dd0c28) | Jul 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3182740b56](https://bsd-hardware.info/?probe=3182740b56) | Jul 21, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | [70c9122b95](https://bsd-hardware.info/?probe=70c9122b95) | Jul 20, 2022 |
| Unknown       | YL-E3854L4-V2               | [cd601ead3a](https://bsd-hardware.info/?probe=cd601ead3a) | Jul 20, 2022 |
| Dell          | 08HPGT A02                  | [ae260e17eb](https://bsd-hardware.info/?probe=ae260e17eb) | Jul 19, 2022 |
| Jingsha       | x79-P3 by xUz               | [ae58265601](https://bsd-hardware.info/?probe=ae58265601) | Jul 18, 2022 |
| Protectli     | FW6 Ver                     | [e4e89253c3](https://bsd-hardware.info/?probe=e4e89253c3) | Jul 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3bf44f4bb5](https://bsd-hardware.info/?probe=3bf44f4bb5) | Jul 17, 2022 |
| Lenovo        | 361A SDK0J40700 WIN 3258... | [8671985fad](https://bsd-hardware.info/?probe=8671985fad) | Jul 17, 2022 |
| Dell          | 04Y8V0 A02                  | [5bba9aafa1](https://bsd-hardware.info/?probe=5bba9aafa1) | Jul 17, 2022 |
| HP            | 1589                        | [3f9d19b372](https://bsd-hardware.info/?probe=3f9d19b372) | Jul 16, 2022 |
| Dell          | 051FJ8 A02                  | [39de8d3c92](https://bsd-hardware.info/?probe=39de8d3c92) | Jul 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [e294973f12](https://bsd-hardware.info/?probe=e294973f12) | Jul 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9771cb16c0](https://bsd-hardware.info/?probe=9771cb16c0) | Jul 15, 2022 |
| Unknown       | Unknown                     | [1058650b8e](https://bsd-hardware.info/?probe=1058650b8e) | Jul 15, 2022 |
| Unknown       | Unknown                     | [e4795fcc70](https://bsd-hardware.info/?probe=e4795fcc70) | Jul 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1e8b0433e8](https://bsd-hardware.info/?probe=1e8b0433e8) | Jul 15, 2022 |
| Dell          | 06D7TR A00                  | [e567cc10e7](https://bsd-hardware.info/?probe=e567cc10e7) | Jul 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [85a49cb7be](https://bsd-hardware.info/?probe=85a49cb7be) | Jul 14, 2022 |
| MW            | GMLK-2_5G4L                 | [300b7cfcb6](https://bsd-hardware.info/?probe=300b7cfcb6) | Jul 13, 2022 |
| Protectli     | VP2410 10                   | [ffb2821bab](https://bsd-hardware.info/?probe=ffb2821bab) | Jul 13, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | [3f5548c246](https://bsd-hardware.info/?probe=3f5548c246) | Jul 12, 2022 |
| ASRock        | X570 PG Velocita            | [ceb7ed4c1e](https://bsd-hardware.info/?probe=ceb7ed4c1e) | Jul 12, 2022 |
| PC Engines    | APU2                        | [57b035462a](https://bsd-hardware.info/?probe=57b035462a) | Jul 12, 2022 |
| Protectli     | FW2 Ver                     | [89ba2534c0](https://bsd-hardware.info/?probe=89ba2534c0) | Jul 12, 2022 |
| Unknown       | Unknown                     | [322ee9f1c9](https://bsd-hardware.info/?probe=322ee9f1c9) | Jul 11, 2022 |
| SmbiosType... | SmbiosType2_BoardProduct... | [eee15ff905](https://bsd-hardware.info/?probe=eee15ff905) | Jul 11, 2022 |
| Unknown       | Unknown                     | [abf18d0628](https://bsd-hardware.info/?probe=abf18d0628) | Jul 11, 2022 |
| Protectli     | FW6 Ver                     | [0ff1996217](https://bsd-hardware.info/?probe=0ff1996217) | Jul 11, 2022 |
| Jingsha       | x79-P3 by xUz               | [b4f18ad479](https://bsd-hardware.info/?probe=b4f18ad479) | Jul 11, 2022 |
| HP            | 1495                        | [7ed22254af](https://bsd-hardware.info/?probe=7ed22254af) | Jul 11, 2022 |
| HP            | 1495                        | [1bf0dc0f98](https://bsd-hardware.info/?probe=1bf0dc0f98) | Jul 11, 2022 |
| Protectli     | FW6                         | [cf0a97896f](https://bsd-hardware.info/?probe=cf0a97896f) | Jul 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4c74cdfb76](https://bsd-hardware.info/?probe=4c74cdfb76) | Jul 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [6edc61f549](https://bsd-hardware.info/?probe=6edc61f549) | Jul 10, 2022 |
| Jingsha       | x79-P3 by xUz               | [eec1480bc7](https://bsd-hardware.info/?probe=eec1480bc7) | Jul 10, 2022 |
| Intel         | Q3XXG4-P V1.0               | [f9226218a0](https://bsd-hardware.info/?probe=f9226218a0) | Jul 09, 2022 |
| Supermicro    | X11SBA-LN4F                 | [fc85312fc7](https://bsd-hardware.info/?probe=fc85312fc7) | Jul 08, 2022 |
| Dell          | 05GD68 A00                  | [3c9057ab65](https://bsd-hardware.info/?probe=3c9057ab65) | Jul 08, 2022 |
| Dell          | 01TJ2K A02                  | [467070c750](https://bsd-hardware.info/?probe=467070c750) | Jul 08, 2022 |
| Protectli     | VP2410                      | [e5c8ed1549](https://bsd-hardware.info/?probe=e5c8ed1549) | Jul 07, 2022 |
| ASUSTek       | PRIME A520M-A II            | [0819ecdcf9](https://bsd-hardware.info/?probe=0819ecdcf9) | Jul 07, 2022 |
| ASUSTek       | PRIME A520M-A II            | [d459d3431a](https://bsd-hardware.info/?probe=d459d3431a) | Jul 07, 2022 |
| Unknown       | YL-E3854L4-V2               | [1326524180](https://bsd-hardware.info/?probe=1326524180) | Jul 07, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5d668f86de](https://bsd-hardware.info/?probe=5d668f86de) | Jul 06, 2022 |
| MiTAC         | PH11CMI                     | [9111d63b0a](https://bsd-hardware.info/?probe=9111d63b0a) | Jul 06, 2022 |
| ASRock        | X570 PG Velocita            | [08359c2723](https://bsd-hardware.info/?probe=08359c2723) | Jul 06, 2022 |
| Protectli     | VP2410 10                   | [bc786895e5](https://bsd-hardware.info/?probe=bc786895e5) | Jul 05, 2022 |
| ASRock        | H370M-ITX/ac                | [ebc1f9cbf1](https://bsd-hardware.info/?probe=ebc1f9cbf1) | Jul 05, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [5116ea39c1](https://bsd-hardware.info/?probe=5116ea39c1) | Jul 05, 2022 |
| Protectli     | FW6E                        | [efa044fab5](https://bsd-hardware.info/?probe=efa044fab5) | Jul 05, 2022 |
| Dell          | 042P49 A01                  | [85404f4f29](https://bsd-hardware.info/?probe=85404f4f29) | Jul 04, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [041ad7f035](https://bsd-hardware.info/?probe=041ad7f035) | Jul 04, 2022 |
| ASRock        | H370M-ITX/ac                | [ce09ce2aa9](https://bsd-hardware.info/?probe=ce09ce2aa9) | Jul 04, 2022 |
| Dell          | 01TJ2K A02                  | [b9037d1fb0](https://bsd-hardware.info/?probe=b9037d1fb0) | Jul 04, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [f261de9b25](https://bsd-hardware.info/?probe=f261de9b25) | Jul 03, 2022 |
| HP            | 843F                        | [30700c4158](https://bsd-hardware.info/?probe=30700c4158) | Jul 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | [720d51613e](https://bsd-hardware.info/?probe=720d51613e) | Jul 03, 2022 |
| Unknown       | Unknown                     | [5b79558a40](https://bsd-hardware.info/?probe=5b79558a40) | Jul 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | [699fea1ac9](https://bsd-hardware.info/?probe=699fea1ac9) | Jul 02, 2022 |
| Protectli     | FW4B Ver                    | [83349fd2bf](https://bsd-hardware.info/?probe=83349fd2bf) | Jul 01, 2022 |
| Protectli     | VP2410 10                   | [7c1ae96d22](https://bsd-hardware.info/?probe=7c1ae96d22) | Jun 29, 2022 |
| PC Engines    | apu4                        | [b139faa593](https://bsd-hardware.info/?probe=b139faa593) | Jun 28, 2022 |
| ASUSTek       | GRYPHON Z87                 | [56594ec74b](https://bsd-hardware.info/?probe=56594ec74b) | Jun 28, 2022 |
| AZW           | Green G1                    | [8364810fca](https://bsd-hardware.info/?probe=8364810fca) | Jun 27, 2022 |
| AZW           | GK55                        | [82e212ab9e](https://bsd-hardware.info/?probe=82e212ab9e) | Jun 27, 2022 |
| ASUSTek       | ROG STRIX Z590-I GAMING ... | [b628bb87a6](https://bsd-hardware.info/?probe=b628bb87a6) | Jun 26, 2022 |
| Dell          | 0D6H9T A00                  | [b71ecdf543](https://bsd-hardware.info/?probe=b71ecdf543) | Jun 26, 2022 |
| Unknown       | Unknown                     | [3d2f470da6](https://bsd-hardware.info/?probe=3d2f470da6) | Jun 24, 2022 |
| SmbiosType... | SmbiosType2_BoardProduct... | [d80af3d3b1](https://bsd-hardware.info/?probe=d80af3d3b1) | Jun 24, 2022 |
| ALLEGIANCE... | X79 V3.3F                   | [190560a4f4](https://bsd-hardware.info/?probe=190560a4f4) | Jun 23, 2022 |
| Lenovo        | 0B98401 PRO                 | [ef2ff887f3](https://bsd-hardware.info/?probe=ef2ff887f3) | Jun 22, 2022 |
| HP            | 8906 SMVB                   | [c7ea52a92e](https://bsd-hardware.info/?probe=c7ea52a92e) | Jun 22, 2022 |
| Protectli     | FW6 Ver                     | [b0a265f65f](https://bsd-hardware.info/?probe=b0a265f65f) | Jun 21, 2022 |
| Protectli     | FW4B Ver                    | [0efa4b4878](https://bsd-hardware.info/?probe=0efa4b4878) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [081b5f8bec](https://bsd-hardware.info/?probe=081b5f8bec) | Jun 20, 2022 |
| Protectli     | FW4B Ver                    | [24d72267be](https://bsd-hardware.info/?probe=24d72267be) | Jun 19, 2022 |
| Dell          | 0WMJ54 A01                  | [78716ab7b5](https://bsd-hardware.info/?probe=78716ab7b5) | Jun 19, 2022 |
| Protectli     | FW6D                        | [04f0fbbc41](https://bsd-hardware.info/?probe=04f0fbbc41) | Jun 19, 2022 |
| TYAN Compu... | Tiger K8W Dual AMD Opter... | [3129273bd4](https://bsd-hardware.info/?probe=3129273bd4) | Jun 18, 2022 |
| MSI           | B360I GMAING PRO AC         | [9d92cd0269](https://bsd-hardware.info/?probe=9d92cd0269) | Jun 18, 2022 |
| Unknown       | YL-E3854L4-V2               | [54003932e8](https://bsd-hardware.info/?probe=54003932e8) | Jun 17, 2022 |
| HP            | 2B29                        | [e8c355314e](https://bsd-hardware.info/?probe=e8c355314e) | Jun 17, 2022 |
| HP            | 1589                        | [3765f1cb09](https://bsd-hardware.info/?probe=3765f1cb09) | Jun 17, 2022 |
| Biostar       | H61MGC                      | [c3328d9806](https://bsd-hardware.info/?probe=c3328d9806) | Jun 17, 2022 |
| Gigabyte      | C1007UN-D                   | [a8d5fadd58](https://bsd-hardware.info/?probe=a8d5fadd58) | Jun 15, 2022 |
| Protectli     | FW6 Ver                     | [a9d98de213](https://bsd-hardware.info/?probe=a9d98de213) | Jun 15, 2022 |
| HP            | 83EE                        | [34235b8478](https://bsd-hardware.info/?probe=34235b8478) | Jun 14, 2022 |
| Supermicro    | X11SDV-8C-TP8F              | [5a180cc6aa](https://bsd-hardware.info/?probe=5a180cc6aa) | Jun 14, 2022 |
| Dell          | 0F6X5P A00                  | [fcadb83b9e](https://bsd-hardware.info/?probe=fcadb83b9e) | Jun 14, 2022 |
| Dell          | 07T4MC A02                  | [5b60dfdcc1](https://bsd-hardware.info/?probe=5b60dfdcc1) | Jun 13, 2022 |
| Unknown       | EMB-B75A                    | [a2adb81748](https://bsd-hardware.info/?probe=a2adb81748) | Jun 13, 2022 |
| Dell          | 0NC2VH A01                  | [29a12ab775](https://bsd-hardware.info/?probe=29a12ab775) | Jun 13, 2022 |
| Supermicro    | X9SCL/X9SCMA                | [7b19e64a0e](https://bsd-hardware.info/?probe=7b19e64a0e) | Jun 13, 2022 |
| Dell          | 0HMF7C A01                  | [ad0f6d4b31](https://bsd-hardware.info/?probe=ad0f6d4b31) | Jun 13, 2022 |
| Supermicro    | X9DR3-F                     | [d81151c0e8](https://bsd-hardware.info/?probe=d81151c0e8) | Jun 12, 2022 |
| ASUSTek       | Maximus VII FORMULA         | [5215d1ebb8](https://bsd-hardware.info/?probe=5215d1ebb8) | Jun 12, 2022 |
| Gigabyte      | H110M-M2-CF                 | [09d6e71897](https://bsd-hardware.info/?probe=09d6e71897) | Jun 12, 2022 |
| ASRock        | B550M Steel Legend          | [c6824c4f4a](https://bsd-hardware.info/?probe=c6824c4f4a) | Jun 11, 2022 |
| ASRock        | B450 Gaming K4              | [a03ff6ad9e](https://bsd-hardware.info/?probe=a03ff6ad9e) | Jun 10, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [65540f1006](https://bsd-hardware.info/?probe=65540f1006) | Jun 09, 2022 |
| Protectli     | VP2410 10                   | [61442e8deb](https://bsd-hardware.info/?probe=61442e8deb) | Jun 09, 2022 |
| HP            | 1495                        | [ce6fa257fd](https://bsd-hardware.info/?probe=ce6fa257fd) | Jun 08, 2022 |
| AZW           | Green G1                    | [0443d21ba3](https://bsd-hardware.info/?probe=0443d21ba3) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d54c86624e](https://bsd-hardware.info/?probe=d54c86624e) | Jun 08, 2022 |
| Gigabyte      | Z390 UD                     | [2e5eb217b5](https://bsd-hardware.info/?probe=2e5eb217b5) | Jun 08, 2022 |
| ADI           | MinnowBoard Turbot          | [917e897373](https://bsd-hardware.info/?probe=917e897373) | Jun 07, 2022 |
| Protectli     | FW6                         | [85d825c3a6](https://bsd-hardware.info/?probe=85d825c3a6) | Jun 07, 2022 |
| Dell          | 0VHWTR A02                  | [af39fe65b7](https://bsd-hardware.info/?probe=af39fe65b7) | Jun 07, 2022 |
| Apple         | MacPro4,1                   | [65380f3847](https://bsd-hardware.info/?probe=65380f3847) | Jun 06, 2022 |
| Dell          | 0WMJ54 A00                  | [40510e311b](https://bsd-hardware.info/?probe=40510e311b) | Jun 06, 2022 |
| MSI           | Z590 PRO WIFI               | [29b410eeb6](https://bsd-hardware.info/?probe=29b410eeb6) | Jun 06, 2022 |
| Unknown       | Unknown                     | [03a994458a](https://bsd-hardware.info/?probe=03a994458a) | Jun 05, 2022 |
| Unknown       | Unknown                     | [2de97a7ff6](https://bsd-hardware.info/?probe=2de97a7ff6) | Jun 05, 2022 |
| Biostar       | Hi-Fi B85N 3D               | [b88e0faba8](https://bsd-hardware.info/?probe=b88e0faba8) | Jun 05, 2022 |
| Gigabyte      | H110M-M2-CF                 | [018c0120f3](https://bsd-hardware.info/?probe=018c0120f3) | Jun 05, 2022 |
| Dell          | 0WR7PY A01                  | [8fd5398904](https://bsd-hardware.info/?probe=8fd5398904) | Jun 04, 2022 |
| Unknown       | Unknown                     | [6449ac13c1](https://bsd-hardware.info/?probe=6449ac13c1) | Jun 03, 2022 |
| MSI           | B360I GMAING PRO AC         | [8754cf67fc](https://bsd-hardware.info/?probe=8754cf67fc) | Jun 03, 2022 |
| Protectli     | FW4B Ver                    | [d55600f2bf](https://bsd-hardware.info/?probe=d55600f2bf) | Jun 02, 2022 |
| Dell          | 05GD68 A00                  | [207c4d519b](https://bsd-hardware.info/?probe=207c4d519b) | Jun 02, 2022 |
| Lenovo        | SHARKBAY 0B98405 STD        | [7820a44cbe](https://bsd-hardware.info/?probe=7820a44cbe) | Jun 01, 2022 |
| Dell          | 0WR7PY A01                  | [4154fda8ab](https://bsd-hardware.info/?probe=4154fda8ab) | May 31, 2022 |
| ASRock        | B450M Pro4                  | [3e62c80025](https://bsd-hardware.info/?probe=3e62c80025) | May 31, 2022 |
| NF-M2S        | ABIT                        | [bef9700756](https://bsd-hardware.info/?probe=bef9700756) | May 31, 2022 |
| Dell          | 05GD68 A00                  | [364b3d55e4](https://bsd-hardware.info/?probe=364b3d55e4) | May 31, 2022 |
| Supermicro    | X9SCL/X9SCM                 | [97f4daf2ad](https://bsd-hardware.info/?probe=97f4daf2ad) | May 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [486ad2acae](https://bsd-hardware.info/?probe=486ad2acae) | May 30, 2022 |
| Protectli     | FW4B                        | [2b833c65c0](https://bsd-hardware.info/?probe=2b833c65c0) | May 29, 2022 |
| Protectli     | VP2410 10                   | [0f275a65af](https://bsd-hardware.info/?probe=0f275a65af) | May 29, 2022 |
| Unknown       | Unknown                     | [90b27f0ac1](https://bsd-hardware.info/?probe=90b27f0ac1) | May 29, 2022 |
| HP            | 1495                        | [e7fcfd6634](https://bsd-hardware.info/?probe=e7fcfd6634) | May 29, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [479e0f44cd](https://bsd-hardware.info/?probe=479e0f44cd) | May 29, 2022 |
| ASUSTek       | P5Q-E                       | [cf67e4079f](https://bsd-hardware.info/?probe=cf67e4079f) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8ebd281f5f](https://bsd-hardware.info/?probe=8ebd281f5f) | May 29, 2022 |
| MSI           | H81M-P33                    | [ab2181e1b4](https://bsd-hardware.info/?probe=ab2181e1b4) | May 29, 2022 |
| Protectli     | FW6                         | [902d82819e](https://bsd-hardware.info/?probe=902d82819e) | May 29, 2022 |
| Dell          | 018D1Y A00                  | [cb624b7a18](https://bsd-hardware.info/?probe=cb624b7a18) | May 29, 2022 |
| Intel         | S1200KP AAG34877-201        | [f6bbaffaeb](https://bsd-hardware.info/?probe=f6bbaffaeb) | May 29, 2022 |
| ASUSTek       | PRIME Z590-P                | [3ef083287f](https://bsd-hardware.info/?probe=3ef083287f) | May 28, 2022 |
| ASUSTek       | PRIME Z590-P                | [53cb90d2b7](https://bsd-hardware.info/?probe=53cb90d2b7) | May 28, 2022 |
| ASUSTek       | P5QL-VM DO                  | [33145067d8](https://bsd-hardware.info/?probe=33145067d8) | May 28, 2022 |
| Intel         | S1200KP AAG34877-201        | [5e08455bea](https://bsd-hardware.info/?probe=5e08455bea) | May 28, 2022 |
| Lenovo        | MAHOBAY NOK                 | [d134ba2206](https://bsd-hardware.info/?probe=d134ba2206) | May 28, 2022 |
| Dell          | 0WR7PY A03                  | [0ba89b7a25](https://bsd-hardware.info/?probe=0ba89b7a25) | May 28, 2022 |
| Dell          | 06D7TR A00                  | [9c70320d7f](https://bsd-hardware.info/?probe=9c70320d7f) | May 27, 2022 |
| Unknown       | Unknown                     | [4e15ce78c8](https://bsd-hardware.info/?probe=4e15ce78c8) | May 26, 2022 |
| Dell          | 0VHWTR A02                  | [51c560673e](https://bsd-hardware.info/?probe=51c560673e) | May 26, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [6906c16701](https://bsd-hardware.info/?probe=6906c16701) | May 26, 2022 |
| HP            | 158A                        | [883958cd36](https://bsd-hardware.info/?probe=883958cd36) | May 25, 2022 |
| Unknown       | Unknown                     | [78d1ad4565](https://bsd-hardware.info/?probe=78d1ad4565) | May 25, 2022 |
| Unknown       | Unknown                     | [b1f95e9759](https://bsd-hardware.info/?probe=b1f95e9759) | May 25, 2022 |
| BCM Advanc... | MX57QM B1                   | [54bafab9d8](https://bsd-hardware.info/?probe=54bafab9d8) | May 25, 2022 |
| Protectli     | FW6 Ver                     | [82b16236c3](https://bsd-hardware.info/?probe=82b16236c3) | May 25, 2022 |
| Intel         | Q3XXG4-P V1.0               | [4b97b0c947](https://bsd-hardware.info/?probe=4b97b0c947) | May 25, 2022 |
| Supermicro    | X10SDV-8C-TLN4F             | [4d5f6d3aa1](https://bsd-hardware.info/?probe=4d5f6d3aa1) | May 24, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [db99798754](https://bsd-hardware.info/?probe=db99798754) | May 24, 2022 |
| Protectli     | FW4B Ver                    | [c7ff34d878](https://bsd-hardware.info/?probe=c7ff34d878) | May 24, 2022 |
| Unknown       | Unknown                     | [3307493f4f](https://bsd-hardware.info/?probe=3307493f4f) | May 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a74913bffa](https://bsd-hardware.info/?probe=a74913bffa) | May 23, 2022 |
| MSI           | H81M-P33                    | [d5a0fd71f2](https://bsd-hardware.info/?probe=d5a0fd71f2) | May 22, 2022 |
| ASUSTek       | P5Q-E                       | [2b93a0b59f](https://bsd-hardware.info/?probe=2b93a0b59f) | May 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [becc2fddbd](https://bsd-hardware.info/?probe=becc2fddbd) | May 22, 2022 |
| Dell          | 06D7TR A00                  | [c87e967424](https://bsd-hardware.info/?probe=c87e967424) | May 22, 2022 |
| Unknown       | Unknown                     | [796fe84e29](https://bsd-hardware.info/?probe=796fe84e29) | May 21, 2022 |
| Protectli     | FW4B Ver                    | [e1121aa6ec](https://bsd-hardware.info/?probe=e1121aa6ec) | May 21, 2022 |
| Dell          | 0WR7PY A01                  | [357e1739ca](https://bsd-hardware.info/?probe=357e1739ca) | May 21, 2022 |
| HP            | 843F                        | [5321d06a75](https://bsd-hardware.info/?probe=5321d06a75) | May 20, 2022 |
| HP            | 8767 A                      | [ac8a395a20](https://bsd-hardware.info/?probe=ac8a395a20) | May 20, 2022 |
| Protectli     | VP2410 10                   | [ce636a7fbe](https://bsd-hardware.info/?probe=ce636a7fbe) | May 20, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [819bed6cfb](https://bsd-hardware.info/?probe=819bed6cfb) | May 19, 2022 |
| Dell          | 042P49 A01                  | [195d06f6c7](https://bsd-hardware.info/?probe=195d06f6c7) | May 19, 2022 |
| Dell          | 042P49 A01                  | [901a883013](https://bsd-hardware.info/?probe=901a883013) | May 19, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [9c459aae41](https://bsd-hardware.info/?probe=9c459aae41) | May 19, 2022 |
| MSI           | K9N6PGM2-V2                 | [d5a6eba10b](https://bsd-hardware.info/?probe=d5a6eba10b) | May 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [37ed1733b4](https://bsd-hardware.info/?probe=37ed1733b4) | May 16, 2022 |
| HP            | 3397                        | [11269254e4](https://bsd-hardware.info/?probe=11269254e4) | May 16, 2022 |
| Unknown       | Unknown                     | [0c224d66be](https://bsd-hardware.info/?probe=0c224d66be) | May 15, 2022 |
| Protectli     | FW4A Ver                    | [2188b1004e](https://bsd-hardware.info/?probe=2188b1004e) | May 15, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [db440da034](https://bsd-hardware.info/?probe=db440da034) | May 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [35ae334ef4](https://bsd-hardware.info/?probe=35ae334ef4) | May 14, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [3d0599f15d](https://bsd-hardware.info/?probe=3d0599f15d) | May 14, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [eba3ba986d](https://bsd-hardware.info/?probe=eba3ba986d) | May 14, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [6fc43c37e6](https://bsd-hardware.info/?probe=6fc43c37e6) | May 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [6a9177eef7](https://bsd-hardware.info/?probe=6a9177eef7) | May 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [11034dd80f](https://bsd-hardware.info/?probe=11034dd80f) | May 13, 2022 |
| Protectli     | FW2B Ver                    | [99ac04d77b](https://bsd-hardware.info/?probe=99ac04d77b) | May 12, 2022 |
| Protectli     | FW4B Ver                    | [045efeba21](https://bsd-hardware.info/?probe=045efeba21) | May 12, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [abdd886f42](https://bsd-hardware.info/?probe=abdd886f42) | May 12, 2022 |
| Dell          | 0WMJ54 A00                  | [e0cc5006c2](https://bsd-hardware.info/?probe=e0cc5006c2) | May 11, 2022 |
| Dell          | 07T4MC A02                  | [38bdad88cc](https://bsd-hardware.info/?probe=38bdad88cc) | May 11, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [62c634b13e](https://bsd-hardware.info/?probe=62c634b13e) | May 11, 2022 |
| JGINYUE       | B85I PLUS V1.0              | [55e9734c09](https://bsd-hardware.info/?probe=55e9734c09) | May 10, 2022 |
| Protectli     | FW6D                        | [a1390bbbea](https://bsd-hardware.info/?probe=a1390bbbea) | May 10, 2022 |
| ASUSTek       | PRIME A320M-K               | [ffb2587425](https://bsd-hardware.info/?probe=ffb2587425) | May 10, 2022 |
| ASUSTek       | PRIME A320M-K               | [fe1055a1c3](https://bsd-hardware.info/?probe=fe1055a1c3) | May 09, 2022 |
| HP            | 802E                        | [8de7dc0ac0](https://bsd-hardware.info/?probe=8de7dc0ac0) | May 08, 2022 |
| ASUSTek       | P5K-E                       | [fe9b1ec1cf](https://bsd-hardware.info/?probe=fe9b1ec1cf) | May 07, 2022 |
| Protectli     | FW4B Ver                    | [c6b6718765](https://bsd-hardware.info/?probe=c6b6718765) | May 07, 2022 |
| Dell          | 0D6H9T A03                  | [74b30f3577](https://bsd-hardware.info/?probe=74b30f3577) | May 07, 2022 |
| AZW           | GK55                        | [4d1aea90c4](https://bsd-hardware.info/?probe=4d1aea90c4) | May 07, 2022 |
| HP            | 8054                        | [6c53f040f5](https://bsd-hardware.info/?probe=6c53f040f5) | May 06, 2022 |
| Dell          | 0Y7WYT A00                  | [76674e4d62](https://bsd-hardware.info/?probe=76674e4d62) | May 06, 2022 |
| Protectli     | FW2B Ver                    | [6c7485ba6b](https://bsd-hardware.info/?probe=6c7485ba6b) | May 06, 2022 |
| Unknown       | J3160-4L                    | [13815ff079](https://bsd-hardware.info/?probe=13815ff079) | May 06, 2022 |
| Supermicro    | X7SPA-HF                    | [990036445e](https://bsd-hardware.info/?probe=990036445e) | May 05, 2022 |
| Protectli     | VP2410                      | [d80da79148](https://bsd-hardware.info/?probe=d80da79148) | May 05, 2022 |
| Protectli     | FW4B Ver                    | [d4606bfb1a](https://bsd-hardware.info/?probe=d4606bfb1a) | May 04, 2022 |
| Protectli     | FW2B Ver                    | [632c881ec8](https://bsd-hardware.info/?probe=632c881ec8) | May 04, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [54ead4b762](https://bsd-hardware.info/?probe=54ead4b762) | May 03, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | [441a5f4a89](https://bsd-hardware.info/?probe=441a5f4a89) | May 03, 2022 |
| Intel         | Q3XXG4-P                    | [ed04988a23](https://bsd-hardware.info/?probe=ed04988a23) | May 03, 2022 |
| Supermicro    | X9SCL/X9SCMA                | [478294cdd3](https://bsd-hardware.info/?probe=478294cdd3) | May 02, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | [6ccb91cdfe](https://bsd-hardware.info/?probe=6ccb91cdfe) | May 01, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | [46c2b63c32](https://bsd-hardware.info/?probe=46c2b63c32) | May 01, 2022 |
| Unknown       | J3160-4L                    | [7ceaeb49f9](https://bsd-hardware.info/?probe=7ceaeb49f9) | May 01, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [a8c820c8c2](https://bsd-hardware.info/?probe=a8c820c8c2) | May 01, 2022 |
| MSI           | 2AE0                        | [9ff97b3d86](https://bsd-hardware.info/?probe=9ff97b3d86) | Apr 30, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [e16c0616d6](https://bsd-hardware.info/?probe=e16c0616d6) | Apr 30, 2022 |
| HP            | 1588h                       | [51ce2c6d49](https://bsd-hardware.info/?probe=51ce2c6d49) | Apr 28, 2022 |
| Protectli     | FW6 Ver                     | [2bd964cc84](https://bsd-hardware.info/?probe=2bd964cc84) | Apr 28, 2022 |
| Jingsha       | x79-P3 by xUz               | [337d593ce0](https://bsd-hardware.info/?probe=337d593ce0) | Apr 28, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [c1df1360a2](https://bsd-hardware.info/?probe=c1df1360a2) | Apr 28, 2022 |
| MSI           | MS-7C37                     | [aaab7cf22a](https://bsd-hardware.info/?probe=aaab7cf22a) | Apr 28, 2022 |
| Supermicro    | X9SCL/X9SCMA                | [0d32ec9fe4](https://bsd-hardware.info/?probe=0d32ec9fe4) | Apr 27, 2022 |
| Supermicro    | X8SIL                       | [ea89820a66](https://bsd-hardware.info/?probe=ea89820a66) | Apr 27, 2022 |
| Protectli     | VP2410                      | [481fce8e01](https://bsd-hardware.info/?probe=481fce8e01) | Apr 26, 2022 |
| Protectli     | FW6 Ver                     | [8d2ca89ae5](https://bsd-hardware.info/?probe=8d2ca89ae5) | Apr 26, 2022 |
| PC Engines    | apu4                        | [2de45511cd](https://bsd-hardware.info/?probe=2de45511cd) | Apr 24, 2022 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | [66f185a3e5](https://bsd-hardware.info/?probe=66f185a3e5) | Apr 23, 2022 |
| Supermicro    | X9SCL/X9SCM                 | [947038b1f9](https://bsd-hardware.info/?probe=947038b1f9) | Apr 22, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [2fd6d176ce](https://bsd-hardware.info/?probe=2fd6d176ce) | Apr 21, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [9853d461a3](https://bsd-hardware.info/?probe=9853d461a3) | Apr 20, 2022 |
| Protectli     | FW4B Ver                    | [da5f95b60d](https://bsd-hardware.info/?probe=da5f95b60d) | Apr 20, 2022 |
| Protectli     | FW4B Ver                    | [c0c3696eab](https://bsd-hardware.info/?probe=c0c3696eab) | Apr 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6fc3367b15](https://bsd-hardware.info/?probe=6fc3367b15) | Apr 19, 2022 |
| Unknown       | YL-SKUL6                    | [8e2a35a0c8](https://bsd-hardware.info/?probe=8e2a35a0c8) | Apr 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b16f95dfea](https://bsd-hardware.info/?probe=b16f95dfea) | Apr 18, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [bd82ff2e7e](https://bsd-hardware.info/?probe=bd82ff2e7e) | Apr 18, 2022 |
| Dell          | 0PC5F7 A02                  | [58b39b90ba](https://bsd-hardware.info/?probe=58b39b90ba) | Apr 17, 2022 |
| Protectli     | FW6                         | [6f77a10d74](https://bsd-hardware.info/?probe=6f77a10d74) | Apr 16, 2022 |
| Protectli     | FW6 Ver                     | [a9702df869](https://bsd-hardware.info/?probe=a9702df869) | Apr 16, 2022 |
| Dell          | 0Y7WYT A00                  | [399a4fb92e](https://bsd-hardware.info/?probe=399a4fb92e) | Apr 15, 2022 |
| Protectli     | FW1 Ver                     | [09f1805532](https://bsd-hardware.info/?probe=09f1805532) | Apr 15, 2022 |
| Dell          | 0J3C2F A00                  | [8188392376](https://bsd-hardware.info/?probe=8188392376) | Apr 14, 2022 |
| Intel         | CRESCENTBAY                 | [7810c76897](https://bsd-hardware.info/?probe=7810c76897) | Apr 14, 2022 |
| Acer          | Veriton X275                | [06390b6cb1](https://bsd-hardware.info/?probe=06390b6cb1) | Apr 13, 2022 |
| Dell          | 04JGCK A01                  | [c3d7d0828b](https://bsd-hardware.info/?probe=c3d7d0828b) | Apr 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [f6bc20d345](https://bsd-hardware.info/?probe=f6bc20d345) | Apr 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [bb9129d4df](https://bsd-hardware.info/?probe=bb9129d4df) | Apr 13, 2022 |
| MW            | GMLK-2_5G4L                 | [fd04d22de9](https://bsd-hardware.info/?probe=fd04d22de9) | Apr 13, 2022 |
| Alienware     | 0KM92T A00                  | [e96f2905eb](https://bsd-hardware.info/?probe=e96f2905eb) | Apr 13, 2022 |
| ASUSTek       | Maximus VIII HERO           | [c776760a11](https://bsd-hardware.info/?probe=c776760a11) | Apr 13, 2022 |
| Dell          | 0J3C2F A00                  | [b875a50291](https://bsd-hardware.info/?probe=b875a50291) | Apr 12, 2022 |
| Dell          | 0Y56T3 A00                  | [d9d86d5bfd](https://bsd-hardware.info/?probe=d9d86d5bfd) | Apr 12, 2022 |
| Intel         | DH67CL AAG10212-205         | [ecbb820987](https://bsd-hardware.info/?probe=ecbb820987) | Apr 12, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | [4a23ea31be](https://bsd-hardware.info/?probe=4a23ea31be) | Apr 11, 2022 |
| Datto         | SSD                         | [f69d873f87](https://bsd-hardware.info/?probe=f69d873f87) | Apr 11, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [39ad080dfb](https://bsd-hardware.info/?probe=39ad080dfb) | Apr 11, 2022 |
| Dell          | 04YP6J A02                  | [f638ef3cbe](https://bsd-hardware.info/?probe=f638ef3cbe) | Apr 11, 2022 |
| Datto         | SSD                         | [6cd7c93838](https://bsd-hardware.info/?probe=6cd7c93838) | Apr 10, 2022 |
| Dell          | 0PC5F7 A02                  | [6c09c89949](https://bsd-hardware.info/?probe=6c09c89949) | Apr 10, 2022 |
| MSI           | H81M-P33                    | [52abbcbc5b](https://bsd-hardware.info/?probe=52abbcbc5b) | Apr 10, 2022 |
| ASUSTek       | P5Q-E                       | [0cbb5faa2e](https://bsd-hardware.info/?probe=0cbb5faa2e) | Apr 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5d759d6436](https://bsd-hardware.info/?probe=5d759d6436) | Apr 10, 2022 |
| Protectli     | FW4B Ver                    | [7b790f0366](https://bsd-hardware.info/?probe=7b790f0366) | Apr 10, 2022 |
| Intel         | DH67CL AAG10212-205         | [de2cd29be6](https://bsd-hardware.info/?probe=de2cd29be6) | Apr 10, 2022 |
| Intel         | DH67BL AAG10189-211         | [2a03c05cce](https://bsd-hardware.info/?probe=2a03c05cce) | Apr 10, 2022 |
| Protectli     | FW6E                        | [0a529f5f09](https://bsd-hardware.info/?probe=0a529f5f09) | Apr 10, 2022 |
| PC Engines    | APU2                        | [074d4aa53c](https://bsd-hardware.info/?probe=074d4aa53c) | Apr 10, 2022 |
| Intel         | DH61CR AAG14064-204         | [fa4b6b0257](https://bsd-hardware.info/?probe=fa4b6b0257) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-205         | [4436915ba0](https://bsd-hardware.info/?probe=4436915ba0) | Apr 09, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [844323ad2d](https://bsd-hardware.info/?probe=844323ad2d) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-210         | [a01376dfc5](https://bsd-hardware.info/?probe=a01376dfc5) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-205         | [85a5d08117](https://bsd-hardware.info/?probe=85a5d08117) | Apr 09, 2022 |
| Dell          | 0T7D40 A01                  | [ef224ffce0](https://bsd-hardware.info/?probe=ef224ffce0) | Apr 09, 2022 |
| Intel         | DH67BL AAG10189-211         | [689ff6c484](https://bsd-hardware.info/?probe=689ff6c484) | Apr 09, 2022 |
| Protectli     | VP2410 10                   | [e128e81c96](https://bsd-hardware.info/?probe=e128e81c96) | Apr 09, 2022 |
| ASRock        | X570 Steel Legend WiFi a... | [703e042cfe](https://bsd-hardware.info/?probe=703e042cfe) | Apr 09, 2022 |
| Dell          | 0D6H9T A00                  | [e58bc4937d](https://bsd-hardware.info/?probe=e58bc4937d) | Apr 09, 2022 |
| Intel         | DH55TC AAE70932-302         | [b9a45002ae](https://bsd-hardware.info/?probe=b9a45002ae) | Apr 09, 2022 |
| Intel         | DH67CL AAG10212-205         | [68f10ed8de](https://bsd-hardware.info/?probe=68f10ed8de) | Apr 09, 2022 |
| Intel         | DH67CL AAG10212-205         | [092643d1c3](https://bsd-hardware.info/?probe=092643d1c3) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-205         | [02b581994b](https://bsd-hardware.info/?probe=02b581994b) | Apr 08, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [840805d1fa](https://bsd-hardware.info/?probe=840805d1fa) | Apr 08, 2022 |
| Protectli     | FW2 Ver                     | [9f73c4b7e5](https://bsd-hardware.info/?probe=9f73c4b7e5) | Apr 08, 2022 |
| Unknown       | J3160-4L                    | [e97a752648](https://bsd-hardware.info/?probe=e97a752648) | Apr 08, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [50d12f98fc](https://bsd-hardware.info/?probe=50d12f98fc) | Apr 08, 2022 |
| ASRock        | B550M Steel Legend          | [ad0ab01ca8](https://bsd-hardware.info/?probe=ad0ab01ca8) | Apr 08, 2022 |
| Protectli     | FW6 Ver                     | [b3acaf2f6d](https://bsd-hardware.info/?probe=b3acaf2f6d) | Apr 07, 2022 |
| Protectli     | VP2410 10                   | [d24fcb00e2](https://bsd-hardware.info/?probe=d24fcb00e2) | Apr 07, 2022 |
| Unknown       | Unknown                     | [7d4820d983](https://bsd-hardware.info/?probe=7d4820d983) | Apr 07, 2022 |
| Protectli     | VP2410 10                   | [a083074e9a](https://bsd-hardware.info/?probe=a083074e9a) | Apr 07, 2022 |
| Acer          | Veriton X275                | [412c31c1a9](https://bsd-hardware.info/?probe=412c31c1a9) | Apr 07, 2022 |
| Protectli     | FW1 Ver                     | [183df9ebd2](https://bsd-hardware.info/?probe=183df9ebd2) | Apr 07, 2022 |
| MSI           | A78M-E45                    | [6db716258a](https://bsd-hardware.info/?probe=6db716258a) | Apr 07, 2022 |
| Supermicro    | X10SLL-F                    | [6e07653d46](https://bsd-hardware.info/?probe=6e07653d46) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2d04e83ea4](https://bsd-hardware.info/?probe=2d04e83ea4) | Apr 06, 2022 |
| ASRock        | AM1H-ITX                    | [5556bf474c](https://bsd-hardware.info/?probe=5556bf474c) | Apr 06, 2022 |
| Protectli     | FW1 Ver                     | [a3af5d0e88](https://bsd-hardware.info/?probe=a3af5d0e88) | Apr 06, 2022 |
| Unknown       | Unknown                     | [7644cc6811](https://bsd-hardware.info/?probe=7644cc6811) | Apr 06, 2022 |
| Dell          | 0PC5F7 A02                  | [e77c0c0cf7](https://bsd-hardware.info/?probe=e77c0c0cf7) | Apr 06, 2022 |
| Supermicro    | X9SAE                       | [a800ac2857](https://bsd-hardware.info/?probe=a800ac2857) | Apr 06, 2022 |
| HP            | 1998                        | [bf9a8c9cb2](https://bsd-hardware.info/?probe=bf9a8c9cb2) | Apr 06, 2022 |
| MSI           | 990FXA-GD80                 | [1581e2f112](https://bsd-hardware.info/?probe=1581e2f112) | Apr 06, 2022 |
| MSI           | 990FXA-GD80                 | [9c0d3e7793](https://bsd-hardware.info/?probe=9c0d3e7793) | Apr 06, 2022 |
| Supermicro    | X10SLL-F                    | [7b901b1d99](https://bsd-hardware.info/?probe=7b901b1d99) | Apr 05, 2022 |
| Protectli     | FW6                         | [9ab59de1ca](https://bsd-hardware.info/?probe=9ab59de1ca) | Apr 05, 2022 |
| HP            | 213D A01                    | [0c24a77be7](https://bsd-hardware.info/?probe=0c24a77be7) | Apr 05, 2022 |
| Protectli     | FW4B                        | [f51cc63f72](https://bsd-hardware.info/?probe=f51cc63f72) | Apr 05, 2022 |
| Dell          | 05GD68 A00                  | [d7efc57aa2](https://bsd-hardware.info/?probe=d7efc57aa2) | Apr 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | [06bad6f773](https://bsd-hardware.info/?probe=06bad6f773) | Apr 04, 2022 |
| Protectli     | FW4B Ver                    | [746d840530](https://bsd-hardware.info/?probe=746d840530) | Apr 03, 2022 |
| HP            | 1495                        | [5e4e29bf54](https://bsd-hardware.info/?probe=5e4e29bf54) | Apr 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1043649da9](https://bsd-hardware.info/?probe=1043649da9) | Apr 03, 2022 |
| MSI           | H81M-P33                    | [b0d11aabb7](https://bsd-hardware.info/?probe=b0d11aabb7) | Apr 03, 2022 |
| ASUSTek       | P5Q-E                       | [dbaaa0dcda](https://bsd-hardware.info/?probe=dbaaa0dcda) | Apr 03, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | [82e48f7eb4](https://bsd-hardware.info/?probe=82e48f7eb4) | Apr 03, 2022 |
| Dell          | 0PC5F7 A02                  | [93d77b3755](https://bsd-hardware.info/?probe=93d77b3755) | Apr 03, 2022 |
| eMachines     | EL1360G                     | [0443d39e17](https://bsd-hardware.info/?probe=0443d39e17) | Apr 02, 2022 |
| PC Engines    | apu4                        | [00e4f2931b](https://bsd-hardware.info/?probe=00e4f2931b) | Apr 02, 2022 |
| Dell          | 04YP6J A02                  | [8be7c68dfb](https://bsd-hardware.info/?probe=8be7c68dfb) | Apr 01, 2022 |
| Dell          | 0D6H9T A00                  | [7daab72741](https://bsd-hardware.info/?probe=7daab72741) | Apr 01, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [01dcca775c](https://bsd-hardware.info/?probe=01dcca775c) | Apr 01, 2022 |
| Dell          | 0GXM1W A00                  | [5bdcde54b1](https://bsd-hardware.info/?probe=5bdcde54b1) | Apr 01, 2022 |
| Dell          | 0G261D A00                  | [b64ddb6733](https://bsd-hardware.info/?probe=b64ddb6733) | Mar 31, 2022 |
| HP            | 158A                        | [5d463584db](https://bsd-hardware.info/?probe=5d463584db) | Mar 31, 2022 |
| ASUSTek       | PRIME A320I-K               | [bd9d4bb7a3](https://bsd-hardware.info/?probe=bd9d4bb7a3) | Mar 31, 2022 |
| Protectli     | FW6 Ver                     | [bffcfb13e3](https://bsd-hardware.info/?probe=bffcfb13e3) | Mar 31, 2022 |
| Supermicro    | X9SAEA                      | [bdb1c8e931](https://bsd-hardware.info/?probe=bdb1c8e931) | Mar 31, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [cb50918ca3](https://bsd-hardware.info/?probe=cb50918ca3) | Mar 30, 2022 |
| MSI           | Z97 PC Mate                 | [6a276beb82](https://bsd-hardware.info/?probe=6a276beb82) | Mar 30, 2022 |
| Dell          | 0G261D A00                  | [91df634364](https://bsd-hardware.info/?probe=91df634364) | Mar 29, 2022 |
| Gigabyte      | H110N-CF                    | [89593af061](https://bsd-hardware.info/?probe=89593af061) | Mar 29, 2022 |
| Protectli     | FW4B                        | [e140c22680](https://bsd-hardware.info/?probe=e140c22680) | Mar 29, 2022 |
| Foxconn       | 2ADA                        | [8f507fcb9a](https://bsd-hardware.info/?probe=8f507fcb9a) | Mar 27, 2022 |
| Dell          | 0NC2VH A02                  | [2593acccf3](https://bsd-hardware.info/?probe=2593acccf3) | Mar 27, 2022 |
| MSI           | H61M-P25                    | [123cb1174a](https://bsd-hardware.info/?probe=123cb1174a) | Mar 27, 2022 |
| PC Engines    | APU                         | [941b9801bc](https://bsd-hardware.info/?probe=941b9801bc) | Mar 27, 2022 |
| MSI           | H81M-P33                    | [823d2d7336](https://bsd-hardware.info/?probe=823d2d7336) | Mar 27, 2022 |
| ASUSTek       | P5Q-E                       | [4e44bfd765](https://bsd-hardware.info/?probe=4e44bfd765) | Mar 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [51507583f6](https://bsd-hardware.info/?probe=51507583f6) | Mar 27, 2022 |
| Dell          | 0M5DCD A00                  | [4c03d19a48](https://bsd-hardware.info/?probe=4c03d19a48) | Mar 27, 2022 |
| Dell          | 03KWTV A02                  | [7a341728eb](https://bsd-hardware.info/?probe=7a341728eb) | Mar 27, 2022 |
| Protectli     | FW4A Ver                    | [32d9eff6fb](https://bsd-hardware.info/?probe=32d9eff6fb) | Mar 27, 2022 |
| Dell          | 05GD68 A00                  | [28f9e0596c](https://bsd-hardware.info/?probe=28f9e0596c) | Mar 27, 2022 |
| Unknown       | Unknown                     | [bd9b55ea13](https://bsd-hardware.info/?probe=bd9b55ea13) | Mar 26, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK MM ... | [3c86d96e65](https://bsd-hardware.info/?probe=3c86d96e65) | Mar 26, 2022 |
| Biostar       | NM70I-1037U                 | [d2c51a35cf](https://bsd-hardware.info/?probe=d2c51a35cf) | Mar 25, 2022 |
| Protectli     | FW4B                        | [9a1d787beb](https://bsd-hardware.info/?probe=9a1d787beb) | Mar 25, 2022 |
| MSI           | G41M-P33 Combo              | [03d5b67d7b](https://bsd-hardware.info/?probe=03d5b67d7b) | Mar 25, 2022 |
| Gigabyte      | H270N-WIFI-CF               | [07af378490](https://bsd-hardware.info/?probe=07af378490) | Mar 25, 2022 |
| ASUSTek       | P5KPL-CM                    | [d9e74758f3](https://bsd-hardware.info/?probe=d9e74758f3) | Mar 24, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [574b11983b](https://bsd-hardware.info/?probe=574b11983b) | Mar 24, 2022 |
| Dell          | 0W0CHX A00                  | [9e9d0f7cb6](https://bsd-hardware.info/?probe=9e9d0f7cb6) | Mar 24, 2022 |
| Dell          | 0WMJ54 A00                  | [c9114be51e](https://bsd-hardware.info/?probe=c9114be51e) | Mar 23, 2022 |
| ASUSTek       | M4A78T-E                    | [7c46c8e712](https://bsd-hardware.info/?probe=7c46c8e712) | Mar 23, 2022 |
| Unknown       | Unknown                     | [b7caab74c8](https://bsd-hardware.info/?probe=b7caab74c8) | Mar 22, 2022 |
| HP            | 1495                        | [af6b21fdff](https://bsd-hardware.info/?probe=af6b21fdff) | Mar 22, 2022 |
| ASRock        | B550M Steel Legend          | [a752b8b4d6](https://bsd-hardware.info/?probe=a752b8b4d6) | Mar 22, 2022 |
| Supermicro    | X7SPA-H                     | [c0415b128f](https://bsd-hardware.info/?probe=c0415b128f) | Mar 22, 2022 |
| Unknown       | Unknown                     | [c4ffde79eb](https://bsd-hardware.info/?probe=c4ffde79eb) | Mar 21, 2022 |
| HP            | 1495                        | [ddcc87225d](https://bsd-hardware.info/?probe=ddcc87225d) | Mar 21, 2022 |
| MSI           | A78M-E45                    | [191e17803a](https://bsd-hardware.info/?probe=191e17803a) | Mar 21, 2022 |
| Dell          | 02YYK5 A01                  | [cddd1bf6a8](https://bsd-hardware.info/?probe=cddd1bf6a8) | Mar 20, 2022 |
| MSI           | X79A-GD45 Plus              | [47e069c6d9](https://bsd-hardware.info/?probe=47e069c6d9) | Mar 20, 2022 |
| Unknown       | Unknown                     | [91d8f0be69](https://bsd-hardware.info/?probe=91d8f0be69) | Mar 20, 2022 |
| ASRock        | X570 Pro4                   | [2aeeaaacfc](https://bsd-hardware.info/?probe=2aeeaaacfc) | Mar 20, 2022 |
| ASRock        | X570 Pro4                   | [4b6df22ff5](https://bsd-hardware.info/?probe=4b6df22ff5) | Mar 20, 2022 |
| ASRock        | AM1B-MDH                    | [2cd18e1270](https://bsd-hardware.info/?probe=2cd18e1270) | Mar 20, 2022 |
| MSI           | H81M-P33                    | [d9421c2715](https://bsd-hardware.info/?probe=d9421c2715) | Mar 20, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/USA/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OPNsense 21.7.7   | 67       | 3.47%   |
| OPNsense 22.7.10  | 63       | 3.26%   |
| OPNsense 21.7.3   | 56       | 2.9%    |
| OPNsense 22.7.4   | 51       | 2.64%   |
| OPNsense 22.1.10  | 51       | 2.64%   |
| OPNsense 21.1.5   | 49       | 2.54%   |
| OPNsense 22.1     | 47       | 2.43%   |
| OPNsense 20.7.8   | 46       | 2.38%   |
| OPNsense 21.7.1   | 45       | 2.33%   |
| OPNsense 22.1.8   | 44       | 2.28%   |
| OPNsense 21.1.3   | 44       | 2.28%   |
| OPNsense 21.1.4   | 40       | 2.07%   |
| OPNsense 22.7.8   | 38       | 1.97%   |
| OPNsense 21.1     | 38       | 1.97%   |
| OPNsense 21.1.8   | 37       | 1.92%   |
| OPNsense 22.1.6   | 34       | 1.76%   |
| OPNsense 22.1.2   | 34       | 1.76%   |
| OPNsense 22.7.9   | 32       | 1.66%   |
| OPNsense 22.7.7   | 32       | 1.66%   |
| OPNsense 22.7.6   | 32       | 1.66%   |
| OPNsense 22.1.4   | 31       | 1.61%   |
| OPNsense 21.1.1   | 30       | 1.55%   |
| OPNsense 21.7.6   | 29       | 1.5%    |
| OPNsense 22.7.2   | 28       | 1.45%   |
| OPNsense 21.1.7   | 28       | 1.45%   |
| helloSystem 0.7.0 | 28       | 1.45%   |
| OPNsense 22.1.7   | 26       | 1.35%   |
| OPNsense 22.7     | 25       | 1.29%   |
| OPNsense 21.1.6   | 25       | 1.29%   |
| OPNsense 22.1.1   | 24       | 1.24%   |
| OPNsense 21.7.5   | 24       | 1.24%   |
| FreeBSD 13.0      | 22       | 1.14%   |
| OPNsense 22.1.9   | 21       | 1.09%   |
| OPNsense 21.7.4   | 21       | 1.09%   |
| OPNsense 21.7     | 21       | 1.09%   |
| OPNsense 21.7.8   | 20       | 1.04%   |
| OPNsense 21.1.2   | 20       | 1.04%   |
| FreeBSD 13.1      | 20       | 1.04%   |
| OPNsense 23.1     | 19       | 0.98%   |
| OPNsense 22.7.1   | 19       | 0.98%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 963      | 70.14%  |
| FreeBSD     | 207      | 15.08%  |
| helloSystem | 72       | 5.24%   |
| OpenBSD     | 37       | 2.69%   |
| GhostBSD    | 19       | 1.38%   |
| pfSense     | 15       | 1.09%   |
| NomadBSD    | 15       | 1.09%   |
| FreeNAS     | 14       | 1.02%   |
| MidnightBSD | 11       | 0.8%    |
| TrueNAS     | 9        | 0.66%   |
| NetBSD      | 4        | 0.29%   |
| OS108       | 2        | 0.15%   |
| HardenedBSD | 2        | 0.15%   |
| XigmaNAS    | 1        | 0.07%   |
| FuryBSD     | 1        | 0.07%   |
| DragonFly   | 1        | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 1345     | 98.61%  |
| i386    | 9        | 0.66%   |
| arm64   | 8        | 0.59%   |
| powerpc | 2        | 0.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 1122     | 80.95%  |
| helloDesktop  | 78       | 5.63%   |
| XFCE          | 29       | 2.09%   |
| KDE5          | 29       | 2.09%   |
| MATE          | 27       | 1.95%   |
| TWM           | 21       | 1.52%   |
| Openbox       | 20       | 1.44%   |
| GNOME         | 19       | 1.37%   |
| fvwm          | 18       | 1.3%    |
| i3            | 11       | 0.79%   |
| Cinnamon      | 4        | 0.29%   |
| Lumina        | 3        | 0.22%   |
| Xfwm4         | 1        | 0.07%   |
| Window Maker  | 1        | 0.07%   |
| Picom         | 1        | 0.07%   |
| Fluxbox       | 1        | 0.07%   |
| Enlightenment | 1        | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 1128     | 82.1%   |
| X11     | 245      | 17.83%  |
| Wayland | 1        | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 1189     | 86.79%  |
| SLiM    | 103      | 7.52%   |
| LightDM | 27       | 1.97%   |
| SDDM    | 23       | 1.68%   |
| XDM     | 19       | 1.39%   |
| GDM     | 9        | 0.66%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Desktops | Percent |
|-----------------|----------|---------|
| Unknown         | 1120     | 80.23%  |
| en_US           | 159      | 11.39%  |
| C               | 109      | 7.81%   |
| en              | 4        | 0.29%   |
| fr              | 1        | 0.07%   |
| en_US.utf-8     | 1        | 0.07%   |
| en_US.ISO8859-1 | 1        | 0.07%   |
| en_GB           | 1        | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 1161     | 83.29%  |
| BIOS | 233      | 16.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 823      | 58.41%  |
| Zfs     | 528      | 37.47%  |
| Ffs     | 37       | 2.63%   |
| Cd9660  | 19       | 1.35%   |
| Hammer2 | 1        | 0.07%   |
| Unknown | 1        | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1259     | 91.17%  |
| MBR     | 109      | 7.89%   |
| Unknown | 10       | 0.72%   |
| BSD     | 3        | 0.22%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Dell                          | 187      | 13.71%  |
| Protectli                     | 165      | 12.1%   |
| Unknown                       | 142      | 10.41%  |
| Hewlett-Packard               | 129      | 9.46%   |
| ASUSTek Computer              | 125      | 9.16%   |
| ASRock                        | 89       | 6.52%   |
| Supermicro                    | 80       | 5.87%   |
| Intel                         | 76       | 5.57%   |
| MSI                           | 59       | 4.33%   |
| Gigabyte Technology           | 57       | 4.18%   |
| Lenovo                        | 46       | 3.37%   |
| PC Engines                    | 28       | 2.05%   |
| Biostar                       | 11       | 0.81%   |
| AZW                           | 11       | 0.81%   |
| Techvision                    | 9        | 0.66%   |
| Foxconn                       | 7        | 0.51%   |
| Apple                         | 7        | 0.51%   |
| Shuttle                       | 6        | 0.44%   |
| SeeedStudio                   | 6        | 0.44%   |
| HARDKERNEL                    | 6        | 0.44%   |
| ASRockRack                    | 6        | 0.44%   |
| Seeed Studio                  | 5        | 0.37%   |
| MW                            | 5        | 0.37%   |
| Fujitsu                       | 5        | 0.37%   |
| CheckPoint                    | 5        | 0.37%   |
| Acer                          | 5        | 0.37%   |
| TYAN Computer                 | 4        | 0.29%   |
| Cisco                         | 4        | 0.29%   |
| AAEON                         | 4        | 0.29%   |
| ShenZhen MinWin Technology    | 3        | 0.22%   |
| MiTAC                         | 3        | 0.22%   |
| Google                        | 3        | 0.22%   |
| CncTion                       | 3        | 0.22%   |
| BESSTAR Tech                  | 3        | 0.22%   |
| Alienware                     | 3        | 0.22%   |
| Soekris Engineering           | 2        | 0.15%   |
| SmbiosType2_BoardManufacturer | 2        | 0.15%   |
| Silicom                       | 2        | 0.15%   |
| Pegatron                      | 2        | 0.15%   |
| NU591                         | 2        | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 144      | 10.56%  |
| Protectli FW4B               | 64       | 4.69%   |
| Protectli FW6                | 48       | 3.52%   |
| Intel Q3XXG4-P V1.0          | 30       | 2.2%    |
| HP t620 PLUS Quad Core TC    | 22       | 1.61%   |
| Supermicro X9SCL/X9SCM       | 20       | 1.47%   |
| Dell OptiPlex 3020           | 20       | 1.47%   |
| Dell OptiPlex 9020           | 19       | 1.39%   |
| ASUS All Series              | 18       | 1.32%   |
| PC Engines apu4              | 13       | 0.95%   |
| PC Engines APU2              | 13       | 0.95%   |
| Dell OptiPlex 990            | 13       | 0.95%   |
| Protectli FW2B               | 12       | 0.88%   |
| Protectli VP2410             | 11       | 0.81%   |
| Dell OptiPlex 7010           | 11       | 0.81%   |
| HP EliteDesk 800 G1 SFF      | 10       | 0.73%   |
| Techvision TVI7309X          | 9        | 0.66%   |
| Intel Nobilis                | 9        | 0.66%   |
| Protectli FW6E               | 7        | 0.51%   |
| Protectli FW6D               | 7        | 0.51%   |
| Protectli FW1                | 7        | 0.51%   |
| HP EliteDesk 800 G2 SFF      | 7        | 0.51%   |
| Dell OptiPlex 790            | 7        | 0.51%   |
| Dell OptiPlex 390            | 7        | 0.51%   |
| AZW GK55                     | 7        | 0.51%   |
| ASUS TUF GAMING X570-PLUS    | 7        | 0.51%   |
| HP Compaq 8200 Elite SFF PC  | 6        | 0.44%   |
| Dell OptiPlex 9010           | 6        | 0.44%   |
| Dell OptiPlex 7020           | 6        | 0.44%   |
| Dell OptiPlex 5040           | 6        | 0.44%   |
| Dell OptiPlex 3010           | 6        | 0.44%   |
| ASUS ROG STRIX B450-F GAMING | 6        | 0.44%   |
| Supermicro X7SPA-HF          | 5        | 0.37%   |
| Protectli FW4A               | 5        | 0.37%   |
| MW GMLK-2_5G4L               | 5        | 0.37%   |
| MSI MS-7721                  | 5        | 0.37%   |
| HP Slim Desktop 290-p0xxx    | 5        | 0.37%   |
| HP ProDesk 600 G1 SFF        | 5        | 0.37%   |
| HP Compaq Elite 8300 SFF     | 5        | 0.37%   |
| HARDKERNEL ODROID-H2         | 5        | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 144      | 10.56%  |
| Unknown              | 144      | 10.56%  |
| Protectli FW4B       | 64       | 4.69%   |
| Protectli FW6        | 48       | 3.52%   |
| Lenovo ThinkCentre   | 32       | 2.35%   |
| Intel Q3XXG4-P       | 31       | 2.27%   |
| HP EliteDesk         | 26       | 1.91%   |
| HP t620              | 24       | 1.76%   |
| ASUS ROG             | 21       | 1.54%   |
| ASUS PRIME           | 21       | 1.54%   |
| Supermicro X9SCL     | 20       | 1.47%   |
| HP ProDesk           | 20       | 1.47%   |
| ASUS TUF             | 20       | 1.47%   |
| HP Compaq            | 18       | 1.32%   |
| ASUS All             | 18       | 1.32%   |
| Dell Precision       | 15       | 1.1%    |
| ASRock X570          | 14       | 1.03%   |
| PC Engines apu4      | 13       | 0.95%   |
| PC Engines APU2      | 13       | 0.95%   |
| Dell Inspiron        | 13       | 0.95%   |
| Protectli FW2B       | 12       | 0.88%   |
| Protectli VP2410     | 11       | 0.81%   |
| Techvision TVI7309X  | 9        | 0.66%   |
| Intel Nobilis        | 9        | 0.66%   |
| HP Slim              | 8        | 0.59%   |
| Protectli FW6E       | 7        | 0.51%   |
| Protectli FW6D       | 7        | 0.51%   |
| Protectli FW1        | 7        | 0.51%   |
| Lenovo IdeaCentre    | 7        | 0.51%   |
| HP Pavilion          | 7        | 0.51%   |
| AZW GK55             | 7        | 0.51%   |
| Supermicro X7SPA-HF  | 5        | 0.37%   |
| Protectli FW4A       | 5        | 0.37%   |
| MW GMLK-2            | 5        | 0.37%   |
| MSI MS-7721          | 5        | 0.37%   |
| HARDKERNEL ODROID-H2 | 5        | 0.37%   |
| Gigabyte X570        | 5        | 0.37%   |
| ASUS M5A78L-M        | 5        | 0.37%   |
| ASRock B450M         | 5        | 0.37%   |
| Supermicro X8SIL     | 4        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 190      | 13.93%  |
| 2018    | 185      | 13.56%  |
| 2020    | 115      | 8.43%   |
| 2014    | 115      | 8.43%   |
| 2016    | 112      | 8.21%   |
| 2021    | 91       | 6.67%   |
| 2013    | 90       | 6.6%    |
| 2022    | 85       | 6.23%   |
| 2011    | 84       | 6.16%   |
| 2012    | 70       | 5.13%   |
| 2017    | 67       | 4.91%   |
| 2015    | 51       | 3.74%   |
| 2010    | 36       | 2.64%   |
| Unknown | 25       | 1.83%   |
| 2009    | 18       | 1.32%   |
| 2008    | 16       | 1.17%   |
| 2007    | 8        | 0.59%   |
| 2006    | 2        | 0.15%   |
| 2004    | 2        | 0.15%   |
| 2003    | 1        | 0.07%   |
| 2001    | 1        | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1364     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1287     | 94.35%  |
| Yes  | 77       | 5.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 519      | 37.02%  |
| 16.01-24.0      | 340      | 24.25%  |
| 4.01-8.0        | 226      | 16.12%  |
| 32.01-64.0      | 185      | 13.2%   |
| 64.01-256.0     | 57       | 4.07%   |
| 2.01-3.0        | 26       | 1.85%   |
| 24.01-32.0      | 23       | 1.64%   |
| 3.01-4.0        | 9        | 0.64%   |
| 0.51-1.0        | 7        | 0.5%    |
| 1.01-2.0        | 5        | 0.36%   |
| 0.01-0.5        | 4        | 0.29%   |
| More than 256.0 | 1        | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 644      | 44.75%  |
| 0.51-1.0    | 422      | 29.33%  |
| 1.01-2.0    | 217      | 15.08%  |
| 4.01-8.0    | 37       | 2.57%   |
| 2.01-3.0    | 33       | 2.29%   |
| 3.01-4.0    | 24       | 1.67%   |
| 8.01-16.0   | 18       | 1.25%   |
| 16.01-24.0  | 11       | 0.76%   |
| 32.01-64.0  | 8        | 0.56%   |
| 24.01-32.0  | 8        | 0.56%   |
| Unknown     | 7        | 0.49%   |
| 64.01-256.0 | 5        | 0.35%   |
| 0           | 5        | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 970      | 68.5%   |
| 2      | 170      | 12.01%  |
| 0      | 90       | 6.36%   |
| 3      | 67       | 4.73%   |
| 4      | 35       | 2.47%   |
| 5      | 24       | 1.69%   |
| 6      | 18       | 1.27%   |
| 7      | 10       | 0.71%   |
| 9      | 5        | 0.35%   |
| 8      | 5        | 0.35%   |
| 10     | 4        | 0.28%   |
| 12     | 3        | 0.21%   |
| 11     | 3        | 0.21%   |
| 21     | 2        | 0.14%   |
| 17     | 2        | 0.14%   |
| 14     | 2        | 0.14%   |
| 40     | 1        | 0.07%   |
| 26     | 1        | 0.07%   |
| 22     | 1        | 0.07%   |
| 19     | 1        | 0.07%   |
| 18     | 1        | 0.07%   |
| 13     | 1        | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1070     | 77.31%  |
| Yes       | 314      | 22.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1351     | 99.05%  |
| No        | 13       | 0.95%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1092     | 79.25%  |
| Yes       | 286      | 20.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1194     | 86.84%  |
| Yes       | 181      | 13.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| USA     | 1364     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Denver               | 23       | 1.53%   |
| Austin               | 20       | 1.33%   |
| Seattle              | 19       | 1.26%   |
| Chicago              | 19       | 1.26%   |
| Portland             | 15       | 1%      |
| New York             | 15       | 1%      |
| Grand Rapids         | 15       | 1%      |
| Rochester            | 14       | 0.93%   |
| Brooklyn             | 14       | 0.93%   |
| Dallas               | 12       | 0.8%    |
| Columbus             | 12       | 0.8%    |
| Mountain View        | 11       | 0.73%   |
| Atlanta              | 11       | 0.73%   |
| Ypsilanti            | 10       | 0.66%   |
| Springfield          | 10       | 0.66%   |
| Houston              | 10       | 0.66%   |
| Oakland              | 9        | 0.6%    |
| Miami                | 9        | 0.6%    |
| San Francisco        | 8        | 0.53%   |
| Milwaukee            | 8        | 0.53%   |
| Los Angeles          | 8        | 0.53%   |
| Fort Worth           | 8        | 0.53%   |
| Salem                | 7        | 0.46%   |
| Raleigh              | 7        | 0.46%   |
| San Diego            | 6        | 0.4%    |
| San Antonio          | 6        | 0.4%    |
| Salt Lake City       | 6        | 0.4%    |
| Saint Paul           | 6        | 0.4%    |
| Redmond              | 6        | 0.4%    |
| Poway                | 6        | 0.4%    |
| Pittsburgh           | 6        | 0.4%    |
| Philadelphia         | 6        | 0.4%    |
| Oklahoma City        | 6        | 0.4%    |
| Minneapolis          | 6        | 0.4%    |
| Las Vegas            | 6        | 0.4%    |
| Fort Lauderdale      | 6        | 0.4%    |
| City of Saint Peters | 6        | 0.4%    |
| Bothell              | 6        | 0.4%    |
| Bellevue             | 6        | 0.4%    |
| Alexandria           | 6        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 271      | 569    | 15.74%  |
| WDC                 | 235      | 746    | 13.65%  |
| Seagate             | 188      | 507    | 10.92%  |
| Kingston            | 139      | 192    | 8.07%   |
| Crucial             | 73       | 110    | 4.24%   |
| SanDisk             | 71       | 90     | 4.12%   |
| Intel               | 59       | 136    | 3.43%   |
| Toshiba             | 52       | 87     | 3.02%   |
| Transcend           | 48       | 99     | 2.79%   |
| Hoodisk             | 47       | 62     | 2.73%   |
| Protectli           | 44       | 71     | 2.56%   |
| Phison              | 39       | 61     | 2.26%   |
| A-DATA Technology   | 38       | 59     | 2.21%   |
| China               | 34       | 41     | 1.97%   |
| Hitachi             | 33       | 85     | 1.92%   |
| SK hynix            | 32       | 40     | 1.86%   |
| PNY                 | 30       | 42     | 1.74%   |
| SPCC                | 26       | 48     | 1.51%   |
| Dogfish             | 20       | 33     | 1.16%   |
| BIWIN               | 20       | 33     | 1.16%   |
| HGST                | 18       | 64     | 1.05%   |
| OCZ                 | 13       | 21     | 0.75%   |
| Hewlett-Packard     | 13       | 36     | 0.75%   |
| Team                | 11       | 14     | 0.64%   |
| FORESEE             | 9        | 11     | 0.52%   |
| Corsair             | 8        | 25     | 0.46%   |
| Apacer              | 8        | 8      | 0.46%   |
| NVMe                | 7        | 10     | 0.41%   |
| Micron Technology   | 6        | 7      | 0.35%   |
| KingSpec            | 6        | 9      | 0.35%   |
| Innodisk            | 6        | 7      | 0.35%   |
| Zheino              | 5        | 9      | 0.29%   |
| Silicon Motion      | 5        | 7      | 0.29%   |
| Plextor             | 5        | 10     | 0.29%   |
| Mushkin             | 5        | 8      | 0.29%   |
| LITEON              | 5        | 8      | 0.29%   |
| KIOXIA              | 5        | 11     | 0.29%   |
| Apple               | 5        | 9      | 0.29%   |
| ShiJi               | 4        | 5      | 0.23%   |
| Patriot             | 4        | 5      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SUV500MS240G 240GB     | 21       | 1.09%   |
| Seagate ST500DM002-1BD142 500GB | 20       | 1.04%   |
| Samsung SSD 850 EVO 250GB       | 20       | 1.04%   |
| Hoodisk SSD 32GB                | 19       | 0.99%   |
| Kingston SUV500MS120G 120GB     | 18       | 0.94%   |
| Protectli 120GB mSATA           | 17       | 0.89%   |
| Kingston SA400S37240G 240GB     | 16       | 0.83%   |
| BIWIN SSD 128GB                 | 16       | 0.83%   |
| WDC WD800JD-75MSA3 80GB         | 14       | 0.73%   |
| PNY CS900 120GB SSD             | 14       | 0.73%   |
| Samsung SSD 860 EVO 500GB       | 13       | 0.68%   |
| Samsung SSD 850 EVO 500GB       | 13       | 0.68%   |
| Hoodisk SSD 128GB               | 13       | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB        | 12       | 0.63%   |
| Samsung SSD 970 EVO Plus 500GB  | 12       | 0.63%   |
| Samsung SSD 860 EVO 250GB       | 12       | 0.63%   |
| Samsung SSD 860 EVO 1TB         | 12       | 0.63%   |
| Phison Sabrent 2TB              | 11       | 0.57%   |
| Kingston SA400S37120G 120GB     | 11       | 0.57%   |
| SPCC Solid State Disk 128GB     | 10       | 0.52%   |
| Toshiba DT01ACA100 1TB          | 9        | 0.47%   |
| Hoodisk SSD 64GB                | 9        | 0.47%   |
| Transcend TS128GMSA230S 128GB   | 8        | 0.42%   |
| Seagate ST4000DM000-1F2168 4TB  | 8        | 0.42%   |
| SanDisk SDSA6MM-016G-1006 16GB  | 8        | 0.42%   |
| Samsung SSD 960 EVO 500GB       | 8        | 0.42%   |
| Protectli 240GB mSATA           | 8        | 0.42%   |
| China SATA SSD 120GB            | 8        | 0.42%   |
| Seagate ST250DM000-1BD141 250GB | 7        | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB  | 7        | 0.36%   |
| Samsung SSD 970 EVO Plus 1TB    | 7        | 0.36%   |
| Samsung SSD 860 EVO M.2 250GB   | 7        | 0.36%   |
| Samsung SSD 850 EVO mSATA 250GB | 7        | 0.36%   |
| Protectli 64GB mSATA            | 7        | 0.36%   |
| Kingston SV300S37A120G 120GB    | 7        | 0.36%   |
| Crucial CT250MX500SSD1 250GB    | 7        | 0.36%   |
| WDC WDS100T2B0A-00SM50 1TB      | 6        | 0.31%   |
| WDC WD30EFRX-68EUZN0 3TB        | 6        | 0.31%   |
| Transcend TS32GSSD370 32GB      | 6        | 0.31%   |
| Samsung SSD 980 500GB           | 6        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC                                | 189      | 644    | 37.8%   |
| Seagate                            | 183      | 494    | 36.6%   |
| Toshiba                            | 42       | 74     | 8.4%    |
| Hitachi                            | 33       | 85     | 6.6%    |
| HGST                               | 18       | 64     | 3.6%    |
| Samsung Electronics                | 8        | 9      | 1.6%    |
| Hewlett-Packard                    | 4        | 14     | 0.8%    |
| Maxtor                             | 3        | 6      | 0.6%    |
| Apple                              | 3        | 4      | 0.6%    |
| Lexar                              | 2        | 2      | 0.4%    |
| HPE                                | 2        | 7      | 0.4%    |
| Adaptec                            | 2        | 2      | 0.4%    |
| WD MediaMax                        | 1        | 3      | 0.2%    |
| QUANTUM                            | 1        | 2      | 0.2%    |
| Product:              USB DISK 3.0 | 1        | 1      | 0.2%    |
| NVMe                               | 1        | 2      | 0.2%    |
| MaxDigital                         | 1        | 1      | 0.2%    |
| MARVELL                            | 1        | 1      | 0.2%    |
| LSI                                | 1        | 3      | 0.2%    |
| IBM-207x                           | 1        | 1      | 0.2%    |
| Fujitsu                            | 1        | 1      | 0.2%    |
| ExcelStor Technology               | 1        | 4      | 0.2%    |
| ASMT                               | 1        | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 188      | 391    | 18.88%  |
| Kingston            | 129      | 182    | 12.95%  |
| SanDisk             | 69       | 85     | 6.93%   |
| Crucial             | 58       | 94     | 5.82%   |
| Transcend           | 47       | 98     | 4.72%   |
| Hoodisk             | 46       | 61     | 4.62%   |
| Intel               | 45       | 114    | 4.52%   |
| Protectli           | 44       | 71     | 4.42%   |
| China               | 34       | 41     | 3.41%   |
| A-DATA Technology   | 30       | 45     | 3.01%   |
| PNY                 | 29       | 41     | 2.91%   |
| WDC                 | 24       | 56     | 2.41%   |
| Dogfish             | 20       | 33     | 2.01%   |
| BIWIN               | 20       | 33     | 2.01%   |
| SPCC                | 19       | 41     | 1.91%   |
| Phison              | 19       | 25     | 1.91%   |
| SK hynix            | 17       | 20     | 1.71%   |
| OCZ                 | 13       | 21     | 1.31%   |
| Toshiba             | 9        | 12     | 0.9%    |
| FORESEE             | 9        | 11     | 0.9%    |
| Apacer              | 8        | 8      | 0.8%    |
| Team                | 7        | 10     | 0.7%    |
| KingSpec            | 6        | 9      | 0.6%    |
| Innodisk            | 6        | 7      | 0.6%    |
| Corsair             | 6        | 11     | 0.6%    |
| Zheino              | 5        | 9      | 0.5%    |
| NVMe                | 5        | 7      | 0.5%    |
| Micron Technology   | 5        | 5      | 0.5%    |
| LITEON              | 5        | 8      | 0.5%    |
| Hewlett-Packard     | 5        | 8      | 0.5%    |
| ShiJi               | 4        | 5      | 0.4%    |
| Seagate             | 4        | 8      | 0.4%    |
| Plextor             | 4        | 6      | 0.4%    |
| Patriot             | 4        | 5      | 0.4%    |
| MyDigitalSSD        | 4        | 6      | 0.4%    |
| Mushkin             | 4        | 6      | 0.4%    |
| LITEONIT            | 4        | 6      | 0.4%    |
| Intenso             | 4        | 9      | 0.4%    |
| Vaseky              | 3        | 3      | 0.3%    |
| Supermicro          | 3        | 3      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 895      | 1668   | 58.65%  |
| HDD  | 395      | 1425   | 25.88%  |
| NVMe | 236      | 424    | 15.47%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1151     | 3093   | 82.98%  |
| NVMe | 236      | 424    | 17.02%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 987      | 1802   | 72.41%  |
| 0.51-1.0   | 189      | 419    | 13.87%  |
| 1.01-2.0   | 70       | 218    | 5.14%   |
| 4.01-10.0  | 41       | 314    | 3.01%   |
| 3.01-4.0   | 37       | 151    | 2.71%   |
| 2.01-3.0   | 28       | 111    | 2.05%   |
| 10.01-20.0 | 11       | 78     | 0.81%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 574      | 40.57%  |
| 251-500        | 242      | 17.1%   |
| 51-100         | 153      | 10.81%  |
| 21-50          | 146      | 10.32%  |
| 1-20           | 130      | 9.19%   |
| 501-1000       | 112      | 7.92%   |
| 1001-2000      | 32       | 2.26%   |
| More than 3000 | 15       | 1.06%   |
| Unknown        | 6        | 0.42%   |
| 2001-3000      | 5        | 0.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1274     | 90.29%  |
| 21-50          | 69       | 4.89%   |
| 51-100         | 28       | 1.98%   |
| 101-250        | 12       | 0.85%   |
| 251-500        | 10       | 0.71%   |
| Unknown        | 6        | 0.43%   |
| More than 3000 | 5        | 0.35%   |
| 501-1000       | 3        | 0.21%   |
| 2001-3000      | 2        | 0.14%   |
| 1001-2000      | 1        | 0.07%   |
| 0              | 1        | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 7        | 11     | 3.43%   |
| Crucial CT275MX300SSD1 275GB          | 4        | 7      | 1.96%   |
| Seagate ST3500418AS 500GB             | 3        | 10     | 1.47%   |
| Kingston SV300S37A60G 64GB            | 3        | 3      | 1.47%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 2        | 2      | 0.98%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2        | 9      | 0.98%   |
| WDC WD2001FASS-00W2B0 2TB             | 2        | 3      | 0.98%   |
| Toshiba DT01ACA050 500GB              | 2        | 2      | 0.98%   |
| SK hynix SC210 mSATA 256GB            | 2        | 2      | 0.98%   |
| Seagate ST500LT012-1DG142 500GB       | 2        | 3      | 0.98%   |
| Seagate ST3500413AS 500GB             | 2        | 10     | 0.98%   |
| Seagate ST31000528AS 1TB              | 2        | 2      | 0.98%   |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2      | 0.98%   |
| Seagate ST2000DL001-9VT156 2TB        | 2        | 2      | 0.98%   |
| Seagate ST1000DM003-9YN162 1TB        | 2        | 6      | 0.98%   |
| Samsung Electronics SSD 850 EVO 500GB | 2        | 2      | 0.98%   |
| MyDigitalSSD SB2 128GB                | 2        | 4      | 0.98%   |
| Kingston SUV400S37120G 120GB          | 2        | 3      | 0.98%   |
| Kingston SNS4151S316G 16GB            | 2        | 2      | 0.98%   |
| Kingston SMS200S3120G 120GB           | 2        | 2      | 0.98%   |
| Hitachi HTS725032A9A364 320GB         | 2        | 2      | 0.98%   |
| Crucial CT240M500SSD1 240GB           | 2        | 3      | 0.98%   |
| Apacer 32GB SATA Flash Drive          | 2        | 2      | 0.98%   |
| WDC WDS500G2B0A-00SM50 500GB          | 1        | 1      | 0.49%   |
| WDC WD60EFAX-68SHWN0 6TB              | 1        | 2      | 0.49%   |
| WDC WD6003FZBX-00K5WB0 6TB            | 1        | 1      | 0.49%   |
| WDC WD5000AAVS-00G9B1 500GB           | 1        | 1      | 0.49%   |
| WDC WD5000AAKX-08ERMA0 500GB          | 1        | 1      | 0.49%   |
| WDC WD5000AAKX-083CA0 500GB           | 1        | 1      | 0.49%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1        | 1      | 0.49%   |
| WDC WD5000AAKX-001CA0 500GB           | 1        | 3      | 0.49%   |
| WDC WD5000AAKS-00V1A0 500GB           | 1        | 2      | 0.49%   |
| WDC WD5000AADS-00S9B0 500GB           | 1        | 1      | 0.49%   |
| WDC WD4000AAKS-00C8A0 400GB           | 1        | 3      | 0.49%   |
| WDC WD3200AAJS-22B4A0 320GB           | 1        | 1      | 0.49%   |
| WDC WD3200AAJS-00L7A0 320GB           | 1        | 1      | 0.49%   |
| WDC WD2500JS-22NCB1 250GB             | 1        | 1      | 0.49%   |
| WDC WD2500AAKX-321CA0 250GB           | 1        | 1      | 0.49%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 6      | 0.49%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1        | 2      | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| Seagate              | 46       | 87     | 23.59%  |
| WDC                  | 33       | 61     | 16.92%  |
| Kingston             | 16       | 19     | 8.21%   |
| Samsung Electronics  | 13       | 15     | 6.67%   |
| Hitachi              | 12       | 16     | 6.15%   |
| Intel                | 11       | 13     | 5.64%   |
| Toshiba              | 10       | 10     | 5.13%   |
| Crucial              | 10       | 14     | 5.13%   |
| SK hynix             | 5        | 7      | 2.56%   |
| SanDisk              | 4        | 6      | 2.05%   |
| OCZ                  | 3        | 3      | 1.54%   |
| LITEON               | 3        | 4      | 1.54%   |
| HGST                 | 3        | 3      | 1.54%   |
| Apacer               | 3        | 3      | 1.54%   |
| MyDigitalSSD         | 2        | 4      | 1.03%   |
| Maxtor               | 2        | 5      | 1.03%   |
| A-DATA Technology    | 2        | 2      | 1.03%   |
| WD MediaMax          | 1        | 3      | 0.51%   |
| VisionTek            | 1        | 1      | 0.51%   |
| Transcend            | 1        | 4      | 0.51%   |
| SPCC                 | 1        | 3      | 0.51%   |
| PNY                  | 1        | 1      | 0.51%   |
| Phison               | 1        | 1      | 0.51%   |
| Micron Technology    | 1        | 1      | 0.51%   |
| LITEONIT             | 1        | 2      | 0.51%   |
| KingDian             | 1        | 1      | 0.51%   |
| INDMEM               | 1        | 1      | 0.51%   |
| HPE                  | 1        | 3      | 0.51%   |
| Hewlett-Packard      | 1        | 4      | 0.51%   |
| Fujitsu              | 1        | 1      | 0.51%   |
| ExcelStor Technology | 1        | 2      | 0.51%   |
| Dogfish              | 1        | 5      | 0.51%   |
| Corsair              | 1        | 1      | 0.51%   |
| BIWIN                | 1        | 1      | 0.51%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| Seagate              | 46       | 87     | 41.44%  |
| WDC                  | 32       | 60     | 28.83%  |
| Hitachi              | 12       | 16     | 10.81%  |
| Toshiba              | 8        | 8      | 7.21%   |
| Samsung Electronics  | 3        | 3      | 2.7%    |
| HGST                 | 3        | 3      | 2.7%    |
| Maxtor               | 2        | 5      | 1.8%    |
| WD MediaMax          | 1        | 3      | 0.9%    |
| HPE                  | 1        | 3      | 0.9%    |
| Hewlett-Packard      | 1        | 4      | 0.9%    |
| Fujitsu              | 1        | 1      | 0.9%    |
| ExcelStor Technology | 1        | 2      | 0.9%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 105      | 195    | 55.85%  |
| SSD  | 82       | 111    | 43.62%  |
| NVMe | 1        | 1      | 0.53%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| SK hynix SC308 SATA 256GB                  | 1        | 1      | 25%     |
| Seagate ST3500418AS 500GB                  | 1        | 2      | 25%     |
| Samsung Electronics SSD 970 EVO Plus 500GB | 1        | 1      | 25%     |
| Samsung Electronics HD204UI 2TB            | 1        | 2      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 3      | 50%     |
| SK hynix            | 1        | 1      | 25%     |
| Seagate             | 1        | 2      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1164     | 3133   | 83.56%  |
| Malfunc  | 187      | 307    | 13.42%  |
| Detected | 38       | 71     | 2.73%   |
| Failed   | 4        | 6      | 0.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1058     | 60.39%  |
| AMD                              | 269      | 15.35%  |
| Samsung Electronics              | 98       | 5.59%   |
| ASMedia Technology               | 45       | 2.57%   |
| SanDisk                          | 41       | 2.34%   |
| Broadcom / LSI                   | 38       | 2.17%   |
| Phison Electronics               | 31       | 1.77%   |
| Marvell Technology Group         | 26       | 1.48%   |
| Silicon Motion                   | 19       | 1.08%   |
| SK hynix                         | 16       | 0.91%   |
| Micron/Crucial Technology        | 14       | 0.8%    |
| Chelsio Communications           | 13       | 0.74%   |
| Kingston Technology Company      | 10       | 0.57%   |
| Nvidia                           | 9        | 0.51%   |
| JMicron Technology               | 9        | 0.51%   |
| Adaptec                          | 7        | 0.4%    |
| KIOXIA                           | 6        | 0.34%   |
| ADATA Technology                 | 6        | 0.34%   |
| Seagate Technology               | 5        | 0.29%   |
| MAXIO Technology (Hangzhou)      | 5        | 0.29%   |
| Silicon Image                    | 3        | 0.17%   |
| Shenzhen Longsys Electronics     | 3        | 0.17%   |
| Realtek Semiconductor            | 3        | 0.17%   |
| VIA Technologies                 | 2        | 0.11%   |
| Solid State Storage Technology   | 2        | 0.11%   |
| Micron Technology                | 2        | 0.11%   |
| Hewlett-Packard                  | 2        | 0.11%   |
| Transcend                        | 1        | 0.06%   |
| Toshiba                          | 1        | 0.06%   |
| Silicon Integrated Systems [SiS] | 1        | 0.06%   |
| Lite-On Technology               | 1        | 0.06%   |
| Innodisk                         | 1        | 0.06%   |
| HighPoint Technologies           | 1        | 0.06%   |
| Broadcom                         | 1        | 0.06%   |
| Biwin Storage Technology         | 1        | 0.06%   |
| Areca Technology                 | 1        | 0.06%   |
| 3ware                            | 1        | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 179      | 8.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 122      | 6.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 100      | 4.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 92       | 4.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 84       | 4.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 66       | 3.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 64       | 3.18%   |
| Intel SATA Controller [RAID mode]                                                       | 56       | 2.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 48       | 2.39%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 45       | 2.24%   |
| AMD 400 Series Chipset SATA Controller                                                  | 42       | 2.09%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 41       | 2.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 37       | 1.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 34       | 1.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 34       | 1.69%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 33       | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 31       | 1.54%   |
| Unknown                                                                                 | 26       | 1.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 24       | 1.19%   |
| AMD 500 Series Chipset SATA Controller                                                  | 23       | 1.14%   |
| Phison E12 NVMe Controller                                                              | 22       | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 20       | 1%      |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 20       | 1%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 19       | 0.95%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 18       | 0.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 17       | 0.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 16       | 0.8%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 15       | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 15       | 0.75%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 15       | 0.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 14       | 0.7%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 14       | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 14       | 0.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 14       | 0.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 13       | 0.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13       | 0.65%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 13       | 0.65%   |
| Samsung NVMe SSD Controller 980                                                         | 12       | 0.6%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 11       | 0.55%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 11       | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1172     | 67.63%  |
| NVMe | 255      | 14.71%  |
| IDE  | 157      | 9.06%   |
| RAID | 88       | 5.08%   |
| SAS  | 39       | 2.25%   |
| SCSI | 22       | 1.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 1073     | 78.55%  |
| AMD      | 282      | 20.64%  |
| ARM      | 6        | 0.44%   |
| Unknown  | 2        | 0.15%   |
| Motorola | 1        | 0.07%   |
| IBM      | 1        | 0.07%   |
| i        | 1        | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz           | 66       | 4.76%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 50       | 3.6%    |
| Intel Celeron N5105 @ 2.00GHz               | 30       | 2.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 27       | 1.95%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 26       | 1.87%   |
| AMD GX-412TC SOC                            | 26       | 1.87%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 24       | 1.73%   |
| AMD GX-420CA SOC with Radeon HD Graphics    | 22       | 1.59%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 21       | 1.51%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 20       | 1.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 19       | 1.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 17       | 1.23%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 17       | 1.23%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 16       | 1.15%   |
| Intel Atom CPU D525 @ 1.80GHz               | 16       | 1.15%   |
| Intel Celeron CPU J3060 @ 1.60GHz           | 13       | 0.94%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 13       | 0.94%   |
| Intel Core i5-2400 CPU @ 3.10GH             | 12       | 0.87%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 11       | 0.79%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 11       | 0.79%   |
| Intel Celeron J4105 CPU @ 1.50GHz           | 11       | 0.79%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 11       | 0.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 10       | 0.72%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 10       | 0.72%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 10       | 0.72%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 10       | 0.72%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 10       | 0.72%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 9        | 0.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 9        | 0.65%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 9        | 0.65%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 9        | 0.65%   |
| AMD Ryzen 5 3600 6-Core Processor           | 9        | 0.65%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz           | 8        | 0.58%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 8        | 0.58%   |
| Intel Atom CPU E3845 @ 1.91GHz              | 8        | 0.58%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 8        | 0.58%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 8        | 0.58%   |
| Intel Core i7-5550U CPU @ 2.00GHz           | 7        | 0.5%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 7        | 0.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz           | 7        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 297      | 21.54%  |
| Intel Celeron           | 247      | 17.91%  |
| Intel Core i7           | 146      | 10.59%  |
| Intel Xeon              | 125      | 9.06%   |
| Intel Core i3           | 107      | 7.76%   |
| Intel Atom              | 59       | 4.28%   |
| AMD GX                  | 57       | 4.13%   |
| AMD Ryzen 7             | 54       | 3.92%   |
| AMD Ryzen 5             | 41       | 2.97%   |
| Intel Pentium           | 27       | 1.96%   |
| Other                   | 23       | 1.67%   |
| AMD FX                  | 20       | 1.45%   |
| AMD Ryzen 9             | 17       | 1.23%   |
| Intel Core 2 Duo        | 13       | 0.94%   |
| AMD Ryzen 3             | 13       | 0.94%   |
| AMD A10                 | 12       | 0.87%   |
| Intel Core 2 Quad       | 9        | 0.65%   |
| AMD Phenom II X4        | 9        | 0.65%   |
| AMD Athlon              | 7        | 0.51%   |
| Intel Pentium Silver    | 6        | 0.44%   |
| Intel Core i9           | 6        | 0.44%   |
| ARM Cortex              | 6        | 0.44%   |
| AMD A8                  | 6        | 0.44%   |
| AMD Ryzen Threadripper  | 5        | 0.36%   |
| AMD Ryzen 5 PRO         | 5        | 0.36%   |
| AMD Opteron             | 5        | 0.36%   |
| AMD A4                  | 5        | 0.36%   |
| Intel Pentium Dual-Core | 4        | 0.29%   |
| Intel Pentium 4         | 4        | 0.29%   |
| Intel Core 2            | 4        | 0.29%   |
| AMD Phenom II X6        | 3        | 0.22%   |
| AMD G                   | 3        | 0.22%   |
| AMD Athlon 64 X2        | 3        | 0.22%   |
| AMD A6                  | 3        | 0.22%   |
| Intel Pentium Gold      | 2        | 0.15%   |
| Intel Pentium D         | 2        | 0.15%   |
| Intel Genuine           | 2        | 0.15%   |
| Intel 686-class         | 2        | 0.15%   |
| AMD Sempron             | 2        | 0.15%   |
| AMD Ryzen Embedded      | 2        | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 755      | 54.67%  |
| 2       | 311      | 22.52%  |
| 8       | 75       | 5.43%   |
| 16      | 57       | 4.13%   |
| 6       | 57       | 4.13%   |
| 12      | 45       | 3.26%   |
| Unknown | 40       | 2.9%    |
| 24      | 11       | 0.8%    |
| 1       | 10       | 0.72%   |
| 32      | 7        | 0.51%   |
| 10      | 4        | 0.29%   |
| 48      | 2        | 0.14%   |
| 14      | 2        | 0.14%   |
| 3       | 2        | 0.14%   |
| 64      | 1        | 0.07%   |
| 28      | 1        | 0.07%   |
| 20      | 1        | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1326     | 97.07%  |
| 2       | 22       | 1.61%   |
| Unknown | 16       | 1.17%   |
| 8       | 1        | 0.07%   |
| 4       | 1        | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 856      | 62.39%  |
| 2       | 473      | 34.48%  |
| Unknown | 43       | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 177      | 12.83%  |
| Haswell       | 170      | 12.32%  |
| Silvermont    | 134      | 9.71%   |
| IvyBridge     | 99       | 7.17%   |
| SandyBridge   | 87       | 6.3%    |
| Skylake       | 86       | 6.23%   |
| Unknown       | 69       | 5%      |
| Goldmont plus | 67       | 4.86%   |
| Zen+          | 43       | 3.12%   |
| Zen 2         | 43       | 3.12%   |
| Broadwell     | 39       | 2.83%   |
| Jaguar        | 35       | 2.54%   |
| Bonnell       | 33       | 2.39%   |
| Puma          | 31       | 2.25%   |
| Zen 3         | 30       | 2.17%   |
| Piledriver    | 30       | 2.17%   |
| CometLake     | 29       | 2.1%    |
| Zen           | 24       | 1.74%   |
| Penryn        | 24       | 1.74%   |
| Nehalem       | 24       | 1.74%   |
| K10           | 18       | 1.3%    |
| Goldmont      | 16       | 1.16%   |
| Core          | 16       | 1.16%   |
| Westmere      | 13       | 0.94%   |
| NetBurst      | 8        | 0.58%   |
| Steamroller   | 7        | 0.51%   |
| K8 Hammer     | 7        | 0.51%   |
| Bobcat        | 7        | 0.51%   |
| Excavator     | 6        | 0.43%   |
| TigerLake     | 3        | 0.22%   |
| Bulldozer     | 2        | 0.14%   |
| P6            | 1        | 0.07%   |
| K10 Llano     | 1        | 0.07%   |
| Geode         | 1        | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 848      | 63.38%  |
| AMD                                          | 230      | 17.19%  |
| Nvidia                                       | 161      | 12.03%  |
| ASPEED Technology                            | 51       | 3.81%   |
| Matrox Electronics Systems                   | 44       | 3.29%   |
| XGI Technology (eXtreme Graphics Innovation) | 3        | 0.22%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 95       | 7.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 92       | 6.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 67       | 4.95%   |
| Intel HD Graphics 530                                                                    | 58       | 4.28%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 56       | 4.14%   |
| Intel HD Graphics 620                                                                    | 54       | 3.99%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 51       | 3.77%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 40       | 2.95%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 37       | 2.73%   |
| Intel JasperLake [UHD Graphics]                                                          | 37       | 2.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 35       | 2.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 33       | 2.44%   |
| Intel UHD Graphics 620                                                                   | 27       | 1.99%   |
| Intel HD Graphics 630                                                                    | 23       | 1.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 23       | 1.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 22       | 1.62%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 22       | 1.62%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 22       | 1.62%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 21       | 1.55%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 20       | 1.48%   |
| Intel HD Graphics 610                                                                    | 17       | 1.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16       | 1.18%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 16       | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16       | 1.18%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 15       | 1.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14       | 1.03%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 12       | 0.89%   |
| Intel HD Graphics 6000                                                                   | 12       | 0.89%   |
| Intel HD Graphics 5500                                                                   | 12       | 0.89%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 8        | 0.59%   |
| AMD RV730 XT [Radeon HD 4670]                                                            | 8        | 0.59%   |
| AMD RS780L [Radeon 3000]                                                                 | 8        | 0.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 7        | 0.52%   |
| Intel HD Graphics 500                                                                    | 7        | 0.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7        | 0.52%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 7        | 0.52%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6        | 0.44%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 6        | 0.44%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 6        | 0.44%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 6        | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 804      | 58.3%   |
| 1 x AMD         | 216      | 15.66%  |
| 1 x Nvidia      | 142      | 10.3%   |
| Other           | 66       | 4.79%   |
| 1 x ASPEED      | 48       | 3.48%   |
| 1 x Matrox      | 42       | 3.05%   |
| 2 x Intel       | 24       | 1.74%   |
| Intel + Nvidia  | 12       | 0.87%   |
| Intel + AMD     | 5        | 0.36%   |
| 2 x AMD         | 4        | 0.29%   |
| AMD + Nvidia    | 4        | 0.29%   |
| 2 x Nvidia      | 3        | 0.22%   |
| 1 x XGI         | 3        | 0.22%   |
| Intel + ASPEED  | 2        | 0.15%   |
| 1 x SiS         | 1        | 0.07%   |
| Nvidia + ASPEED | 1        | 0.07%   |
| AMD + Matrox    | 1        | 0.07%   |
| AMD + ASPEED    | 1        | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1210     | 88.06%  |
| Proprietary | 90       | 6.55%   |
| Unknown     | 74       | 5.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1233     | 89.61%  |
| 1.01-2.0   | 39       | 2.83%   |
| 3.01-4.0   | 26       | 1.89%   |
| 7.01-8.0   | 25       | 1.82%   |
| 0.51-1.0   | 20       | 1.45%   |
| 0.01-0.5   | 13       | 0.94%   |
| 5.01-6.0   | 12       | 0.87%   |
| 8.01-16.0  | 5        | 0.36%   |
| 2.01-3.0   | 2        | 0.15%   |
| 4.01-5.0   | 1        | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 45       | 19.4%   |
| Samsung Electronics  | 29       | 12.5%   |
| Goldstar             | 29       | 12.5%   |
| Acer                 | 25       | 10.78%  |
| Hewlett-Packard      | 18       | 7.76%   |
| Ancor Communications | 14       | 6.03%   |
| ASUSTek Computer     | 8        | 3.45%   |
| Vizio                | 7        | 3.02%   |
| AOC                  | 7        | 3.02%   |
| LG Electronics       | 6        | 2.59%   |
| Lenovo               | 6        | 2.59%   |
| ViewSonic            | 5        | 2.16%   |
| Sceptre Tech         | 4        | 1.72%   |
| BenQ                 | 4        | 1.72%   |
| Sony                 | 3        | 1.29%   |
| MSI                  | 3        | 1.29%   |
| Apple                | 3        | 1.29%   |
| Westinghouse         | 2        | 0.86%   |
| Philips              | 2        | 0.86%   |
| Insignia             | 2        | 0.86%   |
| unknown              | 1        | 0.43%   |
| SHI                  | 1        | 0.43%   |
| SGT                  | 1        | 0.43%   |
| NEC Computers        | 1        | 0.43%   |
| Hitachi              | 1        | 0.43%   |
| HannStar             | 1        | 0.43%   |
| Gateway              | 1        | 0.43%   |
| Envision             | 1        | 0.43%   |
| Chimei Innolux       | 1        | 0.43%   |
| AU Optronics         | 1        | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                     | 3        | 1.23%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch               | 3        | 1.23%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                   | 3        | 1.23%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                   | 3        | 1.23%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch        | 3        | 1.23%   |
| Sony TV SNY9C01 1360x768                                            | 2        | 0.82%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch   | 2        | 0.82%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 300x230mm 14.9-inch | 2        | 0.82%   |
| Samsung Electronics S27C750 SAM0A60 1920x1080 600x340mm 27.2-inch   | 2        | 0.82%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch    | 2        | 0.82%   |
| Goldstar W2246 GSM5784 1920x1080 480x270mm 21.7-inch                | 2        | 0.82%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch          | 2        | 0.82%   |
| Dell S2716DG DELA0D1 2560x1440 600x340mm 27.2-inch                  | 2        | 0.82%   |
| Dell S2418HN/NX DEL4123 1920x1080 530x300mm 24.0-inch               | 2        | 0.82%   |
| ASUSTek Computer VP247 AUS24CA 1920x1080 520x290mm 23.4-inch        | 2        | 0.82%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                  | 2        | 0.82%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch    | 2        | 0.82%   |
| Acer V246HL ACR032E 1920x1080 530x300mm 24.0-inch                   | 2        | 0.82%   |
| Westinghouse LCM-19w4 WDE1904 1440x900 410x260mm 19.1-inch          | 1        | 0.41%   |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch        | 1        | 0.41%   |
| Vizio SV370XVT VIZ0057 1920x1080 820x460mm 37.0-inch                | 1        | 0.41%   |
| Vizio LCD Monitor VIZ0022 1920x540 480x270mm 21.7-inch              | 1        | 0.41%   |
| Vizio E320i-B2 VIZ1002 1360x768 700x400mm 31.7-inch                 | 1        | 0.41%   |
| Vizio E320i-A0 VIZ0091 1366x768 700x390mm 31.5-inch                 | 1        | 0.41%   |
| Vizio D43-D2 VIZ1004 1920x1080 930x520mm 41.9-inch                  | 1        | 0.41%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                 | 1        | 0.41%   |
| Vizio D32f-F1 VIZ1027 1920x1080 700x390mm 31.5-inch                 | 1        | 0.41%   |
| ViewSonic VX910 VSC3C19 1280x1024 380x300mm 19.1-inch               | 1        | 0.41%   |
| ViewSonic N2635w-3M VSC1B24 1360x768 580x330mm 26.3-inch            | 1        | 0.41%   |
| ViewSonic LCD Monitor VSCE032 2560x1440 530x300mm 24.0-inch         | 1        | 0.41%   |
| ViewSonic LCD Monitor VSCDC2E 1920x1080 480x270mm 21.7-inch         | 1        | 0.41%   |
| ViewSonic LCD Monitor VA1938 Series                                 | 1        | 0.41%   |
| unknown LCD Monitor Dell SE2717H/HX 1920x1080                       | 1        | 0.41%   |
| Sony SDM-HS75P SNY2300 1280x1024 340x270mm 17.1-inch                | 1        | 0.41%   |
| SHI LCD-TV**** SHI6102 1360x768 700x390mm 31.5-inch                 | 1        | 0.41%   |
| SGT LC156LF1L_03 SGT1560 1920x1080 300x260mm 15.6-inch              | 1        | 0.41%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch      | 1        | 0.41%   |
| Sceptre Tech Sceptre E20 SPT080D 1600x900 410x280mm 19.5-inch       | 1        | 0.41%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 820x350mm 35.1-inch      | 1        | 0.41%   |
| Sceptre Tech C305W-2560UN SPT0C0D 2560x1080 690x290mm 29.5-inch     | 1        | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 85       | 37.44%  |
| 2560x1440 (QHD)    | 23       | 10.13%  |
| 3840x2160 (4K)     | 21       | 9.25%   |
| 1920x1200 (WUXGA)  | 13       | 5.73%   |
| 1280x1024 (SXGA)   | 13       | 5.73%   |
| 1680x1050 (WSXGA+) | 12       | 5.29%   |
| 1600x900 (HD+)     | 10       | 4.41%   |
| 2560x1080          | 9        | 3.96%   |
| 3440x1440          | 7        | 3.08%   |
| 1440x900 (WXGA+)   | 7        | 3.08%   |
| 1360x768           | 6        | 2.64%   |
| 1366x768 (WXGA)    | 4        | 1.76%   |
| 1024x768 (XGA)     | 4        | 1.76%   |
| 2560x1600          | 3        | 1.32%   |
| 1600x1200          | 2        | 0.88%   |
| Unknown            | 2        | 0.88%   |
| 5760x1080          | 1        | 0.44%   |
| 3840x1600          | 1        | 0.44%   |
| 3840x1080          | 1        | 0.44%   |
| 2806x900           | 1        | 0.44%   |
| 1920x540           | 1        | 0.44%   |
| 1024x600           | 1        | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 41       | 17.6%   |
| 27      | 32       | 13.73%  |
| 31      | 23       | 9.87%   |
| 19      | 21       | 9.01%   |
| Unknown | 21       | 9.01%   |
| 21      | 18       | 7.73%   |
| 23      | 17       | 7.3%    |
| 34      | 11       | 4.72%   |
| 22      | 8        | 3.43%   |
| 17      | 7        | 3%      |
| 29      | 4        | 1.72%   |
| 18      | 4        | 1.72%   |
| 20      | 3        | 1.29%   |
| 15      | 3        | 1.29%   |
| 14      | 3        | 1.29%   |
| 64      | 2        | 0.86%   |
| 13      | 2        | 0.86%   |
| 52      | 1        | 0.43%   |
| 49      | 1        | 0.43%   |
| 42      | 1        | 0.43%   |
| 41      | 1        | 0.43%   |
| 39      | 1        | 0.43%   |
| 37      | 1        | 0.43%   |
| 35      | 1        | 0.43%   |
| 32      | 1        | 0.43%   |
| 28      | 1        | 0.43%   |
| 26      | 1        | 0.43%   |
| 25      | 1        | 0.43%   |
| 16      | 1        | 0.43%   |
| 9       | 1        | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 84       | 37.33%  |
| 401-500     | 47       | 20.89%  |
| 601-700     | 31       | 13.78%  |
| Unknown     | 21       | 9.33%   |
| 701-800     | 12       | 5.33%   |
| 301-350     | 11       | 4.89%   |
| 201-300     | 5        | 2.22%   |
| 351-400     | 4        | 1.78%   |
| 1001-1500   | 4        | 1.78%   |
| 801-900     | 3        | 1.33%   |
| 901-1000    | 2        | 0.89%   |
| 101-200     | 1        | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 136      | 62.67%  |
| 16/10   | 28       | 12.9%   |
| Unknown | 18       | 8.29%   |
| 21/9    | 15       | 6.91%   |
| 5/4     | 10       | 4.61%   |
| 4/3     | 6        | 2.76%   |
| 6/5     | 2        | 0.92%   |
| 32/9    | 1        | 0.46%   |
| 3/2     | 1        | 0.46%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 67       | 29.13%  |
| 351-500        | 38       | 16.52%  |
| 301-350        | 34       | 14.78%  |
| 151-200        | 24       | 10.43%  |
| Unknown        | 21       | 9.13%   |
| 251-300        | 17       | 7.39%   |
| 141-150        | 11       | 4.78%   |
| 501-1000       | 5        | 2.17%   |
| More than 1000 | 3        | 1.3%    |
| 101-110        | 3        | 1.3%    |
| 81-90          | 2        | 0.87%   |
| 121-130        | 2        | 0.87%   |
| 111-120        | 2        | 0.87%   |
| 1-40           | 1        | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 135      | 62.5%   |
| 101-120 | 36       | 16.67%  |
| Unknown | 21       | 9.72%   |
| 121-160 | 12       | 5.56%   |
| 161-240 | 9        | 4.17%   |
| 1-50    | 3        | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1164     | 84.59%  |
| 1     | 180      | 13.08%  |
| 2     | 27       | 1.96%   |
| 3     | 5        | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 1147     | 61.17%  |
| Realtek Semiconductor           | 439      | 23.41%  |
| Qualcomm Atheros                | 72       | 3.84%   |
| Broadcom                        | 71       | 3.79%   |
| Mellanox Technologies           | 26       | 1.39%   |
| Ralink Technology               | 16       | 0.85%   |
| Chelsio Communications          | 15       | 0.8%    |
| IMC Networks                    | 11       | 0.59%   |
| Ralink                          | 8        | 0.43%   |
| U-Blox                          | 6        | 0.32%   |
| Solarflare Communications       | 6        | 0.32%   |
| Marvell Technology Group        | 6        | 0.32%   |
| Aquantia                        | 5        | 0.27%   |
| Seeed Technology                | 4        | 0.21%   |
| Emulex                          | 3        | 0.16%   |
| D-Link System                   | 3        | 0.16%   |
| VIA Technologies                | 2        | 0.11%   |
| TP-Link                         | 2        | 0.11%   |
| Sequans Communications          | 2        | 0.11%   |
| Qualcomm Atheros Communications | 2        | 0.11%   |
| Novatel Wireless                | 2        | 0.11%   |
| MediaTek                        | 2        | 0.11%   |
| Apple                           | 2        | 0.11%   |
| American Megatrends             | 2        | 0.11%   |
| Accton Technology               | 2        | 0.11%   |
| 3Com                            | 2        | 0.11%   |
| ZyXEL Communications            | 1        | 0.05%   |
| Xiaomi                          | 1        | 0.05%   |
| Tehuti Networks                 | 1        | 0.05%   |
| Silicom                         | 1        | 0.05%   |
| Sierra Wireless                 | 1        | 0.05%   |
| Pulse-Eight                     | 1        | 0.05%   |
| Nvidia                          | 1        | 0.05%   |
| National Semiconductor          | 1        | 0.05%   |
| Linksys                         | 1        | 0.05%   |
| ICS Advent                      | 1        | 0.05%   |
| Google                          | 1        | 0.05%   |
| Exar                            | 1        | 0.05%   |
| Edimax Technology               | 1        | 0.05%   |
| Digium                          | 1        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 364      | 15.39%  |
| Intel I211 Gigabit Network Connection                                         | 222      | 9.39%   |
| Intel I210 Gigabit Network Connection                                         | 129      | 5.45%   |
| Intel 82574L Gigabit Network Connection                                       | 111      | 4.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 103      | 4.36%   |
| Intel I350 Gigabit Network Connection                                         | 96       | 4.06%   |
| Intel Ethernet Connection I217-LM                                             | 71       | 3%      |
| Intel 82580 Gigabit Network Connection                                        | 68       | 2.88%   |
| Intel Ethernet Controller I225-V                                              | 67       | 2.83%   |
| Intel 82583V Gigabit Network Connection                                       | 64       | 2.71%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 50       | 2.11%   |
| Realtek RTL8125 2.5GbE Controller                                             | 49       | 2.07%   |
| Intel 82576 Gigabit Network Connection                                        | 44       | 1.86%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 39       | 1.65%   |
| Intel Wi-Fi 6 AX200                                                           | 38       | 1.61%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 37       | 1.56%   |
| Intel Ethernet Connection (2) I219-LM                                         | 31       | 1.31%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 29       | 1.23%   |
| Intel Ethernet Connection (2) I219-V                                          | 28       | 1.18%   |
| Intel Ethernet Controller I226-V                                              | 20       | 0.85%   |
| Intel 82579V Gigabit Network Connection                                       | 19       | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 16       | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 15       | 0.63%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 14       | 0.59%   |
| Intel Wireless 3165                                                           | 14       | 0.59%   |
| Intel Ethernet Connection (2) I218-V                                          | 13       | 0.55%   |
| Intel 82575EB Gigabit Network Connection                                      | 13       | 0.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 12       | 0.51%   |
| Intel Wireless-AC 9260                                                        | 11       | 0.47%   |
| Intel Ethernet Controller X550                                                | 11       | 0.47%   |
| Intel Ethernet Connection I217-V                                              | 11       | 0.47%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 11       | 0.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 10       | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 10       | 0.42%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 10       | 0.42%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 10       | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                                         | 10       | 0.42%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 10       | 0.42%   |
| Intel Wireless 7260                                                           | 9        | 0.38%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 9        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 133      | 44.33%  |
| Qualcomm Atheros                | 60       | 20%     |
| Realtek Semiconductor           | 44       | 14.67%  |
| Broadcom                        | 17       | 5.67%   |
| Ralink Technology               | 16       | 5.33%   |
| IMC Networks                    | 11       | 3.67%   |
| Ralink                          | 8        | 2.67%   |
| TP-Link                         | 2        | 0.67%   |
| Qualcomm Atheros Communications | 2        | 0.67%   |
| MediaTek                        | 2        | 0.67%   |
| ZyXEL Communications            | 1        | 0.33%   |
| Sierra Wireless                 | 1        | 0.33%   |
| Linksys                         | 1        | 0.33%   |
| Edimax Technology               | 1        | 0.33%   |
| Belkin Components               | 1        | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 38       | 12.62%  |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 16       | 5.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 15       | 4.98%   |
| Intel Wireless 3165                                                                           | 14       | 4.65%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 12       | 3.99%   |
| Intel Wireless-AC 9260                                                                        | 11       | 3.65%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                          | 11       | 3.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 10       | 3.32%   |
| Intel Wireless 7260                                                                           | 9        | 2.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 8        | 2.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 8        | 2.66%   |
| Ralink RT5370 Wireless Adapter                                                                | 7        | 2.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 7        | 2.33%   |
| Intel Wireless 7265                                                                           | 7        | 2.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 7        | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 5        | 1.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 5        | 1.66%   |
| Ralink RT5572 Wireless Adapter                                                                | 5        | 1.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 4        | 1.33%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 4        | 1.33%   |
| Intel Wireless 8260                                                                           | 4        | 1.33%   |
| Intel Wireless 3160                                                                           | 4        | 1.33%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 4        | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 3        | 1%      |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 3        | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3        | 1%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3        | 1%      |
| Intel Centrino Wireless-N 2230                                                                | 3        | 1%      |
| Intel Centrino Advanced-N 6235                                                                | 3        | 1%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 3        | 1%      |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 3        | 1%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 0.66%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.66%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 2        | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2        | 0.66%   |
| Ralink RT5372 Wireless Adapter                                                                | 2        | 0.66%   |
| Ralink MT7601U Wireless Adapter                                                               | 2        | 0.66%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2        | 0.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2        | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 1107     | 67.21%  |
| Realtek Semiconductor     | 418      | 25.38%  |
| Broadcom                  | 55       | 3.34%   |
| Qualcomm Atheros          | 14       | 0.85%   |
| Chelsio Communications    | 13       | 0.79%   |
| Solarflare Communications | 6        | 0.36%   |
| Marvell Technology Group  | 6        | 0.36%   |
| Aquantia                  | 5        | 0.3%    |
| Emulex                    | 3        | 0.18%   |
| D-Link System             | 3        | 0.18%   |
| VIA Technologies          | 2        | 0.12%   |
| Novatel Wireless          | 2        | 0.12%   |
| American Megatrends       | 2        | 0.12%   |
| 3Com                      | 2        | 0.12%   |
| Xiaomi                    | 1        | 0.06%   |
| Tehuti Networks           | 1        | 0.06%   |
| Silicom                   | 1        | 0.06%   |
| Nvidia                    | 1        | 0.06%   |
| National Semiconductor    | 1        | 0.06%   |
| ICS Advent                | 1        | 0.06%   |
| Apple                     | 1        | 0.06%   |
| ADMtek                    | 1        | 0.06%   |
| Accton Technology         | 1        | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 364      | 18.15%  |
| Intel I211 Gigabit Network Connection                                         | 222      | 11.07%  |
| Intel I210 Gigabit Network Connection                                         | 129      | 6.43%   |
| Intel 82574L Gigabit Network Connection                                       | 111      | 5.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 103      | 5.13%   |
| Intel I350 Gigabit Network Connection                                         | 96       | 4.79%   |
| Intel Ethernet Connection I217-LM                                             | 71       | 3.54%   |
| Intel 82580 Gigabit Network Connection                                        | 68       | 3.39%   |
| Intel Ethernet Controller I225-V                                              | 67       | 3.34%   |
| Intel 82583V Gigabit Network Connection                                       | 64       | 3.19%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 50       | 2.49%   |
| Realtek RTL8125 2.5GbE Controller                                             | 47       | 2.34%   |
| Intel 82576 Gigabit Network Connection                                        | 44       | 2.19%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 39       | 1.94%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 37       | 1.84%   |
| Intel Ethernet Connection (2) I219-LM                                         | 31       | 1.55%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 29       | 1.45%   |
| Intel Ethernet Connection (2) I219-V                                          | 28       | 1.4%    |
| Intel Ethernet Controller I226-V                                              | 20       | 1%      |
| Intel 82579V Gigabit Network Connection                                       | 19       | 0.95%   |
| Intel Ethernet Connection (2) I218-V                                          | 13       | 0.65%   |
| Intel 82575EB Gigabit Network Connection                                      | 13       | 0.65%   |
| Intel Ethernet Controller X550                                                | 11       | 0.55%   |
| Intel Ethernet Connection I217-V                                              | 11       | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 10       | 0.5%    |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 10       | 0.5%    |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 10       | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                                         | 10       | 0.5%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 10       | 0.5%    |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 9        | 0.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8        | 0.4%    |
| Intel Ethernet Controller I225-LM                                             | 8        | 0.4%    |
| Intel Ethernet Connection (7) I219-V                                          | 8        | 0.4%    |
| Intel NM10/ICH7 Family LAN Controller                                         | 7        | 0.35%   |
| Intel Ethernet Connection X553 1GbE                                           | 7        | 0.35%   |
| Intel Ethernet Connection (5) I219-LM                                         | 7        | 0.35%   |
| Intel 82575GB Gigabit Network Connection                                      | 7        | 0.35%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 6        | 0.3%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 5        | 0.25%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 5        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1351     | 79.71%  |
| WiFi     | 287      | 16.93%  |
| Unknown  | 44       | 2.6%    |
| Modem    | 13       | 0.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1320     | 95.38%  |
| WiFi     | 57       | 4.12%   |
| Unknown  | 7        | 0.51%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 268      | 19.23%  |
| 2     | 262      | 18.79%  |
| 3     | 226      | 16.21%  |
| 1     | 204      | 14.63%  |
| 6     | 182      | 13.06%  |
| 5     | 150      | 10.76%  |
| 7     | 34       | 2.44%   |
| 8     | 26       | 1.87%   |
| 9     | 12       | 0.86%   |
| 10    | 8        | 0.57%   |
| 0     | 8        | 0.57%   |
| 16    | 3        | 0.22%   |
| 11    | 3        | 0.22%   |
| 14    | 2        | 0.14%   |
| 13    | 2        | 0.14%   |
| 12    | 2        | 0.14%   |
| 20    | 1        | 0.07%   |
| 15    | 1        | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1128     | 79.1%   |
| Yes  | 298      | 20.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 114      | 61.62%  |
| Realtek Semiconductor           | 18       | 9.73%   |
| Cambridge Silicon Radio         | 10       | 5.41%   |
| Qualcomm Atheros Communications | 8        | 4.32%   |
| Apple                           | 8        | 4.32%   |
| Broadcom                        | 7        | 3.78%   |
| ASUSTek Computer                | 7        | 3.78%   |
| IMC Networks                    | 6        | 3.24%   |
| Lite-On Technology              | 4        | 2.16%   |
| MediaTek                        | 2        | 1.08%   |
| Dynex                           | 1        | 0.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                      | 33       | 17.84%  |
| Intel Bluetooth wireless interface                         | 30       | 16.22%  |
| Intel Wireless-AC 3168 Bluetooth                           | 16       | 8.65%   |
| Realtek  Bluetooth 4.2 Adapter                             | 14       | 7.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                   | 10       | 5.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)        | 10       | 5.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)             | 7        | 3.78%   |
| Intel Centrino Bluetooth Wireless Transceiver              | 6        | 3.24%   |
| Intel AX210 Bluetooth                                      | 6        | 3.24%   |
| Intel AX201 Bluetooth                                      | 6        | 3.24%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                       | 5        | 2.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                          | 4        | 2.16%   |
| Realtek  Bluetooth Adapter                                 | 2        | 1.08%   |
| Qualcomm Atheros AR9462 Bluetooth                          | 2        | 1.08%   |
| MediaTek Wireless_Device                                   | 2        | 1.08%   |
| Lite-On Bluetooth USB Module                               | 2        | 1.08%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip       | 2        | 1.08%   |
| Broadcom Broadcom 20702 Bluetooth 4.0 Adapter              | 2        | 1.08%   |
| ASUS Bluetooth USB module                                  | 2        | 1.08%   |
| ASUS Bluetooth Controller                                  | 2        | 1.08%   |
| Apple Apple Broadcom Built-in Bluetooth                    | 2        | 1.08%   |
| Realtek  Bluetooth 4.0 Adapter                             | 1        | 0.54%   |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE                | 1        | 0.54%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                    | 1        | 0.54%   |
| Qualcomm Atheros  QCA61x4 Bluetooth 4.1                    | 1        | 0.54%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                     | 1        | 0.54%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter | 1        | 0.54%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                      | 1        | 0.54%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)            | 1        | 0.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                 | 1        | 0.54%   |
| Lite-On Atheros AR9462 Bluetooth 4.0 + HS                  | 1        | 0.54%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                | 1        | 0.54%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS    | 1        | 0.54%   |
| IMC Networks Bluetooth                                     | 1        | 0.54%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter          | 1        | 0.54%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]   | 1        | 0.54%   |
| Broadcom BCM43142A0 Bluetooth Device                       | 1        | 0.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                         | 1        | 0.54%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE      | 1        | 0.54%   |
| ASUS ASUS USB-BT500                                        | 1        | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 793      | 61.66%  |
| AMD                                  | 274      | 21.31%  |
| Nvidia                               | 142      | 11.04%  |
| C-Media Electronics                  | 24       | 1.87%   |
| Creative Labs                        | 12       | 0.93%   |
| SteelSeries ApS                      | 6        | 0.47%   |
| Blue Microphones                     | 4        | 0.31%   |
| Texas Instruments                    | 2        | 0.16%   |
| Logitech                             | 2        | 0.16%   |
| Google                               | 2        | 0.16%   |
| Corsair                              | 2        | 0.16%   |
| ASUSTek Computer                     | 2        | 0.16%   |
| Yamaha                               | 1        | 0.08%   |
| XMOS                                 | 1        | 0.08%   |
| VIA Technologies                     | 1        | 0.08%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.08%   |
| Tenx Technology                      | 1        | 0.08%   |
| Silicon Integrated Systems [SiS]     | 1        | 0.08%   |
| Realtek Semiconductor                | 1        | 0.08%   |
| Razer USA                            | 1        | 0.08%   |
| Quanta                               | 1        | 0.08%   |
| Nektar                               | 1        | 0.08%   |
| LG Electronics                       | 1        | 0.08%   |
| KORG                                 | 1        | 0.08%   |
| Kingston Technology                  | 1        | 0.08%   |
| Genesys Logic                        | 1        | 0.08%   |
| Focusrite-Novation                   | 1        | 0.08%   |
| Creative Technology                  | 1        | 0.08%   |
| Cirrus Logic                         | 1        | 0.08%   |
| Cambridge Silicon Radio              | 1        | 0.08%   |
| Astro Gaming                         | 1        | 0.08%   |
| Apple                                | 1        | 0.08%   |
| AKAI  Professional M.I.              | 1        | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 114      | 7.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 105      | 6.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 88       | 5.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 68       | 4.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 59       | 3.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 58       | 3.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 53       | 3.36%   |
| AMD FCH Azalia Controller                                                                         | 52       | 3.29%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 51       | 3.23%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 49       | 3.1%    |
| Intel Jasper Lake HD Audio                                                                        | 37       | 2.34%   |
| Intel 200 Series PCH HD Audio                                                                     | 37       | 2.34%   |
| AMD Kabini HDMI/DP Audio                                                                          | 36       | 2.28%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 36       | 2.28%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 36       | 2.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 33       | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 30       | 1.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 26       | 1.65%   |
| Intel Broadwell-U Audio Controller                                                                | 25       | 1.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 24       | 1.52%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 23       | 1.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 23       | 1.46%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 22       | 1.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21       | 1.33%   |
| Intel 8 Series HD Audio Controller                                                                | 17       | 1.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 16       | 1.01%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16       | 1.01%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 14       | 0.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 14       | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 13       | 0.82%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 12       | 0.76%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 12       | 0.76%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 11       | 0.7%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 11       | 0.7%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 10       | 0.63%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 10       | 0.63%   |
| AMD Trinity HDMI Audio Controller                                                                 | 10       | 0.63%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 10       | 0.63%   |
| Intel Comet Lake PCH cAVS                                                                         | 9        | 0.57%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 9        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Electronics                     | 211      | 14.47%  |
| Crucial                                 | 185      | 12.69%  |
| SK hynix                                | 182      | 12.48%  |
| Kingston                                | 163      | 11.18%  |
| Unknown                                 | 145      | 9.95%   |
| Micron Technology                       | 131      | 8.98%   |
| G.Skill                                 | 95       | 6.52%   |
| Corsair                                 | 91       | 6.24%   |
| Unknown                                 | 40       | 2.74%   |
| Team                                    | 22       | 1.51%   |
| Patriot                                 | 19       | 1.3%    |
| Nanya Technology                        | 16       | 1.1%    |
| Unknown (ABCD)                          | 15       | 1.03%   |
| Ramaxel Technology                      | 15       | 1.03%   |
| PNY                                     | 15       | 1.03%   |
| A-DATA Technology                       | 15       | 1.03%   |
| Transcend                               | 11       | 0.75%   |
| Kimtigo                                 | 8        | 0.55%   |
| Super Talent                            | 7        | 0.48%   |
| Silicon Power                           | 6        | 0.41%   |
| Timetec                                 | 5        | 0.34%   |
| Elpida                                  | 5        | 0.34%   |
| Silicon Power Computer & Communications | 3        | 0.21%   |
| Sesame                                  | 3        | 0.21%   |
| Patriot Memory (PDP Systems)            | 3        | 0.21%   |
| Innodisk                                | 3        | 0.21%   |
| GeIL                                    | 3        | 0.21%   |
| Toshiba                                 | 2        | 0.14%   |
| Neo Forza                               | 2        | 0.14%   |
| GSkill                                  | 2        | 0.14%   |
| Avant                                   | 2        | 0.14%   |
| Vasekey                                 | 1        | 0.07%   |
| V-Color                                 | 1        | 0.07%   |
| Unknown (0B38)                          | 1        | 0.07%   |
| Unigen                                  | 1        | 0.07%   |
| Unifosa                                 | 1        | 0.07%   |
| Undefined-00BA                          | 1        | 0.07%   |
| Undefined-0002                          | 1        | 0.07%   |
| Teikon                                  | 1        | 0.07%   |
| Smart Modular                           | 1        | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 40       | 2.6%    |
| Unknown RAM Module 8GB 1600MT/s                                | 16       | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 15       | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 13       | 0.85%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s            | 12       | 0.78%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 11       | 0.72%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 11       | 0.72%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 11       | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 9        | 0.59%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 9        | 0.59%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 8        | 0.52%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 8        | 0.52%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s           | 8        | 0.52%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s            | 8        | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s            | 8        | 0.52%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s          | 8        | 0.52%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 8        | 0.52%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s          | 7        | 0.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 7        | 0.46%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s           | 7        | 0.46%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 6        | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                     | 6        | 0.39%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s             | 6        | 0.39%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 6        | 0.39%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s           | 6        | 0.39%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3                     | 6        | 0.39%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s            | 6        | 0.39%   |
| Kingston RAM 99U5428-018.A00LF 8GB DIMM DDR3 1600MT/s          | 6        | 0.39%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                 | 6        | 0.39%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s          | 6        | 0.39%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s          | 6        | 0.39%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s          | 6        | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 5        | 0.33%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s           | 5        | 0.33%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s           | 5        | 0.33%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 5        | 0.33%   |
| Samsung RAM M471B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s            | 5        | 0.33%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 5        | 0.33%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1333MT/s            | 5        | 0.33%   |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s          | 5        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 616      | 48.31%  |
| DDR4    | 531      | 41.65%  |
| Unknown | 44       | 3.45%   |
| DDR2    | 42       | 3.29%   |
| LPDDR4  | 19       | 1.49%   |
| SDRAM   | 12       | 0.94%   |
| DDR     | 9        | 0.71%   |
| LPDDR3  | 1        | 0.08%   |
| DDR5    | 1        | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 885      | 69.69%  |
| SODIMM       | 344      | 27.09%  |
| Unknown      | 31       | 2.44%   |
| RIMM         | 5        | 0.39%   |
| Row Of Chips | 4        | 0.31%   |
| FB-DIMM      | 1        | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 559      | 41.07%  |
| 4096  | 409      | 30.05%  |
| 16384 | 194      | 14.25%  |
| 2048  | 135      | 9.92%   |
| 32768 | 36       | 2.65%   |
| 1024  | 22       | 1.62%   |
| 512   | 5        | 0.37%   |
| 65536 | 1        | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 443      | 32.67%  |
| 2400    | 177      | 13.05%  |
| 1333    | 164      | 12.09%  |
| 2133    | 121      | 8.92%   |
| 3200    | 109      | 8.04%   |
| 2667    | 98       | 7.23%   |
| 800     | 46       | 3.39%   |
| 2666    | 38       | 2.8%    |
| 667     | 24       | 1.77%   |
| 3000    | 21       | 1.55%   |
| 1066    | 20       | 1.47%   |
| 3600    | 19       | 1.4%    |
| Unknown | 15       | 1.11%   |
| 1867    | 13       | 0.96%   |
| 1067    | 12       | 0.88%   |
| 1334    | 8        | 0.59%   |
| 2933    | 7        | 0.52%   |
| 1866    | 6        | 0.44%   |
| 533     | 6        | 0.44%   |
| 4800    | 1        | 0.07%   |
| 4133    | 1        | 0.07%   |
| 3534    | 1        | 0.07%   |
| 3333    | 1        | 0.07%   |
| 2134    | 1        | 0.07%   |
| 1639    | 1        | 0.07%   |
| 1400    | 1        | 0.07%   |
| 400     | 1        | 0.07%   |
| 266     | 1        | 0.07%   |

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
| Seiko Epson     | 1        | 50%     |
| Hewlett-Packard | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Desktops | Percent |
|-------------------------------------------------------------------------------------|----------|---------|
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1        | 50%     |
| HP ScanJet 5300c/5370c                                                              | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Logitech                  | 18       | 50%     |
| Microdia                  | 5        | 13.89%  |
| WCM_USB                   | 2        | 5.56%   |
| SHENZHEN EMEET TECHNOLOGY | 2        | 5.56%   |
| Chicony Electronics       | 2        | 5.56%   |
| Xiongmai                  | 1        | 2.78%   |
| Suyin                     | 1        | 2.78%   |
| Quanta                    | 1        | 2.78%   |
| Lenovo                    | 1        | 2.78%   |
| Generalplus Technology    | 1        | 2.78%   |
| Arkmicro Technologies     | 1        | 2.78%   |
| ARC International         | 1        | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                    | 6        | 16.67%  |
| Logitech Webcam C270                           | 5        | 13.89%  |
| Microdia Webcam Vitade AF                      | 3        | 8.33%   |
| Logitech C922 Pro Stream Webcam                | 3        | 8.33%   |
| WCM_USB WEB CAM                                | 2        | 5.56%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 2        | 5.56%   |
| Logitech Webcam C310                           | 2        | 5.56%   |
| Xiongmai web camera                            | 1        | 2.78%   |
| Suyin Acer CrystalEye Webcam                   | 1        | 2.78%   |
| Quanta Realtek DMFT - RGB                      | 1        | 2.78%   |
| Microdia Ltd., USB  Live camera                | 1        | 2.78%   |
| Microdia Camera                                | 1        | 2.78%   |
| Logitech HD Webcam C615                        | 1        | 2.78%   |
| Logitech HD Webcam C525                        | 1        | 2.78%   |
| Lenovo Lenovo 500 RGB Camera                   | 1        | 2.78%   |
| Generalplus GENERAL WEBCAM                     | 1        | 2.78%   |
| Chicony Ltd., HP 0.3MP Webcam                  | 1        | 2.78%   |
| Chicony HP High Definition 1MP Webcam          | 1        | 2.78%   |
| Arkmicro USB2.0 PC CAMERA                      | 1        | 2.78%   |
| ARC International Camera                       | 1        | 2.78%   |

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
| 1     | 684      | 48.68%  |
| 0     | 467      | 33.24%  |
| 2     | 183      | 13.02%  |
| 3     | 56       | 3.99%   |
| 4     | 12       | 0.85%   |
| 7     | 1        | 0.07%   |
| 6     | 1        | 0.07%   |
| 5     | 1        | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 786      | 69.56%  |
| Net/wireless             | 102      | 9.03%   |
| Bluetooth                | 73       | 6.46%   |
| Firewire controller      | 54       | 4.78%   |
| Net/ethernet             | 28       | 2.48%   |
| Sound                    | 26       | 2.3%    |
| Card reader              | 26       | 2.3%    |
| Network                  | 22       | 1.95%   |
| Graphics card            | 8        | 0.71%   |
| Storage/raid             | 3        | 0.27%   |
| Storage/ata              | 1        | 0.09%   |
| Dvb card                 | 1        | 0.09%   |

