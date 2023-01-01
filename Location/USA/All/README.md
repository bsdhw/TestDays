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

Total: 3596

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | 04415J A00                  | Mini pc     | [3737d80840](https://bsd-hardware.info/?probe=3737d80840) | Dec 31, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [21e1293019](https://bsd-hardware.info/?probe=21e1293019) | Dec 31, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [0bf1c2abef](https://bsd-hardware.info/?probe=0bf1c2abef) | Dec 31, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [c6c6858ef0](https://bsd-hardware.info/?probe=c6c6858ef0) | Dec 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [68a847f5c2](https://bsd-hardware.info/?probe=68a847f5c2) | Dec 31, 2022 |
| GoWin Solu... | R86S                        | Desktop     | [4243d313a1](https://bsd-hardware.info/?probe=4243d313a1) | Dec 31, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [c791e3e3fd](https://bsd-hardware.info/?probe=c791e3e3fd) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [4d9a4bfc40](https://bsd-hardware.info/?probe=4d9a4bfc40) | Dec 30, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [d4460f8031](https://bsd-hardware.info/?probe=d4460f8031) | Dec 30, 2022 |
| Protectli     | FW6                         | Desktop     | [0d62222b7a](https://bsd-hardware.info/?probe=0d62222b7a) | Dec 30, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [46c3e7ffdd](https://bsd-hardware.info/?probe=46c3e7ffdd) | Dec 30, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [8b4c84d972](https://bsd-hardware.info/?probe=8b4c84d972) | Dec 30, 2022 |
| Dell          | 0GN4PW A00                  | Desktop     | [77e235d9f8](https://bsd-hardware.info/?probe=77e235d9f8) | Dec 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [1dab2c420a](https://bsd-hardware.info/?probe=1dab2c420a) | Dec 28, 2022 |
| Intel         | DENLOW_REFRESH_WS           | Desktop     | [4f86e686d2](https://bsd-hardware.info/?probe=4f86e686d2) | Dec 28, 2022 |
| Google        | Peppy                       | Notebook    | [e063619f03](https://bsd-hardware.info/?probe=e063619f03) | Dec 27, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [8cb1f1a8ea](https://bsd-hardware.info/?probe=8cb1f1a8ea) | Dec 27, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [d4296fd9d8](https://bsd-hardware.info/?probe=d4296fd9d8) | Dec 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [39bce6117f](https://bsd-hardware.info/?probe=39bce6117f) | Dec 26, 2022 |
| Dell          | 051FJ8 A01                  | Desktop     | [7f66a21d24](https://bsd-hardware.info/?probe=7f66a21d24) | Dec 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [e52abbf1b8](https://bsd-hardware.info/?probe=e52abbf1b8) | Dec 26, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [5f713b6061](https://bsd-hardware.info/?probe=5f713b6061) | Dec 26, 2022 |
| Protectli     | FW6                         | Desktop     | [90758fca97](https://bsd-hardware.info/?probe=90758fca97) | Dec 26, 2022 |
| Dell          | 0M877N A01                  | Server      | [340dc7255c](https://bsd-hardware.info/?probe=340dc7255c) | Dec 26, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [3fc9a4fd5c](https://bsd-hardware.info/?probe=3fc9a4fd5c) | Dec 26, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [bc829dbb1a](https://bsd-hardware.info/?probe=bc829dbb1a) | Dec 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [f73a37ab81](https://bsd-hardware.info/?probe=f73a37ab81) | Dec 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2e842ddb27](https://bsd-hardware.info/?probe=2e842ddb27) | Dec 25, 2022 |
| Cisco         | ASA5515 A0                  | Desktop     | [9e587b9499](https://bsd-hardware.info/?probe=9e587b9499) | Dec 25, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [1769da5143](https://bsd-hardware.info/?probe=1769da5143) | Dec 25, 2022 |
| HP            | 213D A01                    | Desktop     | [bd620f0fc0](https://bsd-hardware.info/?probe=bd620f0fc0) | Dec 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [bd212706ad](https://bsd-hardware.info/?probe=bd212706ad) | Dec 24, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [af60c7ce81](https://bsd-hardware.info/?probe=af60c7ce81) | Dec 24, 2022 |
| Supermicro    | X10SRH-CLN4FA               | Desktop     | [84c360ad02](https://bsd-hardware.info/?probe=84c360ad02) | Dec 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [153f99a846](https://bsd-hardware.info/?probe=153f99a846) | Dec 24, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [b29f2e4573](https://bsd-hardware.info/?probe=b29f2e4573) | Dec 24, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [701c6e95d6](https://bsd-hardware.info/?probe=701c6e95d6) | Dec 24, 2022 |
| Gigabyte      | Z390 AORUS ELITE            | Desktop     | [91b7417b84](https://bsd-hardware.info/?probe=91b7417b84) | Dec 24, 2022 |
| MSI           | A78M-E35                    | Desktop     | [03176e6683](https://bsd-hardware.info/?probe=03176e6683) | Dec 23, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [52327286e4](https://bsd-hardware.info/?probe=52327286e4) | Dec 23, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [0d70cc442b](https://bsd-hardware.info/?probe=0d70cc442b) | Dec 23, 2022 |
| Lenovo        | ThinkPad T480 20L6S13100    | Notebook    | [67daa912fa](https://bsd-hardware.info/?probe=67daa912fa) | Dec 23, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [e0b4e13386](https://bsd-hardware.info/?probe=e0b4e13386) | Dec 23, 2022 |
| Dell          | Vostro 1400                 | Notebook    | [087a3d269f](https://bsd-hardware.info/?probe=087a3d269f) | Dec 23, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [062fb4cccd](https://bsd-hardware.info/?probe=062fb4cccd) | Dec 23, 2022 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [527bf6bbe4](https://bsd-hardware.info/?probe=527bf6bbe4) | Dec 22, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [633b9a5425](https://bsd-hardware.info/?probe=633b9a5425) | Dec 22, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [df221cefbc](https://bsd-hardware.info/?probe=df221cefbc) | Dec 22, 2022 |
| Dell          | 0UW457 A03                  | Desktop     | [47b66a0d86](https://bsd-hardware.info/?probe=47b66a0d86) | Dec 21, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [16f59f69dc](https://bsd-hardware.info/?probe=16f59f69dc) | Dec 20, 2022 |
| Protectli     | FW2B Ver                    | Desktop     | [9596576df7](https://bsd-hardware.info/?probe=9596576df7) | Dec 20, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [31f17adc5b](https://bsd-hardware.info/?probe=31f17adc5b) | Dec 20, 2022 |
| Supermicro    | X10SDV-4C-TLN4F             | Server      | [c0c8d1f85e](https://bsd-hardware.info/?probe=c0c8d1f85e) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [4c5ccd04d0](https://bsd-hardware.info/?probe=4c5ccd04d0) | Dec 19, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b84941cdd5](https://bsd-hardware.info/?probe=b84941cdd5) | Dec 19, 2022 |
| Lenovo        | ThinkPad T530 2392AQU       | Notebook    | [9a3cbe1893](https://bsd-hardware.info/?probe=9a3cbe1893) | Dec 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [fad0a431e5](https://bsd-hardware.info/?probe=fad0a431e5) | Dec 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 744... | Notebook    | [ea686f63f5](https://bsd-hardware.info/?probe=ea686f63f5) | Dec 19, 2022 |
| Framework     | Laptop                      | Notebook    | [9dcd3592db](https://bsd-hardware.info/?probe=9dcd3592db) | Dec 19, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [b9df714117](https://bsd-hardware.info/?probe=b9df714117) | Dec 19, 2022 |
| Dell          | Edge Gateway 5000           | Mini pc     | [0af7422e2f](https://bsd-hardware.info/?probe=0af7422e2f) | Dec 18, 2022 |
| Dell          | Precision M4800             | Notebook    | [b7a834c4d0](https://bsd-hardware.info/?probe=b7a834c4d0) | Dec 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c1b0b83306](https://bsd-hardware.info/?probe=c1b0b83306) | Dec 18, 2022 |
| MSI           | H81M-P33                    | Desktop     | [78e4743abd](https://bsd-hardware.info/?probe=78e4743abd) | Dec 18, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [f232e5746e](https://bsd-hardware.info/?probe=f232e5746e) | Dec 18, 2022 |
| Supermicro    | X11SCL-F                    | Server      | [638b27bc34](https://bsd-hardware.info/?probe=638b27bc34) | Dec 18, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [a40ada7f7f](https://bsd-hardware.info/?probe=a40ada7f7f) | Dec 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [f6fababc22](https://bsd-hardware.info/?probe=f6fababc22) | Dec 18, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e06fa5d522](https://bsd-hardware.info/?probe=e06fa5d522) | Dec 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a1b29c356e](https://bsd-hardware.info/?probe=a1b29c356e) | Dec 17, 2022 |
| Protectli     | FW6                         | Desktop     | [56f62226e7](https://bsd-hardware.info/?probe=56f62226e7) | Dec 17, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [088766f04d](https://bsd-hardware.info/?probe=088766f04d) | Dec 17, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [f6085ba691](https://bsd-hardware.info/?probe=f6085ba691) | Dec 17, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [afef2952f9](https://bsd-hardware.info/?probe=afef2952f9) | Dec 17, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [b7e599f99d](https://bsd-hardware.info/?probe=b7e599f99d) | Dec 17, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [0da9ef9752](https://bsd-hardware.info/?probe=0da9ef9752) | Dec 17, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [2fe9b1b8c9](https://bsd-hardware.info/?probe=2fe9b1b8c9) | Dec 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [a94bfdaa5c](https://bsd-hardware.info/?probe=a94bfdaa5c) | Dec 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [6bf18dfe5a](https://bsd-hardware.info/?probe=6bf18dfe5a) | Dec 16, 2022 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [cc51093e02](https://bsd-hardware.info/?probe=cc51093e02) | Dec 16, 2022 |
| HP            | 2215                        | Desktop     | [76f607b100](https://bsd-hardware.info/?probe=76f607b100) | Dec 14, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [a77d60297f](https://bsd-hardware.info/?probe=a77d60297f) | Dec 14, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [6ebcd7c974](https://bsd-hardware.info/?probe=6ebcd7c974) | Dec 14, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [bc15367e9f](https://bsd-hardware.info/?probe=bc15367e9f) | Dec 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [ad7f977515](https://bsd-hardware.info/?probe=ad7f977515) | Dec 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f52a3d3fa6](https://bsd-hardware.info/?probe=f52a3d3fa6) | Dec 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [abed96a938](https://bsd-hardware.info/?probe=abed96a938) | Dec 13, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [66e0c118d2](https://bsd-hardware.info/?probe=66e0c118d2) | Dec 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [128ce54404](https://bsd-hardware.info/?probe=128ce54404) | Dec 12, 2022 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [76519f54e9](https://bsd-hardware.info/?probe=76519f54e9) | Dec 12, 2022 |
| Gigabyte      | X99-Designare EX-CF         | Desktop     | [de5bf4b420](https://bsd-hardware.info/?probe=de5bf4b420) | Dec 12, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [2bf8839d12](https://bsd-hardware.info/?probe=2bf8839d12) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [809da57d90](https://bsd-hardware.info/?probe=809da57d90) | Dec 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [1f110891d0](https://bsd-hardware.info/?probe=1f110891d0) | Dec 11, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [028383847e](https://bsd-hardware.info/?probe=028383847e) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [99502ebe9a](https://bsd-hardware.info/?probe=99502ebe9a) | Dec 11, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [ad71b00b0d](https://bsd-hardware.info/?probe=ad71b00b0d) | Dec 11, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [4b14039072](https://bsd-hardware.info/?probe=4b14039072) | Dec 11, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [0939871923](https://bsd-hardware.info/?probe=0939871923) | Dec 11, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [808108016d](https://bsd-hardware.info/?probe=808108016d) | Dec 10, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [0b08951f1c](https://bsd-hardware.info/?probe=0b08951f1c) | Dec 10, 2022 |
| Dell          | 0DRG19 A00                  | Mini pc     | [bbca9fc84f](https://bsd-hardware.info/?probe=bbca9fc84f) | Dec 09, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [3f55143fd9](https://bsd-hardware.info/?probe=3f55143fd9) | Dec 09, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [6b03cb139e](https://bsd-hardware.info/?probe=6b03cb139e) | Dec 09, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [b2f0da8246](https://bsd-hardware.info/?probe=b2f0da8246) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [48d5feacf2](https://bsd-hardware.info/?probe=48d5feacf2) | Dec 08, 2022 |
| Protectli     | FW4C Ver                    | Desktop     | [71368e5cde](https://bsd-hardware.info/?probe=71368e5cde) | Dec 08, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [9862c1b507](https://bsd-hardware.info/?probe=9862c1b507) | Dec 07, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [6db81b5ffe](https://bsd-hardware.info/?probe=6db81b5ffe) | Dec 07, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [8ac499a511](https://bsd-hardware.info/?probe=8ac499a511) | Dec 07, 2022 |
| HP            | 1495                        | Desktop     | [3f033cb7f5](https://bsd-hardware.info/?probe=3f033cb7f5) | Dec 07, 2022 |
| Sophos        | XG                          | Firewall    | [b29a7eaa33](https://bsd-hardware.info/?probe=b29a7eaa33) | Dec 07, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [61347ab3e9](https://bsd-hardware.info/?probe=61347ab3e9) | Dec 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [e3dad11b11](https://bsd-hardware.info/?probe=e3dad11b11) | Dec 06, 2022 |
| DFI           | BE17X(170/171/173)          | Notebook    | [9822160345](https://bsd-hardware.info/?probe=9822160345) | Dec 05, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5441995e7b](https://bsd-hardware.info/?probe=5441995e7b) | Dec 05, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f130844e1e](https://bsd-hardware.info/?probe=f130844e1e) | Dec 05, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [05566134f9](https://bsd-hardware.info/?probe=05566134f9) | Dec 05, 2022 |
| Google        | Lick                        | Notebook    | [8099b2df21](https://bsd-hardware.info/?probe=8099b2df21) | Dec 04, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [54d1511b82](https://bsd-hardware.info/?probe=54d1511b82) | Dec 04, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d72a45fb8f](https://bsd-hardware.info/?probe=d72a45fb8f) | Dec 04, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [595d174631](https://bsd-hardware.info/?probe=595d174631) | Dec 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8ee41750dc](https://bsd-hardware.info/?probe=8ee41750dc) | Dec 04, 2022 |
| Sophos        | XG                          | Firewall    | [a51c56cb12](https://bsd-hardware.info/?probe=a51c56cb12) | Dec 04, 2022 |
| Google        | Lick                        | Notebook    | [9eb2abcdcc](https://bsd-hardware.info/?probe=9eb2abcdcc) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [aeb690b9f3](https://bsd-hardware.info/?probe=aeb690b9f3) | Dec 03, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [1916a4064b](https://bsd-hardware.info/?probe=1916a4064b) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [d4e60c5984](https://bsd-hardware.info/?probe=d4e60c5984) | Dec 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [90de1777bc](https://bsd-hardware.info/?probe=90de1777bc) | Dec 02, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [f8719b2320](https://bsd-hardware.info/?probe=f8719b2320) | Dec 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [5c3941eb3f](https://bsd-hardware.info/?probe=5c3941eb3f) | Dec 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d3b72fdce8](https://bsd-hardware.info/?probe=d3b72fdce8) | Dec 02, 2022 |
| Dell          | Latitude 5590               | Notebook    | [0a17f04eba](https://bsd-hardware.info/?probe=0a17f04eba) | Dec 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [243e309a04](https://bsd-hardware.info/?probe=243e309a04) | Dec 01, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [03708406e8](https://bsd-hardware.info/?probe=03708406e8) | Dec 01, 2022 |
| HP            | 8054                        | Desktop     | [c25adeb2ff](https://bsd-hardware.info/?probe=c25adeb2ff) | Dec 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [504a659236](https://bsd-hardware.info/?probe=504a659236) | Dec 01, 2022 |
| HP            | 8103 A01                    | Mini pc     | [5cd982c2ee](https://bsd-hardware.info/?probe=5cd982c2ee) | Nov 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [794e041b13](https://bsd-hardware.info/?probe=794e041b13) | Nov 30, 2022 |
| Protectli     | FW6                         | Desktop     | [95f3201109](https://bsd-hardware.info/?probe=95f3201109) | Nov 30, 2022 |
| Protectli     | FW4A Ver                    | Desktop     | [9e6e0f5548](https://bsd-hardware.info/?probe=9e6e0f5548) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7308d658dc](https://bsd-hardware.info/?probe=7308d658dc) | Nov 29, 2022 |
| HP            | 8299                        | Desktop     | [d697a2e953](https://bsd-hardware.info/?probe=d697a2e953) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS0XL23    | Notebook    | [bc7585ec56](https://bsd-hardware.info/?probe=bc7585ec56) | Nov 28, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b1f32ca8a1](https://bsd-hardware.info/?probe=b1f32ca8a1) | Nov 28, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [b4cc780c40](https://bsd-hardware.info/?probe=b4cc780c40) | Nov 28, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [fd111870fa](https://bsd-hardware.info/?probe=fd111870fa) | Nov 28, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [39ece5deaf](https://bsd-hardware.info/?probe=39ece5deaf) | Nov 27, 2022 |
| MSI           | H81M-P33                    | Desktop     | [597d48d1c9](https://bsd-hardware.info/?probe=597d48d1c9) | Nov 27, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [10d76fd431](https://bsd-hardware.info/?probe=10d76fd431) | Nov 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [383341b2f1](https://bsd-hardware.info/?probe=383341b2f1) | Nov 27, 2022 |
| HP            | 18E7                        | Desktop     | [c7635c715f](https://bsd-hardware.info/?probe=c7635c715f) | Nov 26, 2022 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [33c1878560](https://bsd-hardware.info/?probe=33c1878560) | Nov 26, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [2b00248458](https://bsd-hardware.info/?probe=2b00248458) | Nov 26, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [3acaad9a7d](https://bsd-hardware.info/?probe=3acaad9a7d) | Nov 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [6de307244e](https://bsd-hardware.info/?probe=6de307244e) | Nov 26, 2022 |
| Protectli     | FW2B Ver                    | Desktop     | [e03929e52f](https://bsd-hardware.info/?probe=e03929e52f) | Nov 25, 2022 |
| Supermicro    | M11SDV-8C+-LN4F             | Server      | [bcf17b19ec](https://bsd-hardware.info/?probe=bcf17b19ec) | Nov 25, 2022 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [dc8015adc3](https://bsd-hardware.info/?probe=dc8015adc3) | Nov 25, 2022 |
| Dell          | 0HFG24 A01                  | Server      | [ca48ff12d3](https://bsd-hardware.info/?probe=ca48ff12d3) | Nov 25, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [5740972ddc](https://bsd-hardware.info/?probe=5740972ddc) | Nov 25, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [de7f2ee053](https://bsd-hardware.info/?probe=de7f2ee053) | Nov 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [5aa1f0193a](https://bsd-hardware.info/?probe=5aa1f0193a) | Nov 24, 2022 |
| Dell          | 07F37C A01                  | Desktop     | [08d048da80](https://bsd-hardware.info/?probe=08d048da80) | Nov 24, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [1b6870d481](https://bsd-hardware.info/?probe=1b6870d481) | Nov 23, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [7fabc0cb8a](https://bsd-hardware.info/?probe=7fabc0cb8a) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [337d5f0f4b](https://bsd-hardware.info/?probe=337d5f0f4b) | Nov 23, 2022 |
| Protectli     | FW4B                        | Desktop     | [d3090c9e8e](https://bsd-hardware.info/?probe=d3090c9e8e) | Nov 23, 2022 |
| PC Engines    | APU2                        | Desktop     | [4d33b6da51](https://bsd-hardware.info/?probe=4d33b6da51) | Nov 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [d4791d1dfc](https://bsd-hardware.info/?probe=d4791d1dfc) | Nov 22, 2022 |
| Dell          | Edge Gateway 5000           | Mini pc     | [18f8f8f8b5](https://bsd-hardware.info/?probe=18f8f8f8b5) | Nov 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [fdffbdb940](https://bsd-hardware.info/?probe=fdffbdb940) | Nov 22, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [77fa42b66c](https://bsd-hardware.info/?probe=77fa42b66c) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [f7129f1c87](https://bsd-hardware.info/?probe=f7129f1c87) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [17aa370584](https://bsd-hardware.info/?probe=17aa370584) | Nov 21, 2022 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [2d8d0056c4](https://bsd-hardware.info/?probe=2d8d0056c4) | Nov 21, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [5030575f0a](https://bsd-hardware.info/?probe=5030575f0a) | Nov 20, 2022 |
| Dell          | 07F37C A01                  | Desktop     | [efb5c9d03d](https://bsd-hardware.info/?probe=efb5c9d03d) | Nov 20, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d3303d1962](https://bsd-hardware.info/?probe=d3303d1962) | Nov 20, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [b1512a254c](https://bsd-hardware.info/?probe=b1512a254c) | Nov 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [521e5ffa8e](https://bsd-hardware.info/?probe=521e5ffa8e) | Nov 20, 2022 |
| HP            | 8054                        | Desktop     | [2c1e20c9e7](https://bsd-hardware.info/?probe=2c1e20c9e7) | Nov 20, 2022 |
| Hardkernel    | ODROID-H3                   | Desktop     | [ec7611edd1](https://bsd-hardware.info/?probe=ec7611edd1) | Nov 20, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [c226ac3d9b](https://bsd-hardware.info/?probe=c226ac3d9b) | Nov 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [5d3ccb6891](https://bsd-hardware.info/?probe=5d3ccb6891) | Nov 20, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [449dcd1463](https://bsd-hardware.info/?probe=449dcd1463) | Nov 19, 2022 |
| Dell          | 09D2HH A00                  | Desktop     | [794fe8eb65](https://bsd-hardware.info/?probe=794fe8eb65) | Nov 19, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [bf83fc6cdb](https://bsd-hardware.info/?probe=bf83fc6cdb) | Nov 19, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [402a623ed0](https://bsd-hardware.info/?probe=402a623ed0) | Nov 19, 2022 |
| Foxconn       | H67S/H61SP                  | Desktop     | [80ad331089](https://bsd-hardware.info/?probe=80ad331089) | Nov 19, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [18062e5bd5](https://bsd-hardware.info/?probe=18062e5bd5) | Nov 19, 2022 |
| Dell          | 0GN4PW A00                  | Desktop     | [9127ec4dac](https://bsd-hardware.info/?probe=9127ec4dac) | Nov 19, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [2eba32390f](https://bsd-hardware.info/?probe=2eba32390f) | Nov 19, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [eaf4ec693e](https://bsd-hardware.info/?probe=eaf4ec693e) | Nov 19, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [f25480c54a](https://bsd-hardware.info/?probe=f25480c54a) | Nov 18, 2022 |
| HP            | 82FE 11                     | Desktop     | [547e5e3ce1](https://bsd-hardware.info/?probe=547e5e3ce1) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [f732942dd9](https://bsd-hardware.info/?probe=f732942dd9) | Nov 18, 2022 |
| Dell          | 051FJ8 A02                  | Desktop     | [296b446a8f](https://bsd-hardware.info/?probe=296b446a8f) | Nov 18, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [ddf3f8603a](https://bsd-hardware.info/?probe=ddf3f8603a) | Nov 17, 2022 |
| AAEON         | MF-001 V1.0                 | Desktop     | [d98d84f1a4](https://bsd-hardware.info/?probe=d98d84f1a4) | Nov 17, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [9cd1c1fc21](https://bsd-hardware.info/?probe=9cd1c1fc21) | Nov 17, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [15458aff84](https://bsd-hardware.info/?probe=15458aff84) | Nov 16, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [47f82850da](https://bsd-hardware.info/?probe=47f82850da) | Nov 16, 2022 |
| HP            | ProLiant DL120 Gen9         | Server      | [94513a53f8](https://bsd-hardware.info/?probe=94513a53f8) | Nov 16, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [94afb24fbc](https://bsd-hardware.info/?probe=94afb24fbc) | Nov 16, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5096994f99](https://bsd-hardware.info/?probe=5096994f99) | Nov 16, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [314916c885](https://bsd-hardware.info/?probe=314916c885) | Nov 15, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [dd637e0562](https://bsd-hardware.info/?probe=dd637e0562) | Nov 15, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [9e568eb5ee](https://bsd-hardware.info/?probe=9e568eb5ee) | Nov 14, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [74a717c2e6](https://bsd-hardware.info/?probe=74a717c2e6) | Nov 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6f1e732a53](https://bsd-hardware.info/?probe=6f1e732a53) | Nov 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [15e38a5ca8](https://bsd-hardware.info/?probe=15e38a5ca8) | Nov 13, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [2b1175a4df](https://bsd-hardware.info/?probe=2b1175a4df) | Nov 13, 2022 |
| MSI           | H81M-P33                    | Desktop     | [98b0980231](https://bsd-hardware.info/?probe=98b0980231) | Nov 13, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [80c0d775a7](https://bsd-hardware.info/?probe=80c0d775a7) | Nov 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [072f2a6c27](https://bsd-hardware.info/?probe=072f2a6c27) | Nov 13, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [5125bff15a](https://bsd-hardware.info/?probe=5125bff15a) | Nov 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [838256315e](https://bsd-hardware.info/?probe=838256315e) | Nov 13, 2022 |
| Dell          | Latitude E7240              | Notebook    | [ea99621380](https://bsd-hardware.info/?probe=ea99621380) | Nov 12, 2022 |
| HP            | 8169                        | Desktop     | [e80c8a40a5](https://bsd-hardware.info/?probe=e80c8a40a5) | Nov 12, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [75b586fdfc](https://bsd-hardware.info/?probe=75b586fdfc) | Nov 12, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [f1cd4bdbf3](https://bsd-hardware.info/?probe=f1cd4bdbf3) | Nov 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [817c69a4b0](https://bsd-hardware.info/?probe=817c69a4b0) | Nov 12, 2022 |
| MSI           | MS-9897                     | Desktop     | [2527ac44f4](https://bsd-hardware.info/?probe=2527ac44f4) | Nov 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [790e616e22](https://bsd-hardware.info/?probe=790e616e22) | Nov 12, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [b8ee0562af](https://bsd-hardware.info/?probe=b8ee0562af) | Nov 12, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [54dd33114e](https://bsd-hardware.info/?probe=54dd33114e) | Nov 12, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [23a0c08442](https://bsd-hardware.info/?probe=23a0c08442) | Nov 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [a2b2bb3a77](https://bsd-hardware.info/?probe=a2b2bb3a77) | Nov 11, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [515a9245ac](https://bsd-hardware.info/?probe=515a9245ac) | Nov 11, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [f12f8c8fb2](https://bsd-hardware.info/?probe=f12f8c8fb2) | Nov 11, 2022 |
| Supermicro    | X10SDV-TLN4F                | Server      | [2c96fe37f6](https://bsd-hardware.info/?probe=2c96fe37f6) | Nov 10, 2022 |
| ASRock        | J4005B-ITX                  | Desktop     | [554b92cae5](https://bsd-hardware.info/?probe=554b92cae5) | Nov 10, 2022 |
| Deciso        | Netboard A20                | Notebook    | [0320675a86](https://bsd-hardware.info/?probe=0320675a86) | Nov 10, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [1300135627](https://bsd-hardware.info/?probe=1300135627) | Nov 10, 2022 |
| Cisco         | C170 A0                     | Desktop     | [3ba579a78c](https://bsd-hardware.info/?probe=3ba579a78c) | Nov 10, 2022 |
| AZW           | GK55                        | Desktop     | [d73ef4f4fc](https://bsd-hardware.info/?probe=d73ef4f4fc) | Nov 10, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [4bb9a9324b](https://bsd-hardware.info/?probe=4bb9a9324b) | Nov 10, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [d75162607b](https://bsd-hardware.info/?probe=d75162607b) | Nov 09, 2022 |
| Intel         | JSL MRD                     | Desktop     | [5800246e28](https://bsd-hardware.info/?probe=5800246e28) | Nov 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [5807159f51](https://bsd-hardware.info/?probe=5807159f51) | Nov 08, 2022 |
| Google        | Zako                        | Desktop     | [5d4b53e2d4](https://bsd-hardware.info/?probe=5d4b53e2d4) | Nov 08, 2022 |
| Dell          | 081N4V A08                  | Server      | [6454631448](https://bsd-hardware.info/?probe=6454631448) | Nov 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [31ff384824](https://bsd-hardware.info/?probe=31ff384824) | Nov 07, 2022 |
| HP            | 8768 A                      | Desktop     | [c8a44e84c6](https://bsd-hardware.info/?probe=c8a44e84c6) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [70e257e360](https://bsd-hardware.info/?probe=70e257e360) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [fed7f55a01](https://bsd-hardware.info/?probe=fed7f55a01) | Nov 06, 2022 |
| HP            | 18E7                        | Desktop     | [6a80fc5241](https://bsd-hardware.info/?probe=6a80fc5241) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [59b8857bba](https://bsd-hardware.info/?probe=59b8857bba) | Nov 06, 2022 |
| MSI           | H81M-P33                    | Desktop     | [750d2f53c7](https://bsd-hardware.info/?probe=750d2f53c7) | Nov 06, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [e427ea787e](https://bsd-hardware.info/?probe=e427ea787e) | Nov 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c6abe84145](https://bsd-hardware.info/?probe=c6abe84145) | Nov 06, 2022 |
| Protectli     | FW6                         | Desktop     | [654e223853](https://bsd-hardware.info/?probe=654e223853) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [a33d1a4123](https://bsd-hardware.info/?probe=a33d1a4123) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [6fb650e2e8](https://bsd-hardware.info/?probe=6fb650e2e8) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [3771535d50](https://bsd-hardware.info/?probe=3771535d50) | Nov 06, 2022 |
| Dell          | OptiPlex 5050               | Desktop     | [cfd442a25d](https://bsd-hardware.info/?probe=cfd442a25d) | Nov 06, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [33eea3a422](https://bsd-hardware.info/?probe=33eea3a422) | Nov 05, 2022 |
| Sophos        | SG                          | Firewall    | [d80c273f85](https://bsd-hardware.info/?probe=d80c273f85) | Nov 05, 2022 |
| Protectli     | FW4C Ver                    | Desktop     | [71c0c846f1](https://bsd-hardware.info/?probe=71c0c846f1) | Nov 05, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [946c93ec7b](https://bsd-hardware.info/?probe=946c93ec7b) | Nov 05, 2022 |
| Dell          | 0KM5PX A01                  | Server      | [a1a15662d0](https://bsd-hardware.info/?probe=a1a15662d0) | Nov 04, 2022 |
| Dell          | 0KM5PX A01                  | Server      | [0ee82f0b87](https://bsd-hardware.info/?probe=0ee82f0b87) | Nov 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [4f58f89a6e](https://bsd-hardware.info/?probe=4f58f89a6e) | Nov 04, 2022 |
| HP            | 82A2                        | Desktop     | [d83974a5ed](https://bsd-hardware.info/?probe=d83974a5ed) | Nov 03, 2022 |
| HP            | 339A                        | Desktop     | [a1e829d9d9](https://bsd-hardware.info/?probe=a1e829d9d9) | Nov 03, 2022 |
| Sophos        | XG                          | Firewall    | [f2f91c4258](https://bsd-hardware.info/?probe=f2f91c4258) | Nov 03, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [8e0c8344af](https://bsd-hardware.info/?probe=8e0c8344af) | Nov 03, 2022 |
| Samsung       | 750TDA                      | Notebook    | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| HP            | 843F                        | Desktop     | [f921634ea0](https://bsd-hardware.info/?probe=f921634ea0) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [7708c4bb19](https://bsd-hardware.info/?probe=7708c4bb19) | Nov 02, 2022 |
| HP            | 843F                        | Desktop     | [bba76c5ce6](https://bsd-hardware.info/?probe=bba76c5ce6) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [22d3fc953a](https://bsd-hardware.info/?probe=22d3fc953a) | Nov 01, 2022 |
| Sophos        | XG                          | Firewall    | [a245d23614](https://bsd-hardware.info/?probe=a245d23614) | Nov 01, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [23483285a8](https://bsd-hardware.info/?probe=23483285a8) | Nov 01, 2022 |
| Dell          | Latitude 5591               | Notebook    | [40957fa567](https://bsd-hardware.info/?probe=40957fa567) | Oct 31, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6afa103d09](https://bsd-hardware.info/?probe=6afa103d09) | Oct 31, 2022 |
| Supermicro    | X10DRU-i+                   | Desktop     | [1ffd63a929](https://bsd-hardware.info/?probe=1ffd63a929) | Oct 31, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [d2d5364c96](https://bsd-hardware.info/?probe=d2d5364c96) | Oct 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [c14a3eb06b](https://bsd-hardware.info/?probe=c14a3eb06b) | Oct 31, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | Notebook    | [b816902c0b](https://bsd-hardware.info/?probe=b816902c0b) | Oct 31, 2022 |
| MSI           | H81M-P33                    | Desktop     | [b67d6a7bb2](https://bsd-hardware.info/?probe=b67d6a7bb2) | Oct 30, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [8161bfd24d](https://bsd-hardware.info/?probe=8161bfd24d) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a0896f17e4](https://bsd-hardware.info/?probe=a0896f17e4) | Oct 30, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [d20bfb6d64](https://bsd-hardware.info/?probe=d20bfb6d64) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | Notebook    | [2776d8c350](https://bsd-hardware.info/?probe=2776d8c350) | Oct 30, 2022 |
| Lenovo        | ThinkPad W530 24491A0       | Notebook    | [4a700f43f8](https://bsd-hardware.info/?probe=4a700f43f8) | Oct 30, 2022 |
| HP            | 843B                        | Desktop     | [d7d572f9ad](https://bsd-hardware.info/?probe=d7d572f9ad) | Oct 29, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [f8652952a4](https://bsd-hardware.info/?probe=f8652952a4) | Oct 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [02d617a604](https://bsd-hardware.info/?probe=02d617a604) | Oct 29, 2022 |
| Dell          | 0XCR8D A01                  | Desktop     | [a019244c85](https://bsd-hardware.info/?probe=a019244c85) | Oct 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [9a12cd02f0](https://bsd-hardware.info/?probe=9a12cd02f0) | Oct 28, 2022 |
| MSI           | B360I GMAING PRO AC         | Desktop     | [7287c670f0](https://bsd-hardware.info/?probe=7287c670f0) | Oct 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [015f0a0a6d](https://bsd-hardware.info/?probe=015f0a0a6d) | Oct 27, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [16c226553c](https://bsd-hardware.info/?probe=16c226553c) | Oct 27, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [f89024b7be](https://bsd-hardware.info/?probe=f89024b7be) | Oct 27, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [766ee6f4eb](https://bsd-hardware.info/?probe=766ee6f4eb) | Oct 27, 2022 |
| Dell          | 081N4V A05                  | Server      | [913791b3cc](https://bsd-hardware.info/?probe=913791b3cc) | Oct 26, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [f6df7bf1e8](https://bsd-hardware.info/?probe=f6df7bf1e8) | Oct 26, 2022 |
| Lenovo        | ThinkPad T420s 4174DL7      | Notebook    | [82d774e711](https://bsd-hardware.info/?probe=82d774e711) | Oct 26, 2022 |
| Supermicro    | X11SSH-F                    | Server      | [66c10b64cb](https://bsd-hardware.info/?probe=66c10b64cb) | Oct 25, 2022 |
| Dell          | 05XGC8 A01                  | Desktop     | [97947568ee](https://bsd-hardware.info/?probe=97947568ee) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [09e5063724](https://bsd-hardware.info/?probe=09e5063724) | Oct 24, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [eea9a0bef3](https://bsd-hardware.info/?probe=eea9a0bef3) | Oct 24, 2022 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [0708c0f089](https://bsd-hardware.info/?probe=0708c0f089) | Oct 24, 2022 |
| Unknown       | YL-J3160L4                  | Desktop     | [746694bb1d](https://bsd-hardware.info/?probe=746694bb1d) | Oct 24, 2022 |
| HP            | ProLiant DL360 G5           | Server      | [8a90c37da4](https://bsd-hardware.info/?probe=8a90c37da4) | Oct 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [caad4323ba](https://bsd-hardware.info/?probe=caad4323ba) | Oct 23, 2022 |
| MSI           | H81M-P33                    | Desktop     | [626f503cad](https://bsd-hardware.info/?probe=626f503cad) | Oct 23, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [2b98739799](https://bsd-hardware.info/?probe=2b98739799) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [56dac6bc80](https://bsd-hardware.info/?probe=56dac6bc80) | Oct 23, 2022 |
| HP            | 843B                        | Desktop     | [9ea2590610](https://bsd-hardware.info/?probe=9ea2590610) | Oct 23, 2022 |
| Unknown       | 1.21                        | Desktop     | [f8a845fcda](https://bsd-hardware.info/?probe=f8a845fcda) | Oct 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [89d0639a68](https://bsd-hardware.info/?probe=89d0639a68) | Oct 23, 2022 |
| Lenovo        | ThinkServer RS140           | Server      | [d6111b8ff1](https://bsd-hardware.info/?probe=d6111b8ff1) | Oct 23, 2022 |
| Dell          | 01W23F A02                  | Server      | [8e2465430e](https://bsd-hardware.info/?probe=8e2465430e) | Oct 22, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [803b44339b](https://bsd-hardware.info/?probe=803b44339b) | Oct 22, 2022 |
| Supermicro    | X9DRD-iF                    | Server      | [d21c2d1a10](https://bsd-hardware.info/?probe=d21c2d1a10) | Oct 22, 2022 |
| Supermicro    | X9DRD-iF                    | Server      | [c708a7828f](https://bsd-hardware.info/?probe=c708a7828f) | Oct 22, 2022 |
| Dell          | 0M877N A00                  | Server      | [dd965c2bfc](https://bsd-hardware.info/?probe=dd965c2bfc) | Oct 22, 2022 |
| Dell          | 0KM5PX A04                  | Server      | [9c2ca983ac](https://bsd-hardware.info/?probe=9c2ca983ac) | Oct 22, 2022 |
| MSI           | 890GXM-G65                  | Desktop     | [03c116d78f](https://bsd-hardware.info/?probe=03c116d78f) | Oct 22, 2022 |
| Alienware     | 0PGRP5 A01                  | Desktop     | [e34219da0f](https://bsd-hardware.info/?probe=e34219da0f) | Oct 22, 2022 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [12f7ac40ac](https://bsd-hardware.info/?probe=12f7ac40ac) | Oct 21, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [a47e59ad6b](https://bsd-hardware.info/?probe=a47e59ad6b) | Oct 21, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [eb9ffe08e7](https://bsd-hardware.info/?probe=eb9ffe08e7) | Oct 21, 2022 |
| Protectli     | FW6                         | Desktop     | [528ef94fb5](https://bsd-hardware.info/?probe=528ef94fb5) | Oct 21, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [bef50b27cb](https://bsd-hardware.info/?probe=bef50b27cb) | Oct 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [1778396ba9](https://bsd-hardware.info/?probe=1778396ba9) | Oct 20, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [ef14460db8](https://bsd-hardware.info/?probe=ef14460db8) | Oct 19, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [c75bcb519e](https://bsd-hardware.info/?probe=c75bcb519e) | Oct 18, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [45d6590312](https://bsd-hardware.info/?probe=45d6590312) | Oct 18, 2022 |
| Dell          | 02K9CR A02                  | Desktop     | [a5cda6c49e](https://bsd-hardware.info/?probe=a5cda6c49e) | Oct 18, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [2e4cd910d7](https://bsd-hardware.info/?probe=2e4cd910d7) | Oct 17, 2022 |
| Dell          | 0CNCJW A10                  | Server      | [1bc8c02062](https://bsd-hardware.info/?probe=1bc8c02062) | Oct 17, 2022 |
| Dell          | 0CNCJW A10                  | Server      | [25666c6950](https://bsd-hardware.info/?probe=25666c6950) | Oct 17, 2022 |
| BESSTAR Te... | GB7B                        | Mini pc     | [75ee70a8cd](https://bsd-hardware.info/?probe=75ee70a8cd) | Oct 17, 2022 |
| Intel         | DH57DD AAE82022-202         | Desktop     | [01622a2528](https://bsd-hardware.info/?probe=01622a2528) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2885a5ce85](https://bsd-hardware.info/?probe=2885a5ce85) | Oct 17, 2022 |
| HP            | 1588h                       | Desktop     | [e78a0308c7](https://bsd-hardware.info/?probe=e78a0308c7) | Oct 16, 2022 |
| Protectli     | FW4B                        | Desktop     | [57ae1d8cda](https://bsd-hardware.info/?probe=57ae1d8cda) | Oct 15, 2022 |
| HP            | 8169                        | Desktop     | [86b1fbf917](https://bsd-hardware.info/?probe=86b1fbf917) | Oct 15, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [76a1007c46](https://bsd-hardware.info/?probe=76a1007c46) | Oct 15, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [55967e02f6](https://bsd-hardware.info/?probe=55967e02f6) | Oct 15, 2022 |
| TYAN Compu... | Tiger K8W Dual AMD Opter... | Desktop     | [bbd42243ae](https://bsd-hardware.info/?probe=bbd42243ae) | Oct 15, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [b02dcbb7b5](https://bsd-hardware.info/?probe=b02dcbb7b5) | Oct 15, 2022 |
| TYAN Compu... | Tiger K8W Dual AMD Opter... | Desktop     | [0e9ac1e935](https://bsd-hardware.info/?probe=0e9ac1e935) | Oct 15, 2022 |
| Dell          | 081N4V A09                  | Server      | [3cbacacfa4](https://bsd-hardware.info/?probe=3cbacacfa4) | Oct 15, 2022 |
| TYAN Compu... | Intel 440BX/GX Rev. 4       | Desktop     | [8d99f317e4](https://bsd-hardware.info/?probe=8d99f317e4) | Oct 15, 2022 |
| Dell          | 0G1548 A00                  | Desktop     | [226af33d5b](https://bsd-hardware.info/?probe=226af33d5b) | Oct 15, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [06214241b3](https://bsd-hardware.info/?probe=06214241b3) | Oct 15, 2022 |
| AZW           | Green G1                    | Desktop     | [f6f16c5141](https://bsd-hardware.info/?probe=f6f16c5141) | Oct 15, 2022 |
| Supermicro    | X10SLL-F                    | Desktop     | [3b13ea475b](https://bsd-hardware.info/?probe=3b13ea475b) | Oct 14, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [17a6b61af7](https://bsd-hardware.info/?probe=17a6b61af7) | Oct 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [856e29140e](https://bsd-hardware.info/?probe=856e29140e) | Oct 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [10358c7207](https://bsd-hardware.info/?probe=10358c7207) | Oct 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b20b6c7997](https://bsd-hardware.info/?probe=b20b6c7997) | Oct 13, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [0da821d451](https://bsd-hardware.info/?probe=0da821d451) | Oct 13, 2022 |
| Dell          | Latitude 5591               | Notebook    | [04f53f51c8](https://bsd-hardware.info/?probe=04f53f51c8) | Oct 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [7000ef7aeb](https://bsd-hardware.info/?probe=7000ef7aeb) | Oct 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [94915735cc](https://bsd-hardware.info/?probe=94915735cc) | Oct 11, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [abceadc2e3](https://bsd-hardware.info/?probe=abceadc2e3) | Oct 11, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ff2b9a916f](https://bsd-hardware.info/?probe=ff2b9a916f) | Oct 11, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [2cba6fbbb7](https://bsd-hardware.info/?probe=2cba6fbbb7) | Oct 11, 2022 |
| Dell          | Latitude 5591               | Notebook    | [eda94b6c48](https://bsd-hardware.info/?probe=eda94b6c48) | Oct 11, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [4c9069df20](https://bsd-hardware.info/?probe=4c9069df20) | Oct 10, 2022 |
| HP            | 1495                        | Desktop     | [cfa8ab5df3](https://bsd-hardware.info/?probe=cfa8ab5df3) | Oct 10, 2022 |
| Dell          | Latitude E6420              | Notebook    | [48c26d2a17](https://bsd-hardware.info/?probe=48c26d2a17) | Oct 10, 2022 |
| Protectli     | FW1 Ver                     | Desktop     | [1015ef5e66](https://bsd-hardware.info/?probe=1015ef5e66) | Oct 09, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [e08e2ca6e0](https://bsd-hardware.info/?probe=e08e2ca6e0) | Oct 09, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [c79fa6f001](https://bsd-hardware.info/?probe=c79fa6f001) | Oct 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [e595ade938](https://bsd-hardware.info/?probe=e595ade938) | Oct 09, 2022 |
| MiTAC         | PH11CMI                     | Desktop     | [71802cdcad](https://bsd-hardware.info/?probe=71802cdcad) | Oct 09, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [464739212c](https://bsd-hardware.info/?probe=464739212c) | Oct 08, 2022 |
| Lenovo        | ThinkCentre M72e 3664AD9    | Desktop     | [f6fded284d](https://bsd-hardware.info/?probe=f6fded284d) | Oct 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [e4e47282a9](https://bsd-hardware.info/?probe=e4e47282a9) | Oct 08, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [82335a8874](https://bsd-hardware.info/?probe=82335a8874) | Oct 07, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [384de92279](https://bsd-hardware.info/?probe=384de92279) | Oct 07, 2022 |
| Supermicro    | X8DT6                       | Server      | [2bd1529913](https://bsd-hardware.info/?probe=2bd1529913) | Oct 07, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [9d3eed2bec](https://bsd-hardware.info/?probe=9d3eed2bec) | Oct 07, 2022 |
| Lenovo        | ThinkPad X270 20HMS04P00    | Notebook    | [7647b7a0b2](https://bsd-hardware.info/?probe=7647b7a0b2) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [ad8b88d10b](https://bsd-hardware.info/?probe=ad8b88d10b) | Oct 07, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [84300e7dcc](https://bsd-hardware.info/?probe=84300e7dcc) | Oct 07, 2022 |
| ADI Engine... | RCC-VE                      | Desktop     | [f6a9012bb2](https://bsd-hardware.info/?probe=f6a9012bb2) | Oct 07, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [7e24ab5841](https://bsd-hardware.info/?probe=7e24ab5841) | Oct 07, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [11e04b0c73](https://bsd-hardware.info/?probe=11e04b0c73) | Oct 07, 2022 |
| Protectli     | FW4B                        | Desktop     | [89a0375ecb](https://bsd-hardware.info/?probe=89a0375ecb) | Oct 06, 2022 |
| Protectli     | VP4650                      | Desktop     | [c9f3c90f23](https://bsd-hardware.info/?probe=c9f3c90f23) | Oct 06, 2022 |
| Dell          | 081N4V A04                  | Server      | [a2d73ebe76](https://bsd-hardware.info/?probe=a2d73ebe76) | Oct 05, 2022 |
| HP            | 8299                        | Desktop     | [e0f84d2500](https://bsd-hardware.info/?probe=e0f84d2500) | Oct 05, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [ec799eed0c](https://bsd-hardware.info/?probe=ec799eed0c) | Oct 05, 2022 |
| Sophos        | XG                          | Firewall    | [7db10dce96](https://bsd-hardware.info/?probe=7db10dce96) | Oct 05, 2022 |
| Dell          | 0WMJ54 A00                  | Desktop     | [541e5011d9](https://bsd-hardware.info/?probe=541e5011d9) | Oct 04, 2022 |
| HP            | 18E7                        | Desktop     | [ad345682d8](https://bsd-hardware.info/?probe=ad345682d8) | Oct 04, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [627206d154](https://bsd-hardware.info/?probe=627206d154) | Oct 04, 2022 |
| Sophos        | XG                          | Firewall    | [6408d528c9](https://bsd-hardware.info/?probe=6408d528c9) | Oct 03, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [8123ab15ec](https://bsd-hardware.info/?probe=8123ab15ec) | Oct 03, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [d30234a34e](https://bsd-hardware.info/?probe=d30234a34e) | Oct 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [f2647037ec](https://bsd-hardware.info/?probe=f2647037ec) | Oct 02, 2022 |
| HPE           | ProLiant ML30 Gen10         | Desktop     | [f1b45790d4](https://bsd-hardware.info/?probe=f1b45790d4) | Oct 02, 2022 |
| Dell          | Precision M4800             | Notebook    | [0fcbdeeeb7](https://bsd-hardware.info/?probe=0fcbdeeeb7) | Oct 02, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [5671721752](https://bsd-hardware.info/?probe=5671721752) | Oct 02, 2022 |
| HP            | 8767 A                      | Desktop     | [9d98b3baa4](https://bsd-hardware.info/?probe=9d98b3baa4) | Oct 02, 2022 |
| HP            | 212B                        | Desktop     | [7bc6506336](https://bsd-hardware.info/?probe=7bc6506336) | Oct 01, 2022 |
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
| Unknown       | Unknown                     | Desktop     | [69a8b9b8d9](https://bsd-hardware.info/?probe=69a8b9b8d9) | Sep 26, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [cfcfd2a636](https://bsd-hardware.info/?probe=cfcfd2a636) | Sep 26, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [68d99cffe1](https://bsd-hardware.info/?probe=68d99cffe1) | Sep 26, 2022 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [83607fc711](https://bsd-hardware.info/?probe=83607fc711) | Sep 25, 2022 |
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
| HP            | 213D A01                    | Desktop     | [6e8a38b6ca](https://bsd-hardware.info/?probe=6e8a38b6ca) | Sep 18, 2022 |
| EAGLE EYE ... | BayTrail-D Rev.00           | Desktop     | [261f623516](https://bsd-hardware.info/?probe=261f623516) | Sep 18, 2022 |
| CONTEC        | G1/EMB-CV1/iD2550           | Desktop     | [266ef0ca6a](https://bsd-hardware.info/?probe=266ef0ca6a) | Sep 18, 2022 |
| Standard      | SFFGL Series                | Mini pc     | [a537bcd507](https://bsd-hardware.info/?probe=a537bcd507) | Sep 16, 2022 |
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
| Jingsha       | x79-P3 by xUz               | Desktop     | [32ed0bcfa9](https://bsd-hardware.info/?probe=32ed0bcfa9) | Jul 26, 2022 |
| HP            | 18E7                        | Desktop     | [0d18e24e2e](https://bsd-hardware.info/?probe=0d18e24e2e) | Jul 26, 2022 |
| Dell          | 07F37C A01                  | Desktop     | [dfea879cdc](https://bsd-hardware.info/?probe=dfea879cdc) | Jul 26, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d32a6452bb](https://bsd-hardware.info/?probe=d32a6452bb) | Jul 25, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [9b3459c1ec](https://bsd-hardware.info/?probe=9b3459c1ec) | Jul 25, 2022 |
| Shuttle       | FS310                       | Desktop     | [4dd7894e83](https://bsd-hardware.info/?probe=4dd7894e83) | Jul 25, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [bf4826f24c](https://bsd-hardware.info/?probe=bf4826f24c) | Jul 24, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [84cfd4b073](https://bsd-hardware.info/?probe=84cfd4b073) | Jul 24, 2022 |
| AAEON         | FWS-2350 V1.0               | Desktop     | [e16dd36daf](https://bsd-hardware.info/?probe=e16dd36daf) | Jul 24, 2022 |
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
| Dell          | 08HPGT A02                  | Desktop     | [ae260e17eb](https://bsd-hardware.info/?probe=ae260e17eb) | Jul 19, 2022 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [ae58265601](https://bsd-hardware.info/?probe=ae58265601) | Jul 18, 2022 |
| Deciso        | Netboard A20                | Notebook    | [2bc988b18a](https://bsd-hardware.info/?probe=2bc988b18a) | Jul 18, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [15c5d9fdd9](https://bsd-hardware.info/?probe=15c5d9fdd9) | Jul 17, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [e4e89253c3](https://bsd-hardware.info/?probe=e4e89253c3) | Jul 17, 2022 |
| Deciso        | Netboard A20                | Notebook    | [a4be4171b6](https://bsd-hardware.info/?probe=a4be4171b6) | Jul 17, 2022 |
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
| Supermicro    | A1SRi-2558F                 | Mini pc     | [698d59d94e](https://bsd-hardware.info/?probe=698d59d94e) | Jul 13, 2022 |
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
| Jingsha       | x79-P3 by xUz               | Desktop     | [b4f18ad479](https://bsd-hardware.info/?probe=b4f18ad479) | Jul 11, 2022 |
| HP            | 1495                        | Desktop     | [7ed22254af](https://bsd-hardware.info/?probe=7ed22254af) | Jul 11, 2022 |
| HP            | 1495                        | Desktop     | [1bf0dc0f98](https://bsd-hardware.info/?probe=1bf0dc0f98) | Jul 11, 2022 |
| Supermicro    | X10SBAB                     | Server      | [1bf38a759a](https://bsd-hardware.info/?probe=1bf38a759a) | Jul 10, 2022 |
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
| HP            | 843F                        | Desktop     | [30700c4158](https://bsd-hardware.info/?probe=30700c4158) | Jul 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [720d51613e](https://bsd-hardware.info/?probe=720d51613e) | Jul 03, 2022 |
| HP            | ProLiant DL20 Gen9          | Server      | [f82d95a462](https://bsd-hardware.info/?probe=f82d95a462) | Jul 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [5b79558a40](https://bsd-hardware.info/?probe=5b79558a40) | Jul 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [699fea1ac9](https://bsd-hardware.info/?probe=699fea1ac9) | Jul 02, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [3c2e2da462](https://bsd-hardware.info/?probe=3c2e2da462) | Jul 02, 2022 |
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
| AZW           | GK55                        | Desktop     | [82e212ab9e](https://bsd-hardware.info/?probe=82e212ab9e) | Jun 27, 2022 |
| Supermicro    | X10SRL-F                    | Server      | [1499a2903d](https://bsd-hardware.info/?probe=1499a2903d) | Jun 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3f2f69321d](https://bsd-hardware.info/?probe=3f2f69321d) | Jun 27, 2022 |
| ASUSTek       | ROG STRIX Z590-I GAMING ... | Desktop     | [b628bb87a6](https://bsd-hardware.info/?probe=b628bb87a6) | Jun 26, 2022 |
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
| Unknown       | EMB-B75A                    | Desktop     | [a2adb81748](https://bsd-hardware.info/?probe=a2adb81748) | Jun 13, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [29a12ab775](https://bsd-hardware.info/?probe=29a12ab775) | Jun 13, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [b627258b73](https://bsd-hardware.info/?probe=b627258b73) | Jun 13, 2022 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [7b19e64a0e](https://bsd-hardware.info/?probe=7b19e64a0e) | Jun 13, 2022 |
| Dell          | PowerEdge R610              | Server      | [68bd058f04](https://bsd-hardware.info/?probe=68bd058f04) | Jun 13, 2022 |
| Dell          | 0HMF7C A01                  | Desktop     | [ad0f6d4b31](https://bsd-hardware.info/?probe=ad0f6d4b31) | Jun 13, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [db92ea33c8](https://bsd-hardware.info/?probe=db92ea33c8) | Jun 12, 2022 |
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
| HP            | 1495                        | Desktop     | [ce6fa257fd](https://bsd-hardware.info/?probe=ce6fa257fd) | Jun 08, 2022 |
| AZW           | Green G1                    | Desktop     | [0443d21ba3](https://bsd-hardware.info/?probe=0443d21ba3) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d54c86624e](https://bsd-hardware.info/?probe=d54c86624e) | Jun 08, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [2e5eb217b5](https://bsd-hardware.info/?probe=2e5eb217b5) | Jun 08, 2022 |
| ADI           | MinnowBoard Turbot          | Desktop     | [917e897373](https://bsd-hardware.info/?probe=917e897373) | Jun 07, 2022 |
| Protectli     | FW6                         | Desktop     | [85d825c3a6](https://bsd-hardware.info/?probe=85d825c3a6) | Jun 07, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [af39fe65b7](https://bsd-hardware.info/?probe=af39fe65b7) | Jun 07, 2022 |
| Apple         | MacPro4,1                   | Desktop     | [65380f3847](https://bsd-hardware.info/?probe=65380f3847) | Jun 06, 2022 |
| Dell          | 0WMJ54 A00                  | Desktop     | [40510e311b](https://bsd-hardware.info/?probe=40510e311b) | Jun 06, 2022 |
| Sophos        | SG                          | Firewall    | [2f235d7404](https://bsd-hardware.info/?probe=2f235d7404) | Jun 06, 2022 |
| MSI           | Z590 PRO WIFI               | Desktop     | [29b410eeb6](https://bsd-hardware.info/?probe=29b410eeb6) | Jun 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [03a994458a](https://bsd-hardware.info/?probe=03a994458a) | Jun 05, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [2de97a7ff6](https://bsd-hardware.info/?probe=2de97a7ff6) | Jun 05, 2022 |
| Biostar       | Hi-Fi B85N 3D               | Desktop     | [b88e0faba8](https://bsd-hardware.info/?probe=b88e0faba8) | Jun 05, 2022 |
| HP            | 8103 A01                    | Mini pc     | [97ef9e2512](https://bsd-hardware.info/?probe=97ef9e2512) | Jun 05, 2022 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [018c0120f3](https://bsd-hardware.info/?probe=018c0120f3) | Jun 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | Notebook    | [8029eb2018](https://bsd-hardware.info/?probe=8029eb2018) | Jun 04, 2022 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [53f89519ba](https://bsd-hardware.info/?probe=53f89519ba) | Jun 04, 2022 |
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
| JGINYUE       | B85I PLUS V1.0              | Desktop     | [55e9734c09](https://bsd-hardware.info/?probe=55e9734c09) | May 10, 2022 |
| Protectli     | FW6D                        | Desktop     | [a1390bbbea](https://bsd-hardware.info/?probe=a1390bbbea) | May 10, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ffb2587425](https://bsd-hardware.info/?probe=ffb2587425) | May 10, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fe1055a1c3](https://bsd-hardware.info/?probe=fe1055a1c3) | May 09, 2022 |
| Dell          | Latitude 2100               | Notebook    | [40406069ee](https://bsd-hardware.info/?probe=40406069ee) | May 09, 2022 |
| HP            | 802E                        | Desktop     | [8de7dc0ac0](https://bsd-hardware.info/?probe=8de7dc0ac0) | May 08, 2022 |
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

...

See full list of test cases in the file [Test_Cases.md](</Location/USA/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 21.7.7   | 90        | 3.16%   |
| OPNsense 21.7.3   | 77        | 2.7%    |
| OPNsense 21.7.1   | 69        | 2.42%   |
| OPNsense 22.1     | 68        | 2.39%   |
| OPNsense 21.1.5   | 67        | 2.35%   |
| OPNsense 22.7.4   | 65        | 2.28%   |
| helloSystem 0.7.0 | 64        | 2.25%   |
| OPNsense 20.7.8   | 61        | 2.14%   |
| OPNsense 22.1.10  | 60        | 2.11%   |
| OPNsense 21.1.4   | 60        | 2.11%   |
| FreeBSD 13.0      | 60        | 2.11%   |
| OPNsense 22.1.8   | 58        | 2.04%   |
| OPNsense 21.1.3   | 58        | 2.04%   |
| OPNsense 21.1     | 51        | 1.79%   |
| OPNsense 21.1.8   | 50        | 1.75%   |
| OPNsense 22.7.9   | 49        | 1.72%   |
| OPNsense 22.7.6   | 49        | 1.72%   |
| OPNsense 22.7.2   | 45        | 1.58%   |
| OPNsense 22.7.8   | 44        | 1.54%   |
| FreeBSD 13.1      | 44        | 1.54%   |
| OPNsense 22.7     | 42        | 1.47%   |
| OPNsense 22.1.6   | 42        | 1.47%   |
| OPNsense 22.1.4   | 42        | 1.47%   |
| OPNsense 22.1.2   | 42        | 1.47%   |
| OPNsense 21.1.7   | 42        | 1.47%   |
| OPNsense 21.1.1   | 42        | 1.47%   |
| helloSystem 0.5.0 | 42        | 1.47%   |
| OPNsense 22.7.7   | 40        | 1.4%    |
| OPNsense 22.1.1   | 36        | 1.26%   |
| OPNsense 21.7.6   | 36        | 1.26%   |
| OPNsense 21.1.6   | 36        | 1.26%   |
| OPNsense 22.1.7   | 33        | 1.16%   |
| FreeBSD 13.0-p4   | 33        | 1.16%   |
| OPNsense 21.7.5   | 32        | 1.12%   |
| OPNsense 21.7.4   | 31        | 1.09%   |
| OPNsense 21.1.2   | 31        | 1.09%   |
| OpenBSD 6.8       | 31        | 1.09%   |
| FreeBSD 12.2      | 30        | 1.05%   |
| OPNsense 21.7     | 29        | 1.02%   |
| OPNsense 21.7.8   | 28        | 0.98%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 1264      | 59.48%  |
| FreeBSD     | 454       | 21.36%  |
| helloSystem | 155       | 7.29%   |
| OpenBSD     | 89        | 4.19%   |
| GhostBSD    | 46        | 2.16%   |
| NomadBSD    | 33        | 1.55%   |
| pfSense     | 17        | 0.8%    |
| FreeNAS     | 17        | 0.8%    |
| MidnightBSD | 13        | 0.61%   |
| TrueNAS     | 11        | 0.52%   |
| HardenedBSD | 9         | 0.42%   |
| DragonFly   | 6         | 0.28%   |
| NetBSD      | 5         | 0.24%   |
| FuryBSD     | 3         | 0.14%   |
| OS108       | 2         | 0.09%   |
| XigmaNAS    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 2057      | 97.63%  |
| i386    | 27        | 1.28%   |
| arm64   | 21        | 1%      |
| powerpc | 2         | 0.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 1494      | 69.49%  |
| helloDesktop  | 165       | 7.67%   |
| XFCE          | 90        | 4.19%   |
| MATE          | 67        | 3.12%   |
| KDE5          | 65        | 3.02%   |
| fvwm          | 58        | 2.7%    |
| TWM           | 51        | 2.37%   |
| Openbox       | 47        | 2.19%   |
| GNOME         | 42        | 1.95%   |
| i3            | 27        | 1.26%   |
| Cinnamon      | 12        | 0.56%   |
| Fluxbox       | 6         | 0.28%   |
| Enlightenment | 6         | 0.28%   |
| Lumina        | 4         | 0.19%   |
| AwesomeWM     | 3         | 0.14%   |
| Xfwm4         | 2         | 0.09%   |
| GNUstep       | 2         | 0.09%   |
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

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1514      | 71.42%  |
| X11     | 601       | 28.35%  |
| Wayland | 5         | 0.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1683      | 78.94%  |
| SLiM    | 248       | 11.63%  |
| LightDM | 73        | 3.42%   |
| SDDM    | 66        | 3.1%    |
| XDM     | 36        | 1.69%   |
| GDM     | 24        | 1.13%   |
| Ly      | 2         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 1557      | 72.15%  |
| en_US           | 334       | 15.48%  |
| C               | 257       | 11.91%  |
| en_US.US-ASCII  | 2         | 0.09%   |
| en_US.ISO8859-1 | 2         | 0.09%   |
| en_GB           | 2         | 0.09%   |
| fr              | 1         | 0.05%   |
| es_CO           | 1         | 0.05%   |
| en_US.utf-8     | 1         | 0.05%   |
| de_DE           | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1755      | 81.89%  |
| BIOS | 388       | 18.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 1144      | 52.82%  |
| Zfs     | 886       | 40.9%   |
| Ffs     | 89        | 4.11%   |
| Cd9660  | 40        | 1.85%   |
| Hammer2 | 6         | 0.28%   |
| Unknown | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1926      | 90.47%  |
| MBR     | 178       | 8.36%   |
| Unknown | 19        | 0.89%   |
| BSD     | 6         | 0.28%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 357       | 16.96%  |
| Hewlett-Packard         | 209       | 9.93%   |
| Lenovo                  | 195       | 9.26%   |
| Supermicro              | 189       | 8.98%   |
| Protectli               | 162       | 7.7%    |
| Unknown                 | 149       | 7.08%   |
| ASUSTek Computer        | 138       | 6.56%   |
| ASRock                  | 89        | 4.23%   |
| Intel                   | 88        | 4.18%   |
| MSI                     | 62        | 2.95%   |
| Gigabyte Technology     | 54        | 2.57%   |
| AMI                     | 36        | 1.71%   |
| Apple                   | 34        | 1.62%   |
| PC Engines              | 28        | 1.33%   |
| Deciso                  | 17        | 0.81%   |
| Sophos                  | 16        | 0.76%   |
| Acer                    | 16        | 0.76%   |
| CompuLab                | 11        | 0.52%   |
| System76                | 10        | 0.48%   |
| Biostar                 | 10        | 0.48%   |
| AZW                     | 10        | 0.48%   |
| Toshiba                 | 9         | 0.43%   |
| AWOW                    | 9         | 0.43%   |
| Techvision              | 8         | 0.38%   |
| BESSTAR Tech            | 8         | 0.38%   |
| Google                  | 7         | 0.33%   |
| Fujitsu                 | 7         | 0.33%   |
| Framework               | 7         | 0.33%   |
| Foxconn                 | 7         | 0.33%   |
| ASRockRack              | 7         | 0.33%   |
| Shuttle                 | 6         | 0.29%   |
| SeeedStudio             | 6         | 0.29%   |
| HARDKERNEL              | 6         | 0.29%   |
| ZOTAC                   | 5         | 0.24%   |
| Seeed Studio            | 5         | 0.24%   |
| Cisco Systems           | 5         | 0.24%   |
| TYAN Computer           | 4         | 0.19%   |
| Raspberry Pi Foundation | 4         | 0.19%   |
| MW                      | 4         | 0.19%   |
| HPE                     | 4         | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 154       | 7.32%   |
| Protectli FW4B                      | 63        | 2.99%   |
| Supermicro Super Server             | 50        | 2.38%   |
| Protectli FW6                       | 46        | 2.19%   |
| AMI Aptio CRB                       | 32        | 1.52%   |
| Intel Q3XXG4-P V1.0                 | 29        | 1.38%   |
| HP t620 PLUS Quad Core TC           | 20        | 0.95%   |
| Dell OptiPlex 9020                  | 19        | 0.9%    |
| Dell OptiPlex 3020                  | 19        | 0.9%    |
| HP t730 Thin Client                 | 18        | 0.86%   |
| Supermicro X9SCL/X9SCM              | 17        | 0.81%   |
| Dell PowerEdge R210 II              | 17        | 0.81%   |
| Supermicro X10SLH-N6-ST031          | 16        | 0.76%   |
| ASUS All Series                     | 15        | 0.71%   |
| PC Engines apu4                     | 13        | 0.62%   |
| PC Engines APU2                     | 13        | 0.62%   |
| Dell OptiPlex 990                   | 13        | 0.62%   |
| Protectli FW2B                      | 12        | 0.57%   |
| Protectli VP2410                    | 11        | 0.52%   |
| Dell OptiPlex 7010                  | 11        | 0.52%   |
| CompuLab fitlet2                    | 11        | 0.52%   |
| Deciso Netboard A20                 | 10        | 0.48%   |
| Supermicro A1SAi                    | 9         | 0.43%   |
| Sophos XG                           | 9         | 0.43%   |
| HP EliteDesk 800 G1 SFF             | 9         | 0.43%   |
| Techvision TVI7309X                 | 8         | 0.38%   |
| Dell PowerEdge R630                 | 8         | 0.38%   |
| Dell PowerEdge R610                 | 8         | 0.38%   |
| Protectli FW6E                      | 7         | 0.33%   |
| Protectli FW6D                      | 7         | 0.33%   |
| Protectli FW1                       | 7         | 0.33%   |
| Intel Nobilis                       | 7         | 0.33%   |
| Framework Laptop                    | 7         | 0.33%   |
| Dell Wyse 5070 Extended Thin Client | 7         | 0.33%   |
| Dell PowerEdge R220                 | 7         | 0.33%   |
| Dell OptiPlex 790                   | 7         | 0.33%   |
| Dell OptiPlex 390                   | 7         | 0.33%   |
| AZW GK55                            | 7         | 0.33%   |
| AWOW PC BOX                         | 7         | 0.33%   |
| ASUS TUF GAMING X570-PLUS           | 7         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 154       | 7.32%   |
| Dell OptiPlex              | 135       | 6.41%   |
| Lenovo ThinkPad            | 115       | 5.46%   |
| Dell PowerEdge             | 95        | 4.51%   |
| Protectli FW4B             | 63        | 2.99%   |
| Supermicro Super           | 50        | 2.38%   |
| Protectli FW6              | 46        | 2.19%   |
| Lenovo ThinkCentre         | 42        | 2%      |
| Dell Latitude              | 32        | 1.52%   |
| Dell Inspiron              | 32        | 1.52%   |
| AMI Aptio                  | 32        | 1.52%   |
| Intel Q3XXG4-P             | 30        | 1.43%   |
| Dell Precision             | 28        | 1.33%   |
| HP EliteDesk               | 23        | 1.09%   |
| HP t620                    | 22        | 1.05%   |
| ASUS PRIME                 | 21        | 1%      |
| ASUS TUF                   | 20        | 0.95%   |
| HP ProLiant                | 19        | 0.9%    |
| HP Compaq                  | 19        | 0.9%    |
| ASUS ROG                   | 19        | 0.9%    |
| HP t730                    | 18        | 0.86%   |
| HP ProDesk                 | 18        | 0.86%   |
| HP Pavilion                | 18        | 0.86%   |
| Supermicro X9SCL           | 17        | 0.81%   |
| Supermicro X10SLH-N6-ST031 | 16        | 0.76%   |
| ASUS All                   | 15        | 0.71%   |
| ASRock X570                | 14        | 0.67%   |
| PC Engines apu4            | 13        | 0.62%   |
| PC Engines APU2            | 13        | 0.62%   |
| Protectli FW2B             | 12        | 0.57%   |
| Protectli VP2410           | 11        | 0.52%   |
| Dell XPS                   | 11        | 0.52%   |
| Deciso Netboard            | 11        | 0.52%   |
| CompuLab fitlet2           | 11        | 0.52%   |
| Supermicro A1SAi           | 9         | 0.43%   |
| Sophos XG                  | 9         | 0.43%   |
| Techvision TVI7309X        | 8         | 0.38%   |
| Lenovo IdeaPad             | 8         | 0.38%   |
| HP Slim                    | 8         | 0.38%   |
| Acer Aspire                | 8         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 279       | 13.25%  |
| 2019    | 259       | 12.3%   |
| 2020    | 213       | 10.12%  |
| 2021    | 161       | 7.65%   |
| 2016    | 147       | 6.98%   |
| 2014    | 142       | 6.75%   |
| 2015    | 137       | 6.51%   |
| 2011    | 130       | 6.18%   |
| 2013    | 127       | 6.03%   |
| 2017    | 116       | 5.51%   |
| 2022    | 103       | 4.89%   |
| 2012    | 98        | 4.66%   |
| 2010    | 59        | 2.8%    |
| 2009    | 38        | 1.81%   |
| Unknown | 35        | 1.66%   |
| 2008    | 26        | 1.24%   |
| 2007    | 17        | 0.81%   |
| 2006    | 10        | 0.48%   |
| 2004    | 4         | 0.19%   |
| 2005    | 1         | 0.05%   |
| 2003    | 1         | 0.05%   |
| 2002    | 1         | 0.05%   |
| 2001    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1295      | 61.52%  |
| Notebook       | 381       | 18.1%   |
| Server         | 234       | 11.12%  |
| Mini pc        | 143       | 6.79%   |
| Firewall       | 22        | 1.05%   |
| Convertible    | 14        | 0.67%   |
| System on chip | 12        | 0.57%   |
| All in one     | 4         | 0.19%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2019      | 95.91%  |
| Yes  | 86        | 4.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 783       | 36.3%   |
| 16.01-24.0      | 487       | 22.58%  |
| 4.01-8.0        | 358       | 16.6%   |
| 32.01-64.0      | 271       | 12.56%  |
| 64.01-256.0     | 119       | 5.52%   |
| 2.01-3.0        | 46        | 2.13%   |
| 24.01-32.0      | 38        | 1.76%   |
| 3.01-4.0        | 28        | 1.3%    |
| 0.51-1.0        | 11        | 0.51%   |
| 1.01-2.0        | 8         | 0.37%   |
| 0.01-0.5        | 5         | 0.23%   |
| More than 256.0 | 3         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 997       | 45.07%  |
| 0.51-1.0    | 628       | 28.39%  |
| 1.01-2.0    | 316       | 14.29%  |
| 4.01-8.0    | 65        | 2.94%   |
| 2.01-3.0    | 63        | 2.85%   |
| 3.01-4.0    | 37        | 1.67%   |
| 8.01-16.0   | 35        | 1.58%   |
| 24.01-32.0  | 18        | 0.81%   |
| 16.01-24.0  | 17        | 0.77%   |
| 32.01-64.0  | 12        | 0.54%   |
| 0           | 10        | 0.45%   |
| Unknown     | 8         | 0.36%   |
| 64.01-256.0 | 6         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1471      | 67.88%  |
| 2      | 289       | 13.34%  |
| 0      | 170       | 7.84%   |
| 3      | 89        | 4.11%   |
| 4      | 40        | 1.85%   |
| 5      | 26        | 1.2%    |
| 6      | 22        | 1.02%   |
| 7      | 10        | 0.46%   |
| 14     | 8         | 0.37%   |
| 12     | 6         | 0.28%   |
| 10     | 6         | 0.28%   |
| 8      | 6         | 0.28%   |
| 9      | 5         | 0.23%   |
| 11     | 4         | 0.18%   |
| 21     | 2         | 0.09%   |
| 18     | 2         | 0.09%   |
| 17     | 2         | 0.09%   |
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

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1635      | 76.76%  |
| Yes       | 495       | 23.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2020      | 95.96%  |
| No        | 85        | 4.04%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1394      | 65.66%  |
| Yes       | 729       | 34.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1633      | 76.99%  |
| Yes       | 488       | 23.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| USA     | 2105      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Brooklyn      | 39        | 1.69%   |
| Chicago       | 37        | 1.6%    |
| Seattle       | 30        | 1.3%    |
| New York      | 29        | 1.26%   |
| Denver        | 29        | 1.26%   |
| Dallas        | 25        | 1.08%   |
| Portland      | 24        | 1.04%   |
| Rochester     | 19        | 0.82%   |
| Los Angeles   | 19        | 0.82%   |
| Austin        | 18        | 0.78%   |
| Atlanta       | 17        | 0.74%   |
| San Francisco | 16        | 0.69%   |
| Mountain View | 15        | 0.65%   |
| Columbus      | 15        | 0.65%   |
| Springfield   | 14        | 0.61%   |
| Phoenix       | 14        | 0.61%   |
| Grand Rapids  | 13        | 0.56%   |
| Ypsilanti     | 12        | 0.52%   |
| Oakland       | 12        | 0.52%   |
| Las Vegas     | 11        | 0.48%   |
| Vienna        | 10        | 0.43%   |
| Salem         | 10        | 0.43%   |
| Omaha         | 10        | 0.43%   |
| Minneapolis   | 10        | 0.43%   |
| Houston       | 10        | 0.43%   |
| San Jose      | 9         | 0.39%   |
| San Antonio   | 9         | 0.39%   |
| Philadelphia  | 9         | 0.39%   |
| Milwaukee     | 9         | 0.39%   |
| Miami         | 9         | 0.39%   |
| Lexington     | 9         | 0.39%   |
| Kansas City   | 9         | 0.39%   |
| Jacksonville  | 9         | 0.39%   |
| Brookline     | 9         | 0.39%   |
| Bothell       | 9         | 0.39%   |
| Washington    | 8         | 0.35%   |
| San Diego     | 8         | 0.35%   |
| Raleigh       | 8         | 0.35%   |
| Poway         | 8         | 0.35%   |
| Madison       | 8         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 405       | 741    | 15.98%  |
| WDC                 | 341       | 964    | 13.45%  |
| Seagate             | 245       | 682    | 9.66%   |
| Kingston            | 170       | 226    | 6.71%   |
| SanDisk             | 117       | 149    | 4.62%   |
| Crucial             | 117       | 176    | 4.62%   |
| Intel               | 108       | 204    | 4.26%   |
| Toshiba             | 91        | 163    | 3.59%   |
| Transcend           | 88        | 163    | 3.47%   |
| Hitachi             | 59        | 149    | 2.33%   |
| A-DATA Technology   | 53        | 83     | 2.09%   |
| Hoodisk             | 51        | 68     | 2.01%   |
| Phison              | 50        | 79     | 1.97%   |
| SK hynix            | 45        | 56     | 1.78%   |
| Protectli           | 42        | 68     | 1.66%   |
| China               | 41        | 58     | 1.62%   |
| PNY                 | 40        | 56     | 1.58%   |
| HGST                | 34        | 99     | 1.34%   |
| Hewlett-Packard     | 30        | 94     | 1.18%   |
| SPCC                | 29        | 51     | 1.14%   |
| NVMe                | 22        | 29     | 0.87%   |
| Dogfish             | 22        | 34     | 0.87%   |
| BIWIN               | 22        | 34     | 0.87%   |
| Micron Technology   | 21        | 26     | 0.83%   |
| FORESEE             | 19        | 25     | 0.75%   |
| OCZ                 | 17        | 26     | 0.67%   |
| Apple               | 16        | 18     | 0.63%   |
| Corsair             | 14        | 30     | 0.55%   |
| Apacer              | 14        | 15     | 0.55%   |
| KingSpec            | 13        | 16     | 0.51%   |
| LITEON              | 10        | 16     | 0.39%   |
| Zheino              | 9         | 16     | 0.36%   |
| Team                | 9         | 11     | 0.36%   |
| Mushkin             | 9         | 13     | 0.36%   |
| KIOXIA              | 9         | 15     | 0.36%   |
| Supermicro          | 8         | 8      | 0.32%   |
| Plextor             | 8         | 16     | 0.32%   |
| Patriot             | 8         | 9      | 0.32%   |
| OWC                 | 8         | 12     | 0.32%   |
| LITEONIT            | 7         | 8      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB       | 26        | 0.93%   |
| Kingston SA400S37240G 240GB     | 25        | 0.89%   |
| Kingston SUV500MS240G 240GB     | 22        | 0.79%   |
| Hoodisk SSD 32GB                | 21        | 0.75%   |
| Seagate ST500DM002-1BD142 500GB | 19        | 0.68%   |
| Kingston SUV500MS120G 120GB     | 19        | 0.68%   |
| Samsung SSD 860 EVO 500GB       | 18        | 0.64%   |
| Samsung SSD 970 EVO Plus 500GB  | 17        | 0.61%   |
| Samsung SSD 850 EVO 500GB       | 16        | 0.57%   |
| Protectli 120GB mSATA           | 16        | 0.57%   |
| BIWIN SSD 128GB                 | 16        | 0.57%   |
| Samsung SSD 860 EVO 250GB       | 15        | 0.54%   |
| Samsung SSD 860 EVO 1TB         | 15        | 0.54%   |
| PNY CS900 120GB SSD             | 15        | 0.54%   |
| Kingston SA400S37120G 120GB     | 14        | 0.5%    |
| Hoodisk SSD 128GB               | 14        | 0.5%    |
| Samsung SSD 860 EVO M.2 250GB   | 13        | 0.47%   |
| Crucial CT500MX500SSD1 500GB    | 13        | 0.47%   |
| WDC WD800JD-75MSA3 80GB         | 12        | 0.43%   |
| SanDisk SSD PLUS 240GB          | 12        | 0.43%   |
| FORESEE 128GB SSD               | 12        | 0.43%   |
| Crucial CT1000MX500SSD1 1TB     | 12        | 0.43%   |
| WDC WD10EZEX-08WN4A0 1TB        | 11        | 0.39%   |
| Transcend TS256GMTS952T2 256GB  | 11        | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB    | 11        | 0.39%   |
| WDC WDS500G3X0C-00SJG0 500GB    | 10        | 0.36%   |
| SPCC Solid State Disk 128GB     | 10        | 0.36%   |
| SanDisk SDSA6MM-016G-1006 16GB  | 10        | 0.36%   |
| Phison Sabrent 512GB            | 10        | 0.36%   |
| Hoodisk SSD 64GB                | 10        | 0.36%   |
| Crucial CT250MX500SSD1 250GB    | 10        | 0.36%   |
| China SATA SSD 120GB            | 10        | 0.36%   |
| Toshiba DT01ACA100 1TB          | 9         | 0.32%   |
| Seagate ST4000DM000-1F2168 4TB  | 9         | 0.32%   |
| SanDisk SDSSDA120G 120GB        | 9         | 0.32%   |
| Samsung SSD 960 EVO 500GB       | 9         | 0.32%   |
| Samsung SSD 870 EVO 500GB       | 9         | 0.32%   |
| Kingston SV300S37A120G 120GB    | 9         | 0.32%   |
| HP RAID 0 480GB                 | 9         | 0.32%   |
| Crucial CT120BX500SSD1 120GB    | 9         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC                                | 256       | 813    | 34.88%  |
| Seagate                            | 235       | 657    | 32.02%  |
| Toshiba                            | 74        | 143    | 10.08%  |
| Hitachi                            | 59        | 149    | 8.04%   |
| HGST                               | 34        | 99     | 4.63%   |
| NVMe                               | 14        | 17     | 1.91%   |
| Hewlett-Packard                    | 14        | 49     | 1.91%   |
| Samsung Electronics                | 11        | 16     | 1.5%    |
| Apple                              | 8         | 9      | 1.09%   |
| Maxtor                             | 4         | 8      | 0.54%   |
| Fujitsu                            | 3         | 3      | 0.41%   |
| LSI                                | 2         | 7      | 0.27%   |
| Lexar                              | 2         | 2      | 0.27%   |
| HPE                                | 2         | 7      | 0.27%   |
| Adaptec                            | 2         | 2      | 0.27%   |
| WD MediaMax                        | 1         | 3      | 0.14%   |
| QUANTUM                            | 1         | 2      | 0.14%   |
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

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 278       | 503    | 19.16%  |
| Kingston            | 157       | 212    | 10.82%  |
| SanDisk             | 115       | 144    | 7.93%   |
| Crucial             | 97        | 148    | 6.69%   |
| Transcend           | 83        | 157    | 5.72%   |
| Intel               | 82        | 167    | 5.65%   |
| Hoodisk             | 50        | 67     | 3.45%   |
| A-DATA Technology   | 43        | 66     | 2.96%   |
| Protectli           | 42        | 68     | 2.89%   |
| China               | 40        | 57     | 2.76%   |
| PNY                 | 39        | 55     | 2.69%   |
| WDC                 | 37        | 73     | 2.55%   |
| Phison              | 27        | 36     | 1.86%   |
| SPCC                | 23        | 45     | 1.59%   |
| SK hynix            | 23        | 29     | 1.59%   |
| Dogfish             | 22        | 34     | 1.52%   |
| BIWIN               | 22        | 34     | 1.52%   |
| FORESEE             | 19        | 25     | 1.31%   |
| OCZ                 | 17        | 26     | 1.17%   |
| Apacer              | 14        | 15     | 0.96%   |
| Micron Technology   | 13        | 16     | 0.9%    |
| KingSpec            | 13        | 16     | 0.9%    |
| Corsair             | 12        | 17     | 0.83%   |
| Hewlett-Packard     | 11        | 21     | 0.76%   |
| Zheino              | 9         | 16     | 0.62%   |
| Toshiba             | 9         | 12     | 0.62%   |
| Seagate             | 9         | 19     | 0.62%   |
| LITEON              | 9         | 15     | 0.62%   |
| Supermicro          | 8         | 8      | 0.55%   |
| OWC                 | 8         | 12     | 0.55%   |
| NVMe                | 8         | 10     | 0.55%   |
| Apple               | 8         | 9      | 0.55%   |
| Plextor             | 7         | 12     | 0.48%   |
| Patriot             | 7         | 8      | 0.48%   |
| Mushkin             | 7         | 10     | 0.48%   |
| LITEONIT            | 7         | 8      | 0.48%   |
| Team                | 6         | 8      | 0.41%   |
| Innodisk            | 6         | 7      | 0.41%   |
| ShiJi               | 4         | 5      | 0.28%   |
| SATADOM             | 4         | 8      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1309      | 2289   | 57.74%  |
| HDD  | 602       | 2004   | 26.55%  |
| NVMe | 356       | 593    | 15.7%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1725      | 4293   | 82.89%  |
| NVMe | 356       | 593    | 17.11%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1443      | 2494   | 71.68%  |
| 0.51-1.0   | 320       | 641    | 15.9%   |
| 1.01-2.0   | 97        | 283    | 4.82%   |
| 4.01-10.0  | 58        | 423    | 2.88%   |
| 3.01-4.0   | 40        | 172    | 1.99%   |
| 2.01-3.0   | 40        | 166    | 1.99%   |
| 10.01-20.0 | 14        | 110    | 0.7%    |
| 20.01-50.0 | 1         | 4      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 860       | 39.52%  |
| 251-500        | 395       | 18.15%  |
| 1-20           | 226       | 10.39%  |
| 51-100         | 213       | 9.79%   |
| 501-1000       | 199       | 9.15%   |
| 21-50          | 197       | 9.05%   |
| 1001-2000      | 47        | 2.16%   |
| More than 3000 | 20        | 0.92%   |
| Unknown        | 13        | 0.6%    |
| 2001-3000      | 6         | 0.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1939      | 89.15%  |
| 21-50          | 121       | 5.56%   |
| 51-100         | 51        | 2.34%   |
| 101-250        | 28        | 1.29%   |
| Unknown        | 13        | 0.6%    |
| 251-500        | 12        | 0.55%   |
| More than 3000 | 5         | 0.23%   |
| 2001-3000      | 2         | 0.09%   |
| 501-1000       | 2         | 0.09%   |
| 1001-2000      | 1         | 0.05%   |
| 0              | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 7         | 11     | 2.34%   |
| Seagate ST500LM021-1KJ152 500GB       | 4         | 4      | 1.34%   |
| Kingston SV300S37A60G 64GB            | 4         | 4      | 1.34%   |
| Kingston SMS200S3120G 120GB           | 4         | 4      | 1.34%   |
| Crucial CT275MX300SSD1 275GB          | 4         | 7      | 1.34%   |
| Apacer 16GB SATA Flash Drive          | 4         | 5      | 1.34%   |
| SK hynix SC210 mSATA 256GB            | 3         | 3      | 1%      |
| Seagate ST3500418AS 500GB             | 3         | 10     | 1%      |
| Apacer 32GB SATA Flash Drive          | 3         | 3      | 1%      |
| WDC WD5000AAKX-60U6AA0 500GB          | 2         | 2      | 0.67%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2         | 9      | 0.67%   |
| WDC WD1600BEKT-66F3T2 160GB           | 2         | 4      | 0.67%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 0.67%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.67%   |
| Toshiba DT01ACA050 500GB              | 2         | 2      | 0.67%   |
| SSSTC CVB-8D128-HP 128GB              | 2         | 2      | 0.67%   |
| SK hynix SC308 SATA 128GB             | 2         | 3      | 0.67%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 3      | 0.67%   |
| Seagate ST3500413AS 500GB             | 2         | 10     | 0.67%   |
| Seagate ST31000528AS 1TB              | 2         | 2      | 0.67%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 2      | 0.67%   |
| Seagate ST2000DL001-9VT156 2TB        | 2         | 2      | 0.67%   |
| Seagate ST1000DM003-9YN162 1TB        | 2         | 6      | 0.67%   |
| SanDisk SSD PLUS 240GB                | 2         | 3      | 0.67%   |
| Samsung Electronics SSD 850 EVO 500GB | 2         | 2      | 0.67%   |
| MyDigitalSSD SB2 128GB                | 2         | 4      | 0.67%   |
| Kingston SV300S37A120G 120GB          | 2         | 2      | 0.67%   |
| Kingston SUV400S37120G 120GB          | 2         | 3      | 0.67%   |
| Kingston SNS4151S316GD 16GB           | 2         | 4      | 0.67%   |
| Kingston SNS4151S316G 16GB            | 2         | 2      | 0.67%   |
| Intel SSDSC2BX200G4R 200GB            | 2         | 3      | 0.67%   |
| Intel SSDSA2M080G2GC 80GB             | 2         | 2      | 0.67%   |
| Hitachi HUA722020ALA331 2TB           | 2         | 4      | 0.67%   |
| Hitachi HTS725032A9A364 320GB         | 2         | 2      | 0.67%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.67%   |
| Crucial CT480M500SSD1 480GB           | 2         | 3      | 0.67%   |
| Crucial CT240M500SSD1 240GB           | 2         | 3      | 0.67%   |
| ZTC SM201-064G                        | 1         | 3      | 0.33%   |
| Wintec 120GB SATA3 SF2281 SSD         | 1         | 1      | 0.33%   |
| WDC WDS500G2B0A-00SM50 500GB          | 1         | 1      | 0.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 63        | 117    | 21.88%  |
| WDC                  | 42        | 85     | 14.58%  |
| Kingston             | 23        | 26     | 7.99%   |
| Intel                | 23        | 29     | 7.99%   |
| Toshiba              | 19        | 27     | 6.6%    |
| Hitachi              | 19        | 25     | 6.6%    |
| Samsung Electronics  | 18        | 24     | 6.25%   |
| Crucial              | 12        | 17     | 4.17%   |
| SanDisk              | 7         | 10     | 2.43%   |
| HGST                 | 7         | 7      | 2.43%   |
| Apacer               | 7         | 8      | 2.43%   |
| SK hynix             | 6         | 8      | 2.08%   |
| OCZ                  | 4         | 4      | 1.39%   |
| LITEON               | 3         | 4      | 1.04%   |
| SSSTC                | 2         | 2      | 0.69%   |
| Phison               | 2         | 2      | 0.69%   |
| MyDigitalSSD         | 2         | 4      | 0.69%   |
| Micron Technology    | 2         | 2      | 0.69%   |
| Maxtor               | 2         | 5      | 0.69%   |
| Corsair              | 2         | 2      | 0.69%   |
| ZTC                  | 1         | 3      | 0.35%   |
| Wintec               | 1         | 1      | 0.35%   |
| WD MediaMax          | 1         | 3      | 0.35%   |
| VisionTek            | 1         | 1      | 0.35%   |
| Transcend            | 1         | 4      | 0.35%   |
| SPCC                 | 1         | 3      | 0.35%   |
| PNY                  | 1         | 1      | 0.35%   |
| Patriot              | 1         | 1      | 0.35%   |
| LITEONIT             | 1         | 1      | 0.35%   |
| KingSpec             | 1         | 1      | 0.35%   |
| KingDian             | 1         | 1      | 0.35%   |
| INDMEM               | 1         | 1      | 0.35%   |
| IBM/Hitachi          | 1         | 1      | 0.35%   |
| HPE                  | 1         | 3      | 0.35%   |
| HP Phison            | 1         | 1      | 0.35%   |
| Hewlett-Packard      | 1         | 4      | 0.35%   |
| Fujitsu              | 1         | 1      | 0.35%   |
| ExcelStor Technology | 1         | 2      | 0.35%   |
| Dogfish              | 1         | 5      | 0.35%   |
| China                | 1         | 1      | 0.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 63        | 117    | 39.13%  |
| WDC                  | 41        | 84     | 25.47%  |
| Hitachi              | 19        | 25     | 11.8%   |
| Toshiba              | 17        | 25     | 10.56%  |
| HGST                 | 7         | 7      | 4.35%   |
| Samsung Electronics  | 4         | 5      | 2.48%   |
| Maxtor               | 2         | 5      | 1.24%   |
| WD MediaMax          | 1         | 3      | 0.62%   |
| IBM/Hitachi          | 1         | 1      | 0.62%   |
| HPE                  | 1         | 3      | 0.62%   |
| Hewlett-Packard      | 1         | 4      | 0.62%   |
| Fujitsu              | 1         | 1      | 0.62%   |
| ExcelStor Technology | 1         | 2      | 0.62%   |
| China                | 1         | 1      | 0.62%   |
| Apple                | 1         | 1      | 0.62%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 154       | 284    | 55%     |
| SSD  | 124       | 164    | 44.29%  |
| NVMe | 2         | 2      | 0.71%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZYLN256HCHP-000L2 256GB | 2         | 2      | 40%     |
| SK hynix SC308 SATA 256GB                    | 1         | 1      | 20%     |
| Seagate ST3500418AS 500GB                    | 1         | 2      | 20%     |
| Samsung Electronics HD204UI 2TB              | 1         | 2      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 4      | 60%     |
| SK hynix            | 1         | 1      | 20%     |
| Seagate             | 1         | 2      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1739      | 4299   | 83.25%  |
| Malfunc  | 276       | 450    | 13.21%  |
| Detected | 69        | 130    | 3.3%    |
| Failed   | 5         | 7      | 0.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1625      | 61.74%  |
| AMD                              | 345       | 13.11%  |
| Samsung Electronics              | 148       | 5.62%   |
| Broadcom / LSI                   | 108       | 4.1%    |
| SanDisk                          | 72        | 2.74%   |
| ASMedia Technology               | 43        | 1.63%   |
| Phison Electronics               | 37        | 1.41%   |
| Marvell Technology Group         | 29        | 1.1%    |
| SK hynix                         | 25        | 0.95%   |
| Silicon Motion                   | 20        | 0.76%   |
| Chelsio Communications           | 18        | 0.68%   |
| Hewlett-Packard                  | 17        | 0.65%   |
| Micron/Crucial Technology        | 16        | 0.61%   |
| Nvidia                           | 13        | 0.49%   |
| Kingston Technology Company      | 13        | 0.49%   |
| KIOXIA                           | 11        | 0.42%   |
| Micron Technology                | 10        | 0.38%   |
| JMicron Technology               | 10        | 0.38%   |
| ADATA Technology                 | 8         | 0.3%    |
| Adaptec                          | 8         | 0.3%    |
| Toshiba                          | 7         | 0.27%   |
| Silicon Image                    | 6         | 0.23%   |
| Seagate Technology               | 6         | 0.23%   |
| Transcend                        | 5         | 0.19%   |
| Shenzhen Longsys Electronics     | 4         | 0.15%   |
| Realtek Semiconductor            | 4         | 0.15%   |
| Solid State Storage Technology   | 3         | 0.11%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.11%   |
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

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 244       | 8.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 193       | 6.4%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 133       | 4.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 108       | 3.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 97        | 3.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 80        | 2.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 76        | 2.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 75        | 2.49%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 62        | 2.06%   |
| Intel SATA Controller [RAID mode]                                                | 53        | 1.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 47        | 1.56%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 46        | 1.53%   |
| Unknown                                                                          | 46        | 1.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 42        | 1.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 41        | 1.36%   |
| AMD 400 Series Chipset SATA Controller                                           | 41        | 1.36%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 39        | 1.29%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 39        | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 38        | 1.26%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 37        | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 36        | 1.19%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 33        | 1.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 33        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 33        | 1.09%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 31        | 1.03%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 30        | 1%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 30        | 1%      |
| Intel Jasper Lake SATA AHCI Controller                                           | 29        | 0.96%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 28        | 0.93%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 27        | 0.9%    |
| AMD FCH IDE Controller                                                           | 26        | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 25        | 0.83%   |
| Phison E12 NVMe Controller                                                       | 24        | 0.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 24        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 24        | 0.8%    |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 23        | 0.76%   |
| AMD 500 Series Chipset SATA Controller                                           | 23        | 0.76%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 21        | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 21        | 0.7%    |
| Samsung NVMe SSD Controller 980                                                  | 20        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1738      | 65.58%  |
| NVMe | 392       | 14.79%  |
| IDE  | 258       | 9.74%   |
| RAID | 161       | 6.08%   |
| SAS  | 69        | 2.6%    |
| SCSI | 32        | 1.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1714      | 81.23%  |
| AMD      | 371       | 17.58%  |
| ARM      | 18        | 0.85%   |
| Unknown  | 4         | 0.19%   |
| Motorola | 1         | 0.05%   |
| IBM      | 1         | 0.05%   |
| i        | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz        | 66        | 3.09%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 49        | 2.29%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 35        | 1.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 30        | 1.4%    |
| Intel Celeron N5105 @ 2.00GHz            | 26        | 1.22%   |
| AMD GX-412TC SOC                         | 26        | 1.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 24        | 1.12%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 24        | 1.12%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 23        | 1.08%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 22        | 1.03%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 20        | 0.94%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 20        | 0.94%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 19        | 0.89%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 19        | 0.89%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 19        | 0.89%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 16        | 0.75%   |
| Intel Atom CPU D525 @ 1.80GHz            | 16        | 0.75%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 14        | 0.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 14        | 0.65%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 14        | 0.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 14        | 0.65%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz        | 13        | 0.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 13        | 0.61%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 13        | 0.61%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 13        | 0.61%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz      | 12        | 0.56%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 12        | 0.56%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 12        | 0.56%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 12        | 0.56%   |
| Intel Xeon CPU D-1518 @ 2.20GHz          | 11        | 0.51%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 11        | 0.51%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 11        | 0.51%   |
| Intel Core 2 Duo                         | 11        | 0.51%   |
| AMD Ryzen 7 2700 Eight-Core Processor    | 11        | 0.51%   |
| Intel Core i7-4770 CPU @ 3.40GHz         | 10        | 0.47%   |
| Intel Core i3-10100 CPU @ 3.60GHz        | 10        | 0.47%   |
| AMD Ryzen 5 5600G with Radeon Graphics   | 10        | 0.47%   |
| Intel Xeon CPU E31220 @ 3.10GHz          | 8         | 0.37%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz      | 8         | 0.37%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 8         | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 419       | 19.7%   |
| Intel Xeon              | 312       | 14.67%  |
| Intel Celeron           | 304       | 14.29%  |
| Intel Core i7           | 248       | 11.66%  |
| Intel Core i3           | 136       | 6.39%   |
| Intel Atom              | 113       | 5.31%   |
| Other                   | 75        | 3.53%   |
| AMD Ryzen 7             | 63        | 2.96%   |
| AMD GX                  | 57        | 2.68%   |
| AMD Ryzen 5             | 46        | 2.16%   |
| Intel Pentium           | 43        | 2.02%   |
| Intel Core 2 Duo        | 37        | 1.74%   |
| AMD FX                  | 20        | 0.94%   |
| AMD Ryzen 9             | 18        | 0.85%   |
| ARM Cortex              | 17        | 0.8%    |
| AMD EPYC                | 17        | 0.8%    |
| AMD Ryzen 3             | 16        | 0.75%   |
| Intel Pentium Silver    | 15        | 0.71%   |
| AMD A10                 | 13        | 0.61%   |
| Intel Core i9           | 11        | 0.52%   |
| Intel Core 2            | 9         | 0.42%   |
| AMD Ryzen 5 PRO         | 8         | 0.38%   |
| AMD Phenom II X4        | 8         | 0.38%   |
| AMD A8                  | 8         | 0.38%   |
| Intel Core 2 Quad       | 7         | 0.33%   |
| AMD Athlon              | 7         | 0.33%   |
| Intel Pentium 4         | 6         | 0.28%   |
| AMD Ryzen Embedded      | 6         | 0.28%   |
| AMD Opteron             | 6         | 0.28%   |
| AMD G                   | 6         | 0.28%   |
| AMD A6                  | 5         | 0.24%   |
| AMD A4                  | 5         | 0.24%   |
| Intel Pentium Dual-Core | 4         | 0.19%   |
| Intel Genuine           | 4         | 0.19%   |
| AMD Ryzen Threadripper  | 4         | 0.19%   |
| Intel Pentium M         | 3         | 0.14%   |
| Intel Pentium D         | 3         | 0.14%   |
| AMD Ryzen 7 PRO         | 3         | 0.14%   |
| AMD Phenom II X6        | 3         | 0.14%   |
| AMD E2                  | 3         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1062      | 49.91%  |
| 2       | 542       | 25.47%  |
| 8       | 143       | 6.72%   |
| 6       | 88        | 4.14%   |
| Unknown | 82        | 3.85%   |
| 16      | 76        | 3.57%   |
| 12      | 68        | 3.2%    |
| 1       | 20        | 0.94%   |
| 24      | 13        | 0.61%   |
| 32      | 8         | 0.38%   |
| 20      | 7         | 0.33%   |
| 10      | 7         | 0.33%   |
| 48      | 3         | 0.14%   |
| 36      | 2         | 0.09%   |
| 28      | 2         | 0.09%   |
| 14      | 2         | 0.09%   |
| 3       | 2         | 0.09%   |
| 64      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1978      | 93.7%   |
| 2       | 96        | 4.55%   |
| Unknown | 35        | 1.66%   |
| 8       | 1         | 0.05%   |
| 4       | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1119      | 52.86%  |
| 2       | 907       | 42.84%  |
| Unknown | 90        | 4.25%   |
| 4       | 1         | 0.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 271       | 12.75%  |
| Haswell         | 255       | 12%     |
| Silvermont      | 200       | 9.41%   |
| IvyBridge       | 158       | 7.44%   |
| SandyBridge     | 148       | 6.96%   |
| Skylake         | 123       | 5.79%   |
| Broadwell       | 87        | 4.09%   |
| Unknown         | 84        | 3.95%   |
| Goldmont plus   | 83        | 3.91%   |
| Goldmont        | 59        | 2.78%   |
| Westmere        | 57        | 2.68%   |
| Zen 2           | 55        | 2.59%   |
| Zen+            | 50        | 2.35%   |
| Zen             | 45        | 2.12%   |
| Penryn          | 42        | 1.98%   |
| Bonnell         | 42        | 1.98%   |
| Nehalem         | 39        | 1.84%   |
| Core            | 36        | 1.69%   |
| CometLake       | 35        | 1.65%   |
| Puma            | 34        | 1.6%    |
| Jaguar          | 34        | 1.6%    |
| Zen 3           | 31        | 1.46%   |
| Piledriver      | 30        | 1.41%   |
| Steamroller     | 26        | 1.22%   |
| K10             | 20        | 0.94%   |
| Bobcat          | 17        | 0.8%    |
| TigerLake       | 15        | 0.71%   |
| NetBurst        | 14        | 0.66%   |
| Excavator       | 12        | 0.56%   |
| K8 Hammer       | 9         | 0.42%   |
| P6              | 4         | 0.19%   |
| K10 Llano       | 3         | 0.14%   |
| IceLake         | 3         | 0.14%   |
| Bulldozer       | 2         | 0.09%   |
| K8 & K10 hybrid | 1         | 0.05%   |
| Geode           | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1227      | 58.07%  |
| AMD                                          | 341       | 16.14%  |
| Nvidia                                       | 231       | 10.93%  |
| Matrox Electronics Systems                   | 156       | 7.38%   |
| ASPEED Technology                            | 153       | 7.24%   |
| XGI Technology (eXtreme Graphics Innovation) | 3         | 0.14%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 153       | 7.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 108       | 5.02%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 95        | 4.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 93        | 4.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 89        | 4.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 74        | 3.44%   |
| Intel HD Graphics 620                                                                    | 67        | 3.11%   |
| Intel HD Graphics 530                                                                    | 62        | 2.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 61        | 2.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 44        | 2.05%   |
| Intel UHD Graphics 620                                                                   | 42        | 1.95%   |
| Matrox Electronics Systems G200eR2                                                       | 40        | 1.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 37        | 1.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 37        | 1.72%   |
| Intel HD Graphics 500                                                                    | 36        | 1.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 34        | 1.58%   |
| Intel JasperLake [UHD Graphics]                                                          | 33        | 1.53%   |
| Intel HD Graphics 630                                                                    | 30        | 1.39%   |
| Intel HD Graphics 5500                                                                   | 28        | 1.3%    |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 26        | 1.21%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 24        | 1.12%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 23        | 1.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 23        | 1.07%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 21        | 0.98%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 21        | 0.98%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 20        | 0.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 20        | 0.93%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 20        | 0.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 19        | 0.88%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 18        | 0.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 17        | 0.79%   |
| Intel HD Graphics 610                                                                    | 16        | 0.74%   |
| AMD Renoir                                                                               | 16        | 0.74%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 0.7%    |
| AMD ES1000                                                                               | 15        | 0.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 0.65%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 14        | 0.65%   |
| Intel HD Graphics 6000                                                                   | 13        | 0.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 0.6%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 12        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1100      | 51.84%  |
| 1 x AMD         | 308       | 14.51%  |
| 1 x Nvidia      | 162       | 7.63%   |
| 1 x Matrox      | 154       | 7.26%   |
| 1 x ASPEED      | 146       | 6.88%   |
| Other           | 97        | 4.57%   |
| Intel + Nvidia  | 55        | 2.59%   |
| 2 x Intel       | 52        | 2.45%   |
| Intel + AMD     | 15        | 0.71%   |
| AMD + Nvidia    | 9         | 0.42%   |
| 2 x AMD         | 7         | 0.33%   |
| Intel + ASPEED  | 4         | 0.19%   |
| 2 x Nvidia      | 3         | 0.14%   |
| 1 x XGI         | 3         | 0.14%   |
| Nvidia + ASPEED | 3         | 0.14%   |
| 1 x SiS         | 2         | 0.09%   |
| AMD + Matrox    | 1         | 0.05%   |
| AMD + ASPEED    | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1880      | 88.8%   |
| Unknown     | 119       | 5.62%   |
| Proprietary | 118       | 5.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1922      | 90.45%  |
| 1.01-2.0   | 55        | 2.59%   |
| 0.01-0.5   | 39        | 1.84%   |
| 3.01-4.0   | 34        | 1.6%    |
| 7.01-8.0   | 25        | 1.18%   |
| 0.51-1.0   | 25        | 1.18%   |
| 5.01-6.0   | 15        | 0.71%   |
| 8.01-16.0  | 5         | 0.24%   |
| 2.01-3.0   | 4         | 0.19%   |
| 4.01-5.0   | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 62        | 11.23%  |
| LG Display              | 60        | 10.87%  |
| AU Optronics            | 54        | 9.78%   |
| Dell                    | 49        | 8.88%   |
| BOE                     | 43        | 7.79%   |
| Chimei Innolux          | 31        | 5.62%   |
| Goldstar                | 29        | 5.25%   |
| Lenovo                  | 28        | 5.07%   |
| Acer                    | 28        | 5.07%   |
| Hewlett-Packard         | 22        | 3.99%   |
| Ancor Communications    | 20        | 3.62%   |
| Apple                   | 14        | 2.54%   |
| Vizio                   | 9         | 1.63%   |
| ASUSTek Computer        | 9         | 1.63%   |
| ViewSonic               | 8         | 1.45%   |
| Sharp                   | 8         | 1.45%   |
| Sceptre Tech            | 8         | 1.45%   |
| AOC                     | 8         | 1.45%   |
| LG Electronics          | 7         | 1.27%   |
| Chi Mei Optoelectronics | 7         | 1.27%   |
| BenQ                    | 6         | 1.09%   |
| Sony                    | 3         | 0.54%   |
| MSI                     | 3         | 0.54%   |
| LGD                     | 3         | 0.54%   |
| InfoVision              | 3         | 0.54%   |
| HannStar                | 3         | 0.54%   |
| Westinghouse            | 2         | 0.36%   |
| Philips                 | 2         | 0.36%   |
| NEC Computers           | 2         | 0.36%   |
| Insignia                | 2         | 0.36%   |
| IBM                     | 2         | 0.36%   |
| unknown                 | 1         | 0.18%   |
| Toshiba                 | 1         | 0.18%   |
| Tech Concepts           | 1         | 0.18%   |
| SHI                     | 1         | 0.18%   |
| SGT                     | 1         | 0.18%   |
| PANDA                   | 1         | 0.18%   |
| Panasonic               | 1         | 0.18%   |
| LG Philips              | 1         | 0.18%   |
| Lenovo Group Limited    | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 7         | 1.24%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 6         | 1.06%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch          | 5         | 0.88%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch       | 4         | 0.71%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch | 4         | 0.71%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 4         | 0.71%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch              | 4         | 0.71%   |
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                      | 3         | 0.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 3         | 0.53%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                | 3         | 0.53%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 3         | 0.53%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch              | 3         | 0.53%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch              | 3         | 0.53%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                    | 3         | 0.53%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                    | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 3         | 0.53%   |
| BOE LCD Monitor BOE05DA 1366x768 280x160mm 12.7-inch                 | 3         | 0.53%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch         | 3         | 0.53%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch     | 3         | 0.53%   |
| Acer V246HL ACR032E 1920x1080 530x300mm 24.0-inch                    | 3         | 0.53%   |
| Sony TV SNY9C01 1360x768                                             | 2         | 0.35%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 820x350mm 35.1-inch       | 2         | 0.35%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch    | 2         | 0.35%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 300x230mm 14.9-inch  | 2         | 0.35%   |
| Samsung Electronics S27C750 SAM0A60 1920x1080 600x340mm 27.2-inch    | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch | 2         | 0.35%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch         | 2         | 0.35%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch         | 2         | 0.35%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch         | 2         | 0.35%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch         | 2         | 0.35%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x170mm 13.9-inch         | 2         | 0.35%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch          | 2         | 0.35%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch          | 2         | 0.35%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                | 2         | 0.35%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch     | 2         | 0.35%   |
| Goldstar W2246 GSM5784 1920x1080 480x270mm 21.7-inch                 | 2         | 0.35%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 2         | 0.35%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 2         | 0.35%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 2         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 181       | 33.46%  |
| 1366x768 (WXGA)    | 106       | 19.59%  |
| 2560x1440 (QHD)    | 38        | 7.02%   |
| 3840x2160 (4K)     | 35        | 6.47%   |
| 1600x900 (HD+)     | 32        | 5.91%   |
| 1280x800 (WXGA)    | 22        | 4.07%   |
| 1280x1024 (SXGA)   | 18        | 3.33%   |
| 1680x1050 (WSXGA+) | 16        | 2.96%   |
| 1920x1200 (WUXGA)  | 15        | 2.77%   |
| 2560x1080          | 11        | 2.03%   |
| 1440x900 (WXGA+)   | 10        | 1.85%   |
| 3440x1440          | 9         | 1.66%   |
| 2256x1504          | 7         | 1.29%   |
| 1360x768           | 7         | 1.29%   |
| 2560x1600          | 5         | 0.92%   |
| 1024x768 (XGA)     | 5         | 0.92%   |
| 1024x600           | 5         | 0.92%   |
| Unknown            | 4         | 0.74%   |
| 3840x1600          | 2         | 0.37%   |
| 3200x1800 (QHD+)   | 2         | 0.37%   |
| 1600x1200          | 2         | 0.37%   |
| 5760x2160          | 1         | 0.18%   |
| 5760x1080          | 1         | 0.18%   |
| 4480x1080          | 1         | 0.18%   |
| 3840x1080          | 1         | 0.18%   |
| 2880x1620          | 1         | 0.18%   |
| 2806x900           | 1         | 0.18%   |
| 1920x540           | 1         | 0.18%   |
| 1920x1920          | 1         | 0.18%   |
| 1400x1050          | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 106       | 19.24%  |
| 13      | 92        | 16.7%   |
| 24      | 50        | 9.07%   |
| 27      | 44        | 7.99%   |
| Unknown | 28        | 5.08%   |
| 12      | 26        | 4.72%   |
| 31      | 25        | 4.54%   |
| 17      | 24        | 4.36%   |
| 19      | 23        | 4.17%   |
| 23      | 21        | 3.81%   |
| 21      | 18        | 3.27%   |
| 14      | 17        | 3.09%   |
| 11      | 15        | 2.72%   |
| 34      | 11        | 2%      |
| 22      | 8         | 1.45%   |
| 29      | 7         | 1.27%   |
| 20      | 5         | 0.91%   |
| 64      | 4         | 0.73%   |
| 18      | 4         | 0.73%   |
| 26      | 3         | 0.54%   |
| 37      | 2         | 0.36%   |
| 35      | 2         | 0.36%   |
| 16      | 2         | 0.36%   |
| 10      | 2         | 0.36%   |
| 9       | 2         | 0.36%   |
| 54      | 1         | 0.18%   |
| 52      | 1         | 0.18%   |
| 49      | 1         | 0.18%   |
| 42      | 1         | 0.18%   |
| 41      | 1         | 0.18%   |
| 39      | 1         | 0.18%   |
| 32      | 1         | 0.18%   |
| 28      | 1         | 0.18%   |
| 25      | 1         | 0.18%   |
| 8       | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 177       | 32.84%  |
| 501-600     | 105       | 19.48%  |
| 201-300     | 91        | 16.88%  |
| 401-500     | 50        | 9.28%   |
| 601-700     | 38        | 7.05%   |
| Unknown     | 28        | 5.19%   |
| 351-400     | 21        | 3.9%    |
| 701-800     | 12        | 2.23%   |
| 1001-1500   | 7         | 1.3%    |
| 801-900     | 5         | 0.93%   |
| 101-200     | 3         | 0.56%   |
| 901-1000    | 2         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 367       | 71.54%  |
| 16/10   | 61        | 11.89%  |
| Unknown | 24        | 4.68%   |
| 21/9    | 20        | 3.9%    |
| 5/4     | 15        | 2.92%   |
| 3/2     | 12        | 2.34%   |
| 4/3     | 9         | 1.75%   |
| 6/5     | 3         | 0.58%   |
| 32/9    | 1         | 0.19%   |
| 1.00    | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 92        | 16.76%  |
| 91-100         | 81        | 14.75%  |
| 201-250        | 79        | 14.39%  |
| 301-350        | 49        | 8.93%   |
| 351-500        | 42        | 7.65%   |
| 151-200        | 28        | 5.1%    |
| Unknown        | 28        | 5.1%    |
| 61-70          | 27        | 4.92%   |
| 101-110        | 27        | 4.92%   |
| 251-300        | 19        | 3.46%   |
| 121-130        | 15        | 2.73%   |
| 51-60          | 14        | 2.55%   |
| 141-150        | 14        | 2.55%   |
| 71-80          | 12        | 2.19%   |
| More than 1000 | 6         | 1.09%   |
| 501-1000       | 6         | 1.09%   |
| 1-40           | 3         | 0.55%   |
| 111-120        | 3         | 0.55%   |
| 41-50          | 2         | 0.36%   |
| 131-140        | 2         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 173       | 32.52%  |
| 121-160       | 145       | 27.26%  |
| 101-120       | 134       | 25.19%  |
| 161-240       | 40        | 7.52%   |
| Unknown       | 28        | 5.26%   |
| More than 240 | 9         | 1.69%   |
| 1-50          | 3         | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1607      | 75.66%  |
| 1     | 452       | 21.28%  |
| 2     | 58        | 2.73%   |
| 3     | 6         | 0.28%   |
| 4     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1684      | 57.26%  |
| Realtek Semiconductor            | 630       | 21.42%  |
| Broadcom                         | 226       | 7.68%   |
| Qualcomm Atheros                 | 135       | 4.59%   |
| Mellanox Technologies            | 35        | 1.19%   |
| Ralink Technology                | 25        | 0.85%   |
| Chelsio Communications           | 21        | 0.71%   |
| IMC Networks                     | 16        | 0.54%   |
| AMD                              | 15        | 0.51%   |
| Marvell Technology Group         | 13        | 0.44%   |
| Ralink                           | 11        | 0.37%   |
| Edimax Technology                | 11        | 0.37%   |
| TP-Link                          | 9         | 0.31%   |
| U-Blox                           | 7         | 0.24%   |
| Solarflare Communications        | 6         | 0.2%    |
| Aquantia                         | 6         | 0.2%    |
| Nvidia                           | 5         | 0.17%   |
| Novatel Wireless                 | 5         | 0.17%   |
| NetGear                          | 5         | 0.17%   |
| MediaTek                         | 5         | 0.17%   |
| Apple                            | 5         | 0.17%   |
| Seeed Technology                 | 4         | 0.14%   |
| QLogic                           | 4         | 0.14%   |
| Google                           | 4         | 0.14%   |
| Emulex                           | 4         | 0.14%   |
| D-Link System                    | 4         | 0.14%   |
| Cisco Systems                    | 3         | 0.1%    |
| ASUSTek Computer                 | 3         | 0.1%    |
| VIA Technologies                 | 2         | 0.07%   |
| Sierra Wireless                  | 2         | 0.07%   |
| Qualcomm Atheros Communications  | 2         | 0.07%   |
| Dell                             | 2         | 0.07%   |
| American Megatrends              | 2         | 0.07%   |
| Accton Technology                | 2         | 0.07%   |
| 3Com                             | 2         | 0.07%   |
| ZyXEL Communications             | 1         | 0.03%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.03%   |
| Xiaomi                           | 1         | 0.03%   |
| Tehuti Networks                  | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 498       | 13.28%  |
| Intel I211 Gigabit Network Connection                                         | 256       | 6.83%   |
| Intel I210 Gigabit Network Connection                                         | 194       | 5.17%   |
| Intel I350 Gigabit Network Connection                                         | 161       | 4.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 142       | 3.79%   |
| Intel 82574L Gigabit Network Connection                                       | 114       | 3.04%   |
| Intel Ethernet Connection I217-LM                                             | 87        | 2.32%   |
| Intel 82580 Gigabit Network Connection                                        | 69        | 1.84%   |
| Intel Ethernet Controller I225-V                                              | 68        | 1.81%   |
| Intel 82583V Gigabit Network Connection                                       | 68        | 1.81%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 61        | 1.63%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 60        | 1.6%    |
| Intel 82576 Gigabit Network Connection                                        | 58        | 1.55%   |
| Intel Wi-Fi 6 AX200                                                           | 57        | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                             | 48        | 1.28%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 45        | 1.2%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 42        | 1.12%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 42        | 1.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 40        | 1.07%   |
| Intel Ethernet Connection (2) I219-LM                                         | 37        | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 34        | 0.91%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 34        | 0.91%   |
| Intel Wireless 8265 / 8275                                                    | 33        | 0.88%   |
| Intel Wireless 7265                                                           | 31        | 0.83%   |
| Intel Wireless 7260                                                           | 31        | 0.83%   |
| Intel Wireless 8260                                                           | 30        | 0.8%    |
| Intel Wireless 3165                                                           | 27        | 0.72%   |
| Intel Ethernet Connection I354                                                | 26        | 0.69%   |
| Intel Ethernet Connection (2) I219-V                                          | 26        | 0.69%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 26        | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 21        | 0.56%   |
| Intel Wireless-AC 9260                                                        | 21        | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 20        | 0.53%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 19        | 0.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 19        | 0.51%   |
| Intel 82579V Gigabit Network Connection                                       | 18        | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                                         | 17        | 0.45%   |
| Intel Ethernet Controller I226-V                                              | 16        | 0.43%   |
| Intel Ethernet Connection X553 1GbE                                           | 16        | 0.43%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 16        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 417       | 53.19%  |
| Qualcomm Atheros                | 115       | 14.67%  |
| Realtek Semiconductor           | 94        | 11.99%  |
| Broadcom                        | 63        | 8.04%   |
| Ralink Technology               | 25        | 3.19%   |
| IMC Networks                    | 16        | 2.04%   |
| Ralink                          | 11        | 1.4%    |
| Edimax Technology               | 11        | 1.4%    |
| TP-Link                         | 9         | 1.15%   |
| NetGear                         | 5         | 0.64%   |
| MediaTek                        | 4         | 0.51%   |
| ASUSTek Computer                | 3         | 0.38%   |
| Sierra Wireless                 | 2         | 0.26%   |
| Qualcomm Atheros Communications | 2         | 0.26%   |
| ZyXEL Communications            | 1         | 0.13%   |
| Marvell Technology Group        | 1         | 0.13%   |
| Linksys                         | 1         | 0.13%   |
| D-Link System                   | 1         | 0.13%   |
| D-Link                          | 1         | 0.13%   |
| Belkin Components               | 1         | 0.13%   |
| AboCom Systems                  | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 57        | 7.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 34        | 4.3%    |
| Intel Wireless 8265 / 8275                                              | 33        | 4.18%   |
| Intel Wireless 7265                                                     | 31        | 3.92%   |
| Intel Wireless 7260                                                     | 31        | 3.92%   |
| Intel Wireless 8260                                                     | 30        | 3.8%    |
| Intel Wireless 3165                                                     | 27        | 3.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 21        | 2.66%   |
| Intel Wireless-AC 9260                                                  | 21        | 2.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 20        | 2.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 19        | 2.41%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 16        | 2.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 15        | 1.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 1.9%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 15        | 1.9%    |
| Ralink RT5370 Wireless Adapter                                          | 14        | 1.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 13        | 1.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 1.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 13        | 1.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 12        | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 1.39%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 11        | 1.39%   |
| Intel Wireless 3160                                                     | 11        | 1.39%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 11        | 1.39%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 11        | 1.39%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 10        | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 1.01%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 8         | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 0.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.89%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 7         | 0.89%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 7         | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1499      | 62.25%  |
| Realtek Semiconductor            | 585       | 24.29%  |
| Broadcom                         | 188       | 7.81%   |
| Qualcomm Atheros                 | 28        | 1.16%   |
| Chelsio Communications           | 18        | 0.75%   |
| AMD                              | 15        | 0.62%   |
| Marvell Technology Group         | 12        | 0.5%    |
| Solarflare Communications        | 6         | 0.25%   |
| Aquantia                         | 6         | 0.25%   |
| Nvidia                           | 5         | 0.21%   |
| Novatel Wireless                 | 5         | 0.21%   |
| QLogic                           | 4         | 0.17%   |
| Emulex                           | 4         | 0.17%   |
| Apple                            | 4         | 0.17%   |
| Google                           | 3         | 0.12%   |
| D-Link System                    | 3         | 0.12%   |
| Cisco Systems                    | 3         | 0.12%   |
| VIA Technologies                 | 2         | 0.08%   |
| American Megatrends              | 2         | 0.08%   |
| 3Com                             | 2         | 0.08%   |
| Xiaomi                           | 1         | 0.04%   |
| Tehuti Networks                  | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Silicom                          | 1         | 0.04%   |
| Samsung Electronics              | 1         | 0.04%   |
| Qualcomm                         | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.04%   |
| National Semiconductor           | 1         | 0.04%   |
| MYRICOM                          | 1         | 0.04%   |
| Lenovo                           | 1         | 0.04%   |
| ICS Advent                       | 1         | 0.04%   |
| Amazon.com                       | 1         | 0.04%   |
| ADMtek                           | 1         | 0.04%   |
| Accton Technology                | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 498       | 17.33%  |
| Intel I211 Gigabit Network Connection                                         | 256       | 8.91%   |
| Intel I210 Gigabit Network Connection                                         | 194       | 6.75%   |
| Intel I350 Gigabit Network Connection                                         | 161       | 5.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 142       | 4.94%   |
| Intel 82574L Gigabit Network Connection                                       | 114       | 3.97%   |
| Intel Ethernet Connection I217-LM                                             | 87        | 3.03%   |
| Intel 82580 Gigabit Network Connection                                        | 69        | 2.4%    |
| Intel Ethernet Controller I225-V                                              | 68        | 2.37%   |
| Intel 82583V Gigabit Network Connection                                       | 68        | 2.37%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 61        | 2.12%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 60        | 2.09%   |
| Intel 82576 Gigabit Network Connection                                        | 58        | 2.02%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 45        | 1.57%   |
| Realtek RTL8125 2.5GbE Controller                                             | 44        | 1.53%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 42        | 1.46%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 42        | 1.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 40        | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                                         | 37        | 1.29%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 34        | 1.18%   |
| Intel Ethernet Connection I354                                                | 26        | 0.9%    |
| Intel Ethernet Connection (2) I219-V                                          | 26        | 0.9%    |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 26        | 0.9%    |
| Intel 82579V Gigabit Network Connection                                       | 18        | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                                         | 17        | 0.59%   |
| Intel Ethernet Controller I226-V                                              | 16        | 0.56%   |
| Intel Ethernet Connection X553 1GbE                                           | 16        | 0.56%   |
| Intel Ethernet Controller X550                                                | 15        | 0.52%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 15        | 0.52%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 15        | 0.52%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 15        | 0.52%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 15        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                                          | 13        | 0.45%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 12        | 0.42%   |
| Intel 82575EB Gigabit Network Connection                                      | 12        | 0.42%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 12        | 0.42%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 11        | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 10        | 0.35%   |
| Intel Ethernet Connection I217-V                                              | 10        | 0.35%   |
| Intel Ethernet Connection (3) I218-LM                                         | 10        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2020      | 71.28%  |
| WiFi     | 730       | 25.76%  |
| Unknown  | 62        | 2.19%   |
| Modem    | 22        | 0.78%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1903      | 84.2%   |
| WiFi     | 348       | 15.4%   |
| Unknown  | 9         | 0.4%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 636       | 29.65%  |
| 4     | 380       | 17.72%  |
| 3     | 292       | 13.61%  |
| 1     | 277       | 12.91%  |
| 6     | 235       | 10.96%  |
| 5     | 162       | 7.55%   |
| 8     | 53        | 2.47%   |
| 7     | 38        | 1.77%   |
| 0     | 22        | 1.03%   |
| 10    | 17        | 0.79%   |
| 9     | 16        | 0.75%   |
| 11    | 5         | 0.23%   |
| 14    | 3         | 0.14%   |
| 12    | 3         | 0.14%   |
| 16    | 2         | 0.09%   |
| 13    | 2         | 0.09%   |
| 20    | 1         | 0.05%   |
| 15    | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1777      | 81.33%  |
| Yes  | 408       | 18.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 304       | 61.29%  |
| Broadcom                        | 41        | 8.27%   |
| Apple                           | 34        | 6.85%   |
| Realtek Semiconductor           | 32        | 6.45%   |
| Qualcomm Atheros Communications | 21        | 4.23%   |
| IMC Networks                    | 21        | 4.23%   |
| Cambridge Silicon Radio         | 10        | 2.02%   |
| Dell                            | 8         | 1.61%   |
| ASUSTek Computer                | 8         | 1.61%   |
| Lite-On Technology              | 5         | 1.01%   |
| Foxconn / Hon Hai               | 5         | 1.01%   |
| MediaTek                        | 2         | 0.4%    |
| Alps Electric                   | 2         | 0.4%    |
| Realtek                         | 1         | 0.2%    |
| Hewlett-Packard                 | 1         | 0.2%    |
| Dynex                           | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 129       | 25.96%  |
| Intel AX200 Bluetooth                                       | 51        | 10.26%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 37        | 7.44%   |
| Intel AX201 Bluetooth                                       | 24        | 4.83%   |
| Realtek  Bluetooth 4.2 Adapter                              | 20        | 4.02%   |
| Intel Wireless-AC 3168 Bluetooth                            | 20        | 4.02%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 19        | 3.82%   |
| Apple Bluetooth Host Controller                             | 17        | 3.42%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 14        | 2.82%   |
| Intel AX210 Bluetooth                                       | 12        | 2.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 10        | 2.01%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 10        | 2.01%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 9         | 1.81%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 8         | 1.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 7         | 1.41%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 6         | 1.21%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 5         | 1.01%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 5         | 1.01%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 4         | 0.8%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 4         | 0.8%    |
| IMC Networks Realtek Bluetooth Adapter                      | 4         | 0.8%    |
| Dell DW375 Bluetooth Module                                 | 4         | 0.8%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 4         | 0.8%    |
| Realtek  Bluetooth Adapter                                  | 3         | 0.6%    |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 3         | 0.6%    |
| Apple Built-in iSight (no firmware loaded)                  | 3         | 0.6%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 2         | 0.4%    |
| Realtek RTL8821A Bluetooth                                  | 2         | 0.4%    |
| Realtek  Bluetooth 4.0 Adapter                              | 2         | 0.4%    |
| Realtek Bluetooth Radio                                     | 2         | 0.4%    |
| Qualcomm Atheros  QCA61x4 Bluetooth 4.1                     | 2         | 0.4%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 0.4%    |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 2         | 0.4%    |
| MediaTek Wireless_Device                                    | 2         | 0.4%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 2         | 0.4%    |
| Lite-On Bluetooth USB Module                                | 2         | 0.4%    |
| Intel Intel Wireless Bluetooth                              | 2         | 0.4%    |
| IMC Networks Wireless_Device                                | 2         | 0.4%    |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 2         | 0.4%    |
| IMC Networks Bluetooth module                               | 2         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1187      | 64.93%  |
| AMD                                  | 372       | 20.35%  |
| Nvidia                               | 177       | 9.68%   |
| C-Media Electronics                  | 26        | 1.42%   |
| Creative Labs                        | 12        | 0.66%   |
| SteelSeries ApS                      | 6         | 0.33%   |
| Blue Microphones                     | 5         | 0.27%   |
| Realtek Semiconductor                | 4         | 0.22%   |
| Logitech                             | 4         | 0.22%   |
| Texas Instruments                    | 3         | 0.16%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.11%   |
| Lenovo                               | 2         | 0.11%   |
| Google                               | 2         | 0.11%   |
| Corsair                              | 2         | 0.11%   |
| Cambridge Silicon Radio              | 2         | 0.11%   |
| Yamaha                               | 1         | 0.05%   |
| XMOS                                 | 1         | 0.05%   |
| VIA Technologies                     | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.05%   |
| Tenx Technology                      | 1         | 0.05%   |
| Razer USA                            | 1         | 0.05%   |
| Quanta                               | 1         | 0.05%   |
| Nektar                               | 1         | 0.05%   |
| LG Electronics                       | 1         | 0.05%   |
| KORG                                 | 1         | 0.05%   |
| Kingston Technology                  | 1         | 0.05%   |
| JMTek                                | 1         | 0.05%   |
| Genesys Logic                        | 1         | 0.05%   |
| Focusrite-Novation                   | 1         | 0.05%   |
| ESS Technology                       | 1         | 0.05%   |
| Creative Technology                  | 1         | 0.05%   |
| CMX Systems                          | 1         | 0.05%   |
| Cirrus Logic                         | 1         | 0.05%   |
| ASUSTek Computer                     | 1         | 0.05%   |
| Astro Gaming                         | 1         | 0.05%   |
| Apple                                | 1         | 0.05%   |
| AKAI  Professional M.I.              | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 130       | 5.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 120       | 5.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 103       | 4.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 102       | 4.57%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 101       | 4.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 95        | 4.26%   |
| AMD FCH Azalia Controller                                                                         | 75        | 3.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 72        | 3.23%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 67        | 3%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 66        | 2.96%   |
| Intel Cannon Lake PCH cAVS                                                                        | 50        | 2.24%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 48        | 2.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 47        | 2.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 47        | 2.11%   |
| Intel Broadwell-U Audio Controller                                                                | 44        | 1.97%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 43        | 1.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 42        | 1.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 42        | 1.88%   |
| Intel 200 Series PCH HD Audio                                                                     | 37        | 1.66%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 35        | 1.57%   |
| Intel 8 Series HD Audio Controller                                                                | 35        | 1.57%   |
| Intel Jasper Lake HD Audio                                                                        | 33        | 1.48%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 33        | 1.48%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 32        | 1.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 32        | 1.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 27        | 1.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 26        | 1.17%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 25        | 1.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 24        | 1.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 22        | 0.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 18        | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 17        | 0.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 16        | 0.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 0.63%   |
| Intel Comet Lake PCH cAVS                                                                         | 14        | 0.63%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 14        | 0.63%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 14        | 0.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 0.58%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 13        | 0.58%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 12        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 430       | 19.17%  |
| SK hynix                                | 357       | 15.92%  |
| Micron Technology                       | 234       | 10.43%  |
| Crucial                                 | 234       | 10.43%  |
| Kingston                                | 203       | 9.05%   |
| Unknown                                 | 202       | 9.01%   |
| G.Skill                                 | 102       | 4.55%   |
| Corsair                                 | 89        | 3.97%   |
| Unknown                                 | 51        | 2.27%   |
| Unknown (ABCD)                          | 34        | 1.52%   |
| Transcend                               | 31        | 1.38%   |
| Team                                    | 27        | 1.2%    |
| Nanya Technology                        | 25        | 1.11%   |
| A-DATA Technology                       | 24        | 1.07%   |
| Ramaxel Technology                      | 22        | 0.98%   |
| Patriot                                 | 22        | 0.98%   |
| PNY                                     | 20        | 0.89%   |
| Elpida                                  | 15        | 0.67%   |
| Toshiba                                 | 11        | 0.49%   |
| Kimtigo                                 | 11        | 0.49%   |
| Super Talent                            | 10        | 0.45%   |
| Timetec                                 | 8         | 0.36%   |
| Avant                                   | 6         | 0.27%   |
| Silicon Power                           | 5         | 0.22%   |
| Sesame                                  | 4         | 0.18%   |
| Innodisk                                | 4         | 0.18%   |
| Patriot Memory (PDP Systems)            | 3         | 0.13%   |
| Neo Forza                               | 3         | 0.13%   |
| Hewlett-Packard                         | 3         | 0.13%   |
| Goldkey                                 | 3         | 0.13%   |
| GeIL                                    | 3         | 0.13%   |
| Apacer                                  | 3         | 0.13%   |
| Silicon Power Computer & Communications | 2         | 0.09%   |
| Qimonda                                 | 2         | 0.09%   |
| HPE                                     | 2         | 0.09%   |
| GSkill                                  | 2         | 0.09%   |
| Golden Empire                           | 2         | 0.09%   |
| Vasekey                                 | 1         | 0.04%   |
| V-Color                                 | 1         | 0.04%   |
| Unknown (0B38)                          | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 51        | 2.12%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 31        | 1.29%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 22        | 0.91%   |
| Unknown RAM Module 8GB 1600MT/s                              | 15        | 0.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 15        | 0.62%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 15        | 0.62%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 13        | 0.54%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 13        | 0.54%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 13        | 0.54%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 12        | 0.5%    |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s          | 12        | 0.5%    |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s         | 12        | 0.5%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 11        | 0.46%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 11        | 0.46%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 11        | 0.46%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 11        | 0.46%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 11        | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 10        | 0.42%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s        | 10        | 0.42%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 9         | 0.37%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s          | 9         | 0.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 9         | 0.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s          | 9         | 0.37%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s        | 8         | 0.33%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 8         | 0.33%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 8         | 0.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s        | 8         | 0.33%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s          | 8         | 0.33%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s        | 8         | 0.33%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s        | 8         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 7         | 0.29%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 7         | 0.29%   |
| Samsung RAM M471A4G43MB1-CTD 0kB SODIMM DDR4 2667MT/s        | 7         | 0.29%   |
| Samsung RAM M391B5273DH0-CK0 4GB DIMM DDR3 1600MT/s          | 7         | 0.29%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s         | 7         | 0.29%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 7         | 0.29%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                   | 6         | 0.25%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s         | 6         | 0.25%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 6         | 0.25%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 6         | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 1000      | 51.02%  |
| DDR4    | 744       | 37.96%  |
| DDR2    | 79        | 4.03%   |
| Unknown | 47        | 2.4%    |
| LPDDR4  | 43        | 2.19%   |
| DDR     | 15        | 0.77%   |
| LPDDR3  | 14        | 0.71%   |
| SDRAM   | 12        | 0.61%   |
| LPDDR5  | 3         | 0.15%   |
| DRAM    | 2         | 0.1%    |
| SRAM    | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 1132      | 57.81%  |
| SODIMM       | 750       | 38.3%   |
| Unknown      | 33        | 1.69%   |
| Row Of Chips | 23        | 1.17%   |
| Chip         | 9         | 0.46%   |
| FB-DIMM      | 8         | 0.41%   |
| RIMM         | 3         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 807       | 38.21%  |
| 4096   | 679       | 32.15%  |
| 16384  | 293       | 13.87%  |
| 2048   | 224       | 10.61%  |
| 32768  | 58        | 2.75%   |
| 1024   | 41        | 1.94%   |
| 512    | 6         | 0.28%   |
| 65536  | 2         | 0.09%   |
| 131072 | 1         | 0.05%   |
| 256    | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 674       | 32.1%   |
| 1333    | 281       | 13.38%  |
| 2400    | 256       | 12.19%  |
| 2133    | 178       | 8.48%   |
| 2667    | 172       | 8.19%   |
| 3200    | 140       | 6.67%   |
| 800     | 55        | 2.62%   |
| 667     | 50        | 2.38%   |
| 2666    | 46        | 2.19%   |
| 1334    | 34        | 1.62%   |
| 1066    | 33        | 1.57%   |
| 1867    | 32        | 1.52%   |
| 1067    | 28        | 1.33%   |
| Unknown | 22        | 1.05%   |
| 3000    | 21        | 1%      |
| 3600    | 19        | 0.9%    |
| 2933    | 11        | 0.52%   |
| 1866    | 10        | 0.48%   |
| 533     | 10        | 0.48%   |
| 4267    | 4         | 0.19%   |
| 975     | 4         | 0.19%   |
| 6400    | 3         | 0.14%   |
| 400     | 3         | 0.14%   |
| 1400    | 2         | 0.1%    |
| 1200    | 2         | 0.1%    |
| 4800    | 1         | 0.05%   |
| 4266    | 1         | 0.05%   |
| 4133    | 1         | 0.05%   |
| 3534    | 1         | 0.05%   |
| 3333    | 1         | 0.05%   |
| 2134    | 1         | 0.05%   |
| 1639    | 1         | 0.05%   |
| 266     | 1         | 0.05%   |
| 200     | 1         | 0.05%   |
| 166     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 2         | 28.57%  |
| Brother Industries    | 2         | 28.57%  |
| Prolific Technology   | 1         | 14.29%  |
| Lexmark International | 1         | 14.29%  |
| Apple                 | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                            | 1         | 12.5%   |
| Lexmark International Lexmark MS710 Print                                | 1         | 12.5%   |
| HP PNP Fax Null                                                          | 1         | 12.5%   |
| HP LaserJet 1012                                                         | 1         | 12.5%   |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer | 1         | 12.5%   |
| Brother MFC-L2685DW                                                      | 1         | 12.5%   |
| Brother MFC-J485DW                                                       | 1         | 12.5%   |
| Apple Gamesir-G3s 2.10                                                   | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP ScanJet 5300c/5370c | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 80        | 26.14%  |
| Acer                                   | 31        | 10.13%  |
| Microdia                               | 27        | 8.82%   |
| Realtek Semiconductor                  | 24        | 7.84%   |
| IMC Networks                           | 22        | 7.19%   |
| Logitech                               | 21        | 6.86%   |
| Sunplus Innovation Technology          | 17        | 5.56%   |
| Apple                                  | 11        | 3.59%   |
| Quanta                                 | 10        | 3.27%   |
| Suyin                                  | 9         | 2.94%   |
| Lite-On Technology                     | 8         | 2.61%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.61%   |
| Luxvisions Innotech Limited            | 7         | 2.29%   |
| Lenovo                                 | 5         | 1.63%   |
| Syntek                                 | 3         | 0.98%   |
| Importek                               | 3         | 0.98%   |
| WCM_USB                                | 2         | 0.65%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.65%   |
| Ricoh                                  | 2         | 0.65%   |
| Primax Electronics                     | 2         | 0.65%   |
| OmniVision Technologies                | 2         | 0.65%   |
| Alcor Micro                            | 2         | 0.65%   |
| Xiongmai                               | 1         | 0.33%   |
| Unknown                                | 1         | 0.33%   |
| Silicon Motion                         | 1         | 0.33%   |
| Intel                                  | 1         | 0.33%   |
| Generalplus Technology                 | 1         | 0.33%   |
| Arkmicro Technologies                  | 1         | 0.33%   |
| ARC International                      | 1         | 0.33%   |
| ALi                                    | 1         | 0.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 26        | 8.39%   |
| Acer Integrated Camera                              | 17        | 5.48%   |
| Realtek Integrated_Webcam_HD                        | 8         | 2.58%   |
| Microdia Integrated Webcam                          | 8         | 2.58%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 8         | 2.58%   |
| Logitech HD Pro Webcam C920                         | 7         | 2.26%   |
| Apple FaceTime HD Camera                            | 7         | 2.26%   |
| Sunplus Integrated_Webcam_HD                        | 6         | 1.94%   |
| Lite-On Integrated Camera                           | 6         | 1.94%   |
| Chicony Integrated Camera [ThinkPad]                | 6         | 1.94%   |
| Chicony Integrated Camera (1280x720@30)             | 6         | 1.94%   |
| Realtek Realtek USB2.0 PC Camera                    | 5         | 1.61%   |
| Logitech Webcam C270                                | 5         | 1.61%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 1.61%   |
| IMC Networks Integrated Camera                      | 5         | 1.61%   |
| Acer ThinkPad Integrated Camera                     | 5         | 1.61%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 4         | 1.29%   |
| Microdia Webcam Vitade AF                           | 4         | 1.29%   |
| Microdia Dell Laptop Integrated Webcam HD           | 4         | 1.29%   |
| Lenovo Integrated Webcam [R5U877]                   | 4         | 1.29%   |
| Chicony HD WebCam                                   | 4         | 1.29%   |
| Suyin Integrated_Webcam_HD                          | 3         | 0.97%   |
| Sunplus HD WebCam                                   | 3         | 0.97%   |
| Realtek Laptop Camera                               | 3         | 0.97%   |
| Quanta HP Webcam                                    | 3         | 0.97%   |
| Quanta HP TrueVision HD Camera                      | 3         | 0.97%   |
| Microdia Integrated_Webcam_HD                       | 3         | 0.97%   |
| Luxvisions Innotech Limited Integrated Camera       | 3         | 0.97%   |
| Logitech C922 Pro Stream Webcam                     | 3         | 0.97%   |
| IMC Networks UVC VGA Webcam                         | 3         | 0.97%   |
| IMC Networks EasyCamera                             | 3         | 0.97%   |
| Chicony Chicony USB2.0 Camera                       | 3         | 0.97%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 0.97%   |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 0.97%   |
| Acer Lenovo EasyCamera                              | 3         | 0.97%   |
| WCM_USB WEB CAM                                     | 2         | 0.65%   |
| Syntek Lenovo EasyCamera                            | 2         | 0.65%   |
| Suyin Acer CrystalEye Webcam                        | 2         | 0.65%   |
| Sunplus Dell E5570 integrated webcam                | 2         | 0.65%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960      | 2         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 27        | 36%     |
| Synaptics                  | 13        | 17.33%  |
| Upek                       | 11        | 14.67%  |
| STMicroelectronics         | 10        | 13.33%  |
| Shenzhen Goodix Technology | 5         | 6.67%   |
| AuthenTec                  | 5         | 6.67%   |
| Samsung Electronics        | 1         | 1.33%   |
| Focal-systems.Corp         | 1         | 1.33%   |
| Elan Microelectronics      | 1         | 1.33%   |
| Broadcom                   | 1         | 1.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 13        | 17.33%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 11        | 14.67%  |
| STMicroelectronics Fingerprint Reader                                        | 10        | 13.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 5         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 5         | 6.67%   |
| Shenzhen Goodix Fingerprint Reader                                           | 5         | 6.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 4%      |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 4%      |
| Validity Sensors Synaptics WBDI                                              | 3         | 4%      |
| AuthenTec AuthenTec Inc. AES1660                                             | 2         | 2.67%   |
| AuthenTec AES2810                                                            | 2         | 2.67%   |
| Unknown                                                                      | 2         | 2.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 1.33%   |
| Validity Sensors VFS491                                                      | 1         | 1.33%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 1.33%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 1.33%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 1.33%   |
| Synaptics product 0x00be                                                     | 1         | 1.33%   |
| Samsung Fingerprint Sensor Device - 730B                                     | 1         | 1.33%   |
| Focal-systems.Corp FocalTech Fingerprint reader                              | 1         | 1.33%   |
| Elan ELAN WBF Fingerprint Sensor                                             | 1         | 1.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 1.33%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 1.33%   |

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
| 1     | 812       | 37.3%   |
| 0     | 692       | 31.79%  |
| 2     | 439       | 20.17%  |
| 3     | 168       | 7.72%   |
| 4     | 48        | 2.2%    |
| 5     | 12        | 0.55%   |
| 6     | 5         | 0.23%   |
| 7     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1227      | 59.65%  |
| Bluetooth                | 210       | 10.21%  |
| Net/wireless             | 206       | 10.01%  |
| Card reader              | 117       | 5.69%   |
| Firewire controller      | 82        | 3.99%   |
| Fingerprint reader       | 62        | 3.01%   |
| Net/ethernet             | 39        | 1.9%    |
| Sound                    | 36        | 1.75%   |
| Network                  | 32        | 1.56%   |
| Graphics card            | 20        | 0.97%   |
| Storage                  | 9         | 0.44%   |
| Modem                    | 6         | 0.29%   |
| Storage/raid             | 3         | 0.15%   |
| Storage/ata              | 3         | 0.15%   |
| Dvb card                 | 3         | 0.15%   |
| Storage/ide              | 2         | 0.1%    |

