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

Total: 253

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| ASUSTek       | PRIME B550M-A               | [40cd6d1472](https://bsd-hardware.info/?probe=40cd6d1472) | Mar 19, 2022 |
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
| ASUSTek       | M2NPV-MX                    | [45e53e33d8](https://bsd-hardware.info/?probe=45e53e33d8) | Jan 23, 2021 |
| Unknown       | Unknown                     | [4c4d549584](https://bsd-hardware.info/?probe=4c4d549584) | Jan 22, 2021 |
| ASUSTek       | M2NPV-MX                    | [ae29fe5691](https://bsd-hardware.info/?probe=ae29fe5691) | Jan 22, 2021 |
| ASUSTek       | M2NPV-MX                    | [bdd89d655d](https://bsd-hardware.info/?probe=bdd89d655d) | Jan 22, 2021 |
| ASUSTek       | M2NPV-MX                    | [006cafaa6b](https://bsd-hardware.info/?probe=006cafaa6b) | Jan 22, 2021 |
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


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| OPNsense 21.1.5              | 13       | 6.28%   |
| OPNsense 21.7.7              | 10       | 4.83%   |
| OpenBSD 6.8                  | 9        | 4.35%   |
| OPNsense 22.1.6              | 8        | 3.86%   |
| OPNsense 22.7                | 6        | 2.9%    |
| OPNsense 22.1.10             | 6        | 2.9%    |
| OPNsense 22.1.1              | 6        | 2.9%    |
| OPNsense 22.1                | 6        | 2.9%    |
| OPNsense 21.7.1              | 6        | 2.9%    |
| OPNsense 21.1.3              | 6        | 2.9%    |
| OPNsense 21.1                | 6        | 2.9%    |
| OPNsense 22.1.2              | 5        | 2.42%   |
| helloSystem 0.5.0            | 5        | 2.42%   |
| GhostBSD 20.04.02            | 5        | 2.42%   |
| OPNsense 22.1.3              | 4        | 1.93%   |
| OPNsense 21.7.5              | 4        | 1.93%   |
| OPNsense 21.7.3              | 4        | 1.93%   |
| OPNsense 21.7                | 4        | 1.93%   |
| OPNsense 20.7.8              | 4        | 1.93%   |
| helloSystem 0.4.0            | 4        | 1.93%   |
| FreeBSD 13.1                 | 4        | 1.93%   |
| FreeBSD 12.1-p8              | 4        | 1.93%   |
| OPNsense 22.1.5              | 3        | 1.45%   |
| OPNsense 21.7.8              | 3        | 1.45%   |
| OPNsense 21.7.4              | 3        | 1.45%   |
| OPNsense 21.1.7              | 3        | 1.45%   |
| OPNsense 21.1.4              | 3        | 1.45%   |
| OpenBSD 6.9                  | 3        | 1.45%   |
| NomadBSD 1.3.2               | 3        | 1.45%   |
| helloSystem 0.7.0            | 3        | 1.45%   |
| FreeBSD 13.0-p4              | 3        | 1.45%   |
| FreeBSD 13.0-p11             | 3        | 1.45%   |
| FreeBSD 13.0                 | 3        | 1.45%   |
| FreeBSD 12.1-STABLE          | 3        | 1.45%   |
| OPNsense 22.7.1              | 2        | 0.97%   |
| OPNsense 22.1.4              | 2        | 0.97%   |
| OPNsense 21.1.6              | 2        | 0.97%   |
| OPNsense 21.1.1              | 2        | 0.97%   |
| helloSystem 0.8.0            | 2        | 0.97%   |
| FreeBSD 13.1-BETA2           | 2        | 0.97%   |
| FreeBSD 12.2-p4              | 2        | 0.97%   |
| TrueNAS 12.2-p11             | 1        | 0.48%   |
| OPNsense 22.1.9              | 1        | 0.48%   |
| OPNsense 22.1.8              | 1        | 0.48%   |
| OPNsense 21.7.6              | 1        | 0.48%   |
| OPNsense 21.7.2              | 1        | 0.48%   |
| OPNsense 21.1.8              | 1        | 0.48%   |
| OPNsense 20.7.5              | 1        | 0.48%   |
| OpenBSD 7.0                  | 1        | 0.48%   |
| NetBSD 9.2                   | 1        | 0.48%   |
| NetBSD 9.1                   | 1        | 0.48%   |
| HardenedBSD 13.0-STABLE-HBSD | 1        | 0.48%   |
| FreeNAS 11.3-p7              | 1        | 0.48%   |
| FreeBSD 14.0-CURRENT         | 1        | 0.48%   |
| FreeBSD 13.1-STABLE          | 1        | 0.48%   |
| FreeBSD 13.1-RC6             | 1        | 0.48%   |
| FreeBSD 13.0-STABLE          | 1        | 0.48%   |
| FreeBSD 13.0-p5              | 1        | 0.48%   |
| FreeBSD 12.2-p3              | 1        | 0.48%   |
| FreeBSD 12.2-p2              | 1        | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 90       | 54.22%  |
| FreeBSD     | 38       | 22.89%  |
| helloSystem | 14       | 8.43%   |
| OpenBSD     | 11       | 6.63%   |
| GhostBSD    | 5        | 3.01%   |
| NomadBSD    | 3        | 1.81%   |
| NetBSD      | 2        | 1.2%    |
| TrueNAS     | 1        | 0.6%    |
| HardenedBSD | 1        | 0.6%    |
| FreeNAS     | 1        | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 164      | 99.39%  |
| i386  | 1        | 0.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 120      | 71.86%  |
| helloDesktop | 16       | 9.58%   |
| XFCE         | 12       | 7.19%   |
| MATE         | 5        | 2.99%   |
| Openbox      | 3        | 1.8%    |
| KDE5         | 3        | 1.8%    |
| fvwm         | 3        | 1.8%    |
| GNOME        | 2        | 1.2%    |
| TWM          | 1        | 0.6%    |
| Cinnamon     | 1        | 0.6%    |
| AwesomeWM    | 1        | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 122      | 73.94%  |
| X11     | 42       | 25.45%  |
| Wayland | 1        | 0.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 130      | 78.31%  |
| SLiM    | 21       | 12.65%  |
| LightDM | 8        | 4.82%   |
| SDDM    | 4        | 2.41%   |
| XDM     | 2        | 1.2%    |
| GDM     | 1        | 0.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 119      | 71.69%  |
| en_US          | 21       | 12.65%  |
| C              | 13       | 7.83%   |
| fr_FR          | 12       | 7.23%   |
| fr_FR.US-ASCII | 1        | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 124      | 74.25%  |
| BIOS | 43       | 25.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 89       | 52.98%  |
| Zfs    | 65       | 38.69%  |
| Ffs    | 11       | 6.55%   |
| Cd9660 | 3        | 1.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 143      | 85.63%  |
| MBR     | 23       | 13.77%  |
| Unknown | 1        | 0.6%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 27       | 16.36%  |
| Intel               | 18       | 10.91%  |
| PC Engines          | 16       | 9.7%    |
| Dell                | 16       | 9.7%    |
| Gigabyte Technology | 14       | 8.48%   |
| Unknown             | 14       | 8.48%   |
| ASRock              | 10       | 6.06%   |
| Hewlett-Packard     | 9        | 5.45%   |
| MSI                 | 8        | 4.85%   |
| Supermicro          | 6        | 3.64%   |
| Shuttle             | 2        | 1.21%   |
| RUNING              | 2        | 1.21%   |
| Protectli           | 2        | 1.21%   |
| Lenovo              | 2        | 1.21%   |
| Fujitsu             | 2        | 1.21%   |
| ASRockRack          | 2        | 1.21%   |
| AMD                 | 2        | 1.21%   |
| ZOTAC               | 1        | 0.61%   |
| Wistron             | 1        | 0.61%   |
| VeryPC              | 1        | 0.61%   |
| Pegatron            | 1        | 0.61%   |
| Packard Bell        | 1        | 0.61%   |
| MW                  | 1        | 0.61%   |
| Jetway              | 1        | 0.61%   |
| Google              | 1        | 0.61%   |
| Deciso              | 1        | 0.61%   |
| CNCTION-IAF-E3845   | 1        | 0.61%   |
| AZW                 | 1        | 0.61%   |
| Acer                | 1        | 0.61%   |
| AAEON               | 1        | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| Unknown                                  | 15       | 9.09%   |
| PC Engines APU2                          | 9        | 5.45%   |
| Intel Q3XXG4-P V1.0                      | 9        | 5.45%   |
| PC Engines APU3                          | 3        | 1.82%   |
| Dell OptiPlex 9020                       | 3        | 1.82%   |
| ASUS All Series                          | 3        | 1.82%   |
| RUNING B75M INTEL H3V                    | 2        | 1.21%   |
| PC Engines apu4                          | 2        | 1.21%   |
| HP ProLiant MicroServer Gen8             | 2        | 1.21%   |
| Gigabyte X570 I AORUS PRO WIFI           | 2        | 1.21%   |
| Dell OptiPlex 3010                       | 2        | 1.21%   |
| ASUS Z170-P D3                           | 2        | 1.21%   |
| ASUS PRIME B450M-A                       | 2        | 1.21%   |
| ASUS P8Z68-V LX                          | 2        | 1.21%   |
| ZOTAC XXXXXX                             | 1        | 0.61%   |
| Wistron ProLiant ML110 G6                | 1        | 0.61%   |
| VeryPC S400-K7-N-O                       | 1        | 0.61%   |
| Supermicro X8STi                         | 1        | 0.61%   |
| Supermicro X7SPA-HF                      | 1        | 0.61%   |
| Supermicro X10SLH-N6-ST031               | 1        | 0.61%   |
| Supermicro SYS-E300-9D-8CN8TP            | 1        | 0.61%   |
| Supermicro SYS-E300-9A-4C                | 1        | 0.61%   |
| Supermicro SYS-5019A-FTN4                | 1        | 0.61%   |
| Shuttle NC10U                            | 1        | 0.61%   |
| Shuttle DS61                             | 1        | 0.61%   |
| Protectli VP2410                         | 1        | 0.61%   |
| Protectli FW6                            | 1        | 0.61%   |
| Pegatron Elite 7300 Series MT            | 1        | 0.61%   |
| PC Engines apu1                          | 1        | 0.61%   |
| PC Engines APU                           | 1        | 0.61%   |
| Packard Bell imedia S2110                | 1        | 0.61%   |
| MW GMLK-2_5G4L                           | 1        | 0.61%   |
| MSI MS-9A68                              | 1        | 0.61%   |
| MSI MS-9A45                              | 1        | 0.61%   |
| MSI MS-7C09                              | 1        | 0.61%   |
| MSI MS-7C02                              | 1        | 0.61%   |
| MSI MS-7B24                              | 1        | 0.61%   |
| MSI MS-7887                              | 1        | 0.61%   |
| MSI MS-7758                              | 1        | 0.61%   |
| MSI MS-7253                              | 1        | 0.61%   |
| Lenovo ThinkSystem ST50 7Y48CTO1WW       | 1        | 0.61%   |
| Lenovo ThinkCentre M93p 10A8S0CE09       | 1        | 0.61%   |
| Jetway 1.0                               | 1        | 0.61%   |
| Intel SKYBAY                             | 1        | 0.61%   |
| Intel REXBOX                             | 1        | 0.61%   |
| Intel DN2800MT AAG81515-900              | 1        | 0.61%   |
| Intel DH67BL AAG10189-213                | 1        | 0.61%   |
| Intel DH61AGL                            | 1        | 0.61%   |
| Intel DH61AG AAG23736-505                | 1        | 0.61%   |
| Intel D945GCLF2 AAE46416-104             | 1        | 0.61%   |
| Intel D2500HN                            | 1        | 0.61%   |
| Intel CARLOW                             | 1        | 0.61%   |
| HP ProDesk 600 G2 DM                     | 1        | 0.61%   |
| HP Desktop M01-F0xxx                     | 1        | 0.61%   |
| HP Compaq Elite 8300 Touch All-in-One PC | 1        | 0.61%   |
| HP Compaq Elite 8300 SFF                 | 1        | 0.61%   |
| HP Compaq dc7900 Small Form Factor       | 1        | 0.61%   |
| HP Compaq dc7900 Convertible Minitower   | 1        | 0.61%   |
| HP 860-012nf                             | 1        | 0.61%   |
| Google Guado                             | 1        | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Unknown                       | 15       | 9.09%   |
| Dell OptiPlex                 | 12       | 7.27%   |
| PC Engines APU2               | 9        | 5.45%   |
| Intel Q3XXG4-P                | 9        | 5.45%   |
| ASUS PRIME                    | 6        | 3.64%   |
| HP Compaq                     | 4        | 2.42%   |
| PC Engines APU3               | 3        | 1.82%   |
| ASUS All                      | 3        | 1.82%   |
| RUNING B75M                   | 2        | 1.21%   |
| PC Engines apu4               | 2        | 1.21%   |
| HP ProLiant                   | 2        | 1.21%   |
| Gigabyte X570                 | 2        | 1.21%   |
| ASUS Z170-P                   | 2        | 1.21%   |
| ASUS P8Z68-V                  | 2        | 1.21%   |
| ZOTAC XXXXXX                  | 1        | 0.61%   |
| Wistron ProLiant              | 1        | 0.61%   |
| VeryPC S400-K7-N-O            | 1        | 0.61%   |
| Supermicro X8STi              | 1        | 0.61%   |
| Supermicro X7SPA-HF           | 1        | 0.61%   |
| Supermicro X10SLH-N6-ST031    | 1        | 0.61%   |
| Supermicro SYS-E300-9D-8CN8TP | 1        | 0.61%   |
| Supermicro SYS-E300-9A-4C     | 1        | 0.61%   |
| Supermicro SYS-5019A-FTN4     | 1        | 0.61%   |
| Shuttle NC10U                 | 1        | 0.61%   |
| Shuttle DS61                  | 1        | 0.61%   |
| Protectli VP2410              | 1        | 0.61%   |
| Protectli FW6                 | 1        | 0.61%   |
| Pegatron Elite                | 1        | 0.61%   |
| PC Engines apu1               | 1        | 0.61%   |
| PC Engines APU                | 1        | 0.61%   |
| Packard Bell imedia           | 1        | 0.61%   |
| MW GMLK-2                     | 1        | 0.61%   |
| MSI MS-9A68                   | 1        | 0.61%   |
| MSI MS-9A45                   | 1        | 0.61%   |
| MSI MS-7C09                   | 1        | 0.61%   |
| MSI MS-7C02                   | 1        | 0.61%   |
| MSI MS-7B24                   | 1        | 0.61%   |
| MSI MS-7887                   | 1        | 0.61%   |
| MSI MS-7758                   | 1        | 0.61%   |
| MSI MS-7253                   | 1        | 0.61%   |
| Lenovo ThinkSystem            | 1        | 0.61%   |
| Lenovo ThinkCentre            | 1        | 0.61%   |
| Jetway 1.0                    | 1        | 0.61%   |
| Intel SKYBAY                  | 1        | 0.61%   |
| Intel REXBOX                  | 1        | 0.61%   |
| Intel DN2800MT                | 1        | 0.61%   |
| Intel DH67BL                  | 1        | 0.61%   |
| Intel DH61AGL                 | 1        | 0.61%   |
| Intel DH61AG                  | 1        | 0.61%   |
| Intel D945GCLF2               | 1        | 0.61%   |
| Intel D2500HN                 | 1        | 0.61%   |
| Intel CARLOW                  | 1        | 0.61%   |
| HP ProDesk                    | 1        | 0.61%   |
| HP Desktop                    | 1        | 0.61%   |
| HP 860-012nf                  | 1        | 0.61%   |
| Google Guado                  | 1        | 0.61%   |
| Gigabyte Z97P-D3              | 1        | 0.61%   |
| Gigabyte Z690I                | 1        | 0.61%   |
| Gigabyte X79-UD3              | 1        | 0.61%   |
| Gigabyte X58A-UD5             | 1        | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2016    | 30       | 18.18%  |
| 2019    | 21       | 12.73%  |
| 2018    | 17       | 10.3%   |
| 2012    | 15       | 9.09%   |
| 2020    | 13       | 7.88%   |
| 2013    | 13       | 7.88%   |
| 2014    | 9        | 5.45%   |
| 2021    | 8        | 4.85%   |
| 2017    | 7        | 4.24%   |
| 2015    | 7        | 4.24%   |
| 2010    | 6        | 3.64%   |
| 2011    | 4        | 2.42%   |
| 2009    | 4        | 2.42%   |
| 2008    | 3        | 1.82%   |
| Unknown | 3        | 1.82%   |
| 2022    | 2        | 1.21%   |
| 2007    | 2        | 1.21%   |
| 2006    | 1        | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 165      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 147      | 89.09%  |
| Yes  | 18       | 10.91%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 54       | 32.73%  |
| 4.01-8.0    | 48       | 29.09%  |
| 16.01-24.0  | 37       | 22.42%  |
| 32.01-64.0  | 9        | 5.45%   |
| 2.01-3.0    | 8        | 4.85%   |
| 64.01-256.0 | 5        | 3.03%   |
| 1.01-2.0    | 3        | 1.82%   |
| 3.01-4.0    | 1        | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 92       | 55.42%  |
| 0.51-1.0   | 45       | 27.11%  |
| 1.01-2.0   | 14       | 8.43%   |
| 2.01-3.0   | 5        | 3.01%   |
| 4.01-8.0   | 4        | 2.41%   |
| 3.01-4.0   | 2        | 1.2%    |
| Unknown    | 2        | 1.2%    |
| 16.01-24.0 | 1        | 0.6%    |
| 8.01-16.0  | 1        | 0.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 105      | 62.87%  |
| 2      | 20       | 11.98%  |
| 3      | 16       | 9.58%   |
| 0      | 14       | 8.38%   |
| 5      | 4        | 2.4%    |
| 4      | 4        | 2.4%    |
| 6      | 2        | 1.2%    |
| 10     | 1        | 0.6%    |
| 8      | 1        | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 141      | 84.43%  |
| Yes       | 26       | 15.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 164      | 99.39%  |
| No        | 1        | 0.61%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 122      | 73.49%  |
| Yes       | 44       | 26.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 143      | 86.67%  |
| Yes       | 22       | 13.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| France  | 165      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                         | Desktops | Percent |
|------------------------------|----------|---------|
| Paris                        | 38       | 20.88%  |
| Toulouse                     | 5        | 2.75%   |
| Roubaix                      | 5        | 2.75%   |
| Soisy-sur-Seine              | 4        | 2.2%    |
| Vaulx-en-Velin               | 3        | 1.65%   |
| Montfermeil                  | 3        | 1.65%   |
| Lyon                         | 3        | 1.65%   |
| Agen                         | 3        | 1.65%   |
| Г‰chirolles               | 2        | 1.1%    |
| Villeurbanne                 | 2        | 1.1%    |
| Seyssinet-Pariset            | 2        | 1.1%    |
| Saint-Martin-d'HГЁres      | 2        | 1.1%    |
| Saint-Denis                  | 2        | 1.1%    |
| Rennes                       | 2        | 1.1%    |
| Pau                          | 2        | 1.1%    |
| Marseille                    | 2        | 1.1%    |
| Lille                        | 2        | 1.1%    |
| Fougeres                     | 2        | 1.1%    |
| Escaudain                    | 2        | 1.1%    |
| Bordeaux                     | 2        | 1.1%    |
| Ã‰tampes                  | 2        | 1.1%    |
| Yerres                       | 1        | 0.55%   |
| Villaz                       | 1        | 0.55%   |
| Vichy                        | 1        | 0.55%   |
| Vénissieux                  | 1        | 0.55%   |
| Vauvillers                   | 1        | 0.55%   |
| Vauclerc                     | 1        | 0.55%   |
| Thionville                   | 1        | 0.55%   |
| Teteghem                     | 1        | 0.55%   |
| Strasbourg                   | 1        | 0.55%   |
| Schiltigheim                 | 1        | 0.55%   |
| Sallanches                   | 1        | 0.55%   |
| Salagnon                     | 1        | 0.55%   |
| Sainte-Foy-les-Lyon          | 1        | 0.55%   |
| Saint-Г‰tienne-du-Rouvray | 1        | 0.55%   |
| Saint-Martin-sur-Oust        | 1        | 0.55%   |
| Saint-Mande                  | 1        | 0.55%   |
| Saint-Laurent-de-Ceris       | 1        | 0.55%   |
| Saint-Herblain               | 1        | 0.55%   |
| Saint-Denis-de-Pile          | 1        | 0.55%   |
| Sable-sur-Sarthe             | 1        | 0.55%   |
| Roissy-en-Brie               | 1        | 0.55%   |
| Rochefort                    | 1        | 0.55%   |
| Rillieux-la-Pape             | 1        | 0.55%   |
| RezГ©                      | 1        | 0.55%   |
| Quevert                      | 1        | 0.55%   |
| Puteaux                      | 1        | 0.55%   |
| Puisieulx                    | 1        | 0.55%   |
| Pluvigner                    | 1        | 0.55%   |
| Plouzane                     | 1        | 0.55%   |
| Plougonven                   | 1        | 0.55%   |
| Paray-sous-Briailles         | 1        | 0.55%   |
| OrlГ©ans                   | 1        | 0.55%   |
| NГ©rac                     | 1        | 0.55%   |
| Novillars                    | 1        | 0.55%   |
| Noisy-le-Grand               | 1        | 0.55%   |
| Nice                         | 1        | 0.55%   |
| Neuve-Maison                 | 1        | 0.55%   |
| Neuilly-le-Vendin            | 1        | 0.55%   |
| Nantes                       | 1        | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 34       | 45     | 16.83%  |
| WDC                 | 28       | 51     | 13.86%  |
| Samsung Electronics | 20       | 29     | 9.9%    |
| Crucial             | 17       | 22     | 8.42%   |
| Kingston            | 14       | 25     | 6.93%   |
| Transcend           | 11       | 14     | 5.45%   |
| Phison              | 9        | 10     | 4.46%   |
| Toshiba             | 8        | 15     | 3.96%   |
| SanDisk             | 6        | 12     | 2.97%   |
| Hoodisk             | 5        | 5      | 2.48%   |
| China               | 5        | 11     | 2.48%   |
| Intel               | 4        | 7      | 1.98%   |
| Hitachi             | 4        | 4      | 1.98%   |
| HGST                | 4        | 7      | 1.98%   |
| PNY                 | 3        | 6      | 1.49%   |
| OCZ                 | 3        | 4      | 1.49%   |
| LDLC                | 3        | 3      | 1.49%   |
| Corsair             | 3        | 4      | 1.49%   |
| Apple               | 3        | 5      | 1.49%   |
| Micron Technology   | 2        | 3      | 0.99%   |
| SPCC                | 1        | 1      | 0.5%    |
| Silicon Power       | 1        | 1      | 0.5%    |
| ShiJi               | 1        | 2      | 0.5%    |
| SABRENT             | 1        | 1      | 0.5%    |
| Pccooler            | 1        | 1      | 0.5%    |
| NVMe                | 1        | 1      | 0.5%    |
| Maxtor              | 1        | 2      | 0.5%    |
| LITEON              | 1        | 2      | 0.5%    |
| Kingchuxing         | 1        | 2      | 0.5%    |
| Innodisk            | 1        | 1      | 0.5%    |
| Indilinx            | 1        | 6      | 0.5%    |
| Generic             | 1        | 1      | 0.5%    |
| Fujitsu             | 1        | 1      | 0.5%    |
| FORESEE             | 1        | 2      | 0.5%    |
| BORY                | 1        | 1      | 0.5%    |
| BIWIN               | 1        | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Phison SATA SSD 16GB               | 8        | 3.62%   |
| Crucial CT120BX500SSD1 120GB       | 4        | 1.81%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3        | 1.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3        | 1.36%   |
| SanDisk SSD PLUS 120GB             | 3        | 1.36%   |
| Samsung SSD 850 EVO 250GB          | 3        | 1.36%   |
| HGST HUS724020ALA640 2TB           | 3        | 1.36%   |
| Transcend TS128GSSD420K 128GB      | 2        | 0.9%    |
| Toshiba HDWD120 2TB                | 2        | 0.9%    |
| Seagate ST3500418AS 500GB          | 2        | 0.9%    |
| Seagate ST31000524AS 1TB           | 2        | 0.9%    |
| Seagate ST1000DM010-2EP102 1TB     | 2        | 0.9%    |
| Seagate ST1000DM003-1SB102 1TB     | 2        | 0.9%    |
| Seagate ST1000DM003-1ER162 1TB     | 2        | 0.9%    |
| Samsung HD501LJ 500GB              | 2        | 0.9%    |
| LDLC F8+M.2 240 240GB              | 2        | 0.9%    |
| Kingston SV300S37A120G 120GB       | 2        | 0.9%    |
| Kingston SUV500MS120G 120GB        | 2        | 0.9%    |
| Kingston SUV400S37240G 240GB       | 2        | 0.9%    |
| Kingston SA400S37120G 120GB        | 2        | 0.9%    |
| Hoodisk SSD 32GB                   | 2        | 0.9%    |
| HGST HUS726020ALA610 2TB           | 2        | 0.9%    |
| Crucial CT250P2SSD8 250GB          | 2        | 0.9%    |
| Crucial CT240BX500SSD1 240GB       | 2        | 0.9%    |
| Crucial CT1000P1SSD8 1TB           | 2        | 0.9%    |
| Crucial CT1000BX500SSD1 1TB        | 2        | 0.9%    |
| China MSATA 64GB SSD               | 2        | 0.9%    |
| Apple SSD SM256E 256GB             | 2        | 0.9%    |
| WDC WDS240G2G0A-00JH30 240GB       | 1        | 0.45%   |
| WDC WDS100T2G0A-00JH30 1TB         | 1        | 0.45%   |
| WDC WD80EZAZ-11TDBA0 8TB           | 1        | 0.45%   |
| WDC WD800BEVT-75ZCT2 80GB          | 1        | 0.45%   |
| WDC WD6400AAKS-22A7B0 640GB        | 1        | 0.45%   |
| WDC WD6003FFBX-68MU3N0 6TB         | 1        | 0.45%   |
| WDC WD5002ABYS-18B1B0 500GB        | 1        | 0.45%   |
| WDC WD5000LPLX-75ZNTT0 500GB       | 1        | 0.45%   |
| WDC WD5000BEVT-22ZAT0 500GB        | 1        | 0.45%   |
| WDC WD40EFRX-68N32N0 4TB           | 1        | 0.45%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1        | 0.45%   |
| WDC WD30EZRX-00D8PB0 3TB           | 1        | 0.45%   |
| WDC WD30EFRX-68AX9N0 3TB           | 1        | 0.45%   |
| WDC WD3000GLFS-01F8U0 304GB        | 1        | 0.45%   |
| WDC WD2503ABYX-01WERA1 256GB       | 1        | 0.45%   |
| WDC WD2500JS-75NCB3 250GB          | 1        | 0.45%   |
| WDC WD2500BEVS-60UST0 250GB        | 1        | 0.45%   |
| WDC WD20NMVW-11EDZS2 2TB           | 1        | 0.45%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 1        | 0.45%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 0.45%   |
| WDC WD20EARX-00PASB0 2TB           | 1        | 0.45%   |
| WDC WD2002FYPS-02W3B0 2TB          | 1        | 0.45%   |
| WDC WD2002FFSX-68PF8N0 2TB         | 1        | 0.45%   |
| WDC WD15EADS-00P8B0 1.5TB          | 1        | 0.45%   |
| WDC WD1500HLFS-01G6U4 150GB        | 1        | 0.45%   |
| WDC WD10EZEX-22MFCA0 1TB           | 1        | 0.45%   |
| WDC WD10EZEX-00UD2A0 1TB           | 1        | 0.45%   |
| WDC WD10EAVS-00D7B0 1TB            | 1        | 0.45%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 0.45%   |
| WDC WD1001FAES-75W7A0 1TB          | 1        | 0.45%   |
| WDC WD Elements 25A1 4TB           | 1        | 0.45%   |
| Transcend TS64GSSD340 64GB         | 1        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 33       | 43     | 38.82%  |
| WDC                 | 26       | 49     | 30.59%  |
| Toshiba             | 7        | 14     | 8.24%   |
| Samsung Electronics | 6        | 12     | 7.06%   |
| Hitachi             | 4        | 4      | 4.71%   |
| HGST                | 4        | 7      | 4.71%   |
| SABRENT             | 1        | 1      | 1.18%   |
| Maxtor              | 1        | 2      | 1.18%   |
| Generic             | 1        | 1      | 1.18%   |
| Fujitsu             | 1        | 1      | 1.18%   |
| Apple               | 1        | 3      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 13       | 24     | 13.13%  |
| Crucial             | 11       | 14     | 11.11%  |
| Transcend           | 10       | 12     | 10.1%   |
| Samsung Electronics | 10       | 11     | 10.1%   |
| Phison              | 8        | 9      | 8.08%   |
| SanDisk             | 6        | 12     | 6.06%   |
| Hoodisk             | 5        | 5      | 5.05%   |
| China               | 5        | 11     | 5.05%   |
| PNY                 | 3        | 6      | 3.03%   |
| OCZ                 | 3        | 4      | 3.03%   |
| Intel               | 3        | 4      | 3.03%   |
| Corsair             | 3        | 4      | 3.03%   |
| WDC                 | 2        | 2      | 2.02%   |
| Apple               | 2        | 2      | 2.02%   |
| Toshiba             | 1        | 1      | 1.01%   |
| SPCC                | 1        | 1      | 1.01%   |
| Silicon Power       | 1        | 1      | 1.01%   |
| ShiJi               | 1        | 2      | 1.01%   |
| Seagate             | 1        | 2      | 1.01%   |
| Pccooler            | 1        | 1      | 1.01%   |
| NVMe                | 1        | 1      | 1.01%   |
| Micron Technology   | 1        | 2      | 1.01%   |
| LITEON              | 1        | 2      | 1.01%   |
| Kingchuxing         | 1        | 2      | 1.01%   |
| Innodisk            | 1        | 1      | 1.01%   |
| Indilinx            | 1        | 6      | 1.01%   |
| FORESEE             | 1        | 2      | 1.01%   |
| BORY                | 1        | 1      | 1.01%   |
| BIWIN               | 1        | 1      | 1.01%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 94       | 146    | 52.51%  |
| HDD  | 66       | 137    | 36.87%  |
| NVMe | 19       | 25     | 10.61%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 141      | 283    | 88.13%  |
| NVMe | 19       | 25     | 11.88%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 117      | 184    | 68.82%  |
| 0.51-1.0   | 26       | 43     | 15.29%  |
| 1.01-2.0   | 17       | 35     | 10%     |
| 2.01-3.0   | 4        | 9      | 2.35%   |
| 4.01-10.0  | 4        | 7      | 2.35%   |
| 3.01-4.0   | 2        | 5      | 1.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 49       | 29.7%   |
| 1-20           | 33       | 20%     |
| 251-500        | 20       | 12.12%  |
| 21-50          | 20       | 12.12%  |
| 51-100         | 17       | 10.3%   |
| 501-1000       | 16       | 9.7%    |
| 1001-2000      | 4        | 2.42%   |
| More than 3000 | 3        | 1.82%   |
| 2001-3000      | 3        | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 137      | 82.04%  |
| 21-50          | 14       | 8.38%   |
| 251-500        | 6        | 3.59%   |
| 101-250        | 4        | 2.4%    |
| 51-100         | 3        | 1.8%    |
| More than 3000 | 1        | 0.6%    |
| 1001-2000      | 1        | 0.6%    |
| 501-1000       | 1        | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Samsung Electronics HD501LJ 500GB  | 2        | 2      | 6.45%   |
| WDC WD6400AAKS-22A7B0 640GB        | 1        | 1      | 3.23%   |
| WDC WD5002ABYS-18B1B0 500GB        | 1        | 1      | 3.23%   |
| WDC WD30EFRX-68AX9N0 3TB           | 1        | 4      | 3.23%   |
| WDC WD2500BEVS-60UST0 250GB        | 1        | 1      | 3.23%   |
| WDC WD2002FYPS-02W3B0 2TB          | 1        | 1      | 3.23%   |
| WDC WD15EADS-00P8B0 1.5TB          | 1        | 1      | 3.23%   |
| WDC WD10EZEX-08WN4A0 1TB           | 1        | 1      | 3.23%   |
| WDC WD10EAVS-00D7B0 1TB            | 1        | 1      | 3.23%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 1      | 3.23%   |
| WDC WD1001FAES-75W7A0 1TB          | 1        | 1      | 3.23%   |
| Seagate ST9500325AS 500GB          | 1        | 1      | 3.23%   |
| Seagate ST500VT000-1DK142 500GB    | 1        | 1      | 3.23%   |
| Seagate ST500LM000-SSHD-8GB        | 1        | 2      | 3.23%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1      | 3.23%   |
| Seagate ST380013AS 80GB            | 1        | 2      | 3.23%   |
| Seagate ST3250620AS 250GB          | 1        | 1      | 3.23%   |
| Seagate ST3160023AS 160GB          | 1        | 1      | 3.23%   |
| Seagate ST31000524AS 1TB           | 1        | 1      | 3.23%   |
| Seagate ST1000NM0011 1TB           | 1        | 1      | 3.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 3.23%   |
| Samsung Electronics HD322GJ 320GB  | 1        | 1      | 3.23%   |
| Samsung Electronics HD256GJ 250GB  | 1        | 1      | 3.23%   |
| Samsung Electronics HD103UJ 1TB    | 1        | 1      | 3.23%   |
| OCZ VERTEX-TURBO 32GB              | 1        | 2      | 3.23%   |
| Kingston SV300S37A120G 120GB       | 1        | 1      | 3.23%   |
| Intel SSDSA2M080G2GN 80GB          | 1        | 1      | 3.23%   |
| Hitachi HTS727575A9E364 752GB      | 1        | 1      | 3.23%   |
| Hitachi HTS542525K9SA00 250GB      | 1        | 1      | 3.23%   |
| Corsair Force 3 SSD 120GB          | 1        | 2      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 13     | 35.71%  |
| Seagate             | 9        | 12     | 32.14%  |
| Samsung Electronics | 3        | 5      | 10.71%  |
| Hitachi             | 2        | 2      | 7.14%   |
| OCZ                 | 1        | 2      | 3.57%   |
| Kingston            | 1        | 1      | 3.57%   |
| Intel               | 1        | 1      | 3.57%   |
| Corsair             | 1        | 2      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 13     | 41.67%  |
| Seagate             | 9        | 12     | 37.5%   |
| Samsung Electronics | 3        | 5      | 12.5%   |
| Hitachi             | 2        | 2      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 32     | 84%     |
| SSD  | 4        | 6      | 16%     |

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
| Works    | 140      | 265    | 83.33%  |
| Malfunc  | 24       | 38     | 14.29%  |
| Detected | 4        | 5      | 2.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 119      | 58.62%  |
| AMD                           | 42       | 20.69%  |
| Micron/Crucial Technology     | 7        | 3.45%   |
| ASMedia Technology            | 6        | 2.96%   |
| Samsung Electronics           | 5        | 2.46%   |
| Silicon Motion                | 3        | 1.48%   |
| Marvell Technology Group      | 3        | 1.48%   |
| JMicron Technology            | 3        | 1.48%   |
| Broadcom / LSI                | 3        | 1.48%   |
| VIA Technologies              | 2        | 0.99%   |
| Chelsio Communications        | 2        | 0.99%   |
| Silicon Image                 | 1        | 0.49%   |
| Phison Electronics            | 1        | 0.49%   |
| Nvidia                        | 1        | 0.49%   |
| Micron Technology             | 1        | 0.49%   |
| Kingston Technology Company   | 1        | 0.49%   |
| Integrated Technology Express | 1        | 0.49%   |
| Hewlett-Packard               | 1        | 0.49%   |
| Unknown                       | 1        | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 25       | 10.73%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 15       | 6.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 10       | 4.29%   |
| AMD FCH SATA Controller [IDE mode]                                               | 9        | 3.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 8        | 3.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6        | 2.58%   |
| Intel SATA Controller [RAID mode]                                                | 6        | 2.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6        | 2.58%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 6        | 2.58%   |
| AMD 400 Series Chipset SATA Controller                                           | 6        | 2.58%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5        | 2.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5        | 2.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 5        | 2.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5        | 2.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4        | 1.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4        | 1.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 4        | 1.72%   |
| Unknown                                                                          | 4        | 1.72%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3        | 1.29%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 3        | 1.29%   |
| JMicron JMB363 SATA/IDE Controller                                               | 3        | 1.29%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3        | 1.29%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3        | 1.29%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 3        | 1.29%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 3        | 1.29%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 3        | 1.29%   |
| AMD 500 Series Chipset SATA Controller                                           | 3        | 1.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2        | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2        | 0.86%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 2        | 0.86%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2        | 0.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2        | 0.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2        | 0.86%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 2        | 0.86%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 2        | 0.86%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 2        | 0.86%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 2        | 0.86%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 2        | 0.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2        | 0.86%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 2        | 0.86%   |
| AMD FCH SATA Controller D                                                        | 2        | 0.86%   |
| AMD 300 Series Chipset SATA Controller                                           | 2        | 0.86%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1        | 0.43%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1        | 0.43%   |
| VIA VT6415 PATA IDE Host Controller                                              | 1        | 0.43%   |
| Silicon Image SiI 3124 PCI-X Serial ATA Controller                               | 1        | 0.43%   |
| Samsung NVMe SSD Controller 980                                                  | 1        | 0.43%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1        | 0.43%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1        | 0.43%   |
| Nvidia MCP51 IDE                                                                 | 1        | 0.43%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1        | 0.43%   |
| Micron/Crucial NVMe Controller                                                   | 1        | 0.43%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                          | 1        | 0.43%   |
| Kingston Company A2000 NVMe SSD                                                  | 1        | 0.43%   |
| Intel SSD 660P Series                                                            | 1        | 0.43%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 1        | 0.43%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1        | 0.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1        | 0.43%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1        | 0.43%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 1        | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 139      | 68.47%  |
| IDE  | 28       | 13.79%  |
| NVMe | 20       | 9.85%   |
| RAID | 11       | 5.42%   |
| SCSI | 3        | 1.48%   |
| SAS  | 2        | 0.99%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 121      | 73.33%  |
| AMD    | 44       | 26.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD GX-412TC SOC                            | 14       | 8.38%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 4        | 2.4%    |
| Intel Core i5-4300Y CPU @ 1.60GHz           | 3        | 1.8%    |
| Intel Core i5-2500K CPU @ 3.30GHz           | 3        | 1.8%    |
| Intel Core i3-3225 CPU @ 3.30GHz            | 3        | 1.8%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.8%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 1.8%    |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz         | 2        | 1.2%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.2%    |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2        | 1.2%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.2%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.2%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.2%    |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 1.2%    |
| Intel Core i3-4010U CPU @ 1.70GHz           | 2        | 1.2%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.2%    |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2        | 1.2%    |
| Intel Core 2 Quad CPU                       | 2        | 1.2%    |
| Intel Celeron CPU J3160 @ 1.60GHz           | 2        | 1.2%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2        | 1.2%    |
| Intel Atom CPU D525 @ 1.80GHz               | 2        | 1.2%    |
| Intel Atom CPU C3558 @ 2.20GHz              | 2        | 1.2%    |
| Intel 686-class                             | 2        | 1.2%    |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.2%    |
| AMD G-T40E Processor                        | 2        | 1.2%    |
| AMD Athlon 5350 APU with Radeon R3          | 2        | 1.2%    |
| Intel Xeon W-2255 CPU @ 3.70GHz             | 1        | 0.6%    |
| Intel Xeon E-2124G CPU @ 3.40GHz            | 1        | 0.6%    |
| Intel Xeon D-2187NT CPU @ 2.00GHz           | 1        | 0.6%    |
| Intel Xeon D-2146NT CPU @ 2.30GHz           | 1        | 0.6%    |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1        | 0.6%    |
| Intel Xeon CPU E31260L @ 2.40GHz            | 1        | 0.6%    |
| Intel Xeon CPU E31235 @ 3.20GHz             | 1        | 0.6%    |
| Intel Xeon CPU E3-1275 V2 @ 3.50GHz         | 1        | 0.6%    |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz         | 1        | 0.6%    |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1        | 0.6%    |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 0.6%    |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz         | 1        | 0.6%    |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 0.6%    |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.6%    |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.6%    |
| Intel Pentium CPU G630T @ 2.30GHz           | 1        | 0.6%    |
| Intel Pentium CPU G4400T @ 2.90GHz          | 1        | 0.6%    |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.6%    |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.6%    |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.6%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1        | 0.6%    |
| Intel Core i7-4770R CPU @ 3.20GHz           | 1        | 0.6%    |
| Intel Core i7-3930K CPU @ 3.20GHz           | 1        | 0.6%    |
| Intel Core i7-3820 CPU @ 3.60GHz            | 1        | 0.6%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.6%    |
| Intel Core i7-2700K CPU @ 3.50GHz           | 1        | 0.6%    |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 0.6%    |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 0.6%    |
| Intel Core i7 CPU                           | 1        | 0.6%    |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.6%    |
| Intel Core i5-8400T CPU @ 1.70GHz           | 1        | 0.6%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.6%    |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 32       | 19.16%  |
| Intel Celeron           | 18       | 10.78%  |
| Intel Core i3           | 16       | 9.58%   |
| AMD GX                  | 16       | 9.58%   |
| Intel Xeon              | 14       | 8.38%   |
| Intel Atom              | 12       | 7.19%   |
| Intel Core i7           | 11       | 6.59%   |
| AMD Ryzen 5             | 7        | 4.19%   |
| Intel Core 2 Quad       | 6        | 3.59%   |
| AMD Ryzen 7             | 6        | 3.59%   |
| Other                   | 5        | 2.99%   |
| Intel Pentium           | 4        | 2.4%    |
| Intel Pentium Gold      | 2        | 1.2%    |
| Intel 686-class         | 2        | 1.2%    |
| AMD G                   | 2        | 1.2%    |
| AMD Athlon 64 X2        | 2        | 1.2%    |
| AMD Athlon              | 2        | 1.2%    |
| AMD A8                  | 2        | 1.2%    |
| Intel Pentium Dual-Core | 1        | 0.6%    |
| Intel Core 2 Duo        | 1        | 0.6%    |
| AMD Ryzen 9             | 1        | 0.6%    |
| AMD Ryzen 3             | 1        | 0.6%    |
| AMD Phenom II X4        | 1        | 0.6%    |
| AMD FX                  | 1        | 0.6%    |
| AMD E1                  | 1        | 0.6%    |
| AMD A10                 | 1        | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 75       | 45.18%  |
| 2       | 52       | 31.33%  |
| 6       | 9        | 5.42%   |
| Unknown | 8        | 4.82%   |
| 16      | 7        | 4.22%   |
| 8       | 7        | 4.22%   |
| 12      | 6        | 3.61%   |
| 32      | 1        | 0.6%    |
| 10      | 1        | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 161      | 97.58%  |
| Unknown | 4        | 2.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 103      | 62.42%  |
| 2       | 54       | 32.73%  |
| Unknown | 8        | 4.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Skylake       | 15       | 9.04%   |
| Puma          | 15       | 9.04%   |
| IvyBridge     | 15       | 9.04%   |
| Haswell       | 15       | 9.04%   |
| SandyBridge   | 14       | 8.43%   |
| KabyLake      | 14       | 8.43%   |
| Silvermont    | 9        | 5.42%   |
| Unknown       | 7        | 4.22%   |
| Zen 2         | 6        | 3.61%   |
| Penryn        | 6        | 3.61%   |
| Bonnell       | 6        | 3.61%   |
| Broadwell     | 5        | 3.01%   |
| Zen+          | 4        | 2.41%   |
| Goldmont plus | 4        | 2.41%   |
| Goldmont      | 4        | 2.41%   |
| Zen 3         | 3        | 1.81%   |
| Nehalem       | 3        | 1.81%   |
| Jaguar        | 3        | 1.81%   |
| Bobcat        | 3        | 1.81%   |
| Zen           | 2        | 1.2%    |
| Westmere      | 2        | 1.2%    |
| Piledriver    | 2        | 1.2%    |
| Core          | 2        | 1.2%    |
| CometLake     | 2        | 1.2%    |
| TigerLake     | 1        | 0.6%    |
| Steamroller   | 1        | 0.6%    |
| K8 Hammer     | 1        | 0.6%    |
| K10           | 1        | 0.6%    |
| Excavator     | 1        | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 89       | 61.81%  |
| Nvidia                     | 22       | 15.28%  |
| AMD                        | 22       | 15.28%  |
| ASPEED Technology          | 6        | 4.17%   |
| Matrox Electronics Systems | 5        | 3.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 8        | 5.52%   |
| Intel HD Graphics 530                                                                    | 7        | 4.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6        | 4.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 4.14%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 6        | 4.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5        | 3.45%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4        | 2.76%   |
| Intel HD Graphics 510                                                                    | 4        | 2.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4        | 2.76%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 2.07%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3        | 2.07%   |
| Intel HD Graphics 620                                                                    | 3        | 2.07%   |
| Intel HD Graphics 5500                                                                   | 3        | 2.07%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 3        | 2.07%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 2.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 2.07%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3        | 2.07%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 2.07%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2        | 1.38%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2        | 1.38%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 1.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2        | 1.38%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.38%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 2        | 1.38%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 1.38%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 2        | 1.38%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 1.38%   |
| AMD Cezanne                                                                              | 2        | 1.38%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.69%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 0.69%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 0.69%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.69%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 0.69%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 0.69%   |
| Nvidia GF114 [GeForce GTX 560]                                                           | 1        | 0.69%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                                        | 1        | 0.69%   |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1        | 0.69%   |
| Nvidia GA106 [RTX A2000 12GB]                                                            | 1        | 0.69%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                           | 1        | 0.69%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 1        | 0.69%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1        | 0.69%   |
| Nvidia C51PV [GeForce 6150]                                                              | 1        | 0.69%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1        | 0.69%   |
| Intel Xeon E3-1200 Processor Family Integrated Graphics Controller                       | 1        | 0.69%   |
| Intel Tiger Lake UHD Graphics                                                            | 1        | 0.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1        | 0.69%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 0.69%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 1        | 0.69%   |
| Intel JasperLake [UHD Graphics]                                                          | 1        | 0.69%   |
| Intel HD Graphics P530                                                                   | 1        | 0.69%   |
| Intel HD Graphics 630                                                                    | 1        | 0.69%   |
| Intel HD Graphics 6000                                                                   | 1        | 0.69%   |
| Intel HD Graphics 500                                                                    | 1        | 0.69%   |
| Intel HD Graphics                                                                        | 1        | 0.69%   |
| Intel Crystal Well Integrated Iris Pro Graphics 5200                                     | 1        | 0.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                               | 1        | 0.69%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                            | 1        | 0.69%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 0.69%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 0.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 85       | 51.2%   |
| Other      | 22       | 13.25%  |
| 1 x Nvidia | 22       | 13.25%  |
| 1 x AMD    | 22       | 13.25%  |
| 1 x ASPEED | 6        | 3.61%   |
| 1 x Matrox | 5        | 3.01%   |
| 2 x Intel  | 4        | 2.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 124      | 74.7%   |
| Unknown     | 27       | 16.27%  |
| Proprietary | 15       | 9.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 138      | 83.64%  |
| 1.01-2.0   | 7        | 4.24%   |
| 7.01-8.0   | 6        | 3.64%   |
| 0.51-1.0   | 6        | 3.64%   |
| 0.01-0.5   | 4        | 2.42%   |
| 5.01-6.0   | 2        | 1.21%   |
| 3.01-4.0   | 1        | 0.61%   |
| 8.01-16.0  | 1        | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 7        | 20%     |
| Iiyama               | 4        | 11.43%  |
| Hewlett-Packard      | 4        | 11.43%  |
| Samsung Electronics  | 3        | 8.57%   |
| Idek Iiyama          | 3        | 8.57%   |
| Goldstar             | 3        | 8.57%   |
| Ancor Communications | 3        | 8.57%   |
| Sony                 | 1        | 2.86%   |
| PRI                  | 1        | 2.86%   |
| Philips              | 1        | 2.86%   |
| Packard Bell         | 1        | 2.86%   |
| LG Electronics       | 1        | 2.86%   |
| CKL                  | 1        | 2.86%   |
| BenQ                 | 1        | 2.86%   |
| AOC                  | 1        | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Sony TV  *00 SNYF903 3840x2160 950x540mm 43.0-inch                    | 1        | 2.86%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch   | 1        | 2.86%   |
| Samsung Electronics LCD Monitor SyncMaster 3520x1200                  | 1        | 2.86%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                     | 1        | 2.86%   |
| PRI LED-MONITOR PRI0828 3840x2160 1150x650mm 52.0-inch                | 1        | 2.86%   |
| Philips LCD Monitor PHLC00B 1280x1024 340x270mm 17.1-inch             | 1        | 2.86%   |
| Packard Bell Viseo 200Ws PKB00C2 1600x900 440x250mm 19.9-inch         | 1        | 2.86%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 1        | 2.86%   |
| Iiyama PLX2483H IVM6114 1920x1080 530x300mm 24.0-inch                 | 1        | 2.86%   |
| Iiyama PL2783Q IVM661F 2560x1440 600x340mm 27.2-inch                  | 1        | 2.86%   |
| Iiyama PL2483H IVM6138 1920x1080 530x300mm 24.0-inch                  | 1        | 2.86%   |
| Iiyama PL2474H IVM6137 1920x1080 520x290mm 23.4-inch                  | 1        | 2.86%   |
| Idek Iiyama LCD Monitor PLX2783H 1920x1080                            | 1        | 2.86%   |
| Idek Iiyama LCD Monitor PL2409HD 1920x1080                            | 1        | 2.86%   |
| Idek Iiyama LCD Monitor PL2206W 1680x1050                             | 1        | 2.86%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 470x300mm 22.0-inch           | 1        | 2.86%   |
| Hewlett-Packard HPQ 8300 AiO HWP4212 1920x1080 510x290mm 23.1-inch    | 1        | 2.86%   |
| Hewlett-Packard 2310e HWP2909 1920x1080 510x290mm 23.1-inch           | 1        | 2.86%   |
| Hewlett-Packard 2211 HWP2938 1920x1080 480x270mm 21.7-inch            | 1        | 2.86%   |
| Goldstar L1730S GSM438D 1280x1024 340x270mm 17.1-inch                 | 1        | 2.86%   |
| Goldstar 27GK750F GSM770F 1920x1080 600x340mm 27.2-inch               | 1        | 2.86%   |
| Goldstar 19MB35 GSM4C23 1280x1024 380x300mm 19.1-inch                 | 1        | 2.86%   |
| Dell P2418D DELD0C2 2560x1440 530x300mm 24.0-inch                     | 1        | 2.86%   |
| Dell P1917S DELD092 1280x1024 380x300mm 19.1-inch                     | 1        | 2.86%   |
| Dell P1917S DELD091 1280x1024 380x300mm 19.1-inch                     | 1        | 2.86%   |
| Dell P1911 DELA073 1440x900 410x260mm 19.1-inch                       | 1        | 2.86%   |
| Dell LCD Monitor U2414H                                               | 1        | 2.86%   |
| Dell E2014H DELD03B 1600x900 430x240mm 19.4-inch                      | 1        | 2.86%   |
| Dell E1715S DELD062 1280x1024 340x270mm 17.1-inch                     | 1        | 2.86%   |
| CKL LCD Monitor CKL0001 1920x1200 1150x650mm 52.0-inch                | 1        | 2.86%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 1        | 2.86%   |
| AOC Q2577W AOC2577 2560x1440 550x310mm 24.9-inch                      | 1        | 2.86%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 520x290mm 23.4-inch | 1        | 2.86%   |
| Ancor Communications ASUS PB238 ACI23A2 1920x1080 510x290mm 23.1-inch | 1        | 2.86%   |
| Ancor Communications ASUS MG278 ACI27A8 2560x1440 600x340mm 27.2-inch | 1        | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 13       | 37.14%  |
| 1280x1024 (SXGA)   | 6        | 17.14%  |
| 2560x1440 (QHD)    | 4        | 11.43%  |
| 3840x2160 (4K)     | 2        | 5.71%   |
| 1680x1050 (WSXGA+) | 2        | 5.71%   |
| 1600x900 (HD+)     | 2        | 5.71%   |
| 1440x900 (WXGA+)   | 2        | 5.71%   |
| 3520x1200          | 1        | 2.86%   |
| 2560x1080          | 1        | 2.86%   |
| 1920x1200 (WUXGA)  | 1        | 2.86%   |
| Unknown            | 1        | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 7        | 20.59%  |
| Unknown | 6        | 17.65%  |
| 23      | 5        | 14.71%  |
| 24      | 4        | 11.76%  |
| 27      | 3        | 8.82%   |
| 17      | 3        | 8.82%   |
| 52      | 2        | 5.88%   |
| 21      | 2        | 5.88%   |
| 43      | 1        | 2.94%   |
| 22      | 1        | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 12       | 35.29%  |
| 401-500     | 7        | 20.59%  |
| Unknown     | 6        | 17.65%  |
| 351-400     | 3        | 8.82%   |
| 301-350     | 3        | 8.82%   |
| 1001-1500   | 2        | 5.88%   |
| 901-1000    | 1        | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 19       | 55.88%  |
| 5/4     | 6        | 17.65%  |
| Unknown | 6        | 17.65%  |
| 16/10   | 3        | 8.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 32.35%  |
| 151-200        | 7        | 20.59%  |
| Unknown        | 6        | 17.65%  |
| 301-350        | 3        | 8.82%   |
| 141-150        | 3        | 8.82%   |
| More than 1000 | 2        | 5.88%   |
| 251-300        | 1        | 2.94%   |
| 501-1000       | 1        | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 20       | 58.82%  |
| 101-120 | 6        | 17.65%  |
| Unknown | 6        | 17.65%  |
| 1-50    | 1        | 2.94%   |
| 121-160 | 1        | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 130      | 78.31%  |
| 1     | 35       | 21.08%  |
| 2     | 1        | 0.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 121      | 52.61%  |
| Realtek Semiconductor           | 69       | 30%     |
| Qualcomm Atheros                | 13       | 5.65%   |
| Broadcom                        | 9        | 3.91%   |
| Ralink Technology               | 2        | 0.87%   |
| Qualcomm                        | 2        | 0.87%   |
| D-Link System                   | 2        | 0.87%   |
| Chelsio Communications          | 2        | 0.87%   |
| VIA Technologies                | 1        | 0.43%   |
| TP-Link                         | 1        | 0.43%   |
| Qualcomm Atheros Communications | 1        | 0.43%   |
| Microchip Technology            | 1        | 0.43%   |
| MediaTek                        | 1        | 0.43%   |
| Huawei Technologies             | 1        | 0.43%   |
| Edimax Technology               | 1        | 0.43%   |
| American Megatrends             | 1        | 0.43%   |
| AMD                             | 1        | 0.43%   |
| 3Com                            | 1        | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 62       | 21.75%  |
| Intel I211 Gigabit Network Connection                                         | 29       | 10.18%  |
| Intel 82574L Gigabit Network Connection                                       | 17       | 5.96%   |
| Intel I210 Gigabit Network Connection                                         | 16       | 5.61%   |
| Intel I350 Gigabit Network Connection                                         | 8        | 2.81%   |
| Realtek RTL8125 2.5GbE Controller                                             | 7        | 2.46%   |
| Intel Wi-Fi 6 AX200                                                           | 7        | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 2.46%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6        | 2.11%   |
| Intel Ethernet Controller I225-V                                              | 5        | 1.75%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 1.75%   |
| Intel 82579V Gigabit Network Connection                                       | 5        | 1.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 4        | 1.4%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 3        | 1.05%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 3        | 1.05%   |
| Intel Ethernet Connection X553 1GbE                                           | 3        | 1.05%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 1.05%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 1.05%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 1.05%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.7%    |
| Ralink RT5370 Wireless Adapter                                                | 2        | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2        | 0.7%    |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 2        | 0.7%    |
| Intel Wireless 7260                                                           | 2        | 0.7%    |
| Intel Wireless 3165                                                           | 2        | 0.7%    |
| Intel Ethernet Controller X550                                                | 2        | 0.7%    |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 2        | 0.7%    |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.7%    |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 0.7%    |
| Intel 82583V Gigabit Network Connection                                       | 2        | 0.7%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.7%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 0.7%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.7%    |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1        | 0.35%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 0.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 0.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.35%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1        | 0.35%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                   | 1        | 0.35%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1        | 0.35%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1        | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.35%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.35%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.35%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.35%   |
| Microchip HTC Hub Controller                                                  | 1        | 0.35%   |
| MediaTek 802.11ac Wireless LAN Card                                           | 1        | 0.35%   |
| Intel Wireless-AC 9260                                                        | 1        | 0.35%   |
| Intel Wireless 7265                                                           | 1        | 0.35%   |
| Intel Wireless 3160                                                           | 1        | 0.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 0.35%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1        | 0.35%   |
| Intel Wi-Fi 6 AX201                                                           | 1        | 0.35%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 1        | 0.35%   |
| Intel Ethernet Controller I225-LM                                             | 1        | 0.35%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 21       | 45.65%  |
| Qualcomm Atheros                | 10       | 21.74%  |
| Realtek Semiconductor           | 8        | 17.39%  |
| Ralink Technology               | 2        | 4.35%   |
| TP-Link                         | 1        | 2.17%   |
| Qualcomm Atheros Communications | 1        | 2.17%   |
| MediaTek                        | 1        | 2.17%   |
| Edimax Technology               | 1        | 2.17%   |
| Broadcom                        | 1        | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 7        | 15.22%  |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 4        | 8.7%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 3        | 6.52%   |
| Ralink RT5370 Wireless Adapter                                  | 2        | 4.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 2        | 4.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 2        | 4.35%   |
| Intel Wireless 7260                                             | 2        | 4.35%   |
| Intel Wireless 3165                                             | 2        | 4.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 2        | 4.35%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 1        | 2.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 1        | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 1        | 2.17%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1        | 2.17%   |
| Realtek RTL8191SEvA Wireless LAN Controller                     | 1        | 2.17%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 1        | 2.17%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1        | 2.17%   |
| Qualcomm Atheros AR9271 802.11n                                 | 1        | 2.17%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 1        | 2.17%   |
| MediaTek 802.11ac Wireless LAN Card                             | 1        | 2.17%   |
| Intel Wireless-AC 9260                                          | 1        | 2.17%   |
| Intel Wireless 7265                                             | 1        | 2.17%   |
| Intel Wireless 3160                                             | 1        | 2.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 1        | 2.17%   |
| Intel Wi-Fi 6 AX201 160MHz                                      | 1        | 2.17%   |
| Intel Wi-Fi 6 AX201                                             | 1        | 2.17%   |
| Intel Centrino Advanced-N 6235                                  | 1        | 2.17%   |
| Intel Alder Lake-S PCH CNVi WiFi                                | 1        | 2.17%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 1        | 2.17%   |
| Broadcom BCM43224 802.11a/b/g/n                                 | 1        | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 113      | 56.5%   |
| Realtek Semiconductor  | 66       | 33%     |
| Broadcom               | 8        | 4%      |
| Qualcomm Atheros       | 3        | 1.5%    |
| Qualcomm               | 2        | 1%      |
| D-Link System          | 2        | 1%      |
| Chelsio Communications | 2        | 1%      |
| VIA Technologies       | 1        | 0.5%    |
| American Megatrends    | 1        | 0.5%    |
| AMD                    | 1        | 0.5%    |
| 3Com                   | 1        | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 62       | 26.27%  |
| Intel I211 Gigabit Network Connection                                         | 29       | 12.29%  |
| Intel 82574L Gigabit Network Connection                                       | 17       | 7.2%    |
| Intel I210 Gigabit Network Connection                                         | 16       | 6.78%   |
| Intel I350 Gigabit Network Connection                                         | 8        | 3.39%   |
| Realtek RTL8125 2.5GbE Controller                                             | 7        | 2.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 2.97%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6        | 2.54%   |
| Intel Ethernet Controller I225-V                                              | 5        | 2.12%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 2.12%   |
| Intel 82579V Gigabit Network Connection                                       | 5        | 2.12%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 3        | 1.27%   |
| Intel Ethernet Connection X553 1GbE                                           | 3        | 1.27%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 1.27%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 1.27%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 1.27%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.85%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 2        | 0.85%   |
| Intel Ethernet Controller X550                                                | 2        | 0.85%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 2        | 0.85%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.85%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.85%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 0.85%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.85%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 0.85%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.85%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1        | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.42%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.42%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 1        | 0.42%   |
| Intel Ethernet Controller I225-LM                                             | 1        | 0.42%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.42%   |
| Intel Ethernet Connection X722 for 10GbE backplane                            | 1        | 0.42%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1        | 0.42%   |
| Intel Ethernet Connection I219-LM                                             | 1        | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.42%   |
| Intel Ethernet Connection (5) I219-V                                          | 1        | 0.42%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 0.42%   |
| Intel Ethernet Connection (13) I219-V                                         | 1        | 0.42%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.42%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.42%   |
| Intel 82575GB Gigabit Network Connection                                      | 1        | 0.42%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1        | 0.42%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 0.42%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 0.42%   |
| Chelsio T6425-CR Unified Wire Ethernet Controller                             | 1        | 0.42%   |
| Chelsio T520-CR Unified Wire Ethernet Controller                              | 1        | 0.42%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 1        | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.42%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1        | 0.42%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 0.42%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 1        | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1        | 0.42%   |
| American Megatrends Virtual Ethernet                                          | 1        | 0.42%   |
| AMD 79c970 [PCnet32 LANCE]                                                    | 1        | 0.42%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 1        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 164      | 77.73%  |
| WiFi     | 44       | 20.85%  |
| Unknown  | 2        | 0.95%   |
| Modem    | 1        | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 154      | 98.09%  |
| WiFi     | 3        | 1.91%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 42       | 25.15%  |
| 2     | 38       | 22.75%  |
| 4     | 29       | 17.37%  |
| 3     | 29       | 17.37%  |
| 5     | 10       | 5.99%   |
| 6     | 6        | 3.59%   |
| 8     | 4        | 2.4%    |
| 7     | 4        | 2.4%    |
| 13    | 1        | 0.6%    |
| 12    | 1        | 0.6%    |
| 11    | 1        | 0.6%    |
| 10    | 1        | 0.6%    |
| 0     | 1        | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 133      | 77.33%  |
| Yes  | 39       | 22.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 16       | 72.73%  |
| Cambridge Silicon Radio  | 2        | 9.09%   |
| Broadcom                 | 2        | 9.09%   |
| Realtek Semiconductor    | 1        | 4.55%   |
| HTC (High Tech Computer) | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 5        | 22.73%  |
| Intel Bluetooth wireless interface                                   | 4        | 18.18%  |
| Intel AX201 Bluetooth                                                | 2        | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2        | 9.09%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 9.09%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 4.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 1        | 4.55%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 4.55%   |
| Intel AX210 Bluetooth                                                | 1        | 4.55%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 83       | 57.24%  |
| AMD                                          | 27       | 18.62%  |
| Nvidia                                       | 20       | 13.79%  |
| Focusrite-Novation                           | 2        | 1.38%   |
| Creative Labs                                | 2        | 1.38%   |
| C-Media Electronics                          | 2        | 1.38%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.69%   |
| VIA Technologies                             | 1        | 0.69%   |
| Texas Instruments                            | 1        | 0.69%   |
| Sony                                         | 1        | 0.69%   |
| Micronas                                     | 1        | 0.69%   |
| Kingston Technology                          | 1        | 0.69%   |
| iCreate Technologies                         | 1        | 0.69%   |
| Giga-Byte Technology                         | 1        | 0.69%   |
| ESS Technology                               | 1        | 0.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11       | 6.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10       | 5.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7        | 4%      |
| Intel 200 Series PCH HD Audio                                                                     | 7        | 4%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7        | 4%      |
| AMD FCH Azalia Controller                                                                         | 7        | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6        | 3.43%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6        | 3.43%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5        | 2.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4        | 2.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4        | 2.29%   |
| Intel Broadwell-U Audio Controller                                                                | 4        | 2.29%   |
| Intel 8 Series HD Audio Controller                                                                | 4        | 2.29%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4        | 2.29%   |
| Nvidia High Definition Audio Controller                                                           | 3        | 1.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3        | 1.71%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 1.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3        | 1.71%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3        | 1.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 1.71%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3        | 1.71%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3        | 1.71%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3        | 1.71%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2        | 1.14%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 2        | 1.14%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2        | 1.14%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2        | 1.14%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 1.14%   |
| AMD Navi 10 HDMI Audio                                                                            | 2        | 1.14%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2        | 1.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 1.14%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 1.14%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1        | 0.57%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1        | 0.57%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1        | 0.57%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1        | 0.57%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 0.57%   |
| Nvidia MCP51 High Definition Audio                                                                | 1        | 0.57%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1        | 0.57%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 0.57%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 0.57%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1        | 0.57%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 0.57%   |
| Nvidia GF110 High Definition Audio Controller                                                     | 1        | 0.57%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1        | 0.57%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1        | 0.57%   |
| Micronas Blue USB Audio 2.0                                                                       | 1        | 0.57%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1        | 0.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1        | 0.57%   |
| Intel Jasper Lake HD Audio                                                                        | 1        | 0.57%   |
| Intel Crystal Well HD Audio Controller                                                            | 1        | 0.57%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 0.57%   |
| Intel Comet Lake PCH cAVS                                                                         | 1        | 0.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1        | 0.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1        | 0.57%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1        | 0.57%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1        | 0.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1        | 0.57%   |
| iCreate Technologies ASUS Xonar U7 Audio Device                                                   | 1        | 0.57%   |
| Giga-Byte Technology USB Audio                                                                    | 1        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 21       | 13.91%  |
| Samsung Electronics | 21       | 13.91%  |
| Kingston            | 20       | 13.25%  |
| Corsair             | 20       | 13.25%  |
| SK hynix            | 17       | 11.26%  |
| Crucial             | 14       | 9.27%   |
| G.Skill             | 13       | 8.61%   |
| Micron Technology   | 7        | 4.64%   |
| Transcend           | 3        | 1.99%   |
| Nanya Technology    | 3        | 1.99%   |
| Kimtigo             | 2        | 1.32%   |
| Atermiter           | 2        | 1.32%   |
| Teikon              | 1        | 0.66%   |
| Patriot             | 1        | 0.66%   |
| OCZ                 | 1        | 0.66%   |
| Hewlett-Packard     | 1        | 0.66%   |
| Goldenmars          | 1        | 0.66%   |
| Elpida              | 1        | 0.66%   |
| Apacer              | 1        | 0.66%   |
| Unknown             | 1        | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 4        | 2.47%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 4        | 2.47%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 1600MT/s     | 3        | 1.85%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 2        | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s              | 2        | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s             | 2        | 1.23%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 2        | 1.23%   |
| Samsung RAM M393A4K40CB2-CTD 32GB DIMM DDR4 2667MT/s    | 2        | 1.23%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 1.23%   |
| Micron RAM 8HTF12864AZ-800H1 1GB DIMM DDR2 800MT/s      | 2        | 1.23%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 2        | 1.23%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s   | 2        | 1.23%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s          | 2        | 1.23%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3200MT/s    | 2        | 1.23%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s | 2        | 1.23%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s     | 2        | 1.23%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1333MT/s     | 2        | 1.23%   |
| Atermiter RAM Module 8GB DIMM DDR3 800MT/s              | 2        | 1.23%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s            | 1        | 0.62%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR3 1332MT/s               | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM 667MT/s                     | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM 400MT/s                     | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                    | 1        | 0.62%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s            | 1        | 0.62%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                | 1        | 0.62%   |
| Unknown RAM Module 1GB DIMM 667MT/s                     | 1        | 0.62%   |
| Transcend RAM TS512MSK64V3H 4GB SODIMM DDR3 667MT/s     | 1        | 0.62%   |
| Transcend RAM TS1GLK72V6H 8GB DIMM DDR3 1600MT/s        | 1        | 0.62%   |
| Transcend RAM TS1GLH64V1H 8GB DIMM DDR4 2133MT/s        | 1        | 0.62%   |
| Teikon RAM TMTS8G58DFRBFIR-16 8GB SODIMM DDR3 1600MT/s  | 1        | 0.62%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s              | 1        | 0.62%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s    | 1        | 0.62%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 0.62%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 0.62%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB DDR3 1600MT/s         | 1        | 0.62%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 1        | 0.62%   |
| SK hynix RAM HMT351U7BFR8A-H9 4GB DIMM DDR3 1333MT/s    | 1        | 0.62%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 0.62%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s  | 1        | 0.62%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s  | 1        | 0.62%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s    | 1        | 0.62%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s    | 1        | 0.62%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 0.62%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 0.62%   |
| SK hynix RAM HMP125U6EFR8C-S6 2GB DIMM DDR2 800MT/s     | 1        | 0.62%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 2400MT/s  | 1        | 0.62%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16GB DIMM DDR4 3200MT/s   | 1        | 0.62%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s    | 1        | 0.62%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 1        | 0.62%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s             | 1        | 0.62%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s               | 1        | 0.62%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s   | 1        | 0.62%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1        | 0.62%   |
| Samsung RAM M471B2873FHS-CH9 4GB DIMM DDR3 1600MT/s     | 1        | 0.62%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s   | 1        | 0.62%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s  | 1        | 0.62%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s   | 1        | 0.62%   |
| Samsung RAM M393A2K40CB1-CRC 16GB DIMM DDR4 2400MT/s    | 1        | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 75       | 53.96%  |
| DDR4    | 49       | 35.25%  |
| Unknown | 10       | 7.19%   |
| DDR2    | 5        | 3.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 102      | 73.91%  |
| SODIMM  | 35       | 25.36%  |
| Unknown | 1        | 0.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 52       | 35.37%  |
| 8192  | 49       | 33.33%  |
| 2048  | 24       | 16.33%  |
| 16384 | 12       | 8.16%   |
| 1024  | 6        | 4.08%   |
| 32768 | 4        | 2.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 43       | 30.28%  |
| 1333  | 27       | 19.01%  |
| 2400  | 14       | 9.86%   |
| 2667  | 12       | 8.45%   |
| 3200  | 10       | 7.04%   |
| 800   | 10       | 7.04%   |
| 2133  | 9        | 6.34%   |
| 1066  | 4        | 2.82%   |
| 2666  | 3        | 2.11%   |
| 1334  | 2        | 1.41%   |
| 667   | 2        | 1.41%   |
| 5200  | 1        | 0.7%    |
| 2933  | 1        | 0.7%    |
| 1400  | 1        | 0.7%    |
| 1332  | 1        | 0.7%    |
| 533   | 1        | 0.7%    |
| 400   | 1        | 0.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| Seiko Epson Printer | 1        | 100%    |

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
| Logitech                 | 2        | 50%     |
| Novatek Microelectronics | 1        | 25%     |
| Linux Foundation         | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Novatek HP High Definition 2MP Webcam | 1        | 25%     |
| Logitech Webcam C270                  | 1        | 25%     |
| Logitech C922 Pro Stream Webcam       | 1        | 25%     |
| Linux Foundation HD Camera            | 1        | 25%     |

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
| 1     | 84       | 50%     |
| 0     | 57       | 33.93%  |
| 2     | 19       | 11.31%  |
| 3     | 7        | 4.17%   |
| 4     | 1        | 0.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 92       | 68.15%  |
| Net/wireless             | 18       | 13.33%  |
| Bluetooth                | 9        | 6.67%   |
| Firewire controller      | 6        | 4.44%   |
| Sound                    | 3        | 2.22%   |
| Net/ethernet             | 3        | 2.22%   |
| Network                  | 1        | 0.74%   |
| Modem                    | 1        | 0.74%   |
| Graphics card            | 1        | 0.74%   |
| Card reader              | 1        | 0.74%   |

