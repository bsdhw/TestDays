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

Total: 502

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkCentre M90p L1BRM6H    | [800565bf84](https://bsd-hardware.info/?probe=800565bf84) | Jan 01, 2026 |
| Dell          | 0KWVT8 A02                  | [3ee774aa9b](https://bsd-hardware.info/?probe=3ee774aa9b) | Dec 18, 2025 |
| Gigabyte      | Z390 UD                     | [30709fdf65](https://bsd-hardware.info/?probe=30709fdf65) | Dec 15, 2025 |
| Lenovo        | ThinkCentre M90p L1BRM6H    | [bdb4f5e891](https://bsd-hardware.info/?probe=bdb4f5e891) | Dec 15, 2025 |
| Unknown       | Unknown                     | [b8291a45ea](https://bsd-hardware.info/?probe=b8291a45ea) | Dec 14, 2025 |
| Lenovo        | ThinkCentre M90p L1BRM6H    | [8585182662](https://bsd-hardware.info/?probe=8585182662) | Dec 09, 2025 |
| Intel         | B75                         | [a7cd91259f](https://bsd-hardware.info/?probe=a7cd91259f) | Dec 09, 2025 |
| Techvision    | TVI7309X B0                 | [57c5d3f6b8](https://bsd-hardware.info/?probe=57c5d3f6b8) | Dec 08, 2025 |
| Wistron       | ProLiant ML110 G6           | [e76c924297](https://bsd-hardware.info/?probe=e76c924297) | Dec 05, 2025 |
| Gigabyte      | Z390 UD                     | [e721aea164](https://bsd-hardware.info/?probe=e721aea164) | Dec 05, 2025 |
| ASUSTek       | P5KPL-AM SE                 | [9acdf4e4d9](https://bsd-hardware.info/?probe=9acdf4e4d9) | Dec 04, 2025 |
| Wistron       | ProLiant ML110 G6           | [d1baeb4331](https://bsd-hardware.info/?probe=d1baeb4331) | Dec 02, 2025 |
| Intel         | B75 V1.1                    | [cda5ec3ff7](https://bsd-hardware.info/?probe=cda5ec3ff7) | Nov 27, 2025 |
| ASUSTek       | M2N-MX SE Plus              | [0a5beb9e8d](https://bsd-hardware.info/?probe=0a5beb9e8d) | Nov 24, 2025 |
| Lenovo        | ThinkCentre M90p L1BRM6H    | [aabc4d488d](https://bsd-hardware.info/?probe=aabc4d488d) | Nov 24, 2025 |
| Unknown       | Unknown                     | [c473f67730](https://bsd-hardware.info/?probe=c473f67730) | Nov 16, 2025 |
| Unknown       | Unknown                     | [6c84ccaf82](https://bsd-hardware.info/?probe=6c84ccaf82) | Nov 16, 2025 |
| Techvision    | TVI7309X B0                 | [f6c7ad1562](https://bsd-hardware.info/?probe=f6c7ad1562) | Nov 09, 2025 |
| Unknown       | Unknown                     | [78e0dce780](https://bsd-hardware.info/?probe=78e0dce780) | Nov 01, 2025 |
| Unknown       | Unknown                     | [e2b5078c38](https://bsd-hardware.info/?probe=e2b5078c38) | Oct 31, 2025 |
| Intel         | Q3XXG4-P V1.0               | [1a6cbc2c84](https://bsd-hardware.info/?probe=1a6cbc2c84) | Oct 31, 2025 |
| Unknown       | Unknown                     | [a93af77e8b](https://bsd-hardware.info/?probe=a93af77e8b) | Oct 31, 2025 |
| Intel         | Q3XXG4-P V1.0               | [b50d52dc2f](https://bsd-hardware.info/?probe=b50d52dc2f) | Oct 31, 2025 |
| Techvision    | TVI7309X B0                 | [1bc6c13ee5](https://bsd-hardware.info/?probe=1bc6c13ee5) | Oct 31, 2025 |
| Unknown       | Unknown                     | [82f8f9b9f5](https://bsd-hardware.info/?probe=82f8f9b9f5) | Oct 31, 2025 |
| Unknown       | Unknown                     | [b1bab1a894](https://bsd-hardware.info/?probe=b1bab1a894) | Oct 31, 2025 |
| Unknown       | Unknown                     | [449976df23](https://bsd-hardware.info/?probe=449976df23) | Oct 31, 2025 |
| Intel         | Q3XXG4-P V1.0               | [a84c81069e](https://bsd-hardware.info/?probe=a84c81069e) | Oct 31, 2025 |
| Intel         | Q3XXG4-P V1.0               | [62a06d38be](https://bsd-hardware.info/?probe=62a06d38be) | Oct 31, 2025 |
| Unknown       | Unknown                     | [261d22971f](https://bsd-hardware.info/?probe=261d22971f) | Oct 30, 2025 |
| Unknown       | Unknown                     | [d5e0ff82b8](https://bsd-hardware.info/?probe=d5e0ff82b8) | Oct 29, 2025 |
| Lenovo        | IdeaPad 1 15IAU7 82VY       | [e03b7ff8d7](https://bsd-hardware.info/?probe=e03b7ff8d7) | Oct 27, 2025 |
| OEM           | MCR-A520M-DXV4 V1.0         | [57c7b475bd](https://bsd-hardware.info/?probe=57c7b475bd) | Oct 26, 2025 |
| Unknown       | Unknown                     | [e71c6aea6d](https://bsd-hardware.info/?probe=e71c6aea6d) | Oct 25, 2025 |
| Dell          | 0VTJVC A01                  | [d69bdd3a5b](https://bsd-hardware.info/?probe=d69bdd3a5b) | Oct 24, 2025 |
| Lenovo        | IdeaPad 1 15IAU7 82VY       | [23579e6d61](https://bsd-hardware.info/?probe=23579e6d61) | Oct 21, 2025 |
| Gigabyte      | H170N-WIFI-CF               | [11bb8ee985](https://bsd-hardware.info/?probe=11bb8ee985) | Oct 07, 2025 |
| ASUSTek       | P8H61-M LE/BR               | [2b600aa1b9](https://bsd-hardware.info/?probe=2b600aa1b9) | Oct 06, 2025 |
| Dell          | 0HD5W2 A01                  | [4788a964ad](https://bsd-hardware.info/?probe=4788a964ad) | Oct 02, 2025 |
| Dell          | 0VTJVC A01                  | [a7eeca17c1](https://bsd-hardware.info/?probe=a7eeca17c1) | Sep 18, 2025 |
| PAIQ          | Baytrail-Series A1          | [28c0716c48](https://bsd-hardware.info/?probe=28c0716c48) | Sep 16, 2025 |
| Lenovo        | ThinkCentre M90p 5864B19    | [0a57e90346](https://bsd-hardware.info/?probe=0a57e90346) | Sep 10, 2025 |
| Lenovo        | 334B SDK0T76530 WIN 3556... | [a7b9cd2d37](https://bsd-hardware.info/?probe=a7b9cd2d37) | Sep 08, 2025 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | [d37e4d2de1](https://bsd-hardware.info/?probe=d37e4d2de1) | Aug 27, 2025 |
| Gigabyte      | B550M DS3H                  | [dbb56cb8fb](https://bsd-hardware.info/?probe=dbb56cb8fb) | Aug 27, 2025 |
| Unknown       | Unknown                     | [7570fd6f01](https://bsd-hardware.info/?probe=7570fd6f01) | Aug 27, 2025 |
| Unknown       | Unknown                     | [b745504cf6](https://bsd-hardware.info/?probe=b745504cf6) | Aug 23, 2025 |
| Unknown       | Unknown                     | [31d8527cdc](https://bsd-hardware.info/?probe=31d8527cdc) | Aug 19, 2025 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [85de119457](https://bsd-hardware.info/?probe=85de119457) | Aug 08, 2025 |
| Gigabyte      | B550M DS3H AC               | [60942f4c9d](https://bsd-hardware.info/?probe=60942f4c9d) | Aug 08, 2025 |
| Dell          | 08NPPY A00                  | [e0e896b8d5](https://bsd-hardware.info/?probe=e0e896b8d5) | Jul 28, 2025 |
| ANGXUN        | X99-V205 V2.0               | [11f63fc02f](https://bsd-hardware.info/?probe=11f63fc02f) | Jul 28, 2025 |
| Dell          | 0JR269                      | [3321bb9549](https://bsd-hardware.info/?probe=3321bb9549) | Jul 27, 2025 |
| ECS           | H61H2-M2                    | [6719fff345](https://bsd-hardware.info/?probe=6719fff345) | Jul 21, 2025 |
| Unknown       | Unknown                     | [e787423ec4](https://bsd-hardware.info/?probe=e787423ec4) | Jul 15, 2025 |
| ASUSTek       | PRIME A520M-K               | [6adf994c5d](https://bsd-hardware.info/?probe=6adf994c5d) | Jul 13, 2025 |
| Unknown       | Unknown                     | [5efaedcf51](https://bsd-hardware.info/?probe=5efaedcf51) | Jul 11, 2025 |
| Biostar       | A320MH                      | [8fa78d8cd6](https://bsd-hardware.info/?probe=8fa78d8cd6) | Jul 11, 2025 |
| Biostar       | A320MH                      | [f1b336ba44](https://bsd-hardware.info/?probe=f1b336ba44) | Jul 10, 2025 |
| Techvision    | TVI7309X B0                 | [12476c7e8a](https://bsd-hardware.info/?probe=12476c7e8a) | Jul 03, 2025 |
| ASUSTek       | H81M-C/BR                   | [413a703228](https://bsd-hardware.info/?probe=413a703228) | Jun 29, 2025 |
| PCWare        | IPX1800G2                   | [29c2894945](https://bsd-hardware.info/?probe=29c2894945) | Jun 27, 2025 |
| ASUSTek       | H81M-C/BR                   | [a2fd75ca95](https://bsd-hardware.info/?probe=a2fd75ca95) | Jun 26, 2025 |
| Unknown       | Unknown                     | [5e9fe37b34](https://bsd-hardware.info/?probe=5e9fe37b34) | Jun 23, 2025 |
| Unknown       | Unknown                     | [9b1b90e8d3](https://bsd-hardware.info/?probe=9b1b90e8d3) | Jun 22, 2025 |
| Dell          | 0GDG8Y A02                  | [fc6be01ea9](https://bsd-hardware.info/?probe=fc6be01ea9) | Jun 21, 2025 |
| Gigabyte      | H170N-WIFI-CF               | [6eb77cafb4](https://bsd-hardware.info/?probe=6eb77cafb4) | Jun 20, 2025 |
| Dell          | 0200DY A01                  | [a1919c5c3c](https://bsd-hardware.info/?probe=a1919c5c3c) | Jun 20, 2025 |
| ASUSTek       | P8H61-M LE/BR               | [4a9b43edaf](https://bsd-hardware.info/?probe=4a9b43edaf) | Jun 19, 2025 |
| Unknown       | Unknown                     | [60006f6e27](https://bsd-hardware.info/?probe=60006f6e27) | Jun 06, 2025 |
| Techvision    | TVI7309X B0                 | [96d9813896](https://bsd-hardware.info/?probe=96d9813896) | Jun 05, 2025 |
| Unknown       | Unknown                     | [565a08aeec](https://bsd-hardware.info/?probe=565a08aeec) | Jun 01, 2025 |
| Intel         | H61                         | [7277c70705](https://bsd-hardware.info/?probe=7277c70705) | May 30, 2025 |
| Techvision    | TVI7309X B0                 | [509a50ab86](https://bsd-hardware.info/?probe=509a50ab86) | May 28, 2025 |
| Intel         | H81                         | [a54e1b0055](https://bsd-hardware.info/?probe=a54e1b0055) | May 24, 2025 |
| ASUSTek       | PRIME H510M-E               | [faea4ddd17](https://bsd-hardware.info/?probe=faea4ddd17) | May 16, 2025 |
| ASUSTek       | PRIME H510M-E               | [ce23d0fc03](https://bsd-hardware.info/?probe=ce23d0fc03) | May 16, 2025 |
| Intel         | H81                         | [acf04289dd](https://bsd-hardware.info/?probe=acf04289dd) | May 14, 2025 |
| Gigabyte      | 945GCM-S2C                  | [4b6343527e](https://bsd-hardware.info/?probe=4b6343527e) | May 09, 2025 |
| Gigabyte      | H170N-WIFI-CF               | [f583c57725](https://bsd-hardware.info/?probe=f583c57725) | May 08, 2025 |
| Techvision    | TVI7309X B0                 | [673efab07e](https://bsd-hardware.info/?probe=673efab07e) | May 07, 2025 |
| AZW           | EQ                          | [2d8de8ea8c](https://bsd-hardware.info/?probe=2d8de8ea8c) | May 07, 2025 |
| Unknown       | Unknown                     | [3b4e6690e9](https://bsd-hardware.info/?probe=3b4e6690e9) | May 06, 2025 |
| Dell          | 0GDG8Y A02                  | [b782addbbb](https://bsd-hardware.info/?probe=b782addbbb) | May 04, 2025 |
| Dell          | 0WN7Y6 A02                  | [11094710f0](https://bsd-hardware.info/?probe=11094710f0) | Apr 26, 2025 |
| Gigabyte      | H97N-WIFI                   | [734dcf8218](https://bsd-hardware.info/?probe=734dcf8218) | Apr 25, 2025 |
| Unknown       | Unknown                     | [1953a73ae6](https://bsd-hardware.info/?probe=1953a73ae6) | Apr 22, 2025 |
| Unknown       | Unknown                     | [4e0a2deea4](https://bsd-hardware.info/?probe=4e0a2deea4) | Apr 22, 2025 |
| Unknown       | Unknown                     | [55f25075a0](https://bsd-hardware.info/?probe=55f25075a0) | Apr 21, 2025 |
| Unknown       | Unknown                     | [ba982b7388](https://bsd-hardware.info/?probe=ba982b7388) | Apr 15, 2025 |
| ASRock        | J4005B-ITX                  | [c2cc53b84a](https://bsd-hardware.info/?probe=c2cc53b84a) | Apr 13, 2025 |
| ASUSTek       | M2N-MX SE Plus              | [f2d3e93ebe](https://bsd-hardware.info/?probe=f2d3e93ebe) | Apr 07, 2025 |
| Unknown       | Unknown                     | [a219137ae6](https://bsd-hardware.info/?probe=a219137ae6) | Apr 04, 2025 |
| ASUSTek       | PRIME H510M-A               | [31b602bcf3](https://bsd-hardware.info/?probe=31b602bcf3) | Mar 22, 2025 |
| Intel         | Q3XXG4-P V1.0               | [c23620b2d4](https://bsd-hardware.info/?probe=c23620b2d4) | Mar 21, 2025 |
| PAIQ          | Baytrail-Series A1          | [366825d5eb](https://bsd-hardware.info/?probe=366825d5eb) | Mar 12, 2025 |
| Techvision    | TVI7309X B0                 | [a22d3d28b8](https://bsd-hardware.info/?probe=a22d3d28b8) | Feb 19, 2025 |
| MSI           | H110M PRO-VH PLUS           | [8472e8a8a5](https://bsd-hardware.info/?probe=8472e8a8a5) | Feb 15, 2025 |
| ASUSTek       | M5A97 R2.0                  | [ab6c72f8d6](https://bsd-hardware.info/?probe=ab6c72f8d6) | Feb 12, 2025 |
| Lenovo        | 30C1                        | [354344647a](https://bsd-hardware.info/?probe=354344647a) | Feb 08, 2025 |
| Dell          | 0411GW A02                  | [7039ec8969](https://bsd-hardware.info/?probe=7039ec8969) | Feb 07, 2025 |
| Unknown       | Unknown                     | [0d1285813a](https://bsd-hardware.info/?probe=0d1285813a) | Feb 06, 2025 |
| ASRock        | B550 PG Riptide             | [67cbab46c9](https://bsd-hardware.info/?probe=67cbab46c9) | Feb 05, 2025 |
| Dell          | 0411GW A02                  | [111d1b0746](https://bsd-hardware.info/?probe=111d1b0746) | Feb 05, 2025 |
| Unknown       | Unknown                     | [29178cf78a](https://bsd-hardware.info/?probe=29178cf78a) | Jan 31, 2025 |
| Biostar       | H410MH                      | [cdf2daae65](https://bsd-hardware.info/?probe=cdf2daae65) | Jan 29, 2025 |
| Techvision    | TVI7309X B0                 | [ae407acb03](https://bsd-hardware.info/?probe=ae407acb03) | Jan 28, 2025 |
| PCWare        | IPX1800G2                   | [8ea1119386](https://bsd-hardware.info/?probe=8ea1119386) | Jan 24, 2025 |
| Lenovo        | 30C1                        | [084bb91a4a](https://bsd-hardware.info/?probe=084bb91a4a) | Jan 22, 2025 |
| Intel         | DQ77KB AAG81483-501         | [f7f3ea8739](https://bsd-hardware.info/?probe=f7f3ea8739) | Jan 19, 2025 |
| ChangWang     | CW56-58                     | [6c156ae5a8](https://bsd-hardware.info/?probe=6c156ae5a8) | Jan 18, 2025 |
| Techvision    | TVI7309X B0                 | [857a3be9d7](https://bsd-hardware.info/?probe=857a3be9d7) | Jan 16, 2025 |
| Gigabyte      | H61M-DS2                    | [6544f43cfd](https://bsd-hardware.info/?probe=6544f43cfd) | Jan 15, 2025 |
| Unknown       | DH61BR G32662-203           | [88b78708a8](https://bsd-hardware.info/?probe=88b78708a8) | Jan 14, 2025 |
| Unknown       | DH61BR G32662-203           | [0189aa0eb9](https://bsd-hardware.info/?probe=0189aa0eb9) | Jan 14, 2025 |
| Techvision    | TVI7309X B0                 | [0e08b6d723](https://bsd-hardware.info/?probe=0e08b6d723) | Jan 10, 2025 |
| ASUSTek       | P8H61-M LX3 R2.0            | [83875e4395](https://bsd-hardware.info/?probe=83875e4395) | Jan 10, 2025 |
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
| ASUSTek       | P8H61-M LX3 R2.0            | [16d1e0aa3e](https://bsd-hardware.info/?probe=16d1e0aa3e) | Mar 31, 2023 |
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

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| helloSystem 0.8.1    | 16       | 3.97%   |
| OPNsense 25.7.6      | 13       | 3.23%   |
| helloSystem 0.7.0    | 13       | 3.23%   |
| OPNsense 23.1.11     | 10       | 2.48%   |
| OPNsense 25.1.5      | 8        | 1.99%   |
| OPNsense 25.1.9      | 7        | 1.74%   |
| OPNsense 24.7.12     | 7        | 1.74%   |
| OPNsense 23.7.12     | 7        | 1.74%   |
| helloSystem 0.8.0    | 7        | 1.74%   |
| OPNsense 25.7.9      | 6        | 1.49%   |
| OPNsense 24.7.5      | 6        | 1.49%   |
| OPNsense 24.7        | 6        | 1.49%   |
| OPNsense 23.1.7      | 6        | 1.49%   |
| OPNsense 23.1.5      | 6        | 1.49%   |
| OPNsense 22.1.10     | 6        | 1.49%   |
| OPNsense 20.7.8      | 6        | 1.49%   |
| OPNsense 23.7.10     | 5        | 1.24%   |
| OPNsense 23.1.9      | 5        | 1.24%   |
| OPNsense 22.7.5      | 5        | 1.24%   |
| OPNsense 21.1.3      | 5        | 1.24%   |
| OPNsense 21.1        | 5        | 1.24%   |
| helloSystem 0.4.0    | 5        | 1.24%   |
| OPNsense 25.1.7      | 4        | 0.99%   |
| OPNsense 25.1        | 4        | 0.99%   |
| OPNsense 24.7.7      | 4        | 0.99%   |
| OPNsense 24.7.6      | 4        | 0.99%   |
| OPNsense 24.7.11     | 4        | 0.99%   |
| OPNsense 24.1.9      | 4        | 0.99%   |
| OPNsense 24.1.5      | 4        | 0.99%   |
| OPNsense 23.7.9      | 4        | 0.99%   |
| OPNsense 23.1        | 4        | 0.99%   |
| OPNsense 22.7.8      | 4        | 0.99%   |
| OPNsense 22.7.4      | 4        | 0.99%   |
| OPNsense 21.1.1      | 4        | 0.99%   |
| helloSystem 0.6.0    | 4        | 0.99%   |
| helloSystem 0.5.0    | 4        | 0.99%   |
| FreeBSD 14.0-CURRENT | 4        | 0.99%   |
| OPNsense 25.7.7      | 3        | 0.74%   |
| OPNsense 25.7.4      | 3        | 0.74%   |
| OPNsense 25.7.3      | 3        | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 192      | 64.65%  |
| helloSystem | 47       | 15.82%  |
| FreeBSD     | 39       | 13.13%  |
| OpenBSD     | 6        | 2.02%   |
| GhostBSD    | 4        | 1.35%   |
| pfSense     | 2        | 0.67%   |
| NomadBSD    | 2        | 0.67%   |
| NetBSD      | 2        | 0.67%   |
| TrueNAS     | 1        | 0.34%   |
| FreeNAS     | 1        | 0.34%   |
| ClonOS      | 1        | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 289      | 98.97%  |
| i386  | 2        | 0.68%   |
| arm64 | 1        | 0.34%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 204      | 68.23%  |
| helloDesktop | 52       | 17.39%  |
| KDE5         | 10       | 3.34%   |
| XFCE         | 6        | 2.01%   |
| MATE         | 6        | 2.01%   |
| TWM          | 5        | 1.67%   |
| GNOME        | 5        | 1.67%   |
| Openbox      | 4        | 1.34%   |
| i3           | 3        | 1%      |
| X-Cinnamon   | 1        | 0.33%   |
| Window Maker | 1        | 0.33%   |
| LXQt         | 1        | 0.33%   |
| AwesomeWM    | 1        | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 206      | 70.07%  |
| X11     | 83       | 28.23%  |
| Wayland | 5        | 1.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 222      | 75%     |
| SLiM    | 50       | 16.89%  |
| SDDM    | 12       | 4.05%   |
| LightDM | 6        | 2.03%   |
| GDM     | 4        | 1.35%   |
| XDM     | 1        | 0.34%   |
| Ly      | 1        | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 208      | 68.42%  |
| en_US            | 31       | 10.2%   |
| C                | 29       | 9.54%   |
| pt_BR            | 24       | 7.89%   |
| fr_FR            | 6        | 1.97%   |
| pt               | 3        | 0.99%   |
| pt_PT            | 1        | 0.33%   |
| fr               | 1        | 0.33%   |
| en_US.ISO8859-15 | 1        | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 264      | 88%     |
| BIOS | 36       | 12%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Zfs    | 162      | 53.29%  |
| Ufs    | 113      | 37.17%  |
| Cd9660 | 23       | 7.57%   |
| Ffs    | 6        | 1.97%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 277      | 93.27%  |
| MBR     | 18       | 6.06%   |
| Unknown | 2        | 0.67%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUSTek Computer        | 52       | 17.81%  |
| Unknown                 | 48       | 16.44%  |
| Intel                   | 31       | 10.62%  |
| Dell                    | 30       | 10.27%  |
| Gigabyte Technology     | 26       | 8.9%    |
| Techvision              | 13       | 4.45%   |
| Hewlett-Packard         | 12       | 4.11%   |
| ASRock                  | 12       | 4.11%   |
| Lenovo                  | 10       | 3.42%   |
| MSI                     | 5        | 1.71%   |
| PCWare                  | 4        | 1.37%   |
| Itautec                 | 4        | 1.37%   |
| ECS                     | 4        | 1.37%   |
| Biostar                 | 4        | 1.37%   |
| Positivo                | 3        | 1.03%   |
| Pegatron                | 3        | 1.03%   |
| Yanling                 | 2        | 0.68%   |
| AZW                     | 2        | 0.68%   |
| YANYU                   | 1        | 0.34%   |
| Wistron                 | 1        | 0.34%   |
| ULTRATOP                | 1        | 0.34%   |
| T-bao                   | 1        | 0.34%   |
| Supermicro              | 1        | 0.34%   |
| Soyo                    | 1        | 0.34%   |
| Semp Toshiba            | 1        | 0.34%   |
| Procomp Ind. Eletronica | 1        | 0.34%   |
| pine64                  | 1        | 0.34%   |
| PAIQ                    | 1        | 0.34%   |
| OEM                     | 1        | 0.34%   |
| Megaware                | 1        | 0.34%   |
| maiyunda                | 1        | 0.34%   |
| LG Electronics          | 1        | 0.34%   |
| KLLISRE                 | 1        | 0.34%   |
| HC                      | 1        | 0.34%   |
| GoWin Solution          | 1        | 0.34%   |
| GALAX                   | 1        | 0.34%   |
| ECS-USA                 | 1        | 0.34%   |
| Dell EMC                | 1        | 0.34%   |
| Daten Tecnologia        | 1        | 0.34%   |
| CWWK                    | 1        | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 49       | 16.78%  |
| Techvision TVI7309X            | 13       | 4.45%   |
| Intel Q3XXG4-P V1.0            | 10       | 3.42%   |
| ASUS All Series                | 7        | 2.4%    |
| ASUS PRIME B450M-GAMING/BR     | 4        | 1.37%   |
| Intel H81                      | 3        | 1.03%   |
| Gigabyte B550M DS3H AC         | 3        | 1.03%   |
| Dell OptiPlex 7040             | 3        | 1.03%   |
| ASUS PRIME A520M-E             | 3        | 1.03%   |
| Pegatron IPM41-D3              | 2        | 0.68%   |
| PCWare IPX1800G2               | 2        | 0.68%   |
| Intel H61                      | 2        | 0.68%   |
| Intel H55                      | 2        | 0.68%   |
| Intel B75                      | 2        | 0.68%   |
| Gigabyte H61M-S2-B3            | 2        | 0.68%   |
| Gigabyte H170N-WIFI            | 2        | 0.68%   |
| Dell OptiPlex 3050             | 2        | 0.68%   |
| Dell OptiPlex 3020             | 2        | 0.68%   |
| ASUS TUF Gaming B550M-PLUS     | 2        | 0.68%   |
| ASUS P8H61-M LX3 R2.0          | 2        | 0.68%   |
| ASUS P8H61-M LX3 PLUS R2.0     | 2        | 0.68%   |
| ASUS P8H61-M LE/BR             | 2        | 0.68%   |
| ASUS P5KPL-AM SE               | 2        | 0.68%   |
| ASUS M5A97 LE R2.0             | 2        | 0.68%   |
| ASUS M5A78L-M LX/BR            | 2        | 0.68%   |
| ASUS A88XM-A                   | 2        | 0.68%   |
| ASRock J4005B-ITX              | 2        | 0.68%   |
| YANYU N39SL                    | 1        | 0.34%   |
| Yanling YL-CLU6L-V1            | 1        | 0.34%   |
| Yanling NS-1U8L                | 1        | 0.34%   |
| Wistron ProLiant ML110 G6      | 1        | 0.34%   |
| ULTRATOP C2017-LIVA-ZE         | 1        | 0.34%   |
| T-bao MINI PC                  | 1        | 0.34%   |
| Supermicro 92.510.02134-3      | 1        | 0.34%   |
| Soyo SY-YL B550M               | 1        | 0.34%   |
| Semp Toshiba STI               | 1        | 0.34%   |
| Procomp Ind. Eletronica G41MXE | 1        | 0.34%   |
| Positivo Positivo Master D610  | 1        | 0.34%   |
| Positivo POS-PIQ77CL           | 1        | 0.34%   |
| Positivo POS-EAA75DE           | 1        | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| Unknown                   | 49       | 16.78%  |
| Dell OptiPlex             | 19       | 6.51%   |
| Techvision TVI7309X       | 13       | 4.45%   |
| ASUS PRIME                | 12       | 4.11%   |
| Intel Q3XXG4-P            | 10       | 3.42%   |
| Lenovo ThinkCentre        | 7        | 2.4%    |
| ASUS All                  | 7        | 2.4%    |
| ASUS P8H61-M              | 6        | 2.05%   |
| HP ProLiant               | 5        | 1.71%   |
| Gigabyte B550M            | 4        | 1.37%   |
| Dell Vostro               | 4        | 1.37%   |
| Dell Inspiron             | 4        | 1.37%   |
| ASUS TUF                  | 4        | 1.37%   |
| Itautec Infoway           | 3        | 1.03%   |
| Intel H81                 | 3        | 1.03%   |
| ASUS M5A97                | 3        | 1.03%   |
| ASUS M5A78L-M             | 3        | 1.03%   |
| Pegatron IPM41-D3         | 2        | 0.68%   |
| PCWare IPX1800G2          | 2        | 0.68%   |
| Intel H61                 | 2        | 0.68%   |
| Intel H55                 | 2        | 0.68%   |
| Intel B75                 | 2        | 0.68%   |
| HP Compaq                 | 2        | 0.68%   |
| Gigabyte H61M-S2-B3       | 2        | 0.68%   |
| Gigabyte H170N-WIFI       | 2        | 0.68%   |
| Gigabyte GA-78LMT-USB3    | 2        | 0.68%   |
| Gigabyte B450M            | 2        | 0.68%   |
| Dell Precision            | 2        | 0.68%   |
| ASUS P5KPL-AM             | 2        | 0.68%   |
| ASUS P5G41T-M             | 2        | 0.68%   |
| ASUS A88XM-A              | 2        | 0.68%   |
| ASRock J4005B-ITX         | 2        | 0.68%   |
| YANYU N39SL               | 1        | 0.34%   |
| Yanling YL-CLU6L-V1       | 1        | 0.34%   |
| Yanling NS-1U8L           | 1        | 0.34%   |
| Wistron ProLiant          | 1        | 0.34%   |
| ULTRATOP C2017-LIVA-ZE    | 1        | 0.34%   |
| T-bao MINI                | 1        | 0.34%   |
| Supermicro 92.510.02134-3 | 1        | 0.34%   |
| Soyo SY-YL                | 1        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2022    | 49       | 16.78%  |
| 2016    | 28       | 9.59%   |
| 2013    | 21       | 7.19%   |
| 2010    | 19       | 6.51%   |
| 2023    | 18       | 6.16%   |
| 2014    | 18       | 6.16%   |
| 2012    | 18       | 6.16%   |
| 2019    | 15       | 5.14%   |
| 2017    | 14       | 4.79%   |
| 2011    | 14       | 4.79%   |
| 2021    | 12       | 4.11%   |
| 2020    | 12       | 4.11%   |
| 2018    | 12       | 4.11%   |
| 2008    | 11       | 3.77%   |
| 2024    | 10       | 3.42%   |
| 2009    | 9        | 3.08%   |
| 2025    | 4        | 1.37%   |
| 2007    | 4        | 1.37%   |
| 2015    | 3        | 1.03%   |
| Unknown | 1        | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 292      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 292      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 127      | 41.78%  |
| 4.01-8.0    | 71       | 23.36%  |
| 16.01-24.0  | 65       | 21.38%  |
| 32.01-64.0  | 21       | 6.91%   |
| 2.01-3.0    | 9        | 2.96%   |
| 64.01-256.0 | 5        | 1.64%   |
| 3.01-4.0    | 4        | 1.32%   |
| 24.01-32.0  | 2        | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 164      | 53.95%  |
| 0.51-1.0   | 89       | 29.28%  |
| 1.01-2.0   | 35       | 11.51%  |
| 2.01-3.0   | 9        | 2.96%   |
| 4.01-8.0   | 3        | 0.99%   |
| Unknown    | 2        | 0.66%   |
| 16.01-24.0 | 1        | 0.33%   |
| 8.01-16.0  | 1        | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 201      | 64.63%  |
| 0      | 49       | 15.76%  |
| 2      | 33       | 10.61%  |
| 3      | 16       | 5.14%   |
| 4      | 6        | 1.93%   |
| 5      | 4        | 1.29%   |
| 7      | 1        | 0.32%   |
| 6      | 1        | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 245      | 83.33%  |
| Yes       | 49       | 16.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 289      | 98.97%  |
| No        | 3        | 1.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 240      | 81.63%  |
| Yes       | 54       | 18.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 258      | 87.76%  |
| Yes       | 36       | 12.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Brazil  | 292      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Sao Paulo               | 42       | 12.88%  |
| Rio de Janeiro          | 20       | 6.13%   |
| Curitiba                | 16       | 4.91%   |
| SГЈo Paulo            | 12       | 3.68%   |
| Sao José dos Campos    | 9        | 2.76%   |
| Porto Alegre            | 9        | 2.76%   |
| Jaraguá do Sul         | 6        | 1.84%   |
| Sao Jose do Rio Preto   | 5        | 1.53%   |
| Osasco                  | 5        | 1.53%   |
| Maringá                | 5        | 1.53%   |
| Campinas                | 5        | 1.53%   |
| Brasília               | 5        | 1.53%   |
| Pouso Alegre            | 4        | 1.23%   |
| Joinville               | 4        | 1.23%   |
| Fortaleza               | 4        | 1.23%   |
| Belo Horizonte          | 4        | 1.23%   |
| Sorocaba                | 3        | 0.92%   |
| SÃ£o Paulo            | 3        | 0.92%   |
| Sao Bernardo do Campo   | 3        | 0.92%   |
| Salvador                | 3        | 0.92%   |
| Novo Hamburgo           | 3        | 0.92%   |
| Londrina                | 3        | 0.92%   |
| Cuiabá                 | 3        | 0.92%   |
| Blumenau                | 3        | 0.92%   |
| Valparaiso de Goias     | 2        | 0.61%   |
| Suzano                  | 2        | 0.61%   |
| Sao Leopoldo            | 2        | 0.61%   |
| Santos                  | 2        | 0.61%   |
| Santa Barbara d'Oeste   | 2        | 0.61%   |
| RondonГіpolis         | 2        | 0.61%   |
| Rio Claro               | 2        | 0.61%   |
| Recife                  | 2        | 0.61%   |
| Praia Grande            | 2        | 0.61%   |
| Pirapora                | 2        | 0.61%   |
| Manaus                  | 2        | 0.61%   |
| Jaboatao dos Guararapes | 2        | 0.61%   |
| Itaperuna               | 2        | 0.61%   |
| Guarulhos               | 2        | 0.61%   |
| Florianópolis          | 2        | 0.61%   |
| Cruzeiro do Sul         | 2        | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC                                | 56       | 76     | 17.34%  |
| Kingston                           | 52       | 91     | 16.1%   |
| Seagate                            | 49       | 89     | 15.17%  |
| Samsung Electronics                | 31       | 44     | 9.6%    |
| China                              | 15       | 20     | 4.64%   |
| SanDisk                            | 14       | 18     | 4.33%   |
| KingSpec                           | 10       | 16     | 3.1%    |
| Toshiba                            | 9        | 12     | 2.79%   |
| Hoodisk                            | 9        | 9      | 2.79%   |
| A-DATA Technology                  | 9        | 12     | 2.79%   |
| Crucial                            | 8        | 11     | 2.48%   |
| Silicon Motion                     | 7        | 8      | 2.17%   |
| XrayDisk                           | 5        | 5      | 1.55%   |
| HGST                               | 5        | 7      | 1.55%   |
| Hitachi                            | 4        | 8      | 1.24%   |
| Gigabyte Technology                | 3        | 6      | 0.93%   |
| Fanxiang                           | 3        | 4      | 0.93%   |
| tecmiyo                            | 2        | 4      | 0.62%   |
| PNY                                | 2        | 2      | 0.62%   |
| NTC                                | 2        | 2      | 0.62%   |
| Micron Technology                  | 2        | 2      | 0.62%   |
| Maxtor                             | 2        | 2      | 0.62%   |
| Intel                              | 2        | 6      | 0.62%   |
| XUNZHE                             | 1        | 1      | 0.31%   |
| Vaseky                             | 1        | 1      | 0.31%   |
| TGT                                | 1        | 1      | 0.31%   |
| Teelkoou                           | 1        | 1      | 0.31%   |
| SMI                                | 1        | 1      | 0.31%   |
| Silicon                            | 1        | 1      | 0.31%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.31%   |
| NVMe                               | 1        | 2      | 0.31%   |
| Netac                              | 1        | 1      | 0.31%   |
| MACROVIP                           | 1        | 1      | 0.31%   |
| LITEON                             | 1        | 1      | 0.31%   |
| Lexar                              | 1        | 1      | 0.31%   |
| Kston                              | 1        | 1      | 0.31%   |
| Innodisk                           | 1        | 1      | 0.31%   |
| Indilinx                           | 1        | 2      | 0.31%   |
| Hewlett-Packard                    | 1        | 1      | 0.31%   |
| Faspeed                            | 1        | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB         | 18       | 5.17%   |
| Kingston SA400S37120G 120GB         | 11       | 3.16%   |
| Seagate ST500DM002-1BD142 500GB     | 10       | 2.87%   |
| Kingston SA400S37480G 480GB         | 9        | 2.59%   |
| SanDisk SSD PLUS 120GB              | 7        | 2.01%   |
| Seagate ST1000DM010-2EP102 1TB      | 6        | 1.72%   |
| Hoodisk SSD 64GB                    | 6        | 1.72%   |
| Samsung SSD 870 EVO 250GB           | 5        | 1.44%   |
| Samsung HD322HJ 320GB               | 5        | 1.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4        | 1.15%   |
| Samsung HD161HJ 160GB               | 4        | 1.15%   |
| WDC WD10EZEX-00RKKA0 1TB            | 3        | 0.86%   |
| Seagate ST4000DM000-1F2168 4TB      | 3        | 0.86%   |
| Seagate ST2000DM006-2DM164 2TB      | 3        | 0.86%   |
| Seagate ST1000DM003-1CH162 1TB      | 3        | 0.86%   |
| Samsung HD502HJ 500GB               | 3        | 0.86%   |
| Samsung HD103SJ 1TB                 | 3        | 0.86%   |
| KingSpec MT-128 128GB               | 3        | 0.86%   |
| Crucial CT240BX500SSD1 240GB        | 3        | 0.86%   |
| Crucial CT120BX500SSD1 120GB        | 3        | 0.86%   |
| China SATA SSD 120GB                | 3        | 0.86%   |
| A-DATA SU630 240GB                  | 3        | 0.86%   |
| XrayDisk 1TB SSD                    | 2        | 0.57%   |
| WDC WDS120G2G0A-00JH30 120GB        | 2        | 0.57%   |
| WDC WD80EFPX-68C4ZN0 8TB            | 2        | 0.57%   |
| WDC WD5000LPLX-75ZNTT0 500GB        | 2        | 0.57%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 2        | 0.57%   |
| WDC WD5000AAKX-003CA0 500GB         | 2        | 0.57%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 2        | 0.57%   |
| WDC WD2500BEVT-75ZCT2 250GB         | 2        | 0.57%   |
| WDC WD10EZEX-00WN4A0 1TB            | 2        | 0.57%   |
| Toshiba MQ01ABF050 500GB            | 2        | 0.57%   |
| Silicon Motion NVME SSD 128GB       | 2        | 0.57%   |
| Seagate ST500LT012-9WS142 500GB     | 2        | 0.57%   |
| Seagate ST500DM002-1SB10A 500GB     | 2        | 0.57%   |
| SanDisk SSD PLUS 240GB              | 2        | 0.57%   |
| SanDisk SDSSDA240G 240GB            | 2        | 0.57%   |
| SanDisk SDSSDA120G 120GB            | 2        | 0.57%   |
| Samsung HD161GJ 160GB               | 2        | 0.57%   |
| Samsung HD081GJ 80GB                | 2        | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC                                | 50       | 67     | 34.97%  |
| Seagate                            | 49       | 89     | 34.27%  |
| Samsung Electronics                | 21       | 29     | 14.69%  |
| Toshiba                            | 9        | 12     | 6.29%   |
| Hitachi                            | 4        | 8      | 2.8%    |
| HGST                               | 4        | 5      | 2.8%    |
| Maxtor                             | 2        | 2      | 1.4%    |
| SMI                                | 1        | 1      | 0.7%    |
| Product:              USB DISK 2.0 | 1        | 1      | 0.7%    |
| NVMe                               | 1        | 2      | 0.7%    |
| Hewlett-Packard                    | 1        | 1      | 0.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 48       | 87     | 29.27%  |
| China               | 15       | 20     | 9.15%   |
| SanDisk             | 14       | 18     | 8.54%   |
| KingSpec            | 10       | 15     | 6.1%    |
| Hoodisk             | 9        | 9      | 5.49%   |
| A-DATA Technology   | 9        | 12     | 5.49%   |
| Samsung Electronics | 8        | 9      | 4.88%   |
| Crucial             | 8        | 11     | 4.88%   |
| WDC                 | 6        | 8      | 3.66%   |
| XrayDisk            | 5        | 5      | 3.05%   |
| Gigabyte Technology | 3        | 6      | 1.83%   |
| tecmiyo             | 2        | 4      | 1.22%   |
| PNY                 | 2        | 2      | 1.22%   |
| NTC                 | 2        | 2      | 1.22%   |
| Micron Technology   | 2        | 2      | 1.22%   |
| Intel               | 2        | 6      | 1.22%   |
| XUNZHE              | 1        | 1      | 0.61%   |
| Vaseky              | 1        | 1      | 0.61%   |
| TGT                 | 1        | 1      | 0.61%   |
| Teelkoou            | 1        | 1      | 0.61%   |
| Silicon             | 1        | 1      | 0.61%   |
| Netac               | 1        | 1      | 0.61%   |
| MACROVIP            | 1        | 1      | 0.61%   |
| LITEON              | 1        | 1      | 0.61%   |
| Lexar               | 1        | 1      | 0.61%   |
| Kston               | 1        | 1      | 0.61%   |
| Innodisk            | 1        | 1      | 0.61%   |
| Indilinx            | 1        | 2      | 0.61%   |
| HGST                | 1        | 2      | 0.61%   |
| Faspeed             | 1        | 1      | 0.61%   |
| Fanxiang            | 1        | 1      | 0.61%   |
| Drevo               | 1        | 8      | 0.61%   |
| Corsair             | 1        | 1      | 0.61%   |
| BR                  | 1        | 2      | 0.61%   |
| Apacer              | 1        | 1      | 0.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 150      | 245    | 52.82%  |
| HDD  | 116      | 217    | 40.85%  |
| NVMe | 18       | 24     | 6.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 232      | 462    | 92.8%   |
| NVMe | 18       | 24     | 7.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 215      | 368    | 80.22%  |
| 0.51-1.0   | 31       | 49     | 11.57%  |
| 1.01-2.0   | 14       | 31     | 5.22%   |
| 3.01-4.0   | 4        | 10     | 1.49%   |
| 4.01-10.0  | 3        | 3      | 1.12%   |
| 20.01-50.0 | 1        | 1      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 131      | 40.94%  |
| 251-500        | 59       | 18.44%  |
| 1-20           | 43       | 13.44%  |
| 51-100         | 39       | 12.19%  |
| 21-50          | 22       | 6.88%   |
| 501-1000       | 17       | 5.31%   |
| 1001-2000      | 4        | 1.25%   |
| More than 3000 | 2        | 0.63%   |
| 2001-3000      | 2        | 0.63%   |
| Unknown        | 1        | 0.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 271      | 90.64%  |
| 21-50     | 16       | 5.35%   |
| 101-250   | 5        | 1.67%   |
| 501-1000  | 2        | 0.67%   |
| 51-100    | 2        | 0.67%   |
| 2001-3000 | 1        | 0.33%   |
| 1001-2000 | 1        | 0.33%   |
| Unknown   | 1        | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Desktops | Drives | Percent |
|-------------------------------------------|----------|--------|---------|
| Samsung Electronics HD322HJ 320GB         | 4        | 5      | 4.6%    |
| Seagate ST500DM002-1BD142 500GB           | 3        | 4      | 3.45%   |
| Samsung Electronics HD161HJ 160GB         | 3        | 3      | 3.45%   |
| WDC WD5000LPLX-75ZNTT0 500GB              | 2        | 2      | 2.3%    |
| WDC WD5000AAKX-003CA0 500GB               | 2        | 4      | 2.3%    |
| WDC WD10EZEX-00RKKA0 1TB                  | 2        | 2      | 2.3%    |
| Seagate ST500LT012-9WS142 500GB           | 2        | 4      | 2.3%    |
| Kingston SV300S37A60G 64GB                | 2        | 2      | 2.3%    |
| Kingston SA400S37120G 120GB               | 2        | 2      | 2.3%    |
| KingSpec P4-120 120GB                     | 2        | 3      | 2.3%    |
| XrayDisk SSD 240GB                        | 1        | 1      | 1.15%   |
| WDC WD5000LPVX-22V0TT0 500GB              | 1        | 1      | 1.15%   |
| WDC WD5000AVVS-63H0B1 500GB               | 1        | 1      | 1.15%   |
| WDC WD5000AAKX-75U6AA0 500GB              | 1        | 1      | 1.15%   |
| WDC WD5000AAKX-603CA0 500GB               | 1        | 2      | 1.15%   |
| WDC WD5000AAKX-08ERMA0 500GB              | 1        | 1      | 1.15%   |
| WDC WD5000AAKX-00U6AA0 500GB              | 1        | 1      | 1.15%   |
| WDC WD5000AAKX-00ERMA0 500GB              | 1        | 1      | 1.15%   |
| WDC WD5000AAKS-08V0A0 500GB               | 1        | 1      | 1.15%   |
| WDC WD5000AAKS-00UU3A0 500GB              | 1        | 1      | 1.15%   |
| WDC WD3200LPVX-22V0TT0 320GB              | 1        | 1      | 1.15%   |
| WDC WD3200BEVT-11ZCT0 320GB               | 1        | 2      | 1.15%   |
| WDC WD3200BEVT-00A0RT0 233GB              | 1        | 1      | 1.15%   |
| WDC WD3200AAKS-00UU3A0 320GB              | 1        | 1      | 1.15%   |
| WDC WD3200AAJS-56M0A0 320GB               | 1        | 1      | 1.15%   |
| WDC WD3200AAJS-00YZCA0 320GB              | 1        | 1      | 1.15%   |
| WDC WD2502ABYS-18B7A0 250GB               | 1        | 1      | 1.15%   |
| WDC WD2500AAJS-75M0A0 250GB               | 1        | 1      | 1.15%   |
| WDC WD10PURX-64E5EY0 1TB                  | 1        | 1      | 1.15%   |
| WDC WD10EADS-65M2BX 1TB                   | 1        | 1      | 1.15%   |
| Toshiba MQ01ABD050 500GB                  | 1        | 1      | 1.15%   |
| Toshiba MK8052GSX 80GB                    | 1        | 1      | 1.15%   |
| Toshiba MK1255GSX H 120GB                 | 1        | 1      | 1.15%   |
| tecmiyo SSD MSATA 64GB                    | 1        | 2      | 1.15%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB | 1        | 1      | 1.15%   |
| Seagate ST9320325AS 320GB                 | 1        | 1      | 1.15%   |
| Seagate ST9160314AS 160GB                 | 1        | 1      | 1.15%   |
| Seagate ST500LM021-1KJ152 500GB           | 1        | 1      | 1.15%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1        | 1      | 1.15%   |
| Seagate ST500DM002-1BC142 500GB           | 1        | 1      | 1.15%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 29     | 27.38%  |
| Seagate             | 15       | 26     | 17.86%  |
| Samsung Electronics | 12       | 15     | 14.29%  |
| Kingston            | 6        | 7      | 7.14%   |
| KingSpec            | 5        | 6      | 5.95%   |
| Toshiba             | 3        | 3      | 3.57%   |
| Hitachi             | 3        | 7      | 3.57%   |
| HGST                | 3        | 4      | 3.57%   |
| SanDisk             | 2        | 2      | 2.38%   |
| Micron Technology   | 2        | 2      | 2.38%   |
| Maxtor              | 2        | 2      | 2.38%   |
| A-DATA Technology   | 2        | 2      | 2.38%   |
| XrayDisk            | 1        | 1      | 1.19%   |
| tecmiyo             | 1        | 2      | 1.19%   |
| Silicon Motion      | 1        | 1      | 1.19%   |
| Netac               | 1        | 1      | 1.19%   |
| Corsair             | 1        | 1      | 1.19%   |
| China               | 1        | 1      | 1.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 29     | 38.33%  |
| Seagate             | 15       | 26     | 25%     |
| Samsung Electronics | 12       | 15     | 20%     |
| Toshiba             | 3        | 3      | 5%      |
| Hitachi             | 3        | 7      | 5%      |
| Maxtor              | 2        | 2      | 3.33%   |
| HGST                | 2        | 2      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 55       | 84     | 69.62%  |
| SSD  | 23       | 27     | 29.11%  |
| NVMe | 1        | 1      | 1.27%   |

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
| Works    | 194      | 353    | 68.31%  |
| Malfunc  | 75       | 112    | 26.41%  |
| Detected | 12       | 17     | 4.23%   |
| Failed   | 3        | 4      | 1.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel                                   | 231      | 68.14%  |
| AMD                                     | 50       | 14.75%  |
| Silicon Motion                          | 16       | 4.72%   |
| Kingston Technology Company             | 8        | 2.36%   |
| Samsung Electronics                     | 5        | 1.47%   |
| Nvidia                                  | 4        | 1.18%   |
| SanDisk                                 | 3        | 0.88%   |
| JMicron Technology                      | 3        | 0.88%   |
| ADATA Technology                        | 3        | 0.88%   |
| Solid State Storage Technology          | 2        | 0.59%   |
| SK hynix                                | 2        | 0.59%   |
| Phison Electronics                      | 2        | 0.59%   |
| MAXIO Technology (Hangzhou)             | 2        | 0.59%   |
| Shenzhen Unionmemory Information System | 1        | 0.29%   |
| Realtek Semiconductor                   | 1        | 0.29%   |
| Netac Technology                        | 1        | 0.29%   |
| Lite-On Technology                      | 1        | 0.29%   |
| Integrated Technology Express           | 1        | 0.29%   |
| Hewlett-Packard                         | 1        | 0.29%   |
| ASMedia Technology                      | 1        | 0.29%   |
| Adaptec                                 | 1        | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 26       | 6.37%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 22       | 5.39%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 18       | 4.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 17       | 4.17%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 17       | 4.17%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 16       | 3.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 3.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14       | 3.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13       | 3.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13       | 3.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13       | 3.19%   |
| AMD 500 Series Chipset SATA Controller                                                  | 13       | 3.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 12       | 2.94%   |
| Intel Alder Lake-N SATA AHCI Controller                                                 | 10       | 2.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 2.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 1.96%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 1.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7        | 1.72%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 1.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 1.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 6        | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 1.23%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 0.98%   |
| Nvidia MCP61 IDE                                                                        | 4        | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4        | 0.98%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.98%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 4        | 0.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 0.74%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 0.74%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 0.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3        | 0.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3        | 0.74%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 0.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 0.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.49%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 2        | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 220      | 63.58%  |
| IDE  | 69       | 19.94%  |
| NVMe | 47       | 13.58%  |
| RAID | 9        | 2.6%    |
| SCSI | 1        | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 239      | 81.29%  |
| AMD    | 54       | 18.37%  |
| ARM    | 1        | 0.34%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Celeron J4125 CPU @ 2.00GHz           | 19       | 6.4%    |
| Intel Celeron N5105 @ 2.00GHz               | 14       | 4.71%   |
| Intel N100                                  | 10       | 3.37%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 6        | 2.02%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 5        | 1.68%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 5        | 1.68%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 5        | 1.68%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 5        | 1.68%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 1.35%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 4        | 1.35%   |
| Intel Pentium Silver N6005 @ 2.00GHz        | 3        | 1.01%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.01%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 3        | 1.01%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 1.01%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 1.01%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 3        | 1.01%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 3        | 1.01%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 3        | 1.01%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.01%   |
| Intel Core i3-2100 CPU                      | 3        | 1.01%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 3        | 1.01%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.01%   |
| Intel Core 2 Duo                            | 3        | 1.01%   |
| AMD FX-8320E Eight-Core Processor           | 3        | 1.01%   |
| AMD FX-6300 Six-Core Processor              | 3        | 1.01%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 2        | 0.67%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 0.67%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2        | 0.67%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 0.67%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 0.67%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.67%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 0.67%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 0.67%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 0.67%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 0.67%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 0.67%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 2        | 0.67%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 0.67%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 0.67%   |
| Intel Core 2 Duo CPU                        | 2        | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 60       | 20.27%  |
| Intel Core i5           | 43       | 14.53%  |
| Intel Core i3           | 41       | 13.85%  |
| Intel Xeon              | 20       | 6.76%   |
| Other                   | 17       | 5.74%   |
| Intel Core 2 Duo        | 17       | 5.74%   |
| Intel Core i7           | 16       | 5.41%   |
| AMD Ryzen 5             | 14       | 4.73%   |
| AMD FX                  | 12       | 4.05%   |
| AMD Ryzen 7             | 8        | 2.7%    |
| Intel Pentium Dual-Core | 7        | 2.36%   |
| Intel Pentium           | 7        | 2.36%   |
| Intel Core 2 Quad       | 5        | 1.69%   |
| Intel Atom              | 4        | 1.35%   |
| Intel Pentium Silver    | 3        | 1.01%   |
| AMD Ryzen 3             | 3        | 1.01%   |
| AMD Athlon 64 X2        | 3        | 1.01%   |
| AMD Ryzen 3 PRO         | 2        | 0.68%   |
| AMD A10                 | 2        | 0.68%   |
| Intel Pentium Dual      | 1        | 0.34%   |
| Intel Core 2            | 1        | 0.34%   |
| ARM Cortex              | 1        | 0.34%   |
| AMD Turion II Neo       | 1        | 0.34%   |
| AMD Ryzen 5 PRO         | 1        | 0.34%   |
| AMD PRO A8              | 1        | 0.34%   |
| AMD Phenom              | 1        | 0.34%   |
| AMD E                   | 1        | 0.34%   |
| AMD C-60                | 1        | 0.34%   |
| AMD Athlon II X2        | 1        | 0.34%   |
| AMD Athlon              | 1        | 0.34%   |
| AMD A8                  | 1        | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 135      | 45.3%   |
| 2       | 93       | 31.21%  |
| 6       | 22       | 7.38%   |
| 8       | 19       | 6.38%   |
| Unknown | 12       | 4.03%   |
| 12      | 10       | 3.36%   |
| 16      | 4        | 1.34%   |
| 20      | 1        | 0.34%   |
| 14      | 1        | 0.34%   |
| 1       | 1        | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 290      | 99.32%  |
| 2       | 1        | 0.34%   |
| Unknown | 1        | 0.34%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 194      | 65.54%  |
| 2       | 90       | 30.41%  |
| Unknown | 12       | 4.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 41       | 13.8%   |
| Haswell       | 29       | 9.76%   |
| Penryn        | 27       | 9.09%   |
| KabyLake      | 25       | 8.42%   |
| Goldmont plus | 22       | 7.41%   |
| IvyBridge     | 20       | 6.73%   |
| SandyBridge   | 19       | 6.4%    |
| Zen 3         | 12       | 4.04%   |
| Silvermont    | 12       | 4.04%   |
| Skylake       | 10       | 3.37%   |
| Westmere      | 8        | 2.69%   |
| Piledriver    | 8        | 2.69%   |
| Zen+          | 7        | 2.36%   |
| Nehalem       | 7        | 2.36%   |
| Core          | 7        | 2.36%   |
| Broadwell     | 6        | 2.02%   |
| Zen 2         | 5        | 1.68%   |
| Zen           | 5        | 1.68%   |
| CometLake     | 5        | 1.68%   |
| Steamroller   | 4        | 1.35%   |
| Bulldozer     | 4        | 1.35%   |
| K8 Hammer     | 3        | 1.01%   |
| K10           | 3        | 1.01%   |
| Goldmont      | 3        | 1.01%   |
| Bonnell       | 2        | 0.67%   |
| Bobcat        | 2        | 0.67%   |
| TigerLake     | 1        | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 200      | 68.49%  |
| AMD                        | 53       | 18.15%  |
| Nvidia                     | 32       | 10.96%  |
| Matrox Electronics Systems | 6        | 2.05%   |
| ASPEED Technology          | 1        | 0.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                         | 22       | 7.41%   |
| Intel JasperLake [UHD Graphics]                                             | 20       | 6.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 17       | 5.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 13       | 4.38%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 13       | 4.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 12       | 4.04%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 12       | 4.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 12       | 4.04%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 11       | 3.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 11       | 3.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 9        | 3.03%   |
| Intel Core Processor Integrated Graphics Controller                         | 7        | 2.36%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7        | 2.36%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 6        | 2.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 6        | 2.02%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.35%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                    | 4        | 1.35%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 1.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 1.35%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 1.35%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 1.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 1.35%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.01%   |
| Matrox Electronics Systems MGA G200EH                                       | 3        | 1.01%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 3        | 1.01%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 3        | 1.01%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 1.01%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 1.01%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.01%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 0.67%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 0.67%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2        | 0.67%   |
| Intel Skylake-DT/H GT2 [HD Graphics P530]                                   | 2        | 0.67%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                | 2        | 0.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 0.67%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                     | 2        | 0.67%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                     | 2        | 0.67%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 2        | 0.67%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 0.34%   |
| Nvidia GT215M [GeForce GT 335M]                                             | 1        | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 190      | 64.19%  |
| 1 x AMD        | 50       | 16.89%  |
| 1 x Nvidia     | 31       | 10.47%  |
| Other          | 8        | 2.7%    |
| 2 x Intel      | 6        | 2.03%   |
| 1 x Matrox     | 6        | 2.03%   |
| Intel + AMD    | 3        | 1.01%   |
| Intel + Nvidia | 1        | 0.34%   |
| 1 x ASPEED     | 1        | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 269      | 91.19%  |
| Proprietary | 18       | 6.1%    |
| Unknown     | 8        | 2.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 247      | 83.16%  |
| 1.01-2.0   | 13       | 4.38%   |
| 0.51-1.0   | 13       | 4.38%   |
| 3.01-4.0   | 11       | 3.7%    |
| 0.01-0.5   | 8        | 2.69%   |
| 7.01-8.0   | 4        | 1.35%   |
| 2.01-3.0   | 1        | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 23       | 31.94%  |
| Samsung Electronics | 17       | 23.61%  |
| Philips             | 6        | 8.33%   |
| AOC                 | 5        | 6.94%   |
| Unknown (XXX)       | 2        | 2.78%   |
| Lenovo              | 2        | 2.78%   |
| Acer                | 2        | 2.78%   |
| VIZTA               | 1        | 1.39%   |
| VIE                 | 1        | 1.39%   |
| TXD                 | 1        | 1.39%   |
| Semp Toshiba        | 1        | 1.39%   |
| Panasonic           | 1        | 1.39%   |
| MStar               | 1        | 1.39%   |
| LRX                 | 1        | 1.39%   |
| LG Electronics      | 1        | 1.39%   |
| LG Display          | 1        | 1.39%   |
| ITE                 | 1        | 1.39%   |
| Hewlett-Packard     | 1        | 1.39%   |
| Dell                | 1        | 1.39%   |
| BOE                 | 1        | 1.39%   |
| ASUSTek Computer    | 1        | 1.39%   |
| AGO                 | 1        | 1.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Unknown (XXX) Beyond TV XXX9221 1920x1080 1210x680mm 54.6-inch       | 2        | 2.6%    |
| Samsung Electronics SyncMaster SAM0601 1600x900                      | 2        | 2.6%    |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch  | 2        | 2.6%    |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 2        | 2.6%    |
| VIZTA VGA JRY1900 1440x900 410x260mm 19.1-inch                       | 1        | 1.3%    |
| VIE E195 VIE1950 1600x900 410x280mm 19.5-inch                        | 1        | 1.3%    |
| TXD VGA TXD009A 1440x900 330x210mm 15.4-inch                         | 1        | 1.3%    |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch            | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch  | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch  | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                     | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM058F 1920x1080 480x270mm 21.7-inch | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM04E4 1600x900 440x250mm 19.9-inch  | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch  | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch  | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM0117 1280x1024 310x230mm 15.2-inch | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch  | 1        | 1.3%    |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 440x250mm 19.9-inch | 1        | 1.3%    |
| Samsung Electronics S23C550 SAM0A42 1920x1080 510x290mm 23.1-inch    | 1        | 1.3%    |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch     | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SMT27A550 1920x1080                  | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM0678 1360x768                     | 1        | 1.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 1        | 1.3%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 1        | 1.3%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch              | 1        | 1.3%    |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch              | 1        | 1.3%    |
| Philips LCD Monitor PHL2051 1600x900 440x250mm 19.9-inch             | 1        | 1.3%    |
| Philips 221EL PHLC056 1920x1080 480x270mm 21.7-inch                  | 1        | 1.3%    |
| Philips 202EL PHLC05C 1600x900 440x250mm 19.9-inch                   | 1        | 1.3%    |
| Panasonic TV MEIC136 1280x720 698x392mm 31.5-inch                    | 1        | 1.3%    |
| MStar TSB LEDTV MST0030 1920x1080 1150x650mm 52.0-inch               | 1        | 1.3%    |
| LRX '' LRX2281 1280x960 5x4mm 0.3-inch                               | 1        | 1.3%    |
| LG Electronics LCD Monitor LG ULTRAWIDE 3640x1920                    | 1        | 1.3%    |
| LG Electronics LCD Monitor 23MP55                                    | 1        | 1.3%    |
| LG Display LCD Monitor LGD020C 1600x900 350x190mm 15.7-inch          | 1        | 1.3%    |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 480x270mm 21.7-inch             | 1        | 1.3%    |
| Lenovo L197 Wide LEN1152 1440x900 410x260mm 19.1-inch                | 1        | 1.3%    |
| ITE DP2VGA V235 ITE6516 1920x1080 600x340mm 27.2-inch                | 1        | 1.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 31       | 42.47%  |
| 1600x900 (HD+)     | 10       | 13.7%   |
| 1366x768 (WXGA)    | 8        | 10.96%  |
| 1440x900 (WXGA+)   | 5        | 6.85%   |
| 1360x768           | 4        | 5.48%   |
| 1280x1024 (SXGA)   | 4        | 5.48%   |
| 2560x1080          | 3        | 4.11%   |
| 1024x768 (XGA)     | 2        | 2.74%   |
| 3840x2160 (4K)     | 1        | 1.37%   |
| 3640x1920          | 1        | 1.37%   |
| 1680x1050 (WSXGA+) | 1        | 1.37%   |
| 1280x960           | 1        | 1.37%   |
| 1280x720 (HD)      | 1        | 1.37%   |
| Unknown            | 1        | 1.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 12       | 16.22%  |
| 21      | 12       | 16.22%  |
| 19      | 12       | 16.22%  |
| 18      | 7        | 9.46%   |
| Unknown | 7        | 9.46%   |
| 15      | 5        | 6.76%   |
| 34      | 3        | 4.05%   |
| 54      | 2        | 2.7%    |
| 31      | 2        | 2.7%    |
| 27      | 2        | 2.7%    |
| 20      | 2        | 2.7%    |
| 17      | 2        | 2.7%    |
| 14      | 2        | 2.7%    |
| 52      | 1        | 1.35%   |
| 24      | 1        | 1.35%   |
| 13      | 1        | 1.35%   |
| 0       | 1        | 1.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 32       | 43.84%  |
| 501-600     | 14       | 19.18%  |
| 301-350     | 7        | 9.59%   |
| Unknown     | 7        | 9.59%   |
| 701-800     | 3        | 4.11%   |
| 201-300     | 3        | 4.11%   |
| 1001-1500   | 3        | 4.11%   |
| 601-700     | 2        | 2.74%   |
| 351-400     | 1        | 1.37%   |
| 1-100       | 1        | 1.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 49       | 70%     |
| 16/10   | 5        | 7.14%   |
| 5/4     | 4        | 5.71%   |
| 4/3     | 4        | 5.71%   |
| 21/9    | 3        | 4.29%   |
| Unknown | 3        | 4.29%   |
| 3/2     | 2        | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 23       | 31.51%  |
| 151-200        | 15       | 20.55%  |
| 141-150        | 9        | 12.33%  |
| Unknown        | 8        | 10.96%  |
| 351-500        | 5        | 6.85%   |
| 101-110        | 4        | 5.48%   |
| More than 1000 | 3        | 4.11%   |
| 91-100         | 3        | 4.11%   |
| 301-350        | 2        | 2.74%   |
| 111-120        | 1        | 1.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 41       | 56.16%  |
| 101-120       | 17       | 23.29%  |
| Unknown       | 7        | 9.59%   |
| 1-50          | 5        | 6.85%   |
| More than 240 | 1        | 1.37%   |
| 161-240       | 1        | 1.37%   |
| 121-160       | 1        | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 216      | 73.22%  |
| 1     | 72       | 24.41%  |
| 2     | 7        | 2.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 169      | 43.11%  |
| Realtek Semiconductor      | 167      | 42.6%   |
| Broadcom                   | 16       | 4.08%   |
| Qualcomm Atheros           | 13       | 3.32%   |
| D-Link System              | 5        | 1.28%   |
| Ralink                     | 4        | 1.02%   |
| IMC Networks               | 3        | 0.77%   |
| Ralink Technology          | 2        | 0.51%   |
| Edimax Technology          | 2        | 0.51%   |
| ZTE WCDMA Technologies MSM | 1        | 0.26%   |
| TP-Link                    | 1        | 0.26%   |
| STMicroelectronics         | 1        | 0.26%   |
| Samsung Electronics        | 1        | 0.26%   |
| Mellanox Technologies      | 1        | 0.26%   |
| MediaTek                   | 1        | 0.26%   |
| ICS Advent                 | 1        | 0.26%   |
| Dell                       | 1        | 0.26%   |
| Arduino SA                 | 1        | 0.26%   |
| Aquantia                   | 1        | 0.26%   |
| 3Com                       | 1        | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 133      | 28.48%  |
| Intel Ethernet Controller I225-V                                              | 29       | 6.21%   |
| Intel Ethernet Controller I226-V                                              | 27       | 5.78%   |
| Intel I211 Gigabit Network Connection                                         | 20       | 4.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 18       | 3.85%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 16       | 3.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 9        | 1.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 9        | 1.93%   |
| Intel 82574L Gigabit Network Connection                                       | 9        | 1.93%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 8        | 1.71%   |
| Intel I350 Gigabit Network Connection                                         | 8        | 1.71%   |
| Intel 82576 Gigabit Network Connection                                        | 8        | 1.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 1.5%    |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 1.07%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 1.07%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 5        | 1.07%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 5        | 1.07%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                  | 4        | 0.86%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 4        | 0.86%   |
| Intel Ethernet Connection I217-LM                                             | 4        | 0.86%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 0.86%   |
| Intel 82580 Gigabit Network Connection                                        | 4        | 0.86%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 4        | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 3        | 0.64%   |
| Intel Wireless 3165                                                           | 3        | 0.64%   |
| Intel I210 Gigabit Network Connection                                         | 3        | 0.64%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 0.64%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3        | 0.64%   |
| Intel 82583V Gigabit Network Connection                                       | 3        | 0.64%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 0.64%   |
| Intel 82578DM Gigabit Network Connection                                      | 3        | 0.64%   |
| Intel 82578DC Gigabit Network Connection                                      | 3        | 0.64%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.64%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 3        | 0.64%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 3        | 0.64%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                          | 2        | 0.43%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 2        | 0.43%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 2        | 0.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 22       | 37.93%  |
| Realtek Semiconductor | 18       | 31.03%  |
| Ralink                | 4        | 6.9%    |
| Qualcomm Atheros      | 4        | 6.9%    |
| IMC Networks          | 3        | 5.17%   |
| Ralink Technology     | 2        | 3.45%   |
| Edimax Technology     | 2        | 3.45%   |
| TP-Link               | 1        | 1.72%   |
| Dell                  | 1        | 1.72%   |
| D-Link System         | 1        | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                                              | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                           | 9        | 15.25%  |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                                                       | 4        | 6.78%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                                          | 4        | 6.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                                                | 3        | 5.08%   |
| Intel Wireless 3165                                                                                                | 3        | 5.08%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                                               | 3        | 5.08%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                                               | 2        | 3.39%   |
| Ralink RT2561/RT61 rev B 802.11g                                                                                   | 2        | 3.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                                   | 2        | 3.39%   |
| Intel Wireless 8260                                                                                                | 2        | 3.39%   |
| Intel Wireless 7265                                                                                                | 2        | 3.39%   |
| Intel Wireless 7260                                                                                                | 2        | 3.39%   |
| Intel Wi-Fi 6 AX200                                                                                                | 2        | 3.39%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                                         | 1        | 1.69%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                                              | 1        | 1.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                                         | 1        | 1.69%   |
| Realtek RTL8187SE Wireless LAN Controller                                                                          | 1        | 1.69%   |
| Ralink RT5370 Wireless Adapter                                                                                     | 1        | 1.69%   |
| Ralink MT7601U Wireless Adapter                                                                                    | 1        | 1.69%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                                                    | 1        | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                         | 1        | 1.69%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                                            | 1        | 1.69%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                                     | 1        | 1.69%   |
| Intel Jasper Lake PCH CNVi WiFi                                                                                    | 1        | 1.69%   |
| Intel Centrino Advanced-N 6235                                                                                     | 1        | 1.69%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                                                   | 1        | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                   | 1        | 1.69%   |
| Intel Alder Lake-N PCH CNVi WiFi                                                                                   | 1        | 1.69%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                                                     | 1        | 1.69%   |
| Edimax AC600 Wireless LAN USB Adapter                                                                              | 1        | 1.69%   |
| Dell Wireless 5808 Mobile Broadband (Sierra Wireless Mini PCIE, 4G UMTS,HSDPA,HSPA+,LTE,1xRTT,EVDO Rev A,GSM,GPRS) | 1        | 1.69%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]                                               | 1        | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 164      | 45.68%  |
| Intel                      | 160      | 44.57%  |
| Broadcom                   | 16       | 4.46%   |
| Qualcomm Atheros           | 9        | 2.51%   |
| D-Link System              | 4        | 1.11%   |
| ZTE WCDMA Technologies MSM | 1        | 0.28%   |
| Samsung Electronics        | 1        | 0.28%   |
| MediaTek                   | 1        | 0.28%   |
| ICS Advent                 | 1        | 0.28%   |
| Aquantia                   | 1        | 0.28%   |
| 3Com                       | 1        | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                                              | Desktops | Percent |
|----------------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                             | 133      | 32.84%  |
| Intel Ethernet Controller I225-V                                                                   | 29       | 7.16%   |
| Intel Ethernet Controller I226-V                                                                   | 27       | 6.67%   |
| Intel I211 Gigabit Network Connection                                                              | 20       | 4.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                              | 18       | 4.44%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                  | 16       | 3.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                              | 9        | 2.22%   |
| Intel 82574L Gigabit Network Connection                                                            | 9        | 2.22%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                                    | 8        | 1.98%   |
| Intel I350 Gigabit Network Connection                                                              | 8        | 1.98%   |
| Intel 82576 Gigabit Network Connection                                                             | 8        | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                              | 7        | 1.73%   |
| Realtek RTL8125 2.5GbE Controller                                                                  | 5        | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                                                              | 5        | 1.23%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)                      | 5        | 1.23%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                     | 5        | 1.23%   |
| Intel Ethernet Connection I217-LM                                                                  | 4        | 0.99%   |
| Intel Ethernet Connection (2) I219-V                                                               | 4        | 0.99%   |
| Intel 82580 Gigabit Network Connection                                                             | 4        | 0.99%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                                    | 4        | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                      | 3        | 0.74%   |
| Intel I210 Gigabit Network Connection                                                              | 3        | 0.74%   |
| Intel Ethernet Connection (2) I218-V                                                               | 3        | 0.74%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                                               | 3        | 0.74%   |
| Intel 82583V Gigabit Network Connection                                                            | 3        | 0.74%   |
| Intel 82579V Gigabit Network Connection                                                            | 3        | 0.74%   |
| Intel 82578DM Gigabit Network Connection                                                           | 3        | 0.74%   |
| Intel 82578DC Gigabit Network Connection                                                           | 3        | 0.74%   |
| Intel 82567LM-3 Gigabit Network Connection                                                         | 3        | 0.74%   |
| Intel 82566DM-2 Gigabit Network Connection                                                         | 3        | 0.74%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                                         | 2        | 0.49%   |
| Intel Ethernet Connection (7) I219-V                                                               | 2        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                                              | 2        | 0.49%   |
| Intel Ethernet Connection (14) I219-V                                                              | 2        | 0.49%   |
| Intel 82575GB Gigabit Network Connection                                                           | 2        | 0.49%   |
| Intel 82575EB Gigabit Network Connection                                                           | 2        | 0.49%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                                         | 2        | 0.49%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                                                   | 2        | 0.49%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                                                   | 2        | 0.49%   |
| ZTE WCDMA MSM ZTE Mobile Boardband CDC Ethernet Control Model (ECM) CDC Ethernet Data Mass Storage | 1        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 289      | 83.53%  |
| WiFi     | 54       | 15.61%  |
| Modem    | 2        | 0.58%   |
| Unknown  | 1        | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 283      | 95.29%  |
| WiFi     | 14       | 4.71%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 70       | 23.41%  |
| 4     | 69       | 23.08%  |
| 2     | 67       | 22.41%  |
| 3     | 45       | 15.05%  |
| 5     | 21       | 7.02%   |
| 6     | 15       | 5.02%   |
| 9     | 4        | 1.34%   |
| 7     | 3        | 1%      |
| 8     | 2        | 0.67%   |
| 14    | 1        | 0.33%   |
| 11    | 1        | 0.33%   |
| 0     | 1        | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 261      | 86.14%  |
| Yes  | 42       | 13.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 20       | 52.63%  |
| Realtek Semiconductor           | 9        | 23.68%  |
| Cambridge Silicon Radio         | 6        | 15.79%  |
| Qualcomm Atheros Communications | 1        | 2.63%   |
| Qcom                            | 1        | 2.63%   |
| IMC Networks                    | 1        | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Adapter                           | 9        | 23.68%  |
| Intel Bluetooth wireless interface                  | 8        | 21.05%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 15.79%  |
| Intel AX210 Bluetooth                               | 4        | 10.53%  |
| Intel AX201 Bluetooth                               | 3        | 7.89%   |
| Intel AX200 Bluetooth                               | 2        | 5.26%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth       | 1        | 2.63%   |
| Qcom Broadcom Bluetooth USB                         | 1        | 2.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 2.63%   |
| Intel AX211 Bluetooth                               | 1        | 2.63%   |
| IMC Networks Realtek Bluetooth Adapter              | 1        | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 202      | 65.8%   |
| AMD                                             | 63       | 20.52%  |
| Nvidia                                          | 28       | 9.12%   |
| C-Media Electronics                             | 6        | 1.95%   |
| Zoran Co. Personal Media Division (Nogatech)    | 3        | 0.98%   |
| XING WEI 2.4G USB                               | 1        | 0.33%   |
| Weltrend Semiconductor                          | 1        | 0.33%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.33%   |
| KTMicro                                         | 1        | 0.33%   |
| Generalplus Technology                          | 1        | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 23       | 6.32%   |
| Intel Jasper Lake HD Audio                                                 | 20       | 5.49%   |
| AMD Ryzen HD Audio Controller                                              | 20       | 5.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 18       | 4.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 18       | 4.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 16       | 4.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 15       | 4.12%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 15       | 4.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14       | 3.85%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 14       | 3.85%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 11       | 3.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11       | 3.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10       | 2.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 8        | 2.2%    |
| Intel 200 Series PCH HD Audio                                              | 8        | 2.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7        | 1.92%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6        | 1.65%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 1.65%   |
| Intel 8 Series HD Audio Controller                                         | 6        | 1.65%   |
| Nvidia High Definition Audio Controller                                    | 5        | 1.37%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 1.1%    |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 1.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4        | 1.1%    |
| Intel Broadwell-U Audio Controller                                         | 4        | 1.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 1.1%    |
| AMD Kaveri HDMI/DP Audio Controller                                        | 4        | 1.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.1%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.1%    |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 3        | 0.82%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 0.82%   |
| Intel Sunrise Point-LP HD Audio                                            | 3        | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 0.82%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 0.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 0.82%   |
| C-Media Electronics CM108 Audio Controller                                 | 3        | 0.82%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 3        | 0.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 0.82%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Unknown                | 60       | 18.4%   |
| Kingston               | 53       | 16.26%  |
| Samsung Electronics    | 25       | 7.67%   |
| Unknown                | 25       | 7.67%   |
| Smart                  | 24       | 7.36%   |
| Crucial                | 19       | 5.83%   |
| Micron Technology      | 14       | 4.29%   |
| SK hynix               | 13       | 3.99%   |
| Teikon                 | 11       | 3.37%   |
| A-DATA Technology      | 11       | 3.37%   |
| Corsair                | 10       | 3.07%   |
| Unknown (ABCD)         | 4        | 1.23%   |
| Team                   | 3        | 0.92%   |
| PUSKILL                | 3        | 0.92%   |
| MemoWise               | 3        | 0.92%   |
| Hikvision              | 3        | 0.92%   |
| G.Skill                | 3        | 0.92%   |
| Toshiba                | 2        | 0.61%   |
| RZX                    | 2        | 0.61%   |
| Patriot                | 2        | 0.61%   |
| Multilaser             | 2        | 0.61%   |
| Lexar                  | 2        | 0.61%   |
| Hewlett-Packard        | 2        | 0.61%   |
| Atermiter              | 2        | 0.61%   |
| Apacer                 | 2        | 0.61%   |
| Walton Chaintech       | 1        | 0.31%   |
| Unknown (AB)           | 1        | 0.31%   |
| Unknown (8A02)         | 1        | 0.31%   |
| Unknown (0x5846)       | 1        | 0.31%   |
| Unknown (0x0DD5)       | 1        | 0.31%   |
| Unknown (0x0B92)       | 1        | 0.31%   |
| Unknown (0x0080)       | 1        | 0.31%   |
| Unknown (00000000802C) | 1        | 0.31%   |
| tigo                   | 1        | 0.31%   |
| Smart Modular          | 1        | 0.31%   |
| SK_Hynix               | 1        | 0.31%   |
| Qumo                   | 1        | 0.31%   |
| Nanya Technology       | 1        | 0.31%   |
| Kreton                 | 1        | 0.31%   |
| Kllisre                | 1        | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown                                                      | 25       | 7.16%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s          | 6        | 1.72%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 5        | 1.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 4        | 1.15%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 4        | 1.15%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 4        | 1.15%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s | 4        | 1.15%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 3        | 0.86%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 3        | 0.86%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 3        | 0.86%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 3        | 0.86%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                     | 3        | 0.86%   |
| Unknown RAM Module 2GB DIMM DDR2                             | 3        | 0.86%   |
| Unknown RAM Module 2GB DIMM                                  | 3        | 0.86%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s          | 3        | 0.86%   |
| Smart RAM SH564568FH8N0QHSCG 2GB DIMM DDR3 1333MT/s          | 3        | 0.86%   |
| Samsung RAM M378B5673EH1-CF8 2GB DIMM DDR3 1067MT/s          | 3        | 0.86%   |
| MemoWise RAM MW04GN1339UB8 4GB DIMM DDR3 1333MT/s            | 3        | 0.86%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                  | 2        | 0.57%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 2        | 0.57%   |
| Unknown RAM Module 2GB DIMM 667MT/s                          | 2        | 0.57%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 2        | 0.57%   |
| Teikon RAM TMTS8G58DFRBFKB-16 8GB SODIMM DDR3 1600MT/s       | 2        | 0.57%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s           | 2        | 0.57%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR5 6400MT/s          | 2        | 0.57%   |
| Samsung RAM M471A1K43CB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2        | 0.57%   |
| Samsung RAM M425R1GB4BB0-CWMOD 8GB SODIMM DDR5 5600MT/s      | 2        | 0.57%   |
| RZX RAM D3D9M1333G-4G 4GB DIMM DDR3 1333MT/s                 | 2        | 0.57%   |
| Patriot RAM 2666 C16 Series 8GB DIMM DDR4 3000MT/s           | 2        | 0.57%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                    | 2        | 0.57%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 2400MT/s          | 2        | 0.57%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s            | 2        | 0.57%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2400MT/s          | 2        | 0.57%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 2        | 0.57%   |
| Kingston RAM KHX1600C10D3/ 4GB DIMM DDR3 1866MT/s            | 2        | 0.57%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s        | 2        | 0.57%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s        | 2        | 0.57%   |
| Kingston RAM 99U5471-034.A00LF 4GB DIMM DDR3                 | 2        | 0.57%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s        | 2        | 0.57%   |
| Kingston RAM 9905428-155.A00LF 8GB SODIMM DDR3 1600MT/s      | 2        | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 110      | 39.01%  |
| DDR3    | 104      | 36.88%  |
| Unknown | 18       | 6.38%   |
| DDR2    | 16       | 5.67%   |
| SDRAM   | 15       | 5.32%   |
| DDR5    | 9        | 3.19%   |
| LPDDR4  | 6        | 2.13%   |
| LPDDR5  | 3        | 1.06%   |
| LPDDR3  | 1        | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 200      | 71.43%  |
| SODIMM       | 73       | 26.07%  |
| Row Of Chips | 6        | 2.14%   |
| Chip         | 1        | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 114      | 37.13%  |
| 4096  | 84       | 27.36%  |
| 2048  | 56       | 18.24%  |
| 16384 | 40       | 13.03%  |
| 1024  | 8        | 2.61%   |
| 32768 | 5        | 1.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 60       | 19.8%   |
| 1333    | 45       | 14.85%  |
| 2400    | 42       | 13.86%  |
| 3200    | 30       | 9.9%    |
| 2667    | 29       | 9.57%   |
| Unknown | 24       | 7.92%   |
| 800     | 12       | 3.96%   |
| 2133    | 9        | 2.97%   |
| 2666    | 7        | 2.31%   |
| 4800    | 6        | 1.98%   |
| 667     | 6        | 1.98%   |
| 1067    | 5        | 1.65%   |
| 1866    | 4        | 1.32%   |
| 1066    | 4        | 1.32%   |
| 6400    | 3        | 0.99%   |
| 5600    | 3        | 0.99%   |
| 3000    | 3        | 0.99%   |
| 2933    | 2        | 0.66%   |
| 1867    | 2        | 0.66%   |
| 400     | 2        | 0.66%   |
| 4267    | 1        | 0.33%   |
| 4000    | 1        | 0.33%   |
| 3733    | 1        | 0.33%   |
| 3600    | 1        | 0.33%   |
| 333     | 1        | 0.33%   |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 2        | 22.22%  |
| Z-Star Microelectronics       | 1        | 11.11%  |
| Sunplus Innovation Technology | 1        | 11.11%  |
| Quanta                        | 1        | 11.11%  |
| Bison Electronics             | 1        | 11.11%  |
| Aveo Technology               | 1        | 11.11%  |
| Asuscom Network               | 1        | 11.11%  |
| Alcorlink                     | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera      | 1        | 11.11%  |
| Sunplus SPCA2281 Web Camera     | 1        | 11.11%  |
| Quanta LG Webcam                | 1        | 11.11%  |
| Logitech Webcam C270            | 1        | 11.11%  |
| Logitech HD Pro Webcam C920     | 1        | 11.11%  |
| Bison Integrated Camera         | 1        | 11.11%  |
| Aveo USB2.0 Camera              | 1        | 11.11%  |
| Asuscom Network Depstech webcam | 1        | 11.11%  |
| Alcorlink USB 2.0 Camera        | 1        | 11.11%  |

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
| 1     | 159      | 53.72%  |
| 0     | 103      | 34.8%   |
| 2     | 27       | 9.12%   |
| 3     | 6        | 2.03%   |
| 4     | 1        | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 175      | 79.19%  |
| Bluetooth                | 20       | 9.05%   |
| Net/wireless             | 16       | 7.24%   |
| Sound                    | 5        | 2.26%   |
| Net/ethernet             | 2        | 0.9%    |
| Network                  | 1        | 0.45%   |
| Graphics card            | 1        | 0.45%   |
| Firewire controller      | 1        | 0.45%   |

