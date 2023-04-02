BSD in France - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in France.

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

Total: 334

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [9696e7d17f](https://bsd-hardware.info/?probe=9696e7d17f) | Mar 29, 2023 |
| Acer          | Revo 70                     | [50d93bea69](https://bsd-hardware.info/?probe=50d93bea69) | Mar 23, 2023 |
| MSI           | H81I                        | [4983a6a077](https://bsd-hardware.info/?probe=4983a6a077) | Mar 22, 2023 |
| HP            | 805A                        | [d90c74af40](https://bsd-hardware.info/?probe=d90c74af40) | Mar 21, 2023 |
| MSI           | H81I                        | [a1981bf557](https://bsd-hardware.info/?probe=a1981bf557) | Mar 19, 2023 |
| Unknown       | Unknown                     | [03cf8c47dc](https://bsd-hardware.info/?probe=03cf8c47dc) | Mar 17, 2023 |
| YENTEK        | R250                        | [fc42406b39](https://bsd-hardware.info/?probe=fc42406b39) | Mar 15, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [864a4017cb](https://bsd-hardware.info/?probe=864a4017cb) | Mar 15, 2023 |
| Unknown       | J3160-4L                    | [bc21ae472e](https://bsd-hardware.info/?probe=bc21ae472e) | Mar 13, 2023 |
| Gigabyte      | G31M-S2L                    | [d210b12607](https://bsd-hardware.info/?probe=d210b12607) | Mar 13, 2023 |
| MW            | GMLK-2_5G4L                 | [ad6f854637](https://bsd-hardware.info/?probe=ad6f854637) | Mar 12, 2023 |
| Dell          | 07WP95 A02                  | [f45a92348a](https://bsd-hardware.info/?probe=f45a92348a) | Mar 12, 2023 |
| HP            | 3398                        | [20bcb682d8](https://bsd-hardware.info/?probe=20bcb682d8) | Mar 11, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3548f4efa2](https://bsd-hardware.info/?probe=3548f4efa2) | Mar 11, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | [98fe8cc428](https://bsd-hardware.info/?probe=98fe8cc428) | Mar 09, 2023 |
| Intel         | CRESCENTBAY                 | [3c5f826544](https://bsd-hardware.info/?probe=3c5f826544) | Mar 07, 2023 |
| ASRock        | X300M-STX                   | [2a6207fb45](https://bsd-hardware.info/?probe=2a6207fb45) | Mar 07, 2023 |
| MW            | GMLK-2_5G4L                 | [8e9e9d3ce2](https://bsd-hardware.info/?probe=8e9e9d3ce2) | Mar 05, 2023 |
| Unknown       | Unknown                     | [8c93a7e552](https://bsd-hardware.info/?probe=8c93a7e552) | Mar 04, 2023 |
| Intel         | D510MO AAE76523-403         | [0da634580f](https://bsd-hardware.info/?probe=0da634580f) | Mar 03, 2023 |
| Unknown       | Unknown                     | [85fdc49ec4](https://bsd-hardware.info/?probe=85fdc49ec4) | Mar 03, 2023 |
| HP            | 1496                        | [f2acf09862](https://bsd-hardware.info/?probe=f2acf09862) | Mar 02, 2023 |
| HP            | 212B                        | [185934706d](https://bsd-hardware.info/?probe=185934706d) | Mar 02, 2023 |
| ASUSTek       | PRIME A320I-K               | [9fa1054078](https://bsd-hardware.info/?probe=9fa1054078) | Mar 02, 2023 |
| HP            | 8055                        | [faadcd3e41](https://bsd-hardware.info/?probe=faadcd3e41) | Feb 26, 2023 |
| ASRock        | X300M-STX                   | [fb908ee344](https://bsd-hardware.info/?probe=fb908ee344) | Feb 23, 2023 |
| Techvision    | TVI7309X B0                 | [3e1b050969](https://bsd-hardware.info/?probe=3e1b050969) | Feb 22, 2023 |
| Techvision    | TVI7309X B0                 | [d23b2cfe5a](https://bsd-hardware.info/?probe=d23b2cfe5a) | Feb 17, 2023 |
| HP            | 198E                        | [1f9a7e4f9b](https://bsd-hardware.info/?probe=1f9a7e4f9b) | Feb 17, 2023 |
| Dell          | 04YP6J A02                  | [0f589ba9bf](https://bsd-hardware.info/?probe=0f589ba9bf) | Feb 16, 2023 |
| Dell          | 0782GW A00                  | [95a8784d4a](https://bsd-hardware.info/?probe=95a8784d4a) | Feb 16, 2023 |
| Dell          | OptiPlex 9020               | [0c8a5f8dfa](https://bsd-hardware.info/?probe=0c8a5f8dfa) | Feb 13, 2023 |
| Unknown       | J3160-4L                    | [4c4e675427](https://bsd-hardware.info/?probe=4c4e675427) | Feb 10, 2023 |
| ChangWang     | CW56-58                     | [e376971bd6](https://bsd-hardware.info/?probe=e376971bd6) | Feb 09, 2023 |
| HP            | 8350                        | [9ec1605295](https://bsd-hardware.info/?probe=9ec1605295) | Feb 04, 2023 |
| Unknown       | Unknown                     | [6096b00a0c](https://bsd-hardware.info/?probe=6096b00a0c) | Jan 29, 2023 |
| AMD           | Larne CRB                   | [8b9a301b47](https://bsd-hardware.info/?probe=8b9a301b47) | Jan 27, 2023 |
| Unknown       | Unknown                     | [d36217b166](https://bsd-hardware.info/?probe=d36217b166) | Jan 26, 2023 |
| ASUSTek       | PRIME A320I-K               | [0c75494953](https://bsd-hardware.info/?probe=0c75494953) | Jan 25, 2023 |
| Dell          | PowerEdge R710              | [720e99b25e](https://bsd-hardware.info/?probe=720e99b25e) | Jan 17, 2023 |
| Techvision    | TVI7309X B0                 | [7cbcb5b513](https://bsd-hardware.info/?probe=7cbcb5b513) | Jan 12, 2023 |
| Lenovo        | 3138                        | [14876c7561](https://bsd-hardware.info/?probe=14876c7561) | Jan 12, 2023 |
| Lenovo        | ThinkStation D20 415575G    | [0a15d989e3](https://bsd-hardware.info/?probe=0a15d989e3) | Jan 08, 2023 |
| Dell          | 08NPPY A00                  | [0d13116822](https://bsd-hardware.info/?probe=0d13116822) | Jan 06, 2023 |
| ASUSTek       | PRIME A320I-K               | [334575b738](https://bsd-hardware.info/?probe=334575b738) | Dec 31, 2022 |
| Protectli     | FW6 Ver                     | [41094c24b2](https://bsd-hardware.info/?probe=41094c24b2) | Dec 27, 2022 |
| Protectli     | FW6 Ver                     | [d62deb9883](https://bsd-hardware.info/?probe=d62deb9883) | Dec 26, 2022 |
| Intel         | Q3XXG4-P V1.0               | [33c59c687d](https://bsd-hardware.info/?probe=33c59c687d) | Dec 24, 2022 |
| ASUSTek       | X99-DELUXE                  | [abe21b9c9e](https://bsd-hardware.info/?probe=abe21b9c9e) | Dec 18, 2022 |
| MSI           | MS-98C8                     | [a6e45c8e5f](https://bsd-hardware.info/?probe=a6e45c8e5f) | Dec 17, 2022 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | [11d5b82cdd](https://bsd-hardware.info/?probe=11d5b82cdd) | Dec 17, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [342c99d07d](https://bsd-hardware.info/?probe=342c99d07d) | Dec 10, 2022 |
| Protectli     | FW4B Ver                    | [dbbdd023e9](https://bsd-hardware.info/?probe=dbbdd023e9) | Dec 08, 2022 |
| ASUSTek       | G11CD                       | [7bc1746333](https://bsd-hardware.info/?probe=7bc1746333) | Dec 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [c953c78309](https://bsd-hardware.info/?probe=c953c78309) | Dec 07, 2022 |
| ASUSTek       | PRIME B360M-K               | [90279b62b7](https://bsd-hardware.info/?probe=90279b62b7) | Dec 05, 2022 |
| Unknown       | Unknown                     | [54e89ef90b](https://bsd-hardware.info/?probe=54e89ef90b) | Dec 04, 2022 |
| Dell          | 0GXM1W A00                  | [9497657cb2](https://bsd-hardware.info/?probe=9497657cb2) | Dec 04, 2022 |
| Dell          | 08NPPY A00                  | [6a1a5865cb](https://bsd-hardware.info/?probe=6a1a5865cb) | Nov 30, 2022 |
| Supermicro    | X10SRG-F                    | [66b7819b2a](https://bsd-hardware.info/?probe=66b7819b2a) | Nov 27, 2022 |
| MW            | GMLK-2_5G4L                 | [787a2db2cd](https://bsd-hardware.info/?probe=787a2db2cd) | Nov 26, 2022 |
| HP            | 806A                        | [9567b6949c](https://bsd-hardware.info/?probe=9567b6949c) | Nov 11, 2022 |
| Unknown       | Unknown                     | [4adc5f7629](https://bsd-hardware.info/?probe=4adc5f7629) | Nov 09, 2022 |
| Unknown       | Unknown                     | [47efa8b4bc](https://bsd-hardware.info/?probe=47efa8b4bc) | Nov 06, 2022 |
| Intel         | CRESCENTBAY                 | [0312c464c4](https://bsd-hardware.info/?probe=0312c464c4) | Nov 05, 2022 |
| ASUSTek       | E35M1-I DELUXE              | [2fdf1c6db6](https://bsd-hardware.info/?probe=2fdf1c6db6) | Oct 18, 2022 |
| HP            | 260 G3 DM                   | [3ad5292d71](https://bsd-hardware.info/?probe=3ad5292d71) | Oct 13, 2022 |
| HP            | Compaq nw8440 (RND39ET)     | [55bef385e3](https://bsd-hardware.info/?probe=55bef385e3) | Oct 13, 2022 |
| Clevo         | R130T                       | [6f8a6bf77c](https://bsd-hardware.info/?probe=6f8a6bf77c) | Oct 10, 2022 |
| Soekris En... | net6501                     | [1cb23f6bda](https://bsd-hardware.info/?probe=1cb23f6bda) | Oct 08, 2022 |
| Soekris En... | net6501                     | [03ee772b1f](https://bsd-hardware.info/?probe=03ee772b1f) | Oct 08, 2022 |
| HP            | ProLiant MicroServer Gen... | [31ce3d5e46](https://bsd-hardware.info/?probe=31ce3d5e46) | Oct 07, 2022 |
| Intel         | CRESCENTBAY                 | [36fb81bec0](https://bsd-hardware.info/?probe=36fb81bec0) | Oct 07, 2022 |
| PC Engines    | apu1                        | [1a8ff34d31](https://bsd-hardware.info/?probe=1a8ff34d31) | Oct 06, 2022 |
| Unknown       | Unknown                     | [16f6784862](https://bsd-hardware.info/?probe=16f6784862) | Sep 27, 2022 |
| Dell          | 0T10XW A02                  | [b8db4655e5](https://bsd-hardware.info/?probe=b8db4655e5) | Sep 26, 2022 |
| Techvision    | TVI7309X B0                 | [ae535b0b49](https://bsd-hardware.info/?probe=ae535b0b49) | Sep 25, 2022 |
| HP            | ProLiant MicroServer Gen... | [8f4900d0e6](https://bsd-hardware.info/?probe=8f4900d0e6) | Sep 25, 2022 |
| HP            | ProLiant MicroServer Gen... | [59886931c5](https://bsd-hardware.info/?probe=59886931c5) | Sep 24, 2022 |
| Intel         | Q3XXG4-P V1.0               | [5029142d61](https://bsd-hardware.info/?probe=5029142d61) | Sep 22, 2022 |
| HP            | 21D0                        | [43fa46655e](https://bsd-hardware.info/?probe=43fa46655e) | Sep 21, 2022 |
| HP            | 21D0                        | [463e2563d7](https://bsd-hardware.info/?probe=463e2563d7) | Sep 19, 2022 |
| PC Engines    | APU2                        | [95ae240b55](https://bsd-hardware.info/?probe=95ae240b55) | Sep 13, 2022 |
| Unknown       | J3160-4L                    | [4db37ff154](https://bsd-hardware.info/?probe=4db37ff154) | Sep 07, 2022 |
| AMD           | Larne CRB                   | [787a51fa78](https://bsd-hardware.info/?probe=787a51fa78) | Sep 03, 2022 |
| ASUSTek       | H81M-A                      | [11ac5a7932](https://bsd-hardware.info/?probe=11ac5a7932) | Sep 02, 2022 |
| Dell          | 0T10XW A00                  | [d346cf971a](https://bsd-hardware.info/?probe=d346cf971a) | Aug 15, 2022 |
| Protectli     | FW6 Ver                     | [ab6603e750](https://bsd-hardware.info/?probe=ab6603e750) | Aug 13, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | [649021e20c](https://bsd-hardware.info/?probe=649021e20c) | Aug 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | [870dface68](https://bsd-hardware.info/?probe=870dface68) | Aug 11, 2022 |
| Unknown       | Unknown                     | [5e2f93a960](https://bsd-hardware.info/?probe=5e2f93a960) | Aug 06, 2022 |
| Unknown       | Unknown                     | [66fefba790](https://bsd-hardware.info/?probe=66fefba790) | Aug 06, 2022 |
| HP            | ProLiant MicroServer Gen... | [81441a97b2](https://bsd-hardware.info/?probe=81441a97b2) | Aug 06, 2022 |
| HP            | 3397                        | [6111a627d6](https://bsd-hardware.info/?probe=6111a627d6) | Aug 05, 2022 |
| AMD           | Larne CRB                   | [db094f95af](https://bsd-hardware.info/?probe=db094f95af) | Aug 04, 2022 |
| Unknown       | Unknown                     | [5ac2fc150b](https://bsd-hardware.info/?probe=5ac2fc150b) | Aug 02, 2022 |
| HP            | 3397                        | [dac75fec6e](https://bsd-hardware.info/?probe=dac75fec6e) | Jul 31, 2022 |
| Dell          | 05XGC8 A01                  | [0eaaa31106](https://bsd-hardware.info/?probe=0eaaa31106) | Jul 31, 2022 |
| Gigabyte      | GB-BSi3-1115G4              | [4cd0769d75](https://bsd-hardware.info/?probe=4cd0769d75) | Jul 30, 2022 |
| AMD           | Larne CRB                   | [794541e833](https://bsd-hardware.info/?probe=794541e833) | Jul 29, 2022 |
| MW            | GMLK-2_5G4L                 | [3fe3a46a7a](https://bsd-hardware.info/?probe=3fe3a46a7a) | Jul 21, 2022 |
| Intel         | Q3XXG4-P V1.0               | [bbca74a96f](https://bsd-hardware.info/?probe=bbca74a96f) | Jul 16, 2022 |
| Intel         | Q3XXG4-P V1.0               | [9e54e446ef](https://bsd-hardware.info/?probe=9e54e446ef) | Jul 14, 2022 |
| Intel         | S1200KP AAG34877-201        | [d43e397f02](https://bsd-hardware.info/?probe=d43e397f02) | Jul 10, 2022 |
| ASRock        | Z490M Pro4                  | [b57457834e](https://bsd-hardware.info/?probe=b57457834e) | Jul 04, 2022 |
| Intel         | Q3XXG4-P V1.0               | [ab2f42b567](https://bsd-hardware.info/?probe=ab2f42b567) | Jun 26, 2022 |
| Intel         | D945GCLF2 AAE46416-104      | [84f2afeff4](https://bsd-hardware.info/?probe=84f2afeff4) | Jun 21, 2022 |
| HP            | 86E9 A                      | [1d1ac2dd90](https://bsd-hardware.info/?probe=1d1ac2dd90) | Jun 16, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [4e0a906acb](https://bsd-hardware.info/?probe=4e0a906acb) | Jun 11, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | [776a4892d0](https://bsd-hardware.info/?probe=776a4892d0) | Jun 10, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | [9bacfc2b0e](https://bsd-hardware.info/?probe=9bacfc2b0e) | May 29, 2022 |
| Intel         | DH67BL AAG10189-213         | [e8d2744812](https://bsd-hardware.info/?probe=e8d2744812) | May 12, 2022 |
| ASRock        | A320M Pro4-F                | [f307756ddf](https://bsd-hardware.info/?probe=f307756ddf) | May 11, 2022 |
| Unknown       | Unknown                     | [6cf944b0ef](https://bsd-hardware.info/?probe=6cf944b0ef) | May 10, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cf58c679ef](https://bsd-hardware.info/?probe=cf58c679ef) | May 08, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [5f9e266167](https://bsd-hardware.info/?probe=5f9e266167) | May 04, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [7d4dd8ba29](https://bsd-hardware.info/?probe=7d4dd8ba29) | May 04, 2022 |
| Dell          | 0782GW A00                  | [3481513b0f](https://bsd-hardware.info/?probe=3481513b0f) | May 03, 2022 |
| ASUSTek       | AM1I-A                      | [8fce57c9e4](https://bsd-hardware.info/?probe=8fce57c9e4) | Apr 25, 2022 |
| ASUSTek       | P5KR                        | [cf745ca0da](https://bsd-hardware.info/?probe=cf745ca0da) | Apr 23, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [875d6b2da3](https://bsd-hardware.info/?probe=875d6b2da3) | Apr 22, 2022 |
| Intel         | Q3XXG4-P V1.0               | [a278852381](https://bsd-hardware.info/?probe=a278852381) | Apr 21, 2022 |
| Dell          | 06JWJY A01                  | [16f4cc5d53](https://bsd-hardware.info/?probe=16f4cc5d53) | Apr 20, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [ab8aea2f5c](https://bsd-hardware.info/?probe=ab8aea2f5c) | Apr 17, 2022 |
| Deciso        | Netboard A10                | [6e0b916230](https://bsd-hardware.info/?probe=6e0b916230) | Apr 16, 2022 |
| HP            | 86E9 A                      | [be43a8efde](https://bsd-hardware.info/?probe=be43a8efde) | Apr 14, 2022 |
| Unknown       | J3160-4L                    | [4b981630d7](https://bsd-hardware.info/?probe=4b981630d7) | Apr 13, 2022 |
| Dell          | 0T10XW A02                  | [06720f3c57](https://bsd-hardware.info/?probe=06720f3c57) | Apr 13, 2022 |
| Unknown       | Unknown                     | [e6ba291c2d](https://bsd-hardware.info/?probe=e6ba291c2d) | Apr 12, 2022 |
| Jetway        | 1.0                         | [ac2ab09363](https://bsd-hardware.info/?probe=ac2ab09363) | Apr 11, 2022 |
| Unknown       | Unknown                     | [4e208e9425](https://bsd-hardware.info/?probe=4e208e9425) | Apr 10, 2022 |
| ASUSTek       | P5G41T-M LX3                | [ded0d1a114](https://bsd-hardware.info/?probe=ded0d1a114) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX3                | [14a6449380](https://bsd-hardware.info/?probe=14a6449380) | Apr 09, 2022 |
| Unknown       | Unknown                     | [50833ab257](https://bsd-hardware.info/?probe=50833ab257) | Apr 07, 2022 |
| Intel         | Q3XXG4-P V1.0               | [e44ebcb340](https://bsd-hardware.info/?probe=e44ebcb340) | Apr 06, 2022 |
| ASRock        | H110M-ITX                   | [946c8fd467](https://bsd-hardware.info/?probe=946c8fd467) | Apr 04, 2022 |
| PC Engines    | APU2                        | [5eb2e04d11](https://bsd-hardware.info/?probe=5eb2e04d11) | Apr 02, 2022 |
| Dell          | 0782GW A00                  | [c83fab9193](https://bsd-hardware.info/?probe=c83fab9193) | Apr 01, 2022 |
| HP            | ProLiant MicroServer Gen... | [7a991e2f31](https://bsd-hardware.info/?probe=7a991e2f31) | Mar 24, 2022 |
| Dell          | 0782GW A00                  | [acb99d63ce](https://bsd-hardware.info/?probe=acb99d63ce) | Mar 23, 2022 |
| Unknown       | Unknown                     | [05a81cb5d5](https://bsd-hardware.info/?probe=05a81cb5d5) | Mar 22, 2022 |
| Protectli     | FW6 Ver                     | [483cf54bfc](https://bsd-hardware.info/?probe=483cf54bfc) | Mar 21, 2022 |
| ASUSTek       | PRIME B550M-A               | [d0946bc53f](https://bsd-hardware.info/?probe=d0946bc53f) | Mar 21, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [d2ecb6259c](https://bsd-hardware.info/?probe=d2ecb6259c) | Mar 20, 2022 |
| Protectli     | FW6 Ver                     | [a4a1c8e5ca](https://bsd-hardware.info/?probe=a4a1c8e5ca) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | [b23ab09f52](https://bsd-hardware.info/?probe=b23ab09f52) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | [545e5ebfc9](https://bsd-hardware.info/?probe=545e5ebfc9) | Mar 18, 2022 |
| HP            | ProLiant MicroServer Gen... | [b652261bda](https://bsd-hardware.info/?probe=b652261bda) | Mar 14, 2022 |
| HP            | ProLiant MicroServer Gen... | [0a2a94839d](https://bsd-hardware.info/?probe=0a2a94839d) | Mar 13, 2022 |
| CNCTION-IA... | Unknown                     | [0051c86e4c](https://bsd-hardware.info/?probe=0051c86e4c) | Mar 07, 2022 |
| AAEON         | UP-CHT01 V0.4               | [9aaa7c7a32](https://bsd-hardware.info/?probe=9aaa7c7a32) | Mar 05, 2022 |
| Protectli     | VP2410                      | [1f650fc994](https://bsd-hardware.info/?probe=1f650fc994) | Mar 05, 2022 |
| PC Engines    | apu1                        | [177dc1fbc8](https://bsd-hardware.info/?probe=177dc1fbc8) | Mar 03, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [43bfceb19d](https://bsd-hardware.info/?probe=43bfceb19d) | Mar 02, 2022 |
| Dell          | 0782GW A00                  | [7b19f71ce1](https://bsd-hardware.info/?probe=7b19f71ce1) | Feb 26, 2022 |
| PC Engines    | apu1                        | [d904aa7790](https://bsd-hardware.info/?probe=d904aa7790) | Feb 24, 2022 |
| Intel         | CARLOW                      | [d46b68cc28](https://bsd-hardware.info/?probe=d46b68cc28) | Feb 23, 2022 |
| HP            | 8169                        | [f449b4cd6c](https://bsd-hardware.info/?probe=f449b4cd6c) | Feb 23, 2022 |
| Intel         | CARLOW                      | [b64bf97293](https://bsd-hardware.info/?probe=b64bf97293) | Feb 19, 2022 |
| Dell          | 0782GW A00                  | [ef5cc6be72](https://bsd-hardware.info/?probe=ef5cc6be72) | Feb 17, 2022 |
| Supermicro    | X11SDV-8C-TP8F              | [18576ef86c](https://bsd-hardware.info/?probe=18576ef86c) | Feb 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | [fbc24f90e5](https://bsd-hardware.info/?probe=fbc24f90e5) | Feb 17, 2022 |
| MSI           | MS-7253                     | [c4e971ea82](https://bsd-hardware.info/?probe=c4e971ea82) | Feb 16, 2022 |
| Intel         | Q3XXG4-P V1.0               | [df529a84b9](https://bsd-hardware.info/?probe=df529a84b9) | Feb 16, 2022 |
| AMD           | X64                         | [e5a9ff1138](https://bsd-hardware.info/?probe=e5a9ff1138) | Feb 15, 2022 |
| Supermicro    | X11SDV-8C-TP8F              | [09a6920a4f](https://bsd-hardware.info/?probe=09a6920a4f) | Feb 12, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [91b1ec3b93](https://bsd-hardware.info/?probe=91b1ec3b93) | Feb 06, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [2accc42e21](https://bsd-hardware.info/?probe=2accc42e21) | Feb 06, 2022 |
| Dell          | 0T10XW A02                  | [9213769810](https://bsd-hardware.info/?probe=9213769810) | Feb 05, 2022 |
| Intel         | SKYBAY                      | [95c3231a3a](https://bsd-hardware.info/?probe=95c3231a3a) | Feb 03, 2022 |
| MSI           | MS-9A45 0A                  | [cfbfdf0e55](https://bsd-hardware.info/?probe=cfbfdf0e55) | Jan 31, 2022 |
| Unknown       | J3160-4L                    | [9dc53740a9](https://bsd-hardware.info/?probe=9dc53740a9) | Jan 29, 2022 |
| AMD           | Larne CRB                   | [c6a85da1d5](https://bsd-hardware.info/?probe=c6a85da1d5) | Jan 28, 2022 |
| Dell          | 0PC5F7 A03                  | [7a5d842d33](https://bsd-hardware.info/?probe=7a5d842d33) | Jan 27, 2022 |
| Intel         | SKYBAY                      | [f1c7ee0712](https://bsd-hardware.info/?probe=f1c7ee0712) | Jan 26, 2022 |
| ASRock        | H110M-ITX                   | [5c58d01f2d](https://bsd-hardware.info/?probe=5c58d01f2d) | Jan 25, 2022 |
| RUNING        | B75M INTEL H3V              | [9a060df0a2](https://bsd-hardware.info/?probe=9a060df0a2) | Jan 23, 2022 |
| AMD           | Larne CRB                   | [6c37b91111](https://bsd-hardware.info/?probe=6c37b91111) | Jan 22, 2022 |
| Dell          | 0T10XW A02                  | [b01e6eb706](https://bsd-hardware.info/?probe=b01e6eb706) | Jan 22, 2022 |
| ASRock        | B365M Pro4                  | [8449bd20c1](https://bsd-hardware.info/?probe=8449bd20c1) | Jan 18, 2022 |
| ASUSTek       | PRIME X570-P                | [3dead218e1](https://bsd-hardware.info/?probe=3dead218e1) | Jan 16, 2022 |
| Unknown       | Unknown                     | [6baaab27fd](https://bsd-hardware.info/?probe=6baaab27fd) | Jan 15, 2022 |
| MSI           | MS-98C8                     | [0102557f05](https://bsd-hardware.info/?probe=0102557f05) | Jan 15, 2022 |
| PC Engines    | APU2                        | [7062b84459](https://bsd-hardware.info/?probe=7062b84459) | Jan 14, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [6aeb9adadb](https://bsd-hardware.info/?probe=6aeb9adadb) | Dec 31, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [8c3181ee8d](https://bsd-hardware.info/?probe=8c3181ee8d) | Dec 29, 2021 |
| Intel         | Q3XXG4-P V1.0               | [cdb5578df8](https://bsd-hardware.info/?probe=cdb5578df8) | Dec 27, 2021 |
| Gigabyte      | X58A-UD5                    | [62b94dd372](https://bsd-hardware.info/?probe=62b94dd372) | Dec 21, 2021 |
| ASRock        | Z590M-ITX/ax                | [124ac672b0](https://bsd-hardware.info/?probe=124ac672b0) | Dec 20, 2021 |
| Unknown       | Unknown                     | [225298bcd6](https://bsd-hardware.info/?probe=225298bcd6) | Dec 12, 2021 |
| RUNING        | B75M INTEL H3V              | [61312aa506](https://bsd-hardware.info/?probe=61312aa506) | Nov 30, 2021 |
| Dell          | VEP-4600-V930 034R2CA03     | [313d1b7032](https://bsd-hardware.info/?probe=313d1b7032) | Nov 25, 2021 |
| Gigabyte      | MZBSWBP-00                  | [9e7a72d920](https://bsd-hardware.info/?probe=9e7a72d920) | Nov 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | [16206960c4](https://bsd-hardware.info/?probe=16206960c4) | Nov 24, 2021 |
| HP            | 3031h                       | [056352a663](https://bsd-hardware.info/?probe=056352a663) | Nov 21, 2021 |
| RUNING        | B75M INTEL H3V              | [5cfcc8c5f8](https://bsd-hardware.info/?probe=5cfcc8c5f8) | Nov 13, 2021 |
| HP            | 3031h                       | [d63bbcfceb](https://bsd-hardware.info/?probe=d63bbcfceb) | Oct 31, 2021 |
| HP            | 3031h                       | [c5e39a5e6d](https://bsd-hardware.info/?probe=c5e39a5e6d) | Oct 31, 2021 |
| MSI           | MS-9A45 0A                  | [e2db09bacb](https://bsd-hardware.info/?probe=e2db09bacb) | Oct 30, 2021 |
| ASRockRack    | C3558D4I-4L                 | [dfba84ce5a](https://bsd-hardware.info/?probe=dfba84ce5a) | Oct 29, 2021 |
| Intel         | Q3XXG4-P V1.0               | [e2167afc3b](https://bsd-hardware.info/?probe=e2167afc3b) | Oct 25, 2021 |
| Intel         | Q3XXG4-P V1.0               | [3f5b148e23](https://bsd-hardware.info/?probe=3f5b148e23) | Oct 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | [6f019f05b6](https://bsd-hardware.info/?probe=6f019f05b6) | Oct 20, 2021 |
| PC Engines    | APU2                        | [4b8fb7992f](https://bsd-hardware.info/?probe=4b8fb7992f) | Oct 16, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [e53866a5d9](https://bsd-hardware.info/?probe=e53866a5d9) | Oct 11, 2021 |
| ASUSTek       | P9X79                       | [be9d90602d](https://bsd-hardware.info/?probe=be9d90602d) | Oct 11, 2021 |
| Unknown       | Unknown                     | [2fd62acb45](https://bsd-hardware.info/?probe=2fd62acb45) | Oct 10, 2021 |
| Lenovo        | 3138                        | [8b5cf892d0](https://bsd-hardware.info/?probe=8b5cf892d0) | Oct 04, 2021 |
| ASUSTek       | F2A85-M                     | [5b7623f03b](https://bsd-hardware.info/?probe=5b7623f03b) | Sep 21, 2021 |
| Unknown       | Unknown                     | [1b8ce81945](https://bsd-hardware.info/?probe=1b8ce81945) | Sep 19, 2021 |
| ASRock        | B460M Pro4                  | [cfc7818691](https://bsd-hardware.info/?probe=cfc7818691) | Sep 10, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [d5750a95a4](https://bsd-hardware.info/?probe=d5750a95a4) | Sep 08, 2021 |
| Packard Be... | imedia S2110A               | [d62a38660c](https://bsd-hardware.info/?probe=d62a38660c) | Sep 08, 2021 |
| ASUSTek       | P8Z68-V LX                  | [29cfd33c5e](https://bsd-hardware.info/?probe=29cfd33c5e) | Sep 06, 2021 |
| ASRockRack    | X470D4U                     | [827c50f77b](https://bsd-hardware.info/?probe=827c50f77b) | Aug 28, 2021 |
| Dell          | 0G3HR7 A00                  | [7f75f30b75](https://bsd-hardware.info/?probe=7f75f30b75) | Aug 27, 2021 |
| PC Engines    | APU2                        | [0a35da2af7](https://bsd-hardware.info/?probe=0a35da2af7) | Aug 24, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3e088c942b](https://bsd-hardware.info/?probe=3e088c942b) | Aug 22, 2021 |
| Unknown       | Unknown                     | [1dd499d54c](https://bsd-hardware.info/?probe=1dd499d54c) | Aug 12, 2021 |
| Dell          | 0XCR8D A03                  | [11526a150b](https://bsd-hardware.info/?probe=11526a150b) | Aug 10, 2021 |
| Shuttle       | FS61                        | [b1fbaa8a6b](https://bsd-hardware.info/?probe=b1fbaa8a6b) | Aug 09, 2021 |
| ASUSTek       | H81M-A                      | [bb65c30be3](https://bsd-hardware.info/?probe=bb65c30be3) | Aug 07, 2021 |
| ASUSTek       | H81M-A                      | [9e0c8e8024](https://bsd-hardware.info/?probe=9e0c8e8024) | Aug 07, 2021 |
| Unknown       | YL-SKUL6-7 Series           | [b9ef180b73](https://bsd-hardware.info/?probe=b9ef180b73) | Aug 04, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [3ff984316b](https://bsd-hardware.info/?probe=3ff984316b) | Aug 04, 2021 |
| Dell          | 0G261D A00                  | [2ce00e9f6b](https://bsd-hardware.info/?probe=2ce00e9f6b) | Aug 02, 2021 |
| Unknown       | Unknown                     | [34d448e1d1](https://bsd-hardware.info/?probe=34d448e1d1) | Jul 30, 2021 |
| Unknown       | Unknown                     | [846b6cca20](https://bsd-hardware.info/?probe=846b6cca20) | Jul 30, 2021 |
| Unknown       | Unknown                     | [8aaf18daa1](https://bsd-hardware.info/?probe=8aaf18daa1) | Jul 28, 2021 |
| ASRock        | D1800B-ITX                  | [4831cc5183](https://bsd-hardware.info/?probe=4831cc5183) | Jul 21, 2021 |
| HP            | 2B4B                        | [456625c82f](https://bsd-hardware.info/?probe=456625c82f) | Jul 04, 2021 |
| Dell          | 0XR1GT A00                  | [1e66c42238](https://bsd-hardware.info/?probe=1e66c42238) | Jul 02, 2021 |
| Shuttle       | NC10U                       | [5d2d20dd04](https://bsd-hardware.info/?probe=5d2d20dd04) | Jul 02, 2021 |
| ASUSTek       | PRIME B350M-E               | [bde8057846](https://bsd-hardware.info/?probe=bde8057846) | Jun 29, 2021 |
| Wistron       | ProLiant ML110 G6           | [8f336c0fa3](https://bsd-hardware.info/?probe=8f336c0fa3) | Jun 19, 2021 |
| Wistron       | ProLiant ML110 G6           | [dc619f203f](https://bsd-hardware.info/?probe=dc619f203f) | Jun 19, 2021 |
| ASRock        | H110M-ITX                   | [124c75ba7c](https://bsd-hardware.info/?probe=124c75ba7c) | Jun 17, 2021 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | [e6cbfc417b](https://bsd-hardware.info/?probe=e6cbfc417b) | Jun 10, 2021 |
| Supermicro    | X10SLH-N6-ST031             | [e54175f99f](https://bsd-hardware.info/?probe=e54175f99f) | Jun 06, 2021 |
| Unknown       | YL-J3160L4                  | [24f3dbd372](https://bsd-hardware.info/?probe=24f3dbd372) | Jun 04, 2021 |
| Dell          | 0T10XW A02                  | [cec18015ba](https://bsd-hardware.info/?probe=cec18015ba) | May 30, 2021 |
| Dell          | 0T10XW A02                  | [16f36a045f](https://bsd-hardware.info/?probe=16f36a045f) | May 26, 2021 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | [3e650be93d](https://bsd-hardware.info/?probe=3e650be93d) | May 24, 2021 |
| ASUSTek       | AM1I-A                      | [aafc52d6a1](https://bsd-hardware.info/?probe=aafc52d6a1) | May 24, 2021 |
| Google        | Guado                       | [54f01f821d](https://bsd-hardware.info/?probe=54f01f821d) | May 21, 2021 |
| MSI           | Z77A-G41                    | [c471a8f2fe](https://bsd-hardware.info/?probe=c471a8f2fe) | May 16, 2021 |
| Unknown       | YL-J3160L4                  | [3468faf656](https://bsd-hardware.info/?probe=3468faf656) | May 07, 2021 |
| ASRockRack    | X470D4U                     | [421da89770](https://bsd-hardware.info/?probe=421da89770) | May 06, 2021 |
| ASUSTek       | P8H77-M PRO                 | [87e5651fd1](https://bsd-hardware.info/?probe=87e5651fd1) | May 06, 2021 |
| PC Engines    | APU2                        | [c99a0b0e4d](https://bsd-hardware.info/?probe=c99a0b0e4d) | May 05, 2021 |
| MSI           | MS-9A45 0A                  | [e930fac60b](https://bsd-hardware.info/?probe=e930fac60b) | May 05, 2021 |
| Supermicro    | X8STi                       | [c615ef1edf](https://bsd-hardware.info/?probe=c615ef1edf) | May 04, 2021 |
| ASUSTek       | Rampage II GENE             | [4eac97c85c](https://bsd-hardware.info/?probe=4eac97c85c) | May 04, 2021 |
| Unknown       | Unknown                     | [4368de8d34](https://bsd-hardware.info/?probe=4368de8d34) | Apr 28, 2021 |
| PC Engines    | APU3                        | [1d6ca07c5a](https://bsd-hardware.info/?probe=1d6ca07c5a) | Apr 27, 2021 |
| PC Engines    | APU3                        | [8fc426b107](https://bsd-hardware.info/?probe=8fc426b107) | Apr 22, 2021 |
| Dell          | 0PC5F7 A03                  | [e262812b4d](https://bsd-hardware.info/?probe=e262812b4d) | Apr 21, 2021 |
| Unknown       | J3160-4L                    | [354dc80671](https://bsd-hardware.info/?probe=354dc80671) | Apr 07, 2021 |
| PC Engines    | apu4                        | [160a01d9e1](https://bsd-hardware.info/?probe=160a01d9e1) | Apr 03, 2021 |
| Supermicro    | X7SPA-HF                    | [f3b6d4d5c4](https://bsd-hardware.info/?probe=f3b6d4d5c4) | Apr 03, 2021 |
| PC Engines    | APU2                        | [97554df75d](https://bsd-hardware.info/?probe=97554df75d) | Mar 30, 2021 |
| ASUSTek       | P8Z68-V LX                  | [0263b0e32e](https://bsd-hardware.info/?probe=0263b0e32e) | Mar 26, 2021 |
| Lenovo        | 3138                        | [f12dd68efb](https://bsd-hardware.info/?probe=f12dd68efb) | Mar 25, 2021 |
| Dell          | 0KRC95 A02                  | [68354c00cf](https://bsd-hardware.info/?probe=68354c00cf) | Mar 25, 2021 |
| Dell          | 0NW6H5 A00                  | [1499695aae](https://bsd-hardware.info/?probe=1499695aae) | Mar 25, 2021 |
| Dell          | 0NW6H5 A00                  | [650cd9b653](https://bsd-hardware.info/?probe=650cd9b653) | Mar 24, 2021 |
| Dell          | 0D28YY A00                  | [bef38bd379](https://bsd-hardware.info/?probe=bef38bd379) | Mar 23, 2021 |
| ASRock        | Z490M Pro4                  | [c0df245c1b](https://bsd-hardware.info/?probe=c0df245c1b) | Mar 13, 2021 |
| Dell          | 0PC5F7 A03                  | [24b657e7ba](https://bsd-hardware.info/?probe=24b657e7ba) | Mar 12, 2021 |
| MSI           | B360M BAZOOKA               | [17a763a917](https://bsd-hardware.info/?probe=17a763a917) | Mar 11, 2021 |
| ASUSTek       | AM1I-A                      | [835842d361](https://bsd-hardware.info/?probe=835842d361) | Mar 10, 2021 |
| ASRock        | Z490M Pro4                  | [348d592fab](https://bsd-hardware.info/?probe=348d592fab) | Mar 05, 2021 |
| VeryPC        | S400                        | [77b744169b](https://bsd-hardware.info/?probe=77b744169b) | Mar 04, 2021 |
| VeryPC        | S400                        | [edcea11cb7](https://bsd-hardware.info/?probe=edcea11cb7) | Mar 04, 2021 |
| HP            | 86E9 A                      | [215398b88f](https://bsd-hardware.info/?probe=215398b88f) | Feb 28, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [b1f1b3cd82](https://bsd-hardware.info/?probe=b1f1b3cd82) | Feb 22, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [929bda8001](https://bsd-hardware.info/?probe=929bda8001) | Feb 22, 2021 |
| Acer          | EG43M                       | [22552918ee](https://bsd-hardware.info/?probe=22552918ee) | Feb 21, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [ade306695d](https://bsd-hardware.info/?probe=ade306695d) | Feb 20, 2021 |
| ASRock        | H370M-ITX/ac                | [5d39657098](https://bsd-hardware.info/?probe=5d39657098) | Feb 14, 2021 |
| ASUSTek       | PRIME B450M-A               | [ba7f82b343](https://bsd-hardware.info/?probe=ba7f82b343) | Feb 12, 2021 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [5965bc8a1d](https://bsd-hardware.info/?probe=5965bc8a1d) | Feb 11, 2021 |
| PC Engines    | APU                         | [282a9596c6](https://bsd-hardware.info/?probe=282a9596c6) | Feb 11, 2021 |
| Dell          | 030VXY A01                  | [23e7163f58](https://bsd-hardware.info/?probe=23e7163f58) | Feb 10, 2021 |
| Gigabyte      | Z97P-D3                     | [a3bd8f5772](https://bsd-hardware.info/?probe=a3bd8f5772) | Feb 10, 2021 |
| Dell          | 0PC5F7 A03                  | [94bcab24a8](https://bsd-hardware.info/?probe=94bcab24a8) | Feb 09, 2021 |
| PC Engines    | APU3                        | [e21438c3cc](https://bsd-hardware.info/?probe=e21438c3cc) | Feb 07, 2021 |
| MSI           | Z77A-G41                    | [35bae50659](https://bsd-hardware.info/?probe=35bae50659) | Feb 06, 2021 |
| Unknown       | Unknown                     | [8ef7071a3f](https://bsd-hardware.info/?probe=8ef7071a3f) | Feb 04, 2021 |
| Unknown       | YL-J3160L4                  | [857c5aade9](https://bsd-hardware.info/?probe=857c5aade9) | Feb 04, 2021 |
| MSI           | MS-9A45 0A                  | [f66ccf2f33](https://bsd-hardware.info/?probe=f66ccf2f33) | Feb 03, 2021 |
| MSI           | MS-9A45 0A                  | [c384535b6f](https://bsd-hardware.info/?probe=c384535b6f) | Feb 02, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | [c8af335c01](https://bsd-hardware.info/?probe=c8af335c01) | Jan 29, 2021 |
| ASUSTek       | M2NPV-MX                    | [dae16641bb](https://bsd-hardware.info/?probe=dae16641bb) | Jan 23, 2021 |
| Unknown       | Unknown                     | [4c4d549584](https://bsd-hardware.info/?probe=4c4d549584) | Jan 22, 2021 |
| ASUSTek       | M2NPV-MX                    | [80edc8dae6](https://bsd-hardware.info/?probe=80edc8dae6) | Jan 22, 2021 |
| PC Engines    | apu4                        | [3507544d2e](https://bsd-hardware.info/?probe=3507544d2e) | Jan 20, 2021 |
| Dell          | 0NW6H5 A00                  | [f6df3820b5](https://bsd-hardware.info/?probe=f6df3820b5) | Jan 18, 2021 |
| Dell          | 0KC9NP A01                  | [a9228fa7c3](https://bsd-hardware.info/?probe=a9228fa7c3) | Jan 15, 2021 |
| Dell          | 030VXY A01                  | [5af442bf61](https://bsd-hardware.info/?probe=5af442bf61) | Jan 15, 2021 |
| HP            | 3399                        | [b11946a41a](https://bsd-hardware.info/?probe=b11946a41a) | Jan 13, 2021 |
| Pegatron      | 2AB5                        | [8093f75ea2](https://bsd-hardware.info/?probe=8093f75ea2) | Jan 13, 2021 |
| Dell          | 0NW6H5 A00                  | [d54f451ea5](https://bsd-hardware.info/?probe=d54f451ea5) | Jan 07, 2021 |
| HP            | 3032h                       | [13648fd22d](https://bsd-hardware.info/?probe=13648fd22d) | Jan 07, 2021 |
| Dell          | 0KC9NP A01                  | [ee2d5f3289](https://bsd-hardware.info/?probe=ee2d5f3289) | Jan 07, 2021 |
| Dell          | 030VXY A01                  | [c117ffdc98](https://bsd-hardware.info/?probe=c117ffdc98) | Jan 07, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | [36ef631bfe](https://bsd-hardware.info/?probe=36ef631bfe) | Jan 05, 2021 |
| Gigabyte      | X79-UD3                     | [a8baf509d9](https://bsd-hardware.info/?probe=a8baf509d9) | Dec 26, 2020 |
| ASUSTek       | PRIME B450M-A               | [d13e0a1749](https://bsd-hardware.info/?probe=d13e0a1749) | Dec 15, 2020 |
| ASRock        | J3455-ITX                   | [1d5bd18d14](https://bsd-hardware.info/?probe=1d5bd18d14) | Oct 29, 2020 |
| Supermicro    | X8STi                       | [1b64902781](https://bsd-hardware.info/?probe=1b64902781) | Oct 26, 2020 |
| AZW           | Z83 II                      | [9416876f20](https://bsd-hardware.info/?probe=9416876f20) | Oct 24, 2020 |
| AZW           | Z83 II                      | [19b1b4d85d](https://bsd-hardware.info/?probe=19b1b4d85d) | Oct 24, 2020 |
| Intel         | D2500HN                     | [6dbc4dfa33](https://bsd-hardware.info/?probe=6dbc4dfa33) | Oct 21, 2020 |
| PC Engines    | APU2                        | [d1ca549fe7](https://bsd-hardware.info/?probe=d1ca549fe7) | Oct 21, 2020 |
| ZOTAC         | XXXXXX                      | [0f8960bdd3](https://bsd-hardware.info/?probe=0f8960bdd3) | Oct 21, 2020 |
| Intel         | D2500HN                     | [4b432dcb3d](https://bsd-hardware.info/?probe=4b432dcb3d) | Oct 20, 2020 |
| PC Engines    | APU2                        | [b95ef9962d](https://bsd-hardware.info/?probe=b95ef9962d) | Oct 20, 2020 |
| PC Engines    | APU2                        | [aecf376503](https://bsd-hardware.info/?probe=aecf376503) | Oct 20, 2020 |
| HP            | ProLiant MicroServer Gen... | [88f2d98930](https://bsd-hardware.info/?probe=88f2d98930) | Sep 12, 2020 |
| Intel         | DH61AG AAG23736-505         | [3f99489a19](https://bsd-hardware.info/?probe=3f99489a19) | Aug 19, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [42de38c478](https://bsd-hardware.info/?probe=42de38c478) | Aug 19, 2020 |
| Intel         | DN2800MT AAG81515-900       | [bcfec367a9](https://bsd-hardware.info/?probe=bcfec367a9) | Aug 14, 2020 |
| Gigabyte      | P35-DS3R                    | [4ed0c89a67](https://bsd-hardware.info/?probe=4ed0c89a67) | Aug 07, 2020 |
| ASUSTek       | Z170-P D3                   | [7b8885caf3](https://bsd-hardware.info/?probe=7b8885caf3) | Aug 07, 2020 |
| ASUSTek       | Z170-P D3                   | [2e9821f90f](https://bsd-hardware.info/?probe=2e9821f90f) | Aug 07, 2020 |
| Gigabyte      | EP45-DS4                    | [a56a9c50fc](https://bsd-hardware.info/?probe=a56a9c50fc) | Aug 07, 2020 |
| Gigabyte      | P35-DS3R                    | [0b111b137c](https://bsd-hardware.info/?probe=0b111b137c) | Aug 07, 2020 |
| Intel         | DH61AGL G71256-202          | [666757a826](https://bsd-hardware.info/?probe=666757a826) | Jun 14, 2020 |
| PC Engines    | APU2                        | [dc1c86095f](https://bsd-hardware.info/?probe=dc1c86095f) | Jun 14, 2020 |
| Gigabyte      | H77N-WIFI                   | [48dd406069](https://bsd-hardware.info/?probe=48dd406069) | May 30, 2020 |
| ASUSTek       | P8H61 PRO                   | [94c4617d4e](https://bsd-hardware.info/?probe=94c4617d4e) | May 27, 2020 |
| MSI           | Z87I GAMING AC              | [5d38b05178](https://bsd-hardware.info/?probe=5d38b05178) | May 25, 2020 |
| Unknown       | Unknown                     | [3bcdac5d97](https://bsd-hardware.info/?probe=3bcdac5d97) | May 24, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OPNsense 21.1.5   | 13       | 4.59%   |
| OPNsense 23.1.1   | 11       | 3.89%   |
| OPNsense 21.7.7   | 10       | 3.53%   |
| OPNsense 22.1.6   | 9        | 3.18%   |
| OpenBSD 6.8       | 9        | 3.18%   |
| OPNsense 23.1     | 6        | 2.12%   |
| OPNsense 22.7.9   | 6        | 2.12%   |
| OPNsense 22.7.4   | 6        | 2.12%   |
| OPNsense 22.7     | 6        | 2.12%   |
| OPNsense 22.1.10  | 6        | 2.12%   |
| OPNsense 22.1.1   | 6        | 2.12%   |
| OPNsense 22.1     | 6        | 2.12%   |
| OPNsense 21.7.1   | 6        | 2.12%   |
| OPNsense 21.1.3   | 6        | 2.12%   |
| OPNsense 21.1     | 6        | 2.12%   |
| OPNsense 22.1.2   | 5        | 1.77%   |
| helloSystem 0.5.0 | 5        | 1.77%   |
| GhostBSD 20.04.02 | 5        | 1.77%   |
| FreeBSD 13.1      | 5        | 1.77%   |
| OPNsense 23.1.3   | 4        | 1.41%   |
| OPNsense 22.7.7   | 4        | 1.41%   |
| OPNsense 22.7.10  | 4        | 1.41%   |
| OPNsense 22.1.3   | 4        | 1.41%   |
| OPNsense 21.7.8   | 4        | 1.41%   |
| OPNsense 21.7.5   | 4        | 1.41%   |
| OPNsense 21.7.3   | 4        | 1.41%   |
| OPNsense 21.7     | 4        | 1.41%   |
| OPNsense 20.7.8   | 4        | 1.41%   |
| OpenBSD 7.2       | 4        | 1.41%   |
| OpenBSD 7.1       | 4        | 1.41%   |
| helloSystem 0.8.1 | 4        | 1.41%   |
| helloSystem 0.7.0 | 4        | 1.41%   |
| helloSystem 0.4.0 | 4        | 1.41%   |
| FreeBSD 12.1-p8   | 4        | 1.41%   |
| OPNsense 22.7.8   | 3        | 1.06%   |
| OPNsense 22.7.5   | 3        | 1.06%   |
| OPNsense 22.7.11  | 3        | 1.06%   |
| OPNsense 22.1.5   | 3        | 1.06%   |
| OPNsense 21.7.4   | 3        | 1.06%   |
| OPNsense 21.1.7   | 3        | 1.06%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 131      | 58.22%  |
| FreeBSD     | 43       | 19.11%  |
| OpenBSD     | 18       | 8%      |
| helloSystem | 18       | 8%      |
| GhostBSD    | 5        | 2.22%   |
| NomadBSD    | 3        | 1.33%   |
| NetBSD      | 3        | 1.33%   |
| TrueNAS     | 2        | 0.89%   |
| HardenedBSD | 1        | 0.44%   |
| FreeNAS     | 1        | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 222      | 99.11%  |
| i386  | 2        | 0.89%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 164      | 72.25%  |
| helloDesktop | 28       | 12.33%  |
| XFCE         | 14       | 6.17%   |
| MATE         | 5        | 2.2%    |
| KDE5         | 4        | 1.76%   |
| Openbox      | 3        | 1.32%   |
| fvwm         | 3        | 1.32%   |
| GNOME        | 2        | 0.88%   |
| TWM          | 1        | 0.44%   |
| LXDE         | 1        | 0.44%   |
| Cinnamon     | 1        | 0.44%   |
| AwesomeWM    | 1        | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 168      | 75%     |
| X11     | 55       | 24.55%  |
| Wayland | 1        | 0.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 182      | 80.89%  |
| SLiM    | 26       | 11.56%  |
| LightDM | 10       | 4.44%   |
| SDDM    | 4        | 1.78%   |
| XDM     | 2        | 0.89%   |
| GDM     | 1        | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 167      | 74.22%  |
| en_US          | 22       | 9.78%   |
| fr_FR          | 19       | 8.44%   |
| C              | 16       | 7.11%   |
| fr_FR.US-ASCII | 1        | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 172      | 76.11%  |
| BIOS | 54       | 23.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 119      | 52.19%  |
| Zfs    | 85       | 37.28%  |
| Ffs    | 18       | 7.89%   |
| Cd9660 | 6        | 2.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 194      | 85.84%  |
| MBR     | 30       | 13.27%  |
| Unknown | 2        | 0.88%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 35       | 15.63%  |
| Intel               | 24       | 10.71%  |
| Dell                | 23       | 10.27%  |
| Hewlett-Packard     | 20       | 8.93%   |
| Unknown             | 20       | 8.93%   |
| PC Engines          | 18       | 8.04%   |
| Gigabyte Technology | 16       | 7.14%   |
| ASRock              | 12       | 5.36%   |
| MSI                 | 9        | 4.02%   |
| Supermicro          | 7        | 3.13%   |
| Techvision          | 4        | 1.79%   |
| Protectli           | 3        | 1.34%   |
| Lenovo              | 3        | 1.34%   |
| Fujitsu             | 3        | 1.34%   |
| Shuttle             | 2        | 0.89%   |
| RUNING              | 2        | 0.89%   |
| MW                  | 2        | 0.89%   |
| ASRockRack          | 2        | 0.89%   |
| AMD                 | 2        | 0.89%   |
| Acer                | 2        | 0.89%   |
| ZOTAC               | 1        | 0.45%   |
| YENTEK              | 1        | 0.45%   |
| Wistron             | 1        | 0.45%   |
| VeryPC              | 1        | 0.45%   |
| Soekris Engineering | 1        | 0.45%   |
| Pegatron            | 1        | 0.45%   |
| Packard Bell        | 1        | 0.45%   |
| Jetway              | 1        | 0.45%   |
| Google              | 1        | 0.45%   |
| Deciso              | 1        | 0.45%   |
| CNCTION-IAF-E3845   | 1        | 0.45%   |
| Clevo               | 1        | 0.45%   |
| ChangWang           | 1        | 0.45%   |
| AZW                 | 1        | 0.45%   |
| AAEON               | 1        | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown                          | 21       | 9.38%   |
| Intel Q3XXG4-P V1.0              | 11       | 4.91%   |
| PC Engines APU2                  | 10       | 4.46%   |
| Techvision TVI7309X              | 4        | 1.79%   |
| Dell OptiPlex 9020               | 4        | 1.79%   |
| ASUS All Series                  | 4        | 1.79%   |
| PC Engines APU3                  | 3        | 1.34%   |
| Intel CRESCENTBAY                | 3        | 1.34%   |
| RUNING B75M INTEL H3V            | 2        | 0.89%   |
| PC Engines apu4                  | 2        | 0.89%   |
| PC Engines apu1                  | 2        | 0.89%   |
| MW GMLK-2_5G4L                   | 2        | 0.89%   |
| HP ProLiant MicroServer Gen8     | 2        | 0.89%   |
| Gigabyte X570 I AORUS PRO WIFI   | 2        | 0.89%   |
| Dell OptiPlex 7010               | 2        | 0.89%   |
| Dell OptiPlex 3050               | 2        | 0.89%   |
| Dell OptiPlex 3010               | 2        | 0.89%   |
| ASUS Z170-P D3                   | 2        | 0.89%   |
| ASUS PRIME B450M-A               | 2        | 0.89%   |
| ASUS PRIME A320I-K               | 2        | 0.89%   |
| ASUS P8Z68-V LX                  | 2        | 0.89%   |
| ZOTAC XXXXXX                     | 1        | 0.45%   |
| YENTEK R250                      | 1        | 0.45%   |
| Wistron ProLiant ML110 G6        | 1        | 0.45%   |
| VeryPC S400-K7-N-O               | 1        | 0.45%   |
| Supermicro X8STi                 | 1        | 0.45%   |
| Supermicro X7SPA-HF              | 1        | 0.45%   |
| Supermicro X10SLH-N6-ST031       | 1        | 0.45%   |
| Supermicro SYS-E300-9D-8CN8TP    | 1        | 0.45%   |
| Supermicro SYS-E300-9A-4C        | 1        | 0.45%   |
| Supermicro SYS-5019A-FTN4        | 1        | 0.45%   |
| Supermicro SYS-1018GR-TA02-CG009 | 1        | 0.45%   |
| Soekris Engineering net6501      | 1        | 0.45%   |
| Shuttle NC10U                    | 1        | 0.45%   |
| Shuttle DS61                     | 1        | 0.45%   |
| Protectli VP2410                 | 1        | 0.45%   |
| Protectli FW6                    | 1        | 0.45%   |
| Protectli FW4B                   | 1        | 0.45%   |
| Pegatron Elite 7300 Series MT    | 1        | 0.45%   |
| PC Engines APU                   | 1        | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown                          | 21       | 9.38%   |
| Dell OptiPlex                    | 18       | 8.04%   |
| Intel Q3XXG4-P                   | 11       | 4.91%   |
| PC Engines APU2                  | 10       | 4.46%   |
| ASUS PRIME                       | 10       | 4.46%   |
| HP Compaq                        | 7        | 3.13%   |
| Techvision TVI7309X              | 4        | 1.79%   |
| HP ProDesk                       | 4        | 1.79%   |
| ASUS All                         | 4        | 1.79%   |
| PC Engines APU3                  | 3        | 1.34%   |
| Intel CRESCENTBAY                | 3        | 1.34%   |
| RUNING B75M                      | 2        | 0.89%   |
| PC Engines apu4                  | 2        | 0.89%   |
| PC Engines apu1                  | 2        | 0.89%   |
| MW GMLK-2                        | 2        | 0.89%   |
| HP ProLiant                      | 2        | 0.89%   |
| HP EliteDesk                     | 2        | 0.89%   |
| Gigabyte X570                    | 2        | 0.89%   |
| ASUS Z170-P                      | 2        | 0.89%   |
| ASUS TUF                         | 2        | 0.89%   |
| ASUS P8Z68-V                     | 2        | 0.89%   |
| ZOTAC XXXXXX                     | 1        | 0.45%   |
| YENTEK R250                      | 1        | 0.45%   |
| Wistron ProLiant                 | 1        | 0.45%   |
| VeryPC S400-K7-N-O               | 1        | 0.45%   |
| Supermicro X8STi                 | 1        | 0.45%   |
| Supermicro X7SPA-HF              | 1        | 0.45%   |
| Supermicro X10SLH-N6-ST031       | 1        | 0.45%   |
| Supermicro SYS-E300-9D-8CN8TP    | 1        | 0.45%   |
| Supermicro SYS-E300-9A-4C        | 1        | 0.45%   |
| Supermicro SYS-5019A-FTN4        | 1        | 0.45%   |
| Supermicro SYS-1018GR-TA02-CG009 | 1        | 0.45%   |
| Soekris Engineering net6501      | 1        | 0.45%   |
| Shuttle NC10U                    | 1        | 0.45%   |
| Shuttle DS61                     | 1        | 0.45%   |
| Protectli VP2410                 | 1        | 0.45%   |
| Protectli FW6                    | 1        | 0.45%   |
| Protectli FW4B                   | 1        | 0.45%   |
| Pegatron Elite                   | 1        | 0.45%   |
| PC Engines APU                   | 1        | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2016    | 36       | 16.07%  |
| 2019    | 25       | 11.16%  |
| 2018    | 25       | 11.16%  |
| 2012    | 20       | 8.93%   |
| 2020    | 17       | 7.59%   |
| 2014    | 14       | 6.25%   |
| 2013    | 14       | 6.25%   |
| 2021    | 13       | 5.8%    |
| 2022    | 12       | 5.36%   |
| 2015    | 8        | 3.57%   |
| 2017    | 7        | 3.13%   |
| 2011    | 7        | 3.13%   |
| 2010    | 7        | 3.13%   |
| Unknown | 6        | 2.68%   |
| 2009    | 5        | 2.23%   |
| 2008    | 4        | 1.79%   |
| 2007    | 3        | 1.34%   |
| 2006    | 1        | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 224      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 204      | 91.07%  |
| Yes  | 20       | 8.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 76       | 33.78%  |
| 4.01-8.0    | 58       | 25.78%  |
| 16.01-24.0  | 52       | 23.11%  |
| 32.01-64.0  | 12       | 5.33%   |
| 2.01-3.0    | 11       | 4.89%   |
| 64.01-256.0 | 7        | 3.11%   |
| 1.01-2.0    | 4        | 1.78%   |
| 3.01-4.0    | 2        | 0.89%   |
| 24.01-32.0  | 2        | 0.89%   |
| 0.51-1.0    | 1        | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 123      | 54.67%  |
| 0.51-1.0   | 61       | 27.11%  |
| 1.01-2.0   | 20       | 8.89%   |
| 2.01-3.0   | 7        | 3.11%   |
| 4.01-8.0   | 4        | 1.78%   |
| 3.01-4.0   | 3        | 1.33%   |
| Unknown    | 3        | 1.33%   |
| 8.01-16.0  | 2        | 0.89%   |
| 16.01-24.0 | 1        | 0.44%   |
| 0          | 1        | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 141      | 61.84%  |
| 2      | 30       | 13.16%  |
| 0      | 22       | 9.65%   |
| 3      | 19       | 8.33%   |
| 5      | 6        | 2.63%   |
| 4      | 5        | 2.19%   |
| 6      | 3        | 1.32%   |
| 10     | 1        | 0.44%   |
| 8      | 1        | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 191      | 84.51%  |
| Yes       | 35       | 15.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 223      | 99.55%  |
| No        | 1        | 0.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 167      | 74.22%  |
| Yes       | 58       | 25.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 195      | 87.05%  |
| Yes       | 29       | 12.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| France  | 224      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Paris                   | 51       | 20.4%   |
| Toulouse                | 5        | 2%      |
| Roubaix                 | 5        | 2%      |
| Soisy-sur-Seine         | 4        | 1.6%    |
| Saint-Denis             | 4        | 1.6%    |
| Lyon                    | 4        | 1.6%    |
| Agen                    | 4        | 1.6%    |
| Vaulx-en-Velin          | 3        | 1.2%    |
| Thionville              | 3        | 1.2%    |
| Montfermeil             | 3        | 1.2%    |
| Lille                   | 3        | 1.2%    |
| Bonson                  | 3        | 1.2%    |
| Г‰chirolles          | 2        | 0.8%    |
| Villeurbanne            | 2        | 0.8%    |
| Seyssinet-Pariset       | 2        | 0.8%    |
| Saint-Martin-d'HГЁres | 2        | 0.8%    |
| Rennes                  | 2        | 0.8%    |
| Pau                     | 2        | 0.8%    |
| Noisy-le-Grand          | 2        | 0.8%    |
| Nice                    | 2        | 0.8%    |
| Nantes                  | 2        | 0.8%    |
| Marseille               | 2        | 0.8%    |
| Fougeres                | 2        | 0.8%    |
| Escaudain               | 2        | 0.8%    |
| Courbevoie              | 2        | 0.8%    |
| Cognac                  | 2        | 0.8%    |
| Clermont-Ferrand        | 2        | 0.8%    |
| Bordeaux                | 2        | 0.8%    |
| Ã‰tampes             | 2        | 0.8%    |
| Anglet                  | 2        | 0.8%    |
| Yerres                  | 1        | 0.4%    |
| Wasquehal               | 1        | 0.4%    |
| Villaz                  | 1        | 0.4%    |
| Vichy                   | 1        | 0.4%    |
| Vénissieux             | 1        | 0.4%    |
| Vauvillers              | 1        | 0.4%    |
| Vauclerc                | 1        | 0.4%    |
| Teteghem                | 1        | 0.4%    |
| Strasbourg              | 1        | 0.4%    |
| Schiltigheim            | 1        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 38       | 54     | 13.97%  |
| WDC                 | 36       | 63     | 13.24%  |
| Samsung Electronics | 30       | 42     | 11.03%  |
| Crucial             | 24       | 30     | 8.82%   |
| Kingston            | 21       | 35     | 7.72%   |
| Transcend           | 12       | 17     | 4.41%   |
| Toshiba             | 10       | 18     | 3.68%   |
| China               | 10       | 19     | 3.68%   |
| Phison              | 9        | 10     | 3.31%   |
| Intel               | 9        | 12     | 3.31%   |
| PNY                 | 7        | 14     | 2.57%   |
| SanDisk             | 6        | 13     | 2.21%   |
| Hoodisk             | 5        | 5      | 1.84%   |
| HGST                | 5        | 8      | 1.84%   |
| Corsair             | 5        | 9      | 1.84%   |
| Hitachi             | 4        | 4      | 1.47%   |
| Apple               | 4        | 6      | 1.47%   |
| OCZ                 | 3        | 4      | 1.1%    |
| LDLC                | 3        | 3      | 1.1%    |
| SK hynix            | 2        | 2      | 0.74%   |
| NVMe                | 2        | 2      | 0.74%   |
| Micron Technology   | 2        | 3      | 0.74%   |
| Maxtor              | 2        | 3      | 0.74%   |
| Fujitsu             | 2        | 2      | 0.74%   |
| Fanxiang            | 2        | 2      | 0.74%   |
| A-DATA Technology   | 2        | 2      | 0.74%   |
| TEXTORM             | 1        | 1      | 0.37%   |
| SPCC                | 1        | 1      | 0.37%   |
| Silicon Power       | 1        | 1      | 0.37%   |
| ShiJi               | 1        | 2      | 0.37%   |
| SABRENT             | 1        | 1      | 0.37%   |
| Pccooler            | 1        | 1      | 0.37%   |
| OPENBSD             | 1        | 2      | 0.37%   |
| LITEON              | 1        | 2      | 0.37%   |
| Kingchuxing         | 1        | 2      | 0.37%   |
| Innodisk            | 1        | 1      | 0.37%   |
| Indilinx            | 1        | 7      | 0.37%   |
| Generic             | 1        | 1      | 0.37%   |
| FORESEE             | 1        | 2      | 0.37%   |
| Dell                | 1        | 2      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Phison SATA SSD 16GB               | 8        | 2.69%   |
| Samsung SSD 850 EVO 250GB          | 6        | 2.02%   |
| PNY CS900 120GB SSD                | 4        | 1.35%   |
| Crucial CT120BX500SSD1 120GB       | 4        | 1.35%   |
| China MSATA 64GB SSD               | 4        | 1.35%   |
| WDC WDS240G2G0A-00JH30 240GB       | 3        | 1.01%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3        | 1.01%   |
| Seagate ST3500418AS 500GB          | 3        | 1.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3        | 1.01%   |
| SanDisk SSD PLUS 120GB             | 3        | 1.01%   |
| Kingston SV300S37A120G 120GB       | 3        | 1.01%   |
| Kingston SUV500MS120G 120GB        | 3        | 1.01%   |
| Kingston SA400S37240G 240GB        | 3        | 1.01%   |
| Kingston SA400S37120G 120GB        | 3        | 1.01%   |
| HGST HUS724020ALA640 2TB           | 3        | 1.01%   |
| Crucial CT240BX500SSD1 240GB       | 3        | 1.01%   |
| Crucial CT1000BX500SSD1 1TB        | 3        | 1.01%   |
| Transcend TS128GSSD420K 128GB      | 2        | 0.67%   |
| Transcend TS128GMSA230S 128GB      | 2        | 0.67%   |
| Toshiba HDWD120 2TB                | 2        | 0.67%   |
| SK hynix SC311 SATA 256GB          | 2        | 0.67%   |
| Seagate ST31000524AS 1TB           | 2        | 0.67%   |
| Seagate ST2000NM000A-2J2100 2TB    | 2        | 0.67%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 0.67%   |
| Seagate ST2000DM001-9YN164 2TB     | 2        | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB     | 2        | 0.67%   |
| Seagate ST1000DM003-1SB102 1TB     | 2        | 0.67%   |
| Seagate ST1000DM003-1ER162 1TB     | 2        | 0.67%   |
| Samsung HD501LJ 500GB              | 2        | 0.67%   |
| PNY 120GB SATA SSD                 | 2        | 0.67%   |
| LDLC F8+M.2 240 240GB              | 2        | 0.67%   |
| Kingston SUV400S37240G 240GB       | 2        | 0.67%   |
| Hoodisk SSD 32GB                   | 2        | 0.67%   |
| HGST HUS726020ALA610 2TB           | 2        | 0.67%   |
| Fanxiang S500PRO 256GB             | 2        | 0.67%   |
| Crucial CT500MX500SSD1 500GB       | 2        | 0.67%   |
| Crucial CT250P2SSD8 250GB          | 2        | 0.67%   |
| Crucial CT250MX500SSD1 250GB       | 2        | 0.67%   |
| Crucial CT1000P1SSD8 1TB           | 2        | 0.67%   |
| Corsair Force LX SSD 128GB         | 2        | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 37       | 52     | 35.58%  |
| WDC                 | 32       | 58     | 30.77%  |
| Toshiba             | 9        | 17     | 8.65%   |
| Samsung Electronics | 7        | 13     | 6.73%   |
| HGST                | 5        | 8      | 4.81%   |
| Hitachi             | 4        | 4      | 3.85%   |
| Maxtor              | 2        | 3      | 1.92%   |
| Fujitsu             | 2        | 2      | 1.92%   |
| Apple               | 2        | 4      | 1.92%   |
| SABRENT             | 1        | 1      | 0.96%   |
| OPENBSD             | 1        | 2      | 0.96%   |
| Generic             | 1        | 1      | 0.96%   |
| Dell                | 1        | 2      | 0.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 19       | 33     | 13.38%  |
| Crucial             | 18       | 22     | 12.68%  |
| Samsung Electronics | 17       | 21     | 11.97%  |
| Transcend           | 11       | 15     | 7.75%   |
| China               | 10       | 19     | 7.04%   |
| Phison              | 8        | 9      | 5.63%   |
| PNY                 | 7        | 14     | 4.93%   |
| Intel               | 7        | 8      | 4.93%   |
| SanDisk             | 6        | 13     | 4.23%   |
| Hoodisk             | 5        | 5      | 3.52%   |
| WDC                 | 4        | 5      | 2.82%   |
| Corsair             | 4        | 5      | 2.82%   |
| OCZ                 | 3        | 4      | 2.11%   |
| SK hynix            | 2        | 2      | 1.41%   |
| NVMe                | 2        | 2      | 1.41%   |
| Apple               | 2        | 2      | 1.41%   |
| A-DATA Technology   | 2        | 2      | 1.41%   |
| Toshiba             | 1        | 1      | 0.7%    |
| TEXTORM             | 1        | 1      | 0.7%    |
| SPCC                | 1        | 1      | 0.7%    |
| Silicon Power       | 1        | 1      | 0.7%    |
| ShiJi               | 1        | 2      | 0.7%    |
| Seagate             | 1        | 2      | 0.7%    |
| Pccooler            | 1        | 1      | 0.7%    |
| Micron Technology   | 1        | 2      | 0.7%    |
| LITEON              | 1        | 2      | 0.7%    |
| Kingchuxing         | 1        | 2      | 0.7%    |
| Innodisk            | 1        | 1      | 0.7%    |
| Indilinx            | 1        | 7      | 0.7%    |
| FORESEE             | 1        | 2      | 0.7%    |
| BORY                | 1        | 2      | 0.7%    |
| BIWIN               | 1        | 1      | 0.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 132      | 209    | 55%     |
| HDD  | 81       | 167    | 33.75%  |
| NVMe | 27       | 36     | 11.25%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 186      | 376    | 87.32%  |
| NVMe | 27       | 36     | 12.68%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 157      | 254    | 70.4%   |
| 0.51-1.0   | 34       | 56     | 15.25%  |
| 1.01-2.0   | 20       | 41     | 8.97%   |
| 2.01-3.0   | 5        | 10     | 2.24%   |
| 4.01-10.0  | 5        | 9      | 2.24%   |
| 3.01-4.0   | 2        | 6      | 0.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 74       | 32.74%  |
| 1-20           | 38       | 16.81%  |
| 251-500        | 29       | 12.83%  |
| 21-50          | 26       | 11.5%   |
| 51-100         | 24       | 10.62%  |
| 501-1000       | 20       | 8.85%   |
| 1001-2000      | 7        | 3.1%    |
| 2001-3000      | 4        | 1.77%   |
| More than 3000 | 3        | 1.33%   |
| Unknown        | 1        | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 188      | 82.82%  |
| 21-50          | 17       | 7.49%   |
| 251-500        | 8        | 3.52%   |
| 101-250        | 5        | 2.2%    |
| 51-100         | 4        | 1.76%   |
| 501-1000       | 2        | 0.88%   |
| More than 3000 | 1        | 0.44%   |
| 1001-2000      | 1        | 0.44%   |
| Unknown        | 1        | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB       | 2        | 3      | 5%      |
| Samsung Electronics HD501LJ 500GB  | 2        | 2      | 5%      |
| WDC WD6400BPVT-22HXZT3 640GB       | 1        | 1      | 2.5%    |
| WDC WD6400AAKS-22A7B0 640GB        | 1        | 1      | 2.5%    |
| WDC WD5002ABYS-18B1B0 500GB        | 1        | 1      | 2.5%    |
| WDC WD30EFRX-68AX9N0 3TB           | 1        | 4      | 2.5%    |
| WDC WD2500BEVS-60UST0 250GB        | 1        | 1      | 2.5%    |
| WDC WD2002FYPS-02W3B0 2TB          | 1        | 1      | 2.5%    |
| WDC WD15EADS-00P8B0 1.5TB          | 1        | 1      | 2.5%    |
| WDC WD10EZEX-08WN4A0 1TB           | 1        | 1      | 2.5%    |
| WDC WD10EAVS-00D7B0 1TB            | 1        | 1      | 2.5%    |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 1      | 2.5%    |
| WDC WD1001FAES-75W7A0 1TB          | 1        | 1      | 2.5%    |
| Toshiba MK5065GSX 500GB            | 1        | 1      | 2.5%    |
| Toshiba DT01ACA100 1TB             | 1        | 1      | 2.5%    |
| Seagate ST9500325AS 500GB          | 1        | 1      | 2.5%    |
| Seagate ST500VT000-1DK142 500GB    | 1        | 1      | 2.5%    |
| Seagate ST500LM000-SSHD-8GB        | 1        | 2      | 2.5%    |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1      | 2.5%    |
| Seagate ST380013AS 80GB            | 1        | 2      | 2.5%    |
| Seagate ST3250620AS 250GB          | 1        | 1      | 2.5%    |
| Seagate ST3160023AS 160GB          | 1        | 1      | 2.5%    |
| Seagate ST31000524AS 1TB           | 1        | 1      | 2.5%    |
| Seagate ST1000NM0011 1TB           | 1        | 1      | 2.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 2.5%    |
| Samsung Electronics HD322GJ 320GB  | 1        | 1      | 2.5%    |
| Samsung Electronics HD256GJ 250GB  | 1        | 1      | 2.5%    |
| Samsung Electronics HD103UJ 1TB    | 1        | 1      | 2.5%    |
| OCZ VERTEX-TURBO 32GB              | 1        | 2      | 2.5%    |
| Maxtor 6Y080M0 82GB                | 1        | 1      | 2.5%    |
| Kingston SV300S37A120G 120GB       | 1        | 1      | 2.5%    |
| Intel SSDSA2M080G2GN 80GB          | 1        | 1      | 2.5%    |
| Hitachi HTS727575A9E364 752GB      | 1        | 1      | 2.5%    |
| Hitachi HTS542525K9SA00 250GB      | 1        | 1      | 2.5%    |
| HGST HTS721010A9E630 1TB           | 1        | 1      | 2.5%    |
| Corsair Force 3 SSD 120GB          | 1        | 2      | 2.5%    |
| A-DATA Technology SX300 128GB      | 1        | 1      | 2.5%    |
| A-DATA Technology SU800 128GB      | 1        | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 17     | 35.14%  |
| Seagate             | 9        | 12     | 24.32%  |
| Samsung Electronics | 3        | 5      | 8.11%   |
| Toshiba             | 2        | 2      | 5.41%   |
| Hitachi             | 2        | 2      | 5.41%   |
| A-DATA Technology   | 2        | 2      | 5.41%   |
| OCZ                 | 1        | 2      | 2.7%    |
| Maxtor              | 1        | 1      | 2.7%    |
| Kingston            | 1        | 1      | 2.7%    |
| Intel               | 1        | 1      | 2.7%    |
| HGST                | 1        | 1      | 2.7%    |
| Corsair             | 1        | 2      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 14     | 37.93%  |
| Seagate             | 9        | 12     | 31.03%  |
| Samsung Electronics | 3        | 5      | 10.34%  |
| Toshiba             | 2        | 2      | 6.9%    |
| Hitachi             | 2        | 2      | 6.9%    |
| Maxtor              | 1        | 1      | 3.45%   |
| HGST                | 1        | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 26       | 37     | 76.47%  |
| SSD  | 8        | 11     | 23.53%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 183      | 351    | 81.7%   |
| Malfunc  | 33       | 48     | 14.73%  |
| Detected | 8        | 13     | 3.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 164      | 60.74%  |
| AMD                           | 54       | 20%     |
| Micron/Crucial Technology     | 8        | 2.96%   |
| Samsung Electronics           | 7        | 2.59%   |
| ASMedia Technology            | 7        | 2.59%   |
| Silicon Motion                | 4        | 1.48%   |
| Broadcom / LSI                | 4        | 1.48%   |
| Marvell Technology Group      | 3        | 1.11%   |
| JMicron Technology            | 3        | 1.11%   |
| VIA Technologies              | 2        | 0.74%   |
| MAXIO Technology (Hangzhou)   | 2        | 0.74%   |
| Kingston Technology Company   | 2        | 0.74%   |
| Chelsio Communications        | 2        | 0.74%   |
| Transcend                     | 1        | 0.37%   |
| Silicon Image                 | 1        | 0.37%   |
| SanDisk                       | 1        | 0.37%   |
| Phison Electronics            | 1        | 0.37%   |
| Nvidia                        | 1        | 0.37%   |
| Micron Technology             | 1        | 0.37%   |
| Integrated Technology Express | 1        | 0.37%   |
| Hewlett-Packard               | 1        | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 31       | 10%     |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 17       | 5.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 16       | 5.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11       | 3.55%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 10       | 3.23%   |
| AMD FCH SATA Controller [IDE mode]                                               | 10       | 3.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9        | 2.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8        | 2.58%   |
| Intel SATA Controller [RAID mode]                                                | 8        | 2.58%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 7        | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7        | 2.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6        | 1.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 6        | 1.94%   |
| AMD 400 Series Chipset SATA Controller                                           | 6        | 1.94%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 5        | 1.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5        | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5        | 1.61%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 5        | 1.61%   |
| AMD 500 Series Chipset SATA Controller                                           | 5        | 1.61%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 4        | 1.29%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4        | 1.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 4        | 1.29%   |
| AMD FCH SATA Controller D                                                        | 4        | 1.29%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3        | 0.97%   |
| Samsung NVMe SSD Controller 980                                                  | 3        | 0.97%   |
| JMicron JMB363 SATA/IDE Controller                                               | 3        | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3        | 0.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3        | 0.97%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 3        | 0.97%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 3        | 0.97%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 3        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3        | 0.97%   |
| Unknown                                                                          | 3        | 0.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2        | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2        | 0.65%   |
| Micron/Crucial NVMe Storage Controller                                           | 2        | 0.65%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                     | 2        | 0.65%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 2        | 0.65%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2        | 0.65%   |
| Intel SSD 660P Series                                                            | 2        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 189      | 68.98%  |
| IDE  | 36       | 13.14%  |
| NVMe | 30       | 10.95%  |
| RAID | 14       | 5.11%   |
| SCSI | 3        | 1.09%   |
| SAS  | 2        | 0.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 168      | 75%     |
| AMD    | 56       | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD GX-412TC SOC                       | 15       | 6.61%   |
| Intel Core i3-4010U CPU @ 1.70GHz      | 5        | 2.2%    |
| Intel Celeron J4125 CPU @ 2.00GHz      | 5        | 2.2%    |
| Intel Celeron N5105 @ 2.00GHz          | 4        | 1.76%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 3        | 1.32%   |
| Intel Core i5-6500T CPU @ 2.50GHz      | 3        | 1.32%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 1.32%   |
| Intel Core i5-4300Y CPU @ 1.60GHz      | 3        | 1.32%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 3        | 1.32%   |
| Intel Core i5-2500K CPU @ 3.30GHz      | 3        | 1.32%   |
| Intel Core i3-3225 CPU @ 3.30GHz       | 3        | 1.32%   |
| Intel Core i3-3220 CPU @ 3.30GHz       | 3        | 1.32%   |
| Intel Core 2 Quad CPU                  | 3        | 1.32%   |
| Intel Celeron CPU J3160 @ 1.60GHz      | 3        | 1.32%   |
| Intel 686-class                        | 3        | 1.32%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 3        | 1.32%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 3        | 1.32%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 3        | 1.32%   |
| AMD G-T40E Processor                   | 3        | 1.32%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz   | 2        | 0.88%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz    | 2        | 0.88%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 2        | 0.88%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 2        | 0.88%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 2        | 0.88%   |
| Intel Core i5-5250U CPU @ 1.60GHz      | 2        | 0.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 2        | 0.88%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 2        | 0.88%   |
| Intel Core i3-6100 CPU @ 3.70GHz       | 2        | 0.88%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz  | 2        | 0.88%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz      | 2        | 0.88%   |
| Intel Atom CPU D525 @ 1.80GHz          | 2        | 0.88%   |
| Intel Atom CPU C3558 @ 2.20GHz         | 2        | 0.88%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 2        | 0.88%   |
| AMD Ryzen 5 3600 6-Core Processor      | 2        | 0.88%   |
| AMD Athlon 5350 APU with Radeon R3     | 2        | 0.88%   |
| Intel Xeon W-2255 CPU @ 3.70GHz        | 1        | 0.44%   |
| Intel Xeon E-2124G CPU @ 3.40GHz       | 1        | 0.44%   |
| Intel Xeon D-2187NT CPU @ 2.00GHz      | 1        | 0.44%   |
| Intel Xeon D-2146NT CPU @ 2.30GHz      | 1        | 0.44%   |
| Intel Xeon CPU X5650 @ 2.67GHz         | 1        | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 43       | 19.03%  |
| Intel Core i3           | 26       | 11.5%   |
| Intel Celeron           | 24       | 10.62%  |
| Intel Xeon              | 18       | 7.96%   |
| AMD GX                  | 18       | 7.96%   |
| Intel Core i7           | 16       | 7.08%   |
| Intel Atom              | 13       | 5.75%   |
| AMD Ryzen 5             | 10       | 4.42%   |
| Other                   | 8        | 3.54%   |
| AMD Ryzen 7             | 8        | 3.54%   |
| Intel Core 2 Quad       | 7        | 3.1%    |
| Intel Pentium           | 6        | 2.65%   |
| Intel 686-class         | 3        | 1.33%   |
| AMD G                   | 3        | 1.33%   |
| Intel Pentium Gold      | 2        | 0.88%   |
| Intel Core 2 Duo        | 2        | 0.88%   |
| AMD Ryzen 3             | 2        | 0.88%   |
| AMD E                   | 2        | 0.88%   |
| AMD Athlon 64 X2        | 2        | 0.88%   |
| AMD Athlon              | 2        | 0.88%   |
| AMD A8                  | 2        | 0.88%   |
| Intel Pentium Silver    | 1        | 0.44%   |
| Intel Pentium Dual-Core | 1        | 0.44%   |
| Intel Genuine           | 1        | 0.44%   |
| Intel Core 2            | 1        | 0.44%   |
| AMD Ryzen 9             | 1        | 0.44%   |
| AMD Phenom II X4        | 1        | 0.44%   |
| AMD FX                  | 1        | 0.44%   |
| AMD E1                  | 1        | 0.44%   |
| AMD A10                 | 1        | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 99       | 44%     |
| 2       | 69       | 30.67%  |
| Unknown | 14       | 6.22%   |
| 6       | 11       | 4.89%   |
| 12      | 10       | 4.44%   |
| 8       | 10       | 4.44%   |
| 16      | 9        | 4%      |
| 32      | 2        | 0.89%   |
| 10      | 1        | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 215      | 95.98%  |
| Unknown | 8        | 3.57%   |
| 2       | 1        | 0.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 137      | 61.16%  |
| 2       | 73       | 32.59%  |
| Unknown | 14       | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 27       | 11.95%  |
| KabyLake      | 23       | 10.18%  |
| IvyBridge     | 19       | 8.41%   |
| Skylake       | 18       | 7.96%   |
| SandyBridge   | 16       | 7.08%   |
| Puma          | 16       | 7.08%   |
| Unknown       | 14       | 6.19%   |
| Silvermont    | 10       | 4.42%   |
| Bonnell       | 8        | 3.54%   |
| Zen 3         | 7        | 3.1%    |
| Zen 2         | 7        | 3.1%    |
| Penryn        | 7        | 3.1%    |
| Broadwell     | 6        | 2.65%   |
| Bobcat        | 6        | 2.65%   |
| Zen+          | 5        | 2.21%   |
| Goldmont plus | 5        | 2.21%   |
| Nehalem       | 4        | 1.77%   |
| Jaguar        | 4        | 1.77%   |
| Goldmont      | 4        | 1.77%   |
| Core          | 4        | 1.77%   |
| Westmere      | 3        | 1.33%   |
| Zen           | 2        | 0.88%   |
| TigerLake     | 2        | 0.88%   |
| Steamroller   | 2        | 0.88%   |
| Piledriver    | 2        | 0.88%   |
| CometLake     | 2        | 0.88%   |
| K8 Hammer     | 1        | 0.44%   |
| K10           | 1        | 0.44%   |
| Excavator     | 1        | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 126      | 63.32%  |
| AMD                        | 33       | 16.58%  |
| Nvidia                     | 27       | 13.57%  |
| ASPEED Technology          | 7        | 3.52%   |
| Matrox Electronics Systems | 6        | 3.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                                    | 11       | 5.5%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10       | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9        | 4.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8        | 4%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7        | 3.5%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 7        | 3.5%    |
| Intel JasperLake [UHD Graphics]                                                          | 6        | 3%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6        | 3%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6        | 3%      |
| Intel HD Graphics 630                                                                    | 5        | 2.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5        | 2.5%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4        | 2%      |
| Intel HD Graphics 620                                                                    | 4        | 2%      |
| Intel HD Graphics 510                                                                    | 4        | 2%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4        | 2%      |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 3        | 1.5%    |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 1.5%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 1.5%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3        | 1.5%    |
| Intel HD Graphics 5500                                                                   | 3        | 1.5%    |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 3        | 1.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 1.5%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3        | 1.5%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 1.5%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 2        | 1%      |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 1%      |
| Intel HD Graphics 6000                                                                   | 2        | 1%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1%      |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 2        | 1%      |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2        | 1%      |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1%      |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 1%      |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 2        | 1%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 1%      |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1        | 0.5%    |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.5%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 0.5%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 0.5%    |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.5%    |
| Nvidia GK107GL [Quadro 410]                                                              | 1        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 120      | 53.1%   |
| 1 x AMD        | 33       | 14.6%   |
| Other          | 28       | 12.39%  |
| 1 x Nvidia     | 26       | 11.5%   |
| 1 x ASPEED     | 7        | 3.1%    |
| 1 x Matrox     | 6        | 2.65%   |
| 2 x Intel      | 5        | 2.21%   |
| Intel + Nvidia | 1        | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 174      | 77.33%  |
| Unknown     | 33       | 14.67%  |
| Proprietary | 18       | 8%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 190      | 84.44%  |
| 0.51-1.0   | 9        | 4%      |
| 1.01-2.0   | 7        | 3.11%   |
| 7.01-8.0   | 6        | 2.67%   |
| 0.01-0.5   | 6        | 2.67%   |
| 5.01-6.0   | 4        | 1.78%   |
| 3.01-4.0   | 2        | 0.89%   |
| 8.01-16.0  | 1        | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 8        | 18.18%  |
| Iiyama               | 4        | 9.09%   |
| Idek Iiyama          | 4        | 9.09%   |
| Hewlett-Packard      | 4        | 9.09%   |
| Samsung Electronics  | 3        | 6.82%   |
| Goldstar             | 3        | 6.82%   |
| Ancor Communications | 3        | 6.82%   |
| Acer                 | 3        | 6.82%   |
| AOC                  | 2        | 4.55%   |
| Sony                 | 1        | 2.27%   |
| PRI                  | 1        | 2.27%   |
| PKB                  | 1        | 2.27%   |
| Philips              | 1        | 2.27%   |
| Packard Bell         | 1        | 2.27%   |
| LG Electronics       | 1        | 2.27%   |
| Lenovo Group Limited | 1        | 2.27%   |
| CKL                  | 1        | 2.27%   |
| BenQ                 | 1        | 2.27%   |
| Apple                | 1        | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Idek Iiyama LCD Monitor PLX2783H 1920x1080                            | 2        | 4.55%   |
| Acer V223HQ ACR0070 1920x1080 470x270mm 21.3-inch                     | 2        | 4.55%   |
| Sony TV  *00 SNYF903 3840x2160 950x540mm 43.0-inch                    | 1        | 2.27%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch   | 1        | 2.27%   |
| Samsung Electronics LCD Monitor SyncMaster 3520x1200                  | 1        | 2.27%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                     | 1        | 2.27%   |
| PRI LED-MONITOR PRI0828 3840x2160 1150x650mm 52.0-inch                | 1        | 2.27%   |
| PKB LCD Monitor MAE200W 1680x1050                                     | 1        | 2.27%   |
| Philips LCD Monitor PHLC00B 1280x1024 340x270mm 17.1-inch             | 1        | 2.27%   |
| Packard Bell Viseo 200Ws PKB00C2 1600x900 440x250mm 19.9-inch         | 1        | 2.27%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 1        | 2.27%   |
| Lenovo Group Limited LCD Monitor LEN P27h-10 2560x1440                | 1        | 2.27%   |
| Iiyama PLX2483H IVM6114 1920x1080 530x300mm 24.0-inch                 | 1        | 2.27%   |
| Iiyama PL2783Q IVM661F 2560x1440 600x340mm 27.2-inch                  | 1        | 2.27%   |
| Iiyama PL2483H IVM6138 1920x1080 530x300mm 24.0-inch                  | 1        | 2.27%   |
| Iiyama PL2474H IVM6137 1920x1080 520x290mm 23.4-inch                  | 1        | 2.27%   |
| Idek Iiyama LCD Monitor PL2409HD 1920x1080                            | 1        | 2.27%   |
| Idek Iiyama LCD Monitor PL2206W 1680x1050                             | 1        | 2.27%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 470x300mm 22.0-inch           | 1        | 2.27%   |
| Hewlett-Packard HPQ 8300 AiO HWP4212 1920x1080 510x290mm 23.1-inch    | 1        | 2.27%   |
| Hewlett-Packard 2310e HWP2909 1920x1080 510x290mm 23.1-inch           | 1        | 2.27%   |
| Hewlett-Packard 2211 HWP2938 1920x1080 480x270mm 21.7-inch            | 1        | 2.27%   |
| Goldstar L1730S GSM438D 1280x1024 340x270mm 17.1-inch                 | 1        | 2.27%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch               | 1        | 2.27%   |
| Goldstar 19MB35 GSM4C23 1280x1024 380x300mm 19.1-inch                 | 1        | 2.27%   |
| Dell U2515H DELD06F 2560x1440 550x310mm 24.9-inch                     | 1        | 2.27%   |
| Dell P2418D DELD0C2 2560x1440 530x300mm 24.0-inch                     | 1        | 2.27%   |
| Dell P1917S DELD092 1280x1024 380x300mm 19.1-inch                     | 1        | 2.27%   |
| Dell P1917S DELD091 1280x1024 380x300mm 19.1-inch                     | 1        | 2.27%   |
| Dell P1911 DELA073 1440x900 410x260mm 19.1-inch                       | 1        | 2.27%   |
| Dell LCD Monitor U2414H                                               | 1        | 2.27%   |
| Dell E2014H DELD03B 1600x900 430x240mm 19.4-inch                      | 1        | 2.27%   |
| Dell E1715S DELD062 1280x1024 340x270mm 17.1-inch                     | 1        | 2.27%   |
| CKL LCD Monitor CKL0001 1920x1200 1150x650mm 52.0-inch                | 1        | 2.27%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 1        | 2.27%   |
| Apple LCD Monitor APP9C73 1280x800 290x180mm 13.4-inch                | 1        | 2.27%   |
| AOC Q2577W AOC2577 2560x1440 550x310mm 24.9-inch                      | 1        | 2.27%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                     | 1        | 2.27%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 520x290mm 23.4-inch | 1        | 2.27%   |
| Ancor Communications ASUS PB238 ACI23A2 1920x1080 510x290mm 23.1-inch | 1        | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 18       | 40.91%  |
| 2560x1440 (QHD)    | 6        | 13.64%  |
| 1280x1024 (SXGA)   | 6        | 13.64%  |
| 1680x1050 (WSXGA+) | 3        | 6.82%   |
| 3840x2160 (4K)     | 2        | 4.55%   |
| 1600x900 (HD+)     | 2        | 4.55%   |
| 1440x900 (WXGA+)   | 2        | 4.55%   |
| 3520x1200          | 1        | 2.27%   |
| 2560x1080          | 1        | 2.27%   |
| 1920x1200 (WUXGA)  | 1        | 2.27%   |
| 1280x800 (WXGA)    | 1        | 2.27%   |
| Unknown            | 1        | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 9        | 20.93%  |
| 19      | 7        | 16.28%  |
| 24      | 6        | 13.95%  |
| 23      | 5        | 11.63%  |
| 21      | 5        | 11.63%  |
| 27      | 3        | 6.98%   |
| 17      | 3        | 6.98%   |
| 52      | 2        | 4.65%   |
| 43      | 1        | 2.33%   |
| 22      | 1        | 2.33%   |
| 13      | 1        | 2.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 14       | 32.56%  |
| 401-500     | 10       | 23.26%  |
| Unknown     | 9        | 20.93%  |
| 351-400     | 3        | 6.98%   |
| 301-350     | 3        | 6.98%   |
| 1001-1500   | 2        | 4.65%   |
| 201-300     | 1        | 2.33%   |
| 901-1000    | 1        | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 24       | 55.81%  |
| Unknown | 9        | 20.93%  |
| 5/4     | 6        | 13.95%  |
| 16/10   | 4        | 9.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 27.91%  |
| 151-200        | 10       | 23.26%  |
| Unknown        | 9        | 20.93%  |
| 301-350        | 3        | 6.98%   |
| 141-150        | 3        | 6.98%   |
| More than 1000 | 2        | 4.65%   |
| 251-300        | 2        | 4.65%   |
| 81-90          | 1        | 2.33%   |
| 501-1000       | 1        | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 21       | 48.84%  |
| 101-120 | 11       | 25.58%  |
| Unknown | 9        | 20.93%  |
| 1-50    | 1        | 2.33%   |
| 121-160 | 1        | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 176      | 77.88%  |
| 1     | 49       | 21.68%  |
| 2     | 1        | 0.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 157      | 50.16%  |
| Realtek Semiconductor           | 96       | 30.67%  |
| Qualcomm Atheros                | 17       | 5.43%   |
| Broadcom                        | 17       | 5.43%   |
| Ralink Technology               | 2        | 0.64%   |
| Qualcomm                        | 2        | 0.64%   |
| Huawei Technologies             | 2        | 0.64%   |
| D-Link System                   | 2        | 0.64%   |
| Chelsio Communications          | 2        | 0.64%   |
| VIA Technologies                | 1        | 0.32%   |
| TP-Link                         | 1        | 0.32%   |
| Samsung Electronics             | 1        | 0.32%   |
| Ralink                          | 1        | 0.32%   |
| Qualcomm Atheros Communications | 1        | 0.32%   |
| QLogic                          | 1        | 0.32%   |
| Microchip Technology            | 1        | 0.32%   |
| Mellanox Technologies           | 1        | 0.32%   |
| MediaTek                        | 1        | 0.32%   |
| Emulex                          | 1        | 0.32%   |
| Edimax Technology               | 1        | 0.32%   |
| Aquantia                        | 1        | 0.32%   |
| American Megatrends             | 1        | 0.32%   |
| AMD                             | 1        | 0.32%   |
| Accton Technology               | 1        | 0.32%   |
| 3Com                            | 1        | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 87       | 22.54%  |
| Intel I211 Gigabit Network Connection                                         | 37       | 9.59%   |
| Intel 82574L Gigabit Network Connection                                       | 21       | 5.44%   |
| Intel I210 Gigabit Network Connection                                         | 19       | 4.92%   |
| Intel I350 Gigabit Network Connection                                         | 10       | 2.59%   |
| Intel Ethernet Controller I225-V                                              | 10       | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 2.59%   |
| Realtek RTL8125 2.5GbE Controller                                             | 8        | 2.07%   |
| Intel Wi-Fi 6 AX200                                                           | 7        | 1.81%   |
| Intel Ethernet Connection I217-LM                                             | 7        | 1.81%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6        | 1.55%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6        | 1.55%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 1.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 5        | 1.3%    |
| Intel 82579V Gigabit Network Connection                                       | 5        | 1.3%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 4        | 1.04%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4        | 1.04%   |
| Intel Ethernet Controller I226-V                                              | 4        | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 3        | 0.78%   |
| Intel Ethernet Connection X553 1GbE                                           | 3        | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 0.78%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.78%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 3        | 0.78%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.52%   |
| Ralink RT5370 Wireless Adapter                                                | 2        | 0.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 0.52%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.52%   |
| Qualcomm ALCATEL RNDIS Interface                                              | 2        | 0.52%   |
| Intel Wireless-AC 9260                                                        | 2        | 0.52%   |
| Intel Wireless 7260                                                           | 2        | 0.52%   |
| Intel Wireless 3165                                                           | 2        | 0.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 2        | 0.52%   |
| Intel Ethernet Controller X550                                                | 2        | 0.52%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 2        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.52%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.52%   |
| Intel Centrino Advanced-N 6235                                                | 2        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 26       | 43.33%  |
| Qualcomm Atheros                | 13       | 21.67%  |
| Realtek Semiconductor           | 11       | 18.33%  |
| Ralink Technology               | 2        | 3.33%   |
| Broadcom                        | 2        | 3.33%   |
| TP-Link                         | 1        | 1.67%   |
| Ralink                          | 1        | 1.67%   |
| Qualcomm Atheros Communications | 1        | 1.67%   |
| MediaTek                        | 1        | 1.67%   |
| Edimax Technology               | 1        | 1.67%   |
| Accton Technology               | 1        | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 7        | 11.67%  |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 5        | 8.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 4        | 6.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 3        | 5%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 3        | 5%      |
| Ralink RT5370 Wireless Adapter                                  | 2        | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 2        | 3.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 2        | 3.33%   |
| Intel Wireless-AC 9260                                          | 2        | 3.33%   |
| Intel Wireless 7260                                             | 2        | 3.33%   |
| Intel Wireless 3165                                             | 2        | 3.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 2        | 3.33%   |
| Intel Centrino Advanced-N 6235                                  | 2        | 3.33%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 1        | 1.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 1        | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 1        | 1.67%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1        | 1.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                     | 1        | 1.67%   |
| Realtek RTL8191SEvA Wireless LAN Controller                     | 1        | 1.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 1        | 1.67%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 1        | 1.67%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                       | 1        | 1.67%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1        | 1.67%   |
| Qualcomm Atheros AR9271 802.11n                                 | 1        | 1.67%   |
| MediaTek 802.11ac Wireless LAN Card                             | 1        | 1.67%   |
| Intel Wireless 7265                                             | 1        | 1.67%   |
| Intel Wireless 3160                                             | 1        | 1.67%   |
| Intel Wi-Fi 6 AX201 160MHz                                      | 1        | 1.67%   |
| Intel Wi-Fi 6 AX201                                             | 1        | 1.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection           | 1        | 1.67%   |
| Intel Alder Lake-S PCH CNVi WiFi                                | 1        | 1.67%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 1        | 1.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter              | 1        | 1.67%   |
| Broadcom BCM43224 802.11a/b/g/n                                 | 1        | 1.67%   |
| Accton Arcadyan 802.11N Wireless Adapter                        | 1        | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 147      | 54.04%  |
| Realtek Semiconductor  | 92       | 33.82%  |
| Broadcom               | 15       | 5.51%   |
| Qualcomm Atheros       | 4        | 1.47%   |
| Qualcomm               | 2        | 0.74%   |
| D-Link System          | 2        | 0.74%   |
| Chelsio Communications | 2        | 0.74%   |
| VIA Technologies       | 1        | 0.37%   |
| Samsung Electronics    | 1        | 0.37%   |
| QLogic                 | 1        | 0.37%   |
| Emulex                 | 1        | 0.37%   |
| Aquantia               | 1        | 0.37%   |
| American Megatrends    | 1        | 0.37%   |
| AMD                    | 1        | 0.37%   |
| 3Com                   | 1        | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 87       | 27.1%   |
| Intel I211 Gigabit Network Connection                                         | 37       | 11.53%  |
| Intel 82574L Gigabit Network Connection                                       | 21       | 6.54%   |
| Intel I210 Gigabit Network Connection                                         | 19       | 5.92%   |
| Intel I350 Gigabit Network Connection                                         | 10       | 3.12%   |
| Intel Ethernet Controller I225-V                                              | 10       | 3.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 3.12%   |
| Realtek RTL8125 2.5GbE Controller                                             | 8        | 2.49%   |
| Intel Ethernet Connection I217-LM                                             | 7        | 2.18%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6        | 1.87%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6        | 1.87%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 1.87%   |
| Intel 82579V Gigabit Network Connection                                       | 5        | 1.56%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4        | 1.25%   |
| Intel Ethernet Controller I226-V                                              | 4        | 1.25%   |
| Intel Ethernet Connection X553 1GbE                                           | 3        | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 0.93%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 0.93%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.93%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 3        | 0.93%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.62%   |
| Qualcomm ALCATEL RNDIS Interface                                              | 2        | 0.62%   |
| Intel Ethernet Controller X550                                                | 2        | 0.62%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 2        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.62%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.62%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 0.62%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 0.62%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 2        | 0.62%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 2        | 0.62%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.62%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1        | 0.31%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1        | 0.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.31%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.31%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.31%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 0.31%   |
| Intel Platform Controller Hub EG20T Gigabit Ethernet Controller               | 1        | 0.31%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 1        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 223      | 77.97%  |
| WiFi     | 58       | 20.28%  |
| Unknown  | 4        | 1.4%    |
| Modem    | 1        | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 209      | 98.12%  |
| WiFi     | 4        | 1.88%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 54       | 23.89%  |
| 2     | 49       | 21.68%  |
| 4     | 48       | 21.24%  |
| 3     | 37       | 16.37%  |
| 5     | 15       | 6.64%   |
| 6     | 8        | 3.54%   |
| 8     | 5        | 2.21%   |
| 7     | 5        | 2.21%   |
| 13    | 1        | 0.44%   |
| 12    | 1        | 0.44%   |
| 11    | 1        | 0.44%   |
| 10    | 1        | 0.44%   |
| 0     | 1        | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 176      | 75.54%  |
| Yes  | 57       | 24.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 20       | 68.97%  |
| Cambridge Silicon Radio  | 3        | 10.34%  |
| Broadcom                 | 2        | 6.9%    |
| Realtek Semiconductor    | 1        | 3.45%   |
| HTC (High Tech Computer) | 1        | 3.45%   |
| Hewlett-Packard          | 1        | 3.45%   |
| ASUSTek Computer         | 1        | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 5        | 17.24%  |
| Intel Bluetooth wireless interface                                   | 4        | 13.79%  |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 10.34%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 3        | 10.34%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 2        | 6.9%    |
| Intel AX210 Bluetooth                                                | 2        | 6.9%    |
| Intel AX201 Bluetooth                                                | 2        | 6.9%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 6.9%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 3.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 3.45%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 3.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 1        | 3.45%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 124      | 60.78%  |
| AMD                                          | 40       | 19.61%  |
| Nvidia                                       | 24       | 11.76%  |
| Focusrite-Novation                           | 2        | 0.98%   |
| Creative Labs                                | 2        | 0.98%   |
| C-Media Electronics                          | 2        | 0.98%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.49%   |
| VIA Technologies                             | 1        | 0.49%   |
| Texas Instruments                            | 1        | 0.49%   |
| Sony                                         | 1        | 0.49%   |
| Micronas                                     | 1        | 0.49%   |
| Logitech                                     | 1        | 0.49%   |
| Kingston Technology                          | 1        | 0.49%   |
| iCreate Technologies                         | 1        | 0.49%   |
| Giga-Byte Technology                         | 1        | 0.49%   |
| ESS Technology                               | 1        | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13       | 5.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 13       | 5.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12       | 4.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12       | 4.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10       | 4.03%   |
| Intel 200 Series PCH HD Audio                                                                     | 10       | 4.03%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9        | 3.63%   |
| Intel 8 Series HD Audio Controller                                                                | 8        | 3.23%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 8        | 3.23%   |
| AMD FCH Azalia Controller                                                                         | 8        | 3.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6        | 2.42%   |
| Intel Jasper Lake HD Audio                                                                        | 6        | 2.42%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5        | 2.02%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5        | 2.02%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5        | 2.02%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5        | 2.02%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5        | 2.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5        | 2.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4        | 1.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4        | 1.61%   |
| Intel Broadwell-U Audio Controller                                                                | 4        | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4        | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4        | 1.61%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3        | 1.21%   |
| Nvidia High Definition Audio Controller                                                           | 3        | 1.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3        | 1.21%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 1.21%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3        | 1.21%   |
| AMD Wrestler HDMI Audio                                                                           | 3        | 1.21%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2        | 0.81%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 2        | 0.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2        | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2        | 0.81%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 2        | 0.81%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 2        | 0.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2        | 0.81%   |
| AMD Navi 10 HDMI Audio                                                                            | 2        | 0.81%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2        | 0.81%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 0.81%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 30       | 14.71%  |
| SK hynix            | 28       | 13.73%  |
| Kingston            | 27       | 13.24%  |
| Corsair             | 25       | 12.25%  |
| Unknown             | 24       | 11.76%  |
| G.Skill             | 19       | 9.31%   |
| Crucial             | 18       | 8.82%   |
| Micron Technology   | 10       | 4.9%    |
| Unknown             | 4        | 1.96%   |
| Transcend           | 3        | 1.47%   |
| Nanya Technology    | 3        | 1.47%   |
| Kimtigo             | 2        | 0.98%   |
| Elpida              | 2        | 0.98%   |
| Atermiter           | 2        | 0.98%   |
| Unknown (0B38)      | 1        | 0.49%   |
| Teikon              | 1        | 0.49%   |
| Patriot             | 1        | 0.49%   |
| OCZ                 | 1        | 0.49%   |
| Hewlett-Packard     | 1        | 0.49%   |
| Goldenmars          | 1        | 0.49%   |
| Apacer              | 1        | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 5        | 2.31%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 4        | 1.85%   |
| Unknown                                                 | 4        | 1.85%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s    | 3        | 1.39%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 1600MT/s     | 3        | 1.39%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 3        | 1.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 2        | 0.93%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 2        | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s              | 2        | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s             | 2        | 0.93%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 2        | 0.93%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 2        | 0.93%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3             | 2        | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s  | 2        | 0.93%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s             | 2        | 0.93%   |
| Samsung RAM M393A4K40CB2-CTD 32GB DIMM DDR4 2667MT/s    | 2        | 0.93%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s     | 2        | 0.93%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s     | 2        | 0.93%   |
| Micron RAM 8HTF12864AZ-800H1 1GB DIMM DDR2 800MT/s      | 2        | 0.93%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 2666MT/s     | 2        | 0.93%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 2        | 0.93%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s   | 2        | 0.93%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s          | 2        | 0.93%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3200MT/s    | 2        | 0.93%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s | 2        | 0.93%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s     | 2        | 0.93%   |
| Corsair RAM CMV8GX4M1A2133C15 8GB DIMM DDR4 2133MT/s    | 2        | 0.93%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1333MT/s     | 2        | 0.93%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 2133MT/s  | 2        | 0.93%   |
| Atermiter RAM Module 8GB DIMM DDR3 800MT/s              | 2        | 0.93%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s            | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR3 1332MT/s               | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM 667MT/s                     | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM 400MT/s                     | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                    | 1        | 0.46%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s            | 1        | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                | 1        | 0.46%   |
| Unknown RAM Module 1GB DIMM 667MT/s                     | 1        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 90       | 48.65%  |
| DDR4    | 77       | 41.62%  |
| Unknown | 12       | 6.49%   |
| DDR2    | 6        | 3.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 126      | 68.48%  |
| SODIMM  | 57       | 30.98%  |
| Unknown | 1        | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 71       | 36.22%  |
| 4096  | 66       | 33.67%  |
| 2048  | 30       | 15.31%  |
| 16384 | 17       | 8.67%   |
| 1024  | 7        | 3.57%   |
| 32768 | 5        | 2.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 53       | 27.75%  |
| 1333  | 34       | 17.8%   |
| 3200  | 20       | 10.47%  |
| 2400  | 19       | 9.95%   |
| 2133  | 16       | 8.38%   |
| 2667  | 15       | 7.85%   |
| 800   | 11       | 5.76%   |
| 2666  | 7        | 3.66%   |
| 1066  | 4        | 2.09%   |
| 667   | 3        | 1.57%   |
| 1334  | 2        | 1.05%   |
| 5200  | 1        | 0.52%   |
| 3000  | 1        | 0.52%   |
| 1400  | 1        | 0.52%   |
| 1332  | 1        | 0.52%   |
| 1067  | 1        | 0.52%   |
| 533   | 1        | 0.52%   |
| 400   | 1        | 0.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 50%     |
| Dymo-CoStar | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Seiko Epson Printer         | 1        | 50%     |
| Dymo-CoStar LabelWriter 450 | 1        | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LIDE 25 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 3        | 60%     |
| ValueHD                  | 1        | 20%     |
| Novatek Microelectronics | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 2        | 40%     |
| ValueHD HD Camera                     | 1        | 20%     |
| Novatek HP High Definition 2MP Webcam | 1        | 20%     |
| Logitech C922 Pro Stream Webcam       | 1        | 20%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Upek      | 1        | 50%     |
| AuthenTec | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 50%     |
| AuthenTec AES2501 Fingerprint Sensor                   | 1        | 50%     |

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
| 1     | 117      | 51.54%  |
| 0     | 74       | 32.6%   |
| 2     | 25       | 11.01%  |
| 3     | 10       | 4.41%   |
| 4     | 1        | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 130      | 69.52%  |
| Net/wireless             | 22       | 11.76%  |
| Bluetooth                | 12       | 6.42%   |
| Firewire controller      | 8        | 4.28%   |
| Net/ethernet             | 5        | 2.67%   |
| Sound                    | 4        | 2.14%   |
| Graphics card            | 2        | 1.07%   |
| Storage                  | 1        | 0.53%   |
| Network                  | 1        | 0.53%   |
| Modem                    | 1        | 0.53%   |
| Card reader              | 1        | 0.53%   |

