BSD in Canada - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Canada.

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

Total: 286

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Protectli     | FW4B Ver                    | [cfaeaeb2f2](https://bsd-hardware.info/?probe=cfaeaeb2f2) | Nov 29, 2022 |
| Protectli     | FW4B Ver                    | [e8e158f783](https://bsd-hardware.info/?probe=e8e158f783) | Nov 27, 2022 |
| Unknown       | Unknown                     | [512a05eefb](https://bsd-hardware.info/?probe=512a05eefb) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [5f0b8df8d0](https://bsd-hardware.info/?probe=5f0b8df8d0) | Nov 27, 2022 |
| Unknown       | Unknown                     | [222e69ff59](https://bsd-hardware.info/?probe=222e69ff59) | Nov 26, 2022 |
| Protectli     | FW6                         | [74510f3177](https://bsd-hardware.info/?probe=74510f3177) | Nov 25, 2022 |
| HP            | 8055                        | [ace4570d15](https://bsd-hardware.info/?probe=ace4570d15) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | [7258992b77](https://bsd-hardware.info/?probe=7258992b77) | Nov 24, 2022 |
| ASUSTek       | M5A97 PLUS                  | [7c7a121711](https://bsd-hardware.info/?probe=7c7a121711) | Nov 18, 2022 |
| Intel         | SHARKBAY                    | [5875ecec9f](https://bsd-hardware.info/?probe=5875ecec9f) | Nov 18, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [0d37f1878b](https://bsd-hardware.info/?probe=0d37f1878b) | Nov 17, 2022 |
| AZW           | U59                         | [25e1349c5f](https://bsd-hardware.info/?probe=25e1349c5f) | Nov 17, 2022 |
| Lenovo        | 30D9 No DPK                 | [bb9cf416c4](https://bsd-hardware.info/?probe=bb9cf416c4) | Nov 11, 2022 |
| ASUSTek       | P8H77-I                     | [04ea3cc97d](https://bsd-hardware.info/?probe=04ea3cc97d) | Nov 09, 2022 |
| Dell          | 09KPNV A01                  | [32331d772c](https://bsd-hardware.info/?probe=32331d772c) | Nov 08, 2022 |
| Datto         | SSD                         | [235483110d](https://bsd-hardware.info/?probe=235483110d) | Nov 05, 2022 |
| Cisco         | ASA5512 A0                  | [871a5c449f](https://bsd-hardware.info/?probe=871a5c449f) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | [5758027775](https://bsd-hardware.info/?probe=5758027775) | Oct 31, 2022 |
| Protectli     | FW4B Ver                    | [6dda683e10](https://bsd-hardware.info/?probe=6dda683e10) | Oct 28, 2022 |
| HP            | 18E4                        | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [c3f0ae254e](https://bsd-hardware.info/?probe=c3f0ae254e) | Oct 17, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [b4e02e3f51](https://bsd-hardware.info/?probe=b4e02e3f51) | Oct 16, 2022 |
| Unknown       | Unknown                     | [00b5fa7a4e](https://bsd-hardware.info/?probe=00b5fa7a4e) | Oct 13, 2022 |
| ASRock        | B450M Pro4-F                | [edead8a3ae](https://bsd-hardware.info/?probe=edead8a3ae) | Oct 11, 2022 |
| Dell          | 04YP6J A01                  | [ce728798a1](https://bsd-hardware.info/?probe=ce728798a1) | Oct 07, 2022 |
| ASUSTek       | P8B75-M                     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| Unknown       | Unknown                     | [79060c241b](https://bsd-hardware.info/?probe=79060c241b) | Oct 03, 2022 |
| Techvision    | TVI7309X B0                 | [33b252016c](https://bsd-hardware.info/?probe=33b252016c) | Sep 26, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [a1a2cbc6c9](https://bsd-hardware.info/?probe=a1a2cbc6c9) | Sep 20, 2022 |
| CncTion       | N5105-4L B0                 | [22f23ccfa5](https://bsd-hardware.info/?probe=22f23ccfa5) | Sep 17, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [21e7190ff2](https://bsd-hardware.info/?probe=21e7190ff2) | Sep 11, 2022 |
| ASUSTek       | M5A97 PLUS                  | [3c152ae7bd](https://bsd-hardware.info/?probe=3c152ae7bd) | Sep 11, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [89b185547b](https://bsd-hardware.info/?probe=89b185547b) | Sep 10, 2022 |
| Intel         | MAHOBAY                     | [a854e50942](https://bsd-hardware.info/?probe=a854e50942) | Sep 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [860518eb18](https://bsd-hardware.info/?probe=860518eb18) | Sep 04, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [b53e1d28cd](https://bsd-hardware.info/?probe=b53e1d28cd) | Sep 04, 2022 |
| Intel         | DQ67EP AAG12529-307         | [1fb1fd6705](https://bsd-hardware.info/?probe=1fb1fd6705) | Sep 03, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [2e4b87acd2](https://bsd-hardware.info/?probe=2e4b87acd2) | Sep 03, 2022 |
| Protectli     | FW4B Ver                    | [b3a1456bb4](https://bsd-hardware.info/?probe=b3a1456bb4) | Aug 29, 2022 |
| Gigabyte      | MBHM87P-00                  | [9fa5160871](https://bsd-hardware.info/?probe=9fa5160871) | Aug 22, 2022 |
| Dell          | 04Y8V0 A02                  | [9fc4b3c63e](https://bsd-hardware.info/?probe=9fc4b3c63e) | Aug 17, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [753f277d5c](https://bsd-hardware.info/?probe=753f277d5c) | Aug 16, 2022 |
| AZW           | Green G1                    | [4bccb24702](https://bsd-hardware.info/?probe=4bccb24702) | Aug 15, 2022 |
| Dell          | 04Y8V0 A02                  | [a21172360d](https://bsd-hardware.info/?probe=a21172360d) | Aug 15, 2022 |
| Dell          | 04Y8V0 A02                  | [6acccc63ff](https://bsd-hardware.info/?probe=6acccc63ff) | Aug 15, 2022 |
| Lenovo        | 3111 SDK0J40705 WIN 3425... | [6927813b1d](https://bsd-hardware.info/?probe=6927813b1d) | Aug 13, 2022 |
| Lenovo        | SDK0E50510 WIN              | [a45977c76b](https://bsd-hardware.info/?probe=a45977c76b) | Aug 10, 2022 |
| Dell          | 09KPNV A01                  | [236cd1ee65](https://bsd-hardware.info/?probe=236cd1ee65) | Aug 08, 2022 |
| Biostar       | TA880GU3+                   | [8b0c8541b3](https://bsd-hardware.info/?probe=8b0c8541b3) | Aug 06, 2022 |
| MSI           | 785GT-E63                   | [8c307fb033](https://bsd-hardware.info/?probe=8c307fb033) | Aug 03, 2022 |
| Dell          | 0XHGV1 A00                  | [860b06cb6b](https://bsd-hardware.info/?probe=860b06cb6b) | Aug 01, 2022 |
| HP            | 8055                        | [6a8a361dae](https://bsd-hardware.info/?probe=6a8a361dae) | Jul 31, 2022 |
| Dell          | 0TTDMJ A00                  | [900c62c2ba](https://bsd-hardware.info/?probe=900c62c2ba) | Jul 30, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [27b986a422](https://bsd-hardware.info/?probe=27b986a422) | Jul 30, 2022 |
| HP            | 8055                        | [41d802a80a](https://bsd-hardware.info/?probe=41d802a80a) | Jul 29, 2022 |
| ASUSTek       | M5A97 PLUS                  | [7be6ba0021](https://bsd-hardware.info/?probe=7be6ba0021) | Jul 29, 2022 |
| HP            | 18E9                        | [56460b095e](https://bsd-hardware.info/?probe=56460b095e) | Jul 27, 2022 |
| Lenovo        | SHARKBAY NOK                | [1ed99ad502](https://bsd-hardware.info/?probe=1ed99ad502) | Jul 20, 2022 |
| Dell          | 0WR7PY A03                  | [46a6f4e8f3](https://bsd-hardware.info/?probe=46a6f4e8f3) | Jul 19, 2022 |
| Lenovo        | ThinkCentre M91 4518E4U     | [8dd1034cfa](https://bsd-hardware.info/?probe=8dd1034cfa) | Jul 16, 2022 |
| AZW           | Green G1                    | [9a2120ae5a](https://bsd-hardware.info/?probe=9a2120ae5a) | Jul 14, 2022 |
| Datto         | SSD                         | [639d28d449](https://bsd-hardware.info/?probe=639d28d449) | Jul 08, 2022 |
| Protectli     | FW6                         | [e82838534b](https://bsd-hardware.info/?probe=e82838534b) | Jul 06, 2022 |
| Protectli     | FW6 Ver                     | [ac861b1ee3](https://bsd-hardware.info/?probe=ac861b1ee3) | Jun 25, 2022 |
| Protectli     | FW6 Ver                     | [598ecb5457](https://bsd-hardware.info/?probe=598ecb5457) | Jun 25, 2022 |
| HP            | 82A2                        | [77c244bd43](https://bsd-hardware.info/?probe=77c244bd43) | Jun 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a57a2f609c](https://bsd-hardware.info/?probe=a57a2f609c) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [1febab0774](https://bsd-hardware.info/?probe=1febab0774) | Jun 12, 2022 |
| HP            | 1998                        | [1bb67075dd](https://bsd-hardware.info/?probe=1bb67075dd) | Jun 12, 2022 |
| Apple         | Mac-F221BEC8                | [5054729300](https://bsd-hardware.info/?probe=5054729300) | Jun 11, 2022 |
| HP            | 1998                        | [54a6daf0a6](https://bsd-hardware.info/?probe=54a6daf0a6) | Jun 11, 2022 |
| Acer          | EM61SM/EM61PM               | [3b8d6cb36e](https://bsd-hardware.info/?probe=3b8d6cb36e) | Jun 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [26cd129290](https://bsd-hardware.info/?probe=26cd129290) | Jun 06, 2022 |
| Dell          | 0HHV7N A00                  | [f3c197bdfb](https://bsd-hardware.info/?probe=f3c197bdfb) | Jun 04, 2022 |
| ASUSTek       | M5A97 PLUS                  | [8e8ef96421](https://bsd-hardware.info/?probe=8e8ef96421) | Jun 04, 2022 |
| Dell          | 02YYK5 A01                  | [dce99bec81](https://bsd-hardware.info/?probe=dce99bec81) | Jun 03, 2022 |
| ASUSTek       | M5A97 PLUS                  | [8ca71ddf4d](https://bsd-hardware.info/?probe=8ca71ddf4d) | Jun 02, 2022 |
| ASUSTek       | M5A97 PLUS                  | [9d5edd9fa9](https://bsd-hardware.info/?probe=9d5edd9fa9) | May 29, 2022 |
| Dell          | 0M3F6C A01                  | [21d45bc75d](https://bsd-hardware.info/?probe=21d45bc75d) | May 23, 2022 |
| ASUSTek       | PRIME B250M-C               | [c956536edd](https://bsd-hardware.info/?probe=c956536edd) | May 23, 2022 |
| Dell          | 0HHV7N A00                  | [6d7475e9c9](https://bsd-hardware.info/?probe=6d7475e9c9) | May 22, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [963fa158b5](https://bsd-hardware.info/?probe=963fa158b5) | May 22, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [1014f7f61c](https://bsd-hardware.info/?probe=1014f7f61c) | May 18, 2022 |
| Dell          | 0DXJD9 A01                  | [be13c9069c](https://bsd-hardware.info/?probe=be13c9069c) | May 18, 2022 |
| ASUSTek       | PRIME B250M-C               | [9ec22ea24c](https://bsd-hardware.info/?probe=9ec22ea24c) | May 17, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [30cfcd5004](https://bsd-hardware.info/?probe=30cfcd5004) | May 15, 2022 |
| Protectli     | FW4B Ver                    | [9af60bd6e4](https://bsd-hardware.info/?probe=9af60bd6e4) | May 14, 2022 |
| ASUSTek       | M5A97 PLUS                  | [fd066b2db9](https://bsd-hardware.info/?probe=fd066b2db9) | May 14, 2022 |
| Unknown       | Unknown                     | [0958a64385](https://bsd-hardware.info/?probe=0958a64385) | May 12, 2022 |
| Unknown       | Unknown                     | [0d62d4e3cd](https://bsd-hardware.info/?probe=0d62d4e3cd) | May 09, 2022 |
| Gigabyte      | F2A68HM-H                   | [daed3f9401](https://bsd-hardware.info/?probe=daed3f9401) | May 06, 2022 |
| ASUSTek       | H81M-E                      | [cf2f288b93](https://bsd-hardware.info/?probe=cf2f288b93) | May 04, 2022 |
| HP            | 1495                        | [6e0f1cc72e](https://bsd-hardware.info/?probe=6e0f1cc72e) | Apr 29, 2022 |
| HP            | 1998                        | [1244e0583b](https://bsd-hardware.info/?probe=1244e0583b) | Apr 27, 2022 |
| Unknown       | Unknown                     | [b3d5defed1](https://bsd-hardware.info/?probe=b3d5defed1) | Apr 26, 2022 |
| Unknown       | Unknown                     | [4166c67369](https://bsd-hardware.info/?probe=4166c67369) | Apr 20, 2022 |
| Dell          | G5 5090                     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| Unknown       | Unknown                     | [979e868c51](https://bsd-hardware.info/?probe=979e868c51) | Apr 16, 2022 |
| Dell          | 0DXJD9 A01                  | [4023d86091](https://bsd-hardware.info/?probe=4023d86091) | Apr 15, 2022 |
| ASRock        | J3455B-ITX                  | [29be552d6a](https://bsd-hardware.info/?probe=29be552d6a) | Apr 15, 2022 |
| Unknown       | Unknown                     | [1173feae11](https://bsd-hardware.info/?probe=1173feae11) | Apr 13, 2022 |
| Dell          | 0DXJD9 A01                  | [6dac56f3bb](https://bsd-hardware.info/?probe=6dac56f3bb) | Apr 11, 2022 |
| Dell          | 0WR7PY A03                  | [641d1574ce](https://bsd-hardware.info/?probe=641d1574ce) | Apr 11, 2022 |
| PC Engines    | APU                         | [e266947055](https://bsd-hardware.info/?probe=e266947055) | Mar 29, 2022 |
| Unknown       | Unknown                     | [ef1a743845](https://bsd-hardware.info/?probe=ef1a743845) | Mar 28, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [1176fca4ab](https://bsd-hardware.info/?probe=1176fca4ab) | Mar 27, 2022 |
| Unknown       | Unknown                     | [d0e7b62eda](https://bsd-hardware.info/?probe=d0e7b62eda) | Mar 25, 2022 |
| Protectli     | FW4B Ver                    | [cf576c571d](https://bsd-hardware.info/?probe=cf576c571d) | Mar 22, 2022 |
| HP            | 213D A01                    | [6baba4f9c1](https://bsd-hardware.info/?probe=6baba4f9c1) | Mar 20, 2022 |
| ASUSTek       | P8Z68-V LE                  | [3727ba82af](https://bsd-hardware.info/?probe=3727ba82af) | Mar 19, 2022 |
| Intel         | SHARKBAY                    | [f22a45488b](https://bsd-hardware.info/?probe=f22a45488b) | Mar 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [a5fd383c40](https://bsd-hardware.info/?probe=a5fd383c40) | Mar 14, 2022 |
| MSI           | MS-7388                     | [ad8209dbdb](https://bsd-hardware.info/?probe=ad8209dbdb) | Mar 05, 2022 |
| MSI           | MS-7388                     | [a59bca8bde](https://bsd-hardware.info/?probe=a59bca8bde) | Mar 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [a6abb45607](https://bsd-hardware.info/?probe=a6abb45607) | Mar 04, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [6b2550968e](https://bsd-hardware.info/?probe=6b2550968e) | Feb 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | [b69015f0e0](https://bsd-hardware.info/?probe=b69015f0e0) | Feb 16, 2022 |
| PC Engines    | apu4                        | [09f27a0f23](https://bsd-hardware.info/?probe=09f27a0f23) | Feb 14, 2022 |
| Protectli     | FW6                         | [d33b2f1244](https://bsd-hardware.info/?probe=d33b2f1244) | Feb 13, 2022 |
| Dell          | 0XHGV1 A00                  | [12ccb8699b](https://bsd-hardware.info/?probe=12ccb8699b) | Feb 08, 2022 |
| Dell          | 0XHGV1 A00                  | [0d3b560aad](https://bsd-hardware.info/?probe=0d3b560aad) | Feb 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [3dabf0503d](https://bsd-hardware.info/?probe=3dabf0503d) | Feb 08, 2022 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [53abdfa3b1](https://bsd-hardware.info/?probe=53abdfa3b1) | Feb 07, 2022 |
| ASUSTek       | PRIME H410M-A               | [1dafdcc71a](https://bsd-hardware.info/?probe=1dafdcc71a) | Feb 05, 2022 |
| ASRock        | J4105M                      | [09b9d104b9](https://bsd-hardware.info/?probe=09b9d104b9) | Feb 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | [07d565ad8c](https://bsd-hardware.info/?probe=07d565ad8c) | Feb 02, 2022 |
| ASRock        | J3455B-ITX                  | [83975bd2b1](https://bsd-hardware.info/?probe=83975bd2b1) | Jan 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | [ff629a490d](https://bsd-hardware.info/?probe=ff629a490d) | Jan 29, 2022 |
| Dell          | 0WMJ54 A01                  | [4b17ef7a18](https://bsd-hardware.info/?probe=4b17ef7a18) | Jan 27, 2022 |
| PC Engines    | APU2                        | [5ea082ddf9](https://bsd-hardware.info/?probe=5ea082ddf9) | Jan 13, 2022 |
| Dell          | 0X4N41 A01                  | [87000234dc](https://bsd-hardware.info/?probe=87000234dc) | Jan 11, 2022 |
| ASUSTek       | P8Z68-M PRO                 | [a0885f4f44](https://bsd-hardware.info/?probe=a0885f4f44) | Jan 10, 2022 |
| Unknown       | Unknown                     | [ded64258b4](https://bsd-hardware.info/?probe=ded64258b4) | Jan 09, 2022 |
| Unknown       | Unknown                     | [8d607c1d19](https://bsd-hardware.info/?probe=8d607c1d19) | Jan 03, 2022 |
| Unknown       | Unknown                     | [c183bdd5af](https://bsd-hardware.info/?probe=c183bdd5af) | Jan 01, 2022 |
| Unknown       | Unknown                     | [4848e4009f](https://bsd-hardware.info/?probe=4848e4009f) | Jan 01, 2022 |
| AMI           | Cherry Trail CR             | [7d47d0db05](https://bsd-hardware.info/?probe=7d47d0db05) | Dec 30, 2021 |
| ASUSTek       | P8B75-M                     | [c3884fac44](https://bsd-hardware.info/?probe=c3884fac44) | Dec 30, 2021 |
| ASUSTek       | Z170-P                      | [bde74629f9](https://bsd-hardware.info/?probe=bde74629f9) | Dec 25, 2021 |
| ASRock        | J3355B-ITX                  | [f4648747b0](https://bsd-hardware.info/?probe=f4648747b0) | Dec 22, 2021 |
| Quanta        | 2AC7 011                    | [1a831a1d34](https://bsd-hardware.info/?probe=1a831a1d34) | Dec 18, 2021 |
| HP            | 843B                        | [f0d279747f](https://bsd-hardware.info/?probe=f0d279747f) | Dec 13, 2021 |
| HP            | 843B                        | [56400d3999](https://bsd-hardware.info/?probe=56400d3999) | Dec 13, 2021 |
| AMI           | Cherry Trail CR             | [624041b5db](https://bsd-hardware.info/?probe=624041b5db) | Dec 09, 2021 |
| Dell          | 051FJ8 A01                  | [ccfb8336a0](https://bsd-hardware.info/?probe=ccfb8336a0) | Dec 01, 2021 |
| HP            | 843B                        | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | [dc9d060c7f](https://bsd-hardware.info/?probe=dc9d060c7f) | Nov 27, 2021 |
| ASUSTek       | M5A97 PLUS                  | [a26bc8f2b3](https://bsd-hardware.info/?probe=a26bc8f2b3) | Nov 14, 2021 |
| Gigabyte      | MRZNVMS-00                  | [817cb3e603](https://bsd-hardware.info/?probe=817cb3e603) | Nov 12, 2021 |
| ASUSTek       | M5A97 PLUS                  | [970387f9d9](https://bsd-hardware.info/?probe=970387f9d9) | Nov 09, 2021 |
| Protectli     | FW6E                        | [ebe5b24dee](https://bsd-hardware.info/?probe=ebe5b24dee) | Nov 08, 2021 |
| Protectli     | FW6E                        | [6c12084410](https://bsd-hardware.info/?probe=6c12084410) | Nov 07, 2021 |
| ASUSTek       | M5A97 PLUS                  | [99b5ab3e42](https://bsd-hardware.info/?probe=99b5ab3e42) | Nov 04, 2021 |
| ASRock        | H370M-ITX/ac                | [bf37ad85e7](https://bsd-hardware.info/?probe=bf37ad85e7) | Nov 03, 2021 |
| Unknown       | Unknown                     | [579cf2ac1a](https://bsd-hardware.info/?probe=579cf2ac1a) | Oct 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7abc8386ec](https://bsd-hardware.info/?probe=7abc8386ec) | Oct 31, 2021 |
| HP            | 843B                        | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [c3d6cddf87](https://bsd-hardware.info/?probe=c3d6cddf87) | Oct 25, 2021 |
| Intel         | CRESCENTBAY                 | [5c8f3708b1](https://bsd-hardware.info/?probe=5c8f3708b1) | Oct 21, 2021 |
| Acer          | Aspire TC-780               | [77101a00b3](https://bsd-hardware.info/?probe=77101a00b3) | Oct 11, 2021 |
| Acer          | Aspire TC-780               | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |
| ASUSTek       | M5A97 PLUS                  | [cc419789f8](https://bsd-hardware.info/?probe=cc419789f8) | Oct 08, 2021 |
| MSI           | B450I GAMING PLUS AC        | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | [00bafc5f7c](https://bsd-hardware.info/?probe=00bafc5f7c) | Oct 03, 2021 |
| ASUSTek       | H81M-E                      | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [36a5bc62bf](https://bsd-hardware.info/?probe=36a5bc62bf) | Sep 27, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [01e33c8399](https://bsd-hardware.info/?probe=01e33c8399) | Sep 26, 2021 |
| ASUSTek       | H81M-E                      | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| AMI           | Cherry Trail CR             | [3b709e37c2](https://bsd-hardware.info/?probe=3b709e37c2) | Sep 12, 2021 |
| ASUSTek       | P8H77-I                     | [1feb22dc52](https://bsd-hardware.info/?probe=1feb22dc52) | Sep 12, 2021 |
| HP            | 212B                        | [d3894b9f37](https://bsd-hardware.info/?probe=d3894b9f37) | Sep 10, 2021 |
| ASRock        | H110M-DGS R3.0              | [df08c4e6d3](https://bsd-hardware.info/?probe=df08c4e6d3) | Sep 09, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | [c64c51359c](https://bsd-hardware.info/?probe=c64c51359c) | Sep 09, 2021 |
| Dell          | 09KPNV A01                  | [e960bc2548](https://bsd-hardware.info/?probe=e960bc2548) | Sep 01, 2021 |
| Gigabyte      | H61N-USB3                   | [3dca10264a](https://bsd-hardware.info/?probe=3dca10264a) | Aug 29, 2021 |
| ASRock        | B450M Pro4                  | [70dc185964](https://bsd-hardware.info/?probe=70dc185964) | Aug 25, 2021 |
| HP            | 1589                        | [4d51cc9c4b](https://bsd-hardware.info/?probe=4d51cc9c4b) | Aug 24, 2021 |
| Acer          | Aspire TC-895 V:1.0         | [da3e8986a3](https://bsd-hardware.info/?probe=da3e8986a3) | Aug 22, 2021 |
| AMI           | Cherry Trail CR             | [bd94ad09ef](https://bsd-hardware.info/?probe=bd94ad09ef) | Aug 12, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | [94201b7633](https://bsd-hardware.info/?probe=94201b7633) | Aug 10, 2021 |
| Supermicro    | X11SDV-8C-TP8F              | [6da61be169](https://bsd-hardware.info/?probe=6da61be169) | Aug 08, 2021 |
| Intel         | Q3XXG4-P V1.0               | [535b577563](https://bsd-hardware.info/?probe=535b577563) | Aug 03, 2021 |
| HP            | ProLiant ML150 G6           | [783c2ba254](https://bsd-hardware.info/?probe=783c2ba254) | Aug 02, 2021 |
| Protectli     | FW4B Ver                    | [b434d9bfb8](https://bsd-hardware.info/?probe=b434d9bfb8) | Aug 02, 2021 |
| ASUSTek       | P5QL PRO                    | [4d118404a8](https://bsd-hardware.info/?probe=4d118404a8) | Jul 29, 2021 |
| ASRock        | J3455B-ITX                  | [fc13802cd3](https://bsd-hardware.info/?probe=fc13802cd3) | Jul 19, 2021 |
| Intel         | SHARKBAY                    | [5697d53687](https://bsd-hardware.info/?probe=5697d53687) | Jul 19, 2021 |
| Lenovo        | SHARKBAY 0C48431 PRO        | [0a1fa8924e](https://bsd-hardware.info/?probe=0a1fa8924e) | Jul 17, 2021 |
| ASRock        | J3455B-ITX                  | [b86c2cfc99](https://bsd-hardware.info/?probe=b86c2cfc99) | Jul 16, 2021 |
| PC Engines    | apu4                        | [51163b13ef](https://bsd-hardware.info/?probe=51163b13ef) | Jul 11, 2021 |
| Intel         | SHARKBAY                    | [59a1b5f761](https://bsd-hardware.info/?probe=59a1b5f761) | Jul 10, 2021 |
| Gigabyte      | H97-D3H-CF                  | [a326fd4061](https://bsd-hardware.info/?probe=a326fd4061) | Jun 20, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [ef7104e237](https://bsd-hardware.info/?probe=ef7104e237) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [d2dd261a2a](https://bsd-hardware.info/?probe=d2dd261a2a) | Jun 20, 2021 |
| Intel         | SHARKBAY                    | [6aa5f8046e](https://bsd-hardware.info/?probe=6aa5f8046e) | Jun 19, 2021 |
| Shuttle       | FS110                       | [9b4093c9a1](https://bsd-hardware.info/?probe=9b4093c9a1) | Jun 17, 2021 |
| Intel         | Q3XXG4-P V1.0               | [459bf008e9](https://bsd-hardware.info/?probe=459bf008e9) | Jun 12, 2021 |
| HP            | 805D                        | [dc4e61ecd4](https://bsd-hardware.info/?probe=dc4e61ecd4) | Jun 07, 2021 |
| HP            | 1998                        | [2806e1e8cf](https://bsd-hardware.info/?probe=2806e1e8cf) | Jun 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | [95a281e2f8](https://bsd-hardware.info/?probe=95a281e2f8) | Jun 04, 2021 |
| Unknown       | Unknown                     | [65dd81d59e](https://bsd-hardware.info/?probe=65dd81d59e) | Jun 02, 2021 |
| Protectli     | FW4B Ver                    | [7e013ea910](https://bsd-hardware.info/?probe=7e013ea910) | May 20, 2021 |
| Unknown       | Unknown                     | [f90e5f9566](https://bsd-hardware.info/?probe=f90e5f9566) | May 16, 2021 |
| Unknown       | Unknown                     | [e67de92cb9](https://bsd-hardware.info/?probe=e67de92cb9) | May 14, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [273e379d9f](https://bsd-hardware.info/?probe=273e379d9f) | May 14, 2021 |
| Shuttle       | FS110                       | [e39173782f](https://bsd-hardware.info/?probe=e39173782f) | May 08, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [1f78fbb36c](https://bsd-hardware.info/?probe=1f78fbb36c) | May 08, 2021 |
| Intel         | Q3XXG4-P V1.0               | [5a128dd6a3](https://bsd-hardware.info/?probe=5a128dd6a3) | Apr 22, 2021 |
| HP            | 18E7                        | [e6354de524](https://bsd-hardware.info/?probe=e6354de524) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7a6f106b0e](https://bsd-hardware.info/?probe=7a6f106b0e) | Apr 18, 2021 |
| Intel         | SHARKBAY                    | [cd0467031a](https://bsd-hardware.info/?probe=cd0467031a) | Apr 17, 2021 |
| HARDKERNEL    | ODROID-H2                   | [5a1a372153](https://bsd-hardware.info/?probe=5a1a372153) | Apr 16, 2021 |
| HARDKERNEL    | ODROID-H2                   | [31a9bf167b](https://bsd-hardware.info/?probe=31a9bf167b) | Apr 16, 2021 |
| Dell          | 051FJ8 A01                  | [351b13fd3b](https://bsd-hardware.info/?probe=351b13fd3b) | Apr 15, 2021 |
| ASRock        | J4105M                      | [69165e1573](https://bsd-hardware.info/?probe=69165e1573) | Apr 13, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [5aca6c03c1](https://bsd-hardware.info/?probe=5aca6c03c1) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [0e814e53e9](https://bsd-hardware.info/?probe=0e814e53e9) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [817ec0a0da](https://bsd-hardware.info/?probe=817ec0a0da) | Apr 09, 2021 |
| ASUSTek       | PRIME H410M-A               | [6f4f9fb14e](https://bsd-hardware.info/?probe=6f4f9fb14e) | Apr 07, 2021 |
| HP            | 2AF7                        | [acd341147c](https://bsd-hardware.info/?probe=acd341147c) | Apr 03, 2021 |
| Dell          | 0TTDMJ A00                  | [b5c0428c8a](https://bsd-hardware.info/?probe=b5c0428c8a) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | [6af0a9bc78](https://bsd-hardware.info/?probe=6af0a9bc78) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | [aaf140005c](https://bsd-hardware.info/?probe=aaf140005c) | Mar 30, 2021 |
| AMI           | Cherry Trail CR             | [636dfb334b](https://bsd-hardware.info/?probe=636dfb334b) | Mar 29, 2021 |
| Gigabyte      | D525TUD                     | [a48a515986](https://bsd-hardware.info/?probe=a48a515986) | Mar 24, 2021 |
| Dell          | 0M9KCM A00                  | [7280d52eff](https://bsd-hardware.info/?probe=7280d52eff) | Mar 23, 2021 |
| Lenovo        | 30D9 No DPK                 | [061ad76c0e](https://bsd-hardware.info/?probe=061ad76c0e) | Mar 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | [03935b2745](https://bsd-hardware.info/?probe=03935b2745) | Mar 20, 2021 |
| Dell          | 00V62H A00                  | [27cb6a75c8](https://bsd-hardware.info/?probe=27cb6a75c8) | Mar 19, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [8964a02114](https://bsd-hardware.info/?probe=8964a02114) | Mar 15, 2021 |
| ASRock        | B450M Pro4                  | [e9ca160a2d](https://bsd-hardware.info/?probe=e9ca160a2d) | Mar 11, 2021 |
| Shuttle       | FS110                       | [fc31311d01](https://bsd-hardware.info/?probe=fc31311d01) | Mar 10, 2021 |
| Supermicro    | A2SDi-TP8F                  | [c30d805062](https://bsd-hardware.info/?probe=c30d805062) | Mar 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [c7b0539b99](https://bsd-hardware.info/?probe=c7b0539b99) | Mar 02, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | [9d35f9e853](https://bsd-hardware.info/?probe=9d35f9e853) | Feb 24, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [11d6c98009](https://bsd-hardware.info/?probe=11d6c98009) | Feb 21, 2021 |
| Protectli     | FW6                         | [b656792690](https://bsd-hardware.info/?probe=b656792690) | Feb 20, 2021 |
| ASUSTek       | PRIME H410M-A               | [cfd1824b40](https://bsd-hardware.info/?probe=cfd1824b40) | Feb 18, 2021 |
| Gigabyte      | MRZNVMS-00                  | [b51cb672a4](https://bsd-hardware.info/?probe=b51cb672a4) | Feb 12, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [3402eabdbf](https://bsd-hardware.info/?probe=3402eabdbf) | Feb 09, 2021 |
| ASRock        | Z270M-ITX/ac                | [9b50d422e3](https://bsd-hardware.info/?probe=9b50d422e3) | Feb 04, 2021 |
| HP            | 0AECh D                     | [6dde87584c](https://bsd-hardware.info/?probe=6dde87584c) | Feb 04, 2021 |
| PC Engines    | apu4                        | [18dfb34a97](https://bsd-hardware.info/?probe=18dfb34a97) | Feb 04, 2021 |
| HP            | 3397                        | [cda4af23ee](https://bsd-hardware.info/?probe=cda4af23ee) | Feb 03, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | [0a48224f4b](https://bsd-hardware.info/?probe=0a48224f4b) | Feb 03, 2021 |
| HP            | 3397                        | [65f1db2a70](https://bsd-hardware.info/?probe=65f1db2a70) | Feb 03, 2021 |
| HP            | 82B4                        | [faf58d8f87](https://bsd-hardware.info/?probe=faf58d8f87) | Jan 30, 2021 |
| Lenovo        | 30D9 No DPK                 | [12056c71ad](https://bsd-hardware.info/?probe=12056c71ad) | Jan 30, 2021 |
| PC Engines    | APU2                        | [7e96c61bf9](https://bsd-hardware.info/?probe=7e96c61bf9) | Jan 30, 2021 |
| ASRock        | J3455-ITX                   | [65bde09c13](https://bsd-hardware.info/?probe=65bde09c13) | Jan 26, 2021 |
| ASRock        | J3455-ITX                   | [0a4d4fc896](https://bsd-hardware.info/?probe=0a4d4fc896) | Jan 25, 2021 |
| ASRock        | J3355B-ITX                  | [e8496a6202](https://bsd-hardware.info/?probe=e8496a6202) | Jan 24, 2021 |
| PC Engines    | APU2                        | [da6e3cd1a6](https://bsd-hardware.info/?probe=da6e3cd1a6) | Jan 23, 2021 |
| PC Engines    | APU2                        | [3d536a42eb](https://bsd-hardware.info/?probe=3d536a42eb) | Jan 21, 2021 |
| PC Engines    | APU2                        | [043446a653](https://bsd-hardware.info/?probe=043446a653) | Jan 21, 2021 |
| Shuttle       | FS110                       | [fed17a1f77](https://bsd-hardware.info/?probe=fed17a1f77) | Jan 21, 2021 |
| Supermicro    | X8STi                       | [7cda964f76](https://bsd-hardware.info/?probe=7cda964f76) | Jan 20, 2021 |
| Dell          | 0M9KCM A02                  | [1cc5f6a07b](https://bsd-hardware.info/?probe=1cc5f6a07b) | Jan 20, 2021 |
| ASUSTek       | Z97-A                       | [8c55004504](https://bsd-hardware.info/?probe=8c55004504) | Jan 19, 2021 |
| Supermicro    | X7SLA                       | [2d31f38bf0](https://bsd-hardware.info/?probe=2d31f38bf0) | Jan 10, 2021 |
| Supermicro    | X7SPA-HF                    | [834cb6c68a](https://bsd-hardware.info/?probe=834cb6c68a) | Jan 10, 2021 |
| MSI           | X58 Pro-E                   | [bd108f94d5](https://bsd-hardware.info/?probe=bd108f94d5) | Jan 02, 2021 |
| HP            | 212B                        | [7fe9d2c508](https://bsd-hardware.info/?probe=7fe9d2c508) | Dec 18, 2020 |
| Dell          | 0GM819                      | [adc8eb1931](https://bsd-hardware.info/?probe=adc8eb1931) | Dec 18, 2020 |
| HP            | 805D                        | [dc62857275](https://bsd-hardware.info/?probe=dc62857275) | Dec 17, 2020 |
| Supermicro    | X8STi                       | [80c2762cfb](https://bsd-hardware.info/?probe=80c2762cfb) | Dec 16, 2020 |
| ASRockRack    | D1541D4U-2O8R               | [d59d8a3b6d](https://bsd-hardware.info/?probe=d59d8a3b6d) | Dec 16, 2020 |
| Supermicro    | X11SSH-F                    | [ebb920c0c4](https://bsd-hardware.info/?probe=ebb920c0c4) | Dec 16, 2020 |
| MSI           | X99S SLI PLUS               | [9b2421d9d5](https://bsd-hardware.info/?probe=9b2421d9d5) | Nov 28, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5d5ecb38cd](https://bsd-hardware.info/?probe=5d5ecb38cd) | Nov 25, 2020 |
| MSI           | 970 GAMING                  | [002b408f7e](https://bsd-hardware.info/?probe=002b408f7e) | Nov 18, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [714b6539cf](https://bsd-hardware.info/?probe=714b6539cf) | Nov 07, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [9f871ab960](https://bsd-hardware.info/?probe=9f871ab960) | Nov 01, 2020 |
| Intel         | X79 V2.81A                  | [d5b4cdf28a](https://bsd-hardware.info/?probe=d5b4cdf28a) | Oct 30, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [59c940d739](https://bsd-hardware.info/?probe=59c940d739) | Oct 30, 2020 |
| Unknown       | Unknown                     | [8552669e76](https://bsd-hardware.info/?probe=8552669e76) | Oct 30, 2020 |
| Unknown       | Unknown                     | [50966c2f83](https://bsd-hardware.info/?probe=50966c2f83) | Oct 30, 2020 |
| ADI Engine... | RCC-VE                      | [30440abc03](https://bsd-hardware.info/?probe=30440abc03) | Oct 29, 2020 |
| IBM           | Board                       | [11b0b7012f](https://bsd-hardware.info/?probe=11b0b7012f) | Oct 21, 2020 |
| IBM           | Board                       | [a92c08a920](https://bsd-hardware.info/?probe=a92c08a920) | Oct 21, 2020 |
| IBM           | Board                       | [80d5f15a63](https://bsd-hardware.info/?probe=80d5f15a63) | Oct 21, 2020 |
| MSI           | MS-7250                     | [41e2d9dab3](https://bsd-hardware.info/?probe=41e2d9dab3) | Sep 04, 2020 |
| HP            | 3031h                       | [1f2695b3a7](https://bsd-hardware.info/?probe=1f2695b3a7) | Aug 25, 2020 |
| ASUSTek       | Z170-P                      | [49e01a949b](https://bsd-hardware.info/?probe=49e01a949b) | Jul 29, 2020 |
| ASUSTek       | P8Z77-V LK                  | [0f7697b73a](https://bsd-hardware.info/?probe=0f7697b73a) | May 28, 2020 |
| Dell          | 0T10XW A02                  | [81f39f3061](https://bsd-hardware.info/?probe=81f39f3061) | May 28, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OPNsense 22.1.8   | 8        | 3.33%   |
| OPNsense 22.1.10  | 8        | 3.33%   |
| OPNsense 21.1.4   | 8        | 3.33%   |
| helloSystem 0.5.0 | 8        | 3.33%   |
| OPNsense 22.7.8   | 7        | 2.92%   |
| OPNsense 22.1.7   | 7        | 2.92%   |
| OPNsense 22.1     | 7        | 2.92%   |
| OPNsense 21.7     | 7        | 2.92%   |
| OPNsense 21.1.3   | 7        | 2.92%   |
| OPNsense 21.1     | 7        | 2.92%   |
| helloSystem 0.7.0 | 7        | 2.92%   |
| OPNsense 22.7.4   | 6        | 2.5%    |
| OPNsense 22.1.6   | 6        | 2.5%    |
| OPNsense 21.1.5   | 6        | 2.5%    |
| OPNsense 20.7.8   | 6        | 2.5%    |
| OPNsense 22.7     | 5        | 2.08%   |
| OPNsense 21.7.7   | 5        | 2.08%   |
| OPNsense 21.7.3   | 5        | 2.08%   |
| OPNsense 21.7.1   | 5        | 2.08%   |
| OPNsense 21.1.6   | 5        | 2.08%   |
| OPNsense 21.1.1   | 5        | 2.08%   |
| FreeBSD 13.1      | 5        | 2.08%   |
| FreeBSD 12.2      | 5        | 2.08%   |
| OPNsense 22.7.7   | 4        | 1.67%   |
| OPNsense 22.1.3   | 4        | 1.67%   |
| OPNsense 21.7.8   | 4        | 1.67%   |
| OPNsense 21.7.4   | 4        | 1.67%   |
| OPNsense 22.7.3   | 3        | 1.25%   |
| OPNsense 22.7.2   | 3        | 1.25%   |
| OPNsense 22.1.9   | 3        | 1.25%   |
| OPNsense 21.1.8   | 3        | 1.25%   |
| OPNsense 21.1.7   | 3        | 1.25%   |
| OPNsense 21.1.2   | 3        | 1.25%   |
| FreeBSD 13.0      | 3        | 1.25%   |
| OPNsense 23.1     | 2        | 0.83%   |
| OPNsense 22.7.6   | 2        | 0.83%   |
| OPNsense 22.7.5   | 2        | 0.83%   |
| OPNsense 22.7.1   | 2        | 0.83%   |
| OPNsense 22.1.4   | 2        | 0.83%   |
| OPNsense 22.1.2   | 2        | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 124      | 65.61%  |
| FreeBSD     | 36       | 19.05%  |
| helloSystem | 18       | 9.52%   |
| OpenBSD     | 3        | 1.59%   |
| GhostBSD    | 3        | 1.59%   |
| FreeNAS     | 3        | 1.59%   |
| TrueNAS     | 1        | 0.53%   |
| pfSense     | 1        | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 185      | 99.46%  |
| i386  | 1        | 0.54%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 142      | 75.13%  |
| helloDesktop | 19       | 10.05%  |
| XFCE         | 8        | 4.23%   |
| KDE5         | 7        | 3.7%    |
| MATE         | 6        | 3.17%   |
| GNOME        | 2        | 1.06%   |
| Cinnamon     | 2        | 1.06%   |
| X-Cinnamon   | 1        | 0.53%   |
| Window Maker | 1        | 0.53%   |
| LXDE         | 1        | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 142      | 76.34%  |
| X11     | 43       | 23.12%  |
| Wayland | 1        | 0.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 150      | 79.37%  |
| SLiM    | 21       | 11.11%  |
| SDDM    | 10       | 5.29%   |
| LightDM | 4        | 2.12%   |
| XDM     | 3        | 1.59%   |
| GDM     | 1        | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 137      | 73.26%  |
| en_US   | 31       | 16.58%  |
| C       | 14       | 7.49%   |
| en_CA   | 3        | 1.6%    |
| fr_FR   | 2        | 1.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 154      | 81.05%  |
| BIOS | 36       | 18.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 108      | 55.96%  |
| Zfs    | 78       | 40.41%  |
| Cd9660 | 4        | 2.07%   |
| Ffs    | 3        | 1.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 171      | 91.94%  |
| MBR     | 14       | 7.53%   |
| Unknown | 1        | 0.54%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Dell                       | 23       | 12.37%  |
| ASUSTek Computer           | 23       | 12.37%  |
| Hewlett-Packard            | 22       | 11.83%  |
| Lenovo                     | 14       | 7.53%   |
| Protectli                  | 13       | 6.99%   |
| Intel                      | 13       | 6.99%   |
| Gigabyte Technology        | 12       | 6.45%   |
| ASRock                     | 11       | 5.91%   |
| Unknown                    | 11       | 5.91%   |
| Supermicro                 | 9        | 4.84%   |
| MSI                        | 8        | 4.3%    |
| PC Engines                 | 5        | 2.69%   |
| Acer                       | 3        | 1.61%   |
| Techvision                 | 2        | 1.08%   |
| AZW                        | 2        | 1.08%   |
| Yanling                    | 1        | 0.54%   |
| Shuttle                    | 1        | 0.54%   |
| ShenZhen MinWin Technology | 1        | 0.54%   |
| SeeedStudio                | 1        | 0.54%   |
| Quanta                     | 1        | 0.54%   |
| IBM                        | 1        | 0.54%   |
| HARDKERNEL                 | 1        | 0.54%   |
| Datto                      | 1        | 0.54%   |
| CncTion                    | 1        | 0.54%   |
| Cisco                      | 1        | 0.54%   |
| Biostar                    | 1        | 0.54%   |
| ASRockRack                 | 1        | 0.54%   |
| Apple                      | 1        | 0.54%   |
| AMI                        | 1        | 0.54%   |
| ADI Engineering            | 1        | 0.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 11       | 5.91%   |
| Protectli FW4B                     | 7        | 3.76%   |
| Protectli FW6                      | 5        | 2.69%   |
| Intel Q3XXG4-P V1.0                | 5        | 2.69%   |
| Intel NDISB533                     | 4        | 2.15%   |
| HP EliteDesk 800 G1 SFF            | 3        | 1.61%   |
| Dell OptiPlex 9010                 | 3        | 1.61%   |
| Dell G5 5090                       | 3        | 1.61%   |
| ASUS All Series                    | 3        | 1.61%   |
| Techvision TVI7309X                | 2        | 1.08%   |
| Supermicro X8STi                   | 2        | 1.08%   |
| PC Engines apu4                    | 2        | 1.08%   |
| PC Engines APU2                    | 2        | 1.08%   |
| Lenovo ThinkCentre M93p 10A8S16X0J | 2        | 1.08%   |
| HP Z440 Workstation                | 2        | 1.08%   |
| Dell Precision WorkStation T3500   | 2        | 1.08%   |
| Dell Precision Tower 5810          | 2        | 1.08%   |
| Dell OptiPlex 7010                 | 2        | 1.08%   |
| Dell OptiPlex 3020                 | 2        | 1.08%   |
| ASUS P8H77-I                       | 2        | 1.08%   |
| ASUS M5A97 PLUS                    | 2        | 1.08%   |
| ASRock H110M-DGS R3.0              | 2        | 1.08%   |
| ASRock B450M Pro4                  | 2        | 1.08%   |
| Yanling YL-KBR6L                   | 1        | 0.54%   |
| Supermicro X7SPA-HF                | 1        | 0.54%   |
| Supermicro X7SLA                   | 1        | 0.54%   |
| Supermicro SYS-E300-9A             | 1        | 0.54%   |
| Supermicro SYS-5019S-ML            | 1        | 0.54%   |
| Supermicro SYS-5019D-FN8TP         | 1        | 0.54%   |
| Supermicro SYS-5019A-FTN4          | 1        | 0.54%   |
| Supermicro AS -5019D-FTN4          | 1        | 0.54%   |
| Shuttle DH110                      | 1        | 0.54%   |
| ShenZhen MinWin MW-GMLK-2.5G6L     | 1        | 0.54%   |
| SeeedStudio ODYSSEY-X86J4105       | 1        | 0.54%   |
| Quanta 120-1135                    | 1        | 0.54%   |
| Protectli FW6E                     | 1        | 0.54%   |
| PC Engines APU                     | 1        | 0.54%   |
| MSI MS-7B79                        | 1        | 0.54%   |
| MSI MS-7A40                        | 1        | 0.54%   |
| MSI MS-7885                        | 1        | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Dell OptiPlex                  | 15       | 8.06%   |
| Lenovo ThinkCentre             | 12       | 6.45%   |
| Unknown                        | 11       | 5.91%   |
| Protectli FW4B                 | 7        | 3.76%   |
| HP ProDesk                     | 6        | 3.23%   |
| Protectli FW6                  | 5        | 2.69%   |
| Intel Q3XXG4-P                 | 5        | 2.69%   |
| HP EliteDesk                   | 5        | 2.69%   |
| Dell Precision                 | 5        | 2.69%   |
| ASUS PRIME                     | 5        | 2.69%   |
| Intel NDISB533                 | 4        | 2.15%   |
| HP Compaq                      | 3        | 1.61%   |
| Dell G5                        | 3        | 1.61%   |
| ASUS All                       | 3        | 1.61%   |
| ASRock B450M                   | 3        | 1.61%   |
| Acer Aspire                    | 3        | 1.61%   |
| Techvision TVI7309X            | 2        | 1.08%   |
| Supermicro X8STi               | 2        | 1.08%   |
| PC Engines apu4                | 2        | 1.08%   |
| PC Engines APU2                | 2        | 1.08%   |
| HP Z440                        | 2        | 1.08%   |
| ASUS ROG                       | 2        | 1.08%   |
| ASUS P8H77-I                   | 2        | 1.08%   |
| ASUS M5A97                     | 2        | 1.08%   |
| ASRock H110M-DGS               | 2        | 1.08%   |
| Yanling YL-KBR6L               | 1        | 0.54%   |
| Supermicro X7SPA-HF            | 1        | 0.54%   |
| Supermicro X7SLA               | 1        | 0.54%   |
| Supermicro SYS-E300-9A         | 1        | 0.54%   |
| Supermicro SYS-5019S-ML        | 1        | 0.54%   |
| Supermicro SYS-5019D-FN8TP     | 1        | 0.54%   |
| Supermicro SYS-5019A-FTN4      | 1        | 0.54%   |
| Supermicro AS                  | 1        | 0.54%   |
| Shuttle DH110                  | 1        | 0.54%   |
| ShenZhen MinWin MW-GMLK-2.5G6L | 1        | 0.54%   |
| SeeedStudio ODYSSEY-X86J4105   | 1        | 0.54%   |
| Quanta 120-1135                | 1        | 0.54%   |
| Protectli FW6E                 | 1        | 0.54%   |
| PC Engines APU                 | 1        | 0.54%   |
| MSI MS-7B79                    | 1        | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 37       | 19.89%  |
| 2020    | 25       | 13.44%  |
| 2014    | 21       | 11.29%  |
| 2016    | 15       | 8.06%   |
| 2013    | 15       | 8.06%   |
| 2019    | 13       | 6.99%   |
| 2022    | 9        | 4.84%   |
| 2011    | 8        | 4.3%    |
| 2010    | 8        | 4.3%    |
| 2015    | 7        | 3.76%   |
| 2017    | 6        | 3.23%   |
| 2009    | 6        | 3.23%   |
| 2021    | 5        | 2.69%   |
| 2012    | 5        | 2.69%   |
| 2008    | 3        | 1.61%   |
| 2007    | 1        | 0.54%   |
| 2006    | 1        | 0.54%   |
| Unknown | 1        | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 186      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 179      | 96.24%  |
| Yes  | 7        | 3.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 74       | 38.95%  |
| 16.01-24.0  | 44       | 23.16%  |
| 4.01-8.0    | 31       | 16.32%  |
| 32.01-64.0  | 21       | 11.05%  |
| 64.01-256.0 | 7        | 3.68%   |
| 24.01-32.0  | 5        | 2.63%   |
| 2.01-3.0    | 5        | 2.63%   |
| 3.01-4.0    | 1        | 0.53%   |
| 1.01-2.0    | 1        | 0.53%   |
| 0.51-1.0    | 1        | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 94       | 49.47%  |
| 0.51-1.0    | 56       | 29.47%  |
| 1.01-2.0    | 24       | 12.63%  |
| 4.01-8.0    | 4        | 2.11%   |
| 3.01-4.0    | 4        | 2.11%   |
| 2.01-3.0    | 4        | 2.11%   |
| 32.01-64.0  | 1        | 0.53%   |
| 64.01-256.0 | 1        | 0.53%   |
| 8.01-16.0   | 1        | 0.53%   |
| 0           | 1        | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 133      | 70.74%  |
| 2      | 28       | 14.89%  |
| 3      | 9        | 4.79%   |
| 0      | 9        | 4.79%   |
| 4      | 5        | 2.66%   |
| 13     | 1        | 0.53%   |
| 10     | 1        | 0.53%   |
| 7      | 1        | 0.53%   |
| 5      | 1        | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 147      | 77.37%  |
| Yes       | 43       | 22.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 185      | 99.46%  |
| No        | 1        | 0.54%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 153      | 81.38%  |
| Yes       | 35       | 18.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 163      | 87.63%  |
| Yes       | 23       | 12.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Canada  | 186      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Toronto                    | 19       | 9.64%   |
| Ottawa                     | 13       | 6.6%    |
| Montreal                   | 13       | 6.6%    |
| Edmonton                   | 9        | 4.57%   |
| Calgary                    | 9        | 4.57%   |
| Winnipeg                   | 7        | 3.55%   |
| Victoria                   | 7        | 3.55%   |
| Kitchener                  | 7        | 3.55%   |
| Vancouver                  | 5        | 2.54%   |
| Surrey                     | 4        | 2.03%   |
| Brampton                   | 4        | 2.03%   |
| Windsor                    | 3        | 1.52%   |
| St. Albert                 | 3        | 1.52%   |
| Sarnia                     | 3        | 1.52%   |
| Regina                     | 3        | 1.52%   |
| Moncton                    | 3        | 1.52%   |
| Terrebonne                 | 2        | 1.02%   |
| Saskatoon                  | 2        | 1.02%   |
| Sainte-Julie               | 2        | 1.02%   |
| Saint-Bruno-de-Montarville | 2        | 1.02%   |
| Richmond                   | 2        | 1.02%   |
| Québec                    | 2        | 1.02%   |
| Peterborough               | 2        | 1.02%   |
| Oakville                   | 2        | 1.02%   |
| Nanaimo                    | 2        | 1.02%   |
| London                     | 2        | 1.02%   |
| Laval                      | 2        | 1.02%   |
| Kingston                   | 2        | 1.02%   |
| Kanata                     | 2        | 1.02%   |
| Hamilton                   | 2        | 1.02%   |
| Guelph                     | 2        | 1.02%   |
| Greater Sudbury            | 2        | 1.02%   |
| Burnaby                    | 2        | 1.02%   |
| Burlington                 | 2        | 1.02%   |
| West Kelowna               | 1        | 0.51%   |
| Wallaceburg                | 1        | 0.51%   |
| Vaughan                    | 1        | 0.51%   |
| Uxbridge                   | 1        | 0.51%   |
| Tobique First Nation       | 1        | 0.51%   |
| Thorold                    | 1        | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 35       | 61     | 15.35%  |
| Samsung Electronics | 35       | 47     | 15.35%  |
| WDC                 | 32       | 71     | 14.04%  |
| Kingston            | 27       | 33     | 11.84%  |
| Crucial             | 12       | 15     | 5.26%   |
| Intel               | 10       | 12     | 4.39%   |
| Toshiba             | 7        | 11     | 3.07%   |
| SanDisk             | 7        | 9      | 3.07%   |
| A-DATA Technology   | 7        | 13     | 3.07%   |
| SPCC                | 4        | 4      | 1.75%   |
| OCZ                 | 4        | 5      | 1.75%   |
| Mushkin             | 4        | 4      | 1.75%   |
| Dogfish             | 4        | 7      | 1.75%   |
| BIWIN               | 4        | 4      | 1.75%   |
| PNY                 | 3        | 4      | 1.32%   |
| Micron Technology   | 3        | 6      | 1.32%   |
| Hoodisk             | 3        | 4      | 1.32%   |
| HGST                | 3        | 4      | 1.32%   |
| VisionTek           | 2        | 6      | 0.88%   |
| Transcend           | 2        | 3      | 0.88%   |
| SK hynix            | 2        | 4      | 0.88%   |
| Hitachi             | 2        | 2      | 0.88%   |
| Hewlett-Packard     | 2        | 2      | 0.88%   |
| Corsair             | 2        | 4      | 0.88%   |
| China               | 2        | 3      | 0.88%   |
| Timetec             | 1        | 1      | 0.44%   |
| Team                | 1        | 1      | 0.44%   |
| SATADOM             | 1        | 2      | 0.44%   |
| Protectli           | 1        | 2      | 0.44%   |
| Phison              | 1        | 1      | 0.44%   |
| NVMe                | 1        | 1      | 0.44%   |
| HPE                 | 1        | 4      | 0.44%   |
| FORESEE             | 1        | 1      | 0.44%   |
| EAGET               | 1        | 1      | 0.44%   |
| AVEXIR              | 1        | 2      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SA400S37240G 240GB     | 10       | 4.12%   |
| Kingston SA400S37120G 120GB     | 6        | 2.47%   |
| Seagate ST1000DM010-2EP102 1TB  | 5        | 2.06%   |
| Samsung SSD 850 EVO 250GB       | 5        | 2.06%   |
| Samsung SSD 860 EVO 500GB       | 4        | 1.65%   |
| BIWIN SSD 128GB                 | 4        | 1.65%   |
| WDC WD20EZRX-00DC0B0 2TB        | 3        | 1.23%   |
| Toshiba DT01ACA100 1TB          | 3        | 1.23%   |
| Seagate ST500DM002-1BD142 500GB | 3        | 1.23%   |
| Seagate ST3500413AS 500GB       | 3        | 1.23%   |
| SanDisk SD6SB1M064G1022I 64GB   | 3        | 1.23%   |
| Samsung SSD 840 EVO 120GB       | 3        | 1.23%   |
| Crucial CT240BX500SSD1 240GB    | 3        | 1.23%   |
| WDC WD40EFRX-68WT0N0 4TB        | 2        | 0.82%   |
| WDC WD10EZEX-22MFCA0 1TB        | 2        | 0.82%   |
| WDC WD10EZEX-08WN4A0 1TB        | 2        | 0.82%   |
| WDC PC SN520 NVMe 256GB         | 2        | 0.82%   |
| VisionTek mSATA 120GB           | 2        | 0.82%   |
| Transcend TS256GMSA230S 256GB   | 2        | 0.82%   |
| Toshiba MQ01ABD075 752GB        | 2        | 0.82%   |
| Seagate ST2000DM008-2FR102 2TB  | 2        | 0.82%   |
| Seagate ST1000DM003-1CH162 1TB  | 2        | 0.82%   |
| Samsung SSD 980 PRO 1TB         | 2        | 0.82%   |
| Samsung SSD 850 EVO mSATA 250GB | 2        | 0.82%   |
| Samsung SSD 840 EVO 250GB       | 2        | 0.82%   |
| PNY CS1311 120GB SSD            | 2        | 0.82%   |
| Mushkin MKNSSDEC60GB 64GB       | 2        | 0.82%   |
| Kingston SUV500MS120G 120GB     | 2        | 0.82%   |
| Intel SSDSC2BB080G4 80GB        | 2        | 0.82%   |
| Crucial CT1000MX500SSD1 1TB     | 2        | 0.82%   |
| A-DATA SU650 120GB              | 2        | 0.82%   |
| A-DATA SU630 240GB              | 2        | 0.82%   |
| WDC WDS500G2B0B-00YS70 500GB    | 1        | 0.41%   |
| WDC WDS500G2B0A-00SM50 500GB    | 1        | 0.41%   |
| WDC WDS250G3X0C-00SJG0 250GB    | 1        | 0.41%   |
| WDC WDS250G2B0A 250GB           | 1        | 0.41%   |
| WDC WDS120G2G0A-00JH30 120GB    | 1        | 0.41%   |
| WDC WDS100T2B0A-00SM50 1TB      | 1        | 0.41%   |
| WDC WD6400AAKS-22A7B2 640GB     | 1        | 0.41%   |
| WDC WD6003FZBX-00K5WB0 6TB      | 1        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 33       | 59     | 47.83%  |
| WDC     | 25       | 60     | 36.23%  |
| Toshiba | 6        | 8      | 8.7%    |
| HGST    | 3        | 4      | 4.35%   |
| Hitachi | 2        | 2      | 2.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 30       | 39     | 21.28%  |
| Kingston            | 27       | 32     | 19.15%  |
| Crucial             | 11       | 14     | 7.8%    |
| Intel               | 9        | 11     | 6.38%   |
| SanDisk             | 7        | 9      | 4.96%   |
| A-DATA Technology   | 7        | 13     | 4.96%   |
| WDC                 | 5        | 7      | 3.55%   |
| OCZ                 | 4        | 5      | 2.84%   |
| Mushkin             | 4        | 4      | 2.84%   |
| Dogfish             | 4        | 7      | 2.84%   |
| BIWIN               | 4        | 4      | 2.84%   |
| SPCC                | 3        | 3      | 2.13%   |
| PNY                 | 3        | 4      | 2.13%   |
| Micron Technology   | 3        | 6      | 2.13%   |
| Hoodisk             | 3        | 4      | 2.13%   |
| VisionTek           | 2        | 6      | 1.42%   |
| Transcend           | 2        | 3      | 1.42%   |
| Seagate             | 2        | 2      | 1.42%   |
| Corsair             | 2        | 4      | 1.42%   |
| China               | 2        | 3      | 1.42%   |
| SATADOM             | 1        | 2      | 0.71%   |
| Protectli           | 1        | 2      | 0.71%   |
| Phison              | 1        | 1      | 0.71%   |
| HPE                 | 1        | 4      | 0.71%   |
| FORESEE             | 1        | 1      | 0.71%   |
| EAGET               | 1        | 1      | 0.71%   |
| AVEXIR              | 1        | 2      | 0.71%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 130      | 193    | 63.11%  |
| HDD  | 57       | 133    | 27.67%  |
| NVMe | 19       | 28     | 9.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 169      | 326    | 89.89%  |
| NVMe | 19       | 28     | 10.11%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 140      | 204    | 71.07%  |
| 0.51-1.0   | 32       | 55     | 16.24%  |
| 1.01-2.0   | 10       | 19     | 5.08%   |
| 3.01-4.0   | 5        | 15     | 2.54%   |
| 2.01-3.0   | 4        | 8      | 2.03%   |
| 4.01-10.0  | 4        | 22     | 2.03%   |
| 10.01-20.0 | 2        | 3      | 1.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 82       | 42.49%  |
| 251-500        | 33       | 17.1%   |
| 51-100         | 23       | 11.92%  |
| 1-20           | 20       | 10.36%  |
| 21-50          | 18       | 9.33%   |
| 501-1000       | 9        | 4.66%   |
| 1001-2000      | 5        | 2.59%   |
| Unknown        | 2        | 1.04%   |
| More than 3000 | 1        | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 172      | 87.76%  |
| 21-50    | 17       | 8.67%   |
| 51-100   | 4        | 2.04%   |
| Unknown  | 2        | 1.02%   |
| 501-1000 | 1        | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| VisionTek mSATA 120GB                      | 2        | 6      | 6.25%   |
| Toshiba MQ01ABD075 752GB                   | 2        | 2      | 6.25%   |
| Seagate ST500DM002-1BD142 500GB            | 2        | 4      | 6.25%   |
| Seagate ST3500413AS 500GB                  | 2        | 4      | 6.25%   |
| WDC WD6400AAKS-22A7B2 640GB                | 1        | 4      | 3.13%   |
| WDC WD50EFRX-68L0BN1 5TB                   | 1        | 1      | 3.13%   |
| WDC WD40EFRX-68WT0N0 4TB                   | 1        | 2      | 3.13%   |
| WDC WD30EZRX-22D8PB0 3TB                   | 1        | 1      | 3.13%   |
| WDC WD2500AAKX-001CA0 250GB                | 1        | 1      | 3.13%   |
| Toshiba DT01ACA100 1TB                     | 1        | 3      | 3.13%   |
| Seagate ST500LM021-1KJ152 500GB            | 1        | 1      | 3.13%   |
| Seagate ST3250318AS 250GB                  | 1        | 1      | 3.13%   |
| Seagate ST3200822AS 200GB                  | 1        | 1      | 3.13%   |
| Seagate ST3160815AS 160GB                  | 1        | 1      | 3.13%   |
| Seagate ST31500341AS 1.5TB                 | 1        | 2      | 3.13%   |
| Seagate ST3120026A 120GB                   | 1        | 1      | 3.13%   |
| Seagate ST31000520AS 1TB                   | 1        | 1      | 3.13%   |
| Seagate ST1000DM003-1CH162 1TB             | 1        | 2      | 3.13%   |
| Samsung Electronics SSD 870 EVO 250GB      | 1        | 2      | 3.13%   |
| Mushkin MKNSSDEC512GB                      | 1        | 1      | 3.13%   |
| Micron Technology M500_MTFDDAK960MAV 960GB | 1        | 4      | 3.13%   |
| Kingston SV300S37A120G 120GB               | 1        | 1      | 3.13%   |
| Intel SSDSC2BB480G4 480GB                  | 1        | 1      | 3.13%   |
| Intel SSDSA2M080G2GC 80GB                  | 1        | 1      | 3.13%   |
| Hitachi HDT721010SLA360 1TB                | 1        | 1      | 3.13%   |
| HGST HTS725050A7E630 500GB                 | 1        | 1      | 3.13%   |
| HGST HTS541010A9E680 1TB                   | 1        | 1      | 3.13%   |
| Crucial CT240M500SSD1 240GB                | 1        | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 18     | 35.48%  |
| WDC                 | 5        | 9      | 16.13%  |
| Toshiba             | 3        | 5      | 9.68%   |
| VisionTek           | 2        | 6      | 6.45%   |
| Intel               | 2        | 2      | 6.45%   |
| HGST                | 2        | 2      | 6.45%   |
| Samsung Electronics | 1        | 2      | 3.23%   |
| Mushkin             | 1        | 1      | 3.23%   |
| Micron Technology   | 1        | 4      | 3.23%   |
| Kingston            | 1        | 1      | 3.23%   |
| Hitachi             | 1        | 1      | 3.23%   |
| Crucial             | 1        | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 18     | 50%     |
| WDC     | 5        | 9      | 22.73%  |
| Toshiba | 3        | 5      | 13.64%  |
| HGST    | 2        | 2      | 9.09%   |
| Hitachi | 1        | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 35     | 68.97%  |
| SSD  | 9        | 17     | 31.03%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| WDC WD10SPZX-00Z10T0 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 160      | 297    | 82.9%   |
| Malfunc  | 28       | 52     | 14.51%  |
| Detected | 4        | 4      | 2.07%   |
| Failed   | 1        | 1      | 0.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 153      | 68.61%  |
| AMD                         | 32       | 14.35%  |
| Samsung Electronics         | 6        | 2.69%   |
| SanDisk                     | 5        | 2.24%   |
| Silicon Motion              | 4        | 1.79%   |
| Nvidia                      | 4        | 1.79%   |
| ASMedia Technology          | 4        | 1.79%   |
| SK hynix                    | 2        | 0.9%    |
| Silicon Image               | 2        | 0.9%    |
| JMicron Technology          | 2        | 0.9%    |
| Chelsio Communications      | 2        | 0.9%    |
| Broadcom / LSI              | 2        | 0.9%    |
| Toshiba                     | 1        | 0.45%   |
| Micron/Crucial Technology   | 1        | 0.45%   |
| MAXIO Technology (Hangzhou) | 1        | 0.45%   |
| Marvell Technology Group    | 1        | 0.45%   |
| Kingston Technology Company | 1        | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 26       | 10%     |
| AMD FCH SATA Controller [AHCI mode]                                              | 13       | 5%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 12       | 4.62%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 11       | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 9        | 3.46%   |
| AMD 400 Series Chipset SATA Controller                                           | 9        | 3.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8        | 3.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7        | 2.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7        | 2.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 7        | 2.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7        | 2.69%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 7        | 2.69%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 6        | 2.31%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 5        | 1.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4        | 1.54%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 4        | 1.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4        | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4        | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4        | 1.54%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3        | 1.15%   |
| SanDisk PC SN520 NVMe SSD                                                        | 3        | 1.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3        | 1.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3        | 1.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3        | 1.15%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3        | 1.15%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3        | 1.15%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3        | 1.15%   |
| AMD FCH SATA Controller [IDE mode]                                               | 3        | 1.15%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 2        | 0.77%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2        | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2        | 0.77%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2        | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2        | 0.77%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 2        | 0.77%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2        | 0.77%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2        | 0.77%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 2        | 0.77%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 2        | 0.77%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]      | 2        | 0.77%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2        | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 163      | 73.09%  |
| IDE  | 29       | 13%     |
| NVMe | 20       | 8.97%   |
| RAID | 6        | 2.69%   |
| SCSI | 3        | 1.35%   |
| SAS  | 2        | 0.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 154      | 81.48%  |
| AMD    | 35       | 18.52%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Intel Core i5-4570 CPU @ 3.20GHz    | 7        | 3.66%   |
| Intel Celeron CPU J3160 @ 1.60GHz   | 7        | 3.66%   |
| Intel Core i5-3570 CPU @ 3.40GHz    | 6        | 3.14%   |
| Intel Core i5-6500 CPU @ 3.20GHz    | 5        | 2.62%   |
| Intel Celeron N5105 @ 2.00GHz       | 5        | 2.62%   |
| Intel Core i5-4590 CPU @ 3.30GHz    | 4        | 2.09%   |
| Intel Core i5-4570TE CPU @ 2.70GHz  | 4        | 2.09%   |
| Intel Celeron J4125 CPU @ 2.00GHz   | 4        | 2.09%   |
| AMD GX-412TC SOC                    | 4        | 2.09%   |
| Intel Xeon                          | 3        | 1.57%   |
| Intel Pentium CPU G4560 @ 3.50GHz   | 3        | 1.57%   |
| Intel Core i7-9700K CPU @ 3.60GHz   | 3        | 1.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz    | 3        | 1.57%   |
| Intel Core i5-7200U CPU @ 2.50GHz   | 3        | 1.57%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz | 2        | 1.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz   | 2        | 1.05%   |
| Intel Core i7-7700 CPU @ 3.60GHz    | 2        | 1.05%   |
| Intel Core i7-4790K CPU @ 4.00GHz   | 2        | 1.05%   |
| Intel Core i5-8400 CPU @ 2.80GHz    | 2        | 1.05%   |
| Intel Core i5-4670 CPU @ 3.40GHz    | 2        | 1.05%   |
| Intel Core i5-4460 CPU @ 3.20GHz    | 2        | 1.05%   |
| Intel Core i5-3470T CPU @ 2.90GHz   | 2        | 1.05%   |
| Intel Core i3-4030U CPU @ 1.90GHz   | 2        | 1.05%   |
| Intel Celeron J4105 CPU @ 1.50GHz   | 2        | 1.05%   |
| Intel Celeron CPU J3455 @ 1.50GHz   | 2        | 1.05%   |
| Intel Celeron CPU J1900 @ 1.99GHz   | 2        | 1.05%   |
| AMD Ryzen 5 2600 Six-Core Processor | 2        | 1.05%   |
| AMD FX-8350 Eight-Core Processor    | 2        | 1.05%   |
| AMD FX-8320E Eight-Core Processor   | 2        | 1.05%   |
| AMD FX-4350 Quad-Core Processor     | 2        | 1.05%   |
| Intel Xeon D-2146NT CPU @ 2.30GHz   | 1        | 0.52%   |
| Intel Xeon CPU X5660 @ 2.80GHz      | 1        | 0.52%   |
| Intel Xeon CPU W3530 @ 2.80GHz      | 1        | 0.52%   |
| Intel Xeon CPU L5640 @ 2.27GHz      | 1        | 0.52%   |
| Intel Xeon CPU E5645 @ 2.40GHz      | 1        | 0.52%   |
| Intel Xeon CPU E5506 @ 2.13GHz      | 1        | 0.52%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz | 1        | 0.52%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz | 1        | 0.52%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz | 1        | 0.52%   |
| Intel Xeon CPU E5-1603 @ 2.80GHz    | 1        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 57       | 30%     |
| Intel Celeron           | 26       | 13.68%  |
| Intel Xeon              | 18       | 9.47%   |
| Intel Core i7           | 17       | 8.95%   |
| Intel Core i3           | 16       | 8.42%   |
| Intel Atom              | 7        | 3.68%   |
| AMD FX                  | 6        | 3.16%   |
| Intel Pentium           | 5        | 2.63%   |
| AMD GX                  | 5        | 2.63%   |
| AMD Ryzen 5             | 4        | 2.11%   |
| Other                   | 3        | 1.58%   |
| AMD Ryzen 7             | 3        | 1.58%   |
| AMD Athlon 64 X2        | 3        | 1.58%   |
| Intel Pentium Dual-Core | 2        | 1.05%   |
| Intel Core 2 Quad       | 2        | 1.05%   |
| Intel Core 2 Duo        | 2        | 1.05%   |
| AMD Ryzen 9             | 2        | 1.05%   |
| AMD Ryzen 3             | 2        | 1.05%   |
| Intel Pentium 4         | 1        | 0.53%   |
| AMD Ryzen Embedded      | 1        | 0.53%   |
| AMD Ryzen 5 PRO         | 1        | 0.53%   |
| AMD Phenom II X6        | 1        | 0.53%   |
| AMD Phenom              | 1        | 0.53%   |
| AMD G                   | 1        | 0.53%   |
| AMD EPYC                | 1        | 0.53%   |
| AMD E                   | 1        | 0.53%   |
| AMD Athlon              | 1        | 0.53%   |
| AMD A6                  | 1        | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 99       | 52.38%  |
| 2       | 45       | 23.81%  |
| 8       | 14       | 7.41%   |
| 6       | 14       | 7.41%   |
| 12      | 5        | 2.65%   |
| 16      | 4        | 2.12%   |
| 10      | 2        | 1.06%   |
| Unknown | 2        | 1.06%   |
| 32      | 1        | 0.53%   |
| 24      | 1        | 0.53%   |
| 11      | 1        | 0.53%   |
| 3       | 1        | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 184      | 98.92%  |
| 2       | 1        | 0.54%   |
| Unknown | 1        | 0.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 119      | 63.64%  |
| 2       | 66       | 35.29%  |
| Unknown | 2        | 1.07%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 38       | 19.9%   |
| KabyLake      | 22       | 11.52%  |
| IvyBridge     | 17       | 8.9%    |
| Skylake       | 12       | 6.28%   |
| Silvermont    | 11       | 5.76%   |
| SandyBridge   | 7        | 3.66%   |
| Piledriver    | 7        | 3.66%   |
| Goldmont plus | 7        | 3.66%   |
| Zen+          | 6        | 3.14%   |
| Westmere      | 6        | 3.14%   |
| Penryn        | 6        | 3.14%   |
| Goldmont      | 6        | 3.14%   |
| Unknown       | 6        | 3.14%   |
| Broadwell     | 5        | 2.62%   |
| Zen           | 4        | 2.09%   |
| Puma          | 4        | 2.09%   |
| CometLake     | 4        | 2.09%   |
| Nehalem       | 3        | 1.57%   |
| K8 Hammer     | 3        | 1.57%   |
| K10           | 3        | 1.57%   |
| Bonnell       | 3        | 1.57%   |
| Zen 3         | 2        | 1.05%   |
| Zen 2         | 2        | 1.05%   |
| Jaguar        | 2        | 1.05%   |
| Bobcat        | 2        | 1.05%   |
| TigerLake     | 1        | 0.52%   |
| NetBurst      | 1        | 0.52%   |
| Core          | 1        | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 116      | 63.39%  |
| Nvidia                     | 31       | 16.94%  |
| AMD                        | 25       | 13.66%  |
| ASPEED Technology          | 7        | 3.83%   |
| Matrox Electronics Systems | 4        | 2.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 26       | 14.13%  |
| Intel HD Graphics 530                                                                    | 9        | 4.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 8        | 4.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8        | 4.35%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7        | 3.8%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 7        | 3.8%    |
| Intel JasperLake [UHD Graphics]                                                          | 5        | 2.72%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 5        | 2.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5        | 2.72%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 2.17%   |
| Intel HD Graphics 630                                                                    | 4        | 2.17%   |
| Intel HD Graphics 610                                                                    | 4        | 2.17%   |
| Intel HD Graphics 500                                                                    | 4        | 2.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4        | 2.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 2.17%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3        | 1.63%   |
| Intel UHD Graphics 620                                                                   | 3        | 1.63%   |
| Intel HD Graphics 620                                                                    | 3        | 1.63%   |
| Intel HD Graphics 5500                                                                   | 3        | 1.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 1.63%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2        | 1.09%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 1.09%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 1.09%   |
| Nvidia GM107GL [Quadro K620]                                                             | 2        | 1.09%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 1.09%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.09%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.09%   |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 1.09%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 1.09%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 2        | 1.09%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 1.09%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 0.54%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 0.54%   |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.54%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.54%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.54%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                                        | 1        | 0.54%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 112      | 59.26%  |
| 1 x Nvidia     | 29       | 15.34%  |
| 1 x AMD        | 25       | 13.23%  |
| Other          | 8        | 4.23%   |
| 1 x ASPEED     | 7        | 3.7%    |
| 1 x Matrox     | 4        | 2.12%   |
| 2 x Intel      | 2        | 1.06%   |
| Intel + Nvidia | 2        | 1.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 162      | 86.17%  |
| Proprietary | 18       | 9.57%   |
| Unknown     | 8        | 4.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 160      | 85.56%  |
| 0.51-1.0   | 8        | 4.28%   |
| 1.01-2.0   | 7        | 3.74%   |
| 3.01-4.0   | 4        | 2.14%   |
| 7.01-8.0   | 3        | 1.6%    |
| 5.01-6.0   | 3        | 1.6%    |
| 2.01-3.0   | 1        | 0.53%   |
| 0.01-0.5   | 1        | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 9        | 21.95%  |
| Dell                 | 5        | 12.2%   |
| BenQ                 | 5        | 12.2%   |
| Samsung Electronics  | 3        | 7.32%   |
| Lenovo               | 3        | 7.32%   |
| Sony                 | 2        | 4.88%   |
| Hewlett-Packard      | 2        | 4.88%   |
| AOC                  | 2        | 4.88%   |
| Acer                 | 2        | 4.88%   |
| ViewSonic            | 1        | 2.44%   |
| Videoseven           | 1        | 2.44%   |
| Toshiba              | 1        | 2.44%   |
| LTV                  | 1        | 2.44%   |
| LG Electronics       | 1        | 2.44%   |
| Insignia             | 1        | 2.44%   |
| ASUSTek Computer     | 1        | 2.44%   |
| Ancor Communications | 1        | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Sony LCD Monitor TV XV 1920x1080                                       | 2        | 4.44%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 2        | 4.44%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 2        | 4.44%   |
| ViewSonic LCD Monitor VSCFA2B 1920x1080 510x290mm 23.1-inch            | 1        | 2.22%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1        | 2.22%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 1        | 2.22%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1210x680mm 54.6-inch | 1        | 2.22%   |
| LTV LTV1280M1A LTV0A3C 1024x768 800x450mm 36.1-inch                    | 1        | 2.22%   |
| LG Electronics LCD Monitor LG Ultra HD 7680x2160                       | 1        | 2.22%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1        | 2.22%   |
| Lenovo LEN-M93z-B  LEN0093 1920x1080 510x290mm 23.1-inch               | 1        | 2.22%   |
| Insignia LCD Monitor BBY0050 1920x1080 700x400mm 31.7-inch             | 1        | 2.22%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1        | 2.22%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch             | 1        | 2.22%   |
| Goldstar W2442 GSM56D9 1920x1080 530x300mm 24.0-inch                   | 1        | 2.22%   |
| Goldstar W2052 GSM4E88 1680x1050 470x300mm 22.0-inch                   | 1        | 2.22%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                   | 1        | 2.22%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 1        | 2.22%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch            | 1        | 2.22%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch            | 1        | 2.22%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch               | 1        | 2.22%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 2.22%   |
| Goldstar LG FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch              | 1        | 2.22%   |
| Goldstar LCD Monitor GSM76F5 1920x1080 700x390mm 31.5-inch             | 1        | 2.22%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                 | 1        | 2.22%   |
| Dell P3222QE DEL4246 3840x2160 700x390mm 31.5-inch                     | 1        | 2.22%   |
| Dell P2311H DEL4067 1920x1080 510x290mm 23.1-inch                      | 1        | 2.22%   |
| Dell P2219H DELA114 1920x1080 480x270mm 21.7-inch                      | 1        | 2.22%   |
| Dell LCD Monitor DELF003 1440x900 410x260mm 19.1-inch                  | 1        | 2.22%   |
| Dell 2001FP DELA008 1600x1200 410x310mm 20.2-inch                      | 1        | 2.22%   |
| BenQ XL2430T BNQ7F3D 1920x1080 530x300mm 24.0-inch                     | 1        | 2.22%   |
| BenQ LCD Monitor PD3200Q                                               | 1        | 2.22%   |
| BenQ LCD Monitor GW2765                                                | 1        | 2.22%   |
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                      | 1        | 2.22%   |
| BenQ G900HD BNQ7816 1366x768 410x230mm 18.5-inch                       | 1        | 2.22%   |
| BenQ BL2780 BNQ802B 1920x1080 600x340mm 27.2-inch                      | 1        | 2.22%   |
| ASUSTek Computer VP228 AUS22A1 1920x1080 480x270mm 21.7-inch           | 1        | 2.22%   |
| AOC 24G2W1G4 AOC2402 1920x1080 530x300mm 24.0-inch                     | 1        | 2.22%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                      | 1        | 2.22%   |
| Ancor Communications VX279 ACI27E4 1920x1080 600x340mm 27.2-inch       | 1        | 2.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 21       | 52.5%   |
| 3840x2160 (4K)     | 5        | 12.5%   |
| 1440x900 (WXGA+)   | 2        | 5%      |
| Unknown            | 2        | 5%      |
| 7680x2160          | 1        | 2.5%    |
| 3440x1440          | 1        | 2.5%    |
| 2560x1440 (QHD)    | 1        | 2.5%    |
| 2560x1080          | 1        | 2.5%    |
| 1680x1050 (WSXGA+) | 1        | 2.5%    |
| 1600x900 (HD+)     | 1        | 2.5%    |
| 1600x1200          | 1        | 2.5%    |
| 1366x768 (WXGA)    | 1        | 2.5%    |
| 1280x1024 (SXGA)   | 1        | 2.5%    |
| 1024x768 (XGA)     | 1        | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 10       | 23.81%  |
| 27      | 5        | 11.9%   |
| 21      | 5        | 11.9%   |
| 19      | 4        | 9.52%   |
| Unknown | 4        | 9.52%   |
| 54      | 3        | 7.14%   |
| 23      | 3        | 7.14%   |
| 34      | 2        | 4.76%   |
| 31      | 2        | 4.76%   |
| 36      | 1        | 2.38%   |
| 22      | 1        | 2.38%   |
| 20      | 1        | 2.38%   |
| 18      | 1        | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 41.46%  |
| 401-500     | 11       | 26.83%  |
| Unknown     | 4        | 9.76%   |
| 701-800     | 3        | 7.32%   |
| 1001-1500   | 3        | 7.32%   |
| 601-700     | 2        | 4.88%   |
| 351-400     | 1        | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 28       | 71.79%  |
| Unknown | 4        | 10.26%  |
| 16/10   | 3        | 7.69%   |
| 21/9    | 2        | 5.13%   |
| 5/4     | 1        | 2.56%   |
| 4/3     | 1        | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 18       | 43.9%   |
| 301-350        | 5        | 12.2%   |
| 151-200        | 5        | 12.2%   |
| 351-500        | 4        | 9.76%   |
| Unknown        | 4        | 9.76%   |
| More than 1000 | 3        | 7.32%   |
| 141-150        | 1        | 2.44%   |
| 501-1000       | 1        | 2.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 28       | 66.67%  |
| 101-120 | 7        | 16.67%  |
| Unknown | 4        | 9.52%   |
| 1-50    | 1        | 2.38%   |
| 161-240 | 1        | 2.38%   |
| 121-160 | 1        | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 145      | 77.13%  |
| 1     | 35       | 18.62%  |
| 2     | 8        | 4.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 144      | 56.03%  |
| Realtek Semiconductor           | 76       | 29.57%  |
| Broadcom                        | 12       | 4.67%   |
| Qualcomm Atheros                | 7        | 2.72%   |
| Solarflare Communications       | 3        | 1.17%   |
| Ralink                          | 2        | 0.78%   |
| Marvell Technology Group        | 2        | 0.78%   |
| Chelsio Communications          | 2        | 0.78%   |
| 3Com                            | 2        | 0.78%   |
| Qualcomm Atheros Communications | 1        | 0.39%   |
| NetGear                         | 1        | 0.39%   |
| Mellanox Technologies           | 1        | 0.39%   |
| MediaTek                        | 1        | 0.39%   |
| IMC Networks                    | 1        | 0.39%   |
| Google                          | 1        | 0.39%   |
| D-Link System                   | 1        | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 66       | 20.89%  |
| Intel I211 Gigabit Network Connection                                         | 25       | 7.91%   |
| Intel Ethernet Connection I217-LM                                             | 20       | 6.33%   |
| Intel 82574L Gigabit Network Connection                                       | 20       | 6.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 12       | 3.8%    |
| Intel I350 Gigabit Network Connection                                         | 11       | 3.48%   |
| Intel 82583V Gigabit Network Connection                                       | 9        | 2.85%   |
| Intel I210 Gigabit Network Connection                                         | 7        | 2.22%   |
| Intel 82580 Gigabit Network Connection                                        | 7        | 2.22%   |
| Intel 82576 Gigabit Network Connection                                        | 7        | 2.22%   |
| Intel Wi-Fi 6 AX200                                                           | 6        | 1.9%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 1.9%    |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 1.58%   |
| Intel Ethernet Controller I225-V                                              | 5        | 1.58%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 1.27%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 4        | 1.27%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3        | 0.95%   |
| Intel Wireless 7260                                                           | 3        | 0.95%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 0.95%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 0.95%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3        | 0.95%   |
| Solarflare SFC9020 10G Ethernet Controller                                    | 2        | 0.63%   |
| Intel Wireless 3165                                                           | 2        | 0.63%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 2        | 0.63%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2        | 0.63%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.63%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.63%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.63%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 0.63%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 0.63%   |
| Intel 82599 10 Gigabit Network Connection                                     | 2        | 0.63%   |
| Intel 82575GB Gigabit Network Connection                                      | 2        | 0.63%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 2        | 0.63%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 2        | 0.63%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 2        | 0.63%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1        | 0.32%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 0.32%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.32%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 18       | 50%     |
| Realtek Semiconductor           | 5        | 13.89%  |
| Qualcomm Atheros                | 5        | 13.89%  |
| Ralink                          | 2        | 5.56%   |
| Broadcom                        | 2        | 5.56%   |
| Qualcomm Atheros Communications | 1        | 2.78%   |
| NetGear                         | 1        | 2.78%   |
| MediaTek                        | 1        | 2.78%   |
| IMC Networks                    | 1        | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 6        | 16.67%  |
| Intel Wireless 7260                                                     | 3        | 8.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3        | 8.33%   |
| Intel Wireless 3165                                                     | 2        | 5.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 2.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1        | 2.78%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 2.78%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1        | 2.78%   |
| Realtek Realtek Bluetooth Adapter                                       | 1        | 2.78%   |
| Ralink RT5592 PCIe Wireless Network Adapter                             | 1        | 2.78%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1        | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1        | 2.78%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 2.78%   |
| Qualcomm Atheros AR958x 802.11abgn Wireless Network Adapter             | 1        | 2.78%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1        | 2.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 2.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 2.78%   |
| NetGear A6200 802.11a/b/g/n/ac Wireless Adapter [Broadcom BCM43526]     | 1        | 2.78%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 2.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1        | 2.78%   |
| Intel Centrino Wireless-N 105                                           | 1        | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 2.78%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 1        | 2.78%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 1        | 2.78%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1        | 2.78%   |
| Broadcom BCM4321 802.11b/g/n                                            | 1        | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 135      | 57.94%  |
| Realtek Semiconductor     | 75       | 32.19%  |
| Broadcom                  | 10       | 4.29%   |
| Solarflare Communications | 3        | 1.29%   |
| Qualcomm Atheros          | 2        | 0.86%   |
| Marvell Technology Group  | 2        | 0.86%   |
| Chelsio Communications    | 2        | 0.86%   |
| 3Com                      | 2        | 0.86%   |
| Google                    | 1        | 0.43%   |
| D-Link System             | 1        | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 66       | 23.74%  |
| Intel I211 Gigabit Network Connection                                         | 25       | 8.99%   |
| Intel Ethernet Connection I217-LM                                             | 20       | 7.19%   |
| Intel 82574L Gigabit Network Connection                                       | 20       | 7.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 12       | 4.32%   |
| Intel I350 Gigabit Network Connection                                         | 11       | 3.96%   |
| Intel 82583V Gigabit Network Connection                                       | 9        | 3.24%   |
| Intel I210 Gigabit Network Connection                                         | 7        | 2.52%   |
| Intel 82580 Gigabit Network Connection                                        | 7        | 2.52%   |
| Intel 82576 Gigabit Network Connection                                        | 7        | 2.52%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 2.16%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 1.8%    |
| Intel Ethernet Controller I225-V                                              | 5        | 1.8%    |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 1.44%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 4        | 1.44%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3        | 1.08%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.08%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 1.08%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3        | 1.08%   |
| Solarflare SFC9020 10G Ethernet Controller                                    | 2        | 0.72%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 2        | 0.72%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2        | 0.72%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.72%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.72%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.72%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 0.72%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 0.72%   |
| Intel 82599 10 Gigabit Network Connection                                     | 2        | 0.72%   |
| Intel 82575GB Gigabit Network Connection                                      | 2        | 0.72%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 2        | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 2        | 0.72%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 2        | 0.72%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1        | 0.36%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.36%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1        | 0.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.36%   |
| Intel Ethernet Controller X550                                                | 1        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 185      | 83.33%  |
| WiFi     | 35       | 15.77%  |
| Unknown  | 2        | 0.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 181      | 95.77%  |
| WiFi     | 8        | 4.23%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 46       | 24.34%  |
| 1     | 36       | 19.05%  |
| 4     | 32       | 16.93%  |
| 3     | 30       | 15.87%  |
| 5     | 21       | 11.11%  |
| 6     | 15       | 7.94%   |
| 7     | 4        | 2.12%   |
| 8     | 2        | 1.06%   |
| 10    | 1        | 0.53%   |
| 9     | 1        | 0.53%   |
| 0     | 1        | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 168      | 87.96%  |
| Yes  | 23       | 12.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 14       | 60.87%  |
| Cambridge Silicon Radio | 4        | 17.39%  |
| Realtek Semiconductor   | 1        | 4.35%   |
| MediaTek                | 1        | 4.35%   |
| IMC Networks            | 1        | 4.35%   |
| Foxconn / Hon Hai       | 1        | 4.35%   |
| Apple                   | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                | 5        | 21.74%  |
| Intel Bluetooth wireless interface                   | 4        | 17.39%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 4        | 17.39%  |
| Intel Wireless-AC 3168 Bluetooth                     | 3        | 13.04%  |
| Realtek  Bluetooth 4.2 Adapter                       | 1        | 4.35%   |
| MediaTek Wireless_Device                             | 1        | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 1        | 4.35%   |
| Intel AX201 Bluetooth                                | 1        | 4.35%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip | 1        | 4.35%   |
| Foxconn / Hon Hai Bluetooth USB Module               | 1        | 4.35%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                 | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 113      | 61.08%  |
| AMD                 | 32       | 17.3%   |
| Nvidia              | 30       | 16.22%  |
| Logitech            | 3        | 1.62%   |
| C-Media Electronics | 2        | 1.08%   |
| Yamaha              | 1        | 0.54%   |
| Texas Instruments   | 1        | 0.54%   |
| SteelSeries ApS     | 1        | 0.54%   |
| KTMicro             | 1        | 0.54%   |
| Creative Labs       | 1        | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 24       | 10.57%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 24       | 10.57%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9        | 3.96%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8        | 3.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7        | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7        | 3.08%   |
| Intel 200 Series PCH HD Audio                                                                     | 7        | 3.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7        | 3.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6        | 2.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5        | 2.2%    |
| Intel Jasper Lake HD Audio                                                                        | 5        | 2.2%    |
| Intel Cannon Lake PCH cAVS                                                                        | 5        | 2.2%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5        | 2.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5        | 2.2%    |
| Nvidia High Definition Audio Controller                                                           | 4        | 1.76%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4        | 1.76%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4        | 1.76%   |
| Intel Broadwell-U Audio Controller                                                                | 4        | 1.76%   |
| Intel 8 Series HD Audio Controller                                                                | 4        | 1.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4        | 1.76%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 1.32%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 1.32%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 1.32%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 1.32%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 1.32%   |
| AMD FCH Azalia Controller                                                                         | 3        | 1.32%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 1.32%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2        | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 0.88%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2        | 0.88%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2        | 0.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2        | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2        | 0.88%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2        | 0.88%   |
| AMD Navi 10 HDMI Audio                                                                            | 2        | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2        | 0.88%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 2        | 0.88%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2        | 0.88%   |
| Yamaha Steinberg UR22mkII                                                                         | 1        | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 34       | 16.04%  |
| Samsung Electronics | 33       | 15.57%  |
| SK hynix            | 30       | 14.15%  |
| Unknown             | 21       | 9.91%   |
| Corsair             | 19       | 8.96%   |
| Crucial             | 15       | 7.08%   |
| G.Skill             | 14       | 6.6%    |
| Micron Technology   | 10       | 4.72%   |
| Apacer              | 5        | 2.36%   |
| Team                | 4        | 1.89%   |
| Ramaxel Technology  | 4        | 1.89%   |
| Unknown (0x0C26)    | 3        | 1.42%   |
| Patriot             | 3        | 1.42%   |
| A-DATA Technology   | 3        | 1.42%   |
| Unknown             | 3        | 1.42%   |
| Timetec             | 2        | 0.94%   |
| OCZ                 | 2        | 0.94%   |
| Nanya Technology    | 2        | 0.94%   |
| V-Color             | 1        | 0.47%   |
| Unknown (ABCD)      | 1        | 0.47%   |
| Unknown (0x0DD5)    | 1        | 0.47%   |
| Toshiba             | 1        | 0.47%   |
| Cors                | 1        | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 5        | 2.19%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 4        | 1.75%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s     | 4        | 1.75%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s | 4        | 1.75%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s     | 3        | 1.32%   |
| Unknown                                                 | 3        | 1.32%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 2        | 0.88%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 0.88%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 2        | 0.88%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 2        | 0.88%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.88%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.88%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s    | 2        | 0.88%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s    | 2        | 0.88%   |
| SK hynix RAM HMA451R7AFR8N-TF 4GB RIMM DDR4 2133MT/s    | 2        | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 2        | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s     | 2        | 0.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s     | 2        | 0.88%   |
| Micron RAM 9ASF51272PZ-2G1A2 4GB RIMM DDR4 2133MT/s     | 2        | 0.88%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s     | 2        | 0.88%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s      | 2        | 0.88%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s     | 2        | 0.88%   |
| Corsair RAM CMV8GX3M1A1333C9 8GB DIMM DDR3 1333MT/s     | 2        | 0.88%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1333MT/s     | 2        | 0.88%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s   | 2        | 0.88%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s  | 2        | 0.88%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 2667MT/s  | 2        | 0.88%   |
| V-Color RAM VCOLOR-TD2G16C9-H8 2GB DIMM 1333MT/s        | 1        | 0.44%   |
| Unknown RAM Module 8GB DIMM DDR4 2666MT/s               | 1        | 0.44%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s               | 1        | 0.44%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 0.44%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                  | 1        | 0.44%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s               | 1        | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s              | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR 1066MT/s                | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM 400MT/s                     | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s             | 1        | 0.44%   |
| Unknown RAM Module 1GB DIMM SDRAM 667MT/s               | 1        | 0.44%   |
| Unknown RAM Module 1GB DIMM SDRAM                       | 1        | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 90       | 50%     |
| DDR4    | 68       | 37.78%  |
| Unknown | 9        | 5%      |
| DDR2    | 6        | 3.33%   |
| SDRAM   | 4        | 2.22%   |
| DDR     | 2        | 1.11%   |
| LPDDR4  | 1        | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 126      | 72%     |
| SODIMM | 46       | 26.29%  |
| RIMM   | 3        | 1.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 72       | 36.73%  |
| 8192  | 67       | 34.18%  |
| 16384 | 25       | 12.76%  |
| 2048  | 24       | 12.24%  |
| 1024  | 6        | 3.06%   |
| 32768 | 1        | 0.51%   |
| 512   | 1        | 0.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 68       | 34.69%  |
| 1333    | 27       | 13.78%  |
| 2400    | 19       | 9.69%   |
| 2133    | 18       | 9.18%   |
| 2667    | 15       | 7.65%   |
| 3200    | 12       | 6.12%   |
| 2666    | 6        | 3.06%   |
| 800     | 6        | 3.06%   |
| 667     | 4        | 2.04%   |
| Unknown | 4        | 2.04%   |
| 3600    | 3        | 1.53%   |
| 1066    | 3        | 1.53%   |
| 1866    | 2        | 1.02%   |
| 1067    | 2        | 1.02%   |
| 400     | 2        | 1.02%   |
| 5200    | 1        | 0.51%   |
| 3400    | 1        | 0.51%   |
| 3000    | 1        | 0.51%   |
| 1334    | 1        | 0.51%   |
| 333     | 1        | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 66.67%  |
| Brother Industries | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| HP LaserJet 2200          | 1        | 33.33%  |
| HP Color LaserJet CP1215  | 1        | 33.33%  |
| Brother HL-L5200DW series | 1        | 33.33%  |

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
| Canon CanoScan LiDE 220 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 2        | 50%     |
| Microdia            | 1        | 25%     |
| Chicony Electronics | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Microdia JOYACCESS JA-Webcam | 1        | 25%     |
| Logitech Webcam C310         | 1        | 25%     |
| Logitech HD Pro Webcam C920  | 1        | 25%     |
| Chicony HP 0.3MP Webcam      | 1        | 25%     |

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
| 1     | 109      | 56.77%  |
| 0     | 57       | 29.69%  |
| 2     | 21       | 10.94%  |
| 3     | 3        | 1.56%   |
| 4     | 2        | 1.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 121      | 77.56%  |
| Net/wireless             | 12       | 7.69%   |
| Sound                    | 5        | 3.21%   |
| Bluetooth                | 5        | 3.21%   |
| Firewire controller      | 4        | 2.56%   |
| Net/ethernet             | 3        | 1.92%   |
| Card reader              | 3        | 1.92%   |
| Network                  | 2        | 1.28%   |
| Storage/raid             | 1        | 0.64%   |

