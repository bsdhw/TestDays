BSD in Australia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for BSD in Australia.

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

Total: 102

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Shuttle       | DS77U                       | [6bf60f3010](https://bsd-hardware.info/?probe=6bf60f3010) | Dec 27, 2025 |
| Dynabook      | TECRA A65-M                 | [840b58a6a7](https://bsd-hardware.info/?probe=840b58a6a7) | Dec 13, 2025 |
| Lenovo        | LOQ 15IRX9 83DV             | [dd92947fcc](https://bsd-hardware.info/?probe=dd92947fcc) | Nov 18, 2025 |
| Apple         | MacBookPro7,1               | [f4e3b1813c](https://bsd-hardware.info/?probe=f4e3b1813c) | Oct 31, 2025 |
| HP            | EliteBook 850 G2            | [735796bf17](https://bsd-hardware.info/?probe=735796bf17) | Sep 11, 2025 |
| HP            | EliteBook 850 G2            | [cf6d05a5d4](https://bsd-hardware.info/?probe=cf6d05a5d4) | Sep 07, 2025 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [b4dfb3fe25](https://bsd-hardware.info/?probe=b4dfb3fe25) | Sep 04, 2025 |
| Deciso        | NetBoard-A10_Gen.3          | [542252ee3c](https://bsd-hardware.info/?probe=542252ee3c) | Aug 23, 2025 |
| Lenovo        | ThinkPad P50 20EQS4RV00     | [370957ec7c](https://bsd-hardware.info/?probe=370957ec7c) | May 08, 2025 |
| Lenovo        | ThinkPad X390 20Q1S30100    | [10f654b932](https://bsd-hardware.info/?probe=10f654b932) | Apr 12, 2025 |
| Dell          | G16 7630                    | [3b19a7c28a](https://bsd-hardware.info/?probe=3b19a7c28a) | Mar 29, 2025 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS4... | [8e22203722](https://bsd-hardware.info/?probe=8e22203722) | Feb 24, 2025 |
| Framework     | Laptop (12th Gen Intel C... | [7a0b5ab0c5](https://bsd-hardware.info/?probe=7a0b5ab0c5) | Feb 22, 2025 |
| Deciso        | NetBoard-A10_Gen.3          | [e9045ae700](https://bsd-hardware.info/?probe=e9045ae700) | Feb 13, 2025 |
| Toshiba       | Satellite L50D-C            | [f8d95e1977](https://bsd-hardware.info/?probe=f8d95e1977) | Feb 12, 2025 |
| Lenovo        | ThinkPad P50 20EQS4RV00     | [f4361f3b6f](https://bsd-hardware.info/?probe=f4361f3b6f) | Jan 23, 2025 |
| Dell          | Latitude E5520              | [e8415a5758](https://bsd-hardware.info/?probe=e8415a5758) | Jan 05, 2025 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [b659f5f797](https://bsd-hardware.info/?probe=b659f5f797) | Dec 03, 2024 |
| HP            | EliteBook 840 G5            | [1abb405f84](https://bsd-hardware.info/?probe=1abb405f84) | Nov 24, 2024 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [b16a33c476](https://bsd-hardware.info/?probe=b16a33c476) | Nov 17, 2024 |
| Lenovo        | ThinkPad T490 20N2S0QE00    | [4ea2230818](https://bsd-hardware.info/?probe=4ea2230818) | Oct 15, 2024 |
| Lenovo        | ThinkPad T490 20N2S0QE00    | [b7f189a238](https://bsd-hardware.info/?probe=b7f189a238) | Oct 14, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [869d37ac5e](https://bsd-hardware.info/?probe=869d37ac5e) | Oct 04, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [9aea4f42bc](https://bsd-hardware.info/?probe=9aea4f42bc) | Sep 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [91106574a4](https://bsd-hardware.info/?probe=91106574a4) | Aug 24, 2024 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [14634a95c5](https://bsd-hardware.info/?probe=14634a95c5) | Jul 29, 2024 |
| ASUSTek       | U50Vg                       | [02c8f9cdf5](https://bsd-hardware.info/?probe=02c8f9cdf5) | Jul 06, 2024 |
| Google        | Ultima                      | [732adeb5e4](https://bsd-hardware.info/?probe=732adeb5e4) | Feb 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [6a78256797](https://bsd-hardware.info/?probe=6a78256797) | Feb 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [2c33e6e9e7](https://bsd-hardware.info/?probe=2c33e6e9e7) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ed79ea60c4](https://bsd-hardware.info/?probe=ed79ea60c4) | Nov 13, 2023 |
| Dell          | XPS 13 9360                 | [c7d016caa9](https://bsd-hardware.info/?probe=c7d016caa9) | Nov 04, 2023 |
| Dell          | G16 7630                    | [deb5f3bd32](https://bsd-hardware.info/?probe=deb5f3bd32) | Oct 21, 2023 |
| Unknown       | Unknown                     | [9c6c7f9d6b](https://bsd-hardware.info/?probe=9c6c7f9d6b) | Oct 10, 2023 |
| Dell          | G16 7630                    | [4e39a5ebdf](https://bsd-hardware.info/?probe=4e39a5ebdf) | Sep 21, 2023 |
| Lenovo        | ThinkPad L390 20NRS00Q00    | [b9885ea126](https://bsd-hardware.info/?probe=b9885ea126) | Sep 17, 2023 |
| Lenovo        | ThinkPad T480s 20L7S24F0... | [bb7eb8b380](https://bsd-hardware.info/?probe=bb7eb8b380) | Sep 15, 2023 |
| HP            | Pavilion dv5                | [b7dad77d0d](https://bsd-hardware.info/?probe=b7dad77d0d) | Sep 14, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | [2e6af170b9](https://bsd-hardware.info/?probe=2e6af170b9) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [0ebdda5146](https://bsd-hardware.info/?probe=0ebdda5146) | Aug 31, 2023 |
| Dell          | G5 5590                     | [2e496efada](https://bsd-hardware.info/?probe=2e496efada) | Aug 26, 2023 |
| Dell          | G5 5590                     | [fd4f457391](https://bsd-hardware.info/?probe=fd4f457391) | Aug 26, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [60dac781b2](https://bsd-hardware.info/?probe=60dac781b2) | Jul 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BK0... | [01f4886e09](https://bsd-hardware.info/?probe=01f4886e09) | Jul 21, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [4274ca291e](https://bsd-hardware.info/?probe=4274ca291e) | Jul 08, 2023 |
| Dell          | XPS 13 9360                 | [648c09752f](https://bsd-hardware.info/?probe=648c09752f) | Jun 27, 2023 |
| HP            | Compaq 6830s                | [1a06917a0f](https://bsd-hardware.info/?probe=1a06917a0f) | Jun 14, 2023 |
| Timi          | TM1701                      | [1dd768a721](https://bsd-hardware.info/?probe=1dd768a721) | May 25, 2023 |
| Intel Clie... | LAPBC510                    | [68b1300903](https://bsd-hardware.info/?probe=68b1300903) | Apr 22, 2023 |
| Unknown       | Unknown                     | [ee06e14aa2](https://bsd-hardware.info/?probe=ee06e14aa2) | Mar 29, 2023 |
| Acer          | Nitro AN515-55              | [e023282dcd](https://bsd-hardware.info/?probe=e023282dcd) | Mar 13, 2023 |
| ASUSTek       | G74Sx                       | [6b7cf8fcac](https://bsd-hardware.info/?probe=6b7cf8fcac) | Mar 13, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [4d69517a13](https://bsd-hardware.info/?probe=4d69517a13) | Feb 07, 2023 |
| Lenovo        | ThinkPad X131e 33672K5      | [4cc4d44e43](https://bsd-hardware.info/?probe=4cc4d44e43) | Aug 15, 2022 |
| Dell          | G5 5590                     | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| HP            | ZBook 14                    | [a646255b51](https://bsd-hardware.info/?probe=a646255b51) | May 02, 2022 |
| Lenovo        | ThinkPad T470 20HES0ES1F    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| HP            | Notebook                    | [eea4cff90b](https://bsd-hardware.info/?probe=eea4cff90b) | Apr 27, 2022 |
| HP            | Notebook                    | [eaff4f0fbf](https://bsd-hardware.info/?probe=eaff4f0fbf) | Apr 19, 2022 |
| HP            | Notebook                    | [6a112cfe6c](https://bsd-hardware.info/?probe=6a112cfe6c) | Apr 11, 2022 |
| HP            | Notebook                    | [a31dd5f48d](https://bsd-hardware.info/?probe=a31dd5f48d) | Apr 11, 2022 |
| Dell          | G5 5590                     | [0871c1269b](https://bsd-hardware.info/?probe=0871c1269b) | Mar 07, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [51b0a953b5](https://bsd-hardware.info/?probe=51b0a953b5) | Feb 22, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [85441a65a9](https://bsd-hardware.info/?probe=85441a65a9) | Feb 21, 2022 |
| Dell          | Latitude E7450              | [8a3867f171](https://bsd-hardware.info/?probe=8a3867f171) | Feb 03, 2022 |
| Toshiba       | Satellite L50-A             | [94b87158aa](https://bsd-hardware.info/?probe=94b87158aa) | Jan 21, 2022 |
| Apple         | MacBookPro5,5               | [53b106bbb6](https://bsd-hardware.info/?probe=53b106bbb6) | Jan 16, 2022 |
| HP            | Laptop 15s-du1xxx           | [8ebeac18ca](https://bsd-hardware.info/?probe=8ebeac18ca) | Nov 19, 2021 |
| Lenovo        | ThinkPad Mini10 3507A31     | [ced0819a8e](https://bsd-hardware.info/?probe=ced0819a8e) | Oct 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [2494d9d2db](https://bsd-hardware.info/?probe=2494d9d2db) | Sep 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [28bbeb8b2e](https://bsd-hardware.info/?probe=28bbeb8b2e) | Sep 26, 2021 |
| Lenovo        | G40-70 20369                | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| Intel         | SandyBridge Platform        | [f0aaf635c3](https://bsd-hardware.info/?probe=f0aaf635c3) | Sep 02, 2021 |
| Toshiba       | PORTEGE Z10t-A              | [cb7cbd17d0](https://bsd-hardware.info/?probe=cb7cbd17d0) | Jun 20, 2021 |
| Apple         | MacBookPro11,3              | [1c9feef8e7](https://bsd-hardware.info/?probe=1c9feef8e7) | May 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [821c81e652](https://bsd-hardware.info/?probe=821c81e652) | Apr 09, 2021 |
| ASUSTek       | TP500LNG                    | [6501322932](https://bsd-hardware.info/?probe=6501322932) | Apr 06, 2021 |
| Dell          | G5 5590                     | [18863bc535](https://bsd-hardware.info/?probe=18863bc535) | Apr 05, 2021 |
| HP            | ProBook 430 G3              | [32dfd5e52a](https://bsd-hardware.info/?probe=32dfd5e52a) | Mar 22, 2021 |
| Unknown       | Unknown                     | [70304f9c5d](https://bsd-hardware.info/?probe=70304f9c5d) | Mar 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [950cf51db1](https://bsd-hardware.info/?probe=950cf51db1) | Feb 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a2833c6695](https://bsd-hardware.info/?probe=a2833c6695) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | [a201c5f713](https://bsd-hardware.info/?probe=a201c5f713) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | [d0a5d1cb86](https://bsd-hardware.info/?probe=d0a5d1cb86) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | [a51cf81e58](https://bsd-hardware.info/?probe=a51cf81e58) | Feb 06, 2021 |
| Toshiba       | KIRA                        | [1ee77fde0b](https://bsd-hardware.info/?probe=1ee77fde0b) | Jan 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [de7d8622aa](https://bsd-hardware.info/?probe=de7d8622aa) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [7f6ebffad8](https://bsd-hardware.info/?probe=7f6ebffad8) | Dec 18, 2020 |
| Lenovo        | ThinkPad T460p 20FXCTO1W... | [ddc907ccf4](https://bsd-hardware.info/?probe=ddc907ccf4) | Dec 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [1414d7ae80](https://bsd-hardware.info/?probe=1414d7ae80) | Dec 16, 2020 |
| ASUSTek       | K72F                        | [321cd9d139](https://bsd-hardware.info/?probe=321cd9d139) | Dec 08, 2020 |
| ASUSTek       | K72F                        | [b36ff0b052](https://bsd-hardware.info/?probe=b36ff0b052) | Dec 08, 2020 |
| HP            | Setzer                      | [da7914cdd5](https://bsd-hardware.info/?probe=da7914cdd5) | Nov 22, 2020 |
| Lenovo        | ThinkPad T450 20BVA020AU    | [5d8bce59e8](https://bsd-hardware.info/?probe=5d8bce59e8) | Nov 16, 2020 |
| Lenovo        | ThinkPad X230 2320JXM       | [cdbf62a168](https://bsd-hardware.info/?probe=cdbf62a168) | Oct 29, 2020 |
| Lenovo        | ThinkPad X60s 17033JM       | [67e701adb7](https://bsd-hardware.info/?probe=67e701adb7) | Oct 21, 2020 |
| Acer          | Peppy                       | [d68bd5cbb5](https://bsd-hardware.info/?probe=d68bd5cbb5) | Oct 02, 2020 |
| Acer          | Peppy                       | [26058cddbf](https://bsd-hardware.info/?probe=26058cddbf) | Oct 02, 2020 |
| Apple         | MacBookAir5,1               | [6cced6fcf0](https://bsd-hardware.info/?probe=6cced6fcf0) | Sep 23, 2020 |
| Lenovo        | ThinkPad T460p 20FXCTO1W... | [b62876dd94](https://bsd-hardware.info/?probe=b62876dd94) | Aug 04, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [e4d2dcda5b](https://bsd-hardware.info/?probe=e4d2dcda5b) | Jul 31, 2020 |
| Lenovo        | ThinkPad X220 4291C35       | [f22c83f68b](https://bsd-hardware.info/?probe=f22c83f68b) | May 31, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| helloSystem 0.8.1       | 5         | 5.62%   |
| FreeBSD 13.0            | 4         | 4.49%   |
| OpenBSD 6.8             | 3         | 3.37%   |
| helloSystem 0.4.0       | 3         | 3.37%   |
| FreeBSD 14.1            | 3         | 3.37%   |
| FreeBSD 13.2            | 3         | 3.37%   |
| OPNsense 22.1.6         | 2         | 2.25%   |
| OPNsense 21.1.3         | 2         | 2.25%   |
| OpenBSD 7.2             | 2         | 2.25%   |
| helloSystem 0.9.0       | 2         | 2.25%   |
| helloSystem 0.6.0       | 2         | 2.25%   |
| FreeBSD 15.0-PRERELEASE | 2         | 2.25%   |
| FreeBSD 14.2-p3         | 2         | 2.25%   |
| FreeBSD 14.2            | 2         | 2.25%   |
| FreeBSD 14.0-BETA2      | 2         | 2.25%   |
| FreeBSD 14.0            | 2         | 2.25%   |
| FreeBSD 12.2            | 2         | 2.25%   |
| FreeBSD 12.1-p10        | 2         | 2.25%   |
| FreeBSD 12.1            | 2         | 2.25%   |
| OPNsense 25.7.10        | 1         | 1.12%   |
| OPNsense 25.4.2         | 1         | 1.12%   |
| OPNsense 24.7.9         | 1         | 1.12%   |
| OPNsense 24.10.2        | 1         | 1.12%   |
| OPNsense 24.1.9         | 1         | 1.12%   |
| OPNsense 23.7.3         | 1         | 1.12%   |
| OPNsense 23.1.4         | 1         | 1.12%   |
| OPNsense 22.1.1         | 1         | 1.12%   |
| OPNsense 21.7.1         | 1         | 1.12%   |
| OPNsense 21.7           | 1         | 1.12%   |
| OpenBSD 6.7             | 1         | 1.12%   |
| NomadBSD 81e34fc3       | 1         | 1.12%   |
| NomadBSD 20231013       | 1         | 1.12%   |
| NomadBSD 1.4            | 1         | 1.12%   |
| NetBSD 10.1             | 1         | 1.12%   |
| helloSystem 0.5.0       | 1         | 1.12%   |
| GhostBSD 25.02-R14.3p2  | 1         | 1.12%   |
| GhostBSD 24.07.3        | 1         | 1.12%   |
| FuguIta 7.1             | 1         | 1.12%   |
| FreeBSD 15.0-STABLE     | 1         | 1.12%   |
| FreeBSD 15.0-CURRENT    | 1         | 1.12%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 40        | 50%     |
| OPNsense    | 14        | 17.5%   |
| helloSystem | 13        | 16.25%  |
| OpenBSD     | 6         | 7.5%    |
| NomadBSD    | 3         | 3.75%   |
| GhostBSD    | 2         | 2.5%    |
| NetBSD      | 1         | 1.25%   |
| FuguIta     | 1         | 1.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 79        | 98.75%  |
| i386  | 1         | 1.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Console      | 23        | 27.38%  |
| helloDesktop | 16        | 19.05%  |
| XFCE         | 7         | 8.33%   |
| KDE5         | 5         | 5.95%   |
| i3           | 5         | 5.95%   |
| GNOME        | 5         | 5.95%   |
| TWM          | 4         | 4.76%   |
| fvwm         | 4         | 4.76%   |
| Openbox      | 3         | 3.57%   |
| MATE         | 3         | 3.57%   |
| Fluxbox      | 2         | 2.38%   |
| wlroots      | 1         | 1.19%   |
| sway         | 1         | 1.19%   |
| Picom        | 1         | 1.19%   |
| KDE6         | 1         | 1.19%   |
| KDE          | 1         | 1.19%   |
| Budgie       | 1         | 1.19%   |
| AwesomeWM    | 1         | 1.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 55        | 67.9%   |
| Console | 19        | 23.46%  |
| Wayland | 7         | 8.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 43        | 51.81%  |
| SLiM    | 17        | 20.48%  |
| SDDM    | 10        | 12.05%  |
| LightDM | 7         | 8.43%   |
| XDM     | 2         | 2.41%   |
| GDM     | 2         | 2.41%   |
| PCDM    | 1         | 1.2%    |
| Ly      | 1         | 1.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| Unknown         | 33        | 39.76%  |
| C               | 22        | 26.51%  |
| en_US           | 15        | 18.07%  |
| en_AU           | 11        | 13.25%  |
| en_AU.US-ASCII  | 1         | 1.2%    |
| en_AU.ISO8859-1 | 1         | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 69        | 86.25%  |
| BIOS | 11        | 13.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 45        | 56.25%  |
| Ufs    | 23        | 28.75%  |
| Ffs    | 7         | 8.75%   |
| Cd9660 | 5         | 6.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 73        | 91.25%  |
| MBR  | 7         | 8.75%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 34        | 42.5%   |
| Hewlett-Packard      | 10        | 12.5%   |
| Dell                 | 7         | 8.75%   |
| Toshiba              | 4         | 5%      |
| ASUSTek Computer     | 4         | 5%      |
| Apple                | 4         | 5%      |
| Unknown              | 3         | 3.75%   |
| Framework            | 2         | 2.5%    |
| Deciso               | 2         | 2.5%    |
| Acer                 | 2         | 2.5%    |
| Timi                 | 1         | 1.25%   |
| Shuttle              | 1         | 1.25%   |
| Samsung Electronics  | 1         | 1.25%   |
| ReachingTech         | 1         | 1.25%   |
| Intel Client Systems | 1         | 1.25%   |
| Intel                | 1         | 1.25%   |
| Google               | 1         | 1.25%   |
| Dynabook             | 1         | 1.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 3         | 3.75%   |
| HP EliteBook 850 G2                                                                      | 2         | 2.5%    |
| Framework Laptop (12th Gen Intel Core)                                                   | 2         | 2.5%    |
| Dell XPS 13 9360                                                                         | 2         | 2.5%    |
| Dell G5 5590                                                                             | 2         | 2.5%    |
| Deciso NetBoard-A10_Gen.3                                                                | 2         | 2.5%    |
| Toshiba Satellite L50D-C                                                                 | 1         | 1.25%   |
| Toshiba Satellite L50-A                                                                  | 1         | 1.25%   |
| Toshiba PORTEGE Z10t-A                                                                   | 1         | 1.25%   |
| Toshiba KIRA                                                                             | 1         | 1.25%   |
| Timi TM1701                                                                              | 1         | 1.25%   |
| Shuttle DS77U                                                                            | 1         | 1.25%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 1.25%   |
| ReachingTech DreamQuest Pro 2022                                                         | 1         | 1.25%   |
| Lenovo ThinkPad X60s 17033JM                                                             | 1         | 1.25%   |
| Lenovo ThinkPad X390 20Q1S30100                                                          | 1         | 1.25%   |
| Lenovo ThinkPad X230 2320JXM                                                             | 1         | 1.25%   |
| Lenovo ThinkPad X220 4291C35                                                             | 1         | 1.25%   |
| Lenovo ThinkPad X1C 5th W10DG 20K3A03CAU                                                 | 1         | 1.25%   |
| Lenovo ThinkPad X131e 33672K5                                                            | 1         | 1.25%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XXS2XW00                                               | 1         | 1.25%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW                                              | 1         | 1.25%   |
| Lenovo ThinkPad X1 Carbon 7th 20R1CTO1WW                                                 | 1         | 1.25%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100                                                 | 1         | 1.25%   |
| Lenovo ThinkPad X1 Carbon 4th 20FC0019AU                                                 | 1         | 1.25%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB006FAU                                                 | 1         | 1.25%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU                                                 | 1         | 1.25%   |
| Lenovo ThinkPad X1 Carbon 3443CTO                                                        | 1         | 1.25%   |
| Lenovo ThinkPad T490 20N2S0QE00                                                          | 1         | 1.25%   |
| Lenovo ThinkPad T480s 20L7S24F00                                                         | 1         | 1.25%   |
| Lenovo ThinkPad T470 W10DG 20JNS0EM1D                                                    | 1         | 1.25%   |
| Lenovo ThinkPad T470 W10DG 20JM000BUS                                                    | 1         | 1.25%   |
| Lenovo ThinkPad T470 20HES0ES1F                                                          | 1         | 1.25%   |
| Lenovo ThinkPad T460p 20FXCTO1WW                                                         | 1         | 1.25%   |
| Lenovo ThinkPad T450 20BVA020AU                                                          | 1         | 1.25%   |
| Lenovo ThinkPad T440s 20ARS1BK08                                                         | 1         | 1.25%   |
| Lenovo ThinkPad P50 20EQS4RV00                                                           | 1         | 1.25%   |
| Lenovo ThinkPad P1 Gen 3 20TJS4T100                                                      | 1         | 1.25%   |
| Lenovo ThinkPad Mini10 3507A31                                                           | 1         | 1.25%   |
| Lenovo ThinkPad L390 20NRS00Q00                                                          | 1         | 1.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 29        | 36.25%  |
| Lenovo IdeaPad                | 3         | 3.75%   |
| HP EliteBook                  | 3         | 3.75%   |
| Unknown                       | 3         | 3.75%   |
| Toshiba Satellite             | 2         | 2.5%    |
| Framework Laptop              | 2         | 2.5%    |
| Dell XPS                      | 2         | 2.5%    |
| Dell Latitude                 | 2         | 2.5%    |
| Dell G5                       | 2         | 2.5%    |
| Deciso NetBoard-A10           | 2         | 2.5%    |
| Toshiba PORTEGE               | 1         | 1.25%   |
| Toshiba KIRA                  | 1         | 1.25%   |
| Timi TM1701                   | 1         | 1.25%   |
| Shuttle DS77U                 | 1         | 1.25%   |
| Samsung 350V5C                | 1         | 1.25%   |
| ReachingTech DreamQuest       | 1         | 1.25%   |
| Lenovo LOQ                    | 1         | 1.25%   |
| Lenovo G40-70                 | 1         | 1.25%   |
| Intel SandyBridge             | 1         | 1.25%   |
| Intel Client Systems LAPBC510 | 1         | 1.25%   |
| HP ZBook                      | 1         | 1.25%   |
| HP Setzer                     | 1         | 1.25%   |
| HP ProBook                    | 1         | 1.25%   |
| HP Pavilion                   | 1         | 1.25%   |
| HP Notebook                   | 1         | 1.25%   |
| HP Laptop                     | 1         | 1.25%   |
| HP Compaq                     | 1         | 1.25%   |
| Google Ultima                 | 1         | 1.25%   |
| Dynabook TECRA                | 1         | 1.25%   |
| Dell G16                      | 1         | 1.25%   |
| ASUS U50Vg                    | 1         | 1.25%   |
| ASUS TP500LNG                 | 1         | 1.25%   |
| ASUS K72F                     | 1         | 1.25%   |
| ASUS G74Sx                    | 1         | 1.25%   |
| Apple MacBookPro7             | 1         | 1.25%   |
| Apple MacBookPro5             | 1         | 1.25%   |
| Apple MacBookPro11            | 1         | 1.25%   |
| Apple MacBookAir5             | 1         | 1.25%   |
| Acer Peppy                    | 1         | 1.25%   |
| Acer Nitro                    | 1         | 1.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 9         | 11.25%  |
| 2017 | 8         | 10%     |
| 2022 | 7         | 8.75%   |
| 2016 | 6         | 7.5%    |
| 2023 | 5         | 6.25%   |
| 2019 | 5         | 6.25%   |
| 2015 | 5         | 6.25%   |
| 2014 | 5         | 6.25%   |
| 2021 | 4         | 5%      |
| 2018 | 4         | 5%      |
| 2013 | 4         | 5%      |
| 2012 | 4         | 5%      |
| 2011 | 3         | 3.75%   |
| 2009 | 3         | 3.75%   |
| 2025 | 2         | 2.5%    |
| 2024 | 2         | 2.5%    |
| 2010 | 2         | 2.5%    |
| 2008 | 1         | 1.25%   |
| 2007 | 1         | 1.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 80        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 77        | 96.25%  |
| Yes  | 3         | 3.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 30        | 37.5%   |
| 16.01-24.0  | 28        | 35%     |
| 4.01-8.0    | 11        | 13.75%  |
| 32.01-64.0  | 4         | 5%      |
| 64.01-256.0 | 2         | 2.5%    |
| 1.01-2.0    | 2         | 2.5%    |
| 3.01-4.0    | 1         | 1.25%   |
| 24.01-32.0  | 1         | 1.25%   |
| 2.01-3.0    | 1         | 1.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 34        | 41.98%  |
| 0.01-0.5 | 30        | 37.04%  |
| 1.01-2.0 | 9         | 11.11%  |
| 2.01-3.0 | 4         | 4.94%   |
| 4.01-8.0 | 2         | 2.47%   |
| 0        | 1         | 1.23%   |
| Unknown  | 1         | 1.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 54        | 67.5%   |
| 0      | 20        | 25%     |
| 2      | 5         | 6.25%   |
| 3      | 1         | 1.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 67        | 83.75%  |
| Yes       | 13        | 16.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 82.5%   |
| No        | 14        | 17.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 92.5%   |
| No        | 6         | 7.5%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 71.6%   |
| No        | 23        | 28.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Australia | 80        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Sydney       | 26        | 32.1%   |
| Melbourne    | 15        | 18.52%  |
| Brisbane     | 11        | 13.58%  |
| Perth        | 9         | 11.11%  |
| Canberra     | 5         | 6.17%   |
| Adelaide     | 5         | 6.17%   |
| Warrnambool  | 1         | 1.23%   |
| South Yarra  | 1         | 1.23%   |
| Ryde         | 1         | 1.23%   |
| Kellyville   | 1         | 1.23%   |
| Gold Coast   | 1         | 1.23%   |
| East Malvern | 1         | 1.23%   |
| Darlinghurst | 1         | 1.23%   |
| Burwood      | 1         | 1.23%   |
| Ballarat     | 1         | 1.23%   |
| Adelaide CBD | 1         | 1.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 17     | 25.4%   |
| Toshiba             | 7         | 8      | 11.11%  |
| Seagate             | 5         | 6      | 7.94%   |
| Intel               | 5         | 5      | 7.94%   |
| WDC                 | 4         | 4      | 6.35%   |
| SanDisk             | 4         | 5      | 6.35%   |
| Crucial             | 4         | 5      | 6.35%   |
| SK hynix            | 2         | 4      | 3.17%   |
| NVMe                | 2         | 3      | 3.17%   |
| Kingston            | 2         | 2      | 3.17%   |
| WLW                 | 1         | 1      | 1.59%   |
| Silicon Motion      | 1         | 1      | 1.59%   |
| Lenovo              | 1         | 1      | 1.59%   |
| Jetflash            | 1         | 1      | 1.59%   |
| Integral            | 1         | 1      | 1.59%   |
| Hitachi             | 1         | 1      | 1.59%   |
| HGST                | 1         | 1      | 1.59%   |
| Gigabyte Technology | 1         | 1      | 1.59%   |
| Fujitsu             | 1         | 1      | 1.59%   |
| FORESEE             | 1         | 1      | 1.59%   |
| Dogfish             | 1         | 1      | 1.59%   |
| Apple               | 1         | 1      | 1.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Toshiba THNSF5256GPUK 256GB        | 2         | 3.13%   |
| SanDisk SD6SB1M-128G-1006 128GB    | 2         | 3.13%   |
| Samsung SSD 840 EVO 250GB          | 2         | 3.13%   |
| Crucial CT1000BX500SSD1 1TB        | 2         | 3.13%   |
| WLW essentials 4GB                 | 1         | 1.56%   |
| WDC WDS480G2G0A-00JH30 480GB       | 1         | 1.56%   |
| WDC WD3200BEVT-00SCST0 320GB       | 1         | 1.56%   |
| WDC WD2500BEVS-22UST0 250GB        | 1         | 1.56%   |
| WDC WD10JPVX-60JC3T0 1TB           | 1         | 1.56%   |
| Toshiba THNSNF256GMCS 256GB        | 1         | 1.56%   |
| Toshiba THNSF5256GCJ7 256GB        | 1         | 1.56%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1.56%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1.56%   |
| Toshiba MK2555GSXF 250GB           | 1         | 1.56%   |
| SK hynix PC401 NVMe 512GB          | 1         | 1.56%   |
| SK hynix BC501 NVMe 512GB          | 1         | 1.56%   |
| Silicon Motion Aura Pro X2 960GB   | 1         | 1.56%   |
| Seagate ST9750420AS 752GB          | 1         | 1.56%   |
| Seagate ST9500325AS 500GB          | 1         | 1.56%   |
| Seagate ST9250315ASG 250GB         | 1         | 1.56%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1.56%   |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 1.56%   |
| SanDisk SD8TN8U256G1001 256GB      | 1         | 1.56%   |
| SanDisk SD5SG2128G1052E 128GB      | 1         | 1.56%   |
| Samsung SSD PM871 mSATA 256GB      | 1         | 1.56%   |
| Samsung SSD 980 1TB                | 1         | 1.56%   |
| Samsung SSD 860 EVO 500GB          | 1         | 1.56%   |
| Samsung PM961 NVMe 256GB           | 1         | 1.56%   |
| Samsung MZVLB512HBJQ-000H1 512GB   | 1         | 1.56%   |
| Samsung MZVLB256HAHQ-000L7 256GB   | 1         | 1.56%   |
| Samsung MZVLB256HAHQ-00000 256GB   | 1         | 1.56%   |
| Samsung MZVL2512HCJQ-00BL7 512GB   | 1         | 1.56%   |
| Samsung MZVL2512HCJQ-00B00 512GB   | 1         | 1.56%   |
| Samsung MZNLN512HMJP-000L7 512GB   | 1         | 1.56%   |
| Samsung MZNLN256HCHP-000L7 256GB   | 1         | 1.56%   |
| Samsung MZMTE128HMGR-00000 128GB   | 1         | 1.56%   |
| Samsung MZALQ512HBLU-00BL2 512GB   | 1         | 1.56%   |
| Samsung MZ7PC128HAFU-000L1 128GB   | 1         | 1.56%   |
| NVMe WD_BLACK SN850X 1TB           | 1         | 1.56%   |
| NVMe WD Blue SN570 2T              | 1         | 1.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 5         | 6      | 27.78%  |
| WDC      | 3         | 3      | 16.67%  |
| Toshiba  | 3         | 3      | 16.67%  |
| NVMe     | 2         | 2      | 11.11%  |
| WLW      | 1         | 1      | 5.56%   |
| Jetflash | 1         | 1      | 5.56%   |
| Hitachi  | 1         | 1      | 5.56%   |
| HGST     | 1         | 1      | 5.56%   |
| Fujitsu  | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 27.59%  |
| SanDisk             | 4         | 5      | 13.79%  |
| Intel               | 4         | 4      | 13.79%  |
| Crucial             | 4         | 5      | 13.79%  |
| Kingston            | 2         | 2      | 6.9%    |
| WDC                 | 1         | 1      | 3.45%   |
| Toshiba             | 1         | 1      | 3.45%   |
| NVMe                | 1         | 1      | 3.45%   |
| Integral            | 1         | 1      | 3.45%   |
| FORESEE             | 1         | 1      | 3.45%   |
| Dogfish             | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 28        | 32     | 44.44%  |
| HDD  | 18        | 19     | 28.57%  |
| NVMe | 17        | 20     | 26.98%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 44        | 51     | 72.13%  |
| NVMe | 17        | 20     | 27.87%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 38     | 77.78%  |
| 0.51-1.0   | 8         | 10     | 17.78%  |
| 1.01-2.0   | 2         | 3      | 4.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 30        | 37.5%   |
| 251-500    | 21        | 26.25%  |
| 1-20       | 15        | 18.75%  |
| 501-1000   | 6         | 7.5%    |
| 51-100     | 5         | 6.25%   |
| 21-50      | 2         | 2.5%    |
| 1001-2000  | 1         | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 67        | 80.72%  |
| 51-100  | 8         | 9.64%   |
| 21-50   | 5         | 6.02%   |
| 101-250 | 2         | 2.41%   |
| 251-500 | 1         | 1.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB       | 1         | 1      | 14.29%  |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1      | 14.29%  |
| Kingston SNS4151S316G 16GB         | 1         | 1      | 14.29%  |
| Intel SSDSC2BF180A4L 180GB         | 1         | 1      | 14.29%  |
| Hitachi HTS542525K9A300 250GB      | 1         | 1      | 14.29%  |
| HGST HTS725050A7E630 500GB         | 1         | 1      | 14.29%  |
| Apple SSD SM256E 256GB             | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 1         | 1      | 14.29%  |
| Seagate  | 1         | 1      | 14.29%  |
| Kingston | 1         | 1      | 14.29%  |
| Intel    | 1         | 1      | 14.29%  |
| Hitachi  | 1         | 1      | 14.29%  |
| HGST     | 1         | 1      | 14.29%  |
| Apple    | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 4         | 4      | 57.14%  |
| HDD  | 3         | 3      | 42.86%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 51        | 60     | 83.61%  |
| Malfunc  | 7         | 7      | 11.48%  |
| Detected | 3         | 4      | 4.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 45        | 51.14%  |
| Samsung Electronics       | 10        | 11.36%  |
| Sandisk                   | 9         | 10.23%  |
| Toshiba                   | 6         | 6.82%   |
| AMD                       | 5         | 5.68%   |
| Transcend                 | 2         | 2.27%   |
| SK hynix                  | 2         | 2.27%   |
| Phison Electronics        | 2         | 2.27%   |
| Nvidia                    | 2         | 2.27%   |
| Micron Technology         | 2         | 2.27%   |
| Silicon Motion            | 1         | 1.14%   |
| Micron/Crucial Technology | 1         | 1.14%   |
| Lenovo                    | 1         | 1.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 7         | 7.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 6         | 6.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 5         | 5.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 5         | 5.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 5         | 5.62%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 5         | 5.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 4         | 4.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 3         | 3.37%   |
| Transcend NVMe PCIe SSD 220S/240S/MTE710T                                     | 2         | 2.25%   |
| Toshiba XG6 NVMe SSD Controller                                               | 2         | 2.25%   |
| Toshiba XG4 NVMe SSD Controller                                               | 2         | 2.25%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 2         | 2.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2         | 2.25%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 2         | 2.25%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                   | 2         | 2.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 2         | 2.25%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 2         | 2.25%   |
| Toshiba XG5 NVMe SSD Controller                                               | 1         | 1.12%   |
| Toshiba XG3 NVMe SSD Controller                                               | 1         | 1.12%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                   | 1         | 1.12%   |
| SK hynix BC511 NVMe SSD                                                       | 1         | 1.12%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 1         | 1.12%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 1         | 1.12%   |
| Sandisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                   | 1         | 1.12%   |
| Sandisk WD PC SN5000S M.2 2242 NVMe SSD (DRAM-less)                           | 1         | 1.12%   |
| Sandisk WD Blue SN570 NVMe SSD 2TB                                            | 1         | 1.12%   |
| Sandisk WD Black SN850X NVMe SSD                                              | 1         | 1.12%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                         | 1         | 1.12%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                   | 1         | 1.12%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 1.12%   |
| Phison PS5027-E27T PCIe4 NVMe Controller (DRAM-less)                          | 1         | 1.12%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                           | 1         | 1.12%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                      | 1         | 1.12%   |
| Nvidia MCP79 AHCI Controller                                                  | 1         | 1.12%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 1         | 1.12%   |
| Lenovo LENSE30256GMSP34MEAT3TA                                                | 1         | 1.12%   |
| Intel SSD 660P Series                                                         | 1         | 1.12%   |
| Intel RST Volume Management Device Controller                                 | 1         | 1.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.12%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1         | 1.12%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 48        | 54.55%  |
| NVMe | 36        | 40.91%  |
| RAID | 3         | 3.41%   |
| IDE  | 1         | 1.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 70        | 87.5%   |
| AMD    | 10        | 12.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz     | 3         | 3.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz      | 3         | 3.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz      | 3         | 3.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz      | 2         | 2.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz      | 2         | 2.5%    |
| Intel Core i7-5600U CPU @ 2.60GHz      | 2         | 2.5%    |
| Intel Core i7-4510U CPU @ 2.00GHz      | 2         | 2.5%    |
| Intel Core i7-3667U CPU @ 2.00GHz      | 2         | 2.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz     | 2         | 2.5%    |
| Intel Core i5-7200U CPU @ 2.50GHz      | 2         | 2.5%    |
| Intel Core i5-5300U CPU @ 2.30GHz      | 2         | 2.5%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz   | 2         | 2.5%    |
| Intel 13th Gen Core i7-13650HX         | 2         | 2.5%    |
| Intel 12th Gen Core i5-1240P           | 2         | 2.5%    |
| AMD Ryzen Embedded V1500B              | 2         | 2.5%    |
| AMD Ryzen 5 5500U with Radeon Graphics | 2         | 2.5%    |
| Intel Xeon CPU E3-1220 V2 @ 3.10GH     | 1         | 1.25%   |
| Intel CPU Version                      | 1         | 1.25%   |
| Intel Core i7-8665U CPU @ 1.90GHz      | 1         | 1.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz      | 1         | 1.25%   |
| Intel Core i7-7500U CPU @ 2.70GHz      | 1         | 1.25%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz     | 1         | 1.25%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz     | 1         | 1.25%   |
| Intel Core i7-6600U CPU @ 2.60GHz      | 1         | 1.25%   |
| Intel Core i7-6500U CPU @ 2.50GHz      | 1         | 1.25%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz     | 1         | 1.25%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz     | 1         | 1.25%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 1         | 1.25%   |
| Intel Core i7-3537U CPU @ 2.00GHz      | 1         | 1.25%   |
| Intel Core i7-2670QM CPU @ 2.20GHz     | 1         | 1.25%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 1         | 1.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 1         | 1.25%   |
| Intel Core i5-7300U CPU @ 2.60GHz      | 1         | 1.25%   |
| Intel Core i5-6200U CPU @ 2.30GHz      | 1         | 1.25%   |
| Intel Core i5-4300U CPU @ 1.90GHz      | 1         | 1.25%   |
| Intel Core i5-4210Y CPU @ 1.50GHz      | 1         | 1.25%   |
| Intel Core i5-3380M CPU @ 2.90GHz      | 1         | 1.25%   |
| Intel Core i5-3210M CPU @ 2.50GHz      | 1         | 1.25%   |
| Intel Core i5-2520M CPU @ 2.50GH       | 1         | 1.25%   |
| Intel Core i5 CPU M 480 @ 2.67GH       | 1         | 1.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 27        | 33.75%  |
| Intel Core i5      | 20        | 25%     |
| Other              | 9         | 11.25%  |
| Intel Celeron      | 6         | 7.5%    |
| Intel Core 2 Duo   | 5         | 6.25%   |
| AMD Ryzen 5        | 3         | 3.75%   |
| Intel Core i3      | 2         | 2.5%    |
| AMD Ryzen Embedded | 2         | 2.5%    |
| AMD Ryzen 7        | 2         | 2.5%    |
| Intel Xeon         | 1         | 1.25%   |
| Intel Core Duo     | 1         | 1.25%   |
| AMD A8             | 1         | 1.25%   |
| AMD A6             | 1         | 1.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 37        | 46.25%  |
| 4       | 23        | 28.75%  |
| 6       | 5         | 6.25%   |
| Unknown | 5         | 6.25%   |
| 8       | 4         | 5%      |
| 12      | 2         | 2.5%    |
| 10      | 2         | 2.5%    |
| 16      | 1         | 1.25%   |
| 1       | 1         | 1.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 77        | 96.25%  |
| 2       | 2         | 2.5%    |
| Unknown | 1         | 1.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 59        | 73.75%  |
| 1       | 16        | 20%     |
| Unknown | 5         | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 15        | 18.75%  |
| Skylake     | 9         | 11.25%  |
| Unknown     | 9         | 11.25%  |
| IvyBridge   | 8         | 10%     |
| Haswell     | 8         | 10%     |
| SandyBridge | 5         | 6.25%   |
| Penryn      | 4         | 5%      |
| Broadwell   | 4         | 5%      |
| CometLake   | 3         | 3.75%   |
| Zen         | 2         | 2.5%    |
| TigerLake   | 2         | 2.5%    |
| Silvermont  | 2         | 2.5%    |
| Puma        | 2         | 2.5%    |
| Zen+        | 1         | 1.25%   |
| Zen 3       | 1         | 1.25%   |
| Westmere    | 1         | 1.25%   |
| P6          | 1         | 1.25%   |
| Excavator   | 1         | 1.25%   |
| Core        | 1         | 1.25%   |
| Bonnell     | 1         | 1.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Intel          | 60        | 63.83%  |
| Nvidia         | 19        | 20.21%  |
| AMD            | 14        | 14.89%  |
| Silicon Motion | 1         | 1.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 7         | 7.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 7.29%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 5         | 5.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 5.21%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 4         | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 4.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 3.13%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 3         | 3.13%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 3.13%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 2.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.08%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 2.08%   |
| AMD Opal PRO [Radeon R7 M260X]                                                           | 2         | 2.08%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 2.08%   |
| AMD Lucienne                                                                             | 2         | 2.08%   |
| Silicon Motion SM712 LynxEM+                                                             | 1         | 1.04%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 1.04%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 1.04%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 1.04%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 1.04%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.04%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.04%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.04%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 1.04%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.04%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 1.04%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 1.04%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.04%   |
| Nvidia G98M [GeForce G 105M]                                                             | 1         | 1.04%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.04%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.04%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 1         | 1.04%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                                          | 1         | 1.04%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 1         | 1.04%   |
| Intel Raptor Lake-S UHD Graphics                                                         | 1         | 1.04%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.04%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 42        | 52.5%   |
| Intel + Nvidia     | 11        | 13.75%  |
| 1 x Nvidia         | 8         | 10%     |
| 1 x AMD            | 8         | 10%     |
| Intel + AMD        | 5         | 6.25%   |
| Other              | 2         | 2.5%    |
| 2 x Intel          | 2         | 2.5%    |
| 2 x AMD            | 1         | 1.25%   |
| 1 x Silicon Motion | 1         | 1.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 70        | 86.42%  |
| Proprietary | 7         | 8.64%   |
| Unknown     | 4         | 4.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 86.25%  |
| 0.01-0.5   | 3         | 3.75%   |
| 3.01-4.0   | 2         | 2.5%    |
| 1.01-2.0   | 2         | 2.5%    |
| 0.51-1.0   | 2         | 2.5%    |
| 7.01-8.0   | 1         | 1.25%   |
| 5.01-6.0   | 1         | 1.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 10        | 22.73%  |
| BOE                  | 8         | 18.18%  |
| LG Display           | 6         | 13.64%  |
| Sharp                | 3         | 6.82%   |
| Chimei Innolux       | 3         | 6.82%   |
| Samsung Electronics  | 2         | 4.55%   |
| Panasonic            | 2         | 4.55%   |
| Dell                 | 2         | 4.55%   |
| LG Philips           | 1         | 2.27%   |
| Lenovo               | 1         | 2.27%   |
| Goldstar             | 1         | 2.27%   |
| CTO                  | 1         | 2.27%   |
| CSW                  | 1         | 2.27%   |
| CSO                  | 1         | 2.27%   |
| Ancor Communications | 1         | 2.27%   |
| Unknown              | 1         | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch              | 2         | 4.44%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch       | 2         | 4.44%   |
| Sharp LQ133T1JX03 SHP140F 2560x1440 290x170mm 13.2-inch              | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SDC4445 1366x768 340x190mm 15.3-inch | 1         | 2.22%   |
| Panasonic TV MEIA0A4 1920x1080 698x392mm 31.5-inch                   | 1         | 2.22%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 340x190mm 15.3-inch          | 1         | 2.22%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 330x210mm 15.4-inch        | 1         | 2.22%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 1         | 2.22%   |
| LG Display LCD Monitor LGD04A9 1920x1080 310x170mm 13.9-inch         | 1         | 2.22%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x170mm 13.9-inch         | 1         | 2.22%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch         | 1         | 2.22%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch          | 1         | 2.22%   |
| LG Display LCD Monitor LGD01DD 1600x900 380x210mm 17.1-inch          | 1         | 2.22%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch              | 1         | 2.22%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 1         | 2.22%   |
| Dell P2415Q DELA0C0 3840x2160 530x300mm 24.0-inch                    | 1         | 2.22%   |
| Dell P2415Q DELA0BE 3840x2160 530x300mm 24.0-inch                    | 1         | 2.22%   |
| Dell P2314H DEL4098 1920x1080 510x290mm 23.1-inch                    | 1         | 2.22%   |
| CTO LCD Monitor CTO1412 1920x1200 300x190mm 14.0-inch                | 1         | 2.22%   |
| CSW LCD Monitor CSW150F 1920x1080 340x190mm 15.3-inch                | 1         | 2.22%   |
| CSO LCD Monitor CSO1630 1920x1200 350x220mm 16.3-inch                | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 340x190mm 15.3-inch     | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 1         | 2.22%   |
| BOE LCD Monitor BOE0CCD 1920x1200 340x220mm 15.9-inch                | 1         | 2.22%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                | 1         | 2.22%   |
| BOE LCD Monitor BOE07C9 1920x1080 300x170mm 13.6-inch                | 1         | 2.22%   |
| BOE LCD Monitor BOE0747 1920x1080 350x200mm 15.9-inch                | 1         | 2.22%   |
| BOE LCD Monitor BOE06FF 1920x1080 340x190mm 15.3-inch                | 1         | 2.22%   |
| BOE LCD Monitor BOE06B3 1366x768 310x170mm 13.9-inch                 | 1         | 2.22%   |
| BOE LCD Monitor BOE0630 1920x1080 340x190mm 15.3-inch                | 1         | 2.22%   |
| BOE LCD Monitor BOE05F0 1366x768 310x170mm 13.9-inch                 | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 340x190mm 15.3-inch       | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 260x140mm 11.6-inch       | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch        | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 340x190mm 15.3-inch        | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch        | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 2.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 20        | 48.78%  |
| 1366x768 (WXGA)   | 10        | 24.39%  |
| 1920x1200 (WUXGA) | 3         | 7.32%   |
| 3840x2160 (4K)    | 2         | 4.88%   |
| 2560x1440 (QHD)   | 2         | 4.88%   |
| 2560x1600         | 1         | 2.44%   |
| 1600x900 (HD+)    | 1         | 2.44%   |
| 1280x800 (WXGA)   | 1         | 2.44%   |
| 1280x720 (HD)     | 1         | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 15        | 34.09%  |
| 13      | 12        | 27.27%  |
| 11      | 4         | 9.09%   |
| 24      | 2         | 4.55%   |
| 17      | 2         | 4.55%   |
| 12      | 2         | 4.55%   |
| 31      | 1         | 2.27%   |
| 23      | 1         | 2.27%   |
| 21      | 1         | 2.27%   |
| 16      | 1         | 2.27%   |
| 14      | 1         | 2.27%   |
| 10      | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 54.55%  |
| 201-300     | 12        | 27.27%  |
| 501-600     | 3         | 6.82%   |
| 351-400     | 2         | 4.55%   |
| 601-700     | 1         | 2.27%   |
| 401-500     | 1         | 2.27%   |
| Unknown     | 1         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 35        | 87.5%   |
| 16/10   | 3         | 7.5%    |
| 3/2     | 1         | 2.5%    |
| Unknown | 1         | 2.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 11        | 25%     |
| 81-90          | 9         | 20.45%  |
| 71-80          | 4         | 9.09%   |
| 51-60          | 4         | 9.09%   |
| 201-250        | 4         | 9.09%   |
| 101-110        | 3         | 6.82%   |
| 61-70          | 2         | 4.55%   |
| 121-130        | 2         | 4.55%   |
| 111-120        | 2         | 4.55%   |
| 351-500        | 1         | 2.27%   |
| 41-50          | 1         | 2.27%   |
| Unknown        | 1         | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 22        | 50%     |
| 161-240       | 8         | 18.18%  |
| 101-120       | 7         | 15.91%  |
| 51-100        | 5         | 11.36%  |
| More than 240 | 1         | 2.27%   |
| Unknown       | 1         | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 42        | 51.85%  |
| 0     | 35        | 43.21%  |
| 2     | 3         | 3.7%    |
| 3     | 1         | 1.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 60        | 48.78%  |
| Realtek Semiconductor             | 28        | 22.76%  |
| Qualcomm Atheros                  | 9         | 7.32%   |
| Broadcom                          | 7         | 5.69%   |
| MediaTek                          | 3         | 2.44%   |
| TP-Link                           | 2         | 1.63%   |
| Sierra Wireless                   | 2         | 1.63%   |
| Lenovo                            | 2         | 1.63%   |
| Ericsson Business Mobile Networks | 2         | 1.63%   |
| AMD                               | 2         | 1.63%   |
| Samsung Electronics               | 1         | 0.81%   |
| Nvidia                            | 1         | 0.81%   |
| NetGear                           | 1         | 0.81%   |
| Microsoft                         | 1         | 0.81%   |
| Marvell Technology Group          | 1         | 0.81%   |
| Google                            | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 17        | 10.56%  |
| Intel Wireless 8260                                                    | 10        | 6.21%   |
| Intel Wireless 7265                                                    | 7         | 4.35%   |
| Intel Wireless 8265 / 8275                                             | 5         | 3.11%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 3.11%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 2.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 2.48%   |
| Realtek USB 2.5GbE Controller                                          | 3         | 1.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 1.86%   |
| Intel Wireless 7260                                                    | 3         | 1.86%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 3         | 1.86%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 1.86%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 3         | 1.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 1.86%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 1.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2         | 1.24%   |
| Sierra Wireless EM7455                                                 | 2         | 1.24%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 2         | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 1.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 1.24%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 1.24%   |
| Lenovo USB-C Dock Ethernet                                             | 2         | 1.24%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 1.24%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.24%   |
| Intel Ethernet Controller I226-V                                       | 2         | 1.24%   |
| Intel Ethernet Connection I219-V                                       | 2         | 1.24%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.24%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 1.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.24%   |
| Intel 700 Series Chipset CNVi WiFi                                     | 2         | 1.24%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module     | 2         | 1.24%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 2         | 1.24%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 2         | 1.24%   |
| AMD XGMAC 10GbE Controller                                             | 2         | 1.24%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1         | 0.62%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 0.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.62%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 53        | 66.25%  |
| Qualcomm Atheros      | 8         | 10%     |
| Broadcom              | 6         | 7.5%    |
| Realtek Semiconductor | 5         | 6.25%   |
| MediaTek              | 3         | 3.75%   |
| TP-Link               | 2         | 2.5%    |
| Sierra Wireless       | 2         | 2.5%    |
| NetGear               | 1         | 1.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                  | 10        | 12.2%   |
| Intel Wireless 7265                                                  | 7         | 8.54%   |
| Intel Wireless 8265 / 8275                                           | 5         | 6.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 4         | 4.88%   |
| Intel Wireless 7260                                                  | 3         | 3.66%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection              | 3         | 3.66%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 3.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 3         | 3.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2         | 2.44%   |
| Sierra Wireless EM7455                                               | 2         | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 2.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 2.44%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 2         | 2.44%   |
| Intel Wi-Fi 6 AX201                                                  | 2         | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 2.44%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 2         | 2.44%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 2         | 2.44%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 2         | 2.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.22%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 1         | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1         | 1.22%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 1.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 1.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1         | 1.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1         | 1.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 1         | 1.22%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                      | 1         | 1.22%   |
| MediaTek MT7925 (RZ717) Wi-Fi 7 160MHz                               | 1         | 1.22%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 1         | 1.22%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 1         | 1.22%   |
| Intel Wireless 3165                                                  | 1         | 1.22%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 1         | 1.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 1         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1         | 1.22%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 1         | 1.22%   |
| Intel Centrino Advanced-N 6235                                       | 1         | 1.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 1         | 1.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 32        | 44.44%  |
| Realtek Semiconductor    | 26        | 36.11%  |
| Qualcomm Atheros         | 3         | 4.17%   |
| Broadcom                 | 3         | 4.17%   |
| Lenovo                   | 2         | 2.78%   |
| AMD                      | 2         | 2.78%   |
| Samsung Electronics      | 1         | 1.39%   |
| Nvidia                   | 1         | 1.39%   |
| Microsoft                | 1         | 1.39%   |
| Marvell Technology Group | 1         | 1.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 17        | 22.37%  |
| Intel Ethernet Connection I219-LM                                      | 5         | 6.58%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 5.26%   |
| Realtek USB 2.5GbE Controller                                          | 3         | 3.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 3.95%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 3.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 3.95%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 3.95%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 2         | 2.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 2.63%   |
| Lenovo USB-C Dock Ethernet                                             | 2         | 2.63%   |
| Intel Ethernet Controller I226-V                                       | 2         | 2.63%   |
| Intel Ethernet Connection I219-V                                       | 2         | 2.63%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 2.63%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 2.63%   |
| AMD XGMAC 10GbE Controller                                             | 2         | 2.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 1.32%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.32%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.32%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.32%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                     | 1         | 1.32%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 1.32%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.32%   |
| Intel Ethernet Connection I218-V                                       | 1         | 1.32%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.32%   |
| Intel Ethernet Connection (2) I219-V                                   | 1         | 1.32%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.32%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 1.32%   |
| Intel Ethernet 10G 2P X520 Adapter                                     | 1         | 1.32%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 1.32%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1         | 1.32%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 1.32%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 1.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 51.75%  |
| Ethernet | 66        | 46.15%  |
| Modem    | 2         | 1.4%    |
| Unknown  | 1         | 0.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 50.55%  |
| WiFi     | 44        | 48.35%  |
| Modem    | 1         | 1.1%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 54        | 67.5%   |
| 1     | 19        | 23.75%  |
| 3     | 3         | 3.75%   |
| 5     | 2         | 2.5%    |
| 6     | 1         | 1.25%   |
| 4     | 1         | 1.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 73        | 90.12%  |
| Yes  | 8         | 9.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 65.52%  |
| Qualcomm Atheros Communications | 4         | 6.9%    |
| Apple                           | 4         | 6.9%    |
| Broadcom                        | 3         | 5.17%   |
| Realtek Semiconductor           | 2         | 3.45%   |
| Hewlett-Packard                 | 2         | 3.45%   |
| Foxconn / Hon Hai               | 2         | 3.45%   |
| Toshiba                         | 1         | 1.72%   |
| MediaTek                        | 1         | 1.72%   |
| IMC Networks                    | 1         | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 21        | 36.21%  |
| Intel AX201 Bluetooth                                  | 7         | 12.07%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 6         | 10.34%  |
| Apple Bluetooth Host Controller                        | 3         | 5.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                 | 2         | 3.45%   |
| Intel AX210 Bluetooth                                  | 2         | 3.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]          | 2         | 3.45%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip        | 1         | 1.72%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                | 1         | 1.72%   |
| Realtek  Bluetooth 4.2 Adapter                         | 1         | 1.72%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                 | 1         | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                  | 1         | 1.72%   |
| MediaTek Wireless_Device                               | 1         | 1.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 1         | 1.72%   |
| Intel AX211 Bluetooth                                  | 1         | 1.72%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 1.72%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter           | 1         | 1.72%   |
| Foxconn / Hon Hai Bluetooth USB Module                 | 1         | 1.72%   |
| Broadcom Bluetooth 4.0                                 | 1         | 1.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]             | 1         | 1.72%   |
| Broadcom BCM2045B (BDC-2.1)                            | 1         | 1.72%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                   | 1         | 1.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 66        | 70.97%  |
| Nvidia                                       | 12        | 12.9%   |
| AMD                                          | 11        | 11.83%  |
| Lenovo                                       | 2         | 2.15%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.08%   |
| Logitech                                     | 1         | 1.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 12.73%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 6.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 5.45%   |
| AMD Ryzen HD Audio Controller                                                                     | 6         | 5.45%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 4.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 3.64%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 3.64%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 2.73%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.73%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 2.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.73%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 3         | 2.73%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.82%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 2         | 1.82%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 2         | 1.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.82%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 2         | 1.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.82%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.82%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.82%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 0.91%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.91%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.91%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.91%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.91%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.91%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.91%   |
| Logitech Headset H340                                                                             | 1         | 0.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.91%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 0.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.91%   |
| AMD Radeon High Definition Audio Controller                                                       | 1         | 0.91%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 33        | 39.29%  |
| SK hynix            | 14        | 16.67%  |
| Micron Technology   | 11        | 13.1%   |
| Crucial             | 6         | 7.14%   |
| Kingston            | 5         | 5.95%   |
| Unknown             | 3         | 3.57%   |
| Transcend           | 3         | 3.57%   |
| Team                | 2         | 2.38%   |
| Ramaxel Technology  | 2         | 2.38%   |
| Unifosa             | 1         | 1.19%   |
| Silicon Power       | 1         | 1.19%   |
| Corsair             | 1         | 1.19%   |
| ASint Technology    | 1         | 1.19%   |
| Unknown             | 1         | 1.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 4         | 4.49%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 2         | 2.25%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 2         | 2.25%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 2.25%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 2.25%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.25%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 2         | 2.25%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.12%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 1.12%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 1.12%   |
| Unifosa RAM HU6E4403EP0200 4GB SODIMM DDR3 1333MT/s              | 1         | 1.12%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                | 1         | 1.12%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 1.12%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 1.12%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 1.12%   |
| SK hynix RAM Module 2GB DDR3 1600MT/s                            | 1         | 1.12%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.12%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s             | 1         | 1.12%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.12%   |
| SK hynix RAM HMCG66AEBSA095N 8GB SODIMM DDR5 4800MT/s            | 1         | 1.12%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.12%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.12%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.12%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s           | 1         | 1.12%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s             | 1         | 1.12%   |
| Silicon Power RAM DBST4GN568S 4GB SODIMM DDR3 1333MT/s           | 1         | 1.12%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.12%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.12%   |
| Samsung RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.12%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                      | 1         | 1.12%   |
| Samsung RAM Module 2GB SODIMM 667MT/s                            | 1         | 1.12%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 1         | 1.12%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.12%   |
| Samsung RAM M471B5174BM0-YH9 4GB Chip DDR3 1333MT/s              | 1         | 1.12%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.12%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.12%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.12%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1333MT/s                   | 1         | 1.12%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.12%   |
| Samsung RAM M471B1G73CB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.12%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 27        | 37.5%   |
| DDR4    | 25        | 34.72%  |
| LPDDR3  | 9         | 12.5%   |
| LPDDR4  | 3         | 4.17%   |
| DDR5    | 3         | 4.17%   |
| DDR2    | 3         | 4.17%   |
| LPDDR5  | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 57        | 75%     |
| Row Of Chips | 10        | 13.16%  |
| Chip         | 6         | 7.89%   |
| Unknown      | 3         | 3.95%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 30        | 38.46%  |
| 4096  | 24        | 30.77%  |
| 16384 | 10        | 12.82%  |
| 2048  | 10        | 12.82%  |
| 32768 | 3         | 3.85%   |
| 12288 | 1         | 1.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 18        | 23.38%  |
| 2667  | 9         | 11.69%  |
| 1867  | 9         | 11.69%  |
| 3200  | 8         | 10.39%  |
| 2400  | 6         | 7.79%   |
| 2133  | 6         | 7.79%   |
| 1333  | 6         | 7.79%   |
| 800   | 3         | 3.9%    |
| 4800  | 2         | 2.6%    |
| 4267  | 2         | 2.6%    |
| 1067  | 2         | 2.6%    |
| 667   | 2         | 2.6%    |
| 6400  | 1         | 1.3%    |
| 5600  | 1         | 1.3%    |
| 3733  | 1         | 1.3%    |
| 1334  | 1         | 1.3%    |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 19        | 36.54%  |
| Bison Electronics                      | 8         | 15.38%  |
| IMC Networks                           | 7         | 13.46%  |
| Microdia                               | 4         | 7.69%   |
| Sunplus Innovation Technology          | 3         | 5.77%   |
| Realtek Semiconductor                  | 3         | 5.77%   |
| Suyin                                  | 2         | 3.85%   |
| Z-Star Microelectronics                | 1         | 1.92%   |
| Syntek                                 | 1         | 1.92%   |
| Quanta                                 | 1         | 1.92%   |
| Luxvisions Innotech Limited            | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.92%   |
| Apple                                  | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 11        | 20.75%  |
| Bison Integrated Camera                                      | 4         | 7.55%   |
| Microdia Integrated_Webcam_HD                                | 3         | 5.66%   |
| IMC Networks Integrated Webcam                               | 2         | 3.77%   |
| IMC Networks EasyCamera                                      | 2         | 3.77%   |
| Chicony Integrated Camera (1280x720@30)                      | 2         | 3.77%   |
| Z-Star WebCam SC-03FFL11739P                                 | 1         | 1.89%   |
| Syntek Integrated Camera                                     | 1         | 1.89%   |
| Suyin Lenovo Integrated Webcam                               | 1         | 1.89%   |
| Suyin HP webcam [dv6-1190en]                                 | 1         | 1.89%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 1.89%   |
| Sunplus Laptop Integrated Webcam HD                          | 1         | 1.89%   |
| Sunplus HD WebCam                                            | 1         | 1.89%   |
| Realtek Laptop Camera                                        | 1         | 1.89%   |
| Realtek Integrated_Webcam_HD                                 | 1         | 1.89%   |
| Realtek Integrated Camera                                    | 1         | 1.89%   |
| Quanta HP Universal Camera                                   | 1         | 1.89%   |
| Microdia Integrated Webcam HD                                | 1         | 1.89%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera          | 1         | 1.89%   |
| IMC Networks TOSHIBA Web Camera - HD                         | 1         | 1.89%   |
| IMC Networks SunplusIT Integrated Camera                     | 1         | 1.89%   |
| IMC Networks Integrated Camera                               | 1         | 1.89%   |
| Chicony USB2.0 VGA UVC WebCam                                | 1         | 1.89%   |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 1.89%   |
| Chicony TOSHIBA Web Camera - 3M                              | 1         | 1.89%   |
| Chicony ThinkPad T490 Webcam                                 | 1         | 1.89%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 1.89%   |
| Chicony Lenovo Integrated Camera                             | 1         | 1.89%   |
| Chicony EasyCamera                                           | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 1.89%   |
| Bison Web Camera - FHD                                       | 1         | 1.89%   |
| Bison SunplusIT Integrated Camera                            | 1         | 1.89%   |
| Bison Lenovo Integrated Webcam                               | 1         | 1.89%   |
| Bison Lenovo EasyCamera                                      | 1         | 1.89%   |
| Apple FaceTime HD Camera (Built-in)                          | 1         | 1.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 65%     |
| Synaptics                  | 3         | 15%     |
| Elan Microelectronics      | 2         | 10%     |
| Upek                       | 1         | 5%      |
| Shenzhen Goodix Technology | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 5         | 25%     |
| Validity Sensors Synaptics WBDI                        | 4         | 20%     |
| Validity Sensors VFS7552 Touch Fingerprint Sensor      | 2         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 10%     |
| Elan Fingerprint Sensor                                | 2         | 10%     |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 5%      |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5%      |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 5%      |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 5%      |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 28        | 33.33%  |
| 3     | 24        | 28.57%  |
| 2     | 22        | 26.19%  |
| 0     | 7         | 8.33%   |
| 6     | 1         | 1.19%   |
| 5     | 1         | 1.19%   |
| 4     | 1         | 1.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 59        | 41.84%  |
| Bluetooth                | 27        | 19.15%  |
| Fingerprint reader       | 17        | 12.06%  |
| Card reader              | 13        | 9.22%   |
| Net/wireless             | 12        | 8.51%   |
| Net/ethernet             | 3         | 2.13%   |
| Graphics card            | 3         | 2.13%   |
| Firewire controller      | 3         | 2.13%   |
| Sound                    | 2         | 1.42%   |
| Storage                  | 1         | 0.71%   |
| Network                  | 1         | 0.71%   |

