BSD in China - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for BSD in China.

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

Total: 238

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | SHARKBAY 0B98401 WIN        | [fb353cc6aa](https://bsd-hardware.info/?probe=fb353cc6aa) | Dec 29, 2025 |
| CncTion       | Tiger Lake-6L B0            | [737e686c03](https://bsd-hardware.info/?probe=737e686c03) | Dec 28, 2025 |
| Unknown       | HSX-TGLNP                   | [d66b1a66aa](https://bsd-hardware.info/?probe=d66b1a66aa) | Dec 19, 2025 |
| Techvision    | TVI7309X B0                 | [cfe4b6d92e](https://bsd-hardware.info/?probe=cfe4b6d92e) | Dec 10, 2025 |
| MSI           | B450M MORTAR TITANIUM       | [ec60f694f7](https://bsd-hardware.info/?probe=ec60f694f7) | Nov 15, 2025 |
| MSI           | B450M MORTAR TITANIUM       | [cccc94e04a](https://bsd-hardware.info/?probe=cccc94e04a) | Nov 15, 2025 |
| OEM           | A55                         | [4ed41d1482](https://bsd-hardware.info/?probe=4ed41d1482) | Nov 08, 2025 |
| OEM           | A55                         | [7fffd8a70b](https://bsd-hardware.info/?probe=7fffd8a70b) | Nov 08, 2025 |
| YF            | ADLNN01 V0.1                | [6a11db30a7](https://bsd-hardware.info/?probe=6a11db30a7) | Nov 05, 2025 |
| ASRockRack    | X470D4U                     | [65b8404ec3](https://bsd-hardware.info/?probe=65b8404ec3) | Oct 30, 2025 |
| Maxtang       | AL50 V1.0                   | [836d832e90](https://bsd-hardware.info/?probe=836d832e90) | Sep 27, 2025 |
| Maxtang       | AL50 V1.0                   | [7ffb442904](https://bsd-hardware.info/?probe=7ffb442904) | Sep 27, 2025 |
| YF            | ADLNN01 V0.1                | [0e52ba0629](https://bsd-hardware.info/?probe=0e52ba0629) | Sep 18, 2025 |
| Unknown       | Unknown                     | [cca7a6bd2e](https://bsd-hardware.info/?probe=cca7a6bd2e) | Sep 10, 2025 |
| Lenovo        | NOK                         | [49d075edf8](https://bsd-hardware.info/?probe=49d075edf8) | Aug 30, 2025 |
| HP            | 2187 A01                    | [d7f37c4be4](https://bsd-hardware.info/?probe=d7f37c4be4) | Aug 02, 2025 |
| HP            | 1791                        | [2af6bb3ada](https://bsd-hardware.info/?probe=2af6bb3ada) | Jul 24, 2025 |
| Intel         | SHARKBAY                    | [725496771a](https://bsd-hardware.info/?probe=725496771a) | Jul 23, 2025 |
| Intel         | SKYBAY                      | [140231475e](https://bsd-hardware.info/?probe=140231475e) | Jul 22, 2025 |
| Techvision    | TVI7309X B0                 | [b37132fb74](https://bsd-hardware.info/?probe=b37132fb74) | Jul 19, 2025 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [c9cf382547](https://bsd-hardware.info/?probe=c9cf382547) | Jul 08, 2025 |
| Unknown       | Unknown                     | [4119467165](https://bsd-hardware.info/?probe=4119467165) | Jun 25, 2025 |
| ASRock        | N3150B-ITX                  | [41b7d2888f](https://bsd-hardware.info/?probe=41b7d2888f) | Jun 15, 2025 |
| SANGFOR       | ZM5400A AF1320              | [adbc715c11](https://bsd-hardware.info/?probe=adbc715c11) | Jun 03, 2025 |
| Techvision    | TVI7309X B0                 | [3ba42f1b79](https://bsd-hardware.info/?probe=3ba42f1b79) | May 30, 2025 |
| Lenovo        | 317A SDK0L77767 WIN 3423... | [e72b2865b3](https://bsd-hardware.info/?probe=e72b2865b3) | May 27, 2025 |
| Unknown       | Unknown                     | [4084b9876d](https://bsd-hardware.info/?probe=4084b9876d) | May 23, 2025 |
| Unknown       | Unknown                     | [3b2ff43e25](https://bsd-hardware.info/?probe=3b2ff43e25) | May 21, 2025 |
| Unknown       | Unknown                     | [6d6b12bbbc](https://bsd-hardware.info/?probe=6d6b12bbbc) | May 21, 2025 |
| HP            | 1791                        | [92060795fc](https://bsd-hardware.info/?probe=92060795fc) | May 21, 2025 |
| ASRock        | A320M-HDV R4.0              | [b343630264](https://bsd-hardware.info/?probe=b343630264) | May 15, 2025 |
| ASRock        | A320M-HDV R4.0              | [61a7e317c5](https://bsd-hardware.info/?probe=61a7e317c5) | May 13, 2025 |
| Unknown       | Unknown                     | [3c2a8638be](https://bsd-hardware.info/?probe=3c2a8638be) | May 06, 2025 |
| Unknown       | DS2501                      | [39bf3696f6](https://bsd-hardware.info/?probe=39bf3696f6) | Apr 26, 2025 |
| Gigabyte      | A520I DASH                  | [af22f1da10](https://bsd-hardware.info/?probe=af22f1da10) | Apr 20, 2025 |
| Intel         | X99H                        | [e88d5ce2d4](https://bsd-hardware.info/?probe=e88d5ce2d4) | Mar 30, 2025 |
| Unknown       | Unknown                     | [f64606c4b1](https://bsd-hardware.info/?probe=f64606c4b1) | Mar 17, 2025 |
| Intel         | SKYBAY                      | [45ee308c30](https://bsd-hardware.info/?probe=45ee308c30) | Mar 14, 2025 |
| Lenovo        | 1059 NOK                    | [46bfc09fb9](https://bsd-hardware.info/?probe=46bfc09fb9) | Mar 14, 2025 |
| Gigabyte      | A520I DASH                  | [406e7e5b14](https://bsd-hardware.info/?probe=406e7e5b14) | Mar 13, 2025 |
| Techvision    | TVI7309X B0                 | [2e2054df8b](https://bsd-hardware.info/?probe=2e2054df8b) | Mar 09, 2025 |
| Techvision    | TVI7309X B0                 | [e9e49ff91d](https://bsd-hardware.info/?probe=e9e49ff91d) | Mar 08, 2025 |
| MSI           | H81M-P33                    | [2061990247](https://bsd-hardware.info/?probe=2061990247) | Feb 26, 2025 |
| Gigabyte      | B85M-D2V-SI                 | [3442395302](https://bsd-hardware.info/?probe=3442395302) | Feb 25, 2025 |
| Lenovo        | 1059 NOK                    | [e88b2e7e02](https://bsd-hardware.info/?probe=e88b2e7e02) | Feb 22, 2025 |
| Unknown       | Unknown                     | [e761010d61](https://bsd-hardware.info/?probe=e761010d61) | Jan 14, 2025 |
| Intel         | SKYBAY                      | [ffdabeb396](https://bsd-hardware.info/?probe=ffdabeb396) | Jan 09, 2025 |
| AZW           | EQ                          | [69a1ed7f82](https://bsd-hardware.info/?probe=69a1ed7f82) | Dec 29, 2024 |
| Unknown       | Unknown                     | [2e05274300](https://bsd-hardware.info/?probe=2e05274300) | Dec 24, 2024 |
| Techvision    | TVI7309X B0                 | [887c112b05](https://bsd-hardware.info/?probe=887c112b05) | Dec 22, 2024 |
| MSI           | ZH77A-G43                   | [f000f3f0cc](https://bsd-hardware.info/?probe=f000f3f0cc) | Dec 16, 2024 |
| JGINYUE       | X99-8D4G Server             | [8a6322442d](https://bsd-hardware.info/?probe=8a6322442d) | Dec 13, 2024 |
| JGINYUE       | X99-8D4G Server             | [0a59d0dd76](https://bsd-hardware.info/?probe=0a59d0dd76) | Dec 09, 2024 |
| Techvision    | TVI7309X B0                 | [8cb6acf4a0](https://bsd-hardware.info/?probe=8cb6acf4a0) | Dec 04, 2024 |
| Gigabyte      | H110MSTX-HD3 Reborn by d... | [c1473102cc](https://bsd-hardware.info/?probe=c1473102cc) | Nov 29, 2024 |
| Gigabyte      | H110MSTX-HD3 Reborn by d... | [d99e7bd515](https://bsd-hardware.info/?probe=d99e7bd515) | Nov 28, 2024 |
| Unknown       | Unknown                     | [dd5a922e5c](https://bsd-hardware.info/?probe=dd5a922e5c) | Nov 05, 2024 |
| Techvision    | TVI7309X B0                 | [bc8f05dd4e](https://bsd-hardware.info/?probe=bc8f05dd4e) | Oct 30, 2024 |
| HP            | 1791                        | [ed11ebb449](https://bsd-hardware.info/?probe=ed11ebb449) | Oct 29, 2024 |
| MSI           | H81M-P33                    | [2d8b4d829c](https://bsd-hardware.info/?probe=2d8b4d829c) | Oct 12, 2024 |
| Unknown       | Unknown                     | [0733846ece](https://bsd-hardware.info/?probe=0733846ece) | Sep 29, 2024 |
| Unknown       | Unknown                     | [4219b5e286](https://bsd-hardware.info/?probe=4219b5e286) | Sep 24, 2024 |
| Unknown       | Unknown                     | [40a73794e8](https://bsd-hardware.info/?probe=40a73794e8) | Sep 24, 2024 |
| HP            | 1791                        | [ba14c6ea52](https://bsd-hardware.info/?probe=ba14c6ea52) | Sep 19, 2024 |
| MSI           | H81M-P33                    | [677cd5d559](https://bsd-hardware.info/?probe=677cd5d559) | Sep 10, 2024 |
| Dell          | 0KYWH7 A03                  | [e7685ec40f](https://bsd-hardware.info/?probe=e7685ec40f) | Sep 05, 2024 |
| Unknown       | Unknown                     | [8c646193be](https://bsd-hardware.info/?probe=8c646193be) | Sep 01, 2024 |
| Intel         | ChiefRiver                  | [fbd6c1a3b4](https://bsd-hardware.info/?probe=fbd6c1a3b4) | Aug 25, 2024 |
| Intel         | X99H                        | [aa96aabb57](https://bsd-hardware.info/?probe=aa96aabb57) | Aug 18, 2024 |
| Unknown       | DS2308                      | [8e83d550ba](https://bsd-hardware.info/?probe=8e83d550ba) | Aug 16, 2024 |
| Quanmax       | MITX-DNVE B1                | [90793d65e8](https://bsd-hardware.info/?probe=90793d65e8) | Aug 14, 2024 |
| Unknown       | Unknown                     | [d7fba3c543](https://bsd-hardware.info/?probe=d7fba3c543) | Aug 08, 2024 |
| Unknown       | Unknown                     | [42ff53cce9](https://bsd-hardware.info/?probe=42ff53cce9) | Aug 03, 2024 |
| Quanmax       | MITX-DNVE B1                | [5616b2e9d3](https://bsd-hardware.info/?probe=5616b2e9d3) | Jul 27, 2024 |
| ASRock        | Q1900M                      | [d2de430209](https://bsd-hardware.info/?probe=d2de430209) | Jul 18, 2024 |
| Techvision    | TVI7309X B0                 | [948e7d1f94](https://bsd-hardware.info/?probe=948e7d1f94) | Jul 14, 2024 |
| ASUSTek       | PRIME B660M-K D4            | [22e00e24fa](https://bsd-hardware.info/?probe=22e00e24fa) | Jul 03, 2024 |
| HP            | 1791                        | [431b6e2651](https://bsd-hardware.info/?probe=431b6e2651) | Jun 21, 2024 |
| Unknown       | Unknown                     | [70c057f043](https://bsd-hardware.info/?probe=70c057f043) | Jun 13, 2024 |
| Gigabyte      | 970A-DS3P                   | [05a19cce97](https://bsd-hardware.info/?probe=05a19cce97) | Jun 05, 2024 |
| Dell          | 03F1TC A00                  | [dbfad2d18f](https://bsd-hardware.info/?probe=dbfad2d18f) | Jun 02, 2024 |
| Unknown       | Unknown                     | [4e52dd4840](https://bsd-hardware.info/?probe=4e52dd4840) | May 29, 2024 |
| BROUNION      | R86S                        | [54b53171d0](https://bsd-hardware.info/?probe=54b53171d0) | May 27, 2024 |
| EVOC          | ECS-1830V2NA C02            | [b407ee06be](https://bsd-hardware.info/?probe=b407ee06be) | May 25, 2024 |
| Intel         | SKYBAY                      | [148385f25e](https://bsd-hardware.info/?probe=148385f25e) | May 16, 2024 |
| Intel         | SKYBAY                      | [32fc56ec41](https://bsd-hardware.info/?probe=32fc56ec41) | May 16, 2024 |
| BROUNION      | R86S                        | [752d83911f](https://bsd-hardware.info/?probe=752d83911f) | May 08, 2024 |
| Intel         | MAHOBAY                     | [c76dc714f2](https://bsd-hardware.info/?probe=c76dc714f2) | Apr 15, 2024 |
| Unknown       | Unknown                     | [75fccc1dbe](https://bsd-hardware.info/?probe=75fccc1dbe) | Apr 15, 2024 |
| Unknown       | Unknown                     | [ba545bb931](https://bsd-hardware.info/?probe=ba545bb931) | Apr 15, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS        | [f960805584](https://bsd-hardware.info/?probe=f960805584) | Mar 26, 2024 |
| Unknown       | QDNV01                      | [72b182fa59](https://bsd-hardware.info/?probe=72b182fa59) | Mar 25, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [c2fcfcd39d](https://bsd-hardware.info/?probe=c2fcfcd39d) | Mar 24, 2024 |
| Intel         | MAHOBAY                     | [cf80a0db55](https://bsd-hardware.info/?probe=cf80a0db55) | Mar 19, 2024 |
| ASRock        | B360M Xtreme                | [e84af03816](https://bsd-hardware.info/?probe=e84af03816) | Feb 16, 2024 |
| Techvision    | TVI7309X B0                 | [0a384151b6](https://bsd-hardware.info/?probe=0a384151b6) | Jan 20, 2024 |
| Unknown       | Unknown                     | [609434dc71](https://bsd-hardware.info/?probe=609434dc71) | Jan 18, 2024 |
| Unknown       | Unknown                     | [ba78787dff](https://bsd-hardware.info/?probe=ba78787dff) | Dec 29, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [06457349dc](https://bsd-hardware.info/?probe=06457349dc) | Dec 22, 2023 |
| Intel         | SKYBAY                      | [6ad2ae72f1](https://bsd-hardware.info/?probe=6ad2ae72f1) | Dec 13, 2023 |
| MSI           | B450M MORTAR                | [4017ce5221](https://bsd-hardware.info/?probe=4017ce5221) | Nov 29, 2023 |
| Supermicro    | X9SCL-II/X9SCM-II           | [34833316ac](https://bsd-hardware.info/?probe=34833316ac) | Nov 27, 2023 |
| Silicom       | 80300-0214-G16 R310         | [34382c8f4b](https://bsd-hardware.info/?probe=34382c8f4b) | Nov 24, 2023 |
| Unknown       | Unknown                     | [456d5ad8bf](https://bsd-hardware.info/?probe=456d5ad8bf) | Nov 05, 2023 |
| YanRay Tec... | B1904                       | [7d194ae12b](https://bsd-hardware.info/?probe=7d194ae12b) | Oct 28, 2023 |
| MECHREVO      | Unknown                     | [2dac22205c](https://bsd-hardware.info/?probe=2dac22205c) | Oct 23, 2023 |
| Lenovo        | SHARKBAY SDK0A46860 WIN     | [da1e562510](https://bsd-hardware.info/?probe=da1e562510) | Oct 10, 2023 |
| Lenovo        | SHARKBAY SDK0A46860 WIN     | [d7cf15da0c](https://bsd-hardware.info/?probe=d7cf15da0c) | Oct 09, 2023 |
| Unknown       | Unknown                     | [c54bad3277](https://bsd-hardware.info/?probe=c54bad3277) | Oct 04, 2023 |
| Biostar       | A55MLC2                     | [fac0f247d0](https://bsd-hardware.info/?probe=fac0f247d0) | Sep 28, 2023 |
| Techvision    | TVI7309X B0                 | [93c70115bd](https://bsd-hardware.info/?probe=93c70115bd) | Aug 19, 2023 |
| Intel         | SKYBAY                      | [53fb653186](https://bsd-hardware.info/?probe=53fb653186) | Aug 18, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [2f6574d368](https://bsd-hardware.info/?probe=2f6574d368) | Aug 08, 2023 |
| Unknown       | Unknown                     | [75e009424e](https://bsd-hardware.info/?probe=75e009424e) | Aug 07, 2023 |
| Intel         | SKYBAY                      | [fde75b4094](https://bsd-hardware.info/?probe=fde75b4094) | Aug 04, 2023 |
| AZW           | EQ                          | [a581a63aae](https://bsd-hardware.info/?probe=a581a63aae) | Jul 29, 2023 |
| AZW           | EQ                          | [1feeda5ce9](https://bsd-hardware.info/?probe=1feeda5ce9) | Jul 29, 2023 |
| Unknown       | Unknown                     | [3ca61a6a18](https://bsd-hardware.info/?probe=3ca61a6a18) | Jul 24, 2023 |
| AZW           | EQ                          | [7d2884120c](https://bsd-hardware.info/?probe=7d2884120c) | Jul 23, 2023 |
| NEC Comput... | IS8XM                       | [9f50189f65](https://bsd-hardware.info/?probe=9f50189f65) | Jul 22, 2023 |
| OEM           | ITX-SC3 V1.1                | [a58b6ba2d4](https://bsd-hardware.info/?probe=a58b6ba2d4) | Jul 18, 2023 |
| OEM           | ITX-SC3 V1.1                | [7c550acc8c](https://bsd-hardware.info/?probe=7c550acc8c) | Jul 18, 2023 |
| Unknown       | Unknown                     | [4c5d9c5da3](https://bsd-hardware.info/?probe=4c5d9c5da3) | Jun 29, 2023 |
| WlanCN        | 6000 Series                 | [d2e71531b6](https://bsd-hardware.info/?probe=d2e71531b6) | Jun 05, 2023 |
| NORCO         | HB133                       | [1d59c53b9b](https://bsd-hardware.info/?probe=1d59c53b9b) | May 25, 2023 |
| DS            | FJ04D JHS60K                | [7561a5e28b](https://bsd-hardware.info/?probe=7561a5e28b) | May 11, 2023 |
| Colorful T... | C.J1900A-BTC PLUS V20       | [07add98717](https://bsd-hardware.info/?probe=07add98717) | May 03, 2023 |
| Colorful T... | C.J1900A-BTC PLUS V20       | [b718c75566](https://bsd-hardware.info/?probe=b718c75566) | May 01, 2023 |
| Dell          | 0VTC0D A02                  | [a807892254](https://bsd-hardware.info/?probe=a807892254) | Apr 19, 2023 |
| Lenovo        | YangTianM6880N              | [a567c3062c](https://bsd-hardware.info/?probe=a567c3062c) | Apr 18, 2023 |
| YENTEK        | ITX-B75R1                   | [7443f81ab1](https://bsd-hardware.info/?probe=7443f81ab1) | Apr 10, 2023 |
| Gigabyte      | M52L-S3P                    | [3a6baf7f2d](https://bsd-hardware.info/?probe=3a6baf7f2d) | Apr 09, 2023 |
| YENTEK        | ITX-B75R1                   | [3cab1716e0](https://bsd-hardware.info/?probe=3cab1716e0) | Apr 08, 2023 |
| Unknown       | Unknown                     | [0976c12353](https://bsd-hardware.info/?probe=0976c12353) | Apr 03, 2023 |
| Intel         | MAHOBAY                     | [6e8443e9f4](https://bsd-hardware.info/?probe=6e8443e9f4) | Apr 01, 2023 |
| Dell          | 0KYJ8C A02                  | [ea8759f206](https://bsd-hardware.info/?probe=ea8759f206) | Mar 09, 2023 |
| Unknown       | Unknown                     | [815cd70e71](https://bsd-hardware.info/?probe=815cd70e71) | Feb 25, 2023 |
| Unknown       | Unknown                     | [866ff788f9](https://bsd-hardware.info/?probe=866ff788f9) | Feb 23, 2023 |
| Lenovo        | SHARKBAY SDK0A46860 WIN     | [4cd5bcdfed](https://bsd-hardware.info/?probe=4cd5bcdfed) | Feb 18, 2023 |
| Dell          | 0KYJ8C A02                  | [854d373499](https://bsd-hardware.info/?probe=854d373499) | Feb 16, 2023 |
| Dell          | 0K240Y A01                  | [d9f16ef94b](https://bsd-hardware.info/?probe=d9f16ef94b) | Jan 18, 2023 |
| Dell          | 0KYJ8C A02                  | [490f20c93d](https://bsd-hardware.info/?probe=490f20c93d) | Dec 21, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [108c9de5cc](https://bsd-hardware.info/?probe=108c9de5cc) | Dec 18, 2022 |
| Dell          | 0KYJ8C A02                  | [c0c4fa9349](https://bsd-hardware.info/?probe=c0c4fa9349) | Dec 02, 2022 |
| TOPFEEL       | H110D4-P1                   | [90b1dfc430](https://bsd-hardware.info/?probe=90b1dfc430) | Nov 19, 2022 |
| Dell          | 0KYJ8C A02                  | [7282ce8fe2](https://bsd-hardware.info/?probe=7282ce8fe2) | Nov 19, 2022 |
| ONDA          | N78G5D3 Ver:5.00            | [009bc44d12](https://bsd-hardware.info/?probe=009bc44d12) | Nov 07, 2022 |
| Lenovo        | YangTianM6880N              | [2e9c3b7368](https://bsd-hardware.info/?probe=2e9c3b7368) | Nov 04, 2022 |
| Centerm       | GA690-2 2                   | [9d6c3d67cd](https://bsd-hardware.info/?probe=9d6c3d67cd) | Oct 28, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [54e4202bc7](https://bsd-hardware.info/?probe=54e4202bc7) | Oct 21, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [c6ee09790d](https://bsd-hardware.info/?probe=c6ee09790d) | Oct 20, 2022 |
| AMD           | Inagua CRB                  | [59c41dcd31](https://bsd-hardware.info/?probe=59c41dcd31) | Oct 11, 2022 |
| AMD           | Inagua CRB                  | [ff4eccae8a](https://bsd-hardware.info/?probe=ff4eccae8a) | Oct 11, 2022 |
| Unknown       | Unknown                     | [a5cbd6786d](https://bsd-hardware.info/?probe=a5cbd6786d) | Oct 11, 2022 |
| Unknown       | Unknown                     | [f31f4c00cd](https://bsd-hardware.info/?probe=f31f4c00cd) | Oct 08, 2022 |
| Dell          | 0KYJ8C A02                  | [130a05a115](https://bsd-hardware.info/?probe=130a05a115) | Oct 07, 2022 |
| Dell          | 0KYJ8C A02                  | [12493c3802](https://bsd-hardware.info/?probe=12493c3802) | Sep 26, 2022 |
| Unknown       | Unknown                     | [199ad16750](https://bsd-hardware.info/?probe=199ad16750) | Sep 21, 2022 |
| Gigabyte      | H410M S2 V2                 | [8de53ac515](https://bsd-hardware.info/?probe=8de53ac515) | Sep 17, 2022 |
| Dell          | 0KYJ8C A02                  | [7e8d44c688](https://bsd-hardware.info/?probe=7e8d44c688) | Sep 10, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [df57940ad5](https://bsd-hardware.info/?probe=df57940ad5) | Sep 03, 2022 |
| Techvision    | TVI7309X B0                 | [9941ee7afb](https://bsd-hardware.info/?probe=9941ee7afb) | Sep 03, 2022 |
| Lenovo        | YangTianM6880N              | [f675498946](https://bsd-hardware.info/?probe=f675498946) | Sep 02, 2022 |
| Unknown       | DTB1168                     | [e924ba2a44](https://bsd-hardware.info/?probe=e924ba2a44) | Sep 01, 2022 |
| WlanCN        | 6000 Series                 | [7fda15ca84](https://bsd-hardware.info/?probe=7fda15ca84) | Aug 25, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [f50526a6d6](https://bsd-hardware.info/?probe=f50526a6d6) | Jul 27, 2022 |
| MAXSUN        | MS-H110D4L FS M.2           | [39d06b12fd](https://bsd-hardware.info/?probe=39d06b12fd) | Jul 25, 2022 |
| ASUSTek       | Maximus IX HERO             | [ea2f21a15f](https://bsd-hardware.info/?probe=ea2f21a15f) | Jul 12, 2022 |
| Techvision    | TVI7309X B0                 | [b2aa5f61e2](https://bsd-hardware.info/?probe=b2aa5f61e2) | Jul 11, 2022 |
| ASUSTek       | Maximus IX HERO             | [81668557c6](https://bsd-hardware.info/?probe=81668557c6) | Jul 08, 2022 |
| Unknown       | Unknown                     | [0f45bdf1ec](https://bsd-hardware.info/?probe=0f45bdf1ec) | Jun 14, 2022 |
| Unknown       | Unknown                     | [57a6f58607](https://bsd-hardware.info/?probe=57a6f58607) | Jun 09, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [d9c28e14df](https://bsd-hardware.info/?probe=d9c28e14df) | May 13, 2022 |
| Lenovo        | MAHOBAY                     | [b54df77b59](https://bsd-hardware.info/?probe=b54df77b59) | May 07, 2022 |
| OEM           | B85 JHS359                  | [c5d29cc6b3](https://bsd-hardware.info/?probe=c5d29cc6b3) | May 03, 2022 |
| PAIQ          | EC3-BT19D4L A1              | [9642cf3129](https://bsd-hardware.info/?probe=9642cf3129) | Mar 30, 2022 |
| ASRock        | Q1900M                      | [e2473b7f22](https://bsd-hardware.info/?probe=e2473b7f22) | Mar 29, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [97f4960723](https://bsd-hardware.info/?probe=97f4960723) | Mar 28, 2022 |
| Unknown       | J3160-4L                    | [e2717ea0eb](https://bsd-hardware.info/?probe=e2717ea0eb) | Mar 24, 2022 |
| Unknown       | Unknown                     | [d08da1541a](https://bsd-hardware.info/?probe=d08da1541a) | Mar 14, 2022 |
| Lenovo        | IdeaCentre B545 10100       | [2f13d4a946](https://bsd-hardware.info/?probe=2f13d4a946) | Mar 12, 2022 |
| ASUSTek       | TUF GAMING X570-PRO         | [8307275b2e](https://bsd-hardware.info/?probe=8307275b2e) | Mar 07, 2022 |
| Unknown       | Unknown                     | [ce3fedcbaf](https://bsd-hardware.info/?probe=ce3fedcbaf) | Mar 07, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [b54ace2a34](https://bsd-hardware.info/?probe=b54ace2a34) | Mar 03, 2022 |
| Intel         | X58                         | [f7075908f6](https://bsd-hardware.info/?probe=f7075908f6) | Feb 09, 2022 |
| Unknown       | Unknown                     | [8eda642f6a](https://bsd-hardware.info/?probe=8eda642f6a) | Jan 04, 2022 |
| Dell          | 0H9KW5 A00                  | [e962ca25b3](https://bsd-hardware.info/?probe=e962ca25b3) | Dec 28, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | [e115f87ef7](https://bsd-hardware.info/?probe=e115f87ef7) | Nov 30, 2021 |
| Unknown       | Unknown                     | [08f546f789](https://bsd-hardware.info/?probe=08f546f789) | Nov 21, 2021 |
| Unknown       | Unknown                     | [d958c5d8f1](https://bsd-hardware.info/?probe=d958c5d8f1) | Nov 18, 2021 |
| Unknown       | Unknown                     | [d3e799d3a6](https://bsd-hardware.info/?probe=d3e799d3a6) | Nov 13, 2021 |
| Unknown       | YL-SKUL6-7 Series           | [8c72c2f429](https://bsd-hardware.info/?probe=8c72c2f429) | Nov 12, 2021 |
| GuoGuang      | IC2M1028V-6                 | [1aa8bbd5b2](https://bsd-hardware.info/?probe=1aa8bbd5b2) | Nov 07, 2021 |
| Lenovo        | SHARKBAY SDK0A46860 PRO     | [9b545faf66](https://bsd-hardware.info/?probe=9b545faf66) | Oct 28, 2021 |
| Lenovo        | SHARKBAY SDK0A46860 PRO     | [f269216a0d](https://bsd-hardware.info/?probe=f269216a0d) | Oct 27, 2021 |
| MSI           | MAG B460M MORTAR            | [f9c5120643](https://bsd-hardware.info/?probe=f9c5120643) | Oct 22, 2021 |
| Gigabyte      | H410M S2 V2                 | [b106820e47](https://bsd-hardware.info/?probe=b106820e47) | Oct 21, 2021 |
| Dell          | 0DR845                      | [d8324d1639](https://bsd-hardware.info/?probe=d8324d1639) | Oct 21, 2021 |
| HP            | 3398                        | [892f19c9bd](https://bsd-hardware.info/?probe=892f19c9bd) | Oct 18, 2021 |
| Gigabyte      | H410M S2 V2                 | [9cf5948654](https://bsd-hardware.info/?probe=9cf5948654) | Oct 13, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | [84f06376e2](https://bsd-hardware.info/?probe=84f06376e2) | Oct 02, 2021 |
| NEC Comput... | SHARKBAY                    | [24229ed11f](https://bsd-hardware.info/?probe=24229ed11f) | Sep 22, 2021 |
| CNCTION-IA... | Unknown                     | [aad95eb2bf](https://bsd-hardware.info/?probe=aad95eb2bf) | Sep 21, 2021 |
| YANYU         | ITX-N29 VER:1.5 baytrail    | [c851a73aa5](https://bsd-hardware.info/?probe=c851a73aa5) | Sep 20, 2021 |
| Unknown       | Unknown                     | [0da457285c](https://bsd-hardware.info/?probe=0da457285c) | Aug 23, 2021 |
| Unknown       | J3160-4L                    | [3063e4b82f](https://bsd-hardware.info/?probe=3063e4b82f) | Aug 21, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | [cce0d947f1](https://bsd-hardware.info/?probe=cce0d947f1) | Aug 20, 2021 |
| PAIQ          | EC3-BT19D4L A1              | [1a438c7632](https://bsd-hardware.info/?probe=1a438c7632) | Aug 19, 2021 |
| CNCTION-IA... | Unknown                     | [7763f089a3](https://bsd-hardware.info/?probe=7763f089a3) | Aug 17, 2021 |
| Unknown       | J3160-4L                    | [dc1e25a4e0](https://bsd-hardware.info/?probe=dc1e25a4e0) | Aug 07, 2021 |
| Lenovo        | NOK                         | [de711c244f](https://bsd-hardware.info/?probe=de711c244f) | Aug 05, 2021 |
| Lenovo        | NOK                         | [5bd27802f0](https://bsd-hardware.info/?probe=5bd27802f0) | Aug 04, 2021 |
| GuoGuang      | IC2M1028V-6                 | [9bfe0dca00](https://bsd-hardware.info/?probe=9bfe0dca00) | Jul 21, 2021 |
| Unknown       | Unknown                     | [58f03a472f](https://bsd-hardware.info/?probe=58f03a472f) | Jul 03, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | [b8712916f2](https://bsd-hardware.info/?probe=b8712916f2) | Jun 29, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | [0b0951a048](https://bsd-hardware.info/?probe=0b0951a048) | Jun 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [8fe29978c3](https://bsd-hardware.info/?probe=8fe29978c3) | Jun 22, 2021 |
| Protectli     | FW6                         | [7fe94af21a](https://bsd-hardware.info/?probe=7fe94af21a) | Jun 11, 2021 |
| CNCTION-IA... | Unknown                     | [ff1a657505](https://bsd-hardware.info/?probe=ff1a657505) | Jun 08, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | [c0b3c87810](https://bsd-hardware.info/?probe=c0b3c87810) | Jun 04, 2021 |
| Colorful T... | C.Q1900M PRO V20            | [5283765cbe](https://bsd-hardware.info/?probe=5283765cbe) | Apr 03, 2021 |
| Gigabyte      | MZBSWBP-00                  | [3623b04225](https://bsd-hardware.info/?probe=3623b04225) | Mar 31, 2021 |
| Dell          | 018D1Y A00                  | [13754ed4ee](https://bsd-hardware.info/?probe=13754ed4ee) | Mar 23, 2021 |
| Dell          | 0YXT71 A00                  | [cb3d9f12c6](https://bsd-hardware.info/?probe=cb3d9f12c6) | Mar 20, 2021 |
| Dell          | 0W2PJY A01                  | [f162510a27](https://bsd-hardware.info/?probe=f162510a27) | Mar 12, 2021 |
| MSI           | B150M MORTAR                | [19923e24d6](https://bsd-hardware.info/?probe=19923e24d6) | Mar 10, 2021 |
| Dell          | 0W2PJY A01                  | [d8c2f0b19f](https://bsd-hardware.info/?probe=d8c2f0b19f) | Mar 04, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | [9a23dee2ea](https://bsd-hardware.info/?probe=9a23dee2ea) | Mar 01, 2021 |
| Gigabyte      | GA-870-UD3P                 | [e228db2983](https://bsd-hardware.info/?probe=e228db2983) | Feb 20, 2021 |
| Dell          | 018D1Y A00                  | [a54f14d773](https://bsd-hardware.info/?probe=a54f14d773) | Feb 18, 2021 |
| Unknown       | Unknown                     | [22af66ce96](https://bsd-hardware.info/?probe=22af66ce96) | Feb 18, 2021 |
| Google        | Guado                       | [f6473eeb71](https://bsd-hardware.info/?probe=f6473eeb71) | Feb 16, 2021 |
| HP            | 8768 A                      | [f2be4b7b65](https://bsd-hardware.info/?probe=f2be4b7b65) | Feb 16, 2021 |
| ASUSTek       | EX-B85M-V                   | [54c319f2c0](https://bsd-hardware.info/?probe=54c319f2c0) | Feb 15, 2021 |
| Unknown       | Unknown                     | [bc823e0dfc](https://bsd-hardware.info/?probe=bc823e0dfc) | Feb 08, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [12e20c2cb0](https://bsd-hardware.info/?probe=12e20c2cb0) | Jan 23, 2021 |
| ASRock        | A320M-ITX                   | [7fab9dd55a](https://bsd-hardware.info/?probe=7fab9dd55a) | Oct 31, 2020 |
| HP            | 213D A01                    | [b081e36525](https://bsd-hardware.info/?probe=b081e36525) | Oct 31, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| helloSystem 0.7.0 | 9        | 4.48%   |
| helloSystem 0.8.1 | 8        | 3.98%   |
| OPNsense 25.1.7   | 6        | 2.99%   |
| OPNsense 21.7.1   | 6        | 2.99%   |
| helloSystem 0.9.0 | 6        | 2.99%   |
| OPNsense 24.7.11  | 5        | 2.49%   |
| OPNsense 23.1.11  | 5        | 2.49%   |
| OPNsense 21.7.3   | 4        | 1.99%   |
| OPNsense 21.1.7   | 4        | 1.99%   |
| helloSystem 0.5.0 | 4        | 1.99%   |
| FreeBSD 13.1-p2   | 4        | 1.99%   |
| OPNsense 25.7.10  | 3        | 1.49%   |
| OPNsense 25.1.5   | 3        | 1.49%   |
| OPNsense 24.7.7   | 3        | 1.49%   |
| OPNsense 24.1.7   | 3        | 1.49%   |
| OPNsense 24.1.10  | 3        | 1.49%   |
| OPNsense 23.1.5   | 3        | 1.49%   |
| OPNsense 23.1.1   | 3        | 1.49%   |
| OPNsense 22.7.5   | 3        | 1.49%   |
| OPNsense 21.7.5   | 3        | 1.49%   |
| OPNsense 21.7.2   | 3        | 1.49%   |
| FreeBSD 13.2      | 3        | 1.49%   |
| OPNsense 25.1.9   | 2        | 1%      |
| OPNsense 25.1.6   | 2        | 1%      |
| OPNsense 25.1.12  | 2        | 1%      |
| OPNsense 24.7.1   | 2        | 1%      |
| OPNsense 24.7     | 2        | 1%      |
| OPNsense 23.7.9   | 2        | 1%      |
| OPNsense 23.7.7   | 2        | 1%      |
| OPNsense 23.7.5   | 2        | 1%      |
| OPNsense 23.7.12  | 2        | 1%      |
| OPNsense 23.7.1   | 2        | 1%      |
| OPNsense 23.1.7   | 2        | 1%      |
| OPNsense 22.7.2   | 2        | 1%      |
| OPNsense 22.1.4   | 2        | 1%      |
| OPNsense 22.1.2   | 2        | 1%      |
| OPNsense 22.1.10  | 2        | 1%      |
| OPNsense 21.1.6   | 2        | 1%      |
| OPNsense 21.1.3   | 2        | 1%      |
| OPNsense 21.1     | 2        | 1%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 97       | 61.78%  |
| helloSystem | 30       | 19.11%  |
| FreeBSD     | 27       | 17.2%   |
| OpenBSD     | 1        | 0.64%   |
| GhostBSD    | 1        | 0.64%   |
| ClonOS      | 1        | 0.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 153      | 98.08%  |
| arm64   | 2        | 1.28%   |
| powerpc | 1        | 0.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 109      | 69.43%  |
| helloDesktop | 31       | 19.75%  |
| KDE5         | 6        | 3.82%   |
| XFCE         | 4        | 2.55%   |
| MATE         | 3        | 1.91%   |
| KDE6         | 2        | 1.27%   |
| i3           | 1        | 0.64%   |
| GNUstep      | 1        | 0.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 111      | 71.15%  |
| X11     | 45       | 28.85%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 111      | 70.7%   |
| SLiM    | 31       | 19.75%  |
| SDDM    | 10       | 6.37%   |
| LightDM | 4        | 2.55%   |
| XDM     | 1        | 0.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 106      | 65.84%  |
| en_US   | 19       | 11.8%   |
| C       | 16       | 9.94%   |
| zh_CN   | 15       | 9.32%   |
| fr_FR   | 5        | 3.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 141      | 90.38%  |
| BIOS | 15       | 9.62%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Zfs    | 91       | 56.88%  |
| Ufs    | 56       | 35%     |
| Cd9660 | 12       | 7.5%    |
| Ffs    | 1        | 0.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 146      | 93.59%  |
| MBR     | 6        | 3.85%   |
| Unknown | 4        | 2.56%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 41       | 26.28%  |
| Lenovo                                     | 11       | 7.05%   |
| Dell                                       | 10       | 6.41%   |
| Gigabyte Technology                        | 9        | 5.77%   |
| MSI                                        | 8        | 5.13%   |
| Techvision                                 | 7        | 4.49%   |
| Intel                                      | 7        | 4.49%   |
| ASUSTek Computer                           | 6        | 3.85%   |
| ASRock                                     | 6        | 3.85%   |
| Hewlett-Packard                            | 5        | 3.21%   |
| ShenZhen MinWin Technology                 | 3        | 1.92%   |
| OEM                                        | 3        | 1.92%   |
| YF                                         | 2        | 1.28%   |
| Quanmax                                    | 2        | 1.28%   |
| PAIQ                                       | 2        | 1.28%   |
| NEC Computers                              | 2        | 1.28%   |
| Maxtang                                    | 2        | 1.28%   |
| Colorful Technology                        | 2        | 1.28%   |
| AZW                                        | 2        | 1.28%   |
| YENTEK                                     | 1        | 0.64%   |
| YANYU                                      | 1        | 0.64%   |
| YanRay Technology                          | 1        | 0.64%   |
| WlanCN                                     | 1        | 0.64%   |
| TOPFEEL                                    | 1        | 0.64%   |
| Supermicro                                 | 1        | 0.64%   |
| Silicom                                    | 1        | 0.64%   |
| SANGFOR                                    | 1        | 0.64%   |
| Protectli                                  | 1        | 0.64%   |
| ONDA                                       | 1        | 0.64%   |
| NORCO                                      | 1        | 0.64%   |
| MECHREVO                                   | 1        | 0.64%   |
| MAXSUN                                     | 1        | 0.64%   |
| JGINYUE                                    | 1        | 0.64%   |
| GuoGuang                                   | 1        | 0.64%   |
| Google                                     | 1        | 0.64%   |
| EVOC                                       | 1        | 0.64%   |
| DS                                         | 1        | 0.64%   |
| Colorful YuGong Technology And Development | 1        | 0.64%   |
| CNCTION-IAF-E3845                          | 1        | 0.64%   |
| CncTion                                    | 1        | 0.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Unknown                                   | 43       | 27.56%  |
| Techvision TVI7309X                       | 7        | 4.49%   |
| ShenZhen MinWin MW-NANO-APL-4L            | 3        | 1.92%   |
| YF ADLNN01                                | 2        | 1.28%   |
| Quanmax MITX-DNVE                         | 2        | 1.28%   |
| PAIQ EC3-BT19D4L                          | 2        | 1.28%   |
| MSI MS-7B89                               | 2        | 1.28%   |
| Maxtang AL50                              | 2        | 1.28%   |
| Lenovo SHARKBAY 0B98401 WIN               | 2        | 1.28%   |
| Intel MAHOBAY                             | 2        | 1.28%   |
| AZW EQ                                    | 2        | 1.28%   |
| ASRock Q1900M                             | 2        | 1.28%   |
| YENTEK ITX-B75R1                          | 1        | 0.64%   |
| YANYU ITX-N29 VER:1.5 baytrail            | 1        | 0.64%   |
| YanRay B1904                              | 1        | 0.64%   |
| WlanCN 6000 Series                        | 1        | 0.64%   |
| TOPFEEL Topone series                     | 1        | 0.64%   |
| Supermicro NS-EI36S                       | 1        | 0.64%   |
| Silicom 6200                              | 1        | 0.64%   |
| SANGFOR ZM5400A                           | 1        | 0.64%   |
| Protectli FW6                             | 1        | 0.64%   |
| ONDA N78G5D3 Ver:5.00                     | 1        | 0.64%   |
| OEM ITX-SC3                               | 1        | 0.64%   |
| OEM B85 JHS359                            | 1        | 0.64%   |
| OEM A55                                   | 1        | 0.64%   |
| NORCO HB133                               | 1        | 0.64%   |
| NEC Computers SHARKBAY                    | 1        | 0.64%   |
| NEC Computers PC-MC32MBZCEECH             | 1        | 0.64%   |
| MSI MS-7C82                               | 1        | 0.64%   |
| MSI MS-7C37                               | 1        | 0.64%   |
| MSI MS-7A38                               | 1        | 0.64%   |
| MSI MS-7972                               | 1        | 0.64%   |
| MSI MS-7817                               | 1        | 0.64%   |
| MSI MS-7758                               | 1        | 0.64%   |
| MAXSUN MS-H110D4L FS M.2                  | 1        | 0.64%   |
| Lenovo YangTianW2090v-00                  | 1        | 0.64%   |
| Lenovo YangTianT4900k-00 imageM31.cap     | 1        | 0.64%   |
| Lenovo YangTianM6880N                     | 1        | 0.64%   |
| Lenovo YangTianA8800T                     | 1        | 0.64%   |
| Lenovo ThinkStation P360 Ultra 30G20027CW | 1        | 0.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 43       | 27.56%  |
| Techvision TVI7309X            | 7        | 4.49%   |
| Dell OptiPlex                  | 5        | 3.21%   |
| ShenZhen MinWin MW-NANO-APL-4L | 3        | 1.92%   |
| Lenovo SHARKBAY                | 3        | 1.92%   |
| Dell Precision                 | 3        | 1.92%   |
| ASUS TUF                       | 3        | 1.92%   |
| YF ADLNN01                     | 2        | 1.28%   |
| Quanmax MITX-DNVE              | 2        | 1.28%   |
| PAIQ EC3-BT19D4L               | 2        | 1.28%   |
| MSI MS-7B89                    | 2        | 1.28%   |
| Maxtang AL50                   | 2        | 1.28%   |
| Lenovo ThinkCentre             | 2        | 1.28%   |
| Intel MAHOBAY                  | 2        | 1.28%   |
| HP t620                        | 2        | 1.28%   |
| AZW EQ                         | 2        | 1.28%   |
| ASRock Q1900M                  | 2        | 1.28%   |
| YENTEK ITX-B75R1               | 1        | 0.64%   |
| YANYU ITX-N29                  | 1        | 0.64%   |
| YanRay B1904                   | 1        | 0.64%   |
| WlanCN 6000                    | 1        | 0.64%   |
| TOPFEEL Topone                 | 1        | 0.64%   |
| Supermicro NS-EI36S            | 1        | 0.64%   |
| Silicom 6200                   | 1        | 0.64%   |
| SANGFOR ZM5400A                | 1        | 0.64%   |
| Protectli FW6                  | 1        | 0.64%   |
| ONDA N78G5D3                   | 1        | 0.64%   |
| OEM ITX-SC3                    | 1        | 0.64%   |
| OEM B85                        | 1        | 0.64%   |
| OEM A55                        | 1        | 0.64%   |
| NORCO HB133                    | 1        | 0.64%   |
| NEC Computers SHARKBAY         | 1        | 0.64%   |
| NEC Computers PC-MC32MBZCEECH  | 1        | 0.64%   |
| MSI MS-7C82                    | 1        | 0.64%   |
| MSI MS-7C37                    | 1        | 0.64%   |
| MSI MS-7A38                    | 1        | 0.64%   |
| MSI MS-7972                    | 1        | 0.64%   |
| MSI MS-7817                    | 1        | 0.64%   |
| MSI MS-7758                    | 1        | 0.64%   |
| MAXSUN MS-H110D4L              | 1        | 0.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2023    | 21       | 13.46%  |
| 2022    | 20       | 12.82%  |
| 2019    | 13       | 8.33%   |
| 2021    | 12       | 7.69%   |
| 2017    | 12       | 7.69%   |
| 2012    | 12       | 7.69%   |
| 2020    | 11       | 7.05%   |
| 2018    | 8        | 5.13%   |
| 2014    | 8        | 5.13%   |
| 2015    | 7        | 4.49%   |
| 2016    | 6        | 3.85%   |
| 2013    | 6        | 3.85%   |
| 2025    | 5        | 3.21%   |
| 2024    | 4        | 2.56%   |
| 2010    | 3        | 1.92%   |
| 2008    | 3        | 1.92%   |
| 2011    | 2        | 1.28%   |
| Unknown | 2        | 1.28%   |
| 2007    | 1        | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 156      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 154      | 98.72%  |
| Yes  | 2        | 1.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 52       | 32.5%   |
| 16.01-24.0  | 43       | 26.88%  |
| 4.01-8.0    | 29       | 18.13%  |
| 32.01-64.0  | 17       | 10.63%  |
| 2.01-3.0    | 12       | 7.5%    |
| 24.01-32.0  | 2        | 1.25%   |
| 64.01-256.0 | 2        | 1.25%   |
| 0.51-1.0    | 2        | 1.25%   |
| 1.01-2.0    | 1        | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 72       | 45.28%  |
| 0.51-1.0 | 61       | 38.36%  |
| 1.01-2.0 | 18       | 11.32%  |
| 2.01-3.0 | 4        | 2.52%   |
| 3.01-4.0 | 3        | 1.89%   |
| 0        | 1        | 0.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 80       | 49.08%  |
| 0      | 48       | 29.45%  |
| 2      | 26       | 15.95%  |
| 3      | 5        | 3.07%   |
| 5      | 3        | 1.84%   |
| 4      | 1        | 0.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 143      | 91.08%  |
| Yes       | 14       | 8.92%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 154      | 98.72%  |
| No        | 2        | 1.28%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 126      | 80.77%  |
| Yes       | 30       | 19.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 133      | 85.26%  |
| Yes       | 23       | 14.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| China   | 156      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Beijing          | 24       | 14.04%  |
| Shenzhen         | 19       | 11.11%  |
| Shanghai         | 16       | 9.36%   |
| Jinrongjie       | 9        | 5.26%   |
| Guangzhou        | 8        | 4.68%   |
| Chengdu          | 8        | 4.68%   |
| Zhengzhou        | 7        | 4.09%   |
| Xi'an            | 5        | 2.92%   |
| Suzhou           | 5        | 2.92%   |
| Hangzhou         | 5        | 2.92%   |
| Shijiazhuang     | 4        | 2.34%   |
| Wuhan            | 3        | 1.75%   |
| Shenyang         | 3        | 1.75%   |
| Nanjing          | 3        | 1.75%   |
| Chongqing        | 3        | 1.75%   |
| Yancheng         | 2        | 1.17%   |
| Xiamen           | 2        | 1.17%   |
| Qingdao          | 2        | 1.17%   |
| Ningbo           | 2        | 1.17%   |
| Liuzhou          | 2        | 1.17%   |
| Zhongshan        | 1        | 0.58%   |
| Zhangjiakou      | 1        | 0.58%   |
| Xicheng District | 1        | 0.58%   |
| Wuxi             | 1        | 0.58%   |
| Wenzhou          | 1        | 0.58%   |
| Tongshan         | 1        | 0.58%   |
| Tieling          | 1        | 0.58%   |
| Tianjin          | 1        | 0.58%   |
| Taohua           | 1        | 0.58%   |
| Songjiang        | 1        | 0.58%   |
| Shahekou         | 1        | 0.58%   |
| Qinnan           | 1        | 0.58%   |
| Qingpu           | 1        | 0.58%   |
| Putuo            | 1        | 0.58%   |
| Nanning          | 1        | 0.58%   |
| Muping           | 1        | 0.58%   |
| Kunming          | 1        | 0.58%   |
| Kuiju            | 1        | 0.58%   |
| Jinhua           | 1        | 0.58%   |
| Jilin City       | 1        | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 21       | 38     | 14.58%  |
| Seagate             | 21       | 31     | 14.58%  |
| Samsung Electronics | 19       | 32     | 13.19%  |
| Intel               | 11       | 11     | 7.64%   |
| Toshiba             | 9        | 13     | 6.25%   |
| SanDisk             | 8        | 14     | 5.56%   |
| FORESEE             | 4        | 5      | 2.78%   |
| China               | 4        | 7      | 2.78%   |
| Transcend           | 3        | 4      | 2.08%   |
| KIOXIA-EXCERIA      | 3        | 4      | 2.08%   |
| Kingston            | 3        | 4      | 2.08%   |
| Hitachi             | 3        | 3      | 2.08%   |
| Hewlett-Packard     | 3        | 5      | 2.08%   |
| Plextor             | 2        | 3      | 1.39%   |
| Netac               | 2        | 2      | 1.39%   |
| HGST                | 2        | 7      | 1.39%   |
| Faspeed             | 2        | 4      | 1.39%   |
| tigo                | 1        | 1      | 0.69%   |
| SK hynix            | 1        | 1      | 0.69%   |
| ShineDisk           | 1        | 1      | 0.69%   |
| Ramsta              | 1        | 1      | 0.69%   |
| ORICO               | 1        | 1      | 0.69%   |
| NVMe                | 1        | 2      | 0.69%   |
| Micron Technology   | 1        | 2      | 0.69%   |
| LITEONIT            | 1        | 1      | 0.69%   |
| Lenovo              | 1        | 1      | 0.69%   |
| KingSpec            | 1        | 1      | 0.69%   |
| KINGSHARE           | 1        | 1      | 0.69%   |
| Kingchuxing         | 1        | 1      | 0.69%   |
| GLOWAY              | 1        | 2      | 0.69%   |
| GALAX               | 1        | 1      | 0.69%   |
| FREEBSD             | 1        | 1      | 0.69%   |
| Crucial             | 1        | 2      | 0.69%   |
| Colorful            | 1        | 1      | 0.69%   |
| Centerm             | 1        | 1      | 0.69%   |
| BORY                | 1        | 2      | 0.69%   |
| BIWIN               | 1        | 3      | 0.69%   |
| Apacer              | 1        | 1      | 0.69%   |
| aigo                | 1        | 1      | 0.69%   |
| Advantech           | 1        | 1      | 0.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST1000DM003-1SB102 1TB  | 4        | 2.44%   |
| Seagate ST500DM002-1BD142 500GB | 3        | 1.83%   |
| Seagate ST9320325AS 320GB       | 2        | 1.22%   |
| KIOXIA-EXCERIA SATA SSD 240GB   | 2        | 1.22%   |
| Intel SSDSA2SH032G1GN 32GB      | 2        | 1.22%   |
| HP VK000480GWCNQ 480GB          | 2        | 1.22%   |
| WDC WUH721414ALE6L4 14TB        | 1        | 0.61%   |
| WDC WDS500G2B0C-00PXH0 500GB    | 1        | 0.61%   |
| WDC WDS500G1B0C-00S6U0 500GB    | 1        | 0.61%   |
| WDC WDS100T2B0C-00PXH0 1TB      | 1        | 0.61%   |
| WDC WD7500LPCX-00KHST0 752GB    | 1        | 0.61%   |
| WDC WD6401AALS-00L3B2 640GB     | 1        | 0.61%   |
| WDC WD5000LPLX-08ZNTT0 500GB    | 1        | 0.61%   |
| WDC WD5000LPCX-24C6HT0 500GB    | 1        | 0.61%   |
| WDC WD5000LPCX-00VHAT0 500GB    | 1        | 0.61%   |
| WDC WD5000BPVT-00HXZT1 500GB    | 1        | 0.61%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 1        | 0.61%   |
| WDC WD5000AAKX-083CA0 500GB     | 1        | 0.61%   |
| WDC WD5000AAKX-001CA0 500GB     | 1        | 0.61%   |
| WDC WD40NDZW-11BCSS1 4TB        | 1        | 0.61%   |
| WDC WD40EZAZ-00ZGHB0 4TB        | 1        | 0.61%   |
| WDC WD4005FZBX-00K5WB0 4TB      | 1        | 0.61%   |
| WDC WD3200AAJS-00L7A0 320GB     | 1        | 0.61%   |
| WDC WD30EZRZ-00WN9B0 3TB        | 1        | 0.61%   |
| WDC WD23PURZ-85C5HY0 2TB        | 1        | 0.61%   |
| WDC WD20SPZX-22UA7T0 2TB        | 1        | 0.61%   |
| WDC WD2003FYYS-007BA0 2TB       | 1        | 0.61%   |
| WDC WD1600BEVT-22ZCT0 160GB     | 1        | 0.61%   |
| WDC WD1600AAJS-22L7A0 160GB     | 1        | 0.61%   |
| WDC WD120EMAZ-11BLFA0 12TB      | 1        | 0.61%   |
| WDC WD10SPZX-00Z10T0 1TB        | 1        | 0.61%   |
| WDC WD10SPCX-00KHST0 1TB        | 1        | 0.61%   |
| WDC WD10EZEX-22MFCA0 1TB        | 1        | 0.61%   |
| WDC WD10EZEX-21WN4A0 1TB        | 1        | 0.61%   |
| WDC WD10EJRX-89N74Y0 1TB        | 1        | 0.61%   |
| WDC WD10EARS-003BB1 1TB         | 1        | 0.61%   |
| WDC PC SN520 NVMe 256GB         | 1        | 0.61%   |
| Transcend TS64GMSA230S 64GB     | 1        | 0.61%   |
| Transcend TS4GCF150 4GB         | 1        | 0.61%   |
| Transcend TS128GMTS400 128GB    | 1        | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 21       | 31     | 39.62%  |
| WDC                 | 20       | 34     | 37.74%  |
| Toshiba             | 5        | 5      | 9.43%   |
| Hitachi             | 3        | 3      | 5.66%   |
| HGST                | 2        | 7      | 3.77%   |
| Samsung Electronics | 1        | 1      | 1.89%   |
| Hewlett-Packard     | 1        | 1      | 1.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 13     | 14.47%  |
| SanDisk             | 8        | 14     | 10.53%  |
| Intel               | 8        | 8      | 10.53%  |
| FORESEE             | 4        | 5      | 5.26%   |
| China               | 4        | 7      | 5.26%   |
| Transcend           | 3        | 4      | 3.95%   |
| Toshiba             | 3        | 7      | 3.95%   |
| KIOXIA-EXCERIA      | 3        | 4      | 3.95%   |
| Kingston            | 3        | 4      | 3.95%   |
| Netac               | 2        | 2      | 2.63%   |
| Hewlett-Packard     | 2        | 4      | 2.63%   |
| faspeed             | 2        | 4      | 2.63%   |
| tigo                | 1        | 1      | 1.32%   |
| SK hynix            | 1        | 1      | 1.32%   |
| ShineDisk           | 1        | 1      | 1.32%   |
| Ramsta              | 1        | 1      | 1.32%   |
| Plextor             | 1        | 1      | 1.32%   |
| ORICO               | 1        | 1      | 1.32%   |
| NVMe                | 1        | 1      | 1.32%   |
| Micron Technology   | 1        | 2      | 1.32%   |
| LITEONIT            | 1        | 1      | 1.32%   |
| Lenovo              | 1        | 1      | 1.32%   |
| KingSpec            | 1        | 1      | 1.32%   |
| KINGSHARE           | 1        | 1      | 1.32%   |
| Kingchuxing         | 1        | 1      | 1.32%   |
| GALAX               | 1        | 1      | 1.32%   |
| FREEBSD             | 1        | 1      | 1.32%   |
| Colorful            | 1        | 1      | 1.32%   |
| Centerm             | 1        | 1      | 1.32%   |
| BORY                | 1        | 2      | 1.32%   |
| BIWIN               | 1        | 3      | 1.32%   |
| Apacer              | 1        | 1      | 1.32%   |
| aigo                | 1        | 1      | 1.32%   |
| Advantech           | 1        | 1      | 1.32%   |
| A-DATA Technology   | 1        | 2      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 72       | 104    | 52.17%  |
| HDD  | 45       | 82     | 32.61%  |
| NVMe | 21       | 33     | 15.22%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 102      | 186    | 82.93%  |
| NVMe | 21       | 33     | 17.07%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 88       | 137    | 69.84%  |
| 0.51-1.0   | 20       | 24     | 15.87%  |
| 1.01-2.0   | 9        | 10     | 7.14%   |
| 3.01-4.0   | 3        | 6      | 2.38%   |
| 4.01-10.0  | 3        | 4      | 2.38%   |
| 2.01-3.0   | 2        | 3      | 1.59%   |
| 10.01-20.0 | 1        | 2      | 0.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 54       | 33.33%  |
| 1-20       | 36       | 22.22%  |
| 251-500    | 27       | 16.67%  |
| 21-50      | 16       | 9.88%   |
| 51-100     | 13       | 8.02%   |
| 501-1000   | 10       | 6.17%   |
| 1001-2000  | 5        | 3.09%   |
| Unknown    | 1        | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 147      | 89.09%  |
| 21-50    | 9        | 5.45%   |
| 51-100   | 5        | 3.03%   |
| 101-250  | 2        | 1.21%   |
| 501-1000 | 1        | 0.61%   |
| Unknown  | 1        | 0.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000BPVT-00HXZT1 500GB      | 1        | 1      | 4.35%   |
| WDC WD5000AAKX-083CA0 500GB       | 1        | 1      | 4.35%   |
| WDC WD5000AAKX-001CA0 500GB       | 1        | 1      | 4.35%   |
| WDC WD1600AAJS-22L7A0 160GB       | 1        | 1      | 4.35%   |
| WDC WD10EJRX-89N74Y0 1TB          | 1        | 1      | 4.35%   |
| SK hynix HFS064G3AMNB-2220A 64GB  | 1        | 1      | 4.35%   |
| ShineDisk M667 120G               | 1        | 1      | 4.35%   |
| Seagate ST9320325AS 320GB         | 1        | 2      | 4.35%   |
| Seagate ST3320620AS 320GB         | 1        | 1      | 4.35%   |
| Seagate ST3320418AS 320GB         | 1        | 2      | 4.35%   |
| Seagate ST31500541AS 1.5TB        | 1        | 1      | 4.35%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 4.35%   |
| Samsung Electronics HM250HI 250GB | 1        | 1      | 4.35%   |
| Intel SSDSA2M120G2GC 120GB        | 1        | 1      | 4.35%   |
| Intel SSDPEKKW256G7 256GB         | 1        | 1      | 4.35%   |
| Hitachi HTS723232A7A364 320GB     | 1        | 1      | 4.35%   |
| HGST HTS725050A7E630 500GB        | 1        | 5      | 4.35%   |
| faspeed M3-360G                   | 1        | 3      | 4.35%   |
| Colorful SL500 640GB              | 1        | 1      | 4.35%   |
| China XJH-32GB                    | 1        | 1      | 4.35%   |
| Centerm SSD 8GB                   | 1        | 1      | 4.35%   |
| BORY M500 16G                     | 1        | 2      | 4.35%   |
| BIWIN SSD 32GB                    | 1        | 3      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 21.74%  |
| Seagate             | 5        | 7      | 21.74%  |
| Intel               | 2        | 2      | 8.7%    |
| SK hynix            | 1        | 1      | 4.35%   |
| ShineDisk           | 1        | 1      | 4.35%   |
| Samsung Electronics | 1        | 1      | 4.35%   |
| Hitachi             | 1        | 1      | 4.35%   |
| HGST                | 1        | 5      | 4.35%   |
| faspeed             | 1        | 3      | 4.35%   |
| Colorful            | 1        | 1      | 4.35%   |
| China               | 1        | 1      | 4.35%   |
| Centerm             | 1        | 1      | 4.35%   |
| BORY                | 1        | 2      | 4.35%   |
| BIWIN               | 1        | 3      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 38.46%  |
| Seagate             | 5        | 7      | 38.46%  |
| Samsung Electronics | 1        | 1      | 7.69%   |
| Hitachi             | 1        | 1      | 7.69%   |
| HGST                | 1        | 5      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 19     | 54.55%  |
| SSD  | 9        | 14     | 40.91%  |
| NVMe | 1        | 1      | 4.55%   |

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
| Works    | 96       | 181    | 80.67%  |
| Malfunc  | 20       | 34     | 16.81%  |
| Detected | 3        | 4      | 2.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel                                   | 121      | 61.42%  |
| AMD                                     | 23       | 11.68%  |
| Samsung Electronics                     | 10       | 5.08%   |
| SanDisk                                 | 7        | 3.55%   |
| MAXIO Technology (Hangzhou)             | 5        | 2.54%   |
| Phison Electronics                      | 4        | 2.03%   |
| KIOXIA                                  | 4        | 2.03%   |
| Silicon Motion                          | 3        | 1.52%   |
| ASMedia Technology                      | 3        | 1.52%   |
| Toshiba                                 | 2        | 1.02%   |
| Nvidia                                  | 2        | 1.02%   |
| Broadcom / LSI                          | 2        | 1.02%   |
| SK hynix                                | 1        | 0.51%   |
| Shenzhen Unionmemory Information System | 1        | 0.51%   |
| Shenzhen Shichuangyi Electronics        | 1        | 0.51%   |
| Shenzhen Longsys Electronics            | 1        | 0.51%   |
| Micron/Crucial Technology               | 1        | 0.51%   |
| Lite-On Technology                      | 1        | 0.51%   |
| Kingston Technology Company             | 1        | 0.51%   |
| JMicron Technology                      | 1        | 0.51%   |
| INNOGRIT                                | 1        | 0.51%   |
| Hosin Global Electronics                | 1        | 0.51%   |
| Unknown                                 | 1        | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 13       | 5.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13       | 5.65%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 11       | 4.78%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 9        | 3.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8        | 3.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7        | 3.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6        | 2.61%   |
| Intel NVMe Optane Memory Series                                                  | 6        | 2.61%   |
| Intel Alder Lake-N SATA AHCI Controller                                          | 6        | 2.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 6        | 2.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 5        | 2.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4        | 1.74%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 4        | 1.74%   |
| Intel Tiger Lake-LP SATA Controller                                              | 4        | 1.74%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 4        | 1.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4        | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4        | 1.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4        | 1.74%   |
| AMD 400 Series Chipset SATA Controller                                           | 4        | 1.74%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 3        | 1.3%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 3        | 1.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3        | 1.3%    |
| Intel SATA Controller [RAID mode]                                                | 3        | 1.3%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3        | 1.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3        | 1.3%    |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 3        | 1.3%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3        | 1.3%    |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                            | 2        | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2        | 0.87%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 2        | 0.87%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                              | 2        | 0.87%   |
| Nvidia MCP61 SATA Controller                                                     | 2        | 0.87%   |
| Nvidia MCP61 IDE                                                                 | 2        | 0.87%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2        | 0.87%   |
| KIOXIA Exceria Plus G3 NVMe SSD (DRAM-less)                                      | 2        | 0.87%   |
| Intel SSD 660P Series                                                            | 2        | 0.87%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2        | 0.87%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2        | 0.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2        | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 124      | 62%     |
| NVMe | 50       | 25%     |
| IDE  | 20       | 10%     |
| RAID | 5        | 2.5%    |
| SAS  | 1        | 0.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 126      | 80.77%  |
| AMD     | 27       | 17.31%  |
| ARM     | 2        | 1.28%   |
| Unknown | 1        | 0.64%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz           | 12       | 7.64%   |
| Intel Celeron N5105 @ 2.00GHz               | 9        | 5.73%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 8        | 5.1%    |
| Intel N100                                  | 5        | 3.18%   |
| Intel Atom CPU D525 @ 1.80GHz               | 5        | 3.18%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 3        | 1.91%   |
| Intel Pentium CPU G3260T @ 2.90GHz          | 2        | 1.27%   |
| Intel N150                                  | 2        | 1.27%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.27%   |
| Intel Core i3-8100T CPU @ 3.10GHz           | 2        | 1.27%   |
| Intel Celeron CPU N3150 @ 1.60GHz           | 2        | 1.27%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 2        | 1.27%   |
| Intel Atom CPU C3558 @ 2.20GHz              | 2        | 1.27%   |
| Intel 12th Gen Core i7-1260P                | 2        | 1.27%   |
| ARM Cortex-A53 r0p4                         | 2        | 1.27%   |
| AMD Ryzen 7 5825U with Radeon Graphics      | 2        | 1.27%   |
| Intel Xeon CPU X5647 @ 2.93GHz              | 1        | 0.64%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1        | 0.64%   |
| Intel Xeon CPU E5-2676 v3 @ 2.40GHz         | 1        | 0.64%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.64%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz         | 1        | 0.64%   |
| Intel Xeon CPU E3-1265L v3 @ 2.50GHz        | 1        | 0.64%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 0.64%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.64%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1        | 0.64%   |
| Intel Xeon                                  | 1        | 0.64%   |
| Intel Pentium Gold 8505                     | 1        | 0.64%   |
| Intel Pentium Gold 7505 @ 2.00GHz           | 1        | 0.64%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 0.64%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1        | 0.64%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 0.64%   |
| Intel Pentium CPU G3460T @ 3.00GHz          | 1        | 0.64%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 0.64%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 0.64%   |
| Intel Genuine CPU @ 2.40GHz                 | 1        | 0.64%   |
| Intel Genuine CPU 0000 @ 2.50GHz            | 1        | 0.64%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1        | 0.64%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 0.64%   |
| Intel Core i7-4785T CPU @ 2.20GHz           | 1        | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 44       | 28.03%  |
| Other                   | 16       | 10.19%  |
| Intel Core i5           | 14       | 8.92%   |
| Intel Atom              | 12       | 7.64%   |
| Intel Xeon              | 10       | 6.37%   |
| Intel Core i3           | 9        | 5.73%   |
| Intel Core i7           | 8        | 5.1%    |
| Intel Pentium           | 7        | 4.46%   |
| AMD Ryzen 7             | 5        | 3.18%   |
| AMD Ryzen 5             | 5        | 3.18%   |
| AMD Athlon II X4        | 3        | 1.91%   |
| Intel Pentium Gold      | 2        | 1.27%   |
| Intel Genuine           | 2        | 1.27%   |
| Intel Core 2 Duo        | 2        | 1.27%   |
| ARM Cortex              | 2        | 1.27%   |
| AMD Ryzen 9             | 2        | 1.27%   |
| AMD Ryzen 3 PRO         | 2        | 1.27%   |
| AMD GX                  | 2        | 1.27%   |
| AMD G                   | 2        | 1.27%   |
| Intel Pentium Dual-Core | 1        | 0.64%   |
| Intel Core 2 Quad       | 1        | 0.64%   |
| AMD Ryzen 3             | 1        | 0.64%   |
| AMD Phenom II X4        | 1        | 0.64%   |
| AMD FX                  | 1        | 0.64%   |
| AMD Athlon X2           | 1        | 0.64%   |
| AMD Athlon              | 1        | 0.64%   |
| AMD A10                 | 1        | 0.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 88       | 55.7%   |
| 2       | 38       | 24.05%  |
| 8       | 8        | 5.06%   |
| 6       | 7        | 4.43%   |
| 12      | 5        | 3.16%   |
| 16      | 4        | 2.53%   |
| 24      | 2        | 1.27%   |
| Unknown | 2        | 1.27%   |
| 28      | 1        | 0.63%   |
| 20      | 1        | 0.63%   |
| 10      | 1        | 0.63%   |
| 1       | 1        | 0.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 152      | 97.44%  |
| Unknown | 3        | 1.92%   |
| 2       | 1        | 0.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 109      | 69.43%  |
| 2       | 45       | 28.66%  |
| Unknown | 3        | 1.91%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 29       | 18.47%  |
| Silvermont    | 16       | 10.19%  |
| Haswell       | 16       | 10.19%  |
| KabyLake      | 12       | 7.64%   |
| IvyBridge     | 9        | 5.73%   |
| Goldmont plus | 9        | 5.73%   |
| Goldmont      | 8        | 5.1%    |
| Bonnell       | 7        | 4.46%   |
| Zen 3         | 5        | 3.18%   |
| Skylake       | 5        | 3.18%   |
| CometLake     | 5        | 3.18%   |
| Zen           | 4        | 2.55%   |
| TigerLake     | 4        | 2.55%   |
| SandyBridge   | 4        | 2.55%   |
| Zen+          | 3        | 1.91%   |
| Penryn        | 3        | 1.91%   |
| K10           | 3        | 1.91%   |
| Zen 2         | 2        | 1.27%   |
| Westmere      | 2        | 1.27%   |
| Piledriver    | 2        | 1.27%   |
| K10 Llano     | 2        | 1.27%   |
| Jaguar        | 2        | 1.27%   |
| Broadwell     | 2        | 1.27%   |
| Bobcat        | 2        | 1.27%   |
| Core          | 1        | 0.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 105      | 68.18%  |
| AMD                        | 23       | 14.94%  |
| Nvidia                     | 21       | 13.64%  |
| RDC Semiconductor          | 2        | 1.3%    |
| ASPEED Technology          | 2        | 1.3%    |
| Matrox Electronics Systems | 1        | 0.65%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13       | 8.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10       | 6.41%   |
| Intel JasperLake [UHD Graphics]                                                          | 10       | 6.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9        | 5.77%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6        | 3.85%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 6        | 3.85%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5        | 3.21%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4        | 2.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4        | 2.56%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3        | 1.92%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3        | 1.92%   |
| Intel Kaby Lake-U GT1 [HD Graphics 610]                                                  | 3        | 1.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 1.92%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 3        | 1.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 1.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2        | 1.28%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2        | 1.28%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 2        | 1.28%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 2        | 1.28%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2        | 1.28%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2        | 1.28%   |
| Intel Alder Lake-N [Intel Graphics]                                                      | 2        | 1.28%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2        | 1.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 1.28%   |
| AMD Barcelo                                                                              | 2        | 1.28%   |
| Unknown                                                                                  | 2        | 1.28%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 0.64%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.64%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 0.64%   |
| Nvidia GP106 [P106-100]                                                                  | 1        | 0.64%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.64%   |
| Nvidia GP106 [GeForce GTX 1060 5GB]                                                      | 1        | 0.64%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 0.64%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.64%   |
| Nvidia GK107 [GeForce GT 740]                                                            | 1        | 0.64%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 0.64%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1        | 0.64%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1        | 0.64%   |
| Nvidia GA106 [RTX A2000 12GB]                                                            | 1        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| 1 x Intel             | 97       | 61.78%  |
| 1 x AMD               | 21       | 13.38%  |
| 1 x Nvidia            | 20       | 12.74%  |
| 2 x Intel             | 6        | 3.82%   |
| Other                 | 5        | 3.18%   |
| 1 x RDC Semiconductor | 2        | 1.27%   |
| Intel + Nvidia        | 2        | 1.27%   |
| 2 x AMD               | 1        | 0.64%   |
| 1 x Matrox            | 1        | 0.64%   |
| 1 x ASPEED            | 1        | 0.64%   |
| AMD + ASPEED          | 1        | 0.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 136      | 87.18%  |
| Proprietary | 13       | 8.33%   |
| Unknown     | 7        | 4.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 141      | 90.38%  |
| 1.01-2.0   | 3        | 1.92%   |
| 7.01-8.0   | 2        | 1.28%   |
| 5.01-6.0   | 2        | 1.28%   |
| 3.01-4.0   | 2        | 1.28%   |
| 0.51-1.0   | 2        | 1.28%   |
| 0.01-0.5   | 2        | 1.28%   |
| 4.01-5.0   | 1        | 0.64%   |
| 8.01-16.0  | 1        | 0.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 6        | 16.67%  |
| AOC                 | 4        | 11.11%  |
| Philips             | 3        | 8.33%   |
| Lenovo              | 3        | 8.33%   |
| ViewSonic           | 2        | 5.56%   |
| Mi                  | 2        | 5.56%   |
| Dostyle             | 2        | 5.56%   |
| ZL_                 | 1        | 2.78%   |
| Samsung Electronics | 1        | 2.78%   |
| SAC                 | 1        | 2.78%   |
| RTK                 | 1        | 2.78%   |
| IPS                 | 1        | 2.78%   |
| Haier               | 1        | 2.78%   |
| GRR                 | 1        | 2.78%   |
| GKE                 | 1        | 2.78%   |
| FSD                 | 1        | 2.78%   |
| FLY                 | 1        | 2.78%   |
| Eizo                | 1        | 2.78%   |
| CAN                 | 1        | 2.78%   |
| BenQ                | 1        | 2.78%   |
| Acer                | 1        | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Dostyle DM320 DST3200 1920x1080 700x390mm 31.5-inch               | 2        | 5.56%   |
| ZL_ zhuoyue-HDMI ZL_2716 2560x1440 600x330mm 27.0-inch            | 1        | 2.78%   |
| ViewSonic VX2880-4K-HDU VSCA33A 3840x2160 630x360mm 28.6-inch     | 1        | 2.78%   |
| ViewSonic VA926 Series VSC7D20 1280x1024 380x300mm 19.1-inch      | 1        | 2.78%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch | 1        | 2.78%   |
| SAC LED MONITOR SAC952D 1920x1080 470x280mm 21.5-inch             | 1        | 2.78%   |
| RTK '' RTK1920 1920x1080 336x210mm 15.6-inch                      | 1        | 2.78%   |
| Philips 298P4 PHLC0BE 2560x1080 670x280mm 28.6-inch               | 1        | 2.78%   |
| Philips 242EL PHLC094 1920x1080 520x290mm 23.4-inch               | 1        | 2.78%   |
| Philips 190V PHL0081 1440x900 400x250mm 18.6-inch                 | 1        | 2.78%   |
| Mi Redmi 27 NQ XMIE001 2560x1440 600x330mm 27.0-inch              | 1        | 2.78%   |
| Mi P27QBB-RA XMID003 2560x1440 600x340mm 27.2-inch                | 1        | 2.78%   |
| Lenovo LEN L1950wD LEN1086 1920x1080 410x260mm 19.1-inch          | 1        | 2.78%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch           | 1        | 2.78%   |
| Lenovo L197 Wide LEN1152 1440x900 410x260mm 19.1-inch             | 1        | 2.78%   |
| IPS W220A IPS3150 3840x2160 700x390mm 31.5-inch                   | 1        | 2.78%   |
| Haier HT-20216B(C) HAI2031 1920x1080 480x270mm 21.7-inch          | 1        | 2.78%   |
| GRR GRC GRR2400 1920x1080 520x310mm 23.8-inch                     | 1        | 2.78%   |
| GKE Z220W GKE0215 1920x1080 470x280mm 21.5-inch                   | 1        | 2.78%   |
| FSD F1905 FSD1850 1366x768 410x230mm 18.5-inch                    | 1        | 2.78%   |
| FLY FZ24SL FLY2400 1920x1080 530x290mm 23.8-inch                  | 1        | 2.78%   |
| Eizo CG276 ENC2400 2560x1440 600x340mm 27.2-inch                  | 1        | 2.78%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                 | 1        | 2.78%   |
| Dell S2240M DELD055 1920x1080 480x270mm 21.7-inch                 | 1        | 2.78%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                 | 1        | 2.78%   |
| Dell P2415Q DELA0C0 3840x2160 530x300mm 24.0-inch                 | 1        | 2.78%   |
| Dell E228WFP DELD015 1680x1050 470x300mm 22.0-inch                | 1        | 2.78%   |
| Dell D2421H DEL2011 1920x1080 530x300mm 24.0-inch                 | 1        | 2.78%   |
| CAN F55C CAN0055 3840x2160 1210x680mm 54.6-inch                   | 1        | 2.78%   |
| BenQ FP91G+ BNQ76A6 1280x1024 380x300mm 19.1-inch                 | 1        | 2.78%   |
| AOC Q27P1B AOC2701 2560x1440 600x340mm 27.2-inch                  | 1        | 2.78%   |
| AOC 2778X AOC2778 2560x1440 600x340mm 27.2-inch                   | 1        | 2.78%   |
| AOC 2490W1 AOC2490 1920x1080 530x300mm 24.0-inch                  | 1        | 2.78%   |
| AOC 2479W AOC2479 1920x1080 520x290mm 23.4-inch                   | 1        | 2.78%   |
| Acer G195WV ACR0263 1440x900 410x260mm 19.1-inch                  | 1        | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 18       | 50%     |
| 2560x1440 (QHD)    | 6        | 16.67%  |
| 3840x2160 (4K)     | 4        | 11.11%  |
| 1440x900 (WXGA+)   | 3        | 8.33%   |
| 1280x1024 (SXGA)   | 2        | 5.56%   |
| 2560x1080          | 1        | 2.78%   |
| 1680x1050 (WSXGA+) | 1        | 2.78%   |
| 1366x768 (WXGA)    | 1        | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 7        | 19.44%  |
| 24     | 5        | 13.89%  |
| 23     | 5        | 13.89%  |
| 19     | 5        | 13.89%  |
| 21     | 4        | 11.11%  |
| 31     | 3        | 8.33%   |
| 28     | 2        | 5.56%   |
| 18     | 2        | 5.56%   |
| 54     | 1        | 2.78%   |
| 22     | 1        | 2.78%   |
| 15     | 1        | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 47.22%  |
| 401-500     | 9        | 25%     |
| 601-700     | 5        | 13.89%  |
| 351-400     | 3        | 8.33%   |
| 301-350     | 1        | 2.78%   |
| 1001-1500   | 1        | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 27       | 75%     |
| 16/10 | 6        | 16.67%  |
| 5/4   | 2        | 5.56%   |
| 21/9  | 1        | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 41.67%  |
| 301-350        | 7        | 19.44%  |
| 151-200        | 6        | 16.67%  |
| 351-500        | 4        | 11.11%  |
| More than 1000 | 1        | 2.78%   |
| 251-300        | 1        | 2.78%   |
| 141-150        | 1        | 2.78%   |
| 101-110        | 1        | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 22       | 61.11%  |
| 101-120 | 10       | 27.78%  |
| 121-160 | 3        | 8.33%   |
| 161-240 | 1        | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 120      | 76.43%  |
| 1     | 37       | 23.57%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 107      | 54.31%  |
| Realtek Semiconductor    | 75       | 38.07%  |
| Qualcomm Atheros         | 4        | 2.03%   |
| Mellanox Technologies    | 3        | 1.52%   |
| Broadcom                 | 3        | 1.52%   |
| Ralink Technology        | 1        | 0.51%   |
| OPPO Electronics         | 1        | 0.51%   |
| Marvell Technology Group | 1        | 0.51%   |
| Apple                    | 1        | 0.51%   |
| American Megatrends      | 1        | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 58       | 25.66%  |
| Intel Ethernet Controller I226-V                                       | 20       | 8.85%   |
| Intel I211 Gigabit Network Connection                                  | 17       | 7.52%   |
| Intel Ethernet Controller I225-V                                       | 14       | 6.19%   |
| Intel 82583V Gigabit Network Connection                                | 8        | 3.54%   |
| Realtek RTL8125 2.5GbE Controller                                      | 7        | 3.1%    |
| Intel I210 Gigabit Network Connection                                  | 6        | 2.65%   |
| Intel I350 Gigabit Network Connection                                  | 5        | 2.21%   |
| Intel Ethernet Connection I217-LM                                      | 5        | 2.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 1.77%   |
| Intel Wi-Fi 6 AX200                                                    | 4        | 1.77%   |
| Intel Ethernet Connection X553 1GbE                                    | 4        | 1.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4        | 1.77%   |
| Intel Wireless 7260                                                    | 3        | 1.33%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 3        | 1.33%   |
| Intel 82576 Gigabit Network Connection                                 | 3        | 1.33%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 1.33%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2        | 0.88%   |
| Mellanox MT27500 Family [ConnectX-3]                                   | 2        | 0.88%   |
| Intel Wireless 3165                                                    | 2        | 0.88%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2        | 0.88%   |
| Intel Ethernet Connection X553 10 GbE SFP+                             | 2        | 0.88%   |
| Intel Ethernet Connection I217-V                                       | 2        | 0.88%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 0.88%   |
| Intel 82575EB Gigabit Network Connection                               | 2        | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.44%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 0.44%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                 | 1        | 0.44%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 0.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1        | 0.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1        | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.44%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 0.44%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                           | 1        | 0.44%   |
| Ralink RT5370 Wireless Adapter                                         | 1        | 0.44%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter        | 1        | 0.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 0.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 0.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 16       | 51.61%  |
| Realtek Semiconductor | 9        | 29.03%  |
| Qualcomm Atheros      | 4        | 12.9%   |
| Ralink Technology     | 1        | 3.23%   |
| Broadcom              | 1        | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                             | 4        | 12.9%   |
| Intel Wireless 7260                                             | 3        | 9.68%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller     | 2        | 6.45%   |
| Intel Wireless 3165                                             | 2        | 6.45%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 2        | 6.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 1        | 3.23%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter         | 1        | 3.23%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1        | 3.23%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 1        | 3.23%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 1        | 3.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 1        | 3.23%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                    | 1        | 3.23%   |
| Ralink RT5370 Wireless Adapter                                  | 1        | 3.23%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1        | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1        | 3.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1        | 3.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 1        | 3.23%   |
| Intel Wireless 3160                                             | 1        | 3.23%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 1        | 3.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 1        | 3.23%   |
| Intel Alder Lake-S PCH CNVi WiFi                                | 1        | 3.23%   |
| Intel Alder Lake-N PCH CNVi WiFi                                | 1        | 3.23%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 1        | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 96       | 56.14%  |
| Realtek Semiconductor    | 69       | 40.35%  |
| Broadcom                 | 2        | 1.17%   |
| OPPO Electronics         | 1        | 0.58%   |
| Marvell Technology Group | 1        | 0.58%   |
| Apple                    | 1        | 0.58%   |
| American Megatrends      | 1        | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 58       | 30.21%  |
| Intel Ethernet Controller I226-V                                              | 20       | 10.42%  |
| Intel I211 Gigabit Network Connection                                         | 17       | 8.85%   |
| Intel Ethernet Controller I225-V                                              | 14       | 7.29%   |
| Intel 82583V Gigabit Network Connection                                       | 8        | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                             | 7        | 3.65%   |
| Intel I210 Gigabit Network Connection                                         | 6        | 3.13%   |
| Intel I350 Gigabit Network Connection                                         | 5        | 2.6%    |
| Intel Ethernet Connection I217-LM                                             | 5        | 2.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4        | 2.08%   |
| Intel Ethernet Connection X553 1GbE                                           | 4        | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4        | 2.08%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3        | 1.56%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 1.56%   |
| Intel 82574L Gigabit Network Connection                                       | 3        | 1.56%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 2        | 1.04%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.04%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 1.04%   |
| Intel 82575EB Gigabit Network Connection                                      | 2        | 1.04%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.52%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1        | 0.52%   |
| OPPO OPPO Find X3 Neo 5G RNDIS Control RNDIS Ethernet Data                    | 1        | 0.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.52%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1        | 0.52%   |
| Intel Ethernet Controller X550                                                | 1        | 0.52%   |
| Intel Ethernet Controller I225-LM                                             | 1        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.52%   |
| Intel Ethernet Connection (17) I219-LM                                        | 1        | 0.52%   |
| Intel Ethernet Connection (13) I219-LM                                        | 1        | 0.52%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.52%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 0.52%   |
| Intel 82575GB Gigabit Network Connection                                      | 1        | 0.52%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.52%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.52%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 0.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.52%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 1        | 0.52%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                               | 1        | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 154      | 82.8%   |
| WiFi     | 29       | 15.59%  |
| Unknown  | 3        | 1.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 146      | 94.19%  |
| WiFi     | 9        | 5.81%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 52       | 33.33%  |
| 1     | 32       | 20.51%  |
| 4     | 27       | 17.31%  |
| 6     | 19       | 12.18%  |
| 5     | 11       | 7.05%   |
| 3     | 8        | 5.13%   |
| 7     | 2        | 1.28%   |
| 0     | 2        | 1.28%   |
| 10    | 1        | 0.64%   |
| 9     | 1        | 0.64%   |
| 8     | 1        | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 118      | 71.52%  |
| Yes  | 47       | 28.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 14       | 60.87%  |
| Realtek Semiconductor           | 3        | 13.04%  |
| Qualcomm Atheros Communications | 2        | 8.7%    |
| Cambridge Silicon Radio         | 2        | 8.7%    |
| IMC Networks                    | 1        | 4.35%   |
| Apple                           | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 4        | 17.39%  |
| Intel AX200 Bluetooth                                       | 4        | 17.39%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2        | 8.7%    |
| Intel AX201 Bluetooth                                       | 2        | 8.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2        | 8.7%    |
| Realtek  Bluetooth 4.2 Adapter                              | 1        | 4.35%   |
| Realtek Bluetooth Adapter                                   | 1        | 4.35%   |
| Realtek Bluetooth 4.0 Adapter                               | 1        | 4.35%   |
| Qualcomm Atheros Dell Wireless 1901 Bluetooth               | 1        | 4.35%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 4.35%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 4.35%   |
| Intel AX210 Bluetooth                                       | 1        | 4.35%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1        | 4.35%   |
| Apple Bluetooth Host Controller                             | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 101      | 66.01%  |
| AMD                                          | 28       | 18.3%   |
| Nvidia                                       | 20       | 13.07%  |
| C-Media Electronics                          | 2        | 1.31%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.65%   |
| Generalplus Technology                       | 1        | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Jasper Lake HD Audio                                                                        | 10       | 5.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9        | 5.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9        | 5.14%   |
| AMD Ryzen HD Audio Controller                                                                     | 9        | 5.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8        | 4.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8        | 4.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8        | 4.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7        | 4%      |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 6        | 3.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5        | 2.86%   |
| AMD FCH Azalia Controller                                                                         | 5        | 2.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4        | 2.29%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 2.29%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4        | 2.29%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 3        | 1.71%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 3        | 1.71%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 1.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3        | 1.71%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 1.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3        | 1.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 1.71%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 3        | 1.71%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3        | 1.71%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 1.71%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 3        | 1.71%   |
| Nvidia MCP61 High Definition Audio                                                                | 2        | 1.14%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 1.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2        | 1.14%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 2        | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2        | 1.14%   |
| Intel 200 Series PCH HD Audio                                                                     | 2        | 1.14%   |
| AMD Wrestler HDMI Audio                                                                           | 2        | 1.14%   |
| AMD Radeon High Definition Audio Controller                                                       | 2        | 1.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2        | 1.14%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2        | 1.14%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 1.14%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1        | 0.57%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 0.57%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 0.57%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 34       | 20.73%  |
| Kingston            | 27       | 16.46%  |
| SK hynix            | 21       | 12.8%   |
| Unknown             | 16       | 9.76%   |
| Micron Technology   | 14       | 8.54%   |
| A-DATA Technology   | 10       | 6.1%    |
| Unknown             | 9        | 5.49%   |
| Crucial             | 6        | 3.66%   |
| Corsair             | 4        | 2.44%   |
| GeIL                | 3        | 1.83%   |
| G.Skill             | 3        | 1.83%   |
| Toshiba             | 2        | 1.22%   |
| Ramaxel Technology  | 2        | 1.22%   |
| Nanya Technology    | 2        | 1.22%   |
| GLOWAY              | 2        | 1.22%   |
| Transcend           | 1        | 0.61%   |
| tigo                | 1        | 0.61%   |
| Team                | 1        | 0.61%   |
| Ramsta              | 1        | 0.61%   |
| KINGBANK            | 1        | 0.61%   |
| Juhor               | 1        | 0.61%   |
| Elpida              | 1        | 0.61%   |
| Apacer              | 1        | 0.61%   |
| Advantech           | 1        | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown                                                    | 9        | 5.14%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 3        | 1.71%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s      | 3        | 1.71%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                 | 2        | 1.14%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                   | 2        | 1.14%   |
| Toshiba RAM HP24D4R7D4HAI-32 32GB DIMM DDR4 2400MT/s       | 2        | 1.14%   |
| SK hynix RAM HMCG66AGBSA092N 8GB SODIMM DDR5 5600MT/s      | 2        | 1.14%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s     | 2        | 1.14%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s      | 2        | 1.14%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s        | 2        | 1.14%   |
| Kingston RAM KHX3200C16FB/8G 8GB SODIMM DDR4 2400MT/s      | 2        | 1.14%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 2933MT/s       | 2        | 1.14%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s        | 2        | 1.14%   |
| GeIL RAM CL11-11-11 D3-1600 4GB DIMM DDR3 1600MT/s         | 2        | 1.14%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s    | 2        | 1.14%   |
| Crucial RAM CT16G48C40S5.C8A1 16GB SODIMM DDR5 4800MT/s    | 2        | 1.14%   |
| Unknown RAM XinJuHuo 8GB SODIMM DDR3 1600MT/s              | 1        | 0.57%   |
| Unknown RAM TMKS8G68ALFBCH-266 8192MB SODIMM DDR4 2400MT/s | 1        | 0.57%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                  | 1        | 0.57%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1        | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s                 | 1        | 0.57%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                  | 1        | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                 | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM 800MT/s                        | 1        | 0.57%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 1        | 0.57%   |
| Unknown RAM Module 1GB DIMM SDRAM                          | 1        | 0.57%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                   | 1        | 0.57%   |
| Unknown RAM IM38GS48A16-BBBHB0 8GB DIMM DDR3 1600MT/s      | 1        | 0.57%   |
| Transcend RAM TS256MLK64V3N 2GB DIMM DDR3 1067MT/s         | 1        | 0.57%   |
| tigo RAM 1600Mhz-4G 4GB DIMM DDR3 1600MT/s                 | 1        | 0.57%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s         | 1        | 0.57%   |
| SK hynix RAM Module 8GB DIMM LPDDR4 6400MT/s               | 1        | 0.57%   |
| SK hynix RAM Module 8GB DIMM DDR4 2400MT/s                 | 1        | 0.57%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB DIMM DDR3 1600MT/s       | 1        | 0.57%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1066MT/s       | 1        | 0.57%   |
| SK hynix RAM HMT325S6EFR8C-PB 2GB DIMM DDR3 1600MT/s       | 1        | 0.57%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB DIMM DDR3 1333MT/s       | 1        | 0.57%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s       | 1        | 0.57%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s    | 1        | 0.57%   |
| SK hynix RAM HMA851U6CJR6N-UH 4GB DIMM DDR4 2400MT/s       | 1        | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 72       | 48.98%  |
| DDR3    | 57       | 38.78%  |
| DDR5    | 8        | 5.44%   |
| DDR2    | 4        | 2.72%   |
| Unknown | 3        | 2.04%   |
| LPDDR4  | 2        | 1.36%   |
| SDRAM   | 1        | 0.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 78       | 52.7%   |
| SODIMM       | 66       | 44.59%  |
| Unknown      | 2        | 1.35%   |
| Row Of Chips | 1        | 0.68%   |
| RIMM         | 1        | 0.68%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 57       | 36.08%  |
| 4096  | 45       | 28.48%  |
| 16384 | 30       | 18.99%  |
| 2048  | 17       | 10.76%  |
| 32768 | 6        | 3.8%    |
| 1024  | 3        | 1.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 33       | 21.02%  |
| 3200    | 24       | 15.29%  |
| 2400    | 23       | 14.65%  |
| 2133    | 17       | 10.83%  |
| 1333    | 14       | 8.92%   |
| 2667    | 11       | 7.01%   |
| 800     | 9        | 5.73%   |
| 4800    | 6        | 3.82%   |
| 2666    | 3        | 1.91%   |
| 1867    | 3        | 1.91%   |
| 1334    | 3        | 1.91%   |
| 5600    | 2        | 1.27%   |
| 2933    | 2        | 1.27%   |
| 1066    | 2        | 1.27%   |
| 667     | 2        | 1.27%   |
| 6400    | 1        | 0.64%   |
| 1067    | 1        | 0.64%   |
| Unknown | 1        | 0.64%   |

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
| Microdia                | 1        | 20%     |
| GEMBIRD                 | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Z-Star Lenovo USB 2.0 UVC Camera | 1        | 20%     |
| Microdia Camera                  | 1        | 20%     |
| Logitech Webcam C170             | 1        | 20%     |
| Logitech C670i FHD Webcam        | 1        | 20%     |
| GEMBIRD USB2.0 PC CAMERA         | 1        | 20%     |

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
| 1     | 78       | 49.68%  |
| 0     | 58       | 36.94%  |
| 2     | 18       | 11.46%  |
| 4     | 2        | 1.27%   |
| 3     | 1        | 0.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 92       | 80.7%   |
| Net/wireless             | 9        | 7.89%   |
| Net/ethernet             | 4        | 3.51%   |
| Bluetooth                | 4        | 3.51%   |
| Sound                    | 3        | 2.63%   |
| Card reader              | 2        | 1.75%   |

