OPNsense - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for OPNsense.

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

Total: 7758

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| AAEON Tech... | PCM-LN02 V2.0               | Desktop     | [046b7464b9](https://bsd-hardware.info/?probe=046b7464b9) | Jan 23, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [a271d3c547](https://bsd-hardware.info/?probe=a271d3c547) | Jan 22, 2023 |
| Intel         | NUC5i7RYB H73774-101        | Mini pc     | [9954516f1a](https://bsd-hardware.info/?probe=9954516f1a) | Jan 22, 2023 |
| AWOW          | AK50                        | Desktop     | [8c983f91e4](https://bsd-hardware.info/?probe=8c983f91e4) | Jan 22, 2023 |
| Lenovo        | ThinkPad T440p 20AN007FG... | Notebook    | [0883806434](https://bsd-hardware.info/?probe=0883806434) | Jan 22, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b938a15d41](https://bsd-hardware.info/?probe=b938a15d41) | Jan 22, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [0e9d5e53b9](https://bsd-hardware.info/?probe=0e9d5e53b9) | Jan 22, 2023 |
| PC Engines    | APU2                        | Desktop     | [658569ae16](https://bsd-hardware.info/?probe=658569ae16) | Jan 22, 2023 |
| Dell          | 0R5KP9 A04                  | Server      | [7b811598b5](https://bsd-hardware.info/?probe=7b811598b5) | Jan 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [8511097117](https://bsd-hardware.info/?probe=8511097117) | Jan 22, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [76840aba40](https://bsd-hardware.info/?probe=76840aba40) | Jan 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [d5d2ce1b39](https://bsd-hardware.info/?probe=d5d2ce1b39) | Jan 22, 2023 |
| Dell          | 0H723K A05                  | Server      | [561152d95d](https://bsd-hardware.info/?probe=561152d95d) | Jan 22, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [a17d96dde0](https://bsd-hardware.info/?probe=a17d96dde0) | Jan 22, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [c9d93a7c6f](https://bsd-hardware.info/?probe=c9d93a7c6f) | Jan 21, 2023 |
| ZOTAC         | ZBOX-ID92/ZBOX-IQ01         | Mini pc     | [d22d8ea874](https://bsd-hardware.info/?probe=d22d8ea874) | Jan 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [0bbf3bdc00](https://bsd-hardware.info/?probe=0bbf3bdc00) | Jan 21, 2023 |
| HP            | 1825                        | Desktop     | [2705218636](https://bsd-hardware.info/?probe=2705218636) | Jan 21, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [6b1a9b8d00](https://bsd-hardware.info/?probe=6b1a9b8d00) | Jan 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [8956f4503e](https://bsd-hardware.info/?probe=8956f4503e) | Jan 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [59c83cb9ee](https://bsd-hardware.info/?probe=59c83cb9ee) | Jan 21, 2023 |
| Fujitsu       | D3243-S1 S26361-D3243-S1    | Desktop     | [d69c3cae4c](https://bsd-hardware.info/?probe=d69c3cae4c) | Jan 21, 2023 |
| PC Engines    | APU2                        | Desktop     | [172844bd8b](https://bsd-hardware.info/?probe=172844bd8b) | Jan 21, 2023 |
| Datto         | 1000                        | Notebook    | [3d2880dd30](https://bsd-hardware.info/?probe=3d2880dd30) | Jan 21, 2023 |
| ASUSTek       | EB1035                      | All in one  | [7e39e23232](https://bsd-hardware.info/?probe=7e39e23232) | Jan 21, 2023 |
| AZW           | Green G1                    | Desktop     | [80498a4090](https://bsd-hardware.info/?probe=80498a4090) | Jan 21, 2023 |
| Lenovo        | SDK0J40705 WIN 342503995... | Desktop     | [0dc2013a9f](https://bsd-hardware.info/?probe=0dc2013a9f) | Jan 21, 2023 |
| AZW           | Green G1                    | Desktop     | [0c84e93ba7](https://bsd-hardware.info/?probe=0c84e93ba7) | Jan 21, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [e6873fe42f](https://bsd-hardware.info/?probe=e6873fe42f) | Jan 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [14089c4ab4](https://bsd-hardware.info/?probe=14089c4ab4) | Jan 21, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [b0fe0783d5](https://bsd-hardware.info/?probe=b0fe0783d5) | Jan 21, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [495563926c](https://bsd-hardware.info/?probe=495563926c) | Jan 21, 2023 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [7a21bfbfb9](https://bsd-hardware.info/?probe=7a21bfbfb9) | Jan 20, 2023 |
| Gigabyte      | F2A75M-HD2                  | Desktop     | [4770b980d6](https://bsd-hardware.info/?probe=4770b980d6) | Jan 20, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [f862df1689](https://bsd-hardware.info/?probe=f862df1689) | Jan 20, 2023 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [629c2e1a21](https://bsd-hardware.info/?probe=629c2e1a21) | Jan 20, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [6b331ff558](https://bsd-hardware.info/?probe=6b331ff558) | Jan 20, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [a4688e4059](https://bsd-hardware.info/?probe=a4688e4059) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2ea8c1d1a4](https://bsd-hardware.info/?probe=2ea8c1d1a4) | Jan 20, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [0d3e0df928](https://bsd-hardware.info/?probe=0d3e0df928) | Jan 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d4018ae0f3](https://bsd-hardware.info/?probe=d4018ae0f3) | Jan 20, 2023 |
| Dell          | 0R5KP9 A04                  | Server      | [03a26b8a34](https://bsd-hardware.info/?probe=03a26b8a34) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [32ebc1c99d](https://bsd-hardware.info/?probe=32ebc1c99d) | Jan 20, 2023 |
| Sophos        | SG                          | Firewall    | [324882f1d6](https://bsd-hardware.info/?probe=324882f1d6) | Jan 20, 2023 |
| Dell          | 04415J A00                  | Mini pc     | [8ffe26845d](https://bsd-hardware.info/?probe=8ffe26845d) | Jan 20, 2023 |
| Cisco         | ASA5512 A0                  | Desktop     | [9cd4409fda](https://bsd-hardware.info/?probe=9cd4409fda) | Jan 20, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [142b3ad8d6](https://bsd-hardware.info/?probe=142b3ad8d6) | Jan 20, 2023 |
| Unknown       | PICO PC                     | Desktop     | [9e20d7dbbc](https://bsd-hardware.info/?probe=9e20d7dbbc) | Jan 20, 2023 |
| Unknown       | YL-E3845L4-V2               | Desktop     | [d93eb933f1](https://bsd-hardware.info/?probe=d93eb933f1) | Jan 20, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [47742b68d5](https://bsd-hardware.info/?probe=47742b68d5) | Jan 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ba99fba661](https://bsd-hardware.info/?probe=ba99fba661) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [32477354bc](https://bsd-hardware.info/?probe=32477354bc) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [62bad8c9f8](https://bsd-hardware.info/?probe=62bad8c9f8) | Jan 19, 2023 |
| HP            | ProLiant DL120 Gen9         | Server      | [7df2c509dd](https://bsd-hardware.info/?probe=7df2c509dd) | Jan 19, 2023 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [48206a7d4a](https://bsd-hardware.info/?probe=48206a7d4a) | Jan 19, 2023 |
| Sophos        | SG                          | Firewall    | [f10f04a5b1](https://bsd-hardware.info/?probe=f10f04a5b1) | Jan 19, 2023 |
| Sophos        | SG                          | Firewall    | [9275bbae4e](https://bsd-hardware.info/?probe=9275bbae4e) | Jan 19, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [f7efd8c7d2](https://bsd-hardware.info/?probe=f7efd8c7d2) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [28bb1a7282](https://bsd-hardware.info/?probe=28bb1a7282) | Jan 19, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [488416a10c](https://bsd-hardware.info/?probe=488416a10c) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [6aa648ba82](https://bsd-hardware.info/?probe=6aa648ba82) | Jan 19, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [8580d62bf3](https://bsd-hardware.info/?probe=8580d62bf3) | Jan 19, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [b9de543167](https://bsd-hardware.info/?probe=b9de543167) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [11948a0ab1](https://bsd-hardware.info/?probe=11948a0ab1) | Jan 18, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [fb9e5fe3cf](https://bsd-hardware.info/?probe=fb9e5fe3cf) | Jan 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [739cc6e5ac](https://bsd-hardware.info/?probe=739cc6e5ac) | Jan 18, 2023 |
| HP            | 17E2                        | Mini pc     | [ff98f389b1](https://bsd-hardware.info/?probe=ff98f389b1) | Jan 18, 2023 |
| ZOTAC         | ZBOX-CI325NANO              | Mini pc     | [67a09fbbab](https://bsd-hardware.info/?probe=67a09fbbab) | Jan 18, 2023 |
| Sophos        | UTM                         | Firewall    | [4b0eace553](https://bsd-hardware.info/?probe=4b0eace553) | Jan 18, 2023 |
| Datto         | Unknown                     | Notebook    | [0b70f2b2b0](https://bsd-hardware.info/?probe=0b70f2b2b0) | Jan 18, 2023 |
| HP            | 83F2                        | Desktop     | [a7230c1af5](https://bsd-hardware.info/?probe=a7230c1af5) | Jan 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [cbdab56490](https://bsd-hardware.info/?probe=cbdab56490) | Jan 18, 2023 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [c5d050f0d6](https://bsd-hardware.info/?probe=c5d050f0d6) | Jan 18, 2023 |
| Datto         | 1000                        | Notebook    | [c2abd24ed6](https://bsd-hardware.info/?probe=c2abd24ed6) | Jan 18, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [f929122d8a](https://bsd-hardware.info/?probe=f929122d8a) | Jan 18, 2023 |
| Intel         | H81U                        | Notebook    | [08d2539153](https://bsd-hardware.info/?probe=08d2539153) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [46178567ff](https://bsd-hardware.info/?probe=46178567ff) | Jan 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [4ccf28379a](https://bsd-hardware.info/?probe=4ccf28379a) | Jan 17, 2023 |
| Intel         | H81U                        | Notebook    | [fe47328dd0](https://bsd-hardware.info/?probe=fe47328dd0) | Jan 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [22015084fc](https://bsd-hardware.info/?probe=22015084fc) | Jan 17, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [65ce4b26be](https://bsd-hardware.info/?probe=65ce4b26be) | Jan 17, 2023 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [6bb5667269](https://bsd-hardware.info/?probe=6bb5667269) | Jan 17, 2023 |
| Wortmann      | terra MiniPC                | Desktop     | [be22193265](https://bsd-hardware.info/?probe=be22193265) | Jan 17, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [11943e270e](https://bsd-hardware.info/?probe=11943e270e) | Jan 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [63689d3fbc](https://bsd-hardware.info/?probe=63689d3fbc) | Jan 17, 2023 |
| MSI           | MS-9897                     | Desktop     | [8aa91d17fa](https://bsd-hardware.info/?probe=8aa91d17fa) | Jan 17, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [52078a2cab](https://bsd-hardware.info/?probe=52078a2cab) | Jan 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [0049fd4cfc](https://bsd-hardware.info/?probe=0049fd4cfc) | Jan 17, 2023 |
| MSI           | MS-9897                     | Desktop     | [0ccc361bd9](https://bsd-hardware.info/?probe=0ccc361bd9) | Jan 17, 2023 |
| HP            | 83F2                        | Desktop     | [912de3c81d](https://bsd-hardware.info/?probe=912de3c81d) | Jan 16, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [c1e1ba5558](https://bsd-hardware.info/?probe=c1e1ba5558) | Jan 16, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [78a4659386](https://bsd-hardware.info/?probe=78a4659386) | Jan 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [23d2c64af3](https://bsd-hardware.info/?probe=23d2c64af3) | Jan 16, 2023 |
| Unknown       | QD-CMU01                    | Desktop     | [768a10819b](https://bsd-hardware.info/?probe=768a10819b) | Jan 16, 2023 |
| HP            | 0AECh D                     | Desktop     | [25b7a10166](https://bsd-hardware.info/?probe=25b7a10166) | Jan 16, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [9994ae920b](https://bsd-hardware.info/?probe=9994ae920b) | Jan 15, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [e25304fa01](https://bsd-hardware.info/?probe=e25304fa01) | Jan 15, 2023 |
| ASRock        | H610M-HDV/M.2               | Desktop     | [b18c58223f](https://bsd-hardware.info/?probe=b18c58223f) | Jan 15, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [1ef7026e21](https://bsd-hardware.info/?probe=1ef7026e21) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [7488afc0a7](https://bsd-hardware.info/?probe=7488afc0a7) | Jan 15, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Desktop     | [af7a4d3493](https://bsd-hardware.info/?probe=af7a4d3493) | Jan 15, 2023 |
| Supermicro    | X11SCM-LN8F                 | Server      | [9e102da483](https://bsd-hardware.info/?probe=9e102da483) | Jan 15, 2023 |
| Silicom       | 80300-0214-G01 R311         | Desktop     | [547b59be2b](https://bsd-hardware.info/?probe=547b59be2b) | Jan 15, 2023 |
| HP            | 8299                        | Desktop     | [d7afab37f3](https://bsd-hardware.info/?probe=d7afab37f3) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [8c44d6309f](https://bsd-hardware.info/?probe=8c44d6309f) | Jan 15, 2023 |
| HP            | 8299                        | Desktop     | [7a5bbc7546](https://bsd-hardware.info/?probe=7a5bbc7546) | Jan 15, 2023 |
| Dell          | 0C2KJT A00                  | Desktop     | [9364056dac](https://bsd-hardware.info/?probe=9364056dac) | Jan 15, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [a975d143b8](https://bsd-hardware.info/?probe=a975d143b8) | Jan 15, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [624bfd62b5](https://bsd-hardware.info/?probe=624bfd62b5) | Jan 15, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [9c70b7e4e1](https://bsd-hardware.info/?probe=9c70b7e4e1) | Jan 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [c85b254f84](https://bsd-hardware.info/?probe=c85b254f84) | Jan 15, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [8aebf3b22a](https://bsd-hardware.info/?probe=8aebf3b22a) | Jan 15, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [c2100f1789](https://bsd-hardware.info/?probe=c2100f1789) | Jan 14, 2023 |
| Shuttle       | FS77U                       | Desktop     | [4598a5f9d1](https://bsd-hardware.info/?probe=4598a5f9d1) | Jan 14, 2023 |
| HP            | 1998                        | Desktop     | [789ecdb3ab](https://bsd-hardware.info/?probe=789ecdb3ab) | Jan 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3d2101dc79](https://bsd-hardware.info/?probe=3d2101dc79) | Jan 14, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [39e071ee73](https://bsd-hardware.info/?probe=39e071ee73) | Jan 14, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [17d73c4d40](https://bsd-hardware.info/?probe=17d73c4d40) | Jan 14, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ad7329411a](https://bsd-hardware.info/?probe=ad7329411a) | Jan 14, 2023 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [92525fd54a](https://bsd-hardware.info/?probe=92525fd54a) | Jan 14, 2023 |
| Lenovo        | 3102 SDK0J40700 WIN 3258... | Desktop     | [9805fe9459](https://bsd-hardware.info/?probe=9805fe9459) | Jan 13, 2023 |
| Lenovo        | 3102 SDK0J40700 WIN 3258... | Desktop     | [1ec6c3acf2](https://bsd-hardware.info/?probe=1ec6c3acf2) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [e0ed98daee](https://bsd-hardware.info/?probe=e0ed98daee) | Jan 13, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [f8a84dbf0c](https://bsd-hardware.info/?probe=f8a84dbf0c) | Jan 13, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [aca9f07469](https://bsd-hardware.info/?probe=aca9f07469) | Jan 13, 2023 |
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
| Protectli     | FW6 Ver                     | Desktop     | [8c1f6c2733](https://bsd-hardware.info/?probe=8c1f6c2733) | Jan 12, 2023 |
| Dell          | 051FJ8 A01                  | Desktop     | [8d5c03acf1](https://bsd-hardware.info/?probe=8d5c03acf1) | Jan 12, 2023 |
| HP            | 82A1                        | Desktop     | [567894a0bb](https://bsd-hardware.info/?probe=567894a0bb) | Jan 12, 2023 |
| Dell          | 0NX642 A11                  | Server      | [f98068785d](https://bsd-hardware.info/?probe=f98068785d) | Jan 12, 2023 |
| Biostar       | A32M2                       | Desktop     | [2540b06338](https://bsd-hardware.info/?probe=2540b06338) | Jan 12, 2023 |
| Lenovo        | 3138                        | Desktop     | [14876c7561](https://bsd-hardware.info/?probe=14876c7561) | Jan 12, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [8f3e58f2bc](https://bsd-hardware.info/?probe=8f3e58f2bc) | Jan 12, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [4154475f49](https://bsd-hardware.info/?probe=4154475f49) | Jan 12, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b1b7d05863](https://bsd-hardware.info/?probe=b1b7d05863) | Jan 12, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [619a877f82](https://bsd-hardware.info/?probe=619a877f82) | Jan 12, 2023 |
| PC Engines    | APU3                        | Desktop     | [b080710198](https://bsd-hardware.info/?probe=b080710198) | Jan 12, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [b53cd12326](https://bsd-hardware.info/?probe=b53cd12326) | Jan 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [a21b21b82f](https://bsd-hardware.info/?probe=a21b21b82f) | Jan 12, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [320272bdf1](https://bsd-hardware.info/?probe=320272bdf1) | Jan 11, 2023 |
| Dell          | 0CNCJW A08                  | Server      | [170f3cc041](https://bsd-hardware.info/?probe=170f3cc041) | Jan 11, 2023 |
| Supermicro    | X9SCI/X9SCA                 | Desktop     | [942d966486](https://bsd-hardware.info/?probe=942d966486) | Jan 11, 2023 |
| HP            | 843B                        | Desktop     | [3e2070415f](https://bsd-hardware.info/?probe=3e2070415f) | Jan 11, 2023 |
| Dell          | 0CN7CM A06                  | Server      | [33c450dade](https://bsd-hardware.info/?probe=33c450dade) | Jan 11, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [56a5c0de6e](https://bsd-hardware.info/?probe=56a5c0de6e) | Jan 11, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [5eedf320f8](https://bsd-hardware.info/?probe=5eedf320f8) | Jan 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [2293d4960d](https://bsd-hardware.info/?probe=2293d4960d) | Jan 11, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [9b4b30a009](https://bsd-hardware.info/?probe=9b4b30a009) | Jan 11, 2023 |
| Datto         | 1000                        | Notebook    | [ab1aa0f250](https://bsd-hardware.info/?probe=ab1aa0f250) | Jan 11, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [4c1bb58037](https://bsd-hardware.info/?probe=4c1bb58037) | Jan 11, 2023 |
| HP            | 213D A01                    | Desktop     | [1d30039961](https://bsd-hardware.info/?probe=1d30039961) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [87d79c88e1](https://bsd-hardware.info/?probe=87d79c88e1) | Jan 11, 2023 |
| ASUSTek       | H110I-PLUS D3               | Desktop     | [d0986bd747](https://bsd-hardware.info/?probe=d0986bd747) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [5386547734](https://bsd-hardware.info/?probe=5386547734) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [9b1707aed4](https://bsd-hardware.info/?probe=9b1707aed4) | Jan 11, 2023 |
| HP            | 1495                        | Desktop     | [4e16deda5a](https://bsd-hardware.info/?probe=4e16deda5a) | Jan 11, 2023 |
| MSI           | H110M-A PRO M2              | Desktop     | [3cf7d4a076](https://bsd-hardware.info/?probe=3cf7d4a076) | Jan 11, 2023 |
| Citrix        | CB-1100                     | Desktop     | [860f27ce64](https://bsd-hardware.info/?probe=860f27ce64) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [6e866a006d](https://bsd-hardware.info/?probe=6e866a006d) | Jan 10, 2023 |
| Biostar       | B450NH                      | Desktop     | [c30a71f5ae](https://bsd-hardware.info/?probe=c30a71f5ae) | Jan 10, 2023 |
| PC Engines    | APU2                        | Desktop     | [1e65573dfa](https://bsd-hardware.info/?probe=1e65573dfa) | Jan 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6b37f8e185](https://bsd-hardware.info/?probe=6b37f8e185) | Jan 10, 2023 |
| Dell          | 0RC130 A03                  | Server      | [861cdcfef1](https://bsd-hardware.info/?probe=861cdcfef1) | Jan 10, 2023 |
| TYAN Compu... | S5530WG2NR-LE-AKA           | Desktop     | [592af460c5](https://bsd-hardware.info/?probe=592af460c5) | Jan 10, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b37db9216b](https://bsd-hardware.info/?probe=b37db9216b) | Jan 10, 2023 |
| MSI           | H61MA-E35                   | Desktop     | [0dc2a84a69](https://bsd-hardware.info/?probe=0dc2a84a69) | Jan 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [e870cfc473](https://bsd-hardware.info/?probe=e870cfc473) | Jan 10, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [c554f29fbb](https://bsd-hardware.info/?probe=c554f29fbb) | Jan 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [2db049304e](https://bsd-hardware.info/?probe=2db049304e) | Jan 10, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [55bd6297fa](https://bsd-hardware.info/?probe=55bd6297fa) | Jan 10, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [12a726c7f3](https://bsd-hardware.info/?probe=12a726c7f3) | Jan 10, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [a1fb64a2f6](https://bsd-hardware.info/?probe=a1fb64a2f6) | Jan 09, 2023 |
| HP            | 8054                        | Desktop     | [7a7dd659c8](https://bsd-hardware.info/?probe=7a7dd659c8) | Jan 09, 2023 |
| Protectli     | FW6                         | Desktop     | [606f595213](https://bsd-hardware.info/?probe=606f595213) | Jan 09, 2023 |
| Protectli     | FW6                         | Desktop     | [6db7b1f01d](https://bsd-hardware.info/?probe=6db7b1f01d) | Jan 09, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [fa583c9b3d](https://bsd-hardware.info/?probe=fa583c9b3d) | Jan 09, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [1ebacfe659](https://bsd-hardware.info/?probe=1ebacfe659) | Jan 09, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [76ce0f8e69](https://bsd-hardware.info/?probe=76ce0f8e69) | Jan 09, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [e217534893](https://bsd-hardware.info/?probe=e217534893) | Jan 09, 2023 |
| HP            | 8299                        | Desktop     | [f80e368b24](https://bsd-hardware.info/?probe=f80e368b24) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [917b19fbeb](https://bsd-hardware.info/?probe=917b19fbeb) | Jan 09, 2023 |
| HP            | 1998                        | Desktop     | [a523babf97](https://bsd-hardware.info/?probe=a523babf97) | Jan 09, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [17ca08ce40](https://bsd-hardware.info/?probe=17ca08ce40) | Jan 09, 2023 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [c86fd3a6ff](https://bsd-hardware.info/?probe=c86fd3a6ff) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [0714b46000](https://bsd-hardware.info/?probe=0714b46000) | Jan 08, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [cc421d80b4](https://bsd-hardware.info/?probe=cc421d80b4) | Jan 08, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [011121c9a5](https://bsd-hardware.info/?probe=011121c9a5) | Jan 08, 2023 |
| Dell          | 03X6X0 A07                  | Server      | [dea6b95d26](https://bsd-hardware.info/?probe=dea6b95d26) | Jan 08, 2023 |
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
| Dell          | 0W3F1J A00                  | Mini pc     | [eca179a730](https://bsd-hardware.info/?probe=eca179a730) | Jan 07, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [7e67007744](https://bsd-hardware.info/?probe=7e67007744) | Jan 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [b19ed4597a](https://bsd-hardware.info/?probe=b19ed4597a) | Jan 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [6347de602a](https://bsd-hardware.info/?probe=6347de602a) | Jan 07, 2023 |
| HP            | 8617                        | Desktop     | [2dd1830de4](https://bsd-hardware.info/?probe=2dd1830de4) | Jan 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e87430a40](https://bsd-hardware.info/?probe=7e87430a40) | Jan 07, 2023 |
| HP            | 1998                        | Desktop     | [7b255bc81f](https://bsd-hardware.info/?probe=7b255bc81f) | Jan 06, 2023 |
| HP            | 1998                        | Desktop     | [6aec5e0d99](https://bsd-hardware.info/?probe=6aec5e0d99) | Jan 06, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [44969e64ee](https://bsd-hardware.info/?probe=44969e64ee) | Jan 06, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [ce6ccffb1b](https://bsd-hardware.info/?probe=ce6ccffb1b) | Jan 06, 2023 |
| Sophos        | UTM                         | Firewall    | [6379cce732](https://bsd-hardware.info/?probe=6379cce732) | Jan 06, 2023 |
| YANYU         | R250                        | Desktop     | [7ea489eae6](https://bsd-hardware.info/?probe=7ea489eae6) | Jan 06, 2023 |
| Dell          | 0CN7CM A06                  | Server      | [7a63630a51](https://bsd-hardware.info/?probe=7a63630a51) | Jan 06, 2023 |
| Dell          | 0CN7CM A06                  | Server      | [996218def1](https://bsd-hardware.info/?probe=996218def1) | Jan 06, 2023 |
| ASRock        | E3C226D2I                   | Desktop     | [5dfcf8051d](https://bsd-hardware.info/?probe=5dfcf8051d) | Jan 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [fa12ea67eb](https://bsd-hardware.info/?probe=fa12ea67eb) | Jan 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [4e8b83804d](https://bsd-hardware.info/?probe=4e8b83804d) | Jan 06, 2023 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [9c1f7ead89](https://bsd-hardware.info/?probe=9c1f7ead89) | Jan 06, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [92c2e73bd4](https://bsd-hardware.info/?probe=92c2e73bd4) | Jan 06, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [0d13116822](https://bsd-hardware.info/?probe=0d13116822) | Jan 06, 2023 |
| Dell          | Latitude E6430              | Notebook    | [45f592a66f](https://bsd-hardware.info/?probe=45f592a66f) | Jan 06, 2023 |
| Dell          | 02K9CR A02                  | Desktop     | [3547d6c126](https://bsd-hardware.info/?probe=3547d6c126) | Jan 06, 2023 |
| Deciso        | Netboard A20                | Notebook    | [3ff47d2ce0](https://bsd-hardware.info/?probe=3ff47d2ce0) | Jan 06, 2023 |
| Dell          | Latitude E6430              | Notebook    | [1c4bec17bb](https://bsd-hardware.info/?probe=1c4bec17bb) | Jan 06, 2023 |
| Supermicro    | X10SDV-6C-TLN4F             | Server      | [19dc10e659](https://bsd-hardware.info/?probe=19dc10e659) | Jan 05, 2023 |
| Gigabyte      | MZGLKDP-00                  | Desktop     | [f54f8db756](https://bsd-hardware.info/?probe=f54f8db756) | Jan 05, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [42bfeeda16](https://bsd-hardware.info/?probe=42bfeeda16) | Jan 05, 2023 |
| Dell          | 0W3F1J A00                  | Mini pc     | [d83b84a6bb](https://bsd-hardware.info/?probe=d83b84a6bb) | Jan 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [b3295065c3](https://bsd-hardware.info/?probe=b3295065c3) | Jan 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [cc8588d977](https://bsd-hardware.info/?probe=cc8588d977) | Jan 05, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [e3f89954bd](https://bsd-hardware.info/?probe=e3f89954bd) | Jan 05, 2023 |
| Biostar       | J4125NHU                    | Desktop     | [41114c45b7](https://bsd-hardware.info/?probe=41114c45b7) | Jan 05, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [6a0f56a7c4](https://bsd-hardware.info/?probe=6a0f56a7c4) | Jan 05, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3e4f41ff05](https://bsd-hardware.info/?probe=3e4f41ff05) | Jan 05, 2023 |
| AMI           | MNHO-048                    | Desktop     | [fbd9fa83d9](https://bsd-hardware.info/?probe=fbd9fa83d9) | Jan 05, 2023 |
| Winston Ma... | PICO PC                     | Desktop     | [d744315833](https://bsd-hardware.info/?probe=d744315833) | Jan 05, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [19f4631b5a](https://bsd-hardware.info/?probe=19f4631b5a) | Jan 05, 2023 |
| Protectli     | VP2410 10                   | Desktop     | [81c02d080f](https://bsd-hardware.info/?probe=81c02d080f) | Jan 05, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [5a4affef3e](https://bsd-hardware.info/?probe=5a4affef3e) | Jan 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [6062f9823e](https://bsd-hardware.info/?probe=6062f9823e) | Jan 04, 2023 |
| Acer          | Aspire X3400                | Desktop     | [fa59d6aa07](https://bsd-hardware.info/?probe=fa59d6aa07) | Jan 04, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [f10075e5d1](https://bsd-hardware.info/?probe=f10075e5d1) | Jan 04, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [4730790da9](https://bsd-hardware.info/?probe=4730790da9) | Jan 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [42277bd8ff](https://bsd-hardware.info/?probe=42277bd8ff) | Jan 04, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [39149acdbd](https://bsd-hardware.info/?probe=39149acdbd) | Jan 04, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [21c60a4db8](https://bsd-hardware.info/?probe=21c60a4db8) | Jan 04, 2023 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [1a72755a55](https://bsd-hardware.info/?probe=1a72755a55) | Jan 04, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [97e19b4cd1](https://bsd-hardware.info/?probe=97e19b4cd1) | Jan 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [3d2465f9f9](https://bsd-hardware.info/?probe=3d2465f9f9) | Jan 03, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [c19d0a4f63](https://bsd-hardware.info/?probe=c19d0a4f63) | Jan 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b1ee757669](https://bsd-hardware.info/?probe=b1ee757669) | Jan 03, 2023 |
| Sophos        | UTM                         | Firewall    | [96361c589a](https://bsd-hardware.info/?probe=96361c589a) | Jan 03, 2023 |
| Sophos        | SG                          | Firewall    | [4f105d12b8](https://bsd-hardware.info/?probe=4f105d12b8) | Jan 03, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [8069ed414b](https://bsd-hardware.info/?probe=8069ed414b) | Jan 03, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7d6e899adb](https://bsd-hardware.info/?probe=7d6e899adb) | Jan 03, 2023 |
| PC Engines    | apu4                        | Desktop     | [3d69b3aec1](https://bsd-hardware.info/?probe=3d69b3aec1) | Jan 03, 2023 |
| HP            | 213D A01                    | Desktop     | [3a1fd3f0a0](https://bsd-hardware.info/?probe=3a1fd3f0a0) | Jan 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [ea01217f17](https://bsd-hardware.info/?probe=ea01217f17) | Jan 02, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [203823deda](https://bsd-hardware.info/?probe=203823deda) | Jan 02, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [8835404cf3](https://bsd-hardware.info/?probe=8835404cf3) | Jan 02, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [849af12174](https://bsd-hardware.info/?probe=849af12174) | Jan 02, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [70b1ca485d](https://bsd-hardware.info/?probe=70b1ca485d) | Jan 02, 2023 |
| Intel         | Milstead Platform           | Notebook    | [21ec3118ef](https://bsd-hardware.info/?probe=21ec3118ef) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [5159265605](https://bsd-hardware.info/?probe=5159265605) | Jan 02, 2023 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [c96a5de4ed](https://bsd-hardware.info/?probe=c96a5de4ed) | Jan 02, 2023 |
| Dell          | 0CU409                      | Desktop     | [a547f05175](https://bsd-hardware.info/?probe=a547f05175) | Jan 02, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5d360961d4](https://bsd-hardware.info/?probe=5d360961d4) | Jan 02, 2023 |
| HP            | 8103 A01                    | Mini pc     | [989cfd51a8](https://bsd-hardware.info/?probe=989cfd51a8) | Jan 02, 2023 |
| HP            | 8055                        | Desktop     | [c8f3d3687d](https://bsd-hardware.info/?probe=c8f3d3687d) | Jan 02, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9dd29daa88](https://bsd-hardware.info/?probe=9dd29daa88) | Jan 02, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [a9bbb3592c](https://bsd-hardware.info/?probe=a9bbb3592c) | Jan 02, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [d5f8e71171](https://bsd-hardware.info/?probe=d5f8e71171) | Jan 02, 2023 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [9c526b27dd](https://bsd-hardware.info/?probe=9c526b27dd) | Jan 02, 2023 |
| SmbiosType... | SmbiosType2_BoardProduct... | Desktop     | [d8d62a103a](https://bsd-hardware.info/?probe=d8d62a103a) | Jan 02, 2023 |
| PC Engines    | apu4                        | Desktop     | [31b327c32b](https://bsd-hardware.info/?probe=31b327c32b) | Jan 01, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [2973cd399c](https://bsd-hardware.info/?probe=2973cd399c) | Jan 01, 2023 |
| ASRock        | E350M1                      | Desktop     | [6a7e5c8d0c](https://bsd-hardware.info/?probe=6a7e5c8d0c) | Jan 01, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [b3ac391a7e](https://bsd-hardware.info/?probe=b3ac391a7e) | Jan 01, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [7a86ed2309](https://bsd-hardware.info/?probe=7a86ed2309) | Jan 01, 2023 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [d179977442](https://bsd-hardware.info/?probe=d179977442) | Jan 01, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [6345f92400](https://bsd-hardware.info/?probe=6345f92400) | Jan 01, 2023 |
| Dell          | 04415J A00                  | Mini pc     | [3737d80840](https://bsd-hardware.info/?probe=3737d80840) | Dec 31, 2022 |
| HP            | 1825                        | Desktop     | [f7e94decd0](https://bsd-hardware.info/?probe=f7e94decd0) | Dec 31, 2022 |
| HP            | 1825                        | Desktop     | [afc1259508](https://bsd-hardware.info/?probe=afc1259508) | Dec 31, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [b6ec2e7e28](https://bsd-hardware.info/?probe=b6ec2e7e28) | Dec 31, 2022 |
| Sophos        | UTM                         | Firewall    | [81bbacbfee](https://bsd-hardware.info/?probe=81bbacbfee) | Dec 31, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [21e1293019](https://bsd-hardware.info/?probe=21e1293019) | Dec 31, 2022 |
| Sophos        | SG                          | Firewall    | [8679b4c8f4](https://bsd-hardware.info/?probe=8679b4c8f4) | Dec 31, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [0bf1c2abef](https://bsd-hardware.info/?probe=0bf1c2abef) | Dec 31, 2022 |
| Supermicro    | X11SSH-LN4F                 | Server      | [5e84d1a402](https://bsd-hardware.info/?probe=5e84d1a402) | Dec 31, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [c6c6858ef0](https://bsd-hardware.info/?probe=c6c6858ef0) | Dec 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [16daca3076](https://bsd-hardware.info/?probe=16daca3076) | Dec 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [68a847f5c2](https://bsd-hardware.info/?probe=68a847f5c2) | Dec 31, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [cac58d91b6](https://bsd-hardware.info/?probe=cac58d91b6) | Dec 31, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [910c2bba4a](https://bsd-hardware.info/?probe=910c2bba4a) | Dec 31, 2022 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [334575b738](https://bsd-hardware.info/?probe=334575b738) | Dec 31, 2022 |
| GoWin Solu... | R86S                        | Desktop     | [4243d313a1](https://bsd-hardware.info/?probe=4243d313a1) | Dec 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [5967766127](https://bsd-hardware.info/?probe=5967766127) | Dec 30, 2022 |
| Fujitsu       | D3313-S3 S26361-D3313-S3    | Desktop     | [b89a55c4aa](https://bsd-hardware.info/?probe=b89a55c4aa) | Dec 30, 2022 |
| OEM           | 1.0                         | Desktop     | [f2aeb0ea02](https://bsd-hardware.info/?probe=f2aeb0ea02) | Dec 30, 2022 |
| CompuLab      | SBC-fit-PC4                 | Mini pc     | [c781bd46dc](https://bsd-hardware.info/?probe=c781bd46dc) | Dec 30, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [cd3e4f7122](https://bsd-hardware.info/?probe=cd3e4f7122) | Dec 30, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [a8ece272af](https://bsd-hardware.info/?probe=a8ece272af) | Dec 30, 2022 |
| Protectli     | FW4B                        | Desktop     | [406fe72c22](https://bsd-hardware.info/?probe=406fe72c22) | Dec 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [126bde2444](https://bsd-hardware.info/?probe=126bde2444) | Dec 30, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [d4460f8031](https://bsd-hardware.info/?probe=d4460f8031) | Dec 30, 2022 |
| Protectli     | FW6                         | Desktop     | [0d62222b7a](https://bsd-hardware.info/?probe=0d62222b7a) | Dec 30, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [46c3e7ffdd](https://bsd-hardware.info/?probe=46c3e7ffdd) | Dec 30, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [8b4c84d972](https://bsd-hardware.info/?probe=8b4c84d972) | Dec 30, 2022 |
| Unknown       | Unknown                     | Firewall    | [72eaa7a90f](https://bsd-hardware.info/?probe=72eaa7a90f) | Dec 30, 2022 |
| Shuttle       | FH110                       | Desktop     | [3759d77a05](https://bsd-hardware.info/?probe=3759d77a05) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [e23f822438](https://bsd-hardware.info/?probe=e23f822438) | Dec 29, 2022 |
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
| Hardkernel    | ODROID-H2                   | Desktop     | [b685ddc2ad](https://bsd-hardware.info/?probe=b685ddc2ad) | Dec 28, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [fa3c5f6504](https://bsd-hardware.info/?probe=fa3c5f6504) | Dec 28, 2022 |
| PC Engines    | APU2                        | Desktop     | [85da0654e1](https://bsd-hardware.info/?probe=85da0654e1) | Dec 28, 2022 |
| Intel         | CARLOW                      | Desktop     | [fa30f060f3](https://bsd-hardware.info/?probe=fa30f060f3) | Dec 28, 2022 |
| ASUSTek       | P11C-M Series               | Desktop     | [21f838983b](https://bsd-hardware.info/?probe=21f838983b) | Dec 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9954c0abee](https://bsd-hardware.info/?probe=9954c0abee) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [5b8ad02694](https://bsd-hardware.info/?probe=5b8ad02694) | Dec 28, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [5dafbbced0](https://bsd-hardware.info/?probe=5dafbbced0) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [e70af54c3f](https://bsd-hardware.info/?probe=e70af54c3f) | Dec 28, 2022 |
| HP            | 1998                        | Desktop     | [afc7de60e3](https://bsd-hardware.info/?probe=afc7de60e3) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c3b95220d7](https://bsd-hardware.info/?probe=c3b95220d7) | Dec 28, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [79d8b1477f](https://bsd-hardware.info/?probe=79d8b1477f) | Dec 28, 2022 |
| Shuttle       | FH110                       | Desktop     | [be457c2796](https://bsd-hardware.info/?probe=be457c2796) | Dec 27, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8d3ab2cab5](https://bsd-hardware.info/?probe=8d3ab2cab5) | Dec 27, 2022 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [4bcc34fdca](https://bsd-hardware.info/?probe=4bcc34fdca) | Dec 27, 2022 |
| Intel         | D2500HN AAG81480-500        | Desktop     | [dae5627541](https://bsd-hardware.info/?probe=dae5627541) | Dec 27, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [8cb1f1a8ea](https://bsd-hardware.info/?probe=8cb1f1a8ea) | Dec 27, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [3bdb5aa361](https://bsd-hardware.info/?probe=3bdb5aa361) | Dec 27, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [41094c24b2](https://bsd-hardware.info/?probe=41094c24b2) | Dec 27, 2022 |
| Dell          | 0X744K A02                  | Server      | [c63d853abc](https://bsd-hardware.info/?probe=c63d853abc) | Dec 27, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b553cea3bd](https://bsd-hardware.info/?probe=b553cea3bd) | Dec 26, 2022 |
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
| Cisco         | ASA5515 A0                  | Desktop     | [9e587b9499](https://bsd-hardware.info/?probe=9e587b9499) | Dec 25, 2022 |
| Shuttle       | FH110                       | Desktop     | [a194756b95](https://bsd-hardware.info/?probe=a194756b95) | Dec 25, 2022 |
| HP            | 8062                        | Desktop     | [f4d3eb024d](https://bsd-hardware.info/?probe=f4d3eb024d) | Dec 25, 2022 |
| HP            | 213D A01                    | Desktop     | [bd620f0fc0](https://bsd-hardware.info/?probe=bd620f0fc0) | Dec 25, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [f1cb9703a7](https://bsd-hardware.info/?probe=f1cb9703a7) | Dec 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [bd212706ad](https://bsd-hardware.info/?probe=bd212706ad) | Dec 24, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [af60c7ce81](https://bsd-hardware.info/?probe=af60c7ce81) | Dec 24, 2022 |
| Sophos        | UTM                         | Firewall    | [224580445a](https://bsd-hardware.info/?probe=224580445a) | Dec 24, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [33c59c687d](https://bsd-hardware.info/?probe=33c59c687d) | Dec 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [153f99a846](https://bsd-hardware.info/?probe=153f99a846) | Dec 24, 2022 |
| HP            | 8299                        | Desktop     | [6715ee2886](https://bsd-hardware.info/?probe=6715ee2886) | Dec 24, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [b29f2e4573](https://bsd-hardware.info/?probe=b29f2e4573) | Dec 24, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [701c6e95d6](https://bsd-hardware.info/?probe=701c6e95d6) | Dec 24, 2022 |
| ASRock        | N3710-NUC IPC               | Desktop     | [80c809e992](https://bsd-hardware.info/?probe=80c809e992) | Dec 24, 2022 |
| Biostar       | A32M2                       | Desktop     | [49c31b364c](https://bsd-hardware.info/?probe=49c31b364c) | Dec 23, 2022 |
| Biostar       | A10N-8800E                  | Desktop     | [d3d1107f77](https://bsd-hardware.info/?probe=d3d1107f77) | Dec 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [58b47341c9](https://bsd-hardware.info/?probe=58b47341c9) | Dec 23, 2022 |
| MSI           | A78M-E35                    | Desktop     | [03176e6683](https://bsd-hardware.info/?probe=03176e6683) | Dec 23, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b19a4d1696](https://bsd-hardware.info/?probe=b19a4d1696) | Dec 23, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [52327286e4](https://bsd-hardware.info/?probe=52327286e4) | Dec 23, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [0d70cc442b](https://bsd-hardware.info/?probe=0d70cc442b) | Dec 23, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [3a8d5c61b6](https://bsd-hardware.info/?probe=3a8d5c61b6) | Dec 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7cccecfde1](https://bsd-hardware.info/?probe=7cccecfde1) | Dec 23, 2022 |
| Intel BOX4... | Geminilake                  | Desktop     | [a2b2b7c25f](https://bsd-hardware.info/?probe=a2b2b7c25f) | Dec 23, 2022 |
| Intel BOX4... | Geminilake                  | Desktop     | [06933f3d87](https://bsd-hardware.info/?probe=06933f3d87) | Dec 23, 2022 |
| Unknown       | QD-WHLU01                   | Desktop     | [a0fb185069](https://bsd-hardware.info/?probe=a0fb185069) | Dec 23, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [e0b4e13386](https://bsd-hardware.info/?probe=e0b4e13386) | Dec 23, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [8325caa4d6](https://bsd-hardware.info/?probe=8325caa4d6) | Dec 23, 2022 |
| HP            | 8299                        | Desktop     | [d9eec3c9f5](https://bsd-hardware.info/?probe=d9eec3c9f5) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [91a89db2ab](https://bsd-hardware.info/?probe=91a89db2ab) | Dec 23, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [bc2c536004](https://bsd-hardware.info/?probe=bc2c536004) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [58ca7ca7d4](https://bsd-hardware.info/?probe=58ca7ca7d4) | Dec 23, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [062fb4cccd](https://bsd-hardware.info/?probe=062fb4cccd) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [dfd3e7acb1](https://bsd-hardware.info/?probe=dfd3e7acb1) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [daaad6a386](https://bsd-hardware.info/?probe=daaad6a386) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [67bc182d1d](https://bsd-hardware.info/?probe=67bc182d1d) | Dec 23, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [6f8bdb560b](https://bsd-hardware.info/?probe=6f8bdb560b) | Dec 23, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cde7bad6c3](https://bsd-hardware.info/?probe=cde7bad6c3) | Dec 22, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [78bcccda01](https://bsd-hardware.info/?probe=78bcccda01) | Dec 22, 2022 |
| Dell          | 060J9C A00                  | Mini pc     | [29b3e0b639](https://bsd-hardware.info/?probe=29b3e0b639) | Dec 22, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [01d8e43ee1](https://bsd-hardware.info/?probe=01d8e43ee1) | Dec 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [0f03a7f2ce](https://bsd-hardware.info/?probe=0f03a7f2ce) | Dec 22, 2022 |
| AAEON         | FWS-2251 V1.0               | Desktop     | [a4ff0a7ec5](https://bsd-hardware.info/?probe=a4ff0a7ec5) | Dec 22, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [9e817a9114](https://bsd-hardware.info/?probe=9e817a9114) | Dec 22, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [90dfe8ee6b](https://bsd-hardware.info/?probe=90dfe8ee6b) | Dec 22, 2022 |
| Acer          | WG43M                       | Desktop     | [d316352c20](https://bsd-hardware.info/?probe=d316352c20) | Dec 22, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [633b9a5425](https://bsd-hardware.info/?probe=633b9a5425) | Dec 22, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2ac107df0f](https://bsd-hardware.info/?probe=2ac107df0f) | Dec 22, 2022 |
| AMI           | Cherry Trail CR             | Mini pc     | [cc9eb40ce1](https://bsd-hardware.info/?probe=cc9eb40ce1) | Dec 22, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [f241237f76](https://bsd-hardware.info/?probe=f241237f76) | Dec 22, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [0c3fea5eb0](https://bsd-hardware.info/?probe=0c3fea5eb0) | Dec 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [0a40b02aeb](https://bsd-hardware.info/?probe=0a40b02aeb) | Dec 22, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [df221cefbc](https://bsd-hardware.info/?probe=df221cefbc) | Dec 22, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [16589e2878](https://bsd-hardware.info/?probe=16589e2878) | Dec 21, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [17ddf8c2e1](https://bsd-hardware.info/?probe=17ddf8c2e1) | Dec 21, 2022 |
| PC Engines    | APU2                        | Desktop     | [9781d92062](https://bsd-hardware.info/?probe=9781d92062) | Dec 21, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [490f20c93d](https://bsd-hardware.info/?probe=490f20c93d) | Dec 21, 2022 |
| PC Engines    | APU2                        | Desktop     | [e94b983d48](https://bsd-hardware.info/?probe=e94b983d48) | Dec 21, 2022 |
| ACMA          | X8SIE                       | Desktop     | [01898b2ffb](https://bsd-hardware.info/?probe=01898b2ffb) | Dec 21, 2022 |
| Intel         | S3420GP E51976-407          | Server      | [c614a1e46f](https://bsd-hardware.info/?probe=c614a1e46f) | Dec 20, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [16f59f69dc](https://bsd-hardware.info/?probe=16f59f69dc) | Dec 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [0bffe61dae](https://bsd-hardware.info/?probe=0bffe61dae) | Dec 20, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3502cb3d47](https://bsd-hardware.info/?probe=3502cb3d47) | Dec 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [a8ec4c3ae4](https://bsd-hardware.info/?probe=a8ec4c3ae4) | Dec 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [4667028e67](https://bsd-hardware.info/?probe=4667028e67) | Dec 20, 2022 |
| Protectli     | FW2B Ver                    | Desktop     | [9596576df7](https://bsd-hardware.info/?probe=9596576df7) | Dec 20, 2022 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [e1e1a80328](https://bsd-hardware.info/?probe=e1e1a80328) | Dec 20, 2022 |
| Dell          | 0X744K A02                  | Server      | [e45fc09011](https://bsd-hardware.info/?probe=e45fc09011) | Dec 20, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [2ea413db31](https://bsd-hardware.info/?probe=2ea413db31) | Dec 20, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [31f17adc5b](https://bsd-hardware.info/?probe=31f17adc5b) | Dec 20, 2022 |
| Dell          | 0WR7PY A00                  | Desktop     | [360336dcc1](https://bsd-hardware.info/?probe=360336dcc1) | Dec 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [364b3758b6](https://bsd-hardware.info/?probe=364b3758b6) | Dec 20, 2022 |
| Sophos        | SG                          | Firewall    | [5536740301](https://bsd-hardware.info/?probe=5536740301) | Dec 20, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [3c36f8db41](https://bsd-hardware.info/?probe=3c36f8db41) | Dec 20, 2022 |
| Supermicro    | X10SDV-4C-TLN4F             | Server      | [c0c8d1f85e](https://bsd-hardware.info/?probe=c0c8d1f85e) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [4c5ccd04d0](https://bsd-hardware.info/?probe=4c5ccd04d0) | Dec 19, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b84941cdd5](https://bsd-hardware.info/?probe=b84941cdd5) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [5d37a0669c](https://bsd-hardware.info/?probe=5d37a0669c) | Dec 19, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [67baacfc7d](https://bsd-hardware.info/?probe=67baacfc7d) | Dec 19, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [c9de65beeb](https://bsd-hardware.info/?probe=c9de65beeb) | Dec 19, 2022 |
| PC Engines    | APU2                        | Desktop     | [5de84cb508](https://bsd-hardware.info/?probe=5de84cb508) | Dec 19, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [511f2a6d16](https://bsd-hardware.info/?probe=511f2a6d16) | Dec 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [fad0a431e5](https://bsd-hardware.info/?probe=fad0a431e5) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [f876d5d5b1](https://bsd-hardware.info/?probe=f876d5d5b1) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [3d77f833b0](https://bsd-hardware.info/?probe=3d77f833b0) | Dec 19, 2022 |
| Dell          | 0VD50G A01                  | Server      | [07852bf200](https://bsd-hardware.info/?probe=07852bf200) | Dec 19, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [b9df714117](https://bsd-hardware.info/?probe=b9df714117) | Dec 19, 2022 |
| Supermicro    | X11SSL-F                    | Server      | [7bd99b62ab](https://bsd-hardware.info/?probe=7bd99b62ab) | Dec 19, 2022 |
| Dell          | Edge Gateway 5000           | Mini pc     | [0af7422e2f](https://bsd-hardware.info/?probe=0af7422e2f) | Dec 18, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [f321130f0e](https://bsd-hardware.info/?probe=f321130f0e) | Dec 18, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [14d483ac06](https://bsd-hardware.info/?probe=14d483ac06) | Dec 18, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [53a90a6c63](https://bsd-hardware.info/?probe=53a90a6c63) | Dec 18, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [abe21b9c9e](https://bsd-hardware.info/?probe=abe21b9c9e) | Dec 18, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [fc7928dfe9](https://bsd-hardware.info/?probe=fc7928dfe9) | Dec 18, 2022 |
| ASRock        | E3C224D2I                   | Desktop     | [106e525671](https://bsd-hardware.info/?probe=106e525671) | Dec 18, 2022 |
| Supermicro    | X11SCL-F                    | Server      | [638b27bc34](https://bsd-hardware.info/?probe=638b27bc34) | Dec 18, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [1f1de1d49c](https://bsd-hardware.info/?probe=1f1de1d49c) | Dec 18, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [a40ada7f7f](https://bsd-hardware.info/?probe=a40ada7f7f) | Dec 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [f6fababc22](https://bsd-hardware.info/?probe=f6fababc22) | Dec 18, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e06fa5d522](https://bsd-hardware.info/?probe=e06fa5d522) | Dec 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a1b29c356e](https://bsd-hardware.info/?probe=a1b29c356e) | Dec 17, 2022 |
| Protectli     | FW6                         | Desktop     | [56f62226e7](https://bsd-hardware.info/?probe=56f62226e7) | Dec 17, 2022 |
| PC Engines    | APU3                        | Desktop     | [5597cca988](https://bsd-hardware.info/?probe=5597cca988) | Dec 17, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [92593f4e79](https://bsd-hardware.info/?probe=92593f4e79) | Dec 17, 2022 |
| MSI           | MS-98C8                     | Desktop     | [a6e45c8e5f](https://bsd-hardware.info/?probe=a6e45c8e5f) | Dec 17, 2022 |
| PC Engines    | APU3                        | Desktop     | [0e1197c771](https://bsd-hardware.info/?probe=0e1197c771) | Dec 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [0e98358cf3](https://bsd-hardware.info/?probe=0e98358cf3) | Dec 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [e8095445e8](https://bsd-hardware.info/?probe=e8095445e8) | Dec 17, 2022 |
| HP            | 213D A01                    | Desktop     | [088766f04d](https://bsd-hardware.info/?probe=088766f04d) | Dec 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [f7700c781d](https://bsd-hardware.info/?probe=f7700c781d) | Dec 17, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [f6085ba691](https://bsd-hardware.info/?probe=f6085ba691) | Dec 17, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [7981529337](https://bsd-hardware.info/?probe=7981529337) | Dec 17, 2022 |
| PC Engines    | APU                         | Desktop     | [19786edc61](https://bsd-hardware.info/?probe=19786edc61) | Dec 17, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [afef2952f9](https://bsd-hardware.info/?probe=afef2952f9) | Dec 17, 2022 |
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
| Intel         | DQ77KB AAG81483-501         | Desktop     | [cc51093e02](https://bsd-hardware.info/?probe=cc51093e02) | Dec 16, 2022 |
| ASRock        | Q2900M                      | Desktop     | [42a53e5201](https://bsd-hardware.info/?probe=42a53e5201) | Dec 16, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [fa8c102cfd](https://bsd-hardware.info/?probe=fa8c102cfd) | Dec 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [3faaaa8209](https://bsd-hardware.info/?probe=3faaaa8209) | Dec 16, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [d9376f2f63](https://bsd-hardware.info/?probe=d9376f2f63) | Dec 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [01e26ec145](https://bsd-hardware.info/?probe=01e26ec145) | Dec 15, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [40911b66e2](https://bsd-hardware.info/?probe=40911b66e2) | Dec 15, 2022 |
| Supermicro    | X11SBA-LN4F                 | Server      | [649d525fdb](https://bsd-hardware.info/?probe=649d525fdb) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [9ac68a1c6d](https://bsd-hardware.info/?probe=9ac68a1c6d) | Dec 15, 2022 |
| Gigabyte      | N3160ND3V                   | Desktop     | [c84bedc821](https://bsd-hardware.info/?probe=c84bedc821) | Dec 15, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [deb30193e2](https://bsd-hardware.info/?probe=deb30193e2) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [e3508ce360](https://bsd-hardware.info/?probe=e3508ce360) | Dec 15, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [435807287e](https://bsd-hardware.info/?probe=435807287e) | Dec 15, 2022 |
| Dell          | 0WR7PY A00                  | Desktop     | [f923c6c0d6](https://bsd-hardware.info/?probe=f923c6c0d6) | Dec 15, 2022 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [7cb1b0cc2d](https://bsd-hardware.info/?probe=7cb1b0cc2d) | Dec 15, 2022 |
| Intel         | H81U                        | Notebook    | [fab3eecc66](https://bsd-hardware.info/?probe=fab3eecc66) | Dec 15, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [e199c0ec3d](https://bsd-hardware.info/?probe=e199c0ec3d) | Dec 15, 2022 |
| Sophos        | SG                          | Firewall    | [16753b9090](https://bsd-hardware.info/?probe=16753b9090) | Dec 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [35ecaf0406](https://bsd-hardware.info/?probe=35ecaf0406) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [9d71e35375](https://bsd-hardware.info/?probe=9d71e35375) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [98621b669c](https://bsd-hardware.info/?probe=98621b669c) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [b0639c3d01](https://bsd-hardware.info/?probe=b0639c3d01) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [52fbc8ccf7](https://bsd-hardware.info/?probe=52fbc8ccf7) | Dec 15, 2022 |
| Dell          | 0CU409                      | Desktop     | [718c9c5c8b](https://bsd-hardware.info/?probe=718c9c5c8b) | Dec 15, 2022 |
| Dell          | 0CU409                      | Desktop     | [161da6b850](https://bsd-hardware.info/?probe=161da6b850) | Dec 15, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [d7d0ebf605](https://bsd-hardware.info/?probe=d7d0ebf605) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [210418cc84](https://bsd-hardware.info/?probe=210418cc84) | Dec 15, 2022 |
| HP            | 1495                        | Desktop     | [04bd0455f2](https://bsd-hardware.info/?probe=04bd0455f2) | Dec 14, 2022 |
| Supermicro    | A1SRM-2758F                 | Server      | [fb96378782](https://bsd-hardware.info/?probe=fb96378782) | Dec 14, 2022 |
| Intel         | H81U                        | Notebook    | [fe1c3cb754](https://bsd-hardware.info/?probe=fe1c3cb754) | Dec 14, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [4091e15cac](https://bsd-hardware.info/?probe=4091e15cac) | Dec 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [64c549f3ae](https://bsd-hardware.info/?probe=64c549f3ae) | Dec 14, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [e44f465325](https://bsd-hardware.info/?probe=e44f465325) | Dec 14, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [cb16bb9431](https://bsd-hardware.info/?probe=cb16bb9431) | Dec 14, 2022 |
| NF541         | 1.0                         | Desktop     | [b0644bada6](https://bsd-hardware.info/?probe=b0644bada6) | Dec 14, 2022 |
| HP            | 1495                        | Desktop     | [23f8aeada7](https://bsd-hardware.info/?probe=23f8aeada7) | Dec 14, 2022 |
| HP            | 2215                        | Desktop     | [76f607b100](https://bsd-hardware.info/?probe=76f607b100) | Dec 14, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [a77d60297f](https://bsd-hardware.info/?probe=a77d60297f) | Dec 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [85520bf6bf](https://bsd-hardware.info/?probe=85520bf6bf) | Dec 14, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [6ebcd7c974](https://bsd-hardware.info/?probe=6ebcd7c974) | Dec 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [ad7f977515](https://bsd-hardware.info/?probe=ad7f977515) | Dec 13, 2022 |
| AZW           | U59                         | Desktop     | [9b22c68e98](https://bsd-hardware.info/?probe=9b22c68e98) | Dec 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [ec6827e543](https://bsd-hardware.info/?probe=ec6827e543) | Dec 13, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [2d6c881723](https://bsd-hardware.info/?probe=2d6c881723) | Dec 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [abed96a938](https://bsd-hardware.info/?probe=abed96a938) | Dec 13, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [66e0c118d2](https://bsd-hardware.info/?probe=66e0c118d2) | Dec 13, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [af9df0d2c9](https://bsd-hardware.info/?probe=af9df0d2c9) | Dec 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [9ee8d1082b](https://bsd-hardware.info/?probe=9ee8d1082b) | Dec 12, 2022 |
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
| Sophos        | XG                          | Firewall    | [e35b3151a3](https://bsd-hardware.info/?probe=e35b3151a3) | Dec 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [fa8afd004f](https://bsd-hardware.info/?probe=fa8afd004f) | Dec 11, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [ad71b00b0d](https://bsd-hardware.info/?probe=ad71b00b0d) | Dec 11, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [d79604d043](https://bsd-hardware.info/?probe=d79604d043) | Dec 11, 2022 |
| HP            | 82B4                        | Desktop     | [c47cb195e0](https://bsd-hardware.info/?probe=c47cb195e0) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3124aaaf95](https://bsd-hardware.info/?probe=3124aaaf95) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b1bd01549a](https://bsd-hardware.info/?probe=b1bd01549a) | Dec 11, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [4b14039072](https://bsd-hardware.info/?probe=4b14039072) | Dec 11, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [0939871923](https://bsd-hardware.info/?probe=0939871923) | Dec 11, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [808108016d](https://bsd-hardware.info/?probe=808108016d) | Dec 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [def65f518e](https://bsd-hardware.info/?probe=def65f518e) | Dec 10, 2022 |
| Fujitsu       | D3313-S1 S26361-D3313-S1    | Desktop     | [7570f3ae64](https://bsd-hardware.info/?probe=7570f3ae64) | Dec 10, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [6b64c3dbaf](https://bsd-hardware.info/?probe=6b64c3dbaf) | Dec 10, 2022 |
| HP            | 213D A01                    | Desktop     | [6c83f31e71](https://bsd-hardware.info/?probe=6c83f31e71) | Dec 10, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [0b08951f1c](https://bsd-hardware.info/?probe=0b08951f1c) | Dec 10, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [342c99d07d](https://bsd-hardware.info/?probe=342c99d07d) | Dec 10, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [33395e819a](https://bsd-hardware.info/?probe=33395e819a) | Dec 10, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [7d80c62813](https://bsd-hardware.info/?probe=7d80c62813) | Dec 09, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [1115d508c1](https://bsd-hardware.info/?probe=1115d508c1) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [0405fd0f0d](https://bsd-hardware.info/?probe=0405fd0f0d) | Dec 09, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [073c2c8de0](https://bsd-hardware.info/?probe=073c2c8de0) | Dec 09, 2022 |
| Hardkernel    | ODROID-H3                   | Desktop     | [cd6aa62212](https://bsd-hardware.info/?probe=cd6aa62212) | Dec 09, 2022 |
| HP            | 1495                        | Desktop     | [3eab39d89f](https://bsd-hardware.info/?probe=3eab39d89f) | Dec 09, 2022 |
| Sophos        | SG                          | Firewall    | [07fbfad254](https://bsd-hardware.info/?probe=07fbfad254) | Dec 09, 2022 |
| Dell          | 0DRG19 A00                  | Mini pc     | [bbca9fc84f](https://bsd-hardware.info/?probe=bbca9fc84f) | Dec 09, 2022 |
| Sophos        | SG                          | Firewall    | [a3b0edbd3c](https://bsd-hardware.info/?probe=a3b0edbd3c) | Dec 09, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [094ac0c253](https://bsd-hardware.info/?probe=094ac0c253) | Dec 09, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [3f55143fd9](https://bsd-hardware.info/?probe=3f55143fd9) | Dec 09, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [6b03cb139e](https://bsd-hardware.info/?probe=6b03cb139e) | Dec 09, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [b2f0da8246](https://bsd-hardware.info/?probe=b2f0da8246) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [493df1f529](https://bsd-hardware.info/?probe=493df1f529) | Dec 09, 2022 |
| PC Engines    | apu4                        | Desktop     | [3e3ab7f196](https://bsd-hardware.info/?probe=3e3ab7f196) | Dec 09, 2022 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [0ac47aa8a0](https://bsd-hardware.info/?probe=0ac47aa8a0) | Dec 09, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [b2720b8b88](https://bsd-hardware.info/?probe=b2720b8b88) | Dec 08, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [79b2a5d3a5](https://bsd-hardware.info/?probe=79b2a5d3a5) | Dec 08, 2022 |
| Dell          | 0TY019 A02                  | Server      | [84b683ec0b](https://bsd-hardware.info/?probe=84b683ec0b) | Dec 08, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [84f8198c18](https://bsd-hardware.info/?probe=84f8198c18) | Dec 08, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [dbbdd023e9](https://bsd-hardware.info/?probe=dbbdd023e9) | Dec 08, 2022 |
| Protectli     | FW4C Ver                    | Desktop     | [71368e5cde](https://bsd-hardware.info/?probe=71368e5cde) | Dec 08, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [575d201794](https://bsd-hardware.info/?probe=575d201794) | Dec 07, 2022 |
| ASUSTek       | G11CD                       | Desktop     | [7bc1746333](https://bsd-hardware.info/?probe=7bc1746333) | Dec 07, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [294f283d65](https://bsd-hardware.info/?probe=294f283d65) | Dec 07, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [9862c1b507](https://bsd-hardware.info/?probe=9862c1b507) | Dec 07, 2022 |
| Lenovo        | 319E SEK0T35577 IOT 4247... | Mini pc     | [33545a5181](https://bsd-hardware.info/?probe=33545a5181) | Dec 07, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [6db81b5ffe](https://bsd-hardware.info/?probe=6db81b5ffe) | Dec 07, 2022 |
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
| Dell          | 0WMJ54 A01                  | Desktop     | [61347ab3e9](https://bsd-hardware.info/?probe=61347ab3e9) | Dec 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [e3dad11b11](https://bsd-hardware.info/?probe=e3dad11b11) | Dec 06, 2022 |
| Supermicro    | X10SLM+-LN4F                | Server      | [319819f81d](https://bsd-hardware.info/?probe=319819f81d) | Dec 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [657972a55d](https://bsd-hardware.info/?probe=657972a55d) | Dec 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [33f23b1291](https://bsd-hardware.info/?probe=33f23b1291) | Dec 06, 2022 |
| YANYU         | R250                        | Desktop     | [bb364271b2](https://bsd-hardware.info/?probe=bb364271b2) | Dec 05, 2022 |
| DFI           | BE17X(170/171/173)          | Notebook    | [9822160345](https://bsd-hardware.info/?probe=9822160345) | Dec 05, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [eaa3b9783e](https://bsd-hardware.info/?probe=eaa3b9783e) | Dec 05, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f130844e1e](https://bsd-hardware.info/?probe=f130844e1e) | Dec 05, 2022 |
| PC Engines    | apu4                        | Desktop     | [72061eb254](https://bsd-hardware.info/?probe=72061eb254) | Dec 05, 2022 |
| ACMA          | X8SIE                       | Desktop     | [361e4ccc04](https://bsd-hardware.info/?probe=361e4ccc04) | Dec 05, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [218e00e7ea](https://bsd-hardware.info/?probe=218e00e7ea) | Dec 05, 2022 |
| Dell          | 0CNWVK A00                  | Desktop     | [5a022db6bf](https://bsd-hardware.info/?probe=5a022db6bf) | Dec 05, 2022 |
| Intel         | CARLOW                      | Desktop     | [1b45524779](https://bsd-hardware.info/?probe=1b45524779) | Dec 05, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [05566134f9](https://bsd-hardware.info/?probe=05566134f9) | Dec 05, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [aa9482884f](https://bsd-hardware.info/?probe=aa9482884f) | Dec 05, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [90279b62b7](https://bsd-hardware.info/?probe=90279b62b7) | Dec 05, 2022 |
| Shuttle       | FS77U                       | Desktop     | [4172b79cfc](https://bsd-hardware.info/?probe=4172b79cfc) | Dec 04, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [54d1511b82](https://bsd-hardware.info/?probe=54d1511b82) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [54e89ef90b](https://bsd-hardware.info/?probe=54e89ef90b) | Dec 04, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [be5f6ad306](https://bsd-hardware.info/?probe=be5f6ad306) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [af4f0984ae](https://bsd-hardware.info/?probe=af4f0984ae) | Dec 04, 2022 |
| ASUSTek       | E35M1-I DELUXE              | Desktop     | [1a183385c7](https://bsd-hardware.info/?probe=1a183385c7) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [d9113585f0](https://bsd-hardware.info/?probe=d9113585f0) | Dec 04, 2022 |
| Sophos        | XG                          | Firewall    | [a51c56cb12](https://bsd-hardware.info/?probe=a51c56cb12) | Dec 04, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [0bdf47ea4c](https://bsd-hardware.info/?probe=0bdf47ea4c) | Dec 04, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [f34b488e42](https://bsd-hardware.info/?probe=f34b488e42) | Dec 04, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [9497657cb2](https://bsd-hardware.info/?probe=9497657cb2) | Dec 04, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [94f78cb509](https://bsd-hardware.info/?probe=94f78cb509) | Dec 03, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [1916a4064b](https://bsd-hardware.info/?probe=1916a4064b) | Dec 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [90de1777bc](https://bsd-hardware.info/?probe=90de1777bc) | Dec 02, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f6c721906b](https://bsd-hardware.info/?probe=f6c721906b) | Dec 02, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5e75bcdb11](https://bsd-hardware.info/?probe=5e75bcdb11) | Dec 02, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [40a0d948b4](https://bsd-hardware.info/?probe=40a0d948b4) | Dec 02, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [f8719b2320](https://bsd-hardware.info/?probe=f8719b2320) | Dec 02, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [c0c4fa9349](https://bsd-hardware.info/?probe=c0c4fa9349) | Dec 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [5c3941eb3f](https://bsd-hardware.info/?probe=5c3941eb3f) | Dec 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d3b72fdce8](https://bsd-hardware.info/?probe=d3b72fdce8) | Dec 02, 2022 |
| Intel         | D33217CK G76541-300         | Desktop     | [545a39b1e4](https://bsd-hardware.info/?probe=545a39b1e4) | Dec 02, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [4bf1aae972](https://bsd-hardware.info/?probe=4bf1aae972) | Dec 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [243e309a04](https://bsd-hardware.info/?probe=243e309a04) | Dec 01, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [03708406e8](https://bsd-hardware.info/?probe=03708406e8) | Dec 01, 2022 |
| HP            | 8054                        | Desktop     | [c25adeb2ff](https://bsd-hardware.info/?probe=c25adeb2ff) | Dec 01, 2022 |
| Thomas-Kre... | P9A-I/2550/4L               | Firewall    | [6bec1ec37d](https://bsd-hardware.info/?probe=6bec1ec37d) | Dec 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [32a4df9cae](https://bsd-hardware.info/?probe=32a4df9cae) | Dec 01, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a7c2e16f5c](https://bsd-hardware.info/?probe=a7c2e16f5c) | Dec 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [504a659236](https://bsd-hardware.info/?probe=504a659236) | Dec 01, 2022 |
| MSI           | Z87I                        | Desktop     | [570046969c](https://bsd-hardware.info/?probe=570046969c) | Dec 01, 2022 |
| HP            | 8103 A01                    | Mini pc     | [5cd982c2ee](https://bsd-hardware.info/?probe=5cd982c2ee) | Nov 30, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [84d1656c05](https://bsd-hardware.info/?probe=84d1656c05) | Nov 30, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [6a1a5865cb](https://bsd-hardware.info/?probe=6a1a5865cb) | Nov 30, 2022 |
| PC Engines    | apu4                        | Desktop     | [7c8b9014b1](https://bsd-hardware.info/?probe=7c8b9014b1) | Nov 30, 2022 |
| PC Engines    | apu4                        | Desktop     | [dd39e91713](https://bsd-hardware.info/?probe=dd39e91713) | Nov 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [794e041b13](https://bsd-hardware.info/?probe=794e041b13) | Nov 30, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [ac4f4b181a](https://bsd-hardware.info/?probe=ac4f4b181a) | Nov 30, 2022 |
| Protectli     | FW6                         | Desktop     | [95f3201109](https://bsd-hardware.info/?probe=95f3201109) | Nov 30, 2022 |
| Protectli     | FW4A Ver                    | Desktop     | [9e6e0f5548](https://bsd-hardware.info/?probe=9e6e0f5548) | Nov 30, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [f3b09cfb70](https://bsd-hardware.info/?probe=f3b09cfb70) | Nov 30, 2022 |
| Intel         | D33217CK G76541-300         | Desktop     | [bbdd9a1b98](https://bsd-hardware.info/?probe=bbdd9a1b98) | Nov 30, 2022 |
| Sophos        | SG                          | Firewall    | [357c380b7c](https://bsd-hardware.info/?probe=357c380b7c) | Nov 29, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cfaeaeb2f2](https://bsd-hardware.info/?probe=cfaeaeb2f2) | Nov 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [a5b10d3f79](https://bsd-hardware.info/?probe=a5b10d3f79) | Nov 29, 2022 |
| ACMA          | X8SIE                       | Desktop     | [532b81e55f](https://bsd-hardware.info/?probe=532b81e55f) | Nov 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7308d658dc](https://bsd-hardware.info/?probe=7308d658dc) | Nov 29, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [2299087d09](https://bsd-hardware.info/?probe=2299087d09) | Nov 29, 2022 |
| Unknown       | A04                         | Server      | [07f21afacc](https://bsd-hardware.info/?probe=07f21afacc) | Nov 29, 2022 |
| Lenovo        | 316A SDK0J40697 WIN 3305... | Mini pc     | [26c9557a0a](https://bsd-hardware.info/?probe=26c9557a0a) | Nov 29, 2022 |
| HP            | 8299                        | Desktop     | [d697a2e953](https://bsd-hardware.info/?probe=d697a2e953) | Nov 29, 2022 |
| ACMA          | X8SIE                       | Desktop     | [d0112d027b](https://bsd-hardware.info/?probe=d0112d027b) | Nov 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e40278b06](https://bsd-hardware.info/?probe=4e40278b06) | Nov 28, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [28dd3a0b1b](https://bsd-hardware.info/?probe=28dd3a0b1b) | Nov 28, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [d48dbd053d](https://bsd-hardware.info/?probe=d48dbd053d) | Nov 28, 2022 |
| PC Engines    | apu4                        | Desktop     | [588e065800](https://bsd-hardware.info/?probe=588e065800) | Nov 28, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [e850e0ae9c](https://bsd-hardware.info/?probe=e850e0ae9c) | Nov 28, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [35950045c6](https://bsd-hardware.info/?probe=35950045c6) | Nov 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [2fe35064cb](https://bsd-hardware.info/?probe=2fe35064cb) | Nov 28, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b1f32ca8a1](https://bsd-hardware.info/?probe=b1f32ca8a1) | Nov 28, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [b4cc780c40](https://bsd-hardware.info/?probe=b4cc780c40) | Nov 28, 2022 |
| Shuttle       | FS81                        | Desktop     | [f714ba647f](https://bsd-hardware.info/?probe=f714ba647f) | Nov 28, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [fd111870fa](https://bsd-hardware.info/?probe=fd111870fa) | Nov 28, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ae55a799e8](https://bsd-hardware.info/?probe=ae55a799e8) | Nov 28, 2022 |
| PC Engines    | apu6                        | Desktop     | [13dcbe5748](https://bsd-hardware.info/?probe=13dcbe5748) | Nov 27, 2022 |
| YANYU         | R250                        | Desktop     | [0be0925e5b](https://bsd-hardware.info/?probe=0be0925e5b) | Nov 27, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [e8e158f783](https://bsd-hardware.info/?probe=e8e158f783) | Nov 27, 2022 |
| Supermicro    | X10SRG-F                    | Desktop     | [66b7819b2a](https://bsd-hardware.info/?probe=66b7819b2a) | Nov 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [512a05eefb](https://bsd-hardware.info/?probe=512a05eefb) | Nov 27, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [ed6b1f75ae](https://bsd-hardware.info/?probe=ed6b1f75ae) | Nov 27, 2022 |
| ASRock        | J4125B-ITX                  | Desktop     | [ad497a63ac](https://bsd-hardware.info/?probe=ad497a63ac) | Nov 27, 2022 |
| HP            | 18E7                        | Desktop     | [c7635c715f](https://bsd-hardware.info/?probe=c7635c715f) | Nov 26, 2022 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [33c1878560](https://bsd-hardware.info/?probe=33c1878560) | Nov 26, 2022 |
| CompuLab      | fit-PC3                     | Mini pc     | [34dd85f78d](https://bsd-hardware.info/?probe=34dd85f78d) | Nov 26, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [2b00248458](https://bsd-hardware.info/?probe=2b00248458) | Nov 26, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [bd1f1fa769](https://bsd-hardware.info/?probe=bd1f1fa769) | Nov 26, 2022 |
| CompuLab      | fit-PC3                     | Mini pc     | [54a64a269c](https://bsd-hardware.info/?probe=54a64a269c) | Nov 26, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7c9df6da87](https://bsd-hardware.info/?probe=7c9df6da87) | Nov 26, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [b87ed70877](https://bsd-hardware.info/?probe=b87ed70877) | Nov 26, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7f9869324b](https://bsd-hardware.info/?probe=7f9869324b) | Nov 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [222e69ff59](https://bsd-hardware.info/?probe=222e69ff59) | Nov 26, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [a5514d3f4b](https://bsd-hardware.info/?probe=a5514d3f4b) | Nov 26, 2022 |
| Sophos        | SG                          | Firewall    | [d0fc510660](https://bsd-hardware.info/?probe=d0fc510660) | Nov 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [6de307244e](https://bsd-hardware.info/?probe=6de307244e) | Nov 26, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [787a2db2cd](https://bsd-hardware.info/?probe=787a2db2cd) | Nov 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [88929a3594](https://bsd-hardware.info/?probe=88929a3594) | Nov 25, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [ef6190861c](https://bsd-hardware.info/?probe=ef6190861c) | Nov 25, 2022 |
| Protectli     | FW6                         | Desktop     | [74510f3177](https://bsd-hardware.info/?probe=74510f3177) | Nov 25, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [76ecd68ff6](https://bsd-hardware.info/?probe=76ecd68ff6) | Nov 25, 2022 |
| Protectli     | FW2B Ver                    | Desktop     | [e03929e52f](https://bsd-hardware.info/?probe=e03929e52f) | Nov 25, 2022 |
| Dell          | 0F0XJ6 A13                  | Server      | [1d71d3c9e7](https://bsd-hardware.info/?probe=1d71d3c9e7) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [317231bad8](https://bsd-hardware.info/?probe=317231bad8) | Nov 25, 2022 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [dc8015adc3](https://bsd-hardware.info/?probe=dc8015adc3) | Nov 25, 2022 |
| ASRock        | H510M-HDV                   | Desktop     | [d2029ae805](https://bsd-hardware.info/?probe=d2029ae805) | Nov 25, 2022 |
| Dell          | 0F0XJ6 A13                  | Server      | [1fb28aaef2](https://bsd-hardware.info/?probe=1fb28aaef2) | Nov 25, 2022 |
| Lenovo        | 1106A14 ThinkServer TS13... | Desktop     | [28aca8c985](https://bsd-hardware.info/?probe=28aca8c985) | Nov 25, 2022 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [2959091a59](https://bsd-hardware.info/?probe=2959091a59) | Nov 25, 2022 |
| Dell          | 0HFG24 A01                  | Server      | [ca48ff12d3](https://bsd-hardware.info/?probe=ca48ff12d3) | Nov 25, 2022 |
| HP            | 8055                        | Desktop     | [ace4570d15](https://bsd-hardware.info/?probe=ace4570d15) | Nov 25, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [7bb8186465](https://bsd-hardware.info/?probe=7bb8186465) | Nov 25, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [de7f2ee053](https://bsd-hardware.info/?probe=de7f2ee053) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [7258992b77](https://bsd-hardware.info/?probe=7258992b77) | Nov 24, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [4a8efeb7a6](https://bsd-hardware.info/?probe=4a8efeb7a6) | Nov 24, 2022 |
| HP            | ProLiant DL360 G5           | Server      | [4a44193c5f](https://bsd-hardware.info/?probe=4a44193c5f) | Nov 24, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [0bbf4f46e7](https://bsd-hardware.info/?probe=0bbf4f46e7) | Nov 24, 2022 |
| Dell          | 0W13NR A07                  | Server      | [c5b09b219b](https://bsd-hardware.info/?probe=c5b09b219b) | Nov 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [d4246caa0f](https://bsd-hardware.info/?probe=d4246caa0f) | Nov 24, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [75a7bf9b27](https://bsd-hardware.info/?probe=75a7bf9b27) | Nov 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [5aa1f0193a](https://bsd-hardware.info/?probe=5aa1f0193a) | Nov 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [c5562e1851](https://bsd-hardware.info/?probe=c5562e1851) | Nov 24, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b6bbaa13e8](https://bsd-hardware.info/?probe=b6bbaa13e8) | Nov 24, 2022 |
| Dell          | 07F37C A01                  | Desktop     | [08d048da80](https://bsd-hardware.info/?probe=08d048da80) | Nov 24, 2022 |
| ASRock Ind... | NUC-1240P                   | Desktop     | [75547bc09a](https://bsd-hardware.info/?probe=75547bc09a) | Nov 24, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [aa3c44499f](https://bsd-hardware.info/?probe=aa3c44499f) | Nov 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [1b6870d481](https://bsd-hardware.info/?probe=1b6870d481) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [77e932dd9e](https://bsd-hardware.info/?probe=77e932dd9e) | Nov 23, 2022 |
| IceWhale T... | ZimaBoard 216 ZMB           | Desktop     | [b75d6c6581](https://bsd-hardware.info/?probe=b75d6c6581) | Nov 23, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [7fabc0cb8a](https://bsd-hardware.info/?probe=7fabc0cb8a) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [337d5f0f4b](https://bsd-hardware.info/?probe=337d5f0f4b) | Nov 23, 2022 |
| ZOTAC         | ZBOX-CI622/CI642/CI662NA... | Mini pc     | [4c3be7ec24](https://bsd-hardware.info/?probe=4c3be7ec24) | Nov 23, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [1860d18e39](https://bsd-hardware.info/?probe=1860d18e39) | Nov 23, 2022 |
| Protectli     | FW4B                        | Desktop     | [d3090c9e8e](https://bsd-hardware.info/?probe=d3090c9e8e) | Nov 23, 2022 |
| Infoblox      | IB-1410                     | Desktop     | [7521108ef5](https://bsd-hardware.info/?probe=7521108ef5) | Nov 23, 2022 |
| HP            | 3396                        | Desktop     | [dc94cbde1a](https://bsd-hardware.info/?probe=dc94cbde1a) | Nov 23, 2022 |
| PC Engines    | apu6                        | Desktop     | [bc334caa03](https://bsd-hardware.info/?probe=bc334caa03) | Nov 23, 2022 |
| PC Engines    | APU2                        | Desktop     | [4d33b6da51](https://bsd-hardware.info/?probe=4d33b6da51) | Nov 23, 2022 |
| Sophos        | UTM                         | Firewall    | [1c0805f9ae](https://bsd-hardware.info/?probe=1c0805f9ae) | Nov 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [d4791d1dfc](https://bsd-hardware.info/?probe=d4791d1dfc) | Nov 22, 2022 |
| Dell          | 0TW855 A07                  | Server      | [d2d859c434](https://bsd-hardware.info/?probe=d2d859c434) | Nov 22, 2022 |
| Dell          | 0MD99X A05                  | Server      | [8adc53c921](https://bsd-hardware.info/?probe=8adc53c921) | Nov 22, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [b666129e73](https://bsd-hardware.info/?probe=b666129e73) | Nov 22, 2022 |
| Datto         | SSD                         | Desktop     | [08d401fa34](https://bsd-hardware.info/?probe=08d401fa34) | Nov 22, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [2f812bd8c3](https://bsd-hardware.info/?probe=2f812bd8c3) | Nov 22, 2022 |
| Dell          | Edge Gateway 5000           | Mini pc     | [18f8f8f8b5](https://bsd-hardware.info/?probe=18f8f8f8b5) | Nov 22, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7742fc7455](https://bsd-hardware.info/?probe=7742fc7455) | Nov 21, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [77fa42b66c](https://bsd-hardware.info/?probe=77fa42b66c) | Nov 21, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [e0f08b66c2](https://bsd-hardware.info/?probe=e0f08b66c2) | Nov 21, 2022 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [2d8d0056c4](https://bsd-hardware.info/?probe=2d8d0056c4) | Nov 21, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [298fde4e33](https://bsd-hardware.info/?probe=298fde4e33) | Nov 21, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [5030575f0a](https://bsd-hardware.info/?probe=5030575f0a) | Nov 20, 2022 |
| HP            | ProLiant DL380 G6           | Server      | [3e3b056cdf](https://bsd-hardware.info/?probe=3e3b056cdf) | Nov 20, 2022 |
| Sophos        | XG                          | Firewall    | [3868856b34](https://bsd-hardware.info/?probe=3868856b34) | Nov 20, 2022 |
| Dell          | 07F37C A01                  | Desktop     | [efb5c9d03d](https://bsd-hardware.info/?probe=efb5c9d03d) | Nov 20, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [98684b1d19](https://bsd-hardware.info/?probe=98684b1d19) | Nov 20, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [f6491f1950](https://bsd-hardware.info/?probe=f6491f1950) | Nov 20, 2022 |
| OEM           | 1.0                         | Desktop     | [a821818533](https://bsd-hardware.info/?probe=a821818533) | Nov 20, 2022 |
| HP            | 8054                        | Desktop     | [2c1e20c9e7](https://bsd-hardware.info/?probe=2c1e20c9e7) | Nov 20, 2022 |
| Dell          | 0TW855 A07                  | Server      | [dbeaf80924](https://bsd-hardware.info/?probe=dbeaf80924) | Nov 20, 2022 |
| Hardkernel    | ODROID-H3                   | Desktop     | [ec7611edd1](https://bsd-hardware.info/?probe=ec7611edd1) | Nov 20, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [15d32e1e36](https://bsd-hardware.info/?probe=15d32e1e36) | Nov 20, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [29210f2239](https://bsd-hardware.info/?probe=29210f2239) | Nov 20, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [c226ac3d9b](https://bsd-hardware.info/?probe=c226ac3d9b) | Nov 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [5d3ccb6891](https://bsd-hardware.info/?probe=5d3ccb6891) | Nov 20, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [449dcd1463](https://bsd-hardware.info/?probe=449dcd1463) | Nov 19, 2022 |
| Dell          | 09D2HH A00                  | Desktop     | [794fe8eb65](https://bsd-hardware.info/?probe=794fe8eb65) | Nov 19, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [20058331ef](https://bsd-hardware.info/?probe=20058331ef) | Nov 19, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [bf83fc6cdb](https://bsd-hardware.info/?probe=bf83fc6cdb) | Nov 19, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [402a623ed0](https://bsd-hardware.info/?probe=402a623ed0) | Nov 19, 2022 |
| Foxconn       | H67S/H61SP                  | Desktop     | [80ad331089](https://bsd-hardware.info/?probe=80ad331089) | Nov 19, 2022 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [7bfffa2718](https://bsd-hardware.info/?probe=7bfffa2718) | Nov 19, 2022 |
| Dell          | 060J9C A00                  | Mini pc     | [efcae22b58](https://bsd-hardware.info/?probe=efcae22b58) | Nov 19, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [18062e5bd5](https://bsd-hardware.info/?probe=18062e5bd5) | Nov 19, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [7282ce8fe2](https://bsd-hardware.info/?probe=7282ce8fe2) | Nov 19, 2022 |
| Dell          | 0GN4PW A00                  | Desktop     | [9127ec4dac](https://bsd-hardware.info/?probe=9127ec4dac) | Nov 19, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [d3cbc9d6ca](https://bsd-hardware.info/?probe=d3cbc9d6ca) | Nov 19, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [2eba32390f](https://bsd-hardware.info/?probe=2eba32390f) | Nov 19, 2022 |
| PC Engines    | apu6                        | Desktop     | [1e9acc3ae6](https://bsd-hardware.info/?probe=1e9acc3ae6) | Nov 18, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [f25480c54a](https://bsd-hardware.info/?probe=f25480c54a) | Nov 18, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [5537746c27](https://bsd-hardware.info/?probe=5537746c27) | Nov 18, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [7c7a121711](https://bsd-hardware.info/?probe=7c7a121711) | Nov 18, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [5875ecec9f](https://bsd-hardware.info/?probe=5875ecec9f) | Nov 18, 2022 |
| HP            | 82FE 11                     | Desktop     | [547e5e3ce1](https://bsd-hardware.info/?probe=547e5e3ce1) | Nov 18, 2022 |
| Fujitsu       | D3289-A1 S26361-D3289-A1... | Desktop     | [dae7027898](https://bsd-hardware.info/?probe=dae7027898) | Nov 18, 2022 |
| Dell          | 051FJ8 A02                  | Desktop     | [296b446a8f](https://bsd-hardware.info/?probe=296b446a8f) | Nov 18, 2022 |
| ASRock        | N3150M                      | Desktop     | [d3b3be7936](https://bsd-hardware.info/?probe=d3b3be7936) | Nov 17, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [f1f56fe86c](https://bsd-hardware.info/?probe=f1f56fe86c) | Nov 17, 2022 |
| Gigabyte      | H110TN                      | Desktop     | [c121bad3fb](https://bsd-hardware.info/?probe=c121bad3fb) | Nov 17, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [ddf3f8603a](https://bsd-hardware.info/?probe=ddf3f8603a) | Nov 17, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [64d8291a91](https://bsd-hardware.info/?probe=64d8291a91) | Nov 17, 2022 |
| PC Engines    | apu4                        | Desktop     | [212f27d85a](https://bsd-hardware.info/?probe=212f27d85a) | Nov 17, 2022 |
| AAEON         | MF-001 V1.0                 | Desktop     | [d98d84f1a4](https://bsd-hardware.info/?probe=d98d84f1a4) | Nov 17, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [f362b4c2ea](https://bsd-hardware.info/?probe=f362b4c2ea) | Nov 17, 2022 |
| AZW           | U59                         | Desktop     | [25e1349c5f](https://bsd-hardware.info/?probe=25e1349c5f) | Nov 17, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [79c7aad234](https://bsd-hardware.info/?probe=79c7aad234) | Nov 17, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [9cd1c1fc21](https://bsd-hardware.info/?probe=9cd1c1fc21) | Nov 17, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [15458aff84](https://bsd-hardware.info/?probe=15458aff84) | Nov 16, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [47f82850da](https://bsd-hardware.info/?probe=47f82850da) | Nov 16, 2022 |
| HP            | ProLiant DL120 Gen9         | Server      | [94513a53f8](https://bsd-hardware.info/?probe=94513a53f8) | Nov 16, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [753c68cfb9](https://bsd-hardware.info/?probe=753c68cfb9) | Nov 16, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [abbd5ab7ff](https://bsd-hardware.info/?probe=abbd5ab7ff) | Nov 16, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b7ed699f3c](https://bsd-hardware.info/?probe=b7ed699f3c) | Nov 16, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [94afb24fbc](https://bsd-hardware.info/?probe=94afb24fbc) | Nov 16, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2714f36aca](https://bsd-hardware.info/?probe=2714f36aca) | Nov 16, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5096994f99](https://bsd-hardware.info/?probe=5096994f99) | Nov 16, 2022 |
| HP            | 82B4                        | Desktop     | [d4badfa185](https://bsd-hardware.info/?probe=d4badfa185) | Nov 15, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [314916c885](https://bsd-hardware.info/?probe=314916c885) | Nov 15, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [dd637e0562](https://bsd-hardware.info/?probe=dd637e0562) | Nov 15, 2022 |
| PC Engines    | apu4                        | Desktop     | [589dec199e](https://bsd-hardware.info/?probe=589dec199e) | Nov 15, 2022 |
| Acer          | TDPS05 R3700                | Desktop     | [4ebc5df17c](https://bsd-hardware.info/?probe=4ebc5df17c) | Nov 15, 2022 |
| Acer          | TDPS05 R3700                | Desktop     | [6e1273fdd6](https://bsd-hardware.info/?probe=6e1273fdd6) | Nov 15, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3425326f3f](https://bsd-hardware.info/?probe=3425326f3f) | Nov 14, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [cecda8d045](https://bsd-hardware.info/?probe=cecda8d045) | Nov 14, 2022 |
| Shuttle       | FH61V                       | Desktop     | [012a5c0fcc](https://bsd-hardware.info/?probe=012a5c0fcc) | Nov 14, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [9e568eb5ee](https://bsd-hardware.info/?probe=9e568eb5ee) | Nov 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [b9994aa302](https://bsd-hardware.info/?probe=b9994aa302) | Nov 14, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [a678226171](https://bsd-hardware.info/?probe=a678226171) | Nov 14, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [0079838512](https://bsd-hardware.info/?probe=0079838512) | Nov 13, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [86dcacdb40](https://bsd-hardware.info/?probe=86dcacdb40) | Nov 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [74a717c2e6](https://bsd-hardware.info/?probe=74a717c2e6) | Nov 13, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [80c0d775a7](https://bsd-hardware.info/?probe=80c0d775a7) | Nov 13, 2022 |
| HP            | 83E1                        | Desktop     | [689b01c121](https://bsd-hardware.info/?probe=689b01c121) | Nov 13, 2022 |
| Sophos        | SG                          | Firewall    | [3d17d672bd](https://bsd-hardware.info/?probe=3d17d672bd) | Nov 13, 2022 |
| Shuttle       | FS35V5                      | Mini pc     | [8b634987b4](https://bsd-hardware.info/?probe=8b634987b4) | Nov 13, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [269f915ce2](https://bsd-hardware.info/?probe=269f915ce2) | Nov 13, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [5125bff15a](https://bsd-hardware.info/?probe=5125bff15a) | Nov 13, 2022 |
| HP            | 3397                        | Desktop     | [d087515b69](https://bsd-hardware.info/?probe=d087515b69) | Nov 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [838256315e](https://bsd-hardware.info/?probe=838256315e) | Nov 13, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ee16ad1ffb](https://bsd-hardware.info/?probe=ee16ad1ffb) | Nov 12, 2022 |
| Fujitsu       | D3373-A1 S26361-D3373-A1... | Server      | [9e972fd1a1](https://bsd-hardware.info/?probe=9e972fd1a1) | Nov 12, 2022 |
| HP            | 8169                        | Desktop     | [e80c8a40a5](https://bsd-hardware.info/?probe=e80c8a40a5) | Nov 12, 2022 |
| Sophos        | SG                          | Firewall    | [4727b6a74e](https://bsd-hardware.info/?probe=4727b6a74e) | Nov 12, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [75b586fdfc](https://bsd-hardware.info/?probe=75b586fdfc) | Nov 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [e5b3cb0bcd](https://bsd-hardware.info/?probe=e5b3cb0bcd) | Nov 12, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [f1cd4bdbf3](https://bsd-hardware.info/?probe=f1cd4bdbf3) | Nov 12, 2022 |
| Sophos        | SG                          | Firewall    | [b07c5da938](https://bsd-hardware.info/?probe=b07c5da938) | Nov 12, 2022 |
| PC Engines    | APU2                        | Desktop     | [b92faf9ebb](https://bsd-hardware.info/?probe=b92faf9ebb) | Nov 12, 2022 |
| PC Engines    | APU2                        | Desktop     | [34960ed27c](https://bsd-hardware.info/?probe=34960ed27c) | Nov 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [817c69a4b0](https://bsd-hardware.info/?probe=817c69a4b0) | Nov 12, 2022 |
| Lenovo        | ThinkServer RS140           | Desktop     | [0dd05e08aa](https://bsd-hardware.info/?probe=0dd05e08aa) | Nov 12, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [cb88c3311a](https://bsd-hardware.info/?probe=cb88c3311a) | Nov 12, 2022 |
| MSI           | MS-9897                     | Desktop     | [2527ac44f4](https://bsd-hardware.info/?probe=2527ac44f4) | Nov 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [790e616e22](https://bsd-hardware.info/?probe=790e616e22) | Nov 12, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [b8ee0562af](https://bsd-hardware.info/?probe=b8ee0562af) | Nov 12, 2022 |
| HP            | 8000 X4                     | Desktop     | [824d5f1ace](https://bsd-hardware.info/?probe=824d5f1ace) | Nov 12, 2022 |
| HP            | 83E1                        | Desktop     | [1760935c91](https://bsd-hardware.info/?probe=1760935c91) | Nov 12, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [54dd33114e](https://bsd-hardware.info/?probe=54dd33114e) | Nov 12, 2022 |
| Unknown       | Unknown                     | Firewall    | [2d2b5ee614](https://bsd-hardware.info/?probe=2d2b5ee614) | Nov 12, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [23a0c08442](https://bsd-hardware.info/?probe=23a0c08442) | Nov 12, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [863c472910](https://bsd-hardware.info/?probe=863c472910) | Nov 12, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0989913192](https://bsd-hardware.info/?probe=0989913192) | Nov 12, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e3161d12c5](https://bsd-hardware.info/?probe=e3161d12c5) | Nov 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [a2b2bb3a77](https://bsd-hardware.info/?probe=a2b2bb3a77) | Nov 11, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [0fcbc68304](https://bsd-hardware.info/?probe=0fcbc68304) | Nov 11, 2022 |
| HP            | 1998                        | Desktop     | [e397526bac](https://bsd-hardware.info/?probe=e397526bac) | Nov 11, 2022 |
| HP            | 806A                        | Desktop     | [9567b6949c](https://bsd-hardware.info/?probe=9567b6949c) | Nov 11, 2022 |
| MSI           | MS-B1831                    | Desktop     | [0db8392019](https://bsd-hardware.info/?probe=0db8392019) | Nov 11, 2022 |
| Lenovo        | ThinkServer RS140           | Desktop     | [b2b1509adf](https://bsd-hardware.info/?probe=b2b1509adf) | Nov 11, 2022 |
| HP            | 1998                        | Desktop     | [6a38c36a3e](https://bsd-hardware.info/?probe=6a38c36a3e) | Nov 11, 2022 |
| Lenovo        | 30D9 No DPK                 | Desktop     | [bb9cf416c4](https://bsd-hardware.info/?probe=bb9cf416c4) | Nov 11, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [515a9245ac](https://bsd-hardware.info/?probe=515a9245ac) | Nov 11, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [f12f8c8fb2](https://bsd-hardware.info/?probe=f12f8c8fb2) | Nov 11, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [5a5e24fdf7](https://bsd-hardware.info/?probe=5a5e24fdf7) | Nov 11, 2022 |
| HP            | 18E9                        | Desktop     | [b9df70f7eb](https://bsd-hardware.info/?probe=b9df70f7eb) | Nov 11, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [391c6bed59](https://bsd-hardware.info/?probe=391c6bed59) | Nov 11, 2022 |
| Supermicro    | X10SDV-TLN4F                | Server      | [2c96fe37f6](https://bsd-hardware.info/?probe=2c96fe37f6) | Nov 10, 2022 |
| ASRock        | J4005B-ITX                  | Desktop     | [554b92cae5](https://bsd-hardware.info/?probe=554b92cae5) | Nov 10, 2022 |
| Deciso        | Netboard A20                | Notebook    | [0320675a86](https://bsd-hardware.info/?probe=0320675a86) | Nov 10, 2022 |
| CheckPoint    | PH-30-00                    | Desktop     | [e42768cd01](https://bsd-hardware.info/?probe=e42768cd01) | Nov 10, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [c741b2fbfa](https://bsd-hardware.info/?probe=c741b2fbfa) | Nov 10, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [61157ac2b6](https://bsd-hardware.info/?probe=61157ac2b6) | Nov 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [521008f8da](https://bsd-hardware.info/?probe=521008f8da) | Nov 10, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [d8030d23b0](https://bsd-hardware.info/?probe=d8030d23b0) | Nov 10, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [686447d655](https://bsd-hardware.info/?probe=686447d655) | Nov 10, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [1300135627](https://bsd-hardware.info/?probe=1300135627) | Nov 10, 2022 |
| Cisco         | C170 A0                     | Desktop     | [3ba579a78c](https://bsd-hardware.info/?probe=3ba579a78c) | Nov 10, 2022 |
| AZW           | GK55                        | Desktop     | [d73ef4f4fc](https://bsd-hardware.info/?probe=d73ef4f4fc) | Nov 10, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [4bb9a9324b](https://bsd-hardware.info/?probe=4bb9a9324b) | Nov 10, 2022 |
| HP            | 843F                        | Desktop     | [23d8a9bda7](https://bsd-hardware.info/?probe=23d8a9bda7) | Nov 10, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [9e3a09a0b3](https://bsd-hardware.info/?probe=9e3a09a0b3) | Nov 10, 2022 |
| Protectli     | FW2B                        | Desktop     | [d15326180f](https://bsd-hardware.info/?probe=d15326180f) | Nov 10, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [f8e610e161](https://bsd-hardware.info/?probe=f8e610e161) | Nov 09, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [d75162607b](https://bsd-hardware.info/?probe=d75162607b) | Nov 09, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [8addd09aa7](https://bsd-hardware.info/?probe=8addd09aa7) | Nov 09, 2022 |
| Sophos        | SG                          | Firewall    | [04b1bf9b24](https://bsd-hardware.info/?probe=04b1bf9b24) | Nov 09, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [667abc6f38](https://bsd-hardware.info/?probe=667abc6f38) | Nov 09, 2022 |
| HP            | 1632                        | Desktop     | [96d60382b7](https://bsd-hardware.info/?probe=96d60382b7) | Nov 09, 2022 |
| ASUSTek       | P8H77-I                     | Desktop     | [04ea3cc97d](https://bsd-hardware.info/?probe=04ea3cc97d) | Nov 09, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [a751c4e782](https://bsd-hardware.info/?probe=a751c4e782) | Nov 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [47e6a4fa8b](https://bsd-hardware.info/?probe=47e6a4fa8b) | Nov 09, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [1fc6403341](https://bsd-hardware.info/?probe=1fc6403341) | Nov 08, 2022 |
| Thomas-Kre... | P9A-I/2550/4L               | Firewall    | [d63fd6f7bd](https://bsd-hardware.info/?probe=d63fd6f7bd) | Nov 08, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [c3eb1a6caf](https://bsd-hardware.info/?probe=c3eb1a6caf) | Nov 08, 2022 |
| Intel         | JSL MRD                     | Desktop     | [5800246e28](https://bsd-hardware.info/?probe=5800246e28) | Nov 08, 2022 |
| ASUSTek       | EX-H110M-V                  | Desktop     | [f9832b4966](https://bsd-hardware.info/?probe=f9832b4966) | Nov 08, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [a84d0a0380](https://bsd-hardware.info/?probe=a84d0a0380) | Nov 08, 2022 |
| Dell          | 0W3F1J A00                  | Mini pc     | [5c70ba3a0d](https://bsd-hardware.info/?probe=5c70ba3a0d) | Nov 08, 2022 |
| Supermicro    | X8DT6                       | Server      | [e7536e4a4c](https://bsd-hardware.info/?probe=e7536e4a4c) | Nov 07, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [970443066b](https://bsd-hardware.info/?probe=970443066b) | Nov 07, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [da16bac6f5](https://bsd-hardware.info/?probe=da16bac6f5) | Nov 07, 2022 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [cb5bb2c3b5](https://bsd-hardware.info/?probe=cb5bb2c3b5) | Nov 07, 2022 |
| Dell          | 081N4V A08                  | Server      | [6454631448](https://bsd-hardware.info/?probe=6454631448) | Nov 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [31ff384824](https://bsd-hardware.info/?probe=31ff384824) | Nov 07, 2022 |
| HP            | 8768 A                      | Desktop     | [c8a44e84c6](https://bsd-hardware.info/?probe=c8a44e84c6) | Nov 07, 2022 |
| Sophos        | SG                          | Firewall    | [4547062398](https://bsd-hardware.info/?probe=4547062398) | Nov 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [659ec0b365](https://bsd-hardware.info/?probe=659ec0b365) | Nov 07, 2022 |
| PC Engines    | APU2                        | Desktop     | [2a913e7a43](https://bsd-hardware.info/?probe=2a913e7a43) | Nov 06, 2022 |
| PC Engines    | APU2                        | Desktop     | [4fda77e4ca](https://bsd-hardware.info/?probe=4fda77e4ca) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [70e257e360](https://bsd-hardware.info/?probe=70e257e360) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [fed7f55a01](https://bsd-hardware.info/?probe=fed7f55a01) | Nov 06, 2022 |
| HP            | 18E7                        | Desktop     | [6a80fc5241](https://bsd-hardware.info/?probe=6a80fc5241) | Nov 06, 2022 |
| Protectli     | VP2410                      | Desktop     | [de5de1ca21](https://bsd-hardware.info/?probe=de5de1ca21) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [59b8857bba](https://bsd-hardware.info/?probe=59b8857bba) | Nov 06, 2022 |
| Cisco Syst... | UCSC-C240-M5SX 74-105773... | Server      | [2633eaf68b](https://bsd-hardware.info/?probe=2633eaf68b) | Nov 06, 2022 |
| Protectli     | FW6                         | Desktop     | [654e223853](https://bsd-hardware.info/?probe=654e223853) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [a33d1a4123](https://bsd-hardware.info/?probe=a33d1a4123) | Nov 06, 2022 |
| Supermicro    | X7SPA-HF                    | Desktop     | [66819692d5](https://bsd-hardware.info/?probe=66819692d5) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [6fb650e2e8](https://bsd-hardware.info/?probe=6fb650e2e8) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [47efa8b4bc](https://bsd-hardware.info/?probe=47efa8b4bc) | Nov 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [3771535d50](https://bsd-hardware.info/?probe=3771535d50) | Nov 06, 2022 |
| Dell          | OptiPlex 5050               | Desktop     | [cfd442a25d](https://bsd-hardware.info/?probe=cfd442a25d) | Nov 06, 2022 |
| Datto         | SSD                         | Desktop     | [235483110d](https://bsd-hardware.info/?probe=235483110d) | Nov 05, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [33eea3a422](https://bsd-hardware.info/?probe=33eea3a422) | Nov 05, 2022 |
| Sophos        | SG                          | Firewall    | [d80c273f85](https://bsd-hardware.info/?probe=d80c273f85) | Nov 05, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [80a31985d9](https://bsd-hardware.info/?probe=80a31985d9) | Nov 05, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [0312c464c4](https://bsd-hardware.info/?probe=0312c464c4) | Nov 05, 2022 |
| Protectli     | FW4C Ver                    | Desktop     | [71c0c846f1](https://bsd-hardware.info/?probe=71c0c846f1) | Nov 05, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [3fa9f3aa5c](https://bsd-hardware.info/?probe=3fa9f3aa5c) | Nov 05, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [946c93ec7b](https://bsd-hardware.info/?probe=946c93ec7b) | Nov 05, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [6efd22e598](https://bsd-hardware.info/?probe=6efd22e598) | Nov 04, 2022 |
| HP            | 213D A01                    | Desktop     | [f579ee6387](https://bsd-hardware.info/?probe=f579ee6387) | Nov 04, 2022 |
| Dell          | 0G7WYD A01                  | Server      | [655a9e7af2](https://bsd-hardware.info/?probe=655a9e7af2) | Nov 04, 2022 |
| ASRock        | H670M-ITX/ax                | Desktop     | [378889e1cd](https://bsd-hardware.info/?probe=378889e1cd) | Nov 04, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [73230496b2](https://bsd-hardware.info/?probe=73230496b2) | Nov 04, 2022 |
| Dell          | 0KM5PX A01                  | Server      | [a1a15662d0](https://bsd-hardware.info/?probe=a1a15662d0) | Nov 04, 2022 |
| Dell          | 0KM5PX A01                  | Server      | [0ee82f0b87](https://bsd-hardware.info/?probe=0ee82f0b87) | Nov 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [4f58f89a6e](https://bsd-hardware.info/?probe=4f58f89a6e) | Nov 04, 2022 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [1b27159e27](https://bsd-hardware.info/?probe=1b27159e27) | Nov 04, 2022 |
| HP            | 82A2                        | Desktop     | [d83974a5ed](https://bsd-hardware.info/?probe=d83974a5ed) | Nov 03, 2022 |
| HP            | 339A                        | Desktop     | [a1e829d9d9](https://bsd-hardware.info/?probe=a1e829d9d9) | Nov 03, 2022 |
| Unknown       | 1.0                         | Desktop     | [9fe6ac4e68](https://bsd-hardware.info/?probe=9fe6ac4e68) | Nov 03, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [9c133326c9](https://bsd-hardware.info/?probe=9c133326c9) | Nov 03, 2022 |
| PC Engines    | apu4                        | Desktop     | [7ed7638be3](https://bsd-hardware.info/?probe=7ed7638be3) | Nov 03, 2022 |
| AMD           | Inagua CRB                  | Desktop     | [5d27c08853](https://bsd-hardware.info/?probe=5d27c08853) | Nov 03, 2022 |
| Sophos        | XG                          | Firewall    | [f2f91c4258](https://bsd-hardware.info/?probe=f2f91c4258) | Nov 03, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [3021b8ee09](https://bsd-hardware.info/?probe=3021b8ee09) | Nov 03, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [7729ec0863](https://bsd-hardware.info/?probe=7729ec0863) | Nov 03, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [0841d714d0](https://bsd-hardware.info/?probe=0841d714d0) | Nov 03, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [8e0c8344af](https://bsd-hardware.info/?probe=8e0c8344af) | Nov 03, 2022 |
| HP            | 843F                        | Desktop     | [f921634ea0](https://bsd-hardware.info/?probe=f921634ea0) | Nov 02, 2022 |
| HP            | 339A                        | Desktop     | [370d93ecde](https://bsd-hardware.info/?probe=370d93ecde) | Nov 02, 2022 |
| Dell          | 0VWT90 A10                  | Server      | [b74220aee1](https://bsd-hardware.info/?probe=b74220aee1) | Nov 02, 2022 |
| Lenovo        | 00FN849 E63448-400          | Server      | [0794efc014](https://bsd-hardware.info/?probe=0794efc014) | Nov 02, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [f0e3f3177a](https://bsd-hardware.info/?probe=f0e3f3177a) | Nov 02, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [b6044fb84c](https://bsd-hardware.info/?probe=b6044fb84c) | Nov 02, 2022 |
| Dell          | 0W3F1J A00                  | Mini pc     | [7c95a69cc9](https://bsd-hardware.info/?probe=7c95a69cc9) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [7708c4bb19](https://bsd-hardware.info/?probe=7708c4bb19) | Nov 02, 2022 |
| HP            | 843F                        | Desktop     | [bba76c5ce6](https://bsd-hardware.info/?probe=bba76c5ce6) | Nov 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [bc7a300434](https://bsd-hardware.info/?probe=bc7a300434) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [22d3fc953a](https://bsd-hardware.info/?probe=22d3fc953a) | Nov 01, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [ac1e500e91](https://bsd-hardware.info/?probe=ac1e500e91) | Nov 01, 2022 |
| ASRock        | H670M-ITX/ax                | Desktop     | [bb78d5d8ea](https://bsd-hardware.info/?probe=bb78d5d8ea) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [871a5c449f](https://bsd-hardware.info/?probe=871a5c449f) | Nov 01, 2022 |
| Dell          | 09T7VV A02                  | Server      | [6e89de5b97](https://bsd-hardware.info/?probe=6e89de5b97) | Nov 01, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [8b2537708c](https://bsd-hardware.info/?probe=8b2537708c) | Nov 01, 2022 |
| Sophos        | SG                          | Firewall    | [ef9269be7e](https://bsd-hardware.info/?probe=ef9269be7e) | Nov 01, 2022 |
| ASRock        | H110 Pro BTC+               | Desktop     | [fb24f0fa6e](https://bsd-hardware.info/?probe=fb24f0fa6e) | Nov 01, 2022 |
| Sophos        | XG                          | Firewall    | [a245d23614](https://bsd-hardware.info/?probe=a245d23614) | Nov 01, 2022 |
| ASUSTek       | K30AM-J_A_F_K31AM-J         | Desktop     | [f587ec97a4](https://bsd-hardware.info/?probe=f587ec97a4) | Nov 01, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [23483285a8](https://bsd-hardware.info/?probe=23483285a8) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [5758027775](https://bsd-hardware.info/?probe=5758027775) | Oct 31, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6afa103d09](https://bsd-hardware.info/?probe=6afa103d09) | Oct 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [09cb46f6bf](https://bsd-hardware.info/?probe=09cb46f6bf) | Oct 31, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [6f21c02bba](https://bsd-hardware.info/?probe=6f21c02bba) | Oct 31, 2022 |
| Supermicro    | X10DRU-i+                   | Desktop     | [1ffd63a929](https://bsd-hardware.info/?probe=1ffd63a929) | Oct 31, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [4dfd35f622](https://bsd-hardware.info/?probe=4dfd35f622) | Oct 31, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [d2d5364c96](https://bsd-hardware.info/?probe=d2d5364c96) | Oct 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [9737a80a1c](https://bsd-hardware.info/?probe=9737a80a1c) | Oct 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [c14a3eb06b](https://bsd-hardware.info/?probe=c14a3eb06b) | Oct 31, 2022 |
| Supermicro    | X7SPA-HF                    | Desktop     | [18b3b416ce](https://bsd-hardware.info/?probe=18b3b416ce) | Oct 31, 2022 |
| ASRock        | H110 Pro BTC+               | Desktop     | [20f2ab4251](https://bsd-hardware.info/?probe=20f2ab4251) | Oct 30, 2022 |
| Sophos        | SG                          | Firewall    | [cab7a59023](https://bsd-hardware.info/?probe=cab7a59023) | Oct 30, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OPNsense/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| OPNsense 21.7.7  | 281       | 4.47%   |
| OPNsense 22.7.10 | 268       | 4.26%   |
| OPNsense 21.1    | 240       | 3.82%   |
| OPNsense 21.7.1  | 229       | 3.64%   |
| OPNsense 22.1    | 227       | 3.61%   |
| OPNsense 21.7.3  | 225       | 3.58%   |
| OPNsense 21.1.5  | 225       | 3.58%   |
| OPNsense 22.7.4  | 214       | 3.4%    |
| OPNsense 20.7.8  | 214       | 3.4%    |
| OPNsense 21.1.3  | 205       | 3.26%   |
| OPNsense 22.1.6  | 192       | 3.05%   |
| OPNsense 22.1.8  | 187       | 2.97%   |
| OPNsense 22.7.6  | 182       | 2.89%   |
| OPNsense 21.1.4  | 175       | 2.78%   |
| OPNsense 22.1.10 | 172       | 2.74%   |
| OPNsense 22.7.9  | 169       | 2.69%   |
| OPNsense 21.1.1  | 157       | 2.5%    |
| OPNsense 21.1.2  | 147       | 2.34%   |
| OPNsense 22.1.4  | 134       | 2.13%   |
| OPNsense 21.7.6  | 131       | 2.08%   |
| OPNsense 22.7    | 129       | 2.05%   |
| OPNsense 21.1.6  | 129       | 2.05%   |
| OPNsense 21.1.7  | 127       | 2.02%   |
| OPNsense 22.7.8  | 123       | 1.96%   |
| OPNsense 22.7.2  | 123       | 1.96%   |
| OPNsense 21.1.8  | 122       | 1.94%   |
| OPNsense 22.1.2  | 120       | 1.91%   |
| OPNsense 22.7.7  | 116       | 1.85%   |
| OPNsense 22.1.1  | 116       | 1.85%   |
| OPNsense 21.7.5  | 113       | 1.8%    |
| OPNsense 22.1.7  | 106       | 1.69%   |
| OPNsense 21.7.2  | 95        | 1.51%   |
| OPNsense 21.7.4  | 93        | 1.48%   |
| OPNsense 21.7    | 92        | 1.46%   |
| OPNsense 22.1.9  | 89        | 1.42%   |
| OPNsense 21.7.8  | 84        | 1.34%   |
| OPNsense 22.1.3  | 76        | 1.21%   |
| OPNsense 22.7.5  | 69        | 1.1%    |
| OPNsense 22.7.1  | 63        | 1%      |
| OPNsense 22.1.5  | 63        | 1%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| OPNsense | 4521      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 4508      | 99.71%  |
| arm64 | 12        | 0.27%   |
| i386  | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 4520      | 99.98%  |
| helloDesktop | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 4521      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 4521      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4475      | 98.55%  |
| C       | 65        | 1.43%   |
| en_US   | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 4185      | 91.7%   |
| BIOS | 379       | 8.3%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 3469      | 74.92%  |
| Zfs    | 1160      | 25.05%  |
| Cd9660 | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 4238      | 93.08%  |
| MBR     | 255       | 5.6%    |
| Unknown | 56        | 1.23%   |
| BSD     | 4         | 0.09%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 498       | 11.02%  |
| Dell                       | 492       | 10.88%  |
| Hewlett-Packard            | 375       | 8.29%   |
| Supermicro                 | 310       | 6.86%   |
| Intel                      | 286       | 6.33%   |
| Protectli                  | 245       | 5.42%   |
| PC Engines                 | 236       | 5.22%   |
| ASUSTek Computer           | 204       | 4.51%   |
| ASRock                     | 179       | 3.96%   |
| AMI                        | 167       | 3.69%   |
| Lenovo                     | 162       | 3.58%   |
| Gigabyte Technology        | 138       | 3.05%   |
| Sophos                     | 113       | 2.5%    |
| Fujitsu                    | 106       | 2.34%   |
| MSI                        | 102       | 2.26%   |
| ZOTAC                      | 83        | 1.84%   |
| Deciso                     | 66        | 1.46%   |
| BESSTAR Tech               | 55        | 1.22%   |
| Shuttle                    | 51        | 1.13%   |
| Techvision                 | 36        | 0.8%    |
| MW                         | 30        | 0.66%   |
| AWOW                       | 29        | 0.64%   |
| Acer                       | 27        | 0.6%    |
| Hardkernel                 | 26        | 0.58%   |
| CompuLab                   | 26        | 0.58%   |
| Biostar                    | 26        | 0.58%   |
| AZW                        | 21        | 0.46%   |
| ShenZhen MinWin Technology | 17        | 0.38%   |
| CheckPoint                 | 15        | 0.33%   |
| ASRockRack                 | 15        | 0.33%   |
| YANYU                      | 14        | 0.31%   |
| Apple                      | 14        | 0.31%   |
| AAEON                      | 14        | 0.31%   |
| Thomas-Krenn.AG            | 12        | 0.27%   |
| Foxconn                    | 12        | 0.27%   |
| CncTion                    | 12        | 0.27%   |
| Cisco                      | 12        | 0.27%   |
| Seeed Studio               | 11        | 0.24%   |
| Inventec                   | 11        | 0.24%   |
| HPE                        | 10        | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 513       | 11.35%  |
| AMI Aptio CRB                       | 131       | 2.9%    |
| PC Engines APU2                     | 117       | 2.59%   |
| Protectli FW4B                      | 101       | 2.23%   |
| Intel Q3XXG4-P V1.0                 | 99        | 2.19%   |
| Supermicro Super Server             | 88        | 1.95%   |
| PC Engines apu4                     | 80        | 1.77%   |
| Protectli FW6                       | 76        | 1.68%   |
| Sophos SG                           | 58        | 1.28%   |
| Fujitsu FUTRO S920                  | 47        | 1.04%   |
| HP t620 PLUS Quad Core TC           | 45        | 1%      |
| HP t730 Thin Client                 | 39        | 0.86%   |
| Dell PowerEdge R210 II              | 39        | 0.86%   |
| Techvision TVI7309X                 | 36        | 0.8%    |
| Sophos XG                           | 31        | 0.69%   |
| ASUS All Series                     | 31        | 0.69%   |
| MW GMLK-2_5G4L                      | 30        | 0.66%   |
| Dell OptiPlex 3020                  | 30        | 0.66%   |
| Dell OptiPlex 9020                  | 29        | 0.64%   |
| Dell OptiPlex 7010                  | 26        | 0.58%   |
| Sophos UTM                          | 24        | 0.53%   |
| HARDKERNEL ODROID-H2                | 24        | 0.53%   |
| HP EliteDesk 800 G1 SFF             | 20        | 0.44%   |
| ZOTAC ZBOX-CI329NANO                | 19        | 0.42%   |
| Supermicro X9SCL/X9SCM              | 19        | 0.42%   |
| Supermicro X10SLH-N6-ST031          | 19        | 0.42%   |
| Supermicro A1SAi                    | 19        | 0.42%   |
| Deciso Netboard A20                 | 19        | 0.42%   |
| CompuLab fitlet2                    | 19        | 0.42%   |
| AWOW PC BOX                         | 19        | 0.42%   |
| Protectli VP2410                    | 18        | 0.4%    |
| Dell Wyse 5070 Extended Thin Client | 18        | 0.4%    |
| PC Engines APU3                     | 16        | 0.35%   |
| PC Engines APU                      | 15        | 0.33%   |
| BESSTAR Tech GK41                   | 15        | 0.33%   |
| ZOTAC ZBOX-CI323NANO                | 14        | 0.31%   |
| Protectli FW2B                      | 14        | 0.31%   |
| Intel CRESCENTBAY                   | 14        | 0.31%   |
| ZOTAC ZBOX-CI327NANO-GS-01          | 13        | 0.29%   |
| Dell PowerEdge R610                 | 13        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 513       | 11.35%  |
| Dell OptiPlex              | 223       | 4.93%   |
| Dell PowerEdge             | 185       | 4.09%   |
| AMI Aptio                  | 133       | 2.94%   |
| PC Engines APU2            | 117       | 2.59%   |
| Lenovo ThinkCentre         | 107       | 2.37%   |
| Protectli FW4B             | 101       | 2.23%   |
| Intel Q3XXG4-P             | 99        | 2.19%   |
| Supermicro Super           | 88        | 1.95%   |
| HP ProLiant                | 87        | 1.92%   |
| PC Engines apu4            | 80        | 1.77%   |
| Protectli FW6              | 76        | 1.68%   |
| Fujitsu FUTRO              | 64        | 1.42%   |
| Sophos SG                  | 58        | 1.28%   |
| HP ProDesk                 | 52        | 1.15%   |
| HP EliteDesk               | 51        | 1.13%   |
| HP t620                    | 47        | 1.04%   |
| HP Compaq                  | 45        | 1%      |
| HP t730                    | 39        | 0.86%   |
| Deciso Netboard            | 37        | 0.82%   |
| Techvision TVI7309X        | 36        | 0.8%    |
| Sophos XG                  | 31        | 0.69%   |
| ASUS All                   | 31        | 0.69%   |
| MW GMLK-2                  | 30        | 0.66%   |
| ASUS PRIME                 | 27        | 0.6%    |
| Sophos UTM                 | 24        | 0.53%   |
| Hardkernel ODROID-H2       | 24        | 0.53%   |
| Dell Wyse                  | 23        | 0.51%   |
| Fujitsu ESPRIMO            | 21        | 0.46%   |
| Dell Precision             | 20        | 0.44%   |
| ZOTAC ZBOX-CI329NANO       | 19        | 0.42%   |
| Supermicro X9SCL           | 19        | 0.42%   |
| Supermicro X10SLH-N6-ST031 | 19        | 0.42%   |
| Supermicro A1SAi           | 19        | 0.42%   |
| CompuLab fitlet2           | 19        | 0.42%   |
| AWOW PC                    | 19        | 0.42%   |
| Protectli VP2410           | 18        | 0.4%    |
| Lenovo ThinkPad            | 18        | 0.4%    |
| Supermicro 1HE             | 17        | 0.38%   |
| PC Engines APU3            | 16        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 641       | 14.18%  |
| 2019    | 480       | 10.62%  |
| 2016    | 451       | 9.98%   |
| 2020    | 436       | 9.64%   |
| 2014    | 400       | 8.85%   |
| 2021    | 395       | 8.74%   |
| 2017    | 285       | 6.3%    |
| 2013    | 274       | 6.06%   |
| 2022    | 262       | 5.8%    |
| 2015    | 232       | 5.13%   |
| 2011    | 203       | 4.49%   |
| 2012    | 190       | 4.2%    |
| 2010    | 120       | 2.65%   |
| 2009    | 68        | 1.5%    |
| 2008    | 48        | 1.06%   |
| 2007    | 18        | 0.4%    |
| 2006    | 9         | 0.2%    |
| Unknown | 6         | 0.13%   |
| 2023    | 1         | 0.02%   |
| 2005    | 1         | 0.02%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 3226      | 71.36%  |
| Mini pc        | 496       | 10.97%  |
| Server         | 479       | 10.6%   |
| Notebook       | 175       | 3.87%   |
| Firewall       | 135       | 2.99%   |
| All in one     | 6         | 0.13%   |
| Convertible    | 3         | 0.07%   |
| System on chip | 1         | 0.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4195      | 92.79%  |
| Yes  | 326       | 7.21%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 1886      | 40.76%  |
| 4.01-8.0        | 1149      | 24.83%  |
| 16.01-24.0      | 894       | 19.32%  |
| 32.01-64.0      | 310       | 6.7%    |
| 2.01-3.0        | 186       | 4.02%   |
| 64.01-256.0     | 99        | 2.14%   |
| 24.01-32.0      | 42        | 0.91%   |
| 3.01-4.0        | 33        | 0.71%   |
| 1.01-2.0        | 15        | 0.32%   |
| 0.51-1.0        | 9         | 0.19%   |
| More than 256.0 | 4         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 2741      | 58.21%  |
| 0.51-1.0    | 1291      | 27.42%  |
| 1.01-2.0    | 399       | 8.47%   |
| 2.01-3.0    | 90        | 1.91%   |
| 4.01-8.0    | 81        | 1.72%   |
| 3.01-4.0    | 51        | 1.08%   |
| 8.01-16.0   | 33        | 0.7%    |
| 16.01-24.0  | 10        | 0.21%   |
| 24.01-32.0  | 6         | 0.13%   |
| 32.01-64.0  | 3         | 0.06%   |
| 64.01-256.0 | 3         | 0.06%   |
| 0           | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3718      | 80.95%  |
| 0      | 458       | 9.97%   |
| 2      | 355       | 7.73%   |
| 3      | 37        | 0.81%   |
| 4      | 15        | 0.33%   |
| 5      | 5         | 0.11%   |
| 25     | 2         | 0.04%   |
| 6      | 2         | 0.04%   |
| 8      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3958      | 86.99%  |
| Yes       | 592       | 13.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4509      | 99.73%  |
| No        | 12        | 0.27%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3666      | 80.25%  |
| Yes       | 902       | 19.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4066      | 89.34%  |
| Yes       | 485       | 10.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1313      | 28.93%  |
| Germany      | 1033      | 22.76%  |
| UK           | 188       | 4.14%   |
| Canada       | 184       | 4.05%   |
| France       | 163       | 3.59%   |
| Netherlands  | 129       | 2.84%   |
| Australia    | 117       | 2.58%   |
| Austria      | 110       | 2.42%   |
| Switzerland  | 105       | 2.31%   |
| Poland       | 90        | 1.98%   |
| Sweden       | 81        | 1.78%   |
| Brazil       | 76        | 1.67%   |
| Italy        | 63        | 1.39%   |
| Russia       | 59        | 1.3%    |
| China        | 53        | 1.17%   |
| Spain        | 49        | 1.08%   |
| Belgium      | 39        | 0.86%   |
| Denmark      | 36        | 0.79%   |
| Finland      | 35        | 0.77%   |
| Romania      | 34        | 0.75%   |
| Portugal     | 34        | 0.75%   |
| Norway       | 31        | 0.68%   |
| South Korea  | 30        | 0.66%   |
| Indonesia    | 29        | 0.64%   |
| Czechia      | 29        | 0.64%   |
| South Africa | 28        | 0.62%   |
| Taiwan       | 25        | 0.55%   |
| Hungary      | 23        | 0.51%   |
| New Zealand  | 19        | 0.42%   |
| India        | 19        | 0.42%   |
| Japan        | 17        | 0.37%   |
| Singapore    | 15        | 0.33%   |
| Mexico       | 15        | 0.33%   |
| Israel       | 15        | 0.33%   |
| Hong Kong    | 15        | 0.33%   |
| Bulgaria     | 15        | 0.33%   |
| Slovenia     | 12        | 0.26%   |
| Lithuania    | 12        | 0.26%   |
| Ukraine      | 9         | 0.2%    |
| Turkey       | 9         | 0.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 85        | 1.66%   |
| Munich            | 49        | 0.96%   |
| Hamburg           | 48        | 0.94%   |
| Vienna            | 47        | 0.92%   |
| Paris             | 36        | 0.71%   |
| Frankfurt am Main | 29        | 0.57%   |
| Cologne           | 27        | 0.53%   |
| Sydney            | 26        | 0.51%   |
| Zurich            | 23        | 0.45%   |
| Melbourne         | 23        | 0.45%   |
| London            | 23        | 0.45%   |
| Moscow            | 22        | 0.43%   |
| Toronto           | 21        | 0.41%   |
| Bucharest         | 21        | 0.41%   |
| Stuttgart         | 20        | 0.39%   |
| Seattle           | 19        | 0.37%   |
| Denver            | 19        | 0.37%   |
| Chicago           | 19        | 0.37%   |
| Warsaw            | 18        | 0.35%   |
| Austin            | 18        | 0.35%   |
| Karlsruhe         | 17        | 0.33%   |
| Dallas            | 17        | 0.33%   |
| Perth             | 16        | 0.31%   |
| New York          | 16        | 0.31%   |
| Jakarta           | 16        | 0.31%   |
| Brisbane          | 16        | 0.31%   |
| Amsterdam         | 16        | 0.31%   |
| Singapore         | 14        | 0.27%   |
| Mountain View     | 14        | 0.27%   |
| Stockholm         | 13        | 0.25%   |
| Madrid            | 13        | 0.25%   |
| Hanover           | 13        | 0.25%   |
| Columbus          | 13        | 0.25%   |
| Ottawa            | 12        | 0.24%   |
| Montreal          | 12        | 0.24%   |
| Johannesburg      | 12        | 0.24%   |
| Oslo              | 11        | 0.22%   |
| Los Angeles       | 11        | 0.22%   |
| Houston           | 11        | 0.22%   |
| Helsinki          | 11        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 641       | 933    | 14.4%   |
| Kingston            | 427       | 625    | 9.59%   |
| Transcend           | 345       | 500    | 7.75%   |
| WDC                 | 336       | 515    | 7.55%   |
| Seagate             | 242       | 387    | 5.44%   |
| SanDisk             | 237       | 324    | 5.32%   |
| Intel               | 219       | 324    | 4.92%   |
| Crucial             | 203       | 312    | 4.56%   |
| Hoodisk             | 175       | 250    | 3.93%   |
| China               | 122       | 173    | 2.74%   |
| Phison              | 113       | 163    | 2.54%   |
| Toshiba             | 102       | 174    | 2.29%   |
| A-DATA Technology   | 97        | 141    | 2.18%   |
| FORESEE             | 73        | 107    | 1.64%   |
| Hewlett-Packard     | 66        | 116    | 1.48%   |
| Hitachi             | 52        | 72     | 1.17%   |
| Protectli           | 50        | 82     | 1.12%   |
| Micron Technology   | 50        | 78     | 1.12%   |
| OCZ                 | 48        | 69     | 1.08%   |
| Dogfish             | 48        | 77     | 1.08%   |
| SPCC                | 46        | 67     | 1.03%   |
| Apacer              | 43        | 52     | 0.97%   |
| PNY                 | 40        | 66     | 0.9%    |
| Innodisk            | 38        | 46     | 0.85%   |
| Intenso             | 36        | 63     | 0.81%   |
| SK hynix            | 35        | 48     | 0.79%   |
| HGST                | 34        | 75     | 0.76%   |
| BIWIN               | 34        | 50     | 0.76%   |
| Corsair             | 30        | 46     | 0.67%   |
| LITEON              | 23        | 33     | 0.52%   |
| LITEONIT            | 21        | 26     | 0.47%   |
| Patriot             | 19        | 29     | 0.43%   |
| Kston               | 19        | 25     | 0.43%   |
| ATP                 | 19        | 22     | 0.43%   |
| Silicon Motion      | 18        | 20     | 0.4%    |
| KingSpec            | 17        | 20     | 0.38%   |
| Gigabyte Technology | 16        | 22     | 0.36%   |
| ShiJi               | 15        | 24     | 0.34%   |
| Team                | 13        | 16     | 0.29%   |
| Plextor             | 13        | 20     | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Phison SATA SSD 16GB            | 62        | 1.37%   |
| Kingston SUV500MS120G 120GB     | 54        | 1.2%    |
| Kingston SA400S37240G 240GB     | 54        | 1.2%    |
| Kingston SA400S37120G 120GB     | 50        | 1.11%   |
| Samsung SSD 850 EVO 250GB       | 49        | 1.09%   |
| Hoodisk SSD 64GB                | 48        | 1.06%   |
| Hoodisk SSD 32GB                | 48        | 1.06%   |
| Hoodisk SSD 128GB               | 47        | 1.04%   |
| Transcend TS128GMSA230S 128GB   | 43        | 0.95%   |
| FORESEE 128GB SSD               | 41        | 0.91%   |
| Crucial CT240BX500SSD1 240GB    | 34        | 0.75%   |
| HP RAID 1(1+0) 800GB            | 32        | 0.71%   |
| Kingston SUV500MS240G 240GB     | 29        | 0.64%   |
| Crucial CT120BX500SSD1 120GB    | 28        | 0.62%   |
| Transcend TS64GMSA230S 64GB     | 27        | 0.6%    |
| Seagate ST500DM002-1BD142 500GB | 26        | 0.58%   |
| BIWIN SSD 128GB                 | 26        | 0.58%   |
| Crucial CT250MX500SSD1 250GB    | 25        | 0.55%   |
| Kingston SV300S37A120G 120GB    | 24        | 0.53%   |
| China SATA SSD 16GB             | 24        | 0.53%   |
| Transcend TS256GMSA230S 256GB   | 23        | 0.51%   |
| Samsung SSD 860 EVO 250GB       | 23        | 0.51%   |
| Transcend TS256GMTS952T2 256GB  | 22        | 0.49%   |
| Samsung SSD 840 EVO 120GB       | 22        | 0.49%   |
| PNY CS900 120GB SSD             | 22        | 0.49%   |
| Kingston SKC600MS256G 256GB     | 22        | 0.49%   |
| SanDisk SDSSDA120G 120GB        | 20        | 0.44%   |
| Samsung SSD 860 EVO 500GB       | 20        | 0.44%   |
| Samsung SSD 850 EVO 120GB       | 20        | 0.44%   |
| Protectli 120GB mSATA           | 20        | 0.44%   |
| FORESEE 64GB SSD                | 20        | 0.44%   |
| A-DATA SU650 120GB              | 20        | 0.44%   |
| Samsung SSD 870 EVO 250GB       | 19        | 0.42%   |
| Samsung SSD 850 EVO 500GB       | 19        | 0.42%   |
| Samsung SSD 840 EVO 250GB       | 19        | 0.42%   |
| A-DATA IM2S3134N-064GM 64GB     | 19        | 0.42%   |
| WDC WDS120G2G0A-00JH30 120GB    | 18        | 0.4%    |
| Transcend TS64GSSD370 64GB      | 18        | 0.4%    |
| Hoodisk SSD 16GB                | 18        | 0.4%    |
| Transcend TS64GMSA370 64GB      | 17        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 225       | 355    | 32.33%  |
| WDC                 | 221       | 342    | 31.75%  |
| Toshiba             | 67        | 118    | 9.63%   |
| Hitachi             | 52        | 72     | 7.47%   |
| HGST                | 34        | 75     | 4.89%   |
| Samsung Electronics | 28        | 36     | 4.02%   |
| Hewlett-Packard     | 27        | 53     | 3.88%   |
| Maxtor              | 9         | 10     | 1.29%   |
| Fujitsu             | 6         | 7      | 0.86%   |
| HPE                 | 5         | 17     | 0.72%   |
| Apple               | 5         | 7      | 0.72%   |
| Dell                | 3         | 49     | 0.43%   |
| NETAPP              | 2         | 4      | 0.29%   |
| LSILOGIC            | 2         | 5      | 0.29%   |
| Cisco               | 2         | 4      | 0.29%   |
| Adaptec             | 2         | 2      | 0.29%   |
| MARVELL             | 1         | 1      | 0.14%   |
| LSI                 | 1         | 1      | 0.14%   |
| InnoLite            | 1         | 1      | 0.14%   |
| IBM-207x            | 1         | 1      | 0.14%   |
| China               | 1         | 1      | 0.14%   |
| Cactus              | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 477       | 675    | 14.37%  |
| Kingston            | 387       | 565    | 11.66%  |
| Transcend           | 317       | 469    | 9.55%   |
| SanDisk             | 236       | 323    | 7.11%   |
| Intel               | 196       | 295    | 5.91%   |
| Crucial             | 183       | 284    | 5.51%   |
| Hoodisk             | 174       | 249    | 5.24%   |
| China               | 121       | 172    | 3.65%   |
| Phison              | 96        | 131    | 2.89%   |
| A-DATA Technology   | 85        | 121    | 2.56%   |
| FORESEE             | 71        | 104    | 2.14%   |
| WDC                 | 69        | 97     | 2.08%   |
| Protectli           | 50        | 82     | 1.51%   |
| OCZ                 | 48        | 69     | 1.45%   |
| Dogfish             | 48        | 77     | 1.45%   |
| Micron Technology   | 47        | 73     | 1.42%   |
| Apacer              | 43        | 52     | 1.3%    |
| Hewlett-Packard     | 41        | 63     | 1.24%   |
| SPCC                | 39        | 56     | 1.18%   |
| PNY                 | 39        | 65     | 1.18%   |
| Innodisk            | 38        | 46     | 1.14%   |
| Intenso             | 36        | 63     | 1.08%   |
| BIWIN               | 34        | 50     | 1.02%   |
| Toshiba             | 26        | 43     | 0.78%   |
| Corsair             | 26        | 39     | 0.78%   |
| LITEON              | 22        | 32     | 0.66%   |
| SK hynix            | 21        | 29     | 0.63%   |
| LITEONIT            | 21        | 26     | 0.63%   |
| Kston               | 19        | 25     | 0.57%   |
| KingSpec            | 17        | 20     | 0.51%   |
| ATP                 | 16        | 16     | 0.48%   |
| Patriot             | 15        | 24     | 0.45%   |
| ShiJi               | 14        | 23     | 0.42%   |
| Plextor             | 12        | 18     | 0.36%   |
| Seagate             | 11        | 25     | 0.33%   |
| Netac               | 10        | 14     | 0.3%    |
| Team                | 9         | 12     | 0.27%   |
| Mushkin             | 9         | 14     | 0.27%   |
| Gigabyte Technology | 9         | 14     | 0.27%   |
| Supermicro          | 8         | 8      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3160      | 4832   | 74.3%   |
| HDD  | 652       | 1162   | 15.33%  |
| NVMe | 441       | 651    | 10.37%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3700      | 5994   | 89.35%  |
| NVMe | 441       | 651    | 10.65%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3437      | 5431   | 90.95%  |
| 0.51-1.0   | 284       | 437    | 7.52%   |
| 1.01-2.0   | 43        | 81     | 1.14%   |
| 2.01-3.0   | 8         | 11     | 0.21%   |
| 3.01-4.0   | 4         | 5      | 0.11%   |
| 4.01-10.0  | 3         | 29     | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2189      | 47.03%  |
| 251-500        | 630       | 13.54%  |
| 51-100         | 612       | 13.15%  |
| 21-50          | 602       | 12.94%  |
| 1-20           | 357       | 7.67%   |
| 501-1000       | 206       | 4.43%   |
| 1001-2000      | 41        | 0.88%   |
| More than 3000 | 8         | 0.17%   |
| 2001-3000      | 5         | 0.11%   |
| Unknown        | 4         | 0.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 4423      | 95.24%  |
| 21-50   | 155       | 3.34%   |
| 51-100  | 48        | 1.03%   |
| 101-250 | 14        | 0.3%    |
| Unknown | 4         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 13        | 24     | 2.77%   |
| Kingston SV300S37A120G 120GB      | 11        | 13     | 2.35%   |
| Apacer 16GB SATA Flash Drive      | 8         | 10     | 1.71%   |
| Kingston SV300S37A60G 64GB        | 7         | 9      | 1.49%   |
| Seagate ST500LM021-1KJ152 500GB   | 6         | 6      | 1.28%   |
| Kingston SMS200S3120G 120GB       | 6         | 7      | 1.28%   |
| HGST HTS725050A7E630 500GB        | 6         | 11     | 1.28%   |
| Seagate ST3160815AS 160GB         | 5         | 6      | 1.07%   |
| Crucial CT275MX300SSD1 275GB      | 5         | 6      | 1.07%   |
| Kingston SMS200S360G 64GB         | 4         | 4      | 0.85%   |
| Intel SSDSA2M160G2GC 160GB        | 4         | 6      | 0.85%   |
| WDC WDS240G2G0A-00JH30 240GB      | 3         | 4      | 0.64%   |
| WDC WDS120G2G0A-00JH30 120GB      | 3         | 4      | 0.64%   |
| WDC WD1600AAJS-75M0A0 160GB       | 3         | 3      | 0.64%   |
| VisionTek mSATA 120GB             | 3         | 7      | 0.64%   |
| Seagate ST500LT012-1DG142 500GB   | 3         | 4      | 0.64%   |
| Seagate ST3500418AS 500GB         | 3         | 9      | 0.64%   |
| Seagate ST3250310AS 250GB         | 3         | 3      | 0.64%   |
| Seagate ST320LT007-9ZV142 320GB   | 3         | 3      | 0.64%   |
| Seagate ST3160318AS 160GB         | 3         | 6      | 0.64%   |
| Samsung Electronics HM160HI 160GB | 3         | 3      | 0.64%   |
| LITEON CV8-8E128-HP 128GB         | 3         | 4      | 0.64%   |
| Kingston SUV400S37120G 120GB      | 3         | 5      | 0.64%   |
| Intel SSDSC2CT120A3 120GB         | 3         | 3      | 0.64%   |
| Intel SSDSC2BW120H6 120GB         | 3         | 4      | 0.64%   |
| Hitachi HDS721050CLA660 500GB     | 3         | 4      | 0.64%   |
| Crucial CT128MX100SSD1 128GB      | 3         | 5      | 0.64%   |
| WDC WD800JD-60LSA5 80GB           | 2         | 2      | 0.43%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 2         | 3      | 0.43%   |
| WDC WD5000AAKS-22V1A0 500GB       | 2         | 2      | 0.43%   |
| Toshiba MQ01ABD100 1TB            | 2         | 2      | 0.43%   |
| Toshiba MQ01ABD075 752GB          | 2         | 2      | 0.43%   |
| Toshiba DT01ACA100 1TB            | 2         | 2      | 0.43%   |
| Toshiba DT01ACA050 500GB          | 2         | 2      | 0.43%   |
| SK hynix SC308 SATA 128GB         | 2         | 3      | 0.43%   |
| SK hynix SC210 mSATA 256GB        | 2         | 2      | 0.43%   |
| Seagate ST9320423AS 320GB         | 2         | 2      | 0.43%   |
| Seagate ST500LT012-9WS142 500GB   | 2         | 3      | 0.43%   |
| Seagate ST380815AS 80GB           | 2         | 2      | 0.43%   |
| Seagate ST3160310CS 160GB         | 2         | 2      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 86        | 135    | 18.34%  |
| WDC                 | 60        | 86     | 12.79%  |
| Kingston            | 47        | 59     | 10.02%  |
| Intel               | 39        | 59     | 8.32%   |
| Samsung Electronics | 33        | 48     | 7.04%   |
| Crucial             | 24        | 35     | 5.12%   |
| Hitachi             | 23        | 29     | 4.9%    |
| Toshiba             | 20        | 25     | 4.26%   |
| SanDisk             | 17        | 30     | 3.62%   |
| Apacer              | 11        | 13     | 2.35%   |
| OCZ                 | 10        | 13     | 2.13%   |
| HGST                | 10        | 16     | 2.13%   |
| China               | 7         | 8      | 1.49%   |
| A-DATA Technology   | 7         | 10     | 1.49%   |
| SK hynix            | 6         | 8      | 1.28%   |
| Micron Technology   | 6         | 6      | 1.28%   |
| Dogfish             | 5         | 11     | 1.07%   |
| Corsair             | 5         | 8      | 1.07%   |
| Maxtor              | 4         | 4      | 0.85%   |
| LITEON              | 4         | 5      | 0.85%   |
| VisionTek           | 3         | 7      | 0.64%   |
| KingDian            | 3         | 3      | 0.64%   |
| HP Phison           | 3         | 3      | 0.64%   |
| Hewlett-Packard     | 3         | 4      | 0.64%   |
| BIWIN               | 3         | 5      | 0.64%   |
| Transcend           | 2         | 3      | 0.43%   |
| SPCC                | 2         | 4      | 0.43%   |
| Phison              | 2         | 2      | 0.43%   |
| MyDigitalSSD        | 2         | 4      | 0.43%   |
| Intenso             | 2         | 2      | 0.43%   |
| ZTC                 | 1         | 3      | 0.21%   |
| Wintec              | 1         | 1      | 0.21%   |
| V-GeN               | 1         | 1      | 0.21%   |
| Terabit             | 1         | 1      | 0.21%   |
| SMI                 | 1         | 1      | 0.21%   |
| ShiJi               | 1         | 1      | 0.21%   |
| PNY                 | 1         | 1      | 0.21%   |
| Plextor             | 1         | 1      | 0.21%   |
| Netac               | 1         | 1      | 0.21%   |
| Mushkin             | 1         | 1      | 0.21%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 86        | 135    | 40.57%  |
| WDC                 | 53        | 77     | 25%     |
| Hitachi             | 23        | 29     | 10.85%  |
| Toshiba             | 15        | 16     | 7.08%   |
| Samsung Electronics | 14        | 16     | 6.6%    |
| HGST                | 10        | 16     | 4.72%   |
| Maxtor              | 4         | 4      | 1.89%   |
| Hewlett-Packard     | 3         | 4      | 1.42%   |
| InnoLite            | 1         | 1      | 0.47%   |
| HPE                 | 1         | 3      | 0.47%   |
| China               | 1         | 1      | 0.47%   |
| Cactus              | 1         | 1      | 0.47%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 252       | 358    | 54.19%  |
| HDD  | 209       | 303    | 44.95%  |
| NVMe | 4         | 9      | 0.86%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZYLN256HCHP-000L2 256GB | 2         | 2      | 13.33%  |
| WDC WD3200BPVT-16JJ5T0 320GB                 | 1         | 1      | 6.67%   |
| WDC WD10SPZX-00Z10T0 1TB                     | 1         | 1      | 6.67%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB         | 1         | 1      | 6.67%   |
| Transcend TS32GSSD370S 32GB                  | 1         | 1      | 6.67%   |
| SK hynix SC308 SATA 256GB                    | 1         | 1      | 6.67%   |
| Seagate ST4000NM0025 4TB                     | 1         | 2      | 6.67%   |
| Seagate ST3500418AS 500GB                    | 1         | 2      | 6.67%   |
| Samsung Electronics SSD 980 250GB            | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 970 EVO Plus 500GB   | 1         | 1      | 6.67%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB   | 1         | 1      | 6.67%   |
| Kingston SV300S37A60G 64GB                   | 1         | 1      | 6.67%   |
| Intel SSDSC2BW120H6 120GB                    | 1         | 1      | 6.67%   |
| Crucial CT250P2SSD8 250GB                    | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 26.67%  |
| WDC                 | 3         | 3      | 20%     |
| Seagate             | 2         | 4      | 13.33%  |
| Transcend           | 1         | 1      | 6.67%   |
| SK hynix            | 1         | 1      | 6.67%   |
| Micron Technology   | 1         | 1      | 6.67%   |
| Kingston            | 1         | 1      | 6.67%   |
| Intel               | 1         | 1      | 6.67%   |
| Crucial             | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3649      | 5800   | 86.37%  |
| Malfunc  | 461       | 670    | 10.91%  |
| Detected | 100       | 158    | 2.37%   |
| Failed   | 15        | 17     | 0.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3681      | 71.21%  |
| AMD                              | 697       | 13.48%  |
| Samsung Electronics              | 141       | 2.73%   |
| Broadcom / LSI                   | 135       | 2.61%   |
| ASMedia Technology               | 62        | 1.2%    |
| SanDisk                          | 57        | 1.1%    |
| Hewlett-Packard                  | 49        | 0.95%   |
| Silicon Motion                   | 42        | 0.81%   |
| Kingston Technology Company      | 40        | 0.77%   |
| Phison Electronics               | 37        | 0.72%   |
| Marvell Technology Group         | 28        | 0.54%   |
| Chelsio Communications           | 26        | 0.5%    |
| Transcend                        | 24        | 0.46%   |
| Micron/Crucial Technology        | 20        | 0.39%   |
| SK hynix                         | 14        | 0.27%   |
| Nvidia                           | 13        | 0.25%   |
| JMicron Technology               | 12        | 0.23%   |
| Toshiba                          | 10        | 0.19%   |
| ADATA Technology                 | 10        | 0.19%   |
| MAXIO Technology (Hangzhou)      | 8         | 0.15%   |
| Silicon Image                    | 6         | 0.12%   |
| Shenzhen Longsys Electronics     | 6         | 0.12%   |
| Seagate Technology               | 6         | 0.12%   |
| Micron Technology                | 5         | 0.1%    |
| KIOXIA                           | 5         | 0.1%    |
| ATP ELECTRONICS                  | 5         | 0.1%    |
| Adaptec                          | 5         | 0.1%    |
| VIA Technologies                 | 3         | 0.06%   |
| Solid State Storage Technology   | 3         | 0.06%   |
| Realtek Semiconductor            | 3         | 0.06%   |
| Dell                             | 3         | 0.06%   |
| XenSource                        | 2         | 0.04%   |
| Lite-On Technology               | 2         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |
| Union Memory (Shenzhen)          | 1         | 0.02%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| Innodisk                         | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 486       | 8.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 409       | 7.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 299       | 5.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 271       | 4.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 268       | 4.6%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 249       | 4.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 214       | 3.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 174       | 2.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 148       | 2.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 110       | 1.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 103       | 1.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 98        | 1.68%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 97        | 1.66%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 91        | 1.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 88        | 1.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 86        | 1.48%   |
| Unknown                                                                                 | 85        | 1.46%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 83        | 1.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 82        | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 74        | 1.27%   |
| Intel SATA Controller [RAID mode]                                                       | 68        | 1.17%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                        | 68        | 1.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 63        | 1.08%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 61        | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 54        | 0.93%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 52        | 0.89%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 50        | 0.86%   |
| Intel Atom Processor C3000 Series SATA Controller 0                                     | 50        | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 50        | 0.86%   |
| AMD FCH IDE Controller                                                                  | 46        | 0.79%   |
| Intel Atom Processor C3000 Series SATA Controller 1                                     | 45        | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 42        | 0.72%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                        | 42        | 0.72%   |
| AMD 400 Series Chipset SATA Controller                                                  | 42        | 0.72%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 39        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 39        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 39        | 0.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 38        | 0.65%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 37        | 0.63%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 36        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3881      | 73.5%   |
| IDE  | 576       | 10.91%  |
| NVMe | 460       | 8.71%   |
| RAID | 284       | 5.38%   |
| SCSI | 46        | 0.87%   |
| SAS  | 33        | 0.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 3777      | 83.36%  |
| AMD     | 740       | 16.33%  |
| ARM     | 9         | 0.2%    |
| Unknown | 3         | 0.07%   |
| VIA     | 2         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                          | 214       | 4.67%   |
| Intel Celeron J4125 CPU @ 2.00GHz         | 175       | 3.82%   |
| Intel Celeron CPU J3160 @ 1.60GHz         | 150       | 3.27%   |
| Intel Celeron CPU J1900 @ 1.99GHz         | 139       | 3.03%   |
| Intel Celeron N5105 @ 2.00GHz             | 81        | 1.77%   |
| Intel Celeron CPU J3455 @ 1.50GHz         | 58        | 1.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz         | 55        | 1.2%    |
| Intel Core i5-6500 CPU @ 3.20GHz          | 49        | 1.07%   |
| AMD GX-420CA SOC with Radeon HD Graphics  | 49        | 1.07%   |
| Intel Core i5-3470 CPU @ 3.20GHz          | 46        | 1%      |
| Intel Core i5-4570 CPU @ 3.20GHz          | 43        | 0.94%   |
| Intel Atom CPU D525 @ 1.80GHz             | 41        | 0.89%   |
| AMD RX-427BB with AMD Radeon R7 Graphics  | 41        | 0.89%   |
| Intel Celeron J4105 CPU @ 1.50GHz         | 39        | 0.85%   |
| Intel Core i3-7100U CPU @ 2.40GHz         | 38        | 0.83%   |
| Intel Core i5-4590 CPU @ 3.30GHz          | 36        | 0.78%   |
| Intel Celeron CPU 3865U @ 1.80GHz         | 34        | 0.74%   |
| Intel Atom CPU C3558 @ 2.20GHz            | 34        | 0.74%   |
| AMD GX-415GA SOC with Radeon HD Graphics  | 34        | 0.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz         | 32        | 0.7%    |
| Intel Pentium CPU N3700 @ 1.60GHz         | 31        | 0.68%   |
| Intel Celeron CPU N3450 @ 1.10GHz         | 31        | 0.68%   |
| Intel Celeron CPU N3150 @ 1.60GHz         | 30        | 0.65%   |
| Intel Atom CPU E3845 @ 1.91GHz            | 30        | 0.65%   |
| Intel Xeon CPU D-1518 @ 2.20GHz           | 27        | 0.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz         | 26        | 0.57%   |
| Intel Celeron N4100 CPU @ 1.10GHz         | 26        | 0.57%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz  | 25        | 0.55%   |
| Intel Celeron CPU N3160 @ 1.60GHz         | 25        | 0.55%   |
| Intel Celeron CPU J1800 @ 2.41GHz         | 25        | 0.55%   |
| Intel Atom CPU C2558 @ 2.40GHz            | 23        | 0.5%    |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz       | 22        | 0.48%   |
| AMD Ryzen Embedded V1500B                 | 22        | 0.48%   |
| Intel Core i5-2400 CPU @ 3.10GHz          | 21        | 0.46%   |
| Intel Core i3-4160 CPU @ 3.60GHz          | 21        | 0.46%   |
| AMD G-T40E Processor                      | 21        | 0.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz         | 20        | 0.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz          | 20        | 0.44%   |
| Intel Celeron J4115 CPU @ 1.80GHz         | 20        | 0.44%   |
| AMD GX-222GC SOC with Radeon R5E Graphics | 20        | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 1072      | 23.5%   |
| Intel Core i5           | 752       | 16.48%  |
| Intel Xeon              | 570       | 12.49%  |
| Intel Core i3           | 420       | 9.21%   |
| AMD GX                  | 352       | 7.72%   |
| Intel Atom              | 323       | 7.08%   |
| Intel Core i7           | 269       | 5.9%    |
| Intel Pentium           | 147       | 3.22%   |
| Other                   | 95        | 2.08%   |
| AMD G                   | 45        | 0.99%   |
| AMD Ryzen 5             | 44        | 0.96%   |
| Intel Pentium Silver    | 43        | 0.94%   |
| Intel Core 2 Duo        | 43        | 0.94%   |
| AMD EPYC                | 36        | 0.79%   |
| Intel Core 2 Quad       | 33        | 0.72%   |
| AMD Ryzen Embedded      | 30        | 0.66%   |
| Intel Pentium Dual-Core | 27        | 0.59%   |
| AMD Ryzen 7             | 27        | 0.59%   |
| AMD FX                  | 24        | 0.53%   |
| Intel Pentium Gold      | 20        | 0.44%   |
| AMD Athlon              | 20        | 0.44%   |
| AMD Ryzen 3             | 13        | 0.28%   |
| AMD Ryzen 5 PRO         | 11        | 0.24%   |
| AMD A4                  | 11        | 0.24%   |
| Intel Pentium Dual      | 10        | 0.22%   |
| Intel Xeon Silver       | 9         | 0.2%    |
| ARM Cortex              | 9         | 0.2%    |
| AMD E                   | 8         | 0.18%   |
| AMD A10                 | 8         | 0.18%   |
| Intel Core 2            | 7         | 0.15%   |
| AMD Opteron             | 7         | 0.15%   |
| Intel Genuine           | 6         | 0.13%   |
| AMD A8                  | 6         | 0.13%   |
| Intel Xeon Gold         | 5         | 0.11%   |
| Intel Pentium 4         | 5         | 0.11%   |
| AMD Athlon 64 X2        | 5         | 0.11%   |
| AMD A6                  | 5         | 0.11%   |
| Intel Core i9           | 4         | 0.09%   |
| AMD Turion II Neo       | 4         | 0.09%   |
| AMD Ryzen 9             | 3         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2602      | 57.05%  |
| 2       | 1321      | 28.96%  |
| 8       | 220       | 4.82%   |
| 6       | 145       | 3.18%   |
| 12      | 79        | 1.73%   |
| Unknown | 67        | 1.47%   |
| 16      | 53        | 1.16%   |
| 1       | 38        | 0.83%   |
| 10      | 10        | 0.22%   |
| 24      | 6         | 0.13%   |
| 20      | 5         | 0.11%   |
| 64      | 4         | 0.09%   |
| 32      | 3         | 0.07%   |
| 36      | 2         | 0.04%   |
| 28      | 2         | 0.04%   |
| 3       | 2         | 0.04%   |
| 128     | 1         | 0.02%   |
| 40      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4377      | 96.75%  |
| 2       | 133       | 2.94%   |
| Unknown | 10        | 0.22%   |
| 4       | 4         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2980      | 65.6%   |
| 2       | 1494      | 32.89%  |
| Unknown | 68        | 1.5%    |
| 4       | 1         | 0.02%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 602       | 13.19%  |
| Haswell       | 540       | 11.83%  |
| KabyLake      | 538       | 11.79%  |
| Goldmont plus | 302       | 6.62%   |
| IvyBridge     | 290       | 6.35%   |
| Puma          | 256       | 5.61%   |
| Skylake       | 251       | 5.5%    |
| SandyBridge   | 243       | 5.32%   |
| Goldmont      | 214       | 4.69%   |
| Unknown       | 162       | 3.55%   |
| Broadwell     | 148       | 3.24%   |
| Jaguar        | 123       | 2.7%    |
| Penryn        | 112       | 2.45%   |
| Bonnell       | 101       | 2.21%   |
| Westmere      | 91        | 1.99%   |
| Zen           | 82        | 1.8%    |
| Core          | 70        | 1.53%   |
| Nehalem       | 65        | 1.42%   |
| CometLake     | 58        | 1.27%   |
| Bobcat        | 57        | 1.25%   |
| Steamroller   | 49        | 1.07%   |
| Zen+          | 41        | 0.9%    |
| Piledriver    | 31        | 0.68%   |
| Zen 2         | 30        | 0.66%   |
| Zen 3         | 24        | 0.53%   |
| K10           | 16        | 0.35%   |
| TigerLake     | 14        | 0.31%   |
| Excavator     | 14        | 0.31%   |
| IceLake       | 12        | 0.26%   |
| NetBurst      | 10        | 0.22%   |
| K8 Hammer     | 10        | 0.22%   |
| Bulldozer     | 5         | 0.11%   |
| K10 Llano     | 3         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2943      | 70.51%  |
| AMD                                          | 442       | 10.59%  |
| ASPEED Technology                            | 326       | 7.81%   |
| Matrox Electronics Systems                   | 322       | 7.71%   |
| Nvidia                                       | 126       | 3.02%   |
| XGI Technology (eXtreme Graphics Innovation) | 5         | 0.12%   |
| VIA Technologies                             | 2         | 0.05%   |
| Silicon Motion                               | 2         | 0.05%   |
| S3 Graphics                                  | 2         | 0.05%   |
| Cirrus Logic                                 | 2         | 0.05%   |
| Tseng Labs                                   | 1         | 0.02%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 326       | 7.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 274       | 6.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 272       | 6.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 252       | 5.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 240       | 5.7%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 151       | 3.58%   |
| Intel HD Graphics 500                                                                    | 138       | 3.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 137       | 3.25%   |
| Intel HD Graphics 620                                                                    | 126       | 2.99%   |
| Intel HD Graphics 530                                                                    | 124       | 2.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 113       | 2.68%   |
| Intel JasperLake [UHD Graphics]                                                          | 104       | 2.47%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 92        | 2.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 88        | 2.09%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 81        | 1.92%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 69        | 1.64%   |
| Matrox Electronics Systems G200eR2                                                       | 68        | 1.61%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 62        | 1.47%   |
| Intel HD Graphics 630                                                                    | 60        | 1.42%   |
| Intel UHD Graphics 620                                                                   | 59        | 1.4%    |
| Intel HD Graphics 610                                                                    | 52        | 1.23%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 49        | 1.16%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 49        | 1.16%   |
| AMD ES1000                                                                               | 49        | 1.16%   |
| Intel HD Graphics 5500                                                                   | 48        | 1.14%   |
| Matrox Electronics Systems MGA G200EH                                                    | 45        | 1.07%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 40        | 0.95%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 38        | 0.9%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 38        | 0.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 0.88%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 34        | 0.81%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 31        | 0.74%   |
| Intel HD Graphics 510                                                                    | 30        | 0.71%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 30        | 0.71%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 30        | 0.71%   |
| Intel HD Graphics 6000                                                                   | 28        | 0.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 27        | 0.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 25        | 0.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 22        | 0.52%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 22        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 2798      | 61.56%  |
| 1 x AMD                | 431       | 9.48%   |
| Other                  | 415       | 9.13%   |
| 1 x Matrox             | 319       | 7.02%   |
| 1 x ASPEED             | 307       | 6.75%   |
| 1 x Nvidia             | 111       | 2.44%   |
| 2 x Intel              | 108       | 2.38%   |
| Intel + ASPEED         | 17        | 0.37%   |
| Intel + Nvidia         | 10        | 0.22%   |
| Intel + AMD            | 7         | 0.15%   |
| 1 x XGI                | 5         | 0.11%   |
| 2 x AMD                | 3         | 0.07%   |
| 1 x VIA                | 2         | 0.04%   |
| 1 x Silicon Motion     | 2         | 0.04%   |
| 1 x Cirrus Logic       | 2         | 0.04%   |
| 2 x Intel + 1 x Nvidia | 1         | 0.02%   |
| 1 x Tseng Labs         | 1         | 0.02%   |
| 1 x SiS                | 1         | 0.02%   |
| 1 x S3 Graphics        | 1         | 0.02%   |
| Nvidia + Matrox        | 1         | 0.02%   |
| Nvidia + ASPEED        | 1         | 0.02%   |
| Intel + Matrox         | 1         | 0.02%   |
| AMD + ASPEED           | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 4115      | 90.88%  |
| Unknown | 413       | 9.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4521      | 99.98%  |
| 1.01-2.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

Zero info for selected period =(

Monitor Model
-------------

Monitor models

Zero info for selected period =(

Monitor Resolution
------------------

Monitor screen resolution

Zero info for selected period =(

Monitor Diagonal
----------------

Diagonal size in inches

Zero info for selected period =(

Monitor Width
-------------

Physical width

Zero info for selected period =(

Aspect Ratio
------------

Proportional relationship between the width and the height

Zero info for selected period =(

Monitor Area
------------

Area in inch²

Zero info for selected period =(

Pixel Density
-------------

Pixels per inch

Zero info for selected period =(

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4521      | 99.98%  |
| 1     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3795      | 59.2%   |
| Realtek Semiconductor           | 1457      | 22.73%  |
| Broadcom                        | 446       | 6.96%   |
| Qualcomm Atheros                | 229       | 3.57%   |
| IMC Networks                    | 51        | 0.8%    |
| AMD                             | 48        | 0.75%   |
| Mellanox Technologies           | 39        | 0.61%   |
| Chelsio Communications          | 37        | 0.58%   |
| Ralink Technology               | 29        | 0.45%   |
| D-Link System                   | 19        | 0.3%    |
| Marvell Technology Group        | 17        | 0.27%   |
| U-Blox                          | 15        | 0.23%   |
| TP-Link                         | 15        | 0.23%   |
| Solarflare Communications       | 13        | 0.2%    |
| QLogic                          | 12        | 0.19%   |
| Ralink                          | 11        | 0.17%   |
| American Megatrends             | 11        | 0.17%   |
| Emulex                          | 10        | 0.16%   |
| Aquantia                        | 9         | 0.14%   |
| ZTE WCDMA Technologies MSM      | 8         | 0.12%   |
| Huawei Technologies             | 8         | 0.12%   |
| Seeed Technology                | 7         | 0.11%   |
| MediaTek                        | 7         | 0.11%   |
| IBM                             | 7         | 0.11%   |
| Edimax Technology               | 7         | 0.11%   |
| Novatel Wireless                | 6         | 0.09%   |
| ICS Advent                      | 6         | 0.09%   |
| ASUSTek Computer                | 6         | 0.09%   |
| Apple                           | 6         | 0.09%   |
| VIA Technologies                | 5         | 0.08%   |
| 3Com                            | 5         | 0.08%   |
| Qualcomm Atheros Communications | 4         | 0.06%   |
| NetXen Incorporated             | 4         | 0.06%   |
| Dell                            | 4         | 0.06%   |
| Samsung Electronics             | 3         | 0.05%   |
| Nvidia                          | 3         | 0.05%   |
| Insyde Software                 | 3         | 0.05%   |
| Xiaomi                          | 2         | 0.03%   |
| SysKonnect                      | 2         | 0.03%   |
| Silicom                         | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1290      | 16.16%  |
| Intel I211 Gigabit Network Connection                                         | 886       | 11.1%   |
| Intel I210 Gigabit Network Connection                                         | 593       | 7.43%   |
| Intel I350 Gigabit Network Connection                                         | 402       | 5.04%   |
| Intel 82574L Gigabit Network Connection                                       | 298       | 3.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 195       | 2.44%   |
| Intel Ethernet Controller I225-V                                              | 184       | 2.3%    |
| Intel 82583V Gigabit Network Connection                                       | 181       | 2.27%   |
| Intel 82576 Gigabit Network Connection                                        | 155       | 1.94%   |
| Intel 82580 Gigabit Network Connection                                        | 153       | 1.92%   |
| Intel Ethernet Connection I217-LM                                             | 142       | 1.78%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 136       | 1.7%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 111       | 1.39%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 109       | 1.37%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 103       | 1.29%   |
| Realtek RTL8125 2.5GbE Controller                                             | 95        | 1.19%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 81        | 1.01%   |
| Intel Wireless 3165                                                           | 78        | 0.98%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 76        | 0.95%   |
| Intel Ethernet Connection I354                                                | 70        | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                         | 58        | 0.73%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 58        | 0.73%   |
| Intel Ethernet Connection X553 1GbE                                           | 56        | 0.7%    |
| Intel Ethernet Controller I226-V                                              | 51        | 0.64%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 51        | 0.64%   |
| Intel Wi-Fi 6 AX200                                                           | 47        | 0.59%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 47        | 0.59%   |
| Intel Ethernet Connection (2) I219-V                                          | 46        | 0.58%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 45        | 0.56%   |
| Intel Wireless 7265                                                           | 41        | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 38        | 0.48%   |
| Intel Ethernet Controller X550                                                | 37        | 0.46%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 37        | 0.46%   |
| Intel Wireless 3160                                                           | 36        | 0.45%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 36        | 0.45%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 35        | 0.44%   |
| Intel Wireless 7260                                                           | 32        | 0.4%    |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 32        | 0.4%    |
| Intel Ethernet Connection I217-V                                              | 32        | 0.4%    |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 31        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 444       | 47.23%  |
| Qualcomm Atheros                | 189       | 20.11%  |
| Realtek Semiconductor           | 105       | 11.17%  |
| Broadcom                        | 58        | 6.17%   |
| IMC Networks                    | 51        | 5.43%   |
| Ralink Technology               | 29        | 3.09%   |
| TP-Link                         | 15        | 1.6%    |
| Ralink                          | 11        | 1.17%   |
| MediaTek                        | 7         | 0.74%   |
| Edimax Technology               | 7         | 0.74%   |
| ASUSTek Computer                | 6         | 0.64%   |
| Qualcomm Atheros Communications | 4         | 0.43%   |
| Sierra Wireless                 | 2         | 0.21%   |
| NetGear                         | 2         | 0.21%   |
| ZyXEL Communications            | 1         | 0.11%   |
| Sitecom Europe                  | 1         | 0.11%   |
| Senao                           | 1         | 0.11%   |
| Mercucys                        | 1         | 0.11%   |
| Marvell Technology Group        | 1         | 0.11%   |
| Gemtek                          | 1         | 0.11%   |
| Dell                            | 1         | 0.11%   |
| D-Link                          | 1         | 0.11%   |
| Belkin Components               | 1         | 0.11%   |
| Accton Technology               | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                             | 78        | 8.23%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 51        | 5.38%   |
| Intel Wi-Fi 6 AX200                                             | 47        | 4.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 45        | 4.75%   |
| Intel Wireless 7265                                             | 41        | 4.32%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 38        | 4.01%   |
| Intel Wireless 3160                                             | 36        | 3.8%    |
| Intel Wireless 7260                                             | 32        | 3.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 28        | 2.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 23        | 2.43%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 21        | 2.22%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 19        | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 19        | 2%      |
| Broadcom BCM43228 802.11a/b/g/n                                 | 18        | 1.9%    |
| Intel Wireless 8265 / 8275                                      | 17        | 1.79%   |
| Intel Wireless 8260                                             | 17        | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 16        | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 16        | 1.69%   |
| Ralink RT5370 Wireless Adapter                                  | 14        | 1.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 12        | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 12        | 1.27%   |
| Intel Centrino Advanced-N 6235                                  | 12        | 1.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 11        | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 11        | 1.16%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 10        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 10        | 1.05%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 10        | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 10        | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 8         | 0.84%   |
| Intel Wireless-AC 9260                                          | 8         | 0.84%   |
| Broadcom BCM4331 802.11a/b/g/n                                  | 8         | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter             | 8         | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 7         | 0.74%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter              | 7         | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 6         | 0.63%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 6         | 0.63%   |
| Ralink RT5572 Wireless Adapter                                  | 6         | 0.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 6         | 0.63%   |
| Intel WiFi Link 5100                                            | 6         | 0.63%   |
| Intel Centrino Wireless-N 2230                                  | 6         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 3552      | 63.14%  |
| Realtek Semiconductor       | 1401      | 24.9%   |
| Broadcom                    | 403       | 7.16%   |
| AMD                         | 48        | 0.85%   |
| Qualcomm Atheros            | 43        | 0.76%   |
| Chelsio Communications      | 26        | 0.46%   |
| D-Link System               | 17        | 0.3%    |
| Marvell Technology Group    | 16        | 0.28%   |
| Solarflare Communications   | 13        | 0.23%   |
| QLogic                      | 12        | 0.21%   |
| American Megatrends         | 11        | 0.2%    |
| Emulex                      | 9         | 0.16%   |
| Aquantia                    | 9         | 0.16%   |
| IBM                         | 7         | 0.12%   |
| Novatel Wireless            | 6         | 0.11%   |
| ICS Advent                  | 6         | 0.11%   |
| Apple                       | 6         | 0.11%   |
| VIA Technologies            | 5         | 0.09%   |
| 3Com                        | 5         | 0.09%   |
| Samsung Electronics         | 3         | 0.05%   |
| Nvidia                      | 3         | 0.05%   |
| Insyde Software             | 3         | 0.05%   |
| Xiaomi                      | 2         | 0.04%   |
| SysKonnect                  | 2         | 0.04%   |
| Silicom                     | 2         | 0.04%   |
| Microsoft                   | 2         | 0.04%   |
| Digital Equipment           | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM  | 1         | 0.02%   |
| Tehuti Networks             | 1         | 0.02%   |
| T & A Mobile Phones         | 1         | 0.02%   |
| Standard Microsystems [SMC] | 1         | 0.02%   |
| Realtek                     | 1         | 0.02%   |
| QNAP System                 | 1         | 0.02%   |
| Netchip Technology          | 1         | 0.02%   |
| National Semiconductor      | 1         | 0.02%   |
| MYRICOM                     | 1         | 0.02%   |
| Google                      | 1         | 0.02%   |
| Davicom Semiconductor       | 1         | 0.02%   |
| ADMtek                      | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1290      | 18.72%  |
| Intel I211 Gigabit Network Connection                                         | 886       | 12.86%  |
| Intel I210 Gigabit Network Connection                                         | 593       | 8.61%   |
| Intel I350 Gigabit Network Connection                                         | 402       | 5.83%   |
| Intel 82574L Gigabit Network Connection                                       | 298       | 4.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 195       | 2.83%   |
| Intel Ethernet Controller I225-V                                              | 184       | 2.67%   |
| Intel 82583V Gigabit Network Connection                                       | 181       | 2.63%   |
| Intel 82576 Gigabit Network Connection                                        | 155       | 2.25%   |
| Intel 82580 Gigabit Network Connection                                        | 153       | 2.22%   |
| Intel Ethernet Connection I217-LM                                             | 142       | 2.06%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 136       | 1.97%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 111       | 1.61%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 109       | 1.58%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 103       | 1.49%   |
| Realtek RTL8125 2.5GbE Controller                                             | 94        | 1.36%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 81        | 1.18%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 76        | 1.1%    |
| Intel Ethernet Connection I354                                                | 70        | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                                         | 58        | 0.84%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 58        | 0.84%   |
| Intel Ethernet Connection X553 1GbE                                           | 56        | 0.81%   |
| Intel Ethernet Controller I226-V                                              | 51        | 0.74%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 47        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                                          | 46        | 0.67%   |
| Intel Ethernet Controller X550                                                | 37        | 0.54%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 37        | 0.54%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 36        | 0.52%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 35        | 0.51%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 32        | 0.46%   |
| Intel Ethernet Connection I217-V                                              | 32        | 0.46%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 31        | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 29        | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 28        | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                                         | 28        | 0.41%   |
| Intel Ethernet Connection (7) I219-V                                          | 26        | 0.38%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 25        | 0.36%   |
| Intel 82579V Gigabit Network Connection                                       | 24        | 0.35%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 24        | 0.35%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 23        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4509      | 81.21%  |
| WiFi     | 903       | 16.26%  |
| Unknown  | 104       | 1.87%   |
| Modem    | 36        | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4478      | 99.53%  |
| WiFi     | 20        | 0.44%   |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 4     | 1163      | 25.26%  |
| 3     | 896       | 19.46%  |
| 2     | 831       | 18.05%  |
| 6     | 645       | 14.01%  |
| 5     | 475       | 10.32%  |
| 8     | 184       | 4%      |
| 1     | 147       | 3.19%   |
| 7     | 105       | 2.28%   |
| 10    | 53        | 1.15%   |
| 9     | 50        | 1.09%   |
| 12    | 17        | 0.37%   |
| 14    | 10        | 0.22%   |
| 11    | 7         | 0.15%   |
| 13    | 6         | 0.13%   |
| 0     | 6         | 0.13%   |
| 16    | 4         | 0.09%   |
| 15    | 3         | 0.07%   |
| 20    | 2         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3777      | 80.14%  |
| Yes  | 936       | 19.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 331       | 67.69%  |
| IMC Networks                    | 51        | 10.43%  |
| Qualcomm Atheros Communications | 25        | 5.11%   |
| Broadcom                        | 17        | 3.48%   |
| Apple                           | 14        | 2.86%   |
| Realtek Semiconductor           | 12        | 2.45%   |
| Cambridge Silicon Radio         | 9         | 1.84%   |
| Foxconn / Hon Hai               | 7         | 1.43%   |
| Lite-On Technology              | 6         | 1.23%   |
| MediaTek                        | 5         | 1.02%   |
| ASUSTek Computer                | 5         | 1.02%   |
| Dell                            | 4         | 0.82%   |
| Qcom                            | 1         | 0.2%    |
| Hewlett-Packard                 | 1         | 0.2%    |
| Dynex                           | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                         | 146       | 29.86%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)             | 62        | 12.68%  |
| Intel AX200 Bluetooth                                      | 46        | 9.41%   |
| Intel Wireless-AC 3168 Bluetooth                           | 23        | 4.7%    |
| Intel Centrino Bluetooth Wireless Transceiver              | 22        | 4.5%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                | 20        | 4.09%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip       | 12        | 2.45%   |
| Apple Bluetooth Host Controller                            | 12        | 2.45%   |
| Intel AX201 Bluetooth                                      | 11        | 2.25%   |
| Intel AX210 Bluetooth                                      | 10        | 2.04%   |
| IMC Networks Realtek Bluetooth Adapter                     | 9         | 1.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)        | 9         | 1.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                      | 8         | 1.64%   |
| Realtek  Bluetooth 4.2 Adapter                             | 7         | 1.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                   | 7         | 1.43%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                     | 5         | 1.02%   |
| MediaTek Wireless_Device                                   | 5         | 1.02%   |
| IMC Networks Bluetooth Radio                               | 5         | 1.02%   |
| Intel Intel Wireless Bluetooth                             | 4         | 0.82%   |
| Qualcomm Atheros AR9462 Bluetooth                          | 3         | 0.61%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)            | 3         | 0.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                 | 3         | 0.61%   |
| Foxconn / Hon Hai Bluetooth USB Module                     | 3         | 0.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                 | 3         | 0.61%   |
| Broadcom BCM2045B (BDC-2.1)                                | 3         | 0.61%   |
| Realtek RTL8821A Bluetooth                                 | 2         | 0.41%   |
| Realtek RTL8723A Bluetooth                                 | 2         | 0.41%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                    | 2         | 0.41%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter | 2         | 0.41%   |
| IMC Networks Bluetooth                                     | 2         | 0.41%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                | 2         | 0.41%   |
| Broadcom HP Bluethunder                                    | 2         | 0.41%   |
| Broadcom Broadcom 20702 Bluetooth 4.0 Adapter              | 2         | 0.41%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE      | 2         | 0.41%   |
| ASUS Bluetooth Controller                                  | 2         | 0.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                    | 1         | 0.2%    |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE        | 1         | 0.2%    |
| Qualcomm Atheros AR3012 Bluetooth                          | 1         | 0.2%    |
| Qcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device         | 1         | 0.2%    |
| Lite-On Qualcomm Atheros QCA61x4A Bluetooth 4.1            | 1         | 0.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2446      | 80.59%  |
| AMD                                          | 470       | 15.49%  |
| Nvidia                                       | 93        | 3.06%   |
| C-Media Electronics                          | 8         | 0.26%   |
| Zoran Co. Personal Media Division (Nogatech) | 7         | 0.23%   |
| KTMicro                                      | 3         | 0.1%    |
| VIA Technologies                             | 2         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.03%   |
| Logitech                                     | 1         | 0.03%   |
| GN Netcom                                    | 1         | 0.03%   |
| Giga-Byte Technology                         | 1         | 0.03%   |
| Genesys Logic                                | 1         | 0.03%   |
| ESS Technology                               | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 297       | 8.07%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 266       | 7.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 241       | 6.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 229       | 6.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 182       | 4.94%   |
| AMD FCH Azalia Controller                                                                         | 170       | 4.62%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 166       | 4.51%   |
| AMD Kabini HDMI/DP Audio                                                                          | 146       | 3.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 139       | 3.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 136       | 3.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 127       | 3.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 111       | 3.02%   |
| Intel Jasper Lake HD Audio                                                                        | 104       | 2.83%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 93        | 2.53%   |
| Intel 8 Series HD Audio Controller                                                                | 91        | 2.47%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 78        | 2.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 77        | 2.09%   |
| Intel Broadwell-U Audio Controller                                                                | 77        | 2.09%   |
| Intel 200 Series PCH HD Audio                                                                     | 75        | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 73        | 1.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 64        | 1.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 49        | 1.33%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 49        | 1.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 46        | 1.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 46        | 1.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 41        | 1.11%   |
| AMD Wrestler HDMI Audio                                                                           | 32        | 0.87%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 30        | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 23        | 0.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 22        | 0.6%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 21        | 0.57%   |
| Unknown                                                                                           | 21        | 0.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 20        | 0.54%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 19        | 0.52%   |
| Intel Comet Lake PCH cAVS                                                                         | 19        | 0.52%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 18        | 0.49%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 17        | 0.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 16        | 0.43%   |
| Nvidia High Definition Audio Controller                                                           | 14        | 0.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 804       | 16.83%  |
| Unknown                    | 612       | 12.81%  |
| Kingston                   | 605       | 12.67%  |
| SK hynix                   | 589       | 12.33%  |
| Crucial                    | 465       | 9.74%   |
| Micron Technology          | 371       | 7.77%   |
| Corsair                    | 176       | 3.69%   |
| G.Skill                    | 152       | 3.18%   |
| Unknown                    | 146       | 3.06%   |
| Transcend                  | 108       | 2.26%   |
| Unknown (ABCD)             | 105       | 2.2%    |
| A-DATA Technology          | 64        | 1.34%   |
| Nanya Technology           | 55        | 1.15%   |
| Ramaxel Technology         | 46        | 0.96%   |
| Patriot                    | 39        | 0.82%   |
| Team                       | 34        | 0.71%   |
| Kimtigo                    | 34        | 0.71%   |
| Apacer                     | 32        | 0.67%   |
| Toshiba                    | 28        | 0.59%   |
| Hewlett-Packard            | 24        | 0.5%    |
| Elpida                     | 20        | 0.42%   |
| ATP                        | 19        | 0.4%    |
| Timetec                    | 14        | 0.29%   |
| PNY                        | 14        | 0.29%   |
| Teikon                     | 12        | 0.25%   |
| Innodisk                   | 11        | 0.23%   |
| Smart                      | 9         | 0.19%   |
| GOODRAM                    | 9         | 0.19%   |
| Tigo                       | 8         | 0.17%   |
| Silicon Power              | 8         | 0.17%   |
| Super Talent               | 7         | 0.15%   |
| GeIL                       | 7         | 0.15%   |
| Smart Modular              | 6         | 0.13%   |
| HPE                        | 6         | 0.13%   |
| Avant                      | 6         | 0.13%   |
| Goldenmars                 | 5         | 0.1%    |
| Unknown (0x0C26)           | 4         | 0.08%   |
| Shenzhen Jinge Information | 4         | 0.08%   |
| OCZ                        | 4         | 0.08%   |
| CSX                        | 4         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 146       | 2.89%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 109       | 2.15%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 104       | 2.06%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 45        | 0.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 38        | 0.75%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 36        | 0.71%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 29        | 0.57%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 26        | 0.51%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 25        | 0.49%   |
| Unknown RAM Module 8GB 1600MT/s                              | 24        | 0.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 24        | 0.47%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s          | 23        | 0.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 23        | 0.45%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s          | 22        | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                   | 21        | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 21        | 0.42%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 20        | 0.4%    |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 20        | 0.4%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 20        | 0.4%    |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s          | 20        | 0.4%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 20        | 0.4%    |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s               | 20        | 0.4%    |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s      | 20        | 0.4%    |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s        | 20        | 0.4%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3                   | 19        | 0.38%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s        | 18        | 0.36%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s        | 17        | 0.34%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 16        | 0.32%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 16        | 0.32%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s          | 16        | 0.32%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 16        | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                   | 15        | 0.3%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 15        | 0.3%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 15        | 0.3%    |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s        | 15        | 0.3%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 14        | 0.28%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 14        | 0.28%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 13        | 0.26%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 13        | 0.26%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 13        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR3            | 2359      | 54.87%  |
| DDR4            | 1476      | 34.33%  |
| DDR2            | 164       | 3.81%   |
| LPDDR4          | 127       | 2.95%   |
| Unknown         | 108       | 2.51%   |
| SDRAM           | 43        | 1%      |
| DDR             | 13        | 0.3%    |
| RAM             | 2         | 0.05%   |
| LPDDR3          | 2         | 0.05%   |
| DRAM            | 2         | 0.05%   |
| DDR5            | 2         | 0.05%   |
| Logical non-vol | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 2496      | 58.35%  |
| SODIMM       | 1684      | 39.36%  |
| Unknown      | 53        | 1.24%   |
| Row Of Chips | 18        | 0.42%   |
| FB-DIMM      | 16        | 0.37%   |
| Chip         | 7         | 0.16%   |
| RIMM         | 4         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1645      | 36.35%  |
| 4096   | 1633      | 36.09%  |
| 2048   | 558       | 12.33%  |
| 16384  | 521       | 11.51%  |
| 1024   | 96        | 2.12%   |
| 32768  | 56        | 1.24%   |
| 512    | 8         | 0.18%   |
| 65536  | 2         | 0.04%   |
| 32767  | 2         | 0.04%   |
| 129728 | 1         | 0.02%   |
| 6144   | 1         | 0.02%   |
| 4092   | 1         | 0.02%   |
| 1556   | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1537      | 33.97%  |
| 1333    | 723       | 15.98%  |
| 2400    | 626       | 13.83%  |
| 2667    | 403       | 8.91%   |
| 2133    | 278       | 6.14%   |
| 3200    | 216       | 4.77%   |
| 800     | 129       | 2.85%   |
| 667     | 129       | 2.85%   |
| 2666    | 76        | 1.68%   |
| 1066    | 70        | 1.55%   |
| Unknown | 62        | 1.37%   |
| 1867    | 58        | 1.28%   |
| 1067    | 41        | 0.91%   |
| 1866    | 36        | 0.8%    |
| 1334    | 34        | 0.75%   |
| 3000    | 22        | 0.49%   |
| 2933    | 19        | 0.42%   |
| 3600    | 15        | 0.33%   |
| 400     | 10        | 0.22%   |
| 1033    | 5         | 0.11%   |
| 533     | 5         | 0.11%   |
| 65535   | 4         | 0.09%   |
| 1400    | 4         | 0.09%   |
| 1332    | 4         | 0.09%   |
| 2600    | 2         | 0.04%   |
| 1200    | 2         | 0.04%   |
| 133     | 2         | 0.04%   |
| 59392   | 1         | 0.02%   |
| 6400    | 1         | 0.02%   |
| 5600    | 1         | 0.02%   |
| 5354    | 1         | 0.02%   |
| 5200    | 1         | 0.02%   |
| 4800    | 1         | 0.02%   |
| 4000    | 1         | 0.02%   |
| 3534    | 1         | 0.02%   |
| 2134    | 1         | 0.02%   |
| 1419    | 1         | 0.02%   |
| 933     | 1         | 0.02%   |
| 333     | 1         | 0.02%   |
| 200     | 1         | 0.02%   |

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

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 12        | 26.67%  |
| Acer                          | 7         | 15.56%  |
| Suyin                         | 4         | 8.89%   |
| Realtek Semiconductor         | 4         | 8.89%   |
| Microdia                      | 3         | 6.67%   |
| Apple                         | 3         | 6.67%   |
| Sunplus Innovation Technology | 2         | 4.44%   |
| Lite-On Technology            | 2         | 4.44%   |
| Z-Star Microelectronics       | 1         | 2.22%   |
| Syntek                        | 1         | 2.22%   |
| Sonix Technology              | 1         | 2.22%   |
| Silicon Motion                | 1         | 2.22%   |
| Logitech                      | 1         | 2.22%   |
| Lenovo                        | 1         | 2.22%   |
| IMC Networks                  | 1         | 2.22%   |
| ALi                           | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 4         | 8.89%   |
| Apple FaceTime HD Camera                 | 3         | 6.67%   |
| Acer Integrated Camera                   | 3         | 6.67%   |
| Realtek Integrated_Webcam_HD             | 2         | 4.44%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 2         | 4.44%   |
| Chicony HP HD Webcam [Fixed]             | 2         | 4.44%   |
| Acer Lenovo EasyCamera                   | 2         | 4.44%   |
| Z-Star WebCam SC-03FFL11739P             | 1         | 2.22%   |
| Syntek EasyCamera                        | 1         | 2.22%   |
| Suyin UVC 1.3MPixel WebCam               | 1         | 2.22%   |
| Suyin HP Webcam                          | 1         | 2.22%   |
| Suyin HD WebCam                          | 1         | 2.22%   |
| Suyin Acer/Lenovo Webcam [CN0316]        | 1         | 2.22%   |
| Sunplus Laptop_Integrated_Webcam_HD      | 1         | 2.22%   |
| Sunplus Laptop_Integrated_Webcam_1.3M    | 1         | 2.22%   |
| Sonix USB 2.0 Camera                     | 1         | 2.22%   |
| Silicon Motion WebCam SCB-0385N          | 1         | 2.22%   |
| Realtek Integrated Webcam HD             | 1         | 2.22%   |
| Realtek Acer 640 x 480 laptop camera     | 1         | 2.22%   |
| Microdia Laptop_Integrated_Webcam_HD     | 1         | 2.22%   |
| Microdia Laptop_Integrated_Webcam_0.3M   | 1         | 2.22%   |
| Microdia 1.3 MPixel Integrated Webcam    | 1         | 2.22%   |
| Logitech HD Pro Webcam C920              | 1         | 2.22%   |
| Lite-On Integrated Camera                | 1         | 2.22%   |
| Lite-On HP HD Webcam [Fixed]             | 1         | 2.22%   |
| Lenovo Integrated Camera                 | 1         | 2.22%   |
| IMC Networks USB2.0 UVC 1.3M WebCam      | 1         | 2.22%   |
| Chicony Integrated Camera [ThinkPad]     | 1         | 2.22%   |
| Chicony HD WebCam (Acer)                 | 1         | 2.22%   |
| Chicony HD Webcam                        | 1         | 2.22%   |
| Chicony Camera                           | 1         | 2.22%   |
| ALi Gateway Webcam                       | 1         | 2.22%   |
| Acer SunplusIT INC. Integrated Camera    | 1         | 2.22%   |
| Acer Lenovo Integrated Webcam            | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 10        | 62.5%   |
| Upek             | 2         | 12.5%   |
| Broadcom         | 2         | 12.5%   |
| AuthenTec        | 2         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 4         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 12.5%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 2         | 12.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 6.25%   |
| Validity Sensors VFS491                                                      | 1         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 6.25%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 6.25%   |

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
| 1     | 1930      | 41.6%   |
| 0     | 1815      | 39.12%  |
| 2     | 579       | 12.48%  |
| 3     | 226       | 4.87%   |
| 4     | 73        | 1.57%   |
| 5     | 16        | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 2530      | 73.1%   |
| Bluetooth                | 279       | 8.06%   |
| Net/wireless             | 277       | 8%      |
| Card reader              | 152       | 4.39%   |
| Net/ethernet             | 63        | 1.82%   |
| Firewire controller      | 54        | 1.56%   |
| Network                  | 52        | 1.5%    |
| Sound                    | 29        | 0.84%   |
| Fingerprint reader       | 16        | 0.46%   |
| Storage/raid             | 6         | 0.17%   |
| Storage                  | 3         | 0.09%   |

