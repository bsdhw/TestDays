BSD in Brazil - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Brazil.

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

Total: 281

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Intel         | BOX-J41L4A V3.01            | [dd8cccddff](https://bsd-hardware.info/?probe=dd8cccddff) | Dec 29, 2023 |
| Intel         | BOX-J41L4A V3.01            | [9294250e89](https://bsd-hardware.info/?probe=9294250e89) | Dec 29, 2023 |
| Intel         | DQ77KB AAG81483-501         | [bf5cb7eb21](https://bsd-hardware.info/?probe=bf5cb7eb21) | Dec 29, 2023 |
| Dell          | 04YP6J A00                  | [9ed1a43f79](https://bsd-hardware.info/?probe=9ed1a43f79) | Dec 29, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [fa4e90491b](https://bsd-hardware.info/?probe=fa4e90491b) | Dec 29, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [1c769a311c](https://bsd-hardware.info/?probe=1c769a311c) | Dec 29, 2023 |
| ASRock        | J4005B-ITX                  | [8ad375a02f](https://bsd-hardware.info/?probe=8ad375a02f) | Dec 26, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [491c854348](https://bsd-hardware.info/?probe=491c854348) | Dec 25, 2023 |
| ASRock        | J4005B-ITX                  | [2ffc965b2e](https://bsd-hardware.info/?probe=2ffc965b2e) | Dec 14, 2023 |
| Unknown       | Unknown                     | [0bc43bd220](https://bsd-hardware.info/?probe=0bc43bd220) | Dec 14, 2023 |
| Unknown       | Unknown                     | [79486fa5ff](https://bsd-hardware.info/?probe=79486fa5ff) | Dec 08, 2023 |
| Dell          | 0411GW A02                  | [f2bc8b79b0](https://bsd-hardware.info/?probe=f2bc8b79b0) | Dec 05, 2023 |
| Intel         | Geminilake                  | [59d13c77e8](https://bsd-hardware.info/?probe=59d13c77e8) | Dec 02, 2023 |
| Intel         | DQ77KB AAG81483-501         | [760a22c4b8](https://bsd-hardware.info/?probe=760a22c4b8) | Dec 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a9b3beae66](https://bsd-hardware.info/?probe=a9b3beae66) | Dec 02, 2023 |
| Intel         | DQ77KB AAG81483-501         | [972ad3cb48](https://bsd-hardware.info/?probe=972ad3cb48) | Dec 02, 2023 |
| ASUSTek       | PRIME A520M-E               | [8d7c03be2f](https://bsd-hardware.info/?probe=8d7c03be2f) | Nov 28, 2023 |
| HP            | 3646h                       | [b3083001a4](https://bsd-hardware.info/?probe=b3083001a4) | Nov 24, 2023 |
| Gigabyte      | B450M AORUS ELITE           | [e49d3f40b6](https://bsd-hardware.info/?probe=e49d3f40b6) | Nov 05, 2023 |
| Dell          | 08NPPY A00                  | [dfc8115b4a](https://bsd-hardware.info/?probe=dfc8115b4a) | Oct 24, 2023 |
| Intel         | DQ77KB AAG81483-501         | [81e77caff8](https://bsd-hardware.info/?probe=81e77caff8) | Oct 23, 2023 |
| ASUSTek       | A88XM-A                     | [a32967cbc5](https://bsd-hardware.info/?probe=a32967cbc5) | Sep 30, 2023 |
| Dell          | 0VRWRC A01                  | [6c85a42e64](https://bsd-hardware.info/?probe=6c85a42e64) | Sep 19, 2023 |
| Unknown       | Unknown                     | [50f509c032](https://bsd-hardware.info/?probe=50f509c032) | Sep 05, 2023 |
| Dell          | 0JCTF8 A00                  | [a2be5a5f0f](https://bsd-hardware.info/?probe=a2be5a5f0f) | Aug 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [e5cae16104](https://bsd-hardware.info/?probe=e5cae16104) | Aug 23, 2023 |
| MSI           | G31M3-L V2                  | [7335b3dea2](https://bsd-hardware.info/?probe=7335b3dea2) | Aug 22, 2023 |
| Daten Tecn... | DH110MXV                    | [bdd9c72e7c](https://bsd-hardware.info/?probe=bdd9c72e7c) | Aug 18, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | [f25db83457](https://bsd-hardware.info/?probe=f25db83457) | Aug 15, 2023 |
| Intel         | H81                         | [80f40918ce](https://bsd-hardware.info/?probe=80f40918ce) | Aug 07, 2023 |
| Unknown       | Unknown                     | [8b7315305c](https://bsd-hardware.info/?probe=8b7315305c) | Jul 31, 2023 |
| ChangWang     | CW56-58                     | [f418f5407c](https://bsd-hardware.info/?probe=f418f5407c) | Jul 30, 2023 |
| Dell          | 0GDG8Y A02                  | [651f6bf18f](https://bsd-hardware.info/?probe=651f6bf18f) | Jul 28, 2023 |
| Dell          | 0HD5W2 A01                  | [e26ef35879](https://bsd-hardware.info/?probe=e26ef35879) | Jul 28, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [1cd9d4cb7f](https://bsd-hardware.info/?probe=1cd9d4cb7f) | Jul 24, 2023 |
| Dell          | 0TD1J8 A00                  | [c99bc29ce0](https://bsd-hardware.info/?probe=c99bc29ce0) | Jul 24, 2023 |
| Intel         | H55                         | [11c9e5747f](https://bsd-hardware.info/?probe=11c9e5747f) | Jul 22, 2023 |
| Unknown       | Unknown                     | [8ced2a3a4d](https://bsd-hardware.info/?probe=8ced2a3a4d) | Jul 17, 2023 |
| Intel         | H55                         | [da217d0606](https://bsd-hardware.info/?probe=da217d0606) | Jul 13, 2023 |
| Unknown       | Unknown                     | [a9c88b1c80](https://bsd-hardware.info/?probe=a9c88b1c80) | Jul 11, 2023 |
| Intel         | Q3XXG4-P V1.0               | [c546c0a84f](https://bsd-hardware.info/?probe=c546c0a84f) | Jul 06, 2023 |
| Dell          | 02YRK5 A03                  | [2d631e9745](https://bsd-hardware.info/?probe=2d631e9745) | Jun 23, 2023 |
| Techvision    | TVI7309X B0                 | [b6e5a7e7bc](https://bsd-hardware.info/?probe=b6e5a7e7bc) | Jun 18, 2023 |
| Techvision    | TVI7309X B0                 | [2d50927445](https://bsd-hardware.info/?probe=2d50927445) | Jun 18, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | [4e827b2cbf](https://bsd-hardware.info/?probe=4e827b2cbf) | Jun 16, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | [3d71827388](https://bsd-hardware.info/?probe=3d71827388) | Jun 16, 2023 |
| Dell          | 053CWD A00                  | [7a5418ac7e](https://bsd-hardware.info/?probe=7a5418ac7e) | Jun 16, 2023 |
| CNCTION-IA... | Unknown                     | [1a0573767e](https://bsd-hardware.info/?probe=1a0573767e) | Jun 16, 2023 |
| Unknown       | Unknown                     | [93dcd13cb6](https://bsd-hardware.info/?probe=93dcd13cb6) | Jun 15, 2023 |
| Dell          | 0HD5W2 A01                  | [a6c6c43f64](https://bsd-hardware.info/?probe=a6c6c43f64) | Jun 13, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [ffe9b51f78](https://bsd-hardware.info/?probe=ffe9b51f78) | Jun 12, 2023 |
| Soyo          | SY-YL B550M                 | [1d1138e3c5](https://bsd-hardware.info/?probe=1d1138e3c5) | Jun 05, 2023 |
| Soyo          | SY-YL B550M                 | [79c6c2a177](https://bsd-hardware.info/?probe=79c6c2a177) | Jun 05, 2023 |
| YANYU         | N39SL                       | [e487646fbf](https://bsd-hardware.info/?probe=e487646fbf) | Jun 05, 2023 |
| Intel         | JSL MRD                     | [f4606f2c25](https://bsd-hardware.info/?probe=f4606f2c25) | Jun 03, 2023 |
| Intel         | JSL MRD                     | [3d5e12d1cf](https://bsd-hardware.info/?probe=3d5e12d1cf) | Jun 03, 2023 |
| Unknown       | Unknown                     | [13c80903b5](https://bsd-hardware.info/?probe=13c80903b5) | May 31, 2023 |
| Intel         | H81                         | [e0e15704fc](https://bsd-hardware.info/?probe=e0e15704fc) | May 29, 2023 |
| Dell          | 0GDG8Y A02                  | [fc6906c72a](https://bsd-hardware.info/?probe=fc6906c72a) | May 27, 2023 |
| Lenovo        | 36C5 SDK0L77767 WIN 3423... | [a19f434ae4](https://bsd-hardware.info/?probe=a19f434ae4) | May 26, 2023 |
| ASUSTek       | PRIME A520M-E               | [efd50a99b7](https://bsd-hardware.info/?probe=efd50a99b7) | May 23, 2023 |
| ASUSTek       | PRIME A520M-E               | [6e82e43784](https://bsd-hardware.info/?probe=6e82e43784) | May 23, 2023 |
| Unknown       | Unknown                     | [fe3f8769f8](https://bsd-hardware.info/?probe=fe3f8769f8) | May 22, 2023 |
| Unknown       | Unknown                     | [d8bec309da](https://bsd-hardware.info/?probe=d8bec309da) | May 16, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [2ce057e389](https://bsd-hardware.info/?probe=2ce057e389) | May 14, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [fa87f4741a](https://bsd-hardware.info/?probe=fa87f4741a) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [bd81294acc](https://bsd-hardware.info/?probe=bd81294acc) | May 13, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [cace71018f](https://bsd-hardware.info/?probe=cace71018f) | May 11, 2023 |
| Gigabyte      | H61M-DS2H                   | [e1856048c0](https://bsd-hardware.info/?probe=e1856048c0) | May 10, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [4353bb0195](https://bsd-hardware.info/?probe=4353bb0195) | May 09, 2023 |
| Unknown       | Unknown                     | [ed836ce6e5](https://bsd-hardware.info/?probe=ed836ce6e5) | May 05, 2023 |
| Unknown       | Unknown                     | [15c2e0790b](https://bsd-hardware.info/?probe=15c2e0790b) | Apr 27, 2023 |
| Intel         | Q3XXG4-P V1.0               | [b46f671e20](https://bsd-hardware.info/?probe=b46f671e20) | Apr 25, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [827308827b](https://bsd-hardware.info/?probe=827308827b) | Apr 24, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [a6141b809a](https://bsd-hardware.info/?probe=a6141b809a) | Apr 21, 2023 |
| Gigabyte      | H61M-S2PH                   | [024173445b](https://bsd-hardware.info/?probe=024173445b) | Apr 18, 2023 |
| Unknown       | Unknown                     | [cff3d92e32](https://bsd-hardware.info/?probe=cff3d92e32) | Apr 15, 2023 |
| Unknown       | Unknown                     | [6d44a8e8c8](https://bsd-hardware.info/?probe=6d44a8e8c8) | Apr 15, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [a149d0b4b5](https://bsd-hardware.info/?probe=a149d0b4b5) | Apr 10, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [ffbe23b7d8](https://bsd-hardware.info/?probe=ffbe23b7d8) | Apr 09, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [592e08cdd2](https://bsd-hardware.info/?probe=592e08cdd2) | Apr 09, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [c98356d42b](https://bsd-hardware.info/?probe=c98356d42b) | Apr 09, 2023 |
| Unknown       | Unknown                     | [4e1d6069e9](https://bsd-hardware.info/?probe=4e1d6069e9) | Apr 04, 2023 |
| Unknown       | Unknown                     | [9cce6d0463](https://bsd-hardware.info/?probe=9cce6d0463) | Apr 03, 2023 |
| ASUSTek       | PRIME A520M-E               | [3592fe0b85](https://bsd-hardware.info/?probe=3592fe0b85) | Apr 03, 2023 |
| Unknown       | Unknown                     | [a0548bbb6e](https://bsd-hardware.info/?probe=a0548bbb6e) | Mar 31, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | [16d1e0aa3e](https://bsd-hardware.info/?probe=16d1e0aa3e) | Mar 31, 2023 |
| ASRock        | H61M-HVS                    | [98777ba333](https://bsd-hardware.info/?probe=98777ba333) | Mar 27, 2023 |
| Positivo      | POS-PIB150DT                | [f0158da9e1](https://bsd-hardware.info/?probe=f0158da9e1) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | [7399558d80](https://bsd-hardware.info/?probe=7399558d80) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | [3fb2d0d992](https://bsd-hardware.info/?probe=3fb2d0d992) | Mar 17, 2023 |
| T-bao         | MINI PC                     | [d4440566b0](https://bsd-hardware.info/?probe=d4440566b0) | Mar 13, 2023 |
| Positivo      | POS-PIB150DT                | [5f39c02bc9](https://bsd-hardware.info/?probe=5f39c02bc9) | Mar 13, 2023 |
| Intel         | DP55WB AAE64798-207         | [1c8295549c](https://bsd-hardware.info/?probe=1c8295549c) | Mar 10, 2023 |
| Dell          | 06X1TJ A00                  | [ac0118b05e](https://bsd-hardware.info/?probe=ac0118b05e) | Mar 03, 2023 |
| Dell          | 06X1TJ A00                  | [b663ccd3cb](https://bsd-hardware.info/?probe=b663ccd3cb) | Mar 01, 2023 |
| Dell          | 0WR7PY A00                  | [70b222c73b](https://bsd-hardware.info/?probe=70b222c73b) | Feb 23, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [fd39a615de](https://bsd-hardware.info/?probe=fd39a615de) | Feb 19, 2023 |
| Gigabyte      | B450M AORUS ELITE           | [6af537ff20](https://bsd-hardware.info/?probe=6af537ff20) | Feb 18, 2023 |
| ASRock        | A320M-DGS                   | [032d7f0c91](https://bsd-hardware.info/?probe=032d7f0c91) | Feb 17, 2023 |
| Unknown       | Unknown                     | [34d9347fc3](https://bsd-hardware.info/?probe=34d9347fc3) | Feb 08, 2023 |
| AZW           | U59                         | [8073f1f5f3](https://bsd-hardware.info/?probe=8073f1f5f3) | Feb 04, 2023 |
| ASRock        | J4005B-ITX                  | [c4bf6a3b8c](https://bsd-hardware.info/?probe=c4bf6a3b8c) | Feb 01, 2023 |
| ASUSTek       | H110M-CS/BR                 | [73b6128279](https://bsd-hardware.info/?probe=73b6128279) | Jan 31, 2023 |
| ASUSTek       | H110M-CS/BR                 | [3fa3b849a3](https://bsd-hardware.info/?probe=3fa3b849a3) | Jan 31, 2023 |
| Biostar       | TB250-BTC+                  | [0a39ffa716](https://bsd-hardware.info/?probe=0a39ffa716) | Jan 24, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [9cd4d2810a](https://bsd-hardware.info/?probe=9cd4d2810a) | Jan 23, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [6dc0fddda1](https://bsd-hardware.info/?probe=6dc0fddda1) | Jan 22, 2023 |
| Unknown       | Unknown                     | [32477354bc](https://bsd-hardware.info/?probe=32477354bc) | Jan 19, 2023 |
| AMI           | MNHO-048                    | [fbd9fa83d9](https://bsd-hardware.info/?probe=fbd9fa83d9) | Jan 05, 2023 |
| Dell          | 0CU409                      | [a547f05175](https://bsd-hardware.info/?probe=a547f05175) | Jan 02, 2023 |
| Dell          | 02YRK5 A03                  | [547b1abce0](https://bsd-hardware.info/?probe=547b1abce0) | Dec 16, 2022 |
| Dell          | 0CU409                      | [718c9c5c8b](https://bsd-hardware.info/?probe=718c9c5c8b) | Dec 15, 2022 |
| Dell          | 0CU409                      | [161da6b850](https://bsd-hardware.info/?probe=161da6b850) | Dec 15, 2022 |
| Dell          | 06X1TJ A00                  | [1115d508c1](https://bsd-hardware.info/?probe=1115d508c1) | Dec 09, 2022 |
| Intel         | Q3XXG4-P V1.0               | [84d1656c05](https://bsd-hardware.info/?probe=84d1656c05) | Nov 30, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [88929a3594](https://bsd-hardware.info/?probe=88929a3594) | Nov 25, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [ef6190861c](https://bsd-hardware.info/?probe=ef6190861c) | Nov 25, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [76ecd68ff6](https://bsd-hardware.info/?probe=76ecd68ff6) | Nov 25, 2022 |
| Pegatron      | IPM41-D3                    | [898f645e32](https://bsd-hardware.info/?probe=898f645e32) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | [d3cbc9d6ca](https://bsd-hardware.info/?probe=d3cbc9d6ca) | Nov 19, 2022 |
| Dell          | 0F428D A00                  | [0a9ca655d3](https://bsd-hardware.info/?probe=0a9ca655d3) | Nov 08, 2022 |
| ASUSTek       | H110M-CS/BR                 | [0841d714d0](https://bsd-hardware.info/?probe=0841d714d0) | Nov 03, 2022 |
| maiyunda      | www.maiyunda.com            | [4dfd35f622](https://bsd-hardware.info/?probe=4dfd35f622) | Oct 31, 2022 |
| maiyunda      | www.maiyunda.com            | [ed59c93b79](https://bsd-hardware.info/?probe=ed59c93b79) | Oct 29, 2022 |
| Lenovo        | ThinkCentre M57p 6078AJ6    | [a808a7360d](https://bsd-hardware.info/?probe=a808a7360d) | Oct 14, 2022 |
| ASUSTek       | H110M-CS/BR                 | [097a263bfc](https://bsd-hardware.info/?probe=097a263bfc) | Oct 11, 2022 |
| PCWare        | IPMH81G1                    | [58b53464d1](https://bsd-hardware.info/?probe=58b53464d1) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | [c70e4d6b3c](https://bsd-hardware.info/?probe=c70e4d6b3c) | Oct 10, 2022 |
| ASRock        | J4005B-ITX                  | [6cf37e95da](https://bsd-hardware.info/?probe=6cf37e95da) | Oct 10, 2022 |
| Gigabyte      | G31M-S2C                    | [8b8f621562](https://bsd-hardware.info/?probe=8b8f621562) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | [21117c0374](https://bsd-hardware.info/?probe=21117c0374) | Oct 10, 2022 |
| ASRock        | J4005B-ITX                  | [0e0ff27c25](https://bsd-hardware.info/?probe=0e0ff27c25) | Oct 09, 2022 |
| HP            | 86FC MVB                    | [56453b00c8](https://bsd-hardware.info/?probe=56453b00c8) | Oct 08, 2022 |
| HP            | 86FC MVB                    | [c542b16d75](https://bsd-hardware.info/?probe=c542b16d75) | Oct 08, 2022 |
| Techvision    | TVI7309X B0                 | [1fd10e86d9](https://bsd-hardware.info/?probe=1fd10e86d9) | Oct 04, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [122f6f6837](https://bsd-hardware.info/?probe=122f6f6837) | Oct 02, 2022 |
| ASRock        | A320M-HD                    | [6418fd0b23](https://bsd-hardware.info/?probe=6418fd0b23) | Sep 28, 2022 |
| Dell          | 02YRK5 A03                  | [2ec32e432d](https://bsd-hardware.info/?probe=2ec32e432d) | Sep 20, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [ca3b8f6b48](https://bsd-hardware.info/?probe=ca3b8f6b48) | Sep 20, 2022 |
| ASUSTek       | M5A88-M                     | [09b5ca588f](https://bsd-hardware.info/?probe=09b5ca588f) | Sep 16, 2022 |
| Techvision    | TVI7309X B0                 | [505feb51ca](https://bsd-hardware.info/?probe=505feb51ca) | Sep 15, 2022 |
| maiyunda      | www.maiyunda.com            | [8776541164](https://bsd-hardware.info/?probe=8776541164) | Sep 09, 2022 |
| Pegatron      | IPM41-D3                    | [2d3a5a5260](https://bsd-hardware.info/?probe=2d3a5a5260) | Sep 06, 2022 |
| Unknown       | Unknown                     | [f2a26e2adc](https://bsd-hardware.info/?probe=f2a26e2adc) | Sep 01, 2022 |
| Unknown       | Unknown                     | [05e28da420](https://bsd-hardware.info/?probe=05e28da420) | Aug 16, 2022 |
| Pegatron      | IPMIP-GS                    | [5ee5edb1d0](https://bsd-hardware.info/?probe=5ee5edb1d0) | Aug 16, 2022 |
| Pegatron      | IPMIP-GS                    | [f3c4668e00](https://bsd-hardware.info/?probe=f3c4668e00) | Aug 16, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | [d61693dffb](https://bsd-hardware.info/?probe=d61693dffb) | Aug 05, 2022 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [0b29806790](https://bsd-hardware.info/?probe=0b29806790) | Jul 23, 2022 |
| ASRock        | N68-S3 UCC                  | [e503017a9f](https://bsd-hardware.info/?probe=e503017a9f) | Jul 21, 2022 |
| Dell          | 0GDG8Y A02                  | [2f163e2a05](https://bsd-hardware.info/?probe=2f163e2a05) | Jul 21, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [f88fa027ab](https://bsd-hardware.info/?probe=f88fa027ab) | Jul 19, 2022 |
| Gigabyte      | C847N                       | [4be8944950](https://bsd-hardware.info/?probe=4be8944950) | Jul 15, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [87d68034db](https://bsd-hardware.info/?probe=87d68034db) | Jul 14, 2022 |
| Pegatron      | IPM41-D3                    | [8b2af1b843](https://bsd-hardware.info/?probe=8b2af1b843) | Jul 06, 2022 |
| Pegatron      | IPM41-D3                    | [1cd93cd5d3](https://bsd-hardware.info/?probe=1cd93cd5d3) | Jul 04, 2022 |
| Biostar       | G41D3C                      | [118bd083bf](https://bsd-hardware.info/?probe=118bd083bf) | Jul 01, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | [346bc6f0ae](https://bsd-hardware.info/?probe=346bc6f0ae) | Jun 20, 2022 |
| ASUSTek       | A88XM-A                     | [a464043744](https://bsd-hardware.info/?probe=a464043744) | Jun 19, 2022 |
| ASUSTek       | P5G41T-M LX V2              | [bba161b618](https://bsd-hardware.info/?probe=bba161b618) | Jun 08, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [7be45ccc7e](https://bsd-hardware.info/?probe=7be45ccc7e) | Jun 08, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | [848361c724](https://bsd-hardware.info/?probe=848361c724) | May 31, 2022 |
| Dell          | 0D28YY A00                  | [8f25636c51](https://bsd-hardware.info/?probe=8f25636c51) | May 19, 2022 |
| CNCTION-IA... | Unknown                     | [d6602975d3](https://bsd-hardware.info/?probe=d6602975d3) | May 16, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [8675ff74d8](https://bsd-hardware.info/?probe=8675ff74d8) | May 09, 2022 |
| HP            | 2820h                       | [d888b8b775](https://bsd-hardware.info/?probe=d888b8b775) | Apr 22, 2022 |
| Intel         | H55                         | [1478e4af73](https://bsd-hardware.info/?probe=1478e4af73) | Apr 20, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [11ec99d4b7](https://bsd-hardware.info/?probe=11ec99d4b7) | Apr 11, 2022 |
| ASUSTek       | P5G41T-M LX V2              | [64de6d6bb9](https://bsd-hardware.info/?probe=64de6d6bb9) | Mar 24, 2022 |
| ASUSTek       | P5G41T-M LX V2              | [99ab8e7989](https://bsd-hardware.info/?probe=99ab8e7989) | Mar 11, 2022 |
| Pegatron      | IPM41-D3                    | [a58b9a4f8f](https://bsd-hardware.info/?probe=a58b9a4f8f) | Mar 09, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [62474001e3](https://bsd-hardware.info/?probe=62474001e3) | Mar 09, 2022 |
| MSI           | U-100 Ver.001               | [50aba1dee8](https://bsd-hardware.info/?probe=50aba1dee8) | Mar 03, 2022 |
| MSI           | U-100 Ver.001               | [6859308aa9](https://bsd-hardware.info/?probe=6859308aa9) | Mar 01, 2022 |
| HP            | 1905                        | [e271589365](https://bsd-hardware.info/?probe=e271589365) | Mar 01, 2022 |
| HP            | 1905                        | [aa010e00f2](https://bsd-hardware.info/?probe=aa010e00f2) | Feb 28, 2022 |
| KLLISRE       | X99-B5 V1.0                 | [5dea1304b9](https://bsd-hardware.info/?probe=5dea1304b9) | Feb 26, 2022 |
| GALAX         | B365M G10b                  | [ceb2291168](https://bsd-hardware.info/?probe=ceb2291168) | Feb 22, 2022 |
| HP            | 83E1                        | [d8e995126f](https://bsd-hardware.info/?probe=d8e995126f) | Feb 10, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [d57de875a6](https://bsd-hardware.info/?probe=d57de875a6) | Feb 07, 2022 |
| Unknown       | YL-E3845L4-V2               | [24e60f4686](https://bsd-hardware.info/?probe=24e60f4686) | Feb 02, 2022 |
| Dell          | 0GDG8Y A02                  | [343129f659](https://bsd-hardware.info/?probe=343129f659) | Feb 01, 2022 |
| Gigabyte      | C847N                       | [0d62b7756c](https://bsd-hardware.info/?probe=0d62b7756c) | Jan 24, 2022 |
| ASUSTek       | J1800I-C/BR                 | [13d6d1ed51](https://bsd-hardware.info/?probe=13d6d1ed51) | Jan 21, 2022 |
| Unknown       | Phitronics G31VS-M          | [820f706b46](https://bsd-hardware.info/?probe=820f706b46) | Jan 06, 2022 |
| Unknown       | G31T-M7                     | [ed7d80e01a](https://bsd-hardware.info/?probe=ed7d80e01a) | Jan 03, 2022 |
| Pegatron      | IPM41-D3                    | [6829928dad](https://bsd-hardware.info/?probe=6829928dad) | Dec 28, 2021 |
| Unknown       | X79                         | [c80b658f36](https://bsd-hardware.info/?probe=c80b658f36) | Nov 09, 2021 |
| Itautec       | ST 4344 ST-4344 Padrao 0... | [ec13cb0829](https://bsd-hardware.info/?probe=ec13cb0829) | Nov 07, 2021 |
| Unknown       | X79                         | [ef88cbc606](https://bsd-hardware.info/?probe=ef88cbc606) | Nov 05, 2021 |
| Dell          | 0M5DCD A02                  | [4ff4198768](https://bsd-hardware.info/?probe=4ff4198768) | Nov 02, 2021 |
| Gigabyte      | G41MT-S2                    | [2847d63db0](https://bsd-hardware.info/?probe=2847d63db0) | Oct 18, 2021 |
| ASRock        | A320M-DGS                   | [11cf5c923a](https://bsd-hardware.info/?probe=11cf5c923a) | Oct 08, 2021 |
| ASUSTek       | J1800I-C/BR                 | [e7395898d8](https://bsd-hardware.info/?probe=e7395898d8) | Sep 25, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [b00f275d35](https://bsd-hardware.info/?probe=b00f275d35) | Sep 23, 2021 |
| ASUSTek       | J1800I-C/BR                 | [91642a928d](https://bsd-hardware.info/?probe=91642a928d) | Sep 20, 2021 |
| PCWare        | PW-945GCX                   | [04bbdf92d6](https://bsd-hardware.info/?probe=04bbdf92d6) | Sep 13, 2021 |
| Unknown       | Phitronics G31VS-M          | [0d13c20ba5](https://bsd-hardware.info/?probe=0d13c20ba5) | Sep 11, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [0a1be200c6](https://bsd-hardware.info/?probe=0a1be200c6) | Aug 29, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [a129f532bd](https://bsd-hardware.info/?probe=a129f532bd) | Aug 28, 2021 |
| Gigabyte      | H61M-S2-B3                  | [7c9c49f924](https://bsd-hardware.info/?probe=7c9c49f924) | Aug 27, 2021 |
| ECS-USA       | GeForce6100PM-M2            | [f6324966fb](https://bsd-hardware.info/?probe=f6324966fb) | Aug 26, 2021 |
| ASUSTek       | P5Q                         | [01c4a15001](https://bsd-hardware.info/?probe=01c4a15001) | Aug 22, 2021 |
| HC            | HCAR357-MI V1.0             | [3293b7bad9](https://bsd-hardware.info/?probe=3293b7bad9) | Aug 17, 2021 |
| Gigabyte      | C847N                       | [c19601f640](https://bsd-hardware.info/?probe=c19601f640) | Aug 07, 2021 |
| Gigabyte      | H61M-S2-B3                  | [d1790c6aed](https://bsd-hardware.info/?probe=d1790c6aed) | Aug 04, 2021 |
| Intel         | Q3XXG4-P V1.0               | [1aad7a6eab](https://bsd-hardware.info/?probe=1aad7a6eab) | Aug 03, 2021 |
| Intel         | Q3XXG4-P V1.0               | [95573fe387](https://bsd-hardware.info/?probe=95573fe387) | Aug 03, 2021 |
| Unknown       | Unknown                     | [524215c510](https://bsd-hardware.info/?probe=524215c510) | Aug 03, 2021 |
| ECS           | BAT-I                       | [6741011e07](https://bsd-hardware.info/?probe=6741011e07) | Aug 02, 2021 |
| Yanling       | NS-1U8L                     | [6166362d7a](https://bsd-hardware.info/?probe=6166362d7a) | Jul 27, 2021 |
| ULTRATOP      | C2017-LIVA-ZE               | [d091f171b7](https://bsd-hardware.info/?probe=d091f171b7) | Jun 23, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [5f9b56c8ae](https://bsd-hardware.info/?probe=5f9b56c8ae) | Jun 15, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [edebe87739](https://bsd-hardware.info/?probe=edebe87739) | Jun 04, 2021 |
| Dell          | 0GDG8Y A02                  | [5b44835ac1](https://bsd-hardware.info/?probe=5b44835ac1) | Jun 03, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [c44be632d3](https://bsd-hardware.info/?probe=c44be632d3) | May 28, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [5675cca325](https://bsd-hardware.info/?probe=5675cca325) | May 28, 2021 |
| Gigabyte      | H61M-S2-B3                  | [b73e45e0df](https://bsd-hardware.info/?probe=b73e45e0df) | May 27, 2021 |
| Toshiba       | STI 005492G                 | [9a8e4a1328](https://bsd-hardware.info/?probe=9a8e4a1328) | May 17, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [e69be420df](https://bsd-hardware.info/?probe=e69be420df) | May 16, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [01cc3a3802](https://bsd-hardware.info/?probe=01cc3a3802) | Apr 11, 2021 |
| Gigabyte      | C847N                       | [1d9e74caab](https://bsd-hardware.info/?probe=1d9e74caab) | Apr 08, 2021 |
| Dell          | 04YP6J A03                  | [779e2e4d2d](https://bsd-hardware.info/?probe=779e2e4d2d) | Apr 05, 2021 |
| Pegatron      | IPM41-D3                    | [687047b3d2](https://bsd-hardware.info/?probe=687047b3d2) | Mar 30, 2021 |
| Dell          | 04YP6J A03                  | [59efed23b2](https://bsd-hardware.info/?probe=59efed23b2) | Mar 30, 2021 |
| Dell          | 0P301D A01                  | [bd0c36fe70](https://bsd-hardware.info/?probe=bd0c36fe70) | Mar 26, 2021 |
| ECS           | H55H-CM                     | [a2808d49c9](https://bsd-hardware.info/?probe=a2808d49c9) | Mar 25, 2021 |
| ECS           | H55H-CM                     | [3b13b3a934](https://bsd-hardware.info/?probe=3b13b3a934) | Mar 25, 2021 |
| ECS           | H55H-CM                     | [5df8692ddd](https://bsd-hardware.info/?probe=5df8692ddd) | Mar 18, 2021 |
| ECS           | H55H-CM                     | [6a10af558b](https://bsd-hardware.info/?probe=6a10af558b) | Mar 18, 2021 |
| Pegatron      | IPM41-D3                    | [fdfc8e2b9b](https://bsd-hardware.info/?probe=fdfc8e2b9b) | Mar 17, 2021 |
| ASUSTek       | H81M-C/BR                   | [c4b2356821](https://bsd-hardware.info/?probe=c4b2356821) | Mar 17, 2021 |
| ASUSTek       | H81M-C/BR                   | [c23066d56d](https://bsd-hardware.info/?probe=c23066d56d) | Mar 17, 2021 |
| Gigabyte      | 970A-UD3P                   | [cc3151bc6f](https://bsd-hardware.info/?probe=cc3151bc6f) | Mar 17, 2021 |
| Gigabyte      | H61M-S2-B3                  | [35f1d21b73](https://bsd-hardware.info/?probe=35f1d21b73) | Mar 16, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [49509bf7ee](https://bsd-hardware.info/?probe=49509bf7ee) | Mar 13, 2021 |
| Dell          | 0HN7XN A01                  | [3339a68c44](https://bsd-hardware.info/?probe=3339a68c44) | Mar 12, 2021 |
| ASRock        | 970A-G                      | [3e474f93cf](https://bsd-hardware.info/?probe=3e474f93cf) | Mar 04, 2021 |
| ASUSTek       | H110M-K                     | [b33294491e](https://bsd-hardware.info/?probe=b33294491e) | Mar 02, 2021 |
| MSI           | E350IS-E45                  | [2d4f50994d](https://bsd-hardware.info/?probe=2d4f50994d) | Feb 24, 2021 |
| ASUSTek       | P5Q                         | [22fa0d8178](https://bsd-hardware.info/?probe=22fa0d8178) | Feb 23, 2021 |
| Intel         | H61                         | [a8ae96a0ab](https://bsd-hardware.info/?probe=a8ae96a0ab) | Feb 23, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [405b36b911](https://bsd-hardware.info/?probe=405b36b911) | Feb 21, 2021 |
| Dell          | 0M8K4M A00                  | [6d3defcde3](https://bsd-hardware.info/?probe=6d3defcde3) | Feb 21, 2021 |
| Intel         | Q3XXG4-P V1.0               | [337aa08686](https://bsd-hardware.info/?probe=337aa08686) | Feb 18, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7699b1e79f](https://bsd-hardware.info/?probe=7699b1e79f) | Feb 18, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7ef872c122](https://bsd-hardware.info/?probe=7ef872c122) | Feb 18, 2021 |
| ASRock        | A320M-DGS                   | [d8a1ca5210](https://bsd-hardware.info/?probe=d8a1ca5210) | Feb 17, 2021 |
| Pegatron      | IPM41-D3                    | [ffc1292c18](https://bsd-hardware.info/?probe=ffc1292c18) | Feb 16, 2021 |
| Pegatron      | IPM41-D3                    | [6e5c330c9c](https://bsd-hardware.info/?probe=6e5c330c9c) | Feb 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | [32a87da376](https://bsd-hardware.info/?probe=32a87da376) | Feb 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | [cf042892e7](https://bsd-hardware.info/?probe=cf042892e7) | Feb 16, 2021 |
| Dell          | 0GDG8Y A02                  | [5cda8abfad](https://bsd-hardware.info/?probe=5cda8abfad) | Feb 14, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [694204751b](https://bsd-hardware.info/?probe=694204751b) | Feb 13, 2021 |
| Dell          | 07N90W A02                  | [6bbd0de8d9](https://bsd-hardware.info/?probe=6bbd0de8d9) | Feb 08, 2021 |
| ASRock        | A320M-DGS                   | [7c179e0033](https://bsd-hardware.info/?probe=7c179e0033) | Feb 06, 2021 |
| HP            | ProLiant ML350 G6           | [0539585a88](https://bsd-hardware.info/?probe=0539585a88) | Feb 05, 2021 |
| Positivo      | POS-EAA75DE                 | [cb30dbeef2](https://bsd-hardware.info/?probe=cb30dbeef2) | Feb 05, 2021 |
| Positivo      | POS-EAA75DE                 | [c1fb910e23](https://bsd-hardware.info/?probe=c1fb910e23) | Feb 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7833038238](https://bsd-hardware.info/?probe=7833038238) | Feb 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | [d46871a402](https://bsd-hardware.info/?probe=d46871a402) | Feb 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | [52d17aa061](https://bsd-hardware.info/?probe=52d17aa061) | Jan 28, 2021 |
| Intel         | DH61WW AAG23116-206         | [85a0e6c728](https://bsd-hardware.info/?probe=85a0e6c728) | Jan 24, 2021 |
| Intel         | DH61WW AAG23116-206         | [3e468c1461](https://bsd-hardware.info/?probe=3e468c1461) | Jan 23, 2021 |
| PCWare        | IPX1800G2                   | [bc9bce51bc](https://bsd-hardware.info/?probe=bc9bce51bc) | Jan 22, 2021 |
| MSI           | J1800I                      | [98abf7d1f0](https://bsd-hardware.info/?probe=98abf7d1f0) | Jan 22, 2021 |
| MSI           | J1800I                      | [b6adf4005e](https://bsd-hardware.info/?probe=b6adf4005e) | Jan 21, 2021 |
| HP            | ProLiant ML310e Gen8 v2     | [ba328938c3](https://bsd-hardware.info/?probe=ba328938c3) | Jan 21, 2021 |
| Intel         | Q3XXG4-P V1.0               | [23e48fdef0](https://bsd-hardware.info/?probe=23e48fdef0) | Jan 21, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [75e86a92f7](https://bsd-hardware.info/?probe=75e86a92f7) | Dec 05, 2020 |
| HP            | ProLiant MicroServer Gen... | [825a724001](https://bsd-hardware.info/?probe=825a724001) | Oct 25, 2020 |
| HP            | ProLiant MicroServer        | [04b6ad9952](https://bsd-hardware.info/?probe=04b6ad9952) | Oct 25, 2020 |
| ASUSTek       | Z8P                         | [7b0818f96a](https://bsd-hardware.info/?probe=7b0818f96a) | Sep 16, 2020 |
| ASUSTek       | STRIX B250G GAMING          | [a02398f78f](https://bsd-hardware.info/?probe=a02398f78f) | Sep 01, 2020 |
| ASUSTek       | Z8P                         | [9f5845a398](https://bsd-hardware.info/?probe=9f5845a398) | Jul 27, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | [7e845aab76](https://bsd-hardware.info/?probe=7e845aab76) | Jul 26, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | [7febd3108d](https://bsd-hardware.info/?probe=7febd3108d) | Jul 26, 2020 |
| Procomp In... | G41MXE                      | [a76a3bb201](https://bsd-hardware.info/?probe=a76a3bb201) | Jul 25, 2020 |
| ASUSTek       | Z8P                         | [5071a32803](https://bsd-hardware.info/?probe=5071a32803) | Jun 05, 2020 |
| ASUSTek       | Z8P                         | [a0723b0566](https://bsd-hardware.info/?probe=a0723b0566) | Jun 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| helloSystem 0.7.0    | 13       | 5.94%   |
| OPNsense 23.1.11     | 10       | 4.57%   |
| helloSystem 0.8.1    | 10       | 4.57%   |
| helloSystem 0.8.0    | 7        | 3.2%    |
| OPNsense 23.1.7      | 6        | 2.74%   |
| OPNsense 23.1.5      | 6        | 2.74%   |
| OPNsense 22.1.10     | 6        | 2.74%   |
| OPNsense 20.7.8      | 6        | 2.74%   |
| OPNsense 23.7.10     | 5        | 2.28%   |
| OPNsense 23.1.9      | 5        | 2.28%   |
| OPNsense 22.7.5      | 5        | 2.28%   |
| OPNsense 21.1.3      | 5        | 2.28%   |
| OPNsense 21.1        | 5        | 2.28%   |
| helloSystem 0.4.0    | 5        | 2.28%   |
| OPNsense 23.7.9      | 4        | 1.83%   |
| OPNsense 23.1        | 4        | 1.83%   |
| OPNsense 22.7.8      | 4        | 1.83%   |
| OPNsense 22.7.4      | 4        | 1.83%   |
| OPNsense 21.1.1      | 4        | 1.83%   |
| helloSystem 0.6.0    | 4        | 1.83%   |
| helloSystem 0.5.0    | 4        | 1.83%   |
| FreeBSD 14.0-CURRENT | 4        | 1.83%   |
| OPNsense 23.1.1      | 3        | 1.37%   |
| OPNsense 22.7.6      | 3        | 1.37%   |
| OPNsense 22.1.8      | 3        | 1.37%   |
| OPNsense 21.7.7      | 3        | 1.37%   |
| OPNsense 21.7.1      | 3        | 1.37%   |
| OPNsense 21.1.9      | 3        | 1.37%   |
| OPNsense 21.1.6      | 3        | 1.37%   |
| OPNsense 21.1.4      | 3        | 1.37%   |
| OPNsense 23.7.6      | 2        | 0.91%   |
| OPNsense 23.7.2      | 2        | 0.91%   |
| OPNsense 23.7        | 2        | 0.91%   |
| OPNsense 23.1.8      | 2        | 0.91%   |
| OPNsense 23.1.6      | 2        | 0.91%   |
| OPNsense 23.1.3      | 2        | 0.91%   |
| OPNsense 22.7.9      | 2        | 0.91%   |
| OPNsense 22.7.10     | 2        | 0.91%   |
| OPNsense 22.1.7      | 2        | 0.91%   |
| OPNsense 22.1        | 2        | 0.91%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 98       | 57.31%  |
| helloSystem | 38       | 22.22%  |
| FreeBSD     | 23       | 13.45%  |
| OpenBSD     | 3        | 1.75%   |
| pfSense     | 2        | 1.17%   |
| NomadBSD    | 2        | 1.17%   |
| GhostBSD    | 2        | 1.17%   |
| TrueNAS     | 1        | 0.58%   |
| NetBSD      | 1        | 0.58%   |
| FreeNAS     | 1        | 0.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 167      | 98.82%  |
| i386  | 2        | 1.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 103      | 60.23%  |
| helloDesktop | 41       | 23.98%  |
| KDE5         | 9        | 5.26%   |
| XFCE         | 4        | 2.34%   |
| Openbox      | 4        | 2.34%   |
| MATE         | 3        | 1.75%   |
| i3           | 2        | 1.17%   |
| X-Cinnamon   | 1        | 0.58%   |
| Window Maker | 1        | 0.58%   |
| TWM          | 1        | 0.58%   |
| GNOME        | 1        | 0.58%   |
| AwesomeWM    | 1        | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 105      | 62.13%  |
| X11     | 64       | 37.87%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 114      | 67.06%  |
| SLiM    | 41       | 24.12%  |
| SDDM    | 9        | 5.29%   |
| GDM     | 3        | 1.76%   |
| LightDM | 2        | 1.18%   |
| XDM     | 1        | 0.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 103      | 59.88%  |
| en_US   | 30       | 17.44%  |
| pt_BR   | 17       | 9.88%   |
| C       | 14       | 8.14%   |
| fr_FR   | 4        | 2.33%   |
| pt      | 3        | 1.74%   |
| fr      | 1        | 0.58%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 143      | 81.71%  |
| BIOS | 32       | 18.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 82       | 46.86%  |
| Zfs    | 72       | 41.14%  |
| Cd9660 | 18       | 10.29%  |
| Ffs    | 3        | 1.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 155      | 89.08%  |
| MBR     | 17       | 9.77%   |
| Unknown | 2        | 1.15%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUSTek Computer        | 35       | 20.71%  |
| Dell                    | 21       | 12.43%  |
| Unknown                 | 20       | 11.83%  |
| Intel                   | 19       | 11.24%  |
| Gigabyte Technology     | 13       | 7.69%   |
| Hewlett-Packard         | 9        | 5.33%   |
| ASRock                  | 7        | 4.14%   |
| Lenovo                  | 5        | 2.96%   |
| MSI                     | 4        | 2.37%   |
| Techvision              | 3        | 1.78%   |
| Positivo                | 3        | 1.78%   |
| Pegatron                | 3        | 1.78%   |
| PCWare                  | 3        | 1.78%   |
| Itautec                 | 3        | 1.78%   |
| ECS                     | 2        | 1.18%   |
| Biostar                 | 2        | 1.18%   |
| YANYU                   | 1        | 0.59%   |
| Yanling                 | 1        | 0.59%   |
| ULTRATOP                | 1        | 0.59%   |
| T-bao                   | 1        | 0.59%   |
| Soyo                    | 1        | 0.59%   |
| Semp Toshiba            | 1        | 0.59%   |
| Procomp Ind. Eletronica | 1        | 0.59%   |
| maiyunda                | 1        | 0.59%   |
| KLLISRE                 | 1        | 0.59%   |
| HC                      | 1        | 0.59%   |
| GALAX                   | 1        | 0.59%   |
| ECS-USA                 | 1        | 0.59%   |
| Daten Tecnologia        | 1        | 0.59%   |
| CNCTION-IAF-E3845       | 1        | 0.59%   |
| ChangWang               | 1        | 0.59%   |
| AZW                     | 1        | 0.59%   |
| AMI                     | 1        | 0.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 21       | 12.43%  |
| Intel Q3XXG4-P V1.0                | 8        | 4.73%   |
| ASUS All Series                    | 4        | 2.37%   |
| Techvision TVI7309X                | 3        | 1.78%   |
| Pegatron IPM41-D3                  | 2        | 1.18%   |
| Intel H81                          | 2        | 1.18%   |
| Intel H55                          | 2        | 1.18%   |
| Gigabyte H61M-S2-B3                | 2        | 1.18%   |
| Dell OptiPlex 7040                 | 2        | 1.18%   |
| Dell OptiPlex 3020                 | 2        | 1.18%   |
| ASUS TUF Gaming B550M-PLUS         | 2        | 1.18%   |
| ASUS PRIME B450M-GAMING/BR         | 2        | 1.18%   |
| ASUS PRIME A520M-E                 | 2        | 1.18%   |
| ASUS P8H61-M LX3 PLUS R2.0         | 2        | 1.18%   |
| ASUS P5G41T-M LX2/BR               | 2        | 1.18%   |
| ASUS M5A78L-M LX/BR                | 2        | 1.18%   |
| ASUS A88XM-A                       | 2        | 1.18%   |
| ASRock J4005B-ITX                  | 2        | 1.18%   |
| YANYU N39SL                        | 1        | 0.59%   |
| Yanling NS-1U8L                    | 1        | 0.59%   |
| ULTRATOP C2017-LIVA-ZE             | 1        | 0.59%   |
| T-bao MINI PC                      | 1        | 0.59%   |
| Soyo SY-YL B550M                   | 1        | 0.59%   |
| Semp Toshiba STI                   | 1        | 0.59%   |
| Procomp Ind. Eletronica G41MXE     | 1        | 0.59%   |
| Positivo Positivo Master D610      | 1        | 0.59%   |
| Positivo POS-PIQ77CL               | 1        | 0.59%   |
| Positivo POS-EAA75DE               | 1        | 0.59%   |
| Pegatron IPMIP-GS                  | 1        | 0.59%   |
| PCWare PW-945GCX                   | 1        | 0.59%   |
| PCWare IPX1800G2                   | 1        | 0.59%   |
| PCWare IPMH81G1                    | 1        | 0.59%   |
| MSI U-100                          | 1        | 0.59%   |
| MSI MS-7877                        | 1        | 0.59%   |
| MSI MS-7698                        | 1        | 0.59%   |
| MSI MS-7529                        | 1        | 0.59%   |
| maiyunda www.maiyunda.com          | 1        | 0.59%   |
| Lenovo V14 G2 ITL 82NM             | 1        | 0.59%   |
| Lenovo ThinkCentre M93p 10A9000WBP | 1        | 0.59%   |
| Lenovo ThinkCentre M57p 6078AJ6    | 1        | 0.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 21       | 12.43%  |
| Dell OptiPlex                  | 13       | 7.69%   |
| Intel Q3XXG4-P                 | 8        | 4.73%   |
| ASUS PRIME                     | 5        | 2.96%   |
| HP ProLiant                    | 4        | 2.37%   |
| Dell Vostro                    | 4        | 2.37%   |
| ASUS All                       | 4        | 2.37%   |
| Techvision TVI7309X            | 3        | 1.78%   |
| Lenovo ThinkCentre             | 3        | 1.78%   |
| Itautec Infoway                | 3        | 1.78%   |
| Dell Inspiron                  | 3        | 1.78%   |
| ASUS TUF                       | 3        | 1.78%   |
| ASUS P8H61-M                   | 3        | 1.78%   |
| ASUS P5G41T-M                  | 3        | 1.78%   |
| ASUS M5A78L-M                  | 3        | 1.78%   |
| Pegatron IPM41-D3              | 2        | 1.18%   |
| Intel H81                      | 2        | 1.18%   |
| Intel H55                      | 2        | 1.18%   |
| HP Compaq                      | 2        | 1.18%   |
| Gigabyte H61M-S2-B3            | 2        | 1.18%   |
| ASUS A88XM-A                   | 2        | 1.18%   |
| ASRock J4005B-ITX              | 2        | 1.18%   |
| YANYU N39SL                    | 1        | 0.59%   |
| Yanling NS-1U8L                | 1        | 0.59%   |
| ULTRATOP C2017-LIVA-ZE         | 1        | 0.59%   |
| T-bao MINI                     | 1        | 0.59%   |
| Soyo SY-YL                     | 1        | 0.59%   |
| Semp Toshiba STI               | 1        | 0.59%   |
| Procomp Ind. Eletronica G41MXE | 1        | 0.59%   |
| Positivo Positivo              | 1        | 0.59%   |
| Positivo POS-PIQ77CL           | 1        | 0.59%   |
| Positivo POS-EAA75DE           | 1        | 0.59%   |
| Pegatron IPMIP-GS              | 1        | 0.59%   |
| PCWare PW-945GCX               | 1        | 0.59%   |
| PCWare IPX1800G2               | 1        | 0.59%   |
| PCWare IPMH81G1                | 1        | 0.59%   |
| MSI U-100                      | 1        | 0.59%   |
| MSI MS-7877                    | 1        | 0.59%   |
| MSI MS-7698                    | 1        | 0.59%   |
| MSI MS-7529                    | 1        | 0.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2022    | 20       | 11.83%  |
| 2016    | 20       | 11.83%  |
| 2013    | 17       | 10.06%  |
| 2010    | 14       | 8.28%   |
| 2018    | 12       | 7.1%    |
| 2021    | 9        | 5.33%   |
| 2011    | 9        | 5.33%   |
| 2020    | 8        | 4.73%   |
| 2019    | 8        | 4.73%   |
| 2017    | 8        | 4.73%   |
| 2014    | 8        | 4.73%   |
| 2012    | 8        | 4.73%   |
| 2009    | 8        | 4.73%   |
| 2008    | 8        | 4.73%   |
| 2023    | 5        | 2.96%   |
| 2015    | 4        | 2.37%   |
| 2007    | 2        | 1.18%   |
| Unknown | 1        | 0.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 169      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 169      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 68       | 38.42%  |
| 4.01-8.0    | 52       | 29.38%  |
| 16.01-24.0  | 36       | 20.34%  |
| 2.01-3.0    | 9        | 5.08%   |
| 32.01-64.0  | 8        | 4.52%   |
| 64.01-256.0 | 3        | 1.69%   |
| 24.01-32.0  | 1        | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 102      | 57.3%   |
| 0.51-1.0   | 48       | 26.97%  |
| 1.01-2.0   | 18       | 10.11%  |
| 2.01-3.0   | 5        | 2.81%   |
| 4.01-8.0   | 2        | 1.12%   |
| 16.01-24.0 | 1        | 0.56%   |
| 8.01-16.0  | 1        | 0.56%   |
| Unknown    | 1        | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 122      | 69.71%  |
| 2      | 18       | 10.29%  |
| 0      | 16       | 9.14%   |
| 3      | 10       | 5.71%   |
| 4      | 4        | 2.29%   |
| 5      | 3        | 1.71%   |
| 7      | 1        | 0.57%   |
| 6      | 1        | 0.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 137      | 80.12%  |
| Yes       | 34       | 19.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 168      | 99.41%  |
| No        | 1        | 0.59%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 142      | 84.02%  |
| Yes       | 27       | 15.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 155      | 91.72%  |
| Yes       | 14       | 8.28%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Brazil  | 169      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Rio de Janeiro            | 13       | 6.81%   |
| SГЈo Paulo              | 12       | 6.28%   |
| Sao Paulo                 | 12       | 6.28%   |
| Sao José dos Campos      | 6        | 3.14%   |
| Jaraguá do Sul           | 6        | 3.14%   |
| Curitiba                  | 6        | 3.14%   |
| Porto Alegre              | 5        | 2.62%   |
| Campinas                  | 4        | 2.09%   |
| Blumenau                  | 4        | 2.09%   |
| SÃ£o Paulo              | 3        | 1.57%   |
| Osasco                    | 3        | 1.57%   |
| Novo Hamburgo             | 3        | 1.57%   |
| Brasília                 | 3        | 1.57%   |
| Sorocaba                  | 2        | 1.05%   |
| Sao Leopoldo              | 2        | 1.05%   |
| Sao Jose do Rio Preto     | 2        | 1.05%   |
| Salvador                  | 2        | 1.05%   |
| RondonГіpolis           | 2        | 1.05%   |
| Rio Claro                 | 2        | 1.05%   |
| Pirapora                  | 2        | 1.05%   |
| Maringá                  | 2        | 1.05%   |
| Londrina                  | 2        | 1.05%   |
| Joinville                 | 2        | 1.05%   |
| Jaboatao dos Guararapes   | 2        | 1.05%   |
| Itaperuna                 | 2        | 1.05%   |
| Guarulhos                 | 2        | 1.05%   |
| Fortaleza                 | 2        | 1.05%   |
| Cruzeiro do Sul           | 2        | 1.05%   |
| BrasÃ­lia               | 2        | 1.05%   |
| Belo Horizonte            | 2        | 1.05%   |
| VitГіria da Conquista   | 1        | 0.52%   |
| Valparaiso de Goias       | 1        | 0.52%   |
| Urupes                    | 1        | 0.52%   |
| Unai                      | 1        | 0.52%   |
| Uberaba                   | 1        | 0.52%   |
| Timbo                     | 1        | 0.52%   |
| Teresina                  | 1        | 0.52%   |
| Taubate                   | 1        | 0.52%   |
| SГЈo JosГ© dos Campos | 1        | 0.52%   |
| Suzano                    | 1        | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 36       | 47     | 17.22%  |
| Kingston            | 36       | 53     | 17.22%  |
| Seagate             | 31       | 60     | 14.83%  |
| Samsung Electronics | 21       | 31     | 10.05%  |
| SanDisk             | 12       | 16     | 5.74%   |
| Hoodisk             | 8        | 8      | 3.83%   |
| Toshiba             | 7        | 7      | 3.35%   |
| China               | 7        | 10     | 3.35%   |
| Crucial             | 6        | 10     | 2.87%   |
| A-DATA Technology   | 6        | 7      | 2.87%   |
| Silicon Motion      | 5        | 6      | 2.39%   |
| XrayDisk            | 3        | 3      | 1.44%   |
| KingSpec            | 3        | 4      | 1.44%   |
| Hitachi             | 3        | 7      | 1.44%   |
| Fanxiang            | 3        | 4      | 1.44%   |
| PNY                 | 2        | 2      | 0.96%   |
| NVMe                | 2        | 4      | 0.96%   |
| NTC                 | 2        | 2      | 0.96%   |
| HGST                | 2        | 3      | 0.96%   |
| Gigabyte Technology | 2        | 3      | 0.96%   |
| Silicon             | 1        | 1      | 0.48%   |
| Netac               | 1        | 1      | 0.48%   |
| Maxtor              | 1        | 1      | 0.48%   |
| MACROVIP            | 1        | 1      | 0.48%   |
| Kston               | 1        | 1      | 0.48%   |
| Intel               | 1        | 2      | 0.48%   |
| Indilinx            | 1        | 2      | 0.48%   |
| Hewlett-Packard     | 1        | 1      | 0.48%   |
| Faspeed             | 1        | 1      | 0.48%   |
| Drevo               | 1        | 6      | 0.48%   |
| Corsair             | 1        | 1      | 0.48%   |
| Colorful            | 1        | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB         | 12       | 5.22%   |
| Kingston SA400S37120G 120GB         | 8        | 3.48%   |
| Seagate ST500DM002-1BD142 500GB     | 7        | 3.04%   |
| SanDisk SSD PLUS 120GB              | 6        | 2.61%   |
| Kingston SA400S37480G 480GB         | 6        | 2.61%   |
| Hoodisk SSD 64GB                    | 6        | 2.61%   |
| Seagate ST1000DM010-2EP102 1TB      | 4        | 1.74%   |
| Samsung HD322HJ 320GB               | 4        | 1.74%   |
| WDC WD10EZEX-00RKKA0 1TB            | 3        | 1.3%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 3        | 1.3%    |
| Seagate ST4000DM000-1F2168 4TB      | 3        | 1.3%    |
| Samsung HD502HJ 500GB               | 3        | 1.3%    |
| Samsung HD103SJ 1TB                 | 3        | 1.3%    |
| Crucial CT120BX500SSD1 120GB        | 3        | 1.3%    |
| A-DATA SU630 240GB                  | 3        | 1.3%    |
| WDC WDS120G2G0A-00JH30 120GB        | 2        | 0.87%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 2        | 0.87%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 2        | 0.87%   |
| WDC WD2500BEVT-75ZCT2 250GB         | 2        | 0.87%   |
| Silicon Motion NVME SSD 128GB       | 2        | 0.87%   |
| Seagate ST2000DM006-2DM164 2TB      | 2        | 0.87%   |
| SanDisk SSD PLUS 240GB              | 2        | 0.87%   |
| SanDisk SDSSDA240G 240GB            | 2        | 0.87%   |
| SanDisk SDSSDA120G 120GB            | 2        | 0.87%   |
| Samsung HD161HJ 160GB               | 2        | 0.87%   |
| Samsung HD081GJ 80GB                | 2        | 0.87%   |
| PNY CS900 120GB SSD                 | 2        | 0.87%   |
| Kingston SUV400S37120G 120GB        | 2        | 0.87%   |
| Kingston SH103S3240G 240GB          | 2        | 0.87%   |
| Hoodisk SSD 32GB                    | 2        | 0.87%   |
| Gigabyte GP-GSTFS31120GNTD 120GB    | 2        | 0.87%   |
| China IM128-P130 128GB              | 2        | 0.87%   |
| A-DATA SU650 120GB                  | 2        | 0.87%   |
| XrayDisk SSD 240GB                  | 1        | 0.43%   |
| XrayDisk SSD 128GB                  | 1        | 0.43%   |
| XrayDisk 1TB SSD                    | 1        | 0.43%   |
| WDC WDS120G2G0B-00EPW0 120GB        | 1        | 0.43%   |
| WDC WD800JD-75MSA3 80GB             | 1        | 0.43%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 0.43%   |
| WDC WD5000AZLX-60K2TA1 500GB        | 1        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 34       | 43     | 35.05%  |
| Seagate             | 31       | 60     | 31.96%  |
| Samsung Electronics | 17       | 24     | 17.53%  |
| Toshiba             | 7        | 7      | 7.22%   |
| Hitachi             | 3        | 7      | 3.09%   |
| NVMe                | 2        | 4      | 2.06%   |
| Maxtor              | 1        | 1      | 1.03%   |
| HGST                | 1        | 2      | 1.03%   |
| Hewlett-Packard     | 1        | 1      | 1.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 33       | 50     | 33%     |
| SanDisk             | 12       | 16     | 12%     |
| Hoodisk             | 8        | 8      | 8%      |
| China               | 7        | 10     | 7%      |
| Crucial             | 6        | 10     | 6%      |
| A-DATA Technology   | 6        | 7      | 6%      |
| XrayDisk            | 3        | 3      | 3%      |
| WDC                 | 3        | 4      | 3%      |
| KingSpec            | 3        | 4      | 3%      |
| Samsung Electronics | 2        | 2      | 2%      |
| PNY                 | 2        | 2      | 2%      |
| NTC                 | 2        | 2      | 2%      |
| Gigabyte Technology | 2        | 3      | 2%      |
| Silicon             | 1        | 1      | 1%      |
| Netac               | 1        | 1      | 1%      |
| MACROVIP            | 1        | 1      | 1%      |
| Kston               | 1        | 1      | 1%      |
| Intel               | 1        | 2      | 1%      |
| Indilinx            | 1        | 2      | 1%      |
| HGST                | 1        | 1      | 1%      |
| Faspeed             | 1        | 1      | 1%      |
| Fanxiang            | 1        | 1      | 1%      |
| Drevo               | 1        | 6      | 1%      |
| Corsair             | 1        | 1      | 1%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 90       | 139    | 49.18%  |
| HDD  | 80       | 149    | 43.72%  |
| NVMe | 13       | 18     | 7.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 142      | 288    | 91.61%  |
| NVMe | 13       | 18     | 8.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 132      | 222    | 79.04%  |
| 0.51-1.0   | 21       | 35     | 12.57%  |
| 1.01-2.0   | 10       | 22     | 5.99%   |
| 3.01-4.0   | 4        | 9      | 2.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 63       | 34.24%  |
| 1-20           | 35       | 19.02%  |
| 251-500        | 30       | 16.3%   |
| 51-100         | 26       | 14.13%  |
| 21-50          | 17       | 9.24%   |
| 501-1000       | 8        | 4.35%   |
| 2001-3000      | 2        | 1.09%   |
| 1001-2000      | 2        | 1.09%   |
| More than 3000 | 1        | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 154      | 90.06%  |
| 21-50     | 10       | 5.85%   |
| 101-250   | 3        | 1.75%   |
| 501-1000  | 2        | 1.17%   |
| 2001-3000 | 1        | 0.58%   |
| 51-100    | 1        | 0.58%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Desktops | Drives | Percent |
|-------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB           | 3        | 3      | 5%      |
| Samsung Electronics HD322HJ 320GB         | 3        | 4      | 5%      |
| WDC WD10EZEX-00RKKA0 1TB                  | 2        | 2      | 3.33%   |
| Samsung Electronics HD161HJ 160GB         | 2        | 2      | 3.33%   |
| XrayDisk SSD 240GB                        | 1        | 1      | 1.67%   |
| WDC WD5000LPVX-22V0TT0 500GB              | 1        | 1      | 1.67%   |
| WDC WD5000AVVS-63H0B1 500GB               | 1        | 1      | 1.67%   |
| WDC WD5000AAKX-00U6AA0 500GB              | 1        | 1      | 1.67%   |
| WDC WD5000AAKX-00ERMA0 500GB              | 1        | 1      | 1.67%   |
| WDC WD5000AAKS-08V0A0 500GB               | 1        | 1      | 1.67%   |
| WDC WD5000AAKS-00UU3A0 500GB              | 1        | 1      | 1.67%   |
| WDC WD3200LPVX-22V0TT0 320GB              | 1        | 1      | 1.67%   |
| WDC WD3200BEVT-00A0RT0 233GB              | 1        | 1      | 1.67%   |
| WDC WD3200AAKS-00UU3A0 320GB              | 1        | 1      | 1.67%   |
| WDC WD3200AAJS-56M0A0 320GB               | 1        | 1      | 1.67%   |
| WDC WD3200AAJS-00YZCA0 320GB              | 1        | 1      | 1.67%   |
| WDC WD2500AAJS-75M0A0 250GB               | 1        | 1      | 1.67%   |
| WDC WD10PURX-64E5EY0 1TB                  | 1        | 1      | 1.67%   |
| WDC WD10EADS-65M2BX 1TB                   | 1        | 1      | 1.67%   |
| Toshiba MQ01ABD050 500GB                  | 1        | 1      | 1.67%   |
| Toshiba MK8052GSX 80GB                    | 1        | 1      | 1.67%   |
| Toshiba MK1255GSX H 120GB                 | 1        | 1      | 1.67%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB | 1        | 1      | 1.67%   |
| Seagate ST9320325AS 320GB                 | 1        | 1      | 1.67%   |
| Seagate ST9160314AS 160GB                 | 1        | 1      | 1.67%   |
| Seagate ST500LT012-9WS142 500GB           | 1        | 2      | 1.67%   |
| Seagate ST500LM021-1KJ152 500GB           | 1        | 1      | 1.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1        | 1      | 1.67%   |
| Seagate ST500DM002-1BC142 500GB           | 1        | 1      | 1.67%   |
| Seagate ST3250310AS 250GB                 | 1        | 1      | 1.67%   |
| Seagate ST320LM001 HN-M320MBB 320GB       | 1        | 1      | 1.67%   |
| Seagate ST2000DM006-2DM164 2TB            | 1        | 1      | 1.67%   |
| Seagate ST2000DM001-1E6164 2TB            | 1        | 1      | 1.67%   |
| Seagate ST2000DL003-9VT166 2TB            | 1        | 9      | 1.67%   |
| SanDisk SSD PLUS 240 GB                   | 1        | 1      | 1.67%   |
| Samsung Electronics HM320II 320GB         | 1        | 2      | 1.67%   |
| Samsung Electronics HD642JJ 640GB         | 1        | 1      | 1.67%   |
| Samsung Electronics HD502HJ 500GB         | 1        | 1      | 1.67%   |
| Samsung Electronics HD203WI 2TB           | 1        | 1      | 1.67%   |
| Samsung Electronics HD103SJ 1TB           | 1        | 1      | 1.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 16     | 24.56%  |
| Seagate             | 14       | 23     | 24.56%  |
| Samsung Electronics | 10       | 13     | 17.54%  |
| Toshiba             | 3        | 3      | 5.26%   |
| Kingston            | 3        | 3      | 5.26%   |
| Hitachi             | 3        | 7      | 5.26%   |
| KingSpec            | 2        | 2      | 3.51%   |
| XrayDisk            | 1        | 1      | 1.75%   |
| Silicon Motion      | 1        | 1      | 1.75%   |
| SanDisk             | 1        | 1      | 1.75%   |
| Netac               | 1        | 1      | 1.75%   |
| Maxtor              | 1        | 1      | 1.75%   |
| HGST                | 1        | 1      | 1.75%   |
| Corsair             | 1        | 1      | 1.75%   |
| A-DATA Technology   | 1        | 1      | 1.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 16     | 31.11%  |
| Seagate             | 14       | 23     | 31.11%  |
| Samsung Electronics | 10       | 13     | 22.22%  |
| Toshiba             | 3        | 3      | 6.67%   |
| Hitachi             | 3        | 7      | 6.67%   |
| Maxtor              | 1        | 1      | 2.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 41       | 63     | 77.36%  |
| SSD  | 11       | 11     | 20.75%  |
| NVMe | 1        | 1      | 1.89%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD3200AAJS-00YZCA0 320GB    | 1        | 1      | 50%     |
| Samsung Electronics HD103SJ 1TB | 1        | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 121      | 216    | 66.85%  |
| Malfunc  | 50       | 75     | 27.62%  |
| Detected | 8        | 12     | 4.42%   |
| Failed   | 2        | 3      | 1.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 135      | 69.95%  |
| AMD                            | 31       | 16.06%  |
| Silicon Motion                 | 9        | 4.66%   |
| Kingston Technology Company    | 4        | 2.07%   |
| Samsung Electronics            | 2        | 1.04%   |
| Nvidia                         | 2        | 1.04%   |
| JMicron Technology             | 2        | 1.04%   |
| Solid State Storage Technology | 1        | 0.52%   |
| SK hynix                       | 1        | 0.52%   |
| Realtek Semiconductor          | 1        | 0.52%   |
| MAXIO Technology (Hangzhou)    | 1        | 0.52%   |
| Integrated Technology Express  | 1        | 0.52%   |
| Hewlett-Packard                | 1        | 0.52%   |
| ASMedia Technology             | 1        | 0.52%   |
| Adaptec                        | 1        | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 23       | 9.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 15       | 6.2%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 5.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 4.55%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 9        | 3.72%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 9        | 3.72%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 3.72%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 8        | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 3.31%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7        | 2.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 2.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 2.89%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 2.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 2.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 2.07%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 2.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4        | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4        | 1.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.65%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 1.24%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 1.24%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.83%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2        | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 0.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 0.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.83%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 0.83%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.83%   |
| AMD FCH SATA Controller D                                                               | 2        | 0.83%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                          | 1        | 0.41%   |
| SK hynix BC511 NVMe SSD                                                                 | 1        | 0.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.41%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 1        | 0.41%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 1        | 0.41%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 117      | 59.39%  |
| IDE  | 52       | 26.4%   |
| NVMe | 19       | 9.64%   |
| RAID | 8        | 4.06%   |
| SCSI | 1        | 0.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 138      | 80.7%   |
| AMD    | 33       | 19.3%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Celeron N5105 @ 2.00GHz                   | 6        | 3.47%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 6        | 3.47%   |
| Intel Core i3-7100 CPU @ 3.90GHz                | 4        | 2.31%   |
| Intel Celeron CPU J1800 @ 2.41GHz               | 4        | 2.31%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 3        | 1.73%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 3        | 1.73%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 3        | 1.73%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz           | 3        | 1.73%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 3        | 1.73%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 3        | 1.73%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 3        | 1.73%   |
| AMD FX-8320E Eight-Core Processor               | 3        | 1.73%   |
| Intel Pentium Silver N6005 @ 2.00GHz            | 2        | 1.16%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 2        | 1.16%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 2        | 1.16%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 2        | 1.16%   |
| Intel Core i5-3570 CPU @ 3.40GHz                | 2        | 1.16%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 2        | 1.16%   |
| Intel Core i3-4030U CPU @ 1.90GHz               | 2        | 1.16%   |
| Intel Core i3-3240 CPU @ 3.40GHz                | 2        | 1.16%   |
| Intel Core i3-2100 CPU                          | 2        | 1.16%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz            | 2        | 1.16%   |
| Intel Core 2 Duo CPU                            | 2        | 1.16%   |
| Intel Celeron J4005 CPU @ 2.00GHz               | 2        | 1.16%   |
| Intel Celeron CPU 847 @ 1.10GHz                 | 2        | 1.16%   |
| AMD FX-6100 Six-Core Processor                  | 2        | 1.16%   |
| AMD A10-7870K Radeon R7, 12 Compute Cores 4C+8G | 2        | 1.16%   |
| Intel Xeon CPU X5680 @ 3.33GHz                  | 1        | 0.58%   |
| Intel Xeon CPU X3440 @ 2.53GHz                  | 1        | 0.58%   |
| Intel Xeon CPU E5506 @ 2.13GHz                  | 1        | 0.58%   |
| Intel Xeon CPU E5462 @ 2.80GHz                  | 1        | 0.58%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz              | 1        | 0.58%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz            | 1        | 0.58%   |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz             | 1        | 0.58%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz             | 1        | 0.58%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz             | 1        | 0.58%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz     | 1        | 0.58%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz     | 1        | 0.58%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz     | 1        | 0.58%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz     | 1        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 31       | 18.02%  |
| Intel Core i5           | 27       | 15.7%   |
| Intel Celeron           | 27       | 15.7%   |
| Intel Core 2 Duo        | 14       | 8.14%   |
| Intel Xeon              | 9        | 5.23%   |
| AMD FX                  | 9        | 5.23%   |
| Intel Pentium Dual-Core | 6        | 3.49%   |
| Intel Core i7           | 6        | 3.49%   |
| AMD Ryzen 5             | 6        | 3.49%   |
| Intel Core 2 Quad       | 5        | 2.91%   |
| AMD Ryzen 7             | 5        | 2.91%   |
| Other                   | 4        | 2.33%   |
| Intel Pentium           | 4        | 2.33%   |
| Intel Atom              | 3        | 1.74%   |
| Intel Pentium Silver    | 2        | 1.16%   |
| AMD A10                 | 2        | 1.16%   |
| Intel Pentium Dual      | 1        | 0.58%   |
| Intel Core 2            | 1        | 0.58%   |
| AMD Turion II Neo       | 1        | 0.58%   |
| AMD Ryzen 5 PRO         | 1        | 0.58%   |
| AMD Ryzen 3 PRO         | 1        | 0.58%   |
| AMD Ryzen 3             | 1        | 0.58%   |
| AMD PRO A8              | 1        | 0.58%   |
| AMD Phenom              | 1        | 0.58%   |
| AMD E                   | 1        | 0.58%   |
| AMD Athlon II X2        | 1        | 0.58%   |
| AMD Athlon 64 X2        | 1        | 0.58%   |
| AMD Athlon              | 1        | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 68       | 39.31%  |
| 4       | 66       | 38.15%  |
| 8       | 13       | 7.51%   |
| 6       | 9        | 5.2%    |
| Unknown | 7        | 4.05%   |
| 12      | 5        | 2.89%   |
| 16      | 4        | 2.31%   |
| 1       | 1        | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 168      | 99.41%  |
| 2      | 1        | 0.59%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 115      | 67.25%  |
| 2       | 49       | 28.65%  |
| Unknown | 7        | 4.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 23       | 13.29%  |
| Haswell       | 19       | 10.98%  |
| KabyLake      | 15       | 8.67%   |
| IvyBridge     | 13       | 7.51%   |
| Unknown       | 13       | 7.51%   |
| SandyBridge   | 11       | 6.36%   |
| Goldmont plus | 9        | 5.2%    |
| Zen+          | 7        | 4.05%   |
| Silvermont    | 7        | 4.05%   |
| Westmere      | 6        | 3.47%   |
| Skylake       | 6        | 3.47%   |
| Piledriver    | 6        | 3.47%   |
| Core          | 6        | 3.47%   |
| Zen 3         | 5        | 2.89%   |
| Broadwell     | 4        | 2.31%   |
| Steamroller   | 3        | 1.73%   |
| Nehalem       | 3        | 1.73%   |
| K10           | 3        | 1.73%   |
| Bulldozer     | 3        | 1.73%   |
| Zen           | 2        | 1.16%   |
| CometLake     | 2        | 1.16%   |
| Bonnell       | 2        | 1.16%   |
| Zen 2         | 1        | 0.58%   |
| TigerLake     | 1        | 0.58%   |
| K8 Hammer     | 1        | 0.58%   |
| Goldmont      | 1        | 0.58%   |
| Bobcat        | 1        | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 116      | 66.67%  |
| AMD                        | 35       | 20.11%  |
| Nvidia                     | 20       | 11.49%  |
| Matrox Electronics Systems | 2        | 1.15%   |
| ASPEED Technology          | 1        | 0.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 12       | 6.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10       | 5.62%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 5.06%   |
| Intel JasperLake [UHD Graphics]                                             | 9        | 5.06%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 9        | 5.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 4.49%   |
| Intel HD Graphics 630                                                       | 8        | 4.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 7        | 3.93%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 7        | 3.93%   |
| Intel Core Processor Integrated Graphics Controller                         | 5        | 2.81%   |
| Intel HD Graphics 5500                                                      | 4        | 2.25%   |
| Intel HD Graphics 530                                                       | 4        | 2.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4        | 2.25%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 2.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 2.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 2.25%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.69%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 3        | 1.69%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 1.69%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 1.69%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 3        | 1.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 1.69%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.69%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.12%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.12%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.12%   |
| Matrox Electronics Systems MGA G200EH                                       | 2        | 1.12%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.12%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.56%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.56%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.56%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.56%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.56%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.56%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 0.56%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 0.56%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1        | 0.56%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 107      | 62.21%  |
| 1 x AMD        | 32       | 18.6%   |
| 1 x Nvidia     | 19       | 11.05%  |
| 2 x Intel      | 5        | 2.91%   |
| Intel + AMD    | 3        | 1.74%   |
| Other          | 2        | 1.16%   |
| 1 x Matrox     | 2        | 1.16%   |
| Intel + Nvidia | 1        | 0.58%   |
| 1 x ASPEED     | 1        | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 155      | 90.64%  |
| Proprietary | 14       | 8.19%   |
| Unknown     | 2        | 1.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 136      | 78.16%  |
| 0.51-1.0   | 11       | 6.32%   |
| 1.01-2.0   | 9        | 5.17%   |
| 3.01-4.0   | 7        | 4.02%   |
| 0.01-0.5   | 7        | 4.02%   |
| 7.01-8.0   | 3        | 1.72%   |
| 2.01-3.0   | 1        | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 20       | 37.74%  |
| Samsung Electronics | 15       | 28.3%   |
| Philips             | 4        | 7.55%   |
| AOC                 | 3        | 5.66%   |
| VIE                 | 1        | 1.89%   |
| Semp Toshiba        | 1        | 1.89%   |
| Panasonic           | 1        | 1.89%   |
| MStar               | 1        | 1.89%   |
| LG Electronics      | 1        | 1.89%   |
| Lenovo              | 1        | 1.89%   |
| ITE                 | 1        | 1.89%   |
| Hewlett-Packard     | 1        | 1.89%   |
| Chimei Innolux      | 1        | 1.89%   |
| ASUSTek Computer    | 1        | 1.89%   |
| AGO                 | 1        | 1.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0601 1600x900                      | 2        | 3.45%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch  | 2        | 3.45%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 2        | 3.45%   |
| VIE E195 VIE1950 1600x900 410x280mm 19.5-inch                        | 1        | 1.72%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch            | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch  | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch  | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                     | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 480x270mm 21.7-inch | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM04E4 1600x900 440x250mm 19.9-inch  | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch  | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch  | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 310x230mm 15.2-inch | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch  | 1        | 1.72%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 440x250mm 19.9-inch | 1        | 1.72%   |
| Samsung Electronics S23C550 SAM0A42 1920x1080 510x290mm 23.1-inch    | 1        | 1.72%   |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch     | 1        | 1.72%   |
| Samsung Electronics LCD Monitor SMT27A550 1920x1080                  | 1        | 1.72%   |
| Samsung Electronics LCD Monitor SAM0678 1360x768                     | 1        | 1.72%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 1        | 1.72%   |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch              | 1        | 1.72%   |
| Philips LCD Monitor PHL2051 1600x900 440x250mm 19.9-inch             | 1        | 1.72%   |
| Philips 221EL PHLC056 1920x1080 480x270mm 21.7-inch                  | 1        | 1.72%   |
| Panasonic TV MEIC136 1280x720 698x392mm 31.5-inch                    | 1        | 1.72%   |
| MStar TSB LEDTV MST0030 1920x1080 1150x650mm 52.0-inch               | 1        | 1.72%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 3640x1920                    | 1        | 1.72%   |
| LG Electronics LCD Monitor 23MP55                                    | 1        | 1.72%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 480x270mm 21.7-inch             | 1        | 1.72%   |
| ITE DP2VGA V235 ITE6516 1920x1080 600x340mm 27.2-inch                | 1        | 1.72%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch           | 1        | 1.72%   |
| Goldstar W2242 GSM4B6F 1680x1050 490x320mm 23.0-inch                 | 1        | 1.72%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                  | 1        | 1.72%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                  | 1        | 1.72%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                  | 1        | 1.72%   |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch          | 1        | 1.72%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch          | 1        | 1.72%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 1        | 1.72%   |
| Goldstar LG HD GSM5ACD 1366x768 410x230mm 18.5-inch                  | 1        | 1.72%   |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch           | 1        | 1.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 25       | 44.64%  |
| 1600x900 (HD+)     | 8        | 14.29%  |
| 1366x768 (WXGA)    | 6        | 10.71%  |
| 2560x1080          | 3        | 5.36%   |
| 1360x768           | 3        | 5.36%   |
| 1280x1024 (SXGA)   | 3        | 5.36%   |
| 1440x900 (WXGA+)   | 2        | 3.57%   |
| 1024x768 (XGA)     | 2        | 3.57%   |
| 3640x1920          | 1        | 1.79%   |
| 1680x1050 (WSXGA+) | 1        | 1.79%   |
| 1280x720 (HD)      | 1        | 1.79%   |
| Unknown            | 1        | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 10       | 17.86%  |
| 23      | 9        | 16.07%  |
| 19      | 8        | 14.29%  |
| 18      | 7        | 12.5%   |
| Unknown | 6        | 10.71%  |
| 34      | 3        | 5.36%   |
| 20      | 2        | 3.57%   |
| 15      | 2        | 3.57%   |
| 14      | 2        | 3.57%   |
| 13      | 2        | 3.57%   |
| 52      | 1        | 1.79%   |
| 31      | 1        | 1.79%   |
| 27      | 1        | 1.79%   |
| 24      | 1        | 1.79%   |
| 17      | 1        | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 26       | 47.27%  |
| 501-600     | 10       | 18.18%  |
| Unknown     | 6        | 10.91%  |
| 301-350     | 4        | 7.27%   |
| 701-800     | 3        | 5.45%   |
| 201-300     | 3        | 5.45%   |
| 601-700     | 1        | 1.82%   |
| 351-400     | 1        | 1.82%   |
| 1001-1500   | 1        | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 38       | 71.7%   |
| 4/3     | 4        | 7.55%   |
| 21/9    | 3        | 5.66%   |
| 5/4     | 2        | 3.77%   |
| 3/2     | 2        | 3.77%   |
| 16/10   | 2        | 3.77%   |
| Unknown | 2        | 3.77%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 20       | 35.71%  |
| 151-200        | 10       | 17.86%  |
| 141-150        | 8        | 14.29%  |
| Unknown        | 6        | 10.71%  |
| 351-500        | 4        | 7.14%   |
| 101-110        | 2        | 3.57%   |
| 91-100         | 2        | 3.57%   |
| More than 1000 | 1        | 1.79%   |
| 81-90          | 1        | 1.79%   |
| 301-350        | 1        | 1.79%   |
| 111-120        | 1        | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 33       | 60%     |
| 101-120 | 12       | 21.82%  |
| Unknown | 6        | 10.91%  |
| 1-50    | 2        | 3.64%   |
| 121-160 | 2        | 3.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 110      | 64.33%  |
| 1     | 56       | 32.75%  |
| 2     | 5        | 2.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 112      | 48.7%   |
| Intel                 | 80       | 34.78%  |
| Broadcom              | 10       | 4.35%   |
| Qualcomm Atheros      | 9        | 3.91%   |
| Ralink                | 4        | 1.74%   |
| D-Link System         | 3        | 1.3%    |
| Ralink Technology     | 2        | 0.87%   |
| IMC Networks          | 2        | 0.87%   |
| TP-Link               | 1        | 0.43%   |
| STMicroelectronics    | 1        | 0.43%   |
| Samsung Electronics   | 1        | 0.43%   |
| MediaTek              | 1        | 0.43%   |
| ICS Advent            | 1        | 0.43%   |
| Edimax Technology     | 1        | 0.43%   |
| Arduino SA            | 1        | 0.43%   |
| 3Com                  | 1        | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 93       | 36.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 14       | 5.43%   |
| Intel I211 Gigabit Network Connection                                         | 13       | 5.04%   |
| Intel Ethernet Controller I226-V                                              | 10       | 3.88%   |
| Intel Ethernet Controller I225-V                                              | 9        | 3.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6        | 2.33%   |
| Intel 82576 Gigabit Network Connection                                        | 5        | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 4        | 1.55%   |
| Intel I350 Gigabit Network Connection                                         | 4        | 1.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4        | 1.55%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 1.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3        | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 1.16%   |
| Intel Ethernet Connection I217-LM                                             | 3        | 1.16%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 1.16%   |
| Intel 82578DC Gigabit Network Connection                                      | 3        | 1.16%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3        | 1.16%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.78%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                  | 2        | 0.78%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                          | 2        | 0.78%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 2        | 0.78%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 2        | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 0.78%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.78%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 0.78%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 0.78%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 0.78%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 2        | 0.78%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 0.78%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 0.78%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.78%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 0.78%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.39%   |
| STMicroelectronics Virtual COM Port                                           | 1        | 0.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.39%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1        | 0.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 35.48%  |
| Intel                 | 7        | 22.58%  |
| Ralink                | 4        | 12.9%   |
| Ralink Technology     | 2        | 6.45%   |
| Qualcomm Atheros      | 2        | 6.45%   |
| IMC Networks          | 2        | 6.45%   |
| TP-Link               | 1        | 3.23%   |
| Edimax Technology     | 1        | 3.23%   |
| D-Link System         | 1        | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4        | 12.5%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 9.38%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                         | 2        | 6.25%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 2        | 6.25%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2        | 6.25%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                 | 2        | 6.25%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1        | 3.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 3.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1        | 3.13%   |
| Realtek RTL8187SE Wireless LAN Controller                            | 1        | 3.13%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 3.13%   |
| Ralink MT7601U Wireless Adapter                                      | 1        | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 3.13%   |
| Intel Wireless 7265                                                  | 1        | 3.13%   |
| Intel Wireless 3165                                                  | 1        | 3.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1        | 3.13%   |
| Intel Wi-Fi 6 AX201                                                  | 1        | 3.13%   |
| Intel Wi-Fi 6 AX200                                                  | 1        | 3.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1        | 3.13%   |
| Intel Centrino Advanced-N 6235                                       | 1        | 3.13%   |
| Edimax AC600 Wireless LAN USB Adapter                                | 1        | 3.13%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1        | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 110      | 52.13%  |
| Intel                 | 78       | 36.97%  |
| Broadcom              | 10       | 4.74%   |
| Qualcomm Atheros      | 7        | 3.32%   |
| D-Link System         | 2        | 0.95%   |
| Samsung Electronics   | 1        | 0.47%   |
| MediaTek              | 1        | 0.47%   |
| ICS Advent            | 1        | 0.47%   |
| 3Com                  | 1        | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 93       | 41.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 14       | 6.25%   |
| Intel I211 Gigabit Network Connection                                         | 13       | 5.8%    |
| Intel Ethernet Controller I226-V                                              | 10       | 4.46%   |
| Intel Ethernet Controller I225-V                                              | 9        | 4.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6        | 2.68%   |
| Intel 82576 Gigabit Network Connection                                        | 5        | 2.23%   |
| Intel I350 Gigabit Network Connection                                         | 4        | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4        | 1.79%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 1.34%   |
| Intel Ethernet Connection I217-LM                                             | 3        | 1.34%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 1.34%   |
| Intel 82578DC Gigabit Network Connection                                      | 3        | 1.34%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3        | 1.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.89%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 2        | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.89%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 0.89%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 0.89%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.89%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 0.89%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 0.89%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 0.89%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 0.89%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 0.89%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 0.89%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.89%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 0.89%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.45%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 0.45%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.45%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 0.45%   |
| Intel Ethernet Controller X550                                                | 1        | 0.45%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 0.45%   |
| Intel 82578DM Gigabit Network Connection                                      | 1        | 0.45%   |
| Intel 82575GB Gigabit Network Connection                                      | 1        | 0.45%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 168      | 85.28%  |
| WiFi     | 27       | 13.71%  |
| Modem    | 2        | 1.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 166      | 93.79%  |
| WiFi     | 11       | 6.21%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 53       | 30.64%  |
| 2     | 46       | 26.59%  |
| 4     | 35       | 20.23%  |
| 3     | 21       | 12.14%  |
| 5     | 10       | 5.78%   |
| 6     | 6        | 3.47%   |
| 8     | 1        | 0.58%   |
| 7     | 1        | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 158      | 90.8%   |
| Yes  | 16       | 9.2%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 42.86%  |
| Realtek Semiconductor   | 5        | 35.71%  |
| Cambridge Silicon Radio | 3        | 21.43%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Adapter                           | 5        | 35.71%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 21.43%  |
| Intel Bluetooth wireless interface                  | 2        | 14.29%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 7.14%   |
| Intel AX210 Bluetooth                               | 1        | 7.14%   |
| Intel AX201 Bluetooth                               | 1        | 7.14%   |
| Intel AX200 Bluetooth                               | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 115      | 62.5%   |
| AMD                                             | 41       | 22.28%  |
| Nvidia                                          | 19       | 10.33%  |
| C-Media Electronics                             | 6        | 3.26%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.54%   |
| KTMicro                                         | 1        | 0.54%   |
| Generalplus Technology                          | 1        | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 21       | 9.46%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11       | 4.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10       | 4.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 4.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10       | 4.5%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 10       | 4.5%    |
| Intel Jasper Lake HD Audio                                                 | 9        | 4.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 3.15%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 3.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 3.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6        | 2.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 2.7%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5        | 2.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 2.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4        | 1.8%    |
| Intel Haswell-ULT HD Audio Controller                                      | 4        | 1.8%    |
| Intel Broadwell-U Audio Controller                                         | 4        | 1.8%    |
| Intel 8 Series HD Audio Controller                                         | 4        | 1.8%    |
| AMD FCH Azalia Controller                                                  | 4        | 1.8%    |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 1.35%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.35%   |
| C-Media Electronics CM108 Audio Controller                                 | 3        | 1.35%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 3        | 1.35%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.35%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 3        | 1.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 1.35%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 1.35%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.35%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.9%    |
| Nvidia High Definition Audio Controller                                    | 2        | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 0.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.9%    |
| Intel Sunrise Point-LP HD Audio                                            | 2        | 0.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 0.9%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 0.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 45       | 23.81%  |
| Kingston            | 30       | 15.87%  |
| Smart               | 17       | 8.99%   |
| Unknown             | 12       | 6.35%   |
| Crucial             | 11       | 5.82%   |
| Samsung Electronics | 9        | 4.76%   |
| Micron Technology   | 8        | 4.23%   |
| Teikon              | 7        | 3.7%    |
| SK hynix            | 6        | 3.17%   |
| Corsair             | 6        | 3.17%   |
| A-DATA Technology   | 6        | 3.17%   |
| G.Skill             | 3        | 1.59%   |
| Unknown (ABCD)      | 2        | 1.06%   |
| Toshiba             | 2        | 1.06%   |
| Patriot             | 2        | 1.06%   |
| Hewlett-Packard     | 2        | 1.06%   |
| Unknown (8A02)      | 1        | 0.53%   |
| Unknown (0x5846)    | 1        | 0.53%   |
| Tigo                | 1        | 0.53%   |
| SK_Hynix            | 1        | 0.53%   |
| RZX                 | 1        | 0.53%   |
| PUSKILL             | 1        | 0.53%   |
| Nanya Technology    | 1        | 0.53%   |
| Multilaser          | 1        | 0.53%   |
| MemoWise            | 1        | 0.53%   |
| Lexar               | 1        | 0.53%   |
| Kreton              | 1        | 0.53%   |
| Kllisre             | 1        | 0.53%   |
| KingSpec            | 1        | 0.53%   |
| Kimtigo             | 1        | 0.53%   |
| Juhor               | 1        | 0.53%   |
| Hikvision           | 1        | 0.53%   |
| GLOWAY              | 1        | 0.53%   |
| Galaxy              | 1        | 0.53%   |
| CSX                 | 1        | 0.53%   |
| Atermiter           | 1        | 0.53%   |
| Apacer              | 1        | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown                                                           | 12       | 5.91%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s               | 5        | 2.46%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 4        | 1.97%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 3        | 1.48%   |
| Unknown RAM Module 4GB DIMM SDRAM                                 | 3        | 1.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 3        | 1.48%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 3        | 1.48%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 3        | 1.48%   |
| Unknown RAM Module 2GB DIMM DDR2                                  | 3        | 1.48%   |
| Unknown RAM Module 2GB DIMM                                       | 3        | 1.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                         | 2        | 0.99%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                              | 2        | 0.99%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                         | 2        | 0.99%   |
| Unknown RAM Module 1GB DIMM SDRAM                                 | 2        | 0.99%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 2        | 0.99%   |
| Teikon RAM TMTS8G58DFRBFKB-16 8GB SODIMM DDR3 1600MT/s            | 2        | 0.99%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s               | 2        | 0.99%   |
| Smart RAM SH564568FH8N0QHSCG 2GB DIMM DDR3 1333MT/s               | 2        | 0.99%   |
| Patriot RAM 2666 C16 Series 4GB DIMM DDR4 3000MT/s                | 2        | 0.99%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                         | 2        | 0.99%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                 | 2        | 0.99%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1866MT/s                 | 2        | 0.99%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s             | 2        | 0.99%   |
| Corsair RAM CMY16GX3M2A2400C11 8GB DIMM DDR3 2400MT/s             | 2        | 0.99%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                       | 2        | 0.99%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                              | 1        | 0.49%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                      | 1        | 0.49%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                      | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                          | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM 400MT/s                               | 1        | 0.49%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                      | 1        | 0.49%   |
| Unknown RAM Module 4096MB DIMM DDR2                               | 1        | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                        | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM SDRAM 1333MT/s                        | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                          | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM 800MT/s                               | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM 667MT/s                               | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                              | 1        | 0.49%   |
| Unknown RAM Module 2048MB DIMM SDRAM                              | 1        | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                      | 1        | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 67       | 41.36%  |
| DDR4    | 51       | 31.48%  |
| Unknown | 15       | 9.26%   |
| SDRAM   | 13       | 8.02%   |
| DDR2    | 12       | 7.41%   |
| LPDDR4  | 3        | 1.85%   |
| DDR5    | 1        | 0.62%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 125      | 77.64%  |
| SODIMM       | 34       | 21.12%  |
| Row Of Chips | 1        | 0.62%   |
| Chip         | 1        | 0.62%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 59       | 33.71%  |
| 4096  | 55       | 31.43%  |
| 2048  | 40       | 22.86%  |
| 16384 | 15       | 8.57%   |
| 1024  | 4        | 2.29%   |
| 32768 | 2        | 1.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 37       | 21.26%  |
| 1333    | 32       | 18.39%  |
| 2400    | 20       | 11.49%  |
| Unknown | 19       | 10.92%  |
| 2667    | 15       | 8.62%   |
| 3200    | 12       | 6.9%    |
| 800     | 10       | 5.75%   |
| 2133    | 6        | 3.45%   |
| 2666    | 4        | 2.3%    |
| 1866    | 3        | 1.72%   |
| 3000    | 2        | 1.15%   |
| 1867    | 2        | 1.15%   |
| 1067    | 2        | 1.15%   |
| 1066    | 2        | 1.15%   |
| 667     | 2        | 1.15%   |
| 400     | 2        | 1.15%   |
| 4800    | 1        | 0.57%   |
| 4000    | 1        | 0.57%   |
| 2933    | 1        | 0.57%   |
| 333     | 1        | 0.57%   |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 2        | 40%     |
| Z-Star Microelectronics | 1        | 20%     |
| Chicony Electronics     | 1        | 20%     |
| Aveo Technology         | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera  | 1        | 20%     |
| Logitech Webcam C270        | 1        | 20%     |
| Logitech HD Pro Webcam C920 | 1        | 20%     |
| Chicony Integrated Camera   | 1        | 20%     |
| Aveo USB2.0 Camera          | 1        | 20%     |

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
| 1     | 87       | 51.18%  |
| 0     | 68       | 40%     |
| 2     | 12       | 7.06%   |
| 3     | 2        | 1.18%   |
| 4     | 1        | 0.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 92       | 82.88%  |
| Net/wireless             | 9        | 8.11%   |
| Sound                    | 4        | 3.6%    |
| Bluetooth                | 3        | 2.7%    |
| Net/ethernet             | 1        | 0.9%    |
| Graphics card            | 1        | 0.9%    |
| Firewire controller      | 1        | 0.9%    |

