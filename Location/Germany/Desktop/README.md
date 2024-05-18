BSD in Germany - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Germany.

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

Total: 2275

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [0aee6a395a](https://bsd-hardware.info/?probe=0aee6a395a) | May 08, 2024 |
| AAEON         | FWS-2365 V1.0               | [e7f5d7ff38](https://bsd-hardware.info/?probe=e7f5d7ff38) | May 07, 2024 |
| Protectli     | FW6 Ver                     | [b56fbf51c6](https://bsd-hardware.info/?probe=b56fbf51c6) | May 07, 2024 |
| Dell          | 0DR845                      | [03e1ebc97e](https://bsd-hardware.info/?probe=03e1ebc97e) | May 07, 2024 |
| Unknown       | Unknown                     | [676aa9858a](https://bsd-hardware.info/?probe=676aa9858a) | May 06, 2024 |
| MSI           | MS-7369                     | [65686a6412](https://bsd-hardware.info/?probe=65686a6412) | May 05, 2024 |
| SHANGZHAOY... | B85M-PRO V1.1               | [873fd32471](https://bsd-hardware.info/?probe=873fd32471) | May 05, 2024 |
| Unknown       | Unknown                     | [5dc8d187ee](https://bsd-hardware.info/?probe=5dc8d187ee) | May 04, 2024 |
| Lanner        | FW-7543 B-GA                | [d999a95489](https://bsd-hardware.info/?probe=d999a95489) | May 03, 2024 |
| Protectli     | FW4B                        | [db66e06618](https://bsd-hardware.info/?probe=db66e06618) | May 02, 2024 |
| AWOW          | AK10                        | [a8fbc35162](https://bsd-hardware.info/?probe=a8fbc35162) | May 01, 2024 |
| Gigabyte      | B760I AORUS PRO DDR4        | [f6606ff3aa](https://bsd-hardware.info/?probe=f6606ff3aa) | May 01, 2024 |
| MSI           | AM1I                        | [148d52d171](https://bsd-hardware.info/?probe=148d52d171) | May 01, 2024 |
| Unknown       | Unknown                     | [39e9c3ddd2](https://bsd-hardware.info/?probe=39e9c3ddd2) | Apr 30, 2024 |
| PC Engines    | APU2                        | [a6953a27eb](https://bsd-hardware.info/?probe=a6953a27eb) | Apr 29, 2024 |
| ASRock        | Q1900M                      | [7f61d481a6](https://bsd-hardware.info/?probe=7f61d481a6) | Apr 29, 2024 |
| PC Engines    | APU2                        | [f18a73e413](https://bsd-hardware.info/?probe=f18a73e413) | Apr 28, 2024 |
| Unknown       | Unknown                     | [d45b3d4001](https://bsd-hardware.info/?probe=d45b3d4001) | Apr 27, 2024 |
| Unknown       | Unknown                     | [4da784940c](https://bsd-hardware.info/?probe=4da784940c) | Apr 27, 2024 |
| HP            | 859B                        | [5d8024a661](https://bsd-hardware.info/?probe=5d8024a661) | Apr 27, 2024 |
| Unknown       | Unknown                     | [2945a5ee0f](https://bsd-hardware.info/?probe=2945a5ee0f) | Apr 27, 2024 |
| AWOW          | AK10                        | [efb7761dc3](https://bsd-hardware.info/?probe=efb7761dc3) | Apr 26, 2024 |
| SJRC          | SJ-ADLN-6L                  | [eba48b51e7](https://bsd-hardware.info/?probe=eba48b51e7) | Apr 26, 2024 |
| Silicom       | 80300-0214-G01 R306         | [1fda8df8d0](https://bsd-hardware.info/?probe=1fda8df8d0) | Apr 25, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [328e9b0321](https://bsd-hardware.info/?probe=328e9b0321) | Apr 25, 2024 |
| Techvision    | TVI7309X B0                 | [f92008b628](https://bsd-hardware.info/?probe=f92008b628) | Apr 25, 2024 |
| Protectli     | VP2420                      | [540090badd](https://bsd-hardware.info/?probe=540090badd) | Apr 24, 2024 |
| CncTion       | N4505-4L B0                 | [ada59fa5ed](https://bsd-hardware.info/?probe=ada59fa5ed) | Apr 24, 2024 |
| Gigabyte      | N3150ND3V                   | [9e0cb28c91](https://bsd-hardware.info/?probe=9e0cb28c91) | Apr 24, 2024 |
| ASUSTek       | H81M-PLUS                   | [b549100edf](https://bsd-hardware.info/?probe=b549100edf) | Apr 23, 2024 |
| ASRock        | A320M Pro4-F                | [b02849b872](https://bsd-hardware.info/?probe=b02849b872) | Apr 23, 2024 |
| Dell          | 0NW6H5 A00                  | [565275ac34](https://bsd-hardware.info/?probe=565275ac34) | Apr 22, 2024 |
| Intel         | BOX-J41L4A V3.01            | [62124a50da](https://bsd-hardware.info/?probe=62124a50da) | Apr 22, 2024 |
| AAEON         | FWS-2280 V1.0               | [071a27c302](https://bsd-hardware.info/?probe=071a27c302) | Apr 22, 2024 |
| Unknown       | Unknown                     | [c3bd100494](https://bsd-hardware.info/?probe=c3bd100494) | Apr 22, 2024 |
| Lanner        | FW-7543 B-GA                | [02a165d26f](https://bsd-hardware.info/?probe=02a165d26f) | Apr 22, 2024 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [072d422490](https://bsd-hardware.info/?probe=072d422490) | Apr 22, 2024 |
| NF541         | 1.0                         | [25cc14f6c9](https://bsd-hardware.info/?probe=25cc14f6c9) | Apr 21, 2024 |
| AAEON         | FWS-2280 V1.0               | [003dbde912](https://bsd-hardware.info/?probe=003dbde912) | Apr 21, 2024 |
| Advantech     | NAMB-1010VC A101            | [e2a9d0cbff](https://bsd-hardware.info/?probe=e2a9d0cbff) | Apr 21, 2024 |
| CWWK          | MINIPC-G12                  | [9e0cee5f8e](https://bsd-hardware.info/?probe=9e0cee5f8e) | Apr 20, 2024 |
| Unknown       | Unknown                     | [71ac1fd7c5](https://bsd-hardware.info/?probe=71ac1fd7c5) | Apr 20, 2024 |
| Protectli     | FW4B                        | [a5c17e61f1](https://bsd-hardware.info/?probe=a5c17e61f1) | Apr 18, 2024 |
| SHANGZHAOY... | B85M-PRO V1.1               | [111bf86a64](https://bsd-hardware.info/?probe=111bf86a64) | Apr 18, 2024 |
| Unknown       | Unknown                     | [5dfaef985e](https://bsd-hardware.info/?probe=5dfaef985e) | Apr 18, 2024 |
| Protectli     | FW6 Ver                     | [f8c9b99afe](https://bsd-hardware.info/?probe=f8c9b99afe) | Apr 17, 2024 |
| ASRock        | N68-GS3 UCC                 | [8da917c311](https://bsd-hardware.info/?probe=8da917c311) | Apr 16, 2024 |
| Gigabyte      | Q670M D3H                   | [923a7e28d2](https://bsd-hardware.info/?probe=923a7e28d2) | Apr 16, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [44758d3d74](https://bsd-hardware.info/?probe=44758d3d74) | Apr 16, 2024 |
| PC Engines    | APU2                        | [a0db25b377](https://bsd-hardware.info/?probe=a0db25b377) | Apr 16, 2024 |
| ASRock        | H310CM-DVS                  | [61e73f301e](https://bsd-hardware.info/?probe=61e73f301e) | Apr 15, 2024 |
| Unknown       | Unknown                     | [c02b232857](https://bsd-hardware.info/?probe=c02b232857) | Apr 15, 2024 |
| Unknown       | J3160-4L                    | [1f2e61cf7d](https://bsd-hardware.info/?probe=1f2e61cf7d) | Apr 14, 2024 |
| Gigabyte      | N3150ND3V                   | [50cdb5f1c0](https://bsd-hardware.info/?probe=50cdb5f1c0) | Apr 13, 2024 |
| Dell          | 0GM819                      | [6140b5e6ad](https://bsd-hardware.info/?probe=6140b5e6ad) | Apr 12, 2024 |
| Dell          | 0NW6H5 A00                  | [850c749c00](https://bsd-hardware.info/?probe=850c749c00) | Apr 12, 2024 |
| HP            | 8298                        | [c9d7df4ade](https://bsd-hardware.info/?probe=c9d7df4ade) | Apr 08, 2024 |
| Dell          | 0C27VV A02                  | [838d1cbd76](https://bsd-hardware.info/?probe=838d1cbd76) | Apr 08, 2024 |
| Unknown       | Unknown                     | [adb3e3abb5](https://bsd-hardware.info/?probe=adb3e3abb5) | Apr 07, 2024 |
| Foxconn       | H61MXV/H67MXV               | [53663c4ae5](https://bsd-hardware.info/?probe=53663c4ae5) | Apr 07, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [8df08d4eb9](https://bsd-hardware.info/?probe=8df08d4eb9) | Apr 06, 2024 |
| HP            | 2B28                        | [b4f2207b5d](https://bsd-hardware.info/?probe=b4f2207b5d) | Apr 06, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [b2c5d9efea](https://bsd-hardware.info/?probe=b2c5d9efea) | Apr 06, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [f454e745a8](https://bsd-hardware.info/?probe=f454e745a8) | Apr 06, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d0ce6ee00b](https://bsd-hardware.info/?probe=d0ce6ee00b) | Apr 05, 2024 |
| Unknown       | Unknown                     | [db63931af3](https://bsd-hardware.info/?probe=db63931af3) | Apr 05, 2024 |
| HP            | 2B28                        | [5a64d57e01](https://bsd-hardware.info/?probe=5a64d57e01) | Apr 05, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3208fef860](https://bsd-hardware.info/?probe=3208fef860) | Apr 04, 2024 |
| OEM           | 1.0                         | [a84e4f90a7](https://bsd-hardware.info/?probe=a84e4f90a7) | Apr 03, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [767ef499db](https://bsd-hardware.info/?probe=767ef499db) | Apr 03, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0ab49168ee](https://bsd-hardware.info/?probe=0ab49168ee) | Apr 02, 2024 |
| ASRock        | B365 Phantom Gaming 4       | [002a5c4b4b](https://bsd-hardware.info/?probe=002a5c4b4b) | Apr 02, 2024 |
| PC Engines    | APU2                        | [8bc45e08fd](https://bsd-hardware.info/?probe=8bc45e08fd) | Apr 01, 2024 |
| Unknown       | Unknown                     | [141a02f122](https://bsd-hardware.info/?probe=141a02f122) | Apr 01, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [cc791d5d6b](https://bsd-hardware.info/?probe=cc791d5d6b) | Apr 01, 2024 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | [2b8b6454a6](https://bsd-hardware.info/?probe=2b8b6454a6) | Mar 31, 2024 |
| Unknown       | Unknown                     | [9c12506b38](https://bsd-hardware.info/?probe=9c12506b38) | Mar 31, 2024 |
| Unknown       | MANIFOLD 2-C                | [791f0e10d0](https://bsd-hardware.info/?probe=791f0e10d0) | Mar 31, 2024 |
| Unknown       | Unknown                     | [19cd39be18](https://bsd-hardware.info/?probe=19cd39be18) | Mar 30, 2024 |
| Yanling       | YL-CLU6L-V1                 | [6b02f9805c](https://bsd-hardware.info/?probe=6b02f9805c) | Mar 29, 2024 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [fd5f6eb3b6](https://bsd-hardware.info/?probe=fd5f6eb3b6) | Mar 29, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [007b6f4e9d](https://bsd-hardware.info/?probe=007b6f4e9d) | Mar 29, 2024 |
| ASRock        | Q1900-ITX                   | [cfceb60c9e](https://bsd-hardware.info/?probe=cfceb60c9e) | Mar 28, 2024 |
| ASRock        | Q1900-ITX                   | [d29def9398](https://bsd-hardware.info/?probe=d29def9398) | Mar 28, 2024 |
| Unknown       | Unknown                     | [88c73f9aac](https://bsd-hardware.info/?probe=88c73f9aac) | Mar 28, 2024 |
| Intel         | ChiefRiver                  | [cad5b112a4](https://bsd-hardware.info/?probe=cad5b112a4) | Mar 28, 2024 |
| PC Engines    | apu4                        | [22943891fe](https://bsd-hardware.info/?probe=22943891fe) | Mar 28, 2024 |
| AAEON         | FWS-2251 V1.0               | [5b53955547](https://bsd-hardware.info/?probe=5b53955547) | Mar 28, 2024 |
| Fujitsu       | D3644-B1 S26361-D3644-B1    | [ab7e9eb3b3](https://bsd-hardware.info/?probe=ab7e9eb3b3) | Mar 27, 2024 |
| Unknown       | Unknown                     | [32c0457508](https://bsd-hardware.info/?probe=32c0457508) | Mar 27, 2024 |
| AZW           | EQ                          | [720bbb4fce](https://bsd-hardware.info/?probe=720bbb4fce) | Mar 27, 2024 |
| Fujitsu       | D3067-A1 S26361-D3067-A1    | [efa43f3297](https://bsd-hardware.info/?probe=efa43f3297) | Mar 27, 2024 |
| Techvision    | TVI7309X B0                 | [e777acccde](https://bsd-hardware.info/?probe=e777acccde) | Mar 26, 2024 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | [c01d223879](https://bsd-hardware.info/?probe=c01d223879) | Mar 26, 2024 |
| ASRock        | A520M-ITX/ac                | [ae88fbe955](https://bsd-hardware.info/?probe=ae88fbe955) | Mar 25, 2024 |
| CWWK          | CW-AD4L-N V1                | [e5f412499d](https://bsd-hardware.info/?probe=e5f412499d) | Mar 25, 2024 |
| MSI           | B450M MORTAR MAX            | [ca39a53bd3](https://bsd-hardware.info/?probe=ca39a53bd3) | Mar 25, 2024 |
| Unknown       | Unknown                     | [83e699ca56](https://bsd-hardware.info/?probe=83e699ca56) | Mar 25, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [c4f7c92b3a](https://bsd-hardware.info/?probe=c4f7c92b3a) | Mar 24, 2024 |
| Fujitsu       | D3067-A1 S26361-D3067-A1    | [d437c9f3ec](https://bsd-hardware.info/?probe=d437c9f3ec) | Mar 24, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [5b299b5bb4](https://bsd-hardware.info/?probe=5b299b5bb4) | Mar 24, 2024 |
| Unknown       | Unknown                     | [0e7756d928](https://bsd-hardware.info/?probe=0e7756d928) | Mar 23, 2024 |
| Unknown       | YL-J3160L4                  | [17e05ff99b](https://bsd-hardware.info/?probe=17e05ff99b) | Mar 23, 2024 |
| ASUSTek       | P8H67-I                     | [70e83653e3](https://bsd-hardware.info/?probe=70e83653e3) | Mar 23, 2024 |
| Unknown       | Unknown                     | [5772e3f865](https://bsd-hardware.info/?probe=5772e3f865) | Mar 22, 2024 |
| MW            | GMLK-2_5G4L                 | [220edbe827](https://bsd-hardware.info/?probe=220edbe827) | Mar 22, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [f0f1bda4c6](https://bsd-hardware.info/?probe=f0f1bda4c6) | Mar 21, 2024 |
| Unknown       | Unknown                     | [31d2e2ad77](https://bsd-hardware.info/?probe=31d2e2ad77) | Mar 19, 2024 |
| MI05          | 1.0                         | [15144d304e](https://bsd-hardware.info/?probe=15144d304e) | Mar 19, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [da7c40ce91](https://bsd-hardware.info/?probe=da7c40ce91) | Mar 18, 2024 |
| HP            | 213D A01                    | [d86065a205](https://bsd-hardware.info/?probe=d86065a205) | Mar 17, 2024 |
| HP            | 8425                        | [9d64ad4ed7](https://bsd-hardware.info/?probe=9d64ad4ed7) | Mar 15, 2024 |
| ASRock        | H310CM-DVS                  | [3f2a641be5](https://bsd-hardware.info/?probe=3f2a641be5) | Mar 15, 2024 |
| ASRock        | J5040-ITX                   | [046fab7e1e](https://bsd-hardware.info/?probe=046fab7e1e) | Mar 14, 2024 |
| MSI           | B450M MORTAR MAX            | [e89e238ce9](https://bsd-hardware.info/?probe=e89e238ce9) | Mar 14, 2024 |
| Gigabyte      | X570S UD                    | [c28339af88](https://bsd-hardware.info/?probe=c28339af88) | Mar 13, 2024 |
| AAEON         | FWS-2362 V1.0               | [ecb6ef08ca](https://bsd-hardware.info/?probe=ecb6ef08ca) | Mar 13, 2024 |
| Unknown       | Unknown                     | [180c13e49f](https://bsd-hardware.info/?probe=180c13e49f) | Mar 13, 2024 |
| ASUSTek       | H81M-PLUS                   | [a77269ec67](https://bsd-hardware.info/?probe=a77269ec67) | Mar 12, 2024 |
| ASUSTek       | P8H61-M PRO                 | [cdf413f137](https://bsd-hardware.info/?probe=cdf413f137) | Mar 12, 2024 |
| OEM_MB        | 2A72                        | [ae3340833c](https://bsd-hardware.info/?probe=ae3340833c) | Mar 11, 2024 |
| Dell          | 0T7D40 A01                  | [da1d8cff5b](https://bsd-hardware.info/?probe=da1d8cff5b) | Mar 11, 2024 |
| Unknown       | Unknown                     | [eb78b18ceb](https://bsd-hardware.info/?probe=eb78b18ceb) | Mar 11, 2024 |
| Intel         | BOX-J41L4A V3.01            | [91980ca805](https://bsd-hardware.info/?probe=91980ca805) | Mar 10, 2024 |
| Unknown       | Unknown                     | [646ddc0a68](https://bsd-hardware.info/?probe=646ddc0a68) | Mar 10, 2024 |
| PC Engines    | APU2                        | [fa374c2fa0](https://bsd-hardware.info/?probe=fa374c2fa0) | Mar 10, 2024 |
| ASRock        | Z97 Professional            | [f00b2738c3](https://bsd-hardware.info/?probe=f00b2738c3) | Mar 10, 2024 |
| PC Engines    | apu4                        | [6a8595a3ef](https://bsd-hardware.info/?probe=6a8595a3ef) | Mar 08, 2024 |
| Protectli     | FW6 Ver                     | [8363fabd39](https://bsd-hardware.info/?probe=8363fabd39) | Mar 08, 2024 |
| Unknown       | Unknown                     | [58d203b730](https://bsd-hardware.info/?probe=58d203b730) | Mar 08, 2024 |
| HP            | 213D A01                    | [964aa8199e](https://bsd-hardware.info/?probe=964aa8199e) | Mar 07, 2024 |
| Supermicro    | X10SRG-F                    | [293c884b40](https://bsd-hardware.info/?probe=293c884b40) | Mar 06, 2024 |
| PC Engines    | APU2                        | [2c64bf49b7](https://bsd-hardware.info/?probe=2c64bf49b7) | Mar 05, 2024 |
| Gigabyte      | IMB1900TN                   | [df5fd8934f](https://bsd-hardware.info/?probe=df5fd8934f) | Mar 04, 2024 |
| Protectli     | FW4B Ver                    | [ac0668a6e3](https://bsd-hardware.info/?probe=ac0668a6e3) | Mar 04, 2024 |
| Unknown       | Unknown                     | [1e20066df1](https://bsd-hardware.info/?probe=1e20066df1) | Mar 03, 2024 |
| PC Engines    | apu4                        | [ba31193999](https://bsd-hardware.info/?probe=ba31193999) | Mar 02, 2024 |
| Seco          | 0D02 A                      | [4aedb9a14f](https://bsd-hardware.info/?probe=4aedb9a14f) | Mar 02, 2024 |
| Seco          | 0D02 A                      | [3c0fb33c35](https://bsd-hardware.info/?probe=3c0fb33c35) | Mar 02, 2024 |
| Intel         | Q3XXG4-P V1.0               | [5119d898d7](https://bsd-hardware.info/?probe=5119d898d7) | Feb 28, 2024 |
| Supermicro    | X9SCL/X9SCM                 | [5a91ab5fef](https://bsd-hardware.info/?probe=5a91ab5fef) | Feb 26, 2024 |
| Unknown       | Unknown                     | [1ea892bfd7](https://bsd-hardware.info/?probe=1ea892bfd7) | Feb 26, 2024 |
| Unknown       | Unknown                     | [ecae7c493f](https://bsd-hardware.info/?probe=ecae7c493f) | Feb 25, 2024 |
| Unknown       | QCML03                      | [da0d43e31b](https://bsd-hardware.info/?probe=da0d43e31b) | Feb 25, 2024 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [5c5ee30a7a](https://bsd-hardware.info/?probe=5c5ee30a7a) | Feb 24, 2024 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [4ea9c8a781](https://bsd-hardware.info/?probe=4ea9c8a781) | Feb 24, 2024 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [8139f2fb4a](https://bsd-hardware.info/?probe=8139f2fb4a) | Feb 24, 2024 |
| Dell          | 0DR845                      | [1f5c710591](https://bsd-hardware.info/?probe=1f5c710591) | Feb 24, 2024 |
| Unknown       | Unknown                     | [b812f56645](https://bsd-hardware.info/?probe=b812f56645) | Feb 23, 2024 |
| Gigabyte      | B360N WIFI-CF               | [9105a79b01](https://bsd-hardware.info/?probe=9105a79b01) | Feb 22, 2024 |
| Unknown       | Unknown                     | [6a06080810](https://bsd-hardware.info/?probe=6a06080810) | Feb 20, 2024 |
| Unknown       | Unknown                     | [2d81dec0b1](https://bsd-hardware.info/?probe=2d81dec0b1) | Feb 20, 2024 |
| PC Engines    | apu4                        | [a81bdf4af4](https://bsd-hardware.info/?probe=a81bdf4af4) | Feb 20, 2024 |
| Gigabyte      | IMB1900TN                   | [676b767621](https://bsd-hardware.info/?probe=676b767621) | Feb 19, 2024 |
| ASRock        | H670M-ITX/ax                | [c67ba39d84](https://bsd-hardware.info/?probe=c67ba39d84) | Feb 18, 2024 |
| ASRock        | H670M-ITX/ax                | [712b7feb38](https://bsd-hardware.info/?probe=712b7feb38) | Feb 18, 2024 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [057ab23bee](https://bsd-hardware.info/?probe=057ab23bee) | Feb 18, 2024 |
| PC Engines    | apu4                        | [2ddf4760e4](https://bsd-hardware.info/?probe=2ddf4760e4) | Feb 18, 2024 |
| Unknown       | J3160-4L                    | [e4b6344125](https://bsd-hardware.info/?probe=e4b6344125) | Feb 18, 2024 |
| Gigabyte      | Z590I VISION D              | [95add8c57a](https://bsd-hardware.info/?probe=95add8c57a) | Feb 18, 2024 |
| Unknown       | Unknown                     | [0d6264dd51](https://bsd-hardware.info/?probe=0d6264dd51) | Feb 17, 2024 |
| Unknown       | Unknown                     | [ac788598a6](https://bsd-hardware.info/?probe=ac788598a6) | Feb 17, 2024 |
| ASUSTek       | B85M-G                      | [0fc891ba64](https://bsd-hardware.info/?probe=0fc891ba64) | Feb 17, 2024 |
| Biostar       | B450NH                      | [9f4dedfcd6](https://bsd-hardware.info/?probe=9f4dedfcd6) | Feb 17, 2024 |
| HP            | 8AC4                        | [524b8cae7c](https://bsd-hardware.info/?probe=524b8cae7c) | Feb 16, 2024 |
| Biostar       | B450NH                      | [2db279db1d](https://bsd-hardware.info/?probe=2db279db1d) | Feb 16, 2024 |
| Unknown       | Unknown                     | [a4781efc54](https://bsd-hardware.info/?probe=a4781efc54) | Feb 16, 2024 |
| Gigabyte      | B360N WIFI-CF               | [65cc201af1](https://bsd-hardware.info/?probe=65cc201af1) | Feb 15, 2024 |
| ASUSTek       | Pro B560M-C                 | [fdeb2cee9d](https://bsd-hardware.info/?probe=fdeb2cee9d) | Feb 14, 2024 |
| Supermicro    | X11SDV-8C-TP8F              | [6a026289ce](https://bsd-hardware.info/?probe=6a026289ce) | Feb 14, 2024 |
| Gigabyte      | IMB1900TN                   | [d0c6d1e44b](https://bsd-hardware.info/?probe=d0c6d1e44b) | Feb 14, 2024 |
| Unknown       | Unknown                     | [5da46d2f84](https://bsd-hardware.info/?probe=5da46d2f84) | Feb 14, 2024 |
| ASRock        | A520M-ITX/ac                | [63408627d9](https://bsd-hardware.info/?probe=63408627d9) | Feb 13, 2024 |
| Gigabyte      | B760I AORUS PRO DDR4        | [0074d80aa1](https://bsd-hardware.info/?probe=0074d80aa1) | Feb 12, 2024 |
| Unknown       | YL-J3160L4                  | [7bb2930dfa](https://bsd-hardware.info/?probe=7bb2930dfa) | Feb 11, 2024 |
| Gigabyte      | B760I AORUS PRO DDR4        | [ab109fa386](https://bsd-hardware.info/?probe=ab109fa386) | Feb 10, 2024 |
| Unknown       | Unknown                     | [ea4fe7a8cf](https://bsd-hardware.info/?probe=ea4fe7a8cf) | Feb 10, 2024 |
| Unknown       | Unknown                     | [eb03c1914f](https://bsd-hardware.info/?probe=eb03c1914f) | Feb 09, 2024 |
| Fujitsu       | D3067-A1 S26361-D3067-A1    | [08ee39a7cf](https://bsd-hardware.info/?probe=08ee39a7cf) | Feb 09, 2024 |
| MSI           | B450M MORTAR MAX            | [1401e42d48](https://bsd-hardware.info/?probe=1401e42d48) | Feb 08, 2024 |
| Unknown       | J3160-4L                    | [353ac982bf](https://bsd-hardware.info/?probe=353ac982bf) | Feb 07, 2024 |
| SHANGZHAOY... | B85M-PRO V1.1               | [79ec97854e](https://bsd-hardware.info/?probe=79ec97854e) | Feb 07, 2024 |
| AAEON         | FWS-2251 V1.0               | [17853848cd](https://bsd-hardware.info/?probe=17853848cd) | Feb 07, 2024 |
| HP            | 8717                        | [de846f4d11](https://bsd-hardware.info/?probe=de846f4d11) | Feb 07, 2024 |
| OEM           | 1.0                         | [dd3228b447](https://bsd-hardware.info/?probe=dd3228b447) | Feb 07, 2024 |
| PC Engines    | apu4                        | [fb60f908ae](https://bsd-hardware.info/?probe=fb60f908ae) | Feb 07, 2024 |
| Gigabyte      | B450M DS3H-CF               | [4073dda626](https://bsd-hardware.info/?probe=4073dda626) | Feb 07, 2024 |
| AAEON         | FWS-2251 V1.0               | [1def0a68ec](https://bsd-hardware.info/?probe=1def0a68ec) | Feb 07, 2024 |
| Unknown       | Unknown                     | [38a8200699](https://bsd-hardware.info/?probe=38a8200699) | Feb 06, 2024 |
| Unknown       | Unknown                     | [7f960ac536](https://bsd-hardware.info/?probe=7f960ac536) | Feb 06, 2024 |
| Gigabyte      | Z68X-UD3H-B3                | [a2c1b1addb](https://bsd-hardware.info/?probe=a2c1b1addb) | Feb 06, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | [a26afd4195](https://bsd-hardware.info/?probe=a26afd4195) | Feb 05, 2024 |
| Intel         | DENLOW_WS                   | [2d0479073b](https://bsd-hardware.info/?probe=2d0479073b) | Feb 05, 2024 |
| Unknown       | Unknown                     | [ff4514068b](https://bsd-hardware.info/?probe=ff4514068b) | Feb 05, 2024 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [9e7d881690](https://bsd-hardware.info/?probe=9e7d881690) | Feb 04, 2024 |
| Unknown       | Unknown                     | [aef9924665](https://bsd-hardware.info/?probe=aef9924665) | Feb 04, 2024 |
| AZW           | EQ                          | [13a1514ea5](https://bsd-hardware.info/?probe=13a1514ea5) | Feb 04, 2024 |
| ASUSTek       | H110I-PLUS                  | [4cb8c45861](https://bsd-hardware.info/?probe=4cb8c45861) | Feb 03, 2024 |
| AZW           | EQ                          | [53f9e8c700](https://bsd-hardware.info/?probe=53f9e8c700) | Feb 03, 2024 |
| ASUSTek       | Pro B560M-C                 | [676019447d](https://bsd-hardware.info/?probe=676019447d) | Feb 03, 2024 |
| ASRock        | H570M-ITX/ac                | [df0fcc7727](https://bsd-hardware.info/?probe=df0fcc7727) | Feb 03, 2024 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [4fdc25bc68](https://bsd-hardware.info/?probe=4fdc25bc68) | Feb 03, 2024 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [e5d18ced76](https://bsd-hardware.info/?probe=e5d18ced76) | Feb 03, 2024 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [f6b0ead009](https://bsd-hardware.info/?probe=f6b0ead009) | Feb 02, 2024 |
| NU591         | 1.0                         | [deccea813e](https://bsd-hardware.info/?probe=deccea813e) | Feb 02, 2024 |
| AAEON         | FWS-2251 V1.0               | [492271b0b3](https://bsd-hardware.info/?probe=492271b0b3) | Feb 02, 2024 |
| ASRock        | ALiveNF7G-HD720p            | [2bc3971f16](https://bsd-hardware.info/?probe=2bc3971f16) | Feb 02, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [f3322d1b78](https://bsd-hardware.info/?probe=f3322d1b78) | Feb 01, 2024 |
| PC Engines    | APU2                        | [36ea8d39d4](https://bsd-hardware.info/?probe=36ea8d39d4) | Feb 01, 2024 |
| Gigabyte      | IMB1900TN                   | [598cd03428](https://bsd-hardware.info/?probe=598cd03428) | Feb 01, 2024 |
| Protectli     | VP2410 10                   | [7d38bf7f11](https://bsd-hardware.info/?probe=7d38bf7f11) | Feb 01, 2024 |
| Gigabyte      | IMB1900TN                   | [60dd608790](https://bsd-hardware.info/?probe=60dd608790) | Feb 01, 2024 |
| Gigabyte      | B760I AORUS PRO DDR4        | [ac68b46e30](https://bsd-hardware.info/?probe=ac68b46e30) | Jan 31, 2024 |
| Gigabyte      | IMB1900TN                   | [99f34191a2](https://bsd-hardware.info/?probe=99f34191a2) | Jan 31, 2024 |
| NU591         | 1.0                         | [1a28ec7585](https://bsd-hardware.info/?probe=1a28ec7585) | Jan 31, 2024 |
| AZW           | EQ                          | [543a7683f5](https://bsd-hardware.info/?probe=543a7683f5) | Jan 31, 2024 |
| SHANGZHAOY... | B85M-PRO V1.1               | [2da6441f53](https://bsd-hardware.info/?probe=2da6441f53) | Jan 31, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [101a551862](https://bsd-hardware.info/?probe=101a551862) | Jan 30, 2024 |
| LANCOM Sys... | UF-360                      | [c220e91992](https://bsd-hardware.info/?probe=c220e91992) | Jan 30, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [72acb76c3b](https://bsd-hardware.info/?probe=72acb76c3b) | Jan 30, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [57d4964d77](https://bsd-hardware.info/?probe=57d4964d77) | Jan 30, 2024 |
| Yanling       | YL-CLU6L-V1                 | [dc64c3b9e2](https://bsd-hardware.info/?probe=dc64c3b9e2) | Jan 30, 2024 |
| CncTion       | N4505-4L B0                 | [2c14913b53](https://bsd-hardware.info/?probe=2c14913b53) | Jan 29, 2024 |
| CncTion       | N4505-4L B0                 | [f242be3f80](https://bsd-hardware.info/?probe=f242be3f80) | Jan 28, 2024 |
| Unknown       | YL-J3160L4                  | [4eaf392351](https://bsd-hardware.info/?probe=4eaf392351) | Jan 28, 2024 |
| Seco          | 0D02 A                      | [41fa3fa6ae](https://bsd-hardware.info/?probe=41fa3fa6ae) | Jan 28, 2024 |
| Seco          | 0D02 A                      | [076c8b8575](https://bsd-hardware.info/?probe=076c8b8575) | Jan 28, 2024 |
| Gigabyte      | J3455N-D3H                  | [9a1adff9eb](https://bsd-hardware.info/?probe=9a1adff9eb) | Jan 28, 2024 |
| Unknown       | Unknown                     | [94fdaaffaf](https://bsd-hardware.info/?probe=94fdaaffaf) | Jan 27, 2024 |
| Unknown       | Unknown                     | [60507b5afd](https://bsd-hardware.info/?probe=60507b5afd) | Jan 27, 2024 |
| OEM           | 1.0                         | [a6c82ad3f1](https://bsd-hardware.info/?probe=a6c82ad3f1) | Jan 26, 2024 |
| PC Engines    | apu4                        | [b3cc677cfa](https://bsd-hardware.info/?probe=b3cc677cfa) | Jan 24, 2024 |
| Unknown       | Unknown                     | [2cd92781d8](https://bsd-hardware.info/?probe=2cd92781d8) | Jan 24, 2024 |
| PC Engines    | APU2                        | [4665b895f7](https://bsd-hardware.info/?probe=4665b895f7) | Jan 24, 2024 |
| Deciso        | Netboard A10                | [cf324e008b](https://bsd-hardware.info/?probe=cf324e008b) | Jan 22, 2024 |
| PC Engines    | apu4                        | [0e2082e8dc](https://bsd-hardware.info/?probe=0e2082e8dc) | Jan 22, 2024 |
| PC Engines    | apu4                        | [f36b7e423e](https://bsd-hardware.info/?probe=f36b7e423e) | Jan 22, 2024 |
| MiTAC         | PD11TI AAPD11TI-100         | [71d42d0c05](https://bsd-hardware.info/?probe=71d42d0c05) | Jan 21, 2024 |
| Protectli     | VP2410 10                   | [e6396f76a1](https://bsd-hardware.info/?probe=e6396f76a1) | Jan 21, 2024 |
| Unknown       | Unknown                     | [4bee671423](https://bsd-hardware.info/?probe=4bee671423) | Jan 20, 2024 |
| Unknown       | Unknown                     | [89747e3a92](https://bsd-hardware.info/?probe=89747e3a92) | Jan 20, 2024 |
| Unknown       | Unknown                     | [c1a338bd53](https://bsd-hardware.info/?probe=c1a338bd53) | Jan 20, 2024 |
| CWWK          | CW-AD4L-N V1                | [2f576f617d](https://bsd-hardware.info/?probe=2f576f617d) | Jan 20, 2024 |
| Unknown       | Unknown                     | [a944f4d913](https://bsd-hardware.info/?probe=a944f4d913) | Jan 19, 2024 |
| Unknown       | Unknown                     | [b225f25bd6](https://bsd-hardware.info/?probe=b225f25bd6) | Jan 19, 2024 |
| ZX            | H610ITXG                    | [8add6c6c8c](https://bsd-hardware.info/?probe=8add6c6c8c) | Jan 16, 2024 |
| Unknown       | Unknown                     | [8cb0bf9ef6](https://bsd-hardware.info/?probe=8cb0bf9ef6) | Jan 16, 2024 |
| PC Engines    | apu4                        | [2c857f37bd](https://bsd-hardware.info/?probe=2c857f37bd) | Jan 15, 2024 |
| PC Engines    | APU2                        | [dd588cfada](https://bsd-hardware.info/?probe=dd588cfada) | Jan 15, 2024 |
| Unknown       | QD-CMU01                    | [f5b7d0415b](https://bsd-hardware.info/?probe=f5b7d0415b) | Jan 15, 2024 |
| PC Engines    | apu4                        | [93f07ee3ad](https://bsd-hardware.info/?probe=93f07ee3ad) | Jan 13, 2024 |
| PC Engines    | apu4                        | [aabf377c9a](https://bsd-hardware.info/?probe=aabf377c9a) | Jan 13, 2024 |
| Unknown       | Unknown                     | [37558c7d54](https://bsd-hardware.info/?probe=37558c7d54) | Jan 12, 2024 |
| Techvision    | TVI7309X B0                 | [023fd3c0ed](https://bsd-hardware.info/?probe=023fd3c0ed) | Jan 12, 2024 |
| Unknown       | Unknown                     | [3ba7f826bb](https://bsd-hardware.info/?probe=3ba7f826bb) | Jan 12, 2024 |
| ASUSTek       | P10S-M Series               | [e9c51e6d9a](https://bsd-hardware.info/?probe=e9c51e6d9a) | Jan 12, 2024 |
| PC Engines    | apu4                        | [0154684e8f](https://bsd-hardware.info/?probe=0154684e8f) | Jan 11, 2024 |
| MSI           | B450M MORTAR MAX            | [f85bbcd879](https://bsd-hardware.info/?probe=f85bbcd879) | Jan 11, 2024 |
| AWOW          | AK10                        | [18ce2740c7](https://bsd-hardware.info/?probe=18ce2740c7) | Jan 10, 2024 |
| Techvision    | TVI7309X B0                 | [c43a31cf9e](https://bsd-hardware.info/?probe=c43a31cf9e) | Jan 10, 2024 |
| Techvision    | TVI7309X B0                 | [1dd0e8fc68](https://bsd-hardware.info/?probe=1dd0e8fc68) | Jan 10, 2024 |
| Unknown       | Unknown                     | [80a25c3416](https://bsd-hardware.info/?probe=80a25c3416) | Jan 08, 2024 |
| SHANGZHAOY... | B85M-PRO V1.1               | [aeed7e4a51](https://bsd-hardware.info/?probe=aeed7e4a51) | Jan 07, 2024 |
| Lanner        | FW-7543 B-GA                | [6687c1ef69](https://bsd-hardware.info/?probe=6687c1ef69) | Jan 07, 2024 |
| ZOTAC         | H67ITX-C-E 02/03/05         | [6aba0c53a6](https://bsd-hardware.info/?probe=6aba0c53a6) | Jan 06, 2024 |
| Unknown       | Unknown                     | [3250ebf7f4](https://bsd-hardware.info/?probe=3250ebf7f4) | Jan 06, 2024 |
| CWWK          | MINIPC-G12                  | [cec3c2ba34](https://bsd-hardware.info/?probe=cec3c2ba34) | Jan 06, 2024 |
| PC Engines    | APU2                        | [680567c89b](https://bsd-hardware.info/?probe=680567c89b) | Jan 05, 2024 |
| Unknown       | MANIFOLD 2-C                | [02161442f5](https://bsd-hardware.info/?probe=02161442f5) | Jan 04, 2024 |
| Unknown       | Unknown                     | [1fddddcbc7](https://bsd-hardware.info/?probe=1fddddcbc7) | Jan 02, 2024 |
| Unknown       | MANIFOLD 2-C                | [6a195bc48f](https://bsd-hardware.info/?probe=6a195bc48f) | Jan 02, 2024 |
| Dell          | 0KYJ8C A00                  | [34246adca9](https://bsd-hardware.info/?probe=34246adca9) | Dec 30, 2023 |
| Unknown       | Unknown                     | [63472bd5e6](https://bsd-hardware.info/?probe=63472bd5e6) | Dec 30, 2023 |
| Intel         | JSL MRD                     | [1c65a367b2](https://bsd-hardware.info/?probe=1c65a367b2) | Dec 30, 2023 |
| Gigabyte      | H110M-D2P-WG-CF             | [77e0d09bf1](https://bsd-hardware.info/?probe=77e0d09bf1) | Dec 29, 2023 |
| Supermicro    | X8SIE                       | [a7e2e09ef4](https://bsd-hardware.info/?probe=a7e2e09ef4) | Dec 28, 2023 |
| Unknown       | QSKL01                      | [ba39338284](https://bsd-hardware.info/?probe=ba39338284) | Dec 28, 2023 |
| AZW           | EQ                          | [fcbfcb31d5](https://bsd-hardware.info/?probe=fcbfcb31d5) | Dec 28, 2023 |
| Techvision    | TVI7309X B0                 | [429f1e855f](https://bsd-hardware.info/?probe=429f1e855f) | Dec 27, 2023 |
| ZX            | H610ITXG                    | [8253eb826a](https://bsd-hardware.info/?probe=8253eb826a) | Dec 27, 2023 |
| Techvision    | TVI7309X B0                 | [6f592981ce](https://bsd-hardware.info/?probe=6f592981ce) | Dec 27, 2023 |
| Unknown       | MANIFOLD 2-C                | [c2f3692204](https://bsd-hardware.info/?probe=c2f3692204) | Dec 27, 2023 |
| Unknown       | Unknown                     | [b054d33e68](https://bsd-hardware.info/?probe=b054d33e68) | Dec 26, 2023 |
| CWWK          | CW-ADLN-6L                  | [fa5891041a](https://bsd-hardware.info/?probe=fa5891041a) | Dec 26, 2023 |
| Unknown       | Unknown                     | [23ca4c0419](https://bsd-hardware.info/?probe=23ca4c0419) | Dec 25, 2023 |
| Unknown       | Unknown                     | [72d02dbaa4](https://bsd-hardware.info/?probe=72d02dbaa4) | Dec 25, 2023 |
| Unknown       | Unknown                     | [9876dcc6aa](https://bsd-hardware.info/?probe=9876dcc6aa) | Dec 24, 2023 |
| Unknown       | Unknown                     | [9a23873dc4](https://bsd-hardware.info/?probe=9a23873dc4) | Dec 24, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [ee768bd5a0](https://bsd-hardware.info/?probe=ee768bd5a0) | Dec 23, 2023 |
| CWWK          | CW-ADLN-6L                  | [d8245df746](https://bsd-hardware.info/?probe=d8245df746) | Dec 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [5ed362ce02](https://bsd-hardware.info/?probe=5ed362ce02) | Dec 22, 2023 |
| ZX            | H610ITXG                    | [11edcbeaff](https://bsd-hardware.info/?probe=11edcbeaff) | Dec 22, 2023 |
| MW            | GMLK-2_5G4L                 | [9eaa02c47c](https://bsd-hardware.info/?probe=9eaa02c47c) | Dec 22, 2023 |
| Unknown       | MANIFOLD 2-C                | [b2597a7f2b](https://bsd-hardware.info/?probe=b2597a7f2b) | Dec 21, 2023 |
| Unknown       | Unknown                     | [ec4c6d8fb5](https://bsd-hardware.info/?probe=ec4c6d8fb5) | Dec 21, 2023 |
| Yanling       | YL-CLU6L-V1                 | [9a0369cc72](https://bsd-hardware.info/?probe=9a0369cc72) | Dec 21, 2023 |
| CWWK          | CW-ADLN-6L                  | [094d15625b](https://bsd-hardware.info/?probe=094d15625b) | Dec 21, 2023 |
| ASUSTek       | H110I-PLUS                  | [5c6e9bd18a](https://bsd-hardware.info/?probe=5c6e9bd18a) | Dec 20, 2023 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | [ec18d4f3a1](https://bsd-hardware.info/?probe=ec18d4f3a1) | Dec 20, 2023 |
| Unknown       | Unknown                     | [f11c353c61](https://bsd-hardware.info/?probe=f11c353c61) | Dec 19, 2023 |
| PC Engines    | apu4                        | [97c6f1ef2a](https://bsd-hardware.info/?probe=97c6f1ef2a) | Dec 19, 2023 |
| MSI           | A520M-A PRO                 | [11e5e87b70](https://bsd-hardware.info/?probe=11e5e87b70) | Dec 16, 2023 |
| SHANGZHAOY... | B85M-PRO V1.1               | [3b7ed136da](https://bsd-hardware.info/?probe=3b7ed136da) | Dec 16, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [f05a97db34](https://bsd-hardware.info/?probe=f05a97db34) | Dec 15, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [343d176e9c](https://bsd-hardware.info/?probe=343d176e9c) | Dec 15, 2023 |
| ASUSTek       | PRO B460M-C                 | [7a32a123f6](https://bsd-hardware.info/?probe=7a32a123f6) | Dec 15, 2023 |
| AZW           | EQ                          | [f1e4bf2224](https://bsd-hardware.info/?probe=f1e4bf2224) | Dec 15, 2023 |
| Techvision    | TVI7309X B0                 | [b5f9416c13](https://bsd-hardware.info/?probe=b5f9416c13) | Dec 12, 2023 |
| Unknown       | Unknown                     | [8a0a469ad0](https://bsd-hardware.info/?probe=8a0a469ad0) | Dec 12, 2023 |
| SHANGZHAOY... | B85M-PRO V1.1               | [5cf5db5a05](https://bsd-hardware.info/?probe=5cf5db5a05) | Dec 11, 2023 |
| Techvision    | TVI7309X B0                 | [9a3a20d295](https://bsd-hardware.info/?probe=9a3a20d295) | Dec 11, 2023 |
| ASRock        | H110M-DVS R3.0              | [b6a4782cbf](https://bsd-hardware.info/?probe=b6a4782cbf) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [47480f848d](https://bsd-hardware.info/?probe=47480f848d) | Dec 10, 2023 |
| ASUSTek       | PRIME X399-A                | [d62ad0d622](https://bsd-hardware.info/?probe=d62ad0d622) | Dec 09, 2023 |
| Dell          | 02YYK5 A00                  | [39e0078d08](https://bsd-hardware.info/?probe=39e0078d08) | Dec 09, 2023 |
| ASRock        | Z370 Pro4                   | [6b4d8c076f](https://bsd-hardware.info/?probe=6b4d8c076f) | Dec 09, 2023 |
| Unknown       | Unknown                     | [31619d30b3](https://bsd-hardware.info/?probe=31619d30b3) | Dec 09, 2023 |
| PC Engines    | APU2                        | [8f318ea168](https://bsd-hardware.info/?probe=8f318ea168) | Dec 09, 2023 |
| PC Engines    | APU2                        | [ca43be99fc](https://bsd-hardware.info/?probe=ca43be99fc) | Dec 08, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [eb2eef3d17](https://bsd-hardware.info/?probe=eb2eef3d17) | Dec 08, 2023 |
| PC Engines    | apu4                        | [cdbac53ff6](https://bsd-hardware.info/?probe=cdbac53ff6) | Dec 08, 2023 |
| Unknown       | Unknown                     | [efab62c197](https://bsd-hardware.info/?probe=efab62c197) | Dec 07, 2023 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | [d3898c1e39](https://bsd-hardware.info/?probe=d3898c1e39) | Dec 07, 2023 |
| Unknown       | Unknown                     | [fed92c23db](https://bsd-hardware.info/?probe=fed92c23db) | Dec 07, 2023 |
| PC Engines    | APU3                        | [06a4e1c23b](https://bsd-hardware.info/?probe=06a4e1c23b) | Dec 06, 2023 |
| PC Engines    | apu4                        | [04dd506405](https://bsd-hardware.info/?probe=04dd506405) | Dec 06, 2023 |
| Techvision    | TVI7309X B0                 | [9d54a02c53](https://bsd-hardware.info/?probe=9d54a02c53) | Dec 05, 2023 |
| Yanling       | YL-KBRL2 Series Ver:1.02    | [3bd3f01055](https://bsd-hardware.info/?probe=3bd3f01055) | Dec 05, 2023 |
| Protectli     | FW2B Ver                    | [9ae293de1b](https://bsd-hardware.info/?probe=9ae293de1b) | Dec 03, 2023 |
| Protectli     | VP2420                      | [31b70f1d0d](https://bsd-hardware.info/?probe=31b70f1d0d) | Dec 03, 2023 |
| Intel         | Q3XXG4-P V1.0               | [8a6ce136cc](https://bsd-hardware.info/?probe=8a6ce136cc) | Dec 03, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [150fd26797](https://bsd-hardware.info/?probe=150fd26797) | Dec 02, 2023 |
| Unknown       | Unknown                     | [5efe3ae6f9](https://bsd-hardware.info/?probe=5efe3ae6f9) | Dec 01, 2023 |
| Protectli     | VP2420                      | [4d59cef5e8](https://bsd-hardware.info/?probe=4d59cef5e8) | Nov 30, 2023 |
| Intel         | JSL MRD                     | [0ec285953e](https://bsd-hardware.info/?probe=0ec285953e) | Nov 30, 2023 |
| Unknown       | Unknown                     | [e5be2bebf5](https://bsd-hardware.info/?probe=e5be2bebf5) | Nov 30, 2023 |
| Unknown       | Unknown                     | [9579521c83](https://bsd-hardware.info/?probe=9579521c83) | Nov 30, 2023 |
| Intel         | JSL MRD                     | [f8beb1caa9](https://bsd-hardware.info/?probe=f8beb1caa9) | Nov 30, 2023 |
| CWWK          | CW-AD4L-N V1                | [e31a43fc53](https://bsd-hardware.info/?probe=e31a43fc53) | Nov 30, 2023 |
| Yanling       | YL-ALU6L                    | [21135d9aa5](https://bsd-hardware.info/?probe=21135d9aa5) | Nov 29, 2023 |
| Techvision    | TVI7309X B0                 | [895be1e0cd](https://bsd-hardware.info/?probe=895be1e0cd) | Nov 28, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [61bf87efe4](https://bsd-hardware.info/?probe=61bf87efe4) | Nov 28, 2023 |
| CNCTION-IA... | Unknown                     | [1b4871792b](https://bsd-hardware.info/?probe=1b4871792b) | Nov 28, 2023 |
| Lanner        | FW-7543 B-GA                | [fa32eea2ff](https://bsd-hardware.info/?probe=fa32eea2ff) | Nov 26, 2023 |
| PC Engines    | APU2                        | [c2ab63093b](https://bsd-hardware.info/?probe=c2ab63093b) | Nov 25, 2023 |
| ASRock        | H570M-ITX/ac                | [a8d3950959](https://bsd-hardware.info/?probe=a8d3950959) | Nov 25, 2023 |
| HP            | 1825                        | [373a147d04](https://bsd-hardware.info/?probe=373a147d04) | Nov 24, 2023 |
| Protectli     | FW6 Ver                     | [7bb170248d](https://bsd-hardware.info/?probe=7bb170248d) | Nov 24, 2023 |
| PICO PC       | MNHO-113                    | [261b0d936c](https://bsd-hardware.info/?probe=261b0d936c) | Nov 23, 2023 |
| Lanner        | FW-7543 B-GA                | [eca8e8785c](https://bsd-hardware.info/?probe=eca8e8785c) | Nov 22, 2023 |
| AZW           | EQ                          | [3407ab2a5b](https://bsd-hardware.info/?probe=3407ab2a5b) | Nov 22, 2023 |
| Unknown       | Unknown                     | [87ab49a51e](https://bsd-hardware.info/?probe=87ab49a51e) | Nov 22, 2023 |
| Unknown       | Unknown                     | [b60795e523](https://bsd-hardware.info/?probe=b60795e523) | Nov 22, 2023 |
| Thomas-Kre... | LES network 6L              | [654e4f96f7](https://bsd-hardware.info/?probe=654e4f96f7) | Nov 21, 2023 |
| MSI           | B450M MORTAR MAX            | [d38d698b2e](https://bsd-hardware.info/?probe=d38d698b2e) | Nov 20, 2023 |
| Intel         | ND2X-NET-PC BIOS Revisio... | [7fd080cf42](https://bsd-hardware.info/?probe=7fd080cf42) | Nov 19, 2023 |
| Dell          | 0WMJ54 A01                  | [bd12235645](https://bsd-hardware.info/?probe=bd12235645) | Nov 18, 2023 |
| Deciso        | Netboard A10                | [5efc270fa6](https://bsd-hardware.info/?probe=5efc270fa6) | Nov 18, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [947076a4de](https://bsd-hardware.info/?probe=947076a4de) | Nov 18, 2023 |
| ASUSTek       | PRIME X470-PRO              | [07dbd58d8e](https://bsd-hardware.info/?probe=07dbd58d8e) | Nov 17, 2023 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | [a406ee9805](https://bsd-hardware.info/?probe=a406ee9805) | Nov 16, 2023 |
| PC Engines    | APU2                        | [5ea4af0d94](https://bsd-hardware.info/?probe=5ea4af0d94) | Nov 16, 2023 |
| Intel         | QHSW02                      | [f05cdb2841](https://bsd-hardware.info/?probe=f05cdb2841) | Nov 15, 2023 |
| ASRock        | A300M-STX                   | [e5f0053202](https://bsd-hardware.info/?probe=e5f0053202) | Nov 15, 2023 |
| Protectli     | FW6 Ver                     | [7719e7606c](https://bsd-hardware.info/?probe=7719e7606c) | Nov 15, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [6257d05c99](https://bsd-hardware.info/?probe=6257d05c99) | Nov 15, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [0f82d77235](https://bsd-hardware.info/?probe=0f82d77235) | Nov 14, 2023 |
| Protectli     | FW6 Ver                     | [4984b1536a](https://bsd-hardware.info/?probe=4984b1536a) | Nov 14, 2023 |
| Protectli     | FW6 Ver                     | [5d9467ed74](https://bsd-hardware.info/?probe=5d9467ed74) | Nov 14, 2023 |
| MW            | GMLK-2_5G4L                 | [d6f10bf9d2](https://bsd-hardware.info/?probe=d6f10bf9d2) | Nov 13, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [49089c64bf](https://bsd-hardware.info/?probe=49089c64bf) | Nov 12, 2023 |
| Unknown       | Unknown                     | [d8cc007961](https://bsd-hardware.info/?probe=d8cc007961) | Nov 12, 2023 |
| PC Engines    | APU3                        | [0c58a923fe](https://bsd-hardware.info/?probe=0c58a923fe) | Nov 12, 2023 |
| MW            | GMLK-2_5G4L                 | [9bab52c825](https://bsd-hardware.info/?probe=9bab52c825) | Nov 11, 2023 |
| Protectli     | FW6 Ver                     | [da0816e168](https://bsd-hardware.info/?probe=da0816e168) | Nov 10, 2023 |
| Techvision    | TVI7309X B0                 | [6afb2cc33f](https://bsd-hardware.info/?probe=6afb2cc33f) | Nov 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [700d52c2dd](https://bsd-hardware.info/?probe=700d52c2dd) | Nov 07, 2023 |
| CncTion       | N5105-4L B0                 | [2c085953ca](https://bsd-hardware.info/?probe=2c085953ca) | Nov 07, 2023 |
| Protectli     | FW6 Ver                     | [df41e8f6b2](https://bsd-hardware.info/?probe=df41e8f6b2) | Nov 07, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [cf8fb90fe0](https://bsd-hardware.info/?probe=cf8fb90fe0) | Nov 07, 2023 |
| MSI           | Z270 PC MATE                | [9686c20980](https://bsd-hardware.info/?probe=9686c20980) | Nov 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [b4c8864cef](https://bsd-hardware.info/?probe=b4c8864cef) | Nov 06, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [456fe0a275](https://bsd-hardware.info/?probe=456fe0a275) | Nov 06, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [ea78913e4c](https://bsd-hardware.info/?probe=ea78913e4c) | Nov 05, 2023 |
| Gigabyte      | B360N WIFI-CF               | [38b5f3b9ad](https://bsd-hardware.info/?probe=38b5f3b9ad) | Nov 04, 2023 |
| CncTion       | N5105-4L B0                 | [86aa07c0ae](https://bsd-hardware.info/?probe=86aa07c0ae) | Nov 04, 2023 |
| ASRock        | B365M-HDV                   | [368366454f](https://bsd-hardware.info/?probe=368366454f) | Nov 03, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [e6927b5eb8](https://bsd-hardware.info/?probe=e6927b5eb8) | Nov 03, 2023 |
| Protectli     | FW6 Ver                     | [13eb07060d](https://bsd-hardware.info/?probe=13eb07060d) | Nov 03, 2023 |
| PC Engines    | apu4                        | [b85acbe43d](https://bsd-hardware.info/?probe=b85acbe43d) | Nov 03, 2023 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [d4298a293f](https://bsd-hardware.info/?probe=d4298a293f) | Nov 02, 2023 |
| Techvision    | TVI7309X B0                 | [b038d8a95d](https://bsd-hardware.info/?probe=b038d8a95d) | Nov 02, 2023 |
| Unknown       | Unknown                     | [691338cb44](https://bsd-hardware.info/?probe=691338cb44) | Nov 02, 2023 |
| Unknown       | Unknown                     | [c6610a58ac](https://bsd-hardware.info/?probe=c6610a58ac) | Nov 02, 2023 |
| PICO PC       | MNHO-113                    | [a4175476a0](https://bsd-hardware.info/?probe=a4175476a0) | Nov 02, 2023 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | [2fcac7d927](https://bsd-hardware.info/?probe=2fcac7d927) | Nov 01, 2023 |
| Hardkernel    | ODROID-H2                   | [41c4097002](https://bsd-hardware.info/?probe=41c4097002) | Oct 30, 2023 |
| AZW           | EQ                          | [034b060507](https://bsd-hardware.info/?probe=034b060507) | Oct 30, 2023 |
| MW            | GMLK-2_5G4L                 | [ec852f7037](https://bsd-hardware.info/?probe=ec852f7037) | Oct 29, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [fc42f6db17](https://bsd-hardware.info/?probe=fc42f6db17) | Oct 28, 2023 |
| HP            | 1825                        | [8a0a258efc](https://bsd-hardware.info/?probe=8a0a258efc) | Oct 28, 2023 |
| Gigabyte      | J3455N-D3H                  | [6448ed1b12](https://bsd-hardware.info/?probe=6448ed1b12) | Oct 28, 2023 |
| IGEL Techn... | D220                        | [3478db91ef](https://bsd-hardware.info/?probe=3478db91ef) | Oct 28, 2023 |
| Supermicro    | X11SSH-F                    | [73160cea1d](https://bsd-hardware.info/?probe=73160cea1d) | Oct 28, 2023 |
| Protectli     | FW4B                        | [23c31e7f9f](https://bsd-hardware.info/?probe=23c31e7f9f) | Oct 27, 2023 |
| Intel         | DB75EN AAG39650-302         | [5d64d42233](https://bsd-hardware.info/?probe=5d64d42233) | Oct 27, 2023 |
| Fujitsu       | D3314-E1 S26361-D3314-E1    | [2cde7906c1](https://bsd-hardware.info/?probe=2cde7906c1) | Oct 27, 2023 |
| Fujitsu       | D3314-A1 S26361-D3314-A1    | [d005339b5f](https://bsd-hardware.info/?probe=d005339b5f) | Oct 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [fe3d35aef8](https://bsd-hardware.info/?probe=fe3d35aef8) | Oct 27, 2023 |
| PC Engines    | apu4                        | [7bbd252741](https://bsd-hardware.info/?probe=7bbd252741) | Oct 27, 2023 |
| Acer          | Veriton X4620G v1.0         | [bc374cdc01](https://bsd-hardware.info/?probe=bc374cdc01) | Oct 26, 2023 |
| Protectli     | FW4B Ver                    | [0d97ba1ab0](https://bsd-hardware.info/?probe=0d97ba1ab0) | Oct 24, 2023 |
| Gigabyte      | MZGLKBP-00                  | [dcd8b6e432](https://bsd-hardware.info/?probe=dcd8b6e432) | Oct 24, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [dea9eee8a4](https://bsd-hardware.info/?probe=dea9eee8a4) | Oct 24, 2023 |
| Techvision    | TVI7309X B0                 | [38b1931562](https://bsd-hardware.info/?probe=38b1931562) | Oct 24, 2023 |
| AZW           | EQ                          | [8cb6ac80d2](https://bsd-hardware.info/?probe=8cb6ac80d2) | Oct 23, 2023 |
| Unknown       | YL-J3160L4                  | [3192ead8b5](https://bsd-hardware.info/?probe=3192ead8b5) | Oct 22, 2023 |
| Unknown       | J3160-4L                    | [d69749afe5](https://bsd-hardware.info/?probe=d69749afe5) | Oct 18, 2023 |
| PC Engines    | APU2                        | [7fb59a92f0](https://bsd-hardware.info/?probe=7fb59a92f0) | Oct 16, 2023 |
| ASRock        | H110M-DVS R3.0              | [abe8593d6e](https://bsd-hardware.info/?probe=abe8593d6e) | Oct 15, 2023 |
| MW            | GMLK-2_5G4L                 | [eb383d6f22](https://bsd-hardware.info/?probe=eb383d6f22) | Oct 15, 2023 |
| MW            | GMLK-2_5G4L                 | [248c73db22](https://bsd-hardware.info/?probe=248c73db22) | Oct 14, 2023 |
| Unknown       | Unknown                     | [77a827631b](https://bsd-hardware.info/?probe=77a827631b) | Oct 13, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | [8b0d009cc4](https://bsd-hardware.info/?probe=8b0d009cc4) | Oct 13, 2023 |
| Unknown       | YL-J3160L4                  | [65acf27cad](https://bsd-hardware.info/?probe=65acf27cad) | Oct 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [516eda52f0](https://bsd-hardware.info/?probe=516eda52f0) | Oct 12, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | [bb82c13e39](https://bsd-hardware.info/?probe=bb82c13e39) | Oct 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [418d78095d](https://bsd-hardware.info/?probe=418d78095d) | Oct 12, 2023 |
| Yanling       | YL-CLU6L-V1                 | [f3b384d87a](https://bsd-hardware.info/?probe=f3b384d87a) | Oct 12, 2023 |
| Unknown       | Unknown                     | [30ec824cf5](https://bsd-hardware.info/?probe=30ec824cf5) | Oct 11, 2023 |
| Unknown       | Unknown                     | [3d5abb3996](https://bsd-hardware.info/?probe=3d5abb3996) | Oct 11, 2023 |
| Unknown       | Unknown                     | [e4faecc5e8](https://bsd-hardware.info/?probe=e4faecc5e8) | Oct 10, 2023 |
| Unknown       | Unknown                     | [5031b0a5a7](https://bsd-hardware.info/?probe=5031b0a5a7) | Oct 10, 2023 |
| Yanling       | YL-CLU6L-V1                 | [cf15e11738](https://bsd-hardware.info/?probe=cf15e11738) | Oct 10, 2023 |
| Unknown       | QD-CMU01                    | [8637821e57](https://bsd-hardware.info/?probe=8637821e57) | Oct 09, 2023 |
| ASRock        | A75M-HVS                    | [93709074ae](https://bsd-hardware.info/?probe=93709074ae) | Oct 09, 2023 |
| Intel         | DENLOW_WS                   | [11b0d7b64f](https://bsd-hardware.info/?probe=11b0d7b64f) | Oct 07, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [d7a7e7338f](https://bsd-hardware.info/?probe=d7a7e7338f) | Oct 07, 2023 |
| ASRock        | J5040-ITX                   | [dffb96790c](https://bsd-hardware.info/?probe=dffb96790c) | Oct 06, 2023 |
| GoWin Solu... | R86S                        | [91b63fa5c7](https://bsd-hardware.info/?probe=91b63fa5c7) | Oct 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [31c7e1d3f3](https://bsd-hardware.info/?probe=31c7e1d3f3) | Oct 06, 2023 |
| Deciso        | Netboard A8                 | [cf3b678212](https://bsd-hardware.info/?probe=cf3b678212) | Oct 06, 2023 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | [5b33d7b22e](https://bsd-hardware.info/?probe=5b33d7b22e) | Oct 04, 2023 |
| PC Engines    | APU2                        | [626d74b530](https://bsd-hardware.info/?probe=626d74b530) | Oct 04, 2023 |
| PC Engines    | apu4                        | [0e813a0050](https://bsd-hardware.info/?probe=0e813a0050) | Oct 04, 2023 |
| Unknown       | Unknown                     | [f5e7677e76](https://bsd-hardware.info/?probe=f5e7677e76) | Oct 01, 2023 |
| PC Engines    | APU2                        | [064fd13617](https://bsd-hardware.info/?probe=064fd13617) | Oct 01, 2023 |
| Unknown       | Unknown                     | [716f9b28ab](https://bsd-hardware.info/?probe=716f9b28ab) | Sep 30, 2023 |
| Unknown       | Unknown                     | [fb21a44f71](https://bsd-hardware.info/?probe=fb21a44f71) | Sep 29, 2023 |
| Techvision    | TVI7309X B0                 | [f50d617197](https://bsd-hardware.info/?probe=f50d617197) | Sep 28, 2023 |
| Gigabyte      | B450M S2H V2                | [31da8655d1](https://bsd-hardware.info/?probe=31da8655d1) | Sep 28, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [b3f0a784ab](https://bsd-hardware.info/?probe=b3f0a784ab) | Sep 28, 2023 |
| Unknown       | YL-J1900L4-V2               | [c186f8b50c](https://bsd-hardware.info/?probe=c186f8b50c) | Sep 25, 2023 |
| Unknown       | Unknown                     | [1ba135fef1](https://bsd-hardware.info/?probe=1ba135fef1) | Sep 24, 2023 |
| Unknown       | Unknown                     | [9c8516c8a8](https://bsd-hardware.info/?probe=9c8516c8a8) | Sep 24, 2023 |
| ASUSTek       | PRIME X470-PRO              | [6a2ce1e29f](https://bsd-hardware.info/?probe=6a2ce1e29f) | Sep 24, 2023 |
| NU591         | 1.0                         | [99f3260ee0](https://bsd-hardware.info/?probe=99f3260ee0) | Sep 24, 2023 |
| PC Engines    | APU2                        | [3c7bd005ef](https://bsd-hardware.info/?probe=3c7bd005ef) | Sep 23, 2023 |
| Yanling       | YL-CLU6L-V1                 | [06d8f02eb7](https://bsd-hardware.info/?probe=06d8f02eb7) | Sep 22, 2023 |
| Unknown       | Unknown                     | [16640c7f04](https://bsd-hardware.info/?probe=16640c7f04) | Sep 22, 2023 |
| Unknown       | Unknown                     | [fcde651e99](https://bsd-hardware.info/?probe=fcde651e99) | Sep 21, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [e046bd9405](https://bsd-hardware.info/?probe=e046bd9405) | Sep 21, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [90f89eea16](https://bsd-hardware.info/?probe=90f89eea16) | Sep 21, 2023 |
| ASRock        | J3455B-ITX                  | [c5a2093552](https://bsd-hardware.info/?probe=c5a2093552) | Sep 21, 2023 |
| Unknown       | Unknown                     | [3c479d7824](https://bsd-hardware.info/?probe=3c479d7824) | Sep 20, 2023 |
| Unknown       | Unknown                     | [13ba11c952](https://bsd-hardware.info/?probe=13ba11c952) | Sep 20, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [92da10b93b](https://bsd-hardware.info/?probe=92da10b93b) | Sep 20, 2023 |
| Unknown       | SKYBAY                      | [95286f41d9](https://bsd-hardware.info/?probe=95286f41d9) | Sep 19, 2023 |
| Intel         | DENLOW_WS                   | [029b3cdd58](https://bsd-hardware.info/?probe=029b3cdd58) | Sep 16, 2023 |
| Unknown       | MANIFOLD 2-C                | [80707f8712](https://bsd-hardware.info/?probe=80707f8712) | Sep 16, 2023 |
| Techvision    | TVI7309X B0                 | [9a30d2d88c](https://bsd-hardware.info/?probe=9a30d2d88c) | Sep 16, 2023 |
| Unknown       | Unknown                     | [1808e7891c](https://bsd-hardware.info/?probe=1808e7891c) | Sep 16, 2023 |
| Unknown       | Unknown                     | [d6acb378a1](https://bsd-hardware.info/?probe=d6acb378a1) | Sep 15, 2023 |
| Unknown       | Unknown                     | [fe010506e6](https://bsd-hardware.info/?probe=fe010506e6) | Sep 15, 2023 |
| Dell          | 0NW6H5 A00                  | [227062e965](https://bsd-hardware.info/?probe=227062e965) | Sep 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [5c89a7a1f1](https://bsd-hardware.info/?probe=5c89a7a1f1) | Sep 13, 2023 |
| Unknown       | Unknown                     | [fd131bd648](https://bsd-hardware.info/?probe=fd131bd648) | Sep 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [0797783a1c](https://bsd-hardware.info/?probe=0797783a1c) | Sep 10, 2023 |
| Unknown       | Unknown                     | [3c85271913](https://bsd-hardware.info/?probe=3c85271913) | Sep 10, 2023 |
| Apple         | PowerMac3,6                 | [36daf7ce75](https://bsd-hardware.info/?probe=36daf7ce75) | Sep 09, 2023 |
| Unknown       | Unknown                     | [3bc1fc9c7b](https://bsd-hardware.info/?probe=3bc1fc9c7b) | Sep 09, 2023 |
| Unknown       | Unknown                     | [68a0e23945](https://bsd-hardware.info/?probe=68a0e23945) | Sep 09, 2023 |
| Techvision    | TVI7309X B0                 | [fe6bcbc332](https://bsd-hardware.info/?probe=fe6bcbc332) | Sep 08, 2023 |
| Techvision    | TVI7309X B0                 | [37e25cbcec](https://bsd-hardware.info/?probe=37e25cbcec) | Sep 08, 2023 |
| Lex           | Pineview-D                  | [351aabdb80](https://bsd-hardware.info/?probe=351aabdb80) | Sep 08, 2023 |
| PC Engines    | APU3                        | [ad38dcf54a](https://bsd-hardware.info/?probe=ad38dcf54a) | Sep 07, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [451cfdf64f](https://bsd-hardware.info/?probe=451cfdf64f) | Sep 06, 2023 |
| Unknown       | Unknown                     | [6361addd62](https://bsd-hardware.info/?probe=6361addd62) | Sep 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [48ca84af37](https://bsd-hardware.info/?probe=48ca84af37) | Sep 06, 2023 |
| PC Engines    | APU2                        | [d582e62190](https://bsd-hardware.info/?probe=d582e62190) | Sep 06, 2023 |
| Unknown       | Unknown                     | [f757c58686](https://bsd-hardware.info/?probe=f757c58686) | Sep 05, 2023 |
| PC Engines    | APU2                        | [c9d2cfe6fa](https://bsd-hardware.info/?probe=c9d2cfe6fa) | Sep 03, 2023 |
| Unknown       | Unknown                     | [53cee3b3c8](https://bsd-hardware.info/?probe=53cee3b3c8) | Sep 03, 2023 |
| Biostar       | J4105NHU                    | [2ac770aa55](https://bsd-hardware.info/?probe=2ac770aa55) | Sep 03, 2023 |
| Inventec      | Z CLASS A02                 | [1f4bf47cab](https://bsd-hardware.info/?probe=1f4bf47cab) | Sep 01, 2023 |
| Unknown       | Unknown                     | [b59ce07b49](https://bsd-hardware.info/?probe=b59ce07b49) | Aug 30, 2023 |
| MW            | GMLK-2_5G4L                 | [56ac0149f8](https://bsd-hardware.info/?probe=56ac0149f8) | Aug 30, 2023 |
| CncTion       | N6000-4L B0                 | [81cbfbffca](https://bsd-hardware.info/?probe=81cbfbffca) | Aug 29, 2023 |
| Unknown       | Unknown                     | [fc384f5de7](https://bsd-hardware.info/?probe=fc384f5de7) | Aug 28, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [a47cd8ee32](https://bsd-hardware.info/?probe=a47cd8ee32) | Aug 27, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [a684024d8e](https://bsd-hardware.info/?probe=a684024d8e) | Aug 27, 2023 |
| PC Engines    | APU                         | [3b29671556](https://bsd-hardware.info/?probe=3b29671556) | Aug 26, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [ed6162710b](https://bsd-hardware.info/?probe=ed6162710b) | Aug 26, 2023 |
| ASUSTek       | H110I-PLUS                  | [a487121854](https://bsd-hardware.info/?probe=a487121854) | Aug 26, 2023 |
| IGEL Techn... | D220                        | [a7686520e1](https://bsd-hardware.info/?probe=a7686520e1) | Aug 26, 2023 |
| Techvision    | TVI7309X B0                 | [662ce63a50](https://bsd-hardware.info/?probe=662ce63a50) | Aug 25, 2023 |
| MW            | GMLK-2_5G4L                 | [8c6f7098f9](https://bsd-hardware.info/?probe=8c6f7098f9) | Aug 25, 2023 |
| CncTion       | N6000-4L B0                 | [d8a9af2435](https://bsd-hardware.info/?probe=d8a9af2435) | Aug 24, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a8fa821e5e](https://bsd-hardware.info/?probe=a8fa821e5e) | Aug 24, 2023 |
| Unknown       | Unknown                     | [74a7137090](https://bsd-hardware.info/?probe=74a7137090) | Aug 22, 2023 |
| ASRock        | A520M-ITX/ac                | [8622d78a7c](https://bsd-hardware.info/?probe=8622d78a7c) | Aug 22, 2023 |
| Gigabyte      | H610I DDR4                  | [f4310832c2](https://bsd-hardware.info/?probe=f4310832c2) | Aug 22, 2023 |
| Intel         | JSL MRD                     | [56165c654b](https://bsd-hardware.info/?probe=56165c654b) | Aug 22, 2023 |
| Unknown       | Unknown                     | [03da20b37e](https://bsd-hardware.info/?probe=03da20b37e) | Aug 22, 2023 |
| Unknown       | MANIFOLD 2-C                | [71e00307ae](https://bsd-hardware.info/?probe=71e00307ae) | Aug 22, 2023 |
| PC Engines    | APU2                        | [3e32acfdc4](https://bsd-hardware.info/?probe=3e32acfdc4) | Aug 22, 2023 |
| Gigabyte      | H110M-D2P-WG-CF             | [a91c61e3e3](https://bsd-hardware.info/?probe=a91c61e3e3) | Aug 21, 2023 |
| Intel         | Q3XXG4-P V1.0               | [ef28836f5c](https://bsd-hardware.info/?probe=ef28836f5c) | Aug 20, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [01d58784e6](https://bsd-hardware.info/?probe=01d58784e6) | Aug 20, 2023 |
| HP            | 8594                        | [b3e5652c1b](https://bsd-hardware.info/?probe=b3e5652c1b) | Aug 20, 2023 |
| HP            | 8594                        | [77d6ac3f77](https://bsd-hardware.info/?probe=77d6ac3f77) | Aug 20, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [b3625ada4b](https://bsd-hardware.info/?probe=b3625ada4b) | Aug 18, 2023 |
| Unknown       | Unknown                     | [de9a146c44](https://bsd-hardware.info/?probe=de9a146c44) | Aug 16, 2023 |
| Unknown       | Q2XX V1.0                   | [be1252b2ff](https://bsd-hardware.info/?probe=be1252b2ff) | Aug 16, 2023 |
| Unknown       | MANIFOLD 2-C                | [18559e2fde](https://bsd-hardware.info/?probe=18559e2fde) | Aug 15, 2023 |
| Unknown       | MANIFOLD 2-C                | [73c35b0a8a](https://bsd-hardware.info/?probe=73c35b0a8a) | Aug 15, 2023 |
| Intel         | SKYBAY                      | [77fbc82e41](https://bsd-hardware.info/?probe=77fbc82e41) | Aug 15, 2023 |
| Protectli     | VP4620                      | [0f0695d190](https://bsd-hardware.info/?probe=0f0695d190) | Aug 15, 2023 |
| PC Engines    | APU2                        | [bdd3050b5f](https://bsd-hardware.info/?probe=bdd3050b5f) | Aug 14, 2023 |
| CncTion       | N5105-4L B0                 | [6c4364fe15](https://bsd-hardware.info/?probe=6c4364fe15) | Aug 13, 2023 |
| PC Engines    | apu4                        | [24e025662c](https://bsd-hardware.info/?probe=24e025662c) | Aug 12, 2023 |
| CncTion       | J4125-4L-I225               | [983bbef1fb](https://bsd-hardware.info/?probe=983bbef1fb) | Aug 12, 2023 |
| WeiBu         | ADL-N Prod                  | [26bbe26e7c](https://bsd-hardware.info/?probe=26bbe26e7c) | Aug 12, 2023 |
| CncTion       | N5105-4L B0                 | [27f84c75b5](https://bsd-hardware.info/?probe=27f84c75b5) | Aug 11, 2023 |
| PC Engines    | APU2                        | [2e9106fc92](https://bsd-hardware.info/?probe=2e9106fc92) | Aug 11, 2023 |
| Gigabyte      | AX370M-DS3H-CF              | [7b00ddd0a1](https://bsd-hardware.info/?probe=7b00ddd0a1) | Aug 11, 2023 |
| PC Engines    | apu1                        | [0b3594d9a3](https://bsd-hardware.info/?probe=0b3594d9a3) | Aug 11, 2023 |
| PC Engines    | apu4                        | [b81f51408d](https://bsd-hardware.info/?probe=b81f51408d) | Aug 10, 2023 |
| PC Engines    | APU2                        | [be0e8bf959](https://bsd-hardware.info/?probe=be0e8bf959) | Aug 09, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [fac2fa5cbe](https://bsd-hardware.info/?probe=fac2fa5cbe) | Aug 08, 2023 |
| Acer          | Veriton N2620G              | [2acf1e4557](https://bsd-hardware.info/?probe=2acf1e4557) | Aug 08, 2023 |
| Techvision    | TVI7309X B0                 | [aeccb6e70c](https://bsd-hardware.info/?probe=aeccb6e70c) | Aug 07, 2023 |
| Lanner        | FW-7543 B-GA                | [dadf592128](https://bsd-hardware.info/?probe=dadf592128) | Aug 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [eceed9eb7a](https://bsd-hardware.info/?probe=eceed9eb7a) | Aug 05, 2023 |
| Unknown       | Unknown                     | [9c4dbcfd67](https://bsd-hardware.info/?probe=9c4dbcfd67) | Aug 05, 2023 |
| Lanner        | FW-7543 B-GA                | [6236e692de](https://bsd-hardware.info/?probe=6236e692de) | Aug 05, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [283fce4c68](https://bsd-hardware.info/?probe=283fce4c68) | Aug 05, 2023 |
| CWWK          | MINIPC-G12                  | [c449203453](https://bsd-hardware.info/?probe=c449203453) | Aug 04, 2023 |
| Lenovo        | SHARKBAY NO DPK             | [62ed2f59f6](https://bsd-hardware.info/?probe=62ed2f59f6) | Aug 04, 2023 |
| PC Engines    | APU2                        | [78c8ed6a89](https://bsd-hardware.info/?probe=78c8ed6a89) | Aug 03, 2023 |
| Shuttle       | DH610                       | [bbdd78fe4b](https://bsd-hardware.info/?probe=bbdd78fe4b) | Aug 01, 2023 |
| Unknown       | Unknown                     | [42c65b8b8b](https://bsd-hardware.info/?probe=42c65b8b8b) | Aug 01, 2023 |
| Hardkernel    | ODROID-H3                   | [aa708122cf](https://bsd-hardware.info/?probe=aa708122cf) | Aug 01, 2023 |
| Shuttle       | DH610                       | [e7c63c97d3](https://bsd-hardware.info/?probe=e7c63c97d3) | Aug 01, 2023 |
| Shuttle       | DH370                       | [a3ab1c6344](https://bsd-hardware.info/?probe=a3ab1c6344) | Jul 31, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [64137e0eec](https://bsd-hardware.info/?probe=64137e0eec) | Jul 29, 2023 |
| PC Engines    | APU2                        | [5eddd5369a](https://bsd-hardware.info/?probe=5eddd5369a) | Jul 28, 2023 |
| Hardkernel    | ODROID-H3                   | [0bb6b16689](https://bsd-hardware.info/?probe=0bb6b16689) | Jul 28, 2023 |
| Unknown       | Unknown                     | [1c6ab6b999](https://bsd-hardware.info/?probe=1c6ab6b999) | Jul 28, 2023 |
| PC Engines    | apu1                        | [8bc97daada](https://bsd-hardware.info/?probe=8bc97daada) | Jul 27, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [64b577cd8e](https://bsd-hardware.info/?probe=64b577cd8e) | Jul 27, 2023 |
| NF541         | 1.0                         | [ba959613a5](https://bsd-hardware.info/?probe=ba959613a5) | Jul 26, 2023 |
| Cisco         | ASA5525 A0                  | [f4409bdc8f](https://bsd-hardware.info/?probe=f4409bdc8f) | Jul 26, 2023 |
| Unknown       | Unknown                     | [f7728cee03](https://bsd-hardware.info/?probe=f7728cee03) | Jul 25, 2023 |
| Unknown       | MANIFOLD 2-C                | [8aa3f5491e](https://bsd-hardware.info/?probe=8aa3f5491e) | Jul 25, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [af215ad226](https://bsd-hardware.info/?probe=af215ad226) | Jul 24, 2023 |
| PC Engines    | apu4                        | [0aa9951131](https://bsd-hardware.info/?probe=0aa9951131) | Jul 24, 2023 |
| PC Engines    | apu4                        | [514dc1e9f9](https://bsd-hardware.info/?probe=514dc1e9f9) | Jul 24, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [dec2c34899](https://bsd-hardware.info/?probe=dec2c34899) | Jul 24, 2023 |
| Unknown       | Unknown                     | [aab49bd228](https://bsd-hardware.info/?probe=aab49bd228) | Jul 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [438424a9d9](https://bsd-hardware.info/?probe=438424a9d9) | Jul 23, 2023 |
| PC Engines    | apu4                        | [ea9a81b423](https://bsd-hardware.info/?probe=ea9a81b423) | Jul 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [3b16dab962](https://bsd-hardware.info/?probe=3b16dab962) | Jul 22, 2023 |
| Protectli     | FW6 Ver                     | [7e1b416d09](https://bsd-hardware.info/?probe=7e1b416d09) | Jul 21, 2023 |
| Yanling       | YL-CLU6L-V1                 | [489c685ec4](https://bsd-hardware.info/?probe=489c685ec4) | Jul 21, 2023 |
| AZW           | EQ                          | [9883a89b8d](https://bsd-hardware.info/?probe=9883a89b8d) | Jul 21, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [efe49f9e5d](https://bsd-hardware.info/?probe=efe49f9e5d) | Jul 20, 2023 |
| Unknown       | Unknown                     | [cce6d65dfb](https://bsd-hardware.info/?probe=cce6d65dfb) | Jul 20, 2023 |
| Unknown       | Unknown                     | [e487955dea](https://bsd-hardware.info/?probe=e487955dea) | Jul 18, 2023 |
| ASUSTek       | Maximus VIII HERO           | [35ab9e002d](https://bsd-hardware.info/?probe=35ab9e002d) | Jul 17, 2023 |
| Unknown       | Unknown                     | [8d82f25df2](https://bsd-hardware.info/?probe=8d82f25df2) | Jul 16, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a2602b7fbf](https://bsd-hardware.info/?probe=a2602b7fbf) | Jul 16, 2023 |
| Gigabyte      | GB-BSi7-1165G7              | [c5f92a4c5e](https://bsd-hardware.info/?probe=c5f92a4c5e) | Jul 14, 2023 |
| MW            | GMLK-2_5G4L                 | [0b90f241cd](https://bsd-hardware.info/?probe=0b90f241cd) | Jul 13, 2023 |
| PICO PC       | JSL-4L                      | [d93e338744](https://bsd-hardware.info/?probe=d93e338744) | Jul 13, 2023 |
| Gigabyte      | B450M H                     | [c2cb1e21fa](https://bsd-hardware.info/?probe=c2cb1e21fa) | Jul 11, 2023 |
| ASRock        | A520M-ITX/ac                | [96bda9f774](https://bsd-hardware.info/?probe=96bda9f774) | Jul 11, 2023 |
| Unknown       | Unknown                     | [5625dd24f6](https://bsd-hardware.info/?probe=5625dd24f6) | Jul 11, 2023 |
| PICO PC       | JSL-4L                      | [d8c9a61dcf](https://bsd-hardware.info/?probe=d8c9a61dcf) | Jul 10, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [3a544928aa](https://bsd-hardware.info/?probe=3a544928aa) | Jul 09, 2023 |
| MiTAC         | PH13CMI                     | [6d0cd37fce](https://bsd-hardware.info/?probe=6d0cd37fce) | Jul 09, 2023 |
| Biostar       | A68N-2100K                  | [20cb208208](https://bsd-hardware.info/?probe=20cb208208) | Jul 09, 2023 |
| Lex           | Pineview-D                  | [290c53a822](https://bsd-hardware.info/?probe=290c53a822) | Jul 09, 2023 |
| Yanling       | YL-ELU3L                    | [0a3c74b25c](https://bsd-hardware.info/?probe=0a3c74b25c) | Jul 07, 2023 |
| ASRock        | A300M-STX                   | [5d896a607e](https://bsd-hardware.info/?probe=5d896a607e) | Jul 06, 2023 |
| Unknown       | Unknown                     | [3644875d54](https://bsd-hardware.info/?probe=3644875d54) | Jul 03, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [2053dbb697](https://bsd-hardware.info/?probe=2053dbb697) | Jul 03, 2023 |
| PC Engines    | apu4                        | [62f0b60653](https://bsd-hardware.info/?probe=62f0b60653) | Jun 30, 2023 |
| Dell          | 00V62H A01                  | [d60c967edb](https://bsd-hardware.info/?probe=d60c967edb) | Jun 29, 2023 |
| Unknown       | Unknown                     | [075deef24f](https://bsd-hardware.info/?probe=075deef24f) | Jun 28, 2023 |
| CncTion       | J4125-4L-I225               | [1785cb2fa3](https://bsd-hardware.info/?probe=1785cb2fa3) | Jun 28, 2023 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [bcad942162](https://bsd-hardware.info/?probe=bcad942162) | Jun 26, 2023 |
| Unknown       | YL-SKUL6                    | [1512f63972](https://bsd-hardware.info/?probe=1512f63972) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | [fa177a2538](https://bsd-hardware.info/?probe=fa177a2538) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | [54ef7dc131](https://bsd-hardware.info/?probe=54ef7dc131) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | [b056cd0426](https://bsd-hardware.info/?probe=b056cd0426) | Jun 26, 2023 |
| Unknown       | J3160-4L                    | [5ad411cd6b](https://bsd-hardware.info/?probe=5ad411cd6b) | Jun 25, 2023 |
| Hardkernel    | ODROID-H3                   | [8a2ea60929](https://bsd-hardware.info/?probe=8a2ea60929) | Jun 25, 2023 |
| Techvision    | TVI7309X B0                 | [18cf91f3a4](https://bsd-hardware.info/?probe=18cf91f3a4) | Jun 23, 2023 |
| Intel         | Q3XXG4-P V1.0               | [bb4dc2b1a2](https://bsd-hardware.info/?probe=bb4dc2b1a2) | Jun 23, 2023 |
| Unknown       | Unknown                     | [16ceade742](https://bsd-hardware.info/?probe=16ceade742) | Jun 23, 2023 |
| Unknown       | Unknown                     | [508aa0bdb4](https://bsd-hardware.info/?probe=508aa0bdb4) | Jun 23, 2023 |
| Yanling       | YL-KBRL2 Series Ver:1.02    | [9e8d6110f4](https://bsd-hardware.info/?probe=9e8d6110f4) | Jun 19, 2023 |
| LANCOM Sys... | UF-60                       | [96904b8bdd](https://bsd-hardware.info/?probe=96904b8bdd) | Jun 19, 2023 |
| Unknown       | Unknown                     | [5fc629699d](https://bsd-hardware.info/?probe=5fc629699d) | Jun 18, 2023 |
| ASRock        | Z97 Professional            | [c978ddda86](https://bsd-hardware.info/?probe=c978ddda86) | Jun 18, 2023 |
| AMD           | Kabini CRB                  | [b774a8b586](https://bsd-hardware.info/?probe=b774a8b586) | Jun 16, 2023 |
| CncTion       | N5105-4L B0                 | [b9c5b6ec05](https://bsd-hardware.info/?probe=b9c5b6ec05) | Jun 15, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [70b0e8172d](https://bsd-hardware.info/?probe=70b0e8172d) | Jun 14, 2023 |
| PC Engines    | apu4                        | [ea036662ca](https://bsd-hardware.info/?probe=ea036662ca) | Jun 14, 2023 |
| Unknown       | J3160-4L                    | [4a6667249e](https://bsd-hardware.info/?probe=4a6667249e) | Jun 13, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [015a5d839a](https://bsd-hardware.info/?probe=015a5d839a) | Jun 13, 2023 |
| Unknown       | Unknown                     | [27617e1ca6](https://bsd-hardware.info/?probe=27617e1ca6) | Jun 13, 2023 |
| HP            | 3397                        | [a918ce0c4b](https://bsd-hardware.info/?probe=a918ce0c4b) | Jun 12, 2023 |
| CWWK          | MINIPC-G12                  | [04ae7435e5](https://bsd-hardware.info/?probe=04ae7435e5) | Jun 12, 2023 |
| MSI           | A320M GRENADE               | [6e0b1f598f](https://bsd-hardware.info/?probe=6e0b1f598f) | Jun 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [02509df772](https://bsd-hardware.info/?probe=02509df772) | Jun 12, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [2d2052de27](https://bsd-hardware.info/?probe=2d2052de27) | Jun 11, 2023 |
| Unknown       | Unknown                     | [8988baa83b](https://bsd-hardware.info/?probe=8988baa83b) | Jun 10, 2023 |
| Unknown       | Unknown                     | [40bb474319](https://bsd-hardware.info/?probe=40bb474319) | Jun 10, 2023 |
| ASRock        | B85M-HDS                    | [09a4700a14](https://bsd-hardware.info/?probe=09a4700a14) | Jun 09, 2023 |
| Wortmann      | terra Nettop 2700           | [e4a90ea530](https://bsd-hardware.info/?probe=e4a90ea530) | Jun 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | [1ae49c4706](https://bsd-hardware.info/?probe=1ae49c4706) | Jun 08, 2023 |
| Intel         | SKYBAY                      | [f1b649ed11](https://bsd-hardware.info/?probe=f1b649ed11) | Jun 08, 2023 |
| Lanner        | FW-7543 B-GA                | [ee85efd1c0](https://bsd-hardware.info/?probe=ee85efd1c0) | Jun 08, 2023 |
| LANCOM Sys... | UF-60                       | [204f10b60f](https://bsd-hardware.info/?probe=204f10b60f) | Jun 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | [4e57bbcdb5](https://bsd-hardware.info/?probe=4e57bbcdb5) | Jun 06, 2023 |
| Intel         | DENLOW_WS                   | [ce3bef7b5a](https://bsd-hardware.info/?probe=ce3bef7b5a) | Jun 06, 2023 |
| CncTion       | N6000-4L B0                 | [c9ec51aa84](https://bsd-hardware.info/?probe=c9ec51aa84) | Jun 05, 2023 |
| HP            | 3397                        | [6783902b93](https://bsd-hardware.info/?probe=6783902b93) | Jun 05, 2023 |
| Hardkernel    | ODROID-H3                   | [42e80f8003](https://bsd-hardware.info/?probe=42e80f8003) | Jun 05, 2023 |
| Dell          | 0PC5F7 A03                  | [23bd5ef252](https://bsd-hardware.info/?probe=23bd5ef252) | Jun 04, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [56a9981ff3](https://bsd-hardware.info/?probe=56a9981ff3) | Jun 03, 2023 |
| PC Engines    | APU2                        | [31c697459b](https://bsd-hardware.info/?probe=31c697459b) | Jun 02, 2023 |
| HP            | 3397                        | [1f8a9a4f27](https://bsd-hardware.info/?probe=1f8a9a4f27) | May 29, 2023 |
| ASRock        | H410M/ac                    | [d3e3d20cc4](https://bsd-hardware.info/?probe=d3e3d20cc4) | May 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | [2827d90215](https://bsd-hardware.info/?probe=2827d90215) | May 28, 2023 |
| HP            | 3397                        | [036d4e087c](https://bsd-hardware.info/?probe=036d4e087c) | May 27, 2023 |
| HP            | 3397                        | [19abd8768e](https://bsd-hardware.info/?probe=19abd8768e) | May 27, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [81775d5ca1](https://bsd-hardware.info/?probe=81775d5ca1) | May 26, 2023 |
| Nitrokey      | NitroWall                   | [1b3b451dee](https://bsd-hardware.info/?probe=1b3b451dee) | May 24, 2023 |
| Unknown       | Unknown                     | [4c7e1d476d](https://bsd-hardware.info/?probe=4c7e1d476d) | May 23, 2023 |
| Nitrokey      | NitroWall                   | [ef701f3991](https://bsd-hardware.info/?probe=ef701f3991) | May 23, 2023 |
| Unknown       | QD-WHLU01                   | [700bcad7cc](https://bsd-hardware.info/?probe=700bcad7cc) | May 22, 2023 |
| HP            | 158B                        | [1ef3762103](https://bsd-hardware.info/?probe=1ef3762103) | May 20, 2023 |
| HP            | 158B                        | [a9c63041a6](https://bsd-hardware.info/?probe=a9c63041a6) | May 20, 2023 |
| ZOTAC         | Unknown                     | [8156e3fede](https://bsd-hardware.info/?probe=8156e3fede) | May 19, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [612e3a21d4](https://bsd-hardware.info/?probe=612e3a21d4) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [8f3c5de741](https://bsd-hardware.info/?probe=8f3c5de741) | May 19, 2023 |
| VIA Techno... | VT82C597                    | [d73db58e48](https://bsd-hardware.info/?probe=d73db58e48) | May 19, 2023 |
| ASUSTek       | PRO B460M-C                 | [9350bb37db](https://bsd-hardware.info/?probe=9350bb37db) | May 18, 2023 |
| Medion        | MS-7633                     | [c01f7b9894](https://bsd-hardware.info/?probe=c01f7b9894) | May 18, 2023 |
| Supermicro    | H8DM8-2                     | [68c51b6006](https://bsd-hardware.info/?probe=68c51b6006) | May 18, 2023 |
| CncTion       | N5105-4L-I226 B0            | [75f5674d44](https://bsd-hardware.info/?probe=75f5674d44) | May 18, 2023 |
| HP            | 3397                        | [d405f14bb9](https://bsd-hardware.info/?probe=d405f14bb9) | May 18, 2023 |
| Unknown       | Unknown                     | [fff8127c3f](https://bsd-hardware.info/?probe=fff8127c3f) | May 17, 2023 |
| Unknown       | Unknown                     | [cc27c738be](https://bsd-hardware.info/?probe=cc27c738be) | May 17, 2023 |
| PC Engines    | apu4                        | [7fe2bf9ad6](https://bsd-hardware.info/?probe=7fe2bf9ad6) | May 16, 2023 |
| PC Engines    | apu4                        | [7723fe0a0a](https://bsd-hardware.info/?probe=7723fe0a0a) | May 16, 2023 |
| ASUSTek       | H110I-PLUS                  | [37922a69a6](https://bsd-hardware.info/?probe=37922a69a6) | May 15, 2023 |
| Lenovo        | SHARKBAY NOK                | [2b4ece70c9](https://bsd-hardware.info/?probe=2b4ece70c9) | May 15, 2023 |
| ASRock        | AM1B-ITX                    | [8ad16a1805](https://bsd-hardware.info/?probe=8ad16a1805) | May 15, 2023 |
| PC Engines    | APU2                        | [62fef2616b](https://bsd-hardware.info/?probe=62fef2616b) | May 15, 2023 |
| MSI           | B85M-G43                    | [6d2160dcee](https://bsd-hardware.info/?probe=6d2160dcee) | May 14, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [7332aba586](https://bsd-hardware.info/?probe=7332aba586) | May 14, 2023 |
| Fujitsu       | D3823-A2 S26361-D3823-Ax... | [2528087de1](https://bsd-hardware.info/?probe=2528087de1) | May 11, 2023 |
| Unknown       | Unknown                     | [eee23dec87](https://bsd-hardware.info/?probe=eee23dec87) | May 11, 2023 |
| ASUSTek       | H110I-PLUS                  | [2543ed83b9](https://bsd-hardware.info/?probe=2543ed83b9) | May 10, 2023 |
| Fujitsu       | D3644-B1 S26361-D3644-B1    | [b2e52b5677](https://bsd-hardware.info/?probe=b2e52b5677) | May 10, 2023 |
| Techvision    | TVI7309X B0                 | [fbf3fde510](https://bsd-hardware.info/?probe=fbf3fde510) | May 09, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [96abd89bab](https://bsd-hardware.info/?probe=96abd89bab) | May 09, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [38243e0313](https://bsd-hardware.info/?probe=38243e0313) | May 09, 2023 |
| PC Engines    | APU2                        | [6aff35010a](https://bsd-hardware.info/?probe=6aff35010a) | May 08, 2023 |
| Hardkernel    | ODROID-H3                   | [5b669f261f](https://bsd-hardware.info/?probe=5b669f261f) | May 08, 2023 |
| Unknown       | T100                        | [fb9c6bff7b](https://bsd-hardware.info/?probe=fb9c6bff7b) | May 07, 2023 |
| Supermicro    | X12STN-C-WOHS               | [d8cf344aee](https://bsd-hardware.info/?probe=d8cf344aee) | May 06, 2023 |
| Unknown       | Unknown                     | [349e1709cd](https://bsd-hardware.info/?probe=349e1709cd) | May 06, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [c29d140ee6](https://bsd-hardware.info/?probe=c29d140ee6) | May 06, 2023 |
| Lanner        | FW-7543 B-GA                | [8346fdf608](https://bsd-hardware.info/?probe=8346fdf608) | May 03, 2023 |
| HP            | 1589                        | [4aee1909c8](https://bsd-hardware.info/?probe=4aee1909c8) | May 03, 2023 |
| ASRock        | A520M-ITX/ac                | [70b09db335](https://bsd-hardware.info/?probe=70b09db335) | May 02, 2023 |
| ASRock        | A520M-ITX/ac                | [eb61af55d5](https://bsd-hardware.info/?probe=eb61af55d5) | May 01, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [8227d6d32c](https://bsd-hardware.info/?probe=8227d6d32c) | Apr 30, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [f86a94eb66](https://bsd-hardware.info/?probe=f86a94eb66) | Apr 30, 2023 |
| Protectli     | VP2420                      | [4ea8453453](https://bsd-hardware.info/?probe=4ea8453453) | Apr 30, 2023 |
| Protectli     | VP2420                      | [46a00b21d9](https://bsd-hardware.info/?probe=46a00b21d9) | Apr 30, 2023 |
| Protectli     | FW4B                        | [048da71e18](https://bsd-hardware.info/?probe=048da71e18) | Apr 29, 2023 |
| PC Engines    | apu1                        | [1a37e9d978](https://bsd-hardware.info/?probe=1a37e9d978) | Apr 27, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [989f3b44bf](https://bsd-hardware.info/?probe=989f3b44bf) | Apr 26, 2023 |
| Supermicro    | X11SDW-8C-TP13F             | [94316d20c8](https://bsd-hardware.info/?probe=94316d20c8) | Apr 26, 2023 |
| MiTAC         | PH13CMI                     | [5d3e954049](https://bsd-hardware.info/?probe=5d3e954049) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [0c8a0100c5](https://bsd-hardware.info/?probe=0c8a0100c5) | Apr 23, 2023 |
| Techvision    | TVI7309X B0                 | [ad73cda832](https://bsd-hardware.info/?probe=ad73cda832) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [775424cbff](https://bsd-hardware.info/?probe=775424cbff) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c26c1111c6](https://bsd-hardware.info/?probe=c26c1111c6) | Apr 21, 2023 |
| Techvision    | TVI7309X B0                 | [215364d870](https://bsd-hardware.info/?probe=215364d870) | Apr 21, 2023 |
| Techvision    | TVI7309X B0                 | [fdbbde509c](https://bsd-hardware.info/?probe=fdbbde509c) | Apr 20, 2023 |
| PC Engines    | APU2                        | [59b3a3eebf](https://bsd-hardware.info/?probe=59b3a3eebf) | Apr 19, 2023 |
| ASUSTek       | Pro B560M-C                 | [b341a9c9c9](https://bsd-hardware.info/?probe=b341a9c9c9) | Apr 19, 2023 |
| Unknown       | Unknown                     | [311e89be7a](https://bsd-hardware.info/?probe=311e89be7a) | Apr 18, 2023 |
| CncTion       | J4125-4L-I225               | [b4fd4e35b2](https://bsd-hardware.info/?probe=b4fd4e35b2) | Apr 18, 2023 |
| Supermicro    | X11SDW-8C-TP13F             | [20fac0b7a5](https://bsd-hardware.info/?probe=20fac0b7a5) | Apr 18, 2023 |
| Unknown       | Unknown                     | [f5153e1b18](https://bsd-hardware.info/?probe=f5153e1b18) | Apr 17, 2023 |
| CncTion       | N5105-4L B0                 | [6de7890035](https://bsd-hardware.info/?probe=6de7890035) | Apr 17, 2023 |
| Unknown       | Unknown                     | [56505e8956](https://bsd-hardware.info/?probe=56505e8956) | Apr 16, 2023 |
| Intel         | Q3XXG4-P V1.0               | [4fbc5291d9](https://bsd-hardware.info/?probe=4fbc5291d9) | Apr 16, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a29966f9ee](https://bsd-hardware.info/?probe=a29966f9ee) | Apr 16, 2023 |
| Unknown       | Unknown                     | [94151c41f1](https://bsd-hardware.info/?probe=94151c41f1) | Apr 14, 2023 |
| Unknown       | YL-SKUL6-7 Series           | [627e7a86c6](https://bsd-hardware.info/?probe=627e7a86c6) | Apr 13, 2023 |
| CncTion       | N5105-4L-I226 B0            | [0c7855ee11](https://bsd-hardware.info/?probe=0c7855ee11) | Apr 13, 2023 |
| Advantech     | UNO-2271G_V2                | [23e4b8d9b1](https://bsd-hardware.info/?probe=23e4b8d9b1) | Apr 12, 2023 |
| ASUSTek       | P10S-M Series               | [0b060edc48](https://bsd-hardware.info/?probe=0b060edc48) | Apr 12, 2023 |
| MW            | GMLK-2_5G4L                 | [9b1dbe0b9a](https://bsd-hardware.info/?probe=9b1dbe0b9a) | Apr 11, 2023 |
| Unknown       | Unknown                     | [cfa755bf6d](https://bsd-hardware.info/?probe=cfa755bf6d) | Apr 11, 2023 |
| CncTion       | N5105-4L-I226 B0            | [65d80d8aeb](https://bsd-hardware.info/?probe=65d80d8aeb) | Apr 09, 2023 |
| Gigabyte      | H610I DDR4                  | [59d65282c3](https://bsd-hardware.info/?probe=59d65282c3) | Apr 08, 2023 |
| ASRock        | A520M-ITX/ac                | [7a0ca560df](https://bsd-hardware.info/?probe=7a0ca560df) | Apr 08, 2023 |
| Unknown       | MANIFOLD 2-C                | [8fb3cbee23](https://bsd-hardware.info/?probe=8fb3cbee23) | Apr 07, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [f1cabdb067](https://bsd-hardware.info/?probe=f1cabdb067) | Apr 06, 2023 |
| Dell          | 04Y8V0 A02                  | [b4dab62ac2](https://bsd-hardware.info/?probe=b4dab62ac2) | Apr 05, 2023 |
| Dell          | 04Y8V0 A02                  | [24d7b97629](https://bsd-hardware.info/?probe=24d7b97629) | Apr 05, 2023 |
| Lanner        | FW-8771 C-GA                | [90d7028263](https://bsd-hardware.info/?probe=90d7028263) | Apr 05, 2023 |
| PC Engines    | apu4                        | [e91a75d782](https://bsd-hardware.info/?probe=e91a75d782) | Apr 05, 2023 |
| Intel         | SKYBAY                      | [81655c4fd5](https://bsd-hardware.info/?probe=81655c4fd5) | Apr 05, 2023 |
| maiyunda      | www.maiyunda.com            | [7cf52a3977](https://bsd-hardware.info/?probe=7cf52a3977) | Apr 03, 2023 |
| Techvision    | TVI7309X B0                 | [ca1360b939](https://bsd-hardware.info/?probe=ca1360b939) | Apr 03, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [bea5641594](https://bsd-hardware.info/?probe=bea5641594) | Apr 02, 2023 |
| MSI           | B450M MORTAR MAX            | [01bf5e8678](https://bsd-hardware.info/?probe=01bf5e8678) | Apr 02, 2023 |
| HP            | 8298                        | [60c66c5066](https://bsd-hardware.info/?probe=60c66c5066) | Mar 30, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [bde9fd671b](https://bsd-hardware.info/?probe=bde9fd671b) | Mar 30, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a160027cc2](https://bsd-hardware.info/?probe=a160027cc2) | Mar 30, 2023 |
| Dell          | 0VG93V A00                  | [1f3e086401](https://bsd-hardware.info/?probe=1f3e086401) | Mar 30, 2023 |
| Intel         | JSL MRD                     | [07adf23a3d](https://bsd-hardware.info/?probe=07adf23a3d) | Mar 28, 2023 |
| CncTion       | N5105-4L B0                 | [b6fd7cd6ae](https://bsd-hardware.info/?probe=b6fd7cd6ae) | Mar 27, 2023 |
| Shuttle       | FS81                        | [b80626e045](https://bsd-hardware.info/?probe=b80626e045) | Mar 26, 2023 |
| Lanner        | FW-7543 B-GA                | [3ed4cfc9c8](https://bsd-hardware.info/?probe=3ed4cfc9c8) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [15e452d25d](https://bsd-hardware.info/?probe=15e452d25d) | Mar 26, 2023 |
| Intel         | Q3XXG4-P V1.0               | [2f16e29f78](https://bsd-hardware.info/?probe=2f16e29f78) | Mar 26, 2023 |
| Protectli     | FW4B Ver                    | [fc5ab682fc](https://bsd-hardware.info/?probe=fc5ab682fc) | Mar 26, 2023 |
| Protectli     | FW4B Ver                    | [5082d62025](https://bsd-hardware.info/?probe=5082d62025) | Mar 25, 2023 |
| MW            | GMLK-2_5G4L                 | [41fa3f51d3](https://bsd-hardware.info/?probe=41fa3f51d3) | Mar 25, 2023 |
| Unknown       | Unknown                     | [387c27f1d7](https://bsd-hardware.info/?probe=387c27f1d7) | Mar 25, 2023 |
| PC Engines    | APU2                        | [4e4a81e456](https://bsd-hardware.info/?probe=4e4a81e456) | Mar 24, 2023 |
| Lex           | Pineview-D                  | [ca2fbb614d](https://bsd-hardware.info/?probe=ca2fbb614d) | Mar 24, 2023 |
| CncTion       | N5105-4L B0                 | [9561c72b9c](https://bsd-hardware.info/?probe=9561c72b9c) | Mar 24, 2023 |
| Intel         | Q3XXG4-P V1.0               | [083d2e65da](https://bsd-hardware.info/?probe=083d2e65da) | Mar 24, 2023 |
| ASRock        | A520M-ITX/ac                | [18877701a6](https://bsd-hardware.info/?probe=18877701a6) | Mar 24, 2023 |
| Protectli     | VP2420                      | [f07553b02c](https://bsd-hardware.info/?probe=f07553b02c) | Mar 23, 2023 |
| Protectli     | VP2420                      | [dfad78899e](https://bsd-hardware.info/?probe=dfad78899e) | Mar 23, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [720f15a1ce](https://bsd-hardware.info/?probe=720f15a1ce) | Mar 23, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [491c0ca78a](https://bsd-hardware.info/?probe=491c0ca78a) | Mar 22, 2023 |
| Intel         | Q3XXG4-P V1.0               | [680002292e](https://bsd-hardware.info/?probe=680002292e) | Mar 22, 2023 |
| MW            | GMLK-2_5G4L                 | [b3f0879ebf](https://bsd-hardware.info/?probe=b3f0879ebf) | Mar 22, 2023 |
| Intel         | SKYBAY                      | [83ea0b27b1](https://bsd-hardware.info/?probe=83ea0b27b1) | Mar 21, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [bcada44b09](https://bsd-hardware.info/?probe=bcada44b09) | Mar 21, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | [7ae004c035](https://bsd-hardware.info/?probe=7ae004c035) | Mar 21, 2023 |
| Unknown       | Unknown                     | [e4365dfa60](https://bsd-hardware.info/?probe=e4365dfa60) | Mar 20, 2023 |
| ASRock        | B550M Pro4                  | [4dc54510d2](https://bsd-hardware.info/?probe=4dc54510d2) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | [cab50cddd5](https://bsd-hardware.info/?probe=cab50cddd5) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | [ff4dda40eb](https://bsd-hardware.info/?probe=ff4dda40eb) | Mar 19, 2023 |
| Intel         | SKYBAY                      | [7bd7f393b1](https://bsd-hardware.info/?probe=7bd7f393b1) | Mar 18, 2023 |
| Intel         | SKYBAY                      | [a8f1d29e24](https://bsd-hardware.info/?probe=a8f1d29e24) | Mar 18, 2023 |
| MSI           | X299 PRO                    | [a26d096ecb](https://bsd-hardware.info/?probe=a26d096ecb) | Mar 18, 2023 |
| Fujitsu       | D3313-S3 S26361-D3313-S3    | [1bf34a929a](https://bsd-hardware.info/?probe=1bf34a929a) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2ceda5b586](https://bsd-hardware.info/?probe=2ceda5b586) | Mar 17, 2023 |
| ASRock        | J5040-ITX                   | [435dc7ee7b](https://bsd-hardware.info/?probe=435dc7ee7b) | Mar 15, 2023 |
| Unknown       | Unknown                     | [68b45d5083](https://bsd-hardware.info/?probe=68b45d5083) | Mar 15, 2023 |
| ASRock        | A520M-ITX/ac                | [1ccc8081fd](https://bsd-hardware.info/?probe=1ccc8081fd) | Mar 15, 2023 |
| Foxconn       | H61M/H61M-S                 | [865fbff42a](https://bsd-hardware.info/?probe=865fbff42a) | Mar 14, 2023 |
| ASRock        | Q1900M                      | [9570525d52](https://bsd-hardware.info/?probe=9570525d52) | Mar 14, 2023 |
| MW            | GMLK-2_5G4L                 | [5211185a2a](https://bsd-hardware.info/?probe=5211185a2a) | Mar 14, 2023 |
| HP            | 8056                        | [e1d2423153](https://bsd-hardware.info/?probe=e1d2423153) | Mar 13, 2023 |
| HP            | 8056                        | [d89b45ea6d](https://bsd-hardware.info/?probe=d89b45ea6d) | Mar 13, 2023 |
| Dell          | 0W0CHX A00                  | [85a9fddd44](https://bsd-hardware.info/?probe=85a9fddd44) | Mar 12, 2023 |
| MW            | GMLK-2_5G4L                 | [fee0ff7804](https://bsd-hardware.info/?probe=fee0ff7804) | Mar 12, 2023 |
| Acer          | Veriton N2620G              | [fa57448331](https://bsd-hardware.info/?probe=fa57448331) | Mar 12, 2023 |
| ASUSTek       | P8Z68-V                     | [3d8ef63e18](https://bsd-hardware.info/?probe=3d8ef63e18) | Mar 11, 2023 |
| ASUSTek       | H110I-PLUS                  | [8736b12c9a](https://bsd-hardware.info/?probe=8736b12c9a) | Mar 11, 2023 |
| MSI           | X299 PRO                    | [0cebc094ca](https://bsd-hardware.info/?probe=0cebc094ca) | Mar 10, 2023 |
| Unknown       | Unknown                     | [2a55137e71](https://bsd-hardware.info/?probe=2a55137e71) | Mar 10, 2023 |
| CheckPoint    | PH-30-00                    | [ec7a5f05fd](https://bsd-hardware.info/?probe=ec7a5f05fd) | Mar 09, 2023 |
| Unknown       | Unknown                     | [d7b171d0bb](https://bsd-hardware.info/?probe=d7b171d0bb) | Mar 09, 2023 |
| Protectli     | VP2420                      | [21d2214da6](https://bsd-hardware.info/?probe=21d2214da6) | Mar 08, 2023 |
| Unknown       | Unknown                     | [86c132c242](https://bsd-hardware.info/?probe=86c132c242) | Mar 07, 2023 |
| MW            | GMLK-2_5G4L                 | [b91b7cf52d](https://bsd-hardware.info/?probe=b91b7cf52d) | Mar 06, 2023 |
| Techvision    | TVI7309X B0                 | [789ae683f7](https://bsd-hardware.info/?probe=789ae683f7) | Mar 05, 2023 |
| ASUSTek       | PRO B460M-C                 | [a3f77b82cc](https://bsd-hardware.info/?probe=a3f77b82cc) | Mar 05, 2023 |
| Dell          | VEP-4600-V910 0PDG1JA02     | [5070c11c54](https://bsd-hardware.info/?probe=5070c11c54) | Mar 05, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [3d912f92aa](https://bsd-hardware.info/?probe=3d912f92aa) | Mar 05, 2023 |
| ASRock        | E350M1                      | [461f8cca23](https://bsd-hardware.info/?probe=461f8cca23) | Mar 04, 2023 |
| Techvision    | TVI7309X B0                 | [6067b3f58d](https://bsd-hardware.info/?probe=6067b3f58d) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | [bbbd05a4c3](https://bsd-hardware.info/?probe=bbbd05a4c3) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | [9ab07ae7f1](https://bsd-hardware.info/?probe=9ab07ae7f1) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | [228816d44e](https://bsd-hardware.info/?probe=228816d44e) | Mar 03, 2023 |
| Unknown       | Unknown                     | [81bf3cf726](https://bsd-hardware.info/?probe=81bf3cf726) | Mar 03, 2023 |
| Intel         | DENLOW_WS                   | [2b70fdb96a](https://bsd-hardware.info/?probe=2b70fdb96a) | Mar 02, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [29290b1b9c](https://bsd-hardware.info/?probe=29290b1b9c) | Mar 01, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [5eb87a21db](https://bsd-hardware.info/?probe=5eb87a21db) | Mar 01, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [39d5f658ce](https://bsd-hardware.info/?probe=39d5f658ce) | Feb 28, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [dcf3f03ddc](https://bsd-hardware.info/?probe=dcf3f03ddc) | Feb 28, 2023 |
| Supermicro    | PDSBM                       | [1dea83dd64](https://bsd-hardware.info/?probe=1dea83dd64) | Feb 26, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [27e756f63d](https://bsd-hardware.info/?probe=27e756f63d) | Feb 26, 2023 |
| Foxconn       | 2A8Ch                       | [96a8673b26](https://bsd-hardware.info/?probe=96a8673b26) | Feb 26, 2023 |
| NF541         | 1.0                         | [863e6235d4](https://bsd-hardware.info/?probe=863e6235d4) | Feb 26, 2023 |
| Unknown       | YL-J3160L4                  | [b774e80761](https://bsd-hardware.info/?probe=b774e80761) | Feb 25, 2023 |
| ASRock        | X470 Gaming K4              | [fbff29a62a](https://bsd-hardware.info/?probe=fbff29a62a) | Feb 25, 2023 |
| Unknown       | Unknown                     | [87ad08a144](https://bsd-hardware.info/?probe=87ad08a144) | Feb 25, 2023 |
| Lenovo        | ThinkCentre M91p 7033A2G    | [25528a00f3](https://bsd-hardware.info/?probe=25528a00f3) | Feb 24, 2023 |
| MSI           | X299 PRO                    | [3ca12f88d9](https://bsd-hardware.info/?probe=3ca12f88d9) | Feb 24, 2023 |
| Unknown       | Unknown                     | [efab6dedba](https://bsd-hardware.info/?probe=efab6dedba) | Feb 24, 2023 |
| Protectli     | VP2420                      | [ac2228fa2b](https://bsd-hardware.info/?probe=ac2228fa2b) | Feb 24, 2023 |
| Dell          | 0C27VV A02                  | [5899533edd](https://bsd-hardware.info/?probe=5899533edd) | Feb 23, 2023 |
| Fujitsu       | D3543-A2 S26361-D3543-A2... | [68165a639f](https://bsd-hardware.info/?probe=68165a639f) | Feb 22, 2023 |
| PC Engines    | APU2                        | [05966fb4dc](https://bsd-hardware.info/?probe=05966fb4dc) | Feb 22, 2023 |
| Protectli     | VP2420                      | [541c13b778](https://bsd-hardware.info/?probe=541c13b778) | Feb 22, 2023 |
| Dell          | 0C27VV A02                  | [a10df954b7](https://bsd-hardware.info/?probe=a10df954b7) | Feb 22, 2023 |
| Intel         | QHSW02                      | [6bec4024a8](https://bsd-hardware.info/?probe=6bec4024a8) | Feb 22, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [3f78b1a6c7](https://bsd-hardware.info/?probe=3f78b1a6c7) | Feb 20, 2023 |
| Protectli     | VP2420                      | [5d8285d184](https://bsd-hardware.info/?probe=5d8285d184) | Feb 19, 2023 |
| CncTion       | J4125-4L-I225               | [6d2c693305](https://bsd-hardware.info/?probe=6d2c693305) | Feb 19, 2023 |
| Yanling       | YL-CLU6L-V1                 | [8d1fa6606b](https://bsd-hardware.info/?probe=8d1fa6606b) | Feb 19, 2023 |
| Unknown       | Unknown                     | [1478bc453d](https://bsd-hardware.info/?probe=1478bc453d) | Feb 17, 2023 |
| Unknown       | Unknown                     | [ac4b0186ff](https://bsd-hardware.info/?probe=ac4b0186ff) | Feb 17, 2023 |
| ZOTAC         | Unknown                     | [0adf0ca671](https://bsd-hardware.info/?probe=0adf0ca671) | Feb 17, 2023 |
| ASUSTek       | N3050M-E                    | [7d6e696fb4](https://bsd-hardware.info/?probe=7d6e696fb4) | Feb 17, 2023 |
| Unknown       | Unknown                     | [71cc084a9c](https://bsd-hardware.info/?probe=71cc084a9c) | Feb 16, 2023 |
| PC Engines    | APU                         | [1162545537](https://bsd-hardware.info/?probe=1162545537) | Feb 15, 2023 |
| ASUSTek       | PRIME A320M-K               | [35aa7d7f04](https://bsd-hardware.info/?probe=35aa7d7f04) | Feb 15, 2023 |
| Supermicro    | X7SPA-HF                    | [6a91635684](https://bsd-hardware.info/?probe=6a91635684) | Feb 14, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a9d6421d3c](https://bsd-hardware.info/?probe=a9d6421d3c) | Feb 14, 2023 |
| Yanling       | YL-CLU6L-V1                 | [9c12ee263f](https://bsd-hardware.info/?probe=9c12ee263f) | Feb 14, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | [d69aba5432](https://bsd-hardware.info/?probe=d69aba5432) | Feb 14, 2023 |
| Unknown       | Unknown                     | [98819b1db5](https://bsd-hardware.info/?probe=98819b1db5) | Feb 13, 2023 |
| Unknown       | Unknown                     | [dbe1c51575](https://bsd-hardware.info/?probe=dbe1c51575) | Feb 12, 2023 |
| ASUSTek       | P8Z68-V                     | [74ebc950e2](https://bsd-hardware.info/?probe=74ebc950e2) | Feb 11, 2023 |
| Yanling       | YL-KBR6L Ver:1.00           | [516c778d65](https://bsd-hardware.info/?probe=516c778d65) | Feb 11, 2023 |
| Foxconn       | 2A8Ch                       | [2874f7a7fa](https://bsd-hardware.info/?probe=2874f7a7fa) | Feb 11, 2023 |
| Gigabyte      | Z490 VISION G               | [6f8ad1a8b9](https://bsd-hardware.info/?probe=6f8ad1a8b9) | Feb 11, 2023 |
| Techvision    | TVI7309X B0                 | [c4c07aec07](https://bsd-hardware.info/?probe=c4c07aec07) | Feb 11, 2023 |
| Unknown       | Unknown                     | [18362d0f11](https://bsd-hardware.info/?probe=18362d0f11) | Feb 10, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [12e4e26e40](https://bsd-hardware.info/?probe=12e4e26e40) | Feb 10, 2023 |
| Foxconn       | 2A8Ch                       | [84c0208f8d](https://bsd-hardware.info/?probe=84c0208f8d) | Feb 10, 2023 |
| ASUSTek       | P7P55D DELUXE               | [dd9685a909](https://bsd-hardware.info/?probe=dd9685a909) | Feb 09, 2023 |
| ASUSTek       | H110I-PLUS                  | [4347c8c716](https://bsd-hardware.info/?probe=4347c8c716) | Feb 09, 2023 |
| ASRock        | A520M-ITX/ac                | [e5b2e1bb9d](https://bsd-hardware.info/?probe=e5b2e1bb9d) | Feb 09, 2023 |
| ASRock        | A520M-ITX/ac                | [f66883c5c2](https://bsd-hardware.info/?probe=f66883c5c2) | Feb 09, 2023 |
| ASUSTek       | P10S-M Series               | [78975e45b7](https://bsd-hardware.info/?probe=78975e45b7) | Feb 09, 2023 |
| Unknown       | MANIFOLD 2-C                | [1a23b05eca](https://bsd-hardware.info/?probe=1a23b05eca) | Feb 07, 2023 |
| Unknown       | Unknown                     | [f4978c3575](https://bsd-hardware.info/?probe=f4978c3575) | Feb 07, 2023 |
| ASUSTek       | P10S-M Series               | [24b74b8ce3](https://bsd-hardware.info/?probe=24b74b8ce3) | Feb 07, 2023 |
| MW            | GMLK-2_5G4L                 | [39fa7db109](https://bsd-hardware.info/?probe=39fa7db109) | Feb 07, 2023 |
| Unknown       | MANIFOLD 2-C                | [923b6d85fd](https://bsd-hardware.info/?probe=923b6d85fd) | Feb 06, 2023 |
| PC Engines    | APU2                        | [e4e00e259c](https://bsd-hardware.info/?probe=e4e00e259c) | Feb 06, 2023 |
| ASUSTek       | P8Z77-M                     | [627bdfafb7](https://bsd-hardware.info/?probe=627bdfafb7) | Feb 06, 2023 |
| MSI           | B450M MORTAR MAX            | [ec37957aed](https://bsd-hardware.info/?probe=ec37957aed) | Feb 05, 2023 |
| Intel         | QHSW02                      | [16722b7429](https://bsd-hardware.info/?probe=16722b7429) | Feb 04, 2023 |
| Unknown       | Unknown                     | [8fdace282e](https://bsd-hardware.info/?probe=8fdace282e) | Feb 04, 2023 |
| ASUSTek       | P10S-M Series               | [c6fc0a639d](https://bsd-hardware.info/?probe=c6fc0a639d) | Feb 03, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [77c7c36f87](https://bsd-hardware.info/?probe=77c7c36f87) | Feb 03, 2023 |
| Unknown       | Unknown                     | [433e29e7bd](https://bsd-hardware.info/?probe=433e29e7bd) | Feb 01, 2023 |
| Supermicro    | X7SPA-HF                    | [2d410c6882](https://bsd-hardware.info/?probe=2d410c6882) | Feb 01, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [9fa25e53f1](https://bsd-hardware.info/?probe=9fa25e53f1) | Feb 01, 2023 |
| PC Engines    | apu4                        | [0d1561fea9](https://bsd-hardware.info/?probe=0d1561fea9) | Jan 31, 2023 |
| Intel         | Q3XXG4-P V1.0               | [418694e14d](https://bsd-hardware.info/?probe=418694e14d) | Jan 31, 2023 |
| Lanner        | FW-7543 B-GA                | [149345d14c](https://bsd-hardware.info/?probe=149345d14c) | Jan 30, 2023 |
| HP            | 1825                        | [717279c19f](https://bsd-hardware.info/?probe=717279c19f) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4c25e80924](https://bsd-hardware.info/?probe=4c25e80924) | Jan 29, 2023 |
| Shenzhen M... | F4BHD                       | [b2540f3beb](https://bsd-hardware.info/?probe=b2540f3beb) | Jan 29, 2023 |
| HP            | 21B4 A01                    | [8df824afd4](https://bsd-hardware.info/?probe=8df824afd4) | Jan 28, 2023 |
| Gigabyte      | B550 AORUS PRO              | [8fd7f80256](https://bsd-hardware.info/?probe=8fd7f80256) | Jan 28, 2023 |
| ASUSTek       | M4A89TD PRO USB3            | [1328d01296](https://bsd-hardware.info/?probe=1328d01296) | Jan 28, 2023 |
| Techvision    | TVI7309X B0                 | [937a255571](https://bsd-hardware.info/?probe=937a255571) | Jan 28, 2023 |
| CncTion       | N5105-4L B0                 | [a7fe868f42](https://bsd-hardware.info/?probe=a7fe868f42) | Jan 27, 2023 |
| Unknown       | Unknown                     | [d3750005c2](https://bsd-hardware.info/?probe=d3750005c2) | Jan 27, 2023 |
| ASUSTek       | PRIME X570-P                | [232a81d2ed](https://bsd-hardware.info/?probe=232a81d2ed) | Jan 27, 2023 |
| Gigabyte      | B760I AORUS PRO DDR4        | [4ebeac2699](https://bsd-hardware.info/?probe=4ebeac2699) | Jan 26, 2023 |
| PC Engines    | APU2                        | [436e596f40](https://bsd-hardware.info/?probe=436e596f40) | Jan 26, 2023 |
| ASUSTek       | PRIME A320M-K               | [cdad2f0001](https://bsd-hardware.info/?probe=cdad2f0001) | Jan 23, 2023 |
| AWOW          | AK50                        | [8c983f91e4](https://bsd-hardware.info/?probe=8c983f91e4) | Jan 22, 2023 |
| PC Engines    | APU2                        | [658569ae16](https://bsd-hardware.info/?probe=658569ae16) | Jan 22, 2023 |
| HP            | 1825                        | [2705218636](https://bsd-hardware.info/?probe=2705218636) | Jan 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [59c83cb9ee](https://bsd-hardware.info/?probe=59c83cb9ee) | Jan 21, 2023 |
| Fujitsu       | D3243-S1 S26361-D3243-S1    | [d69c3cae4c](https://bsd-hardware.info/?probe=d69c3cae4c) | Jan 21, 2023 |
| ASRock        | A520M-ITX/ac                | [e6873fe42f](https://bsd-hardware.info/?probe=e6873fe42f) | Jan 21, 2023 |
| Techvision    | TVI7309X B0                 | [495563926c](https://bsd-hardware.info/?probe=495563926c) | Jan 21, 2023 |
| ASRock        | A520M-ITX/ac                | [f862df1689](https://bsd-hardware.info/?probe=f862df1689) | Jan 20, 2023 |
| Techvision    | TVI7309X B0                 | [d4018ae0f3](https://bsd-hardware.info/?probe=d4018ae0f3) | Jan 20, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [4bcc8752f4](https://bsd-hardware.info/?probe=4bcc8752f4) | Jan 20, 2023 |
| ShenZhen M... | MW-NANO-APL-4L              | [48206a7d4a](https://bsd-hardware.info/?probe=48206a7d4a) | Jan 19, 2023 |
| Unknown       | Unknown                     | [35e269ef1c](https://bsd-hardware.info/?probe=35e269ef1c) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [b528c0bbe3](https://bsd-hardware.info/?probe=b528c0bbe3) | Jan 18, 2023 |
| BESSTAR Te... | TH50                        | [b9de543167](https://bsd-hardware.info/?probe=b9de543167) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | [11948a0ab1](https://bsd-hardware.info/?probe=11948a0ab1) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [f7de27b0ca](https://bsd-hardware.info/?probe=f7de27b0ca) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [9eee9cc526](https://bsd-hardware.info/?probe=9eee9cc526) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | [46178567ff](https://bsd-hardware.info/?probe=46178567ff) | Jan 18, 2023 |
| Wortmann      | terra MiniPC                | [be22193265](https://bsd-hardware.info/?probe=be22193265) | Jan 17, 2023 |
| MSI           | MS-9897                     | [8aa91d17fa](https://bsd-hardware.info/?probe=8aa91d17fa) | Jan 17, 2023 |
| MSI           | MS-9897                     | [0ccc361bd9](https://bsd-hardware.info/?probe=0ccc361bd9) | Jan 17, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [1ef7026e21](https://bsd-hardware.info/?probe=1ef7026e21) | Jan 15, 2023 |
| Techvision    | TVI7309X B0                 | [8aebf3b22a](https://bsd-hardware.info/?probe=8aebf3b22a) | Jan 15, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [17d73c4d40](https://bsd-hardware.info/?probe=17d73c4d40) | Jan 14, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [ad7329411a](https://bsd-hardware.info/?probe=ad7329411a) | Jan 14, 2023 |
| Unknown       | Unknown                     | [fba3e00878](https://bsd-hardware.info/?probe=fba3e00878) | Jan 13, 2023 |
| HP            | 82A1                        | [567894a0bb](https://bsd-hardware.info/?probe=567894a0bb) | Jan 12, 2023 |
| PC Engines    | APU3                        | [b080710198](https://bsd-hardware.info/?probe=b080710198) | Jan 12, 2023 |
| ASRockRack    | X470D4U2/1N1                | [07f15d0014](https://bsd-hardware.info/?probe=07f15d0014) | Jan 11, 2023 |
| CncTion       | J4125-4L-I225               | [56a5c0de6e](https://bsd-hardware.info/?probe=56a5c0de6e) | Jan 11, 2023 |
| PC Engines    | APU2                        | [1e65573dfa](https://bsd-hardware.info/?probe=1e65573dfa) | Jan 10, 2023 |
| Unknown       | Unknown                     | [e870cfc473](https://bsd-hardware.info/?probe=e870cfc473) | Jan 10, 2023 |
| MW            | GMLK-2_5G4L                 | [55bd6297fa](https://bsd-hardware.info/?probe=55bd6297fa) | Jan 10, 2023 |
| MSI           | X299 PRO                    | [a1f37f69d9](https://bsd-hardware.info/?probe=a1f37f69d9) | Jan 08, 2023 |
| Dell          | 0YNVJG A01                  | [8bb9472e6b](https://bsd-hardware.info/?probe=8bb9472e6b) | Jan 08, 2023 |
| Unknown       | Unknown                     | [7b5333020a](https://bsd-hardware.info/?probe=7b5333020a) | Jan 08, 2023 |
| Unknown       | Unknown                     | [1e3ebde983](https://bsd-hardware.info/?probe=1e3ebde983) | Jan 07, 2023 |
| ASUSTek       | F2A85-M                     | [e25da8b10a](https://bsd-hardware.info/?probe=e25da8b10a) | Jan 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | [fa12ea67eb](https://bsd-hardware.info/?probe=fa12ea67eb) | Jan 06, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [92c2e73bd4](https://bsd-hardware.info/?probe=92c2e73bd4) | Jan 06, 2023 |
| Unknown       | Unknown                     | [cc8588d977](https://bsd-hardware.info/?probe=cc8588d977) | Jan 05, 2023 |
| MW            | GMLK-2_5G4L                 | [39149acdbd](https://bsd-hardware.info/?probe=39149acdbd) | Jan 04, 2023 |
| Unknown       | J3160-4L                    | [849af12174](https://bsd-hardware.info/?probe=849af12174) | Jan 02, 2023 |
| CncTion       | N5105-4L B0                 | [70b1ca485d](https://bsd-hardware.info/?probe=70b1ca485d) | Jan 02, 2023 |
| ASRock        | E350M1                      | [6a7e5c8d0c](https://bsd-hardware.info/?probe=6a7e5c8d0c) | Jan 01, 2023 |
| HP            | 1825                        | [f7e94decd0](https://bsd-hardware.info/?probe=f7e94decd0) | Dec 31, 2022 |
| HP            | 1825                        | [afc1259508](https://bsd-hardware.info/?probe=afc1259508) | Dec 31, 2022 |
| CncTion       | N5105-4L B0                 | [cd3e4f7122](https://bsd-hardware.info/?probe=cd3e4f7122) | Dec 30, 2022 |
| Protectli     | FW4B                        | [406fe72c22](https://bsd-hardware.info/?probe=406fe72c22) | Dec 30, 2022 |
| PC Engines    | APU2                        | [7aaf2d91ba](https://bsd-hardware.info/?probe=7aaf2d91ba) | Dec 29, 2022 |
| Lanner        | FW-7543 B-GA                | [6c145361a3](https://bsd-hardware.info/?probe=6c145361a3) | Dec 29, 2022 |
| Unknown       | Unknown                     | [5b8ad02694](https://bsd-hardware.info/?probe=5b8ad02694) | Dec 28, 2022 |
| Unknown       | Unknown                     | [c3b95220d7](https://bsd-hardware.info/?probe=c3b95220d7) | Dec 28, 2022 |
| ASUSTek       | H97-PLUS                    | [f2a248dcfe](https://bsd-hardware.info/?probe=f2a248dcfe) | Dec 26, 2022 |
| HP            | 8062                        | [f4d3eb024d](https://bsd-hardware.info/?probe=f4d3eb024d) | Dec 25, 2022 |
| Biostar       | A10N-8800E                  | [d3d1107f77](https://bsd-hardware.info/?probe=d3d1107f77) | Dec 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | [58b47341c9](https://bsd-hardware.info/?probe=58b47341c9) | Dec 23, 2022 |
| ASRock        | B75M R2.0                   | [3a8d5c61b6](https://bsd-hardware.info/?probe=3a8d5c61b6) | Dec 23, 2022 |
| Unknown       | QD-WHLU01                   | [a0fb185069](https://bsd-hardware.info/?probe=a0fb185069) | Dec 23, 2022 |
| Unknown       | MANIFOLD 2-C                | [bc2c536004](https://bsd-hardware.info/?probe=bc2c536004) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | [daaad6a386](https://bsd-hardware.info/?probe=daaad6a386) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | [67bc182d1d](https://bsd-hardware.info/?probe=67bc182d1d) | Dec 23, 2022 |
| CncTion       | N5105-4L B0                 | [78bcccda01](https://bsd-hardware.info/?probe=78bcccda01) | Dec 22, 2022 |
| ASRock        | A75M-HVS                    | [01d8e43ee1](https://bsd-hardware.info/?probe=01d8e43ee1) | Dec 22, 2022 |
| AAEON         | FWS-2251 V1.0               | [a4ff0a7ec5](https://bsd-hardware.info/?probe=a4ff0a7ec5) | Dec 22, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [2ac107df0f](https://bsd-hardware.info/?probe=2ac107df0f) | Dec 22, 2022 |
| Dell          | 0WR7PY A02                  | [0c3fea5eb0](https://bsd-hardware.info/?probe=0c3fea5eb0) | Dec 22, 2022 |
| ASRock        | 4X4-4000 Series             | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [2ea413db31](https://bsd-hardware.info/?probe=2ea413db31) | Dec 20, 2022 |
| HP            | ProLiant MicroServer Gen... | [8de4ff8626](https://bsd-hardware.info/?probe=8de4ff8626) | Dec 20, 2022 |
| Unknown       | Unknown                     | [5d37a0669c](https://bsd-hardware.info/?probe=5d37a0669c) | Dec 19, 2022 |
| Dell          | 0WR7PY A02                  | [67baacfc7d](https://bsd-hardware.info/?probe=67baacfc7d) | Dec 19, 2022 |
| ASUSTek       | H97-PLUS                    | [c9de65beeb](https://bsd-hardware.info/?probe=c9de65beeb) | Dec 19, 2022 |
| PC Engines    | APU2                        | [5de84cb508](https://bsd-hardware.info/?probe=5de84cb508) | Dec 19, 2022 |
| Gigabyte      | J3455N-D3H                  | [fc7928dfe9](https://bsd-hardware.info/?probe=fc7928dfe9) | Dec 18, 2022 |
| MSI           | X299 PRO                    | [beec8001a1](https://bsd-hardware.info/?probe=beec8001a1) | Dec 17, 2022 |
| Intel         | CRESCENTBAY                 | [7981529337](https://bsd-hardware.info/?probe=7981529337) | Dec 17, 2022 |
| ASRock        | Q2900M                      | [42a53e5201](https://bsd-hardware.info/?probe=42a53e5201) | Dec 16, 2022 |
| ASRock        | A75M-HVS                    | [fa8c102cfd](https://bsd-hardware.info/?probe=fa8c102cfd) | Dec 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | [3faaaa8209](https://bsd-hardware.info/?probe=3faaaa8209) | Dec 16, 2022 |
| Unknown       | Unknown                     | [01e26ec145](https://bsd-hardware.info/?probe=01e26ec145) | Dec 15, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | [40911b66e2](https://bsd-hardware.info/?probe=40911b66e2) | Dec 15, 2022 |
| Unknown       | Unknown                     | [e3508ce360](https://bsd-hardware.info/?probe=e3508ce360) | Dec 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [35ecaf0406](https://bsd-hardware.info/?probe=35ecaf0406) | Dec 15, 2022 |
| Unknown       | Unknown                     | [210418cc84](https://bsd-hardware.info/?probe=210418cc84) | Dec 15, 2022 |
| MW            | GMLK-2_5G4L                 | [cb16bb9431](https://bsd-hardware.info/?probe=cb16bb9431) | Dec 14, 2022 |
| NF541         | 1.0                         | [b0644bada6](https://bsd-hardware.info/?probe=b0644bada6) | Dec 14, 2022 |
| Unknown       | Unknown                     | [ec6827e543](https://bsd-hardware.info/?probe=ec6827e543) | Dec 13, 2022 |
| Techvision    | TVI7309X B0                 | [af9df0d2c9](https://bsd-hardware.info/?probe=af9df0d2c9) | Dec 13, 2022 |
| Unknown       | Unknown                     | [9ee8d1082b](https://bsd-hardware.info/?probe=9ee8d1082b) | Dec 12, 2022 |
| Shuttle       | DH370                       | [1b938aa1a4](https://bsd-hardware.info/?probe=1b938aa1a4) | Dec 12, 2022 |
| Unknown       | MANIFOLD 2-C                | [ba191bd994](https://bsd-hardware.info/?probe=ba191bd994) | Dec 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [3124aaaf95](https://bsd-hardware.info/?probe=3124aaaf95) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [b1bd01549a](https://bsd-hardware.info/?probe=b1bd01549a) | Dec 11, 2022 |
| Unknown       | Unknown                     | [def65f518e](https://bsd-hardware.info/?probe=def65f518e) | Dec 10, 2022 |
| MSI           | B450M MORTAR MAX            | [d8d6af9e56](https://bsd-hardware.info/?probe=d8d6af9e56) | Dec 10, 2022 |
| Protectli     | FW4B Ver                    | [33395e819a](https://bsd-hardware.info/?probe=33395e819a) | Dec 10, 2022 |
| Hardkernel    | ODROID-H3                   | [cd6aa62212](https://bsd-hardware.info/?probe=cd6aa62212) | Dec 09, 2022 |
| Unknown       | Unknown                     | [493df1f529](https://bsd-hardware.info/?probe=493df1f529) | Dec 09, 2022 |
| PC Engines    | apu4                        | [3e3ab7f196](https://bsd-hardware.info/?probe=3e3ab7f196) | Dec 09, 2022 |
| MW            | GMLK-2_5G4L                 | [84f8198c18](https://bsd-hardware.info/?probe=84f8198c18) | Dec 08, 2022 |
| Dell          | 0G261D A00                  | [24b9490c77](https://bsd-hardware.info/?probe=24b9490c77) | Dec 06, 2022 |
| Protectli     | FW4B Ver                    | [eaa3b9783e](https://bsd-hardware.info/?probe=eaa3b9783e) | Dec 05, 2022 |
| PC Engines    | apu4                        | [72061eb254](https://bsd-hardware.info/?probe=72061eb254) | Dec 05, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [aa9482884f](https://bsd-hardware.info/?probe=aa9482884f) | Dec 05, 2022 |
| Shuttle       | FS77U                       | [4172b79cfc](https://bsd-hardware.info/?probe=4172b79cfc) | Dec 04, 2022 |
| Unknown       | Unknown                     | [af4f0984ae](https://bsd-hardware.info/?probe=af4f0984ae) | Dec 04, 2022 |
| ASUSTek       | E35M1-I DELUXE              | [1a183385c7](https://bsd-hardware.info/?probe=1a183385c7) | Dec 04, 2022 |
| Unknown       | Unknown                     | [d9113585f0](https://bsd-hardware.info/?probe=d9113585f0) | Dec 04, 2022 |
| Intel         | D33217CK G76541-300         | [545a39b1e4](https://bsd-hardware.info/?probe=545a39b1e4) | Dec 02, 2022 |
| Intel         | D33217CK G76541-300         | [bbdd9a1b98](https://bsd-hardware.info/?probe=bbdd9a1b98) | Nov 30, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [ae55a799e8](https://bsd-hardware.info/?probe=ae55a799e8) | Nov 28, 2022 |
| PC Engines    | apu6                        | [13dcbe5748](https://bsd-hardware.info/?probe=13dcbe5748) | Nov 27, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| OPNsense 21.7.7  | 43       | 2.28%   |
| OPNsense 21.1    | 42       | 2.23%   |
| OPNsense 22.7.10 | 40       | 2.13%   |
| OPNsense 21.7.1  | 38       | 2.02%   |
| OPNsense 21.1.5  | 38       | 2.02%   |
| OPNsense 22.1    | 36       | 1.91%   |
| OPNsense 24.1.6  | 35       | 1.86%   |
| OPNsense 23.1.11 | 35       | 1.86%   |
| OPNsense 20.7.8  | 34       | 1.81%   |
| OPNsense 21.7.3  | 33       | 1.75%   |
| OPNsense 21.1.3  | 32       | 1.7%    |
| OPNsense 22.7.9  | 31       | 1.65%   |
| OPNsense 21.1.4  | 31       | 1.65%   |
| OPNsense 23.1.5  | 30       | 1.59%   |
| OPNsense 22.1.8  | 30       | 1.59%   |
| OPNsense 21.7.6  | 30       | 1.59%   |
| OPNsense 22.7.4  | 29       | 1.54%   |
| OPNsense 21.1.2  | 29       | 1.54%   |
| OPNsense 21.1.1  | 29       | 1.54%   |
| OPNsense 23.7.12 | 28       | 1.49%   |
| OPNsense 23.7.10 | 28       | 1.49%   |
| OPNsense 23.1.1  | 28       | 1.49%   |
| OPNsense 22.7.6  | 28       | 1.49%   |
| OPNsense 23.7.9  | 27       | 1.43%   |
| OPNsense 24.1.4  | 26       | 1.38%   |
| OPNsense 23.1    | 26       | 1.38%   |
| OPNsense 24.1.1  | 24       | 1.28%   |
| OPNsense 23.7.7  | 24       | 1.28%   |
| OPNsense 23.1.7  | 24       | 1.28%   |
| OPNsense 22.1.6  | 24       | 1.28%   |
| OPNsense 21.7.5  | 24       | 1.28%   |
| OPNsense 23.7.1  | 23       | 1.22%   |
| OPNsense 23.1.9  | 23       | 1.22%   |
| OPNsense 24.1.3  | 22       | 1.17%   |
| OPNsense 23.7.8  | 22       | 1.17%   |
| OPNsense 22.1.10 | 22       | 1.17%   |
| OPNsense 24.1    | 21       | 1.12%   |
| OPNsense 23.7.3  | 19       | 1.01%   |
| OPNsense 23.7.5  | 18       | 0.96%   |
| OPNsense 23.7.11 | 18       | 0.96%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 1130     | 81.18%  |
| FreeBSD     | 123      | 8.84%   |
| helloSystem | 59       | 4.24%   |
| OpenBSD     | 37       | 2.66%   |
| GhostBSD    | 16       | 1.15%   |
| NomadBSD    | 8        | 0.57%   |
| NetBSD      | 6        | 0.43%   |
| TrueNAS     | 4        | 0.29%   |
| pfSense     | 2        | 0.14%   |
| MyBee       | 2        | 0.14%   |
| PC-BSD      | 1        | 0.07%   |
| HardenedBSD | 1        | 0.07%   |
| FreeNAS     | 1        | 0.07%   |
| DragonFly   | 1        | 0.07%   |
| ClonOS      | 1        | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 1370     | 99.13%  |
| arm64   | 4        | 0.29%   |
| arm     | 4        | 0.29%   |
| i386    | 2        | 0.14%   |
| sparc64 | 1        | 0.07%   |
| macppc  | 1        | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 1221     | 87.53%  |
| helloDesktop  | 71       | 5.09%   |
| MATE          | 20       | 1.43%   |
| KDE5          | 20       | 1.43%   |
| XFCE          | 14       | 1%      |
| fvwm          | 12       | 0.86%   |
| TWM           | 8        | 0.57%   |
| AwesomeWM     | 7        | 0.5%    |
| GNOME         | 6        | 0.43%   |
| Openbox       | 4        | 0.29%   |
| i3            | 3        | 0.22%   |
| LXQt          | 1        | 0.07%   |
| LXDE          | 1        | 0.07%   |
| ICEWM         | 1        | 0.07%   |
| GNUstep       | 1        | 0.07%   |
| Fluxbox       | 1        | 0.07%   |
| filer         | 1        | 0.07%   |
| Enlightenment | 1        | 0.07%   |
| Compton       | 1        | 0.07%   |
| Cinnamon      | 1        | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 1230     | 88.87%  |
| X11     | 153      | 11.05%  |
| Tty     | 1        | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 1262     | 90.6%   |
| SLiM    | 74       | 5.31%   |
| SDDM    | 19       | 1.36%   |
| LightDM | 19       | 1.36%   |
| XDM     | 11       | 0.79%   |
| GDM     | 6        | 0.43%   |
| Ly      | 2        | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Desktops | Percent |
|-----------------|----------|---------|
| Unknown         | 1193     | 85.21%  |
| C               | 79       | 5.64%   |
| en_US           | 66       | 4.71%   |
| de_DE           | 46       | 3.29%   |
| fr_FR           | 4        | 0.29%   |
| en              | 3        | 0.21%   |
| en_GB           | 2        | 0.14%   |
| ru_RU           | 1        | 0.07%   |
| ISO8859-15      | 1        | 0.07%   |
| fr              | 1        | 0.07%   |
| en_DE           | 1        | 0.07%   |
| de_DE.ISO8859-1 | 1        | 0.07%   |
| de.DE           | 1        | 0.07%   |
| de              | 1        | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 1215     | 87.47%  |
| BIOS | 174      | 12.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 872      | 61.5%   |
| Zfs     | 489      | 34.49%  |
| Ffs     | 37       | 2.61%   |
| Cd9660  | 19       | 1.34%   |
| Hammer2 | 1        | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1282     | 92.3%   |
| MBR     | 83       | 5.98%   |
| Unknown | 23       | 1.66%   |
| BSD     | 1        | 0.07%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 269      | 19.46%  |
| PC Engines                 | 145      | 10.49%  |
| Fujitsu                    | 118      | 8.54%   |
| ASUSTek Computer           | 82       | 5.93%   |
| ASRock                     | 78       | 5.64%   |
| Hewlett-Packard            | 70       | 5.07%   |
| Gigabyte Technology        | 66       | 4.78%   |
| Intel                      | 61       | 4.41%   |
| Dell                       | 47       | 3.4%    |
| MSI                        | 46       | 3.33%   |
| Protectli                  | 37       | 2.68%   |
| Supermicro                 | 34       | 2.46%   |
| Techvision                 | 25       | 1.81%   |
| CncTion                    | 24       | 1.74%   |
| BESSTAR Tech               | 19       | 1.37%   |
| Shuttle                    | 18       | 1.3%    |
| Lenovo                     | 18       | 1.3%    |
| Hardkernel                 | 14       | 1.01%   |
| MW                         | 13       | 0.94%   |
| Thomas-Krenn.AG            | 10       | 0.72%   |
| Yanling                    | 9        | 0.65%   |
| AAEON                      | 9        | 0.65%   |
| NF541                      | 8        | 0.58%   |
| IceWhale Technology        | 8        | 0.58%   |
| Deciso                     | 8        | 0.58%   |
| CheckPoint                 | 8        | 0.58%   |
| Biostar                    | 8        | 0.58%   |
| ASRockRack                 | 8        | 0.58%   |
| Lanner                     | 6        | 0.43%   |
| CWWK                       | 6        | 0.43%   |
| Foxconn                    | 5        | 0.36%   |
| Beckhoff Automation        | 5        | 0.36%   |
| Advantech                  | 5        | 0.36%   |
| Acer                       | 5        | 0.36%   |
| ZOTAC                      | 4        | 0.29%   |
| ShenZhen MinWin Technology | 4        | 0.29%   |
| NU591                      | 4        | 0.29%   |
| NEXCOM                     | 4        | 0.29%   |
| Lex                        | 4        | 0.29%   |
| OEM                        | 3        | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 273      | 19.75%  |
| PC Engines APU2                   | 70       | 5.07%   |
| Fujitsu FUTRO S920                | 56       | 4.05%   |
| PC Engines apu4                   | 49       | 3.55%   |
| Techvision TVI7309X               | 25       | 1.81%   |
| Intel Q3XXG4-P V1.0               | 18       | 1.3%    |
| Protectli FW6                     | 14       | 1.01%   |
| MW GMLK-2_5G4L                    | 13       | 0.94%   |
| Hardkernel ODROID-H2              | 13       | 0.94%   |
| Protectli FW4B                    | 11       | 0.8%    |
| PC Engines APU3                   | 11       | 0.8%    |
| CncTion N5105-4L                  | 11       | 0.8%    |
| PC Engines APU                    | 10       | 0.72%   |
| Fujitsu FUTRO S930                | 10       | 0.72%   |
| HP ProLiant MicroServer Gen8      | 9        | 0.65%   |
| BESSTAR Tech X35G                 | 9        | 0.65%   |
| HP t620 PLUS Quad Core TC         | 8        | 0.58%   |
| NF541 1.0                         | 7        | 0.51%   |
| ASUS All Series                   | 7        | 0.51%   |
| MSI MS-7B89                       | 6        | 0.43%   |
| IceWhale ZimaBoard 832 ZMB        | 6        | 0.43%   |
| Thomas-Krenn.AG LES network+      | 5        | 0.36%   |
| Protectli VP2420                  | 5        | 0.36%   |
| Lanner GP-7543                    | 5        | 0.36%   |
| Intel DENLOW_WS                   | 5        | 0.36%   |
| Fujitsu FUTRO S940                | 5        | 0.36%   |
| CncTion J4125-4L-I225             | 5        | 0.36%   |
| AAEON FWS-2251                    | 5        | 0.36%   |
| Yanling LES network 6L            | 4        | 0.29%   |
| Thomas-Krenn.AG LES network 6L    | 4        | 0.29%   |
| Supermicro X7SPA-HF               | 4        | 0.29%   |
| Protectli VP2410                  | 4        | 0.29%   |
| PC Engines apu1                   | 4        | 0.29%   |
| NU591 LES v3                      | 4        | 0.29%   |
| NEXCOM ASG                        | 4        | 0.29%   |
| MSI MS-7816                       | 4        | 0.29%   |
| Lex Pineview-D                    | 4        | 0.29%   |
| Intel Jasper Lake Client Platform | 4        | 0.29%   |
| HP t620 Quad Core TC              | 4        | 0.29%   |
| HP Compaq Elite 8300 SFF          | 4        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Unknown               | 273      | 19.75%  |
| Fujitsu FUTRO         | 82       | 5.93%   |
| PC Engines APU2       | 70       | 5.07%   |
| PC Engines apu4       | 49       | 3.55%   |
| Dell OptiPlex         | 39       | 2.82%   |
| Techvision TVI7309X   | 25       | 1.81%   |
| Intel Q3XXG4-P        | 18       | 1.3%    |
| Fujitsu ESPRIMO       | 17       | 1.23%   |
| Protectli FW6         | 14       | 1.01%   |
| Lenovo ThinkCentre    | 14       | 1.01%   |
| HP ProLiant           | 14       | 1.01%   |
| MW GMLK-2             | 13       | 0.94%   |
| HP t620               | 13       | 0.94%   |
| HP ProDesk            | 13       | 0.94%   |
| HARDKERNEL ODROID-H2  | 13       | 0.94%   |
| HP Compaq             | 12       | 0.87%   |
| Protectli FW4B        | 11       | 0.8%    |
| PC Engines APU3       | 11       | 0.8%    |
| CncTion N5105-4L      | 11       | 0.8%    |
| ASUS PRIME            | 11       | 0.8%    |
| PC Engines APU        | 10       | 0.72%   |
| ASUS TUF              | 10       | 0.72%   |
| Thomas-Krenn.AG LES   | 9        | 0.65%   |
| BESSTAR Tech X35G     | 9        | 0.65%   |
| IceWhale ZimaBoard    | 8        | 0.58%   |
| HP EliteDesk          | 8        | 0.58%   |
| Deciso Netboard       | 8        | 0.58%   |
| NF541 1.0             | 7        | 0.51%   |
| ASUS All              | 7        | 0.51%   |
| Yanling LES           | 6        | 0.43%   |
| MSI MS-7B89           | 6        | 0.43%   |
| Protectli VP2420      | 5        | 0.36%   |
| Lanner GP-7543        | 5        | 0.36%   |
| Intel DENLOW          | 5        | 0.36%   |
| Gigabyte X570         | 5        | 0.36%   |
| Gigabyte B450M        | 5        | 0.36%   |
| CncTion J4125-4L-I225 | 5        | 0.36%   |
| ASUS ROG              | 5        | 0.36%   |
| ASUS PRO              | 5        | 0.36%   |
| AAEON FWS-2251        | 5        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2016    | 173      | 12.52%  |
| 2018    | 157      | 11.36%  |
| 2022    | 156      | 11.29%  |
| 2021    | 135      | 9.77%   |
| 2020    | 118      | 8.54%   |
| 2014    | 115      | 8.32%   |
| 2019    | 100      | 7.24%   |
| 2017    | 80       | 5.79%   |
| 2023    | 76       | 5.5%    |
| 2013    | 59       | 4.27%   |
| 2012    | 55       | 3.98%   |
| 2011    | 47       | 3.4%    |
| 2010    | 29       | 2.1%    |
| 2015    | 24       | 1.74%   |
| 2009    | 21       | 1.52%   |
| 2008    | 14       | 1.01%   |
| Unknown | 12       | 0.87%   |
| 2007    | 7        | 0.51%   |
| 2024    | 2        | 0.14%   |
| 2006    | 2        | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1382     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1220     | 88.28%  |
| Yes  | 162      | 11.72%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 510      | 36.2%   |
| 4.01-8.0        | 346      | 24.56%  |
| 16.01-24.0      | 310      | 22%     |
| 32.01-64.0      | 119      | 8.45%   |
| 2.01-3.0        | 48       | 3.41%   |
| 64.01-256.0     | 45       | 3.19%   |
| 24.01-32.0      | 9        | 0.64%   |
| 3.01-4.0        | 7        | 0.5%    |
| 1.01-2.0        | 5        | 0.35%   |
| 0.01-0.5        | 5        | 0.35%   |
| 0.51-1.0        | 3        | 0.21%   |
| More than 256.0 | 2        | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 718      | 50.21%  |
| 0.51-1.0    | 500      | 34.97%  |
| 1.01-2.0    | 129      | 9.02%   |
| 2.01-3.0    | 30       | 2.1%    |
| 3.01-4.0    | 15       | 1.05%   |
| 4.01-8.0    | 13       | 0.91%   |
| 0           | 7        | 0.49%   |
| Unknown     | 6        | 0.42%   |
| 16.01-24.0  | 4        | 0.28%   |
| 8.01-16.0   | 3        | 0.21%   |
| 24.01-32.0  | 2        | 0.14%   |
| 64.01-256.0 | 2        | 0.14%   |
| 32.01-64.0  | 1        | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1070     | 75.3%   |
| 2      | 128      | 9.01%   |
| 0      | 119      | 8.37%   |
| 3      | 45       | 3.17%   |
| 4      | 29       | 2.04%   |
| 5      | 15       | 1.06%   |
| 6      | 7        | 0.49%   |
| 7      | 5        | 0.35%   |
| 8      | 2        | 0.14%   |
| 9      | 1        | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1230     | 88.49%  |
| Yes       | 160      | 11.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1371     | 99.2%   |
| No        | 11       | 0.8%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1137     | 81.45%  |
| Yes       | 259      | 18.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1242     | 89.42%  |
| Yes       | 147      | 10.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Germany | 1382     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Berlin            | 125      | 7.93%   |
| Munich            | 64       | 4.06%   |
| Hamburg           | 52       | 3.3%    |
| Cologne           | 42       | 2.66%   |
| Frankfurt am Main | 39       | 2.47%   |
| Stuttgart         | 23       | 1.46%   |
| Ludwigsburg       | 20       | 1.27%   |
| Karlsruhe         | 19       | 1.2%    |
| Nuremberg         | 16       | 1.01%   |
| Bonn              | 16       | 1.01%   |
| Hanover           | 15       | 0.95%   |
| Dortmund          | 13       | 0.82%   |
| Falkenstein       | 12       | 0.76%   |
| Wiesbaden         | 11       | 0.7%    |
| Mannheim          | 11       | 0.7%    |
| Leipzig           | 11       | 0.7%    |
| Dresden           | 11       | 0.7%    |
| Wuppertal         | 10       | 0.63%   |
| Bochum            | 10       | 0.63%   |
| Düsseldorf       | 9        | 0.57%   |
| Darmstadt         | 9        | 0.57%   |
| Braunschweig      | 9        | 0.57%   |
| Ulm               | 8        | 0.51%   |
| Reutlingen        | 8        | 0.51%   |
| Jena              | 8        | 0.51%   |
| Heidelberg        | 8        | 0.51%   |
| Duisburg          | 8        | 0.51%   |
| Bremen            | 8        | 0.51%   |
| Bielefeld         | 8        | 0.51%   |
| Mainz             | 7        | 0.44%   |
| Magdeburg         | 7        | 0.44%   |
| Kiel              | 7        | 0.44%   |
| Kassel            | 7        | 0.44%   |
| Heilbronn         | 7        | 0.44%   |
| Chemnitz          | 7        | 0.44%   |
| Augsburg          | 7        | 0.44%   |
| Solden            | 6        | 0.38%   |
| Paderborn         | 6        | 0.38%   |
| Münster          | 6        | 0.38%   |
| Wolfsburg         | 5        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 257      | 431    | 16.82%  |
| Transcend           | 138      | 197    | 9.03%   |
| WDC                 | 122      | 211    | 7.98%   |
| Kingston            | 122      | 203    | 7.98%   |
| Crucial             | 82       | 128    | 5.37%   |
| SanDisk             | 79       | 119    | 5.17%   |
| Seagate             | 68       | 110    | 4.45%   |
| China               | 67       | 79     | 4.38%   |
| Intel               | 60       | 95     | 3.93%   |
| Toshiba             | 50       | 86     | 3.27%   |
| Phison              | 40       | 60     | 2.62%   |
| Intenso             | 36       | 59     | 2.36%   |
| Innodisk            | 30       | 36     | 1.96%   |
| Hoodisk             | 30       | 56     | 1.96%   |
| Micron Technology   | 22       | 40     | 1.44%   |
| Hitachi             | 22       | 45     | 1.44%   |
| HGST                | 21       | 39     | 1.37%   |
| FORESEE             | 17       | 22     | 1.11%   |
| Patriot             | 15       | 21     | 0.98%   |
| A-DATA Technology   | 14       | 17     | 0.92%   |
| Protectli           | 13       | 18     | 0.85%   |
| NVMe                | 11       | 19     | 0.72%   |
| OCZ                 | 10       | 14     | 0.65%   |
| ATP                 | 9        | 10     | 0.59%   |
| SPCC                | 8        | 12     | 0.52%   |
| SK hynix            | 8        | 9      | 0.52%   |
| Apacer              | 8        | 17     | 0.52%   |
| Corsair             | 7        | 12     | 0.46%   |
| Verbatim            | 6        | 7      | 0.39%   |
| TCSUNBOW            | 6        | 7      | 0.39%   |
| ShiJi               | 6        | 7      | 0.39%   |
| LITEONIT            | 6        | 9      | 0.39%   |
| KIOXIA              | 6        | 7      | 0.39%   |
| Dogfish             | 6        | 7      | 0.39%   |
| PNY                 | 5        | 6      | 0.33%   |
| Lexar               | 5        | 5      | 0.33%   |
| KIOXIA-EXCERIA      | 5        | 11     | 0.33%   |
| KingSpec            | 5        | 6      | 0.33%   |
| Kimtigo             | 5        | 7      | 0.33%   |
| Gigabyte Technology | 5        | 6      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Transcend TS128GMSA230S 128GB   | 32       | 1.99%   |
| Phison SATA SSD 16GB            | 31       | 1.93%   |
| China SATA SSD 16GB             | 28       | 1.74%   |
| Transcend TS64GMSA230S 64GB     | 17       | 1.06%   |
| Samsung SSD 850 EVO 250GB       | 17       | 1.06%   |
| Samsung SSD 860 EVO 500GB       | 15       | 0.93%   |
| Crucial CT240BX500SSD1 240GB    | 14       | 0.87%   |
| Transcend TS256GMSA230S 256GB   | 13       | 0.81%   |
| Samsung SSD 870 EVO 250GB       | 13       | 0.81%   |
| Transcend TS32GMSA370 32GB      | 12       | 0.75%   |
| Kingston SUV500MS120G 120GB     | 12       | 0.75%   |
| Innodisk DEMSR- 08GB mSATA 3ME3 | 12       | 0.75%   |
| Hoodisk SSD 64GB                | 11       | 0.69%   |
| Samsung SSD 840 EVO 250GB       | 10       | 0.62%   |
| Kingston SKC600MS256G 256GB     | 10       | 0.62%   |
| Kingston SA400S37120G 120GB     | 10       | 0.62%   |
| Kingston SA400S37240G 240GB     | 9        | 0.56%   |
| Transcend TS32GSSD370S 32GB     | 8        | 0.5%    |
| Samsung SSD 970 EVO Plus 500GB  | 8        | 0.5%    |
| Intenso SSD 128GB               | 8        | 0.5%    |
| Intenso SSD 120GB               | 8        | 0.5%    |
| China IM128-P130 128GB          | 8        | 0.5%    |
| Transcend TS64GMSA370 64GB      | 7        | 0.44%   |
| Transcend TS128GMSA370 128GB    | 7        | 0.44%   |
| SanDisk SDSSDA120G 120GB        | 7        | 0.44%   |
| Samsung SSD 860 EVO 250GB       | 7        | 0.44%   |
| Kingston SV300S37A120G 120GB    | 7        | 0.44%   |
| Kingston OM8PDP3512B-A01 512GB  | 7        | 0.44%   |
| Hoodisk SSD 256GB               | 7        | 0.44%   |
| Hoodisk SSD 128GB               | 7        | 0.44%   |
| Crucial CT500MX500SSD1 500GB    | 7        | 0.44%   |
| WDC WD40EFRX-68N32N0 4TB        | 6        | 0.37%   |
| SanDisk SSD PLUS 240GB          | 6        | 0.37%   |
| SanDisk SSD PLUS 120GB          | 6        | 0.37%   |
| SanDisk SDSSDP128G 128GB        | 6        | 0.37%   |
| Samsung SSD 970 PRO 512GB       | 6        | 0.37%   |
| Samsung SSD 860 EVO mSATA 250GB | 6        | 0.37%   |
| Samsung SSD 850 PRO 256GB       | 6        | 0.37%   |
| Samsung SSD 840 EVO 120GB       | 6        | 0.37%   |
| Patriot M.2 P300 128GB          | 6        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 88       | 162    | 32.12%  |
| Seagate             | 62       | 98     | 22.63%  |
| Toshiba             | 35       | 67     | 12.77%  |
| Hitachi             | 22       | 45     | 8.03%   |
| HGST                | 21       | 39     | 7.66%   |
| Samsung Electronics | 18       | 26     | 6.57%   |
| NVMe                | 7        | 8      | 2.55%   |
| OPENBSD             | 3        | 7      | 1.09%   |
| Maxtor              | 2        | 2      | 0.73%   |
| JetFlash            | 2        | 2      | 0.73%   |
| Hewlett-Packard     | 2        | 2      | 0.73%   |
| Fujitsu             | 2        | 2      | 0.73%   |
| WD MediaMax         | 1        | 3      | 0.36%   |
| Product:            | 1        | 1      | 0.36%   |
| LSI                 | 1        | 1      | 0.36%   |
| Intenso             | 1        | 1      | 0.36%   |
| IBM/Hitachi         | 1        | 1      | 0.36%   |
| IBM                 | 1        | 1      | 0.36%   |
| Generic             | 1        | 1      | 0.36%   |
| General             | 1        | 1      | 0.36%   |
| ASMT                | 1        | 1      | 0.36%   |
| Apple               | 1        | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 182      | 297    | 17.4%   |
| Transcend           | 135      | 193    | 12.91%  |
| Kingston            | 94       | 156    | 8.99%   |
| SanDisk             | 79       | 119    | 7.55%   |
| Crucial             | 71       | 106    | 6.79%   |
| China               | 67       | 79     | 6.41%   |
| Intel               | 49       | 81     | 4.68%   |
| Phison              | 35       | 50     | 3.35%   |
| Intenso             | 33       | 55     | 3.15%   |
| Innodisk            | 30       | 36     | 2.87%   |
| Hoodisk             | 30       | 56     | 2.87%   |
| WDC                 | 18       | 20     | 1.72%   |
| Micron Technology   | 17       | 31     | 1.63%   |
| A-DATA Technology   | 14       | 17     | 1.34%   |
| Protectli           | 13       | 18     | 1.24%   |
| Toshiba             | 12       | 15     | 1.15%   |
| FORESEE             | 12       | 16     | 1.15%   |
| OCZ                 | 10       | 14     | 0.96%   |
| ATP                 | 8        | 9      | 0.76%   |
| Apacer              | 8        | 17     | 0.76%   |
| Patriot             | 7        | 10     | 0.67%   |
| Verbatim            | 6        | 7      | 0.57%   |
| TCSUNBOW            | 6        | 7      | 0.57%   |
| ShiJi               | 6        | 7      | 0.57%   |
| NVMe                | 6        | 11     | 0.57%   |
| LITEONIT            | 6        | 9      | 0.57%   |
| Dogfish             | 6        | 7      | 0.57%   |
| SPCC                | 5        | 9      | 0.48%   |
| KingSpec            | 5        | 6      | 0.48%   |
| Vaseky              | 4        | 4      | 0.38%   |
| Seagate             | 4        | 10     | 0.38%   |
| PNY                 | 4        | 5      | 0.38%   |
| Leven               | 4        | 6      | 0.38%   |
| KingDian            | 4        | 11     | 0.38%   |
| Corsair             | 4        | 8      | 0.38%   |
| BORY                | 4        | 7      | 0.38%   |
| Advantech           | 4        | 6      | 0.38%   |
| Team                | 3        | 3      | 0.29%   |
| SK hynix            | 3        | 4      | 0.29%   |
| MEMXPRO             | 3        | 4      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 970      | 1568   | 68.75%  |
| HDD  | 222      | 472    | 15.73%  |
| NVMe | 219      | 341    | 15.52%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1103     | 2040   | 83.43%  |
| NVMe | 219      | 341    | 16.57%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 1011     | 1600   | 82.8%   |
| 0.51-1.0        | 112      | 182    | 9.17%   |
| 1.01-2.0        | 49       | 135    | 4.01%   |
| 3.01-4.0        | 21       | 53     | 1.72%   |
| 2.01-3.0        | 12       | 33     | 0.98%   |
| 4.01-10.0       | 12       | 25     | 0.98%   |
| 10.01-20.0      | 3        | 11     | 0.25%   |
| More than 100.0 | 1        | 1      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 621      | 43.73%  |
| 251-500        | 194      | 13.66%  |
| 1-20           | 184      | 12.96%  |
| 21-50          | 169      | 11.9%   |
| 51-100         | 138      | 9.72%   |
| 501-1000       | 75       | 5.28%   |
| 1001-2000      | 16       | 1.13%   |
| More than 3000 | 11       | 0.77%   |
| 2001-3000      | 6        | 0.42%   |
| Unknown        | 6        | 0.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1322     | 92.77%  |
| 21-50          | 58       | 4.07%   |
| 51-100         | 15       | 1.05%   |
| 101-250        | 6        | 0.42%   |
| Unknown        | 6        | 0.42%   |
| 251-500        | 5        | 0.35%   |
| 501-1000       | 5        | 0.35%   |
| 1001-2000      | 4        | 0.28%   |
| More than 3000 | 2        | 0.14%   |
| 2001-3000      | 2        | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| Kingston SV300S37A60G 64GB                   | 4        | 6      | 3.42%   |
| WDC WD2000FYYZ-01UL1B2 2TB                   | 3        | 5      | 2.56%   |
| Kingston SMS200S360G 64GB                    | 3        | 3      | 2.56%   |
| WDC WDS240G2G0A-00JH30 240GB                 | 2        | 3      | 1.71%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 2        | 7      | 1.71%   |
| WDC WD2000FYYZ-01UL1B1 2TB                   | 2        | 4      | 1.71%   |
| WDC WD1600AAJS-75M0A0 160GB                  | 2        | 2      | 1.71%   |
| Toshiba THNSNK128GCS8 SATA 128GB             | 2        | 2      | 1.71%   |
| Seagate ST3160318AS 160GB                    | 2        | 2      | 1.71%   |
| Seagate ST1000DX001-1CM162 1TB               | 2        | 2      | 1.71%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 2        | 4      | 1.71%   |
| Samsung Electronics HD501LJ 500GB            | 2        | 2      | 1.71%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB   | 2        | 4      | 1.71%   |
| Kingston SMS200S3120G 120GB                  | 2        | 5      | 1.71%   |
| Intenso SSD SATAIII 256GB                    | 2        | 2      | 1.71%   |
| Intel SSDSC2CT120A3 120GB                    | 2        | 2      | 1.71%   |
| HGST HTS541010A7E630 1TB                     | 2        | 4      | 1.71%   |
| Crucial CT275MX300SSD1 275GB                 | 2        | 2      | 1.71%   |
| Crucial CT128MX100SSD1 128GB                 | 2        | 3      | 1.71%   |
| WDC WD60EFRX-68TGBN1 6TB                     | 1        | 3      | 0.85%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1        | 1      | 0.85%   |
| WDC WD2503ABYX-01WERA0 256GB                 | 1        | 2      | 0.85%   |
| WDC WD1600AAJS-08L7A0 160GB                  | 1        | 1      | 0.85%   |
| WDC WD1600AABS-00PRA0 160GB                  | 1        | 1      | 0.85%   |
| WDC WD10EZEX-60WN4A0 1TB                     | 1        | 1      | 0.85%   |
| WDC WD10EAVS-00D7B0 1TB                      | 1        | 1      | 0.85%   |
| WDC WD10EACS-00D6B1 1TB                      | 1        | 2      | 0.85%   |
| Transcend TS8GMSM610 8GB                     | 1        | 2      | 0.85%   |
| Transcend TS32GMSA370 32GB                   | 1        | 1      | 0.85%   |
| Toshiba MQ02ABD100H 1TB                      | 1        | 4      | 0.85%   |
| Toshiba MK3261GSYN 320GB                     | 1        | 1      | 0.85%   |
| Toshiba MK1676GSX H 160GB                    | 1        | 2      | 0.85%   |
| SPCC M.2 PCIe SSD 256GB                      | 1        | 1      | 0.85%   |
| SMI SSD DISK 120GB                           | 1        | 1      | 0.85%   |
| Seagate ST9500620NS 500GB                    | 1        | 1      | 0.85%   |
| Seagate ST9500325AS 500GB                    | 1        | 1      | 0.85%   |
| Seagate ST9320325AS 320GB                    | 1        | 1      | 0.85%   |
| Seagate ST9250827AS 250GB                    | 1        | 2      | 0.85%   |
| Seagate ST9160310AS 160GB                    | 1        | 2      | 0.85%   |
| Seagate ST500DM002-1BD142 500GB              | 1        | 2      | 0.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 26     | 17.39%  |
| WDC                 | 19       | 33     | 16.52%  |
| Samsung Electronics | 12       | 16     | 10.43%  |
| Kingston            | 11       | 17     | 9.57%   |
| Intel               | 9        | 10     | 7.83%   |
| Crucial             | 8        | 22     | 6.96%   |
| Toshiba             | 5        | 9      | 4.35%   |
| HGST                | 5        | 7      | 4.35%   |
| Micron Technology   | 4        | 7      | 3.48%   |
| Hitachi             | 4        | 5      | 3.48%   |
| Transcend           | 2        | 3      | 1.74%   |
| SanDisk             | 2        | 3      | 1.74%   |
| OCZ                 | 2        | 2      | 1.74%   |
| Maxtor              | 2        | 2      | 1.74%   |
| Intenso             | 2        | 2      | 1.74%   |
| SPCC                | 1        | 1      | 0.87%   |
| SMI                 | 1        | 1      | 0.87%   |
| KingSpec            | 1        | 1      | 0.87%   |
| KingDian            | 1        | 4      | 0.87%   |
| Corsair             | 1        | 3      | 0.87%   |
| China               | 1        | 2      | 0.87%   |
| Apacer              | 1        | 1      | 0.87%   |
| A-DATA Technology   | 1        | 2      | 0.87%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 26     | 36.36%  |
| WDC                 | 17       | 30     | 30.91%  |
| HGST                | 5        | 7      | 9.09%   |
| Samsung Electronics | 4        | 6      | 7.27%   |
| Hitachi             | 4        | 5      | 7.27%   |
| Toshiba             | 3        | 7      | 5.45%   |
| Maxtor              | 2        | 2      | 3.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 57       | 93     | 50.44%  |
| HDD  | 53       | 83     | 46.9%   |
| NVMe | 3        | 3      | 2.65%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD3200BPVT-16JJ5T0 320GB      | 1        | 1      | 20%     |
| Transcend TS32GSSD370S 32GB       | 1        | 2      | 20%     |
| Samsung Electronics SSD 980 250GB | 1        | 2      | 20%     |
| Kingston SV300S37A60G 64GB        | 1        | 1      | 20%     |
| Kingston SMS200S330G 32GB         | 1        | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 2        | 2      | 40%     |
| WDC                 | 1        | 1      | 20%     |
| Transcend           | 1        | 2      | 20%     |
| Samsung Electronics | 1        | 2      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1189     | 2134   | 88.8%   |
| Malfunc  | 111      | 179    | 8.29%   |
| Detected | 34       | 61     | 2.54%   |
| Failed   | 5        | 7      | 0.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 965      | 58.17%  |
| AMD                            | 363      | 21.88%  |
| Samsung Electronics            | 76       | 4.58%   |
| SanDisk                        | 33       | 1.99%   |
| ASMedia Technology             | 29       | 1.75%   |
| Kingston Technology Company    | 27       | 1.63%   |
| Silicon Motion                 | 20       | 1.21%   |
| Phison Electronics             | 19       | 1.15%   |
| MAXIO Technology (Hangzhou)    | 19       | 1.15%   |
| Micron/Crucial Technology      | 13       | 0.78%   |
| Marvell Technology Group       | 9        | 0.54%   |
| Broadcom / LSI                 | 9        | 0.54%   |
| KIOXIA                         | 8        | 0.48%   |
| Nvidia                         | 7        | 0.42%   |
| Shenzhen Longsys Electronics   | 6        | 0.36%   |
| Micron Technology              | 6        | 0.36%   |
| VIA Technologies               | 5        | 0.3%    |
| Toshiba                        | 5        | 0.3%    |
| SK hynix                       | 5        | 0.3%    |
| JMicron Technology             | 5        | 0.3%    |
| Silicon Image                  | 3        | 0.18%   |
| Realtek Semiconductor          | 3        | 0.18%   |
| Hosin Global Electronics       | 3        | 0.18%   |
| Hewlett-Packard                | 3        | 0.18%   |
| Yangtze Memory Technologies    | 2        | 0.12%   |
| Solid State Storage Technology | 2        | 0.12%   |
| Seagate Technology             | 2        | 0.12%   |
| Adaptec                        | 2        | 0.12%   |
| Unknown                        | 2        | 0.12%   |
| ULi Electronics                | 1        | 0.06%   |
| Transcend                      | 1        | 0.06%   |
| Integrated Technology Express  | 1        | 0.06%   |
| Enmotus                        | 1        | 0.06%   |
| Chelsio Communications         | 1        | 0.06%   |
| ATP ELECTRONICS                | 1        | 0.06%   |
| Artop Electronic               | 1        | 0.06%   |
| 3ware                          | 1        | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 243      | 13.02%  |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 104      | 5.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 84       | 4.5%    |
| AMD FCH SATA Controller [IDE mode]                                               | 64       | 3.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 60       | 3.21%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 57       | 3.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 52       | 2.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 52       | 2.79%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 46       | 2.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 42       | 2.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 39       | 2.09%   |
| Intel unknown                                                                    | 37       | 1.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 35       | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 35       | 1.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 29       | 1.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 28       | 1.5%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 27       | 1.45%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 27       | 1.45%   |
| AMD 400 Series Chipset SATA Controller                                           | 27       | 1.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 25       | 1.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 24       | 1.29%   |
| Intel Comet Lake SATA AHCI Controller                                            | 22       | 1.18%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 22       | 1.18%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 19       | 1.02%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 19       | 1.02%   |
| Intel SATA Controller [RAID mode]                                                | 18       | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 18       | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 17       | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 17       | 0.91%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 16       | 0.86%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 15       | 0.8%    |
| Intel Elkhart Lake SATA AHCI                                                     | 15       | 0.8%    |
| Intel Tiger Lake-LP SATA Controller                                              | 14       | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 14       | 0.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14       | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 13       | 0.7%    |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 13       | 0.7%    |
| Kingston Company OM3PDP3 NVMe SSD                                                | 12       | 0.64%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 12       | 0.64%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 10       | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1176     | 70.08%  |
| NVMe | 256      | 15.26%  |
| IDE  | 188      | 11.2%   |
| RAID | 45       | 2.68%   |
| SCSI | 8        | 0.48%   |
| SAS  | 5        | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 1003     | 72.26%  |
| AMD     | 373      | 26.87%  |
| ARM     | 8        | 0.58%   |
| VIA     | 2        | 0.14%   |
| Sun     | 1        | 0.07%   |
| Unknown | 1        | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| AMD GX-412TC SOC                          | 131      | 9.37%   |
| Intel Celeron J4125 CPU @ 2.00GHz         | 70       | 5.01%   |
| Intel Celeron N5105 @ 2.00GHz             | 46       | 3.29%   |
| Intel N100                                | 38       | 2.72%   |
| AMD GX-415GA SOC with Radeon HD Graphics  | 38       | 2.72%   |
| Intel Celeron CPU J3160 @ 1.60GHz         | 29       | 2.07%   |
| Intel Celeron CPU J1900 @ 1.99GHz         | 29       | 2.07%   |
| AMD GX-222GC SOC with Radeon R5E Graphics | 24       | 1.72%   |
| Intel Atom CPU D525 @ 1.80GHz             | 16       | 1.14%   |
| Intel Core i5-6500 CPU @ 3.20GHz          | 15       | 1.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz         | 14       | 1%      |
| AMD G-T40E Processor                      | 14       | 1%      |
| Intel Core i7-7500U CPU @ 2.70GHz         | 13       | 0.93%   |
| Intel Celeron J4105 CPU @ 1.50GHz         | 13       | 0.93%   |
| Intel Celeron CPU J3455 @ 1.50GHz         | 13       | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz         | 12       | 0.86%   |
| Intel Atom CPU C3558 @ 2.20GHz            | 12       | 0.86%   |
| AMD GX-424CC SOC with Radeon R5E Graphics | 12       | 0.86%   |
| Intel Celeron J6412 @ 2.00GHz             | 11       | 0.79%   |
| Intel Core i5-3470 CPU @ 3.20GHz          | 10       | 0.72%   |
| Intel Celeron CPU N3150 @ 1.60GHz         | 10       | 0.72%   |
| AMD GX-420CA SOC with Radeon HD Graphics  | 10       | 0.72%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz        | 9        | 0.64%   |
| Intel Celeron J4115 CPU @ 1.80GHz         | 9        | 0.64%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz  | 8        | 0.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz         | 8        | 0.57%   |
| Intel Core i7-7700 CPU @ 3.60GHz          | 8        | 0.57%   |
| Intel Core i5-8365U CPU @ 1.60GHz         | 8        | 0.57%   |
| Intel Celeron CPU N3160 @ 1.60GHz         | 8        | 0.57%   |
| Intel Atom CPU E3845 @ 1.91GHz            | 8        | 0.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz        | 7        | 0.5%    |
| Intel Core i3-N305                        | 7        | 0.5%    |
| Intel Core i3-7100U CPU @ 2.40GHz         | 7        | 0.5%    |
| Intel Core i3-6100 CPU @ 3.70GHz          | 7        | 0.5%    |
| Intel Celeron CPU N3450 @ 1.10GHz         | 7        | 0.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz   | 7        | 0.5%    |
| Intel Pentium Silver N6005 @ 2.00GHz      | 6        | 0.43%   |
| Intel Core i5-8265U CPU @ 1.60GHz         | 6        | 0.43%   |
| Intel Core i5-6500T CPU @ 2.50GHz         | 6        | 0.43%   |
| Intel Core i5-4590 CPU @ 3.30GHz          | 6        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 318      | 22.8%   |
| AMD GX                  | 228      | 16.34%  |
| Intel Core i5           | 202      | 14.48%  |
| Intel Core i3           | 109      | 7.81%   |
| Other                   | 89       | 6.38%   |
| Intel Core i7           | 82       | 5.88%   |
| Intel Xeon              | 72       | 5.16%   |
| Intel Atom              | 71       | 5.09%   |
| AMD Ryzen 7             | 28       | 2.01%   |
| AMD Ryzen 5             | 25       | 1.79%   |
| Intel Pentium Silver    | 20       | 1.43%   |
| AMD G                   | 19       | 1.36%   |
| Intel Pentium           | 16       | 1.15%   |
| AMD FX                  | 15       | 1.08%   |
| Intel Core 2 Quad       | 10       | 0.72%   |
| Intel Core 2 Duo        | 9        | 0.65%   |
| Intel Pentium Dual-Core | 6        | 0.43%   |
| AMD Ryzen 5 PRO         | 6        | 0.43%   |
| Intel Pentium Gold      | 5        | 0.36%   |
| AMD Ryzen 9             | 5        | 0.36%   |
| AMD Ryzen 3             | 5        | 0.36%   |
| AMD Athlon 64 X2        | 5        | 0.36%   |
| AMD Athlon              | 5        | 0.36%   |
| ARM Cortex              | 4        | 0.29%   |
| AMD Ryzen 7 PRO         | 4        | 0.29%   |
| AMD E                   | 4        | 0.29%   |
| Intel Core i9           | 3        | 0.22%   |
| AMD Turion II Neo       | 3        | 0.22%   |
| AMD Ryzen Threadripper  | 3        | 0.22%   |
| AMD Ryzen Embedded      | 3        | 0.22%   |
| AMD Athlon Dual Core    | 3        | 0.22%   |
| AMD A10                 | 3        | 0.22%   |
| AMD A8                  | 2        | 0.14%   |
| AMD A4                  | 2        | 0.14%   |
| Intel Xeon Gold         | 1        | 0.07%   |
| Intel Pentium Dual      | 1        | 0.07%   |
| Intel Pentium 4         | 1        | 0.07%   |
| Intel Core 2            | 1        | 0.07%   |
| Intel 686-class         | 1        | 0.07%   |
| AMD Phenom II X4        | 1        | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 849      | 60.9%   |
| 2       | 332      | 23.82%  |
| 8       | 55       | 3.95%   |
| 6       | 54       | 3.87%   |
| 16      | 34       | 2.44%   |
| Unknown | 27       | 1.94%   |
| 12      | 21       | 1.51%   |
| 1       | 12       | 0.86%   |
| 32      | 6        | 0.43%   |
| 10      | 2        | 0.14%   |
| 36      | 1        | 0.07%   |
| 3       | 1        | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1357     | 98.12%  |
| Unknown | 15       | 1.08%   |
| 2       | 11       | 0.8%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 974      | 70.38%  |
| 2       | 382      | 27.6%   |
| Unknown | 28       | 2.02%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 175      | 12.55%  |
| Puma          | 173      | 12.41%  |
| Unknown       | 173      | 12.41%  |
| Goldmont plus | 106      | 7.6%    |
| Silvermont    | 105      | 7.53%   |
| Haswell       | 86       | 6.17%   |
| Skylake       | 69       | 4.95%   |
| Jaguar        | 59       | 4.23%   |
| IvyBridge     | 59       | 4.23%   |
| Goldmont      | 45       | 3.23%   |
| Bonnell       | 38       | 2.73%   |
| SandyBridge   | 34       | 2.44%   |
| Penryn        | 30       | 2.15%   |
| Zen+          | 24       | 1.72%   |
| Zen 2         | 23       | 1.65%   |
| Bobcat        | 23       | 1.65%   |
| CometLake     | 21       | 1.51%   |
| Zen           | 20       | 1.43%   |
| TigerLake     | 16       | 1.15%   |
| Piledriver    | 15       | 1.08%   |
| Core          | 15       | 1.08%   |
| Broadwell     | 14       | 1%      |
| Zen 3         | 13       | 0.93%   |
| Westmere      | 13       | 0.93%   |
| Nehalem       | 11       | 0.79%   |
| K8 Hammer     | 9        | 0.65%   |
| IceLake       | 9        | 0.65%   |
| K10           | 6        | 0.43%   |
| Bulldozer     | 4        | 0.29%   |
| Excavator     | 2        | 0.14%   |
| Steamroller   | 1        | 0.07%   |
| NetBurst      | 1        | 0.07%   |
| K10 Llano     | 1        | 0.07%   |
| Geode         | 1        | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 861      | 71.45%  |
| AMD                                          | 198      | 16.43%  |
| Nvidia                                       | 81       | 6.72%   |
| ASPEED Technology                            | 36       | 2.99%   |
| Matrox Electronics Systems                   | 26       | 2.16%   |
| VIA Technologies                             | 2        | 0.17%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                      | 94       | 7.71%   |
| Intel JasperLake [UHD Graphics]                                                          | 68       | 5.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 53       | 4.35%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 52       | 4.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 50       | 4.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 40       | 3.28%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 38       | 3.12%   |
| Intel HD Graphics 620                                                                    | 37       | 3.04%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 36       | 2.95%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 36       | 2.95%   |
| Intel HD Graphics 530                                                                    | 33       | 2.71%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 29       | 2.38%   |
| Intel HD Graphics 500                                                                    | 26       | 2.13%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 23       | 1.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22       | 1.8%    |
| Intel UHD Graphics 620                                                                   | 21       | 1.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 21       | 1.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 18       | 1.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 16       | 1.31%   |
| Intel HD Graphics 630                                                                    | 16       | 1.31%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 16       | 1.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15       | 1.23%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 15       | 1.23%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 14       | 1.15%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 12       | 0.98%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 12       | 0.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12       | 0.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11       | 0.9%    |
| AMD Kabini [Radeon HD 8400E]                                                             | 11       | 0.9%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 10       | 0.82%   |
| Matrox Electronics Systems MGA G200EH                                                    | 10       | 0.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10       | 0.82%   |
| Intel HD Graphics 610                                                                    | 10       | 0.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10       | 0.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10       | 0.82%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9        | 0.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9        | 0.74%   |
| Intel HD Graphics 5500                                                                   | 8        | 0.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8        | 0.66%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 8        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 818      | 58.81%  |
| Other          | 199      | 14.31%  |
| 1 x AMD        | 196      | 14.09%  |
| 1 x Nvidia     | 73       | 5.25%   |
| 1 x ASPEED     | 33       | 2.37%   |
| 2 x Intel      | 30       | 2.16%   |
| 1 x Matrox     | 25       | 1.8%    |
| Intel + Nvidia | 8        | 0.58%   |
| Intel + ASPEED | 3        | 0.22%   |
| 1 x VIA        | 2        | 0.14%   |
| 2 x AMD        | 1        | 0.07%   |
| 1 x XGI        | 1        | 0.07%   |
| Intel + Matrox | 1        | 0.07%   |
| Intel + AMD    | 1        | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1130     | 81.47%  |
| Unknown     | 206      | 14.85%  |
| Proprietary | 51       | 3.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1304     | 93.61%  |
| 1.01-2.0   | 29       | 2.08%   |
| 3.01-4.0   | 15       | 1.08%   |
| 0.51-1.0   | 11       | 0.79%   |
| 0.01-0.5   | 11       | 0.79%   |
| 7.01-8.0   | 9        | 0.65%   |
| 5.01-6.0   | 9        | 0.65%   |
| 2.01-3.0   | 4        | 0.29%   |
| 8.01-16.0  | 1        | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 22       | 16.18%  |
| Goldstar             | 14       | 10.29%  |
| Dell                 | 13       | 9.56%   |
| BenQ                 | 12       | 8.82%   |
| Acer                 | 11       | 8.09%   |
| Hewlett-Packard      | 8        | 5.88%   |
| Eizo                 | 7        | 5.15%   |
| Ancor Communications | 7        | 5.15%   |
| LG Electronics       | 6        | 4.41%   |
| Iiyama               | 6        | 4.41%   |
| NEC Computers        | 5        | 3.68%   |
| Fujitsu Siemens      | 5        | 3.68%   |
| Philips              | 3        | 2.21%   |
| Idek Iiyama          | 3        | 2.21%   |
| HannStar             | 2        | 1.47%   |
| ASUSTek Computer     | 2        | 1.47%   |
| AOC                  | 2        | 1.47%   |
| WYT                  | 1        | 0.74%   |
| Vestel Elektronik    | 1        | 0.74%   |
| Mi                   | 1        | 0.74%   |
| LG Display           | 1        | 0.74%   |
| Lenovo               | 1        | 0.74%   |
| CMT                  | 1        | 0.74%   |
| CHD                  | 1        | 0.74%   |
| Belinea              | 1        | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch            | 3        | 2.01%   |
| Fujitsu Siemens B24-9 WE FUS08C3 1920x1200 520x320mm 24.0-inch        | 3        | 2.01%   |
| Samsung Electronics C32JG5x SAM0FDE 2560x1440 700x390mm 31.5-inch     | 2        | 1.34%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 600x340mm 27.2-inch     | 2        | 1.34%   |
| NEC Computers EX341R NEC2C7A 3440x1440 800x330mm 34.1-inch            | 2        | 1.34%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 540x350mm 25.3-inch         | 2        | 1.34%   |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 540x350mm 25.3-inch         | 2        | 1.34%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch          | 2        | 1.34%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch              | 2        | 1.34%   |
| Goldstar E2441 GSM581F 1920x1080 530x300mm 24.0-inch                  | 2        | 1.34%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                     | 2        | 1.34%   |
| Dell LCD Monitor U2412M 3840x1200                                     | 2        | 1.34%   |
| Dell LCD Monitor U2412M                                               | 2        | 1.34%   |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                     | 2        | 1.34%   |
| BenQ GL2760 BNQ78D5 1920x1080 600x340mm 27.2-inch                     | 2        | 1.34%   |
| BenQ GL2450H BNQ78A6 1920x1080 530x300mm 24.0-inch                    | 2        | 1.34%   |
| Ancor Communications MX27AQ ACI27A5 2560x1440 600x340mm 27.2-inch     | 2        | 1.34%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                  | 1        | 0.67%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1        | 0.67%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1        | 0.67%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 520x320mm 24.0-inch  | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM036C 1920x1200 550x340mm 25.5-inch  | 1        | 0.67%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 600x340mm 27.2-inch   | 1        | 0.67%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 520x320mm 24.0-inch   | 1        | 0.67%   |
| Samsung Electronics SAMTRON STN0028 1280x1024 380x300mm 19.1-inch     | 1        | 0.67%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 480x270mm 21.7-inch | 1        | 0.67%   |
| Samsung Electronics S24C650 SAM09E9 1920x1080 520x290mm 23.4-inch     | 1        | 0.67%   |
| Samsung Electronics S24C650 SAM09E8 1920x1080 520x290mm 23.4-inch     | 1        | 0.67%   |
| Samsung Electronics S24C650 SAM09E7 1920x1080 520x290mm 23.4-inch     | 1        | 0.67%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 480x270mm 21.7-inch     | 1        | 0.67%   |
| Samsung Electronics LCD Monitor T27C370 1920x1080                     | 1        | 0.67%   |
| Samsung Electronics LCD Monitor SMB2430L 1920x1080                    | 1        | 0.67%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 890x500mm 40.2-inch | 1        | 0.67%   |
| Samsung Electronics LCD Monitor S22C300 1920x1080                     | 1        | 0.67%   |
| Samsung Electronics LCD Monitor CF791 3440x1440                       | 1        | 0.67%   |
| Samsung Electronics CF791 SAM0DC3 3440x1440 800x330mm 34.1-inch       | 1        | 0.67%   |
| Samsung Electronics C27FG7x SAM0E42 1920x1080 600x340mm 27.2-inch     | 1        | 0.67%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1        | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 58       | 42.34%  |
| 2560x1440 (QHD)    | 17       | 12.41%  |
| 3840x2160 (4K)     | 16       | 11.68%  |
| 1920x1200 (WUXGA)  | 16       | 11.68%  |
| 1280x1024 (SXGA)   | 8        | 5.84%   |
| 3440x1440          | 5        | 3.65%   |
| 1680x1050 (WSXGA+) | 4        | 2.92%   |
| Unknown            | 3        | 2.19%   |
| 3840x1200          | 2        | 1.46%   |
| 2560x1080          | 2        | 1.46%   |
| 1440x900 (WXGA+)   | 2        | 1.46%   |
| 3840x1080          | 1        | 0.73%   |
| 3600x1080          | 1        | 0.73%   |
| 1920x540           | 1        | 0.73%   |
| 1366x768 (WXGA)    | 1        | 0.73%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 33       | 24.26%  |
| 24      | 30       | 22.06%  |
| Unknown | 19       | 13.97%  |
| 21      | 13       | 9.56%   |
| 23      | 12       | 8.82%   |
| 19      | 6        | 4.41%   |
| 34      | 5        | 3.68%   |
| 31      | 4        | 2.94%   |
| 22      | 4        | 2.94%   |
| 25      | 3        | 2.21%   |
| 46      | 1        | 0.74%   |
| 42      | 1        | 0.74%   |
| 32      | 1        | 0.74%   |
| 18      | 1        | 0.74%   |
| 17      | 1        | 0.74%   |
| 16      | 1        | 0.74%   |
| 13      | 1        | 0.74%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 74       | 54.81%  |
| Unknown     | 19       | 14.07%  |
| 401-500     | 17       | 12.59%  |
| 601-700     | 8        | 5.93%   |
| 701-800     | 6        | 4.44%   |
| 351-400     | 6        | 4.44%   |
| 301-350     | 3        | 2.22%   |
| 1001-1500   | 1        | 0.74%   |
| 901-1000    | 1        | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 81       | 61.36%  |
| 16/10   | 19       | 14.39%  |
| Unknown | 18       | 13.64%  |
| 5/4     | 6        | 4.55%   |
| 21/9    | 5        | 3.79%   |
| 3/2     | 2        | 1.52%   |
| 6/5     | 1        | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 43       | 31.85%  |
| 301-350        | 33       | 24.44%  |
| Unknown        | 19       | 14.07%  |
| 251-300        | 18       | 13.33%  |
| 351-500        | 10       | 7.41%   |
| 151-200        | 7        | 5.19%   |
| 501-1000       | 2        | 1.48%   |
| 81-90          | 1        | 0.74%   |
| 141-150        | 1        | 0.74%   |
| 131-140        | 1        | 0.74%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 75       | 55.56%  |
| 101-120 | 26       | 19.26%  |
| Unknown | 19       | 14.07%  |
| 161-240 | 9        | 6.67%   |
| 121-160 | 5        | 3.7%    |
| 1-50    | 1        | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1252     | 90.27%  |
| 1     | 121      | 8.72%   |
| 2     | 13       | 0.94%   |
| 3     | 1        | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 1113     | 60.52%  |
| Realtek Semiconductor             | 464      | 25.23%  |
| Qualcomm Atheros                  | 72       | 3.92%   |
| Broadcom                          | 60       | 3.26%   |
| IMC Networks                      | 16       | 0.87%   |
| Mellanox Technologies             | 15       | 0.82%   |
| TP-Link                           | 9        | 0.49%   |
| U-Blox                            | 8        | 0.44%   |
| D-Link System                     | 7        | 0.38%   |
| American Megatrends               | 7        | 0.38%   |
| Marvell Technology Group          | 6        | 0.33%   |
| Edimax Technology                 | 5        | 0.27%   |
| Ralink Technology                 | 4        | 0.22%   |
| Ralink                            | 4        | 0.22%   |
| MediaTek                          | 4        | 0.22%   |
| Huawei Technologies               | 4        | 0.22%   |
| Chelsio Communications            | 4        | 0.22%   |
| Aquantia                          | 3        | 0.16%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.11%   |
| Samsung Electronics               | 2        | 0.11%   |
| ICS Advent                        | 2        | 0.11%   |
| Ericsson Business Mobile Networks | 2        | 0.11%   |
| Emulex                            | 2        | 0.11%   |
| Dresden Elektronik                | 2        | 0.11%   |
| Xiaomi                            | 1        | 0.05%   |
| Winbond Electronics               | 1        | 0.05%   |
| T & A Mobile Phones               | 1        | 0.05%   |
| SysKonnect                        | 1        | 0.05%   |
| Standard Microsystems [SMC]       | 1        | 0.05%   |
| Qualcomm Atheros Communications   | 1        | 0.05%   |
| QLogic                            | 1        | 0.05%   |
| Oculus VR                         | 1        | 0.05%   |
| Nvidia                            | 1        | 0.05%   |
| NetXen Incorporated               | 1        | 0.05%   |
| NetGear                           | 1        | 0.05%   |
| MYRICOM                           | 1        | 0.05%   |
| Motorola                          | 1        | 0.05%   |
| Digium                            | 1        | 0.05%   |
| Digital Equipment                 | 1        | 0.05%   |
| Dell                              | 1        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 399      | 18.19%  |
| Intel I211 Gigabit Network Connection                                         | 282      | 12.86%  |
| Intel I210 Gigabit Network Connection                                         | 163      | 7.43%   |
| Intel Ethernet Controller I225-V                                              | 115      | 5.24%   |
| Intel Ethernet Controller I226-V                                              | 99       | 4.51%   |
| Intel I350 Gigabit Network Connection                                         | 72       | 3.28%   |
| Intel 82574L Gigabit Network Connection                                       | 69       | 3.15%   |
| Intel 82580 Gigabit Network Connection                                        | 38       | 1.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 38       | 1.73%   |
| Realtek RTL8125 2.5GbE Controller                                             | 35       | 1.6%    |
| Intel 82576 Gigabit Network Connection                                        | 30       | 1.37%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 27       | 1.23%   |
| Intel 82583V Gigabit Network Connection                                       | 26       | 1.19%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 25       | 1.14%   |
| Intel Ethernet Connection (2) I219-V                                          | 23       | 1.05%   |
| Intel Wi-Fi 6 AX200                                                           | 21       | 0.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 19       | 0.87%   |
| Intel Ethernet Connection I217-LM                                             | 18       | 0.82%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 18       | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                                         | 16       | 0.73%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 15       | 0.68%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 15       | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 14       | 0.64%   |
| Intel Ethernet Connection X553 1GbE                                           | 13       | 0.59%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 13       | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 12       | 0.55%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 12       | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                                         | 11       | 0.5%    |
| Intel Centrino Advanced-N 6235                                                | 11       | 0.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 10       | 0.46%   |
| Intel Ethernet Connection (7) I219-V                                          | 10       | 0.46%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 9        | 0.41%   |
| Intel Ethernet Controller X550                                                | 9        | 0.41%   |
| Intel Ethernet Connection I219-LM                                             | 9        | 0.41%   |
| Intel Ethernet Connection I217-V                                              | 9        | 0.41%   |
| Intel 82579V Gigabit Network Connection                                       | 9        | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 8        | 0.36%   |
| Intel Wireless 7265                                                           | 8        | 0.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 7        | 0.32%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 7        | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 98       | 35.9%   |
| Qualcomm Atheros                | 63       | 23.08%  |
| Realtek Semiconductor           | 51       | 18.68%  |
| IMC Networks                    | 16       | 5.86%   |
| Broadcom                        | 13       | 4.76%   |
| TP-Link                         | 9        | 3.3%    |
| Edimax Technology               | 5        | 1.83%   |
| Ralink Technology               | 4        | 1.47%   |
| Ralink                          | 4        | 1.47%   |
| MediaTek                        | 4        | 1.47%   |
| Qualcomm Atheros Communications | 1        | 0.37%   |
| NetGear                         | 1        | 0.37%   |
| Marvell Technology Group        | 1        | 0.37%   |
| Dell                            | 1        | 0.37%   |
| ASUSTek Computer                | 1        | 0.37%   |
| Accton Technology               | 1        | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 21       | 7.58%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 19       | 6.86%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 15       | 5.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 14       | 5.05%   |
| Intel Centrino Advanced-N 6235                                  | 11       | 3.97%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 10       | 3.61%   |
| Intel Wireless 7265                                             | 8        | 2.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 7        | 2.53%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 7        | 2.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 6        | 2.17%   |
| Intel Wireless 7260                                             | 6        | 2.17%   |
| Intel Wireless 3160                                             | 6        | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 6        | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 5        | 1.81%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                             | 4        | 1.44%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 4        | 1.44%   |
| Intel Wireless 3165                                             | 4        | 1.44%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 4        | 1.44%   |
| Broadcom BCM43228 802.11a/b/g/n                                 | 4        | 1.44%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter         | 3        | 1.08%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 3        | 1.08%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                 | 3        | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 3        | 1.08%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                       | 3        | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 3        | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 3        | 1.08%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 3        | 1.08%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection   | 3        | 1.08%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 3        | 1.08%   |
| Intel CNVi: Wi-Fi                                               | 3        | 1.08%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 3        | 1.08%   |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 2        | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 2        | 0.72%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                 | 2        | 0.72%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 2        | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 2        | 0.72%   |
| Ralink RT2501/RT2573 Wireless Adapter                           | 2        | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 2        | 0.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 2        | 0.72%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                | 2        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 1068     | 66.38%  |
| Realtek Semiconductor       | 446      | 27.72%  |
| Broadcom                    | 48       | 2.98%   |
| Qualcomm Atheros            | 9        | 0.56%   |
| American Megatrends         | 7        | 0.44%   |
| Marvell Technology Group    | 5        | 0.31%   |
| D-Link System               | 5        | 0.31%   |
| Aquantia                    | 3        | 0.19%   |
| ZTE WCDMA Technologies MSM  | 2        | 0.12%   |
| Samsung Electronics         | 2        | 0.12%   |
| ICS Advent                  | 2        | 0.12%   |
| Xiaomi                      | 1        | 0.06%   |
| T & A Mobile Phones         | 1        | 0.06%   |
| SysKonnect                  | 1        | 0.06%   |
| Standard Microsystems [SMC] | 1        | 0.06%   |
| QLogic                      | 1        | 0.06%   |
| Nvidia                      | 1        | 0.06%   |
| MYRICOM                     | 1        | 0.06%   |
| Emulex                      | 1        | 0.06%   |
| Digital Equipment           | 1        | 0.06%   |
| Davicom Semiconductor       | 1        | 0.06%   |
| Chelsio Communications      | 1        | 0.06%   |
| Apple                       | 1        | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 399      | 21.43%  |
| Intel I211 Gigabit Network Connection                                         | 282      | 15.15%  |
| Intel I210 Gigabit Network Connection                                         | 163      | 8.75%   |
| Intel Ethernet Controller I225-V                                              | 115      | 6.18%   |
| Intel Ethernet Controller I226-V                                              | 99       | 5.32%   |
| Intel I350 Gigabit Network Connection                                         | 72       | 3.87%   |
| Intel 82574L Gigabit Network Connection                                       | 69       | 3.71%   |
| Intel 82580 Gigabit Network Connection                                        | 38       | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 38       | 2.04%   |
| Realtek RTL8125 2.5GbE Controller                                             | 34       | 1.83%   |
| Intel 82576 Gigabit Network Connection                                        | 30       | 1.61%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 27       | 1.45%   |
| Intel 82583V Gigabit Network Connection                                       | 26       | 1.4%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 25       | 1.34%   |
| Intel Ethernet Connection (2) I219-V                                          | 23       | 1.24%   |
| Intel Ethernet Connection I217-LM                                             | 18       | 0.97%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 18       | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                                         | 16       | 0.86%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 15       | 0.81%   |
| Intel Ethernet Connection X553 1GbE                                           | 13       | 0.7%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 13       | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 12       | 0.64%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 12       | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                                         | 11       | 0.59%   |
| Intel Ethernet Connection (7) I219-V                                          | 10       | 0.54%   |
| Intel Ethernet Controller X550                                                | 9        | 0.48%   |
| Intel Ethernet Connection I219-LM                                             | 9        | 0.48%   |
| Intel Ethernet Connection I217-V                                              | 9        | 0.48%   |
| Intel 82579V Gigabit Network Connection                                       | 9        | 0.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 8        | 0.43%   |
| American Megatrends Virtual Ethernet                                          | 7        | 0.38%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 6        | 0.32%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 6        | 0.32%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 6        | 0.32%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 6        | 0.32%   |
| Intel Ethernet Connection (14) I219-V                                         | 6        | 0.32%   |
| Intel 82575EB Gigabit Network Connection                                      | 6        | 0.32%   |
| Realtek USB 2.5GbE Controller                                                 | 5        | 0.27%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 5        | 0.27%   |
| Intel Ethernet Connection (5) I219-LM                                         | 5        | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1371     | 81.56%  |
| WiFi     | 259      | 15.41%  |
| Unknown  | 37       | 2.2%    |
| Modem    | 14       | 0.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1350     | 98.4%   |
| WiFi     | 21       | 1.53%   |
| Unknown  | 1        | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 336      | 23.88%  |
| 3     | 243      | 17.27%  |
| 2     | 201      | 14.29%  |
| 6     | 197      | 14%     |
| 1     | 188      | 13.36%  |
| 5     | 144      | 10.23%  |
| 8     | 31       | 2.2%    |
| 7     | 23       | 1.63%   |
| 10    | 15       | 1.07%   |
| 9     | 12       | 0.85%   |
| 0     | 10       | 0.71%   |
| 12    | 2        | 0.14%   |
| 11    | 2        | 0.14%   |
| 20    | 1        | 0.07%   |
| 17    | 1        | 0.07%   |
| 14    | 1        | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1089     | 74.85%  |
| Yes  | 366      | 25.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 89       | 58.55%  |
| Realtek Semiconductor           | 18       | 11.84%  |
| Qualcomm Atheros Communications | 16       | 10.53%  |
| IMC Networks                    | 9        | 5.92%   |
| ASUSTek Computer                | 5        | 3.29%   |
| Broadcom                        | 4        | 2.63%   |
| Apple                           | 4        | 2.63%   |
| MediaTek                        | 3        | 1.97%   |
| Micro Star International        | 1        | 0.66%   |
| Foxconn / Hon Hai               | 1        | 0.66%   |
| Cambridge Silicon Radio         | 1        | 0.66%   |
| Unknown                         | 1        | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 25       | 16.23%  |
| Intel AX200 Bluetooth                                       | 22       | 14.29%  |
| Realtek Bluetooth Adapter                                   | 14       | 9.09%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 13       | 8.44%   |
| Intel AX201 Bluetooth                                       | 9        | 5.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 8        | 5.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 7        | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                            | 6        | 3.9%    |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 6        | 3.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5        | 3.25%   |
| MediaTek RZ608 Bluetooth Adapter                            | 3        | 1.95%   |
| Intel AX210 Bluetooth                                       | 3        | 1.95%   |
| Apple Bluetooth Host Controller                             | 3        | 1.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2        | 1.3%    |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 2        | 1.3%    |
| Broadcom BCM2045 Bluetooth                                  | 2        | 1.3%    |
| ASUS USB-BT500                                              | 2        | 1.3%    |
| Realtek RTL8723B Bluetooth                                  | 1        | 0.65%   |
| Realtek RTL8723A Bluetooth                                  | 1        | 0.65%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1        | 0.65%   |
| Realtek Bluetooth 4.2 Adapter                               | 1        | 0.65%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1        | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1        | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1        | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1        | 0.65%   |
| Micro Star International MS-6970 BToes Bluetooth adapter    | 1        | 0.65%   |
| Intel AX211 Bluetooth                                       | 1        | 0.65%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1        | 0.65%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                  | 1        | 0.65%   |
| IMC Networks Bluetooth                                      | 1        | 0.65%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1        | 0.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1        | 0.65%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1        | 0.65%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1        | 0.65%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                | 1        | 0.65%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 0.65%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE       | 1        | 0.65%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 0.65%   |
| Unknown                                                     | 1        | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 745      | 67.42%  |
| AMD                                          | 224      | 20.27%  |
| Nvidia                                       | 72       | 6.52%   |
| C-Media Electronics                          | 16       | 1.45%   |
| Zoran Co. Personal Media Division (Nogatech) | 7        | 0.63%   |
| Logitech                                     | 6        | 0.54%   |
| JMTek                                        | 4        | 0.36%   |
| VIA Technologies                             | 3        | 0.27%   |
| Tenx Technology                              | 3        | 0.27%   |
| Creative Labs                                | 3        | 0.27%   |
| Texas Instruments                            | 2        | 0.18%   |
| Kingston Technology                          | 2        | 0.18%   |
| GN Netcom                                    | 2        | 0.18%   |
| Creative Technology                          | 2        | 0.18%   |
| Audient                                      | 2        | 0.18%   |
| ZOOM                                         | 1        | 0.09%   |
| Yamaha                                       | 1        | 0.09%   |
| Trust                                        | 1        | 0.09%   |
| RME                                          | 1        | 0.09%   |
| Realtek Semiconductor                        | 1        | 0.09%   |
| Native Instruments                           | 1        | 0.09%   |
| M-Audio                                      | 1        | 0.09%   |
| Generalplus Technology                       | 1        | 0.09%   |
| DSEA A/S                                     | 1        | 0.09%   |
| Corsair                                      | 1        | 0.09%   |
| Blue Microphones                             | 1        | 0.09%   |
| AudioQuest                                   | 1        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Kabini HDMI/DP Audio                                                                          | 92       | 7.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 89       | 6.86%   |
| AMD FCH Azalia Controller                                                                         | 72       | 5.55%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 70       | 5.39%   |
| Intel Jasper Lake HD Audio                                                                        | 68       | 5.24%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 48       | 3.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 46       | 3.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 43       | 3.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 39       | 3%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 32       | 2.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 32       | 2.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 29       | 2.23%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 29       | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 26       | 2%      |
| Intel Cannon Lake PCH cAVS                                                                        | 25       | 1.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 23       | 1.77%   |
| Intel 200 Series PCH HD Audio                                                                     | 22       | 1.69%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 22       | 1.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 22       | 1.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 21       | 1.62%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21       | 1.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 19       | 1.46%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 17       | 1.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16       | 1.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14       | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 14       | 1.08%   |
| Intel 8 Series HD Audio Controller                                                                | 13       | 1%      |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 12       | 0.92%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 12       | 0.92%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12       | 0.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11       | 0.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11       | 0.85%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 10       | 0.77%   |
| Intel Broadwell-U Audio Controller                                                                | 10       | 0.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 10       | 0.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9        | 0.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9        | 0.69%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 8        | 0.62%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 8        | 0.62%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 7        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Samsung Electronics        | 238      | 17.06%  |
| Crucial                    | 203      | 14.55%  |
| Unknown                    | 195      | 13.98%  |
| Kingston                   | 148      | 10.61%  |
| SK hynix                   | 126      | 9.03%   |
| Micron Technology          | 104      | 7.46%   |
| G.Skill                    | 82       | 5.88%   |
| Corsair                    | 63       | 4.52%   |
| Unknown                    | 49       | 3.51%   |
| ATP                        | 22       | 1.58%   |
| Nanya Technology           | 20       | 1.43%   |
| Unknown (ABCD)             | 19       | 1.36%   |
| Transcend                  | 18       | 1.29%   |
| A-DATA Technology          | 14       | 1%      |
| Ramaxel Technology         | 10       | 0.72%   |
| Apacer                     | 10       | 0.72%   |
| Kimtigo                    | 6        | 0.43%   |
| Shenzhen Jinge Information | 5        | 0.36%   |
| Patriot                    | 5        | 0.36%   |
| Hewlett-Packard            | 5        | 0.36%   |
| Wodposit                   | 3        | 0.22%   |
| Elpida                     | 3        | 0.22%   |
| Avant                      | 3        | 0.22%   |
| Unknown (AB)               | 2        | 0.14%   |
| Unknown (89EC)             | 2        | 0.14%   |
| Unknown (09C7)             | 2        | 0.14%   |
| Teikon                     | 2        | 0.14%   |
| SK_Hynix                   | 2        | 0.14%   |
| Mushkin                    | 2        | 0.14%   |
| Lexar Co Limited           | 2        | 0.14%   |
| Innodisk                   | 2        | 0.14%   |
| GeIL                       | 2        | 0.14%   |
| Vasekey                    | 1        | 0.07%   |
| Unknown (8A5D)             | 1        | 0.07%   |
| Unknown (8A02)             | 1        | 0.07%   |
| Unknown (7F7F7F94FFFFFFFF) | 1        | 0.07%   |
| Unknown (0x1636)           | 1        | 0.07%   |
| Unknown (0x0E9D)           | 1        | 0.07%   |
| Unknown (0x0C26)           | 1        | 0.07%   |
| Unknown (0B38)             | 1        | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 58       | 3.94%   |
| Unknown                                                      | 49       | 3.33%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 19       | 1.29%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 19       | 1.29%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 15       | 1.02%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s        | 13       | 0.88%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                   | 12       | 0.82%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 12       | 0.82%   |
| ATP RAM X4G08QA8BNWESO-7-TO1 8GB SODIMM DDR4 3200MT/s        | 11       | 0.75%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 10       | 0.68%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 10       | 0.68%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s           | 10       | 0.68%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s      | 9        | 0.61%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s        | 9        | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 8        | 0.54%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 8        | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 7        | 0.48%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s          | 7        | 0.48%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s         | 7        | 0.48%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s    | 7        | 0.48%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 6        | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                   | 6        | 0.41%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 6        | 0.41%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 6        | 0.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 6        | 0.41%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s        | 6        | 0.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 6        | 0.41%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3200MT/s         | 6        | 0.41%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s          | 6        | 0.41%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s            | 6        | 0.41%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s        | 6        | 0.41%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s        | 6        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 5        | 0.34%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                   | 5        | 0.34%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                  | 5        | 0.34%   |
| Transcend RAM TS512MSK64W6H 4GB DIMM DDR3 1600MT/s           | 5        | 0.34%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 5        | 0.34%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 5        | 0.34%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 5        | 0.34%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 5        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 552      | 43.13%  |
| DDR3    | 534      | 41.72%  |
| DDR2    | 47       | 3.67%   |
| DDR5    | 45       | 3.52%   |
| LPDDR4  | 36       | 2.81%   |
| Unknown | 30       | 2.34%   |
| SDRAM   | 23       | 1.8%    |
| LPDDR5  | 8        | 0.63%   |
| DDR     | 5        | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| SODIMM       | 641      | 50.59%  |
| DIMM         | 593      | 46.8%   |
| Row Of Chips | 24       | 1.89%   |
| Unknown      | 8        | 0.63%   |
| FB-DIMM      | 1        | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 478      | 35.72%  |
| 4096  | 432      | 32.29%  |
| 16384 | 217      | 16.22%  |
| 2048  | 145      | 10.84%  |
| 32768 | 47       | 3.51%   |
| 1024  | 17       | 1.27%   |
| 512   | 2        | 0.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 323      | 24.29%  |
| 2400    | 189      | 14.21%  |
| 1333    | 179      | 13.46%  |
| 3200    | 170      | 12.78%  |
| 2667    | 142      | 10.68%  |
| 2133    | 57       | 4.29%   |
| 800     | 43       | 3.23%   |
| 667     | 40       | 3.01%   |
| 4800    | 39       | 2.93%   |
| Unknown | 24       | 1.8%    |
| 1867    | 21       | 1.58%   |
| 2666    | 18       | 1.35%   |
| 1066    | 14       | 1.05%   |
| 3000    | 13       | 0.98%   |
| 2933    | 10       | 0.75%   |
| 1866    | 9        | 0.68%   |
| 6400    | 8        | 0.6%    |
| 5600    | 5        | 0.38%   |
| 3600    | 5        | 0.38%   |
| 1334    | 4        | 0.3%    |
| 1067    | 4        | 0.3%    |
| 333     | 3        | 0.23%   |
| 533     | 2        | 0.15%   |
| 400     | 2        | 0.15%   |
| 65535   | 1        | 0.08%   |
| 5200    | 1        | 0.08%   |
| 3534    | 1        | 0.08%   |
| 3500    | 1        | 0.08%   |
| 1419    | 1        | 0.08%   |
| 1033    | 1        | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 3        | 50%     |
| Ricoh               | 1        | 16.67%  |
| QinHeng Electronics | 1        | 16.67%  |
| Hewlett-Packard     | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Brother MFC-7360N             | 2        | 33.33%  |
| Ricoh SP 112                  | 1        | 16.67%  |
| QinHeng CH340S                | 1        | 16.67%  |
| HP HP LaserJet P2035 HP Print | 1        | 16.67%  |
| Brother HL-L2310D series      | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 2        | 50%     |
| Canon       | 2        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Desktops | Percent |
|-------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                             | 2        | 50%     |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1        | 25%     |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                 | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 9        | 60%     |
| ARC International             | 2        | 13.33%  |
| Z-Star Microelectronics       | 1        | 6.67%   |
| Trust                         | 1        | 6.67%   |
| Sunplus Innovation Technology | 1        | 6.67%   |
| Chicony Electronics           | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech Webcam C270            | 2        | 13.33%  |
| Logitech C920 PRO HD Webcam     | 2        | 13.33%  |
| Logitech C920 HD Pro Webcam     | 2        | 13.33%  |
| ARC International Camera        | 2        | 13.33%  |
| Z-Star Venus USB2.0 Camera      | 1        | 6.67%   |
| Trust Trust USB Camera          | 1        | 6.67%   |
| Sunplus Integrated_Webcam_HD    | 1        | 6.67%   |
| Logitech HD Webcam C525         | 1        | 6.67%   |
| Logitech HD Pro Webcam C920     | 1        | 6.67%   |
| Logitech C922 Pro Stream Webcam | 1        | 6.67%   |
| Chicony HP HD Webcam [Fixed]    | 1        | 6.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 1        | 100%    |

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
| 1     | 686      | 48.41%  |
| 0     | 524      | 36.98%  |
| 2     | 141      | 9.95%   |
| 3     | 41       | 2.89%   |
| 4     | 15       | 1.06%   |
| 5     | 9        | 0.64%   |
| 6     | 1        | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 778      | 73.74%  |
| Net/wireless             | 88       | 8.34%   |
| Bluetooth                | 77       | 7.3%    |
| Card reader              | 37       | 3.51%   |
| Net/ethernet             | 18       | 1.71%   |
| Firewire controller      | 18       | 1.71%   |
| Network                  | 17       | 1.61%   |
| Sound                    | 11       | 1.04%   |
| Graphics card            | 4        | 0.38%   |
| Storage/raid             | 1        | 0.09%   |
| Storage/ide              | 1        | 0.09%   |
| Storage/ata              | 1        | 0.09%   |
| Storage                  | 1        | 0.09%   |
| Modem                    | 1        | 0.09%   |
| Fingerprint reader       | 1        | 0.09%   |
| Dvb card                 | 1        | 0.09%   |

