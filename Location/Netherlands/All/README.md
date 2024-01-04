BSD in Netherlands - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for BSD in Netherlands.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Netherlands/Desktop/README.md) and [notebooks](/Location/Netherlands/Notebook/README.md).

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

Total: 533

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Intel         | NUC11TNBi3 M11908-404       | Mini pc     | [5dac39e062](https://bsd-hardware.info/?probe=5dac39e062) | Jan 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [cd6ce65004](https://bsd-hardware.info/?probe=cd6ce65004) | Dec 29, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [f34b5d84dd](https://bsd-hardware.info/?probe=f34b5d84dd) | Dec 28, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [533a831b97](https://bsd-hardware.info/?probe=533a831b97) | Dec 26, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [c728132d77](https://bsd-hardware.info/?probe=c728132d77) | Dec 20, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [321e9d7328](https://bsd-hardware.info/?probe=321e9d7328) | Dec 20, 2023 |
| Lenovo        | 314C SEK0T35577 IOT 4247... | Mini pc     | [5b09e2113c](https://bsd-hardware.info/?probe=5b09e2113c) | Dec 17, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [fe741ca47c](https://bsd-hardware.info/?probe=fe741ca47c) | Dec 17, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [b453da5223](https://bsd-hardware.info/?probe=b453da5223) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [37499be816](https://bsd-hardware.info/?probe=37499be816) | Dec 11, 2023 |
| AAEON         | FWS-2362 V1.0               | Desktop     | [a58d1df175](https://bsd-hardware.info/?probe=a58d1df175) | Dec 10, 2023 |
| HP            | 82A2                        | Desktop     | [688675d8ea](https://bsd-hardware.info/?probe=688675d8ea) | Dec 10, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [b193b5141c](https://bsd-hardware.info/?probe=b193b5141c) | Dec 07, 2023 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [b5bbc08efe](https://bsd-hardware.info/?probe=b5bbc08efe) | Dec 07, 2023 |
| Protectli     | FW4C                        | Desktop     | [d14bbfd96c](https://bsd-hardware.info/?probe=d14bbfd96c) | Dec 05, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d9c6d21d10](https://bsd-hardware.info/?probe=d9c6d21d10) | Dec 05, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [cb6b022d45](https://bsd-hardware.info/?probe=cb6b022d45) | Dec 04, 2023 |
| Protectli     | FW4B                        | Desktop     | [a92d9762ce](https://bsd-hardware.info/?probe=a92d9762ce) | Dec 04, 2023 |
| Dell          | 0GCPWH A00                  | Mini pc     | [27867fc6fb](https://bsd-hardware.info/?probe=27867fc6fb) | Nov 30, 2023 |
| BESSTAR Te... | GB7B                        | Mini pc     | [ceccfb11da](https://bsd-hardware.info/?probe=ceccfb11da) | Nov 30, 2023 |
| BESSTAR Te... | GB7B                        | Mini pc     | [2d16e2f338](https://bsd-hardware.info/?probe=2d16e2f338) | Nov 29, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [24f4b0ec7e](https://bsd-hardware.info/?probe=24f4b0ec7e) | Nov 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [00ad304a82](https://bsd-hardware.info/?probe=00ad304a82) | Nov 24, 2023 |
| HP            | 21D0                        | Desktop     | [d03aa6a73b](https://bsd-hardware.info/?probe=d03aa6a73b) | Nov 23, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [829f20c667](https://bsd-hardware.info/?probe=829f20c667) | Nov 23, 2023 |
| Shuttle       | XH310V2                     | Desktop     | [524f7be8b5](https://bsd-hardware.info/?probe=524f7be8b5) | Nov 22, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cb6ef0498c](https://bsd-hardware.info/?probe=cb6ef0498c) | Nov 22, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [8610627793](https://bsd-hardware.info/?probe=8610627793) | Nov 16, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [a5aa96e30f](https://bsd-hardware.info/?probe=a5aa96e30f) | Nov 16, 2023 |
| HP            | 82A2                        | Desktop     | [11985512b1](https://bsd-hardware.info/?probe=11985512b1) | Nov 08, 2023 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [e3852e0a81](https://bsd-hardware.info/?probe=e3852e0a81) | Nov 05, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [0caf100d71](https://bsd-hardware.info/?probe=0caf100d71) | Oct 30, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [534dc363f2](https://bsd-hardware.info/?probe=534dc363f2) | Oct 30, 2023 |
| PC Engines    | APU2                        | Desktop     | [78e2f0b5e4](https://bsd-hardware.info/?probe=78e2f0b5e4) | Oct 30, 2023 |
| AAEON         | FWS-2362 V1.0               | Desktop     | [cddea934bd](https://bsd-hardware.info/?probe=cddea934bd) | Oct 30, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [937bf733c5](https://bsd-hardware.info/?probe=937bf733c5) | Oct 28, 2023 |
| ASRock        | N100DC-ITX                  | Desktop     | [888d7c9d18](https://bsd-hardware.info/?probe=888d7c9d18) | Oct 28, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [9508bd06f5](https://bsd-hardware.info/?probe=9508bd06f5) | Oct 28, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [d9f0644c56](https://bsd-hardware.info/?probe=d9f0644c56) | Oct 24, 2023 |
| Lenovo        | 319E SEK0T35577 IOT 4247... | Mini pc     | [52715e6be9](https://bsd-hardware.info/?probe=52715e6be9) | Oct 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [648234b9c2](https://bsd-hardware.info/?probe=648234b9c2) | Oct 09, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [dc147098c6](https://bsd-hardware.info/?probe=dc147098c6) | Oct 08, 2023 |
| HP            | 82B4                        | Desktop     | [daaf49e002](https://bsd-hardware.info/?probe=daaf49e002) | Oct 06, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [dfaa515b13](https://bsd-hardware.info/?probe=dfaa515b13) | Oct 04, 2023 |
| Intel         | NUC8BEB J72692-307          | Mini pc     | [e43673f564](https://bsd-hardware.info/?probe=e43673f564) | Oct 01, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [bfe4c8617a](https://bsd-hardware.info/?probe=bfe4c8617a) | Sep 29, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [c7e64c0893](https://bsd-hardware.info/?probe=c7e64c0893) | Sep 19, 2023 |
| HP            | ProLiant DL380 Gen9         | Server      | [65aa2c10a3](https://bsd-hardware.info/?probe=65aa2c10a3) | Sep 18, 2023 |
| Sophos        | SG                          | Firewall    | [3328f1aa70](https://bsd-hardware.info/?probe=3328f1aa70) | Sep 13, 2023 |
| Sophos        | SG                          | Firewall    | [4bc5b044cd](https://bsd-hardware.info/?probe=4bc5b044cd) | Sep 12, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [6857d78d0b](https://bsd-hardware.info/?probe=6857d78d0b) | Sep 12, 2023 |
| HP            | 8105                        | Desktop     | [ea4f88787c](https://bsd-hardware.info/?probe=ea4f88787c) | Sep 10, 2023 |
| HP            | 8105                        | Desktop     | [0e45394704](https://bsd-hardware.info/?probe=0e45394704) | Sep 10, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [f0fc4f47b8](https://bsd-hardware.info/?probe=f0fc4f47b8) | Sep 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [35e9ee2a00](https://bsd-hardware.info/?probe=35e9ee2a00) | Sep 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [a308c3a87b](https://bsd-hardware.info/?probe=a308c3a87b) | Aug 31, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [914608f1b7](https://bsd-hardware.info/?probe=914608f1b7) | Aug 30, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [8109e9f43f](https://bsd-hardware.info/?probe=8109e9f43f) | Aug 29, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [b83ebfd33b](https://bsd-hardware.info/?probe=b83ebfd33b) | Aug 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [0de8fccd23](https://bsd-hardware.info/?probe=0de8fccd23) | Aug 27, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [4d51e18ce4](https://bsd-hardware.info/?probe=4d51e18ce4) | Aug 25, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [f07be9b690](https://bsd-hardware.info/?probe=f07be9b690) | Aug 24, 2023 |
| Advantech     | SYS-2USM02-6M01E            | Desktop     | [dd02b9879d](https://bsd-hardware.info/?probe=dd02b9879d) | Aug 20, 2023 |
| CncTion       | N5105-4L-I226 B0            | Desktop     | [40f2ba2800](https://bsd-hardware.info/?probe=40f2ba2800) | Aug 18, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | Desktop     | [ad77aba442](https://bsd-hardware.info/?probe=ad77aba442) | Aug 15, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b05547dfb4](https://bsd-hardware.info/?probe=b05547dfb4) | Aug 13, 2023 |
| ASRock        | IMB-195                     | Desktop     | [7b5a73b87e](https://bsd-hardware.info/?probe=7b5a73b87e) | Aug 09, 2023 |
| Supermicro    | X12STL-IF                   | Server      | [e588cd796e](https://bsd-hardware.info/?probe=e588cd796e) | Aug 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [080c931545](https://bsd-hardware.info/?probe=080c931545) | Jul 31, 2023 |
| Supermicro    | X7SLA                       | Desktop     | [c9a39071d0](https://bsd-hardware.info/?probe=c9a39071d0) | Jul 31, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [e06b70a370](https://bsd-hardware.info/?probe=e06b70a370) | Jul 29, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [c9ecdb6ecc](https://bsd-hardware.info/?probe=c9ecdb6ecc) | Jul 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [468f7385c9](https://bsd-hardware.info/?probe=468f7385c9) | Jul 25, 2023 |
| ASRock        | J4205-ITX                   | Desktop     | [90fc3f8e29](https://bsd-hardware.info/?probe=90fc3f8e29) | Jul 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [154660fa30](https://bsd-hardware.info/?probe=154660fa30) | Jul 21, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [abec149182](https://bsd-hardware.info/?probe=abec149182) | Jul 17, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [a99b1233cf](https://bsd-hardware.info/?probe=a99b1233cf) | Jul 15, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [d4265533e2](https://bsd-hardware.info/?probe=d4265533e2) | Jul 15, 2023 |
| Protectli     | VP46xx                      | Desktop     | [516324d248](https://bsd-hardware.info/?probe=516324d248) | Jul 13, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [08b0409497](https://bsd-hardware.info/?probe=08b0409497) | Jul 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [19bec52055](https://bsd-hardware.info/?probe=19bec52055) | Jul 12, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [0723a0cf95](https://bsd-hardware.info/?probe=0723a0cf95) | Jul 11, 2023 |
| Lenovo        | 319E SEK0T35577 IOT 4247... | Mini pc     | [979d165cae](https://bsd-hardware.info/?probe=979d165cae) | Jul 11, 2023 |
| Protectli     | FW2B Ver                    | Desktop     | [e0746e5253](https://bsd-hardware.info/?probe=e0746e5253) | Jul 10, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [7119cd7ae3](https://bsd-hardware.info/?probe=7119cd7ae3) | Jul 08, 2023 |
| Shuttle       | FH110                       | Desktop     | [e68f7ffbf9](https://bsd-hardware.info/?probe=e68f7ffbf9) | Jul 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [e0dd332586](https://bsd-hardware.info/?probe=e0dd332586) | Jul 05, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [f74b33bc25](https://bsd-hardware.info/?probe=f74b33bc25) | Jul 03, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [f9f815c60e](https://bsd-hardware.info/?probe=f9f815c60e) | Jul 02, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [39e46fd477](https://bsd-hardware.info/?probe=39e46fd477) | Jul 02, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [3e8f4fb0a8](https://bsd-hardware.info/?probe=3e8f4fb0a8) | Jun 29, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [17834256ca](https://bsd-hardware.info/?probe=17834256ca) | Jun 28, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [96917bdb04](https://bsd-hardware.info/?probe=96917bdb04) | Jun 26, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [be0008eb2a](https://bsd-hardware.info/?probe=be0008eb2a) | Jun 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [18da718e9e](https://bsd-hardware.info/?probe=18da718e9e) | Jun 26, 2023 |
| Gigabyte      | H610I DDR4                  | Desktop     | [dea4808206](https://bsd-hardware.info/?probe=dea4808206) | Jun 24, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [d194e8bc0d](https://bsd-hardware.info/?probe=d194e8bc0d) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [6172c8b66f](https://bsd-hardware.info/?probe=6172c8b66f) | Jun 22, 2023 |
| ASRock        | H110M-ITX                   | Desktop     | [1180da18fb](https://bsd-hardware.info/?probe=1180da18fb) | Jun 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [29313e36c9](https://bsd-hardware.info/?probe=29313e36c9) | Jun 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [2cc06a4553](https://bsd-hardware.info/?probe=2cc06a4553) | Jun 18, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [43936f5f1c](https://bsd-hardware.info/?probe=43936f5f1c) | Jun 15, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [a380503321](https://bsd-hardware.info/?probe=a380503321) | Jun 11, 2023 |
| Sophos        | SG                          | Firewall    | [cde6f61458](https://bsd-hardware.info/?probe=cde6f61458) | Jun 08, 2023 |
| HP            | 18E7                        | Desktop     | [6daf82289e](https://bsd-hardware.info/?probe=6daf82289e) | Jun 07, 2023 |
| HP            | 18E7                        | Desktop     | [4ca0d96863](https://bsd-hardware.info/?probe=4ca0d96863) | Jun 03, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [c47f62b522](https://bsd-hardware.info/?probe=c47f62b522) | May 28, 2023 |
| HP            | 18E7                        | Desktop     | [5ab1548fe9](https://bsd-hardware.info/?probe=5ab1548fe9) | May 26, 2023 |
| HP            | 18E7                        | Desktop     | [a4d64c1a5e](https://bsd-hardware.info/?probe=a4d64c1a5e) | May 23, 2023 |
| HP            | 18E7                        | Desktop     | [f6986c366c](https://bsd-hardware.info/?probe=f6986c366c) | May 22, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [643f7277de](https://bsd-hardware.info/?probe=643f7277de) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [9e1f65bb29](https://bsd-hardware.info/?probe=9e1f65bb29) | May 18, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [c27d2cfe8b](https://bsd-hardware.info/?probe=c27d2cfe8b) | May 15, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [40b5182f45](https://bsd-hardware.info/?probe=40b5182f45) | May 15, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [819076e07f](https://bsd-hardware.info/?probe=819076e07f) | May 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [d678e62c0c](https://bsd-hardware.info/?probe=d678e62c0c) | May 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7b02526ba4](https://bsd-hardware.info/?probe=7b02526ba4) | May 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [488a5022ca](https://bsd-hardware.info/?probe=488a5022ca) | May 12, 2023 |
| Medion        | Major X10                   | Notebook    | [99228fd9da](https://bsd-hardware.info/?probe=99228fd9da) | May 10, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [5e5f24af1f](https://bsd-hardware.info/?probe=5e5f24af1f) | May 10, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [deb6e3ffa7](https://bsd-hardware.info/?probe=deb6e3ffa7) | May 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [8b403d4350](https://bsd-hardware.info/?probe=8b403d4350) | May 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [52110244c4](https://bsd-hardware.info/?probe=52110244c4) | May 07, 2023 |
| ASRock        | H110M-ITX                   | Desktop     | [5526aa67e8](https://bsd-hardware.info/?probe=5526aa67e8) | May 07, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [2745eadfd9](https://bsd-hardware.info/?probe=2745eadfd9) | May 07, 2023 |
| Intel         | D54250WYK H13922-303        | Desktop     | [f9366e2ccc](https://bsd-hardware.info/?probe=f9366e2ccc) | May 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [779f5f8827](https://bsd-hardware.info/?probe=779f5f8827) | Apr 30, 2023 |
| Intel         | D54250WYK H13922-303        | Desktop     | [4539fe8a93](https://bsd-hardware.info/?probe=4539fe8a93) | Apr 18, 2023 |
| ASUSTek       | P8H67-M EVO                 | Desktop     | [9d189f3b10](https://bsd-hardware.info/?probe=9d189f3b10) | Apr 18, 2023 |
| ASUSTek       | PRIME X299-A II             | Desktop     | [8c345e7a24](https://bsd-hardware.info/?probe=8c345e7a24) | Apr 14, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [b89912af4b](https://bsd-hardware.info/?probe=b89912af4b) | Apr 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [ab8a1de878](https://bsd-hardware.info/?probe=ab8a1de878) | Apr 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d3756c5ab8](https://bsd-hardware.info/?probe=d3756c5ab8) | Apr 09, 2023 |
| HP            | 18E7                        | Desktop     | [b9e5e9a352](https://bsd-hardware.info/?probe=b9e5e9a352) | Apr 05, 2023 |
| Protectli     | VP4650                      | Desktop     | [685cfdf67f](https://bsd-hardware.info/?probe=685cfdf67f) | Apr 05, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [9691b30e4d](https://bsd-hardware.info/?probe=9691b30e4d) | Apr 01, 2023 |
| Sophos        | SG                          | Firewall    | [350970e2eb](https://bsd-hardware.info/?probe=350970e2eb) | Apr 01, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [675bcfa82d](https://bsd-hardware.info/?probe=675bcfa82d) | Mar 29, 2023 |
| Dell          | Inspiron 7437               | Notebook    | [2c4de59558](https://bsd-hardware.info/?probe=2c4de59558) | Mar 27, 2023 |
| HP            | 2820h                       | Desktop     | [58d6933119](https://bsd-hardware.info/?probe=58d6933119) | Mar 26, 2023 |
| Lenovo        | 3102 SDK0J40700 WIN 3258... | Desktop     | [1ffbf45d40](https://bsd-hardware.info/?probe=1ffbf45d40) | Mar 19, 2023 |
| CNCTION-IA... | Unknown                     | Desktop     | [ba5de75eaa](https://bsd-hardware.info/?probe=ba5de75eaa) | Mar 19, 2023 |
| ASUSTek       | P6X58D-E                    | Desktop     | [ec05209185](https://bsd-hardware.info/?probe=ec05209185) | Mar 18, 2023 |
| Sophos        | SG                          | Firewall    | [c671946961](https://bsd-hardware.info/?probe=c671946961) | Mar 12, 2023 |
| Dell EMC      | VEP1425-V210-CPU A00        | Desktop     | [6faf4aed53](https://bsd-hardware.info/?probe=6faf4aed53) | Mar 11, 2023 |
| Notebook      | N2x0WU                      | Notebook    | [9545f36dee](https://bsd-hardware.info/?probe=9545f36dee) | Feb 27, 2023 |
| Supermicro    | X11SCL-IF                   | Server      | [febc7f7a94](https://bsd-hardware.info/?probe=febc7f7a94) | Feb 26, 2023 |
| HP            | 3031h                       | Desktop     | [7324a71ceb](https://bsd-hardware.info/?probe=7324a71ceb) | Feb 23, 2023 |
| Intel         | NUC11TNBi3 M11908-404       | Mini pc     | [6061a0f9c4](https://bsd-hardware.info/?probe=6061a0f9c4) | Feb 23, 2023 |
| Sophos        | SG                          | Firewall    | [b9fc0f3ba3](https://bsd-hardware.info/?probe=b9fc0f3ba3) | Feb 17, 2023 |
| HP            | 3398                        | Desktop     | [186e63e8fe](https://bsd-hardware.info/?probe=186e63e8fe) | Feb 15, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [f63a5598d7](https://bsd-hardware.info/?probe=f63a5598d7) | Feb 14, 2023 |
| HP            | 3031h                       | Desktop     | [cbbf836268](https://bsd-hardware.info/?probe=cbbf836268) | Feb 13, 2023 |
| Lenovo        | 319E SEK0T35577 IOT 4247... | Mini pc     | [708741a2f4](https://bsd-hardware.info/?probe=708741a2f4) | Feb 13, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [e0eac39f4a](https://bsd-hardware.info/?probe=e0eac39f4a) | Feb 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [a726812ab6](https://bsd-hardware.info/?probe=a726812ab6) | Feb 09, 2023 |
| Lenovo        | 319E SEK0T35577 IOT 4247... | Mini pc     | [865b492e94](https://bsd-hardware.info/?probe=865b492e94) | Feb 08, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [8083410c50](https://bsd-hardware.info/?probe=8083410c50) | Feb 06, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [62452eaaaa](https://bsd-hardware.info/?probe=62452eaaaa) | Feb 05, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [96df89832f](https://bsd-hardware.info/?probe=96df89832f) | Feb 04, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7d6cfe5543](https://bsd-hardware.info/?probe=7d6cfe5543) | Feb 04, 2023 |
| Gigabyte      | B150-HD3P-CF                | Desktop     | [fb5a559634](https://bsd-hardware.info/?probe=fb5a559634) | Feb 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [a7d54d41c8](https://bsd-hardware.info/?probe=a7d54d41c8) | Feb 02, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [efac696b1a](https://bsd-hardware.info/?probe=efac696b1a) | Jan 31, 2023 |
| PC Engines    | APU2                        | Desktop     | [2679b3584d](https://bsd-hardware.info/?probe=2679b3584d) | Jan 30, 2023 |
| Lenovo        | 319E SEK0T35577 IOT 4247... | Mini pc     | [09b0e5fc0e](https://bsd-hardware.info/?probe=09b0e5fc0e) | Jan 29, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [65ee58e34e](https://bsd-hardware.info/?probe=65ee58e34e) | Jan 28, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [88e42156af](https://bsd-hardware.info/?probe=88e42156af) | Jan 28, 2023 |
| CNCTION-IA... | Unknown                     | Desktop     | [b639f4670e](https://bsd-hardware.info/?probe=b639f4670e) | Jan 27, 2023 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [8537ac75a1](https://bsd-hardware.info/?probe=8537ac75a1) | Jan 26, 2023 |
| Google        | Cave                        | Notebook    | [76ac12f1e2](https://bsd-hardware.info/?probe=76ac12f1e2) | Jan 25, 2023 |
| ASRock        | X299E-ITX/ac                | Desktop     | [0b7dacf902](https://bsd-hardware.info/?probe=0b7dacf902) | Jan 25, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [17fd94a4c0](https://bsd-hardware.info/?probe=17fd94a4c0) | Jan 23, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [6b1a9b8d00](https://bsd-hardware.info/?probe=6b1a9b8d00) | Jan 21, 2023 |
| PC Engines    | APU2                        | Desktop     | [172844bd8b](https://bsd-hardware.info/?probe=172844bd8b) | Jan 21, 2023 |
| AZW           | SEi                         | Mini pc     | [362a33bd50](https://bsd-hardware.info/?probe=362a33bd50) | Jan 15, 2023 |
| Lenovo        | 3102 SDK0J40700 WIN 3258... | Desktop     | [9805fe9459](https://bsd-hardware.info/?probe=9805fe9459) | Jan 13, 2023 |
| Lenovo        | 3102 SDK0J40700 WIN 3258... | Desktop     | [1ec6c3acf2](https://bsd-hardware.info/?probe=1ec6c3acf2) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [335c3c990a](https://bsd-hardware.info/?probe=335c3c990a) | Jan 08, 2023 |
| Supermicro    | Super Server                | Server      | [841407deb7](https://bsd-hardware.info/?probe=841407deb7) | Jan 07, 2023 |
| Intel         | Milstead Platform           | Notebook    | [21ec3118ef](https://bsd-hardware.info/?probe=21ec3118ef) | Jan 02, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [7dc1fdfadb](https://bsd-hardware.info/?probe=7dc1fdfadb) | Jan 02, 2023 |
| Shuttle       | FH110                       | Desktop     | [3759d77a05](https://bsd-hardware.info/?probe=3759d77a05) | Dec 29, 2022 |
| Advantech     | UNO-2483G-474AE             | Desktop     | [d453f64b4f](https://bsd-hardware.info/?probe=d453f64b4f) | Dec 29, 2022 |
| Shuttle       | FH110                       | Desktop     | [be457c2796](https://bsd-hardware.info/?probe=be457c2796) | Dec 27, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8d3ab2cab5](https://bsd-hardware.info/?probe=8d3ab2cab5) | Dec 27, 2022 |
| Shuttle       | FH110                       | Desktop     | [a194756b95](https://bsd-hardware.info/?probe=a194756b95) | Dec 25, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [32207ea5d9](https://bsd-hardware.info/?probe=32207ea5d9) | Dec 19, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [f51b401c31](https://bsd-hardware.info/?probe=f51b401c31) | Dec 13, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [79b2a5d3a5](https://bsd-hardware.info/?probe=79b2a5d3a5) | Dec 08, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [575d201794](https://bsd-hardware.info/?probe=575d201794) | Dec 07, 2022 |
| Lenovo        | 319E SEK0T35577 IOT 4247... | Mini pc     | [33545a5181](https://bsd-hardware.info/?probe=33545a5181) | Dec 07, 2022 |
| Supermicro    | X10SLM+-LN4F                | Server      | [319819f81d](https://bsd-hardware.info/?probe=319819f81d) | Dec 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS5BU00    | Notebook    | [10619ac217](https://bsd-hardware.info/?probe=10619ac217) | Dec 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [32a4df9cae](https://bsd-hardware.info/?probe=32a4df9cae) | Dec 01, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [1d61d0cf62](https://bsd-hardware.info/?probe=1d61d0cf62) | Nov 29, 2022 |
| ASRockRack    | X470D4U                     | Desktop     | [38d7f55ef7](https://bsd-hardware.info/?probe=38d7f55ef7) | Nov 29, 2022 |
| Lenovo        | ThinkPad T430 2347G7G       | Notebook    | [640540cd67](https://bsd-hardware.info/?probe=640540cd67) | Nov 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e40278b06](https://bsd-hardware.info/?probe=4e40278b06) | Nov 28, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [20058331ef](https://bsd-hardware.info/?probe=20058331ef) | Nov 19, 2022 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [7bfffa2718](https://bsd-hardware.info/?probe=7bfffa2718) | Nov 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0989913192](https://bsd-hardware.info/?probe=0989913192) | Nov 12, 2022 |
| Sophos        | SG                          | Firewall    | [cab7a59023](https://bsd-hardware.info/?probe=cab7a59023) | Oct 30, 2022 |
| Sophos        | SG                          | Firewall    | [01f57abe1b](https://bsd-hardware.info/?probe=01f57abe1b) | Oct 29, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [521283b723](https://bsd-hardware.info/?probe=521283b723) | Oct 22, 2022 |
| HP            | 8719                        | Desktop     | [6bca1a0466](https://bsd-hardware.info/?probe=6bca1a0466) | Oct 22, 2022 |
| HP            | 8719                        | Desktop     | [87efb126fc](https://bsd-hardware.info/?probe=87efb126fc) | Oct 16, 2022 |
| NU941         | 1.0                         | Desktop     | [2690c2a8df](https://bsd-hardware.info/?probe=2690c2a8df) | Oct 10, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [58def8d407](https://bsd-hardware.info/?probe=58def8d407) | Oct 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e021d720f](https://bsd-hardware.info/?probe=4e021d720f) | Oct 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [050c365fcd](https://bsd-hardware.info/?probe=050c365fcd) | Sep 17, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [7bf7249432](https://bsd-hardware.info/?probe=7bf7249432) | Sep 16, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [ad70ccea4d](https://bsd-hardware.info/?probe=ad70ccea4d) | Sep 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [13ec5a6f20](https://bsd-hardware.info/?probe=13ec5a6f20) | Sep 14, 2022 |
| Dell EMC      | VEP1425-V210-CPU A00        | Desktop     | [871a29677b](https://bsd-hardware.info/?probe=871a29677b) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7S2LT00    | Notebook    | [5104875f94](https://bsd-hardware.info/?probe=5104875f94) | Sep 06, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [88d8df1e3a](https://bsd-hardware.info/?probe=88d8df1e3a) | Sep 03, 2022 |
| Dell          | 0DVNTK A00                  | Mini pc     | [216197e933](https://bsd-hardware.info/?probe=216197e933) | Sep 03, 2022 |
| MSI           | H410M-A PRO                 | Desktop     | [d71ca3999c](https://bsd-hardware.info/?probe=d71ca3999c) | Sep 02, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [05bb23ae87](https://bsd-hardware.info/?probe=05bb23ae87) | Aug 26, 2022 |
| Dell          | PowerEdge R620              | Desktop     | [66db9eb745](https://bsd-hardware.info/?probe=66db9eb745) | Aug 25, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [5280e7a6d2](https://bsd-hardware.info/?probe=5280e7a6d2) | Aug 18, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [9ac038fe9d](https://bsd-hardware.info/?probe=9ac038fe9d) | Aug 17, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [28929cae10](https://bsd-hardware.info/?probe=28929cae10) | Aug 17, 2022 |
| PC Engines    | APU2                        | Desktop     | [beb01b4e9c](https://bsd-hardware.info/?probe=beb01b4e9c) | Aug 06, 2022 |
| HP            | 8266                        | Desktop     | [a204146221](https://bsd-hardware.info/?probe=a204146221) | Aug 04, 2022 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [f346b8d7f0](https://bsd-hardware.info/?probe=f346b8d7f0) | Aug 02, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [ad56307789](https://bsd-hardware.info/?probe=ad56307789) | Aug 01, 2022 |
| Gigabyte      | H310M S2H                   | Desktop     | [03d0919731](https://bsd-hardware.info/?probe=03d0919731) | Jul 29, 2022 |
| Deciso        | Netboard A10                | Desktop     | [3f548f31e3](https://bsd-hardware.info/?probe=3f548f31e3) | Jul 25, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [6daa6d0060](https://bsd-hardware.info/?probe=6daa6d0060) | Jul 24, 2022 |
| Lenovo        | ThinkPad X61s 76693KG       | Notebook    | [445446cc28](https://bsd-hardware.info/?probe=445446cc28) | Jul 18, 2022 |
| Protectli     | FW4B                        | Desktop     | [b1ac4ad0dd](https://bsd-hardware.info/?probe=b1ac4ad0dd) | Jul 18, 2022 |
| ASUSTek       | X751LB                      | Notebook    | [5c2ef28301](https://bsd-hardware.info/?probe=5c2ef28301) | Jul 12, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [d680e0d05d](https://bsd-hardware.info/?probe=d680e0d05d) | Jul 10, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [d48d3e4777](https://bsd-hardware.info/?probe=d48d3e4777) | Jul 05, 2022 |
| Star Labs     | LabTop                      | Notebook    | [390c4c4d55](https://bsd-hardware.info/?probe=390c4c4d55) | Jul 03, 2022 |
| Protectli     | FW4B                        | Desktop     | [c4e6db8739](https://bsd-hardware.info/?probe=c4e6db8739) | Jul 03, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [a76b64487b](https://bsd-hardware.info/?probe=a76b64487b) | Jul 01, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [9f33082ffa](https://bsd-hardware.info/?probe=9f33082ffa) | Jun 08, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [ff3865e01f](https://bsd-hardware.info/?probe=ff3865e01f) | Jun 05, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [4be827d8fe](https://bsd-hardware.info/?probe=4be827d8fe) | Jun 01, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [5893942a80](https://bsd-hardware.info/?probe=5893942a80) | May 30, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [ade09344b8](https://bsd-hardware.info/?probe=ade09344b8) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [cc37ea1b7d](https://bsd-hardware.info/?probe=cc37ea1b7d) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [abacee12a9](https://bsd-hardware.info/?probe=abacee12a9) | May 26, 2022 |
| Unknown       | Raspberry Pi 3 Model B P... | Desktop     | [21fa41e4c1](https://bsd-hardware.info/?probe=21fa41e4c1) | May 26, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [3dc5a6f7d2](https://bsd-hardware.info/?probe=3dc5a6f7d2) | May 24, 2022 |
| Dell          | Latitude E7240              | Notebook    | [970234b430](https://bsd-hardware.info/?probe=970234b430) | May 22, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [b9350aeb55](https://bsd-hardware.info/?probe=b9350aeb55) | May 21, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [5cc0eb3e94](https://bsd-hardware.info/?probe=5cc0eb3e94) | May 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [66432302a4](https://bsd-hardware.info/?probe=66432302a4) | May 07, 2022 |
| PC Engines    | APU2                        | Desktop     | [26be7dfcb8](https://bsd-hardware.info/?probe=26be7dfcb8) | Apr 28, 2022 |
| PC Engines    | APU2                        | Desktop     | [4405a65be4](https://bsd-hardware.info/?probe=4405a65be4) | Apr 28, 2022 |
| PC Engines    | APU2                        | Desktop     | [3fe99889aa](https://bsd-hardware.info/?probe=3fe99889aa) | Apr 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [095a279c7b](https://bsd-hardware.info/?probe=095a279c7b) | Apr 25, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [4e7d57df3b](https://bsd-hardware.info/?probe=4e7d57df3b) | Apr 18, 2022 |
| HP            | 1998                        | Desktop     | [4f15447536](https://bsd-hardware.info/?probe=4f15447536) | Apr 18, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [c78d18300d](https://bsd-hardware.info/?probe=c78d18300d) | Apr 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [f58e088df2](https://bsd-hardware.info/?probe=f58e088df2) | Apr 16, 2022 |
| Sony          | SVZ1311C5E                  | Notebook    | [c1c429a7e6](https://bsd-hardware.info/?probe=c1c429a7e6) | Apr 15, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [87306109c8](https://bsd-hardware.info/?probe=87306109c8) | Apr 11, 2022 |
| Protectli     | FW6D                        | Desktop     | [e79304e1dc](https://bsd-hardware.info/?probe=e79304e1dc) | Apr 07, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [99343fc0da](https://bsd-hardware.info/?probe=99343fc0da) | Apr 06, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [7db1501c5c](https://bsd-hardware.info/?probe=7db1501c5c) | Apr 06, 2022 |
| ASRock        | H61DE/S3                    | Desktop     | [00183a69ec](https://bsd-hardware.info/?probe=00183a69ec) | Apr 05, 2022 |
| Lenovo        | 319E SEK0T35577 IOT 4247... | Mini pc     | [634f184200](https://bsd-hardware.info/?probe=634f184200) | Apr 05, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [1ef10e5e36](https://bsd-hardware.info/?probe=1ef10e5e36) | Apr 03, 2022 |
| Supermicro    | X12STL-IF                   | Server      | [87912d52e4](https://bsd-hardware.info/?probe=87912d52e4) | Mar 28, 2022 |
| PC Engines    | apu4                        | Desktop     | [618b2c7955](https://bsd-hardware.info/?probe=618b2c7955) | Mar 27, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [a1700b0347](https://bsd-hardware.info/?probe=a1700b0347) | Mar 21, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [671c66ca19](https://bsd-hardware.info/?probe=671c66ca19) | Mar 21, 2022 |
| Protectli     | FW4B                        | Desktop     | [5323027ba0](https://bsd-hardware.info/?probe=5323027ba0) | Mar 13, 2022 |
| Dell          | 03X6X0 A01                  | Server      | [00ccb7abb3](https://bsd-hardware.info/?probe=00ccb7abb3) | Mar 08, 2022 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [ec336ddab4](https://bsd-hardware.info/?probe=ec336ddab4) | Mar 08, 2022 |
| Supermicro    | X12STL-IF                   | Server      | [5054f03888](https://bsd-hardware.info/?probe=5054f03888) | Mar 06, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [19ed08c39c](https://bsd-hardware.info/?probe=19ed08c39c) | Mar 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [c91c5fe588](https://bsd-hardware.info/?probe=c91c5fe588) | Mar 03, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [c6caefebe6](https://bsd-hardware.info/?probe=c6caefebe6) | Feb 28, 2022 |
| Supermicro    | M11SDV-8C-LN4F              | Desktop     | [e4f7f31828](https://bsd-hardware.info/?probe=e4f7f31828) | Feb 28, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [74f28d34fd](https://bsd-hardware.info/?probe=74f28d34fd) | Feb 27, 2022 |
| Sophos        | XG                          | Firewall    | [44c92baffd](https://bsd-hardware.info/?probe=44c92baffd) | Feb 22, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [a5a8c71167](https://bsd-hardware.info/?probe=a5a8c71167) | Feb 18, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [64ccf1e6a0](https://bsd-hardware.info/?probe=64ccf1e6a0) | Feb 18, 2022 |
| Dell          | 05KX61 A02                  | Server      | [5e72ec3104](https://bsd-hardware.info/?probe=5e72ec3104) | Feb 17, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [f3444924fd](https://bsd-hardware.info/?probe=f3444924fd) | Feb 17, 2022 |
| Lenovo        | ThinkPad X250 20CLS59400    | Notebook    | [92333ad60b](https://bsd-hardware.info/?probe=92333ad60b) | Feb 17, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [f259f73c17](https://bsd-hardware.info/?probe=f259f73c17) | Feb 14, 2022 |
| CompuLab      | uSVR                        | Mini pc     | [9afa228b2a](https://bsd-hardware.info/?probe=9afa228b2a) | Feb 12, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [91870de9fe](https://bsd-hardware.info/?probe=91870de9fe) | Feb 06, 2022 |
| MSI           | H81I                        | Desktop     | [fe3a834f0b](https://bsd-hardware.info/?probe=fe3a834f0b) | Feb 05, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [f785bcb17a](https://bsd-hardware.info/?probe=f785bcb17a) | Feb 04, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [96436a1882](https://bsd-hardware.info/?probe=96436a1882) | Feb 03, 2022 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [f13e7340b1](https://bsd-hardware.info/?probe=f13e7340b1) | Jan 30, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [cb50949dca](https://bsd-hardware.info/?probe=cb50949dca) | Jan 28, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [c7ef0e518f](https://bsd-hardware.info/?probe=c7ef0e518f) | Jan 27, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [04afa3aa4f](https://bsd-hardware.info/?probe=04afa3aa4f) | Jan 23, 2022 |
| Dell          | 03X6X0 A01                  | Server      | [1c3abdddf5](https://bsd-hardware.info/?probe=1c3abdddf5) | Jan 19, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [e795c7ec91](https://bsd-hardware.info/?probe=e795c7ec91) | Jan 17, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [d09cf2e0a7](https://bsd-hardware.info/?probe=d09cf2e0a7) | Jan 14, 2022 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [462b721778](https://bsd-hardware.info/?probe=462b721778) | Jan 11, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [877bb1b29f](https://bsd-hardware.info/?probe=877bb1b29f) | Jan 10, 2022 |
| Unknown       | Unknown                     | Notebook    | [974e1f4e5e](https://bsd-hardware.info/?probe=974e1f4e5e) | Jan 07, 2022 |
| MSI           | H61I-E35 V2/W8              | Desktop     | [8ae05f9d72](https://bsd-hardware.info/?probe=8ae05f9d72) | Jan 05, 2022 |
| XtReAmEr      | Unknown                     | Desktop     | [bd1315aa70](https://bsd-hardware.info/?probe=bd1315aa70) | Jan 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [0efa2c0531](https://bsd-hardware.info/?probe=0efa2c0531) | Dec 31, 2021 |
| Dell          | 0F9NPY A02                  | Server      | [1e0e3c3739](https://bsd-hardware.info/?probe=1e0e3c3739) | Dec 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [79370c33df](https://bsd-hardware.info/?probe=79370c33df) | Dec 28, 2021 |
| Dell          | 03X6X0 A03                  | Server      | [2a59c1bfa2](https://bsd-hardware.info/?probe=2a59c1bfa2) | Dec 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [c5e31aaf52](https://bsd-hardware.info/?probe=c5e31aaf52) | Dec 28, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [30aab74fbc](https://bsd-hardware.info/?probe=30aab74fbc) | Dec 24, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [6b03a2c4c2](https://bsd-hardware.info/?probe=6b03a2c4c2) | Dec 22, 2021 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [6529da52dc](https://bsd-hardware.info/?probe=6529da52dc) | Dec 21, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [69bf80f0c6](https://bsd-hardware.info/?probe=69bf80f0c6) | Dec 20, 2021 |
| Unknown       | Raspberry Pi 3 Model B P... | Desktop     | [ef0dcfaccf](https://bsd-hardware.info/?probe=ef0dcfaccf) | Dec 20, 2021 |
| TOXIC by B... | 15CL872 1050TI              | Notebook    | [0a1683170a](https://bsd-hardware.info/?probe=0a1683170a) | Dec 20, 2021 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [b099f26b73](https://bsd-hardware.info/?probe=b099f26b73) | Dec 20, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [17cad87a0d](https://bsd-hardware.info/?probe=17cad87a0d) | Dec 19, 2021 |
| PC Engines    | apu4                        | Desktop     | [f72343bec1](https://bsd-hardware.info/?probe=f72343bec1) | Dec 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [cd27dd3e2b](https://bsd-hardware.info/?probe=cd27dd3e2b) | Dec 17, 2021 |
| Lenovo        | ThinkPad A285 20MW000JMH    | Notebook    | [ff53f0763c](https://bsd-hardware.info/?probe=ff53f0763c) | Dec 12, 2021 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [fd05f5bf41](https://bsd-hardware.info/?probe=fd05f5bf41) | Dec 11, 2021 |
| HP            | 8105                        | Desktop     | [e38c91e91e](https://bsd-hardware.info/?probe=e38c91e91e) | Dec 11, 2021 |
| HP            | 8105                        | Desktop     | [0b923d55bc](https://bsd-hardware.info/?probe=0b923d55bc) | Dec 11, 2021 |
| Sophos        | XG                          | Firewall    | [59485a80e1](https://bsd-hardware.info/?probe=59485a80e1) | Dec 11, 2021 |
| Protectli     | FW6D                        | Desktop     | [33731d5933](https://bsd-hardware.info/?probe=33731d5933) | Dec 11, 2021 |
| Apple         | MacBookAir1,1               | Notebook    | [61c7028e83](https://bsd-hardware.info/?probe=61c7028e83) | Dec 07, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [5dbff17614](https://bsd-hardware.info/?probe=5dbff17614) | Dec 06, 2021 |
| Unknown       | Raspberry Pi 3 Model B P... | Desktop     | [646ca92a69](https://bsd-hardware.info/?probe=646ca92a69) | Dec 06, 2021 |
| Alienware     | 01NYPT A00                  | Desktop     | [75aa0c00fb](https://bsd-hardware.info/?probe=75aa0c00fb) | Dec 06, 2021 |
| TOXIC by B... | 15CL872 1050TI              | Notebook    | [4fbb430947](https://bsd-hardware.info/?probe=4fbb430947) | Dec 05, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [b77016bee5](https://bsd-hardware.info/?probe=b77016bee5) | Nov 25, 2021 |
| Dell          | 01V648 A04                  | Server      | [0f0265d958](https://bsd-hardware.info/?probe=0f0265d958) | Nov 25, 2021 |
| ASRock        | IMB-195                     | Desktop     | [58e7426808](https://bsd-hardware.info/?probe=58e7426808) | Nov 24, 2021 |
| Lenovo        | ThinkPad T430 2347G7G       | Notebook    | [66c64c1af9](https://bsd-hardware.info/?probe=66c64c1af9) | Nov 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [2276cb5406](https://bsd-hardware.info/?probe=2276cb5406) | Nov 20, 2021 |
| HP            | 339A                        | Desktop     | [a123d76249](https://bsd-hardware.info/?probe=a123d76249) | Nov 19, 2021 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [1486dc195e](https://bsd-hardware.info/?probe=1486dc195e) | Nov 17, 2021 |
| HP            | 1497                        | Desktop     | [24a8d1bb7a](https://bsd-hardware.info/?probe=24a8d1bb7a) | Nov 17, 2021 |
| PC Engines    | APU                         | Desktop     | [ca05f41685](https://bsd-hardware.info/?probe=ca05f41685) | Nov 16, 2021 |
| Dell          | 0R230R A00                  | Desktop     | [c2c6cf4b4d](https://bsd-hardware.info/?probe=c2c6cf4b4d) | Nov 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [c473c704a9](https://bsd-hardware.info/?probe=c473c704a9) | Nov 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [ec7dfabb51](https://bsd-hardware.info/?probe=ec7dfabb51) | Nov 12, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [04cc56305c](https://bsd-hardware.info/?probe=04cc56305c) | Nov 11, 2021 |
| Protectli     | FW4B                        | Desktop     | [cb7b87cd57](https://bsd-hardware.info/?probe=cb7b87cd57) | Nov 09, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [6f779d5170](https://bsd-hardware.info/?probe=6f779d5170) | Nov 03, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [72f0937505](https://bsd-hardware.info/?probe=72f0937505) | Nov 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [f80c884b6f](https://bsd-hardware.info/?probe=f80c884b6f) | Oct 31, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [e4958e59b0](https://bsd-hardware.info/?probe=e4958e59b0) | Oct 29, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [70da799fd0](https://bsd-hardware.info/?probe=70da799fd0) | Oct 25, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [bc4b7f33d5](https://bsd-hardware.info/?probe=bc4b7f33d5) | Oct 25, 2021 |
| Supermicro    | M11SDV-8C-LN4F              | Desktop     | [54c792ac8a](https://bsd-hardware.info/?probe=54c792ac8a) | Oct 20, 2021 |
| Barracuda ... | Barracuda NG Firewall F1... | Firewall    | [9ed491d56a](https://bsd-hardware.info/?probe=9ed491d56a) | Oct 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [67e62d9dd3](https://bsd-hardware.info/?probe=67e62d9dd3) | Oct 11, 2021 |
| Unknown       | Unknown                     | Desktop     | [b3b0308132](https://bsd-hardware.info/?probe=b3b0308132) | Oct 02, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [712bbd0635](https://bsd-hardware.info/?probe=712bbd0635) | Sep 29, 2021 |
| Protectli     | FW6D                        | Desktop     | [ee70d4b2fe](https://bsd-hardware.info/?probe=ee70d4b2fe) | Sep 25, 2021 |
| MSI           | H61I-E35 V2/W8              | Desktop     | [359cb66936](https://bsd-hardware.info/?probe=359cb66936) | Sep 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1afa203e69](https://bsd-hardware.info/?probe=1afa203e69) | Sep 22, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | Desktop     | [ea8fefdf4e](https://bsd-hardware.info/?probe=ea8fefdf4e) | Sep 20, 2021 |
| Shuttle       | XH310V2                     | Desktop     | [f37b485384](https://bsd-hardware.info/?probe=f37b485384) | Sep 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [ba40cc9f75](https://bsd-hardware.info/?probe=ba40cc9f75) | Sep 17, 2021 |
| HP            | 8103 A01                    | Mini pc     | [860e4a3d12](https://bsd-hardware.info/?probe=860e4a3d12) | Sep 16, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [70d35afae8](https://bsd-hardware.info/?probe=70d35afae8) | Sep 15, 2021 |
| Sapphire      | EDGE-FT1M1 E450 1AOVU044    | Desktop     | [85ed325446](https://bsd-hardware.info/?probe=85ed325446) | Sep 11, 2021 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | Desktop     | [0510213747](https://bsd-hardware.info/?probe=0510213747) | Aug 30, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [b3a20bafca](https://bsd-hardware.info/?probe=b3a20bafca) | Aug 29, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [03e08762a6](https://bsd-hardware.info/?probe=03e08762a6) | Aug 27, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [36e36edb7a](https://bsd-hardware.info/?probe=36e36edb7a) | Aug 24, 2021 |
| Shuttle       | DH370                       | Desktop     | [dea088a5bd](https://bsd-hardware.info/?probe=dea088a5bd) | Aug 20, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [ad6b718b92](https://bsd-hardware.info/?probe=ad6b718b92) | Aug 20, 2021 |
| Protectli     | FW4B                        | Desktop     | [ab6695bb0b](https://bsd-hardware.info/?probe=ab6695bb0b) | Aug 18, 2021 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [e057495ca3](https://bsd-hardware.info/?probe=e057495ca3) | Aug 14, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [e9335d8295](https://bsd-hardware.info/?probe=e9335d8295) | Aug 13, 2021 |
| HP            | 625                         | Notebook    | [606d75e6a1](https://bsd-hardware.info/?probe=606d75e6a1) | Aug 11, 2021 |
| HP            | 213D A01                    | Desktop     | [6e52020062](https://bsd-hardware.info/?probe=6e52020062) | Aug 10, 2021 |
| Shuttle       | DH370                       | Desktop     | [6d81fef4fb](https://bsd-hardware.info/?probe=6d81fef4fb) | Aug 09, 2021 |
| Unknown       | Unknown                     | Desktop     | [164b888dbe](https://bsd-hardware.info/?probe=164b888dbe) | Aug 08, 2021 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [0ad676c6a9](https://bsd-hardware.info/?probe=0ad676c6a9) | Aug 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [d4122c5eb0](https://bsd-hardware.info/?probe=d4122c5eb0) | Aug 03, 2021 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [4253ffb8fb](https://bsd-hardware.info/?probe=4253ffb8fb) | Aug 02, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [a6de85de91](https://bsd-hardware.info/?probe=a6de85de91) | Jul 29, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1e337fe131](https://bsd-hardware.info/?probe=1e337fe131) | Jul 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [dd66bc21f6](https://bsd-hardware.info/?probe=dd66bc21f6) | Jul 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [b7edcfabb6](https://bsd-hardware.info/?probe=b7edcfabb6) | Jul 25, 2021 |
| Lenovo        | ThinkPad X230 2325IG2       | Notebook    | [158ecc5e0b](https://bsd-hardware.info/?probe=158ecc5e0b) | Jul 14, 2021 |
| PC Engines    | apu4                        | Desktop     | [027bbc5028](https://bsd-hardware.info/?probe=027bbc5028) | Jul 14, 2021 |
| HP            | 18E9                        | Desktop     | [7bac3be335](https://bsd-hardware.info/?probe=7bac3be335) | Jun 29, 2021 |
| Dell EMC      | VEP1425-V210-CPU A00        | Desktop     | [ad34d48259](https://bsd-hardware.info/?probe=ad34d48259) | Jun 27, 2021 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [5f46ba6832](https://bsd-hardware.info/?probe=5f46ba6832) | Jun 26, 2021 |
| Dell          | 0WR7PY A02                  | Desktop     | [ad5db0563f](https://bsd-hardware.info/?probe=ad5db0563f) | Jun 26, 2021 |
| Lenovo        | Yoga 500-14IBD 80N4         | Notebook    | [9fda78d739](https://bsd-hardware.info/?probe=9fda78d739) | Jun 23, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [46dca136f6](https://bsd-hardware.info/?probe=46dca136f6) | Jun 21, 2021 |
| WYSE          | Z CLASS                     | Notebook    | [571fdbf390](https://bsd-hardware.info/?probe=571fdbf390) | Jun 19, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ee8a47b051](https://bsd-hardware.info/?probe=ee8a47b051) | Jun 17, 2021 |
| HP            | 3397                        | Desktop     | [3dd97c60ca](https://bsd-hardware.info/?probe=3dd97c60ca) | Jun 16, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [9ae8146589](https://bsd-hardware.info/?probe=9ae8146589) | Jun 15, 2021 |
| Dell          | Latitude E4300              | Notebook    | [7855973957](https://bsd-hardware.info/?probe=7855973957) | Jun 12, 2021 |
| SLIMBOOK      | Unknown                     | Notebook    | [80a9ba918e](https://bsd-hardware.info/?probe=80a9ba918e) | Jun 11, 2021 |
| MSI           | B85M-P33 V2                 | Desktop     | [0633d1c78e](https://bsd-hardware.info/?probe=0633d1c78e) | Jun 10, 2021 |
| Dell          | 03X6X0 A02                  | Server      | [deb193d10f](https://bsd-hardware.info/?probe=deb193d10f) | Jun 10, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [db12a78352](https://bsd-hardware.info/?probe=db12a78352) | Jun 08, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [9a7adb8860](https://bsd-hardware.info/?probe=9a7adb8860) | Jun 06, 2021 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [4607d1410c](https://bsd-hardware.info/?probe=4607d1410c) | May 31, 2021 |
| Inventec      | R CLASS A02                 | Desktop     | [b621aeaac3](https://bsd-hardware.info/?probe=b621aeaac3) | May 30, 2021 |
| Gigabyte      | B85-HD3                     | Desktop     | [331da3091c](https://bsd-hardware.info/?probe=331da3091c) | May 28, 2021 |
| Dell          | 0200DY A02                  | Desktop     | [fcbfbc2dfa](https://bsd-hardware.info/?probe=fcbfbc2dfa) | May 25, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [8448df79cd](https://bsd-hardware.info/?probe=8448df79cd) | May 21, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [594c0438a0](https://bsd-hardware.info/?probe=594c0438a0) | May 21, 2021 |
| Notebook      | NL5xRU                      | Notebook    | [792fb07dd9](https://bsd-hardware.info/?probe=792fb07dd9) | May 10, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [add2c1bcba](https://bsd-hardware.info/?probe=add2c1bcba) | May 09, 2021 |
| Dell          | 03X6X0 A03                  | Server      | [d6312ecf58](https://bsd-hardware.info/?probe=d6312ecf58) | May 09, 2021 |
| Shuttle       | FH87                        | Desktop     | [bf5457ff02](https://bsd-hardware.info/?probe=bf5457ff02) | May 09, 2021 |
| Dell          | 0FJ030                      | Desktop     | [91418a4965](https://bsd-hardware.info/?probe=91418a4965) | Apr 30, 2021 |
| Dell          | 0FJ030                      | Desktop     | [7bee24ee8a](https://bsd-hardware.info/?probe=7bee24ee8a) | Apr 30, 2021 |
| Dell          | 0FJ030                      | Desktop     | [d5277ad9e1](https://bsd-hardware.info/?probe=d5277ad9e1) | Apr 30, 2021 |
| Dell          | 0FJ030                      | Desktop     | [63b1980830](https://bsd-hardware.info/?probe=63b1980830) | Apr 30, 2021 |
| HP            | 1998                        | Desktop     | [f6b53096d4](https://bsd-hardware.info/?probe=f6b53096d4) | Apr 28, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [a90eea4001](https://bsd-hardware.info/?probe=a90eea4001) | Apr 27, 2021 |
| HP            | 1497                        | Desktop     | [26724735db](https://bsd-hardware.info/?probe=26724735db) | Apr 24, 2021 |
| HP            | 1998                        | Desktop     | [051c63e153](https://bsd-hardware.info/?probe=051c63e153) | Apr 24, 2021 |
| ASRock        | J4105-ITX                   | Desktop     | [66eee76b50](https://bsd-hardware.info/?probe=66eee76b50) | Apr 21, 2021 |
| Dell          | 0F9NPY A02                  | Server      | [4ebcbdc297](https://bsd-hardware.info/?probe=4ebcbdc297) | Apr 20, 2021 |
| HP            | 1998                        | Desktop     | [7207f742d6](https://bsd-hardware.info/?probe=7207f742d6) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [634521b082](https://bsd-hardware.info/?probe=634521b082) | Apr 07, 2021 |
| Barracuda ... | Barracuda NG Firewall F1... | Firewall    | [31caab92cf](https://bsd-hardware.info/?probe=31caab92cf) | Apr 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [15e5f7932e](https://bsd-hardware.info/?probe=15e5f7932e) | Apr 06, 2021 |
| PC Engines    | apu4                        | Desktop     | [06a59860a8](https://bsd-hardware.info/?probe=06a59860a8) | Apr 04, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [b644ed3914](https://bsd-hardware.info/?probe=b644ed3914) | Mar 31, 2021 |
| Dell          | 0200DY A02                  | Desktop     | [060ebba6d2](https://bsd-hardware.info/?probe=060ebba6d2) | Mar 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [4376accb5e](https://bsd-hardware.info/?probe=4376accb5e) | Mar 29, 2021 |
| MSI           | H410M-A PRO                 | Desktop     | [88f2766975](https://bsd-hardware.info/?probe=88f2766975) | Mar 27, 2021 |
| Lenovo        | ThinkPad X230 23255Y4       | Notebook    | [ab871769f0](https://bsd-hardware.info/?probe=ab871769f0) | Mar 27, 2021 |
| Dell          | 0DRR0P A00                  | Server      | [ebc09e92eb](https://bsd-hardware.info/?probe=ebc09e92eb) | Mar 26, 2021 |
| Shuttle       | FS310                       | Desktop     | [6514807d96](https://bsd-hardware.info/?probe=6514807d96) | Mar 25, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | Notebook    | [d856b5bf95](https://bsd-hardware.info/?probe=d856b5bf95) | Mar 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [4c06c1a897](https://bsd-hardware.info/?probe=4c06c1a897) | Mar 23, 2021 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [b8f568202d](https://bsd-hardware.info/?probe=b8f568202d) | Mar 22, 2021 |
| Dell          | Latitude E7270              | Notebook    | [5ba79f9aa5](https://bsd-hardware.info/?probe=5ba79f9aa5) | Mar 19, 2021 |
| HP            | ProLiant DL360 Gen9         | Desktop     | [b283b34881](https://bsd-hardware.info/?probe=b283b34881) | Mar 17, 2021 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [d5a1acb61b](https://bsd-hardware.info/?probe=d5a1acb61b) | Mar 17, 2021 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [21d6db75f5](https://bsd-hardware.info/?probe=21d6db75f5) | Mar 17, 2021 |
| HP            | ProLiant DL120 Gen9         | Server      | [533b1e078e](https://bsd-hardware.info/?probe=533b1e078e) | Mar 17, 2021 |
| Fujitsu       | D3279-H1 S26361-D3279-H1... | Server      | [7a9d95b303](https://bsd-hardware.info/?probe=7a9d95b303) | Mar 17, 2021 |
| Supermicro    | Super Server                | Server      | [ec1e532ea9](https://bsd-hardware.info/?probe=ec1e532ea9) | Mar 17, 2021 |
| Lenovo        | ThinkPad X280 20KESA000B    | Notebook    | [e2b586d597](https://bsd-hardware.info/?probe=e2b586d597) | Mar 17, 2021 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [fa0e0228a3](https://bsd-hardware.info/?probe=fa0e0228a3) | Mar 17, 2021 |
| iEi           | E452 V1.00                  | Desktop     | [b5665d0df2](https://bsd-hardware.info/?probe=b5665d0df2) | Mar 17, 2021 |
| HP            | ProLiant DL360 Gen9         | Desktop     | [bf440e72a1](https://bsd-hardware.info/?probe=bf440e72a1) | Mar 17, 2021 |
| HP            | EliteDesk 800 G5 SFF        | Desktop     | [aaf9bc1c12](https://bsd-hardware.info/?probe=aaf9bc1c12) | Mar 17, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [6e0891ce80](https://bsd-hardware.info/?probe=6e0891ce80) | Mar 17, 2021 |
| Dell          | 0F9NPY A02                  | Server      | [ff4d8d8eca](https://bsd-hardware.info/?probe=ff4d8d8eca) | Mar 16, 2021 |
| Dell          | 0F9NPY A02                  | Server      | [cb3c1ad90e](https://bsd-hardware.info/?probe=cb3c1ad90e) | Mar 16, 2021 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [ee59c99fe4](https://bsd-hardware.info/?probe=ee59c99fe4) | Mar 15, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [359c03f28d](https://bsd-hardware.info/?probe=359c03f28d) | Mar 12, 2021 |
| HP            | 18E9                        | Desktop     | [cc435f4cd1](https://bsd-hardware.info/?probe=cc435f4cd1) | Mar 10, 2021 |
| Unknown       | Unknown                     | Desktop     | [2093895427](https://bsd-hardware.info/?probe=2093895427) | Mar 10, 2021 |
| Lenovo        | ThinkPad X200s 7470W1V      | Notebook    | [926fe13d8f](https://bsd-hardware.info/?probe=926fe13d8f) | Mar 09, 2021 |
| ASUSTek       | X556UA                      | Notebook    | [57018edd10](https://bsd-hardware.info/?probe=57018edd10) | Mar 07, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [f30a9505dd](https://bsd-hardware.info/?probe=f30a9505dd) | Mar 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [2abc226441](https://bsd-hardware.info/?probe=2abc226441) | Mar 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [60e0b1d346](https://bsd-hardware.info/?probe=60e0b1d346) | Mar 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [db37dfcbf3](https://bsd-hardware.info/?probe=db37dfcbf3) | Mar 02, 2021 |
| MSI           | H410M-A PRO                 | Desktop     | [64bf9eb4cf](https://bsd-hardware.info/?probe=64bf9eb4cf) | Mar 01, 2021 |
| MSI           | H410M-A PRO                 | Desktop     | [eacaff1fff](https://bsd-hardware.info/?probe=eacaff1fff) | Feb 28, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [47c08e3817](https://bsd-hardware.info/?probe=47c08e3817) | Feb 27, 2021 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [9901302790](https://bsd-hardware.info/?probe=9901302790) | Feb 27, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [441133db7f](https://bsd-hardware.info/?probe=441133db7f) | Feb 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [1008505c8a](https://bsd-hardware.info/?probe=1008505c8a) | Feb 23, 2021 |
| MSI           | H410M-A PRO                 | Desktop     | [7d9e05b2fd](https://bsd-hardware.info/?probe=7d9e05b2fd) | Feb 21, 2021 |
| MSI           | H410M-A PRO                 | Desktop     | [408ba48f1f](https://bsd-hardware.info/?probe=408ba48f1f) | Feb 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [6c0a1e1154](https://bsd-hardware.info/?probe=6c0a1e1154) | Feb 20, 2021 |
| Supermicro    | X8SIL                       | Desktop     | [6318953f01](https://bsd-hardware.info/?probe=6318953f01) | Feb 18, 2021 |
| Dell          | Latitude E4300              | Notebook    | [d5051ef185](https://bsd-hardware.info/?probe=d5051ef185) | Feb 16, 2021 |
| Supermicro    | X9SCL/X9SCM                 | Desktop     | [a57dba0cb2](https://bsd-hardware.info/?probe=a57dba0cb2) | Feb 16, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [8bfcff9039](https://bsd-hardware.info/?probe=8bfcff9039) | Feb 16, 2021 |
| Dell          | 0T7D40 A01                  | Desktop     | [301fc86371](https://bsd-hardware.info/?probe=301fc86371) | Feb 15, 2021 |
| Protectli     | FW2B Ver                    | Desktop     | [57ca4c3cac](https://bsd-hardware.info/?probe=57ca4c3cac) | Feb 15, 2021 |
| Dell          | Latitude E4300              | Notebook    | [981de7fd20](https://bsd-hardware.info/?probe=981de7fd20) | Feb 14, 2021 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [d7cca96f72](https://bsd-hardware.info/?probe=d7cca96f72) | Feb 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [994b94b7f5](https://bsd-hardware.info/?probe=994b94b7f5) | Feb 13, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [8f93b4146d](https://bsd-hardware.info/?probe=8f93b4146d) | Feb 12, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e74d76ecb3](https://bsd-hardware.info/?probe=e74d76ecb3) | Feb 12, 2021 |
| Dell          | Latitude 7280               | Notebook    | [defaee0e5c](https://bsd-hardware.info/?probe=defaee0e5c) | Feb 12, 2021 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [9ff4167171](https://bsd-hardware.info/?probe=9ff4167171) | Feb 12, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [687008da4f](https://bsd-hardware.info/?probe=687008da4f) | Feb 11, 2021 |
| Dell          | Latitude 7280               | Notebook    | [d62b7120c8](https://bsd-hardware.info/?probe=d62b7120c8) | Feb 11, 2021 |
| Dell          | 0DRR0P A00                  | Server      | [0b9292a0a4](https://bsd-hardware.info/?probe=0b9292a0a4) | Feb 11, 2021 |
| Dell          | Latitude 7370               | Notebook    | [8ec8d28024](https://bsd-hardware.info/?probe=8ec8d28024) | Feb 08, 2021 |
| PC Engines    | apu4                        | Desktop     | [67e0b30093](https://bsd-hardware.info/?probe=67e0b30093) | Feb 05, 2021 |
| PC Engines    | apu4                        | Desktop     | [d4b1d0ae99](https://bsd-hardware.info/?probe=d4b1d0ae99) | Feb 03, 2021 |
| PC Engines    | APU                         | Desktop     | [91da54ca8c](https://bsd-hardware.info/?probe=91da54ca8c) | Feb 02, 2021 |
| Dell          | Latitude E4300              | Notebook    | [84925c014a](https://bsd-hardware.info/?probe=84925c014a) | Feb 01, 2021 |
| Dell          | 0T7D40 A01                  | Desktop     | [1f5bf7092c](https://bsd-hardware.info/?probe=1f5bf7092c) | Feb 01, 2021 |
| Inventec      | VXC Class A02               | Desktop     | [22d0861af3](https://bsd-hardware.info/?probe=22d0861af3) | Jan 29, 2021 |
| Sophos        | SG                          | Firewall    | [d11e60890a](https://bsd-hardware.info/?probe=d11e60890a) | Jan 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [f4b460a5e4](https://bsd-hardware.info/?probe=f4b460a5e4) | Jan 28, 2021 |
| Inventec      | VXC Class A02               | Desktop     | [8c298fa5bf](https://bsd-hardware.info/?probe=8c298fa5bf) | Jan 28, 2021 |
| Inventec      | VXC Class A02               | Desktop     | [6127d635de](https://bsd-hardware.info/?probe=6127d635de) | Jan 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [f76df86f03](https://bsd-hardware.info/?probe=f76df86f03) | Jan 26, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [881d50fc9e](https://bsd-hardware.info/?probe=881d50fc9e) | Jan 26, 2021 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [97fd3d11e8](https://bsd-hardware.info/?probe=97fd3d11e8) | Jan 25, 2021 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [2577292fe1](https://bsd-hardware.info/?probe=2577292fe1) | Jan 25, 2021 |
| Inventec      | R CLASS A02                 | Desktop     | [545854fcfd](https://bsd-hardware.info/?probe=545854fcfd) | Jan 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5b00abed29](https://bsd-hardware.info/?probe=5b00abed29) | Jan 23, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [f8e3f072fc](https://bsd-hardware.info/?probe=f8e3f072fc) | Jan 23, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [3c0683ff11](https://bsd-hardware.info/?probe=3c0683ff11) | Jan 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5d556cc47f](https://bsd-hardware.info/?probe=5d556cc47f) | Jan 22, 2021 |
| Barracuda ... | Barracuda NG Firewall F1... | Firewall    | [6a1974bebd](https://bsd-hardware.info/?probe=6a1974bebd) | Jan 22, 2021 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [4b2e64662e](https://bsd-hardware.info/?probe=4b2e64662e) | Jan 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [951a898a3f](https://bsd-hardware.info/?probe=951a898a3f) | Jan 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [a1b0841493](https://bsd-hardware.info/?probe=a1b0841493) | Jan 21, 2021 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [064e82b131](https://bsd-hardware.info/?probe=064e82b131) | Jan 21, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [1fd927e2cd](https://bsd-hardware.info/?probe=1fd927e2cd) | Jan 11, 2021 |
| ASRockRack    | EPC612D4U-8R                | Desktop     | [617694f591](https://bsd-hardware.info/?probe=617694f591) | Dec 19, 2020 |
| Supermicro    | X10SAE                      | Server      | [d29048ae5d](https://bsd-hardware.info/?probe=d29048ae5d) | Oct 29, 2020 |
| ASRock        | B360 Pro4                   | Desktop     | [05d3ab8d4b](https://bsd-hardware.info/?probe=05d3ab8d4b) | Oct 29, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [57ecc0c410](https://bsd-hardware.info/?probe=57ecc0c410) | Oct 29, 2020 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [3cebf4d7db](https://bsd-hardware.info/?probe=3cebf4d7db) | Oct 29, 2020 |
| ASRockRack    | EPC612D4U-8R                | Desktop     | [b9ecd0e2b3](https://bsd-hardware.info/?probe=b9ecd0e2b3) | Oct 29, 2020 |
| Dell          | Precision WorkStation T7... | Desktop     | [c01ce9ec81](https://bsd-hardware.info/?probe=c01ce9ec81) | Oct 24, 2020 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [dc33c84287](https://bsd-hardware.info/?probe=dc33c84287) | Oct 22, 2020 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [2808d1dd6a](https://bsd-hardware.info/?probe=2808d1dd6a) | Oct 20, 2020 |
| Apple         | Macmini7,1                  | Mini pc     | [5caa1e1c7b](https://bsd-hardware.info/?probe=5caa1e1c7b) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [7671a495d1](https://bsd-hardware.info/?probe=7671a495d1) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [c1a2bc7a51](https://bsd-hardware.info/?probe=c1a2bc7a51) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [c1c5ee566c](https://bsd-hardware.info/?probe=c1c5ee566c) | Oct 19, 2020 |
| Dell          | PowerEdge R620              | Desktop     | [af87ddbbaa](https://bsd-hardware.info/?probe=af87ddbbaa) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [bee732e516](https://bsd-hardware.info/?probe=bee732e516) | Oct 19, 2020 |
| Intel         | S1200RP G62253-405          | Server      | [2793b07b38](https://bsd-hardware.info/?probe=2793b07b38) | May 30, 2020 |
| Gigabyte      | MQLP7AP-00                  | Desktop     | [07036eab43](https://bsd-hardware.info/?probe=07036eab43) | May 28, 2020 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [85bebeaea0](https://bsd-hardware.info/?probe=85bebeaea0) | May 25, 2020 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [9fea968a19](https://bsd-hardware.info/?probe=9fea968a19) | May 25, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Netherlands/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| OPNsense 23.1.11    | 14        | 3.17%   |
| OPNsense 21.7.7     | 13        | 2.95%   |
| OPNsense 23.7.9     | 11        | 2.49%   |
| helloSystem 0.7.0   | 11        | 2.49%   |
| OPNsense 23.1.7     | 10        | 2.27%   |
| OPNsense 23.1       | 10        | 2.27%   |
| OPNsense 23.1.5     | 9         | 2.04%   |
| OPNsense 21.7.5     | 9         | 2.04%   |
| OPNsense 21.1.3     | 9         | 2.04%   |
| OPNsense 21.7.3     | 8         | 1.81%   |
| OPNsense 21.7.1     | 8         | 1.81%   |
| OPNsense 21.1.1     | 8         | 1.81%   |
| OPNsense 20.7.8     | 8         | 1.81%   |
| OpenBSD 6.8         | 8         | 1.81%   |
| OPNsense 21.7.2     | 7         | 1.59%   |
| helloSystem 0.5.0   | 7         | 1.59%   |
| FreeBSD 13.0        | 7         | 1.59%   |
| OPNsense 23.7.7     | 6         | 1.36%   |
| OPNsense 23.7.10    | 6         | 1.36%   |
| OPNsense 22.7.4     | 6         | 1.36%   |
| OPNsense 22.1.6     | 6         | 1.36%   |
| OPNsense 22.1.4     | 6         | 1.36%   |
| OPNsense 22.1.1     | 6         | 1.36%   |
| OPNsense 22.1       | 6         | 1.36%   |
| OPNsense 21.1.2     | 6         | 1.36%   |
| OPNsense 21.1       | 6         | 1.36%   |
| OpenBSD 7.1         | 6         | 1.36%   |
| helloSystem 0.8.1   | 6         | 1.36%   |
| OPNsense 23.7.2     | 5         | 1.13%   |
| OPNsense 23.1.9     | 5         | 1.13%   |
| OPNsense 22.1.10    | 5         | 1.13%   |
| OPNsense 21.1.7     | 5         | 1.13%   |
| OPNsense 21.1.4     | 5         | 1.13%   |
| OpenBSD 6.9         | 5         | 1.13%   |
| FreeBSD 13.0-STABLE | 5         | 1.13%   |
| FreeBSD 13.0-p5     | 5         | 1.13%   |
| OPNsense 23.7.3     | 4         | 0.91%   |
| OPNsense 23.7.1     | 4         | 0.91%   |
| OPNsense 22.7.2     | 4         | 0.91%   |
| OPNsense 22.7.11    | 4         | 0.91%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 204       | 61.63%  |
| FreeBSD     | 53        | 16.01%  |
| helloSystem | 40        | 12.08%  |
| OpenBSD     | 23        | 6.95%   |
| HardenedBSD | 4         | 1.21%   |
| GhostBSD    | 4         | 1.21%   |
| pfSense     | 1         | 0.3%    |
| NomadBSD    | 1         | 0.3%    |
| NetBSD      | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 318       | 97.55%  |
| arm64 | 7         | 2.15%   |
| i386  | 1         | 0.31%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 238       | 71.47%  |
| helloDesktop  | 49        | 14.71%  |
| KDE5          | 8         | 2.4%    |
| fvwm          | 7         | 2.1%    |
| MATE          | 6         | 1.8%    |
| GNOME         | 6         | 1.8%    |
| XFCE          | 4         | 1.2%    |
| i3            | 4         | 1.2%    |
| TWM           | 3         | 0.9%    |
| LXQt          | 3         | 0.9%    |
| Openbox       | 1         | 0.3%    |
| GNUstep       | 1         | 0.3%    |
| Fluxbox       | 1         | 0.3%    |
| Enlightenment | 1         | 0.3%    |
| AwesomeWM     | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 242       | 74.23%  |
| X11     | 82        | 25.15%  |
| Wayland | 2         | 0.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 258       | 78.42%  |
| SLiM    | 44        | 13.37%  |
| XDM     | 8         | 2.43%   |
| SDDM    | 8         | 2.43%   |
| LightDM | 7         | 2.13%   |
| GDM     | 4         | 1.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 230       | 68.86%  |
| en_US   | 51        | 15.27%  |
| C       | 39        | 11.68%  |
| nl_NL   | 6         | 1.8%    |
| fr_FR   | 3         | 0.9%    |
| en      | 3         | 0.9%    |
| nl      | 1         | 0.3%    |
| de_DE   | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 279       | 85.06%  |
| BIOS | 49        | 14.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 156       | 46.15%  |
| Zfs    | 146       | 43.2%   |
| Ffs    | 23        | 6.8%    |
| Cd9660 | 13        | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 297       | 90.83%  |
| MBR     | 27        | 8.26%   |
| Unknown | 3         | 0.92%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 43        | 13.19%  |
| Hewlett-Packard     | 32        | 9.82%   |
| Unknown             | 32        | 9.82%   |
| Lenovo              | 28        | 8.59%   |
| Intel               | 20        | 6.13%   |
| ASUSTek Computer    | 15        | 4.6%    |
| Supermicro          | 14        | 4.29%   |
| ASRock              | 14        | 4.29%   |
| Gigabyte Technology | 12        | 3.68%   |
| Sophos              | 9         | 2.76%   |
| PC Engines          | 8         | 2.45%   |
| AMI                 | 8         | 2.45%   |
| Deciso              | 7         | 2.15%   |
| Apple               | 7         | 2.15%   |
| Protectli           | 6         | 1.84%   |
| Shuttle             | 5         | 1.53%   |
| Fujitsu             | 5         | 1.53%   |
| Techvision          | 4         | 1.23%   |
| MSI                 | 4         | 1.23%   |
| Notebook            | 3         | 0.92%   |
| MW                  | 3         | 0.92%   |
| Inventec            | 3         | 0.92%   |
| ASRockRack          | 3         | 0.92%   |
| Acer                | 3         | 0.92%   |
| SLIMBOOK            | 2         | 0.61%   |
| Hardkernel          | 2         | 0.61%   |
| CncTion             | 2         | 0.61%   |
| Barracuda Networks  | 2         | 0.61%   |
| Advantech           | 2         | 0.61%   |
| AAEON               | 2         | 0.61%   |
| ZOTAC               | 1         | 0.31%   |
| XtReAmEr            | 1         | 0.31%   |
| WYSE                | 1         | 0.31%   |
| TUXEDO              | 1         | 0.31%   |
| TOXIC by BTO        | 1         | 0.31%   |
| Toshiba             | 1         | 0.31%   |
| Star Labs           | 1         | 0.31%   |
| Sony                | 1         | 0.31%   |
| SolidRun            | 1         | 0.31%   |
| Sapphire            | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Unknown                     | 34        | 10.43%  |
| Intel Q3XXG4-P V1.0         | 10        | 3.07%   |
| Sophos SG                   | 7         | 2.15%   |
| Supermicro Super Server     | 6         | 1.84%   |
| AMI Aptio CRB               | 6         | 1.84%   |
| Dell PowerEdge R620         | 5         | 1.53%   |
| Dell PowerEdge R210 II      | 5         | 1.53%   |
| Techvision TVI7309X         | 4         | 1.23%   |
| PC Engines apu4             | 3         | 0.92%   |
| PC Engines APU2             | 3         | 0.92%   |
| MW GMLK-2_5G4L              | 3         | 0.92%   |
| Fujitsu FUTRO S920          | 3         | 0.92%   |
| Dell OptiPlex 7040          | 3         | 0.92%   |
| Sophos XG                   | 2         | 0.61%   |
| PC Engines APU              | 2         | 0.61%   |
| Inventec VXC Class          | 2         | 0.61%   |
| HP ProDesk 400 G2.5 SFF     | 2         | 0.61%   |
| HP EliteDesk 800 G1 SFF     | 2         | 0.61%   |
| HP EliteBook 840 G3         | 2         | 0.61%   |
| Gigabyte X570 AORUS PRO     | 2         | 0.61%   |
| Dell OptiPlex 7050          | 2         | 0.61%   |
| Dell OptiPlex 390           | 2         | 0.61%   |
| Dell OptiPlex 3050          | 2         | 0.61%   |
| Dell Latitude E4300         | 2         | 0.61%   |
| Deciso OPNsense Appliance   | 2         | 0.61%   |
| Deciso NetBoard-A10         | 2         | 0.61%   |
| ASRockRack X470D4U          | 2         | 0.61%   |
| ZOTAC ZBOX-CI327NANO-GS-01  | 1         | 0.31%   |
| WYSE Z CLASS                | 1         | 0.31%   |
| TUXEDO Pulse 15 Gen1        | 1         | 0.31%   |
| TOXIC by BTO 15CL872 1050TI | 1         | 0.31%   |
| Toshiba Satellite C50-B     | 1         | 0.31%   |
| Supermicro X9SCL/X9SCM      | 1         | 0.31%   |
| Supermicro X8SIL            | 1         | 0.31%   |
| Supermicro X7SLA            | 1         | 0.31%   |
| Supermicro X10SLM+-LN4F     | 1         | 0.31%   |
| Supermicro X10SAE           | 1         | 0.31%   |
| Supermicro AS -E301-9D-8CN4 | 1         | 0.31%   |
| Supermicro AS -5019D-FTN4   | 1         | 0.31%   |
| Supermicro A1SAi            | 1         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 34        | 10.43%  |
| Lenovo ThinkPad              | 17        | 5.21%   |
| Dell OptiPlex                | 17        | 5.21%   |
| Dell PowerEdge               | 13        | 3.99%   |
| Intel Q3XXG4-P               | 10        | 3.07%   |
| HP ProDesk                   | 8         | 2.45%   |
| Sophos SG                    | 7         | 2.15%   |
| Dell Latitude                | 7         | 2.15%   |
| Supermicro Super             | 6         | 1.84%   |
| HP ProLiant                  | 6         | 1.84%   |
| AMI Aptio                    | 6         | 1.84%   |
| HP Compaq                    | 5         | 1.53%   |
| ASUS PRIME                   | 5         | 1.53%   |
| Techvision TVI7309X          | 4         | 1.23%   |
| HP EliteDesk                 | 4         | 1.23%   |
| HP EliteBook                 | 4         | 1.23%   |
| PC Engines apu4              | 3         | 0.92%   |
| PC Engines APU2              | 3         | 0.92%   |
| MW GMLK-2                    | 3         | 0.92%   |
| Lenovo ThinkCentre           | 3         | 0.92%   |
| Lenovo IdeaPad               | 3         | 0.92%   |
| Fujitsu FUTRO                | 3         | 0.92%   |
| Deciso Netboard              | 3         | 0.92%   |
| Acer Aspire                  | 3         | 0.92%   |
| Supermicro AS                | 2         | 0.61%   |
| Sophos XG                    | 2         | 0.61%   |
| PC Engines APU               | 2         | 0.61%   |
| Inventec VXC                 | 2         | 0.61%   |
| Gigabyte X570                | 2         | 0.61%   |
| Dell Wyse                    | 2         | 0.61%   |
| Deciso OPNsense              | 2         | 0.61%   |
| Deciso NetBoard-A10          | 2         | 0.61%   |
| Barracuda Networks Barracuda | 2         | 0.61%   |
| ASRockRack X470D4U           | 2         | 0.61%   |
| ZOTAC ZBOX-CI327NANO-GS-01   | 1         | 0.31%   |
| WYSE Z                       | 1         | 0.31%   |
| TUXEDO Pulse                 | 1         | 0.31%   |
| TOXIC by BTO 15CL872         | 1         | 0.31%   |
| Toshiba Satellite            | 1         | 0.31%   |
| Supermicro X9SCL             | 1         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 40        | 12.27%  |
| 2016    | 29        | 8.9%    |
| 2022    | 28        | 8.59%   |
| 2020    | 28        | 8.59%   |
| 2014    | 27        | 8.28%   |
| 2019    | 25        | 7.67%   |
| 2021    | 24        | 7.36%   |
| 2015    | 22        | 6.75%   |
| 2017    | 18        | 5.52%   |
| 2013    | 16        | 4.91%   |
| 2012    | 16        | 4.91%   |
| 2011    | 16        | 4.91%   |
| 2023    | 9         | 2.76%   |
| Unknown | 8         | 2.45%   |
| 2009    | 7         | 2.15%   |
| 2008    | 7         | 2.15%   |
| 2010    | 4         | 1.23%   |
| 2007    | 1         | 0.31%   |
| 2006    | 1         | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 200       | 61.35%  |
| Notebook       | 67        | 20.55%  |
| Mini pc        | 23        | 7.06%   |
| Server         | 22        | 6.75%   |
| Firewall       | 11        | 3.37%   |
| All in one     | 2         | 0.61%   |
| System on chip | 1         | 0.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 312       | 95.71%  |
| Yes  | 14        | 4.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 124       | 37.58%  |
| 16.01-24.0      | 73        | 22.12%  |
| 4.01-8.0        | 64        | 19.39%  |
| 32.01-64.0      | 32        | 9.7%    |
| 64.01-256.0     | 13        | 3.94%   |
| 2.01-3.0        | 10        | 3.03%   |
| 3.01-4.0        | 5         | 1.52%   |
| More than 256.0 | 3         | 0.91%   |
| 24.01-32.0      | 2         | 0.61%   |
| 1.01-2.0        | 2         | 0.61%   |
| 0.51-1.0        | 2         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 173       | 51.64%  |
| 0.51-1.0   | 97        | 28.96%  |
| 1.01-2.0   | 35        | 10.45%  |
| 4.01-8.0   | 8         | 2.39%   |
| 2.01-3.0   | 7         | 2.09%   |
| 3.01-4.0   | 4         | 1.19%   |
| 8.01-16.0  | 4         | 1.19%   |
| 32.01-64.0 | 2         | 0.6%    |
| 24.01-32.0 | 2         | 0.6%    |
| 16.01-24.0 | 1         | 0.3%    |
| 0          | 1         | 0.3%    |
| Unknown    | 1         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 229       | 68.98%  |
| 2      | 49        | 14.76%  |
| 0      | 19        | 5.72%   |
| 3      | 15        | 4.52%   |
| 4      | 8         | 2.41%   |
| 5      | 5         | 1.51%   |
| 7      | 2         | 0.6%    |
| 17     | 1         | 0.3%    |
| 15     | 1         | 0.3%    |
| 12     | 1         | 0.3%    |
| 10     | 1         | 0.3%    |
| 6      | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 285       | 87.16%  |
| Yes       | 42        | 12.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 309       | 94.79%  |
| No        | 17        | 5.21%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 222       | 67.68%  |
| Yes       | 106       | 32.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 254       | 77.2%   |
| Yes       | 75        | 22.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Netherlands | 326       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Amsterdam           | 61        | 16.31%  |
| Utrecht             | 10        | 2.67%   |
| The Hague           | 9         | 2.41%   |
| Rotterdam           | 8         | 2.14%   |
| Almere Stad         | 7         | 1.87%   |
| Groningen           | 6         | 1.6%    |
| Eindhoven           | 6         | 1.6%    |
| Zeist               | 4         | 1.07%   |
| Zaandam             | 4         | 1.07%   |
| Vlaardingen         | 4         | 1.07%   |
| Poortugaal          | 4         | 1.07%   |
| Papendrecht         | 4         | 1.07%   |
| Hoofddorp           | 4         | 1.07%   |
| Heerlen             | 4         | 1.07%   |
| Barneveld           | 4         | 1.07%   |
| Amersfoort          | 4         | 1.07%   |
| Alphen aan den Rijn | 4         | 1.07%   |
| Veenendaal          | 3         | 0.8%    |
| Tilburg             | 3         | 0.8%    |
| Ospel               | 3         | 0.8%    |
| Oegstgeest          | 3         | 0.8%    |
| Naaldwijk           | 3         | 0.8%    |
| Maastricht          | 3         | 0.8%    |
| Hoogeveen           | 3         | 0.8%    |
| Hengelo             | 3         | 0.8%    |
| Heemskerk           | 3         | 0.8%    |
| Gouda               | 3         | 0.8%    |
| Enschede            | 3         | 0.8%    |
| Ede                 | 3         | 0.8%    |
| Dordrecht           | 3         | 0.8%    |
| Delft               | 3         | 0.8%    |
| Breda               | 3         | 0.8%    |
| Almere Poort        | 3         | 0.8%    |
| 's-Hertogenbosch    | 3         | 0.8%    |
| Zoetermeer          | 2         | 0.53%   |
| Valkenswaard        | 2         | 0.53%   |
| Tiel                | 2         | 0.53%   |
| Teteringen          | 2         | 0.53%   |
| Steenbergen         | 2         | 0.53%   |
| Soest               | 2         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 76        | 121    | 20.05%  |
| WDC                 | 35        | 79     | 9.23%   |
| Crucial             | 30        | 49     | 7.92%   |
| Kingston            | 28        | 36     | 7.39%   |
| Seagate             | 23        | 56     | 6.07%   |
| Transcend           | 21        | 39     | 5.54%   |
| SanDisk             | 13        | 13     | 3.43%   |
| Intel               | 12        | 15     | 3.17%   |
| Toshiba             | 11        | 28     | 2.9%    |
| Hoodisk             | 10        | 15     | 2.64%   |
| Hewlett-Packard     | 8         | 25     | 2.11%   |
| Gigabyte Technology | 7         | 9      | 1.85%   |
| Phison              | 6         | 7      | 1.58%   |
| OCZ                 | 6         | 7      | 1.58%   |
| Hitachi             | 6         | 8      | 1.58%   |
| HGST                | 6         | 10     | 1.58%   |
| China               | 6         | 11     | 1.58%   |
| NVMe                | 5         | 6      | 1.32%   |
| A-DATA Technology   | 5         | 5      | 1.32%   |
| LITEON              | 4         | 5      | 1.06%   |
| Dell                | 4         | 8      | 1.06%   |
| UDinfo              | 3         | 3      | 0.79%   |
| Silicon Motion      | 3         | 4      | 0.79%   |
| ShiJi               | 3         | 4      | 0.79%   |
| FORESEE             | 3         | 6      | 0.79%   |
| Apple               | 3         | 4      | 0.79%   |
| Apacer              | 3         | 5      | 0.79%   |
| Protectli           | 2         | 6      | 0.53%   |
| PNY                 | 2         | 2      | 0.53%   |
| NETAPP              | 2         | 7      | 0.53%   |
| Mushkin             | 2         | 4      | 0.53%   |
| Micron Technology   | 2         | 2      | 0.53%   |
| Kston               | 2         | 6      | 0.53%   |
| Innodisk            | 2         | 2      | 0.53%   |
| HPE                 | 2         | 5      | 0.53%   |
| Corsair             | 2         | 4      | 0.53%   |
| VICKTER             | 1         | 1      | 0.26%   |
| StoreJet            | 1         | 1      | 0.26%   |
| Star Drive          | 1         | 1      | 0.26%   |
| SPCC                | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB        | 11        | 2.71%   |
| Samsung SSD 850 EVO 500GB        | 4         | 0.99%   |
| Kingston SUV500MS120G 120GB      | 4         | 0.99%   |
| Kingston SKC600MS256G 256GB      | 4         | 0.99%   |
| Hoodisk SSD 128GB                | 4         | 0.99%   |
| Dell PERC H710 282GB             | 4         | 0.99%   |
| Crucial CT250MX500SSD1 250GB     | 4         | 0.99%   |
| Crucial CT120BX500SSD1 120GB     | 4         | 0.99%   |
| UDinfo M2S 120GB                 | 3         | 0.74%   |
| Transcend TS128GMTE110S 128GB    | 3         | 0.74%   |
| Toshiba MQ04ABF100 1TB           | 3         | 0.74%   |
| Samsung SSD 850 EVO 120GB        | 3         | 0.74%   |
| Kingston SA400S37240G 240GB      | 3         | 0.74%   |
| Kingston SA400S37120G 120GB      | 3         | 0.74%   |
| Intel SSDSC2BW120A4 120GB        | 3         | 0.74%   |
| Hoodisk SSD 64GB                 | 3         | 0.74%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB | 3         | 0.74%   |
| Crucial M4-CT128M4SSD2 128GB     | 3         | 0.74%   |
| Crucial CT240BX500SSD1 240GB     | 3         | 0.74%   |
| China SATA SSD 16GB              | 3         | 0.74%   |
| A-DATA IM2S3134N-064GM 64GB      | 3         | 0.74%   |
| WDC WD80EFAX-68KNBN0 8TB         | 2         | 0.49%   |
| WDC WD60EFRX-68L0BN1 6TB         | 2         | 0.49%   |
| WDC WD5000LPVX-22V0TT0 500GB     | 2         | 0.49%   |
| WDC WD40EFRX-68WT0N0 4TB         | 2         | 0.49%   |
| WDC WD40EFRX-68N32N0 4TB         | 2         | 0.49%   |
| Transcend TS32GSSD370S 32GB      | 2         | 0.49%   |
| Transcend TS256GMTE652T2 256GB   | 2         | 0.49%   |
| Transcend TS256GMSA452T2 256GB   | 2         | 0.49%   |
| Transcend TS256GMSA230S 256GB    | 2         | 0.49%   |
| Transcend TS128GMSA230S 128GB    | 2         | 0.49%   |
| Seagate ST500LM000-SSHD-8GB      | 2         | 0.49%   |
| Seagate ST1000LM049-2GH172 1TB   | 2         | 0.49%   |
| Samsung SSD 980 PRO 1TB          | 2         | 0.49%   |
| Samsung SSD 980 500GB            | 2         | 0.49%   |
| Samsung SSD 970 EVO Plus 2TB     | 2         | 0.49%   |
| Samsung SSD 970 EVO Plus 1TB     | 2         | 0.49%   |
| Samsung SSD 970 EVO 1TB          | 2         | 0.49%   |
| Samsung SSD 860 EVO 250GB        | 2         | 0.49%   |
| Samsung SSD 850 PRO 128GB        | 2         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 65     | 29.35%  |
| Seagate             | 23        | 56     | 25%     |
| Hewlett-Packard     | 7         | 24     | 7.61%   |
| Samsung Electronics | 6         | 9      | 6.52%   |
| Hitachi             | 6         | 8      | 6.52%   |
| HGST                | 6         | 10     | 6.52%   |
| Toshiba             | 5         | 17     | 5.43%   |
| Dell                | 4         | 8      | 4.35%   |
| NVMe                | 2         | 2      | 2.17%   |
| StoreJet            | 1         | 1      | 1.09%   |
| OPENBSD             | 1         | 1      | 1.09%   |
| Maxtor              | 1         | 1      | 1.09%   |
| Lenovo              | 1         | 2      | 1.09%   |
| HPE                 | 1         | 4      | 1.09%   |
| Apple               | 1         | 1      | 1.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 54        | 85     | 23.79%  |
| Crucial             | 26        | 40     | 11.45%  |
| Kingston            | 22        | 30     | 9.69%   |
| Transcend           | 16        | 33     | 7.05%   |
| SanDisk             | 13        | 13     | 5.73%   |
| Intel               | 10        | 13     | 4.41%   |
| Hoodisk             | 10        | 15     | 4.41%   |
| OCZ                 | 6         | 7      | 2.64%   |
| China               | 6         | 11     | 2.64%   |
| WDC                 | 5         | 8      | 2.2%    |
| LITEON              | 4         | 5      | 1.76%   |
| UDinfo              | 3         | 3      | 1.32%   |
| Phison              | 3         | 3      | 1.32%   |
| NVMe                | 3         | 4      | 1.32%   |
| FORESEE             | 3         | 6      | 1.32%   |
| Apacer              | 3         | 5      | 1.32%   |
| A-DATA Technology   | 3         | 3      | 1.32%   |
| Toshiba             | 2         | 4      | 0.88%   |
| ShiJi               | 2         | 3      | 0.88%   |
| Protectli           | 2         | 6      | 0.88%   |
| PNY                 | 2         | 2      | 0.88%   |
| NETAPP              | 2         | 7      | 0.88%   |
| Mushkin             | 2         | 4      | 0.88%   |
| Kston               | 2         | 6      | 0.88%   |
| Innodisk            | 2         | 2      | 0.88%   |
| Gigabyte Technology | 2         | 2      | 0.88%   |
| Apple               | 2         | 3      | 0.88%   |
| VICKTER             | 1         | 1      | 0.44%   |
| SK hynix            | 1         | 1      | 0.44%   |
| Patriot             | 1         | 2      | 0.44%   |
| OWC                 | 1         | 1      | 0.44%   |
| ORICO               | 1         | 1      | 0.44%   |
| Micron Technology   | 1         | 1      | 0.44%   |
| Maximus             | 1         | 1      | 0.44%   |
| LITEONIT            | 1         | 3      | 0.44%   |
| Leven               | 1         | 1      | 0.44%   |
| KeepData            | 1         | 1      | 0.44%   |
| Intenso             | 1         | 3      | 0.44%   |
| Indilinx            | 1         | 1      | 0.44%   |
| HPE                 | 1         | 1      | 0.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 214       | 347    | 60.45%  |
| HDD  | 81        | 209    | 22.88%  |
| NVMe | 59        | 88     | 16.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 270       | 556    | 82.07%  |
| NVMe | 59        | 88     | 17.93%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 235       | 383    | 77.05%  |
| 0.51-1.0   | 38        | 73     | 12.46%  |
| 1.01-2.0   | 13        | 20     | 4.26%   |
| 3.01-4.0   | 9         | 22     | 2.95%   |
| 4.01-10.0  | 8         | 49     | 2.62%   |
| 2.01-3.0   | 1         | 4      | 0.33%   |
| 10.01-20.0 | 1         | 5      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 144       | 42.11%  |
| 251-500        | 49        | 14.33%  |
| 51-100         | 48        | 14.04%  |
| 1-20           | 43        | 12.57%  |
| 21-50          | 24        | 7.02%   |
| 501-1000       | 18        | 5.26%   |
| 1001-2000      | 9         | 2.63%   |
| More than 3000 | 3         | 0.88%   |
| 2001-3000      | 2         | 0.58%   |
| Unknown        | 2         | 0.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 297       | 89.19%  |
| 21-50    | 15        | 4.5%    |
| 101-250  | 6         | 1.8%    |
| 51-100   | 6         | 1.8%    |
| 251-500  | 4         | 1.2%    |
| 501-1000 | 3         | 0.9%    |
| Unknown  | 2         | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Crucial CT480M500SSD1 480GB               | 2         | 3      | 5.71%   |
| WDC WD2500BEKT-75PVMT0 250GB              | 1         | 1      | 2.86%   |
| WDC WD15EARS-00Z5B1 1.5TB                 | 1         | 1      | 2.86%   |
| ShiJi SSD 32GB                            | 1         | 2      | 2.86%   |
| Seagate ST500LT012-9WS142 500GB           | 1         | 2      | 2.86%   |
| Seagate ST500LM021-1KJ152 500GB           | 1         | 1      | 2.86%   |
| Seagate ST3360320AS 360GB                 | 1         | 1      | 2.86%   |
| Seagate ST3160318AS 160GB                 | 1         | 4      | 2.86%   |
| SanDisk SDSSDP064G 64GB                   | 1         | 1      | 2.86%   |
| SanDisk SD7UB3Q256G1001 256GB             | 1         | 1      | 2.86%   |
| Samsung Electronics SSD 870 EVO 1TB       | 1         | 1      | 2.86%   |
| Samsung Electronics SSD 850 EVO mSATA 1TB | 1         | 1      | 2.86%   |
| Samsung Electronics SSD 850 EVO 1TB       | 1         | 1      | 2.86%   |
| Samsung Electronics SSD 840 Series 120GB  | 1         | 1      | 2.86%   |
| Samsung Electronics SSD 840 EVO 120GB     | 1         | 1      | 2.86%   |
| Samsung Electronics HS082HB 80GB          | 1         | 1      | 2.86%   |
| Samsung Electronics HD322HJ 320GB         | 1         | 1      | 2.86%   |
| Samsung Electronics HD161GJ 160GB         | 1         | 1      | 2.86%   |
| Samsung Electronics HD103SJ 1TB           | 1         | 2      | 2.86%   |
| Kingston SMS200S3120G 120GB               | 1         | 1      | 2.86%   |
| Kingston SA400S37240G 240GB               | 1         | 1      | 2.86%   |
| Intel SSDSC2BA200G3T 200GB                | 1         | 4      | 2.86%   |
| Intel SSDSA2M080G2GC 80GB                 | 1         | 1      | 2.86%   |
| HPE MM1000GBKAL 1TB                       | 1         | 4      | 2.86%   |
| Hitachi HTS545032B9A300 320GB             | 1         | 1      | 2.86%   |
| Hitachi HTS543232A7A384 320GB             | 1         | 1      | 2.86%   |
| Hitachi HDS723015BLA642 1.5TB             | 1         | 3      | 2.86%   |
| HGST HTS725050A7E630 500GB                | 1         | 1      | 2.86%   |
| HGST HDN726060ALE614 6TB                  | 1         | 2      | 2.86%   |
| Hewlett-Packard FB160C4081 160GB          | 1         | 2      | 2.86%   |
| Crucial CT128MX100SSD1 128GB              | 1         | 2      | 2.86%   |
| Corsair Force LS SSD 64GB                 | 1         | 2      | 2.86%   |
| China SH00M128GB                          | 1         | 1      | 2.86%   |
| A-DATA Technology SX7000NP 128GB          | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 10     | 23.53%  |
| Seagate             | 4         | 8      | 11.76%  |
| Hitachi             | 3         | 5      | 8.82%   |
| Crucial             | 3         | 5      | 8.82%   |
| WDC                 | 2         | 2      | 5.88%   |
| SanDisk             | 2         | 2      | 5.88%   |
| Kingston            | 2         | 2      | 5.88%   |
| Intel               | 2         | 5      | 5.88%   |
| HGST                | 2         | 3      | 5.88%   |
| ShiJi               | 1         | 2      | 2.94%   |
| HPE                 | 1         | 4      | 2.94%   |
| Hewlett-Packard     | 1         | 2      | 2.94%   |
| Corsair             | 1         | 2      | 2.94%   |
| China               | 1         | 1      | 2.94%   |
| A-DATA Technology   | 1         | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 8      | 23.53%  |
| Samsung Electronics | 4         | 5      | 23.53%  |
| Hitachi             | 3         | 5      | 17.65%  |
| WDC                 | 2         | 2      | 11.76%  |
| HGST                | 2         | 3      | 11.76%  |
| HPE                 | 1         | 4      | 5.88%   |
| Hewlett-Packard     | 1         | 2      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 29     | 50%     |
| SSD  | 15        | 24     | 46.88%  |
| NVMe | 1         | 1      | 3.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 960 EVO 250GB        | 1         | 1      | 25%     |
| Samsung Electronics MZVLW256HEHP-000H1 256GB | 1         | 1      | 25%     |
| Samsung Electronics MZVLW256HEHP-00000 256GB | 1         | 1      | 25%     |
| HPE MK000480GWUGF 480GB                      | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 75%     |
| HPE                 | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 278       | 564    | 85.54%  |
| Malfunc  | 30        | 54     | 9.23%   |
| Detected | 13        | 22     | 4%      |
| Failed   | 4         | 4      | 1.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 254       | 63.03%  |
| AMD                         | 45        | 11.17%  |
| Samsung Electronics         | 26        | 6.45%   |
| Phison Electronics          | 13        | 3.23%   |
| Broadcom / LSI              | 10        | 2.48%   |
| ASMedia Technology          | 10        | 2.48%   |
| Silicon Motion              | 6         | 1.49%   |
| Micron/Crucial Technology   | 6         | 1.49%   |
| Hewlett-Packard             | 6         | 1.49%   |
| Kingston Technology Company | 5         | 1.24%   |
| Toshiba                     | 4         | 0.99%   |
| SanDisk                     | 4         | 0.99%   |
| Transcend                   | 3         | 0.74%   |
| Marvell Technology Group    | 3         | 0.74%   |
| Micron Technology           | 2         | 0.5%    |
| Realtek Semiconductor       | 1         | 0.25%   |
| Lite-On Technology          | 1         | 0.25%   |
| KIOXIA                      | 1         | 0.25%   |
| JMicron Technology          | 1         | 0.25%   |
| Dell                        | 1         | 0.25%   |
| Chelsio Communications      | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 32        | 7.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 25        | 5.71%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 17        | 3.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 14        | 3.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 13        | 2.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 2.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 11        | 2.51%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 10        | 2.28%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 10        | 2.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 10        | 2.28%   |
| Intel Comet Lake SATA AHCI Controller                                            | 9         | 2.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9         | 2.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 2.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 2.05%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 8         | 1.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 1.83%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 7         | 1.6%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 7         | 1.6%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 6         | 1.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 6         | 1.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 6         | 1.37%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 5         | 1.14%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 5         | 1.14%   |
| Intel SATA Controller [RAID mode]                                                | 5         | 1.14%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 1.14%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 5         | 1.14%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 5         | 1.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 1.14%   |
| AMD 400 Series Chipset SATA Controller                                           | 5         | 1.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 0.91%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 0.91%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 4         | 0.91%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 4         | 0.91%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 4         | 0.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 0.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 0.91%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 4         | 0.91%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)      | 3         | 0.68%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 3         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 269       | 67.76%  |
| NVMe | 69        | 17.38%  |
| RAID | 30        | 7.56%   |
| IDE  | 21        | 5.29%   |
| SAS  | 7         | 1.76%   |
| SCSI | 1         | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 268       | 82.21%  |
| AMD    | 51        | 15.64%  |
| ARM    | 6         | 1.84%   |
| NXP    | 1         | 0.31%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz     | 7         | 2.14%   |
| Intel Celeron N5105 @ 2.00GHz        | 6         | 1.83%   |
| Intel Celeron J4125 CPU @ 2.00GHz    | 6         | 1.83%   |
| Intel Celeron CPU J1900 @ 1.99GHz    | 6         | 1.83%   |
| AMD GX-412TC SOC                     | 6         | 1.83%   |
| Intel Celeron CPU J3160 @ 1.60GHz    | 5         | 1.53%   |
| Intel N100                           | 4         | 1.22%   |
| Intel Core i5-5200U CPU @ 2.20GHz    | 4         | 1.22%   |
| Intel Core 2 Duo                     | 4         | 1.22%   |
| ARM Cortex-A72 r0p3                  | 4         | 1.22%   |
| AMD G-T56N Processor                 | 4         | 1.22%   |
| Intel Xeon CPU D-1521 @ 2.40GHz      | 3         | 0.92%   |
| Intel Core i7-4500U CPU @ 1.80GHz    | 3         | 0.92%   |
| Intel Core i7-2600K CPU @ 3.40GHz    | 3         | 0.92%   |
| Intel Core i5-8365U CPU @ 1.60GHz    | 3         | 0.92%   |
| Intel Core i5-5250U CPU @ 1.60GHz    | 3         | 0.92%   |
| Intel Atom CPU C3558 @ 2.20GHz       | 3         | 0.92%   |
| AMD Ryzen Embedded V1500B            | 3         | 0.92%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz   | 2         | 0.61%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz   | 2         | 0.61%   |
| Intel Pentium Silver N6005 @ 2.00GHz | 2         | 0.61%   |
| Intel Pentium CPU G3420 @ 3.20GHz    | 2         | 0.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz    | 2         | 0.61%   |
| Intel Core i7-7600U CPU @ 2.80GHz    | 2         | 0.61%   |
| Intel Core i7-5550U CPU @ 2.00GHz    | 2         | 0.61%   |
| Intel Core i7-5500U CPU @ 2.40GHz    | 2         | 0.61%   |
| Intel Core i7-4600U CPU @ 2.10GHz    | 2         | 0.61%   |
| Intel Core i7-3520M CPU @ 2.90GHz    | 2         | 0.61%   |
| Intel Core i7-2630QM CPU @ 2.00GHz   | 2         | 0.61%   |
| Intel Core i7-2600 CPU @ 3.40GHz     | 2         | 0.61%   |
| Intel Core i5-8600 CPU @ 3.10GHz     | 2         | 0.61%   |
| Intel Core i5-7500 CPU @ 3.40GHz     | 2         | 0.61%   |
| Intel Core i5-6400 CPU @ 2.70GHz     | 2         | 0.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz    | 2         | 0.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz    | 2         | 0.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz    | 2         | 0.61%   |
| Intel Core i5-4690 CPU @ 3.50GHz     | 2         | 0.61%   |
| Intel Core i5-4590T CPU @ 2.00GHz    | 2         | 0.61%   |
| Intel Core i5-4590S CPU @ 3.00GHz    | 2         | 0.61%   |
| Intel Core i5-4590 CPU @ 3.30GHz     | 2         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 74        | 22.63%  |
| Intel Core i7        | 38        | 11.62%  |
| Intel Celeron        | 38        | 11.62%  |
| Intel Xeon           | 33        | 10.09%  |
| Intel Core i3        | 20        | 6.12%   |
| Intel Atom           | 19        | 5.81%   |
| Other                | 17        | 5.2%    |
| AMD GX               | 14        | 4.28%   |
| Intel Pentium        | 11        | 3.36%   |
| Intel Core 2 Duo     | 11        | 3.36%   |
| AMD Ryzen 7          | 8         | 2.45%   |
| ARM Cortex           | 6         | 1.83%   |
| AMD G                | 6         | 1.83%   |
| Intel Pentium Silver | 3         | 0.92%   |
| Intel Pentium Gold   | 3         | 0.92%   |
| AMD Ryzen Embedded   | 3         | 0.92%   |
| AMD Ryzen 5          | 3         | 0.92%   |
| AMD EPYC             | 3         | 0.92%   |
| Intel Core i9        | 2         | 0.61%   |
| AMD E1               | 2         | 0.61%   |
| Intel Pentium 4      | 1         | 0.31%   |
| Intel Core m7        | 1         | 0.31%   |
| Intel Core m3        | 1         | 0.31%   |
| Intel Core 2         | 1         | 0.31%   |
| AMD Ryzen 9          | 1         | 0.31%   |
| AMD Ryzen 7 PRO      | 1         | 0.31%   |
| AMD Ryzen 5 PRO      | 1         | 0.31%   |
| AMD Ryzen 3          | 1         | 0.31%   |
| AMD E2               | 1         | 0.31%   |
| AMD E                | 1         | 0.31%   |
| AMD Athlon II        | 1         | 0.31%   |
| AMD A8               | 1         | 0.31%   |
| AMD A6               | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 150       | 46.01%  |
| 2       | 107       | 32.82%  |
| 6       | 18        | 5.52%   |
| 8       | 15        | 4.6%    |
| Unknown | 13        | 3.99%   |
| 16      | 9         | 2.76%   |
| 12      | 8         | 2.45%   |
| 1       | 2         | 0.61%   |
| 24      | 1         | 0.31%   |
| 20      | 1         | 0.31%   |
| 18      | 1         | 0.31%   |
| 10      | 1         | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 311       | 95.4%   |
| 2       | 9         | 2.76%   |
| Unknown | 6         | 1.84%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 171       | 52.29%  |
| 2       | 143       | 43.73%  |
| Unknown | 13        | 3.98%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 39        | 11.93%  |
| Haswell       | 36        | 11.01%  |
| Unknown       | 29        | 8.87%   |
| Skylake       | 27        | 8.26%   |
| Silvermont    | 23        | 7.03%   |
| SandyBridge   | 23        | 7.03%   |
| Broadwell     | 23        | 7.03%   |
| IvyBridge     | 18        | 5.5%    |
| Goldmont      | 11        | 3.36%   |
| Goldmont plus | 10        | 3.06%   |
| Zen           | 9         | 2.75%   |
| Puma          | 9         | 2.75%   |
| Penryn        | 9         | 2.75%   |
| CometLake     | 9         | 2.75%   |
| Zen 2         | 7         | 2.14%   |
| Jaguar        | 7         | 2.14%   |
| Bobcat        | 7         | 2.14%   |
| Nehalem       | 5         | 1.53%   |
| Bonnell       | 5         | 1.53%   |
| TigerLake     | 4         | 1.22%   |
| Westmere      | 3         | 0.92%   |
| Core          | 3         | 0.92%   |
| Zen 3         | 2         | 0.61%   |
| Excavator     | 2         | 0.61%   |
| Zen+          | 1         | 0.31%   |
| Steamroller   | 1         | 0.31%   |
| Piledriver    | 1         | 0.31%   |
| NetBurst      | 1         | 0.31%   |
| K8 Hammer     | 1         | 0.31%   |
| K10 Llano     | 1         | 0.31%   |
| K10           | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 208       | 66.67%  |
| AMD                        | 39        | 12.5%   |
| Matrox Electronics Systems | 23        | 7.37%   |
| Nvidia                     | 22        | 7.05%   |
| ASPEED Technology          | 20        | 6.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 20        | 6.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 16        | 5.03%   |
| Intel HD Graphics 530                                                                    | 15        | 4.72%   |
| Intel HD Graphics 5500                                                                   | 12        | 3.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 3.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 3.14%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 9         | 2.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 2.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 2.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 2.83%   |
| Intel JasperLake [UHD Graphics]                                                          | 8         | 2.52%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 2.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 1.89%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 1.89%   |
| Matrox Electronics Systems MGA G200EH                                                    | 5         | 1.57%   |
| Matrox Electronics Systems G200eR2                                                       | 5         | 1.57%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.57%   |
| Intel HD Graphics 630                                                                    | 5         | 1.57%   |
| Intel HD Graphics 620                                                                    | 5         | 1.57%   |
| Intel HD Graphics 6000                                                                   | 5         | 1.57%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 1.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.26%   |
| Intel HD Graphics 500                                                                    | 4         | 1.26%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 4         | 1.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.26%   |
| Intel HD Graphics 610                                                                    | 3         | 0.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.94%   |
| Intel Comet Lake UHD Graphics                                                            | 3         | 0.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 0.94%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 0.94%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.63%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 0.63%   |
| Intel UHD Graphics 620                                                                   | 2         | 0.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.63%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 187       | 57.01%  |
| 1 x AMD        | 37        | 11.28%  |
| Other          | 25        | 7.62%   |
| 1 x Matrox     | 23        | 7.01%   |
| 1 x ASPEED     | 20        | 6.1%    |
| 2 x Intel      | 12        | 3.66%   |
| 1 x Nvidia     | 12        | 3.66%   |
| Intel + Nvidia | 10        | 3.05%   |
| 2 x AMD        | 2         | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 289       | 88.11%  |
| Unknown     | 29        | 8.84%   |
| Proprietary | 10        | 3.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 304       | 92.68%  |
| 0.01-0.5   | 8         | 2.44%   |
| 1.01-2.0   | 6         | 1.83%   |
| 7.01-8.0   | 5         | 1.52%   |
| 0.51-1.0   | 4         | 1.22%   |
| 3.01-4.0   | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 11        | 14.47%  |
| Chimei Innolux          | 9         | 11.84%  |
| Samsung Electronics     | 8         | 10.53%  |
| AU Optronics            | 8         | 10.53%  |
| BOE                     | 7         | 9.21%   |
| Apple                   | 6         | 7.89%   |
| Iiyama                  | 5         | 6.58%   |
| Lenovo                  | 3         | 3.95%   |
| Goldstar                | 3         | 3.95%   |
| Dell                    | 3         | 3.95%   |
| Sony                    | 2         | 2.63%   |
| Sharp                   | 2         | 2.63%   |
| Philips                 | 2         | 2.63%   |
| ViewSonic               | 1         | 1.32%   |
| PANDA                   | 1         | 1.32%   |
| Fujitsu Siemens         | 1         | 1.32%   |
| Chi Mei Optoelectronics | 1         | 1.32%   |
| ASUSTek Computer        | 1         | 1.32%   |
| AOC                     | 1         | 1.32%   |
| Acer                    | 1         | 1.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Philips PHL 328E1 PHLC204 3840x2160 700x390mm 31.5-inch              | 2         | 2.6%    |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch          | 2         | 2.6%    |
| ViewSonic LCD Monitor VX3276-QHD 2560x1440                           | 1         | 1.3%    |
| Sony TV SNYC901 1920x1080                                            | 1         | 1.3%    |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                        | 1         | 1.3%    |
| Sharp LCD Monitor SHP1461 3200x1800 290x170mm 13.2-inch              | 1         | 1.3%    |
| Sharp LCD Monitor SHP1453 1920x1080 350x190mm 15.7-inch              | 1         | 1.3%    |
| Samsung Electronics SyncMaster SAM027F 1680x1050 470x300mm 22.0-inch | 1         | 1.3%    |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch | 1         | 1.3%    |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 530x300mm 24.0-inch    | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC4541 1280x800 260x160mm 12.0-inch | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch | 1         | 1.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch    | 1         | 1.3%    |
| PANDA LC133LF1L02 NCP0019 1920x1080 290x170mm 13.2-inch              | 1         | 1.3%    |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch         | 1         | 1.3%    |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch         | 1         | 1.3%    |
| LG Display LCD Monitor LGD0450 1366x768 280x160mm 12.7-inch          | 1         | 1.3%    |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 1         | 1.3%    |
| LG Display LCD Monitor LGD0414 1920x1080 280x160mm 12.7-inch         | 1         | 1.3%    |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch         | 1         | 1.3%    |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch          | 1         | 1.3%    |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 1         | 1.3%    |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch          | 1         | 1.3%    |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 1         | 1.3%    |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch              | 1         | 1.3%    |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch              | 1         | 1.3%    |
| Iiyama PLE2607WS IVM5608 1920x1080 550x340mm 25.5-inch               | 1         | 1.3%    |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch              | 1         | 1.3%    |
| Iiyama PL2740HS IVM6662 1920x1080 600x340mm 27.2-inch                | 1         | 1.3%    |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                 | 1         | 1.3%    |
| Iiyama PL2209HD IVM560B 1920x1080 480x270mm 21.7-inch                | 1         | 1.3%    |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch          | 1         | 1.3%    |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 1         | 1.3%    |
| Goldstar 34GK950F GSM7727 3440x1440 800x330mm 34.1-inch              | 1         | 1.3%    |
| Fujitsu Siemens L19-1 FUS07DB 1280x1024 380x300mm 19.1-inch          | 1         | 1.3%    |
| Dell UP2716D DEL40DD 2560x1440 600x340mm 27.2-inch                   | 1         | 1.3%    |
| Dell U2715H DELD065 2560x1440 600x340mm 27.2-inch                    | 1         | 1.3%    |
| Dell U2311H DELA060 1920x1080 510x290mm 23.1-inch                    | 1         | 1.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 39.47%  |
| 1366x768 (WXGA)    | 13        | 17.11%  |
| 2560x1440 (QHD)    | 7         | 9.21%   |
| 1280x800 (WXGA)    | 7         | 9.21%   |
| 3840x2160 (4K)     | 5         | 6.58%   |
| 1600x900 (HD+)     | 5         | 6.58%   |
| 3440x1440          | 2         | 2.63%   |
| 1680x1050 (WSXGA+) | 2         | 2.63%   |
| 3200x1800 (QHD+)   | 1         | 1.32%   |
| 2880x1800          | 1         | 1.32%   |
| 1920x515           | 1         | 1.32%   |
| 1600x1200          | 1         | 1.32%   |
| 1280x1024 (SXGA)   | 1         | 1.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 18        | 23.68%  |
| 15      | 16        | 21.05%  |
| 12      | 14        | 18.42%  |
| 27      | 8         | 10.53%  |
| 24      | 3         | 3.95%   |
| 23      | 3         | 3.95%   |
| 34      | 2         | 2.63%   |
| 31      | 2         | 2.63%   |
| 20      | 2         | 2.63%   |
| 17      | 2         | 2.63%   |
| Unknown | 2         | 2.63%   |
| 25      | 1         | 1.32%   |
| 22      | 1         | 1.32%   |
| 21      | 1         | 1.32%   |
| 19      | 1         | 1.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 26        | 34.67%  |
| 201-300     | 21        | 28%     |
| 501-600     | 14        | 18.67%  |
| 401-500     | 4         | 5.33%   |
| 601-700     | 3         | 4%      |
| 351-400     | 3         | 4%      |
| 701-800     | 2         | 2.67%   |
| Unknown     | 2         | 2.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 58        | 77.33%  |
| 16/10   | 10        | 13.33%  |
| 21/9    | 2         | 2.67%   |
| 5/4     | 1         | 1.33%   |
| 4/3     | 1         | 1.33%   |
| 3/2     | 1         | 1.33%   |
| 3.88    | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 15        | 19.74%  |
| 61-70          | 13        | 17.11%  |
| 91-100         | 11        | 14.47%  |
| 301-350        | 8         | 10.53%  |
| 201-250        | 7         | 9.21%   |
| 101-110        | 5         | 6.58%   |
| 351-500        | 4         | 5.26%   |
| 71-80          | 3         | 3.95%   |
| 151-200        | 3         | 3.95%   |
| 251-300        | 2         | 2.63%   |
| 121-130        | 2         | 2.63%   |
| Unknown        | 2         | 2.63%   |
| 1-40           | 1         | 1.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 25        | 33.78%  |
| 101-120       | 20        | 27.03%  |
| 51-100        | 14        | 18.92%  |
| 161-240       | 11        | 14.86%  |
| More than 240 | 2         | 2.7%    |
| Unknown       | 2         | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 248       | 75.61%  |
| 1     | 73        | 22.26%  |
| 2     | 7         | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 263       | 58.97%  |
| Realtek Semiconductor             | 90        | 20.18%  |
| Broadcom                          | 31        | 6.95%   |
| Qualcomm Atheros                  | 23        | 5.16%   |
| TP-Link                           | 5         | 1.12%   |
| IMC Networks                      | 4         | 0.9%    |
| AMD                               | 4         | 0.9%    |
| Ralink Technology                 | 3         | 0.67%   |
| Ralink                            | 3         | 0.67%   |
| Mellanox Technologies             | 3         | 0.67%   |
| Marvell Technology Group          | 3         | 0.67%   |
| Hewlett-Packard                   | 2         | 0.45%   |
| Edimax Technology                 | 2         | 0.45%   |
| U-Blox                            | 1         | 0.22%   |
| Sierra Wireless                   | 1         | 0.22%   |
| MediaTek                          | 1         | 0.22%   |
| Insyde Software                   | 1         | 0.22%   |
| Huawei Technologies               | 1         | 0.22%   |
| HMD Global                        | 1         | 0.22%   |
| Fibocom                           | 1         | 0.22%   |
| Ericsson Business Mobile Networks | 1         | 0.22%   |
| Chelsio Communications            | 1         | 0.22%   |
| ADMtek                            | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 77        | 14.13%  |
| Intel I211 Gigabit Network Connection                                         | 46        | 8.44%   |
| Intel I210 Gigabit Network Connection                                         | 33        | 6.06%   |
| Intel I350 Gigabit Network Connection                                         | 25        | 4.59%   |
| Intel 82574L Gigabit Network Connection                                       | 17        | 3.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 14        | 2.57%   |
| Intel Ethernet Controller I225-V                                              | 13        | 2.39%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 13        | 2.39%   |
| Intel Ethernet Controller I226-V                                              | 10        | 1.83%   |
| Intel Wi-Fi 6 AX200                                                           | 9         | 1.65%   |
| Intel Ethernet Connection (2) I219-V                                          | 8         | 1.47%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 7         | 1.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 6         | 1.1%    |
| Intel Ethernet Connection I217-LM                                             | 6         | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5         | 0.92%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 0.92%   |
| Intel Wireless 7265                                                           | 5         | 0.92%   |
| Intel Wireless 7260                                                           | 5         | 0.92%   |
| Intel Ethernet Connection X553 1GbE                                           | 5         | 0.92%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 5         | 0.92%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 5         | 0.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 4         | 0.73%   |
| Intel Wireless 8260                                                           | 4         | 0.73%   |
| Intel Wireless 3165                                                           | 4         | 0.73%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 4         | 0.73%   |
| Intel Ethernet Connection I354                                                | 4         | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 0.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 4         | 0.73%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 0.73%   |
| Intel 82576 Gigabit Network Connection                                        | 4         | 0.73%   |
| Intel 82567LM Gigabit Network Connection                                      | 4         | 0.73%   |
| AMD XGMAC 10GbE Controller                                                    | 4         | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 0.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 0.55%   |
| Intel Wireless-AC 9260                                                        | 3         | 0.55%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 3         | 0.55%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 3         | 0.55%   |
| Intel Ethernet Connection I218-LM                                             | 3         | 0.55%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3         | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 61        | 50.83%  |
| Qualcomm Atheros      | 20        | 16.67%  |
| Realtek Semiconductor | 11        | 9.17%   |
| Broadcom              | 10        | 8.33%   |
| TP-Link               | 4         | 3.33%   |
| IMC Networks          | 4         | 3.33%   |
| Ralink Technology     | 3         | 2.5%    |
| Ralink                | 3         | 2.5%    |
| Edimax Technology     | 2         | 1.67%   |
| Sierra Wireless       | 1         | 0.83%   |
| MediaTek              | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 9         | 7.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 5%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 4.17%   |
| Intel Wireless 8265 / 8275                                              | 5         | 4.17%   |
| Intel Wireless 7265                                                     | 5         | 4.17%   |
| Intel Wireless 7260                                                     | 5         | 4.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.33%   |
| Intel Wireless 8260                                                     | 4         | 3.33%   |
| Intel Wireless 3165                                                     | 4         | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 3.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 3.33%   |
| Intel Wireless-AC 9260                                                  | 3         | 2.5%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 2.5%    |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 3         | 2.5%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 2.5%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.67%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 1.67%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter         | 2         | 1.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2         | 1.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.67%   |
| Intel Wireless 3160                                                     | 2         | 1.67%   |
| Intel WiFi Link 5100                                                    | 2         | 1.67%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.67%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 1.67%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.67%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 1.67%   |
| TP-Link Wireless USB Adapter                                            | 1         | 0.83%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.83%   |
| Sierra Wireless EM7455                                                  | 1         | 0.83%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.83%   |
| Realtek RTL8192SU 802.11n WLAN Adapter                                  | 1         | 0.83%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.83%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                            | 1         | 0.83%   |
| Ralink RT3572 Wireless Adapter                                          | 1         | 0.83%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                            | 1         | 0.83%   |
| Ralink RT2800 802.11n PCI                                               | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 235       | 65.28%  |
| Realtek Semiconductor    | 83        | 23.06%  |
| Broadcom                 | 25        | 6.94%   |
| Qualcomm Atheros         | 5         | 1.39%   |
| AMD                      | 4         | 1.11%   |
| Marvell Technology Group | 3         | 0.83%   |
| TP-Link                  | 1         | 0.28%   |
| Insyde Software          | 1         | 0.28%   |
| HMD Global               | 1         | 0.28%   |
| Chelsio Communications   | 1         | 0.28%   |
| ADMtek                   | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 77        | 18.51%  |
| Intel I211 Gigabit Network Connection                                         | 46        | 11.06%  |
| Intel I210 Gigabit Network Connection                                         | 33        | 7.93%   |
| Intel I350 Gigabit Network Connection                                         | 25        | 6.01%   |
| Intel 82574L Gigabit Network Connection                                       | 17        | 4.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 14        | 3.37%   |
| Intel Ethernet Controller I225-V                                              | 13        | 3.13%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 13        | 3.13%   |
| Intel Ethernet Controller I226-V                                              | 10        | 2.4%    |
| Intel Ethernet Connection (2) I219-V                                          | 8         | 1.92%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 7         | 1.68%   |
| Intel Ethernet Connection I217-LM                                             | 6         | 1.44%   |
| Intel Ethernet Connection X553 1GbE                                           | 5         | 1.2%    |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 5         | 1.2%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 5         | 1.2%    |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 4         | 0.96%   |
| Intel Ethernet Connection I354                                                | 4         | 0.96%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 0.96%   |
| Intel 82576 Gigabit Network Connection                                        | 4         | 0.96%   |
| Intel 82567LM Gigabit Network Connection                                      | 4         | 0.96%   |
| AMD XGMAC 10GbE Controller                                                    | 4         | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 0.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 0.72%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 3         | 0.72%   |
| Intel Ethernet Connection I218-LM                                             | 3         | 0.72%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 0.72%   |
| Intel 82583V Gigabit Network Connection                                       | 3         | 0.72%   |
| Intel 82575GB Gigabit Network Connection                                      | 3         | 0.72%   |
| Intel 82575EB Gigabit Network Connection                                      | 3         | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3         | 0.72%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 2         | 0.48%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2         | 0.48%   |
| Intel Ethernet Connection I219-V                                              | 2         | 0.48%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.48%   |
| Intel Ethernet Connection I218-V                                              | 2         | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2         | 0.48%   |
| Intel Ethernet Connection (6) I219-V                                          | 2         | 0.48%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 309       | 72.88%  |
| WiFi     | 106       | 25%     |
| Unknown  | 6         | 1.42%   |
| Modem    | 3         | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 284       | 85.54%  |
| WiFi     | 48        | 14.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 115       | 35.17%  |
| 4     | 68        | 20.8%   |
| 1     | 42        | 12.84%  |
| 3     | 36        | 11.01%  |
| 6     | 25        | 7.65%   |
| 5     | 21        | 6.42%   |
| 0     | 6         | 1.83%   |
| 9     | 5         | 1.53%   |
| 8     | 4         | 1.22%   |
| 7     | 3         | 0.92%   |
| 12    | 1         | 0.31%   |
| 10    | 1         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 271       | 79.94%  |
| Yes  | 68        | 20.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 57.89%  |
| Cambridge Silicon Radio         | 7         | 9.21%   |
| Apple                           | 7         | 9.21%   |
| IMC Networks                    | 4         | 5.26%   |
| Broadcom                        | 4         | 5.26%   |
| Realtek Semiconductor           | 3         | 3.95%   |
| Foxconn / Hon Hai               | 2         | 2.63%   |
| TP-Link                         | 1         | 1.32%   |
| Qualcomm Atheros Communications | 1         | 1.32%   |
| Lite-On Technology              | 1         | 1.32%   |
| Hewlett-Packard                 | 1         | 1.32%   |
| Dell                            | 1         | 1.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 19        | 25%     |
| Intel AX200 Bluetooth                                  | 9         | 11.84%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 8         | 10.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 7         | 9.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 3         | 3.95%   |
| Apple Bluetooth Host Controller                        | 3         | 3.95%   |
| Realtek Bluetooth Adapter                              | 2         | 2.63%   |
| Intel AX201 Bluetooth                                  | 2         | 2.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]             | 2         | 2.63%   |
| TP-Link Bluetooth 5.0 USB Adapter                      | 1         | 1.32%   |
| Realtek RTL8723A Bluetooth                             | 1         | 1.32%   |
| Qualcomm Atheros AR3012 Bluetooth                      | 1         | 1.32%   |
| Lite-On Atheros AR3012 Bluetooth                       | 1         | 1.32%   |
| Intel Wireless-AC 3168 Bluetooth                       | 1         | 1.32%   |
| Intel Centrino Bluetooth Wireless Transceiver          | 1         | 1.32%   |
| Intel AX210 Bluetooth                                  | 1         | 1.32%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1            | 1         | 1.32%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS       | 1         | 1.32%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0            | 1         | 1.32%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 1.32%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]          | 1         | 1.32%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter           | 1         | 1.32%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth        | 1         | 1.32%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module            | 1         | 1.32%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                   | 1         | 1.32%   |
| Broadcom BCM2045B (BDC-2.1)                            | 1         | 1.32%   |
| Apple Built-in iSight (no firmware loaded)             | 1         | 1.32%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                   | 1         | 1.32%   |
| Apple Broadcom Built-in Bluetooth                      | 1         | 1.32%   |
| Apple Broadcom Bluetooth 2.1 module                    | 1         | 1.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 200       | 75.76%  |
| AMD                                          | 46        | 17.42%  |
| Nvidia                                       | 13        | 4.92%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.38%   |
| VIA Technologies                             | 1         | 0.38%   |
| Steinberg Soft-und Hardware                  | 1         | 0.38%   |
| Creative Labs                                | 1         | 0.38%   |
| Corsair                                      | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 16        | 4.91%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 15        | 4.6%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 4.6%    |
| Intel Broadwell-U Audio Controller                                                                | 15        | 4.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 4.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 4.29%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 3.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 3.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 3.07%   |
| Intel 200 Series PCH HD Audio                                                                     | 10        | 3.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 3.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 2.76%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 2.76%   |
| AMD FCH Azalia Controller                                                                         | 9         | 2.76%   |
| Intel Jasper Lake HD Audio                                                                        | 8         | 2.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 2.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 2.45%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 2.45%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 2.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 2.15%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 2.15%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 1.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.53%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 1.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.23%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 1.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.23%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 1.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.23%   |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 3         | 0.92%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 0.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.61%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.61%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.61%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 2         | 0.61%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 56        | 17.34%  |
| Kingston              | 45        | 13.93%  |
| SK hynix              | 39        | 12.07%  |
| Micron Technology     | 33        | 10.22%  |
| Unknown               | 26        | 8.05%   |
| Corsair               | 26        | 8.05%   |
| Crucial               | 24        | 7.43%   |
| Transcend             | 9         | 2.79%   |
| A-DATA Technology     | 8         | 2.48%   |
| G.Skill               | 7         | 2.17%   |
| Ramaxel Technology    | 5         | 1.55%   |
| Kimtigo               | 5         | 1.55%   |
| Apacer                | 5         | 1.55%   |
| Unknown (ABCD)        | 4         | 1.24%   |
| Teikon                | 3         | 0.93%   |
| Nanya Technology      | 3         | 0.93%   |
| Hewlett-Packard       | 3         | 0.93%   |
| Elpida                | 3         | 0.93%   |
| Toshiba               | 2         | 0.62%   |
| Team                  | 2         | 0.62%   |
| SK_Hynix              | 2         | 0.62%   |
| Patriot               | 2         | 0.62%   |
| Avant                 | 2         | 0.62%   |
| Unknown               | 2         | 0.62%   |
| Unknown (AB)          | 1         | 0.31%   |
| Unknown (07FB)        | 1         | 0.31%   |
| Tigo                  | 1         | 0.31%   |
| KomputerBay           | 1         | 0.31%   |
| Kingmax Semiconductor | 1         | 0.31%   |
| HPE                   | 1         | 0.31%   |
| GOODRAM               | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 5         | 1.48%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 5         | 1.48%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 4         | 1.18%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                          | 3         | 0.89%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s               | 3         | 0.89%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 3         | 0.89%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 3         | 0.89%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s              | 3         | 0.89%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s             | 3         | 0.89%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s             | 3         | 0.89%   |
| Apacer RAM 37352E4138334331 2GB SODIMM DDR3 1333MT/s              | 3         | 0.89%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 2         | 0.59%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 2         | 0.59%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 2         | 0.59%   |
| Teikon RAM TMTS8G58DFRBFEN-16 8GB SODIMM DDR3 1600MT/s            | 2         | 0.59%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 2400MT/s              | 2         | 0.59%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.59%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s              | 2         | 0.59%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 2         | 0.59%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                       | 2         | 0.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s               | 2         | 0.59%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 0.59%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 0.59%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s             | 2         | 0.59%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 2         | 0.59%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s               | 2         | 0.59%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s               | 2         | 0.59%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 2         | 0.59%   |
| Micron RAM 8ATF1G64AZ-2G3B1 8GB DIMM DDR4 2400MT/s                | 2         | 0.59%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s             | 2         | 0.59%   |
| Kingston RAM 9965669-031.A00G 16GB DIMM DDR4 2400MT/s             | 2         | 0.59%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.59%   |
| G.Skill RAM F4-3200C22-8GRS 8GB SODIMM DDR4 3200MT/s              | 2         | 0.59%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s             | 2         | 0.59%   |
| Crucial RAM CT102464BA160B.M16 8GB DIMM DDR3 1600MT/s             | 2         | 0.59%   |
| Corsair RAM CMSO8GX4M1A2133C15 8GB SODIMM DDR4 2133MT/s           | 2         | 0.59%   |
| A-DATA RAM Module 4GB DIMM DDR4 1866MT/s                          | 2         | 0.59%   |
| Unknown                                                           | 2         | 0.59%   |
| Unknown RAM WPBS16D308SWD-4G 4GB DIMM DDR3 1600MT/s               | 1         | 0.3%    |
| Unknown RAM Module 8GB SODIMM LPDDR3 1867MT/s                     | 1         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 134       | 47.02%  |
| DDR4    | 121       | 42.46%  |
| DDR2    | 12        | 4.21%   |
| LPDDR4  | 5         | 1.75%   |
| Unknown | 5         | 1.75%   |
| DDR5    | 3         | 1.05%   |
| LPDDR3  | 2         | 0.7%    |
| SDRAM   | 1         | 0.35%   |
| LPDDR5  | 1         | 0.35%   |
| DDR     | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 141       | 49.3%   |
| DIMM         | 135       | 47.2%   |
| Row Of Chips | 4         | 1.4%    |
| Chip         | 3         | 1.05%   |
| Unknown      | 3         | 1.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 128       | 41.42%  |
| 4096  | 99        | 32.04%  |
| 2048  | 37        | 11.97%  |
| 16384 | 35        | 11.33%  |
| 32768 | 5         | 1.62%   |
| 1024  | 5         | 1.62%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 88        | 29.53%  |
| 1333    | 41        | 13.76%  |
| 2400    | 32        | 10.74%  |
| 2667    | 28        | 9.4%    |
| 2133    | 28        | 9.4%    |
| 3200    | 24        | 8.05%   |
| 2666    | 7         | 2.35%   |
| 800     | 7         | 2.35%   |
| 667     | 6         | 2.01%   |
| 3000    | 5         | 1.68%   |
| 1867    | 5         | 1.68%   |
| 1866    | 5         | 1.68%   |
| 1334    | 4         | 1.34%   |
| 4800    | 3         | 1.01%   |
| 1066    | 3         | 1.01%   |
| Unknown | 3         | 1.01%   |
| 2933    | 2         | 0.67%   |
| 1067    | 2         | 0.67%   |
| 6400    | 1         | 0.34%   |
| 4267    | 1         | 0.34%   |
| 3600    | 1         | 0.34%   |
| 3400    | 1         | 0.34%   |
| 533     | 1         | 0.34%   |

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


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 17        | 34.69%  |
| Realtek Semiconductor                  | 6         | 12.24%  |
| IMC Networks                           | 6         | 12.24%  |
| Lite-On Technology                     | 4         | 8.16%   |
| Microdia                               | 3         | 6.12%   |
| Bison Electronics                      | 3         | 6.12%   |
| Apple                                  | 3         | 6.12%   |
| Alcor Micro                            | 2         | 4.08%   |
| Sunplus Innovation Technology          | 1         | 2.04%   |
| Sonix Technology                       | 1         | 2.04%   |
| Ricoh                                  | 1         | 2.04%   |
| Logitech                               | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 4         | 8.16%   |
| IMC Networks Integrated Camera                | 3         | 6.12%   |
| Realtek USB Camera                            | 2         | 4.08%   |
| Realtek Integrated_Webcam_HD                  | 2         | 4.08%   |
| Microdia Integrated_Webcam_HD                 | 2         | 4.08%   |
| Lite-On Integrated Camera                     | 2         | 4.08%   |
| Chicony Realtek DMFT RGB                      | 2         | 4.08%   |
| Chicony Chicony USB2.0 Camera                 | 2         | 4.08%   |
| Bison Integrated Camera                       | 2         | 4.08%   |
| Apple FaceTime HD Camera                      | 2         | 4.08%   |
| Sunplus Laptop Integrated Webcam HD           | 1         | 2.04%   |
| Sonix FHD Webcam                              | 1         | 2.04%   |
| Ricoh USB2.0 Camera                           | 1         | 2.04%   |
| Realtek Lenovo EasyCamera                     | 1         | 2.04%   |
| Realtek Integrated Webcam HD                  | 1         | 2.04%   |
| Microdia Dell Integrated HD Webcam            | 1         | 2.04%   |
| Logitech HD Pro Webcam C920                   | 1         | 2.04%   |
| Lite-On TOSHIBA Web Camera - HD               | 1         | 2.04%   |
| Lite-On HP Universal Camera                   | 1         | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam             | 1         | 2.04%   |
| IMC Networks Realtek PC Camera                | 1         | 2.04%   |
| IMC Networks EasyCamera                       | 1         | 2.04%   |
| Chicony VGA Webcam                            | 1         | 2.04%   |
| Chicony thinkpad t430s camera                 | 1         | 2.04%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 2.04%   |
| Chicony Integrated IR Camera                  | 1         | 2.04%   |
| Chicony Integrated Camera (1280x720@30)       | 1         | 2.04%   |
| Chicony HP Wide Vision HD Camera              | 1         | 2.04%   |
| Chicony HP Webcam [2 MP]                      | 1         | 2.04%   |
| Chicony HD WebCam (Acer)                      | 1         | 2.04%   |
| Chicony HD Webcam                             | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 1         | 2.04%   |
| Bison Lenovo EasyCamera                       | 1         | 2.04%   |
| Apple FaceTime HD Camera (Built-in)           | 1         | 2.04%   |
| Alcor Micro ASUS USB2.0 WebCam                | 1         | 2.04%   |
| Alcor Micro Asus Integrated Webcam            | 1         | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 2         | 28.57%  |
| Synaptics          | 2         | 28.57%  |
| AuthenTec          | 2         | 28.57%  |
| STMicroelectronics | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 14.29%  |
| Validity Sensors Synaptics WBDI                   | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader             | 1         | 14.29%  |
| AuthenTec AES2810                                 | 1         | 14.29%  |
| AuthenTec AES1660 Fingerprint Sensor              | 1         | 14.29%  |

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
| 1     | 158       | 47.59%  |
| 0     | 102       | 30.72%  |
| 2     | 46        | 13.86%  |
| 3     | 20        | 6.02%   |
| 4     | 6         | 1.81%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 204       | 69.62%  |
| Bluetooth                | 24        | 8.19%   |
| Net/wireless             | 23        | 7.85%   |
| Card reader              | 16        | 5.46%   |
| Firewire controller      | 6         | 2.05%   |
| Fingerprint reader       | 6         | 2.05%   |
| Net/ethernet             | 4         | 1.37%   |
| Graphics card            | 4         | 1.37%   |
| Storage/ata              | 3         | 1.02%   |
| Storage/raid             | 1         | 0.34%   |
| Storage                  | 1         | 0.34%   |
| Sound                    | 1         | 0.34%   |

