BSD in Sweden - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Sweden.

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

Total: 220

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | G11CD                       | [e4d4f0e1b2](https://bsd-hardware.info/?probe=e4d4f0e1b2) | May 06, 2024 |
| Dell          | 0KYJ8C A00                  | [7a7c8ece3a](https://bsd-hardware.info/?probe=7a7c8ece3a) | Apr 27, 2024 |
| Dell          | 0KYJ8C A00                  | [d35fe4f9ef](https://bsd-hardware.info/?probe=d35fe4f9ef) | Apr 27, 2024 |
| Unknown       | Unknown                     | [3f86c9c69d](https://bsd-hardware.info/?probe=3f86c9c69d) | Apr 19, 2024 |
| Unknown       | Unknown                     | [d5529f00e1](https://bsd-hardware.info/?probe=d5529f00e1) | Apr 18, 2024 |
| HP            | 8299                        | [7b4780009e](https://bsd-hardware.info/?probe=7b4780009e) | Apr 16, 2024 |
| PC Engines    | apu4                        | [5ceaa26e0d](https://bsd-hardware.info/?probe=5ceaa26e0d) | Apr 13, 2024 |
| Unknown       | Unknown                     | [d9b9726d99](https://bsd-hardware.info/?probe=d9b9726d99) | Apr 10, 2024 |
| HPE           | ProLiant MicroServer Gen... | [b3d1f4d1bf](https://bsd-hardware.info/?probe=b3d1f4d1bf) | Apr 02, 2024 |
| Dell          | 0YXT71 A02                  | [e5aceb0ceb](https://bsd-hardware.info/?probe=e5aceb0ceb) | Apr 01, 2024 |
| Dell          | 0YXT71 A02                  | [a8cd5867cb](https://bsd-hardware.info/?probe=a8cd5867cb) | Apr 01, 2024 |
| Unknown       | Unknown                     | [147401844b](https://bsd-hardware.info/?probe=147401844b) | Mar 29, 2024 |
| Dell          | 0KYJ8C A00                  | [eb72b3e4b7](https://bsd-hardware.info/?probe=eb72b3e4b7) | Mar 27, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [14a9ddb552](https://bsd-hardware.info/?probe=14a9ddb552) | Mar 25, 2024 |
| Unknown       | Unknown                     | [c95a414132](https://bsd-hardware.info/?probe=c95a414132) | Mar 19, 2024 |
| Unknown       | Unknown                     | [dc2553c7cb](https://bsd-hardware.info/?probe=dc2553c7cb) | Mar 07, 2024 |
| ASRock        | B650 PG Lightning           | [54d6c96d25](https://bsd-hardware.info/?probe=54d6c96d25) | Feb 22, 2024 |
| Unknown       | Unknown                     | [b58cf5585d](https://bsd-hardware.info/?probe=b58cf5585d) | Feb 22, 2024 |
| HP            | 1998                        | [ef11b12f13](https://bsd-hardware.info/?probe=ef11b12f13) | Feb 18, 2024 |
| HP            | 1998                        | [6895f365c7](https://bsd-hardware.info/?probe=6895f365c7) | Feb 14, 2024 |
| Unknown       | Unknown                     | [9c184fe6fa](https://bsd-hardware.info/?probe=9c184fe6fa) | Feb 14, 2024 |
| Dell          | 07WP95 A02                  | [aad51ede2a](https://bsd-hardware.info/?probe=aad51ede2a) | Feb 12, 2024 |
| HP            | 1998                        | [58de92b13d](https://bsd-hardware.info/?probe=58de92b13d) | Feb 11, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [9778043e6f](https://bsd-hardware.info/?probe=9778043e6f) | Feb 08, 2024 |
| PC Engines    | apu4                        | [d0205e7f2b](https://bsd-hardware.info/?probe=d0205e7f2b) | Feb 05, 2024 |
| ASUSTek       | H110I-PLUS                  | [511747dd03](https://bsd-hardware.info/?probe=511747dd03) | Feb 02, 2024 |
| HP            | 8054                        | [4404de3242](https://bsd-hardware.info/?probe=4404de3242) | Jan 31, 2024 |
| Dell          | 0WR7PY A02                  | [f0eb82f1f3](https://bsd-hardware.info/?probe=f0eb82f1f3) | Jan 31, 2024 |
| CWWK          | CW-AD4L-N V1                | [294a66e260](https://bsd-hardware.info/?probe=294a66e260) | Jan 29, 2024 |
| HP            | 8054                        | [5878ff14cf](https://bsd-hardware.info/?probe=5878ff14cf) | Jan 29, 2024 |
| Unknown       | Unknown                     | [9d002ec65c](https://bsd-hardware.info/?probe=9d002ec65c) | Jan 25, 2024 |
| Dell          | 07WP95 A02                  | [76cdddf230](https://bsd-hardware.info/?probe=76cdddf230) | Jan 21, 2024 |
| Unknown       | Unknown                     | [a56d0b3643](https://bsd-hardware.info/?probe=a56d0b3643) | Jan 20, 2024 |
| CWWK          | CW-AD4L-N V1                | [2e9333aba4](https://bsd-hardware.info/?probe=2e9333aba4) | Jan 11, 2024 |
| Unknown       | Unknown                     | [1032d282eb](https://bsd-hardware.info/?probe=1032d282eb) | Jan 03, 2024 |
| PC Engines    | APU2                        | [c0fcb231db](https://bsd-hardware.info/?probe=c0fcb231db) | Dec 30, 2023 |
| Intel         | CRESCENTBAY                 | [412c714b49](https://bsd-hardware.info/?probe=412c714b49) | Dec 27, 2023 |
| PC Engines    | APU3                        | [6c92d4965a](https://bsd-hardware.info/?probe=6c92d4965a) | Dec 16, 2023 |
| Lenovo        | ThinkServer RS140           | [a380879f2f](https://bsd-hardware.info/?probe=a380879f2f) | Dec 11, 2023 |
| Unknown       | YL-J3160L4                  | [cf07751804](https://bsd-hardware.info/?probe=cf07751804) | Dec 09, 2023 |
| PC Engines    | APU2                        | [dbd4df3e5e](https://bsd-hardware.info/?probe=dbd4df3e5e) | Dec 03, 2023 |
| Gigabyte      | P55A-UD3                    | [ec3037a710](https://bsd-hardware.info/?probe=ec3037a710) | Nov 30, 2023 |
| Gigabyte      | P55A-UD3                    | [eec65ee6ce](https://bsd-hardware.info/?probe=eec65ee6ce) | Nov 28, 2023 |
| Unknown       | Unknown                     | [8b2a1299bf](https://bsd-hardware.info/?probe=8b2a1299bf) | Nov 27, 2023 |
| Unknown       | Unknown                     | [b8b5586ead](https://bsd-hardware.info/?probe=b8b5586ead) | Nov 24, 2023 |
| Dell          | 0HD5W2 A01                  | [7d58ae8d97](https://bsd-hardware.info/?probe=7d58ae8d97) | Nov 14, 2023 |
| HP            | 8054                        | [dd3ce5a68d](https://bsd-hardware.info/?probe=dd3ce5a68d) | Nov 12, 2023 |
| HPE           | ProLiant MicroServer Gen... | [8bb2f091fd](https://bsd-hardware.info/?probe=8bb2f091fd) | Nov 09, 2023 |
| Techvision    | TVI7309X B0                 | [c44b69b11e](https://bsd-hardware.info/?probe=c44b69b11e) | Nov 07, 2023 |
| CWWK          | CW-ADLN-6L                  | [59372d06e0](https://bsd-hardware.info/?probe=59372d06e0) | Nov 02, 2023 |
| Techvision    | TVI7309X B0                 | [8004cade7b](https://bsd-hardware.info/?probe=8004cade7b) | Nov 01, 2023 |
| Unknown       | Unknown                     | [119cb746c8](https://bsd-hardware.info/?probe=119cb746c8) | Oct 25, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [b09bb5811b](https://bsd-hardware.info/?probe=b09bb5811b) | Oct 19, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [e96fbf80a4](https://bsd-hardware.info/?probe=e96fbf80a4) | Oct 19, 2023 |
| Gigabyte      | H510M H                     | [3cf75f0ae6](https://bsd-hardware.info/?probe=3cf75f0ae6) | Oct 19, 2023 |
| Intel         | DN2820FYK H24582-201        | [99260d8bdf](https://bsd-hardware.info/?probe=99260d8bdf) | Oct 07, 2023 |
| Intel         | D54250WYK H13922-303        | [1bca98240a](https://bsd-hardware.info/?probe=1bca98240a) | Oct 04, 2023 |
| ASUSTek       | Pro WS W680-ACE IPMI        | [6a98aea3f9](https://bsd-hardware.info/?probe=6a98aea3f9) | Oct 03, 2023 |
| Techvision    | TVI7309X B0                 | [906fd7e198](https://bsd-hardware.info/?probe=906fd7e198) | Sep 30, 2023 |
| Intel         | DN2820FYK H24582-201        | [ea832a672d](https://bsd-hardware.info/?probe=ea832a672d) | Sep 30, 2023 |
| HP            | 8299                        | [fee80cc3e3](https://bsd-hardware.info/?probe=fee80cc3e3) | Sep 23, 2023 |
| PC Engines    | apu6                        | [1a45dd59a4](https://bsd-hardware.info/?probe=1a45dd59a4) | Sep 21, 2023 |
| HP            | 8299                        | [2f1bdffe66](https://bsd-hardware.info/?probe=2f1bdffe66) | Sep 20, 2023 |
| CWWK          | CW-AD4L-N V1                | [cdeddbf4be](https://bsd-hardware.info/?probe=cdeddbf4be) | Sep 17, 2023 |
| Unknown       | Unknown                     | [b95f409ccf](https://bsd-hardware.info/?probe=b95f409ccf) | Sep 05, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | [9e92903663](https://bsd-hardware.info/?probe=9e92903663) | Aug 18, 2023 |
| Intel         | Q3XXG4-P V1.0               | [0836b029bc](https://bsd-hardware.info/?probe=0836b029bc) | Aug 17, 2023 |
| PC Engines    | APU2                        | [d8f32b19ff](https://bsd-hardware.info/?probe=d8f32b19ff) | Aug 14, 2023 |
| HP            | 8299                        | [74c24bcb16](https://bsd-hardware.info/?probe=74c24bcb16) | Jul 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [ce0f05e871](https://bsd-hardware.info/?probe=ce0f05e871) | Jul 18, 2023 |
| MSI           | B350I PRO AC                | [3c4d3b94d0](https://bsd-hardware.info/?probe=3c4d3b94d0) | Jul 14, 2023 |
| MSI           | B350I PRO AC                | [ab56e76e70](https://bsd-hardware.info/?probe=ab56e76e70) | Jul 14, 2023 |
| PC Engines    | APU2                        | [80d79341a8](https://bsd-hardware.info/?probe=80d79341a8) | Jul 05, 2023 |
| ASUSTek       | P5Q DELUXE                  | [0cf9bf6a63](https://bsd-hardware.info/?probe=0cf9bf6a63) | Jul 04, 2023 |
| Unknown       | Unknown                     | [5080e84698](https://bsd-hardware.info/?probe=5080e84698) | Jun 28, 2023 |
| Unknown       | Unknown                     | [c660f668dc](https://bsd-hardware.info/?probe=c660f668dc) | Jun 25, 2023 |
| Unknown       | Unknown                     | [b67ce69ea4](https://bsd-hardware.info/?probe=b67ce69ea4) | Jun 23, 2023 |
| Unknown       | Unknown                     | [6e8085380f](https://bsd-hardware.info/?probe=6e8085380f) | Jun 23, 2023 |
| Unknown       | Unknown                     | [eb49ebcc0c](https://bsd-hardware.info/?probe=eb49ebcc0c) | Jun 22, 2023 |
| Unknown       | Unknown                     | [193c7d152b](https://bsd-hardware.info/?probe=193c7d152b) | Jun 11, 2023 |
| PC Engines    | APU2                        | [f644f33061](https://bsd-hardware.info/?probe=f644f33061) | Jun 07, 2023 |
| Unknown       | Unknown                     | [e80a97aec3](https://bsd-hardware.info/?probe=e80a97aec3) | May 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a0bff43f5c](https://bsd-hardware.info/?probe=a0bff43f5c) | May 23, 2023 |
| Lenovo        | ThinkCentre M81 1730A1G     | [8f59660eca](https://bsd-hardware.info/?probe=8f59660eca) | May 17, 2023 |
| Techvision    | TVI7309X B0                 | [a75ff519b0](https://bsd-hardware.info/?probe=a75ff519b0) | May 15, 2023 |
| CWWK          | MINIPC-G12                  | [4806dc7d9a](https://bsd-hardware.info/?probe=4806dc7d9a) | Apr 29, 2023 |
| AZW           | GK55                        | [31a99b9d2a](https://bsd-hardware.info/?probe=31a99b9d2a) | Apr 25, 2023 |
| Techvision    | TVI7309X B0                 | [a4bc168937](https://bsd-hardware.info/?probe=a4bc168937) | Apr 22, 2023 |
| AZW           | GK55                        | [cc5a32800f](https://bsd-hardware.info/?probe=cc5a32800f) | Apr 14, 2023 |
| HP            | 1998                        | [bc67c37f5f](https://bsd-hardware.info/?probe=bc67c37f5f) | Apr 04, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [ebbd75883c](https://bsd-hardware.info/?probe=ebbd75883c) | Mar 17, 2023 |
| DFI           | CM100-C                     | [c34832095b](https://bsd-hardware.info/?probe=c34832095b) | Mar 15, 2023 |
| Techvision    | TVI7309X B0                 | [23f9004191](https://bsd-hardware.info/?probe=23f9004191) | Mar 13, 2023 |
| AMI           | MNHO-048                    | [ebd90b78c1](https://bsd-hardware.info/?probe=ebd90b78c1) | Mar 12, 2023 |
| AMI           | MNHO-048                    | [52cdeb023e](https://bsd-hardware.info/?probe=52cdeb023e) | Mar 12, 2023 |
| PC Engines    | APU3                        | [c8008161b0](https://bsd-hardware.info/?probe=c8008161b0) | Mar 09, 2023 |
| Unknown       | Unknown                     | [e4b77410c6](https://bsd-hardware.info/?probe=e4b77410c6) | Mar 08, 2023 |
| Dell          | 0WMJ54 A01                  | [31ed952f9c](https://bsd-hardware.info/?probe=31ed952f9c) | Mar 06, 2023 |
| Dell          | 0WMJ54 A01                  | [732a635016](https://bsd-hardware.info/?probe=732a635016) | Mar 06, 2023 |
| Unknown       | Unknown                     | [44ac3b2832](https://bsd-hardware.info/?probe=44ac3b2832) | Feb 13, 2023 |
| HP            | 82A1                        | [2d7d9105f7](https://bsd-hardware.info/?probe=2d7d9105f7) | Jan 13, 2023 |
| Gigabyte      | G31M-ES2C                   | [8353660219](https://bsd-hardware.info/?probe=8353660219) | Jan 08, 2023 |
| ASRock        | E3C226D2I                   | [5dfcf8051d](https://bsd-hardware.info/?probe=5dfcf8051d) | Jan 06, 2023 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | [ac867149f2](https://bsd-hardware.info/?probe=ac867149f2) | Dec 31, 2022 |
| Unknown       | Unknown                     | [b4d44b0018](https://bsd-hardware.info/?probe=b4d44b0018) | Dec 26, 2022 |
| ACMA          | X8SIE                       | [01898b2ffb](https://bsd-hardware.info/?probe=01898b2ffb) | Dec 21, 2022 |
| PC Engines    | APU3                        | [5597cca988](https://bsd-hardware.info/?probe=5597cca988) | Dec 17, 2022 |
| ACMA          | X8SIE                       | [361e4ccc04](https://bsd-hardware.info/?probe=361e4ccc04) | Dec 05, 2022 |
| ACMA          | X8SIE                       | [532b81e55f](https://bsd-hardware.info/?probe=532b81e55f) | Nov 29, 2022 |
| ACMA          | X8SIE                       | [d0112d027b](https://bsd-hardware.info/?probe=d0112d027b) | Nov 28, 2022 |
| Intel         | D54250WYK H13922-303        | [e850e0ae9c](https://bsd-hardware.info/?probe=e850e0ae9c) | Nov 28, 2022 |
| Intel         | CRESCENTBAY                 | [bd1f1fa769](https://bsd-hardware.info/?probe=bd1f1fa769) | Nov 26, 2022 |
| Gigabyte      | G31M-ES2C                   | [2959091a59](https://bsd-hardware.info/?probe=2959091a59) | Nov 25, 2022 |
| Lenovo        | ThinkServer RS140           | [0dd05e08aa](https://bsd-hardware.info/?probe=0dd05e08aa) | Nov 12, 2022 |
| Lenovo        | ThinkServer RS140           | [b2b1509adf](https://bsd-hardware.info/?probe=b2b1509adf) | Nov 11, 2022 |
| MSI           | Z370I GAMING PRO CARBON ... | [dd9f7679b5](https://bsd-hardware.info/?probe=dd9f7679b5) | Nov 09, 2022 |
| Cisco         | ASA5515 A0                  | [7f848d7c57](https://bsd-hardware.info/?probe=7f848d7c57) | Oct 22, 2022 |
| ASUSTek       | P5L-VM 1394                 | [d7c3749eba](https://bsd-hardware.info/?probe=d7c3749eba) | Oct 13, 2022 |
| AOpen         | iBTMx-DS R1.04 55DED10A0... | [a480263c28](https://bsd-hardware.info/?probe=a480263c28) | Aug 26, 2022 |
| Unknown       | Unknown                     | [e5efeb3781](https://bsd-hardware.info/?probe=e5efeb3781) | Aug 24, 2022 |
| Unknown       | Unknown                     | [9d1eb045e5](https://bsd-hardware.info/?probe=9d1eb045e5) | Aug 20, 2022 |
| ASRock        | X399 Taichi                 | [efd9ee1d33](https://bsd-hardware.info/?probe=efd9ee1d33) | Aug 10, 2022 |
| ASUSTek       | CM6731_CM6431_CM6331        | [6e40b41bc3](https://bsd-hardware.info/?probe=6e40b41bc3) | Aug 04, 2022 |
| Gigabyte      | Z87M-D3H                    | [59ae6fc283](https://bsd-hardware.info/?probe=59ae6fc283) | Jul 26, 2022 |
| Supermicro    | X11SSV-M4                   | [444d9ed75e](https://bsd-hardware.info/?probe=444d9ed75e) | Jul 04, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [ea22a644f6](https://bsd-hardware.info/?probe=ea22a644f6) | Jul 04, 2022 |
| PC Engines    | APU                         | [f41e59d78b](https://bsd-hardware.info/?probe=f41e59d78b) | Jun 11, 2022 |
| MSI           | MS-7369                     | [c2c6bd80e8](https://bsd-hardware.info/?probe=c2c6bd80e8) | May 13, 2022 |
| Intel         | CRESCENTBAY                 | [0d11258d3a](https://bsd-hardware.info/?probe=0d11258d3a) | Apr 22, 2022 |
| Shuttle       | SH570                       | [08e2af8890](https://bsd-hardware.info/?probe=08e2af8890) | Apr 16, 2022 |
| Unknown       | Unknown                     | [2e4a7843ab](https://bsd-hardware.info/?probe=2e4a7843ab) | Apr 14, 2022 |
| HPE           | ProLiant MicroServer Gen... | [04e77555a2](https://bsd-hardware.info/?probe=04e77555a2) | Mar 24, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [23055a27d9](https://bsd-hardware.info/?probe=23055a27d9) | Mar 23, 2022 |
| AOpen         | iBTMx-DS R1.04 55DED10A0... | [8faec8e7ed](https://bsd-hardware.info/?probe=8faec8e7ed) | Mar 10, 2022 |
| HPE           | ProLiant MicroServer Gen... | [a2c59d02ee](https://bsd-hardware.info/?probe=a2c59d02ee) | Mar 08, 2022 |
| HPE           | ProLiant MicroServer Gen... | [099edf57ae](https://bsd-hardware.info/?probe=099edf57ae) | Mar 08, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [1daab68f1f](https://bsd-hardware.info/?probe=1daab68f1f) | Mar 04, 2022 |
| HPE           | ProLiant MicroServer Gen... | [8016115ff1](https://bsd-hardware.info/?probe=8016115ff1) | Feb 24, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [807a29112e](https://bsd-hardware.info/?probe=807a29112e) | Feb 19, 2022 |
| Gigabyte      | G31M-ES2C                   | [5f27a360e4](https://bsd-hardware.info/?probe=5f27a360e4) | Feb 10, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | [37cc045649](https://bsd-hardware.info/?probe=37cc045649) | Jan 28, 2022 |
| MSI           | MS-7C56                     | [962ac1c7b0](https://bsd-hardware.info/?probe=962ac1c7b0) | Jan 20, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | [082da3ef7f](https://bsd-hardware.info/?probe=082da3ef7f) | Jan 19, 2022 |
| ASUSTek       | P8H77-I                     | [e15d67e8db](https://bsd-hardware.info/?probe=e15d67e8db) | Jan 08, 2022 |
| ASRock        | E3C226D2I                   | [a31265ae13](https://bsd-hardware.info/?probe=a31265ae13) | Jan 07, 2022 |
| ASUSTek       | P8H77-I                     | [27960088a3](https://bsd-hardware.info/?probe=27960088a3) | Jan 05, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [1684618e22](https://bsd-hardware.info/?probe=1684618e22) | Jan 01, 2022 |
| Lenovo        | ThinkServer RS140           | [e28b542e9e](https://bsd-hardware.info/?probe=e28b542e9e) | Dec 23, 2021 |
| Intel         | DH61AG AAG81491-600         | [fd9659a9fe](https://bsd-hardware.info/?probe=fd9659a9fe) | Dec 15, 2021 |
| ASUSTek       | Rampage Formula             | [34633c2ca8](https://bsd-hardware.info/?probe=34633c2ca8) | Dec 02, 2021 |
| MSI           | MS-7C56                     | [d4e3f14ad4](https://bsd-hardware.info/?probe=d4e3f14ad4) | Nov 23, 2021 |
| AMI           | PEISIA E3845 VER1.0         | [a6b7ceeada](https://bsd-hardware.info/?probe=a6b7ceeada) | Oct 20, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | [4fdd90135a](https://bsd-hardware.info/?probe=4fdd90135a) | Oct 20, 2021 |
| Lenovo        | Win8 Pro DPK TPG            | [f57ea5540f](https://bsd-hardware.info/?probe=f57ea5540f) | Oct 13, 2021 |
| Gigabyte      | Z87M-D3H                    | [8cb8c4dbf4](https://bsd-hardware.info/?probe=8cb8c4dbf4) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [1ef37663db](https://bsd-hardware.info/?probe=1ef37663db) | Sep 01, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [4737978dbf](https://bsd-hardware.info/?probe=4737978dbf) | Aug 18, 2021 |
| HPE           | ProLiant MicroServer Gen... | [04d9692802](https://bsd-hardware.info/?probe=04d9692802) | Aug 09, 2021 |
| HPE           | ProLiant MicroServer Gen... | [24df2da075](https://bsd-hardware.info/?probe=24df2da075) | Aug 08, 2021 |
| PC Engines    | apu4                        | [815567b75c](https://bsd-hardware.info/?probe=815567b75c) | Aug 02, 2021 |
| PC Engines    | apu4                        | [77fa195d5e](https://bsd-hardware.info/?probe=77fa195d5e) | Aug 02, 2021 |
| ASUSTek       | P8H77-I                     | [52e8a39fb1](https://bsd-hardware.info/?probe=52e8a39fb1) | Jul 19, 2021 |
| Protectli     | FW4B Ver                    | [452a8558c0](https://bsd-hardware.info/?probe=452a8558c0) | Jul 09, 2021 |
| Dell          | 05XGC8 A01                  | [b9841b1272](https://bsd-hardware.info/?probe=b9841b1272) | Jul 08, 2021 |
| Unknown       | Unknown                     | [935263c5a0](https://bsd-hardware.info/?probe=935263c5a0) | Jul 03, 2021 |
| HP            | 82A1                        | [dba57fb77f](https://bsd-hardware.info/?probe=dba57fb77f) | Jun 30, 2021 |
| HPE           | ProLiant MicroServer Gen... | [18e34c37cd](https://bsd-hardware.info/?probe=18e34c37cd) | Jun 28, 2021 |
| HPE           | ProLiant MicroServer Gen... | [3d717eec8f](https://bsd-hardware.info/?probe=3d717eec8f) | Jun 25, 2021 |
| Dell          | 0P03DX A03                  | [b2f0c90d79](https://bsd-hardware.info/?probe=b2f0c90d79) | Jun 24, 2021 |
| ASUSTek       | P5Q DELUXE                  | [5091db2ace](https://bsd-hardware.info/?probe=5091db2ace) | Jun 16, 2021 |
| MSI           | Z97 GAMING 3                | [c6d7626b29](https://bsd-hardware.info/?probe=c6d7626b29) | Jun 12, 2021 |
| ASRock        | X99 WS                      | [201a7417a5](https://bsd-hardware.info/?probe=201a7417a5) | Jun 11, 2021 |
| PC Engines    | APU2                        | [2070f50252](https://bsd-hardware.info/?probe=2070f50252) | May 26, 2021 |
| ASUSTek       | Z87-DELUXE/DUAL             | [69a811cae5](https://bsd-hardware.info/?probe=69a811cae5) | May 25, 2021 |
| ASUSTek       | SABERTOOTH Z87              | [586a4db247](https://bsd-hardware.info/?probe=586a4db247) | May 20, 2021 |
| ASUSTek       | SABERTOOTH Z87              | [eb0c02a451](https://bsd-hardware.info/?probe=eb0c02a451) | May 19, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [62b9ea2794](https://bsd-hardware.info/?probe=62b9ea2794) | May 14, 2021 |
| ASRock        | X99 WS                      | [eb20367455](https://bsd-hardware.info/?probe=eb20367455) | May 05, 2021 |
| ASUSTek       | All Series                  | [ef6afe88d7](https://bsd-hardware.info/?probe=ef6afe88d7) | Apr 17, 2021 |
| Unknown       | YL-J3160L4                  | [ad564817c9](https://bsd-hardware.info/?probe=ad564817c9) | Apr 11, 2021 |
| Unknown       | YL-J3160L4                  | [0712c3048c](https://bsd-hardware.info/?probe=0712c3048c) | Apr 11, 2021 |
| Shuttle       | FH170                       | [d36fccf7b7](https://bsd-hardware.info/?probe=d36fccf7b7) | Apr 01, 2021 |
| MSI           | IONA                        | [5f857882ff](https://bsd-hardware.info/?probe=5f857882ff) | Mar 25, 2021 |
| Unknown       | Unknown                     | [93ef7a4b6e](https://bsd-hardware.info/?probe=93ef7a4b6e) | Mar 22, 2021 |
| ASUSTek       | All Series                  | [c5bc64e4e9](https://bsd-hardware.info/?probe=c5bc64e4e9) | Mar 22, 2021 |
| ASUSTek       | All Series                  | [700ff7d378](https://bsd-hardware.info/?probe=700ff7d378) | Mar 22, 2021 |
| HP            | 8054                        | [1db522699a](https://bsd-hardware.info/?probe=1db522699a) | Mar 21, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [ddc66bc2fb](https://bsd-hardware.info/?probe=ddc66bc2fb) | Mar 20, 2021 |
| Gigabyte      | 970A-DS3P                   | [a5833ca2c9](https://bsd-hardware.info/?probe=a5833ca2c9) | Mar 18, 2021 |
| HP            | 8053                        | [b7ebdfe456](https://bsd-hardware.info/?probe=b7ebdfe456) | Mar 17, 2021 |
| ASUSTek       | P8H67-M                     | [e95d6c6972](https://bsd-hardware.info/?probe=e95d6c6972) | Mar 17, 2021 |
| ADI           | MinnowBoard Turbot          | [ebd85cee04](https://bsd-hardware.info/?probe=ebd85cee04) | Mar 14, 2021 |
| Intel         | Q3XXG4-P V1.0               | [93c9f14bf0](https://bsd-hardware.info/?probe=93c9f14bf0) | Mar 12, 2021 |
| Dell          | 0XCR8D A02                  | [af5d6a85ef](https://bsd-hardware.info/?probe=af5d6a85ef) | Mar 09, 2021 |
| Dell          | 00V62H A00                  | [a9f921e29b](https://bsd-hardware.info/?probe=a9f921e29b) | Mar 03, 2021 |
| Intel         | DQ67SW AAG12527-306         | [a4fb7ae326](https://bsd-hardware.info/?probe=a4fb7ae326) | Mar 02, 2021 |
| Unknown       | Unknown                     | [b00dc0301a](https://bsd-hardware.info/?probe=b00dc0301a) | Feb 27, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [da62664934](https://bsd-hardware.info/?probe=da62664934) | Feb 23, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [5ca10a4860](https://bsd-hardware.info/?probe=5ca10a4860) | Feb 14, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [263a74d1ce](https://bsd-hardware.info/?probe=263a74d1ce) | Feb 12, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [508b3afc1c](https://bsd-hardware.info/?probe=508b3afc1c) | Feb 09, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [8b9f162f70](https://bsd-hardware.info/?probe=8b9f162f70) | Feb 09, 2021 |
| Deciso        | Netboard A10 V2.1           | [dfb0240726](https://bsd-hardware.info/?probe=dfb0240726) | Feb 05, 2021 |
| PC Engines    | APU2                        | [8983ab6689](https://bsd-hardware.info/?probe=8983ab6689) | Feb 03, 2021 |
| HP            | 1905                        | [72ab5653d3](https://bsd-hardware.info/?probe=72ab5653d3) | Feb 03, 2021 |
| ADI           | MinnowBoard Turbot          | [137ff14192](https://bsd-hardware.info/?probe=137ff14192) | Jan 29, 2021 |
| Unknown       | Unknown                     | [920259bf95](https://bsd-hardware.info/?probe=920259bf95) | Jan 28, 2021 |
| ASUSTek       | All Series                  | [7ebe6eee38](https://bsd-hardware.info/?probe=7ebe6eee38) | Jan 25, 2021 |
| ADI           | MinnowBoard Turbot          | [e2fbc5f326](https://bsd-hardware.info/?probe=e2fbc5f326) | Jan 21, 2021 |
| ADI           | MinnowBoard Turbot          | [0b8e4d0630](https://bsd-hardware.info/?probe=0b8e4d0630) | Jan 21, 2021 |
| Dell          | 00V62H A00                  | [bd3877826c](https://bsd-hardware.info/?probe=bd3877826c) | Jan 20, 2021 |
| PC Engines    | APU2                        | [ecf35d22c4](https://bsd-hardware.info/?probe=ecf35d22c4) | Jan 12, 2021 |
| PC Engines    | APU2                        | [2e6256a0ab](https://bsd-hardware.info/?probe=2e6256a0ab) | Nov 23, 2020 |
| PC Engines    | APU2                        | [65de6946d3](https://bsd-hardware.info/?probe=65de6946d3) | Nov 23, 2020 |
| PC Engines    | APU2                        | [b4f5d7d344](https://bsd-hardware.info/?probe=b4f5d7d344) | Nov 16, 2020 |
| HP            | ProLiant ML30 Gen9          | [ecaec68cdb](https://bsd-hardware.info/?probe=ecaec68cdb) | Oct 27, 2020 |
| Wistron       | ProLiant ML110 G6           | [0d2e0f44c1](https://bsd-hardware.info/?probe=0d2e0f44c1) | Aug 06, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [6245f1e175](https://bsd-hardware.info/?probe=6245f1e175) | Aug 06, 2020 |
| Unknown       | Unknown                     | [4e3b87cc6c](https://bsd-hardware.info/?probe=4e3b87cc6c) | Jun 01, 2020 |
| Gigabyte      | Z170X-UD5 TH-CF             | [2fc2952380](https://bsd-hardware.info/?probe=2fc2952380) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OPNsense 21.1     | 8        | 4.55%   |
| OPNsense 23.7.9   | 6        | 3.41%   |
| OPNsense 24.1.4   | 5        | 2.84%   |
| OPNsense 21.1.3   | 5        | 2.84%   |
| OPNsense 21.1.2   | 5        | 2.84%   |
| OPNsense 24.1.1   | 4        | 2.27%   |
| OPNsense 24.1     | 4        | 2.27%   |
| OPNsense 23.7.7   | 4        | 2.27%   |
| OPNsense 23.7.12  | 4        | 2.27%   |
| OPNsense 23.7.10  | 4        | 2.27%   |
| OPNsense 23.1.11  | 4        | 2.27%   |
| OPNsense 22.7.8   | 4        | 2.27%   |
| OPNsense 22.7.10  | 4        | 2.27%   |
| OPNsense 21.7.7   | 4        | 2.27%   |
| OPNsense 24.1.5   | 3        | 1.7%    |
| OPNsense 23.7.6   | 3        | 1.7%    |
| OPNsense 23.7.5   | 3        | 1.7%    |
| OPNsense 23.7.4   | 3        | 1.7%    |
| OPNsense 23.1.6   | 3        | 1.7%    |
| OPNsense 23.1.3   | 3        | 1.7%    |
| OPNsense 23.1.10  | 3        | 1.7%    |
| OPNsense 22.7.2   | 3        | 1.7%    |
| OPNsense 21.7.3   | 3        | 1.7%    |
| OPNsense 21.1.8   | 3        | 1.7%    |
| OPNsense 21.1.5   | 3        | 1.7%    |
| OpenBSD 6.8       | 3        | 1.7%    |
| OPNsense 24.1.6   | 2        | 1.14%   |
| OPNsense 23.7.8   | 2        | 1.14%   |
| OPNsense 23.1.7   | 2        | 1.14%   |
| OPNsense 23.1.2   | 2        | 1.14%   |
| OPNsense 22.7.9   | 2        | 1.14%   |
| OPNsense 22.7.6   | 2        | 1.14%   |
| OPNsense 22.1.9   | 2        | 1.14%   |
| OPNsense 22.1.3   | 2        | 1.14%   |
| OPNsense 21.7.6   | 2        | 1.14%   |
| OPNsense 21.7.1   | 2        | 1.14%   |
| OPNsense 21.7     | 2        | 1.14%   |
| OPNsense 21.1.7   | 2        | 1.14%   |
| OPNsense 20.7.8   | 2        | 1.14%   |
| helloSystem 0.8.1 | 2        | 1.14%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 108      | 77.7%   |
| FreeBSD     | 19       | 13.67%  |
| OpenBSD     | 5        | 3.6%    |
| helloSystem | 4        | 2.88%   |
| pfSense     | 1        | 0.72%   |
| GhostBSD    | 1        | 0.72%   |
| FuryBSD     | 1        | 0.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 138      | 99.28%  |
| octeon | 1        | 0.72%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 116      | 82.86%  |
| KDE5         | 10       | 7.14%   |
| helloDesktop | 4        | 2.86%   |
| fvwm         | 3        | 2.14%   |
| MATE         | 2        | 1.43%   |
| xfwm         | 1        | 0.71%   |
| XFCE         | 1        | 0.71%   |
| TWM          | 1        | 0.71%   |
| GNOME        | 1        | 0.71%   |
| AwesomeWM    | 1        | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 116      | 83.45%  |
| X11     | 23       | 16.55%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 120      | 84.51%  |
| SDDM    | 11       | 7.75%   |
| SLiM    | 4        | 2.82%   |
| LightDM | 3        | 2.11%   |
| XDM     | 2        | 1.41%   |
| GDM     | 2        | 1.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 115      | 80.99%  |
| C              | 12       | 8.45%   |
| en_US          | 10       | 7.04%   |
| sv_SE          | 3        | 2.11%   |
| sv_SE.US-ASCII | 1        | 0.7%    |
| en_CA          | 1        | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 121      | 86.43%  |
| BIOS | 19       | 13.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 79       | 56.03%  |
| Zfs    | 55       | 39.01%  |
| Ffs    | 5        | 3.55%   |
| Cd9660 | 2        | 1.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 128      | 91.43%  |
| MBR     | 9        | 6.43%   |
| Unknown | 3        | 2.14%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 22       | 15.83%  |
| ASUSTek Computer           | 16       | 11.51%  |
| PC Engines                 | 15       | 10.79%  |
| Dell                       | 11       | 7.91%   |
| Intel                      | 10       | 7.19%   |
| Hewlett-Packard            | 10       | 7.19%   |
| Gigabyte Technology        | 9        | 6.47%   |
| MSI                        | 7        | 5.04%   |
| Lenovo                     | 7        | 5.04%   |
| CWWK                       | 4        | 2.88%   |
| ASRock                     | 4        | 2.88%   |
| Techvision                 | 3        | 2.16%   |
| Fujitsu                    | 3        | 2.16%   |
| Shuttle                    | 2        | 1.44%   |
| AMI                        | 2        | 1.44%   |
| Wistron                    | 1        | 0.72%   |
| Supermicro                 | 1        | 0.72%   |
| ShenZhen MinWin Technology | 1        | 0.72%   |
| Protectli                  | 1        | 0.72%   |
| HPE                        | 1        | 0.72%   |
| Fujitsu Siemens            | 1        | 0.72%   |
| DFI                        | 1        | 0.72%   |
| Deciso                     | 1        | 0.72%   |
| Cisco                      | 1        | 0.72%   |
| AZW                        | 1        | 0.72%   |
| Apple                      | 1        | 0.72%   |
| AOpen                      | 1        | 0.72%   |
| ADI                        | 1        | 0.72%   |
| ACMA                       | 1        | 0.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Unknown                                | 22       | 15.83%  |
| PC Engines APU2                        | 7        | 5.04%   |
| PC Engines apu4                        | 4        | 2.88%   |
| Techvision TVI7309X                    | 3        | 2.16%   |
| Intel CRESCENTBAY                      | 3        | 2.16%   |
| HP EliteDesk 800 G2 SFF                | 3        | 2.16%   |
| ASUS All Series                        | 3        | 2.16%   |
| PC Engines APU3                        | 2        | 1.44%   |
| Intel Q3XXG4-P V1.0                    | 2        | 1.44%   |
| Intel D54250WYK H13922-303             | 2        | 1.44%   |
| HP EliteDesk 800 G1 SFF                | 2        | 1.44%   |
| Dell OptiPlex 9020                     | 2        | 1.44%   |
| Dell OptiPlex 7060                     | 2        | 1.44%   |
| Dell OptiPlex 7010                     | 2        | 1.44%   |
| CWWK CW-AD4L-N V1                      | 2        | 1.44%   |
| Wistron ProLiant ML110 G6              | 1        | 0.72%   |
| Supermicro SYS-1019S-MP                | 1        | 0.72%   |
| Shuttle SH570                          | 1        | 0.72%   |
| Shuttle DH170                          | 1        | 0.72%   |
| ShenZhen MinWin MW-NANO-APL-4L         | 1        | 0.72%   |
| Protectli FW4B                         | 1        | 0.72%   |
| PC Engines apu6                        | 1        | 0.72%   |
| PC Engines APU                         | 1        | 0.72%   |
| MSI WC776AA-UUW HPE-110sc              | 1        | 0.72%   |
| MSI MS-7C56                            | 1        | 0.72%   |
| MSI MS-7B85                            | 1        | 0.72%   |
| MSI MS-7B43                            | 1        | 0.72%   |
| MSI MS-7A40                            | 1        | 0.72%   |
| MSI MS-7918                            | 1        | 0.72%   |
| MSI MS-7369                            | 1        | 0.72%   |
| Lenovo ThinkCentre M92p 2988B1G        | 1        | 0.72%   |
| Lenovo ThinkCentre M81 1730A1G         | 1        | 0.72%   |
| Lenovo ThinkCentre M700 10GRCTO1WW     | 1        | 0.72%   |
| Lenovo ThinkCentre Edge72 3493AZG      | 1        | 0.72%   |
| Lenovo ThinkCentre E73 10AS002QMX      | 1        | 0.72%   |
| Lenovo IdeaCentre 300-20ISH 90DA00HEMT | 1        | 0.72%   |
| Lenovo 70F3S00K00 ThinkServer RS140    | 1        | 0.72%   |
| Intel DQ67SW AAG12527-306              | 1        | 0.72%   |
| Intel DN2820FYK H24582-201             | 1        | 0.72%   |
| Intel DH61AG AAG81491-600              | 1        | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 22       | 15.83%  |
| Dell OptiPlex                  | 11       | 7.91%   |
| PC Engines APU2                | 7        | 5.04%   |
| HP EliteDesk                   | 7        | 5.04%   |
| Lenovo ThinkCentre             | 5        | 3.6%    |
| PC Engines apu4                | 4        | 2.88%   |
| Techvision TVI7309X            | 3        | 2.16%   |
| Intel CRESCENTBAY              | 3        | 2.16%   |
| ASUS All                       | 3        | 2.16%   |
| PC Engines APU3                | 2        | 1.44%   |
| Intel Q3XXG4-P                 | 2        | 1.44%   |
| Intel D54250WYK                | 2        | 1.44%   |
| Fujitsu ESPRIMO                | 2        | 1.44%   |
| CWWK CW-AD4L-N                 | 2        | 1.44%   |
| ASUS ROG                       | 2        | 1.44%   |
| Wistron ProLiant               | 1        | 0.72%   |
| Supermicro SYS-1019S-MP        | 1        | 0.72%   |
| Shuttle SH570                  | 1        | 0.72%   |
| Shuttle DH170                  | 1        | 0.72%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 0.72%   |
| Protectli FW4B                 | 1        | 0.72%   |
| PC Engines apu6                | 1        | 0.72%   |
| PC Engines APU                 | 1        | 0.72%   |
| MSI WC776AA-UUW                | 1        | 0.72%   |
| MSI MS-7C56                    | 1        | 0.72%   |
| MSI MS-7B85                    | 1        | 0.72%   |
| MSI MS-7B43                    | 1        | 0.72%   |
| MSI MS-7A40                    | 1        | 0.72%   |
| MSI MS-7918                    | 1        | 0.72%   |
| MSI MS-7369                    | 1        | 0.72%   |
| Lenovo IdeaCentre              | 1        | 0.72%   |
| Lenovo 70F3S00K00              | 1        | 0.72%   |
| Intel DQ67SW                   | 1        | 0.72%   |
| Intel DN2820FYK                | 1        | 0.72%   |
| Intel DH61AG                   | 1        | 0.72%   |
| HPE ProLiant                   | 1        | 0.72%   |
| HP Z230                        | 1        | 0.72%   |
| HP ProLiant                    | 1        | 0.72%   |
| HP ProDesk                     | 1        | 0.72%   |
| Gigabyte Z87M-D3H              | 1        | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2016    | 19       | 13.67%  |
| 2023    | 14       | 10.07%  |
| 2022    | 14       | 10.07%  |
| 2017    | 13       | 9.35%   |
| 2014    | 12       | 8.63%   |
| 2018    | 11       | 7.91%   |
| 2021    | 9        | 6.47%   |
| 2019    | 9        | 6.47%   |
| 2020    | 8        | 5.76%   |
| 2013    | 7        | 5.04%   |
| 2010    | 6        | 4.32%   |
| 2015    | 5        | 3.6%    |
| 2012    | 5        | 3.6%    |
| 2009    | 3        | 2.16%   |
| 2011    | 1        | 0.72%   |
| 2008    | 1        | 0.72%   |
| 2006    | 1        | 0.72%   |
| Unknown | 1        | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 139      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 123      | 88.49%  |
| Yes  | 16       | 11.51%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 51       | 35.92%  |
| 16.01-24.0  | 32       | 22.54%  |
| 4.01-8.0    | 30       | 21.13%  |
| 32.01-64.0  | 16       | 11.27%  |
| 64.01-256.0 | 5        | 3.52%   |
| 2.01-3.0    | 4        | 2.82%   |
| 24.01-32.0  | 3        | 2.11%   |
| 1.01-2.0    | 1        | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 70       | 48.61%  |
| 0.51-1.0   | 49       | 34.03%  |
| 1.01-2.0   | 14       | 9.72%   |
| 4.01-8.0   | 4        | 2.78%   |
| 2.01-3.0   | 3        | 2.08%   |
| 3.01-4.0   | 2        | 1.39%   |
| 32.01-64.0 | 1        | 0.69%   |
| 24.01-32.0 | 1        | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 95       | 66.43%  |
| 2      | 15       | 10.49%  |
| 0      | 11       | 7.69%   |
| 3      | 10       | 6.99%   |
| 6      | 4        | 2.8%    |
| 4      | 4        | 2.8%    |
| 12     | 1        | 0.7%    |
| 10     | 1        | 0.7%    |
| 9      | 1        | 0.7%    |
| 8      | 1        | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 121      | 86.43%  |
| Yes       | 19       | 13.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 138      | 99.28%  |
| No        | 1        | 0.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 119      | 85%     |
| Yes       | 21       | 15%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 121      | 87.05%  |
| Yes       | 18       | 12.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Sweden  | 139      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Stockholm             | 28       | 17.39%  |
| Malmo                 | 8        | 4.97%   |
| Västerås            | 6        | 3.73%   |
| Gothenburg            | 6        | 3.73%   |
| Bromma                | 6        | 3.73%   |
| Umeå                 | 3        | 1.86%   |
| Taby                  | 3        | 1.86%   |
| Skövde               | 3        | 1.86%   |
| Piteå                | 3        | 1.86%   |
| Lund                  | 3        | 1.86%   |
| Linköping            | 3        | 1.86%   |
| Gävle                | 3        | 1.86%   |
| VÃ¤sterÃ¥s        | 2        | 1.24%   |
| Uppsala               | 2        | 1.24%   |
| Upplands Vasby        | 2        | 1.24%   |
| UmeГҐ               | 2        | 1.24%   |
| Tumba                 | 2        | 1.24%   |
| Straengnaes           | 2        | 1.24%   |
| Sollentuna            | 2        | 1.24%   |
| Solleftea             | 2        | 1.24%   |
| LinkГ¶ping          | 2        | 1.24%   |
| Landskrona            | 2        | 1.24%   |
| Karlskrona            | 2        | 1.24%   |
| JГ¶nkГ¶ping       | 2        | 1.24%   |
| Helsingborg           | 2        | 1.24%   |
| Enskede-Arsta-Vantoer | 2        | 1.24%   |
| Bandhagen             | 2        | 1.24%   |
| Г…hus              | 1        | 0.62%   |
| Г„lvГ¤ngen       | 1        | 0.62%   |
| Vaxjo                 | 1        | 0.62%   |
| Vallingby             | 1        | 0.62%   |
| Vallentuna            | 1        | 0.62%   |
| UmeÃ¥               | 1        | 0.62%   |
| Ulricehamn            | 1        | 0.62%   |
| Tyreso Strand         | 1        | 0.62%   |
| Trelleborg            | 1        | 0.62%   |
| Trangsund             | 1        | 0.62%   |
| Torsby                | 1        | 0.62%   |
| SГ¶dertГ¤lje      | 1        | 0.62%   |
| Svanesund             | 1        | 0.62%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 30       | 43     | 16.95%  |
| Kingston            | 22       | 32     | 12.43%  |
| Seagate             | 19       | 43     | 10.73%  |
| WDC                 | 18       | 29     | 10.17%  |
| Hoodisk             | 15       | 24     | 8.47%   |
| Intel               | 14       | 19     | 7.91%   |
| Crucial             | 8        | 17     | 4.52%   |
| Toshiba             | 7        | 16     | 3.95%   |
| Phison              | 5        | 5      | 2.82%   |
| SanDisk             | 4        | 6      | 2.26%   |
| LITEON              | 4        | 10     | 2.26%   |
| China               | 3        | 3      | 1.69%   |
| Transcend           | 2        | 2      | 1.13%   |
| OCZ                 | 2        | 4      | 1.13%   |
| NVMe                | 2        | 3      | 1.13%   |
| Innodisk            | 2        | 3      | 1.13%   |
| Hitachi             | 2        | 2      | 1.13%   |
| Corsair             | 2        | 2      | 1.13%   |
| Apple               | 2        | 3      | 1.13%   |
| Apacer              | 2        | 2      | 1.13%   |
| XrayDisk            | 1        | 1      | 0.56%   |
| Supermicro          | 1        | 1      | 0.56%   |
| SK hynix            | 1        | 1      | 0.56%   |
| Silicon Motion      | 1        | 1      | 0.56%   |
| PNY                 | 1        | 1      | 0.56%   |
| LITEONIT            | 1        | 1      | 0.56%   |
| KingSpec            | 1        | 1      | 0.56%   |
| Kimtigo             | 1        | 1      | 0.56%   |
| Fordisk             | 1        | 1      | 0.56%   |
| faspeed             | 1        | 1      | 0.56%   |
| Fanxiang            | 1        | 2      | 0.56%   |
| A-DATA Technology   | 1        | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| Hoodisk SSD 16GB               | 5        | 2.51%   |
| Hoodisk SSD 64GB               | 4        | 2.01%   |
| Hoodisk SSD 128GB              | 4        | 2.01%   |
| Samsung SSD 860 QVO 1TB        | 3        | 1.51%   |
| Phison YSO128GTLCW-E3C-2 128GB | 3        | 1.51%   |
| Kingston SA400S37240G 240GB    | 3        | 1.51%   |
| Intel SSDSC2BW240A4 240GB      | 3        | 1.51%   |
| WDC WD5000AZLX-60K2TA0 500GB   | 2        | 1.01%   |
| Toshiba HDWR11A 10TB           | 2        | 1.01%   |
| Toshiba HDWQ140 4TB            | 2        | 1.01%   |
| Toshiba DT01ACA100 1TB         | 2        | 1.01%   |
| Seagate ST4000DM004-2CV104 4TB | 2        | 1.01%   |
| Seagate ST2000DM008-2FR102 2TB | 2        | 1.01%   |
| Seagate ST1000DM010-2EP102 1TB | 2        | 1.01%   |
| Samsung SSD 970 EVO Plus 500GB | 2        | 1.01%   |
| Samsung SSD 970 EVO 500GB      | 2        | 1.01%   |
| Samsung SSD 850 EVO 1TB        | 2        | 1.01%   |
| Samsung HD501LJ 500GB          | 2        | 1.01%   |
| Phison SATA SSD 16GB           | 2        | 1.01%   |
| OCZ AGILITY3 120GB             | 2        | 1.01%   |
| Kingston SV300S37A240G 240GB   | 2        | 1.01%   |
| Kingston SKC600MS256G 256GB    | 2        | 1.01%   |
| Kingston SKC600512G 512GB      | 2        | 1.01%   |
| Kingston SA2000M8250G 250GB    | 2        | 1.01%   |
| Intel SSDSC2CT060A3 64GB       | 2        | 1.01%   |
| Crucial CT256MX100SSD1 256GB   | 2        | 1.01%   |
| China SATA SSD 16GB            | 2        | 1.01%   |
| Apacer 64GB SATA Flash Drive   | 2        | 1.01%   |
| XrayDisk SSD 64GB              | 1        | 0.5%    |
| WDC WDS500G3X0C-00SJG0 500GB   | 1        | 0.5%    |
| WDC WDS250G2B0C-00PXH0 250GB   | 1        | 0.5%    |
| WDC WDS250G2B0A-00SM50 250GB   | 1        | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB   | 1        | 0.5%    |
| WDC WDS120G1G0A-00SS50 120GB   | 1        | 0.5%    |
| WDC WD82PURZ-85TEUY0 8TB       | 1        | 0.5%    |
| WDC WD80EZAZ-11TDBA0 8TB       | 1        | 0.5%    |
| WDC WD6400AARS-00Y5B1 640GB    | 1        | 0.5%    |
| WDC WD5000AAKS-07V0A0 500GB    | 1        | 0.5%    |
| WDC WD5000AACS-00ZUB0 500GB    | 1        | 0.5%    |
| WDC WD40EZRZ-22GXCB0 4TB       | 1        | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 40     | 36.96%  |
| WDC                 | 13       | 22     | 28.26%  |
| Toshiba             | 7        | 16     | 15.22%  |
| Samsung Electronics | 5        | 7      | 10.87%  |
| Hitachi             | 2        | 2      | 4.35%   |
| NVMe                | 1        | 2      | 2.17%   |
| Apple               | 1        | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 20       | 29     | 18.69%  |
| Samsung Electronics | 19       | 25     | 17.76%  |
| Hoodisk             | 15       | 24     | 14.02%  |
| Intel               | 12       | 17     | 11.21%  |
| Crucial             | 6        | 15     | 5.61%   |
| SanDisk             | 4        | 6      | 3.74%   |
| LITEON              | 4        | 10     | 3.74%   |
| WDC                 | 3        | 5      | 2.8%    |
| China               | 3        | 3      | 2.8%    |
| Transcend           | 2        | 2      | 1.87%   |
| Phison              | 2        | 2      | 1.87%   |
| OCZ                 | 2        | 4      | 1.87%   |
| Innodisk            | 2        | 3      | 1.87%   |
| Apacer              | 2        | 2      | 1.87%   |
| XrayDisk            | 1        | 1      | 0.93%   |
| Supermicro          | 1        | 1      | 0.93%   |
| SK hynix            | 1        | 1      | 0.93%   |
| Seagate             | 1        | 1      | 0.93%   |
| PNY                 | 1        | 1      | 0.93%   |
| NVMe                | 1        | 1      | 0.93%   |
| LITEONIT            | 1        | 1      | 0.93%   |
| KingSpec            | 1        | 1      | 0.93%   |
| Fordisk             | 1        | 1      | 0.93%   |
| Corsair             | 1        | 1      | 0.93%   |
| Apple               | 1        | 2      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 91       | 159    | 60.26%  |
| HDD  | 33       | 90     | 21.85%  |
| NVMe | 27       | 32     | 17.88%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 109      | 249    | 80.15%  |
| NVMe | 27       | 32     | 19.85%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 97       | 164    | 67.83%  |
| 0.51-1.0   | 22       | 33     | 15.38%  |
| 1.01-2.0   | 10       | 17     | 6.99%   |
| 3.01-4.0   | 9        | 20     | 6.29%   |
| 4.01-10.0  | 5        | 15     | 3.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 63       | 44.37%  |
| 251-500        | 21       | 14.79%  |
| 1-20           | 18       | 12.68%  |
| 21-50          | 15       | 10.56%  |
| 51-100         | 11       | 7.75%   |
| 501-1000       | 8        | 5.63%   |
| 1001-2000      | 4        | 2.82%   |
| More than 3000 | 2        | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 123      | 84.83%  |
| 21-50          | 14       | 9.66%   |
| 251-500        | 2        | 1.38%   |
| 101-250        | 2        | 1.38%   |
| 51-100         | 2        | 1.38%   |
| More than 3000 | 1        | 0.69%   |
| 1001-2000      | 1        | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST1000DM010-2EP102 1TB        | 2        | 3      | 7.69%   |
| WDC WD6400AARS-00Y5B1 640GB           | 1        | 1      | 3.85%   |
| WDC WD40EFRX-68N32N0 4TB              | 1        | 2      | 3.85%   |
| WDC WD2500AAJS-60B4A0 250GB           | 1        | 2      | 3.85%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 2      | 3.85%   |
| WDC WD20EARX-00ZUDB0 2TB              | 1        | 1      | 3.85%   |
| WDC WD2002FYPS-02W3B0 2TB             | 1        | 1      | 3.85%   |
| WDC WD15EARS-00Z5B1 1.5TB             | 1        | 1      | 3.85%   |
| WDC WD15EARS-00MVWB0 1.5TB            | 1        | 1      | 3.85%   |
| SK hynix HFS128G32MND-2200A 128GB     | 1        | 1      | 3.85%   |
| Seagate ST9320423AS 320GB             | 1        | 1      | 3.85%   |
| Seagate ST9320421AS 320GB             | 1        | 1      | 3.85%   |
| Seagate ST8000AS0002-1NA17Z 8TB       | 1        | 1      | 3.85%   |
| Seagate ST2000DM008-2FR102 2TB        | 1        | 1      | 3.85%   |
| Seagate ST100FN0021 100GB             | 1        | 1      | 3.85%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 3.85%   |
| Samsung Electronics HM250JI 250GB     | 1        | 1      | 3.85%   |
| Samsung Electronics HD321KJ 320GB     | 1        | 1      | 3.85%   |
| OCZ AGILITY3 120GB                    | 1        | 2      | 3.85%   |
| Kingston SV300S37A120G 120GB          | 1        | 1      | 3.85%   |
| Intel SSDSC2CT120A3 120GB             | 1        | 1      | 3.85%   |
| Intel SSDSC2CT060A3 64GB              | 1        | 2      | 3.85%   |
| Intel SSDSC2BF180A4H 180GB            | 1        | 1      | 3.85%   |
| Intel SSDSC2BA400G4 400GB             | 1        | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 9      | 28.57%  |
| WDC                 | 5        | 11     | 23.81%  |
| Intel               | 4        | 5      | 19.05%  |
| Samsung Electronics | 3        | 3      | 14.29%  |
| SK hynix            | 1        | 1      | 4.76%   |
| OCZ                 | 1        | 2      | 4.76%   |
| Kingston            | 1        | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 11     | 41.67%  |
| Seagate             | 5        | 8      | 41.67%  |
| Samsung Electronics | 2        | 2      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 21     | 52.63%  |
| SSD  | 8        | 10     | 42.11%  |
| NVMe | 1        | 1      | 5.26%   |

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
| Works    | 120      | 240    | 82.76%  |
| Malfunc  | 19       | 32     | 13.1%   |
| Detected | 6        | 9      | 4.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 101      | 57.39%  |
| AMD                           | 30       | 17.05%  |
| Samsung Electronics           | 12       | 6.82%   |
| Silicon Motion                | 4        | 2.27%   |
| Phison Electronics            | 4        | 2.27%   |
| ASMedia Technology            | 4        | 2.27%   |
| Marvell Technology Group      | 3        | 1.7%    |
| Kingston Technology Company   | 3        | 1.7%    |
| Broadcom / LSI                | 3        | 1.7%    |
| Seagate Technology            | 2        | 1.14%   |
| SanDisk                       | 2        | 1.14%   |
| Micron/Crucial Technology     | 2        | 1.14%   |
| VIA Technologies              | 1        | 0.57%   |
| Nvidia                        | 1        | 0.57%   |
| Integrated Technology Express | 1        | 0.57%   |
| ADATA Technology              | 1        | 0.57%   |
| Adaptec                       | 1        | 0.57%   |
| 3ware                         | 1        | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 22       | 11.17%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 15       | 7.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10       | 5.08%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 8        | 4.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 3.05%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 3.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 2.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5        | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 2.54%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 4        | 2.03%   |
| Intel unknown                                                                           | 4        | 2.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4        | 2.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4        | 2.03%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3        | 1.52%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 3        | 1.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 1.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 1.52%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 1.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.52%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3        | 1.52%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 3        | 1.52%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 1.52%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.52%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2        | 1.02%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 2        | 1.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2        | 1.02%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2        | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 1.02%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.02%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.02%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.51%   |
| Seagate FireCuda 530 SSD                                                                | 1        | 0.51%   |
| Seagate FireCuda 520/IronWolf 525 SSD                                                   | 1        | 0.51%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 1        | 0.51%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 1        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 120      | 67.8%   |
| NVMe | 30       | 16.95%  |
| IDE  | 15       | 8.47%   |
| RAID | 9        | 5.08%   |
| SAS  | 3        | 1.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 108      | 77.14%  |
| AMD     | 31       | 22.14%  |
| Unknown | 1        | 0.71%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| AMD GX-412TC SOC                      | 14       | 9.93%   |
| Intel N100                            | 8        | 5.67%   |
| Intel Core i5-6500 CPU @ 3.20GHz      | 6        | 4.26%   |
| Intel Celeron N5105 @ 2.00GHz         | 6        | 4.26%   |
| Intel Core i7-4770K CPU @ 3.50GHz     | 3        | 2.13%   |
| Intel Core i5-6400 CPU @ 2.70GHz      | 3        | 2.13%   |
| Intel Core i5-4590 CPU @ 3.30GHz      | 3        | 2.13%   |
| Intel Core i3-6100 CPU @ 3.70GHz      | 3        | 2.13%   |
| Intel Celeron J4125 CPU @ 2.00GHz     | 3        | 2.13%   |
| Intel Atom CPU E3845 @ 1.91GHz        | 3        | 2.13%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz   | 2        | 1.42%   |
| Intel Core i7-7500U CPU @ 2.70GHz     | 2        | 1.42%   |
| Intel Core i5-8500T CPU @ 2.10GHz     | 2        | 1.42%   |
| Intel Core i5-4250U CPU @ 1.30GHz     | 2        | 1.42%   |
| Intel Core i5-3470 CPU @ 3.20GHz      | 2        | 1.42%   |
| Intel Core i3-4130 CPU @ 3.40GHz      | 2        | 1.42%   |
| Intel Celeron CPU J3160 @ 1.60GHz     | 2        | 1.42%   |
| AMD Ryzen 9 3900X 12-Core Processor   | 2        | 1.42%   |
| AMD Ryzen 7 1700 Eight-Core Processor | 2        | 1.42%   |
| Intel Xeon E-2224 CPU @ 3.40GHz       | 1        | 0.71%   |
| Intel Xeon CPU X3470 @ 2.93GHz        | 1        | 0.71%   |
| Intel Xeon CPU X3440 @ 2.53GHz        | 1        | 0.71%   |
| Intel Xeon CPU E5450 @ 3.00GHz        | 1        | 0.71%   |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz   | 1        | 0.71%   |
| Intel Xeon CPU E3-1515M v5 @ 2.80GHz  | 1        | 0.71%   |
| Intel Xeon CPU E3-1230L v3 @ 1.80GHz  | 1        | 0.71%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz   | 1        | 0.71%   |
| Intel Pentium Silver N6005 @ 2.00GHz  | 1        | 0.71%   |
| Intel Pentium Dual-Core CPU E5700     | 1        | 0.71%   |
| Intel Pentium CPU G6950 @ 2.80GHz     | 1        | 0.71%   |
| Intel Pentium CPU G4560 @ 3.50GHz     | 1        | 0.71%   |
| Intel Pentium CPU G4400 @ 3.30GHz     | 1        | 0.71%   |
| Intel Core i7-8700K CPU @ 3.70GHz     | 1        | 0.71%   |
| Intel Core i7-6850K CPU @ 3.60GHz     | 1        | 0.71%   |
| Intel Core i7-6700K CPU @ 4.00GHz     | 1        | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz     | 1        | 0.71%   |
| Intel Core i7-5550U CPU @ 2.00GHz     | 1        | 0.71%   |
| Intel Core i7-4790K CPU @ 4.00GHz     | 1        | 0.71%   |
| Intel Core i7-4600U CPU @ 2.10GHz     | 1        | 0.71%   |
| Intel Core i7-4510U CPU @ 2.00GHz     | 1        | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 33       | 23.4%   |
| Intel Core i7           | 16       | 11.35%  |
| Intel Celeron           | 16       | 11.35%  |
| AMD GX                  | 16       | 11.35%  |
| Other                   | 15       | 10.64%  |
| Intel Xeon              | 10       | 7.09%   |
| Intel Core i3           | 9        | 6.38%   |
| AMD Ryzen 7             | 4        | 2.84%   |
| Intel Pentium           | 3        | 2.13%   |
| Intel Atom              | 3        | 2.13%   |
| AMD Ryzen 9             | 3        | 2.13%   |
| Intel Core 2 Quad       | 2        | 1.42%   |
| Intel Pentium Silver    | 1        | 0.71%   |
| Intel Pentium Dual-Core | 1        | 0.71%   |
| Intel Core 2 Duo        | 1        | 0.71%   |
| Intel Core 2            | 1        | 0.71%   |
| AMD Ryzen Threadripper  | 1        | 0.71%   |
| AMD Ryzen 7 PRO         | 1        | 0.71%   |
| AMD Ryzen 5             | 1        | 0.71%   |
| AMD G                   | 1        | 0.71%   |
| AMD FX                  | 1        | 0.71%   |
| AMD Athlon 64 X2        | 1        | 0.71%   |
| AMD Athlon              | 1        | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 91       | 64.54%  |
| 2       | 26       | 18.44%  |
| 6       | 7        | 4.96%   |
| 24      | 5        | 3.55%   |
| Unknown | 5        | 3.55%   |
| 16      | 4        | 2.84%   |
| 8       | 3        | 2.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 137      | 98.56%  |
| Unknown | 2        | 1.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 99       | 70.21%  |
| 2       | 37       | 26.24%  |
| Unknown | 5        | 3.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 23       | 16.31%  |
| Haswell       | 20       | 14.18%  |
| Skylake       | 17       | 12.06%  |
| Puma          | 15       | 10.64%  |
| KabyLake      | 10       | 7.09%   |
| IvyBridge     | 9        | 6.38%   |
| Silvermont    | 7        | 4.96%   |
| Zen           | 4        | 2.84%   |
| SandyBridge   | 4        | 2.84%   |
| Penryn        | 4        | 2.84%   |
| Nehalem       | 4        | 2.84%   |
| Goldmont plus | 4        | 2.84%   |
| Zen 2         | 3        | 2.13%   |
| Broadwell     | 3        | 2.13%   |
| TigerLake     | 2        | 1.42%   |
| Piledriver    | 2        | 1.42%   |
| Jaguar        | 2        | 1.42%   |
| Core          | 2        | 1.42%   |
| Zen 3         | 1        | 0.71%   |
| Westmere      | 1        | 0.71%   |
| K8 Hammer     | 1        | 0.71%   |
| Goldmont      | 1        | 0.71%   |
| CometLake     | 1        | 0.71%   |
| Bobcat        | 1        | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 85       | 68%     |
| Nvidia                     | 20       | 16%     |
| AMD                        | 13       | 10.4%   |
| Matrox Electronics Systems | 4        | 3.2%    |
| ASPEED Technology          | 3        | 2.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                                    | 10       | 7.94%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 9        | 7.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8        | 6.35%   |
| Intel JasperLake [UHD Graphics]                                                          | 8        | 6.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6        | 4.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5        | 3.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5        | 3.97%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 3.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4        | 3.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 2.38%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 3        | 2.38%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 2        | 1.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 1.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 1.59%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2        | 1.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2        | 1.59%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 1.59%   |
| Intel HD Graphics 620                                                                    | 2        | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 1.59%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.59%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 1.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.59%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 1.59%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.79%   |
| Nvidia GT218 [NVS 300]                                                                   | 1        | 0.79%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 0.79%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.79%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.79%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 0.79%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 0.79%   |
| Nvidia GA106 [GeForce RTX 3060]                                                          | 1        | 0.79%   |
| Nvidia AD106 [GeForce RTX 4060 Ti]                                                       | 1        | 0.79%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 0.79%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1        | 0.79%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 0.79%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1        | 0.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1        | 0.79%   |
| Intel Iris Pro Graphics P580                                                             | 1        | 0.79%   |
| Intel HD Graphics 630                                                                    | 1        | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 84       | 59.57%  |
| Other           | 18       | 12.77%  |
| 1 x Nvidia      | 18       | 12.77%  |
| 1 x AMD         | 11       | 7.8%    |
| 1 x Matrox      | 4        | 2.84%   |
| 1 x ASPEED      | 2        | 1.42%   |
| 2 x AMD         | 1        | 0.71%   |
| Nvidia + ASPEED | 1        | 0.71%   |
| Intel + AMD     | 1        | 0.71%   |
| AMD + Nvidia    | 1        | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 107      | 76.43%  |
| Unknown     | 20       | 14.29%  |
| Proprietary | 13       | 9.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 123      | 88.49%  |
| 1.01-2.0   | 4        | 2.88%   |
| 5.01-6.0   | 3        | 2.16%   |
| 0.51-1.0   | 3        | 2.16%   |
| 7.01-8.0   | 2        | 1.44%   |
| 3.01-4.0   | 2        | 1.44%   |
| 8.01-16.0  | 2        | 1.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 7        | 24.14%  |
| Hewlett-Packard      | 5        | 17.24%  |
| Philips              | 4        | 13.79%  |
| LG Electronics       | 2        | 6.9%    |
| Iiyama               | 2        | 6.9%    |
| Dell                 | 2        | 6.9%    |
| AOC                  | 2        | 6.9%    |
| Ancor Communications | 2        | 6.9%    |
| VMO                  | 1        | 3.45%   |
| Goldstar             | 1        | 3.45%   |
| Acer                 | 1        | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch    | 2        | 6.06%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch             | 2        | 6.06%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                | 2        | 6.06%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                     | 2        | 6.06%   |
| AOC 2350 AOC2350 1920x1080 510x290mm 23.1-inch                       | 2        | 6.06%   |
| VMO LCD QHD 1 VMO1091 2560x1440 600x340mm 27.2-inch                  | 1        | 3.03%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch | 1        | 3.03%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch    | 1        | 3.03%   |
| Samsung Electronics LCD Monitor SyncMaster                           | 1        | 3.03%   |
| Samsung Electronics LCD Monitor SE790C 3440x1440                     | 1        | 3.03%   |
| Samsung Electronics LCD Monitor S23E650 3840x1080                    | 1        | 3.03%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 1        | 3.03%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 710x400mm 32.1-inch            | 1        | 3.03%   |
| Philips PHL 221B6Q PHL08DF 1920x1080 480x270mm 21.7-inch             | 1        | 3.03%   |
| LG Electronics LCD Monitor LX20D 1600x1200                           | 1        | 3.03%   |
| LG Electronics LCD Monitor LG HDR WQHD+ 3840x1600                    | 1        | 3.03%   |
| Iiyama PL2888UH IVM7104 3840x2160 620x340mm 27.8-inch                | 1        | 3.03%   |
| Hewlett-Packard Z27n G2 HPN348A 2560x1440 600x340mm 27.2-inch        | 1        | 3.03%   |
| Hewlett-Packard w2216 HWP280C 1680x1050 470x290mm 21.7-inch          | 1        | 3.03%   |
| Hewlett-Packard LCD Monitor Z24n 1920x1200                           | 1        | 3.03%   |
| Hewlett-Packard LCD Monitor E241i 1920x1200                          | 1        | 3.03%   |
| Hewlett-Packard L2335 HWP2615 1920x1200 500x310mm 23.2-inch          | 1        | 3.03%   |
| Hewlett-Packard E243i HPN3463 1920x1200 520x320mm 24.0-inch          | 1        | 3.03%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                | 1        | 3.03%   |
| Dell UP2715K DEL40B8 3840x2160 600x340mm 27.2-inch                   | 1        | 3.03%   |
| Ancor Communications VC279 ACI27C4 1920x1080 600x340mm 27.2-inch     | 1        | 3.03%   |
| Ancor Communications LCD Monitor VX238                               | 1        | 3.03%   |
| Acer LCD Monitor KG251Q 3840x1080                                    | 1        | 3.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 7        | 24.14%  |
| 2560x1440 (QHD)    | 5        | 17.24%  |
| 1920x1200 (WUXGA)  | 5        | 17.24%  |
| 3840x2160 (4K)     | 4        | 13.79%  |
| 3840x1080          | 2        | 6.9%    |
| Unknown            | 2        | 6.9%    |
| 3840x1600          | 1        | 3.45%   |
| 3440x1440          | 1        | 3.45%   |
| 1680x1050 (WSXGA+) | 1        | 3.45%   |
| 1600x1200          | 1        | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 7        | 29.17%  |
| 27      | 6        | 25%     |
| 23      | 4        | 16.67%  |
| 21      | 4        | 16.67%  |
| 24      | 2        | 8.33%   |
| 32      | 1        | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 11       | 45.83%  |
| Unknown     | 7        | 29.17%  |
| 401-500     | 4        | 16.67%  |
| 701-800     | 1        | 4.17%   |
| 601-700     | 1        | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 13       | 56.52%  |
| Unknown | 7        | 30.43%  |
| 16/10   | 3        | 13.04%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 30.43%  |
| Unknown        | 7        | 30.43%  |
| 301-350        | 6        | 26.09%  |
| 251-300        | 2        | 8.7%    |
| 351-500        | 1        | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 8        | 29.63%  |
| Unknown | 7        | 25.93%  |
| 101-120 | 5        | 18.52%  |
| 161-240 | 4        | 14.81%  |
| 1-50    | 2        | 7.41%   |
| 121-160 | 1        | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 117      | 82.98%  |
| 1     | 16       | 11.35%  |
| 2     | 8        | 5.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 114      | 63.69%  |
| Realtek Semiconductor    | 43       | 24.02%  |
| Broadcom                 | 7        | 3.91%   |
| Qualcomm Atheros         | 5        | 2.79%   |
| TP-Link                  | 2        | 1.12%   |
| Ralink Technology        | 1        | 0.56%   |
| OPPO Electronics         | 1        | 0.56%   |
| Mellanox Technologies    | 1        | 0.56%   |
| MediaTek                 | 1        | 0.56%   |
| Marvell Technology Group | 1        | 0.56%   |
| D-Link System            | 1        | 0.56%   |
| Apple                    | 1        | 0.56%   |
| American Megatrends      | 1        | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 36       | 16.22%  |
| Intel I211 Gigabit Network Connection                                         | 22       | 9.91%   |
| Intel Ethernet Controller I226-V                                              | 21       | 9.46%   |
| Intel I210 Gigabit Network Connection                                         | 17       | 7.66%   |
| Intel 82574L Gigabit Network Connection                                       | 11       | 4.95%   |
| Intel I350 Gigabit Network Connection                                         | 8        | 3.6%    |
| Intel Ethernet Connection I217-LM                                             | 7        | 3.15%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7        | 3.15%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 2.7%    |
| Intel 82580 Gigabit Network Connection                                        | 5        | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 2.25%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 1.8%    |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 1.35%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 3        | 1.35%   |
| Intel Ethernet Controller I225-V                                              | 3        | 1.35%   |
| Intel Ethernet Connection I217-V                                              | 3        | 1.35%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3        | 1.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 0.9%    |
| Intel Wireless 7260                                                           | 2        | 0.9%    |
| Intel Ethernet Connection I218-V                                              | 2        | 0.9%    |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 0.9%    |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 0.9%    |
| Intel 82576NS Gigabit Network Connection                                      | 2        | 0.9%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 2        | 0.9%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 0.45%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 0.45%   |
| Realtek USB 2.5GbE Controller                                                 | 1        | 0.45%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.45%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.45%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 0.45%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1        | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.45%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 0.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 0.45%   |
| OPPO WAIPIO-MTP _SN:2EE444D0 RNDIS Control RNDIS Ethernet Data                | 1        | 0.45%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1        | 0.45%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 9        | 42.86%  |
| Realtek Semiconductor | 4        | 19.05%  |
| Qualcomm Atheros      | 3        | 14.29%  |
| TP-Link               | 2        | 9.52%   |
| Broadcom              | 2        | 9.52%   |
| Ralink Technology     | 1        | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 2        | 9.52%   |
| Intel Wireless 7260                                             | 2        | 9.52%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 2        | 9.52%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                    | 1        | 4.76%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 1        | 4.76%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 1        | 4.76%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 1        | 4.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                           | 1        | 4.76%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1        | 4.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 1        | 4.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 1        | 4.76%   |
| Intel Wireless 8265 / 8275                                      | 1        | 4.76%   |
| Intel Wireless 3165                                             | 1        | 4.76%   |
| Intel Wi-Fi 6 AX200                                             | 1        | 4.76%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 1        | 4.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 1        | 4.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                 | 1        | 4.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 1        | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 111      | 66.47%  |
| Realtek Semiconductor    | 42       | 25.15%  |
| Broadcom                 | 6        | 3.59%   |
| Qualcomm Atheros         | 2        | 1.2%    |
| OPPO Electronics         | 1        | 0.6%    |
| MediaTek                 | 1        | 0.6%    |
| Marvell Technology Group | 1        | 0.6%    |
| D-Link System            | 1        | 0.6%    |
| Apple                    | 1        | 0.6%    |
| American Megatrends      | 1        | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 36       | 18%     |
| Intel I211 Gigabit Network Connection                                         | 22       | 11%     |
| Intel Ethernet Controller I226-V                                              | 21       | 10.5%   |
| Intel I210 Gigabit Network Connection                                         | 17       | 8.5%    |
| Intel 82574L Gigabit Network Connection                                       | 11       | 5.5%    |
| Intel I350 Gigabit Network Connection                                         | 8        | 4%      |
| Intel Ethernet Connection I217-LM                                             | 7        | 3.5%    |
| Intel Ethernet Connection (2) I219-LM                                         | 7        | 3.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 3%      |
| Intel 82580 Gigabit Network Connection                                        | 5        | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 2.5%    |
| Intel 82576 Gigabit Network Connection                                        | 4        | 2%      |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 1.5%    |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 3        | 1.5%    |
| Intel Ethernet Controller I225-V                                              | 3        | 1.5%    |
| Intel Ethernet Connection I217-V                                              | 3        | 1.5%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3        | 1.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1%      |
| Intel Ethernet Connection I218-V                                              | 2        | 1%      |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 1%      |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1%      |
| Intel 82576NS Gigabit Network Connection                                      | 2        | 1%      |
| Realtek USB 2.5GbE Controller                                                 | 1        | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.5%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.5%    |
| OPPO WAIPIO-MTP _SN:2EE444D0 RNDIS Control RNDIS Ethernet Data                | 1        | 0.5%    |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.5%    |
| Intel NM10/ICH7 Family LAN Controller                                         | 1        | 0.5%    |
| Intel I210 Gigabit Fiber Network Connection                                   | 1        | 0.5%    |
| Intel Ethernet Controller I226-LM                                             | 1        | 0.5%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.5%    |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 0.5%    |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.5%    |
| Intel Ethernet Connection (14) I219-LM                                        | 1        | 0.5%    |
| Intel 82579V Gigabit Network Connection                                       | 1        | 0.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.5%    |
| Intel 82567LF-3 Gigabit Network Connection                                    | 1        | 0.5%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 1        | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 138      | 86.25%  |
| WiFi     | 21       | 13.13%  |
| Unknown  | 1        | 0.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 136      | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 38       | 26.39%  |
| 4     | 35       | 24.31%  |
| 3     | 26       | 18.06%  |
| 1     | 14       | 9.72%   |
| 5     | 12       | 8.33%   |
| 6     | 11       | 7.64%   |
| 7     | 4        | 2.78%   |
| 13    | 1        | 0.69%   |
| 9     | 1        | 0.69%   |
| 8     | 1        | 0.69%   |
| 0     | 1        | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 128      | 88.89%  |
| Yes  | 16       | 11.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 8        | 44.44%  |
| Cambridge Silicon Radio | 4        | 22.22%  |
| Apple                   | 2        | 11.11%  |
| Realtek                 | 1        | 5.56%   |
| MediaTek                | 1        | 5.56%   |
| IMC Networks            | 1        | 5.56%   |
| Dell                    | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                   | 4        | 22.22%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 4        | 22.22%  |
| Intel Wireless-AC 3168 Bluetooth                     | 2        | 11.11%  |
| Apple Bluetooth Host Controller                      | 2        | 11.11%  |
| Realtek  Bluetooth 4.0 Adapter                       | 1        | 5.56%   |
| MediaTek Bluetooth Adapter                           | 1        | 5.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 1        | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 1        | 5.56%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip | 1        | 5.56%   |
| Dell Wireless 355C Bluetooth 2.0 + EDR module        | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 84       | 64.12%  |
| Nvidia                   | 20       | 15.27%  |
| AMD                      | 18       | 13.74%  |
| Realtek Semiconductor    | 2        | 1.53%   |
| Philips (or NXP)         | 1        | 0.76%   |
| Nordic Semiconductor ASA | 1        | 0.76%   |
| Hewlett-Packard          | 1        | 0.76%   |
| GN Netcom                | 1        | 0.76%   |
| Generalplus Technology   | 1        | 0.76%   |
| Focusrite-Novation       | 1        | 0.76%   |
| BEHRINGER International  | 1        | 0.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 15       | 9.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11       | 7.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10       | 6.45%   |
| Intel Jasper Lake HD Audio                                                                        | 8        | 5.16%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 8        | 5.16%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5        | 3.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5        | 3.23%   |
| Intel 8 Series HD Audio Controller                                                                | 5        | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5        | 3.23%   |
| Nvidia High Definition Audio Controller                                                           | 4        | 2.58%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4        | 2.58%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 1.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3        | 1.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3        | 1.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3        | 1.94%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 1.94%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 1.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3        | 1.94%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 1.29%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 1.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2        | 1.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2        | 1.29%   |
| Intel Broadwell-U Audio Controller                                                                | 2        | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 1.29%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 1.29%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2        | 1.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 1.29%   |
| Realtek Semiconductor USB Audio                                                                   | 1        | 0.65%   |
| Realtek Semiconductor Microphone(Attila) Microphone(Attila) Microphone(Attila)                    | 1        | 0.65%   |
| Philips (or NXP) Philips SHG7980                                                                  | 1        | 0.65%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 0.65%   |
| Nvidia MCP65 High Definition Audio                                                                | 1        | 0.65%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 0.65%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 0.65%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 0.65%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 0.65%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1        | 0.65%   |
| Nordic Semiconductor ASA USB Composite Device Mic Device                                          | 1        | 0.65%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1        | 0.65%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 1        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 24       | 17.02%  |
| Corsair             | 22       | 15.6%   |
| Samsung Electronics | 21       | 14.89%  |
| Kingston            | 16       | 11.35%  |
| Micron Technology   | 14       | 9.93%   |
| Crucial             | 12       | 8.51%   |
| SK hynix            | 11       | 7.8%    |
| G.Skill             | 5        | 3.55%   |
| Kimtigo             | 4        | 2.84%   |
| Ramaxel Technology  | 3        | 2.13%   |
| Unknown             | 2        | 1.42%   |
| Smart Modular       | 1        | 0.71%   |
| Mushkin             | 1        | 0.71%   |
| HPE                 | 1        | 0.71%   |
| Hewlett-Packard     | 1        | 0.71%   |
| Elpida              | 1        | 0.71%   |
| ASint Technology    | 1        | 0.71%   |
| Apacer              | 1        | 0.71%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 12       | 7.95%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s          | 4        | 2.65%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s     | 4        | 2.65%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 3        | 1.99%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s              | 2        | 1.32%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s    | 2        | 1.32%   |
| SK hynix RAM HMCG78AEBSA092N 16GB SODIMM DDR5 4800MT/s  | 2        | 1.32%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s               | 2        | 1.32%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s  | 2        | 1.32%   |
| Samsung RAM M471A1K43CB1-CWE 8GB SODIMM DDR4 3200MT/s   | 2        | 1.32%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s | 2        | 1.32%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 1.32%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                | 2        | 1.32%   |
| Micron RAM 8ATF1G64HZ-2G6D1 8GB SODIMM DDR4 2667MT/s    | 2        | 1.32%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s | 2        | 1.32%   |
| Unknown                                                 | 2        | 1.32%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s             | 1        | 0.66%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 0.66%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 0.66%   |
| Unknown RAM Module 4096MB DIMM DDR3 1332MT/s            | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 1        | 0.66%   |
| Unknown RAM Module 2048MB DIMM DDR3 1332MT/s            | 1        | 0.66%   |
| Unknown RAM Module 1GB DIMM SDRAM                       | 1        | 0.66%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                | 1        | 0.66%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                | 1        | 0.66%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s              | 1        | 0.66%   |
| Unknown RAM Module 1024MB DIMM DDR3 1332MT/s            | 1        | 0.66%   |
| Smart Modular RAM Module 4GB DIMM DDR3 1333MT/s         | 1        | 0.66%   |
| SK hynix RAM Module 16GB DIMM DDR3 1866MT/s             | 1        | 0.66%   |
| SK hynix RAM HMT451U7AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 0.66%   |
| SK hynix RAM HMT41GU7AFR8A-PB 8GB DIMM DDR3 1600MT/s    | 1        | 0.66%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8GB DIMM DDR3 1600MT/s    | 1        | 0.66%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s    | 1        | 0.66%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s    | 1        | 0.66%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s  | 1        | 0.66%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s               | 1        | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s     | 1        | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 62       | 46.97%  |
| DDR4    | 50       | 37.88%  |
| DDR5    | 11       | 8.33%   |
| DDR2    | 4        | 3.03%   |
| Unknown | 3        | 2.27%   |
| SDRAM   | 2        | 1.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 78       | 59.09%  |
| SODIMM | 54       | 40.91%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 56       | 39.16%  |
| 4096  | 49       | 34.27%  |
| 16384 | 19       | 13.29%  |
| 2048  | 9        | 6.29%   |
| 1024  | 6        | 4.2%    |
| 32768 | 4        | 2.8%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 32       | 23.19%  |
| 1333    | 29       | 21.01%  |
| 3200    | 16       | 11.59%  |
| 2133    | 16       | 11.59%  |
| 4800    | 11       | 7.97%   |
| 2667    | 8        | 5.8%    |
| 2400    | 8        | 5.8%    |
| 800     | 4        | 2.9%    |
| 667     | 4        | 2.9%    |
| 2666    | 2        | 1.45%   |
| Unknown | 2        | 1.45%   |
| 4400    | 1        | 0.72%   |
| 2933    | 1        | 0.72%   |
| 1867    | 1        | 0.72%   |
| 1866    | 1        | 0.72%   |
| 1332    | 1        | 0.72%   |
| 333     | 1        | 0.72%   |

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

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

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
| 1     | 79       | 56.43%  |
| 0     | 41       | 29.29%  |
| 2     | 17       | 12.14%  |
| 5     | 1        | 0.71%   |
| 4     | 1        | 0.71%   |
| 3     | 1        | 0.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 91       | 80.53%  |
| Net/wireless             | 8        | 7.08%   |
| Bluetooth                | 6        | 5.31%   |
| Sound                    | 3        | 2.65%   |
| Net/ethernet             | 2        | 1.77%   |
| Storage/ata              | 1        | 0.88%   |
| Graphics card            | 1        | 0.88%   |
| Firewire controller      | 1        | 0.88%   |

