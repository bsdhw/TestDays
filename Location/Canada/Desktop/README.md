BSD in Canada - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Canada.

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

Total: 551

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | PRIME B450M-A               | [1c7bbcc0ca](https://bsd-hardware.info/?probe=1c7bbcc0ca) | Jan 01, 2024 |
| ASUSTek       | PRIME B450M-A               | [6f996518f6](https://bsd-hardware.info/?probe=6f996518f6) | Dec 30, 2023 |
| Dell          | 0F3KHR A02                  | [572ad429ae](https://bsd-hardware.info/?probe=572ad429ae) | Dec 30, 2023 |
| Dell          | 0GU083 A00                  | [caaa806343](https://bsd-hardware.info/?probe=caaa806343) | Dec 28, 2023 |
| AZW           | Green G1                    | [c5bd9604b5](https://bsd-hardware.info/?probe=c5bd9604b5) | Dec 28, 2023 |
| HP            | 304Bh                       | [52ee1947b1](https://bsd-hardware.info/?probe=52ee1947b1) | Dec 27, 2023 |
| ASUSTek       | B150M-A D3                  | [d416ce02f1](https://bsd-hardware.info/?probe=d416ce02f1) | Dec 26, 2023 |
| Intel         | SHARKBAY                    | [0ec70893dd](https://bsd-hardware.info/?probe=0ec70893dd) | Dec 24, 2023 |
| Unknown       | Unknown                     | [4f79ea6f3a](https://bsd-hardware.info/?probe=4f79ea6f3a) | Dec 23, 2023 |
| Unknown       | Unknown                     | [684d183b51](https://bsd-hardware.info/?probe=684d183b51) | Dec 23, 2023 |
| Gigabyte      | MRZNVMS-00                  | [7c9af3e3cd](https://bsd-hardware.info/?probe=7c9af3e3cd) | Dec 23, 2023 |
| Unknown       | Unknown                     | [1a68705919](https://bsd-hardware.info/?probe=1a68705919) | Dec 23, 2023 |
| ASUSTek       | PRIME A320M-K               | [cfe1ed1212](https://bsd-hardware.info/?probe=cfe1ed1212) | Dec 22, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [dbcb26f795](https://bsd-hardware.info/?probe=dbcb26f795) | Dec 22, 2023 |
| HP            | 83F2                        | [858392467f](https://bsd-hardware.info/?probe=858392467f) | Dec 19, 2023 |
| HP            | 83F2                        | [8b1e24b86c](https://bsd-hardware.info/?probe=8b1e24b86c) | Dec 19, 2023 |
| Intel         | JSL MRD                     | [af718ee605](https://bsd-hardware.info/?probe=af718ee605) | Dec 17, 2023 |
| Unknown       | Unknown                     | [be79d227b2](https://bsd-hardware.info/?probe=be79d227b2) | Dec 15, 2023 |
| Gigabyte      | B75N                        | [dad5d14cf7](https://bsd-hardware.info/?probe=dad5d14cf7) | Dec 15, 2023 |
| Protectli     | FW4B Ver                    | [da6ac13ef2](https://bsd-hardware.info/?probe=da6ac13ef2) | Dec 15, 2023 |
| AZW           | EQ                          | [d83e11a7dc](https://bsd-hardware.info/?probe=d83e11a7dc) | Dec 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [67f5c9c912](https://bsd-hardware.info/?probe=67f5c9c912) | Dec 13, 2023 |
| Unknown       | Unknown                     | [5597d71956](https://bsd-hardware.info/?probe=5597d71956) | Dec 09, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [25f4e4ce18](https://bsd-hardware.info/?probe=25f4e4ce18) | Dec 09, 2023 |
| Protectli     | FW4B Ver                    | [55c513d023](https://bsd-hardware.info/?probe=55c513d023) | Dec 08, 2023 |
| ADI Engine... | RCC-VE                      | [b362c84d66](https://bsd-hardware.info/?probe=b362c84d66) | Dec 07, 2023 |
| Unknown       | Unknown                     | [d837d27d35](https://bsd-hardware.info/?probe=d837d27d35) | Dec 02, 2023 |
| AZW           | EQ                          | [e4b294ddda](https://bsd-hardware.info/?probe=e4b294ddda) | Nov 29, 2023 |
| Dell          | 0NC2VH A01                  | [938720f5a3](https://bsd-hardware.info/?probe=938720f5a3) | Nov 26, 2023 |
| Dell          | 0NC2VH A01                  | [5e87df1001](https://bsd-hardware.info/?probe=5e87df1001) | Nov 25, 2023 |
| ADI Engine... | RCC-VE                      | [437a91ad78](https://bsd-hardware.info/?probe=437a91ad78) | Nov 25, 2023 |
| Lenovo        | ThinkCentre M90n-1 11AHS... | [eca5b59407](https://bsd-hardware.info/?probe=eca5b59407) | Nov 23, 2023 |
| HP            | 0B40h                       | [035db0e1c5](https://bsd-hardware.info/?probe=035db0e1c5) | Nov 23, 2023 |
| HP            | 0B40h                       | [559cfb4b40](https://bsd-hardware.info/?probe=559cfb4b40) | Nov 23, 2023 |
| Protectli     | FW4B Ver                    | [3738ed9dd2](https://bsd-hardware.info/?probe=3738ed9dd2) | Nov 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [fe1688477a](https://bsd-hardware.info/?probe=fe1688477a) | Nov 21, 2023 |
| PC Engines    | APU                         | [53fd63efac](https://bsd-hardware.info/?probe=53fd63efac) | Nov 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [95d2a9f59c](https://bsd-hardware.info/?probe=95d2a9f59c) | Nov 21, 2023 |
| Unknown       | Unknown                     | [a3d67285a6](https://bsd-hardware.info/?probe=a3d67285a6) | Nov 19, 2023 |
| Dell          | 0NC2VH A01                  | [83673368b9](https://bsd-hardware.info/?probe=83673368b9) | Nov 17, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [2bc7167601](https://bsd-hardware.info/?probe=2bc7167601) | Nov 17, 2023 |
| Unknown       | Unknown                     | [7c541b6943](https://bsd-hardware.info/?probe=7c541b6943) | Nov 13, 2023 |
| Techvision    | TVI7309X B0                 | [c5d3028f45](https://bsd-hardware.info/?probe=c5d3028f45) | Nov 12, 2023 |
| Techvision    | TVI7309X B0                 | [10dadfc527](https://bsd-hardware.info/?probe=10dadfc527) | Nov 12, 2023 |
| Dell          | 0HHV7N A00                  | [a1f74c50b5](https://bsd-hardware.info/?probe=a1f74c50b5) | Nov 12, 2023 |
| CheckPoint    | T-180-00                    | [9ee64c3012](https://bsd-hardware.info/?probe=9ee64c3012) | Nov 11, 2023 |
| Protectli     | VP2420                      | [607a661b45](https://bsd-hardware.info/?probe=607a661b45) | Nov 08, 2023 |
| Dell          | 0NC2VH A01                  | [0d6203b7c9](https://bsd-hardware.info/?probe=0d6203b7c9) | Nov 07, 2023 |
| MW            | GMLK-2_5G4L                 | [4fe0f6ef5e](https://bsd-hardware.info/?probe=4fe0f6ef5e) | Nov 05, 2023 |
| Unknown       | Unknown                     | [1a820d6364](https://bsd-hardware.info/?probe=1a820d6364) | Nov 05, 2023 |
| Unknown       | Unknown                     | [25d85a53af](https://bsd-hardware.info/?probe=25d85a53af) | Nov 03, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [ade254cf11](https://bsd-hardware.info/?probe=ade254cf11) | Nov 01, 2023 |
| Dell          | 0NC2VH A01                  | [db40304707](https://bsd-hardware.info/?probe=db40304707) | Oct 31, 2023 |
| Dell          | 0XHGV1 A00                  | [a688954dd5](https://bsd-hardware.info/?probe=a688954dd5) | Oct 31, 2023 |
| Dell          | 0NC2VH A01                  | [e69fadd7a8](https://bsd-hardware.info/?probe=e69fadd7a8) | Oct 29, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [558a8a885e](https://bsd-hardware.info/?probe=558a8a885e) | Oct 22, 2023 |
| Dell          | 0WR7PY A01                  | [7e2e07f641](https://bsd-hardware.info/?probe=7e2e07f641) | Oct 20, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [a12be87189](https://bsd-hardware.info/?probe=a12be87189) | Oct 17, 2023 |
| Intel         | B75                         | [baead94277](https://bsd-hardware.info/?probe=baead94277) | Oct 14, 2023 |
| Dell          | 0NC2VH A01                  | [916de10c11](https://bsd-hardware.info/?probe=916de10c11) | Oct 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | [c07dd3b911](https://bsd-hardware.info/?probe=c07dd3b911) | Oct 09, 2023 |
| Unknown       | Unknown                     | [a2a905898b](https://bsd-hardware.info/?probe=a2a905898b) | Oct 08, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [39894be424](https://bsd-hardware.info/?probe=39894be424) | Oct 07, 2023 |
| Unknown       | Unknown                     | [04dbabbf69](https://bsd-hardware.info/?probe=04dbabbf69) | Oct 06, 2023 |
| Techvision    | TVI7309X B0                 | [febaed1e4e](https://bsd-hardware.info/?probe=febaed1e4e) | Oct 03, 2023 |
| Dell          | 0NC2VH A01                  | [b957ce880e](https://bsd-hardware.info/?probe=b957ce880e) | Oct 01, 2023 |
| Dell          | 0GU083 A00                  | [1286478dc2](https://bsd-hardware.info/?probe=1286478dc2) | Oct 01, 2023 |
| Supermicro    | A2SDi-TP8F                  | [9a73be8c9c](https://bsd-hardware.info/?probe=9a73be8c9c) | Sep 30, 2023 |
| HP            | 82B4                        | [60d259ab3f](https://bsd-hardware.info/?probe=60d259ab3f) | Sep 29, 2023 |
| Unknown       | Unknown                     | [df07570acc](https://bsd-hardware.info/?probe=df07570acc) | Sep 28, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [0f20928f2d](https://bsd-hardware.info/?probe=0f20928f2d) | Sep 28, 2023 |
| HP            | 18E5                        | [9c21b6e355](https://bsd-hardware.info/?probe=9c21b6e355) | Sep 25, 2023 |
| Unknown       | Unknown                     | [05f45ba264](https://bsd-hardware.info/?probe=05f45ba264) | Sep 25, 2023 |
| HP            | 18E5                        | [02b94adef6](https://bsd-hardware.info/?probe=02b94adef6) | Sep 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | [5a0b8eb786](https://bsd-hardware.info/?probe=5a0b8eb786) | Sep 21, 2023 |
| ASRock        | B450 Pro4                   | [211b0f3e9c](https://bsd-hardware.info/?probe=211b0f3e9c) | Sep 19, 2023 |
| CncTion       | Jasper-4L B0                | [96f81e84f6](https://bsd-hardware.info/?probe=96f81e84f6) | Sep 18, 2023 |
| Techvision    | TVI7309X B0                 | [7b6014f65f](https://bsd-hardware.info/?probe=7b6014f65f) | Sep 18, 2023 |
| CncTion       | Jasper-4L B0                | [4254b5eac8](https://bsd-hardware.info/?probe=4254b5eac8) | Sep 17, 2023 |
| ASRock        | B450M Pro4-F                | [b6763a8d49](https://bsd-hardware.info/?probe=b6763a8d49) | Sep 17, 2023 |
| Unknown       | Unknown                     | [0fccf590d4](https://bsd-hardware.info/?probe=0fccf590d4) | Sep 12, 2023 |
| Unknown       | Unknown                     | [7c53ad8bea](https://bsd-hardware.info/?probe=7c53ad8bea) | Sep 10, 2023 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [5695984890](https://bsd-hardware.info/?probe=5695984890) | Sep 10, 2023 |
| ASUSTek       | P8H67-M PRO                 | [7e4ea56868](https://bsd-hardware.info/?probe=7e4ea56868) | Sep 10, 2023 |
| ASUSTek       | P8H67-M PRO                 | [ee34cb0b60](https://bsd-hardware.info/?probe=ee34cb0b60) | Sep 10, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [93234978cf](https://bsd-hardware.info/?probe=93234978cf) | Sep 09, 2023 |
| Dell          | 0NC2VH A01                  | [34a855cc56](https://bsd-hardware.info/?probe=34a855cc56) | Sep 06, 2023 |
| Unknown       | Unknown                     | [19711ca08b](https://bsd-hardware.info/?probe=19711ca08b) | Sep 06, 2023 |
| ASUSTek       | P8H67-M PRO                 | [c06ec95a55](https://bsd-hardware.info/?probe=c06ec95a55) | Sep 06, 2023 |
| Dell          | 0NC2VH A01                  | [7209f86fed](https://bsd-hardware.info/?probe=7209f86fed) | Sep 04, 2023 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [a1c29072ea](https://bsd-hardware.info/?probe=a1c29072ea) | Sep 03, 2023 |
| Protectli     | FW6 Ver                     | [70992eb19b](https://bsd-hardware.info/?probe=70992eb19b) | Sep 02, 2023 |
| ASUSTek       | M5A97 PLUS                  | [77b461d3ad](https://bsd-hardware.info/?probe=77b461d3ad) | Sep 02, 2023 |
| Dell          | 042P49 A01                  | [383445ee26](https://bsd-hardware.info/?probe=383445ee26) | Sep 01, 2023 |
| Protectli     | FW6 Ver                     | [04de7aa059](https://bsd-hardware.info/?probe=04de7aa059) | Sep 01, 2023 |
| Dell          | 042P49 A01                  | [a06ab2449f](https://bsd-hardware.info/?probe=a06ab2449f) | Aug 26, 2023 |
| PC Engines    | APU2                        | [ed6839f08c](https://bsd-hardware.info/?probe=ed6839f08c) | Aug 26, 2023 |
| Dell          | 0NC2VH A01                  | [46499d5075](https://bsd-hardware.info/?probe=46499d5075) | Aug 26, 2023 |
| Unknown       | Unknown                     | [6619af0a29](https://bsd-hardware.info/?probe=6619af0a29) | Aug 26, 2023 |
| Unknown       | Unknown                     | [aad81c60fa](https://bsd-hardware.info/?probe=aad81c60fa) | Aug 25, 2023 |
| Dell          | 0KHP4K A03                  | [c54db98574](https://bsd-hardware.info/?probe=c54db98574) | Aug 22, 2023 |
| Dell          | 0KHP4K A03                  | [dd1ad7af32](https://bsd-hardware.info/?probe=dd1ad7af32) | Aug 22, 2023 |
| Protectli     | VP2420                      | [c033157bb2](https://bsd-hardware.info/?probe=c033157bb2) | Aug 22, 2023 |
| Lenovo        | ThinkCentre M90p 3853RN9    | [818c1b5f31](https://bsd-hardware.info/?probe=818c1b5f31) | Aug 20, 2023 |
| Dell          | 04Y8V0 A02                  | [8f26de2199](https://bsd-hardware.info/?probe=8f26de2199) | Aug 19, 2023 |
| Dell          | 0NC2VH A01                  | [7ea90d38d1](https://bsd-hardware.info/?probe=7ea90d38d1) | Aug 18, 2023 |
| ASRock        | B450 Pro4                   | [c12a76c083](https://bsd-hardware.info/?probe=c12a76c083) | Aug 16, 2023 |
| ASUSTek       | P8Z68-V LE                  | [08061905f7](https://bsd-hardware.info/?probe=08061905f7) | Aug 15, 2023 |
| Dell          | 00VTMF A01                  | [399fe2224c](https://bsd-hardware.info/?probe=399fe2224c) | Aug 13, 2023 |
| Dell          | 0NC2VH A01                  | [0fd996a147](https://bsd-hardware.info/?probe=0fd996a147) | Aug 10, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [a22e406f7c](https://bsd-hardware.info/?probe=a22e406f7c) | Aug 10, 2023 |
| Dell          | 04Y8V0 A02                  | [c693116826](https://bsd-hardware.info/?probe=c693116826) | Aug 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [0c9251a971](https://bsd-hardware.info/?probe=0c9251a971) | Aug 09, 2023 |
| ASUSTek       | M4A88TD-M/USB3              | [ce95634a53](https://bsd-hardware.info/?probe=ce95634a53) | Aug 06, 2023 |
| Protectli     | VP2420                      | [2ec2033d58](https://bsd-hardware.info/?probe=2ec2033d58) | Aug 01, 2023 |
| HP            | 2AF7                        | [fc495dc6c7](https://bsd-hardware.info/?probe=fc495dc6c7) | Jul 29, 2023 |
| AZW           | U59                         | [1862cfda96](https://bsd-hardware.info/?probe=1862cfda96) | Jul 23, 2023 |
| Dell          | 0F3KHR A02                  | [8c9dfc9396](https://bsd-hardware.info/?probe=8c9dfc9396) | Jul 23, 2023 |
| AZW           | EQ                          | [b96b847399](https://bsd-hardware.info/?probe=b96b847399) | Jul 20, 2023 |
| Techvision    | TVI7309X B0                 | [3e853472dc](https://bsd-hardware.info/?probe=3e853472dc) | Jul 19, 2023 |
| Dell          | 04Y8V0 A02                  | [738b473ab6](https://bsd-hardware.info/?probe=738b473ab6) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [f58fdceed1](https://bsd-hardware.info/?probe=f58fdceed1) | Jul 18, 2023 |
| Unknown       | Unknown                     | [cfdbed124e](https://bsd-hardware.info/?probe=cfdbed124e) | Jul 17, 2023 |
| Dell          | 0F3KHR A02                  | [e1647604a7](https://bsd-hardware.info/?probe=e1647604a7) | Jul 15, 2023 |
| ASUSTek       | Rampage III Extreme         | [499e5b7941](https://bsd-hardware.info/?probe=499e5b7941) | Jul 14, 2023 |
| HP            | 2AF7                        | [a983dd41d6](https://bsd-hardware.info/?probe=a983dd41d6) | Jul 13, 2023 |
| Techvision    | TVI7309X B0                 | [6db56ee0ef](https://bsd-hardware.info/?probe=6db56ee0ef) | Jul 13, 2023 |
| AZW           | U59                         | [20a3b64ecd](https://bsd-hardware.info/?probe=20a3b64ecd) | Jul 10, 2023 |
| MW            | GMLK-2_5G4L                 | [bbef95a882](https://bsd-hardware.info/?probe=bbef95a882) | Jul 08, 2023 |
| Intel         | CRESCENTBAY                 | [933187d501](https://bsd-hardware.info/?probe=933187d501) | Jul 08, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [76cfc2c80e](https://bsd-hardware.info/?probe=76cfc2c80e) | Jul 07, 2023 |
| Intel         | DQ67SW AAG12527-310         | [e36e748937](https://bsd-hardware.info/?probe=e36e748937) | Jul 06, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [9d6fef9445](https://bsd-hardware.info/?probe=9d6fef9445) | Jul 04, 2023 |
| MW            | GMLK-2_5G4L                 | [1ef9818928](https://bsd-hardware.info/?probe=1ef9818928) | Jun 27, 2023 |
| HP            | 1495                        | [564ff2ef77](https://bsd-hardware.info/?probe=564ff2ef77) | Jun 26, 2023 |
| Lenovo        | ThinkCentre M55 880894U     | [e406083f25](https://bsd-hardware.info/?probe=e406083f25) | Jun 22, 2023 |
| Techvision    | TVI7309X B0                 | [0b667bc4e7](https://bsd-hardware.info/?probe=0b667bc4e7) | Jun 22, 2023 |
| ASUSTek       | M5A97 PLUS                  | [39e7195baf](https://bsd-hardware.info/?probe=39e7195baf) | Jun 15, 2023 |
| Protectli     | FW4B Ver                    | [3484cbbf9f](https://bsd-hardware.info/?probe=3484cbbf9f) | Jun 14, 2023 |
| Techvision    | TVI7309X B0                 | [080be9d6f5](https://bsd-hardware.info/?probe=080be9d6f5) | Jun 13, 2023 |
| Unknown       | Unknown                     | [88a421e275](https://bsd-hardware.info/?probe=88a421e275) | Jun 10, 2023 |
| ASUSTek       | P8Z68-V LE                  | [48833ba1a3](https://bsd-hardware.info/?probe=48833ba1a3) | Jun 08, 2023 |
| Protectli     | VP2420                      | [45e550e09f](https://bsd-hardware.info/?probe=45e550e09f) | Jun 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | [f0f13f5cea](https://bsd-hardware.info/?probe=f0f13f5cea) | Jun 06, 2023 |
| HP            | 1495                        | [a7a24624d7](https://bsd-hardware.info/?probe=a7a24624d7) | Jun 05, 2023 |
| Protectli     | FW4B Ver                    | [5fc38b17d3](https://bsd-hardware.info/?probe=5fc38b17d3) | Jun 04, 2023 |
| Techvision    | TVI7309X B0                 | [5be94420c2](https://bsd-hardware.info/?probe=5be94420c2) | Jun 02, 2023 |
| Techvision    | TVI7309X B0                 | [ed0c6cf73c](https://bsd-hardware.info/?probe=ed0c6cf73c) | May 31, 2023 |
| Unknown       | Unknown                     | [88e6cd10c6](https://bsd-hardware.info/?probe=88e6cd10c6) | May 27, 2023 |
| Protectli     | FW4B                        | [c5c9276f48](https://bsd-hardware.info/?probe=c5c9276f48) | May 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | [e782ceaea8](https://bsd-hardware.info/?probe=e782ceaea8) | May 19, 2023 |
| MSI           | B450I GAMING PLUS AC        | [cc4c36977f](https://bsd-hardware.info/?probe=cc4c36977f) | May 18, 2023 |
| MSI           | B450I GAMING PLUS AC        | [432b2a27c3](https://bsd-hardware.info/?probe=432b2a27c3) | May 13, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [dcea67b6a6](https://bsd-hardware.info/?probe=dcea67b6a6) | May 08, 2023 |
| Lenovo        | ThinkCentre M58 7360EUU     | [b0c462fbd5](https://bsd-hardware.info/?probe=b0c462fbd5) | May 02, 2023 |
| Unknown       | Unknown                     | [73f9fac4f8](https://bsd-hardware.info/?probe=73f9fac4f8) | May 01, 2023 |
| iBASE         | Mi956                       | [e2c1e52a68](https://bsd-hardware.info/?probe=e2c1e52a68) | Apr 29, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [8acf41eb6b](https://bsd-hardware.info/?probe=8acf41eb6b) | Apr 28, 2023 |
| iBASE         | Mi956                       | [cb08976732](https://bsd-hardware.info/?probe=cb08976732) | Apr 27, 2023 |
| Intel         | CRESCENTBAY                 | [b32c8cbec8](https://bsd-hardware.info/?probe=b32c8cbec8) | Apr 27, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [8476daf227](https://bsd-hardware.info/?probe=8476daf227) | Apr 27, 2023 |
| Techvision    | TVI7309X B0                 | [dcacaf8c50](https://bsd-hardware.info/?probe=dcacaf8c50) | Apr 26, 2023 |
| HP            | 1998                        | [41b5bbe52c](https://bsd-hardware.info/?probe=41b5bbe52c) | Apr 26, 2023 |
| Protectli     | FW4B                        | [111e2f7b3b](https://bsd-hardware.info/?probe=111e2f7b3b) | Apr 25, 2023 |
| Unknown       | Unknown                     | [389267d68d](https://bsd-hardware.info/?probe=389267d68d) | Apr 24, 2023 |
| Lenovo        | ThinkCentre M57p 6073ATU    | [b1e7583e6b](https://bsd-hardware.info/?probe=b1e7583e6b) | Apr 24, 2023 |
| Dell          | 04Y8V0 A02                  | [24379ebf10](https://bsd-hardware.info/?probe=24379ebf10) | Apr 20, 2023 |
| Dell          | 09KPNV A01                  | [cf533da9bf](https://bsd-hardware.info/?probe=cf533da9bf) | Apr 16, 2023 |
| Pegatron      | 2A72h                       | [142340aed4](https://bsd-hardware.info/?probe=142340aed4) | Apr 15, 2023 |
| iBASE         | Mi956                       | [0d4d63b29b](https://bsd-hardware.info/?probe=0d4d63b29b) | Apr 14, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [8e77aee0e0](https://bsd-hardware.info/?probe=8e77aee0e0) | Apr 14, 2023 |
| Protectli     | FW4B Ver                    | [d2f19cb660](https://bsd-hardware.info/?probe=d2f19cb660) | Apr 13, 2023 |
| HP            | 3397                        | [cf2d152bee](https://bsd-hardware.info/?probe=cf2d152bee) | Apr 13, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [e6c9c37b02](https://bsd-hardware.info/?probe=e6c9c37b02) | Apr 13, 2023 |
| AMI           | Cherry Trail CR             | [ce3072c27a](https://bsd-hardware.info/?probe=ce3072c27a) | Apr 05, 2023 |
| ASUSTek       | M5A97 PLUS                  | [9418e51f7e](https://bsd-hardware.info/?probe=9418e51f7e) | Apr 03, 2023 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [3bb60897ff](https://bsd-hardware.info/?probe=3bb60897ff) | Apr 01, 2023 |
| Alienware     | 049PDM A00                  | [139d115cdb](https://bsd-hardware.info/?probe=139d115cdb) | Mar 29, 2023 |
| Lenovo        | ThinkCentre M58 7360EUU     | [b86ffef220](https://bsd-hardware.info/?probe=b86ffef220) | Mar 28, 2023 |
| Acer          | WG43M                       | [c8f2a03a08](https://bsd-hardware.info/?probe=c8f2a03a08) | Mar 27, 2023 |
| Acer          | WG43M                       | [5e154dc7cf](https://bsd-hardware.info/?probe=5e154dc7cf) | Mar 26, 2023 |
| MSI           | PRO B660-A DDR4             | [735a5cc6a2](https://bsd-hardware.info/?probe=735a5cc6a2) | Mar 26, 2023 |
| HP            | 1497                        | [08daaf3be1](https://bsd-hardware.info/?probe=08daaf3be1) | Mar 25, 2023 |
| HP            | 21B4 A01                    | [8de4b8231a](https://bsd-hardware.info/?probe=8de4b8231a) | Mar 25, 2023 |
| HP            | 1497                        | [fc6a7ebc91](https://bsd-hardware.info/?probe=fc6a7ebc91) | Mar 25, 2023 |
| HP            | 1497                        | [e98b5284d9](https://bsd-hardware.info/?probe=e98b5284d9) | Mar 25, 2023 |
| Unknown       | Unknown                     | [55c708e91a](https://bsd-hardware.info/?probe=55c708e91a) | Mar 24, 2023 |
| HP            | 1632                        | [8f3bb99bb4](https://bsd-hardware.info/?probe=8f3bb99bb4) | Mar 17, 2023 |
| Lenovo        | ThinkCentre M58p 6138DK1    | [293de8b0fd](https://bsd-hardware.info/?probe=293de8b0fd) | Mar 14, 2023 |
| Unknown       | Unknown                     | [898095b140](https://bsd-hardware.info/?probe=898095b140) | Mar 09, 2023 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [6a15f7d4a1](https://bsd-hardware.info/?probe=6a15f7d4a1) | Mar 09, 2023 |
| Arctic Wol... | AWN101                      | [e0f187e449](https://bsd-hardware.info/?probe=e0f187e449) | Mar 01, 2023 |
| Dell          | 0D24M8 A01                  | [22a1b812f8](https://bsd-hardware.info/?probe=22a1b812f8) | Mar 01, 2023 |
| Lenovo        | 3098 0B98401 PRO            | [40d63fc1f7](https://bsd-hardware.info/?probe=40d63fc1f7) | Feb 27, 2023 |
| Dell          | 01TKCC A01                  | [42da900d88](https://bsd-hardware.info/?probe=42da900d88) | Feb 26, 2023 |
| Lenovo        | 30D9 No DPK                 | [c3864d9d51](https://bsd-hardware.info/?probe=c3864d9d51) | Feb 26, 2023 |
| AZW           | U59                         | [a4e906c608](https://bsd-hardware.info/?probe=a4e906c608) | Feb 26, 2023 |
| Unknown       | Unknown                     | [d690aee80e](https://bsd-hardware.info/?probe=d690aee80e) | Feb 26, 2023 |
| AZW           | U59                         | [4dad05a05a](https://bsd-hardware.info/?probe=4dad05a05a) | Feb 24, 2023 |
| AZW           | U59                         | [638aa3ff8e](https://bsd-hardware.info/?probe=638aa3ff8e) | Feb 24, 2023 |
| Dell          | 0HHV7N A00                  | [50f39ca7e0](https://bsd-hardware.info/?probe=50f39ca7e0) | Feb 20, 2023 |
| Apple         | PowerMac3,6                 | [f31181f95c](https://bsd-hardware.info/?probe=f31181f95c) | Feb 20, 2023 |
| Dell          | 0HHV7N A00                  | [fd90fc5154](https://bsd-hardware.info/?probe=fd90fc5154) | Feb 18, 2023 |
| ASUSTek       | PRIME H310M-C R2.0          | [9761fb446b](https://bsd-hardware.info/?probe=9761fb446b) | Feb 18, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [f3c3e6ecb5](https://bsd-hardware.info/?probe=f3c3e6ecb5) | Feb 16, 2023 |
| MiTAC         | UltraPoint                  | [00e52df710](https://bsd-hardware.info/?probe=00e52df710) | Feb 15, 2023 |
| HP            | 212B                        | [0e13beb9f6](https://bsd-hardware.info/?probe=0e13beb9f6) | Feb 12, 2023 |
| Dell          | 0F3KHR A02                  | [f69bff2d41](https://bsd-hardware.info/?probe=f69bff2d41) | Feb 12, 2023 |
| Dell          | 0F3KHR A02                  | [c9c53f2141](https://bsd-hardware.info/?probe=c9c53f2141) | Feb 12, 2023 |
| iBASE         | Mi956                       | [86d20c1bc0](https://bsd-hardware.info/?probe=86d20c1bc0) | Feb 10, 2023 |
| Unknown       | Unknown                     | [3f0d4c3ced](https://bsd-hardware.info/?probe=3f0d4c3ced) | Feb 10, 2023 |
| ASUSTek       | PRIME B450M-A II            | [0587338e57](https://bsd-hardware.info/?probe=0587338e57) | Feb 08, 2023 |
| Dell          | 0F3KHR A02                  | [98c9324352](https://bsd-hardware.info/?probe=98c9324352) | Feb 05, 2023 |
| Supermicro    | X9SCL/X9SCM                 | [1022faa668](https://bsd-hardware.info/?probe=1022faa668) | Feb 01, 2023 |
| Dell          | 0J3C2F A01                  | [93a87b6106](https://bsd-hardware.info/?probe=93a87b6106) | Jan 30, 2023 |
| Unknown       | Unknown                     | [b8efd7453b](https://bsd-hardware.info/?probe=b8efd7453b) | Jan 29, 2023 |
| ASUSTek       | M5A97 PLUS                  | [e00d33f978](https://bsd-hardware.info/?probe=e00d33f978) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [87e25e2abd](https://bsd-hardware.info/?probe=87e25e2abd) | Jan 26, 2023 |
| Unknown       | Unknown                     | [cde064f460](https://bsd-hardware.info/?probe=cde064f460) | Jan 26, 2023 |
| Techvision    | TVI7309X B0                 | [76840aba40](https://bsd-hardware.info/?probe=76840aba40) | Jan 22, 2023 |
| Unknown       | Unknown                     | [14089c4ab4](https://bsd-hardware.info/?probe=14089c4ab4) | Jan 21, 2023 |
| Dell          | 02YYK5 A01                  | [b0fe0783d5](https://bsd-hardware.info/?probe=b0fe0783d5) | Jan 21, 2023 |
| Unknown       | Unknown                     | [32ebc1c99d](https://bsd-hardware.info/?probe=32ebc1c99d) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [c3281eb186](https://bsd-hardware.info/?probe=c3281eb186) | Jan 18, 2023 |
| HP            | 83F2                        | [a7230c1af5](https://bsd-hardware.info/?probe=a7230c1af5) | Jan 18, 2023 |
| Unknown       | Unknown                     | [0049fd4cfc](https://bsd-hardware.info/?probe=0049fd4cfc) | Jan 17, 2023 |
| HP            | 83F2                        | [912de3c81d](https://bsd-hardware.info/?probe=912de3c81d) | Jan 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | [23d2c64af3](https://bsd-hardware.info/?probe=23d2c64af3) | Jan 16, 2023 |
| Unknown       | Unknown                     | [429659b071](https://bsd-hardware.info/?probe=429659b071) | Jan 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [7ba28d1e6b](https://bsd-hardware.info/?probe=7ba28d1e6b) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [917972b6ae](https://bsd-hardware.info/?probe=917972b6ae) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [bd60eadfc4](https://bsd-hardware.info/?probe=bd60eadfc4) | Jan 12, 2023 |
| Unknown       | Unknown                     | [a21b21b82f](https://bsd-hardware.info/?probe=a21b21b82f) | Jan 12, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [2372c973c8](https://bsd-hardware.info/?probe=2372c973c8) | Jan 11, 2023 |
| Unknown       | Unknown                     | [b19ed4597a](https://bsd-hardware.info/?probe=b19ed4597a) | Jan 07, 2023 |
| Unknown       | Unknown                     | [6347de602a](https://bsd-hardware.info/?probe=6347de602a) | Jan 07, 2023 |
| Unknown       | Unknown                     | [4e8b83804d](https://bsd-hardware.info/?probe=4e8b83804d) | Jan 06, 2023 |
| MSI           | MEG Z690 UNIFY-X            | [e70cd80d11](https://bsd-hardware.info/?probe=e70cd80d11) | Jan 05, 2023 |
| Protectli     | VP2410 10                   | [81c02d080f](https://bsd-hardware.info/?probe=81c02d080f) | Jan 05, 2023 |
| Dell          | 02YYK5 A01                  | [219200b0b6](https://bsd-hardware.info/?probe=219200b0b6) | Jan 05, 2023 |
| Techvision    | TVI7309X B0                 | [4730790da9](https://bsd-hardware.info/?probe=4730790da9) | Jan 04, 2023 |
| Unknown       | Unknown                     | [3d2465f9f9](https://bsd-hardware.info/?probe=3d2465f9f9) | Jan 03, 2023 |
| Techvision    | TVI7309X B0                 | [9dd29daa88](https://bsd-hardware.info/?probe=9dd29daa88) | Jan 02, 2023 |
| Dell          | 0WR7PY A03                  | [b6ec2e7e28](https://bsd-hardware.info/?probe=b6ec2e7e28) | Dec 31, 2022 |
| Dell          | 02YYK5 A01                  | [910c2bba4a](https://bsd-hardware.info/?probe=910c2bba4a) | Dec 31, 2022 |
| Gigabyte      | MBHM87P-00                  | [5d287163c9](https://bsd-hardware.info/?probe=5d287163c9) | Dec 29, 2022 |
| HP            | 1998                        | [afc7de60e3](https://bsd-hardware.info/?probe=afc7de60e3) | Dec 28, 2022 |
| ASRock        | N3710-NUC IPC               | [80c809e992](https://bsd-hardware.info/?probe=80c809e992) | Dec 24, 2022 |
| Protectli     | FW4B Ver                    | [cde7bad6c3](https://bsd-hardware.info/?probe=cde7bad6c3) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | [b8c89bdca8](https://bsd-hardware.info/?probe=b8c89bdca8) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | [b0d1792185](https://bsd-hardware.info/?probe=b0d1792185) | Dec 21, 2022 |
| Dell          | 09KPNV A01                  | [0eea35e069](https://bsd-hardware.info/?probe=0eea35e069) | Dec 19, 2022 |
| Unknown       | Unknown                     | [f876d5d5b1](https://bsd-hardware.info/?probe=f876d5d5b1) | Dec 19, 2022 |
| Unknown       | Unknown                     | [3d77f833b0](https://bsd-hardware.info/?probe=3d77f833b0) | Dec 19, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [1f1de1d49c](https://bsd-hardware.info/?probe=1f1de1d49c) | Dec 18, 2022 |
| PC Engines    | APU                         | [19786edc61](https://bsd-hardware.info/?probe=19786edc61) | Dec 17, 2022 |
| ASUSTek       | PRIME B450M-A II            | [d9376f2f63](https://bsd-hardware.info/?probe=d9376f2f63) | Dec 16, 2022 |
| HP            | 1495                        | [04bd0455f2](https://bsd-hardware.info/?probe=04bd0455f2) | Dec 14, 2022 |
| HP            | 1495                        | [23f8aeada7](https://bsd-hardware.info/?probe=23f8aeada7) | Dec 14, 2022 |
| HP            | 1495                        | [3eab39d89f](https://bsd-hardware.info/?probe=3eab39d89f) | Dec 09, 2022 |
| HP            | 3397                        | [bc9e5c3ab7](https://bsd-hardware.info/?probe=bc9e5c3ab7) | Dec 09, 2022 |
| Pegatron      | 2A72h                       | [87e76fd095](https://bsd-hardware.info/?probe=87e76fd095) | Dec 09, 2022 |
| Protectli     | FW4B Ver                    | [27dea9bcb5](https://bsd-hardware.info/?probe=27dea9bcb5) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [15b2363325](https://bsd-hardware.info/?probe=15b2363325) | Dec 05, 2022 |
| Acer          | Aspire XC-105               | [250b12c3f2](https://bsd-hardware.info/?probe=250b12c3f2) | Dec 05, 2022 |
| Protectli     | FW4B Ver                    | [cfaeaeb2f2](https://bsd-hardware.info/?probe=cfaeaeb2f2) | Nov 29, 2022 |
| Protectli     | FW4B Ver                    | [e8e158f783](https://bsd-hardware.info/?probe=e8e158f783) | Nov 27, 2022 |
| Unknown       | Unknown                     | [512a05eefb](https://bsd-hardware.info/?probe=512a05eefb) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [5f0b8df8d0](https://bsd-hardware.info/?probe=5f0b8df8d0) | Nov 27, 2022 |
| Unknown       | Unknown                     | [222e69ff59](https://bsd-hardware.info/?probe=222e69ff59) | Nov 26, 2022 |
| Protectli     | FW6                         | [74510f3177](https://bsd-hardware.info/?probe=74510f3177) | Nov 25, 2022 |
| HP            | 8055                        | [ace4570d15](https://bsd-hardware.info/?probe=ace4570d15) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | [7258992b77](https://bsd-hardware.info/?probe=7258992b77) | Nov 24, 2022 |
| ASUSTek       | M5A97 PLUS                  | [7c7a121711](https://bsd-hardware.info/?probe=7c7a121711) | Nov 18, 2022 |
| Intel         | SHARKBAY                    | [5875ecec9f](https://bsd-hardware.info/?probe=5875ecec9f) | Nov 18, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [0d37f1878b](https://bsd-hardware.info/?probe=0d37f1878b) | Nov 17, 2022 |
| AZW           | U59                         | [25e1349c5f](https://bsd-hardware.info/?probe=25e1349c5f) | Nov 17, 2022 |
| Lenovo        | 30D9 No DPK                 | [bb9cf416c4](https://bsd-hardware.info/?probe=bb9cf416c4) | Nov 11, 2022 |
| ASUSTek       | P8H77-I                     | [04ea3cc97d](https://bsd-hardware.info/?probe=04ea3cc97d) | Nov 09, 2022 |
| Dell          | 09KPNV A01                  | [32331d772c](https://bsd-hardware.info/?probe=32331d772c) | Nov 08, 2022 |
| Datto         | SSD                         | [235483110d](https://bsd-hardware.info/?probe=235483110d) | Nov 05, 2022 |
| Cisco         | ASA5512 A0                  | [871a5c449f](https://bsd-hardware.info/?probe=871a5c449f) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | [5758027775](https://bsd-hardware.info/?probe=5758027775) | Oct 31, 2022 |
| Protectli     | FW4B Ver                    | [6dda683e10](https://bsd-hardware.info/?probe=6dda683e10) | Oct 28, 2022 |
| HP            | 18E4                        | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [c3f0ae254e](https://bsd-hardware.info/?probe=c3f0ae254e) | Oct 17, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [b4e02e3f51](https://bsd-hardware.info/?probe=b4e02e3f51) | Oct 16, 2022 |
| Unknown       | Unknown                     | [00b5fa7a4e](https://bsd-hardware.info/?probe=00b5fa7a4e) | Oct 13, 2022 |
| ASRock        | B450M Pro4-F                | [edead8a3ae](https://bsd-hardware.info/?probe=edead8a3ae) | Oct 11, 2022 |
| Dell          | 04YP6J A01                  | [ce728798a1](https://bsd-hardware.info/?probe=ce728798a1) | Oct 07, 2022 |
| ASUSTek       | P8B75-M                     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| Unknown       | Unknown                     | [79060c241b](https://bsd-hardware.info/?probe=79060c241b) | Oct 03, 2022 |
| Techvision    | TVI7309X B0                 | [33b252016c](https://bsd-hardware.info/?probe=33b252016c) | Sep 26, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [a1a2cbc6c9](https://bsd-hardware.info/?probe=a1a2cbc6c9) | Sep 20, 2022 |
| CncTion       | N5105-4L B0                 | [22f23ccfa5](https://bsd-hardware.info/?probe=22f23ccfa5) | Sep 17, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [21e7190ff2](https://bsd-hardware.info/?probe=21e7190ff2) | Sep 11, 2022 |
| ASUSTek       | M5A97 PLUS                  | [3c152ae7bd](https://bsd-hardware.info/?probe=3c152ae7bd) | Sep 11, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [89b185547b](https://bsd-hardware.info/?probe=89b185547b) | Sep 10, 2022 |
| Intel         | MAHOBAY                     | [a854e50942](https://bsd-hardware.info/?probe=a854e50942) | Sep 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [860518eb18](https://bsd-hardware.info/?probe=860518eb18) | Sep 04, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [b53e1d28cd](https://bsd-hardware.info/?probe=b53e1d28cd) | Sep 04, 2022 |
| Intel         | DQ67EP AAG12529-307         | [1fb1fd6705](https://bsd-hardware.info/?probe=1fb1fd6705) | Sep 03, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [2e4b87acd2](https://bsd-hardware.info/?probe=2e4b87acd2) | Sep 03, 2022 |
| Protectli     | FW4B Ver                    | [b3a1456bb4](https://bsd-hardware.info/?probe=b3a1456bb4) | Aug 29, 2022 |
| Gigabyte      | MBHM87P-00                  | [9fa5160871](https://bsd-hardware.info/?probe=9fa5160871) | Aug 22, 2022 |
| Dell          | 04Y8V0 A02                  | [9fc4b3c63e](https://bsd-hardware.info/?probe=9fc4b3c63e) | Aug 17, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [753f277d5c](https://bsd-hardware.info/?probe=753f277d5c) | Aug 16, 2022 |
| AZW           | Green G1                    | [4bccb24702](https://bsd-hardware.info/?probe=4bccb24702) | Aug 15, 2022 |
| Dell          | 04Y8V0 A02                  | [a21172360d](https://bsd-hardware.info/?probe=a21172360d) | Aug 15, 2022 |
| Dell          | 04Y8V0 A02                  | [6acccc63ff](https://bsd-hardware.info/?probe=6acccc63ff) | Aug 15, 2022 |
| Lenovo        | 3111 SDK0J40705 WIN 3425... | [6927813b1d](https://bsd-hardware.info/?probe=6927813b1d) | Aug 13, 2022 |
| Lenovo        | SDK0E50510 WIN              | [a45977c76b](https://bsd-hardware.info/?probe=a45977c76b) | Aug 10, 2022 |
| Dell          | 09KPNV A01                  | [236cd1ee65](https://bsd-hardware.info/?probe=236cd1ee65) | Aug 08, 2022 |
| Biostar       | TA880GU3+                   | [8b0c8541b3](https://bsd-hardware.info/?probe=8b0c8541b3) | Aug 06, 2022 |
| MSI           | 785GT-E63                   | [8c307fb033](https://bsd-hardware.info/?probe=8c307fb033) | Aug 03, 2022 |
| Dell          | 0XHGV1 A00                  | [860b06cb6b](https://bsd-hardware.info/?probe=860b06cb6b) | Aug 01, 2022 |
| HP            | 8055                        | [6a8a361dae](https://bsd-hardware.info/?probe=6a8a361dae) | Jul 31, 2022 |
| Dell          | 0TTDMJ A00                  | [900c62c2ba](https://bsd-hardware.info/?probe=900c62c2ba) | Jul 30, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [27b986a422](https://bsd-hardware.info/?probe=27b986a422) | Jul 30, 2022 |
| HP            | 8055                        | [41d802a80a](https://bsd-hardware.info/?probe=41d802a80a) | Jul 29, 2022 |
| ASUSTek       | M5A97 PLUS                  | [7be6ba0021](https://bsd-hardware.info/?probe=7be6ba0021) | Jul 29, 2022 |
| HP            | 18E9                        | [56460b095e](https://bsd-hardware.info/?probe=56460b095e) | Jul 27, 2022 |
| Lenovo        | SHARKBAY NOK                | [1ed99ad502](https://bsd-hardware.info/?probe=1ed99ad502) | Jul 20, 2022 |
| Dell          | 0WR7PY A03                  | [46a6f4e8f3](https://bsd-hardware.info/?probe=46a6f4e8f3) | Jul 19, 2022 |
| Lenovo        | ThinkCentre M91 4518E4U     | [8dd1034cfa](https://bsd-hardware.info/?probe=8dd1034cfa) | Jul 16, 2022 |
| AZW           | Green G1                    | [9a2120ae5a](https://bsd-hardware.info/?probe=9a2120ae5a) | Jul 14, 2022 |
| Datto         | SSD                         | [639d28d449](https://bsd-hardware.info/?probe=639d28d449) | Jul 08, 2022 |
| Protectli     | FW6                         | [e82838534b](https://bsd-hardware.info/?probe=e82838534b) | Jul 06, 2022 |
| Protectli     | FW6 Ver                     | [ac861b1ee3](https://bsd-hardware.info/?probe=ac861b1ee3) | Jun 25, 2022 |
| Protectli     | FW6 Ver                     | [598ecb5457](https://bsd-hardware.info/?probe=598ecb5457) | Jun 25, 2022 |
| HP            | 82A2                        | [77c244bd43](https://bsd-hardware.info/?probe=77c244bd43) | Jun 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a57a2f609c](https://bsd-hardware.info/?probe=a57a2f609c) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [1febab0774](https://bsd-hardware.info/?probe=1febab0774) | Jun 12, 2022 |
| HP            | 1998                        | [1bb67075dd](https://bsd-hardware.info/?probe=1bb67075dd) | Jun 12, 2022 |
| Apple         | Mac-F221BEC8                | [5054729300](https://bsd-hardware.info/?probe=5054729300) | Jun 11, 2022 |
| HP            | 1998                        | [54a6daf0a6](https://bsd-hardware.info/?probe=54a6daf0a6) | Jun 11, 2022 |
| Acer          | EM61SM/EM61PM               | [3b8d6cb36e](https://bsd-hardware.info/?probe=3b8d6cb36e) | Jun 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [26cd129290](https://bsd-hardware.info/?probe=26cd129290) | Jun 06, 2022 |
| Dell          | 0HHV7N A00                  | [f3c197bdfb](https://bsd-hardware.info/?probe=f3c197bdfb) | Jun 04, 2022 |
| ASUSTek       | M5A97 PLUS                  | [8e8ef96421](https://bsd-hardware.info/?probe=8e8ef96421) | Jun 04, 2022 |
| Dell          | 02YYK5 A01                  | [dce99bec81](https://bsd-hardware.info/?probe=dce99bec81) | Jun 03, 2022 |
| ASUSTek       | M5A97 PLUS                  | [8ca71ddf4d](https://bsd-hardware.info/?probe=8ca71ddf4d) | Jun 02, 2022 |
| ASUSTek       | M5A97 PLUS                  | [9d5edd9fa9](https://bsd-hardware.info/?probe=9d5edd9fa9) | May 29, 2022 |
| Dell          | 0M3F6C A01                  | [21d45bc75d](https://bsd-hardware.info/?probe=21d45bc75d) | May 23, 2022 |
| ASUSTek       | PRIME B250M-C               | [c956536edd](https://bsd-hardware.info/?probe=c956536edd) | May 23, 2022 |
| Dell          | 0HHV7N A00                  | [6d7475e9c9](https://bsd-hardware.info/?probe=6d7475e9c9) | May 22, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [963fa158b5](https://bsd-hardware.info/?probe=963fa158b5) | May 22, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [1014f7f61c](https://bsd-hardware.info/?probe=1014f7f61c) | May 18, 2022 |
| Dell          | 0DXJD9 A01                  | [be13c9069c](https://bsd-hardware.info/?probe=be13c9069c) | May 18, 2022 |
| ASUSTek       | PRIME B250M-C               | [9ec22ea24c](https://bsd-hardware.info/?probe=9ec22ea24c) | May 17, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [30cfcd5004](https://bsd-hardware.info/?probe=30cfcd5004) | May 15, 2022 |
| Protectli     | FW4B Ver                    | [9af60bd6e4](https://bsd-hardware.info/?probe=9af60bd6e4) | May 14, 2022 |
| ASUSTek       | M5A97 PLUS                  | [fd066b2db9](https://bsd-hardware.info/?probe=fd066b2db9) | May 14, 2022 |
| Unknown       | Unknown                     | [0958a64385](https://bsd-hardware.info/?probe=0958a64385) | May 12, 2022 |
| Unknown       | Unknown                     | [0d62d4e3cd](https://bsd-hardware.info/?probe=0d62d4e3cd) | May 09, 2022 |
| Gigabyte      | F2A68HM-H                   | [daed3f9401](https://bsd-hardware.info/?probe=daed3f9401) | May 06, 2022 |
| ASUSTek       | H81M-E                      | [cf2f288b93](https://bsd-hardware.info/?probe=cf2f288b93) | May 04, 2022 |
| HP            | 1495                        | [6e0f1cc72e](https://bsd-hardware.info/?probe=6e0f1cc72e) | Apr 29, 2022 |
| HP            | 1998                        | [1244e0583b](https://bsd-hardware.info/?probe=1244e0583b) | Apr 27, 2022 |
| Unknown       | Unknown                     | [b3d5defed1](https://bsd-hardware.info/?probe=b3d5defed1) | Apr 26, 2022 |
| Unknown       | Unknown                     | [4166c67369](https://bsd-hardware.info/?probe=4166c67369) | Apr 20, 2022 |
| Dell          | G5 5090                     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| Unknown       | Unknown                     | [979e868c51](https://bsd-hardware.info/?probe=979e868c51) | Apr 16, 2022 |
| Dell          | 0DXJD9 A01                  | [4023d86091](https://bsd-hardware.info/?probe=4023d86091) | Apr 15, 2022 |
| ASRock        | J3455B-ITX                  | [29be552d6a](https://bsd-hardware.info/?probe=29be552d6a) | Apr 15, 2022 |
| Unknown       | Unknown                     | [1173feae11](https://bsd-hardware.info/?probe=1173feae11) | Apr 13, 2022 |
| Alienware     | 049PDM A00                  | [6dac56f3bb](https://bsd-hardware.info/?probe=6dac56f3bb) | Apr 11, 2022 |
| Dell          | 0WR7PY A03                  | [641d1574ce](https://bsd-hardware.info/?probe=641d1574ce) | Apr 11, 2022 |
| PC Engines    | APU                         | [e266947055](https://bsd-hardware.info/?probe=e266947055) | Mar 29, 2022 |
| Unknown       | Unknown                     | [ef1a743845](https://bsd-hardware.info/?probe=ef1a743845) | Mar 28, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [1176fca4ab](https://bsd-hardware.info/?probe=1176fca4ab) | Mar 27, 2022 |
| Unknown       | Unknown                     | [d0e7b62eda](https://bsd-hardware.info/?probe=d0e7b62eda) | Mar 25, 2022 |
| Protectli     | FW4B Ver                    | [cf576c571d](https://bsd-hardware.info/?probe=cf576c571d) | Mar 22, 2022 |
| HP            | 213D A01                    | [6baba4f9c1](https://bsd-hardware.info/?probe=6baba4f9c1) | Mar 20, 2022 |
| ASUSTek       | P8Z68-V LE                  | [3727ba82af](https://bsd-hardware.info/?probe=3727ba82af) | Mar 19, 2022 |
| Intel         | SHARKBAY                    | [f22a45488b](https://bsd-hardware.info/?probe=f22a45488b) | Mar 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [a5fd383c40](https://bsd-hardware.info/?probe=a5fd383c40) | Mar 14, 2022 |
| MSI           | MS-7388                     | [ad8209dbdb](https://bsd-hardware.info/?probe=ad8209dbdb) | Mar 05, 2022 |
| MSI           | MS-7388                     | [a59bca8bde](https://bsd-hardware.info/?probe=a59bca8bde) | Mar 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [a6abb45607](https://bsd-hardware.info/?probe=a6abb45607) | Mar 04, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [6b2550968e](https://bsd-hardware.info/?probe=6b2550968e) | Feb 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | [b69015f0e0](https://bsd-hardware.info/?probe=b69015f0e0) | Feb 16, 2022 |
| PC Engines    | apu4                        | [09f27a0f23](https://bsd-hardware.info/?probe=09f27a0f23) | Feb 14, 2022 |
| Protectli     | FW6                         | [d33b2f1244](https://bsd-hardware.info/?probe=d33b2f1244) | Feb 13, 2022 |
| Dell          | 0XHGV1 A00                  | [12ccb8699b](https://bsd-hardware.info/?probe=12ccb8699b) | Feb 08, 2022 |
| Dell          | 0XHGV1 A00                  | [0d3b560aad](https://bsd-hardware.info/?probe=0d3b560aad) | Feb 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [3dabf0503d](https://bsd-hardware.info/?probe=3dabf0503d) | Feb 08, 2022 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [53abdfa3b1](https://bsd-hardware.info/?probe=53abdfa3b1) | Feb 07, 2022 |
| ASUSTek       | PRIME H410M-A               | [1dafdcc71a](https://bsd-hardware.info/?probe=1dafdcc71a) | Feb 05, 2022 |
| ASRock        | J4105M                      | [09b9d104b9](https://bsd-hardware.info/?probe=09b9d104b9) | Feb 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | [07d565ad8c](https://bsd-hardware.info/?probe=07d565ad8c) | Feb 02, 2022 |
| ASRock        | J3455B-ITX                  | [83975bd2b1](https://bsd-hardware.info/?probe=83975bd2b1) | Jan 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | [ff629a490d](https://bsd-hardware.info/?probe=ff629a490d) | Jan 29, 2022 |
| Dell          | 0WMJ54 A01                  | [4b17ef7a18](https://bsd-hardware.info/?probe=4b17ef7a18) | Jan 27, 2022 |
| PC Engines    | APU2                        | [5ea082ddf9](https://bsd-hardware.info/?probe=5ea082ddf9) | Jan 13, 2022 |
| Dell          | 0X4N41 A01                  | [87000234dc](https://bsd-hardware.info/?probe=87000234dc) | Jan 11, 2022 |
| ASUSTek       | P8Z68-M PRO                 | [a0885f4f44](https://bsd-hardware.info/?probe=a0885f4f44) | Jan 10, 2022 |
| Unknown       | Unknown                     | [ded64258b4](https://bsd-hardware.info/?probe=ded64258b4) | Jan 09, 2022 |
| Unknown       | Unknown                     | [8d607c1d19](https://bsd-hardware.info/?probe=8d607c1d19) | Jan 03, 2022 |
| Unknown       | Unknown                     | [c183bdd5af](https://bsd-hardware.info/?probe=c183bdd5af) | Jan 01, 2022 |
| Unknown       | Unknown                     | [4848e4009f](https://bsd-hardware.info/?probe=4848e4009f) | Jan 01, 2022 |
| AMI           | Cherry Trail CR             | [7d47d0db05](https://bsd-hardware.info/?probe=7d47d0db05) | Dec 30, 2021 |
| ASUSTek       | P8B75-M                     | [c3884fac44](https://bsd-hardware.info/?probe=c3884fac44) | Dec 30, 2021 |
| ASUSTek       | Z170-P                      | [bde74629f9](https://bsd-hardware.info/?probe=bde74629f9) | Dec 25, 2021 |
| ASRock        | J3355B-ITX                  | [f4648747b0](https://bsd-hardware.info/?probe=f4648747b0) | Dec 22, 2021 |
| Quanta        | 2AC7 011                    | [1a831a1d34](https://bsd-hardware.info/?probe=1a831a1d34) | Dec 18, 2021 |
| HP            | 843B                        | [f0d279747f](https://bsd-hardware.info/?probe=f0d279747f) | Dec 13, 2021 |
| HP            | 843B                        | [56400d3999](https://bsd-hardware.info/?probe=56400d3999) | Dec 13, 2021 |
| AMI           | Cherry Trail CR             | [624041b5db](https://bsd-hardware.info/?probe=624041b5db) | Dec 09, 2021 |
| Dell          | 051FJ8 A01                  | [ccfb8336a0](https://bsd-hardware.info/?probe=ccfb8336a0) | Dec 01, 2021 |
| HP            | 843B                        | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | [dc9d060c7f](https://bsd-hardware.info/?probe=dc9d060c7f) | Nov 27, 2021 |
| ASUSTek       | M5A97 PLUS                  | [a26bc8f2b3](https://bsd-hardware.info/?probe=a26bc8f2b3) | Nov 14, 2021 |
| Gigabyte      | MRZNVMS-00                  | [817cb3e603](https://bsd-hardware.info/?probe=817cb3e603) | Nov 12, 2021 |
| ASUSTek       | M5A97 PLUS                  | [970387f9d9](https://bsd-hardware.info/?probe=970387f9d9) | Nov 09, 2021 |
| Protectli     | FW6E                        | [ebe5b24dee](https://bsd-hardware.info/?probe=ebe5b24dee) | Nov 08, 2021 |
| Protectli     | FW6E                        | [6c12084410](https://bsd-hardware.info/?probe=6c12084410) | Nov 07, 2021 |
| ASUSTek       | M5A97 PLUS                  | [99b5ab3e42](https://bsd-hardware.info/?probe=99b5ab3e42) | Nov 04, 2021 |
| ASRock        | H370M-ITX/ac                | [bf37ad85e7](https://bsd-hardware.info/?probe=bf37ad85e7) | Nov 03, 2021 |
| Unknown       | Unknown                     | [579cf2ac1a](https://bsd-hardware.info/?probe=579cf2ac1a) | Oct 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7abc8386ec](https://bsd-hardware.info/?probe=7abc8386ec) | Oct 31, 2021 |
| HP            | 843B                        | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [c3d6cddf87](https://bsd-hardware.info/?probe=c3d6cddf87) | Oct 25, 2021 |
| Intel         | CRESCENTBAY                 | [5c8f3708b1](https://bsd-hardware.info/?probe=5c8f3708b1) | Oct 21, 2021 |
| Acer          | Aspire TC-780               | [77101a00b3](https://bsd-hardware.info/?probe=77101a00b3) | Oct 11, 2021 |
| Acer          | Aspire TC-780               | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |
| ASUSTek       | M5A97 PLUS                  | [cc419789f8](https://bsd-hardware.info/?probe=cc419789f8) | Oct 08, 2021 |
| MSI           | B450I GAMING PLUS AC        | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | [00bafc5f7c](https://bsd-hardware.info/?probe=00bafc5f7c) | Oct 03, 2021 |
| ASUSTek       | H81M-E                      | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| HP            | 1495                        | [36a5bc62bf](https://bsd-hardware.info/?probe=36a5bc62bf) | Sep 27, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [01e33c8399](https://bsd-hardware.info/?probe=01e33c8399) | Sep 26, 2021 |
| ASUSTek       | H81M-E                      | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| AMI           | Cherry Trail CR             | [3b709e37c2](https://bsd-hardware.info/?probe=3b709e37c2) | Sep 12, 2021 |
| ASUSTek       | P8H77-I                     | [1feb22dc52](https://bsd-hardware.info/?probe=1feb22dc52) | Sep 12, 2021 |
| HP            | 212B                        | [d3894b9f37](https://bsd-hardware.info/?probe=d3894b9f37) | Sep 10, 2021 |
| ASRock        | H110M-DGS R3.0              | [df08c4e6d3](https://bsd-hardware.info/?probe=df08c4e6d3) | Sep 09, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | [c64c51359c](https://bsd-hardware.info/?probe=c64c51359c) | Sep 09, 2021 |
| Dell          | 09KPNV A01                  | [e960bc2548](https://bsd-hardware.info/?probe=e960bc2548) | Sep 01, 2021 |
| Gigabyte      | H61N-USB3                   | [3dca10264a](https://bsd-hardware.info/?probe=3dca10264a) | Aug 29, 2021 |
| ASRock        | B450M Pro4                  | [70dc185964](https://bsd-hardware.info/?probe=70dc185964) | Aug 25, 2021 |
| HP            | 1589                        | [4d51cc9c4b](https://bsd-hardware.info/?probe=4d51cc9c4b) | Aug 24, 2021 |
| Acer          | Aspire TC-895 V:1.0         | [da3e8986a3](https://bsd-hardware.info/?probe=da3e8986a3) | Aug 22, 2021 |
| AMI           | Cherry Trail CR             | [bd94ad09ef](https://bsd-hardware.info/?probe=bd94ad09ef) | Aug 12, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | [94201b7633](https://bsd-hardware.info/?probe=94201b7633) | Aug 10, 2021 |
| Supermicro    | X11SDV-8C-TP8F              | [6da61be169](https://bsd-hardware.info/?probe=6da61be169) | Aug 08, 2021 |
| Intel         | Q3XXG4-P V1.0               | [535b577563](https://bsd-hardware.info/?probe=535b577563) | Aug 03, 2021 |
| HP            | ProLiant ML150 G6           | [783c2ba254](https://bsd-hardware.info/?probe=783c2ba254) | Aug 02, 2021 |
| Protectli     | FW4B Ver                    | [b434d9bfb8](https://bsd-hardware.info/?probe=b434d9bfb8) | Aug 02, 2021 |
| ASUSTek       | P5QL PRO                    | [4d118404a8](https://bsd-hardware.info/?probe=4d118404a8) | Jul 29, 2021 |
| ASRock        | J3455B-ITX                  | [fc13802cd3](https://bsd-hardware.info/?probe=fc13802cd3) | Jul 19, 2021 |
| Intel         | SHARKBAY                    | [5697d53687](https://bsd-hardware.info/?probe=5697d53687) | Jul 19, 2021 |
| Lenovo        | SHARKBAY 0C48431 PRO        | [0a1fa8924e](https://bsd-hardware.info/?probe=0a1fa8924e) | Jul 17, 2021 |
| ASRock        | J3455B-ITX                  | [b86c2cfc99](https://bsd-hardware.info/?probe=b86c2cfc99) | Jul 16, 2021 |
| PC Engines    | apu4                        | [51163b13ef](https://bsd-hardware.info/?probe=51163b13ef) | Jul 11, 2021 |
| Intel         | SHARKBAY                    | [59a1b5f761](https://bsd-hardware.info/?probe=59a1b5f761) | Jul 10, 2021 |
| Gigabyte      | H97-D3H-CF                  | [a326fd4061](https://bsd-hardware.info/?probe=a326fd4061) | Jun 20, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [ef7104e237](https://bsd-hardware.info/?probe=ef7104e237) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [d2dd261a2a](https://bsd-hardware.info/?probe=d2dd261a2a) | Jun 20, 2021 |
| Intel         | SHARKBAY                    | [6aa5f8046e](https://bsd-hardware.info/?probe=6aa5f8046e) | Jun 19, 2021 |
| Shuttle       | FS110                       | [9b4093c9a1](https://bsd-hardware.info/?probe=9b4093c9a1) | Jun 17, 2021 |
| Intel         | Q3XXG4-P V1.0               | [459bf008e9](https://bsd-hardware.info/?probe=459bf008e9) | Jun 12, 2021 |
| HP            | 805D                        | [dc4e61ecd4](https://bsd-hardware.info/?probe=dc4e61ecd4) | Jun 07, 2021 |
| HP            | 1998                        | [2806e1e8cf](https://bsd-hardware.info/?probe=2806e1e8cf) | Jun 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | [95a281e2f8](https://bsd-hardware.info/?probe=95a281e2f8) | Jun 04, 2021 |
| Unknown       | Unknown                     | [65dd81d59e](https://bsd-hardware.info/?probe=65dd81d59e) | Jun 02, 2021 |
| Protectli     | FW4B Ver                    | [7e013ea910](https://bsd-hardware.info/?probe=7e013ea910) | May 20, 2021 |
| Unknown       | Unknown                     | [f90e5f9566](https://bsd-hardware.info/?probe=f90e5f9566) | May 16, 2021 |
| Unknown       | Unknown                     | [e67de92cb9](https://bsd-hardware.info/?probe=e67de92cb9) | May 14, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [273e379d9f](https://bsd-hardware.info/?probe=273e379d9f) | May 14, 2021 |
| Shuttle       | FS110                       | [e39173782f](https://bsd-hardware.info/?probe=e39173782f) | May 08, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [1f78fbb36c](https://bsd-hardware.info/?probe=1f78fbb36c) | May 08, 2021 |
| Intel         | Q3XXG4-P V1.0               | [5a128dd6a3](https://bsd-hardware.info/?probe=5a128dd6a3) | Apr 22, 2021 |
| HP            | 18E7                        | [e6354de524](https://bsd-hardware.info/?probe=e6354de524) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7a6f106b0e](https://bsd-hardware.info/?probe=7a6f106b0e) | Apr 18, 2021 |
| Intel         | SHARKBAY                    | [cd0467031a](https://bsd-hardware.info/?probe=cd0467031a) | Apr 17, 2021 |
| HARDKERNEL    | ODROID-H2                   | [5a1a372153](https://bsd-hardware.info/?probe=5a1a372153) | Apr 16, 2021 |
| HARDKERNEL    | ODROID-H2                   | [31a9bf167b](https://bsd-hardware.info/?probe=31a9bf167b) | Apr 16, 2021 |
| Dell          | 051FJ8 A01                  | [351b13fd3b](https://bsd-hardware.info/?probe=351b13fd3b) | Apr 15, 2021 |
| ASRock        | J4105M                      | [69165e1573](https://bsd-hardware.info/?probe=69165e1573) | Apr 13, 2021 |
| HP            | 1495                        | [5aca6c03c1](https://bsd-hardware.info/?probe=5aca6c03c1) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [0e814e53e9](https://bsd-hardware.info/?probe=0e814e53e9) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [817ec0a0da](https://bsd-hardware.info/?probe=817ec0a0da) | Apr 09, 2021 |
| ASUSTek       | PRIME H410M-A               | [6f4f9fb14e](https://bsd-hardware.info/?probe=6f4f9fb14e) | Apr 07, 2021 |
| HP            | 2AF7                        | [acd341147c](https://bsd-hardware.info/?probe=acd341147c) | Apr 03, 2021 |
| Dell          | 0TTDMJ A00                  | [b5c0428c8a](https://bsd-hardware.info/?probe=b5c0428c8a) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | [6af0a9bc78](https://bsd-hardware.info/?probe=6af0a9bc78) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | [aaf140005c](https://bsd-hardware.info/?probe=aaf140005c) | Mar 30, 2021 |
| AMI           | Cherry Trail CR             | [636dfb334b](https://bsd-hardware.info/?probe=636dfb334b) | Mar 29, 2021 |
| Gigabyte      | D525TUD                     | [a48a515986](https://bsd-hardware.info/?probe=a48a515986) | Mar 24, 2021 |
| Dell          | 0M9KCM A00                  | [7280d52eff](https://bsd-hardware.info/?probe=7280d52eff) | Mar 23, 2021 |
| Lenovo        | 30D9 No DPK                 | [061ad76c0e](https://bsd-hardware.info/?probe=061ad76c0e) | Mar 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | [03935b2745](https://bsd-hardware.info/?probe=03935b2745) | Mar 20, 2021 |
| Dell          | 00V62H A00                  | [27cb6a75c8](https://bsd-hardware.info/?probe=27cb6a75c8) | Mar 19, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [8964a02114](https://bsd-hardware.info/?probe=8964a02114) | Mar 15, 2021 |
| ASRock        | B450M Pro4                  | [e9ca160a2d](https://bsd-hardware.info/?probe=e9ca160a2d) | Mar 11, 2021 |
| Shuttle       | FS110                       | [fc31311d01](https://bsd-hardware.info/?probe=fc31311d01) | Mar 10, 2021 |
| Supermicro    | A2SDi-TP8F                  | [c30d805062](https://bsd-hardware.info/?probe=c30d805062) | Mar 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [c7b0539b99](https://bsd-hardware.info/?probe=c7b0539b99) | Mar 02, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | [9d35f9e853](https://bsd-hardware.info/?probe=9d35f9e853) | Feb 24, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [11d6c98009](https://bsd-hardware.info/?probe=11d6c98009) | Feb 21, 2021 |
| Protectli     | FW6                         | [b656792690](https://bsd-hardware.info/?probe=b656792690) | Feb 20, 2021 |
| ASUSTek       | PRIME H410M-A               | [cfd1824b40](https://bsd-hardware.info/?probe=cfd1824b40) | Feb 18, 2021 |
| Gigabyte      | MRZNVMS-00                  | [b51cb672a4](https://bsd-hardware.info/?probe=b51cb672a4) | Feb 12, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [3402eabdbf](https://bsd-hardware.info/?probe=3402eabdbf) | Feb 09, 2021 |
| ASRock        | Z270M-ITX/ac                | [9b50d422e3](https://bsd-hardware.info/?probe=9b50d422e3) | Feb 04, 2021 |
| HP            | 0AECh D                     | [6dde87584c](https://bsd-hardware.info/?probe=6dde87584c) | Feb 04, 2021 |
| PC Engines    | apu4                        | [18dfb34a97](https://bsd-hardware.info/?probe=18dfb34a97) | Feb 04, 2021 |
| HP            | 3397                        | [cda4af23ee](https://bsd-hardware.info/?probe=cda4af23ee) | Feb 03, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | [0a48224f4b](https://bsd-hardware.info/?probe=0a48224f4b) | Feb 03, 2021 |
| HP            | 3397                        | [65f1db2a70](https://bsd-hardware.info/?probe=65f1db2a70) | Feb 03, 2021 |
| HP            | 82B4                        | [faf58d8f87](https://bsd-hardware.info/?probe=faf58d8f87) | Jan 30, 2021 |
| Lenovo        | 30D9 No DPK                 | [12056c71ad](https://bsd-hardware.info/?probe=12056c71ad) | Jan 30, 2021 |
| PC Engines    | APU2                        | [7e96c61bf9](https://bsd-hardware.info/?probe=7e96c61bf9) | Jan 30, 2021 |
| ASRock        | J3455-ITX                   | [65bde09c13](https://bsd-hardware.info/?probe=65bde09c13) | Jan 26, 2021 |
| ASRock        | J3455-ITX                   | [0a4d4fc896](https://bsd-hardware.info/?probe=0a4d4fc896) | Jan 25, 2021 |
| ASRock        | J3355B-ITX                  | [e8496a6202](https://bsd-hardware.info/?probe=e8496a6202) | Jan 24, 2021 |
| PC Engines    | APU2                        | [da6e3cd1a6](https://bsd-hardware.info/?probe=da6e3cd1a6) | Jan 23, 2021 |
| PC Engines    | APU2                        | [3d536a42eb](https://bsd-hardware.info/?probe=3d536a42eb) | Jan 21, 2021 |
| PC Engines    | APU2                        | [043446a653](https://bsd-hardware.info/?probe=043446a653) | Jan 21, 2021 |
| Shuttle       | FS110                       | [fed17a1f77](https://bsd-hardware.info/?probe=fed17a1f77) | Jan 21, 2021 |
| Supermicro    | X8STi                       | [7cda964f76](https://bsd-hardware.info/?probe=7cda964f76) | Jan 20, 2021 |
| Dell          | 0M9KCM A02                  | [1cc5f6a07b](https://bsd-hardware.info/?probe=1cc5f6a07b) | Jan 20, 2021 |
| ASUSTek       | Z97-A                       | [8c55004504](https://bsd-hardware.info/?probe=8c55004504) | Jan 19, 2021 |
| Supermicro    | X7SLA                       | [2d31f38bf0](https://bsd-hardware.info/?probe=2d31f38bf0) | Jan 10, 2021 |
| Supermicro    | X7SPA-HF                    | [834cb6c68a](https://bsd-hardware.info/?probe=834cb6c68a) | Jan 10, 2021 |
| MSI           | X58 Pro-E                   | [bd108f94d5](https://bsd-hardware.info/?probe=bd108f94d5) | Jan 02, 2021 |
| HP            | 212B                        | [7fe9d2c508](https://bsd-hardware.info/?probe=7fe9d2c508) | Dec 18, 2020 |
| Dell          | 0GM819                      | [adc8eb1931](https://bsd-hardware.info/?probe=adc8eb1931) | Dec 18, 2020 |
| HP            | 805D                        | [dc62857275](https://bsd-hardware.info/?probe=dc62857275) | Dec 17, 2020 |
| Supermicro    | X8STi                       | [80c2762cfb](https://bsd-hardware.info/?probe=80c2762cfb) | Dec 16, 2020 |
| ASRockRack    | D1541D4U-2O8R               | [d59d8a3b6d](https://bsd-hardware.info/?probe=d59d8a3b6d) | Dec 16, 2020 |
| Supermicro    | X11SSH-F                    | [ebb920c0c4](https://bsd-hardware.info/?probe=ebb920c0c4) | Dec 16, 2020 |
| MSI           | X99S SLI PLUS               | [9b2421d9d5](https://bsd-hardware.info/?probe=9b2421d9d5) | Nov 28, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5d5ecb38cd](https://bsd-hardware.info/?probe=5d5ecb38cd) | Nov 25, 2020 |
| MSI           | 970 GAMING                  | [002b408f7e](https://bsd-hardware.info/?probe=002b408f7e) | Nov 18, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [714b6539cf](https://bsd-hardware.info/?probe=714b6539cf) | Nov 07, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [9f871ab960](https://bsd-hardware.info/?probe=9f871ab960) | Nov 01, 2020 |
| Intel         | X79 V2.81A                  | [d5b4cdf28a](https://bsd-hardware.info/?probe=d5b4cdf28a) | Oct 30, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [59c940d739](https://bsd-hardware.info/?probe=59c940d739) | Oct 30, 2020 |
| Unknown       | Unknown                     | [8552669e76](https://bsd-hardware.info/?probe=8552669e76) | Oct 30, 2020 |
| Unknown       | Unknown                     | [50966c2f83](https://bsd-hardware.info/?probe=50966c2f83) | Oct 30, 2020 |
| ADI Engine... | RCC-VE                      | [30440abc03](https://bsd-hardware.info/?probe=30440abc03) | Oct 29, 2020 |
| IBM           | Board                       | [11b0b7012f](https://bsd-hardware.info/?probe=11b0b7012f) | Oct 21, 2020 |
| IBM           | Board                       | [a92c08a920](https://bsd-hardware.info/?probe=a92c08a920) | Oct 21, 2020 |
| IBM           | Board                       | [80d5f15a63](https://bsd-hardware.info/?probe=80d5f15a63) | Oct 21, 2020 |
| MSI           | MS-7250                     | [41e2d9dab3](https://bsd-hardware.info/?probe=41e2d9dab3) | Sep 04, 2020 |
| HP            | 3031h                       | [1f2695b3a7](https://bsd-hardware.info/?probe=1f2695b3a7) | Aug 25, 2020 |
| ASUSTek       | Z170-P                      | [49e01a949b](https://bsd-hardware.info/?probe=49e01a949b) | Jul 29, 2020 |
| ASUSTek       | P8Z77-V LK                  | [0f7697b73a](https://bsd-hardware.info/?probe=0f7697b73a) | May 28, 2020 |
| Dell          | 0T10XW A02                  | [81f39f3061](https://bsd-hardware.info/?probe=81f39f3061) | May 28, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OPNsense 23.7.10  | 16       | 3.61%   |
| OPNsense 23.1.11  | 16       | 3.61%   |
| OPNsense 22.7.10  | 14       | 3.16%   |
| OPNsense 23.7.3   | 10       | 2.26%   |
| OPNsense 23.1.6   | 10       | 2.26%   |
| OPNsense 23.7.8   | 9        | 2.03%   |
| OPNsense 23.7.1   | 9        | 2.03%   |
| OPNsense 23.1.1   | 9        | 2.03%   |
| OPNsense 22.1.10  | 9        | 2.03%   |
| helloSystem 0.7.0 | 9        | 2.03%   |
| OPNsense 23.1.9   | 8        | 1.81%   |
| OPNsense 22.7.8   | 8        | 1.81%   |
| OPNsense 22.1.8   | 8        | 1.81%   |
| OPNsense 21.1.4   | 8        | 1.81%   |
| helloSystem 0.5.0 | 8        | 1.81%   |
| OPNsense 23.1     | 7        | 1.58%   |
| OPNsense 22.1.7   | 7        | 1.58%   |
| OPNsense 22.1     | 7        | 1.58%   |
| OPNsense 21.7     | 7        | 1.58%   |
| OPNsense 21.1.3   | 7        | 1.58%   |
| OPNsense 21.1     | 7        | 1.58%   |
| helloSystem 0.8.1 | 7        | 1.58%   |
| OPNsense 23.7.9   | 6        | 1.35%   |
| OPNsense 23.7.5   | 6        | 1.35%   |
| OPNsense 22.7.4   | 6        | 1.35%   |
| OPNsense 22.1.6   | 6        | 1.35%   |
| OPNsense 21.1.5   | 6        | 1.35%   |
| OPNsense 20.7.8   | 6        | 1.35%   |
| FreeBSD 13.1-p5   | 6        | 1.35%   |
| OPNsense 23.7.2   | 5        | 1.13%   |
| OPNsense 22.7.9   | 5        | 1.13%   |
| OPNsense 22.7.11  | 5        | 1.13%   |
| OPNsense 22.7     | 5        | 1.13%   |
| OPNsense 21.7.7   | 5        | 1.13%   |
| OPNsense 21.7.3   | 5        | 1.13%   |
| OPNsense 21.7.1   | 5        | 1.13%   |
| OPNsense 21.1.6   | 5        | 1.13%   |
| OPNsense 21.1.1   | 5        | 1.13%   |
| FreeBSD 13.1      | 5        | 1.13%   |
| FreeBSD 12.2      | 5        | 1.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 233      | 71.47%  |
| FreeBSD     | 50       | 15.34%  |
| helloSystem | 27       | 8.28%   |
| OpenBSD     | 7        | 2.15%   |
| GhostBSD    | 3        | 0.92%   |
| FreeNAS     | 3        | 0.92%   |
| TrueNAS     | 1        | 0.31%   |
| pfSense     | 1        | 0.31%   |
| MyBee       | 1        | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 321      | 99.38%  |
| macppc | 1        | 0.31%   |
| i386   | 1        | 0.31%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 259      | 79.2%   |
| helloDesktop | 32       | 9.79%   |
| KDE5         | 11       | 3.36%   |
| XFCE         | 8        | 2.45%   |
| MATE         | 6        | 1.83%   |
| GNOME        | 3        | 0.92%   |
| Openbox      | 2        | 0.61%   |
| Cinnamon     | 2        | 0.61%   |
| X-Cinnamon   | 1        | 0.31%   |
| Window Maker | 1        | 0.31%   |
| LXDE         | 1        | 0.31%   |
| DWM          | 1        | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 261      | 80.8%   |
| X11     | 60       | 18.58%  |
| Wayland | 2        | 0.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 272      | 83.18%  |
| SLiM    | 31       | 9.48%   |
| SDDM    | 13       | 3.98%   |
| LightDM | 5        | 1.53%   |
| XDM     | 3        | 0.92%   |
| GDM     | 2        | 0.61%   |
| Ly      | 1        | 0.31%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 249      | 76.62%  |
| en_US   | 41       | 12.62%  |
| C       | 26       | 8%      |
| en_CA   | 5        | 1.54%   |
| fr_FR   | 2        | 0.62%   |
| fr      | 1        | 0.31%   |
| en      | 1        | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 282      | 86.24%  |
| BIOS | 45       | 13.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 168      | 50.45%  |
| Zfs    | 146      | 43.84%  |
| Cd9660 | 12       | 3.6%    |
| Ffs    | 7        | 2.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 303      | 93.81%  |
| MBR     | 18       | 5.57%   |
| Unknown | 2        | 0.62%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 41       | 12.69%  |
| Hewlett-Packard            | 39       | 12.07%  |
| Dell                       | 37       | 11.46%  |
| Lenovo                     | 30       | 9.29%   |
| Unknown                    | 27       | 8.36%   |
| Protectli                  | 22       | 6.81%   |
| Intel                      | 19       | 5.88%   |
| Gigabyte Technology        | 14       | 4.33%   |
| ASRock                     | 13       | 4.02%   |
| Techvision                 | 12       | 3.72%   |
| Supermicro                 | 12       | 3.72%   |
| MSI                        | 11       | 3.41%   |
| AZW                        | 7        | 2.17%   |
| PC Engines                 | 6        | 1.86%   |
| Acer                       | 5        | 1.55%   |
| MW                         | 3        | 0.93%   |
| CncTion                    | 2        | 0.62%   |
| ASRockRack                 | 2        | 0.62%   |
| Apple                      | 2        | 0.62%   |
| ADI Engineering            | 2        | 0.62%   |
| Yanling                    | 1        | 0.31%   |
| Shuttle                    | 1        | 0.31%   |
| ShenZhen MinWin Technology | 1        | 0.31%   |
| SeeedStudio                | 1        | 0.31%   |
| Quanta                     | 1        | 0.31%   |
| Pegatron                   | 1        | 0.31%   |
| MiTAC                      | 1        | 0.31%   |
| IBM                        | 1        | 0.31%   |
| iBASE                      | 1        | 0.31%   |
| HARDKERNEL                 | 1        | 0.31%   |
| Datto                      | 1        | 0.31%   |
| Cisco                      | 1        | 0.31%   |
| CheckPoint                 | 1        | 0.31%   |
| Biostar                    | 1        | 0.31%   |
| Arctic Wolf Networks       | 1        | 0.31%   |
| AMI                        | 1        | 0.31%   |
| Alienware                  | 1        | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 27       | 8.36%   |
| Techvision TVI7309X                | 12       | 3.72%   |
| Protectli FW4B                     | 12       | 3.72%   |
| Protectli FW6                      | 6        | 1.86%   |
| Intel Q3XXG4-P V1.0                | 6        | 1.86%   |
| Intel NDISB533                     | 5        | 1.55%   |
| HP EliteDesk 800 G1 SFF            | 4        | 1.24%   |
| Dell OptiPlex 9010                 | 4        | 1.24%   |
| Dell OptiPlex 7010                 | 4        | 1.24%   |
| AZW U59                            | 4        | 1.24%   |
| PC Engines APU2                    | 3        | 0.93%   |
| MW GMLK-2_5G4L                     | 3        | 0.93%   |
| HP Z440 Workstation                | 3        | 0.93%   |
| HP Compaq 8200 Elite SFF PC        | 3        | 0.93%   |
| HP Compaq 6200 Pro MT PC           | 3        | 0.93%   |
| Dell OptiPlex 7060                 | 3        | 0.93%   |
| ASUS All Series                    | 3        | 0.93%   |
| Supermicro X8STi                   | 2        | 0.62%   |
| Supermicro SYS-E300-9A             | 2        | 0.62%   |
| Protectli VP2420                   | 2        | 0.62%   |
| PC Engines apu4                    | 2        | 0.62%   |
| MSI MS-7A40                        | 2        | 0.62%   |
| Lenovo ThinkCentre M93p 10A8S16X0J | 2        | 0.62%   |
| Intel CRESCENTBAY                  | 2        | 0.62%   |
| HP ProDesk 400 G5 SFF              | 2        | 0.62%   |
| HP Compaq Elite 8300 SFF           | 2        | 0.62%   |
| HP 500-459                         | 2        | 0.62%   |
| Dell Precision WorkStation T3500   | 2        | 0.62%   |
| Dell Precision Tower 5810          | 2        | 0.62%   |
| Dell OptiPlex 7050                 | 2        | 0.62%   |
| Dell OptiPlex 7020                 | 2        | 0.62%   |
| Dell OptiPlex 3060                 | 2        | 0.62%   |
| Dell OptiPlex 3020                 | 2        | 0.62%   |
| Dell OptiPlex 3010                 | 2        | 0.62%   |
| Dell G5 5090                       | 2        | 0.62%   |
| AZW EQ                             | 2        | 0.62%   |
| ASUS PRIME B450M-A                 | 2        | 0.62%   |
| ASUS P8H77-I                       | 2        | 0.62%   |
| ASUS P8H67-M PRO                   | 2        | 0.62%   |
| ASUS M5A97 PLUS                    | 2        | 0.62%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Lenovo ThinkCentre     | 28       | 8.67%   |
| Dell OptiPlex          | 28       | 8.67%   |
| Unknown                | 27       | 8.36%   |
| Techvision TVI7309X    | 12       | 3.72%   |
| Protectli FW4B         | 12       | 3.72%   |
| ASUS PRIME             | 11       | 3.41%   |
| HP Compaq              | 10       | 3.1%    |
| HP ProDesk             | 8        | 2.48%   |
| HP EliteDesk           | 7        | 2.17%   |
| Protectli FW6          | 6        | 1.86%   |
| Intel Q3XXG4-P         | 6        | 1.86%   |
| Dell Precision         | 6        | 1.86%   |
| ASUS ROG               | 6        | 1.86%   |
| Intel NDISB533         | 5        | 1.55%   |
| Acer Aspire            | 5        | 1.55%   |
| AZW U59                | 4        | 1.24%   |
| PC Engines APU2        | 3        | 0.93%   |
| MW GMLK-2              | 3        | 0.93%   |
| HP Z440                | 3        | 0.93%   |
| ASUS All               | 3        | 0.93%   |
| ASRock B450M           | 3        | 0.93%   |
| Supermicro X8STi       | 2        | 0.62%   |
| Supermicro SYS-E300-9A | 2        | 0.62%   |
| Protectli VP2420       | 2        | 0.62%   |
| PC Engines apu4        | 2        | 0.62%   |
| MSI MS-7A40            | 2        | 0.62%   |
| Intel CRESCENTBAY      | 2        | 0.62%   |
| HP t620                | 2        | 0.62%   |
| HP 500-459             | 2        | 0.62%   |
| Dell G5                | 2        | 0.62%   |
| AZW EQ                 | 2        | 0.62%   |
| ASUS TUF               | 2        | 0.62%   |
| ASUS P8H77-I           | 2        | 0.62%   |
| ASUS P8H67-M           | 2        | 0.62%   |
| ASUS M5A97             | 2        | 0.62%   |
| ASRock H110M-DGS       | 2        | 0.62%   |
| ADI Engineering RCC-VE | 2        | 0.62%   |
| Yanling YL-KBR6L       | 1        | 0.31%   |
| Supermicro X9SCL       | 1        | 0.31%   |
| Supermicro X9DR3-F     | 1        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 45       | 13.93%  |
| 2022    | 43       | 13.31%  |
| 2020    | 28       | 8.67%   |
| 2014    | 26       | 8.05%   |
| 2016    | 22       | 6.81%   |
| 2013    | 20       | 6.19%   |
| 2011    | 20       | 6.19%   |
| 2021    | 19       | 5.88%   |
| 2019    | 18       | 5.57%   |
| 2012    | 15       | 4.64%   |
| 2010    | 14       | 4.33%   |
| 2017    | 13       | 4.02%   |
| 2023    | 11       | 3.41%   |
| 2015    | 11       | 3.41%   |
| 2008    | 7        | 2.17%   |
| 2009    | 6        | 1.86%   |
| 2007    | 2        | 0.62%   |
| Unknown | 2        | 0.62%   |
| 2006    | 1        | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 323      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 312      | 96.59%  |
| Yes  | 11       | 3.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 129      | 38.74%  |
| 16.01-24.0  | 87       | 26.13%  |
| 4.01-8.0    | 47       | 14.11%  |
| 32.01-64.0  | 33       | 9.91%   |
| 64.01-256.0 | 16       | 4.8%    |
| 2.01-3.0    | 7        | 2.1%    |
| 3.01-4.0    | 6        | 1.8%    |
| 24.01-32.0  | 5        | 1.5%    |
| 1.01-2.0    | 2        | 0.6%    |
| 0.51-1.0    | 1        | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 155      | 46.69%  |
| 0.51-1.0    | 111      | 33.43%  |
| 1.01-2.0    | 44       | 13.25%  |
| 2.01-3.0    | 9        | 2.71%   |
| 3.01-4.0    | 5        | 1.51%   |
| 4.01-8.0    | 4        | 1.2%    |
| 32.01-64.0  | 1        | 0.3%    |
| 64.01-256.0 | 1        | 0.3%    |
| 8.01-16.0   | 1        | 0.3%    |
| 0           | 1        | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 234      | 70.91%  |
| 2      | 45       | 13.64%  |
| 0      | 22       | 6.67%   |
| 3      | 17       | 5.15%   |
| 4      | 7        | 2.12%   |
| 13     | 2        | 0.61%   |
| 10     | 1        | 0.3%    |
| 7      | 1        | 0.3%    |
| 5      | 1        | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 253      | 77.13%  |
| Yes       | 75       | 22.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 321      | 99.07%  |
| No        | 3        | 0.93%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 260      | 79.51%  |
| Yes       | 67       | 20.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 278      | 86.07%  |
| Yes       | 45       | 13.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Canada  | 323      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Montreal                   | 30       | 8.55%   |
| Toronto                    | 29       | 8.26%   |
| Calgary                    | 24       | 6.84%   |
| Edmonton                   | 17       | 4.84%   |
| Ottawa                     | 16       | 4.56%   |
| Victoria                   | 11       | 3.13%   |
| Winnipeg                   | 10       | 2.85%   |
| Kitchener                  | 8        | 2.28%   |
| Vancouver                  | 7        | 1.99%   |
| Surrey                     | 7        | 1.99%   |
| London                     | 6        | 1.71%   |
| Brampton                   | 6        | 1.71%   |
| Regina                     | 5        | 1.42%   |
| Laval                      | 5        | 1.42%   |
| St. Albert                 | 4        | 1.14%   |
| Scarborough                | 4        | 1.14%   |
| Québec                    | 4        | 1.14%   |
| North Vancouver            | 4        | 1.14%   |
| Moncton                    | 4        | 1.14%   |
| Cambridge                  | 4        | 1.14%   |
| Windsor                    | 3        | 0.85%   |
| St. Jean Baptiste          | 3        | 0.85%   |
| Saskatoon                  | 3        | 0.85%   |
| Sarnia                     | 3        | 0.85%   |
| Sainte-Marthe-sur-le-Lac   | 3        | 0.85%   |
| Nanaimo                    | 3        | 0.85%   |
| Longueuil                  | 3        | 0.85%   |
| Kingston                   | 3        | 0.85%   |
| Greater Sudbury            | 3        | 0.85%   |
| Burlington                 | 3        | 0.85%   |
| West Kelowna               | 2        | 0.57%   |
| Terrebonne                 | 2        | 0.57%   |
| Sherbrooke                 | 2        | 0.57%   |
| Sainte-Julie               | 2        | 0.57%   |
| Saint-Bruno-de-Montarville | 2        | 0.57%   |
| Richmond                   | 2        | 0.57%   |
| Peterborough               | 2        | 0.57%   |
| Oshawa                     | 2        | 0.57%   |
| Oakville                   | 2        | 0.57%   |
| Mississauga                | 2        | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 64       | 94     | 16.84%  |
| Seagate             | 48       | 99     | 12.63%  |
| WDC                 | 47       | 103    | 12.37%  |
| Kingston            | 42       | 58     | 11.05%  |
| Crucial             | 15       | 24     | 3.95%   |
| Intel               | 14       | 20     | 3.68%   |
| A-DATA Technology   | 14       | 25     | 3.68%   |
| SanDisk             | 11       | 14     | 2.89%   |
| Patriot             | 11       | 12     | 2.89%   |
| SPCC                | 9        | 11     | 2.37%   |
| Toshiba             | 8        | 12     | 2.11%   |
| OCZ                 | 6        | 7      | 1.58%   |
| Micron Technology   | 6        | 12     | 1.58%   |
| Hitachi             | 6        | 6      | 1.58%   |
| Dogfish             | 6        | 10     | 1.58%   |
| SK hynix            | 4        | 6      | 1.05%   |
| Protectli           | 4        | 6      | 1.05%   |
| Phison              | 4        | 5      | 1.05%   |
| Mushkin             | 4        | 5      | 1.05%   |
| Hoodisk             | 4        | 5      | 1.05%   |
| HGST                | 4        | 6      | 1.05%   |
| Hewlett-Packard     | 4        | 4      | 1.05%   |
| China               | 4        | 8      | 1.05%   |
| BIWIN               | 4        | 7      | 1.05%   |
| Transcend           | 3        | 4      | 0.79%   |
| Timetec             | 3        | 5      | 0.79%   |
| PNY                 | 3        | 4      | 0.79%   |
| NVMe                | 3        | 3      | 0.79%   |
| VisionTek           | 2        | 6      | 0.53%   |
| Team                | 2        | 5      | 0.53%   |
| Netac               | 2        | 2      | 0.53%   |
| FORESEE             | 2        | 3      | 0.53%   |
| Corsair             | 2        | 4      | 0.53%   |
| walram              | 1        | 1      | 0.26%   |
| Silicon Motion      | 1        | 1      | 0.26%   |
| ShiJi               | 1        | 1      | 0.26%   |
| SATADOM             | 1        | 2      | 0.26%   |
| OPENBSD             | 1        | 1      | 0.26%   |
| Lexar               | 1        | 1      | 0.26%   |
| Kingsand            | 1        | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB         | 13       | 3.2%    |
| Kingston SA400S37120G 120GB         | 9        | 2.22%   |
| Seagate ST500DM002-1BD142 500GB     | 6        | 1.48%   |
| Seagate ST1000DM010-2EP102 1TB      | 6        | 1.48%   |
| Samsung SSD 850 EVO 250GB           | 6        | 1.48%   |
| Samsung SSD 840 EVO 120GB           | 5        | 1.23%   |
| Seagate ST2000DM008-2FR102 2TB      | 4        | 0.99%   |
| SanDisk SD6SB1M064G1022I 64GB       | 4        | 0.99%   |
| Samsung SSD 970 EVO Plus 1TB        | 4        | 0.99%   |
| Samsung SSD 860 EVO 500GB           | 4        | 0.99%   |
| BIWIN SSD 128GB                     | 4        | 0.99%   |
| WDC WD20EZRX-00DC0B0 2TB            | 3        | 0.74%   |
| Transcend TS256GMSA230S 256GB       | 3        | 0.74%   |
| Toshiba DT01ACA100 1TB              | 3        | 0.74%   |
| SPCC Solid State Disk 256GB         | 3        | 0.74%   |
| Seagate ST3500413AS 500GB           | 3        | 0.74%   |
| Samsung SSD 980 1TB                 | 3        | 0.74%   |
| Samsung SSD 840 EVO 250GB           | 3        | 0.74%   |
| Kingston SUV500MS120G 120GB         | 3        | 0.74%   |
| Dogfish SSD 128GB                   | 3        | 0.74%   |
| Crucial CT240BX500SSD1 240GB        | 3        | 0.74%   |
| A-DATA SU655 120GB                  | 3        | 0.74%   |
| WDC WD6400AAKS-22A7B2 640GB         | 2        | 0.49%   |
| WDC WD40EFRX-68WT0N0 4TB            | 2        | 0.49%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 0.49%   |
| WDC WD10EZEX-22MFCA0 1TB            | 2        | 0.49%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2        | 0.49%   |
| WDC PC SN520 NVMe 256GB             | 2        | 0.49%   |
| VisionTek mSATA 120GB               | 2        | 0.49%   |
| Toshiba MQ01ABD075 752GB            | 2        | 0.49%   |
| Team TM8FP6512G 512GB               | 2        | 0.49%   |
| SPCC Solid State Disk 128GB         | 2        | 0.49%   |
| SPCC M.2 PCIe SSD 256GB             | 2        | 0.49%   |
| Seagate ST8000VN0022-2EL112 8TB     | 2        | 0.49%   |
| Seagate ST4000VN008-2DR166 4TB      | 2        | 0.49%   |
| Seagate ST2000DM001-1ER164 2TB      | 2        | 0.49%   |
| Seagate ST1000DM003-1CH162 1TB      | 2        | 0.49%   |
| SanDisk SDSSDHII120G 120GB          | 2        | 0.49%   |
| SanDisk SDSA6MM-016G-1006 16GB      | 2        | 0.49%   |
| Samsung SSD PM871 2.5 7mm 512GB SED | 2        | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 45       | 96     | 45%     |
| WDC     | 34       | 82     | 34%     |
| Toshiba | 7        | 9      | 7%      |
| Hitachi | 6        | 6      | 6%      |
| HGST    | 4        | 6      | 4%      |
| OPENBSD | 1        | 1      | 1%      |
| NVMe    | 1        | 1      | 1%      |
| HPT     | 1        | 1      | 1%      |
| Fujitsu | 1        | 1      | 1%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 46       | 68     | 20.26%  |
| Kingston            | 39       | 50     | 17.18%  |
| Crucial             | 14       | 20     | 6.17%   |
| A-DATA Technology   | 14       | 25     | 6.17%   |
| Intel               | 12       | 17     | 5.29%   |
| SanDisk             | 11       | 14     | 4.85%   |
| Patriot             | 8        | 9      | 3.52%   |
| WDC                 | 7        | 9      | 3.08%   |
| SPCC                | 6        | 8      | 2.64%   |
| OCZ                 | 6        | 7      | 2.64%   |
| Dogfish             | 6        | 10     | 2.64%   |
| Micron Technology   | 5        | 11     | 2.2%    |
| Protectli           | 4        | 6      | 1.76%   |
| Mushkin             | 4        | 5      | 1.76%   |
| Hoodisk             | 4        | 5      | 1.76%   |
| China               | 4        | 8      | 1.76%   |
| BIWIN               | 4        | 7      | 1.76%   |
| Transcend           | 3        | 4      | 1.32%   |
| Seagate             | 3        | 3      | 1.32%   |
| PNY                 | 3        | 4      | 1.32%   |
| VisionTek           | 2        | 6      | 0.88%   |
| Timetec             | 2        | 3      | 0.88%   |
| Netac               | 2        | 2      | 0.88%   |
| Hewlett-Packard     | 2        | 2      | 0.88%   |
| FORESEE             | 2        | 3      | 0.88%   |
| Corsair             | 2        | 4      | 0.88%   |
| walram              | 1        | 1      | 0.44%   |
| SATADOM             | 1        | 2      | 0.44%   |
| Phison              | 1        | 1      | 0.44%   |
| NVMe                | 1        | 1      | 0.44%   |
| Lexar               | 1        | 1      | 0.44%   |
| Kingsand            | 1        | 1      | 0.44%   |
| Innodisk            | 1        | 1      | 0.44%   |
| HPE                 | 1        | 4      | 0.44%   |
| Gigastone           | 1        | 4      | 0.44%   |
| Fanxiang            | 1        | 1      | 0.44%   |
| EAGET               | 1        | 1      | 0.44%   |
| AVEXIR              | 1        | 2      | 0.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 209      | 330    | 60.4%   |
| HDD  | 83       | 203    | 23.99%  |
| NVMe | 54       | 85     | 15.61%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 266      | 533    | 83.13%  |
| NVMe | 54       | 85     | 16.88%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 221      | 342    | 71.99%  |
| 0.51-1.0   | 46       | 81     | 14.98%  |
| 1.01-2.0   | 18       | 39     | 5.86%   |
| 3.01-4.0   | 10       | 25     | 3.26%   |
| 4.01-10.0  | 6        | 33     | 1.95%   |
| 2.01-3.0   | 4        | 10     | 1.3%    |
| 10.01-20.0 | 2        | 3      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 145      | 42.77%  |
| 251-500        | 59       | 17.4%   |
| 51-100         | 38       | 11.21%  |
| 1-20           | 29       | 8.55%   |
| 21-50          | 27       | 7.96%   |
| 501-1000       | 26       | 7.67%   |
| 1001-2000      | 8        | 2.36%   |
| More than 3000 | 4        | 1.18%   |
| Unknown        | 3        | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 302      | 89.88%  |
| 21-50     | 18       | 5.36%   |
| 51-100    | 6        | 1.79%   |
| 101-250   | 3        | 0.89%   |
| Unknown   | 3        | 0.89%   |
| 1001-2000 | 2        | 0.6%    |
| 501-1000  | 2        | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB            | 3        | 5      | 6.12%   |
| WDC WD6400AAKS-22A7B2 640GB                | 2        | 8      | 4.08%   |
| VisionTek mSATA 120GB                      | 2        | 6      | 4.08%   |
| Toshiba MQ01ABD075 752GB                   | 2        | 2      | 4.08%   |
| Seagate ST3500413AS 500GB                  | 2        | 4      | 4.08%   |
| Patriot Pyro SE 120GB                      | 2        | 2      | 4.08%   |
| Patriot Burst Elite 120GB                  | 2        | 2      | 4.08%   |
| WDC WD50EFRX-68L0BN1 5TB                   | 1        | 1      | 2.04%   |
| WDC WD5003AZEX-00K1GA0 500GB               | 1        | 1      | 2.04%   |
| WDC WD40EFRX-68WT0N0 4TB                   | 1        | 2      | 2.04%   |
| WDC WD3200AAKS-75L9A0 320GB                | 1        | 1      | 2.04%   |
| WDC WD30EZRX-22D8PB0 3TB                   | 1        | 1      | 2.04%   |
| WDC WD2500AAKX-001CA0 250GB                | 1        | 1      | 2.04%   |
| WDC WD1600AAJS-60Z0A0 160GB                | 1        | 2      | 2.04%   |
| walram SSD 120G                            | 1        | 1      | 2.04%   |
| Toshiba MQ01ABD100 1TB                     | 1        | 1      | 2.04%   |
| Toshiba DT01ACA100 1TB                     | 1        | 3      | 2.04%   |
| SPCC Solid State Disk 128GB                | 1        | 1      | 2.04%   |
| Seagate ST500LM021-1KJ152 500GB            | 1        | 1      | 2.04%   |
| Seagate ST3250318AS 250GB                  | 1        | 1      | 2.04%   |
| Seagate ST3200822AS 200GB                  | 1        | 1      | 2.04%   |
| Seagate ST3160815AS 160GB                  | 1        | 1      | 2.04%   |
| Seagate ST31500341AS 1.5TB                 | 1        | 2      | 2.04%   |
| Seagate ST3120026A 120GB                   | 1        | 1      | 2.04%   |
| Seagate ST31000520AS 1TB                   | 1        | 1      | 2.04%   |
| Seagate ST1000DM003-1CH162 1TB             | 1        | 2      | 2.04%   |
| Samsung Electronics SSD 870 EVO 250GB      | 1        | 6      | 2.04%   |
| Mushkin MKNSSDEC512GB                      | 1        | 2      | 2.04%   |
| Micron Technology M500_MTFDDAK960MAV 960GB | 1        | 4      | 2.04%   |
| Kingston SV300S37A120G 120GB               | 1        | 1      | 2.04%   |
| Kingston SNS4151S316GD 16GB                | 1        | 2      | 2.04%   |
| Intel SSDSC2BB480G4 480GB                  | 1        | 1      | 2.04%   |
| Intel SSDSA2M080G2GC 80GB                  | 1        | 1      | 2.04%   |
| Hitachi HTS727550A9E364 500GB              | 1        | 1      | 2.04%   |
| Hitachi HTS542520K9A300 200GB              | 1        | 1      | 2.04%   |
| Hitachi HDT721010SLA360 1TB                | 1        | 1      | 2.04%   |
| HGST HTS725050A7E630 500GB                 | 1        | 2      | 2.04%   |
| HGST HTS541010A9E680 1TB                   | 1        | 1      | 2.04%   |
| Hewlett-Packard SSD S700 Pro 128GB         | 1        | 1      | 2.04%   |
| Crucial CT240M500SSD1 240GB                | 1        | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 19     | 25%     |
| WDC                 | 9        | 17     | 18.75%  |
| Toshiba             | 4        | 6      | 8.33%   |
| Patriot             | 4        | 4      | 8.33%   |
| Hitachi             | 3        | 3      | 6.25%   |
| VisionTek           | 2        | 6      | 4.17%   |
| Kingston            | 2        | 3      | 4.17%   |
| Intel               | 2        | 2      | 4.17%   |
| HGST                | 2        | 3      | 4.17%   |
| walram              | 1        | 1      | 2.08%   |
| SPCC                | 1        | 1      | 2.08%   |
| Samsung Electronics | 1        | 6      | 2.08%   |
| Mushkin             | 1        | 2      | 2.08%   |
| Micron Technology   | 1        | 4      | 2.08%   |
| Hewlett-Packard     | 1        | 1      | 2.08%   |
| Crucial             | 1        | 1      | 2.08%   |
| A-DATA Technology   | 1        | 2      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 12       | 19     | 40%     |
| WDC     | 9        | 17     | 30%     |
| Toshiba | 4        | 6      | 13.33%  |
| Hitachi | 3        | 3      | 10%     |
| HGST    | 2        | 3      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 27       | 48     | 60%     |
| SSD  | 18       | 33     | 40%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD10SPZX-00Z10T0 1TB                         | 1        | 1      | 33.33%  |
| Seagate ST3250310AS 250GB                        | 1        | 1      | 33.33%  |
| Samsung Electronics SSD PM830 2.5-inch 7mm 256GB | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 33.33%  |
| Seagate             | 1        | 1      | 33.33%  |
| Samsung Electronics | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 271      | 525    | 83.13%  |
| Malfunc  | 44       | 81     | 13.5%   |
| Detected | 8        | 9      | 2.45%   |
| Failed   | 3        | 3      | 0.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 266      | 65.2%   |
| AMD                         | 49       | 12.01%  |
| Samsung Electronics         | 20       | 4.9%    |
| SanDisk                     | 13       | 3.19%   |
| ASMedia Technology          | 7        | 1.72%   |
| Silicon Motion              | 6        | 1.47%   |
| MAXIO Technology (Hangzhou) | 6        | 1.47%   |
| Nvidia                      | 5        | 1.23%   |
| SK hynix                    | 4        | 0.98%   |
| Phison Electronics          | 4        | 0.98%   |
| Marvell Technology Group    | 4        | 0.98%   |
| Kingston Technology Company | 4        | 0.98%   |
| VIA Technologies            | 3        | 0.74%   |
| JMicron Technology          | 3        | 0.74%   |
| Chelsio Communications      | 3        | 0.74%   |
| Broadcom / LSI              | 3        | 0.74%   |
| Silicon Image               | 2        | 0.49%   |
| Micron/Crucial Technology   | 2        | 0.49%   |
| Toshiba                     | 1        | 0.25%   |
| Realtek Semiconductor       | 1        | 0.25%   |
| Micron Technology           | 1        | 0.25%   |
| HighPoint Technologies      | 1        | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 34       | 7.14%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 28       | 5.88%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 23       | 4.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 21       | 4.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 18       | 3.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 18       | 3.78%   |
| AMD 400 Series Chipset SATA Controller                                           | 15       | 3.15%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 14       | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 13       | 2.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 12       | 2.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 10       | 2.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9        | 1.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8        | 1.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8        | 1.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 8        | 1.68%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 6        | 1.26%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                     | 6        | 1.26%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 6        | 1.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6        | 1.26%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 6        | 1.26%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 5        | 1.05%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 5        | 1.05%   |
| Intel Elkhart Lake SATA AHCI                                                     | 5        | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 5        | 1.05%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 5        | 1.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5        | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5        | 1.05%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                            | 4        | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4        | 0.84%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 4        | 0.84%   |
| AMD FCH SATA Controller [IDE mode]                                               | 4        | 0.84%   |
| VIA VT6415 PATA IDE Host Controller                                              | 3        | 0.63%   |
| SanDisk PC SN520 x2 M.2 2230 NVMe SSD                                            | 3        | 0.63%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 3        | 0.63%   |
| JMicron JMB363 SATA/IDE Controller                                               | 3        | 0.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3        | 0.63%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3        | 0.63%   |
| Intel unknown                                                                    | 3        | 0.63%   |
| Intel SATA Controller [RAID mode]                                                | 3        | 0.63%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 281      | 69.04%  |
| NVMe | 61       | 14.99%  |
| IDE  | 44       | 10.81%  |
| RAID | 12       | 2.95%   |
| SCSI | 5        | 1.23%   |
| SAS  | 4        | 0.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 273      | 83.49%  |
| AMD     | 53       | 16.21%  |
| Unknown | 1        | 0.31%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel Celeron N5105 @ 2.00GHz        | 24       | 7.23%   |
| Intel Celeron CPU J3160 @ 1.60GHz    | 12       | 3.61%   |
| Intel Core i5-3570 CPU @ 3.40GHz     | 9        | 2.71%   |
| Intel Celeron J4125 CPU @ 2.00GHz    | 9        | 2.71%   |
| Intel Core i5-6500 CPU @ 3.20GHz     | 7        | 2.11%   |
| Intel Core i5-4590 CPU @ 3.30GHz     | 7        | 2.11%   |
| Intel Core i5-4570 CPU @ 3.20GHz     | 7        | 2.11%   |
| Intel Core i5-8500 CPU @ 3.00GHz     | 5        | 1.51%   |
| Intel Core i5-4570TE CPU @ 2.70GHz   | 5        | 1.51%   |
| AMD GX-412TC SOC                     | 5        | 1.51%   |
| Intel Xeon                           | 4        | 1.2%    |
| Intel N100                           | 4        | 1.2%    |
| Intel Core i7-3770 CPU @ 3.40GHz     | 4        | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz    | 4        | 1.2%    |
| Intel Core i5-3470 CPU @ 3.20GHz     | 4        | 1.2%    |
| Intel Core i5-2400 CPU @ 3.10GHz     | 4        | 1.2%    |
| Intel Core i3-2100 CPU @ 3.10GHz     | 4        | 1.2%    |
| AMD Ryzen 5 2600 Six-Core Processor  | 4        | 1.2%    |
| Intel Pentium Silver N6005 @ 2.00GHz | 3        | 0.9%    |
| Intel Pentium CPU G4560 @ 3.50GHz    | 3        | 0.9%    |
| Intel Core i7-9700K CPU @ 3.60GHz    | 3        | 0.9%    |
| Intel Core i7-8700 CPU @ 3.20GHz     | 3        | 0.9%    |
| Intel Core i5 CPU 650 @ 3.20GHz      | 3        | 0.9%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz | 3        | 0.9%    |
| Intel Celeron J6413 @ 1.80GHz        | 3        | 0.9%    |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz  | 2        | 0.6%    |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz  | 2        | 0.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz    | 2        | 0.6%    |
| Intel Core i7-7700 CPU @ 3.60GHz     | 2        | 0.6%    |
| Intel Core i7-6700 CPU @ 3.40GHz     | 2        | 0.6%    |
| Intel Core i7-4790K CPU @ 4.00GHz    | 2        | 0.6%    |
| Intel Core i7-2600 CPU @ 3.40GHz     | 2        | 0.6%    |
| Intel Core i5-8400 CPU @ 2.80GHz     | 2        | 0.6%    |
| Intel Core i5-4670 CPU @ 3.40GHz     | 2        | 0.6%    |
| Intel Core i5-4590S CPU @ 3.00GHz    | 2        | 0.6%    |
| Intel Core i5-4460 CPU @ 3.20GHz     | 2        | 0.6%    |
| Intel Core i5-4430 CPU @ 3.00GHz     | 2        | 0.6%    |
| Intel Core i5-3470T CPU @ 2.90GHz    | 2        | 0.6%    |
| Intel Core i5-2500 CPU @ 3.30GHz     | 2        | 0.6%    |
| Intel Core i3-6100T CPU @ 3.20GHz    | 2        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 88       | 26.59%  |
| Intel Celeron           | 63       | 19.03%  |
| Intel Core i7           | 29       | 8.76%   |
| Intel Core i3           | 28       | 8.46%   |
| Intel Xeon              | 23       | 6.95%   |
| Other                   | 13       | 3.93%   |
| Intel Atom              | 10       | 3.02%   |
| AMD Ryzen 5             | 10       | 3.02%   |
| Intel Pentium           | 7        | 2.11%   |
| AMD GX                  | 7        | 2.11%   |
| AMD FX                  | 7        | 2.11%   |
| Intel Core 2 Duo        | 5        | 1.51%   |
| AMD Ryzen 9             | 5        | 1.51%   |
| Intel Core 2 Quad       | 4        | 1.21%   |
| AMD Ryzen 7             | 4        | 1.21%   |
| Intel Pentium Silver    | 3        | 0.91%   |
| Intel Pentium Dual-Core | 3        | 0.91%   |
| AMD Athlon 64 X2        | 3        | 0.91%   |
| AMD Ryzen 3             | 2        | 0.6%    |
| AMD Athlon II X2        | 2        | 0.6%    |
| AMD Athlon              | 2        | 0.6%    |
| Intel Pentium 4         | 1        | 0.3%    |
| Intel Core 2            | 1        | 0.3%    |
| AMD Ryzen Embedded      | 1        | 0.3%    |
| AMD Ryzen 5 PRO         | 1        | 0.3%    |
| AMD Phenom II X6        | 1        | 0.3%    |
| AMD Phenom              | 1        | 0.3%    |
| AMD G                   | 1        | 0.3%    |
| AMD EPYC                | 1        | 0.3%    |
| AMD E                   | 1        | 0.3%    |
| AMD Athlon Dual Core    | 1        | 0.3%    |
| AMD A6                  | 1        | 0.3%    |
| AMD A4                  | 1        | 0.3%    |
| AMD A10                 | 1        | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 186      | 56.53%  |
| 2       | 68       | 20.67%  |
| 6       | 23       | 6.99%   |
| 8       | 17       | 5.17%   |
| 12      | 12       | 3.65%   |
| 32      | 5        | 1.52%   |
| 16      | 5        | 1.52%   |
| Unknown | 4        | 1.22%   |
| 10      | 3        | 0.91%   |
| 24      | 2        | 0.61%   |
| 20      | 1        | 0.3%    |
| 11      | 1        | 0.3%    |
| 5       | 1        | 0.3%    |
| 3       | 1        | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 318      | 98.45%  |
| 2       | 3        | 0.93%   |
| Unknown | 2        | 0.62%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 223      | 68.62%  |
| 2       | 98       | 30.15%  |
| Unknown | 4        | 1.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 48       | 14.46%  |
| Unknown       | 48       | 14.46%  |
| KabyLake      | 35       | 10.54%  |
| IvyBridge     | 27       | 8.13%   |
| SandyBridge   | 21       | 6.33%   |
| Skylake       | 18       | 5.42%   |
| Silvermont    | 18       | 5.42%   |
| Penryn        | 12       | 3.61%   |
| Goldmont plus | 12       | 3.61%   |
| Zen+          | 9        | 2.71%   |
| Westmere      | 9        | 2.71%   |
| Goldmont      | 9        | 2.71%   |
| Piledriver    | 8        | 2.41%   |
| Zen 3         | 6        | 1.81%   |
| Zen           | 6        | 1.81%   |
| Broadwell     | 6        | 1.81%   |
| Puma          | 5        | 1.51%   |
| K10           | 5        | 1.51%   |
| CometLake     | 5        | 1.51%   |
| Nehalem       | 4        | 1.2%    |
| K8 Hammer     | 4        | 1.2%    |
| Jaguar        | 4        | 1.2%    |
| Core          | 3        | 0.9%    |
| Bonnell       | 3        | 0.9%    |
| Zen 2         | 2        | 0.6%    |
| Bobcat        | 2        | 0.6%    |
| TigerLake     | 1        | 0.3%    |
| NetBurst      | 1        | 0.3%    |
| Bulldozer     | 1        | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 225      | 70.09%  |
| Nvidia                     | 42       | 13.08%  |
| AMD                        | 39       | 12.15%  |
| ASPEED Technology          | 10       | 3.12%   |
| Matrox Electronics Systems | 5        | 1.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 33       | 10.06%  |
| Intel JasperLake [UHD Graphics]                                                          | 29       | 8.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17       | 5.18%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 15       | 4.57%   |
| Intel HD Graphics 530                                                                    | 15       | 4.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14       | 4.27%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12       | 3.66%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12       | 3.66%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 10       | 3.05%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 9        | 2.74%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 6        | 1.83%   |
| Intel HD Graphics 630                                                                    | 6        | 1.83%   |
| Intel HD Graphics 500                                                                    | 5        | 1.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5        | 1.52%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 5        | 1.52%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 5        | 1.52%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 1.22%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 4        | 1.22%   |
| Intel HD Graphics 620                                                                    | 4        | 1.22%   |
| Intel HD Graphics 610                                                                    | 4        | 1.22%   |
| Nvidia GM107GL [Quadro K620]                                                             | 3        | 0.91%   |
| Intel UHD Graphics 620                                                                   | 3        | 0.91%   |
| Intel HD Graphics 5500                                                                   | 3        | 0.91%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3        | 0.91%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 0.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 0.91%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2        | 0.61%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 0.61%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 0.61%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 0.61%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 2        | 0.61%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 2        | 0.61%   |
| Nvidia GF119 [NVS 315]                                                                   | 2        | 0.61%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 0.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 0.61%   |
| Intel AlderLake-S GT1                                                                    | 2        | 0.61%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 2        | 0.61%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 0.61%   |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 213      | 64.35%  |
| 1 x Nvidia     | 40       | 12.08%  |
| 1 x AMD        | 36       | 10.88%  |
| Other          | 14       | 4.23%   |
| 1 x ASPEED     | 9        | 2.72%   |
| 2 x Intel      | 7        | 2.11%   |
| 1 x Matrox     | 5        | 1.51%   |
| 2 x AMD        | 3        | 0.91%   |
| Intel + Nvidia | 2        | 0.6%    |
| Intel + ASPEED | 1        | 0.3%    |
| Intel + AMD    | 1        | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 290      | 88.41%  |
| Proprietary | 23       | 7.01%   |
| Unknown     | 15       | 4.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 291      | 89.54%  |
| 1.01-2.0   | 9        | 2.77%   |
| 0.51-1.0   | 9        | 2.77%   |
| 3.01-4.0   | 5        | 1.54%   |
| 7.01-8.0   | 4        | 1.23%   |
| 5.01-6.0   | 3        | 0.92%   |
| 8.01-16.0  | 2        | 0.62%   |
| 2.01-3.0   | 1        | 0.31%   |
| 0.01-0.5   | 1        | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 9        | 17.65%  |
| Dell                 | 6        | 11.76%  |
| BenQ                 | 6        | 11.76%  |
| Samsung Electronics  | 4        | 7.84%   |
| Sony                 | 3        | 5.88%   |
| LG Electronics       | 3        | 5.88%   |
| Lenovo               | 3        | 5.88%   |
| ASUSTek Computer     | 3        | 5.88%   |
| AOC                  | 3        | 5.88%   |
| Acer                 | 3        | 5.88%   |
| Hewlett-Packard      | 2        | 3.92%   |
| ViewSonic            | 1        | 1.96%   |
| Videoseven           | 1        | 1.96%   |
| Toshiba              | 1        | 1.96%   |
| LTV                  | 1        | 1.96%   |
| Insignia             | 1        | 1.96%   |
| Ancor Communications | 1        | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Sony LCD Monitor TV XV 1920x1080                                       | 2        | 3.64%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 2        | 3.64%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 2        | 3.64%   |
| ViewSonic LCD Monitor VSCFA2B 1920x1080 510x290mm 23.1-inch            | 1        | 1.82%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1        | 1.82%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 1        | 1.82%   |
| Sony TV  *30 SNY05D1 3840x2160 1660x930mm 74.9-inch                    | 1        | 1.82%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 1        | 1.82%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1210x680mm 54.6-inch | 1        | 1.82%   |
| LTV LTV1280M1A LTV0A3C 1024x768 800x450mm 36.1-inch                    | 1        | 1.82%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                      | 1        | 1.82%   |
| LG Electronics LCD Monitor LG Ultra HD 7680x2160                       | 1        | 1.82%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1        | 1.82%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1        | 1.82%   |
| Lenovo LEN-M93z-B  LEN0093 1920x1080 510x290mm 23.1-inch               | 1        | 1.82%   |
| Insignia LCD Monitor BBY0050 1920x1080 700x400mm 31.7-inch             | 1        | 1.82%   |
| Hewlett-Packard All-in-One HWP4218 1600x900 440x250mm 19.9-inch        | 1        | 1.82%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch             | 1        | 1.82%   |
| Goldstar W2442 GSM56D9 1920x1080 530x300mm 24.0-inch                   | 1        | 1.82%   |
| Goldstar W2052 GSM4E88 1680x1050 470x300mm 22.0-inch                   | 1        | 1.82%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                   | 1        | 1.82%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 1        | 1.82%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch            | 1        | 1.82%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch            | 1        | 1.82%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch            | 1        | 1.82%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch               | 1        | 1.82%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 1.82%   |
| Goldstar LG FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch              | 1        | 1.82%   |
| Goldstar LCD Monitor GSM76F5 1920x1080 700x390mm 31.5-inch             | 1        | 1.82%   |
| Dell SE2722H DELD116 1920x1080 600x340mm 27.2-inch                     | 1        | 1.82%   |
| Dell P3222QE DEL4246 3840x2160 700x390mm 31.5-inch                     | 1        | 1.82%   |
| Dell P2311H DEL4067 1920x1080 510x290mm 23.1-inch                      | 1        | 1.82%   |
| Dell P2219H DELA114 1920x1080 480x270mm 21.7-inch                      | 1        | 1.82%   |
| Dell LCD Monitor DELF003 1440x900 410x260mm 19.1-inch                  | 1        | 1.82%   |
| Dell 2001FP DELA008 1600x1200 410x310mm 20.2-inch                      | 1        | 1.82%   |
| BenQ XL2430T BNQ7F3D 1920x1080 530x300mm 24.0-inch                     | 1        | 1.82%   |
| BenQ LCD Monitor PD3200Q                                               | 1        | 1.82%   |
| BenQ LCD Monitor GW2765                                                | 1        | 1.82%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                      | 1        | 1.82%   |
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                      | 1        | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 27       | 54%     |
| 3840x2160 (4K)     | 6        | 12%     |
| 2560x1440 (QHD)    | 2        | 4%      |
| 1680x1050 (WSXGA+) | 2        | 4%      |
| 1440x900 (WXGA+)   | 2        | 4%      |
| Unknown            | 2        | 4%      |
| 7680x2160          | 1        | 2%      |
| 3440x1440          | 1        | 2%      |
| 2560x1080          | 1        | 2%      |
| 1920x1200 (WUXGA)  | 1        | 2%      |
| 1600x900 (HD+)     | 1        | 2%      |
| 1600x1200          | 1        | 2%      |
| 1366x768 (WXGA)    | 1        | 2%      |
| 1280x1024 (SXGA)   | 1        | 2%      |
| 1024x768 (XGA)     | 1        | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 12       | 23.08%  |
| 21      | 7        | 13.46%  |
| Unknown | 7        | 13.46%  |
| 27      | 6        | 11.54%  |
| 19      | 4        | 7.69%   |
| 54      | 3        | 5.77%   |
| 23      | 3        | 5.77%   |
| 34      | 2        | 3.85%   |
| 31      | 2        | 3.85%   |
| 22      | 2        | 3.85%   |
| 74      | 1        | 1.92%   |
| 36      | 1        | 1.92%   |
| 20      | 1        | 1.92%   |
| 18      | 1        | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 39.22%  |
| 401-500     | 14       | 27.45%  |
| Unknown     | 7        | 13.73%  |
| 701-800     | 3        | 5.88%   |
| 1001-1500   | 3        | 5.88%   |
| 601-700     | 2        | 3.92%   |
| 351-400     | 1        | 1.96%   |
| 1501-2000   | 1        | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 34       | 69.39%  |
| Unknown | 7        | 14.29%  |
| 16/10   | 4        | 8.16%   |
| 21/9    | 2        | 4.08%   |
| 5/4     | 1        | 2.04%   |
| 4/3     | 1        | 2.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 21       | 41.18%  |
| Unknown        | 7        | 13.73%  |
| 301-350        | 6        | 11.76%  |
| 151-200        | 5        | 9.8%    |
| More than 1000 | 4        | 7.84%   |
| 351-500        | 4        | 7.84%   |
| 251-300        | 2        | 3.92%   |
| 141-150        | 1        | 1.96%   |
| 501-1000       | 1        | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 33       | 63.46%  |
| 101-120 | 9        | 17.31%  |
| Unknown | 7        | 13.46%  |
| 1-50    | 1        | 1.92%   |
| 161-240 | 1        | 1.92%   |
| 121-160 | 1        | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 268      | 81.96%  |
| 1     | 51       | 15.6%   |
| 2     | 8        | 2.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 259      | 57.56%  |
| Realtek Semiconductor           | 126      | 28%     |
| Broadcom                        | 21       | 4.67%   |
| Qualcomm Atheros                | 10       | 2.22%   |
| Mellanox Technologies           | 4        | 0.89%   |
| MediaTek                        | 4        | 0.89%   |
| Solarflare Communications       | 3        | 0.67%   |
| Chelsio Communications          | 3        | 0.67%   |
| Ralink                          | 2        | 0.44%   |
| Marvell Technology Group        | 2        | 0.44%   |
| IMC Networks                    | 2        | 0.44%   |
| 3Com                            | 2        | 0.44%   |
| U-Blox                          | 1        | 0.22%   |
| Qualcomm Atheros Communications | 1        | 0.22%   |
| QLogic                          | 1        | 0.22%   |
| NetGear                         | 1        | 0.22%   |
| Linksys                         | 1        | 0.22%   |
| Hewlett-Packard                 | 1        | 0.22%   |
| Google                          | 1        | 0.22%   |
| D-Link System                   | 1        | 0.22%   |
| D-Link                          | 1        | 0.22%   |
| Aquantia                        | 1        | 0.22%   |
| Apple                           | 1        | 0.22%   |
| American Megatrends             | 1        | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 106      | 18.86%  |
| Intel I211 Gigabit Network Connection                                         | 35       | 6.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 27       | 4.8%    |
| Intel Ethernet Controller I225-V                                              | 26       | 4.63%   |
| Intel Ethernet Connection I217-LM                                             | 25       | 4.45%   |
| Intel 82574L Gigabit Network Connection                                       | 25       | 4.45%   |
| Intel Ethernet Controller I226-V                                              | 21       | 3.74%   |
| Intel I350 Gigabit Network Connection                                         | 18       | 3.2%    |
| Intel 82576 Gigabit Network Connection                                        | 15       | 2.67%   |
| Intel I210 Gigabit Network Connection                                         | 11       | 1.96%   |
| Intel 82583V Gigabit Network Connection                                       | 11       | 1.96%   |
| Realtek RTL8125 2.5GbE Controller                                             | 10       | 1.78%   |
| Intel 82580 Gigabit Network Connection                                        | 8        | 1.42%   |
| Intel Wi-Fi 6 AX200                                                           | 7        | 1.25%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7        | 1.25%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7        | 1.25%   |
| Intel Ethernet Connection (2) I219-V                                          | 6        | 1.07%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6        | 1.07%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 6        | 1.07%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 4        | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                                         | 4        | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 4        | 0.71%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 4        | 0.71%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4        | 0.71%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4        | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 3        | 0.53%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3        | 0.53%   |
| Intel Wireless 7260                                                           | 3        | 0.53%   |
| Intel Wireless 3165                                                           | 3        | 0.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 3        | 0.53%   |
| Intel Ethernet Controller X550                                                | 3        | 0.53%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3        | 0.53%   |
| Intel Ethernet Connection (2) I218-LM                                         | 3        | 0.53%   |
| Intel 82578DM Gigabit Network Connection                                      | 3        | 0.53%   |
| Intel 82575EB Gigabit Network Connection                                      | 3        | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.53%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3        | 0.53%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 3        | 0.53%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3        | 0.53%   |
| Solarflare SFC9020 10G Ethernet Controller                                    | 2        | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 33       | 48.53%  |
| Realtek Semiconductor           | 13       | 19.12%  |
| Qualcomm Atheros                | 8        | 11.76%  |
| MediaTek                        | 4        | 5.88%   |
| Ralink                          | 2        | 2.94%   |
| IMC Networks                    | 2        | 2.94%   |
| Broadcom                        | 2        | 2.94%   |
| Qualcomm Atheros Communications | 1        | 1.47%   |
| NetGear                         | 1        | 1.47%   |
| Linksys                         | 1        | 1.47%   |
| D-Link                          | 1        | 1.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 7        | 10%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4        | 5.71%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 4        | 5.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3        | 4.29%   |
| Intel Wireless 7260                                                     | 3        | 4.29%   |
| Intel Wireless 3165                                                     | 3        | 4.29%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3        | 4.29%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2        | 2.86%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2        | 2.86%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2        | 2.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2        | 2.86%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2        | 2.86%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2        | 2.86%   |
| Intel CNVi: Wi-Fi                                                       | 2        | 2.86%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 2        | 2.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 1.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.43%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.43%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1        | 1.43%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1        | 1.43%   |
| Realtek Bluetooth Adapter                                               | 1        | 1.43%   |
| Ralink RT5592 PCIe Wireless Network Adapter                             | 1        | 1.43%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1        | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1        | 1.43%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 1.43%   |
| Qualcomm Atheros AR958x 802.11abgn Wireless Network Adapter             | 1        | 1.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1        | 1.43%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 1.43%   |
| NetGear A6200 802.11a/b/g/n/ac Wireless Adapter [Broadcom BCM43526]     | 1        | 1.43%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 1.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1        | 1.43%   |
| Linksys WUSB54G v4 802.11g Adapter [Ralink RT2500USB]                   | 1        | 1.43%   |
| Intel Wireless 8260                                                     | 1        | 1.43%   |
| Intel Wireless 7265                                                     | 1        | 1.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1        | 1.43%   |
| Intel Centrino Wireless-N 2230                                          | 1        | 1.43%   |
| Intel Centrino Wireless-N 105                                           | 1        | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1        | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 1.43%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]    | 1        | 1.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 244      | 60.7%   |
| Realtek Semiconductor     | 121      | 30.1%   |
| Broadcom                  | 19       | 4.73%   |
| Solarflare Communications | 3        | 0.75%   |
| Chelsio Communications    | 3        | 0.75%   |
| Qualcomm Atheros          | 2        | 0.5%    |
| Marvell Technology Group  | 2        | 0.5%    |
| 3Com                      | 2        | 0.5%    |
| QLogic                    | 1        | 0.25%   |
| Google                    | 1        | 0.25%   |
| D-Link System             | 1        | 0.25%   |
| Aquantia                  | 1        | 0.25%   |
| Apple                     | 1        | 0.25%   |
| American Megatrends       | 1        | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 106      | 21.95%  |
| Intel I211 Gigabit Network Connection                                         | 35       | 7.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 27       | 5.59%   |
| Intel Ethernet Controller I225-V                                              | 26       | 5.38%   |
| Intel Ethernet Connection I217-LM                                             | 25       | 5.18%   |
| Intel 82574L Gigabit Network Connection                                       | 25       | 5.18%   |
| Intel Ethernet Controller I226-V                                              | 21       | 4.35%   |
| Intel I350 Gigabit Network Connection                                         | 18       | 3.73%   |
| Intel 82576 Gigabit Network Connection                                        | 15       | 3.11%   |
| Intel I210 Gigabit Network Connection                                         | 11       | 2.28%   |
| Intel 82583V Gigabit Network Connection                                       | 11       | 2.28%   |
| Realtek RTL8125 2.5GbE Controller                                             | 10       | 2.07%   |
| Intel 82580 Gigabit Network Connection                                        | 8        | 1.66%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7        | 1.45%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7        | 1.45%   |
| Intel Ethernet Connection (2) I219-V                                          | 6        | 1.24%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6        | 1.24%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 6        | 1.24%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 4        | 0.83%   |
| Intel Ethernet Connection (7) I219-LM                                         | 4        | 0.83%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4        | 0.83%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4        | 0.83%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3        | 0.62%   |
| Intel Ethernet Controller X550                                                | 3        | 0.62%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3        | 0.62%   |
| Intel Ethernet Connection (2) I218-LM                                         | 3        | 0.62%   |
| Intel 82578DM Gigabit Network Connection                                      | 3        | 0.62%   |
| Intel 82575EB Gigabit Network Connection                                      | 3        | 0.62%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.62%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3        | 0.62%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 3        | 0.62%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3        | 0.62%   |
| Solarflare SFC9020 10G Ethernet Controller                                    | 2        | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 0.41%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 2        | 0.41%   |
| Intel Ethernet Connection X553/X557-AT 10GBASE-T                              | 2        | 0.41%   |
| Intel Ethernet Connection X553 1GbE                                           | 2        | 0.41%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 2        | 0.41%   |
| Intel Ethernet Connection I354                                                | 2        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 321      | 80.86%  |
| WiFi     | 67       | 16.88%  |
| Unknown  | 7        | 1.76%   |
| Modem    | 2        | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 310      | 97.18%  |
| WiFi     | 9        | 2.82%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 77       | 23.4%   |
| 2     | 67       | 20.36%  |
| 3     | 65       | 19.76%  |
| 1     | 51       | 15.5%   |
| 5     | 30       | 9.12%   |
| 6     | 22       | 6.69%   |
| 7     | 6        | 1.82%   |
| 8     | 5        | 1.52%   |
| 0     | 3        | 0.91%   |
| 12    | 1        | 0.3%    |
| 10    | 1        | 0.3%    |
| 9     | 1        | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 281      | 84.64%  |
| Yes  | 51       | 15.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 28       | 60.87%  |
| Cambridge Silicon Radio         | 6        | 13.04%  |
| Realtek Semiconductor           | 4        | 8.7%    |
| Foxconn / Hon Hai               | 3        | 6.52%   |
| IMC Networks                    | 2        | 4.35%   |
| Qualcomm Atheros Communications | 1        | 2.17%   |
| MediaTek                        | 1        | 2.17%   |
| Apple                           | 1        | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Intel AX201 Bluetooth                                | 7        | 14.89%  |
| Intel Bluetooth wireless interface                   | 6        | 12.77%  |
| Intel AX200 Bluetooth                                | 6        | 12.77%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 6        | 12.77%  |
| Intel Wireless-AC 3168 Bluetooth                     | 4        | 8.51%   |
| Realtek Bluetooth Adapter                            | 3        | 6.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 2        | 4.26%   |
| Intel AX210 Bluetooth                                | 2        | 4.26%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter            | 2        | 4.26%   |
| Realtek  Bluetooth 4.2 Adapter                       | 1        | 2.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 1        | 2.13%   |
| MediaTek RZ608 Bluetooth Adapter                     | 1        | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver        | 1        | 2.13%   |
| Intel AX211 Bluetooth                                | 1        | 2.13%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip | 1        | 2.13%   |
| IMC Networks MediaTek Bluetooth Adapter              | 1        | 2.13%   |
| Foxconn / Hon Hai Bluetooth USB Module               | 1        | 2.13%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                 | 1        | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 211      | 65.53%  |
| AMD                                          | 49       | 15.22%  |
| Nvidia                                       | 40       | 12.42%  |
| C-Media Electronics                          | 5        | 1.55%   |
| KTMicro                                      | 4        | 1.24%   |
| Logitech                                     | 3        | 0.93%   |
| ASUSTek Computer                             | 2        | 0.62%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.31%   |
| Yamaha                                       | 1        | 0.31%   |
| Texas Instruments                            | 1        | 0.31%   |
| SteelSeries ApS                              | 1        | 0.31%   |
| Plantronics                                  | 1        | 0.31%   |
| Micro Star International                     | 1        | 0.31%   |
| Elgato Systems                               | 1        | 0.31%   |
| Creative Labs                                | 1        | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 31       | 8.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 30       | 7.85%   |
| Intel Jasper Lake HD Audio                                                                        | 29       | 7.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20       | 5.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16       | 4.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13       | 3.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 12       | 3.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10       | 2.62%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10       | 2.62%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9        | 2.36%   |
| Intel 200 Series PCH HD Audio                                                                     | 9        | 2.36%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7        | 1.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6        | 1.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6        | 1.57%   |
| AMD FCH Azalia Controller                                                                         | 6        | 1.57%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6        | 1.57%   |
| Nvidia High Definition Audio Controller                                                           | 5        | 1.31%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5        | 1.31%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5        | 1.31%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 5        | 1.31%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 5        | 1.31%   |
| Intel 8 Series HD Audio Controller                                                                | 5        | 1.31%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5        | 1.31%   |
| KTMicro KT USB Audio                                                                              | 4        | 1.05%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4        | 1.05%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4        | 1.05%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4        | 1.05%   |
| Intel Broadwell-U Audio Controller                                                                | 4        | 1.05%   |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 4        | 1.05%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4        | 1.05%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3        | 0.79%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3        | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 0.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3        | 0.79%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3        | 0.79%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 0.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3        | 0.79%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 3        | 0.79%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Samsung Electronics          | 54       | 15%     |
| Kingston                     | 54       | 15%     |
| SK hynix                     | 47       | 13.06%  |
| Corsair                      | 33       | 9.17%   |
| Unknown                      | 30       | 8.33%   |
| Crucial                      | 29       | 8.06%   |
| Micron Technology            | 24       | 6.67%   |
| G.Skill                      | 22       | 6.11%   |
| Unknown                      | 12       | 3.33%   |
| A-DATA Technology            | 8        | 2.22%   |
| Ramaxel Technology           | 6        | 1.67%   |
| Apacer                       | 6        | 1.67%   |
| Unknown (0x0C26)             | 4        | 1.11%   |
| Team                         | 4        | 1.11%   |
| Patriot                      | 4        | 1.11%   |
| OCZ                          | 3        | 0.83%   |
| Nanya Technology             | 3        | 0.83%   |
| Timetec                      | 2        | 0.56%   |
| AMD                          | 2        | 0.56%   |
| Wodposit                     | 1        | 0.28%   |
| V-Color                      | 1        | 0.28%   |
| Unknown (ABCD)               | 1        | 0.28%   |
| Unknown (0x0DD5)             | 1        | 0.28%   |
| Transcend                    | 1        | 0.28%   |
| Toshiba                      | 1        | 0.28%   |
| Silicon Power                | 1        | 0.28%   |
| PNY                          | 1        | 0.28%   |
| Patriot Memory (PDP Systems) | 1        | 0.28%   |
| Lexar Co Limited             | 1        | 0.28%   |
| Elpida                       | 1        | 0.28%   |
| Cors                         | 1        | 0.28%   |
| Avant                        | 1        | 0.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown                                                 | 12       | 3.07%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 5        | 1.28%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s     | 5        | 1.28%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 5        | 1.28%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s | 5        | 1.28%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 4        | 1.02%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s     | 4        | 1.02%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s      | 4        | 1.02%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 3        | 0.77%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s    | 3        | 0.77%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s     | 3        | 0.77%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s     | 3        | 0.77%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s     | 3        | 0.77%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s  | 3        | 0.77%   |
| Unknown RAM Module 8GB 1600MT/s                         | 2        | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 2        | 0.51%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 0.51%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 2        | 0.51%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 2        | 0.51%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s              | 2        | 0.51%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s    | 2        | 0.51%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.51%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.51%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s    | 2        | 0.51%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s    | 2        | 0.51%   |
| SK hynix RAM HMA451R7AFR8N-TF 4GB RIMM DDR4 2133MT/s    | 2        | 0.51%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 2        | 0.51%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s     | 2        | 0.51%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 0.51%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 0.51%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 2667MT/s     | 2        | 0.51%   |
| Samsung RAM M378A1K43BB1-CPB 8GB DIMM DDR4 3000MT/s     | 2        | 0.51%   |
| Ramaxel RAM RMUA5090KE68H9F2133 4GB DIMM DDR4 2133MT/s  | 2        | 0.51%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s   | 2        | 0.51%   |
| Micron RAM 9ASF51272PZ-2G1A2 4GB RIMM DDR4 2133MT/s     | 2        | 0.51%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s    | 2        | 0.51%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s   | 2        | 0.51%   |
| Micron RAM 18ASF2G72HZ-2G6E1 16GB SODIMM DDR4 2667MT/s  | 2        | 0.51%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s    | 2        | 0.51%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s      | 2        | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 135      | 43.41%  |
| DDR4    | 133      | 42.77%  |
| Unknown | 13       | 4.18%   |
| DDR2    | 12       | 3.86%   |
| DDR5    | 7        | 2.25%   |
| SDRAM   | 5        | 1.61%   |
| LPDDR4  | 3        | 0.96%   |
| DDR     | 2        | 0.64%   |
| LPDDR5  | 1        | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 202      | 66.23%  |
| SODIMM       | 95       | 31.15%  |
| RIMM         | 3        | 0.98%   |
| Row Of Chips | 2        | 0.66%   |
| Unknown      | 2        | 0.66%   |
| FB-DIMM      | 1        | 0.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 123      | 36.07%  |
| 4096  | 109      | 31.96%  |
| 16384 | 43       | 12.61%  |
| 2048  | 42       | 12.32%  |
| 1024  | 12       | 3.52%   |
| 32768 | 10       | 2.93%   |
| 512   | 2        | 0.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 102      | 30.45%  |
| 1333    | 44       | 13.13%  |
| 3200    | 39       | 11.64%  |
| 2667    | 34       | 10.15%  |
| 2400    | 30       | 8.96%   |
| 2133    | 22       | 6.57%   |
| 800     | 11       | 3.28%   |
| 2666    | 8        | 2.39%   |
| 4800    | 5        | 1.49%   |
| 3000    | 5        | 1.49%   |
| 667     | 5        | 1.49%   |
| Unknown | 5        | 1.49%   |
| 1067    | 4        | 1.19%   |
| 1066    | 4        | 1.19%   |
| 3600    | 3        | 0.9%    |
| 6400    | 2        | 0.6%    |
| 1866    | 2        | 0.6%    |
| 400     | 2        | 0.6%    |
| 5600    | 1        | 0.3%    |
| 5200    | 1        | 0.3%    |
| 3733    | 1        | 0.3%    |
| 3400    | 1        | 0.3%    |
| 2933    | 1        | 0.3%    |
| 1334    | 1        | 0.3%    |
| 533     | 1        | 0.3%    |
| 333     | 1        | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 50%     |
| Brother Industries | 2        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| HP LaserJet 2200          | 1        | 25%     |
| HP Color LaserJet CP1215  | 1        | 25%     |
| Brother HL-L5200DW series | 1        | 25%     |
| Brother HL-L2300D series  | 1        | 25%     |

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


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 220 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 3        | 60%     |
| Microdia            | 1        | 20%     |
| Chicony Electronics | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Microdia JOYACCESS JA-Webcam  | 1        | 20%     |
| Logitech Webcam C310          | 1        | 20%     |
| Logitech HD Pro Webcam C920   | 1        | 20%     |
| Logitech BRIO Ultra HD Webcam | 1        | 20%     |
| Chicony HP 0.3MP Webcam       | 1        | 20%     |

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
| 1     | 197      | 59.16%  |
| 0     | 86       | 25.83%  |
| 2     | 37       | 11.11%  |
| 3     | 8        | 2.4%    |
| 4     | 5        | 1.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 221      | 77%     |
| Net/wireless             | 20       | 6.97%   |
| Bluetooth                | 19       | 6.62%   |
| Firewire controller      | 7        | 2.44%   |
| Sound                    | 5        | 1.74%   |
| Net/ethernet             | 5        | 1.74%   |
| Network                  | 4        | 1.39%   |
| Card reader              | 3        | 1.05%   |
| Storage/raid             | 2        | 0.7%    |
| Graphics card            | 1        | 0.35%   |

