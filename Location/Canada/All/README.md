BSD in Canada - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in Canada.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Canada/Desktop/README.md) and [notebooks](/Location/Canada/Notebook/README.md).

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

Total: 505

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Panasonic     | CF-54-1                     | Notebook    | [0c5820ea0d](https://bsd-hardware.info/?probe=0c5820ea0d) | Dec 01, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cfaeaeb2f2](https://bsd-hardware.info/?probe=cfaeaeb2f2) | Nov 29, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [e8e158f783](https://bsd-hardware.info/?probe=e8e158f783) | Nov 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [512a05eefb](https://bsd-hardware.info/?probe=512a05eefb) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5f0b8df8d0](https://bsd-hardware.info/?probe=5f0b8df8d0) | Nov 27, 2022 |
| CompuLab      | fit-PC3                     | Mini pc     | [34dd85f78d](https://bsd-hardware.info/?probe=34dd85f78d) | Nov 26, 2022 |
| CompuLab      | fit-PC3                     | Mini pc     | [54a64a269c](https://bsd-hardware.info/?probe=54a64a269c) | Nov 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [222e69ff59](https://bsd-hardware.info/?probe=222e69ff59) | Nov 26, 2022 |
| Protectli     | FW6                         | Desktop     | [74510f3177](https://bsd-hardware.info/?probe=74510f3177) | Nov 25, 2022 |
| HP            | 8055                        | Desktop     | [ace4570d15](https://bsd-hardware.info/?probe=ace4570d15) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [7258992b77](https://bsd-hardware.info/?probe=7258992b77) | Nov 24, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [e0f08b66c2](https://bsd-hardware.info/?probe=e0f08b66c2) | Nov 21, 2022 |
| Lenovo        | ThinkPad X230 2325T4T       | Notebook    | [f0cc17c7eb](https://bsd-hardware.info/?probe=f0cc17c7eb) | Nov 21, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [8257d11669](https://bsd-hardware.info/?probe=8257d11669) | Nov 20, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [7c7a121711](https://bsd-hardware.info/?probe=7c7a121711) | Nov 18, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [5875ecec9f](https://bsd-hardware.info/?probe=5875ecec9f) | Nov 18, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [0d37f1878b](https://bsd-hardware.info/?probe=0d37f1878b) | Nov 17, 2022 |
| AZW           | U59                         | Desktop     | [25e1349c5f](https://bsd-hardware.info/?probe=25e1349c5f) | Nov 17, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [269f915ce2](https://bsd-hardware.info/?probe=269f915ce2) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [4044f32351](https://bsd-hardware.info/?probe=4044f32351) | Nov 12, 2022 |
| Lenovo        | 30D9 No DPK                 | Desktop     | [bb9cf416c4](https://bsd-hardware.info/?probe=bb9cf416c4) | Nov 11, 2022 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [b8874a6df3](https://bsd-hardware.info/?probe=b8874a6df3) | Nov 10, 2022 |
| ASUSTek       | P8H77-I                     | Desktop     | [04ea3cc97d](https://bsd-hardware.info/?probe=04ea3cc97d) | Nov 09, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [32331d772c](https://bsd-hardware.info/?probe=32331d772c) | Nov 08, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [a84d0a0380](https://bsd-hardware.info/?probe=a84d0a0380) | Nov 08, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [e8aea441aa](https://bsd-hardware.info/?probe=e8aea441aa) | Nov 06, 2022 |
| Datto         | SSD                         | Desktop     | [235483110d](https://bsd-hardware.info/?probe=235483110d) | Nov 05, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [871a5c449f](https://bsd-hardware.info/?probe=871a5c449f) | Nov 01, 2022 |
| Dell          | 09T7VV A02                  | Server      | [6e89de5b97](https://bsd-hardware.info/?probe=6e89de5b97) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [5758027775](https://bsd-hardware.info/?probe=5758027775) | Oct 31, 2022 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [e5716f886a](https://bsd-hardware.info/?probe=e5716f886a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [34f0a2bc03](https://bsd-hardware.info/?probe=34f0a2bc03) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS10N00    | Notebook    | [04ce25bd7f](https://bsd-hardware.info/?probe=04ce25bd7f) | Oct 29, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [e3c5057898](https://bsd-hardware.info/?probe=e3c5057898) | Oct 29, 2022 |
| Unknown       | Unknown                     | Notebook    | [2df5c5b434](https://bsd-hardware.info/?probe=2df5c5b434) | Oct 28, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [6dda683e10](https://bsd-hardware.info/?probe=6dda683e10) | Oct 28, 2022 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [f2fafaa9e3](https://bsd-hardware.info/?probe=f2fafaa9e3) | Oct 27, 2022 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [d96fbc17b5](https://bsd-hardware.info/?probe=d96fbc17b5) | Oct 27, 2022 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [088e0245af](https://bsd-hardware.info/?probe=088e0245af) | Oct 27, 2022 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [6e8067d4d8](https://bsd-hardware.info/?probe=6e8067d4d8) | Oct 26, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [b7a4ee06a6](https://bsd-hardware.info/?probe=b7a4ee06a6) | Oct 26, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [f2236f17ee](https://bsd-hardware.info/?probe=f2236f17ee) | Oct 25, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [c4bbcf9537](https://bsd-hardware.info/?probe=c4bbcf9537) | Oct 24, 2022 |
| HP            | 18E4                        | Desktop     | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [c3f0ae254e](https://bsd-hardware.info/?probe=c3f0ae254e) | Oct 17, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [b4e02e3f51](https://bsd-hardware.info/?probe=b4e02e3f51) | Oct 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [00b5fa7a4e](https://bsd-hardware.info/?probe=00b5fa7a4e) | Oct 13, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [edead8a3ae](https://bsd-hardware.info/?probe=edead8a3ae) | Oct 11, 2022 |
| MSI           | GL65 Leopard 10SFSK         | Notebook    | [2ea7c7f9a2](https://bsd-hardware.info/?probe=2ea7c7f9a2) | Oct 10, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [ce728798a1](https://bsd-hardware.info/?probe=ce728798a1) | Oct 07, 2022 |
| Sophos        | XG                          | Firewall    | [cf528e776d](https://bsd-hardware.info/?probe=cf528e776d) | Oct 05, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [79060c241b](https://bsd-hardware.info/?probe=79060c241b) | Oct 03, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [3590d4504c](https://bsd-hardware.info/?probe=3590d4504c) | Oct 02, 2022 |
| MSI           | GL65 Leopard 10SFSK         | Notebook    | [489567748e](https://bsd-hardware.info/?probe=489567748e) | Oct 01, 2022 |
| Intel         | S1200RP_SE G62252-406       | Server      | [4763fe7595](https://bsd-hardware.info/?probe=4763fe7595) | Sep 30, 2022 |
| Intel         | H81U                        | Notebook    | [fa8c32528a](https://bsd-hardware.info/?probe=fa8c32528a) | Sep 28, 2022 |
| Acer          | Swift SF313-52              | Notebook    | [83516dabac](https://bsd-hardware.info/?probe=83516dabac) | Sep 28, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [33b252016c](https://bsd-hardware.info/?probe=33b252016c) | Sep 26, 2022 |
| Acer          | Swift SF313-52              | Notebook    | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [a1a2cbc6c9](https://bsd-hardware.info/?probe=a1a2cbc6c9) | Sep 20, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | Notebook    | [2f1f82558e](https://bsd-hardware.info/?probe=2f1f82558e) | Sep 18, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [22f23ccfa5](https://bsd-hardware.info/?probe=22f23ccfa5) | Sep 17, 2022 |
| Google        | Peppy                       | Notebook    | [80ffa77224](https://bsd-hardware.info/?probe=80ffa77224) | Sep 15, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [21e7190ff2](https://bsd-hardware.info/?probe=21e7190ff2) | Sep 11, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [3c152ae7bd](https://bsd-hardware.info/?probe=3c152ae7bd) | Sep 11, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [89b185547b](https://bsd-hardware.info/?probe=89b185547b) | Sep 10, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [a854e50942](https://bsd-hardware.info/?probe=a854e50942) | Sep 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [860518eb18](https://bsd-hardware.info/?probe=860518eb18) | Sep 04, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [b53e1d28cd](https://bsd-hardware.info/?probe=b53e1d28cd) | Sep 04, 2022 |
| Intel         | DQ67EP AAG12529-307         | Desktop     | [1fb1fd6705](https://bsd-hardware.info/?probe=1fb1fd6705) | Sep 03, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [2e4b87acd2](https://bsd-hardware.info/?probe=2e4b87acd2) | Sep 03, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [b3a1456bb4](https://bsd-hardware.info/?probe=b3a1456bb4) | Aug 29, 2022 |
| HP            | 8103 A01                    | Mini pc     | [de20688262](https://bsd-hardware.info/?probe=de20688262) | Aug 27, 2022 |
| Dell          | 09T7VV A07                  | Server      | [0325ade874](https://bsd-hardware.info/?probe=0325ade874) | Aug 23, 2022 |
| Gigabyte      | MBHM87P-00                  | Desktop     | [9fa5160871](https://bsd-hardware.info/?probe=9fa5160871) | Aug 22, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [04df24b0b8](https://bsd-hardware.info/?probe=04df24b0b8) | Aug 20, 2022 |
| Dell          | 04Y8V0 A02                  | Desktop     | [9fc4b3c63e](https://bsd-hardware.info/?probe=9fc4b3c63e) | Aug 17, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [753f277d5c](https://bsd-hardware.info/?probe=753f277d5c) | Aug 16, 2022 |
| AZW           | Green G1                    | Desktop     | [4bccb24702](https://bsd-hardware.info/?probe=4bccb24702) | Aug 15, 2022 |
| Dell          | 04Y8V0 A02                  | Desktop     | [a21172360d](https://bsd-hardware.info/?probe=a21172360d) | Aug 15, 2022 |
| Dell          | 04Y8V0 A02                  | Desktop     | [6acccc63ff](https://bsd-hardware.info/?probe=6acccc63ff) | Aug 15, 2022 |
| Lenovo        | 3111 SDK0J40705 WIN 3425... | Desktop     | [6927813b1d](https://bsd-hardware.info/?probe=6927813b1d) | Aug 13, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [a45977c76b](https://bsd-hardware.info/?probe=a45977c76b) | Aug 10, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [236cd1ee65](https://bsd-hardware.info/?probe=236cd1ee65) | Aug 08, 2022 |
| Biostar       | TA880GU3+                   | Desktop     | [8b0c8541b3](https://bsd-hardware.info/?probe=8b0c8541b3) | Aug 06, 2022 |
| MSI           | 785GT-E63                   | Desktop     | [8c307fb033](https://bsd-hardware.info/?probe=8c307fb033) | Aug 03, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [83bbf8e819](https://bsd-hardware.info/?probe=83bbf8e819) | Aug 03, 2022 |
| Intel         | H81U                        | Notebook    | [b5e2598580](https://bsd-hardware.info/?probe=b5e2598580) | Aug 03, 2022 |
| Intel         | H81U                        | Notebook    | [8f50dbe259](https://bsd-hardware.info/?probe=8f50dbe259) | Aug 01, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [860b06cb6b](https://bsd-hardware.info/?probe=860b06cb6b) | Aug 01, 2022 |
| HP            | 8055                        | Desktop     | [6a8a361dae](https://bsd-hardware.info/?probe=6a8a361dae) | Jul 31, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [900c62c2ba](https://bsd-hardware.info/?probe=900c62c2ba) | Jul 30, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [27b986a422](https://bsd-hardware.info/?probe=27b986a422) | Jul 30, 2022 |
| HP            | 8055                        | Desktop     | [41d802a80a](https://bsd-hardware.info/?probe=41d802a80a) | Jul 29, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [7be6ba0021](https://bsd-hardware.info/?probe=7be6ba0021) | Jul 29, 2022 |
| HP            | 18E9                        | Desktop     | [56460b095e](https://bsd-hardware.info/?probe=56460b095e) | Jul 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [03497b7b2a](https://bsd-hardware.info/?probe=03497b7b2a) | Jul 27, 2022 |
| Unknown       | Unknown                     | Firewall    | [15c779bfe1](https://bsd-hardware.info/?probe=15c779bfe1) | Jul 27, 2022 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [3df3bd2f62](https://bsd-hardware.info/?probe=3df3bd2f62) | Jul 22, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [1ed99ad502](https://bsd-hardware.info/?probe=1ed99ad502) | Jul 20, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [46a6f4e8f3](https://bsd-hardware.info/?probe=46a6f4e8f3) | Jul 19, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [7ca3d2715c](https://bsd-hardware.info/?probe=7ca3d2715c) | Jul 19, 2022 |
| Lenovo        | ThinkCentre M91 4518E4U     | Desktop     | [8dd1034cfa](https://bsd-hardware.info/?probe=8dd1034cfa) | Jul 16, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [7530b2fc5f](https://bsd-hardware.info/?probe=7530b2fc5f) | Jul 15, 2022 |
| AZW           | Green G1                    | Desktop     | [9a2120ae5a](https://bsd-hardware.info/?probe=9a2120ae5a) | Jul 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [bd1a86e875](https://bsd-hardware.info/?probe=bd1a86e875) | Jul 10, 2022 |
| Datto         | SSD                         | Desktop     | [639d28d449](https://bsd-hardware.info/?probe=639d28d449) | Jul 08, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [a945073364](https://bsd-hardware.info/?probe=a945073364) | Jul 07, 2022 |
| Protectli     | FW6                         | Desktop     | [e82838534b](https://bsd-hardware.info/?probe=e82838534b) | Jul 06, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [ac861b1ee3](https://bsd-hardware.info/?probe=ac861b1ee3) | Jun 25, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [598ecb5457](https://bsd-hardware.info/?probe=598ecb5457) | Jun 25, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [a6a5de19ae](https://bsd-hardware.info/?probe=a6a5de19ae) | Jun 23, 2022 |
| HP            | 82A2                        | Desktop     | [77c244bd43](https://bsd-hardware.info/?probe=77c244bd43) | Jun 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a57a2f609c](https://bsd-hardware.info/?probe=a57a2f609c) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [1febab0774](https://bsd-hardware.info/?probe=1febab0774) | Jun 12, 2022 |
| HP            | 1998                        | Desktop     | [1bb67075dd](https://bsd-hardware.info/?probe=1bb67075dd) | Jun 12, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [5054729300](https://bsd-hardware.info/?probe=5054729300) | Jun 11, 2022 |
| HP            | 1998                        | Desktop     | [54a6daf0a6](https://bsd-hardware.info/?probe=54a6daf0a6) | Jun 11, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [3b8d6cb36e](https://bsd-hardware.info/?probe=3b8d6cb36e) | Jun 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [26cd129290](https://bsd-hardware.info/?probe=26cd129290) | Jun 06, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [f3c197bdfb](https://bsd-hardware.info/?probe=f3c197bdfb) | Jun 04, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [8e8ef96421](https://bsd-hardware.info/?probe=8e8ef96421) | Jun 04, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [dce99bec81](https://bsd-hardware.info/?probe=dce99bec81) | Jun 03, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [8ca71ddf4d](https://bsd-hardware.info/?probe=8ca71ddf4d) | Jun 02, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [cc70f5d86f](https://bsd-hardware.info/?probe=cc70f5d86f) | Jun 01, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [9d5edd9fa9](https://bsd-hardware.info/?probe=9d5edd9fa9) | May 29, 2022 |
| Dell          | 0M3F6C A01                  | Desktop     | [21d45bc75d](https://bsd-hardware.info/?probe=21d45bc75d) | May 23, 2022 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [c956536edd](https://bsd-hardware.info/?probe=c956536edd) | May 23, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [6d7475e9c9](https://bsd-hardware.info/?probe=6d7475e9c9) | May 22, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [963fa158b5](https://bsd-hardware.info/?probe=963fa158b5) | May 22, 2022 |
| Sophos        | SG                          | Firewall    | [9f76b20afd](https://bsd-hardware.info/?probe=9f76b20afd) | May 22, 2022 |
| Dell          | Studio 1747                 | Notebook    | [7ae292b282](https://bsd-hardware.info/?probe=7ae292b282) | May 21, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [5d31f6f5a8](https://bsd-hardware.info/?probe=5d31f6f5a8) | May 19, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [1014f7f61c](https://bsd-hardware.info/?probe=1014f7f61c) | May 18, 2022 |
| Dell          | 0DXJD9 A01                  | Desktop     | [be13c9069c](https://bsd-hardware.info/?probe=be13c9069c) | May 18, 2022 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [b74299204a](https://bsd-hardware.info/?probe=b74299204a) | May 18, 2022 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [9ec22ea24c](https://bsd-hardware.info/?probe=9ec22ea24c) | May 17, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [c7af1dd7bf](https://bsd-hardware.info/?probe=c7af1dd7bf) | May 16, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [30cfcd5004](https://bsd-hardware.info/?probe=30cfcd5004) | May 15, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [44ab2d6faa](https://bsd-hardware.info/?probe=44ab2d6faa) | May 14, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [9af60bd6e4](https://bsd-hardware.info/?probe=9af60bd6e4) | May 14, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [fd066b2db9](https://bsd-hardware.info/?probe=fd066b2db9) | May 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [0958a64385](https://bsd-hardware.info/?probe=0958a64385) | May 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [0d62d4e3cd](https://bsd-hardware.info/?probe=0d62d4e3cd) | May 09, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [a7111b84cb](https://bsd-hardware.info/?probe=a7111b84cb) | May 08, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [3e60a82218](https://bsd-hardware.info/?probe=3e60a82218) | May 06, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [daed3f9401](https://bsd-hardware.info/?probe=daed3f9401) | May 06, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [a6393754b4](https://bsd-hardware.info/?probe=a6393754b4) | May 05, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [cf2f288b93](https://bsd-hardware.info/?probe=cf2f288b93) | May 04, 2022 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [774cab5326](https://bsd-hardware.info/?probe=774cab5326) | May 03, 2022 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [4b1abdd507](https://bsd-hardware.info/?probe=4b1abdd507) | May 03, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [2884106c6b](https://bsd-hardware.info/?probe=2884106c6b) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [00ba6ca9f8](https://bsd-hardware.info/?probe=00ba6ca9f8) | May 03, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [6b77fe651f](https://bsd-hardware.info/?probe=6b77fe651f) | May 03, 2022 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [f3c30a6190](https://bsd-hardware.info/?probe=f3c30a6190) | May 02, 2022 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [abd8754907](https://bsd-hardware.info/?probe=abd8754907) | May 01, 2022 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [1ce63e2214](https://bsd-hardware.info/?probe=1ce63e2214) | Apr 29, 2022 |
| HP            | 1495                        | Desktop     | [6e0f1cc72e](https://bsd-hardware.info/?probe=6e0f1cc72e) | Apr 29, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [586d311314](https://bsd-hardware.info/?probe=586d311314) | Apr 28, 2022 |
| HP            | 1998                        | Desktop     | [1244e0583b](https://bsd-hardware.info/?probe=1244e0583b) | Apr 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [b3d5defed1](https://bsd-hardware.info/?probe=b3d5defed1) | Apr 26, 2022 |
| Supermicro    | X12SCZ-TLN4FA               | Server      | [2a9ac1e6ee](https://bsd-hardware.info/?probe=2a9ac1e6ee) | Apr 23, 2022 |
| Sophos        | SG                          | Firewall    | [cbd2585bf3](https://bsd-hardware.info/?probe=cbd2585bf3) | Apr 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [4166c67369](https://bsd-hardware.info/?probe=4166c67369) | Apr 20, 2022 |
| Dell          | G5 5090                     | Desktop     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [01945539d9](https://bsd-hardware.info/?probe=01945539d9) | Apr 17, 2022 |
| Sophos        | SG                          | Firewall    | [ed297e4274](https://bsd-hardware.info/?probe=ed297e4274) | Apr 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [979e868c51](https://bsd-hardware.info/?probe=979e868c51) | Apr 16, 2022 |
| Dell          | 0DXJD9 A01                  | Desktop     | [4023d86091](https://bsd-hardware.info/?probe=4023d86091) | Apr 15, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [29be552d6a](https://bsd-hardware.info/?probe=29be552d6a) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [1173feae11](https://bsd-hardware.info/?probe=1173feae11) | Apr 13, 2022 |
| Dell          | 0DXJD9 A01                  | Desktop     | [6dac56f3bb](https://bsd-hardware.info/?probe=6dac56f3bb) | Apr 11, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [641d1574ce](https://bsd-hardware.info/?probe=641d1574ce) | Apr 11, 2022 |
| Toshiba       | Satellite Pro T130          | Notebook    | [62dd51afcf](https://bsd-hardware.info/?probe=62dd51afcf) | Apr 11, 2022 |
| HP            | 8103 A01                    | Mini pc     | [1fa67a8d17](https://bsd-hardware.info/?probe=1fa67a8d17) | Apr 04, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [e79f120d82](https://bsd-hardware.info/?probe=e79f120d82) | Apr 01, 2022 |
| Dell          | 081N4V A06                  | Server      | [700e5de168](https://bsd-hardware.info/?probe=700e5de168) | Apr 01, 2022 |
| PC Engines    | APU                         | Desktop     | [e266947055](https://bsd-hardware.info/?probe=e266947055) | Mar 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [ef1a743845](https://bsd-hardware.info/?probe=ef1a743845) | Mar 28, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [1176fca4ab](https://bsd-hardware.info/?probe=1176fca4ab) | Mar 27, 2022 |
| ASUSTek       | ET2411_W8                   | All in one  | [fb186da68e](https://bsd-hardware.info/?probe=fb186da68e) | Mar 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [d0e7b62eda](https://bsd-hardware.info/?probe=d0e7b62eda) | Mar 25, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cf576c571d](https://bsd-hardware.info/?probe=cf576c571d) | Mar 22, 2022 |
| HP            | 213D A01                    | Desktop     | [6baba4f9c1](https://bsd-hardware.info/?probe=6baba4f9c1) | Mar 20, 2022 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [3727ba82af](https://bsd-hardware.info/?probe=3727ba82af) | Mar 19, 2022 |
| ASUSTek       | ET2411_W8                   | All in one  | [b95da98f21](https://bsd-hardware.info/?probe=b95da98f21) | Mar 17, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [f22a45488b](https://bsd-hardware.info/?probe=f22a45488b) | Mar 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a5fd383c40](https://bsd-hardware.info/?probe=a5fd383c40) | Mar 14, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [6024b9491d](https://bsd-hardware.info/?probe=6024b9491d) | Mar 06, 2022 |
| MSI           | MS-7388                     | Desktop     | [ad8209dbdb](https://bsd-hardware.info/?probe=ad8209dbdb) | Mar 05, 2022 |
| MSI           | MS-7388                     | Desktop     | [a59bca8bde](https://bsd-hardware.info/?probe=a59bca8bde) | Mar 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [a6abb45607](https://bsd-hardware.info/?probe=a6abb45607) | Mar 04, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [589f10057f](https://bsd-hardware.info/?probe=589f10057f) | Mar 01, 2022 |
| Intel         | H81U                        | Notebook    | [71068a0577](https://bsd-hardware.info/?probe=71068a0577) | Mar 01, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [e14fd85d4a](https://bsd-hardware.info/?probe=e14fd85d4a) | Feb 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [6b2550968e](https://bsd-hardware.info/?probe=6b2550968e) | Feb 23, 2022 |
| Intel         | NUC5CPYB H61145-404         | Mini pc     | [5f4e1c30b8](https://bsd-hardware.info/?probe=5f4e1c30b8) | Feb 19, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b69015f0e0](https://bsd-hardware.info/?probe=b69015f0e0) | Feb 16, 2022 |
| PC Engines    | apu4                        | Desktop     | [09f27a0f23](https://bsd-hardware.info/?probe=09f27a0f23) | Feb 14, 2022 |
| Protectli     | FW6                         | Desktop     | [d33b2f1244](https://bsd-hardware.info/?probe=d33b2f1244) | Feb 13, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [04bee98c7e](https://bsd-hardware.info/?probe=04bee98c7e) | Feb 12, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [bd63b06ea9](https://bsd-hardware.info/?probe=bd63b06ea9) | Feb 11, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [12ccb8699b](https://bsd-hardware.info/?probe=12ccb8699b) | Feb 08, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [0d3b560aad](https://bsd-hardware.info/?probe=0d3b560aad) | Feb 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [3dabf0503d](https://bsd-hardware.info/?probe=3dabf0503d) | Feb 08, 2022 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [53abdfa3b1](https://bsd-hardware.info/?probe=53abdfa3b1) | Feb 07, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [1dafdcc71a](https://bsd-hardware.info/?probe=1dafdcc71a) | Feb 05, 2022 |
| Supermicro    | H11DSi                      | Server      | [4e41dc7f8b](https://bsd-hardware.info/?probe=4e41dc7f8b) | Feb 03, 2022 |
| ASRock        | J4105M                      | Desktop     | [09b9d104b9](https://bsd-hardware.info/?probe=09b9d104b9) | Feb 03, 2022 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [342915fccd](https://bsd-hardware.info/?probe=342915fccd) | Feb 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [07d565ad8c](https://bsd-hardware.info/?probe=07d565ad8c) | Feb 02, 2022 |
| Dell          | 00NH4P A03                  | Server      | [1fe915b90a](https://bsd-hardware.info/?probe=1fe915b90a) | Feb 01, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [83975bd2b1](https://bsd-hardware.info/?probe=83975bd2b1) | Jan 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ff629a490d](https://bsd-hardware.info/?probe=ff629a490d) | Jan 29, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [4b17ef7a18](https://bsd-hardware.info/?probe=4b17ef7a18) | Jan 27, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [4df3db0379](https://bsd-hardware.info/?probe=4df3db0379) | Jan 26, 2022 |
| Sophos        | SG                          | Firewall    | [3c6601bf94](https://bsd-hardware.info/?probe=3c6601bf94) | Jan 15, 2022 |
| PC Engines    | APU2                        | Desktop     | [5ea082ddf9](https://bsd-hardware.info/?probe=5ea082ddf9) | Jan 13, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [87000234dc](https://bsd-hardware.info/?probe=87000234dc) | Jan 11, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | Notebook    | [4ae2360503](https://bsd-hardware.info/?probe=4ae2360503) | Jan 11, 2022 |
| ASUSTek       | P8Z68-M PRO                 | Desktop     | [a0885f4f44](https://bsd-hardware.info/?probe=a0885f4f44) | Jan 10, 2022 |
| Dell          | 0DT021 A02                  | Server      | [d1fdef3d4d](https://bsd-hardware.info/?probe=d1fdef3d4d) | Jan 09, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7863226bbe](https://bsd-hardware.info/?probe=7863226bbe) | Jan 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [ded64258b4](https://bsd-hardware.info/?probe=ded64258b4) | Jan 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [8d607c1d19](https://bsd-hardware.info/?probe=8d607c1d19) | Jan 03, 2022 |
| Toshiba       | TECRA Z40-B                 | Notebook    | [d498fcd3f8](https://bsd-hardware.info/?probe=d498fcd3f8) | Jan 02, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [a07366611d](https://bsd-hardware.info/?probe=a07366611d) | Jan 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [c183bdd5af](https://bsd-hardware.info/?probe=c183bdd5af) | Jan 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [4848e4009f](https://bsd-hardware.info/?probe=4848e4009f) | Jan 01, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [7d47d0db05](https://bsd-hardware.info/?probe=7d47d0db05) | Dec 30, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [c3884fac44](https://bsd-hardware.info/?probe=c3884fac44) | Dec 30, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [259b5cc7b2](https://bsd-hardware.info/?probe=259b5cc7b2) | Dec 28, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [bde74629f9](https://bsd-hardware.info/?probe=bde74629f9) | Dec 25, 2021 |
| ASRock        | J3355B-ITX                  | Desktop     | [f4648747b0](https://bsd-hardware.info/?probe=f4648747b0) | Dec 22, 2021 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [839eed529d](https://bsd-hardware.info/?probe=839eed529d) | Dec 21, 2021 |
| Lenovo        | ThinkPad X280 20KF001UUS    | Notebook    | [5b9001009e](https://bsd-hardware.info/?probe=5b9001009e) | Dec 20, 2021 |
| HP            | 8103 A01                    | Mini pc     | [0138a82561](https://bsd-hardware.info/?probe=0138a82561) | Dec 18, 2021 |
| Quanta        | 2AC7 011                    | Desktop     | [1a831a1d34](https://bsd-hardware.info/?probe=1a831a1d34) | Dec 18, 2021 |
| HP            | 843B                        | Desktop     | [f0d279747f](https://bsd-hardware.info/?probe=f0d279747f) | Dec 13, 2021 |
| HP            | 843B                        | Desktop     | [56400d3999](https://bsd-hardware.info/?probe=56400d3999) | Dec 13, 2021 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [a86326d049](https://bsd-hardware.info/?probe=a86326d049) | Dec 11, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [624041b5db](https://bsd-hardware.info/?probe=624041b5db) | Dec 09, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [79d9964300](https://bsd-hardware.info/?probe=79d9964300) | Dec 02, 2021 |
| Dell          | 051FJ8 A01                  | Desktop     | [ccfb8336a0](https://bsd-hardware.info/?probe=ccfb8336a0) | Dec 01, 2021 |
| HP            | 843B                        | Desktop     | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| Apple         | Mac-F2218FA9                | All in one  | [7154bea350](https://bsd-hardware.info/?probe=7154bea350) | Nov 27, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [dc9d060c7f](https://bsd-hardware.info/?probe=dc9d060c7f) | Nov 27, 2021 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [339779baad](https://bsd-hardware.info/?probe=339779baad) | Nov 26, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [49a0a07721](https://bsd-hardware.info/?probe=49a0a07721) | Nov 25, 2021 |
| Supermicro    | X12SCZ-TLN4FA               | Server      | [3debb4fe22](https://bsd-hardware.info/?probe=3debb4fe22) | Nov 24, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [f922794063](https://bsd-hardware.info/?probe=f922794063) | Nov 22, 2021 |
| Apple         | Mac-F2218FA9                | All in one  | [1802f6c891](https://bsd-hardware.info/?probe=1802f6c891) | Nov 21, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [a26bc8f2b3](https://bsd-hardware.info/?probe=a26bc8f2b3) | Nov 14, 2021 |
| Gigabyte      | MRZNVMS-00                  | Desktop     | [817cb3e603](https://bsd-hardware.info/?probe=817cb3e603) | Nov 12, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b0a51ac0af](https://bsd-hardware.info/?probe=b0a51ac0af) | Nov 11, 2021 |
| Dell          | Studio 1747                 | Notebook    | [7ab6b58d69](https://bsd-hardware.info/?probe=7ab6b58d69) | Nov 11, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [970387f9d9](https://bsd-hardware.info/?probe=970387f9d9) | Nov 09, 2021 |
| Protectli     | FW6E                        | Desktop     | [ebe5b24dee](https://bsd-hardware.info/?probe=ebe5b24dee) | Nov 08, 2021 |
| Protectli     | FW6E                        | Desktop     | [6c12084410](https://bsd-hardware.info/?probe=6c12084410) | Nov 07, 2021 |
| Unknown       | Unknown                     | Firewall    | [053ec385f8](https://bsd-hardware.info/?probe=053ec385f8) | Nov 04, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [99b5ab3e42](https://bsd-hardware.info/?probe=99b5ab3e42) | Nov 04, 2021 |
| ASRock        | H370M-ITX/ac                | Desktop     | [bf37ad85e7](https://bsd-hardware.info/?probe=bf37ad85e7) | Nov 03, 2021 |
| Unknown       | Unknown                     | Desktop     | [579cf2ac1a](https://bsd-hardware.info/?probe=579cf2ac1a) | Oct 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7abc8386ec](https://bsd-hardware.info/?probe=7abc8386ec) | Oct 31, 2021 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [721ef0235c](https://bsd-hardware.info/?probe=721ef0235c) | Oct 30, 2021 |
| HP            | 843B                        | Desktop     | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [c3d6cddf87](https://bsd-hardware.info/?probe=c3d6cddf87) | Oct 25, 2021 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [9e254ab443](https://bsd-hardware.info/?probe=9e254ab443) | Oct 23, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [1d5e3e5bc3](https://bsd-hardware.info/?probe=1d5e3e5bc3) | Oct 22, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [3337c00433](https://bsd-hardware.info/?probe=3337c00433) | Oct 22, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [5c8f3708b1](https://bsd-hardware.info/?probe=5c8f3708b1) | Oct 21, 2021 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [93f9e34d05](https://bsd-hardware.info/?probe=93f9e34d05) | Oct 19, 2021 |
| Dell          | Studio 1747                 | Notebook    | [ca939fbe2f](https://bsd-hardware.info/?probe=ca939fbe2f) | Oct 19, 2021 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [b20953f2f4](https://bsd-hardware.info/?probe=b20953f2f4) | Oct 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [bbdfde368b](https://bsd-hardware.info/?probe=bbdfde368b) | Oct 18, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [1a5bae2227](https://bsd-hardware.info/?probe=1a5bae2227) | Oct 15, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [77101a00b3](https://bsd-hardware.info/?probe=77101a00b3) | Oct 11, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [cc419789f8](https://bsd-hardware.info/?probe=cc419789f8) | Oct 08, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | Desktop     | [00bafc5f7c](https://bsd-hardware.info/?probe=00bafc5f7c) | Oct 03, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [36a5bc62bf](https://bsd-hardware.info/?probe=36a5bc62bf) | Sep 27, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [01e33c8399](https://bsd-hardware.info/?probe=01e33c8399) | Sep 26, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [ca41aa2f67](https://bsd-hardware.info/?probe=ca41aa2f67) | Sep 23, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [8dc995488e](https://bsd-hardware.info/?probe=8dc995488e) | Sep 13, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [3b709e37c2](https://bsd-hardware.info/?probe=3b709e37c2) | Sep 12, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [1feb22dc52](https://bsd-hardware.info/?probe=1feb22dc52) | Sep 12, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [0e81fce9eb](https://bsd-hardware.info/?probe=0e81fce9eb) | Sep 10, 2021 |
| HP            | 212B                        | Desktop     | [d3894b9f37](https://bsd-hardware.info/?probe=d3894b9f37) | Sep 10, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [df08c4e6d3](https://bsd-hardware.info/?probe=df08c4e6d3) | Sep 09, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [c64c51359c](https://bsd-hardware.info/?probe=c64c51359c) | Sep 09, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [e960bc2548](https://bsd-hardware.info/?probe=e960bc2548) | Sep 01, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [3dca10264a](https://bsd-hardware.info/?probe=3dca10264a) | Aug 29, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [70dc185964](https://bsd-hardware.info/?probe=70dc185964) | Aug 25, 2021 |
| HP            | 1589                        | Desktop     | [4d51cc9c4b](https://bsd-hardware.info/?probe=4d51cc9c4b) | Aug 24, 2021 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [da3e8986a3](https://bsd-hardware.info/?probe=da3e8986a3) | Aug 22, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [75f3efc215](https://bsd-hardware.info/?probe=75f3efc215) | Aug 18, 2021 |
| Supermicro    | X11SSW-F                    | Server      | [766c25105d](https://bsd-hardware.info/?probe=766c25105d) | Aug 17, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [bd94ad09ef](https://bsd-hardware.info/?probe=bd94ad09ef) | Aug 12, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | Desktop     | [94201b7633](https://bsd-hardware.info/?probe=94201b7633) | Aug 10, 2021 |
| HP            | Notebook                    | Notebook    | [a3c3297cd2](https://bsd-hardware.info/?probe=a3c3297cd2) | Aug 08, 2021 |
| HP            | Notebook                    | Notebook    | [0c316107a4](https://bsd-hardware.info/?probe=0c316107a4) | Aug 08, 2021 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [6da61be169](https://bsd-hardware.info/?probe=6da61be169) | Aug 08, 2021 |
| ZOTAC         | Board                       | Mini pc     | [e441e5484c](https://bsd-hardware.info/?probe=e441e5484c) | Aug 08, 2021 |
| IBM           | 00Y8494                     | Server      | [92ed5993f4](https://bsd-hardware.info/?probe=92ed5993f4) | Aug 07, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [535b577563](https://bsd-hardware.info/?probe=535b577563) | Aug 03, 2021 |
| HP            | ProLiant ML150 G6           | Desktop     | [783c2ba254](https://bsd-hardware.info/?probe=783c2ba254) | Aug 02, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [b434d9bfb8](https://bsd-hardware.info/?probe=b434d9bfb8) | Aug 02, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [4d118404a8](https://bsd-hardware.info/?probe=4d118404a8) | Jul 29, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [1c3ec31075](https://bsd-hardware.info/?probe=1c3ec31075) | Jul 28, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [fc13802cd3](https://bsd-hardware.info/?probe=fc13802cd3) | Jul 19, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [5697d53687](https://bsd-hardware.info/?probe=5697d53687) | Jul 19, 2021 |
| IBM           | 00Y8494                     | Server      | [76a17b83e5](https://bsd-hardware.info/?probe=76a17b83e5) | Jul 19, 2021 |
| Lenovo        | SHARKBAY 0C48431 PRO        | Desktop     | [0a1fa8924e](https://bsd-hardware.info/?probe=0a1fa8924e) | Jul 17, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [b86c2cfc99](https://bsd-hardware.info/?probe=b86c2cfc99) | Jul 16, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [4bd9c0bbb8](https://bsd-hardware.info/?probe=4bd9c0bbb8) | Jul 11, 2021 |
| PC Engines    | apu4                        | Desktop     | [51163b13ef](https://bsd-hardware.info/?probe=51163b13ef) | Jul 11, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [59a1b5f761](https://bsd-hardware.info/?probe=59a1b5f761) | Jul 10, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [f07b30b043](https://bsd-hardware.info/?probe=f07b30b043) | Jul 03, 2021 |
| Gigabyte      | MMLP3AP-00                  | Notebook    | [168e674b55](https://bsd-hardware.info/?probe=168e674b55) | Jul 03, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [d4f6eea56a](https://bsd-hardware.info/?probe=d4f6eea56a) | Jun 27, 2021 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [a326fd4061](https://bsd-hardware.info/?probe=a326fd4061) | Jun 20, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [ef7104e237](https://bsd-hardware.info/?probe=ef7104e237) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX H370-I GAMING     | Desktop     | [d2dd261a2a](https://bsd-hardware.info/?probe=d2dd261a2a) | Jun 20, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [6aa5f8046e](https://bsd-hardware.info/?probe=6aa5f8046e) | Jun 19, 2021 |
| Dell          | Inspiron 15-7579            | Notebook    | [4b8b5f7918](https://bsd-hardware.info/?probe=4b8b5f7918) | Jun 19, 2021 |
| Shuttle       | FS110                       | Desktop     | [9b4093c9a1](https://bsd-hardware.info/?probe=9b4093c9a1) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | Notebook    | [7db1345e97](https://bsd-hardware.info/?probe=7db1345e97) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | Notebook    | [cbade775b6](https://bsd-hardware.info/?probe=cbade775b6) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | Notebook    | [80052d6cdc](https://bsd-hardware.info/?probe=80052d6cdc) | Jun 15, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [34df628c87](https://bsd-hardware.info/?probe=34df628c87) | Jun 14, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [83cf0bb0fb](https://bsd-hardware.info/?probe=83cf0bb0fb) | Jun 12, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [d239ee4916](https://bsd-hardware.info/?probe=d239ee4916) | Jun 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [459bf008e9](https://bsd-hardware.info/?probe=459bf008e9) | Jun 12, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [d09c80b4d4](https://bsd-hardware.info/?probe=d09c80b4d4) | Jun 11, 2021 |
| HP            | 805D                        | Desktop     | [dc4e61ecd4](https://bsd-hardware.info/?probe=dc4e61ecd4) | Jun 07, 2021 |
| HP            | 8523 A01                    | Mini pc     | [d563d65a91](https://bsd-hardware.info/?probe=d563d65a91) | Jun 05, 2021 |
| HP            | 1998                        | Desktop     | [2806e1e8cf](https://bsd-hardware.info/?probe=2806e1e8cf) | Jun 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [95a281e2f8](https://bsd-hardware.info/?probe=95a281e2f8) | Jun 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [65dd81d59e](https://bsd-hardware.info/?probe=65dd81d59e) | Jun 02, 2021 |
| HP            | 8103 A01                    | Mini pc     | [93a434d951](https://bsd-hardware.info/?probe=93a434d951) | Jun 01, 2021 |
| Apple         | PowerBook5,2                | Notebook    | [8cc0aab53c](https://bsd-hardware.info/?probe=8cc0aab53c) | May 31, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [1cd4e4b333](https://bsd-hardware.info/?probe=1cd4e4b333) | May 28, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [5d64699270](https://bsd-hardware.info/?probe=5d64699270) | May 28, 2021 |
| HP            | 8103 A01                    | Mini pc     | [df43b9c68e](https://bsd-hardware.info/?probe=df43b9c68e) | May 26, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [fbfd0e7969](https://bsd-hardware.info/?probe=fbfd0e7969) | May 21, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [7e013ea910](https://bsd-hardware.info/?probe=7e013ea910) | May 20, 2021 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [ef5e9ec095](https://bsd-hardware.info/?probe=ef5e9ec095) | May 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [65f5931910](https://bsd-hardware.info/?probe=65f5931910) | May 18, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [1e9f399d73](https://bsd-hardware.info/?probe=1e9f399d73) | May 17, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [e6a555b397](https://bsd-hardware.info/?probe=e6a555b397) | May 17, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [109f3afa21](https://bsd-hardware.info/?probe=109f3afa21) | May 17, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [f92f43bc54](https://bsd-hardware.info/?probe=f92f43bc54) | May 17, 2021 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [33bc82e701](https://bsd-hardware.info/?probe=33bc82e701) | May 17, 2021 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [bf76401b74](https://bsd-hardware.info/?probe=bf76401b74) | May 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [f90e5f9566](https://bsd-hardware.info/?probe=f90e5f9566) | May 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [e67de92cb9](https://bsd-hardware.info/?probe=e67de92cb9) | May 14, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [273e379d9f](https://bsd-hardware.info/?probe=273e379d9f) | May 14, 2021 |
| Shuttle       | FS110                       | Desktop     | [e39173782f](https://bsd-hardware.info/?probe=e39173782f) | May 08, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [1f78fbb36c](https://bsd-hardware.info/?probe=1f78fbb36c) | May 08, 2021 |
| Dell          | Latitude 3440               | Notebook    | [3c8d21772a](https://bsd-hardware.info/?probe=3c8d21772a) | May 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5a128dd6a3](https://bsd-hardware.info/?probe=5a128dd6a3) | Apr 22, 2021 |
| HP            | 8523 A01                    | Mini pc     | [dde68fc65d](https://bsd-hardware.info/?probe=dde68fc65d) | Apr 22, 2021 |
| HP            | 18E7                        | Desktop     | [e6354de524](https://bsd-hardware.info/?probe=e6354de524) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7a6f106b0e](https://bsd-hardware.info/?probe=7a6f106b0e) | Apr 18, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [cd0467031a](https://bsd-hardware.info/?probe=cd0467031a) | Apr 17, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [5a1a372153](https://bsd-hardware.info/?probe=5a1a372153) | Apr 16, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [31a9bf167b](https://bsd-hardware.info/?probe=31a9bf167b) | Apr 16, 2021 |
| Dell          | 051FJ8 A01                  | Desktop     | [351b13fd3b](https://bsd-hardware.info/?probe=351b13fd3b) | Apr 15, 2021 |
| ASRock        | J4105M                      | Desktop     | [69165e1573](https://bsd-hardware.info/?probe=69165e1573) | Apr 13, 2021 |
| HP            | 8523 A01                    | Mini pc     | [f4e8e7e7e8](https://bsd-hardware.info/?probe=f4e8e7e7e8) | Apr 11, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [5aca6c03c1](https://bsd-hardware.info/?probe=5aca6c03c1) | Apr 09, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [5950dfc99a](https://bsd-hardware.info/?probe=5950dfc99a) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [0e814e53e9](https://bsd-hardware.info/?probe=0e814e53e9) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [817ec0a0da](https://bsd-hardware.info/?probe=817ec0a0da) | Apr 09, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [6f4f9fb14e](https://bsd-hardware.info/?probe=6f4f9fb14e) | Apr 07, 2021 |
| Dell          | 072XWF A01                  | Server      | [77f48d8337](https://bsd-hardware.info/?probe=77f48d8337) | Apr 07, 2021 |
| Dell          | Latitude 3440               | Notebook    | [7e85a38390](https://bsd-hardware.info/?probe=7e85a38390) | Apr 04, 2021 |
| HP            | 2AF7                        | Desktop     | [acd341147c](https://bsd-hardware.info/?probe=acd341147c) | Apr 03, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [39d86447b4](https://bsd-hardware.info/?probe=39d86447b4) | Mar 31, 2021 |
| Dell          | 0TTDMJ A00                  | Desktop     | [b5c0428c8a](https://bsd-hardware.info/?probe=b5c0428c8a) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [6af0a9bc78](https://bsd-hardware.info/?probe=6af0a9bc78) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [aaf140005c](https://bsd-hardware.info/?probe=aaf140005c) | Mar 30, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [636dfb334b](https://bsd-hardware.info/?probe=636dfb334b) | Mar 29, 2021 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [bb65d06888](https://bsd-hardware.info/?probe=bb65d06888) | Mar 28, 2021 |
| Gigabyte      | D525TUD                     | Desktop     | [a48a515986](https://bsd-hardware.info/?probe=a48a515986) | Mar 24, 2021 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [a951f7ffe4](https://bsd-hardware.info/?probe=a951f7ffe4) | Mar 24, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [9b84d1e7e6](https://bsd-hardware.info/?probe=9b84d1e7e6) | Mar 24, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [cf4b3e0c6f](https://bsd-hardware.info/?probe=cf4b3e0c6f) | Mar 23, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [4a59793120](https://bsd-hardware.info/?probe=4a59793120) | Mar 23, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [7280d52eff](https://bsd-hardware.info/?probe=7280d52eff) | Mar 23, 2021 |
| Lenovo        | 30D9 No DPK                 | Desktop     | [061ad76c0e](https://bsd-hardware.info/?probe=061ad76c0e) | Mar 20, 2021 |
| Dell          | Inspiron 7370               | Notebook    | [7e2328dda3](https://bsd-hardware.info/?probe=7e2328dda3) | Mar 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [03935b2745](https://bsd-hardware.info/?probe=03935b2745) | Mar 20, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [27cb6a75c8](https://bsd-hardware.info/?probe=27cb6a75c8) | Mar 19, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [8964a02114](https://bsd-hardware.info/?probe=8964a02114) | Mar 15, 2021 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [b13ee482e8](https://bsd-hardware.info/?probe=b13ee482e8) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [f46146b79e](https://bsd-hardware.info/?probe=f46146b79e) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [c1ed4c02b8](https://bsd-hardware.info/?probe=c1ed4c02b8) | Mar 11, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [e9ca160a2d](https://bsd-hardware.info/?probe=e9ca160a2d) | Mar 11, 2021 |
| Shuttle       | FS110                       | Desktop     | [fc31311d01](https://bsd-hardware.info/?probe=fc31311d01) | Mar 10, 2021 |
| Unknown       | Unknown                     | Firewall    | [7b7714416c](https://bsd-hardware.info/?probe=7b7714416c) | Mar 09, 2021 |
| Alienware     | 14                          | Notebook    | [0e0cdf952a](https://bsd-hardware.info/?probe=0e0cdf952a) | Mar 06, 2021 |
| Supermicro    | A2SDi-TP8F                  | Desktop     | [c30d805062](https://bsd-hardware.info/?probe=c30d805062) | Mar 05, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [c7b0539b99](https://bsd-hardware.info/?probe=c7b0539b99) | Mar 02, 2021 |
| IBM           | 94Y7614                     | Server      | [7515ccaa7a](https://bsd-hardware.info/?probe=7515ccaa7a) | Mar 01, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [48dfa4a5f6](https://bsd-hardware.info/?probe=48dfa4a5f6) | Mar 01, 2021 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [fc4265eb19](https://bsd-hardware.info/?probe=fc4265eb19) | Feb 24, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [9d35f9e853](https://bsd-hardware.info/?probe=9d35f9e853) | Feb 24, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [dbf040e5a8](https://bsd-hardware.info/?probe=dbf040e5a8) | Feb 22, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [11d6c98009](https://bsd-hardware.info/?probe=11d6c98009) | Feb 21, 2021 |
| Toshiba       | Satellite U500              | Notebook    | [feae098542](https://bsd-hardware.info/?probe=feae098542) | Feb 20, 2021 |
| Protectli     | FW6                         | Desktop     | [b656792690](https://bsd-hardware.info/?probe=b656792690) | Feb 20, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [cfd1824b40](https://bsd-hardware.info/?probe=cfd1824b40) | Feb 18, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [4c7959ac6e](https://bsd-hardware.info/?probe=4c7959ac6e) | Feb 17, 2021 |
| Gigabyte      | MRZNVMS-00                  | Desktop     | [b51cb672a4](https://bsd-hardware.info/?probe=b51cb672a4) | Feb 12, 2021 |
| Lenovo        | ThinkPad T410 253722U       | Notebook    | [219e9cb1d7](https://bsd-hardware.info/?probe=219e9cb1d7) | Feb 10, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3402eabdbf](https://bsd-hardware.info/?probe=3402eabdbf) | Feb 09, 2021 |
| Intel         | H81U                        | Notebook    | [efb1f9d207](https://bsd-hardware.info/?probe=efb1f9d207) | Feb 07, 2021 |
| Lenovo        | 314D SDK0J40700 WIN 3258... | Mini pc     | [5a5119a395](https://bsd-hardware.info/?probe=5a5119a395) | Feb 06, 2021 |
| ASRock        | Z270M-ITX/ac                | Desktop     | [9b50d422e3](https://bsd-hardware.info/?probe=9b50d422e3) | Feb 04, 2021 |
| Supermicro    | X8DT6                       | Server      | [6acb4d8445](https://bsd-hardware.info/?probe=6acb4d8445) | Feb 04, 2021 |
| HP            | 0AECh D                     | Desktop     | [6dde87584c](https://bsd-hardware.info/?probe=6dde87584c) | Feb 04, 2021 |
| HP            | 829A                        | Mini pc     | [ede207c6df](https://bsd-hardware.info/?probe=ede207c6df) | Feb 04, 2021 |
| PC Engines    | apu4                        | Desktop     | [18dfb34a97](https://bsd-hardware.info/?probe=18dfb34a97) | Feb 04, 2021 |
| HP            | 3397                        | Desktop     | [cda4af23ee](https://bsd-hardware.info/?probe=cda4af23ee) | Feb 03, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [0a48224f4b](https://bsd-hardware.info/?probe=0a48224f4b) | Feb 03, 2021 |
| HP            | 3397                        | Desktop     | [65f1db2a70](https://bsd-hardware.info/?probe=65f1db2a70) | Feb 03, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [efe09d459a](https://bsd-hardware.info/?probe=efe09d459a) | Jan 31, 2021 |
| Dell          | 086HF8 A08                  | Server      | [1d5c769e0f](https://bsd-hardware.info/?probe=1d5c769e0f) | Jan 31, 2021 |
| HP            | 82B4                        | Desktop     | [faf58d8f87](https://bsd-hardware.info/?probe=faf58d8f87) | Jan 30, 2021 |
| Lenovo        | 30D9 No DPK                 | Desktop     | [12056c71ad](https://bsd-hardware.info/?probe=12056c71ad) | Jan 30, 2021 |
| PC Engines    | APU2                        | Desktop     | [7e96c61bf9](https://bsd-hardware.info/?probe=7e96c61bf9) | Jan 30, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [0147020401](https://bsd-hardware.info/?probe=0147020401) | Jan 30, 2021 |
| ASRock        | J3455-ITX                   | Desktop     | [65bde09c13](https://bsd-hardware.info/?probe=65bde09c13) | Jan 26, 2021 |
| ASRock        | J3455-ITX                   | Desktop     | [0a4d4fc896](https://bsd-hardware.info/?probe=0a4d4fc896) | Jan 25, 2021 |
| Dell          | 086HF8 A08                  | Server      | [f2eb601b2a](https://bsd-hardware.info/?probe=f2eb601b2a) | Jan 25, 2021 |
| ASRock        | J3355B-ITX                  | Desktop     | [e8496a6202](https://bsd-hardware.info/?probe=e8496a6202) | Jan 24, 2021 |
| PC Engines    | APU2                        | Desktop     | [da6e3cd1a6](https://bsd-hardware.info/?probe=da6e3cd1a6) | Jan 23, 2021 |
| Supermicro    | X8DT6                       | Server      | [b24cc06305](https://bsd-hardware.info/?probe=b24cc06305) | Jan 22, 2021 |
| PC Engines    | APU2                        | Desktop     | [3d536a42eb](https://bsd-hardware.info/?probe=3d536a42eb) | Jan 21, 2021 |
| PC Engines    | APU2                        | Desktop     | [043446a653](https://bsd-hardware.info/?probe=043446a653) | Jan 21, 2021 |
| Shuttle       | FS110                       | Desktop     | [fed17a1f77](https://bsd-hardware.info/?probe=fed17a1f77) | Jan 21, 2021 |
| Supermicro    | X8DTH                       | Server      | [9ea2aeeb86](https://bsd-hardware.info/?probe=9ea2aeeb86) | Jan 20, 2021 |
| Supermicro    | X8STi                       | Desktop     | [7cda964f76](https://bsd-hardware.info/?probe=7cda964f76) | Jan 20, 2021 |
| Dell          | 0M9KCM A02                  | Desktop     | [1cc5f6a07b](https://bsd-hardware.info/?probe=1cc5f6a07b) | Jan 20, 2021 |
| Dell          | 086HF8 A08                  | Server      | [b087a1d9d2](https://bsd-hardware.info/?probe=b087a1d9d2) | Jan 20, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [8c55004504](https://bsd-hardware.info/?probe=8c55004504) | Jan 19, 2021 |
| Intel         | S1200RP_SE G62252-406       | Server      | [49ad4461dc](https://bsd-hardware.info/?probe=49ad4461dc) | Jan 16, 2021 |
| Supermicro    | C7Z170-OCEB                 | Server      | [9f6632de8b](https://bsd-hardware.info/?probe=9f6632de8b) | Jan 10, 2021 |
| Supermicro    | X7SLA                       | Desktop     | [2d31f38bf0](https://bsd-hardware.info/?probe=2d31f38bf0) | Jan 10, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [834cb6c68a](https://bsd-hardware.info/?probe=834cb6c68a) | Jan 10, 2021 |
| Alienware     | 14                          | Notebook    | [dd2cc000a7](https://bsd-hardware.info/?probe=dd2cc000a7) | Jan 07, 2021 |
| Alienware     | 14                          | Notebook    | [48f61623f2](https://bsd-hardware.info/?probe=48f61623f2) | Jan 07, 2021 |
| MSI           | X58 Pro-E                   | Desktop     | [bd108f94d5](https://bsd-hardware.info/?probe=bd108f94d5) | Jan 02, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [11011ecee1](https://bsd-hardware.info/?probe=11011ecee1) | Jan 02, 2021 |
| HP            | 212B                        | Desktop     | [7fe9d2c508](https://bsd-hardware.info/?probe=7fe9d2c508) | Dec 18, 2020 |
| Dell          | 0GM819                      | Desktop     | [adc8eb1931](https://bsd-hardware.info/?probe=adc8eb1931) | Dec 18, 2020 |
| HP            | 805D                        | Desktop     | [dc62857275](https://bsd-hardware.info/?probe=dc62857275) | Dec 17, 2020 |
| Supermicro    | X8STi                       | Desktop     | [80c2762cfb](https://bsd-hardware.info/?probe=80c2762cfb) | Dec 16, 2020 |
| ASRockRack    | D1541D4U-2O8R               | Desktop     | [d59d8a3b6d](https://bsd-hardware.info/?probe=d59d8a3b6d) | Dec 16, 2020 |
| Supermicro    | X11SSH-F                    | Desktop     | [ebb920c0c4](https://bsd-hardware.info/?probe=ebb920c0c4) | Dec 16, 2020 |
| MSI           | X99S SLI PLUS               | Desktop     | [9b2421d9d5](https://bsd-hardware.info/?probe=9b2421d9d5) | Nov 28, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5d5ecb38cd](https://bsd-hardware.info/?probe=5d5ecb38cd) | Nov 25, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [002b408f7e](https://bsd-hardware.info/?probe=002b408f7e) | Nov 18, 2020 |
| Lenovo        | ThinkPad T440 20B7S0A800    | Notebook    | [d3474f1ca3](https://bsd-hardware.info/?probe=d3474f1ca3) | Nov 18, 2020 |
| Dell          | 0YFVT1 A06                  | Server      | [fd37374e7b](https://bsd-hardware.info/?probe=fd37374e7b) | Nov 11, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | Notebook    | [6a0f910601](https://bsd-hardware.info/?probe=6a0f910601) | Nov 10, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | Notebook    | [6dca4cdd18](https://bsd-hardware.info/?probe=6dca4cdd18) | Nov 10, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [714b6539cf](https://bsd-hardware.info/?probe=714b6539cf) | Nov 07, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [9f871ab960](https://bsd-hardware.info/?probe=9f871ab960) | Nov 01, 2020 |
| Intel         | X79 V2.81A                  | Desktop     | [d5b4cdf28a](https://bsd-hardware.info/?probe=d5b4cdf28a) | Oct 30, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [59c940d739](https://bsd-hardware.info/?probe=59c940d739) | Oct 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [8552669e76](https://bsd-hardware.info/?probe=8552669e76) | Oct 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [50966c2f83](https://bsd-hardware.info/?probe=50966c2f83) | Oct 30, 2020 |
| Dell          | 0YFVT1 A06                  | Server      | [fca49dda17](https://bsd-hardware.info/?probe=fca49dda17) | Oct 29, 2020 |
| ADI Engine... | RCC-VE                      | Desktop     | [30440abc03](https://bsd-hardware.info/?probe=30440abc03) | Oct 29, 2020 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [c41d989a06](https://bsd-hardware.info/?probe=c41d989a06) | Oct 28, 2020 |
| IBM           | Board                       | Desktop     | [11b0b7012f](https://bsd-hardware.info/?probe=11b0b7012f) | Oct 21, 2020 |
| IBM           | Board                       | Desktop     | [a92c08a920](https://bsd-hardware.info/?probe=a92c08a920) | Oct 21, 2020 |
| IBM           | Board                       | Desktop     | [80d5f15a63](https://bsd-hardware.info/?probe=80d5f15a63) | Oct 21, 2020 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [f287de215c](https://bsd-hardware.info/?probe=f287de215c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [f846609c80](https://bsd-hardware.info/?probe=f846609c80) | Oct 20, 2020 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [feb1da0406](https://bsd-hardware.info/?probe=feb1da0406) | Oct 20, 2020 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [efece2abf7](https://bsd-hardware.info/?probe=efece2abf7) | Oct 20, 2020 |
| ASUSTek       | 1000HE                      | Notebook    | [621df26e0c](https://bsd-hardware.info/?probe=621df26e0c) | Oct 19, 2020 |
| Lenovo        | ThinkPad T460 20FMS1BC01    | Notebook    | [bf6d6d155b](https://bsd-hardware.info/?probe=bf6d6d155b) | Oct 19, 2020 |
| Lenovo        | ThinkPad E495 20NE0001US    | Notebook    | [a1fc75a9b7](https://bsd-hardware.info/?probe=a1fc75a9b7) | Oct 09, 2020 |
| MSI           | MS-7250                     | Desktop     | [41e2d9dab3](https://bsd-hardware.info/?probe=41e2d9dab3) | Sep 04, 2020 |
| HP            | Pavilion dv6500             | Notebook    | [316ffb0740](https://bsd-hardware.info/?probe=316ffb0740) | Sep 04, 2020 |
| HP            | 3031h                       | Desktop     | [1f2695b3a7](https://bsd-hardware.info/?probe=1f2695b3a7) | Aug 25, 2020 |
| Acer          | AOD270                      | Notebook    | [41d2974f13](https://bsd-hardware.info/?probe=41d2974f13) | Aug 20, 2020 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [515042ff2d](https://bsd-hardware.info/?probe=515042ff2d) | Aug 20, 2020 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [7f6095b266](https://bsd-hardware.info/?probe=7f6095b266) | Aug 20, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [e568f0f32e](https://bsd-hardware.info/?probe=e568f0f32e) | Aug 04, 2020 |
| ASUSTek       | Z170-P                      | Desktop     | [49e01a949b](https://bsd-hardware.info/?probe=49e01a949b) | Jul 29, 2020 |
| ASUSTek       | K52JK                       | Notebook    | [d5d32f1334](https://bsd-hardware.info/?probe=d5d32f1334) | Jun 29, 2020 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [0f7697b73a](https://bsd-hardware.info/?probe=0f7697b73a) | May 28, 2020 |
| Dell          | 0T10XW A02                  | Desktop     | [81f39f3061](https://bsd-hardware.info/?probe=81f39f3061) | May 28, 2020 |
| Lenovo        | ThinkPad T420 4180B39       | Notebook    | [05ed5eb1e4](https://bsd-hardware.info/?probe=05ed5eb1e4) | May 25, 2020 |
| Lenovo        | ThinkPad X270 20HNCTO1WW    | Notebook    | [7def094afb](https://bsd-hardware.info/?probe=7def094afb) | May 23, 2020 |
| ASUSTek       | K52JK                       | Notebook    | [6a6b06fc67](https://bsd-hardware.info/?probe=6a6b06fc67) | May 23, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| OpenBSD 7.2         | 15        | 3.56%   |
| helloSystem 0.7.0   | 13        | 3.09%   |
| OPNsense 21.1.4     | 12        | 2.85%   |
| OPNsense 21.1       | 12        | 2.85%   |
| OpenBSD 7.1         | 12        | 2.85%   |
| helloSystem 0.5.0   | 11        | 2.61%   |
| OPNsense 22.7.4     | 10        | 2.38%   |
| OPNsense 22.1.7     | 10        | 2.38%   |
| OPNsense 22.1.6     | 10        | 2.38%   |
| OPNsense 22.1.10    | 10        | 2.38%   |
| OPNsense 21.1.3     | 10        | 2.38%   |
| OPNsense 22.7.8     | 9         | 2.14%   |
| OPNsense 22.7       | 9         | 2.14%   |
| OPNsense 22.1       | 9         | 2.14%   |
| OPNsense 21.1.6     | 9         | 2.14%   |
| OpenBSD 7.0         | 9         | 2.14%   |
| OpenBSD 6.9         | 9         | 2.14%   |
| FreeBSD 12.2        | 9         | 2.14%   |
| OPNsense 22.1.8     | 8         | 1.9%    |
| OPNsense 21.7.7     | 8         | 1.9%    |
| OPNsense 21.7.1     | 8         | 1.9%    |
| OPNsense 21.1.5     | 8         | 1.9%    |
| OpenBSD 6.8         | 8         | 1.9%    |
| OPNsense 21.7       | 7         | 1.66%   |
| FreeBSD 13.0        | 7         | 1.66%   |
| OPNsense 21.7.8     | 6         | 1.43%   |
| OPNsense 21.7.3     | 6         | 1.43%   |
| OPNsense 21.1.1     | 6         | 1.43%   |
| OPNsense 20.7.8     | 6         | 1.43%   |
| FreeBSD 13.1        | 6         | 1.43%   |
| OPNsense 22.7.7     | 5         | 1.19%   |
| OPNsense 22.7.2     | 5         | 1.19%   |
| OPNsense 21.7.5     | 5         | 1.19%   |
| OPNsense 21.7.4     | 5         | 1.19%   |
| OPNsense 21.1.2     | 5         | 1.19%   |
| helloSystem 0.4.0   | 5         | 1.19%   |
| FreeBSD 13.0-p5     | 5         | 1.19%   |
| FreeBSD 12.2-STABLE | 5         | 1.19%   |
| OPNsense 22.7.6     | 4         | 0.95%   |
| OPNsense 22.1.9     | 4         | 0.95%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 167       | 55.3%   |
| FreeBSD     | 68        | 22.52%  |
| helloSystem | 32        | 10.6%   |
| OpenBSD     | 22        | 7.28%   |
| GhostBSD    | 6         | 1.99%   |
| FreeNAS     | 3         | 0.99%   |
| TrueNAS     | 2         | 0.66%   |
| pfSense     | 1         | 0.33%   |
| NetBSD      | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 292       | 97.66%  |
| i386   | 5         | 1.67%   |
| macppc | 1         | 0.33%   |
| arm64  | 1         | 0.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 195       | 62.7%   |
| helloDesktop | 47        | 15.11%  |
| XFCE         | 18        | 5.79%   |
| fvwm         | 12        | 3.86%   |
| KDE5         | 10        | 3.22%   |
| MATE         | 8         | 2.57%   |
| TWM          | 4         | 1.29%   |
| GNOME        | 4         | 1.29%   |
| Cinnamon     | 3         | 0.96%   |
| Openbox      | 2         | 0.64%   |
| i3           | 2         | 0.64%   |
| X-Cinnamon   | 1         | 0.32%   |
| Window Maker | 1         | 0.32%   |
| LXQt         | 1         | 0.32%   |
| LXDE         | 1         | 0.32%   |
| Lumina       | 1         | 0.32%   |
| Fluxbox      | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 194       | 64.88%  |
| X11     | 103       | 34.45%  |
| Wayland | 2         | 0.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 230       | 75.91%  |
| SLiM    | 36        | 11.88%  |
| SDDM    | 14        | 4.62%   |
| XDM     | 10        | 3.3%    |
| LightDM | 10        | 3.3%    |
| GDM     | 3         | 0.99%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 213       | 70.76%  |
| en_US   | 48        | 15.95%  |
| C       | 25        | 8.31%   |
| en_CA   | 9         | 2.99%   |
| fr_FR   | 4         | 1.33%   |
| fr_CA   | 1         | 0.33%   |
| en_NL   | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 235       | 77.3%   |
| BIOS | 69        | 22.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 161       | 52.1%   |
| Zfs     | 116       | 37.54%  |
| Ffs     | 22        | 7.12%   |
| Cd9660  | 9         | 2.91%   |
| Unknown | 1         | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 265       | 88.63%  |
| MBR     | 31        | 10.37%  |
| Unknown | 3         | 1%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell                           | 39        | 13.04%  |
| Lenovo                         | 38        | 12.71%  |
| Hewlett-Packard                | 33        | 11.04%  |
| ASUSTek Computer               | 29        | 9.7%    |
| Intel                          | 21        | 7.02%   |
| Supermicro                     | 18        | 6.02%   |
| Protectli                      | 13        | 4.35%   |
| Gigabyte Technology            | 13        | 4.35%   |
| Unknown                        | 13        | 4.35%   |
| ASRock                         | 11        | 3.68%   |
| MSI                            | 9         | 3.01%   |
| PC Engines                     | 5         | 1.67%   |
| AWOW                           | 5         | 1.67%   |
| AMI                            | 5         | 1.67%   |
| Acer                           | 5         | 1.67%   |
| Apple                          | 4         | 1.34%   |
| Toshiba                        | 3         | 1%      |
| Panasonic                      | 3         | 1%      |
| IBM                            | 3         | 1%      |
| ZOTAC                          | 2         | 0.67%   |
| Techvision                     | 2         | 0.67%   |
| Sophos                         | 2         | 0.67%   |
| Matsushita Electric Industrial | 2         | 0.67%   |
| AZW                            | 2         | 0.67%   |
| Yanling                        | 1         | 0.33%   |
| Shuttle                        | 1         | 0.33%   |
| ShenZhen MinWin Technology     | 1         | 0.33%   |
| SeeedStudio                    | 1         | 0.33%   |
| Raspberry Pi Foundation        | 1         | 0.33%   |
| Quanta                         | 1         | 0.33%   |
| LG Electronics                 | 1         | 0.33%   |
| HPE                            | 1         | 0.33%   |
| HARDKERNEL                     | 1         | 0.33%   |
| Google                         | 1         | 0.33%   |
| Fujitsu                        | 1         | 0.33%   |
| Datto                          | 1         | 0.33%   |
| CompuLab                       | 1         | 0.33%   |
| CncTion                        | 1         | 0.33%   |
| Cisco                          | 1         | 0.33%   |
| Biostar                        | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 13        | 4.35%   |
| Protectli FW4B                     | 7         | 2.34%   |
| Protectli FW6                      | 5         | 1.67%   |
| Intel Q3XXG4-P V1.0                | 5         | 1.67%   |
| AWOW PC BOX                        | 5         | 1.67%   |
| Supermicro Super Server            | 4         | 1.34%   |
| Intel NDISB533                     | 4         | 1.34%   |
| Intel H81U                         | 3         | 1%      |
| HP t730 Thin Client                | 3         | 1%      |
| HP EliteDesk 800 G1 SFF            | 3         | 1%      |
| Dell OptiPlex 9010                 | 3         | 1%      |
| Dell G5 5090                       | 3         | 1%      |
| ASUS All Series                    | 3         | 1%      |
| AMI Aptio CRB                      | 3         | 1%      |
| Techvision TVI7309X                | 2         | 0.67%   |
| Supermicro X8STi                   | 2         | 0.67%   |
| PC Engines apu4                    | 2         | 0.67%   |
| PC Engines APU2                    | 2         | 0.67%   |
| Lenovo ThinkCentre M93p 10A8S16X0J | 2         | 0.67%   |
| HP Z440 Workstation                | 2         | 0.67%   |
| Dell Precision WorkStation T3500   | 2         | 0.67%   |
| Dell Precision Tower 5810          | 2         | 0.67%   |
| Dell PowerEdge R210 II             | 2         | 0.67%   |
| Dell OptiPlex 7010                 | 2         | 0.67%   |
| Dell OptiPlex 3020                 | 2         | 0.67%   |
| ASUS P8H77-I                       | 2         | 0.67%   |
| ASUS M5A97 PLUS                    | 2         | 0.67%   |
| ASRock H110M-DGS R3.0              | 2         | 0.67%   |
| ASRock B450M Pro4                  | 2         | 0.67%   |
| ZOTAC ZBOX-CI341                   | 1         | 0.33%   |
| ZOTAC ZBOX-CI329NANO               | 1         | 0.33%   |
| Yanling YL-KBR6L                   | 1         | 0.33%   |
| Toshiba TECRA Z40-B                | 1         | 0.33%   |
| Toshiba Satellite U500             | 1         | 0.33%   |
| Toshiba Satellite Pro T130         | 1         | 0.33%   |
| Supermicro X8DTH-i/6/iF/6F         | 1         | 0.33%   |
| Supermicro X8DT6                   | 1         | 0.33%   |
| Supermicro X7SPA-HF                | 1         | 0.33%   |
| Supermicro X7SLA                   | 1         | 0.33%   |
| Supermicro X10SLH-N6-ST031         | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 20        | 6.69%   |
| Lenovo ThinkCentre  | 15        | 5.02%   |
| Dell OptiPlex       | 15        | 5.02%   |
| Unknown             | 13        | 4.35%   |
| Dell PowerEdge      | 8         | 2.68%   |
| Protectli FW4B      | 7         | 2.34%   |
| HP ProDesk          | 6         | 2.01%   |
| HP EliteDesk        | 6         | 2.01%   |
| Protectli FW6       | 5         | 1.67%   |
| Intel Q3XXG4-P      | 5         | 1.67%   |
| Dell Precision      | 5         | 1.67%   |
| Dell Inspiron       | 5         | 1.67%   |
| AWOW PC             | 5         | 1.67%   |
| ASUS PRIME          | 5         | 1.67%   |
| Supermicro Super    | 4         | 1.34%   |
| Intel NDISB533      | 4         | 1.34%   |
| HP Compaq           | 4         | 1.34%   |
| Intel H81U          | 3         | 1%      |
| HP t730             | 3         | 1%      |
| HP ProLiant         | 3         | 1%      |
| Dell G5             | 3         | 1%      |
| ASUS All            | 3         | 1%      |
| ASRock B450M        | 3         | 1%      |
| AMI Aptio           | 3         | 1%      |
| Acer Aspire         | 3         | 1%      |
| Toshiba Satellite   | 2         | 0.67%   |
| Techvision TVI7309X | 2         | 0.67%   |
| Supermicro X8STi    | 2         | 0.67%   |
| PC Engines apu4     | 2         | 0.67%   |
| PC Engines APU2     | 2         | 0.67%   |
| IBM System          | 2         | 0.67%   |
| HP Z440             | 2         | 0.67%   |
| HP Pavilion         | 2         | 0.67%   |
| Dell Latitude       | 2         | 0.67%   |
| ASUS TUF            | 2         | 0.67%   |
| ASUS ROG            | 2         | 0.67%   |
| ASUS P8H77-I        | 2         | 0.67%   |
| ASUS M5A97          | 2         | 0.67%   |
| ASRock H110M-DGS    | 2         | 0.67%   |
| ZOTAC ZBOX-CI341    | 1         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 47        | 15.72%  |
| 2020    | 40        | 13.38%  |
| 2014    | 29        | 9.7%    |
| 2019    | 24        | 8.03%   |
| 2016    | 21        | 7.02%   |
| 2013    | 20        | 6.69%   |
| 2015    | 19        | 6.35%   |
| 2010    | 18        | 6.02%   |
| 2011    | 16        | 5.35%   |
| 2012    | 13        | 4.35%   |
| 2022    | 11        | 3.68%   |
| 2017    | 11        | 3.68%   |
| 2009    | 10        | 3.34%   |
| 2021    | 9         | 3.01%   |
| 2008    | 4         | 1.34%   |
| Unknown | 3         | 1%      |
| 2006    | 2         | 0.67%   |
| 2007    | 1         | 0.33%   |
| 2002    | 1         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 186       | 62.21%  |
| Notebook       | 59        | 19.73%  |
| Mini pc        | 24        | 8.03%   |
| Server         | 23        | 7.69%   |
| Firewall       | 3         | 1%      |
| All in one     | 3         | 1%      |
| System on chip | 1         | 0.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 291       | 97.32%  |
| Yes  | 8         | 2.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 114       | 37.5%   |
| 16.01-24.0      | 63        | 20.72%  |
| 4.01-8.0        | 54        | 17.76%  |
| 32.01-64.0      | 32        | 10.53%  |
| 64.01-256.0     | 13        | 4.28%   |
| 2.01-3.0        | 10        | 3.29%   |
| 3.01-4.0        | 6         | 1.97%   |
| 24.01-32.0      | 6         | 1.97%   |
| 0.51-1.0        | 3         | 0.99%   |
| 1.01-2.0        | 2         | 0.66%   |
| More than 256.0 | 1         | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 156       | 50.81%  |
| 0.51-1.0    | 86        | 28.01%  |
| 1.01-2.0    | 33        | 10.75%  |
| 4.01-8.0    | 7         | 2.28%   |
| 2.01-3.0    | 7         | 2.28%   |
| 3.01-4.0    | 5         | 1.63%   |
| 0           | 4         | 1.3%    |
| 24.01-32.0  | 3         | 0.98%   |
| 64.01-256.0 | 2         | 0.65%   |
| 8.01-16.0   | 2         | 0.65%   |
| 32.01-64.0  | 1         | 0.33%   |
| Unknown     | 1         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 212       | 69.28%  |
| 2      | 44        | 14.38%  |
| 0      | 22        | 7.19%   |
| 3      | 11        | 3.59%   |
| 4      | 7         | 2.29%   |
| 7      | 2         | 0.65%   |
| 5      | 2         | 0.65%   |
| 40     | 1         | 0.33%   |
| 25     | 1         | 0.33%   |
| 14     | 1         | 0.33%   |
| 13     | 1         | 0.33%   |
| 10     | 1         | 0.33%   |
| 6      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 236       | 77.89%  |
| Yes       | 67        | 22.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 293       | 97.99%  |
| No        | 6         | 2.01%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 194       | 64.03%  |
| Yes       | 109       | 35.97%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 224       | 74.42%  |
| Yes       | 77        | 25.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Canada  | 299       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Montreal                   | 35        | 10.61%  |
| Toronto                    | 30        | 9.09%   |
| Ottawa                     | 16        | 4.85%   |
| Victoria                   | 14        | 4.24%   |
| Calgary                    | 14        | 4.24%   |
| Vancouver                  | 12        | 3.64%   |
| Edmonton                   | 11        | 3.33%   |
| Winnipeg                   | 9         | 2.73%   |
| Saint-Laurent              | 9         | 2.73%   |
| Kitchener                  | 8         | 2.42%   |
| Brampton                   | 8         | 2.42%   |
| Surrey                     | 7         | 2.12%   |
| QuГ©bec                  | 6         | 1.82%   |
| Sainte-Julie               | 4         | 1.21%   |
| Québec                    | 4         | 1.21%   |
| Peterborough               | 4         | 1.21%   |
| Moncton                    | 4         | 1.21%   |
| Gatineau                   | 4         | 1.21%   |
| Burnaby                    | 4         | 1.21%   |
| Windsor                    | 3         | 0.91%   |
| St. Albert                 | 3         | 0.91%   |
| Sherwood Park              | 3         | 0.91%   |
| Sarnia                     | 3         | 0.91%   |
| Regina                     | 3         | 0.91%   |
| QuÃ©bec                  | 3         | 0.91%   |
| Oakville                   | 3         | 0.91%   |
| Maple Ridge                | 3         | 0.91%   |
| Laval                      | 3         | 0.91%   |
| Kingston                   | 3         | 0.91%   |
| Kingsburg                  | 3         | 0.91%   |
| Kanata                     | 3         | 0.91%   |
| Hamilton                   | 3         | 0.91%   |
| Guelph                     | 3         | 0.91%   |
| Terrebonne                 | 2         | 0.61%   |
| Stratford                  | 2         | 0.61%   |
| Smiths Falls               | 2         | 0.61%   |
| Sherbrooke                 | 2         | 0.61%   |
| Saskatoon                  | 2         | 0.61%   |
| Saint-Bruno-de-Montarville | 2         | 0.61%   |
| Richmond                   | 2         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 55        | 84     | 15.76%  |
| WDC                 | 54        | 144    | 15.47%  |
| Seagate             | 44        | 91     | 12.61%  |
| Kingston            | 35        | 41     | 10.03%  |
| Intel               | 16        | 19     | 4.58%   |
| Crucial             | 15        | 18     | 4.3%    |
| Toshiba             | 13        | 18     | 3.72%   |
| A-DATA Technology   | 11        | 20     | 3.15%   |
| SanDisk             | 9         | 13     | 2.58%   |
| Hitachi             | 9         | 51     | 2.58%   |
| Dogfish             | 7         | 16     | 2.01%   |
| OCZ                 | 6         | 9      | 1.72%   |
| FORESEE             | 6         | 19     | 1.72%   |
| SPCC                | 5         | 5      | 1.43%   |
| SK hynix            | 5         | 7      | 1.43%   |
| Hewlett-Packard     | 5         | 5      | 1.43%   |
| Mushkin             | 4         | 4      | 1.15%   |
| Micron Technology   | 4         | 7      | 1.15%   |
| Hoodisk             | 4         | 5      | 1.15%   |
| HGST                | 4         | 40     | 1.15%   |
| BIWIN               | 4         | 4      | 1.15%   |
| Transcend           | 3         | 4      | 0.86%   |
| PNY                 | 3         | 4      | 0.86%   |
| NVMe                | 3         | 3      | 0.86%   |
| VisionTek           | 2         | 6      | 0.57%   |
| Phison              | 2         | 2      | 0.57%   |
| Lexar               | 2         | 3      | 0.57%   |
| Corsair             | 2         | 4      | 0.57%   |
| China               | 2         | 3      | 0.57%   |
| Apacer              | 2         | 2      | 0.57%   |
| XPG                 | 1         | 1      | 0.29%   |
| Timetec             | 1         | 1      | 0.29%   |
| Team                | 1         | 1      | 0.29%   |
| SATADOM             | 1         | 2      | 0.29%   |
| Protectli           | 1         | 2      | 0.29%   |
| Netac               | 1         | 1      | 0.29%   |
| Kston               | 1         | 2      | 0.29%   |
| KingDian            | 1         | 1      | 0.29%   |
| HPE                 | 1         | 4      | 0.29%   |
| HP Phison           | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB     | 12        | 3.14%   |
| Kingston SA400S37120G 120GB     | 9         | 2.36%   |
| Samsung SSD 850 EVO 250GB       | 6         | 1.57%   |
| FORESEE 128GB SSD               | 6         | 1.57%   |
| Seagate ST1000DM010-2EP102 1TB  | 5         | 1.31%   |
| Samsung SSD 860 EVO 500GB       | 5         | 1.31%   |
| BIWIN SSD 128GB                 | 4         | 1.05%   |
| WDC WDS500G2B0A-00SM50 500GB    | 3         | 0.79%   |
| WDC WD20EZRX-00DC0B0 2TB        | 3         | 0.79%   |
| Toshiba DT01ACA100 1TB          | 3         | 0.79%   |
| Seagate ST500DM002-1BD142 500GB | 3         | 0.79%   |
| Seagate ST3500413AS 500GB       | 3         | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB  | 3         | 0.79%   |
| SanDisk SD6SB1M064G1022I 64GB   | 3         | 0.79%   |
| Samsung SSD 840 EVO 120GB       | 3         | 0.79%   |
| Dogfish SSD 128GB               | 3         | 0.79%   |
| Crucial CT240BX500SSD1 240GB    | 3         | 0.79%   |
| WDC WD7500BPKX-00HPJT0 752GB    | 2         | 0.52%   |
| WDC WD40EFRX-68WT0N0 4TB        | 2         | 0.52%   |
| WDC WD30EFRX-68EUZN0 3TB        | 2         | 0.52%   |
| WDC WD20EFRX-68EUZN0 2TB        | 2         | 0.52%   |
| WDC WD120EDAZ-11F3RA0 12TB      | 2         | 0.52%   |
| WDC WD10JPLX-00MBPT0 1TB        | 2         | 0.52%   |
| WDC WD10EZEX-22MFCA0 1TB        | 2         | 0.52%   |
| WDC WD10EZEX-08WN4A0 1TB        | 2         | 0.52%   |
| WDC PC SN520 NVMe 256GB         | 2         | 0.52%   |
| VisionTek mSATA 120GB           | 2         | 0.52%   |
| Transcend TS256GMSA230S 256GB   | 2         | 0.52%   |
| Toshiba MQ01ABD075 752GB        | 2         | 0.52%   |
| SPCC Solid State Disk 256GB     | 2         | 0.52%   |
| Seagate ST2000DM001-1ER164 2TB  | 2         | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB  | 2         | 0.52%   |
| Samsung SSD 980 PRO 1TB         | 2         | 0.52%   |
| Samsung SSD 970 EVO Plus 250GB  | 2         | 0.52%   |
| Samsung SSD 870 EVO 250GB       | 2         | 0.52%   |
| Samsung SSD 860 PRO 256GB       | 2         | 0.52%   |
| Samsung SSD 860 EVO 1TB         | 2         | 0.52%   |
| Samsung SSD 850 PRO 256GB       | 2         | 0.52%   |
| Samsung SSD 850 EVO mSATA 250GB | 2         | 0.52%   |
| Samsung SSD 850 EVO 500GB       | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 89     | 37.17%  |
| WDC                 | 41        | 123    | 36.28%  |
| Toshiba             | 11        | 14     | 9.73%   |
| Hitachi             | 9         | 51     | 7.96%   |
| HGST                | 4         | 40     | 3.54%   |
| NVMe                | 2         | 2      | 1.77%   |
| Samsung Electronics | 1         | 1      | 0.88%   |
| Lexar               | 1         | 1      | 0.88%   |
| Hewlett-Packard     | 1         | 1      | 0.88%   |
| Fujitsu             | 1         | 1      | 0.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 46        | 67     | 22.33%  |
| Kingston            | 35        | 40     | 16.99%  |
| Intel               | 13        | 16     | 6.31%   |
| Crucial             | 13        | 16     | 6.31%   |
| A-DATA Technology   | 10        | 19     | 4.85%   |
| WDC                 | 9         | 11     | 4.37%   |
| SanDisk             | 9         | 13     | 4.37%   |
| Dogfish             | 7         | 16     | 3.4%    |
| OCZ                 | 6         | 9      | 2.91%   |
| FORESEE             | 6         | 19     | 2.91%   |
| SPCC                | 4         | 4      | 1.94%   |
| Mushkin             | 4         | 4      | 1.94%   |
| Micron Technology   | 4         | 7      | 1.94%   |
| Hoodisk             | 4         | 5      | 1.94%   |
| BIWIN               | 4         | 4      | 1.94%   |
| Transcend           | 3         | 4      | 1.46%   |
| PNY                 | 3         | 4      | 1.46%   |
| VisionTek           | 2         | 6      | 0.97%   |
| SK hynix            | 2         | 2      | 0.97%   |
| Seagate             | 2         | 2      | 0.97%   |
| Hewlett-Packard     | 2         | 2      | 0.97%   |
| Corsair             | 2         | 4      | 0.97%   |
| China               | 2         | 3      | 0.97%   |
| Apacer              | 2         | 2      | 0.97%   |
| Toshiba             | 1         | 1      | 0.49%   |
| SATADOM             | 1         | 2      | 0.49%   |
| Protectli           | 1         | 2      | 0.49%   |
| Phison              | 1         | 1      | 0.49%   |
| Netac               | 1         | 1      | 0.49%   |
| Lexar               | 1         | 2      | 0.49%   |
| Kston               | 1         | 2      | 0.49%   |
| KingDian            | 1         | 1      | 0.49%   |
| HPE                 | 1         | 4      | 0.49%   |
| HP Phison           | 1         | 1      | 0.49%   |
| EAGET               | 1         | 1      | 0.49%   |
| AVEXIR              | 1         | 2      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 188       | 299    | 59.12%  |
| HDD  | 97        | 323    | 30.5%   |
| NVMe | 33        | 49     | 10.38%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 261       | 622    | 88.78%  |
| NVMe | 33        | 49     | 11.22%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 211       | 337    | 69.87%  |
| 0.51-1.0   | 52        | 100    | 17.22%  |
| 1.01-2.0   | 16        | 43     | 5.3%    |
| 3.01-4.0   | 7         | 54     | 2.32%   |
| 2.01-3.0   | 6         | 25     | 1.99%   |
| 4.01-10.0  | 6         | 45     | 1.99%   |
| 10.01-20.0 | 4         | 18     | 1.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 121       | 38.66%  |
| 251-500        | 47        | 15.02%  |
| 21-50          | 42        | 13.42%  |
| 1-20           | 39        | 12.46%  |
| 51-100         | 36        | 11.5%   |
| 501-1000       | 17        | 5.43%   |
| 1001-2000      | 7         | 2.24%   |
| Unknown        | 3         | 0.96%   |
| More than 3000 | 1         | 0.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 266       | 85.26%  |
| 21-50    | 32        | 10.26%  |
| 51-100   | 8         | 2.56%   |
| Unknown  | 3         | 0.96%   |
| 251-500  | 1         | 0.32%   |
| 101-250  | 1         | 0.32%   |
| 501-1000 | 1         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| VisionTek mSATA 120GB                      | 2         | 6      | 4%      |
| Toshiba MQ01ABD075 752GB                   | 2         | 2      | 4%      |
| Seagate ST500DM002-1BD142 500GB            | 2         | 4      | 4%      |
| Seagate ST3500413AS 500GB                  | 2         | 4      | 4%      |
| WDC WDS200T2B0A 2TB                        | 1         | 1      | 2%      |
| WDC WD7500BPKX-00HPJT0 752GB               | 1         | 4      | 2%      |
| WDC WD6400BEVT-22A0RT0 640GB               | 1         | 1      | 2%      |
| WDC WD6400AAKS-22A7B2 640GB                | 1         | 4      | 2%      |
| WDC WD50EFRX-68L0BN1 5TB                   | 1         | 1      | 2%      |
| WDC WD40EFRX-68WT0N0 4TB                   | 1         | 2      | 2%      |
| WDC WD30EZRX-22D8PB0 3TB                   | 1         | 1      | 2%      |
| WDC WD2500AAKX-001CA0 250GB                | 1         | 1      | 2%      |
| Toshiba DT01ACA100 1TB                     | 1         | 3      | 2%      |
| Seagate ST9500420AS 500GB                  | 1         | 2      | 2%      |
| Seagate ST500LM021-1KJ152 500GB            | 1         | 1      | 2%      |
| Seagate ST3250318AS 250GB                  | 1         | 1      | 2%      |
| Seagate ST3200822AS 200GB                  | 1         | 1      | 2%      |
| Seagate ST3160815AS 160GB                  | 1         | 1      | 2%      |
| Seagate ST31500341AS 1.5TB                 | 1         | 2      | 2%      |
| Seagate ST3120026A 120GB                   | 1         | 1      | 2%      |
| Seagate ST31000520AS 1TB                   | 1         | 1      | 2%      |
| Seagate ST2000DL003-9VT166 2TB             | 1         | 4      | 2%      |
| Seagate ST1000DM003-1CH162 1TB             | 1         | 2      | 2%      |
| Samsung Electronics SSD 970 EVO 2TB        | 1         | 1      | 2%      |
| Samsung Electronics SSD 870 EVO 250GB      | 1         | 2      | 2%      |
| Samsung Electronics SSD 860 EVO 1TB        | 1         | 2      | 2%      |
| OCZ VERTEX 32GB                            | 1         | 3      | 2%      |
| Mushkin MKNSSDEC512GB                      | 1         | 1      | 2%      |
| Micron Technology M500_MTFDDAK960MAV 960GB | 1         | 4      | 2%      |
| Kingston SV300S37A120G 120GB               | 1         | 1      | 2%      |
| Kingston SNS4151S316GD 16GB                | 1         | 1      | 2%      |
| Intel SSDSC2CW120A3 120GB                  | 1         | 1      | 2%      |
| Intel SSDSC2BB480G4 480GB                  | 1         | 1      | 2%      |
| Intel SSDSC2BB012T7 1.2TB                  | 1         | 2      | 2%      |
| Intel SSDSA2M080G2GC 80GB                  | 1         | 1      | 2%      |
| HP Phison PSSBN016GA27MC0 16GB             | 1         | 1      | 2%      |
| Hitachi HTS541612J9SA00 120GB              | 1         | 1      | 2%      |
| Hitachi HDT721064SLA360 640GB              | 1         | 1      | 2%      |
| Hitachi HDT721010SLA360 1TB                | 1         | 1      | 2%      |
| Hitachi HDS5C3030ALA630 3TB                | 1         | 14     | 2%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 24     | 27.08%  |
| WDC                 | 8         | 15     | 16.67%  |
| Intel               | 4         | 5      | 8.33%   |
| Hitachi             | 4         | 17     | 8.33%   |
| Toshiba             | 3         | 5      | 6.25%   |
| VisionTek           | 2         | 6      | 4.17%   |
| Samsung Electronics | 2         | 5      | 4.17%   |
| Kingston            | 2         | 2      | 4.17%   |
| HGST                | 2         | 2      | 4.17%   |
| OCZ                 | 1         | 3      | 2.08%   |
| Mushkin             | 1         | 1      | 2.08%   |
| Micron Technology   | 1         | 4      | 2.08%   |
| HP Phison           | 1         | 1      | 2.08%   |
| Dogfish             | 1         | 2      | 2.08%   |
| Crucial             | 1         | 1      | 2.08%   |
| Apacer              | 1         | 1      | 2.08%   |
| A-DATA Technology   | 1         | 4      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 24     | 44.83%  |
| WDC     | 7         | 14     | 24.14%  |
| Hitachi | 4         | 17     | 13.79%  |
| Toshiba | 3         | 5      | 10.34%  |
| HGST    | 2         | 2      | 6.9%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 62     | 57.45%  |
| SSD  | 19        | 35     | 40.43%  |
| NVMe | 1         | 1      | 2.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-00Z10T0 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 247       | 563    | 81.79%  |
| Malfunc  | 45        | 98     | 14.9%   |
| Detected | 9         | 9      | 2.98%   |
| Failed   | 1         | 1      | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 243       | 68.26%  |
| AMD                         | 39        | 10.96%  |
| Samsung Electronics         | 14        | 3.93%   |
| Broadcom / LSI              | 12        | 3.37%   |
| SanDisk                     | 9         | 2.53%   |
| Nvidia                      | 6         | 1.69%   |
| Silicon Motion              | 4         | 1.12%   |
| Chelsio Communications      | 4         | 1.12%   |
| ASMedia Technology          | 4         | 1.12%   |
| SK hynix                    | 3         | 0.84%   |
| Marvell Technology Group    | 3         | 0.84%   |
| Silicon Image               | 2         | 0.56%   |
| Micron/Crucial Technology   | 2         | 0.56%   |
| JMicron Technology          | 2         | 0.56%   |
| Hewlett-Packard             | 2         | 0.56%   |
| Toshiba                     | 1         | 0.28%   |
| Realtek Semiconductor       | 1         | 0.28%   |
| Phison Electronics          | 1         | 0.28%   |
| MAXIO Technology (Hangzhou) | 1         | 0.28%   |
| Kingston Technology Company | 1         | 0.28%   |
| Dell                        | 1         | 0.28%   |
| ADATA Technology            | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 32        | 7.94%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 4.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 4.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 13        | 3.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 2.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 11        | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 11        | 2.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 9         | 2.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9         | 2.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 2.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 9         | 2.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 2.23%   |
| AMD 400 Series Chipset SATA Controller                                           | 9         | 2.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8         | 1.99%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 8         | 1.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 1.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 7         | 1.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 1.49%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 5         | 1.24%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 1.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 1.24%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 0.99%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 4         | 0.99%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 4         | 0.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 0.99%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 4         | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4         | 0.99%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3         | 0.74%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 0.74%   |
| SanDisk PC SN520 NVMe SSD                                                        | 3         | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3         | 0.74%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.74%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3         | 0.74%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 3         | 0.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 0.74%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 0.74%   |
| AMD FCH SATA Controller [IDE mode]                                               | 3         | 0.74%   |
| AMD FCH IDE Controller                                                           | 3         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 248       | 69.27%  |
| IDE  | 44        | 12.29%  |
| NVMe | 37        | 10.34%  |
| RAID | 17        | 4.75%   |
| SAS  | 6         | 1.68%   |
| SCSI | 6         | 1.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 255       | 84.44%  |
| AMD     | 45        | 14.9%   |
| ARM     | 1         | 0.33%   |
| Unknown | 1         | 0.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz        | 8         | 2.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 7         | 2.28%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 6         | 1.95%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 6         | 1.95%   |
| Intel Core i5-3570 CPU @ 3.40GHz         | 6         | 1.95%   |
| Intel Celeron N5105 @ 2.00GHz            | 5         | 1.63%   |
| Intel Celeron CPU J3455E @ 1.50GHz       | 5         | 1.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 4         | 1.3%    |
| Intel Core i5-4590 CPU @ 3.30GHz         | 4         | 1.3%    |
| Intel Core i5-4570TE CPU @ 2.70GHz       | 4         | 1.3%    |
| Intel Core i5-2520M CPU @ 2.50GHz        | 4         | 1.3%    |
| Intel Celeron J4125 CPU @ 2.00GHz        | 4         | 1.3%    |
| Intel Celeron CPU J1900 @ 1.99GHz        | 4         | 1.3%    |
| AMD GX-412TC SOC                         | 4         | 1.3%    |
| Intel Xeon                               | 3         | 0.98%   |
| Intel Pentium CPU G4560 @ 3.50GHz        | 3         | 0.98%   |
| Intel Core i7-9700K CPU @ 3.60GHz        | 3         | 0.98%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 3         | 0.98%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 3         | 0.98%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 3         | 0.98%   |
| Intel Core i3-5005U CPU @ 2.00GHz        | 3         | 0.98%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 3         | 0.98%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 3         | 0.98%   |
| Intel Xeon CPU E5645 @ 2.40GHz           | 2         | 0.65%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz      | 2         | 0.65%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz      | 2         | 0.65%   |
| Intel CPU Version                        | 2         | 0.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 2         | 0.65%   |
| Intel Core i7-7700 CPU @ 3.60GHz         | 2         | 0.65%   |
| Intel Core i7-4790K CPU @ 4.00GHz        | 2         | 0.65%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 2         | 0.65%   |
| Intel Core i5-8400 CPU @ 2.80GHz         | 2         | 0.65%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 2         | 0.65%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 0.65%   |
| Intel Core i5-4670 CPU @ 3.40GHz         | 2         | 0.65%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 2         | 0.65%   |
| Intel Core i5-3470T CPU @ 2.90GHz        | 2         | 0.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 2         | 0.65%   |
| Intel Core i5-10400 CPU @ 2.90GHz        | 2         | 0.65%   |
| Intel Core i3-5010U CPU @ 2.10GHz        | 2         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 87        | 28.62%  |
| Intel Celeron           | 40        | 13.16%  |
| Intel Xeon              | 36        | 11.84%  |
| Intel Core i7           | 31        | 10.2%   |
| Intel Core i3           | 26        | 8.55%   |
| Intel Atom              | 12        | 3.95%   |
| Other                   | 10        | 3.29%   |
| Intel Pentium           | 6         | 1.97%   |
| Intel Core 2 Duo        | 6         | 1.97%   |
| AMD FX                  | 6         | 1.97%   |
| AMD GX                  | 5         | 1.64%   |
| AMD Ryzen 7             | 4         | 1.32%   |
| AMD Ryzen 5             | 4         | 1.32%   |
| Intel Pentium Dual-Core | 3         | 0.99%   |
| AMD Athlon 64 X2        | 3         | 0.99%   |
| Intel Pentium 4         | 2         | 0.66%   |
| Intel Core 2 Quad       | 2         | 0.66%   |
| AMD Ryzen Embedded      | 2         | 0.66%   |
| AMD Ryzen 9             | 2         | 0.66%   |
| AMD Ryzen 5 PRO         | 2         | 0.66%   |
| AMD Ryzen 3             | 2         | 0.66%   |
| AMD Opteron             | 2         | 0.66%   |
| AMD G                   | 2         | 0.66%   |
| AMD EPYC                | 2         | 0.66%   |
| Intel Genuine           | 1         | 0.33%   |
| ARM Cortex              | 1         | 0.33%   |
| AMD Phenom II X6        | 1         | 0.33%   |
| AMD Phenom              | 1         | 0.33%   |
| AMD E                   | 1         | 0.33%   |
| AMD Athlon              | 1         | 0.33%   |
| AMD A6                  | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 134       | 44.37%  |
| 2       | 96        | 31.79%  |
| 6       | 20        | 6.62%   |
| 8       | 17        | 5.63%   |
| Unknown | 11        | 3.64%   |
| 12      | 10        | 3.31%   |
| 16      | 6         | 1.99%   |
| 10      | 2         | 0.66%   |
| 64      | 1         | 0.33%   |
| 32      | 1         | 0.33%   |
| 24      | 1         | 0.33%   |
| 11      | 1         | 0.33%   |
| 3       | 1         | 0.33%   |
| 1       | 1         | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 283       | 93.71%  |
| 2       | 13        | 4.3%    |
| Unknown | 6         | 1.99%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 153       | 51%     |
| 2       | 135       | 45%     |
| Unknown | 12        | 4%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 49        | 16.01%  |
| KabyLake      | 34        | 11.11%  |
| IvyBridge     | 26        | 8.5%    |
| Skylake       | 21        | 6.86%   |
| Silvermont    | 17        | 5.56%   |
| Broadwell     | 16        | 5.23%   |
| SandyBridge   | 15        | 4.9%    |
| Westmere      | 14        | 4.58%   |
| Penryn        | 11        | 3.59%   |
| Goldmont      | 11        | 3.59%   |
| Unknown       | 11        | 3.59%   |
| Goldmont plus | 9         | 2.94%   |
| Zen+          | 8         | 2.61%   |
| Piledriver    | 8         | 2.61%   |
| CometLake     | 7         | 2.29%   |
| Nehalem       | 6         | 1.96%   |
| Bonnell       | 6         | 1.96%   |
| Zen 2         | 4         | 1.31%   |
| Zen           | 4         | 1.31%   |
| Puma          | 4         | 1.31%   |
| Steamroller   | 3         | 0.98%   |
| K8 Hammer     | 3         | 0.98%   |
| K10           | 3         | 0.98%   |
| Core          | 3         | 0.98%   |
| Bobcat        | 3         | 0.98%   |
| Zen 3         | 2         | 0.65%   |
| NetBurst      | 2         | 0.65%   |
| Jaguar        | 2         | 0.65%   |
| TigerLake     | 1         | 0.33%   |
| P6            | 1         | 0.33%   |
| IceLake       | 1         | 0.33%   |
| Excavator     | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 187       | 62.54%  |
| Nvidia                     | 42        | 14.05%  |
| AMD                        | 40        | 13.38%  |
| Matrox Electronics Systems | 17        | 5.69%   |
| ASPEED Technology          | 13        | 4.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 28        | 9.21%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 13        | 4.28%   |
| Intel HD Graphics 5500                                                                   | 12        | 3.95%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 10        | 3.29%   |
| Intel HD Graphics 530                                                                    | 10        | 3.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 3.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 3.29%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 2.96%   |
| Intel HD Graphics 500                                                                    | 9         | 2.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 2.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 2.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 2.63%   |
| Intel HD Graphics 620                                                                    | 6         | 1.97%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.64%   |
| Intel JasperLake [UHD Graphics]                                                          | 5         | 1.64%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 5         | 1.64%   |
| Intel HD Graphics 630                                                                    | 5         | 1.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 1.64%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.32%   |
| Intel HD Graphics 610                                                                    | 4         | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.32%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.32%   |
| Matrox Electronics Systems G200eR2                                                       | 3         | 0.99%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.99%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3         | 0.99%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2         | 0.66%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.66%   |
| Nvidia GM107GL [Quadro K620]                                                             | 2         | 0.66%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 2         | 0.66%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2         | 0.66%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 0.66%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.66%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.66%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.66%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 172       | 56.95%  |
| 1 x AMD        | 39        | 12.91%  |
| 1 x Nvidia     | 35        | 11.59%  |
| 1 x Matrox     | 17        | 5.63%   |
| 1 x ASPEED     | 12        | 3.97%   |
| Other          | 11        | 3.64%   |
| 2 x Intel      | 8         | 2.65%   |
| Intel + Nvidia | 7         | 2.32%   |
| AMD + ASPEED   | 1         | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 266       | 88.37%  |
| Proprietary | 23        | 7.64%   |
| Unknown     | 12        | 3.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 262       | 87.04%  |
| 1.01-2.0   | 11        | 3.65%   |
| 0.51-1.0   | 10        | 3.32%   |
| 3.01-4.0   | 6         | 1.99%   |
| 0.01-0.5   | 5         | 1.66%   |
| 7.01-8.0   | 3         | 1%      |
| 5.01-6.0   | 3         | 1%      |
| 2.01-3.0   | 1         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Goldstar                | 12        | 13.04%  |
| Dell                    | 10        | 10.87%  |
| LG Display              | 9         | 9.78%   |
| Chimei Innolux          | 9         | 9.78%   |
| Samsung Electronics     | 7         | 7.61%   |
| AU Optronics            | 6         | 6.52%   |
| Lenovo                  | 5         | 5.43%   |
| BOE                     | 5         | 5.43%   |
| BenQ                    | 5         | 5.43%   |
| Chi Mei Optoelectronics | 3         | 3.26%   |
| Toshiba                 | 2         | 2.17%   |
| Sony                    | 2         | 2.17%   |
| Hewlett-Packard         | 2         | 2.17%   |
| Apple                   | 2         | 2.17%   |
| AOC                     | 2         | 2.17%   |
| Ancor Communications    | 2         | 2.17%   |
| Acer                    | 2         | 2.17%   |
| ViewSonic               | 1         | 1.09%   |
| Videoseven              | 1         | 1.09%   |
| RTK                     | 1         | 1.09%   |
| LTV                     | 1         | 1.09%   |
| LG Electronics          | 1         | 1.09%   |
| Insignia                | 1         | 1.09%   |
| ASUSTek Computer        | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Sony LCD Monitor TV XV 1920x1080                                       | 2         | 2.08%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 2         | 2.08%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch            | 2         | 2.08%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 2         | 2.08%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch       | 2         | 2.08%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch         | 2         | 2.08%   |
| ViewSonic LCD Monitor VSCFA2B 1920x1080 510x290mm 23.1-inch            | 1         | 1.04%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1         | 1.04%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 1         | 1.04%   |
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch               | 1         | 1.04%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch   | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 330x210mm 15.4-inch   | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch   | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch   | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1210x680mm 54.6-inch | 1         | 1.04%   |
| RTK CPL AIO PC RTK2482 1920x1080 510x280mm 22.9-inch                   | 1         | 1.04%   |
| LTV LTV1280M1A LTV0A3C 1024x768 800x450mm 36.1-inch                    | 1         | 1.04%   |
| LG Electronics LCD Monitor LG Ultra HD 7680x2160                       | 1         | 1.04%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1         | 1.04%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch            | 1         | 1.04%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch            | 1         | 1.04%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch            | 1         | 1.04%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch            | 1         | 1.04%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch            | 1         | 1.04%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch           | 1         | 1.04%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch           | 1         | 1.04%   |
| Lenovo LEN-M93z-B  LEN0093 1920x1080 510x290mm 23.1-inch               | 1         | 1.04%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch                | 1         | 1.04%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                | 1         | 1.04%   |
| Insignia LCD Monitor BBY0050 1920x1080 700x400mm 31.7-inch             | 1         | 1.04%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1         | 1.04%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch             | 1         | 1.04%   |
| Goldstar W2442 GSM56D9 1920x1080 530x300mm 24.0-inch                   | 1         | 1.04%   |
| Goldstar W2052 GSM4E88 1680x1050 470x300mm 22.0-inch                   | 1         | 1.04%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                   | 1         | 1.04%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 1         | 1.04%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch            | 1         | 1.04%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch            | 1         | 1.04%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch             | 1         | 1.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 40        | 43.96%  |
| 1366x768 (WXGA)    | 15        | 16.48%  |
| 3840x2160 (4K)     | 7         | 7.69%   |
| 1600x900 (HD+)     | 6         | 6.59%   |
| 1280x800 (WXGA)    | 3         | 3.3%    |
| 3440x1440          | 2         | 2.2%    |
| 2560x1440 (QHD)    | 2         | 2.2%    |
| 2560x1080          | 2         | 2.2%    |
| 1680x1050 (WSXGA+) | 2         | 2.2%    |
| 1440x900 (WXGA+)   | 2         | 2.2%    |
| 1280x1024 (SXGA)   | 2         | 2.2%    |
| Unknown            | 2         | 2.2%    |
| 7680x2160          | 1         | 1.1%    |
| 2256x1504          | 1         | 1.1%    |
| 1920x1200 (WUXGA)  | 1         | 1.1%    |
| 1600x1200          | 1         | 1.1%    |
| 1280x854           | 1         | 1.1%    |
| 1024x768 (XGA)     | 1         | 1.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 17        | 18.28%  |
| 24      | 11        | 11.83%  |
| 15      | 11        | 11.83%  |
| 27      | 8         | 8.6%    |
| 12      | 7         | 7.53%   |
| 21      | 6         | 6.45%   |
| 23      | 5         | 5.38%   |
| 19      | 5         | 5.38%   |
| 34      | 4         | 4.3%    |
| Unknown | 4         | 4.3%    |
| 54      | 3         | 3.23%   |
| 22      | 3         | 3.23%   |
| 31      | 2         | 2.15%   |
| 17      | 2         | 2.15%   |
| 36      | 1         | 1.08%   |
| 20      | 1         | 1.08%   |
| 18      | 1         | 1.08%   |
| 14      | 1         | 1.08%   |
| 11      | 1         | 1.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 24        | 26.09%  |
| 301-350     | 22        | 23.91%  |
| 201-300     | 15        | 16.3%   |
| 401-500     | 13        | 14.13%  |
| 701-800     | 5         | 5.43%   |
| 351-400     | 4         | 4.35%   |
| Unknown     | 4         | 4.35%   |
| 1001-1500   | 3         | 3.26%   |
| 601-700     | 2         | 2.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 69        | 76.67%  |
| 16/10   | 8         | 8.89%   |
| 21/9    | 4         | 4.44%   |
| Unknown | 4         | 4.44%   |
| 5/4     | 2         | 2.22%   |
| 3/2     | 2         | 2.22%   |
| 4/3     | 1         | 1.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 23        | 25%     |
| 81-90          | 14        | 15.22%  |
| 301-350        | 8         | 8.7%    |
| 61-70          | 7         | 7.61%   |
| 351-500        | 6         | 6.52%   |
| 151-200        | 6         | 6.52%   |
| 101-110        | 6         | 6.52%   |
| 91-100         | 5         | 5.43%   |
| 71-80          | 4         | 4.35%   |
| Unknown        | 4         | 4.35%   |
| More than 1000 | 3         | 3.26%   |
| 121-130        | 2         | 2.17%   |
| 51-60          | 1         | 1.09%   |
| 251-300        | 1         | 1.09%   |
| 141-150        | 1         | 1.09%   |
| 501-1000       | 1         | 1.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 37        | 39.78%  |
| 101-120 | 22        | 23.66%  |
| 121-160 | 20        | 21.51%  |
| 161-240 | 9         | 9.68%   |
| Unknown | 4         | 4.3%    |
| 1-50    | 1         | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 203       | 67.22%  |
| 1     | 90        | 29.8%   |
| 2     | 9         | 2.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 225       | 52.82%  |
| Realtek Semiconductor             | 110       | 25.82%  |
| Broadcom                          | 32        | 7.51%   |
| Qualcomm Atheros                  | 22        | 5.16%   |
| Chelsio Communications            | 6         | 1.41%   |
| Solarflare Communications         | 3         | 0.7%    |
| Marvell Technology Group          | 3         | 0.7%    |
| Sierra Wireless                   | 2         | 0.47%   |
| Ralink                            | 2         | 0.47%   |
| Nvidia                            | 2         | 0.47%   |
| IBM                               | 2         | 0.47%   |
| Ericsson Business Mobile Networks | 2         | 0.47%   |
| 3Com                              | 2         | 0.47%   |
| TP-Link                           | 1         | 0.23%   |
| Ralink Technology                 | 1         | 0.23%   |
| Qualcomm Atheros Communications   | 1         | 0.23%   |
| QLogic                            | 1         | 0.23%   |
| NetGear                           | 1         | 0.23%   |
| Mellanox Technologies             | 1         | 0.23%   |
| MediaTek                          | 1         | 0.23%   |
| JMicron Technology                | 1         | 0.23%   |
| Insyde Software                   | 1         | 0.23%   |
| IMC Networks                      | 1         | 0.23%   |
| Google                            | 1         | 0.23%   |
| D-Link System                     | 1         | 0.23%   |
| Apple                             | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 92        | 17.1%   |
| Intel I211 Gigabit Network Connection                                         | 28        | 5.2%    |
| Intel 82574L Gigabit Network Connection                                       | 23        | 4.28%   |
| Intel Ethernet Connection I217-LM                                             | 20        | 3.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 19        | 3.53%   |
| Intel I350 Gigabit Network Connection                                         | 15        | 2.79%   |
| Intel I210 Gigabit Network Connection                                         | 15        | 2.79%   |
| Intel Wireless 7265                                                           | 10        | 1.86%   |
| Intel 82576 Gigabit Network Connection                                        | 10        | 1.86%   |
| Intel 82583V Gigabit Network Connection                                       | 9         | 1.67%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9         | 1.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8         | 1.49%   |
| Intel Wireless 8260                                                           | 8         | 1.49%   |
| Intel 82580 Gigabit Network Connection                                        | 8         | 1.49%   |
| Intel Wireless 7260                                                           | 7         | 1.3%    |
| Intel Ethernet Connection I219-LM                                             | 7         | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 7         | 1.3%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 7         | 1.3%    |
| Intel Wi-Fi 6 AX200                                                           | 6         | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5         | 0.93%   |
| Intel Wireless 3165                                                           | 5         | 0.93%   |
| Intel Ethernet Controller I225-V                                              | 5         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5         | 0.93%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 5         | 0.93%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 0.74%   |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 0.74%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 0.74%   |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 0.74%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3         | 0.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 3         | 0.56%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 3         | 0.56%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3         | 0.56%   |
| Intel Ethernet Connection (3) I218-V                                          | 3         | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3         | 0.56%   |
| Intel Centrino Advanced-N 6200                                                | 3         | 0.56%   |
| Intel 82575GB Gigabit Network Connection                                      | 3         | 0.56%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3         | 0.56%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3         | 0.56%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 3         | 0.56%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 73        | 64.6%   |
| Qualcomm Atheros                | 16        | 14.16%  |
| Realtek Semiconductor           | 8         | 7.08%   |
| Broadcom                        | 7         | 6.19%   |
| Ralink                          | 2         | 1.77%   |
| TP-Link                         | 1         | 0.88%   |
| Sierra Wireless                 | 1         | 0.88%   |
| Ralink Technology               | 1         | 0.88%   |
| Qualcomm Atheros Communications | 1         | 0.88%   |
| NetGear                         | 1         | 0.88%   |
| MediaTek                        | 1         | 0.88%   |
| IMC Networks                    | 1         | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 10        | 8.77%   |
| Intel Wireless 8260                                                     | 8         | 7.02%   |
| Intel Wireless 7260                                                     | 7         | 6.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 6.14%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 5.26%   |
| Intel Wireless 3165                                                     | 5         | 4.39%   |
| Intel Wireless 8265 / 8275                                              | 4         | 3.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 2.63%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 2.63%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 2.63%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 1.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.75%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                   | 1         | 0.88%   |
| Sierra Wireless EM7455                                                  | 1         | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.88%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.88%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.88%   |
| Realtek Realtek Bluetooth Adapter                                       | 1         | 0.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.88%   |
| Ralink RT5592 PCIe Wireless Network Adapter                             | 1         | 0.88%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1         | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.88%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.88%   |
| Qualcomm Atheros AR958x 802.11abgn Wireless Network Adapter             | 1         | 0.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.88%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.88%   |
| NetGear A6200 802.11a/b/g/n/ac Wireless Adapter [Broadcom BCM43526]     | 1         | 0.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.88%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 192       | 53.78%  |
| Realtek Semiconductor     | 109       | 30.53%  |
| Broadcom                  | 25        | 7%      |
| Qualcomm Atheros          | 9         | 2.52%   |
| Chelsio Communications    | 4         | 1.12%   |
| Solarflare Communications | 3         | 0.84%   |
| Marvell Technology Group  | 3         | 0.84%   |
| Nvidia                    | 2         | 0.56%   |
| IBM                       | 2         | 0.56%   |
| 3Com                      | 2         | 0.56%   |
| QLogic                    | 1         | 0.28%   |
| JMicron Technology        | 1         | 0.28%   |
| Insyde Software           | 1         | 0.28%   |
| Google                    | 1         | 0.28%   |
| D-Link System             | 1         | 0.28%   |
| Apple                     | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 92        | 22.22%  |
| Intel I211 Gigabit Network Connection                                         | 28        | 6.76%   |
| Intel 82574L Gigabit Network Connection                                       | 23        | 5.56%   |
| Intel Ethernet Connection I217-LM                                             | 20        | 4.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 19        | 4.59%   |
| Intel I350 Gigabit Network Connection                                         | 15        | 3.62%   |
| Intel I210 Gigabit Network Connection                                         | 15        | 3.62%   |
| Intel 82576 Gigabit Network Connection                                        | 10        | 2.42%   |
| Intel 82583V Gigabit Network Connection                                       | 9         | 2.17%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9         | 2.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8         | 1.93%   |
| Intel 82580 Gigabit Network Connection                                        | 8         | 1.93%   |
| Intel Ethernet Connection I219-LM                                             | 7         | 1.69%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 7         | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5         | 1.21%   |
| Intel Ethernet Controller I225-V                                              | 5         | 1.21%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5         | 1.21%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 5         | 1.21%   |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 0.97%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 0.97%   |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 0.97%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3         | 0.72%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 3         | 0.72%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3         | 0.72%   |
| Intel Ethernet Connection (3) I218-V                                          | 3         | 0.72%   |
| Intel 82575GB Gigabit Network Connection                                      | 3         | 0.72%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3         | 0.72%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3         | 0.72%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 3         | 0.72%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3         | 0.72%   |
| Solarflare SFC9020 10G Ethernet Controller                                    | 2         | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2         | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 2         | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 0.48%   |
| Nvidia MCP79 Ethernet                                                         | 2         | 0.48%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 2         | 0.48%   |
| Intel Ethernet Controller X550                                                | 2         | 0.48%   |
| Intel Ethernet Connection I354                                                | 2         | 0.48%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 293       | 71.12%  |
| WiFi     | 109       | 26.46%  |
| Unknown  | 9         | 2.18%   |
| Modem    | 1         | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 271       | 80.9%   |
| WiFi     | 64        | 19.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 117       | 38.36%  |
| 3     | 45        | 14.75%  |
| 1     | 42        | 13.77%  |
| 4     | 40        | 13.11%  |
| 5     | 23        | 7.54%   |
| 6     | 20        | 6.56%   |
| 7     | 6         | 1.97%   |
| 8     | 5         | 1.64%   |
| 9     | 2         | 0.66%   |
| 0     | 2         | 0.66%   |
| 14    | 1         | 0.33%   |
| 12    | 1         | 0.33%   |
| 10    | 1         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 273       | 88.35%  |
| Yes  | 36        | 11.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 58.44%  |
| Cambridge Silicon Radio         | 6         | 7.79%   |
| Broadcom                        | 4         | 5.19%   |
| Realtek Semiconductor           | 3         | 3.9%    |
| Qualcomm Atheros Communications | 3         | 3.9%    |
| IMC Networks                    | 3         | 3.9%    |
| Foxconn / Hon Hai               | 3         | 3.9%    |
| Apple                           | 3         | 3.9%    |
| Alps Electric                   | 2         | 2.6%    |
| Toshiba                         | 1         | 1.3%    |
| MediaTek                        | 1         | 1.3%    |
| Lite-On Technology              | 1         | 1.3%    |
| Hewlett-Packard                 | 1         | 1.3%    |
| ASUSTek Computer                | 1         | 1.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 26        | 33.77%  |
| Intel AX200 Bluetooth                                       | 6         | 7.79%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 6         | 7.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 6.49%   |
| Intel AX201 Bluetooth                                       | 4         | 5.19%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 3.9%    |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 3.9%    |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 2.6%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 2.6%    |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 2.6%    |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 1.3%    |
| Realtek RTL8723A Bluetooth                                  | 1         | 1.3%    |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.3%    |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 1.3%    |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.3%    |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 1.3%    |
| MediaTek Wireless_Device                                    | 1         | 1.3%    |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 1.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.3%    |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 1         | 1.3%    |
| IMC Networks Bluetooth                                      | 1         | 1.3%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 1.3%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.3%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 1.3%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 1.3%    |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 1.3%    |
| Apple Bluetooth Host Controller                             | 1         | 1.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 191       | 67.73%  |
| AMD                 | 42        | 14.89%  |
| Nvidia              | 35        | 12.41%  |
| C-Media Electronics | 4         | 1.42%   |
| Logitech            | 3         | 1.06%   |
| Texas Instruments   | 2         | 0.71%   |
| Yamaha              | 1         | 0.35%   |
| XMOS                | 1         | 0.35%   |
| SteelSeries ApS     | 1         | 0.35%   |
| KTMicro             | 1         | 0.35%   |
| Creative Labs       | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 27        | 7.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 25        | 7.25%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 4.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 15        | 4.35%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 3.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 3.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 3.19%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 2.61%   |
| Intel 200 Series PCH HD Audio                                                                     | 9         | 2.61%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 2.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 2.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 2.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 2.32%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 7         | 2.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.74%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 1.74%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 1.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.45%   |
| Intel Jasper Lake HD Audio                                                                        | 5         | 1.45%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5         | 1.45%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5         | 1.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.16%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4         | 1.16%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.87%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.87%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 0.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 0.87%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 0.87%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 0.87%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.58%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.58%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.58%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.58%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.58%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 60        | 18.35%  |
| SK hynix            | 59        | 18.04%  |
| Kingston            | 46        | 14.07%  |
| Unknown             | 35        | 10.7%   |
| Corsair             | 22        | 6.73%   |
| Micron Technology   | 21        | 6.42%   |
| G.Skill             | 17        | 5.2%    |
| Crucial             | 17        | 5.2%    |
| Unknown (ABCD)      | 6         | 1.83%   |
| Ramaxel Technology  | 5         | 1.53%   |
| Apacer              | 5         | 1.53%   |
| Unknown             | 5         | 1.53%   |
| Team                | 4         | 1.22%   |
| A-DATA Technology   | 4         | 1.22%   |
| Unknown (0x0C26)    | 3         | 0.92%   |
| Timetec             | 3         | 0.92%   |
| Patriot             | 3         | 0.92%   |
| Nanya Technology    | 3         | 0.92%   |
| OCZ                 | 2         | 0.61%   |
| V-Color             | 1         | 0.31%   |
| Unknown (0x0DD5)    | 1         | 0.31%   |
| Transcend           | 1         | 0.31%   |
| Toshiba             | 1         | 0.31%   |
| Teikon              | 1         | 0.31%   |
| Cors                | 1         | 0.31%   |
| Avant               | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 6         | 1.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 5         | 1.42%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s               | 5         | 1.42%   |
| Unknown                                                           | 5         | 1.42%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 4         | 1.14%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 4         | 1.14%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 4         | 1.14%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s               | 4         | 1.14%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s           | 4         | 1.14%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 3         | 0.85%   |
| SK hynix RAM HMT351U7BFR8A-H9 4GB DIMM DDR3 1333MT/s              | 3         | 0.85%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s           | 3         | 0.85%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s               | 3         | 0.85%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 2         | 0.57%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 2         | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                         | 2         | 0.57%   |
| Unknown RAM Module 1GB SODIMM DDR2                                | 2         | 0.57%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 0.57%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 0.57%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 0.57%   |
| SK hynix RAM HMT151R7BFR4C-H9 4GB DIMM DDR3 1333MT/s              | 2         | 0.57%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s            | 2         | 0.57%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s              | 2         | 0.57%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s              | 2         | 0.57%   |
| SK hynix RAM HMA451R7AFR8N-TF 4GB RIMM DDR4 2133MT/s              | 2         | 0.57%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s             | 2         | 0.57%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 0.57%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s               | 2         | 0.57%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 2         | 0.57%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 2         | 0.57%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM DDR3 1600MT/s              | 2         | 0.57%   |
| Micron RAM 9ASF51272PZ-2G1A2 4GB RIMM DDR4 2133MT/s               | 2         | 0.57%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s               | 2         | 0.57%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s           | 2         | 0.57%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s               | 2         | 0.57%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s                | 2         | 0.57%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s               | 2         | 0.57%   |
| Corsair RAM CMV8GX3M1A1333C9 8GB DIMM DDR3 1333MT/s               | 2         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 151       | 53.17%  |
| DDR4    | 95        | 33.45%  |
| DDR2    | 11        | 3.87%   |
| Unknown | 10        | 3.52%   |
| SDRAM   | 7         | 2.46%   |
| LPDDR4  | 7         | 2.46%   |
| DDR     | 2         | 0.7%    |
| LPDDR3  | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 158       | 56.43%  |
| SODIMM       | 114       | 40.71%  |
| RIMM         | 3         | 1.07%   |
| Row Of Chips | 2         | 0.71%   |
| Chip         | 2         | 0.71%   |
| FB-DIMM      | 1         | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 114       | 37.13%  |
| 8192  | 102       | 33.22%  |
| 16384 | 41        | 13.36%  |
| 2048  | 39        | 12.7%   |
| 1024  | 8         | 2.61%   |
| 512   | 2         | 0.65%   |
| 32768 | 1         | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 100       | 32.89%  |
| 1333    | 44        | 14.47%  |
| 2400    | 35        | 11.51%  |
| 2667    | 24        | 7.89%   |
| 2133    | 22        | 7.24%   |
| 3200    | 18        | 5.92%   |
| Unknown | 10        | 3.29%   |
| 1067    | 9         | 2.96%   |
| 800     | 7         | 2.3%    |
| 2666    | 6         | 1.97%   |
| 667     | 6         | 1.97%   |
| 1334    | 5         | 1.64%   |
| 3600    | 3         | 0.99%   |
| 1867    | 3         | 0.99%   |
| 1066    | 3         | 0.99%   |
| 1866    | 2         | 0.66%   |
| 400     | 2         | 0.66%   |
| 5200    | 1         | 0.33%   |
| 3400    | 1         | 0.33%   |
| 3000    | 1         | 0.33%   |
| 533     | 1         | 0.33%   |
| 333     | 1         | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 50%     |
| Samsung Electronics | 1         | 25%     |
| Brother Industries  | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 25%     |
| HP LaserJet 2200                   | 1         | 25%     |
| HP Color LaserJet CP1215           | 1         | 25%     |
| Brother HL-L5200DW series          | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 16        | 35.56%  |
| Acer                          | 6         | 13.33%  |
| Microdia                      | 5         | 11.11%  |
| Realtek Semiconductor         | 4         | 8.89%   |
| Lite-On Technology            | 3         | 6.67%   |
| IMC Networks                  | 3         | 6.67%   |
| Syntek                        | 2         | 4.44%   |
| Sunplus Innovation Technology | 2         | 4.44%   |
| Logitech                      | 2         | 4.44%   |
| Quanta                        | 1         | 2.22%   |
| Lenovo                        | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Acer Integrated Camera                   | 4         | 8.89%   |
| Lite-On Integrated Camera                | 3         | 6.67%   |
| Chicony integrated camera                | 3         | 6.67%   |
| Chicony HD Webcam                        | 3         | 6.67%   |
| Syntek Lenovo EasyCamera                 | 1         | 2.22%   |
| Syntek ASUS USB2.0 camera                | 1         | 2.22%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 2.22%   |
| Sunplus ASUS Webcam                      | 1         | 2.22%   |
| Realtek Realtek USB2.0 PC Camera         | 1         | 2.22%   |
| Realtek Realtek PC Camera                | 1         | 2.22%   |
| Realtek Integrated Webcam HD             | 1         | 2.22%   |
| Realtek Integrated Webcam                | 1         | 2.22%   |
| Quanta USB2.0 HD UVC WebCam              | 1         | 2.22%   |
| Microdia Sonix USB 2.0 Camera            | 1         | 2.22%   |
| Microdia Laptop_Integrated_Webcam_2M     | 1         | 2.22%   |
| Microdia JOYACCESS JA-Webcam             | 1         | 2.22%   |
| Microdia Integrated Webcam HD            | 1         | 2.22%   |
| Microdia Integrated Webcam               | 1         | 2.22%   |
| Logitech Webcam C310                     | 1         | 2.22%   |
| Logitech HD Pro Webcam C920              | 1         | 2.22%   |
| Lenovo Integrated Webcam [R5U877]        | 1         | 2.22%   |
| IMC Networks UVC VGA Webcam              | 1         | 2.22%   |
| IMC Networks Integrated Webcam           | 1         | 2.22%   |
| IMC Networks Integrated Camera           | 1         | 2.22%   |
| Chicony WebCam                           | 1         | 2.22%   |
| Chicony VGA 24fps UVC Webcam             | 1         | 2.22%   |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 2.22%   |
| Chicony Sonix ST50220 USB Video Camera   | 1         | 2.22%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 2.22%   |
| Chicony Integrated Camera [ThinkPad]     | 1         | 2.22%   |
| Chicony HP HD Camera                     | 1         | 2.22%   |
| Chicony HP 0.3MP Webcam                  | 1         | 2.22%   |
| Chicony FJ Camera                        | 1         | 2.22%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 1         | 2.22%   |
| Acer ThinkPad P50 Integrated Camera      | 1         | 2.22%   |
| Acer SunplusIT Integrated Camera         | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 50%     |
| Upek                  | 2         | 16.67%  |
| AuthenTec             | 2         | 16.67%  |
| Synaptics             | 1         | 8.33%   |
| LighTuning Technology | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 25%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 16.67%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 8.33%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                        | 1         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 8.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 8.33%   |
| AuthenTec AuthenTec Inc. AES2660                       | 1         | 8.33%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 8.33%   |

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
| 1     | 148       | 47.28%  |
| 0     | 87        | 27.8%   |
| 2     | 51        | 16.29%  |
| 3     | 20        | 6.39%   |
| 4     | 5         | 1.6%    |
| 5     | 2         | 0.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 190       | 63.76%  |
| Bluetooth                | 28        | 9.4%    |
| Net/wireless             | 20        | 6.71%   |
| Card reader              | 17        | 5.7%    |
| Firewire controller      | 12        | 4.03%   |
| Fingerprint reader       | 8         | 2.68%   |
| Sound                    | 6         | 2.01%   |
| Net/ethernet             | 6         | 2.01%   |
| Network                  | 5         | 1.68%   |
| Storage                  | 2         | 0.67%   |
| Graphics card            | 2         | 0.67%   |
| Storage/raid             | 1         | 0.34%   |
| Storage/ata              | 1         | 0.34%   |

