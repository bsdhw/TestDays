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

Total: 385

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | DH61BR G32662-203           | [c082ba6276](https://bsd-hardware.info/?probe=c082ba6276) | Jan 06, 2025 |
| CWWK          | CW-J6-6L                    | [938c3dd6d1](https://bsd-hardware.info/?probe=938c3dd6d1) | Jan 04, 2025 |
| ASRock        | FM2A55M-HD+ R2.0            | [f7a1fd8000](https://bsd-hardware.info/?probe=f7a1fd8000) | Dec 31, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [e03720a10c](https://bsd-hardware.info/?probe=e03720a10c) | Dec 27, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [34c03dc287](https://bsd-hardware.info/?probe=34c03dc287) | Dec 18, 2024 |
| Dell          | 0CU409                      | [4a9ae9da54](https://bsd-hardware.info/?probe=4a9ae9da54) | Dec 10, 2024 |
| ASRock        | B550 PG Riptide             | [183c138b5d](https://bsd-hardware.info/?probe=183c138b5d) | Dec 09, 2024 |
| Unknown       | Unknown                     | [365e2536fc](https://bsd-hardware.info/?probe=365e2536fc) | Dec 06, 2024 |
| Dell          | 0RY206                      | [e72ddbe6c0](https://bsd-hardware.info/?probe=e72ddbe6c0) | Dec 04, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [06d16e6428](https://bsd-hardware.info/?probe=06d16e6428) | Dec 03, 2024 |
| ASRock        | FM2A55M-HD+ R2.0            | [6554ebbcca](https://bsd-hardware.info/?probe=6554ebbcca) | Nov 25, 2024 |
| ASRock        | FM2A55M-HD+ R2.0            | [989b523126](https://bsd-hardware.info/?probe=989b523126) | Nov 15, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [b9b63a6ca9](https://bsd-hardware.info/?probe=b9b63a6ca9) | Nov 15, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [0def0b220f](https://bsd-hardware.info/?probe=0def0b220f) | Nov 13, 2024 |
| Unknown       | Unknown                     | [4bf2350360](https://bsd-hardware.info/?probe=4bf2350360) | Nov 09, 2024 |
| CncTion       | J4125-4L V1.0               | [c012eb7002](https://bsd-hardware.info/?probe=c012eb7002) | Nov 07, 2024 |
| Dell          | 0GDG8Y A02                  | [ad27700305](https://bsd-hardware.info/?probe=ad27700305) | Nov 07, 2024 |
| Unknown       | Unknown                     | [7d3443149e](https://bsd-hardware.info/?probe=7d3443149e) | Nov 03, 2024 |
| Gigabyte      | B550M DS3H AC               | [5a48320b8b](https://bsd-hardware.info/?probe=5a48320b8b) | Oct 31, 2024 |
| Dell          | 053CWD A00                  | [1a6b365ab4](https://bsd-hardware.info/?probe=1a6b365ab4) | Oct 30, 2024 |
| Gigabyte      | B450M DS3H-CF               | [ef22672b81](https://bsd-hardware.info/?probe=ef22672b81) | Oct 29, 2024 |
| Unknown       | Unknown                     | [5a4da349a3](https://bsd-hardware.info/?probe=5a4da349a3) | Oct 27, 2024 |
| CncTion       | J4125-4L V1.0               | [9f1b523fb3](https://bsd-hardware.info/?probe=9f1b523fb3) | Oct 23, 2024 |
| Unknown       | Unknown                     | [72c8a667f9](https://bsd-hardware.info/?probe=72c8a667f9) | Oct 23, 2024 |
| Dell          | 0RY206                      | [72fd9572dc](https://bsd-hardware.info/?probe=72fd9572dc) | Oct 21, 2024 |
| ASRock        | G31M-VS2                    | [76aa159718](https://bsd-hardware.info/?probe=76aa159718) | Oct 18, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | [3e9754954d](https://bsd-hardware.info/?probe=3e9754954d) | Oct 12, 2024 |
| Techvision    | TVI7309X B0                 | [00717c120b](https://bsd-hardware.info/?probe=00717c120b) | Oct 09, 2024 |
| Gigabyte      | C847N                       | [5098f443ae](https://bsd-hardware.info/?probe=5098f443ae) | Oct 09, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | [cb476ab6ab](https://bsd-hardware.info/?probe=cb476ab6ab) | Oct 09, 2024 |
| CncTion       | J4125-4L V1.0               | [c634bbc0e5](https://bsd-hardware.info/?probe=c634bbc0e5) | Oct 08, 2024 |
| Gigabyte      | B550M DS3H AC               | [399f958c29](https://bsd-hardware.info/?probe=399f958c29) | Oct 08, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | [e4e1bf6fa2](https://bsd-hardware.info/?probe=e4e1bf6fa2) | Oct 05, 2024 |
| Gigabyte      | B550M DS3H AC               | [6bed12aa05](https://bsd-hardware.info/?probe=6bed12aa05) | Oct 03, 2024 |
| HP            | 8062                        | [0e7e52042b](https://bsd-hardware.info/?probe=0e7e52042b) | Oct 01, 2024 |
| Intel         | X99-P4 V8.0                 | [e6972a88e8](https://bsd-hardware.info/?probe=e6972a88e8) | Sep 30, 2024 |
| Intel         | DQ77KB AAG81483-501         | [03185ed878](https://bsd-hardware.info/?probe=03185ed878) | Sep 29, 2024 |
| Gigabyte      | H110M-H-CF                  | [9d4ad1a258](https://bsd-hardware.info/?probe=9d4ad1a258) | Sep 26, 2024 |
| Gigabyte      | H170N-WIFI-CF               | [4e733b287a](https://bsd-hardware.info/?probe=4e733b287a) | Sep 20, 2024 |
| Gigabyte      | H110M-H-CF                  | [c2e72acbcd](https://bsd-hardware.info/?probe=c2e72acbcd) | Sep 17, 2024 |
| CncTion       | J4125-4L V1.0               | [55e3221edf](https://bsd-hardware.info/?probe=55e3221edf) | Sep 09, 2024 |
| ASRock        | Z87M Pro4                   | [dbbdcc1fe6](https://bsd-hardware.info/?probe=dbbdcc1fe6) | Aug 31, 2024 |
| ASRock        | Z87M Pro4                   | [2ddfd242d0](https://bsd-hardware.info/?probe=2ddfd242d0) | Aug 27, 2024 |
| CncTion       | J4125-4L V1.0               | [595c124d74](https://bsd-hardware.info/?probe=595c124d74) | Aug 20, 2024 |
| CncTion       | J4125-4L V1.0               | [9dec1304e2](https://bsd-hardware.info/?probe=9dec1304e2) | Aug 19, 2024 |
| Unknown       | Unknown                     | [5194f3264e](https://bsd-hardware.info/?probe=5194f3264e) | Aug 19, 2024 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [e7df8e47f0](https://bsd-hardware.info/?probe=e7df8e47f0) | Aug 17, 2024 |
| Itautec       | IS12UT0 versao1             | [0df5f3f7e0](https://bsd-hardware.info/?probe=0df5f3f7e0) | Aug 14, 2024 |
| Intel         | DQ77KB AAG81483-501         | [b34365cda2](https://bsd-hardware.info/?probe=b34365cda2) | Aug 08, 2024 |
| ASRock        | B550 PG Riptide             | [2e59d3c157](https://bsd-hardware.info/?probe=2e59d3c157) | Aug 05, 2024 |
| Techvision    | TVI7309X B0                 | [248e52de1a](https://bsd-hardware.info/?probe=248e52de1a) | Aug 05, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [242b9ea518](https://bsd-hardware.info/?probe=242b9ea518) | Aug 04, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [7ed3471df1](https://bsd-hardware.info/?probe=7ed3471df1) | Aug 04, 2024 |
| Unknown       | DH61BR G32662-203           | [596a891e0a](https://bsd-hardware.info/?probe=596a891e0a) | Aug 04, 2024 |
| Intel         | E5-A99 V1.2                 | [5b39b1d1c0](https://bsd-hardware.info/?probe=5b39b1d1c0) | Jul 31, 2024 |
| Intel         | X99-P4 V8.0                 | [0b82977c6e](https://bsd-hardware.info/?probe=0b82977c6e) | Jul 31, 2024 |
| ASRock        | B450M-HDV R4.0              | [cd3e80c5af](https://bsd-hardware.info/?probe=cd3e80c5af) | Jul 28, 2024 |
| Unknown       | 1.0                         | [94f03e97ea](https://bsd-hardware.info/?probe=94f03e97ea) | Jul 27, 2024 |
| Unknown       | DH61BR G32662-203           | [6e073b5233](https://bsd-hardware.info/?probe=6e073b5233) | Jul 26, 2024 |
| Unknown       | Unknown                     | [5bc1c6ba5f](https://bsd-hardware.info/?probe=5bc1c6ba5f) | Jul 26, 2024 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [ed6505a58e](https://bsd-hardware.info/?probe=ed6505a58e) | Jul 19, 2024 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [b1de030d31](https://bsd-hardware.info/?probe=b1de030d31) | Jul 19, 2024 |
| Intel         | J1900                       | [475a904b20](https://bsd-hardware.info/?probe=475a904b20) | Jul 04, 2024 |
| Dell EMC      | EDGE620-CPU A00             | [970f4eb5d1](https://bsd-hardware.info/?probe=970f4eb5d1) | Jun 24, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6d499422cd](https://bsd-hardware.info/?probe=6d499422cd) | Jun 23, 2024 |
| HP            | ProLiant ML310e Gen8        | [7b0f897223](https://bsd-hardware.info/?probe=7b0f897223) | Jun 21, 2024 |
| Techvision    | TVI7309X B0                 | [5ea99ffcb7](https://bsd-hardware.info/?probe=5ea99ffcb7) | Jun 18, 2024 |
| Techvision    | TVI7309X B0                 | [6091912e69](https://bsd-hardware.info/?probe=6091912e69) | Jun 16, 2024 |
| Intel         | X99-P4 V8.0                 | [f301ad31cf](https://bsd-hardware.info/?probe=f301ad31cf) | Jun 12, 2024 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [3ef620dd9a](https://bsd-hardware.info/?probe=3ef620dd9a) | Jun 12, 2024 |
| Yanling       | YL-CLU6L-V1                 | [4e6d8019c0](https://bsd-hardware.info/?probe=4e6d8019c0) | Jun 05, 2024 |
| pine64        | rock64_rk3328               | [d417f7c182](https://bsd-hardware.info/?probe=d417f7c182) | May 30, 2024 |
| ASUSTek       | PRIME A520M-E               | [04f0387794](https://bsd-hardware.info/?probe=04f0387794) | May 30, 2024 |
| Megaware      | MW-HDC-M 02/24/2012 - MW... | [9a662cb553](https://bsd-hardware.info/?probe=9a662cb553) | May 24, 2024 |
| Megaware      | MW-HDC-M 02/24/2012 - MW... | [ec0376f009](https://bsd-hardware.info/?probe=ec0376f009) | May 24, 2024 |
| Intel         | DQ77KB AAG81483-501         | [0bd6e7fcf6](https://bsd-hardware.info/?probe=0bd6e7fcf6) | May 24, 2024 |
| Techvision    | TVI7309X B0                 | [c605cdb907](https://bsd-hardware.info/?probe=c605cdb907) | May 11, 2024 |
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
| helloSystem 0.8.1    | 14       | 4.58%   |
| helloSystem 0.7.0    | 13       | 4.25%   |
| OPNsense 23.1.11     | 10       | 3.27%   |
| helloSystem 0.8.0    | 7        | 2.29%   |
| OPNsense 24.7.5      | 6        | 1.96%   |
| OPNsense 24.7        | 6        | 1.96%   |
| OPNsense 23.7.12     | 6        | 1.96%   |
| OPNsense 23.1.7      | 6        | 1.96%   |
| OPNsense 23.1.5      | 6        | 1.96%   |
| OPNsense 22.1.10     | 6        | 1.96%   |
| OPNsense 20.7.8      | 6        | 1.96%   |
| OPNsense 23.7.10     | 5        | 1.63%   |
| OPNsense 23.1.9      | 5        | 1.63%   |
| OPNsense 22.7.5      | 5        | 1.63%   |
| OPNsense 21.1.3      | 5        | 1.63%   |
| OPNsense 21.1        | 5        | 1.63%   |
| helloSystem 0.4.0    | 5        | 1.63%   |
| OPNsense 24.7.7      | 4        | 1.31%   |
| OPNsense 24.7.6      | 4        | 1.31%   |
| OPNsense 24.1.9      | 4        | 1.31%   |
| OPNsense 24.1.5      | 4        | 1.31%   |
| OPNsense 23.7.9      | 4        | 1.31%   |
| OPNsense 23.1        | 4        | 1.31%   |
| OPNsense 22.7.8      | 4        | 1.31%   |
| OPNsense 22.7.4      | 4        | 1.31%   |
| OPNsense 21.1.1      | 4        | 1.31%   |
| helloSystem 0.6.0    | 4        | 1.31%   |
| helloSystem 0.5.0    | 4        | 1.31%   |
| FreeBSD 14.0-CURRENT | 4        | 1.31%   |
| OPNsense 24.7.11     | 3        | 0.98%   |
| OPNsense 24.1.8      | 3        | 0.98%   |
| OPNsense 24.1.6      | 3        | 0.98%   |
| OPNsense 23.7.11     | 3        | 0.98%   |
| OPNsense 23.1.1      | 3        | 0.98%   |
| OPNsense 22.7.6      | 3        | 0.98%   |
| OPNsense 22.1.8      | 3        | 0.98%   |
| OPNsense 21.7.7      | 3        | 0.98%   |
| OPNsense 21.7.1      | 3        | 0.98%   |
| OPNsense 21.1.9      | 3        | 0.98%   |
| OPNsense 21.1.6      | 3        | 0.98%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 138      | 61.06%  |
| helloSystem | 44       | 19.47%  |
| FreeBSD     | 29       | 12.83%  |
| OpenBSD     | 4        | 1.77%   |
| GhostBSD    | 3        | 1.33%   |
| pfSense     | 2        | 0.88%   |
| NomadBSD    | 2        | 0.88%   |
| NetBSD      | 2        | 0.88%   |
| TrueNAS     | 1        | 0.44%   |
| FreeNAS     | 1        | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 219      | 98.65%  |
| i386  | 2        | 0.9%    |
| arm64 | 1        | 0.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 145      | 63.32%  |
| helloDesktop | 48       | 20.96%  |
| KDE5         | 10       | 4.37%   |
| XFCE         | 6        | 2.62%   |
| MATE         | 5        | 2.18%   |
| Openbox      | 4        | 1.75%   |
| GNOME        | 4        | 1.75%   |
| TWM          | 2        | 0.87%   |
| i3           | 2        | 0.87%   |
| X-Cinnamon   | 1        | 0.44%   |
| Window Maker | 1        | 0.44%   |
| AwesomeWM    | 1        | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 148      | 66.07%  |
| X11     | 73       | 32.59%  |
| Wayland | 3        | 1.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 159      | 70.35%  |
| SLiM    | 47       | 20.8%   |
| SDDM    | 9        | 3.98%   |
| LightDM | 5        | 2.21%   |
| GDM     | 4        | 1.77%   |
| XDM     | 1        | 0.44%   |
| Ly      | 1        | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 146      | 63.2%   |
| en_US            | 30       | 12.99%  |
| C                | 23       | 9.96%   |
| pt_BR            | 21       | 9.09%   |
| fr_FR            | 5        | 2.16%   |
| pt               | 3        | 1.3%    |
| pt_PT            | 1        | 0.43%   |
| fr               | 1        | 0.43%   |
| en_US.ISO8859-15 | 1        | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 195      | 84.78%  |
| BIOS | 35       | 15.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 103      | 44.59%  |
| Zfs    | 102      | 44.16%  |
| Cd9660 | 22       | 9.52%   |
| Ffs    | 4        | 1.73%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 207      | 91.19%  |
| MBR     | 18       | 7.93%   |
| Unknown | 2        | 0.88%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUSTek Computer        | 43       | 19.37%  |
| Unknown                 | 28       | 12.61%  |
| Intel                   | 25       | 11.26%  |
| Dell                    | 23       | 10.36%  |
| Gigabyte Technology     | 19       | 8.56%   |
| Hewlett-Packard         | 12       | 5.41%   |
| ASRock                  | 12       | 5.41%   |
| Techvision              | 8        | 3.6%    |
| MSI                     | 4        | 1.8%    |
| Lenovo                  | 4        | 1.8%    |
| Itautec                 | 4        | 1.8%    |
| Positivo                | 3        | 1.35%   |
| Pegatron                | 3        | 1.35%   |
| PCWare                  | 3        | 1.35%   |
| ECS                     | 3        | 1.35%   |
| Yanling                 | 2        | 0.9%    |
| Biostar                 | 2        | 0.9%    |
| YANYU                   | 1        | 0.45%   |
| ULTRATOP                | 1        | 0.45%   |
| T-bao                   | 1        | 0.45%   |
| Supermicro              | 1        | 0.45%   |
| Soyo                    | 1        | 0.45%   |
| Semp Toshiba            | 1        | 0.45%   |
| Procomp Ind. Eletronica | 1        | 0.45%   |
| pine64                  | 1        | 0.45%   |
| Megaware                | 1        | 0.45%   |
| maiyunda                | 1        | 0.45%   |
| LG Electronics          | 1        | 0.45%   |
| KLLISRE                 | 1        | 0.45%   |
| HC                      | 1        | 0.45%   |
| GoWin Solution          | 1        | 0.45%   |
| GALAX                   | 1        | 0.45%   |
| ECS-USA                 | 1        | 0.45%   |
| Dell EMC                | 1        | 0.45%   |
| Daten Tecnologia        | 1        | 0.45%   |
| CWWK                    | 1        | 0.45%   |
| CNCTION-IAF-E3845       | 1        | 0.45%   |
| CncTion                 | 1        | 0.45%   |
| ChangWang               | 1        | 0.45%   |
| AZW                     | 1        | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 29       | 13.06%  |
| Techvision TVI7309X            | 8        | 3.6%    |
| Intel Q3XXG4-P V1.0            | 8        | 3.6%    |
| ASUS All Series                | 6        | 2.7%    |
| ASUS PRIME B450M-GAMING/BR     | 4        | 1.8%    |
| ASUS PRIME A520M-E             | 3        | 1.35%   |
| Pegatron IPM41-D3              | 2        | 0.9%    |
| Intel H81                      | 2        | 0.9%    |
| Intel H55                      | 2        | 0.9%    |
| Gigabyte H61M-S2-B3            | 2        | 0.9%    |
| Gigabyte B550M DS3H AC         | 2        | 0.9%    |
| Dell OptiPlex 7040             | 2        | 0.9%    |
| Dell OptiPlex 3020             | 2        | 0.9%    |
| ASUS TUF Gaming B550M-PLUS     | 2        | 0.9%    |
| ASUS P8H61-M LX3 PLUS R2.0     | 2        | 0.9%    |
| ASUS P5G41T-M LX2/BR           | 2        | 0.9%    |
| ASUS M5A97 LE R2.0             | 2        | 0.9%    |
| ASUS M5A78L-M LX/BR            | 2        | 0.9%    |
| ASUS A88XM-A                   | 2        | 0.9%    |
| ASRock J4005B-ITX              | 2        | 0.9%    |
| YANYU N39SL                    | 1        | 0.45%   |
| Yanling YL-CLU6L-V1            | 1        | 0.45%   |
| Yanling NS-1U8L                | 1        | 0.45%   |
| ULTRATOP C2017-LIVA-ZE         | 1        | 0.45%   |
| T-bao MINI PC                  | 1        | 0.45%   |
| Supermicro 92.510.02134-3      | 1        | 0.45%   |
| Soyo SY-YL B550M               | 1        | 0.45%   |
| Semp Toshiba STI               | 1        | 0.45%   |
| Procomp Ind. Eletronica G41MXE | 1        | 0.45%   |
| Positivo Positivo Master D610  | 1        | 0.45%   |
| Positivo POS-PIQ77CL           | 1        | 0.45%   |
| Positivo POS-EAA75DE           | 1        | 0.45%   |
| pine64 rock64_rk3328           | 1        | 0.45%   |
| Pegatron IPMIP-GS              | 1        | 0.45%   |
| PCWare PW-945GCX               | 1        | 0.45%   |
| PCWare IPX1800G2               | 1        | 0.45%   |
| PCWare IPMH81G1                | 1        | 0.45%   |
| MSI U-100                      | 1        | 0.45%   |
| MSI MS-7877                    | 1        | 0.45%   |
| MSI MS-7698                    | 1        | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 29       | 13.06%  |
| Dell OptiPlex                  | 14       | 6.31%   |
| ASUS PRIME                     | 9        | 4.05%   |
| Techvision TVI7309X            | 8        | 3.6%    |
| Intel Q3XXG4-P                 | 8        | 3.6%    |
| ASUS All                       | 6        | 2.7%    |
| HP ProLiant                    | 5        | 2.25%   |
| Dell Vostro                    | 4        | 1.8%    |
| Dell Inspiron                  | 4        | 1.8%    |
| ASUS TUF                       | 4        | 1.8%    |
| Lenovo ThinkCentre             | 3        | 1.35%   |
| Itautec Infoway                | 3        | 1.35%   |
| ASUS P8H61-M                   | 3        | 1.35%   |
| ASUS P5G41T-M                  | 3        | 1.35%   |
| ASUS M5A78L-M                  | 3        | 1.35%   |
| Pegatron IPM41-D3              | 2        | 0.9%    |
| Intel H81                      | 2        | 0.9%    |
| Intel H55                      | 2        | 0.9%    |
| HP Compaq                      | 2        | 0.9%    |
| Gigabyte H61M-S2-B3            | 2        | 0.9%    |
| Gigabyte GA-78LMT-USB3         | 2        | 0.9%    |
| Gigabyte B550M                 | 2        | 0.9%    |
| Gigabyte B450M                 | 2        | 0.9%    |
| ASUS M5A97                     | 2        | 0.9%    |
| ASUS A88XM-A                   | 2        | 0.9%    |
| ASRock J4005B-ITX              | 2        | 0.9%    |
| YANYU N39SL                    | 1        | 0.45%   |
| Yanling YL-CLU6L-V1            | 1        | 0.45%   |
| Yanling NS-1U8L                | 1        | 0.45%   |
| ULTRATOP C2017-LIVA-ZE         | 1        | 0.45%   |
| T-bao MINI                     | 1        | 0.45%   |
| Supermicro 92.510.02134-3      | 1        | 0.45%   |
| Soyo SY-YL                     | 1        | 0.45%   |
| Semp Toshiba STI               | 1        | 0.45%   |
| Procomp Ind. Eletronica G41MXE | 1        | 0.45%   |
| Positivo Positivo              | 1        | 0.45%   |
| Positivo POS-PIQ77CL           | 1        | 0.45%   |
| Positivo POS-EAA75DE           | 1        | 0.45%   |
| pine64 rock64                  | 1        | 0.45%   |
| Pegatron IPMIP-GS              | 1        | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2022    | 36       | 16.22%  |
| 2016    | 22       | 9.91%   |
| 2013    | 19       | 8.56%   |
| 2012    | 15       | 6.76%   |
| 2010    | 15       | 6.76%   |
| 2014    | 14       | 6.31%   |
| 2018    | 13       | 5.86%   |
| 2023    | 12       | 5.41%   |
| 2017    | 12       | 5.41%   |
| 2019    | 10       | 4.5%    |
| 2011    | 10       | 4.5%    |
| 2020    | 9        | 4.05%   |
| 2008    | 9        | 4.05%   |
| 2021    | 8        | 3.6%    |
| 2009    | 8        | 3.6%    |
| 2024    | 4        | 1.8%    |
| 2007    | 3        | 1.35%   |
| 2015    | 2        | 0.9%    |
| Unknown | 1        | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 222      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 222      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 90       | 39.13%  |
| 4.01-8.0    | 63       | 27.39%  |
| 16.01-24.0  | 45       | 19.57%  |
| 32.01-64.0  | 16       | 6.96%   |
| 2.01-3.0    | 9        | 3.91%   |
| 64.01-256.0 | 4        | 1.74%   |
| 24.01-32.0  | 2        | 0.87%   |
| 3.01-4.0    | 1        | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 128      | 55.17%  |
| 0.51-1.0   | 63       | 27.16%  |
| 1.01-2.0   | 28       | 12.07%  |
| 2.01-3.0   | 7        | 3.02%   |
| 4.01-8.0   | 2        | 0.86%   |
| Unknown    | 2        | 0.86%   |
| 16.01-24.0 | 1        | 0.43%   |
| 8.01-16.0  | 1        | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 160      | 67.51%  |
| 0      | 27       | 11.39%  |
| 2      | 25       | 10.55%  |
| 3      | 13       | 5.49%   |
| 4      | 6        | 2.53%   |
| 5      | 4        | 1.69%   |
| 7      | 1        | 0.42%   |
| 6      | 1        | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 182      | 81.25%  |
| Yes       | 42       | 18.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 220      | 99.1%   |
| No        | 2        | 0.9%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 183      | 82.06%  |
| Yes       | 40       | 17.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 199      | 88.84%  |
| Yes       | 25       | 11.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Brazil  | 222      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Sao Paulo               | 27       | 10.84%  |
| Rio de Janeiro          | 15       | 6.02%   |
| SГЈo Paulo            | 12       | 4.82%   |
| Curitiba                | 10       | 4.02%   |
| Porto Alegre            | 7        | 2.81%   |
| Sao José dos Campos    | 6        | 2.41%   |
| Jaraguá do Sul         | 6        | 2.41%   |
| Osasco                  | 5        | 2.01%   |
| Maringá                | 5        | 2.01%   |
| Joinville               | 4        | 1.61%   |
| Campinas                | 4        | 1.61%   |
| Belo Horizonte          | 4        | 1.61%   |
| SÃ£o Paulo            | 3        | 1.2%    |
| Salvador                | 3        | 1.2%    |
| Novo Hamburgo           | 3        | 1.2%    |
| Londrina                | 3        | 1.2%    |
| Fortaleza               | 3        | 1.2%    |
| Brasília               | 3        | 1.2%    |
| Blumenau                | 3        | 1.2%    |
| Valparaiso de Goias     | 2        | 0.8%    |
| Sorocaba                | 2        | 0.8%    |
| Sao Leopoldo            | 2        | 0.8%    |
| Sao Jose do Rio Preto   | 2        | 0.8%    |
| Sao Bernardo do Campo   | 2        | 0.8%    |
| Santa Barbara d'Oeste   | 2        | 0.8%    |
| RondonГіpolis         | 2        | 0.8%    |
| Rio Claro               | 2        | 0.8%    |
| Pirapora                | 2        | 0.8%    |
| Jaboatao dos Guararapes | 2        | 0.8%    |
| Itaperuna               | 2        | 0.8%    |
| Guarulhos               | 2        | 0.8%    |
| Cuiabá                 | 2        | 0.8%    |
| Cruzeiro do Sul         | 2        | 0.8%    |
| BrasÃ­lia             | 2        | 0.8%    |
| VitГіria da Conquista | 1        | 0.4%    |
| Urupes                  | 1        | 0.4%    |
| Unai                    | 1        | 0.4%    |
| Uberaba                 | 1        | 0.4%    |
| Timbo                   | 1        | 0.4%    |
| Teresina                | 1        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Kingston                           | 45       | 80     | 17.11%  |
| WDC                                | 43       | 59     | 16.35%  |
| Seagate                            | 42       | 79     | 15.97%  |
| Samsung Electronics                | 23       | 36     | 8.75%   |
| SanDisk                            | 14       | 18     | 5.32%   |
| Toshiba                            | 9        | 12     | 3.42%   |
| Hoodisk                            | 9        | 9      | 3.42%   |
| China                              | 9        | 14     | 3.42%   |
| Silicon Motion                     | 7        | 8      | 2.66%   |
| KingSpec                           | 7        | 10     | 2.66%   |
| A-DATA Technology                  | 7        | 8      | 2.66%   |
| Crucial                            | 6        | 9      | 2.28%   |
| XrayDisk                           | 5        | 5      | 1.9%    |
| HGST                               | 4        | 5      | 1.52%   |
| Hitachi                            | 3        | 7      | 1.14%   |
| Gigabyte Technology                | 3        | 6      | 1.14%   |
| Fanxiang                           | 3        | 4      | 1.14%   |
| PNY                                | 2        | 2      | 0.76%   |
| NTC                                | 2        | 2      | 0.76%   |
| Vaseky                             | 1        | 1      | 0.38%   |
| Teelkoou                           | 1        | 1      | 0.38%   |
| tecmiyo                            | 1        | 2      | 0.38%   |
| SMI                                | 1        | 1      | 0.38%   |
| Silicon                            | 1        | 1      | 0.38%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.38%   |
| NVMe                               | 1        | 2      | 0.38%   |
| Netac                              | 1        | 1      | 0.38%   |
| Maxtor                             | 1        | 1      | 0.38%   |
| MACROVIP                           | 1        | 1      | 0.38%   |
| Kston                              | 1        | 1      | 0.38%   |
| Intel                              | 1        | 2      | 0.38%   |
| Indilinx                           | 1        | 2      | 0.38%   |
| Hewlett-Packard                    | 1        | 1      | 0.38%   |
| Faspeed                            | 1        | 1      | 0.38%   |
| Drevo                              | 1        | 7      | 0.38%   |
| Corsair                            | 1        | 1      | 0.38%   |
| Colorful                           | 1        | 1      | 0.38%   |
| BR                                 | 1        | 2      | 0.38%   |
| Apacer                             | 1        | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB         | 16       | 5.57%   |
| Kingston SA400S37120G 120GB         | 10       | 3.48%   |
| Seagate ST500DM002-1BD142 500GB     | 8        | 2.79%   |
| Kingston SA400S37480G 480GB         | 8        | 2.79%   |
| SanDisk SSD PLUS 120GB              | 7        | 2.44%   |
| Hoodisk SSD 64GB                    | 6        | 2.09%   |
| Seagate ST1000DM010-2EP102 1TB      | 5        | 1.74%   |
| Samsung HD322HJ 320GB               | 5        | 1.74%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4        | 1.39%   |
| WDC WD10EZEX-00RKKA0 1TB            | 3        | 1.05%   |
| Seagate ST4000DM000-1F2168 4TB      | 3        | 1.05%   |
| Seagate ST2000DM006-2DM164 2TB      | 3        | 1.05%   |
| Samsung HD502HJ 500GB               | 3        | 1.05%   |
| Samsung HD161HJ 160GB               | 3        | 1.05%   |
| Samsung HD103SJ 1TB                 | 3        | 1.05%   |
| Crucial CT120BX500SSD1 120GB        | 3        | 1.05%   |
| A-DATA SU630 240GB                  | 3        | 1.05%   |
| XrayDisk 1TB SSD                    | 2        | 0.7%    |
| WDC WDS120G2G0A-00JH30 120GB        | 2        | 0.7%    |
| WDC WD5000AAKX-00U6AA0 500GB        | 2        | 0.7%    |
| WDC WD3200AAJS-00YZCA0 320GB        | 2        | 0.7%    |
| WDC WD2500BEVT-75ZCT2 250GB         | 2        | 0.7%    |
| Toshiba MQ01ABF050 500GB            | 2        | 0.7%    |
| Silicon Motion NVME SSD 128GB       | 2        | 0.7%    |
| Seagate ST500LT012-9WS142 500GB     | 2        | 0.7%    |
| Seagate ST500DM002-1SB10A 500GB     | 2        | 0.7%    |
| Seagate ST1000DM003-1CH162 1TB      | 2        | 0.7%    |
| SanDisk SSD PLUS 240GB              | 2        | 0.7%    |
| SanDisk SDSSDA240G 240GB            | 2        | 0.7%    |
| SanDisk SDSSDA120G 120GB            | 2        | 0.7%    |
| Samsung HD081GJ 80GB                | 2        | 0.7%    |
| PNY CS900 120GB SSD                 | 2        | 0.7%    |
| Kingston SV300S37A60G 64GB          | 2        | 0.7%    |
| Kingston SUV400S37120G 120GB        | 2        | 0.7%    |
| Kingston SH103S3240G 240GB          | 2        | 0.7%    |
| KingSpec P4-120 120GB               | 2        | 0.7%    |
| KingSpec MT-128 128GB               | 2        | 0.7%    |
| Hoodisk SSD 32GB                    | 2        | 0.7%    |
| Gigabyte GP-GSTFS31120GNTD 120GB    | 2        | 0.7%    |
| Crucial CT240BX500SSD1 240GB        | 2        | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 42       | 79     | 34.71%  |
| WDC                                | 40       | 54     | 33.06%  |
| Samsung Electronics                | 19       | 27     | 15.7%   |
| Toshiba                            | 9        | 12     | 7.44%   |
| Hitachi                            | 3        | 7      | 2.48%   |
| HGST                               | 3        | 4      | 2.48%   |
| SMI                                | 1        | 1      | 0.83%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.83%   |
| NVMe                               | 1        | 2      | 0.83%   |
| Maxtor                             | 1        | 1      | 0.83%   |
| Hewlett-Packard                    | 1        | 1      | 0.83%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 41       | 76     | 32.54%  |
| SanDisk             | 14       | 18     | 11.11%  |
| Hoodisk             | 9        | 9      | 7.14%   |
| China               | 9        | 14     | 7.14%   |
| KingSpec            | 7        | 10     | 5.56%   |
| A-DATA Technology   | 7        | 8      | 5.56%   |
| Crucial             | 6        | 9      | 4.76%   |
| XrayDisk            | 5        | 5      | 3.97%   |
| WDC                 | 3        | 4      | 2.38%   |
| Gigabyte Technology | 3        | 6      | 2.38%   |
| Samsung Electronics | 2        | 3      | 1.59%   |
| PNY                 | 2        | 2      | 1.59%   |
| NTC                 | 2        | 2      | 1.59%   |
| Vaseky              | 1        | 1      | 0.79%   |
| Teelkoou            | 1        | 1      | 0.79%   |
| tecmiyo             | 1        | 2      | 0.79%   |
| Silicon             | 1        | 1      | 0.79%   |
| Netac               | 1        | 1      | 0.79%   |
| MACROVIP            | 1        | 1      | 0.79%   |
| Kston               | 1        | 1      | 0.79%   |
| Intel               | 1        | 2      | 0.79%   |
| Indilinx            | 1        | 2      | 0.79%   |
| HGST                | 1        | 1      | 0.79%   |
| Faspeed             | 1        | 1      | 0.79%   |
| Fanxiang            | 1        | 1      | 0.79%   |
| Drevo               | 1        | 7      | 0.79%   |
| Corsair             | 1        | 1      | 0.79%   |
| BR                  | 1        | 2      | 0.79%   |
| Apacer              | 1        | 1      | 0.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 116      | 192    | 50.22%  |
| HDD  | 98       | 189    | 42.42%  |
| NVMe | 17       | 23     | 7.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 183      | 381    | 91.5%   |
| NVMe | 17       | 23     | 8.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 170      | 296    | 78.7%   |
| 0.51-1.0   | 26       | 44     | 12.04%  |
| 1.01-2.0   | 14       | 29     | 6.48%   |
| 3.01-4.0   | 4        | 10     | 1.85%   |
| 4.01-10.0  | 2        | 2      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 90       | 37.04%  |
| 251-500        | 42       | 17.28%  |
| 1-20           | 39       | 16.05%  |
| 51-100         | 32       | 13.17%  |
| 21-50          | 20       | 8.23%   |
| 501-1000       | 11       | 4.53%   |
| 1001-2000      | 4        | 1.65%   |
| More than 3000 | 2        | 0.82%   |
| 2001-3000      | 2        | 0.82%   |
| Unknown        | 1        | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 205      | 90.31%  |
| 21-50     | 13       | 5.73%   |
| 101-250   | 3        | 1.32%   |
| 501-1000  | 2        | 0.88%   |
| 2001-3000 | 1        | 0.44%   |
| 1001-2000 | 1        | 0.44%   |
| 51-100    | 1        | 0.44%   |
| Unknown   | 1        | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Desktops | Drives | Percent |
|-------------------------------------------|----------|--------|---------|
| Samsung Electronics HD322HJ 320GB         | 4        | 5      | 5.48%   |
| Seagate ST500DM002-1BD142 500GB           | 3        | 4      | 4.11%   |
| WDC WD10EZEX-00RKKA0 1TB                  | 2        | 2      | 2.74%   |
| Seagate ST500LT012-9WS142 500GB           | 2        | 3      | 2.74%   |
| Samsung Electronics HD161HJ 160GB         | 2        | 2      | 2.74%   |
| Kingston SV300S37A60G 64GB                | 2        | 2      | 2.74%   |
| KingSpec P4-120 120GB                     | 2        | 3      | 2.74%   |
| XrayDisk SSD 240GB                        | 1        | 1      | 1.37%   |
| WDC WD5000LPVX-22V0TT0 500GB              | 1        | 1      | 1.37%   |
| WDC WD5000AVVS-63H0B1 500GB               | 1        | 1      | 1.37%   |
| WDC WD5000AAKX-603CA0 500GB               | 1        | 2      | 1.37%   |
| WDC WD5000AAKX-00U6AA0 500GB              | 1        | 1      | 1.37%   |
| WDC WD5000AAKX-00ERMA0 500GB              | 1        | 1      | 1.37%   |
| WDC WD5000AAKX-003CA0 500GB               | 1        | 2      | 1.37%   |
| WDC WD5000AAKS-08V0A0 500GB               | 1        | 1      | 1.37%   |
| WDC WD5000AAKS-00UU3A0 500GB              | 1        | 1      | 1.37%   |
| WDC WD3200LPVX-22V0TT0 320GB              | 1        | 1      | 1.37%   |
| WDC WD3200BEVT-00A0RT0 233GB              | 1        | 1      | 1.37%   |
| WDC WD3200AAKS-00UU3A0 320GB              | 1        | 1      | 1.37%   |
| WDC WD3200AAJS-56M0A0 320GB               | 1        | 1      | 1.37%   |
| WDC WD3200AAJS-00YZCA0 320GB              | 1        | 1      | 1.37%   |
| WDC WD2502ABYS-18B7A0 250GB               | 1        | 1      | 1.37%   |
| WDC WD2500AAJS-75M0A0 250GB               | 1        | 1      | 1.37%   |
| WDC WD10PURX-64E5EY0 1TB                  | 1        | 1      | 1.37%   |
| WDC WD10EADS-65M2BX 1TB                   | 1        | 1      | 1.37%   |
| Toshiba MQ01ABD050 500GB                  | 1        | 1      | 1.37%   |
| Toshiba MK8052GSX 80GB                    | 1        | 1      | 1.37%   |
| Toshiba MK1255GSX H 120GB                 | 1        | 1      | 1.37%   |
| tecmiyo SSD MSATA 64GB                    | 1        | 2      | 1.37%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB | 1        | 1      | 1.37%   |
| Seagate ST9320325AS 320GB                 | 1        | 1      | 1.37%   |
| Seagate ST9160314AS 160GB                 | 1        | 1      | 1.37%   |
| Seagate ST500LM021-1KJ152 500GB           | 1        | 1      | 1.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1        | 1      | 1.37%   |
| Seagate ST500DM002-1BC142 500GB           | 1        | 1      | 1.37%   |
| Seagate ST3250310AS 250GB                 | 1        | 1      | 1.37%   |
| Seagate ST320LM001 HN-M320MBB 320GB       | 1        | 1      | 1.37%   |
| Seagate ST2000DM006-2DM164 2TB            | 1        | 1      | 1.37%   |
| Seagate ST2000DM001-1E6164 2TB            | 1        | 1      | 1.37%   |
| Seagate ST2000DL003-9VT166 2TB            | 1        | 9      | 1.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 21     | 24.29%  |
| Seagate             | 15       | 25     | 21.43%  |
| Samsung Electronics | 11       | 14     | 15.71%  |
| Kingston            | 5        | 6      | 7.14%   |
| KingSpec            | 4        | 5      | 5.71%   |
| Toshiba             | 3        | 3      | 4.29%   |
| Hitachi             | 3        | 7      | 4.29%   |
| SanDisk             | 2        | 2      | 2.86%   |
| HGST                | 2        | 2      | 2.86%   |
| XrayDisk            | 1        | 1      | 1.43%   |
| tecmiyo             | 1        | 2      | 1.43%   |
| Silicon Motion      | 1        | 1      | 1.43%   |
| Netac               | 1        | 1      | 1.43%   |
| Maxtor              | 1        | 1      | 1.43%   |
| Corsair             | 1        | 1      | 1.43%   |
| China               | 1        | 1      | 1.43%   |
| A-DATA Technology   | 1        | 1      | 1.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 21     | 33.33%  |
| Seagate             | 15       | 25     | 29.41%  |
| Samsung Electronics | 11       | 14     | 21.57%  |
| Toshiba             | 3        | 3      | 5.88%   |
| Hitachi             | 3        | 7      | 5.88%   |
| Maxtor              | 1        | 1      | 1.96%   |
| HGST                | 1        | 1      | 1.96%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 47       | 72     | 71.21%  |
| SSD  | 18       | 21     | 27.27%  |
| NVMe | 1        | 1      | 1.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD3200AAJS-00YZCA0 320GB    | 1        | 1      | 33.33%  |
| Seagate ST3160318AS 160GB       | 1        | 1      | 33.33%  |
| Samsung Electronics HD103SJ 1TB | 1        | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 33.33%  |
| Seagate             | 1        | 1      | 33.33%  |
| Samsung Electronics | 1        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 156      | 293    | 67.53%  |
| Malfunc  | 62       | 94     | 26.84%  |
| Detected | 10       | 13     | 4.33%   |
| Failed   | 3        | 4      | 1.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 172      | 67.72%  |
| AMD                           | 44       | 17.32%  |
| Silicon Motion                | 13       | 5.12%   |
| Kingston Technology Company   | 7        | 2.76%   |
| Samsung Electronics           | 4        | 1.57%   |
| Nvidia                        | 3        | 1.18%   |
| JMicron Technology            | 2        | 0.79%   |
| SK hynix                      | 1        | 0.39%   |
| SanDisk                       | 1        | 0.39%   |
| Realtek Semiconductor         | 1        | 0.39%   |
| Phison Electronics            | 1        | 0.39%   |
| MAXIO Technology (Hangzhou)   | 1        | 0.39%   |
| Integrated Technology Express | 1        | 0.39%   |
| Hewlett-Packard               | 1        | 0.39%   |
| ASMedia Technology            | 1        | 0.39%   |
| Adaptec                       | 1        | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 24       | 7.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 16       | 5.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 15       | 4.87%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 15       | 4.87%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 13       | 4.22%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 13       | 4.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 3.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 3.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 9        | 2.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 2.92%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9        | 2.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 2.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8        | 2.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 2.6%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 2.27%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 2.27%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 1.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 1.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4        | 1.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4        | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 1.3%    |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.97%   |
| Nvidia MCP61 IDE                                                                        | 3        | 0.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 0.97%   |
| Intel Alder Lake-N SATA AHCI Controller                                                 | 3        | 0.97%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 0.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3        | 0.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3        | 0.97%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 0.97%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 3        | 0.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.65%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 2        | 0.65%   |
| Intel Elkhart Lake SATA AHCI                                                            | 2        | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2        | 0.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 163      | 63.18%  |
| IDE  | 57       | 22.09%  |
| NVMe | 29       | 11.24%  |
| RAID | 8        | 3.1%    |
| SCSI | 1        | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 176      | 78.57%  |
| AMD    | 47       | 20.98%  |
| ARM    | 1        | 0.45%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Celeron J4125 CPU @ 2.00GHz               | 12       | 5.31%   |
| Intel Celeron N5105 @ 2.00GHz                   | 10       | 4.42%   |
| Intel Celeron CPU J1800 @ 2.41GHz               | 5        | 2.21%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 5        | 2.21%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 4        | 1.77%   |
| Intel Core i3-7100 CPU @ 3.90GHz                | 4        | 1.77%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 4        | 1.77%   |
| Intel Pentium Silver N6005 @ 2.00GHz            | 3        | 1.33%   |
| Intel N100                                      | 3        | 1.33%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 3        | 1.33%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 3        | 1.33%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz           | 3        | 1.33%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 3        | 1.33%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 3        | 1.33%   |
| AMD FX-8320E Eight-Core Processor               | 3        | 1.33%   |
| AMD FX-6300 Six-Core Processor                  | 3        | 1.33%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 2        | 0.88%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 2        | 0.88%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 2        | 0.88%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 2        | 0.88%   |
| Intel Core i5-3570 CPU @ 3.40GHz                | 2        | 0.88%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 2        | 0.88%   |
| Intel Core i3-4030U CPU @ 1.90GHz               | 2        | 0.88%   |
| Intel Core i3-3240 CPU @ 3.40GHz                | 2        | 0.88%   |
| Intel Core i3-2100 CPU                          | 2        | 0.88%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz            | 2        | 0.88%   |
| Intel Core 2 Duo CPU                            | 2        | 0.88%   |
| Intel Celeron J4005 CPU @ 2.00GHz               | 2        | 0.88%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 2        | 0.88%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 2        | 0.88%   |
| Intel Celeron CPU 847 @ 1.10GHz                 | 2        | 0.88%   |
| AMD Ryzen 7 3800X 8-Core Processor              | 2        | 0.88%   |
| AMD FX-6100 Six-Core Processor                  | 2        | 0.88%   |
| AMD A10-7870K Radeon R7, 12 Compute Cores 4C+8G | 2        | 0.88%   |
| Intel Xeon CPU X5680 @ 3.33GHz                  | 1        | 0.44%   |
| Intel Xeon CPU X3440 @ 2.53GHz                  | 1        | 0.44%   |
| Intel Xeon CPU X3430 @ 2.40GHz                  | 1        | 0.44%   |
| Intel Xeon CPU E5506 @ 2.13GHz                  | 1        | 0.44%   |
| Intel Xeon CPU E5462 @ 2.80GHz                  | 1        | 0.44%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz              | 1        | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 44       | 19.56%  |
| Intel Core i3           | 32       | 14.22%  |
| Intel Core i5           | 30       | 13.33%  |
| Intel Xeon              | 15       | 6.67%   |
| Intel Core 2 Duo        | 15       | 6.67%   |
| AMD Ryzen 5             | 12       | 5.33%   |
| Intel Core i7           | 11       | 4.89%   |
| AMD FX                  | 11       | 4.89%   |
| AMD Ryzen 7             | 7        | 3.11%   |
| Intel Pentium Dual-Core | 6        | 2.67%   |
| Intel Pentium           | 6        | 2.67%   |
| Other                   | 5        | 2.22%   |
| Intel Core 2 Quad       | 5        | 2.22%   |
| Intel Atom              | 4        | 1.78%   |
| Intel Pentium Silver    | 3        | 1.33%   |
| AMD Ryzen 3             | 2        | 0.89%   |
| AMD Athlon 64 X2        | 2        | 0.89%   |
| AMD A10                 | 2        | 0.89%   |
| Intel Pentium Dual      | 1        | 0.44%   |
| Intel Core 2            | 1        | 0.44%   |
| ARM Cortex              | 1        | 0.44%   |
| AMD Turion II Neo       | 1        | 0.44%   |
| AMD Ryzen 5 PRO         | 1        | 0.44%   |
| AMD Ryzen 3 PRO         | 1        | 0.44%   |
| AMD PRO A8              | 1        | 0.44%   |
| AMD Phenom              | 1        | 0.44%   |
| AMD E                   | 1        | 0.44%   |
| AMD C-60                | 1        | 0.44%   |
| AMD Athlon II X2        | 1        | 0.44%   |
| AMD Athlon              | 1        | 0.44%   |
| AMD A8                  | 1        | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 92       | 40.53%  |
| 2       | 78       | 34.36%  |
| 6       | 18       | 7.93%   |
| 8       | 15       | 6.61%   |
| 12      | 9        | 3.96%   |
| Unknown | 9        | 3.96%   |
| 16      | 4        | 1.76%   |
| 14      | 1        | 0.44%   |
| 1       | 1        | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 220      | 99.1%   |
| 2       | 1        | 0.45%   |
| Unknown | 1        | 0.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 153      | 68%     |
| 2       | 63       | 28%     |
| Unknown | 9        | 4%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 24       | 10.62%  |
| Unknown       | 24       | 10.62%  |
| Haswell       | 21       | 9.29%   |
| KabyLake      | 19       | 8.41%   |
| IvyBridge     | 16       | 7.08%   |
| Goldmont plus | 15       | 6.64%   |
| SandyBridge   | 13       | 5.75%   |
| Zen 3         | 9        | 3.98%   |
| Silvermont    | 9        | 3.98%   |
| Skylake       | 8        | 3.54%   |
| Piledriver    | 8        | 3.54%   |
| Zen+          | 7        | 3.1%    |
| Westmere      | 6        | 2.65%   |
| Core          | 6        | 2.65%   |
| Broadwell     | 6        | 2.65%   |
| Nehalem       | 5        | 2.21%   |
| Zen 2         | 4        | 1.77%   |
| Zen           | 4        | 1.77%   |
| Steamroller   | 4        | 1.77%   |
| K10           | 3        | 1.33%   |
| Goldmont      | 3        | 1.33%   |
| CometLake     | 3        | 1.33%   |
| Bulldozer     | 3        | 1.33%   |
| K8 Hammer     | 2        | 0.88%   |
| Bonnell       | 2        | 0.88%   |
| Bobcat        | 2        | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 145      | 64.44%  |
| AMD                        | 47       | 20.89%  |
| Nvidia                     | 27       | 12%     |
| Matrox Electronics Systems | 5        | 2.22%   |
| ASPEED Technology          | 1        | 0.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel JasperLake [UHD Graphics]                                             | 15       | 6.55%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 15       | 6.55%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 12       | 5.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12       | 5.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 4.37%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 3.93%   |
| Intel HD Graphics 630                                                       | 9        | 3.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 9        | 3.93%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 8        | 3.49%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 8        | 3.49%   |
| Intel HD Graphics 530                                                       | 5        | 2.18%   |
| Intel Core Processor Integrated Graphics Controller                         | 5        | 2.18%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 2.18%   |
| Intel HD Graphics 5500                                                      | 4        | 1.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4        | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 1.75%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 1.75%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 1.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 1.75%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.31%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.31%   |
| Matrox Electronics Systems MGA G200EH                                       | 3        | 1.31%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 3        | 1.31%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.31%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 3        | 1.31%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 1.31%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.31%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 0.87%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2        | 0.87%   |
| Intel HD Graphics 500                                                       | 2        | 0.87%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                | 2        | 0.87%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 0.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 0.87%   |
| Nvidia GT215M [GeForce GT 335M]                                             | 1        | 0.44%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.44%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.44%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.44%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.44%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.44%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 136      | 60.18%  |
| 1 x AMD        | 44       | 19.47%  |
| 1 x Nvidia     | 26       | 11.5%   |
| Other          | 5        | 2.21%   |
| 2 x Intel      | 5        | 2.21%   |
| 1 x Matrox     | 5        | 2.21%   |
| Intel + AMD    | 3        | 1.33%   |
| Intel + Nvidia | 1        | 0.44%   |
| 1 x ASPEED     | 1        | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 203      | 90.22%  |
| Proprietary | 17       | 7.56%   |
| Unknown     | 5        | 2.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 181      | 79.74%  |
| 0.51-1.0   | 13       | 5.73%   |
| 1.01-2.0   | 12       | 5.29%   |
| 3.01-4.0   | 9        | 3.96%   |
| 0.01-0.5   | 7        | 3.08%   |
| 7.01-8.0   | 4        | 1.76%   |
| 2.01-3.0   | 1        | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 22       | 35.48%  |
| Samsung Electronics | 16       | 25.81%  |
| Philips             | 5        | 8.06%   |
| AOC                 | 5        | 8.06%   |
| Lenovo              | 2        | 3.23%   |
| VIE                 | 1        | 1.61%   |
| Unknown (XXX)       | 1        | 1.61%   |
| Semp Toshiba        | 1        | 1.61%   |
| Panasonic           | 1        | 1.61%   |
| MStar               | 1        | 1.61%   |
| LG Electronics      | 1        | 1.61%   |
| LG Display          | 1        | 1.61%   |
| ITE                 | 1        | 1.61%   |
| Hewlett-Packard     | 1        | 1.61%   |
| ASUSTek Computer    | 1        | 1.61%   |
| AGO                 | 1        | 1.61%   |
| Acer                | 1        | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0601 1600x900                      | 2        | 2.99%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch  | 2        | 2.99%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 2        | 2.99%   |
| VIE E195 VIE1950 1600x900 410x280mm 19.5-inch                        | 1        | 1.49%   |
| Unknown (XXX) Beyond TV XXX9221 1920x1080 1210x680mm 54.6-inch       | 1        | 1.49%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch            | 1        | 1.49%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch | 1        | 1.49%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch  | 1        | 1.49%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch  | 1        | 1.49%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                     | 1        | 1.49%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 480x270mm 21.7-inch | 1        | 1.49%   |
| Samsung Electronics SyncMaster SAM04E4 1600x900 440x250mm 19.9-inch  | 1        | 1.49%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch  | 1        | 1.49%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch  | 1        | 1.49%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 310x230mm 15.2-inch | 1        | 1.49%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch  | 1        | 1.49%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 440x250mm 19.9-inch | 1        | 1.49%   |
| Samsung Electronics S23C550 SAM0A42 1920x1080 510x290mm 23.1-inch    | 1        | 1.49%   |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch     | 1        | 1.49%   |
| Samsung Electronics LCD Monitor SMT27A550 1920x1080                  | 1        | 1.49%   |
| Samsung Electronics LCD Monitor SAM0678 1360x768                     | 1        | 1.49%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 1        | 1.49%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 1        | 1.49%   |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch              | 1        | 1.49%   |
| Philips LCD Monitor PHL2051 1600x900 440x250mm 19.9-inch             | 1        | 1.49%   |
| Philips 221EL PHLC056 1920x1080 480x270mm 21.7-inch                  | 1        | 1.49%   |
| Philips 202EL PHLC05C 1600x900 440x250mm 19.9-inch                   | 1        | 1.49%   |
| Panasonic TV MEIC136 1280x720 698x392mm 31.5-inch                    | 1        | 1.49%   |
| MStar TSB LEDTV MST0030 1920x1080 1150x650mm 52.0-inch               | 1        | 1.49%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 3640x1920                    | 1        | 1.49%   |
| LG Electronics LCD Monitor 23MP55                                    | 1        | 1.49%   |
| LG Display LCD Monitor LGD020C 1600x900 350x190mm 15.7-inch          | 1        | 1.49%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 480x270mm 21.7-inch             | 1        | 1.49%   |
| Lenovo L197 Wide LEN1152 1440x900 410x260mm 19.1-inch                | 1        | 1.49%   |
| ITE DP2VGA V235 ITE6516 1920x1080 600x340mm 27.2-inch                | 1        | 1.49%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch           | 1        | 1.49%   |
| Goldstar W2242 GSM4B6F 1680x1050 490x320mm 23.0-inch                 | 1        | 1.49%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                  | 1        | 1.49%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                  | 1        | 1.49%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                  | 1        | 1.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 28       | 43.75%  |
| 1600x900 (HD+)     | 10       | 15.63%  |
| 1366x768 (WXGA)    | 6        | 9.38%   |
| 1360x768           | 4        | 6.25%   |
| 2560x1080          | 3        | 4.69%   |
| 1440x900 (WXGA+)   | 3        | 4.69%   |
| 1280x1024 (SXGA)   | 3        | 4.69%   |
| 1024x768 (XGA)     | 2        | 3.13%   |
| 3840x2160 (4K)     | 1        | 1.56%   |
| 3640x1920          | 1        | 1.56%   |
| 1680x1050 (WSXGA+) | 1        | 1.56%   |
| 1280x720 (HD)      | 1        | 1.56%   |
| Unknown            | 1        | 1.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 11       | 17.19%  |
| 21      | 11       | 17.19%  |
| 19      | 10       | 15.63%  |
| 18      | 7        | 10.94%  |
| Unknown | 6        | 9.38%   |
| 34      | 3        | 4.69%   |
| 15      | 3        | 4.69%   |
| 31      | 2        | 3.13%   |
| 27      | 2        | 3.13%   |
| 20      | 2        | 3.13%   |
| 14      | 2        | 3.13%   |
| 54      | 1        | 1.56%   |
| 52      | 1        | 1.56%   |
| 24      | 1        | 1.56%   |
| 17      | 1        | 1.56%   |
| 13      | 1        | 1.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 29       | 46.03%  |
| 501-600     | 13       | 20.63%  |
| Unknown     | 6        | 9.52%   |
| 301-350     | 4        | 6.35%   |
| 701-800     | 3        | 4.76%   |
| 201-300     | 3        | 4.76%   |
| 601-700     | 2        | 3.17%   |
| 1001-1500   | 2        | 3.17%   |
| 351-400     | 1        | 1.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 45       | 73.77%  |
| 4/3     | 4        | 6.56%   |
| 21/9    | 3        | 4.92%   |
| 16/10   | 3        | 4.92%   |
| 5/4     | 2        | 3.28%   |
| 3/2     | 2        | 3.28%   |
| Unknown | 2        | 3.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 34.38%  |
| 151-200        | 13       | 20.31%  |
| 141-150        | 8        | 12.5%   |
| Unknown        | 6        | 9.38%   |
| 351-500        | 5        | 7.81%   |
| 101-110        | 3        | 4.69%   |
| More than 1000 | 2        | 3.13%   |
| 301-350        | 2        | 3.13%   |
| 91-100         | 2        | 3.13%   |
| 111-120        | 1        | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 37       | 58.73%  |
| 101-120 | 14       | 22.22%  |
| Unknown | 6        | 9.52%   |
| 1-50    | 4        | 6.35%   |
| 161-240 | 1        | 1.59%   |
| 121-160 | 1        | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 155      | 68.58%  |
| 1     | 65       | 28.76%  |
| 2     | 6        | 2.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 135      | 44.55%  |
| Intel                      | 123      | 40.59%  |
| Broadcom                   | 12       | 3.96%   |
| Qualcomm Atheros           | 11       | 3.63%   |
| Ralink                     | 4        | 1.32%   |
| IMC Networks               | 3        | 0.99%   |
| D-Link System              | 3        | 0.99%   |
| Ralink Technology          | 2        | 0.66%   |
| ZTE WCDMA Technologies MSM | 1        | 0.33%   |
| TP-Link                    | 1        | 0.33%   |
| STMicroelectronics         | 1        | 0.33%   |
| Samsung Electronics        | 1        | 0.33%   |
| Mellanox Technologies      | 1        | 0.33%   |
| MediaTek                   | 1        | 0.33%   |
| ICS Advent                 | 1        | 0.33%   |
| Edimax Technology          | 1        | 0.33%   |
| Arduino SA                 | 1        | 0.33%   |
| 3Com                       | 1        | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 105      | 29.58%  |
| Intel Ethernet Controller I225-V                                              | 18       | 5.07%   |
| Intel Ethernet Controller I226-V                                              | 17       | 4.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 15       | 4.23%   |
| Intel I211 Gigabit Network Connection                                         | 15       | 4.23%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 12       | 3.38%   |
| Intel I350 Gigabit Network Connection                                         | 8        | 2.25%   |
| Intel 82574L Gigabit Network Connection                                       | 8        | 2.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 7        | 1.97%   |
| Intel 82576 Gigabit Network Connection                                        | 7        | 1.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 6        | 1.69%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 6        | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 1.41%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4        | 1.13%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3        | 0.85%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                  | 3        | 0.85%   |
| Intel Wireless 3165                                                           | 3        | 0.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 3        | 0.85%   |
| Intel Ethernet Connection I217-LM                                             | 3        | 0.85%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 0.85%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 0.85%   |
| Intel 82583V Gigabit Network Connection                                       | 3        | 0.85%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 0.85%   |
| Intel 82578DC Gigabit Network Connection                                      | 3        | 0.85%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 3        | 0.85%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                          | 2        | 0.56%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 2        | 0.56%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 2        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.56%   |
| Intel Wireless 7265                                                           | 2        | 0.56%   |
| Intel Wi-Fi 6 AX200                                                           | 2        | 0.56%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 0.56%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 0.56%   |
| Intel 82575GB Gigabit Network Connection                                      | 2        | 0.56%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2        | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 0.56%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 15       | 34.09%  |
| Realtek Semiconductor | 14       | 31.82%  |
| Ralink                | 4        | 9.09%   |
| Qualcomm Atheros      | 3        | 6.82%   |
| IMC Networks          | 3        | 6.82%   |
| Ralink Technology     | 2        | 4.55%   |
| TP-Link               | 1        | 2.27%   |
| Edimax Technology     | 1        | 2.27%   |
| D-Link System         | 1        | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 6        | 13.33%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 6.67%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                         | 3        | 6.67%   |
| Intel Wireless 3165                                                  | 3        | 6.67%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 3        | 6.67%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                 | 3        | 6.67%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 2        | 4.44%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2        | 4.44%   |
| Intel Wireless 7265                                                  | 2        | 4.44%   |
| Intel Wi-Fi 6 AX200                                                  | 2        | 4.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1        | 2.22%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 2.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1        | 2.22%   |
| Realtek RTL8187SE Wireless LAN Controller                            | 1        | 2.22%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 2.22%   |
| Ralink MT7601U Wireless Adapter                                      | 1        | 2.22%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter      | 1        | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 2.22%   |
| Intel Wireless 8260                                                  | 1        | 2.22%   |
| Intel Wi-Fi 6 AX201 160MHz                                           | 1        | 2.22%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 1        | 2.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1        | 2.22%   |
| Intel Centrino Advanced-N 6235                                       | 1        | 2.22%   |
| Edimax AC600 Wireless LAN USB Adapter                                | 1        | 2.22%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1        | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 132      | 47.83%  |
| Intel                      | 117      | 42.39%  |
| Broadcom                   | 12       | 4.35%   |
| Qualcomm Atheros           | 8        | 2.9%    |
| D-Link System              | 2        | 0.72%   |
| ZTE WCDMA Technologies MSM | 1        | 0.36%   |
| Samsung Electronics        | 1        | 0.36%   |
| MediaTek                   | 1        | 0.36%   |
| ICS Advent                 | 1        | 0.36%   |
| 3Com                       | 1        | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 105      | 34.2%   |
| Intel Ethernet Controller I225-V                                              | 18       | 5.86%   |
| Intel Ethernet Controller I226-V                                              | 17       | 5.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 15       | 4.89%   |
| Intel I211 Gigabit Network Connection                                         | 15       | 4.89%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 12       | 3.91%   |
| Intel I350 Gigabit Network Connection                                         | 8        | 2.61%   |
| Intel 82574L Gigabit Network Connection                                       | 8        | 2.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 7        | 2.28%   |
| Intel 82576 Gigabit Network Connection                                        | 7        | 2.28%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 6        | 1.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 1.63%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4        | 1.3%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 1.3%    |
| Intel Ethernet Connection I217-LM                                             | 3        | 0.98%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 0.98%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 0.98%   |
| Intel 82583V Gigabit Network Connection                                       | 3        | 0.98%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 0.98%   |
| Intel 82578DC Gigabit Network Connection                                      | 3        | 0.98%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 2        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 0.65%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 0.65%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 0.65%   |
| Intel 82575GB Gigabit Network Connection                                      | 2        | 0.65%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2        | 0.65%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 0.65%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 0.65%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 0.65%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 0.65%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.65%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 0.65%   |
| ZTE WCDMA MSM ZXIC Mobile Boardband                                           | 1        | 0.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.33%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.33%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 1        | 0.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 0.33%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 220      | 83.65%  |
| WiFi     | 40       | 15.21%  |
| Modem    | 2        | 0.76%   |
| Unknown  | 1        | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 216      | 94.74%  |
| WiFi     | 12       | 5.26%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 60       | 26.32%  |
| 2     | 56       | 24.56%  |
| 4     | 49       | 21.49%  |
| 3     | 32       | 14.04%  |
| 5     | 14       | 6.14%   |
| 6     | 11       | 4.82%   |
| 7     | 2        | 0.88%   |
| 11    | 1        | 0.44%   |
| 9     | 1        | 0.44%   |
| 8     | 1        | 0.44%   |
| 0     | 1        | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 200      | 86.21%  |
| Yes  | 32       | 13.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 13       | 48.15%  |
| Realtek Semiconductor   | 7        | 25.93%  |
| Cambridge Silicon Radio | 6        | 22.22%  |
| Qcom                    | 1        | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Adapter                           | 7        | 25.93%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 22.22%  |
| Intel Bluetooth wireless interface                  | 5        | 18.52%  |
| Intel AX210 Bluetooth                               | 3        | 11.11%  |
| Intel AX201 Bluetooth                               | 2        | 7.41%   |
| Intel AX200 Bluetooth                               | 2        | 7.41%   |
| Qcom Broadcom Bluetooth USB                         | 1        | 3.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 150      | 62.5%   |
| AMD                                             | 56       | 23.33%  |
| Nvidia                                          | 24       | 10%     |
| C-Media Electronics                             | 6        | 2.5%    |
| Zoran Co. Personal Media Division (Nogatech)    | 1        | 0.42%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.42%   |
| KTMicro                                         | 1        | 0.42%   |
| Generalplus Technology                          | 1        | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 22       | 7.67%   |
| Intel Jasper Lake HD Audio                                                 | 15       | 5.23%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 15       | 5.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13       | 4.53%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 13       | 4.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 4.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12       | 4.18%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 11       | 3.83%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11       | 3.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10       | 3.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 3.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8        | 2.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 7        | 2.44%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 2.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 2.09%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.74%   |
| Nvidia High Definition Audio Controller                                    | 4        | 1.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4        | 1.39%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4        | 1.39%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.39%   |
| Intel Broadwell-U Audio Controller                                         | 4        | 1.39%   |
| Intel 8 Series HD Audio Controller                                         | 4        | 1.39%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 4        | 1.39%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.39%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.05%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 1.05%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 1.05%   |
| Intel Sunrise Point-LP HD Audio                                            | 3        | 1.05%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 3        | 1.05%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.05%   |
| C-Media Electronics CM108 Audio Controller                                 | 3        | 1.05%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 3        | 1.05%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.05%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.05%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 1.05%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.7%    |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 0.7%    |
| Intel Elkhart Lake High Density Audio bus interface                        | 2        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 52       | 21.14%  |
| Kingston            | 38       | 15.45%  |
| Smart               | 20       | 8.13%   |
| Samsung Electronics | 17       | 6.91%   |
| Unknown             | 16       | 6.5%    |
| Crucial             | 14       | 5.69%   |
| Micron Technology   | 11       | 4.47%   |
| A-DATA Technology   | 10       | 4.07%   |
| SK hynix            | 9        | 3.66%   |
| Teikon              | 7        | 2.85%   |
| Corsair             | 7        | 2.85%   |
| Unknown (ABCD)      | 4        | 1.63%   |
| G.Skill             | 3        | 1.22%   |
| Toshiba             | 2        | 0.81%   |
| Team                | 2        | 0.81%   |
| RZX                 | 2        | 0.81%   |
| PUSKILL             | 2        | 0.81%   |
| Patriot             | 2        | 0.81%   |
| Hikvision           | 2        | 0.81%   |
| Hewlett-Packard     | 2        | 0.81%   |
| Unknown (AB)        | 1        | 0.41%   |
| Unknown (8A02)      | 1        | 0.41%   |
| Unknown (0x5846)    | 1        | 0.41%   |
| Unknown (0x0DD5)    | 1        | 0.41%   |
| Unknown (0x0B92)    | 1        | 0.41%   |
| Unknown (0x0080)    | 1        | 0.41%   |
| tigo                | 1        | 0.41%   |
| SK_Hynix            | 1        | 0.41%   |
| Qumo                | 1        | 0.41%   |
| Nanya Technology    | 1        | 0.41%   |
| Multilaser          | 1        | 0.41%   |
| MemoWise            | 1        | 0.41%   |
| Lexar               | 1        | 0.41%   |
| Kreton              | 1        | 0.41%   |
| Kllisre             | 1        | 0.41%   |
| KingSpec            | 1        | 0.41%   |
| Kimtigo             | 1        | 0.41%   |
| Juhor               | 1        | 0.41%   |
| GLOWAY              | 1        | 0.41%   |
| Galaxy Microsystems | 1        | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 16       | 6.08%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s            | 6        | 2.28%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 5        | 1.9%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 4        | 1.52%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 3        | 1.14%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 3        | 1.14%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 3        | 1.14%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 3        | 1.14%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 3        | 1.14%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 3        | 1.14%   |
| Unknown RAM Module 2GB DIMM DDR2                               | 3        | 1.14%   |
| Unknown RAM Module 2GB DIMM                                    | 3        | 1.14%   |
| Smart RAM SH564568FH8N0QHSCG 2GB DIMM DDR3 1333MT/s            | 3        | 1.14%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 2        | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 2        | 0.76%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 2        | 0.76%   |
| Teikon RAM TMTS8G58DFRBFKB-16 8GB SODIMM DDR3 1600MT/s         | 2        | 0.76%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s             | 2        | 0.76%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s            | 2        | 0.76%   |
| Samsung RAM M471A1K43CB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2        | 0.76%   |
| RZX RAM D3D9M1333G-4G 4GB DIMM DDR3 1333MT/s                   | 2        | 0.76%   |
| Patriot RAM 2666 C16 Series 16GB DIMM DDR4 3000MT/s            | 2        | 0.76%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                      | 2        | 0.76%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s            | 2        | 0.76%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s              | 2        | 0.76%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 2        | 0.76%   |
| Kingston RAM KHX1600C10D3/ 4GB DIMM DDR3 1866MT/s              | 2        | 0.76%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s          | 2        | 0.76%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s          | 2        | 0.76%   |
| Hikvision RAM HKED4082CAA1D0HA1 8GB SODIMM DDR4 2400MT/s       | 2        | 0.76%   |
| Crucial RAM BLS4G4D240FSC.8FBD 4GB DIMM DDR4 2400MT/s          | 2        | 0.76%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s           | 2        | 0.76%   |
| Corsair RAM CMY16GX3M2A2400C11 8GB DIMM DDR3 2400MT/s          | 2        | 0.76%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2        | 0.76%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                    | 1        | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                      | 1        | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 0.38%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 1        | 0.38%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 0.38%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                   | 1        | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 81       | 37.85%  |
| DDR3    | 80       | 37.38%  |
| Unknown | 16       | 7.48%   |
| SDRAM   | 14       | 6.54%   |
| DDR2    | 13       | 6.07%   |
| LPDDR4  | 6        | 2.8%    |
| DDR5    | 2        | 0.93%   |
| LPDDR5  | 1        | 0.47%   |
| LPDDR3  | 1        | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 158      | 74.53%  |
| SODIMM       | 50       | 23.58%  |
| Row Of Chips | 3        | 1.42%   |
| Chip         | 1        | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 83       | 35.62%  |
| 4096  | 68       | 29.18%  |
| 2048  | 45       | 19.31%  |
| 16384 | 27       | 11.59%  |
| 1024  | 6        | 2.58%   |
| 32768 | 4        | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 48       | 20.87%  |
| 1333    | 37       | 16.09%  |
| 2400    | 31       | 13.48%  |
| 3200    | 22       | 9.57%   |
| 2667    | 21       | 9.13%   |
| Unknown | 20       | 8.7%    |
| 800     | 10       | 4.35%   |
| 2133    | 8        | 3.48%   |
| 2666    | 7        | 3.04%   |
| 3000    | 3        | 1.3%    |
| 1866    | 3        | 1.3%    |
| 1067    | 3        | 1.3%    |
| 667     | 3        | 1.3%    |
| 2933    | 2        | 0.87%   |
| 1867    | 2        | 0.87%   |
| 1066    | 2        | 0.87%   |
| 400     | 2        | 0.87%   |
| 6400    | 1        | 0.43%   |
| 5600    | 1        | 0.43%   |
| 4800    | 1        | 0.43%   |
| 4267    | 1        | 0.43%   |
| 4000    | 1        | 0.43%   |
| 333     | 1        | 0.43%   |

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
| 1     | 117      | 52%     |
| 0     | 87       | 38.67%  |
| 2     | 18       | 8%      |
| 3     | 2        | 0.89%   |
| 4     | 1        | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 122      | 79.74%  |
| Net/wireless             | 13       | 8.5%    |
| Bluetooth                | 10       | 6.54%   |
| Sound                    | 4        | 2.61%   |
| Network                  | 1        | 0.65%   |
| Net/ethernet             | 1        | 0.65%   |
| Graphics card            | 1        | 0.65%   |
| Firewire controller      | 1        | 0.65%   |

