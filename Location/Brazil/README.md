BSD in Brazil - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in Brazil.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Brazil/Desktop/README.md) and [notebooks](/Location/Brazil/Notebook/README.md).

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

Total: 631

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | DH61BR G32662-203           | Desktop     | [c082ba6276](https://bsd-hardware.info/?probe=c082ba6276) | Jan 06, 2025 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [4bd0423b13](https://bsd-hardware.info/?probe=4bd0423b13) | Jan 05, 2025 |
| CWWK          | CW-J6-6L                    | Desktop     | [938c3dd6d1](https://bsd-hardware.info/?probe=938c3dd6d1) | Jan 04, 2025 |
| Dell          | Inspiron 3421               | Notebook    | [0cae3b71cd](https://bsd-hardware.info/?probe=0cae3b71cd) | Dec 31, 2024 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [f7a1fd8000](https://bsd-hardware.info/?probe=f7a1fd8000) | Dec 31, 2024 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [81977dc6c5](https://bsd-hardware.info/?probe=81977dc6c5) | Dec 28, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [e03720a10c](https://bsd-hardware.info/?probe=e03720a10c) | Dec 27, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [34c03dc287](https://bsd-hardware.info/?probe=34c03dc287) | Dec 18, 2024 |
| Unknown       | Unknown                     | Notebook    | [e02dd09c46](https://bsd-hardware.info/?probe=e02dd09c46) | Dec 12, 2024 |
| Dell          | 0CU409                      | Desktop     | [4a9ae9da54](https://bsd-hardware.info/?probe=4a9ae9da54) | Dec 10, 2024 |
| ASRock        | B550 PG Riptide             | Desktop     | [183c138b5d](https://bsd-hardware.info/?probe=183c138b5d) | Dec 09, 2024 |
| Timi          | TM1703                      | Notebook    | [6af452297e](https://bsd-hardware.info/?probe=6af452297e) | Dec 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [365e2536fc](https://bsd-hardware.info/?probe=365e2536fc) | Dec 06, 2024 |
| Dell          | 0RY206                      | Desktop     | [e72ddbe6c0](https://bsd-hardware.info/?probe=e72ddbe6c0) | Dec 04, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [06d16e6428](https://bsd-hardware.info/?probe=06d16e6428) | Dec 03, 2024 |
| Advantech     | FWA-6520 A103-1             | Server      | [4ac3494599](https://bsd-hardware.info/?probe=4ac3494599) | Dec 02, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | Notebook    | [208feb98b3](https://bsd-hardware.info/?probe=208feb98b3) | Nov 26, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | Notebook    | [1f1948481c](https://bsd-hardware.info/?probe=1f1948481c) | Nov 26, 2024 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [6554ebbcca](https://bsd-hardware.info/?probe=6554ebbcca) | Nov 25, 2024 |
| Unknown       | Unknown                     | Notebook    | [c5db5961d4](https://bsd-hardware.info/?probe=c5db5961d4) | Nov 20, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | Notebook    | [ab3ba2edf5](https://bsd-hardware.info/?probe=ab3ba2edf5) | Nov 18, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | Notebook    | [2a9c5b1e5c](https://bsd-hardware.info/?probe=2a9c5b1e5c) | Nov 18, 2024 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [989b523126](https://bsd-hardware.info/?probe=989b523126) | Nov 15, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [b9b63a6ca9](https://bsd-hardware.info/?probe=b9b63a6ca9) | Nov 15, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [0def0b220f](https://bsd-hardware.info/?probe=0def0b220f) | Nov 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [4bf2350360](https://bsd-hardware.info/?probe=4bf2350360) | Nov 09, 2024 |
| CncTion       | J4125-4L V1.0               | Desktop     | [c012eb7002](https://bsd-hardware.info/?probe=c012eb7002) | Nov 07, 2024 |
| Dell          | 0GDG8Y A02                  | Desktop     | [ad27700305](https://bsd-hardware.info/?probe=ad27700305) | Nov 07, 2024 |
| Dell          | 0W1MP6 A04                  | Server      | [0a74b8ea7d](https://bsd-hardware.info/?probe=0a74b8ea7d) | Nov 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [7d3443149e](https://bsd-hardware.info/?probe=7d3443149e) | Nov 03, 2024 |
| Apple         | MacBook7,1                  | Notebook    | [056bc64a0c](https://bsd-hardware.info/?probe=056bc64a0c) | Nov 03, 2024 |
| Unknown       | Unknown                     | Notebook    | [57c6faa7cc](https://bsd-hardware.info/?probe=57c6faa7cc) | Nov 01, 2024 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [5a48320b8b](https://bsd-hardware.info/?probe=5a48320b8b) | Oct 31, 2024 |
| Positivo      | H14BT58                     | Notebook    | [b54614c603](https://bsd-hardware.info/?probe=b54614c603) | Oct 31, 2024 |
| Dell          | 053CWD A00                  | Desktop     | [1a6b365ab4](https://bsd-hardware.info/?probe=1a6b365ab4) | Oct 30, 2024 |
| Unknown       | Unknown                     | Notebook    | [46a5a36c7d](https://bsd-hardware.info/?probe=46a5a36c7d) | Oct 29, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ef22672b81](https://bsd-hardware.info/?probe=ef22672b81) | Oct 29, 2024 |
| Dell          | Latitude 5490               | Notebook    | [aa1887b2e7](https://bsd-hardware.info/?probe=aa1887b2e7) | Oct 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [5a4da349a3](https://bsd-hardware.info/?probe=5a4da349a3) | Oct 27, 2024 |
| CncTion       | J4125-4L V1.0               | Desktop     | [9f1b523fb3](https://bsd-hardware.info/?probe=9f1b523fb3) | Oct 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [72c8a667f9](https://bsd-hardware.info/?probe=72c8a667f9) | Oct 23, 2024 |
| Dell          | 0RY206                      | Desktop     | [72fd9572dc](https://bsd-hardware.info/?probe=72fd9572dc) | Oct 21, 2024 |
| ASRock        | G31M-VS2                    | Desktop     | [76aa159718](https://bsd-hardware.info/?probe=76aa159718) | Oct 18, 2024 |
| Lenovo        | ThinkPad E490 20N9S48S00    | Notebook    | [6df8b611a2](https://bsd-hardware.info/?probe=6df8b611a2) | Oct 14, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [3e9754954d](https://bsd-hardware.info/?probe=3e9754954d) | Oct 12, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [00717c120b](https://bsd-hardware.info/?probe=00717c120b) | Oct 09, 2024 |
| Gigabyte      | C847N                       | Desktop     | [5098f443ae](https://bsd-hardware.info/?probe=5098f443ae) | Oct 09, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [cb476ab6ab](https://bsd-hardware.info/?probe=cb476ab6ab) | Oct 09, 2024 |
| CncTion       | J4125-4L V1.0               | Desktop     | [c634bbc0e5](https://bsd-hardware.info/?probe=c634bbc0e5) | Oct 08, 2024 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [399f958c29](https://bsd-hardware.info/?probe=399f958c29) | Oct 08, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [e4e1bf6fa2](https://bsd-hardware.info/?probe=e4e1bf6fa2) | Oct 05, 2024 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [6bed12aa05](https://bsd-hardware.info/?probe=6bed12aa05) | Oct 03, 2024 |
| Acer          | Aspire A515-45              | Notebook    | [3e03a4540a](https://bsd-hardware.info/?probe=3e03a4540a) | Oct 02, 2024 |
| HP            | 8062                        | Desktop     | [0e7e52042b](https://bsd-hardware.info/?probe=0e7e52042b) | Oct 01, 2024 |
| Intel         | X99-P4 V8.0                 | Desktop     | [e6972a88e8](https://bsd-hardware.info/?probe=e6972a88e8) | Sep 30, 2024 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [03185ed878](https://bsd-hardware.info/?probe=03185ed878) | Sep 29, 2024 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [9d4ad1a258](https://bsd-hardware.info/?probe=9d4ad1a258) | Sep 26, 2024 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [4e733b287a](https://bsd-hardware.info/?probe=4e733b287a) | Sep 20, 2024 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [c2e72acbcd](https://bsd-hardware.info/?probe=c2e72acbcd) | Sep 17, 2024 |
| CncTion       | J4125-4L V1.0               | Desktop     | [55e3221edf](https://bsd-hardware.info/?probe=55e3221edf) | Sep 09, 2024 |
| ASRock        | Z87M Pro4                   | Desktop     | [dbbdcc1fe6](https://bsd-hardware.info/?probe=dbbdcc1fe6) | Aug 31, 2024 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [f78f3487b8](https://bsd-hardware.info/?probe=f78f3487b8) | Aug 27, 2024 |
| Acer          | Aspire 5551                 | Notebook    | [861d3a83cc](https://bsd-hardware.info/?probe=861d3a83cc) | Aug 27, 2024 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [d5e4a58748](https://bsd-hardware.info/?probe=d5e4a58748) | Aug 27, 2024 |
| ASRock        | Z87M Pro4                   | Desktop     | [2ddfd242d0](https://bsd-hardware.info/?probe=2ddfd242d0) | Aug 27, 2024 |
| Acer          | Aspire 5551                 | Notebook    | [07da5932a6](https://bsd-hardware.info/?probe=07da5932a6) | Aug 27, 2024 |
| CncTion       | J4125-4L V1.0               | Desktop     | [595c124d74](https://bsd-hardware.info/?probe=595c124d74) | Aug 20, 2024 |
| CncTion       | J4125-4L V1.0               | Desktop     | [9dec1304e2](https://bsd-hardware.info/?probe=9dec1304e2) | Aug 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [5194f3264e](https://bsd-hardware.info/?probe=5194f3264e) | Aug 19, 2024 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [e7df8e47f0](https://bsd-hardware.info/?probe=e7df8e47f0) | Aug 17, 2024 |
| Intelbras     | S41ILx                      | Notebook    | [85e9cf50b4](https://bsd-hardware.info/?probe=85e9cf50b4) | Aug 16, 2024 |
| Itautec       | IS12UT0 versao1             | Desktop     | [0df5f3f7e0](https://bsd-hardware.info/?probe=0df5f3f7e0) | Aug 14, 2024 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [b34365cda2](https://bsd-hardware.info/?probe=b34365cda2) | Aug 08, 2024 |
| ASRock        | B550 PG Riptide             | Desktop     | [2e59d3c157](https://bsd-hardware.info/?probe=2e59d3c157) | Aug 05, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [248e52de1a](https://bsd-hardware.info/?probe=248e52de1a) | Aug 05, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [242b9ea518](https://bsd-hardware.info/?probe=242b9ea518) | Aug 04, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [7ed3471df1](https://bsd-hardware.info/?probe=7ed3471df1) | Aug 04, 2024 |
| Unknown       | DH61BR G32662-203           | Desktop     | [596a891e0a](https://bsd-hardware.info/?probe=596a891e0a) | Aug 04, 2024 |
| Intel         | E5-A99 V1.2                 | Desktop     | [5b39b1d1c0](https://bsd-hardware.info/?probe=5b39b1d1c0) | Jul 31, 2024 |
| Intel         | X99-P4 V8.0                 | Desktop     | [0b82977c6e](https://bsd-hardware.info/?probe=0b82977c6e) | Jul 31, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [cd3e80c5af](https://bsd-hardware.info/?probe=cd3e80c5af) | Jul 28, 2024 |
| Unknown       | 1.0                         | Desktop     | [94f03e97ea](https://bsd-hardware.info/?probe=94f03e97ea) | Jul 27, 2024 |
| Unknown       | DH61BR G32662-203           | Desktop     | [6e073b5233](https://bsd-hardware.info/?probe=6e073b5233) | Jul 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [5bc1c6ba5f](https://bsd-hardware.info/?probe=5bc1c6ba5f) | Jul 26, 2024 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [ed6505a58e](https://bsd-hardware.info/?probe=ed6505a58e) | Jul 19, 2024 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [b1de030d31](https://bsd-hardware.info/?probe=b1de030d31) | Jul 19, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [7a5e3b5861](https://bsd-hardware.info/?probe=7a5e3b5861) | Jul 07, 2024 |
| Lenovo        | ThinkPad X230 2325SCM       | Notebook    | [8406cad5be](https://bsd-hardware.info/?probe=8406cad5be) | Jul 06, 2024 |
| Unknown       | Unknown                     | Notebook    | [d424bffcf6](https://bsd-hardware.info/?probe=d424bffcf6) | Jul 04, 2024 |
| Intel         | J1900                       | Desktop     | [475a904b20](https://bsd-hardware.info/?probe=475a904b20) | Jul 04, 2024 |
| Dell          | Inspiron 3501               | Notebook    | [058d42521c](https://bsd-hardware.info/?probe=058d42521c) | Jun 29, 2024 |
| Dell EMC      | EDGE620-CPU A00             | Desktop     | [970f4eb5d1](https://bsd-hardware.info/?probe=970f4eb5d1) | Jun 24, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6d499422cd](https://bsd-hardware.info/?probe=6d499422cd) | Jun 23, 2024 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [7b0f897223](https://bsd-hardware.info/?probe=7b0f897223) | Jun 21, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [5ea99ffcb7](https://bsd-hardware.info/?probe=5ea99ffcb7) | Jun 18, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [6091912e69](https://bsd-hardware.info/?probe=6091912e69) | Jun 16, 2024 |
| Dell          | 0RD5H2 A05                  | Server      | [8681367f98](https://bsd-hardware.info/?probe=8681367f98) | Jun 15, 2024 |
| Intel         | X99-P4 V8.0                 | Desktop     | [f301ad31cf](https://bsd-hardware.info/?probe=f301ad31cf) | Jun 12, 2024 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [3ef620dd9a](https://bsd-hardware.info/?probe=3ef620dd9a) | Jun 12, 2024 |
| Dell          | 0RD5H2 A05                  | Server      | [08325d81ce](https://bsd-hardware.info/?probe=08325d81ce) | Jun 11, 2024 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [4e6d8019c0](https://bsd-hardware.info/?probe=4e6d8019c0) | Jun 05, 2024 |
| pine64        | rock64_rk3328               | Desktop     | [d417f7c182](https://bsd-hardware.info/?probe=d417f7c182) | May 30, 2024 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [04f0387794](https://bsd-hardware.info/?probe=04f0387794) | May 30, 2024 |
| Megaware      | MW-HDC-M 02/24/2012 - MW... | Desktop     | [9a662cb553](https://bsd-hardware.info/?probe=9a662cb553) | May 24, 2024 |
| Megaware      | MW-HDC-M 02/24/2012 - MW... | Desktop     | [ec0376f009](https://bsd-hardware.info/?probe=ec0376f009) | May 24, 2024 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [0bd6e7fcf6](https://bsd-hardware.info/?probe=0bd6e7fcf6) | May 24, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [c605cdb907](https://bsd-hardware.info/?probe=c605cdb907) | May 11, 2024 |
| Unknown       | DH61BR G32662-203           | Desktop     | [f9ebf93574](https://bsd-hardware.info/?probe=f9ebf93574) | May 06, 2024 |
| Lenovo        | B40-30 80F1                 | Notebook    | [98be66c2e6](https://bsd-hardware.info/?probe=98be66c2e6) | May 03, 2024 |
| Lenovo        | ThinkPad E490 20N9S48S00    | Notebook    | [f70fb4bd81](https://bsd-hardware.info/?probe=f70fb4bd81) | May 01, 2024 |
| Intel         | YC-4L-002                   | Desktop     | [ac058ece5c](https://bsd-hardware.info/?probe=ac058ece5c) | Apr 30, 2024 |
| Dell          | 04YP6J A00                  | Desktop     | [92b5c39349](https://bsd-hardware.info/?probe=92b5c39349) | Apr 29, 2024 |
| Acer          | Aspire 5551                 | Notebook    | [ee15a7d2b5](https://bsd-hardware.info/?probe=ee15a7d2b5) | Apr 29, 2024 |
| ASRock        | Z87M Pro4                   | Desktop     | [91a487bad5](https://bsd-hardware.info/?probe=91a487bad5) | Apr 29, 2024 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [28856a768f](https://bsd-hardware.info/?probe=28856a768f) | Apr 23, 2024 |
| ECS           | KBLU-MINI                   | Desktop     | [0380406242](https://bsd-hardware.info/?probe=0380406242) | Apr 18, 2024 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [e79deb66c2](https://bsd-hardware.info/?probe=e79deb66c2) | Apr 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [23cc24ddfc](https://bsd-hardware.info/?probe=23cc24ddfc) | Apr 13, 2024 |
| Lenovo        | ThinkPad E490 20N9S48S00    | Notebook    | [a755c9e288](https://bsd-hardware.info/?probe=a755c9e288) | Apr 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [e72e2a9dae](https://bsd-hardware.info/?probe=e72e2a9dae) | Apr 12, 2024 |
| Supermicro    | 92.510.02134-3              | Desktop     | [e0b08a8502](https://bsd-hardware.info/?probe=e0b08a8502) | Apr 05, 2024 |
| Supermicro    | 92.510.02134-3              | Desktop     | [8f5fb5245e](https://bsd-hardware.info/?probe=8f5fb5245e) | Apr 05, 2024 |
| Dell          | 06HR05 A00                  | Desktop     | [9505b5cf4f](https://bsd-hardware.info/?probe=9505b5cf4f) | Apr 02, 2024 |
| Intel         | BOX-J41L4A V3.01            | Desktop     | [8e31084435](https://bsd-hardware.info/?probe=8e31084435) | Mar 29, 2024 |
| CNCTION-IA... | Unknown                     | Desktop     | [42996aca85](https://bsd-hardware.info/?probe=42996aca85) | Mar 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [157a2cbf6c](https://bsd-hardware.info/?probe=157a2cbf6c) | Mar 15, 2024 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [bb5384ee3e](https://bsd-hardware.info/?probe=bb5384ee3e) | Mar 14, 2024 |
| Dell          | Inspiron 15 3511            | Notebook    | [7ac9f4bd85](https://bsd-hardware.info/?probe=7ac9f4bd85) | Mar 14, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [e97bd00aad](https://bsd-hardware.info/?probe=e97bd00aad) | Mar 13, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [fd60868096](https://bsd-hardware.info/?probe=fd60868096) | Mar 10, 2024 |
| LG Electro... | R590-P.BE54P1               | Desktop     | [120ec3afe6](https://bsd-hardware.info/?probe=120ec3afe6) | Mar 09, 2024 |
| Intel         | ZC-R40-4125                 | Desktop     | [6f76935200](https://bsd-hardware.info/?probe=6f76935200) | Mar 05, 2024 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [b0e5a68883](https://bsd-hardware.info/?probe=b0e5a68883) | Mar 03, 2024 |
| Dell          | 072J5G A03                  | Server      | [04e1610925](https://bsd-hardware.info/?probe=04e1610925) | Mar 02, 2024 |
| ASRock        | J4005B-ITX                  | Desktop     | [ffcfdde6b9](https://bsd-hardware.info/?probe=ffcfdde6b9) | Feb 29, 2024 |
| Itautec       | Infoway                     | Notebook    | [35399f6e75](https://bsd-hardware.info/?probe=35399f6e75) | Feb 28, 2024 |
| Lenovo        | B40-30 80F1                 | Notebook    | [9e435212e2](https://bsd-hardware.info/?probe=9e435212e2) | Feb 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [96711959a2](https://bsd-hardware.info/?probe=96711959a2) | Feb 20, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [fa2107c718](https://bsd-hardware.info/?probe=fa2107c718) | Feb 11, 2024 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [96f998dae3](https://bsd-hardware.info/?probe=96f998dae3) | Feb 09, 2024 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [cb6b8e5aef](https://bsd-hardware.info/?probe=cb6b8e5aef) | Feb 02, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [952fa413fe](https://bsd-hardware.info/?probe=952fa413fe) | Feb 01, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [b66edf2033](https://bsd-hardware.info/?probe=b66edf2033) | Jan 31, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [94f04895fe](https://bsd-hardware.info/?probe=94f04895fe) | Jan 27, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [28539d7eb4](https://bsd-hardware.info/?probe=28539d7eb4) | Jan 24, 2024 |
| HP            | s5-1210br                   | Desktop     | [9ce94bc2b7](https://bsd-hardware.info/?probe=9ce94bc2b7) | Jan 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [dc8b338a3e](https://bsd-hardware.info/?probe=dc8b338a3e) | Jan 19, 2024 |
| GoWin Solu... | R86S                        | Desktop     | [43c637977a](https://bsd-hardware.info/?probe=43c637977a) | Jan 19, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [b9e259b247](https://bsd-hardware.info/?probe=b9e259b247) | Jan 19, 2024 |
| Lenovo        | ThinkPad X220 42912Z1       | Notebook    | [1abc94b4b1](https://bsd-hardware.info/?probe=1abc94b4b1) | Jan 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [f516302dc5](https://bsd-hardware.info/?probe=f516302dc5) | Jan 13, 2024 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | Desktop     | [2fb631cb20](https://bsd-hardware.info/?probe=2fb631cb20) | Jan 13, 2024 |
| CNCTION-IA... | Unknown                     | Desktop     | [52a8efdb73](https://bsd-hardware.info/?probe=52a8efdb73) | Jan 07, 2024 |
| Dell          | 0TY019 A02                  | Server      | [0c569f887e](https://bsd-hardware.info/?probe=0c569f887e) | Jan 02, 2024 |
| Intel         | BOX-J41L4A V3.01            | Desktop     | [dd8cccddff](https://bsd-hardware.info/?probe=dd8cccddff) | Dec 29, 2023 |
| Intel         | BOX-J41L4A V3.01            | Desktop     | [9294250e89](https://bsd-hardware.info/?probe=9294250e89) | Dec 29, 2023 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [bf5cb7eb21](https://bsd-hardware.info/?probe=bf5cb7eb21) | Dec 29, 2023 |
| Dell          | 04YP6J A00                  | Desktop     | [9ed1a43f79](https://bsd-hardware.info/?probe=9ed1a43f79) | Dec 29, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [fa4e90491b](https://bsd-hardware.info/?probe=fa4e90491b) | Dec 29, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [1c769a311c](https://bsd-hardware.info/?probe=1c769a311c) | Dec 29, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [7387d0de6b](https://bsd-hardware.info/?probe=7387d0de6b) | Dec 28, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [19a5ef28f8](https://bsd-hardware.info/?probe=19a5ef28f8) | Dec 28, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [8b71e16af3](https://bsd-hardware.info/?probe=8b71e16af3) | Dec 27, 2023 |
| ASRock        | J4005B-ITX                  | Desktop     | [8ad375a02f](https://bsd-hardware.info/?probe=8ad375a02f) | Dec 26, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | Desktop     | [491c854348](https://bsd-hardware.info/?probe=491c854348) | Dec 25, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [2c652aa0a1](https://bsd-hardware.info/?probe=2c652aa0a1) | Dec 16, 2023 |
| ASRock        | J4005B-ITX                  | Desktop     | [2ffc965b2e](https://bsd-hardware.info/?probe=2ffc965b2e) | Dec 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [0bc43bd220](https://bsd-hardware.info/?probe=0bc43bd220) | Dec 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [79486fa5ff](https://bsd-hardware.info/?probe=79486fa5ff) | Dec 08, 2023 |
| Dell          | 0411GW A02                  | Desktop     | [f2bc8b79b0](https://bsd-hardware.info/?probe=f2bc8b79b0) | Dec 05, 2023 |
| Intel         | Geminilake                  | Desktop     | [59d13c77e8](https://bsd-hardware.info/?probe=59d13c77e8) | Dec 02, 2023 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [760a22c4b8](https://bsd-hardware.info/?probe=760a22c4b8) | Dec 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a9b3beae66](https://bsd-hardware.info/?probe=a9b3beae66) | Dec 02, 2023 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [972ad3cb48](https://bsd-hardware.info/?probe=972ad3cb48) | Dec 02, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [8d7c03be2f](https://bsd-hardware.info/?probe=8d7c03be2f) | Nov 28, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [b11a972371](https://bsd-hardware.info/?probe=b11a972371) | Nov 24, 2023 |
| HP            | 3646h                       | Desktop     | [b3083001a4](https://bsd-hardware.info/?probe=b3083001a4) | Nov 24, 2023 |
| Intel         | NUC62R 2C                   | Mini pc     | [d47608f986](https://bsd-hardware.info/?probe=d47608f986) | Nov 23, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [a4eded7a52](https://bsd-hardware.info/?probe=a4eded7a52) | Nov 22, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [2aa8175a33](https://bsd-hardware.info/?probe=2aa8175a33) | Nov 17, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [3f63ee5447](https://bsd-hardware.info/?probe=3f63ee5447) | Nov 13, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [9bc3c5e163](https://bsd-hardware.info/?probe=9bc3c5e163) | Nov 05, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [e49d3f40b6](https://bsd-hardware.info/?probe=e49d3f40b6) | Nov 05, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [dfc8115b4a](https://bsd-hardware.info/?probe=dfc8115b4a) | Oct 24, 2023 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [81e77caff8](https://bsd-hardware.info/?probe=81e77caff8) | Oct 23, 2023 |
| Lenovo        | B40-30 80F1                 | Notebook    | [00c5e6adda](https://bsd-hardware.info/?probe=00c5e6adda) | Oct 03, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [a32967cbc5](https://bsd-hardware.info/?probe=a32967cbc5) | Sep 30, 2023 |
| Dell          | 08D89F A00                  | Server      | [6a9c0620a0](https://bsd-hardware.info/?probe=6a9c0620a0) | Sep 28, 2023 |
| Dell          | 0J555H A00                  | Server      | [3c395551d4](https://bsd-hardware.info/?probe=3c395551d4) | Sep 28, 2023 |
| Dell          | 08D89F A00                  | Server      | [de921e42d3](https://bsd-hardware.info/?probe=de921e42d3) | Sep 28, 2023 |
| Dell          | 0VV3F2 A01                  | Server      | [69b9504be5](https://bsd-hardware.info/?probe=69b9504be5) | Sep 25, 2023 |
| GPD           | G1619-04                    | Notebook    | [30ad9b72b5](https://bsd-hardware.info/?probe=30ad9b72b5) | Sep 23, 2023 |
| Dell          | 0VRWRC A01                  | Desktop     | [6c85a42e64](https://bsd-hardware.info/?probe=6c85a42e64) | Sep 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [50f509c032](https://bsd-hardware.info/?probe=50f509c032) | Sep 05, 2023 |
| Dell          | 0JCTF8 A00                  | Desktop     | [a2be5a5f0f](https://bsd-hardware.info/?probe=a2be5a5f0f) | Aug 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e5cae16104](https://bsd-hardware.info/?probe=e5cae16104) | Aug 23, 2023 |
| MSI           | G31M3-L V2                  | Desktop     | [7335b3dea2](https://bsd-hardware.info/?probe=7335b3dea2) | Aug 22, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [bdd9c72e7c](https://bsd-hardware.info/?probe=bdd9c72e7c) | Aug 18, 2023 |
| Dell          | 05FT2M A04                  | Server      | [73afce6eeb](https://bsd-hardware.info/?probe=73afce6eeb) | Aug 17, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [f25db83457](https://bsd-hardware.info/?probe=f25db83457) | Aug 15, 2023 |
| Sophos        | SG                          | Firewall    | [5d3b81800b](https://bsd-hardware.info/?probe=5d3b81800b) | Aug 09, 2023 |
| Sophos        | SG                          | Firewall    | [bcb2c49854](https://bsd-hardware.info/?probe=bcb2c49854) | Aug 09, 2023 |
| Intel         | H81                         | Desktop     | [80f40918ce](https://bsd-hardware.info/?probe=80f40918ce) | Aug 07, 2023 |
| Compaq        | Presario CQ-17              | Notebook    | [f97feb2db0](https://bsd-hardware.info/?probe=f97feb2db0) | Aug 04, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [cbc7fc88d0](https://bsd-hardware.info/?probe=cbc7fc88d0) | Aug 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [8b7315305c](https://bsd-hardware.info/?probe=8b7315305c) | Jul 31, 2023 |
| ChangWang     | CW56-58                     | Desktop     | [f418f5407c](https://bsd-hardware.info/?probe=f418f5407c) | Jul 30, 2023 |
| Dell          | 0GDG8Y A02                  | Desktop     | [651f6bf18f](https://bsd-hardware.info/?probe=651f6bf18f) | Jul 28, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [e26ef35879](https://bsd-hardware.info/?probe=e26ef35879) | Jul 28, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [1cd9d4cb7f](https://bsd-hardware.info/?probe=1cd9d4cb7f) | Jul 24, 2023 |
| Dell          | 0TD1J8 A00                  | Desktop     | [c99bc29ce0](https://bsd-hardware.info/?probe=c99bc29ce0) | Jul 24, 2023 |
| Intel         | H55                         | Desktop     | [11c9e5747f](https://bsd-hardware.info/?probe=11c9e5747f) | Jul 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [8ced2a3a4d](https://bsd-hardware.info/?probe=8ced2a3a4d) | Jul 17, 2023 |
| Intel         | H55                         | Desktop     | [da217d0606](https://bsd-hardware.info/?probe=da217d0606) | Jul 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [a9c88b1c80](https://bsd-hardware.info/?probe=a9c88b1c80) | Jul 11, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [c546c0a84f](https://bsd-hardware.info/?probe=c546c0a84f) | Jul 06, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3151e6d3bb](https://bsd-hardware.info/?probe=3151e6d3bb) | Jul 05, 2023 |
| Dell          | 0TW855 A07                  | Server      | [6b0d9156a9](https://bsd-hardware.info/?probe=6b0d9156a9) | Jun 26, 2023 |
| Dell          | Latitude 5490               | Notebook    | [b638c1b2b1](https://bsd-hardware.info/?probe=b638c1b2b1) | Jun 23, 2023 |
| Dell          | 02YRK5 A03                  | Desktop     | [2d631e9745](https://bsd-hardware.info/?probe=2d631e9745) | Jun 23, 2023 |
| HP            | 1000                        | Notebook    | [21faecd7a6](https://bsd-hardware.info/?probe=21faecd7a6) | Jun 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b6e5a7e7bc](https://bsd-hardware.info/?probe=b6e5a7e7bc) | Jun 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [2d50927445](https://bsd-hardware.info/?probe=2d50927445) | Jun 18, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | Desktop     | [4e827b2cbf](https://bsd-hardware.info/?probe=4e827b2cbf) | Jun 16, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | Desktop     | [3d71827388](https://bsd-hardware.info/?probe=3d71827388) | Jun 16, 2023 |
| IBM           | 69Y5698                     | Server      | [9f5eb975e0](https://bsd-hardware.info/?probe=9f5eb975e0) | Jun 16, 2023 |
| Dell          | 053CWD A00                  | Desktop     | [7a5418ac7e](https://bsd-hardware.info/?probe=7a5418ac7e) | Jun 16, 2023 |
| CNCTION-IA... | Unknown                     | Desktop     | [1a0573767e](https://bsd-hardware.info/?probe=1a0573767e) | Jun 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [93dcd13cb6](https://bsd-hardware.info/?probe=93dcd13cb6) | Jun 15, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [a6c6c43f64](https://bsd-hardware.info/?probe=a6c6c43f64) | Jun 13, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [ffe9b51f78](https://bsd-hardware.info/?probe=ffe9b51f78) | Jun 12, 2023 |
| Lenovo        | B40-30 80F1                 | Notebook    | [769c678314](https://bsd-hardware.info/?probe=769c678314) | Jun 10, 2023 |
| Soyo          | SY-YL B550M                 | Desktop     | [1d1138e3c5](https://bsd-hardware.info/?probe=1d1138e3c5) | Jun 05, 2023 |
| Soyo          | SY-YL B550M                 | Desktop     | [79c6c2a177](https://bsd-hardware.info/?probe=79c6c2a177) | Jun 05, 2023 |
| YANYU         | N39SL                       | Desktop     | [e487646fbf](https://bsd-hardware.info/?probe=e487646fbf) | Jun 05, 2023 |
| Intel         | JSL MRD                     | Desktop     | [f4606f2c25](https://bsd-hardware.info/?probe=f4606f2c25) | Jun 03, 2023 |
| Intel         | JSL MRD                     | Desktop     | [3d5e12d1cf](https://bsd-hardware.info/?probe=3d5e12d1cf) | Jun 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [13c80903b5](https://bsd-hardware.info/?probe=13c80903b5) | May 31, 2023 |
| Intel         | H81                         | Desktop     | [e0e15704fc](https://bsd-hardware.info/?probe=e0e15704fc) | May 29, 2023 |
| Dell          | 0GDG8Y A02                  | Desktop     | [fc6906c72a](https://bsd-hardware.info/?probe=fc6906c72a) | May 27, 2023 |
| Lenovo        | 36C5 SDK0L77767 WIN 3423... | Desktop     | [a19f434ae4](https://bsd-hardware.info/?probe=a19f434ae4) | May 26, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [c39ea00de5](https://bsd-hardware.info/?probe=c39ea00de5) | May 25, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [efd50a99b7](https://bsd-hardware.info/?probe=efd50a99b7) | May 23, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [6e82e43784](https://bsd-hardware.info/?probe=6e82e43784) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [fe3f8769f8](https://bsd-hardware.info/?probe=fe3f8769f8) | May 22, 2023 |
| Sony          | VPCEG15FB                   | Notebook    | [8777493861](https://bsd-hardware.info/?probe=8777493861) | May 21, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | Notebook    | [5e25a49c65](https://bsd-hardware.info/?probe=5e25a49c65) | May 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [d8bec309da](https://bsd-hardware.info/?probe=d8bec309da) | May 16, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | Notebook    | [7732b2cfa7](https://bsd-hardware.info/?probe=7732b2cfa7) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | Notebook    | [b6071c549a](https://bsd-hardware.info/?probe=b6071c549a) | May 15, 2023 |
| Sony          | SVF14A15CBB                 | Notebook    | [4ada2dca25](https://bsd-hardware.info/?probe=4ada2dca25) | May 14, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [2ce057e389](https://bsd-hardware.info/?probe=2ce057e389) | May 14, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [fa87f4741a](https://bsd-hardware.info/?probe=fa87f4741a) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [bd81294acc](https://bsd-hardware.info/?probe=bd81294acc) | May 13, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [cace71018f](https://bsd-hardware.info/?probe=cace71018f) | May 11, 2023 |
| Intel         | HuronRiver Platform         | Notebook    | [83494ffd65](https://bsd-hardware.info/?probe=83494ffd65) | May 11, 2023 |
| Gigabyte      | H61M-DS2H                   | Desktop     | [e1856048c0](https://bsd-hardware.info/?probe=e1856048c0) | May 10, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [4353bb0195](https://bsd-hardware.info/?probe=4353bb0195) | May 09, 2023 |
| Intel         | NUC62R 2C                   | Mini pc     | [a1cb2ad4f4](https://bsd-hardware.info/?probe=a1cb2ad4f4) | May 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [ed836ce6e5](https://bsd-hardware.info/?probe=ed836ce6e5) | May 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [15c2e0790b](https://bsd-hardware.info/?probe=15c2e0790b) | Apr 27, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b46f671e20](https://bsd-hardware.info/?probe=b46f671e20) | Apr 25, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [827308827b](https://bsd-hardware.info/?probe=827308827b) | Apr 24, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [ef4870410f](https://bsd-hardware.info/?probe=ef4870410f) | Apr 23, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [a6141b809a](https://bsd-hardware.info/?probe=a6141b809a) | Apr 21, 2023 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [024173445b](https://bsd-hardware.info/?probe=024173445b) | Apr 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [cff3d92e32](https://bsd-hardware.info/?probe=cff3d92e32) | Apr 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [6d44a8e8c8](https://bsd-hardware.info/?probe=6d44a8e8c8) | Apr 15, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [74986a169a](https://bsd-hardware.info/?probe=74986a169a) | Apr 15, 2023 |
| Samsung       | 370E4K                      | Notebook    | [c363d008bf](https://bsd-hardware.info/?probe=c363d008bf) | Apr 13, 2023 |
| Lenovo        | ThinkPad X230 23257EP       | Notebook    | [e94085cd2d](https://bsd-hardware.info/?probe=e94085cd2d) | Apr 12, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [a149d0b4b5](https://bsd-hardware.info/?probe=a149d0b4b5) | Apr 10, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [ffbe23b7d8](https://bsd-hardware.info/?probe=ffbe23b7d8) | Apr 09, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [592e08cdd2](https://bsd-hardware.info/?probe=592e08cdd2) | Apr 09, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [c98356d42b](https://bsd-hardware.info/?probe=c98356d42b) | Apr 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [4e1d6069e9](https://bsd-hardware.info/?probe=4e1d6069e9) | Apr 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cce6d0463](https://bsd-hardware.info/?probe=9cce6d0463) | Apr 03, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [3592fe0b85](https://bsd-hardware.info/?probe=3592fe0b85) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [a0548bbb6e](https://bsd-hardware.info/?probe=a0548bbb6e) | Mar 31, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [16d1e0aa3e](https://bsd-hardware.info/?probe=16d1e0aa3e) | Mar 31, 2023 |
| Dell          | 0MX4YF A01                  | Server      | [6a6b7d1e6d](https://bsd-hardware.info/?probe=6a6b7d1e6d) | Mar 29, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [98777ba333](https://bsd-hardware.info/?probe=98777ba333) | Mar 27, 2023 |
| Lenovo        | ThinkPad T430 2349G5P       | Notebook    | [9ea67d3893](https://bsd-hardware.info/?probe=9ea67d3893) | Mar 27, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [cbb9f6bfbb](https://bsd-hardware.info/?probe=cbb9f6bfbb) | Mar 17, 2023 |
| Positivo      | POS-PIB150DT                | Desktop     | [f0158da9e1](https://bsd-hardware.info/?probe=f0158da9e1) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [7399558d80](https://bsd-hardware.info/?probe=7399558d80) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [3fb2d0d992](https://bsd-hardware.info/?probe=3fb2d0d992) | Mar 17, 2023 |
| Lenovo        | ThinkPad X201 36801T6       | Notebook    | [decaf0c347](https://bsd-hardware.info/?probe=decaf0c347) | Mar 17, 2023 |
| Dell          | Inspiron 5557               | Notebook    | [ff199c6d21](https://bsd-hardware.info/?probe=ff199c6d21) | Mar 16, 2023 |
| Samsung       | 275E4E/275E5E               | Notebook    | [dd4f7ef594](https://bsd-hardware.info/?probe=dd4f7ef594) | Mar 15, 2023 |
| T-bao         | MINI PC                     | Desktop     | [d4440566b0](https://bsd-hardware.info/?probe=d4440566b0) | Mar 13, 2023 |
| Positivo      | POS-PIB150DT                | Desktop     | [5f39c02bc9](https://bsd-hardware.info/?probe=5f39c02bc9) | Mar 13, 2023 |
| Intel         | DP55WB AAE64798-207         | Desktop     | [1c8295549c](https://bsd-hardware.info/?probe=1c8295549c) | Mar 10, 2023 |
| HP            | ProLiant DL160 Gen8         | Server      | [43c3eafd9d](https://bsd-hardware.info/?probe=43c3eafd9d) | Mar 07, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [ac0118b05e](https://bsd-hardware.info/?probe=ac0118b05e) | Mar 03, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [b663ccd3cb](https://bsd-hardware.info/?probe=b663ccd3cb) | Mar 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [a919e85270](https://bsd-hardware.info/?probe=a919e85270) | Feb 28, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [b480a98b22](https://bsd-hardware.info/?probe=b480a98b22) | Feb 26, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [45549e4faf](https://bsd-hardware.info/?probe=45549e4faf) | Feb 25, 2023 |
| Dell          | 0WR7PY A00                  | Desktop     | [70b222c73b](https://bsd-hardware.info/?probe=70b222c73b) | Feb 23, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [db00abb833](https://bsd-hardware.info/?probe=db00abb833) | Feb 19, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [fd39a615de](https://bsd-hardware.info/?probe=fd39a615de) | Feb 19, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [6af537ff20](https://bsd-hardware.info/?probe=6af537ff20) | Feb 18, 2023 |
| Lenovo        | ThinkPad T430u 33522D5      | Notebook    | [d5bbbb8cbe](https://bsd-hardware.info/?probe=d5bbbb8cbe) | Feb 17, 2023 |
| ASRock        | A320M-DGS                   | Desktop     | [032d7f0c91](https://bsd-hardware.info/?probe=032d7f0c91) | Feb 17, 2023 |
| Dell          | 0CN7CM A06                  | Server      | [a4e6db54d8](https://bsd-hardware.info/?probe=a4e6db54d8) | Feb 10, 2023 |
| Acer          | Aspire 4739Z                | Notebook    | [1e97a0b938](https://bsd-hardware.info/?probe=1e97a0b938) | Feb 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [34d9347fc3](https://bsd-hardware.info/?probe=34d9347fc3) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [3345f50844](https://bsd-hardware.info/?probe=3345f50844) | Feb 06, 2023 |
| Dell          | 0DFXXD A00                  | Server      | [299fce37cb](https://bsd-hardware.info/?probe=299fce37cb) | Feb 06, 2023 |
| Dell          | 0DFXXD A00                  | Server      | [3c867871f2](https://bsd-hardware.info/?probe=3c867871f2) | Feb 06, 2023 |
| AZW           | U59                         | Desktop     | [8073f1f5f3](https://bsd-hardware.info/?probe=8073f1f5f3) | Feb 04, 2023 |
| Lenovo        | SKYBAY 31900002 WIN 1801... | All in one  | [725797b27e](https://bsd-hardware.info/?probe=725797b27e) | Feb 02, 2023 |
| ASRock        | J4005B-ITX                  | Desktop     | [c4bf6a3b8c](https://bsd-hardware.info/?probe=c4bf6a3b8c) | Feb 01, 2023 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [73b6128279](https://bsd-hardware.info/?probe=73b6128279) | Jan 31, 2023 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [3fa3b849a3](https://bsd-hardware.info/?probe=3fa3b849a3) | Jan 31, 2023 |
| Biostar       | TB250-BTC+                  | Desktop     | [0a39ffa716](https://bsd-hardware.info/?probe=0a39ffa716) | Jan 24, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [9cd4d2810a](https://bsd-hardware.info/?probe=9cd4d2810a) | Jan 23, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [6dc0fddda1](https://bsd-hardware.info/?probe=6dc0fddda1) | Jan 22, 2023 |
| Dell          | 0H723K A05                  | Server      | [561152d95d](https://bsd-hardware.info/?probe=561152d95d) | Jan 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [32477354bc](https://bsd-hardware.info/?probe=32477354bc) | Jan 19, 2023 |
| Lenovo        | B40-70 80F30005BR           | Notebook    | [17333d88cf](https://bsd-hardware.info/?probe=17333d88cf) | Jan 17, 2023 |
| Dell          | 0CN7CM A06                  | Server      | [33c450dade](https://bsd-hardware.info/?probe=33c450dade) | Jan 11, 2023 |
| Dell          | 0CN7CM A06                  | Server      | [7a63630a51](https://bsd-hardware.info/?probe=7a63630a51) | Jan 06, 2023 |
| Dell          | 0CN7CM A06                  | Server      | [996218def1](https://bsd-hardware.info/?probe=996218def1) | Jan 06, 2023 |
| AMI           | MNHO-048                    | Desktop     | [fbd9fa83d9](https://bsd-hardware.info/?probe=fbd9fa83d9) | Jan 05, 2023 |
| Dell          | 0CU409                      | Desktop     | [a547f05175](https://bsd-hardware.info/?probe=a547f05175) | Jan 02, 2023 |
| Intel         | S3420GP E51976-407          | Server      | [c614a1e46f](https://bsd-hardware.info/?probe=c614a1e46f) | Dec 20, 2022 |
| Dell          | 02YRK5 A03                  | Desktop     | [547b1abce0](https://bsd-hardware.info/?probe=547b1abce0) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [3a9623cfb4](https://bsd-hardware.info/?probe=3a9623cfb4) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [0314add226](https://bsd-hardware.info/?probe=0314add226) | Dec 16, 2022 |
| Dell          | 0CU409                      | Desktop     | [718c9c5c8b](https://bsd-hardware.info/?probe=718c9c5c8b) | Dec 15, 2022 |
| Dell          | 0CU409                      | Desktop     | [161da6b850](https://bsd-hardware.info/?probe=161da6b850) | Dec 15, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [1115d508c1](https://bsd-hardware.info/?probe=1115d508c1) | Dec 09, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [529cbab9aa](https://bsd-hardware.info/?probe=529cbab9aa) | Dec 01, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [84d1656c05](https://bsd-hardware.info/?probe=84d1656c05) | Nov 30, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [3dd9e3557c](https://bsd-hardware.info/?probe=3dd9e3557c) | Nov 30, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [88929a3594](https://bsd-hardware.info/?probe=88929a3594) | Nov 25, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [ef6190861c](https://bsd-hardware.info/?probe=ef6190861c) | Nov 25, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [76ecd68ff6](https://bsd-hardware.info/?probe=76ecd68ff6) | Nov 25, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [898f645e32](https://bsd-hardware.info/?probe=898f645e32) | Nov 25, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [61f8a35700](https://bsd-hardware.info/?probe=61f8a35700) | Nov 25, 2022 |
| Dell          | 0TW855 A07                  | Server      | [d2d859c434](https://bsd-hardware.info/?probe=d2d859c434) | Nov 22, 2022 |
| Dell          | 0TW855 A07                  | Server      | [dbeaf80924](https://bsd-hardware.info/?probe=dbeaf80924) | Nov 20, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [d3cbc9d6ca](https://bsd-hardware.info/?probe=d3cbc9d6ca) | Nov 19, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [5c37012f33](https://bsd-hardware.info/?probe=5c37012f33) | Nov 10, 2022 |
| Dell          | 0F428D A00                  | Desktop     | [0a9ca655d3](https://bsd-hardware.info/?probe=0a9ca655d3) | Nov 08, 2022 |
| Supermicro    | X8DT6                       | Server      | [e7536e4a4c](https://bsd-hardware.info/?probe=e7536e4a4c) | Nov 07, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [6efd22e598](https://bsd-hardware.info/?probe=6efd22e598) | Nov 04, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [0841d714d0](https://bsd-hardware.info/?probe=0841d714d0) | Nov 03, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [4dfd35f622](https://bsd-hardware.info/?probe=4dfd35f622) | Oct 31, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [ed59c93b79](https://bsd-hardware.info/?probe=ed59c93b79) | Oct 29, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [764a816130](https://bsd-hardware.info/?probe=764a816130) | Oct 21, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [09bca1b1ff](https://bsd-hardware.info/?probe=09bca1b1ff) | Oct 20, 2022 |
| Lenovo        | ThinkCentre M57p 6078AJ6    | Desktop     | [a808a7360d](https://bsd-hardware.info/?probe=a808a7360d) | Oct 14, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [097a263bfc](https://bsd-hardware.info/?probe=097a263bfc) | Oct 11, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [58b53464d1](https://bsd-hardware.info/?probe=58b53464d1) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [c70e4d6b3c](https://bsd-hardware.info/?probe=c70e4d6b3c) | Oct 10, 2022 |
| ASRock        | J4005B-ITX                  | Desktop     | [6cf37e95da](https://bsd-hardware.info/?probe=6cf37e95da) | Oct 10, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8b8f621562](https://bsd-hardware.info/?probe=8b8f621562) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [21117c0374](https://bsd-hardware.info/?probe=21117c0374) | Oct 10, 2022 |
| ASRock        | J4005B-ITX                  | Desktop     | [0e0ff27c25](https://bsd-hardware.info/?probe=0e0ff27c25) | Oct 09, 2022 |
| HP            | 86FC MVB                    | Desktop     | [56453b00c8](https://bsd-hardware.info/?probe=56453b00c8) | Oct 08, 2022 |
| HP            | 86FC MVB                    | Desktop     | [c542b16d75](https://bsd-hardware.info/?probe=c542b16d75) | Oct 08, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [9c092c9cd7](https://bsd-hardware.info/?probe=9c092c9cd7) | Oct 05, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [1fd10e86d9](https://bsd-hardware.info/?probe=1fd10e86d9) | Oct 04, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [122f6f6837](https://bsd-hardware.info/?probe=122f6f6837) | Oct 02, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [6418fd0b23](https://bsd-hardware.info/?probe=6418fd0b23) | Sep 28, 2022 |
| Lenovo        | G475 20080                  | Notebook    | [fb07463a9a](https://bsd-hardware.info/?probe=fb07463a9a) | Sep 24, 2022 |
| Lenovo        | G475 20080                  | Notebook    | [c4b1acb6d1](https://bsd-hardware.info/?probe=c4b1acb6d1) | Sep 24, 2022 |
| Dell          | 02YRK5 A03                  | Desktop     | [2ec32e432d](https://bsd-hardware.info/?probe=2ec32e432d) | Sep 20, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [ca3b8f6b48](https://bsd-hardware.info/?probe=ca3b8f6b48) | Sep 20, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [09b5ca588f](https://bsd-hardware.info/?probe=09b5ca588f) | Sep 16, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [505feb51ca](https://bsd-hardware.info/?probe=505feb51ca) | Sep 15, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [8776541164](https://bsd-hardware.info/?probe=8776541164) | Sep 09, 2022 |
| Dell          | 0W0W22 A08                  | Server      | [4d371914ed](https://bsd-hardware.info/?probe=4d371914ed) | Sep 07, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [2d3a5a5260](https://bsd-hardware.info/?probe=2d3a5a5260) | Sep 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [f2a26e2adc](https://bsd-hardware.info/?probe=f2a26e2adc) | Sep 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [05e28da420](https://bsd-hardware.info/?probe=05e28da420) | Aug 16, 2022 |
| Pegatron      | IPMIP-GS                    | Desktop     | [5ee5edb1d0](https://bsd-hardware.info/?probe=5ee5edb1d0) | Aug 16, 2022 |
| Pegatron      | IPMIP-GS                    | Desktop     | [f3c4668e00](https://bsd-hardware.info/?probe=f3c4668e00) | Aug 16, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [d61693dffb](https://bsd-hardware.info/?probe=d61693dffb) | Aug 05, 2022 |
| Dell          | 0VV3F2 A01                  | Server      | [ad01fbd5a3](https://bsd-hardware.info/?probe=ad01fbd5a3) | Aug 03, 2022 |
| Dell          | 0VV3F2 A01                  | Server      | [c0e6b1eb61](https://bsd-hardware.info/?probe=c0e6b1eb61) | Aug 03, 2022 |
| Lenovo        | ThinkPad T61 7661GY9        | Notebook    | [7ab5339eee](https://bsd-hardware.info/?probe=7ab5339eee) | Jul 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [e2a5a65135](https://bsd-hardware.info/?probe=e2a5a65135) | Jul 23, 2022 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | Desktop     | [0b29806790](https://bsd-hardware.info/?probe=0b29806790) | Jul 23, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e503017a9f](https://bsd-hardware.info/?probe=e503017a9f) | Jul 21, 2022 |
| Dell          | 0GDG8Y A02                  | Desktop     | [2f163e2a05](https://bsd-hardware.info/?probe=2f163e2a05) | Jul 21, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [f88fa027ab](https://bsd-hardware.info/?probe=f88fa027ab) | Jul 19, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [56a7002cc5](https://bsd-hardware.info/?probe=56a7002cc5) | Jul 16, 2022 |
| Gigabyte      | C847N                       | Desktop     | [4be8944950](https://bsd-hardware.info/?probe=4be8944950) | Jul 15, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [87d68034db](https://bsd-hardware.info/?probe=87d68034db) | Jul 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b09ba0c799](https://bsd-hardware.info/?probe=b09ba0c799) | Jul 12, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [56fae2295e](https://bsd-hardware.info/?probe=56fae2295e) | Jul 08, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [ba96a05e5c](https://bsd-hardware.info/?probe=ba96a05e5c) | Jul 08, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [8b2af1b843](https://bsd-hardware.info/?probe=8b2af1b843) | Jul 06, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [1cd93cd5d3](https://bsd-hardware.info/?probe=1cd93cd5d3) | Jul 04, 2022 |
| Biostar       | G41D3C                      | Desktop     | [118bd083bf](https://bsd-hardware.info/?probe=118bd083bf) | Jul 01, 2022 |
| Lenovo        | ThinkPad T410 2522CS7       | Notebook    | [a1561dacb2](https://bsd-hardware.info/?probe=a1561dacb2) | Jun 26, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [346bc6f0ae](https://bsd-hardware.info/?probe=346bc6f0ae) | Jun 20, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [a464043744](https://bsd-hardware.info/?probe=a464043744) | Jun 19, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [af923daeda](https://bsd-hardware.info/?probe=af923daeda) | Jun 12, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [bba161b618](https://bsd-hardware.info/?probe=bba161b618) | Jun 08, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [7be45ccc7e](https://bsd-hardware.info/?probe=7be45ccc7e) | Jun 08, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [848361c724](https://bsd-hardware.info/?probe=848361c724) | May 31, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [6a6450f264](https://bsd-hardware.info/?probe=6a6450f264) | May 30, 2022 |
| Dell          | 0D28YY A00                  | Desktop     | [8f25636c51](https://bsd-hardware.info/?probe=8f25636c51) | May 19, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [b0ea5e7a5e](https://bsd-hardware.info/?probe=b0ea5e7a5e) | May 19, 2022 |
| CNCTION-IA... | Unknown                     | Desktop     | [d6602975d3](https://bsd-hardware.info/?probe=d6602975d3) | May 16, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [8675ff74d8](https://bsd-hardware.info/?probe=8675ff74d8) | May 09, 2022 |
| Dell          | Inspiron 5437               | Notebook    | [830ea686ab](https://bsd-hardware.info/?probe=830ea686ab) | Apr 24, 2022 |
| HP            | 2820h                       | Desktop     | [d888b8b775](https://bsd-hardware.info/?probe=d888b8b775) | Apr 22, 2022 |
| Intel         | H55                         | Desktop     | [1478e4af73](https://bsd-hardware.info/?probe=1478e4af73) | Apr 20, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [11ec99d4b7](https://bsd-hardware.info/?probe=11ec99d4b7) | Apr 11, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [64de6d6bb9](https://bsd-hardware.info/?probe=64de6d6bb9) | Mar 24, 2022 |
| Gateway       | NE56R                       | Notebook    | [87d177b9da](https://bsd-hardware.info/?probe=87d177b9da) | Mar 20, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [8460816b1f](https://bsd-hardware.info/?probe=8460816b1f) | Mar 13, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [99ab8e7989](https://bsd-hardware.info/?probe=99ab8e7989) | Mar 11, 2022 |
| Acer          | Aspire E1-421               | Notebook    | [cc83218496](https://bsd-hardware.info/?probe=cc83218496) | Mar 10, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [a58b9a4f8f](https://bsd-hardware.info/?probe=a58b9a4f8f) | Mar 09, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [62474001e3](https://bsd-hardware.info/?probe=62474001e3) | Mar 09, 2022 |
| Itautec       | Infoway w7535               | Notebook    | [b55f9d1bfb](https://bsd-hardware.info/?probe=b55f9d1bfb) | Mar 09, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [8b51036856](https://bsd-hardware.info/?probe=8b51036856) | Mar 06, 2022 |
| MSI           | U-100 Ver.001               | Desktop     | [50aba1dee8](https://bsd-hardware.info/?probe=50aba1dee8) | Mar 03, 2022 |
| MSI           | U-100 Ver.001               | Desktop     | [6859308aa9](https://bsd-hardware.info/?probe=6859308aa9) | Mar 01, 2022 |
| HP            | 1905                        | Desktop     | [e271589365](https://bsd-hardware.info/?probe=e271589365) | Mar 01, 2022 |
| HP            | 1905                        | Desktop     | [aa010e00f2](https://bsd-hardware.info/?probe=aa010e00f2) | Feb 28, 2022 |
| KLLISRE       | X99-B5 V1.0                 | Desktop     | [5dea1304b9](https://bsd-hardware.info/?probe=5dea1304b9) | Feb 26, 2022 |
| GALAX         | B365M G10b                  | Desktop     | [ceb2291168](https://bsd-hardware.info/?probe=ceb2291168) | Feb 22, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [aa484c30a8](https://bsd-hardware.info/?probe=aa484c30a8) | Feb 12, 2022 |
| HP            | 83E1                        | Desktop     | [d8e995126f](https://bsd-hardware.info/?probe=d8e995126f) | Feb 10, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [d57de875a6](https://bsd-hardware.info/?probe=d57de875a6) | Feb 07, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5606f6d091](https://bsd-hardware.info/?probe=5606f6d091) | Feb 05, 2022 |
| Unknown       | YL-E3845L4-V2               | Desktop     | [24e60f4686](https://bsd-hardware.info/?probe=24e60f4686) | Feb 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [a07a15f667](https://bsd-hardware.info/?probe=a07a15f667) | Feb 02, 2022 |
| Dell          | 0GDG8Y A02                  | Desktop     | [343129f659](https://bsd-hardware.info/?probe=343129f659) | Feb 01, 2022 |
| Gigabyte      | C847N                       | Desktop     | [0d62b7756c](https://bsd-hardware.info/?probe=0d62b7756c) | Jan 24, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [13d6d1ed51](https://bsd-hardware.info/?probe=13d6d1ed51) | Jan 21, 2022 |
| Gateway       | NE56R                       | Notebook    | [a5aa8aa49a](https://bsd-hardware.info/?probe=a5aa8aa49a) | Jan 18, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [a9d2458de5](https://bsd-hardware.info/?probe=a9d2458de5) | Jan 13, 2022 |
| Sony          | VPCYB45JB                   | Notebook    | [cd18905620](https://bsd-hardware.info/?probe=cd18905620) | Jan 09, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [21407195e3](https://bsd-hardware.info/?probe=21407195e3) | Jan 07, 2022 |
| Unknown       | Phitronics G31VS-M          | Desktop     | [820f706b46](https://bsd-hardware.info/?probe=820f706b46) | Jan 06, 2022 |
| Unknown       | G31T-M7                     | Desktop     | [ed7d80e01a](https://bsd-hardware.info/?probe=ed7d80e01a) | Jan 03, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [6829928dad](https://bsd-hardware.info/?probe=6829928dad) | Dec 28, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [73076dd5de](https://bsd-hardware.info/?probe=73076dd5de) | Dec 21, 2021 |
| Samsung       | 530XBB                      | Notebook    | [fe0adb59d8](https://bsd-hardware.info/?probe=fe0adb59d8) | Dec 20, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [ad308cc715](https://bsd-hardware.info/?probe=ad308cc715) | Dec 08, 2021 |
| Philco        | 10B                         | Notebook    | [a27148f35d](https://bsd-hardware.info/?probe=a27148f35d) | Dec 06, 2021 |
| Positivo      | C14CR01                     | Notebook    | [a33c158f9f](https://bsd-hardware.info/?probe=a33c158f9f) | Dec 05, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [df981410a9](https://bsd-hardware.info/?probe=df981410a9) | Dec 04, 2021 |
| Samsung       | 530XBB                      | Notebook    | [8387645312](https://bsd-hardware.info/?probe=8387645312) | Dec 03, 2021 |
| Samsung       | 530XBB                      | Notebook    | [41d5f95889](https://bsd-hardware.info/?probe=41d5f95889) | Dec 03, 2021 |
| Samsung       | 530XBB                      | Notebook    | [e1983c2353](https://bsd-hardware.info/?probe=e1983c2353) | Dec 03, 2021 |
| Samsung       | 530XBB                      | Notebook    | [b344605891](https://bsd-hardware.info/?probe=b344605891) | Dec 02, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [7c6b2f2013](https://bsd-hardware.info/?probe=7c6b2f2013) | Nov 14, 2021 |
| Toshiba       | STI NA 1401                 | Notebook    | [bbbf661ee8](https://bsd-hardware.info/?probe=bbbf661ee8) | Nov 14, 2021 |
| Unknown       | X79                         | Desktop     | [c80b658f36](https://bsd-hardware.info/?probe=c80b658f36) | Nov 09, 2021 |
| Itautec       | ST 4344 ST-4344 Padrao 0... | Desktop     | [ec13cb0829](https://bsd-hardware.info/?probe=ec13cb0829) | Nov 07, 2021 |
| HP            | 14                          | Notebook    | [e0c8e95e52](https://bsd-hardware.info/?probe=e0c8e95e52) | Nov 07, 2021 |
| Unknown       | X79                         | Desktop     | [ef88cbc606](https://bsd-hardware.info/?probe=ef88cbc606) | Nov 05, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [03be88ded4](https://bsd-hardware.info/?probe=03be88ded4) | Nov 02, 2021 |
| Dell          | 0M5DCD A02                  | Desktop     | [4ff4198768](https://bsd-hardware.info/?probe=4ff4198768) | Nov 02, 2021 |
| Gigabyte      | G41MT-S2                    | Desktop     | [2847d63db0](https://bsd-hardware.info/?probe=2847d63db0) | Oct 18, 2021 |
| Dell          | Inspiron 7460               | Notebook    | [3dbc09a4df](https://bsd-hardware.info/?probe=3dbc09a4df) | Oct 13, 2021 |
| ASUSTek       | PN50-E1                     | Mini pc     | [2781b31f9b](https://bsd-hardware.info/?probe=2781b31f9b) | Oct 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS2A11K    | Notebook    | [e47f4113bf](https://bsd-hardware.info/?probe=e47f4113bf) | Oct 08, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [11cf5c923a](https://bsd-hardware.info/?probe=11cf5c923a) | Oct 08, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [20f9d1c3f0](https://bsd-hardware.info/?probe=20f9d1c3f0) | Oct 06, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [88d44cfe0c](https://bsd-hardware.info/?probe=88d44cfe0c) | Oct 05, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [a376201681](https://bsd-hardware.info/?probe=a376201681) | Oct 05, 2021 |
| Dell          | Latitude 5490               | Notebook    | [f0f4370a9c](https://bsd-hardware.info/?probe=f0f4370a9c) | Sep 27, 2021 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [e7395898d8](https://bsd-hardware.info/?probe=e7395898d8) | Sep 25, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [b00f275d35](https://bsd-hardware.info/?probe=b00f275d35) | Sep 23, 2021 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [91642a928d](https://bsd-hardware.info/?probe=91642a928d) | Sep 20, 2021 |
| PCWare        | PW-945GCX                   | Desktop     | [04bbdf92d6](https://bsd-hardware.info/?probe=04bbdf92d6) | Sep 13, 2021 |
| Unknown       | Phitronics G31VS-M          | Desktop     | [0d13c20ba5](https://bsd-hardware.info/?probe=0d13c20ba5) | Sep 11, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [d91ec24ce0](https://bsd-hardware.info/?probe=d91ec24ce0) | Aug 29, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [0a1be200c6](https://bsd-hardware.info/?probe=0a1be200c6) | Aug 29, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [a129f532bd](https://bsd-hardware.info/?probe=a129f532bd) | Aug 28, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [7c9c49f924](https://bsd-hardware.info/?probe=7c9c49f924) | Aug 27, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [fe69db32c8](https://bsd-hardware.info/?probe=fe69db32c8) | Aug 27, 2021 |
| ECS-USA       | GeForce6100PM-M2            | Desktop     | [f6324966fb](https://bsd-hardware.info/?probe=f6324966fb) | Aug 26, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [2bc72bf29e](https://bsd-hardware.info/?probe=2bc72bf29e) | Aug 23, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [01c4a15001](https://bsd-hardware.info/?probe=01c4a15001) | Aug 22, 2021 |
| Avell High... | A60 MUV                     | Notebook    | [85f5c972a5](https://bsd-hardware.info/?probe=85f5c972a5) | Aug 21, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [3293b7bad9](https://bsd-hardware.info/?probe=3293b7bad9) | Aug 17, 2021 |
| Gigabyte      | C847N                       | Desktop     | [c19601f640](https://bsd-hardware.info/?probe=c19601f640) | Aug 07, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [a40a382f62](https://bsd-hardware.info/?probe=a40a382f62) | Aug 06, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [f43771bc21](https://bsd-hardware.info/?probe=f43771bc21) | Aug 05, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [ae874102c3](https://bsd-hardware.info/?probe=ae874102c3) | Aug 04, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [d1790c6aed](https://bsd-hardware.info/?probe=d1790c6aed) | Aug 04, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1aad7a6eab](https://bsd-hardware.info/?probe=1aad7a6eab) | Aug 03, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [95573fe387](https://bsd-hardware.info/?probe=95573fe387) | Aug 03, 2021 |
| Unknown       | Unknown                     | Desktop     | [524215c510](https://bsd-hardware.info/?probe=524215c510) | Aug 03, 2021 |
| ECS           | BAT-I                       | Desktop     | [6741011e07](https://bsd-hardware.info/?probe=6741011e07) | Aug 02, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [6283cb4190](https://bsd-hardware.info/?probe=6283cb4190) | Aug 01, 2021 |
| Yanling       | NS-1U8L                     | Desktop     | [6166362d7a](https://bsd-hardware.info/?probe=6166362d7a) | Jul 27, 2021 |
| Avell High... | A62 LIV                     | Notebook    | [5983302b1d](https://bsd-hardware.info/?probe=5983302b1d) | Jul 21, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [daa7e68a1f](https://bsd-hardware.info/?probe=daa7e68a1f) | Jul 21, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [98cefddb1b](https://bsd-hardware.info/?probe=98cefddb1b) | Jul 17, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [a857cdfd42](https://bsd-hardware.info/?probe=a857cdfd42) | Jul 07, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [08cafd05b1](https://bsd-hardware.info/?probe=08cafd05b1) | Jul 06, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [128c08e60f](https://bsd-hardware.info/?probe=128c08e60f) | Jul 04, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [f6d72c011d](https://bsd-hardware.info/?probe=f6d72c011d) | Jul 01, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [ceb18e38a3](https://bsd-hardware.info/?probe=ceb18e38a3) | Jun 28, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [7623c94ba1](https://bsd-hardware.info/?probe=7623c94ba1) | Jun 25, 2021 |
| ULTRATOP      | C2017-LIVA-ZE               | Desktop     | [d091f171b7](https://bsd-hardware.info/?probe=d091f171b7) | Jun 23, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [d59f20f88a](https://bsd-hardware.info/?probe=d59f20f88a) | Jun 22, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [cc6dc71d37](https://bsd-hardware.info/?probe=cc6dc71d37) | Jun 21, 2021 |
| Gateway       | NE56R                       | Notebook    | [cc65e24aea](https://bsd-hardware.info/?probe=cc65e24aea) | Jun 20, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [5f9b56c8ae](https://bsd-hardware.info/?probe=5f9b56c8ae) | Jun 15, 2021 |
| Gateway       | NE56R                       | Notebook    | [932f5d03f3](https://bsd-hardware.info/?probe=932f5d03f3) | Jun 13, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [cf3508718c](https://bsd-hardware.info/?probe=cf3508718c) | Jun 11, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | Notebook    | [66743a51cc](https://bsd-hardware.info/?probe=66743a51cc) | Jun 04, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [edebe87739](https://bsd-hardware.info/?probe=edebe87739) | Jun 04, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [53a69aa8c1](https://bsd-hardware.info/?probe=53a69aa8c1) | Jun 04, 2021 |
| Dell          | 0GDG8Y A02                  | Desktop     | [5b44835ac1](https://bsd-hardware.info/?probe=5b44835ac1) | Jun 03, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [c44be632d3](https://bsd-hardware.info/?probe=c44be632d3) | May 28, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [5675cca325](https://bsd-hardware.info/?probe=5675cca325) | May 28, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [b73e45e0df](https://bsd-hardware.info/?probe=b73e45e0df) | May 27, 2021 |
| Lenovo        | ThinkPad X270 20HM004JBR    | Notebook    | [88c27e65d7](https://bsd-hardware.info/?probe=88c27e65d7) | May 23, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [0d1d75a914](https://bsd-hardware.info/?probe=0d1d75a914) | May 23, 2021 |
| Dell          | 0C7TDG A03                  | Server      | [25e20c3f35](https://bsd-hardware.info/?probe=25e20c3f35) | May 19, 2021 |
| HP            | ProLiant DL20 Gen9          | Server      | [0d13ec7ac2](https://bsd-hardware.info/?probe=0d13ec7ac2) | May 17, 2021 |
| Toshiba       | STI 005492G                 | Desktop     | [9a8e4a1328](https://bsd-hardware.info/?probe=9a8e4a1328) | May 17, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [e69be420df](https://bsd-hardware.info/?probe=e69be420df) | May 16, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [076dc91b26](https://bsd-hardware.info/?probe=076dc91b26) | May 13, 2021 |
| HP            | ProLiant DL20 Gen9          | Server      | [a5c5f7dba6](https://bsd-hardware.info/?probe=a5c5f7dba6) | May 12, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | Notebook    | [852a900303](https://bsd-hardware.info/?probe=852a900303) | Apr 22, 2021 |
| AMI           | Aptio CRB 11                | Mini pc     | [e75df3aaa4](https://bsd-hardware.info/?probe=e75df3aaa4) | Apr 20, 2021 |
| Gateway       | NE56R                       | Notebook    | [bbbc827581](https://bsd-hardware.info/?probe=bbbc827581) | Apr 16, 2021 |
| Gateway       | NE56R                       | Notebook    | [af262c2350](https://bsd-hardware.info/?probe=af262c2350) | Apr 11, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [01cc3a3802](https://bsd-hardware.info/?probe=01cc3a3802) | Apr 11, 2021 |
| Gigabyte      | C847N                       | Desktop     | [1d9e74caab](https://bsd-hardware.info/?probe=1d9e74caab) | Apr 08, 2021 |
| Dell          | 04YP6J A03                  | Desktop     | [779e2e4d2d](https://bsd-hardware.info/?probe=779e2e4d2d) | Apr 05, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [687047b3d2](https://bsd-hardware.info/?probe=687047b3d2) | Mar 30, 2021 |
| Dell          | 04YP6J A03                  | Desktop     | [59efed23b2](https://bsd-hardware.info/?probe=59efed23b2) | Mar 30, 2021 |
| Dell          | 0P301D A01                  | Desktop     | [bd0c36fe70](https://bsd-hardware.info/?probe=bd0c36fe70) | Mar 26, 2021 |
| ECS           | H55H-CM                     | Desktop     | [a2808d49c9](https://bsd-hardware.info/?probe=a2808d49c9) | Mar 25, 2021 |
| ECS           | H55H-CM                     | Desktop     | [3b13b3a934](https://bsd-hardware.info/?probe=3b13b3a934) | Mar 25, 2021 |
| Avell High... | A62                         | Notebook    | [df77dd6562](https://bsd-hardware.info/?probe=df77dd6562) | Mar 22, 2021 |
| Notebook      | N85_N87HCHNHZ               | Notebook    | [e84b5b6e5f](https://bsd-hardware.info/?probe=e84b5b6e5f) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | Notebook    | [8d81204137](https://bsd-hardware.info/?probe=8d81204137) | Mar 22, 2021 |
| ECS           | H55H-CM                     | Desktop     | [5df8692ddd](https://bsd-hardware.info/?probe=5df8692ddd) | Mar 18, 2021 |
| ECS           | H55H-CM                     | Desktop     | [6a10af558b](https://bsd-hardware.info/?probe=6a10af558b) | Mar 18, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [fdfc8e2b9b](https://bsd-hardware.info/?probe=fdfc8e2b9b) | Mar 17, 2021 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [c4b2356821](https://bsd-hardware.info/?probe=c4b2356821) | Mar 17, 2021 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [c23066d56d](https://bsd-hardware.info/?probe=c23066d56d) | Mar 17, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [cc3151bc6f](https://bsd-hardware.info/?probe=cc3151bc6f) | Mar 17, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [35f1d21b73](https://bsd-hardware.info/?probe=35f1d21b73) | Mar 16, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [599d3e84d7](https://bsd-hardware.info/?probe=599d3e84d7) | Mar 16, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [f156951052](https://bsd-hardware.info/?probe=f156951052) | Mar 14, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [49509bf7ee](https://bsd-hardware.info/?probe=49509bf7ee) | Mar 13, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [3339a68c44](https://bsd-hardware.info/?probe=3339a68c44) | Mar 12, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [525eeec663](https://bsd-hardware.info/?probe=525eeec663) | Mar 12, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [4b65be31e6](https://bsd-hardware.info/?probe=4b65be31e6) | Mar 11, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [3bdcd1ac80](https://bsd-hardware.info/?probe=3bdcd1ac80) | Mar 05, 2021 |
| ASRock        | 970A-G                      | Desktop     | [3e474f93cf](https://bsd-hardware.info/?probe=3e474f93cf) | Mar 04, 2021 |
| Dell          | 0H5FVJ A01                  | Server      | [efe3dbf989](https://bsd-hardware.info/?probe=efe3dbf989) | Mar 03, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [b33294491e](https://bsd-hardware.info/?probe=b33294491e) | Mar 02, 2021 |
| Dell          | 0DFXXD A00                  | Server      | [deb86bda7b](https://bsd-hardware.info/?probe=deb86bda7b) | Feb 26, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [5211d36066](https://bsd-hardware.info/?probe=5211d36066) | Feb 25, 2021 |
| MSI           | E350IS-E45                  | Desktop     | [2d4f50994d](https://bsd-hardware.info/?probe=2d4f50994d) | Feb 24, 2021 |
| Unknown       | Unknown                     | Notebook    | [d11ec93413](https://bsd-hardware.info/?probe=d11ec93413) | Feb 23, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [22fa0d8178](https://bsd-hardware.info/?probe=22fa0d8178) | Feb 23, 2021 |
| Intel         | H61                         | Desktop     | [a8ae96a0ab](https://bsd-hardware.info/?probe=a8ae96a0ab) | Feb 23, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [467a915fc7](https://bsd-hardware.info/?probe=467a915fc7) | Feb 23, 2021 |
| LG Electro... | 14Z980-G.BH51P1             | Notebook    | [d8ee6bc4e3](https://bsd-hardware.info/?probe=d8ee6bc4e3) | Feb 22, 2021 |
| Lenovo        | ThinkPad X240 20AMS4V000    | Notebook    | [cbfa45fe44](https://bsd-hardware.info/?probe=cbfa45fe44) | Feb 22, 2021 |
| ASUSTek       | K46CA                       | Notebook    | [f286c1e784](https://bsd-hardware.info/?probe=f286c1e784) | Feb 21, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [405b36b911](https://bsd-hardware.info/?probe=405b36b911) | Feb 21, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c9a8d5ade5](https://bsd-hardware.info/?probe=c9a8d5ade5) | Feb 21, 2021 |
| Dell          | 0M8K4M A00                  | Desktop     | [6d3defcde3](https://bsd-hardware.info/?probe=6d3defcde3) | Feb 21, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [5b163eb70f](https://bsd-hardware.info/?probe=5b163eb70f) | Feb 19, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [724e753eb9](https://bsd-hardware.info/?probe=724e753eb9) | Feb 19, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [337aa08686](https://bsd-hardware.info/?probe=337aa08686) | Feb 18, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7699b1e79f](https://bsd-hardware.info/?probe=7699b1e79f) | Feb 18, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7ef872c122](https://bsd-hardware.info/?probe=7ef872c122) | Feb 18, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [d8a1ca5210](https://bsd-hardware.info/?probe=d8a1ca5210) | Feb 17, 2021 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [1a49b7921a](https://bsd-hardware.info/?probe=1a49b7921a) | Feb 17, 2021 |
| Lenovo        | ThinkPad T430 2349PMP       | Notebook    | [23de6449ad](https://bsd-hardware.info/?probe=23de6449ad) | Feb 17, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [ffc1292c18](https://bsd-hardware.info/?probe=ffc1292c18) | Feb 16, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [6e5c330c9c](https://bsd-hardware.info/?probe=6e5c330c9c) | Feb 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [32a87da376](https://bsd-hardware.info/?probe=32a87da376) | Feb 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cf042892e7](https://bsd-hardware.info/?probe=cf042892e7) | Feb 16, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [c5f6880081](https://bsd-hardware.info/?probe=c5f6880081) | Feb 15, 2021 |
| Dell          | 0GDG8Y A02                  | Desktop     | [5cda8abfad](https://bsd-hardware.info/?probe=5cda8abfad) | Feb 14, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [694204751b](https://bsd-hardware.info/?probe=694204751b) | Feb 13, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [411797b4dc](https://bsd-hardware.info/?probe=411797b4dc) | Feb 13, 2021 |
| Clevo         | C41X0                       | Notebook    | [81c48d156a](https://bsd-hardware.info/?probe=81c48d156a) | Feb 12, 2021 |
| Apple         | MacBook6,1                  | Notebook    | [3a9335691f](https://bsd-hardware.info/?probe=3a9335691f) | Feb 11, 2021 |
| Dell          | 07N90W A02                  | Desktop     | [6bbd0de8d9](https://bsd-hardware.info/?probe=6bbd0de8d9) | Feb 08, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [7c179e0033](https://bsd-hardware.info/?probe=7c179e0033) | Feb 06, 2021 |
| HP            | ProLiant ML350 G6           | Desktop     | [0539585a88](https://bsd-hardware.info/?probe=0539585a88) | Feb 05, 2021 |
| Positivo      | POS-EAA75DE                 | Desktop     | [cb30dbeef2](https://bsd-hardware.info/?probe=cb30dbeef2) | Feb 05, 2021 |
| Positivo      | POS-EAA75DE                 | Desktop     | [c1fb910e23](https://bsd-hardware.info/?probe=c1fb910e23) | Feb 05, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [a667296c17](https://bsd-hardware.info/?probe=a667296c17) | Feb 03, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7833038238](https://bsd-hardware.info/?probe=7833038238) | Feb 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [d46871a402](https://bsd-hardware.info/?probe=d46871a402) | Feb 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [52d17aa061](https://bsd-hardware.info/?probe=52d17aa061) | Jan 28, 2021 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [85a0e6c728](https://bsd-hardware.info/?probe=85a0e6c728) | Jan 24, 2021 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [3e468c1461](https://bsd-hardware.info/?probe=3e468c1461) | Jan 23, 2021 |
| PCWare        | IPX1800G2                   | Desktop     | [bc9bce51bc](https://bsd-hardware.info/?probe=bc9bce51bc) | Jan 22, 2021 |
| MSI           | J1800I                      | Desktop     | [98abf7d1f0](https://bsd-hardware.info/?probe=98abf7d1f0) | Jan 22, 2021 |
| MSI           | J1800I                      | Desktop     | [b6adf4005e](https://bsd-hardware.info/?probe=b6adf4005e) | Jan 21, 2021 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [ba328938c3](https://bsd-hardware.info/?probe=ba328938c3) | Jan 21, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [23e48fdef0](https://bsd-hardware.info/?probe=23e48fdef0) | Jan 21, 2021 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | Notebook    | [bc2855974c](https://bsd-hardware.info/?probe=bc2855974c) | Dec 06, 2020 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [75e86a92f7](https://bsd-hardware.info/?probe=75e86a92f7) | Dec 05, 2020 |
| Unknown       | Unknown                     | Notebook    | [6953b9a9e4](https://bsd-hardware.info/?probe=6953b9a9e4) | Nov 22, 2020 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [825a724001](https://bsd-hardware.info/?probe=825a724001) | Oct 25, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [04b6ad9952](https://bsd-hardware.info/?probe=04b6ad9952) | Oct 25, 2020 |
| Dell          | Latitude 3490               | Notebook    | [b28cc12aeb](https://bsd-hardware.info/?probe=b28cc12aeb) | Sep 20, 2020 |
| ASUSTek       | Z8P                         | Desktop     | [7b0818f96a](https://bsd-hardware.info/?probe=7b0818f96a) | Sep 16, 2020 |
| ASUSTek       | STRIX B250G GAMING          | Desktop     | [a02398f78f](https://bsd-hardware.info/?probe=a02398f78f) | Sep 01, 2020 |
| Acer          | Spin SP111-32N              | Convertible | [b8fdb26064](https://bsd-hardware.info/?probe=b8fdb26064) | Sep 01, 2020 |
| Acer          | Spin SP111-32N              | Convertible | [33266821d4](https://bsd-hardware.info/?probe=33266821d4) | Sep 01, 2020 |
| Lenovo        | ThinkPad T490 20N30029BR    | Notebook    | [41dbfb6fdc](https://bsd-hardware.info/?probe=41dbfb6fdc) | Aug 06, 2020 |
| ASUSTek       | Z8P                         | Desktop     | [9f5845a398](https://bsd-hardware.info/?probe=9f5845a398) | Jul 27, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | Desktop     | [7e845aab76](https://bsd-hardware.info/?probe=7e845aab76) | Jul 26, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | Desktop     | [7febd3108d](https://bsd-hardware.info/?probe=7febd3108d) | Jul 26, 2020 |
| Procomp In... | G41MXE                      | Desktop     | [a76a3bb201](https://bsd-hardware.info/?probe=a76a3bb201) | Jul 25, 2020 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [1b84bffd9b](https://bsd-hardware.info/?probe=1b84bffd9b) | Jul 24, 2020 |
| Sony          | VPCEG17FB                   | Notebook    | [7d48bd3606](https://bsd-hardware.info/?probe=7d48bd3606) | Jul 13, 2020 |
| Lenovo        | ThinkPad X250 20CLS18S0Z    | Notebook    | [f668ce4e5b](https://bsd-hardware.info/?probe=f668ce4e5b) | Jul 05, 2020 |
| ASUSTek       | Z8P                         | Desktop     | [5071a32803](https://bsd-hardware.info/?probe=5071a32803) | Jun 05, 2020 |
| ASUSTek       | Z8P                         | Desktop     | [a0723b0566](https://bsd-hardware.info/?probe=a0723b0566) | Jun 05, 2020 |
| Dell          | 0PV3YR A05                  | Server      | [245d470945](https://bsd-hardware.info/?probe=245d470945) | Jun 05, 2020 |
| Dell          | 0PV3YR A05                  | Server      | [5e50c0fa57](https://bsd-hardware.info/?probe=5e50c0fa57) | Jun 05, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.8.1    | 32        | 6.36%   |
| helloSystem 0.7.0    | 27        | 5.37%   |
| helloSystem 0.8.0    | 17        | 3.38%   |
| helloSystem 0.4.0    | 15        | 2.98%   |
| helloSystem 0.6.0    | 14        | 2.78%   |
| helloSystem 0.5.0    | 14        | 2.78%   |
| helloSystem 0.9.0    | 12        | 2.39%   |
| OPNsense 23.1.11     | 10        | 1.99%   |
| OPNsense 23.1.7      | 8         | 1.59%   |
| FreeBSD 13.0         | 8         | 1.59%   |
| OPNsense 23.1.5      | 7         | 1.39%   |
| OPNsense 22.1.10     | 7         | 1.39%   |
| FreeBSD 14.0-CURRENT | 7         | 1.39%   |
| OPNsense 24.7.7      | 6         | 1.19%   |
| OPNsense 24.7.5      | 6         | 1.19%   |
| OPNsense 24.7        | 6         | 1.19%   |
| OPNsense 23.7.12     | 6         | 1.19%   |
| OPNsense 23.7.10     | 6         | 1.19%   |
| OPNsense 23.1        | 6         | 1.19%   |
| OPNsense 22.7.4      | 6         | 1.19%   |
| OPNsense 21.1.3      | 6         | 1.19%   |
| OPNsense 21.1        | 6         | 1.19%   |
| OPNsense 20.7.8      | 6         | 1.19%   |
| OpenBSD 7.3          | 6         | 1.19%   |
| FreeBSD 13.2         | 6         | 1.19%   |
| OPNsense 24.1.9      | 5         | 0.99%   |
| OPNsense 23.7.9      | 5         | 0.99%   |
| OPNsense 23.1.9      | 5         | 0.99%   |
| OPNsense 22.7.8      | 5         | 0.99%   |
| OPNsense 22.7.5      | 5         | 0.99%   |
| OPNsense 21.1.2      | 5         | 0.99%   |
| OPNsense 21.1.1      | 5         | 0.99%   |
| FreeBSD 14.1         | 5         | 0.99%   |
| FreeBSD 14.0         | 5         | 0.99%   |
| OPNsense 24.7.6      | 4         | 0.8%    |
| OPNsense 24.1.8      | 4         | 0.8%    |
| OPNsense 24.1.5      | 4         | 0.8%    |
| OPNsense 23.1.1      | 4         | 0.8%    |
| OPNsense 22.7.6      | 4         | 0.8%    |
| OPNsense 22.1.8      | 4         | 0.8%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 172       | 42.79%  |
| helloSystem | 123       | 30.6%   |
| FreeBSD     | 73        | 18.16%  |
| OpenBSD     | 13        | 3.23%   |
| GhostBSD    | 7         | 1.74%   |
| pfSense     | 3         | 0.75%   |
| NetBSD      | 3         | 0.75%   |
| TrueNAS     | 2         | 0.5%    |
| NomadBSD    | 2         | 0.5%    |
| FreeNAS     | 2         | 0.5%    |
| OS108       | 1         | 0.25%   |
| DragonFly   | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 387       | 98.47%  |
| i386  | 4         | 1.02%   |
| arm64 | 2         | 0.51%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 191       | 46.81%  |
| helloDesktop | 131       | 32.11%  |
| KDE5         | 17        | 4.17%   |
| XFCE         | 15        | 3.68%   |
| MATE         | 12        | 2.94%   |
| GNOME        | 12        | 2.94%   |
| TWM          | 8         | 1.96%   |
| Openbox      | 6         | 1.47%   |
| i3           | 5         | 1.23%   |
| spectrwm     | 2         | 0.49%   |
| fvwm         | 2         | 0.49%   |
| X-Cinnamon   | 1         | 0.25%   |
| Window Maker | 1         | 0.25%   |
| LXQt         | 1         | 0.25%   |
| KDE          | 1         | 0.25%   |
| Hyprland     | 1         | 0.25%   |
| EXWM         | 1         | 0.25%   |
| AwesomeWM    | 1         | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 198       | 49.87%  |
| Console | 195       | 49.12%  |
| Wayland | 4         | 1.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 224       | 55.72%  |
| SLiM    | 132       | 32.84%  |
| SDDM    | 17        | 4.23%   |
| LightDM | 16        | 3.98%   |
| GDM     | 8         | 1.99%   |
| XDM     | 4         | 1%      |
| Ly      | 1         | 0.25%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 204       | 49.88%  |
| en_US            | 90        | 22%     |
| C                | 50        | 12.22%  |
| pt_BR            | 42        | 10.27%  |
| fr_FR            | 9         | 2.2%    |
| pt               | 8         | 1.96%   |
| pt_PT            | 1         | 0.24%   |
| fr               | 1         | 0.24%   |
| en_US.ISO8859-15 | 1         | 0.24%   |
| en_US.ISO8859-1  | 1         | 0.24%   |
| en_GB            | 1         | 0.24%   |
| en               | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 350       | 87.06%  |
| BIOS | 52        | 12.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 201       | 49.02%  |
| Ufs     | 149       | 36.34%  |
| Cd9660  | 45        | 10.98%  |
| Ffs     | 14        | 3.41%   |
| Hammer2 | 1         | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 374       | 93.97%  |
| MBR     | 21        | 5.28%   |
| Unknown | 3         | 0.75%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 69        | 17.56%  |
| ASUSTek Computer        | 46        | 11.7%   |
| Lenovo                  | 41        | 10.43%  |
| Unknown                 | 34        | 8.65%   |
| Intel                   | 28        | 7.12%   |
| Gigabyte Technology     | 19        | 4.83%   |
| Hewlett-Packard         | 17        | 4.33%   |
| Acer                    | 17        | 4.33%   |
| ASRock                  | 12        | 3.05%   |
| Samsung Electronics     | 11        | 2.8%    |
| Techvision              | 8         | 2.04%   |
| AMI                     | 8         | 2.04%   |
| Itautec                 | 7         | 1.78%   |
| Apple                   | 7         | 1.78%   |
| Positivo                | 5         | 1.27%   |
| Sony                    | 4         | 1.02%   |
| MSI                     | 4         | 1.02%   |
| Supermicro              | 3         | 0.76%   |
| Pegatron                | 3         | 0.76%   |
| PCWare                  | 3         | 0.76%   |
| ECS                     | 3         | 0.76%   |
| Avell High Performance  | 3         | 0.76%   |
| Yanling                 | 2         | 0.51%   |
| Semp Toshiba            | 2         | 0.51%   |
| LG Electronics          | 2         | 0.51%   |
| Gateway                 | 2         | 0.51%   |
| Biostar                 | 2         | 0.51%   |
| YANYU                   | 1         | 0.25%   |
| ULTRATOP                | 1         | 0.25%   |
| Timi                    | 1         | 0.25%   |
| T-bao                   | 1         | 0.25%   |
| Soyo                    | 1         | 0.25%   |
| Sophos                  | 1         | 0.25%   |
| Procomp Ind. Eletronica | 1         | 0.25%   |
| pine64                  | 1         | 0.25%   |
| Philco                  | 1         | 0.25%   |
| Notebook                | 1         | 0.25%   |
| Megaware                | 1         | 0.25%   |
| maiyunda                | 1         | 0.25%   |
| KLLISRE                 | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 35        | 8.91%   |
| Techvision TVI7309X                 | 8         | 2.04%   |
| Intel Q3XXG4-P V1.0                 | 8         | 2.04%   |
| Dell Inspiron 3442                  | 6         | 1.53%   |
| ASUS All Series                     | 6         | 1.53%   |
| AMI Aptio CRB                       | 6         | 1.53%   |
| ASUS PRIME B450M-GAMING/BR          | 4         | 1.02%   |
| Dell PowerEdge T110 II              | 3         | 0.76%   |
| Dell Inspiron 3421                  | 3         | 0.76%   |
| ASUS PRIME A520M-E                  | 3         | 0.76%   |
| Samsung 340XAA/350XAA/550XAA        | 2         | 0.51%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK | 2         | 0.51%   |
| Pegatron IPM41-D3                   | 2         | 0.51%   |
| Lenovo IdeaPadFlex 5 14ITL05 82LT   | 2         | 0.51%   |
| Lenovo IdeaPad S145-15API 81V7      | 2         | 0.51%   |
| Itautec Infoway                     | 2         | 0.51%   |
| Intel H81                           | 2         | 0.51%   |
| Intel H55                           | 2         | 0.51%   |
| Gigabyte H61M-S2-B3                 | 2         | 0.51%   |
| Gigabyte B550M DS3H AC              | 2         | 0.51%   |
| Gateway NE56R                       | 2         | 0.51%   |
| Dell PowerEdge R620                 | 2         | 0.51%   |
| Dell PowerEdge 1950                 | 2         | 0.51%   |
| Dell OptiPlex 7040                  | 2         | 0.51%   |
| Dell OptiPlex 3020                  | 2         | 0.51%   |
| Dell Latitude 5490                  | 2         | 0.51%   |
| ASUS TUF Gaming B550M-PLUS          | 2         | 0.51%   |
| ASUS P8H61-M LX3 PLUS R2.0          | 2         | 0.51%   |
| ASUS P5G41T-M LX2/BR                | 2         | 0.51%   |
| ASUS M5A97 LE R2.0                  | 2         | 0.51%   |
| ASUS M5A78L-M LX/BR                 | 2         | 0.51%   |
| ASUS A88XM-A                        | 2         | 0.51%   |
| ASRock J4005B-ITX                   | 2         | 0.51%   |
| Acer Aspire 5750                    | 2         | 0.51%   |
| YANYU N39SL                         | 1         | 0.25%   |
| Yanling YL-CLU6L-V1                 | 1         | 0.25%   |
| Yanling NS-1U8L                     | 1         | 0.25%   |
| ULTRATOP C2017-LIVA-ZE              | 1         | 0.25%   |
| Timi TM1703                         | 1         | 0.25%   |
| T-bao MINI PC                       | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 35        | 8.91%   |
| Dell Inspiron              | 25        | 6.36%   |
| Lenovo ThinkPad            | 20        | 5.09%   |
| Dell PowerEdge             | 18        | 4.58%   |
| Dell OptiPlex              | 14        | 3.56%   |
| Acer Aspire                | 14        | 3.56%   |
| ASUS PRIME                 | 9         | 2.29%   |
| Techvision TVI7309X        | 8         | 2.04%   |
| Lenovo IdeaPad             | 8         | 2.04%   |
| Intel Q3XXG4-P             | 8         | 2.04%   |
| HP ProLiant                | 7         | 1.78%   |
| AMI Aptio                  | 7         | 1.78%   |
| Itautec Infoway            | 6         | 1.53%   |
| Dell Vostro                | 6         | 1.53%   |
| ASUS All                   | 6         | 1.53%   |
| Dell Latitude              | 4         | 1.02%   |
| ASUS TUF                   | 4         | 1.02%   |
| Lenovo ThinkCentre         | 3         | 0.76%   |
| ASUS P8H61-M               | 3         | 0.76%   |
| ASUS P5G41T-M              | 3         | 0.76%   |
| ASUS M5A78L-M              | 3         | 0.76%   |
| Semp Toshiba STI           | 2         | 0.51%   |
| Samsung 340XAA             | 2         | 0.51%   |
| Samsung 270E5K             | 2         | 0.51%   |
| Pegatron IPM41-D3          | 2         | 0.51%   |
| Lenovo IdeaPadFlex         | 2         | 0.51%   |
| Intel H81                  | 2         | 0.51%   |
| Intel H55                  | 2         | 0.51%   |
| HP Compaq                  | 2         | 0.51%   |
| Gigabyte H61M-S2-B3        | 2         | 0.51%   |
| Gigabyte GA-78LMT-USB3     | 2         | 0.51%   |
| Gigabyte B550M             | 2         | 0.51%   |
| Gigabyte B450M             | 2         | 0.51%   |
| Gateway NE56R              | 2         | 0.51%   |
| Avell High Performance A62 | 2         | 0.51%   |
| ASUS M5A97                 | 2         | 0.51%   |
| ASUS A88XM-A               | 2         | 0.51%   |
| ASRock J4005B-ITX          | 2         | 0.51%   |
| Acer Nitro                 | 2         | 0.51%   |
| YANYU N39SL                | 1         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 43        | 10.94%  |
| 2013    | 37        | 9.41%   |
| 2018    | 32        | 8.14%   |
| 2016    | 30        | 7.63%   |
| 2014    | 26        | 6.62%   |
| 2011    | 26        | 6.62%   |
| 2019    | 25        | 6.36%   |
| 2012    | 24        | 6.11%   |
| 2020    | 21        | 5.34%   |
| 2023    | 20        | 5.09%   |
| 2017    | 20        | 5.09%   |
| 2010    | 20        | 5.09%   |
| 2021    | 18        | 4.58%   |
| 2009    | 14        | 3.56%   |
| 2008    | 12        | 3.05%   |
| 2015    | 11        | 2.8%    |
| 2007    | 6         | 1.53%   |
| 2024    | 4         | 1.02%   |
| Unknown | 4         | 1.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 222       | 56.49%  |
| Notebook    | 129       | 32.82%  |
| Server      | 25        | 6.36%   |
| Mini pc     | 9         | 2.29%   |
| All in one  | 4         | 1.02%   |
| Convertible | 3         | 0.76%   |
| Firewall    | 1         | 0.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 393       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 163       | 40.15%  |
| 4.01-8.0    | 118       | 29.06%  |
| 16.01-24.0  | 73        | 17.98%  |
| 32.01-64.0  | 21        | 5.17%   |
| 2.01-3.0    | 13        | 3.2%    |
| 64.01-256.0 | 7         | 1.72%   |
| 24.01-32.0  | 6         | 1.48%   |
| 3.01-4.0    | 5         | 1.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 233       | 57.39%  |
| 0.51-1.0   | 116       | 28.57%  |
| 1.01-2.0   | 36        | 8.87%   |
| 2.01-3.0   | 10        | 2.46%   |
| Unknown    | 4         | 0.99%   |
| 4.01-8.0   | 3         | 0.74%   |
| 32.01-64.0 | 1         | 0.25%   |
| 24.01-32.0 | 1         | 0.25%   |
| 16.01-24.0 | 1         | 0.25%   |
| 8.01-16.0  | 1         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 270       | 65.06%  |
| 2      | 58        | 13.98%  |
| 0      | 58        | 13.98%  |
| 3      | 15        | 3.61%   |
| 4      | 8         | 1.93%   |
| 5      | 4         | 0.96%   |
| 7      | 1         | 0.24%   |
| 6      | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 289       | 73.16%  |
| Yes       | 106       | 26.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 372       | 94.66%  |
| No        | 21        | 5.34%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 223       | 56.6%   |
| Yes       | 171       | 43.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 270       | 68.35%  |
| Yes       | 125       | 31.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Brazil  | 393       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Sao Paulo                 | 48        | 11.09%  |
| Rio de Janeiro            | 25        | 5.77%   |
| SГЈo Paulo              | 19        | 4.39%   |
| Curitiba                  | 19        | 4.39%   |
| Belo Horizonte            | 11        | 2.54%   |
| Porto Alegre              | 8         | 1.85%   |
| Campinas                  | 8         | 1.85%   |
| Sao José dos Campos      | 7         | 1.62%   |
| Fortaleza                 | 7         | 1.62%   |
| Blumenau                  | 7         | 1.62%   |
| SÃ£o Paulo              | 6         | 1.39%   |
| Osasco                    | 6         | 1.39%   |
| Maringá                  | 6         | 1.39%   |
| Joinville                 | 6         | 1.39%   |
| Jaraguá do Sul           | 6         | 1.39%   |
| Manaus                    | 5         | 1.15%   |
| Florianópolis            | 5         | 1.15%   |
| Brasília                 | 5         | 1.15%   |
| Maceió                   | 4         | 0.92%   |
| Londrina                  | 4         | 0.92%   |
| SГЈo JosГ© dos Campos | 3         | 0.69%   |
| Sao Bernardo do Campo     | 3         | 0.69%   |
| Salvador                  | 3         | 0.69%   |
| Novo Hamburgo             | 3         | 0.69%   |
| JoГЈo Pessoa            | 3         | 0.69%   |
| Visconde do Rio Branco    | 2         | 0.46%   |
| Valparaiso de Goias       | 2         | 0.46%   |
| Uberaba                   | 2         | 0.46%   |
| Teresina                  | 2         | 0.46%   |
| Taubate                   | 2         | 0.46%   |
| Sorocaba                  | 2         | 0.46%   |
| Serra                     | 2         | 0.46%   |
| Sao Vicente               | 2         | 0.46%   |
| Sao Leopoldo              | 2         | 0.46%   |
| Sao Jose do Rio Preto     | 2         | 0.46%   |
| Sao Goncalo               | 2         | 0.46%   |
| Santa Barbara d'Oeste     | 2         | 0.46%   |
| RondonГіpolis           | 2         | 0.46%   |
| Rio das Ostras            | 2         | 0.46%   |
| Rio Claro                 | 2         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Kingston                           | 70        | 108    | 15.66%  |
| Seagate                            | 68        | 132    | 15.21%  |
| WDC                                | 67        | 86     | 14.99%  |
| Samsung Electronics                | 37        | 52     | 8.28%   |
| SanDisk                            | 26        | 30     | 5.82%   |
| Toshiba                            | 23        | 27     | 5.15%   |
| A-DATA Technology                  | 17        | 19     | 3.8%    |
| Crucial                            | 13        | 20     | 2.91%   |
| KingSpec                           | 12        | 16     | 2.68%   |
| China                              | 12        | 17     | 2.68%   |
| Silicon Motion                     | 9         | 10     | 2.01%   |
| Hoodisk                            | 9         | 9      | 2.01%   |
| XrayDisk                           | 5         | 5      | 1.12%   |
| NVMe                               | 5         | 7      | 1.12%   |
| Hitachi                            | 5         | 9      | 1.12%   |
| Gigabyte Technology                | 5         | 9      | 1.12%   |
| SK hynix                           | 4         | 5      | 0.89%   |
| LITEON                             | 4         | 4      | 0.89%   |
| HGST                               | 4         | 5      | 0.89%   |
| SSSTC                              | 3         | 3      | 0.67%   |
| Product:              USB DISK 2.0 | 3         | 3      | 0.67%   |
| PNY                                | 3         | 3      | 0.67%   |
| Netac                              | 3         | 3      | 0.67%   |
| Hewlett-Packard                    | 3         | 4      | 0.67%   |
| Fanxiang                           | 3         | 4      | 0.67%   |
| SMI                                | 2         | 2      | 0.45%   |
| Patriot                            | 2         | 5      | 0.45%   |
| NTC                                | 2         | 2      | 0.45%   |
| Lexar                              | 2         | 3      | 0.45%   |
| Kston                              | 2         | 2      | 0.45%   |
| Vaseky                             | 1         | 1      | 0.22%   |
| Transcend                          | 1         | 2      | 0.22%   |
| Teelkoou                           | 1         | 1      | 0.22%   |
| tecmiyo                            | 1         | 2      | 0.22%   |
| Smart                              | 1         | 1      | 0.22%   |
| Silicon                            | 1         | 1      | 0.22%   |
| Qunion                             | 1         | 1      | 0.22%   |
| Phison                             | 1         | 1      | 0.22%   |
| Maxtor                             | 1         | 1      | 0.22%   |
| MACROVIP                           | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB                          | 19        | 4%      |
| Kingston SA400S37120G 120GB                          | 12        | 2.53%   |
| SanDisk SSD PLUS 120GB                               | 11        | 2.32%   |
| Kingston SA400S37480G 480GB                          | 11        | 2.32%   |
| Seagate ST500DM002-1BD142 500GB                      | 8         | 1.68%   |
| Seagate ST500LM012 HN-M500MBB 500GB                  | 6         | 1.26%   |
| Hoodisk SSD 64GB                                     | 6         | 1.26%   |
| Seagate ST1000DM010-2EP102 1TB                       | 5         | 1.05%   |
| Samsung HD322HJ 320GB                                | 5         | 1.05%   |
| Kingston SA400S37960G 960GB                          | 5         | 1.05%   |
| Toshiba MQ01ABD100 1TB                               | 4         | 0.84%   |
| Seagate ST500LT012-9WS142 500GB                      | 4         | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 4         | 0.84%   |
| Samsung HD502HJ 500GB                                | 4         | 0.84%   |
| KingSpec MT-128 128GB                                | 4         | 0.84%   |
| Gigabyte GP-GSTFS31120GNTD 120GB                     | 4         | 0.84%   |
| WDC WDS240G2G0A-00JH30 240GB                         | 3         | 0.63%   |
| WDC WD10EZEX-00RKKA0 1TB                             | 3         | 0.63%   |
| Seagate ST4000DM000-1F2168 4TB                       | 3         | 0.63%   |
| Seagate ST2000DM006-2DM164 2TB                       | 3         | 0.63%   |
| Seagate ST1000LM048-2E7172 1TB                       | 3         | 0.63%   |
| SanDisk SSD PLUS 240GB                               | 3         | 0.63%   |
| SanDisk SDSSDA240G 240GB                             | 3         | 0.63%   |
| Samsung HM321HI 320GB                                | 3         | 0.63%   |
| Samsung HD161HJ 160GB                                | 3         | 0.63%   |
| Samsung HD103SJ 1TB                                  | 3         | 0.63%   |
| Product:              USB DISK 2.0 USB DISK 2.0 16GB | 3         | 0.63%   |
| Kingston SUV400S37240G 240GB                         | 3         | 0.63%   |
| Kingston SUV400S37120G 120GB                         | 3         | 0.63%   |
| KingSpec P4-120 120GB                                | 3         | 0.63%   |
| Crucial CT120BX500SSD1 120GB                         | 3         | 0.63%   |
| China SATA SSD 120GB                                 | 3         | 0.63%   |
| A-DATA SU630 240GB                                   | 3         | 0.63%   |
| XrayDisk 1TB SSD                                     | 2         | 0.42%   |
| WDC WDS480G2G0B-00EPW0 480GB                         | 2         | 0.42%   |
| WDC WDS120G2G0A-00JH30 120GB                         | 2         | 0.42%   |
| WDC WD5000AAKX-00U6AA0 500GB                         | 2         | 0.42%   |
| WDC WD3200AAJS-00YZCA0 320GB                         | 2         | 0.42%   |
| WDC WD2500BEVT-75ZCT2 250GB                          | 2         | 0.42%   |
| WDC WD10SPZX-24Z10 1TB                               | 2         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate                            | 68        | 132    | 34.87%  |
| WDC                                | 59        | 73     | 30.26%  |
| Samsung Electronics                | 25        | 35     | 12.82%  |
| Toshiba                            | 22        | 26     | 11.28%  |
| Hitachi                            | 5         | 9      | 2.56%   |
| Product:              USB DISK 2.0 | 3         | 3      | 1.54%   |
| NVMe                               | 3         | 5      | 1.54%   |
| HGST                               | 3         | 4      | 1.54%   |
| Hewlett-Packard                    | 3         | 4      | 1.54%   |
| SMI                                | 2         | 2      | 1.03%   |
| Maxtor                             | 1         | 1      | 0.51%   |
| Generic                            | 1         | 1      | 0.51%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 65        | 103    | 30.37%  |
| SanDisk             | 26        | 30     | 12.15%  |
| KingSpec            | 12        | 16     | 5.61%   |
| Crucial             | 12        | 19     | 5.61%   |
| China               | 12        | 17     | 5.61%   |
| A-DATA Technology   | 10        | 12     | 4.67%   |
| WDC                 | 9         | 12     | 4.21%   |
| Hoodisk             | 9         | 9      | 4.21%   |
| Samsung Electronics | 8         | 9      | 3.74%   |
| XrayDisk            | 5         | 5      | 2.34%   |
| Gigabyte Technology | 5         | 9      | 2.34%   |
| LITEON              | 4         | 4      | 1.87%   |
| SK hynix            | 3         | 4      | 1.4%    |
| PNY                 | 3         | 3      | 1.4%    |
| Patriot             | 2         | 5      | 0.93%   |
| NTC                 | 2         | 2      | 0.93%   |
| Kston               | 2         | 2      | 0.93%   |
| Vaseky              | 1         | 1      | 0.47%   |
| Transcend           | 1         | 2      | 0.47%   |
| Teelkoou            | 1         | 1      | 0.47%   |
| tecmiyo             | 1         | 2      | 0.47%   |
| Smart               | 1         | 1      | 0.47%   |
| Silicon             | 1         | 1      | 0.47%   |
| Qunion              | 1         | 1      | 0.47%   |
| NVMe                | 1         | 1      | 0.47%   |
| Netac               | 1         | 1      | 0.47%   |
| MACROVIP            | 1         | 1      | 0.47%   |
| LITEONIT            | 1         | 1      | 0.47%   |
| Lexar               | 1         | 1      | 0.47%   |
| Intel               | 1         | 2      | 0.47%   |
| Indilinx            | 1         | 2      | 0.47%   |
| Hikvision           | 1         | 1      | 0.47%   |
| HGST                | 1         | 1      | 0.47%   |
| Faspeed             | 1         | 1      | 0.47%   |
| Fanxiang            | 1         | 1      | 0.47%   |
| Drevo               | 1         | 7      | 0.47%   |
| Corsair             | 1         | 1      | 0.47%   |
| BR                  | 1         | 2      | 0.47%   |
| Biostar             | 1         | 1      | 0.47%   |
| BHT                 | 1         | 1      | 0.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 194       | 297    | 48.99%  |
| HDD  | 162       | 295    | 40.91%  |
| NVMe | 40        | 47     | 10.1%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 306       | 592    | 88.44%  |
| NVMe | 40        | 47     | 11.56%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 270       | 438    | 75.84%  |
| 0.51-1.0   | 60        | 84     | 16.85%  |
| 1.01-2.0   | 19        | 34     | 5.34%   |
| 3.01-4.0   | 5         | 34     | 1.4%    |
| 4.01-10.0  | 2         | 2      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 148       | 34.34%  |
| 1-20           | 77        | 17.87%  |
| 251-500        | 73        | 16.94%  |
| 51-100         | 54        | 12.53%  |
| 21-50          | 34        | 7.89%   |
| 501-1000       | 27        | 6.26%   |
| 1001-2000      | 10        | 2.32%   |
| 2001-3000      | 4         | 0.93%   |
| More than 3000 | 2         | 0.46%   |
| Unknown        | 2         | 0.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 355       | 88.31%  |
| 21-50     | 25        | 6.22%   |
| 101-250   | 7         | 1.74%   |
| 501-1000  | 5         | 1.24%   |
| 51-100    | 5         | 1.24%   |
| Unknown   | 2         | 0.5%    |
| 251-500   | 1         | 0.25%   |
| 2001-3000 | 1         | 0.25%   |
| 1001-2000 | 1         | 0.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB     | 4         | 5      | 3.64%   |
| Samsung Electronics HD322HJ 320GB   | 4         | 5      | 3.64%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 4      | 2.73%   |
| WDC WD10EZEX-00RKKA0 1TB            | 2         | 2      | 1.82%   |
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 1.82%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 1.82%   |
| Seagate ST9320325AS 320GB           | 2         | 2      | 1.82%   |
| Seagate ST9160314AS 160GB           | 2         | 2      | 1.82%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 2         | 2      | 1.82%   |
| SanDisk SSD PLUS 120GB              | 2         | 2      | 1.82%   |
| Samsung Electronics HM321HI 320GB   | 2         | 2      | 1.82%   |
| Samsung Electronics HD502HJ 500GB   | 2         | 3      | 1.82%   |
| Samsung Electronics HD161HJ 160GB   | 2         | 2      | 1.82%   |
| Kingston SV300S37A60G 64GB          | 2         | 2      | 1.82%   |
| KingSpec P4-120 120GB               | 2         | 3      | 1.82%   |
| XrayDisk SSD 240GB                  | 1         | 1      | 0.91%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 0.91%   |
| WDC WD5000B 500GB                   | 1         | 1      | 0.91%   |
| WDC WD5000AVVS-63H0B1 500GB         | 1         | 1      | 0.91%   |
| WDC WD5000AAKX-603CA0 500GB         | 1         | 2      | 0.91%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 1         | 1      | 0.91%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 0.91%   |
| WDC WD5000AAKX-003CA0 500GB         | 1         | 2      | 0.91%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1         | 1      | 0.91%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1         | 1      | 0.91%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 1      | 0.91%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1         | 1      | 0.91%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1         | 1      | 0.91%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1         | 1      | 0.91%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 1         | 1      | 0.91%   |
| WDC WD2502ABYS-18B7A0 250GB         | 1         | 1      | 0.91%   |
| WDC WD2500AAJS-75M0A0 250GB         | 1         | 1      | 0.91%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 1      | 0.91%   |
| WDC WD10PURX-64E5EY0 1TB            | 1         | 1      | 0.91%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 1      | 0.91%   |
| WDC WD10EADS-65M2BX 1TB             | 1         | 1      | 0.91%   |
| Transcend TS32GMSM610 32GB          | 1         | 2      | 0.91%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 0.91%   |
| Toshiba MK8052GSX 80GB              | 1         | 1      | 0.91%   |
| Toshiba MK6465GSX 640GB             | 1         | 2      | 0.91%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 39     | 26.17%  |
| WDC                 | 20        | 24     | 18.69%  |
| Samsung Electronics | 14        | 18     | 13.08%  |
| Toshiba             | 13        | 14     | 12.15%  |
| Kingston            | 6         | 7      | 5.61%   |
| Hitachi             | 5         | 9      | 4.67%   |
| KingSpec            | 4         | 5      | 3.74%   |
| SanDisk             | 3         | 3      | 2.8%    |
| HGST                | 2         | 2      | 1.87%   |
| A-DATA Technology   | 2         | 2      | 1.87%   |
| XrayDisk            | 1         | 1      | 0.93%   |
| Transcend           | 1         | 2      | 0.93%   |
| tecmiyo             | 1         | 2      | 0.93%   |
| SK hynix            | 1         | 1      | 0.93%   |
| Silicon Motion      | 1         | 1      | 0.93%   |
| Netac               | 1         | 1      | 0.93%   |
| Maxtor              | 1         | 1      | 0.93%   |
| LITEON              | 1         | 1      | 0.93%   |
| Corsair             | 1         | 1      | 0.93%   |
| China               | 1         | 1      | 0.93%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 39     | 34.15%  |
| WDC                 | 20        | 24     | 24.39%  |
| Samsung Electronics | 14        | 18     | 17.07%  |
| Toshiba             | 13        | 14     | 15.85%  |
| Hitachi             | 5         | 9      | 6.1%    |
| Maxtor              | 1         | 1      | 1.22%   |
| HGST                | 1         | 1      | 1.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 74        | 106    | 74.75%  |
| SSD  | 24        | 28     | 24.24%  |
| NVMe | 1         | 1      | 1.01%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-00YZCA0 320GB      | 1         | 1      | 25%     |
| Seagate ST3160318AS 160GB         | 1         | 1      | 25%     |
| Samsung Electronics HM500JJ 500GB | 1         | 1      | 25%     |
| Samsung Electronics HD103SJ 1TB   | 1         | 2      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 50%     |
| WDC                 | 1         | 1      | 25%     |
| Seagate             | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 273       | 477    | 70.18%  |
| Malfunc  | 95        | 135    | 24.42%  |
| Detected | 17        | 22     | 4.37%   |
| Failed   | 4         | 5      | 1.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 322       | 69.7%   |
| AMD                            | 52        | 11.26%  |
| Silicon Motion                 | 17        | 3.68%   |
| Broadcom / LSI                 | 13        | 2.81%   |
| Kingston Technology Company    | 10        | 2.16%   |
| ADATA Technology               | 9         | 1.95%   |
| Samsung Electronics            | 8         | 1.73%   |
| Nvidia                         | 6         | 1.3%    |
| Solid State Storage Technology | 4         | 0.87%   |
| SK hynix                       | 2         | 0.43%   |
| Realtek Semiconductor          | 2         | 0.43%   |
| Phison Electronics             | 2         | 0.43%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.43%   |
| JMicron Technology             | 2         | 0.43%   |
| Hewlett-Packard                | 2         | 0.43%   |
| Toshiba                        | 1         | 0.22%   |
| Shenzhen Longsys Electronics   | 1         | 0.22%   |
| SanDisk                        | 1         | 0.22%   |
| Micron/Crucial Technology      | 1         | 0.22%   |
| KIOXIA                         | 1         | 0.22%   |
| Integrated Technology Express  | 1         | 0.22%   |
| Biwin Storage Technology       | 1         | 0.22%   |
| ASMedia Technology             | 1         | 0.22%   |
| Adaptec                        | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 24        | 4.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 22        | 4.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 22        | 4.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 18        | 3.4%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 18        | 3.4%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 17        | 3.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 17        | 3.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 17        | 3.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 16        | 3.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 14        | 2.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 13        | 2.46%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 13        | 2.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13        | 2.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12        | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 10        | 1.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9         | 1.7%    |
| AMD 500 Series Chipset SATA Controller                                                  | 9         | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8         | 1.51%   |
| Intel SATA Controller [RAID mode]                                                       | 7         | 1.32%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 1.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 7         | 1.32%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 1.32%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 1.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6         | 1.13%   |
| ADATA IM2P33F8 series NVMe SSD (DRAM-less)                                              | 6         | 1.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 5         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5         | 0.95%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                          | 4         | 0.76%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 4         | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4         | 0.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 4         | 0.76%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 0.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 0.76%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4         | 0.76%   |
| Broadcom / LSI MegaRAID SAS 2008 [Falcon]                                               | 4         | 0.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 306       | 65.11%  |
| IDE  | 71        | 15.11%  |
| NVMe | 61        | 12.98%  |
| RAID | 29        | 6.17%   |
| SCSI | 2         | 0.43%   |
| SAS  | 1         | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 334       | 84.56%  |
| AMD     | 59        | 14.94%  |
| ARM     | 1         | 0.25%   |
| Unknown | 1         | 0.25%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron J4125 CPU @ 2.00GHz           | 12        | 3.02%   |
| Intel Celeron N5105 @ 2.00GHz               | 10        | 2.52%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 6         | 1.51%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 5         | 1.26%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 5         | 1.26%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 5         | 1.26%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 5         | 1.26%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 1.01%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 4         | 1.01%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 4         | 1.01%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 4         | 1.01%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4         | 1.01%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 4         | 1.01%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz         | 3         | 0.76%   |
| Intel Pentium Silver N6005 @ 2.00GHz        | 3         | 0.76%   |
| Intel N100                                  | 3         | 0.76%   |
| Intel CPU Version                           | 3         | 0.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 0.76%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 3         | 0.76%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 0.76%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 3         | 0.76%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 3         | 0.76%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3         | 0.76%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 3         | 0.76%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3         | 0.76%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 0.76%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 3         | 0.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 0.76%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3         | 0.76%   |
| AMD FX-8320E Eight-Core Processor           | 3         | 0.76%   |
| AMD FX-6300 Six-Core Processor              | 3         | 0.76%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 2         | 0.5%    |
| Intel Xeon CPU E5620 @ 2.40GHz              | 2         | 0.5%    |
| Intel Xeon CPU E5506 @ 2.13GHz              | 2         | 0.5%    |
| Intel Xeon CPU E5-2609 v2 @ 2.50GHz         | 2         | 0.5%    |
| Intel Xeon CPU E5-2420 v2 @ 2.20GHz         | 2         | 0.5%    |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 2         | 0.5%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 0.5%    |
| Intel Genuine CPU                           | 2         | 0.5%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 77        | 19.44%  |
| Intel Celeron           | 62        | 15.66%  |
| Intel Core i3           | 53        | 13.38%  |
| Intel Xeon              | 38        | 9.6%    |
| Intel Core i7           | 29        | 7.32%   |
| Intel Core 2 Duo        | 21        | 5.3%    |
| Other                   | 17        | 4.29%   |
| AMD Ryzen 5             | 13        | 3.28%   |
| Intel Pentium           | 11        | 2.78%   |
| AMD Ryzen 7             | 11        | 2.78%   |
| AMD FX                  | 11        | 2.78%   |
| Intel Atom              | 7         | 1.77%   |
| Intel Pentium Dual-Core | 6         | 1.52%   |
| Intel Core 2 Quad       | 5         | 1.26%   |
| Intel Pentium Silver    | 3         | 0.76%   |
| AMD Ryzen 3             | 3         | 0.76%   |
| Intel Genuine           | 2         | 0.51%   |
| AMD E1                  | 2         | 0.51%   |
| AMD E                   | 2         | 0.51%   |
| AMD C-60                | 2         | 0.51%   |
| AMD Athlon 64 X2        | 2         | 0.51%   |
| AMD A10                 | 2         | 0.51%   |
| Intel Xeon Silver       | 1         | 0.25%   |
| Intel Pentium M         | 1         | 0.25%   |
| Intel Pentium Gold      | 1         | 0.25%   |
| Intel Pentium Dual      | 1         | 0.25%   |
| Intel Core M            | 1         | 0.25%   |
| Intel Core 2            | 1         | 0.25%   |
| ARM Cortex              | 1         | 0.25%   |
| AMD Turion II Neo       | 1         | 0.25%   |
| AMD Ryzen 5 PRO         | 1         | 0.25%   |
| AMD Ryzen 3 PRO         | 1         | 0.25%   |
| AMD PRO A8              | 1         | 0.25%   |
| AMD Phenom              | 1         | 0.25%   |
| AMD C-50                | 1         | 0.25%   |
| AMD Athlon II X2        | 1         | 0.25%   |
| AMD Athlon II           | 1         | 0.25%   |
| AMD Athlon              | 1         | 0.25%   |
| AMD A8                  | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 169       | 42.46%  |
| 4       | 141       | 35.43%  |
| 8       | 26        | 6.53%   |
| 6       | 23        | 5.78%   |
| Unknown | 17        | 4.27%   |
| 12      | 12        | 3.02%   |
| 16      | 6         | 1.51%   |
| 1       | 2         | 0.5%    |
| 24      | 1         | 0.25%   |
| 14      | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 374       | 95.17%  |
| 2       | 16        | 4.07%   |
| Unknown | 3         | 0.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 213       | 53.79%  |
| 2       | 166       | 41.92%  |
| Unknown | 17        | 4.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 45        | 11.34%  |
| IvyBridge     | 38        | 9.57%   |
| Penryn        | 34        | 8.56%   |
| SandyBridge   | 33        | 8.31%   |
| Haswell       | 33        | 8.31%   |
| Unknown       | 31        | 7.81%   |
| Skylake       | 21        | 5.29%   |
| Silvermont    | 18        | 4.53%   |
| Goldmont plus | 17        | 4.28%   |
| Broadwell     | 15        | 3.78%   |
| Westmere      | 14        | 3.53%   |
| Zen+          | 10        | 2.52%   |
| Core          | 10        | 2.52%   |
| Zen 3         | 9         | 2.27%   |
| Piledriver    | 8         | 2.02%   |
| Nehalem       | 8         | 2.02%   |
| Bobcat        | 7         | 1.76%   |
| TigerLake     | 6         | 1.51%   |
| Goldmont      | 6         | 1.51%   |
| CometLake     | 6         | 1.51%   |
| Zen 2         | 5         | 1.26%   |
| Zen           | 4         | 1.01%   |
| Steamroller   | 4         | 1.01%   |
| K10           | 4         | 1.01%   |
| Bonnell       | 4         | 1.01%   |
| Bulldozer     | 3         | 0.76%   |
| K8 Hammer     | 2         | 0.5%    |
| IceLake       | 2         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 272       | 65.07%  |
| AMD                        | 67        | 16.03%  |
| Nvidia                     | 52        | 12.44%  |
| Matrox Electronics Systems | 24        | 5.74%   |
| ASPEED Technology          | 3         | 0.72%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 28        | 6.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 18        | 4.23%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 17        | 3.99%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 17        | 3.99%   |
| Intel JasperLake [UHD Graphics]                                             | 15        | 3.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 14        | 3.29%   |
| Intel HD Graphics 5500                                                      | 12        | 2.82%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 12        | 2.82%   |
| Intel Core Processor Integrated Graphics Controller                         | 11        | 2.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10        | 2.35%   |
| Intel HD Graphics 630                                                       | 10        | 2.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9         | 2.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 9         | 2.11%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 8         | 1.88%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 8         | 1.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 8         | 1.88%   |
| Intel UHD Graphics 620                                                      | 7         | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7         | 1.64%   |
| Intel HD Graphics 530                                                       | 6         | 1.41%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6         | 1.41%   |
| Matrox Electronics Systems MGA G200EH                                       | 5         | 1.17%   |
| Matrox Electronics Systems G200eR2                                          | 5         | 1.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 5         | 1.17%   |
| Intel HD Graphics 620                                                       | 5         | 1.17%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5         | 1.17%   |
| AMD ES1000                                                                  | 5         | 1.17%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 4         | 0.94%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller    | 4         | 0.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 4         | 0.94%   |
| Intel HD Graphics 500                                                       | 4         | 0.94%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4         | 0.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4         | 0.94%   |
| Nvidia GT218 [GeForce 210]                                                  | 3         | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 0.7%    |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 3         | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 3         | 0.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 0.7%    |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                | 3         | 0.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 232       | 58.44%  |
| 1 x AMD        | 61        | 15.37%  |
| 1 x Nvidia     | 31        | 7.81%   |
| 1 x Matrox     | 24        | 6.05%   |
| Intel + Nvidia | 21        | 5.29%   |
| 2 x Intel      | 13        | 3.27%   |
| Other          | 6         | 1.51%   |
| Intel + AMD    | 6         | 1.51%   |
| 1 x ASPEED     | 3         | 0.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 364       | 91.69%  |
| Proprietary | 24        | 6.05%   |
| Unknown     | 9         | 2.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 342       | 85.71%  |
| 0.01-0.5   | 14        | 3.51%   |
| 1.01-2.0   | 13        | 3.26%   |
| 0.51-1.0   | 13        | 3.26%   |
| 3.01-4.0   | 11        | 2.76%   |
| 7.01-8.0   | 4         | 1%      |
| 5.01-6.0   | 1         | 0.25%   |
| 2.01-3.0   | 1         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 33        | 19.3%   |
| Goldstar                | 25        | 14.62%  |
| Samsung Electronics     | 21        | 12.28%  |
| BOE                     | 19        | 11.11%  |
| LG Display              | 16        | 9.36%   |
| Chimei Innolux          | 11        | 6.43%   |
| AOC                     | 9         | 5.26%   |
| Philips                 | 6         | 3.51%   |
| Lenovo                  | 5         | 2.92%   |
| InfoVision              | 4         | 2.34%   |
| Dell                    | 3         | 1.75%   |
| Apple                   | 3         | 1.75%   |
| Hewlett-Packard         | 2         | 1.17%   |
| VIE                     | 1         | 0.58%   |
| Unknown (XXX)           | 1         | 0.58%   |
| Semp Toshiba            | 1         | 0.58%   |
| PANDA                   | 1         | 0.58%   |
| Panasonic               | 1         | 0.58%   |
| MTD                     | 1         | 0.58%   |
| MStar                   | 1         | 0.58%   |
| LG Electronics          | 1         | 0.58%   |
| JDI                     | 1         | 0.58%   |
| ITE                     | 1         | 0.58%   |
| Chi Mei Optoelectronics | 1         | 0.58%   |
| ASUSTek Computer        | 1         | 0.58%   |
| AGO                     | 1         | 0.58%   |
| Acer                    | 1         | 0.58%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 4         | 2.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 4         | 2.27%   |
| AU Optronics LCD Monitor AUO303C 1366x768 310x170mm 13.9-inch         | 3         | 1.7%    |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 2         | 1.14%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch   | 2         | 1.14%   |
| LG Display LCD Monitor LGD0458 1366x768 310x170mm 13.9-inch           | 2         | 1.14%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 1.14%   |
| BOE LCD Monitor BOE08CD 1366x768 340x190mm 15.3-inch                  | 2         | 1.14%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 2         | 1.14%   |
| BOE LCD Monitor BOE05EF 1366x768 310x170mm 13.9-inch                  | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch         | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO263D 1920x1080 310x170mm 13.9-inch        | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch         | 2         | 1.14%   |
| AOC T2242we AOC2242 1920x1080 480x270mm 21.7-inch                     | 2         | 1.14%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 2         | 1.14%   |
| VIE E195 VIE1950 1600x900 410x280mm 19.5-inch                         | 1         | 0.57%   |
| Unknown (XXX) Beyond TV XXX9221 1920x1080 1210x680mm 54.6-inch        | 1         | 0.57%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch             | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch  | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch   | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                      | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 480x270mm 21.7-inch  | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM04E4 1600x900 440x250mm 19.9-inch   | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch   | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch   | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 310x230mm 15.2-inch  | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch   | 1         | 0.57%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 440x250mm 19.9-inch  | 1         | 0.57%   |
| Samsung Electronics S23C550 SAM0A42 1920x1080 510x290mm 23.1-inch     | 1         | 0.57%   |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch      | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SMT27A550 1920x1080                   | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 890x500mm 40.2-inch | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SAM0678 1360x768                      | 1         | 0.57%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1         | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 67        | 39.64%  |
| 1920x1080 (FHD)    | 58        | 34.32%  |
| 1600x900 (HD+)     | 12        | 7.1%    |
| 1440x900 (WXGA+)   | 5         | 2.96%   |
| 2560x1080          | 4         | 2.37%   |
| 1360x768           | 4         | 2.37%   |
| 1280x800 (WXGA)    | 4         | 2.37%   |
| 1280x1024 (SXGA)   | 3         | 1.78%   |
| 2560x1600          | 2         | 1.18%   |
| 1680x1050 (WSXGA+) | 2         | 1.18%   |
| 1024x768 (XGA)     | 2         | 1.18%   |
| 3840x2160 (4K)     | 1         | 0.59%   |
| 3640x1920          | 1         | 0.59%   |
| 2560x1440 (QHD)    | 1         | 0.59%   |
| 1280x720 (HD)      | 1         | 0.59%   |
| 1024x600           | 1         | 0.59%   |
| Unknown            | 1         | 0.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 46        | 26.59%  |
| 15      | 38        | 21.97%  |
| 21      | 14        | 8.09%   |
| 23      | 12        | 6.94%   |
| 19      | 10        | 5.78%   |
| 18      | 9         | 5.2%    |
| 14      | 7         | 4.05%   |
| 24      | 6         | 3.47%   |
| 12      | 6         | 3.47%   |
| Unknown | 6         | 3.47%   |
| 34      | 4         | 2.31%   |
| 20      | 4         | 2.31%   |
| 31      | 2         | 1.16%   |
| 27      | 2         | 1.16%   |
| 54      | 1         | 0.58%   |
| 52      | 1         | 0.58%   |
| 46      | 1         | 0.58%   |
| 40      | 1         | 0.58%   |
| 17      | 1         | 0.58%   |
| 11      | 1         | 0.58%   |
| 10      | 1         | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 81        | 47.09%  |
| 401-500     | 36        | 20.93%  |
| 501-600     | 19        | 11.05%  |
| 201-300     | 19        | 11.05%  |
| Unknown     | 6         | 3.49%   |
| 701-800     | 4         | 2.33%   |
| 1001-1500   | 3         | 1.74%   |
| 601-700     | 2         | 1.16%   |
| 801-900     | 1         | 0.58%   |
| 351-400     | 1         | 0.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 134       | 83.75%  |
| 16/10   | 12        | 7.5%    |
| 4/3     | 4         | 2.5%    |
| 21/9    | 4         | 2.5%    |
| 5/4     | 2         | 1.25%   |
| 3/2     | 2         | 1.25%   |
| Unknown | 2         | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 48        | 27.75%  |
| 91-100         | 34        | 19.65%  |
| 201-250        | 31        | 17.92%  |
| 151-200        | 15        | 8.67%   |
| 141-150        | 10        | 5.78%   |
| 61-70          | 6         | 3.47%   |
| 351-500        | 6         | 3.47%   |
| Unknown        | 6         | 3.47%   |
| 101-110        | 5         | 2.89%   |
| More than 1000 | 2         | 1.16%   |
| 71-80          | 2         | 1.16%   |
| 301-350        | 2         | 1.16%   |
| 111-120        | 2         | 1.16%   |
| 501-1000       | 2         | 1.16%   |
| 51-60          | 1         | 0.58%   |
| 41-50          | 1         | 0.58%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 75        | 44.12%  |
| 51-100  | 49        | 28.82%  |
| 121-160 | 29        | 17.06%  |
| 161-240 | 6         | 3.53%   |
| Unknown | 6         | 3.53%   |
| 1-50    | 5         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 212       | 53%     |
| 1     | 167       | 41.75%  |
| 2     | 21        | 5.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 210       | 36.46%  |
| Intel                      | 203       | 35.24%  |
| Qualcomm Atheros           | 65        | 11.28%  |
| Broadcom                   | 49        | 8.51%   |
| Samsung Electronics        | 7         | 1.22%   |
| JMicron Technology         | 6         | 1.04%   |
| Ralink Technology          | 5         | 0.87%   |
| Ralink                     | 4         | 0.69%   |
| Nvidia                     | 3         | 0.52%   |
| MediaTek                   | 3         | 0.52%   |
| IMC Networks               | 3         | 0.52%   |
| D-Link System              | 3         | 0.52%   |
| TP-Link                    | 2         | 0.35%   |
| Mellanox Technologies      | 2         | 0.35%   |
| ZTE WCDMA Technologies MSM | 1         | 0.17%   |
| Xiaomi                     | 1         | 0.17%   |
| SysKonnect                 | 1         | 0.17%   |
| STMicroelectronics         | 1         | 0.17%   |
| Marvell Technology Group   | 1         | 0.17%   |
| ICS Advent                 | 1         | 0.17%   |
| IBM                        | 1         | 0.17%   |
| Edimax Technology          | 1         | 0.17%   |
| Dell                       | 1         | 0.17%   |
| Arduino SA                 | 1         | 0.17%   |
| 3Com                       | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 142       | 20.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 43        | 6.31%   |
| Intel I211 Gigabit Network Connection                                         | 20        | 2.94%   |
| Intel Ethernet Controller I225-V                                              | 20        | 2.94%   |
| Intel Ethernet Controller I226-V                                              | 18        | 2.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 17        | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 15        | 2.2%    |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 12        | 1.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 12        | 1.76%   |
| Intel 82574L Gigabit Network Connection                                       | 12        | 1.76%   |
| Intel I350 Gigabit Network Connection                                         | 11        | 1.62%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 11        | 1.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 9         | 1.32%   |
| Intel 82576 Gigabit Network Connection                                        | 9         | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 8         | 1.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 7         | 1.03%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 7         | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 7         | 1.03%   |
| Intel Wireless 7265                                                           | 7         | 1.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 6         | 0.88%   |
| Intel Wireless 8265 / 8275                                                    | 6         | 0.88%   |
| Intel Wi-Fi 6 AX201                                                           | 6         | 0.88%   |
| Intel I210 Gigabit Network Connection                                         | 6         | 0.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 0.88%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 0.88%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 6         | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5         | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5         | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 5         | 0.73%   |
| Intel Wireless 3165                                                           | 5         | 0.73%   |
| Intel Wi-Fi 6 AX200                                                           | 5         | 0.73%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 4         | 0.59%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                  | 4         | 0.59%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 4         | 0.59%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 4         | 0.59%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 0.59%   |
| Intel 82583V Gigabit Network Connection                                       | 4         | 0.59%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 4         | 0.59%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 3         | 0.44%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 3         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 69        | 37.91%  |
| Qualcomm Atheros      | 56        | 30.77%  |
| Realtek Semiconductor | 30        | 16.48%  |
| Broadcom              | 10        | 5.49%   |
| Ralink Technology     | 5         | 2.75%   |
| Ralink                | 4         | 2.2%    |
| IMC Networks          | 3         | 1.65%   |
| TP-Link               | 2         | 1.1%    |
| MediaTek              | 1         | 0.55%   |
| Edimax Technology     | 1         | 0.55%   |
| D-Link System         | 1         | 0.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 17        | 9.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15        | 8.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 4.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 4.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 7         | 3.8%    |
| Intel Wireless 7265                                            | 7         | 3.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 3.26%   |
| Intel Wireless 8265 / 8275                                     | 6         | 3.26%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 3.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 3.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5         | 2.72%   |
| Intel Wireless 3165                                            | 5         | 2.72%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 2.72%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                   | 4         | 2.17%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 4         | 2.17%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 1.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 1.63%   |
| Intel Wireless 8260                                            | 3         | 1.63%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 3         | 1.63%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 3         | 1.63%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 1.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 1.09%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                           | 2         | 1.09%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 2         | 1.09%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 1.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.09%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.09%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.09%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.09%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.09%   |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.54%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 0.54%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1         | 0.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 199       | 44.72%  |
| Intel                      | 164       | 36.85%  |
| Broadcom                   | 41        | 9.21%   |
| Qualcomm Atheros           | 14        | 3.15%   |
| Samsung Electronics        | 7         | 1.57%   |
| JMicron Technology         | 6         | 1.35%   |
| Nvidia                     | 3         | 0.67%   |
| MediaTek                   | 2         | 0.45%   |
| D-Link System              | 2         | 0.45%   |
| ZTE WCDMA Technologies MSM | 1         | 0.22%   |
| Xiaomi                     | 1         | 0.22%   |
| SysKonnect                 | 1         | 0.22%   |
| Marvell Technology Group   | 1         | 0.22%   |
| ICS Advent                 | 1         | 0.22%   |
| IBM                        | 1         | 0.22%   |
| 3Com                       | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 142       | 28.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 43        | 8.76%   |
| Intel I211 Gigabit Network Connection                                         | 20        | 4.07%   |
| Intel Ethernet Controller I225-V                                              | 20        | 4.07%   |
| Intel Ethernet Controller I226-V                                              | 18        | 3.67%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 12        | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 12        | 2.44%   |
| Intel 82574L Gigabit Network Connection                                       | 12        | 2.44%   |
| Intel I350 Gigabit Network Connection                                         | 11        | 2.24%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 11        | 2.24%   |
| Intel 82576 Gigabit Network Connection                                        | 9         | 1.83%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 7         | 1.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 7         | 1.43%   |
| Intel I210 Gigabit Network Connection                                         | 6         | 1.22%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 1.22%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 6         | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5         | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 5         | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 4         | 0.81%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 4         | 0.81%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 0.81%   |
| Intel 82583V Gigabit Network Connection                                       | 4         | 0.81%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 4         | 0.81%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 3         | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 3         | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                                         | 3         | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 0.61%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 0.61%   |
| Intel Ethernet Connection (2) I218-V                                          | 3         | 0.61%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 0.61%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 0.61%   |
| Intel 82578DC Gigabit Network Connection                                      | 3         | 0.61%   |
| Intel 82575GB Gigabit Network Connection                                      | 3         | 0.61%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3         | 0.61%   |
| Broadcom NetXtreme II BCM57800 1/10 Gigabit Ethernet                          | 3         | 0.61%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 3         | 0.61%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 3         | 0.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 3         | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 372       | 67.64%  |
| WiFi     | 171       | 31.09%  |
| Unknown  | 5         | 0.91%   |
| Modem    | 2         | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 329       | 75.98%  |
| WiFi     | 103       | 23.79%  |
| Unknown  | 1         | 0.23%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 168       | 42%     |
| 1     | 86        | 21.5%   |
| 4     | 62        | 15.5%   |
| 3     | 36        | 9%      |
| 6     | 22        | 5.5%    |
| 5     | 16        | 4%      |
| 8     | 4         | 1%      |
| 7     | 2         | 0.5%    |
| 11    | 1         | 0.25%   |
| 10    | 1         | 0.25%   |
| 9     | 1         | 0.25%   |
| 0     | 1         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 354       | 87.84%  |
| Yes  | 49        | 12.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 40.63%  |
| Qualcomm Atheros Communications | 31        | 24.22%  |
| Realtek Semiconductor           | 10        | 7.81%   |
| Cambridge Silicon Radio         | 8         | 6.25%   |
| Broadcom                        | 7         | 5.47%   |
| Apple                           | 7         | 5.47%   |
| Lite-On Technology              | 6         | 4.69%   |
| Foxconn / Hon Hai               | 4         | 3.13%   |
| Qcom                            | 1         | 0.78%   |
| IMC Networks                    | 1         | 0.78%   |
| Dell                            | 1         | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 19        | 14.84%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 13        | 10.16%  |
| Realtek Bluetooth Adapter                                   | 9         | 7.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 8         | 6.25%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 7         | 5.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 7         | 5.47%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 6         | 4.69%   |
| Intel AX201 Bluetooth                                       | 5         | 3.91%   |
| Intel AX200 Bluetooth                                       | 5         | 3.91%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 4         | 3.13%   |
| Intel AX210 Bluetooth                                       | 4         | 3.13%   |
| Apple Bluetooth Host Controller                             | 4         | 3.13%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 3         | 2.34%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 3         | 2.34%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 2.34%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 2         | 1.56%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 1.56%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.56%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 2         | 1.56%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 1.56%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 0.78%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.78%   |
| Qcom Broadcom Bluetooth USB                                 | 1         | 0.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.78%   |
| Lite-On MediaTek Bluetooth MT7921                           | 1         | 0.78%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.78%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 0.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.78%   |
| Intel AX211 Bluetooth                                       | 1         | 0.78%   |
| IMC Networks Bluetooth Module                               | 1         | 0.78%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 0.78%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 0.78%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.78%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 0.78%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 0.78%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 276       | 69.7%   |
| AMD                                             | 69        | 17.42%  |
| Nvidia                                          | 35        | 8.84%   |
| C-Media Electronics                             | 6         | 1.52%   |
| Zoran Co. Personal Media Division (Nogatech)    | 1         | 0.25%   |
| Texas Instruments                               | 1         | 0.25%   |
| Plantronics                                     | 1         | 0.25%   |
| M-Audio                                         | 1         | 0.25%   |
| Logitech                                        | 1         | 0.25%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.25%   |
| Lenovo                                          | 1         | 0.25%   |
| KTMicro                                         | 1         | 0.25%   |
| Generalplus Technology                          | 1         | 0.25%   |
| DSEA A/S                                        | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 29        | 6.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 25        | 5.3%    |
| Intel Sunrise Point-LP HD Audio                                            | 24        | 5.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 24        | 5.08%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 21        | 4.45%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 17        | 3.6%    |
| Intel Jasper Lake HD Audio                                                 | 15        | 3.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 15        | 3.18%   |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 2.97%   |
| Intel 8 Series HD Audio Controller                                         | 14        | 2.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 14        | 2.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 13        | 2.75%   |
| Intel Broadwell-U Audio Controller                                         | 13        | 2.75%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 2.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 2.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 12        | 2.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 2.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 2.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 1.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 1.48%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.48%   |
| AMD FCH Azalia Controller                                                  | 7         | 1.48%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 1.27%   |
| AMD Wrestler HDMI Audio                                                    | 6         | 1.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 5         | 1.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.85%   |
| Nvidia High Definition Audio Controller                                    | 4         | 0.85%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 0.85%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 4         | 0.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4         | 0.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 0.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.64%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.64%   |
| Intel Elkhart Lake High Density Audio bus interface                        | 3         | 0.64%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 3         | 0.64%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 67        | 15.23%  |
| Kingston            | 60        | 13.64%  |
| Smart               | 56        | 12.73%  |
| Samsung Electronics | 51        | 11.59%  |
| SK hynix            | 26        | 5.91%   |
| A-DATA Technology   | 21        | 4.77%   |
| Crucial             | 19        | 4.32%   |
| Unknown             | 18        | 4.09%   |
| Teikon              | 17        | 3.86%   |
| Micron Technology   | 15        | 3.41%   |
| Corsair             | 7         | 1.59%   |
| Smart Brazil        | 6         | 1.36%   |
| High Bridge         | 6         | 1.36%   |
| Unknown (ABCD)      | 5         | 1.14%   |
| Hewlett-Packard     | 4         | 0.91%   |
| PUSKILL             | 3         | 0.68%   |
| Multilaser          | 3         | 0.68%   |
| G.Skill             | 3         | 0.68%   |
| Apacer              | 3         | 0.68%   |
| Toshiba             | 2         | 0.45%   |
| Team                | 2         | 0.45%   |
| Smart Modular       | 2         | 0.45%   |
| RZX                 | 2         | 0.45%   |
| Patriot             | 2         | 0.45%   |
| Nanya Technology    | 2         | 0.45%   |
| Kllisre             | 2         | 0.45%   |
| Hikvision           | 2         | 0.45%   |
| Atermiter           | 2         | 0.45%   |
| 019400B300CE        | 2         | 0.45%   |
| Unknown (AB)        | 1         | 0.23%   |
| Unknown (8A02)      | 1         | 0.23%   |
| Unknown (0x5846)    | 1         | 0.23%   |
| Unknown (0x0DD5)    | 1         | 0.23%   |
| Unknown (0x0B92)    | 1         | 0.23%   |
| Unknown (0x0B45)    | 1         | 0.23%   |
| Unknown (0x0080)    | 1         | 0.23%   |
| Transcend           | 1         | 0.23%   |
| tigo                | 1         | 0.23%   |
| SK_Hynix            | 1         | 0.23%   |
| Qumo                | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 18        | 3.83%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s          | 6         | 1.28%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s            | 6         | 1.28%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 5         | 1.06%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s          | 5         | 1.06%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 4         | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 4         | 0.85%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s          | 4         | 0.85%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s          | 4         | 0.85%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s          | 4         | 0.85%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 3         | 0.64%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 3         | 0.64%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 3         | 0.64%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 3         | 0.64%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 3         | 0.64%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 3         | 0.64%   |
| Unknown RAM Module 2GB DIMM DDR2                               | 3         | 0.64%   |
| Unknown RAM Module 2GB DIMM                                    | 3         | 0.64%   |
| Smart RAM SH564568FH8N0QHSCG 2GB DIMM DDR3 1333MT/s            | 3         | 0.64%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s          | 3         | 0.64%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s          | 3         | 0.64%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2400MT/s   | 3         | 0.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s          | 3         | 0.64%   |
| Kingston RAM Module 8GB SODIMM DDR3 1600MT/s                   | 3         | 0.64%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                    | 2         | 0.43%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 2         | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 2         | 0.43%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 2         | 0.43%   |
| Teikon RAM TMTS8G58DFRBFKB-16 8GB SODIMM DDR3 1600MT/s         | 2         | 0.43%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s         | 2         | 0.43%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s         | 2         | 0.43%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s             | 2         | 0.43%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s            | 2         | 0.43%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1333MT/s          | 2         | 0.43%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s          | 2         | 0.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.43%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s          | 2         | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 2         | 0.43%   |
| Samsung RAM M471A1K43CB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 173       | 46.63%  |
| DDR4    | 127       | 34.23%  |
| DDR2    | 25        | 6.74%   |
| Unknown | 19        | 5.12%   |
| SDRAM   | 14        | 3.77%   |
| LPDDR4  | 7         | 1.89%   |
| DDR5    | 3         | 0.81%   |
| LPDDR5  | 1         | 0.27%   |
| LPDDR3  | 1         | 0.27%   |
| DDR     | 1         | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 187       | 50.68%  |
| SODIMM       | 171       | 46.34%  |
| Row Of Chips | 7         | 1.9%    |
| FB-DIMM      | 3         | 0.81%   |
| Chip         | 1         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 141       | 34.14%  |
| 8192  | 133       | 32.2%   |
| 2048  | 84        | 20.34%  |
| 16384 | 41        | 9.93%   |
| 1024  | 9         | 2.18%   |
| 32768 | 5         | 1.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 106       | 26.24%  |
| 1333    | 60        | 14.85%  |
| 2400    | 49        | 12.13%  |
| 2667    | 36        | 8.91%   |
| 3200    | 33        | 8.17%   |
| Unknown | 23        | 5.69%   |
| 2133    | 15        | 3.71%   |
| 800     | 13        | 3.22%   |
| 1334    | 12        | 2.97%   |
| 667     | 11        | 2.72%   |
| 2666    | 9         | 2.23%   |
| 1067    | 7         | 1.73%   |
| 1066    | 6         | 1.49%   |
| 3000    | 3         | 0.74%   |
| 1867    | 3         | 0.74%   |
| 1866    | 3         | 0.74%   |
| 533     | 3         | 0.74%   |
| 5600    | 2         | 0.5%    |
| 2933    | 2         | 0.5%    |
| 400     | 2         | 0.5%    |
| 6400    | 1         | 0.25%   |
| 4800    | 1         | 0.25%   |
| 4267    | 1         | 0.25%   |
| 4000    | 1         | 0.25%   |
| 975     | 1         | 0.25%   |
| 333     | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| ELGIN  | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model        | Computers | Percent |
|--------------|-----------|---------|
| ELGIN L42PRO | 2         | 100%    |

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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 26        | 22.81%  |
| Bison Electronics             | 19        | 16.67%  |
| Microdia                      | 13        | 11.4%   |
| Realtek Semiconductor         | 10        | 8.77%   |
| Silicon Motion                | 9         | 7.89%   |
| Sunplus Innovation Technology | 4         | 3.51%   |
| Logitech                      | 4         | 3.51%   |
| IMC Networks                  | 4         | 3.51%   |
| Syntek                        | 3         | 2.63%   |
| Suyin                         | 3         | 2.63%   |
| Luxvisions Innotech Limited   | 3         | 2.63%   |
| Apple                         | 3         | 2.63%   |
| Unknown                       | 2         | 1.75%   |
| Quanta                        | 2         | 1.75%   |
| Lenovo                        | 2         | 1.75%   |
| Alcor Micro                   | 2         | 1.75%   |
| Z-Star Microelectronics       | 1         | 0.88%   |
| Tripath Technology            | 1         | 0.88%   |
| Lite-On Technology            | 1         | 0.88%   |
| Aveo Technology               | 1         | 0.88%   |
| ALi                           | 1         | 0.88%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Bison Integrated Camera                       | 9         | 7.83%   |
| Microdia Integrated_Webcam_HD                 | 6         | 5.22%   |
| Chicony HD WebCam                             | 6         | 5.22%   |
| Silicon Motion Realtek DMFT RGB               | 4         | 3.48%   |
| Microdia Dell Laptop Integrated Webcam HD     | 4         | 3.48%   |
| Syntek EasyCamera                             | 3         | 2.61%   |
| Sunplus Integrated_Webcam_HD                  | 3         | 2.61%   |
| Silicon Motion Realtek USB 2.0 PC Camera      | 3         | 2.61%   |
| Realtek Dell EasyCamera                       | 3         | 2.61%   |
| Luxvisions Innotech Limited Integrated Camera | 3         | 2.61%   |
| Chicony Sony Visual Communication Camera      | 3         | 2.61%   |
| Chicony Integrated Camera                     | 3         | 2.61%   |
| Bison Lenovo EasyCamera                       | 3         | 2.61%   |
| Unknown Realtek PC Camera                     | 2         | 1.74%   |
| Realtek Integrated Webcam                     | 2         | 1.74%   |
| Logitech Webcam C270                          | 2         | 1.74%   |
| IMC Networks EasyCamera                       | 2         | 1.74%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 2         | 1.74%   |
| Bison HD Webcam                               | 2         | 1.74%   |
| Apple FaceTime HD Camera                      | 2         | 1.74%   |
| Alcor Micro Acer Integrated Webcam            | 2         | 1.74%   |
| Z-Star Venus USB2.0 Camera                    | 1         | 0.87%   |
| Tripath USB Camera                            | 1         | 0.87%   |
| Suyin WebCam                                  | 1         | 0.87%   |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 0.87%   |
| Suyin Integrated_Webcam_HD                    | 1         | 0.87%   |
| Sunplus HD WebCam                             | 1         | 0.87%   |
| Silicon Motion WebCam SCX Series              | 1         | 0.87%   |
| Silicon Motion ATIV VGA Camera                | 1         | 0.87%   |
| Realtek LG Camera                             | 1         | 0.87%   |
| Realtek Integrated_Webcam_FHD                 | 1         | 0.87%   |
| Realtek Integrated_Webcam_8M                  | 1         | 0.87%   |
| Realtek Integrated Webcam HD                  | 1         | 0.87%   |
| Realtek Composite Webcam                      | 1         | 0.87%   |
| Realtek Acer 640 x 480 laptop camera          | 1         | 0.87%   |
| Quanta LG Webcam                              | 1         | 0.87%   |
| Quanta HD Webcam                              | 1         | 0.87%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 0.87%   |
| Microdia Laptop_Integrated_Webcam_1.3M        | 1         | 0.87%   |
| Microdia Integrated Webcam HD                 | 1         | 0.87%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 30%     |
| Synaptics                  | 5         | 25%     |
| Upek                       | 4         | 20%     |
| Shenzhen Goodix Technology | 2         | 10%     |
| Samsung Electronics        | 1         | 5%      |
| Elan Microelectronics      | 1         | 5%      |
| Broadcom                   | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 4         | 20%     |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 10%     |
| Synaptics WBDI                                                               | 2         | 10%     |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 2         | 10%     |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 10%     |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 5%      |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 5%      |
| Validity Sensors Synaptics WBDI                                              | 1         | 5%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 5%      |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 5%      |
| Elan Fingerprint Sensor                                                      | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5%      |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 164       | 41.21%  |
| 0     | 126       | 31.66%  |
| 2     | 68        | 17.09%  |
| 3     | 24        | 6.03%   |
| 4     | 11        | 2.76%   |
| 5     | 5         | 1.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 242       | 60.8%   |
| Bluetooth                | 44        | 11.06%  |
| Card reader              | 39        | 9.8%    |
| Net/wireless             | 38        | 9.55%   |
| Fingerprint reader       | 19        | 4.77%   |
| Sound                    | 6         | 1.51%   |
| Network                  | 4         | 1.01%   |
| Net/ethernet             | 2         | 0.5%    |
| Graphics card            | 2         | 0.5%    |
| Storage                  | 1         | 0.25%   |
| Firewire controller      | 1         | 0.25%   |

