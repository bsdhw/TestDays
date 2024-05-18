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

Total: 308

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | DH61BR G32662-203           | [f9ebf93574](https://bsd-hardware.info/?probe=f9ebf93574) | May 06, 2024 |
| Intel         | YC-4L-002                   | [ac058ece5c](https://bsd-hardware.info/?probe=ac058ece5c) | Apr 30, 2024 |
| Dell          | 04YP6J A00                  | [92b5c39349](https://bsd-hardware.info/?probe=92b5c39349) | Apr 29, 2024 |
| ASRock        | Z87M Pro4                   | [91a487bad5](https://bsd-hardware.info/?probe=91a487bad5) | Apr 29, 2024 |
| ASUSTek       | J1800I-C/BR                 | [28856a768f](https://bsd-hardware.info/?probe=28856a768f) | Apr 23, 2024 |
| ECS           | KBLU-MINI                   | [0380406242](https://bsd-hardware.info/?probe=0380406242) | Apr 18, 2024 |
| Intel         | DQ77KB AAG81483-501         | [e79deb66c2](https://bsd-hardware.info/?probe=e79deb66c2) | Apr 17, 2024 |
| Unknown       | Unknown                     | [23cc24ddfc](https://bsd-hardware.info/?probe=23cc24ddfc) | Apr 13, 2024 |
| Unknown       | Unknown                     | [e72e2a9dae](https://bsd-hardware.info/?probe=e72e2a9dae) | Apr 12, 2024 |
| Supermicro    | 92.510.02134-3              | [e0b08a8502](https://bsd-hardware.info/?probe=e0b08a8502) | Apr 05, 2024 |
| Supermicro    | 92.510.02134-3              | [8f5fb5245e](https://bsd-hardware.info/?probe=8f5fb5245e) | Apr 05, 2024 |
| Dell          | 06HR05 A00                  | [9505b5cf4f](https://bsd-hardware.info/?probe=9505b5cf4f) | Apr 02, 2024 |
| Intel         | BOX-J41L4A V3.01            | [8e31084435](https://bsd-hardware.info/?probe=8e31084435) | Mar 29, 2024 |
| CNCTION-IA... | Unknown                     | [42996aca85](https://bsd-hardware.info/?probe=42996aca85) | Mar 16, 2024 |
| Unknown       | Unknown                     | [157a2cbf6c](https://bsd-hardware.info/?probe=157a2cbf6c) | Mar 15, 2024 |
| Intel         | DQ77KB AAG81483-501         | [bb5384ee3e](https://bsd-hardware.info/?probe=bb5384ee3e) | Mar 14, 2024 |
| LG Electro... | R590-P.BE54P1               | [120ec3afe6](https://bsd-hardware.info/?probe=120ec3afe6) | Mar 09, 2024 |
| Intel         | ZC-R40-4125                 | [6f76935200](https://bsd-hardware.info/?probe=6f76935200) | Mar 05, 2024 |
| ASUSTek       | PRIME A520M-E               | [b0e5a68883](https://bsd-hardware.info/?probe=b0e5a68883) | Mar 03, 2024 |
| ASRock        | J4005B-ITX                  | [ffcfdde6b9](https://bsd-hardware.info/?probe=ffcfdde6b9) | Feb 29, 2024 |
| Unknown       | Unknown                     | [96711959a2](https://bsd-hardware.info/?probe=96711959a2) | Feb 20, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [fa2107c718](https://bsd-hardware.info/?probe=fa2107c718) | Feb 11, 2024 |
| Intel         | DQ77KB AAG81483-501         | [96f998dae3](https://bsd-hardware.info/?probe=96f998dae3) | Feb 09, 2024 |
| ASUSTek       | Z97M-PLUS/BR                | [cb6b8e5aef](https://bsd-hardware.info/?probe=cb6b8e5aef) | Feb 02, 2024 |
| HP            | s5-1210br                   | [9ce94bc2b7](https://bsd-hardware.info/?probe=9ce94bc2b7) | Jan 19, 2024 |
| Unknown       | Unknown                     | [dc8b338a3e](https://bsd-hardware.info/?probe=dc8b338a3e) | Jan 19, 2024 |
| GoWin Solu... | R86S                        | [43c637977a](https://bsd-hardware.info/?probe=43c637977a) | Jan 19, 2024 |
| Techvision    | TVI7309X B0                 | [b9e259b247](https://bsd-hardware.info/?probe=b9e259b247) | Jan 19, 2024 |
| Unknown       | Unknown                     | [f516302dc5](https://bsd-hardware.info/?probe=f516302dc5) | Jan 13, 2024 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [2fb631cb20](https://bsd-hardware.info/?probe=2fb631cb20) | Jan 13, 2024 |
| CNCTION-IA... | Unknown                     | [52a8efdb73](https://bsd-hardware.info/?probe=52a8efdb73) | Jan 07, 2024 |
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
| Gigabyte      | B250M-Gaming 3-CF           | [cace71018f](https://bsd-hardware.info/?probe=cace71018f) | May 11, 2023 |
| Gigabyte      | H61M-DS2H                   | [e1856048c0](https://bsd-hardware.info/?probe=e1856048c0) | May 10, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [4353bb0195](https://bsd-hardware.info/?probe=4353bb0195) | May 09, 2023 |
| Unknown       | Unknown                     | [ed836ce6e5](https://bsd-hardware.info/?probe=ed836ce6e5) | May 05, 2023 |
| Unknown       | Unknown                     | [15c2e0790b](https://bsd-hardware.info/?probe=15c2e0790b) | Apr 27, 2023 |
| Intel         | Q3XXG4-P V1.0               | [b46f671e20](https://bsd-hardware.info/?probe=b46f671e20) | Apr 25, 2023 |
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
| helloSystem 0.7.0    | 13       | 5.24%   |
| helloSystem 0.8.1    | 12       | 4.84%   |
| OPNsense 23.1.11     | 10       | 4.03%   |
| helloSystem 0.8.0    | 7        | 2.82%   |
| OPNsense 23.1.7      | 6        | 2.42%   |
| OPNsense 23.1.5      | 6        | 2.42%   |
| OPNsense 22.1.10     | 6        | 2.42%   |
| OPNsense 20.7.8      | 6        | 2.42%   |
| OPNsense 23.7.12     | 5        | 2.02%   |
| OPNsense 23.7.10     | 5        | 2.02%   |
| OPNsense 23.1.9      | 5        | 2.02%   |
| OPNsense 22.7.5      | 5        | 2.02%   |
| OPNsense 21.1.3      | 5        | 2.02%   |
| OPNsense 21.1        | 5        | 2.02%   |
| helloSystem 0.4.0    | 5        | 2.02%   |
| OPNsense 24.1.5      | 4        | 1.61%   |
| OPNsense 23.7.9      | 4        | 1.61%   |
| OPNsense 23.1        | 4        | 1.61%   |
| OPNsense 22.7.8      | 4        | 1.61%   |
| OPNsense 22.7.4      | 4        | 1.61%   |
| OPNsense 21.1.1      | 4        | 1.61%   |
| helloSystem 0.6.0    | 4        | 1.61%   |
| helloSystem 0.5.0    | 4        | 1.61%   |
| FreeBSD 14.0-CURRENT | 4        | 1.61%   |
| OPNsense 24.1.6      | 3        | 1.21%   |
| OPNsense 23.7.11     | 3        | 1.21%   |
| OPNsense 23.1.1      | 3        | 1.21%   |
| OPNsense 22.7.6      | 3        | 1.21%   |
| OPNsense 22.1.8      | 3        | 1.21%   |
| OPNsense 21.7.7      | 3        | 1.21%   |
| OPNsense 21.7.1      | 3        | 1.21%   |
| OPNsense 21.1.9      | 3        | 1.21%   |
| OPNsense 21.1.6      | 3        | 1.21%   |
| OPNsense 21.1.4      | 3        | 1.21%   |
| OPNsense 24.1.3      | 2        | 0.81%   |
| OPNsense 24.1.2      | 2        | 0.81%   |
| OPNsense 24.1.1      | 2        | 0.81%   |
| OPNsense 23.7.6      | 2        | 0.81%   |
| OPNsense 23.7.2      | 2        | 0.81%   |
| OPNsense 23.7        | 2        | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 109      | 58.29%  |
| helloSystem | 41       | 21.93%  |
| FreeBSD     | 23       | 12.3%   |
| OpenBSD     | 4        | 2.14%   |
| GhostBSD    | 3        | 1.6%    |
| pfSense     | 2        | 1.07%   |
| NomadBSD    | 2        | 1.07%   |
| TrueNAS     | 1        | 0.53%   |
| NetBSD      | 1        | 0.53%   |
| FreeNAS     | 1        | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 183      | 98.92%  |
| i386  | 2        | 1.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 114      | 60.64%  |
| helloDesktop | 45       | 23.94%  |
| KDE5         | 9        | 4.79%   |
| XFCE         | 5        | 2.66%   |
| Openbox      | 4        | 2.13%   |
| MATE         | 4        | 2.13%   |
| i3           | 2        | 1.06%   |
| X-Cinnamon   | 1        | 0.53%   |
| Window Maker | 1        | 0.53%   |
| TWM          | 1        | 0.53%   |
| GNOME        | 1        | 0.53%   |
| AwesomeWM    | 1        | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 117      | 63.24%  |
| X11     | 68       | 36.76%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 126      | 67.38%  |
| SLiM    | 44       | 23.53%  |
| SDDM    | 9        | 4.81%   |
| LightDM | 4        | 2.14%   |
| GDM     | 3        | 1.6%    |
| XDM     | 1        | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 115      | 60.85%  |
| en_US            | 30       | 15.87%  |
| pt_BR            | 19       | 10.05%  |
| C                | 15       | 7.94%   |
| fr_FR            | 5        | 2.65%   |
| pt               | 3        | 1.59%   |
| fr               | 1        | 0.53%   |
| en_US.ISO8859-15 | 1        | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 158      | 82.72%  |
| BIOS | 33       | 17.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 91       | 47.64%  |
| Zfs    | 76       | 39.79%  |
| Cd9660 | 20       | 10.47%  |
| Ffs    | 4        | 2.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 170      | 89.47%  |
| MBR     | 18       | 9.47%   |
| Unknown | 2        | 1.05%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUSTek Computer        | 37       | 20%     |
| Unknown                 | 25       | 13.51%  |
| Dell                    | 22       | 11.89%  |
| Intel                   | 21       | 11.35%  |
| Gigabyte Technology     | 13       | 7.03%   |
| Hewlett-Packard         | 10       | 5.41%   |
| ASRock                  | 8        | 4.32%   |
| Techvision              | 4        | 2.16%   |
| MSI                     | 4        | 2.16%   |
| Lenovo                  | 4        | 2.16%   |
| Positivo                | 3        | 1.62%   |
| Pegatron                | 3        | 1.62%   |
| PCWare                  | 3        | 1.62%   |
| Itautec                 | 3        | 1.62%   |
| ECS                     | 3        | 1.62%   |
| Biostar                 | 2        | 1.08%   |
| YANYU                   | 1        | 0.54%   |
| Yanling                 | 1        | 0.54%   |
| ULTRATOP                | 1        | 0.54%   |
| T-bao                   | 1        | 0.54%   |
| Supermicro              | 1        | 0.54%   |
| Soyo                    | 1        | 0.54%   |
| Semp Toshiba            | 1        | 0.54%   |
| Procomp Ind. Eletronica | 1        | 0.54%   |
| maiyunda                | 1        | 0.54%   |
| LG Electronics          | 1        | 0.54%   |
| KLLISRE                 | 1        | 0.54%   |
| HC                      | 1        | 0.54%   |
| GoWin Solution          | 1        | 0.54%   |
| GALAX                   | 1        | 0.54%   |
| ECS-USA                 | 1        | 0.54%   |
| Daten Tecnologia        | 1        | 0.54%   |
| CNCTION-IAF-E3845       | 1        | 0.54%   |
| ChangWang               | 1        | 0.54%   |
| AZW                     | 1        | 0.54%   |
| AMI                     | 1        | 0.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 26       | 14.05%  |
| Intel Q3XXG4-P V1.0                | 8        | 4.32%   |
| ASUS All Series                    | 6        | 3.24%   |
| Techvision TVI7309X                | 4        | 2.16%   |
| Pegatron IPM41-D3                  | 2        | 1.08%   |
| Intel H81                          | 2        | 1.08%   |
| Intel H55                          | 2        | 1.08%   |
| Gigabyte H61M-S2-B3                | 2        | 1.08%   |
| Dell OptiPlex 7040                 | 2        | 1.08%   |
| Dell OptiPlex 3020                 | 2        | 1.08%   |
| ASUS TUF Gaming B550M-PLUS         | 2        | 1.08%   |
| ASUS PRIME B450M-GAMING/BR         | 2        | 1.08%   |
| ASUS PRIME A520M-E                 | 2        | 1.08%   |
| ASUS P8H61-M LX3 PLUS R2.0         | 2        | 1.08%   |
| ASUS P5G41T-M LX2/BR               | 2        | 1.08%   |
| ASUS M5A78L-M LX/BR                | 2        | 1.08%   |
| ASUS A88XM-A                       | 2        | 1.08%   |
| ASRock J4005B-ITX                  | 2        | 1.08%   |
| YANYU N39SL                        | 1        | 0.54%   |
| Yanling NS-1U8L                    | 1        | 0.54%   |
| ULTRATOP C2017-LIVA-ZE             | 1        | 0.54%   |
| T-bao MINI PC                      | 1        | 0.54%   |
| Supermicro 92.510.02134-3          | 1        | 0.54%   |
| Soyo SY-YL B550M                   | 1        | 0.54%   |
| Semp Toshiba STI                   | 1        | 0.54%   |
| Procomp Ind. Eletronica G41MXE     | 1        | 0.54%   |
| Positivo Positivo Master D610      | 1        | 0.54%   |
| Positivo POS-PIQ77CL               | 1        | 0.54%   |
| Positivo POS-EAA75DE               | 1        | 0.54%   |
| Pegatron IPMIP-GS                  | 1        | 0.54%   |
| PCWare PW-945GCX                   | 1        | 0.54%   |
| PCWare IPX1800G2                   | 1        | 0.54%   |
| PCWare IPMH81G1                    | 1        | 0.54%   |
| MSI U-100                          | 1        | 0.54%   |
| MSI MS-7877                        | 1        | 0.54%   |
| MSI MS-7698                        | 1        | 0.54%   |
| MSI MS-7529                        | 1        | 0.54%   |
| maiyunda www.maiyunda.com          | 1        | 0.54%   |
| LG R590-P.BE54P1                   | 1        | 0.54%   |
| Lenovo ThinkCentre M93p 10A9000WBP | 1        | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 26       | 14.05%  |
| Dell OptiPlex                  | 14       | 7.57%   |
| Intel Q3XXG4-P                 | 8        | 4.32%   |
| ASUS All                       | 6        | 3.24%   |
| ASUS PRIME                     | 5        | 2.7%    |
| Techvision TVI7309X            | 4        | 2.16%   |
| HP ProLiant                    | 4        | 2.16%   |
| Dell Vostro                    | 4        | 2.16%   |
| Lenovo ThinkCentre             | 3        | 1.62%   |
| Itautec Infoway                | 3        | 1.62%   |
| Dell Inspiron                  | 3        | 1.62%   |
| ASUS TUF                       | 3        | 1.62%   |
| ASUS P8H61-M                   | 3        | 1.62%   |
| ASUS P5G41T-M                  | 3        | 1.62%   |
| ASUS M5A78L-M                  | 3        | 1.62%   |
| Pegatron IPM41-D3              | 2        | 1.08%   |
| Intel H81                      | 2        | 1.08%   |
| Intel H55                      | 2        | 1.08%   |
| HP Compaq                      | 2        | 1.08%   |
| Gigabyte H61M-S2-B3            | 2        | 1.08%   |
| ASUS A88XM-A                   | 2        | 1.08%   |
| ASRock J4005B-ITX              | 2        | 1.08%   |
| YANYU N39SL                    | 1        | 0.54%   |
| Yanling NS-1U8L                | 1        | 0.54%   |
| ULTRATOP C2017-LIVA-ZE         | 1        | 0.54%   |
| T-bao MINI                     | 1        | 0.54%   |
| Supermicro 92.510.02134-3      | 1        | 0.54%   |
| Soyo SY-YL                     | 1        | 0.54%   |
| Semp Toshiba STI               | 1        | 0.54%   |
| Procomp Ind. Eletronica G41MXE | 1        | 0.54%   |
| Positivo Positivo              | 1        | 0.54%   |
| Positivo POS-PIQ77CL           | 1        | 0.54%   |
| Positivo POS-EAA75DE           | 1        | 0.54%   |
| Pegatron IPMIP-GS              | 1        | 0.54%   |
| PCWare PW-945GCX               | 1        | 0.54%   |
| PCWare IPX1800G2               | 1        | 0.54%   |
| PCWare IPMH81G1                | 1        | 0.54%   |
| MSI U-100                      | 1        | 0.54%   |
| MSI MS-7877                    | 1        | 0.54%   |
| MSI MS-7698                    | 1        | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2022    | 25       | 13.51%  |
| 2016    | 21       | 11.35%  |
| 2013    | 18       | 9.73%   |
| 2010    | 15       | 8.11%   |
| 2018    | 12       | 6.49%   |
| 2017    | 10       | 5.41%   |
| 2011    | 10       | 5.41%   |
| 2021    | 9        | 4.86%   |
| 2014    | 9        | 4.86%   |
| 2012    | 9        | 4.86%   |
| 2023    | 8        | 4.32%   |
| 2020    | 8        | 4.32%   |
| 2019    | 8        | 4.32%   |
| 2009    | 8        | 4.32%   |
| 2008    | 8        | 4.32%   |
| 2015    | 4        | 2.16%   |
| 2007    | 2        | 1.08%   |
| Unknown | 1        | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 185      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 185      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 77       | 40.1%   |
| 4.01-8.0    | 56       | 29.17%  |
| 16.01-24.0  | 36       | 18.75%  |
| 32.01-64.0  | 9        | 4.69%   |
| 2.01-3.0    | 9        | 4.69%   |
| 64.01-256.0 | 3        | 1.56%   |
| 24.01-32.0  | 2        | 1.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 111      | 57.22%  |
| 0.51-1.0   | 54       | 27.84%  |
| 1.01-2.0   | 19       | 9.79%   |
| 2.01-3.0   | 5        | 2.58%   |
| 4.01-8.0   | 2        | 1.03%   |
| 16.01-24.0 | 1        | 0.52%   |
| 8.01-16.0  | 1        | 0.52%   |
| Unknown    | 1        | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 133      | 68.91%  |
| 2      | 20       | 10.36%  |
| 0      | 20       | 10.36%  |
| 3      | 10       | 5.18%   |
| 4      | 5        | 2.59%   |
| 5      | 3        | 1.55%   |
| 7      | 1        | 0.52%   |
| 6      | 1        | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 150      | 80.21%  |
| Yes       | 37       | 19.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 184      | 99.46%  |
| No        | 1        | 0.54%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 155      | 83.78%  |
| Yes       | 30       | 16.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 168      | 90.81%  |
| Yes       | 17       | 9.19%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Brazil  | 185      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Sao Paulo                 | 16       | 7.69%   |
| Rio de Janeiro            | 13       | 6.25%   |
| SГЈo Paulo              | 12       | 5.77%   |
| Sao José dos Campos      | 6        | 2.88%   |
| Porto Alegre              | 6        | 2.88%   |
| Jaraguá do Sul           | 6        | 2.88%   |
| Curitiba                  | 6        | 2.88%   |
| Osasco                    | 4        | 1.92%   |
| Joinville                 | 4        | 1.92%   |
| Campinas                  | 4        | 1.92%   |
| SÃ£o Paulo              | 3        | 1.44%   |
| Salvador                  | 3        | 1.44%   |
| Novo Hamburgo             | 3        | 1.44%   |
| Brasília                 | 3        | 1.44%   |
| Blumenau                  | 3        | 1.44%   |
| Belo Horizonte            | 3        | 1.44%   |
| Sorocaba                  | 2        | 0.96%   |
| Sao Leopoldo              | 2        | 0.96%   |
| Sao Jose do Rio Preto     | 2        | 0.96%   |
| Sao Bernardo do Campo     | 2        | 0.96%   |
| RondonГіpolis           | 2        | 0.96%   |
| Rio Claro                 | 2        | 0.96%   |
| Pirapora                  | 2        | 0.96%   |
| Maringá                  | 2        | 0.96%   |
| Londrina                  | 2        | 0.96%   |
| Jaboatao dos Guararapes   | 2        | 0.96%   |
| Itaperuna                 | 2        | 0.96%   |
| Guarulhos                 | 2        | 0.96%   |
| Fortaleza                 | 2        | 0.96%   |
| Cruzeiro do Sul           | 2        | 0.96%   |
| BrasÃ­lia               | 2        | 0.96%   |
| VitГіria da Conquista   | 1        | 0.48%   |
| Valparaiso de Goias       | 1        | 0.48%   |
| Urupes                    | 1        | 0.48%   |
| Unai                      | 1        | 0.48%   |
| Uberaba                   | 1        | 0.48%   |
| Timbo                     | 1        | 0.48%   |
| Teresina                  | 1        | 0.48%   |
| Taubate                   | 1        | 0.48%   |
| SГЈo JosГ© dos Campos | 1        | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 38       | 50     | 17.12%  |
| Kingston            | 38       | 62     | 17.12%  |
| Seagate             | 33       | 64     | 14.86%  |
| Samsung Electronics | 22       | 33     | 9.91%   |
| SanDisk             | 12       | 16     | 5.41%   |
| China               | 9        | 14     | 4.05%   |
| Hoodisk             | 8        | 8      | 3.6%    |
| Toshiba             | 7        | 8      | 3.15%   |
| Silicon Motion      | 6        | 7      | 2.7%    |
| A-DATA Technology   | 6        | 7      | 2.7%    |
| KingSpec            | 5        | 8      | 2.25%   |
| Crucial             | 5        | 8      | 2.25%   |
| XrayDisk            | 4        | 4      | 1.8%    |
| Hitachi             | 3        | 7      | 1.35%   |
| Fanxiang            | 3        | 4      | 1.35%   |
| PNY                 | 2        | 2      | 0.9%    |
| NTC                 | 2        | 2      | 0.9%    |
| HGST                | 2        | 3      | 0.9%    |
| Gigabyte Technology | 2        | 5      | 0.9%    |
| Teelkoou            | 1        | 1      | 0.45%   |
| tecmiyo             | 1        | 1      | 0.45%   |
| Silicon             | 1        | 1      | 0.45%   |
| NVMe                | 1        | 2      | 0.45%   |
| Netac               | 1        | 1      | 0.45%   |
| Maxtor              | 1        | 1      | 0.45%   |
| MACROVIP            | 1        | 1      | 0.45%   |
| Kston               | 1        | 1      | 0.45%   |
| Intel               | 1        | 2      | 0.45%   |
| Indilinx            | 1        | 2      | 0.45%   |
| Hewlett-Packard     | 1        | 1      | 0.45%   |
| Faspeed             | 1        | 1      | 0.45%   |
| Drevo               | 1        | 6      | 0.45%   |
| Corsair             | 1        | 1      | 0.45%   |
| Colorful            | 1        | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB         | 13       | 5.33%   |
| Kingston SA400S37120G 120GB         | 9        | 3.69%   |
| Seagate ST500DM002-1BD142 500GB     | 7        | 2.87%   |
| SanDisk SSD PLUS 120GB              | 6        | 2.46%   |
| Kingston SA400S37480G 480GB         | 6        | 2.46%   |
| Hoodisk SSD 64GB                    | 6        | 2.46%   |
| Samsung HD322HJ 320GB               | 5        | 2.05%   |
| Seagate ST1000DM010-2EP102 1TB      | 4        | 1.64%   |
| WDC WD10EZEX-00RKKA0 1TB            | 3        | 1.23%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3        | 1.23%   |
| Seagate ST4000DM000-1F2168 4TB      | 3        | 1.23%   |
| Samsung HD502HJ 500GB               | 3        | 1.23%   |
| Samsung HD103SJ 1TB                 | 3        | 1.23%   |
| Crucial CT120BX500SSD1 120GB        | 3        | 1.23%   |
| A-DATA SU630 240GB                  | 3        | 1.23%   |
| XrayDisk 1TB SSD                    | 2        | 0.82%   |
| WDC WDS120G2G0A-00JH30 120GB        | 2        | 0.82%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 2        | 0.82%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 2        | 0.82%   |
| WDC WD2500BEVT-75ZCT2 250GB         | 2        | 0.82%   |
| Silicon Motion NVME SSD 128GB       | 2        | 0.82%   |
| Seagate ST2000DM006-2DM164 2TB      | 2        | 0.82%   |
| SanDisk SSD PLUS 240GB              | 2        | 0.82%   |
| SanDisk SDSSDA240G 240GB            | 2        | 0.82%   |
| SanDisk SDSSDA120G 120GB            | 2        | 0.82%   |
| Samsung HD161HJ 160GB               | 2        | 0.82%   |
| Samsung HD081GJ 80GB                | 2        | 0.82%   |
| PNY CS900 120GB SSD                 | 2        | 0.82%   |
| Kingston SUV400S37120G 120GB        | 2        | 0.82%   |
| Kingston SH103S3240G 240GB          | 2        | 0.82%   |
| Hoodisk SSD 32GB                    | 2        | 0.82%   |
| Gigabyte GP-GSTFS31120GNTD 120GB    | 2        | 0.82%   |
| China SATA SSD 120GB                | 2        | 0.82%   |
| China IM128-P130 128GB              | 2        | 0.82%   |
| A-DATA SU650 120GB                  | 2        | 0.82%   |
| XrayDisk SSD 240GB                  | 1        | 0.41%   |
| XrayDisk SSD 128GB                  | 1        | 0.41%   |
| WDC WDS120G2G0B-00EPW0 120GB        | 1        | 0.41%   |
| WDC WD800JD-75MSA3 80GB             | 1        | 0.41%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 36       | 46     | 35.64%  |
| Seagate             | 33       | 64     | 32.67%  |
| Samsung Electronics | 18       | 25     | 17.82%  |
| Toshiba             | 7        | 8      | 6.93%   |
| Hitachi             | 3        | 7      | 2.97%   |
| NVMe                | 1        | 2      | 0.99%   |
| Maxtor              | 1        | 1      | 0.99%   |
| HGST                | 1        | 2      | 0.99%   |
| Hewlett-Packard     | 1        | 1      | 0.99%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 35       | 59     | 32.41%  |
| SanDisk             | 12       | 16     | 11.11%  |
| China               | 9        | 14     | 8.33%   |
| Hoodisk             | 8        | 8      | 7.41%   |
| A-DATA Technology   | 6        | 7      | 5.56%   |
| KingSpec            | 5        | 8      | 4.63%   |
| Crucial             | 5        | 8      | 4.63%   |
| XrayDisk            | 4        | 4      | 3.7%    |
| WDC                 | 3        | 4      | 2.78%   |
| Samsung Electronics | 2        | 3      | 1.85%   |
| PNY                 | 2        | 2      | 1.85%   |
| NTC                 | 2        | 2      | 1.85%   |
| Gigabyte Technology | 2        | 5      | 1.85%   |
| Teelkoou            | 1        | 1      | 0.93%   |
| tecmiyo             | 1        | 1      | 0.93%   |
| Silicon             | 1        | 1      | 0.93%   |
| Netac               | 1        | 1      | 0.93%   |
| MACROVIP            | 1        | 1      | 0.93%   |
| Kston               | 1        | 1      | 0.93%   |
| Intel               | 1        | 2      | 0.93%   |
| Indilinx            | 1        | 2      | 0.93%   |
| HGST                | 1        | 1      | 0.93%   |
| Faspeed             | 1        | 1      | 0.93%   |
| Fanxiang            | 1        | 1      | 0.93%   |
| Drevo               | 1        | 6      | 0.93%   |
| Corsair             | 1        | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 98       | 160    | 50%     |
| HDD  | 84       | 156    | 42.86%  |
| NVMe | 14       | 19     | 7.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 153      | 316    | 91.62%  |
| NVMe | 14       | 19     | 8.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 142      | 244    | 78.89%  |
| 0.51-1.0   | 22       | 37     | 12.22%  |
| 1.01-2.0   | 12       | 25     | 6.67%   |
| 3.01-4.0   | 4        | 10     | 2.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 74       | 36.82%  |
| 1-20           | 37       | 18.41%  |
| 251-500        | 31       | 15.42%  |
| 51-100         | 26       | 12.94%  |
| 21-50          | 17       | 8.46%   |
| 501-1000       | 9        | 4.48%   |
| 1001-2000      | 3        | 1.49%   |
| 2001-3000      | 2        | 1%      |
| More than 3000 | 1        | 0.5%    |
| Unknown        | 1        | 0.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 168      | 89.84%  |
| 21-50     | 10       | 5.35%   |
| 101-250   | 3        | 1.6%    |
| 501-1000  | 2        | 1.07%   |
| 2001-3000 | 1        | 0.53%   |
| 1001-2000 | 1        | 0.53%   |
| 51-100    | 1        | 0.53%   |
| Unknown   | 1        | 0.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Desktops | Drives | Percent |
|-------------------------------------------|----------|--------|---------|
| Samsung Electronics HD322HJ 320GB         | 4        | 5      | 6.15%   |
| Seagate ST500DM002-1BD142 500GB           | 3        | 4      | 4.62%   |
| WDC WD10EZEX-00RKKA0 1TB                  | 2        | 2      | 3.08%   |
| Samsung Electronics HD161HJ 160GB         | 2        | 2      | 3.08%   |
| XrayDisk SSD 240GB                        | 1        | 1      | 1.54%   |
| WDC WD5000LPVX-22V0TT0 500GB              | 1        | 1      | 1.54%   |
| WDC WD5000AVVS-63H0B1 500GB               | 1        | 1      | 1.54%   |
| WDC WD5000AAKX-00U6AA0 500GB              | 1        | 1      | 1.54%   |
| WDC WD5000AAKX-00ERMA0 500GB              | 1        | 1      | 1.54%   |
| WDC WD5000AAKS-08V0A0 500GB               | 1        | 1      | 1.54%   |
| WDC WD5000AAKS-00UU3A0 500GB              | 1        | 1      | 1.54%   |
| WDC WD3200LPVX-22V0TT0 320GB              | 1        | 1      | 1.54%   |
| WDC WD3200BEVT-00A0RT0 233GB              | 1        | 1      | 1.54%   |
| WDC WD3200AAKS-00UU3A0 320GB              | 1        | 1      | 1.54%   |
| WDC WD3200AAJS-56M0A0 320GB               | 1        | 1      | 1.54%   |
| WDC WD3200AAJS-00YZCA0 320GB              | 1        | 1      | 1.54%   |
| WDC WD2502ABYS-18B7A0 250GB               | 1        | 1      | 1.54%   |
| WDC WD2500AAJS-75M0A0 250GB               | 1        | 1      | 1.54%   |
| WDC WD10PURX-64E5EY0 1TB                  | 1        | 1      | 1.54%   |
| WDC WD10EADS-65M2BX 1TB                   | 1        | 1      | 1.54%   |
| Toshiba MQ01ABD050 500GB                  | 1        | 1      | 1.54%   |
| Toshiba MK8052GSX 80GB                    | 1        | 1      | 1.54%   |
| Toshiba MK1255GSX H 120GB                 | 1        | 1      | 1.54%   |
| tecmiyo SSD MSATA 64GB                    | 1        | 1      | 1.54%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB | 1        | 1      | 1.54%   |
| Seagate ST9320325AS 320GB                 | 1        | 1      | 1.54%   |
| Seagate ST9160314AS 160GB                 | 1        | 1      | 1.54%   |
| Seagate ST500LT012-9WS142 500GB           | 1        | 2      | 1.54%   |
| Seagate ST500LM021-1KJ152 500GB           | 1        | 1      | 1.54%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1        | 1      | 1.54%   |
| Seagate ST500DM002-1BC142 500GB           | 1        | 1      | 1.54%   |
| Seagate ST3250310AS 250GB                 | 1        | 1      | 1.54%   |
| Seagate ST320LM001 HN-M320MBB 320GB       | 1        | 1      | 1.54%   |
| Seagate ST2000DM006-2DM164 2TB            | 1        | 1      | 1.54%   |
| Seagate ST2000DM001-1E6164 2TB            | 1        | 1      | 1.54%   |
| Seagate ST2000DL003-9VT166 2TB            | 1        | 9      | 1.54%   |
| SanDisk SSD PLUS 240 GB                   | 1        | 1      | 1.54%   |
| Samsung Electronics HM320II 320GB         | 1        | 2      | 1.54%   |
| Samsung Electronics HD642JJ 640GB         | 1        | 1      | 1.54%   |
| Samsung Electronics HD502HJ 500GB         | 1        | 1      | 1.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 17     | 24.19%  |
| Seagate             | 14       | 24     | 22.58%  |
| Samsung Electronics | 11       | 14     | 17.74%  |
| Toshiba             | 3        | 3      | 4.84%   |
| Kingston            | 3        | 4      | 4.84%   |
| KingSpec            | 3        | 4      | 4.84%   |
| Hitachi             | 3        | 7      | 4.84%   |
| XrayDisk            | 1        | 1      | 1.61%   |
| tecmiyo             | 1        | 1      | 1.61%   |
| Silicon Motion      | 1        | 1      | 1.61%   |
| SanDisk             | 1        | 1      | 1.61%   |
| Netac               | 1        | 1      | 1.61%   |
| Maxtor              | 1        | 1      | 1.61%   |
| HGST                | 1        | 1      | 1.61%   |
| Corsair             | 1        | 1      | 1.61%   |
| China               | 1        | 1      | 1.61%   |
| A-DATA Technology   | 1        | 1      | 1.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 17     | 31.91%  |
| Seagate             | 14       | 24     | 29.79%  |
| Samsung Electronics | 11       | 14     | 23.4%   |
| Toshiba             | 3        | 3      | 6.38%   |
| Hitachi             | 3        | 7      | 6.38%   |
| Maxtor              | 1        | 1      | 2.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 43       | 66     | 74.14%  |
| SSD  | 14       | 16     | 24.14%  |
| NVMe | 1        | 1      | 1.72%   |

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
| Works    | 129      | 239    | 66.84%  |
| Malfunc  | 55       | 83     | 28.5%   |
| Detected | 7        | 10     | 3.63%   |
| Failed   | 2        | 3      | 1.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 150      | 71.77%  |
| AMD                           | 31       | 14.83%  |
| Silicon Motion                | 10       | 4.78%   |
| Kingston Technology Company   | 5        | 2.39%   |
| Samsung Electronics           | 2        | 0.96%   |
| Nvidia                        | 2        | 0.96%   |
| JMicron Technology            | 2        | 0.96%   |
| SK hynix                      | 1        | 0.48%   |
| Realtek Semiconductor         | 1        | 0.48%   |
| MAXIO Technology (Hangzhou)   | 1        | 0.48%   |
| Integrated Technology Express | 1        | 0.48%   |
| Hewlett-Packard               | 1        | 0.48%   |
| ASMedia Technology            | 1        | 0.48%   |
| Adaptec                       | 1        | 0.48%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 23       | 8.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 15       | 5.81%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 5.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 12       | 4.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 4.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 10       | 3.88%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 9        | 3.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9        | 3.49%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 3.49%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 8        | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 3.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 2.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 2.71%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 1.94%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 1.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4        | 1.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4        | 1.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.55%   |
| Intel unknown                                                                           | 3        | 1.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.16%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 1.16%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 1.16%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 1.16%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.78%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.78%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2        | 0.78%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.78%   |
| AMD FCH SATA Controller D                                                               | 2        | 0.78%   |
| SK hynix BC511 NVMe SSD                                                                 | 1        | 0.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.39%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 1        | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 131      | 61.5%   |
| IDE  | 53       | 24.88%  |
| NVMe | 20       | 9.39%   |
| RAID | 8        | 3.76%   |
| SCSI | 1        | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 154      | 82.35%  |
| AMD    | 33       | 17.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Celeron J4125 CPU @ 2.00GHz               | 9        | 4.76%   |
| Intel Celeron N5105 @ 2.00GHz                   | 7        | 3.7%    |
| Intel Celeron CPU J1800 @ 2.41GHz               | 5        | 2.65%   |
| Intel Core i3-7100 CPU @ 3.90GHz                | 4        | 2.12%   |
| Intel Pentium Silver N6005 @ 2.00GHz            | 3        | 1.59%   |
| Intel N100                                      | 3        | 1.59%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 3        | 1.59%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 3        | 1.59%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 3        | 1.59%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz           | 3        | 1.59%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 3        | 1.59%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 3        | 1.59%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 3        | 1.59%   |
| AMD FX-8320E Eight-Core Processor               | 3        | 1.59%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 2        | 1.06%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 2        | 1.06%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 2        | 1.06%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 2        | 1.06%   |
| Intel Core i5-3570 CPU @ 3.40GHz                | 2        | 1.06%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 2        | 1.06%   |
| Intel Core i3-4030U CPU @ 1.90GHz               | 2        | 1.06%   |
| Intel Core i3-3240 CPU @ 3.40GHz                | 2        | 1.06%   |
| Intel Core i3-2100 CPU                          | 2        | 1.06%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz            | 2        | 1.06%   |
| Intel Core 2 Duo CPU                            | 2        | 1.06%   |
| Intel Celeron J4005 CPU @ 2.00GHz               | 2        | 1.06%   |
| Intel Celeron CPU 847 @ 1.10GHz                 | 2        | 1.06%   |
| AMD FX-6100 Six-Core Processor                  | 2        | 1.06%   |
| AMD A10-7870K Radeon R7, 12 Compute Cores 4C+8G | 2        | 1.06%   |
| Intel Xeon CPU X5680 @ 3.33GHz                  | 1        | 0.53%   |
| Intel Xeon CPU X3440 @ 2.53GHz                  | 1        | 0.53%   |
| Intel Xeon CPU X3430 @ 2.40GHz                  | 1        | 0.53%   |
| Intel Xeon CPU E5506 @ 2.13GHz                  | 1        | 0.53%   |
| Intel Xeon CPU E5462 @ 2.80GHz                  | 1        | 0.53%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz              | 1        | 0.53%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz            | 1        | 0.53%   |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz             | 1        | 0.53%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz             | 1        | 0.53%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz             | 1        | 0.53%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz     | 1        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 33       | 17.55%  |
| Intel Core i3           | 31       | 16.49%  |
| Intel Core i5           | 28       | 14.89%  |
| Intel Core 2 Duo        | 14       | 7.45%   |
| Intel Xeon              | 10       | 5.32%   |
| Intel Core i7           | 10       | 5.32%   |
| AMD FX                  | 9        | 4.79%   |
| Intel Pentium Dual-Core | 6        | 3.19%   |
| Intel Pentium           | 6        | 3.19%   |
| AMD Ryzen 5             | 6        | 3.19%   |
| Other                   | 5        | 2.66%   |
| Intel Core 2 Quad       | 5        | 2.66%   |
| AMD Ryzen 7             | 5        | 2.66%   |
| Intel Pentium Silver    | 3        | 1.6%    |
| Intel Atom              | 3        | 1.6%    |
| AMD A10                 | 2        | 1.06%   |
| Intel Pentium Dual      | 1        | 0.53%   |
| Intel Core 2            | 1        | 0.53%   |
| AMD Turion II Neo       | 1        | 0.53%   |
| AMD Ryzen 5 PRO         | 1        | 0.53%   |
| AMD Ryzen 3 PRO         | 1        | 0.53%   |
| AMD Ryzen 3             | 1        | 0.53%   |
| AMD PRO A8              | 1        | 0.53%   |
| AMD Phenom              | 1        | 0.53%   |
| AMD E                   | 1        | 0.53%   |
| AMD Athlon II X2        | 1        | 0.53%   |
| AMD Athlon 64 X2        | 1        | 0.53%   |
| AMD Athlon              | 1        | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 77       | 40.74%  |
| 2       | 72       | 38.1%   |
| 8       | 13       | 6.88%   |
| 6       | 10       | 5.29%   |
| Unknown | 7        | 3.7%    |
| 12      | 5        | 2.65%   |
| 16      | 4        | 2.12%   |
| 1       | 1        | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 184      | 99.46%  |
| 2      | 1        | 0.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 127      | 67.91%  |
| 2       | 53       | 28.34%  |
| Unknown | 7        | 3.74%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 23       | 12.17%  |
| Haswell       | 21       | 11.11%  |
| Unknown       | 18       | 9.52%   |
| KabyLake      | 17       | 8.99%   |
| SandyBridge   | 13       | 6.88%   |
| IvyBridge     | 13       | 6.88%   |
| Goldmont plus | 12       | 6.35%   |
| Silvermont    | 8        | 4.23%   |
| Zen+          | 7        | 3.7%    |
| Westmere      | 6        | 3.17%   |
| Skylake       | 6        | 3.17%   |
| Piledriver    | 6        | 3.17%   |
| Core          | 6        | 3.17%   |
| Zen 3         | 5        | 2.65%   |
| Nehalem       | 5        | 2.65%   |
| Broadwell     | 4        | 2.12%   |
| Steamroller   | 3        | 1.59%   |
| K10           | 3        | 1.59%   |
| Bulldozer     | 3        | 1.59%   |
| Zen           | 2        | 1.06%   |
| CometLake     | 2        | 1.06%   |
| Bonnell       | 2        | 1.06%   |
| Zen 2         | 1        | 0.53%   |
| K8 Hammer     | 1        | 0.53%   |
| Goldmont      | 1        | 0.53%   |
| Bobcat        | 1        | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 130      | 68.42%  |
| AMD                        | 35       | 18.42%  |
| Nvidia                     | 21       | 11.05%  |
| Matrox Electronics Systems | 3        | 1.58%   |
| ASPEED Technology          | 1        | 0.53%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                         | 12       | 6.19%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 12       | 6.19%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12       | 6.19%   |
| Intel JasperLake [UHD Graphics]                                             | 11       | 5.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 5.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 4.64%   |
| Intel HD Graphics 630                                                       | 8        | 4.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 8        | 4.12%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 7        | 3.61%   |
| Intel Core Processor Integrated Graphics Controller                         | 5        | 2.58%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 2.58%   |
| Intel HD Graphics 5500                                                      | 4        | 2.06%   |
| Intel HD Graphics 530                                                       | 4        | 2.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4        | 2.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 2.06%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 2.06%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 3        | 1.55%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.55%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 3        | 1.55%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 1.55%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 1.55%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 3        | 1.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 1.55%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.55%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.03%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.03%   |
| Matrox Electronics Systems MGA G200EH                                       | 2        | 1.03%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.03%   |
| Nvidia GT215M [GeForce GT 335M]                                             | 1        | 0.52%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.52%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.52%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.52%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.52%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.52%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.52%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.52%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.52%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 0.52%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 121      | 64.36%  |
| 1 x AMD        | 32       | 17.02%  |
| 1 x Nvidia     | 20       | 10.64%  |
| 2 x Intel      | 5        | 2.66%   |
| 1 x Matrox     | 3        | 1.6%    |
| Intel + AMD    | 3        | 1.6%    |
| Other          | 2        | 1.06%   |
| Intel + Nvidia | 1        | 0.53%   |
| 1 x ASPEED     | 1        | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 170      | 90.91%  |
| Proprietary | 15       | 8.02%   |
| Unknown     | 2        | 1.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 151      | 79.47%  |
| 0.51-1.0   | 12       | 6.32%   |
| 1.01-2.0   | 9        | 4.74%   |
| 3.01-4.0   | 7        | 3.68%   |
| 0.01-0.5   | 7        | 3.68%   |
| 7.01-8.0   | 3        | 1.58%   |
| 2.01-3.0   | 1        | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 20       | 35.71%  |
| Samsung Electronics | 15       | 26.79%  |
| Philips             | 5        | 8.93%   |
| AOC                 | 4        | 7.14%   |
| Lenovo              | 2        | 3.57%   |
| VIE                 | 1        | 1.79%   |
| Semp Toshiba        | 1        | 1.79%   |
| Panasonic           | 1        | 1.79%   |
| MStar               | 1        | 1.79%   |
| LG Electronics      | 1        | 1.79%   |
| LG Display          | 1        | 1.79%   |
| ITE                 | 1        | 1.79%   |
| Hewlett-Packard     | 1        | 1.79%   |
| ASUSTek Computer    | 1        | 1.79%   |
| AGO                 | 1        | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0601 1600x900                      | 2        | 3.28%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch  | 2        | 3.28%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 2        | 3.28%   |
| VIE E195 VIE1950 1600x900 410x280mm 19.5-inch                        | 1        | 1.64%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch            | 1        | 1.64%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch | 1        | 1.64%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch  | 1        | 1.64%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch  | 1        | 1.64%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                     | 1        | 1.64%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 480x270mm 21.7-inch | 1        | 1.64%   |
| Samsung Electronics SyncMaster SAM04E4 1600x900 440x250mm 19.9-inch  | 1        | 1.64%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch  | 1        | 1.64%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch  | 1        | 1.64%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 310x230mm 15.2-inch | 1        | 1.64%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch  | 1        | 1.64%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 440x250mm 19.9-inch | 1        | 1.64%   |
| Samsung Electronics S23C550 SAM0A42 1920x1080 510x290mm 23.1-inch    | 1        | 1.64%   |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch     | 1        | 1.64%   |
| Samsung Electronics LCD Monitor SMT27A550 1920x1080                  | 1        | 1.64%   |
| Samsung Electronics LCD Monitor SAM0678 1360x768                     | 1        | 1.64%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 1        | 1.64%   |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch              | 1        | 1.64%   |
| Philips LCD Monitor PHL2051 1600x900 440x250mm 19.9-inch             | 1        | 1.64%   |
| Philips 221EL PHLC056 1920x1080 480x270mm 21.7-inch                  | 1        | 1.64%   |
| Philips 202EL PHLC05C 1600x900 440x250mm 19.9-inch                   | 1        | 1.64%   |
| Panasonic TV MEIC136 1280x720 698x392mm 31.5-inch                    | 1        | 1.64%   |
| MStar TSB LEDTV MST0030 1920x1080 1150x650mm 52.0-inch               | 1        | 1.64%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 3640x1920                    | 1        | 1.64%   |
| LG Electronics LCD Monitor 23MP55                                    | 1        | 1.64%   |
| LG Display LCD Monitor LGD020C 1600x900 350x190mm 15.7-inch          | 1        | 1.64%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 480x270mm 21.7-inch             | 1        | 1.64%   |
| Lenovo L197 Wide LEN1152 1440x900 410x260mm 19.1-inch                | 1        | 1.64%   |
| ITE DP2VGA V235 ITE6516 1920x1080 600x340mm 27.2-inch                | 1        | 1.64%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch           | 1        | 1.64%   |
| Goldstar W2242 GSM4B6F 1680x1050 490x320mm 23.0-inch                 | 1        | 1.64%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                  | 1        | 1.64%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                  | 1        | 1.64%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                  | 1        | 1.64%   |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch          | 1        | 1.64%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch          | 1        | 1.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 25       | 42.37%  |
| 1600x900 (HD+)     | 10       | 16.95%  |
| 1366x768 (WXGA)    | 6        | 10.17%  |
| 2560x1080          | 3        | 5.08%   |
| 1440x900 (WXGA+)   | 3        | 5.08%   |
| 1360x768           | 3        | 5.08%   |
| 1280x1024 (SXGA)   | 3        | 5.08%   |
| 1024x768 (XGA)     | 2        | 3.39%   |
| 3640x1920          | 1        | 1.69%   |
| 1680x1050 (WSXGA+) | 1        | 1.69%   |
| 1280x720 (HD)      | 1        | 1.69%   |
| Unknown            | 1        | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 10       | 16.95%  |
| 21      | 10       | 16.95%  |
| 19      | 10       | 16.95%  |
| 18      | 7        | 11.86%  |
| Unknown | 6        | 10.17%  |
| 34      | 3        | 5.08%   |
| 15      | 3        | 5.08%   |
| 20      | 2        | 3.39%   |
| 14      | 2        | 3.39%   |
| 52      | 1        | 1.69%   |
| 31      | 1        | 1.69%   |
| 27      | 1        | 1.69%   |
| 24      | 1        | 1.69%   |
| 17      | 1        | 1.69%   |
| 13      | 1        | 1.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 28       | 48.28%  |
| 501-600     | 11       | 18.97%  |
| Unknown     | 6        | 10.34%  |
| 301-350     | 4        | 6.9%    |
| 701-800     | 3        | 5.17%   |
| 201-300     | 3        | 5.17%   |
| 601-700     | 1        | 1.72%   |
| 351-400     | 1        | 1.72%   |
| 1001-1500   | 1        | 1.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 40       | 71.43%  |
| 4/3     | 4        | 7.14%   |
| 21/9    | 3        | 5.36%   |
| 16/10   | 3        | 5.36%   |
| 5/4     | 2        | 3.57%   |
| 3/2     | 2        | 3.57%   |
| Unknown | 2        | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 21       | 35.59%  |
| 151-200        | 12       | 20.34%  |
| 141-150        | 8        | 13.56%  |
| Unknown        | 6        | 10.17%  |
| 351-500        | 4        | 6.78%   |
| 101-110        | 3        | 5.08%   |
| 91-100         | 2        | 3.39%   |
| More than 1000 | 1        | 1.69%   |
| 301-350        | 1        | 1.69%   |
| 111-120        | 1        | 1.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 36       | 62.07%  |
| 101-120 | 13       | 22.41%  |
| Unknown | 6        | 10.34%  |
| 1-50    | 2        | 3.45%   |
| 121-160 | 1        | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 122      | 65.24%  |
| 1     | 60       | 32.09%  |
| 2     | 5        | 2.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 115      | 46%     |
| Intel                      | 94       | 37.6%   |
| Qualcomm Atheros           | 10       | 4%      |
| Broadcom                   | 10       | 4%      |
| Ralink                     | 4        | 1.6%    |
| D-Link System              | 3        | 1.2%    |
| Ralink Technology          | 2        | 0.8%    |
| IMC Networks               | 2        | 0.8%    |
| ZTE WCDMA Technologies MSM | 1        | 0.4%    |
| TP-Link                    | 1        | 0.4%    |
| STMicroelectronics         | 1        | 0.4%    |
| Samsung Electronics        | 1        | 0.4%    |
| Mellanox Technologies      | 1        | 0.4%    |
| MediaTek                   | 1        | 0.4%    |
| ICS Advent                 | 1        | 0.4%    |
| Edimax Technology          | 1        | 0.4%    |
| Arduino SA                 | 1        | 0.4%    |
| 3Com                       | 1        | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                              | Desktops | Percent |
|----------------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                             | 89       | 31.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                              | 14       | 4.91%   |
| Intel I211 Gigabit Network Connection                                                              | 13       | 4.56%   |
| Intel Ethernet Controller I226-V                                                                   | 13       | 4.56%   |
| Intel Ethernet Controller I225-V                                                                   | 12       | 4.21%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                  | 11       | 3.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                              | 6        | 2.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                           | 5        | 1.75%   |
| Intel 82576 Gigabit Network Connection                                                             | 5        | 1.75%   |
| Intel 82574L Gigabit Network Connection                                                            | 5        | 1.75%   |
| Intel I350 Gigabit Network Connection                                                              | 4        | 1.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                              | 4        | 1.4%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)                      | 4        | 1.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                                | 3        | 1.05%   |
| Realtek RTL8125 2.5GbE Controller                                                                  | 3        | 1.05%   |
| Intel Ethernet Connection I217-LM                                                                  | 3        | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                                                              | 3        | 1.05%   |
| Intel Ethernet Connection (2) I218-V                                                               | 3        | 1.05%   |
| Intel 82579V Gigabit Network Connection                                                            | 3        | 1.05%   |
| Intel 82578DC Gigabit Network Connection                                                           | 3        | 1.05%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                                    | 2        | 0.7%    |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                                       | 2        | 0.7%    |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                               | 2        | 0.7%    |
| Ralink RT2561/RT61 rev B 802.11g                                                                   | 2        | 0.7%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                                         | 2        | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                      | 2        | 0.7%    |
| Intel Wireless 7265                                                                                | 2        | 0.7%    |
| Intel Wireless 3165                                                                                | 2        | 0.7%    |
| Intel Ethernet Connection (7) I219-LM                                                              | 2        | 0.7%    |
| Intel Ethernet Connection (2) I219-V                                                               | 2        | 0.7%    |
| Intel 82583V Gigabit Network Connection                                                            | 2        | 0.7%    |
| Intel 82567LM-3 Gigabit Network Connection                                                         | 2        | 0.7%    |
| Intel 82566DM-2 Gigabit Network Connection                                                         | 2        | 0.7%    |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                               | 2        | 0.7%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                                    | 2        | 0.7%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                     | 2        | 0.7%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                                                   | 2        | 0.7%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                                                   | 2        | 0.7%    |
| ZTE WCDMA MSM ZTE Mobile Boardband CDC Ethernet Control Model (ECM) CDC Ethernet Data Mass Storage | 1        | 0.35%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                         | 1        | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 35.29%  |
| Intel                 | 9        | 26.47%  |
| Ralink                | 4        | 11.76%  |
| Ralink Technology     | 2        | 5.88%   |
| Qualcomm Atheros      | 2        | 5.88%   |
| IMC Networks          | 2        | 5.88%   |
| TP-Link               | 1        | 2.94%   |
| Edimax Technology     | 1        | 2.94%   |
| D-Link System         | 1        | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 5        | 14.29%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 8.57%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                         | 2        | 5.71%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 2        | 5.71%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2        | 5.71%   |
| Intel Wireless 7265                                                  | 2        | 5.71%   |
| Intel Wireless 3165                                                  | 2        | 5.71%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                 | 2        | 5.71%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1        | 2.86%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 2.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1        | 2.86%   |
| Realtek RTL8187SE Wireless LAN Controller                            | 1        | 2.86%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 2.86%   |
| Ralink MT7601U Wireless Adapter                                      | 1        | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 2.86%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 1        | 2.86%   |
| Intel Wi-Fi 6 AX201 160MHz                                           | 1        | 2.86%   |
| Intel Wi-Fi 6 AX200                                                  | 1        | 2.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1        | 2.86%   |
| Intel Centrino Advanced-N 6235                                       | 1        | 2.86%   |
| Edimax AC600 Wireless LAN USB Adapter                                | 1        | 2.86%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1        | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 113      | 49.13%  |
| Intel                      | 92       | 40%     |
| Broadcom                   | 10       | 4.35%   |
| Qualcomm Atheros           | 8        | 3.48%   |
| D-Link System              | 2        | 0.87%   |
| ZTE WCDMA Technologies MSM | 1        | 0.43%   |
| Samsung Electronics        | 1        | 0.43%   |
| MediaTek                   | 1        | 0.43%   |
| ICS Advent                 | 1        | 0.43%   |
| 3Com                       | 1        | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                                              | Desktops | Percent |
|----------------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                             | 89       | 36.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                              | 14       | 5.67%   |
| Intel I211 Gigabit Network Connection                                                              | 13       | 5.26%   |
| Intel Ethernet Controller I226-V                                                                   | 13       | 5.26%   |
| Intel Ethernet Controller I225-V                                                                   | 12       | 4.86%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                  | 11       | 4.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                              | 6        | 2.43%   |
| Intel 82576 Gigabit Network Connection                                                             | 5        | 2.02%   |
| Intel 82574L Gigabit Network Connection                                                            | 5        | 2.02%   |
| Intel I350 Gigabit Network Connection                                                              | 4        | 1.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                              | 4        | 1.62%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)                      | 4        | 1.62%   |
| Realtek RTL8125 2.5GbE Controller                                                                  | 3        | 1.21%   |
| Intel Ethernet Connection I217-LM                                                                  | 3        | 1.21%   |
| Intel Ethernet Connection (2) I219-LM                                                              | 3        | 1.21%   |
| Intel Ethernet Connection (2) I218-V                                                               | 3        | 1.21%   |
| Intel 82579V Gigabit Network Connection                                                            | 3        | 1.21%   |
| Intel 82578DC Gigabit Network Connection                                                           | 3        | 1.21%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                                    | 2        | 0.81%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                                         | 2        | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                      | 2        | 0.81%   |
| Intel Ethernet Connection (7) I219-LM                                                              | 2        | 0.81%   |
| Intel Ethernet Connection (2) I219-V                                                               | 2        | 0.81%   |
| Intel 82583V Gigabit Network Connection                                                            | 2        | 0.81%   |
| Intel 82567LM-3 Gigabit Network Connection                                                         | 2        | 0.81%   |
| Intel 82566DM-2 Gigabit Network Connection                                                         | 2        | 0.81%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                                    | 2        | 0.81%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                     | 2        | 0.81%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                                                   | 2        | 0.81%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                                                   | 2        | 0.81%   |
| ZTE WCDMA MSM ZTE Mobile Boardband CDC Ethernet Control Model (ECM) CDC Ethernet Data Mass Storage | 1        | 0.4%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                                        | 1        | 0.4%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                                         | 1        | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                         | 1        | 0.4%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                                      | 1        | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                           | 1        | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                                     | 1        | 0.4%    |
| MediaTek USB Ethernet-RNDIS                                                                        | 1        | 0.4%    |
| Intel Ethernet Controller X550                                                                     | 1        | 0.4%    |
| Intel Ethernet Controller I226-LM                                                                  | 1        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 184      | 84.79%  |
| WiFi     | 30       | 13.82%  |
| Modem    | 2        | 0.92%   |
| Unknown  | 1        | 0.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 183      | 94.82%  |
| WiFi     | 10       | 5.18%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 57       | 30.16%  |
| 2     | 47       | 24.87%  |
| 4     | 40       | 21.16%  |
| 3     | 25       | 13.23%  |
| 5     | 11       | 5.82%   |
| 6     | 7        | 3.7%    |
| 8     | 1        | 0.53%   |
| 7     | 1        | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 172      | 90.53%  |
| Yes  | 18       | 9.47%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 8        | 44.44%  |
| Realtek Semiconductor   | 6        | 33.33%  |
| Cambridge Silicon Radio | 3        | 16.67%  |
| Qcom                    | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Adapter                           | 6        | 33.33%  |
| Intel Bluetooth wireless interface                  | 4        | 22.22%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 16.67%  |
| Intel AX201 Bluetooth                               | 2        | 11.11%  |
| Qcom Broadcom Bluetooth USB                         | 1        | 5.56%   |
| Intel AX210 Bluetooth                               | 1        | 5.56%   |
| Intel AX200 Bluetooth                               | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 129      | 64.5%   |
| AMD                                             | 41       | 20.5%   |
| Nvidia                                          | 20       | 10%     |
| C-Media Electronics                             | 6        | 3%      |
| Zoran Co. Personal Media Division (Nogatech)    | 1        | 0.5%    |
| Licensed by Sony Computer Entertainment America | 1        | 0.5%    |
| KTMicro                                         | 1        | 0.5%    |
| Generalplus Technology                          | 1        | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 21       | 8.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 5%      |
| Intel Jasper Lake HD Audio                                                 | 11       | 4.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11       | 4.58%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11       | 4.58%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10       | 4.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8        | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 2.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7        | 2.92%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 2.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 2.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 6        | 2.5%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 2.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4        | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4        | 1.67%   |
| Intel Broadwell-U Audio Controller                                         | 4        | 1.67%   |
| Intel 8 Series HD Audio Controller                                         | 4        | 1.67%   |
| AMD FCH Azalia Controller                                                  | 4        | 1.67%   |
| Nvidia High Definition Audio Controller                                    | 3        | 1.25%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 1.25%   |
| Intel Sunrise Point-LP HD Audio                                            | 3        | 1.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.25%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 3        | 1.25%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.25%   |
| C-Media Electronics CM108 Audio Controller                                 | 3        | 1.25%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 3        | 1.25%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.25%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 3        | 1.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 1.25%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 1.25%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.25%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.83%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 46       | 22.55%  |
| Kingston            | 34       | 16.67%  |
| Smart               | 17       | 8.33%   |
| Samsung Electronics | 12       | 5.88%   |
| Crucial             | 12       | 5.88%   |
| Unknown             | 12       | 5.88%   |
| Micron Technology   | 9        | 4.41%   |
| Teikon              | 7        | 3.43%   |
| SK hynix            | 7        | 3.43%   |
| A-DATA Technology   | 7        | 3.43%   |
| Corsair             | 6        | 2.94%   |
| G.Skill             | 3        | 1.47%   |
| Unknown (ABCD)      | 2        | 0.98%   |
| Toshiba             | 2        | 0.98%   |
| PUSKILL             | 2        | 0.98%   |
| Patriot             | 2        | 0.98%   |
| Hikvision           | 2        | 0.98%   |
| Hewlett-Packard     | 2        | 0.98%   |
| Unknown (8A02)      | 1        | 0.49%   |
| Unknown (0x5846)    | 1        | 0.49%   |
| Unknown (0x0080)    | 1        | 0.49%   |
| tigo                | 1        | 0.49%   |
| SK_Hynix            | 1        | 0.49%   |
| RZX                 | 1        | 0.49%   |
| Nanya Technology    | 1        | 0.49%   |
| Multilaser          | 1        | 0.49%   |
| MemoWise            | 1        | 0.49%   |
| Lexar               | 1        | 0.49%   |
| Kreton              | 1        | 0.49%   |
| Kllisre             | 1        | 0.49%   |
| KingSpec            | 1        | 0.49%   |
| Kimtigo             | 1        | 0.49%   |
| Juhor               | 1        | 0.49%   |
| GLOWAY              | 1        | 0.49%   |
| Galaxy              | 1        | 0.49%   |
| CSX                 | 1        | 0.49%   |
| Atermiter           | 1        | 0.49%   |
| Apacer              | 1        | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown                                                      | 12       | 5.48%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s          | 5        | 2.28%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 4        | 1.83%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 3        | 1.37%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 3        | 1.37%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 3        | 1.37%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 3        | 1.37%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 3        | 1.37%   |
| Unknown RAM Module 2GB DIMM DDR2                             | 3        | 1.37%   |
| Unknown RAM Module 2GB DIMM                                  | 3        | 1.37%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 2        | 0.91%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 2        | 0.91%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 2        | 0.91%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 2        | 0.91%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 2        | 0.91%   |
| Teikon RAM TMTS8G58DFRBFKB-16 8GB SODIMM DDR3 1600MT/s       | 2        | 0.91%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s          | 2        | 0.91%   |
| Smart RAM SH564568FH8N0QHSCG 2GB DIMM DDR3 1333MT/s          | 2        | 0.91%   |
| Patriot RAM 2666 C16 Series 4GB DIMM DDR4 3000MT/s           | 2        | 0.91%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                    | 2        | 0.91%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s          | 2        | 0.91%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s            | 2        | 0.91%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 2        | 0.91%   |
| Kingston RAM KHX1600C10D3/ 4GB DIMM DDR3 1866MT/s            | 2        | 0.91%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s        | 2        | 0.91%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s        | 2        | 0.91%   |
| Hikvision RAM HKED4082CAA1D0HA1 8GB SODIMM DDR4 2400MT/s     | 2        | 0.91%   |
| Corsair RAM CMY16GX3M2A2400C11 8GB DIMM DDR3 2400MT/s        | 2        | 0.91%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                  | 2        | 0.91%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1        | 0.46%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                         | 1        | 0.46%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                 | 1        | 0.46%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                 | 1        | 0.46%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                     | 1        | 0.46%   |
| Unknown RAM Module 4GB DIMM 400MT/s                          | 1        | 0.46%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                 | 1        | 0.46%   |
| Unknown RAM Module 4096MB DIMM DDR2                          | 1        | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                   | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM SDRAM 1333MT/s                   | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                     | 1        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 72       | 40.91%  |
| DDR4    | 57       | 32.39%  |
| Unknown | 15       | 8.52%   |
| SDRAM   | 13       | 7.39%   |
| DDR2    | 12       | 6.82%   |
| LPDDR4  | 4        | 2.27%   |
| DDR5    | 2        | 1.14%   |
| LPDDR5  | 1        | 0.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 130      | 74.29%  |
| SODIMM       | 41       | 23.43%  |
| Row Of Chips | 3        | 1.71%   |
| Chip         | 1        | 0.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 65       | 34.21%  |
| 4096  | 59       | 31.05%  |
| 2048  | 41       | 21.58%  |
| 16384 | 18       | 9.47%   |
| 1024  | 5        | 2.63%   |
| 32768 | 2        | 1.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 40       | 21.16%  |
| 1333    | 34       | 17.99%  |
| 2400    | 25       | 13.23%  |
| Unknown | 19       | 10.05%  |
| 2667    | 16       | 8.47%   |
| 3200    | 13       | 6.88%   |
| 800     | 10       | 5.29%   |
| 2666    | 5        | 2.65%   |
| 2133    | 5        | 2.65%   |
| 1866    | 3        | 1.59%   |
| 3000    | 2        | 1.06%   |
| 1867    | 2        | 1.06%   |
| 1067    | 2        | 1.06%   |
| 1066    | 2        | 1.06%   |
| 667     | 2        | 1.06%   |
| 400     | 2        | 1.06%   |
| 6400    | 1        | 0.53%   |
| 5600    | 1        | 0.53%   |
| 4800    | 1        | 0.53%   |
| 4267    | 1        | 0.53%   |
| 4000    | 1        | 0.53%   |
| 2933    | 1        | 0.53%   |
| 333     | 1        | 0.53%   |

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
| Quanta                  | 1        | 20%     |
| Aveo Technology         | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera  | 1        | 20%     |
| Quanta LG Webcam            | 1        | 20%     |
| Logitech Webcam C270        | 1        | 20%     |
| Logitech HD Pro Webcam C920 | 1        | 20%     |
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
| 1     | 99       | 53.23%  |
| 0     | 70       | 37.63%  |
| 2     | 14       | 7.53%   |
| 3     | 2        | 1.08%   |
| 4     | 1        | 0.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 105      | 82.03%  |
| Net/wireless             | 10       | 7.81%   |
| Bluetooth                | 6        | 4.69%   |
| Sound                    | 4        | 3.13%   |
| Net/ethernet             | 1        | 0.78%   |
| Graphics card            | 1        | 0.78%   |
| Firewire controller      | 1        | 0.78%   |

