BSD in Poland - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in Poland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Poland/Desktop/README.md) and [notebooks](/Location/Poland/Notebook/README.md).

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

Total: 678

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | QDNV01                      | Desktop     | [ca2dd0099d](https://bsd-hardware.info/?probe=ca2dd0099d) | Jan 05, 2025 |
| HP            | Unknown                     | Notebook    | [babd844cfb](https://bsd-hardware.info/?probe=babd844cfb) | Jan 04, 2025 |
| HP            | Unknown                     | Notebook    | [54cd46759e](https://bsd-hardware.info/?probe=54cd46759e) | Jan 03, 2025 |
| Dell          | 081N4V A04                  | Server      | [029563c5c1](https://bsd-hardware.info/?probe=029563c5c1) | Dec 31, 2024 |
| Dell          | 0JP3NX A00                  | Desktop     | [27d474564d](https://bsd-hardware.info/?probe=27d474564d) | Dec 24, 2024 |
| Lenovo        | [3633AC1] STC               | Server      | [04693e20ee](https://bsd-hardware.info/?probe=04693e20ee) | Dec 23, 2024 |
| MSI           | Z97I AC                     | Desktop     | [b6ff881901](https://bsd-hardware.info/?probe=b6ff881901) | Dec 21, 2024 |
| Supermicro    | X11SSL-F                    | Server      | [d01d1b37b8](https://bsd-hardware.info/?probe=d01d1b37b8) | Dec 17, 2024 |
| PC Engines    | APU2                        | Desktop     | [731738fd98](https://bsd-hardware.info/?probe=731738fd98) | Dec 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1f7a60f418](https://bsd-hardware.info/?probe=1f7a60f418) | Dec 13, 2024 |
| MSI           | Z97I AC                     | Desktop     | [844a11760c](https://bsd-hardware.info/?probe=844a11760c) | Dec 13, 2024 |
| Dell          | 0VRCY5 A14                  | Server      | [ea3362af64](https://bsd-hardware.info/?probe=ea3362af64) | Dec 12, 2024 |
| MSI           | Z97 GAMING 3                | Desktop     | [9cd14a585d](https://bsd-hardware.info/?probe=9cd14a585d) | Dec 04, 2024 |
| HP            | 829A                        | Mini pc     | [a7db169329](https://bsd-hardware.info/?probe=a7db169329) | Dec 04, 2024 |
| OEM           | BayTrail JHS60K             | Desktop     | [0e795e9e06](https://bsd-hardware.info/?probe=0e795e9e06) | Nov 30, 2024 |
| Lenovo        | 0x30F617AA SDK0J40705 WI... | Desktop     | [793b039943](https://bsd-hardware.info/?probe=793b039943) | Nov 29, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b6aaae01ed](https://bsd-hardware.info/?probe=b6aaae01ed) | Nov 29, 2024 |
| Dell          | 02C2CP A02                  | Server      | [1de5f56857](https://bsd-hardware.info/?probe=1de5f56857) | Nov 27, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [6379c6aa6d](https://bsd-hardware.info/?probe=6379c6aa6d) | Nov 25, 2024 |
| iEi           | B542 V1.00                  | Desktop     | [fc2b00d368](https://bsd-hardware.info/?probe=fc2b00d368) | Nov 24, 2024 |
| HP            | 255 G7 Notebook PC          | Notebook    | [9422dbf997](https://bsd-hardware.info/?probe=9422dbf997) | Nov 22, 2024 |
| Unknown       | QDNV01                      | Desktop     | [3c7e558c94](https://bsd-hardware.info/?probe=3c7e558c94) | Nov 22, 2024 |
| Acer          | Revo RL80                   | Desktop     | [51e0b0c016](https://bsd-hardware.info/?probe=51e0b0c016) | Nov 22, 2024 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [e59272c611](https://bsd-hardware.info/?probe=e59272c611) | Nov 18, 2024 |
| ASRock        | N100M                       | Desktop     | [62d2f6b522](https://bsd-hardware.info/?probe=62d2f6b522) | Nov 14, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [8b74f88be7](https://bsd-hardware.info/?probe=8b74f88be7) | Nov 14, 2024 |
| MSI           | B450-A PRO MAX              | Desktop     | [265f542246](https://bsd-hardware.info/?probe=265f542246) | Nov 12, 2024 |
| HP            | OMEN by Transcend Gaming... | Notebook    | [213d36f877](https://bsd-hardware.info/?probe=213d36f877) | Nov 10, 2024 |
| Lenovo        | ThinkPad X280 20KES2VQ00    | Notebook    | [d864971168](https://bsd-hardware.info/?probe=d864971168) | Oct 30, 2024 |
| HP            | 17E2                        | Desktop     | [1125a48b97](https://bsd-hardware.info/?probe=1125a48b97) | Oct 27, 2024 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [1195b00783](https://bsd-hardware.info/?probe=1195b00783) | Oct 18, 2024 |
| Dell          | 04R2JF A00                  | Mini pc     | [6782d71a2f](https://bsd-hardware.info/?probe=6782d71a2f) | Oct 15, 2024 |
| ASRock        | N100M                       | Desktop     | [2634b14037](https://bsd-hardware.info/?probe=2634b14037) | Oct 13, 2024 |
| Hardkernel    | ODROID-H2                   | Desktop     | [fdbcde66d7](https://bsd-hardware.info/?probe=fdbcde66d7) | Oct 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [9f95f388e0](https://bsd-hardware.info/?probe=9f95f388e0) | Oct 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [d7f091b659](https://bsd-hardware.info/?probe=d7f091b659) | Oct 06, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [174b97a5f7](https://bsd-hardware.info/?probe=174b97a5f7) | Oct 06, 2024 |
| Intel         | J1900                       | Desktop     | [5193dbe58d](https://bsd-hardware.info/?probe=5193dbe58d) | Oct 02, 2024 |
| Biostar       | B450MHP                     | Desktop     | [af6e8cf307](https://bsd-hardware.info/?probe=af6e8cf307) | Sep 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [2f6692ef1f](https://bsd-hardware.info/?probe=2f6692ef1f) | Sep 29, 2024 |
| HP            | 213D A01                    | Desktop     | [487226104e](https://bsd-hardware.info/?probe=487226104e) | Sep 28, 2024 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [063740b539](https://bsd-hardware.info/?probe=063740b539) | Sep 25, 2024 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | Desktop     | [3082b44977](https://bsd-hardware.info/?probe=3082b44977) | Sep 24, 2024 |
| NU591R        | 1.0                         | Desktop     | [d993b74208](https://bsd-hardware.info/?probe=d993b74208) | Sep 24, 2024 |
| Dell          | Vostro 5490                 | Notebook    | [32de340e28](https://bsd-hardware.info/?probe=32de340e28) | Sep 23, 2024 |
| Dell          | 03NVJ6 A01                  | Desktop     | [ebf63c5ffd](https://bsd-hardware.info/?probe=ebf63c5ffd) | Sep 22, 2024 |
| Dell          | 03NVJ6 A01                  | Desktop     | [f13225748a](https://bsd-hardware.info/?probe=f13225748a) | Sep 18, 2024 |
| Dell          | 02C2CP A02                  | Server      | [98dea9477a](https://bsd-hardware.info/?probe=98dea9477a) | Sep 18, 2024 |
| Shuttle       | FZ270                       | Desktop     | [eff73dcdb7](https://bsd-hardware.info/?probe=eff73dcdb7) | Sep 17, 2024 |
| ASUSTek       | P7P55D                      | Desktop     | [dd70c06a90](https://bsd-hardware.info/?probe=dd70c06a90) | Sep 17, 2024 |
| Dell          | 0N28XX A02                  | Server      | [0df97c4cbd](https://bsd-hardware.info/?probe=0df97c4cbd) | Sep 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [586433be33](https://bsd-hardware.info/?probe=586433be33) | Sep 11, 2024 |
| Dell          | 03NXH8 A00                  | Mini pc     | [fe6cbf7eba](https://bsd-hardware.info/?probe=fe6cbf7eba) | Sep 07, 2024 |
| ASRock        | B360M Pro4                  | Desktop     | [64d222278e](https://bsd-hardware.info/?probe=64d222278e) | Sep 06, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [2655c01614](https://bsd-hardware.info/?probe=2655c01614) | Sep 05, 2024 |
| Lenovo        | 3130 NOK                    | Mini pc     | [5669374138](https://bsd-hardware.info/?probe=5669374138) | Sep 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [e58c13f756](https://bsd-hardware.info/?probe=e58c13f756) | Sep 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [ebb28a1abb](https://bsd-hardware.info/?probe=ebb28a1abb) | Aug 24, 2024 |
| ASUSTek       | Z10PA-U8 Series             | Desktop     | [4e57035d21](https://bsd-hardware.info/?probe=4e57035d21) | Aug 24, 2024 |
| ASUSTek       | P7P55D                      | Desktop     | [4d303038e8](https://bsd-hardware.info/?probe=4d303038e8) | Aug 21, 2024 |
| Unknown       | Unknown                     | Notebook    | [7dbe7b6eaf](https://bsd-hardware.info/?probe=7dbe7b6eaf) | Aug 19, 2024 |
| ASUSTek       | P7P55D                      | Desktop     | [d457cff496](https://bsd-hardware.info/?probe=d457cff496) | Aug 19, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [bb5610fbd5](https://bsd-hardware.info/?probe=bb5610fbd5) | Aug 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [dd5c3a1a85](https://bsd-hardware.info/?probe=dd5c3a1a85) | Aug 18, 2024 |
| Lenovo        | ThinkPad X230 23255RG       | Notebook    | [b79ae8b113](https://bsd-hardware.info/?probe=b79ae8b113) | Aug 18, 2024 |
| Lenovo        | [3633AC1] STC               | Server      | [8b5278c28c](https://bsd-hardware.info/?probe=8b5278c28c) | Aug 13, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [984f299fae](https://bsd-hardware.info/?probe=984f299fae) | Aug 11, 2024 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [49322a0f1b](https://bsd-hardware.info/?probe=49322a0f1b) | Aug 10, 2024 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [4b81b4bd7f](https://bsd-hardware.info/?probe=4b81b4bd7f) | Aug 08, 2024 |
| Shuttle       | FZ270                       | Desktop     | [a509bdd918](https://bsd-hardware.info/?probe=a509bdd918) | Aug 06, 2024 |
| ASUSTek       | Z10PA-U8 Series             | Desktop     | [6c162eb9de](https://bsd-hardware.info/?probe=6c162eb9de) | Aug 04, 2024 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [ed6539c0d5](https://bsd-hardware.info/?probe=ed6539c0d5) | Aug 03, 2024 |
| Unknown       | Unknown                     | Notebook    | [207a85a15d](https://bsd-hardware.info/?probe=207a85a15d) | Aug 02, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [65838d86a4](https://bsd-hardware.info/?probe=65838d86a4) | Jul 31, 2024 |
| ASUSTek       | P8P67 LE                    | Desktop     | [38d26ac7ef](https://bsd-hardware.info/?probe=38d26ac7ef) | Jul 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [3f5facaca0](https://bsd-hardware.info/?probe=3f5facaca0) | Jul 28, 2024 |
| Dell          | XPS 13 9343                 | Notebook    | [f7837f7b55](https://bsd-hardware.info/?probe=f7837f7b55) | Jul 28, 2024 |
| Dell          | XPS 13 9343                 | Notebook    | [9053a69af6](https://bsd-hardware.info/?probe=9053a69af6) | Jul 28, 2024 |
| Apple         | MacBookPro11,4              | Notebook    | [6bade1eaf8](https://bsd-hardware.info/?probe=6bade1eaf8) | Jul 26, 2024 |
| Dell          | XPS 13 9343                 | Notebook    | [c979e064f1](https://bsd-hardware.info/?probe=c979e064f1) | Jul 25, 2024 |
| HP            | Pavilion dv7                | Notebook    | [5178909b84](https://bsd-hardware.info/?probe=5178909b84) | Jul 21, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [769af57314](https://bsd-hardware.info/?probe=769af57314) | Jul 19, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | Notebook    | [b9206448e2](https://bsd-hardware.info/?probe=b9206448e2) | Jul 17, 2024 |
| NU591R        | 1.0                         | Desktop     | [15bdc18801](https://bsd-hardware.info/?probe=15bdc18801) | Jul 16, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [7bd9eefcdb](https://bsd-hardware.info/?probe=7bd9eefcdb) | Jul 16, 2024 |
| Protectli     | V1410                       | Desktop     | [a009041b01](https://bsd-hardware.info/?probe=a009041b01) | Jul 14, 2024 |
| IGEL Techn... | M350C                       | Notebook    | [79957869db](https://bsd-hardware.info/?probe=79957869db) | Jul 12, 2024 |
| Gigabyte      | H170M-D3H                   | Desktop     | [7fc1b74405](https://bsd-hardware.info/?probe=7fc1b74405) | Jul 11, 2024 |
| HP            | ProLiant DL360p Gen8        | Server      | [e892231480](https://bsd-hardware.info/?probe=e892231480) | Jul 08, 2024 |
| Dell          | 03NXH8 A00                  | Mini pc     | [b8379ee0fe](https://bsd-hardware.info/?probe=b8379ee0fe) | Jul 05, 2024 |
| Unknown       | Unknown                     | All in one  | [fc8dd184ac](https://bsd-hardware.info/?probe=fc8dd184ac) | Jun 27, 2024 |
| Lenovo        | M30-70 20446                | Notebook    | [fd24cae390](https://bsd-hardware.info/?probe=fd24cae390) | Jun 26, 2024 |
| Lenovo        | M30-70 20446                | Notebook    | [e9a1a61239](https://bsd-hardware.info/?probe=e9a1a61239) | Jun 26, 2024 |
| Lenovo        | M30-70 20446                | Notebook    | [babc2efc9e](https://bsd-hardware.info/?probe=babc2efc9e) | Jun 26, 2024 |
| Lenovo        | M30-70 20446                | Notebook    | [0251872176](https://bsd-hardware.info/?probe=0251872176) | Jun 26, 2024 |
| MSI           | Z77A-G43                    | Desktop     | [9dbddeec9f](https://bsd-hardware.info/?probe=9dbddeec9f) | Jun 26, 2024 |
| MSI           | Z77A-G43                    | Desktop     | [794812339d](https://bsd-hardware.info/?probe=794812339d) | Jun 26, 2024 |
| Gigabyte      | X670 GAMING X AX V2         | Desktop     | [4ba8f14215](https://bsd-hardware.info/?probe=4ba8f14215) | Jun 23, 2024 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [3bae42b16c](https://bsd-hardware.info/?probe=3bae42b16c) | Jun 23, 2024 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [43d331e51c](https://bsd-hardware.info/?probe=43d331e51c) | Jun 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [0ccbb8fb68](https://bsd-hardware.info/?probe=0ccbb8fb68) | Jun 21, 2024 |
| Deciso        | NetBoard-A30 R1.0           | Server      | [80e810e04f](https://bsd-hardware.info/?probe=80e810e04f) | Jun 18, 2024 |
| ASUSTek       | Z10PA-U8 Series             | Desktop     | [ed87446558](https://bsd-hardware.info/?probe=ed87446558) | Jun 15, 2024 |
| ASUSTek       | Z10PA-U8 Series             | Desktop     | [386e93d33b](https://bsd-hardware.info/?probe=386e93d33b) | Jun 15, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [2ccb52d7b5](https://bsd-hardware.info/?probe=2ccb52d7b5) | Jun 11, 2024 |
| CheckPoint    | QS-22-00                    | Desktop     | [2b53b8d5eb](https://bsd-hardware.info/?probe=2b53b8d5eb) | Jun 11, 2024 |
| CheckPoint    | QS-22-00                    | Desktop     | [b077c2faa1](https://bsd-hardware.info/?probe=b077c2faa1) | Jun 11, 2024 |
| Apple         | MacBookPro11,4              | Notebook    | [3988badee2](https://bsd-hardware.info/?probe=3988badee2) | Jun 11, 2024 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [5b53bd70e9](https://bsd-hardware.info/?probe=5b53bd70e9) | Jun 08, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | Notebook    | [e2a13da073](https://bsd-hardware.info/?probe=e2a13da073) | Jun 06, 2024 |
| CheckPoint    | QS-22-00                    | Desktop     | [8b2b2b405b](https://bsd-hardware.info/?probe=8b2b2b405b) | Jun 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [60afe7652a](https://bsd-hardware.info/?probe=60afe7652a) | Jun 04, 2024 |
| ASRock        | X99 Extreme4                | Desktop     | [af182c3b9b](https://bsd-hardware.info/?probe=af182c3b9b) | Jun 04, 2024 |
| Sony          | SVF1521G6EW                 | Notebook    | [b977d6f1e0](https://bsd-hardware.info/?probe=b977d6f1e0) | Jun 02, 2024 |
| PC Engines    | apu6                        | Desktop     | [1ddfd14973](https://bsd-hardware.info/?probe=1ddfd14973) | Jun 02, 2024 |
| HP            | 18E5                        | Desktop     | [c599ffe53f](https://bsd-hardware.info/?probe=c599ffe53f) | May 31, 2024 |
| Giada         | Apollolake JHS61L           | Desktop     | [d7c4508cf5](https://bsd-hardware.info/?probe=d7c4508cf5) | May 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [aae0ad6a9a](https://bsd-hardware.info/?probe=aae0ad6a9a) | May 28, 2024 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [4edc2b9cba](https://bsd-hardware.info/?probe=4edc2b9cba) | May 26, 2024 |
| HP            | 213D A01                    | Desktop     | [f2751f087b](https://bsd-hardware.info/?probe=f2751f087b) | May 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [5bf9269ec0](https://bsd-hardware.info/?probe=5bf9269ec0) | May 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [729aeb790d](https://bsd-hardware.info/?probe=729aeb790d) | May 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [b158edf2bd](https://bsd-hardware.info/?probe=b158edf2bd) | May 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [1f563c3df1](https://bsd-hardware.info/?probe=1f563c3df1) | May 19, 2024 |
| HP            | 213D A01                    | Desktop     | [56245654e5](https://bsd-hardware.info/?probe=56245654e5) | May 18, 2024 |
| Dell          | 0MJ137 A00                  | Server      | [99c6c09547](https://bsd-hardware.info/?probe=99c6c09547) | May 16, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [0f9e113064](https://bsd-hardware.info/?probe=0f9e113064) | May 14, 2024 |
| Dell          | 03NXH8 A00                  | Mini pc     | [45fc618aff](https://bsd-hardware.info/?probe=45fc618aff) | May 06, 2024 |
| Dell          | 03NXH8 A00                  | Mini pc     | [aa51033b7c](https://bsd-hardware.info/?probe=aa51033b7c) | May 03, 2024 |
| Unknown       | Unknown                     | Desktop     | [e54a161178](https://bsd-hardware.info/?probe=e54a161178) | Apr 28, 2024 |
| Unknown       | Unknown                     | Notebook    | [6016137c6c](https://bsd-hardware.info/?probe=6016137c6c) | Apr 24, 2024 |
| HP            | 8054                        | Desktop     | [7a76b345c0](https://bsd-hardware.info/?probe=7a76b345c0) | Apr 23, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [7ae4c9320c](https://bsd-hardware.info/?probe=7ae4c9320c) | Apr 23, 2024 |
| HP            | 8054                        | Desktop     | [040f48e020](https://bsd-hardware.info/?probe=040f48e020) | Apr 23, 2024 |
| HP            | 3396                        | Desktop     | [f154c34157](https://bsd-hardware.info/?probe=f154c34157) | Apr 19, 2024 |
| ASRock        | X99 Extreme4                | Desktop     | [8d5a19e786](https://bsd-hardware.info/?probe=8d5a19e786) | Apr 13, 2024 |
| ASRock        | X99 Extreme4                | Desktop     | [f2fdbc8d66](https://bsd-hardware.info/?probe=f2fdbc8d66) | Apr 13, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [66aaf90799](https://bsd-hardware.info/?probe=66aaf90799) | Apr 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [55fcf12f06](https://bsd-hardware.info/?probe=55fcf12f06) | Apr 12, 2024 |
| Supermicro    | X10SLL-SF                   | Server      | [f9ae26fa3f](https://bsd-hardware.info/?probe=f9ae26fa3f) | Apr 11, 2024 |
| Gigabyte      | H97M-D3H                    | Desktop     | [8c0a605e99](https://bsd-hardware.info/?probe=8c0a605e99) | Apr 10, 2024 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [040c686c32](https://bsd-hardware.info/?probe=040c686c32) | Apr 07, 2024 |
| Intel         | D2500CC AAG81477-400        | Desktop     | [883217db7f](https://bsd-hardware.info/?probe=883217db7f) | Apr 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [b0994abd3c](https://bsd-hardware.info/?probe=b0994abd3c) | Apr 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [c805058269](https://bsd-hardware.info/?probe=c805058269) | Apr 03, 2024 |
| ASRock        | A520M-ITX/ac                | Desktop     | [1239807f69](https://bsd-hardware.info/?probe=1239807f69) | Mar 30, 2024 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [be101e8917](https://bsd-hardware.info/?probe=be101e8917) | Mar 29, 2024 |
| MSI           | MS-98G4                     | Desktop     | [22901a90e7](https://bsd-hardware.info/?probe=22901a90e7) | Mar 25, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [62988feb32](https://bsd-hardware.info/?probe=62988feb32) | Mar 22, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [c00f4d37cc](https://bsd-hardware.info/?probe=c00f4d37cc) | Mar 22, 2024 |
| ASUSTek       | X550CA                      | Notebook    | [ff92192d22](https://bsd-hardware.info/?probe=ff92192d22) | Mar 19, 2024 |
| Supermicro    | X9SBAA                      | Server      | [04a61d8ef7](https://bsd-hardware.info/?probe=04a61d8ef7) | Mar 16, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [1a072e681a](https://bsd-hardware.info/?probe=1a072e681a) | Mar 15, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [6741cefeb7](https://bsd-hardware.info/?probe=6741cefeb7) | Mar 12, 2024 |
| Dell          | 03NXH8 A00                  | Mini pc     | [c6fab428e2](https://bsd-hardware.info/?probe=c6fab428e2) | Mar 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [a88d3b4a91](https://bsd-hardware.info/?probe=a88d3b4a91) | Mar 09, 2024 |
| Unknown       | QDNV01                      | Desktop     | [2092ae4116](https://bsd-hardware.info/?probe=2092ae4116) | Mar 09, 2024 |
| Unknown       | QDNV01                      | Desktop     | [1d7ee8bcc2](https://bsd-hardware.info/?probe=1d7ee8bcc2) | Mar 09, 2024 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [ba0295b8ea](https://bsd-hardware.info/?probe=ba0295b8ea) | Mar 05, 2024 |
| Lenovo        | ThinkPad X230 23254S6       | Notebook    | [cae99ac427](https://bsd-hardware.info/?probe=cae99ac427) | Mar 03, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [c050de5841](https://bsd-hardware.info/?probe=c050de5841) | Mar 01, 2024 |
| Intel         | NUC42R                      | Mini pc     | [704813ac54](https://bsd-hardware.info/?probe=704813ac54) | Feb 28, 2024 |
| HP            | 213D A01                    | Desktop     | [c5bdc2713e](https://bsd-hardware.info/?probe=c5bdc2713e) | Feb 27, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [1f76f6d5f9](https://bsd-hardware.info/?probe=1f76f6d5f9) | Feb 25, 2024 |
| Dell          | 0G261D A00                  | Desktop     | [34a8d8ab2f](https://bsd-hardware.info/?probe=34a8d8ab2f) | Feb 25, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [14536814b0](https://bsd-hardware.info/?probe=14536814b0) | Feb 25, 2024 |
| Biostar       | J4125NHU                    | Desktop     | [1527f68f80](https://bsd-hardware.info/?probe=1527f68f80) | Feb 19, 2024 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [02ee8062bc](https://bsd-hardware.info/?probe=02ee8062bc) | Feb 18, 2024 |
| HP            | 8103 A01                    | Mini pc     | [92bebda2d7](https://bsd-hardware.info/?probe=92bebda2d7) | Feb 12, 2024 |
| HP            | 17E2                        | Desktop     | [946d33d274](https://bsd-hardware.info/?probe=946d33d274) | Feb 09, 2024 |
| Dell          | 03NXH8 A00                  | Mini pc     | [7d16a53b54](https://bsd-hardware.info/?probe=7d16a53b54) | Feb 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [0bf7e7f085](https://bsd-hardware.info/?probe=0bf7e7f085) | Feb 03, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [f6f19ac329](https://bsd-hardware.info/?probe=f6f19ac329) | Feb 02, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [043918562c](https://bsd-hardware.info/?probe=043918562c) | Jan 30, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [8b93ca6177](https://bsd-hardware.info/?probe=8b93ca6177) | Jan 29, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [5d0e727014](https://bsd-hardware.info/?probe=5d0e727014) | Jan 29, 2024 |
| HP            | 17E2                        | Desktop     | [f5d50d721e](https://bsd-hardware.info/?probe=f5d50d721e) | Jan 28, 2024 |
| ASRock        | H310M-ITX/ac                | Desktop     | [55ac417044](https://bsd-hardware.info/?probe=55ac417044) | Jan 28, 2024 |
| HP            | 17E2                        | Desktop     | [970b437e61](https://bsd-hardware.info/?probe=970b437e61) | Jan 21, 2024 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [01499997cb](https://bsd-hardware.info/?probe=01499997cb) | Jan 21, 2024 |
| HP            | 213D A01                    | Desktop     | [23ae22cd46](https://bsd-hardware.info/?probe=23ae22cd46) | Jan 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [6afcd4a25f](https://bsd-hardware.info/?probe=6afcd4a25f) | Jan 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [36e0f351c2](https://bsd-hardware.info/?probe=36e0f351c2) | Jan 18, 2024 |
| Dell          | 03NXH8 A00                  | Mini pc     | [8634625b34](https://bsd-hardware.info/?probe=8634625b34) | Jan 16, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [53acaf27b3](https://bsd-hardware.info/?probe=53acaf27b3) | Jan 16, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [d318950ac5](https://bsd-hardware.info/?probe=d318950ac5) | Jan 15, 2024 |
| Dell          | 0MGK50 A02                  | Desktop     | [311083cbe9](https://bsd-hardware.info/?probe=311083cbe9) | Jan 11, 2024 |
| Dell          | 0MGK50 A02                  | Desktop     | [7c2faad499](https://bsd-hardware.info/?probe=7c2faad499) | Jan 11, 2024 |
| HP            | 18E5                        | Desktop     | [cdea726a3a](https://bsd-hardware.info/?probe=cdea726a3a) | Jan 03, 2024 |
| Intel         | H61M-DS2                    | Desktop     | [bd541b60c8](https://bsd-hardware.info/?probe=bd541b60c8) | Dec 30, 2023 |
| Lenovo        | ThinkPad X220 4291H77       | Notebook    | [2fe3ff7e06](https://bsd-hardware.info/?probe=2fe3ff7e06) | Dec 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [c99ee25103](https://bsd-hardware.info/?probe=c99ee25103) | Dec 17, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b600237a69](https://bsd-hardware.info/?probe=b600237a69) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [92ae7371ee](https://bsd-hardware.info/?probe=92ae7371ee) | Dec 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [6097033e25](https://bsd-hardware.info/?probe=6097033e25) | Dec 05, 2023 |
| Yanling       | YL-EL4L-0A Ver              | Desktop     | [d0c780fa8b](https://bsd-hardware.info/?probe=d0c780fa8b) | Nov 27, 2023 |
| NU591R        | 1.0                         | Desktop     | [2552269778](https://bsd-hardware.info/?probe=2552269778) | Nov 27, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [f2aa7b3ebf](https://bsd-hardware.info/?probe=f2aa7b3ebf) | Nov 25, 2023 |
| Lenovo        | 0x30F617AA SDK0J40705 WI... | Desktop     | [3385be6d7c](https://bsd-hardware.info/?probe=3385be6d7c) | Nov 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [74aaffb0d7](https://bsd-hardware.info/?probe=74aaffb0d7) | Nov 21, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [9eab94b4f7](https://bsd-hardware.info/?probe=9eab94b4f7) | Nov 18, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [00de0389fb](https://bsd-hardware.info/?probe=00de0389fb) | Nov 18, 2023 |
| HP            | 17E2                        | Mini pc     | [2e93df6830](https://bsd-hardware.info/?probe=2e93df6830) | Nov 17, 2023 |
| Unknown       | Raspberry Pi                | Soc         | [de988c2e66](https://bsd-hardware.info/?probe=de988c2e66) | Nov 14, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [2487233a5d](https://bsd-hardware.info/?probe=2487233a5d) | Nov 13, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [05bf5fb9f4](https://bsd-hardware.info/?probe=05bf5fb9f4) | Nov 07, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [1d80294e3e](https://bsd-hardware.info/?probe=1d80294e3e) | Nov 06, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [a217880b63](https://bsd-hardware.info/?probe=a217880b63) | Nov 05, 2023 |
| HP            | 213D A01                    | Desktop     | [e7de264f61](https://bsd-hardware.info/?probe=e7de264f61) | Nov 05, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [f6a8d5dbad](https://bsd-hardware.info/?probe=f6a8d5dbad) | Nov 03, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [8473035148](https://bsd-hardware.info/?probe=8473035148) | Nov 03, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [e977a38199](https://bsd-hardware.info/?probe=e977a38199) | Nov 02, 2023 |
| Intel         | JSL MRD                     | Desktop     | [328c764941](https://bsd-hardware.info/?probe=328c764941) | Oct 27, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [1157df98bf](https://bsd-hardware.info/?probe=1157df98bf) | Oct 27, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [1b42e4a912](https://bsd-hardware.info/?probe=1b42e4a912) | Oct 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [8e245ccb85](https://bsd-hardware.info/?probe=8e245ccb85) | Oct 25, 2023 |
| Shuttle       | FZ270                       | Desktop     | [1aa4ad0971](https://bsd-hardware.info/?probe=1aa4ad0971) | Oct 23, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [ab44e043d2](https://bsd-hardware.info/?probe=ab44e043d2) | Oct 23, 2023 |
| HP            | 8103 A01                    | Mini pc     | [d621f08c5a](https://bsd-hardware.info/?probe=d621f08c5a) | Oct 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [5a7e4222f1](https://bsd-hardware.info/?probe=5a7e4222f1) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [cc1a558efe](https://bsd-hardware.info/?probe=cc1a558efe) | Oct 21, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [a8727c3ee3](https://bsd-hardware.info/?probe=a8727c3ee3) | Oct 19, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b2a20ba176](https://bsd-hardware.info/?probe=b2a20ba176) | Oct 10, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [b192196423](https://bsd-hardware.info/?probe=b192196423) | Oct 08, 2023 |
| Gigabyte      | P35-DS3R                    | Desktop     | [6f742cd646](https://bsd-hardware.info/?probe=6f742cd646) | Oct 05, 2023 |
| MSI           | MS-98G4                     | Desktop     | [fa88c3c925](https://bsd-hardware.info/?probe=fa88c3c925) | Oct 04, 2023 |
| IGEL Techn... | VX900                       | Desktop     | [eb65624dc3](https://bsd-hardware.info/?probe=eb65624dc3) | Sep 29, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [c560c88351](https://bsd-hardware.info/?probe=c560c88351) | Sep 29, 2023 |
| Dell          | 03NXH8 A00                  | Mini pc     | [cc346350f3](https://bsd-hardware.info/?probe=cc346350f3) | Sep 29, 2023 |
| MSI           | MS-98G4                     | Desktop     | [a8ea23c0df](https://bsd-hardware.info/?probe=a8ea23c0df) | Sep 28, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b698f41785](https://bsd-hardware.info/?probe=b698f41785) | Sep 28, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [a0d9fae143](https://bsd-hardware.info/?probe=a0d9fae143) | Sep 27, 2023 |
| HP            | 3396                        | Desktop     | [a60feb9960](https://bsd-hardware.info/?probe=a60feb9960) | Sep 25, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [621470728b](https://bsd-hardware.info/?probe=621470728b) | Sep 19, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [49593de0a0](https://bsd-hardware.info/?probe=49593de0a0) | Sep 16, 2023 |
| Dell          | XPS 9320                    | Notebook    | [d80b3d5a54](https://bsd-hardware.info/?probe=d80b3d5a54) | Sep 14, 2023 |
| Dell          | 0D24M8 A03                  | Desktop     | [48441955a6](https://bsd-hardware.info/?probe=48441955a6) | Sep 14, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [cda96eed7a](https://bsd-hardware.info/?probe=cda96eed7a) | Aug 28, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [85b0bba1ea](https://bsd-hardware.info/?probe=85b0bba1ea) | Aug 27, 2023 |
| Gigabyte      | H510M K                     | Desktop     | [17f15f19f4](https://bsd-hardware.info/?probe=17f15f19f4) | Aug 26, 2023 |
| Lenovo        | ThinkPad X200 7458WNZ       | Notebook    | [3ac1d60240](https://bsd-hardware.info/?probe=3ac1d60240) | Aug 12, 2023 |
| HP            | 18E5                        | Desktop     | [61bde93177](https://bsd-hardware.info/?probe=61bde93177) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [7751768206](https://bsd-hardware.info/?probe=7751768206) | Aug 10, 2023 |
| AMI           | PB_1900A                    | Desktop     | [791f6e0cb4](https://bsd-hardware.info/?probe=791f6e0cb4) | Aug 07, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [6496fe0cfe](https://bsd-hardware.info/?probe=6496fe0cfe) | Aug 03, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [09f173d4b6](https://bsd-hardware.info/?probe=09f173d4b6) | Jul 30, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [9c0c41b663](https://bsd-hardware.info/?probe=9c0c41b663) | Jul 30, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [e11855c762](https://bsd-hardware.info/?probe=e11855c762) | Jul 24, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [3a774e653a](https://bsd-hardware.info/?probe=3a774e653a) | Jul 19, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [386a80104d](https://bsd-hardware.info/?probe=386a80104d) | Jul 19, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [604ac1ea85](https://bsd-hardware.info/?probe=604ac1ea85) | Jul 19, 2023 |
| Supermicro    | A2SDV-4C-LN10PF             | Desktop     | [8be657ad15](https://bsd-hardware.info/?probe=8be657ad15) | Jul 17, 2023 |
| HP            | 213D A01                    | Desktop     | [ae7b01c282](https://bsd-hardware.info/?probe=ae7b01c282) | Jul 16, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [1de68296ba](https://bsd-hardware.info/?probe=1de68296ba) | Jul 15, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [5f5c78ed40](https://bsd-hardware.info/?probe=5f5c78ed40) | Jul 15, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [c55c8784e1](https://bsd-hardware.info/?probe=c55c8784e1) | Jul 13, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [df74f4520e](https://bsd-hardware.info/?probe=df74f4520e) | Jul 08, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [16fc35ccac](https://bsd-hardware.info/?probe=16fc35ccac) | Jul 06, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [e569621be2](https://bsd-hardware.info/?probe=e569621be2) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [553cd9ecae](https://bsd-hardware.info/?probe=553cd9ecae) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | Desktop     | [3c80c960d3](https://bsd-hardware.info/?probe=3c80c960d3) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | Desktop     | [051ddf6f8d](https://bsd-hardware.info/?probe=051ddf6f8d) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [dfdb0bd650](https://bsd-hardware.info/?probe=dfdb0bd650) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [e68bb73773](https://bsd-hardware.info/?probe=e68bb73773) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [3b4a248520](https://bsd-hardware.info/?probe=3b4a248520) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [0a2a221aae](https://bsd-hardware.info/?probe=0a2a221aae) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [7e5ee8de12](https://bsd-hardware.info/?probe=7e5ee8de12) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [3b50a90ebc](https://bsd-hardware.info/?probe=3b50a90ebc) | Jul 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [13c087ef5e](https://bsd-hardware.info/?probe=13c087ef5e) | Jul 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [1aff07438c](https://bsd-hardware.info/?probe=1aff07438c) | Jun 28, 2023 |
| Dell          | Latitude E4310              | Notebook    | [9cdd4909fe](https://bsd-hardware.info/?probe=9cdd4909fe) | Jun 24, 2023 |
| HP            | 213D A01                    | Desktop     | [eccc48bb80](https://bsd-hardware.info/?probe=eccc48bb80) | Jun 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b4f214b72](https://bsd-hardware.info/?probe=6b4f214b72) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [615e7cbf52](https://bsd-hardware.info/?probe=615e7cbf52) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [8357f0f72e](https://bsd-hardware.info/?probe=8357f0f72e) | Jun 15, 2023 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [15329a007b](https://bsd-hardware.info/?probe=15329a007b) | Jun 14, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [b007264caa](https://bsd-hardware.info/?probe=b007264caa) | Jun 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [3679eb8cd4](https://bsd-hardware.info/?probe=3679eb8cd4) | Jun 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [9afa1aea18](https://bsd-hardware.info/?probe=9afa1aea18) | Jun 10, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [f79924e37b](https://bsd-hardware.info/?probe=f79924e37b) | Jun 08, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP4C    | Notebook    | [b891388109](https://bsd-hardware.info/?probe=b891388109) | Jun 07, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [95ceb1335c](https://bsd-hardware.info/?probe=95ceb1335c) | Jun 04, 2023 |
| Dell          | 0TKM9Y A00                  | Mini pc     | [fdd78a8f45](https://bsd-hardware.info/?probe=fdd78a8f45) | Jun 03, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [98ebd3efdb](https://bsd-hardware.info/?probe=98ebd3efdb) | Jun 02, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [48a63a2328](https://bsd-hardware.info/?probe=48a63a2328) | Jun 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [e057606b14](https://bsd-hardware.info/?probe=e057606b14) | May 29, 2023 |
| NU591R        | 1.0                         | Desktop     | [e4bdd753d1](https://bsd-hardware.info/?probe=e4bdd753d1) | May 28, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [b121b2cba9](https://bsd-hardware.info/?probe=b121b2cba9) | May 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [1070ff80a8](https://bsd-hardware.info/?probe=1070ff80a8) | May 26, 2023 |
| Intel         | S1200RP                     | Server      | [f3143ec0e1](https://bsd-hardware.info/?probe=f3143ec0e1) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [3b4be5b07a](https://bsd-hardware.info/?probe=3b4be5b07a) | May 24, 2023 |
| Intel         | S1200RP                     | Server      | [59ee73a435](https://bsd-hardware.info/?probe=59ee73a435) | May 23, 2023 |
| Google        | Sentry                      | Notebook    | [107124dd66](https://bsd-hardware.info/?probe=107124dd66) | May 22, 2023 |
| PC Engines    | apu6                        | Desktop     | [cfebc05e50](https://bsd-hardware.info/?probe=cfebc05e50) | May 21, 2023 |
| PC Engines    | apu6                        | Desktop     | [320d6a85a3](https://bsd-hardware.info/?probe=320d6a85a3) | May 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [2a2b4272f9](https://bsd-hardware.info/?probe=2a2b4272f9) | May 20, 2023 |
| HP            | 213D A01                    | Desktop     | [8e1d1d5670](https://bsd-hardware.info/?probe=8e1d1d5670) | May 20, 2023 |
| Packard Be... | EasyNote LJ65               | Notebook    | [36d3e7aaf7](https://bsd-hardware.info/?probe=36d3e7aaf7) | May 19, 2023 |
| PC Engines    | apu4                        | Desktop     | [1d4c0fad6a](https://bsd-hardware.info/?probe=1d4c0fad6a) | May 16, 2023 |
| PC Engines    | apu4                        | Desktop     | [94bdc05090](https://bsd-hardware.info/?probe=94bdc05090) | May 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [526906c806](https://bsd-hardware.info/?probe=526906c806) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [8aede62ca8](https://bsd-hardware.info/?probe=8aede62ca8) | May 14, 2023 |
| Supermicro    | X8SIL                       | Desktop     | [bb30062fc1](https://bsd-hardware.info/?probe=bb30062fc1) | May 14, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [dd2b0657d0](https://bsd-hardware.info/?probe=dd2b0657d0) | May 13, 2023 |
| Dell          | 05XGC8 A00                  | Desktop     | [131214e3a7](https://bsd-hardware.info/?probe=131214e3a7) | May 12, 2023 |
| HP            | 213D A01                    | Desktop     | [92c8d4c54e](https://bsd-hardware.info/?probe=92c8d4c54e) | May 12, 2023 |
| Lenovo        | ThinkPad T500 205663G       | Notebook    | [d706da9400](https://bsd-hardware.info/?probe=d706da9400) | May 06, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [6e34c8b22a](https://bsd-hardware.info/?probe=6e34c8b22a) | May 05, 2023 |
| Gigabyte      | H510M K                     | Desktop     | [e4a5065086](https://bsd-hardware.info/?probe=e4a5065086) | May 03, 2023 |
| HP            | 213D A01                    | Desktop     | [6810604547](https://bsd-hardware.info/?probe=6810604547) | May 03, 2023 |
| HP            | ProLiant DL320e Gen8        | Server      | [03255b960a](https://bsd-hardware.info/?probe=03255b960a) | Apr 30, 2023 |
| HP            | ProLiant DL320e Gen8        | Server      | [b1c41e5e29](https://bsd-hardware.info/?probe=b1c41e5e29) | Apr 29, 2023 |
| Gigabyte      | H510M K                     | Desktop     | [a952664d92](https://bsd-hardware.info/?probe=a952664d92) | Apr 29, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [ce8453fcce](https://bsd-hardware.info/?probe=ce8453fcce) | Apr 27, 2023 |
| HP            | 18E5                        | Desktop     | [9f82560327](https://bsd-hardware.info/?probe=9f82560327) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [838979f891](https://bsd-hardware.info/?probe=838979f891) | Apr 20, 2023 |
| Medion        | E15302                      | Notebook    | [f47f32e1cc](https://bsd-hardware.info/?probe=f47f32e1cc) | Apr 17, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [a7830f5244](https://bsd-hardware.info/?probe=a7830f5244) | Apr 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [fb756bb34e](https://bsd-hardware.info/?probe=fb756bb34e) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [add8280600](https://bsd-hardware.info/?probe=add8280600) | Apr 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [e1e041b34a](https://bsd-hardware.info/?probe=e1e041b34a) | Apr 07, 2023 |
| Fujitsu       | CELSIUS H920                | Notebook    | [0551eecbcc](https://bsd-hardware.info/?probe=0551eecbcc) | Apr 06, 2023 |
| Dell          | 012KND A00                  | Mini pc     | [55d92330be](https://bsd-hardware.info/?probe=55d92330be) | Apr 04, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [ac38e117ac](https://bsd-hardware.info/?probe=ac38e117ac) | Apr 04, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [032a4be314](https://bsd-hardware.info/?probe=032a4be314) | Apr 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [f4d583f326](https://bsd-hardware.info/?probe=f4d583f326) | Apr 01, 2023 |
| Fujitsu       | CELSIUS H920                | Notebook    | [e6300dc691](https://bsd-hardware.info/?probe=e6300dc691) | Mar 31, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [837fdf1a2c](https://bsd-hardware.info/?probe=837fdf1a2c) | Mar 31, 2023 |
| Lenovo        | ThinkPad T540p 20BFS10W0... | Notebook    | [30c5fc2625](https://bsd-hardware.info/?probe=30c5fc2625) | Mar 29, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [2f5592023f](https://bsd-hardware.info/?probe=2f5592023f) | Mar 29, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [6316b108be](https://bsd-hardware.info/?probe=6316b108be) | Mar 29, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [a8f794f3fb](https://bsd-hardware.info/?probe=a8f794f3fb) | Mar 24, 2023 |
| HP            | 18E5                        | Desktop     | [1f402a50e7](https://bsd-hardware.info/?probe=1f402a50e7) | Mar 22, 2023 |
| ASUSTek       | X71Vn                       | Notebook    | [6e96ea55ee](https://bsd-hardware.info/?probe=6e96ea55ee) | Mar 22, 2023 |
| Intel         | X99                         | Desktop     | [a74c2b96ff](https://bsd-hardware.info/?probe=a74c2b96ff) | Mar 21, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [8d0e6be5da](https://bsd-hardware.info/?probe=8d0e6be5da) | Mar 20, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [acc1970543](https://bsd-hardware.info/?probe=acc1970543) | Mar 18, 2023 |
| Lenovo        | ThinkPad A275 20KCS07010    | Notebook    | [4d6daf66c1](https://bsd-hardware.info/?probe=4d6daf66c1) | Mar 18, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [653dbe54a4](https://bsd-hardware.info/?probe=653dbe54a4) | Mar 18, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b8404f57ba](https://bsd-hardware.info/?probe=b8404f57ba) | Mar 15, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2d5e8056c0](https://bsd-hardware.info/?probe=2d5e8056c0) | Mar 15, 2023 |
| Dell          | Latitude D630               | Notebook    | [da1fa73418](https://bsd-hardware.info/?probe=da1fa73418) | Mar 14, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | Notebook    | [882cc7fc62](https://bsd-hardware.info/?probe=882cc7fc62) | Mar 13, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [593f6ff02d](https://bsd-hardware.info/?probe=593f6ff02d) | Mar 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [e8204efca6](https://bsd-hardware.info/?probe=e8204efca6) | Mar 12, 2023 |
| Dell          | Latitude E5450              | Notebook    | [4bb2040221](https://bsd-hardware.info/?probe=4bb2040221) | Mar 11, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [29ad0e1044](https://bsd-hardware.info/?probe=29ad0e1044) | Mar 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [12990e3b0f](https://bsd-hardware.info/?probe=12990e3b0f) | Mar 09, 2023 |
| HP            | 8103 A01                    | Mini pc     | [acb993fd8a](https://bsd-hardware.info/?probe=acb993fd8a) | Mar 06, 2023 |
| AMI           | PB_1900A                    | Desktop     | [79504fcf66](https://bsd-hardware.info/?probe=79504fcf66) | Mar 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [78d56cd69d](https://bsd-hardware.info/?probe=78d56cd69d) | Mar 01, 2023 |
| Intel         | S1200RP                     | Server      | [176c42716f](https://bsd-hardware.info/?probe=176c42716f) | Mar 01, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [1758c6207c](https://bsd-hardware.info/?probe=1758c6207c) | Feb 27, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | Notebook    | [97d9b10c8a](https://bsd-hardware.info/?probe=97d9b10c8a) | Feb 24, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [e55635df08](https://bsd-hardware.info/?probe=e55635df08) | Feb 23, 2023 |
| PC Engines    | apu1                        | Desktop     | [41fe7362c4](https://bsd-hardware.info/?probe=41fe7362c4) | Feb 22, 2023 |
| Unknown       | V0.9x                       | Desktop     | [21243cad5f](https://bsd-hardware.info/?probe=21243cad5f) | Feb 21, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [9aec93f312](https://bsd-hardware.info/?probe=9aec93f312) | Feb 19, 2023 |
| MSI           | Z97 GUARD-PRO               | Desktop     | [43d56964b9](https://bsd-hardware.info/?probe=43d56964b9) | Feb 12, 2023 |
| Supermicro    | X8STi                       | Desktop     | [4faeca02d3](https://bsd-hardware.info/?probe=4faeca02d3) | Feb 11, 2023 |
| MSI           | Z97 GUARD-PRO               | Desktop     | [9f066752d5](https://bsd-hardware.info/?probe=9f066752d5) | Feb 11, 2023 |
| HP            | 3396                        | Desktop     | [6a20d52898](https://bsd-hardware.info/?probe=6a20d52898) | Feb 08, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [bbe7b327fd](https://bsd-hardware.info/?probe=bbe7b327fd) | Feb 06, 2023 |
| HP            | Notebook                    | Notebook    | [8d8e5c294a](https://bsd-hardware.info/?probe=8d8e5c294a) | Feb 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [cb25ee692c](https://bsd-hardware.info/?probe=cb25ee692c) | Feb 05, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [ea5b1c178b](https://bsd-hardware.info/?probe=ea5b1c178b) | Feb 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [e76cc93e5d](https://bsd-hardware.info/?probe=e76cc93e5d) | Jan 31, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [bccdd2f331](https://bsd-hardware.info/?probe=bccdd2f331) | Jan 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [540696f4e5](https://bsd-hardware.info/?probe=540696f4e5) | Jan 29, 2023 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [3492d9a849](https://bsd-hardware.info/?probe=3492d9a849) | Jan 27, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [92c676e033](https://bsd-hardware.info/?probe=92c676e033) | Jan 26, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7bd5f0c2e9](https://bsd-hardware.info/?probe=7bd5f0c2e9) | Jan 22, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [6b331ff558](https://bsd-hardware.info/?probe=6b331ff558) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [6aa648ba82](https://bsd-hardware.info/?probe=6aa648ba82) | Jan 19, 2023 |
| Intel         | H81U                        | Notebook    | [08d2539153](https://bsd-hardware.info/?probe=08d2539153) | Jan 18, 2023 |
| Intel         | H81U                        | Notebook    | [fe47328dd0](https://bsd-hardware.info/?probe=fe47328dd0) | Jan 17, 2023 |
| HP            | 1495                        | Desktop     | [4e16deda5a](https://bsd-hardware.info/?probe=4e16deda5a) | Jan 11, 2023 |
| Gigabyte      | H510M K                     | Desktop     | [c30a71f5ae](https://bsd-hardware.info/?probe=c30a71f5ae) | Jan 10, 2023 |
| Dell          | Latitude E6430              | Notebook    | [45f592a66f](https://bsd-hardware.info/?probe=45f592a66f) | Jan 06, 2023 |
| Dell          | Latitude E6430              | Notebook    | [1c4bec17bb](https://bsd-hardware.info/?probe=1c4bec17bb) | Jan 06, 2023 |
| Biostar       | J4125NHU                    | Desktop     | [41114c45b7](https://bsd-hardware.info/?probe=41114c45b7) | Jan 05, 2023 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [4bcc34fdca](https://bsd-hardware.info/?probe=4bcc34fdca) | Dec 27, 2022 |
| Intel         | D2500HN AAG81480-500        | Desktop     | [dae5627541](https://bsd-hardware.info/?probe=dae5627541) | Dec 27, 2022 |
| Dell          | 060J9C A00                  | Mini pc     | [29b3e0b639](https://bsd-hardware.info/?probe=29b3e0b639) | Dec 22, 2022 |
| Acer          | WG43M                       | Desktop     | [d316352c20](https://bsd-hardware.info/?probe=d316352c20) | Dec 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [0e98358cf3](https://bsd-hardware.info/?probe=0e98358cf3) | Dec 17, 2022 |
| Google        | Lars                        | Notebook    | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [b23f59a068](https://bsd-hardware.info/?probe=b23f59a068) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [c93690c7ca](https://bsd-hardware.info/?probe=c93690c7ca) | Nov 27, 2022 |
| Shuttle       | FZ270                       | Desktop     | [04a7f49322](https://bsd-hardware.info/?probe=04a7f49322) | Nov 27, 2022 |
| Shuttle       | FZ270                       | Desktop     | [10016f39b9](https://bsd-hardware.info/?probe=10016f39b9) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [675c9fdf94](https://bsd-hardware.info/?probe=675c9fdf94) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [a337eb9e5f](https://bsd-hardware.info/?probe=a337eb9e5f) | Nov 27, 2022 |
| Shuttle       | FH270                       | Desktop     | [192351ac6f](https://bsd-hardware.info/?probe=192351ac6f) | Nov 27, 2022 |
| Shuttle       | FH270                       | Desktop     | [3b68d89092](https://bsd-hardware.info/?probe=3b68d89092) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [5048d00fd8](https://bsd-hardware.info/?probe=5048d00fd8) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [60bdb57227](https://bsd-hardware.info/?probe=60bdb57227) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [ebdca950cc](https://bsd-hardware.info/?probe=ebdca950cc) | Nov 27, 2022 |
| HP            | 3396                        | Desktop     | [dc94cbde1a](https://bsd-hardware.info/?probe=dc94cbde1a) | Nov 23, 2022 |
| Gigabyte      | H110TN                      | Desktop     | [c121bad3fb](https://bsd-hardware.info/?probe=c121bad3fb) | Nov 17, 2022 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [f27ff1a7c3](https://bsd-hardware.info/?probe=f27ff1a7c3) | Oct 22, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [348bef7dba](https://bsd-hardware.info/?probe=348bef7dba) | Oct 20, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [f84b205626](https://bsd-hardware.info/?probe=f84b205626) | Oct 18, 2022 |
| HP            | SpectreXT Pro 13-b000 PC    | Notebook    | [f45ea42873](https://bsd-hardware.info/?probe=f45ea42873) | Oct 16, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [e08c408ced](https://bsd-hardware.info/?probe=e08c408ced) | Oct 14, 2022 |
| ASRockRack    | EP2C612D16FM                | Desktop     | [30a582fccb](https://bsd-hardware.info/?probe=30a582fccb) | Oct 07, 2022 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [f521533d51](https://bsd-hardware.info/?probe=f521533d51) | Oct 06, 2022 |
| Gigabyte      | H510M K                     | Desktop     | [27f932ee37](https://bsd-hardware.info/?probe=27f932ee37) | Oct 02, 2022 |
| Gigabyte      | H510M K                     | Desktop     | [4beab225f6](https://bsd-hardware.info/?probe=4beab225f6) | Sep 28, 2022 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [fe44242c3b](https://bsd-hardware.info/?probe=fe44242c3b) | Sep 25, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [fe9eecb935](https://bsd-hardware.info/?probe=fe9eecb935) | Sep 18, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [da4bd87fee](https://bsd-hardware.info/?probe=da4bd87fee) | Sep 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7aa564bfb2](https://bsd-hardware.info/?probe=7aa564bfb2) | Sep 14, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [0ee299e989](https://bsd-hardware.info/?probe=0ee299e989) | Sep 14, 2022 |
| Dell          | 0HJK12 A03                  | Server      | [96ad323ca0](https://bsd-hardware.info/?probe=96ad323ca0) | Sep 13, 2022 |
| Dell          | 0H5J4J A01                  | Server      | [acb91f797f](https://bsd-hardware.info/?probe=acb91f797f) | Sep 13, 2022 |
| HP            | 213D A01                    | Desktop     | [6354ddb4a8](https://bsd-hardware.info/?probe=6354ddb4a8) | Sep 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b2dc861f47](https://bsd-hardware.info/?probe=b2dc861f47) | Sep 10, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [3547d9da9c](https://bsd-hardware.info/?probe=3547d9da9c) | Sep 01, 2022 |
| HP            | 213D A01                    | Desktop     | [c495fb5448](https://bsd-hardware.info/?probe=c495fb5448) | Aug 30, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [d721e505cb](https://bsd-hardware.info/?probe=d721e505cb) | Aug 27, 2022 |
| HP            | 213D A01                    | Desktop     | [1b90f312ea](https://bsd-hardware.info/?probe=1b90f312ea) | Aug 26, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [eec9546431](https://bsd-hardware.info/?probe=eec9546431) | Aug 23, 2022 |
| Inventec      | Z CLASS A02                 | Desktop     | [cb3708c9bf](https://bsd-hardware.info/?probe=cb3708c9bf) | Aug 21, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [2e7d570822](https://bsd-hardware.info/?probe=2e7d570822) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [7afa139f4f](https://bsd-hardware.info/?probe=7afa139f4f) | Aug 20, 2022 |
| Gigabyte      | IMB4100TN                   | Desktop     | [aa4bae0d12](https://bsd-hardware.info/?probe=aa4bae0d12) | Aug 15, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [038c5f8763](https://bsd-hardware.info/?probe=038c5f8763) | Aug 10, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [932058e97a](https://bsd-hardware.info/?probe=932058e97a) | Aug 09, 2022 |
| iEi           | B449 V1.00                  | Desktop     | [7776910eea](https://bsd-hardware.info/?probe=7776910eea) | Aug 05, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [c38ad87323](https://bsd-hardware.info/?probe=c38ad87323) | Aug 04, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [6093566ed2](https://bsd-hardware.info/?probe=6093566ed2) | Aug 04, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [706d8fc244](https://bsd-hardware.info/?probe=706d8fc244) | Aug 04, 2022 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [2967d5275e](https://bsd-hardware.info/?probe=2967d5275e) | Jul 29, 2022 |
| HP            | 3397                        | Desktop     | [68eb683936](https://bsd-hardware.info/?probe=68eb683936) | Jul 27, 2022 |
| ASUSTek       | P8B WS                      | Desktop     | [dd7f8123d2](https://bsd-hardware.info/?probe=dd7f8123d2) | Jul 19, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | Notebook    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| HP            | 213D A01                    | Desktop     | [0f58ab215e](https://bsd-hardware.info/?probe=0f58ab215e) | Jul 03, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [a094c1c53b](https://bsd-hardware.info/?probe=a094c1c53b) | Jun 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [fe9f636040](https://bsd-hardware.info/?probe=fe9f636040) | Jun 13, 2022 |
| Dell          | 0TY019 A01                  | Server      | [1aeb1bf3bf](https://bsd-hardware.info/?probe=1aeb1bf3bf) | Jun 09, 2022 |
| Dell          | Latitude 5410               | Notebook    | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [6acbc93101](https://bsd-hardware.info/?probe=6acbc93101) | May 30, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [3f39f21672](https://bsd-hardware.info/?probe=3f39f21672) | May 29, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [6a6fda6d6d](https://bsd-hardware.info/?probe=6a6fda6d6d) | May 26, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ce4d7c01e5](https://bsd-hardware.info/?probe=ce4d7c01e5) | May 24, 2022 |
| HP            | 213D A01                    | Desktop     | [562722ac56](https://bsd-hardware.info/?probe=562722ac56) | Apr 30, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [0d46ae5678](https://bsd-hardware.info/?probe=0d46ae5678) | Apr 25, 2022 |
| Apple         | PowerMac10,1                | Desktop     | [e054e605fa](https://bsd-hardware.info/?probe=e054e605fa) | Apr 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [3c5fcc2377](https://bsd-hardware.info/?probe=3c5fcc2377) | Apr 22, 2022 |
| HP            | 213D A01                    | Desktop     | [4dea775e1b](https://bsd-hardware.info/?probe=4dea775e1b) | Apr 12, 2022 |
| Intel         | NUC6CAYB J26842-405         | Mini pc     | [534af14a9f](https://bsd-hardware.info/?probe=534af14a9f) | Apr 11, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [da64cbb0d1](https://bsd-hardware.info/?probe=da64cbb0d1) | Apr 07, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [9a260e4d21](https://bsd-hardware.info/?probe=9a260e4d21) | Apr 05, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [964ceb3616](https://bsd-hardware.info/?probe=964ceb3616) | Apr 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [5038186437](https://bsd-hardware.info/?probe=5038186437) | Apr 02, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [e0c61311da](https://bsd-hardware.info/?probe=e0c61311da) | Apr 01, 2022 |
| ASUSTek       | P6-P8H61E                   | Desktop     | [11664cd9d7](https://bsd-hardware.info/?probe=11664cd9d7) | Mar 30, 2022 |
| ASUSTek       | P6-P8H61E                   | Desktop     | [540f66f678](https://bsd-hardware.info/?probe=540f66f678) | Mar 29, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [717721a634](https://bsd-hardware.info/?probe=717721a634) | Mar 29, 2022 |
| Dell          | 0DNFFW A00                  | All in one  | [30432daccb](https://bsd-hardware.info/?probe=30432daccb) | Mar 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [38c71bac61](https://bsd-hardware.info/?probe=38c71bac61) | Mar 22, 2022 |
| Acer          | Aptio CRB                   | Mini pc     | [f38b7df811](https://bsd-hardware.info/?probe=f38b7df811) | Mar 20, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [e973d1e806](https://bsd-hardware.info/?probe=e973d1e806) | Mar 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [a54ee6f019](https://bsd-hardware.info/?probe=a54ee6f019) | Mar 18, 2022 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [55515325c4](https://bsd-hardware.info/?probe=55515325c4) | Mar 15, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [a488c9af25](https://bsd-hardware.info/?probe=a488c9af25) | Mar 14, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [9e440b5500](https://bsd-hardware.info/?probe=9e440b5500) | Mar 13, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [b4142103cb](https://bsd-hardware.info/?probe=b4142103cb) | Mar 10, 2022 |
| Dell          | 075CGM A00                  | Mini pc     | [ac38d3156d](https://bsd-hardware.info/?probe=ac38d3156d) | Mar 10, 2022 |
| Inventec      | 0VKXH3 A01                  | Mini pc     | [d018e86ea8](https://bsd-hardware.info/?probe=d018e86ea8) | Mar 10, 2022 |
| Unknown       | LeMaker Banana Pi           | Desktop     | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [4bc5573cf5](https://bsd-hardware.info/?probe=4bc5573cf5) | Mar 02, 2022 |
| Dell          | 0DNFFW A00                  | All in one  | [2db3ec9574](https://bsd-hardware.info/?probe=2db3ec9574) | Feb 27, 2022 |
| Intel         | D945GSEJT                   | Desktop     | [bf6a38dfcb](https://bsd-hardware.info/?probe=bf6a38dfcb) | Feb 26, 2022 |
| HP            | 213D A01                    | Desktop     | [b9560ec339](https://bsd-hardware.info/?probe=b9560ec339) | Feb 24, 2022 |
| Dell          | Latitude E6430              | Notebook    | [fdde41404d](https://bsd-hardware.info/?probe=fdde41404d) | Feb 24, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [a4341268d0](https://bsd-hardware.info/?probe=a4341268d0) | Feb 23, 2022 |
| ASRock        | ConRoe1333-D667             | Desktop     | [624b4f4de7](https://bsd-hardware.info/?probe=624b4f4de7) | Feb 23, 2022 |
| Shuttle       | FZ270                       | Desktop     | [7e0eb61342](https://bsd-hardware.info/?probe=7e0eb61342) | Feb 22, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [feb7882341](https://bsd-hardware.info/?probe=feb7882341) | Feb 22, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [11bed21472](https://bsd-hardware.info/?probe=11bed21472) | Feb 21, 2022 |
| MSI           | MS-AEC11                    | All in one  | [7863616b75](https://bsd-hardware.info/?probe=7863616b75) | Feb 20, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [04e528ca9f](https://bsd-hardware.info/?probe=04e528ca9f) | Feb 19, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [64999a24c1](https://bsd-hardware.info/?probe=64999a24c1) | Feb 16, 2022 |
| Raspberry ... | Raspberry Pi 400            | Desktop     | [dd56609ceb](https://bsd-hardware.info/?probe=dd56609ceb) | Feb 14, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [c024d383e7](https://bsd-hardware.info/?probe=c024d383e7) | Feb 13, 2022 |
| HP            | 213D A01                    | Desktop     | [0171663489](https://bsd-hardware.info/?probe=0171663489) | Feb 12, 2022 |
| Unknown       | LeMaker Banana Pi           | Desktop     | [77413a3d9d](https://bsd-hardware.info/?probe=77413a3d9d) | Feb 12, 2022 |
| MSI           | B75A-G43                    | Desktop     | [8e445eb2d4](https://bsd-hardware.info/?probe=8e445eb2d4) | Feb 08, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [478714c7c9](https://bsd-hardware.info/?probe=478714c7c9) | Feb 07, 2022 |
| MSI           | H61M-P20                    | Desktop     | [98ec852f90](https://bsd-hardware.info/?probe=98ec852f90) | Feb 06, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [f107f7c1b1](https://bsd-hardware.info/?probe=f107f7c1b1) | Feb 06, 2022 |
| ASUSTek       | P6-P8H61E                   | Desktop     | [e838981914](https://bsd-hardware.info/?probe=e838981914) | Feb 06, 2022 |
| Dell          | 075CGM A00                  | Mini pc     | [5a9e6ea87f](https://bsd-hardware.info/?probe=5a9e6ea87f) | Feb 05, 2022 |
| Lenovo        | G500s 20245                 | Notebook    | [41f9f804ac](https://bsd-hardware.info/?probe=41f9f804ac) | Feb 04, 2022 |
| Dell          | 04YP6J A02                  | Desktop     | [550e7feb7f](https://bsd-hardware.info/?probe=550e7feb7f) | Feb 03, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [0b290f2ac3](https://bsd-hardware.info/?probe=0b290f2ac3) | Feb 02, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [f8476c0ea7](https://bsd-hardware.info/?probe=f8476c0ea7) | Feb 01, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [97ef0862c2](https://bsd-hardware.info/?probe=97ef0862c2) | Feb 01, 2022 |
| Dell          | 0K6VXP A00                  | Mini pc     | [cbb110122a](https://bsd-hardware.info/?probe=cbb110122a) | Jan 29, 2022 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [2acf9ac926](https://bsd-hardware.info/?probe=2acf9ac926) | Jan 29, 2022 |
| Intel         | D2500HN AAG81480-500        | Desktop     | [3a39fe5ec2](https://bsd-hardware.info/?probe=3a39fe5ec2) | Jan 29, 2022 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [268906bcbe](https://bsd-hardware.info/?probe=268906bcbe) | Jan 29, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [8e0a22c065](https://bsd-hardware.info/?probe=8e0a22c065) | Jan 28, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [5996ba19b1](https://bsd-hardware.info/?probe=5996ba19b1) | Jan 27, 2022 |
| Dell          | 014GRG A03                  | Desktop     | [223d955a90](https://bsd-hardware.info/?probe=223d955a90) | Jan 26, 2022 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [2506316700](https://bsd-hardware.info/?probe=2506316700) | Jan 26, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [8edf072b67](https://bsd-hardware.info/?probe=8edf072b67) | Jan 25, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [d77aae8064](https://bsd-hardware.info/?probe=d77aae8064) | Jan 23, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [04abd226f3](https://bsd-hardware.info/?probe=04abd226f3) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [9f06290060](https://bsd-hardware.info/?probe=9f06290060) | Jan 17, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [9f442754d0](https://bsd-hardware.info/?probe=9f442754d0) | Jan 17, 2022 |
| Dell          | Latitude E6430              | Notebook    | [e18a4bc564](https://bsd-hardware.info/?probe=e18a4bc564) | Jan 10, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [19be37f181](https://bsd-hardware.info/?probe=19be37f181) | Jan 09, 2022 |
| Intel         | SKYBAY                      | Desktop     | [64db889658](https://bsd-hardware.info/?probe=64db889658) | Jan 01, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [a671e3eb04](https://bsd-hardware.info/?probe=a671e3eb04) | Dec 31, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [b77a4ee97c](https://bsd-hardware.info/?probe=b77a4ee97c) | Dec 30, 2021 |
| Dell          | 0VV3F2 A02                  | Server      | [2897e61a2f](https://bsd-hardware.info/?probe=2897e61a2f) | Dec 28, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [b650885b00](https://bsd-hardware.info/?probe=b650885b00) | Dec 24, 2021 |
| MSI           | H81M-P32                    | Desktop     | [bb4e756ca9](https://bsd-hardware.info/?probe=bb4e756ca9) | Dec 20, 2021 |
| Supermicro    | X11SSN-L-VDCA               | Server      | [2efe92bba7](https://bsd-hardware.info/?probe=2efe92bba7) | Dec 20, 2021 |
| Dell          | Latitude E5470              | Notebook    | [18470afd9d](https://bsd-hardware.info/?probe=18470afd9d) | Dec 19, 2021 |
| Gigabyte      | H110TN                      | Desktop     | [8b6f0f839d](https://bsd-hardware.info/?probe=8b6f0f839d) | Dec 18, 2021 |
| Supermicro    | X11SSN-L-VDCA               | Server      | [5f9458870a](https://bsd-hardware.info/?probe=5f9458870a) | Dec 18, 2021 |
| Dell          | 0YY821 A00                  | Desktop     | [5de293a0be](https://bsd-hardware.info/?probe=5de293a0be) | Dec 17, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [32d20b9b8e](https://bsd-hardware.info/?probe=32d20b9b8e) | Dec 14, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [2921401f70](https://bsd-hardware.info/?probe=2921401f70) | Dec 12, 2021 |
| Dell          | G15 5510                    | Notebook    | [2da7a07664](https://bsd-hardware.info/?probe=2da7a07664) | Dec 07, 2021 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [66ed413cab](https://bsd-hardware.info/?probe=66ed413cab) | Dec 05, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [73373c3c65](https://bsd-hardware.info/?probe=73373c3c65) | Dec 04, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [540d2ef68c](https://bsd-hardware.info/?probe=540d2ef68c) | Nov 29, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [bc3b65334e](https://bsd-hardware.info/?probe=bc3b65334e) | Nov 29, 2021 |
| Dell          | G15 5510                    | Notebook    | [8846b3fd69](https://bsd-hardware.info/?probe=8846b3fd69) | Nov 27, 2021 |
| Shuttle       | FH270                       | Desktop     | [81643d52fd](https://bsd-hardware.info/?probe=81643d52fd) | Nov 26, 2021 |
| Dell          | 0VRCY5 A14                  | Server      | [5add1e88aa](https://bsd-hardware.info/?probe=5add1e88aa) | Nov 26, 2021 |
| Dell          | 0VRCY5 A14                  | Server      | [23281cbd58](https://bsd-hardware.info/?probe=23281cbd58) | Nov 26, 2021 |
| Dell          | 0VRCY5 A14                  | Server      | [f092d1f57b](https://bsd-hardware.info/?probe=f092d1f57b) | Nov 26, 2021 |
| ASRock        | Q1900B-ITX                  | Desktop     | [7f32937b2c](https://bsd-hardware.info/?probe=7f32937b2c) | Nov 26, 2021 |
| Shuttle       | FZ270                       | Desktop     | [309687b5be](https://bsd-hardware.info/?probe=309687b5be) | Nov 26, 2021 |
| ASRock        | Q1900B-ITX                  | Desktop     | [4df18caa5f](https://bsd-hardware.info/?probe=4df18caa5f) | Nov 26, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [74a4364a7f](https://bsd-hardware.info/?probe=74a4364a7f) | Nov 25, 2021 |
| HP            | 213D A01                    | Desktop     | [0059e5b645](https://bsd-hardware.info/?probe=0059e5b645) | Nov 23, 2021 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [7330a6f958](https://bsd-hardware.info/?probe=7330a6f958) | Nov 20, 2021 |
| Gigabyte      | MX33-BS1-V1                 | Server      | [bccac8e3bb](https://bsd-hardware.info/?probe=bccac8e3bb) | Nov 19, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [12a360ddd1](https://bsd-hardware.info/?probe=12a360ddd1) | Nov 14, 2021 |
| Dell          | G15 5510                    | Notebook    | [e9d432bc06](https://bsd-hardware.info/?probe=e9d432bc06) | Nov 12, 2021 |
| Dell          | G15 5510                    | Notebook    | [91750755e4](https://bsd-hardware.info/?probe=91750755e4) | Nov 12, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [0513869be8](https://bsd-hardware.info/?probe=0513869be8) | Nov 09, 2021 |
| Dell          | Latitude E6430              | Notebook    | [46f2ef2432](https://bsd-hardware.info/?probe=46f2ef2432) | Nov 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [d31ea9f041](https://bsd-hardware.info/?probe=d31ea9f041) | Nov 02, 2021 |
| Dell          | 0JD6X3 A05                  | Server      | [76dc6d941d](https://bsd-hardware.info/?probe=76dc6d941d) | Oct 30, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9f8010bdbe](https://bsd-hardware.info/?probe=9f8010bdbe) | Oct 25, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [5c6ee51d15](https://bsd-hardware.info/?probe=5c6ee51d15) | Oct 23, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [f3bf8edc1e](https://bsd-hardware.info/?probe=f3bf8edc1e) | Oct 22, 2021 |
| HP            | 213D A01                    | Desktop     | [4b4903dfb2](https://bsd-hardware.info/?probe=4b4903dfb2) | Oct 17, 2021 |
| Dell          | Latitude E6430              | Notebook    | [d31f35bb29](https://bsd-hardware.info/?probe=d31f35bb29) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H                  | Desktop     | [445b53ddba](https://bsd-hardware.info/?probe=445b53ddba) | Oct 15, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [3d0a63b493](https://bsd-hardware.info/?probe=3d0a63b493) | Oct 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [fc1eda0998](https://bsd-hardware.info/?probe=fc1eda0998) | Oct 08, 2021 |
| Gigabyte      | B450M DS3H                  | Desktop     | [50e4e13ee0](https://bsd-hardware.info/?probe=50e4e13ee0) | Oct 07, 2021 |
| MSI           | MS-7B53                     | Desktop     | [c7104d301e](https://bsd-hardware.info/?probe=c7104d301e) | Oct 05, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [49173900e7](https://bsd-hardware.info/?probe=49173900e7) | Oct 04, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [d05a877535](https://bsd-hardware.info/?probe=d05a877535) | Oct 03, 2021 |
| ASUSTek       | X555LB                      | Notebook    | [e3443d9f27](https://bsd-hardware.info/?probe=e3443d9f27) | Oct 02, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [96448603f5](https://bsd-hardware.info/?probe=96448603f5) | Oct 02, 2021 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [e186d750d0](https://bsd-hardware.info/?probe=e186d750d0) | Sep 30, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [a302e181a5](https://bsd-hardware.info/?probe=a302e181a5) | Sep 27, 2021 |
| Dell          | 04YP6J A02                  | Desktop     | [9ff547c00b](https://bsd-hardware.info/?probe=9ff547c00b) | Sep 16, 2021 |
| IBM           | ThinkPad X41 2525FAG        | Notebook    | [63a34dc807](https://bsd-hardware.info/?probe=63a34dc807) | Sep 14, 2021 |
| ASUSTek       | Q87T                        | Desktop     | [91e631c240](https://bsd-hardware.info/?probe=91e631c240) | Sep 11, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [c7b549e91e](https://bsd-hardware.info/?probe=c7b549e91e) | Sep 02, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9e13729a12](https://bsd-hardware.info/?probe=9e13729a12) | Sep 02, 2021 |
| Essentiel ... | MS-7848                     | Desktop     | [fa20a0307e](https://bsd-hardware.info/?probe=fa20a0307e) | Sep 01, 2021 |
| Dell          | 086HF8 A07                  | Server      | [810f826ac4](https://bsd-hardware.info/?probe=810f826ac4) | Aug 26, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [38332c6f8d](https://bsd-hardware.info/?probe=38332c6f8d) | Aug 16, 2021 |
| Lenovo        | Unknown                     | Notebook    | [e16ce5e864](https://bsd-hardware.info/?probe=e16ce5e864) | Aug 08, 2021 |
| AOpen         | D1009 A1A4                  | Desktop     | [dc60a8dece](https://bsd-hardware.info/?probe=dc60a8dece) | Aug 03, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [77676fbcfc](https://bsd-hardware.info/?probe=77676fbcfc) | Jul 18, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [fd9fbe6981](https://bsd-hardware.info/?probe=fd9fbe6981) | Jul 16, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [ccbdcabf0a](https://bsd-hardware.info/?probe=ccbdcabf0a) | Jul 12, 2021 |
| HP            | 1998                        | Desktop     | [fdf0088303](https://bsd-hardware.info/?probe=fdf0088303) | Jul 08, 2021 |
| Supermicro    | X10SDV-TP8F                 | Server      | [51d7177ca5](https://bsd-hardware.info/?probe=51d7177ca5) | Jul 01, 2021 |
| Toshiba       | PORTEGE X20W-D              | Convertible | [1e5dc453f6](https://bsd-hardware.info/?probe=1e5dc453f6) | Jun 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [668bf95221](https://bsd-hardware.info/?probe=668bf95221) | Jun 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [1fffc03fbf](https://bsd-hardware.info/?probe=1fffc03fbf) | Jun 24, 2021 |
| Lenovo        | ThinkPad T440 20B7S1860W    | Notebook    | [8552205176](https://bsd-hardware.info/?probe=8552205176) | Jun 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9f82e215c3](https://bsd-hardware.info/?probe=9f82e215c3) | Jun 22, 2021 |
| Dell          | 0MJ137 A00                  | Server      | [8a115f25d1](https://bsd-hardware.info/?probe=8a115f25d1) | Jun 18, 2021 |
| Dell          | Vostro 3560                 | Notebook    | [ce9d5f9a46](https://bsd-hardware.info/?probe=ce9d5f9a46) | Jun 18, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [4097d7aea8](https://bsd-hardware.info/?probe=4097d7aea8) | Jun 16, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [a9fe2f5aad](https://bsd-hardware.info/?probe=a9fe2f5aad) | Jun 16, 2021 |
| Lenovo        | Board                       | Desktop     | [c981ffdff7](https://bsd-hardware.info/?probe=c981ffdff7) | Jun 15, 2021 |
| Dell          | Latitude 5400               | Notebook    | [1bb6c1f63f](https://bsd-hardware.info/?probe=1bb6c1f63f) | Jun 15, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [eeb4489d2f](https://bsd-hardware.info/?probe=eeb4489d2f) | Jun 13, 2021 |
| Dell          | Latitude E6440              | Notebook    | [8fa2c1f5c4](https://bsd-hardware.info/?probe=8fa2c1f5c4) | Jun 13, 2021 |
| Dell          | Latitude E6440              | Notebook    | [77f259babe](https://bsd-hardware.info/?probe=77f259babe) | Jun 12, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [338240a790](https://bsd-hardware.info/?probe=338240a790) | Jun 05, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [bf23a1ca58](https://bsd-hardware.info/?probe=bf23a1ca58) | Jun 02, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [9f4ebe949f](https://bsd-hardware.info/?probe=9f4ebe949f) | May 31, 2021 |
| MSI           | H81M-P32                    | Desktop     | [1ffaa46853](https://bsd-hardware.info/?probe=1ffaa46853) | May 31, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [b19abd94b7](https://bsd-hardware.info/?probe=b19abd94b7) | May 31, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [732a50af16](https://bsd-hardware.info/?probe=732a50af16) | May 29, 2021 |
| MSI           | H81M-P32                    | Desktop     | [253deda07f](https://bsd-hardware.info/?probe=253deda07f) | May 28, 2021 |
| Lenovo        | Board                       | Desktop     | [1d6f23a5de](https://bsd-hardware.info/?probe=1d6f23a5de) | May 24, 2021 |
| Dell          | Latitude E6410              | Notebook    | [211fe874fd](https://bsd-hardware.info/?probe=211fe874fd) | May 22, 2021 |
| Dell          | 0R230R A00                  | Desktop     | [bd8bf06e7f](https://bsd-hardware.info/?probe=bd8bf06e7f) | May 21, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [6317bd7dbd](https://bsd-hardware.info/?probe=6317bd7dbd) | May 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [1dcb55d9fe](https://bsd-hardware.info/?probe=1dcb55d9fe) | May 05, 2021 |
| Supermicro    | X7DCL                       | Desktop     | [27fc294bca](https://bsd-hardware.info/?probe=27fc294bca) | May 03, 2021 |
| Dell          | Latitude E6440              | Notebook    | [3a656ded12](https://bsd-hardware.info/?probe=3a656ded12) | Apr 19, 2021 |
| Dell          | Latitude E6440              | Notebook    | [68f57531cb](https://bsd-hardware.info/?probe=68f57531cb) | Apr 19, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [b848b8e046](https://bsd-hardware.info/?probe=b848b8e046) | Apr 03, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [7ce3b2f01e](https://bsd-hardware.info/?probe=7ce3b2f01e) | Mar 27, 2021 |
| Dell          | 086HF8 A07                  | Server      | [0a3a820345](https://bsd-hardware.info/?probe=0a3a820345) | Mar 26, 2021 |
| Supermicro    | X7SLA                       | Desktop     | [043c20b93d](https://bsd-hardware.info/?probe=043c20b93d) | Mar 19, 2021 |
| Dell          | Latitude E6440              | Notebook    | [a332efd9d9](https://bsd-hardware.info/?probe=a332efd9d9) | Mar 15, 2021 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b570778ef7](https://bsd-hardware.info/?probe=b570778ef7) | Mar 14, 2021 |
| Dell          | 0TY019 A01                  | Server      | [6a1cb01323](https://bsd-hardware.info/?probe=6a1cb01323) | Mar 09, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [dee034110e](https://bsd-hardware.info/?probe=dee034110e) | Mar 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [73eec13c5e](https://bsd-hardware.info/?probe=73eec13c5e) | Mar 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [6d7bac1be1](https://bsd-hardware.info/?probe=6d7bac1be1) | Feb 23, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [60d084275e](https://bsd-hardware.info/?probe=60d084275e) | Feb 19, 2021 |
| Dell          | 05KX61 A02                  | Server      | [31b6e52cf4](https://bsd-hardware.info/?probe=31b6e52cf4) | Feb 15, 2021 |
| HP            | ENVY dv7                    | Notebook    | [4637a9eeff](https://bsd-hardware.info/?probe=4637a9eeff) | Feb 14, 2021 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [8d8683565a](https://bsd-hardware.info/?probe=8d8683565a) | Feb 13, 2021 |
| ASRock        | D1800B-ITX                  | Desktop     | [38f8b13f43](https://bsd-hardware.info/?probe=38f8b13f43) | Feb 10, 2021 |
| Unknown       | Unknown                     | Desktop     | [f4b7bb4518](https://bsd-hardware.info/?probe=f4b7bb4518) | Feb 08, 2021 |
| Dell          | 096JG8 A00                  | Desktop     | [b6630c8516](https://bsd-hardware.info/?probe=b6630c8516) | Feb 07, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [bee421a110](https://bsd-hardware.info/?probe=bee421a110) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [e8157ac6a3](https://bsd-hardware.info/?probe=e8157ac6a3) | Feb 06, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [5f293a8796](https://bsd-hardware.info/?probe=5f293a8796) | Feb 05, 2021 |
| Dell          | 096JG8 A00                  | Desktop     | [e73a728a76](https://bsd-hardware.info/?probe=e73a728a76) | Feb 03, 2021 |
| Dell          | 096JG8 A00                  | Desktop     | [612272e598](https://bsd-hardware.info/?probe=612272e598) | Feb 03, 2021 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [3d18f3f8a9](https://bsd-hardware.info/?probe=3d18f3f8a9) | Jan 23, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [b26cfcd81d](https://bsd-hardware.info/?probe=b26cfcd81d) | Dec 28, 2020 |
| Lenovo        | ThinkPad X200s 7470A98      | Notebook    | [41f36aa8b6](https://bsd-hardware.info/?probe=41f36aa8b6) | Dec 19, 2020 |
| ASUSTek       | E45M1-I DELUXE              | Desktop     | [8e767b517d](https://bsd-hardware.info/?probe=8e767b517d) | Dec 16, 2020 |
| Unknown       | Spring Peak                 | Notebook    | [b61f5c268a](https://bsd-hardware.info/?probe=b61f5c268a) | Dec 15, 2020 |
| PC Special... | Recoil II                   | Notebook    | [343eec31b5](https://bsd-hardware.info/?probe=343eec31b5) | Dec 06, 2020 |
| Panasonic     | CFMX4-1                     | Notebook    | [761d21f21a](https://bsd-hardware.info/?probe=761d21f21a) | Dec 06, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [dce3ba8c99](https://bsd-hardware.info/?probe=dce3ba8c99) | Nov 18, 2020 |
| HP            | 213D A01                    | Desktop     | [ca6ab5347e](https://bsd-hardware.info/?probe=ca6ab5347e) | Nov 13, 2020 |
| Shuttle       | FH270                       | Desktop     | [532cda62a8](https://bsd-hardware.info/?probe=532cda62a8) | Oct 29, 2020 |
| Intel         | D53427RKE G87971-406        | Desktop     | [bb6eeb8ef8](https://bsd-hardware.info/?probe=bb6eeb8ef8) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [8f4b51dabd](https://bsd-hardware.info/?probe=8f4b51dabd) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [bb3d02abc3](https://bsd-hardware.info/?probe=bb3d02abc3) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [26d1d76748](https://bsd-hardware.info/?probe=26d1d76748) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [fb3b9ecee9](https://bsd-hardware.info/?probe=fb3b9ecee9) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [785c53f34c](https://bsd-hardware.info/?probe=785c53f34c) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [f5efac2cc7](https://bsd-hardware.info/?probe=f5efac2cc7) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [cc8f51b953](https://bsd-hardware.info/?probe=cc8f51b953) | Oct 29, 2020 |
| Dell          | 0VRCY5 A14                  | Server      | [397aee2b27](https://bsd-hardware.info/?probe=397aee2b27) | Oct 29, 2020 |
| Intel         | S2600GZ G11481-352          | Server      | [474b0e44ea](https://bsd-hardware.info/?probe=474b0e44ea) | Oct 29, 2020 |
| Dell          | 0M332H A00                  | Server      | [9c70f76349](https://bsd-hardware.info/?probe=9c70f76349) | Oct 29, 2020 |
| Dell          | 072T6D A01                  | Server      | [4389b1ce81](https://bsd-hardware.info/?probe=4389b1ce81) | Oct 29, 2020 |
| Shuttle       | FH270                       | Desktop     | [e93928c59b](https://bsd-hardware.info/?probe=e93928c59b) | Oct 29, 2020 |
| ASRock        | QC5000M-ITX/PH              | Desktop     | [8d27c35122](https://bsd-hardware.info/?probe=8d27c35122) | Oct 29, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | Notebook    | [2664153a6e](https://bsd-hardware.info/?probe=2664153a6e) | Oct 29, 2020 |
| Dell          | 06NWYK A01                  | Desktop     | [9d4ea8797b](https://bsd-hardware.info/?probe=9d4ea8797b) | Oct 29, 2020 |
| Dell          | 06NWYK A01                  | Desktop     | [5ae47d058d](https://bsd-hardware.info/?probe=5ae47d058d) | Oct 29, 2020 |
| Lenovo        | ThinkPad X230 23254S6       | Notebook    | [f4ac5ddaa4](https://bsd-hardware.info/?probe=f4ac5ddaa4) | Oct 25, 2020 |
| HP            | 635                         | Notebook    | [3b21406e87](https://bsd-hardware.info/?probe=3b21406e87) | Oct 23, 2020 |
| PC Engines    | apu1                        | Desktop     | [c77b06b3eb](https://bsd-hardware.info/?probe=c77b06b3eb) | Oct 20, 2020 |
| Lenovo        | ThinkPad T480 20L6S4GR02    | Notebook    | [6c2d8a57ea](https://bsd-hardware.info/?probe=6c2d8a57ea) | Oct 19, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | Notebook    | [01d2c090de](https://bsd-hardware.info/?probe=01d2c090de) | Oct 03, 2020 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [4906f28cfc](https://bsd-hardware.info/?probe=4906f28cfc) | Aug 14, 2020 |
| ASUSTek       | AM1M-A                      | Desktop     | [4dca0d2aa4](https://bsd-hardware.info/?probe=4dca0d2aa4) | Aug 14, 2020 |
| PC Engines    | APU2                        | Desktop     | [82f64585b8](https://bsd-hardware.info/?probe=82f64585b8) | Aug 14, 2020 |
| Fujitsu       | D3003-B1 S26361-D3003-B1    | Desktop     | [8c92fcf25f](https://bsd-hardware.info/?probe=8c92fcf25f) | Aug 14, 2020 |
| Fujitsu       | D3003-B1 S26361-D3003-B1    | Desktop     | [b6a4e39a1b](https://bsd-hardware.info/?probe=b6a4e39a1b) | Aug 14, 2020 |
| Dell          | Latitude XT2                | Notebook    | [19456100cf](https://bsd-hardware.info/?probe=19456100cf) | Jul 16, 2020 |
| Dell          | Latitude XT2                | Notebook    | [160725773f](https://bsd-hardware.info/?probe=160725773f) | Jul 16, 2020 |
| Sony          | SVF1521K1EB                 | Notebook    | [fe29d4e002](https://bsd-hardware.info/?probe=fe29d4e002) | Jun 29, 2020 |
| ASRock        | N3150B-ITX                  | Desktop     | [2b9248155e](https://bsd-hardware.info/?probe=2b9248155e) | Jun 09, 2020 |
| ASUSTek       | N3150I-C                    | Desktop     | [3da71be3c9](https://bsd-hardware.info/?probe=3da71be3c9) | Jun 09, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | Notebook    | [9ba8051e48](https://bsd-hardware.info/?probe=9ba8051e48) | Jun 09, 2020 |
| Dell          | Latitude E7240              | Notebook    | [1de87c0000](https://bsd-hardware.info/?probe=1de87c0000) | May 30, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.8.1    | 30        | 5.21%   |
| helloSystem 0.7.0    | 15        | 2.6%    |
| OpenBSD 7.0          | 12        | 2.08%   |
| FreeBSD 12.1-p10     | 12        | 2.08%   |
| OPNsense 22.7.10     | 9         | 1.56%   |
| FreeBSD 14.0-CURRENT | 9         | 1.56%   |
| FreeBSD 13.1-p8      | 9         | 1.56%   |
| OPNsense 24.7.1      | 7         | 1.22%   |
| OPNsense 24.1.9      | 7         | 1.22%   |
| OPNsense 24.1.7      | 7         | 1.22%   |
| OPNsense 23.7.12     | 7         | 1.22%   |
| OPNsense 23.1.7      | 7         | 1.22%   |
| OPNsense 23.1.11     | 7         | 1.22%   |
| OPNsense 23.1.1      | 7         | 1.22%   |
| FreeBSD 13.2         | 7         | 1.22%   |
| OPNsense 24.7.6      | 6         | 1.04%   |
| OPNsense 24.1.8      | 6         | 1.04%   |
| OPNsense 24.1.4      | 6         | 1.04%   |
| OPNsense 23.7.9      | 6         | 1.04%   |
| OPNsense 23.7.7      | 6         | 1.04%   |
| OPNsense 23.1        | 6         | 1.04%   |
| OpenBSD 7.1          | 6         | 1.04%   |
| helloSystem 0.9.0    | 6         | 1.04%   |
| helloSystem 0.6.0    | 6         | 1.04%   |
| FreeBSD 12.2         | 6         | 1.04%   |
| OPNsense 24.7.11     | 5         | 0.87%   |
| OPNsense 24.1.6      | 5         | 0.87%   |
| OPNsense 24.1.5      | 5         | 0.87%   |
| OPNsense 23.7.5      | 5         | 0.87%   |
| OPNsense 23.7.4      | 5         | 0.87%   |
| OPNsense 23.1.5      | 5         | 0.87%   |
| OPNsense 22.1        | 5         | 0.87%   |
| OPNsense 21.7.3      | 5         | 0.87%   |
| OPNsense 21.1.6      | 5         | 0.87%   |
| helloSystem 0.8.0    | 5         | 0.87%   |
| helloSystem 0.5.0    | 5         | 0.87%   |
| FreeBSD 14.1         | 5         | 0.87%   |
| FreeBSD 13.0-p5      | 5         | 0.87%   |
| OPNsense 24.7.8      | 4         | 0.69%   |
| OPNsense 24.7.5      | 4         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 211       | 47.95%  |
| FreeBSD     | 109       | 24.77%  |
| helloSystem | 67        | 15.23%  |
| OpenBSD     | 29        | 6.59%   |
| GhostBSD    | 13        | 2.95%   |
| NetBSD      | 4         | 0.91%   |
| NomadBSD    | 3         | 0.68%   |
| XigmaNAS    | 2         | 0.45%   |
| MyBee       | 1         | 0.23%   |
| DragonFly   | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 426       | 97.04%  |
| arm64  | 6         | 1.37%   |
| i386   | 4         | 0.91%   |
| macppc | 1         | 0.23%   |
| evbarm | 1         | 0.23%   |
| armv7  | 1         | 0.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 268       | 60.09%  |
| helloDesktop  | 77        | 17.26%  |
| XFCE          | 20        | 4.48%   |
| GNOME         | 17        | 3.81%   |
| fvwm          | 16        | 3.59%   |
| MATE          | 15        | 3.36%   |
| KDE5          | 12        | 2.69%   |
| i3            | 8         | 1.79%   |
| openbox       | 5         | 1.12%   |
| TWM           | 4         | 0.9%    |
| xinitrc       | 1         | 0.22%   |
| xfwm          | 1         | 0.22%   |
| KDE           | 1         | 0.22%   |
| Enlightenment | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 281       | 63.72%  |
| X11     | 160       | 36.28%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 316       | 71.33%  |
| SLiM    | 77        | 17.38%  |
| LightDM | 18        | 4.06%   |
| SDDM    | 15        | 3.39%   |
| GDM     | 9         | 2.03%   |
| XDM     | 8         | 1.81%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 275       | 61.66%  |
| C              | 63        | 14.13%  |
| en_US          | 57        | 12.78%  |
| pl_PL          | 35        | 7.85%   |
| fr_FR          | 9         | 2.02%   |
| pl             | 2         | 0.45%   |
| en_GB          | 2         | 0.45%   |
| pt_PT          | 1         | 0.22%   |
| en_IE.US-ASCII | 1         | 0.22%   |
| en             | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 372       | 84.35%  |
| BIOS | 69        | 15.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 226       | 50.79%  |
| Ufs     | 161       | 36.18%  |
| Ffs     | 29        | 6.52%   |
| Cd9660  | 28        | 6.29%   |
| Hammer2 | 1         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 400       | 91.12%  |
| MBR     | 30        | 6.83%   |
| Unknown | 8         | 1.82%   |
| BSD     | 1         | 0.23%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 78        | 17.77%  |
| Lenovo                     | 55        | 12.53%  |
| Hewlett-Packard            | 46        | 10.48%  |
| Unknown                    | 42        | 9.57%   |
| ASUSTek Computer           | 30        | 6.83%   |
| Gigabyte Technology        | 28        | 6.38%   |
| Intel                      | 21        | 4.78%   |
| ASRock                     | 18        | 4.1%    |
| MSI                        | 17        | 3.87%   |
| Fujitsu                    | 17        | 3.87%   |
| Supermicro                 | 13        | 2.96%   |
| ZOTAC                      | 6         | 1.37%   |
| Acer                       | 6         | 1.37%   |
| Techvision                 | 5         | 1.14%   |
| PC Engines                 | 5         | 1.14%   |
| Apple                      | 5         | 1.14%   |
| Deciso                     | 4         | 0.91%   |
| Shuttle                    | 3         | 0.68%   |
| Sony                       | 2         | 0.46%   |
| Raspberry Pi Foundation    | 2         | 0.46%   |
| Inventec                   | 2         | 0.46%   |
| IGEL Technology            | 2         | 0.46%   |
| iEi                        | 2         | 0.46%   |
| Google                     | 2         | 0.46%   |
| CheckPoint                 | 2         | 0.46%   |
| Biostar                    | 2         | 0.46%   |
| AMI                        | 2         | 0.46%   |
| Yanling                    | 1         | 0.23%   |
| Wistron                    | 1         | 0.23%   |
| Toshiba                    | 1         | 0.23%   |
| ShenZhen MinWin Technology | 1         | 0.23%   |
| Seeed Studio               | 1         | 0.23%   |
| Samsung Electronics        | 1         | 0.23%   |
| Protectli                  | 1         | 0.23%   |
| PC Specialist              | 1         | 0.23%   |
| Panasonic                  | 1         | 0.23%   |
| Packard Bell               | 1         | 0.23%   |
| OEM                        | 1         | 0.23%   |
| NU591R                     | 1         | 0.23%   |
| Notebook                   | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 44        | 10.02%  |
| Dell OEM-R 720xd                    | 14        | 3.19%   |
| HP t620 PLUS Quad Core TC           | 13        | 2.96%   |
| Fujitsu FUTRO S920                  | 9         | 2.05%   |
| Dell Wyse 5070 Extended Thin Client | 7         | 1.59%   |
| Techvision TVI7309X                 | 5         | 1.14%   |
| Lenovo ThinkPad X200 745969G        | 5         | 1.14%   |
| Gigabyte B360N WIFI                 | 5         | 1.14%   |
| Dell Wyse 5070 Thin Client          | 4         | 0.91%   |
| ZOTAC ZBOX-CI329NANO                | 3         | 0.68%   |
| Supermicro X9SCL/X9SCM              | 3         | 0.68%   |
| ASUS All Series                     | 3         | 0.68%   |
| ASRock Q1900B-ITX                   | 3         | 0.68%   |
| ZOTAC ZBOX-CI341                    | 2         | 0.46%   |
| PC Engines APU2                     | 2         | 0.46%   |
| MSI MS-7D25                         | 2         | 0.46%   |
| MSI MS-7918                         | 2         | 0.46%   |
| MSI MS-7758                         | 2         | 0.46%   |
| Lenovo ThinkCentre M700 10J0S1CK00  | 2         | 0.46%   |
| Lenovo System x3250 M6 -[3633AC1]-  | 2         | 0.46%   |
| Lenovo G580 20150                   | 2         | 0.46%   |
| Intel SHARKBAY                      | 2         | 0.46%   |
| Intel Q3XXG4-P V1.0                 | 2         | 0.46%   |
| Intel D2500CC AAG81477-401          | 2         | 0.46%   |
| Intel Appliance B4                  | 2         | 0.46%   |
| HP t730 Thin Client                 | 2         | 0.46%   |
| HP ProLiant DL360p Gen8             | 2         | 0.46%   |
| HP ProLiant DL360 G7                | 2         | 0.46%   |
| HP 17E2                             | 2         | 0.46%   |
| Gigabyte H270N-WIFI                 | 2         | 0.46%   |
| Gigabyte H110TN                     | 2         | 0.46%   |
| Dell OptiPlex 7050                  | 2         | 0.46%   |
| Dell OptiPlex 3040                  | 2         | 0.46%   |
| Dell OptiPlex 3020                  | 2         | 0.46%   |
| Dell Latitude E6430                 | 2         | 0.46%   |
| CheckPoint QS-22-00                 | 2         | 0.46%   |
| ASUS P7P55D                         | 2         | 0.46%   |
| ASRock J3455B-ITX                   | 2         | 0.46%   |
| Apple MacBookPro11,4                | 2         | 0.46%   |
| ZOTAC ZBOX-CI323NANO                | 1         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Unknown              | 44        | 10.02%  |
| Lenovo ThinkPad      | 30        | 6.83%   |
| Dell OptiPlex        | 15        | 3.42%   |
| Dell OEM-R           | 14        | 3.19%   |
| HP t620              | 13        | 2.96%   |
| Fujitsu FUTRO        | 13        | 2.96%   |
| Dell PowerEdge       | 13        | 2.96%   |
| Dell Latitude        | 13        | 2.96%   |
| Dell Wyse            | 11        | 2.51%   |
| Lenovo ThinkCentre   | 10        | 2.28%   |
| HP ProLiant          | 6         | 1.37%   |
| Techvision TVI7309X  | 5         | 1.14%   |
| Gigabyte B360N       | 5         | 1.14%   |
| Dell Vostro          | 5         | 1.14%   |
| HP EliteDesk         | 4         | 0.91%   |
| Acer Aspire          | 4         | 0.91%   |
| ZOTAC ZBOX-CI329NANO | 3         | 0.68%   |
| Supermicro X9SCL     | 3         | 0.68%   |
| Intel D2500CC        | 3         | 0.68%   |
| HP t730              | 3         | 0.68%   |
| HP EliteBook         | 3         | 0.68%   |
| HP Compaq            | 3         | 0.68%   |
| ASUS PRIME           | 3         | 0.68%   |
| ASUS All             | 3         | 0.68%   |
| ASRock Q1900B-ITX    | 3         | 0.68%   |
| ZOTAC ZBOX-CI341     | 2         | 0.46%   |
| RPi Raspberry        | 2         | 0.46%   |
| PC Engines APU2      | 2         | 0.46%   |
| MSI MS-7D25          | 2         | 0.46%   |
| MSI MS-7918          | 2         | 0.46%   |
| MSI MS-7758          | 2         | 0.46%   |
| Lenovo System        | 2         | 0.46%   |
| Lenovo IdeaPad       | 2         | 0.46%   |
| Lenovo G580          | 2         | 0.46%   |
| Intel SHARKBAY       | 2         | 0.46%   |
| Intel Q3XXG4-P       | 2         | 0.46%   |
| Intel Appliance      | 2         | 0.46%   |
| HP Laptop            | 2         | 0.46%   |
| HP ENVY              | 2         | 0.46%   |
| HP 17E2              | 2         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 52        | 11.85%  |
| 2018    | 45        | 10.25%  |
| 2020    | 38        | 8.66%   |
| 2013    | 36        | 8.2%    |
| 2012    | 32        | 7.29%   |
| 2019    | 31        | 7.06%   |
| 2022    | 28        | 6.38%   |
| 2023    | 27        | 6.15%   |
| 2016    | 26        | 5.92%   |
| 2021    | 24        | 5.47%   |
| 2017    | 17        | 3.87%   |
| 2011    | 17        | 3.87%   |
| 2009    | 17        | 3.87%   |
| 2015    | 14        | 3.19%   |
| 2010    | 12        | 2.73%   |
| 2024    | 8         | 1.82%   |
| Unknown | 6         | 1.37%   |
| 2008    | 3         | 0.68%   |
| 2007    | 3         | 0.68%   |
| 2006    | 3         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 250       | 56.95%  |
| Notebook       | 107       | 24.37%  |
| Server         | 44        | 10.02%  |
| Mini pc        | 28        | 6.38%   |
| All in one     | 6         | 1.37%   |
| System on chip | 2         | 0.46%   |
| Convertible    | 2         | 0.46%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 431       | 98.18%  |
| Yes  | 8         | 1.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 142       | 31.56%  |
| 16.01-24.0      | 114       | 25.33%  |
| 4.01-8.0        | 102       | 22.67%  |
| 32.01-64.0      | 37        | 8.22%   |
| 64.01-256.0     | 26        | 5.78%   |
| 2.01-3.0        | 9         | 2%      |
| 3.01-4.0        | 7         | 1.56%   |
| 0.51-1.0        | 5         | 1.11%   |
| 24.01-32.0      | 4         | 0.89%   |
| More than 256.0 | 2         | 0.44%   |
| 1.01-2.0        | 1         | 0.22%   |
| 0.01-0.5        | 1         | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 218       | 47.91%  |
| 0.51-1.0    | 143       | 31.43%  |
| 1.01-2.0    | 63        | 13.85%  |
| 2.01-3.0    | 10        | 2.2%    |
| 4.01-8.0    | 7         | 1.54%   |
| 8.01-16.0   | 4         | 0.88%   |
| Unknown     | 4         | 0.88%   |
| 3.01-4.0    | 2         | 0.44%   |
| 0           | 2         | 0.44%   |
| 64.01-256.0 | 1         | 0.22%   |
| 16.01-24.0  | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 258       | 55.97%  |
| 2      | 82        | 17.79%  |
| 0      | 77        | 16.7%   |
| 3      | 15        | 3.25%   |
| 4      | 10        | 2.17%   |
| 5      | 8         | 1.74%   |
| 6      | 6         | 1.3%    |
| 9      | 2         | 0.43%   |
| 8      | 2         | 0.43%   |
| 10     | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 360       | 81.08%  |
| Yes       | 84        | 18.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 415       | 94.53%  |
| No        | 24        | 5.47%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 254       | 57.21%  |
| Yes       | 190       | 42.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 321       | 71.97%  |
| Yes       | 125       | 28.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Poland  | 439       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Warsaw               | 71        | 14.55%  |
| Krakow               | 41        | 8.4%    |
| Wroclaw              | 34        | 6.97%   |
| Gdansk               | 28        | 5.74%   |
| Gdynia               | 25        | 5.12%   |
| Poznan               | 17        | 3.48%   |
| Lodz                 | 15        | 3.07%   |
| Lublin               | 9         | 1.84%   |
| Katowice             | 7         | 1.43%   |
| Radom                | 6         | 1.23%   |
| Bydgoszcz            | 6         | 1.23%   |
| Szczecin             | 5         | 1.02%   |
| Piaseczno            | 5         | 1.02%   |
| Zgierz               | 4         | 0.82%   |
| Miedziana Gora       | 4         | 0.82%   |
| Gliwice              | 4         | 0.82%   |
| Bialystok            | 4         | 0.82%   |
| Torun                | 3         | 0.61%   |
| Rybnik               | 3         | 0.61%   |
| Puławy              | 3         | 0.61%   |
| Lubin                | 3         | 0.61%   |
| Lezno                | 3         | 0.61%   |
| Legionowo            | 3         | 0.61%   |
| Kielce               | 3         | 0.61%   |
| Gmina Świebodzin    | 3         | 0.61%   |
| Chrusty              | 3         | 0.61%   |
| Е»ukowo            | 2         | 0.41%   |
| Zielona Góra        | 2         | 0.41%   |
| Zdunska Wola         | 2         | 0.41%   |
| Włocławek          | 2         | 0.41%   |
| Witkow               | 2         | 0.41%   |
| Walendow             | 2         | 0.41%   |
| Sulejowek            | 2         | 0.41%   |
| Siedlce              | 2         | 0.41%   |
| Rzeszów             | 2         | 0.41%   |
| Radzionkow           | 2         | 0.41%   |
| Pstragowa            | 2         | 0.41%   |
| Police               | 2         | 0.41%   |
| Piotrkow Trybunalski | 2         | 0.41%   |
| Pepowo               | 2         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 70        | 125    | 14.37%  |
| WDC                 | 64        | 144    | 13.14%  |
| Seagate             | 57        | 112    | 11.7%   |
| GOODRAM             | 32        | 51     | 6.57%   |
| SanDisk             | 28        | 38     | 5.75%   |
| A-DATA Technology   | 22        | 29     | 4.52%   |
| Kingston            | 19        | 22     | 3.9%    |
| Toshiba             | 16        | 34     | 3.29%   |
| SPCC                | 13        | 20     | 2.67%   |
| Intel               | 13        | 19     | 2.67%   |
| Crucial             | 12        | 22     | 2.46%   |
| Transcend           | 11        | 18     | 2.26%   |
| Hitachi             | 9         | 9      | 1.85%   |
| Apacer              | 9         | 16     | 1.85%   |
| SK hynix            | 8         | 8      | 1.64%   |
| China               | 7         | 10     | 1.44%   |
| NVMe                | 6         | 9      | 1.23%   |
| Innodisk            | 6         | 8      | 1.23%   |
| Hoodisk             | 6         | 13     | 1.23%   |
| Hewlett-Packard     | 6         | 6      | 1.23%   |
| PNY                 | 5         | 9      | 1.03%   |
| Plextor             | 5         | 5      | 1.03%   |
| Patriot             | 5         | 7      | 1.03%   |
| OCZ                 | 4         | 4      | 0.82%   |
| Micron Technology   | 4         | 10     | 0.82%   |
| LITEONIT            | 4         | 6      | 0.82%   |
| LITEON              | 4         | 4      | 0.82%   |
| Lexar               | 4         | 4      | 0.82%   |
| HGST                | 4         | 6      | 0.82%   |
| Gigabyte Technology | 4         | 5      | 0.82%   |
| Kston               | 3         | 3      | 0.62%   |
| Corsair             | 3         | 6      | 0.62%   |
| Apple               | 3         | 3      | 0.62%   |
| Phison              | 2         | 2      | 0.41%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.41%   |
| Intenso             | 2         | 3      | 0.41%   |
| Fanxiang            | 2         | 3      | 0.41%   |
| XPG                 | 1         | 1      | 0.21%   |
| Vaseky              | 1         | 1      | 0.21%   |
| Team                | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WDS500G1R0A-68A4W0 500GB         | 6         | 1.11%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 6         | 1.11%   |
| Samsung HM321HI 320GB                | 6         | 1.11%   |
| WDC WD5000LPLX-22ZNTT0 500GB         | 5         | 0.93%   |
| Seagate ST1000DM003-1CH162 1TB       | 5         | 0.93%   |
| Crucial CT500MX500SSD1 500GB         | 5         | 0.93%   |
| WDC WD20EFRX-68EUZN0 2TB             | 4         | 0.74%   |
| SPCC Solid State Disk 256GB          | 4         | 0.74%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 0.74%   |
| SanDisk SDSA6MM-016G-1006 16GB       | 4         | 0.74%   |
| Hoodisk SSD 128GB                    | 4         | 0.74%   |
| GOODRAM SSDPR-CX400-512-G2 512GB     | 4         | 0.74%   |
| WDC WD5003ABYZ-011FA0 500GB          | 3         | 0.56%   |
| SPCC Solid State Disk 512GB          | 3         | 0.56%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.56%   |
| Seagate ST500DM002-1BD142 500GB      | 3         | 0.56%   |
| Seagate ST1000NM0033-9ZM173 1TB      | 3         | 0.56%   |
| Samsung SSD 980 1TB                  | 3         | 0.56%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.56%   |
| Samsung SSD 860 EVO 1TB              | 3         | 0.56%   |
| Samsung SSD 850 EVO 250GB            | 3         | 0.56%   |
| Kingston SUV500MS120G 120GB          | 3         | 0.56%   |
| Kingston SA400S37240G 240GB          | 3         | 0.56%   |
| Intel SSDSC2KB240G8 240GB            | 3         | 0.56%   |
| Innodisk DEMSR- 16GB mSATA 3ME3      | 3         | 0.56%   |
| GOODRAM SSDPR-CX400-256-G2 256GB     | 3         | 0.56%   |
| GOODRAM SSDPR-CX400-256 256GB        | 3         | 0.56%   |
| GOODRAM SSDPR-CX400-128 128GB        | 3         | 0.56%   |
| GOODRAM SSDPR-CL100-120-G3 120GB     | 3         | 0.56%   |
| GOODRAM SSDPR-CL100-120-G2 120GB     | 3         | 0.56%   |
| Apacer AS340 240GB                   | 3         | 0.56%   |
| A-DATA SU900 256GB                   | 3         | 0.56%   |
| A-DATA SU800 256GB                   | 3         | 0.56%   |
| WDC WDS500G2B0B-00YS70 500GB         | 2         | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 0.37%   |
| WDC WD20SDZW-11JJ8S0 2TB             | 2         | 0.37%   |
| WDC WD20NMVW-59EDZS7 2TB             | 2         | 0.37%   |
| WDC WD20EARS-00MVWB0 2TB             | 2         | 0.37%   |
| WDC WD10JPLX-00MBPT0 1TB             | 2         | 0.37%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB | 2         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate                            | 57        | 112    | 35.85%  |
| WDC                                | 52        | 112    | 32.7%   |
| Samsung Electronics                | 15        | 23     | 9.43%   |
| Toshiba                            | 13        | 31     | 8.18%   |
| Hitachi                            | 9         | 9      | 5.66%   |
| HGST                               | 4         | 6      | 2.52%   |
| NVMe                               | 3         | 4      | 1.89%   |
| Hewlett-Packard                    | 3         | 3      | 1.89%   |
| SSDPR-CX                           | 1         | 1      | 0.63%   |
| Product:              USB DISK 2.0 | 1         | 1      | 0.63%   |
| Apple                              | 1         | 1      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 37        | 74     | 13.75%  |
| GOODRAM             | 30        | 47     | 11.15%  |
| SanDisk             | 28        | 38     | 10.41%  |
| Kingston            | 18        | 20     | 6.69%   |
| A-DATA Technology   | 16        | 22     | 5.95%   |
| WDC                 | 13        | 26     | 4.83%   |
| SPCC                | 13        | 20     | 4.83%   |
| Crucial             | 11        | 21     | 4.09%   |
| Apacer              | 9         | 16     | 3.35%   |
| Transcend           | 8         | 14     | 2.97%   |
| Intel               | 8         | 12     | 2.97%   |
| China               | 7         | 10     | 2.6%    |
| Innodisk            | 6         | 8      | 2.23%   |
| Hoodisk             | 6         | 13     | 2.23%   |
| SK hynix            | 5         | 5      | 1.86%   |
| Plextor             | 5         | 5      | 1.86%   |
| OCZ                 | 4         | 4      | 1.49%   |
| Micron Technology   | 4         | 10     | 1.49%   |
| LITEONIT            | 4         | 6      | 1.49%   |
| Gigabyte Technology | 4         | 5      | 1.49%   |
| PNY                 | 3         | 6      | 1.12%   |
| Patriot             | 3         | 3      | 1.12%   |
| LITEON              | 3         | 3      | 1.12%   |
| Kston               | 3         | 3      | 1.12%   |
| Hewlett-Packard     | 3         | 3      | 1.12%   |
| Corsair             | 3         | 6      | 1.12%   |
| NVMe                | 2         | 2      | 0.74%   |
| Intenso             | 2         | 3      | 0.74%   |
| Apple               | 2         | 2      | 0.74%   |
| Toshiba             | 1         | 1      | 0.37%   |
| Team                | 1         | 1      | 0.37%   |
| Silicon Power       | 1         | 1      | 0.37%   |
| Phison              | 1         | 1      | 0.37%   |
| Lexar               | 1         | 1      | 0.37%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.37%   |
| FORESEE             | 1         | 1      | 0.37%   |
| Biostar             | 1         | 1      | 0.37%   |
| Advantech           | 1         | 1      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 237       | 416    | 55.5%   |
| HDD  | 129       | 303    | 30.21%  |
| NVMe | 61        | 90     | 14.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 322       | 719    | 84.07%  |
| NVMe | 61        | 90     | 15.93%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 265       | 461    | 70.11%  |
| 0.51-1.0   | 66        | 127    | 17.46%  |
| 1.01-2.0   | 25        | 71     | 6.61%   |
| 3.01-4.0   | 11        | 28     | 2.91%   |
| 2.01-3.0   | 6         | 19     | 1.59%   |
| 4.01-10.0  | 4         | 11     | 1.06%   |
| 10.01-20.0 | 1         | 2      | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 182       | 39.57%  |
| 251-500        | 69        | 15%     |
| 1-20           | 60        | 13.04%  |
| 51-100         | 57        | 12.39%  |
| 21-50          | 39        | 8.48%   |
| 501-1000       | 38        | 8.26%   |
| More than 3000 | 6         | 1.3%    |
| 1001-2000      | 4         | 0.87%   |
| Unknown        | 3         | 0.65%   |
| 2001-3000      | 2         | 0.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 400       | 87.72%  |
| 21-50          | 23        | 5.04%   |
| 51-100         | 12        | 2.63%   |
| 101-250        | 10        | 2.19%   |
| 251-500        | 4         | 0.88%   |
| Unknown        | 3         | 0.66%   |
| More than 3000 | 2         | 0.44%   |
| 1001-2000      | 2         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST1000DM003-1CH162 1TB  | 3         | 3      | 4.55%   |
| WDC WD5000LPLX-22ZNTT0 500GB    | 2         | 2      | 3.03%   |
| Toshiba MQ04ABF100 1TB          | 2         | 2      | 3.03%   |
| Seagate ST96812AS 64GB          | 2         | 5      | 3.03%   |
| Apacer 16GB SATA Flash Drive    | 2         | 3      | 3.03%   |
| WDC WD7500BPKT-00PK4T0 752GB    | 1         | 1      | 1.52%   |
| WDC WD360ADFD-00NLR1 37GB       | 1         | 1      | 1.52%   |
| WDC WD3200BEKT-22PVMT0 320GB    | 1         | 1      | 1.52%   |
| WDC WD3200AAVS-00ZTB0 320GB     | 1         | 1      | 1.52%   |
| WDC WD2500AAKX-753CA0 250GB     | 1         | 1      | 1.52%   |
| WDC WD2500AAKX-083CA1 250GB     | 1         | 2      | 1.52%   |
| WDC WD20NPVX-00EA4T0 2TB        | 1         | 2      | 1.52%   |
| WDC WD20EZRX-00D8PB0 2TB        | 1         | 1      | 1.52%   |
| WDC WD20EURS-63S48Y0 2TB        | 1         | 1      | 1.52%   |
| WDC WD20EARS-00MVWB0 2TB        | 1         | 1      | 1.52%   |
| WDC WD1600BEVE-00UYT0 160GB     | 1         | 1      | 1.52%   |
| WDC WD1600AAJS-40H3A0 160GB     | 1         | 1      | 1.52%   |
| WDC WD1200BEVS-07LAT0 120GB     | 1         | 1      | 1.52%   |
| WDC WD10EZEX-75M2NA0 1TB        | 1         | 1      | 1.52%   |
| WDC WD10EZEX-08M2NA0 1TB        | 1         | 1      | 1.52%   |
| WDC WD10EARS-003BB1 1TB         | 1         | 1      | 1.52%   |
| Toshiba THNSNK512GVN8 512GB     | 1         | 1      | 1.52%   |
| Toshiba MK3261GSYN 320GB        | 1         | 1      | 1.52%   |
| Toshiba MK1252GSX 120GB         | 1         | 1      | 1.52%   |
| SPCC Solid State Disk 256GB     | 1         | 1      | 1.52%   |
| SPCC Solid State Disk 240GB     | 1         | 1      | 1.52%   |
| SK hynix SC308 SATA 256GB       | 1         | 1      | 1.52%   |
| SK hynix SC210 mSATA 256GB      | 1         | 1      | 1.52%   |
| SK hynix SC210 mSATA 128GB      | 1         | 1      | 1.52%   |
| Seagate ST9500420AS 500GB       | 1         | 2      | 1.52%   |
| Seagate ST9250410AS 250GB       | 1         | 1      | 1.52%   |
| Seagate ST9160821AS 160GB       | 1         | 1      | 1.52%   |
| Seagate ST9160412AS 160GB       | 1         | 1      | 1.52%   |
| Seagate ST500LM000-1EJ162 500GB | 1         | 1      | 1.52%   |
| Seagate ST500DM002-1BD142 500GB | 1         | 1      | 1.52%   |
| Seagate ST3250310AS 250GB       | 1         | 1      | 1.52%   |
| Seagate ST32000542AS 2TB        | 1         | 2      | 1.52%   |
| Seagate ST2000LM015-2E8174 2TB  | 1         | 2      | 1.52%   |
| Seagate ST2000DL003-9VT166 2TB  | 1         | 1      | 1.52%   |
| Seagate ST1000NM0033-9ZM173 1TB | 1         | 2      | 1.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 20     | 26.15%  |
| Seagate             | 17        | 24     | 26.15%  |
| Toshiba             | 5         | 5      | 7.69%   |
| Hitachi             | 4         | 4      | 6.15%   |
| SK hynix            | 3         | 3      | 4.62%   |
| Samsung Electronics | 3         | 3      | 4.62%   |
| Micron Technology   | 3         | 3      | 4.62%   |
| Kingston            | 3         | 3      | 4.62%   |
| SPCC                | 2         | 2      | 3.08%   |
| Crucial             | 2         | 3      | 3.08%   |
| Apacer              | 2         | 3      | 3.08%   |
| SanDisk             | 1         | 5      | 1.54%   |
| Plextor             | 1         | 1      | 1.54%   |
| Intel               | 1         | 1      | 1.54%   |
| A-DATA Technology   | 1         | 1      | 1.54%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 20     | 38.64%  |
| Seagate             | 17        | 24     | 38.64%  |
| Toshiba             | 4         | 4      | 9.09%   |
| Hitachi             | 4         | 4      | 9.09%   |
| Samsung Electronics | 2         | 2      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 54     | 65.57%  |
| SSD  | 21        | 27     | 34.43%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB        | 1         | 1      | 33.33%  |
| Vaseky V900-120G                | 1         | 1      | 33.33%  |
| SanDisk SD9SN8W-256G-1006 256GB | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Vaseky  | 1         | 1      | 33.33%  |
| SanDisk | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 325       | 708    | 81.05%  |
| Malfunc  | 60        | 81     | 14.96%  |
| Detected | 13        | 17     | 3.24%   |
| Failed   | 3         | 3      | 0.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 308       | 57.79%  |
| AMD                            | 72        | 13.51%  |
| Broadcom / LSI                 | 34        | 6.38%   |
| Samsung Electronics            | 25        | 4.69%   |
| SanDisk                        | 12        | 2.25%   |
| Silicon Motion                 | 8         | 1.5%    |
| Phison Electronics             | 7         | 1.31%   |
| ASMedia Technology             | 6         | 1.13%   |
| SK hynix                       | 5         | 0.94%   |
| MAXIO Technology (Hangzhou)    | 5         | 0.94%   |
| Marvell Technology Group       | 5         | 0.94%   |
| Hewlett-Packard                | 5         | 0.94%   |
| ADATA Technology               | 5         | 0.94%   |
| Shenzhen Longsys Electronics   | 4         | 0.75%   |
| JMicron Technology             | 4         | 0.75%   |
| Transcend                      | 3         | 0.56%   |
| KIOXIA                         | 3         | 0.56%   |
| Kingston Technology Company    | 3         | 0.56%   |
| VIA Technologies               | 2         | 0.38%   |
| Realtek Semiconductor          | 2         | 0.38%   |
| Nvidia                         | 2         | 0.38%   |
| Lite-On Technology             | 2         | 0.38%   |
| Toshiba                        | 1         | 0.19%   |
| Solid State Storage Technology | 1         | 0.19%   |
| O2 Micro                       | 1         | 0.19%   |
| Micron/Crucial Technology      | 1         | 0.19%   |
| Micron Technology              | 1         | 0.19%   |
| Integrated Technology Express  | 1         | 0.19%   |
| Hosin Global Electronics       | 1         | 0.19%   |
| Chelsio Communications         | 1         | 0.19%   |
| Biwin Storage Technology       | 1         | 0.19%   |
| Apple                          | 1         | 0.19%   |
| Adaptec                        | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 50        | 8.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 30        | 5.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21        | 3.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19        | 3.23%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                          | 18        | 3.06%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 17        | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14        | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 14        | 2.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 12        | 2.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 12        | 2.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 12        | 2.04%   |
| Intel Alder Lake-N SATA AHCI Controller                                                 | 11        | 1.87%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11        | 1.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 10        | 1.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9         | 1.53%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 9         | 1.53%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 9         | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 9         | 1.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 1.36%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 8         | 1.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 7         | 1.19%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 1.19%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 6         | 1.02%   |
| Intel SATA Controller [RAID mode]                                                       | 6         | 1.02%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 6         | 1.02%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6         | 1.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6         | 1.02%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 5         | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 0.85%   |
| Intel Atom Processor C3000 Series SATA Controller 1                                     | 5         | 0.85%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5         | 0.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 0.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 5         | 0.85%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5         | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4         | 0.68%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 0.68%   |
| Intel Atom Processor C3000 Series SATA Controller 0                                     | 4         | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 344       | 65.4%   |
| NVMe | 87        | 16.54%  |
| RAID | 46        | 8.75%   |
| IDE  | 42        | 7.98%   |
| SAS  | 4         | 0.76%   |
| SCSI | 3         | 0.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 348       | 79.09%  |
| AMD     | 82        | 18.64%  |
| ARM     | 7         | 1.59%   |
| VIA     | 1         | 0.23%   |
| PowerPC | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz      | 14        | 3.15%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 13        | 2.92%   |
| Intel N100                               | 12        | 2.7%    |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 10        | 2.25%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 9         | 2.02%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 8         | 1.8%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 7         | 1.57%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 7         | 1.57%   |
| Intel Celeron N5105 @ 2.00GHz            | 6         | 1.35%   |
| Intel Celeron N4100 CPU @ 1.10GHz        | 6         | 1.35%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 5         | 1.12%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 5         | 1.12%   |
| AMD G-T56N Processor                     | 5         | 1.12%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 4         | 0.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz       | 4         | 0.9%    |
| Intel Core i3-8300T CPU @ 3.20GHz        | 4         | 0.9%    |
| Intel Core i3-6100 CPU @ 3.70GHz         | 4         | 0.9%    |
| Intel Core 2 Duo                         | 4         | 0.9%    |
| Intel Celeron CPU J3455 @ 1.50GHz        | 4         | 0.9%    |
| Intel Atom CPU D2500 @ 1.86GHz           | 4         | 0.9%    |
| AMD GX-412TC SOC                         | 4         | 0.9%    |
| Intel Xeon CPU E3-1270 V2 @ 3.50GHz      | 3         | 0.67%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 3         | 0.67%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 3         | 0.67%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 3         | 0.67%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 3         | 0.67%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 3         | 0.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 3         | 0.67%   |
| Intel Core i3-4005U CPU @ 1.70GHz        | 3         | 0.67%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 3         | 0.67%   |
| Intel Atom CPU C3758R @ 2.40GHz          | 3         | 0.67%   |
| ARM Cortex-A72 r0p3                      | 3         | 0.67%   |
| ARM Cortex-A55 r2p0                      | 3         | 0.67%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 3         | 0.67%   |
| AMD Phenom II X4 965 Processor           | 3         | 0.67%   |
| Intel Xeon CPU X5660 @ 2.80GHz           | 2         | 0.45%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 2         | 0.45%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz      | 2         | 0.45%   |
| Intel Xeon CPU E3-1260L v5 @ 2.90GHz     | 2         | 0.45%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz   | 2         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 74        | 16.63%  |
| Intel Celeron           | 58        | 13.03%  |
| Intel Xeon              | 51        | 11.46%  |
| Intel Core i7           | 40        | 8.99%   |
| Intel Core i3           | 35        | 7.87%   |
| Other                   | 30        | 6.74%   |
| AMD GX                  | 28        | 6.29%   |
| Intel Pentium           | 16        | 3.6%    |
| Intel Core 2 Duo        | 15        | 3.37%   |
| Intel Atom              | 14        | 3.15%   |
| Intel Pentium Silver    | 12        | 2.7%    |
| ARM Cortex              | 7         | 1.57%   |
| AMD Ryzen 7             | 7         | 1.57%   |
| AMD Ryzen 3             | 7         | 1.57%   |
| AMD G                   | 7         | 1.57%   |
| AMD Ryzen 5             | 6         | 1.35%   |
| Intel Pentium Dual-Core | 3         | 0.67%   |
| Intel Core 2 Quad       | 3         | 0.67%   |
| AMD Ryzen Embedded      | 3         | 0.67%   |
| AMD Ryzen 9             | 3         | 0.67%   |
| AMD Phenom II X4        | 3         | 0.67%   |
| Intel Pentium Gold      | 2         | 0.45%   |
| Intel Core 2            | 2         | 0.45%   |
| AMD Ryzen 5 PRO         | 2         | 0.45%   |
| AMD Ryzen 3 PRO         | 2         | 0.45%   |
| AMD EPYC                | 2         | 0.45%   |
| AMD E                   | 2         | 0.45%   |
| AMD Athlon              | 2         | 0.45%   |
| Intel Xeon Gold         | 1         | 0.22%   |
| Intel Pentium M         | 1         | 0.22%   |
| Intel Genuine           | 1         | 0.22%   |
| Intel Celeron M         | 1         | 0.22%   |
| AMD Ryzen 7 PRO         | 1         | 0.22%   |
| AMD Phenom II X6        | 1         | 0.22%   |
| AMD FX                  | 1         | 0.22%   |
| AMD Athlon 64 X2        | 1         | 0.22%   |
| AMD A4                  | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 215       | 48.31%  |
| 2       | 117       | 26.29%  |
| 8       | 25        | 5.62%   |
| Unknown | 25        | 5.62%   |
| 16      | 22        | 4.94%   |
| 6       | 15        | 3.37%   |
| 12      | 13        | 2.92%   |
| 1       | 6         | 1.35%   |
| 24      | 2         | 0.45%   |
| 20      | 2         | 0.45%   |
| 32      | 1         | 0.22%   |
| 18      | 1         | 0.22%   |
| 14      | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 394       | 89.75%  |
| 2       | 28        | 6.38%   |
| Unknown | 17        | 3.87%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 245       | 55.43%  |
| 2       | 168       | 38.01%  |
| Unknown | 29        | 6.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| IvyBridge     | 46        | 10.34%  |
| Unknown       | 46        | 10.34%  |
| KabyLake      | 45        | 10.11%  |
| Haswell       | 44        | 9.89%   |
| Goldmont plus | 30        | 6.74%   |
| Skylake       | 29        | 6.52%   |
| SandyBridge   | 28        | 6.29%   |
| Jaguar        | 25        | 5.62%   |
| Penryn        | 23        | 5.17%   |
| Silvermont    | 15        | 3.37%   |
| Goldmont      | 13        | 2.92%   |
| Broadwell     | 12        | 2.7%    |
| Zen           | 10        | 2.25%   |
| Zen 2         | 9         | 2.02%   |
| Bobcat        | 9         | 2.02%   |
| Westmere      | 7         | 1.57%   |
| Bonnell       | 7         | 1.57%   |
| Zen+          | 6         | 1.35%   |
| Zen 3         | 6         | 1.35%   |
| Nehalem       | 6         | 1.35%   |
| Puma          | 5         | 1.12%   |
| Core          | 5         | 1.12%   |
| K10           | 4         | 0.9%    |
| TigerLake     | 3         | 0.67%   |
| Steamroller   | 3         | 0.67%   |
| CometLake     | 3         | 0.67%   |
| P6            | 2         | 0.45%   |
| Piledriver    | 1         | 0.22%   |
| NetBurst      | 1         | 0.22%   |
| K8 Hammer     | 1         | 0.22%   |
| Excavator     | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 259       | 56.92%  |
| AMD                                          | 89        | 19.56%  |
| Nvidia                                       | 49        | 10.77%  |
| Matrox Electronics Systems                   | 41        | 9.01%   |
| ASPEED Technology                            | 13        | 2.86%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.44%   |
| VIA Technologies                             | 2         | 0.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Matrox Electronics Systems G200eR2                                                       | 23        | 5%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 19        | 4.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 4.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 18        | 3.91%   |
| Intel HD Graphics 530                                                                    | 15        | 3.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 3.26%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 14        | 3.04%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 13        | 2.83%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 13        | 2.83%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 11        | 2.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 2.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 2.17%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 9         | 1.96%   |
| Intel JasperLake [UHD Graphics]                                                          | 9         | 1.96%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 9         | 1.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9         | 1.96%   |
| Intel HD Graphics 630                                                                    | 8         | 1.74%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 8         | 1.74%   |
| Intel HD Graphics 500                                                                    | 7         | 1.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 1.52%   |
| Intel HD Graphics 620                                                                    | 6         | 1.3%    |
| AMD Wrestler [Radeon HD 6320]                                                            | 6         | 1.3%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.09%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 1.09%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 5         | 1.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.09%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.87%   |
| Matrox Electronics Systems MGA G200EH                                                    | 4         | 0.87%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 4         | 0.87%   |
| Intel UHD Graphics 620                                                                   | 4         | 0.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 0.87%   |
| Intel HD Graphics 510                                                                    | 4         | 0.87%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 0.87%   |
| AMD ES1000                                                                               | 4         | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 215       | 48.42%  |
| 1 x AMD         | 82        | 18.47%  |
| 1 x Matrox      | 41        | 9.23%   |
| 1 x Nvidia      | 25        | 5.63%   |
| Intel + Nvidia  | 22        | 4.95%   |
| Other           | 18        | 4.05%   |
| 2 x Intel       | 16        | 3.6%    |
| 1 x ASPEED      | 11        | 2.48%   |
| Intel + AMD     | 6         | 1.35%   |
| 1 x XGI         | 2         | 0.45%   |
| 1 x VIA         | 2         | 0.45%   |
| Nvidia + ASPEED | 2         | 0.45%   |
| AMD + Nvidia    | 1         | 0.23%   |
| AMD + ASPEED    | 1         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 394       | 89.55%  |
| Unknown     | 24        | 5.45%   |
| Proprietary | 22        | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 398       | 90.25%  |
| 1.01-2.0   | 10        | 2.27%   |
| 7.01-8.0   | 9         | 2.04%   |
| 3.01-4.0   | 9         | 2.04%   |
| 0.51-1.0   | 7         | 1.59%   |
| 0.01-0.5   | 6         | 1.36%   |
| 5.01-6.0   | 1         | 0.23%   |
| 8.01-16.0  | 1         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 20        | 12.74%  |
| LG Display              | 20        | 12.74%  |
| Dell                    | 11        | 7.01%   |
| Lenovo                  | 10        | 6.37%   |
| Iiyama                  | 10        | 6.37%   |
| BOE                     | 10        | 6.37%   |
| AU Optronics            | 9         | 5.73%   |
| Chimei Innolux          | 8         | 5.1%    |
| Acer                    | 6         | 3.82%   |
| NEC Computers           | 5         | 3.18%   |
| Goldstar                | 5         | 3.18%   |
| Philips                 | 4         | 2.55%   |
| Chi Mei Optoelectronics | 4         | 2.55%   |
| Apple                   | 4         | 2.55%   |
| AOC                     | 4         | 2.55%   |
| InfoVision              | 3         | 1.91%   |
| Hewlett-Packard         | 3         | 1.91%   |
| BenQ                    | 3         | 1.91%   |
| Sharp                   | 2         | 1.27%   |
| Idek Iiyama             | 2         | 1.27%   |
| Vestel Elektronik       | 1         | 0.64%   |
| Toshiba                 | 1         | 0.64%   |
| RTK                     | 1         | 0.64%   |
| PANDA                   | 1         | 0.64%   |
| Medion                  | 1         | 0.64%   |
| KTC                     | 1         | 0.64%   |
| JDI                     | 1         | 0.64%   |
| Huion                   | 1         | 0.64%   |
| HPN                     | 1         | 0.64%   |
| Gateway                 | 1         | 0.64%   |
| Eizo                    | 1         | 0.64%   |
| CSO                     | 1         | 0.64%   |
| BOE Technology Group    | 1         | 0.64%   |
| Unknown                 | 1         | 0.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 6         | 3.77%   |
| Iiyama PL2775HD IVM6604 1920x1080 600x340mm 27.2-inch                    | 6         | 3.77%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch              | 3         | 1.89%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch     | 2         | 1.26%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch        | 2         | 1.26%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 2         | 1.26%   |
| Dell U2515H DELD070 2560x1440 550x310mm 24.9-inch                        | 2         | 1.26%   |
| Dell P2214H DELA099 1920x1080 480x270mm 21.7-inch                        | 2         | 1.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 1.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 1.26%   |
| Apple Color LCD APPA02E 2880x1800 330x210mm 15.4-inch                    | 2         | 1.26%   |
| AOC Q27G2WG4 AOC2702 2560x1440 600x340mm 27.2-inch                       | 2         | 1.26%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch       | 1         | 0.63%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                        | 1         | 0.63%   |
| Sharp LCD Monitor SHP1451 1920x1080 280x160mm 12.7-inch                  | 1         | 0.63%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch                  | 1         | 0.63%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch        | 1         | 0.63%   |
| Samsung Electronics T24D391 SAM0B73 1920x1080 520x290mm 23.4-inch        | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0523 1920x1080 480x270mm 21.7-inch     | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch     | 1         | 0.63%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 630x360mm 28.6-inch        | 1         | 0.63%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 530x300mm 24.0-inch      | 1         | 0.63%   |
| Samsung Electronics LF27T370F SAM711E 1920x1080 600x340mm 27.2-inch      | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4163 3456x2160 290x180mm 13.4-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC324A 1366x768 290x170mm 13.2-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                        | 1         | 0.63%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                        | 1         | 0.63%   |
| RTK FHD RTK0039 1920x1080 300x190mm 14.0-inch                            | 1         | 0.63%   |
| Philips PHL 275S1 PHL094B 2560x1440 600x340mm 27.2-inch                  | 1         | 0.63%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 1         | 0.63%   |
| Philips LCD Monitor PHLC01A 1680x1050 470x300mm 22.0-inch                | 1         | 0.63%   |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                        | 1         | 0.63%   |
| PANDA LCD Monitor NCP006E 1920x1080 340x190mm 15.3-inch                  | 1         | 0.63%   |
| NEC Computers LCD73V NEC66C2 1280x1024 340x270mm 17.1-inch               | 1         | 0.63%   |
| NEC Computers LCD4020 NEC66EA 1920x540 890x500mm 40.2-inch               | 1         | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 62        | 41.89%  |
| 1366x768 (WXGA)    | 31        | 20.95%  |
| 3840x2160 (4K)     | 8         | 5.41%   |
| 1280x800 (WXGA)    | 8         | 5.41%   |
| 2560x1440 (QHD)    | 7         | 4.73%   |
| 1680x1050 (WSXGA+) | 5         | 3.38%   |
| 1280x1024 (SXGA)   | 5         | 3.38%   |
| 1600x900 (HD+)     | 4         | 2.7%    |
| 1920x1200 (WUXGA)  | 3         | 2.03%   |
| 5760x2160          | 2         | 1.35%   |
| 2880x1800          | 2         | 1.35%   |
| 1920x540           | 2         | 1.35%   |
| 1440x900 (WXGA+)   | 2         | 1.35%   |
| Unknown            | 2         | 1.35%   |
| 3840x2400          | 1         | 0.68%   |
| 3456x2160          | 1         | 0.68%   |
| 3200x1800 (QHD+)   | 1         | 0.68%   |
| 2560x1080          | 1         | 0.68%   |
| 1024x768 (XGA)     | 1         | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 31        | 20.39%  |
| 13      | 23        | 15.13%  |
| 27      | 17        | 11.18%  |
| 12      | 17        | 11.18%  |
| 23      | 11        | 7.24%   |
| 24      | 10        | 6.58%   |
| 21      | 8         | 5.26%   |
| Unknown | 7         | 4.61%   |
| 17      | 5         | 3.29%   |
| 19      | 4         | 2.63%   |
| 14      | 4         | 2.63%   |
| 22      | 3         | 1.97%   |
| 18      | 3         | 1.97%   |
| 42      | 2         | 1.32%   |
| 31      | 2         | 1.32%   |
| 28      | 2         | 1.32%   |
| 50      | 1         | 0.66%   |
| 40      | 1         | 0.66%   |
| 20      | 1         | 0.66%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 50        | 33.56%  |
| 501-600     | 35        | 23.49%  |
| 201-300     | 26        | 17.45%  |
| 401-500     | 16        | 10.74%  |
| 351-400     | 7         | 4.7%    |
| Unknown     | 7         | 4.7%    |
| 601-700     | 4         | 2.68%   |
| 901-1000    | 2         | 1.34%   |
| 801-900     | 1         | 0.67%   |
| 1001-1500   | 1         | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 102       | 72.86%  |
| 16/10   | 23        | 16.43%  |
| Unknown | 6         | 4.29%   |
| 5/4     | 5         | 3.57%   |
| 3/2     | 2         | 1.43%   |
| 4/3     | 1         | 0.71%   |
| 21/9    | 1         | 0.71%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 25        | 16.67%  |
| 81-90          | 22        | 14.67%  |
| 91-100         | 20        | 13.33%  |
| 61-70          | 17        | 11.33%  |
| 301-350        | 17        | 11.33%  |
| 101-110        | 12        | 8%      |
| Unknown        | 7         | 4.67%   |
| 251-300        | 6         | 4%      |
| 151-200        | 6         | 4%      |
| 71-80          | 4         | 2.67%   |
| 141-150        | 4         | 2.67%   |
| 351-500        | 3         | 2%      |
| 501-1000       | 3         | 2%      |
| 121-130        | 2         | 1.33%   |
| More than 1000 | 1         | 0.67%   |
| 131-140        | 1         | 0.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 50        | 34.01%  |
| 121-160       | 46        | 31.29%  |
| 101-120       | 30        | 20.41%  |
| 161-240       | 9         | 6.12%   |
| Unknown       | 7         | 4.76%   |
| More than 240 | 3         | 2.04%   |
| 1-50          | 2         | 1.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 288       | 64.86%  |
| 1     | 137       | 30.86%  |
| 2     | 16        | 3.6%    |
| 3     | 3         | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 292       | 44.72%  |
| Realtek Semiconductor             | 198       | 30.32%  |
| Broadcom                          | 68        | 10.41%  |
| Qualcomm Atheros                  | 37        | 5.67%   |
| Qualcomm Atheros Communications   | 6         | 0.92%   |
| TP-Link                           | 4         | 0.61%   |
| AMD                               | 4         | 0.61%   |
| Huawei Technologies               | 3         | 0.46%   |
| Emulex                            | 3         | 0.46%   |
| Dell                              | 3         | 0.46%   |
| Xiaomi                            | 2         | 0.31%   |
| Ralink Technology                 | 2         | 0.31%   |
| Mellanox Technologies             | 2         | 0.31%   |
| Marvell Technology Group          | 2         | 0.31%   |
| IMC Networks                      | 2         | 0.31%   |
| IBM                               | 2         | 0.31%   |
| Chelsio Communications            | 2         | 0.31%   |
| ZyXEL Communications              | 1         | 0.15%   |
| VIA Technologies                  | 1         | 0.15%   |
| Van Ooijen Technische Informatica | 1         | 0.15%   |
| U-Blox                            | 1         | 0.15%   |
| Sierra Wireless                   | 1         | 0.15%   |
| Seeed Technology                  | 1         | 0.15%   |
| Samsung Electronics               | 1         | 0.15%   |
| Ralink                            | 1         | 0.15%   |
| QLogic                            | 1         | 0.15%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.15%   |
| Nvidia                            | 1         | 0.15%   |
| Nuvoton                           | 1         | 0.15%   |
| NetGear                           | 1         | 0.15%   |
| MediaTek                          | 1         | 0.15%   |
| Ericsson Business Mobile Networks | 1         | 0.15%   |
| D-Link System                     | 1         | 0.15%   |
| Atheros                           | 1         | 0.15%   |
| ASUSTek Computer                  | 1         | 0.15%   |
| Apple                             | 1         | 0.15%   |
| American Megatrends               | 1         | 0.15%   |
| 3Com                              | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 173       | 21.68%  |
| Intel I211 Gigabit Network Connection                                         | 32        | 4.01%   |
| Intel I350 Gigabit Network Connection                                         | 30        | 3.76%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 24        | 3.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 22        | 2.76%   |
| Intel I210 Gigabit Network Connection                                         | 21        | 2.63%   |
| Intel Ethernet Controller I226-V                                              | 21        | 2.63%   |
| Intel Ethernet Controller I225-V                                              | 16        | 2.01%   |
| Intel 82574L Gigabit Network Connection                                       | 14        | 1.75%   |
| Intel Ethernet Connection I217-LM                                             | 12        | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 12        | 1.5%    |
| Intel Ethernet Connection (2) I219-V                                          | 10        | 1.25%   |
| Intel 82567LM Gigabit Network Connection                                      | 10        | 1.25%   |
| Intel Wireless 8265 / 8275                                                    | 9         | 1.13%   |
| Intel Ethernet Connection (7) I219-V                                          | 9         | 1.13%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9         | 1.13%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 9         | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 8         | 1%      |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 8         | 1%      |
| Intel 82580 Gigabit Network Connection                                        | 8         | 1%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 7         | 0.88%   |
| Intel Wireless 8260                                                           | 7         | 0.88%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 7         | 0.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6         | 0.75%   |
| Intel Ultimate N WiFi Link 5300                                               | 6         | 0.75%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 6         | 0.75%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 6         | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5         | 0.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 5         | 0.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 5         | 0.63%   |
| Intel Wireless 7265                                                           | 5         | 0.63%   |
| Intel Wireless 7260                                                           | 5         | 0.63%   |
| Intel Wireless 3165                                                           | 5         | 0.63%   |
| Intel Wi-Fi 6 AX200                                                           | 5         | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 4         | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4         | 0.5%    |
| Qualcomm Atheros AR9271 802.11n                                               | 4         | 0.5%    |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 4         | 0.5%    |
| Intel Ethernet Connection I219-LM                                             | 4         | 0.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 4         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 108       | 52.68%  |
| Qualcomm Atheros                | 31        | 15.12%  |
| Realtek Semiconductor           | 25        | 12.2%   |
| Broadcom                        | 18        | 8.78%   |
| Qualcomm Atheros Communications | 6         | 2.93%   |
| TP-Link                         | 4         | 1.95%   |
| Ralink Technology               | 2         | 0.98%   |
| IMC Networks                    | 2         | 0.98%   |
| Dell                            | 2         | 0.98%   |
| ZyXEL Communications            | 1         | 0.49%   |
| Ralink                          | 1         | 0.49%   |
| NetGear                         | 1         | 0.49%   |
| MediaTek                        | 1         | 0.49%   |
| D-Link System                   | 1         | 0.49%   |
| Atheros                         | 1         | 0.49%   |
| ASUSTek Computer                | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 12        | 5.83%   |
| Intel Wireless 8265 / 8275                                                    | 9         | 4.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 8         | 3.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 7         | 3.4%    |
| Intel Wireless 8260                                                           | 7         | 3.4%    |
| Intel Gemini Lake PCH CNVi WiFi                                               | 7         | 3.4%    |
| Intel Ultimate N WiFi Link 5300                                               | 6         | 2.91%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 6         | 2.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5         | 2.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 5         | 2.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 5         | 2.43%   |
| Intel Wireless 7265                                                           | 5         | 2.43%   |
| Intel Wireless 7260                                                           | 5         | 2.43%   |
| Intel Wireless 3165                                                           | 5         | 2.43%   |
| Intel Wi-Fi 6 AX200                                                           | 5         | 2.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 4         | 1.94%   |
| Qualcomm Atheros AR9271 802.11n                                               | 4         | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 4         | 1.94%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 3         | 1.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 3         | 1.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 3         | 1.46%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 3         | 1.46%   |
| Intel Wi-Fi 6 AX201                                                           | 3         | 1.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3         | 1.46%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 3         | 1.46%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2         | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2         | 0.97%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 2         | 0.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.97%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 0.97%   |
| Ralink RT5370 Wireless Adapter                                                | 2         | 0.97%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 2         | 0.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 0.97%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 2         | 0.97%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 0.97%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 2         | 0.97%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 2         | 0.97%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 2         | 0.97%   |
| Intel Centrino Advanced-N 6235                                                | 2         | 0.97%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 244       | 47.94%  |
| Realtek Semiconductor         | 184       | 36.15%  |
| Broadcom                      | 52        | 10.22%  |
| Qualcomm Atheros              | 7         | 1.38%   |
| AMD                           | 4         | 0.79%   |
| Xiaomi                        | 2         | 0.39%   |
| Marvell Technology Group      | 2         | 0.39%   |
| IBM                           | 2         | 0.39%   |
| Emulex                        | 2         | 0.39%   |
| VIA Technologies              | 1         | 0.2%    |
| Samsung Electronics           | 1         | 0.2%    |
| QLogic                        | 1         | 0.2%    |
| OnePlus Technology (Shenzhen) | 1         | 0.2%    |
| Nvidia                        | 1         | 0.2%    |
| Huawei Technologies           | 1         | 0.2%    |
| Chelsio Communications        | 1         | 0.2%    |
| Apple                         | 1         | 0.2%    |
| American Megatrends           | 1         | 0.2%    |
| 3Com                          | 1         | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 173       | 29.98%  |
| Intel I211 Gigabit Network Connection                                         | 32        | 5.55%   |
| Intel I350 Gigabit Network Connection                                         | 30        | 5.2%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 24        | 4.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 22        | 3.81%   |
| Intel I210 Gigabit Network Connection                                         | 21        | 3.64%   |
| Intel Ethernet Controller I226-V                                              | 21        | 3.64%   |
| Intel Ethernet Controller I225-V                                              | 16        | 2.77%   |
| Intel 82574L Gigabit Network Connection                                       | 14        | 2.43%   |
| Intel Ethernet Connection I217-LM                                             | 12        | 2.08%   |
| Intel Ethernet Connection (2) I219-V                                          | 10        | 1.73%   |
| Intel 82567LM Gigabit Network Connection                                      | 10        | 1.73%   |
| Intel Ethernet Connection (7) I219-V                                          | 9         | 1.56%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9         | 1.56%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 9         | 1.56%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 8         | 1.39%   |
| Intel 82580 Gigabit Network Connection                                        | 8         | 1.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6         | 1.04%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 6         | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4         | 0.69%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 4         | 0.69%   |
| Intel Ethernet Connection I219-LM                                             | 4         | 0.69%   |
| Intel 82579V Gigabit Network Connection                                       | 4         | 0.69%   |
| Intel 82576 Gigabit Network Connection                                        | 4         | 0.69%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 4         | 0.69%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                               | 4         | 0.69%   |
| AMD XGMAC 10GbE Controller                                                    | 4         | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 0.52%   |
| Intel Ethernet Connection I218-LM                                             | 3         | 0.52%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3         | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                                         | 3         | 0.52%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 0.52%   |
| Intel 82576NS Gigabit Network Connection                                      | 3         | 0.52%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3         | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3         | 0.52%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 2         | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2         | 0.35%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                         | 2         | 0.35%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 2         | 0.35%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 2         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 415       | 66.94%  |
| WiFi     | 190       | 30.65%  |
| Unknown  | 9         | 1.45%   |
| Modem    | 6         | 0.97%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 367       | 80.66%  |
| WiFi     | 88        | 19.34%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 149       | 33.26%  |
| 1     | 84        | 18.75%  |
| 3     | 66        | 14.73%  |
| 4     | 62        | 13.84%  |
| 6     | 32        | 7.14%   |
| 5     | 32        | 7.14%   |
| 0     | 10        | 2.23%   |
| 8     | 4         | 0.89%   |
| 14    | 3         | 0.67%   |
| 9     | 3         | 0.67%   |
| 7     | 2         | 0.45%   |
| 10    | 1         | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 431       | 97.51%  |
| Yes  | 11        | 2.49%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 56%     |
| Broadcom                        | 11        | 8.8%    |
| Realtek Semiconductor           | 10        | 8%      |
| IMC Networks                    | 5         | 4%      |
| Cambridge Silicon Radio         | 5         | 4%      |
| Qualcomm Atheros Communications | 4         | 3.2%    |
| Foxconn / Hon Hai               | 4         | 3.2%    |
| ASUSTek Computer                | 4         | 3.2%    |
| Apple                           | 4         | 3.2%    |
| Lite-On Technology              | 2         | 1.6%    |
| Dell                            | 2         | 1.6%    |
| TP-Link                         | 1         | 0.8%    |
| Qcom                            | 1         | 0.8%    |
| MediaTek                        | 1         | 0.8%    |
| Hewlett-Packard                 | 1         | 0.8%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 26        | 20.8%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 17        | 13.6%   |
| Intel AX201 Bluetooth                                    | 9         | 7.2%    |
| Realtek Bluetooth Adapter                                | 6         | 4.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 5         | 4%      |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 5         | 4%      |
| Intel AX200 Bluetooth                                    | 4         | 3.2%    |
| Intel Wireless-AC 3168 Bluetooth                         | 3         | 2.4%    |
| Intel Centrino Bluetooth Wireless Transceiver            | 3         | 2.4%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 3         | 2.4%    |
| Intel AX210 Bluetooth                                    | 3         | 2.4%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 3         | 2.4%    |
| Apple Bluetooth Host Controller                          | 3         | 2.4%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter        | 2         | 1.6%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth            | 2         | 1.6%    |
| ASUS USB-BT500                                           | 2         | 1.6%    |
| TP-Link Bluetooth 5.0 USB Adapter                        | 1         | 0.8%    |
| Realtek Wireless Bluetooth Adapter                       | 1         | 0.8%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 1         | 0.8%    |
| Realtek  Bluetooth 4.2 Adapter                           | 1         | 0.8%    |
| Realtek Bluetooth 4.2 Adapter                            | 1         | 0.8%    |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                   | 1         | 0.8%    |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device     | 1         | 0.8%    |
| Qualcomm Atheros AR9462 Bluetooth                        | 1         | 0.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 1         | 0.8%    |
| Qcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device       | 1         | 0.8%    |
| MediaTek RZ608 Bluetooth Adapter                         | 1         | 0.8%    |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS              | 1         | 0.8%    |
| Lite-On Bluetooth USB Module                             | 1         | 0.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1         | 0.8%    |
| Intel AX211 Bluetooth                                    | 1         | 0.8%    |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip     | 1         | 0.8%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS         | 1         | 0.8%    |
| IMC Networks Asus Integrated Bluetooth module [AR3011]   | 1         | 0.8%    |
| HP Atheros AR9285 Malbec Bluetooth Adapter               | 1         | 0.8%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 0.8%    |
| Foxconn / Hon Hai Bluetooth USB Module                   | 1         | 0.8%    |
| Dell DW375 Bluetooth Module                              | 1         | 0.8%    |
| Dell Dell Wireless 380 Bluetooth 4.0 Module              | 1         | 0.8%    |
| Broadcom BCM43142A0 Bluetooth Module                     | 1         | 0.8%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 265       | 67.26%  |
| AMD                                          | 82        | 20.81%  |
| Nvidia                                       | 30        | 7.61%   |
| C-Media Electronics                          | 4         | 1.02%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.51%   |
| VIA Technologies                             | 2         | 0.51%   |
| Logitech                                     | 2         | 0.51%   |
| Creative Labs                                | 2         | 0.51%   |
| ROCCAT                                       | 1         | 0.25%   |
| Realtek Semiconductor                        | 1         | 0.25%   |
| Nektar                                       | 1         | 0.25%   |
| Kingston Technology                          | 1         | 0.25%   |
| Creative Technology                          | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 27        | 5.5%    |
| AMD Kabini HDMI/DP Audio                                                                          | 26        | 5.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 5.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 22        | 4.48%   |
| AMD FCH Azalia Controller                                                                         | 20        | 4.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 19        | 3.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 3.87%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 19        | 3.87%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 3.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 3.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 15        | 3.05%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 13        | 2.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 2.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 2.24%   |
| Intel 200 Series PCH HD Audio                                                                     | 10        | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 1.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 1.83%   |
| Intel Jasper Lake HD Audio                                                                        | 9         | 1.83%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 1.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 1.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9         | 1.83%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 1.63%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 1.43%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 1.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 1.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.22%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 1.22%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 6         | 1.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 1.22%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.02%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 5         | 1.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.61%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 98        | 21.4%   |
| SK hynix            | 73        | 15.94%  |
| Kingston            | 62        | 13.54%  |
| Unknown             | 44        | 9.61%   |
| Micron Technology   | 40        | 8.73%   |
| GOODRAM             | 28        | 6.11%   |
| Crucial             | 19        | 4.15%   |
| G.Skill             | 14        | 3.06%   |
| Unknown             | 13        | 2.84%   |
| Ramaxel Technology  | 9         | 1.97%   |
| Corsair             | 9         | 1.97%   |
| A-DATA Technology   | 6         | 1.31%   |
| Toshiba             | 5         | 1.09%   |
| Patriot             | 5         | 1.09%   |
| Transcend           | 4         | 0.87%   |
| Nanya Technology    | 4         | 0.87%   |
| Wilk                | 3         | 0.66%   |
| Elpida              | 3         | 0.66%   |
| Unknown (ABCD)      | 2         | 0.44%   |
| Lexar Co Limited    | 2         | 0.44%   |
| Hewlett-Packard     | 2         | 0.44%   |
| Apacer              | 2         | 0.44%   |
| Unknown (07FB)      | 1         | 0.22%   |
| Team                | 1         | 0.22%   |
| SHARETRONIC         | 1         | 0.22%   |
| Qimonda             | 1         | 0.22%   |
| PUSKILL             | 1         | 0.22%   |
| Kimtigo             | 1         | 0.22%   |
| Innodisk            | 1         | 0.22%   |
| GeIL                | 1         | 0.22%   |
| Cors                | 1         | 0.22%   |
| ATP                 | 1         | 0.22%   |
| A-DA                | 1         | 0.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M393B1G70QH0-YK0 8GB DIMM DDR3 1600MT/s            | 16        | 3.28%   |
| Unknown                                                        | 13        | 2.66%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s          | 7         | 1.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 6         | 1.23%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s         | 6         | 1.23%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 5         | 1.02%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 5         | 1.02%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s              | 5         | 1.02%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 4         | 0.82%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                      | 4         | 0.82%   |
| Toshiba RAM KKN2NM-MIE 4GB SODIMM DDR4 2666MT/s                | 4         | 0.82%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 4         | 0.82%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 3         | 0.61%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 3         | 0.61%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 0.61%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 3         | 0.61%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 3         | 0.61%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s          | 3         | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 0.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 0.61%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 3         | 0.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 3         | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 3         | 0.61%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s      | 3         | 0.61%   |
| GOODRAM RAM GR1600S364L11/8G 8GB SODIMM DDR3 1600MT/s          | 3         | 0.61%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 2         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 2         | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                       | 2         | 0.41%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 2         | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 2         | 0.41%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 2         | 0.41%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                   | 2         | 0.41%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                   | 2         | 0.41%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 2         | 0.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.41%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.41%   |
| SK hynix RAM HMT351R7BFR8A-H9 4GB DIMM DDR3 1333MT/s           | 2         | 0.41%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s         | 2         | 0.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 0.41%   |
| SK hynix RAM HMA41GR7AFR8N-TF 8GB DIMM DDR4 2133MT/s           | 2         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 204       | 50.37%  |
| DDR4    | 151       | 37.28%  |
| DDR5    | 12        | 2.96%   |
| DDR2    | 9         | 2.22%   |
| Unknown | 8         | 1.98%   |
| LPDDR4  | 7         | 1.73%   |
| SDRAM   | 4         | 0.99%   |
| LPDDR3  | 3         | 0.74%   |
| DDR     | 3         | 0.74%   |
| LPDDR5  | 2         | 0.49%   |
| DRAM    | 2         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 204       | 50.5%   |
| DIMM         | 185       | 45.79%  |
| Row Of Chips | 9         | 2.23%   |
| RIMM         | 2         | 0.5%    |
| Unknown      | 2         | 0.5%    |
| FB-DIMM      | 1         | 0.25%   |
| Chip         | 1         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 165       | 38.02%  |
| 4096  | 143       | 32.95%  |
| 2048  | 59        | 13.59%  |
| 16384 | 46        | 10.6%   |
| 32768 | 10        | 2.3%    |
| 1024  | 9         | 2.07%   |
| 512   | 2         | 0.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 138       | 32.17%  |
| 2400    | 56        | 13.05%  |
| 1333    | 48        | 11.19%  |
| 2667    | 37        | 8.62%   |
| 3200    | 36        | 8.39%   |
| 2133    | 22        | 5.13%   |
| 800     | 15        | 3.5%    |
| 1334    | 9         | 2.1%    |
| 4800    | 8         | 1.86%   |
| 2666    | 7         | 1.63%   |
| 1867    | 7         | 1.63%   |
| 667     | 7         | 1.63%   |
| 1067    | 6         | 1.4%    |
| 1066    | 6         | 1.4%    |
| Unknown | 6         | 1.4%    |
| 5600    | 4         | 0.93%   |
| 1866    | 4         | 0.93%   |
| 6400    | 2         | 0.47%   |
| 4267    | 2         | 0.47%   |
| 5200    | 1         | 0.23%   |
| 4000    | 1         | 0.23%   |
| 3600    | 1         | 0.23%   |
| 3333    | 1         | 0.23%   |
| 3000    | 1         | 0.23%   |
| 2933    | 1         | 0.23%   |
| 2048    | 1         | 0.23%   |
| 533     | 1         | 0.23%   |
| 400     | 1         | 0.23%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 31        | 39.74%  |
| Microdia                               | 9         | 11.54%  |
| Realtek Semiconductor                  | 8         | 10.26%  |
| Bison Electronics                      | 6         | 7.69%   |
| Logitech                               | 3         | 3.85%   |
| IMC Networks                           | 3         | 3.85%   |
| Syntek                                 | 2         | 2.56%   |
| Sunplus Innovation Technology          | 2         | 2.56%   |
| Ricoh                                  | 2         | 2.56%   |
| Luxvisions Innotech Limited            | 2         | 2.56%   |
| Lite-On Technology                     | 2         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.56%   |
| Suyin                                  | 1         | 1.28%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.28%   |
| Quanta                                 | 1         | 1.28%   |
| Hewlett-Packard                        | 1         | 1.28%   |
| DigiTech                               | 1         | 1.28%   |
| Apple                                  | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                     | 6         | 7.59%   |
| Chicony Realtek DMFT RGB                                      | 4         | 5.06%   |
| Realtek Lenovo EasyCamera                                     | 3         | 3.8%    |
| Realtek Integrated_Webcam_HD                                  | 3         | 3.8%    |
| Microdia Integrated Webcam                                    | 3         | 3.8%    |
| Logitech HD Pro Webcam C920                                   | 3         | 3.8%    |
| Chicony Integrated Camera [ThinkPad]                          | 3         | 3.8%    |
| Chicony Integrated Camera (1280x720@30)                       | 3         | 3.8%    |
| Microdia Integrated_Webcam_HD                                 | 2         | 2.53%   |
| Lite-On Integrated Camera                                     | 2         | 2.53%   |
| IMC Networks Integrated Camera                                | 2         | 2.53%   |
| Bison Lenovo EasyCamera                                       | 2         | 2.53%   |
| Bison Integrated Camera                                       | 2         | 2.53%   |
| Syntek Lenovo EasyCamera                                      | 1         | 1.27%   |
| Syntek Integrated Camera                                      | 1         | 1.27%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                      | 1         | 1.27%   |
| Sunplus Integrated_Webcam_HD                                  | 1         | 1.27%   |
| Sunplus Integrated_Webcam_FHD                                 | 1         | 1.27%   |
| Shenzhen Kingcome Optoelectronic NexiGo HelloCam N930W Camera | 1         | 1.27%   |
| Ricoh Integrated Webcam                                       | 1         | 1.27%   |
| Ricoh HD Webcam                                               | 1         | 1.27%   |
| Realtek HD WebCam                                             | 1         | 1.27%   |
| Realtek Front Camera                                          | 1         | 1.27%   |
| Quanta Realtek DMFT RGB                                       | 1         | 1.27%   |
| Microdia PC-LM1E                                              | 1         | 1.27%   |
| Microdia Laptop_Integrated_Webcam_HD                          | 1         | 1.27%   |
| Microdia Integrated HD Webcam                                 | 1         | 1.27%   |
| Microdia Dell Integrated HD Webcam                            | 1         | 1.27%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera           | 1         | 1.27%   |
| Luxvisions Innotech Limited HP True Vision FHD Camera         | 1         | 1.27%   |
| IMC Networks EasyCamera                                       | 1         | 1.27%   |
| HP Premium Starter Webcam                                     | 1         | 1.27%   |
| DigiTech WebCam SCB-0350M                                     | 1         | 1.27%   |
| Chicony USB2.0 VGA UVC WebCam                                 | 1         | 1.27%   |
| Chicony USB2.0 HD UVC WebCam                                  | 1         | 1.27%   |
| Chicony ThinkPad T490 Webcam                                  | 1         | 1.27%   |
| Chicony Realtek DMFT IR                                       | 1         | 1.27%   |
| Chicony Lenovo Integrated Camera (0.3MP)                      | 1         | 1.27%   |
| Chicony Lenovo EasyCamera                                     | 1         | 1.27%   |
| Chicony HP Wide Vision HD Camera                              | 1         | 1.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 31.82%  |
| Validity Sensors           | 4         | 18.18%  |
| AuthenTec                  | 4         | 18.18%  |
| Broadcom                   | 3         | 13.64%  |
| Shenzhen Goodix Technology | 2         | 9.09%   |
| STMicroelectronics         | 1         | 4.55%   |
| Elan Microelectronics      | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 4         | 18.18%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 13.64%  |
| AuthenTec AES2810                                                            | 3         | 13.64%  |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 9.09%   |
| Validity Sensors Fingerprint scanner                                         | 2         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 9.09%   |
| Synaptics WBDI                                                               | 1         | 4.55%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 4.55%   |
| Elan Fingerprint Sensor                                                      | 1         | 4.55%   |
| AuthenTec AES2660                                                            | 1         | 4.55%   |

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
| 1     | 198       | 44.1%   |
| 0     | 122       | 27.17%  |
| 2     | 94        | 20.94%  |
| 3     | 24        | 5.35%   |
| 4     | 6         | 1.34%   |
| 5     | 3         | 0.67%   |
| 6     | 2         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 284       | 63.53%  |
| Bluetooth                | 44        | 9.84%   |
| Net/wireless             | 39        | 8.72%   |
| Card reader              | 25        | 5.59%   |
| Fingerprint reader       | 21        | 4.7%    |
| Graphics card            | 10        | 2.24%   |
| Firewire controller      | 7         | 1.57%   |
| Sound                    | 6         | 1.34%   |
| Network                  | 5         | 1.12%   |
| Net/ethernet             | 3         | 0.67%   |
| Storage/nvme             | 1         | 0.22%   |
| Storage                  | 1         | 0.22%   |
| Modem                    | 1         | 0.22%   |

