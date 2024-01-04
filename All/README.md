BSD - Tested Hardware & Statistics
----------------------------------

A project to collect tested hardware configurations for BSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Desktop/README.md) and [notebooks](/Notebook/README.md).

OS-specific reports: [FreeBSD](/Dist/FreeBSD), [GhostBSD](/Dist/GhostBSD), [helloSystem](/Dist/helloSystem), [NetBSD](/Dist/NetBSD), [NomadBSD](/Dist/NomadBSD), [OpenBSD](/Dist/OpenBSD), [OPNsense](/Dist/OPNsense), [pfSense](/Dist/pfSense), [TrueNAS](/Dist/TrueNAS).

This report is for real hardware. Report for virtual hardware: [TestDays_VE](https://github.com/bsdhw/TestDays_VE)

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

Total: 20524

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | 8103 A01                    | Mini pc     | [d066ee0847](https://bsd-hardware.info/?probe=d066ee0847) | Jan 02, 2024 |
| ASUSTek       | P11C-M Series               | Desktop     | [37230a7cd9](https://bsd-hardware.info/?probe=37230a7cd9) | Jan 02, 2024 |
| AZW           | U59                         | Desktop     | [c8ffb92584](https://bsd-hardware.info/?probe=c8ffb92584) | Jan 02, 2024 |
| Lenovo        | ThinkPad T490s 20NX000MU... | Notebook    | [1271688c43](https://bsd-hardware.info/?probe=1271688c43) | Jan 02, 2024 |
| Intel         | JSL MRD                     | Desktop     | [6405a13f96](https://bsd-hardware.info/?probe=6405a13f96) | Jan 02, 2024 |
| AWOW          | AZ51                        | Mini pc     | [2dc5c759ac](https://bsd-hardware.info/?probe=2dc5c759ac) | Jan 02, 2024 |
| Protectli     | VP46xx                      | Desktop     | [f958569c30](https://bsd-hardware.info/?probe=f958569c30) | Jan 02, 2024 |
| Sophos        | XG                          | Firewall    | [6e9752e680](https://bsd-hardware.info/?probe=6e9752e680) | Jan 02, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [a29eec0aa5](https://bsd-hardware.info/?probe=a29eec0aa5) | Jan 02, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [2ab7b9d6b2](https://bsd-hardware.info/?probe=2ab7b9d6b2) | Jan 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [77d8cc2e7c](https://bsd-hardware.info/?probe=77d8cc2e7c) | Jan 02, 2024 |
| Intel         | NUC11TNBi3 M11908-404       | Mini pc     | [5dac39e062](https://bsd-hardware.info/?probe=5dac39e062) | Jan 02, 2024 |
| Gowin Solu... | GW-MB-U01                   | Desktop     | [673266d486](https://bsd-hardware.info/?probe=673266d486) | Jan 01, 2024 |
| Sophos        | XG                          | Firewall    | [a472e0b686](https://bsd-hardware.info/?probe=a472e0b686) | Jan 01, 2024 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [270a946916](https://bsd-hardware.info/?probe=270a946916) | Jan 01, 2024 |
| Fujitsu       | D3034-A1 S26361-D3034-A1... | Server      | [806449eded](https://bsd-hardware.info/?probe=806449eded) | Jan 01, 2024 |
| Alienware     | 07HV66 A00                  | Desktop     | [ea6a3f3020](https://bsd-hardware.info/?probe=ea6a3f3020) | Jan 01, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1c7bbcc0ca](https://bsd-hardware.info/?probe=1c7bbcc0ca) | Jan 01, 2024 |
| Protectli     | VP2420                      | Desktop     | [bc43bc2215](https://bsd-hardware.info/?probe=bc43bc2215) | Jan 01, 2024 |
| Protectli     | FW4B Ver                    | Desktop     | [3191952740](https://bsd-hardware.info/?probe=3191952740) | Jan 01, 2024 |
| MSI           | Z170A PC MATE               | Desktop     | [e05af13af9](https://bsd-hardware.info/?probe=e05af13af9) | Jan 01, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [7e2b858339](https://bsd-hardware.info/?probe=7e2b858339) | Dec 31, 2023 |
| Protectli     | VP2420                      | Desktop     | [4b1f47b18e](https://bsd-hardware.info/?probe=4b1f47b18e) | Dec 31, 2023 |
| Samsung       | R510/P510                   | Notebook    | [920e7e2d14](https://bsd-hardware.info/?probe=920e7e2d14) | Dec 31, 2023 |
| Supermicro    | X11SBA-LN4FA                | Server      | [dbf9225f63](https://bsd-hardware.info/?probe=dbf9225f63) | Dec 31, 2023 |
| PC Engines    | APU3                        | Desktop     | [d2074bd451](https://bsd-hardware.info/?probe=d2074bd451) | Dec 31, 2023 |
| MSI           | Z270-A PRO                  | Desktop     | [2f2f406aa3](https://bsd-hardware.info/?probe=2f2f406aa3) | Dec 31, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [84985aa669](https://bsd-hardware.info/?probe=84985aa669) | Dec 31, 2023 |
| MSI           | H81M-P33                    | Desktop     | [82e08820f2](https://bsd-hardware.info/?probe=82e08820f2) | Dec 31, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [da3b88ef85](https://bsd-hardware.info/?probe=da3b88ef85) | Dec 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [391f4c0e0b](https://bsd-hardware.info/?probe=391f4c0e0b) | Dec 31, 2023 |
| GEEK+         | Mini PC                     | Mini pc     | [9e550a39c1](https://bsd-hardware.info/?probe=9e550a39c1) | Dec 31, 2023 |
| Dell          | 01PXF9 A00                  | Mini pc     | [7c785122a9](https://bsd-hardware.info/?probe=7c785122a9) | Dec 31, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [bcbbfa0368](https://bsd-hardware.info/?probe=bcbbfa0368) | Dec 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [56ecba336a](https://bsd-hardware.info/?probe=56ecba336a) | Dec 31, 2023 |
| Casper        | NIRVANA DESKTOP             | Desktop     | [926ae04d23](https://bsd-hardware.info/?probe=926ae04d23) | Dec 31, 2023 |
| HP            | 8103 A01                    | Mini pc     | [3c3e8d1f67](https://bsd-hardware.info/?probe=3c3e8d1f67) | Dec 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [d4bedea996](https://bsd-hardware.info/?probe=d4bedea996) | Dec 30, 2023 |
| Intel         | H61M-DS2                    | Desktop     | [bd541b60c8](https://bsd-hardware.info/?probe=bd541b60c8) | Dec 30, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [1889675f37](https://bsd-hardware.info/?probe=1889675f37) | Dec 30, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d95f2f3534](https://bsd-hardware.info/?probe=d95f2f3534) | Dec 30, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [715a274a2e](https://bsd-hardware.info/?probe=715a274a2e) | Dec 30, 2023 |
| Dell          | Vostro V130                 | Notebook    | [44e78243c2](https://bsd-hardware.info/?probe=44e78243c2) | Dec 30, 2023 |
| Protectli     | FW4A Ver                    | Desktop     | [39c4ea3a24](https://bsd-hardware.info/?probe=39c4ea3a24) | Dec 30, 2023 |
| PC Engines    | APU2                        | Desktop     | [c0fcb231db](https://bsd-hardware.info/?probe=c0fcb231db) | Dec 30, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [56472e8f51](https://bsd-hardware.info/?probe=56472e8f51) | Dec 30, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [6f996518f6](https://bsd-hardware.info/?probe=6f996518f6) | Dec 30, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [0e31087126](https://bsd-hardware.info/?probe=0e31087126) | Dec 30, 2023 |
| Dell          | 0F3KHR A02                  | Desktop     | [572ad429ae](https://bsd-hardware.info/?probe=572ad429ae) | Dec 30, 2023 |
| HP            | 3397                        | Desktop     | [46b6923bcd](https://bsd-hardware.info/?probe=46b6923bcd) | Dec 30, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [c915c03729](https://bsd-hardware.info/?probe=c915c03729) | Dec 30, 2023 |
| Protectli     | FW2B Ver                    | Desktop     | [3dbf91e1d4](https://bsd-hardware.info/?probe=3dbf91e1d4) | Dec 30, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [e235575d34](https://bsd-hardware.info/?probe=e235575d34) | Dec 30, 2023 |
| Unknown       | QDNV01                      | Desktop     | [d2fed4bb5f](https://bsd-hardware.info/?probe=d2fed4bb5f) | Dec 30, 2023 |
| Dell          | 0KYJ8C A00                  | Desktop     | [34246adca9](https://bsd-hardware.info/?probe=34246adca9) | Dec 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [63472bd5e6](https://bsd-hardware.info/?probe=63472bd5e6) | Dec 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [19daaf5eee](https://bsd-hardware.info/?probe=19daaf5eee) | Dec 30, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [c1c8f32b44](https://bsd-hardware.info/?probe=c1c8f32b44) | Dec 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [ce3ae03b86](https://bsd-hardware.info/?probe=ce3ae03b86) | Dec 30, 2023 |
| Intel         | JSL MRD                     | Desktop     | [1c65a367b2](https://bsd-hardware.info/?probe=1c65a367b2) | Dec 30, 2023 |
| Gigabyte      | H110M-D2P-WG-CF             | Desktop     | [77e0d09bf1](https://bsd-hardware.info/?probe=77e0d09bf1) | Dec 29, 2023 |
| Intel         | BOX-J41L4A V3.01            | Desktop     | [dd8cccddff](https://bsd-hardware.info/?probe=dd8cccddff) | Dec 29, 2023 |
| HP            | 82B4                        | Desktop     | [de6046d060](https://bsd-hardware.info/?probe=de6046d060) | Dec 29, 2023 |
| Intel         | BOX-J41L4A V3.01            | Desktop     | [9294250e89](https://bsd-hardware.info/?probe=9294250e89) | Dec 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [cd6ce65004](https://bsd-hardware.info/?probe=cd6ce65004) | Dec 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [fe3a4e49ee](https://bsd-hardware.info/?probe=fe3a4e49ee) | Dec 29, 2023 |
| Dell          | Inspiron 3195               | Convertible | [fb2acd7e84](https://bsd-hardware.info/?probe=fb2acd7e84) | Dec 29, 2023 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [bf5cb7eb21](https://bsd-hardware.info/?probe=bf5cb7eb21) | Dec 29, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [1545839e21](https://bsd-hardware.info/?probe=1545839e21) | Dec 29, 2023 |
| AWOW          | AZ51                        | Mini pc     | [b177ac4213](https://bsd-hardware.info/?probe=b177ac4213) | Dec 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [5354734c83](https://bsd-hardware.info/?probe=5354734c83) | Dec 29, 2023 |
| Dell          | 04YP6J A00                  | Desktop     | [9ed1a43f79](https://bsd-hardware.info/?probe=9ed1a43f79) | Dec 29, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [49375afedd](https://bsd-hardware.info/?probe=49375afedd) | Dec 29, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [66f7dd1f06](https://bsd-hardware.info/?probe=66f7dd1f06) | Dec 29, 2023 |
| PC Engines    | apu4                        | Desktop     | [3901782984](https://bsd-hardware.info/?probe=3901782984) | Dec 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [ba78787dff](https://bsd-hardware.info/?probe=ba78787dff) | Dec 29, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [e54393775b](https://bsd-hardware.info/?probe=e54393775b) | Dec 29, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [fa4e90491b](https://bsd-hardware.info/?probe=fa4e90491b) | Dec 29, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [1c769a311c](https://bsd-hardware.info/?probe=1c769a311c) | Dec 29, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [bc5f165c4a](https://bsd-hardware.info/?probe=bc5f165c4a) | Dec 29, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [f9b91683f8](https://bsd-hardware.info/?probe=f9b91683f8) | Dec 28, 2023 |
| Dell          | 0GU083 A00                  | Desktop     | [caaa806343](https://bsd-hardware.info/?probe=caaa806343) | Dec 28, 2023 |
| Supermicro    | X8SIE                       | Desktop     | [a7e2e09ef4](https://bsd-hardware.info/?probe=a7e2e09ef4) | Dec 28, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [ec4b676c4b](https://bsd-hardware.info/?probe=ec4b676c4b) | Dec 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [eba2e80eee](https://bsd-hardware.info/?probe=eba2e80eee) | Dec 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [f34b5d84dd](https://bsd-hardware.info/?probe=f34b5d84dd) | Dec 28, 2023 |
| Unknown       | QSKL01                      | Desktop     | [ba39338284](https://bsd-hardware.info/?probe=ba39338284) | Dec 28, 2023 |
| AZW           | Green G1                    | Desktop     | [c5bd9604b5](https://bsd-hardware.info/?probe=c5bd9604b5) | Dec 28, 2023 |
| Deciso        | Netboard A20                | Notebook    | [c545672f6f](https://bsd-hardware.info/?probe=c545672f6f) | Dec 28, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [7387d0de6b](https://bsd-hardware.info/?probe=7387d0de6b) | Dec 28, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [c1f17be486](https://bsd-hardware.info/?probe=c1f17be486) | Dec 28, 2023 |
| Fujitsu       | D3090-A1 S26361-D3090-A1    | Server      | [1952b64d3d](https://bsd-hardware.info/?probe=1952b64d3d) | Dec 28, 2023 |
| AZW           | EQ                          | Desktop     | [fcbfcb31d5](https://bsd-hardware.info/?probe=fcbfcb31d5) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B460-G GAMING     | Desktop     | [6b9d713fe0](https://bsd-hardware.info/?probe=6b9d713fe0) | Dec 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [23269a4f84](https://bsd-hardware.info/?probe=23269a4f84) | Dec 28, 2023 |
| Protectli     | VP2420                      | Desktop     | [39b80f6d35](https://bsd-hardware.info/?probe=39b80f6d35) | Dec 28, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [19a5ef28f8](https://bsd-hardware.info/?probe=19a5ef28f8) | Dec 28, 2023 |
| HP            | 0B54h D                     | Desktop     | [0fc53a659f](https://bsd-hardware.info/?probe=0fc53a659f) | Dec 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [f93ba42c7a](https://bsd-hardware.info/?probe=f93ba42c7a) | Dec 28, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [55a9dc404b](https://bsd-hardware.info/?probe=55a9dc404b) | Dec 27, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [429f1e855f](https://bsd-hardware.info/?probe=429f1e855f) | Dec 27, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [00abf2f109](https://bsd-hardware.info/?probe=00abf2f109) | Dec 27, 2023 |
| Supermicro    | X10DRi-T                    | Desktop     | [0001356297](https://bsd-hardware.info/?probe=0001356297) | Dec 27, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [4ddf360812](https://bsd-hardware.info/?probe=4ddf360812) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [0a2c02f944](https://bsd-hardware.info/?probe=0a2c02f944) | Dec 27, 2023 |
| Rembrandt     | ARB928                      | Notebook    | [c9a9bfd4aa](https://bsd-hardware.info/?probe=c9a9bfd4aa) | Dec 27, 2023 |
| ZX            | H610ITXG                    | Desktop     | [8253eb826a](https://bsd-hardware.info/?probe=8253eb826a) | Dec 27, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [1f28c229cb](https://bsd-hardware.info/?probe=1f28c229cb) | Dec 27, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d4f5a9c35a](https://bsd-hardware.info/?probe=d4f5a9c35a) | Dec 27, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [f43cf3565a](https://bsd-hardware.info/?probe=f43cf3565a) | Dec 27, 2023 |
| HP            | 304Bh                       | Desktop     | [52ee1947b1](https://bsd-hardware.info/?probe=52ee1947b1) | Dec 27, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6f592981ce](https://bsd-hardware.info/?probe=6f592981ce) | Dec 27, 2023 |
| Protectli     | VP2420                      | Desktop     | [a7e60ab925](https://bsd-hardware.info/?probe=a7e60ab925) | Dec 27, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [c2f3692204](https://bsd-hardware.info/?probe=c2f3692204) | Dec 27, 2023 |
| HP            | 1998                        | Desktop     | [8bebbb8dab](https://bsd-hardware.info/?probe=8bebbb8dab) | Dec 27, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [412c714b49](https://bsd-hardware.info/?probe=412c714b49) | Dec 27, 2023 |
| MSI           | Aspen                       | Desktop     | [ac6dd2b153](https://bsd-hardware.info/?probe=ac6dd2b153) | Dec 27, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [8b71e16af3](https://bsd-hardware.info/?probe=8b71e16af3) | Dec 27, 2023 |
| Intel         | J1900                       | Desktop     | [2a647a5c54](https://bsd-hardware.info/?probe=2a647a5c54) | Dec 27, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [c910bb7b83](https://bsd-hardware.info/?probe=c910bb7b83) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [4b1250f831](https://bsd-hardware.info/?probe=4b1250f831) | Dec 26, 2023 |
| AZW           | Green G5                    | Desktop     | [a088cebb95](https://bsd-hardware.info/?probe=a088cebb95) | Dec 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [b054d33e68](https://bsd-hardware.info/?probe=b054d33e68) | Dec 26, 2023 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | Desktop     | [3f1abe2cd8](https://bsd-hardware.info/?probe=3f1abe2cd8) | Dec 26, 2023 |
| ASRock        | J4005B-ITX                  | Desktop     | [8ad375a02f](https://bsd-hardware.info/?probe=8ad375a02f) | Dec 26, 2023 |
| Sophos        | XG                          | Firewall    | [c30f177b0f](https://bsd-hardware.info/?probe=c30f177b0f) | Dec 26, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [533a831b97](https://bsd-hardware.info/?probe=533a831b97) | Dec 26, 2023 |
| Protectli     | FW4B                        | Desktop     | [cf4ead1922](https://bsd-hardware.info/?probe=cf4ead1922) | Dec 26, 2023 |
| HP            | 8062                        | Desktop     | [3f3a2202eb](https://bsd-hardware.info/?probe=3f3a2202eb) | Dec 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [48677111e5](https://bsd-hardware.info/?probe=48677111e5) | Dec 26, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [d08712b71d](https://bsd-hardware.info/?probe=d08712b71d) | Dec 26, 2023 |
| HP            | 1998                        | Desktop     | [2782adcac6](https://bsd-hardware.info/?probe=2782adcac6) | Dec 26, 2023 |
| ASUSTek       | B150M-A D3                  | Desktop     | [d416ce02f1](https://bsd-hardware.info/?probe=d416ce02f1) | Dec 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [563547a218](https://bsd-hardware.info/?probe=563547a218) | Dec 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [058859b9c4](https://bsd-hardware.info/?probe=058859b9c4) | Dec 26, 2023 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [fa5891041a](https://bsd-hardware.info/?probe=fa5891041a) | Dec 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [8f17cade1c](https://bsd-hardware.info/?probe=8f17cade1c) | Dec 25, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [47fdb04811](https://bsd-hardware.info/?probe=47fdb04811) | Dec 25, 2023 |
| Sophos        | UTM                         | Firewall    | [89d19cc2ab](https://bsd-hardware.info/?probe=89d19cc2ab) | Dec 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [f712f3c6c0](https://bsd-hardware.info/?probe=f712f3c6c0) | Dec 25, 2023 |
| Unknown       | YL-J3160L4                  | Desktop     | [50f8c02769](https://bsd-hardware.info/?probe=50f8c02769) | Dec 25, 2023 |
| Supermicro    | X11SDW-16C-TP13F+           | Desktop     | [49ed0c6dca](https://bsd-hardware.info/?probe=49ed0c6dca) | Dec 25, 2023 |
| Lenovo        | ThinkPad X131e 33672T9      | Notebook    | [93f964da45](https://bsd-hardware.info/?probe=93f964da45) | Dec 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [23ca4c0419](https://bsd-hardware.info/?probe=23ca4c0419) | Dec 25, 2023 |
| Lenovo        | ThinkCentre M72e 3629A15    | Desktop     | [90d6ad1083](https://bsd-hardware.info/?probe=90d6ad1083) | Dec 25, 2023 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [6b85ccc7ed](https://bsd-hardware.info/?probe=6b85ccc7ed) | Dec 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [72d02dbaa4](https://bsd-hardware.info/?probe=72d02dbaa4) | Dec 25, 2023 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [7ad0451a6f](https://bsd-hardware.info/?probe=7ad0451a6f) | Dec 25, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | Desktop     | [304af7e00e](https://bsd-hardware.info/?probe=304af7e00e) | Dec 25, 2023 |
| AMI           | Intel                       | Notebook    | [df557e3915](https://bsd-hardware.info/?probe=df557e3915) | Dec 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | Notebook    | [b6c3c05155](https://bsd-hardware.info/?probe=b6c3c05155) | Dec 25, 2023 |
| Lenovo        | ThinkPad X250 20CLS8Q601    | Notebook    | [2c52684baa](https://bsd-hardware.info/?probe=2c52684baa) | Dec 25, 2023 |
| Dell          | 081N4V A10                  | Server      | [62d49dec3c](https://bsd-hardware.info/?probe=62d49dec3c) | Dec 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [03f7101d55](https://bsd-hardware.info/?probe=03f7101d55) | Dec 25, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [f1180b6e76](https://bsd-hardware.info/?probe=f1180b6e76) | Dec 25, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e41699ae87](https://bsd-hardware.info/?probe=e41699ae87) | Dec 25, 2023 |
| Sophos        | XG                          | Firewall    | [f1a7e4eb38](https://bsd-hardware.info/?probe=f1a7e4eb38) | Dec 25, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | Desktop     | [491c854348](https://bsd-hardware.info/?probe=491c854348) | Dec 25, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [742764e130](https://bsd-hardware.info/?probe=742764e130) | Dec 25, 2023 |
| Unknown       | QGLK03                      | Desktop     | [4be2a41109](https://bsd-hardware.info/?probe=4be2a41109) | Dec 25, 2023 |
| Unknown       | QGLK03                      | Desktop     | [b187a024cb](https://bsd-hardware.info/?probe=b187a024cb) | Dec 25, 2023 |
| Unknown       | QSKL01                      | Desktop     | [f69898815d](https://bsd-hardware.info/?probe=f69898815d) | Dec 25, 2023 |
| Protectli     | VP2420                      | Desktop     | [5368ee9cc8](https://bsd-hardware.info/?probe=5368ee9cc8) | Dec 24, 2023 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | Desktop     | [504fb1678f](https://bsd-hardware.info/?probe=504fb1678f) | Dec 24, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [a740494857](https://bsd-hardware.info/?probe=a740494857) | Dec 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [278ab700ae](https://bsd-hardware.info/?probe=278ab700ae) | Dec 24, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [7e4cee9689](https://bsd-hardware.info/?probe=7e4cee9689) | Dec 24, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [19c9105326](https://bsd-hardware.info/?probe=19c9105326) | Dec 24, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [04675127c2](https://bsd-hardware.info/?probe=04675127c2) | Dec 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1ef7136151](https://bsd-hardware.info/?probe=1ef7136151) | Dec 24, 2023 |
| IGEL Techn... | H830C                       | Notebook    | [da070c0348](https://bsd-hardware.info/?probe=da070c0348) | Dec 24, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [80e8d502be](https://bsd-hardware.info/?probe=80e8d502be) | Dec 24, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [5844adb190](https://bsd-hardware.info/?probe=5844adb190) | Dec 24, 2023 |
| Acer          | Veriton X490G               | Desktop     | [3f4dbee6d1](https://bsd-hardware.info/?probe=3f4dbee6d1) | Dec 24, 2023 |
| Acer          | Veriton X490G               | Desktop     | [1865afdae1](https://bsd-hardware.info/?probe=1865afdae1) | Dec 24, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [0ec70893dd](https://bsd-hardware.info/?probe=0ec70893dd) | Dec 24, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [1656e8f6b0](https://bsd-hardware.info/?probe=1656e8f6b0) | Dec 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9876dcc6aa](https://bsd-hardware.info/?probe=9876dcc6aa) | Dec 24, 2023 |
| Protectli     | VP2420                      | Desktop     | [34e03b1271](https://bsd-hardware.info/?probe=34e03b1271) | Dec 24, 2023 |
| Unknown       | QGLK03                      | Desktop     | [a586279dd0](https://bsd-hardware.info/?probe=a586279dd0) | Dec 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9a23873dc4](https://bsd-hardware.info/?probe=9a23873dc4) | Dec 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [da2b7d434e](https://bsd-hardware.info/?probe=da2b7d434e) | Dec 24, 2023 |
| YANYU         | H17SL                       | Desktop     | [464357d8c1](https://bsd-hardware.info/?probe=464357d8c1) | Dec 24, 2023 |
| eMachines     | eM350                       | Notebook    | [00d1d0c359](https://bsd-hardware.info/?probe=00d1d0c359) | Dec 23, 2023 |
| Dell          | 01Y1CJ A00                  | Mini pc     | [69e3982549](https://bsd-hardware.info/?probe=69e3982549) | Dec 23, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [7ca1ae0c93](https://bsd-hardware.info/?probe=7ca1ae0c93) | Dec 23, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [13699f3359](https://bsd-hardware.info/?probe=13699f3359) | Dec 23, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [ee768bd5a0](https://bsd-hardware.info/?probe=ee768bd5a0) | Dec 23, 2023 |
| Dell          | 01G5C3 A02                  | Server      | [7940d24d8e](https://bsd-hardware.info/?probe=7940d24d8e) | Dec 23, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [e39c520eb6](https://bsd-hardware.info/?probe=e39c520eb6) | Dec 23, 2023 |
| PC Engines    | APU2                        | Desktop     | [79f4518fa1](https://bsd-hardware.info/?probe=79f4518fa1) | Dec 23, 2023 |
| Dell          | Precision 5510              | Notebook    | [4bad5ad995](https://bsd-hardware.info/?probe=4bad5ad995) | Dec 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [609d9be189](https://bsd-hardware.info/?probe=609d9be189) | Dec 23, 2023 |
| Dell          | Precision 7720              | Notebook    | [a30d05e373](https://bsd-hardware.info/?probe=a30d05e373) | Dec 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [4f79ea6f3a](https://bsd-hardware.info/?probe=4f79ea6f3a) | Dec 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [684d183b51](https://bsd-hardware.info/?probe=684d183b51) | Dec 23, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [06828fbfed](https://bsd-hardware.info/?probe=06828fbfed) | Dec 23, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | Notebook    | [32c06c5669](https://bsd-hardware.info/?probe=32c06c5669) | Dec 23, 2023 |
| Dell          | 03X6X0 A02                  | Server      | [1fc8559747](https://bsd-hardware.info/?probe=1fc8559747) | Dec 23, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [3c06ec4635](https://bsd-hardware.info/?probe=3c06ec4635) | Dec 23, 2023 |
| AZW           | EQ                          | Desktop     | [9818e5f996](https://bsd-hardware.info/?probe=9818e5f996) | Dec 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [97559370a8](https://bsd-hardware.info/?probe=97559370a8) | Dec 23, 2023 |
| Gigabyte      | MRZNVMS-00                  | Desktop     | [7c9af3e3cd](https://bsd-hardware.info/?probe=7c9af3e3cd) | Dec 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [1a68705919](https://bsd-hardware.info/?probe=1a68705919) | Dec 23, 2023 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [d8245df746](https://bsd-hardware.info/?probe=d8245df746) | Dec 23, 2023 |
| TULPAR        | A5 V20.3                    | Notebook    | [89b65e7036](https://bsd-hardware.info/?probe=89b65e7036) | Dec 23, 2023 |
| Lenovo        | ThinkCentre M72e 3629A15    | Desktop     | [8a92c95f65](https://bsd-hardware.info/?probe=8a92c95f65) | Dec 22, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [4b6a62bebe](https://bsd-hardware.info/?probe=4b6a62bebe) | Dec 22, 2023 |
| Orange Pi     | 5P                          | Soc         | [aa6c177cb0](https://bsd-hardware.info/?probe=aa6c177cb0) | Dec 22, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [c4e5366baa](https://bsd-hardware.info/?probe=c4e5366baa) | Dec 22, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [fbf8f52ea0](https://bsd-hardware.info/?probe=fbf8f52ea0) | Dec 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [620fc27594](https://bsd-hardware.info/?probe=620fc27594) | Dec 22, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [5ed362ce02](https://bsd-hardware.info/?probe=5ed362ce02) | Dec 22, 2023 |
| Pegatron      | 2ACF                        | Desktop     | [2556fa3be1](https://bsd-hardware.info/?probe=2556fa3be1) | Dec 22, 2023 |
| PC Engines    | apu4                        | Desktop     | [48a0e27e11](https://bsd-hardware.info/?probe=48a0e27e11) | Dec 22, 2023 |
| ZX            | H610ITXG                    | Desktop     | [11edcbeaff](https://bsd-hardware.info/?probe=11edcbeaff) | Dec 22, 2023 |
| Dell          | Latitude E7240              | Notebook    | [f2229124bf](https://bsd-hardware.info/?probe=f2229124bf) | Dec 22, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [7f8968ee0a](https://bsd-hardware.info/?probe=7f8968ee0a) | Dec 22, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [2463b12f4e](https://bsd-hardware.info/?probe=2463b12f4e) | Dec 22, 2023 |
| Lenovo        | ThinkPad A485 20MU000VUS    | Notebook    | [98663cbfef](https://bsd-hardware.info/?probe=98663cbfef) | Dec 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [85ec93f4cd](https://bsd-hardware.info/?probe=85ec93f4cd) | Dec 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cfe1ed1212](https://bsd-hardware.info/?probe=cfe1ed1212) | Dec 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [34f3eb8059](https://bsd-hardware.info/?probe=34f3eb8059) | Dec 22, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [2e35364732](https://bsd-hardware.info/?probe=2e35364732) | Dec 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [7b24999fbb](https://bsd-hardware.info/?probe=7b24999fbb) | Dec 22, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [dbcb26f795](https://bsd-hardware.info/?probe=dbcb26f795) | Dec 22, 2023 |
| ASUSTek       | PRIME H610I-PLUS D4         | Desktop     | [3a435d185e](https://bsd-hardware.info/?probe=3a435d185e) | Dec 22, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [9eaa02c47c](https://bsd-hardware.info/?probe=9eaa02c47c) | Dec 22, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [76495a4c85](https://bsd-hardware.info/?probe=76495a4c85) | Dec 22, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [06457349dc](https://bsd-hardware.info/?probe=06457349dc) | Dec 22, 2023 |
| Supermicro    | X11SSH-LN4F                 | Server      | [132a8d8b6f](https://bsd-hardware.info/?probe=132a8d8b6f) | Dec 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [84a9704b97](https://bsd-hardware.info/?probe=84a9704b97) | Dec 21, 2023 |
| Protectli     | VP2420                      | Desktop     | [04695d0802](https://bsd-hardware.info/?probe=04695d0802) | Dec 21, 2023 |
| Shuttle       | FS77U                       | Desktop     | [9c746c0d5c](https://bsd-hardware.info/?probe=9c746c0d5c) | Dec 21, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [b2597a7f2b](https://bsd-hardware.info/?probe=b2597a7f2b) | Dec 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [ec4c6d8fb5](https://bsd-hardware.info/?probe=ec4c6d8fb5) | Dec 21, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [9a0369cc72](https://bsd-hardware.info/?probe=9a0369cc72) | Dec 21, 2023 |
| Dell          | 012KND A00                  | Mini pc     | [9107aaa45d](https://bsd-hardware.info/?probe=9107aaa45d) | Dec 21, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [70fe8567d6](https://bsd-hardware.info/?probe=70fe8567d6) | Dec 21, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [4ccf9a2566](https://bsd-hardware.info/?probe=4ccf9a2566) | Dec 21, 2023 |
| Lenovo        | ThinkSystem ST50 V2 7D8J... | Desktop     | [a5eedba370](https://bsd-hardware.info/?probe=a5eedba370) | Dec 21, 2023 |
| Sophos        | UTM                         | Firewall    | [e1e002bdd4](https://bsd-hardware.info/?probe=e1e002bdd4) | Dec 21, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [8a2c7af96c](https://bsd-hardware.info/?probe=8a2c7af96c) | Dec 21, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [2ba0ee6609](https://bsd-hardware.info/?probe=2ba0ee6609) | Dec 21, 2023 |
| PC Engines    | apu4                        | Desktop     | [7fa270657e](https://bsd-hardware.info/?probe=7fa270657e) | Dec 21, 2023 |
| Intel         | DH61AG AAG23736-400         | Desktop     | [e6a38faa07](https://bsd-hardware.info/?probe=e6a38faa07) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [f9fd749985](https://bsd-hardware.info/?probe=f9fd749985) | Dec 21, 2023 |
| Protectli     | VP2420                      | Desktop     | [9a4aba32a7](https://bsd-hardware.info/?probe=9a4aba32a7) | Dec 21, 2023 |
| Dell          | 0NV0M7 A01                  | Desktop     | [835ca2056c](https://bsd-hardware.info/?probe=835ca2056c) | Dec 21, 2023 |
| Protectli     | FW4B                        | Desktop     | [d67b8b063a](https://bsd-hardware.info/?probe=d67b8b063a) | Dec 21, 2023 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [094d15625b](https://bsd-hardware.info/?probe=094d15625b) | Dec 21, 2023 |
| Intel         | NUC11ATBPE M49844-303       | Mini pc     | [1e083d16ac](https://bsd-hardware.info/?probe=1e083d16ac) | Dec 21, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [5c6e9bd18a](https://bsd-hardware.info/?probe=5c6e9bd18a) | Dec 20, 2023 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | Desktop     | [ec18d4f3a1](https://bsd-hardware.info/?probe=ec18d4f3a1) | Dec 20, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [11764c4c5e](https://bsd-hardware.info/?probe=11764c4c5e) | Dec 20, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [760c7214cc](https://bsd-hardware.info/?probe=760c7214cc) | Dec 20, 2023 |
| Clevo         | W240BU                      | Notebook    | [19bb603cab](https://bsd-hardware.info/?probe=19bb603cab) | Dec 20, 2023 |
| Intel         | J1900                       | Desktop     | [2322789485](https://bsd-hardware.info/?probe=2322789485) | Dec 20, 2023 |
| Apple         | PowerBook3,5                | Notebook    | [53313e58d8](https://bsd-hardware.info/?probe=53313e58d8) | Dec 20, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [6e070fbb90](https://bsd-hardware.info/?probe=6e070fbb90) | Dec 20, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [c728132d77](https://bsd-hardware.info/?probe=c728132d77) | Dec 20, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [2974d1c480](https://bsd-hardware.info/?probe=2974d1c480) | Dec 20, 2023 |
| Lenovo        | ThinkPad T490s 20NYS4HL1... | Notebook    | [97fb2e025e](https://bsd-hardware.info/?probe=97fb2e025e) | Dec 20, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [321e9d7328](https://bsd-hardware.info/?probe=321e9d7328) | Dec 20, 2023 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [54b2061c80](https://bsd-hardware.info/?probe=54b2061c80) | Dec 19, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [bd9dd3d647](https://bsd-hardware.info/?probe=bd9dd3d647) | Dec 19, 2023 |
| Dell          | 0VD5HY A00                  | Desktop     | [03b0e973ca](https://bsd-hardware.info/?probe=03b0e973ca) | Dec 19, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [c00a69de7c](https://bsd-hardware.info/?probe=c00a69de7c) | Dec 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [f11c353c61](https://bsd-hardware.info/?probe=f11c353c61) | Dec 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [5f6cc807a3](https://bsd-hardware.info/?probe=5f6cc807a3) | Dec 19, 2023 |
| PC Engines    | APU2                        | Desktop     | [f3061d599c](https://bsd-hardware.info/?probe=f3061d599c) | Dec 19, 2023 |
| HP            | 83F2                        | Desktop     | [858392467f](https://bsd-hardware.info/?probe=858392467f) | Dec 19, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [851f118bd5](https://bsd-hardware.info/?probe=851f118bd5) | Dec 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [02bf1d2cd4](https://bsd-hardware.info/?probe=02bf1d2cd4) | Dec 19, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [841767c8f8](https://bsd-hardware.info/?probe=841767c8f8) | Dec 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [5281bb9e20](https://bsd-hardware.info/?probe=5281bb9e20) | Dec 19, 2023 |
| PC Engines    | apu4                        | Desktop     | [97c6f1ef2a](https://bsd-hardware.info/?probe=97c6f1ef2a) | Dec 19, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [0716929be0](https://bsd-hardware.info/?probe=0716929be0) | Dec 19, 2023 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [bb91074237](https://bsd-hardware.info/?probe=bb91074237) | Dec 19, 2023 |
| HP            | 83F2                        | Desktop     | [8b1e24b86c](https://bsd-hardware.info/?probe=8b1e24b86c) | Dec 19, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7d5e8bcb8a](https://bsd-hardware.info/?probe=7d5e8bcb8a) | Dec 19, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [35283b08ff](https://bsd-hardware.info/?probe=35283b08ff) | Dec 19, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [abcaede8e1](https://bsd-hardware.info/?probe=abcaede8e1) | Dec 19, 2023 |
| ASUSTek       | P5B-VM                      | Desktop     | [00e7a346b2](https://bsd-hardware.info/?probe=00e7a346b2) | Dec 19, 2023 |
| HP            | 212B                        | Desktop     | [d110ce488b](https://bsd-hardware.info/?probe=d110ce488b) | Dec 18, 2023 |
| Lenovo        | ThinkPad X220 4291H77       | Notebook    | [2fe3ff7e06](https://bsd-hardware.info/?probe=2fe3ff7e06) | Dec 18, 2023 |
| ASRockRack    | C3558D4I-4L                 | Desktop     | [108b107783](https://bsd-hardware.info/?probe=108b107783) | Dec 18, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [6bc190970b](https://bsd-hardware.info/?probe=6bc190970b) | Dec 18, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [b99ed60ab6](https://bsd-hardware.info/?probe=b99ed60ab6) | Dec 18, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [825a0f57e3](https://bsd-hardware.info/?probe=825a0f57e3) | Dec 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [4114a11fe7](https://bsd-hardware.info/?probe=4114a11fe7) | Dec 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | Notebook    | [4bc98299dd](https://bsd-hardware.info/?probe=4bc98299dd) | Dec 18, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [ad0f62cef1](https://bsd-hardware.info/?probe=ad0f62cef1) | Dec 18, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YV... | Notebook    | [10fb96c00d](https://bsd-hardware.info/?probe=10fb96c00d) | Dec 18, 2023 |
| Dell          | 04JN2K A03                  | Server      | [d56fe5aeb2](https://bsd-hardware.info/?probe=d56fe5aeb2) | Dec 18, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [ba2cad0d55](https://bsd-hardware.info/?probe=ba2cad0d55) | Dec 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [c4a54e3710](https://bsd-hardware.info/?probe=c4a54e3710) | Dec 18, 2023 |
| Protectli     | FW4A Ver                    | Desktop     | [9660edcc5c](https://bsd-hardware.info/?probe=9660edcc5c) | Dec 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [107e747798](https://bsd-hardware.info/?probe=107e747798) | Dec 17, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [ea3bc70906](https://bsd-hardware.info/?probe=ea3bc70906) | Dec 17, 2023 |
| Intel         | JSL MRD                     | Desktop     | [29c4bae1f4](https://bsd-hardware.info/?probe=29c4bae1f4) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [f11703c364](https://bsd-hardware.info/?probe=f11703c364) | Dec 17, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [d0ebaa4479](https://bsd-hardware.info/?probe=d0ebaa4479) | Dec 17, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [8f6f4d38d3](https://bsd-hardware.info/?probe=8f6f4d38d3) | Dec 17, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [ae676079d7](https://bsd-hardware.info/?probe=ae676079d7) | Dec 17, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [5a4d01667e](https://bsd-hardware.info/?probe=5a4d01667e) | Dec 17, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ea79e98108](https://bsd-hardware.info/?probe=ea79e98108) | Dec 17, 2023 |
| Intel         | JSL MRD                     | Desktop     | [af718ee605](https://bsd-hardware.info/?probe=af718ee605) | Dec 17, 2023 |
| ECS           | H81H3-WM                    | Desktop     | [9df1f030f9](https://bsd-hardware.info/?probe=9df1f030f9) | Dec 17, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [878769cc62](https://bsd-hardware.info/?probe=878769cc62) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [88306fe484](https://bsd-hardware.info/?probe=88306fe484) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [6a3ef5165f](https://bsd-hardware.info/?probe=6a3ef5165f) | Dec 17, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [57a4adcc91](https://bsd-hardware.info/?probe=57a4adcc91) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [cefdf7d9ca](https://bsd-hardware.info/?probe=cefdf7d9ca) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [c99ee25103](https://bsd-hardware.info/?probe=c99ee25103) | Dec 17, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [1eb8cc9d76](https://bsd-hardware.info/?probe=1eb8cc9d76) | Dec 17, 2023 |
| Lenovo        | 314C SEK0T35577 IOT 4247... | Mini pc     | [5b09e2113c](https://bsd-hardware.info/?probe=5b09e2113c) | Dec 17, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [fe741ca47c](https://bsd-hardware.info/?probe=fe741ca47c) | Dec 17, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [11e5e87b70](https://bsd-hardware.info/?probe=11e5e87b70) | Dec 16, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [2c652aa0a1](https://bsd-hardware.info/?probe=2c652aa0a1) | Dec 16, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [b0194a8d4a](https://bsd-hardware.info/?probe=b0194a8d4a) | Dec 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [4b134e7787](https://bsd-hardware.info/?probe=4b134e7787) | Dec 16, 2023 |
| PC Engines    | APU3                        | Desktop     | [6c92d4965a](https://bsd-hardware.info/?probe=6c92d4965a) | Dec 16, 2023 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [17f70cfb67](https://bsd-hardware.info/?probe=17f70cfb67) | Dec 16, 2023 |
| CSL-Comput... | C15 v3                      | Notebook    | [dd93594896](https://bsd-hardware.info/?probe=dd93594896) | Dec 16, 2023 |
| Intel         | ChiefRiver D                | Desktop     | [ac362a0f29](https://bsd-hardware.info/?probe=ac362a0f29) | Dec 16, 2023 |
| Intel         | ChiefRiver D                | Desktop     | [bd8cacb673](https://bsd-hardware.info/?probe=bd8cacb673) | Dec 16, 2023 |
| Google        | Guado                       | Desktop     | [186f14c0a6](https://bsd-hardware.info/?probe=186f14c0a6) | Dec 16, 2023 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [a2aa82ed5d](https://bsd-hardware.info/?probe=a2aa82ed5d) | Dec 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [784c8ae515](https://bsd-hardware.info/?probe=784c8ae515) | Dec 16, 2023 |
| Protectli     | FW4B                        | Desktop     | [b862c8c507](https://bsd-hardware.info/?probe=b862c8c507) | Dec 16, 2023 |
| HP            | 212B                        | Desktop     | [1737c1241b](https://bsd-hardware.info/?probe=1737c1241b) | Dec 16, 2023 |
| Lenovo        | ThinkPad P1 20MD002MUS      | Notebook    | [c0dcfec41d](https://bsd-hardware.info/?probe=c0dcfec41d) | Dec 16, 2023 |
| SHANGZHAOY... | B85M-PRO V1.1               | Desktop     | [3b7ed136da](https://bsd-hardware.info/?probe=3b7ed136da) | Dec 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [df97b81bea](https://bsd-hardware.info/?probe=df97b81bea) | Dec 15, 2023 |
| ASRock        | IMB-181-L                   | Desktop     | [a81eb6eadf](https://bsd-hardware.info/?probe=a81eb6eadf) | Dec 15, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [aefb80936c](https://bsd-hardware.info/?probe=aefb80936c) | Dec 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7a5e6024cd](https://bsd-hardware.info/?probe=7a5e6024cd) | Dec 15, 2023 |
| AZW           | MINI S 10                   | Desktop     | [d8eee18baf](https://bsd-hardware.info/?probe=d8eee18baf) | Dec 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [be79d227b2](https://bsd-hardware.info/?probe=be79d227b2) | Dec 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [5adc44e122](https://bsd-hardware.info/?probe=5adc44e122) | Dec 15, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [f05a97db34](https://bsd-hardware.info/?probe=f05a97db34) | Dec 15, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [343d176e9c](https://bsd-hardware.info/?probe=343d176e9c) | Dec 15, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [7a32a123f6](https://bsd-hardware.info/?probe=7a32a123f6) | Dec 15, 2023 |
| Google        | Guado                       | Desktop     | [11b7e710c6](https://bsd-hardware.info/?probe=11b7e710c6) | Dec 15, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [4b7be4588e](https://bsd-hardware.info/?probe=4b7be4588e) | Dec 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [4adda9051f](https://bsd-hardware.info/?probe=4adda9051f) | Dec 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [93f650efc3](https://bsd-hardware.info/?probe=93f650efc3) | Dec 15, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [9773ffcc27](https://bsd-hardware.info/?probe=9773ffcc27) | Dec 15, 2023 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [41899c5e07](https://bsd-hardware.info/?probe=41899c5e07) | Dec 15, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [b6845a3e54](https://bsd-hardware.info/?probe=b6845a3e54) | Dec 15, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [c4b2a86518](https://bsd-hardware.info/?probe=c4b2a86518) | Dec 15, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [e1867819f3](https://bsd-hardware.info/?probe=e1867819f3) | Dec 15, 2023 |
| Toshiba       | Portable PC                 | Notebook    | [bee6ea8f18](https://bsd-hardware.info/?probe=bee6ea8f18) | Dec 15, 2023 |
| Gigabyte      | B75N                        | Desktop     | [dad5d14cf7](https://bsd-hardware.info/?probe=dad5d14cf7) | Dec 15, 2023 |
| Dell          | Latitude E6220              | Notebook    | [372070b2f2](https://bsd-hardware.info/?probe=372070b2f2) | Dec 15, 2023 |
| HP            | 82A2                        | Desktop     | [906fd206fe](https://bsd-hardware.info/?probe=906fd206fe) | Dec 15, 2023 |
| Google        | Kohaku                      | Notebook    | [0b945d8f38](https://bsd-hardware.info/?probe=0b945d8f38) | Dec 15, 2023 |
| HP            | 82A2                        | Desktop     | [0a816d2760](https://bsd-hardware.info/?probe=0a816d2760) | Dec 15, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [da6ac13ef2](https://bsd-hardware.info/?probe=da6ac13ef2) | Dec 15, 2023 |
| AZW           | EQ                          | Desktop     | [f1e4bf2224](https://bsd-hardware.info/?probe=f1e4bf2224) | Dec 15, 2023 |
| Acer          | V5-131                      | Notebook    | [76e88ee5df](https://bsd-hardware.info/?probe=76e88ee5df) | Dec 14, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [c197b26909](https://bsd-hardware.info/?probe=c197b26909) | Dec 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [a9f96c677c](https://bsd-hardware.info/?probe=a9f96c677c) | Dec 14, 2023 |
| ASRock        | J4005B-ITX                  | Desktop     | [2ffc965b2e](https://bsd-hardware.info/?probe=2ffc965b2e) | Dec 14, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [306f9c1b03](https://bsd-hardware.info/?probe=306f9c1b03) | Dec 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [0bc43bd220](https://bsd-hardware.info/?probe=0bc43bd220) | Dec 14, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [d9d33d12d7](https://bsd-hardware.info/?probe=d9d33d12d7) | Dec 14, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [9654df78b8](https://bsd-hardware.info/?probe=9654df78b8) | Dec 14, 2023 |
| Dell          | Latitude 3420               | Notebook    | [3767d653b9](https://bsd-hardware.info/?probe=3767d653b9) | Dec 14, 2023 |
| Dell          | 0PC5F7 A00                  | Desktop     | [e47e643ced](https://bsd-hardware.info/?probe=e47e643ced) | Dec 14, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [e15a019715](https://bsd-hardware.info/?probe=e15a019715) | Dec 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [88d2ae1175](https://bsd-hardware.info/?probe=88d2ae1175) | Dec 14, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [60451d4e43](https://bsd-hardware.info/?probe=60451d4e43) | Dec 14, 2023 |
| Dell          | Latitude E6540              | Notebook    | [77a9b10ab9](https://bsd-hardware.info/?probe=77a9b10ab9) | Dec 13, 2023 |
| AZW           | EQ                          | Desktop     | [d83e11a7dc](https://bsd-hardware.info/?probe=d83e11a7dc) | Dec 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [c22fff97b8](https://bsd-hardware.info/?probe=c22fff97b8) | Dec 13, 2023 |
| Intel         | SKYBAY                      | Desktop     | [6ad2ae72f1](https://bsd-hardware.info/?probe=6ad2ae72f1) | Dec 13, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [159a5556ab](https://bsd-hardware.info/?probe=159a5556ab) | Dec 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [bc50d301fa](https://bsd-hardware.info/?probe=bc50d301fa) | Dec 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [dced442907](https://bsd-hardware.info/?probe=dced442907) | Dec 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [b2407b8a31](https://bsd-hardware.info/?probe=b2407b8a31) | Dec 13, 2023 |
| Intel         | Luna Pier CRB Revision D    | Desktop     | [44215d3b22](https://bsd-hardware.info/?probe=44215d3b22) | Dec 13, 2023 |
| Intel         | ChiefRiver D                | Desktop     | [dafa13827e](https://bsd-hardware.info/?probe=dafa13827e) | Dec 13, 2023 |
| Intel         | Luna Pier CRB Revision D    | Desktop     | [e47e6d56e8](https://bsd-hardware.info/?probe=e47e6d56e8) | Dec 13, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [12e42ebd6d](https://bsd-hardware.info/?probe=12e42ebd6d) | Dec 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [c96a52dd9c](https://bsd-hardware.info/?probe=c96a52dd9c) | Dec 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [8eb8c9eff3](https://bsd-hardware.info/?probe=8eb8c9eff3) | Dec 13, 2023 |
| Google        | Lindar rev3                 | Notebook    | [2e748fc42c](https://bsd-hardware.info/?probe=2e748fc42c) | Dec 13, 2023 |
| Intel         | QHSW02                      | Desktop     | [da6b7c7115](https://bsd-hardware.info/?probe=da6b7c7115) | Dec 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [a7fcca51be](https://bsd-hardware.info/?probe=a7fcca51be) | Dec 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [67f5c9c912](https://bsd-hardware.info/?probe=67f5c9c912) | Dec 13, 2023 |
| ASRock        | H170M-ITX/DL                | Desktop     | [79039f6105](https://bsd-hardware.info/?probe=79039f6105) | Dec 13, 2023 |
| ASUSTek       | K52JT                       | Notebook    | [1dc348adc0](https://bsd-hardware.info/?probe=1dc348adc0) | Dec 13, 2023 |
| ASUSTek       | BM6875_BM6675_BP6375        | Desktop     | [3d0160889b](https://bsd-hardware.info/?probe=3d0160889b) | Dec 13, 2023 |
| Supermicro    | X7SBi                       | Desktop     | [a0124f00ba](https://bsd-hardware.info/?probe=a0124f00ba) | Dec 13, 2023 |
| Sophos        | SG                          | Firewall    | [13c711aabf](https://bsd-hardware.info/?probe=13c711aabf) | Dec 13, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b600237a69](https://bsd-hardware.info/?probe=b600237a69) | Dec 12, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b5f9416c13](https://bsd-hardware.info/?probe=b5f9416c13) | Dec 12, 2023 |
| Dell          | 0J8G6F A03                  | Desktop     | [e6e7f333a3](https://bsd-hardware.info/?probe=e6e7f333a3) | Dec 12, 2023 |
| Intel         | DH67BL AAG10189-207         | Desktop     | [e6210120bd](https://bsd-hardware.info/?probe=e6210120bd) | Dec 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d81a233601](https://bsd-hardware.info/?probe=d81a233601) | Dec 12, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [09f5b25e72](https://bsd-hardware.info/?probe=09f5b25e72) | Dec 12, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [20dd6f1621](https://bsd-hardware.info/?probe=20dd6f1621) | Dec 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [357a808604](https://bsd-hardware.info/?probe=357a808604) | Dec 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [9a842bf3c8](https://bsd-hardware.info/?probe=9a842bf3c8) | Dec 12, 2023 |
| MSI           | B150 GAMING M3              | Desktop     | [b5dc4da596](https://bsd-hardware.info/?probe=b5dc4da596) | Dec 12, 2023 |
| Biostar       | N61PB-M2S                   | Desktop     | [69501bdb78](https://bsd-hardware.info/?probe=69501bdb78) | Dec 12, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [c26ebe6c80](https://bsd-hardware.info/?probe=c26ebe6c80) | Dec 12, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [b453da5223](https://bsd-hardware.info/?probe=b453da5223) | Dec 12, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [c05c574f37](https://bsd-hardware.info/?probe=c05c574f37) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [8a0a469ad0](https://bsd-hardware.info/?probe=8a0a469ad0) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [123088175c](https://bsd-hardware.info/?probe=123088175c) | Dec 11, 2023 |
| Dell          | 0N051F A04                  | Server      | [38535e6878](https://bsd-hardware.info/?probe=38535e6878) | Dec 11, 2023 |
| Dell          | 0XDN97 A09                  | Server      | [129a73f16f](https://bsd-hardware.info/?probe=129a73f16f) | Dec 11, 2023 |
| EVGA          | X570 DARK.0                 | Desktop     | [1c84a8169b](https://bsd-hardware.info/?probe=1c84a8169b) | Dec 11, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [6e876a349f](https://bsd-hardware.info/?probe=6e876a349f) | Dec 11, 2023 |
| Dell          | 084XW4 A05                  | Server      | [951a41f88c](https://bsd-hardware.info/?probe=951a41f88c) | Dec 11, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [2febbeffc2](https://bsd-hardware.info/?probe=2febbeffc2) | Dec 11, 2023 |
| Dell          | 084XW4 A06                  | Server      | [961b6ac6f7](https://bsd-hardware.info/?probe=961b6ac6f7) | Dec 11, 2023 |
| Lenovo        | 3111 NOK                    | Mini pc     | [533dbaf23a](https://bsd-hardware.info/?probe=533dbaf23a) | Dec 11, 2023 |
| SHANGZHAOY... | B85M-PRO V1.1               | Desktop     | [5cf5db5a05](https://bsd-hardware.info/?probe=5cf5db5a05) | Dec 11, 2023 |
| Dell          | 08CYF7 A05                  | Server      | [2768b91142](https://bsd-hardware.info/?probe=2768b91142) | Dec 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [37499be816](https://bsd-hardware.info/?probe=37499be816) | Dec 11, 2023 |
| HP            | 8103 A01                    | Mini pc     | [e2f44ab91e](https://bsd-hardware.info/?probe=e2f44ab91e) | Dec 11, 2023 |
| Lenovo        | ThinkServer RS140           | Desktop     | [a380879f2f](https://bsd-hardware.info/?probe=a380879f2f) | Dec 11, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [becfed036a](https://bsd-hardware.info/?probe=becfed036a) | Dec 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9a3a20d295](https://bsd-hardware.info/?probe=9a3a20d295) | Dec 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [68f73bf8ba](https://bsd-hardware.info/?probe=68f73bf8ba) | Dec 11, 2023 |
| Dell          | Latitude E6510              | Notebook    | [86c4864c0a](https://bsd-hardware.info/?probe=86c4864c0a) | Dec 11, 2023 |
| Dell          | Latitude E6510              | Notebook    | [dc2d54a168](https://bsd-hardware.info/?probe=dc2d54a168) | Dec 11, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [9368c19a35](https://bsd-hardware.info/?probe=9368c19a35) | Dec 11, 2023 |
| Pegatron      | 2AF0                        | Desktop     | [61aea25165](https://bsd-hardware.info/?probe=61aea25165) | Dec 10, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [b806cc2a41](https://bsd-hardware.info/?probe=b806cc2a41) | Dec 10, 2023 |
| AZW           | EQ                          | Desktop     | [0280c1cdb9](https://bsd-hardware.info/?probe=0280c1cdb9) | Dec 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [ec8c50c128](https://bsd-hardware.info/?probe=ec8c50c128) | Dec 10, 2023 |
| AZW           | EQ                          | Desktop     | [48537a5985](https://bsd-hardware.info/?probe=48537a5985) | Dec 10, 2023 |
| Supermicro    | X10SBAA                     | Server      | [f68b2d784b](https://bsd-hardware.info/?probe=f68b2d784b) | Dec 10, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [881ad2eacf](https://bsd-hardware.info/?probe=881ad2eacf) | Dec 10, 2023 |
| Protectli     | VP2420                      | Desktop     | [74c1ede426](https://bsd-hardware.info/?probe=74c1ede426) | Dec 10, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [b6a4782cbf](https://bsd-hardware.info/?probe=b6a4782cbf) | Dec 10, 2023 |
| Dell          | 0YNVJG A02                  | Desktop     | [2d8992cd50](https://bsd-hardware.info/?probe=2d8992cd50) | Dec 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [fc1097e9b0](https://bsd-hardware.info/?probe=fc1097e9b0) | Dec 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [3e478d7459](https://bsd-hardware.info/?probe=3e478d7459) | Dec 10, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [06e5f53429](https://bsd-hardware.info/?probe=06e5f53429) | Dec 10, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [8dd13bf91f](https://bsd-hardware.info/?probe=8dd13bf91f) | Dec 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [4b8c881de0](https://bsd-hardware.info/?probe=4b8c881de0) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [47480f848d](https://bsd-hardware.info/?probe=47480f848d) | Dec 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [2b1599aacd](https://bsd-hardware.info/?probe=2b1599aacd) | Dec 10, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [89f0463ec6](https://bsd-hardware.info/?probe=89f0463ec6) | Dec 10, 2023 |
| AAEON         | FWS-2362 V1.0               | Desktop     | [a58d1df175](https://bsd-hardware.info/?probe=a58d1df175) | Dec 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [edfa10c0dd](https://bsd-hardware.info/?probe=edfa10c0dd) | Dec 10, 2023 |
| Google        | Parrot                      | Notebook    | [c10a95cbcc](https://bsd-hardware.info/?probe=c10a95cbcc) | Dec 10, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [20572de8e3](https://bsd-hardware.info/?probe=20572de8e3) | Dec 10, 2023 |
| ASRock        | B660M Phantom Gaming 4      | Desktop     | [e71ffa9a86](https://bsd-hardware.info/?probe=e71ffa9a86) | Dec 10, 2023 |
| Google        | Parrot                      | Notebook    | [3a69ea2682](https://bsd-hardware.info/?probe=3a69ea2682) | Dec 10, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a03446d994](https://bsd-hardware.info/?probe=a03446d994) | Dec 10, 2023 |
| HP            | 82A2                        | Desktop     | [688675d8ea](https://bsd-hardware.info/?probe=688675d8ea) | Dec 10, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [b7e23a4ed4](https://bsd-hardware.info/?probe=b7e23a4ed4) | Dec 10, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [3b6c1c2fbb](https://bsd-hardware.info/?probe=3b6c1c2fbb) | Dec 09, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [78399ba39e](https://bsd-hardware.info/?probe=78399ba39e) | Dec 09, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [05acf05b44](https://bsd-hardware.info/?probe=05acf05b44) | Dec 09, 2023 |
| Gigabyte      | B650 AORUS ELITE AX V2      | Desktop     | [7a6cdb3f06](https://bsd-hardware.info/?probe=7a6cdb3f06) | Dec 09, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [d62ad0d622](https://bsd-hardware.info/?probe=d62ad0d622) | Dec 09, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [55094840ea](https://bsd-hardware.info/?probe=55094840ea) | Dec 09, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [0fe56565dc](https://bsd-hardware.info/?probe=0fe56565dc) | Dec 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [5597d71956](https://bsd-hardware.info/?probe=5597d71956) | Dec 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [76f58e8986](https://bsd-hardware.info/?probe=76f58e8986) | Dec 09, 2023 |
| Unknown       | YL-J3160L4                  | Desktop     | [cf07751804](https://bsd-hardware.info/?probe=cf07751804) | Dec 09, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [25f4e4ce18](https://bsd-hardware.info/?probe=25f4e4ce18) | Dec 09, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [0674ed24ed](https://bsd-hardware.info/?probe=0674ed24ed) | Dec 09, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [39e0078d08](https://bsd-hardware.info/?probe=39e0078d08) | Dec 09, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [6b4d8c076f](https://bsd-hardware.info/?probe=6b4d8c076f) | Dec 09, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [5b31c551ae](https://bsd-hardware.info/?probe=5b31c551ae) | Dec 09, 2023 |
| HP            | 8076                        | Desktop     | [f6fe5f5051](https://bsd-hardware.info/?probe=f6fe5f5051) | Dec 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [31619d30b3](https://bsd-hardware.info/?probe=31619d30b3) | Dec 09, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [20dbd4481a](https://bsd-hardware.info/?probe=20dbd4481a) | Dec 09, 2023 |
| PC Engines    | APU2                        | Desktop     | [8f318ea168](https://bsd-hardware.info/?probe=8f318ea168) | Dec 09, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [1372cdf30f](https://bsd-hardware.info/?probe=1372cdf30f) | Dec 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [8422bc152b](https://bsd-hardware.info/?probe=8422bc152b) | Dec 08, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [a0591ac105](https://bsd-hardware.info/?probe=a0591ac105) | Dec 08, 2023 |
| ASRock        | Z370 Gaming K6              | Desktop     | [2074ab8412](https://bsd-hardware.info/?probe=2074ab8412) | Dec 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [426e43d7f2](https://bsd-hardware.info/?probe=426e43d7f2) | Dec 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [050e7d8c01](https://bsd-hardware.info/?probe=050e7d8c01) | Dec 08, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [90476f8605](https://bsd-hardware.info/?probe=90476f8605) | Dec 08, 2023 |
| PC Engines    | APU2                        | Desktop     | [ca43be99fc](https://bsd-hardware.info/?probe=ca43be99fc) | Dec 08, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [eb2eef3d17](https://bsd-hardware.info/?probe=eb2eef3d17) | Dec 08, 2023 |
| PC Engines    | apu4                        | Desktop     | [cdbac53ff6](https://bsd-hardware.info/?probe=cdbac53ff6) | Dec 08, 2023 |
| HP            | 3397                        | Desktop     | [9013e5a39a](https://bsd-hardware.info/?probe=9013e5a39a) | Dec 08, 2023 |
| Dell          | 081N4V A08                  | Server      | [3aba7cf14e](https://bsd-hardware.info/?probe=3aba7cf14e) | Dec 08, 2023 |
| Lenovo        | 3106 NOK                    | Desktop     | [0ef598481e](https://bsd-hardware.info/?probe=0ef598481e) | Dec 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [79486fa5ff](https://bsd-hardware.info/?probe=79486fa5ff) | Dec 08, 2023 |
| Biostar       | N61PB-M2S                   | Desktop     | [8b4dfe4511](https://bsd-hardware.info/?probe=8b4dfe4511) | Dec 08, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [cf3304bda2](https://bsd-hardware.info/?probe=cf3304bda2) | Dec 08, 2023 |
| Dell          | Latitude 7414               | Notebook    | [2d57c22982](https://bsd-hardware.info/?probe=2d57c22982) | Dec 08, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [55c513d023](https://bsd-hardware.info/?probe=55c513d023) | Dec 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [be6c7879b4](https://bsd-hardware.info/?probe=be6c7879b4) | Dec 07, 2023 |
| Protectli     | VP2420                      | Desktop     | [84a056721c](https://bsd-hardware.info/?probe=84a056721c) | Dec 07, 2023 |
| HP            | 806A                        | Desktop     | [4339b3acd2](https://bsd-hardware.info/?probe=4339b3acd2) | Dec 07, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [c119d3003e](https://bsd-hardware.info/?probe=c119d3003e) | Dec 07, 2023 |
| Dell          | Precision 7560              | Notebook    | [13f7324bd9](https://bsd-hardware.info/?probe=13f7324bd9) | Dec 07, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [b193b5141c](https://bsd-hardware.info/?probe=b193b5141c) | Dec 07, 2023 |
| Dell          | Precision 7560              | Notebook    | [5d3e6e3bd4](https://bsd-hardware.info/?probe=5d3e6e3bd4) | Dec 07, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [7fd4743b86](https://bsd-hardware.info/?probe=7fd4743b86) | Dec 07, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [6c5bcd325e](https://bsd-hardware.info/?probe=6c5bcd325e) | Dec 07, 2023 |
| Protectli     | VP46xx                      | Desktop     | [5051678913](https://bsd-hardware.info/?probe=5051678913) | Dec 07, 2023 |
| AWOW          | AZ51                        | Mini pc     | [f92f2f58c2](https://bsd-hardware.info/?probe=f92f2f58c2) | Dec 07, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [2b600594af](https://bsd-hardware.info/?probe=2b600594af) | Dec 07, 2023 |
| PC Engines    | APU2                        | Desktop     | [92c3ba510a](https://bsd-hardware.info/?probe=92c3ba510a) | Dec 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [efab62c197](https://bsd-hardware.info/?probe=efab62c197) | Dec 07, 2023 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [b5bbc08efe](https://bsd-hardware.info/?probe=b5bbc08efe) | Dec 07, 2023 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [d3898c1e39](https://bsd-hardware.info/?probe=d3898c1e39) | Dec 07, 2023 |
| Lenovo        | ThinkPad P70 20ESS1L600     | Notebook    | [2e3870f2ee](https://bsd-hardware.info/?probe=2e3870f2ee) | Dec 07, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [406d7a0572](https://bsd-hardware.info/?probe=406d7a0572) | Dec 07, 2023 |
| ADI Engine... | RCC-VE                      | Desktop     | [b362c84d66](https://bsd-hardware.info/?probe=b362c84d66) | Dec 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [23b689f778](https://bsd-hardware.info/?probe=23b689f778) | Dec 07, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [c906f764b0](https://bsd-hardware.info/?probe=c906f764b0) | Dec 07, 2023 |
| HP            | 213D A01                    | Desktop     | [a7ded310e3](https://bsd-hardware.info/?probe=a7ded310e3) | Dec 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [fed92c23db](https://bsd-hardware.info/?probe=fed92c23db) | Dec 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [a11b04691d](https://bsd-hardware.info/?probe=a11b04691d) | Dec 07, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [68cdde130c](https://bsd-hardware.info/?probe=68cdde130c) | Dec 06, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [7476cc6440](https://bsd-hardware.info/?probe=7476cc6440) | Dec 06, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [3784a39a41](https://bsd-hardware.info/?probe=3784a39a41) | Dec 06, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [52605948b7](https://bsd-hardware.info/?probe=52605948b7) | Dec 06, 2023 |
| PC Engines    | APU3                        | Desktop     | [06a4e1c23b](https://bsd-hardware.info/?probe=06a4e1c23b) | Dec 06, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [84c15c0d02](https://bsd-hardware.info/?probe=84c15c0d02) | Dec 06, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [41e61ade9a](https://bsd-hardware.info/?probe=41e61ade9a) | Dec 06, 2023 |
| HP            | 18E7                        | Desktop     | [02b090c3aa](https://bsd-hardware.info/?probe=02b090c3aa) | Dec 06, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [e61ae323ad](https://bsd-hardware.info/?probe=e61ae323ad) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [7a1ab6fd47](https://bsd-hardware.info/?probe=7a1ab6fd47) | Dec 06, 2023 |
| Sony          | VJS122C11L                  | Notebook    | [7d100c8e2c](https://bsd-hardware.info/?probe=7d100c8e2c) | Dec 06, 2023 |
| Dell          | 0CN7X8 A01                  | Server      | [82ff66fb79](https://bsd-hardware.info/?probe=82ff66fb79) | Dec 06, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [4a74f06217](https://bsd-hardware.info/?probe=4a74f06217) | Dec 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [ac7f59dc32](https://bsd-hardware.info/?probe=ac7f59dc32) | Dec 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [92ae7371ee](https://bsd-hardware.info/?probe=92ae7371ee) | Dec 06, 2023 |
| Fusion5       | FMP4 v2                     | Desktop     | [786d461a61](https://bsd-hardware.info/?probe=786d461a61) | Dec 06, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [17fd054f21](https://bsd-hardware.info/?probe=17fd054f21) | Dec 06, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [1034c9883a](https://bsd-hardware.info/?probe=1034c9883a) | Dec 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [52d2381f88](https://bsd-hardware.info/?probe=52d2381f88) | Dec 06, 2023 |
| PC Engines    | apu4                        | Desktop     | [dae8568bec](https://bsd-hardware.info/?probe=dae8568bec) | Dec 06, 2023 |
| PC Engines    | apu4                        | Desktop     | [04dd506405](https://bsd-hardware.info/?probe=04dd506405) | Dec 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [ef425e8732](https://bsd-hardware.info/?probe=ef425e8732) | Dec 05, 2023 |
| Protectli     | FW4C                        | Desktop     | [d14bbfd96c](https://bsd-hardware.info/?probe=d14bbfd96c) | Dec 05, 2023 |
| Lenovo        | ThinkPad W520 4270CTO       | Notebook    | [e63bc464f2](https://bsd-hardware.info/?probe=e63bc464f2) | Dec 05, 2023 |
| PC Engines    | APU2                        | Desktop     | [6bbcef15d3](https://bsd-hardware.info/?probe=6bbcef15d3) | Dec 05, 2023 |
| Dell          | 0411GW A02                  | Desktop     | [f2bc8b79b0](https://bsd-hardware.info/?probe=f2bc8b79b0) | Dec 05, 2023 |
| MECHREVO      | F7BSC V1.0                  | Mini pc     | [d1104aa676](https://bsd-hardware.info/?probe=d1104aa676) | Dec 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [98f7e31255](https://bsd-hardware.info/?probe=98f7e31255) | Dec 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [6097033e25](https://bsd-hardware.info/?probe=6097033e25) | Dec 05, 2023 |
| ECS           | MCP61M-M3                   | Desktop     | [6d6c04c278](https://bsd-hardware.info/?probe=6d6c04c278) | Dec 05, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9d54a02c53](https://bsd-hardware.info/?probe=9d54a02c53) | Dec 05, 2023 |
| Yanling       | YL-KBRL2 Series Ver:1.02    | Desktop     | [3bd3f01055](https://bsd-hardware.info/?probe=3bd3f01055) | Dec 05, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d9c6d21d10](https://bsd-hardware.info/?probe=d9c6d21d10) | Dec 05, 2023 |
| HP            | 8103 A01                    | Mini pc     | [f558be71a3](https://bsd-hardware.info/?probe=f558be71a3) | Dec 05, 2023 |
| HP            | 8103 A01                    | Mini pc     | [a71bdf2036](https://bsd-hardware.info/?probe=a71bdf2036) | Dec 05, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [c97833a27e](https://bsd-hardware.info/?probe=c97833a27e) | Dec 05, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [cc4538374c](https://bsd-hardware.info/?probe=cc4538374c) | Dec 05, 2023 |
| HP            | 805D                        | Desktop     | [57a0021595](https://bsd-hardware.info/?probe=57a0021595) | Dec 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [2301bb487f](https://bsd-hardware.info/?probe=2301bb487f) | Dec 05, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [a6175a2d93](https://bsd-hardware.info/?probe=a6175a2d93) | Dec 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8c023b9c33](https://bsd-hardware.info/?probe=8c023b9c33) | Dec 05, 2023 |
| Acer          | AOD260                      | Notebook    | [f8d6bb3095](https://bsd-hardware.info/?probe=f8d6bb3095) | Dec 05, 2023 |
| ASRock        | 990FX Extreme3              | Desktop     | [6ac792ecf6](https://bsd-hardware.info/?probe=6ac792ecf6) | Dec 05, 2023 |
| Dell          | Latitude E6330              | Notebook    | [7e0a01e9ad](https://bsd-hardware.info/?probe=7e0a01e9ad) | Dec 05, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [d6c18203b4](https://bsd-hardware.info/?probe=d6c18203b4) | Dec 04, 2023 |
| Wortmann      | TERRA_MOBILE_1541           | Notebook    | [63f1a71855](https://bsd-hardware.info/?probe=63f1a71855) | Dec 04, 2023 |
| Lenovo        | ThinkPad T430s 23532QG      | Notebook    | [b456c01e0f](https://bsd-hardware.info/?probe=b456c01e0f) | Dec 04, 2023 |
| Lenovo        | XXXX FFFFFFFFFF             | Desktop     | [780619812e](https://bsd-hardware.info/?probe=780619812e) | Dec 04, 2023 |
| Lenovo        | XXXX FFFFFFFFFF             | Desktop     | [7ddfbf4af2](https://bsd-hardware.info/?probe=7ddfbf4af2) | Dec 04, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [2f9c1e6d93](https://bsd-hardware.info/?probe=2f9c1e6d93) | Dec 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [ca548efdec](https://bsd-hardware.info/?probe=ca548efdec) | Dec 04, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [267d300e4a](https://bsd-hardware.info/?probe=267d300e4a) | Dec 04, 2023 |
| HP            | 8103 A01                    | Mini pc     | [0da20332e6](https://bsd-hardware.info/?probe=0da20332e6) | Dec 04, 2023 |
| Dell          | 01G5C3 A02                  | Server      | [c5e25db7f9](https://bsd-hardware.info/?probe=c5e25db7f9) | Dec 04, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [cb6b022d45](https://bsd-hardware.info/?probe=cb6b022d45) | Dec 04, 2023 |
| Supermicro    | X10SRH-CFA                  | Server      | [867424b026](https://bsd-hardware.info/?probe=867424b026) | Dec 04, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [494f638f4e](https://bsd-hardware.info/?probe=494f638f4e) | Dec 04, 2023 |
| ASUSTek       | X555LB                      | Notebook    | [0df52370a2](https://bsd-hardware.info/?probe=0df52370a2) | Dec 04, 2023 |
| Protectli     | FW6                         | Desktop     | [91d91ebf31](https://bsd-hardware.info/?probe=91d91ebf31) | Dec 04, 2023 |
| MiTAC         | UltraPoint                  | Desktop     | [346d03e78c](https://bsd-hardware.info/?probe=346d03e78c) | Dec 04, 2023 |
| PC Engines    | APU2                        | Desktop     | [46fa133d51](https://bsd-hardware.info/?probe=46fa133d51) | Dec 04, 2023 |
| Protectli     | FW4B                        | Desktop     | [a92d9762ce](https://bsd-hardware.info/?probe=a92d9762ce) | Dec 04, 2023 |
| PC Engines    | APU2                        | Desktop     | [dbd4df3e5e](https://bsd-hardware.info/?probe=dbd4df3e5e) | Dec 03, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [85ef5e07cd](https://bsd-hardware.info/?probe=85ef5e07cd) | Dec 03, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [177ffa702e](https://bsd-hardware.info/?probe=177ffa702e) | Dec 03, 2023 |
| HP            | 8715                        | Mini pc     | [262c6ee87c](https://bsd-hardware.info/?probe=262c6ee87c) | Dec 03, 2023 |
| HP            | Pavilion g7                 | Notebook    | [4c1bc19902](https://bsd-hardware.info/?probe=4c1bc19902) | Dec 03, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [2fefe41bcd](https://bsd-hardware.info/?probe=2fefe41bcd) | Dec 03, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [d04fd54963](https://bsd-hardware.info/?probe=d04fd54963) | Dec 03, 2023 |
| ASRock        | H310M-HDV/M.2               | Desktop     | [56ef117b12](https://bsd-hardware.info/?probe=56ef117b12) | Dec 03, 2023 |
| Intel         | RUT40R                      | Desktop     | [01b815dd9b](https://bsd-hardware.info/?probe=01b815dd9b) | Dec 03, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [ea8b5e1c14](https://bsd-hardware.info/?probe=ea8b5e1c14) | Dec 03, 2023 |
| HPE           | ML10Gen9                    | Server      | [c99bd5d7e4](https://bsd-hardware.info/?probe=c99bd5d7e4) | Dec 03, 2023 |
| Acidanther... | MacBookPro16,3              | Notebook    | [322ea11f6c](https://bsd-hardware.info/?probe=322ea11f6c) | Dec 03, 2023 |
| Lenovo        | ThinkCentre M70e 0828W17    | Desktop     | [02c7f33254](https://bsd-hardware.info/?probe=02c7f33254) | Dec 03, 2023 |
| Protectli     | FW4B                        | Desktop     | [dab9b84618](https://bsd-hardware.info/?probe=dab9b84618) | Dec 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [3dfc964b40](https://bsd-hardware.info/?probe=3dfc964b40) | Dec 03, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [a13be946a5](https://bsd-hardware.info/?probe=a13be946a5) | Dec 03, 2023 |
| Protectli     | FW2B Ver                    | Desktop     | [9ae293de1b](https://bsd-hardware.info/?probe=9ae293de1b) | Dec 03, 2023 |
| Sophos        | XG                          | Firewall    | [a851304161](https://bsd-hardware.info/?probe=a851304161) | Dec 03, 2023 |
| HP            | 1825                        | Desktop     | [3edf79b1ba](https://bsd-hardware.info/?probe=3edf79b1ba) | Dec 03, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [4f5b576aff](https://bsd-hardware.info/?probe=4f5b576aff) | Dec 03, 2023 |
| Protectli     | VP2420                      | Desktop     | [31b70f1d0d](https://bsd-hardware.info/?probe=31b70f1d0d) | Dec 03, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [18364861b5](https://bsd-hardware.info/?probe=18364861b5) | Dec 03, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [34db2bdd7d](https://bsd-hardware.info/?probe=34db2bdd7d) | Dec 03, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [f23df632e4](https://bsd-hardware.info/?probe=f23df632e4) | Dec 03, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [8a6ce136cc](https://bsd-hardware.info/?probe=8a6ce136cc) | Dec 03, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [150fd26797](https://bsd-hardware.info/?probe=150fd26797) | Dec 02, 2023 |
| AZW           | MINI S 10                   | Desktop     | [caf105bd1b](https://bsd-hardware.info/?probe=caf105bd1b) | Dec 02, 2023 |
| Intel         | D33217GKE G76540-207        | Desktop     | [761e1e0eae](https://bsd-hardware.info/?probe=761e1e0eae) | Dec 02, 2023 |
| HP            | 83EE                        | Desktop     | [bfb65878fa](https://bsd-hardware.info/?probe=bfb65878fa) | Dec 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [d837d27d35](https://bsd-hardware.info/?probe=d837d27d35) | Dec 02, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [8ffbff07d4](https://bsd-hardware.info/?probe=8ffbff07d4) | Dec 02, 2023 |
| Intel         | Geminilake                  | Desktop     | [59d13c77e8](https://bsd-hardware.info/?probe=59d13c77e8) | Dec 02, 2023 |
| Lenovo        | ThinkPad X280 20KES5M300    | Notebook    | [28d67ab74a](https://bsd-hardware.info/?probe=28d67ab74a) | Dec 02, 2023 |
| HP            | 8265                        | Desktop     | [ec9e6fdd6e](https://bsd-hardware.info/?probe=ec9e6fdd6e) | Dec 02, 2023 |
| ASUSTek       | X555LB                      | Notebook    | [e96bb84b37](https://bsd-hardware.info/?probe=e96bb84b37) | Dec 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [84fd9622e4](https://bsd-hardware.info/?probe=84fd9622e4) | Dec 02, 2023 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [760a22c4b8](https://bsd-hardware.info/?probe=760a22c4b8) | Dec 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a9b3beae66](https://bsd-hardware.info/?probe=a9b3beae66) | Dec 02, 2023 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [972ad3cb48](https://bsd-hardware.info/?probe=972ad3cb48) | Dec 02, 2023 |
| Dell          | 0GCY4M A01                  | Desktop     | [a5d23a5491](https://bsd-hardware.info/?probe=a5d23a5491) | Dec 02, 2023 |
| Star Labs     | LabTop                      | Notebook    | [e8dcf01d78](https://bsd-hardware.info/?probe=e8dcf01d78) | Dec 02, 2023 |
| Protectli     | FW4C                        | Desktop     | [c3b8887f26](https://bsd-hardware.info/?probe=c3b8887f26) | Dec 02, 2023 |
| Lenovo        | 3129 SDK0J40679 WIN 3273... | Desktop     | [da81c9605d](https://bsd-hardware.info/?probe=da81c9605d) | Dec 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [baf3e413d0](https://bsd-hardware.info/?probe=baf3e413d0) | Dec 01, 2023 |
| AZW           | EQ                          | Desktop     | [1f66e98633](https://bsd-hardware.info/?probe=1f66e98633) | Dec 01, 2023 |
| ASUSTek       | PRIME B650M-K               | Desktop     | [bbb53c5b97](https://bsd-hardware.info/?probe=bbb53c5b97) | Dec 01, 2023 |
| Intel         | H81U                        | Notebook    | [b74cca91df](https://bsd-hardware.info/?probe=b74cca91df) | Dec 01, 2023 |
| Intel         | QHSW02                      | Desktop     | [00af22bad5](https://bsd-hardware.info/?probe=00af22bad5) | Dec 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [ef2a5b9804](https://bsd-hardware.info/?probe=ef2a5b9804) | Dec 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [d5da0ab59d](https://bsd-hardware.info/?probe=d5da0ab59d) | Dec 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [5efe3ae6f9](https://bsd-hardware.info/?probe=5efe3ae6f9) | Dec 01, 2023 |
| ASRock        | H110M-HDS                   | Desktop     | [519a82f253](https://bsd-hardware.info/?probe=519a82f253) | Dec 01, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [0457bab107](https://bsd-hardware.info/?probe=0457bab107) | Dec 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [353b3874d5](https://bsd-hardware.info/?probe=353b3874d5) | Dec 01, 2023 |
| Protectli     | VP2420                      | Desktop     | [410b06a673](https://bsd-hardware.info/?probe=410b06a673) | Dec 01, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [ee42ff764f](https://bsd-hardware.info/?probe=ee42ff764f) | Dec 01, 2023 |
| Protectli     | VP2420                      | Desktop     | [4d59cef5e8](https://bsd-hardware.info/?probe=4d59cef5e8) | Nov 30, 2023 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [b394563830](https://bsd-hardware.info/?probe=b394563830) | Nov 30, 2023 |
| Dell          | 0GCPWH A00                  | Mini pc     | [27867fc6fb](https://bsd-hardware.info/?probe=27867fc6fb) | Nov 30, 2023 |
| BESSTAR Te... | GB7B                        | Mini pc     | [ceccfb11da](https://bsd-hardware.info/?probe=ceccfb11da) | Nov 30, 2023 |
| Intel         | JSL MRD                     | Desktop     | [0ec285953e](https://bsd-hardware.info/?probe=0ec285953e) | Nov 30, 2023 |
| Intel         | Geminilake                  | Desktop     | [0b0a4f8d68](https://bsd-hardware.info/?probe=0b0a4f8d68) | Nov 30, 2023 |
| Dell          | 081N4V A10                  | Server      | [46338756b8](https://bsd-hardware.info/?probe=46338756b8) | Nov 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [7d3416a30f](https://bsd-hardware.info/?probe=7d3416a30f) | Nov 30, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [f1cb9a41ba](https://bsd-hardware.info/?probe=f1cb9a41ba) | Nov 30, 2023 |
| Dell          | 0XN8Y6 A12                  | Server      | [3c8b7cfb27](https://bsd-hardware.info/?probe=3c8b7cfb27) | Nov 30, 2023 |
| AZW           | EQ                          | Desktop     | [a2f18cb86e](https://bsd-hardware.info/?probe=a2f18cb86e) | Nov 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [e5be2bebf5](https://bsd-hardware.info/?probe=e5be2bebf5) | Nov 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [9579521c83](https://bsd-hardware.info/?probe=9579521c83) | Nov 30, 2023 |
| Intel         | JSL MRD                     | Desktop     | [f8beb1caa9](https://bsd-hardware.info/?probe=f8beb1caa9) | Nov 30, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [ec3037a710](https://bsd-hardware.info/?probe=ec3037a710) | Nov 30, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [78fef35503](https://bsd-hardware.info/?probe=78fef35503) | Nov 30, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [e1a3d3ff53](https://bsd-hardware.info/?probe=e1a3d3ff53) | Nov 30, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [1af8f23214](https://bsd-hardware.info/?probe=1af8f23214) | Nov 30, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [6ceeb87719](https://bsd-hardware.info/?probe=6ceeb87719) | Nov 30, 2023 |
| Silver Pea... | Unknown                     | Firewall    | [405efa1824](https://bsd-hardware.info/?probe=405efa1824) | Nov 30, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [e31a43fc53](https://bsd-hardware.info/?probe=e31a43fc53) | Nov 30, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [d8b2ccabda](https://bsd-hardware.info/?probe=d8b2ccabda) | Nov 30, 2023 |
| BESSTAR Te... | GB7B                        | Mini pc     | [2d16e2f338](https://bsd-hardware.info/?probe=2d16e2f338) | Nov 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [906bc578c7](https://bsd-hardware.info/?probe=906bc578c7) | Nov 29, 2023 |
| AZW           | EQ                          | Desktop     | [e4b294ddda](https://bsd-hardware.info/?probe=e4b294ddda) | Nov 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [933b042721](https://bsd-hardware.info/?probe=933b042721) | Nov 29, 2023 |
| Yanling       | YL-ALU6L                    | Desktop     | [21135d9aa5](https://bsd-hardware.info/?probe=21135d9aa5) | Nov 29, 2023 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [e98e7bcab5](https://bsd-hardware.info/?probe=e98e7bcab5) | Nov 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [decaed145b](https://bsd-hardware.info/?probe=decaed145b) | Nov 29, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [ae4c6d7097](https://bsd-hardware.info/?probe=ae4c6d7097) | Nov 29, 2023 |
| AZW           | EQ                          | Desktop     | [b74a6439c5](https://bsd-hardware.info/?probe=b74a6439c5) | Nov 29, 2023 |
| AZW           | EQ                          | Desktop     | [f250b760ac](https://bsd-hardware.info/?probe=f250b760ac) | Nov 29, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [4017ce5221](https://bsd-hardware.info/?probe=4017ce5221) | Nov 29, 2023 |
| MUCAI         | H61 V1.6A                   | Desktop     | [8dfd16da29](https://bsd-hardware.info/?probe=8dfd16da29) | Nov 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [f3a2321558](https://bsd-hardware.info/?probe=f3a2321558) | Nov 29, 2023 |
| HP            | ProLiant ML350 G5           | Desktop     | [606d45973a](https://bsd-hardware.info/?probe=606d45973a) | Nov 29, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [ec250e722a](https://bsd-hardware.info/?probe=ec250e722a) | Nov 29, 2023 |
| Intel         | DH67CL AAG10212-206         | Desktop     | [818a6b3f2c](https://bsd-hardware.info/?probe=818a6b3f2c) | Nov 29, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [895be1e0cd](https://bsd-hardware.info/?probe=895be1e0cd) | Nov 28, 2023 |
| Unknown       | QDNV01                      | Desktop     | [63cbf7642b](https://bsd-hardware.info/?probe=63cbf7642b) | Nov 28, 2023 |
| Deciso        | Netboard A8                 | Desktop     | [53d89587d0](https://bsd-hardware.info/?probe=53d89587d0) | Nov 28, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [61bf87efe4](https://bsd-hardware.info/?probe=61bf87efe4) | Nov 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [ac008cef96](https://bsd-hardware.info/?probe=ac008cef96) | Nov 28, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [a2a08d6eec](https://bsd-hardware.info/?probe=a2a08d6eec) | Nov 28, 2023 |
| CNCTION-IA... | Unknown                     | Desktop     | [1b4871792b](https://bsd-hardware.info/?probe=1b4871792b) | Nov 28, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [d45a39836c](https://bsd-hardware.info/?probe=d45a39836c) | Nov 28, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [8d7c03be2f](https://bsd-hardware.info/?probe=8d7c03be2f) | Nov 28, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [35b8808218](https://bsd-hardware.info/?probe=35b8808218) | Nov 28, 2023 |
| Dell          | Precision 5510              | Notebook    | [3a7b2ae214](https://bsd-hardware.info/?probe=3a7b2ae214) | Nov 28, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [806a29d40a](https://bsd-hardware.info/?probe=806a29d40a) | Nov 28, 2023 |
| Dell          | 0DVNTK A00                  | Mini pc     | [3f81508cc6](https://bsd-hardware.info/?probe=3f81508cc6) | Nov 28, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [eec65ee6ce](https://bsd-hardware.info/?probe=eec65ee6ce) | Nov 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [97fc765ff5](https://bsd-hardware.info/?probe=97fc765ff5) | Nov 28, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [30e336f42f](https://bsd-hardware.info/?probe=30e336f42f) | Nov 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [2a34bc9613](https://bsd-hardware.info/?probe=2a34bc9613) | Nov 28, 2023 |
| AZW           | SER                         | Desktop     | [48a259ae28](https://bsd-hardware.info/?probe=48a259ae28) | Nov 28, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [be0344dcf2](https://bsd-hardware.info/?probe=be0344dcf2) | Nov 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [ddb77f8341](https://bsd-hardware.info/?probe=ddb77f8341) | Nov 28, 2023 |
| Cisco         | C170 A0                     | Desktop     | [cde1b3b0a4](https://bsd-hardware.info/?probe=cde1b3b0a4) | Nov 27, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [1096dc8160](https://bsd-hardware.info/?probe=1096dc8160) | Nov 27, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [1bfc57a019](https://bsd-hardware.info/?probe=1bfc57a019) | Nov 27, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [b32ded6bb9](https://bsd-hardware.info/?probe=b32ded6bb9) | Nov 27, 2023 |
| Supermicro    | X9SCL-II/X9SCM-II           | Desktop     | [34833316ac](https://bsd-hardware.info/?probe=34833316ac) | Nov 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [5631aa6b68](https://bsd-hardware.info/?probe=5631aa6b68) | Nov 27, 2023 |
| HP            | 3031h                       | Desktop     | [6c69231a9f](https://bsd-hardware.info/?probe=6c69231a9f) | Nov 27, 2023 |
| Yanling       | YL-EL4L-0A Ver              | Desktop     | [d0c780fa8b](https://bsd-hardware.info/?probe=d0c780fa8b) | Nov 27, 2023 |
| NU591R        | 1.0                         | Desktop     | [2552269778](https://bsd-hardware.info/?probe=2552269778) | Nov 27, 2023 |
| Foxconn       | 17A0                        | Desktop     | [5cc85cbcb9](https://bsd-hardware.info/?probe=5cc85cbcb9) | Nov 27, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [4a195d6b46](https://bsd-hardware.info/?probe=4a195d6b46) | Nov 27, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [b132017cc8](https://bsd-hardware.info/?probe=b132017cc8) | Nov 27, 2023 |
| GoWin Solu... | R86S-N                      | Desktop     | [1d40615c24](https://bsd-hardware.info/?probe=1d40615c24) | Nov 27, 2023 |
| WTM           | BKHD-N5105-5LAN B0          | Desktop     | [4d58c53d68](https://bsd-hardware.info/?probe=4d58c53d68) | Nov 27, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [c9f6264329](https://bsd-hardware.info/?probe=c9f6264329) | Nov 27, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [1e9f19c4ae](https://bsd-hardware.info/?probe=1e9f19c4ae) | Nov 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [db10241016](https://bsd-hardware.info/?probe=db10241016) | Nov 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [8b2a1299bf](https://bsd-hardware.info/?probe=8b2a1299bf) | Nov 27, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [af326ddda5](https://bsd-hardware.info/?probe=af326ddda5) | Nov 27, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [3b18ff26c0](https://bsd-hardware.info/?probe=3b18ff26c0) | Nov 27, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [42bddda351](https://bsd-hardware.info/?probe=42bddda351) | Nov 26, 2023 |
| Dell          | Inspiron 7558               | Notebook    | [b34a8742d5](https://bsd-hardware.info/?probe=b34a8742d5) | Nov 26, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [87351f500b](https://bsd-hardware.info/?probe=87351f500b) | Nov 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [14c7b94add](https://bsd-hardware.info/?probe=14c7b94add) | Nov 26, 2023 |
| Intel         | D33217GKE G76540-207        | Desktop     | [9b0af83da8](https://bsd-hardware.info/?probe=9b0af83da8) | Nov 26, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [fa32eea2ff](https://bsd-hardware.info/?probe=fa32eea2ff) | Nov 26, 2023 |
| PC Engines    | APU2                        | Desktop     | [d3c14df95e](https://bsd-hardware.info/?probe=d3c14df95e) | Nov 26, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [6ae043723c](https://bsd-hardware.info/?probe=6ae043723c) | Nov 26, 2023 |
| PC Engines    | APU2                        | Desktop     | [6a15554f47](https://bsd-hardware.info/?probe=6a15554f47) | Nov 26, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [b2de4a6100](https://bsd-hardware.info/?probe=b2de4a6100) | Nov 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [55339dbfab](https://bsd-hardware.info/?probe=55339dbfab) | Nov 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b653e75063](https://bsd-hardware.info/?probe=b653e75063) | Nov 26, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1454187842](https://bsd-hardware.info/?probe=1454187842) | Nov 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [28f6ec2a7b](https://bsd-hardware.info/?probe=28f6ec2a7b) | Nov 26, 2023 |
| ShenZhen M... | 3865U-6L                    | Desktop     | [009e913736](https://bsd-hardware.info/?probe=009e913736) | Nov 26, 2023 |
| PC Engines    | APU3                        | Desktop     | [6032cf8fae](https://bsd-hardware.info/?probe=6032cf8fae) | Nov 26, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7241023750](https://bsd-hardware.info/?probe=7241023750) | Nov 26, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [938720f5a3](https://bsd-hardware.info/?probe=938720f5a3) | Nov 26, 2023 |
| ASRock        | B550 Taichi                 | Desktop     | [60d2873b5d](https://bsd-hardware.info/?probe=60d2873b5d) | Nov 26, 2023 |
| Google        | Kohaku                      | Notebook    | [94c3c0f6b7](https://bsd-hardware.info/?probe=94c3c0f6b7) | Nov 26, 2023 |
| Google        | Kohaku                      | Notebook    | [198b445c4e](https://bsd-hardware.info/?probe=198b445c4e) | Nov 26, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [268228d2b7](https://bsd-hardware.info/?probe=268228d2b7) | Nov 26, 2023 |
| Dell          | 03X6X0 A03                  | Server      | [238143f959](https://bsd-hardware.info/?probe=238143f959) | Nov 26, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [bf23ac0d57](https://bsd-hardware.info/?probe=bf23ac0d57) | Nov 26, 2023 |
| HP            | 0B54h D                     | Desktop     | [92d27048f9](https://bsd-hardware.info/?probe=92d27048f9) | Nov 26, 2023 |
| Dell          | 0XCR8D A01                  | Desktop     | [de52fe9aef](https://bsd-hardware.info/?probe=de52fe9aef) | Nov 26, 2023 |
| HP            | 0B54h D                     | Desktop     | [ca4d073520](https://bsd-hardware.info/?probe=ca4d073520) | Nov 26, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [c6ff092502](https://bsd-hardware.info/?probe=c6ff092502) | Nov 26, 2023 |
| Dell          | 086HF8 A08                  | Server      | [bdef882b62](https://bsd-hardware.info/?probe=bdef882b62) | Nov 26, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [f1adcd15f0](https://bsd-hardware.info/?probe=f1adcd15f0) | Nov 26, 2023 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | Notebook    | [3517ce2745](https://bsd-hardware.info/?probe=3517ce2745) | Nov 26, 2023 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | Notebook    | [5f336b9d93](https://bsd-hardware.info/?probe=5f336b9d93) | Nov 26, 2023 |
| Intel         | CM8I7CB8N K53740-202        | Mini pc     | [481571734a](https://bsd-hardware.info/?probe=481571734a) | Nov 25, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [f2aa7b3ebf](https://bsd-hardware.info/?probe=f2aa7b3ebf) | Nov 25, 2023 |
| Dell          | 0CNCJW A05                  | Server      | [959f3becea](https://bsd-hardware.info/?probe=959f3becea) | Nov 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [c3dc51f3fe](https://bsd-hardware.info/?probe=c3dc51f3fe) | Nov 25, 2023 |
| Dell          | Latitude E5540              | Notebook    | [d12acc0425](https://bsd-hardware.info/?probe=d12acc0425) | Nov 25, 2023 |
| PC Engines    | APU2                        | Desktop     | [c2ab63093b](https://bsd-hardware.info/?probe=c2ab63093b) | Nov 25, 2023 |
| Intel         | NUC5i5RYB H40999-503        | Mini pc     | [3997370fc6](https://bsd-hardware.info/?probe=3997370fc6) | Nov 25, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [5e87df1001](https://bsd-hardware.info/?probe=5e87df1001) | Nov 25, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [be568b54bf](https://bsd-hardware.info/?probe=be568b54bf) | Nov 25, 2023 |
| Dell          | 086HF8 A08                  | Server      | [702f4f9f8f](https://bsd-hardware.info/?probe=702f4f9f8f) | Nov 25, 2023 |
| Dell          | Latitude 5480               | Notebook    | [639ffb1573](https://bsd-hardware.info/?probe=639ffb1573) | Nov 25, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [4661b8933c](https://bsd-hardware.info/?probe=4661b8933c) | Nov 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [ce88332d94](https://bsd-hardware.info/?probe=ce88332d94) | Nov 25, 2023 |
| HP            | 8103 A01                    | Mini pc     | [de7a23f9ca](https://bsd-hardware.info/?probe=de7a23f9ca) | Nov 25, 2023 |
| ADI Engine... | RCC-VE                      | Desktop     | [437a91ad78](https://bsd-hardware.info/?probe=437a91ad78) | Nov 25, 2023 |
| HP            | 8103 A01                    | Mini pc     | [06217360c6](https://bsd-hardware.info/?probe=06217360c6) | Nov 25, 2023 |
| ASRock        | H570M-ITX/ac                | Desktop     | [a8d3950959](https://bsd-hardware.info/?probe=a8d3950959) | Nov 25, 2023 |
| HP            | 1998                        | Desktop     | [7822122c69](https://bsd-hardware.info/?probe=7822122c69) | Nov 25, 2023 |
| Dell          | 01Y1CJ A00                  | Mini pc     | [761475ca9e](https://bsd-hardware.info/?probe=761475ca9e) | Nov 24, 2023 |
| HP            | 1825                        | Desktop     | [373a147d04](https://bsd-hardware.info/?probe=373a147d04) | Nov 24, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [24f4b0ec7e](https://bsd-hardware.info/?probe=24f4b0ec7e) | Nov 24, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7bb170248d](https://bsd-hardware.info/?probe=7bb170248d) | Nov 24, 2023 |
| Dell          | Inspiron 7558               | Notebook    | [aad8d359f3](https://bsd-hardware.info/?probe=aad8d359f3) | Nov 24, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [af2a408d87](https://bsd-hardware.info/?probe=af2a408d87) | Nov 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [b8b5586ead](https://bsd-hardware.info/?probe=b8b5586ead) | Nov 24, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [1d3aee41d6](https://bsd-hardware.info/?probe=1d3aee41d6) | Nov 24, 2023 |
| Dell          | 0MFXTY A01                  | Server      | [d60cd55e61](https://bsd-hardware.info/?probe=d60cd55e61) | Nov 24, 2023 |
| Lenovo        | 0x30F617AA SDK0J40705 WI... | Desktop     | [3385be6d7c](https://bsd-hardware.info/?probe=3385be6d7c) | Nov 24, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [a44d6afa76](https://bsd-hardware.info/?probe=a44d6afa76) | Nov 24, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [b67644f2b3](https://bsd-hardware.info/?probe=b67644f2b3) | Nov 24, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [e0d8200dfa](https://bsd-hardware.info/?probe=e0d8200dfa) | Nov 24, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [dad527aa3b](https://bsd-hardware.info/?probe=dad527aa3b) | Nov 24, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [ece72d8870](https://bsd-hardware.info/?probe=ece72d8870) | Nov 24, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [b11a972371](https://bsd-hardware.info/?probe=b11a972371) | Nov 24, 2023 |
| Google        | Dragonair                   | Notebook    | [713cf1bc38](https://bsd-hardware.info/?probe=713cf1bc38) | Nov 24, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [b479df9cfc](https://bsd-hardware.info/?probe=b479df9cfc) | Nov 24, 2023 |
| HP            | Notebook                    | Notebook    | [aff6430eb2](https://bsd-hardware.info/?probe=aff6430eb2) | Nov 24, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b7e6b2579a](https://bsd-hardware.info/?probe=b7e6b2579a) | Nov 24, 2023 |
| Silicom       | 80300-0214-G16 R310         | Desktop     | [34382c8f4b](https://bsd-hardware.info/?probe=34382c8f4b) | Nov 24, 2023 |
| HP            | 3646h                       | Desktop     | [b3083001a4](https://bsd-hardware.info/?probe=b3083001a4) | Nov 24, 2023 |
| Lenovo        | ThinkPad A485 20MU000VUS    | Notebook    | [8f21b7d70f](https://bsd-hardware.info/?probe=8f21b7d70f) | Nov 24, 2023 |
| Dell          | 0F0XJ6 A13                  | Server      | [f4a31a2e53](https://bsd-hardware.info/?probe=f4a31a2e53) | Nov 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [00ad304a82](https://bsd-hardware.info/?probe=00ad304a82) | Nov 24, 2023 |
| ASRock        | X399 Professional Gaming    | Desktop     | [9c9645e87a](https://bsd-hardware.info/?probe=9c9645e87a) | Nov 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [9762745c92](https://bsd-hardware.info/?probe=9762745c92) | Nov 23, 2023 |
| Lenovo        | ThinkCentre M90n-1 11AHS... | Desktop     | [eca5b59407](https://bsd-hardware.info/?probe=eca5b59407) | Nov 23, 2023 |
| Dell          | Latitude E5440              | Notebook    | [629fba28cc](https://bsd-hardware.info/?probe=629fba28cc) | Nov 23, 2023 |
| YANYU         | ITX-M9F VER:1.3 baytrail    | Desktop     | [c9e7bbc120](https://bsd-hardware.info/?probe=c9e7bbc120) | Nov 23, 2023 |
| PICO PC       | MNHO-113                    | Desktop     | [261b0d936c](https://bsd-hardware.info/?probe=261b0d936c) | Nov 23, 2023 |
| HP            | 0B40h                       | Desktop     | [035db0e1c5](https://bsd-hardware.info/?probe=035db0e1c5) | Nov 23, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [2756c10ff8](https://bsd-hardware.info/?probe=2756c10ff8) | Nov 23, 2023 |
| HP            | 0B40h                       | Desktop     | [559cfb4b40](https://bsd-hardware.info/?probe=559cfb4b40) | Nov 23, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [f99aad52c2](https://bsd-hardware.info/?probe=f99aad52c2) | Nov 23, 2023 |
| Intel         | NUC62R 2C                   | Mini pc     | [d47608f986](https://bsd-hardware.info/?probe=d47608f986) | Nov 23, 2023 |
| Dell          | 0MFXTY A01                  | Server      | [982b2609c5](https://bsd-hardware.info/?probe=982b2609c5) | Nov 23, 2023 |
| Lenovo        | ThinkCentre M720s 10SUSB... | Desktop     | [a44a9f3526](https://bsd-hardware.info/?probe=a44a9f3526) | Nov 23, 2023 |
| HP            | 21D0                        | Desktop     | [d03aa6a73b](https://bsd-hardware.info/?probe=d03aa6a73b) | Nov 23, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [829f20c667](https://bsd-hardware.info/?probe=829f20c667) | Nov 23, 2023 |
| Sophos        | XG                          | Firewall    | [a0539d33da](https://bsd-hardware.info/?probe=a0539d33da) | Nov 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [b5be73085a](https://bsd-hardware.info/?probe=b5be73085a) | Nov 23, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [d883d8bbd1](https://bsd-hardware.info/?probe=d883d8bbd1) | Nov 23, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e26144a9ce](https://bsd-hardware.info/?probe=e26144a9ce) | Nov 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [0d706d98b4](https://bsd-hardware.info/?probe=0d706d98b4) | Nov 23, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [1da7551908](https://bsd-hardware.info/?probe=1da7551908) | Nov 23, 2023 |
| Acer          | JM11-MS                     | Notebook    | [0490895189](https://bsd-hardware.info/?probe=0490895189) | Nov 23, 2023 |
| Dell          | Latitude 7490               | Notebook    | [e860d3dbcf](https://bsd-hardware.info/?probe=e860d3dbcf) | Nov 23, 2023 |
| HP            | 8767 A                      | Desktop     | [12aa6c74c7](https://bsd-hardware.info/?probe=12aa6c74c7) | Nov 23, 2023 |
| Dell          | 00P8G1 A00                  | All in one  | [daca9b37fd](https://bsd-hardware.info/?probe=daca9b37fd) | Nov 23, 2023 |
| Protectli     | VP2420                      | Desktop     | [ec846da264](https://bsd-hardware.info/?probe=ec846da264) | Nov 23, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [086dd66ae7](https://bsd-hardware.info/?probe=086dd66ae7) | Nov 22, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [eca8e8785c](https://bsd-hardware.info/?probe=eca8e8785c) | Nov 22, 2023 |
| Intel         | DH67BL AAG10189-207         | Desktop     | [734103b696](https://bsd-hardware.info/?probe=734103b696) | Nov 22, 2023 |
| AZW           | EQ                          | Desktop     | [3407ab2a5b](https://bsd-hardware.info/?probe=3407ab2a5b) | Nov 22, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [81faa8cbd2](https://bsd-hardware.info/?probe=81faa8cbd2) | Nov 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [87ab49a51e](https://bsd-hardware.info/?probe=87ab49a51e) | Nov 22, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [9f6d0c8539](https://bsd-hardware.info/?probe=9f6d0c8539) | Nov 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [b60795e523](https://bsd-hardware.info/?probe=b60795e523) | Nov 22, 2023 |
| Dell          | 0GY6Y8 A00                  | Desktop     | [8181170ec9](https://bsd-hardware.info/?probe=8181170ec9) | Nov 22, 2023 |
| Shuttle       | XH310V2                     | Desktop     | [524f7be8b5](https://bsd-hardware.info/?probe=524f7be8b5) | Nov 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [c8960ff614](https://bsd-hardware.info/?probe=c8960ff614) | Nov 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [1bed6c30cd](https://bsd-hardware.info/?probe=1bed6c30cd) | Nov 22, 2023 |
| HP            | 339A                        | Desktop     | [fdc6ee7b57](https://bsd-hardware.info/?probe=fdc6ee7b57) | Nov 22, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [a4eded7a52](https://bsd-hardware.info/?probe=a4eded7a52) | Nov 22, 2023 |
| Cisco         | ASA5525 A0                  | Desktop     | [0e4aa1cec5](https://bsd-hardware.info/?probe=0e4aa1cec5) | Nov 22, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [4c5aa5c3ea](https://bsd-hardware.info/?probe=4c5aa5c3ea) | Nov 22, 2023 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [2c256503f5](https://bsd-hardware.info/?probe=2c256503f5) | Nov 22, 2023 |
| Acidanther... | MacBookPro16,3              | Notebook    | [5f89fa2cd2](https://bsd-hardware.info/?probe=5f89fa2cd2) | Nov 22, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [4c80855e88](https://bsd-hardware.info/?probe=4c80855e88) | Nov 22, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cb6ef0498c](https://bsd-hardware.info/?probe=cb6ef0498c) | Nov 22, 2023 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [ae412e2945](https://bsd-hardware.info/?probe=ae412e2945) | Nov 22, 2023 |
| HP            | 213D A01                    | Desktop     | [cc42c64a45](https://bsd-hardware.info/?probe=cc42c64a45) | Nov 22, 2023 |
| MUCAI         | H61 V1.6A                   | Desktop     | [f750403713](https://bsd-hardware.info/?probe=f750403713) | Nov 21, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [3738ed9dd2](https://bsd-hardware.info/?probe=3738ed9dd2) | Nov 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [fe1688477a](https://bsd-hardware.info/?probe=fe1688477a) | Nov 21, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [a37a33268d](https://bsd-hardware.info/?probe=a37a33268d) | Nov 21, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [2ea96f8806](https://bsd-hardware.info/?probe=2ea96f8806) | Nov 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [74aaffb0d7](https://bsd-hardware.info/?probe=74aaffb0d7) | Nov 21, 2023 |
| Toshiba       | Satellite C40-A             | Notebook    | [0c545b75e9](https://bsd-hardware.info/?probe=0c545b75e9) | Nov 21, 2023 |
| Thomas-Kre... | LES network 6L              | Desktop     | [654e4f96f7](https://bsd-hardware.info/?probe=654e4f96f7) | Nov 21, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [c208293594](https://bsd-hardware.info/?probe=c208293594) | Nov 21, 2023 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [06a7986011](https://bsd-hardware.info/?probe=06a7986011) | Nov 21, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d842474f9a](https://bsd-hardware.info/?probe=d842474f9a) | Nov 21, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [fb283e956a](https://bsd-hardware.info/?probe=fb283e956a) | Nov 21, 2023 |
| PC Engines    | APU                         | Desktop     | [53fd63efac](https://bsd-hardware.info/?probe=53fd63efac) | Nov 21, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [19dfa9e36a](https://bsd-hardware.info/?probe=19dfa9e36a) | Nov 21, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [2049a0d3db](https://bsd-hardware.info/?probe=2049a0d3db) | Nov 21, 2023 |
| CWWK          | MINIPC-G4                   | Desktop     | [d9b122a533](https://bsd-hardware.info/?probe=d9b122a533) | Nov 21, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [9f690594a0](https://bsd-hardware.info/?probe=9f690594a0) | Nov 21, 2023 |
| Toshiba       | Satellite C40-A             | Notebook    | [cecd389c82](https://bsd-hardware.info/?probe=cecd389c82) | Nov 21, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3b2c6796da](https://bsd-hardware.info/?probe=3b2c6796da) | Nov 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [87466d5ec0](https://bsd-hardware.info/?probe=87466d5ec0) | Nov 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [95d2a9f59c](https://bsd-hardware.info/?probe=95d2a9f59c) | Nov 21, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [9b3cb9cbd6](https://bsd-hardware.info/?probe=9b3cb9cbd6) | Nov 21, 2023 |
| Pegatron      | TRUCKEE                     | Desktop     | [9f4c9969f1](https://bsd-hardware.info/?probe=9f4c9969f1) | Nov 21, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [ec5731af27](https://bsd-hardware.info/?probe=ec5731af27) | Nov 21, 2023 |
| Pegatron      | TRUCKEE                     | Desktop     | [8c8daeff55](https://bsd-hardware.info/?probe=8c8daeff55) | Nov 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [ff855b549e](https://bsd-hardware.info/?probe=ff855b549e) | Nov 20, 2023 |
| Protectli     | FW4C                        | Desktop     | [7fa5301a63](https://bsd-hardware.info/?probe=7fa5301a63) | Nov 20, 2023 |
| ASRock        | H470M-ITX/ac                | Desktop     | [e54ba21f70](https://bsd-hardware.info/?probe=e54ba21f70) | Nov 20, 2023 |
| YANYU         | R250                        | Desktop     | [74ee81493f](https://bsd-hardware.info/?probe=74ee81493f) | Nov 20, 2023 |
| AZW           | EQ                          | Desktop     | [cb2efd436d](https://bsd-hardware.info/?probe=cb2efd436d) | Nov 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [6e5266f2a1](https://bsd-hardware.info/?probe=6e5266f2a1) | Nov 20, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d38d698b2e](https://bsd-hardware.info/?probe=d38d698b2e) | Nov 20, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4b6284d041](https://bsd-hardware.info/?probe=4b6284d041) | Nov 20, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [07766d29fd](https://bsd-hardware.info/?probe=07766d29fd) | Nov 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [da5da3b1a4](https://bsd-hardware.info/?probe=da5da3b1a4) | Nov 20, 2023 |
| PICO PC       | MNHO-113                    | Desktop     | [c9a12372b4](https://bsd-hardware.info/?probe=c9a12372b4) | Nov 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [fad6ccb3f8](https://bsd-hardware.info/?probe=fad6ccb3f8) | Nov 20, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [96562d6513](https://bsd-hardware.info/?probe=96562d6513) | Nov 20, 2023 |
| AZW           | EQ                          | Desktop     | [adcc84f66a](https://bsd-hardware.info/?probe=adcc84f66a) | Nov 20, 2023 |
| Supermicro    | A2SAP-HA                    | Desktop     | [c912b74149](https://bsd-hardware.info/?probe=c912b74149) | Nov 20, 2023 |
| AZW           | EQ                          | Desktop     | [9f0dd7c0b4](https://bsd-hardware.info/?probe=9f0dd7c0b4) | Nov 20, 2023 |
| Dell          | 01V648 A07                  | Server      | [cb698d50c6](https://bsd-hardware.info/?probe=cb698d50c6) | Nov 20, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [fdb7c00df7](https://bsd-hardware.info/?probe=fdb7c00df7) | Nov 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [a3d67285a6](https://bsd-hardware.info/?probe=a3d67285a6) | Nov 19, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [5caaad73bd](https://bsd-hardware.info/?probe=5caaad73bd) | Nov 19, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [17d29b1055](https://bsd-hardware.info/?probe=17d29b1055) | Nov 19, 2023 |
| ASRock        | Z370 Gaming K6              | Desktop     | [0b219600a3](https://bsd-hardware.info/?probe=0b219600a3) | Nov 19, 2023 |
| Protectli     | VP2420                      | Desktop     | [42bac7a450](https://bsd-hardware.info/?probe=42bac7a450) | Nov 19, 2023 |
| Sophos        | SG                          | Firewall    | [516a13a5f0](https://bsd-hardware.info/?probe=516a13a5f0) | Nov 19, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [41bb4c277b](https://bsd-hardware.info/?probe=41bb4c277b) | Nov 19, 2023 |
| HP            | 1998                        | Desktop     | [60c8a90e7e](https://bsd-hardware.info/?probe=60c8a90e7e) | Nov 19, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [797f393ce0](https://bsd-hardware.info/?probe=797f393ce0) | Nov 19, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6406980bbf](https://bsd-hardware.info/?probe=6406980bbf) | Nov 19, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [e7ccb4156e](https://bsd-hardware.info/?probe=e7ccb4156e) | Nov 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a570c7994c](https://bsd-hardware.info/?probe=a570c7994c) | Nov 19, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [e6bfeee196](https://bsd-hardware.info/?probe=e6bfeee196) | Nov 19, 2023 |
| Lenovo        | ThinkPad W530 24411M9       | Notebook    | [0272396725](https://bsd-hardware.info/?probe=0272396725) | Nov 19, 2023 |
| Supermicro    | X11SBA-LN4F-SI011A          | Server      | [5480de19a2](https://bsd-hardware.info/?probe=5480de19a2) | Nov 19, 2023 |
| Intel         | ND2X-NET-PC BIOS Revisio... | Desktop     | [7fd080cf42](https://bsd-hardware.info/?probe=7fd080cf42) | Nov 19, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [72987e629d](https://bsd-hardware.info/?probe=72987e629d) | Nov 19, 2023 |
| MSI           | B560-A PRO                  | Desktop     | [cf9b5a14ce](https://bsd-hardware.info/?probe=cf9b5a14ce) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [2c33e6e9e7](https://bsd-hardware.info/?probe=2c33e6e9e7) | Nov 19, 2023 |
| Gigabyte      | Z68X-UD5-B3                 | Desktop     | [f8fcca51ca](https://bsd-hardware.info/?probe=f8fcca51ca) | Nov 19, 2023 |
| Protectli     | VP2420                      | Desktop     | [05284d48bc](https://bsd-hardware.info/?probe=05284d48bc) | Nov 19, 2023 |
| Dell          | Latitude 5440               | Notebook    | [9daa44aacf](https://bsd-hardware.info/?probe=9daa44aacf) | Nov 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [8f162077aa](https://bsd-hardware.info/?probe=8f162077aa) | Nov 18, 2023 |
| Panasonic     | CF-31-5                     | Notebook    | [8771ab6139](https://bsd-hardware.info/?probe=8771ab6139) | Nov 18, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [6074d7118a](https://bsd-hardware.info/?probe=6074d7118a) | Nov 18, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [bd12235645](https://bsd-hardware.info/?probe=bd12235645) | Nov 18, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [9eab94b4f7](https://bsd-hardware.info/?probe=9eab94b4f7) | Nov 18, 2023 |
| Deciso        | Netboard A10                | Desktop     | [5efc270fa6](https://bsd-hardware.info/?probe=5efc270fa6) | Nov 18, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [947076a4de](https://bsd-hardware.info/?probe=947076a4de) | Nov 18, 2023 |
| Lenovo        | ThinkPad T60 8744HDG        | Notebook    | [fc54b10db3](https://bsd-hardware.info/?probe=fc54b10db3) | Nov 18, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [00de0389fb](https://bsd-hardware.info/?probe=00de0389fb) | Nov 18, 2023 |
| Dell          | Precision 5520              | Notebook    | [45f5e399a4](https://bsd-hardware.info/?probe=45f5e399a4) | Nov 18, 2023 |
| Supermicro    | H8SML                       | Desktop     | [c4a58844c5](https://bsd-hardware.info/?probe=c4a58844c5) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [cfbda53125](https://bsd-hardware.info/?probe=cfbda53125) | Nov 18, 2023 |
| HP            | Notebook                    | Notebook    | [c583c221c7](https://bsd-hardware.info/?probe=c583c221c7) | Nov 17, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [83673368b9](https://bsd-hardware.info/?probe=83673368b9) | Nov 17, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [07dbd58d8e](https://bsd-hardware.info/?probe=07dbd58d8e) | Nov 17, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [9061ad4228](https://bsd-hardware.info/?probe=9061ad4228) | Nov 17, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [9ca9377fee](https://bsd-hardware.info/?probe=9ca9377fee) | Nov 17, 2023 |
| ADLINK Tec... | ABEG                        | Desktop     | [87e37876b0](https://bsd-hardware.info/?probe=87e37876b0) | Nov 17, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [ece5171a1d](https://bsd-hardware.info/?probe=ece5171a1d) | Nov 17, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [d44a6cfd84](https://bsd-hardware.info/?probe=d44a6cfd84) | Nov 17, 2023 |
| HP            | 17E2                        | Mini pc     | [2e93df6830](https://bsd-hardware.info/?probe=2e93df6830) | Nov 17, 2023 |
| Protectli     | VP2420                      | Desktop     | [ee1cbf5fd0](https://bsd-hardware.info/?probe=ee1cbf5fd0) | Nov 17, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | Desktop     | [1b811bacb7](https://bsd-hardware.info/?probe=1b811bacb7) | Nov 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [42f8d10b95](https://bsd-hardware.info/?probe=42f8d10b95) | Nov 17, 2023 |
| HP            | Notebook                    | Notebook    | [5d2df329aa](https://bsd-hardware.info/?probe=5d2df329aa) | Nov 17, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [a81ae16c47](https://bsd-hardware.info/?probe=a81ae16c47) | Nov 17, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [2aa8175a33](https://bsd-hardware.info/?probe=2aa8175a33) | Nov 17, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [2bc7167601](https://bsd-hardware.info/?probe=2bc7167601) | Nov 17, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | Desktop     | [204ee8891b](https://bsd-hardware.info/?probe=204ee8891b) | Nov 16, 2023 |
| Dell          | Precision 7720              | Notebook    | [65a0287ad6](https://bsd-hardware.info/?probe=65a0287ad6) | Nov 16, 2023 |
| Unknown       | YL-SKUL6                    | Desktop     | [ac654676da](https://bsd-hardware.info/?probe=ac654676da) | Nov 16, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [984f5f2f4b](https://bsd-hardware.info/?probe=984f5f2f4b) | Nov 16, 2023 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [a406ee9805](https://bsd-hardware.info/?probe=a406ee9805) | Nov 16, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [8610627793](https://bsd-hardware.info/?probe=8610627793) | Nov 16, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [a5aa96e30f](https://bsd-hardware.info/?probe=a5aa96e30f) | Nov 16, 2023 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [c555ae522c](https://bsd-hardware.info/?probe=c555ae522c) | Nov 16, 2023 |
| PC Engines    | APU2                        | Desktop     | [5ea4af0d94](https://bsd-hardware.info/?probe=5ea4af0d94) | Nov 16, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [23b537c7a3](https://bsd-hardware.info/?probe=23b537c7a3) | Nov 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [066991fce5](https://bsd-hardware.info/?probe=066991fce5) | Nov 16, 2023 |
| Lenovo        | ThinkPad X230 2320A5U       | Notebook    | [48f8b6a93a](https://bsd-hardware.info/?probe=48f8b6a93a) | Nov 16, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [e28d22b5ed](https://bsd-hardware.info/?probe=e28d22b5ed) | Nov 16, 2023 |
| HP            | 213D A01                    | Desktop     | [eff9e5704a](https://bsd-hardware.info/?probe=eff9e5704a) | Nov 16, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | Desktop     | [b34836b090](https://bsd-hardware.info/?probe=b34836b090) | Nov 16, 2023 |
| Intel         | BayTrail Platform           | Tablet      | [cefd9be0a9](https://bsd-hardware.info/?probe=cefd9be0a9) | Nov 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [8854b07e12](https://bsd-hardware.info/?probe=8854b07e12) | Nov 15, 2023 |
| Intel         | QHSW02                      | Desktop     | [f05cdb2841](https://bsd-hardware.info/?probe=f05cdb2841) | Nov 15, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [e5f0053202](https://bsd-hardware.info/?probe=e5f0053202) | Nov 15, 2023 |
| Lenovo        | ThinkServer RS160 70TG      | Server      | [9a47c94254](https://bsd-hardware.info/?probe=9a47c94254) | Nov 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [918706e110](https://bsd-hardware.info/?probe=918706e110) | Nov 15, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7719e7606c](https://bsd-hardware.info/?probe=7719e7606c) | Nov 15, 2023 |
| Supermicro    | H8DGU                       | Server      | [aa3a09d113](https://bsd-hardware.info/?probe=aa3a09d113) | Nov 15, 2023 |
| Supermicro    | H8DGU                       | Server      | [5ca736990f](https://bsd-hardware.info/?probe=5ca736990f) | Nov 15, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [6257d05c99](https://bsd-hardware.info/?probe=6257d05c99) | Nov 15, 2023 |
| Lenovo        | NOK                         | Desktop     | [6d55a75c4d](https://bsd-hardware.info/?probe=6d55a75c4d) | Nov 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0e4ea9ccbf](https://bsd-hardware.info/?probe=0e4ea9ccbf) | Nov 15, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [7d9f6b4511](https://bsd-hardware.info/?probe=7d9f6b4511) | Nov 15, 2023 |
| Dell          | G5 5505                     | Notebook    | [088aea32c0](https://bsd-hardware.info/?probe=088aea32c0) | Nov 15, 2023 |
| Supermicro    | X10SRH-CFA                  | Server      | [0550bd6c93](https://bsd-hardware.info/?probe=0550bd6c93) | Nov 15, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [98fac2d452](https://bsd-hardware.info/?probe=98fac2d452) | Nov 15, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [3e93db0df7](https://bsd-hardware.info/?probe=3e93db0df7) | Nov 15, 2023 |
| HP            | Compaq CQ45                 | Desktop     | [4f3c176253](https://bsd-hardware.info/?probe=4f3c176253) | Nov 14, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [e98965d0f9](https://bsd-hardware.info/?probe=e98965d0f9) | Nov 14, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [0f82d77235](https://bsd-hardware.info/?probe=0f82d77235) | Nov 14, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [fec17c799c](https://bsd-hardware.info/?probe=fec17c799c) | Nov 14, 2023 |
| HP            | ProLiant DL360 G5           | Server      | [8b2811bcf5](https://bsd-hardware.info/?probe=8b2811bcf5) | Nov 14, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [7d58ae8d97](https://bsd-hardware.info/?probe=7d58ae8d97) | Nov 14, 2023 |
| HP            | 18E7                        | Desktop     | [3cbe1117fa](https://bsd-hardware.info/?probe=3cbe1117fa) | Nov 14, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [4984b1536a](https://bsd-hardware.info/?probe=4984b1536a) | Nov 14, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [5d9467ed74](https://bsd-hardware.info/?probe=5d9467ed74) | Nov 14, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [629ec873d7](https://bsd-hardware.info/?probe=629ec873d7) | Nov 14, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [b858bd0986](https://bsd-hardware.info/?probe=b858bd0986) | Nov 14, 2023 |
| Unknown       | Raspberry Pi                | Soc         | [de988c2e66](https://bsd-hardware.info/?probe=de988c2e66) | Nov 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [db926657cc](https://bsd-hardware.info/?probe=db926657cc) | Nov 14, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [253d230fd3](https://bsd-hardware.info/?probe=253d230fd3) | Nov 14, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [0e443cd752](https://bsd-hardware.info/?probe=0e443cd752) | Nov 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d74a1ddc22](https://bsd-hardware.info/?probe=d74a1ddc22) | Nov 14, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [2487233a5d](https://bsd-hardware.info/?probe=2487233a5d) | Nov 13, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [ee4c8ddddc](https://bsd-hardware.info/?probe=ee4c8ddddc) | Nov 13, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ea2d57ac16](https://bsd-hardware.info/?probe=ea2d57ac16) | Nov 13, 2023 |
| Lenovo        | NOK                         | Desktop     | [52593923f0](https://bsd-hardware.info/?probe=52593923f0) | Nov 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [7c541b6943](https://bsd-hardware.info/?probe=7c541b6943) | Nov 13, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [d6f10bf9d2](https://bsd-hardware.info/?probe=d6f10bf9d2) | Nov 13, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [97267cbee9](https://bsd-hardware.info/?probe=97267cbee9) | Nov 13, 2023 |
| Dell          | 015HP0 A00                  | Mini pc     | [b282285d51](https://bsd-hardware.info/?probe=b282285d51) | Nov 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [771c13f8ea](https://bsd-hardware.info/?probe=771c13f8ea) | Nov 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [35ae423f7a](https://bsd-hardware.info/?probe=35ae423f7a) | Nov 13, 2023 |
| Dell          | 015HP0 A00                  | Mini pc     | [2c1f962756](https://bsd-hardware.info/?probe=2c1f962756) | Nov 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [8b333abcaa](https://bsd-hardware.info/?probe=8b333abcaa) | Nov 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [ed79ea60c4](https://bsd-hardware.info/?probe=ed79ea60c4) | Nov 13, 2023 |
| MUCAI         | H61 V1.6A                   | Desktop     | [bd3f1334ee](https://bsd-hardware.info/?probe=bd3f1334ee) | Nov 13, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [3f63ee5447](https://bsd-hardware.info/?probe=3f63ee5447) | Nov 13, 2023 |
| HP            | 8594                        | Desktop     | [3f87234909](https://bsd-hardware.info/?probe=3f87234909) | Nov 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [626ff9ba56](https://bsd-hardware.info/?probe=626ff9ba56) | Nov 13, 2023 |
| HP            | 8594                        | Desktop     | [3da4e9f75d](https://bsd-hardware.info/?probe=3da4e9f75d) | Nov 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0fd2711a56](https://bsd-hardware.info/?probe=0fd2711a56) | Nov 12, 2023 |
| Protectli     | VP4650                      | Desktop     | [0eeeb46242](https://bsd-hardware.info/?probe=0eeeb46242) | Nov 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [3892c7ab84](https://bsd-hardware.info/?probe=3892c7ab84) | Nov 12, 2023 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 448       | 2.72%   |
| helloSystem 0.8.1    | 416       | 2.53%   |
| OPNsense 23.1.11     | 349       | 2.12%   |
| OPNsense 21.7.7      | 281       | 1.71%   |
| OPNsense 22.7.10     | 262       | 1.59%   |
| helloSystem 0.8.0    | 254       | 1.54%   |
| helloSystem 0.5.0    | 245       | 1.49%   |
| OPNsense 21.1        | 240       | 1.46%   |
| FreeBSD 13.1         | 235       | 1.43%   |
| OPNsense 23.1        | 229       | 1.39%   |
| OPNsense 21.7.1      | 229       | 1.39%   |
| OPNsense 22.1        | 227       | 1.38%   |
| OPNsense 21.7.3      | 225       | 1.37%   |
| OPNsense 21.1.5      | 225       | 1.37%   |
| FreeBSD 13.0         | 223       | 1.35%   |
| OPNsense 23.7.10     | 222       | 1.35%   |
| OPNsense 23.1.5      | 220       | 1.34%   |
| OPNsense 23.7.9      | 215       | 1.31%   |
| OPNsense 22.7.4      | 214       | 1.3%    |
| OPNsense 20.7.8      | 214       | 1.3%    |
| OpenBSD 6.8          | 208       | 1.26%   |
| OPNsense 21.1.3      | 205       | 1.24%   |
| OPNsense 23.1.7      | 196       | 1.19%   |
| OPNsense 23.1.1      | 192       | 1.17%   |
| OPNsense 22.1.6      | 192       | 1.17%   |
| helloSystem 0.4.0    | 190       | 1.15%   |
| OPNsense 22.1.8      | 187       | 1.14%   |
| OPNsense 22.1.10     | 185       | 1.12%   |
| OPNsense 22.7.6      | 184       | 1.12%   |
| OPNsense 23.7.7      | 182       | 1.1%    |
| OPNsense 22.7.9      | 175       | 1.06%   |
| OPNsense 21.1.4      | 175       | 1.06%   |
| OPNsense 23.7.1      | 169       | 1.03%   |
| OPNsense 23.1.9      | 160       | 0.97%   |
| OPNsense 21.1.1      | 157       | 0.95%   |
| FreeBSD 14.0-CURRENT | 152       | 0.92%   |
| OPNsense 23.1.6      | 149       | 0.9%    |
| OPNsense 21.1.2      | 147       | 0.89%   |
| FreeBSD 13.2         | 147       | 0.89%   |
| OPNsense 23.7.5      | 143       | 0.87%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 6947      | 55.13%  |
| FreeBSD     | 2519      | 19.99%  |
| helloSystem | 1710      | 13.57%  |
| OpenBSD     | 613       | 4.86%   |
| GhostBSD    | 288       | 2.29%   |
| NomadBSD    | 199       | 1.58%   |
| NetBSD      | 81        | 0.64%   |
| TrueNAS     | 50        | 0.4%    |
| pfSense     | 34        | 0.27%   |
| FreeNAS     | 30        | 0.24%   |
| MyBee       | 27        | 0.21%   |
| HardenedBSD | 19        | 0.15%   |
| MidnightBSD | 18        | 0.14%   |
| DragonFly   | 16        | 0.13%   |
| XigmaNAS    | 14        | 0.11%   |
| FuryBSD     | 12        | 0.1%    |
| FuguIta     | 7         | 0.06%   |
| ClonOS      | 7         | 0.06%   |
| OS108       | 4         | 0.03%   |
| Ting        | 3         | 0.02%   |
| PC-BSD      | 3         | 0.02%   |
| LibertyBSD  | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 12090     | 97.34%  |
| i386    | 147       | 1.18%   |
| arm64   | 135       | 1.09%   |
| arm     | 14        | 0.11%   |
| macppc  | 10        | 0.08%   |
| evbarm  | 9         | 0.07%   |
| sparc64 | 6         | 0.05%   |
| powerpc | 5         | 0.04%   |
| octeon  | 2         | 0.02%   |
| armv7   | 2         | 0.02%   |
| riscv   | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Console          | 8117      | 63.79%  |
| helloDesktop     | 1917      | 15.07%  |
| XFCE             | 525       | 4.13%   |
| KDE5             | 470       | 3.69%   |
| MATE             | 378       | 2.97%   |
| fvwm             | 275       | 2.16%   |
| openbox          | 232       | 1.82%   |
| GNOME            | 221       | 1.74%   |
| TWM              | 193       | 1.52%   |
| i3               | 122       | 0.96%   |
| Cinnamon         | 35        | 0.28%   |
| LXQt             | 33        | 0.26%   |
| AwesomeWM        | 29        | 0.23%   |
| Fluxbox          | 25        | 0.2%    |
| Enlightenment    | 21        | 0.17%   |
| LXDE             | 16        | 0.13%   |
| xinitrc          | 12        | 0.09%   |
| Lumina           | 12        | 0.09%   |
| DWM              | 12        | 0.09%   |
| GNUstep          | 7         | 0.06%   |
| Window Maker     | 6         | 0.05%   |
| CTWM             | 6         | 0.05%   |
| Picom            | 5         | 0.04%   |
| IceWM            | 5         | 0.04%   |
| xfwm             | 4         | 0.03%   |
| X-Cinnamon       | 4         | 0.03%   |
| CDE              | 4         | 0.03%   |
| Budgie           | 4         | 0.03%   |
| spectrwm         | 3         | 0.02%   |
| KDE              | 3         | 0.02%   |
| Xfwm4            | 2         | 0.02%   |
| StumpWM          | 2         | 0.02%   |
| Mutter           | 2         | 0.02%   |
| Metacity (Marco) | 2         | 0.02%   |
| JWM              | 2         | 0.02%   |
| Compton          | 2         | 0.02%   |
| Awesome          | 2         | 0.02%   |
| sway             | 1         | 0.01%   |
| sdorfehs         | 1         | 0.01%   |
| Ratpoison        | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 8229      | 65.87%  |
| X11     | 4196      | 33.59%  |
| Wayland | 66        | 0.53%   |
| Tty     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 9184      | 72.74%  |
| SLiM    | 2135      | 16.91%  |
| SDDM    | 494       | 3.91%   |
| LightDM | 464       | 3.68%   |
| XDM     | 173       | 1.37%   |
| GDM     | 149       | 1.18%   |
| Ly      | 23        | 0.18%   |
| PCDM    | 2         | 0.02%   |
| WDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 8282      | 64.87%  |
| en_US           | 1975      | 15.47%  |
| C               | 1389      | 10.88%  |
| ru_RU           | 213       | 1.67%   |
| fr_FR           | 165       | 1.29%   |
| de_DE           | 128       | 1%      |
| en              | 92        | 0.72%   |
| en_GB           | 61        | 0.48%   |
| es_ES           | 56        | 0.44%   |
| pt_BR           | 35        | 0.27%   |
| pl_PL           | 29        | 0.23%   |
| it_IT           | 29        | 0.23%   |
| zh_CN           | 27        | 0.21%   |
| fr              | 17        | 0.13%   |
| en_CA           | 16        | 0.13%   |
| en_AU           | 16        | 0.13%   |
| ru              | 13        | 0.1%    |
| fi_FI           | 13        | 0.1%    |
| ja_JP           | 12        | 0.09%   |
| zh_TW           | 10        | 0.08%   |
| uk_UA           | 10        | 0.08%   |
| pt              | 9         | 0.07%   |
| es              | 9         | 0.07%   |
| en_IE           | 8         | 0.06%   |
| de              | 8         | 0.06%   |
| nb_NO           | 7         | 0.05%   |
| cs_CZ           | 7         | 0.05%   |
| tr_TR           | 6         | 0.05%   |
| nl_NL           | 6         | 0.05%   |
| hu_HU           | 6         | 0.05%   |
| es_AR           | 6         | 0.05%   |
| sv_SE           | 5         | 0.04%   |
| en_NZ           | 5         | 0.04%   |
| el_GR           | 5         | 0.04%   |
| ru_RU.KOI8-R    | 4         | 0.03%   |
| ko_KR           | 4         | 0.03%   |
| jp_JP           | 4         | 0.03%   |
| en_US.ISO8859-1 | 4         | 0.03%   |
| de_CH           | 4         | 0.03%   |
| pt_PT           | 3         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 10509     | 83.71%  |
| BIOS | 2045      | 16.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 6034      | 47.19%  |
| Zfs     | 5422      | 42.4%   |
| Cd9660  | 682       | 5.33%   |
| Ffs     | 621       | 4.86%   |
| Hammer2 | 15        | 0.12%   |
| Unknown | 7         | 0.05%   |
| XXX     | 3         | 0.02%   |
| Nfs     | 2         | 0.02%   |
| Xfs     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 11360     | 90.81%  |
| MBR     | 992       | 7.93%   |
| Unknown | 142       | 1.14%   |
| BSD     | 16        | 0.13%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 1426      | 11.48%  |
| Lenovo                  | 1272      | 10.24%  |
| Unknown                 | 1091      | 8.79%   |
| Hewlett-Packard         | 1072      | 8.63%   |
| ASUSTek Computer        | 1033      | 8.32%   |
| Intel                   | 604       | 4.86%   |
| Supermicro              | 549       | 4.42%   |
| Gigabyte Technology     | 536       | 4.32%   |
| ASRock                  | 460       | 3.7%    |
| Protectli               | 372       | 3%      |
| PC Engines              | 365       | 2.94%   |
| MSI                     | 332       | 2.67%   |
| Fujitsu                 | 251       | 2.02%   |
| AMI                     | 236       | 1.9%    |
| Acer                    | 218       | 1.76%   |
| Apple                   | 195       | 1.57%   |
| Sophos                  | 178       | 1.43%   |
| Techvision              | 138       | 1.11%   |
| ZOTAC                   | 107       | 0.86%   |
| Deciso                  | 106       | 0.85%   |
| Shuttle                 | 76        | 0.61%   |
| BESSTAR Tech            | 74        | 0.6%    |
| Toshiba                 | 64        | 0.52%   |
| AZW                     | 63        | 0.51%   |
| Samsung Electronics     | 57        | 0.46%   |
| MW                      | 56        | 0.45%   |
| Biostar                 | 46        | 0.37%   |
| ASRockRack              | 41        | 0.33%   |
| IBM                     | 40        | 0.32%   |
| Raspberry Pi Foundation | 38        | 0.31%   |
| CWWK                    | 38        | 0.31%   |
| CncTion                 | 38        | 0.31%   |
| Sony                    | 37        | 0.3%    |
| AWOW                    | 37        | 0.3%    |
| Hardkernel              | 36        | 0.29%   |
| Google                  | 36        | 0.29%   |
| CompuLab                | 31        | 0.25%   |
| IceWhale Technology     | 29        | 0.23%   |
| Foxconn                 | 27        | 0.22%   |
| Pegatron                | 26        | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 1134      | 9.13%   |
| PC Engines APU2                     | 179       | 1.44%   |
| AMI Aptio CRB                       | 175       | 1.41%   |
| Supermicro Super Server             | 153       | 1.23%   |
| Techvision TVI7309X                 | 138       | 1.11%   |
| Intel Q3XXG4-P V1.0                 | 131       | 1.06%   |
| Protectli FW4B                      | 128       | 1.03%   |
| PC Engines apu4                     | 114       | 0.92%   |
| Protectli FW6                       | 102       | 0.82%   |
| Sophos SG                           | 97        | 0.78%   |
| ASUS All Series                     | 94        | 0.76%   |
| Fujitsu FUTRO S920                  | 86        | 0.69%   |
| HP t620 PLUS Quad Core TC           | 60        | 0.48%   |
| HP t730 Thin Client                 | 58        | 0.47%   |
| MW GMLK-2_5G4L                      | 56        | 0.45%   |
| Dell OptiPlex 9020                  | 55        | 0.44%   |
| Dell PowerEdge R210 II              | 51        | 0.41%   |
| Dell OptiPlex 3020                  | 51        | 0.41%   |
| Sophos XG                           | 47        | 0.38%   |
| Dell OptiPlex 7010                  | 44        | 0.35%   |
| Dell Wyse 5070 Extended Thin Client | 34        | 0.27%   |
| Sophos UTM                          | 33        | 0.27%   |
| Protectli VP2420                    | 31        | 0.25%   |
| Dell OptiPlex 7040                  | 30        | 0.24%   |
| Supermicro A1SAi                    | 29        | 0.23%   |
| RPi Raspberry Pi                    | 29        | 0.23%   |
| HP EliteDesk 800 G1 SFF             | 29        | 0.23%   |
| Hardkernel ODROID-H2                | 29        | 0.23%   |
| Supermicro X9SCL/X9SCM              | 28        | 0.23%   |
| Supermicro X10SLH-N6-ST031          | 28        | 0.23%   |
| Protectli VP2410                    | 27        | 0.22%   |
| PC Engines APU3                     | 27        | 0.22%   |
| HP Compaq Elite 8300 SFF            | 25        | 0.2%    |
| Deciso NetBoard-A10                 | 25        | 0.2%    |
| ZOTAC ZBOX-CI329NANO                | 24        | 0.19%   |
| PC Engines APU                      | 24        | 0.19%   |
| CompuLab fitlet2                    | 24        | 0.19%   |
| BESSTAR Tech GK41                   | 24        | 0.19%   |
| Intel CRESCENTBAY                   | 23        | 0.19%   |
| HP ProLiant MicroServer Gen8        | 23        | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 1134      | 9.13%   |
| Lenovo ThinkPad     | 722       | 5.81%   |
| Dell OptiPlex       | 485       | 3.91%   |
| Dell PowerEdge      | 334       | 2.69%   |
| Lenovo ThinkCentre  | 256       | 2.06%   |
| Dell Latitude       | 185       | 1.49%   |
| PC Engines APU2     | 179       | 1.44%   |
| AMI Aptio           | 177       | 1.43%   |
| ASUS PRIME          | 162       | 1.3%    |
| HP ProLiant         | 160       | 1.29%   |
| Supermicro Super    | 153       | 1.23%   |
| Dell Inspiron       | 147       | 1.18%   |
| Techvision TVI7309X | 138       | 1.11%   |
| Acer Aspire         | 138       | 1.11%   |
| Intel Q3XXG4-P      | 132       | 1.06%   |
| HP Compaq           | 130       | 1.05%   |
| Protectli FW4B      | 128       | 1.03%   |
| HP EliteDesk        | 121       | 0.97%   |
| Fujitsu FUTRO       | 121       | 0.97%   |
| HP ProDesk          | 115       | 0.93%   |
| PC Engines apu4     | 114       | 0.92%   |
| Protectli FW6       | 102       | 0.82%   |
| Dell Precision      | 99        | 0.8%    |
| Sophos SG           | 97        | 0.78%   |
| ASUS All            | 94        | 0.76%   |
| Lenovo IdeaPad      | 85        | 0.68%   |
| ASUS ROG            | 83        | 0.67%   |
| ASUS TUF            | 70        | 0.56%   |
| HP t620             | 68        | 0.55%   |
| HP Pavilion         | 63        | 0.51%   |
| HP t730             | 59        | 0.48%   |
| MW GMLK-2           | 56        | 0.45%   |
| HP EliteBook        | 56        | 0.45%   |
| Deciso Netboard     | 48        | 0.39%   |
| Sophos XG           | 47        | 0.38%   |
| Dell Wyse           | 46        | 0.37%   |
| Toshiba Satellite   | 42        | 0.34%   |
| Fujitsu ESPRIMO     | 39        | 0.31%   |
| Dell XPS            | 39        | 0.31%   |
| HP ProBook          | 38        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 1345      | 10.83%  |
| 2020    | 1071      | 8.63%   |
| 2019    | 1068      | 8.6%    |
| 2022    | 1040      | 8.38%   |
| 2021    | 1030      | 8.3%    |
| 2016    | 979       | 7.88%   |
| 2014    | 906       | 7.3%    |
| 2013    | 722       | 5.81%   |
| 2017    | 665       | 5.36%   |
| 2012    | 642       | 5.17%   |
| 2011    | 609       | 4.9%    |
| 2015    | 607       | 4.89%   |
| 2010    | 423       | 3.41%   |
| 2023    | 360       | 2.9%    |
| 2009    | 298       | 2.4%    |
| 2008    | 235       | 1.89%   |
| Unknown | 207       | 1.67%   |
| 2007    | 112       | 0.9%    |
| 2006    | 55        | 0.44%   |
| 2005    | 15        | 0.12%   |
| 2004    | 12        | 0.1%    |
| 2003    | 8         | 0.06%   |
| 2002    | 5         | 0.04%   |
| 2001    | 3         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 7532      | 60.66%  |
| Notebook       | 2752      | 22.16%  |
| Server         | 887       | 7.14%   |
| Mini pc        | 841       | 6.77%   |
| Firewall       | 206       | 1.66%   |
| System on chip | 71        | 0.57%   |
| All in one     | 66        | 0.53%   |
| Convertible    | 53        | 0.43%   |
| Tablet         | 9         | 0.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 11869     | 95.58%  |
| Yes  | 549       | 4.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 4481      | 35.33%  |
| 16.01-24.0      | 2899      | 22.85%  |
| 4.01-8.0        | 2580      | 20.34%  |
| 32.01-64.0      | 1160      | 9.14%   |
| 64.01-256.0     | 518       | 4.08%   |
| 2.01-3.0        | 454       | 3.58%   |
| 3.01-4.0        | 187       | 1.47%   |
| 24.01-32.0      | 169       | 1.33%   |
| 0.51-1.0        | 98        | 0.77%   |
| 1.01-2.0        | 67        | 0.53%   |
| 0.01-0.5        | 38        | 0.3%    |
| More than 256.0 | 31        | 0.24%   |
| Unknown         | 2         | 0.02%   |
| 0               | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 0.01-0.5        | 6421      | 49.9%   |
| 0.51-1.0        | 3820      | 29.69%  |
| 1.01-2.0        | 1451      | 11.28%  |
| 2.01-3.0        | 354       | 2.75%   |
| 4.01-8.0        | 222       | 1.73%   |
| 3.01-4.0        | 162       | 1.26%   |
| 8.01-16.0       | 107       | 0.83%   |
| Unknown         | 96        | 0.75%   |
| 0               | 75        | 0.58%   |
| 16.01-24.0      | 49        | 0.38%   |
| 24.01-32.0      | 47        | 0.37%   |
| 32.01-64.0      | 39        | 0.3%    |
| 64.01-256.0     | 24        | 0.19%   |
| More than 256.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 8621      | 67.25%  |
| 2      | 1798      | 14.03%  |
| 0      | 1201      | 9.37%   |
| 3      | 509       | 3.97%   |
| 4      | 275       | 2.15%   |
| 5      | 136       | 1.06%   |
| 6      | 88        | 0.69%   |
| 7      | 48        | 0.37%   |
| 8      | 29        | 0.23%   |
| 10     | 18        | 0.14%   |
| 14     | 16        | 0.12%   |
| 9      | 15        | 0.12%   |
| 12     | 14        | 0.11%   |
| 11     | 10        | 0.08%   |
| 17     | 6         | 0.05%   |
| 25     | 4         | 0.03%   |
| 13     | 4         | 0.03%   |
| 18     | 3         | 0.02%   |
| 16     | 3         | 0.02%   |
| 15     | 3         | 0.02%   |
| 58     | 2         | 0.02%   |
| 40     | 2         | 0.02%   |
| 24     | 2         | 0.02%   |
| 23     | 2         | 0.02%   |
| 21     | 2         | 0.02%   |
| 19     | 2         | 0.02%   |
| 63     | 1         | 0.01%   |
| 30     | 1         | 0.01%   |
| 28     | 1         | 0.01%   |
| 27     | 1         | 0.01%   |
| 26     | 1         | 0.01%   |
| 22     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 10111     | 80.76%  |
| Yes       | 2409      | 19.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 11806     | 95.06%  |
| No        | 613       | 4.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 7805      | 62.33%  |
| Yes       | 4717      | 37.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 9273      | 74.1%   |
| Yes       | 3241      | 25.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 3193      | 25.6%   |
| Germany      | 2022      | 16.21%  |
| Russia       | 652       | 5.23%   |
| UK           | 502       | 4.02%   |
| France       | 502       | 4.02%   |
| Canada       | 485       | 3.89%   |
| Poland       | 331       | 2.65%   |
| Netherlands  | 326       | 2.61%   |
| Brazil       | 311       | 2.49%   |
| Australia    | 305       | 2.45%   |
| Italy        | 259       | 2.08%   |
| Switzerland  | 230       | 1.84%   |
| Austria      | 207       | 1.66%   |
| Spain        | 206       | 1.65%   |
| China        | 195       | 1.56%   |
| Sweden       | 191       | 1.53%   |
| Romania      | 113       | 0.91%   |
| Czechia      | 112       | 0.9%    |
| Belgium      | 109       | 0.87%   |
| Finland      | 107       | 0.86%   |
| Norway       | 105       | 0.84%   |
| Ukraine      | 103       | 0.83%   |
| Indonesia    | 103       | 0.83%   |
| India        | 98        | 0.79%   |
| Japan        | 90        | 0.72%   |
| Taiwan       | 87        | 0.7%    |
| Hungary      | 87        | 0.7%    |
| Portugal     | 78        | 0.63%   |
| Denmark      | 76        | 0.61%   |
| South Korea  | 71        | 0.57%   |
| Mexico       | 71        | 0.57%   |
| New Zealand  | 64        | 0.51%   |
| Bulgaria     | 63        | 0.51%   |
| Argentina    | 57        | 0.46%   |
| South Africa | 55        | 0.44%   |
| Turkey       | 48        | 0.38%   |
| Greece       | 46        | 0.37%   |
| Singapore    | 36        | 0.29%   |
| Thailand     | 35        | 0.28%   |
| Slovakia     | 34        | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 204       | 1.47%   |
| Berlin            | 179       | 1.29%   |
| Vienna            | 113       | 0.81%   |
| Paris             | 106       | 0.76%   |
| Sydney            | 93        | 0.67%   |
| St Petersburg     | 85        | 0.61%   |
| Munich            | 81        | 0.58%   |
| Hamburg           | 78        | 0.56%   |
| London            | 75        | 0.54%   |
| Zurich            | 63        | 0.45%   |
| Montreal          | 63        | 0.45%   |
| Amsterdam         | 62        | 0.45%   |
| Melbourne         | 56        | 0.4%    |
| Frankfurt am Main | 56        | 0.4%    |
| Warsaw            | 55        | 0.4%    |
| Seattle           | 55        | 0.4%    |
| Cologne           | 51        | 0.37%   |
| New York          | 49        | 0.35%   |
| Brooklyn          | 49        | 0.35%   |
| Toronto           | 47        | 0.34%   |
| Denver            | 47        | 0.34%   |
| Chicago           | 47        | 0.34%   |
| Bucharest         | 47        | 0.34%   |
| Madrid            | 44        | 0.32%   |
| Jakarta           | 43        | 0.31%   |
| Milan             | 41        | 0.3%    |
| Helsinki          | 41        | 0.3%    |
| Perth             | 40        | 0.29%   |
| Los Angeles       | 39        | 0.28%   |
| Brisbane          | 39        | 0.28%   |
| Stuttgart         | 37        | 0.27%   |
| Kyiv              | 37        | 0.27%   |
| Portland          | 36        | 0.26%   |
| Oslo              | 36        | 0.26%   |
| Singapore         | 35        | 0.25%   |
| Prague            | 35        | 0.25%   |
| Sofia             | 34        | 0.25%   |
| Dallas            | 34        | 0.25%   |
| Calgary           | 34        | 0.25%   |
| Rome              | 32        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2234      | 3681   | 15.48%  |
| WDC                 | 1761      | 3846   | 12.21%  |
| Seagate             | 1367      | 2781   | 9.48%   |
| Kingston            | 1121      | 1576   | 7.77%   |
| Crucial             | 708       | 1078   | 4.91%   |
| Toshiba             | 637       | 1115   | 4.42%   |
| Intel               | 595       | 971    | 4.12%   |
| SanDisk             | 588       | 793    | 4.08%   |
| Transcend           | 582       | 881    | 4.03%   |
| Hitachi             | 345       | 620    | 2.39%   |
| A-DATA Technology   | 298       | 413    | 2.07%   |
| China               | 263       | 372    | 1.82%   |
| Hoodisk             | 245       | 366    | 1.7%    |
| HGST                | 204       | 548    | 1.41%   |
| Phison              | 199       | 281    | 1.38%   |
| SK hynix            | 186       | 251    | 1.29%   |
| Micron Technology   | 172       | 260    | 1.19%   |
| Hewlett-Packard     | 148       | 407    | 1.03%   |
| SPCC                | 146       | 225    | 1.01%   |
| NVMe                | 138       | 191    | 0.96%   |
| PNY                 | 117       | 185    | 0.81%   |
| FORESEE             | 113       | 163    | 0.78%   |
| OCZ                 | 105       | 142    | 0.73%   |
| Protectli           | 96        | 151    | 0.67%   |
| Apacer              | 92        | 120    | 0.64%   |
| Patriot             | 85        | 117    | 0.59%   |
| Apple               | 77        | 85     | 0.53%   |
| Silicon Motion      | 76        | 98     | 0.53%   |
| Corsair             | 76        | 133    | 0.53%   |
| Intenso             | 73        | 117    | 0.51%   |
| Innodisk            | 68        | 88     | 0.47%   |
| Dogfish             | 66        | 114    | 0.46%   |
| Gigabyte Technology | 61        | 83     | 0.42%   |
| KingSpec            | 59        | 75     | 0.41%   |
| LITEON              | 54        | 79     | 0.37%   |
| BIWIN               | 48        | 75     | 0.33%   |
| KIOXIA              | 47        | 56     | 0.33%   |
| Team                | 45        | 73     | 0.31%   |
| Fanxiang            | 44        | 62     | 0.3%    |
| LITEONIT            | 41        | 50     | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 174       | 1.11%   |
| Kingston SA400S37120G 120GB        | 136       | 0.87%   |
| Samsung SSD 850 EVO 250GB          | 129       | 0.82%   |
| Samsung SSD 860 EVO 500GB          | 93        | 0.59%   |
| Seagate ST500DM002-1BD142 500GB    | 84        | 0.54%   |
| Crucial CT240BX500SSD1 240GB       | 84        | 0.54%   |
| Samsung SSD 860 EVO 250GB          | 83        | 0.53%   |
| Phison SATA SSD 16GB               | 74        | 0.47%   |
| Kingston SUV500MS120G 120GB        | 73        | 0.46%   |
| Hoodisk SSD 32GB                   | 72        | 0.46%   |
| Samsung SSD 850 EVO 500GB          | 69        | 0.44%   |
| Kingston SV300S37A120G 120GB       | 68        | 0.43%   |
| Hoodisk SSD 64GB                   | 68        | 0.43%   |
| Hoodisk SSD 128GB                  | 67        | 0.43%   |
| Crucial CT500MX500SSD1 500GB       | 66        | 0.42%   |
| Crucial CT250MX500SSD1 250GB       | 66        | 0.42%   |
| Transcend TS128GMSA230S 128GB      | 60        | 0.38%   |
| Kingston SA400S37480G 480GB        | 60        | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB     | 56        | 0.36%   |
| Crucial CT120BX500SSD1 120GB       | 56        | 0.36%   |
| FORESEE 128GB SSD                  | 54        | 0.34%   |
| Seagate ST1000DM010-2EP102 1TB     | 53        | 0.34%   |
| Samsung SSD 840 EVO 250GB          | 52        | 0.33%   |
| Samsung SSD 970 EVO Plus 1TB       | 51        | 0.32%   |
| HP RAID 1(1+0) 304GB               | 50        | 0.32%   |
| China SATA SSD 16GB                | 50        | 0.32%   |
| Seagate ST1000LM035-1RK172 1TB     | 49        | 0.31%   |
| Toshiba DT01ACA100 1TB             | 48        | 0.31%   |
| Samsung SSD 860 EVO 1TB            | 48        | 0.31%   |
| Kingston SKC600MS256G 256GB        | 48        | 0.31%   |
| WDC WDS240G2G0A-00JH30 240GB       | 46        | 0.29%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 46        | 0.29%   |
| Toshiba MQ01ABD100 1TB             | 44        | 0.28%   |
| Samsung SSD 840 EVO 120GB          | 44        | 0.28%   |
| Samsung SSD 870 EVO 250GB          | 43        | 0.27%   |
| PNY CS900 120GB SSD                | 43        | 0.27%   |
| A-DATA SU650 120GB                 | 42        | 0.27%   |
| Samsung SSD 970 EVO Plus 250GB     | 41        | 0.26%   |
| Samsung SSD 850 EVO 120GB          | 41        | 0.26%   |
| Crucial CT1000MX500SSD1 1TB        | 40        | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                                 | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| WDC                                    | 1331      | 3083   | 30.98%  |
| Seagate                                | 1326      | 2703   | 30.87%  |
| Toshiba                                | 482       | 879    | 11.22%  |
| Hitachi                                | 342       | 612    | 7.96%   |
| HGST                                   | 203       | 543    | 4.73%   |
| Samsung Electronics                    | 182       | 260    | 4.24%   |
| Hewlett-Packard                        | 107       | 330    | 2.49%   |
| NVMe                                   | 88        | 121    | 2.05%   |
| Maxtor                                 | 40        | 47     | 0.93%   |
| Fujitsu                                | 39        | 50     | 0.91%   |
| Apple                                  | 29        | 32     | 0.68%   |
| OPENBSD                                | 16        | 27     | 0.37%   |
| Dell                                   | 13        | 68     | 0.3%    |
| HPE                                    | 9         | 38     | 0.21%   |
| USB                                    | 5         | 5      | 0.12%   |
| Lexar                                  | 5         | 6      | 0.12%   |
| Jetflash                               | 5         | 5      | 0.12%   |
| HPT                                    | 5         | 44     | 0.12%   |
| Generic                                | 5         | 5      | 0.12%   |
| China                                  | 4         | 4      | 0.09%   |
| Adaptec                                | 4         | 14     | 0.09%   |
| NETAPP                                 | 3         | 6      | 0.07%   |
| LSILOGIC                               | 3         | 6      | 0.07%   |
| LSI                                    | 3         | 9      | 0.07%   |
| IBM/Hitachi                            | 3         | 3      | 0.07%   |
| WD MediaMax                            | 2         | 6      | 0.05%   |
| StoreJet                               | 2         | 2      | 0.05%   |
| QUANTUM                                | 2         | 3      | 0.05%   |
| Product:              USB Flash Memory | 2         | 2      | 0.05%   |
| Multiple                               | 2         | 2      | 0.05%   |
| MaxDigital                             | 2         | 2      | 0.05%   |
| Lenovo                                 | 2         | 4      | 0.05%   |
| IBM                                    | 2         | 2      | 0.05%   |
| General                                | 2         | 2      | 0.05%   |
| Cisco                                  | 2         | 4      | 0.05%   |
| ASMT                                   | 2         | 2      | 0.05%   |
| Areca                                  | 2         | 3      | 0.05%   |
| Verbatim                               | 1         | 1      | 0.02%   |
| UFD 2.0                                | 1         | 1      | 0.02%   |
| SYNOLOGY                               | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1422      | 2335   | 17.73%  |
| Kingston            | 969       | 1372   | 12.08%  |
| SanDisk             | 584       | 785    | 7.28%   |
| Crucial             | 582       | 887    | 7.26%   |
| Transcend           | 523       | 806    | 6.52%   |
| Intel               | 454       | 783    | 5.66%   |
| WDC                 | 271       | 406    | 3.38%   |
| China               | 259       | 368    | 3.23%   |
| A-DATA Technology   | 244       | 330    | 3.04%   |
| Hoodisk             | 243       | 364    | 3.03%   |
| Micron Technology   | 125       | 193    | 1.56%   |
| Phison              | 121       | 161    | 1.51%   |
| SPCC                | 115       | 180    | 1.43%   |
| PNY                 | 106       | 170    | 1.32%   |
| OCZ                 | 105       | 142    | 1.31%   |
| FORESEE             | 101       | 150    | 1.26%   |
| Protectli           | 96        | 151    | 1.2%    |
| Toshiba             | 90        | 129    | 1.12%   |
| SK hynix            | 90        | 119    | 1.12%   |
| Apacer              | 90        | 118    | 1.12%   |
| Intenso             | 70        | 114    | 0.87%   |
| Innodisk            | 68        | 88     | 0.85%   |
| Patriot             | 66        | 95     | 0.82%   |
| Dogfish             | 66        | 114    | 0.82%   |
| KingSpec            | 59        | 75     | 0.74%   |
| Corsair             | 56        | 79     | 0.7%    |
| LITEON              | 50        | 74     | 0.62%   |
| NVMe                | 47        | 56     | 0.59%   |
| Apple               | 47        | 52     | 0.59%   |
| BIWIN               | 42        | 69     | 0.52%   |
| LITEONIT            | 41        | 50     | 0.51%   |
| Gigabyte Technology | 34        | 49     | 0.42%   |
| GOODRAM             | 32        | 46     | 0.4%    |
| Plextor             | 30        | 39     | 0.37%   |
| Seagate             | 27        | 54     | 0.34%   |
| Hewlett-Packard     | 26        | 39     | 0.32%   |
| Lexar               | 25        | 34     | 0.31%   |
| Kston               | 25        | 33     | 0.31%   |
| Team                | 24        | 46     | 0.3%    |
| ShiJi               | 22        | 33     | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 7283      | 12006  | 55.86%  |
| HDD  | 3574      | 8958   | 27.41%  |
| NVMe | 2180      | 3316   | 16.72%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 9774      | 20964  | 81.76%  |
| NVMe | 2180      | 3316   | 18.24%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 8382      | 13898  | 74.26%  |
| 0.51-1.0        | 1670      | 2961   | 14.8%   |
| 1.01-2.0        | 582       | 1353   | 5.16%   |
| 3.01-4.0        | 255       | 951    | 2.26%   |
| 4.01-10.0       | 200       | 1060   | 1.77%   |
| 2.01-3.0        | 141       | 474    | 1.25%   |
| 10.01-20.0      | 50        | 257    | 0.44%   |
| More than 100.0 | 3         | 3      | 0.03%   |
| 20.01-50.0      | 3         | 6      | 0.03%   |
| 0               | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 4954      | 38.2%   |
| 251-500        | 2146      | 16.55%  |
| 1-20           | 1942      | 14.97%  |
| 51-100         | 1340      | 10.33%  |
| 21-50          | 1137      | 8.77%   |
| 501-1000       | 949       | 7.32%   |
| 1001-2000      | 257       | 1.98%   |
| More than 3000 | 119       | 0.92%   |
| Unknown        | 73        | 0.56%   |
| 2001-3000      | 53        | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 11358     | 88.42%  |
| 21-50          | 747       | 5.82%   |
| 51-100         | 265       | 2.06%   |
| 101-250        | 191       | 1.49%   |
| 251-500        | 80        | 0.62%   |
| Unknown        | 73        | 0.57%   |
| 501-1000       | 57        | 0.44%   |
| More than 3000 | 31        | 0.24%   |
| 1001-2000      | 27        | 0.21%   |
| 2001-3000      | 14        | 0.11%   |
| 0              | 2         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 32        | 50     | 1.69%   |
| Kingston SV300S37A120G 120GB        | 20        | 25     | 1.05%   |
| HGST HTS725050A7E630 500GB          | 19        | 35     | 1%      |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 15        | 20     | 0.79%   |
| Toshiba MQ01ABD100 1TB              | 14        | 15     | 0.74%   |
| Seagate ST500LM021-1KJ152 500GB     | 14        | 14     | 0.74%   |
| Seagate ST500LT012-9WS142 500GB     | 13        | 19     | 0.69%   |
| Seagate ST3500418AS 500GB           | 12        | 21     | 0.63%   |
| Kingston SV300S37A60G 64GB          | 12        | 16     | 0.63%   |
| Kingston SMS200S3120G 120GB         | 12        | 13     | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB        | 11        | 18     | 0.58%   |
| Hitachi HTS541612J9SA00 120GB       | 11        | 12     | 0.58%   |
| Seagate ST9500420AS 500GB           | 10        | 14     | 0.53%   |
| Seagate ST9500325AS 500GB           | 10        | 15     | 0.53%   |
| Seagate ST500LT012-1DG142 500GB     | 10        | 11     | 0.53%   |
| Apacer 16GB SATA Flash Drive        | 10        | 15     | 0.53%   |
| WDC WD30EFRX-68EUZN0 3TB            | 9         | 26     | 0.47%   |
| Seagate ST9320325AS 320GB           | 9         | 9      | 0.47%   |
| Seagate ST3500413AS 500GB           | 9         | 23     | 0.47%   |
| Toshiba MQ01ABF050 500GB            | 8         | 10     | 0.42%   |
| Toshiba DT01ACA100 1TB              | 8         | 11     | 0.42%   |
| Samsung Electronics SSD 870 EVO 1TB | 8         | 12     | 0.42%   |
| Samsung Electronics HM160HI 160GB   | 8         | 9      | 0.42%   |
| Kingston SMS200S360G 64GB           | 8         | 9      | 0.42%   |
| Intel SSDSA2M080G2GC 80GB           | 8         | 9      | 0.42%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 7         | 7      | 0.37%   |
| Seagate ST320LT007-9ZV142 320GB     | 7         | 7      | 0.37%   |
| SanDisk SSD PLUS 240GB              | 7         | 8      | 0.37%   |
| Samsung Electronics HD501LJ 500GB   | 7         | 9      | 0.37%   |
| Kingston SA400S37240G 240GB         | 7         | 7      | 0.37%   |
| Intel SSDSC2BF180A4L 180GB          | 7         | 7      | 0.37%   |
| Intel SSDSA2M160G2GC 160GB          | 7         | 9      | 0.37%   |
| Crucial CT525MX300SSD1 528GB        | 7         | 11     | 0.37%   |
| Crucial CT275MX300SSD1 275GB        | 7         | 10     | 0.37%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 6         | 7      | 0.32%   |
| WDC WD40EFRX-68WT0N0 4TB            | 6         | 19     | 0.32%   |
| WDC WD20EFRX-68EUZN0 2TB            | 6         | 14     | 0.32%   |
| Toshiba MK3261GSYN 320GB            | 6         | 8      | 0.32%   |
| Seagate ST9320423AS 320GB           | 6         | 6      | 0.32%   |
| Seagate ST3160815AS 160GB           | 6         | 7      | 0.32%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 404       | 587    | 22.04%  |
| WDC                 | 329       | 506    | 17.95%  |
| Hitachi             | 148       | 192    | 8.07%   |
| Samsung Electronics | 144       | 209    | 7.86%   |
| Toshiba             | 133       | 189    | 7.26%   |
| Kingston            | 110       | 139    | 6%      |
| Intel               | 104       | 135    | 5.67%   |
| HGST                | 58        | 103    | 3.16%   |
| Crucial             | 56        | 89     | 3.06%   |
| SanDisk             | 47        | 67     | 2.56%   |
| A-DATA Technology   | 28        | 40     | 1.53%   |
| Micron Technology   | 23        | 31     | 1.25%   |
| SK hynix            | 20        | 26     | 1.09%   |
| OCZ                 | 20        | 26     | 1.09%   |
| Maxtor              | 18        | 23     | 0.98%   |
| Apacer              | 17        | 22     | 0.93%   |
| Corsair             | 14        | 19     | 0.76%   |
| China               | 14        | 15     | 0.76%   |
| Hewlett-Packard     | 9         | 15     | 0.49%   |
| Apple               | 9         | 9      | 0.49%   |
| SPCC                | 8         | 11     | 0.44%   |
| LITEON              | 8         | 9      | 0.44%   |
| Transcend           | 7         | 13     | 0.38%   |
| Patriot             | 7         | 8      | 0.38%   |
| Fujitsu             | 7         | 10     | 0.38%   |
| Dogfish             | 6         | 14     | 0.33%   |
| SSSTC               | 5         | 7      | 0.27%   |
| HP Phison           | 5         | 5      | 0.27%   |
| Plextor             | 4         | 4      | 0.22%   |
| Phison              | 4         | 4      | 0.22%   |
| KingSpec            | 4         | 4      | 0.22%   |
| VisionTek           | 3         | 7      | 0.16%   |
| KingDian            | 3         | 5      | 0.16%   |
| Intenso             | 3         | 3      | 0.16%   |
| BIWIN               | 3         | 5      | 0.16%   |
| SMI                 | 2         | 2      | 0.11%   |
| PNY                 | 2         | 2      | 0.11%   |
| MyDigitalSSD        | 2         | 4      | 0.11%   |
| IBM/Hitachi         | 2         | 2      | 0.11%   |
| HPE                 | 2         | 7      | 0.11%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 403       | 586    | 34.62%  |
| WDC                  | 311       | 479    | 26.72%  |
| Hitachi              | 148       | 192    | 12.71%  |
| Toshiba              | 123       | 172    | 10.57%  |
| Samsung Electronics  | 74        | 97     | 6.36%   |
| HGST                 | 57        | 102    | 4.9%    |
| Maxtor               | 18        | 23     | 1.55%   |
| Hewlett-Packard      | 7         | 12     | 0.6%    |
| Fujitsu              | 7         | 10     | 0.6%    |
| Apple                | 6         | 6      | 0.52%   |
| IBM/Hitachi          | 2         | 2      | 0.17%   |
| HPE                  | 2         | 7      | 0.17%   |
| China                | 2         | 2      | 0.17%   |
| WD MediaMax          | 1         | 3      | 0.09%   |
| InnoLite             | 1         | 1      | 0.09%   |
| ExcelStor Technology | 1         | 2      | 0.09%   |
| Cactus               | 1         | 1      | 0.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1098      | 1697   | 62.24%  |
| SSD  | 639       | 891    | 36.22%  |
| NVMe | 27        | 35     | 1.53%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| SanDisk pSSD 16GB                                | 5         | 5      | 8.33%   |
| Samsung Electronics MZYLN256HCHP-000L2 256GB     | 2         | 2      | 3.33%   |
| WDC WD7501AALS-00J7B0 752GB                      | 1         | 1      | 1.67%   |
| WDC WD6400AARS-00Y5B1 640GB                      | 1         | 2      | 1.67%   |
| WDC WD3200L 320GB                                | 1         | 1      | 1.67%   |
| WDC WD3200BPVT-16JJ5T0 320GB                     | 1         | 1      | 1.67%   |
| WDC WD3200AAJS-00YZCA0 320GB                     | 1         | 1      | 1.67%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 1      | 1.67%   |
| WDC WD1600BEVT-22ZCT0 160GB                      | 1         | 1      | 1.67%   |
| WDC WD10SPZX-00Z10T0 1TB                         | 1         | 1      | 1.67%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB             | 1         | 1      | 1.67%   |
| Transcend TS32GSSD370S 32GB                      | 1         | 2      | 1.67%   |
| Transcend TS128GMTE110S 128GB                    | 1         | 1      | 1.67%   |
| Toshiba MG05ACA800E 8TB                          | 1         | 1      | 1.67%   |
| Supermicro SSD 16GB                              | 1         | 1      | 1.67%   |
| SK hynix SC308 SATA 256GB                        | 1         | 1      | 1.67%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB          | 1         | 1      | 1.67%   |
| Seagate ST4000NM0025 4TB                         | 1         | 2      | 1.67%   |
| Seagate ST3500418AS 500GB                        | 1         | 2      | 1.67%   |
| Seagate ST3250310AS 250GB                        | 1         | 1      | 1.67%   |
| Seagate ST3160318AS 160GB                        | 1         | 1      | 1.67%   |
| SanDisk SD9SN8W-256G-1006 256GB                  | 1         | 1      | 1.67%   |
| Samsung Electronics SSD PM830 2.5-inch 7mm 256GB | 1         | 1      | 1.67%   |
| Samsung Electronics SSD 980 250GB                | 1         | 2      | 1.67%   |
| Samsung Electronics SSD 970 EVO Plus 500GB       | 1         | 1      | 1.67%   |
| Samsung Electronics SSD 960 EVO 250GB            | 1         | 1      | 1.67%   |
| Samsung Electronics PM981 NVMe 256GB             | 1         | 1      | 1.67%   |
| Samsung Electronics PM961 NVMe 256GB             | 1         | 1      | 1.67%   |
| Samsung Electronics MZVLW256HEHP-000H1 256GB     | 1         | 1      | 1.67%   |
| Samsung Electronics MZVLW256HEHP-00000 256GB     | 1         | 1      | 1.67%   |
| Samsung Electronics MZVLB256HBHQ-000H1 256GB     | 1         | 1      | 1.67%   |
| Samsung Electronics MZALQ256HBJD-00BL2 256GB     | 1         | 1      | 1.67%   |
| Samsung Electronics HM500JJ 500GB                | 1         | 1      | 1.67%   |
| Samsung Electronics HM250JI 250GB                | 1         | 1      | 1.67%   |
| Samsung Electronics HD204UI 2TB                  | 1         | 2      | 1.67%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 2      | 1.67%   |
| Micron Technology 1100_MTFDDAV256TBN 64GB        | 1         | 1      | 1.67%   |
| Maxtor 6E040L0 40GB                              | 1         | 1      | 1.67%   |
| Kingston SV300S37A60G 64GB                       | 1         | 1      | 1.67%   |
| Kingston SMS200S360G 64GB                        | 1         | 1      | 1.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 19     | 26.67%  |
| WDC                 | 9         | 10     | 15%     |
| SanDisk             | 6         | 6      | 10%     |
| Seagate             | 4         | 6      | 6.67%   |
| Kingston            | 4         | 5      | 6.67%   |
| Intel               | 4         | 5      | 6.67%   |
| Hitachi             | 3         | 16     | 5%      |
| Crucial             | 3         | 3      | 5%      |
| Transcend           | 2         | 3      | 3.33%   |
| SK hynix            | 2         | 2      | 3.33%   |
| Toshiba             | 1         | 1      | 1.67%   |
| Supermicro          | 1         | 1      | 1.67%   |
| Micron Technology   | 1         | 1      | 1.67%   |
| Maxtor              | 1         | 1      | 1.67%   |
| HPE                 | 1         | 1      | 1.67%   |
| Hoodisk             | 1         | 1      | 1.67%   |
| HGST                | 1         | 1      | 1.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 9963      | 20688  | 81.7%   |
| Malfunc  | 1724      | 2623   | 14.14%  |
| Detected | 447       | 887    | 3.67%   |
| Failed   | 60        | 82     | 0.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 9404      | 61.95%  |
| AMD                                     | 1967      | 12.96%  |
| Samsung Electronics                     | 837       | 5.51%   |
| Broadcom / LSI                          | 417       | 2.75%   |
| SanDisk                                 | 350       | 2.31%   |
| ASMedia Technology                      | 214       | 1.41%   |
| Silicon Motion                          | 209       | 1.38%   |
| Phison Electronics                      | 186       | 1.23%   |
| Kingston Technology Company             | 170       | 1.12%   |
| Marvell Technology Group                | 144       | 0.95%   |
| Micron/Crucial Technology               | 136       | 0.9%    |
| Nvidia                                  | 113       | 0.74%   |
| SK hynix                                | 108       | 0.71%   |
| Hewlett-Packard                         | 94        | 0.62%   |
| JMicron Technology                      | 78        | 0.51%   |
| Toshiba                                 | 72        | 0.47%   |
| MAXIO Technology (Hangzhou)             | 72        | 0.47%   |
| KIOXIA                                  | 60        | 0.4%    |
| Micron Technology                       | 58        | 0.38%   |
| ADATA Technology                        | 52        | 0.34%   |
| Transcend                               | 48        | 0.32%   |
| Chelsio Communications                  | 40        | 0.26%   |
| Realtek Semiconductor                   | 38        | 0.25%   |
| Adaptec                                 | 34        | 0.22%   |
| Shenzhen Longsys Electronics            | 31        | 0.2%    |
| VIA Technologies                        | 30        | 0.2%    |
| Silicon Image                           | 24        | 0.16%   |
| Seagate Technology                      | 21        | 0.14%   |
| Solid State Storage Technology          | 16        | 0.11%   |
| Silicon Integrated Systems [SiS]        | 14        | 0.09%   |
| Hosin Global Electronics                | 13        | 0.09%   |
| Lite-On Technology                      | 11        | 0.07%   |
| Union Memory (Shenzhen)                 | 10        | 0.07%   |
| Biwin Storage Technology                | 10        | 0.07%   |
| Lenovo                                  | 9         | 0.06%   |
| Shenzhen Unionmemory Information System | 8         | 0.05%   |
| Integrated Technology Express           | 8         | 0.05%   |
| Areca Technology                        | 8         | 0.05%   |
| Dell                                    | 7         | 0.05%   |
| HighPoint Technologies                  | 6         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 1304      | 7.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 817       | 4.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 621       | 3.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 530       | 3.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 478       | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 436       | 2.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 409       | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 403       | 2.34%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 391       | 2.27%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 326       | 1.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 324       | 1.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 287       | 1.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 271       | 1.58%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 256       | 1.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 250       | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 244       | 1.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 241       | 1.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 240       | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 219       | 1.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 207       | 1.2%    |
| AMD 400 Series Chipset SATA Controller                                           | 194       | 1.13%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 192       | 1.12%   |
| Intel SATA Controller [RAID mode]                                                | 192       | 1.12%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 190       | 1.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 178       | 1.04%   |
| AMD FCH SATA Controller [IDE mode]                                               | 165       | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 160       | 0.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 146       | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 144       | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 139       | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                            | 135       | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 134       | 0.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 121       | 0.7%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 118       | 0.69%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 116       | 0.67%   |
| AMD 500 Series Chipset SATA Controller                                           | 116       | 0.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 111       | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 109       | 0.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 107       | 0.62%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 105       | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 10054     | 65.6%   |
| NVMe | 2520      | 16.44%  |
| IDE  | 1618      | 10.56%  |
| RAID | 817       | 5.33%   |
| SAS  | 201       | 1.31%   |
| SCSI | 117       | 0.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 10038     | 80.63%  |
| AMD                | 2213      | 17.78%  |
| ARM                | 136       | 1.09%   |
| Unknown            | 34        | 0.27%   |
| VIA                | 5         | 0.04%   |
| PowerPC            | 4         | 0.03%   |
| Rockchip           | 3         | 0.02%   |
| IBM                | 2         | 0.02%   |
| Broadcom           | 2         | 0.02%   |
| 7447A              | 2         | 0.02%   |
| 11th               | 2         | 0.02%   |
| SUNW,UltraAX-i2    | 1         | 0.01%   |
| Sun                | 1         | 0.01%   |
| Research           | 1         | 0.01%   |
| NXP                | 1         | 0.01%   |
| Motorola           | 1         | 0.01%   |
| i                  | 1         | 0.01%   |
| Bochs              | 1         | 0.01%   |
| Baikal Electronics | 1         | 0.01%   |
| 123456789ABC       | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                         | 324       | 2.58%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 300       | 2.38%   |
| Intel Celeron N5105 @ 2.00GHz            | 267       | 2.12%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 209       | 1.66%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 187       | 1.49%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 116       | 0.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 108       | 0.86%   |
| Intel N100                               | 101       | 0.8%    |
| Intel Core i5-8250U CPU @ 1.60GHz        | 88        | 0.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz         | 88        | 0.7%    |
| Intel Core i5-4570 CPU @ 3.20GHz         | 76        | 0.6%    |
| Intel Celeron CPU J3455 @ 1.50GHz        | 75        | 0.6%    |
| Intel Core i5-2520M CPU @ 2.50GHz        | 69        | 0.55%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 67        | 0.53%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 67        | 0.53%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 66        | 0.52%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 66        | 0.52%   |
| Intel Atom CPU D525 @ 1.80GHz            | 63        | 0.5%    |
| AMD RX-427BB with AMD Radeon R7 Graphics | 62        | 0.49%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 61        | 0.48%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 60        | 0.48%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 59        | 0.47%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 59        | 0.47%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 58        | 0.46%   |
| Intel Pentium Silver N6005 @ 2.00GHz     | 55        | 0.44%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 55        | 0.44%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 55        | 0.44%   |
| Intel Core 2 Duo                         | 55        | 0.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 54        | 0.43%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 54        | 0.43%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 53        | 0.42%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 51        | 0.41%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 50        | 0.4%    |
| Intel Core i5-10210U CPU @ 1.60GHz       | 49        | 0.39%   |
| ARM Cortex-A72 r0p3                      | 49        | 0.39%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 47        | 0.37%   |
| Intel CPU Version                        | 46        | 0.37%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 45        | 0.36%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 45        | 0.36%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 44        | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2380      | 19%     |
| Intel Celeron           | 1975      | 15.77%  |
| Intel Core i7           | 1260      | 10.06%  |
| Intel Xeon              | 1249      | 9.97%   |
| Intel Core i3           | 939       | 7.5%    |
| Other                   | 645       | 5.15%   |
| Intel Atom              | 559       | 4.46%   |
| AMD GX                  | 550       | 4.39%   |
| Intel Pentium           | 331       | 2.64%   |
| Intel Core 2 Duo        | 313       | 2.5%    |
| AMD Ryzen 5             | 287       | 2.29%   |
| AMD Ryzen 7             | 281       | 2.24%   |
| Intel Pentium Silver    | 138       | 1.1%    |
| ARM Cortex              | 126       | 1.01%   |
| AMD FX                  | 97        | 0.77%   |
| AMD Ryzen 3             | 86        | 0.69%   |
| Intel Core 2 Quad       | 81        | 0.65%   |
| AMD Ryzen 9             | 76        | 0.61%   |
| Intel Pentium Dual-Core | 72        | 0.57%   |
| AMD EPYC                | 72        | 0.57%   |
| AMD G                   | 71        | 0.57%   |
| AMD Ryzen Embedded      | 50        | 0.4%    |
| AMD Athlon              | 46        | 0.37%   |
| Intel Core 2            | 41        | 0.33%   |
| AMD A10                 | 38        | 0.3%    |
| AMD Ryzen 5 PRO         | 37        | 0.3%    |
| Intel Pentium Gold      | 36        | 0.29%   |
| Intel Genuine           | 34        | 0.27%   |
| AMD Phenom II X4        | 34        | 0.27%   |
| AMD A4                  | 32        | 0.26%   |
| Intel Xeon Silver       | 31        | 0.25%   |
| Intel Core i9           | 31        | 0.25%   |
| AMD A6                  | 31        | 0.25%   |
| AMD A8                  | 30        | 0.24%   |
| Intel Pentium 4         | 29        | 0.23%   |
| AMD Ryzen 7 PRO         | 26        | 0.21%   |
| AMD E                   | 26        | 0.21%   |
| Intel Pentium Dual      | 24        | 0.19%   |
| Intel Pentium M         | 23        | 0.18%   |
| AMD Opteron             | 23        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 5930      | 47.34%  |
| 2       | 3613      | 28.84%  |
| 8       | 681       | 5.44%   |
| Unknown | 632       | 5.05%   |
| 6       | 568       | 4.53%   |
| 16      | 358       | 2.86%   |
| 12      | 346       | 2.76%   |
| 1       | 171       | 1.37%   |
| 24      | 62        | 0.49%   |
| 32      | 47        | 0.38%   |
| 10      | 45        | 0.36%   |
| 20      | 20        | 0.16%   |
| 64      | 11        | 0.09%   |
| 3       | 9         | 0.07%   |
| 14      | 7         | 0.06%   |
| 48      | 6         | 0.05%   |
| 36      | 5         | 0.04%   |
| 28      | 5         | 0.04%   |
| 128     | 2         | 0.02%   |
| 40      | 2         | 0.02%   |
| 22      | 2         | 0.02%   |
| 18      | 2         | 0.02%   |
| 5       | 2         | 0.02%   |
| 11      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 11727     | 94.22%  |
| 2       | 418       | 3.36%   |
| Unknown | 294       | 2.36%   |
| 4       | 5         | 0.04%   |
| 8       | 2         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6917      | 55.41%  |
| 2       | 4863      | 38.95%  |
| Unknown | 703       | 5.63%   |
| 4       | 1         | 0.01%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 1548      | 12.37%  |
| Haswell         | 1262      | 10.08%  |
| Unknown         | 1068      | 8.53%   |
| Silvermont      | 934       | 7.46%   |
| IvyBridge       | 876       | 7%      |
| Skylake         | 785       | 6.27%   |
| SandyBridge     | 737       | 5.89%   |
| Goldmont plus   | 539       | 4.31%   |
| Penryn          | 453       | 3.62%   |
| Puma            | 421       | 3.36%   |
| Broadwell       | 400       | 3.2%    |
| Goldmont        | 345       | 2.76%   |
| Westmere        | 305       | 2.44%   |
| Zen 2           | 249       | 1.99%   |
| Core            | 248       | 1.98%   |
| Zen             | 241       | 1.93%   |
| Bonnell         | 232       | 1.85%   |
| Zen+            | 216       | 1.73%   |
| Jaguar          | 206       | 1.65%   |
| CometLake       | 205       | 1.64%   |
| Zen 3           | 200       | 1.6%    |
| Nehalem         | 170       | 1.36%   |
| Piledriver      | 135       | 1.08%   |
| TigerLake       | 132       | 1.05%   |
| K10             | 127       | 1.01%   |
| Bobcat          | 119       | 0.95%   |
| Steamroller     | 83        | 0.66%   |
| Excavator       | 60        | 0.48%   |
| NetBurst        | 52        | 0.42%   |
| K8 Hammer       | 46        | 0.37%   |
| P6              | 44        | 0.35%   |
| IceLake         | 34        | 0.27%   |
| Bulldozer       | 20        | 0.16%   |
| K10 Llano       | 16        | 0.13%   |
| Geode           | 6         | 0.05%   |
| K8 & K10 hybrid | 3         | 0.02%   |
| K6              | 2         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 7721      | 62.57%  |
| AMD                                          | 1868      | 15.14%  |
| Nvidia                                       | 1479      | 11.99%  |
| Matrox Electronics Systems                   | 635       | 5.15%   |
| ASPEED Technology                            | 591       | 4.79%   |
| XGI Technology (eXtreme Graphics Innovation) | 10        | 0.08%   |
| Silicon Integrated Systems [SiS]             | 10        | 0.08%   |
| VIA Technologies                             | 8         | 0.06%   |
| S3 Graphics                                  | 5         | 0.04%   |
| Silicon Motion                               | 3         | 0.02%   |
| Cirrus Logic                                 | 2         | 0.02%   |
| Tseng Labs                                   | 1         | 0.01%   |
| Trident Microsystems                         | 1         | 0.01%   |
| Red Hat                                      | 1         | 0.01%   |
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
| ASPEED Technology ASPEED Graphics Family                                                 | 591       | 4.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 485       | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 483       | 3.84%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 463       | 3.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 420       | 3.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 399       | 3.17%   |
| Intel JasperLake [UHD Graphics]                                                          | 379       | 3.01%   |
| Intel HD Graphics 530                                                                    | 343       | 2.73%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 298       | 2.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 273       | 2.17%   |
| Intel HD Graphics 620                                                                    | 265       | 2.11%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 262       | 2.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 251       | 1.99%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 225       | 1.79%   |
| Intel HD Graphics 500                                                                    | 215       | 1.71%   |
| Intel UHD Graphics 620                                                                   | 208       | 1.65%   |
| Intel HD Graphics 5500                                                                   | 195       | 1.55%   |
| Intel HD Graphics 630                                                                    | 185       | 1.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 169       | 1.34%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 143       | 1.14%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 135       | 1.07%   |
| Matrox Electronics Systems G200eR2                                                       | 130       | 1.03%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 123       | 0.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 123       | 0.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 118       | 0.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 116       | 0.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 113       | 0.9%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 111       | 0.88%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 104       | 0.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 101       | 0.8%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 100       | 0.79%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 99        | 0.79%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 97        | 0.77%   |
| AMD ES1000                                                                               | 93        | 0.74%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 91        | 0.72%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 88        | 0.7%    |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 87        | 0.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 87        | 0.69%   |
| Matrox Electronics Systems MGA G200EH                                                    | 86        | 0.68%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 77        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 6742      | 53.88%  |
| 1 x AMD                                  | 1652      | 13.2%   |
| 1 x Nvidia                               | 999       | 7.98%   |
| Other                                    | 803       | 6.42%   |
| 1 x Matrox                               | 629       | 5.03%   |
| 1 x ASPEED                               | 543       | 4.34%   |
| 2 x Intel                                | 413       | 3.3%    |
| Intel + Nvidia                           | 411       | 3.28%   |
| Intel + AMD                              | 124       | 0.99%   |
| 2 x AMD                                  | 44        | 0.35%   |
| AMD + Nvidia                             | 43        | 0.34%   |
| Intel + ASPEED                           | 30        | 0.24%   |
| Nvidia + ASPEED                          | 14        | 0.11%   |
| 1 x XGI                                  | 10        | 0.08%   |
| 1 x SiS                                  | 10        | 0.08%   |
| 2 x Nvidia                               | 9         | 0.07%   |
| 1 x VIA                                  | 8         | 0.06%   |
| 1 x S3 Graphics                          | 5         | 0.04%   |
| AMD + ASPEED                             | 5         | 0.04%   |
| 1 x Silicon Motion                       | 3         | 0.02%   |
| Intel + Matrox                           | 2         | 0.02%   |
| Intel + AMD + 1 x Nvidia                 | 2         | 0.02%   |
| 1 x Cirrus Logic                         | 2         | 0.02%   |
| AMD + Matrox                             | 2         | 0.02%   |
| 2 x Intel + 1 x Nvidia                   | 1         | 0.01%   |
| 1 x Tseng Labs                           | 1         | 0.01%   |
| 1 x Trident Microsystems                 | 1         | 0.01%   |
| 1 x Red Hat                              | 1         | 0.01%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.01%   |
| Nvidia + Matrox                          | 1         | 0.01%   |
| Nvidia + Huawei Technologies             | 1         | 0.01%   |
| Intel + 2 x AMD                          | 1         | 0.01%   |
| 1 x 3DLabs                               | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 10785     | 86.27%  |
| Unknown     | 976       | 7.81%   |
| Proprietary | 741       | 5.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 11245     | 89.67%  |
| 1.01-2.0   | 317       | 2.53%   |
| 0.01-0.5   | 294       | 2.34%   |
| 0.51-1.0   | 210       | 1.67%   |
| 3.01-4.0   | 196       | 1.56%   |
| 7.01-8.0   | 142       | 1.13%   |
| 5.01-6.0   | 80        | 0.64%   |
| 8.01-16.0  | 29        | 0.23%   |
| 2.01-3.0   | 27        | 0.22%   |
| 4.01-5.0   | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 394       | 11.05%  |
| Samsung Electronics     | 393       | 11.02%  |
| LG Display              | 365       | 10.23%  |
| Chimei Innolux          | 255       | 7.15%   |
| Dell                    | 245       | 6.87%   |
| BOE                     | 237       | 6.64%   |
| Goldstar                | 190       | 5.33%   |
| Lenovo                  | 146       | 4.09%   |
| Acer                    | 120       | 3.36%   |
| Hewlett-Packard         | 114       | 3.2%    |
| BenQ                    | 94        | 2.64%   |
| Apple                   | 93        | 2.61%   |
| Philips                 | 88        | 2.47%   |
| AOC                     | 84        | 2.35%   |
| Ancor Communications    | 70        | 1.96%   |
| ViewSonic               | 49        | 1.37%   |
| Sharp                   | 49        | 1.37%   |
| Iiyama                  | 46        | 1.29%   |
| Chi Mei Optoelectronics | 42        | 1.18%   |
| LG Electronics          | 30        | 0.84%   |
| InfoVision              | 30        | 0.84%   |
| ASUSTek Computer        | 29        | 0.81%   |
| Sony                    | 22        | 0.62%   |
| NEC Computers           | 22        | 0.62%   |
| Fujitsu Siemens         | 19        | 0.53%   |
| Eizo                    | 19        | 0.53%   |
| PANDA                   | 17        | 0.48%   |
| LG Philips              | 16        | 0.45%   |
| HannStar                | 16        | 0.45%   |
| MSI                     | 14        | 0.39%   |
| Toshiba                 | 12        | 0.34%   |
| Idek Iiyama             | 12        | 0.34%   |
| Unknown                 | 12        | 0.34%   |
| CSO                     | 11        | 0.31%   |
| Vizio                   | 10        | 0.28%   |
| Panasonic               | 10        | 0.28%   |
| Unknown                 | 9         | 0.25%   |
| LGD                     | 9         | 0.25%   |
| Sceptre Tech            | 8         | 0.22%   |
| Lenovo Group Limited    | 7         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 26        | 0.71%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 17        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 13        | 0.35%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                | 12        | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 12        | 0.33%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 12        | 0.33%   |
| Unknown                                                              | 12        | 0.33%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 11        | 0.3%    |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch              | 10        | 0.27%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch              | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 10        | 0.27%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 9         | 0.24%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 9         | 0.24%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 9         | 0.24%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch              | 9         | 0.24%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch              | 9         | 0.24%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 9         | 0.24%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 9         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 9         | 0.24%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch        | 9         | 0.24%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 9         | 0.24%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 9         | 0.24%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 9         | 0.24%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 9         | 0.24%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch | 8         | 0.22%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch          | 8         | 0.22%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 8         | 0.22%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 8         | 0.22%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 8         | 0.22%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch            | 8         | 0.22%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 8         | 0.22%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 7         | 0.19%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 7         | 0.19%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch              | 7         | 0.19%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 7         | 0.19%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch      | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch     | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch     | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch      | 7         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1404      | 40.09%  |
| 1366x768 (WXGA)    | 708       | 20.22%  |
| 3840x2160 (4K)     | 184       | 5.25%   |
| 2560x1440 (QHD)    | 181       | 5.17%   |
| 1600x900 (HD+)     | 154       | 4.4%    |
| 1280x1024 (SXGA)   | 131       | 3.74%   |
| 1280x800 (WXGA)    | 115       | 3.28%   |
| 1920x1200 (WUXGA)  | 104       | 2.97%   |
| 1440x900 (WXGA+)   | 92        | 2.63%   |
| 1680x1050 (WSXGA+) | 85        | 2.43%   |
| 2560x1080          | 39        | 1.11%   |
| Unknown            | 38        | 1.09%   |
| 1024x600           | 35        | 1%      |
| 3440x1440          | 33        | 0.94%   |
| 2560x1600          | 20        | 0.57%   |
| 1024x768 (XGA)     | 20        | 0.57%   |
| 1360x768           | 16        | 0.46%   |
| 3840x1080          | 13        | 0.37%   |
| 3200x1800 (QHD+)   | 13        | 0.37%   |
| 1600x1200          | 12        | 0.34%   |
| 1920x540           | 11        | 0.31%   |
| 2880x1800          | 9         | 0.26%   |
| 2256x1504          | 8         | 0.23%   |
| 3840x1600          | 4         | 0.11%   |
| 2160x1440          | 4         | 0.11%   |
| 1400x1050          | 4         | 0.11%   |
| 5760x2160          | 3         | 0.09%   |
| 3840x1200          | 3         | 0.09%   |
| 3000x2000          | 3         | 0.09%   |
| 2736x1824          | 3         | 0.09%   |
| 2048x1152          | 3         | 0.09%   |
| 5760x1080          | 2         | 0.06%   |
| 3840x2400          | 2         | 0.06%   |
| 3520x1080          | 2         | 0.06%   |
| 1920x1280          | 2         | 0.06%   |
| 1280x854           | 2         | 0.06%   |
| 1280x720 (HD)      | 2         | 0.06%   |
| 9600x2160          | 1         | 0.03%   |
| 8960x1440          | 1         | 0.03%   |
| 7860x2400          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 679       | 19.08%  |
| 13      | 641       | 18.02%  |
| 24      | 294       | 8.26%   |
| 27      | 257       | 7.22%   |
| Unknown | 224       | 6.3%    |
| 21      | 219       | 6.16%   |
| 12      | 183       | 5.14%   |
| 23      | 181       | 5.09%   |
| 19      | 152       | 4.27%   |
| 17      | 140       | 3.93%   |
| 14      | 82        | 2.3%    |
| 11      | 76        | 2.14%   |
| 31      | 73        | 2.05%   |
| 18      | 58        | 1.63%   |
| 34      | 47        | 1.32%   |
| 22      | 45        | 1.26%   |
| 10      | 34        | 0.96%   |
| 20      | 33        | 0.93%   |
| 29      | 12        | 0.34%   |
| 40      | 11        | 0.31%   |
| 16      | 9         | 0.25%   |
| 9       | 9         | 0.25%   |
| 42      | 8         | 0.22%   |
| 54      | 7         | 0.2%    |
| 28      | 7         | 0.2%    |
| 26      | 7         | 0.2%    |
| 25      | 7         | 0.2%    |
| 64      | 6         | 0.17%   |
| 52      | 6         | 0.17%   |
| 39      | 5         | 0.14%   |
| 32      | 5         | 0.14%   |
| 49      | 4         | 0.11%   |
| 46      | 4         | 0.11%   |
| 43      | 4         | 0.11%   |
| 33      | 4         | 0.11%   |
| 50      | 3         | 0.08%   |
| 48      | 3         | 0.08%   |
| 41      | 3         | 0.08%   |
| 37      | 3         | 0.08%   |
| 35      | 3         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1202      | 34.18%  |
| 501-600     | 691       | 19.65%  |
| 201-300     | 557       | 15.84%  |
| 401-500     | 437       | 12.43%  |
| Unknown     | 224       | 6.37%   |
| 351-400     | 151       | 4.29%   |
| 601-700     | 116       | 3.3%    |
| 701-800     | 57        | 1.62%   |
| 1001-1500   | 37        | 1.05%   |
| 801-900     | 21        | 0.6%    |
| 901-1000    | 16        | 0.45%   |
| 101-200     | 6         | 0.17%   |
| 1501-2000   | 1         | 0.03%   |
| 1-100       | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2457      | 73.34%  |
| 16/10   | 401       | 11.97%  |
| Unknown | 194       | 5.79%   |
| 5/4     | 113       | 3.37%   |
| 21/9    | 67        | 2%      |
| 3/2     | 55        | 1.64%   |
| 4/3     | 46        | 1.37%   |
| 32/9    | 6         | 0.18%   |
| 6/5     | 5         | 0.15%   |
| 3.88    | 1         | 0.03%   |
| 3.18    | 1         | 0.03%   |
| 11/10   | 1         | 0.03%   |
| 1.96    | 1         | 0.03%   |
| 1.00    | 1         | 0.03%   |
| 0.46    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 621       | 17.58%  |
| 81-90          | 588       | 16.65%  |
| 91-100         | 516       | 14.61%  |
| 301-350        | 269       | 7.62%   |
| Unknown        | 224       | 6.34%   |
| 151-200        | 202       | 5.72%   |
| 61-70          | 181       | 5.12%   |
| 101-110        | 172       | 4.87%   |
| 351-500        | 140       | 3.96%   |
| 71-80          | 112       | 3.17%   |
| 141-150        | 105       | 2.97%   |
| 251-300        | 99        | 2.8%    |
| 121-130        | 81        | 2.29%   |
| 51-60          | 75        | 2.12%   |
| 501-1000       | 45        | 1.27%   |
| 41-50          | 38        | 1.08%   |
| More than 1000 | 28        | 0.79%   |
| 111-120        | 19        | 0.54%   |
| 131-140        | 10        | 0.28%   |
| 1-40           | 7         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1102      | 31.59%  |
| 121-160       | 919       | 26.35%  |
| 101-120       | 913       | 26.18%  |
| 161-240       | 232       | 6.65%   |
| Unknown       | 224       | 6.42%   |
| More than 240 | 73        | 2.09%   |
| 1-50          | 25        | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 8796      | 69.99%  |
| 1     | 3404      | 27.09%  |
| 2     | 342       | 2.72%   |
| 3     | 23        | 0.18%   |
| 4     | 2         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 8976      | 51.75%  |
| Realtek Semiconductor             | 4416      | 25.46%  |
| Broadcom                          | 1207      | 6.96%   |
| Qualcomm Atheros                  | 1037      | 5.98%   |
| Marvell Technology Group          | 115       | 0.66%   |
| Ralink Technology                 | 114       | 0.66%   |
| Mellanox Technologies             | 112       | 0.65%   |
| TP-Link                           | 94        | 0.54%   |
| AMD                               | 82        | 0.47%   |
| IMC Networks                      | 77        | 0.44%   |
| Ralink                            | 69        | 0.4%    |
| MediaTek                          | 55        | 0.32%   |
| Chelsio Communications            | 55        | 0.32%   |
| D-Link System                     | 54        | 0.31%   |
| Nvidia                            | 52        | 0.3%    |
| Samsung Electronics               | 50        | 0.29%   |
| Edimax Technology                 | 44        | 0.25%   |
| U-Blox                            | 37        | 0.21%   |
| Sierra Wireless                   | 36        | 0.21%   |
| Ericsson Business Mobile Networks | 36        | 0.21%   |
| Aquantia                          | 32        | 0.18%   |
| Huawei Technologies               | 29        | 0.17%   |
| Dell                              | 27        | 0.16%   |
| Xiaomi                            | 26        | 0.15%   |
| Qualcomm Atheros Communications   | 25        | 0.14%   |
| VIA Technologies                  | 24        | 0.14%   |
| Solarflare Communications         | 23        | 0.13%   |
| American Megatrends               | 23        | 0.13%   |
| Google                            | 21        | 0.12%   |
| Apple                             | 21        | 0.12%   |
| ASUSTek Computer                  | 20        | 0.12%   |
| Emulex                            | 19        | 0.11%   |
| QLogic                            | 18        | 0.1%    |
| 3Com                              | 16        | 0.09%   |
| IBM                               | 15        | 0.09%   |
| Hewlett-Packard                   | 15        | 0.09%   |
| JMicron Technology                | 14        | 0.08%   |
| D-Link                            | 14        | 0.08%   |
| NetGear                           | 12        | 0.07%   |
| ZTE WCDMA Technologies MSM        | 11        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 3563      | 16.5%   |
| Intel I211 Gigabit Network Connection                                         | 1394      | 6.45%   |
| Intel I210 Gigabit Network Connection                                         | 945       | 4.38%   |
| Intel I350 Gigabit Network Connection                                         | 644       | 2.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 590       | 2.73%   |
| Intel Ethernet Controller I225-V                                              | 524       | 2.43%   |
| Intel 82574L Gigabit Network Connection                                       | 518       | 2.4%    |
| Intel Ethernet Controller I226-V                                              | 413       | 1.91%   |
| Intel Ethernet Connection I217-LM                                             | 336       | 1.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 290       | 1.34%   |
| Intel 82576 Gigabit Network Connection                                        | 261       | 1.21%   |
| Intel 82583V Gigabit Network Connection                                       | 252       | 1.17%   |
| Realtek RTL8125 2.5GbE Controller                                             | 243       | 1.13%   |
| Intel Wi-Fi 6 AX200                                                           | 242       | 1.12%   |
| Intel Wireless 8265 / 8275                                                    | 236       | 1.09%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 226       | 1.05%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 222       | 1.03%   |
| Intel 82580 Gigabit Network Connection                                        | 220       | 1.02%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 213       | 0.99%   |
| Intel Wireless 7265                                                           | 203       | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                                         | 196       | 0.91%   |
| Intel Wireless 7260                                                           | 182       | 0.84%   |
| Intel Wireless 8260                                                           | 172       | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 169       | 0.78%   |
| Intel Wireless 3165                                                           | 159       | 0.74%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 150       | 0.69%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 143       | 0.66%   |
| Intel Ethernet Connection (2) I219-V                                          | 139       | 0.64%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 132       | 0.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 123       | 0.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 117       | 0.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 116       | 0.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 112       | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 108       | 0.5%    |
| Intel Ethernet Connection (7) I219-V                                          | 107       | 0.5%    |
| Intel Ethernet Connection I354                                                | 105       | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                         | 104       | 0.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 101       | 0.47%   |
| Intel Ethernet Connection I219-LM                                             | 98        | 0.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 94        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2621      | 51.45%  |
| Qualcomm Atheros                      | 853       | 16.75%  |
| Realtek Semiconductor                 | 651       | 12.78%  |
| Broadcom                              | 367       | 7.2%    |
| Ralink Technology                     | 114       | 2.24%   |
| TP-Link                               | 93        | 1.83%   |
| IMC Networks                          | 77        | 1.51%   |
| Ralink                                | 69        | 1.35%   |
| MediaTek                              | 49        | 0.96%   |
| Edimax Technology                     | 44        | 0.86%   |
| Sierra Wireless                       | 27        | 0.53%   |
| Qualcomm Atheros Communications       | 25        | 0.49%   |
| ASUSTek Computer                      | 20        | 0.39%   |
| D-Link                                | 14        | 0.27%   |
| D-Link System                         | 13        | 0.26%   |
| NetGear                               | 12        | 0.24%   |
| Dell                                  | 9         | 0.18%   |
| Mercucys                              | 4         | 0.08%   |
| Belkin Components                     | 4         | 0.08%   |
| Atheros                               | 4         | 0.08%   |
| Qualcomm Technologies                 | 3         | 0.06%   |
| AboCom Systems                        | 3         | 0.06%   |
| ZyXEL Communications                  | 2         | 0.04%   |
| Marvell Technology Group              | 2         | 0.04%   |
| Linksys                               | 2         | 0.04%   |
| BUFFALO                               | 2         | 0.04%   |
| Accton Technology                     | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Senao                                 | 1         | 0.02%   |
| Sagem                                 | 1         | 0.02%   |
| Qcom                                  | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Gemtek                                | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 242       | 4.7%    |
| Intel Wireless 8265 / 8275                                              | 236       | 4.58%   |
| Intel Wireless 7265                                                     | 203       | 3.94%   |
| Intel Wireless 7260                                                     | 182       | 3.53%   |
| Intel Wireless 8260                                                     | 172       | 3.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 169       | 3.28%   |
| Intel Wireless 3165                                                     | 159       | 3.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 123       | 2.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 117       | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 116       | 2.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 112       | 2.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 108       | 2.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 101       | 1.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 94        | 1.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 85        | 1.65%   |
| Intel Wi-Fi 6 AX201                                                     | 78        | 1.51%   |
| Intel Wireless 3160                                                     | 77        | 1.49%   |
| Intel Wireless-AC 9260                                                  | 75        | 1.46%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 75        | 1.46%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 73        | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 72        | 1.4%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 71        | 1.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 69        | 1.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 67        | 1.3%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 57        | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 56        | 1.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 49        | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 48        | 0.93%   |
| Ralink RT5370 Wireless Adapter                                          | 46        | 0.89%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 45        | 0.87%   |
| Intel Centrino Advanced-N 6235                                          | 44        | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 44        | 0.85%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 43        | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 42        | 0.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 42        | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 41        | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 41        | 0.8%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 41        | 0.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 40        | 0.78%   |
| Intel Centrino Ultimate-N 6300                                          | 40        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 7727      | 56.07%  |
| Realtek Semiconductor             | 4131      | 29.98%  |
| Broadcom                          | 937       | 6.8%    |
| Qualcomm Atheros                  | 264       | 1.92%   |
| Marvell Technology Group          | 111       | 0.81%   |
| AMD                               | 81        | 0.59%   |
| Nvidia                            | 52        | 0.38%   |
| Samsung Electronics               | 50        | 0.36%   |
| Chelsio Communications            | 40        | 0.29%   |
| D-Link System                     | 38        | 0.28%   |
| Aquantia                          | 31        | 0.22%   |
| Xiaomi                            | 26        | 0.19%   |
| VIA Technologies                  | 24        | 0.17%   |
| Solarflare Communications         | 23        | 0.17%   |
| American Megatrends               | 23        | 0.17%   |
| QLogic                            | 18        | 0.13%   |
| Apple                             | 18        | 0.13%   |
| Emulex                            | 17        | 0.12%   |
| JMicron Technology                | 14        | 0.1%    |
| 3Com                              | 14        | 0.1%    |
| Google                            | 13        | 0.09%   |
| Qualcomm                          | 11        | 0.08%   |
| Huawei Technologies               | 11        | 0.08%   |
| ICS Advent                        | 9         | 0.07%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.06%   |
| Novatel Wireless                  | 7         | 0.05%   |
| Insyde Software                   | 7         | 0.05%   |
| MediaTek                          | 6         | 0.04%   |
| OPPO Electronics                  | 5         | 0.04%   |
| Davicom Semiconductor             | 5         | 0.04%   |
| National Semiconductor            | 4         | 0.03%   |
| Microsoft                         | 4         | 0.03%   |
| T & A Mobile Phones               | 3         | 0.02%   |
| Sundance Technology Inc / IC Plus | 3         | 0.02%   |
| Silicom                           | 3         | 0.02%   |
| OnePlus Technology (Shenzhen)     | 3         | 0.02%   |
| MYRICOM                           | 3         | 0.02%   |
| Cisco Systems                     | 3         | 0.02%   |
| ADMtek                            | 3         | 0.02%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 3563      | 22.31%  |
| Intel I211 Gigabit Network Connection                                         | 1394      | 8.73%   |
| Intel I210 Gigabit Network Connection                                         | 945       | 5.92%   |
| Intel I350 Gigabit Network Connection                                         | 644       | 4.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 590       | 3.69%   |
| Intel Ethernet Controller I225-V                                              | 524       | 3.28%   |
| Intel 82574L Gigabit Network Connection                                       | 518       | 3.24%   |
| Intel Ethernet Controller I226-V                                              | 413       | 2.59%   |
| Intel Ethernet Connection I217-LM                                             | 336       | 2.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 290       | 1.82%   |
| Intel 82576 Gigabit Network Connection                                        | 261       | 1.63%   |
| Intel 82583V Gigabit Network Connection                                       | 252       | 1.58%   |
| Realtek RTL8125 2.5GbE Controller                                             | 234       | 1.46%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 226       | 1.41%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 222       | 1.39%   |
| Intel 82580 Gigabit Network Connection                                        | 220       | 1.38%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 213       | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                                         | 196       | 1.23%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 150       | 0.94%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 143       | 0.9%    |
| Intel Ethernet Connection (2) I219-V                                          | 139       | 0.87%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 132       | 0.83%   |
| Intel Ethernet Connection (7) I219-V                                          | 107       | 0.67%   |
| Intel Ethernet Connection I354                                                | 105       | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                                         | 104       | 0.65%   |
| Intel Ethernet Connection I219-LM                                             | 98        | 0.61%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 90        | 0.56%   |
| Intel Ethernet Connection X553 1GbE                                           | 85        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 81        | 0.51%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 81        | 0.51%   |
| Intel 82579V Gigabit Network Connection                                       | 80        | 0.5%    |
| AMD XGMAC 10GbE Controller                                                    | 80        | 0.5%    |
| Intel Ethernet Controller X550                                                | 79        | 0.49%   |
| Intel Ethernet Connection (4) I219-LM                                         | 71        | 0.44%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 68        | 0.43%   |
| Intel Ethernet Connection I217-V                                              | 68        | 0.43%   |
| Intel Ethernet Connection (5) I219-LM                                         | 62        | 0.39%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 60        | 0.38%   |
| Intel Ethernet Connection (3) I218-LM                                         | 59        | 0.37%   |
| Intel 82575EB Gigabit Network Connection                                      | 59        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 11805     | 69.49%  |
| WiFi     | 4717      | 27.77%  |
| Unknown  | 299       | 1.76%   |
| Modem    | 166       | 0.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 10828     | 83.45%  |
| WiFi     | 2109      | 16.25%  |
| Unknown  | 25        | 0.19%   |
| Modem    | 13        | 0.1%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4157      | 32.97%  |
| 4     | 2100      | 16.65%  |
| 1     | 2075      | 16.46%  |
| 3     | 1606      | 12.74%  |
| 6     | 1027      | 8.14%   |
| 5     | 772       | 6.12%   |
| 8     | 263       | 2.09%   |
| 0     | 203       | 1.61%   |
| 7     | 163       | 1.29%   |
| 10    | 83        | 0.66%   |
| 9     | 82        | 0.65%   |
| 12    | 28        | 0.22%   |
| 14    | 12        | 0.1%    |
| 13    | 11        | 0.09%   |
| 11    | 10        | 0.08%   |
| 15    | 6         | 0.05%   |
| 16    | 5         | 0.04%   |
| 20    | 4         | 0.03%   |
| 17    | 2         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 10886     | 84.9%   |
| Yes  | 1936      | 15.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1881      | 57.19%  |
| Realtek Semiconductor           | 216       | 6.57%   |
| Broadcom                        | 213       | 6.48%   |
| Apple                           | 187       | 5.69%   |
| Qualcomm Atheros Communications | 184       | 5.59%   |
| IMC Networks                    | 144       | 4.38%   |
| Cambridge Silicon Radio         | 117       | 3.56%   |
| Foxconn / Hon Hai               | 72        | 2.19%   |
| Lite-On Technology              | 66        | 2.01%   |
| ASUSTek Computer                | 54        | 1.64%   |
| Dell                            | 38        | 1.16%   |
| Hewlett-Packard                 | 29        | 0.88%   |
| Alps Electric                   | 18        | 0.55%   |
| MediaTek                        | 17        | 0.52%   |
| Ralink                          | 11        | 0.33%   |
| TP-Link                         | 7         | 0.21%   |
| Skylight Digital                | 6         | 0.18%   |
| Toshiba                         | 3         | 0.09%   |
| Integrated System Solution      | 3         | 0.09%   |
| Fujitsu                         | 3         | 0.09%   |
| USI                             | 2         | 0.06%   |
| Taiyo Yuden                     | 2         | 0.06%   |
| HTC (High Tech Computer)        | 2         | 0.06%   |
| Creative Technology             | 2         | 0.06%   |
| Silicon Wave                    | 1         | 0.03%   |
| Ralink Technology               | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Primax Electronics              | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Esel International              | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 839       | 25.44%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 246       | 7.46%   |
| Intel AX201 Bluetooth                                       | 232       | 7.03%   |
| Intel AX200 Bluetooth                                       | 232       | 7.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 117       | 3.55%   |
| Realtek Bluetooth Adapter                                   | 102       | 3.09%   |
| Intel Wireless-AC 3168 Bluetooth                            | 95        | 2.88%   |
| Apple Bluetooth Host Controller                             | 93        | 2.82%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 74        | 2.24%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 67        | 2.03%   |
| Intel AX210 Bluetooth                                       | 67        | 2.03%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 61        | 1.85%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 56        | 1.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 44        | 1.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 38        | 1.15%   |
| IMC Networks Realtek Bluetooth Adapter                      | 37        | 1.12%   |
| Realtek  Bluetooth 4.2 Adapter                              | 36        | 1.09%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 36        | 1.09%   |
| Apple Broadcom Built-in Bluetooth                           | 33        | 1%      |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 28        | 0.85%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 23        | 0.7%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 22        | 0.67%   |
| Lite-On Atheros AR3012 Bluetooth                            | 21        | 0.64%   |
| Intel AX211 Bluetooth                                       | 21        | 0.64%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 19        | 0.58%   |
| Realtek Bluetooth 4.0 Adapter                               | 18        | 0.55%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 18        | 0.55%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 18        | 0.55%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 18        | 0.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 17        | 0.52%   |
| MediaTek RZ608 Bluetooth Adapter                            | 16        | 0.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 16        | 0.49%   |
| Apple Built-in iSight (no firmware loaded)                  | 16        | 0.49%   |
| Realtek Bluetooth 4.2 Adapter                               | 15        | 0.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 15        | 0.45%   |
| Dell DW375 Bluetooth Module                                 | 15        | 0.45%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 13        | 0.39%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 13        | 0.39%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 12        | 0.36%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 12        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 7577      | 67.77%  |
| AMD                                          | 1956      | 17.49%  |
| Nvidia                                       | 1054      | 9.43%   |
| C-Media Electronics                          | 115       | 1.03%   |
| Logitech                                     | 39        | 0.35%   |
| Creative Labs                                | 34        | 0.3%    |
| Texas Instruments                            | 33        | 0.3%    |
| Zoran Co. Personal Media Division (Nogatech) | 29        | 0.26%   |
| Realtek Semiconductor                        | 20        | 0.18%   |
| Lenovo                                       | 17        | 0.15%   |
| GN Netcom                                    | 17        | 0.15%   |
| VIA Technologies                             | 16        | 0.14%   |
| Generalplus Technology                       | 15        | 0.13%   |
| SteelSeries ApS                              | 14        | 0.13%   |
| JMTek                                        | 14        | 0.13%   |
| Silicon Integrated Systems [SiS]             | 13        | 0.12%   |
| Creative Technology                          | 11        | 0.1%    |
| ASUSTek Computer                             | 11        | 0.1%    |
| KTMicro                                      | 10        | 0.09%   |
| Kingston Technology                          | 9         | 0.08%   |
| BEHRINGER International                      | 9         | 0.08%   |
| Focusrite-Novation                           | 8         | 0.07%   |
| Plantronics                                  | 7         | 0.06%   |
| Yamaha                                       | 6         | 0.05%   |
| Sony                                         | 6         | 0.05%   |
| ESS Technology                               | 6         | 0.05%   |
| Corsair                                      | 6         | 0.05%   |
| Blue Microphones                             | 6         | 0.05%   |
| MosArt Semiconductor                         | 5         | 0.04%   |
| Hewlett-Packard                              | 5         | 0.04%   |
| Cambridge Silicon Radio                      | 5         | 0.04%   |
| XMOS                                         | 4         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 4         | 0.04%   |
| Tenx Technology                              | 4         | 0.04%   |
| Razer USA                                    | 4         | 0.04%   |
| M-Audio                                      | 4         | 0.04%   |
| ULi Electronics                              | 3         | 0.03%   |
| RODE Microphones                             | 3         | 0.03%   |
| Micro Star International                     | 3         | 0.03%   |
| FiiO Electronics Technology                  | 3         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 635       | 4.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 609       | 4.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 594       | 4.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 557       | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 530       | 3.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 482       | 3.61%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 480       | 3.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 380       | 2.85%   |
| Intel Jasper Lake HD Audio                                                                        | 376       | 2.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 371       | 2.78%   |
| AMD FCH Azalia Controller                                                                         | 363       | 2.72%   |
| Intel Cannon Lake PCH cAVS                                                                        | 305       | 2.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 291       | 2.18%   |
| Intel 8 Series HD Audio Controller                                                                | 281       | 2.11%   |
| AMD Kabini HDMI/DP Audio                                                                          | 281       | 2.11%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 278       | 2.08%   |
| Intel Broadwell-U Audio Controller                                                                | 259       | 1.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 255       | 1.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 255       | 1.91%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 230       | 1.72%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 230       | 1.72%   |
| Intel 200 Series PCH HD Audio                                                                     | 225       | 1.69%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 210       | 1.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 190       | 1.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 181       | 1.36%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 177       | 1.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 174       | 1.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 168       | 1.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 141       | 1.06%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 130       | 0.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 129       | 0.97%   |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 125       | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 121       | 0.91%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 117       | 0.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 100       | 0.75%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 89        | 0.67%   |
| Intel Comet Lake PCH cAVS                                                                         | 80        | 0.6%    |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 77        | 0.58%   |
| Nvidia High Definition Audio Controller                                                           | 70        | 0.52%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 70        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 2413      | 18.55%  |
| SK hynix                                | 1777      | 13.66%  |
| Kingston                                | 1536      | 11.81%  |
| Unknown                                 | 1395      | 10.72%  |
| Micron Technology                       | 1141      | 8.77%   |
| Crucial                                 | 1129      | 8.68%   |
| Corsair                                 | 561       | 4.31%   |
| G.Skill                                 | 415       | 3.19%   |
| Unknown                                 | 392       | 3.01%   |
| Transcend                               | 225       | 1.73%   |
| A-DATA Technology                       | 213       | 1.64%   |
| Unknown (ABCD)                          | 181       | 1.39%   |
| Ramaxel Technology                      | 169       | 1.3%    |
| Nanya Technology                        | 144       | 1.11%   |
| Team                                    | 120       | 0.92%   |
| Elpida                                  | 115       | 0.88%   |
| Patriot                                 | 92        | 0.71%   |
| Kimtigo                                 | 62        | 0.48%   |
| Apacer                                  | 62        | 0.48%   |
| Hewlett-Packard                         | 55        | 0.42%   |
| Smart                                   | 48        | 0.37%   |
| Toshiba                                 | 46        | 0.35%   |
| GOODRAM                                 | 36        | 0.28%   |
| PNY                                     | 33        | 0.25%   |
| ATP                                     | 33        | 0.25%   |
| Timetec                                 | 29        | 0.22%   |
| Avant                                   | 29        | 0.22%   |
| Teikon                                  | 26        | 0.2%    |
| Silicon Power                           | 18        | 0.14%   |
| AMD                                     | 18        | 0.14%   |
| Innodisk                                | 16        | 0.12%   |
| SK_Hynix                                | 15        | 0.12%   |
| Unknown (AB)                            | 14        | 0.11%   |
| Super Talent                            | 14        | 0.11%   |
| Patriot Memory (PDP Systems)            | 14        | 0.11%   |
| GeIL                                    | 14        | 0.11%   |
| HPE                                     | 13        | 0.1%    |
| tigo                                    | 12        | 0.09%   |
| 48spaces                                | 12        | 0.09%   |
| Silicon Power Computer & Communications | 10        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 392       | 2.82%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 167       | 1.2%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 165       | 1.19%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 109       | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 101       | 0.73%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 71        | 0.51%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 66        | 0.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 63        | 0.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 61        | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 57        | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 57        | 0.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 56        | 0.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 54        | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 53        | 0.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 50        | 0.36%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s             | 50        | 0.36%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 46        | 0.33%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s               | 45        | 0.32%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 44        | 0.32%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 43        | 0.31%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s             | 42        | 0.3%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s             | 41        | 0.29%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 41        | 0.29%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s           | 40        | 0.29%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 39        | 0.28%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 36        | 0.26%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s             | 36        | 0.26%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s               | 36        | 0.26%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 36        | 0.26%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s           | 36        | 0.26%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s             | 36        | 0.26%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 35        | 0.25%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s             | 34        | 0.24%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                    | 34        | 0.24%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                         | 33        | 0.24%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 33        | 0.24%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 33        | 0.24%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 33        | 0.24%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s             | 33        | 0.24%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 32        | 0.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR3            | 5258      | 45.99%  |
| DDR4            | 4480      | 39.19%  |
| DDR2            | 563       | 4.92%   |
| Unknown         | 318       | 2.78%   |
| LPDDR4          | 292       | 2.55%   |
| SDRAM           | 149       | 1.3%    |
| DDR5            | 146       | 1.28%   |
| LPDDR3          | 94        | 0.82%   |
| DDR             | 71        | 0.62%   |
| LPDDR5          | 35        | 0.31%   |
| DRAM            | 18        | 0.16%   |
| RAM             | 5         | 0.04%   |
| SRAM            | 1         | 0.01%   |
| Logical non-vol | 1         | 0.01%   |
| DDR2 FB-DIMM    | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 5653      | 49.62%  |
| SODIMM       | 5298      | 46.5%   |
| Row Of Chips | 230       | 2.02%   |
| Unknown      | 96        | 0.84%   |
| Chip         | 68        | 0.6%    |
| FB-DIMM      | 34        | 0.3%    |
| RIMM         | 14        | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 4468      | 36.28%  |
| 4096   | 3872      | 31.44%  |
| 16384  | 1628      | 13.22%  |
| 2048   | 1590      | 12.91%  |
| 32768  | 350       | 2.84%   |
| 1024   | 326       | 2.65%   |
| 512    | 46        | 0.37%   |
| 256    | 9         | 0.07%   |
| 65536  | 7         | 0.06%   |
| 128    | 4         | 0.03%   |
| 3072   | 3         | 0.02%   |
| 32767  | 2         | 0.02%   |
| 64     | 2         | 0.02%   |
| 131072 | 1         | 0.01%   |
| 129728 | 1         | 0.01%   |
| 6144   | 1         | 0.01%   |
| 4092   | 1         | 0.01%   |
| 2560   | 1         | 0.01%   |
| 1556   | 1         | 0.01%   |
| 1491   | 1         | 0.01%   |
| 32     | 1         | 0.01%   |
| 8      | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 3408      | 28.04%  |
| 1333    | 1577      | 12.98%  |
| 2400    | 1439      | 11.84%  |
| 2667    | 1187      | 9.77%   |
| 3200    | 1164      | 9.58%   |
| 2133    | 806       | 6.63%   |
| 800     | 373       | 3.07%   |
| 667     | 359       | 2.95%   |
| Unknown | 219       | 1.8%    |
| 2666    | 200       | 1.65%   |
| 1867    | 179       | 1.47%   |
| 1334    | 177       | 1.46%   |
| 1067    | 176       | 1.45%   |
| 1066    | 152       | 1.25%   |
| 4800    | 121       | 1%      |
| 3000    | 82        | 0.67%   |
| 2933    | 81        | 0.67%   |
| 1866    | 78        | 0.64%   |
| 3600    | 63        | 0.52%   |
| 533     | 47        | 0.39%   |
| 6400    | 37        | 0.3%    |
| 4267    | 37        | 0.3%    |
| 400     | 33        | 0.27%   |
| 5600    | 19        | 0.16%   |
| 975     | 12        | 0.1%    |
| 2048    | 10        | 0.08%   |
| 333     | 10        | 0.08%   |
| 4000    | 8         | 0.07%   |
| 3733    | 8         | 0.07%   |
| 266     | 8         | 0.07%   |
| 4266    | 7         | 0.06%   |
| 1400    | 7         | 0.06%   |
| 1332    | 7         | 0.06%   |
| 1033    | 7         | 0.06%   |
| 5200    | 6         | 0.05%   |
| 1639    | 6         | 0.05%   |
| 65535   | 5         | 0.04%   |
| 3400    | 5         | 0.04%   |
| 1200    | 5         | 0.04%   |
| 3534    | 3         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Brother Industries    | 13        | 30.23%  |
| Hewlett-Packard       | 12        | 27.91%  |
| Prolific Technology   | 4         | 9.3%    |
| Seiko Epson           | 2         | 4.65%   |
| Lexmark International | 2         | 4.65%   |
| ELGIN                 | 2         | 4.65%   |
| Dymo-CoStar           | 2         | 4.65%   |
| Samsung Electronics   | 1         | 2.33%   |
| Ricoh                 | 1         | 2.33%   |
| QinHeng Electronics   | 1         | 2.33%   |
| Kyocera               | 1         | 2.33%   |
| Canon                 | 1         | 2.33%   |
| Apple                 | 1         | 2.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Computers | Percent |
|-------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                                                                     | 4         | 8.89%   |
| ELGIN L42PRO                                                                                                      | 2         | 4.44%   |
| Brother MFC-7360N                                                                                                 | 2         | 4.44%   |
| Brother HL-1430 Laser Printer                                                                                     | 2         | 4.44%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                                                                             | 1         | 2.22%   |
| Seiko Epson Printer                                                                                               | 1         | 2.22%   |
| Samsung ML-1610 Mono Laser Printer                                                                                | 1         | 2.22%   |
| Ricoh SP 112                                                                                                      | 1         | 2.22%   |
| QinHeng CH340S                                                                                                    | 1         | 2.22%   |
| Lexmark International SINDOH A603_A608 Print                                                                      | 1         | 2.22%   |
| Lexmark International Lexmark MS710 Print                                                                         | 1         | 2.22%   |
| Kyocera FS-1025MFP                                                                                                | 1         | 2.22%   |
| HP PNP Fax Null                                                                                                   | 1         | 2.22%   |
| HP LaserJet P3005                                                                                                 | 1         | 2.22%   |
| HP LaserJet 3390                                                                                                  | 1         | 2.22%   |
| HP LaserJet 2200                                                                                                  | 1         | 2.22%   |
| HP LaserJet 1200                                                                                                  | 1         | 2.22%   |
| HP LaserJet 1020                                                                                                  | 1         | 2.22%   |
| HP LaserJet 1012                                                                                                  | 1         | 2.22%   |
| HP Laser 107a Printer                                                                                             | 1         | 2.22%   |
| HP HP LaserJet P2035 HP Print                                                                                     | 1         | 2.22%   |
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1         | 2.22%   |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer                        | 1         | 2.22%   |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer                                          | 1         | 2.22%   |
| HP DeskJet 5850c                                                                                                  | 1         | 2.22%   |
| HP Color LaserJet CP1215                                                                                          | 1         | 2.22%   |
| Dymo-CoStar LabelWriter 450                                                                                       | 1         | 2.22%   |
| Dymo-CoStar DYMO LabelWriter 450 DUO                                                                              | 1         | 2.22%   |
| Canon LBP2900                                                                                                     | 1         | 2.22%   |
| Brother MFC-L2685DW                                                                                               | 1         | 2.22%   |
| Brother MFC-J485DW                                                                                                | 1         | 2.22%   |
| Brother MFC-J200                                                                                                  | 1         | 2.22%   |
| Brother HL-L5200DW series                                                                                         | 1         | 2.22%   |
| Brother HL-L2310D series                                                                                          | 1         | 2.22%   |
| Brother HL-L2300D series                                                                                          | 1         | 2.22%   |
| Brother HL-2030 Laser Printer                                                                                     | 1         | 2.22%   |
| Brother DCP-J152W                                                                                                 | 1         | 2.22%   |
| Brother DCP-J100                                                                                                  | 1         | 2.22%   |
| Apple Gamesir-G3s 2.10                                                                                            | 1         | 2.22%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 13        | 76.47%  |
| Seiko Epson     | 3         | 17.65%  |
| Hewlett-Packard | 1         | 5.88%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 4         | 23.53%  |
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 2         | 11.76%  |
| Canon CanoScan LiDE 220                                                             | 2         | 11.76%  |
| Canon CanoScan LiDE 210                                                             | 2         | 11.76%  |
| Canon CanoScan LiDE 120                                                             | 2         | 11.76%  |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 5.88%   |
| HP ScanJet 5300c/5370c                                                              | 1         | 5.88%   |
| Canon CanoScan LiDE 700F                                                            | 1         | 5.88%   |
| Canon CanoScan LIDE 25                                                              | 1         | 5.88%   |
| Canon CanoScan LiDE 100                                                             | 1         | 5.88%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 592       | 27.13%  |
| Bison Electronics                      | 229       | 10.49%  |
| IMC Networks                           | 194       | 8.89%   |
| Microdia                               | 187       | 8.57%   |
| Realtek Semiconductor                  | 173       | 7.93%   |
| Sunplus Innovation Technology          | 117       | 5.36%   |
| Logitech                               | 97        | 4.45%   |
| Suyin                                  | 68        | 3.12%   |
| Lite-On Technology                     | 65        | 2.98%   |
| Apple                                  | 48        | 2.2%    |
| Cheng Uei Precision Industry (Foxlink) | 47        | 2.15%   |
| Syntek                                 | 46        | 2.11%   |
| Quanta                                 | 45        | 2.06%   |
| Silicon Motion                         | 31        | 1.42%   |
| Lenovo                                 | 27        | 1.24%   |
| Alcor Micro                            | 26        | 1.19%   |
| Luxvisions Innotech Limited            | 25        | 1.15%   |
| Z-Star Microelectronics                | 23        | 1.05%   |
| ALi                                    | 15        | 0.69%   |
| Ricoh                                  | 13        | 0.6%    |
| Importek                               | 11        | 0.5%    |
| ARC International                      | 8         | 0.37%   |
| Shenzhen Kingcome Optoelectronic       | 7         | 0.32%   |
| Intel                                  | 6         | 0.27%   |
| Supreme Electronics                    | 5         | 0.23%   |
| Trust                                  | 4         | 0.18%   |
| Primax Electronics                     | 4         | 0.18%   |
| OmniVision Technologies                | 4         | 0.18%   |
| Jiangxi Shinetech Optical              | 4         | 0.18%   |
| Genesys Logic                          | 4         | 0.18%   |
| GEMBIRD                                | 4         | 0.18%   |
| Arkmicro Technologies                  | 4         | 0.18%   |
| Unknown                                | 3         | 0.14%   |
| Tripath Technology                     | 3         | 0.14%   |
| Generalplus Technology                 | 3         | 0.14%   |
| DigiTech                               | 3         | 0.14%   |
| Cubeternet                             | 3         | 0.14%   |
| WCM_USB                                | 2         | 0.09%   |
| USB Camera                             | 2         | 0.09%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 181       | 8.22%   |
| Bison Integrated Camera                       | 106       | 4.81%   |
| IMC Networks Integrated Camera                | 63        | 2.86%   |
| Microdia Integrated_Webcam_HD                 | 51        | 2.32%   |
| Realtek Integrated_Webcam_HD                  | 43        | 1.95%   |
| Lite-On Integrated Camera                     | 42        | 1.91%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 40        | 1.82%   |
| Microdia Integrated Webcam                    | 39        | 1.77%   |
| Chicony HD WebCam                             | 39        | 1.77%   |
| Sunplus Integrated_Webcam_HD                  | 34        | 1.54%   |
| Realtek USB 2.0 PC Camera                     | 29        | 1.32%   |
| Chicony Integrated Camera (1280x720@30)       | 28        | 1.27%   |
| Logitech Webcam C270                          | 26        | 1.18%   |
| Bison Lenovo EasyCamera                       | 25        | 1.13%   |
| Apple FaceTime HD Camera                      | 25        | 1.13%   |
| IMC Networks Realtek PC Camera                | 23        | 1.04%   |
| Bison SunplusIT Integrated Camera             | 23        | 1.04%   |
| Logitech HD Pro Webcam C920                   | 21        | 0.95%   |
| Chicony Integrated Camera [ThinkPad]          | 21        | 0.95%   |
| IMC Networks EasyCamera                       | 20        | 0.91%   |
| Apple FaceTime HD Camera (Built-in)           | 19        | 0.86%   |
| Chicony Realtek DMFT RGB                      | 18        | 0.82%   |
| Syntek Lenovo EasyCamera                      | 16        | 0.73%   |
| Chicony Integrated IR Camera                  | 16        | 0.73%   |
| Bison ThinkPad Integrated Camera              | 16        | 0.73%   |
| Realtek USB Camera                            | 15        | 0.68%   |
| Lenovo Integrated Webcam [R5U877]             | 15        | 0.68%   |
| Chicony HP HD Webcam [Fixed]                  | 15        | 0.68%   |
| Syntek EasyCamera                             | 14        | 0.64%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 13        | 0.59%   |
| Microdia USB 2.0 Camera                       | 13        | 0.59%   |
| Bison Lenovo Integrated Webcam                | 13        | 0.59%   |
| Syntek Integrated Camera                      | 12        | 0.54%   |
| Luxvisions Innotech Limited Integrated Camera | 12        | 0.54%   |
| Chicony Lenovo EasyCamera                     | 12        | 0.54%   |
| Chicony FJ Camera                             | 12        | 0.54%   |
| Chicony EasyCamera                            | 12        | 0.54%   |
| Chicony Chicony USB2.0 Camera                 | 12        | 0.54%   |
| Microdia Dell Laptop Integrated Webcam HD     | 11        | 0.5%    |
| IMC Networks UVC VGA Webcam                   | 11        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 209       | 36.67%  |
| Synaptics                  | 115       | 20.18%  |
| Upek                       | 64        | 11.23%  |
| AuthenTec                  | 46        | 8.07%   |
| Shenzhen Goodix Technology | 44        | 7.72%   |
| STMicroelectronics         | 32        | 5.61%   |
| Broadcom                   | 18        | 3.16%   |
| LighTuning Technology      | 15        | 2.63%   |
| Elan Microelectronics      | 14        | 2.46%   |
| FocalTech Systems          | 8         | 1.4%    |
| Samsung Electronics        | 2         | 0.35%   |
| Next Biometrics            | 1         | 0.18%   |
| Fingerprint Cards          | 1         | 0.18%   |
| DigitalPersona             | 1         | 0.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 68        | 11.93%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 61        | 10.7%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 47        | 8.25%   |
| Validity Sensors Synaptics WBDI                                              | 37        | 6.49%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 35        | 6.14%   |
| Shenzhen Goodix Fingerprint Reader                                           | 33        | 5.79%   |
| STMicroelectronics Fingerprint Reader                                        | 32        | 5.61%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 24        | 4.21%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 24        | 4.21%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 18        | 3.16%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 17        | 2.98%   |
| Elan Fingerprint Sensor                                                      | 14        | 2.46%   |
| AuthenTec AES2810                                                            | 14        | 2.46%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 12        | 2.11%   |
| Synaptics WBDI                                                               | 8         | 1.4%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 8         | 1.4%    |
| AuthenTec AES1660                                                            | 8         | 1.4%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 7         | 1.23%   |
| Shenzhen Goodix  Fingerprint Device                                          | 7         | 1.23%   |
| Validity Sensors VFS491                                                      | 6         | 1.05%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 6         | 1.05%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 6         | 1.05%   |
| FocalTech Systems Fingerprint Reader                                         | 6         | 1.05%   |
| AuthenTec AES1600                                                            | 6         | 1.05%   |
| Validity Sensors Fingerprint scanner                                         | 5         | 0.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 5         | 0.88%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 4         | 0.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 4         | 0.7%    |
| Validity Sensors Swipe Fingerprint Sensor                                    | 4         | 0.7%    |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 4         | 0.7%    |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 4         | 0.7%    |
| Validity Sensors VFS101 Fingerprint Reader                                   | 3         | 0.53%   |
| Validity Sensors VFS Fingerprint sensor                                      | 3         | 0.53%   |
| Upek TCS5B Fingerprint sensor                                                | 3         | 0.53%   |
| AuthenTec AES2660                                                            | 3         | 0.53%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 2         | 0.35%   |
| Synaptics UWP WBDI Device                                                    | 2         | 0.35%   |
| Synaptics UWP WBDI                                                           | 2         | 0.35%   |
| Samsung CanvasBio Fingerprint Reader                                         | 2         | 0.35%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 2         | 0.35%   |

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
| 1     | 5191      | 40.49%  |
| 0     | 4016      | 31.33%  |
| 2     | 2254      | 17.58%  |
| 3     | 926       | 7.22%   |
| 4     | 326       | 2.54%   |
| 5     | 73        | 0.57%   |
| 6     | 20        | 0.16%   |
| 7     | 9         | 0.07%   |
| 9     | 2         | 0.02%   |
| 8     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 7378      | 60.04%  |
| Bluetooth                | 1288      | 10.48%  |
| Net/wireless             | 1207      | 9.82%   |
| Card reader              | 744       | 6.05%   |
| Fingerprint reader       | 485       | 3.95%   |
| Firewire controller      | 387       | 3.15%   |
| Sound                    | 201       | 1.64%   |
| Net/ethernet             | 173       | 1.41%   |
| Network                  | 164       | 1.33%   |
| Graphics card            | 122       | 0.99%   |
| Storage                  | 54        | 0.44%   |
| Modem                    | 26        | 0.21%   |
| Storage/ata              | 21        | 0.17%   |
| Storage/raid             | 19        | 0.15%   |
| Dvb card                 | 10        | 0.08%   |
| Storage/ide              | 6         | 0.05%   |
| Storage/nvme             | 3         | 0.02%   |
| Wireless                 | 1         | 0.01%   |

