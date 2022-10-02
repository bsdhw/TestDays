BSD in USA - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for BSD in USA.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/USA/Desktop/README.md) and [notebooks](/Location/USA/Notebook/README.md).

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

Total: 3371

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| AAEON         | FWS-2350 V1.0               | Desktop     | [00cc54cbad](https://bsd-hardware.info/?probe=00cc54cbad) | Oct 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [01566cd078](https://bsd-hardware.info/?probe=01566cd078) | Oct 01, 2022 |
| Dell          | 0PC5F7 A00                  | Desktop     | [376550557f](https://bsd-hardware.info/?probe=376550557f) | Sep 30, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [6853ba1191](https://bsd-hardware.info/?probe=6853ba1191) | Sep 30, 2022 |
| Biostar       | N68S3B                      | Desktop     | [24c8fcee9a](https://bsd-hardware.info/?probe=24c8fcee9a) | Sep 29, 2022 |
| HP            | 17E2                        | Mini pc     | [15ec4829ce](https://bsd-hardware.info/?probe=15ec4829ce) | Sep 29, 2022 |
| Lenovo        | ThinkPad W530 2436CTO       | Notebook    | [6515a18552](https://bsd-hardware.info/?probe=6515a18552) | Sep 29, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [62b9a56103](https://bsd-hardware.info/?probe=62b9a56103) | Sep 29, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [a3e25236fc](https://bsd-hardware.info/?probe=a3e25236fc) | Sep 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [2926e2dc6f](https://bsd-hardware.info/?probe=2926e2dc6f) | Sep 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c3f8e853ef](https://bsd-hardware.info/?probe=c3f8e853ef) | Sep 28, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [441eb24fd2](https://bsd-hardware.info/?probe=441eb24fd2) | Sep 28, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3234a0b453](https://bsd-hardware.info/?probe=3234a0b453) | Sep 28, 2022 |
| Sophos        | UTM                         | Firewall    | [9856bb0d34](https://bsd-hardware.info/?probe=9856bb0d34) | Sep 28, 2022 |
| Dell          | 081N4V A04                  | Server      | [34f2cbafda](https://bsd-hardware.info/?probe=34f2cbafda) | Sep 28, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [390f4301dd](https://bsd-hardware.info/?probe=390f4301dd) | Sep 27, 2022 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [5e823b71da](https://bsd-hardware.info/?probe=5e823b71da) | Sep 27, 2022 |
| Supermicro    | X11SBA-LN4F                 | Desktop     | [4c7f997199](https://bsd-hardware.info/?probe=4c7f997199) | Sep 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [3966e558bf](https://bsd-hardware.info/?probe=3966e558bf) | Sep 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [69a8b9b8d9](https://bsd-hardware.info/?probe=69a8b9b8d9) | Sep 26, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [cfcfd2a636](https://bsd-hardware.info/?probe=cfcfd2a636) | Sep 26, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [6c75d1609b](https://bsd-hardware.info/?probe=6c75d1609b) | Sep 26, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [68d99cffe1](https://bsd-hardware.info/?probe=68d99cffe1) | Sep 26, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [83607fc711](https://bsd-hardware.info/?probe=83607fc711) | Sep 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [c61ef8d251](https://bsd-hardware.info/?probe=c61ef8d251) | Sep 25, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [dad8b0a635](https://bsd-hardware.info/?probe=dad8b0a635) | Sep 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2d56ff12a1](https://bsd-hardware.info/?probe=2d56ff12a1) | Sep 25, 2022 |
| HP            | 3397                        | Desktop     | [8b019e6a96](https://bsd-hardware.info/?probe=8b019e6a96) | Sep 25, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [c81d389fd2](https://bsd-hardware.info/?probe=c81d389fd2) | Sep 25, 2022 |
| Biostar       | N68S3B                      | Desktop     | [59bd37df63](https://bsd-hardware.info/?probe=59bd37df63) | Sep 25, 2022 |
| System76      | Gazelle                     | Notebook    | [d087321049](https://bsd-hardware.info/?probe=d087321049) | Sep 24, 2022 |
| MSI           | A88XM-E45                   | Desktop     | [d9d06daa51](https://bsd-hardware.info/?probe=d9d06daa51) | Sep 24, 2022 |
| HP            | 18E7                        | Desktop     | [02ac7695d7](https://bsd-hardware.info/?probe=02ac7695d7) | Sep 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [8f42ff0969](https://bsd-hardware.info/?probe=8f42ff0969) | Sep 24, 2022 |
| System76      | Gazelle                     | Notebook    | [6d5d4f5021](https://bsd-hardware.info/?probe=6d5d4f5021) | Sep 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [95b1404339](https://bsd-hardware.info/?probe=95b1404339) | Sep 23, 2022 |
| Deciso        | Netboard A20                | Notebook    | [388e27791d](https://bsd-hardware.info/?probe=388e27791d) | Sep 23, 2022 |
| Intel         | S3210SH FRU Ver             | Server      | [e6d299ffc1](https://bsd-hardware.info/?probe=e6d299ffc1) | Sep 23, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [13f6367ce8](https://bsd-hardware.info/?probe=13f6367ce8) | Sep 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [b7bfcbef72](https://bsd-hardware.info/?probe=b7bfcbef72) | Sep 22, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1a89d78fa4](https://bsd-hardware.info/?probe=1a89d78fa4) | Sep 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [8e55c8e637](https://bsd-hardware.info/?probe=8e55c8e637) | Sep 20, 2022 |
| HP            | 1495                        | Desktop     | [163ac0a58b](https://bsd-hardware.info/?probe=163ac0a58b) | Sep 20, 2022 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [16479f1a2c](https://bsd-hardware.info/?probe=16479f1a2c) | Sep 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [1ceba97eb9](https://bsd-hardware.info/?probe=1ceba97eb9) | Sep 20, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [afbedcb189](https://bsd-hardware.info/?probe=afbedcb189) | Sep 20, 2022 |
| Supermicro    | X9DRD-iF                    | Server      | [f5e927f8ba](https://bsd-hardware.info/?probe=f5e927f8ba) | Sep 20, 2022 |
| Toshiba       | PORTEGE R700                | Notebook    | [10b85eccae](https://bsd-hardware.info/?probe=10b85eccae) | Sep 19, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [b394504429](https://bsd-hardware.info/?probe=b394504429) | Sep 19, 2022 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | Notebook    | [1b75ee6295](https://bsd-hardware.info/?probe=1b75ee6295) | Sep 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [8956b895ab](https://bsd-hardware.info/?probe=8956b895ab) | Sep 19, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [d1c81ef222](https://bsd-hardware.info/?probe=d1c81ef222) | Sep 19, 2022 |
| Dell          | 01TJ2K A02                  | Desktop     | [b34cf533f3](https://bsd-hardware.info/?probe=b34cf533f3) | Sep 19, 2022 |
| Lenovo        | ThinkStation D10 6493WEU    | Desktop     | [526e5eea0b](https://bsd-hardware.info/?probe=526e5eea0b) | Sep 18, 2022 |
| Supermicro    | A2SDi-TP8F                  | Desktop     | [db2194c9b9](https://bsd-hardware.info/?probe=db2194c9b9) | Sep 18, 2022 |
| MSI           | H81M-P33                    | Desktop     | [3e0c285177](https://bsd-hardware.info/?probe=3e0c285177) | Sep 18, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [ba1487a053](https://bsd-hardware.info/?probe=ba1487a053) | Sep 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [6dadd3f723](https://bsd-hardware.info/?probe=6dadd3f723) | Sep 18, 2022 |
| HP            | 213D A01                    | Desktop     | [6e8a38b6ca](https://bsd-hardware.info/?probe=6e8a38b6ca) | Sep 18, 2022 |
| EAGLE EYE ... | BayTrail-D Rev.00           | Desktop     | [261f623516](https://bsd-hardware.info/?probe=261f623516) | Sep 18, 2022 |
| CONTEC        | G1/EMB-CV1/iD2550           | Desktop     | [266ef0ca6a](https://bsd-hardware.info/?probe=266ef0ca6a) | Sep 18, 2022 |
| Standard      | SFFGL Series                | Mini pc     | [a537bcd507](https://bsd-hardware.info/?probe=a537bcd507) | Sep 16, 2022 |
| Dell          | 081N4V A04                  | Server      | [0e3a5d306d](https://bsd-hardware.info/?probe=0e3a5d306d) | Sep 16, 2022 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [ce024b9f84](https://bsd-hardware.info/?probe=ce024b9f84) | Sep 15, 2022 |
| Standard      | SFFGL Series                | Mini pc     | [f1b8de71f4](https://bsd-hardware.info/?probe=f1b8de71f4) | Sep 15, 2022 |
| Supermicro    | A2SDi-TP8F                  | Desktop     | [8c67aa0f6e](https://bsd-hardware.info/?probe=8c67aa0f6e) | Sep 15, 2022 |
| Dell          | 081N4V A04                  | Server      | [1b5150b554](https://bsd-hardware.info/?probe=1b5150b554) | Sep 15, 2022 |
| Supermicro    | X10DRL-i                    | Server      | [de856f28a4](https://bsd-hardware.info/?probe=de856f28a4) | Sep 15, 2022 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [0157925fad](https://bsd-hardware.info/?probe=0157925fad) | Sep 15, 2022 |
| Supermicro    | X11SSM-F                    | Server      | [a1dc602460](https://bsd-hardware.info/?probe=a1dc602460) | Sep 15, 2022 |
| AZW           | Green G1                    | Desktop     | [1ccd8f86b3](https://bsd-hardware.info/?probe=1ccd8f86b3) | Sep 14, 2022 |
| Protectli     | FW6                         | Desktop     | [23227c99a0](https://bsd-hardware.info/?probe=23227c99a0) | Sep 14, 2022 |
| HP            | 8103 A01                    | Mini pc     | [94ba5ceedb](https://bsd-hardware.info/?probe=94ba5ceedb) | Sep 14, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [cce6101086](https://bsd-hardware.info/?probe=cce6101086) | Sep 14, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [a444259756](https://bsd-hardware.info/?probe=a444259756) | Sep 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [992ddc4118](https://bsd-hardware.info/?probe=992ddc4118) | Sep 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e95ac333fe](https://bsd-hardware.info/?probe=e95ac333fe) | Sep 13, 2022 |
| Intel         | D945GCLF2 AAE46416-106      | Desktop     | [8e2f7792eb](https://bsd-hardware.info/?probe=8e2f7792eb) | Sep 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f023ae7ed2](https://bsd-hardware.info/?probe=f023ae7ed2) | Sep 13, 2022 |
| Deciso        | Netboard A20                | Notebook    | [8af40be425](https://bsd-hardware.info/?probe=8af40be425) | Sep 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [baaf9cbda6](https://bsd-hardware.info/?probe=baaf9cbda6) | Sep 13, 2022 |
| Protectli     | FW4B                        | Desktop     | [0553a226de](https://bsd-hardware.info/?probe=0553a226de) | Sep 13, 2022 |
| Protectli     | FW4B                        | Desktop     | [0ccd9a9f2c](https://bsd-hardware.info/?probe=0ccd9a9f2c) | Sep 12, 2022 |
| HP            | 8054                        | Desktop     | [3385f78f9c](https://bsd-hardware.info/?probe=3385f78f9c) | Sep 12, 2022 |
| MSI           | H81M-E33                    | Desktop     | [b80a45410b](https://bsd-hardware.info/?probe=b80a45410b) | Sep 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [700e6ba6a9](https://bsd-hardware.info/?probe=700e6ba6a9) | Sep 11, 2022 |
| MSI           | H81M-E33                    | Desktop     | [66d179c5f4](https://bsd-hardware.info/?probe=66d179c5f4) | Sep 11, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [1cbbe33027](https://bsd-hardware.info/?probe=1cbbe33027) | Sep 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [3b668ace72](https://bsd-hardware.info/?probe=3b668ace72) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [62c287a993](https://bsd-hardware.info/?probe=62c287a993) | Sep 11, 2022 |
| Dell          | XPS M1330                   | Notebook    | [d84548dd9b](https://bsd-hardware.info/?probe=d84548dd9b) | Sep 11, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [ce6906d604](https://bsd-hardware.info/?probe=ce6906d604) | Sep 10, 2022 |
| MSI           | A88XM-E45                   | Desktop     | [2df6d013e9](https://bsd-hardware.info/?probe=2df6d013e9) | Sep 10, 2022 |
| HP            | 8103 A01                    | Mini pc     | [34f00f7f28](https://bsd-hardware.info/?probe=34f00f7f28) | Sep 10, 2022 |
| CONTEC        | G1/EMB-CV1/iD2550           | Desktop     | [0df35f9c64](https://bsd-hardware.info/?probe=0df35f9c64) | Sep 10, 2022 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [6b449e63d3](https://bsd-hardware.info/?probe=6b449e63d3) | Sep 10, 2022 |
| EAGLE EYE ... | BayTrail-D Rev.00           | Desktop     | [3137cdbf7c](https://bsd-hardware.info/?probe=3137cdbf7c) | Sep 09, 2022 |
| AZW           | Green G1                    | Desktop     | [b9e82f5157](https://bsd-hardware.info/?probe=b9e82f5157) | Sep 09, 2022 |
| EAGLE EYE ... | BayTrail-D Rev.00           | Desktop     | [1e62e2ea85](https://bsd-hardware.info/?probe=1e62e2ea85) | Sep 09, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [4e393e3814](https://bsd-hardware.info/?probe=4e393e3814) | Sep 08, 2022 |
| Dell          | Precision 7540              | Notebook    | [f39c0f4d92](https://bsd-hardware.info/?probe=f39c0f4d92) | Sep 08, 2022 |
| Protectli     | FW4B                        | Desktop     | [b934171c54](https://bsd-hardware.info/?probe=b934171c54) | Sep 07, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [3c3c40a10f](https://bsd-hardware.info/?probe=3c3c40a10f) | Sep 07, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [f431032a32](https://bsd-hardware.info/?probe=f431032a32) | Sep 07, 2022 |
| HP            | 1495                        | Desktop     | [4ba1b5820e](https://bsd-hardware.info/?probe=4ba1b5820e) | Sep 06, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [00ee0319aa](https://bsd-hardware.info/?probe=00ee0319aa) | Sep 06, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [817b37c259](https://bsd-hardware.info/?probe=817b37c259) | Sep 06, 2022 |
| Dell          | Precision 7550              | Notebook    | [d2bf200529](https://bsd-hardware.info/?probe=d2bf200529) | Sep 06, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [34bc2f5c5b](https://bsd-hardware.info/?probe=34bc2f5c5b) | Sep 04, 2022 |
| HP            | ProLiant DL20 Gen9          | Server      | [1eb31c7e35](https://bsd-hardware.info/?probe=1eb31c7e35) | Sep 04, 2022 |
| HP            | ProLiant DL360 G5           | Server      | [770f185ee2](https://bsd-hardware.info/?probe=770f185ee2) | Sep 04, 2022 |
| Dell          | 0H5J4J A01                  | Server      | [ab1c1b4aad](https://bsd-hardware.info/?probe=ab1c1b4aad) | Sep 04, 2022 |
| MSI           | H81M-P33                    | Desktop     | [3f7258c807](https://bsd-hardware.info/?probe=3f7258c807) | Sep 04, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [cced3168c8](https://bsd-hardware.info/?probe=cced3168c8) | Sep 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [61b82d5ebb](https://bsd-hardware.info/?probe=61b82d5ebb) | Sep 04, 2022 |
| HP            | ProLiant DL360 G5           | Server      | [387e5946f7](https://bsd-hardware.info/?probe=387e5946f7) | Sep 04, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [a769499d94](https://bsd-hardware.info/?probe=a769499d94) | Sep 04, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [0f35d398cb](https://bsd-hardware.info/?probe=0f35d398cb) | Sep 04, 2022 |
| Protectli     | FW4B                        | Desktop     | [86a4422a0f](https://bsd-hardware.info/?probe=86a4422a0f) | Sep 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [4034fae93d](https://bsd-hardware.info/?probe=4034fae93d) | Sep 04, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [5ea71c99c7](https://bsd-hardware.info/?probe=5ea71c99c7) | Sep 03, 2022 |
| Dell          | 0WMJ54 A00                  | Desktop     | [39ee331ecb](https://bsd-hardware.info/?probe=39ee331ecb) | Sep 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [b2e4674180](https://bsd-hardware.info/?probe=b2e4674180) | Sep 03, 2022 |
| Protectli     | FW4B                        | Desktop     | [1e384b1cf6](https://bsd-hardware.info/?probe=1e384b1cf6) | Sep 02, 2022 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [ce9dc034c9](https://bsd-hardware.info/?probe=ce9dc034c9) | Sep 02, 2022 |
| HP            | 213D A01                    | Desktop     | [5e8fa931ef](https://bsd-hardware.info/?probe=5e8fa931ef) | Sep 02, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [73304d07bb](https://bsd-hardware.info/?probe=73304d07bb) | Sep 01, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [9148bf85ec](https://bsd-hardware.info/?probe=9148bf85ec) | Sep 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [b62a001fe9](https://bsd-hardware.info/?probe=b62a001fe9) | Sep 01, 2022 |
| Dell          | 07F37C A01                  | Desktop     | [53de9cce89](https://bsd-hardware.info/?probe=53de9cce89) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [4e58d828cc](https://bsd-hardware.info/?probe=4e58d828cc) | Sep 01, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [78b1cb4ae5](https://bsd-hardware.info/?probe=78b1cb4ae5) | Aug 31, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [77f98904c2](https://bsd-hardware.info/?probe=77f98904c2) | Aug 31, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [0563755b0d](https://bsd-hardware.info/?probe=0563755b0d) | Aug 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [e8259494a3](https://bsd-hardware.info/?probe=e8259494a3) | Aug 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [98d9c506c9](https://bsd-hardware.info/?probe=98d9c506c9) | Aug 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [6bc59f4024](https://bsd-hardware.info/?probe=6bc59f4024) | Aug 30, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [8d047e7667](https://bsd-hardware.info/?probe=8d047e7667) | Aug 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [411daea5f8](https://bsd-hardware.info/?probe=411daea5f8) | Aug 29, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [97bf732bfe](https://bsd-hardware.info/?probe=97bf732bfe) | Aug 29, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [19e3294fe9](https://bsd-hardware.info/?probe=19e3294fe9) | Aug 29, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [4d7efd6aa6](https://bsd-hardware.info/?probe=4d7efd6aa6) | Aug 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [a3677591ec](https://bsd-hardware.info/?probe=a3677591ec) | Aug 28, 2022 |
| MSI           | H81M-P33                    | Desktop     | [4d00b83ad4](https://bsd-hardware.info/?probe=4d00b83ad4) | Aug 28, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [6c1bc8d99f](https://bsd-hardware.info/?probe=6c1bc8d99f) | Aug 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4e55957971](https://bsd-hardware.info/?probe=4e55957971) | Aug 28, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [079adb24f8](https://bsd-hardware.info/?probe=079adb24f8) | Aug 28, 2022 |
| Dell          | PowerEdge R610              | Server      | [6006aed07f](https://bsd-hardware.info/?probe=6006aed07f) | Aug 28, 2022 |
| Dell          | Precision 7550              | Notebook    | [71f615178f](https://bsd-hardware.info/?probe=71f615178f) | Aug 27, 2022 |
| Supermicro    | X8DTL                       | Server      | [37350b3ac0](https://bsd-hardware.info/?probe=37350b3ac0) | Aug 27, 2022 |
| Supermicro    | X10SLM+-LN4F                | Server      | [70a786b8b5](https://bsd-hardware.info/?probe=70a786b8b5) | Aug 27, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [29d63f7027](https://bsd-hardware.info/?probe=29d63f7027) | Aug 27, 2022 |
| Dell          | 030VXY A02                  | Desktop     | [9acd691261](https://bsd-hardware.info/?probe=9acd691261) | Aug 26, 2022 |
| HP            | 21B4 A01                    | Desktop     | [93eab13f35](https://bsd-hardware.info/?probe=93eab13f35) | Aug 26, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [05d009b0df](https://bsd-hardware.info/?probe=05d009b0df) | Aug 26, 2022 |
| Unknown       | YL-E3845L4-V2               | Desktop     | [ee6fe793f2](https://bsd-hardware.info/?probe=ee6fe793f2) | Aug 24, 2022 |
| Dell          | 04YP6J A02                  | Desktop     | [38269a215a](https://bsd-hardware.info/?probe=38269a215a) | Aug 24, 2022 |
| Protectli     | VP2410                      | Desktop     | [67a5cd38d0](https://bsd-hardware.info/?probe=67a5cd38d0) | Aug 24, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [55090e4971](https://bsd-hardware.info/?probe=55090e4971) | Aug 24, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [f237a01839](https://bsd-hardware.info/?probe=f237a01839) | Aug 24, 2022 |
| Supermicro    | A1SRi                       | Mini pc     | [55a9138af4](https://bsd-hardware.info/?probe=55a9138af4) | Aug 23, 2022 |
| Supermicro    | X11SDW-4C-TP13F             | Desktop     | [84a08c6936](https://bsd-hardware.info/?probe=84a08c6936) | Aug 23, 2022 |
| Dell          | 0M877N A00                  | Server      | [acabd589fa](https://bsd-hardware.info/?probe=acabd589fa) | Aug 23, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [17f4ac1979](https://bsd-hardware.info/?probe=17f4ac1979) | Aug 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [8d3dee7258](https://bsd-hardware.info/?probe=8d3dee7258) | Aug 23, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [44013a98bb](https://bsd-hardware.info/?probe=44013a98bb) | Aug 23, 2022 |
| Dell          | 0K29HN A01                  | Server      | [f96cb98005](https://bsd-hardware.info/?probe=f96cb98005) | Aug 23, 2022 |
| Protectli     | FW4B                        | Desktop     | [d2dd7771d2](https://bsd-hardware.info/?probe=d2dd7771d2) | Aug 22, 2022 |
| BESSTAR Te... | GK45                        | Convertible | [6399352798](https://bsd-hardware.info/?probe=6399352798) | Aug 21, 2022 |
| Dell          | 0PC5F7 A00                  | Desktop     | [27049ee122](https://bsd-hardware.info/?probe=27049ee122) | Aug 21, 2022 |
| Dell          | 02C2CP A06                  | Server      | [7c432603cf](https://bsd-hardware.info/?probe=7c432603cf) | Aug 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [89535fc84c](https://bsd-hardware.info/?probe=89535fc84c) | Aug 21, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [ac2d88c2dd](https://bsd-hardware.info/?probe=ac2d88c2dd) | Aug 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b5786b8119](https://bsd-hardware.info/?probe=b5786b8119) | Aug 21, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | Notebook    | [296e81dd9d](https://bsd-hardware.info/?probe=296e81dd9d) | Aug 21, 2022 |
| Cisco         | ASA5525 A0                  | Desktop     | [5a8641fc9d](https://bsd-hardware.info/?probe=5a8641fc9d) | Aug 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [15a2225cc6](https://bsd-hardware.info/?probe=15a2225cc6) | Aug 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [1dfb3adb6b](https://bsd-hardware.info/?probe=1dfb3adb6b) | Aug 20, 2022 |
| Cisco         | ASA5525 A0                  | Desktop     | [80152a4fc3](https://bsd-hardware.info/?probe=80152a4fc3) | Aug 20, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [6412c2a8e3](https://bsd-hardware.info/?probe=6412c2a8e3) | Aug 20, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | Notebook    | [b79fa4531e](https://bsd-hardware.info/?probe=b79fa4531e) | Aug 20, 2022 |
| Lenovo        | ThinkPad 11e 4th Gen 20H... | Notebook    | [ba1ea734b1](https://bsd-hardware.info/?probe=ba1ea734b1) | Aug 19, 2022 |
| Dell          | 00W9X3 A00                  | Server      | [869769654b](https://bsd-hardware.info/?probe=869769654b) | Aug 19, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [ce0d33d973](https://bsd-hardware.info/?probe=ce0d33d973) | Aug 19, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [7ec18da9e4](https://bsd-hardware.info/?probe=7ec18da9e4) | Aug 19, 2022 |
| Protectli     | FW4B                        | Desktop     | [2fdd88b8b8](https://bsd-hardware.info/?probe=2fdd88b8b8) | Aug 19, 2022 |
| Dell          | 0PTTT9 A00                  | Desktop     | [c7490e7180](https://bsd-hardware.info/?probe=c7490e7180) | Aug 18, 2022 |
| Dell          | 03XKDV A02                  | Server      | [88bb2bdb40](https://bsd-hardware.info/?probe=88bb2bdb40) | Aug 18, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [6f22c3a6e3](https://bsd-hardware.info/?probe=6f22c3a6e3) | Aug 18, 2022 |
| Google        | Peppy                       | Notebook    | [e2e0a1953d](https://bsd-hardware.info/?probe=e2e0a1953d) | Aug 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [52da85a309](https://bsd-hardware.info/?probe=52da85a309) | Aug 18, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [a4e8c2c77e](https://bsd-hardware.info/?probe=a4e8c2c77e) | Aug 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [029b31e61f](https://bsd-hardware.info/?probe=029b31e61f) | Aug 17, 2022 |
| CncTion       | J4125-4L-I225               | Desktop     | [ec4f43e1bb](https://bsd-hardware.info/?probe=ec4f43e1bb) | Aug 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [db2cb12805](https://bsd-hardware.info/?probe=db2cb12805) | Aug 17, 2022 |
| Dell          | Studio 1537                 | Notebook    | [a185649600](https://bsd-hardware.info/?probe=a185649600) | Aug 17, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [e09aa880f9](https://bsd-hardware.info/?probe=e09aa880f9) | Aug 16, 2022 |
| Dell          | 0D6H9T A03                  | Desktop     | [16e5b72b64](https://bsd-hardware.info/?probe=16e5b72b64) | Aug 16, 2022 |
| ASRock        | B460M-HDV                   | Desktop     | [9b48c66296](https://bsd-hardware.info/?probe=9b48c66296) | Aug 15, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [29c3379293](https://bsd-hardware.info/?probe=29c3379293) | Aug 15, 2022 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [179d983936](https://bsd-hardware.info/?probe=179d983936) | Aug 14, 2022 |
| HP            | 8103 A01                    | Mini pc     | [af7da50546](https://bsd-hardware.info/?probe=af7da50546) | Aug 14, 2022 |
| MSI           | H81M-P33                    | Desktop     | [3d0836d403](https://bsd-hardware.info/?probe=3d0836d403) | Aug 14, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [c50be0ecae](https://bsd-hardware.info/?probe=c50be0ecae) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4b6ad32189](https://bsd-hardware.info/?probe=4b6ad32189) | Aug 14, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [f453f94dd3](https://bsd-hardware.info/?probe=f453f94dd3) | Aug 14, 2022 |
| MiTAC         | PH11CMI                     | Desktop     | [8656b8a7b9](https://bsd-hardware.info/?probe=8656b8a7b9) | Aug 14, 2022 |
| HP            | 82B4                        | Desktop     | [f8c65040bf](https://bsd-hardware.info/?probe=f8c65040bf) | Aug 13, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [35f0eac5f1](https://bsd-hardware.info/?probe=35f0eac5f1) | Aug 13, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [6d6e03307e](https://bsd-hardware.info/?probe=6d6e03307e) | Aug 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5d4af4fba9](https://bsd-hardware.info/?probe=5d4af4fba9) | Aug 13, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [95c42fcc82](https://bsd-hardware.info/?probe=95c42fcc82) | Aug 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1292c617d2](https://bsd-hardware.info/?probe=1292c617d2) | Aug 13, 2022 |
| Sophos        | XG                          | Firewall    | [64dd2d6993](https://bsd-hardware.info/?probe=64dd2d6993) | Aug 13, 2022 |
| AZW           | GK55                        | Desktop     | [b34aad2082](https://bsd-hardware.info/?probe=b34aad2082) | Aug 12, 2022 |
| Supermicro    | X10DRU-i+                   | Desktop     | [f3ca1d1814](https://bsd-hardware.info/?probe=f3ca1d1814) | Aug 12, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [9fa2ad6213](https://bsd-hardware.info/?probe=9fa2ad6213) | Aug 12, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [12ec460778](https://bsd-hardware.info/?probe=12ec460778) | Aug 12, 2022 |
| ASRock        | X570 PG Velocita            | Desktop     | [a91ccd3112](https://bsd-hardware.info/?probe=a91ccd3112) | Aug 11, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [8bcb2eaddc](https://bsd-hardware.info/?probe=8bcb2eaddc) | Aug 11, 2022 |
| HP            | 1495                        | Desktop     | [fbfa0fdedc](https://bsd-hardware.info/?probe=fbfa0fdedc) | Aug 11, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [9d82dae644](https://bsd-hardware.info/?probe=9d82dae644) | Aug 11, 2022 |
| Dell          | 09T7VV A04                  | Server      | [addcb4cb9b](https://bsd-hardware.info/?probe=addcb4cb9b) | Aug 11, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [adc2c951c6](https://bsd-hardware.info/?probe=adc2c951c6) | Aug 10, 2022 |
| Dell          | 07F37C A01                  | Desktop     | [d263572380](https://bsd-hardware.info/?probe=d263572380) | Aug 10, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [38b569fc94](https://bsd-hardware.info/?probe=38b569fc94) | Aug 10, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [6fb93918f0](https://bsd-hardware.info/?probe=6fb93918f0) | Aug 10, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [49a60b6412](https://bsd-hardware.info/?probe=49a60b6412) | Aug 09, 2022 |
| Protectli     | VP2410                      | Desktop     | [a9ecca1096](https://bsd-hardware.info/?probe=a9ecca1096) | Aug 09, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [da2ffefdff](https://bsd-hardware.info/?probe=da2ffefdff) | Aug 07, 2022 |
| Dell          | 0PXXHP A13                  | Server      | [370151a08f](https://bsd-hardware.info/?probe=370151a08f) | Aug 07, 2022 |
| MSI           | H81M-P33                    | Desktop     | [099e1c8b15](https://bsd-hardware.info/?probe=099e1c8b15) | Aug 07, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [b96612a45b](https://bsd-hardware.info/?probe=b96612a45b) | Aug 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [29b392331d](https://bsd-hardware.info/?probe=29b392331d) | Aug 07, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [b26884e164](https://bsd-hardware.info/?probe=b26884e164) | Aug 07, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [231400295f](https://bsd-hardware.info/?probe=231400295f) | Aug 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [0185519e19](https://bsd-hardware.info/?probe=0185519e19) | Aug 06, 2022 |
| ASRock        | 970A-G                      | Desktop     | [5014e97cb5](https://bsd-hardware.info/?probe=5014e97cb5) | Aug 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [4444668ecb](https://bsd-hardware.info/?probe=4444668ecb) | Aug 06, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [67619bab07](https://bsd-hardware.info/?probe=67619bab07) | Aug 06, 2022 |
| Dell          | 02C2CP A04                  | Server      | [30602e7478](https://bsd-hardware.info/?probe=30602e7478) | Aug 06, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [cdd6baad68](https://bsd-hardware.info/?probe=cdd6baad68) | Aug 05, 2022 |
| PC Engines    | APU2                        | Desktop     | [9bc1aa868e](https://bsd-hardware.info/?probe=9bc1aa868e) | Aug 05, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [850198c512](https://bsd-hardware.info/?probe=850198c512) | Aug 05, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [cddf42b097](https://bsd-hardware.info/?probe=cddf42b097) | Aug 05, 2022 |
| Unknown       | YL-E3845L4-V2               | Desktop     | [7b27220307](https://bsd-hardware.info/?probe=7b27220307) | Aug 04, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [fe87e22e26](https://bsd-hardware.info/?probe=fe87e22e26) | Aug 04, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [2980d9d398](https://bsd-hardware.info/?probe=2980d9d398) | Aug 04, 2022 |
| ASRockRack    | X470D4U                     | Desktop     | [a32da79434](https://bsd-hardware.info/?probe=a32da79434) | Aug 04, 2022 |
| Dell          | 0KM5PX A04                  | Server      | [6245559fe6](https://bsd-hardware.info/?probe=6245559fe6) | Aug 03, 2022 |
| SmbiosType... | SmbiosType2_BoardProduct... | Desktop     | [3c63a3a259](https://bsd-hardware.info/?probe=3c63a3a259) | Aug 03, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [cdc6bc6ef8](https://bsd-hardware.info/?probe=cdc6bc6ef8) | Aug 03, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [4c0ff1f949](https://bsd-hardware.info/?probe=4c0ff1f949) | Aug 03, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [d4462c2aca](https://bsd-hardware.info/?probe=d4462c2aca) | Aug 03, 2022 |
| Dell          | Edge Gateway 5000           | Mini pc     | [1a79f4d6d8](https://bsd-hardware.info/?probe=1a79f4d6d8) | Aug 03, 2022 |
| NF792         | 1.0                         | Desktop     | [93f777a0ae](https://bsd-hardware.info/?probe=93f777a0ae) | Aug 02, 2022 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [c7f3604755](https://bsd-hardware.info/?probe=c7f3604755) | Aug 02, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f89554f1b3](https://bsd-hardware.info/?probe=f89554f1b3) | Aug 02, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [b4745f3fbf](https://bsd-hardware.info/?probe=b4745f3fbf) | Aug 01, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [910403ba69](https://bsd-hardware.info/?probe=910403ba69) | Aug 01, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [2257be098f](https://bsd-hardware.info/?probe=2257be098f) | Aug 01, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [7ba6844cb9](https://bsd-hardware.info/?probe=7ba6844cb9) | Jul 31, 2022 |
| Protectli     | FW4A Ver                    | Desktop     | [47bd308b5f](https://bsd-hardware.info/?probe=47bd308b5f) | Jul 31, 2022 |
| MSI           | H81M-P33                    | Desktop     | [10fc9a4368](https://bsd-hardware.info/?probe=10fc9a4368) | Jul 31, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [10139014e1](https://bsd-hardware.info/?probe=10139014e1) | Jul 31, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1129960acb](https://bsd-hardware.info/?probe=1129960acb) | Jul 31, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [13baedb59b](https://bsd-hardware.info/?probe=13baedb59b) | Jul 31, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5b73e61a78](https://bsd-hardware.info/?probe=5b73e61a78) | Jul 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [125a4a6501](https://bsd-hardware.info/?probe=125a4a6501) | Jul 31, 2022 |
| Dell          | 01V648 A03                  | Server      | [33aed2a5c1](https://bsd-hardware.info/?probe=33aed2a5c1) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [7c5137f2f8](https://bsd-hardware.info/?probe=7c5137f2f8) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [3f6e556a7c](https://bsd-hardware.info/?probe=3f6e556a7c) | Jul 30, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [0887dc2e0e](https://bsd-hardware.info/?probe=0887dc2e0e) | Jul 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [d6920a8af5](https://bsd-hardware.info/?probe=d6920a8af5) | Jul 30, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [4e108a3b49](https://bsd-hardware.info/?probe=4e108a3b49) | Jul 30, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [168056c169](https://bsd-hardware.info/?probe=168056c169) | Jul 30, 2022 |
| WesternDig... | BBC 0001                    | Desktop     | [5673b5c8e8](https://bsd-hardware.info/?probe=5673b5c8e8) | Jul 29, 2022 |
| HP            | 213D A01                    | Desktop     | [c24cba449b](https://bsd-hardware.info/?probe=c24cba449b) | Jul 29, 2022 |
| Acer          | Veriton X275                | Desktop     | [8fdb6785a9](https://bsd-hardware.info/?probe=8fdb6785a9) | Jul 29, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [5d4d3d7553](https://bsd-hardware.info/?probe=5d4d3d7553) | Jul 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cd35c4b6ce](https://bsd-hardware.info/?probe=cd35c4b6ce) | Jul 29, 2022 |
| AAEON         | MIX-TLUD1 V1.0              | Desktop     | [6b1ea56289](https://bsd-hardware.info/?probe=6b1ea56289) | Jul 29, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [eb7ac52c45](https://bsd-hardware.info/?probe=eb7ac52c45) | Jul 28, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [d7b0e73f03](https://bsd-hardware.info/?probe=d7b0e73f03) | Jul 27, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [3db94efbf6](https://bsd-hardware.info/?probe=3db94efbf6) | Jul 27, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [9597e7c0cc](https://bsd-hardware.info/?probe=9597e7c0cc) | Jul 27, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [32ed0bcfa9](https://bsd-hardware.info/?probe=32ed0bcfa9) | Jul 26, 2022 |
| HP            | 18E7                        | Desktop     | [0d18e24e2e](https://bsd-hardware.info/?probe=0d18e24e2e) | Jul 26, 2022 |
| Dell          | 07F37C A01                  | Desktop     | [dfea879cdc](https://bsd-hardware.info/?probe=dfea879cdc) | Jul 26, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d32a6452bb](https://bsd-hardware.info/?probe=d32a6452bb) | Jul 25, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [9b3459c1ec](https://bsd-hardware.info/?probe=9b3459c1ec) | Jul 25, 2022 |
| Shuttle       | FS310                       | Desktop     | [4dd7894e83](https://bsd-hardware.info/?probe=4dd7894e83) | Jul 25, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [bf4826f24c](https://bsd-hardware.info/?probe=bf4826f24c) | Jul 24, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [84cfd4b073](https://bsd-hardware.info/?probe=84cfd4b073) | Jul 24, 2022 |
| AAEON         | FWS-2350 V1.0               | Desktop     | [e16dd36daf](https://bsd-hardware.info/?probe=e16dd36daf) | Jul 24, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2f7e57d927](https://bsd-hardware.info/?probe=2f7e57d927) | Jul 24, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [6fd0d31624](https://bsd-hardware.info/?probe=6fd0d31624) | Jul 24, 2022 |
| Dell          | 04Y8V0 A02                  | Desktop     | [4ab59b9029](https://bsd-hardware.info/?probe=4ab59b9029) | Jul 24, 2022 |
| Dell          | Precision 5560              | Notebook    | [3dc82c6d91](https://bsd-hardware.info/?probe=3dc82c6d91) | Jul 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [b392e9fcc9](https://bsd-hardware.info/?probe=b392e9fcc9) | Jul 23, 2022 |
| AWOW          | AK34Pro                     | Mini pc     | [dc862477ff](https://bsd-hardware.info/?probe=dc862477ff) | Jul 23, 2022 |
| HP            | 8103 A01                    | Mini pc     | [17be7e6c35](https://bsd-hardware.info/?probe=17be7e6c35) | Jul 23, 2022 |
| HP            | 213D A01                    | Desktop     | [26c8ae3969](https://bsd-hardware.info/?probe=26c8ae3969) | Jul 22, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [224d08a214](https://bsd-hardware.info/?probe=224d08a214) | Jul 22, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [0bf33c9e69](https://bsd-hardware.info/?probe=0bf33c9e69) | Jul 22, 2022 |
| HP            | 82A2                        | Desktop     | [7ec5ec44a5](https://bsd-hardware.info/?probe=7ec5ec44a5) | Jul 21, 2022 |
| Dell          | 08VT7V A05                  | Server      | [681d1997eb](https://bsd-hardware.info/?probe=681d1997eb) | Jul 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [52cc45aba9](https://bsd-hardware.info/?probe=52cc45aba9) | Jul 21, 2022 |
| Protectli     | FW6                         | Desktop     | [5a13dd0c28](https://bsd-hardware.info/?probe=5a13dd0c28) | Jul 21, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [7dfb067d40](https://bsd-hardware.info/?probe=7dfb067d40) | Jul 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [3182740b56](https://bsd-hardware.info/?probe=3182740b56) | Jul 21, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [70c9122b95](https://bsd-hardware.info/?probe=70c9122b95) | Jul 20, 2022 |
| Unknown       | YL-E3854L4-V2               | Desktop     | [cd601ead3a](https://bsd-hardware.info/?probe=cd601ead3a) | Jul 20, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [321d3333dd](https://bsd-hardware.info/?probe=321d3333dd) | Jul 19, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [6308d8da4f](https://bsd-hardware.info/?probe=6308d8da4f) | Jul 19, 2022 |
| Dell          | 08HPGT A02                  | Desktop     | [ae260e17eb](https://bsd-hardware.info/?probe=ae260e17eb) | Jul 19, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [ae58265601](https://bsd-hardware.info/?probe=ae58265601) | Jul 18, 2022 |
| Deciso        | Netboard A20                | Notebook    | [2bc988b18a](https://bsd-hardware.info/?probe=2bc988b18a) | Jul 18, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [15c5d9fdd9](https://bsd-hardware.info/?probe=15c5d9fdd9) | Jul 17, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [e4e89253c3](https://bsd-hardware.info/?probe=e4e89253c3) | Jul 17, 2022 |
| Deciso        | Netboard A20                | Notebook    | [a4be4171b6](https://bsd-hardware.info/?probe=a4be4171b6) | Jul 17, 2022 |
| MSI           | H81M-P33                    | Desktop     | [c9d1bc6685](https://bsd-hardware.info/?probe=c9d1bc6685) | Jul 17, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [7c02a92f29](https://bsd-hardware.info/?probe=7c02a92f29) | Jul 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [3bf44f4bb5](https://bsd-hardware.info/?probe=3bf44f4bb5) | Jul 17, 2022 |
| Lenovo        | 361A SDK0J40700 WIN 3258... | Desktop     | [8671985fad](https://bsd-hardware.info/?probe=8671985fad) | Jul 17, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [64b17b1b35](https://bsd-hardware.info/?probe=64b17b1b35) | Jul 17, 2022 |
| Dell          | 04Y8V0 A02                  | Desktop     | [5bba9aafa1](https://bsd-hardware.info/?probe=5bba9aafa1) | Jul 17, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [3c7cfd537b](https://bsd-hardware.info/?probe=3c7cfd537b) | Jul 17, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [23f1880e42](https://bsd-hardware.info/?probe=23f1880e42) | Jul 16, 2022 |
| HP            | 1589                        | Desktop     | [3f9d19b372](https://bsd-hardware.info/?probe=3f9d19b372) | Jul 16, 2022 |
| Dell          | 051FJ8 A02                  | Desktop     | [39de8d3c92](https://bsd-hardware.info/?probe=39de8d3c92) | Jul 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [e294973f12](https://bsd-hardware.info/?probe=e294973f12) | Jul 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9771cb16c0](https://bsd-hardware.info/?probe=9771cb16c0) | Jul 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [1058650b8e](https://bsd-hardware.info/?probe=1058650b8e) | Jul 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [e4795fcc70](https://bsd-hardware.info/?probe=e4795fcc70) | Jul 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1e8b0433e8](https://bsd-hardware.info/?probe=1e8b0433e8) | Jul 15, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [f087f83248](https://bsd-hardware.info/?probe=f087f83248) | Jul 14, 2022 |
| Lenovo        | ThinkPad X260 20F6S0KA00    | Notebook    | [117014d55f](https://bsd-hardware.info/?probe=117014d55f) | Jul 14, 2022 |
| Dell          | 02C2CP A04                  | Server      | [3c3ab6b2c6](https://bsd-hardware.info/?probe=3c3ab6b2c6) | Jul 14, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [e567cc10e7](https://bsd-hardware.info/?probe=e567cc10e7) | Jul 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [85a49cb7be](https://bsd-hardware.info/?probe=85a49cb7be) | Jul 14, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [300b7cfcb6](https://bsd-hardware.info/?probe=300b7cfcb6) | Jul 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5f63e8291a](https://bsd-hardware.info/?probe=5f63e8291a) | Jul 13, 2022 |
| Supermicro    | A1SRi-2558F                 | Mini pc     | [698d59d94e](https://bsd-hardware.info/?probe=698d59d94e) | Jul 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [46e618c773](https://bsd-hardware.info/?probe=46e618c773) | Jul 13, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [ffb2821bab](https://bsd-hardware.info/?probe=ffb2821bab) | Jul 13, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [894b6f82cf](https://bsd-hardware.info/?probe=894b6f82cf) | Jul 13, 2022 |
| Dell          | 01G5C3 A02                  | Server      | [ca50b43cb8](https://bsd-hardware.info/?probe=ca50b43cb8) | Jul 13, 2022 |
| Deciso        | Netboard A20                | Notebook    | [743b330db3](https://bsd-hardware.info/?probe=743b330db3) | Jul 12, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [3f5548c246](https://bsd-hardware.info/?probe=3f5548c246) | Jul 12, 2022 |
| ASRock        | X570 PG Velocita            | Desktop     | [ceb7ed4c1e](https://bsd-hardware.info/?probe=ceb7ed4c1e) | Jul 12, 2022 |
| PC Engines    | APU2                        | Desktop     | [57b035462a](https://bsd-hardware.info/?probe=57b035462a) | Jul 12, 2022 |
| Toshiba       | Satellite L305D             | Notebook    | [b0311b8175](https://bsd-hardware.info/?probe=b0311b8175) | Jul 12, 2022 |
| Protectli     | FW2 Ver                     | Desktop     | [89ba2534c0](https://bsd-hardware.info/?probe=89ba2534c0) | Jul 12, 2022 |
| Dell          | 01G5C3 A02                  | Server      | [266891233d](https://bsd-hardware.info/?probe=266891233d) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [7081ddd59c](https://bsd-hardware.info/?probe=7081ddd59c) | Jul 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [322ee9f1c9](https://bsd-hardware.info/?probe=322ee9f1c9) | Jul 11, 2022 |
| SmbiosType... | SmbiosType2_BoardProduct... | Desktop     | [eee15ff905](https://bsd-hardware.info/?probe=eee15ff905) | Jul 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [abf18d0628](https://bsd-hardware.info/?probe=abf18d0628) | Jul 11, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [0ff1996217](https://bsd-hardware.info/?probe=0ff1996217) | Jul 11, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ce9c6efd80](https://bsd-hardware.info/?probe=ce9c6efd80) | Jul 11, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [b4f18ad479](https://bsd-hardware.info/?probe=b4f18ad479) | Jul 11, 2022 |
| HP            | 1495                        | Desktop     | [7ed22254af](https://bsd-hardware.info/?probe=7ed22254af) | Jul 11, 2022 |
| HP            | 1495                        | Desktop     | [1bf0dc0f98](https://bsd-hardware.info/?probe=1bf0dc0f98) | Jul 11, 2022 |
| Supermicro    | X10SBAB                     | Server      | [1bf38a759a](https://bsd-hardware.info/?probe=1bf38a759a) | Jul 10, 2022 |
| MSI           | H81M-P33                    | Desktop     | [698249149d](https://bsd-hardware.info/?probe=698249149d) | Jul 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c2a2cdcbbb](https://bsd-hardware.info/?probe=c2a2cdcbbb) | Jul 10, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [0c830d88dc](https://bsd-hardware.info/?probe=0c830d88dc) | Jul 10, 2022 |
| Protectli     | FW6                         | Desktop     | [cf0a97896f](https://bsd-hardware.info/?probe=cf0a97896f) | Jul 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4c74cdfb76](https://bsd-hardware.info/?probe=4c74cdfb76) | Jul 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [6edc61f549](https://bsd-hardware.info/?probe=6edc61f549) | Jul 10, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [eec1480bc7](https://bsd-hardware.info/?probe=eec1480bc7) | Jul 10, 2022 |
| Toshiba       | Satellite L305D             | Notebook    | [ed950787b0](https://bsd-hardware.info/?probe=ed950787b0) | Jul 10, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f9226218a0](https://bsd-hardware.info/?probe=f9226218a0) | Jul 09, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [202827c443](https://bsd-hardware.info/?probe=202827c443) | Jul 09, 2022 |
| Supermicro    | X11SBA-LN4F                 | Desktop     | [fc85312fc7](https://bsd-hardware.info/?probe=fc85312fc7) | Jul 08, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [3c9057ab65](https://bsd-hardware.info/?probe=3c9057ab65) | Jul 08, 2022 |
| Dell          | 01TJ2K A02                  | Desktop     | [467070c750](https://bsd-hardware.info/?probe=467070c750) | Jul 08, 2022 |
| Protectli     | VP2410                      | Desktop     | [e5c8ed1549](https://bsd-hardware.info/?probe=e5c8ed1549) | Jul 07, 2022 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [0819ecdcf9](https://bsd-hardware.info/?probe=0819ecdcf9) | Jul 07, 2022 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [d459d3431a](https://bsd-hardware.info/?probe=d459d3431a) | Jul 07, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [7bad2fce01](https://bsd-hardware.info/?probe=7bad2fce01) | Jul 07, 2022 |
| Dell          | Latitude E6420              | Notebook    | [c41c8ff4f4](https://bsd-hardware.info/?probe=c41c8ff4f4) | Jul 07, 2022 |
| Unknown       | YL-E3854L4-V2               | Desktop     | [1326524180](https://bsd-hardware.info/?probe=1326524180) | Jul 07, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [9e17b85d9b](https://bsd-hardware.info/?probe=9e17b85d9b) | Jul 06, 2022 |
| Dell          | 0F9NPY A02                  | Server      | [f1bb207022](https://bsd-hardware.info/?probe=f1bb207022) | Jul 06, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [5d668f86de](https://bsd-hardware.info/?probe=5d668f86de) | Jul 06, 2022 |
| MiTAC         | PH11CMI                     | Desktop     | [9111d63b0a](https://bsd-hardware.info/?probe=9111d63b0a) | Jul 06, 2022 |
| ASRock        | X570 PG Velocita            | Desktop     | [08359c2723](https://bsd-hardware.info/?probe=08359c2723) | Jul 06, 2022 |
| Dell          | 0F9NPY A02                  | Server      | [919d608fda](https://bsd-hardware.info/?probe=919d608fda) | Jul 05, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [bc786895e5](https://bsd-hardware.info/?probe=bc786895e5) | Jul 05, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [ebc1f9cbf1](https://bsd-hardware.info/?probe=ebc1f9cbf1) | Jul 05, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [5116ea39c1](https://bsd-hardware.info/?probe=5116ea39c1) | Jul 05, 2022 |
| Protectli     | FW6E                        | Desktop     | [efa044fab5](https://bsd-hardware.info/?probe=efa044fab5) | Jul 05, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [eb4105a1ba](https://bsd-hardware.info/?probe=eb4105a1ba) | Jul 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [584ecf8423](https://bsd-hardware.info/?probe=584ecf8423) | Jul 05, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [85404f4f29](https://bsd-hardware.info/?probe=85404f4f29) | Jul 04, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [041ad7f035](https://bsd-hardware.info/?probe=041ad7f035) | Jul 04, 2022 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [886522d5e6](https://bsd-hardware.info/?probe=886522d5e6) | Jul 04, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [81e9f8506f](https://bsd-hardware.info/?probe=81e9f8506f) | Jul 04, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [d82547b583](https://bsd-hardware.info/?probe=d82547b583) | Jul 04, 2022 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [a3cba2571b](https://bsd-hardware.info/?probe=a3cba2571b) | Jul 04, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [ce09ce2aa9](https://bsd-hardware.info/?probe=ce09ce2aa9) | Jul 04, 2022 |
| Dell          | 01TJ2K A02                  | Desktop     | [b9037d1fb0](https://bsd-hardware.info/?probe=b9037d1fb0) | Jul 04, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [f261de9b25](https://bsd-hardware.info/?probe=f261de9b25) | Jul 03, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [34ada293b1](https://bsd-hardware.info/?probe=34ada293b1) | Jul 03, 2022 |
| MSI           | H81M-P33                    | Desktop     | [e482fbe2d2](https://bsd-hardware.info/?probe=e482fbe2d2) | Jul 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d5dd169581](https://bsd-hardware.info/?probe=d5dd169581) | Jul 03, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [7a998b2fa4](https://bsd-hardware.info/?probe=7a998b2fa4) | Jul 03, 2022 |
| HP            | 843F                        | Desktop     | [30700c4158](https://bsd-hardware.info/?probe=30700c4158) | Jul 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [720d51613e](https://bsd-hardware.info/?probe=720d51613e) | Jul 03, 2022 |
| HP            | ProLiant DL20 Gen9          | Server      | [f82d95a462](https://bsd-hardware.info/?probe=f82d95a462) | Jul 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [5b79558a40](https://bsd-hardware.info/?probe=5b79558a40) | Jul 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [699fea1ac9](https://bsd-hardware.info/?probe=699fea1ac9) | Jul 02, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [452aabec42](https://bsd-hardware.info/?probe=452aabec42) | Jul 02, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [3c2e2da462](https://bsd-hardware.info/?probe=3c2e2da462) | Jul 02, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [5ec12d679e](https://bsd-hardware.info/?probe=5ec12d679e) | Jul 01, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [83349fd2bf](https://bsd-hardware.info/?probe=83349fd2bf) | Jul 01, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [b870cd3698](https://bsd-hardware.info/?probe=b870cd3698) | Jul 01, 2022 |
| Intel         | NUC8i5BESB K75953-303       | Mini pc     | [b0a9749159](https://bsd-hardware.info/?probe=b0a9749159) | Jul 01, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | Notebook    | [5777cb6dc6](https://bsd-hardware.info/?probe=5777cb6dc6) | Jul 01, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [8cdc3bd7ab](https://bsd-hardware.info/?probe=8cdc3bd7ab) | Jul 01, 2022 |
| Supermicro    | X11SSQ-L-DE05BA             | Server      | [6244e44f35](https://bsd-hardware.info/?probe=6244e44f35) | Jun 30, 2022 |
| Unknown       | Unknown                     | Notebook    | [d9e6e5b83a](https://bsd-hardware.info/?probe=d9e6e5b83a) | Jun 29, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [ace8b06cd3](https://bsd-hardware.info/?probe=ace8b06cd3) | Jun 29, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [7c1ae96d22](https://bsd-hardware.info/?probe=7c1ae96d22) | Jun 29, 2022 |
| CloudGenix    | ion 2000                    | Firewall    | [1c489d4e2e](https://bsd-hardware.info/?probe=1c489d4e2e) | Jun 28, 2022 |
| PC Engines    | apu4                        | Desktop     | [b139faa593](https://bsd-hardware.info/?probe=b139faa593) | Jun 28, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [56594ec74b](https://bsd-hardware.info/?probe=56594ec74b) | Jun 28, 2022 |
| Toshiba       | PORTEGE R700                | Notebook    | [d9c359c2ab](https://bsd-hardware.info/?probe=d9c359c2ab) | Jun 28, 2022 |
| AZW           | Green G1                    | Desktop     | [8364810fca](https://bsd-hardware.info/?probe=8364810fca) | Jun 27, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [e0c49be06e](https://bsd-hardware.info/?probe=e0c49be06e) | Jun 27, 2022 |
| AZW           | GK55                        | Desktop     | [82e212ab9e](https://bsd-hardware.info/?probe=82e212ab9e) | Jun 27, 2022 |
| Supermicro    | X10SRL-F                    | Server      | [1499a2903d](https://bsd-hardware.info/?probe=1499a2903d) | Jun 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3f2f69321d](https://bsd-hardware.info/?probe=3f2f69321d) | Jun 27, 2022 |
| ASUSTek       | ROG STRIX Z590-I GAMING ... | Desktop     | [b628bb87a6](https://bsd-hardware.info/?probe=b628bb87a6) | Jun 26, 2022 |
| MSI           | H81M-P33                    | Desktop     | [079fcf320f](https://bsd-hardware.info/?probe=079fcf320f) | Jun 26, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [bbc59d9815](https://bsd-hardware.info/?probe=bbc59d9815) | Jun 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [6eb02df970](https://bsd-hardware.info/?probe=6eb02df970) | Jun 26, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [b71ecdf543](https://bsd-hardware.info/?probe=b71ecdf543) | Jun 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [3d2f470da6](https://bsd-hardware.info/?probe=3d2f470da6) | Jun 24, 2022 |
| SmbiosType... | SmbiosType2_BoardProduct... | Desktop     | [d80af3d3b1](https://bsd-hardware.info/?probe=d80af3d3b1) | Jun 24, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [7baa424bfd](https://bsd-hardware.info/?probe=7baa424bfd) | Jun 23, 2022 |
| ALLEGIANCE... | X79 V3.3F                   | Desktop     | [190560a4f4](https://bsd-hardware.info/?probe=190560a4f4) | Jun 23, 2022 |
| Dell          | 0YDJK3 A10                  | Server      | [0fce035aee](https://bsd-hardware.info/?probe=0fce035aee) | Jun 22, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [ef2ff887f3](https://bsd-hardware.info/?probe=ef2ff887f3) | Jun 22, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [9dfcf12ab1](https://bsd-hardware.info/?probe=9dfcf12ab1) | Jun 22, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [c7ea52a92e](https://bsd-hardware.info/?probe=c7ea52a92e) | Jun 22, 2022 |
| Lenovo        | ThinkPad X270 20HN001HUS    | Notebook    | [139e4817d7](https://bsd-hardware.info/?probe=139e4817d7) | Jun 21, 2022 |
| Dell          | 0RC130 A03                  | Server      | [8b59f71f96](https://bsd-hardware.info/?probe=8b59f71f96) | Jun 21, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [b0a265f65f](https://bsd-hardware.info/?probe=b0a265f65f) | Jun 21, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [0efa4b4878](https://bsd-hardware.info/?probe=0efa4b4878) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [081b5f8bec](https://bsd-hardware.info/?probe=081b5f8bec) | Jun 20, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [24d72267be](https://bsd-hardware.info/?probe=24d72267be) | Jun 19, 2022 |
| Dell          | 0CNCJW A08                  | Server      | [cd8960f886](https://bsd-hardware.info/?probe=cd8960f886) | Jun 19, 2022 |
| Dell          | 0CNCJW A08                  | Server      | [912e4925e9](https://bsd-hardware.info/?probe=912e4925e9) | Jun 19, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [5b7a6bf8f8](https://bsd-hardware.info/?probe=5b7a6bf8f8) | Jun 19, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [78716ab7b5](https://bsd-hardware.info/?probe=78716ab7b5) | Jun 19, 2022 |
| HP            | Compaq tc4400 (EN357UT#A... | Notebook    | [f4e4e3826b](https://bsd-hardware.info/?probe=f4e4e3826b) | Jun 19, 2022 |
| Protectli     | FW6D                        | Desktop     | [04f0fbbc41](https://bsd-hardware.info/?probe=04f0fbbc41) | Jun 19, 2022 |
| TYAN Compu... | Tiger K8W Dual AMD Opter... | Desktop     | [3129273bd4](https://bsd-hardware.info/?probe=3129273bd4) | Jun 18, 2022 |
| MSI           | B360I GMAING PRO AC         | Desktop     | [9d92cd0269](https://bsd-hardware.info/?probe=9d92cd0269) | Jun 18, 2022 |
| Unknown       | YL-E3854L4-V2               | Desktop     | [54003932e8](https://bsd-hardware.info/?probe=54003932e8) | Jun 17, 2022 |
| HP            | 2B29                        | Desktop     | [e8c355314e](https://bsd-hardware.info/?probe=e8c355314e) | Jun 17, 2022 |
| HP            | 1589                        | Desktop     | [3765f1cb09](https://bsd-hardware.info/?probe=3765f1cb09) | Jun 17, 2022 |
| Dell          | 0Y2G6P A03                  | Server      | [ecb370bba4](https://bsd-hardware.info/?probe=ecb370bba4) | Jun 17, 2022 |
| Biostar       | H61MGC                      | Desktop     | [c3328d9806](https://bsd-hardware.info/?probe=c3328d9806) | Jun 17, 2022 |
| Dell          | 0CNCJW A08                  | Server      | [8e0f43615e](https://bsd-hardware.info/?probe=8e0f43615e) | Jun 16, 2022 |
| Dell          | 0CNCJW A08                  | Server      | [8e5151768d](https://bsd-hardware.info/?probe=8e5151768d) | Jun 16, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [3344e5152d](https://bsd-hardware.info/?probe=3344e5152d) | Jun 16, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [9f630c894a](https://bsd-hardware.info/?probe=9f630c894a) | Jun 16, 2022 |
| ASUSTek       | ZenBook UX461FA_UX461FA     | Convertible | [3079ca74a6](https://bsd-hardware.info/?probe=3079ca74a6) | Jun 16, 2022 |
| Gigabyte      | C1007UN-D                   | Desktop     | [a8d5fadd58](https://bsd-hardware.info/?probe=a8d5fadd58) | Jun 15, 2022 |
| Dell          | 015TH9 A00                  | Server      | [9db5cc48b8](https://bsd-hardware.info/?probe=9db5cc48b8) | Jun 15, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | Notebook    | [43d7380492](https://bsd-hardware.info/?probe=43d7380492) | Jun 15, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [a9d98de213](https://bsd-hardware.info/?probe=a9d98de213) | Jun 15, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7231380d11](https://bsd-hardware.info/?probe=7231380d11) | Jun 15, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | Notebook    | [a3e3500ca5](https://bsd-hardware.info/?probe=a3e3500ca5) | Jun 15, 2022 |
| HP            | 83EE                        | Desktop     | [34235b8478](https://bsd-hardware.info/?probe=34235b8478) | Jun 14, 2022 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [5a180cc6aa](https://bsd-hardware.info/?probe=5a180cc6aa) | Jun 14, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [fcadb83b9e](https://bsd-hardware.info/?probe=fcadb83b9e) | Jun 14, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [d0be82ee85](https://bsd-hardware.info/?probe=d0be82ee85) | Jun 14, 2022 |
| Dell          | 07T4MC A02                  | Desktop     | [5b60dfdcc1](https://bsd-hardware.info/?probe=5b60dfdcc1) | Jun 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8cc71bff7d](https://bsd-hardware.info/?probe=8cc71bff7d) | Jun 13, 2022 |
| Unknown       | EMB-B75A                    | Desktop     | [a2adb81748](https://bsd-hardware.info/?probe=a2adb81748) | Jun 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [59fba84256](https://bsd-hardware.info/?probe=59fba84256) | Jun 13, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [29a12ab775](https://bsd-hardware.info/?probe=29a12ab775) | Jun 13, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [b627258b73](https://bsd-hardware.info/?probe=b627258b73) | Jun 13, 2022 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [7b19e64a0e](https://bsd-hardware.info/?probe=7b19e64a0e) | Jun 13, 2022 |
| Dell          | PowerEdge R610              | Server      | [68bd058f04](https://bsd-hardware.info/?probe=68bd058f04) | Jun 13, 2022 |
| Dell          | 0HMF7C A01                  | Desktop     | [ad0f6d4b31](https://bsd-hardware.info/?probe=ad0f6d4b31) | Jun 13, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [db92ea33c8](https://bsd-hardware.info/?probe=db92ea33c8) | Jun 12, 2022 |
| MSI           | H81M-P33                    | Desktop     | [87a66430db](https://bsd-hardware.info/?probe=87a66430db) | Jun 12, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [9b34d14850](https://bsd-hardware.info/?probe=9b34d14850) | Jun 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c281c439e8](https://bsd-hardware.info/?probe=c281c439e8) | Jun 12, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [e7017b0ea5](https://bsd-hardware.info/?probe=e7017b0ea5) | Jun 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S45W00    | Notebook    | [acfa5c94d5](https://bsd-hardware.info/?probe=acfa5c94d5) | Jun 12, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [d81151c0e8](https://bsd-hardware.info/?probe=d81151c0e8) | Jun 12, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [5215d1ebb8](https://bsd-hardware.info/?probe=5215d1ebb8) | Jun 12, 2022 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [09d6e71897](https://bsd-hardware.info/?probe=09d6e71897) | Jun 12, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [c6824c4f4a](https://bsd-hardware.info/?probe=c6824c4f4a) | Jun 11, 2022 |
| HP            | ProLiant DL20 Gen9          | Server      | [0c5556ab5f](https://bsd-hardware.info/?probe=0c5556ab5f) | Jun 11, 2022 |
| HP            | ProLiant DL20 Gen9          | Server      | [87ea02111d](https://bsd-hardware.info/?probe=87ea02111d) | Jun 10, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [a03ff6ad9e](https://bsd-hardware.info/?probe=a03ff6ad9e) | Jun 10, 2022 |
| Dell          | 0804P1 A04                  | Server      | [c8ddb7dae6](https://bsd-hardware.info/?probe=c8ddb7dae6) | Jun 10, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [65540f1006](https://bsd-hardware.info/?probe=65540f1006) | Jun 09, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [61442e8deb](https://bsd-hardware.info/?probe=61442e8deb) | Jun 09, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [d1a197ec53](https://bsd-hardware.info/?probe=d1a197ec53) | Jun 09, 2022 |
| Dell          | Precision M4800             | Notebook    | [4d77bb0082](https://bsd-hardware.info/?probe=4d77bb0082) | Jun 08, 2022 |
| Dell          | Precision M4800             | Notebook    | [b9169c863c](https://bsd-hardware.info/?probe=b9169c863c) | Jun 08, 2022 |
| HP            | 1495                        | Desktop     | [ce6fa257fd](https://bsd-hardware.info/?probe=ce6fa257fd) | Jun 08, 2022 |
| AZW           | Green G1                    | Desktop     | [0443d21ba3](https://bsd-hardware.info/?probe=0443d21ba3) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d54c86624e](https://bsd-hardware.info/?probe=d54c86624e) | Jun 08, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [2e5eb217b5](https://bsd-hardware.info/?probe=2e5eb217b5) | Jun 08, 2022 |
| ADI           | MinnowBoard Turbot          | Desktop     | [917e897373](https://bsd-hardware.info/?probe=917e897373) | Jun 07, 2022 |
| Protectli     | FW6                         | Desktop     | [85d825c3a6](https://bsd-hardware.info/?probe=85d825c3a6) | Jun 07, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [1a9b85f6c5](https://bsd-hardware.info/?probe=1a9b85f6c5) | Jun 07, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [af39fe65b7](https://bsd-hardware.info/?probe=af39fe65b7) | Jun 07, 2022 |
| Apple         | MacPro4,1                   | Desktop     | [65380f3847](https://bsd-hardware.info/?probe=65380f3847) | Jun 06, 2022 |
| Dell          | 0WMJ54 A00                  | Desktop     | [40510e311b](https://bsd-hardware.info/?probe=40510e311b) | Jun 06, 2022 |
| Sophos        | SG                          | Firewall    | [2f235d7404](https://bsd-hardware.info/?probe=2f235d7404) | Jun 06, 2022 |
| MSI           | Z590 PRO WIFI               | Desktop     | [29b410eeb6](https://bsd-hardware.info/?probe=29b410eeb6) | Jun 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [03a994458a](https://bsd-hardware.info/?probe=03a994458a) | Jun 05, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [2de97a7ff6](https://bsd-hardware.info/?probe=2de97a7ff6) | Jun 05, 2022 |
| Biostar       | Hi-Fi B85N 3D               | Desktop     | [b88e0faba8](https://bsd-hardware.info/?probe=b88e0faba8) | Jun 05, 2022 |
| MSI           | H81M-P33                    | Desktop     | [49ab973713](https://bsd-hardware.info/?probe=49ab973713) | Jun 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7f11ab4091](https://bsd-hardware.info/?probe=7f11ab4091) | Jun 05, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [10381fadd6](https://bsd-hardware.info/?probe=10381fadd6) | Jun 05, 2022 |
| HP            | 8103 A01                    | Mini pc     | [97ef9e2512](https://bsd-hardware.info/?probe=97ef9e2512) | Jun 05, 2022 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [018c0120f3](https://bsd-hardware.info/?probe=018c0120f3) | Jun 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | Notebook    | [8029eb2018](https://bsd-hardware.info/?probe=8029eb2018) | Jun 04, 2022 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [53f89519ba](https://bsd-hardware.info/?probe=53f89519ba) | Jun 04, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [0f0c2bcf67](https://bsd-hardware.info/?probe=0f0c2bcf67) | Jun 04, 2022 |
| MSI           | B360I GMAING PRO AC         | Desktop     | [f29f648413](https://bsd-hardware.info/?probe=f29f648413) | Jun 04, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [20ea25695a](https://bsd-hardware.info/?probe=20ea25695a) | Jun 04, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [8fd5398904](https://bsd-hardware.info/?probe=8fd5398904) | Jun 04, 2022 |
| HP            | 8103 A01                    | Mini pc     | [4cddf5a2c8](https://bsd-hardware.info/?probe=4cddf5a2c8) | Jun 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [6449ac13c1](https://bsd-hardware.info/?probe=6449ac13c1) | Jun 03, 2022 |
| Dell          | Latitude E5500              | Notebook    | [b1cb5de914](https://bsd-hardware.info/?probe=b1cb5de914) | Jun 03, 2022 |
| MSI           | B360I GMAING PRO AC         | Desktop     | [8754cf67fc](https://bsd-hardware.info/?probe=8754cf67fc) | Jun 03, 2022 |
| HP            | 8103 A01                    | Mini pc     | [544a5a6f8b](https://bsd-hardware.info/?probe=544a5a6f8b) | Jun 02, 2022 |
| Lenovo        | ThinkPad W520 4282AD4       | Notebook    | [40198abaa2](https://bsd-hardware.info/?probe=40198abaa2) | Jun 02, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [d55600f2bf](https://bsd-hardware.info/?probe=d55600f2bf) | Jun 02, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [207c4d519b](https://bsd-hardware.info/?probe=207c4d519b) | Jun 02, 2022 |
| Lenovo        | SHARKBAY 0B98405 STD        | Desktop     | [7820a44cbe](https://bsd-hardware.info/?probe=7820a44cbe) | Jun 01, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [4154fda8ab](https://bsd-hardware.info/?probe=4154fda8ab) | May 31, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [3e62c80025](https://bsd-hardware.info/?probe=3e62c80025) | May 31, 2022 |
| GPD           | MicroPC                     | Notebook    | [a448570ff9](https://bsd-hardware.info/?probe=a448570ff9) | May 31, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [ca9f2125af](https://bsd-hardware.info/?probe=ca9f2125af) | May 31, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [283a074737](https://bsd-hardware.info/?probe=283a074737) | May 31, 2022 |
| GPD           | MicroPC                     | Notebook    | [0046ab7c9b](https://bsd-hardware.info/?probe=0046ab7c9b) | May 31, 2022 |
| NF-M2S        | ABIT                        | Desktop     | [bef9700756](https://bsd-hardware.info/?probe=bef9700756) | May 31, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [364b3d55e4](https://bsd-hardware.info/?probe=364b3d55e4) | May 31, 2022 |
| Supermicro    | X9SCL/X9SCM                 | Desktop     | [97f4daf2ad](https://bsd-hardware.info/?probe=97f4daf2ad) | May 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [486ad2acae](https://bsd-hardware.info/?probe=486ad2acae) | May 30, 2022 |
| Protectli     | FW4B                        | Desktop     | [2b833c65c0](https://bsd-hardware.info/?probe=2b833c65c0) | May 29, 2022 |
| System76      | Galago Pro                  | Notebook    | [126ebc1522](https://bsd-hardware.info/?probe=126ebc1522) | May 29, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [0f275a65af](https://bsd-hardware.info/?probe=0f275a65af) | May 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [90b27f0ac1](https://bsd-hardware.info/?probe=90b27f0ac1) | May 29, 2022 |
| HP            | 1495                        | Desktop     | [e7fcfd6634](https://bsd-hardware.info/?probe=e7fcfd6634) | May 29, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [479e0f44cd](https://bsd-hardware.info/?probe=479e0f44cd) | May 29, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [cf67e4079f](https://bsd-hardware.info/?probe=cf67e4079f) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8ebd281f5f](https://bsd-hardware.info/?probe=8ebd281f5f) | May 29, 2022 |
| MSI           | H81M-P33                    | Desktop     | [ab2181e1b4](https://bsd-hardware.info/?probe=ab2181e1b4) | May 29, 2022 |
| Protectli     | FW6                         | Desktop     | [902d82819e](https://bsd-hardware.info/?probe=902d82819e) | May 29, 2022 |
| Dell          | Latitude E6430              | Notebook    | [d7ced37bac](https://bsd-hardware.info/?probe=d7ced37bac) | May 29, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [cb624b7a18](https://bsd-hardware.info/?probe=cb624b7a18) | May 29, 2022 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [f6bbaffaeb](https://bsd-hardware.info/?probe=f6bbaffaeb) | May 29, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [3ef083287f](https://bsd-hardware.info/?probe=3ef083287f) | May 28, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [53cb90d2b7](https://bsd-hardware.info/?probe=53cb90d2b7) | May 28, 2022 |
| ASUSTek       | P5QL-VM DO                  | Desktop     | [33145067d8](https://bsd-hardware.info/?probe=33145067d8) | May 28, 2022 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [5e08455bea](https://bsd-hardware.info/?probe=5e08455bea) | May 28, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [d134ba2206](https://bsd-hardware.info/?probe=d134ba2206) | May 28, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [0ba89b7a25](https://bsd-hardware.info/?probe=0ba89b7a25) | May 28, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [9c70320d7f](https://bsd-hardware.info/?probe=9c70320d7f) | May 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e15ce78c8](https://bsd-hardware.info/?probe=4e15ce78c8) | May 26, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [51c560673e](https://bsd-hardware.info/?probe=51c560673e) | May 26, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [6906c16701](https://bsd-hardware.info/?probe=6906c16701) | May 26, 2022 |
| HP            | 158A                        | Desktop     | [883958cd36](https://bsd-hardware.info/?probe=883958cd36) | May 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [78d1ad4565](https://bsd-hardware.info/?probe=78d1ad4565) | May 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [b1f95e9759](https://bsd-hardware.info/?probe=b1f95e9759) | May 25, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [bcf5c6db64](https://bsd-hardware.info/?probe=bcf5c6db64) | May 25, 2022 |
| BCM Advanc... | MX57QM B1                   | Desktop     | [54bafab9d8](https://bsd-hardware.info/?probe=54bafab9d8) | May 25, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [82b16236c3](https://bsd-hardware.info/?probe=82b16236c3) | May 25, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [4b97b0c947](https://bsd-hardware.info/?probe=4b97b0c947) | May 25, 2022 |
| Supermicro    | X10SDV-8C-TLN4F             | Desktop     | [4d5f6d3aa1](https://bsd-hardware.info/?probe=4d5f6d3aa1) | May 24, 2022 |
| Intel         | NUC7i7BNB J31145-306        | Mini pc     | [934edfe03d](https://bsd-hardware.info/?probe=934edfe03d) | May 24, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [db99798754](https://bsd-hardware.info/?probe=db99798754) | May 24, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [c7ff34d878](https://bsd-hardware.info/?probe=c7ff34d878) | May 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [3307493f4f](https://bsd-hardware.info/?probe=3307493f4f) | May 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a74913bffa](https://bsd-hardware.info/?probe=a74913bffa) | May 23, 2022 |
| Supermicro    | X10SRi-FB                   | Server      | [c8a2c831e9](https://bsd-hardware.info/?probe=c8a2c831e9) | May 23, 2022 |
| Deciso        | Netboard A20                | Notebook    | [eba0ffa870](https://bsd-hardware.info/?probe=eba0ffa870) | May 23, 2022 |
| Dell          | Precision M4800             | Notebook    | [6a703b66f8](https://bsd-hardware.info/?probe=6a703b66f8) | May 22, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d5a0fd71f2](https://bsd-hardware.info/?probe=d5a0fd71f2) | May 22, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [2b93a0b59f](https://bsd-hardware.info/?probe=2b93a0b59f) | May 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [becc2fddbd](https://bsd-hardware.info/?probe=becc2fddbd) | May 22, 2022 |
| Deciso        | Netboard A20                | Notebook    | [1fe95544bd](https://bsd-hardware.info/?probe=1fe95544bd) | May 22, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [c87e967424](https://bsd-hardware.info/?probe=c87e967424) | May 22, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [f48cce1f02](https://bsd-hardware.info/?probe=f48cce1f02) | May 22, 2022 |
| Timi          | TM1701                      | Notebook    | [a28220d11f](https://bsd-hardware.info/?probe=a28220d11f) | May 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [796fe84e29](https://bsd-hardware.info/?probe=796fe84e29) | May 21, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [e1121aa6ec](https://bsd-hardware.info/?probe=e1121aa6ec) | May 21, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [357e1739ca](https://bsd-hardware.info/?probe=357e1739ca) | May 21, 2022 |
| HP            | 843F                        | Desktop     | [5321d06a75](https://bsd-hardware.info/?probe=5321d06a75) | May 20, 2022 |
| Sophos        | SG                          | Firewall    | [aa183f4d0d](https://bsd-hardware.info/?probe=aa183f4d0d) | May 20, 2022 |
| HP            | 8767 A                      | Desktop     | [ac8a395a20](https://bsd-hardware.info/?probe=ac8a395a20) | May 20, 2022 |
| HP            | Pavilion dv6                | Notebook    | [73e328ad87](https://bsd-hardware.info/?probe=73e328ad87) | May 20, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [ce636a7fbe](https://bsd-hardware.info/?probe=ce636a7fbe) | May 20, 2022 |
| Deciso        | Netboard A20                | Notebook    | [f78f6b9abb](https://bsd-hardware.info/?probe=f78f6b9abb) | May 20, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [819bed6cfb](https://bsd-hardware.info/?probe=819bed6cfb) | May 19, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [195d06f6c7](https://bsd-hardware.info/?probe=195d06f6c7) | May 19, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [901a883013](https://bsd-hardware.info/?probe=901a883013) | May 19, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [9c459aae41](https://bsd-hardware.info/?probe=9c459aae41) | May 19, 2022 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [d5a6eba10b](https://bsd-hardware.info/?probe=d5a6eba10b) | May 19, 2022 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [7189b48418](https://bsd-hardware.info/?probe=7189b48418) | May 17, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [37ed1733b4](https://bsd-hardware.info/?probe=37ed1733b4) | May 16, 2022 |
| HP            | 3397                        | Desktop     | [11269254e4](https://bsd-hardware.info/?probe=11269254e4) | May 16, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [5688deb0a7](https://bsd-hardware.info/?probe=5688deb0a7) | May 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [0c224d66be](https://bsd-hardware.info/?probe=0c224d66be) | May 15, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [ed1ccabff0](https://bsd-hardware.info/?probe=ed1ccabff0) | May 15, 2022 |
| MSI           | H81M-P33                    | Desktop     | [7ac64b1e55](https://bsd-hardware.info/?probe=7ac64b1e55) | May 15, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [b8960b35d4](https://bsd-hardware.info/?probe=b8960b35d4) | May 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e07337b1a1](https://bsd-hardware.info/?probe=e07337b1a1) | May 15, 2022 |
| Dell          | Precision M4800             | Notebook    | [6dc325b553](https://bsd-hardware.info/?probe=6dc325b553) | May 15, 2022 |
| Protectli     | FW4A Ver                    | Desktop     | [2188b1004e](https://bsd-hardware.info/?probe=2188b1004e) | May 15, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [628efb3066](https://bsd-hardware.info/?probe=628efb3066) | May 15, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [9f87323412](https://bsd-hardware.info/?probe=9f87323412) | May 15, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [db440da034](https://bsd-hardware.info/?probe=db440da034) | May 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [35ae334ef4](https://bsd-hardware.info/?probe=35ae334ef4) | May 14, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [3d0599f15d](https://bsd-hardware.info/?probe=3d0599f15d) | May 14, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [eba3ba986d](https://bsd-hardware.info/?probe=eba3ba986d) | May 14, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [6fc43c37e6](https://bsd-hardware.info/?probe=6fc43c37e6) | May 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6a9177eef7](https://bsd-hardware.info/?probe=6a9177eef7) | May 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [11034dd80f](https://bsd-hardware.info/?probe=11034dd80f) | May 13, 2022 |
| Protectli     | FW2B Ver                    | Desktop     | [99ac04d77b](https://bsd-hardware.info/?probe=99ac04d77b) | May 12, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [045efeba21](https://bsd-hardware.info/?probe=045efeba21) | May 12, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [abdd886f42](https://bsd-hardware.info/?probe=abdd886f42) | May 12, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [991f67362f](https://bsd-hardware.info/?probe=991f67362f) | May 12, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [285ffa8252](https://bsd-hardware.info/?probe=285ffa8252) | May 11, 2022 |
| Dell          | 0WMJ54 A00                  | Desktop     | [e0cc5006c2](https://bsd-hardware.info/?probe=e0cc5006c2) | May 11, 2022 |
| Dell          | 07T4MC A02                  | Desktop     | [38bdad88cc](https://bsd-hardware.info/?probe=38bdad88cc) | May 11, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [62c634b13e](https://bsd-hardware.info/?probe=62c634b13e) | May 11, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [6dce802641](https://bsd-hardware.info/?probe=6dce802641) | May 10, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [97d7714d47](https://bsd-hardware.info/?probe=97d7714d47) | May 10, 2022 |
| JGINYUE       | B85I PLUS V1.0              | Desktop     | [55e9734c09](https://bsd-hardware.info/?probe=55e9734c09) | May 10, 2022 |
| Protectli     | FW6D                        | Desktop     | [a1390bbbea](https://bsd-hardware.info/?probe=a1390bbbea) | May 10, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ffb2587425](https://bsd-hardware.info/?probe=ffb2587425) | May 10, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fe1055a1c3](https://bsd-hardware.info/?probe=fe1055a1c3) | May 09, 2022 |
| Dell          | Latitude 2100               | Notebook    | [40406069ee](https://bsd-hardware.info/?probe=40406069ee) | May 09, 2022 |
| HP            | 802E                        | Desktop     | [8de7dc0ac0](https://bsd-hardware.info/?probe=8de7dc0ac0) | May 08, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [58cad4a2a5](https://bsd-hardware.info/?probe=58cad4a2a5) | May 08, 2022 |
| MSI           | H81M-P33                    | Desktop     | [bafda9a2aa](https://bsd-hardware.info/?probe=bafda9a2aa) | May 08, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [76e16e7fdc](https://bsd-hardware.info/?probe=76e16e7fdc) | May 08, 2022 |
| Lenovo        | ThinkPad X250 20CLS02V00    | Notebook    | [7e2771b8f6](https://bsd-hardware.info/?probe=7e2771b8f6) | May 08, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [fe9b1ec1cf](https://bsd-hardware.info/?probe=fe9b1ec1cf) | May 07, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [c6b6718765](https://bsd-hardware.info/?probe=c6b6718765) | May 07, 2022 |
| Dell          | 0D6H9T A03                  | Desktop     | [74b30f3577](https://bsd-hardware.info/?probe=74b30f3577) | May 07, 2022 |
| AZW           | GK55                        | Desktop     | [4d1aea90c4](https://bsd-hardware.info/?probe=4d1aea90c4) | May 07, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [850df51257](https://bsd-hardware.info/?probe=850df51257) | May 06, 2022 |
| HP            | 8054                        | Desktop     | [6c53f040f5](https://bsd-hardware.info/?probe=6c53f040f5) | May 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [659e98fd68](https://bsd-hardware.info/?probe=659e98fd68) | May 06, 2022 |
| Supermicro    | A1SAM-2550F                 | Server      | [919195c544](https://bsd-hardware.info/?probe=919195c544) | May 06, 2022 |
| HP            | 17E2                        | Mini pc     | [ac74e1cc65](https://bsd-hardware.info/?probe=ac74e1cc65) | May 06, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [76674e4d62](https://bsd-hardware.info/?probe=76674e4d62) | May 06, 2022 |
| Protectli     | FW2B Ver                    | Desktop     | [6c7485ba6b](https://bsd-hardware.info/?probe=6c7485ba6b) | May 06, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | Notebook    | [e99738632d](https://bsd-hardware.info/?probe=e99738632d) | May 06, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [13815ff079](https://bsd-hardware.info/?probe=13815ff079) | May 06, 2022 |
| Supermicro    | A1SAM-2550F                 | Server      | [e797df7273](https://bsd-hardware.info/?probe=e797df7273) | May 05, 2022 |
| Supermicro    | X7SPA-HF                    | Desktop     | [990036445e](https://bsd-hardware.info/?probe=990036445e) | May 05, 2022 |
| Protectli     | VP2410                      | Desktop     | [d80da79148](https://bsd-hardware.info/?probe=d80da79148) | May 05, 2022 |
| Protectli     | FW2B Ver                    | Desktop     | [b2eb9a10fa](https://bsd-hardware.info/?probe=b2eb9a10fa) | May 04, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [d4606bfb1a](https://bsd-hardware.info/?probe=d4606bfb1a) | May 04, 2022 |
| Protectli     | FW2B Ver                    | Desktop     | [632c881ec8](https://bsd-hardware.info/?probe=632c881ec8) | May 04, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [54ead4b762](https://bsd-hardware.info/?probe=54ead4b762) | May 03, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [86ea07c719](https://bsd-hardware.info/?probe=86ea07c719) | May 03, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [441a5f4a89](https://bsd-hardware.info/?probe=441a5f4a89) | May 03, 2022 |
| Intel         | Q3XXG4-P                    | Desktop     | [ed04988a23](https://bsd-hardware.info/?probe=ed04988a23) | May 03, 2022 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [478294cdd3](https://bsd-hardware.info/?probe=478294cdd3) | May 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [128b461a84](https://bsd-hardware.info/?probe=128b461a84) | May 02, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [6ccb91cdfe](https://bsd-hardware.info/?probe=6ccb91cdfe) | May 01, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [46c2b63c32](https://bsd-hardware.info/?probe=46c2b63c32) | May 01, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [a28d0e9c9d](https://bsd-hardware.info/?probe=a28d0e9c9d) | May 01, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7b1cd9e231](https://bsd-hardware.info/?probe=7b1cd9e231) | May 01, 2022 |
| MSI           | H81M-P33                    | Desktop     | [30d7aec5a0](https://bsd-hardware.info/?probe=30d7aec5a0) | May 01, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [7ceaeb49f9](https://bsd-hardware.info/?probe=7ceaeb49f9) | May 01, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [a8c820c8c2](https://bsd-hardware.info/?probe=a8c820c8c2) | May 01, 2022 |
| Toshiba       | Satellite P25               | Notebook    | [6a920e9c8a](https://bsd-hardware.info/?probe=6a920e9c8a) | May 01, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [e4970bf75f](https://bsd-hardware.info/?probe=e4970bf75f) | Apr 30, 2022 |
| MSI           | 2AE0                        | Desktop     | [9ff97b3d86](https://bsd-hardware.info/?probe=9ff97b3d86) | Apr 30, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [e16c0616d6](https://bsd-hardware.info/?probe=e16c0616d6) | Apr 30, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [7a212b5833](https://bsd-hardware.info/?probe=7a212b5833) | Apr 29, 2022 |
| Dell          | 02C2CP A04                  | Server      | [6ea07b9e6c](https://bsd-hardware.info/?probe=6ea07b9e6c) | Apr 29, 2022 |
| HP            | 1588h                       | Desktop     | [51ce2c6d49](https://bsd-hardware.info/?probe=51ce2c6d49) | Apr 28, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [2bd964cc84](https://bsd-hardware.info/?probe=2bd964cc84) | Apr 28, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [337d593ce0](https://bsd-hardware.info/?probe=337d593ce0) | Apr 28, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [a4fa09b7c1](https://bsd-hardware.info/?probe=a4fa09b7c1) | Apr 28, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [c1df1360a2](https://bsd-hardware.info/?probe=c1df1360a2) | Apr 28, 2022 |
| MSI           | MS-7C37                     | Desktop     | [aaab7cf22a](https://bsd-hardware.info/?probe=aaab7cf22a) | Apr 28, 2022 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [0d32ec9fe4](https://bsd-hardware.info/?probe=0d32ec9fe4) | Apr 27, 2022 |
| Supermicro    | X8SIL                       | Desktop     | [ea89820a66](https://bsd-hardware.info/?probe=ea89820a66) | Apr 27, 2022 |
| Supermicro    | A1SRi-2558F                 | Mini pc     | [91f8607bd5](https://bsd-hardware.info/?probe=91f8607bd5) | Apr 27, 2022 |
| HP            | 17E2                        | Mini pc     | [4cd954cab1](https://bsd-hardware.info/?probe=4cd954cab1) | Apr 27, 2022 |
| HP            | 8103 A01                    | Mini pc     | [d3234681fe](https://bsd-hardware.info/?probe=d3234681fe) | Apr 26, 2022 |
| Protectli     | VP2410                      | Desktop     | [481fce8e01](https://bsd-hardware.info/?probe=481fce8e01) | Apr 26, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [8d2ca89ae5](https://bsd-hardware.info/?probe=8d2ca89ae5) | Apr 26, 2022 |
| Framework     | Laptop                      | Notebook    | [5d6cb039ea](https://bsd-hardware.info/?probe=5d6cb039ea) | Apr 25, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [b6b5897fb7](https://bsd-hardware.info/?probe=b6b5897fb7) | Apr 25, 2022 |
| Supermicro    | X10SLQ                      | Server      | [94e031b1e8](https://bsd-hardware.info/?probe=94e031b1e8) | Apr 24, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d14d6194ed](https://bsd-hardware.info/?probe=d14d6194ed) | Apr 24, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [27a4680bec](https://bsd-hardware.info/?probe=27a4680bec) | Apr 24, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [76580a0375](https://bsd-hardware.info/?probe=76580a0375) | Apr 24, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [10ca96dd0a](https://bsd-hardware.info/?probe=10ca96dd0a) | Apr 24, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [e588c93d54](https://bsd-hardware.info/?probe=e588c93d54) | Apr 24, 2022 |
| PC Engines    | apu4                        | Desktop     | [2de45511cd](https://bsd-hardware.info/?probe=2de45511cd) | Apr 24, 2022 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | Desktop     | [66f185a3e5](https://bsd-hardware.info/?probe=66f185a3e5) | Apr 23, 2022 |
| HP            | 2000                        | Notebook    | [e9599a9bc3](https://bsd-hardware.info/?probe=e9599a9bc3) | Apr 22, 2022 |
| Supermicro    | X9SCL/X9SCM                 | Desktop     | [947038b1f9](https://bsd-hardware.info/?probe=947038b1f9) | Apr 22, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [362ff46a0a](https://bsd-hardware.info/?probe=362ff46a0a) | Apr 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [b4a6761ab3](https://bsd-hardware.info/?probe=b4a6761ab3) | Apr 21, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [1365bb4de7](https://bsd-hardware.info/?probe=1365bb4de7) | Apr 21, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2fd6d176ce](https://bsd-hardware.info/?probe=2fd6d176ce) | Apr 21, 2022 |
| Supermicro    | X11SAT                      | Server      | [a888ae8488](https://bsd-hardware.info/?probe=a888ae8488) | Apr 21, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [bae3bbc2be](https://bsd-hardware.info/?probe=bae3bbc2be) | Apr 21, 2022 |
| Dell          | 03XKDV A02                  | Server      | [83ed89069c](https://bsd-hardware.info/?probe=83ed89069c) | Apr 20, 2022 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [9853d461a3](https://bsd-hardware.info/?probe=9853d461a3) | Apr 20, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [da5f95b60d](https://bsd-hardware.info/?probe=da5f95b60d) | Apr 20, 2022 |
| Dell          | 0FKD45 A03                  | Server      | [dde6af4613](https://bsd-hardware.info/?probe=dde6af4613) | Apr 19, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [c0c3696eab](https://bsd-hardware.info/?probe=c0c3696eab) | Apr 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6fc3367b15](https://bsd-hardware.info/?probe=6fc3367b15) | Apr 19, 2022 |
| Unknown       | YL-SKUL6                    | Desktop     | [8e2a35a0c8](https://bsd-hardware.info/?probe=8e2a35a0c8) | Apr 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b16f95dfea](https://bsd-hardware.info/?probe=b16f95dfea) | Apr 18, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bd82ff2e7e](https://bsd-hardware.info/?probe=bd82ff2e7e) | Apr 18, 2022 |
| Dell          | 0PC5F7 A02                  | Desktop     | [58b39b90ba](https://bsd-hardware.info/?probe=58b39b90ba) | Apr 17, 2022 |
| MSI           | H81M-P33                    | Desktop     | [4bc268cc37](https://bsd-hardware.info/?probe=4bc268cc37) | Apr 17, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [1c967bd89f](https://bsd-hardware.info/?probe=1c967bd89f) | Apr 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c8badc9bc6](https://bsd-hardware.info/?probe=c8badc9bc6) | Apr 17, 2022 |
| Protectli     | FW6                         | Desktop     | [6f77a10d74](https://bsd-hardware.info/?probe=6f77a10d74) | Apr 16, 2022 |
| Lenovo        | G51-35 80M8                 | Notebook    | [285328cb61](https://bsd-hardware.info/?probe=285328cb61) | Apr 16, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [a9702df869](https://bsd-hardware.info/?probe=a9702df869) | Apr 16, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [399a4fb92e](https://bsd-hardware.info/?probe=399a4fb92e) | Apr 15, 2022 |
| Protectli     | FW1 Ver                     | Desktop     | [09f1805532](https://bsd-hardware.info/?probe=09f1805532) | Apr 15, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [8188392376](https://bsd-hardware.info/?probe=8188392376) | Apr 14, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [7810c76897](https://bsd-hardware.info/?probe=7810c76897) | Apr 14, 2022 |
| Acer          | Veriton X275                | Desktop     | [06390b6cb1](https://bsd-hardware.info/?probe=06390b6cb1) | Apr 13, 2022 |
| Dell          | 04JGCK A01                  | Desktop     | [c3d7d0828b](https://bsd-hardware.info/?probe=c3d7d0828b) | Apr 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f6bc20d345](https://bsd-hardware.info/?probe=f6bc20d345) | Apr 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [bb9129d4df](https://bsd-hardware.info/?probe=bb9129d4df) | Apr 13, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [fd04d22de9](https://bsd-hardware.info/?probe=fd04d22de9) | Apr 13, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [872a05c140](https://bsd-hardware.info/?probe=872a05c140) | Apr 13, 2022 |
| Alienware     | 0KM92T A00                  | Desktop     | [e96f2905eb](https://bsd-hardware.info/?probe=e96f2905eb) | Apr 13, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [c776760a11](https://bsd-hardware.info/?probe=c776760a11) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [4cbd9f9314](https://bsd-hardware.info/?probe=4cbd9f9314) | Apr 12, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [b875a50291](https://bsd-hardware.info/?probe=b875a50291) | Apr 12, 2022 |
| Dell          | 0Y56T3 A00                  | Desktop     | [d9d86d5bfd](https://bsd-hardware.info/?probe=d9d86d5bfd) | Apr 12, 2022 |
| Deciso        | Netboard A20                | Notebook    | [aa1f373bfb](https://bsd-hardware.info/?probe=aa1f373bfb) | Apr 12, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [880174cb9b](https://bsd-hardware.info/?probe=880174cb9b) | Apr 12, 2022 |
| Intel         | DH67CL AAG10212-205         | Desktop     | [ecbb820987](https://bsd-hardware.info/?probe=ecbb820987) | Apr 12, 2022 |
| Supermicro    | X10SRi-FB                   | Server      | [970fa01d42](https://bsd-hardware.info/?probe=970fa01d42) | Apr 11, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [e0f42a2bb2](https://bsd-hardware.info/?probe=e0f42a2bb2) | Apr 11, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [0e836941e0](https://bsd-hardware.info/?probe=0e836941e0) | Apr 11, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [4a23ea31be](https://bsd-hardware.info/?probe=4a23ea31be) | Apr 11, 2022 |
| Datto         | SSD                         | Desktop     | [f69d873f87](https://bsd-hardware.info/?probe=f69d873f87) | Apr 11, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [39ad080dfb](https://bsd-hardware.info/?probe=39ad080dfb) | Apr 11, 2022 |
| Deciso        | Netboard A20                | Notebook    | [d12cd9d1a1](https://bsd-hardware.info/?probe=d12cd9d1a1) | Apr 11, 2022 |
| Datto         | 1000                        | Notebook    | [745e356caa](https://bsd-hardware.info/?probe=745e356caa) | Apr 11, 2022 |
| Dell          | 04YP6J A02                  | Desktop     | [f638ef3cbe](https://bsd-hardware.info/?probe=f638ef3cbe) | Apr 11, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [82fc6dbaab](https://bsd-hardware.info/?probe=82fc6dbaab) | Apr 10, 2022 |
| Datto         | SSD                         | Desktop     | [6cd7c93838](https://bsd-hardware.info/?probe=6cd7c93838) | Apr 10, 2022 |
| Dell          | 0PC5F7 A02                  | Desktop     | [6c09c89949](https://bsd-hardware.info/?probe=6c09c89949) | Apr 10, 2022 |
| MSI           | H81M-P33                    | Desktop     | [52abbcbc5b](https://bsd-hardware.info/?probe=52abbcbc5b) | Apr 10, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [0cbb5faa2e](https://bsd-hardware.info/?probe=0cbb5faa2e) | Apr 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5d759d6436](https://bsd-hardware.info/?probe=5d759d6436) | Apr 10, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [7b790f0366](https://bsd-hardware.info/?probe=7b790f0366) | Apr 10, 2022 |
| Intel         | DH67CL AAG10212-205         | Desktop     | [de2cd29be6](https://bsd-hardware.info/?probe=de2cd29be6) | Apr 10, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | Notebook    | [3b7da460a2](https://bsd-hardware.info/?probe=3b7da460a2) | Apr 10, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [2a03c05cce](https://bsd-hardware.info/?probe=2a03c05cce) | Apr 10, 2022 |
| Protectli     | FW6E                        | Desktop     | [0a529f5f09](https://bsd-hardware.info/?probe=0a529f5f09) | Apr 10, 2022 |
| PC Engines    | APU2                        | Desktop     | [074d4aa53c](https://bsd-hardware.info/?probe=074d4aa53c) | Apr 10, 2022 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [fa4b6b0257](https://bsd-hardware.info/?probe=fa4b6b0257) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-205         | Desktop     | [4436915ba0](https://bsd-hardware.info/?probe=4436915ba0) | Apr 09, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [844323ad2d](https://bsd-hardware.info/?probe=844323ad2d) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-210         | Desktop     | [a01376dfc5](https://bsd-hardware.info/?probe=a01376dfc5) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-205         | Desktop     | [85a5d08117](https://bsd-hardware.info/?probe=85a5d08117) | Apr 09, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [ef224ffce0](https://bsd-hardware.info/?probe=ef224ffce0) | Apr 09, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [689ff6c484](https://bsd-hardware.info/?probe=689ff6c484) | Apr 09, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [e128e81c96](https://bsd-hardware.info/?probe=e128e81c96) | Apr 09, 2022 |
| Lenovo        | ThinkPad T495 20NJ0000US    | Notebook    | [c626b32508](https://bsd-hardware.info/?probe=c626b32508) | Apr 09, 2022 |
| Dell          | 08VT7V A05                  | Server      | [0026813838](https://bsd-hardware.info/?probe=0026813838) | Apr 09, 2022 |
| ASRock        | X570 Steel Legend WiFi a... | Desktop     | [703e042cfe](https://bsd-hardware.info/?probe=703e042cfe) | Apr 09, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [e58bc4937d](https://bsd-hardware.info/?probe=e58bc4937d) | Apr 09, 2022 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [b9a45002ae](https://bsd-hardware.info/?probe=b9a45002ae) | Apr 09, 2022 |
| Intel         | DH67CL AAG10212-205         | Desktop     | [68f10ed8de](https://bsd-hardware.info/?probe=68f10ed8de) | Apr 09, 2022 |
| Intel         | DH67CL AAG10212-205         | Desktop     | [092643d1c3](https://bsd-hardware.info/?probe=092643d1c3) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-205         | Desktop     | [02b581994b](https://bsd-hardware.info/?probe=02b581994b) | Apr 08, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [840805d1fa](https://bsd-hardware.info/?probe=840805d1fa) | Apr 08, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [32db8548c0](https://bsd-hardware.info/?probe=32db8548c0) | Apr 08, 2022 |
| Dell          | Vostro 1400                 | Notebook    | [7e0964d31d](https://bsd-hardware.info/?probe=7e0964d31d) | Apr 08, 2022 |
| Protectli     | FW2 Ver                     | Desktop     | [9f73c4b7e5](https://bsd-hardware.info/?probe=9f73c4b7e5) | Apr 08, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [e97a752648](https://bsd-hardware.info/?probe=e97a752648) | Apr 08, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [50d12f98fc](https://bsd-hardware.info/?probe=50d12f98fc) | Apr 08, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [ad0ab01ca8](https://bsd-hardware.info/?probe=ad0ab01ca8) | Apr 08, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [b3acaf2f6d](https://bsd-hardware.info/?probe=b3acaf2f6d) | Apr 07, 2022 |
| Deciso        | Netboard A20                | Notebook    | [c6217643cc](https://bsd-hardware.info/?probe=c6217643cc) | Apr 07, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [d24fcb00e2](https://bsd-hardware.info/?probe=d24fcb00e2) | Apr 07, 2022 |
| Gigabyte      | MMLP7AP-00                  | Notebook    | [8116ea4eac](https://bsd-hardware.info/?probe=8116ea4eac) | Apr 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [7d4820d983](https://bsd-hardware.info/?probe=7d4820d983) | Apr 07, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [a083074e9a](https://bsd-hardware.info/?probe=a083074e9a) | Apr 07, 2022 |
| Acer          | Veriton X275                | Desktop     | [412c31c1a9](https://bsd-hardware.info/?probe=412c31c1a9) | Apr 07, 2022 |
| Protectli     | FW1 Ver                     | Desktop     | [183df9ebd2](https://bsd-hardware.info/?probe=183df9ebd2) | Apr 07, 2022 |
| MSI           | A78M-E45                    | Desktop     | [6db716258a](https://bsd-hardware.info/?probe=6db716258a) | Apr 07, 2022 |
| Supermicro    | X10SLL-F                    | Desktop     | [6e07653d46](https://bsd-hardware.info/?probe=6e07653d46) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2d04e83ea4](https://bsd-hardware.info/?probe=2d04e83ea4) | Apr 06, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [5556bf474c](https://bsd-hardware.info/?probe=5556bf474c) | Apr 06, 2022 |
| Dell          | 081N4V A12                  | Server      | [20f8611419](https://bsd-hardware.info/?probe=20f8611419) | Apr 06, 2022 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [5ed8eb5a88](https://bsd-hardware.info/?probe=5ed8eb5a88) | Apr 06, 2022 |
| HP            | 8103 A01                    | Mini pc     | [60580ff26b](https://bsd-hardware.info/?probe=60580ff26b) | Apr 06, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [cd798576f8](https://bsd-hardware.info/?probe=cd798576f8) | Apr 06, 2022 |
| Protectli     | FW1 Ver                     | Desktop     | [a3af5d0e88](https://bsd-hardware.info/?probe=a3af5d0e88) | Apr 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [7644cc6811](https://bsd-hardware.info/?probe=7644cc6811) | Apr 06, 2022 |
| Dell          | 0PC5F7 A02                  | Desktop     | [e77c0c0cf7](https://bsd-hardware.info/?probe=e77c0c0cf7) | Apr 06, 2022 |
| Supermicro    | X9SAE                       | Desktop     | [a800ac2857](https://bsd-hardware.info/?probe=a800ac2857) | Apr 06, 2022 |
| HP            | 1998                        | Desktop     | [bf9a8c9cb2](https://bsd-hardware.info/?probe=bf9a8c9cb2) | Apr 06, 2022 |
| MSI           | 990FXA-GD80                 | Desktop     | [1581e2f112](https://bsd-hardware.info/?probe=1581e2f112) | Apr 06, 2022 |
| MSI           | 990FXA-GD80                 | Desktop     | [9c0d3e7793](https://bsd-hardware.info/?probe=9c0d3e7793) | Apr 06, 2022 |
| Supermicro    | X10SLL-F                    | Desktop     | [7b901b1d99](https://bsd-hardware.info/?probe=7b901b1d99) | Apr 05, 2022 |
| Protectli     | FW6                         | Desktop     | [9ab59de1ca](https://bsd-hardware.info/?probe=9ab59de1ca) | Apr 05, 2022 |
| HP            | 213D A01                    | Desktop     | [0c24a77be7](https://bsd-hardware.info/?probe=0c24a77be7) | Apr 05, 2022 |
| Protectli     | FW4B                        | Desktop     | [f51cc63f72](https://bsd-hardware.info/?probe=f51cc63f72) | Apr 05, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [d7efc57aa2](https://bsd-hardware.info/?probe=d7efc57aa2) | Apr 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [06bad6f773](https://bsd-hardware.info/?probe=06bad6f773) | Apr 04, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [746d840530](https://bsd-hardware.info/?probe=746d840530) | Apr 03, 2022 |
| HP            | 1495                        | Desktop     | [5e4e29bf54](https://bsd-hardware.info/?probe=5e4e29bf54) | Apr 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1043649da9](https://bsd-hardware.info/?probe=1043649da9) | Apr 03, 2022 |
| MSI           | H81M-P33                    | Desktop     | [b0d11aabb7](https://bsd-hardware.info/?probe=b0d11aabb7) | Apr 03, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [dbaaa0dcda](https://bsd-hardware.info/?probe=dbaaa0dcda) | Apr 03, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [ea77aa3506](https://bsd-hardware.info/?probe=ea77aa3506) | Apr 03, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [82e48f7eb4](https://bsd-hardware.info/?probe=82e48f7eb4) | Apr 03, 2022 |
| Dell          | 0PC5F7 A02                  | Desktop     | [93d77b3755](https://bsd-hardware.info/?probe=93d77b3755) | Apr 03, 2022 |
| eMachines     | EL1360G                     | Desktop     | [0443d39e17](https://bsd-hardware.info/?probe=0443d39e17) | Apr 02, 2022 |
| PC Engines    | apu4                        | Desktop     | [00e4f2931b](https://bsd-hardware.info/?probe=00e4f2931b) | Apr 02, 2022 |
| Supermicro    | X11SCL-LN4F                 | Server      | [bc53356d96](https://bsd-hardware.info/?probe=bc53356d96) | Apr 02, 2022 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [1868573e9a](https://bsd-hardware.info/?probe=1868573e9a) | Apr 02, 2022 |
| Supermicro    | X8DTU-LN4+                  | Server      | [99a1843021](https://bsd-hardware.info/?probe=99a1843021) | Apr 01, 2022 |
| Dell          | 04YP6J A02                  | Desktop     | [8be7c68dfb](https://bsd-hardware.info/?probe=8be7c68dfb) | Apr 01, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [7daab72741](https://bsd-hardware.info/?probe=7daab72741) | Apr 01, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [01dcca775c](https://bsd-hardware.info/?probe=01dcca775c) | Apr 01, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [94d3e8af32](https://bsd-hardware.info/?probe=94d3e8af32) | Apr 01, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [5bdcde54b1](https://bsd-hardware.info/?probe=5bdcde54b1) | Apr 01, 2022 |
| Datto         | 1000                        | Notebook    | [5974640141](https://bsd-hardware.info/?probe=5974640141) | Mar 31, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [b64ddb6733](https://bsd-hardware.info/?probe=b64ddb6733) | Mar 31, 2022 |
| HP            | 158A                        | Desktop     | [5d463584db](https://bsd-hardware.info/?probe=5d463584db) | Mar 31, 2022 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [bd9d4bb7a3](https://bsd-hardware.info/?probe=bd9d4bb7a3) | Mar 31, 2022 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [c84f270fba](https://bsd-hardware.info/?probe=c84f270fba) | Mar 31, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [bffcfb13e3](https://bsd-hardware.info/?probe=bffcfb13e3) | Mar 31, 2022 |
| Supermicro    | X9SAEA                      | Desktop     | [bdb1c8e931](https://bsd-hardware.info/?probe=bdb1c8e931) | Mar 31, 2022 |
| HP            | 17E2                        | Mini pc     | [f94c61b51a](https://bsd-hardware.info/?probe=f94c61b51a) | Mar 30, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [653bba75e9](https://bsd-hardware.info/?probe=653bba75e9) | Mar 30, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [cb50918ca3](https://bsd-hardware.info/?probe=cb50918ca3) | Mar 30, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [6a276beb82](https://bsd-hardware.info/?probe=6a276beb82) | Mar 30, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [97f0250f90](https://bsd-hardware.info/?probe=97f0250f90) | Mar 30, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [ecb92e497e](https://bsd-hardware.info/?probe=ecb92e497e) | Mar 30, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [91df634364](https://bsd-hardware.info/?probe=91df634364) | Mar 29, 2022 |
| Supermicro    | X8DTU-LN4+                  | Server      | [efd40250a4](https://bsd-hardware.info/?probe=efd40250a4) | Mar 29, 2022 |
| Gigabyte      | H110N-CF                    | Desktop     | [89593af061](https://bsd-hardware.info/?probe=89593af061) | Mar 29, 2022 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [c24c0076af](https://bsd-hardware.info/?probe=c24c0076af) | Mar 29, 2022 |
| Protectli     | FW4B                        | Desktop     | [e140c22680](https://bsd-hardware.info/?probe=e140c22680) | Mar 29, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [a51ca89399](https://bsd-hardware.info/?probe=a51ca89399) | Mar 28, 2022 |
| Supermicro    | X10SRi-FB                   | Server      | [0467221645](https://bsd-hardware.info/?probe=0467221645) | Mar 28, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [8f507fcb9a](https://bsd-hardware.info/?probe=8f507fcb9a) | Mar 27, 2022 |
| Dell          | 0NC2VH A02                  | Desktop     | [2593acccf3](https://bsd-hardware.info/?probe=2593acccf3) | Mar 27, 2022 |
| MSI           | H61M-P25                    | Desktop     | [123cb1174a](https://bsd-hardware.info/?probe=123cb1174a) | Mar 27, 2022 |
| PC Engines    | APU                         | Desktop     | [941b9801bc](https://bsd-hardware.info/?probe=941b9801bc) | Mar 27, 2022 |
| MSI           | H81M-P33                    | Desktop     | [823d2d7336](https://bsd-hardware.info/?probe=823d2d7336) | Mar 27, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [4e44bfd765](https://bsd-hardware.info/?probe=4e44bfd765) | Mar 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [51507583f6](https://bsd-hardware.info/?probe=51507583f6) | Mar 27, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [38c2741e61](https://bsd-hardware.info/?probe=38c2741e61) | Mar 27, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [4c03d19a48](https://bsd-hardware.info/?probe=4c03d19a48) | Mar 27, 2022 |
| Dell          | 03KWTV A02                  | Desktop     | [7a341728eb](https://bsd-hardware.info/?probe=7a341728eb) | Mar 27, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [d7e343be80](https://bsd-hardware.info/?probe=d7e343be80) | Mar 27, 2022 |
| Protectli     | FW4A Ver                    | Desktop     | [32d9eff6fb](https://bsd-hardware.info/?probe=32d9eff6fb) | Mar 27, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [28f9e0596c](https://bsd-hardware.info/?probe=28f9e0596c) | Mar 27, 2022 |
| Deciso        | Netboard A20                | Notebook    | [51a8ceefee](https://bsd-hardware.info/?probe=51a8ceefee) | Mar 26, 2022 |
| Deciso        | Netboard A20                | Notebook    | [43a1f11ae0](https://bsd-hardware.info/?probe=43a1f11ae0) | Mar 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [bd9b55ea13](https://bsd-hardware.info/?probe=bd9b55ea13) | Mar 26, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK MM ... | Desktop     | [3c86d96e65](https://bsd-hardware.info/?probe=3c86d96e65) | Mar 26, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [95646c7b48](https://bsd-hardware.info/?probe=95646c7b48) | Mar 25, 2022 |
| Biostar       | NM70I-1037U                 | Desktop     | [d2c51a35cf](https://bsd-hardware.info/?probe=d2c51a35cf) | Mar 25, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [94f78425f1](https://bsd-hardware.info/?probe=94f78425f1) | Mar 25, 2022 |
| Protectli     | FW4B                        | Desktop     | [9a1d787beb](https://bsd-hardware.info/?probe=9a1d787beb) | Mar 25, 2022 |
| MSI           | G41M-P33 Combo              | Desktop     | [03d5b67d7b](https://bsd-hardware.info/?probe=03d5b67d7b) | Mar 25, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [723f46ef7a](https://bsd-hardware.info/?probe=723f46ef7a) | Mar 25, 2022 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [07af378490](https://bsd-hardware.info/?probe=07af378490) | Mar 25, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [d9e74758f3](https://bsd-hardware.info/?probe=d9e74758f3) | Mar 24, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [574b11983b](https://bsd-hardware.info/?probe=574b11983b) | Mar 24, 2022 |
| Dell          | 0W0CHX A00                  | Desktop     | [9e9d0f7cb6](https://bsd-hardware.info/?probe=9e9d0f7cb6) | Mar 24, 2022 |
| Supermicro    | M11SDV-4CT-LN4FA            | Server      | [2c44e568ea](https://bsd-hardware.info/?probe=2c44e568ea) | Mar 24, 2022 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [15acb1b742](https://bsd-hardware.info/?probe=15acb1b742) | Mar 24, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [09116f9139](https://bsd-hardware.info/?probe=09116f9139) | Mar 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [1af600b3ae](https://bsd-hardware.info/?probe=1af600b3ae) | Mar 24, 2022 |
| Lenovo        | ThinkPad X230 2325BV9       | Notebook    | [d2a16f6102](https://bsd-hardware.info/?probe=d2a16f6102) | Mar 23, 2022 |
| Dell          | 0WMJ54 A00                  | Desktop     | [c9114be51e](https://bsd-hardware.info/?probe=c9114be51e) | Mar 23, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [693d365311](https://bsd-hardware.info/?probe=693d365311) | Mar 23, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [7c46c8e712](https://bsd-hardware.info/?probe=7c46c8e712) | Mar 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [b7caab74c8](https://bsd-hardware.info/?probe=b7caab74c8) | Mar 22, 2022 |
| HP            | 1495                        | Desktop     | [af6b21fdff](https://bsd-hardware.info/?probe=af6b21fdff) | Mar 22, 2022 |
| Gateway       | NV55C                       | Notebook    | [a63381d681](https://bsd-hardware.info/?probe=a63381d681) | Mar 22, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [a752b8b4d6](https://bsd-hardware.info/?probe=a752b8b4d6) | Mar 22, 2022 |
| Supermicro    | X7SPA-H                     | Desktop     | [c0415b128f](https://bsd-hardware.info/?probe=c0415b128f) | Mar 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [c4ffde79eb](https://bsd-hardware.info/?probe=c4ffde79eb) | Mar 21, 2022 |
| HP            | 1495                        | Desktop     | [ddcc87225d](https://bsd-hardware.info/?probe=ddcc87225d) | Mar 21, 2022 |
| MSI           | A78M-E45                    | Desktop     | [191e17803a](https://bsd-hardware.info/?probe=191e17803a) | Mar 21, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [cddd1bf6a8](https://bsd-hardware.info/?probe=cddd1bf6a8) | Mar 20, 2022 |
| MSI           | X79A-GD45 Plus              | Desktop     | [47e069c6d9](https://bsd-hardware.info/?probe=47e069c6d9) | Mar 20, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [1ae8321767](https://bsd-hardware.info/?probe=1ae8321767) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [91d8f0be69](https://bsd-hardware.info/?probe=91d8f0be69) | Mar 20, 2022 |
| Sophos        | SG                          | Firewall    | [866eb3c9cb](https://bsd-hardware.info/?probe=866eb3c9cb) | Mar 20, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [2aeeaaacfc](https://bsd-hardware.info/?probe=2aeeaaacfc) | Mar 20, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [4b6df22ff5](https://bsd-hardware.info/?probe=4b6df22ff5) | Mar 20, 2022 |
| ASRock        | AM1B-MDH                    | Desktop     | [2cd18e1270](https://bsd-hardware.info/?probe=2cd18e1270) | Mar 20, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d9421c2715](https://bsd-hardware.info/?probe=d9421c2715) | Mar 20, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [5a6cb7ab07](https://bsd-hardware.info/?probe=5a6cb7ab07) | Mar 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [12814be80b](https://bsd-hardware.info/?probe=12814be80b) | Mar 20, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [848b4d2d85](https://bsd-hardware.info/?probe=848b4d2d85) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [b137fe659e](https://bsd-hardware.info/?probe=b137fe659e) | Mar 20, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [89a5b0a1e2](https://bsd-hardware.info/?probe=89a5b0a1e2) | Mar 20, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [ee37b7abf2](https://bsd-hardware.info/?probe=ee37b7abf2) | Mar 19, 2022 |
| GEEK+         | Mini PC                     | Mini pc     | [74c2f601fd](https://bsd-hardware.info/?probe=74c2f601fd) | Mar 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [4aabccc99e](https://bsd-hardware.info/?probe=4aabccc99e) | Mar 19, 2022 |
| Protectli     | FW4B                        | Desktop     | [0fc7d5fb74](https://bsd-hardware.info/?probe=0fc7d5fb74) | Mar 19, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [2ea4f88d47](https://bsd-hardware.info/?probe=2ea4f88d47) | Mar 18, 2022 |
| Supermicro    | M11SDV-4CT-LN4FA            | Server      | [16e7b1456b](https://bsd-hardware.info/?probe=16e7b1456b) | Mar 18, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [fb3fd7ea82](https://bsd-hardware.info/?probe=fb3fd7ea82) | Mar 17, 2022 |
| MSI           | X79A-GD45 Plus              | Desktop     | [8aee77286e](https://bsd-hardware.info/?probe=8aee77286e) | Mar 17, 2022 |
| HP            | Pavilion dv6                | Notebook    | [dee0853f4b](https://bsd-hardware.info/?probe=dee0853f4b) | Mar 17, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [ebdfd000c6](https://bsd-hardware.info/?probe=ebdfd000c6) | Mar 17, 2022 |
| Unknown       | YL-E3854L4-V2               | Desktop     | [c3d9e88b9d](https://bsd-hardware.info/?probe=c3d9e88b9d) | Mar 16, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5cf613062c](https://bsd-hardware.info/?probe=5cf613062c) | Mar 16, 2022 |
| PC Engines    | APU2                        | Desktop     | [ff8dfbf357](https://bsd-hardware.info/?probe=ff8dfbf357) | Mar 16, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [e9dcb4c3da](https://bsd-hardware.info/?probe=e9dcb4c3da) | Mar 16, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [660c9f4c3d](https://bsd-hardware.info/?probe=660c9f4c3d) | Mar 15, 2022 |
| Protectli     | VP2410                      | Desktop     | [be162c6555](https://bsd-hardware.info/?probe=be162c6555) | Mar 15, 2022 |
| Lenovo        | ThinkPad T420 4236MBU       | Notebook    | [8bd2318fb6](https://bsd-hardware.info/?probe=8bd2318fb6) | Mar 15, 2022 |
| Dell          | OptiPlex 980                | Desktop     | [49579d1cb3](https://bsd-hardware.info/?probe=49579d1cb3) | Mar 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [0bd1ef2b48](https://bsd-hardware.info/?probe=0bd1ef2b48) | Mar 15, 2022 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [891baf81f6](https://bsd-hardware.info/?probe=891baf81f6) | Mar 14, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [c5d261e811](https://bsd-hardware.info/?probe=c5d261e811) | Mar 14, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [ed0add65a3](https://bsd-hardware.info/?probe=ed0add65a3) | Mar 14, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [5426ab5339](https://bsd-hardware.info/?probe=5426ab5339) | Mar 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [3c28521de5](https://bsd-hardware.info/?probe=3c28521de5) | Mar 13, 2022 |
| Supermicro    | X9SCAA/-L                   | Desktop     | [fe27eac86a](https://bsd-hardware.info/?probe=fe27eac86a) | Mar 13, 2022 |
| Lenovo        | ThinkPad X201 32492EU       | Notebook    | [4a5ba4f3e4](https://bsd-hardware.info/?probe=4a5ba4f3e4) | Mar 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d01a922777](https://bsd-hardware.info/?probe=d01a922777) | Mar 13, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0e6ba0e5bc](https://bsd-hardware.info/?probe=0e6ba0e5bc) | Mar 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [3b2e18a52e](https://bsd-hardware.info/?probe=3b2e18a52e) | Mar 13, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [2ac306b67f](https://bsd-hardware.info/?probe=2ac306b67f) | Mar 13, 2022 |
| ASUSTek       | Q87T                        | Desktop     | [e407674aba](https://bsd-hardware.info/?probe=e407674aba) | Mar 13, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [0baa77a129](https://bsd-hardware.info/?probe=0baa77a129) | Mar 13, 2022 |
| MSI           | H81TI                       | Desktop     | [71d1d55fdc](https://bsd-hardware.info/?probe=71d1d55fdc) | Mar 12, 2022 |
| Inventec      | DQ Class A02                | Desktop     | [f617253042](https://bsd-hardware.info/?probe=f617253042) | Mar 12, 2022 |
| Dell          | 0YF8P5 A00                  | Desktop     | [b55a699934](https://bsd-hardware.info/?probe=b55a699934) | Mar 11, 2022 |
| Cisco         | ASA5525 A0                  | Desktop     | [53a51ec160](https://bsd-hardware.info/?probe=53a51ec160) | Mar 11, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [e04a1b354c](https://bsd-hardware.info/?probe=e04a1b354c) | Mar 11, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b2653f69b2](https://bsd-hardware.info/?probe=b2653f69b2) | Mar 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [d4c36f39a9](https://bsd-hardware.info/?probe=d4c36f39a9) | Mar 11, 2022 |
| ASRock        | X570 PG Velocita            | Desktop     | [d3596dff89](https://bsd-hardware.info/?probe=d3596dff89) | Mar 11, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [4a7894f2d8](https://bsd-hardware.info/?probe=4a7894f2d8) | Mar 11, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [ac59621182](https://bsd-hardware.info/?probe=ac59621182) | Mar 10, 2022 |
| MSI           | X79A-GD45 Plus              | Desktop     | [4f526205fb](https://bsd-hardware.info/?probe=4f526205fb) | Mar 10, 2022 |
| MSI           | X79A-GD45 Plus              | Desktop     | [dc59c075e8](https://bsd-hardware.info/?probe=dc59c075e8) | Mar 10, 2022 |
| Supermicro    | X9SCAA/-L                   | Desktop     | [f7d3072736](https://bsd-hardware.info/?probe=f7d3072736) | Mar 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [78b36d5068](https://bsd-hardware.info/?probe=78b36d5068) | Mar 10, 2022 |
| Lenovo        | IdeaPad N585                | Notebook    | [e22da97709](https://bsd-hardware.info/?probe=e22da97709) | Mar 10, 2022 |
| Supermicro    | X9DRD-iF                    | Server      | [2475a7b110](https://bsd-hardware.info/?probe=2475a7b110) | Mar 09, 2022 |
| MSI           | H81TI                       | Desktop     | [181123c364](https://bsd-hardware.info/?probe=181123c364) | Mar 09, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [0b2fc3b509](https://bsd-hardware.info/?probe=0b2fc3b509) | Mar 09, 2022 |
| Protectli     | FW4A Ver                    | Desktop     | [9d724e72c3](https://bsd-hardware.info/?probe=9d724e72c3) | Mar 09, 2022 |
| Intel         | DENLOW_REFRESH_WS           | Desktop     | [a64041317e](https://bsd-hardware.info/?probe=a64041317e) | Mar 09, 2022 |
| Intel         | DENLOW_REFRESH_WS           | Desktop     | [c95222f0be](https://bsd-hardware.info/?probe=c95222f0be) | Mar 09, 2022 |
| HP            | 8103 A01                    | Mini pc     | [364241899f](https://bsd-hardware.info/?probe=364241899f) | Mar 09, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [4774a3bc2f](https://bsd-hardware.info/?probe=4774a3bc2f) | Mar 09, 2022 |
| Dell          | 01G5C3 A02                  | Server      | [da98b2ad6b](https://bsd-hardware.info/?probe=da98b2ad6b) | Mar 08, 2022 |
| Gigabyte      | C246-WU4-CF                 | Desktop     | [17b3590a3f](https://bsd-hardware.info/?probe=17b3590a3f) | Mar 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [359e795db4](https://bsd-hardware.info/?probe=359e795db4) | Mar 08, 2022 |
| Biostar       | A68N-5545                   | Desktop     | [33b05fc05a](https://bsd-hardware.info/?probe=33b05fc05a) | Mar 08, 2022 |
| Protectli     | FW2B                        | Desktop     | [f8f7cd07ed](https://bsd-hardware.info/?probe=f8f7cd07ed) | Mar 07, 2022 |
| Lenovo        | ThinkServer RS140           | Desktop     | [51ebc2c3fd](https://bsd-hardware.info/?probe=51ebc2c3fd) | Mar 07, 2022 |
| Cisco Syst... | UCSC-C3K-M4SRB 73-17622-... | Server      | [f168e21dd6](https://bsd-hardware.info/?probe=f168e21dd6) | Mar 07, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [dbd5c6e5e3](https://bsd-hardware.info/?probe=dbd5c6e5e3) | Mar 07, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [79d8e655a3](https://bsd-hardware.info/?probe=79d8e655a3) | Mar 06, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [6044bde4fa](https://bsd-hardware.info/?probe=6044bde4fa) | Mar 06, 2022 |
| Unknown       | 0H47HH A07                  | Server      | [7cd73d4820](https://bsd-hardware.info/?probe=7cd73d4820) | Mar 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [20cdc9d999](https://bsd-hardware.info/?probe=20cdc9d999) | Mar 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c2051f121a](https://bsd-hardware.info/?probe=c2051f121a) | Mar 06, 2022 |
| HP            | 1589                        | Desktop     | [8bd32670c2](https://bsd-hardware.info/?probe=8bd32670c2) | Mar 06, 2022 |
| Barracuda ... | Barracuda Firewall X50      | Firewall    | [9097f70cc6](https://bsd-hardware.info/?probe=9097f70cc6) | Mar 06, 2022 |
| Protectli     | VP2410                      | Desktop     | [3b3ae27cb3](https://bsd-hardware.info/?probe=3b3ae27cb3) | Mar 06, 2022 |
| Cisco         | ASA5525 A0                  | Desktop     | [dcd3ccf4bf](https://bsd-hardware.info/?probe=dcd3ccf4bf) | Mar 06, 2022 |
| Protectli     | FW2 Ver                     | Desktop     | [a2ef313477](https://bsd-hardware.info/?probe=a2ef313477) | Mar 05, 2022 |
| MSI           | H81TI                       | Desktop     | [153dcd203c](https://bsd-hardware.info/?probe=153dcd203c) | Mar 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/USA/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 21.7.7   | 90        | 3.55%   |
| OPNsense 21.7.3   | 77        | 3.04%   |
| OPNsense 21.7.1   | 69        | 2.72%   |
| OPNsense 22.1     | 68        | 2.68%   |
| OPNsense 21.1.5   | 67        | 2.64%   |
| OPNsense 20.7.8   | 61        | 2.4%    |
| OPNsense 21.1.4   | 60        | 2.36%   |
| FreeBSD 13.0      | 60        | 2.36%   |
| OPNsense 22.7.4   | 58        | 2.29%   |
| OPNsense 22.1.8   | 58        | 2.29%   |
| OPNsense 21.1.3   | 58        | 2.29%   |
| helloSystem 0.7.0 | 55        | 2.17%   |
| OPNsense 22.1.10  | 53        | 2.09%   |
| OPNsense 21.1     | 51        | 2.01%   |
| OPNsense 21.1.8   | 50        | 1.97%   |
| OPNsense 22.7.2   | 44        | 1.73%   |
| OPNsense 22.1.6   | 42        | 1.66%   |
| OPNsense 22.1.4   | 42        | 1.66%   |
| OPNsense 22.1.2   | 42        | 1.66%   |
| OPNsense 21.1.7   | 42        | 1.66%   |
| OPNsense 21.1.1   | 42        | 1.66%   |
| helloSystem 0.5.0 | 42        | 1.66%   |
| OPNsense 22.7     | 41        | 1.62%   |
| FreeBSD 13.1      | 38        | 1.5%    |
| OPNsense 22.1.1   | 36        | 1.42%   |
| OPNsense 21.7.6   | 36        | 1.42%   |
| OPNsense 21.1.6   | 36        | 1.42%   |
| OPNsense 22.1.7   | 33        | 1.3%    |
| FreeBSD 13.0-p4   | 33        | 1.3%    |
| OPNsense 21.7.5   | 32        | 1.26%   |
| OPNsense 21.7.4   | 31        | 1.22%   |
| OPNsense 21.1.2   | 31        | 1.22%   |
| OpenBSD 6.8       | 31        | 1.22%   |
| FreeBSD 12.2      | 30        | 1.18%   |
| OPNsense 21.7     | 29        | 1.14%   |
| OPNsense 21.7.8   | 28        | 1.1%    |
| OPNsense 21.7.2   | 27        | 1.06%   |
| helloSystem 0.4.0 | 27        | 1.06%   |
| OPNsense 22.1.9   | 26        | 1.02%   |
| OPNsense 22.1.3   | 24        | 0.95%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 1094      | 57.25%  |
| FreeBSD     | 436       | 22.82%  |
| helloSystem | 141       | 7.38%   |
| OpenBSD     | 83        | 4.34%   |
| GhostBSD    | 44        | 2.3%    |
| NomadBSD    | 32        | 1.67%   |
| FreeNAS     | 17        | 0.89%   |
| pfSense     | 15        | 0.78%   |
| MidnightBSD | 12        | 0.63%   |
| TrueNAS     | 11        | 0.58%   |
| HardenedBSD | 9         | 0.47%   |
| DragonFly   | 6         | 0.31%   |
| NetBSD      | 5         | 0.26%   |
| FuryBSD     | 3         | 0.16%   |
| OS108       | 2         | 0.1%    |
| XigmaNAS    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 1844      | 97.41%  |
| i386    | 26        | 1.37%   |
| arm64   | 21        | 1.11%   |
| powerpc | 2         | 0.11%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 1315      | 68.13%  |
| helloDesktop  | 144       | 7.46%   |
| XFCE          | 85        | 4.4%    |
| MATE          | 65        | 3.37%   |
| KDE5          | 62        | 3.21%   |
| fvwm          | 58        | 3.01%   |
| TWM           | 49        | 2.54%   |
| Openbox       | 46        | 2.38%   |
| GNOME         | 40        | 2.07%   |
| i3            | 25        | 1.3%    |
| Cinnamon      | 12        | 0.62%   |
| Enlightenment | 6         | 0.31%   |
| Lumina        | 4         | 0.21%   |
| Fluxbox       | 3         | 0.16%   |
| AwesomeWM     | 3         | 0.16%   |
| Xfwm4         | 2         | 0.1%    |
| GNUstep       | 2         | 0.1%    |
| Window Maker  | 1         | 0.05%   |
| spectrwm      | 1         | 0.05%   |
| Picom         | 1         | 0.05%   |
| LXQt          | 1         | 0.05%   |
| LXDE          | 1         | 0.05%   |
| KDE           | 1         | 0.05%   |
| DWM           | 1         | 0.05%   |
| Compton       | 1         | 0.05%   |
| CDE           | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1333      | 70.05%  |
| X11     | 565       | 29.69%  |
| Wayland | 5         | 0.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1494      | 77.93%  |
| SLiM    | 231       | 12.05%  |
| LightDM | 70        | 3.65%   |
| SDDM    | 62        | 3.23%   |
| XDM     | 34        | 1.77%   |
| GDM     | 24        | 1.25%   |
| Ly      | 2         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 1382      | 71.31%  |
| en_US           | 316       | 16.31%  |
| C               | 231       | 11.92%  |
| en_US.US-ASCII  | 2         | 0.1%    |
| en_US.ISO8859-1 | 2         | 0.1%    |
| en_GB           | 2         | 0.1%    |
| es_CO           | 1         | 0.05%   |
| en_US.utf-8     | 1         | 0.05%   |
| de_DE           | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1555      | 80.7%   |
| BIOS | 372       | 19.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 1056      | 54.21%  |
| Zfs     | 771       | 39.58%  |
| Ffs     | 83        | 4.26%   |
| Cd9660  | 31        | 1.59%   |
| Hammer2 | 6         | 0.31%   |
| Unknown | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1716      | 89.61%  |
| MBR     | 174       | 9.09%   |
| Unknown | 19        | 0.99%   |
| BSD     | 6         | 0.31%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 318       | 16.82%  |
| Hewlett-Packard         | 190       | 10.05%  |
| Lenovo                  | 173       | 9.15%   |
| Supermicro              | 171       | 9.04%   |
| Protectli               | 145       | 7.67%   |
| ASUSTek Computer        | 130       | 6.87%   |
| Unknown                 | 126       | 6.66%   |
| ASRock                  | 86        | 4.55%   |
| Intel                   | 78        | 4.12%   |
| MSI                     | 56        | 2.96%   |
| Gigabyte Technology     | 48        | 2.54%   |
| Apple                   | 31        | 1.64%   |
| AMI                     | 30        | 1.59%   |
| PC Engines              | 28        | 1.48%   |
| Deciso                  | 16        | 0.85%   |
| Acer                    | 16        | 0.85%   |
| Sophos                  | 14        | 0.74%   |
| System76                | 10        | 0.53%   |
| CompuLab                | 10        | 0.53%   |
| Biostar                 | 10        | 0.53%   |
| AZW                     | 10        | 0.53%   |
| Toshiba                 | 9         | 0.48%   |
| AWOW                    | 8         | 0.42%   |
| ASRockRack              | 7         | 0.37%   |
| Shuttle                 | 6         | 0.32%   |
| SeeedStudio             | 6         | 0.32%   |
| Framework               | 6         | 0.32%   |
| ZOTAC                   | 5         | 0.26%   |
| HARDKERNEL              | 5         | 0.26%   |
| Fujitsu                 | 5         | 0.26%   |
| Foxconn                 | 5         | 0.26%   |
| Cisco Systems           | 5         | 0.26%   |
| BESSTAR Tech            | 5         | 0.26%   |
| TYAN Computer           | 4         | 0.21%   |
| Techvision              | 4         | 0.21%   |
| Seeed Studio            | 4         | 0.21%   |
| Raspberry Pi Foundation | 4         | 0.21%   |
| HPE                     | 4         | 0.21%   |
| Google                  | 4         | 0.21%   |
| Gateway                 | 4         | 0.21%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 131       | 6.93%   |
| Protectli FW4B                      | 56        | 2.96%   |
| Protectli FW6                       | 42        | 2.22%   |
| Supermicro Super Server             | 39        | 2.06%   |
| AMI Aptio CRB                       | 26        | 1.37%   |
| Intel Q3XXG4-P V1.0                 | 23        | 1.22%   |
| HP t620 PLUS Quad Core TC           | 20        | 1.06%   |
| HP t730 Thin Client                 | 18        | 0.95%   |
| Dell OptiPlex 9020                  | 18        | 0.95%   |
| Supermicro X9SCL/X9SCM              | 17        | 0.9%    |
| Supermicro X10SLH-N6-ST031          | 16        | 0.85%   |
| Dell OptiPlex 3020                  | 16        | 0.85%   |
| PC Engines apu4                     | 13        | 0.69%   |
| PC Engines APU2                     | 13        | 0.69%   |
| Dell PowerEdge R210 II              | 13        | 0.69%   |
| ASUS All Series                     | 13        | 0.69%   |
| Dell OptiPlex 990                   | 12        | 0.63%   |
| Protectli VP2410                    | 11        | 0.58%   |
| Protectli FW2B                      | 11        | 0.58%   |
| Dell OptiPlex 7010                  | 11        | 0.58%   |
| Deciso Netboard A20                 | 10        | 0.53%   |
| CompuLab fitlet2                    | 10        | 0.53%   |
| Supermicro A1SAi                    | 9         | 0.48%   |
| HP EliteDesk 800 G1 SFF             | 9         | 0.48%   |
| Sophos XG                           | 8         | 0.42%   |
| Dell PowerEdge R610                 | 8         | 0.42%   |
| Protectli FW6E                      | 7         | 0.37%   |
| Protectli FW6D                      | 7         | 0.37%   |
| Intel Nobilis                       | 7         | 0.37%   |
| Dell OptiPlex 790                   | 7         | 0.37%   |
| AZW GK55                            | 7         | 0.37%   |
| AWOW PC BOX                         | 7         | 0.37%   |
| Protectli FW1                       | 6         | 0.32%   |
| Framework Laptop                    | 6         | 0.32%   |
| Dell Wyse 5070 Extended Thin Client | 6         | 0.32%   |
| Dell PowerEdge R630                 | 6         | 0.32%   |
| Dell OptiPlex 390                   | 6         | 0.32%   |
| Dell OptiPlex 3010                  | 6         | 0.32%   |
| ASUS TUF GAMING X570-PLUS           | 6         | 0.32%   |
| Supermicro X7SPA-HF                 | 5         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 131       | 6.93%   |
| Dell OptiPlex              | 123       | 6.5%    |
| Lenovo ThinkPad            | 103       | 5.45%   |
| Dell PowerEdge             | 82        | 4.34%   |
| Protectli FW4B             | 56        | 2.96%   |
| Protectli FW6              | 42        | 2.22%   |
| Supermicro Super           | 39        | 2.06%   |
| Lenovo ThinkCentre         | 37        | 1.96%   |
| Dell Inspiron              | 29        | 1.53%   |
| Dell Latitude              | 28        | 1.48%   |
| Dell Precision             | 26        | 1.37%   |
| AMI Aptio                  | 26        | 1.37%   |
| Intel Q3XXG4-P             | 24        | 1.27%   |
| HP t620                    | 22        | 1.16%   |
| ASUS PRIME                 | 20        | 1.06%   |
| HP EliteDesk               | 19        | 1%      |
| ASUS ROG                   | 19        | 1%      |
| HP t730                    | 18        | 0.95%   |
| HP Compaq                  | 18        | 0.95%   |
| Supermicro X9SCL           | 17        | 0.9%    |
| Supermicro X10SLH-N6-ST031 | 16        | 0.85%   |
| HP ProLiant                | 16        | 0.85%   |
| HP Pavilion                | 15        | 0.79%   |
| ASUS TUF                   | 15        | 0.79%   |
| HP ProDesk                 | 14        | 0.74%   |
| ASRock X570                | 14        | 0.74%   |
| PC Engines apu4            | 13        | 0.69%   |
| PC Engines APU2            | 13        | 0.69%   |
| ASUS All                   | 13        | 0.69%   |
| Protectli VP2410           | 11        | 0.58%   |
| Protectli FW2B             | 11        | 0.58%   |
| Deciso Netboard            | 11        | 0.58%   |
| Dell XPS                   | 10        | 0.53%   |
| CompuLab fitlet2           | 10        | 0.53%   |
| Supermicro A1SAi           | 9         | 0.48%   |
| Sophos XG                  | 8         | 0.42%   |
| Lenovo IdeaPad             | 8         | 0.42%   |
| Acer Aspire                | 8         | 0.42%   |
| Toshiba Satellite          | 7         | 0.37%   |
| Protectli FW6E             | 7         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 257       | 13.59%  |
| 2019    | 246       | 13.01%  |
| 2020    | 195       | 10.31%  |
| 2021    | 151       | 7.99%   |
| 2016    | 137       | 7.24%   |
| 2014    | 133       | 7.03%   |
| 2015    | 125       | 6.61%   |
| 2011    | 121       | 6.4%    |
| 2013    | 114       | 6.03%   |
| 2017    | 100       | 5.29%   |
| 2012    | 88        | 4.65%   |
| 2010    | 50        | 2.64%   |
| 2022    | 46        | 2.43%   |
| 2009    | 38        | 2.01%   |
| Unknown | 35        | 1.85%   |
| 2008    | 23        | 1.22%   |
| 2007    | 15        | 0.79%   |
| 2006    | 10        | 0.53%   |
| 2004    | 4         | 0.21%   |
| 2005    | 1         | 0.05%   |
| 2002    | 1         | 0.05%   |
| 2001    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1154      | 61.03%  |
| Notebook       | 355       | 18.77%  |
| Server         | 203       | 10.74%  |
| Mini pc        | 129       | 6.82%   |
| Firewall       | 20        | 1.06%   |
| Convertible    | 14        | 0.74%   |
| System on chip | 12        | 0.63%   |
| All in one     | 4         | 0.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1813      | 95.88%  |
| Yes  | 78        | 4.12%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 701       | 36.21%  |
| 16.01-24.0      | 427       | 22.06%  |
| 4.01-8.0        | 329       | 16.99%  |
| 32.01-64.0      | 245       | 12.65%  |
| 64.01-256.0     | 109       | 5.63%   |
| 2.01-3.0        | 41        | 2.12%   |
| 24.01-32.0      | 34        | 1.76%   |
| 3.01-4.0        | 26        | 1.34%   |
| 0.51-1.0        | 9         | 0.46%   |
| 1.01-2.0        | 8         | 0.41%   |
| 0.01-0.5        | 5         | 0.26%   |
| More than 256.0 | 2         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 893       | 44.81%  |
| 0.51-1.0    | 559       | 28.05%  |
| 1.01-2.0    | 281       | 14.1%   |
| 4.01-8.0    | 63        | 3.16%   |
| 2.01-3.0    | 57        | 2.86%   |
| 3.01-4.0    | 35        | 1.76%   |
| 8.01-16.0   | 35        | 1.76%   |
| 24.01-32.0  | 17        | 0.85%   |
| 16.01-24.0  | 16        | 0.8%    |
| 32.01-64.0  | 13        | 0.65%   |
| 0           | 10        | 0.5%    |
| Unknown     | 8         | 0.4%    |
| 64.01-256.0 | 6         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1324      | 68.11%  |
| 2      | 262       | 13.48%  |
| 0      | 144       | 7.41%   |
| 3      | 74        | 3.81%   |
| 4      | 39        | 2.01%   |
| 5      | 22        | 1.13%   |
| 6      | 21        | 1.08%   |
| 7      | 10        | 0.51%   |
| 14     | 8         | 0.41%   |
| 12     | 6         | 0.31%   |
| 8      | 6         | 0.31%   |
| 9      | 5         | 0.26%   |
| 11     | 4         | 0.21%   |
| 10     | 4         | 0.21%   |
| 21     | 2         | 0.1%    |
| 18     | 2         | 0.1%    |
| 17     | 2         | 0.1%    |
| 58     | 1         | 0.05%   |
| 40     | 1         | 0.05%   |
| 28     | 1         | 0.05%   |
| 26     | 1         | 0.05%   |
| 22     | 1         | 0.05%   |
| 19     | 1         | 0.05%   |
| 16     | 1         | 0.05%   |
| 15     | 1         | 0.05%   |
| 13     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1454      | 75.97%  |
| Yes       | 460       | 24.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1813      | 95.88%  |
| No        | 78        | 4.12%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1241      | 65.04%  |
| Yes       | 667       | 34.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1466      | 76.96%  |
| Yes       | 439       | 23.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| USA     | 1891      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Brooklyn      | 37        | 1.8%    |
| Chicago       | 33        | 1.6%    |
| Seattle       | 28        | 1.36%   |
| Denver        | 28        | 1.36%   |
| New York      | 24        | 1.17%   |
| Portland      | 22        | 1.07%   |
| Dallas        | 21        | 1.02%   |
| Rochester     | 18        | 0.87%   |
| Los Angeles   | 18        | 0.87%   |
| Mountain View | 15        | 0.73%   |
| Columbus      | 15        | 0.73%   |
| Austin        | 15        | 0.73%   |
| San Francisco | 14        | 0.68%   |
| Atlanta       | 14        | 0.68%   |
| Grand Rapids  | 13        | 0.63%   |
| Springfield   | 12        | 0.58%   |
| Ypsilanti     | 11        | 0.53%   |
| Phoenix       | 11        | 0.53%   |
| Vienna        | 10        | 0.49%   |
| Salem         | 10        | 0.49%   |
| Omaha         | 10        | 0.49%   |
| Minneapolis   | 10        | 0.49%   |
| Las Vegas     | 10        | 0.49%   |
| San Antonio   | 9         | 0.44%   |
| Bothell       | 9         | 0.44%   |
| Washington    | 8         | 0.39%   |
| San Jose      | 8         | 0.39%   |
| San Diego     | 8         | 0.39%   |
| Poway         | 8         | 0.39%   |
| Philadelphia  | 8         | 0.39%   |
| Oakland       | 8         | 0.39%   |
| Milwaukee     | 8         | 0.39%   |
| Miami         | 8         | 0.39%   |
| Madison       | 8         | 0.39%   |
| Lexington     | 8         | 0.39%   |
| Jacksonville  | 8         | 0.39%   |
| Houston       | 8         | 0.39%   |
| Frisco        | 8         | 0.39%   |
| Fort Worth    | 8         | 0.39%   |
| Beaverton     | 8         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 371       | 677    | 16.05%  |
| WDC                 | 317       | 929    | 13.71%  |
| Seagate             | 229       | 651    | 9.9%    |
| Kingston            | 150       | 200    | 6.49%   |
| SanDisk             | 112       | 142    | 4.84%   |
| Crucial             | 106       | 163    | 4.58%   |
| Intel               | 102       | 191    | 4.41%   |
| Toshiba             | 83        | 146    | 3.59%   |
| Transcend           | 80        | 143    | 3.46%   |
| Hitachi             | 56        | 143    | 2.42%   |
| Phison              | 48        | 73     | 2.08%   |
| A-DATA Technology   | 47        | 72     | 2.03%   |
| Hoodisk             | 43        | 58     | 1.86%   |
| Protectli           | 38        | 60     | 1.64%   |
| SK hynix            | 36        | 43     | 1.56%   |
| PNY                 | 34        | 48     | 1.47%   |
| HGST                | 34        | 94     | 1.47%   |
| China               | 33        | 41     | 1.43%   |
| Hewlett-Packard     | 28        | 91     | 1.21%   |
| SPCC                | 25        | 47     | 1.08%   |
| Dogfish             | 21        | 32     | 0.91%   |
| NVMe                | 20        | 27     | 0.87%   |
| BIWIN               | 20        | 32     | 0.87%   |
| Micron Technology   | 19        | 24     | 0.82%   |
| OCZ                 | 17        | 26     | 0.74%   |
| FORESEE             | 16        | 22     | 0.69%   |
| Apple               | 14        | 15     | 0.61%   |
| KingSpec            | 13        | 16     | 0.56%   |
| Apacer              | 13        | 14     | 0.56%   |
| Corsair             | 12        | 32     | 0.52%   |
| Mushkin             | 9         | 13     | 0.39%   |
| LITEON              | 9         | 13     | 0.39%   |
| Plextor             | 8         | 16     | 0.35%   |
| Patriot             | 8         | 9      | 0.35%   |
| OWC                 | 8         | 12     | 0.35%   |
| Zheino              | 7         | 14     | 0.3%    |
| KIOXIA              | 7         | 14     | 0.3%    |
| LITEONIT            | 6         | 6      | 0.26%   |
| Lexar               | 6         | 10     | 0.26%   |
| Team                | 5         | 7      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB       | 23        | 0.9%    |
| Kingston SUV500MS240G 240GB     | 22        | 0.86%   |
| Kingston SA400S37240G 240GB     | 22        | 0.86%   |
| Kingston SUV500MS120G 120GB     | 18        | 0.71%   |
| Seagate ST500DM002-1BD142 500GB | 17        | 0.67%   |
| Samsung SSD 860 EVO 500GB       | 17        | 0.67%   |
| Protectli 120GB mSATA           | 16        | 0.63%   |
| Hoodisk SSD 32GB                | 16        | 0.63%   |
| PNY CS900 120GB SSD             | 15        | 0.59%   |
| Samsung SSD 970 EVO Plus 500GB  | 14        | 0.55%   |
| Samsung SSD 860 EVO 250GB       | 14        | 0.55%   |
| Samsung SSD 860 EVO 1TB         | 14        | 0.55%   |
| Samsung SSD 850 EVO 500GB       | 14        | 0.55%   |
| BIWIN SSD 128GB                 | 14        | 0.55%   |
| Kingston SA400S37120G 120GB     | 13        | 0.51%   |
| WDC WD800JD-75MSA3 80GB         | 12        | 0.47%   |
| SanDisk SSD PLUS 240GB          | 12        | 0.47%   |
| Hoodisk SSD 128GB               | 12        | 0.47%   |
| Crucial CT500MX500SSD1 500GB    | 12        | 0.47%   |
| WDC WD10EZEX-08WN4A0 1TB        | 11        | 0.43%   |
| Crucial CT1000MX500SSD1 1TB     | 11        | 0.43%   |
| WDC WDS500G3X0C-00SJG0 500GB    | 10        | 0.39%   |
| Transcend TS256GMTS952T2 256GB  | 10        | 0.39%   |
| SPCC Solid State Disk 128GB     | 10        | 0.39%   |
| SanDisk SDSA6MM-016G-1006 16GB  | 10        | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB    | 10        | 0.39%   |
| Samsung SSD 860 EVO M.2 250GB   | 10        | 0.39%   |
| Phison Sabrent 256GB            | 10        | 0.39%   |
| FORESEE 128GB SSD               | 10        | 0.39%   |
| Crucial CT250MX500SSD1 250GB    | 10        | 0.39%   |
| Seagate ST4000DM000-1F2168 4TB  | 9         | 0.35%   |
| SanDisk SDSSDA120G 120GB        | 9         | 0.35%   |
| Hoodisk SSD 64GB                | 9         | 0.35%   |
| WDC WD30EFRX-68EUZN0 3TB        | 8         | 0.31%   |
| Transcend TS128GMSA230S 128GB   | 8         | 0.31%   |
| Toshiba DT01ACA100 1TB          | 8         | 0.31%   |
| Seagate ST1000DM003-1CH162 1TB  | 8         | 0.31%   |
| Samsung SSD 960 EVO 500GB       | 8         | 0.31%   |
| Samsung SSD 960 EVO 250GB       | 8         | 0.31%   |
| HP RAID 0 2TB                   | 8         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC                                | 242       | 793    | 34.72%  |
| Seagate                            | 220       | 628    | 31.56%  |
| Toshiba                            | 69        | 129    | 9.9%    |
| Hitachi                            | 56        | 143    | 8.03%   |
| HGST                               | 34        | 94     | 4.88%   |
| Hewlett-Packard                    | 18        | 59     | 2.58%   |
| NVMe                               | 12        | 15     | 1.72%   |
| Samsung Electronics                | 11        | 16     | 1.58%   |
| Apple                              | 7         | 8      | 1%      |
| Maxtor                             | 3         | 7      | 0.43%   |
| Fujitsu                            | 3         | 3      | 0.43%   |
| LSI                                | 2         | 6      | 0.29%   |
| Lexar                              | 2         | 2      | 0.29%   |
| HPE                                | 2         | 7      | 0.29%   |
| Adaptec                            | 2         | 2      | 0.29%   |
| WD MediaMax                        | 1         | 3      | 0.14%   |
| QUANTUM                            | 1         | 1      | 0.14%   |
| Product:              USB DISK 3.0 | 1         | 1      | 0.14%   |
| OPENBSD                            | 1         | 1      | 0.14%   |
| NETAPP                             | 1         | 2      | 0.14%   |
| MaxDigital                         | 1         | 1      | 0.14%   |
| MARVELL                            | 1         | 1      | 0.14%   |
| IBM/Hitachi                        | 1         | 1      | 0.14%   |
| IBM-207x                           | 1         | 1      | 0.14%   |
| Generic                            | 1         | 1      | 0.14%   |
| ExcelStor Technology               | 1         | 4      | 0.14%   |
| Dell                               | 1         | 3      | 0.14%   |
| China                              | 1         | 1      | 0.14%   |
| ASMT                               | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 255       | 457    | 19.45%  |
| Kingston            | 141       | 190    | 10.76%  |
| SanDisk             | 110       | 137    | 8.39%   |
| Crucial             | 88        | 137    | 6.71%   |
| Intel               | 79        | 159    | 6.03%   |
| Transcend           | 75        | 137    | 5.72%   |
| Hoodisk             | 42        | 57     | 3.2%    |
| Protectli           | 38        | 60     | 2.9%    |
| A-DATA Technology   | 38        | 56     | 2.9%    |
| WDC                 | 35        | 69     | 2.67%   |
| PNY                 | 33        | 47     | 2.52%   |
| China               | 32        | 40     | 2.44%   |
| Phison              | 26        | 35     | 1.98%   |
| SPCC                | 22        | 44     | 1.68%   |
| Dogfish             | 21        | 32     | 1.6%    |
| BIWIN               | 20        | 32     | 1.53%   |
| SK hynix            | 19        | 21     | 1.45%   |
| OCZ                 | 17        | 26     | 1.3%    |
| FORESEE             | 16        | 22     | 1.22%   |
| KingSpec            | 13        | 16     | 0.99%   |
| Apacer              | 13        | 14     | 0.99%   |
| Micron Technology   | 11        | 14     | 0.84%   |
| Corsair             | 10        | 14     | 0.76%   |
| Seagate             | 8         | 18     | 0.61%   |
| OWC                 | 8         | 12     | 0.61%   |
| NVMe                | 8         | 10     | 0.61%   |
| LITEON              | 8         | 12     | 0.61%   |
| Zheino              | 7         | 14     | 0.53%   |
| Toshiba             | 7         | 10     | 0.53%   |
| Plextor             | 7         | 12     | 0.53%   |
| Patriot             | 7         | 8      | 0.53%   |
| Mushkin             | 7         | 10     | 0.53%   |
| Apple               | 7         | 7      | 0.53%   |
| LITEONIT            | 6         | 6      | 0.46%   |
| Supermicro          | 5         | 5      | 0.38%   |
| Hewlett-Packard     | 5         | 8      | 0.38%   |
| ShiJi               | 4         | 4      | 0.31%   |
| SATADOM             | 4         | 8      | 0.31%   |
| MyDigitalSSD        | 4         | 6      | 0.31%   |
| Lexar               | 4         | 8      | 0.31%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1178      | 2053   | 57.32%  |
| HDD  | 570       | 1934   | 27.74%  |
| NVMe | 307       | 535    | 14.94%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1570      | 3987   | 83.64%  |
| NVMe | 307       | 535    | 16.36%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1308      | 2239   | 70.93%  |
| 0.51-1.0   | 296       | 593    | 16.05%  |
| 1.01-2.0   | 96        | 293    | 5.21%   |
| 4.01-10.0  | 54        | 417    | 2.93%   |
| 2.01-3.0   | 40        | 166    | 2.17%   |
| 3.01-4.0   | 36        | 165    | 1.95%   |
| 10.01-20.0 | 13        | 110    | 0.7%    |
| 20.01-50.0 | 1         | 4      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 764       | 39.02%  |
| 251-500        | 351       | 17.93%  |
| 1-20           | 208       | 10.62%  |
| 51-100         | 202       | 10.32%  |
| 501-1000       | 182       | 9.3%    |
| 21-50          | 172       | 8.78%   |
| 1001-2000      | 44        | 2.25%   |
| More than 3000 | 18        | 0.92%   |
| Unknown        | 12        | 0.61%   |
| 2001-3000      | 5         | 0.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1735      | 88.75%  |
| 21-50          | 111       | 5.68%   |
| 51-100         | 47        | 2.4%    |
| 101-250        | 28        | 1.43%   |
| Unknown        | 12        | 0.61%   |
| 251-500        | 11        | 0.56%   |
| More than 3000 | 5         | 0.26%   |
| 2001-3000      | 2         | 0.1%    |
| 501-1000       | 2         | 0.1%    |
| 1001-2000      | 1         | 0.05%   |
| 0              | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 6         | 9      | 2.22%   |
| Crucial CT275MX300SSD1 275GB          | 4         | 7      | 1.48%   |
| Apacer 16GB SATA Flash Drive          | 4         | 5      | 1.48%   |
| SK hynix SC210 mSATA 256GB            | 3         | 3      | 1.11%   |
| Seagate ST500LM021-1KJ152 500GB       | 3         | 3      | 1.11%   |
| Seagate ST3500418AS 500GB             | 3         | 10     | 1.11%   |
| Kingston SV300S37A60G 64GB            | 3         | 3      | 1.11%   |
| Kingston SMS200S3120G 120GB           | 3         | 3      | 1.11%   |
| Apacer 32GB SATA Flash Drive          | 3         | 3      | 1.11%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 2         | 2      | 0.74%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2         | 9      | 0.74%   |
| WDC WD1600BEKT-66F3T2 160GB           | 2         | 4      | 0.74%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.74%   |
| Toshiba DT01ACA050 500GB              | 2         | 2      | 0.74%   |
| SSSTC CVB-8D128-HP 128GB              | 2         | 2      | 0.74%   |
| Seagate ST3500413AS 500GB             | 2         | 9      | 0.74%   |
| Seagate ST31000528AS 1TB              | 2         | 2      | 0.74%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 2      | 0.74%   |
| Seagate ST1000DM003-9YN162 1TB        | 2         | 6      | 0.74%   |
| SanDisk SSD PLUS 240GB                | 2         | 3      | 0.74%   |
| Samsung Electronics SSD 850 EVO 500GB | 2         | 2      | 0.74%   |
| MyDigitalSSD SB2 128GB                | 2         | 4      | 0.74%   |
| Kingston SV300S37A120G 120GB          | 2         | 2      | 0.74%   |
| Kingston SUV400S37120G 120GB          | 2         | 3      | 0.74%   |
| Kingston SNS4151S316G 16GB            | 2         | 2      | 0.74%   |
| Intel SSDSA2M080G2GC 80GB             | 2         | 2      | 0.74%   |
| Hitachi HUA722020ALA331 2TB           | 2         | 4      | 0.74%   |
| Hitachi HTS725032A9A364 320GB         | 2         | 2      | 0.74%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.74%   |
| Crucial CT240M500SSD1 240GB           | 2         | 2      | 0.74%   |
| ZTC SM201-064G                        | 1         | 3      | 0.37%   |
| Wintec 120GB SATA3 SF2281 SSD         | 1         | 1      | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB          | 1         | 1      | 0.37%   |
| WDC WD60EFAX-68SHWN0 6TB              | 1         | 2      | 0.37%   |
| WDC WD6003FZBX-00K5WB0 6TB            | 1         | 1      | 0.37%   |
| WDC WD6002FFWX-68TZ4N0 6TB            | 1         | 7      | 0.37%   |
| WDC WD5003ABYX-18WERA0 500GB          | 1         | 4      | 0.37%   |
| WDC WD5000LPCX-75VHAT0 500GB          | 1         | 1      | 0.37%   |
| WDC WD5000AAVS-00G9B1 500GB           | 1         | 1      | 0.37%   |
| WDC WD5000AAKX-08ERMA0 500GB          | 1         | 1      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 58        | 109    | 22.39%  |
| WDC                  | 41        | 83     | 15.83%  |
| Intel                | 21        | 25     | 8.11%   |
| Kingston             | 20        | 23     | 7.72%   |
| Hitachi              | 17        | 23     | 6.56%   |
| Samsung Electronics  | 16        | 20     | 6.18%   |
| Toshiba              | 15        | 21     | 5.79%   |
| Crucial              | 11        | 15     | 4.25%   |
| HGST                 | 7         | 7      | 2.7%    |
| Apacer               | 7         | 8      | 2.7%    |
| SanDisk              | 6         | 9      | 2.32%   |
| SK hynix             | 5         | 6      | 1.93%   |
| OCZ                  | 4         | 4      | 1.54%   |
| SSSTC                | 2         | 2      | 0.77%   |
| MyDigitalSSD         | 2         | 4      | 0.77%   |
| Micron Technology    | 2         | 2      | 0.77%   |
| LITEON               | 2         | 3      | 0.77%   |
| ZTC                  | 1         | 3      | 0.39%   |
| Wintec               | 1         | 1      | 0.39%   |
| WD MediaMax          | 1         | 3      | 0.39%   |
| VisionTek            | 1         | 1      | 0.39%   |
| Transcend            | 1         | 4      | 0.39%   |
| SPCC                 | 1         | 3      | 0.39%   |
| Phison               | 1         | 1      | 0.39%   |
| Patriot              | 1         | 1      | 0.39%   |
| Maxtor               | 1         | 4      | 0.39%   |
| KingSpec             | 1         | 1      | 0.39%   |
| KingDian             | 1         | 1      | 0.39%   |
| INDMEM               | 1         | 1      | 0.39%   |
| IBM/Hitachi          | 1         | 1      | 0.39%   |
| HPE                  | 1         | 3      | 0.39%   |
| HP Phison            | 1         | 1      | 0.39%   |
| Hewlett-Packard      | 1         | 4      | 0.39%   |
| Fujitsu              | 1         | 1      | 0.39%   |
| ExcelStor Technology | 1         | 2      | 0.39%   |
| Dogfish              | 1         | 5      | 0.39%   |
| China                | 1         | 1      | 0.39%   |
| BIWIN                | 1         | 1      | 0.39%   |
| Apple                | 1         | 1      | 0.39%   |
| A-DATA Technology    | 1         | 1      | 0.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 58        | 109    | 39.19%  |
| WDC                  | 40        | 82     | 27.03%  |
| Hitachi              | 17        | 23     | 11.49%  |
| Toshiba              | 13        | 19     | 8.78%   |
| HGST                 | 7         | 7      | 4.73%   |
| Samsung Electronics  | 4         | 5      | 2.7%    |
| WD MediaMax          | 1         | 3      | 0.68%   |
| Maxtor               | 1         | 4      | 0.68%   |
| IBM/Hitachi          | 1         | 1      | 0.68%   |
| HPE                  | 1         | 3      | 0.68%   |
| Hewlett-Packard      | 1         | 4      | 0.68%   |
| Fujitsu              | 1         | 1      | 0.68%   |
| ExcelStor Technology | 1         | 2      | 0.68%   |
| China                | 1         | 1      | 0.68%   |
| Apple                | 1         | 1      | 0.68%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 141       | 265    | 56.18%  |
| SSD  | 109       | 143    | 43.43%  |
| NVMe | 1         | 1      | 0.4%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZYLN256HCHP-000L2 256GB | 2         | 2      | 66.67%  |
| Samsung Electronics HD204UI 2TB              | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 4      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1570      | 3990   | 83.24%  |
| Malfunc  | 247       | 409    | 13.1%   |
| Detected | 66        | 119    | 3.5%    |
| Failed   | 3         | 4      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1446      | 61.01%  |
| AMD                              | 324       | 13.67%  |
| Samsung Electronics              | 134       | 5.65%   |
| Broadcom / LSI                   | 102       | 4.3%    |
| SanDisk                          | 61        | 2.57%   |
| ASMedia Technology               | 43        | 1.81%   |
| Phison Electronics               | 34        | 1.43%   |
| Marvell Technology Group         | 27        | 1.14%   |
| SK hynix                         | 20        | 0.84%   |
| Chelsio Communications           | 18        | 0.76%   |
| Hewlett-Packard                  | 15        | 0.63%   |
| Silicon Motion                   | 14        | 0.59%   |
| Micron/Crucial Technology        | 14        | 0.59%   |
| Nvidia                           | 12        | 0.51%   |
| Micron Technology                | 10        | 0.42%   |
| Kingston Technology Company      | 10        | 0.42%   |
| JMicron Technology               | 10        | 0.42%   |
| KIOXIA                           | 9         | 0.38%   |
| Adaptec                          | 8         | 0.34%   |
| Toshiba                          | 7         | 0.3%    |
| ADATA Technology                 | 7         | 0.3%    |
| Silicon Image                    | 6         | 0.25%   |
| Seagate Technology               | 5         | 0.21%   |
| Unknown                          | 5         | 0.21%   |
| Shenzhen Longsys Electronics     | 4         | 0.17%   |
| Realtek Semiconductor            | 4         | 0.17%   |
| Solid State Storage Technology   | 3         | 0.13%   |
| VIA Technologies                 | 2         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.08%   |
| Lite-On Technology               | 2         | 0.08%   |
| Lenovo                           | 2         | 0.08%   |
| Broadcom                         | 2         | 0.08%   |
| Biwin Storage Technology         | 2         | 0.08%   |
| Union Memory (Shenzhen)          | 1         | 0.04%   |
| HighPoint Technologies           | 1         | 0.04%   |
| Dell                             | 1         | 0.04%   |
| Areca Technology                 | 1         | 0.04%   |
| Amazon.com                       | 1         | 0.04%   |
| 3ware                            | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 231       | 8.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 171       | 6.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 125       | 4.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 92        | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 90        | 3.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 69        | 2.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 69        | 2.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 65        | 2.39%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 58        | 2.14%   |
| Intel SATA Controller [RAID mode]                                                | 47        | 1.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 45        | 1.66%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 43        | 1.58%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 39        | 1.44%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 39        | 1.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 37        | 1.36%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 37        | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 37        | 1.36%   |
| Unknown                                                                          | 37        | 1.36%   |
| AMD 400 Series Chipset SATA Controller                                           | 36        | 1.33%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 35        | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 32        | 1.18%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 31        | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 29        | 1.07%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 27        | 0.99%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 27        | 0.99%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 26        | 0.96%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 26        | 0.96%   |
| AMD FCH IDE Controller                                                           | 25        | 0.92%   |
| Phison E12 NVMe Controller                                                       | 24        | 0.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 24        | 0.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 24        | 0.88%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 23        | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 23        | 0.85%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 22        | 0.81%   |
| AMD 500 Series Chipset SATA Controller                                           | 22        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 21        | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 20        | 0.74%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 19        | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                            | 16        | 0.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 16        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1557      | 65.45%  |
| NVMe | 338       | 14.21%  |
| IDE  | 240       | 10.09%  |
| RAID | 147       | 6.18%   |
| SAS  | 65        | 2.73%   |
| SCSI | 32        | 1.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1522      | 80.27%  |
| AMD      | 349       | 18.41%  |
| ARM      | 18        | 0.95%   |
| Unknown  | 4         | 0.21%   |
| Motorola | 1         | 0.05%   |
| IBM      | 1         | 0.05%   |
| i        | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz        | 58        | 3.02%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 42        | 2.19%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 34        | 1.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 28        | 1.46%   |
| AMD GX-412TC SOC                         | 26        | 1.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 23        | 1.2%    |
| Intel Core i5-4570 CPU @ 3.20GHz         | 23        | 1.2%    |
| AMD GX-420CA SOC with Radeon HD Graphics | 20        | 1.04%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 19        | 0.99%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 19        | 0.99%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 18        | 0.94%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 18        | 0.94%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 18        | 0.94%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 17        | 0.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 15        | 0.78%   |
| Intel Atom CPU D525 @ 1.80GHz            | 15        | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 13        | 0.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 13        | 0.68%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 13        | 0.68%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 13        | 0.68%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 13        | 0.68%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz      | 12        | 0.62%   |
| Intel Celeron N5105 @ 2.00GHz            | 12        | 0.62%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 12        | 0.62%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz        | 11        | 0.57%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 11        | 0.57%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 11        | 0.57%   |
| Intel Core 2 Duo                         | 11        | 0.57%   |
| AMD Ryzen 7 2700 Eight-Core Processor    | 11        | 0.57%   |
| Intel Xeon CPU D-1518 @ 2.20GHz          | 10        | 0.52%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 10        | 0.52%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 10        | 0.52%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 9         | 0.47%   |
| Intel Xeon CPU E31220 @ 3.10GHz          | 8         | 0.42%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 8         | 0.42%   |
| Intel Core i7-4790 CPU @ 3.60GHz         | 8         | 0.42%   |
| Intel Core i7-4770 CPU @ 3.40GHz         | 8         | 0.42%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 8         | 0.42%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 8         | 0.42%   |
| Intel Core i3-10100 CPU @ 3.60GHz        | 8         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 382       | 20%     |
| Intel Xeon              | 279       | 14.61%  |
| Intel Celeron           | 256       | 13.4%   |
| Intel Core i7           | 225       | 11.78%  |
| Intel Core i3           | 119       | 6.23%   |
| Intel Atom              | 106       | 5.55%   |
| Other                   | 65        | 3.4%    |
| AMD Ryzen 7             | 61        | 3.19%   |
| AMD GX                  | 55        | 2.88%   |
| AMD Ryzen 5             | 43        | 2.25%   |
| Intel Core 2 Duo        | 35        | 1.83%   |
| Intel Pentium           | 33        | 1.73%   |
| AMD FX                  | 20        | 1.05%   |
| ARM Cortex              | 17        | 0.89%   |
| AMD Ryzen 9             | 17        | 0.89%   |
| AMD Ryzen 3             | 14        | 0.73%   |
| AMD EPYC                | 14        | 0.73%   |
| AMD A10                 | 11        | 0.58%   |
| Intel Core i9           | 10        | 0.52%   |
| Intel Pentium Silver    | 8         | 0.42%   |
| Intel Core 2            | 8         | 0.42%   |
| AMD Ryzen 5 PRO         | 8         | 0.42%   |
| Intel Core 2 Quad       | 7         | 0.37%   |
| AMD Phenom II X4        | 7         | 0.37%   |
| AMD Athlon              | 7         | 0.37%   |
| AMD A8                  | 7         | 0.37%   |
| Intel Pentium 4         | 6         | 0.31%   |
| AMD Ryzen Embedded      | 6         | 0.31%   |
| AMD Opteron             | 6         | 0.31%   |
| AMD G                   | 6         | 0.31%   |
| AMD A6                  | 5         | 0.26%   |
| AMD A4                  | 5         | 0.26%   |
| Intel Pentium Dual-Core | 4         | 0.21%   |
| Intel Genuine           | 4         | 0.21%   |
| Intel Pentium M         | 3         | 0.16%   |
| Intel Pentium D         | 3         | 0.16%   |
| AMD Ryzen 7 PRO         | 3         | 0.16%   |
| AMD Phenom II X6        | 3         | 0.16%   |
| AMD E2                  | 3         | 0.16%   |
| AMD E1                  | 3         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 937       | 49.03%  |
| 2       | 491       | 25.69%  |
| 8       | 134       | 7.01%   |
| Unknown | 80        | 4.19%   |
| 6       | 76        | 3.98%   |
| 16      | 71        | 3.72%   |
| 12      | 63        | 3.3%    |
| 1       | 19        | 0.99%   |
| 24      | 12        | 0.63%   |
| 32      | 7         | 0.37%   |
| 20      | 6         | 0.31%   |
| 10      | 5         | 0.26%   |
| 48      | 3         | 0.16%   |
| 28      | 2         | 0.1%    |
| 14      | 2         | 0.1%    |
| 3       | 2         | 0.1%    |
| 64      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1772      | 93.41%  |
| 2       | 89        | 4.69%   |
| Unknown | 34        | 1.79%   |
| 8       | 1         | 0.05%   |
| 4       | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1002      | 52.68%  |
| 2       | 812       | 42.69%  |
| Unknown | 87        | 4.57%   |
| 4       | 1         | 0.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 248       | 13%     |
| Haswell         | 226       | 11.84%  |
| Silvermont      | 178       | 9.33%   |
| IvyBridge       | 146       | 7.65%   |
| SandyBridge     | 138       | 7.23%   |
| Skylake         | 106       | 5.56%   |
| Broadwell       | 74        | 3.88%   |
| Goldmont plus   | 71        | 3.72%   |
| Unknown         | 56        | 2.94%   |
| Zen 2           | 54        | 2.83%   |
| Goldmont        | 54        | 2.83%   |
| Westmere        | 51        | 2.67%   |
| Zen+            | 46        | 2.41%   |
| Zen             | 41        | 2.15%   |
| Bonnell         | 41        | 2.15%   |
| Penryn          | 40        | 2.1%    |
| Nehalem         | 37        | 1.94%   |
| Jaguar          | 34        | 1.78%   |
| Core            | 34        | 1.78%   |
| Puma            | 32        | 1.68%   |
| Piledriver      | 29        | 1.52%   |
| CometLake       | 29        | 1.52%   |
| Zen 3           | 27        | 1.42%   |
| Steamroller     | 24        | 1.26%   |
| K10             | 18        | 0.94%   |
| Bobcat          | 17        | 0.89%   |
| NetBurst        | 13        | 0.68%   |
| TigerLake       | 11        | 0.58%   |
| Excavator       | 11        | 0.58%   |
| K8 Hammer       | 8         | 0.42%   |
| P6              | 4         | 0.21%   |
| K10 Llano       | 3         | 0.16%   |
| IceLake         | 3         | 0.16%   |
| Bulldozer       | 2         | 0.1%    |
| K8 & K10 hybrid | 1         | 0.05%   |
| Geode           | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1082      | 57.13%  |
| AMD                                          | 322       | 17%     |
| Nvidia                                       | 213       | 11.25%  |
| Matrox Electronics Systems                   | 139       | 7.34%   |
| ASPEED Technology                            | 133       | 7.02%   |
| XGI Technology (eXtreme Graphics Innovation) | 3         | 0.16%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 133       | 6.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 91        | 4.72%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 88        | 4.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 85        | 4.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 84        | 4.36%   |
| Intel HD Graphics 620                                                                    | 64        | 3.32%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 63        | 3.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 57        | 2.96%   |
| Intel HD Graphics 530                                                                    | 51        | 2.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 41        | 2.13%   |
| Intel UHD Graphics 620                                                                   | 38        | 1.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 35        | 1.82%   |
| Intel HD Graphics 500                                                                    | 34        | 1.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 34        | 1.77%   |
| Matrox Electronics Systems G200eR2                                                       | 32        | 1.66%   |
| Intel HD Graphics 5500                                                                   | 27        | 1.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 26        | 1.35%   |
| Intel HD Graphics 630                                                                    | 25        | 1.3%    |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 24        | 1.25%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 21        | 1.09%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 20        | 1.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 20        | 1.04%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 20        | 1.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 20        | 1.04%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 19        | 0.99%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 19        | 0.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 18        | 0.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 17        | 0.88%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 17        | 0.88%   |
| AMD Renoir                                                                               | 16        | 0.83%   |
| AMD Cezanne                                                                              | 15        | 0.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 0.73%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 14        | 0.73%   |
| AMD ES1000                                                                               | 14        | 0.73%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 13        | 0.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 0.67%   |
| Intel JasperLake [UHD Graphics]                                                          | 12        | 0.62%   |
| Intel HD Graphics 6000                                                                   | 12        | 0.62%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 11        | 0.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 966       | 50.71%  |
| 1 x AMD         | 290       | 15.22%  |
| 1 x Nvidia      | 148       | 7.77%   |
| 1 x Matrox      | 137       | 7.19%   |
| 1 x ASPEED      | 126       | 6.61%   |
| Other           | 94        | 4.93%   |
| Intel + Nvidia  | 50        | 2.62%   |
| 2 x Intel       | 48        | 2.52%   |
| Intel + AMD     | 14        | 0.73%   |
| AMD + Nvidia    | 9         | 0.47%   |
| 2 x AMD         | 7         | 0.37%   |
| 2 x Nvidia      | 3         | 0.16%   |
| 1 x XGI         | 3         | 0.16%   |
| Nvidia + ASPEED | 3         | 0.16%   |
| Intel + ASPEED  | 3         | 0.16%   |
| 1 x SiS         | 2         | 0.1%    |
| AMD + Matrox    | 1         | 0.05%   |
| AMD + ASPEED    | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1676      | 88.12%  |
| Unknown     | 115       | 6.05%   |
| Proprietary | 111       | 5.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1712      | 89.68%  |
| 1.01-2.0   | 53        | 2.78%   |
| 0.01-0.5   | 39        | 2.04%   |
| 3.01-4.0   | 33        | 1.73%   |
| 7.01-8.0   | 24        | 1.26%   |
| 0.51-1.0   | 24        | 1.26%   |
| 5.01-6.0   | 14        | 0.73%   |
| 8.01-16.0  | 5         | 0.26%   |
| 2.01-3.0   | 4         | 0.21%   |
| 4.01-5.0   | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 59        | 11.43%  |
| LG Display              | 59        | 11.43%  |
| AU Optronics            | 50        | 9.69%   |
| Dell                    | 46        | 8.91%   |
| BOE                     | 38        | 7.36%   |
| Goldstar                | 28        | 5.43%   |
| Chimei Innolux          | 27        | 5.23%   |
| Acer                    | 26        | 5.04%   |
| Lenovo                  | 25        | 4.84%   |
| Hewlett-Packard         | 20        | 3.88%   |
| Ancor Communications    | 19        | 3.68%   |
| Apple                   | 12        | 2.33%   |
| Vizio                   | 9         | 1.74%   |
| ASUSTek Computer        | 9         | 1.74%   |
| ViewSonic               | 8         | 1.55%   |
| Sharp                   | 8         | 1.55%   |
| Sceptre Tech            | 8         | 1.55%   |
| AOC                     | 8         | 1.55%   |
| LG Electronics          | 7         | 1.36%   |
| Chi Mei Optoelectronics | 7         | 1.36%   |
| BenQ                    | 5         | 0.97%   |
| Sony                    | 3         | 0.58%   |
| LGD                     | 3         | 0.58%   |
| InfoVision              | 3         | 0.58%   |
| HannStar                | 3         | 0.58%   |
| Westinghouse            | 2         | 0.39%   |
| Philips                 | 2         | 0.39%   |
| NEC Computers           | 2         | 0.39%   |
| Insignia                | 2         | 0.39%   |
| IBM                     | 2         | 0.39%   |
| unknown                 | 1         | 0.19%   |
| Toshiba                 | 1         | 0.19%   |
| Tech Concepts           | 1         | 0.19%   |
| SHI                     | 1         | 0.19%   |
| PANDA                   | 1         | 0.19%   |
| Panasonic               | 1         | 0.19%   |
| LG Philips              | 1         | 0.19%   |
| Lenovo Group Limited    | 1         | 0.19%   |
| HJW                     | 1         | 0.19%   |
| Hitachi                 | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 6         | 1.13%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                    | 6         | 1.13%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch              | 5         | 0.94%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch           | 4         | 0.75%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch     | 3         | 0.57%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 3         | 0.57%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                    | 3         | 0.57%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 3         | 0.57%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                  | 3         | 0.57%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 3         | 0.57%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 3         | 0.57%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                        | 3         | 0.57%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                        | 3         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 3         | 0.57%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch             | 3         | 0.57%   |
| Acer V246HL ACR032E 1920x1080 530x300mm 24.0-inch                        | 3         | 0.57%   |
| Sony TV SNY9C01 1360x768                                                 | 2         | 0.38%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 820x350mm 35.1-inch           | 2         | 0.38%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch        | 2         | 0.38%   |
| Samsung Electronics S27C750 SAM0A60 1920x1080 600x340mm 27.2-inch        | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch     | 2         | 0.38%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 2         | 0.38%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 2         | 0.38%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch             | 2         | 0.38%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x170mm 13.9-inch             | 2         | 0.38%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch              | 2         | 0.38%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch              | 2         | 0.38%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch                  | 2         | 0.38%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                    | 2         | 0.38%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch         | 2         | 0.38%   |
| Goldstar W2246 GSM5784 1920x1080 480x270mm 21.7-inch                     | 2         | 0.38%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2         | 0.38%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch               | 2         | 0.38%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.38%   |
| Dell S2716DG DELA0D1 2560x1440 600x340mm 27.2-inch                       | 2         | 0.38%   |
| Dell S2418HN/NX DEL4123 1920x1080 530x300mm 24.0-inch                    | 2         | 0.38%   |
| Dell E196FP DELA015 1280x1024 380x300mm 19.1-inch                        | 2         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 2         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 340x190mm 15.3-inch | 2         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 165       | 32.54%  |
| 1366x768 (WXGA)    | 102       | 20.12%  |
| 2560x1440 (QHD)    | 36        | 7.1%    |
| 3840x2160 (4K)     | 35        | 6.9%    |
| 1600x900 (HD+)     | 29        | 5.72%   |
| 1280x800 (WXGA)    | 19        | 3.75%   |
| 1280x1024 (SXGA)   | 17        | 3.35%   |
| 1920x1200 (WUXGA)  | 15        | 2.96%   |
| 1680x1050 (WSXGA+) | 15        | 2.96%   |
| 1440x900 (WXGA+)   | 10        | 1.97%   |
| 3440x1440          | 9         | 1.78%   |
| 2560x1080          | 9         | 1.78%   |
| 1360x768           | 8         | 1.58%   |
| 2256x1504          | 6         | 1.18%   |
| 2560x1600          | 5         | 0.99%   |
| 1024x600           | 5         | 0.99%   |
| 1024x768 (XGA)     | 4         | 0.79%   |
| Unknown            | 4         | 0.79%   |
| 3840x1600          | 2         | 0.39%   |
| 3200x1800 (QHD+)   | 2         | 0.39%   |
| 5760x2160          | 1         | 0.2%    |
| 5760x1080          | 1         | 0.2%    |
| 4480x1080          | 1         | 0.2%    |
| 3840x1080          | 1         | 0.2%    |
| 2880x1620          | 1         | 0.2%    |
| 2806x900           | 1         | 0.2%    |
| 1920x540           | 1         | 0.2%    |
| 1920x1920          | 1         | 0.2%    |
| 1600x1200          | 1         | 0.2%    |
| 1400x1050          | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 99        | 19.22%  |
| 13      | 84        | 16.31%  |
| 24      | 48        | 9.32%   |
| 27      | 42        | 8.16%   |
| Unknown | 28        | 5.44%   |
| 17      | 24        | 4.66%   |
| 12      | 24        | 4.66%   |
| 23      | 21        | 4.08%   |
| 19      | 21        | 4.08%   |
| 31      | 20        | 3.88%   |
| 21      | 18        | 3.5%    |
| 14      | 15        | 2.91%   |
| 11      | 13        | 2.52%   |
| 34      | 10        | 1.94%   |
| 22      | 8         | 1.55%   |
| 29      | 7         | 1.36%   |
| 64      | 4         | 0.78%   |
| 20      | 4         | 0.78%   |
| 18      | 4         | 0.78%   |
| 26      | 3         | 0.58%   |
| 37      | 2         | 0.39%   |
| 35      | 2         | 0.39%   |
| 10      | 2         | 0.39%   |
| 9       | 2         | 0.39%   |
| 54      | 1         | 0.19%   |
| 52      | 1         | 0.19%   |
| 49      | 1         | 0.19%   |
| 42      | 1         | 0.19%   |
| 41      | 1         | 0.19%   |
| 39      | 1         | 0.19%   |
| 32      | 1         | 0.19%   |
| 25      | 1         | 0.19%   |
| 16      | 1         | 0.19%   |
| 8       | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 164       | 32.54%  |
| 501-600     | 102       | 20.24%  |
| 201-300     | 82        | 16.27%  |
| 401-500     | 48        | 9.52%   |
| 601-700     | 32        | 6.35%   |
| Unknown     | 28        | 5.56%   |
| 351-400     | 20        | 3.97%   |
| 701-800     | 11        | 2.18%   |
| 1001-1500   | 7         | 1.39%   |
| 801-900     | 5         | 0.99%   |
| 101-200     | 3         | 0.6%    |
| 901-1000    | 2         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 346       | 72.08%  |
| 16/10   | 58        | 12.08%  |
| Unknown | 24        | 5%      |
| 21/9    | 18        | 3.75%   |
| 5/4     | 14        | 2.92%   |
| 3/2     | 9         | 1.88%   |
| 4/3     | 7         | 1.46%   |
| 6/5     | 2         | 0.42%   |
| 32/9    | 1         | 0.21%   |
| 1.00    | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 83        | 16.18%  |
| 201-250        | 77        | 15.01%  |
| 91-100         | 77        | 15.01%  |
| 301-350        | 47        | 9.16%   |
| 351-500        | 36        | 7.02%   |
| Unknown        | 28        | 5.46%   |
| 61-70          | 25        | 4.87%   |
| 151-200        | 25        | 4.87%   |
| 101-110        | 24        | 4.68%   |
| 251-300        | 18        | 3.51%   |
| 141-150        | 14        | 2.73%   |
| 121-130        | 13        | 2.53%   |
| 71-80          | 12        | 2.34%   |
| 51-60          | 12        | 2.34%   |
| More than 1000 | 6         | 1.17%   |
| 501-1000       | 6         | 1.17%   |
| 1-40           | 3         | 0.58%   |
| 111-120        | 3         | 0.58%   |
| 41-50          | 2         | 0.39%   |
| 131-140        | 2         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 159       | 31.99%  |
| 121-160       | 132       | 26.56%  |
| 101-120       | 129       | 25.96%  |
| 161-240       | 37        | 7.44%   |
| Unknown       | 28        | 5.63%   |
| More than 240 | 9         | 1.81%   |
| 1-50          | 3         | 0.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1421      | 74.55%  |
| 1     | 424       | 22.25%  |
| 2     | 54        | 2.83%   |
| 3     | 6         | 0.31%   |
| 4     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1495      | 56.63%  |
| Realtek Semiconductor            | 580       | 21.97%  |
| Broadcom                         | 202       | 7.65%   |
| Qualcomm Atheros                 | 127       | 4.81%   |
| Mellanox Technologies            | 29        | 1.1%    |
| Ralink Technology                | 23        | 0.87%   |
| Chelsio Communications           | 21        | 0.8%    |
| AMD                              | 14        | 0.53%   |
| Ralink                           | 11        | 0.42%   |
| Marvell Technology Group         | 11        | 0.42%   |
| IMC Networks                     | 11        | 0.42%   |
| Edimax Technology                | 10        | 0.38%   |
| TP-Link                          | 8         | 0.3%    |
| Solarflare Communications        | 6         | 0.23%   |
| U-Blox                           | 5         | 0.19%   |
| Nvidia                           | 5         | 0.19%   |
| Novatel Wireless                 | 5         | 0.19%   |
| NetGear                          | 5         | 0.19%   |
| Aquantia                         | 5         | 0.19%   |
| QLogic                           | 4         | 0.15%   |
| MediaTek                         | 4         | 0.15%   |
| Emulex                           | 4         | 0.15%   |
| D-Link System                    | 4         | 0.15%   |
| Apple                            | 4         | 0.15%   |
| Seeed Technology                 | 3         | 0.11%   |
| Cisco Systems                    | 3         | 0.11%   |
| VIA Technologies                 | 2         | 0.08%   |
| Qualcomm Atheros Communications  | 2         | 0.08%   |
| Google                           | 2         | 0.08%   |
| Dell                             | 2         | 0.08%   |
| ASUSTek Computer                 | 2         | 0.08%   |
| American Megatrends              | 2         | 0.08%   |
| Accton Technology                | 2         | 0.08%   |
| 3Com                             | 2         | 0.08%   |
| ZyXEL Communications             | 1         | 0.04%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.04%   |
| Xiaomi                           | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Silicom                          | 1         | 0.04%   |
| Sierra Wireless                  | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 456       | 13.56%  |
| Intel I211 Gigabit Network Connection                                         | 234       | 6.96%   |
| Intel I210 Gigabit Network Connection                                         | 183       | 5.44%   |
| Intel I350 Gigabit Network Connection                                         | 134       | 3.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 131       | 3.9%    |
| Intel 82574L Gigabit Network Connection                                       | 105       | 3.12%   |
| Intel Ethernet Connection I217-LM                                             | 80        | 2.38%   |
| Intel 82580 Gigabit Network Connection                                        | 66        | 1.96%   |
| Intel 82583V Gigabit Network Connection                                       | 64        | 1.9%    |
| Intel Wi-Fi 6 AX200                                                           | 56        | 1.67%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 55        | 1.64%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 53        | 1.58%   |
| Intel 82576 Gigabit Network Connection                                        | 53        | 1.58%   |
| Realtek RTL8125 2.5GbE Controller                                             | 42        | 1.25%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 40        | 1.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 39        | 1.16%   |
| Intel Ethernet Controller I225-V                                              | 39        | 1.16%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 37        | 1.1%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 34        | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                                         | 32        | 0.95%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 32        | 0.95%   |
| Intel Wireless 7260                                                           | 30        | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 30        | 0.89%   |
| Intel Wireless 8265 / 8275                                                    | 28        | 0.83%   |
| Intel Wireless 8260                                                           | 27        | 0.8%    |
| Intel Wireless 7265                                                           | 26        | 0.77%   |
| Intel Wireless 3165                                                           | 25        | 0.74%   |
| Intel Ethernet Connection I354                                                | 25        | 0.74%   |
| Intel Ethernet Connection (2) I219-V                                          | 25        | 0.74%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 21        | 0.62%   |
| Intel Wireless-AC 9260                                                        | 20        | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 19        | 0.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 19        | 0.57%   |
| Intel 82579V Gigabit Network Connection                                       | 18        | 0.54%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 16        | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                                         | 16        | 0.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 16        | 0.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 15        | 0.45%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 14        | 0.42%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 14        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 380       | 52.92%  |
| Qualcomm Atheros                | 109       | 15.18%  |
| Realtek Semiconductor           | 88        | 12.26%  |
| Broadcom                        | 58        | 8.08%   |
| Ralink Technology               | 23        | 3.2%    |
| Ralink                          | 11        | 1.53%   |
| IMC Networks                    | 11        | 1.53%   |
| Edimax Technology               | 10        | 1.39%   |
| TP-Link                         | 8         | 1.11%   |
| NetGear                         | 5         | 0.7%    |
| MediaTek                        | 3         | 0.42%   |
| Qualcomm Atheros Communications | 2         | 0.28%   |
| ASUSTek Computer                | 2         | 0.28%   |
| ZyXEL Communications            | 1         | 0.14%   |
| Sierra Wireless                 | 1         | 0.14%   |
| Marvell Technology Group        | 1         | 0.14%   |
| Linksys                         | 1         | 0.14%   |
| D-Link System                   | 1         | 0.14%   |
| D-Link                          | 1         | 0.14%   |
| Belkin Components               | 1         | 0.14%   |
| AboCom Systems                  | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 56        | 7.76%   |
| Intel Wireless 7260                                                     | 30        | 4.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 30        | 4.16%   |
| Intel Wireless 8265 / 8275                                              | 28        | 3.88%   |
| Intel Wireless 8260                                                     | 27        | 3.74%   |
| Intel Wireless 7265                                                     | 26        | 3.6%    |
| Intel Wireless 3165                                                     | 25        | 3.46%   |
| Intel Wireless-AC 9260                                                  | 20        | 2.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 19        | 2.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 19        | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 16        | 2.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 15        | 2.08%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 14        | 1.94%   |
| Ralink RT5370 Wireless Adapter                                          | 13        | 1.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 1.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 12        | 1.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 11        | 1.52%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 11        | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 1.52%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 11        | 1.52%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 11        | 1.52%   |
| Intel Wireless 3160                                                     | 10        | 1.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 10        | 1.39%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 10        | 1.39%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 10        | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 1.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 0.97%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 7         | 0.97%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 7         | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.83%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 0.83%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 6         | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1322      | 61.4%   |
| Realtek Semiconductor            | 538       | 24.99%  |
| Broadcom                         | 167       | 7.76%   |
| Qualcomm Atheros                 | 26        | 1.21%   |
| Chelsio Communications           | 18        | 0.84%   |
| AMD                              | 14        | 0.65%   |
| Marvell Technology Group         | 10        | 0.46%   |
| Solarflare Communications        | 6         | 0.28%   |
| Nvidia                           | 5         | 0.23%   |
| Novatel Wireless                 | 5         | 0.23%   |
| Aquantia                         | 5         | 0.23%   |
| QLogic                           | 4         | 0.19%   |
| Emulex                           | 4         | 0.19%   |
| D-Link System                    | 3         | 0.14%   |
| Cisco Systems                    | 3         | 0.14%   |
| Apple                            | 3         | 0.14%   |
| VIA Technologies                 | 2         | 0.09%   |
| Google                           | 2         | 0.09%   |
| American Megatrends              | 2         | 0.09%   |
| 3Com                             | 2         | 0.09%   |
| Xiaomi                           | 1         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |
| Silicom                          | 1         | 0.05%   |
| Samsung Electronics              | 1         | 0.05%   |
| Qualcomm                         | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.05%   |
| National Semiconductor           | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |
| ICS Advent                       | 1         | 0.05%   |
| Amazon.com                       | 1         | 0.05%   |
| ADMtek                           | 1         | 0.05%   |
| Accton Technology                | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 456       | 17.77%  |
| Intel I211 Gigabit Network Connection                                         | 234       | 9.12%   |
| Intel I210 Gigabit Network Connection                                         | 183       | 7.13%   |
| Intel I350 Gigabit Network Connection                                         | 134       | 5.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 131       | 5.11%   |
| Intel 82574L Gigabit Network Connection                                       | 105       | 4.09%   |
| Intel Ethernet Connection I217-LM                                             | 80        | 3.12%   |
| Intel 82580 Gigabit Network Connection                                        | 66        | 2.57%   |
| Intel 82583V Gigabit Network Connection                                       | 64        | 2.49%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 55        | 2.14%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 53        | 2.07%   |
| Intel 82576 Gigabit Network Connection                                        | 53        | 2.07%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 40        | 1.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 39        | 1.52%   |
| Intel Ethernet Controller I225-V                                              | 39        | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                             | 38        | 1.48%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 37        | 1.44%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 34        | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                                         | 32        | 1.25%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 32        | 1.25%   |
| Intel Ethernet Connection I354                                                | 25        | 0.97%   |
| Intel Ethernet Connection (2) I219-V                                          | 25        | 0.97%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 21        | 0.82%   |
| Intel 82579V Gigabit Network Connection                                       | 18        | 0.7%    |
| Intel Ethernet Connection (7) I219-LM                                         | 16        | 0.62%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 14        | 0.55%   |
| Intel Ethernet Controller X550                                                | 13        | 0.51%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 13        | 0.51%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 13        | 0.51%   |
| Intel Ethernet Connection X553 1GbE                                           | 13        | 0.51%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 11        | 0.43%   |
| Intel Ethernet Connection (7) I219-V                                          | 11        | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 10        | 0.39%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 10        | 0.39%   |
| Intel Ethernet Connection (3) I218-LM                                         | 10        | 0.39%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 10        | 0.39%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 9         | 0.35%   |
| Intel Ethernet Connection I217-V                                              | 9         | 0.35%   |
| Intel Ethernet Connection (2) I218-V                                          | 9         | 0.35%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 9         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1813      | 70.96%  |
| WiFi     | 668       | 26.14%  |
| Unknown  | 55        | 2.15%   |
| Modem    | 19        | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1711      | 83.42%  |
| WiFi     | 331       | 16.14%  |
| Unknown  | 9         | 0.44%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 592       | 30.72%  |
| 4     | 319       | 16.55%  |
| 3     | 260       | 13.49%  |
| 1     | 258       | 13.39%  |
| 6     | 210       | 10.9%   |
| 5     | 138       | 7.16%   |
| 8     | 46        | 2.39%   |
| 7     | 36        | 1.87%   |
| 0     | 22        | 1.14%   |
| 10    | 16        | 0.83%   |
| 9     | 13        | 0.67%   |
| 11    | 5         | 0.26%   |
| 14    | 3         | 0.16%   |
| 12    | 3         | 0.16%   |
| 16    | 2         | 0.1%    |
| 13    | 2         | 0.1%    |
| 20    | 1         | 0.05%   |
| 15    | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1616      | 82.41%  |
| Yes  | 345       | 17.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 270       | 60.4%   |
| Broadcom                        | 38        | 8.5%    |
| Apple                           | 31        | 6.94%   |
| Realtek Semiconductor           | 28        | 6.26%   |
| Qualcomm Atheros Communications | 20        | 4.47%   |
| IMC Networks                    | 20        | 4.47%   |
| Cambridge Silicon Radio         | 9         | 2.01%   |
| Dell                            | 8         | 1.79%   |
| ASUSTek Computer                | 8         | 1.79%   |
| Lite-On Technology              | 5         | 1.12%   |
| Foxconn / Hon Hai               | 4         | 0.89%   |
| Alps Electric                   | 2         | 0.45%   |
| Realtek                         | 1         | 0.22%   |
| MediaTek                        | 1         | 0.22%   |
| Hewlett-Packard                 | 1         | 0.22%   |
| Dynex                           | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 112       | 25%     |
| Intel AX200 Bluetooth                                       | 50        | 11.16%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 34        | 7.59%   |
| Intel AX201 Bluetooth                                       | 21        | 4.69%   |
| Realtek  Bluetooth 4.2 Adapter                              | 17        | 3.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 17        | 3.79%   |
| Intel Wireless-AC 3168 Bluetooth                            | 17        | 3.79%   |
| Apple Bluetooth Host Controller                             | 16        | 3.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 13        | 2.9%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 9         | 2.01%   |
| Intel AX210 Bluetooth                                       | 9         | 2.01%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 9         | 2.01%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 9         | 2.01%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 7         | 1.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 7         | 1.56%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 6         | 1.34%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 5         | 1.12%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 4         | 0.89%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 4         | 0.89%   |
| IMC Networks Realtek Bluetooth Adapter                      | 4         | 0.89%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 4         | 0.89%   |
| Dell DW375 Bluetooth Module                                 | 4         | 0.89%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 4         | 0.89%   |
| Realtek  Bluetooth Adapter                                  | 3         | 0.67%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 3         | 0.67%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 0.45%   |
| Realtek  Bluetooth 4.0 Adapter                              | 2         | 0.45%   |
| Realtek Bluetooth Radio                                     | 2         | 0.45%   |
| Qualcomm Atheros  QCA61x4 Bluetooth 4.1                     | 2         | 0.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 0.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 2         | 0.45%   |
| Lite-On Bluetooth USB Module                                | 2         | 0.45%   |
| IMC Networks Wireless_Device                                | 2         | 0.45%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 2         | 0.45%   |
| IMC Networks Bluetooth module                               | 2         | 0.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 0.45%   |
| Broadcom Broadcom 20702 Bluetooth 4.0 Adapter               | 2         | 0.45%   |
| ASUS Bluetooth USB module                                   | 2         | 0.45%   |
| ASUS Bluetooth Controller                                   | 2         | 0.45%   |
| ASUS ASUS USB-BT500                                         | 2         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1050      | 63.67%  |
| AMD                              | 350       | 21.22%  |
| Nvidia                           | 163       | 9.88%   |
| C-Media Electronics              | 24        | 1.46%   |
| Creative Labs                    | 12        | 0.73%   |
| SteelSeries ApS                  | 6         | 0.36%   |
| Blue Microphones                 | 5         | 0.3%    |
| Realtek Semiconductor            | 4         | 0.24%   |
| Logitech                         | 4         | 0.24%   |
| Texas Instruments                | 2         | 0.12%   |
| Silicon Integrated Systems [SiS] | 2         | 0.12%   |
| Lenovo                           | 2         | 0.12%   |
| Corsair                          | 2         | 0.12%   |
| Cambridge Silicon Radio          | 2         | 0.12%   |
| Yamaha                           | 1         | 0.06%   |
| XMOS                             | 1         | 0.06%   |
| VIA Technologies                 | 1         | 0.06%   |
| Tenx Technology                  | 1         | 0.06%   |
| Razer USA                        | 1         | 0.06%   |
| Quanta                           | 1         | 0.06%   |
| Nektar                           | 1         | 0.06%   |
| LG Electronics                   | 1         | 0.06%   |
| KORG                             | 1         | 0.06%   |
| Kingston Technology              | 1         | 0.06%   |
| JMTek                            | 1         | 0.06%   |
| Genesys Logic                    | 1         | 0.06%   |
| Focusrite-Novation               | 1         | 0.06%   |
| ESS Technology                   | 1         | 0.06%   |
| Creative Technology              | 1         | 0.06%   |
| CMX Systems                      | 1         | 0.06%   |
| Cirrus Logic                     | 1         | 0.06%   |
| ASUSTek Computer                 | 1         | 0.06%   |
| Astro Gaming                     | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |
| AKAI  Professional M.I.          | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 118       | 5.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 110       | 5.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 96        | 4.77%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 94        | 4.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 89        | 4.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 88        | 4.37%   |
| AMD FCH Azalia Controller                                                                         | 70        | 3.48%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 63        | 3.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 60        | 2.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 58        | 2.88%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 47        | 2.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 45        | 2.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 44        | 2.18%   |
| Intel Cannon Lake PCH cAVS                                                                        | 43        | 2.14%   |
| Intel Broadwell-U Audio Controller                                                                | 42        | 2.09%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 41        | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 40        | 1.99%   |
| AMD Kabini HDMI/DP Audio                                                                          | 39        | 1.94%   |
| Intel 200 Series PCH HD Audio                                                                     | 32        | 1.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 31        | 1.54%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 30        | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 29        | 1.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 27        | 1.34%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 26        | 1.29%   |
| Intel 8 Series HD Audio Controller                                                                | 26        | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 24        | 1.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 23        | 1.14%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 23        | 1.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 21        | 1.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 17        | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 15        | 0.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 15        | 0.74%   |
| Intel Comet Lake PCH cAVS                                                                         | 13        | 0.65%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 13        | 0.65%   |
| Intel Jasper Lake HD Audio                                                                        | 12        | 0.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 0.6%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 12        | 0.6%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 11        | 0.55%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 11        | 0.55%   |
| AMD Wrestler HDMI Audio                                                                           | 11        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 386       | 19.24%  |
| SK hynix                     | 318       | 15.85%  |
| Crucial                      | 211       | 10.52%  |
| Micron Technology            | 196       | 9.77%   |
| Unknown                      | 193       | 9.62%   |
| Kingston                     | 187       | 9.32%   |
| G.Skill                      | 96        | 4.79%   |
| Corsair                      | 82        | 4.09%   |
| Unknown                      | 38        | 1.89%   |
| Unknown (ABCD)               | 31        | 1.55%   |
| Transcend                    | 28        | 1.4%    |
| Nanya Technology             | 24        | 1.2%    |
| Team                         | 22        | 1.1%    |
| Patriot                      | 21        | 1.05%   |
| Ramaxel Technology           | 20        | 1%      |
| A-DATA Technology            | 20        | 1%      |
| PNY                          | 18        | 0.9%    |
| Elpida                       | 14        | 0.7%    |
| Toshiba                      | 11        | 0.55%   |
| Super Talent                 | 9         | 0.45%   |
| Kimtigo                      | 9         | 0.45%   |
| Timetec                      | 6         | 0.3%    |
| Silicon Power                | 5         | 0.25%   |
| Innodisk                     | 4         | 0.2%    |
| Avant                        | 4         | 0.2%    |
| Sesame                       | 3         | 0.15%   |
| Neo Forza                    | 3         | 0.15%   |
| Goldkey                      | 3         | 0.15%   |
| GeIL                         | 3         | 0.15%   |
| Apacer                       | 3         | 0.15%   |
| Qimonda                      | 2         | 0.1%    |
| Patriot Memory (PDP Systems) | 2         | 0.1%    |
| HPE                          | 2         | 0.1%    |
| Hewlett-Packard              | 2         | 0.1%    |
| GSkill                       | 2         | 0.1%    |
| Golden Empire                | 2         | 0.1%    |
| Unknown (0B38)               | 1         | 0.05%   |
| Unknown (000000000C01)       | 1         | 0.05%   |
| Unigen                       | 1         | 0.05%   |
| Unifosa                      | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 38        | 1.76%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 28        | 1.3%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 22        | 1.02%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 14        | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 14        | 0.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 14        | 0.65%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 13        | 0.6%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 11        | 0.51%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 11        | 0.51%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s               | 11        | 0.51%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 11        | 0.51%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 11        | 0.51%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 10        | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 10        | 0.46%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 10        | 0.46%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 10        | 0.46%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s              | 10        | 0.46%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s             | 10        | 0.46%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s              | 9         | 0.42%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s               | 9         | 0.42%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s             | 8         | 0.37%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 8         | 0.37%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s             | 8         | 0.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 8         | 0.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s             | 8         | 0.37%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s               | 8         | 0.37%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s             | 8         | 0.37%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s             | 8         | 0.37%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 7         | 0.32%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 7         | 0.32%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 7         | 0.32%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 7         | 0.32%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s            | 7         | 0.32%   |
| Samsung RAM M391B5273DH0-CK0 4GB DIMM DDR3 1600MT/s               | 7         | 0.32%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s              | 7         | 0.32%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s              | 6         | 0.28%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 6         | 0.28%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 6         | 0.28%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 6         | 0.28%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 6         | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 917       | 52.28%  |
| DDR4    | 642       | 36.6%   |
| DDR2    | 75        | 4.28%   |
| Unknown | 42        | 2.39%   |
| LPDDR4  | 35        | 2%      |
| DDR     | 15        | 0.86%   |
| LPDDR3  | 13        | 0.74%   |
| SDRAM   | 11        | 0.63%   |
| DRAM    | 2         | 0.11%   |
| SRAM    | 1         | 0.06%   |
| LPDDR5  | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 1012      | 57.76%  |
| SODIMM       | 676       | 38.58%  |
| Unknown      | 29        | 1.66%   |
| Row Of Chips | 16        | 0.91%   |
| Chip         | 9         | 0.51%   |
| FB-DIMM      | 7         | 0.4%    |
| RIMM         | 3         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 713       | 37.74%  |
| 4096  | 614       | 32.5%   |
| 16384 | 262       | 13.87%  |
| 2048  | 201       | 10.64%  |
| 32768 | 52        | 2.75%   |
| 1024  | 40        | 2.12%   |
| 512   | 4         | 0.21%   |
| 65536 | 2         | 0.11%   |
| 256   | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 617       | 32.78%  |
| 1333    | 261       | 13.87%  |
| 2400    | 227       | 12.06%  |
| 2133    | 159       | 8.45%   |
| 2667    | 145       | 7.7%    |
| 3200    | 110       | 5.84%   |
| 800     | 55        | 2.92%   |
| 667     | 48        | 2.55%   |
| 2666    | 42        | 2.23%   |
| 1334    | 33        | 1.75%   |
| 1066    | 28        | 1.49%   |
| 1867    | 25        | 1.33%   |
| 1067    | 25        | 1.33%   |
| Unknown | 21        | 1.12%   |
| 3600    | 16        | 0.85%   |
| 3000    | 15        | 0.8%    |
| 2933    | 12        | 0.64%   |
| 533     | 10        | 0.53%   |
| 1866    | 8         | 0.43%   |
| 975     | 4         | 0.21%   |
| 4267    | 3         | 0.16%   |
| 400     | 3         | 0.16%   |
| 1400    | 2         | 0.11%   |
| 1200    | 2         | 0.11%   |
| 6400    | 1         | 0.05%   |
| 4800    | 1         | 0.05%   |
| 4266    | 1         | 0.05%   |
| 4133    | 1         | 0.05%   |
| 3534    | 1         | 0.05%   |
| 3333    | 1         | 0.05%   |
| 2800    | 1         | 0.05%   |
| 2134    | 1         | 0.05%   |
| 1639    | 1         | 0.05%   |
| 200     | 1         | 0.05%   |
| 166     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 2         | 33.33%  |
| Prolific Technology   | 1         | 16.67%  |
| Lexmark International | 1         | 16.67%  |
| Brother Industries    | 1         | 16.67%  |
| Apple                 | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                            | 1         | 14.29%  |
| Lexmark International Lexmark MS710 Print                                | 1         | 14.29%  |
| HP PNP Fax Null                                                          | 1         | 14.29%  |
| HP LaserJet 1012                                                         | 1         | 14.29%  |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer | 1         | 14.29%  |
| Brother MFC-J485DW                                                       | 1         | 14.29%  |
| Apple Gamesir-G3s 2.10                                                   | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP ScanJet 5300c/5370c | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 76        | 26.67%  |
| Acer                                   | 26        | 9.12%   |
| Microdia                               | 25        | 8.77%   |
| Realtek Semiconductor                  | 22        | 7.72%   |
| Logitech                               | 21        | 7.37%   |
| IMC Networks                           | 19        | 6.67%   |
| Sunplus Innovation Technology          | 16        | 5.61%   |
| Apple                                  | 11        | 3.86%   |
| Quanta                                 | 10        | 3.51%   |
| Suyin                                  | 9         | 3.16%   |
| Lite-On Technology                     | 7         | 2.46%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.46%   |
| Luxvisions Innotech Limited            | 6         | 2.11%   |
| Lenovo                                 | 4         | 1.4%    |
| Syntek                                 | 3         | 1.05%   |
| Importek                               | 3         | 1.05%   |
| WCM_USB                                | 2         | 0.7%    |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.7%    |
| Ricoh                                  | 2         | 0.7%    |
| Primax Electronics                     | 2         | 0.7%    |
| OmniVision Technologies                | 2         | 0.7%    |
| Alcor Micro                            | 2         | 0.7%    |
| Xiongmai                               | 1         | 0.35%   |
| Unknown                                | 1         | 0.35%   |
| Silicon Motion                         | 1         | 0.35%   |
| Intel                                  | 1         | 0.35%   |
| Generalplus Technology                 | 1         | 0.35%   |
| Arkmicro Technologies                  | 1         | 0.35%   |
| ARC International                      | 1         | 0.35%   |
| ALi                                    | 1         | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                      | 23        | 7.99%   |
| Acer Integrated Camera                         | 15        | 5.21%   |
| Realtek Integrated_Webcam_HD                   | 8         | 2.78%   |
| Chicony Lenovo Integrated Camera (0.3MP)       | 8         | 2.78%   |
| Microdia Integrated Webcam                     | 7         | 2.43%   |
| Logitech HD Pro Webcam C920                    | 7         | 2.43%   |
| Apple FaceTime HD Camera                       | 7         | 2.43%   |
| Sunplus Integrated_Webcam_HD                   | 6         | 2.08%   |
| Chicony Integrated Camera [ThinkPad]           | 6         | 2.08%   |
| Chicony Integrated Camera (1280x720@30)        | 6         | 2.08%   |
| Realtek Realtek USB2.0 PC Camera               | 5         | 1.74%   |
| Logitech Webcam C270                           | 5         | 1.74%   |
| Lite-On Integrated Camera                      | 5         | 1.74%   |
| IMC Networks USB2.0 HD UVC WebCam              | 5         | 1.74%   |
| IMC Networks Integrated Camera                 | 5         | 1.74%   |
| Microdia Webcam Vitade AF                      | 4         | 1.39%   |
| Microdia Dell Laptop Integrated Webcam HD      | 4         | 1.39%   |
| Suyin Integrated_Webcam_HD                     | 3         | 1.04%   |
| Sunplus Laptop_Integrated_Webcam_FHD           | 3         | 1.04%   |
| Sunplus HD WebCam                              | 3         | 1.04%   |
| Quanta HP Webcam                               | 3         | 1.04%   |
| Quanta HP TrueVision HD Camera                 | 3         | 1.04%   |
| Logitech C922 Pro Stream Webcam                | 3         | 1.04%   |
| Lenovo Integrated Webcam [R5U877]              | 3         | 1.04%   |
| IMC Networks UVC VGA Webcam                    | 3         | 1.04%   |
| Chicony HD Webcam                              | 3         | 1.04%   |
| Chicony Chicony USB2.0 Camera                  | 3         | 1.04%   |
| Apple FaceTime HD Camera (Built-in)            | 3         | 1.04%   |
| Acer ThinkPad Integrated Camera                | 3         | 1.04%   |
| Acer Lenovo EasyCamera                         | 3         | 1.04%   |
| WCM_USB WEB CAM                                | 2         | 0.69%   |
| Syntek Lenovo EasyCamera                       | 2         | 0.69%   |
| Suyin Acer CrystalEye Webcam                   | 2         | 0.69%   |
| Sunplus Dell E5570 integrated webcam           | 2         | 0.69%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 2         | 0.69%   |
| Realtek Laptop Camera                          | 2         | 0.69%   |
| Realtek Integrated Webcam                      | 2         | 0.69%   |
| Quanta Realtek DMFT - RGB                      | 2         | 0.69%   |
| Primax HP HD Webcam [Fixed]                    | 2         | 0.69%   |
| OmniVision OV2640 Webcam                       | 2         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 25        | 35.21%  |
| Synaptics                  | 13        | 18.31%  |
| Upek                       | 10        | 14.08%  |
| STMicroelectronics         | 10        | 14.08%  |
| Shenzhen Goodix Technology | 5         | 7.04%   |
| AuthenTec                  | 4         | 5.63%   |
| Samsung Electronics        | 1         | 1.41%   |
| Focal-systems.Corp         | 1         | 1.41%   |
| Elan Microelectronics      | 1         | 1.41%   |
| Broadcom                   | 1         | 1.41%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 12        | 16.9%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 10        | 14.08%  |
| STMicroelectronics Fingerprint Reader                                        | 10        | 14.08%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 5         | 7.04%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 5         | 7.04%   |
| Shenzhen Goodix Fingerprint Reader                                           | 5         | 7.04%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 4.23%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 4.23%   |
| Validity Sensors Synaptics WBDI                                              | 2         | 2.82%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 2         | 2.82%   |
| Unknown                                                                      | 2         | 2.82%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 1.41%   |
| Validity Sensors VFS491                                                      | 1         | 1.41%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 1.41%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 1.41%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 1.41%   |
| Synaptics product 0x00be                                                     | 1         | 1.41%   |
| Samsung Fingerprint Sensor Device - 730B                                     | 1         | 1.41%   |
| Focal-systems.Corp FocalTech Fingerprint reader                              | 1         | 1.41%   |
| Elan ELAN WBF Fingerprint Sensor                                             | 1         | 1.41%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 1.41%   |
| AuthenTec AES2810                                                            | 1         | 1.41%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 1.41%   |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 722       | 36.84%  |
| 0     | 632       | 32.24%  |
| 2     | 392       | 20%     |
| 3     | 150       | 7.65%   |
| 4     | 47        | 2.4%    |
| 5     | 11        | 0.56%   |
| 6     | 5         | 0.26%   |
| 7     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1084      | 58.53%  |
| Net/wireless             | 194       | 10.48%  |
| Bluetooth                | 181       | 9.77%   |
| Card reader              | 112       | 6.05%   |
| Firewire controller      | 79        | 4.27%   |
| Fingerprint reader       | 60        | 3.24%   |
| Net/ethernet             | 37        | 2%      |
| Sound                    | 34        | 1.84%   |
| Network                  | 29        | 1.57%   |
| Graphics card            | 18        | 0.97%   |
| Storage                  | 8         | 0.43%   |
| Modem                    | 6         | 0.32%   |
| Storage/raid             | 3         | 0.16%   |
| Dvb card                 | 3         | 0.16%   |
| Storage/ide              | 2         | 0.11%   |
| Storage/ata              | 2         | 0.11%   |

