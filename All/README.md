BSD - Tested Hardware & Statistics
----------------------------------

A project to collect tested hardware configurations for BSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Desktop/README.md) and [notebooks](/Notebook/README.md).

OS-specific reports: [FreeBSD](/Dist/FreeBSD), [GhostBSD](/Dist/GhostBSD), [helloSystem](/Dist/helloSystem), [NetBSD](/Dist/NetBSD), [NomadBSD](/Dist/NomadBSD), [OpenBSD](/Dist/OpenBSD), [OPNsense](/Dist/OPNsense), [pfSense](/Dist/pfSense), [TrueNAS](/Dist/TrueNAS).

This report is for real hardware. Report for virtual hardware: [TestCoverage_VE](https://github.com/bsdhw/TestCoverage_VE)

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

Total: 13792

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [d03f9c19f8](https://bsd-hardware.info/?probe=d03f9c19f8) | Jan 23, 2023 |
| AAEON Tech... | PCM-LN02 V2.0               | Desktop     | [046b7464b9](https://bsd-hardware.info/?probe=046b7464b9) | Jan 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [840145eb80](https://bsd-hardware.info/?probe=840145eb80) | Jan 23, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [8b137bca84](https://bsd-hardware.info/?probe=8b137bca84) | Jan 23, 2023 |
| Timi          | TM1607                      | Notebook    | [7636a0ef8f](https://bsd-hardware.info/?probe=7636a0ef8f) | Jan 23, 2023 |
| Timi          | TM1607                      | Notebook    | [1ca46404a1](https://bsd-hardware.info/?probe=1ca46404a1) | Jan 23, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [771f2c4d96](https://bsd-hardware.info/?probe=771f2c4d96) | Jan 23, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [881e97e41c](https://bsd-hardware.info/?probe=881e97e41c) | Jan 23, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [006553f965](https://bsd-hardware.info/?probe=006553f965) | Jan 23, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [4b3a05fc2a](https://bsd-hardware.info/?probe=4b3a05fc2a) | Jan 22, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [6dc0fddda1](https://bsd-hardware.info/?probe=6dc0fddda1) | Jan 22, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [a271d3c547](https://bsd-hardware.info/?probe=a271d3c547) | Jan 22, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [d2652b76cf](https://bsd-hardware.info/?probe=d2652b76cf) | Jan 22, 2023 |
| Intel         | NUC5i7RYB H73774-101        | Mini pc     | [9954516f1a](https://bsd-hardware.info/?probe=9954516f1a) | Jan 22, 2023 |
| ASUSTek       | Q405UA                      | Convertible | [6662cab62d](https://bsd-hardware.info/?probe=6662cab62d) | Jan 22, 2023 |
| ASUSTek       | Q405UA                      | Convertible | [2b94c3efae](https://bsd-hardware.info/?probe=2b94c3efae) | Jan 22, 2023 |
| Dell          | Latitude E6400              | Notebook    | [dcc804a61f](https://bsd-hardware.info/?probe=dcc804a61f) | Jan 22, 2023 |
| Dell          | Latitude E6400              | Notebook    | [9dd8d0184f](https://bsd-hardware.info/?probe=9dd8d0184f) | Jan 22, 2023 |
| AWOW          | AK50                        | Desktop     | [8c983f91e4](https://bsd-hardware.info/?probe=8c983f91e4) | Jan 22, 2023 |
| Lenovo        | ThinkPad T440p 20AN007FG... | Notebook    | [0883806434](https://bsd-hardware.info/?probe=0883806434) | Jan 22, 2023 |
| Dell          | 03KWTV A02                  | Desktop     | [28088f7e94](https://bsd-hardware.info/?probe=28088f7e94) | Jan 22, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b938a15d41](https://bsd-hardware.info/?probe=b938a15d41) | Jan 22, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [0e9d5e53b9](https://bsd-hardware.info/?probe=0e9d5e53b9) | Jan 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0041MX     | Notebook    | [c27f1f53f2](https://bsd-hardware.info/?probe=c27f1f53f2) | Jan 22, 2023 |
| PC Engines    | APU2                        | Desktop     | [658569ae16](https://bsd-hardware.info/?probe=658569ae16) | Jan 22, 2023 |
| Dell          | 0R5KP9 A04                  | Server      | [7b811598b5](https://bsd-hardware.info/?probe=7b811598b5) | Jan 22, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [26d1d923d6](https://bsd-hardware.info/?probe=26d1d923d6) | Jan 22, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0bbc074f1c](https://bsd-hardware.info/?probe=0bbc074f1c) | Jan 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [28d8d82d34](https://bsd-hardware.info/?probe=28d8d82d34) | Jan 22, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7bd5f0c2e9](https://bsd-hardware.info/?probe=7bd5f0c2e9) | Jan 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [8511097117](https://bsd-hardware.info/?probe=8511097117) | Jan 22, 2023 |
| Intel         | H61                         | Desktop     | [7faeca8300](https://bsd-hardware.info/?probe=7faeca8300) | Jan 22, 2023 |
| Panasonic     | CF-C1BWFAZ1M                | Notebook    | [d129d929ac](https://bsd-hardware.info/?probe=d129d929ac) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [ab38c51298](https://bsd-hardware.info/?probe=ab38c51298) | Jan 22, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [76840aba40](https://bsd-hardware.info/?probe=76840aba40) | Jan 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [d5d2ce1b39](https://bsd-hardware.info/?probe=d5d2ce1b39) | Jan 22, 2023 |
| Dell          | 0H723K A05                  | Server      | [561152d95d](https://bsd-hardware.info/?probe=561152d95d) | Jan 22, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [a17d96dde0](https://bsd-hardware.info/?probe=a17d96dde0) | Jan 22, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [c9d93a7c6f](https://bsd-hardware.info/?probe=c9d93a7c6f) | Jan 21, 2023 |
| ZOTAC         | ZBOX-ID92/ZBOX-IQ01         | Mini pc     | [d22d8ea874](https://bsd-hardware.info/?probe=d22d8ea874) | Jan 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [0bbf3bdc00](https://bsd-hardware.info/?probe=0bbf3bdc00) | Jan 21, 2023 |
| HP            | 1825                        | Desktop     | [2705218636](https://bsd-hardware.info/?probe=2705218636) | Jan 21, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [8ae819f673](https://bsd-hardware.info/?probe=8ae819f673) | Jan 21, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [6b1a9b8d00](https://bsd-hardware.info/?probe=6b1a9b8d00) | Jan 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [8956f4503e](https://bsd-hardware.info/?probe=8956f4503e) | Jan 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [59c83cb9ee](https://bsd-hardware.info/?probe=59c83cb9ee) | Jan 21, 2023 |
| Fujitsu       | D3243-S1 S26361-D3243-S1    | Desktop     | [d69c3cae4c](https://bsd-hardware.info/?probe=d69c3cae4c) | Jan 21, 2023 |
| PC Engines    | APU2                        | Desktop     | [172844bd8b](https://bsd-hardware.info/?probe=172844bd8b) | Jan 21, 2023 |
| Datto         | 1000                        | Notebook    | [3d2880dd30](https://bsd-hardware.info/?probe=3d2880dd30) | Jan 21, 2023 |
| ASUSTek       | EB1035                      | All in one  | [7e39e23232](https://bsd-hardware.info/?probe=7e39e23232) | Jan 21, 2023 |
| AZW           | Green G1                    | Desktop     | [80498a4090](https://bsd-hardware.info/?probe=80498a4090) | Jan 21, 2023 |
| Lenovo        | SDK0J40705 WIN 342503995... | Desktop     | [0dc2013a9f](https://bsd-hardware.info/?probe=0dc2013a9f) | Jan 21, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | Notebook    | [3497ee2fcc](https://bsd-hardware.info/?probe=3497ee2fcc) | Jan 21, 2023 |
| AZW           | Green G1                    | Desktop     | [0c84e93ba7](https://bsd-hardware.info/?probe=0c84e93ba7) | Jan 21, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [e6873fe42f](https://bsd-hardware.info/?probe=e6873fe42f) | Jan 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [14089c4ab4](https://bsd-hardware.info/?probe=14089c4ab4) | Jan 21, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [b0fe0783d5](https://bsd-hardware.info/?probe=b0fe0783d5) | Jan 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1d040b684b](https://bsd-hardware.info/?probe=1d040b684b) | Jan 21, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [495563926c](https://bsd-hardware.info/?probe=495563926c) | Jan 21, 2023 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [7a21bfbfb9](https://bsd-hardware.info/?probe=7a21bfbfb9) | Jan 20, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e6ad419f5e](https://bsd-hardware.info/?probe=e6ad419f5e) | Jan 20, 2023 |
| Gigabyte      | F2A75M-HD2                  | Desktop     | [4770b980d6](https://bsd-hardware.info/?probe=4770b980d6) | Jan 20, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [f862df1689](https://bsd-hardware.info/?probe=f862df1689) | Jan 20, 2023 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [629c2e1a21](https://bsd-hardware.info/?probe=629c2e1a21) | Jan 20, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [6b331ff558](https://bsd-hardware.info/?probe=6b331ff558) | Jan 20, 2023 |
| ASUSTek       | PRO A520M-C                 | Desktop     | [bebcd1a008](https://bsd-hardware.info/?probe=bebcd1a008) | Jan 20, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [a4688e4059](https://bsd-hardware.info/?probe=a4688e4059) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2ea8c1d1a4](https://bsd-hardware.info/?probe=2ea8c1d1a4) | Jan 20, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [0d3e0df928](https://bsd-hardware.info/?probe=0d3e0df928) | Jan 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d4018ae0f3](https://bsd-hardware.info/?probe=d4018ae0f3) | Jan 20, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [4bcc8752f4](https://bsd-hardware.info/?probe=4bcc8752f4) | Jan 20, 2023 |
| Dell          | 0R5KP9 A04                  | Server      | [03a26b8a34](https://bsd-hardware.info/?probe=03a26b8a34) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [32ebc1c99d](https://bsd-hardware.info/?probe=32ebc1c99d) | Jan 20, 2023 |
| Unknown       | AMD-GX3                     | Desktop     | [a38ff8331a](https://bsd-hardware.info/?probe=a38ff8331a) | Jan 20, 2023 |
| Sophos        | SG                          | Firewall    | [324882f1d6](https://bsd-hardware.info/?probe=324882f1d6) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [3afbfc6cea](https://bsd-hardware.info/?probe=3afbfc6cea) | Jan 20, 2023 |
| Unknown       | YL-SKUL6                    | Desktop     | [ef4abfe322](https://bsd-hardware.info/?probe=ef4abfe322) | Jan 20, 2023 |
| Dell          | 04415J A00                  | Mini pc     | [8ffe26845d](https://bsd-hardware.info/?probe=8ffe26845d) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [e13627df1a](https://bsd-hardware.info/?probe=e13627df1a) | Jan 20, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [fa42e2faf7](https://bsd-hardware.info/?probe=fa42e2faf7) | Jan 20, 2023 |
| Cisco         | ASA5512 A0                  | Desktop     | [9cd4409fda](https://bsd-hardware.info/?probe=9cd4409fda) | Jan 20, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [142b3ad8d6](https://bsd-hardware.info/?probe=142b3ad8d6) | Jan 20, 2023 |
| Unknown       | PICO PC                     | Desktop     | [9e20d7dbbc](https://bsd-hardware.info/?probe=9e20d7dbbc) | Jan 20, 2023 |
| Unknown       | YL-E3845L4-V2               | Desktop     | [d93eb933f1](https://bsd-hardware.info/?probe=d93eb933f1) | Jan 20, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [47742b68d5](https://bsd-hardware.info/?probe=47742b68d5) | Jan 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ba99fba661](https://bsd-hardware.info/?probe=ba99fba661) | Jan 19, 2023 |
| Acer          | TravelMate B311-31          | Notebook    | [dc3f072645](https://bsd-hardware.info/?probe=dc3f072645) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [32477354bc](https://bsd-hardware.info/?probe=32477354bc) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [62bad8c9f8](https://bsd-hardware.info/?probe=62bad8c9f8) | Jan 19, 2023 |
| HP            | ProLiant DL120 Gen9         | Server      | [7df2c509dd](https://bsd-hardware.info/?probe=7df2c509dd) | Jan 19, 2023 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [48206a7d4a](https://bsd-hardware.info/?probe=48206a7d4a) | Jan 19, 2023 |
| Sophos        | SG                          | Firewall    | [f10f04a5b1](https://bsd-hardware.info/?probe=f10f04a5b1) | Jan 19, 2023 |
| Sophos        | SG                          | Firewall    | [9275bbae4e](https://bsd-hardware.info/?probe=9275bbae4e) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [35e269ef1c](https://bsd-hardware.info/?probe=35e269ef1c) | Jan 19, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [f7efd8c7d2](https://bsd-hardware.info/?probe=f7efd8c7d2) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [28bb1a7282](https://bsd-hardware.info/?probe=28bb1a7282) | Jan 19, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [488416a10c](https://bsd-hardware.info/?probe=488416a10c) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [6aa648ba82](https://bsd-hardware.info/?probe=6aa648ba82) | Jan 19, 2023 |
| Dell          | Precision 5540              | Notebook    | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [8580d62bf3](https://bsd-hardware.info/?probe=8580d62bf3) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [b528c0bbe3](https://bsd-hardware.info/?probe=b528c0bbe3) | Jan 18, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [b9de543167](https://bsd-hardware.info/?probe=b9de543167) | Jan 18, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [c3281eb186](https://bsd-hardware.info/?probe=c3281eb186) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [11948a0ab1](https://bsd-hardware.info/?probe=11948a0ab1) | Jan 18, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [fb9e5fe3cf](https://bsd-hardware.info/?probe=fb9e5fe3cf) | Jan 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [739cc6e5ac](https://bsd-hardware.info/?probe=739cc6e5ac) | Jan 18, 2023 |
| HP            | 17E2                        | Mini pc     | [ff98f389b1](https://bsd-hardware.info/?probe=ff98f389b1) | Jan 18, 2023 |
| ZOTAC         | ZBOX-CI325NANO              | Mini pc     | [67a09fbbab](https://bsd-hardware.info/?probe=67a09fbbab) | Jan 18, 2023 |
| Lenovo        | H30-05 90BJ0085SP           | Desktop     | [1424b3641c](https://bsd-hardware.info/?probe=1424b3641c) | Jan 18, 2023 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [ed566c9a5c](https://bsd-hardware.info/?probe=ed566c9a5c) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [f7de27b0ca](https://bsd-hardware.info/?probe=f7de27b0ca) | Jan 18, 2023 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [cfb839082b](https://bsd-hardware.info/?probe=cfb839082b) | Jan 18, 2023 |
| Lenovo        | H30-05 90BJ0085SP           | Desktop     | [d491694079](https://bsd-hardware.info/?probe=d491694079) | Jan 18, 2023 |
| Sophos        | UTM                         | Firewall    | [4b0eace553](https://bsd-hardware.info/?probe=4b0eace553) | Jan 18, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [d9f16ef94b](https://bsd-hardware.info/?probe=d9f16ef94b) | Jan 18, 2023 |
| Datto         | Unknown                     | Notebook    | [0b70f2b2b0](https://bsd-hardware.info/?probe=0b70f2b2b0) | Jan 18, 2023 |
| HP            | 83F2                        | Desktop     | [a7230c1af5](https://bsd-hardware.info/?probe=a7230c1af5) | Jan 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [cbdab56490](https://bsd-hardware.info/?probe=cbdab56490) | Jan 18, 2023 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [c5d050f0d6](https://bsd-hardware.info/?probe=c5d050f0d6) | Jan 18, 2023 |
| Datto         | 1000                        | Notebook    | [c2abd24ed6](https://bsd-hardware.info/?probe=c2abd24ed6) | Jan 18, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [f929122d8a](https://bsd-hardware.info/?probe=f929122d8a) | Jan 18, 2023 |
| Intel         | H81U                        | Notebook    | [08d2539153](https://bsd-hardware.info/?probe=08d2539153) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [9eee9cc526](https://bsd-hardware.info/?probe=9eee9cc526) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [46178567ff](https://bsd-hardware.info/?probe=46178567ff) | Jan 18, 2023 |
| Intel         | DH67BL AAG10189-206         | Desktop     | [37ae895d75](https://bsd-hardware.info/?probe=37ae895d75) | Jan 17, 2023 |
| Intel         | DQ45CB AAE30148-302         | Desktop     | [349da05405](https://bsd-hardware.info/?probe=349da05405) | Jan 17, 2023 |
| Dell          | PowerEdge R710              | Desktop     | [720e99b25e](https://bsd-hardware.info/?probe=720e99b25e) | Jan 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [4ccf28379a](https://bsd-hardware.info/?probe=4ccf28379a) | Jan 17, 2023 |
| Intel         | H81U                        | Notebook    | [fe47328dd0](https://bsd-hardware.info/?probe=fe47328dd0) | Jan 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [dcdf55f06e](https://bsd-hardware.info/?probe=dcdf55f06e) | Jan 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [22015084fc](https://bsd-hardware.info/?probe=22015084fc) | Jan 17, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [65ce4b26be](https://bsd-hardware.info/?probe=65ce4b26be) | Jan 17, 2023 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [6bb5667269](https://bsd-hardware.info/?probe=6bb5667269) | Jan 17, 2023 |
| Wortmann      | terra MiniPC                | Desktop     | [be22193265](https://bsd-hardware.info/?probe=be22193265) | Jan 17, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d8007634f3](https://bsd-hardware.info/?probe=d8007634f3) | Jan 17, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [11943e270e](https://bsd-hardware.info/?probe=11943e270e) | Jan 17, 2023 |
| HP            | 1998                        | Desktop     | [6c36e5e82e](https://bsd-hardware.info/?probe=6c36e5e82e) | Jan 17, 2023 |
| Lenovo        | B40-70 80F30005BR           | Notebook    | [17333d88cf](https://bsd-hardware.info/?probe=17333d88cf) | Jan 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [63689d3fbc](https://bsd-hardware.info/?probe=63689d3fbc) | Jan 17, 2023 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [d0e2e85346](https://bsd-hardware.info/?probe=d0e2e85346) | Jan 17, 2023 |
| MSI           | MS-9897                     | Desktop     | [8aa91d17fa](https://bsd-hardware.info/?probe=8aa91d17fa) | Jan 17, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [52078a2cab](https://bsd-hardware.info/?probe=52078a2cab) | Jan 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [0049fd4cfc](https://bsd-hardware.info/?probe=0049fd4cfc) | Jan 17, 2023 |
| MSI           | MS-9897                     | Desktop     | [0ccc361bd9](https://bsd-hardware.info/?probe=0ccc361bd9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [78327c664e](https://bsd-hardware.info/?probe=78327c664e) | Jan 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9d87e4009a](https://bsd-hardware.info/?probe=9d87e4009a) | Jan 16, 2023 |
| HP            | 83F2                        | Desktop     | [912de3c81d](https://bsd-hardware.info/?probe=912de3c81d) | Jan 16, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [600f7f4f4f](https://bsd-hardware.info/?probe=600f7f4f4f) | Jan 16, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [c1e1ba5558](https://bsd-hardware.info/?probe=c1e1ba5558) | Jan 16, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [78a4659386](https://bsd-hardware.info/?probe=78a4659386) | Jan 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [23d2c64af3](https://bsd-hardware.info/?probe=23d2c64af3) | Jan 16, 2023 |
| Unknown       | QD-CMU01                    | Desktop     | [768a10819b](https://bsd-hardware.info/?probe=768a10819b) | Jan 16, 2023 |
| HP            | 0AECh D                     | Desktop     | [25b7a10166](https://bsd-hardware.info/?probe=25b7a10166) | Jan 16, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [7ef714a7f1](https://bsd-hardware.info/?probe=7ef714a7f1) | Jan 16, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [9994ae920b](https://bsd-hardware.info/?probe=9994ae920b) | Jan 15, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [e98d329586](https://bsd-hardware.info/?probe=e98d329586) | Jan 15, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [86875f01c2](https://bsd-hardware.info/?probe=86875f01c2) | Jan 15, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [e25304fa01](https://bsd-hardware.info/?probe=e25304fa01) | Jan 15, 2023 |
| HP            | Pavilion dv6                | Notebook    | [e42082b1c1](https://bsd-hardware.info/?probe=e42082b1c1) | Jan 15, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [247370372d](https://bsd-hardware.info/?probe=247370372d) | Jan 15, 2023 |
| ASRock        | H610M-HDV/M.2               | Desktop     | [b18c58223f](https://bsd-hardware.info/?probe=b18c58223f) | Jan 15, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [1ef7026e21](https://bsd-hardware.info/?probe=1ef7026e21) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [7488afc0a7](https://bsd-hardware.info/?probe=7488afc0a7) | Jan 15, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Desktop     | [af7a4d3493](https://bsd-hardware.info/?probe=af7a4d3493) | Jan 15, 2023 |
| AZW           | SEi                         | Mini pc     | [362a33bd50](https://bsd-hardware.info/?probe=362a33bd50) | Jan 15, 2023 |
| MSI           | H81M-P33                    | Desktop     | [800b3bc34b](https://bsd-hardware.info/?probe=800b3bc34b) | Jan 15, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [ffbcac312f](https://bsd-hardware.info/?probe=ffbcac312f) | Jan 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [48e7397e29](https://bsd-hardware.info/?probe=48e7397e29) | Jan 15, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [e4c2272546](https://bsd-hardware.info/?probe=e4c2272546) | Jan 15, 2023 |
| Supermicro    | X11SCM-LN8F                 | Server      | [9e102da483](https://bsd-hardware.info/?probe=9e102da483) | Jan 15, 2023 |
| Silicom       | 80300-0214-G01 R311         | Desktop     | [547b59be2b](https://bsd-hardware.info/?probe=547b59be2b) | Jan 15, 2023 |
| HP            | 8299                        | Desktop     | [d7afab37f3](https://bsd-hardware.info/?probe=d7afab37f3) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [8c44d6309f](https://bsd-hardware.info/?probe=8c44d6309f) | Jan 15, 2023 |
| HP            | 8299                        | Desktop     | [7a5bbc7546](https://bsd-hardware.info/?probe=7a5bbc7546) | Jan 15, 2023 |
| Dell          | 0C2KJT A00                  | Desktop     | [9364056dac](https://bsd-hardware.info/?probe=9364056dac) | Jan 15, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [a975d143b8](https://bsd-hardware.info/?probe=a975d143b8) | Jan 15, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [624bfd62b5](https://bsd-hardware.info/?probe=624bfd62b5) | Jan 15, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [05cc17947c](https://bsd-hardware.info/?probe=05cc17947c) | Jan 15, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [9c70b7e4e1](https://bsd-hardware.info/?probe=9c70b7e4e1) | Jan 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [c85b254f84](https://bsd-hardware.info/?probe=c85b254f84) | Jan 15, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [8aebf3b22a](https://bsd-hardware.info/?probe=8aebf3b22a) | Jan 15, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [ad094a458b](https://bsd-hardware.info/?probe=ad094a458b) | Jan 14, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [c2100f1789](https://bsd-hardware.info/?probe=c2100f1789) | Jan 14, 2023 |
| Shuttle       | FS77U                       | Desktop     | [4598a5f9d1](https://bsd-hardware.info/?probe=4598a5f9d1) | Jan 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [ced6c29193](https://bsd-hardware.info/?probe=ced6c29193) | Jan 14, 2023 |
| HP            | 1998                        | Desktop     | [789ecdb3ab](https://bsd-hardware.info/?probe=789ecdb3ab) | Jan 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3d2101dc79](https://bsd-hardware.info/?probe=3d2101dc79) | Jan 14, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [39e071ee73](https://bsd-hardware.info/?probe=39e071ee73) | Jan 14, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [17d73c4d40](https://bsd-hardware.info/?probe=17d73c4d40) | Jan 14, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ad7329411a](https://bsd-hardware.info/?probe=ad7329411a) | Jan 14, 2023 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [92525fd54a](https://bsd-hardware.info/?probe=92525fd54a) | Jan 14, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [035f9afc5d](https://bsd-hardware.info/?probe=035f9afc5d) | Jan 14, 2023 |
| Dell          | OptiPlex 3040               | Desktop     | [07abf8e8b2](https://bsd-hardware.info/?probe=07abf8e8b2) | Jan 14, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [9ded9cc6ec](https://bsd-hardware.info/?probe=9ded9cc6ec) | Jan 14, 2023 |
| HP            | Presario V2000 (EZ621UA#... | Notebook    | [847af5b70f](https://bsd-hardware.info/?probe=847af5b70f) | Jan 14, 2023 |
| Lenovo        | 3102 SDK0J40700 WIN 3258... | Desktop     | [9805fe9459](https://bsd-hardware.info/?probe=9805fe9459) | Jan 13, 2023 |
| Lenovo        | 3102 SDK0J40700 WIN 3258... | Desktop     | [1ec6c3acf2](https://bsd-hardware.info/?probe=1ec6c3acf2) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [e0ed98daee](https://bsd-hardware.info/?probe=e0ed98daee) | Jan 13, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [f8a84dbf0c](https://bsd-hardware.info/?probe=f8a84dbf0c) | Jan 13, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [aca9f07469](https://bsd-hardware.info/?probe=aca9f07469) | Jan 13, 2023 |
| HP            | Pavilion g6                 | Notebook    | [ceb79702f2](https://bsd-hardware.info/?probe=ceb79702f2) | Jan 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f682e06d06](https://bsd-hardware.info/?probe=f682e06d06) | Jan 13, 2023 |
| HP            | 82A2                        | Desktop     | [4e5c9de512](https://bsd-hardware.info/?probe=4e5c9de512) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [429659b071](https://bsd-hardware.info/?probe=429659b071) | Jan 13, 2023 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [c4dad014a4](https://bsd-hardware.info/?probe=c4dad014a4) | Jan 13, 2023 |
| HP            | 82A1                        | Desktop     | [2d7d9105f7](https://bsd-hardware.info/?probe=2d7d9105f7) | Jan 13, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [c908dc76a1](https://bsd-hardware.info/?probe=c908dc76a1) | Jan 13, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [c5769bcae3](https://bsd-hardware.info/?probe=c5769bcae3) | Jan 13, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [82f4b97203](https://bsd-hardware.info/?probe=82f4b97203) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [fba3e00878](https://bsd-hardware.info/?probe=fba3e00878) | Jan 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [7ba28d1e6b](https://bsd-hardware.info/?probe=7ba28d1e6b) | Jan 13, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [a18d3bf0ea](https://bsd-hardware.info/?probe=a18d3bf0ea) | Jan 13, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d4846c3ec1](https://bsd-hardware.info/?probe=d4846c3ec1) | Jan 13, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [28e606751f](https://bsd-hardware.info/?probe=28e606751f) | Jan 12, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [f1eb574d26](https://bsd-hardware.info/?probe=f1eb574d26) | Jan 12, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [7cbcb5b513](https://bsd-hardware.info/?probe=7cbcb5b513) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [917972b6ae](https://bsd-hardware.info/?probe=917972b6ae) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [bd60eadfc4](https://bsd-hardware.info/?probe=bd60eadfc4) | Jan 12, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [8c1f6c2733](https://bsd-hardware.info/?probe=8c1f6c2733) | Jan 12, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [95ebd841b2](https://bsd-hardware.info/?probe=95ebd841b2) | Jan 12, 2023 |
| Dell          | 051FJ8 A01                  | Desktop     | [8d5c03acf1](https://bsd-hardware.info/?probe=8d5c03acf1) | Jan 12, 2023 |
| HP            | 82A1                        | Desktop     | [567894a0bb](https://bsd-hardware.info/?probe=567894a0bb) | Jan 12, 2023 |
| Dell          | 0NX642 A11                  | Server      | [f98068785d](https://bsd-hardware.info/?probe=f98068785d) | Jan 12, 2023 |
| Biostar       | A32M2                       | Desktop     | [2540b06338](https://bsd-hardware.info/?probe=2540b06338) | Jan 12, 2023 |
| Lenovo        | 3138                        | Desktop     | [14876c7561](https://bsd-hardware.info/?probe=14876c7561) | Jan 12, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [3126dc27f1](https://bsd-hardware.info/?probe=3126dc27f1) | Jan 12, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [8f3e58f2bc](https://bsd-hardware.info/?probe=8f3e58f2bc) | Jan 12, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [4154475f49](https://bsd-hardware.info/?probe=4154475f49) | Jan 12, 2023 |
| Gigabyte      | Z390 AORUS ELITE            | Desktop     | [53a5719c6a](https://bsd-hardware.info/?probe=53a5719c6a) | Jan 12, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b1b7d05863](https://bsd-hardware.info/?probe=b1b7d05863) | Jan 12, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [619a877f82](https://bsd-hardware.info/?probe=619a877f82) | Jan 12, 2023 |
| PC Engines    | APU3                        | Desktop     | [b080710198](https://bsd-hardware.info/?probe=b080710198) | Jan 12, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [b53cd12326](https://bsd-hardware.info/?probe=b53cd12326) | Jan 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [a21b21b82f](https://bsd-hardware.info/?probe=a21b21b82f) | Jan 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [cb7b02c421](https://bsd-hardware.info/?probe=cb7b02c421) | Jan 11, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [320272bdf1](https://bsd-hardware.info/?probe=320272bdf1) | Jan 11, 2023 |
| Dell          | 0CNCJW A08                  | Server      | [170f3cc041](https://bsd-hardware.info/?probe=170f3cc041) | Jan 11, 2023 |
| Supermicro    | X9SCI/X9SCA                 | Desktop     | [942d966486](https://bsd-hardware.info/?probe=942d966486) | Jan 11, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | Notebook    | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
| HP            | 843B                        | Desktop     | [3e2070415f](https://bsd-hardware.info/?probe=3e2070415f) | Jan 11, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [1008903f65](https://bsd-hardware.info/?probe=1008903f65) | Jan 11, 2023 |
| Dell          | 0CN7CM A06                  | Server      | [33c450dade](https://bsd-hardware.info/?probe=33c450dade) | Jan 11, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [864db5c1f9](https://bsd-hardware.info/?probe=864db5c1f9) | Jan 11, 2023 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [07f15d0014](https://bsd-hardware.info/?probe=07f15d0014) | Jan 11, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [56a5c0de6e](https://bsd-hardware.info/?probe=56a5c0de6e) | Jan 11, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [5eedf320f8](https://bsd-hardware.info/?probe=5eedf320f8) | Jan 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [2293d4960d](https://bsd-hardware.info/?probe=2293d4960d) | Jan 11, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [9b4b30a009](https://bsd-hardware.info/?probe=9b4b30a009) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [41b04a4c81](https://bsd-hardware.info/?probe=41b04a4c81) | Jan 11, 2023 |
| Supermicro    | X11DPi-N                    | Server      | [1f1f11fc1a](https://bsd-hardware.info/?probe=1f1f11fc1a) | Jan 11, 2023 |
| Datto         | 1000                        | Notebook    | [ab1aa0f250](https://bsd-hardware.info/?probe=ab1aa0f250) | Jan 11, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [4c1bb58037](https://bsd-hardware.info/?probe=4c1bb58037) | Jan 11, 2023 |
| HP            | 213D A01                    | Desktop     | [1d30039961](https://bsd-hardware.info/?probe=1d30039961) | Jan 11, 2023 |
| Razer         | Blade Stealth               | Notebook    | [2464314a65](https://bsd-hardware.info/?probe=2464314a65) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [87d79c88e1](https://bsd-hardware.info/?probe=87d79c88e1) | Jan 11, 2023 |
| ASUSTek       | H110I-PLUS D3               | Desktop     | [d0986bd747](https://bsd-hardware.info/?probe=d0986bd747) | Jan 11, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [82e9263905](https://bsd-hardware.info/?probe=82e9263905) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [5386547734](https://bsd-hardware.info/?probe=5386547734) | Jan 11, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [2372c973c8](https://bsd-hardware.info/?probe=2372c973c8) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [9b1707aed4](https://bsd-hardware.info/?probe=9b1707aed4) | Jan 11, 2023 |
| HP            | 1495                        | Desktop     | [4e16deda5a](https://bsd-hardware.info/?probe=4e16deda5a) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [ef45a319a3](https://bsd-hardware.info/?probe=ef45a319a3) | Jan 11, 2023 |
| HP            | 805D                        | Desktop     | [4912ca5cd6](https://bsd-hardware.info/?probe=4912ca5cd6) | Jan 11, 2023 |
| MSI           | H110M-A PRO M2              | Desktop     | [3cf7d4a076](https://bsd-hardware.info/?probe=3cf7d4a076) | Jan 11, 2023 |
| Citrix        | CB-1100                     | Desktop     | [860f27ce64](https://bsd-hardware.info/?probe=860f27ce64) | Jan 11, 2023 |
| HP            | 805D                        | Desktop     | [3da9c57f1f](https://bsd-hardware.info/?probe=3da9c57f1f) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [6e866a006d](https://bsd-hardware.info/?probe=6e866a006d) | Jan 10, 2023 |
| Biostar       | B450NH                      | Desktop     | [c30a71f5ae](https://bsd-hardware.info/?probe=c30a71f5ae) | Jan 10, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [2428fe6bd3](https://bsd-hardware.info/?probe=2428fe6bd3) | Jan 10, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [e4af143188](https://bsd-hardware.info/?probe=e4af143188) | Jan 10, 2023 |
| PC Engines    | APU2                        | Desktop     | [1e65573dfa](https://bsd-hardware.info/?probe=1e65573dfa) | Jan 10, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [0b16265d11](https://bsd-hardware.info/?probe=0b16265d11) | Jan 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6b37f8e185](https://bsd-hardware.info/?probe=6b37f8e185) | Jan 10, 2023 |
| Dell          | 0RC130 A03                  | Server      | [861cdcfef1](https://bsd-hardware.info/?probe=861cdcfef1) | Jan 10, 2023 |
| TYAN Compu... | S5530WG2NR-LE-AKA           | Desktop     | [592af460c5](https://bsd-hardware.info/?probe=592af460c5) | Jan 10, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b37db9216b](https://bsd-hardware.info/?probe=b37db9216b) | Jan 10, 2023 |
| MSI           | H61MA-E35                   | Desktop     | [0dc2a84a69](https://bsd-hardware.info/?probe=0dc2a84a69) | Jan 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [e870cfc473](https://bsd-hardware.info/?probe=e870cfc473) | Jan 10, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [c554f29fbb](https://bsd-hardware.info/?probe=c554f29fbb) | Jan 10, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [9bda43254c](https://bsd-hardware.info/?probe=9bda43254c) | Jan 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [2db049304e](https://bsd-hardware.info/?probe=2db049304e) | Jan 10, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [55bd6297fa](https://bsd-hardware.info/?probe=55bd6297fa) | Jan 10, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [12a726c7f3](https://bsd-hardware.info/?probe=12a726c7f3) | Jan 10, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [a1fb64a2f6](https://bsd-hardware.info/?probe=a1fb64a2f6) | Jan 09, 2023 |
| HP            | 8054                        | Desktop     | [7a7dd659c8](https://bsd-hardware.info/?probe=7a7dd659c8) | Jan 09, 2023 |
| Protectli     | FW6                         | Desktop     | [606f595213](https://bsd-hardware.info/?probe=606f595213) | Jan 09, 2023 |
| Protectli     | FW6                         | Desktop     | [6db7b1f01d](https://bsd-hardware.info/?probe=6db7b1f01d) | Jan 09, 2023 |
| HP            | 2000                        | Notebook    | [7f29899321](https://bsd-hardware.info/?probe=7f29899321) | Jan 09, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [fa583c9b3d](https://bsd-hardware.info/?probe=fa583c9b3d) | Jan 09, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [3a9ec9299c](https://bsd-hardware.info/?probe=3a9ec9299c) | Jan 09, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [1ebacfe659](https://bsd-hardware.info/?probe=1ebacfe659) | Jan 09, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [8def3dc9b2](https://bsd-hardware.info/?probe=8def3dc9b2) | Jan 09, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [76ce0f8e69](https://bsd-hardware.info/?probe=76ce0f8e69) | Jan 09, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [470fa4f28a](https://bsd-hardware.info/?probe=470fa4f28a) | Jan 09, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [e217534893](https://bsd-hardware.info/?probe=e217534893) | Jan 09, 2023 |
| HP            | 8299                        | Desktop     | [f80e368b24](https://bsd-hardware.info/?probe=f80e368b24) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [917b19fbeb](https://bsd-hardware.info/?probe=917b19fbeb) | Jan 09, 2023 |
| HP            | 1998                        | Desktop     | [a523babf97](https://bsd-hardware.info/?probe=a523babf97) | Jan 09, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [17ca08ce40](https://bsd-hardware.info/?probe=17ca08ce40) | Jan 09, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [97b65880b0](https://bsd-hardware.info/?probe=97b65880b0) | Jan 09, 2023 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [c86fd3a6ff](https://bsd-hardware.info/?probe=c86fd3a6ff) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [0714b46000](https://bsd-hardware.info/?probe=0714b46000) | Jan 08, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [549b75038e](https://bsd-hardware.info/?probe=549b75038e) | Jan 08, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5e81493c8d](https://bsd-hardware.info/?probe=5e81493c8d) | Jan 08, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [cc421d80b4](https://bsd-hardware.info/?probe=cc421d80b4) | Jan 08, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [011121c9a5](https://bsd-hardware.info/?probe=011121c9a5) | Jan 08, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [4014cc42ed](https://bsd-hardware.info/?probe=4014cc42ed) | Jan 08, 2023 |
| Lenovo        | ThinkStation D20 415575G    | Desktop     | [0a15d989e3](https://bsd-hardware.info/?probe=0a15d989e3) | Jan 08, 2023 |
| MSI           | X299 PRO                    | Desktop     | [a1f37f69d9](https://bsd-hardware.info/?probe=a1f37f69d9) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [335c3c990a](https://bsd-hardware.info/?probe=335c3c990a) | Jan 08, 2023 |
| Dell          | 03X6X0 A07                  | Server      | [dea6b95d26](https://bsd-hardware.info/?probe=dea6b95d26) | Jan 08, 2023 |
| MSI           | H81M-P33                    | Desktop     | [585a3dc78c](https://bsd-hardware.info/?probe=585a3dc78c) | Jan 08, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1e9d8cc278](https://bsd-hardware.info/?probe=1e9d8cc278) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [490261883c](https://bsd-hardware.info/?probe=490261883c) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [e56cfbdedc](https://bsd-hardware.info/?probe=e56cfbdedc) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [db483e3d46](https://bsd-hardware.info/?probe=db483e3d46) | Jan 08, 2023 |
| CheckPoint    | T-180-00                    | Desktop     | [5cee1fe8d6](https://bsd-hardware.info/?probe=5cee1fe8d6) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [8c877bf16e](https://bsd-hardware.info/?probe=8c877bf16e) | Jan 08, 2023 |
| Protectli     | FW6                         | Desktop     | [6ce513ba71](https://bsd-hardware.info/?probe=6ce513ba71) | Jan 08, 2023 |
| Intel         | SKYBAY                      | Desktop     | [21ed0daf1c](https://bsd-hardware.info/?probe=21ed0daf1c) | Jan 08, 2023 |
| Dell          | 05GD68 A00                  | Desktop     | [c42af2bdc3](https://bsd-hardware.info/?probe=c42af2bdc3) | Jan 08, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [8353660219](https://bsd-hardware.info/?probe=8353660219) | Jan 08, 2023 |
| HP            | 3397                        | Desktop     | [516464d7ef](https://bsd-hardware.info/?probe=516464d7ef) | Jan 08, 2023 |
| Dell          | 0YNVJG A01                  | Desktop     | [8bb9472e6b](https://bsd-hardware.info/?probe=8bb9472e6b) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [bb243a8862](https://bsd-hardware.info/?probe=bb243a8862) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [7b5333020a](https://bsd-hardware.info/?probe=7b5333020a) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [1e3ebde983](https://bsd-hardware.info/?probe=1e3ebde983) | Jan 07, 2023 |
| Supermicro    | Super Server                | Server      | [841407deb7](https://bsd-hardware.info/?probe=841407deb7) | Jan 07, 2023 |
| Dell          | 0W3F1J A00                  | Mini pc     | [eca179a730](https://bsd-hardware.info/?probe=eca179a730) | Jan 07, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [b8f49b8d19](https://bsd-hardware.info/?probe=b8f49b8d19) | Jan 07, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [7e67007744](https://bsd-hardware.info/?probe=7e67007744) | Jan 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [b19ed4597a](https://bsd-hardware.info/?probe=b19ed4597a) | Jan 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [6347de602a](https://bsd-hardware.info/?probe=6347de602a) | Jan 07, 2023 |
| HP            | 8617                        | Desktop     | [2dd1830de4](https://bsd-hardware.info/?probe=2dd1830de4) | Jan 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e87430a40](https://bsd-hardware.info/?probe=7e87430a40) | Jan 07, 2023 |
| HP            | 1998                        | Desktop     | [7b255bc81f](https://bsd-hardware.info/?probe=7b255bc81f) | Jan 06, 2023 |
| HP            | 1998                        | Desktop     | [6aec5e0d99](https://bsd-hardware.info/?probe=6aec5e0d99) | Jan 06, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [44969e64ee](https://bsd-hardware.info/?probe=44969e64ee) | Jan 06, 2023 |
| Lenovo        | ThinkPad T400 2764CTO       | Notebook    | [26f8459193](https://bsd-hardware.info/?probe=26f8459193) | Jan 06, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [ce6ccffb1b](https://bsd-hardware.info/?probe=ce6ccffb1b) | Jan 06, 2023 |
| Sophos        | UTM                         | Firewall    | [6379cce732](https://bsd-hardware.info/?probe=6379cce732) | Jan 06, 2023 |
| YANYU         | R250                        | Desktop     | [7ea489eae6](https://bsd-hardware.info/?probe=7ea489eae6) | Jan 06, 2023 |
| Dell          | 0CN7CM A06                  | Server      | [7a63630a51](https://bsd-hardware.info/?probe=7a63630a51) | Jan 06, 2023 |
| Dell          | 0CN7CM A06                  | Server      | [996218def1](https://bsd-hardware.info/?probe=996218def1) | Jan 06, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [e25da8b10a](https://bsd-hardware.info/?probe=e25da8b10a) | Jan 06, 2023 |
| ASRock        | E3C226D2I                   | Desktop     | [5dfcf8051d](https://bsd-hardware.info/?probe=5dfcf8051d) | Jan 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [fa12ea67eb](https://bsd-hardware.info/?probe=fa12ea67eb) | Jan 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [4e8b83804d](https://bsd-hardware.info/?probe=4e8b83804d) | Jan 06, 2023 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [9c1f7ead89](https://bsd-hardware.info/?probe=9c1f7ead89) | Jan 06, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [92c2e73bd4](https://bsd-hardware.info/?probe=92c2e73bd4) | Jan 06, 2023 |
| Supermicro    | X10DRL-i                    | Server      | [c0fa5bb871](https://bsd-hardware.info/?probe=c0fa5bb871) | Jan 06, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [0d13116822](https://bsd-hardware.info/?probe=0d13116822) | Jan 06, 2023 |
| Dell          | Latitude E6430              | Notebook    | [45f592a66f](https://bsd-hardware.info/?probe=45f592a66f) | Jan 06, 2023 |
| Dell          | 02K9CR A02                  | Desktop     | [3547d6c126](https://bsd-hardware.info/?probe=3547d6c126) | Jan 06, 2023 |
| Deciso        | Netboard A20                | Notebook    | [3ff47d2ce0](https://bsd-hardware.info/?probe=3ff47d2ce0) | Jan 06, 2023 |
| Dell          | Latitude E6430              | Notebook    | [1c4bec17bb](https://bsd-hardware.info/?probe=1c4bec17bb) | Jan 06, 2023 |
| Supermicro    | X10SDV-6C-TLN4F             | Server      | [19dc10e659](https://bsd-hardware.info/?probe=19dc10e659) | Jan 05, 2023 |
| Gigabyte      | MZGLKDP-00                  | Desktop     | [f54f8db756](https://bsd-hardware.info/?probe=f54f8db756) | Jan 05, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [42bfeeda16](https://bsd-hardware.info/?probe=42bfeeda16) | Jan 05, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [379b59f079](https://bsd-hardware.info/?probe=379b59f079) | Jan 05, 2023 |
| Dell          | 0W3F1J A00                  | Mini pc     | [d83b84a6bb](https://bsd-hardware.info/?probe=d83b84a6bb) | Jan 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [b3295065c3](https://bsd-hardware.info/?probe=b3295065c3) | Jan 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [cc8588d977](https://bsd-hardware.info/?probe=cc8588d977) | Jan 05, 2023 |
| SLIMBOOK      | ESSENTIAL-15-11             | Notebook    | [3f758732d3](https://bsd-hardware.info/?probe=3f758732d3) | Jan 05, 2023 |
| MSI           | MEG Z690 UNIFY-X            | Desktop     | [e70cd80d11](https://bsd-hardware.info/?probe=e70cd80d11) | Jan 05, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [e3f89954bd](https://bsd-hardware.info/?probe=e3f89954bd) | Jan 05, 2023 |
| Biostar       | J4125NHU                    | Desktop     | [41114c45b7](https://bsd-hardware.info/?probe=41114c45b7) | Jan 05, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [6a0f56a7c4](https://bsd-hardware.info/?probe=6a0f56a7c4) | Jan 05, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3e4f41ff05](https://bsd-hardware.info/?probe=3e4f41ff05) | Jan 05, 2023 |
| AMI           | MNHO-048                    | Desktop     | [fbd9fa83d9](https://bsd-hardware.info/?probe=fbd9fa83d9) | Jan 05, 2023 |
| Winston Ma... | PICO PC                     | Desktop     | [d744315833](https://bsd-hardware.info/?probe=d744315833) | Jan 05, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [19f4631b5a](https://bsd-hardware.info/?probe=19f4631b5a) | Jan 05, 2023 |
| Protectli     | VP2410 10                   | Desktop     | [81c02d080f](https://bsd-hardware.info/?probe=81c02d080f) | Jan 05, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [219200b0b6](https://bsd-hardware.info/?probe=219200b0b6) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1deece00b3](https://bsd-hardware.info/?probe=1deece00b3) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [cc9d84d5ed](https://bsd-hardware.info/?probe=cc9d84d5ed) | Jan 05, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [5a4affef3e](https://bsd-hardware.info/?probe=5a4affef3e) | Jan 04, 2023 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [9dc3183152](https://bsd-hardware.info/?probe=9dc3183152) | Jan 04, 2023 |
| Supermicro    | X10DRiB                     | Desktop     | [d120c268f7](https://bsd-hardware.info/?probe=d120c268f7) | Jan 04, 2023 |
| Supermicro    | X10DRi-T                    | Desktop     | [3bd4e1dc9c](https://bsd-hardware.info/?probe=3bd4e1dc9c) | Jan 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [6062f9823e](https://bsd-hardware.info/?probe=6062f9823e) | Jan 04, 2023 |
| Acer          | Aspire X3400                | Desktop     | [fa59d6aa07](https://bsd-hardware.info/?probe=fa59d6aa07) | Jan 04, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [f10075e5d1](https://bsd-hardware.info/?probe=f10075e5d1) | Jan 04, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [4730790da9](https://bsd-hardware.info/?probe=4730790da9) | Jan 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [42277bd8ff](https://bsd-hardware.info/?probe=42277bd8ff) | Jan 04, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [39149acdbd](https://bsd-hardware.info/?probe=39149acdbd) | Jan 04, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [17f5e2e3d2](https://bsd-hardware.info/?probe=17f5e2e3d2) | Jan 04, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [6a1ff80054](https://bsd-hardware.info/?probe=6a1ff80054) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [a1517b13f6](https://bsd-hardware.info/?probe=a1517b13f6) | Jan 04, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [21c60a4db8](https://bsd-hardware.info/?probe=21c60a4db8) | Jan 04, 2023 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [1a72755a55](https://bsd-hardware.info/?probe=1a72755a55) | Jan 04, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [97e19b4cd1](https://bsd-hardware.info/?probe=97e19b4cd1) | Jan 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [3d2465f9f9](https://bsd-hardware.info/?probe=3d2465f9f9) | Jan 03, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [c19d0a4f63](https://bsd-hardware.info/?probe=c19d0a4f63) | Jan 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b1ee757669](https://bsd-hardware.info/?probe=b1ee757669) | Jan 03, 2023 |
| Sophos        | UTM                         | Firewall    | [96361c589a](https://bsd-hardware.info/?probe=96361c589a) | Jan 03, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [aa6c483d4f](https://bsd-hardware.info/?probe=aa6c483d4f) | Jan 03, 2023 |
| Sophos        | SG                          | Firewall    | [4f105d12b8](https://bsd-hardware.info/?probe=4f105d12b8) | Jan 03, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | Notebook    | [0657433463](https://bsd-hardware.info/?probe=0657433463) | Jan 03, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [8069ed414b](https://bsd-hardware.info/?probe=8069ed414b) | Jan 03, 2023 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | Notebook    | [ef6972d07a](https://bsd-hardware.info/?probe=ef6972d07a) | Jan 03, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7d6e899adb](https://bsd-hardware.info/?probe=7d6e899adb) | Jan 03, 2023 |
| PC Engines    | apu4                        | Desktop     | [3d69b3aec1](https://bsd-hardware.info/?probe=3d69b3aec1) | Jan 03, 2023 |
| PC Engines    | apu4                        | Desktop     | [62e6e7e679](https://bsd-hardware.info/?probe=62e6e7e679) | Jan 03, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [409d119307](https://bsd-hardware.info/?probe=409d119307) | Jan 02, 2023 |
| HP            | 213D A01                    | Desktop     | [3a1fd3f0a0](https://bsd-hardware.info/?probe=3a1fd3f0a0) | Jan 02, 2023 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [d66b90249d](https://bsd-hardware.info/?probe=d66b90249d) | Jan 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [ea01217f17](https://bsd-hardware.info/?probe=ea01217f17) | Jan 02, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [203823deda](https://bsd-hardware.info/?probe=203823deda) | Jan 02, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [8835404cf3](https://bsd-hardware.info/?probe=8835404cf3) | Jan 02, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [849af12174](https://bsd-hardware.info/?probe=849af12174) | Jan 02, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [70b1ca485d](https://bsd-hardware.info/?probe=70b1ca485d) | Jan 02, 2023 |
| Intel         | Milstead Platform           | Notebook    | [21ec3118ef](https://bsd-hardware.info/?probe=21ec3118ef) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [5159265605](https://bsd-hardware.info/?probe=5159265605) | Jan 02, 2023 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [c96a5de4ed](https://bsd-hardware.info/?probe=c96a5de4ed) | Jan 02, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [7dc1fdfadb](https://bsd-hardware.info/?probe=7dc1fdfadb) | Jan 02, 2023 |
| Alienware     | m15 R4                      | Notebook    | [1438237430](https://bsd-hardware.info/?probe=1438237430) | Jan 02, 2023 |
| Dell          | 0CU409                      | Desktop     | [a547f05175](https://bsd-hardware.info/?probe=a547f05175) | Jan 02, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5d360961d4](https://bsd-hardware.info/?probe=5d360961d4) | Jan 02, 2023 |
| HP            | 8103 A01                    | Mini pc     | [989cfd51a8](https://bsd-hardware.info/?probe=989cfd51a8) | Jan 02, 2023 |
| HP            | 8055                        | Desktop     | [c8f3d3687d](https://bsd-hardware.info/?probe=c8f3d3687d) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [1697219032](https://bsd-hardware.info/?probe=1697219032) | Jan 02, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9dd29daa88](https://bsd-hardware.info/?probe=9dd29daa88) | Jan 02, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [a9bbb3592c](https://bsd-hardware.info/?probe=a9bbb3592c) | Jan 02, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [d5f8e71171](https://bsd-hardware.info/?probe=d5f8e71171) | Jan 02, 2023 |
| Gigabyte      | Z390 AORUS ELITE            | Desktop     | [dcf6e2df1a](https://bsd-hardware.info/?probe=dcf6e2df1a) | Jan 02, 2023 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [9c526b27dd](https://bsd-hardware.info/?probe=9c526b27dd) | Jan 02, 2023 |
| SmbiosType... | SmbiosType2_BoardProduct... | Desktop     | [d8d62a103a](https://bsd-hardware.info/?probe=d8d62a103a) | Jan 02, 2023 |
| Shuttle       | DS20U                       | Desktop     | [a5aa09e49f](https://bsd-hardware.info/?probe=a5aa09e49f) | Jan 01, 2023 |
| PC Engines    | apu4                        | Desktop     | [31b327c32b](https://bsd-hardware.info/?probe=31b327c32b) | Jan 01, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [2973cd399c](https://bsd-hardware.info/?probe=2973cd399c) | Jan 01, 2023 |
| ASRock        | E350M1                      | Desktop     | [6a7e5c8d0c](https://bsd-hardware.info/?probe=6a7e5c8d0c) | Jan 01, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [3b0ef08599](https://bsd-hardware.info/?probe=3b0ef08599) | Jan 01, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [b3ac391a7e](https://bsd-hardware.info/?probe=b3ac391a7e) | Jan 01, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [7a86ed2309](https://bsd-hardware.info/?probe=7a86ed2309) | Jan 01, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [a9b3805c0b](https://bsd-hardware.info/?probe=a9b3805c0b) | Jan 01, 2023 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [d179977442](https://bsd-hardware.info/?probe=d179977442) | Jan 01, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0a57dcce99](https://bsd-hardware.info/?probe=0a57dcce99) | Jan 01, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [d3306559de](https://bsd-hardware.info/?probe=d3306559de) | Jan 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [772779fadf](https://bsd-hardware.info/?probe=772779fadf) | Jan 01, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [6345f92400](https://bsd-hardware.info/?probe=6345f92400) | Jan 01, 2023 |
| Dell          | 04415J A00                  | Mini pc     | [3737d80840](https://bsd-hardware.info/?probe=3737d80840) | Dec 31, 2022 |
| HP            | 1825                        | Desktop     | [f7e94decd0](https://bsd-hardware.info/?probe=f7e94decd0) | Dec 31, 2022 |
| HP            | 1825                        | Desktop     | [afc1259508](https://bsd-hardware.info/?probe=afc1259508) | Dec 31, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [b6ec2e7e28](https://bsd-hardware.info/?probe=b6ec2e7e28) | Dec 31, 2022 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | Notebook    | [22c4a06468](https://bsd-hardware.info/?probe=22c4a06468) | Dec 31, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [ab7e64f657](https://bsd-hardware.info/?probe=ab7e64f657) | Dec 31, 2022 |
| Sophos        | UTM                         | Firewall    | [81bbacbfee](https://bsd-hardware.info/?probe=81bbacbfee) | Dec 31, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [21e1293019](https://bsd-hardware.info/?probe=21e1293019) | Dec 31, 2022 |
| Sophos        | SG                          | Firewall    | [8679b4c8f4](https://bsd-hardware.info/?probe=8679b4c8f4) | Dec 31, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [0bf1c2abef](https://bsd-hardware.info/?probe=0bf1c2abef) | Dec 31, 2022 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | Desktop     | [ac867149f2](https://bsd-hardware.info/?probe=ac867149f2) | Dec 31, 2022 |
| Supermicro    | X11SSH-LN4F                 | Server      | [5e84d1a402](https://bsd-hardware.info/?probe=5e84d1a402) | Dec 31, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [c6c6858ef0](https://bsd-hardware.info/?probe=c6c6858ef0) | Dec 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [16daca3076](https://bsd-hardware.info/?probe=16daca3076) | Dec 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [68a847f5c2](https://bsd-hardware.info/?probe=68a847f5c2) | Dec 31, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [cac58d91b6](https://bsd-hardware.info/?probe=cac58d91b6) | Dec 31, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [910c2bba4a](https://bsd-hardware.info/?probe=910c2bba4a) | Dec 31, 2022 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [334575b738](https://bsd-hardware.info/?probe=334575b738) | Dec 31, 2022 |
| GoWin Solu... | R86S                        | Desktop     | [4243d313a1](https://bsd-hardware.info/?probe=4243d313a1) | Dec 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [5967766127](https://bsd-hardware.info/?probe=5967766127) | Dec 30, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [c791e3e3fd](https://bsd-hardware.info/?probe=c791e3e3fd) | Dec 30, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [d5fa6c651c](https://bsd-hardware.info/?probe=d5fa6c651c) | Dec 30, 2022 |
| Fujitsu       | D3313-S3 S26361-D3313-S3    | Desktop     | [b89a55c4aa](https://bsd-hardware.info/?probe=b89a55c4aa) | Dec 30, 2022 |
| OEM           | 1.0                         | Desktop     | [f2aeb0ea02](https://bsd-hardware.info/?probe=f2aeb0ea02) | Dec 30, 2022 |
| CompuLab      | SBC-fit-PC4                 | Mini pc     | [c781bd46dc](https://bsd-hardware.info/?probe=c781bd46dc) | Dec 30, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [cd3e4f7122](https://bsd-hardware.info/?probe=cd3e4f7122) | Dec 30, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [a8ece272af](https://bsd-hardware.info/?probe=a8ece272af) | Dec 30, 2022 |
| Protectli     | FW4B                        | Desktop     | [406fe72c22](https://bsd-hardware.info/?probe=406fe72c22) | Dec 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [126bde2444](https://bsd-hardware.info/?probe=126bde2444) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [956499202e](https://bsd-hardware.info/?probe=956499202e) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [4d9a4bfc40](https://bsd-hardware.info/?probe=4d9a4bfc40) | Dec 30, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [d4460f8031](https://bsd-hardware.info/?probe=d4460f8031) | Dec 30, 2022 |
| Protectli     | FW6                         | Desktop     | [0d62222b7a](https://bsd-hardware.info/?probe=0d62222b7a) | Dec 30, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [46c3e7ffdd](https://bsd-hardware.info/?probe=46c3e7ffdd) | Dec 30, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [8b4c84d972](https://bsd-hardware.info/?probe=8b4c84d972) | Dec 30, 2022 |
| Unknown       | Unknown                     | Firewall    | [72eaa7a90f](https://bsd-hardware.info/?probe=72eaa7a90f) | Dec 30, 2022 |
| Shuttle       | FH110                       | Desktop     | [3759d77a05](https://bsd-hardware.info/?probe=3759d77a05) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [e23f822438](https://bsd-hardware.info/?probe=e23f822438) | Dec 29, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d22c37fa81](https://bsd-hardware.info/?probe=d22c37fa81) | Dec 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [0f727c761b](https://bsd-hardware.info/?probe=0f727c761b) | Dec 29, 2022 |
| Gigabyte      | MBHM87P-00                  | Desktop     | [5d287163c9](https://bsd-hardware.info/?probe=5d287163c9) | Dec 29, 2022 |
| Dell          | 0GN4PW A00                  | Desktop     | [77e235d9f8](https://bsd-hardware.info/?probe=77e235d9f8) | Dec 29, 2022 |
| Advantech     | UNO-2483G-474AE             | Desktop     | [d453f64b4f](https://bsd-hardware.info/?probe=d453f64b4f) | Dec 29, 2022 |
| HP            | 8000 X4                     | Desktop     | [e66d228381](https://bsd-hardware.info/?probe=e66d228381) | Dec 29, 2022 |
| PC Engines    | APU2                        | Desktop     | [7aaf2d91ba](https://bsd-hardware.info/?probe=7aaf2d91ba) | Dec 29, 2022 |
| Lanner        | FW-7543 B-GA                | Desktop     | [6c145361a3](https://bsd-hardware.info/?probe=6c145361a3) | Dec 29, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d3b1e89901](https://bsd-hardware.info/?probe=d3b1e89901) | Dec 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [1dab2c420a](https://bsd-hardware.info/?probe=1dab2c420a) | Dec 28, 2022 |
| Intel         | DENLOW_REFRESH_WS           | Desktop     | [4f86e686d2](https://bsd-hardware.info/?probe=4f86e686d2) | Dec 28, 2022 |
| MSI           | H270 GAMING M3              | Desktop     | [5d14519e73](https://bsd-hardware.info/?probe=5d14519e73) | Dec 28, 2022 |
| MSI           | H270 GAMING M3              | Desktop     | [5dcdab1ee3](https://bsd-hardware.info/?probe=5dcdab1ee3) | Dec 28, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [b685ddc2ad](https://bsd-hardware.info/?probe=b685ddc2ad) | Dec 28, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [fa3c5f6504](https://bsd-hardware.info/?probe=fa3c5f6504) | Dec 28, 2022 |
| PC Engines    | APU2                        | Desktop     | [85da0654e1](https://bsd-hardware.info/?probe=85da0654e1) | Dec 28, 2022 |
| Intel         | CARLOW                      | Desktop     | [fa30f060f3](https://bsd-hardware.info/?probe=fa30f060f3) | Dec 28, 2022 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| ASUSTek       | P11C-M Series               | Desktop     | [21f838983b](https://bsd-hardware.info/?probe=21f838983b) | Dec 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9954c0abee](https://bsd-hardware.info/?probe=9954c0abee) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [5b8ad02694](https://bsd-hardware.info/?probe=5b8ad02694) | Dec 28, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [5dafbbced0](https://bsd-hardware.info/?probe=5dafbbced0) | Dec 28, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Desktop     | [888de76acd](https://bsd-hardware.info/?probe=888de76acd) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [e70af54c3f](https://bsd-hardware.info/?probe=e70af54c3f) | Dec 28, 2022 |
| HP            | 1998                        | Desktop     | [afc7de60e3](https://bsd-hardware.info/?probe=afc7de60e3) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c3b95220d7](https://bsd-hardware.info/?probe=c3b95220d7) | Dec 28, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [79d8b1477f](https://bsd-hardware.info/?probe=79d8b1477f) | Dec 28, 2022 |
| Shuttle       | FH110                       | Desktop     | [be457c2796](https://bsd-hardware.info/?probe=be457c2796) | Dec 27, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8d3ab2cab5](https://bsd-hardware.info/?probe=8d3ab2cab5) | Dec 27, 2022 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [4bcc34fdca](https://bsd-hardware.info/?probe=4bcc34fdca) | Dec 27, 2022 |
| Intel         | D2500HN AAG81480-500        | Desktop     | [dae5627541](https://bsd-hardware.info/?probe=dae5627541) | Dec 27, 2022 |
| Google        | Peppy                       | Notebook    | [e063619f03](https://bsd-hardware.info/?probe=e063619f03) | Dec 27, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [8cb1f1a8ea](https://bsd-hardware.info/?probe=8cb1f1a8ea) | Dec 27, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [3bdb5aa361](https://bsd-hardware.info/?probe=3bdb5aa361) | Dec 27, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [41094c24b2](https://bsd-hardware.info/?probe=41094c24b2) | Dec 27, 2022 |
| Dell          | 0X744K A02                  | Server      | [c63d853abc](https://bsd-hardware.info/?probe=c63d853abc) | Dec 27, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [07dc4a3178](https://bsd-hardware.info/?probe=07dc4a3178) | Dec 27, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b553cea3bd](https://bsd-hardware.info/?probe=b553cea3bd) | Dec 26, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [50c8cb79f7](https://bsd-hardware.info/?probe=50c8cb79f7) | Dec 26, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [d4296fd9d8](https://bsd-hardware.info/?probe=d4296fd9d8) | Dec 26, 2022 |
| Sophos        | SG                          | Firewall    | [e331fe5e06](https://bsd-hardware.info/?probe=e331fe5e06) | Dec 26, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2265227a5c](https://bsd-hardware.info/?probe=2265227a5c) | Dec 26, 2022 |
| Dell          | 0X744K A02                  | Server      | [a9dac66670](https://bsd-hardware.info/?probe=a9dac66670) | Dec 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [39bce6117f](https://bsd-hardware.info/?probe=39bce6117f) | Dec 26, 2022 |
| Dell          | 051FJ8 A01                  | Desktop     | [7f66a21d24](https://bsd-hardware.info/?probe=7f66a21d24) | Dec 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [e52abbf1b8](https://bsd-hardware.info/?probe=e52abbf1b8) | Dec 26, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [d62deb9883](https://bsd-hardware.info/?probe=d62deb9883) | Dec 26, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7b36d32911](https://bsd-hardware.info/?probe=7b36d32911) | Dec 26, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [5f713b6061](https://bsd-hardware.info/?probe=5f713b6061) | Dec 26, 2022 |
| Protectli     | FW6                         | Desktop     | [90758fca97](https://bsd-hardware.info/?probe=90758fca97) | Dec 26, 2022 |
| Dell          | 0M877N A01                  | Server      | [340dc7255c](https://bsd-hardware.info/?probe=340dc7255c) | Dec 26, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [3fc9a4fd5c](https://bsd-hardware.info/?probe=3fc9a4fd5c) | Dec 26, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [b09ff8826c](https://bsd-hardware.info/?probe=b09ff8826c) | Dec 26, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [f2a248dcfe](https://bsd-hardware.info/?probe=f2a248dcfe) | Dec 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [b4d44b0018](https://bsd-hardware.info/?probe=b4d44b0018) | Dec 26, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [bc829dbb1a](https://bsd-hardware.info/?probe=bc829dbb1a) | Dec 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [f73a37ab81](https://bsd-hardware.info/?probe=f73a37ab81) | Dec 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2e842ddb27](https://bsd-hardware.info/?probe=2e842ddb27) | Dec 25, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [883dbf15e4](https://bsd-hardware.info/?probe=883dbf15e4) | Dec 25, 2022 |
| Cisco         | ASA5515 A0                  | Desktop     | [9e587b9499](https://bsd-hardware.info/?probe=9e587b9499) | Dec 25, 2022 |
| Shuttle       | FH110                       | Desktop     | [a194756b95](https://bsd-hardware.info/?probe=a194756b95) | Dec 25, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [1769da5143](https://bsd-hardware.info/?probe=1769da5143) | Dec 25, 2022 |
| HP            | 8062                        | Desktop     | [f4d3eb024d](https://bsd-hardware.info/?probe=f4d3eb024d) | Dec 25, 2022 |
| Star Labs     | Lite                        | Notebook    | [9ad15636dd](https://bsd-hardware.info/?probe=9ad15636dd) | Dec 25, 2022 |
| HP            | 213D A01                    | Desktop     | [bd620f0fc0](https://bsd-hardware.info/?probe=bd620f0fc0) | Dec 25, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [f1cb9703a7](https://bsd-hardware.info/?probe=f1cb9703a7) | Dec 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [bd212706ad](https://bsd-hardware.info/?probe=bd212706ad) | Dec 24, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [af60c7ce81](https://bsd-hardware.info/?probe=af60c7ce81) | Dec 24, 2022 |
| Supermicro    | X10SRH-CLN4FA               | Desktop     | [84c360ad02](https://bsd-hardware.info/?probe=84c360ad02) | Dec 24, 2022 |
| Sophos        | UTM                         | Firewall    | [224580445a](https://bsd-hardware.info/?probe=224580445a) | Dec 24, 2022 |
| Alienware     | m15 R4                      | Notebook    | [deaef8f0ef](https://bsd-hardware.info/?probe=deaef8f0ef) | Dec 24, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [33c59c687d](https://bsd-hardware.info/?probe=33c59c687d) | Dec 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [153f99a846](https://bsd-hardware.info/?probe=153f99a846) | Dec 24, 2022 |
| HP            | 8299                        | Desktop     | [6715ee2886](https://bsd-hardware.info/?probe=6715ee2886) | Dec 24, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [b29f2e4573](https://bsd-hardware.info/?probe=b29f2e4573) | Dec 24, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [701c6e95d6](https://bsd-hardware.info/?probe=701c6e95d6) | Dec 24, 2022 |
| ASRock        | N3710-NUC IPC               | Desktop     | [80c809e992](https://bsd-hardware.info/?probe=80c809e992) | Dec 24, 2022 |
| Gigabyte      | Z390 AORUS ELITE            | Desktop     | [91b7417b84](https://bsd-hardware.info/?probe=91b7417b84) | Dec 24, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4c3b92bb42](https://bsd-hardware.info/?probe=4c3b92bb42) | Dec 24, 2022 |
| Dell          | 0H28RR A04                  | Server      | [8e22402d9e](https://bsd-hardware.info/?probe=8e22402d9e) | Dec 24, 2022 |
| Biostar       | A32M2                       | Desktop     | [49c31b364c](https://bsd-hardware.info/?probe=49c31b364c) | Dec 23, 2022 |
| Tactus        | GeoFlex 110                 | Notebook    | [955c355b47](https://bsd-hardware.info/?probe=955c355b47) | Dec 23, 2022 |
| Toshiba       | Satellite BE96-F299         | Notebook    | [ca475dd1d0](https://bsd-hardware.info/?probe=ca475dd1d0) | Dec 23, 2022 |
| Biostar       | A10N-8800E                  | Desktop     | [d3d1107f77](https://bsd-hardware.info/?probe=d3d1107f77) | Dec 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [58b47341c9](https://bsd-hardware.info/?probe=58b47341c9) | Dec 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [b38d32b139](https://bsd-hardware.info/?probe=b38d32b139) | Dec 23, 2022 |
| MSI           | A78M-E35                    | Desktop     | [03176e6683](https://bsd-hardware.info/?probe=03176e6683) | Dec 23, 2022 |
| Sony          | VPCSB11FX                   | Notebook    | [966183e570](https://bsd-hardware.info/?probe=966183e570) | Dec 23, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b19a4d1696](https://bsd-hardware.info/?probe=b19a4d1696) | Dec 23, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [52327286e4](https://bsd-hardware.info/?probe=52327286e4) | Dec 23, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [0d70cc442b](https://bsd-hardware.info/?probe=0d70cc442b) | Dec 23, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [3a8d5c61b6](https://bsd-hardware.info/?probe=3a8d5c61b6) | Dec 23, 2022 |
| Lenovo        | ThinkPad T480 20L6S13100    | Notebook    | [67daa912fa](https://bsd-hardware.info/?probe=67daa912fa) | Dec 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7cccecfde1](https://bsd-hardware.info/?probe=7cccecfde1) | Dec 23, 2022 |
| Intel BOX4... | Geminilake                  | Desktop     | [a2b2b7c25f](https://bsd-hardware.info/?probe=a2b2b7c25f) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [a2bc442acd](https://bsd-hardware.info/?probe=a2bc442acd) | Dec 23, 2022 |
| Intel BOX4... | Geminilake                  | Desktop     | [06933f3d87](https://bsd-hardware.info/?probe=06933f3d87) | Dec 23, 2022 |
| Unknown       | QD-WHLU01                   | Desktop     | [a0fb185069](https://bsd-hardware.info/?probe=a0fb185069) | Dec 23, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [e0b4e13386](https://bsd-hardware.info/?probe=e0b4e13386) | Dec 23, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [8325caa4d6](https://bsd-hardware.info/?probe=8325caa4d6) | Dec 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| Dell          | Vostro 1400                 | Notebook    | [087a3d269f](https://bsd-hardware.info/?probe=087a3d269f) | Dec 23, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [570b96d0f7](https://bsd-hardware.info/?probe=570b96d0f7) | Dec 23, 2022 |
| HP            | 8299                        | Desktop     | [d9eec3c9f5](https://bsd-hardware.info/?probe=d9eec3c9f5) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [91a89db2ab](https://bsd-hardware.info/?probe=91a89db2ab) | Dec 23, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [bc2c536004](https://bsd-hardware.info/?probe=bc2c536004) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [58ca7ca7d4](https://bsd-hardware.info/?probe=58ca7ca7d4) | Dec 23, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [062fb4cccd](https://bsd-hardware.info/?probe=062fb4cccd) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [dfd3e7acb1](https://bsd-hardware.info/?probe=dfd3e7acb1) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [daaad6a386](https://bsd-hardware.info/?probe=daaad6a386) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [67bc182d1d](https://bsd-hardware.info/?probe=67bc182d1d) | Dec 23, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [6f8bdb560b](https://bsd-hardware.info/?probe=6f8bdb560b) | Dec 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3e5e7e3e61](https://bsd-hardware.info/?probe=3e5e7e3e61) | Dec 22, 2022 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cde7bad6c3](https://bsd-hardware.info/?probe=cde7bad6c3) | Dec 22, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [78bcccda01](https://bsd-hardware.info/?probe=78bcccda01) | Dec 22, 2022 |
| Dell          | 060J9C A00                  | Mini pc     | [29b3e0b639](https://bsd-hardware.info/?probe=29b3e0b639) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [eea4262af2](https://bsd-hardware.info/?probe=eea4262af2) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [cae00eb4d6](https://bsd-hardware.info/?probe=cae00eb4d6) | Dec 22, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [01d8e43ee1](https://bsd-hardware.info/?probe=01d8e43ee1) | Dec 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [0f03a7f2ce](https://bsd-hardware.info/?probe=0f03a7f2ce) | Dec 22, 2022 |
| AAEON         | FWS-2251 V1.0               | Desktop     | [a4ff0a7ec5](https://bsd-hardware.info/?probe=a4ff0a7ec5) | Dec 22, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [9e817a9114](https://bsd-hardware.info/?probe=9e817a9114) | Dec 22, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [90dfe8ee6b](https://bsd-hardware.info/?probe=90dfe8ee6b) | Dec 22, 2022 |
| Acer          | WG43M                       | Desktop     | [d316352c20](https://bsd-hardware.info/?probe=d316352c20) | Dec 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [527bf6bbe4](https://bsd-hardware.info/?probe=527bf6bbe4) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [b8c89bdca8](https://bsd-hardware.info/?probe=b8c89bdca8) | Dec 22, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [633b9a5425](https://bsd-hardware.info/?probe=633b9a5425) | Dec 22, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2ac107df0f](https://bsd-hardware.info/?probe=2ac107df0f) | Dec 22, 2022 |
| AMI           | Cherry Trail CR             | Mini pc     | [cc9eb40ce1](https://bsd-hardware.info/?probe=cc9eb40ce1) | Dec 22, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [f241237f76](https://bsd-hardware.info/?probe=f241237f76) | Dec 22, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [0c3fea5eb0](https://bsd-hardware.info/?probe=0c3fea5eb0) | Dec 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [0a40b02aeb](https://bsd-hardware.info/?probe=0a40b02aeb) | Dec 22, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [df221cefbc](https://bsd-hardware.info/?probe=df221cefbc) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [b0d1792185](https://bsd-hardware.info/?probe=b0d1792185) | Dec 21, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [16589e2878](https://bsd-hardware.info/?probe=16589e2878) | Dec 21, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [17ddf8c2e1](https://bsd-hardware.info/?probe=17ddf8c2e1) | Dec 21, 2022 |
| PC Engines    | APU2                        | Desktop     | [9781d92062](https://bsd-hardware.info/?probe=9781d92062) | Dec 21, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [490f20c93d](https://bsd-hardware.info/?probe=490f20c93d) | Dec 21, 2022 |
| PC Engines    | APU2                        | Desktop     | [e94b983d48](https://bsd-hardware.info/?probe=e94b983d48) | Dec 21, 2022 |
| ACMA          | X8SIE                       | Desktop     | [01898b2ffb](https://bsd-hardware.info/?probe=01898b2ffb) | Dec 21, 2022 |
| Dell          | 0UW457 A03                  | Desktop     | [47b66a0d86](https://bsd-hardware.info/?probe=47b66a0d86) | Dec 21, 2022 |
| Raspberry ... | Raspberry Pi 400            | Desktop     | [ee9cac334f](https://bsd-hardware.info/?probe=ee9cac334f) | Dec 21, 2022 |
| Lenovo        | ThinkPad T60 1951A47        | Notebook    | [e254601f07](https://bsd-hardware.info/?probe=e254601f07) | Dec 21, 2022 |
| HP            | 18E7                        | Desktop     | [0b962b9400](https://bsd-hardware.info/?probe=0b962b9400) | Dec 20, 2022 |
| Intel         | S3420GP E51976-407          | Server      | [c614a1e46f](https://bsd-hardware.info/?probe=c614a1e46f) | Dec 20, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [16f59f69dc](https://bsd-hardware.info/?probe=16f59f69dc) | Dec 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [0bffe61dae](https://bsd-hardware.info/?probe=0bffe61dae) | Dec 20, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3502cb3d47](https://bsd-hardware.info/?probe=3502cb3d47) | Dec 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [a8ec4c3ae4](https://bsd-hardware.info/?probe=a8ec4c3ae4) | Dec 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [4667028e67](https://bsd-hardware.info/?probe=4667028e67) | Dec 20, 2022 |
| Protectli     | FW2B Ver                    | Desktop     | [9596576df7](https://bsd-hardware.info/?probe=9596576df7) | Dec 20, 2022 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [e1e1a80328](https://bsd-hardware.info/?probe=e1e1a80328) | Dec 20, 2022 |
| Dell          | 0X744K A02                  | Server      | [e45fc09011](https://bsd-hardware.info/?probe=e45fc09011) | Dec 20, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [2ea413db31](https://bsd-hardware.info/?probe=2ea413db31) | Dec 20, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8de4ff8626](https://bsd-hardware.info/?probe=8de4ff8626) | Dec 20, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [31f17adc5b](https://bsd-hardware.info/?probe=31f17adc5b) | Dec 20, 2022 |
| Dell          | 0WR7PY A00                  | Desktop     | [360336dcc1](https://bsd-hardware.info/?probe=360336dcc1) | Dec 20, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [af2a9d1a42](https://bsd-hardware.info/?probe=af2a9d1a42) | Dec 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [364b3758b6](https://bsd-hardware.info/?probe=364b3758b6) | Dec 20, 2022 |
| Sophos        | SG                          | Firewall    | [5536740301](https://bsd-hardware.info/?probe=5536740301) | Dec 20, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [3c36f8db41](https://bsd-hardware.info/?probe=3c36f8db41) | Dec 20, 2022 |
| MSI           | MS-7922                     | Desktop     | [95dbf4f7a8](https://bsd-hardware.info/?probe=95dbf4f7a8) | Dec 19, 2022 |
| Supermicro    | X10SDV-4C-TLN4F             | Server      | [c0c8d1f85e](https://bsd-hardware.info/?probe=c0c8d1f85e) | Dec 19, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [32207ea5d9](https://bsd-hardware.info/?probe=32207ea5d9) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [4c5ccd04d0](https://bsd-hardware.info/?probe=4c5ccd04d0) | Dec 19, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b84941cdd5](https://bsd-hardware.info/?probe=b84941cdd5) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [5d37a0669c](https://bsd-hardware.info/?probe=5d37a0669c) | Dec 19, 2022 |
| Lenovo        | ThinkPad T530 2392AQU       | Notebook    | [9a3cbe1893](https://bsd-hardware.info/?probe=9a3cbe1893) | Dec 19, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [67baacfc7d](https://bsd-hardware.info/?probe=67baacfc7d) | Dec 19, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [0eea35e069](https://bsd-hardware.info/?probe=0eea35e069) | Dec 19, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [c9de65beeb](https://bsd-hardware.info/?probe=c9de65beeb) | Dec 19, 2022 |
| PC Engines    | APU2                        | Desktop     | [5de84cb508](https://bsd-hardware.info/?probe=5de84cb508) | Dec 19, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [511f2a6d16](https://bsd-hardware.info/?probe=511f2a6d16) | Dec 19, 2022 |
| Unknown       | Pine64 RockPro64 v2.1       | Desktop     | [59525051d3](https://bsd-hardware.info/?probe=59525051d3) | Dec 19, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [683591700f](https://bsd-hardware.info/?probe=683591700f) | Dec 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [fad0a431e5](https://bsd-hardware.info/?probe=fad0a431e5) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [f876d5d5b1](https://bsd-hardware.info/?probe=f876d5d5b1) | Dec 19, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b730e64d4a](https://bsd-hardware.info/?probe=b730e64d4a) | Dec 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 744... | Notebook    | [ea686f63f5](https://bsd-hardware.info/?probe=ea686f63f5) | Dec 19, 2022 |
| Framework     | Laptop                      | Notebook    | [9dcd3592db](https://bsd-hardware.info/?probe=9dcd3592db) | Dec 19, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [29ad5ee336](https://bsd-hardware.info/?probe=29ad5ee336) | Dec 19, 2022 |
| Acer          | Veriton M680G               | Desktop     | [cb44a9e848](https://bsd-hardware.info/?probe=cb44a9e848) | Dec 19, 2022 |
| Acer          | Veriton M680G               | Desktop     | [f7184d9158](https://bsd-hardware.info/?probe=f7184d9158) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [3d77f833b0](https://bsd-hardware.info/?probe=3d77f833b0) | Dec 19, 2022 |
| Dell          | 0VD50G A01                  | Server      | [07852bf200](https://bsd-hardware.info/?probe=07852bf200) | Dec 19, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [b9df714117](https://bsd-hardware.info/?probe=b9df714117) | Dec 19, 2022 |
| Supermicro    | X11SSL-F                    | Server      | [7bd99b62ab](https://bsd-hardware.info/?probe=7bd99b62ab) | Dec 19, 2022 |
| Dell          | Edge Gateway 5000           | Mini pc     | [0af7422e2f](https://bsd-hardware.info/?probe=0af7422e2f) | Dec 18, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [f321130f0e](https://bsd-hardware.info/?probe=f321130f0e) | Dec 18, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [14d483ac06](https://bsd-hardware.info/?probe=14d483ac06) | Dec 18, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [c233fa7d25](https://bsd-hardware.info/?probe=c233fa7d25) | Dec 18, 2022 |
| Dell          | Precision M4800             | Notebook    | [b7a834c4d0](https://bsd-hardware.info/?probe=b7a834c4d0) | Dec 18, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [53a90a6c63](https://bsd-hardware.info/?probe=53a90a6c63) | Dec 18, 2022 |
| ASRock        | B660M-ITX/ac                | Desktop     | [f6c8eb4e18](https://bsd-hardware.info/?probe=f6c8eb4e18) | Dec 18, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [abe21b9c9e](https://bsd-hardware.info/?probe=abe21b9c9e) | Dec 18, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [fc7928dfe9](https://bsd-hardware.info/?probe=fc7928dfe9) | Dec 18, 2022 |
| ASRock        | E3C224D2I                   | Desktop     | [106e525671](https://bsd-hardware.info/?probe=106e525671) | Dec 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c1b0b83306](https://bsd-hardware.info/?probe=c1b0b83306) | Dec 18, 2022 |
| MSI           | H81M-P33                    | Desktop     | [78e4743abd](https://bsd-hardware.info/?probe=78e4743abd) | Dec 18, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [f232e5746e](https://bsd-hardware.info/?probe=f232e5746e) | Dec 18, 2022 |
| Supermicro    | X11SCL-F                    | Server      | [638b27bc34](https://bsd-hardware.info/?probe=638b27bc34) | Dec 18, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [108c9de5cc](https://bsd-hardware.info/?probe=108c9de5cc) | Dec 18, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [1f1de1d49c](https://bsd-hardware.info/?probe=1f1de1d49c) | Dec 18, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [a40ada7f7f](https://bsd-hardware.info/?probe=a40ada7f7f) | Dec 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [f6fababc22](https://bsd-hardware.info/?probe=f6fababc22) | Dec 18, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e06fa5d522](https://bsd-hardware.info/?probe=e06fa5d522) | Dec 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a1b29c356e](https://bsd-hardware.info/?probe=a1b29c356e) | Dec 17, 2022 |
| MSI           | X299 PRO                    | Desktop     | [beec8001a1](https://bsd-hardware.info/?probe=beec8001a1) | Dec 17, 2022 |
| Protectli     | FW6                         | Desktop     | [56f62226e7](https://bsd-hardware.info/?probe=56f62226e7) | Dec 17, 2022 |
| PC Engines    | APU3                        | Desktop     | [5597cca988](https://bsd-hardware.info/?probe=5597cca988) | Dec 17, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [92593f4e79](https://bsd-hardware.info/?probe=92593f4e79) | Dec 17, 2022 |
| MSI           | MS-98C8                     | Desktop     | [a6e45c8e5f](https://bsd-hardware.info/?probe=a6e45c8e5f) | Dec 17, 2022 |
| Dell          | Latitude E6430              | Notebook    | [b8f950de05](https://bsd-hardware.info/?probe=b8f950de05) | Dec 17, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7cf06451fd](https://bsd-hardware.info/?probe=7cf06451fd) | Dec 17, 2022 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [11d5b82cdd](https://bsd-hardware.info/?probe=11d5b82cdd) | Dec 17, 2022 |
| PC Engines    | APU3                        | Desktop     | [0e1197c771](https://bsd-hardware.info/?probe=0e1197c771) | Dec 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [0e98358cf3](https://bsd-hardware.info/?probe=0e98358cf3) | Dec 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [e8095445e8](https://bsd-hardware.info/?probe=e8095445e8) | Dec 17, 2022 |
| HP            | 213D A01                    | Desktop     | [088766f04d](https://bsd-hardware.info/?probe=088766f04d) | Dec 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [f7700c781d](https://bsd-hardware.info/?probe=f7700c781d) | Dec 17, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [f6085ba691](https://bsd-hardware.info/?probe=f6085ba691) | Dec 17, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [7981529337](https://bsd-hardware.info/?probe=7981529337) | Dec 17, 2022 |
| PC Engines    | APU                         | Desktop     | [19786edc61](https://bsd-hardware.info/?probe=19786edc61) | Dec 17, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [afef2952f9](https://bsd-hardware.info/?probe=afef2952f9) | Dec 17, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [b7e599f99d](https://bsd-hardware.info/?probe=b7e599f99d) | Dec 17, 2022 |
| Dell          | Latitude E6430              | Notebook    | [8d92a4e37e](https://bsd-hardware.info/?probe=8d92a4e37e) | Dec 17, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [0da9ef9752](https://bsd-hardware.info/?probe=0da9ef9752) | Dec 17, 2022 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [c3ffb2c87d](https://bsd-hardware.info/?probe=c3ffb2c87d) | Dec 17, 2022 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [160d942d28](https://bsd-hardware.info/?probe=160d942d28) | Dec 17, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [2fe9b1b8c9](https://bsd-hardware.info/?probe=2fe9b1b8c9) | Dec 16, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [4d3d23fbd1](https://bsd-hardware.info/?probe=4d3d23fbd1) | Dec 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [a94bfdaa5c](https://bsd-hardware.info/?probe=a94bfdaa5c) | Dec 16, 2022 |
| Dell          | 02YRK5 A03                  | Desktop     | [547b1abce0](https://bsd-hardware.info/?probe=547b1abce0) | Dec 16, 2022 |
| MSI           | H81M-E33                    | Desktop     | [411bb9d111](https://bsd-hardware.info/?probe=411bb9d111) | Dec 16, 2022 |
| MSI           | MS-B1831                    | Desktop     | [638e327c4e](https://bsd-hardware.info/?probe=638e327c4e) | Dec 16, 2022 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [d44c580408](https://bsd-hardware.info/?probe=d44c580408) | Dec 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [6bf18dfe5a](https://bsd-hardware.info/?probe=6bf18dfe5a) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [3a9623cfb4](https://bsd-hardware.info/?probe=3a9623cfb4) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [0314add226](https://bsd-hardware.info/?probe=0314add226) | Dec 16, 2022 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [cc51093e02](https://bsd-hardware.info/?probe=cc51093e02) | Dec 16, 2022 |
| ASRock        | Q2900M                      | Desktop     | [42a53e5201](https://bsd-hardware.info/?probe=42a53e5201) | Dec 16, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [fa8c102cfd](https://bsd-hardware.info/?probe=fa8c102cfd) | Dec 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [3faaaa8209](https://bsd-hardware.info/?probe=3faaaa8209) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [d9376f2f63](https://bsd-hardware.info/?probe=d9376f2f63) | Dec 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [01e26ec145](https://bsd-hardware.info/?probe=01e26ec145) | Dec 15, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [e6778fa5fd](https://bsd-hardware.info/?probe=e6778fa5fd) | Dec 15, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [40911b66e2](https://bsd-hardware.info/?probe=40911b66e2) | Dec 15, 2022 |
| Supermicro    | X11SBA-LN4F                 | Server      | [649d525fdb](https://bsd-hardware.info/?probe=649d525fdb) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [9ac68a1c6d](https://bsd-hardware.info/?probe=9ac68a1c6d) | Dec 15, 2022 |
| Gigabyte      | N3160ND3V                   | Desktop     | [c84bedc821](https://bsd-hardware.info/?probe=c84bedc821) | Dec 15, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [deb30193e2](https://bsd-hardware.info/?probe=deb30193e2) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [e3508ce360](https://bsd-hardware.info/?probe=e3508ce360) | Dec 15, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [435807287e](https://bsd-hardware.info/?probe=435807287e) | Dec 15, 2022 |
| Dell          | 0WR7PY A00                  | Desktop     | [f923c6c0d6](https://bsd-hardware.info/?probe=f923c6c0d6) | Dec 15, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [7cb1b0cc2d](https://bsd-hardware.info/?probe=7cb1b0cc2d) | Dec 15, 2022 |
| Intel         | H81U                        | Notebook    | [fab3eecc66](https://bsd-hardware.info/?probe=fab3eecc66) | Dec 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [e199c0ec3d](https://bsd-hardware.info/?probe=e199c0ec3d) | Dec 15, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [e5c4d51eab](https://bsd-hardware.info/?probe=e5c4d51eab) | Dec 15, 2022 |
| Sophos        | SG                          | Firewall    | [16753b9090](https://bsd-hardware.info/?probe=16753b9090) | Dec 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [35ecaf0406](https://bsd-hardware.info/?probe=35ecaf0406) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [9d71e35375](https://bsd-hardware.info/?probe=9d71e35375) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [98621b669c](https://bsd-hardware.info/?probe=98621b669c) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [b0639c3d01](https://bsd-hardware.info/?probe=b0639c3d01) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [52fbc8ccf7](https://bsd-hardware.info/?probe=52fbc8ccf7) | Dec 15, 2022 |
| Dell          | 0CU409                      | Desktop     | [718c9c5c8b](https://bsd-hardware.info/?probe=718c9c5c8b) | Dec 15, 2022 |
| Dell          | 0CU409                      | Desktop     | [161da6b850](https://bsd-hardware.info/?probe=161da6b850) | Dec 15, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [d7d0ebf605](https://bsd-hardware.info/?probe=d7d0ebf605) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [9b5307f44d](https://bsd-hardware.info/?probe=9b5307f44d) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [210418cc84](https://bsd-hardware.info/?probe=210418cc84) | Dec 15, 2022 |
| HP            | 1495                        | Desktop     | [04bd0455f2](https://bsd-hardware.info/?probe=04bd0455f2) | Dec 14, 2022 |
| Supermicro    | A1SRM-2758F                 | Server      | [fb96378782](https://bsd-hardware.info/?probe=fb96378782) | Dec 14, 2022 |
| Intel         | H81U                        | Notebook    | [fe1c3cb754](https://bsd-hardware.info/?probe=fe1c3cb754) | Dec 14, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [9551c57fc3](https://bsd-hardware.info/?probe=9551c57fc3) | Dec 14, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [4091e15cac](https://bsd-hardware.info/?probe=4091e15cac) | Dec 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [64c549f3ae](https://bsd-hardware.info/?probe=64c549f3ae) | Dec 14, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [e44f465325](https://bsd-hardware.info/?probe=e44f465325) | Dec 14, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [cb16bb9431](https://bsd-hardware.info/?probe=cb16bb9431) | Dec 14, 2022 |
| NF541         | 1.0                         | Desktop     | [b0644bada6](https://bsd-hardware.info/?probe=b0644bada6) | Dec 14, 2022 |
| HP            | 1495                        | Desktop     | [23f8aeada7](https://bsd-hardware.info/?probe=23f8aeada7) | Dec 14, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [6fc0671dc6](https://bsd-hardware.info/?probe=6fc0671dc6) | Dec 14, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [617f431099](https://bsd-hardware.info/?probe=617f431099) | Dec 14, 2022 |
| HP            | 2215                        | Desktop     | [76f607b100](https://bsd-hardware.info/?probe=76f607b100) | Dec 14, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [a77d60297f](https://bsd-hardware.info/?probe=a77d60297f) | Dec 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [85520bf6bf](https://bsd-hardware.info/?probe=85520bf6bf) | Dec 14, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [0e2278affa](https://bsd-hardware.info/?probe=0e2278affa) | Dec 14, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [6ebcd7c974](https://bsd-hardware.info/?probe=6ebcd7c974) | Dec 14, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [bc15367e9f](https://bsd-hardware.info/?probe=bc15367e9f) | Dec 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [ad7f977515](https://bsd-hardware.info/?probe=ad7f977515) | Dec 13, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| AZW           | U59                         | Desktop     | [9b22c68e98](https://bsd-hardware.info/?probe=9b22c68e98) | Dec 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [ec6827e543](https://bsd-hardware.info/?probe=ec6827e543) | Dec 13, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [2d6c881723](https://bsd-hardware.info/?probe=2d6c881723) | Dec 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f52a3d3fa6](https://bsd-hardware.info/?probe=f52a3d3fa6) | Dec 13, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [f51b401c31](https://bsd-hardware.info/?probe=f51b401c31) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [abed96a938](https://bsd-hardware.info/?probe=abed96a938) | Dec 13, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [66e0c118d2](https://bsd-hardware.info/?probe=66e0c118d2) | Dec 13, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [af9df0d2c9](https://bsd-hardware.info/?probe=af9df0d2c9) | Dec 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [9ee8d1082b](https://bsd-hardware.info/?probe=9ee8d1082b) | Dec 12, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [353c3d5cee](https://bsd-hardware.info/?probe=353c3d5cee) | Dec 12, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| HP            | Pavilion dv4                | Notebook    | [ee94a86a43](https://bsd-hardware.info/?probe=ee94a86a43) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [64c92d49d9](https://bsd-hardware.info/?probe=64c92d49d9) | Dec 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [73cb5d86bc](https://bsd-hardware.info/?probe=73cb5d86bc) | Dec 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [128ce54404](https://bsd-hardware.info/?probe=128ce54404) | Dec 12, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [735f01a028](https://bsd-hardware.info/?probe=735f01a028) | Dec 12, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ca959befa0](https://bsd-hardware.info/?probe=ca959befa0) | Dec 12, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [e1297f9eef](https://bsd-hardware.info/?probe=e1297f9eef) | Dec 12, 2022 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [76519f54e9](https://bsd-hardware.info/?probe=76519f54e9) | Dec 12, 2022 |
| Gigabyte      | X99-Designare EX-CF         | Desktop     | [de5bf4b420](https://bsd-hardware.info/?probe=de5bf4b420) | Dec 12, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [2bf8839d12](https://bsd-hardware.info/?probe=2bf8839d12) | Dec 12, 2022 |
| Shuttle       | DH370                       | Desktop     | [1b938aa1a4](https://bsd-hardware.info/?probe=1b938aa1a4) | Dec 12, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [ba191bd994](https://bsd-hardware.info/?probe=ba191bd994) | Dec 12, 2022 |
| Dell          | 0TY019 A02                  | Server      | [a12907d76a](https://bsd-hardware.info/?probe=a12907d76a) | Dec 12, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [7f343df5d5](https://bsd-hardware.info/?probe=7f343df5d5) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [809da57d90](https://bsd-hardware.info/?probe=809da57d90) | Dec 11, 2022 |
| Sophos        | XG                          | Firewall    | [e35b3151a3](https://bsd-hardware.info/?probe=e35b3151a3) | Dec 11, 2022 |
| Biostar       | A68N-5600E                  | Desktop     | [5274876096](https://bsd-hardware.info/?probe=5274876096) | Dec 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [fa8afd004f](https://bsd-hardware.info/?probe=fa8afd004f) | Dec 11, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [0be43b76d1](https://bsd-hardware.info/?probe=0be43b76d1) | Dec 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [1f110891d0](https://bsd-hardware.info/?probe=1f110891d0) | Dec 11, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [028383847e](https://bsd-hardware.info/?probe=028383847e) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [99502ebe9a](https://bsd-hardware.info/?probe=99502ebe9a) | Dec 11, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [ad71b00b0d](https://bsd-hardware.info/?probe=ad71b00b0d) | Dec 11, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [d79604d043](https://bsd-hardware.info/?probe=d79604d043) | Dec 11, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [6d10b2a0b4](https://bsd-hardware.info/?probe=6d10b2a0b4) | Dec 11, 2022 |
| HP            | 82B4                        | Desktop     | [c47cb195e0](https://bsd-hardware.info/?probe=c47cb195e0) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3124aaaf95](https://bsd-hardware.info/?probe=3124aaaf95) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b1bd01549a](https://bsd-hardware.info/?probe=b1bd01549a) | Dec 11, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [4b14039072](https://bsd-hardware.info/?probe=4b14039072) | Dec 11, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [0939871923](https://bsd-hardware.info/?probe=0939871923) | Dec 11, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [808108016d](https://bsd-hardware.info/?probe=808108016d) | Dec 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [def65f518e](https://bsd-hardware.info/?probe=def65f518e) | Dec 10, 2022 |
| Fujitsu       | D3313-S1 S26361-D3313-S1    | Desktop     | [7570f3ae64](https://bsd-hardware.info/?probe=7570f3ae64) | Dec 10, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d8d6af9e56](https://bsd-hardware.info/?probe=d8d6af9e56) | Dec 10, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [1d8397a653](https://bsd-hardware.info/?probe=1d8397a653) | Dec 10, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [6b64c3dbaf](https://bsd-hardware.info/?probe=6b64c3dbaf) | Dec 10, 2022 |
| HP            | 213D A01                    | Desktop     | [6c83f31e71](https://bsd-hardware.info/?probe=6c83f31e71) | Dec 10, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [0b08951f1c](https://bsd-hardware.info/?probe=0b08951f1c) | Dec 10, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [7aef0a996b](https://bsd-hardware.info/?probe=7aef0a996b) | Dec 10, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [342c99d07d](https://bsd-hardware.info/?probe=342c99d07d) | Dec 10, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [33395e819a](https://bsd-hardware.info/?probe=33395e819a) | Dec 10, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [7d80c62813](https://bsd-hardware.info/?probe=7d80c62813) | Dec 09, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [1115d508c1](https://bsd-hardware.info/?probe=1115d508c1) | Dec 09, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [2048ff5f71](https://bsd-hardware.info/?probe=2048ff5f71) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [0405fd0f0d](https://bsd-hardware.info/?probe=0405fd0f0d) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c30f53fc6d](https://bsd-hardware.info/?probe=c30f53fc6d) | Dec 09, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [073c2c8de0](https://bsd-hardware.info/?probe=073c2c8de0) | Dec 09, 2022 |
| HP            | 2000                        | Notebook    | [5414b7c943](https://bsd-hardware.info/?probe=5414b7c943) | Dec 09, 2022 |
| Hardkernel    | ODROID-H3                   | Desktop     | [cd6aa62212](https://bsd-hardware.info/?probe=cd6aa62212) | Dec 09, 2022 |
| HP            | 1495                        | Desktop     | [3eab39d89f](https://bsd-hardware.info/?probe=3eab39d89f) | Dec 09, 2022 |
| Sophos        | SG                          | Firewall    | [07fbfad254](https://bsd-hardware.info/?probe=07fbfad254) | Dec 09, 2022 |
| Dell          | 0DRG19 A00                  | Mini pc     | [bbca9fc84f](https://bsd-hardware.info/?probe=bbca9fc84f) | Dec 09, 2022 |
| Sophos        | SG                          | Firewall    | [a3b0edbd3c](https://bsd-hardware.info/?probe=a3b0edbd3c) | Dec 09, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [10b6c81bce](https://bsd-hardware.info/?probe=10b6c81bce) | Dec 09, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [094ac0c253](https://bsd-hardware.info/?probe=094ac0c253) | Dec 09, 2022 |
| HP            | 3397                        | Desktop     | [bc9e5c3ab7](https://bsd-hardware.info/?probe=bc9e5c3ab7) | Dec 09, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [3f55143fd9](https://bsd-hardware.info/?probe=3f55143fd9) | Dec 09, 2022 |
| Pegatron      | 2A72h                       | Desktop     | [87e76fd095](https://bsd-hardware.info/?probe=87e76fd095) | Dec 09, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [6b03cb139e](https://bsd-hardware.info/?probe=6b03cb139e) | Dec 09, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [b2f0da8246](https://bsd-hardware.info/?probe=b2f0da8246) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [493df1f529](https://bsd-hardware.info/?probe=493df1f529) | Dec 09, 2022 |
| PC Engines    | apu4                        | Desktop     | [3e3ab7f196](https://bsd-hardware.info/?probe=3e3ab7f196) | Dec 09, 2022 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [0ac47aa8a0](https://bsd-hardware.info/?probe=0ac47aa8a0) | Dec 09, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [b2720b8b88](https://bsd-hardware.info/?probe=b2720b8b88) | Dec 08, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [48d5feacf2](https://bsd-hardware.info/?probe=48d5feacf2) | Dec 08, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [79b2a5d3a5](https://bsd-hardware.info/?probe=79b2a5d3a5) | Dec 08, 2022 |
| Dell          | 0TY019 A02                  | Server      | [84b683ec0b](https://bsd-hardware.info/?probe=84b683ec0b) | Dec 08, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [84f8198c18](https://bsd-hardware.info/?probe=84f8198c18) | Dec 08, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [dbbdd023e9](https://bsd-hardware.info/?probe=dbbdd023e9) | Dec 08, 2022 |
| Protectli     | FW4C Ver                    | Desktop     | [71368e5cde](https://bsd-hardware.info/?probe=71368e5cde) | Dec 08, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [575d201794](https://bsd-hardware.info/?probe=575d201794) | Dec 07, 2022 |
| HP            | 245 G6                      | Notebook    | [49ce6aa725](https://bsd-hardware.info/?probe=49ce6aa725) | Dec 07, 2022 |
| ASUSTek       | G11CD                       | Desktop     | [7bc1746333](https://bsd-hardware.info/?probe=7bc1746333) | Dec 07, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [294f283d65](https://bsd-hardware.info/?probe=294f283d65) | Dec 07, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [9862c1b507](https://bsd-hardware.info/?probe=9862c1b507) | Dec 07, 2022 |
| Lenovo        | 319E SEK0T35577 IOT 4247... | Mini pc     | [33545a5181](https://bsd-hardware.info/?probe=33545a5181) | Dec 07, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [6db81b5ffe](https://bsd-hardware.info/?probe=6db81b5ffe) | Dec 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c953c78309](https://bsd-hardware.info/?probe=c953c78309) | Dec 07, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [7f6194b56e](https://bsd-hardware.info/?probe=7f6194b56e) | Dec 07, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [8ac499a511](https://bsd-hardware.info/?probe=8ac499a511) | Dec 07, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [a28b2cf6da](https://bsd-hardware.info/?probe=a28b2cf6da) | Dec 07, 2022 |
| HP            | 1495                        | Desktop     | [3f033cb7f5](https://bsd-hardware.info/?probe=3f033cb7f5) | Dec 07, 2022 |
| Sophos        | XG                          | Firewall    | [b29a7eaa33](https://bsd-hardware.info/?probe=b29a7eaa33) | Dec 07, 2022 |
| ASRock        | H110 Pro BTC+               | Desktop     | [7cc4b63834](https://bsd-hardware.info/?probe=7cc4b63834) | Dec 07, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [27dea9bcb5](https://bsd-hardware.info/?probe=27dea9bcb5) | Dec 07, 2022 |
| ASRock        | H110 Pro BTC+               | Desktop     | [f733e29fc8](https://bsd-hardware.info/?probe=f733e29fc8) | Dec 06, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [c33d11ed7b](https://bsd-hardware.info/?probe=c33d11ed7b) | Dec 06, 2022 |
| JGINYUE       | H97I GAMING V1.0            | Desktop     | [f222af4098](https://bsd-hardware.info/?probe=f222af4098) | Dec 06, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [24b9490c77](https://bsd-hardware.info/?probe=24b9490c77) | Dec 06, 2022 |
| Shuttle       | DS10U                       | Desktop     | [0f1e027b35](https://bsd-hardware.info/?probe=0f1e027b35) | Dec 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [78893acbd5](https://bsd-hardware.info/?probe=78893acbd5) | Dec 06, 2022 |
| ASUSTek       | CM1530                      | Desktop     | [902c77b5dc](https://bsd-hardware.info/?probe=902c77b5dc) | Dec 06, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [61347ab3e9](https://bsd-hardware.info/?probe=61347ab3e9) | Dec 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [e3dad11b11](https://bsd-hardware.info/?probe=e3dad11b11) | Dec 06, 2022 |
| HP            | 82A2                        | Desktop     | [c612b7e283](https://bsd-hardware.info/?probe=c612b7e283) | Dec 06, 2022 |
| Supermicro    | X10SLM+-LN4F                | Server      | [319819f81d](https://bsd-hardware.info/?probe=319819f81d) | Dec 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [657972a55d](https://bsd-hardware.info/?probe=657972a55d) | Dec 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [33f23b1291](https://bsd-hardware.info/?probe=33f23b1291) | Dec 06, 2022 |
| YANYU         | R250                        | Desktop     | [bb364271b2](https://bsd-hardware.info/?probe=bb364271b2) | Dec 05, 2022 |
| DFI           | BE17X(170/171/173)          | Notebook    | [9822160345](https://bsd-hardware.info/?probe=9822160345) | Dec 05, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [eaa3b9783e](https://bsd-hardware.info/?probe=eaa3b9783e) | Dec 05, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5441995e7b](https://bsd-hardware.info/?probe=5441995e7b) | Dec 05, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f130844e1e](https://bsd-hardware.info/?probe=f130844e1e) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [15b2363325](https://bsd-hardware.info/?probe=15b2363325) | Dec 05, 2022 |
| PC Engines    | apu4                        | Desktop     | [72061eb254](https://bsd-hardware.info/?probe=72061eb254) | Dec 05, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [2fe00838c3](https://bsd-hardware.info/?probe=2fe00838c3) | Dec 05, 2022 |
| ACMA          | X8SIE                       | Desktop     | [361e4ccc04](https://bsd-hardware.info/?probe=361e4ccc04) | Dec 05, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [71f95dafb4](https://bsd-hardware.info/?probe=71f95dafb4) | Dec 05, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [f6685811a3](https://bsd-hardware.info/?probe=f6685811a3) | Dec 05, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [218e00e7ea](https://bsd-hardware.info/?probe=218e00e7ea) | Dec 05, 2022 |
| Dell          | 0CNWVK A00                  | Desktop     | [5a022db6bf](https://bsd-hardware.info/?probe=5a022db6bf) | Dec 05, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Acer          | Aspire XC-105               | Desktop     | [250b12c3f2](https://bsd-hardware.info/?probe=250b12c3f2) | Dec 05, 2022 |
| Intel         | CARLOW                      | Desktop     | [1b45524779](https://bsd-hardware.info/?probe=1b45524779) | Dec 05, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [05566134f9](https://bsd-hardware.info/?probe=05566134f9) | Dec 05, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [aa9482884f](https://bsd-hardware.info/?probe=aa9482884f) | Dec 05, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [90279b62b7](https://bsd-hardware.info/?probe=90279b62b7) | Dec 05, 2022 |
| Google        | Lick                        | Notebook    | [8099b2df21](https://bsd-hardware.info/?probe=8099b2df21) | Dec 04, 2022 |
| Shuttle       | FS77U                       | Desktop     | [4172b79cfc](https://bsd-hardware.info/?probe=4172b79cfc) | Dec 04, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [54d1511b82](https://bsd-hardware.info/?probe=54d1511b82) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [54e89ef90b](https://bsd-hardware.info/?probe=54e89ef90b) | Dec 04, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [be5f6ad306](https://bsd-hardware.info/?probe=be5f6ad306) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [af4f0984ae](https://bsd-hardware.info/?probe=af4f0984ae) | Dec 04, 2022 |
| ASUSTek       | E35M1-I DELUXE              | Desktop     | [1a183385c7](https://bsd-hardware.info/?probe=1a183385c7) | Dec 04, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d72a45fb8f](https://bsd-hardware.info/?probe=d72a45fb8f) | Dec 04, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [595d174631](https://bsd-hardware.info/?probe=595d174631) | Dec 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8ee41750dc](https://bsd-hardware.info/?probe=8ee41750dc) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [d9113585f0](https://bsd-hardware.info/?probe=d9113585f0) | Dec 04, 2022 |
| Sophos        | XG                          | Firewall    | [a51c56cb12](https://bsd-hardware.info/?probe=a51c56cb12) | Dec 04, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [0bdf47ea4c](https://bsd-hardware.info/?probe=0bdf47ea4c) | Dec 04, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [f34b488e42](https://bsd-hardware.info/?probe=f34b488e42) | Dec 04, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [9497657cb2](https://bsd-hardware.info/?probe=9497657cb2) | Dec 04, 2022 |
| Google        | Lick                        | Notebook    | [9eb2abcdcc](https://bsd-hardware.info/?probe=9eb2abcdcc) | Dec 03, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [94f78cb509](https://bsd-hardware.info/?probe=94f78cb509) | Dec 03, 2022 |
| Google        | Lars                        | Notebook    | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS5BU00    | Notebook    | [10619ac217](https://bsd-hardware.info/?probe=10619ac217) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [aeb690b9f3](https://bsd-hardware.info/?probe=aeb690b9f3) | Dec 03, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [1916a4064b](https://bsd-hardware.info/?probe=1916a4064b) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [d4e60c5984](https://bsd-hardware.info/?probe=d4e60c5984) | Dec 03, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ddeb9befdf](https://bsd-hardware.info/?probe=ddeb9befdf) | Dec 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [90de1777bc](https://bsd-hardware.info/?probe=90de1777bc) | Dec 02, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f6c721906b](https://bsd-hardware.info/?probe=f6c721906b) | Dec 02, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5e75bcdb11](https://bsd-hardware.info/?probe=5e75bcdb11) | Dec 02, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [40a0d948b4](https://bsd-hardware.info/?probe=40a0d948b4) | Dec 02, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [f8719b2320](https://bsd-hardware.info/?probe=f8719b2320) | Dec 02, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [c0c4fa9349](https://bsd-hardware.info/?probe=c0c4fa9349) | Dec 02, 2022 |
| HASEE Comp... | N95XKP6                     | Notebook    | [0bc2996a6d](https://bsd-hardware.info/?probe=0bc2996a6d) | Dec 02, 2022 |
| ASUSTek       | PRIME H310T2 R2.0           | All in one  | [d1cc7c07e0](https://bsd-hardware.info/?probe=d1cc7c07e0) | Dec 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [5c3941eb3f](https://bsd-hardware.info/?probe=5c3941eb3f) | Dec 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d3b72fdce8](https://bsd-hardware.info/?probe=d3b72fdce8) | Dec 02, 2022 |
| Dell          | Latitude 5590               | Notebook    | [0a17f04eba](https://bsd-hardware.info/?probe=0a17f04eba) | Dec 02, 2022 |
| Intel         | D33217CK G76541-300         | Desktop     | [545a39b1e4](https://bsd-hardware.info/?probe=545a39b1e4) | Dec 02, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [4bf1aae972](https://bsd-hardware.info/?probe=4bf1aae972) | Dec 02, 2022 |
| Intel         | X99                         | Desktop     | [c21a466fc1](https://bsd-hardware.info/?probe=c21a466fc1) | Dec 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [243e309a04](https://bsd-hardware.info/?probe=243e309a04) | Dec 01, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [03708406e8](https://bsd-hardware.info/?probe=03708406e8) | Dec 01, 2022 |
| HP            | 8054                        | Desktop     | [c25adeb2ff](https://bsd-hardware.info/?probe=c25adeb2ff) | Dec 01, 2022 |
| Thomas-Kre... | P9A-I/2550/4L               | Firewall    | [6bec1ec37d](https://bsd-hardware.info/?probe=6bec1ec37d) | Dec 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [32a4df9cae](https://bsd-hardware.info/?probe=32a4df9cae) | Dec 01, 2022 |
| Intel         | NUC11ATBC4 M53051-400       | Mini pc     | [6fe2ba74b7](https://bsd-hardware.info/?probe=6fe2ba74b7) | Dec 01, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a7c2e16f5c](https://bsd-hardware.info/?probe=a7c2e16f5c) | Dec 01, 2022 |
| Panasonic     | CF-54-1                     | Notebook    | [0c5820ea0d](https://bsd-hardware.info/?probe=0c5820ea0d) | Dec 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [504a659236](https://bsd-hardware.info/?probe=504a659236) | Dec 01, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [529cbab9aa](https://bsd-hardware.info/?probe=529cbab9aa) | Dec 01, 2022 |
| Acidanther... | MacBookPro15,1              | Notebook    | [57c3a4005a](https://bsd-hardware.info/?probe=57c3a4005a) | Dec 01, 2022 |
| MSI           | Z87I                        | Desktop     | [570046969c](https://bsd-hardware.info/?probe=570046969c) | Dec 01, 2022 |
| HP            | 8103 A01                    | Mini pc     | [5cd982c2ee](https://bsd-hardware.info/?probe=5cd982c2ee) | Nov 30, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [84d1656c05](https://bsd-hardware.info/?probe=84d1656c05) | Nov 30, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [6a1a5865cb](https://bsd-hardware.info/?probe=6a1a5865cb) | Nov 30, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [087264570d](https://bsd-hardware.info/?probe=087264570d) | Nov 30, 2022 |
| PC Engines    | apu4                        | Desktop     | [7c8b9014b1](https://bsd-hardware.info/?probe=7c8b9014b1) | Nov 30, 2022 |
| PC Engines    | apu4                        | Desktop     | [dd39e91713](https://bsd-hardware.info/?probe=dd39e91713) | Nov 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [794e041b13](https://bsd-hardware.info/?probe=794e041b13) | Nov 30, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [920a2fe2e9](https://bsd-hardware.info/?probe=920a2fe2e9) | Nov 30, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [ac4f4b181a](https://bsd-hardware.info/?probe=ac4f4b181a) | Nov 30, 2022 |
| Panasonic     | CF-31-5                     | Notebook    | [7047afaaf4](https://bsd-hardware.info/?probe=7047afaaf4) | Nov 30, 2022 |
| Protectli     | FW6                         | Desktop     | [95f3201109](https://bsd-hardware.info/?probe=95f3201109) | Nov 30, 2022 |
| GPD           | P3 MAX                      | Notebook    | [4a467c9616](https://bsd-hardware.info/?probe=4a467c9616) | Nov 30, 2022 |
| Protectli     | FW4A Ver                    | Desktop     | [9e6e0f5548](https://bsd-hardware.info/?probe=9e6e0f5548) | Nov 30, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [3dd9e3557c](https://bsd-hardware.info/?probe=3dd9e3557c) | Nov 30, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [f3b09cfb70](https://bsd-hardware.info/?probe=f3b09cfb70) | Nov 30, 2022 |
| Intel         | D33217CK G76541-300         | Desktop     | [bbdd9a1b98](https://bsd-hardware.info/?probe=bbdd9a1b98) | Nov 30, 2022 |
| Sophos        | SG                          | Firewall    | [357c380b7c](https://bsd-hardware.info/?probe=357c380b7c) | Nov 29, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [1d61d0cf62](https://bsd-hardware.info/?probe=1d61d0cf62) | Nov 29, 2022 |
| ASRockRack    | X470D4U                     | Desktop     | [38d7f55ef7](https://bsd-hardware.info/?probe=38d7f55ef7) | Nov 29, 2022 |
| Lenovo        | ThinkPad T430 2347G7G       | Notebook    | [640540cd67](https://bsd-hardware.info/?probe=640540cd67) | Nov 29, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cfaeaeb2f2](https://bsd-hardware.info/?probe=cfaeaeb2f2) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [929e4bda1e](https://bsd-hardware.info/?probe=929e4bda1e) | Nov 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [a5b10d3f79](https://bsd-hardware.info/?probe=a5b10d3f79) | Nov 29, 2022 |
| ACMA          | X8SIE                       | Desktop     | [532b81e55f](https://bsd-hardware.info/?probe=532b81e55f) | Nov 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7308d658dc](https://bsd-hardware.info/?probe=7308d658dc) | Nov 29, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [2299087d09](https://bsd-hardware.info/?probe=2299087d09) | Nov 29, 2022 |
| Unknown       | A04                         | Server      | [07f21afacc](https://bsd-hardware.info/?probe=07f21afacc) | Nov 29, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [9618eb0cbe](https://bsd-hardware.info/?probe=9618eb0cbe) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [7c9ee800c5](https://bsd-hardware.info/?probe=7c9ee800c5) | Nov 29, 2022 |
| Lenovo        | 316A SDK0J40697 WIN 3305... | Mini pc     | [26c9557a0a](https://bsd-hardware.info/?probe=26c9557a0a) | Nov 29, 2022 |
| HP            | 8299                        | Desktop     | [d697a2e953](https://bsd-hardware.info/?probe=d697a2e953) | Nov 29, 2022 |
| Acer          | TravelMate B115-M           | Notebook    | [13e318fec2](https://bsd-hardware.info/?probe=13e318fec2) | Nov 29, 2022 |
| ACMA          | X8SIE                       | Desktop     | [d0112d027b](https://bsd-hardware.info/?probe=d0112d027b) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [43163b0170](https://bsd-hardware.info/?probe=43163b0170) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [d00aa0021e](https://bsd-hardware.info/?probe=d00aa0021e) | Nov 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e40278b06](https://bsd-hardware.info/?probe=4e40278b06) | Nov 28, 2022 |
| Lenovo        | ThinkPad T460 20FMS0XL23    | Notebook    | [bc7585ec56](https://bsd-hardware.info/?probe=bc7585ec56) | Nov 28, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [28dd3a0b1b](https://bsd-hardware.info/?probe=28dd3a0b1b) | Nov 28, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [d48dbd053d](https://bsd-hardware.info/?probe=d48dbd053d) | Nov 28, 2022 |
| PC Engines    | apu4                        | Desktop     | [588e065800](https://bsd-hardware.info/?probe=588e065800) | Nov 28, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [e850e0ae9c](https://bsd-hardware.info/?probe=e850e0ae9c) | Nov 28, 2022 |
| Toshiba       | TECRA Z40-C-12Z             | Notebook    | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [35950045c6](https://bsd-hardware.info/?probe=35950045c6) | Nov 28, 2022 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 425       | 3.82%   |
| OPNsense 21.7.7      | 281       | 2.53%   |
| OPNsense 22.7.10     | 268       | 2.41%   |
| helloSystem 0.5.0    | 245       | 2.2%    |
| OPNsense 21.1        | 240       | 2.16%   |
| OPNsense 21.7.1      | 229       | 2.06%   |
| OPNsense 22.1        | 227       | 2.04%   |
| OPNsense 21.7.3      | 225       | 2.02%   |
| OPNsense 21.1.5      | 225       | 2.02%   |
| FreeBSD 13.0         | 222       | 2%      |
| OPNsense 22.7.4      | 214       | 1.93%   |
| OPNsense 20.7.8      | 214       | 1.93%   |
| OpenBSD 6.8          | 208       | 1.87%   |
| OPNsense 21.1.3      | 205       | 1.84%   |
| FreeBSD 13.1         | 195       | 1.75%   |
| OPNsense 22.1.6      | 192       | 1.73%   |
| helloSystem 0.4.0    | 190       | 1.71%   |
| OPNsense 22.1.8      | 187       | 1.68%   |
| OPNsense 22.7.6      | 182       | 1.64%   |
| OPNsense 21.1.4      | 175       | 1.57%   |
| OPNsense 22.1.10     | 172       | 1.55%   |
| OPNsense 22.7.9      | 169       | 1.52%   |
| OPNsense 21.1.1      | 157       | 1.41%   |
| OPNsense 21.1.2      | 147       | 1.32%   |
| FreeBSD 12.2         | 141       | 1.27%   |
| helloSystem 0.6.0    | 137       | 1.23%   |
| OPNsense 22.1.4      | 134       | 1.21%   |
| OPNsense 21.7.6      | 131       | 1.18%   |
| OPNsense 22.7        | 129       | 1.16%   |
| OPNsense 21.1.6      | 129       | 1.16%   |
| OPNsense 21.1.7      | 127       | 1.14%   |
| OPNsense 22.7.8      | 123       | 1.11%   |
| OPNsense 22.7.2      | 123       | 1.11%   |
| OPNsense 21.1.8      | 122       | 1.1%    |
| OPNsense 22.1.2      | 120       | 1.08%   |
| OPNsense 22.7.7      | 116       | 1.04%   |
| OPNsense 22.1.1      | 116       | 1.04%   |
| FreeBSD 14.0-CURRENT | 115       | 1.03%   |
| helloSystem 0.8.0    | 114       | 1.03%   |
| OPNsense 21.7.5      | 113       | 1.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 4521      | 51.76%  |
| FreeBSD     | 2006      | 22.97%  |
| helloSystem | 1073      | 12.28%  |
| OpenBSD     | 512       | 5.86%   |
| GhostBSD    | 213       | 2.44%   |
| NomadBSD    | 151       | 1.73%   |
| NetBSD      | 56        | 0.64%   |
| TrueNAS     | 45        | 0.52%   |
| FreeNAS     | 30        | 0.34%   |
| pfSense     | 29        | 0.33%   |
| HardenedBSD | 19        | 0.22%   |
| DragonFly   | 16        | 0.18%   |
| MidnightBSD | 15        | 0.17%   |
| MyBee       | 12        | 0.14%   |
| FuryBSD     | 11        | 0.13%   |
| XigmaNAS    | 9         | 0.1%    |
| OS108       | 4         | 0.05%   |
| FuguIta     | 4         | 0.05%   |
| PC-BSD      | 3         | 0.03%   |
| ClonOS      | 3         | 0.03%   |
| Ting        | 2         | 0.02%   |
| LibertyBSD  | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 8363      | 97.07%  |
| i386    | 123       | 1.43%   |
| arm64   | 96        | 1.11%   |
| arm     | 12        | 0.14%   |
| evbarm  | 6         | 0.07%   |
| macppc  | 5         | 0.06%   |
| sparc64 | 3         | 0.03%   |
| powerpc | 2         | 0.02%   |
| octeon  | 2         | 0.02%   |
| armv7   | 2         | 0.02%   |
| riscv   | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Console          | 5495      | 62.24%  |
| helloDesktop     | 1205      | 13.65%  |
| XFCE             | 402       | 4.55%   |
| KDE5             | 343       | 3.88%   |
| MATE             | 287       | 3.25%   |
| fvwm             | 274       | 3.1%    |
| Openbox          | 193       | 2.19%   |
| GNOME            | 163       | 1.85%   |
| TWM              | 157       | 1.78%   |
| i3               | 104       | 1.18%   |
| Cinnamon         | 32        | 0.36%   |
| AwesomeWM        | 24        | 0.27%   |
| Fluxbox          | 22        | 0.25%   |
| LXQt             | 21        | 0.24%   |
| Enlightenment    | 17        | 0.19%   |
| LXDE             | 15        | 0.17%   |
| Lumina           | 11        | 0.12%   |
| DWM              | 9         | 0.1%    |
| GNUstep          | 6         | 0.07%   |
| CTWM             | 5         | 0.06%   |
| xfwm             | 4         | 0.05%   |
| Window Maker     | 4         | 0.05%   |
| CDE              | 4         | 0.05%   |
| spectrwm         | 3         | 0.03%   |
| Picom            | 3         | 0.03%   |
| Xfwm4            | 2         | 0.02%   |
| X-Cinnamon       | 2         | 0.02%   |
| Mutter           | 2         | 0.02%   |
| Metacity (Marco) | 2         | 0.02%   |
| IceWM            | 2         | 0.02%   |
| Compton          | 2         | 0.02%   |
| awesome          | 2         | 0.02%   |
| xinitrc          | 1         | 0.01%   |
| sway             | 1         | 0.01%   |
| StumpWM          | 1         | 0.01%   |
| Ratpoison        | 1         | 0.01%   |
| plasma           | 1         | 0.01%   |
| PekWM            | 1         | 0.01%   |
| KWin             | 1         | 0.01%   |
| KDE              | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 5589      | 64.5%   |
| X11     | 3041      | 35.1%   |
| Wayland | 35        | 0.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 6365      | 72.71%  |
| SLiM    | 1461      | 16.69%  |
| SDDM    | 331       | 3.78%   |
| LightDM | 325       | 3.71%   |
| XDM     | 141       | 1.61%   |
| GDM     | 117       | 1.34%   |
| Ly      | 11        | 0.13%   |
| PCDM    | 2         | 0.02%   |
| WDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 5672      | 64.22%  |
| en_US           | 1594      | 18.05%  |
| C               | 949       | 10.75%  |
| ru_RU           | 151       | 1.71%   |
| de_DE           | 85        | 0.96%   |
| fr_FR           | 51        | 0.58%   |
| en_GB           | 48        | 0.54%   |
| es_ES           | 25        | 0.28%   |
| zh_CN           | 20        | 0.23%   |
| pt_BR           | 17        | 0.19%   |
| it_IT           | 15        | 0.17%   |
| en_CA           | 15        | 0.17%   |
| pl_PL           | 13        | 0.15%   |
| en_AU           | 12        | 0.14%   |
| en              | 12        | 0.14%   |
| ja_JP           | 11        | 0.12%   |
| uk_UA           | 10        | 0.11%   |
| nb_NO           | 7         | 0.08%   |
| fi_FI           | 7         | 0.08%   |
| hu_HU           | 6         | 0.07%   |
| en_IE           | 6         | 0.07%   |
| es_AR           | 5         | 0.06%   |
| en_NZ           | 5         | 0.06%   |
| el_GR           | 5         | 0.06%   |
| cs_CZ           | 5         | 0.06%   |
| sv_SE           | 4         | 0.05%   |
| ru_RU.KOI8-R    | 4         | 0.05%   |
| en_US.ISO8859-1 | 4         | 0.05%   |
| zh_TW           | 3         | 0.03%   |
| tr_TR           | 3         | 0.03%   |
| ru              | 3         | 0.03%   |
| es              | 3         | 0.03%   |
| en_US.US-ASCII  | 3         | 0.03%   |
| de_DE.ISO8859-1 | 3         | 0.03%   |
| de_CH           | 3         | 0.03%   |
| sl_SI           | 2         | 0.02%   |
| sk_SK           | 2         | 0.02%   |
| pt_PT           | 2         | 0.02%   |
| pt              | 2         | 0.02%   |
| nl_NL           | 2         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 6977      | 80%     |
| BIOS | 1744      | 20%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 4453      | 50.4%   |
| Zfs     | 3521      | 39.85%  |
| Ffs     | 517       | 5.85%   |
| Cd9660  | 318       | 3.6%    |
| Hammer2 | 15        | 0.17%   |
| Unknown | 7         | 0.08%   |
| XXX     | 3         | 0.03%   |
| Xfs     | 1         | 0.01%   |
| Nfs     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 7718      | 88.91%  |
| MBR     | 843       | 9.71%   |
| Unknown | 106       | 1.22%   |
| BSD     | 14        | 0.16%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 1030      | 11.96%  |
| Lenovo                     | 884       | 10.26%  |
| ASUSTek Computer           | 758       | 8.8%    |
| Hewlett-Packard            | 750       | 8.71%   |
| Unknown                    | 653       | 7.58%   |
| Supermicro                 | 425       | 4.93%   |
| Intel                      | 414       | 4.81%   |
| Gigabyte Technology        | 380       | 4.41%   |
| ASRock                     | 355       | 4.12%   |
| PC Engines                 | 284       | 3.3%    |
| MSI                        | 252       | 2.93%   |
| Protectli                  | 249       | 2.89%   |
| AMI                        | 174       | 2.02%   |
| Fujitsu                    | 157       | 1.82%   |
| Acer                       | 157       | 1.82%   |
| Apple                      | 142       | 1.65%   |
| Sophos                     | 113       | 1.31%   |
| ZOTAC                      | 86        | 1%      |
| Deciso                     | 70        | 0.81%   |
| Shuttle                    | 62        | 0.72%   |
| BESSTAR Tech               | 60        | 0.7%    |
| Toshiba                    | 47        | 0.55%   |
| Biostar                    | 38        | 0.44%   |
| Techvision                 | 37        | 0.43%   |
| Samsung Electronics        | 36        | 0.42%   |
| IBM                        | 34        | 0.39%   |
| AWOW                       | 31        | 0.36%   |
| MW                         | 30        | 0.35%   |
| Sony                       | 29        | 0.34%   |
| HARDKERNEL                 | 29        | 0.34%   |
| ASRockRack                 | 29        | 0.34%   |
| CompuLab                   | 26        | 0.3%    |
| AZW                        | 24        | 0.28%   |
| Raspberry Pi Foundation    | 23        | 0.27%   |
| Foxconn                    | 22        | 0.26%   |
| Pegatron                   | 21        | 0.24%   |
| ShenZhen MinWin Technology | 18        | 0.21%   |
| Google                     | 18        | 0.21%   |
| HPE                        | 17        | 0.2%    |
| TUXEDO                     | 15        | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 682       | 7.92%   |
| PC Engines APU2                     | 139       | 1.61%   |
| AMI Aptio CRB                       | 136       | 1.58%   |
| Supermicro Super Server             | 117       | 1.36%   |
| Intel Q3XXG4-P V1.0                 | 102       | 1.18%   |
| Protectli FW4B                      | 101       | 1.17%   |
| PC Engines apu4                     | 92        | 1.07%   |
| Protectli FW6                       | 78        | 0.91%   |
| ASUS All Series                     | 76        | 0.88%   |
| Sophos SG                           | 58        | 0.67%   |
| HP t620 PLUS Quad Core TC           | 49        | 0.57%   |
| Fujitsu FUTRO S920                  | 49        | 0.57%   |
| Dell PowerEdge R210 II              | 43        | 0.5%    |
| HP t730 Thin Client                 | 39        | 0.45%   |
| Dell OptiPlex 9020                  | 38        | 0.44%   |
| Techvision TVI7309X                 | 37        | 0.43%   |
| Dell OptiPlex 3020                  | 34        | 0.39%   |
| Sophos XG                           | 31        | 0.36%   |
| MW GMLK-2_5G4L                      | 30        | 0.35%   |
| Dell OptiPlex 7010                  | 30        | 0.35%   |
| HARDKERNEL ODROID-H2                | 27        | 0.31%   |
| Supermicro X9SCL/X9SCM              | 26        | 0.3%    |
| Sophos UTM                          | 24        | 0.28%   |
| HP ProLiant MicroServer Gen8        | 23        | 0.27%   |
| HP EliteDesk 800 G1 SFF             | 23        | 0.27%   |
| Supermicro A1SAi                    | 21        | 0.24%   |
| AWOW PC BOX                         | 21        | 0.24%   |
| Supermicro X10SLH-N6-ST031          | 20        | 0.23%   |
| PC Engines APU3                     | 20        | 0.23%   |
| PC Engines APU                      | 20        | 0.23%   |
| Deciso Netboard A20                 | 20        | 0.23%   |
| ZOTAC ZBOX-CI329NANO                | 19        | 0.22%   |
| Dell PowerEdge R710                 | 19        | 0.22%   |
| CompuLab fitlet2                    | 19        | 0.22%   |
| Protectli VP2410                    | 18        | 0.21%   |
| Dell Wyse 5070 Extended Thin Client | 18        | 0.21%   |
| Dell PowerEdge R610                 | 18        | 0.21%   |
| Protectli FW2B                      | 16        | 0.19%   |
| HP ProDesk 600 G1 SFF               | 16        | 0.19%   |
| HP Compaq Elite 8300 SFF            | 16        | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Unknown              | 682       | 7.92%   |
| Lenovo ThinkPad      | 531       | 6.17%   |
| Dell OptiPlex        | 310       | 3.6%    |
| Dell PowerEdge       | 262       | 3.04%   |
| Lenovo ThinkCentre   | 149       | 1.73%   |
| Dell Latitude        | 142       | 1.65%   |
| PC Engines APU2      | 139       | 1.61%   |
| AMI Aptio            | 138       | 1.6%    |
| HP ProLiant          | 134       | 1.56%   |
| Supermicro Super     | 117       | 1.36%   |
| Dell Inspiron        | 108       | 1.25%   |
| ASUS PRIME           | 108       | 1.25%   |
| Intel Q3XXG4-P       | 103       | 1.2%    |
| Protectli FW4B       | 101       | 1.17%   |
| Acer Aspire          | 101       | 1.17%   |
| PC Engines apu4      | 92        | 1.07%   |
| HP Compaq            | 91        | 1.06%   |
| Dell Precision       | 80        | 0.93%   |
| Protectli FW6        | 78        | 0.91%   |
| ASUS All             | 76        | 0.88%   |
| HP EliteDesk         | 70        | 0.81%   |
| Fujitsu FUTRO        | 67        | 0.78%   |
| HP ProDesk           | 66        | 0.77%   |
| Sophos SG            | 58        | 0.67%   |
| ASUS ROG             | 56        | 0.65%   |
| HP t620              | 55        | 0.64%   |
| Lenovo IdeaPad       | 54        | 0.63%   |
| ASUS TUF             | 51        | 0.59%   |
| HP Pavilion          | 45        | 0.52%   |
| Deciso Netboard      | 40        | 0.46%   |
| HP t730              | 39        | 0.45%   |
| HP EliteBook         | 38        | 0.44%   |
| Techvision TVI7309X  | 37        | 0.43%   |
| Toshiba Satellite    | 32        | 0.37%   |
| Sophos XG            | 31        | 0.36%   |
| HP ProBook           | 31        | 0.36%   |
| MW GMLK-2            | 30        | 0.35%   |
| Dell XPS             | 28        | 0.33%   |
| Hardkernel ODROID-H2 | 27        | 0.31%   |
| Fujitsu ESPRIMO      | 27        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 1013      | 11.76%  |
| 2019    | 910       | 10.57%  |
| 2020    | 872       | 10.12%  |
| 2021    | 684       | 7.94%   |
| 2016    | 658       | 7.64%   |
| 2014    | 641       | 7.44%   |
| 2013    | 556       | 6.46%   |
| 2017    | 499       | 5.79%   |
| 2015    | 469       | 5.45%   |
| 2011    | 457       | 5.31%   |
| 2012    | 442       | 5.13%   |
| 2022    | 365       | 4.24%   |
| 2010    | 324       | 3.76%   |
| 2009    | 237       | 2.75%   |
| 2008    | 163       | 1.89%   |
| Unknown | 154       | 1.79%   |
| 2007    | 86        | 1%      |
| 2006    | 44        | 0.51%   |
| 2005    | 12        | 0.14%   |
| 2004    | 11        | 0.13%   |
| 2003    | 8         | 0.09%   |
| 2002    | 5         | 0.06%   |
| 2001    | 2         | 0.02%   |
| 2023    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 5075      | 58.92%  |
| Notebook       | 1977      | 22.95%  |
| Server         | 687       | 7.98%   |
| Mini pc        | 591       | 6.86%   |
| Firewall       | 135       | 1.57%   |
| All in one     | 52        | 0.6%    |
| System on chip | 51        | 0.59%   |
| Convertible    | 40        | 0.46%   |
| Tablet         | 5         | 0.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8196      | 95.16%  |
| Yes  | 417       | 4.84%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 3073      | 35.06%  |
| 4.01-8.0        | 1946      | 22.2%   |
| 16.01-24.0      | 1821      | 20.77%  |
| 32.01-64.0      | 786       | 8.97%   |
| 64.01-256.0     | 348       | 3.97%   |
| 2.01-3.0        | 331       | 3.78%   |
| 3.01-4.0        | 148       | 1.69%   |
| 24.01-32.0      | 120       | 1.37%   |
| 0.51-1.0        | 80        | 0.91%   |
| 1.01-2.0        | 61        | 0.7%    |
| 0.01-0.5        | 27        | 0.31%   |
| More than 256.0 | 22        | 0.25%   |
| Unknown         | 2         | 0.02%   |
| 0               | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 0.01-0.5        | 4630      | 51.79%  |
| 0.51-1.0        | 2436      | 27.25%  |
| 1.01-2.0        | 941       | 10.53%  |
| 2.01-3.0        | 236       | 2.64%   |
| 4.01-8.0        | 182       | 2.04%   |
| 3.01-4.0        | 133       | 1.49%   |
| 8.01-16.0       | 95        | 1.06%   |
| Unknown         | 69        | 0.77%   |
| 0               | 62        | 0.69%   |
| 16.01-24.0      | 48        | 0.54%   |
| 24.01-32.0      | 47        | 0.53%   |
| 32.01-64.0      | 36        | 0.4%    |
| 64.01-256.0     | 24        | 0.27%   |
| More than 256.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 5883      | 66.44%  |
| 2      | 1292      | 14.59%  |
| 0      | 728       | 8.22%   |
| 3      | 380       | 4.29%   |
| 4      | 223       | 2.52%   |
| 5      | 109       | 1.23%   |
| 6      | 75        | 0.85%   |
| 7      | 40        | 0.45%   |
| 8      | 24        | 0.27%   |
| 14     | 16        | 0.18%   |
| 10     | 15        | 0.17%   |
| 12     | 12        | 0.14%   |
| 9      | 12        | 0.14%   |
| 11     | 9         | 0.1%    |
| 17     | 5         | 0.06%   |
| 25     | 4         | 0.05%   |
| 18     | 3         | 0.03%   |
| 16     | 3         | 0.03%   |
| 15     | 3         | 0.03%   |
| 13     | 3         | 0.03%   |
| 40     | 2         | 0.02%   |
| 23     | 2         | 0.02%   |
| 21     | 2         | 0.02%   |
| 19     | 2         | 0.02%   |
| 63     | 1         | 0.01%   |
| 58     | 1         | 0.01%   |
| 28     | 1         | 0.01%   |
| 27     | 1         | 0.01%   |
| 26     | 1         | 0.01%   |
| 24     | 1         | 0.01%   |
| 22     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 6908      | 79.6%   |
| Yes       | 1770      | 20.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8191      | 95.09%  |
| No        | 423       | 4.91%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5369      | 61.86%  |
| Yes       | 3310      | 38.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 6505      | 74.92%  |
| Yes       | 2178      | 25.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 2176      | 25.15%  |
| Germany      | 1460      | 16.87%  |
| Russia       | 453       | 5.24%   |
| France       | 355       | 4.1%    |
| UK           | 349       | 4.03%   |
| Canada       | 330       | 3.81%   |
| Netherlands  | 227       | 2.62%   |
| Poland       | 214       | 2.47%   |
| Brazil       | 204       | 2.36%   |
| Australia    | 199       | 2.3%    |
| Italy        | 169       | 1.95%   |
| Switzerland  | 165       | 1.91%   |
| Austria      | 156       | 1.8%    |
| Spain        | 148       | 1.71%   |
| China        | 143       | 1.65%   |
| Sweden       | 138       | 1.59%   |
| Ukraine      | 95        | 1.1%    |
| Czechia      | 84        | 0.97%   |
| Norway       | 79        | 0.91%   |
| Finland      | 76        | 0.88%   |
| India        | 72        | 0.83%   |
| Japan        | 69        | 0.8%    |
| Romania      | 67        | 0.77%   |
| Hungary      | 64        | 0.74%   |
| Indonesia    | 63        | 0.73%   |
| Portugal     | 60        | 0.69%   |
| Belgium      | 58        | 0.67%   |
| Denmark      | 56        | 0.65%   |
| Taiwan       | 53        | 0.61%   |
| Mexico       | 49        | 0.57%   |
| South Korea  | 42        | 0.49%   |
| New Zealand  | 42        | 0.49%   |
| Argentina    | 38        | 0.44%   |
| Greece       | 37        | 0.43%   |
| Bulgaria     | 37        | 0.43%   |
| South Africa | 36        | 0.42%   |
| Thailand     | 29        | 0.34%   |
| Turkey       | 27        | 0.31%   |
| Slovenia     | 24        | 0.28%   |
| Singapore    | 24        | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 149       | 1.57%   |
| Berlin            | 134       | 1.41%   |
| Vienna            | 88        | 0.93%   |
| Paris             | 79        | 0.83%   |
| Munich            | 64        | 0.67%   |
| Hamburg           | 58        | 0.61%   |
| Sydney            | 50        | 0.53%   |
| Amsterdam         | 50        | 0.53%   |
| London            | 48        | 0.51%   |
| St Petersburg     | 47        | 0.5%    |
| Zurich            | 46        | 0.48%   |
| Frankfurt am Main | 39        | 0.41%   |
| Brooklyn          | 39        | 0.41%   |
| Warsaw            | 38        | 0.4%    |
| Kyiv              | 37        | 0.39%   |
| Chicago           | 37        | 0.39%   |
| Montreal          | 36        | 0.38%   |
| Melbourne         | 35        | 0.37%   |
| Seattle           | 33        | 0.35%   |
| Jakarta           | 33        | 0.35%   |
| Cologne           | 33        | 0.35%   |
| Bucharest         | 33        | 0.35%   |
| Toronto           | 31        | 0.33%   |
| New York          | 30        | 0.32%   |
| Helsinki          | 30        | 0.32%   |
| Madrid            | 29        | 0.31%   |
| Denver            | 29        | 0.31%   |
| Stuttgart         | 28        | 0.3%    |
| Prague            | 28        | 0.3%    |
| Perth             | 28        | 0.3%    |
| Oslo              | 27        | 0.28%   |
| Portland          | 26        | 0.27%   |
| Brisbane          | 26        | 0.27%   |
| Dallas            | 25        | 0.26%   |
| Austin            | 24        | 0.25%   |
| Athens            | 24        | 0.25%   |
| Singapore         | 23        | 0.24%   |
| Milan             | 23        | 0.24%   |
| Sofia             | 21        | 0.22%   |
| Rome              | 21        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1563      | 2503   | 15.26%  |
| WDC                 | 1381      | 2956   | 13.49%  |
| Seagate             | 1059      | 2212   | 10.34%  |
| Kingston            | 762       | 1060   | 7.44%   |
| Crucial             | 503       | 737    | 4.91%   |
| Toshiba             | 468       | 838    | 4.57%   |
| SanDisk             | 440       | 584    | 4.3%    |
| Intel               | 421       | 678    | 4.11%   |
| Transcend           | 406       | 582    | 3.96%   |
| Hitachi             | 259       | 502    | 2.53%   |
| A-DATA Technology   | 196       | 273    | 1.91%   |
| Hoodisk             | 183       | 261    | 1.79%   |
| Phison              | 164       | 231    | 1.6%    |
| HGST                | 160       | 421    | 1.56%   |
| China               | 140       | 195    | 1.37%   |
| Hewlett-Packard     | 113       | 330    | 1.1%    |
| NVMe                | 111       | 147    | 1.08%   |
| Micron Technology   | 110       | 171    | 1.07%   |
| SK hynix            | 108       | 139    | 1.05%   |
| SPCC                | 89        | 131    | 0.87%   |
| OCZ                 | 81        | 109    | 0.79%   |
| PNY                 | 80        | 131    | 0.78%   |
| FORESEE             | 79        | 114    | 0.77%   |
| Apacer              | 65        | 74     | 0.63%   |
| Corsair             | 60        | 92     | 0.59%   |
| Intenso             | 53        | 83     | 0.52%   |
| Protectli           | 51        | 83     | 0.5%    |
| Apple               | 51        | 56     | 0.5%    |
| Dogfish             | 49        | 78     | 0.48%   |
| Patriot             | 45        | 61     | 0.44%   |
| KingSpec            | 42        | 52     | 0.41%   |
| Innodisk            | 41        | 49     | 0.4%    |
| LITEON              | 40        | 55     | 0.39%   |
| BIWIN               | 39        | 56     | 0.38%   |
| Gigabyte Technology | 35        | 47     | 0.34%   |
| Silicon Motion      | 33        | 39     | 0.32%   |
| LITEONIT            | 33        | 38     | 0.32%   |
| Fujitsu             | 31        | 42     | 0.3%    |
| Plextor             | 28        | 41     | 0.27%   |
| KIOXIA              | 28        | 35     | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 123       | 1.1%    |
| Samsung SSD 850 EVO 250GB          | 102       | 0.91%   |
| Kingston SA400S37120G 120GB        | 96        | 0.85%   |
| Phison SATA SSD 16GB               | 74        | 0.66%   |
| Samsung SSD 860 EVO 500GB          | 73        | 0.65%   |
| Kingston SUV500MS120G 120GB        | 64        | 0.57%   |
| Crucial CT240BX500SSD1 240GB       | 62        | 0.55%   |
| Samsung SSD 860 EVO 250GB          | 61        | 0.54%   |
| Seagate ST500DM002-1BD142 500GB    | 57        | 0.51%   |
| Samsung SSD 850 EVO 500GB          | 54        | 0.48%   |
| Hoodisk SSD 32GB                   | 52        | 0.46%   |
| Crucial CT500MX500SSD1 500GB       | 51        | 0.45%   |
| Hoodisk SSD 64GB                   | 50        | 0.45%   |
| Crucial CT250MX500SSD1 250GB       | 49        | 0.44%   |
| Hoodisk SSD 128GB                  | 48        | 0.43%   |
| Kingston SV300S37A120G 120GB       | 47        | 0.42%   |
| Crucial CT120BX500SSD1 120GB       | 44        | 0.39%   |
| Transcend TS128GMSA230S 128GB      | 43        | 0.38%   |
| FORESEE 128GB SSD                  | 43        | 0.38%   |
| Seagate ST1000LM035-1RK172 1TB     | 41        | 0.37%   |
| Seagate ST1000DM010-2EP102 1TB     | 41        | 0.37%   |
| HP RAID 1(1+0) 800GB               | 40        | 0.36%   |
| Samsung SSD 860 EVO 1TB            | 39        | 0.35%   |
| Toshiba DT01ACA100 1TB             | 38        | 0.34%   |
| Toshiba MQ01ABD100 1TB             | 37        | 0.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 37        | 0.33%   |
| Samsung SSD 840 EVO 250GB          | 36        | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB       | 35        | 0.31%   |
| Samsung SSD 970 EVO Plus 500GB     | 35        | 0.31%   |
| Kingston SUV500MS240G 240GB        | 35        | 0.31%   |
| WDC WD40EFRX-68N32N0 4TB           | 34        | 0.3%    |
| WDC WDS120G2G0A-00JH30 120GB       | 32        | 0.28%   |
| Samsung SSD 840 EVO 120GB          | 32        | 0.28%   |
| Crucial CT1000MX500SSD1 1TB        | 32        | 0.28%   |
| A-DATA SU650 120GB                 | 32        | 0.28%   |
| Samsung SSD 850 EVO 120GB          | 30        | 0.27%   |
| PNY CS900 120GB SSD                | 30        | 0.27%   |
| Kingston SA400S37480G 480GB        | 30        | 0.27%   |
| WDC WD30EFRX-68EUZN0 3TB           | 29        | 0.26%   |
| SanDisk SDSSDA120G 120GB           | 29        | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                                 | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| WDC                                    | 1068      | 2407   | 32.04%  |
| Seagate                                | 1031      | 2156   | 30.93%  |
| Toshiba                                | 360       | 674    | 10.8%   |
| Hitachi                                | 258       | 498    | 7.74%   |
| HGST                                   | 160       | 421    | 4.8%    |
| Samsung Electronics                    | 149       | 209    | 4.47%   |
| NVMe                                   | 71        | 93     | 2.13%   |
| Hewlett-Packard                        | 51        | 212    | 1.53%   |
| Fujitsu                                | 30        | 40     | 0.9%    |
| Maxtor                                 | 25        | 31     | 0.75%   |
| Apple                                  | 18        | 21     | 0.54%   |
| OPENBSD                                | 16        | 23     | 0.48%   |
| Dell                                   | 13        | 68     | 0.39%   |
| LSI                                    | 8         | 14     | 0.24%   |
| HPE                                    | 7         | 29     | 0.21%   |
| Generic                                | 5         | 5      | 0.15%   |
| USB                                    | 4         | 4      | 0.12%   |
| Adaptec                                | 4         | 14     | 0.12%   |
| NETAPP                                 | 3         | 6      | 0.09%   |
| Lexar                                  | 3         | 3      | 0.09%   |
| JetFlash                               | 3         | 3      | 0.09%   |
| HPT                                    | 3         | 35     | 0.09%   |
| WD MediaMax                            | 2         | 5      | 0.06%   |
| StoreJet                               | 2         | 2      | 0.06%   |
| Product:              USB Flash Memory | 2         | 2      | 0.06%   |
| Multiple                               | 2         | 2      | 0.06%   |
| MaxDigital                             | 2         | 2      | 0.06%   |
| LSILOGIC                               | 2         | 5      | 0.06%   |
| Lenovo                                 | 2         | 4      | 0.06%   |
| IBM/Hitachi                            | 2         | 2      | 0.06%   |
| IBM                                    | 2         | 2      | 0.06%   |
| Cisco                                  | 2         | 4      | 0.06%   |
| China                                  | 2         | 2      | 0.06%   |
| ASMT                                   | 2         | 2      | 0.06%   |
| Areca                                  | 2         | 3      | 0.06%   |
| UFD 2.0                                | 1         | 1      | 0.03%   |
| SYNOLOGY                               | 1         | 1      | 0.03%   |
| SSDPR-CX                               | 1         | 1      | 0.03%   |
| SABRENT                                | 1         | 1      | 0.03%   |
| QUANTUM                                | 1         | 2      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1036      | 1610   | 18.07%  |
| Kingston            | 679       | 941    | 11.85%  |
| SanDisk             | 438       | 579    | 7.64%   |
| Crucial             | 437       | 647    | 7.62%   |
| Transcend           | 373       | 544    | 6.51%   |
| Intel               | 342       | 572    | 5.97%   |
| WDC                 | 199       | 306    | 3.47%   |
| Hoodisk             | 182       | 260    | 3.18%   |
| A-DATA Technology   | 161       | 218    | 2.81%   |
| China               | 138       | 193    | 2.41%   |
| Phison              | 119       | 158    | 2.08%   |
| Micron Technology   | 87        | 137    | 1.52%   |
| OCZ                 | 81        | 109    | 1.41%   |
| FORESEE             | 76        | 110    | 1.33%   |
| SPCC                | 75        | 111    | 1.31%   |
| PNY                 | 74        | 122    | 1.29%   |
| Toshiba             | 72        | 100    | 1.26%   |
| Apacer              | 65        | 74     | 1.13%   |
| Hewlett-Packard     | 58        | 89     | 1.01%   |
| SK hynix            | 53        | 67     | 0.92%   |
| Intenso             | 52        | 82     | 0.91%   |
| Protectli           | 51        | 83     | 0.89%   |
| Dogfish             | 49        | 78     | 0.85%   |
| Corsair             | 46        | 62     | 0.8%    |
| KingSpec            | 42        | 52     | 0.73%   |
| Innodisk            | 41        | 49     | 0.72%   |
| Patriot             | 40        | 55     | 0.7%    |
| LITEON              | 38        | 53     | 0.66%   |
| NVMe                | 36        | 42     | 0.63%   |
| BIWIN               | 36        | 53     | 0.63%   |
| LITEONIT            | 33        | 38     | 0.58%   |
| Apple               | 32        | 34     | 0.56%   |
| Plextor             | 25        | 34     | 0.44%   |
| GOODRAM             | 22        | 34     | 0.38%   |
| Kston               | 21        | 27     | 0.37%   |
| Seagate             | 20        | 39     | 0.35%   |
| Gigabyte Technology | 20        | 29     | 0.35%   |
| Team                | 17        | 22     | 0.3%    |
| KingDian            | 16        | 23     | 0.28%   |
| ATP                 | 16        | 16     | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 5214      | 8332   | 56.63%  |
| HDD  | 2741      | 7024   | 29.77%  |
| NVMe | 1252      | 1912   | 13.6%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 7120      | 15356  | 85.05%  |
| NVMe | 1252      | 1912   | 14.95%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 6076      | 9969   | 73.05%  |
| 0.51-1.0        | 1274      | 2163   | 15.32%  |
| 1.01-2.0        | 421       | 992    | 5.06%   |
| 3.01-4.0        | 203       | 742    | 2.44%   |
| 4.01-10.0       | 173       | 853    | 2.08%   |
| 2.01-3.0        | 125       | 430    | 1.5%    |
| 10.01-20.0      | 40        | 198    | 0.48%   |
| 20.01-50.0      | 3         | 6      | 0.04%   |
| More than 100.0 | 2         | 2      | 0.02%   |
| 0               | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 3320      | 37.05%  |
| 251-500        | 1436      | 16.03%  |
| 1-20           | 1404      | 15.67%  |
| 51-100         | 969       | 10.81%  |
| 21-50          | 838       | 9.35%   |
| 501-1000       | 626       | 6.99%   |
| 1001-2000      | 173       | 1.93%   |
| More than 3000 | 90        | 1%      |
| Unknown        | 63        | 0.7%    |
| 2001-3000      | 41        | 0.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 7772      | 87.49%  |
| 21-50          | 534       | 6.01%   |
| 51-100         | 210       | 2.36%   |
| 101-250        | 141       | 1.59%   |
| Unknown        | 63        | 0.71%   |
| 251-500        | 59        | 0.66%   |
| 501-1000       | 43        | 0.48%   |
| More than 3000 | 25        | 0.28%   |
| 1001-2000      | 22        | 0.25%   |
| 2001-3000      | 13        | 0.15%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 24        | 38     | 1.72%   |
| Kingston SV300S37A120G 120GB        | 15        | 17     | 1.08%   |
| HGST HTS725050A7E630 500GB          | 14        | 29     | 1.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 13        | 16     | 0.93%   |
| Seagate ST500LT012-9WS142 500GB     | 12        | 17     | 0.86%   |
| Seagate ST500LM021-1KJ152 500GB     | 11        | 11     | 0.79%   |
| Toshiba MQ01ABD100 1TB              | 10        | 10     | 0.72%   |
| Seagate ST500LT012-1DG142 500GB     | 10        | 11     | 0.72%   |
| Kingston SMS200S3120G 120GB         | 10        | 11     | 0.72%   |
| Seagate ST3500418AS 500GB           | 9         | 18     | 0.65%   |
| Seagate ST3500413AS 500GB           | 9         | 23     | 0.65%   |
| Seagate ST9500420AS 500GB           | 8         | 11     | 0.57%   |
| Kingston SV300S37A60G 64GB          | 8         | 10     | 0.57%   |
| Apacer 16GB SATA Flash Drive        | 8         | 10     | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB        | 7         | 8      | 0.5%    |
| WDC WD30EFRX-68EUZN0 3TB            | 7         | 19     | 0.5%    |
| Toshiba MQ01ABF050 500GB            | 7         | 9      | 0.5%    |
| Seagate ST9500325AS 500GB           | 7         | 8      | 0.5%    |
| Seagate ST320LT007-9ZV142 320GB     | 7         | 7      | 0.5%    |
| Samsung Electronics HD501LJ 500GB   | 7         | 9      | 0.5%    |
| Intel SSDSA2M080G2GC 80GB           | 7         | 8      | 0.5%    |
| WDC WD20EFRX-68EUZN0 2TB            | 6         | 14     | 0.43%   |
| Seagate ST9320423AS 320GB           | 6         | 6      | 0.43%   |
| Seagate ST9320325AS 320GB           | 6         | 6      | 0.43%   |
| Seagate ST3160815AS 160GB           | 6         | 7      | 0.43%   |
| Samsung Electronics SSD 870 EVO 1TB | 6         | 10     | 0.43%   |
| Samsung Electronics HM160HI 160GB   | 6         | 6      | 0.43%   |
| Kingston SMS200S360G 64GB           | 6         | 6      | 0.43%   |
| Intel SSDSA2M160G2GC 160GB          | 6         | 8      | 0.43%   |
| Hitachi HTS541612J9SA00 120GB       | 6         | 7      | 0.43%   |
| Crucial CT525MX300SSD1 528GB        | 6         | 10     | 0.43%   |
| Crucial CT275MX300SSD1 275GB        | 6         | 9      | 0.43%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 5         | 5      | 0.36%   |
| WDC WD40EFRX-68WT0N0 4TB            | 5         | 13     | 0.36%   |
| Toshiba MQ01ABD075 752GB            | 5         | 5      | 0.36%   |
| Seagate ST380815AS 80GB             | 5         | 5      | 0.36%   |
| Seagate ST3250310AS 250GB           | 5         | 5      | 0.36%   |
| Seagate ST31000528AS 1TB            | 5         | 6      | 0.36%   |
| Seagate ST2000DL003-9VT166 2TB      | 5         | 16     | 0.36%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 6      | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 310       | 457    | 23.1%   |
| WDC                 | 254       | 384    | 18.93%  |
| Hitachi             | 110       | 149    | 8.2%    |
| Samsung Electronics | 106       | 143    | 7.9%    |
| Toshiba             | 95        | 143    | 7.08%   |
| Intel               | 77        | 105    | 5.74%   |
| Kingston            | 75        | 91     | 5.59%   |
| Crucial             | 41        | 61     | 3.06%   |
| HGST                | 40        | 73     | 2.98%   |
| SanDisk             | 31        | 47     | 2.31%   |
| A-DATA Technology   | 19        | 28     | 1.42%   |
| OCZ                 | 17        | 21     | 1.27%   |
| Micron Technology   | 17        | 23     | 1.27%   |
| Apacer              | 13        | 15     | 0.97%   |
| SK hynix            | 11        | 15     | 0.82%   |
| Maxtor              | 11        | 15     | 0.82%   |
| Corsair             | 11        | 16     | 0.82%   |
| China               | 8         | 9      | 0.6%    |
| LITEON              | 7         | 8      | 0.52%   |
| Hewlett-Packard     | 7         | 13     | 0.52%   |
| Fujitsu             | 6         | 9      | 0.45%   |
| Apple               | 6         | 6      | 0.45%   |
| Dogfish             | 5         | 11     | 0.37%   |
| Transcend           | 4         | 8      | 0.3%    |
| VisionTek           | 3         | 7      | 0.22%   |
| SPCC                | 3         | 5      | 0.22%   |
| Phison              | 3         | 3      | 0.22%   |
| KingSpec            | 3         | 3      | 0.22%   |
| KingDian            | 3         | 3      | 0.22%   |
| Intenso             | 3         | 3      | 0.22%   |
| HP Phison           | 3         | 3      | 0.22%   |
| BIWIN               | 3         | 5      | 0.22%   |
| SSSTC               | 2         | 2      | 0.15%   |
| SMI                 | 2         | 2      | 0.15%   |
| Plextor             | 2         | 2      | 0.15%   |
| MyDigitalSSD        | 2         | 4      | 0.15%   |
| ZTC                 | 1         | 3      | 0.07%   |
| XrayDisk            | 1         | 1      | 0.07%   |
| XPG                 | 1         | 1      | 0.07%   |
| Wintec              | 1         | 1      | 0.07%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 309       | 456    | 35.19%  |
| WDC                  | 240       | 367    | 27.33%  |
| Hitachi              | 110       | 149    | 12.53%  |
| Toshiba              | 87        | 131    | 9.91%   |
| Samsung Electronics  | 58        | 73     | 6.61%   |
| HGST                 | 40        | 73     | 4.56%   |
| Maxtor               | 11        | 15     | 1.25%   |
| Hewlett-Packard      | 6         | 11     | 0.68%   |
| Fujitsu              | 6         | 9      | 0.68%   |
| Apple                | 4         | 4      | 0.46%   |
| WD MediaMax          | 1         | 3      | 0.11%   |
| InnoLite             | 1         | 1      | 0.11%   |
| IBM/Hitachi          | 1         | 1      | 0.11%   |
| HPE                  | 1         | 3      | 0.11%   |
| ExcelStor Technology | 1         | 2      | 0.11%   |
| China                | 1         | 1      | 0.11%   |
| Cactus               | 1         | 1      | 0.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 825       | 1300   | 64.1%   |
| SSD  | 448       | 611    | 34.81%  |
| NVMe | 14        | 19     | 1.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZYLN256HCHP-000L2 256GB | 2         | 2      | 6.9%    |
| WDC WD6400AARS-00Y5B1 640GB                  | 1         | 2      | 3.45%   |
| WDC WD3200BPVT-16JJ5T0 320GB                 | 1         | 1      | 3.45%   |
| WDC WD3200AAJS-00YZCA0 320GB                 | 1         | 1      | 3.45%   |
| WDC WD20EARS-00MVWB0 2TB                     | 1         | 1      | 3.45%   |
| WDC WD10SPZX-00Z10T0 1TB                     | 1         | 1      | 3.45%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB         | 1         | 1      | 3.45%   |
| Transcend TS32GSSD370S 32GB                  | 1         | 1      | 3.45%   |
| Toshiba MG05ACA800E 8TB                      | 1         | 1      | 3.45%   |
| SK hynix SC308 SATA 256GB                    | 1         | 1      | 3.45%   |
| Seagate ST4000NM0025 4TB                     | 1         | 2      | 3.45%   |
| Seagate ST3500418AS 500GB                    | 1         | 2      | 3.45%   |
| SanDisk pSSD 16GB                            | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 980 250GB            | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 970 EVO Plus 500GB   | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 960 EVO 250GB        | 1         | 1      | 3.45%   |
| Samsung Electronics HM250JI 250GB            | 1         | 1      | 3.45%   |
| Samsung Electronics HD204UI 2TB              | 1         | 2      | 3.45%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB   | 1         | 1      | 3.45%   |
| Maxtor 6E040L0 41GB                          | 1         | 1      | 3.45%   |
| Kingston SV300S37A60G 64GB                   | 1         | 1      | 3.45%   |
| Intel SSDSC2BW120H6 120GB                    | 1         | 1      | 3.45%   |
| HPE MK000480GWUGF 480GB                      | 1         | 1      | 3.45%   |
| Hitachi HUS724040ALE641 4TB                  | 1         | 14     | 3.45%   |
| Hitachi HTS545025B9A300 250GB                | 1         | 1      | 3.45%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 3.45%   |
| Crucial M4-CT256M4SSD1 256GB                 | 1         | 1      | 3.45%   |
| Crucial CT250P2SSD8 250GB                    | 1         | 1      | 3.45%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 24.14%  |
| WDC                 | 6         | 7      | 20.69%  |
| Seagate             | 2         | 4      | 6.9%    |
| Hitachi             | 2         | 15     | 6.9%    |
| Crucial             | 2         | 2      | 6.9%    |
| Transcend           | 1         | 1      | 3.45%   |
| Toshiba             | 1         | 1      | 3.45%   |
| SK hynix            | 1         | 1      | 3.45%   |
| SanDisk             | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 1      | 3.45%   |
| Maxtor              | 1         | 1      | 3.45%   |
| Kingston            | 1         | 1      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| HPE                 | 1         | 1      | 3.45%   |
| HGST                | 1         | 1      | 3.45%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 6941      | 14573  | 80.91%  |
| Malfunc  | 1258      | 1930   | 14.66%  |
| Detected | 351       | 719    | 4.09%   |
| Failed   | 29        | 46     | 0.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6504      | 62.84%  |
| AMD                              | 1444      | 13.95%  |
| Samsung Electronics              | 519       | 5.01%   |
| Broadcom / LSI                   | 334       | 3.23%   |
| SanDisk                          | 206       | 1.99%   |
| ASMedia Technology               | 168       | 1.62%   |
| Marvell Technology Group         | 107       | 1.03%   |
| Phison Electronics               | 106       | 1.02%   |
| Silicon Motion                   | 99        | 0.96%   |
| Kingston Technology Company      | 91        | 0.88%   |
| Nvidia                           | 89        | 0.86%   |
| Hewlett-Packard                  | 73        | 0.71%   |
| Micron/Crucial Technology        | 66        | 0.64%   |
| SK hynix                         | 63        | 0.61%   |
| JMicron Technology               | 53        | 0.51%   |
| Toshiba                          | 41        | 0.4%    |
| KIOXIA                           | 37        | 0.36%   |
| ADATA Technology                 | 37        | 0.36%   |
| Chelsio Communications           | 31        | 0.3%    |
| Micron Technology                | 29        | 0.28%   |
| Adaptec                          | 28        | 0.27%   |
| Transcend                        | 27        | 0.26%   |
| Silicon Image                    | 23        | 0.22%   |
| VIA Technologies                 | 21        | 0.2%    |
| Seagate Technology               | 15        | 0.14%   |
| Realtek Semiconductor            | 13        | 0.13%   |
| Shenzhen Longsys Electronics     | 12        | 0.12%   |
| Silicon Integrated Systems [SiS] | 10        | 0.1%    |
| MAXIO Technology (Hangzhou)      | 10        | 0.1%    |
| Solid State Storage Technology   | 9         | 0.09%   |
| Lenovo                           | 8         | 0.08%   |
| Areca Technology                 | 8         | 0.08%   |
| Union Memory (Shenzhen)          | 7         | 0.07%   |
| Lite-On Technology               | 7         | 0.07%   |
| Integrated Technology Express    | 6         | 0.06%   |
| Biwin Storage Technology         | 6         | 0.06%   |
| 3ware                            | 6         | 0.06%   |
| Dell                             | 5         | 0.05%   |
| ATP ELECTRONICS                  | 5         | 0.05%   |
| ULi Electronics                  | 4         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 964       | 8.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 595       | 5.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 484       | 4.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 339       | 2.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 333       | 2.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 312       | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 305       | 2.58%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 291       | 2.46%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 265       | 2.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 239       | 2.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 201       | 1.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 198       | 1.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 191       | 1.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 187       | 1.58%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 178       | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 170       | 1.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 167       | 1.41%   |
| Unknown                                                                          | 167       | 1.41%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 165       | 1.39%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 158       | 1.33%   |
| AMD 400 Series Chipset SATA Controller                                           | 148       | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 143       | 1.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 141       | 1.19%   |
| AMD FCH SATA Controller [IDE mode]                                               | 127       | 1.07%   |
| Intel SATA Controller [RAID mode]                                                | 124       | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 123       | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 107       | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 104       | 0.88%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 103       | 0.87%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 94        | 0.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 94        | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 92        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                            | 92        | 0.78%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 87        | 0.73%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 87        | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 86        | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 84        | 0.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 81        | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 81        | 0.68%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 78        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 6984      | 66.6%   |
| NVMe | 1410      | 13.45%  |
| IDE  | 1238      | 11.81%  |
| RAID | 596       | 5.68%   |
| SAS  | 165       | 1.57%   |
| SCSI | 94        | 0.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 6900      | 79.94%  |
| AMD                | 1592      | 18.44%  |
| ARM                | 98        | 1.14%   |
| Unknown            | 24        | 0.28%   |
| PowerPC            | 4         | 0.05%   |
| VIA                | 3         | 0.03%   |
| Rockchip           | 2         | 0.02%   |
| Sun                | 1         | 0.01%   |
| Research           | 1         | 0.01%   |
| Motorola           | 1         | 0.01%   |
| IBM                | 1         | 0.01%   |
| i                  | 1         | 0.01%   |
| Broadcom           | 1         | 0.01%   |
| Baikal Electronics | 1         | 0.01%   |
| 123456789ABC       | 1         | 0.01%   |
| 11th               | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                         | 252       | 2.89%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 175       | 2.01%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 154       | 1.77%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 151       | 1.73%   |
| Intel Celeron N5105 @ 2.00GHz            | 86        | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 84        | 0.96%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 65        | 0.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 64        | 0.73%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 64        | 0.73%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 64        | 0.73%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 57        | 0.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 55        | 0.63%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 53        | 0.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 48        | 0.55%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 48        | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 47        | 0.54%   |
| Intel Atom CPU D525 @ 1.80GHz            | 47        | 0.54%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 46        | 0.53%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 44        | 0.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz        | 43        | 0.49%   |
| Intel Core 2 Duo                         | 43        | 0.49%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 41        | 0.47%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 41        | 0.47%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 41        | 0.47%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 40        | 0.46%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 39        | 0.45%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 39        | 0.45%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 39        | 0.45%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 38        | 0.44%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 38        | 0.44%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 38        | 0.44%   |
| Intel CPU Version                        | 36        | 0.41%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 36        | 0.41%   |
| ARM Cortex-A72 r0p3                      | 36        | 0.41%   |
| Intel Xeon                               | 34        | 0.39%   |
| AMD Ryzen 5 3600 6-Core Processor        | 34        | 0.39%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 33        | 0.38%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 33        | 0.38%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 32        | 0.37%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 32        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1651      | 19.03%  |
| Intel Celeron           | 1260      | 14.52%  |
| Intel Xeon              | 958       | 11.04%  |
| Intel Core i7           | 916       | 10.56%  |
| Intel Core i3           | 672       | 7.74%   |
| Intel Atom              | 404       | 4.66%   |
| AMD GX                  | 404       | 4.66%   |
| Other                   | 280       | 3.23%   |
| Intel Core 2 Duo        | 244       | 2.81%   |
| Intel Pentium           | 234       | 2.7%    |
| AMD Ryzen 5             | 201       | 2.32%   |
| AMD Ryzen 7             | 186       | 2.14%   |
| ARM Cortex              | 90        | 1.04%   |
| AMD FX                  | 80        | 0.92%   |
| AMD Ryzen 3             | 62        | 0.71%   |
| Intel Core 2 Quad       | 61        | 0.7%    |
| Intel Pentium Silver    | 59        | 0.68%   |
| AMD G                   | 58        | 0.67%   |
| Intel Pentium Dual-Core | 52        | 0.6%    |
| AMD Ryzen 9             | 49        | 0.56%   |
| AMD EPYC                | 45        | 0.52%   |
| Intel Core 2            | 34        | 0.39%   |
| AMD Ryzen Embedded      | 32        | 0.37%   |
| AMD Athlon              | 30        | 0.35%   |
| AMD Ryzen 5 PRO         | 29        | 0.33%   |
| Intel Pentium 4         | 27        | 0.31%   |
| Intel Xeon Silver       | 26        | 0.3%    |
| AMD A10                 | 26        | 0.3%    |
| Intel Pentium Gold      | 25        | 0.29%   |
| Intel Genuine           | 25        | 0.29%   |
| AMD A6                  | 25        | 0.29%   |
| AMD A4                  | 25        | 0.29%   |
| AMD A8                  | 23        | 0.27%   |
| Intel Core i9           | 22        | 0.25%   |
| AMD Phenom II X4        | 22        | 0.25%   |
| AMD Opteron             | 21        | 0.24%   |
| AMD E                   | 21        | 0.24%   |
| AMD Athlon 64 X2        | 21        | 0.24%   |
| Intel Pentium M         | 19        | 0.22%   |
| Intel Pentium Dual      | 19        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 3887      | 44.77%  |
| 2       | 2674      | 30.8%   |
| Unknown | 499       | 5.75%   |
| 8       | 497       | 5.72%   |
| 6       | 375       | 4.32%   |
| 16      | 240       | 2.76%   |
| 12      | 228       | 2.63%   |
| 1       | 137       | 1.58%   |
| 24      | 47        | 0.54%   |
| 10      | 24        | 0.28%   |
| 32      | 22        | 0.25%   |
| 20      | 16        | 0.18%   |
| 64      | 9         | 0.1%    |
| 3       | 7         | 0.08%   |
| 48      | 5         | 0.06%   |
| 28      | 4         | 0.05%   |
| 14      | 4         | 0.05%   |
| 36      | 3         | 0.03%   |
| 128     | 2         | 0.02%   |
| 40      | 1         | 0.01%   |
| 11      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 8071      | 93.44%  |
| 2       | 336       | 3.89%   |
| Unknown | 225       | 2.6%    |
| 4       | 5         | 0.06%   |
| 8       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4591      | 53.04%  |
| 2       | 3508      | 40.53%  |
| Unknown | 556       | 6.42%   |
| 4       | 1         | 0.01%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 1088      | 12.54%  |
| Haswell         | 925       | 10.66%  |
| Silvermont      | 701       | 8.08%   |
| IvyBridge       | 659       | 7.6%    |
| SandyBridge     | 559       | 6.44%   |
| Skylake         | 518       | 5.97%   |
| Unknown         | 384       | 4.43%   |
| Penryn          | 350       | 4.03%   |
| Goldmont plus   | 340       | 3.92%   |
| Puma            | 317       | 3.65%   |
| Broadwell       | 303       | 3.49%   |
| Goldmont        | 249       | 2.87%   |
| Westmere        | 238       | 2.74%   |
| Zen 2           | 200       | 2.31%   |
| Core            | 192       | 2.21%   |
| Bonnell         | 176       | 2.03%   |
| Zen             | 173       | 1.99%   |
| Zen+            | 163       | 1.88%   |
| Jaguar          | 150       | 1.73%   |
| CometLake       | 134       | 1.54%   |
| Nehalem         | 128       | 1.48%   |
| Piledriver      | 108       | 1.24%   |
| Zen 3           | 98        | 1.13%   |
| Bobcat          | 96        | 1.11%   |
| K10             | 92        | 1.06%   |
| TigerLake       | 55        | 0.63%   |
| Steamroller     | 54        | 0.62%   |
| NetBurst        | 46        | 0.53%   |
| Excavator       | 43        | 0.5%    |
| K8 Hammer       | 39        | 0.45%   |
| P6              | 37        | 0.43%   |
| IceLake         | 27        | 0.31%   |
| Bulldozer       | 14        | 0.16%   |
| K10 Llano       | 11        | 0.13%   |
| Geode           | 5         | 0.06%   |
| K8 & K10 hybrid | 3         | 0.03%   |
| K6              | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 5122      | 60.07%  |
| AMD                                          | 1325      | 15.54%  |
| Nvidia                                       | 1115      | 13.08%  |
| Matrox Electronics Systems                   | 504       | 5.91%   |
| ASPEED Technology                            | 426       | 5%      |
| XGI Technology (eXtreme Graphics Innovation) | 8         | 0.09%   |
| VIA Technologies                             | 6         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 6         | 0.07%   |
| S3 Graphics                                  | 5         | 0.06%   |
| Silicon Motion                               | 2         | 0.02%   |
| Cirrus Logic                                 | 2         | 0.02%   |
| Tseng Labs                                   | 1         | 0.01%   |
| Trident Microsystems                         | 1         | 0.01%   |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.01%   |
| Huawei Technologies                          | 1         | 0.01%   |
| ATI                                          | 1         | 0.01%   |
| 3DLabs                                       | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 426       | 4.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 351       | 4.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 333       | 3.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 319       | 3.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 297       | 3.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 297       | 3.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 225       | 2.59%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 217       | 2.5%    |
| Intel HD Graphics 620                                                                    | 210       | 2.42%   |
| Intel HD Graphics 530                                                                    | 200       | 2.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 200       | 2.3%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 160       | 1.84%   |
| Intel HD Graphics 500                                                                    | 160       | 1.84%   |
| Intel UHD Graphics 620                                                                   | 144       | 1.66%   |
| Intel HD Graphics 5500                                                                   | 144       | 1.66%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 136       | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 130       | 1.5%    |
| Intel JasperLake [UHD Graphics]                                                          | 114       | 1.31%   |
| Matrox Electronics Systems G200eR2                                                       | 107       | 1.23%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 106       | 1.22%   |
| Intel HD Graphics 630                                                                    | 105       | 1.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 89        | 1.02%   |
| Intel Core Processor Integrated Graphics Controller                                      | 87        | 1%      |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 87        | 1%      |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 85        | 0.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 84        | 0.97%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 83        | 0.95%   |
| AMD ES1000                                                                               | 78        | 0.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 77        | 0.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 75        | 0.86%   |
| Matrox Electronics Systems MGA G200EH                                                    | 69        | 0.79%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 69        | 0.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 68        | 0.78%   |
| AMD Renoir                                                                               | 68        | 0.78%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 67        | 0.77%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 62        | 0.71%   |
| Intel HD Graphics 610                                                                    | 61        | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 56        | 0.64%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 53        | 0.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 52        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 4413      | 50.88%  |
| 1 x AMD                                  | 1182      | 13.63%  |
| 1 x Nvidia                               | 774       | 8.92%   |
| Other                                    | 589       | 6.79%   |
| 1 x Matrox                               | 499       | 5.75%   |
| 1 x ASPEED                               | 397       | 4.58%   |
| 2 x Intel                                | 306       | 3.53%   |
| Intel + Nvidia                           | 295       | 3.4%    |
| Intel + AMD                              | 86        | 0.99%   |
| 2 x AMD                                  | 28        | 0.32%   |
| AMD + Nvidia                             | 27        | 0.31%   |
| Intel + ASPEED                           | 19        | 0.22%   |
| 2 x Nvidia                               | 9         | 0.1%    |
| 1 x XGI                                  | 8         | 0.09%   |
| Nvidia + ASPEED                          | 8         | 0.09%   |
| 1 x VIA                                  | 6         | 0.07%   |
| 1 x SiS                                  | 6         | 0.07%   |
| 1 x S3 Graphics                          | 4         | 0.05%   |
| AMD + ASPEED                             | 3         | 0.03%   |
| 1 x Silicon Motion                       | 2         | 0.02%   |
| Intel + Matrox                           | 2         | 0.02%   |
| 1 x Cirrus Logic                         | 2         | 0.02%   |
| 2 x Intel + 1 x Nvidia                   | 1         | 0.01%   |
| 1 x Tseng Labs                           | 1         | 0.01%   |
| 1 x Trident Microsystems                 | 1         | 0.01%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.01%   |
| Nvidia + Matrox                          | 1         | 0.01%   |
| Nvidia + Huawei Technologies             | 1         | 0.01%   |
| Intel + AMD + 1 x Nvidia                 | 1         | 0.01%   |
| AMD + Matrox                             | 1         | 0.01%   |
| 1 x 3DLabs                               | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 7383      | 85.18%  |
| Unknown     | 720       | 8.31%   |
| Proprietary | 565       | 6.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7733      | 88.92%  |
| 1.01-2.0   | 262       | 3.01%   |
| 0.01-0.5   | 205       | 2.36%   |
| 0.51-1.0   | 164       | 1.89%   |
| 3.01-4.0   | 140       | 1.61%   |
| 7.01-8.0   | 97        | 1.12%   |
| 5.01-6.0   | 57        | 0.66%   |
| 2.01-3.0   | 22        | 0.25%   |
| 8.01-16.0  | 16        | 0.18%   |
| 4.01-5.0   | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 318       | 11.25%  |
| Samsung Electronics     | 314       | 11.11%  |
| AU Optronics            | 305       | 10.79%  |
| Dell                    | 200       | 7.08%   |
| Chimei Innolux          | 194       | 6.86%   |
| BOE                     | 185       | 6.55%   |
| Goldstar                | 155       | 5.48%   |
| Lenovo                  | 126       | 4.46%   |
| Acer                    | 90        | 3.18%   |
| Hewlett-Packard         | 89        | 3.15%   |
| BenQ                    | 76        | 2.69%   |
| Apple                   | 72        | 2.55%   |
| AOC                     | 72        | 2.55%   |
| Philips                 | 70        | 2.48%   |
| Ancor Communications    | 60        | 2.12%   |
| Sharp                   | 36        | 1.27%   |
| Iiyama                  | 34        | 1.2%    |
| Chi Mei Optoelectronics | 34        | 1.2%    |
| ViewSonic               | 33        | 1.17%   |
| InfoVision              | 23        | 0.81%   |
| LG Electronics          | 22        | 0.78%   |
| ASUSTek Computer        | 22        | 0.78%   |
| Sony                    | 20        | 0.71%   |
| PANDA                   | 17        | 0.6%    |
| NEC Computers           | 17        | 0.6%    |
| Eizo                    | 16        | 0.57%   |
| Fujitsu Siemens         | 14        | 0.5%    |
| LG Philips              | 13        | 0.46%   |
| Toshiba                 | 12        | 0.42%   |
| HannStar                | 12        | 0.42%   |
| Vizio                   | 9         | 0.32%   |
| unknown                 | 9         | 0.32%   |
| Panasonic               | 9         | 0.32%   |
| Sceptre Tech            | 8         | 0.28%   |
| LGD                     | 8         | 0.28%   |
| MSI                     | 7         | 0.25%   |
| CSO                     | 7         | 0.25%   |
| Idek Iiyama             | 6         | 0.21%   |
| CPT                     | 6         | 0.21%   |
| JDI                     | 5         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 21        | 0.72%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 15        | 0.52%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 11        | 0.38%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 11        | 0.38%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch              | 10        | 0.34%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch              | 10        | 0.34%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 10        | 0.34%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                | 9         | 0.31%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch              | 9         | 0.31%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 9         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 9         | 0.31%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 9         | 0.31%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch | 8         | 0.28%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 8         | 0.28%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 8         | 0.28%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 8         | 0.28%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 8         | 0.28%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 8         | 0.28%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch              | 8         | 0.28%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 8         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 8         | 0.28%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch        | 8         | 0.28%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 8         | 0.28%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 8         | 0.28%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 8         | 0.28%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 7         | 0.24%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 7         | 0.24%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 7         | 0.24%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch              | 7         | 0.24%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 7         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch     | 7         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch      | 7         | 0.24%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 7         | 0.24%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 7         | 0.24%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 6         | 0.21%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch          | 6         | 0.21%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch              | 6         | 0.21%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 6         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch      | 6         | 0.21%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch     | 6         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1083      | 39.01%  |
| 1366x768 (WXGA)    | 570       | 20.53%  |
| 3840x2160 (4K)     | 145       | 5.22%   |
| 2560x1440 (QHD)    | 145       | 5.22%   |
| 1600x900 (HD+)     | 133       | 4.79%   |
| 1280x1024 (SXGA)   | 110       | 3.96%   |
| 1280x800 (WXGA)    | 106       | 3.82%   |
| 1920x1200 (WUXGA)  | 78        | 2.81%   |
| 1440x900 (WXGA+)   | 73        | 2.63%   |
| 1680x1050 (WSXGA+) | 71        | 2.56%   |
| 2560x1080          | 30        | 1.08%   |
| 3440x1440          | 29        | 1.04%   |
| 1024x600           | 25        | 0.9%    |
| Unknown            | 25        | 0.9%    |
| 1024x768 (XGA)     | 16        | 0.58%   |
| 1360x768           | 13        | 0.47%   |
| 1920x540           | 11        | 0.4%    |
| 1600x1200          | 11        | 0.4%    |
| 3200x1800 (QHD+)   | 10        | 0.36%   |
| 2560x1600          | 9         | 0.32%   |
| 2256x1504          | 8         | 0.29%   |
| 2880x1620          | 7         | 0.25%   |
| 3840x1080          | 6         | 0.22%   |
| 2880x1800          | 6         | 0.22%   |
| 3840x1600          | 3         | 0.11%   |
| 3840x1200          | 3         | 0.11%   |
| 3000x2000          | 3         | 0.11%   |
| 2160x1440          | 3         | 0.11%   |
| 2048x1152          | 3         | 0.11%   |
| 1400x1050          | 3         | 0.11%   |
| 5760x2160          | 2         | 0.07%   |
| 5760x1080          | 2         | 0.07%   |
| 3840x2400          | 2         | 0.07%   |
| 2736x1824          | 2         | 0.07%   |
| 1280x720 (HD)      | 2         | 0.07%   |
| 7680x2160          | 1         | 0.04%   |
| 720x1280           | 1         | 0.04%   |
| 5760x1256          | 1         | 0.04%   |
| 5760x1200          | 1         | 0.04%   |
| 5120x1440          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 552       | 19.53%  |
| 13      | 505       | 17.87%  |
| 24      | 229       | 8.1%    |
| 27      | 199       | 7.04%   |
| 21      | 176       | 6.23%   |
| 12      | 158       | 5.59%   |
| 23      | 149       | 5.27%   |
| Unknown | 143       | 5.06%   |
| 19      | 130       | 4.6%    |
| 17      | 107       | 3.79%   |
| 14      | 70        | 2.48%   |
| 31      | 61        | 2.16%   |
| 11      | 54        | 1.91%   |
| 18      | 47        | 1.66%   |
| 34      | 38        | 1.34%   |
| 22      | 38        | 1.34%   |
| 20      | 28        | 0.99%   |
| 10      | 25        | 0.88%   |
| 29      | 10        | 0.35%   |
| 40      | 9         | 0.32%   |
| 16      | 9         | 0.32%   |
| 54      | 7         | 0.25%   |
| 42      | 7         | 0.25%   |
| 9       | 7         | 0.25%   |
| 64      | 6         | 0.21%   |
| 39      | 5         | 0.18%   |
| 32      | 5         | 0.18%   |
| 28      | 5         | 0.18%   |
| 26      | 5         | 0.18%   |
| 25      | 5         | 0.18%   |
| 52      | 4         | 0.14%   |
| 50      | 3         | 0.11%   |
| 49      | 3         | 0.11%   |
| 46      | 3         | 0.11%   |
| 41      | 3         | 0.11%   |
| 37      | 3         | 0.11%   |
| 33      | 3         | 0.11%   |
| 48      | 2         | 0.07%   |
| 43      | 2         | 0.07%   |
| 35      | 2         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 965       | 34.56%  |
| 501-600     | 539       | 19.31%  |
| 201-300     | 452       | 16.19%  |
| 401-500     | 355       | 12.71%  |
| Unknown     | 143       | 5.12%   |
| 351-400     | 122       | 4.37%   |
| 601-700     | 99        | 3.55%   |
| 701-800     | 47        | 1.68%   |
| 1001-1500   | 33        | 1.18%   |
| 801-900     | 18        | 0.64%   |
| 901-1000    | 12        | 0.43%   |
| 101-200     | 6         | 0.21%   |
| 1-100       | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1963      | 74.08%  |
| 16/10   | 323       | 12.19%  |
| Unknown | 117       | 4.42%   |
| 5/4     | 98        | 3.7%    |
| 21/9    | 55        | 2.08%   |
| 3/2     | 44        | 1.66%   |
| 4/3     | 37        | 1.4%    |
| 6/5     | 4         | 0.15%   |
| 32/9    | 4         | 0.15%   |
| 3.18    | 1         | 0.04%   |
| 11/10   | 1         | 0.04%   |
| 1.96    | 1         | 0.04%   |
| 1.00    | 1         | 0.04%   |
| 0.46    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 499       | 17.78%  |
| 81-90          | 471       | 16.79%  |
| 91-100         | 429       | 15.29%  |
| 301-350        | 208       | 7.41%   |
| 151-200        | 171       | 6.09%   |
| 61-70          | 159       | 5.67%   |
| Unknown        | 143       | 5.1%    |
| 101-110        | 135       | 4.81%   |
| 351-500        | 115       | 4.1%    |
| 71-80          | 86        | 3.06%   |
| 141-150        | 85        | 3.03%   |
| 251-300        | 79        | 2.82%   |
| 121-130        | 60        | 2.14%   |
| 51-60          | 53        | 1.89%   |
| 501-1000       | 37        | 1.32%   |
| 41-50          | 28        | 1%      |
| More than 1000 | 25        | 0.89%   |
| 111-120        | 9         | 0.32%   |
| 131-140        | 8         | 0.29%   |
| 1-40           | 6         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 884       | 31.97%  |
| 101-120       | 747       | 27.02%  |
| 121-160       | 722       | 26.11%  |
| 161-240       | 199       | 7.2%    |
| Unknown       | 143       | 5.17%   |
| More than 240 | 49        | 1.77%   |
| 1-50          | 21        | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5994      | 68.75%  |
| 1     | 2422      | 27.78%  |
| 2     | 282       | 3.23%   |
| 3     | 19        | 0.22%   |
| 4     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 6141      | 50.93%  |
| Realtek Semiconductor             | 3090      | 25.63%  |
| Broadcom                          | 914       | 7.58%   |
| Qualcomm Atheros                  | 757       | 6.28%   |
| Marvell Technology Group          | 90        | 0.75%   |
| Ralink Technology                 | 83        | 0.69%   |
| TP-Link                           | 59        | 0.49%   |
| Mellanox Technologies             | 58        | 0.48%   |
| IMC Networks                      | 56        | 0.46%   |
| Ralink                            | 51        | 0.42%   |
| AMD                               | 51        | 0.42%   |
| Chelsio Communications            | 42        | 0.35%   |
| Nvidia                            | 41        | 0.34%   |
| D-Link System                     | 37        | 0.31%   |
| Edimax Technology                 | 34        | 0.28%   |
| Ericsson Business Mobile Networks | 28        | 0.23%   |
| MediaTek                          | 25        | 0.21%   |
| Sierra Wireless                   | 22        | 0.18%   |
| VIA Technologies                  | 20        | 0.17%   |
| U-Blox                            | 19        | 0.16%   |
| Huawei Technologies               | 19        | 0.16%   |
| Aquantia                          | 19        | 0.16%   |
| Xiaomi                            | 18        | 0.15%   |
| Samsung Electronics               | 18        | 0.15%   |
| Qualcomm Atheros Communications   | 18        | 0.15%   |
| Solarflare Communications         | 16        | 0.13%   |
| Apple                             | 16        | 0.13%   |
| American Megatrends               | 16        | 0.13%   |
| QLogic                            | 15        | 0.12%   |
| Emulex                            | 15        | 0.12%   |
| ASUSTek Computer                  | 15        | 0.12%   |
| 3Com                              | 13        | 0.11%   |
| IBM                               | 12        | 0.1%    |
| Google                            | 12        | 0.1%    |
| Hewlett-Packard                   | 11        | 0.09%   |
| Dell                              | 11        | 0.09%   |
| JMicron Technology                | 10        | 0.08%   |
| D-Link                            | 9         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 8         | 0.07%   |
| Qualcomm                          | 8         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 2521      | 16.89%  |
| Intel I211 Gigabit Network Connection                                         | 1045      | 7%      |
| Intel I210 Gigabit Network Connection                                         | 705       | 4.72%   |
| Intel I350 Gigabit Network Connection                                         | 472       | 3.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 440       | 2.95%   |
| Intel 82574L Gigabit Network Connection                                       | 399       | 2.67%   |
| Intel Ethernet Connection I217-LM                                             | 237       | 1.59%   |
| Intel Ethernet Controller I225-V                                              | 214       | 1.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 210       | 1.41%   |
| Intel 82583V Gigabit Network Connection                                       | 187       | 1.25%   |
| Intel 82576 Gigabit Network Connection                                        | 178       | 1.19%   |
| Intel Wi-Fi 6 AX200                                                           | 174       | 1.17%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 165       | 1.11%   |
| Intel 82580 Gigabit Network Connection                                        | 163       | 1.09%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 163       | 1.09%   |
| Intel Wireless 8265 / 8275                                                    | 162       | 1.09%   |
| Intel Wireless 7265                                                           | 152       | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                             | 141       | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 137       | 0.92%   |
| Intel Wireless 7260                                                           | 134       | 0.9%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 132       | 0.88%   |
| Intel Wireless 8260                                                           | 121       | 0.81%   |
| Intel Wireless 3165                                                           | 121       | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                                         | 120       | 0.8%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 115       | 0.77%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 103       | 0.69%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 95        | 0.64%   |
| Intel Ethernet Connection (2) I219-V                                          | 93        | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 89        | 0.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 87        | 0.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 82        | 0.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 76        | 0.51%   |
| Intel Ethernet Connection I354                                                | 76        | 0.51%   |
| Intel Ethernet Connection I219-LM                                             | 76        | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 75        | 0.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 72        | 0.48%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 70        | 0.47%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 70        | 0.47%   |
| Intel 82579V Gigabit Network Connection                                       | 65        | 0.44%   |
| Intel Ethernet Connection (7) I219-V                                          | 63        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1839      | 51.45%  |
| Qualcomm Atheros                      | 620       | 17.35%  |
| Realtek Semiconductor                 | 428       | 11.98%  |
| Broadcom                              | 277       | 7.75%   |
| Ralink Technology                     | 83        | 2.32%   |
| TP-Link                               | 59        | 1.65%   |
| IMC Networks                          | 56        | 1.57%   |
| Ralink                                | 51        | 1.43%   |
| Edimax Technology                     | 34        | 0.95%   |
| MediaTek                              | 21        | 0.59%   |
| Sierra Wireless                       | 18        | 0.5%    |
| Qualcomm Atheros Communications       | 18        | 0.5%    |
| ASUSTek Computer                      | 15        | 0.42%   |
| D-Link System                         | 9         | 0.25%   |
| D-Link                                | 9         | 0.25%   |
| NetGear                               | 8         | 0.22%   |
| Dell                                  | 6         | 0.17%   |
| Mercucys                              | 3         | 0.08%   |
| Atheros                               | 3         | 0.08%   |
| AboCom Systems                        | 3         | 0.08%   |
| Belkin Components                     | 2         | 0.06%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Senao                                 | 1         | 0.03%   |
| Sagem                                 | 1         | 0.03%   |
| Qcom                                  | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| Marvell Technology Group              | 1         | 0.03%   |
| Linksys                               | 1         | 0.03%   |
| Gemtek                                | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |
| Accton Technology                     | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 174       | 4.82%   |
| Intel Wireless 8265 / 8275                                              | 162       | 4.49%   |
| Intel Wireless 7265                                                     | 152       | 4.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 137       | 3.8%    |
| Intel Wireless 7260                                                     | 134       | 3.71%   |
| Intel Wireless 8260                                                     | 121       | 3.35%   |
| Intel Wireless 3165                                                     | 121       | 3.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 89        | 2.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 87        | 2.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 82        | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 76        | 2.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 75        | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 72        | 2%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 70        | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 60        | 1.66%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 58        | 1.61%   |
| Intel Wireless 3160                                                     | 57        | 1.58%   |
| Intel Wireless-AC 9260                                                  | 56        | 1.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 53        | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 53        | 1.47%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 52        | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 40        | 1.11%   |
| Ralink RT5370 Wireless Adapter                                          | 39        | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 39        | 1.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 39        | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 35        | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 35        | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 33        | 0.91%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 33        | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 32        | 0.89%   |
| Intel Centrino Advanced-N 6235                                          | 32        | 0.89%   |
| Intel Wi-Fi 6 AX201                                                     | 31        | 0.86%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 31        | 0.86%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 31        | 0.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 31        | 0.86%   |
| Intel Centrino Advanced-N 6200                                          | 30        | 0.83%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 30        | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 29        | 0.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 29        | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 29        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5231      | 54.79%  |
| Realtek Semiconductor            | 2899      | 30.36%  |
| Broadcom                         | 706       | 7.39%   |
| Qualcomm Atheros                 | 197       | 2.06%   |
| Marvell Technology Group         | 89        | 0.93%   |
| AMD                              | 50        | 0.52%   |
| Nvidia                           | 41        | 0.43%   |
| Chelsio Communications           | 31        | 0.32%   |
| D-Link System                    | 25        | 0.26%   |
| VIA Technologies                 | 20        | 0.21%   |
| Aquantia                         | 19        | 0.2%    |
| Xiaomi                           | 18        | 0.19%   |
| Samsung Electronics              | 18        | 0.19%   |
| Solarflare Communications        | 16        | 0.17%   |
| American Megatrends              | 16        | 0.17%   |
| QLogic                           | 15        | 0.16%   |
| Emulex                           | 14        | 0.15%   |
| Apple                            | 14        | 0.15%   |
| IBM                              | 12        | 0.13%   |
| 3Com                             | 12        | 0.13%   |
| JMicron Technology               | 10        | 0.1%    |
| Google                           | 10        | 0.1%    |
| Qualcomm                         | 8         | 0.08%   |
| Silicon Integrated Systems [SiS] | 6         | 0.06%   |
| Novatel Wireless                 | 6         | 0.06%   |
| ICS Advent                       | 6         | 0.06%   |
| Huawei Technologies              | 6         | 0.06%   |
| Insyde Software                  | 4         | 0.04%   |
| OPPO Electronics                 | 3         | 0.03%   |
| National Semiconductor           | 3         | 0.03%   |
| Microsoft                        | 3         | 0.03%   |
| Davicom Semiconductor            | 3         | 0.03%   |
| Cisco Systems                    | 3         | 0.03%   |
| ADMtek                           | 3         | 0.03%   |
| Tehuti Networks                  | 2         | 0.02%   |
| SysKonnect                       | 2         | 0.02%   |
| Silicom                          | 2         | 0.02%   |
| Realtek                          | 2         | 0.02%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.02%   |
| MYRICOM                          | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 2521      | 22.88%  |
| Intel I211 Gigabit Network Connection                                         | 1045      | 9.48%   |
| Intel I210 Gigabit Network Connection                                         | 705       | 6.4%    |
| Intel I350 Gigabit Network Connection                                         | 472       | 4.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 440       | 3.99%   |
| Intel 82574L Gigabit Network Connection                                       | 399       | 3.62%   |
| Intel Ethernet Connection I217-LM                                             | 237       | 2.15%   |
| Intel Ethernet Controller I225-V                                              | 214       | 1.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 210       | 1.91%   |
| Intel 82583V Gigabit Network Connection                                       | 187       | 1.7%    |
| Intel 82576 Gigabit Network Connection                                        | 178       | 1.62%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 165       | 1.5%    |
| Intel 82580 Gigabit Network Connection                                        | 163       | 1.48%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 163       | 1.48%   |
| Realtek RTL8125 2.5GbE Controller                                             | 132       | 1.2%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 132       | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                                         | 120       | 1.09%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 115       | 1.04%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 103       | 0.93%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 95        | 0.86%   |
| Intel Ethernet Connection (2) I219-V                                          | 93        | 0.84%   |
| Intel Ethernet Connection I354                                                | 76        | 0.69%   |
| Intel Ethernet Connection I219-LM                                             | 76        | 0.69%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 70        | 0.64%   |
| Intel 82579V Gigabit Network Connection                                       | 65        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                                          | 63        | 0.57%   |
| Intel Ethernet Connection X553 1GbE                                           | 60        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 57        | 0.52%   |
| Intel Ethernet Connection I217-V                                              | 54        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                         | 54        | 0.49%   |
| Intel Ethernet Controller I226-V                                              | 52        | 0.47%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 49        | 0.44%   |
| Intel Ethernet Controller X550                                                | 48        | 0.44%   |
| Intel Ethernet Connection (3) I218-LM                                         | 46        | 0.42%   |
| Intel 82577LM Gigabit Network Connection                                      | 45        | 0.41%   |
| Intel Ethernet Connection (4) I219-LM                                         | 44        | 0.4%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 44        | 0.4%    |
| Intel Ethernet Connection I218-LM                                             | 42        | 0.38%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 40        | 0.36%   |
| Intel Ethernet Connection (4) I219-V                                          | 40        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 8191      | 69.44%  |
| WiFi     | 3310      | 28.06%  |
| Unknown  | 182       | 1.54%   |
| Modem    | 113       | 0.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 7643      | 81.66%  |
| WiFi     | 1679      | 17.94%  |
| Unknown  | 25        | 0.27%   |
| Modem    | 13        | 0.14%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3037      | 34.8%   |
| 1     | 1493      | 17.11%  |
| 4     | 1320      | 15.13%  |
| 3     | 1082      | 12.4%   |
| 6     | 681       | 7.8%    |
| 5     | 508       | 5.82%   |
| 8     | 193       | 2.21%   |
| 0     | 144       | 1.65%   |
| 7     | 112       | 1.28%   |
| 10    | 56        | 0.64%   |
| 9     | 50        | 0.57%   |
| 12    | 18        | 0.21%   |
| 14    | 10        | 0.11%   |
| 11    | 7         | 0.08%   |
| 13    | 6         | 0.07%   |
| 16    | 4         | 0.05%   |
| 15    | 3         | 0.03%   |
| 20    | 2         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7637      | 86.09%  |
| Yes  | 1234      | 13.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1244      | 56.39%  |
| Broadcom                        | 162       | 7.34%   |
| Apple                           | 133       | 6.03%   |
| Qualcomm Atheros Communications | 127       | 5.76%   |
| Realtek Semiconductor           | 115       | 5.21%   |
| IMC Networks                    | 107       | 4.85%   |
| Cambridge Silicon Radio         | 84        | 3.81%   |
| Lite-On Technology              | 45        | 2.04%   |
| Foxconn / Hon Hai               | 43        | 1.95%   |
| ASUSTek Computer                | 38        | 1.72%   |
| Dell                            | 31        | 1.41%   |
| Hewlett-Packard                 | 22        | 1%      |
| Alps Electric                   | 16        | 0.73%   |
| Ralink                          | 8         | 0.36%   |
| MediaTek                        | 8         | 0.36%   |
| Realtek                         | 7         | 0.32%   |
| Integrated System Solution      | 3         | 0.14%   |
| Toshiba                         | 2         | 0.09%   |
| HTC (High Tech Computer)        | 2         | 0.09%   |
| Creative Technology             | 2         | 0.09%   |
| TP-Link                         | 1         | 0.05%   |
| Qcom                            | 1         | 0.05%   |
| Opticis                         | 1         | 0.05%   |
| Micro Star International        | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| Dynex                           | 1         | 0.05%   |
| Bluetooth Device                | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 572       | 25.88%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 171       | 7.74%   |
| Intel AX200 Bluetooth                                       | 167       | 7.56%   |
| Intel AX201 Bluetooth                                       | 117       | 5.29%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 84        | 3.8%    |
| Intel Wireless-AC 3168 Bluetooth                            | 72        | 3.26%   |
| Apple Bluetooth Host Controller                             | 58        | 2.62%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 56        | 2.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 49        | 2.22%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 46        | 2.08%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 46        | 2.08%   |
| Realtek  Bluetooth 4.2 Adapter                              | 40        | 1.81%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 28        | 1.27%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 28        | 1.27%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 27        | 1.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 25        | 1.13%   |
| Intel AX210 Bluetooth                                       | 24        | 1.09%   |
| Realtek  Bluetooth Adapter                                  | 23        | 1.04%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 23        | 1.04%   |
| IMC Networks Realtek Bluetooth Adapter                      | 19        | 0.86%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 18        | 0.81%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 17        | 0.77%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 16        | 0.72%   |
| Lite-On Atheros AR3012 Bluetooth                            | 15        | 0.68%   |
| Realtek  Bluetooth 4.0 Adapter                              | 13        | 0.59%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 13        | 0.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 12        | 0.54%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 12        | 0.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 12        | 0.54%   |
| Dell DW375 Bluetooth Module                                 | 12        | 0.54%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 12        | 0.54%   |
| Apple Built-in iSight (no firmware loaded)                  | 12        | 0.54%   |
| Realtek Bluetooth Radio                                     | 11        | 0.5%    |
| Realtek RTL8723B Bluetooth                                  | 10        | 0.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 10        | 0.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 10        | 0.45%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 10        | 0.45%   |
| Alps Electric UGTZ4 Bluetooth                               | 10        | 0.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 9         | 0.41%   |
| Ralink RT3290 Bluetooth                                     | 8         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 5065      | 66.38%  |
| AMD                                          | 1382      | 18.11%  |
| Nvidia                                       | 796       | 10.43%  |
| C-Media Electronics                          | 69        | 0.9%    |
| Logitech                                     | 29        | 0.38%   |
| Creative Labs                                | 25        | 0.33%   |
| Texas Instruments                            | 22        | 0.29%   |
| GN Netcom                                    | 15        | 0.2%    |
| Realtek Semiconductor                        | 13        | 0.17%   |
| Lenovo                                       | 13        | 0.17%   |
| VIA Technologies                             | 12        | 0.16%   |
| SteelSeries ApS                              | 12        | 0.16%   |
| JMTek                                        | 12        | 0.16%   |
| Silicon Integrated Systems [SiS]             | 10        | 0.13%   |
| Kingston Technology                          | 8         | 0.1%    |
| Creative Technology                          | 8         | 0.1%    |
| Zoran Co. Personal Media Division (Nogatech) | 7         | 0.09%   |
| Generalplus Technology                       | 7         | 0.09%   |
| Sony                                         | 6         | 0.08%   |
| Focusrite-Novation                           | 6         | 0.08%   |
| Blue Microphones                             | 6         | 0.08%   |
| BEHRINGER International                      | 6         | 0.08%   |
| Yamaha                                       | 5         | 0.07%   |
| ESS Technology                               | 5         | 0.07%   |
| Corsair                                      | 5         | 0.07%   |
| XMOS                                         | 4         | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 4         | 0.05%   |
| Plantronics                                  | 4         | 0.05%   |
| Cambridge Silicon Radio                      | 4         | 0.05%   |
| ASUSTek Computer                             | 4         | 0.05%   |
| ULi Electronics                              | 3         | 0.04%   |
| M-Audio                                      | 3         | 0.04%   |
| KTMicro                                      | 3         | 0.04%   |
| FiiO Electronics Technology                  | 3         | 0.04%   |
| Trust                                        | 2         | 0.03%   |
| Tenx Technology                              | 2         | 0.03%   |
| RODE Microphones                             | 2         | 0.03%   |
| Microsoft                                    | 2         | 0.03%   |
| Micro Star International                     | 2         | 0.03%   |
| Hewlett-Packard                              | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 469       | 5.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 436       | 4.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 435       | 4.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 402       | 4.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 399       | 4.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 302       | 3.3%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 291       | 3.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 276       | 3.02%   |
| AMD FCH Azalia Controller                                                                         | 259       | 2.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 246       | 2.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 217       | 2.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 206       | 2.25%   |
| Intel 8 Series HD Audio Controller                                                                | 205       | 2.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 204       | 2.23%   |
| AMD Kabini HDMI/DP Audio                                                                          | 198       | 2.17%   |
| Intel Broadwell-U Audio Controller                                                                | 194       | 2.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 188       | 2.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 187       | 2.04%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 179       | 1.96%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 160       | 1.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 139       | 1.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 138       | 1.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 133       | 1.45%   |
| Intel 200 Series PCH HD Audio                                                                     | 132       | 1.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 132       | 1.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 128       | 1.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 125       | 1.37%   |
| Intel Jasper Lake HD Audio                                                                        | 114       | 1.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 108       | 1.18%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 104       | 1.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 93        | 1.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 79        | 0.86%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 78        | 0.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 73        | 0.8%    |
| Intel Comet Lake PCH cAVS                                                                         | 64        | 0.7%    |
| Nvidia High Definition Audio Controller                                                           | 55        | 0.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 55        | 0.6%    |
| AMD Wrestler HDMI Audio                                                                           | 55        | 0.6%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 54        | 0.59%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 51        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1629      | 18.34%  |
| SK hynix            | 1238      | 13.94%  |
| Kingston            | 1135      | 12.78%  |
| Unknown             | 1084      | 12.2%   |
| Micron Technology   | 730       | 8.22%   |
| Crucial             | 719       | 8.09%   |
| Corsair             | 380       | 4.28%   |
| G.Skill             | 286       | 3.22%   |
| Unknown             | 219       | 2.47%   |
| Transcend           | 143       | 1.61%   |
| A-DATA Technology   | 126       | 1.42%   |
| Unknown (ABCD)      | 120       | 1.35%   |
| Ramaxel Technology  | 112       | 1.26%   |
| Nanya Technology    | 110       | 1.24%   |
| Elpida              | 90        | 1.01%   |
| Team                | 63        | 0.71%   |
| Patriot             | 61        | 0.69%   |
| Apacer              | 42        | 0.47%   |
| Hewlett-Packard     | 40        | 0.45%   |
| Kimtigo             | 36        | 0.41%   |
| Toshiba             | 32        | 0.36%   |
| Smart               | 32        | 0.36%   |
| PNY                 | 26        | 0.29%   |
| GOODRAM             | 25        | 0.28%   |
| Avant               | 22        | 0.25%   |
| Teikon              | 19        | 0.21%   |
| ATP                 | 19        | 0.21%   |
| Timetec             | 16        | 0.18%   |
| Super Talent        | 14        | 0.16%   |
| Silicon Power       | 13        | 0.15%   |
| Innodisk            | 12        | 0.14%   |
| AMD                 | 12        | 0.14%   |
| Tigo                | 10        | 0.11%   |
| HPE                 | 9         | 0.1%    |
| GeIL                | 9         | 0.1%    |
| 48spaces            | 8         | 0.09%   |
| Qimonda             | 7         | 0.08%   |
| Neo Forza           | 7         | 0.08%   |
| Goldkey             | 7         | 0.08%   |
| Smart Modular       | 6         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 219       | 2.3%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 122       | 1.28%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 113       | 1.19%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 72        | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 70        | 0.73%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 51        | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 50        | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 50        | 0.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 48        | 0.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 42        | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 41        | 0.43%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 37        | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 37        | 0.39%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 37        | 0.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 37        | 0.39%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 36        | 0.38%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 35        | 0.37%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 31        | 0.33%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 30        | 0.31%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 29        | 0.3%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 28        | 0.29%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 28        | 0.29%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3                   | 28        | 0.29%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 28        | 0.29%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 27        | 0.28%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 27        | 0.28%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 26        | 0.27%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s        | 26        | 0.27%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s        | 26        | 0.27%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 26        | 0.27%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s      | 26        | 0.27%   |
| Unknown RAM Module 8GB 1600MT/s                              | 24        | 0.25%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 24        | 0.25%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 24        | 0.25%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s          | 24        | 0.25%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 24        | 0.25%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s        | 24        | 0.25%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 22        | 0.23%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s          | 22        | 0.23%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s        | 22        | 0.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR3            | 3924      | 50.26%  |
| DDR4            | 2790      | 35.73%  |
| DDR2            | 427       | 5.47%   |
| Unknown         | 240       | 3.07%   |
| LPDDR4          | 169       | 2.16%   |
| SDRAM           | 98        | 1.26%   |
| LPDDR3          | 70        | 0.9%    |
| DDR             | 61        | 0.78%   |
| DRAM            | 15        | 0.19%   |
| RAM             | 4         | 0.05%   |
| LPDDR5          | 4         | 0.05%   |
| DDR5            | 4         | 0.05%   |
| SRAM            | 1         | 0.01%   |
| Logical non-vol | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 4087      | 52.5%   |
| SODIMM       | 3434      | 44.11%  |
| Row Of Chips | 112       | 1.44%   |
| Unknown      | 64        | 0.82%   |
| Chip         | 49        | 0.63%   |
| FB-DIMM      | 27        | 0.35%   |
| RIMM         | 12        | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 2906      | 34.56%  |
| 4096   | 2833      | 33.69%  |
| 2048   | 1167      | 13.88%  |
| 16384  | 1029      | 12.24%  |
| 1024   | 245       | 2.91%   |
| 32768  | 159       | 1.89%   |
| 512    | 42        | 0.5%    |
| 256    | 8         | 0.1%    |
| 65536  | 5         | 0.06%   |
| 128    | 4         | 0.05%   |
| 32767  | 2         | 0.02%   |
| 131072 | 1         | 0.01%   |
| 129728 | 1         | 0.01%   |
| 6144   | 1         | 0.01%   |
| 4092   | 1         | 0.01%   |
| 2560   | 1         | 0.01%   |
| 1556   | 1         | 0.01%   |
| 64     | 1         | 0.01%   |
| 32     | 1         | 0.01%   |
| 8      | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 2463      | 29.67%  |
| 1333    | 1212      | 14.6%   |
| 2400    | 997       | 12.01%  |
| 2667    | 719       | 8.66%   |
| 2133    | 577       | 6.95%   |
| 3200    | 546       | 6.58%   |
| 667     | 281       | 3.39%   |
| 800     | 273       | 3.29%   |
| Unknown | 170       | 2.05%   |
| 1334    | 150       | 1.81%   |
| 2666    | 144       | 1.73%   |
| 1867    | 130       | 1.57%   |
| 1067    | 130       | 1.57%   |
| 1066    | 126       | 1.52%   |
| 1866    | 56        | 0.67%   |
| 3000    | 50        | 0.6%    |
| 533     | 43        | 0.52%   |
| 2933    | 42        | 0.51%   |
| 3600    | 39        | 0.47%   |
| 400     | 26        | 0.31%   |
| 4267    | 16        | 0.19%   |
| 975     | 11        | 0.13%   |
| 333     | 9         | 0.11%   |
| 1400    | 7         | 0.08%   |
| 266     | 7         | 0.08%   |
| 1332    | 6         | 0.07%   |
| 65535   | 5         | 0.06%   |
| 6400    | 5         | 0.06%   |
| 3400    | 5         | 0.06%   |
| 2134    | 5         | 0.06%   |
| 1033    | 5         | 0.06%   |
| 4266    | 4         | 0.05%   |
| 1200    | 4         | 0.05%   |
| 4800    | 3         | 0.04%   |
| 3534    | 3         | 0.04%   |
| 2048    | 3         | 0.04%   |
| 5200    | 2         | 0.02%   |
| 2600    | 2         | 0.02%   |
| 1639    | 2         | 0.02%   |
| 933     | 2         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Brother Industries    | 11        | 30.56%  |
| Hewlett-Packard       | 10        | 27.78%  |
| Seiko Epson           | 2         | 5.56%   |
| Prolific Technology   | 2         | 5.56%   |
| Lexmark International | 2         | 5.56%   |
| ELGIN                 | 2         | 5.56%   |
| Samsung Electronics   | 1         | 2.78%   |
| Ricoh                 | 1         | 2.78%   |
| QinHeng Electronics   | 1         | 2.78%   |
| Kyocera               | 1         | 2.78%   |
| Dymo-CoStar           | 1         | 2.78%   |
| Canon                 | 1         | 2.78%   |
| Apple                 | 1         | 2.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Computers | Percent |
|-------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                                                                     | 2         | 5.26%   |
| ELGIN L42PRO                                                                                                      | 2         | 5.26%   |
| Brother MFC-7360N                                                                                                 | 2         | 5.26%   |
| Brother HL-1430 Laser Printer                                                                                     | 2         | 5.26%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                                                                             | 1         | 2.63%   |
| Seiko Epson Printer                                                                                               | 1         | 2.63%   |
| Samsung ML-1610 Mono Laser Printer                                                                                | 1         | 2.63%   |
| Ricoh SP 112                                                                                                      | 1         | 2.63%   |
| QinHeng CH340S                                                                                                    | 1         | 2.63%   |
| Lexmark International SINDOH A603_A608 Print                                                                      | 1         | 2.63%   |
| Lexmark International Lexmark MS710 Print                                                                         | 1         | 2.63%   |
| Kyocera FS-1025MFP                                                                                                | 1         | 2.63%   |
| HP PNP Fax Null                                                                                                   | 1         | 2.63%   |
| HP LaserJet P3005                                                                                                 | 1         | 2.63%   |
| HP LaserJet 2200                                                                                                  | 1         | 2.63%   |
| HP LaserJet 1200                                                                                                  | 1         | 2.63%   |
| HP LaserJet 1012                                                                                                  | 1         | 2.63%   |
| HP HP LaserJet P2035 HP Print                                                                                     | 1         | 2.63%   |
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1         | 2.63%   |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer                        | 1         | 2.63%   |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer                                          | 1         | 2.63%   |
| HP HP Laser 107w                                                                                                  | 1         | 2.63%   |
| HP DeskJet 5850c                                                                                                  | 1         | 2.63%   |
| HP Color LaserJet CP1215                                                                                          | 1         | 2.63%   |
| Dymo-CoStar DYMO LabelWriter 450 DUO                                                                              | 1         | 2.63%   |
| Canon LBP2900                                                                                                     | 1         | 2.63%   |
| Brother MFC-L2685DW                                                                                               | 1         | 2.63%   |
| Brother MFC-J485DW                                                                                                | 1         | 2.63%   |
| Brother MFC-J200                                                                                                  | 1         | 2.63%   |
| Brother HL-L5200DW series                                                                                         | 1         | 2.63%   |
| Brother HL-L2310D series                                                                                          | 1         | 2.63%   |
| Brother HL-2030 Laser Printer                                                                                     | 1         | 2.63%   |
| Brother DCP-J100                                                                                                  | 1         | 2.63%   |
| Apple Gamesir-G3s 2.10                                                                                            | 1         | 2.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 7         | 77.78%  |
| Seiko Epson     | 1         | 11.11%  |
| Hewlett-Packard | 1         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 4         | 44.44%  |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 11.11%  |
| HP ScanJet 5300c/5370c                                                              | 1         | 11.11%  |
| Canon CanoScan LIDE 25                                                              | 1         | 11.11%  |
| Canon CanoScan LiDE 220                                                             | 1         | 11.11%  |
| Canon CanoScan LiDE 210                                                             | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 434       | 27.4%   |
| Acer                                   | 153       | 9.66%   |
| IMC Networks                           | 145       | 9.15%   |
| Realtek Semiconductor                  | 134       | 8.46%   |
| Microdia                               | 134       | 8.46%   |
| Sunplus Innovation Technology          | 82        | 5.18%   |
| Logitech                               | 79        | 4.99%   |
| Suyin                                  | 55        | 3.47%   |
| Lite-On Technology                     | 51        | 3.22%   |
| Quanta                                 | 32        | 2.02%   |
| Cheng Uei Precision Industry (Foxlink) | 32        | 2.02%   |
| Apple                                  | 32        | 2.02%   |
| Syntek                                 | 31        | 1.96%   |
| Silicon Motion                         | 23        | 1.45%   |
| Lenovo                                 | 21        | 1.33%   |
| Alcor Micro                            | 19        | 1.2%    |
| Z-Star Microelectronics                | 17        | 1.07%   |
| Ricoh                                  | 12        | 0.76%   |
| Luxvisions Innotech Limited            | 12        | 0.76%   |
| ALi                                    | 11        | 0.69%   |
| Importek                               | 8         | 0.51%   |
| ARC International                      | 7         | 0.44%   |
| Intel                                  | 4         | 0.25%   |
| Arkmicro Technologies                  | 4         | 0.25%   |
| Sonix Technology                       | 3         | 0.19%   |
| Primax Electronics                     | 3         | 0.19%   |
| OmniVision Technologies                | 3         | 0.19%   |
| WCM_USB                                | 2         | 0.13%   |
| Unknown                                | 2         | 0.13%   |
| Tripath Technology                     | 2         | 0.13%   |
| ShineTech                              | 2         | 0.13%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.13%   |
| Pixart Imaging                         | 2         | 0.13%   |
| Hewlett-Packard                        | 2         | 0.13%   |
| Genesys Logic                          | 2         | 0.13%   |
| Generalplus Technology                 | 2         | 0.13%   |
| GEMBIRD                                | 2         | 0.13%   |
| DigiTech                               | 2         | 0.13%   |
| Cubeternet                             | 2         | 0.13%   |
| Creative Technology                    | 2         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 132       | 8.26%   |
| Acer Integrated Camera                    | 70        | 4.38%   |
| IMC Networks Integrated Camera            | 44        | 2.75%   |
| Realtek Integrated_Webcam_HD              | 43        | 2.69%   |
| Chicony HD Webcam                         | 38        | 2.38%   |
| Lite-On Integrated Camera                 | 33        | 2.06%   |
| Microdia Integrated_Webcam_HD             | 32        | 2%      |
| Microdia Integrated Webcam                | 32        | 2%      |
| Chicony Lenovo Integrated Camera (0.3MP)  | 28        | 1.75%   |
| Sunplus Integrated_Webcam_HD              | 25        | 1.56%   |
| Realtek Realtek USB2.0 PC Camera          | 23        | 1.44%   |
| IMC Networks USB2.0 HD UVC WebCam         | 23        | 1.44%   |
| Logitech Webcam C270                      | 20        | 1.25%   |
| Logitech HD Pro Webcam C920               | 20        | 1.25%   |
| Acer Lenovo EasyCamera                    | 20        | 1.25%   |
| Chicony Chicony USB2.0 Camera             | 19        | 1.19%   |
| Chicony Integrated Camera (1280x720@30)   | 18        | 1.13%   |
| Apple FaceTime HD Camera                  | 18        | 1.13%   |
| IMC Networks EasyCamera                   | 16        | 1%      |
| Chicony Integrated Camera [ThinkPad]      | 15        | 0.94%   |
| Syntek Lenovo EasyCamera                  | 14        | 0.88%   |
| Lenovo Integrated Webcam [R5U877]         | 13        | 0.81%   |
| Chicony HP HD Webcam [Fixed]              | 13        | 0.81%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 12        | 0.75%   |
| Apple FaceTime HD Camera (Built-in)       | 12        | 0.75%   |
| Syntek EasyCamera                         | 11        | 0.69%   |
| Realtek USB Camera                        | 11        | 0.69%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 11        | 0.69%   |
| Acer SunplusIT Integrated Camera          | 11        | 0.69%   |
| Acer ThinkPad Integrated Camera           | 10        | 0.63%   |
| Microdia Laptop_Integrated_Webcam_HD      | 9         | 0.56%   |
| Microdia Dell Laptop Integrated Webcam HD | 9         | 0.56%   |
| Chicony USB2.0 VGA UVC WebCam             | 9         | 0.56%   |
| Chicony ThinkPad T490 Webcam              | 9         | 0.56%   |
| Chicony Lenovo EasyCamera                 | 9         | 0.56%   |
| Acer Lenovo Integrated Webcam             | 9         | 0.56%   |
| Realtek Lenovo EasyCamera                 | 8         | 0.5%    |
| Microdia Integrated Webcam HD             | 8         | 0.5%    |
| IMC Networks USB2.0 UVC HD Webcam         | 8         | 0.5%    |
| IMC Networks Integrated Webcam            | 8         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 165       | 39.29%  |
| Synaptics                  | 75        | 17.86%  |
| Upek                       | 50        | 11.9%   |
| AuthenTec                  | 36        | 8.57%   |
| Shenzhen Goodix Technology | 34        | 8.1%    |
| STMicroelectronics         | 26        | 6.19%   |
| Broadcom                   | 15        | 3.57%   |
| LighTuning Technology      | 9         | 2.14%   |
| Elan Microelectronics      | 4         | 0.95%   |
| Samsung Electronics        | 2         | 0.48%   |
| Focal-systems.Corp         | 2         | 0.48%   |
| Next Biometrics            | 1         | 0.24%   |
| DigitalPersona             | 1         | 0.24%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 54        | 12.86%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 47        | 11.19%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 31        | 7.38%   |
| Validity Sensors Synaptics WBDI                                              | 30        | 7.14%   |
| STMicroelectronics Fingerprint Reader                                        | 26        | 6.19%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 21        | 5%      |
| Shenzhen Goodix Fingerprint Reader                                           | 21        | 5%      |
| Validity Sensors VFS495 Fingerprint Reader                                   | 19        | 4.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 16        | 3.81%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 15        | 3.57%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 3.57%   |
| Shenzhen Goodix  FingerPrint Device                                          | 10        | 2.38%   |
| AuthenTec AES2810                                                            | 10        | 2.38%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 10        | 2.38%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                    | 6         | 1.43%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 6         | 1.43%   |
| Unknown                                                                      | 6         | 1.43%   |
| Validity Sensors VFS491                                                      | 5         | 1.19%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 5         | 1.19%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 5         | 1.19%   |
| AuthenTec AES1600                                                            | 5         | 1.19%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 4         | 0.95%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 4         | 0.95%   |
| Validity Sensors Fingerprint scanner                                         | 4         | 0.95%   |
| Elan ELAN WBF Fingerprint Sensor                                             | 4         | 0.95%   |
| Validity Sensors VFS Fingerprint sensor                                      | 3         | 0.71%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 3         | 0.71%   |
| Upek TCS5B Fingerprint sensor                                                | 3         | 0.71%   |
| Synaptics  WBDI                                                              | 3         | 0.71%   |
| Synaptics product 0x00be                                                     | 3         | 0.71%   |
| Shenzhen Goodix FingerPrint                                                  | 3         | 0.71%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 3         | 0.71%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 3         | 0.71%   |
| LighTuning EgisTec EH575                                                     | 3         | 0.71%   |
| Focal-systems.Corp FocalTech Fingerprint reader                              | 2         | 0.48%   |
| AuthenTec AuthenTec Inc. AES2660                                             | 2         | 0.48%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 2         | 0.48%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 0.24%   |
| Validity Sensors VFS101 Fingerprint Reader                                   | 1         | 0.24%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 0.24%   |

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
| 1     | 3382      | 38.02%  |
| 0     | 2985      | 33.55%  |
| 2     | 1550      | 17.42%  |
| 3     | 647       | 7.27%   |
| 4     | 247       | 2.78%   |
| 5     | 57        | 0.64%   |
| 6     | 18        | 0.2%    |
| 7     | 8         | 0.09%   |
| 9     | 1         | 0.01%   |
| 8     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 4873      | 57.57%  |
| Net/wireless             | 885       | 10.45%  |
| Bluetooth                | 842       | 9.95%   |
| Card reader              | 609       | 7.19%   |
| Fingerprint reader       | 351       | 4.15%   |
| Firewire controller      | 313       | 3.7%    |
| Sound                    | 150       | 1.77%   |
| Net/ethernet             | 117       | 1.38%   |
| Network                  | 111       | 1.31%   |
| Graphics card            | 101       | 1.19%   |
| Storage                  | 42        | 0.5%    |
| Modem                    | 23        | 0.27%   |
| Storage/ata              | 17        | 0.2%    |
| Storage/raid             | 13        | 0.15%   |
| Dvb card                 | 8         | 0.09%   |
| Storage/ide              | 6         | 0.07%   |
| Storage/nvme             | 3         | 0.04%   |
| Wireless                 | 1         | 0.01%   |

