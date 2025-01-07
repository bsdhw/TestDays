BSD in Russia - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Russia.

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

Total: 763

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | PRIME B550-PLUS             | [6a1b59c063](https://bsd-hardware.info/?probe=6a1b59c063) | Jan 06, 2025 |
| ASUSTek       | B85M-E                      | [aef38fc437](https://bsd-hardware.info/?probe=aef38fc437) | Jan 05, 2025 |
| Shenzhen s... | miniPC                      | [974d78e0bf](https://bsd-hardware.info/?probe=974d78e0bf) | Dec 31, 2024 |
| Intel         | D2500HN                     | [a316391d86](https://bsd-hardware.info/?probe=a316391d86) | Dec 27, 2024 |
| Intel         | HURONRIVER                  | [dda4ccd2af](https://bsd-hardware.info/?probe=dda4ccd2af) | Dec 26, 2024 |
| AZW           | U59                         | [17a9a9d767](https://bsd-hardware.info/?probe=17a9a9d767) | Dec 25, 2024 |
| Techvision    | TVI7309X B0                 | [c16b1e23d4](https://bsd-hardware.info/?probe=c16b1e23d4) | Dec 21, 2024 |
| MSI           | GF615M-P33 V2               | [79f42224b7](https://bsd-hardware.info/?probe=79f42224b7) | Dec 17, 2024 |
| Gigabyte      | G41M-Combo                  | [d2d73e5ab9](https://bsd-hardware.info/?probe=d2d73e5ab9) | Dec 16, 2024 |
| Techvision    | TVI7309X B0                 | [e9ef186dcc](https://bsd-hardware.info/?probe=e9ef186dcc) | Dec 16, 2024 |
| Gigabyte      | Z690 AORUS ULTRA            | [3ec2b38bad](https://bsd-hardware.info/?probe=3ec2b38bad) | Dec 07, 2024 |
| Unknown       | Unknown                     | [3ad310c1ca](https://bsd-hardware.info/?probe=3ad310c1ca) | Dec 06, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [d024fa4f7a](https://bsd-hardware.info/?probe=d024fa4f7a) | Dec 06, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [ca1c97cf99](https://bsd-hardware.info/?probe=ca1c97cf99) | Dec 05, 2024 |
| Gigabyte      | H81M-S2PV                   | [63de24e596](https://bsd-hardware.info/?probe=63de24e596) | Dec 05, 2024 |
| ASUSTek       | PRIME H510M-R               | [772e88509f](https://bsd-hardware.info/?probe=772e88509f) | Dec 04, 2024 |
| Unknown       | QGLK03                      | [80b9c73d39](https://bsd-hardware.info/?probe=80b9c73d39) | Dec 01, 2024 |
| Unknown       | Unknown                     | [81d5169045](https://bsd-hardware.info/?probe=81d5169045) | Nov 27, 2024 |
| Gigabyte      | C1037UN-EU                  | [5efd7ff2d7](https://bsd-hardware.info/?probe=5efd7ff2d7) | Nov 26, 2024 |
| ASRock        | G41C-GS                     | [6330b64304](https://bsd-hardware.info/?probe=6330b64304) | Nov 23, 2024 |
| ASUSTek       | PRIME N100I-D D4            | [e634c55da0](https://bsd-hardware.info/?probe=e634c55da0) | Nov 22, 2024 |
| MSI           | PRO H610M-B DDR4            | [ed161aa339](https://bsd-hardware.info/?probe=ed161aa339) | Nov 21, 2024 |
| Unknown       | Unknown                     | [9cb678b64b](https://bsd-hardware.info/?probe=9cb678b64b) | Nov 19, 2024 |
| Gigabyte      | H61M-DS2                    | [b475794daf](https://bsd-hardware.info/?probe=b475794daf) | Nov 16, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [b62c2f6af1](https://bsd-hardware.info/?probe=b62c2f6af1) | Nov 09, 2024 |
| Gigabyte      | B560M DS3H V2               | [0c6f84aca8](https://bsd-hardware.info/?probe=0c6f84aca8) | Nov 09, 2024 |
| RDW Comput... | Kama-10                     | [0886b2b851](https://bsd-hardware.info/?probe=0886b2b851) | Nov 07, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [3450ab98b4](https://bsd-hardware.info/?probe=3450ab98b4) | Nov 07, 2024 |
| Unknown       | Unknown                     | [85bc2300d4](https://bsd-hardware.info/?probe=85bc2300d4) | Nov 04, 2024 |
| Unknown       | Q-790                       | [d7a5da3c3d](https://bsd-hardware.info/?probe=d7a5da3c3d) | Nov 02, 2024 |
| Gigabyte      | B450M S2H V2                | [1dd8ec6cbc](https://bsd-hardware.info/?probe=1dd8ec6cbc) | Oct 27, 2024 |
| Gigabyte      | B560M DS3H V2               | [12a26b4ff0](https://bsd-hardware.info/?probe=12a26b4ff0) | Oct 24, 2024 |
| Lenovo        | Bantry CRB NOK              | [aa498bf596](https://bsd-hardware.info/?probe=aa498bf596) | Oct 21, 2024 |
| Lenovo        | Bantry CRB NOK              | [33d4eb027a](https://bsd-hardware.info/?probe=33d4eb027a) | Oct 20, 2024 |
| Radxa         | rock-pi-e_rk3328            | [0447de6ec9](https://bsd-hardware.info/?probe=0447de6ec9) | Oct 19, 2024 |
| AZW           | U59                         | [576db5afb7](https://bsd-hardware.info/?probe=576db5afb7) | Oct 17, 2024 |
| Unknown       | Unknown                     | [ede814bb31](https://bsd-hardware.info/?probe=ede814bb31) | Oct 12, 2024 |
| Unknown       | adnbsc01                    | [3a0fab72d7](https://bsd-hardware.info/?probe=3a0fab72d7) | Sep 29, 2024 |
| Supermicro    | X7DA8                       | [92ebb2a336](https://bsd-hardware.info/?probe=92ebb2a336) | Sep 26, 2024 |
| Soyo          | SY-B250 BTC                 | [9c3afc54b3](https://bsd-hardware.info/?probe=9c3afc54b3) | Sep 23, 2024 |
| Unknown       | Unknown                     | [170341d296](https://bsd-hardware.info/?probe=170341d296) | Sep 19, 2024 |
| Unknown       | adnbsc01                    | [4f5340fc2c](https://bsd-hardware.info/?probe=4f5340fc2c) | Sep 18, 2024 |
| ASRock        | B550 Taichi                 | [4d8657f05e](https://bsd-hardware.info/?probe=4d8657f05e) | Sep 17, 2024 |
| ASUSTek       | PRIME H470M-PLUS            | [573ff12450](https://bsd-hardware.info/?probe=573ff12450) | Sep 13, 2024 |
| ASUSTek       | PRIME H470M-PLUS            | [3619cdfbec](https://bsd-hardware.info/?probe=3619cdfbec) | Sep 13, 2024 |
| Unknown       | Unknown                     | [92a6c31579](https://bsd-hardware.info/?probe=92a6c31579) | Sep 12, 2024 |
| Intel         | QHSW02                      | [365c9dcc32](https://bsd-hardware.info/?probe=365c9dcc32) | Sep 05, 2024 |
| Techvision    | TVI7309X B0                 | [0461c31cfa](https://bsd-hardware.info/?probe=0461c31cfa) | Sep 02, 2024 |
| Unknown       | QCML02                      | [d6029b3176](https://bsd-hardware.info/?probe=d6029b3176) | Sep 01, 2024 |
| Gigabyte      | N3150ND3V                   | [e215a00f4a](https://bsd-hardware.info/?probe=e215a00f4a) | Aug 30, 2024 |
| Unknown       | QCML02                      | [63f02a15c8](https://bsd-hardware.info/?probe=63f02a15c8) | Aug 29, 2024 |
| Lenovo        | Bantry CRB NOK              | [544a0f63e8](https://bsd-hardware.info/?probe=544a0f63e8) | Aug 27, 2024 |
| Lenovo        | Bantry CRB NOK              | [c2da5cc30e](https://bsd-hardware.info/?probe=c2da5cc30e) | Aug 27, 2024 |
| ASRock        | 970 Pro3 R2.0               | [2d6cb49646](https://bsd-hardware.info/?probe=2d6cb49646) | Aug 23, 2024 |
| Gigabyte      | B550M DS3H                  | [9b53982342](https://bsd-hardware.info/?probe=9b53982342) | Aug 22, 2024 |
| ASRock        | A320M-ITX                   | [73f83a9526](https://bsd-hardware.info/?probe=73f83a9526) | Aug 22, 2024 |
| Gigabyte      | B550M DS3H                  | [04c96f56e7](https://bsd-hardware.info/?probe=04c96f56e7) | Aug 22, 2024 |
| Gigabyte      | Z77N-WIFI                   | [ce8cad61be](https://bsd-hardware.info/?probe=ce8cad61be) | Aug 21, 2024 |
| Aquarius      | AQH610T SKU 00              | [62fbfbc201](https://bsd-hardware.info/?probe=62fbfbc201) | Aug 20, 2024 |
| Aquarius      | AQH610T SKU 00              | [0b32fb7cf5](https://bsd-hardware.info/?probe=0b32fb7cf5) | Aug 20, 2024 |
| Unknown       | Q-790                       | [91c1bb5ffd](https://bsd-hardware.info/?probe=91c1bb5ffd) | Aug 19, 2024 |
| ETegro Tec... | ETRS230G3                   | [123f8a464a](https://bsd-hardware.info/?probe=123f8a464a) | Aug 18, 2024 |
| ASUSTek       | P5G41T-M LX3                | [157b4f49fa](https://bsd-hardware.info/?probe=157b4f49fa) | Aug 15, 2024 |
| Unknown       | Unknown                     | [02869ec50d](https://bsd-hardware.info/?probe=02869ec50d) | Aug 11, 2024 |
| Unknown       | Q-790                       | [1ca0f16887](https://bsd-hardware.info/?probe=1ca0f16887) | Aug 07, 2024 |
| ASUSTek       | H110M-K                     | [b5c3543fa5](https://bsd-hardware.info/?probe=b5c3543fa5) | Jul 03, 2024 |
| Gigabyte      | B450M DS3H-CF               | [df8915643d](https://bsd-hardware.info/?probe=df8915643d) | Jul 02, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [d28277fb98](https://bsd-hardware.info/?probe=d28277fb98) | Jun 30, 2024 |
| Techvision    | TVI7309X B0                 | [ae3dc4ca3a](https://bsd-hardware.info/?probe=ae3dc4ca3a) | Jun 18, 2024 |
| Unknown       | Unknown                     | [dd5f673761](https://bsd-hardware.info/?probe=dd5f673761) | Jun 17, 2024 |
| Gigabyte      | Z370P D3-CF                 | [68dcdfd73f](https://bsd-hardware.info/?probe=68dcdfd73f) | Jun 10, 2024 |
| Unknown       | Unknown                     | [ba2d4e0728](https://bsd-hardware.info/?probe=ba2d4e0728) | Jun 04, 2024 |
| ASUSTek       | PRIME Z270-P                | [e9d5c616a0](https://bsd-hardware.info/?probe=e9d5c616a0) | May 31, 2024 |
| Unknown       | Unknown                     | [a4498a9e10](https://bsd-hardware.info/?probe=a4498a9e10) | May 24, 2024 |
| ASUSTek       | M2NPV-VM                    | [750fc5deea](https://bsd-hardware.info/?probe=750fc5deea) | May 24, 2024 |
| ASRock        | B550 Taichi                 | [524c9eda2c](https://bsd-hardware.info/?probe=524c9eda2c) | May 23, 2024 |
| ASRock        | B550 Taichi                 | [bf60c50ac6](https://bsd-hardware.info/?probe=bf60c50ac6) | May 23, 2024 |
| ASRock        | B550 Phantom Gaming 4       | [e9e0fec5c7](https://bsd-hardware.info/?probe=e9e0fec5c7) | May 21, 2024 |
| Foxconn       | 2ABF                        | [2ff8167020](https://bsd-hardware.info/?probe=2ff8167020) | May 20, 2024 |
| ASUSTek       | PRIME B250M-K               | [91bfac051b](https://bsd-hardware.info/?probe=91bfac051b) | May 20, 2024 |
| Soyo          | SY-B250 BTC                 | [4f299d9df8](https://bsd-hardware.info/?probe=4f299d9df8) | May 19, 2024 |
| ASUSTek       | P5QL PRO                    | [544633763b](https://bsd-hardware.info/?probe=544633763b) | May 18, 2024 |
| Unknown       | Unknown                     | [0fc50d9849](https://bsd-hardware.info/?probe=0fc50d9849) | May 14, 2024 |
| ASUSTek       | H110M-C                     | [fbfee7e505](https://bsd-hardware.info/?probe=fbfee7e505) | May 09, 2024 |
| ASUSTek       | TUF B360-PLUS GAMING        | [c809f82bd6](https://bsd-hardware.info/?probe=c809f82bd6) | May 09, 2024 |
| Unknown       | QDNV01                      | [8926d1c8f1](https://bsd-hardware.info/?probe=8926d1c8f1) | May 07, 2024 |
| Unknown       | Unknown                     | [6fad0f3ec7](https://bsd-hardware.info/?probe=6fad0f3ec7) | May 07, 2024 |
| AZW           | U59                         | [d900403d1a](https://bsd-hardware.info/?probe=d900403d1a) | May 06, 2024 |
| Gigabyte      | P67A-D3-B3                  | [2e71ecd984](https://bsd-hardware.info/?probe=2e71ecd984) | May 03, 2024 |
| Gigabyte      | Z370P D3-CF                 | [591ac5deba](https://bsd-hardware.info/?probe=591ac5deba) | May 03, 2024 |
| Dell          | 0CNWVK A00                  | [3c90466a0a](https://bsd-hardware.info/?probe=3c90466a0a) | May 02, 2024 |
| Gigabyte      | H61M-S2PV                   | [dec458ffdf](https://bsd-hardware.info/?probe=dec458ffdf) | May 02, 2024 |
| ASRock        | H610M-H2/M.2 D5             | [6ab73f5217](https://bsd-hardware.info/?probe=6ab73f5217) | Apr 28, 2024 |
| Unknown       | Q-790                       | [0c25ef8e72](https://bsd-hardware.info/?probe=0c25ef8e72) | Apr 25, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [ac75273460](https://bsd-hardware.info/?probe=ac75273460) | Apr 25, 2024 |
| AZW           | U59                         | [dcd692e9fc](https://bsd-hardware.info/?probe=dcd692e9fc) | Apr 25, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [0b322f0da8](https://bsd-hardware.info/?probe=0b322f0da8) | Apr 24, 2024 |
| ASUSTek       | P8H61-M LX                  | [eaee094e07](https://bsd-hardware.info/?probe=eaee094e07) | Apr 23, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | [ebaca4d176](https://bsd-hardware.info/?probe=ebaca4d176) | Apr 23, 2024 |
| Unknown       | Unknown                     | [08cdf907e4](https://bsd-hardware.info/?probe=08cdf907e4) | Apr 15, 2024 |
| ASRock        | H610M-H2/M.2 D5             | [0c2877ba10](https://bsd-hardware.info/?probe=0c2877ba10) | Apr 15, 2024 |
| Lenovo        | ThinkServer RS140           | [40aba08780](https://bsd-hardware.info/?probe=40aba08780) | Apr 14, 2024 |
| MAXSUN        | MS-Challenger B450M         | [e3d38c06bf](https://bsd-hardware.info/?probe=e3d38c06bf) | Apr 13, 2024 |
| Unknown       | Unknown                     | [34d08de74d](https://bsd-hardware.info/?probe=34d08de74d) | Apr 13, 2024 |
| MSI           | A520M-A PRO                 | [ad2494f0c0](https://bsd-hardware.info/?probe=ad2494f0c0) | Apr 11, 2024 |
| Lenovo        | ThinkServer RS140           | [77864ffe0d](https://bsd-hardware.info/?probe=77864ffe0d) | Apr 10, 2024 |
| MSI           | A520M-A PRO                 | [3fb8a577ad](https://bsd-hardware.info/?probe=3fb8a577ad) | Apr 10, 2024 |
| Unknown       | Unknown                     | [8756afef80](https://bsd-hardware.info/?probe=8756afef80) | Apr 10, 2024 |
| Gigabyte      | B360M D2V                   | [766a437527](https://bsd-hardware.info/?probe=766a437527) | Apr 07, 2024 |
| MSI           | PRO H610M-B DDR4            | [ddfaad8bed](https://bsd-hardware.info/?probe=ddfaad8bed) | Apr 07, 2024 |
| Gigabyte      | IMB1900N                    | [ed465b2fa0](https://bsd-hardware.info/?probe=ed465b2fa0) | Apr 06, 2024 |
| Unknown       | Unknown                     | [3bcc4b4df3](https://bsd-hardware.info/?probe=3bcc4b4df3) | Mar 31, 2024 |
| Unknown       | Unknown                     | [b1c47bed17](https://bsd-hardware.info/?probe=b1c47bed17) | Mar 27, 2024 |
| Unknown       | Unknown                     | [3e703f3ae6](https://bsd-hardware.info/?probe=3e703f3ae6) | Mar 27, 2024 |
| Gigabyte      | H81M-S2V                    | [f04f1f2154](https://bsd-hardware.info/?probe=f04f1f2154) | Mar 20, 2024 |
| Unknown       | Unknown                     | [9acbce6ef2](https://bsd-hardware.info/?probe=9acbce6ef2) | Mar 19, 2024 |
| Unknown       | Unknown                     | [2776bdbd27](https://bsd-hardware.info/?probe=2776bdbd27) | Mar 16, 2024 |
| Unknown       | Unknown                     | [820c6cbe0c](https://bsd-hardware.info/?probe=820c6cbe0c) | Mar 10, 2024 |
| Gigabyte      | P35-DS3                     | [d877d925e1](https://bsd-hardware.info/?probe=d877d925e1) | Feb 28, 2024 |
| TONK          | TN1900-C92                  | [395add95d4](https://bsd-hardware.info/?probe=395add95d4) | Feb 28, 2024 |
| Gigabyte      | P35-DS3                     | [dd8beb7c03](https://bsd-hardware.info/?probe=dd8beb7c03) | Feb 27, 2024 |
| ASUSTek       | M4A89TD PRO USB3            | [c0561cccdd](https://bsd-hardware.info/?probe=c0561cccdd) | Feb 26, 2024 |
| Gigabyte      | B85-HD3                     | [49b226f804](https://bsd-hardware.info/?probe=49b226f804) | Feb 23, 2024 |
| Unknown       | Unknown                     | [865bcfe2b7](https://bsd-hardware.info/?probe=865bcfe2b7) | Feb 22, 2024 |
| Gigabyte      | Z97X-UD3H-CF                | [054056b5fa](https://bsd-hardware.info/?probe=054056b5fa) | Feb 21, 2024 |
| PC Engines    | APU2                        | [66d6af8951](https://bsd-hardware.info/?probe=66d6af8951) | Feb 20, 2024 |
| Gigabyte      | Z97X-UD3H-CF                | [d84e00c746](https://bsd-hardware.info/?probe=d84e00c746) | Feb 19, 2024 |
| Techvision    | TVI7309X B0                 | [d4bdab4711](https://bsd-hardware.info/?probe=d4bdab4711) | Feb 10, 2024 |
| Gigabyte      | X299 AORUS Gaming-CF        | [47e91ddd92](https://bsd-hardware.info/?probe=47e91ddd92) | Feb 08, 2024 |
| Unknown       | Unknown                     | [05745ae76a](https://bsd-hardware.info/?probe=05745ae76a) | Feb 04, 2024 |
| Foxconn       | 2ABF                        | [d145d7a650](https://bsd-hardware.info/?probe=d145d7a650) | Feb 01, 2024 |
| ASUSTek       | P5E3 PRO                    | [354299e930](https://bsd-hardware.info/?probe=354299e930) | Feb 01, 2024 |
| Unknown       | Unknown                     | [80f34deedc](https://bsd-hardware.info/?probe=80f34deedc) | Jan 29, 2024 |
| Unknown       | Unknown                     | [18168c211d](https://bsd-hardware.info/?probe=18168c211d) | Jan 29, 2024 |
| Unknown       | Unknown                     | [754c764123](https://bsd-hardware.info/?probe=754c764123) | Jan 29, 2024 |
| ASRock        | H310CM-HDV/M.2              | [4f45811a17](https://bsd-hardware.info/?probe=4f45811a17) | Jan 27, 2024 |
| Unknown       | Q-790                       | [ec71672aed](https://bsd-hardware.info/?probe=ec71672aed) | Jan 25, 2024 |
| Gigabyte      | GA-970A-D3                  | [6aeb253575](https://bsd-hardware.info/?probe=6aeb253575) | Jan 25, 2024 |
| Unknown       | Q-790                       | [b94e9febe7](https://bsd-hardware.info/?probe=b94e9febe7) | Jan 24, 2024 |
| AMI           | PEISIA E3845 VER1.0         | [2448066e32](https://bsd-hardware.info/?probe=2448066e32) | Jan 23, 2024 |
| Gigabyte      | GA-970A-D3                  | [838906ef1b](https://bsd-hardware.info/?probe=838906ef1b) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [e2053919c4](https://bsd-hardware.info/?probe=e2053919c4) | Jan 15, 2024 |
| Intel         | D410PT AAE76528-404         | [87da69a1ef](https://bsd-hardware.info/?probe=87da69a1ef) | Jan 10, 2024 |
| HP            | 3641h                       | [90626880cf](https://bsd-hardware.info/?probe=90626880cf) | Jan 09, 2024 |
| Unknown       | Unknown                     | [5deb235717](https://bsd-hardware.info/?probe=5deb235717) | Jan 05, 2024 |
| Huanan        | X99-F8 V2.0                 | [04c19f755d](https://bsd-hardware.info/?probe=04c19f755d) | Jan 03, 2024 |
| Unknown       | Unknown                     | [d4bedea996](https://bsd-hardware.info/?probe=d4bedea996) | Dec 30, 2023 |
| Unknown       | Unknown                     | [19daaf5eee](https://bsd-hardware.info/?probe=19daaf5eee) | Dec 30, 2023 |
| Supermicro    | X10DRi-T                    | [0001356297](https://bsd-hardware.info/?probe=0001356297) | Dec 27, 2023 |
| Techvision    | TVI7309X B0                 | [1f28c229cb](https://bsd-hardware.info/?probe=1f28c229cb) | Dec 27, 2023 |
| Techvision    | TVI7309X B0                 | [d4f5a9c35a](https://bsd-hardware.info/?probe=d4f5a9c35a) | Dec 27, 2023 |
| Unknown       | Unknown                     | [84a9704b97](https://bsd-hardware.info/?probe=84a9704b97) | Dec 21, 2023 |
| ASUSTek       | P5B-VM                      | [00e7a346b2](https://bsd-hardware.info/?probe=00e7a346b2) | Dec 19, 2023 |
| Gigabyte      | H61M-S2PV                   | [88d2ae1175](https://bsd-hardware.info/?probe=88d2ae1175) | Dec 14, 2023 |
| Supermicro    | X7SBi                       | [a0124f00ba](https://bsd-hardware.info/?probe=a0124f00ba) | Dec 13, 2023 |
| Unknown       | Unknown                     | [123088175c](https://bsd-hardware.info/?probe=123088175c) | Dec 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [1034c9883a](https://bsd-hardware.info/?probe=1034c9883a) | Dec 06, 2023 |
| ASUSTek       | H81M-C                      | [177ffa702e](https://bsd-hardware.info/?probe=177ffa702e) | Dec 03, 2023 |
| Lenovo        | 3129 SDK0J40679 WIN 3273... | [da81c9605d](https://bsd-hardware.info/?probe=da81c9605d) | Dec 01, 2023 |
| Intel         | Geminilake                  | [0b0a4f8d68](https://bsd-hardware.info/?probe=0b0a4f8d68) | Nov 30, 2023 |
| MSI           | B350 PC MATE                | [87351f500b](https://bsd-hardware.info/?probe=87351f500b) | Nov 26, 2023 |
| MSI           | PRO H610M-B DDR4            | [c6ff092502](https://bsd-hardware.info/?probe=c6ff092502) | Nov 26, 2023 |
| Unknown       | Unknown                     | [ce88332d94](https://bsd-hardware.info/?probe=ce88332d94) | Nov 25, 2023 |
| Gigabyte      | Z68X-UD5-B3                 | [f8fcca51ca](https://bsd-hardware.info/?probe=f8fcca51ca) | Nov 19, 2023 |
| Unknown       | Unknown                     | [626ff9ba56](https://bsd-hardware.info/?probe=626ff9ba56) | Nov 13, 2023 |
| Unknown       | Unknown                     | [c535fae89f](https://bsd-hardware.info/?probe=c535fae89f) | Nov 10, 2023 |
| Techvision    | TVI7309X B0                 | [227e21dfdf](https://bsd-hardware.info/?probe=227e21dfdf) | Nov 09, 2023 |
| Techvision    | TVI7309X B0                 | [3dafd6bd42](https://bsd-hardware.info/?probe=3dafd6bd42) | Nov 07, 2023 |
| Techvision    | TVI7309X B0                 | [40dffa3e21](https://bsd-hardware.info/?probe=40dffa3e21) | Nov 06, 2023 |
| Gigabyte      | B450M H                     | [69b57fab79](https://bsd-hardware.info/?probe=69b57fab79) | Nov 02, 2023 |
| Unknown       | Unknown                     | [1a63df656e](https://bsd-hardware.info/?probe=1a63df656e) | Oct 31, 2023 |
| Intel         | DCP847SKE                   | [3b5b83d95f](https://bsd-hardware.info/?probe=3b5b83d95f) | Oct 30, 2023 |
| Intel         | DCP847SKE                   | [ba44d23972](https://bsd-hardware.info/?probe=ba44d23972) | Oct 29, 2023 |
| Unknown       | Unknown                     | [b688e6b635](https://bsd-hardware.info/?probe=b688e6b635) | Oct 28, 2023 |
| Sun           | SUNW,SPARC-Enterprise-T5... | [50457ff825](https://bsd-hardware.info/?probe=50457ff825) | Oct 27, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [3d6569cef5](https://bsd-hardware.info/?probe=3d6569cef5) | Oct 26, 2023 |
| Gigabyte      | H81M-S2PV                   | [310fcb9763](https://bsd-hardware.info/?probe=310fcb9763) | Oct 26, 2023 |
| Unknown       | Unknown                     | [6b3f2cf24c](https://bsd-hardware.info/?probe=6b3f2cf24c) | Oct 25, 2023 |
| Unknown       | Unknown                     | [db96ffb93a](https://bsd-hardware.info/?probe=db96ffb93a) | Oct 25, 2023 |
| Unknown       | Unknown                     | [06f91445cb](https://bsd-hardware.info/?probe=06f91445cb) | Oct 24, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [193c3e5732](https://bsd-hardware.info/?probe=193c3e5732) | Oct 22, 2023 |
| Unknown       | Unknown                     | [629eefe0c2](https://bsd-hardware.info/?probe=629eefe0c2) | Oct 21, 2023 |
| ASUSTek       | PRIME H470M-PLUS            | [88cdd6135f](https://bsd-hardware.info/?probe=88cdd6135f) | Oct 20, 2023 |
| MSI           | PRO H610M-B DDR4            | [1cc822b8c1](https://bsd-hardware.info/?probe=1cc822b8c1) | Oct 19, 2023 |
| Unknown       | Unknown                     | [0fd1a7196f](https://bsd-hardware.info/?probe=0fd1a7196f) | Oct 13, 2023 |
| Wistron       | ProLiant ML110 G6           | [d5676f7895](https://bsd-hardware.info/?probe=d5676f7895) | Oct 10, 2023 |
| TONK          | TN2800                      | [a47aba3406](https://bsd-hardware.info/?probe=a47aba3406) | Oct 10, 2023 |
| Gigabyte      | B550M DS3H                  | [66a1e081e6](https://bsd-hardware.info/?probe=66a1e081e6) | Oct 07, 2023 |
| Unknown       | Unknown                     | [9d236eb8bb](https://bsd-hardware.info/?probe=9d236eb8bb) | Oct 06, 2023 |
| Unknown       | Unknown                     | [9ad768a37a](https://bsd-hardware.info/?probe=9ad768a37a) | Oct 04, 2023 |
| Techvision    | TVI7309X B0                 | [9748abc90d](https://bsd-hardware.info/?probe=9748abc90d) | Oct 02, 2023 |
| TONK          | TN2800                      | [bce9c62915](https://bsd-hardware.info/?probe=bce9c62915) | Sep 29, 2023 |
| ASRock        | Z690 Phantom Gaming 4/D5    | [6eab8daef7](https://bsd-hardware.info/?probe=6eab8daef7) | Sep 21, 2023 |
| Apple         | MacPro4,1                   | [c368087050](https://bsd-hardware.info/?probe=c368087050) | Sep 20, 2023 |
| Huanan        | X99-F8D PLUS V1.3           | [53d31a28bf](https://bsd-hardware.info/?probe=53d31a28bf) | Sep 14, 2023 |
| Gigabyte      | GA-870A-UD3                 | [095b8aa8fb](https://bsd-hardware.info/?probe=095b8aa8fb) | Sep 11, 2023 |
| Lenovo        | 3140 NOK                    | [945ad170d7](https://bsd-hardware.info/?probe=945ad170d7) | Sep 10, 2023 |
| Lenovo        | 3140 NOK                    | [3f9dcefb8e](https://bsd-hardware.info/?probe=3f9dcefb8e) | Sep 10, 2023 |
| Unknown       | Unknown                     | [29578638c1](https://bsd-hardware.info/?probe=29578638c1) | Sep 08, 2023 |
| Intel         | HM570                       | [3112f263f5](https://bsd-hardware.info/?probe=3112f263f5) | Sep 07, 2023 |
| Intel         | HM570                       | [0e4bfa9794](https://bsd-hardware.info/?probe=0e4bfa9794) | Sep 07, 2023 |
| Gigabyte      | P35C-DS3R                   | [4424751223](https://bsd-hardware.info/?probe=4424751223) | Sep 04, 2023 |
| Shuttle       | DS20U                       | [d034a8e5b8](https://bsd-hardware.info/?probe=d034a8e5b8) | Sep 02, 2023 |
| VIA Techno... | VT8623-8235                 | [3274cd095e](https://bsd-hardware.info/?probe=3274cd095e) | Aug 31, 2023 |
| MSI           | MS-7125                     | [3dfb767d80](https://bsd-hardware.info/?probe=3dfb767d80) | Aug 30, 2023 |
| MSI           | H110M PRO-VD                | [dcbd4ebf8f](https://bsd-hardware.info/?probe=dcbd4ebf8f) | Aug 27, 2023 |
| Techvision    | TVI7309X B0                 | [ebb4e825a3](https://bsd-hardware.info/?probe=ebb4e825a3) | Aug 25, 2023 |
| ASUSTek       | P5M2-R                      | [73135bf26d](https://bsd-hardware.info/?probe=73135bf26d) | Aug 25, 2023 |
| MSI           | MAG B460M BAZOOKA           | [7cf9279c14](https://bsd-hardware.info/?probe=7cf9279c14) | Aug 22, 2023 |
| Gigabyte      | C1037UN-EU                  | [76945fc8cb](https://bsd-hardware.info/?probe=76945fc8cb) | Aug 22, 2023 |
| Unknown       | Unknown                     | [341152089f](https://bsd-hardware.info/?probe=341152089f) | Aug 21, 2023 |
| Unknown       | Unknown                     | [5ab27fdf53](https://bsd-hardware.info/?probe=5ab27fdf53) | Aug 21, 2023 |
| Shuttle       | DS20U                       | [5c511e0613](https://bsd-hardware.info/?probe=5c511e0613) | Aug 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [7e1d475356](https://bsd-hardware.info/?probe=7e1d475356) | Aug 18, 2023 |
| MSI           | A520M-A PRO                 | [cc946b2a89](https://bsd-hardware.info/?probe=cc946b2a89) | Aug 15, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [946e123320](https://bsd-hardware.info/?probe=946e123320) | Aug 13, 2023 |
| Dell          | 0CNWVK A00                  | [fdb03dc15f](https://bsd-hardware.info/?probe=fdb03dc15f) | Aug 09, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [4fc1fbaba1](https://bsd-hardware.info/?probe=4fc1fbaba1) | Aug 09, 2023 |
| MSI           | MS-7623                     | [189fb4d7cc](https://bsd-hardware.info/?probe=189fb4d7cc) | Aug 08, 2023 |
| ASRock        | B550 PG Velocita            | [3ff5fcfbc0](https://bsd-hardware.info/?probe=3ff5fcfbc0) | Aug 02, 2023 |
| MSI           | G41M-P33 Combo              | [d4a26f9214](https://bsd-hardware.info/?probe=d4a26f9214) | Jul 24, 2023 |
| Techvision    | TVI7309X B0                 | [65599626a9](https://bsd-hardware.info/?probe=65599626a9) | Jul 23, 2023 |
| Unknown       | Q-790                       | [49f9861c7f](https://bsd-hardware.info/?probe=49f9861c7f) | Jul 17, 2023 |
| Unknown       | Unknown                     | [4a82a6a375](https://bsd-hardware.info/?probe=4a82a6a375) | Jul 17, 2023 |
| ECS           | H61H2-M17                   | [aa4679bee7](https://bsd-hardware.info/?probe=aa4679bee7) | Jul 14, 2023 |
| Unknown       | Unknown                     | [a322b1ee22](https://bsd-hardware.info/?probe=a322b1ee22) | Jul 13, 2023 |
| Unknown       | Q-790                       | [cc02bb60de](https://bsd-hardware.info/?probe=cc02bb60de) | Jul 13, 2023 |
| Radxa         | rock-pi-n10a                | [a9767501e2](https://bsd-hardware.info/?probe=a9767501e2) | Jul 12, 2023 |
| ASRock        | P67 Pro3 SE                 | [a7284068da](https://bsd-hardware.info/?probe=a7284068da) | Jul 12, 2023 |
| ASRock        | H61M-GS                     | [502952e73f](https://bsd-hardware.info/?probe=502952e73f) | Jul 11, 2023 |
| Foxconn       | 2ABF                        | [26e209d8e1](https://bsd-hardware.info/?probe=26e209d8e1) | Jul 10, 2023 |
| ASRock        | Z690 PG Riptide             | [a9ab5114e1](https://bsd-hardware.info/?probe=a9ab5114e1) | Jul 10, 2023 |
| ASRock        | Z690 PG Riptide             | [813e46e924](https://bsd-hardware.info/?probe=813e46e924) | Jul 10, 2023 |
| Unknown       | Unknown                     | [c930867e8e](https://bsd-hardware.info/?probe=c930867e8e) | Jul 07, 2023 |
| ASRock        | Z690 PG Riptide             | [364cf5800b](https://bsd-hardware.info/?probe=364cf5800b) | Jul 06, 2023 |
| ASUSTek       | PRIME H510M-A               | [fd5fa70fb7](https://bsd-hardware.info/?probe=fd5fa70fb7) | Jul 03, 2023 |
| Gigabyte      | B360M D2V                   | [bf5f6fd6dd](https://bsd-hardware.info/?probe=bf5f6fd6dd) | Jun 30, 2023 |
| Unknown       | Unknown                     | [c07f4ffa1e](https://bsd-hardware.info/?probe=c07f4ffa1e) | Jun 29, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [2dfabb3a28](https://bsd-hardware.info/?probe=2dfabb3a28) | Jun 23, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [b63efe1bc2](https://bsd-hardware.info/?probe=b63efe1bc2) | Jun 23, 2023 |
| ASUSTek       | PRIME B350M-A               | [29545a1054](https://bsd-hardware.info/?probe=29545a1054) | Jun 21, 2023 |
| ASUSTek       | P7P55D LE                   | [ea97ade85d](https://bsd-hardware.info/?probe=ea97ade85d) | Jun 17, 2023 |
| Unknown       | Unknown                     | [f41e1f2b83](https://bsd-hardware.info/?probe=f41e1f2b83) | Jun 14, 2023 |
| Gigabyte      | B450M S2H                   | [2008116e96](https://bsd-hardware.info/?probe=2008116e96) | Jun 10, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [15a71633ec](https://bsd-hardware.info/?probe=15a71633ec) | Jun 08, 2023 |
| Gigabyte      | G41MT-S2                    | [355202536f](https://bsd-hardware.info/?probe=355202536f) | Jun 07, 2023 |
| Supermicro    | X10DRi-T                    | [c72eaa89d7](https://bsd-hardware.info/?probe=c72eaa89d7) | May 31, 2023 |
| Unknown       | Unknown                     | [086747eef4](https://bsd-hardware.info/?probe=086747eef4) | May 29, 2023 |
| ASRockRack    | E3C242D4U                   | [ae8287e8fd](https://bsd-hardware.info/?probe=ae8287e8fd) | May 29, 2023 |
| ASUSTek       | PRIME H510M-K               | [53a2d5356d](https://bsd-hardware.info/?probe=53a2d5356d) | May 26, 2023 |
| Gigabyte      | B360M D2V                   | [5960982eb3](https://bsd-hardware.info/?probe=5960982eb3) | May 25, 2023 |
| HP            | 0A60h                       | [98e9deff3d](https://bsd-hardware.info/?probe=98e9deff3d) | May 16, 2023 |
| Gigabyte      | Z490 VISION G               | [976e31bfbc](https://bsd-hardware.info/?probe=976e31bfbc) | May 16, 2023 |
| Gigabyte      | Z490 VISION G               | [8eeec83a4e](https://bsd-hardware.info/?probe=8eeec83a4e) | May 16, 2023 |
| Dell          | 0CNWVK A00                  | [0d1e1a3ca4](https://bsd-hardware.info/?probe=0d1e1a3ca4) | May 16, 2023 |
| Acer          | Revo RN86                   | [2e52c2b9b2](https://bsd-hardware.info/?probe=2e52c2b9b2) | May 13, 2023 |
| Unknown       | Unknown                     | [990b3eb510](https://bsd-hardware.info/?probe=990b3eb510) | May 12, 2023 |
| Gigabyte      | H77N-WIFI                   | [cf2014c973](https://bsd-hardware.info/?probe=cf2014c973) | May 04, 2023 |
| Supermicro    | X10DRi-T                    | [ba54a43cb4](https://bsd-hardware.info/?probe=ba54a43cb4) | May 03, 2023 |
| HP            | 82B4                        | [244817e203](https://bsd-hardware.info/?probe=244817e203) | May 02, 2023 |
| Unknown       | Unknown                     | [d6f92a5ecc](https://bsd-hardware.info/?probe=d6f92a5ecc) | Apr 28, 2023 |
| Unknown       | Unknown                     | [290fabd69d](https://bsd-hardware.info/?probe=290fabd69d) | Apr 26, 2023 |
| Gigabyte      | B360M D2V                   | [d4881f1fb6](https://bsd-hardware.info/?probe=d4881f1fb6) | Apr 25, 2023 |
| Dell          | 0CNWVK A00                  | [6642a4b35d](https://bsd-hardware.info/?probe=6642a4b35d) | Apr 18, 2023 |
| Gigabyte      | B360M D2V                   | [f73cb94828](https://bsd-hardware.info/?probe=f73cb94828) | Apr 17, 2023 |
| Unknown       | Unknown                     | [926ab149ae](https://bsd-hardware.info/?probe=926ab149ae) | Apr 14, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [882a817f46](https://bsd-hardware.info/?probe=882a817f46) | Apr 13, 2023 |
| Unknown       | Unknown                     | [c960f2dc8b](https://bsd-hardware.info/?probe=c960f2dc8b) | Apr 12, 2023 |
| ASUSTek       | P10S-I Series               | [5084c2b77f](https://bsd-hardware.info/?probe=5084c2b77f) | Apr 11, 2023 |
| PC Engines    | APU2                        | [cdcdfe6e0b](https://bsd-hardware.info/?probe=cdcdfe6e0b) | Apr 10, 2023 |
| Intel         | DG35EC AAE29266-205         | [821368d0f0](https://bsd-hardware.info/?probe=821368d0f0) | Apr 09, 2023 |
| HP            | 2820h                       | [e304f130aa](https://bsd-hardware.info/?probe=e304f130aa) | Apr 09, 2023 |
| HP            | 2820h                       | [ff9500303d](https://bsd-hardware.info/?probe=ff9500303d) | Apr 09, 2023 |
| Unknown       | Unknown                     | [f96c113329](https://bsd-hardware.info/?probe=f96c113329) | Apr 08, 2023 |
| Gigabyte      | B360M D2V                   | [6429eebbaa](https://bsd-hardware.info/?probe=6429eebbaa) | Apr 05, 2023 |
| Intel         | B75                         | [3a7eee851b](https://bsd-hardware.info/?probe=3a7eee851b) | Apr 03, 2023 |
| Unknown       | Unknown                     | [c801b9e5af](https://bsd-hardware.info/?probe=c801b9e5af) | Apr 03, 2023 |
| Unknown       | Unknown                     | [9b2420726f](https://bsd-hardware.info/?probe=9b2420726f) | Apr 03, 2023 |
| Unknown       | Unknown                     | [414cbf5935](https://bsd-hardware.info/?probe=414cbf5935) | Apr 03, 2023 |
| Unknown       | Unknown                     | [6b79c64c73](https://bsd-hardware.info/?probe=6b79c64c73) | Apr 03, 2023 |
| ASRock        | AB350M Pro4-F               | [424f3a2021](https://bsd-hardware.info/?probe=424f3a2021) | Apr 02, 2023 |
| ASRock        | X570S PG Riptide            | [8ccb321056](https://bsd-hardware.info/?probe=8ccb321056) | Apr 01, 2023 |
| Biostar       | TH67B                       | [234c5e0b83](https://bsd-hardware.info/?probe=234c5e0b83) | Mar 31, 2023 |
| ASRock        | X570S PG Riptide            | [0d66edbd38](https://bsd-hardware.info/?probe=0d66edbd38) | Mar 27, 2023 |
| Dell          | 0VD5HY A00                  | [1b54a68123](https://bsd-hardware.info/?probe=1b54a68123) | Mar 26, 2023 |
| MSI           | 870-G45                     | [19cbb6e0f3](https://bsd-hardware.info/?probe=19cbb6e0f3) | Mar 26, 2023 |
| MSI           | PRO H610M-B DDR4            | [ee01b690bc](https://bsd-hardware.info/?probe=ee01b690bc) | Mar 25, 2023 |
| MSI           | 870-G45                     | [14e990c885](https://bsd-hardware.info/?probe=14e990c885) | Mar 25, 2023 |
| ASUSTek       | P5K SE                      | [646eff3292](https://bsd-hardware.info/?probe=646eff3292) | Mar 25, 2023 |
| Stonesoft     | DEV-1301-2-C1-R             | [3bc0fc5d63](https://bsd-hardware.info/?probe=3bc0fc5d63) | Mar 24, 2023 |
| Stonesoft     | DEV-1301-2-C1-R             | [2699b59d1b](https://bsd-hardware.info/?probe=2699b59d1b) | Mar 24, 2023 |
| Unknown       | T360D11                     | [d4d69405c5](https://bsd-hardware.info/?probe=d4d69405c5) | Mar 23, 2023 |
| Gigabyte      | F2A55-DS3                   | [ce8775fbe5](https://bsd-hardware.info/?probe=ce8775fbe5) | Mar 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | [840a902d2b](https://bsd-hardware.info/?probe=840a902d2b) | Mar 22, 2023 |
| ASUSTek       | M5A78L-M LX3                | [3f78d8f1ae](https://bsd-hardware.info/?probe=3f78d8f1ae) | Mar 18, 2023 |
| Intel         | B75                         | [11bcf42a35](https://bsd-hardware.info/?probe=11bcf42a35) | Mar 18, 2023 |
| Unknown       | Unknown                     | [dd8a64237a](https://bsd-hardware.info/?probe=dd8a64237a) | Mar 18, 2023 |
| Intel         | DG35EC AAE29266-205         | [0ab42ce2ee](https://bsd-hardware.info/?probe=0ab42ce2ee) | Mar 16, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [da2b96de55](https://bsd-hardware.info/?probe=da2b96de55) | Mar 16, 2023 |
| Gigabyte      | B450M S2H                   | [dfa4f43317](https://bsd-hardware.info/?probe=dfa4f43317) | Mar 15, 2023 |
| Lenovo        | NO DPK                      | [8a38ed8d33](https://bsd-hardware.info/?probe=8a38ed8d33) | Mar 14, 2023 |
| ASUSTek       | B85M-G                      | [6401dd52d2](https://bsd-hardware.info/?probe=6401dd52d2) | Mar 14, 2023 |
| Gigabyte      | B365M H                     | [7acb7cb65f](https://bsd-hardware.info/?probe=7acb7cb65f) | Mar 13, 2023 |
| Gigabyte      | H110M-S2-CF                 | [6afb777789](https://bsd-hardware.info/?probe=6afb777789) | Mar 13, 2023 |
| Techvision    | TVI7309X B0                 | [f07e092146](https://bsd-hardware.info/?probe=f07e092146) | Mar 11, 2023 |
| MSI           | PRO H610M-B DDR4            | [b08fd92e36](https://bsd-hardware.info/?probe=b08fd92e36) | Mar 10, 2023 |
| MSI           | PRO H610M-B DDR4            | [654bdb4eb2](https://bsd-hardware.info/?probe=654bdb4eb2) | Mar 10, 2023 |
| Gigabyte      | B360M D2V                   | [6ac60b8104](https://bsd-hardware.info/?probe=6ac60b8104) | Mar 10, 2023 |
| Elpitech      | ET101-A1                    | [0172697883](https://bsd-hardware.info/?probe=0172697883) | Mar 10, 2023 |
| Huanan        | X99-QD4 V1.0                | [58090b9dbf](https://bsd-hardware.info/?probe=58090b9dbf) | Mar 09, 2023 |
| ASUSTek       | P8Z77-V PREMIUM             | [a2873d7c87](https://bsd-hardware.info/?probe=a2873d7c87) | Mar 09, 2023 |
| ASUSTek       | P7H55                       | [3c78171104](https://bsd-hardware.info/?probe=3c78171104) | Mar 04, 2023 |
| ASUSTek       | P7H55                       | [5ce8dbf5f3](https://bsd-hardware.info/?probe=5ce8dbf5f3) | Mar 04, 2023 |
| Huanan        | X99-QD4 V1.0                | [8404060d9e](https://bsd-hardware.info/?probe=8404060d9e) | Mar 02, 2023 |
| Unknown       | Unknown                     | [13ac9d6b7e](https://bsd-hardware.info/?probe=13ac9d6b7e) | Mar 01, 2023 |
| MSI           | PRO H610M-B DDR4            | [2072e8fac6](https://bsd-hardware.info/?probe=2072e8fac6) | Feb 28, 2023 |
| MSI           | PRO H610M-B DDR4            | [e85ed3f609](https://bsd-hardware.info/?probe=e85ed3f609) | Feb 27, 2023 |
| Unknown       | Unknown                     | [95c62844de](https://bsd-hardware.info/?probe=95c62844de) | Feb 25, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [b2681fdfb4](https://bsd-hardware.info/?probe=b2681fdfb4) | Feb 23, 2023 |
| MSI           | MS-92E3 0A                  | [683ff1f7d0](https://bsd-hardware.info/?probe=683ff1f7d0) | Feb 22, 2023 |
| Intel         | DN2820FYK H24582-203        | [dd0d96422f](https://bsd-hardware.info/?probe=dd0d96422f) | Feb 19, 2023 |
| ASRock        | G41M-GS3                    | [eace523f17](https://bsd-hardware.info/?probe=eace523f17) | Feb 18, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [6f4b514959](https://bsd-hardware.info/?probe=6f4b514959) | Feb 14, 2023 |
| Huanan        | X99-QD4 V1.0                | [9a0c17560f](https://bsd-hardware.info/?probe=9a0c17560f) | Feb 14, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [5507e05838](https://bsd-hardware.info/?probe=5507e05838) | Feb 12, 2023 |
| ASRock        | A770DE+                     | [cf1c018ede](https://bsd-hardware.info/?probe=cf1c018ede) | Feb 10, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [33af90dd93](https://bsd-hardware.info/?probe=33af90dd93) | Feb 08, 2023 |
| Intel         | DN2820FYK H24582-203        | [ae05d4c6cd](https://bsd-hardware.info/?probe=ae05d4c6cd) | Feb 06, 2023 |
| Unknown       | Unknown                     | [7fcfb747a7](https://bsd-hardware.info/?probe=7fcfb747a7) | Feb 06, 2023 |
| Techvision    | TVI7309X B0                 | [222da5a477](https://bsd-hardware.info/?probe=222da5a477) | Feb 04, 2023 |
| Techvision    | TVI7309X B0                 | [a58d9501ad](https://bsd-hardware.info/?probe=a58d9501ad) | Jan 31, 2023 |
| MACHINIST     | X99-K9 V2.0                 | [eb8a6cb004](https://bsd-hardware.info/?probe=eb8a6cb004) | Jan 30, 2023 |
| ChangWang     | CW56-58                     | [2d48772c23](https://bsd-hardware.info/?probe=2d48772c23) | Jan 27, 2023 |
| Citrix        | CB-1100                     | [36199a59e2](https://bsd-hardware.info/?probe=36199a59e2) | Jan 26, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [6b63a16799](https://bsd-hardware.info/?probe=6b63a16799) | Jan 26, 2023 |
| ChangWang     | CW56-58                     | [89ec5e42ef](https://bsd-hardware.info/?probe=89ec5e42ef) | Jan 26, 2023 |
| Gigabyte      | B360M D2V                   | [6685066b6e](https://bsd-hardware.info/?probe=6685066b6e) | Jan 26, 2023 |
| ASUSTek       | P5G41T-M LX3                | [a712c2d054](https://bsd-hardware.info/?probe=a712c2d054) | Jan 26, 2023 |
| Gigabyte      | H61M-S2PV                   | [9a307961ed](https://bsd-hardware.info/?probe=9a307961ed) | Jan 26, 2023 |
| ASUSTek       | P5G41T-M LX3                | [7b2fee315d](https://bsd-hardware.info/?probe=7b2fee315d) | Jan 26, 2023 |
| Shuttle       | DS20U                       | [71033e4a64](https://bsd-hardware.info/?probe=71033e4a64) | Jan 26, 2023 |
| Dell          | 0HY9JP A02                  | [ca71c8ab2b](https://bsd-hardware.info/?probe=ca71c8ab2b) | Jan 25, 2023 |
| Dell          | 0CNWVK A00                  | [e59d4ab226](https://bsd-hardware.info/?probe=e59d4ab226) | Jan 25, 2023 |
| ASUSTek       | P7P55D LE                   | [5da1e71837](https://bsd-hardware.info/?probe=5da1e71837) | Jan 25, 2023 |
| ASRock        | Z390 Pro4                   | [b9d64a7496](https://bsd-hardware.info/?probe=b9d64a7496) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS PRO              | [6cf4f6761e](https://bsd-hardware.info/?probe=6cf4f6761e) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [27ea626000](https://bsd-hardware.info/?probe=27ea626000) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [abc17c6fc6](https://bsd-hardware.info/?probe=abc17c6fc6) | Jan 23, 2023 |
| AZW           | U59                         | [1f97b27470](https://bsd-hardware.info/?probe=1f97b27470) | Jan 23, 2023 |
| MSI           | B450M MORTAR MAX            | [840145eb80](https://bsd-hardware.info/?probe=840145eb80) | Jan 23, 2023 |
| Unknown       | Unknown                     | [8956f4503e](https://bsd-hardware.info/?probe=8956f4503e) | Jan 21, 2023 |
| Unknown       | AMD-GX3                     | [a38ff8331a](https://bsd-hardware.info/?probe=a38ff8331a) | Jan 20, 2023 |
| Unknown       | Unknown                     | [3afbfc6cea](https://bsd-hardware.info/?probe=3afbfc6cea) | Jan 20, 2023 |
| Unknown       | YL-SKUL6                    | [ef4abfe322](https://bsd-hardware.info/?probe=ef4abfe322) | Jan 20, 2023 |
| Unknown       | Unknown                     | [e13627df1a](https://bsd-hardware.info/?probe=e13627df1a) | Jan 20, 2023 |
| Unknown       | Unknown                     | [8c44d6309f](https://bsd-hardware.info/?probe=8c44d6309f) | Jan 15, 2023 |
| ASUSTek       | PRIME Z390-P                | [3126dc27f1](https://bsd-hardware.info/?probe=3126dc27f1) | Jan 12, 2023 |
| ASUSTek       | H81M-E                      | [1008903f65](https://bsd-hardware.info/?probe=1008903f65) | Jan 11, 2023 |
| Techvision    | TVI7309X B0                 | [2293d4960d](https://bsd-hardware.info/?probe=2293d4960d) | Jan 11, 2023 |
| Citrix        | CB-1100                     | [860f27ce64](https://bsd-hardware.info/?probe=860f27ce64) | Jan 11, 2023 |
| Techvision    | TVI7309X B0                 | [19f4631b5a](https://bsd-hardware.info/?probe=19f4631b5a) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | [1deece00b3](https://bsd-hardware.info/?probe=1deece00b3) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | [cc9d84d5ed](https://bsd-hardware.info/?probe=cc9d84d5ed) | Jan 05, 2023 |
| Unknown       | Unknown                     | [ea01217f17](https://bsd-hardware.info/?probe=ea01217f17) | Jan 02, 2023 |
| Gigabyte      | C1037UN-EU                  | [9c526b27dd](https://bsd-hardware.info/?probe=9c526b27dd) | Jan 02, 2023 |
| Shuttle       | DS20U                       | [a5aa09e49f](https://bsd-hardware.info/?probe=a5aa09e49f) | Jan 01, 2023 |
| Unknown       | Unknown                     | [4c3b92bb42](https://bsd-hardware.info/?probe=4c3b92bb42) | Dec 24, 2022 |
| Unknown       | Unknown                     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| Unknown       | Unknown                     | [3e5e7e3e61](https://bsd-hardware.info/?probe=3e5e7e3e61) | Dec 22, 2022 |
| Unknown       | Unknown                     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| Unknown       | Unknown                     | [9b5307f44d](https://bsd-hardware.info/?probe=9b5307f44d) | Dec 15, 2022 |
| Huanan        | X99-F8D V2.4                | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| ASUSTek       | P8H77-V LE                  | [10b6c81bce](https://bsd-hardware.info/?probe=10b6c81bce) | Dec 09, 2022 |
| Huanan        | X99-F8D V2.4                | [f6685811a3](https://bsd-hardware.info/?probe=f6685811a3) | Dec 05, 2022 |
| Dell          | 0CNWVK A00                  | [5a022db6bf](https://bsd-hardware.info/?probe=5a022db6bf) | Dec 05, 2022 |
| Intel         | X99                         | [c21a466fc1](https://bsd-hardware.info/?probe=c21a466fc1) | Dec 01, 2022 |
| MSI           | PRO H610M-B DDR4            | [929e4bda1e](https://bsd-hardware.info/?probe=929e4bda1e) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | [7c9ee800c5](https://bsd-hardware.info/?probe=7c9ee800c5) | Nov 29, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [43163b0170](https://bsd-hardware.info/?probe=43163b0170) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [d00aa0021e](https://bsd-hardware.info/?probe=d00aa0021e) | Nov 28, 2022 |
| Acer          | Revo RN86                   | [a4dcb7f7a2](https://bsd-hardware.info/?probe=a4dcb7f7a2) | Nov 27, 2022 |
| Unknown       | Unknown                     | [1d3bd58d18](https://bsd-hardware.info/?probe=1d3bd58d18) | Nov 25, 2022 |
| Gigabyte      | H81M-HD3                    | [564cf3d66a](https://bsd-hardware.info/?probe=564cf3d66a) | Nov 22, 2022 |
| Unknown       | Unknown                     | [0760ed34c3](https://bsd-hardware.info/?probe=0760ed34c3) | Nov 21, 2022 |
| Huanan        | X99-F8D V2.4                | [9faf79b3f3](https://bsd-hardware.info/?probe=9faf79b3f3) | Nov 18, 2022 |
| Huanan        | X99-F8D V2.4                | [22ec05d988](https://bsd-hardware.info/?probe=22ec05d988) | Nov 12, 2022 |
| Acer          | RS880M05                    | [455f9b5026](https://bsd-hardware.info/?probe=455f9b5026) | Nov 07, 2022 |
| ASUSTek       | Z170-K                      | [907b8c2402](https://bsd-hardware.info/?probe=907b8c2402) | Nov 05, 2022 |
| Unknown       | Unknown                     | [58c2f4b4f7](https://bsd-hardware.info/?probe=58c2f4b4f7) | Nov 04, 2022 |
| Gigabyte      | Z68XP-UD3                   | [0f22defdb3](https://bsd-hardware.info/?probe=0f22defdb3) | Oct 30, 2022 |
| Unknown       | Unknown                     | [acf41f7000](https://bsd-hardware.info/?probe=acf41f7000) | Oct 29, 2022 |
| PC Engines    | APU2                        | [d52e3d0ce3](https://bsd-hardware.info/?probe=d52e3d0ce3) | Oct 25, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [d7b32200a5](https://bsd-hardware.info/?probe=d7b32200a5) | Oct 22, 2022 |
| Acer          | Revo RN86                   | [692ea69bab](https://bsd-hardware.info/?probe=692ea69bab) | Oct 21, 2022 |
| PC Engines    | APU2                        | [cf1abf5e46](https://bsd-hardware.info/?probe=cf1abf5e46) | Oct 21, 2022 |
| Unknown       | Unknown                     | [d5586487b4](https://bsd-hardware.info/?probe=d5586487b4) | Oct 21, 2022 |
| ASUSTek       | P10S-I Series               | [ceb58e75b8](https://bsd-hardware.info/?probe=ceb58e75b8) | Oct 20, 2022 |
| Supermicro    | X11SSL-F                    | [24faa4663c](https://bsd-hardware.info/?probe=24faa4663c) | Oct 19, 2022 |
| ASUSTek       | N3050I-C                    | [4a83b0953e](https://bsd-hardware.info/?probe=4a83b0953e) | Oct 18, 2022 |
| Gigabyte      | C1037UN-EU                  | [734ff7f48c](https://bsd-hardware.info/?probe=734ff7f48c) | Oct 02, 2022 |
| ASRock        | X570M Pro4                  | [433857f5f7](https://bsd-hardware.info/?probe=433857f5f7) | Sep 27, 2022 |
| YANYU         | H67SL                       | [5f5819ef11](https://bsd-hardware.info/?probe=5f5819ef11) | Sep 24, 2022 |
| NITRINOnet    | M360RUS56                   | [490b9593e0](https://bsd-hardware.info/?probe=490b9593e0) | Sep 23, 2022 |
| YANYU         | H67SL                       | [37ba00c2f3](https://bsd-hardware.info/?probe=37ba00c2f3) | Sep 15, 2022 |
| Maxtang       | BYT30                       | [90053990c3](https://bsd-hardware.info/?probe=90053990c3) | Sep 10, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [98dff45d54](https://bsd-hardware.info/?probe=98dff45d54) | Sep 09, 2022 |
| Dell          | 0Y7WYT A00                  | [2870b9e4c7](https://bsd-hardware.info/?probe=2870b9e4c7) | Sep 05, 2022 |
| HP            | 8719                        | [f3132fc160](https://bsd-hardware.info/?probe=f3132fc160) | Sep 05, 2022 |
| Maxtang       | BYT30                       | [f5c34c7662](https://bsd-hardware.info/?probe=f5c34c7662) | Sep 03, 2022 |
| ASRock        | ConRoeXFire-eSATA2          | [caf005ed95](https://bsd-hardware.info/?probe=caf005ed95) | Sep 01, 2022 |
| Intel         | X79 V2.72A                  | [435901d8c9](https://bsd-hardware.info/?probe=435901d8c9) | Aug 29, 2022 |
| Gigabyte      | A320M-H-CF                  | [2549c7cadf](https://bsd-hardware.info/?probe=2549c7cadf) | Aug 27, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [7d4eaaf087](https://bsd-hardware.info/?probe=7d4eaaf087) | Aug 22, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [063addc66e](https://bsd-hardware.info/?probe=063addc66e) | Aug 22, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [5ea9441653](https://bsd-hardware.info/?probe=5ea9441653) | Aug 19, 2022 |
| Gigabyte      | C1037UN-EU                  | [0a867d7017](https://bsd-hardware.info/?probe=0a867d7017) | Aug 18, 2022 |
| Gigabyte      | H61M-DS2                    | [a2fc8d9c67](https://bsd-hardware.info/?probe=a2fc8d9c67) | Aug 18, 2022 |
| Gigabyte      | H61M-DS2                    | [9a7d45e51c](https://bsd-hardware.info/?probe=9a7d45e51c) | Aug 16, 2022 |
| ASUSTek       | PRIME X370-PRO              | [4055810ef2](https://bsd-hardware.info/?probe=4055810ef2) | Aug 14, 2022 |
| ASRock        | H110M-DGS R3.0              | [0c654b6c34](https://bsd-hardware.info/?probe=0c654b6c34) | Aug 11, 2022 |
| Unknown       | Unknown                     | [467bcd3c04](https://bsd-hardware.info/?probe=467bcd3c04) | Aug 07, 2022 |
| Unknown       | Unknown                     | [b3c0b4a4f4](https://bsd-hardware.info/?probe=b3c0b4a4f4) | Aug 04, 2022 |
| Unknown       | Unknown                     | [612282319b](https://bsd-hardware.info/?probe=612282319b) | Aug 04, 2022 |
| Acer          | Revo 70                     | [0c23ffdc5a](https://bsd-hardware.info/?probe=0c23ffdc5a) | Aug 03, 2022 |
| ASRock        | A320M-DVS R4.0              | [77f61a8711](https://bsd-hardware.info/?probe=77f61a8711) | Aug 01, 2022 |
| Gigabyte      | 970A-DS3P FX                | [3c33e546bb](https://bsd-hardware.info/?probe=3c33e546bb) | Jul 31, 2022 |
| HP            | 339A                        | [241e56a349](https://bsd-hardware.info/?probe=241e56a349) | Jul 27, 2022 |
| Gigabyte      | H61M-DS2                    | [3ba3cedec4](https://bsd-hardware.info/?probe=3ba3cedec4) | Jul 21, 2022 |
| Acer          | RS880M05                    | [7bcc14ceba](https://bsd-hardware.info/?probe=7bcc14ceba) | Jul 16, 2022 |
| Gigabyte      | H310M S2 x.x                | [b11ca9c369](https://bsd-hardware.info/?probe=b11ca9c369) | Jul 16, 2022 |
| Acer          | Revo 70                     | [aad484a882](https://bsd-hardware.info/?probe=aad484a882) | Jul 13, 2022 |
| Acer          | Revo 70                     | [c8b51a94bd](https://bsd-hardware.info/?probe=c8b51a94bd) | Jul 13, 2022 |
| Kraftway      | KWH77                       | [c34f44a495](https://bsd-hardware.info/?probe=c34f44a495) | Jul 12, 2022 |
| Gigabyte      | C1037UN-EU                  | [3644f56368](https://bsd-hardware.info/?probe=3644f56368) | Jul 10, 2022 |
| Intel         | DN2820FYK H24582-203        | [8a9a8cdbd0](https://bsd-hardware.info/?probe=8a9a8cdbd0) | Jul 08, 2022 |
| Lenovo        | NO DPK                      | [2c79a92fc4](https://bsd-hardware.info/?probe=2c79a92fc4) | Jul 06, 2022 |
| Techvision    | TVI7309X B0                 | [12279c8a4b](https://bsd-hardware.info/?probe=12279c8a4b) | Jul 06, 2022 |
| Techvision    | TVI7309X B0                 | [19a4b27ae7](https://bsd-hardware.info/?probe=19a4b27ae7) | Jul 05, 2022 |
| Acer          | Aspire XC-895 V:1.0         | [d67aa61a6b](https://bsd-hardware.info/?probe=d67aa61a6b) | Jul 05, 2022 |
| Acer          | Revo RN86                   | [2dc98202aa](https://bsd-hardware.info/?probe=2dc98202aa) | Jul 05, 2022 |
| Gigabyte      | G41MT-S2                    | [0563158740](https://bsd-hardware.info/?probe=0563158740) | Jun 28, 2022 |
| ASRock        | P67 Professional            | [3372d35113](https://bsd-hardware.info/?probe=3372d35113) | Jun 28, 2022 |
| Dell          | 07KY25 A00                  | [9981217b1b](https://bsd-hardware.info/?probe=9981217b1b) | Jun 16, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [067dbf3357](https://bsd-hardware.info/?probe=067dbf3357) | Jun 15, 2022 |
| Pegatron      | 2A94h                       | [17078490f7](https://bsd-hardware.info/?probe=17078490f7) | Jun 11, 2022 |
| Pegatron      | 2A94h                       | [438d4f9b2f](https://bsd-hardware.info/?probe=438d4f9b2f) | Jun 09, 2022 |
| Gigabyte      | F2A75M-D3H                  | [ae3436167b](https://bsd-hardware.info/?probe=ae3436167b) | Jun 05, 2022 |
| Unknown       | Unknown                     | [a56bc64f26](https://bsd-hardware.info/?probe=a56bc64f26) | May 27, 2022 |
| ASUSTek       | P5LD2                       | [64208afa2c](https://bsd-hardware.info/?probe=64208afa2c) | May 25, 2022 |
| khadas        | edge-v                      | [60fb48e34c](https://bsd-hardware.info/?probe=60fb48e34c) | May 23, 2022 |
| khadas        | edge-v                      | [6facaa8032](https://bsd-hardware.info/?probe=6facaa8032) | May 22, 2022 |
| Gigabyte      | H81M-S2PV                   | [1937e77b97](https://bsd-hardware.info/?probe=1937e77b97) | May 22, 2022 |
| ASUSTek       | P8Z77-V LX                  | [e7055d83e2](https://bsd-hardware.info/?probe=e7055d83e2) | May 20, 2022 |
| Supermicro    | X10DRi-T                    | [d6fa145c7c](https://bsd-hardware.info/?probe=d6fa145c7c) | May 16, 2022 |
| HP            | ProLiant MicroServer        | [e569bffe8f](https://bsd-hardware.info/?probe=e569bffe8f) | May 12, 2022 |
| Unknown       | Unknown                     | [224614e9ab](https://bsd-hardware.info/?probe=224614e9ab) | May 10, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [76eef59920](https://bsd-hardware.info/?probe=76eef59920) | May 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | [bf3d4941a2](https://bsd-hardware.info/?probe=bf3d4941a2) | May 06, 2022 |
| Gigabyte      | A320M-H-CF                  | [24d308754b](https://bsd-hardware.info/?probe=24d308754b) | May 02, 2022 |
| Unknown       | Unknown                     | [d036c00d6c](https://bsd-hardware.info/?probe=d036c00d6c) | Apr 28, 2022 |
| ASRock        | J3355B-ITX                  | [c0739686fb](https://bsd-hardware.info/?probe=c0739686fb) | Apr 28, 2022 |
| Supermicro    | X10DRi-T                    | [dcd02e012d](https://bsd-hardware.info/?probe=dcd02e012d) | Apr 28, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1a475f0939](https://bsd-hardware.info/?probe=1a475f0939) | Apr 27, 2022 |
| ASRock        | X570S PG Riptide            | [928d2abb5e](https://bsd-hardware.info/?probe=928d2abb5e) | Apr 26, 2022 |
| Gigabyte      | H310M S2 x.x                | [549053284c](https://bsd-hardware.info/?probe=549053284c) | Apr 25, 2022 |
| PC Engines    | APU2                        | [04a6549c99](https://bsd-hardware.info/?probe=04a6549c99) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | [955922ebe2](https://bsd-hardware.info/?probe=955922ebe2) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | [4d66b2b328](https://bsd-hardware.info/?probe=4d66b2b328) | Apr 23, 2022 |
| Intel         | DH67BL                      | [3c3c9e12da](https://bsd-hardware.info/?probe=3c3c9e12da) | Apr 22, 2022 |
| KOHJINSHA     | SH series                   | [3136a0ca03](https://bsd-hardware.info/?probe=3136a0ca03) | Apr 22, 2022 |
| Lenovo        | ThinkPad X240 20ALA0AHRT    | [062a08c811](https://bsd-hardware.info/?probe=062a08c811) | Apr 22, 2022 |
| Gigabyte      | B450 AORUS M                | [427cf12b45](https://bsd-hardware.info/?probe=427cf12b45) | Apr 22, 2022 |
| Sony          | VPCL22Z1R                   | [f199d57905](https://bsd-hardware.info/?probe=f199d57905) | Apr 22, 2022 |
| ASUSTek       | Z170-K                      | [b16705bbbd](https://bsd-hardware.info/?probe=b16705bbbd) | Apr 22, 2022 |
| ASUSTek       | P10S-I Series               | [aca13dba36](https://bsd-hardware.info/?probe=aca13dba36) | Apr 22, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [8e64404e52](https://bsd-hardware.info/?probe=8e64404e52) | Apr 19, 2022 |
| Shuttle       | DS20U                       | [f01372719f](https://bsd-hardware.info/?probe=f01372719f) | Apr 16, 2022 |
| HP            | ProLiant MicroServer        | [fa76da045a](https://bsd-hardware.info/?probe=fa76da045a) | Apr 13, 2022 |
| Gigabyte      | E3000N                      | [7169c296cc](https://bsd-hardware.info/?probe=7169c296cc) | Apr 08, 2022 |
| Supermicro    | X10DRi-T                    | [e17bbe2186](https://bsd-hardware.info/?probe=e17bbe2186) | Apr 05, 2022 |
| Gigabyte      | H310M S2 x.x                | [29a9462f72](https://bsd-hardware.info/?probe=29a9462f72) | Apr 04, 2022 |
| Intel         | DCP847SKE                   | [a79e298be3](https://bsd-hardware.info/?probe=a79e298be3) | Apr 03, 2022 |
| Supermicro    | X10DRi-T                    | [eae4612261](https://bsd-hardware.info/?probe=eae4612261) | Mar 31, 2022 |
| MSI           | B85-G43                     | [f0a919c35f](https://bsd-hardware.info/?probe=f0a919c35f) | Mar 25, 2022 |
| MSI           | B85-G43                     | [7bd545fda8](https://bsd-hardware.info/?probe=7bd545fda8) | Mar 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | [8696405d09](https://bsd-hardware.info/?probe=8696405d09) | Mar 24, 2022 |
| Huanan        | X99-F8D V2.4                | [4ef193841e](https://bsd-hardware.info/?probe=4ef193841e) | Mar 13, 2022 |
| Gigabyte      | G31M-S2C                    | [5a22bb6991](https://bsd-hardware.info/?probe=5a22bb6991) | Mar 12, 2022 |
| MSI           | B350M BAZOOKA               | [bac8d0bdb7](https://bsd-hardware.info/?probe=bac8d0bdb7) | Mar 11, 2022 |
| ASRock        | G41C-VS                     | [a9a1b1a493](https://bsd-hardware.info/?probe=a9a1b1a493) | Mar 03, 2022 |
| Intel         | DN2800MT AAG23738-600       | [8ecf2d023f](https://bsd-hardware.info/?probe=8ecf2d023f) | Mar 02, 2022 |
| Gigabyte      | X58A-UD5                    | [58d57520c1](https://bsd-hardware.info/?probe=58d57520c1) | Feb 20, 2022 |
| Gigabyte      | C1037UN-EU                  | [5b6dd82da8](https://bsd-hardware.info/?probe=5b6dd82da8) | Feb 18, 2022 |
| ASRock        | B460M Pro4                  | [7a2781344f](https://bsd-hardware.info/?probe=7a2781344f) | Feb 17, 2022 |
| MW            | GMLK-2_5G4L                 | [2dd03795ba](https://bsd-hardware.info/?probe=2dd03795ba) | Feb 11, 2022 |
| ASRock        | X370 Gaming X               | [22f8d133d4](https://bsd-hardware.info/?probe=22f8d133d4) | Feb 09, 2022 |
| ASRock        | D1800M                      | [0902154c8e](https://bsd-hardware.info/?probe=0902154c8e) | Feb 08, 2022 |
| Dell          | 0654JC A01                  | [bbcf2bad96](https://bsd-hardware.info/?probe=bbcf2bad96) | Feb 08, 2022 |
| ASUSTek       | P5G41T-M                    | [a7d5b65ba1](https://bsd-hardware.info/?probe=a7d5b65ba1) | Feb 07, 2022 |
| MSI           | MS-7C96                     | [c08331ad58](https://bsd-hardware.info/?probe=c08331ad58) | Feb 06, 2022 |
| Kontron       | KT965/ATXP 61420000         | [b5389bbf43](https://bsd-hardware.info/?probe=b5389bbf43) | Feb 06, 2022 |
| ASRock        | H81M-VG4 R2.0               | [8af8b5270e](https://bsd-hardware.info/?probe=8af8b5270e) | Feb 04, 2022 |
| ASUSTek       | P4P800-VM                   | [2343c503a7](https://bsd-hardware.info/?probe=2343c503a7) | Feb 04, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [58ea01e4e6](https://bsd-hardware.info/?probe=58ea01e4e6) | Jan 29, 2022 |
| Lenovo        | 30C9 NOK                    | [7169d2989c](https://bsd-hardware.info/?probe=7169d2989c) | Jan 29, 2022 |
| Pegatron      | IPPPV-D3G                   | [d5e44ccf6b](https://bsd-hardware.info/?probe=d5e44ccf6b) | Jan 28, 2022 |
| ASUSTek       | P5GC-MX                     | [372749f9d7](https://bsd-hardware.info/?probe=372749f9d7) | Jan 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [eb44c8d7e1](https://bsd-hardware.info/?probe=eb44c8d7e1) | Jan 27, 2022 |
| ASUSTek       | P5B SE                      | [f97fba19c1](https://bsd-hardware.info/?probe=f97fba19c1) | Jan 26, 2022 |
| Kontron       | KT965/ATXP 61420000         | [36109b09ca](https://bsd-hardware.info/?probe=36109b09ca) | Jan 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [9f0a000ceb](https://bsd-hardware.info/?probe=9f0a000ceb) | Jan 25, 2022 |
| ASUSTek       | P5B SE                      | [e3332e7b94](https://bsd-hardware.info/?probe=e3332e7b94) | Jan 25, 2022 |
| ASRock        | B460M Pro4                  | [107a1e59f5](https://bsd-hardware.info/?probe=107a1e59f5) | Jan 25, 2022 |
| MSI           | G31TM-P21                   | [10ca6492c1](https://bsd-hardware.info/?probe=10ca6492c1) | Jan 25, 2022 |
| MSI           | G31TM-P21                   | [7563c4cf09](https://bsd-hardware.info/?probe=7563c4cf09) | Jan 25, 2022 |
| Kontron       | KT965/ATXP 61420000         | [db757ea2ef](https://bsd-hardware.info/?probe=db757ea2ef) | Jan 25, 2022 |
| Gigabyte      | H310M S2 x.x                | [b0aeac1ef8](https://bsd-hardware.info/?probe=b0aeac1ef8) | Jan 25, 2022 |
| ASUSTek       | P5M2                        | [f2d4eccf4d](https://bsd-hardware.info/?probe=f2d4eccf4d) | Jan 24, 2022 |
| ASUSTek       | P7H55-M                     | [fb73c2f7dc](https://bsd-hardware.info/?probe=fb73c2f7dc) | Jan 23, 2022 |
| ASRock        | J3455-ITX                   | [55d70a3070](https://bsd-hardware.info/?probe=55d70a3070) | Jan 22, 2022 |
| ASRock        | J3455-ITX                   | [bf033b6b9f](https://bsd-hardware.info/?probe=bf033b6b9f) | Jan 22, 2022 |
| Intel         | DCP847SKE                   | [2828ef2a6d](https://bsd-hardware.info/?probe=2828ef2a6d) | Jan 20, 2022 |
| ASUSTek       | PRIME Z590-P                | [0473b57d99](https://bsd-hardware.info/?probe=0473b57d99) | Jan 19, 2022 |
| Intel CNCT... | Unknown                     | [0debf023f1](https://bsd-hardware.info/?probe=0debf023f1) | Jan 18, 2022 |
| Gigabyte      | B365 HD3                    | [62fc48bd99](https://bsd-hardware.info/?probe=62fc48bd99) | Jan 15, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d377e06101](https://bsd-hardware.info/?probe=d377e06101) | Jan 15, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [384cbe9714](https://bsd-hardware.info/?probe=384cbe9714) | Jan 13, 2022 |
| ASUSTek       | A68HM-PLUS                  | [650628a974](https://bsd-hardware.info/?probe=650628a974) | Jan 10, 2022 |
| friendlyel... | nanopi-m4                   | [bb29e50061](https://bsd-hardware.info/?probe=bb29e50061) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [14d6cfb7a4](https://bsd-hardware.info/?probe=14d6cfb7a4) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [ce75fa56bd](https://bsd-hardware.info/?probe=ce75fa56bd) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [612825abe3](https://bsd-hardware.info/?probe=612825abe3) | Dec 27, 2021 |
| khadas        | edge-v                      | [42c428aac0](https://bsd-hardware.info/?probe=42c428aac0) | Dec 26, 2021 |
| Gigabyte      | 970A-DS3P                   | [0918f0a5b9](https://bsd-hardware.info/?probe=0918f0a5b9) | Dec 25, 2021 |
| ASUSTek       | PRIME B350M-A               | [b0aa3885bb](https://bsd-hardware.info/?probe=b0aa3885bb) | Dec 25, 2021 |
| Acer          | Revo RN86                   | [6d184a1e62](https://bsd-hardware.info/?probe=6d184a1e62) | Dec 23, 2021 |
| Gigabyte      | E3000N                      | [eb0ba1b296](https://bsd-hardware.info/?probe=eb0ba1b296) | Dec 22, 2021 |
| HP            | 1850                        | [aa737033c4](https://bsd-hardware.info/?probe=aa737033c4) | Dec 21, 2021 |
| HP            | 1850                        | [17f42cda78](https://bsd-hardware.info/?probe=17f42cda78) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5cc62c68f9](https://bsd-hardware.info/?probe=5cc62c68f9) | Dec 21, 2021 |
| ASRock        | H110M-DGS                   | [40c4553adb](https://bsd-hardware.info/?probe=40c4553adb) | Dec 21, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [bc55ac50d1](https://bsd-hardware.info/?probe=bc55ac50d1) | Dec 20, 2021 |
| Acer          | Revo RN86                   | [68541bb331](https://bsd-hardware.info/?probe=68541bb331) | Dec 20, 2021 |
| Acer          | Aspire XC-895 V:1.0         | [58440d7663](https://bsd-hardware.info/?probe=58440d7663) | Dec 20, 2021 |
| MSI           | MS-9852 10                  | [4b851eef0a](https://bsd-hardware.info/?probe=4b851eef0a) | Dec 19, 2021 |
| ASUSTek       | P5G41T-M                    | [44bba395e8](https://bsd-hardware.info/?probe=44bba395e8) | Dec 13, 2021 |
| ASUSTek       | P5G41T-M                    | [1fb865c4ae](https://bsd-hardware.info/?probe=1fb865c4ae) | Dec 09, 2021 |
| Gigabyte      | Z68XP-UD3                   | [9fca53da56](https://bsd-hardware.info/?probe=9fca53da56) | Dec 08, 2021 |
| ASUSTek       | P5B                         | [93b542ab79](https://bsd-hardware.info/?probe=93b542ab79) | Dec 06, 2021 |
| Gigabyte      | GA-8S661FXM-775             | [3a64909558](https://bsd-hardware.info/?probe=3a64909558) | Dec 06, 2021 |
| Gigabyte      | MZGLKBP-00                  | [e713e3adee](https://bsd-hardware.info/?probe=e713e3adee) | Dec 05, 2021 |
| Unknown       | Q2XX V1.1                   | [66d6a26e35](https://bsd-hardware.info/?probe=66d6a26e35) | Dec 04, 2021 |
| Unknown       | Unknown                     | [a91c9ec877](https://bsd-hardware.info/?probe=a91c9ec877) | Dec 04, 2021 |
| Gigabyte      | H81M-S2PV                   | [0d4c532744](https://bsd-hardware.info/?probe=0d4c532744) | Nov 29, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [dab56eef53](https://bsd-hardware.info/?probe=dab56eef53) | Nov 07, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [f26b302e43](https://bsd-hardware.info/?probe=f26b302e43) | Nov 07, 2021 |
| Unknown       | Intel X79                   | [044908e7c3](https://bsd-hardware.info/?probe=044908e7c3) | Oct 30, 2021 |
| Gigabyte      | Z77X-UD3H                   | [4c9b877754](https://bsd-hardware.info/?probe=4c9b877754) | Oct 29, 2021 |
| HP            | 0A60h                       | [5c227c5b61](https://bsd-hardware.info/?probe=5c227c5b61) | Oct 27, 2021 |
| Radxa         | rock-pi-4                   | [767ef0f0a6](https://bsd-hardware.info/?probe=767ef0f0a6) | Oct 27, 2021 |
| Radxa         | rock-pi-4                   | [fcd3e65f7e](https://bsd-hardware.info/?probe=fcd3e65f7e) | Oct 26, 2021 |
| Acer          | RS880M05                    | [4718f0cb0c](https://bsd-hardware.info/?probe=4718f0cb0c) | Oct 21, 2021 |
| Radxa         | rock-pi-4                   | [876564310f](https://bsd-hardware.info/?probe=876564310f) | Oct 19, 2021 |
| Unknown       | Unknown                     | [9716564d5e](https://bsd-hardware.info/?probe=9716564d5e) | Oct 19, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [39c78ac754](https://bsd-hardware.info/?probe=39c78ac754) | Oct 19, 2021 |
| ASUSTek       | P5P43TD PRO                 | [2870e26de1](https://bsd-hardware.info/?probe=2870e26de1) | Oct 17, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [5173ffc13b](https://bsd-hardware.info/?probe=5173ffc13b) | Oct 17, 2021 |
| Dell          | 0Y7WYT A00                  | [1de7ed2a67](https://bsd-hardware.info/?probe=1de7ed2a67) | Oct 16, 2021 |
| Lenovo        | SHARKBAY No DPK             | [e762f9146e](https://bsd-hardware.info/?probe=e762f9146e) | Oct 16, 2021 |
| ASUSTek       | P10S-I Series               | [d086bf947a](https://bsd-hardware.info/?probe=d086bf947a) | Oct 15, 2021 |
| ASUSTek       | F2A85-M                     | [b4e3f33e5c](https://bsd-hardware.info/?probe=b4e3f33e5c) | Oct 14, 2021 |
| Lenovo        | SHARKBAY No DPK             | [14dcd924b5](https://bsd-hardware.info/?probe=14dcd924b5) | Oct 13, 2021 |
| Gigabyte      | B450 AORUS M                | [d09f63f257](https://bsd-hardware.info/?probe=d09f63f257) | Oct 07, 2021 |
| Intel         | J1900                       | [9d6c7612d3](https://bsd-hardware.info/?probe=9d6c7612d3) | Oct 05, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [bd312d1c88](https://bsd-hardware.info/?probe=bd312d1c88) | Oct 03, 2021 |
| Unknown       | Unknown                     | [b45dad63f6](https://bsd-hardware.info/?probe=b45dad63f6) | Sep 20, 2021 |
| Unknown       | Unknown                     | [ed7c1c1f3b](https://bsd-hardware.info/?probe=ed7c1c1f3b) | Sep 20, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [198c4264f9](https://bsd-hardware.info/?probe=198c4264f9) | Sep 16, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [062602e8db](https://bsd-hardware.info/?probe=062602e8db) | Sep 15, 2021 |
| ASRock        | B450M Pro4-F                | [ae1765efd5](https://bsd-hardware.info/?probe=ae1765efd5) | Sep 10, 2021 |
| Gigabyte      | Z68P-DS3                    | [9a2545337b](https://bsd-hardware.info/?probe=9a2545337b) | Sep 09, 2021 |
| ASUSTek       | P5KPL-CM                    | [01ac3a91d0](https://bsd-hardware.info/?probe=01ac3a91d0) | Sep 01, 2021 |
| ASUSTek       | PRIME Z590-P                | [aeb23122b6](https://bsd-hardware.info/?probe=aeb23122b6) | Aug 31, 2021 |
| Intel         | DG33BU AAD79951-408         | [e8f4f644e3](https://bsd-hardware.info/?probe=e8f4f644e3) | Aug 30, 2021 |
| ASUSTek       | P4P800-VM                   | [f23a539453](https://bsd-hardware.info/?probe=f23a539453) | Aug 30, 2021 |
| Unknown       | Q2XX V1.1                   | [5ca9aa0bf2](https://bsd-hardware.info/?probe=5ca9aa0bf2) | Aug 19, 2021 |
| Gigabyte      | HA65M-D2H-B3                | [fc9b50bb85](https://bsd-hardware.info/?probe=fc9b50bb85) | Aug 16, 2021 |
| Supermicro    | X10DRH-CT                   | [6ccb3c09d6](https://bsd-hardware.info/?probe=6ccb3c09d6) | Aug 12, 2021 |
| Pegatron      | IPPCR-SS                    | [8a7fc2689b](https://bsd-hardware.info/?probe=8a7fc2689b) | Aug 09, 2021 |
| MSI           | H81M-P33                    | [6dcb3aa559](https://bsd-hardware.info/?probe=6dcb3aa559) | Aug 05, 2021 |
| ASRock        | X570 Pro4                   | [011fb96fe0](https://bsd-hardware.info/?probe=011fb96fe0) | Aug 04, 2021 |
| Gigabyte      | PH67A-D3-B3                 | [73dff53f04](https://bsd-hardware.info/?probe=73dff53f04) | Jul 23, 2021 |
| HP            | ProLiant DL360e Gen8        | [30eeb098b0](https://bsd-hardware.info/?probe=30eeb098b0) | Jul 10, 2021 |
| HP            | ProLiant DL320 G5           | [3b4ee33976](https://bsd-hardware.info/?probe=3b4ee33976) | Jul 10, 2021 |
| Foxconn       | AT-7000 Series              | [3802fb98b5](https://bsd-hardware.info/?probe=3802fb98b5) | Jul 10, 2021 |
| MSI           | H81M-E33                    | [c9fda90944](https://bsd-hardware.info/?probe=c9fda90944) | Jul 08, 2021 |
| Pegatron      | IPPCR-SS                    | [86b2e85d24](https://bsd-hardware.info/?probe=86b2e85d24) | Jul 05, 2021 |
| ASUSTek       | M5A97 R2.0                  | [e7a0dfcecf](https://bsd-hardware.info/?probe=e7a0dfcecf) | Jun 28, 2021 |
| Supermicro    | X10DRH-CT                   | [583e9e5a66](https://bsd-hardware.info/?probe=583e9e5a66) | Jun 26, 2021 |
| ECS           | A740GM-M                    | [a9d9106f11](https://bsd-hardware.info/?probe=a9d9106f11) | Jun 24, 2021 |
| Gigabyte      | GA-IMB370TN                 | [449fc82ff8](https://bsd-hardware.info/?probe=449fc82ff8) | Jun 21, 2021 |
| MSI           | H110M PRO-VH PLUS           | [45b842180e](https://bsd-hardware.info/?probe=45b842180e) | Jun 20, 2021 |
| ASUSTek       | H110I-PLUS                  | [0cb30b464d](https://bsd-hardware.info/?probe=0cb30b464d) | Jun 17, 2021 |
| ASUSTek       | M4A78LT-M                   | [0c8d6cd661](https://bsd-hardware.info/?probe=0c8d6cd661) | Jun 14, 2021 |
| Intel         | X79 V2.72A                  | [88173bcf06](https://bsd-hardware.info/?probe=88173bcf06) | Jun 14, 2021 |
| ASUSTek       | P5K SE/EPU                  | [60d9b24b69](https://bsd-hardware.info/?probe=60d9b24b69) | Jun 13, 2021 |
| Gigabyte      | GA-IMB370TN                 | [b486e670fe](https://bsd-hardware.info/?probe=b486e670fe) | Jun 02, 2021 |
| Biostar       | TH67B                       | [1f2321ec41](https://bsd-hardware.info/?probe=1f2321ec41) | Jun 01, 2021 |
| Gigabyte      | H61M-DS2                    | [d9657e7246](https://bsd-hardware.info/?probe=d9657e7246) | Jun 01, 2021 |
| ASUSTek       | PRIME Z590-P                | [8c06f6b716](https://bsd-hardware.info/?probe=8c06f6b716) | Jun 01, 2021 |
| Unknown       | Unknown                     | [d098ba539d](https://bsd-hardware.info/?probe=d098ba539d) | May 27, 2021 |
| ASUSTek       | P7H55-M/USB3                | [87068a97be](https://bsd-hardware.info/?probe=87068a97be) | May 26, 2021 |
| Unknown       | Unknown                     | [f9fa9ae41a](https://bsd-hardware.info/?probe=f9fa9ae41a) | May 24, 2021 |
| Acer          | Revo RN86                   | [ec302a221a](https://bsd-hardware.info/?probe=ec302a221a) | May 15, 2021 |
| Unknown       | Unknown                     | [364a778de1](https://bsd-hardware.info/?probe=364a778de1) | May 14, 2021 |
| ASUSTek       | Z87-PLUS                    | [629d15378d](https://bsd-hardware.info/?probe=629d15378d) | May 10, 2021 |
| ASUSTek       | H81M-K                      | [ae105fb8bc](https://bsd-hardware.info/?probe=ae105fb8bc) | May 09, 2021 |
| ASUSTek       | Maximus II Formula          | [493bb4da66](https://bsd-hardware.info/?probe=493bb4da66) | May 07, 2021 |
| Gigabyte      | X58A-UD5                    | [24502c7f7b](https://bsd-hardware.info/?probe=24502c7f7b) | May 04, 2021 |
| ASUSTek       | P10S-I Series               | [6548ae7d88](https://bsd-hardware.info/?probe=6548ae7d88) | May 01, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [8055ed41df](https://bsd-hardware.info/?probe=8055ed41df) | Apr 25, 2021 |
| Gigabyte      | F2A75M-HD2                  | [18a74377ac](https://bsd-hardware.info/?probe=18a74377ac) | Apr 25, 2021 |
| Unknown       | Q2XX V1.1                   | [5c7ea7fb7d](https://bsd-hardware.info/?probe=5c7ea7fb7d) | Apr 24, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [ab8235808d](https://bsd-hardware.info/?probe=ab8235808d) | Apr 23, 2021 |
| Gigabyte      | C1037UN-EU                  | [a379c24586](https://bsd-hardware.info/?probe=a379c24586) | Apr 19, 2021 |
| Gigabyte      | GA-IMB370TN                 | [7c77a33f75](https://bsd-hardware.info/?probe=7c77a33f75) | Apr 18, 2021 |
| Unknown       | Unknown                     | [48090193c1](https://bsd-hardware.info/?probe=48090193c1) | Apr 17, 2021 |
| Unknown       | Unknown                     | [1c4a81b9a5](https://bsd-hardware.info/?probe=1c4a81b9a5) | Apr 17, 2021 |
| Unknown       | Unknown                     | [7b295345e6](https://bsd-hardware.info/?probe=7b295345e6) | Apr 17, 2021 |
| Unknown       | Unknown                     | [0c708350cd](https://bsd-hardware.info/?probe=0c708350cd) | Apr 17, 2021 |
| Gigabyte      | GA-IMB370TN                 | [513027c242](https://bsd-hardware.info/?probe=513027c242) | Apr 13, 2021 |
| Gigabyte      | GA-IMB370TN                 | [8023a25ccb](https://bsd-hardware.info/?probe=8023a25ccb) | Mar 29, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [ec9e43382e](https://bsd-hardware.info/?probe=ec9e43382e) | Mar 25, 2021 |
| ASRock        | H71M-DGS                    | [d05d6281d3](https://bsd-hardware.info/?probe=d05d6281d3) | Mar 21, 2021 |
| ASUSTek       | P8H77-I                     | [46d36c6b23](https://bsd-hardware.info/?probe=46d36c6b23) | Mar 21, 2021 |
| Intel         | PB_1900A V2.1               | [a2378c3bee](https://bsd-hardware.info/?probe=a2378c3bee) | Mar 17, 2021 |
| ASUSTek       | AT5NM10T-I                  | [7c26a8b81e](https://bsd-hardware.info/?probe=7c26a8b81e) | Mar 12, 2021 |
| ASRock        | Q1900M                      | [f366c06928](https://bsd-hardware.info/?probe=f366c06928) | Mar 09, 2021 |
| Gigabyte      | EG43M-S2H                   | [f6eaa55ada](https://bsd-hardware.info/?probe=f6eaa55ada) | Mar 06, 2021 |
| ASUSTek       | STRIX B250F GAMING          | [cf965a3a5b](https://bsd-hardware.info/?probe=cf965a3a5b) | Mar 06, 2021 |
| Gigabyte      | 8IG1000MK                   | [49ee1efce0](https://bsd-hardware.info/?probe=49ee1efce0) | Mar 01, 2021 |
| Kontron       | KT965/ATXP 61420000         | [8755a0003d](https://bsd-hardware.info/?probe=8755a0003d) | Mar 01, 2021 |
| Lenovo        | Board                       | [395ef09e6d](https://bsd-hardware.info/?probe=395ef09e6d) | Feb 25, 2021 |
| Lenovo        | Board                       | [96fbaf0644](https://bsd-hardware.info/?probe=96fbaf0644) | Feb 25, 2021 |
| ASRock        | G31M-VS2                    | [6c7150dc1b](https://bsd-hardware.info/?probe=6c7150dc1b) | Feb 24, 2021 |
| Acer          | TPDS05 R3700                | [651f8a2bb4](https://bsd-hardware.info/?probe=651f8a2bb4) | Feb 23, 2021 |
| PC Engines    | APU2                        | [02a107a767](https://bsd-hardware.info/?probe=02a107a767) | Feb 23, 2021 |
| ASRock        | J4205-ITX                   | [c8e0b22858](https://bsd-hardware.info/?probe=c8e0b22858) | Feb 23, 2021 |
| ASUSTek       | P8Z77-V LX                  | [8390039d0b](https://bsd-hardware.info/?probe=8390039d0b) | Feb 22, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [8e52de9bec](https://bsd-hardware.info/?probe=8e52de9bec) | Feb 19, 2021 |
| ASRock        | Z170 Pro4/D3                | [7df0653726](https://bsd-hardware.info/?probe=7df0653726) | Feb 19, 2021 |
| ASUSTek       | H87I-PLUS                   | [8f8f08f763](https://bsd-hardware.info/?probe=8f8f08f763) | Feb 17, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [ae42a14150](https://bsd-hardware.info/?probe=ae42a14150) | Feb 16, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [24551b886c](https://bsd-hardware.info/?probe=24551b886c) | Feb 16, 2021 |
| ASRock        | B550M Pro4                  | [61a5641019](https://bsd-hardware.info/?probe=61a5641019) | Feb 14, 2021 |
| ASUSTek       | PRIME B450M-A               | [ac6b550ff4](https://bsd-hardware.info/?probe=ac6b550ff4) | Feb 12, 2021 |
| ASUSTek       | P8H77-V                     | [aaaffba650](https://bsd-hardware.info/?probe=aaaffba650) | Feb 11, 2021 |
| ASUSTek       | P5GDC Pro                   | [ca50169bf4](https://bsd-hardware.info/?probe=ca50169bf4) | Feb 11, 2021 |
| Gigabyte      | J3455N-D3H                  | [65e5edcfd7](https://bsd-hardware.info/?probe=65e5edcfd7) | Feb 11, 2021 |
| ASRock        | J3455M                      | [0493901aff](https://bsd-hardware.info/?probe=0493901aff) | Feb 10, 2021 |
| ASRock        | H61M-S                      | [f7b01b5274](https://bsd-hardware.info/?probe=f7b01b5274) | Feb 08, 2021 |
| Gigabyte      | Z68A-D3H-B3                 | [e1c3b89d0d](https://bsd-hardware.info/?probe=e1c3b89d0d) | Feb 06, 2021 |
| Gigabyte      | J3455N-D3H                  | [e2fd3451b6](https://bsd-hardware.info/?probe=e2fd3451b6) | Jan 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | [2a81a1bd1f](https://bsd-hardware.info/?probe=2a81a1bd1f) | Jan 24, 2021 |
| MSI           | MS-7235                     | [6a0d60ad2c](https://bsd-hardware.info/?probe=6a0d60ad2c) | Jan 21, 2021 |
| Dell          | 0Y7WYT A00                  | [4af9b92154](https://bsd-hardware.info/?probe=4af9b92154) | Jan 19, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [ad33eaab8a](https://bsd-hardware.info/?probe=ad33eaab8a) | Jan 19, 2021 |
| Centerm       | C30                         | [862ffd88e6](https://bsd-hardware.info/?probe=862ffd88e6) | Dec 16, 2020 |
| Gigabyte      | Z68P-DS3                    | [a1fe36fd99](https://bsd-hardware.info/?probe=a1fe36fd99) | Dec 16, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [fb6286f788](https://bsd-hardware.info/?probe=fb6286f788) | Dec 13, 2020 |
| ASUSTek       | P4P800-VM                   | [4fe4c14195](https://bsd-hardware.info/?probe=4fe4c14195) | Dec 05, 2020 |
| Acer          | Aspire XC-895 V:1.0         | [c5017eff06](https://bsd-hardware.info/?probe=c5017eff06) | Dec 04, 2020 |
| PC Engines    | APU2                        | [90d68eee14](https://bsd-hardware.info/?probe=90d68eee14) | Dec 04, 2020 |
| PC Engines    | APU2                        | [fab3041b1e](https://bsd-hardware.info/?probe=fab3041b1e) | Dec 04, 2020 |
| Gigabyte      | Unknown                     | [8a9ae48d42](https://bsd-hardware.info/?probe=8a9ae48d42) | Dec 01, 2020 |
| ASRock        | N68-GE                      | [ce9159c2fa](https://bsd-hardware.info/?probe=ce9159c2fa) | Nov 30, 2020 |
| Unknown       | Unknown                     | [153be3caa3](https://bsd-hardware.info/?probe=153be3caa3) | Nov 28, 2020 |
| ASRock        | N68-GE                      | [028eabaec2](https://bsd-hardware.info/?probe=028eabaec2) | Nov 28, 2020 |
| ASUSTek       | H97M-E                      | [c3230a9065](https://bsd-hardware.info/?probe=c3230a9065) | Nov 23, 2020 |
| ASUSTek       | P5GDC Pro                   | [8776b186c1](https://bsd-hardware.info/?probe=8776b186c1) | Nov 14, 2020 |
| ASRock        | X570 Steel Legend           | [8a79e3f5e4](https://bsd-hardware.info/?probe=8a79e3f5e4) | Nov 11, 2020 |
| Pegatron      | 1.03                        | [e660e12e3c](https://bsd-hardware.info/?probe=e660e12e3c) | Nov 10, 2020 |
| Gigabyte      | M61SME-S2L                  | [d8809eb5e7](https://bsd-hardware.info/?probe=d8809eb5e7) | Nov 09, 2020 |
| Gigabyte      | M61SME-S2L                  | [e5f658c70a](https://bsd-hardware.info/?probe=e5f658c70a) | Nov 09, 2020 |
| MSI           | Z97S SLI Krait Edition      | [c766aab801](https://bsd-hardware.info/?probe=c766aab801) | Nov 09, 2020 |
| Pegatron      | SKLD4-P1                    | [ea548b4c71](https://bsd-hardware.info/?probe=ea548b4c71) | Nov 08, 2020 |
| ASUSTek       | B75M-A                      | [43ece33e8c](https://bsd-hardware.info/?probe=43ece33e8c) | Oct 31, 2020 |
| ASRock        | J3455-ITX                   | [52fe99a6d6](https://bsd-hardware.info/?probe=52fe99a6d6) | Oct 29, 2020 |
| Gigabyte      | X58A-UD5                    | [6e642641e5](https://bsd-hardware.info/?probe=6e642641e5) | Oct 25, 2020 |
| ASUSTek       | B150M-K                     | [135db0e455](https://bsd-hardware.info/?probe=135db0e455) | Oct 22, 2020 |
| Unknown       | Unknown                     | [223aa9e0a3](https://bsd-hardware.info/?probe=223aa9e0a3) | Oct 22, 2020 |
| ASUSTek       | Z170-A                      | [a1c6966373](https://bsd-hardware.info/?probe=a1c6966373) | Oct 21, 2020 |
| ASUSTek       | Z170-K                      | [19cb3ccc34](https://bsd-hardware.info/?probe=19cb3ccc34) | Oct 20, 2020 |
| Intel         | S3000AH                     | [f5b858601a](https://bsd-hardware.info/?probe=f5b858601a) | Oct 20, 2020 |
| Unknown       | Unknown                     | [bedb4a4b37](https://bsd-hardware.info/?probe=bedb4a4b37) | Oct 20, 2020 |
| ASUSTek       | P10S-I Series               | [1a0e9f0100](https://bsd-hardware.info/?probe=1a0e9f0100) | Oct 19, 2020 |
| IBM           | Board                       | [af2f64a7a8](https://bsd-hardware.info/?probe=af2f64a7a8) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | [dc7b96e637](https://bsd-hardware.info/?probe=dc7b96e637) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | [0184fcedcf](https://bsd-hardware.info/?probe=0184fcedcf) | Oct 19, 2020 |
| Unknown       | Unknown                     | [e36fc2b2b2](https://bsd-hardware.info/?probe=e36fc2b2b2) | Oct 19, 2020 |
| ASRock        | N68C-S UCC                  | [027fbd78f5](https://bsd-hardware.info/?probe=027fbd78f5) | Oct 19, 2020 |
| MSI           | B450M MORTAR MAX            | [1123cb92ba](https://bsd-hardware.info/?probe=1123cb92ba) | Oct 04, 2020 |
| ASUSTek       | H81M-D PLUS                 | [95b75130f4](https://bsd-hardware.info/?probe=95b75130f4) | Sep 26, 2020 |
| Gigabyte      | C246-WU4-CF                 | [4117a39b03](https://bsd-hardware.info/?probe=4117a39b03) | Sep 23, 2020 |
| Acer          | Revo RN86                   | [d1b1775be3](https://bsd-hardware.info/?probe=d1b1775be3) | Sep 23, 2020 |
| ASUSTek       | H81M-D PLUS                 | [e8ab84404c](https://bsd-hardware.info/?probe=e8ab84404c) | Sep 22, 2020 |
| Acer          | Revo RN86                   | [c6b2c64d14](https://bsd-hardware.info/?probe=c6b2c64d14) | Sep 20, 2020 |
| ASUSTek       | H81M-D PLUS                 | [7be45f1bec](https://bsd-hardware.info/?probe=7be45f1bec) | Sep 19, 2020 |
| ASUSTek       | H81M-D PLUS                 | [e9dd488fe0](https://bsd-hardware.info/?probe=e9dd488fe0) | Sep 13, 2020 |
| ASUSTek       | P5QD TURBO                  | [598e77539b](https://bsd-hardware.info/?probe=598e77539b) | Aug 21, 2020 |
| ASUSTek       | P5QD TURBO                  | [e210609359](https://bsd-hardware.info/?probe=e210609359) | Aug 21, 2020 |
| Gigabyte      | X58A-UD5                    | [63a429ad0e](https://bsd-hardware.info/?probe=63a429ad0e) | Aug 16, 2020 |
| ASUSTek       | P8P67                       | [c61cac017e](https://bsd-hardware.info/?probe=c61cac017e) | Aug 06, 2020 |
| ASUSTek       | K8N-VM                      | [0ddf168986](https://bsd-hardware.info/?probe=0ddf168986) | Aug 06, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | [4f4cb01708](https://bsd-hardware.info/?probe=4f4cb01708) | Aug 05, 2020 |
| MSI           | H61M-P20                    | [fefac5637b](https://bsd-hardware.info/?probe=fefac5637b) | Aug 03, 2020 |
| ASRock        | E350M1                      | [08eec78cdf](https://bsd-hardware.info/?probe=08eec78cdf) | Jul 25, 2020 |
| ASUSTek       | P5Q DELUXE                  | [eb3f0a19ae](https://bsd-hardware.info/?probe=eb3f0a19ae) | Jul 25, 2020 |
| Pegatron      | 2A73                        | [05dea28605](https://bsd-hardware.info/?probe=05dea28605) | Jul 21, 2020 |
| Supermicro    | NSM5200A                    | [49a39eb60f](https://bsd-hardware.info/?probe=49a39eb60f) | Jul 15, 2020 |
| Gigabyte      | GA-790FXTA-UD5              | [667d98ccb2](https://bsd-hardware.info/?probe=667d98ccb2) | Jul 15, 2020 |
| ASRock        | B450 Pro4                   | [836bf04a97](https://bsd-hardware.info/?probe=836bf04a97) | Jul 15, 2020 |
| ASUSTek       | P5KPL-AM                    | [daaa05bbf4](https://bsd-hardware.info/?probe=daaa05bbf4) | Jul 15, 2020 |
| Gigabyte      | Z77-D3H                     | [97c6656398](https://bsd-hardware.info/?probe=97c6656398) | Jul 12, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [08dd1b91a8](https://bsd-hardware.info/?probe=08dd1b91a8) | Jun 30, 2020 |
| Foxconn       | nT-330i                     | [79ab8efb37](https://bsd-hardware.info/?probe=79ab8efb37) | Jun 29, 2020 |
| ASRock        | J3455-ITX                   | [1c8e18b787](https://bsd-hardware.info/?probe=1c8e18b787) | Jun 15, 2020 |
| Unknown       | Unknown                     | [ee9f9df2c1](https://bsd-hardware.info/?probe=ee9f9df2c1) | May 31, 2020 |
| Unknown       | Unknown                     | [6034ab8e6e](https://bsd-hardware.info/?probe=6034ab8e6e) | May 31, 2020 |
| ASRock        | Q1900M                      | [8787d15bc5](https://bsd-hardware.info/?probe=8787d15bc5) | May 31, 2020 |
| ASRock        | Q1900M                      | [79fe3017ef](https://bsd-hardware.info/?probe=79fe3017ef) | May 31, 2020 |
| Gigabyte      | M68MT-S2P                   | [08534174df](https://bsd-hardware.info/?probe=08534174df) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | [8e0f831fd8](https://bsd-hardware.info/?probe=8e0f831fd8) | May 27, 2020 |
| Gigabyte      | M68MT-S2P                   | [03ea0992c4](https://bsd-hardware.info/?probe=03ea0992c4) | May 27, 2020 |
| IBM           | Board                       | [1bcc2b8e0b](https://bsd-hardware.info/?probe=1bcc2b8e0b) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | [74b9526162](https://bsd-hardware.info/?probe=74b9526162) | May 27, 2020 |
| Gigabyte      | B450M GAMING                | [b4c4c676c4](https://bsd-hardware.info/?probe=b4c4c676c4) | May 26, 2020 |
| Unknown       | YL-J3060L2                  | [55be2fab24](https://bsd-hardware.info/?probe=55be2fab24) | May 26, 2020 |
| Gigabyte      | GA-MA78GM-UD2H              | [66bce86f33](https://bsd-hardware.info/?probe=66bce86f33) | May 26, 2020 |
| Acer          | WMCP78M                     | [db1e7a52b9](https://bsd-hardware.info/?probe=db1e7a52b9) | May 25, 2020 |
| Acer          | WMCP78M                     | [d9b08cfc0c](https://bsd-hardware.info/?probe=d9b08cfc0c) | May 25, 2020 |
| ASUSTek       | P5Q SE PLUS                 | [84e9e67aa2](https://bsd-hardware.info/?probe=84e9e67aa2) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | [8b9481baf2](https://bsd-hardware.info/?probe=8b9481baf2) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | [33c4579f99](https://bsd-hardware.info/?probe=33c4579f99) | May 25, 2020 |
| MSI           | MS-7255                     | [3984f45545](https://bsd-hardware.info/?probe=3984f45545) | May 25, 2020 |
| Gigabyte      | 945GM-S2                    | [59e3624de7](https://bsd-hardware.info/?probe=59e3624de7) | May 25, 2020 |
| Gigabyte      | F2A75M-HD2                  | [09bfdeafbd](https://bsd-hardware.info/?probe=09bfdeafbd) | May 25, 2020 |
| ASRock        | J4205-ITX                   | [bb67f0e80b](https://bsd-hardware.info/?probe=bb67f0e80b) | May 25, 2020 |
| ASUSTek       | Z87-EXPERT                  | [9f0ad7bbcf](https://bsd-hardware.info/?probe=9f0ad7bbcf) | May 25, 2020 |
| Supermicro    | X11DPH-T                    | [1db4784753](https://bsd-hardware.info/?probe=1db4784753) | May 25, 2020 |
| Supermicro    | X11DPH-T                    | [79aea35f1f](https://bsd-hardware.info/?probe=79aea35f1f) | May 25, 2020 |
| ASUSTek       | P5M2                        | [c1f04b3a84](https://bsd-hardware.info/?probe=c1f04b3a84) | May 25, 2020 |
| ASUSTek       | P6T SE                      | [66bbed8d59](https://bsd-hardware.info/?probe=66bbed8d59) | May 25, 2020 |
| ASUSTek       | P6T SE                      | [6eb355eabd](https://bsd-hardware.info/?probe=6eb355eabd) | May 25, 2020 |
| Gigabyte      | EX58-UD4                    | [e7f015c6da](https://bsd-hardware.info/?probe=e7f015c6da) | May 25, 2020 |
| ASUSTek       | P5Q                         | [97732c8106](https://bsd-hardware.info/?probe=97732c8106) | May 25, 2020 |
| ASUSTek       | P5GD2-Deluxe                | [5b1dc84da5](https://bsd-hardware.info/?probe=5b1dc84da5) | May 25, 2020 |
| Acer          | WMCP78M                     | [55755e9ab9](https://bsd-hardware.info/?probe=55755e9ab9) | May 25, 2020 |
| ASUSTek       | P5K-E                       | [a1b81962ac](https://bsd-hardware.info/?probe=a1b81962ac) | May 25, 2020 |
| ASUSTek       | P5K-E                       | [8f72d18bff](https://bsd-hardware.info/?probe=8f72d18bff) | May 25, 2020 |
| Gigabyte      | Z68P-DS3                    | [c06e03cda0](https://bsd-hardware.info/?probe=c06e03cda0) | May 25, 2020 |
| Intel         | DN2820FYK H24582-203        | [6cb240a9f6](https://bsd-hardware.info/?probe=6cb240a9f6) | May 25, 2020 |
| ASUSTek       | B75M-PLUS                   | [4620a00ccc](https://bsd-hardware.info/?probe=4620a00ccc) | May 25, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Russia/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| helloSystem 0.8.1    | 34       | 5.51%   |
| helloSystem 0.7.0    | 28       | 4.54%   |
| OpenBSD 6.8          | 19       | 3.08%   |
| FreeBSD 14.0-CURRENT | 16       | 2.59%   |
| FreeBSD 13.1         | 15       | 2.43%   |
| FreeBSD 13.0         | 15       | 2.43%   |
| FreeBSD 12.1-p5      | 15       | 2.43%   |
| helloSystem 0.8.0    | 14       | 2.27%   |
| FreeBSD 13.2         | 14       | 2.27%   |
| OpenBSD 7.3          | 13       | 2.11%   |
| OpenBSD 7.1          | 10       | 1.62%   |
| helloSystem 0.5.0    | 9        | 1.46%   |
| FreeBSD 13.0-STABLE  | 9        | 1.46%   |
| OpenBSD 7.0          | 8        | 1.3%    |
| OpenBSD 6.7          | 8        | 1.3%    |
| helloSystem 0.9.0    | 8        | 1.3%    |
| FreeBSD 12.1-STABLE  | 7        | 1.13%   |
| OpenBSD 7.2          | 6        | 0.97%   |
| helloSystem 0.6.0    | 6        | 0.97%   |
| helloSystem 0.4.0    | 6        | 0.97%   |
| FreeBSD 12.2         | 6        | 0.97%   |
| OPNsense 24.1.7      | 5        | 0.81%   |
| OPNsense 24.1.6      | 5        | 0.81%   |
| OPNsense 23.7.10     | 5        | 0.81%   |
| OPNsense 22.7.11     | 5        | 0.81%   |
| helloSystem 0.8.2    | 5        | 0.81%   |
| GhostBSD 20.04.02    | 5        | 0.81%   |
| FreeBSD 14.0         | 5        | 0.81%   |
| FreeBSD 12.1-p7      | 5        | 0.81%   |
| OPNsense 24.7.9      | 4        | 0.65%   |
| OPNsense 24.7.3      | 4        | 0.65%   |
| OPNsense 23.1        | 4        | 0.65%   |
| OPNsense 22.1.6      | 4        | 0.65%   |
| OPNsense 22.1.10     | 4        | 0.65%   |
| OPNsense 21.1.5      | 4        | 0.65%   |
| OpenBSD 6.9          | 4        | 0.65%   |
| MyBee 13.2           | 4        | 0.65%   |
| FreeBSD 14.0-BETA5   | 4        | 0.65%   |
| FreeBSD 12.2-p3      | 4        | 0.65%   |
| FreeBSD 12.2-p2      | 4        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| FreeBSD     | 182      | 35.34%  |
| OPNsense    | 120      | 23.3%   |
| helloSystem | 107      | 20.78%  |
| OpenBSD     | 52       | 10.1%   |
| MyBee       | 19       | 3.69%   |
| NetBSD      | 11       | 2.14%   |
| GhostBSD    | 6        | 1.17%   |
| NomadBSD    | 4        | 0.78%   |
| ClonOS      | 4        | 0.78%   |
| Ting        | 3        | 0.58%   |
| pfSense     | 2        | 0.39%   |
| XigmaNAS    | 1        | 0.19%   |
| TrueNAS     | 1        | 0.19%   |
| PC-BSD      | 1        | 0.19%   |
| FuryBSD     | 1        | 0.19%   |
| DragonFly   | 1        | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 448      | 90.14%  |
| arm64   | 26       | 5.23%   |
| i386    | 15       | 3.02%   |
| macppc  | 2        | 0.4%    |
| arm     | 2        | 0.4%    |
| sparc64 | 1        | 0.2%    |
| powerpc | 1        | 0.2%    |
| evbarm  | 1        | 0.2%    |
| armv7   | 1        | 0.2%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 252      | 49.12%  |
| helloDesktop | 131      | 25.54%  |
| KDE5         | 29       | 5.65%   |
| XFCE         | 25       | 4.87%   |
| fvwm         | 19       | 3.7%    |
| MATE         | 15       | 2.92%   |
| TWM          | 12       | 2.34%   |
| Openbox      | 10       | 1.95%   |
| GNOME        | 7        | 1.36%   |
| Fluxbox      | 6        | 1.17%   |
| X-Cinnamon   | 1        | 0.19%   |
| plasma       | 1        | 0.19%   |
| KWin         | 1        | 0.19%   |
| DWM          | 1        | 0.19%   |
| Budgie       | 1        | 0.19%   |
| AwesomeWM    | 1        | 0.19%   |
| akonadi_newm | 1        | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 262      | 52.4%   |
| X11     | 237      | 47.4%   |
| Wayland | 1        | 0.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 330      | 65.48%  |
| SLiM    | 123      | 24.4%   |
| SDDM    | 27       | 5.36%   |
| LightDM | 15       | 2.98%   |
| XDM     | 5        | 0.99%   |
| GDM     | 4        | 0.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 202      | 38.92%  |
| en_US          | 117      | 22.54%  |
| ru_RU          | 113      | 21.77%  |
| C              | 62       | 11.95%  |
| fr_FR          | 13       | 2.5%    |
| ru             | 6        | 1.16%   |
| ru_RU.KOI8-R   | 3        | 0.58%   |
| fr             | 1        | 0.19%   |
| en_GB          | 1        | 0.19%   |
| cv_RU.US-ASCII | 1        | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 347      | 68.44%  |
| BIOS | 160      | 31.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Zfs     | 223      | 43.9%   |
| Ufs     | 171      | 33.66%  |
| Cd9660  | 60       | 11.81%  |
| Ffs     | 52       | 10.24%  |
| Nullfs  | 1        | 0.2%    |
| Hammer2 | 1        | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 416      | 83.7%   |
| MBR     | 77       | 15.49%  |
| Unknown | 4        | 0.8%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUSTek Computer                    | 108      | 21.82%  |
| Gigabyte Technology                 | 91       | 18.38%  |
| Unknown                             | 74       | 14.95%  |
| ASRock                              | 49       | 9.9%    |
| MSI                                 | 30       | 6.06%   |
| Intel                               | 19       | 3.84%   |
| Hewlett-Packard                     | 11       | 2.22%   |
| Supermicro                          | 10       | 2.02%   |
| Lenovo                              | 10       | 2.02%   |
| Techvision                          | 9        | 1.82%   |
| Huanan                              | 8        | 1.62%   |
| Pegatron                            | 7        | 1.41%   |
| Dell                                | 7        | 1.41%   |
| Acer                                | 6        | 1.21%   |
| PC Engines                          | 4        | 0.81%   |
| Radxa                               | 3        | 0.61%   |
| Fujitsu                             | 3        | 0.61%   |
| Foxconn                             | 3        | 0.61%   |
| TONK                                | 2        | 0.4%    |
| Shuttle                             | 2        | 0.4%    |
| ECS                                 | 2        | 0.4%    |
| AZW                                 | 2        | 0.4%    |
| YANYU                               | 1        | 0.2%    |
| Wistron                             | 1        | 0.2%    |
| VIA Technologies                    | 1        | 0.2%    |
| Sun                                 | 1        | 0.2%    |
| Stonesoft                           | 1        | 0.2%    |
| Soyo                                | 1        | 0.2%    |
| Sony                                | 1        | 0.2%    |
| Shenzhen suqiao computer technology | 1        | 0.2%    |
| Seeed Studio                        | 1        | 0.2%    |
| RDW Computers                       | 1        | 0.2%    |
| QIYIDA                              | 1        | 0.2%    |
| NITRINOnet                          | 1        | 0.2%    |
| MW                                  | 1        | 0.2%    |
| Maxtang                             | 1        | 0.2%    |
| MAXSUN                              | 1        | 0.2%    |
| MACHINIST                           | 1        | 0.2%    |
| Kraftway                            | 1        | 0.2%    |
| Kontron                             | 1        | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                  | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 75       | 15.15%  |
| ASUS All Series                                                       | 13       | 2.63%   |
| Techvision TVI7309X                                                   | 9        | 1.82%   |
| PC Engines APU2                                                       | 4        | 0.81%   |
| Gigabyte C1037UN-EU                                                   | 4        | 0.81%   |
| MSI MS-7D46                                                           | 3        | 0.61%   |
| Huanan X99-QD4 V1.0                                                   | 3        | 0.61%   |
| Gigabyte H61M-S2PV                                                    | 3        | 0.61%   |
| Gigabyte H61M-DS2                                                     | 3        | 0.61%   |
| Supermicro SYS-6028R-TRT                                              | 2        | 0.4%    |
| Supermicro SSG-6029P-E1CR12L                                          | 2        | 0.4%    |
| Shuttle DS20U                                                         | 2        | 0.4%    |
| Pegatron SAISHIAT2                                                    | 2        | 0.4%    |
| MSI MS-7C96                                                           | 2        | 0.4%    |
| MSI MS-7B89                                                           | 2        | 0.4%    |
| MSI MS-7817                                                           | 2        | 0.4%    |
| Intel X79 V2.72A                                                      | 2        | 0.4%    |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 2        | 0.4%    |
| HP ProLiant MicroServer                                               | 2        | 0.4%    |
| Gigabyte Z68XP-UD3                                                    | 2        | 0.4%    |
| Gigabyte Z370P D3                                                     | 2        | 0.4%    |
| Gigabyte M68MT-S2P                                                    | 2        | 0.4%    |
| Gigabyte H81M-S2PV                                                    | 2        | 0.4%    |
| Gigabyte H310M S2 2.0                                                 | 2        | 0.4%    |
| Gigabyte GA-IMB370TN                                                  | 2        | 0.4%    |
| Gigabyte B550M DS3H                                                   | 2        | 0.4%    |
| Gigabyte B450 AORUS M                                                 | 2        | 0.4%    |
| Gigabyte A320M-H                                                      | 2        | 0.4%    |
| Dell OptiPlex 7040                                                    | 2        | 0.4%    |
| AZW U59                                                               | 2        | 0.4%    |
| ASUS PRIME Z590-P                                                     | 2        | 0.4%    |
| ASUS PRIME X370-PRO                                                   | 2        | 0.4%    |
| ASUS P8Z77-V LX                                                       | 2        | 0.4%    |
| ASUS P6T SE                                                           | 2        | 0.4%    |
| ASUS P5G41T-M LX3                                                     | 2        | 0.4%    |
| ASUS P4P800-VM                                                        | 2        | 0.4%    |
| ASUS M5A97 R2.0                                                       | 2        | 0.4%    |
| ASRock Z690 PG Riptide                                                | 2        | 0.4%    |
| ASRock X570S PG Riptide                                               | 2        | 0.4%    |
| ASRock J4205-ITX                                                      | 2        | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 75       | 15.15%  |
| ASUS PRIME                   | 17       | 3.43%   |
| ASUS All                     | 13       | 2.63%   |
| Techvision TVI7309X          | 9        | 1.82%   |
| Lenovo ThinkCentre           | 6        | 1.21%   |
| ASUS ROG                     | 6        | 1.21%   |
| Gigabyte B450M               | 5        | 1.01%   |
| Dell OptiPlex                | 5        | 1.01%   |
| PC Engines APU2              | 4        | 0.81%   |
| HP ProLiant                  | 4        | 0.81%   |
| HP Compaq                    | 4        | 0.81%   |
| Gigabyte C1037UN-EU          | 4        | 0.81%   |
| ASUS TUF                     | 4        | 0.81%   |
| MSI MS-7D46                  | 3        | 0.61%   |
| Huanan X99-QD4               | 3        | 0.61%   |
| Gigabyte H61M-S2PV           | 3        | 0.61%   |
| Gigabyte H61M-DS2            | 3        | 0.61%   |
| ASUS P8Z77-V                 | 3        | 0.61%   |
| ASUS P5Q                     | 3        | 0.61%   |
| ASUS P5G41T-M                | 3        | 0.61%   |
| ASUS M5A97                   | 3        | 0.61%   |
| ASRock Z690                  | 3        | 0.61%   |
| ASRock X570                  | 3        | 0.61%   |
| ASRock B550                  | 3        | 0.61%   |
| Acer Aspire                  | 3        | 0.61%   |
| Supermicro SYS-6028R-TRT     | 2        | 0.4%    |
| Supermicro SSG-6029P-E1CR12L | 2        | 0.4%    |
| Shuttle DS20U                | 2        | 0.4%    |
| Pegatron SAISHIAT2           | 2        | 0.4%    |
| MSI MS-7C96                  | 2        | 0.4%    |
| MSI MS-7B89                  | 2        | 0.4%    |
| MSI MS-7817                  | 2        | 0.4%    |
| Intel X79                    | 2        | 0.4%    |
| Huanan X99-F8D               | 2        | 0.4%    |
| Huanan X79                   | 2        | 0.4%    |
| HP ProDesk                   | 2        | 0.4%    |
| Gigabyte Z68XP-UD3           | 2        | 0.4%    |
| Gigabyte Z370P               | 2        | 0.4%    |
| Gigabyte M68MT-S2P           | 2        | 0.4%    |
| Gigabyte H81M-S2PV           | 2        | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2022    | 48       | 9.7%    |
| 2018    | 45       | 9.09%   |
| 2021    | 37       | 7.47%   |
| 2019    | 36       | 7.27%   |
| 2013    | 33       | 6.67%   |
| 2011    | 31       | 6.26%   |
| Unknown | 30       | 6.06%   |
| 2012    | 29       | 5.86%   |
| 2010    | 28       | 5.66%   |
| 2020    | 25       | 5.05%   |
| 2023    | 21       | 4.24%   |
| 2009    | 20       | 4.04%   |
| 2017    | 19       | 3.84%   |
| 2016    | 18       | 3.64%   |
| 2014    | 18       | 3.64%   |
| 2008    | 14       | 2.83%   |
| 2007    | 13       | 2.63%   |
| 2015    | 10       | 2.02%   |
| 2024    | 6        | 1.21%   |
| 2006    | 6        | 1.21%   |
| 2005    | 5        | 1.01%   |
| 2004    | 3        | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 495      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 491      | 99.19%  |
| Yes  | 4        | 0.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 123      | 24.4%   |
| 16.01-24.0      | 114      | 22.62%  |
| 4.01-8.0        | 102      | 20.24%  |
| 32.01-64.0      | 54       | 10.71%  |
| 2.01-3.0        | 34       | 6.75%   |
| 64.01-256.0     | 24       | 4.76%   |
| 3.01-4.0        | 21       | 4.17%   |
| 0.51-1.0        | 12       | 2.38%   |
| 24.01-32.0      | 9        | 1.79%   |
| 0.01-0.5        | 5        | 0.99%   |
| 1.01-2.0        | 4        | 0.79%   |
| More than 256.0 | 2        | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 247      | 47.96%  |
| 0.51-1.0    | 134      | 26.02%  |
| 1.01-2.0    | 69       | 13.4%   |
| 2.01-3.0    | 12       | 2.33%   |
| 4.01-8.0    | 11       | 2.14%   |
| Unknown     | 11       | 2.14%   |
| 3.01-4.0    | 10       | 1.94%   |
| 8.01-16.0   | 8        | 1.55%   |
| 0           | 6        | 1.17%   |
| 16.01-24.0  | 4        | 0.78%   |
| 24.01-32.0  | 2        | 0.39%   |
| 64.01-256.0 | 1        | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 234      | 44.66%  |
| 2      | 109      | 20.8%   |
| 0      | 60       | 11.45%  |
| 3      | 50       | 9.54%   |
| 4      | 35       | 6.68%   |
| 5      | 19       | 3.63%   |
| 6      | 6        | 1.15%   |
| 7      | 4        | 0.76%   |
| 9      | 2        | 0.38%   |
| 19     | 1        | 0.19%   |
| 14     | 1        | 0.19%   |
| 11     | 1        | 0.19%   |
| 10     | 1        | 0.19%   |
| 8      | 1        | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 426      | 85.03%  |
| Yes       | 75       | 14.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 473      | 95.56%  |
| No        | 22       | 4.44%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 378      | 75.75%  |
| Yes       | 121      | 24.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 430      | 86.35%  |
| Yes       | 68       | 13.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 495      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 149      | 29.16%  |
| St Petersburg     | 59       | 11.55%  |
| Krasnodar         | 23       | 4.5%    |
| Yekaterinburg     | 16       | 3.13%   |
| Chelyabinsk       | 15       | 2.94%   |
| Novosibirsk       | 12       | 2.35%   |
| Voronezh          | 9        | 1.76%   |
| Vladivostok       | 8        | 1.57%   |
| Ozersk            | 8        | 1.57%   |
| Barnaul           | 8        | 1.57%   |
| Stavropol         | 7        | 1.37%   |
| Omsk              | 7        | 1.37%   |
| Kamensk-Ural'skiy | 7        | 1.37%   |
| Surgut            | 6        | 1.17%   |
| Saratov           | 6        | 1.17%   |
| Ufa               | 5        | 0.98%   |
| Podolsk           | 5        | 0.98%   |
| Perm              | 5        | 0.98%   |
| Krasnoyarsk       | 5        | 0.98%   |
| Kirov             | 5        | 0.98%   |
| Cherepovets       | 5        | 0.98%   |
| Volgograd         | 4        | 0.78%   |
| Penza             | 4        | 0.78%   |
| Orenburg          | 4        | 0.78%   |
| Nizhniy Novgorod  | 4        | 0.78%   |
| Lipetsk           | 4        | 0.78%   |
| Khabarovsk        | 4        | 0.78%   |
| Tambov            | 3        | 0.59%   |
| Khimki            | 3        | 0.59%   |
| Irkutsk           | 3        | 0.59%   |
| Zhukovskiy        | 2        | 0.39%   |
| Volzhskiy         | 2        | 0.39%   |
| Vladimir          | 2        | 0.39%   |
| Vidnoye           | 2        | 0.39%   |
| Ulyanovsk         | 2        | 0.39%   |
| Ulan-Ude          | 2        | 0.39%   |
| Smolensk          | 2        | 0.39%   |
| Sertolovo         | 2        | 0.39%   |
| Samara            | 2        | 0.39%   |
| Rostov-on-Don     | 2        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 137      | 232    | 19.66%  |
| Seagate             | 129      | 292    | 18.51%  |
| Samsung Electronics | 74       | 109    | 10.62%  |
| Kingston            | 50       | 67     | 7.17%   |
| Toshiba             | 38       | 86     | 5.45%   |
| Hitachi             | 25       | 66     | 3.59%   |
| Intel               | 22       | 39     | 3.16%   |
| Crucial             | 16       | 23     | 2.3%    |
| A-DATA Technology   | 15       | 20     | 2.15%   |
| SPCC                | 10       | 11     | 1.43%   |
| HGST                | 10       | 23     | 1.43%   |
| Apacer              | 10       | 14     | 1.43%   |
| Silicon Motion      | 9        | 14     | 1.29%   |
| KingSpec            | 9        | 12     | 1.29%   |
| AMD                 | 9        | 10     | 1.29%   |
| Smartbuy            | 8        | 11     | 1.15%   |
| Plextor             | 8        | 11     | 1.15%   |
| SanDisk             | 7        | 8      | 1%      |
| Patriot             | 7        | 7      | 1%      |
| Netac               | 7        | 11     | 1%      |
| Maxtor              | 7        | 7      | 1%      |
| OCZ                 | 6        | 6      | 0.86%   |
| Micron Technology   | 6        | 11     | 0.86%   |
| Transcend           | 5        | 5      | 0.72%   |
| OPENBSD             | 5        | 12     | 0.72%   |
| Gigabyte Technology | 5        | 5      | 0.72%   |
| Kston               | 4        | 4      | 0.57%   |
| Hewlett-Packard     | 4        | 7      | 0.57%   |
| China               | 4        | 4      | 0.57%   |
| Team                | 3        | 3      | 0.43%   |
| Hoodisk             | 3        | 5      | 0.43%   |
| Fujitsu             | 3        | 4      | 0.43%   |
| XrayDisk            | 2        | 2      | 0.29%   |
| XPG                 | 2        | 2      | 0.29%   |
| Verbatim            | 2        | 2      | 0.29%   |
| NVMe                | 2        | 7      | 0.29%   |
| MSI                 | 2        | 5      | 0.29%   |
| GOODRAM             | 2        | 2      | 0.29%   |
| FORESEE             | 2        | 2      | 0.29%   |
| XUNZHE              | 1        | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB     | 9        | 1.12%   |
| Toshiba DT01ACA100 1TB             | 8        | 1%      |
| Kingston SA400S37240G 240GB        | 8        | 1%      |
| WDC WDS240G2G0A-00JH30 240GB       | 6        | 0.75%   |
| WDC WDS120G2G0A-00JH30 120GB       | 6        | 0.75%   |
| WDC WD20EARX-00PASB0 2TB           | 5        | 0.62%   |
| Toshiba HDWD110 1TB                | 5        | 0.62%   |
| Seagate ST250DM000-1BD141 250GB    | 5        | 0.62%   |
| Samsung SSD 860 EVO 500GB          | 5        | 0.62%   |
| Samsung SSD 860 EVO 250GB          | 5        | 0.62%   |
| OPENBSD SR RAID 1 128GB            | 5        | 0.62%   |
| AMD R5SL120G 120GB                 | 5        | 0.62%   |
| A-DATA SU650 120GB                 | 5        | 0.62%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 4        | 0.5%    |
| Toshiba DT01ACA050 500GB           | 4        | 0.5%    |
| SPCC Solid State Disk 128GB        | 4        | 0.5%    |
| Seagate ST500DM002-1BD142 500GB    | 4        | 0.5%    |
| Seagate ST3300657SS 304GB          | 4        | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4        | 0.5%    |
| Samsung SSD 970 EVO Plus 500GB     | 4        | 0.5%    |
| Samsung SSD 970 EVO Plus 250GB     | 4        | 0.5%    |
| Samsung SSD 870 EVO 500GB          | 4        | 0.5%    |
| Netac SSD 256GB                    | 4        | 0.5%    |
| Kston SSD 128GB                    | 4        | 0.5%    |
| Kingston SA400S37120G 120GB        | 4        | 0.5%    |
| Intel SSDSC2BW480H6 480GB          | 4        | 0.5%    |
| WDC WDS500G1B0A-00H9H0 500GB       | 3        | 0.37%   |
| WDC WD800AAJS-00PSA0 80GB          | 3        | 0.37%   |
| WDC WD6400AARS-00Y5B1 640GB        | 3        | 0.37%   |
| WDC WD5000AZLX-00K2TA0 500GB       | 3        | 0.37%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 3        | 0.37%   |
| WDC WD5000AAKS-00V1A0 500GB        | 3        | 0.37%   |
| WDC WD10JFCX-68N6GN0 1TB           | 3        | 0.37%   |
| WDC WD10EZRX-00A8LB0 1TB           | 3        | 0.37%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3        | 0.37%   |
| Smartbuy SSD 64GB                  | 3        | 0.37%   |
| Silicon Motion NE-256 256GB        | 3        | 0.37%   |
| Seagate ST4000VN008-2DR166 4TB     | 3        | 0.37%   |
| Seagate ST380815AS 80GB            | 3        | 0.37%   |
| Seagate ST3500413AS 500GB          | 3        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 129      | 292    | 36.34%  |
| WDC                                | 119      | 202    | 33.52%  |
| Toshiba                            | 36       | 84     | 10.14%  |
| Hitachi                            | 25       | 66     | 7.04%   |
| Samsung Electronics                | 12       | 18     | 3.38%   |
| HGST                               | 10       | 23     | 2.82%   |
| Maxtor                             | 7        | 7      | 1.97%   |
| OPENBSD                            | 5        | 12     | 1.41%   |
| Fujitsu                            | 3        | 4      | 0.85%   |
| NVMe                               | 2        | 7      | 0.56%   |
| Hewlett-Packard                    | 2        | 5      | 0.56%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.28%   |
| MaxDigital                         | 1        | 1      | 0.28%   |
| LSILOGIC                           | 1        | 1      | 0.28%   |
| JetFlash                           | 1        | 1      | 0.28%   |
| IBM                                | 1        | 1      | 0.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 43       | 56     | 15.81%  |
| Kingston            | 38       | 50     | 13.97%  |
| WDC                 | 19       | 24     | 6.99%   |
| Intel               | 15       | 26     | 5.51%   |
| Crucial             | 14       | 20     | 5.15%   |
| A-DATA Technology   | 11       | 14     | 4.04%   |
| SPCC                | 9        | 10     | 3.31%   |
| KingSpec            | 9        | 12     | 3.31%   |
| Smartbuy            | 8        | 11     | 2.94%   |
| Plextor             | 8        | 11     | 2.94%   |
| Apacer              | 8        | 10     | 2.94%   |
| SanDisk             | 7        | 8      | 2.57%   |
| AMD                 | 7        | 8      | 2.57%   |
| Patriot             | 6        | 6      | 2.21%   |
| OCZ                 | 6        | 6      | 2.21%   |
| Netac               | 6        | 10     | 2.21%   |
| Micron Technology   | 6        | 11     | 2.21%   |
| Transcend           | 5        | 5      | 1.84%   |
| Kston               | 4        | 4      | 1.47%   |
| China               | 4        | 4      | 1.47%   |
| Team                | 3        | 3      | 1.1%    |
| Hoodisk             | 3        | 5      | 1.1%    |
| Verbatim            | 2        | 2      | 0.74%   |
| Toshiba             | 2        | 2      | 0.74%   |
| Hewlett-Packard     | 2        | 2      | 0.74%   |
| Gigabyte Technology | 2        | 2      | 0.74%   |
| XUNZHE              | 1        | 1      | 0.37%   |
| XrayDisk            | 1        | 1      | 0.37%   |
| XPG                 | 1        | 1      | 0.37%   |
| walram              | 1        | 1      | 0.37%   |
| TAMMUZ              | 1        | 1      | 0.37%   |
| SETHRISE            | 1        | 1      | 0.37%   |
| SATADOM             | 1        | 1      | 0.37%   |
| Qumo                | 1        | 1      | 0.37%   |
| Palit               | 1        | 1      | 0.37%   |
| MSI                 | 1        | 4      | 0.37%   |
| LuminouTek          | 1        | 2      | 0.37%   |
| LITEON              | 1        | 1      | 0.37%   |
| KingDian            | 1        | 3      | 0.37%   |
| Kingchuxing         | 1        | 1      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 270      | 725    | 46.39%  |
| SSD  | 237      | 354    | 40.72%  |
| NVMe | 75       | 116    | 12.89%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 409      | 1079   | 84.5%   |
| NVMe | 75       | 116    | 15.5%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 341      | 577    | 62.34%  |
| 0.51-1.0   | 114      | 216    | 20.84%  |
| 1.01-2.0   | 44       | 151    | 8.04%   |
| 3.01-4.0   | 23       | 54     | 4.2%    |
| 4.01-10.0  | 13       | 30     | 2.38%   |
| 2.01-3.0   | 10       | 26     | 1.83%   |
| 10.01-20.0 | 2        | 25     | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 150      | 28.52%  |
| 1-20           | 105      | 19.96%  |
| 251-500        | 91       | 17.3%   |
| 51-100         | 57       | 10.84%  |
| 21-50          | 42       | 7.98%   |
| 501-1000       | 40       | 7.6%    |
| More than 3000 | 17       | 3.23%   |
| 1001-2000      | 15       | 2.85%   |
| 2001-3000      | 5        | 0.95%   |
| Unknown        | 4        | 0.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 422      | 82.42%  |
| 21-50          | 40       | 7.81%   |
| 101-250        | 11       | 2.15%   |
| 51-100         | 11       | 2.15%   |
| More than 3000 | 7        | 1.37%   |
| 501-1000       | 7        | 1.37%   |
| 2001-3000      | 4        | 0.78%   |
| 1001-2000      | 4        | 0.78%   |
| Unknown        | 4        | 0.78%   |
| 251-500        | 2        | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Intel SSDSC2BW480H6 480GB           | 4        | 4      | 2.9%    |
| WDC WD5000AAKS-00V1A0 500GB         | 3        | 3      | 2.17%   |
| Samsung Electronics SSD 870 EVO 1TB | 3        | 8      | 2.17%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2        | 2      | 1.45%   |
| WDC WD5003AZEX-00MK2A0 500GB        | 2        | 2      | 1.45%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2        | 2      | 1.45%   |
| WDC WD3200AAKX-001CA0 320GB         | 2        | 2      | 1.45%   |
| WDC WD15EARS-00Z5B1 1.5TB           | 2        | 2      | 1.45%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 2        | 2      | 1.45%   |
| Toshiba MK3259GSXP 320GB            | 2        | 2      | 1.45%   |
| Seagate ST500LT012-9WS142 500GB     | 2        | 2      | 1.45%   |
| Seagate ST3500413AS 500GB           | 2        | 4      | 1.45%   |
| Seagate ST3320418AS 320GB           | 2        | 2      | 1.45%   |
| Seagate ST3250410AS 250GB           | 2        | 2      | 1.45%   |
| Seagate ST250DM000-1BD141 250GB     | 2        | 4      | 1.45%   |
| Seagate ST2000DM001-9YN164 2TB      | 2        | 2      | 1.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2        | 2      | 1.45%   |
| Samsung Electronics HD161HJ 160GB   | 2        | 3      | 1.45%   |
| Maxtor STM3320613AS 320GB           | 2        | 2      | 1.45%   |
| Kingston SA400S37120G 120GB         | 2        | 2      | 1.45%   |
| Hitachi HDS721010CLA332 1TB         | 2        | 4      | 1.45%   |
| XPG SX950U 240GB                    | 1        | 1      | 0.72%   |
| WDC WD800AAJS-00TDA0 80GB           | 1        | 1      | 0.72%   |
| WDC WD7501AALS-00E8B0 752GB         | 1        | 1      | 0.72%   |
| WDC WD7500AACS-00ZJB0 752GB         | 1        | 1      | 0.72%   |
| WDC WD60EFRX-68MYMN1 6TB            | 1        | 1      | 0.72%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1        | 2      | 0.72%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1        | 1      | 0.72%   |
| WDC WD5000AZRZ-00HTKB0 500GB        | 1        | 1      | 0.72%   |
| WDC WD5000AZLX-00CL5A0 500GB        | 1        | 1      | 0.72%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 1      | 0.72%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1        | 1      | 0.72%   |
| WDC WD5000AADS-56S9B0 500GB         | 1        | 1      | 0.72%   |
| WDC WD5000AADS-00S9B0 500GB         | 1        | 1      | 0.72%   |
| WDC WD40EFRX-68N32N0 4TB            | 1        | 3      | 0.72%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1        | 1      | 0.72%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1        | 1      | 0.72%   |
| WDC WD3200AAKS-00L9A0 320GB         | 1        | 1      | 0.72%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 1        | 1      | 0.72%   |
| WDC WD20NMVW-11W68S0 2TB            | 1        | 2      | 0.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 37       | 51     | 28.46%  |
| Seagate             | 36       | 52     | 27.69%  |
| Samsung Electronics | 11       | 18     | 8.46%   |
| Hitachi             | 8        | 14     | 6.15%   |
| Kingston            | 7        | 7      | 5.38%   |
| Intel               | 7        | 7      | 5.38%   |
| Toshiba             | 5        | 7      | 3.85%   |
| Maxtor              | 4        | 4      | 3.08%   |
| SPCC                | 2        | 2      | 1.54%   |
| Plextor             | 2        | 2      | 1.54%   |
| HGST                | 2        | 2      | 1.54%   |
| XPG                 | 1        | 1      | 0.77%   |
| Transcend           | 1        | 1      | 0.77%   |
| Micron Technology   | 1        | 2      | 0.77%   |
| Hewlett-Packard     | 1        | 1      | 0.77%   |
| GLOWAY              | 1        | 2      | 0.77%   |
| GK                  | 1        | 1      | 0.77%   |
| Crucial             | 1        | 1      | 0.77%   |
| AMD                 | 1        | 2      | 0.77%   |
| A-DATA Technology   | 1        | 1      | 0.77%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 36       | 52     | 37.5%   |
| WDC                 | 35       | 49     | 36.46%  |
| Hitachi             | 8        | 14     | 8.33%   |
| Toshiba             | 5        | 7      | 5.21%   |
| Samsung Electronics | 5        | 7      | 5.21%   |
| Maxtor              | 4        | 4      | 4.17%   |
| HGST                | 2        | 2      | 2.08%   |
| Hewlett-Packard     | 1        | 1      | 1.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 94       | 136    | 74.02%  |
| SSD  | 32       | 41     | 25.2%   |
| NVMe | 1        | 1      | 0.79%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                | Desktops | Drives | Percent |
|--------------------------------------|----------|--------|---------|
| WDC WD7501AALS-00J7B0 752GB          | 1        | 1      | 16.67%  |
| WDC WD6400AARS-00Y5B1 640GB          | 1        | 2      | 16.67%  |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1        | 1      | 16.67%  |
| Toshiba MG05ACA800E 8TB              | 1        | 1      | 16.67%  |
| Hitachi HDS721010DLE630 1TB          | 1        | 1      | 16.67%  |
| Crucial M4-CT256M4SSD1 256GB         | 1        | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 4      | 50%     |
| Toshiba | 1        | 1      | 16.67%  |
| Hitachi | 1        | 1      | 16.67%  |
| Crucial | 1        | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 364      | 937    | 68.81%  |
| Malfunc  | 123      | 178    | 23.25%  |
| Detected | 36       | 73     | 6.81%   |
| Failed   | 6        | 7      | 1.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel                                   | 345      | 53.41%  |
| AMD                                     | 94       | 14.55%  |
| Samsung Electronics                     | 29       | 4.49%   |
| Silicon Motion                          | 24       | 3.72%   |
| Marvell Technology Group                | 19       | 2.94%   |
| JMicron Technology                      | 17       | 2.63%   |
| ASMedia Technology                      | 15       | 2.32%   |
| Nvidia                                  | 13       | 2.01%   |
| Kingston Technology Company             | 13       | 2.01%   |
| Broadcom / LSI                          | 10       | 1.55%   |
| Phison Electronics                      | 9        | 1.39%   |
| Sandisk                                 | 8        | 1.24%   |
| ADATA Technology                        | 8        | 1.24%   |
| Realtek Semiconductor                   | 6        | 0.93%   |
| MAXIO Technology (Hangzhou)             | 4        | 0.62%   |
| Areca Technology                        | 4        | 0.62%   |
| VIA Technologies                        | 3        | 0.46%   |
| Micron/Crucial Technology               | 3        | 0.46%   |
| Yangtze Memory Technologies             | 2        | 0.31%   |
| Toshiba                                 | 2        | 0.31%   |
| SK hynix                                | 2        | 0.31%   |
| Silicon Image                           | 2        | 0.31%   |
| Shenzhen Longsys Electronics            | 2        | 0.31%   |
| Netac Technology                        | 2        | 0.31%   |
| Lite-On IT Corp. / Plextor              | 2        | 0.31%   |
| Integrated Technology Express           | 2        | 0.31%   |
| Silicon Integrated Systems [SiS]        | 1        | 0.15%   |
| Shenzhen Unionmemory Information System | 1        | 0.15%   |
| Lite-On Technology                      | 1        | 0.15%   |
| KIOXIA                                  | 1        | 0.15%   |
| 3ware                                   | 1        | 0.15%   |
| Unknown                                 | 1        | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 42       | 5.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 26       | 3.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25       | 3.27%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 24       | 3.14%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 21       | 2.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 21       | 2.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 21       | 2.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 19       | 2.49%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19       | 2.49%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 18       | 2.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 17       | 2.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 16       | 2.09%   |
| AMD 400 Series Chipset SATA Controller                                                  | 15       | 1.96%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 14       | 1.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 14       | 1.83%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 14       | 1.83%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 13       | 1.7%    |
| AMD 500 Series Chipset SATA Controller                                                  | 13       | 1.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 11       | 1.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 11       | 1.44%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 10       | 1.31%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 10       | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10       | 1.31%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 9        | 1.18%   |
| Intel Alder Lake-N SATA AHCI Controller                                                 | 9        | 1.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 8        | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 8        | 1.05%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 8        | 1.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8        | 1.05%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 7        | 0.92%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 0.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6        | 0.79%   |
| Intel SSD 660P Series                                                                   | 6        | 0.79%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 6        | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 0.79%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 0.79%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 5        | 0.65%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 5        | 0.65%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 5        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 369      | 59.52%  |
| NVMe | 121      | 19.52%  |
| IDE  | 109      | 17.58%  |
| RAID | 9        | 1.45%   |
| SCSI | 7        | 1.13%   |
| SAS  | 5        | 0.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 354      | 71.08%  |
| AMD     | 108      | 21.69%  |
| ARM     | 27       | 5.42%   |
| Unknown | 6        | 1.2%    |
| VIA     | 1        | 0.2%    |
| PowerPC | 1        | 0.2%    |
| 7447A   | 1        | 0.2%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| ARM Cortex-A55 r2p0                    | 14       | 2.77%   |
| Intel Celeron N5105 @ 2.00GHz          | 11       | 2.18%   |
| Intel N100                             | 9        | 1.78%   |
| Intel Celeron CPU J1900 @ 1.99GHz      | 6        | 1.19%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 6        | 1.19%   |
| AMD Ryzen 5 3600 6-Core Processor      | 6        | 1.19%   |
|                                        | 6        | 1.19%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz  | 5        | 0.99%   |
| Intel Celeron J4125 CPU @ 2.00GHz      | 5        | 0.99%   |
| Intel Celeron CPU J1800 @ 2.41GHz      | 5        | 0.99%   |
| Intel Celeron CPU 1037U @ 1.80GHz      | 5        | 0.99%   |
| ARM Cortex-A57 r1p3                    | 5        | 0.99%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 4        | 0.79%   |
| Intel Core i5-7400 CPU @ 3.00GHz       | 4        | 0.79%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 4        | 0.79%   |
| Intel Core i5-10400 CPU @ 2.90GHz      | 4        | 0.79%   |
| Intel Celeron N5100 @ 1.10GHz          | 4        | 0.79%   |
| AMD GX-412TC SOC                       | 4        | 0.79%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz   | 3        | 0.59%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz | 3        | 0.59%   |
| Intel Pentium CPU G3220 @ 3.00GHz      | 3        | 0.59%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 3        | 0.59%   |
| Intel Core i3-6100 CPU @ 3.70GHz       | 3        | 0.59%   |
| Intel Core i3-3220 CPU @ 3.30GHz       | 3        | 0.59%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz   | 3        | 0.59%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz   | 3        | 0.59%   |
| Intel Core 2 Duo CPU                   | 3        | 0.59%   |
| Intel Celeron CPU J3455 @ 1.50GHz      | 3        | 0.59%   |
| Intel 12th Gen Core i5-12400           | 3        | 0.59%   |
| Intel 12th Gen Core i3-12100           | 3        | 0.59%   |
| ARM Cortex-A53 r0p4                    | 3        | 0.59%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 3        | 0.59%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 3        | 0.59%   |
| AMD Ryzen 5 1600 Six-Core Processor    | 3        | 0.59%   |
| AMD FX-6300 Six-Core Processor         | 3        | 0.59%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz    | 2        | 0.4%    |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz    | 2        | 0.4%    |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz    | 2        | 0.4%    |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz    | 2        | 0.4%    |
| Intel Xeon CPU E31270 @ 3.40GHz        | 2        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 69       | 13.8%   |
| Intel Core i5           | 53       | 10.6%   |
| Intel Xeon              | 41       | 8.2%    |
| Intel Core i3           | 38       | 7.6%    |
| Other                   | 31       | 6.2%    |
| Intel Core i7           | 30       | 6%      |
| ARM Cortex              | 27       | 5.4%    |
| AMD Ryzen 5             | 25       | 5%      |
| Intel Core 2 Duo        | 18       | 3.6%    |
| Intel Pentium           | 17       | 3.4%    |
| Intel Atom              | 16       | 3.2%    |
| Intel Core 2 Quad       | 13       | 2.6%    |
| AMD Ryzen 7             | 13       | 2.6%    |
| AMD FX                  | 9        | 1.8%    |
| Intel Pentium 4         | 7        | 1.4%    |
| AMD Ryzen 9             | 6        | 1.2%    |
| AMD Phenom II X4        | 6        | 1.2%    |
| Intel Pentium Gold      | 5        | 1%      |
| AMD Ryzen 3             | 5        | 1%      |
| AMD GX                  | 5        | 1%      |
| Intel Pentium Dual-Core | 4        | 0.8%    |
| AMD Athlon 64 X2        | 4        | 0.8%    |
| Intel Pentium Dual      | 3        | 0.6%    |
| Intel Pentium D         | 3        | 0.6%    |
| Intel Genuine           | 3        | 0.6%    |
| Intel Core i9           | 3        | 0.6%    |
| Intel Core 2            | 3        | 0.6%    |
| AMD Phenom II X6        | 3        | 0.6%    |
| AMD E                   | 3        | 0.6%    |
| AMD Athlon II X3        | 3        | 0.6%    |
| AMD A4                  | 3        | 0.6%    |
| AMD A10                 | 3        | 0.6%    |
| Intel Xeon Bronze       | 2        | 0.4%    |
| Intel Pentium Silver    | 2        | 0.4%    |
| Intel Celeron D         | 2        | 0.4%    |
| Intel 686-class         | 2        | 0.4%    |
| AMD Turion II Neo       | 2        | 0.4%    |
| AMD Sempron             | 2        | 0.4%    |
| AMD Ryzen 5 PRO         | 2        | 0.4%    |
| AMD Phenom              | 2        | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 172      | 34.4%   |
| 2       | 113      | 22.6%   |
| Unknown | 75       | 15%     |
| 6       | 47       | 9.4%    |
| 8       | 24       | 4.8%    |
| 12      | 22       | 4.4%    |
| 1       | 16       | 3.2%    |
| 16      | 14       | 2.8%    |
| 24      | 5        | 1%      |
| 14      | 3        | 0.6%    |
| 32      | 2        | 0.4%    |
| 28      | 2        | 0.4%    |
| 3       | 2        | 0.4%    |
| 20      | 1        | 0.2%    |
| 18      | 1        | 0.2%    |
| 10      | 1        | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 445      | 89.36%  |
| Unknown | 43       | 8.63%   |
| 2       | 10       | 2.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 275      | 54.89%  |
| 2       | 141      | 28.14%  |
| Unknown | 85       | 16.97%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 83       | 16.63%  |
| KabyLake      | 47       | 9.42%   |
| SandyBridge   | 35       | 7.01%   |
| Haswell       | 35       | 7.01%   |
| IvyBridge     | 31       | 6.21%   |
| Penryn        | 30       | 6.01%   |
| Zen 2         | 19       | 3.81%   |
| Silvermont    | 19       | 3.81%   |
| K10           | 19       | 3.81%   |
| Core          | 19       | 3.81%   |
| Skylake       | 17       | 3.41%   |
| Zen 3         | 16       | 3.21%   |
| CometLake     | 13       | 2.61%   |
| NetBurst      | 12       | 2.4%    |
| Bonnell       | 12       | 2.4%    |
| Piledriver    | 11       | 2.2%    |
| Goldmont      | 11       | 2.2%    |
| Zen           | 9        | 1.8%    |
| Nehalem       | 9        | 1.8%    |
| Zen+          | 8        | 1.6%    |
| Goldmont plus | 8        | 1.6%    |
| K8 Hammer     | 7        | 1.4%    |
| Broadwell     | 7        | 1.4%    |
| Westmere      | 4        | 0.8%    |
| Puma          | 4        | 0.8%    |
| Bulldozer     | 4        | 0.8%    |
| Bobcat        | 3        | 0.6%    |
| Steamroller   | 2        | 0.4%    |
| Jaguar        | 2        | 0.4%    |
| TigerLake     | 1        | 0.2%    |
| P6            | 1        | 0.2%    |
| Geode         | 1        | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 222      | 47.13%  |
| Nvidia                                       | 131      | 27.81%  |
| AMD                                          | 99       | 21.02%  |
| ASPEED Technology                            | 11       | 2.34%   |
| Matrox Electronics Systems                   | 4        | 0.85%   |
| VIA Technologies                             | 2        | 0.42%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.21%   |
| Cirrus Logic                                 | 1        | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel JasperLake [UHD Graphics]                                                          | 15       | 3.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14       | 2.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14       | 2.89%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 14       | 2.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 13       | 2.69%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 11       | 2.27%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11       | 2.27%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 11       | 2.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 10       | 2.07%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 10       | 2.07%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10       | 2.07%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 9        | 1.86%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 8        | 1.65%   |
| Intel HD Graphics 530                                                                    | 8        | 1.65%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 8        | 1.65%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 7        | 1.45%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 6        | 1.24%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6        | 1.24%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 6        | 1.24%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6        | 1.24%   |
| Nvidia GT218 [GeForce 210]                                                               | 5        | 1.03%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5        | 1.03%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 5        | 1.03%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 5        | 1.03%   |
| Intel HD Graphics 630                                                                    | 5        | 1.03%   |
| Intel HD Graphics 500                                                                    | 5        | 1.03%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 5        | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 1.03%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5        | 1.03%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5        | 1.03%   |
| AMD ES1000                                                                               | 5        | 1.03%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 4        | 0.83%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 4        | 0.83%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 4        | 0.83%   |
| Intel 82865G Integrated Graphics Controller                                              | 4        | 0.83%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 4        | 0.83%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 3        | 0.62%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 3        | 0.62%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 3        | 0.62%   |
| Intel UHD Graphics 620                                                                   | 3        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Intel                | 201      | 40.36%  |
| 1 x Nvidia               | 122      | 24.5%   |
| 1 x AMD                  | 85       | 17.07%  |
| Other                    | 41       | 8.23%   |
| 1 x ASPEED               | 11       | 2.21%   |
| 2 x Intel                | 10       | 2.01%   |
| 2 x AMD                  | 8        | 1.61%   |
| Intel + Nvidia           | 5        | 1%      |
| Intel + AMD              | 5        | 1%      |
| 1 x Matrox               | 3        | 0.6%    |
| 1 x VIA                  | 2        | 0.4%    |
| 1 x XGI                  | 1        | 0.2%    |
| Nvidia + Matrox          | 1        | 0.2%    |
| Intel + AMD + 1 x Nvidia | 1        | 0.2%    |
| 1 x Cirrus Logic         | 1        | 0.2%    |
| AMD + Nvidia             | 1        | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 373      | 74.45%  |
| Proprietary | 76       | 15.17%  |
| Unknown     | 52       | 10.38%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 384      | 76.8%   |
| 1.01-2.0   | 26       | 5.2%    |
| 3.01-4.0   | 24       | 4.8%    |
| 0.51-1.0   | 24       | 4.8%    |
| 0.01-0.5   | 16       | 3.2%    |
| 7.01-8.0   | 12       | 2.4%    |
| 5.01-6.0   | 8        | 1.6%    |
| 8.01-16.0  | 4        | 0.8%    |
| 2.01-3.0   | 2        | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 41       | 21.47%  |
| Goldstar             | 25       | 13.09%  |
| Dell                 | 16       | 8.38%   |
| Philips              | 13       | 6.81%   |
| ViewSonic            | 12       | 6.28%   |
| BenQ                 | 12       | 6.28%   |
| Acer                 | 12       | 6.28%   |
| Ancor Communications | 11       | 5.76%   |
| AOC                  | 10       | 5.24%   |
| NEC Computers        | 7        | 3.66%   |
| Hewlett-Packard      | 5        | 2.62%   |
| Sony                 | 4        | 2.09%   |
| LG Electronics       | 4        | 2.09%   |
| RTK                  | 3        | 1.57%   |
| Iiyama               | 2        | 1.05%   |
| Fujitsu Siemens      | 2        | 1.05%   |
| Unknown (CDD)        | 1        | 0.52%   |
| RGT                  | 1        | 0.52%   |
| Panasonic            | 1        | 0.52%   |
| Microstep            | 1        | 0.52%   |
| Mi                   | 1        | 0.52%   |
| Lenovo               | 1        | 0.52%   |
| IPS                  | 1        | 0.52%   |
| InfoVision           | 1        | 0.52%   |
| Gigabyte Technology  | 1        | 0.52%   |
| Daewoo               | 1        | 0.52%   |
| CHO                  | 1        | 0.52%   |
| Unknown              | 1        | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch   | 4        | 1.99%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch   | 3        | 1.49%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch          | 2        | 1%      |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch            | 2        | 1%      |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 2        | 1%      |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch    | 2        | 1%      |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch     | 2        | 1%      |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 2        | 1%      |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 2        | 1%      |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2        | 1%      |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 2        | 1%      |
| Philips 170S PHL0839 1280x1024 340x270mm 17.1-inch                     | 2        | 1%      |
| NEC Computers FE791SB NEC61D7 1600x1200 330x240mm 16.1-inch            | 2        | 1%      |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                    | 2        | 1%      |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 2        | 1%      |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2        | 1%      |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                  | 2        | 1%      |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                      | 2        | 1%      |
| AOC Q27P1B AOC2701 2560x1440 600x340mm 27.2-inch                       | 2        | 1%      |
| AOC 2270W AOC2270 1920x1080 480x270mm 21.7-inch                        | 2        | 1%      |
| Ancor Communications ASUS VS239 ACI23D2 1920x1080 510x290mm 23.1-inch  | 2        | 1%      |
| Acer QG241Y ACR079C 1920x1080 520x320mm 24.0-inch                      | 2        | 1%      |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch             | 1        | 0.5%    |
| ViewSonic VP171s-2 VSC4B1B 1280x1024 340x270mm 17.1-inch               | 1        | 0.5%    |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch          | 1        | 0.5%    |
| ViewSonic VA2710-FHD VSCA736 1920x1080 600x340mm 27.2-inch             | 1        | 0.5%    |
| ViewSonic VA2418-FHD VSCD739 1920x1080 530x300mm 24.0-inch             | 1        | 0.5%    |
| ViewSonic LCD Monitor VX2451 SERIES 1920x1080                          | 1        | 0.5%    |
| ViewSonic LCD Monitor VSC8724 1440x900 410x260mm 19.1-inch             | 1        | 0.5%    |
| ViewSonic LCD Monitor VSC5826 1366x768 410x230mm 18.5-inch             | 1        | 0.5%    |
| ViewSonic LCD Monitor VSC2528 1920x1080 520x290mm 23.4-inch            | 1        | 0.5%    |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch               | 1        | 0.5%    |
| Sony TV  *00 SNY8204 3840x2160 1220x680mm 55.0-inch                    | 1        | 0.5%    |
| Sony TV  *00 SNY7C04 3840x2160 1080x610mm 48.8-inch                    | 1        | 0.5%    |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch                | 1        | 0.5%    |
| Sony SDM-E76D SNYB200 1280x1024 340x270mm 17.1-inch                    | 1        | 0.5%    |
| Samsung Electronics U32R59x SAM0F94 3840x2160 700x390mm 31.5-inch      | 1        | 0.5%    |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 700x390mm 31.5-inch      | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM05FB 1920x1080 510x290mm 23.1-inch   | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch   | 1        | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 86       | 45.74%  |
| 1280x1024 (SXGA)   | 30       | 15.96%  |
| 3840x2160 (4K)     | 15       | 7.98%   |
| 2560x1440 (QHD)    | 11       | 5.85%   |
| 1680x1050 (WSXGA+) | 9        | 4.79%   |
| 1440x900 (WXGA+)   | 9        | 4.79%   |
| 1920x1200 (WUXGA)  | 8        | 4.26%   |
| 1600x900 (HD+)     | 7        | 3.72%   |
| 1366x768 (WXGA)    | 6        | 3.19%   |
| 1600x1200          | 2        | 1.06%   |
| Unknown            | 2        | 1.06%   |
| 3440x1440          | 1        | 0.53%   |
| 2560x1080          | 1        | 0.53%   |
| 1024x768 (XGA)     | 1        | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 27       | 14.06%  |
| 21      | 26       | 13.54%  |
| 19      | 23       | 11.98%  |
| 27      | 20       | 10.42%  |
| 23      | 20       | 10.42%  |
| Unknown | 20       | 10.42%  |
| 17      | 18       | 9.38%   |
| 18      | 6        | 3.13%   |
| 22      | 5        | 2.6%    |
| 20      | 5        | 2.6%    |
| 31      | 4        | 2.08%   |
| 15      | 3        | 1.56%   |
| 52      | 2        | 1.04%   |
| 50      | 2        | 1.04%   |
| 16      | 2        | 1.04%   |
| 57      | 1        | 0.52%   |
| 55      | 1        | 0.52%   |
| 48      | 1        | 0.52%   |
| 46      | 1        | 0.52%   |
| 34      | 1        | 0.52%   |
| 32      | 1        | 0.52%   |
| 26      | 1        | 0.52%   |
| 14      | 1        | 0.52%   |
| 12      | 1        | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 66       | 34.74%  |
| 401-500     | 54       | 28.42%  |
| 301-350     | 23       | 12.11%  |
| Unknown     | 20       | 10.53%  |
| 351-400     | 10       | 5.26%   |
| 1001-1500   | 8        | 4.21%   |
| 601-700     | 5        | 2.63%   |
| 701-800     | 2        | 1.05%   |
| 201-300     | 2        | 1.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 111      | 59.36%  |
| 16/10   | 27       | 14.44%  |
| 5/4     | 26       | 13.9%   |
| Unknown | 18       | 9.63%   |
| 4/3     | 3        | 1.6%    |
| 6/5     | 1        | 0.53%   |
| 21/9    | 1        | 0.53%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 68       | 35.42%  |
| 151-200        | 30       | 15.63%  |
| 141-150        | 23       | 11.98%  |
| 301-350        | 21       | 10.94%  |
| Unknown        | 20       | 10.42%  |
| 251-300        | 9        | 4.69%   |
| More than 1000 | 7        | 3.65%   |
| 351-500        | 6        | 3.13%   |
| 101-110        | 4        | 2.08%   |
| 121-130        | 2        | 1.04%   |
| 61-70          | 1        | 0.52%   |
| 501-1000       | 1        | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 117      | 61.58%  |
| 101-120 | 30       | 15.79%  |
| Unknown | 20       | 10.53%  |
| 121-160 | 12       | 6.32%   |
| 161-240 | 6        | 3.16%   |
| 1-50    | 5        | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 309      | 61.31%  |
| 1     | 181      | 35.91%  |
| 2     | 13       | 2.58%   |
| 3     | 1        | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 297      | 45.41%  |
| Intel                             | 194      | 29.66%  |
| Qualcomm Atheros                  | 55       | 8.41%   |
| Broadcom                          | 19       | 2.91%   |
| D-Link System                     | 11       | 1.68%   |
| Marvell Technology Group          | 9        | 1.38%   |
| VIA Technologies                  | 8        | 1.22%   |
| Huawei Technologies               | 6        | 0.92%   |
| Samsung Electronics               | 4        | 0.61%   |
| Ralink Technology                 | 4        | 0.61%   |
| Ralink                            | 4        | 0.61%   |
| 3Com                              | 4        | 0.61%   |
| TP-Link                           | 3        | 0.46%   |
| IMC Networks                      | 3        | 0.46%   |
| Aquantia                          | 3        | 0.46%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.31%   |
| Qualcomm Atheros Communications   | 2        | 0.31%   |
| Qualcomm                          | 2        | 0.31%   |
| QinHeng Electronics               | 2        | 0.31%   |
| Mellanox Technologies             | 2        | 0.31%   |
| MediaTek                          | 2        | 0.31%   |
| D-Link                            | 2        | 0.31%   |
| Atmel                             | 2        | 0.31%   |
| ZyXEL Communications              | 1        | 0.15%   |
| Tehuti Networks                   | 1        | 0.15%   |
| Sundance Technology Inc / IC Plus | 1        | 0.15%   |
| STMicroelectronics                | 1        | 0.15%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.15%   |
| Qcom                              | 1        | 0.15%   |
| OPPO Electronics                  | 1        | 0.15%   |
| Nvidia                            | 1        | 0.15%   |
| MYRICOM                           | 1        | 0.15%   |
| Mercucys                          | 1        | 0.15%   |
| Edimax Technology                 | 1        | 0.15%   |
| ASUSTek Computer                  | 1        | 0.15%   |
| Apple                             | 1        | 0.15%   |
| Accton Technology                 | 1        | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 237      | 31.43%  |
| Intel I211 Gigabit Network Connection                                         | 25       | 3.32%   |
| Realtek RTL8125 2.5GbE Controller                                             | 22       | 2.92%   |
| Intel 82574L Gigabit Network Connection                                       | 22       | 2.92%   |
| Intel Ethernet Controller I226-V                                              | 21       | 2.79%   |
| Intel Ethernet Controller I225-V                                              | 20       | 2.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 14       | 1.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 11       | 1.46%   |
| Intel I210 Gigabit Network Connection                                         | 10       | 1.33%   |
| Intel I350 Gigabit Network Connection                                         | 9        | 1.19%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9        | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 8        | 1.06%   |
| Intel Ethernet Connection (2) I219-V                                          | 8        | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 7        | 0.93%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 6        | 0.8%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 6        | 0.8%    |
| Intel Ethernet Connection (17) I219-V                                         | 6        | 0.8%    |
| Intel 82579V Gigabit Network Connection                                       | 6        | 0.8%    |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 5        | 0.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5        | 0.66%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 5        | 0.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 5        | 0.66%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 5        | 0.66%   |
| Intel Wi-Fi 6 AX200                                                           | 5        | 0.66%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 5        | 0.66%   |
| Intel Ethernet Connection I217-V                                              | 5        | 0.66%   |
| Intel Ethernet Connection (7) I219-V                                          | 5        | 0.66%   |
| Intel 82583V Gigabit Network Connection                                       | 5        | 0.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 0.66%   |
| Intel 82576 Gigabit Network Connection                                        | 5        | 0.66%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 5        | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 4        | 0.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4        | 0.53%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 4        | 0.53%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 4        | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 4        | 0.53%   |
| Intel Wireless 7265                                                           | 4        | 0.53%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4        | 0.53%   |
| Realtek USB 2.5GbE Controller                                                 | 3        | 0.4%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 3        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 35       | 27.56%  |
| Intel                           | 33       | 25.98%  |
| Qualcomm Atheros                | 29       | 22.83%  |
| Broadcom                        | 6        | 4.72%   |
| Ralink Technology               | 4        | 3.15%   |
| Ralink                          | 4        | 3.15%   |
| TP-Link                         | 3        | 2.36%   |
| IMC Networks                    | 3        | 2.36%   |
| Qualcomm Atheros Communications | 2        | 1.57%   |
| MediaTek                        | 2        | 1.57%   |
| D-Link                          | 2        | 1.57%   |
| Qcom                            | 1        | 0.79%   |
| Mercucys                        | 1        | 0.79%   |
| Edimax Technology               | 1        | 0.79%   |
| ASUSTek Computer                | 1        | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 7        | 5.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 5        | 3.91%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 5        | 3.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 5        | 3.91%   |
| Intel Wi-Fi 6 AX200                                                         | 5        | 3.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 4        | 3.13%   |
| Intel Wireless 7265                                                         | 4        | 3.13%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                 | 3        | 2.34%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                    | 3        | 2.34%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 3        | 2.34%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                      | 3        | 2.34%   |
| Realtek Bluetooth Adapter                                                   | 3        | 2.34%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                   | 3        | 2.34%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 3        | 2.34%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                | 3        | 2.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2        | 1.56%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                             | 2        | 1.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2        | 1.56%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 2        | 1.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2        | 1.56%   |
| Ralink MT7601U Wireless Adapter                                             | 2        | 1.56%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                        | 2        | 1.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2        | 1.56%   |
| Intel Wireless 8265 / 8275                                                  | 2        | 1.56%   |
| Intel Wi-Fi 6 AX201 160MHz                                                  | 2        | 1.56%   |
| Intel CNVi: Wi-Fi                                                           | 2        | 1.56%   |
| Intel Centrino Wireless-N 2230                                              | 2        | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 2        | 1.56%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 2        | 1.56%   |
| TP-Link Wireless USB Adapter                                                | 1        | 0.78%   |
| TP-Link Wireless MU-MIMO USB Adapter                                        | 1        | 0.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                | 1        | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 1        | 0.78%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                     | 1        | 0.78%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                      | 1        | 0.78%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 1        | 0.78%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                | 1        | 0.78%   |
| Realtek 802.11n WLAN Adapter                                                | 1        | 0.78%   |
| Ralink RT5370 Wireless Adapter                                              | 1        | 0.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                                       | 1        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 286      | 51.16%  |
| Intel                             | 180      | 32.2%   |
| Qualcomm Atheros                  | 27       | 4.83%   |
| Broadcom                          | 13       | 2.33%   |
| D-Link System                     | 11       | 1.97%   |
| Marvell Technology Group          | 9        | 1.61%   |
| VIA Technologies                  | 8        | 1.43%   |
| Samsung Electronics               | 4        | 0.72%   |
| 3Com                              | 4        | 0.72%   |
| Aquantia                          | 3        | 0.54%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.36%   |
| Qualcomm                          | 2        | 0.36%   |
| Huawei Technologies               | 2        | 0.36%   |
| Tehuti Networks                   | 1        | 0.18%   |
| Sundance Technology Inc / IC Plus | 1        | 0.18%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.18%   |
| OPPO Electronics                  | 1        | 0.18%   |
| Nvidia                            | 1        | 0.18%   |
| MYRICOM                           | 1        | 0.18%   |
| Apple                             | 1        | 0.18%   |
| Accton Technology                 | 1        | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 237      | 38.6%   |
| Intel I211 Gigabit Network Connection                                         | 25       | 4.07%   |
| Realtek RTL8125 2.5GbE Controller                                             | 22       | 3.58%   |
| Intel 82574L Gigabit Network Connection                                       | 22       | 3.58%   |
| Intel Ethernet Controller I226-V                                              | 21       | 3.42%   |
| Intel Ethernet Controller I225-V                                              | 20       | 3.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 14       | 2.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 11       | 1.79%   |
| Intel I210 Gigabit Network Connection                                         | 10       | 1.63%   |
| Intel I350 Gigabit Network Connection                                         | 9        | 1.47%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9        | 1.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 8        | 1.3%    |
| Intel Ethernet Connection (2) I219-V                                          | 8        | 1.3%    |
| VIA VT6105/VT6106S [Rhine-III]                                                | 6        | 0.98%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 6        | 0.98%   |
| Intel Ethernet Connection (17) I219-V                                         | 6        | 0.98%   |
| Intel 82579V Gigabit Network Connection                                       | 6        | 0.98%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 5        | 0.81%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 5        | 0.81%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 5        | 0.81%   |
| Intel Ethernet Connection I217-V                                              | 5        | 0.81%   |
| Intel Ethernet Connection (7) I219-V                                          | 5        | 0.81%   |
| Intel 82583V Gigabit Network Connection                                       | 5        | 0.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 0.81%   |
| Intel 82576 Gigabit Network Connection                                        | 5        | 0.81%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 5        | 0.81%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4        | 0.65%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 4        | 0.65%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 4        | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 4        | 0.65%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4        | 0.65%   |
| Realtek USB 2.5GbE Controller                                                 | 3        | 0.49%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 3        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 0.49%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3        | 0.49%   |
| Intel 82562EZ 10/100 Ethernet Controller                                      | 3        | 0.49%   |
| Intel 82540EM Gigabit Ethernet Controller                                     | 3        | 0.49%   |
| D-Link System DGE-530T Gigabit Ethernet Adapter (rev 11)                      | 3        | 0.49%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 3        | 0.49%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                       | 3        | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 473      | 78.18%  |
| WiFi     | 121      | 20%     |
| Unknown  | 7        | 1.16%   |
| Modem    | 4        | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 421      | 92.94%  |
| WiFi     | 31       | 6.84%   |
| Unknown  | 1        | 0.22%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 217      | 42.72%  |
| 2     | 126      | 24.8%   |
| 3     | 54       | 10.63%  |
| 0     | 41       | 8.07%   |
| 4     | 35       | 6.89%   |
| 6     | 13       | 2.56%   |
| 5     | 10       | 1.97%   |
| 9     | 5        | 0.98%   |
| 7     | 4        | 0.79%   |
| 8     | 2        | 0.39%   |
| 12    | 1        | 0.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 480      | 95.62%  |
| Yes  | 22       | 4.38%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 31       | 44.29%  |
| Realtek Semiconductor           | 8        | 11.43%  |
| Cambridge Silicon Radio         | 8        | 11.43%  |
| IMC Networks                    | 5        | 7.14%   |
| Qualcomm Atheros Communications | 4        | 5.71%   |
| ASUSTek Computer                | 3        | 4.29%   |
| Apple                           | 3        | 4.29%   |
| Foxconn / Hon Hai               | 2        | 2.86%   |
| Silicon Wave                    | 1        | 1.43%   |
| Ralink                          | 1        | 1.43%   |
| MediaTek                        | 1        | 1.43%   |
| Lite-On Technology              | 1        | 1.43%   |
| Edimax Technology               | 1        | 1.43%   |
| Broadcom                        | 1        | 1.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 9        | 12.68%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 8        | 11.27%  |
| Realtek Bluetooth Adapter                                   | 7        | 9.86%   |
| Intel AX200 Bluetooth                                       | 6        | 8.45%   |
| Intel AX201 Bluetooth                                       | 4        | 5.63%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3        | 4.23%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 3        | 4.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3        | 4.23%   |
| Intel AX210 Bluetooth                                       | 3        | 4.23%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 3        | 4.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2        | 2.82%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 2        | 2.82%   |
| Apple Bluetooth Host Controller                             | 2        | 2.82%   |
| Silicon Wave Bluetooth Wireless Adapter                     | 1        | 1.41%   |
| Realtek Bluetooth 4.0 Adapter                               | 1        | 1.41%   |
| Ralink RT3290 Bluetooth                                     | 1        | 1.41%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 1.41%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1        | 1.41%   |
| MediaTek RZ608 Bluetooth Adapter                            | 1        | 1.41%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1        | 1.41%   |
| Intel AX211 Bluetooth                                       | 1        | 1.41%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1        | 1.41%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 1        | 1.41%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                   | 1        | 1.41%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1        | 1.41%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter     | 1        | 1.41%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter            | 1        | 1.41%   |
| ASUS Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter     | 1        | 1.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 1.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 291      | 51.23%  |
| AMD                                          | 109      | 19.19%  |
| Nvidia                                       | 106      | 18.66%  |
| C-Media Electronics                          | 7        | 1.23%   |
| Texas Instruments                            | 5        | 0.88%   |
| Realtek Semiconductor                        | 5        | 0.88%   |
| Zoran Co. Personal Media Division (Nogatech) | 4        | 0.7%    |
| VIA Technologies                             | 4        | 0.7%    |
| JMTek                                        | 4        | 0.7%    |
| Logitech                                     | 3        | 0.53%   |
| Creative Technology                          | 3        | 0.53%   |
| Creative Labs                                | 3        | 0.53%   |
| KTMicro                                      | 2        | 0.35%   |
| Focusrite-Novation                           | 2        | 0.35%   |
| Xilinx                                       | 1        | 0.18%   |
| Superlux digit                               | 1        | 0.18%   |
| SteelSeries ApS                              | 1        | 0.18%   |
| Sony                                         | 1        | 0.18%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.18%   |
| Samsung Electronics                          | 1        | 0.18%   |
| RME                                          | 1        | 0.18%   |
| Nordic Semiconductor ASA                     | 1        | 0.18%   |
| Microsoft                                    | 1        | 0.18%   |
| M-Audio                                      | 1        | 0.18%   |
| Huawei Technologies                          | 1        | 0.18%   |
| HECATE G2 GAMING HEADSET                     | 1        | 0.18%   |
| GN Netcom                                    | 1        | 0.18%   |
| Generalplus Technology                       | 1        | 0.18%   |
| FiiO Electronics Technology                  | 1        | 0.18%   |
| ESS Technology                               | 1        | 0.18%   |
| Ensoniq                                      | 1        | 0.18%   |
| Edifier Technology                           | 1        | 0.18%   |
| Cambridge Silicon Radio                      | 1        | 0.18%   |
| Unknown                                      | 1        | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 26       | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 26       | 4.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 24       | 3.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 23       | 3.61%   |
| AMD Starship/Matisse HD Audio Controller                                   | 21       | 3.3%    |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 21       | 3.3%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 19       | 2.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 17       | 2.67%   |
| Intel 200 Series PCH HD Audio                                              | 17       | 2.67%   |
| Intel Jasper Lake HD Audio                                                 | 15       | 2.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15       | 2.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 14       | 2.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 14       | 2.2%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 14       | 2.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 13       | 2.04%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 13       | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11       | 1.73%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10       | 1.57%   |
| Nvidia GK107 HDMI Audio Controller                                         | 10       | 1.57%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 10       | 1.57%   |
| AMD FCH Azalia Controller                                                  | 10       | 1.57%   |
| Intel Alder Lake-S HD Audio Controller                                     | 9        | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9        | 1.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9        | 1.41%   |
| Nvidia High Definition Audio Controller                                    | 8        | 1.26%   |
| Nvidia TU116 High Definition Audio Controller                              | 7        | 1.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7        | 1.1%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 7        | 1.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7        | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                              | 6        | 0.94%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6        | 0.94%   |
| Nvidia GP108 High Definition Audio Controller                              | 5        | 0.78%   |
| Intel Comet Lake PCH cAVS                                                  | 5        | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 5        | 0.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 0.78%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 0.78%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 4        | 0.63%   |
| Texas Instruments PCM2902 Audio Codec                                      | 4        | 0.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4        | 0.63%   |
| Nvidia MCP61 High Definition Audio                                         | 4        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Kingston                                | 101      | 21%     |
| Unknown                                 | 96       | 19.96%  |
| Samsung Electronics                     | 49       | 10.19%  |
| Crucial                                 | 34       | 7.07%   |
| Unknown                                 | 25       | 5.2%    |
| SK hynix                                | 23       | 4.78%   |
| Micron Technology                       | 20       | 4.16%   |
| Patriot                                 | 17       | 3.53%   |
| AMD                                     | 16       | 3.33%   |
| A-DATA Technology                       | 11       | 2.29%   |
| Corsair                                 | 10       | 2.08%   |
| G.Skill                                 | 8        | 1.66%   |
| Patriot Memory (PDP Systems)            | 7        | 1.46%   |
| Atermiter                               | 7        | 1.46%   |
| Ramaxel Technology                      | 5        | 1.04%   |
| Unknown (ABCD)                          | 4        | 0.83%   |
| Transcend                               | 4        | 0.83%   |
| Nanya Technology                        | 4        | 0.83%   |
| Kllisre                                 | 4        | 0.83%   |
| Apacer                                  | 4        | 0.83%   |
| Qumo                                    | 3        | 0.62%   |
| Netac                                   | 3        | 0.62%   |
| Goldkey                                 | 3        | 0.62%   |
| Unifosa                                 | 2        | 0.42%   |
| Silicon Power Computer & Communications | 2        | 0.42%   |
| Silicon Power                           | 2        | 0.42%   |
| Kingmax                                 | 2        | 0.42%   |
| Elpida                                  | 2        | 0.42%   |
| Unknown (0x0DD5)                        | 1        | 0.21%   |
| Tigo                                    | 1        | 0.21%   |
| Teikon                                  | 1        | 0.21%   |
| Team                                    | 1        | 0.21%   |
| S                                       | 1        | 0.21%   |
| Ramos Technology                        | 1        | 0.21%   |
| PDPSystems                              | 1        | 0.21%   |
| KINGBANK                                | 1        | 0.21%   |
| Innodisk                                | 1        | 0.21%   |
| H                                       | 1        | 0.21%   |
| GOODRAM                                 | 1        | 0.21%   |
| Foxline                                 | 1        | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 25       | 4.71%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 11       | 2.07%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 6        | 1.13%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 5        | 0.94%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 5        | 0.94%   |
| Unknown RAM Module 512MB DIMM SDRAM                            | 4        | 0.75%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 4        | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 4        | 0.75%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 4        | 0.75%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 3        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                       | 3        | 0.56%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s            | 3        | 0.56%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s           | 3        | 0.56%   |
| G.Skill RAM F4-4000C18-32GVK 32GB DIMM DDR4 4000MT/s           | 3        | 0.56%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s          | 3        | 0.56%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s          | 3        | 0.56%   |
| AMD RAM R748G2400U2S 8GB DIMM DDR4 2400MT/s                    | 3        | 0.56%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3200MT/s                    | 3        | 0.56%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3400MT/s                    | 3        | 0.56%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                        | 2        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 2        | 0.38%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                      | 2        | 0.38%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 2        | 0.38%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 2        | 0.38%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                     | 2        | 0.38%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                       | 2        | 0.38%   |
| Unknown RAM Module 1GB DIMM DDR2 400MT/s                       | 2        | 0.38%   |
| Unknown RAM Module 1GB DIMM 1333MT/s                           | 2        | 0.38%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 2        | 0.38%   |
| Transcend RAM JM2666HLE-32G 32GB DIMM DDR4 2666MT/s            | 2        | 0.38%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s           | 2        | 0.38%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 2        | 0.38%   |
| Silicon Power & RAM Module 8GB DIMM DDR4 3200MT/s              | 2        | 0.38%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s          | 2        | 0.38%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2        | 0.38%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB SODIMM DDR5 4800MT/s        | 2        | 0.38%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s           | 2        | 0.38%   |
| Samsung RAM M393A2K40BB2-CTD 16GB DIMM DDR4 2667MT/s           | 2        | 0.38%   |
| Patriot RAM PSD34G16002 4GB DIMM DDR3 1600MT/s                 | 2        | 0.38%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s             | 2        | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 171      | 40.52%  |
| DDR3    | 136      | 32.23%  |
| Unknown | 38       | 9%      |
| DDR2    | 29       | 6.87%   |
| SDRAM   | 21       | 4.98%   |
| DDR5    | 12       | 2.84%   |
| DDR     | 10       | 2.37%   |
| LPDDR4  | 4        | 0.95%   |
| LPDDR5  | 1        | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 347      | 82.23%  |
| SODIMM       | 74       | 17.54%  |
| Row Of Chips | 1        | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 130      | 27.78%  |
| 4096  | 104      | 22.22%  |
| 2048  | 88       | 18.8%   |
| 16384 | 68       | 14.53%  |
| 1024  | 34       | 7.26%   |
| 32768 | 28       | 5.98%   |
| 512   | 13       | 2.78%   |
| 49152 | 1        | 0.21%   |
| 256   | 1        | 0.21%   |
| 8     | 1        | 0.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 70       | 15.73%  |
| 1333    | 70       | 15.73%  |
| 3200    | 59       | 13.26%  |
| 2400    | 49       | 11.01%  |
| 2667    | 35       | 7.87%   |
| 800     | 28       | 6.29%   |
| Unknown | 22       | 4.94%   |
| 2133    | 19       | 4.27%   |
| 667     | 16       | 3.6%    |
| 400     | 9        | 2.02%   |
| 1066    | 8        | 1.8%    |
| 4800    | 7        | 1.57%   |
| 2666    | 7        | 1.57%   |
| 1067    | 6        | 1.35%   |
| 5600    | 4        | 0.9%    |
| 533     | 4        | 0.9%    |
| 4000    | 3        | 0.67%   |
| 3600    | 3        | 0.67%   |
| 3400    | 3        | 0.67%   |
| 3000    | 3        | 0.67%   |
| 2933    | 3        | 0.67%   |
| 1866    | 3        | 0.67%   |
| 1867    | 2        | 0.45%   |
| 1400    | 2        | 0.45%   |
| 6400    | 1        | 0.22%   |
| 5200    | 1        | 0.22%   |
| 3733    | 1        | 0.22%   |
| 2048    | 1        | 0.22%   |
| 1334    | 1        | 0.22%   |
| 1332    | 1        | 0.22%   |
| 933     | 1        | 0.22%   |
| 333     | 1        | 0.22%   |
| 266     | 1        | 0.22%   |
| 133     | 1        | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Seiko Epson         | 1        | 20%     |
| Samsung Electronics | 1        | 20%     |
| Kyocera             | 1        | 20%     |
| Hewlett-Packard     | 1        | 20%     |
| Brother Industries  | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed) | 1        | 20%     |
| Samsung ML-2010P Mono Laser Printer   | 1        | 20%     |
| Kyocera FS-1025MFP                    | 1        | 20%     |
| HP Laser 107a Printer                 | 1        | 20%     |
| Brother HL-2030 Laser Printer         | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 50%     |
| Canon       | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seiko Epson ES-H7200 [GT-20000] | 1        | 50%     |
| Canon CanoScan N1240U/LiDE 30   | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 5        | 22.73%  |
| Microdia                      | 3        | 13.64%  |
| Z-Star Microelectronics       | 2        | 9.09%   |
| Arkmicro Technologies         | 2        | 9.09%   |
| Sunplus Innovation Technology | 1        | 4.55%   |
| Silicon Motion                | 1        | 4.55%   |
| Ricoh                         | 1        | 4.55%   |
| Realtek Semiconductor         | 1        | 4.55%   |
| Pixart Imaging                | 1        | 4.55%   |
| Huawei Technologies           | 1        | 4.55%   |
| GEMBIRD                       | 1        | 4.55%   |
| Chicony Electronics           | 1        | 4.55%   |
| Aveo Technology               | 1        | 4.55%   |
| A4Tech                        | 1        | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Logitech Webcam C270                | 3        | 13.64%  |
| Z-Star Venus USB2.0 Camera          | 1        | 4.55%   |
| Z-Star Integrated Camera            | 1        | 4.55%   |
| Sunplus 2-USB 2.0 Camera            | 1        | 4.55%   |
| Silicon Motion 300k Pixel Camera    | 1        | 4.55%   |
| Ricoh USB2.0 Camera                 | 1        | 4.55%   |
| Realtek USB Video Device            | 1        | 4.55%   |
| Pixart Imaging PAC731x Trust Webcam | 1        | 4.55%   |
| Microdia Webcam Vitade AF           | 1        | 4.55%   |
| Microdia USB 2.0 Camera             | 1        | 4.55%   |
| Microdia ASUS USB 2.0 Webcam        | 1        | 4.55%   |
| Logitech Webcam C170                | 1        | 4.55%   |
| Logitech C505 HD Webcam             | 1        | 4.55%   |
| Huawei HiCamera                     | 1        | 4.55%   |
| GEMBIRD USB2.0 PC CAMERA            | 1        | 4.55%   |
| Chicony USB2.0 VGA UVC WebCam       | 1        | 4.55%   |
| Aveo Camera                         | 1        | 4.55%   |
| Arkmicro Webcam Carrefour           | 1        | 4.55%   |
| Arkmicro USB 2.0 PC CAMERA          | 1        | 4.55%   |
| A4Tech A4tech FHD 1080P PC Camera   | 1        | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Validity Sensors  | 1        | 50%     |
| FocalTech Systems | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 50%     |
| FocalTech Systems Fingerprint Reader         | 1        | 50%     |

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
| 0     | 217      | 42.72%  |
| 1     | 216      | 42.52%  |
| 2     | 61       | 12.01%  |
| 3     | 11       | 2.17%   |
| 4     | 3        | 0.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 231      | 66%     |
| Net/wireless             | 39       | 11.14%  |
| Sound                    | 20       | 5.71%   |
| Bluetooth                | 17       | 4.86%   |
| Firewire controller      | 13       | 3.71%   |
| Net/ethernet             | 12       | 3.43%   |
| Graphics card            | 5        | 1.43%   |
| Network                  | 4        | 1.14%   |
| Card reader              | 4        | 1.14%   |
| Storage/ata              | 3        | 0.86%   |
| Storage                  | 1        | 0.29%   |
| Fingerprint reader       | 1        | 0.29%   |

