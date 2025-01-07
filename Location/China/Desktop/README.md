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

Total: 191

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| helloSystem 0.7.0 | 9        | 5.59%   |
| OPNsense 21.7.1   | 6        | 3.73%   |
| helloSystem 0.9.0 | 6        | 3.73%   |
| OPNsense 23.1.11  | 5        | 3.11%   |
| helloSystem 0.8.1 | 5        | 3.11%   |
| OPNsense 21.7.3   | 4        | 2.48%   |
| OPNsense 21.1.7   | 4        | 2.48%   |
| helloSystem 0.5.0 | 4        | 2.48%   |
| FreeBSD 13.1-p2   | 4        | 2.48%   |
| OPNsense 24.7.7   | 3        | 1.86%   |
| OPNsense 24.7.11  | 3        | 1.86%   |
| OPNsense 24.1.7   | 3        | 1.86%   |
| OPNsense 24.1.10  | 3        | 1.86%   |
| OPNsense 23.1.5   | 3        | 1.86%   |
| OPNsense 23.1.1   | 3        | 1.86%   |
| OPNsense 22.7.5   | 3        | 1.86%   |
| OPNsense 21.7.5   | 3        | 1.86%   |
| OPNsense 21.7.2   | 3        | 1.86%   |
| FreeBSD 13.2      | 3        | 1.86%   |
| OPNsense 24.7.1   | 2        | 1.24%   |
| OPNsense 24.7     | 2        | 1.24%   |
| OPNsense 23.7.9   | 2        | 1.24%   |
| OPNsense 23.7.7   | 2        | 1.24%   |
| OPNsense 23.7.5   | 2        | 1.24%   |
| OPNsense 23.7.12  | 2        | 1.24%   |
| OPNsense 23.7.1   | 2        | 1.24%   |
| OPNsense 23.1.7   | 2        | 1.24%   |
| OPNsense 22.7.2   | 2        | 1.24%   |
| OPNsense 22.1.4   | 2        | 1.24%   |
| OPNsense 22.1.2   | 2        | 1.24%   |
| OPNsense 22.1.10  | 2        | 1.24%   |
| OPNsense 21.1.6   | 2        | 1.24%   |
| OPNsense 21.1.3   | 2        | 1.24%   |
| OPNsense 21.1     | 2        | 1.24%   |
| helloSystem 0.6.0 | 2        | 1.24%   |
| helloSystem 0.4.0 | 2        | 1.24%   |
| FreeBSD 14.0-p5   | 2        | 1.24%   |
| FreeBSD 14.0      | 2        | 1.24%   |
| OPNsense 24.7.5   | 1        | 0.62%   |
| OPNsense 24.7.4   | 1        | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 76       | 59.38%  |
| helloSystem | 28       | 21.88%  |
| FreeBSD     | 22       | 17.19%  |
| OpenBSD     | 1        | 0.78%   |
| GhostBSD    | 1        | 0.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 124      | 97.64%  |
| arm64   | 2        | 1.57%   |
| powerpc | 1        | 0.79%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 85       | 66.41%  |
| helloDesktop | 29       | 22.66%  |
| KDE5         | 6        | 4.69%   |
| XFCE         | 4        | 3.13%   |
| MATE         | 2        | 1.56%   |
| i3           | 1        | 0.78%   |
| GNUstep      | 1        | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 87       | 68.5%   |
| X11     | 40       | 31.5%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 87       | 67.97%  |
| SLiM    | 29       | 22.66%  |
| SDDM    | 8        | 6.25%   |
| LightDM | 3        | 2.34%   |
| XDM     | 1        | 0.78%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 85       | 65.89%  |
| en_US   | 18       | 13.95%  |
| C       | 11       | 8.53%   |
| zh_CN   | 10       | 7.75%   |
| fr_FR   | 5        | 3.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 113      | 88.98%  |
| BIOS | 14       | 11.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Zfs    | 65       | 50%     |
| Ufs    | 52       | 40%     |
| Cd9660 | 12       | 9.23%   |
| Ffs    | 1        | 0.77%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 118      | 92.91%  |
| MBR     | 6        | 4.72%   |
| Unknown | 3        | 2.36%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 33       | 25.98%  |
| Dell                                       | 10       | 7.87%   |
| MSI                                        | 7        | 5.51%   |
| Lenovo                                     | 7        | 5.51%   |
| Gigabyte Technology                        | 7        | 5.51%   |
| Intel                                      | 6        | 4.72%   |
| ASUSTek Computer                           | 6        | 4.72%   |
| Techvision                                 | 5        | 3.94%   |
| Hewlett-Packard                            | 4        | 3.15%   |
| ASRock                                     | 4        | 3.15%   |
| ShenZhen MinWin Technology                 | 3        | 2.36%   |
| Quanmax                                    | 2        | 1.57%   |
| PAIQ                                       | 2        | 1.57%   |
| OEM                                        | 2        | 1.57%   |
| NEC Computers                              | 2        | 1.57%   |
| Colorful Technology                        | 2        | 1.57%   |
| AZW                                        | 2        | 1.57%   |
| YENTEK                                     | 1        | 0.79%   |
| YANYU                                      | 1        | 0.79%   |
| YanRay Technology                          | 1        | 0.79%   |
| WlanCN                                     | 1        | 0.79%   |
| TOPFEEL                                    | 1        | 0.79%   |
| Supermicro                                 | 1        | 0.79%   |
| Silicom                                    | 1        | 0.79%   |
| Protectli                                  | 1        | 0.79%   |
| ONDA                                       | 1        | 0.79%   |
| NORCO                                      | 1        | 0.79%   |
| MECHREVO                                   | 1        | 0.79%   |
| MAXSUN                                     | 1        | 0.79%   |
| JGINYUE                                    | 1        | 0.79%   |
| GuoGuang                                   | 1        | 0.79%   |
| Google                                     | 1        | 0.79%   |
| EVOC                                       | 1        | 0.79%   |
| DS                                         | 1        | 0.79%   |
| Colorful YuGong Technology And Development | 1        | 0.79%   |
| CNCTION-IAF-E3845                          | 1        | 0.79%   |
| Centerm                                    | 1        | 0.79%   |
| BROUNION                                   | 1        | 0.79%   |
| Biostar                                    | 1        | 0.79%   |
| AMD                                        | 1        | 0.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 35       | 27.56%  |
| Techvision TVI7309X                | 5        | 3.94%   |
| ShenZhen MinWin MW-NANO-APL-4L     | 3        | 2.36%   |
| Quanmax MITX-DNVE                  | 2        | 1.57%   |
| PAIQ EC3-BT19D4L                   | 2        | 1.57%   |
| Intel MAHOBAY                      | 2        | 1.57%   |
| AZW EQ                             | 2        | 1.57%   |
| ASRock Q1900M                      | 2        | 1.57%   |
| YENTEK ITX-B75R1                   | 1        | 0.79%   |
| YANYU ITX-N29 VER:1.5 baytrail     | 1        | 0.79%   |
| YanRay B1904                       | 1        | 0.79%   |
| WlanCN 6000 Series                 | 1        | 0.79%   |
| TOPFEEL Topone series              | 1        | 0.79%   |
| Supermicro NS-EI36S                | 1        | 0.79%   |
| Silicom 6200                       | 1        | 0.79%   |
| Protectli FW6                      | 1        | 0.79%   |
| ONDA N78G5D3 Ver:5.00              | 1        | 0.79%   |
| OEM ITX-SC3                        | 1        | 0.79%   |
| OEM B85 JHS359                     | 1        | 0.79%   |
| NORCO HB133                        | 1        | 0.79%   |
| NEC Computers SHARKBAY             | 1        | 0.79%   |
| NEC Computers PC-MC32MBZCEECH      | 1        | 0.79%   |
| MSI MS-7C82                        | 1        | 0.79%   |
| MSI MS-7C37                        | 1        | 0.79%   |
| MSI MS-7B89                        | 1        | 0.79%   |
| MSI MS-7A38                        | 1        | 0.79%   |
| MSI MS-7972                        | 1        | 0.79%   |
| MSI MS-7817                        | 1        | 0.79%   |
| MSI MS-7758                        | 1        | 0.79%   |
| MAXSUN MS-H110D4L FS M.2           | 1        | 0.79%   |
| Lenovo YangTianW2090v-00           | 1        | 0.79%   |
| Lenovo YangTianM6880N              | 1        | 0.79%   |
| Lenovo YangTianA8800T              | 1        | 0.79%   |
| Lenovo ThinkCentre M93p 10AA0020CN | 1        | 0.79%   |
| Lenovo SHARKBAY SDK0A46860 WIN     | 1        | 0.79%   |
| Lenovo SHARKBAY 0B98401 WIN        | 1        | 0.79%   |
| Lenovo IdeaCentre B545 10100       | 1        | 0.79%   |
| JGINYUE X99-8D4/2.5G Server        | 1        | 0.79%   |
| Intel X99                          | 1        | 0.79%   |
| Intel X58                          | 1        | 0.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 35       | 27.56%  |
| Techvision TVI7309X            | 5        | 3.94%   |
| Dell OptiPlex                  | 5        | 3.94%   |
| ShenZhen MinWin MW-NANO-APL-4L | 3        | 2.36%   |
| Dell Precision                 | 3        | 2.36%   |
| ASUS TUF                       | 3        | 2.36%   |
| Quanmax MITX-DNVE              | 2        | 1.57%   |
| PAIQ EC3-BT19D4L               | 2        | 1.57%   |
| Lenovo SHARKBAY                | 2        | 1.57%   |
| Intel MAHOBAY                  | 2        | 1.57%   |
| AZW EQ                         | 2        | 1.57%   |
| ASRock Q1900M                  | 2        | 1.57%   |
| YENTEK ITX-B75R1               | 1        | 0.79%   |
| YANYU ITX-N29                  | 1        | 0.79%   |
| YanRay B1904                   | 1        | 0.79%   |
| WlanCN 6000                    | 1        | 0.79%   |
| TOPFEEL Topone                 | 1        | 0.79%   |
| Supermicro NS-EI36S            | 1        | 0.79%   |
| Silicom 6200                   | 1        | 0.79%   |
| Protectli FW6                  | 1        | 0.79%   |
| ONDA N78G5D3                   | 1        | 0.79%   |
| OEM ITX-SC3                    | 1        | 0.79%   |
| OEM B85                        | 1        | 0.79%   |
| NORCO HB133                    | 1        | 0.79%   |
| NEC Computers SHARKBAY         | 1        | 0.79%   |
| NEC Computers PC-MC32MBZCEECH  | 1        | 0.79%   |
| MSI MS-7C82                    | 1        | 0.79%   |
| MSI MS-7C37                    | 1        | 0.79%   |
| MSI MS-7B89                    | 1        | 0.79%   |
| MSI MS-7A38                    | 1        | 0.79%   |
| MSI MS-7972                    | 1        | 0.79%   |
| MSI MS-7817                    | 1        | 0.79%   |
| MSI MS-7758                    | 1        | 0.79%   |
| MAXSUN MS-H110D4L              | 1        | 0.79%   |
| Lenovo YangTianW2090v-00       | 1        | 0.79%   |
| Lenovo YangTianM6880N          | 1        | 0.79%   |
| Lenovo YangTianA8800T          | 1        | 0.79%   |
| Lenovo ThinkCentre             | 1        | 0.79%   |
| Lenovo IdeaCentre              | 1        | 0.79%   |
| JGINYUE X99-8D4                | 1        | 0.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2022    | 15       | 11.81%  |
| 2023    | 14       | 11.02%  |
| 2021    | 12       | 9.45%   |
| 2020    | 11       | 8.66%   |
| 2019    | 11       | 8.66%   |
| 2017    | 11       | 8.66%   |
| 2012    | 10       | 7.87%   |
| 2018    | 7        | 5.51%   |
| 2014    | 7        | 5.51%   |
| 2013    | 7        | 5.51%   |
| 2016    | 5        | 3.94%   |
| 2015    | 4        | 3.15%   |
| 2024    | 3        | 2.36%   |
| 2010    | 3        | 2.36%   |
| 2011    | 2        | 1.57%   |
| 2008    | 2        | 1.57%   |
| Unknown | 2        | 1.57%   |
| 2007    | 1        | 0.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 127      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 125      | 98.43%  |
| Yes  | 2        | 1.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 42       | 32.56%  |
| 16.01-24.0  | 30       | 23.26%  |
| 4.01-8.0    | 25       | 19.38%  |
| 32.01-64.0  | 14       | 10.85%  |
| 2.01-3.0    | 11       | 8.53%   |
| 24.01-32.0  | 2        | 1.55%   |
| 64.01-256.0 | 2        | 1.55%   |
| 0.51-1.0    | 2        | 1.55%   |
| 1.01-2.0    | 1        | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 65       | 50.78%  |
| 0.51-1.0 | 44       | 34.38%  |
| 1.01-2.0 | 13       | 10.16%  |
| 2.01-3.0 | 3        | 2.34%   |
| 3.01-4.0 | 2        | 1.56%   |
| 0        | 1        | 0.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 71       | 53.79%  |
| 0      | 31       | 23.48%  |
| 2      | 21       | 15.91%  |
| 3      | 5        | 3.79%   |
| 5      | 3        | 2.27%   |
| 4      | 1        | 0.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 116      | 90.63%  |
| Yes       | 12       | 9.38%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 125      | 98.43%  |
| No        | 2        | 1.57%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 80.31%  |
| Yes       | 25       | 19.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 108      | 85.04%  |
| Yes       | 19       | 14.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| China   | 127      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Beijing          | 16       | 11.51%  |
| Shenzhen         | 15       | 10.79%  |
| Shanghai         | 14       | 10.07%  |
| Jinrongjie       | 8        | 5.76%   |
| Chengdu          | 8        | 5.76%   |
| Zhengzhou        | 7        | 5.04%   |
| Guangzhou        | 6        | 4.32%   |
| Suzhou           | 5        | 3.6%    |
| Xi'an            | 4        | 2.88%   |
| Hangzhou         | 4        | 2.88%   |
| Shenyang         | 3        | 2.16%   |
| Chongqing        | 3        | 2.16%   |
| Yancheng         | 2        | 1.44%   |
| Xiamen           | 2        | 1.44%   |
| Wuhan            | 2        | 1.44%   |
| Qingdao          | 2        | 1.44%   |
| Ningbo           | 2        | 1.44%   |
| Liuzhou          | 2        | 1.44%   |
| Zhongshan        | 1        | 0.72%   |
| Zhangjiakou      | 1        | 0.72%   |
| Xicheng District | 1        | 0.72%   |
| Wuxi             | 1        | 0.72%   |
| Wenzhou          | 1        | 0.72%   |
| Tongshan         | 1        | 0.72%   |
| Tieling          | 1        | 0.72%   |
| Taohua           | 1        | 0.72%   |
| Songjiang        | 1        | 0.72%   |
| Shijiazhuang     | 1        | 0.72%   |
| Shahekou         | 1        | 0.72%   |
| Qinnan           | 1        | 0.72%   |
| Qingpu           | 1        | 0.72%   |
| Putuo            | 1        | 0.72%   |
| Nanjing          | 1        | 0.72%   |
| Muping           | 1        | 0.72%   |
| Kunming          | 1        | 0.72%   |
| Kuiju            | 1        | 0.72%   |
| Jinhua           | 1        | 0.72%   |
| Jiangbei         | 1        | 0.72%   |
| Huangshi         | 1        | 0.72%   |
| Hongkou          | 1        | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 36     | 15.63%  |
| Seagate             | 18       | 26     | 14.06%  |
| Samsung Electronics | 16       | 27     | 12.5%   |
| Intel               | 11       | 11     | 8.59%   |
| Toshiba             | 9        | 11     | 7.03%   |
| SanDisk             | 7        | 10     | 5.47%   |
| FORESEE             | 4        | 5      | 3.13%   |
| China               | 4        | 6      | 3.13%   |
| Transcend           | 3        | 4      | 2.34%   |
| Kingston            | 3        | 4      | 2.34%   |
| Hitachi             | 3        | 3      | 2.34%   |
| Hewlett-Packard     | 3        | 5      | 2.34%   |
| KIOXIA-EXCERIA      | 2        | 3      | 1.56%   |
| HGST                | 2        | 7      | 1.56%   |
| faspeed             | 2        | 3      | 1.56%   |
| tigo                | 1        | 1      | 0.78%   |
| SK hynix            | 1        | 1      | 0.78%   |
| Ramsta              | 1        | 1      | 0.78%   |
| Plextor             | 1        | 2      | 0.78%   |
| ORICO               | 1        | 1      | 0.78%   |
| NVMe                | 1        | 2      | 0.78%   |
| Netac               | 1        | 1      | 0.78%   |
| Micron Technology   | 1        | 2      | 0.78%   |
| LITEONIT            | 1        | 1      | 0.78%   |
| Lenovo              | 1        | 1      | 0.78%   |
| KingSpec            | 1        | 1      | 0.78%   |
| GLOWAY              | 1        | 2      | 0.78%   |
| FREEBSD             | 1        | 1      | 0.78%   |
| Crucial             | 1        | 2      | 0.78%   |
| Colorful            | 1        | 1      | 0.78%   |
| Centerm             | 1        | 1      | 0.78%   |
| BORY                | 1        | 2      | 0.78%   |
| BIWIN               | 1        | 3      | 0.78%   |
| Apacer              | 1        | 1      | 0.78%   |
| aigo                | 1        | 1      | 0.78%   |
| A-DATA Technology   | 1        | 2      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB | 3        | 2.04%   |
| Seagate ST1000DM003-1SB102 1TB  | 3        | 2.04%   |
| Intel SSDSA2SH032G1GN 32GB      | 2        | 1.36%   |
| HP VK000480GWCNQ 480GB          | 2        | 1.36%   |
| WDC WUH721414ALE6L4 14TB        | 1        | 0.68%   |
| WDC WDS500G2B0C-00PXH0 500GB    | 1        | 0.68%   |
| WDC WDS500G1B0C-00S6U0 500GB    | 1        | 0.68%   |
| WDC WDS100T2B0C-00PXH0 1TB      | 1        | 0.68%   |
| WDC WD7500LPCX-00KHST0 752GB    | 1        | 0.68%   |
| WDC WD6401AALS-00L3B2 640GB     | 1        | 0.68%   |
| WDC WD5000LPLX-08ZNTT0 500GB    | 1        | 0.68%   |
| WDC WD5000LPCX-24C6HT0 500GB    | 1        | 0.68%   |
| WDC WD5000LPCX-00VHAT0 500GB    | 1        | 0.68%   |
| WDC WD5000BPVT-00HXZT1 500GB    | 1        | 0.68%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 1        | 0.68%   |
| WDC WD5000AAKX-083CA0 500GB     | 1        | 0.68%   |
| WDC WD40NDZW-11BCSS1 4TB        | 1        | 0.68%   |
| WDC WD40EZAZ-00ZGHB0 4TB        | 1        | 0.68%   |
| WDC WD4005FZBX-00K5WB0 4TB      | 1        | 0.68%   |
| WDC WD3200AAJS-00L7A0 320GB     | 1        | 0.68%   |
| WDC WD30EZRZ-00WN9B0 3TB        | 1        | 0.68%   |
| WDC WD23PURZ-85C5HY0 2TB        | 1        | 0.68%   |
| WDC WD20SPZX-22UA7T0 2TB        | 1        | 0.68%   |
| WDC WD2003FYYS-007BA0 2TB       | 1        | 0.68%   |
| WDC WD1600BEVT-22ZCT0 160GB     | 1        | 0.68%   |
| WDC WD1600AAJS-22L7A0 160GB     | 1        | 0.68%   |
| WDC WD120EMAZ-11BLFA0 12TB      | 1        | 0.68%   |
| WDC WD10SPZX-00Z10T0 1TB        | 1        | 0.68%   |
| WDC WD10SPCX-00KHST0 1TB        | 1        | 0.68%   |
| WDC WD10EZEX-22MFCA0 1TB        | 1        | 0.68%   |
| WDC WD10EZEX-21WN4A0 1TB        | 1        | 0.68%   |
| WDC WD10EJRX-89N74Y0 1TB        | 1        | 0.68%   |
| WDC WD10EARS-003BB1 1TB         | 1        | 0.68%   |
| WDC PC SN520 NVMe 256GB         | 1        | 0.68%   |
| Transcend TS64GMSA230S 64GB     | 1        | 0.68%   |
| Transcend TS4GCF150 4GB         | 1        | 0.68%   |
| Transcend TS128GMTS400 128GB    | 1        | 0.68%   |
| Toshiba TR200 240GB             | 1        | 0.68%   |
| Toshiba THNSFJ256GMCT 256GB     | 1        | 0.68%   |
| Toshiba MQ04ABF100 1TB          | 1        | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 19       | 32     | 38.78%  |
| Seagate             | 18       | 26     | 36.73%  |
| Toshiba             | 5        | 5      | 10.2%   |
| Hitachi             | 3        | 3      | 6.12%   |
| HGST                | 2        | 7      | 4.08%   |
| Samsung Electronics | 1        | 1      | 2.04%   |
| Hewlett-Packard     | 1        | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 11     | 13.85%  |
| Intel               | 8        | 8      | 12.31%  |
| SanDisk             | 7        | 10     | 10.77%  |
| FORESEE             | 4        | 5      | 6.15%   |
| China               | 4        | 6      | 6.15%   |
| Transcend           | 3        | 4      | 4.62%   |
| Toshiba             | 3        | 5      | 4.62%   |
| Kingston            | 3        | 4      | 4.62%   |
| KIOXIA-EXCERIA      | 2        | 3      | 3.08%   |
| Hewlett-Packard     | 2        | 4      | 3.08%   |
| faspeed             | 2        | 3      | 3.08%   |
| tigo                | 1        | 1      | 1.54%   |
| SK hynix            | 1        | 1      | 1.54%   |
| Ramsta              | 1        | 1      | 1.54%   |
| ORICO               | 1        | 1      | 1.54%   |
| NVMe                | 1        | 1      | 1.54%   |
| Netac               | 1        | 1      | 1.54%   |
| Micron Technology   | 1        | 2      | 1.54%   |
| LITEONIT            | 1        | 1      | 1.54%   |
| Lenovo              | 1        | 1      | 1.54%   |
| KingSpec            | 1        | 1      | 1.54%   |
| FREEBSD             | 1        | 1      | 1.54%   |
| Colorful            | 1        | 1      | 1.54%   |
| Centerm             | 1        | 1      | 1.54%   |
| BORY                | 1        | 2      | 1.54%   |
| BIWIN               | 1        | 3      | 1.54%   |
| Apacer              | 1        | 1      | 1.54%   |
| aigo                | 1        | 1      | 1.54%   |
| A-DATA Technology   | 1        | 2      | 1.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 61       | 86     | 50%     |
| HDD  | 41       | 75     | 33.61%  |
| NVMe | 20       | 30     | 16.39%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 90       | 161    | 81.82%  |
| NVMe | 20       | 30     | 18.18%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 77       | 115    | 68.75%  |
| 0.51-1.0   | 19       | 23     | 16.96%  |
| 1.01-2.0   | 8        | 9      | 7.14%   |
| 3.01-4.0   | 3        | 6      | 2.68%   |
| 2.01-3.0   | 2        | 3      | 1.79%   |
| 4.01-10.0  | 2        | 3      | 1.79%   |
| 10.01-20.0 | 1        | 2      | 0.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 38       | 28.79%  |
| 1-20       | 32       | 24.24%  |
| 251-500    | 22       | 16.67%  |
| 21-50      | 14       | 10.61%  |
| 51-100     | 13       | 9.85%   |
| 501-1000   | 7        | 5.3%    |
| 1001-2000  | 5        | 3.79%   |
| Unknown    | 1        | 0.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 117      | 87.97%  |
| 21-50    | 9        | 6.77%   |
| 51-100   | 4        | 3.01%   |
| 101-250  | 1        | 0.75%   |
| 501-1000 | 1        | 0.75%   |
| Unknown  | 1        | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000BPVT-00HXZT1 500GB      | 1        | 1      | 4.76%   |
| WDC WD5000AAKX-083CA0 500GB       | 1        | 1      | 4.76%   |
| WDC WD1600AAJS-22L7A0 160GB       | 1        | 1      | 4.76%   |
| WDC WD10EJRX-89N74Y0 1TB          | 1        | 1      | 4.76%   |
| SK hynix HFS064G3AMNB-2220A 64GB  | 1        | 1      | 4.76%   |
| Seagate ST9320325AS 320GB         | 1        | 1      | 4.76%   |
| Seagate ST3320620AS 320GB         | 1        | 1      | 4.76%   |
| Seagate ST3320418AS 320GB         | 1        | 2      | 4.76%   |
| Seagate ST31500541AS 1.5TB        | 1        | 1      | 4.76%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 4.76%   |
| Samsung Electronics HM250HI 250GB | 1        | 1      | 4.76%   |
| Intel SSDSA2M120G2GC 120GB        | 1        | 1      | 4.76%   |
| Intel SSDPEKKW256G7 256GB         | 1        | 1      | 4.76%   |
| Hitachi HTS723232A7A364 320GB     | 1        | 1      | 4.76%   |
| HGST HTS725050A7E630 500GB        | 1        | 5      | 4.76%   |
| faspeed M3-360G                   | 1        | 2      | 4.76%   |
| Colorful SL500 640GB              | 1        | 1      | 4.76%   |
| China XJH-32GB                    | 1        | 1      | 4.76%   |
| Centerm SSD 8GB                   | 1        | 1      | 4.76%   |
| BORY M500 16G                     | 1        | 2      | 4.76%   |
| BIWIN SSD 32GB                    | 1        | 3      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 23.81%  |
| WDC                 | 4        | 4      | 19.05%  |
| Intel               | 2        | 2      | 9.52%   |
| SK hynix            | 1        | 1      | 4.76%   |
| Samsung Electronics | 1        | 1      | 4.76%   |
| Hitachi             | 1        | 1      | 4.76%   |
| HGST                | 1        | 5      | 4.76%   |
| faspeed             | 1        | 2      | 4.76%   |
| Colorful            | 1        | 1      | 4.76%   |
| China               | 1        | 1      | 4.76%   |
| Centerm             | 1        | 1      | 4.76%   |
| BORY                | 1        | 2      | 4.76%   |
| BIWIN               | 1        | 3      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 41.67%  |
| WDC                 | 4        | 4      | 33.33%  |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |
| HGST                | 1        | 5      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 17     | 55%     |
| SSD  | 8        | 12     | 40%     |
| NVMe | 1        | 1      | 5%      |

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
| Works    | 84       | 157    | 79.25%  |
| Malfunc  | 19       | 30     | 17.92%  |
| Detected | 3        | 4      | 2.83%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 100      | 64.94%  |
| AMD                              | 16       | 10.39%  |
| Samsung Electronics              | 8        | 5.19%   |
| SanDisk                          | 7        | 4.55%   |
| KIOXIA                           | 3        | 1.95%   |
| Silicon Motion                   | 2        | 1.3%    |
| Nvidia                           | 2        | 1.3%    |
| MAXIO Technology (Hangzhou)      | 2        | 1.3%    |
| Broadcom / LSI                   | 2        | 1.3%    |
| Toshiba                          | 1        | 0.65%   |
| Shenzhen Shichuangyi Electronics | 1        | 0.65%   |
| Shenzhen Longsys Electronics     | 1        | 0.65%   |
| Phison Electronics               | 1        | 0.65%   |
| Micron/Crucial Technology        | 1        | 0.65%   |
| Lite-On Technology               | 1        | 0.65%   |
| Kingston Technology Company      | 1        | 0.65%   |
| JMicron Technology               | 1        | 0.65%   |
| INNOGRIT                         | 1        | 0.65%   |
| Hosin Global Electronics         | 1        | 0.65%   |
| ASMedia Technology               | 1        | 0.65%   |
| Unknown                          | 1        | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 13       | 7.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10       | 5.49%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 8        | 4.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7        | 3.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7        | 3.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6        | 3.3%    |
| Intel Jasper Lake SATA AHCI Controller                                           | 6        | 3.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 6        | 3.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 5        | 2.75%   |
| Intel NVMe Optane Memory Series                                                  | 4        | 2.2%    |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 4        | 2.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4        | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4        | 2.2%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 3        | 1.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3        | 1.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3        | 1.65%   |
| Intel SATA Controller [RAID mode]                                                | 3        | 1.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3        | 1.65%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 3        | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3        | 1.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 2        | 1.1%    |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                            | 2        | 1.1%    |
| Nvidia MCP61 SATA Controller                                                     | 2        | 1.1%    |
| Nvidia MCP61 IDE                                                                 | 2        | 1.1%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 2        | 1.1%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2        | 1.1%    |
| Intel SSD 660P Series                                                            | 2        | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2        | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2        | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                            | 2        | 1.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2        | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2        | 1.1%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 2        | 1.1%    |
| Intel Alder Lake-N SATA AHCI Controller                                          | 2        | 1.1%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2        | 1.1%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2        | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2        | 1.1%    |
| AMD 400 Series Chipset SATA Controller                                           | 2        | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 99       | 62.66%  |
| NVMe | 35       | 22.15%  |
| IDE  | 18       | 11.39%  |
| RAID | 5        | 3.16%   |
| SAS  | 1        | 0.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 104      | 81.89%  |
| AMD     | 20       | 15.75%  |
| ARM     | 2        | 1.57%   |
| Unknown | 1        | 0.79%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz           | 12       | 9.38%   |
| Intel Celeron N5105 @ 2.00GHz               | 7        | 5.47%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 7        | 5.47%   |
| Intel Atom CPU D525 @ 1.80GHz               | 5        | 3.91%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 3        | 2.34%   |
| Intel Pentium CPU G3260T @ 2.90GHz          | 2        | 1.56%   |
| Intel N100                                  | 2        | 1.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.56%   |
| Intel Core i3-8100T CPU @ 3.10GHz           | 2        | 1.56%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 2        | 1.56%   |
| Intel Atom CPU C3558 @ 2.20GHz              | 2        | 1.56%   |
| ARM Cortex-A53 r0p4                         | 2        | 1.56%   |
| Intel Xeon CPU X5647 @ 2.93GHz              | 1        | 0.78%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1        | 0.78%   |
| Intel Xeon CPU E5-2676 v3 @ 2.40GHz         | 1        | 0.78%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.78%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz         | 1        | 0.78%   |
| Intel Xeon CPU E3-1265L v3 @ 2.50GHz        | 1        | 0.78%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 0.78%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.78%   |
| Intel Xeon                                  | 1        | 0.78%   |
| Intel Pentium Gold 8505                     | 1        | 0.78%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 0.78%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1        | 0.78%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 0.78%   |
| Intel Pentium CPU G3460T @ 3.00GHz          | 1        | 0.78%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 0.78%   |
| Intel Genuine CPU @ 2.40GHz                 | 1        | 0.78%   |
| Intel Genuine CPU 0000 @ 2.50GHz            | 1        | 0.78%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.78%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1        | 0.78%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 0.78%   |
| Intel Core i7-4785T CPU @ 2.20GHz           | 1        | 0.78%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.78%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.78%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 0.78%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.78%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 0.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1        | 0.78%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 38       | 29.69%  |
| Intel Core i5           | 12       | 9.38%   |
| Intel Atom              | 12       | 9.38%   |
| Intel Xeon              | 9        | 7.03%   |
| Intel Core i3           | 9        | 7.03%   |
| Intel Core i7           | 7        | 5.47%   |
| Other                   | 6        | 4.69%   |
| Intel Pentium           | 6        | 4.69%   |
| AMD Ryzen 5             | 5        | 3.91%   |
| AMD Ryzen 7             | 3        | 2.34%   |
| Intel Genuine           | 2        | 1.56%   |
| Intel Core 2 Duo        | 2        | 1.56%   |
| ARM Cortex              | 2        | 1.56%   |
| AMD Ryzen 9             | 2        | 1.56%   |
| AMD G                   | 2        | 1.56%   |
| AMD Athlon II X4        | 2        | 1.56%   |
| Intel Pentium Gold      | 1        | 0.78%   |
| Intel Pentium Dual-Core | 1        | 0.78%   |
| Intel Core 2 Quad       | 1        | 0.78%   |
| AMD Ryzen 3             | 1        | 0.78%   |
| AMD Phenom II X4        | 1        | 0.78%   |
| AMD GX                  | 1        | 0.78%   |
| AMD FX                  | 1        | 0.78%   |
| AMD Athlon X2           | 1        | 0.78%   |
| AMD A10                 | 1        | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 70       | 54.69%  |
| 2       | 33       | 25.78%  |
| 6       | 6        | 4.69%   |
| 12      | 5        | 3.91%   |
| 8       | 5        | 3.91%   |
| 16      | 3        | 2.34%   |
| 24      | 2        | 1.56%   |
| Unknown | 2        | 1.56%   |
| 28      | 1        | 0.78%   |
| 1       | 1        | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 123      | 96.85%  |
| Unknown | 3        | 2.36%   |
| 2       | 1        | 0.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 90       | 70.87%  |
| 2       | 34       | 26.77%  |
| Unknown | 3        | 2.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 18       | 14.06%  |
| Silvermont    | 15       | 11.72%  |
| KabyLake      | 12       | 9.38%   |
| Haswell       | 12       | 9.38%   |
| IvyBridge     | 9        | 7.03%   |
| Goldmont plus | 8        | 6.25%   |
| Goldmont      | 8        | 6.25%   |
| Bonnell       | 7        | 5.47%   |
| Skylake       | 5        | 3.91%   |
| CometLake     | 4        | 3.13%   |
| Zen           | 3        | 2.34%   |
| SandyBridge   | 3        | 2.34%   |
| Penryn        | 3        | 2.34%   |
| K10           | 3        | 2.34%   |
| Zen+          | 2        | 1.56%   |
| Zen 3         | 2        | 1.56%   |
| Zen 2         | 2        | 1.56%   |
| Westmere      | 2        | 1.56%   |
| Piledriver    | 2        | 1.56%   |
| Broadwell     | 2        | 1.56%   |
| Bobcat        | 2        | 1.56%   |
| TigerLake     | 1        | 0.78%   |
| K10 Llano     | 1        | 0.78%   |
| Jaguar        | 1        | 0.78%   |
| Core          | 1        | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 84       | 68.29%  |
| AMD                        | 18       | 14.63%  |
| Nvidia                     | 17       | 13.82%  |
| RDC Semiconductor          | 2        | 1.63%   |
| Matrox Electronics Systems | 1        | 0.81%   |
| ASPEED Technology          | 1        | 0.81%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13       | 10.4%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8        | 6.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7        | 5.6%    |
| Intel JasperLake [UHD Graphics]                                                          | 7        | 5.6%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6        | 4.8%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5        | 4%      |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3        | 2.4%    |
| Intel HD Graphics 610                                                                    | 3        | 2.4%    |
| Intel HD Graphics 500                                                                    | 3        | 2.4%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 2.4%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 2.4%    |
| Intel Alder Lake-N [UHD Graphics]                                                        | 3        | 2.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 2.4%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 1.6%    |
| Intel HD Graphics 620                                                                    | 2        | 1.6%    |
| Intel HD Graphics 530                                                                    | 2        | 1.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 1.6%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2        | 1.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.6%    |
| Unknown                                                                                  | 2        | 1.6%    |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 0.8%    |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.8%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 0.8%    |
| Nvidia GP106 [P106-100]                                                                  | 1        | 0.8%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.8%    |
| Nvidia GP106 [GeForce GTX 1060 5GB]                                                      | 1        | 0.8%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 0.8%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.8%    |
| Nvidia GF108 [GeForce GT 630]                                                            | 1        | 0.8%    |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1        | 0.8%    |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 0.8%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 0.8%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 0.8%    |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1        | 0.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1        | 0.8%    |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 1        | 0.8%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 0.8%    |
| Intel Iris Graphics 540                                                                  | 1        | 0.8%    |
| Intel HD Graphics 630                                                                    | 1        | 0.8%    |
| Intel HD Graphics 5500                                                                   | 1        | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| 1 x Intel             | 77       | 60.63%  |
| 1 x AMD               | 17       | 13.39%  |
| 1 x Nvidia            | 16       | 12.6%   |
| 2 x Intel             | 6        | 4.72%   |
| Other                 | 5        | 3.94%   |
| 1 x RDC Semiconductor | 2        | 1.57%   |
| 2 x AMD               | 1        | 0.79%   |
| 1 x Matrox            | 1        | 0.79%   |
| Intel + Nvidia        | 1        | 0.79%   |
| 1 x ASPEED            | 1        | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 108      | 85.04%  |
| Proprietary | 12       | 9.45%   |
| Unknown     | 7        | 5.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 112      | 88.19%  |
| 1.01-2.0   | 3        | 2.36%   |
| 7.01-8.0   | 2        | 1.57%   |
| 5.01-6.0   | 2        | 1.57%   |
| 3.01-4.0   | 2        | 1.57%   |
| 0.51-1.0   | 2        | 1.57%   |
| 0.01-0.5   | 2        | 1.57%   |
| 4.01-5.0   | 1        | 0.79%   |
| 8.01-16.0  | 1        | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 6        | 18.75%  |
| AOC                 | 4        | 12.5%   |
| Philips             | 3        | 9.38%   |
| ViewSonic           | 2        | 6.25%   |
| Mi                  | 2        | 6.25%   |
| Lenovo              | 2        | 6.25%   |
| ZL_                 | 1        | 3.13%   |
| Samsung Electronics | 1        | 3.13%   |
| SAC                 | 1        | 3.13%   |
| RTK                 | 1        | 3.13%   |
| IPS                 | 1        | 3.13%   |
| Haier               | 1        | 3.13%   |
| GRR                 | 1        | 3.13%   |
| FSD                 | 1        | 3.13%   |
| FLY                 | 1        | 3.13%   |
| Eizo                | 1        | 3.13%   |
| CAN                 | 1        | 3.13%   |
| BenQ                | 1        | 3.13%   |
| Acer                | 1        | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| ZL_ zhuoyue-HDMI ZL_2716 2560x1440 600x330mm 27.0-inch            | 1        | 3.13%   |
| ViewSonic VX2880-4K-HDU VSCA33A 3840x2160 630x360mm 28.6-inch     | 1        | 3.13%   |
| ViewSonic VA926 Series VSC7D20 1280x1024 380x300mm 19.1-inch      | 1        | 3.13%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch | 1        | 3.13%   |
| SAC LED MONITOR SAC952D 1920x1080 600x340mm 27.2-inch             | 1        | 3.13%   |
| RTK '' RTK1920 1920x1080 336x210mm 15.6-inch                      | 1        | 3.13%   |
| Philips 298P4 PHLC0BE 2560x1080 670x280mm 28.6-inch               | 1        | 3.13%   |
| Philips 242EL PHLC094 1920x1080 520x290mm 23.4-inch               | 1        | 3.13%   |
| Philips 190V PHL0081 1440x900 400x250mm 18.6-inch                 | 1        | 3.13%   |
| Mi Redmi 27 NQ XMIE001 2560x1440 600x330mm 27.0-inch              | 1        | 3.13%   |
| Mi P27QBB-RA XMID003 2560x1440 600x340mm 27.2-inch                | 1        | 3.13%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch           | 1        | 3.13%   |
| Lenovo L197 Wide LEN1152 1440x900 410x260mm 19.1-inch             | 1        | 3.13%   |
| IPS W220A IPS3150 3840x2160 700x390mm 31.5-inch                   | 1        | 3.13%   |
| Haier HT-20216B(C) HAI2031 1920x1080 480x270mm 21.7-inch          | 1        | 3.13%   |
| GRR GRC GRR2400 1920x1080 520x310mm 23.8-inch                     | 1        | 3.13%   |
| FSD F1905 FSD1850 1366x768 410x230mm 18.5-inch                    | 1        | 3.13%   |
| FLY FZ24SL FLY2400 1920x1080 530x290mm 23.8-inch                  | 1        | 3.13%   |
| Eizo CG276 ENC2400 2560x1440 600x340mm 27.2-inch                  | 1        | 3.13%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                 | 1        | 3.13%   |
| Dell S2240M DELD055 1920x1080 480x270mm 21.7-inch                 | 1        | 3.13%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                 | 1        | 3.13%   |
| Dell P2415Q DELA0C0 3840x2160 530x300mm 24.0-inch                 | 1        | 3.13%   |
| Dell E228WFP DELD015 1680x1050 470x300mm 22.0-inch                | 1        | 3.13%   |
| Dell D2421H DEL2011 1920x1080 530x300mm 24.0-inch                 | 1        | 3.13%   |
| CAN F55C CAN0055 3840x2160 1210x680mm 54.6-inch                   | 1        | 3.13%   |
| BenQ FP91G+ BNQ76A6 1280x1024 380x300mm 19.1-inch                 | 1        | 3.13%   |
| AOC Q27P1B AOC2701 2560x1440 600x340mm 27.2-inch                  | 1        | 3.13%   |
| AOC 2778X AOC2778 2560x1440 600x340mm 27.2-inch                   | 1        | 3.13%   |
| AOC 2490W1 AOC2490 1920x1080 530x300mm 24.0-inch                  | 1        | 3.13%   |
| AOC 2479W AOC2479 1920x1080 520x290mm 23.4-inch                   | 1        | 3.13%   |
| Acer G195WV ACR0263 1440x900 410x260mm 19.1-inch                  | 1        | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 14       | 43.75%  |
| 2560x1440 (QHD)    | 6        | 18.75%  |
| 3840x2160 (4K)     | 4        | 12.5%   |
| 1440x900 (WXGA+)   | 3        | 9.38%   |
| 1280x1024 (SXGA)   | 2        | 6.25%   |
| 2560x1080          | 1        | 3.13%   |
| 1680x1050 (WSXGA+) | 1        | 3.13%   |
| 1366x768 (WXGA)    | 1        | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 7        | 21.88%  |
| 24     | 5        | 15.63%  |
| 23     | 5        | 15.63%  |
| 19     | 4        | 12.5%   |
| 21     | 3        | 9.38%   |
| 28     | 2        | 6.25%   |
| 18     | 2        | 6.25%   |
| 54     | 1        | 3.13%   |
| 31     | 1        | 3.13%   |
| 22     | 1        | 3.13%   |
| 15     | 1        | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 53.13%  |
| 401-500     | 7        | 21.88%  |
| 601-700     | 3        | 9.38%   |
| 351-400     | 3        | 9.38%   |
| 301-350     | 1        | 3.13%   |
| 1001-1500   | 1        | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 24       | 75%     |
| 16/10 | 5        | 15.63%  |
| 5/4   | 2        | 6.25%   |
| 21/9  | 1        | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 14       | 43.75%  |
| 301-350        | 7        | 21.88%  |
| 151-200        | 5        | 15.63%  |
| 351-500        | 2        | 6.25%   |
| More than 1000 | 1        | 3.13%   |
| 251-300        | 1        | 3.13%   |
| 141-150        | 1        | 3.13%   |
| 101-110        | 1        | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 20       | 62.5%   |
| 101-120 | 8        | 25%     |
| 121-160 | 3        | 9.38%   |
| 161-240 | 1        | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 94       | 73.44%  |
| 1     | 34       | 26.56%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 87       | 54.04%  |
| Realtek Semiconductor    | 61       | 37.89%  |
| Qualcomm Atheros         | 4        | 2.48%   |
| Broadcom                 | 3        | 1.86%   |
| Mellanox Technologies    | 2        | 1.24%   |
| Ralink Technology        | 1        | 0.62%   |
| OPPO Electronics         | 1        | 0.62%   |
| Marvell Technology Group | 1        | 0.62%   |
| Apple                    | 1        | 0.62%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 48       | 25.95%  |
| Intel I211 Gigabit Network Connection                                  | 17       | 9.19%   |
| Intel Ethernet Controller I225-V                                       | 12       | 6.49%   |
| Intel Ethernet Controller I226-V                                       | 10       | 5.41%   |
| Intel 82583V Gigabit Network Connection                                | 7        | 3.78%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5        | 2.7%    |
| Intel I350 Gigabit Network Connection                                  | 4        | 2.16%   |
| Intel Ethernet Connection X553 1GbE                                    | 4        | 2.16%   |
| Intel Ethernet Connection I217-LM                                      | 4        | 2.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4        | 2.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 1.62%   |
| Intel Wireless 7260                                                    | 3        | 1.62%   |
| Intel I210 Gigabit Network Connection                                  | 3        | 1.62%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 3        | 1.62%   |
| Intel 82576 Gigabit Network Connection                                 | 3        | 1.62%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 1.62%   |
| Mellanox MT27500 Family [ConnectX-3]                                   | 2        | 1.08%   |
| Intel Wireless 3165                                                    | 2        | 1.08%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 1.08%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2        | 1.08%   |
| Intel Ethernet Connection X553 10 GbE SFP+                             | 2        | 1.08%   |
| Intel Ethernet Connection I217-V                                       | 2        | 1.08%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 1.08%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 1.08%   |
| Intel 82575EB Gigabit Network Connection                               | 2        | 1.08%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1        | 0.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.54%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 0.54%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                 | 1        | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 0.54%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1        | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1        | 0.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.54%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 0.54%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                           | 1        | 0.54%   |
| Ralink RT5370 Wireless Adapter                                         | 1        | 0.54%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter        | 1        | 0.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 0.54%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 13       | 48.15%  |
| Realtek Semiconductor | 8        | 29.63%  |
| Qualcomm Atheros      | 4        | 14.81%  |
| Ralink Technology     | 1        | 3.7%    |
| Broadcom              | 1        | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wireless 7260                                             | 3        | 11.11%  |
| Intel Wireless 3165                                             | 2        | 7.41%   |
| Intel Wi-Fi 6 AX200                                             | 2        | 7.41%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 2        | 7.41%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller     | 1        | 3.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 1        | 3.7%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter         | 1        | 3.7%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1        | 3.7%    |
| Realtek RTL8188EE Wireless Network Adapter                      | 1        | 3.7%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 1        | 3.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 1        | 3.7%    |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                    | 1        | 3.7%    |
| Ralink RT5370 Wireless Adapter                                  | 1        | 3.7%    |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1        | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1        | 3.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1        | 3.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 1        | 3.7%    |
| Intel Wireless 3160                                             | 1        | 3.7%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 1        | 3.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 1        | 3.7%    |
| Intel CNVi: Wi-Fi                                               | 1        | 3.7%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 1        | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 78       | 56.12%  |
| Realtek Semiconductor    | 56       | 40.29%  |
| Broadcom                 | 2        | 1.44%   |
| OPPO Electronics         | 1        | 0.72%   |
| Marvell Technology Group | 1        | 0.72%   |
| Apple                    | 1        | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 48       | 30.77%  |
| Intel I211 Gigabit Network Connection                                  | 17       | 10.9%   |
| Intel Ethernet Controller I225-V                                       | 12       | 7.69%   |
| Intel Ethernet Controller I226-V                                       | 10       | 6.41%   |
| Intel 82583V Gigabit Network Connection                                | 7        | 4.49%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5        | 3.21%   |
| Intel I350 Gigabit Network Connection                                  | 4        | 2.56%   |
| Intel Ethernet Connection X553 1GbE                                    | 4        | 2.56%   |
| Intel Ethernet Connection I217-LM                                      | 4        | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4        | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 1.92%   |
| Intel I210 Gigabit Network Connection                                  | 3        | 1.92%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 3        | 1.92%   |
| Intel 82576 Gigabit Network Connection                                 | 3        | 1.92%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 1.92%   |
| Intel Ethernet Connection X553 10 GbE SFP+                             | 2        | 1.28%   |
| Intel Ethernet Connection I217-V                                       | 2        | 1.28%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 1.28%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 1.28%   |
| Intel 82575EB Gigabit Network Connection                               | 2        | 1.28%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.64%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 0.64%   |
| OPPO KALAMA-MTP_CID:0437_SN:B2767D06 RNDIS Control RNDIS Ethernet Data | 1        | 0.64%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.64%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 0.64%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 0.64%   |
| Intel Ethernet Connection (17) I219-LM                                 | 1        | 0.64%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 0.64%   |
| Intel 82580 Gigabit Network Connection                                 | 1        | 0.64%   |
| Intel 82575GB Gigabit Network Connection                               | 1        | 0.64%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                     | 1        | 0.64%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 0.64%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 0.64%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                       | 1        | 0.64%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                        | 1        | 0.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 125      | 82.24%  |
| WiFi     | 25       | 16.45%  |
| Unknown  | 2        | 1.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 119      | 94.44%  |
| WiFi     | 7        | 5.56%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 45       | 35.43%  |
| 1     | 27       | 21.26%  |
| 4     | 20       | 15.75%  |
| 6     | 14       | 11.02%  |
| 5     | 10       | 7.87%   |
| 3     | 4        | 3.15%   |
| 7     | 2        | 1.57%   |
| 0     | 2        | 1.57%   |
| 10    | 1        | 0.79%   |
| 9     | 1        | 0.79%   |
| 8     | 1        | 0.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 102      | 76.12%  |
| Yes  | 32       | 23.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 57.89%  |
| Realtek Semiconductor           | 3        | 15.79%  |
| Qualcomm Atheros Communications | 2        | 10.53%  |
| Cambridge Silicon Radio         | 2        | 10.53%  |
| Apple                           | 1        | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 4        | 21.05%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2        | 10.53%  |
| Intel AX200 Bluetooth                                       | 2        | 10.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2        | 10.53%  |
| Realtek  Bluetooth 4.2 Adapter                              | 1        | 5.26%   |
| Realtek Bluetooth Adapter                                   | 1        | 5.26%   |
| Realtek Bluetooth 4.0 Adapter                               | 1        | 5.26%   |
| Qualcomm Atheros Dell Wireless 1901 Bluetooth               | 1        | 5.26%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 5.26%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 5.26%   |
| Intel AX210 Bluetooth                                       | 1        | 5.26%   |
| Intel AX201 Bluetooth                                       | 1        | 5.26%   |
| Apple Bluetooth Host Controller                             | 1        | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 82       | 67.21%  |
| AMD                    | 21       | 17.21%  |
| Nvidia                 | 16       | 13.11%  |
| C-Media Electronics    | 2        | 1.64%   |
| Generalplus Technology | 1        | 0.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8        | 5.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8        | 5.8%    |
| Intel Jasper Lake HD Audio                                                                        | 7        | 5.07%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7        | 5.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7        | 5.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7        | 5.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6        | 4.35%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 6        | 4.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4        | 2.9%    |
| Nvidia GM206 High Definition Audio Controller                                                     | 3        | 2.17%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 2.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3        | 2.17%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3        | 2.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 2.17%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 2.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3        | 2.17%   |
| AMD FCH Azalia Controller                                                                         | 3        | 2.17%   |
| Nvidia MCP61 High Definition Audio                                                                | 2        | 1.45%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2        | 1.45%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 1.45%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2        | 1.45%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2        | 1.45%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 2        | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 1.45%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 2        | 1.45%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 2        | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2        | 1.45%   |
| Intel 200 Series PCH HD Audio                                                                     | 2        | 1.45%   |
| AMD Wrestler HDMI Audio                                                                           | 2        | 1.45%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2        | 1.45%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2        | 1.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 1.45%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 0.72%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 0.72%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 0.72%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 0.72%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1        | 0.72%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1        | 0.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 26       | 18.98%  |
| Kingston            | 23       | 16.79%  |
| Unknown             | 16       | 11.68%  |
| SK hynix            | 16       | 11.68%  |
| Micron Technology   | 13       | 9.49%   |
| A-DATA Technology   | 9        | 6.57%   |
| Unknown             | 7        | 5.11%   |
| Crucial             | 4        | 2.92%   |
| Corsair             | 4        | 2.92%   |
| GeIL                | 3        | 2.19%   |
| G.Skill             | 3        | 2.19%   |
| Toshiba             | 2        | 1.46%   |
| Ramaxel Technology  | 2        | 1.46%   |
| Nanya Technology    | 2        | 1.46%   |
| tigo                | 1        | 0.73%   |
| Team                | 1        | 0.73%   |
| Ramsta              | 1        | 0.73%   |
| KINGBANK            | 1        | 0.73%   |
| Juhor               | 1        | 0.73%   |
| Elpida              | 1        | 0.73%   |
| Apacer              | 1        | 0.73%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown                                                    | 7        | 4.79%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 3        | 2.05%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                 | 2        | 1.37%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                   | 2        | 1.37%   |
| Toshiba RAM HP24D4R7D4HAI-32 32GB DIMM DDR4 2400MT/s       | 2        | 1.37%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 2        | 1.37%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s        | 2        | 1.37%   |
| Kingston RAM KHX3200C16FB/8G 8GB SODIMM DDR4 2400MT/s      | 2        | 1.37%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 2933MT/s       | 2        | 1.37%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s        | 2        | 1.37%   |
| GeIL RAM CL11-11-11 D3-1600 8GB DIMM DDR3 1600MT/s         | 2        | 1.37%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s    | 2        | 1.37%   |
| Unknown RAM XinJuHuo 8GB SODIMM DDR3 1600MT/s              | 1        | 0.68%   |
| Unknown RAM TMKS8G68ALFBCH-266 8192MB SODIMM DDR4 2400MT/s | 1        | 0.68%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                  | 1        | 0.68%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1        | 0.68%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s                 | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                  | 1        | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                 | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM 800MT/s                        | 1        | 0.68%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 1        | 0.68%   |
| Unknown RAM Module 1GB DIMM SDRAM                          | 1        | 0.68%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                   | 1        | 0.68%   |
| Unknown RAM IM38GS48A16-BBBHB0 8GB DIMM DDR3 1600MT/s      | 1        | 0.68%   |
| tigo RAM 1600Mhz-4G 4GB DIMM DDR3 1600MT/s                 | 1        | 0.68%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s         | 1        | 0.68%   |
| SK hynix RAM Module 8GB DIMM DDR4 2400MT/s                 | 1        | 0.68%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB DIMM DDR3 1600MT/s       | 1        | 0.68%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM 1066MT/s            | 1        | 0.68%   |
| SK hynix RAM HMT325S6EFR8C-PB 2GB DIMM DDR3 1600MT/s       | 1        | 0.68%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB DIMM DDR3 1333MT/s       | 1        | 0.68%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s       | 1        | 0.68%   |
| SK hynix RAM HMCG66AGBSA092N 8GB SODIMM DDR5 5600MT/s      | 1        | 0.68%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s    | 1        | 0.68%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s     | 1        | 0.68%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s       | 1        | 0.68%   |
| SK hynix RAM HMA81GS7DJR8N-VK 8192MB SODIMM DDR4 2667MT/s  | 1        | 0.68%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1        | 0.68%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s     | 1        | 0.68%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s       | 1        | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 56       | 46.28%  |
| DDR3    | 52       | 42.98%  |
| DDR5    | 4        | 3.31%   |
| DDR2    | 4        | 3.31%   |
| Unknown | 3        | 2.48%   |
| SDRAM   | 1        | 0.83%   |
| LPDDR4  | 1        | 0.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 70       | 57.38%  |
| SODIMM       | 48       | 39.34%  |
| Unknown      | 2        | 1.64%   |
| Row Of Chips | 1        | 0.82%   |
| RIMM         | 1        | 0.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 44       | 33.85%  |
| 4096  | 41       | 31.54%  |
| 16384 | 22       | 16.92%  |
| 2048  | 16       | 12.31%  |
| 32768 | 5        | 3.85%   |
| 1024  | 2        | 1.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 30       | 22.9%   |
| 2400    | 19       | 14.5%   |
| 2133    | 15       | 11.45%  |
| 3200    | 14       | 10.69%  |
| 1333    | 14       | 10.69%  |
| 2667    | 11       | 8.4%    |
| 800     | 9        | 6.87%   |
| 4800    | 3        | 2.29%   |
| 2666    | 3        | 2.29%   |
| 1867    | 3        | 2.29%   |
| 1334    | 3        | 2.29%   |
| 2933    | 2        | 1.53%   |
| 667     | 2        | 1.53%   |
| 5600    | 1        | 0.76%   |
| 1066    | 1        | 0.76%   |
| Unknown | 1        | 0.76%   |

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
| 1     | 62       | 48.82%  |
| 0     | 49       | 38.58%  |
| 2     | 15       | 11.81%  |
| 4     | 1        | 0.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 72       | 79.12%  |
| Net/wireless             | 9        | 9.89%   |
| Sound                    | 3        | 3.3%    |
| Bluetooth                | 3        | 3.3%    |
| Net/ethernet             | 2        | 2.2%    |
| Card reader              | 2        | 2.2%    |

