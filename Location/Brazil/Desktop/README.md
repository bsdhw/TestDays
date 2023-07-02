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

Total: 240

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| Positivo      | POS-EINM70CS SIM            | [0b29806790](https://bsd-hardware.info/?probe=0b29806790) | Jul 23, 2022 |
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
| helloSystem 0.7.0    | 13       | 7.07%   |
| helloSystem 0.8.0    | 7        | 3.8%    |
| OPNsense 23.1.7      | 6        | 3.26%   |
| OPNsense 23.1.5      | 6        | 3.26%   |
| OPNsense 22.1.10     | 6        | 3.26%   |
| OPNsense 20.7.8      | 6        | 3.26%   |
| OPNsense 23.1.9      | 5        | 2.72%   |
| OPNsense 22.7.5      | 5        | 2.72%   |
| OPNsense 21.1.3      | 5        | 2.72%   |
| OPNsense 21.1        | 5        | 2.72%   |
| helloSystem 0.8.1    | 5        | 2.72%   |
| helloSystem 0.4.0    | 5        | 2.72%   |
| OPNsense 23.1        | 4        | 2.17%   |
| OPNsense 22.7.8      | 4        | 2.17%   |
| OPNsense 22.7.4      | 4        | 2.17%   |
| OPNsense 21.1.1      | 4        | 2.17%   |
| helloSystem 0.6.0    | 4        | 2.17%   |
| helloSystem 0.5.0    | 4        | 2.17%   |
| FreeBSD 14.0-CURRENT | 4        | 2.17%   |
| OPNsense 23.1.1      | 3        | 1.63%   |
| OPNsense 22.7.6      | 3        | 1.63%   |
| OPNsense 22.1.8      | 3        | 1.63%   |
| OPNsense 21.7.7      | 3        | 1.63%   |
| OPNsense 21.7.1      | 3        | 1.63%   |
| OPNsense 21.1.9      | 3        | 1.63%   |
| OPNsense 21.1.6      | 3        | 1.63%   |
| OPNsense 21.1.4      | 3        | 1.63%   |
| OPNsense 23.1.8      | 2        | 1.09%   |
| OPNsense 23.1.6      | 2        | 1.09%   |
| OPNsense 23.1.3      | 2        | 1.09%   |
| OPNsense 22.7.9      | 2        | 1.09%   |
| OPNsense 22.7.10     | 2        | 1.09%   |
| OPNsense 22.1.7      | 2        | 1.09%   |
| OPNsense 22.1        | 2        | 1.09%   |
| OPNsense 21.1.7      | 2        | 1.09%   |
| OPNsense 21.1.2      | 2        | 1.09%   |
| OpenBSD 7.3          | 2        | 1.09%   |
| NomadBSD 5806f915    | 2        | 1.09%   |
| FreeBSD 13.0-p7      | 2        | 1.09%   |
| FreeBSD 13.0         | 2        | 1.09%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 78       | 54.93%  |
| helloSystem | 34       | 23.94%  |
| FreeBSD     | 19       | 13.38%  |
| OpenBSD     | 3        | 2.11%   |
| pfSense     | 2        | 1.41%   |
| NomadBSD    | 2        | 1.41%   |
| TrueNAS     | 1        | 0.7%    |
| NetBSD      | 1        | 0.7%    |
| GhostBSD    | 1        | 0.7%    |
| FreeNAS     | 1        | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 138      | 98.57%  |
| i386  | 2        | 1.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 83       | 58.45%  |
| helloDesktop | 37       | 26.06%  |
| KDE5         | 8        | 5.63%   |
| Openbox      | 4        | 2.82%   |
| XFCE         | 3        | 2.11%   |
| MATE         | 2        | 1.41%   |
| Window Maker | 1        | 0.7%    |
| TWM          | 1        | 0.7%    |
| i3           | 1        | 0.7%    |
| GNOME        | 1        | 0.7%    |
| AwesomeWM    | 1        | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 85       | 60.71%  |
| X11     | 55       | 39.29%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 93       | 65.96%  |
| SLiM    | 36       | 25.53%  |
| SDDM    | 7        | 4.96%   |
| GDM     | 3        | 2.13%   |
| XDM     | 1        | 0.71%   |
| LightDM | 1        | 0.71%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 83       | 58.45%  |
| en_US   | 29       | 20.42%  |
| pt_BR   | 12       | 8.45%   |
| C       | 11       | 7.75%   |
| pt      | 3        | 2.11%   |
| fr_FR   | 3        | 2.11%   |
| fr      | 1        | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 118      | 81.38%  |
| BIOS | 27       | 18.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 73       | 50.34%  |
| Zfs    | 54       | 37.24%  |
| Cd9660 | 15       | 10.34%  |
| Ffs    | 3        | 2.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 127      | 88.19%  |
| MBR     | 15       | 10.42%  |
| Unknown | 2        | 1.39%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUSTek Computer        | 30       | 21.43%  |
| Dell                    | 15       | 10.71%  |
| Unknown                 | 15       | 10.71%  |
| Intel                   | 13       | 9.29%   |
| Gigabyte Technology     | 12       | 8.57%   |
| Hewlett-Packard         | 8        | 5.71%   |
| ASRock                  | 6        | 4.29%   |
| Positivo                | 4        | 2.86%   |
| Lenovo                  | 4        | 2.86%   |
| Techvision              | 3        | 2.14%   |
| Pegatron                | 3        | 2.14%   |
| PCWare                  | 3        | 2.14%   |
| MSI                     | 3        | 2.14%   |
| Itautec                 | 2        | 1.43%   |
| ECS                     | 2        | 1.43%   |
| Biostar                 | 2        | 1.43%   |
| YANYU                   | 1        | 0.71%   |
| Yanling                 | 1        | 0.71%   |
| ULTRATOP                | 1        | 0.71%   |
| T-bao                   | 1        | 0.71%   |
| Soyo                    | 1        | 0.71%   |
| Semp Toshiba            | 1        | 0.71%   |
| Procomp Ind. Eletronica | 1        | 0.71%   |
| maiyunda                | 1        | 0.71%   |
| KLLISRE                 | 1        | 0.71%   |
| HC                      | 1        | 0.71%   |
| GALAX                   | 1        | 0.71%   |
| ECS-USA                 | 1        | 0.71%   |
| CNCTION-IAF-E3845       | 1        | 0.71%   |
| AZW                     | 1        | 0.71%   |
| AMI                     | 1        | 0.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 16       | 11.43%  |
| Intel Q3XXG4-P V1.0                     | 7        | 5%      |
| ASUS All Series                         | 4        | 2.86%   |
| Techvision TVI7309X                     | 3        | 2.14%   |
| Pegatron IPM41-D3                       | 2        | 1.43%   |
| Gigabyte H61M-S2-B3                     | 2        | 1.43%   |
| ASUS PRIME B450M-GAMING/BR              | 2        | 1.43%   |
| ASUS P8H61-M LX3 PLUS R2.0              | 2        | 1.43%   |
| ASUS M5A78L-M LX/BR                     | 2        | 1.43%   |
| YANYU N39SL                             | 1        | 0.71%   |
| Yanling NS-1U8L                         | 1        | 0.71%   |
| ULTRATOP C2017-LIVA-ZE                  | 1        | 0.71%   |
| T-bao MINI PC                           | 1        | 0.71%   |
| Soyo SY-YL B550M                        | 1        | 0.71%   |
| Semp Toshiba STI                        | 1        | 0.71%   |
| Procomp Ind. Eletronica G41MXE          | 1        | 0.71%   |
| Positivo Positivo Master D610           | 1        | 0.71%   |
| Positivo POS-PIQ77CL                    | 1        | 0.71%   |
| Positivo POS-EINM70CS                   | 1        | 0.71%   |
| Positivo POS-EAA75DE                    | 1        | 0.71%   |
| Pegatron IPMIP-GS                       | 1        | 0.71%   |
| PCWare PW-945GCX                        | 1        | 0.71%   |
| PCWare IPX1800G2                        | 1        | 0.71%   |
| PCWare IPMH81G1                         | 1        | 0.71%   |
| MSI U-100                               | 1        | 0.71%   |
| MSI MS-7877                             | 1        | 0.71%   |
| MSI MS-7698                             | 1        | 0.71%   |
| maiyunda www.maiyunda.com               | 1        | 0.71%   |
| Lenovo V14 G2 ITL 82NM                  | 1        | 0.71%   |
| Lenovo ThinkCentre M57p 6078AJ6         | 1        | 0.71%   |
| Lenovo ThinkCentre A70 7099A5P          | 1        | 0.71%   |
| Lenovo IdeaCentre 510A-15IKL 90GV0019CD | 1        | 0.71%   |
| KLLISRE X99-B5 V1.0                     | 1        | 0.71%   |
| Itautec Infoway ST-4344                 | 1        | 0.71%   |
| Itautec Infoway                         | 1        | 0.71%   |
| Intel Jasper Lake Client Platform       | 1        | 0.71%   |
| Intel H81                               | 1        | 0.71%   |
| Intel H61                               | 1        | 0.71%   |
| Intel H55                               | 1        | 0.71%   |
| Intel DP55WB AAE64798-207               | 1        | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 16       | 11.43%  |
| Dell OptiPlex                  | 8        | 5.71%   |
| Intel Q3XXG4-P                 | 7        | 5%      |
| HP ProLiant                    | 4        | 2.86%   |
| Dell Vostro                    | 4        | 2.86%   |
| ASUS PRIME                     | 4        | 2.86%   |
| ASUS All                       | 4        | 2.86%   |
| Techvision TVI7309X            | 3        | 2.14%   |
| Dell Inspiron                  | 3        | 2.14%   |
| ASUS P8H61-M                   | 3        | 2.14%   |
| ASUS M5A78L-M                  | 3        | 2.14%   |
| Pegatron IPM41-D3              | 2        | 1.43%   |
| Lenovo ThinkCentre             | 2        | 1.43%   |
| Itautec Infoway                | 2        | 1.43%   |
| Gigabyte H61M-S2-B3            | 2        | 1.43%   |
| ASUS P5G41T-M                  | 2        | 1.43%   |
| YANYU N39SL                    | 1        | 0.71%   |
| Yanling NS-1U8L                | 1        | 0.71%   |
| ULTRATOP C2017-LIVA-ZE         | 1        | 0.71%   |
| T-bao MINI                     | 1        | 0.71%   |
| Soyo SY-YL                     | 1        | 0.71%   |
| Semp Toshiba STI               | 1        | 0.71%   |
| Procomp Ind. Eletronica G41MXE | 1        | 0.71%   |
| Positivo Positivo              | 1        | 0.71%   |
| Positivo POS-PIQ77CL           | 1        | 0.71%   |
| Positivo POS-EINM70CS          | 1        | 0.71%   |
| Positivo POS-EAA75DE           | 1        | 0.71%   |
| Pegatron IPMIP-GS              | 1        | 0.71%   |
| PCWare PW-945GCX               | 1        | 0.71%   |
| PCWare IPX1800G2               | 1        | 0.71%   |
| PCWare IPMH81G1                | 1        | 0.71%   |
| MSI U-100                      | 1        | 0.71%   |
| MSI MS-7877                    | 1        | 0.71%   |
| MSI MS-7698                    | 1        | 0.71%   |
| maiyunda www.maiyunda.com      | 1        | 0.71%   |
| Lenovo V14                     | 1        | 0.71%   |
| Lenovo IdeaCentre              | 1        | 0.71%   |
| KLLISRE X99-B5                 | 1        | 0.71%   |
| Intel Jasper                   | 1        | 0.71%   |
| Intel H81                      | 1        | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2022 | 17       | 12.14%  |
| 2016 | 17       | 12.14%  |
| 2013 | 15       | 10.71%  |
| 2010 | 13       | 9.29%   |
| 2018 | 9        | 6.43%   |
| 2012 | 8        | 5.71%   |
| 2011 | 8        | 5.71%   |
| 2019 | 7        | 5%      |
| 2017 | 7        | 5%      |
| 2008 | 7        | 5%      |
| 2021 | 6        | 4.29%   |
| 2020 | 6        | 4.29%   |
| 2014 | 6        | 4.29%   |
| 2009 | 6        | 4.29%   |
| 2015 | 4        | 2.86%   |
| 2023 | 2        | 1.43%   |
| 2007 | 2        | 1.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 140      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 140      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 56       | 38.1%   |
| 4.01-8.0    | 45       | 30.61%  |
| 16.01-24.0  | 28       | 19.05%  |
| 32.01-64.0  | 8        | 5.44%   |
| 2.01-3.0    | 8        | 5.44%   |
| 24.01-32.0  | 1        | 0.68%   |
| 64.01-256.0 | 1        | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 87       | 59.59%  |
| 0.51-1.0   | 37       | 25.34%  |
| 1.01-2.0   | 13       | 8.9%    |
| 2.01-3.0   | 4        | 2.74%   |
| 4.01-8.0   | 2        | 1.37%   |
| 16.01-24.0 | 1        | 0.68%   |
| 8.01-16.0  | 1        | 0.68%   |
| Unknown    | 1        | 0.68%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 105      | 72.41%  |
| 2      | 14       | 9.66%   |
| 0      | 10       | 6.9%    |
| 3      | 9        | 6.21%   |
| 5      | 3        | 2.07%   |
| 4      | 2        | 1.38%   |
| 7      | 1        | 0.69%   |
| 6      | 1        | 0.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 114      | 81.43%  |
| Yes       | 26       | 18.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 139      | 99.29%  |
| No        | 1        | 0.71%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 118      | 84.29%  |
| Yes       | 22       | 15.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 127      | 90.71%  |
| Yes       | 13       | 9.29%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Brazil  | 140      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| SГЈo Paulo              | 12       | 7.5%    |
| Rio de Janeiro            | 12       | 7.5%    |
| Sao Paulo                 | 9        | 5.63%   |
| Sao José dos Campos      | 5        | 3.13%   |
| Porto Alegre              | 5        | 3.13%   |
| Jaraguá do Sul           | 4        | 2.5%    |
| Curitiba                  | 4        | 2.5%    |
| Blumenau                  | 4        | 2.5%    |
| SÃ£o Paulo              | 3        | 1.88%   |
| Brasília                 | 3        | 1.88%   |
| Sao Leopoldo              | 2        | 1.25%   |
| Salvador                  | 2        | 1.25%   |
| RondonГіpolis           | 2        | 1.25%   |
| Rio Claro                 | 2        | 1.25%   |
| Pirapora                  | 2        | 1.25%   |
| Osasco                    | 2        | 1.25%   |
| Novo Hamburgo             | 2        | 1.25%   |
| Maringá                  | 2        | 1.25%   |
| Londrina                  | 2        | 1.25%   |
| Itaperuna                 | 2        | 1.25%   |
| Fortaleza                 | 2        | 1.25%   |
| Campinas                  | 2        | 1.25%   |
| BrasÃ­lia               | 2        | 1.25%   |
| Belo Horizonte            | 2        | 1.25%   |
| VitГіria da Conquista   | 1        | 0.63%   |
| Valparaiso de Goias       | 1        | 0.63%   |
| Urupes                    | 1        | 0.63%   |
| Unai                      | 1        | 0.63%   |
| Uberaba                   | 1        | 0.63%   |
| Timbo                     | 1        | 0.63%   |
| Teresina                  | 1        | 0.63%   |
| Taubate                   | 1        | 0.63%   |
| SГЈo JosГ© dos Campos | 1        | 0.63%   |
| Suzano                    | 1        | 0.63%   |
| Sumaré                   | 1        | 0.63%   |
| Serra                     | 1        | 0.63%   |
| Sao Vicente               | 1        | 0.63%   |
| Sao Jose do Rio Preto     | 1        | 0.63%   |
| Sao Goncalo               | 1        | 0.63%   |
| Sao Domingos das Dores    | 1        | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 35       | 44     | 19.66%  |
| Kingston            | 29       | 45     | 16.29%  |
| Seagate             | 25       | 52     | 14.04%  |
| Samsung Electronics | 20       | 29     | 11.24%  |
| SanDisk             | 11       | 15     | 6.18%   |
| Hoodisk             | 6        | 6      | 3.37%   |
| Crucial             | 6        | 10     | 3.37%   |
| China               | 6        | 9      | 3.37%   |
| Toshiba             | 5        | 5      | 2.81%   |
| Silicon Motion      | 5        | 6      | 2.81%   |
| A-DATA Technology   | 5        | 5      | 2.81%   |
| XrayDisk            | 3        | 3      | 1.69%   |
| NVMe                | 2        | 4      | 1.12%   |
| NTC                 | 2        | 2      | 1.12%   |
| KingSpec            | 2        | 2      | 1.12%   |
| Hitachi             | 2        | 6      | 1.12%   |
| HGST                | 2        | 3      | 1.12%   |
| Silicon             | 1        | 1      | 0.56%   |
| PNY                 | 1        | 1      | 0.56%   |
| Netac               | 1        | 1      | 0.56%   |
| Kston               | 1        | 1      | 0.56%   |
| Indilinx            | 1        | 1      | 0.56%   |
| Hewlett-Packard     | 1        | 1      | 0.56%   |
| Gigabyte Technology | 1        | 1      | 0.56%   |
| Faspeed             | 1        | 1      | 0.56%   |
| Fanxiang            | 1        | 1      | 0.56%   |
| Drevo               | 1        | 5      | 0.56%   |
| Corsair             | 1        | 1      | 0.56%   |
| Colorful            | 1        | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB         | 10       | 5.03%   |
| Kingston SA400S37120G 120GB         | 7        | 3.52%   |
| Seagate ST500DM002-1BD142 500GB     | 6        | 3.02%   |
| SanDisk SSD PLUS 120GB              | 6        | 3.02%   |
| Seagate ST1000DM010-2EP102 1TB      | 4        | 2.01%   |
| Hoodisk SSD 64GB                    | 4        | 2.01%   |
| WDC WD10EZEX-00RKKA0 1TB            | 3        | 1.51%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3        | 1.51%   |
| Seagate ST4000DM000-1F2168 4TB      | 3        | 1.51%   |
| Samsung HD502HJ 500GB               | 3        | 1.51%   |
| Samsung HD322HJ 320GB               | 3        | 1.51%   |
| Samsung HD103SJ 1TB                 | 3        | 1.51%   |
| Kingston SA400S37480G 480GB         | 3        | 1.51%   |
| Crucial CT120BX500SSD1 120GB        | 3        | 1.51%   |
| A-DATA SU630 240GB                  | 3        | 1.51%   |
| WDC WDS120G2G0A-00JH30 120GB        | 2        | 1.01%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 2        | 1.01%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 2        | 1.01%   |
| Silicon Motion NVME SSD 128GB       | 2        | 1.01%   |
| Seagate ST2000DM006-2DM164 2TB      | 2        | 1.01%   |
| SanDisk SDSSDA240G 240GB            | 2        | 1.01%   |
| SanDisk SDSSDA120G 120GB            | 2        | 1.01%   |
| Samsung HD161HJ 160GB               | 2        | 1.01%   |
| Samsung HD081GJ 80GB                | 2        | 1.01%   |
| Kingston SUV400S37120G 120GB        | 2        | 1.01%   |
| Hoodisk SSD 32GB                    | 2        | 1.01%   |
| China IM128-P130 128GB              | 2        | 1.01%   |
| A-DATA SU650 120GB                  | 2        | 1.01%   |
| XrayDisk SSD 240GB                  | 1        | 0.5%    |
| XrayDisk SSD 128GB                  | 1        | 0.5%    |
| XrayDisk 1TB SSD                    | 1        | 0.5%    |
| WDC WDS120G2G0B-00EPW0 120GB        | 1        | 0.5%    |
| WDC WD800JD-75MSA3 80GB             | 1        | 0.5%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 0.5%    |
| WDC WD5000AZLX-60K2TA1 500GB        | 1        | 0.5%    |
| WDC WD5000AVVS-63H0B1 500GB         | 1        | 0.5%    |
| WDC WD5000AVCS-632DY1 500GB         | 1        | 0.5%    |
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 0.5%    |
| WDC WD5000AAKX-00ERMA0 500GB        | 1        | 0.5%    |
| WDC WD5000AAKS-08V0A0 500GB         | 1        | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 33       | 41     | 38.82%  |
| Seagate             | 25       | 52     | 29.41%  |
| Samsung Electronics | 16       | 22     | 18.82%  |
| Toshiba             | 5        | 5      | 5.88%   |
| NVMe                | 2        | 4      | 2.35%   |
| Hitachi             | 2        | 6      | 2.35%   |
| HGST                | 1        | 2      | 1.18%   |
| Hewlett-Packard     | 1        | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 26       | 42     | 31.33%  |
| SanDisk             | 11       | 15     | 13.25%  |
| Hoodisk             | 6        | 6      | 7.23%   |
| Crucial             | 6        | 10     | 7.23%   |
| China               | 6        | 9      | 7.23%   |
| A-DATA Technology   | 5        | 5      | 6.02%   |
| XrayDisk            | 3        | 3      | 3.61%   |
| WDC                 | 3        | 3      | 3.61%   |
| Samsung Electronics | 2        | 2      | 2.41%   |
| NTC                 | 2        | 2      | 2.41%   |
| KingSpec            | 2        | 2      | 2.41%   |
| Silicon             | 1        | 1      | 1.2%    |
| PNY                 | 1        | 1      | 1.2%    |
| Netac               | 1        | 1      | 1.2%    |
| Kston               | 1        | 1      | 1.2%    |
| Indilinx            | 1        | 1      | 1.2%    |
| HGST                | 1        | 1      | 1.2%    |
| Gigabyte Technology | 1        | 1      | 1.2%    |
| Faspeed             | 1        | 1      | 1.2%    |
| Fanxiang            | 1        | 1      | 1.2%    |
| Drevo               | 1        | 5      | 1.2%    |
| Corsair             | 1        | 1      | 1.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 74       | 114    | 47.74%  |
| HDD  | 70       | 133    | 45.16%  |
| NVMe | 11       | 15     | 7.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 121      | 247    | 91.67%  |
| NVMe | 11       | 15     | 8.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 112      | 189    | 79.43%  |
| 0.51-1.0   | 18       | 31     | 12.77%  |
| 1.01-2.0   | 8        | 19     | 5.67%   |
| 3.01-4.0   | 3        | 8      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 50       | 32.47%  |
| 1-20           | 32       | 20.78%  |
| 251-500        | 25       | 16.23%  |
| 51-100         | 22       | 14.29%  |
| 21-50          | 13       | 8.44%   |
| 501-1000       | 8        | 5.19%   |
| 2001-3000      | 2        | 1.3%    |
| More than 3000 | 1        | 0.65%   |
| 1001-2000      | 1        | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 128      | 90.78%  |
| 21-50     | 7        | 4.96%   |
| 101-250   | 3        | 2.13%   |
| 501-1000  | 2        | 1.42%   |
| 2001-3000 | 1        | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Desktops | Drives | Percent |
|-------------------------------------------|----------|--------|---------|
| Samsung Electronics HD322HJ 320GB         | 3        | 4      | 5.77%   |
| WDC WD10EZEX-00RKKA0 1TB                  | 2        | 2      | 3.85%   |
| Seagate ST500DM002-1BD142 500GB           | 2        | 2      | 3.85%   |
| Samsung Electronics HD161HJ 160GB         | 2        | 2      | 3.85%   |
| XrayDisk SSD 240GB                        | 1        | 1      | 1.92%   |
| WDC WD5000LPVX-22V0TT0 500GB              | 1        | 1      | 1.92%   |
| WDC WD5000AVVS-63H0B1 500GB               | 1        | 1      | 1.92%   |
| WDC WD5000AAKX-00U6AA0 500GB              | 1        | 1      | 1.92%   |
| WDC WD5000AAKX-00ERMA0 500GB              | 1        | 1      | 1.92%   |
| WDC WD5000AAKS-08V0A0 500GB               | 1        | 1      | 1.92%   |
| WDC WD5000AAKS-00UU3A0 500GB              | 1        | 1      | 1.92%   |
| WDC WD3200LPVX-22V0TT0 320GB              | 1        | 1      | 1.92%   |
| WDC WD3200BEVT-00A0RT0 233GB              | 1        | 1      | 1.92%   |
| WDC WD3200AAKS-00UU3A0 320GB              | 1        | 1      | 1.92%   |
| WDC WD3200AAJS-56M0A0 320GB               | 1        | 1      | 1.92%   |
| WDC WD3200AAJS-00YZCA0 320GB              | 1        | 1      | 1.92%   |
| WDC WD2500AAJS-75M0A0 250GB               | 1        | 1      | 1.92%   |
| WDC WD10PURX-64E5EY0 1TB                  | 1        | 1      | 1.92%   |
| WDC WD10EADS-65M2BX 1TB                   | 1        | 1      | 1.92%   |
| Toshiba MQ01ABD050 500GB                  | 1        | 1      | 1.92%   |
| Toshiba MK1255GSX H 120GB                 | 1        | 1      | 1.92%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB | 1        | 1      | 1.92%   |
| Seagate ST9160314AS 160GB                 | 1        | 1      | 1.92%   |
| Seagate ST500LT012-9WS142 500GB           | 1        | 1      | 1.92%   |
| Seagate ST500LM021-1KJ152 500GB           | 1        | 1      | 1.92%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1        | 1      | 1.92%   |
| Seagate ST500DM002-1BC142 500GB           | 1        | 1      | 1.92%   |
| Seagate ST3250310AS 250GB                 | 1        | 1      | 1.92%   |
| Seagate ST320LM001 HN-M320MBB 320GB       | 1        | 1      | 1.92%   |
| Seagate ST2000DM006-2DM164 2TB            | 1        | 1      | 1.92%   |
| Seagate ST2000DM001-1E6164 2TB            | 1        | 1      | 1.92%   |
| Seagate ST2000DL003-9VT166 2TB            | 1        | 9      | 1.92%   |
| SanDisk SSD PLUS 240 GB                   | 1        | 1      | 1.92%   |
| Samsung Electronics HM320II 320GB         | 1        | 2      | 1.92%   |
| Samsung Electronics HD642JJ 640GB         | 1        | 1      | 1.92%   |
| Samsung Electronics HD502HJ 500GB         | 1        | 1      | 1.92%   |
| Samsung Electronics HD203WI 2TB           | 1        | 1      | 1.92%   |
| Samsung Electronics HD103SJ 1TB           | 1        | 1      | 1.92%   |
| Samsung Electronics HD081GJ 80GB          | 1        | 1      | 1.92%   |
| Netac SSD 128GB                           | 1        | 1      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 16     | 28.57%  |
| Seagate             | 12       | 20     | 24.49%  |
| Samsung Electronics | 10       | 13     | 20.41%  |
| Toshiba             | 2        | 2      | 4.08%   |
| Kingston            | 2        | 2      | 4.08%   |
| Hitachi             | 2        | 6      | 4.08%   |
| XrayDisk            | 1        | 1      | 2.04%   |
| Silicon Motion      | 1        | 1      | 2.04%   |
| SanDisk             | 1        | 1      | 2.04%   |
| Netac               | 1        | 1      | 2.04%   |
| KingSpec            | 1        | 1      | 2.04%   |
| HGST                | 1        | 1      | 2.04%   |
| Corsair             | 1        | 1      | 2.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 16     | 35%     |
| Seagate             | 12       | 20     | 30%     |
| Samsung Electronics | 10       | 13     | 25%     |
| Toshiba             | 2        | 2      | 5%      |
| Hitachi             | 2        | 6      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 37       | 57     | 80.43%  |
| SSD  | 8        | 8      | 17.39%  |
| NVMe | 1        | 1      | 2.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD3200AAJS-00YZCA0 320GB    | 1        | 1      | 50%     |
| Samsung Electronics HD103SJ 1TB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 104      | 183    | 66.24%  |
| Malfunc  | 44       | 66     | 28.03%  |
| Detected | 7        | 11     | 4.46%   |
| Failed   | 2        | 2      | 1.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 113      | 70.63%  |
| AMD                            | 24       | 15%     |
| Silicon Motion                 | 8        | 5%      |
| Kingston Technology Company    | 3        | 1.88%   |
| Samsung Electronics            | 2        | 1.25%   |
| Nvidia                         | 2        | 1.25%   |
| Solid State Storage Technology | 1        | 0.63%   |
| SK hynix                       | 1        | 0.63%   |
| Realtek Semiconductor          | 1        | 0.63%   |
| JMicron Technology             | 1        | 0.63%   |
| Integrated Technology Express  | 1        | 0.63%   |
| Hewlett-Packard                | 1        | 0.63%   |
| ASMedia Technology             | 1        | 0.63%   |
| Adaptec                        | 1        | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 21       | 10.5%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13       | 6.5%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 11       | 5.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 8        | 4%      |
| Intel Jasper Lake SATA AHCI Controller                                                  | 8        | 4%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 4%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 4%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 4%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7        | 3.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 3.5%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 3%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 3%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 3%      |
| Intel SATA Controller [RAID mode]                                                       | 5        | 2.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5        | 2.5%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4        | 2%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 1.5%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 1.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3        | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.5%    |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 1.5%    |
| Nvidia MCP61 SATA Controller                                                            | 2        | 1%      |
| Nvidia MCP61 IDE                                                                        | 2        | 1%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 1%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1%      |
| AMD FCH SATA Controller D                                                               | 2        | 1%      |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1%      |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                          | 1        | 0.5%    |
| SK hynix BC511 NVMe SSD                                                                 | 1        | 0.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.5%    |
| Realtek NVMe Controller                                                                 | 1        | 0.5%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1        | 0.5%    |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 0.5%    |
| Kingston Company NVMe Controller                                                        | 1        | 0.5%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.5%    |
| Intel Tiger Lake-LP SATA Controller                                                     | 1        | 0.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 0.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 94       | 57.67%  |
| IDE  | 45       | 27.61%  |
| NVMe | 16       | 9.82%   |
| RAID | 7        | 4.29%   |
| SCSI | 1        | 0.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 116      | 81.69%  |
| AMD    | 26       | 18.31%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Celeron N5105 @ 2.00GHz               | 6        | 4.2%    |
| Intel Core i3-7100 CPU @ 3.90GHz            | 4        | 2.8%    |
| Intel Celeron CPU J1800 @ 2.41GHz           | 4        | 2.8%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 2.1%    |
| Intel Core i3-5005U CPU @ 2.00GHz           | 3        | 2.1%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 2.1%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 2.1%    |
| Intel Celeron J4125 CPU @ 2.00GHz           | 3        | 2.1%    |
| AMD FX-8320E Eight-Core Processor           | 3        | 2.1%    |
| Intel Pentium Silver N6005 @ 2.00GHz        | 2        | 1.4%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 1.4%    |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.4%    |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 1.4%    |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2        | 1.4%    |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 1.4%    |
| Intel Core i3-2100 CPU                      | 2        | 1.4%    |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 1.4%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.4%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 1.4%    |
| Intel Core 2 Duo CPU                        | 2        | 1.4%    |
| Intel Celeron CPU 847 @ 1.10GHz             | 2        | 1.4%    |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5506 @ 2.13GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 0.7%    |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz        | 1        | 0.7%    |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 0.7%    |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1        | 0.7%    |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 0.7%    |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.7%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.7%    |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.7%    |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.7%    |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1        | 0.7%    |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.7%    |
| Intel Pentium CPU G2020T @ 2.50GHz          | 1        | 0.7%    |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.7%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.7%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 0.7%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 28       | 19.72%  |
| Intel Celeron           | 23       | 16.2%   |
| Intel Core i5           | 18       | 12.68%  |
| Intel Core 2 Duo        | 12       | 8.45%   |
| AMD FX                  | 8        | 5.63%   |
| Intel Xeon              | 7        | 4.93%   |
| Intel Pentium Dual-Core | 6        | 4.23%   |
| Intel Core i7           | 5        | 3.52%   |
| AMD Ryzen 5             | 5        | 3.52%   |
| Intel Pentium           | 4        | 2.82%   |
| Intel Core 2 Quad       | 4        | 2.82%   |
| Other                   | 3        | 2.11%   |
| Intel Atom              | 3        | 2.11%   |
| Intel Pentium Silver    | 2        | 1.41%   |
| AMD Ryzen 7             | 2        | 1.41%   |
| Intel Pentium Dual      | 1        | 0.7%    |
| Intel Core 2            | 1        | 0.7%    |
| AMD Turion II Neo       | 1        | 0.7%    |
| AMD Ryzen 5 PRO         | 1        | 0.7%    |
| AMD Ryzen 3 PRO         | 1        | 0.7%    |
| AMD Ryzen 3             | 1        | 0.7%    |
| AMD PRO A8              | 1        | 0.7%    |
| AMD Phenom              | 1        | 0.7%    |
| AMD E                   | 1        | 0.7%    |
| AMD Athlon II X2        | 1        | 0.7%    |
| AMD Athlon              | 1        | 0.7%    |
| AMD A10                 | 1        | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 60       | 41.67%  |
| 4       | 51       | 35.42%  |
| 8       | 12       | 8.33%   |
| 6       | 7        | 4.86%   |
| Unknown | 7        | 4.86%   |
| 12      | 4        | 2.78%   |
| 16      | 2        | 1.39%   |
| 1       | 1        | 0.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 139      | 99.29%  |
| 2      | 1        | 0.71%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 93       | 65.96%  |
| 2       | 41       | 29.08%  |
| Unknown | 7        | 4.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 20       | 13.99%  |
| Haswell       | 14       | 9.79%   |
| KabyLake      | 13       | 9.09%   |
| IvyBridge     | 13       | 9.09%   |
| Unknown       | 12       | 8.39%   |
| SandyBridge   | 10       | 6.99%   |
| Zen+          | 7        | 4.9%    |
| Silvermont    | 7        | 4.9%    |
| Piledriver    | 6        | 4.2%    |
| Core          | 6        | 4.2%    |
| Goldmont plus | 5        | 3.5%    |
| Westmere      | 4        | 2.8%    |
| Broadwell     | 4        | 2.8%    |
| K10           | 3        | 2.1%    |
| Zen 3         | 2        | 1.4%    |
| Zen           | 2        | 1.4%    |
| Steamroller   | 2        | 1.4%    |
| Skylake       | 2        | 1.4%    |
| Nehalem       | 2        | 1.4%    |
| CometLake     | 2        | 1.4%    |
| Bulldozer     | 2        | 1.4%    |
| Bonnell       | 2        | 1.4%    |
| TigerLake     | 1        | 0.7%    |
| Goldmont      | 1        | 0.7%    |
| Bobcat        | 1        | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 96       | 65.75%  |
| AMD                        | 28       | 19.18%  |
| Nvidia                     | 19       | 13.01%  |
| Matrox Electronics Systems | 2        | 1.37%   |
| ASPEED Technology          | 1        | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 11       | 7.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 6.04%   |
| Intel JasperLake [UHD Graphics]                                             | 9        | 6.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 6.04%   |
| Intel HD Graphics 630                                                       | 7        | 4.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 7        | 4.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 6        | 4.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 3.36%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 5        | 3.36%   |
| Intel HD Graphics 5500                                                      | 4        | 2.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 2.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3        | 2.01%   |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 2.01%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 2.01%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 2.01%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 2.01%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.34%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.34%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.34%   |
| Matrox Electronics Systems MGA G200EH                                       | 2        | 1.34%   |
| Intel HD Graphics 530                                                       | 2        | 1.34%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.34%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.34%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 2        | 1.34%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 1.34%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.34%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.34%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.34%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.67%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.67%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.67%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.67%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 0.67%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 0.67%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1        | 0.67%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 0.67%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 88       | 61.54%  |
| 1 x AMD        | 25       | 17.48%  |
| 1 x Nvidia     | 18       | 12.59%  |
| 2 x Intel      | 4        | 2.8%    |
| Intel + AMD    | 3        | 2.1%    |
| 1 x Matrox     | 2        | 1.4%    |
| Other          | 1        | 0.7%    |
| Intel + Nvidia | 1        | 0.7%    |
| 1 x ASPEED     | 1        | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 128      | 90.14%  |
| Proprietary | 13       | 9.15%   |
| Unknown     | 1        | 0.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 112      | 77.78%  |
| 0.51-1.0   | 9        | 6.25%   |
| 1.01-2.0   | 8        | 5.56%   |
| 3.01-4.0   | 6        | 4.17%   |
| 0.01-0.5   | 5        | 3.47%   |
| 7.01-8.0   | 3        | 2.08%   |
| 2.01-3.0   | 1        | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 18       | 40.91%  |
| Samsung Electronics | 12       | 27.27%  |
| Philips             | 4        | 9.09%   |
| AOC                 | 2        | 4.55%   |
| VIE                 | 1        | 2.27%   |
| Semp Toshiba        | 1        | 2.27%   |
| Panasonic           | 1        | 2.27%   |
| LG Electronics      | 1        | 2.27%   |
| Lenovo              | 1        | 2.27%   |
| Hewlett-Packard     | 1        | 2.27%   |
| Chimei Innolux      | 1        | 2.27%   |
| ASUSTek Computer    | 1        | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0601 1600x900                      | 2        | 4.17%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch  | 2        | 4.17%   |
| VIE E195 VIE1950 1600x900 410x280mm 19.5-inch                        | 1        | 2.08%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch            | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch  | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch  | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                     | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch  | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch  | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 310x230mm 15.2-inch | 1        | 2.08%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch  | 1        | 2.08%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 440x250mm 19.9-inch | 1        | 2.08%   |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch     | 1        | 2.08%   |
| Samsung Electronics LCD Monitor SMT27A550 1920x1080                  | 1        | 2.08%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 1        | 2.08%   |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch              | 1        | 2.08%   |
| Philips LCD Monitor PHL2051 1600x900 440x250mm 19.9-inch             | 1        | 2.08%   |
| Philips 221EL PHLC056 1920x1080 480x270mm 21.7-inch                  | 1        | 2.08%   |
| Panasonic TV MEIC136 1280x720 698x392mm 31.5-inch                    | 1        | 2.08%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 3640x1920                    | 1        | 2.08%   |
| LG Electronics LCD Monitor 23MP55                                    | 1        | 2.08%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 480x270mm 21.7-inch             | 1        | 2.08%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch           | 1        | 2.08%   |
| Goldstar W2242 GSM4B6F 1680x1050 490x320mm 23.0-inch                 | 1        | 2.08%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                  | 1        | 2.08%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                  | 1        | 2.08%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                  | 1        | 2.08%   |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch          | 1        | 2.08%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch          | 1        | 2.08%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 1        | 2.08%   |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch           | 1        | 2.08%   |
| Goldstar L1950H GSM4AA2 1280x1024 380x300mm 19.1-inch                | 1        | 2.08%   |
| Goldstar L1753T GSM4433 1280x1024 340x270mm 17.1-inch                | 1        | 2.08%   |
| Goldstar L1553S GSM3BB0 1024x768 300x230mm 14.9-inch                 | 1        | 2.08%   |
| Goldstar E2241 GSM581A 1920x1080 480x270mm 21.7-inch                 | 1        | 2.08%   |
| Goldstar E2041 GSM4EC9 1600x900 450x250mm 20.3-inch                  | 1        | 2.08%   |
| Goldstar D2342P GSM5840 1920x1080 510x290mm 23.1-inch                | 1        | 2.08%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                | 1        | 2.08%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                | 1        | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 19       | 41.3%   |
| 1600x900 (HD+)     | 7        | 15.22%  |
| 1366x768 (WXGA)    | 4        | 8.7%    |
| 2560x1080          | 3        | 6.52%   |
| 1280x1024 (SXGA)   | 3        | 6.52%   |
| 1440x900 (WXGA+)   | 2        | 4.35%   |
| 1360x768           | 2        | 4.35%   |
| 1024x768 (XGA)     | 2        | 4.35%   |
| 3640x1920          | 1        | 2.17%   |
| 1680x1050 (WSXGA+) | 1        | 2.17%   |
| 1280x720 (HD)      | 1        | 2.17%   |
| Unknown            | 1        | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 9        | 19.57%  |
| 23      | 7        | 15.22%  |
| 19      | 7        | 15.22%  |
| 18      | 5        | 10.87%  |
| Unknown | 5        | 10.87%  |
| 34      | 3        | 6.52%   |
| 20      | 2        | 4.35%   |
| 15      | 2        | 4.35%   |
| 13      | 2        | 4.35%   |
| 31      | 1        | 2.17%   |
| 24      | 1        | 2.17%   |
| 17      | 1        | 2.17%   |
| 14      | 1        | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 22       | 48.89%  |
| 501-600     | 7        | 15.56%  |
| Unknown     | 5        | 11.11%  |
| 301-350     | 4        | 8.89%   |
| 701-800     | 3        | 6.67%   |
| 201-300     | 2        | 4.44%   |
| 601-700     | 1        | 2.22%   |
| 351-400     | 1        | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 30       | 68.18%  |
| 4/3     | 3        | 6.82%   |
| 21/9    | 3        | 6.82%   |
| 5/4     | 2        | 4.55%   |
| 3/2     | 2        | 4.55%   |
| 16/10   | 2        | 4.55%   |
| Unknown | 2        | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 17       | 36.96%  |
| 151-200        | 9        | 19.57%  |
| 141-150        | 6        | 13.04%  |
| Unknown        | 5        | 10.87%  |
| 351-500        | 4        | 8.7%    |
| 91-100         | 2        | 4.35%   |
| 81-90          | 1        | 2.17%   |
| 111-120        | 1        | 2.17%   |
| 101-110        | 1        | 2.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 28       | 60.87%  |
| 101-120 | 11       | 23.91%  |
| Unknown | 5        | 10.87%  |
| 1-50    | 1        | 2.17%   |
| 121-160 | 1        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 90       | 63.38%  |
| 1     | 48       | 33.8%   |
| 2     | 4        | 2.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 95       | 50%     |
| Intel                 | 61       | 32.11%  |
| Qualcomm Atheros      | 9        | 4.74%   |
| Broadcom              | 8        | 4.21%   |
| Ralink                | 4        | 2.11%   |
| D-Link System         | 3        | 1.58%   |
| Ralink Technology     | 2        | 1.05%   |
| TP-Link               | 1        | 0.53%   |
| STMicroelectronics    | 1        | 0.53%   |
| Samsung Electronics   | 1        | 0.53%   |
| MediaTek              | 1        | 0.53%   |
| ICS Advent            | 1        | 0.53%   |
| Edimax Technology     | 1        | 0.53%   |
| Arduino SA            | 1        | 0.53%   |
| 3Com                  | 1        | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 78       | 37.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 12       | 5.74%   |
| Intel I211 Gigabit Network Connection                                         | 11       | 5.26%   |
| Intel Ethernet Controller I226-V                                              | 7        | 3.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6        | 2.87%   |
| Intel Ethernet Controller I225-V                                              | 6        | 2.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 4        | 1.91%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 1.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3        | 1.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 1.44%   |
| Intel 82578DC Gigabit Network Connection                                      | 3        | 1.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.96%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                          | 2        | 0.96%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 2        | 0.96%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 2        | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.96%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 0.96%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 0.96%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 0.96%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.96%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 0.96%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 0.96%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 0.96%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.96%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 0.96%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 0.96%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 0.96%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.96%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.48%   |
| STMicroelectronics Virtual COM Port                                           | 1        | 0.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.48%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1        | 0.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1        | 0.48%   |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1        | 0.48%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.48%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                  | 1        | 0.48%   |
| Ralink RT5370 Wireless Adapter                                                | 1        | 0.48%   |
| Ralink MT7601U Wireless Adapter                                               | 1        | 0.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1        | 0.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 10       | 38.46%  |
| Intel                 | 5        | 19.23%  |
| Ralink                | 4        | 15.38%  |
| Ralink Technology     | 2        | 7.69%   |
| Qualcomm Atheros      | 2        | 7.69%   |
| TP-Link               | 1        | 3.85%   |
| Edimax Technology     | 1        | 3.85%   |
| D-Link System         | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4        | 14.81%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 11.11%  |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 2        | 7.41%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2        | 7.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1        | 3.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 3.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1        | 3.7%    |
| Realtek RTL8187SE Wireless LAN Controller                            | 1        | 3.7%    |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                         | 1        | 3.7%    |
| Ralink RT5370 Wireless Adapter                                       | 1        | 3.7%    |
| Ralink MT7601U Wireless Adapter                                      | 1        | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 3.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 3.7%    |
| Intel Wireless 7265                                                  | 1        | 3.7%    |
| Intel Wireless 3165                                                  | 1        | 3.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1        | 3.7%    |
| Intel Wi-Fi 6 AX201                                                  | 1        | 3.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1        | 3.7%    |
| Edimax AC600 Wireless LAN USB Adapter                                | 1        | 3.7%    |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1        | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 93       | 53.76%  |
| Intel                 | 59       | 34.1%   |
| Broadcom              | 8        | 4.62%   |
| Qualcomm Atheros      | 7        | 4.05%   |
| D-Link System         | 2        | 1.16%   |
| Samsung Electronics   | 1        | 0.58%   |
| MediaTek              | 1        | 0.58%   |
| ICS Advent            | 1        | 0.58%   |
| 3Com                  | 1        | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 78       | 43.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 12       | 6.67%   |
| Intel I211 Gigabit Network Connection                                         | 11       | 6.11%   |
| Intel Ethernet Controller I226-V                                              | 7        | 3.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6        | 3.33%   |
| Intel Ethernet Controller I225-V                                              | 6        | 3.33%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 1.67%   |
| Intel 82578DC Gigabit Network Connection                                      | 3        | 1.67%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 1.11%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 2        | 1.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 1.11%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 1.11%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 1.11%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.11%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 1.11%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 1.11%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 1.11%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 1.11%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 1.11%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 1.11%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 1.11%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 1.11%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 1.11%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 0.56%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.56%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 0.56%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 0.56%   |
| Intel 82575GB Gigabit Network Connection                                      | 1        | 0.56%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.56%   |
| Intel 82562V-2 10/100 Network Connection                                      | 1        | 0.56%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 0.56%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                       | 1        | 0.56%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1        | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 139      | 85.28%  |
| WiFi     | 22       | 13.5%   |
| Modem    | 2        | 1.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 137      | 92.57%  |
| WiFi     | 11       | 7.43%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 46       | 31.94%  |
| 2     | 39       | 27.08%  |
| 4     | 28       | 19.44%  |
| 3     | 19       | 13.19%  |
| 5     | 8        | 5.56%   |
| 6     | 4        | 2.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 131      | 90.34%  |
| Yes  | 14       | 9.66%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Realtek Semiconductor   | 5        | 38.46%  |
| Intel                   | 5        | 38.46%  |
| Cambridge Silicon Radio | 3        | 23.08%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Adapter                           | 5        | 38.46%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 23.08%  |
| Intel Bluetooth wireless interface                  | 2        | 15.38%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 7.69%   |
| Intel AX210 Bluetooth                               | 1        | 7.69%   |
| Intel AX201 Bluetooth                               | 1        | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 95       | 62.09%  |
| AMD                                             | 33       | 21.57%  |
| Nvidia                                          | 18       | 11.76%  |
| C-Media Electronics                             | 4        | 2.61%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.65%   |
| KTMicro                                         | 1        | 0.65%   |
| Generalplus Technology                          | 1        | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 19       | 10.61%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10       | 5.59%   |
| Intel Jasper Lake HD Audio                                                 | 9        | 5.03%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 4.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7        | 3.91%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7        | 3.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 3.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 3.35%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 3.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5        | 2.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 2.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4        | 2.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4        | 2.23%   |
| Intel Broadwell-U Audio Controller                                         | 4        | 2.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 2.23%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3        | 1.68%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.68%   |
| Intel 8 Series HD Audio Controller                                         | 3        | 1.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.68%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.68%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.68%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 1.68%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 1.68%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 1.12%   |
| Nvidia High Definition Audio Controller                                    | 2        | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 1.12%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 1.12%   |
| C-Media Electronics CM108 Audio Controller                                 | 2        | 1.12%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2        | 1.12%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 1.12%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2        | 1.12%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.12%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.56%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.56%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 40       | 25.81%  |
| Kingston            | 27       | 17.42%  |
| Smart               | 14       | 9.03%   |
| Crucial             | 9        | 5.81%   |
| Unknown             | 9        | 5.81%   |
| Micron Technology   | 7        | 4.52%   |
| Samsung Electronics | 6        | 3.87%   |
| A-DATA Technology   | 6        | 3.87%   |
| Teikon              | 5        | 3.23%   |
| Corsair             | 5        | 3.23%   |
| SK hynix            | 2        | 1.29%   |
| Patriot             | 2        | 1.29%   |
| Hewlett-Packard     | 2        | 1.29%   |
| G.Skill             | 2        | 1.29%   |
| Unknown (0x5846)    | 1        | 0.65%   |
| Toshiba             | 1        | 0.65%   |
| Tigo                | 1        | 0.65%   |
| SK_Hynix            | 1        | 0.65%   |
| RZX                 | 1        | 0.65%   |
| PUSKILL             | 1        | 0.65%   |
| Nanya Technology    | 1        | 0.65%   |
| Multilaser          | 1        | 0.65%   |
| MemoWise            | 1        | 0.65%   |
| Lexar               | 1        | 0.65%   |
| Kreton              | 1        | 0.65%   |
| Kllisre             | 1        | 0.65%   |
| KingSpec            | 1        | 0.65%   |
| Juhor               | 1        | 0.65%   |
| Hikvision           | 1        | 0.65%   |
| GLOWAY              | 1        | 0.65%   |
| Galaxy              | 1        | 0.65%   |
| CSX                 | 1        | 0.65%   |
| Apacer              | 1        | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown                                                | 9        | 5.33%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 4        | 2.37%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s    | 4        | 2.37%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 3        | 1.78%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 3        | 1.78%   |
| Unknown RAM Module 2GB DIMM DDR2                       | 3        | 1.78%   |
| Unknown RAM Module 2GB DIMM                            | 3        | 1.78%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 2        | 1.18%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 2        | 1.18%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 2        | 1.18%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 2        | 1.18%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s              | 2        | 1.18%   |
| Teikon RAM TMTS8G58DFRBFKB-16 8GB SODIMM DDR3 1600MT/s | 2        | 1.18%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s    | 2        | 1.18%   |
| Patriot RAM 2666 C16 Series 16GB DIMM DDR4 3000MT/s    | 2        | 1.18%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s              | 2        | 1.18%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s      | 2        | 1.18%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1866MT/s      | 2        | 1.18%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s  | 2        | 1.18%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s            | 2        | 1.18%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                   | 1        | 0.59%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s           | 1        | 0.59%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s           | 1        | 0.59%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s               | 1        | 0.59%   |
| Unknown RAM Module 4GB DIMM 400MT/s                    | 1        | 0.59%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 0.59%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s           | 1        | 0.59%   |
| Unknown RAM Module 4096MB DIMM DDR2                    | 1        | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s             | 1        | 0.59%   |
| Unknown RAM Module 2GB DIMM SDRAM 1333MT/s             | 1        | 0.59%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 1        | 0.59%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 1        | 0.59%   |
| Unknown RAM Module 2GB DIMM 667MT/s                    | 1        | 0.59%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                   | 1        | 0.59%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 1        | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s           | 1        | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s           | 1        | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 1        | 0.59%   |
| Unknown RAM Module 2048MB DIMM DDR2                    | 1        | 0.59%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 1        | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 58       | 43.28%  |
| DDR4    | 41       | 30.6%   |
| DDR2    | 12       | 8.96%   |
| Unknown | 12       | 8.96%   |
| SDRAM   | 10       | 7.46%   |
| LPDDR4  | 1        | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 105      | 78.95%  |
| SODIMM       | 26       | 19.55%  |
| Row Of Chips | 1        | 0.75%   |
| Chip         | 1        | 0.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 47       | 32.41%  |
| 8192  | 46       | 31.72%  |
| 2048  | 37       | 25.52%  |
| 16384 | 11       | 7.59%   |
| 1024  | 3        | 2.07%   |
| 32768 | 1        | 0.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 31       | 21.68%  |
| 1333    | 28       | 19.58%  |
| Unknown | 15       | 10.49%  |
| 2400    | 14       | 9.79%   |
| 2667    | 12       | 8.39%   |
| 800     | 10       | 6.99%   |
| 3200    | 8        | 5.59%   |
| 2133    | 6        | 4.2%    |
| 2666    | 4        | 2.8%    |
| 1866    | 3        | 2.1%    |
| 3000    | 2        | 1.4%    |
| 1867    | 2        | 1.4%    |
| 1066    | 2        | 1.4%    |
| 667     | 2        | 1.4%    |
| 400     | 2        | 1.4%    |
| 1067    | 1        | 0.7%    |
| 333     | 1        | 0.7%    |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 2        | 50%     |
| Chicony Electronics | 1        | 25%     |
| Aveo Technology     | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech Webcam C270        | 1        | 25%     |
| Logitech HD Pro Webcam C920 | 1        | 25%     |
| Chicony Integrated Camera   | 1        | 25%     |
| Aveo USB2.0 Camera          | 1        | 25%     |

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
| 1     | 67       | 47.52%  |
| 0     | 60       | 42.55%  |
| 2     | 11       | 7.8%    |
| 3     | 2        | 1.42%   |
| 4     | 1        | 0.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 74       | 82.22%  |
| Net/wireless             | 8        | 8.89%   |
| Sound                    | 4        | 4.44%   |
| Bluetooth                | 2        | 2.22%   |
| Graphics card            | 1        | 1.11%   |
| Firewire controller      | 1        | 1.11%   |

