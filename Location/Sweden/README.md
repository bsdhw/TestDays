BSD in Sweden - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in Sweden.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Sweden/Desktop/README.md) and [notebooks](/Location/Sweden/Notebook/README.md).

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

Total: 275

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | 8103 A01                    | Mini pc     | [d066ee0847](https://bsd-hardware.info/?probe=d066ee0847) | Jan 02, 2024 |
| Fujitsu       | D3034-A1 S26361-D3034-A1... | Server      | [806449eded](https://bsd-hardware.info/?probe=806449eded) | Jan 01, 2024 |
| PC Engines    | APU2                        | Desktop     | [c0fcb231db](https://bsd-hardware.info/?probe=c0fcb231db) | Dec 30, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [412c714b49](https://bsd-hardware.info/?probe=412c714b49) | Dec 27, 2023 |
| PC Engines    | APU3                        | Desktop     | [6c92d4965a](https://bsd-hardware.info/?probe=6c92d4965a) | Dec 16, 2023 |
| Lenovo        | ThinkServer RS140           | Desktop     | [a380879f2f](https://bsd-hardware.info/?probe=a380879f2f) | Dec 11, 2023 |
| Unknown       | YL-J3160L4                  | Desktop     | [cf07751804](https://bsd-hardware.info/?probe=cf07751804) | Dec 09, 2023 |
| PC Engines    | APU2                        | Desktop     | [dbd4df3e5e](https://bsd-hardware.info/?probe=dbd4df3e5e) | Dec 03, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [ec3037a710](https://bsd-hardware.info/?probe=ec3037a710) | Nov 30, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [eec65ee6ce](https://bsd-hardware.info/?probe=eec65ee6ce) | Nov 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [8b2a1299bf](https://bsd-hardware.info/?probe=8b2a1299bf) | Nov 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [b8b5586ead](https://bsd-hardware.info/?probe=b8b5586ead) | Nov 24, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [7d58ae8d97](https://bsd-hardware.info/?probe=7d58ae8d97) | Nov 14, 2023 |
| HP            | 8054                        | Desktop     | [dd3ce5a68d](https://bsd-hardware.info/?probe=dd3ce5a68d) | Nov 12, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [8bb2f091fd](https://bsd-hardware.info/?probe=8bb2f091fd) | Nov 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [c44b69b11e](https://bsd-hardware.info/?probe=c44b69b11e) | Nov 07, 2023 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [59372d06e0](https://bsd-hardware.info/?probe=59372d06e0) | Nov 02, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [8004cade7b](https://bsd-hardware.info/?probe=8004cade7b) | Nov 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [119cb746c8](https://bsd-hardware.info/?probe=119cb746c8) | Oct 25, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [b09bb5811b](https://bsd-hardware.info/?probe=b09bb5811b) | Oct 19, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [e96fbf80a4](https://bsd-hardware.info/?probe=e96fbf80a4) | Oct 19, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [3cf75f0ae6](https://bsd-hardware.info/?probe=3cf75f0ae6) | Oct 19, 2023 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [99260d8bdf](https://bsd-hardware.info/?probe=99260d8bdf) | Oct 07, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [85e94bd511](https://bsd-hardware.info/?probe=85e94bd511) | Oct 06, 2023 |
| Intel         | D54250WYK H13922-303        | Desktop     | [1bca98240a](https://bsd-hardware.info/?probe=1bca98240a) | Oct 04, 2023 |
| ASUSTek       | Pro WS W680-ACE IPMI        | Desktop     | [6a98aea3f9](https://bsd-hardware.info/?probe=6a98aea3f9) | Oct 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [906fd7e198](https://bsd-hardware.info/?probe=906fd7e198) | Sep 30, 2023 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [ea832a672d](https://bsd-hardware.info/?probe=ea832a672d) | Sep 30, 2023 |
| HP            | 8299                        | Desktop     | [fee80cc3e3](https://bsd-hardware.info/?probe=fee80cc3e3) | Sep 23, 2023 |
| PC Engines    | apu6                        | Desktop     | [1a45dd59a4](https://bsd-hardware.info/?probe=1a45dd59a4) | Sep 21, 2023 |
| HP            | 8299                        | Desktop     | [2f1bdffe66](https://bsd-hardware.info/?probe=2f1bdffe66) | Sep 20, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [6bb6186f22](https://bsd-hardware.info/?probe=6bb6186f22) | Sep 19, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [cdeddbf4be](https://bsd-hardware.info/?probe=cdeddbf4be) | Sep 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [b95f409ccf](https://bsd-hardware.info/?probe=b95f409ccf) | Sep 05, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [44afefb7c1](https://bsd-hardware.info/?probe=44afefb7c1) | Aug 28, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | Desktop     | [9e92903663](https://bsd-hardware.info/?probe=9e92903663) | Aug 18, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [0836b029bc](https://bsd-hardware.info/?probe=0836b029bc) | Aug 17, 2023 |
| PC Engines    | APU2                        | Desktop     | [d8f32b19ff](https://bsd-hardware.info/?probe=d8f32b19ff) | Aug 14, 2023 |
| HP            | ProLiant DL380 G7           | Server      | [5b327a0a32](https://bsd-hardware.info/?probe=5b327a0a32) | Aug 10, 2023 |
| HP            | ProLiant DL380 G7           | Server      | [5ae4888d17](https://bsd-hardware.info/?probe=5ae4888d17) | Aug 04, 2023 |
| HP            | 8299                        | Desktop     | [74c24bcb16](https://bsd-hardware.info/?probe=74c24bcb16) | Jul 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [ce0f05e871](https://bsd-hardware.info/?probe=ce0f05e871) | Jul 18, 2023 |
| MSI           | B350I PRO AC                | Desktop     | [3c4d3b94d0](https://bsd-hardware.info/?probe=3c4d3b94d0) | Jul 14, 2023 |
| MSI           | B350I PRO AC                | Desktop     | [ab56e76e70](https://bsd-hardware.info/?probe=ab56e76e70) | Jul 14, 2023 |
| PC Engines    | APU2                        | Desktop     | [80d79341a8](https://bsd-hardware.info/?probe=80d79341a8) | Jul 05, 2023 |
| Supermicro    | X10DRW-EA                   | Server      | [72a198dc53](https://bsd-hardware.info/?probe=72a198dc53) | Jul 04, 2023 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [0cf9bf6a63](https://bsd-hardware.info/?probe=0cf9bf6a63) | Jul 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [5080e84698](https://bsd-hardware.info/?probe=5080e84698) | Jun 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [c660f668dc](https://bsd-hardware.info/?probe=c660f668dc) | Jun 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [b67ce69ea4](https://bsd-hardware.info/?probe=b67ce69ea4) | Jun 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [6e8085380f](https://bsd-hardware.info/?probe=6e8085380f) | Jun 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [eb49ebcc0c](https://bsd-hardware.info/?probe=eb49ebcc0c) | Jun 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [193c7d152b](https://bsd-hardware.info/?probe=193c7d152b) | Jun 11, 2023 |
| PC Engines    | APU2                        | Desktop     | [f644f33061](https://bsd-hardware.info/?probe=f644f33061) | Jun 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [e80a97aec3](https://bsd-hardware.info/?probe=e80a97aec3) | May 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a0bff43f5c](https://bsd-hardware.info/?probe=a0bff43f5c) | May 23, 2023 |
| Lenovo        | ThinkCentre M81 1730A1G     | Desktop     | [8f59660eca](https://bsd-hardware.info/?probe=8f59660eca) | May 17, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [a75ff519b0](https://bsd-hardware.info/?probe=a75ff519b0) | May 15, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [4806dc7d9a](https://bsd-hardware.info/?probe=4806dc7d9a) | Apr 29, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [692df89c1f](https://bsd-hardware.info/?probe=692df89c1f) | Apr 26, 2023 |
| AZW           | GK55                        | Desktop     | [31a99b9d2a](https://bsd-hardware.info/?probe=31a99b9d2a) | Apr 25, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [a4bc168937](https://bsd-hardware.info/?probe=a4bc168937) | Apr 22, 2023 |
| AZW           | GK55                        | Desktop     | [cc5a32800f](https://bsd-hardware.info/?probe=cc5a32800f) | Apr 14, 2023 |
| HP            | 1998                        | Desktop     | [bc67c37f5f](https://bsd-hardware.info/?probe=bc67c37f5f) | Apr 04, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [ebbd75883c](https://bsd-hardware.info/?probe=ebbd75883c) | Mar 17, 2023 |
| DFI           | CM100-C                     | Desktop     | [c34832095b](https://bsd-hardware.info/?probe=c34832095b) | Mar 15, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [23f9004191](https://bsd-hardware.info/?probe=23f9004191) | Mar 13, 2023 |
| AMI           | MNHO-048                    | Desktop     | [ebd90b78c1](https://bsd-hardware.info/?probe=ebd90b78c1) | Mar 12, 2023 |
| AMI           | MNHO-048                    | Desktop     | [52cdeb023e](https://bsd-hardware.info/?probe=52cdeb023e) | Mar 12, 2023 |
| PC Engines    | APU3                        | Desktop     | [c8008161b0](https://bsd-hardware.info/?probe=c8008161b0) | Mar 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [e4b77410c6](https://bsd-hardware.info/?probe=e4b77410c6) | Mar 08, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [31ed952f9c](https://bsd-hardware.info/?probe=31ed952f9c) | Mar 06, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [732a635016](https://bsd-hardware.info/?probe=732a635016) | Mar 06, 2023 |
| Supermicro    | X11SSH-LN4F                 | Server      | [7ab6080dfe](https://bsd-hardware.info/?probe=7ab6080dfe) | Feb 24, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [d04d402809](https://bsd-hardware.info/?probe=d04d402809) | Feb 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [44ac3b2832](https://bsd-hardware.info/?probe=44ac3b2832) | Feb 13, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [96fa5325d1](https://bsd-hardware.info/?probe=96fa5325d1) | Feb 11, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d49da87ce9](https://bsd-hardware.info/?probe=d49da87ce9) | Feb 07, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [a98d28355d](https://bsd-hardware.info/?probe=a98d28355d) | Feb 05, 2023 |
| Star Labs     | StarBook                    | Notebook    | [d222f381b0](https://bsd-hardware.info/?probe=d222f381b0) | Jan 23, 2023 |
| Star Labs     | StarBook                    | Notebook    | [045d4bb6e8](https://bsd-hardware.info/?probe=045d4bb6e8) | Jan 23, 2023 |
| ASUSTek       | EB1035                      | All in one  | [7e39e23232](https://bsd-hardware.info/?probe=7e39e23232) | Jan 21, 2023 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [c2100f1789](https://bsd-hardware.info/?probe=c2100f1789) | Jan 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3d2101dc79](https://bsd-hardware.info/?probe=3d2101dc79) | Jan 14, 2023 |
| HP            | 82A1                        | Desktop     | [2d7d9105f7](https://bsd-hardware.info/?probe=2d7d9105f7) | Jan 13, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [b53cd12326](https://bsd-hardware.info/?probe=b53cd12326) | Jan 12, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [8353660219](https://bsd-hardware.info/?probe=8353660219) | Jan 08, 2023 |
| ASRock        | E3C226D2I                   | Desktop     | [5dfcf8051d](https://bsd-hardware.info/?probe=5dfcf8051d) | Jan 06, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [21c60a4db8](https://bsd-hardware.info/?probe=21c60a4db8) | Jan 04, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [7a86ed2309](https://bsd-hardware.info/?probe=7a86ed2309) | Jan 01, 2023 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | Notebook    | [22c4a06468](https://bsd-hardware.info/?probe=22c4a06468) | Dec 31, 2022 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | Desktop     | [ac867149f2](https://bsd-hardware.info/?probe=ac867149f2) | Dec 31, 2022 |
| CompuLab      | SBC-fit-PC4                 | Mini pc     | [c781bd46dc](https://bsd-hardware.info/?probe=c781bd46dc) | Dec 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [b4d44b0018](https://bsd-hardware.info/?probe=b4d44b0018) | Dec 26, 2022 |
| ACMA          | X8SIE                       | Desktop     | [01898b2ffb](https://bsd-hardware.info/?probe=01898b2ffb) | Dec 21, 2022 |
| PC Engines    | APU3                        | Desktop     | [5597cca988](https://bsd-hardware.info/?probe=5597cca988) | Dec 17, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [7d80c62813](https://bsd-hardware.info/?probe=7d80c62813) | Dec 09, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [b2720b8b88](https://bsd-hardware.info/?probe=b2720b8b88) | Dec 08, 2022 |
| ACMA          | X8SIE                       | Desktop     | [361e4ccc04](https://bsd-hardware.info/?probe=361e4ccc04) | Dec 05, 2022 |
| ACMA          | X8SIE                       | Desktop     | [532b81e55f](https://bsd-hardware.info/?probe=532b81e55f) | Nov 29, 2022 |
| ACMA          | X8SIE                       | Desktop     | [d0112d027b](https://bsd-hardware.info/?probe=d0112d027b) | Nov 28, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [e850e0ae9c](https://bsd-hardware.info/?probe=e850e0ae9c) | Nov 28, 2022 |
| Toshiba       | TECRA Z40-C-12Z             | Notebook    | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [bd1f1fa769](https://bsd-hardware.info/?probe=bd1f1fa769) | Nov 26, 2022 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [2959091a59](https://bsd-hardware.info/?probe=2959091a59) | Nov 25, 2022 |
| Lenovo        | ThinkServer RS140           | Desktop     | [0dd05e08aa](https://bsd-hardware.info/?probe=0dd05e08aa) | Nov 12, 2022 |
| Lenovo        | ThinkServer RS140           | Desktop     | [b2b1509adf](https://bsd-hardware.info/?probe=b2b1509adf) | Nov 11, 2022 |
| MSI           | Z370I GAMING PRO CARBON ... | Desktop     | [dd9f7679b5](https://bsd-hardware.info/?probe=dd9f7679b5) | Nov 09, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [970443066b](https://bsd-hardware.info/?probe=970443066b) | Nov 07, 2022 |
| Cisco         | ASA5515 A0                  | Desktop     | [7f848d7c57](https://bsd-hardware.info/?probe=7f848d7c57) | Oct 22, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [d7c3749eba](https://bsd-hardware.info/?probe=d7c3749eba) | Oct 13, 2022 |
| HP            | 8103 A01                    | Mini pc     | [f187229469](https://bsd-hardware.info/?probe=f187229469) | Oct 09, 2022 |
| Dell          | 05KX61 A04                  | Server      | [f1232f79c4](https://bsd-hardware.info/?probe=f1232f79c4) | Sep 25, 2022 |
| HP            | Unknown                     | Notebook    | [7bd69ee984](https://bsd-hardware.info/?probe=7bd69ee984) | Aug 29, 2022 |
| AOpen         | iBTMx-DS R1.04 55DED10A0... | Desktop     | [a480263c28](https://bsd-hardware.info/?probe=a480263c28) | Aug 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [e5efeb3781](https://bsd-hardware.info/?probe=e5efeb3781) | Aug 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [9d1eb045e5](https://bsd-hardware.info/?probe=9d1eb045e5) | Aug 20, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [efd9ee1d33](https://bsd-hardware.info/?probe=efd9ee1d33) | Aug 10, 2022 |
| ASUSTek       | CM6731_CM6431_CM6331        | Desktop     | [6e40b41bc3](https://bsd-hardware.info/?probe=6e40b41bc3) | Aug 04, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [59ae6fc283](https://bsd-hardware.info/?probe=59ae6fc283) | Jul 26, 2022 |
| HP            | ProBook 4730s               | Notebook    | [e70725dd32](https://bsd-hardware.info/?probe=e70725dd32) | Jul 23, 2022 |
| Supermicro    | X11SSV-M4                   | Desktop     | [444d9ed75e](https://bsd-hardware.info/?probe=444d9ed75e) | Jul 04, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ea22a644f6](https://bsd-hardware.info/?probe=ea22a644f6) | Jul 04, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [dfd321896a](https://bsd-hardware.info/?probe=dfd321896a) | Jun 14, 2022 |
| PC Engines    | APU                         | Desktop     | [f41e59d78b](https://bsd-hardware.info/?probe=f41e59d78b) | Jun 11, 2022 |
| Supermicro    | X11SSH-LN4F                 | Server      | [d3ba57cf29](https://bsd-hardware.info/?probe=d3ba57cf29) | Jun 01, 2022 |
| MSI           | MS-7369                     | Desktop     | [c2c6bd80e8](https://bsd-hardware.info/?probe=c2c6bd80e8) | May 13, 2022 |
| Dell          | 05Y15N A06                  | Server      | [047ecc3a64](https://bsd-hardware.info/?probe=047ecc3a64) | May 13, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [0d11258d3a](https://bsd-hardware.info/?probe=0d11258d3a) | Apr 22, 2022 |
| HP            | 8103 A01                    | Mini pc     | [b3d4d3c2db](https://bsd-hardware.info/?probe=b3d4d3c2db) | Apr 16, 2022 |
| Shuttle       | SH570                       | Desktop     | [08e2af8890](https://bsd-hardware.info/?probe=08e2af8890) | Apr 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [2e4a7843ab](https://bsd-hardware.info/?probe=2e4a7843ab) | Apr 14, 2022 |
| ASUSTek       | UX305UA                     | Notebook    | [3fb1786193](https://bsd-hardware.info/?probe=3fb1786193) | Apr 04, 2022 |
| Dell          | 0GFKVD A00                  | Server      | [2b14dd2a23](https://bsd-hardware.info/?probe=2b14dd2a23) | Mar 29, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [04e77555a2](https://bsd-hardware.info/?probe=04e77555a2) | Mar 24, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [23055a27d9](https://bsd-hardware.info/?probe=23055a27d9) | Mar 23, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | Notebook    | [dbb0e378d5](https://bsd-hardware.info/?probe=dbb0e378d5) | Mar 17, 2022 |
| AOpen         | iBTMx-DS R1.04 55DED10A0... | Desktop     | [8faec8e7ed](https://bsd-hardware.info/?probe=8faec8e7ed) | Mar 10, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [a2c59d02ee](https://bsd-hardware.info/?probe=a2c59d02ee) | Mar 08, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [099edf57ae](https://bsd-hardware.info/?probe=099edf57ae) | Mar 08, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [1daab68f1f](https://bsd-hardware.info/?probe=1daab68f1f) | Mar 04, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [8016115ff1](https://bsd-hardware.info/?probe=8016115ff1) | Feb 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [5d39002367](https://bsd-hardware.info/?probe=5d39002367) | Feb 21, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [807a29112e](https://bsd-hardware.info/?probe=807a29112e) | Feb 19, 2022 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [5f27a360e4](https://bsd-hardware.info/?probe=5f27a360e4) | Feb 10, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [37cc045649](https://bsd-hardware.info/?probe=37cc045649) | Jan 28, 2022 |
| MSI           | MS-7C56                     | Desktop     | [962ac1c7b0](https://bsd-hardware.info/?probe=962ac1c7b0) | Jan 20, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [082da3ef7f](https://bsd-hardware.info/?probe=082da3ef7f) | Jan 19, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [26ccd8e3c5](https://bsd-hardware.info/?probe=26ccd8e3c5) | Jan 16, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [e0e7b21668](https://bsd-hardware.info/?probe=e0e7b21668) | Jan 09, 2022 |
| ASUSTek       | P8H77-I                     | Desktop     | [e15d67e8db](https://bsd-hardware.info/?probe=e15d67e8db) | Jan 08, 2022 |
| ASRock        | E3C226D2I                   | Desktop     | [a31265ae13](https://bsd-hardware.info/?probe=a31265ae13) | Jan 07, 2022 |
| ASUSTek       | P8H77-I                     | Desktop     | [27960088a3](https://bsd-hardware.info/?probe=27960088a3) | Jan 05, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [1684618e22](https://bsd-hardware.info/?probe=1684618e22) | Jan 01, 2022 |
| HP            | ProLiant DL360 G5           | Server      | [8eaea61913](https://bsd-hardware.info/?probe=8eaea61913) | Dec 29, 2021 |
| Lenovo        | ThinkServer RS140           | Desktop     | [e28b542e9e](https://bsd-hardware.info/?probe=e28b542e9e) | Dec 23, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [fda420b944](https://bsd-hardware.info/?probe=fda420b944) | Dec 20, 2021 |
| HPE           | ProLiant DL380 Gen10        | Server      | [d1e6144816](https://bsd-hardware.info/?probe=d1e6144816) | Dec 20, 2021 |
| Intel         | DH61AG AAG81491-600         | Desktop     | [fd9659a9fe](https://bsd-hardware.info/?probe=fd9659a9fe) | Dec 15, 2021 |
| ASUSTek       | Rampage Formula             | Desktop     | [34633c2ca8](https://bsd-hardware.info/?probe=34633c2ca8) | Dec 02, 2021 |
| MSI           | MS-7C56                     | Desktop     | [d4e3f14ad4](https://bsd-hardware.info/?probe=d4e3f14ad4) | Nov 23, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | Notebook    | [0391bf9ea4](https://bsd-hardware.info/?probe=0391bf9ea4) | Nov 14, 2021 |
| Dell          | 0N28XX A02                  | Server      | [b640c5a644](https://bsd-hardware.info/?probe=b640c5a644) | Nov 10, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [92b975763f](https://bsd-hardware.info/?probe=92b975763f) | Nov 08, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [fc919c73e3](https://bsd-hardware.info/?probe=fc919c73e3) | Nov 07, 2021 |
| Google        | Grunt                       | Notebook    | [aa07a1dd40](https://bsd-hardware.info/?probe=aa07a1dd40) | Nov 05, 2021 |
| Google        | Grunt                       | Notebook    | [c87e033731](https://bsd-hardware.info/?probe=c87e033731) | Nov 01, 2021 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [a6b7ceeada](https://bsd-hardware.info/?probe=a6b7ceeada) | Oct 20, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [4fdd90135a](https://bsd-hardware.info/?probe=4fdd90135a) | Oct 20, 2021 |
| Google        | Grunt                       | Notebook    | [e6d4421a4d](https://bsd-hardware.info/?probe=e6d4421a4d) | Oct 16, 2021 |
| Google        | Grunt                       | Notebook    | [ee9b2d7ad3](https://bsd-hardware.info/?probe=ee9b2d7ad3) | Oct 15, 2021 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [f57ea5540f](https://bsd-hardware.info/?probe=f57ea5540f) | Oct 13, 2021 |
| Google        | Grunt                       | Notebook    | [e76c73d9a3](https://bsd-hardware.info/?probe=e76c73d9a3) | Oct 11, 2021 |
| Acer          | Aspire A315-56              | Notebook    | [03ca802f4b](https://bsd-hardware.info/?probe=03ca802f4b) | Oct 02, 2021 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [8cb8c4dbf4](https://bsd-hardware.info/?probe=8cb8c4dbf4) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1ef37663db](https://bsd-hardware.info/?probe=1ef37663db) | Sep 01, 2021 |
| Dell          | 0M877N A01                  | Server      | [1585126252](https://bsd-hardware.info/?probe=1585126252) | Aug 18, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [4737978dbf](https://bsd-hardware.info/?probe=4737978dbf) | Aug 18, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [bd4b0f0700](https://bsd-hardware.info/?probe=bd4b0f0700) | Aug 17, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [04d9692802](https://bsd-hardware.info/?probe=04d9692802) | Aug 09, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [24df2da075](https://bsd-hardware.info/?probe=24df2da075) | Aug 08, 2021 |
| PC Engines    | apu4                        | Desktop     | [815567b75c](https://bsd-hardware.info/?probe=815567b75c) | Aug 02, 2021 |
| PC Engines    | apu4                        | Desktop     | [77fa195d5e](https://bsd-hardware.info/?probe=77fa195d5e) | Aug 02, 2021 |
| Lenovo        | ThinkPad X250 20CLS4JH00    | Notebook    | [89a74889ae](https://bsd-hardware.info/?probe=89a74889ae) | Aug 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [c577b93feb](https://bsd-hardware.info/?probe=c577b93feb) | Jul 24, 2021 |
| Lenovo        | ThinkPad T400 2767WSB       | Notebook    | [36ce1d1e00](https://bsd-hardware.info/?probe=36ce1d1e00) | Jul 24, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [52e8a39fb1](https://bsd-hardware.info/?probe=52e8a39fb1) | Jul 19, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | Notebook    | [5b43300a93](https://bsd-hardware.info/?probe=5b43300a93) | Jul 13, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [452a8558c0](https://bsd-hardware.info/?probe=452a8558c0) | Jul 09, 2021 |
| Dell          | 05XGC8 A01                  | Desktop     | [b9841b1272](https://bsd-hardware.info/?probe=b9841b1272) | Jul 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [935263c5a0](https://bsd-hardware.info/?probe=935263c5a0) | Jul 03, 2021 |
| HP            | 82A1                        | Desktop     | [dba57fb77f](https://bsd-hardware.info/?probe=dba57fb77f) | Jun 30, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [18e34c37cd](https://bsd-hardware.info/?probe=18e34c37cd) | Jun 28, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [3d717eec8f](https://bsd-hardware.info/?probe=3d717eec8f) | Jun 25, 2021 |
| Dell          | 0P03DX A03                  | Desktop     | [b2f0c90d79](https://bsd-hardware.info/?probe=b2f0c90d79) | Jun 24, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [1b8d66e5f0](https://bsd-hardware.info/?probe=1b8d66e5f0) | Jun 22, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [5091db2ace](https://bsd-hardware.info/?probe=5091db2ace) | Jun 16, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [c6d7626b29](https://bsd-hardware.info/?probe=c6d7626b29) | Jun 12, 2021 |
| ASRock        | X99 WS                      | Desktop     | [201a7417a5](https://bsd-hardware.info/?probe=201a7417a5) | Jun 11, 2021 |
| Dell          | 0NR282 A00                  | Server      | [f3854ba6e8](https://bsd-hardware.info/?probe=f3854ba6e8) | Jun 07, 2021 |
| Sony          | SVP1322M1EBI                | Notebook    | [23316d0f2b](https://bsd-hardware.info/?probe=23316d0f2b) | May 29, 2021 |
| PC Engines    | APU2                        | Desktop     | [2070f50252](https://bsd-hardware.info/?probe=2070f50252) | May 26, 2021 |
| ASUSTek       | Z87-DELUXE/DUAL             | Desktop     | [69a811cae5](https://bsd-hardware.info/?probe=69a811cae5) | May 25, 2021 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [586a4db247](https://bsd-hardware.info/?probe=586a4db247) | May 20, 2021 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [eb0c02a451](https://bsd-hardware.info/?probe=eb0c02a451) | May 19, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [62b9ea2794](https://bsd-hardware.info/?probe=62b9ea2794) | May 14, 2021 |
| Dell          | Latitude 5500               | Notebook    | [2538b038ed](https://bsd-hardware.info/?probe=2538b038ed) | May 08, 2021 |
| ASRock        | X99 WS                      | Desktop     | [eb20367455](https://bsd-hardware.info/?probe=eb20367455) | May 05, 2021 |
| Dell          | 0NR282 A00                  | Server      | [09082703f8](https://bsd-hardware.info/?probe=09082703f8) | Apr 29, 2021 |
| Dell          | 03X6X0 A01                  | Server      | [9f13074b78](https://bsd-hardware.info/?probe=9f13074b78) | Apr 24, 2021 |
| ASUSTek       | All Series                  | Desktop     | [ef6afe88d7](https://bsd-hardware.info/?probe=ef6afe88d7) | Apr 17, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [ad564817c9](https://bsd-hardware.info/?probe=ad564817c9) | Apr 11, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [0712c3048c](https://bsd-hardware.info/?probe=0712c3048c) | Apr 11, 2021 |
| Dell          | 09T7VV A05                  | Server      | [668c05619b](https://bsd-hardware.info/?probe=668c05619b) | Apr 09, 2021 |
| Dell          | 09T7VV A05                  | Server      | [917ab2c4e6](https://bsd-hardware.info/?probe=917ab2c4e6) | Apr 06, 2021 |
| Shuttle       | FH170                       | Desktop     | [d36fccf7b7](https://bsd-hardware.info/?probe=d36fccf7b7) | Apr 01, 2021 |
| Dell          | 0F0XJ6 A02                  | Server      | [052c1899c8](https://bsd-hardware.info/?probe=052c1899c8) | Mar 29, 2021 |
| Dell          | 0F0XJ6 A02                  | Server      | [806c6f796e](https://bsd-hardware.info/?probe=806c6f796e) | Mar 29, 2021 |
| MSI           | IONA                        | Desktop     | [5f857882ff](https://bsd-hardware.info/?probe=5f857882ff) | Mar 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [93ef7a4b6e](https://bsd-hardware.info/?probe=93ef7a4b6e) | Mar 22, 2021 |
| ASUSTek       | All Series                  | Desktop     | [c5bc64e4e9](https://bsd-hardware.info/?probe=c5bc64e4e9) | Mar 22, 2021 |
| ASUSTek       | All Series                  | Desktop     | [700ff7d378](https://bsd-hardware.info/?probe=700ff7d378) | Mar 22, 2021 |
| HP            | 8054                        | Desktop     | [1db522699a](https://bsd-hardware.info/?probe=1db522699a) | Mar 21, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [ddc66bc2fb](https://bsd-hardware.info/?probe=ddc66bc2fb) | Mar 20, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a5833ca2c9](https://bsd-hardware.info/?probe=a5833ca2c9) | Mar 18, 2021 |
| HP            | 8053                        | Desktop     | [b7ebdfe456](https://bsd-hardware.info/?probe=b7ebdfe456) | Mar 17, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [e95d6c6972](https://bsd-hardware.info/?probe=e95d6c6972) | Mar 17, 2021 |
| Lenovo        | ThinkPad X395 20NL001SMX    | Notebook    | [cd016e96ee](https://bsd-hardware.info/?probe=cd016e96ee) | Mar 17, 2021 |
| ADI           | MinnowBoard Turbot          | Desktop     | [ebd85cee04](https://bsd-hardware.info/?probe=ebd85cee04) | Mar 14, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [93c9f14bf0](https://bsd-hardware.info/?probe=93c9f14bf0) | Mar 12, 2021 |
| Dell          | 0XCR8D A02                  | Desktop     | [af5d6a85ef](https://bsd-hardware.info/?probe=af5d6a85ef) | Mar 09, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [a9f921e29b](https://bsd-hardware.info/?probe=a9f921e29b) | Mar 03, 2021 |
| Intel         | DQ67SW AAG12527-306         | Desktop     | [a4fb7ae326](https://bsd-hardware.info/?probe=a4fb7ae326) | Mar 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [b00dc0301a](https://bsd-hardware.info/?probe=b00dc0301a) | Feb 27, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [da62664934](https://bsd-hardware.info/?probe=da62664934) | Feb 23, 2021 |
| Dell          | Latitude E7240              | Notebook    | [e42e579971](https://bsd-hardware.info/?probe=e42e579971) | Feb 22, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [7968c7d2dd](https://bsd-hardware.info/?probe=7968c7d2dd) | Feb 16, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f8bdec0105](https://bsd-hardware.info/?probe=f8bdec0105) | Feb 14, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [5ca10a4860](https://bsd-hardware.info/?probe=5ca10a4860) | Feb 14, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [263a74d1ce](https://bsd-hardware.info/?probe=263a74d1ce) | Feb 12, 2021 |
| ASUSTek       | S551LN                      | Notebook    | [42792115e3](https://bsd-hardware.info/?probe=42792115e3) | Feb 11, 2021 |
| Toshiba       | Satellite L450              | Notebook    | [eb44256bfe](https://bsd-hardware.info/?probe=eb44256bfe) | Feb 11, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [508b3afc1c](https://bsd-hardware.info/?probe=508b3afc1c) | Feb 09, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [8b9f162f70](https://bsd-hardware.info/?probe=8b9f162f70) | Feb 09, 2021 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [dfb0240726](https://bsd-hardware.info/?probe=dfb0240726) | Feb 05, 2021 |
| PC Engines    | APU2                        | Desktop     | [8983ab6689](https://bsd-hardware.info/?probe=8983ab6689) | Feb 03, 2021 |
| HP            | 1905                        | Desktop     | [72ab5653d3](https://bsd-hardware.info/?probe=72ab5653d3) | Feb 03, 2021 |
| Microsoft     | Surface Go 2                | Tablet      | [69c8123ec6](https://bsd-hardware.info/?probe=69c8123ec6) | Feb 01, 2021 |
| HP            | 8103 A01                    | Mini pc     | [da8a373d43](https://bsd-hardware.info/?probe=da8a373d43) | Jan 30, 2021 |
| ADI           | MinnowBoard Turbot          | Desktop     | [137ff14192](https://bsd-hardware.info/?probe=137ff14192) | Jan 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [920259bf95](https://bsd-hardware.info/?probe=920259bf95) | Jan 28, 2021 |
| HP            | 8103 A01                    | Mini pc     | [55c7d22c4d](https://bsd-hardware.info/?probe=55c7d22c4d) | Jan 28, 2021 |
| HP            | ProLiant DL380 Gen9         | Server      | [c2bb148e8a](https://bsd-hardware.info/?probe=c2bb148e8a) | Jan 28, 2021 |
| Dell          | 06G98X A02                  | Server      | [b062e0f4e4](https://bsd-hardware.info/?probe=b062e0f4e4) | Jan 28, 2021 |
| Dell          | 0WCJNT A06                  | Server      | [4710d6000d](https://bsd-hardware.info/?probe=4710d6000d) | Jan 28, 2021 |
| ASUSTek       | All Series                  | Desktop     | [7ebe6eee38](https://bsd-hardware.info/?probe=7ebe6eee38) | Jan 25, 2021 |
| ADI           | MinnowBoard Turbot          | Desktop     | [e2fbc5f326](https://bsd-hardware.info/?probe=e2fbc5f326) | Jan 21, 2021 |
| ADI           | MinnowBoard Turbot          | Desktop     | [0b8e4d0630](https://bsd-hardware.info/?probe=0b8e4d0630) | Jan 21, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [bd3877826c](https://bsd-hardware.info/?probe=bd3877826c) | Jan 20, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [3a9d5d1a1d](https://bsd-hardware.info/?probe=3a9d5d1a1d) | Jan 20, 2021 |
| PC Engines    | APU2                        | Desktop     | [ecf35d22c4](https://bsd-hardware.info/?probe=ecf35d22c4) | Jan 12, 2021 |
| Lenovo        | ThinkPad X201 3680FAG       | Notebook    | [1ba69078df](https://bsd-hardware.info/?probe=1ba69078df) | Dec 06, 2020 |
| PC Engines    | APU2                        | Desktop     | [2e6256a0ab](https://bsd-hardware.info/?probe=2e6256a0ab) | Nov 23, 2020 |
| PC Engines    | APU2                        | Desktop     | [65de6946d3](https://bsd-hardware.info/?probe=65de6946d3) | Nov 23, 2020 |
| PC Engines    | APU2                        | Desktop     | [b4f5d7d344](https://bsd-hardware.info/?probe=b4f5d7d344) | Nov 16, 2020 |
| HP            | ProLiant ML30 Gen9          | Desktop     | [ecaec68cdb](https://bsd-hardware.info/?probe=ecaec68cdb) | Oct 27, 2020 |
| Intel         | NUC5CPYB                    | Mini pc     | [1ec5c12f0b](https://bsd-hardware.info/?probe=1ec5c12f0b) | Oct 27, 2020 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [547b36ea62](https://bsd-hardware.info/?probe=547b36ea62) | Aug 19, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | Notebook    | [acb3ad955f](https://bsd-hardware.info/?probe=acb3ad955f) | Aug 06, 2020 |
| Lenovo        | ThinkPad L560 20F10032MS    | Notebook    | [bf2b792b64](https://bsd-hardware.info/?probe=bf2b792b64) | Aug 06, 2020 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [0d2e0f44c1](https://bsd-hardware.info/?probe=0d2e0f44c1) | Aug 06, 2020 |
| Lenovo        | ThinkPad L560 20F10032MS    | Notebook    | [0aa6a9a921](https://bsd-hardware.info/?probe=0aa6a9a921) | Aug 06, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [6245f1e175](https://bsd-hardware.info/?probe=6245f1e175) | Aug 06, 2020 |
| Unknown       | Unknown                     | Desktop     | [4e3b87cc6c](https://bsd-hardware.info/?probe=4e3b87cc6c) | Jun 01, 2020 |
| Gigabyte      | Z170X-UD5 TH-CF             | Desktop     | [2fc2952380](https://bsd-hardware.info/?probe=2fc2952380) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 21.1     | 11        | 4.8%    |
| OPNsense 22.7.10  | 9         | 3.93%   |
| OPNsense 23.7.9   | 6         | 2.62%   |
| OPNsense 21.7.7   | 6         | 2.62%   |
| OPNsense 21.1.3   | 6         | 2.62%   |
| OpenBSD 6.8       | 6         | 2.62%   |
| OPNsense 23.7.10  | 5         | 2.18%   |
| OPNsense 23.1.11  | 5         | 2.18%   |
| OPNsense 21.1.5   | 5         | 2.18%   |
| OPNsense 21.1.2   | 5         | 2.18%   |
| OpenBSD 7.0       | 5         | 2.18%   |
| helloSystem 0.5.0 | 5         | 2.18%   |
| OPNsense 23.7.7   | 4         | 1.75%   |
| OPNsense 22.7.8   | 4         | 1.75%   |
| OPNsense 21.1.8   | 4         | 1.75%   |
| OPNsense 23.7.6   | 3         | 1.31%   |
| OPNsense 23.7.5   | 3         | 1.31%   |
| OPNsense 23.7.4   | 3         | 1.31%   |
| OPNsense 23.7.1   | 3         | 1.31%   |
| OPNsense 23.1.6   | 3         | 1.31%   |
| OPNsense 23.1.3   | 3         | 1.31%   |
| OPNsense 23.1.10  | 3         | 1.31%   |
| OPNsense 22.7.9   | 3         | 1.31%   |
| OPNsense 22.7.2   | 3         | 1.31%   |
| OPNsense 22.1.8   | 3         | 1.31%   |
| OPNsense 21.7.3   | 3         | 1.31%   |
| OPNsense 21.7.1   | 3         | 1.31%   |
| OPNsense 20.7.8   | 3         | 1.31%   |
| OpenBSD 6.9       | 3         | 1.31%   |
| helloSystem 0.8.0 | 3         | 1.31%   |
| helloSystem 0.7.0 | 3         | 1.31%   |
| FreeBSD 13.1-p5   | 3         | 1.31%   |
| FreeBSD 13.0-p7   | 3         | 1.31%   |
| FreeBSD 12.1-p8   | 3         | 1.31%   |
| OPNsense 23.7.8   | 2         | 0.87%   |
| OPNsense 23.1.7   | 2         | 0.87%   |
| OPNsense 23.1.2   | 2         | 0.87%   |
| OPNsense 23.1.1   | 2         | 0.87%   |
| OPNsense 23.1     | 2         | 0.87%   |
| OPNsense 22.7.7   | 2         | 0.87%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 122       | 63.87%  |
| FreeBSD     | 31        | 16.23%  |
| OpenBSD     | 16        | 8.38%   |
| helloSystem | 15        | 7.85%   |
| GhostBSD    | 4         | 2.09%   |
| pfSense     | 1         | 0.52%   |
| NomadBSD    | 1         | 0.52%   |
| FuryBSD     | 1         | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 190       | 99.48%  |
| octeon | 1         | 0.52%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 137       | 70.98%  |
| helloDesktop | 16        | 8.29%   |
| KDE5         | 12        | 6.22%   |
| fvwm         | 12        | 6.22%   |
| MATE         | 5         | 2.59%   |
| XFCE         | 2         | 1.04%   |
| i3           | 2         | 1.04%   |
| xfwm         | 1         | 0.52%   |
| TWM          | 1         | 0.52%   |
| Openbox      | 1         | 0.52%   |
| Mutter       | 1         | 0.52%   |
| LXQt         | 1         | 0.52%   |
| GNOME        | 1         | 0.52%   |
| AwesomeWM    | 1         | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 138       | 72.25%  |
| X11     | 53        | 27.75%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 151       | 77.84%  |
| SLiM    | 16        | 8.25%   |
| SDDM    | 13        | 6.7%    |
| LightDM | 7         | 3.61%   |
| GDM     | 5         | 2.58%   |
| XDM     | 2         | 1.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 137       | 70.98%  |
| en_US          | 26        | 13.47%  |
| C              | 19        | 9.84%   |
| sv_SE          | 5         | 2.59%   |
| sv_SE.US-ASCII | 1         | 0.52%   |
| sv             | 1         | 0.52%   |
| en_GB          | 1         | 0.52%   |
| en_CA          | 1         | 0.52%   |
| en_BE          | 1         | 0.52%   |
| en             | 1         | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 166       | 86.01%  |
| BIOS | 27        | 13.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 95        | 49.22%  |
| Zfs    | 77        | 39.9%   |
| Ffs    | 16        | 8.29%   |
| Cd9660 | 5         | 2.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 177       | 91.24%  |
| MBR     | 16        | 8.25%   |
| Unknown | 1         | 0.52%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Hewlett-Packard            | 21        | 10.99%  |
| Dell                       | 21        | 10.99%  |
| Lenovo                     | 20        | 10.47%  |
| ASUSTek Computer           | 18        | 9.42%   |
| Unknown                    | 16        | 8.38%   |
| PC Engines                 | 13        | 6.81%   |
| Intel                      | 11        | 5.76%   |
| Gigabyte Technology        | 9         | 4.71%   |
| MSI                        | 7         | 3.66%   |
| AMI                        | 7         | 3.66%   |
| Supermicro                 | 6         | 3.14%   |
| Techvision                 | 3         | 1.57%   |
| Microsoft                  | 3         | 1.57%   |
| Fujitsu                    | 3         | 1.57%   |
| CWWK                       | 3         | 1.57%   |
| ASRock                     | 3         | 1.57%   |
| Apple                      | 3         | 1.57%   |
| Toshiba                    | 2         | 1.05%   |
| Shuttle                    | 2         | 1.05%   |
| HPE                        | 2         | 1.05%   |
| Deciso                     | 2         | 1.05%   |
| ZOTAC                      | 1         | 0.52%   |
| Wistron                    | 1         | 0.52%   |
| Star Labs                  | 1         | 0.52%   |
| Sony                       | 1         | 0.52%   |
| ShenZhen MinWin Technology | 1         | 0.52%   |
| Protectli                  | 1         | 0.52%   |
| Google                     | 1         | 0.52%   |
| Fujitsu Siemens            | 1         | 0.52%   |
| DFI                        | 1         | 0.52%   |
| CompuLab                   | 1         | 0.52%   |
| Cisco                      | 1         | 0.52%   |
| AZW                        | 1         | 0.52%   |
| AOpen                      | 1         | 0.52%   |
| ADI                        | 1         | 0.52%   |
| ACMA                       | 1         | 0.52%   |
| Acer                       | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 17        | 8.9%    |
| PC Engines APU2                | 7         | 3.66%   |
| AMI Aptio CRB                  | 5         | 2.62%   |
| HP t730 Thin Client            | 4         | 2.09%   |
| Techvision TVI7309X            | 3         | 1.57%   |
| Supermicro Super Server        | 3         | 1.57%   |
| Intel CRESCENTBAY              | 3         | 1.57%   |
| ASUS All Series                | 3         | 1.57%   |
| Supermicro X10SLL-F            | 2         | 1.05%   |
| PC Engines apu4                | 2         | 1.05%   |
| PC Engines APU3                | 2         | 1.05%   |
| Microsoft Surface Pro 7        | 2         | 1.05%   |
| Intel Q3XXG4-P V1.0            | 2         | 1.05%   |
| Intel D54250WYK H13922-303     | 2         | 1.05%   |
| HP EliteDesk 800 G2 SFF        | 2         | 1.05%   |
| Dell PowerEdge R210 II         | 2         | 1.05%   |
| Dell PowerEdge R210            | 2         | 1.05%   |
| Dell OptiPlex 9020             | 2         | 1.05%   |
| ZOTAC ZBOX-CI329NANO           | 1         | 0.52%   |
| Wistron ProLiant ML110 G6      | 1         | 0.52%   |
| Toshiba TECRA Z40-C-12Z        | 1         | 0.52%   |
| Toshiba Satellite L450         | 1         | 0.52%   |
| Supermicro SYS-1019S-MP        | 1         | 0.52%   |
| Star Labs StarBook             | 1         | 0.52%   |
| Sony SVP1322M1EBI              | 1         | 0.52%   |
| Shuttle SH570                  | 1         | 0.52%   |
| Shuttle DH170                  | 1         | 0.52%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.52%   |
| Protectli FW4B                 | 1         | 0.52%   |
| PC Engines apu6                | 1         | 0.52%   |
| PC Engines APU                 | 1         | 0.52%   |
| MSI WC776AA-UUW HPE-110sc      | 1         | 0.52%   |
| MSI MS-7C56                    | 1         | 0.52%   |
| MSI MS-7B85                    | 1         | 0.52%   |
| MSI MS-7B43                    | 1         | 0.52%   |
| MSI MS-7A40                    | 1         | 0.52%   |
| MSI MS-7918                    | 1         | 0.52%   |
| MSI MS-7369                    | 1         | 0.52%   |
| Microsoft Surface Go 2         | 1         | 0.52%   |
| Lenovo V130-15IGM 81HL         | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 17        | 8.9%    |
| Dell PowerEdge                 | 11        | 5.76%   |
| Lenovo ThinkPad                | 9         | 4.71%   |
| PC Engines APU2                | 7         | 3.66%   |
| Dell OptiPlex                  | 6         | 3.14%   |
| Lenovo ThinkCentre             | 5         | 2.62%   |
| HP ProLiant                    | 5         | 2.62%   |
| HP EliteDesk                   | 5         | 2.62%   |
| AMI Aptio                      | 5         | 2.62%   |
| HP t730                        | 4         | 2.09%   |
| Techvision TVI7309X            | 3         | 1.57%   |
| Supermicro Super               | 3         | 1.57%   |
| Microsoft Surface              | 3         | 1.57%   |
| Intel CRESCENTBAY              | 3         | 1.57%   |
| Dell Latitude                  | 3         | 1.57%   |
| ASUS All                       | 3         | 1.57%   |
| Supermicro X10SLL-F            | 2         | 1.05%   |
| PC Engines apu4                | 2         | 1.05%   |
| PC Engines APU3                | 2         | 1.05%   |
| Lenovo IdeaPad                 | 2         | 1.05%   |
| Intel Q3XXG4-P                 | 2         | 1.05%   |
| Intel D54250WYK                | 2         | 1.05%   |
| HPE ProLiant                   | 2         | 1.05%   |
| ASUS ROG                       | 2         | 1.05%   |
| ZOTAC ZBOX-CI329NANO           | 1         | 0.52%   |
| Wistron ProLiant               | 1         | 0.52%   |
| Toshiba TECRA                  | 1         | 0.52%   |
| Toshiba Satellite              | 1         | 0.52%   |
| Supermicro SYS-1019S-MP        | 1         | 0.52%   |
| Star Labs StarBook             | 1         | 0.52%   |
| Sony SVP1322M1EBI              | 1         | 0.52%   |
| Shuttle SH570                  | 1         | 0.52%   |
| Shuttle DH170                  | 1         | 0.52%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.52%   |
| Protectli FW4B                 | 1         | 0.52%   |
| PC Engines apu6                | 1         | 0.52%   |
| PC Engines APU                 | 1         | 0.52%   |
| MSI WC776AA-UUW                | 1         | 0.52%   |
| MSI MS-7C56                    | 1         | 0.52%   |
| MSI MS-7B85                    | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2016    | 24        | 12.57%  |
| 2020    | 19        | 9.95%   |
| 2017    | 17        | 8.9%    |
| 2014    | 17        | 8.9%    |
| 2022    | 16        | 8.38%   |
| 2019    | 14        | 7.33%   |
| 2018    | 13        | 6.81%   |
| 2021    | 12        | 6.28%   |
| 2015    | 11        | 5.76%   |
| 2010    | 11        | 5.76%   |
| 2012    | 9         | 4.71%   |
| 2023    | 7         | 3.66%   |
| 2013    | 7         | 3.66%   |
| 2009    | 7         | 3.66%   |
| 2011    | 4         | 2.09%   |
| 2007    | 1         | 0.52%   |
| 2006    | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 119       | 62.3%   |
| Notebook   | 34        | 17.8%   |
| Server     | 22        | 11.52%  |
| Mini pc    | 12        | 6.28%   |
| Tablet     | 3         | 1.57%   |
| All in one | 1         | 0.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 174       | 91.1%   |
| Yes  | 17        | 8.9%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 67        | 34.54%  |
| 4.01-8.0        | 45        | 23.2%   |
| 16.01-24.0      | 40        | 20.62%  |
| 32.01-64.0      | 18        | 9.28%   |
| 64.01-256.0     | 7         | 3.61%   |
| 24.01-32.0      | 6         | 3.09%   |
| 2.01-3.0        | 5         | 2.58%   |
| More than 256.0 | 3         | 1.55%   |
| 3.01-4.0        | 2         | 1.03%   |
| 1.01-2.0        | 1         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 99        | 50.77%  |
| 0.51-1.0    | 60        | 30.77%  |
| 1.01-2.0    | 20        | 10.26%  |
| 2.01-3.0    | 5         | 2.56%   |
| 4.01-8.0    | 4         | 2.05%   |
| 3.01-4.0    | 2         | 1.03%   |
| 24.01-32.0  | 2         | 1.03%   |
| 64.01-256.0 | 2         | 1.03%   |
| 32.01-64.0  | 1         | 0.51%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 137       | 70.26%  |
| 2      | 19        | 9.74%   |
| 0      | 12        | 6.15%   |
| 3      | 11        | 5.64%   |
| 6      | 4         | 2.05%   |
| 4      | 3         | 1.54%   |
| 11     | 2         | 1.03%   |
| 8      | 2         | 1.03%   |
| 18     | 1         | 0.51%   |
| 12     | 1         | 0.51%   |
| 10     | 1         | 0.51%   |
| 9      | 1         | 0.51%   |
| 5      | 1         | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 158       | 82.29%  |
| Yes       | 34        | 17.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 180       | 94.24%  |
| No        | 11        | 5.76%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 130       | 67.71%  |
| Yes       | 62        | 32.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 148       | 77.08%  |
| Yes       | 44        | 22.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Sweden  | 191       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Stockholm             | 29        | 13.49%  |
| Malmo                 | 13        | 6.05%   |
| Gothenburg            | 8         | 3.72%   |
| Bromma                | 6         | 2.79%   |
| LinkГ¶ping          | 5         | 2.33%   |
| VÃ¤sterÃ¥s        | 4         | 1.86%   |
| Västerås            | 4         | 1.86%   |
| UmeГҐ               | 4         | 1.86%   |
| Uppsala               | 3         | 1.4%    |
| Taby                  | 3         | 1.4%    |
| Sollentuna            | 3         | 1.4%    |
| Piteå                | 3         | 1.4%    |
| Lund                  | 3         | 1.4%    |
| Linköping            | 3         | 1.4%    |
| Karlskrona            | 3         | 1.4%    |
| JГ¶nkГ¶ping       | 3         | 1.4%    |
| Henan                 | 3         | 1.4%    |
| Gävle                | 3         | 1.4%    |
| Bandhagen             | 3         | 1.4%    |
| Upplands Vasby        | 2         | 0.93%   |
| Umeå                 | 2         | 0.93%   |
| Tyreso Strand         | 2         | 0.93%   |
| Tumba                 | 2         | 0.93%   |
| Solna                 | 2         | 0.93%   |
| Solleftea             | 2         | 0.93%   |
| Skövde               | 2         | 0.93%   |
| Örebro               | 2         | 0.93%   |
| Landskrona            | 2         | 0.93%   |
| Kungsbacka            | 2         | 0.93%   |
| Jönköping           | 2         | 0.93%   |
| Helsingborg           | 2         | 0.93%   |
| Falkenberg            | 2         | 0.93%   |
| Enskede-Arsta-Vantoer | 2         | 0.93%   |
| Г…hus              | 1         | 0.47%   |
| Г„lvГ¤ngen       | 1         | 0.47%   |
| Vaxjo                 | 1         | 0.47%   |
| Varekil               | 1         | 0.47%   |
| UmeÃ¥               | 1         | 0.47%   |
| Ulricehamn            | 1         | 0.47%   |
| Trosa                 | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 42        | 58     | 18.18%  |
| Kingston            | 25        | 32     | 10.82%  |
| Seagate             | 22        | 52     | 9.52%   |
| WDC                 | 21        | 32     | 9.09%   |
| Intel               | 19        | 35     | 8.23%   |
| Hoodisk             | 15        | 23     | 6.49%   |
| SanDisk             | 10        | 13     | 4.33%   |
| Crucial             | 9         | 18     | 3.9%    |
| Toshiba             | 8         | 18     | 3.46%   |
| NVMe                | 5         | 6      | 2.16%   |
| Transcend           | 4         | 4      | 1.73%   |
| Micron Technology   | 4         | 7      | 1.73%   |
| Hewlett-Packard     | 4         | 8      | 1.73%   |
| Phison              | 3         | 3      | 1.3%    |
| OCZ                 | 3         | 5      | 1.3%    |
| LITEON              | 3         | 6      | 1.3%    |
| Hitachi             | 3         | 3      | 1.3%    |
| China               | 3         | 3      | 1.3%    |
| Apple               | 3         | 3      | 1.3%    |
| SK hynix            | 2         | 2      | 0.87%   |
| Innodisk            | 2         | 3      | 0.87%   |
| HPE                 | 2         | 14     | 0.87%   |
| Apacer              | 2         | 2      | 0.87%   |
| A-DATA Technology   | 2         | 2      | 0.87%   |
| XrayDisk            | 1         | 1      | 0.43%   |
| Supermicro          | 1         | 1      | 0.43%   |
| Star Drive          | 1         | 1      | 0.43%   |
| Silicon Motion      | 1         | 1      | 0.43%   |
| PNY                 | 1         | 1      | 0.43%   |
| MARVELL             | 1         | 2      | 0.43%   |
| LITEONIT            | 1         | 1      | 0.43%   |
| KingSpec            | 1         | 1      | 0.43%   |
| Kimtigo             | 1         | 1      | 0.43%   |
| HGST                | 1         | 4      | 0.43%   |
| Fordisk             | 1         | 1      | 0.43%   |
| faspeed             | 1         | 1      | 0.43%   |
| Fanxiang            | 1         | 2      | 0.43%   |
| Dell                | 1         | 2      | 0.43%   |
| Corsair             | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| SanDisk SDSA6MM-032G-1006 32GB | 4         | 1.56%   |
| Kingston SA400S37120G 120GB    | 4         | 1.56%   |
| Hoodisk SSD 64GB               | 4         | 1.56%   |
| Hoodisk SSD 16GB               | 4         | 1.56%   |
| Hoodisk SSD 128GB              | 4         | 1.56%   |
| Samsung SSD 860 QVO 1TB        | 3         | 1.17%   |
| Kingston SA400S37240G 240GB    | 3         | 1.17%   |
| Intel SSDSC2BW240A4 240GB      | 3         | 1.17%   |
| WDC WD5000AZLX-60K2TA0 500GB   | 2         | 0.78%   |
| Toshiba HDWR11A 10TB           | 2         | 0.78%   |
| Toshiba HDWQ140 4TB            | 2         | 0.78%   |
| Seagate ST4000DM004-2CV104 4TB | 2         | 0.78%   |
| Seagate ST2000DM008-2FR102 2TB | 2         | 0.78%   |
| Seagate ST1000DM010-2EP102 1TB | 2         | 0.78%   |
| SanDisk SDSSDHP256G 256GB      | 2         | 0.78%   |
| Samsung SSD 970 EVO Plus 500GB | 2         | 0.78%   |
| Samsung SSD 970 EVO 500GB      | 2         | 0.78%   |
| Samsung SSD 870 EVO 250GB      | 2         | 0.78%   |
| Samsung SSD 860 EVO 250GB      | 2         | 0.78%   |
| Samsung SSD 850 EVO 250GB      | 2         | 0.78%   |
| Samsung SSD 840 EVO 120GB      | 2         | 0.78%   |
| Samsung HD501LJ 500GB          | 2         | 0.78%   |
| Phison SATA SSD 16GB           | 2         | 0.78%   |
| OCZ AGILITY3 120GB             | 2         | 0.78%   |
| NVMe KBG40ZPZ256G TOS 256GB    | 2         | 0.78%   |
| Kingston SV300S37A240G 240GB   | 2         | 0.78%   |
| Kingston SV300S37A120G 120GB   | 2         | 0.78%   |
| Kingston SKC600MS256G 256GB    | 2         | 0.78%   |
| Intel SSDSC2CT120A3 120GB      | 2         | 0.78%   |
| Intel SSDSC2CT060A3 64GB       | 2         | 0.78%   |
| Hoodisk SSD 32GB               | 2         | 0.78%   |
| HP RAID 1(1+0) 304GB           | 2         | 0.78%   |
| Crucial CT256MX100SSD1 256GB   | 2         | 0.78%   |
| China SATA SSD 16GB            | 2         | 0.78%   |
| Apacer 64GB SATA Flash Drive   | 2         | 0.78%   |
| XrayDisk SSD 64GB              | 1         | 0.39%   |
| WDC WDS500G3X0C-00SJG0 500GB   | 1         | 0.39%   |
| WDC WDS250G2B0C-00PXH0 250GB   | 1         | 0.39%   |
| WDC WDS250G2B0A-00SM50 250GB   | 1         | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB   | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 50     | 35%     |
| WDC                 | 14        | 23     | 23.33%  |
| Toshiba             | 6         | 15     | 10%     |
| Samsung Electronics | 6         | 9      | 10%     |
| Hewlett-Packard     | 4         | 8      | 6.67%   |
| NVMe                | 3         | 4      | 5%      |
| Hitachi             | 3         | 3      | 5%      |
| HPE                 | 1         | 8      | 1.67%   |
| HGST                | 1         | 4      | 1.67%   |
| Apple               | 1         | 1      | 1.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 38     | 20.28%  |
| Kingston            | 23        | 30     | 16.08%  |
| Intel               | 16        | 31     | 11.19%  |
| Hoodisk             | 15        | 23     | 10.49%  |
| SanDisk             | 10        | 13     | 6.99%   |
| Crucial             | 7         | 16     | 4.9%    |
| Micron Technology   | 4         | 7      | 2.8%    |
| WDC                 | 3         | 5      | 2.1%    |
| OCZ                 | 3         | 5      | 2.1%    |
| LITEON              | 3         | 6      | 2.1%    |
| China               | 3         | 3      | 2.1%    |
| Transcend           | 2         | 2      | 1.4%    |
| Toshiba             | 2         | 3      | 1.4%    |
| SK hynix            | 2         | 2      | 1.4%    |
| Phison              | 2         | 2      | 1.4%    |
| NVMe                | 2         | 2      | 1.4%    |
| Innodisk            | 2         | 3      | 1.4%    |
| Apple               | 2         | 2      | 1.4%    |
| Apacer              | 2         | 2      | 1.4%    |
| XrayDisk            | 1         | 1      | 0.7%    |
| Supermicro          | 1         | 1      | 0.7%    |
| Seagate             | 1         | 1      | 0.7%    |
| PNY                 | 1         | 1      | 0.7%    |
| MARVELL             | 1         | 2      | 0.7%    |
| LITEONIT            | 1         | 1      | 0.7%    |
| KingSpec            | 1         | 1      | 0.7%    |
| HPE                 | 1         | 6      | 0.7%    |
| Fordisk             | 1         | 1      | 0.7%    |
| Dell                | 1         | 2      | 0.7%    |
| Corsair             | 1         | 1      | 0.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 126       | 213    | 61.46%  |
| HDD  | 47        | 125    | 22.93%  |
| NVMe | 32        | 35     | 15.61%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 156       | 338    | 82.98%  |
| NVMe | 32        | 35     | 17.02%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 139       | 217    | 71.28%  |
| 0.51-1.0   | 30        | 45     | 15.38%  |
| 3.01-4.0   | 10        | 28     | 5.13%   |
| 1.01-2.0   | 9         | 24     | 4.62%   |
| 4.01-10.0  | 7         | 24     | 3.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 85        | 43.59%  |
| 1-20           | 25        | 12.82%  |
| 251-500        | 23        | 11.79%  |
| 51-100         | 23        | 11.79%  |
| 21-50          | 21        | 10.77%  |
| 501-1000       | 11        | 5.64%   |
| 1001-2000      | 4         | 2.05%   |
| More than 3000 | 3         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 171       | 87.24%  |
| 21-50          | 19        | 9.69%   |
| 251-500        | 2         | 1.02%   |
| 101-250        | 2         | 1.02%   |
| More than 3000 | 1         | 0.51%   |
| 1001-2000      | 1         | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000DM010-2EP102 1TB               | 2         | 2      | 5.71%   |
| Kingston SV300S37A120G 120GB                 | 2         | 2      | 5.71%   |
| Intel SSDSC2CT120A3 120GB                    | 2         | 2      | 5.71%   |
| WDC WD6400AARS-00Y5B1 640GB                  | 1         | 1      | 2.86%   |
| WDC WD40EFRX-68N32N0 4TB                     | 1         | 2      | 2.86%   |
| WDC WD2500AAJS-60B4A0 250GB                  | 1         | 2      | 2.86%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 2      | 2.86%   |
| WDC WD20EARX-00ZUDB0 2TB                     | 1         | 1      | 2.86%   |
| WDC WD2002FYPS-02W3B0 2TB                    | 1         | 1      | 2.86%   |
| WDC WD15EARS-00Z5B1 1.5TB                    | 1         | 1      | 2.86%   |
| WDC WD15EARS-00MVWB0 1.5TB                   | 1         | 1      | 2.86%   |
| WDC WD10EAVS-00D7B0 1TB                      | 1         | 1      | 2.86%   |
| SK hynix HFS128G32MND-2200A 128GB            | 1         | 1      | 2.86%   |
| Seagate ST9640320AS 640GB                    | 1         | 1      | 2.86%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 2.86%   |
| Seagate ST9320423AS 320GB                    | 1         | 1      | 2.86%   |
| Seagate ST8000AS0002-1NA17Z 8TB              | 1         | 1      | 2.86%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 2.86%   |
| Seagate ST2000DM008-2FR102 2TB               | 1         | 1      | 2.86%   |
| Seagate ST100FN0021 100GB                    | 1         | 1      | 2.86%   |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 1      | 2.86%   |
| Seagate ST1000DM003-1ER162 1TB               | 1         | 1      | 2.86%   |
| Samsung Electronics SSD 970 EVO 500GB        | 1         | 1      | 2.86%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB | 1         | 1      | 2.86%   |
| Samsung Electronics HM250JI 250GB            | 1         | 1      | 2.86%   |
| Samsung Electronics HD321KJ 320GB            | 1         | 1      | 2.86%   |
| OCZ AGILITY3 120GB                           | 1         | 2      | 2.86%   |
| Kingston SMS200S3120G 120GB                  | 1         | 1      | 2.86%   |
| Intel SSDSC2CT060A3 64GB                     | 1         | 2      | 2.86%   |
| Intel SSDSC2BA400G4 400GB                    | 1         | 1      | 2.86%   |
| Intel SSDSA2M080G2GC 80GB                    | 1         | 1      | 2.86%   |
| Hitachi HTS725025A9A364 250GB                | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 32.26%  |
| WDC                 | 6         | 12     | 19.35%  |
| Intel               | 5         | 6      | 16.13%  |
| Samsung Electronics | 4         | 4      | 12.9%   |
| Kingston            | 3         | 3      | 9.68%   |
| SK hynix            | 1         | 1      | 3.23%   |
| OCZ                 | 1         | 2      | 3.23%   |
| Hitachi             | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 50%     |
| WDC                 | 6         | 12     | 33.33%  |
| Samsung Electronics | 2         | 2      | 11.11%  |
| Hitachi             | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 25     | 55.17%  |
| SSD  | 12        | 14     | 41.38%  |
| NVMe | 1         | 1      | 3.45%   |

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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 156       | 313    | 78.79%  |
| Malfunc  | 29        | 40     | 14.65%  |
| Detected | 13        | 20     | 6.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 139       | 58.9%   |
| AMD                           | 32        | 13.56%  |
| Samsung Electronics           | 13        | 5.51%   |
| Broadcom / LSI                | 9         | 3.81%   |
| Marvell Technology Group      | 6         | 2.54%   |
| Silicon Motion                | 5         | 2.12%   |
| SanDisk                       | 4         | 1.69%   |
| Hewlett-Packard               | 4         | 1.69%   |
| ASMedia Technology            | 4         | 1.69%   |
| Kingston Technology Company   | 3         | 1.27%   |
| Phison Electronics            | 2         | 0.85%   |
| Micron/Crucial Technology     | 2         | 0.85%   |
| KIOXIA                        | 2         | 0.85%   |
| Adaptec                       | 2         | 0.85%   |
| VIA Technologies              | 1         | 0.42%   |
| Transcend                     | 1         | 0.42%   |
| Seagate Technology            | 1         | 0.42%   |
| Realtek Semiconductor         | 1         | 0.42%   |
| Nvidia                        | 1         | 0.42%   |
| Integrated Technology Express | 1         | 0.42%   |
| Dell                          | 1         | 0.42%   |
| ADATA Technology              | 1         | 0.42%   |
| 3ware                         | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 25        | 9.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 13        | 4.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 4.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 2.93%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 8         | 2.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 2.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 2.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 7         | 2.56%   |
| Intel SATA Controller [RAID mode]                                                | 6         | 2.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 2.2%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 5         | 1.83%   |
| AMD FCH IDE Controller                                                           | 5         | 1.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.47%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 4         | 1.47%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 4         | 1.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.1%    |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 3         | 1.1%    |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 1.1%    |
| AMD 500 Series Chipset SATA Controller                                           | 3         | 1.1%    |
| AMD 300 Series Chipset SATA Controller                                           | 3         | 1.1%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 2         | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.73%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 2         | 0.73%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 0.73%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 0.73%   |
| Intel unknown                                                                    | 2         | 0.73%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.73%   |
| Intel SSD 660P Series                                                            | 2         | 0.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 0.73%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 2         | 0.73%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 2         | 0.73%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 0.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 0.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 154       | 62.86%  |
| NVMe | 38        | 15.51%  |
| IDE  | 25        | 10.2%   |
| RAID | 21        | 8.57%   |
| SAS  | 7         | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 155       | 80.73%  |
| AMD     | 36        | 18.75%  |
| Unknown | 1         | 0.52%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                         | 12        | 6.22%   |
| Intel Celeron N5105 @ 2.00GHz            | 6         | 3.11%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 5         | 2.59%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 5         | 2.59%   |
| Intel N100                               | 4         | 2.07%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 4         | 2.07%   |
| Intel Core i7-4770K CPU @ 3.50GHz        | 3         | 1.55%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 3         | 1.55%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 3         | 1.55%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz      | 2         | 1.04%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz      | 2         | 1.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 1.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 2         | 1.04%   |
| Intel Core i5-6400 CPU @ 2.70GHz         | 2         | 1.04%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 2         | 1.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 2         | 1.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 1.04%   |
| Intel Core i5-4250U CPU @ 1.30GHz        | 2         | 1.04%   |
| Intel Core i5-4200U CPU @ 1.60GHz        | 2         | 1.04%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz       | 2         | 1.04%   |
| Intel Core i5 CPU M 540 @ 2.53GHz        | 2         | 1.04%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 2         | 1.04%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 2         | 1.04%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2         | 1.04%   |
| AMD Ryzen 9 3900X 12-Core Processor      | 2         | 1.04%   |
| AMD Ryzen 7 1700 Eight-Core Processor    | 2         | 1.04%   |
| Intel Xeon Silver 4116 CPU @ 2.10GHz     | 1         | 0.52%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz     | 1         | 0.52%   |
| Intel Xeon Silver 4110 CPU @ 2.10GHz     | 1         | 0.52%   |
| Intel Xeon E-2224 CPU @ 3.40GHz          | 1         | 0.52%   |
| Intel Xeon CPU X5680 @ 3.33GHz           | 1         | 0.52%   |
| Intel Xeon CPU X3470 @ 2.93GHz           | 1         | 0.52%   |
| Intel Xeon CPU X3450 @ 2.67GHz           | 1         | 0.52%   |
| Intel Xeon CPU X3440 @ 2.53GHz           | 1         | 0.52%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5640 @ 2.67GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5450 @ 3.00GHz           | 1         | 0.52%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz       | 1         | 0.52%   |
| Intel Xeon CPU E5-2623 v4 @ 2.60GHz      | 1         | 0.52%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz       | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 46        | 23.83%  |
| Intel Xeon              | 28        | 14.51%  |
| Intel Celeron           | 23        | 11.92%  |
| Intel Core i7           | 21        | 10.88%  |
| Other                   | 17        | 8.81%   |
| AMD GX                  | 15        | 7.77%   |
| Intel Core i3           | 9         | 4.66%   |
| AMD Ryzen 7             | 4         | 2.07%   |
| Intel Xeon Silver       | 3         | 1.55%   |
| Intel Pentium           | 3         | 1.55%   |
| Intel Core 2 Duo        | 3         | 1.55%   |
| Intel Atom              | 3         | 1.55%   |
| Intel Core 2 Quad       | 2         | 1.04%   |
| AMD Ryzen 9             | 2         | 1.04%   |
| Intel Pentium Silver    | 1         | 0.52%   |
| Intel Pentium Dual-Core | 1         | 0.52%   |
| Intel Core m3           | 1         | 0.52%   |
| Intel Core 2            | 1         | 0.52%   |
| AMD Ryzen Threadripper  | 1         | 0.52%   |
| AMD Ryzen Embedded      | 1         | 0.52%   |
| AMD Ryzen 7 PRO         | 1         | 0.52%   |
| AMD Ryzen 5 PRO         | 1         | 0.52%   |
| AMD Ryzen 5             | 1         | 0.52%   |
| AMD G                   | 1         | 0.52%   |
| AMD FX                  | 1         | 0.52%   |
| AMD Athlon 64 X2        | 1         | 0.52%   |
| AMD Athlon              | 1         | 0.52%   |
| AMD A4                  | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 110       | 56.99%  |
| 2       | 48        | 24.87%  |
| 16      | 7         | 3.63%   |
| 8       | 7         | 3.63%   |
| 6       | 7         | 3.63%   |
| Unknown | 7         | 3.63%   |
| 24      | 5         | 2.59%   |
| 12      | 1         | 0.52%   |
| 10      | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 181       | 94.76%  |
| 2       | 7         | 3.66%   |
| Unknown | 3         | 1.57%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 106       | 54.92%  |
| 2       | 80        | 41.45%  |
| Unknown | 7         | 3.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 26        | 13.47%  |
| Skylake       | 23        | 11.92%  |
| Unknown       | 18        | 9.33%   |
| KabyLake      | 15        | 7.77%   |
| Silvermont    | 13        | 6.74%   |
| SandyBridge   | 13        | 6.74%   |
| Puma          | 13        | 6.74%   |
| IvyBridge     | 8         | 4.15%   |
| Westmere      | 7         | 3.63%   |
| Penryn        | 7         | 3.63%   |
| Broadwell     | 7         | 3.63%   |
| Nehalem       | 6         | 3.11%   |
| Zen           | 5         | 2.59%   |
| Steamroller   | 4         | 2.07%   |
| Goldmont plus | 4         | 2.07%   |
| Core          | 4         | 2.07%   |
| Zen 2         | 3         | 1.55%   |
| Jaguar        | 3         | 1.55%   |
| IceLake       | 3         | 1.55%   |
| TigerLake     | 2         | 1.04%   |
| Piledriver    | 2         | 1.04%   |
| Zen+          | 1         | 0.52%   |
| Zen 3         | 1         | 0.52%   |
| K8 Hammer     | 1         | 0.52%   |
| Goldmont      | 1         | 0.52%   |
| Excavator     | 1         | 0.52%   |
| CometLake     | 1         | 0.52%   |
| Bobcat        | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 111       | 60.66%  |
| Nvidia                     | 23        | 12.57%  |
| AMD                        | 23        | 12.57%  |
| Matrox Electronics Systems | 18        | 9.84%   |
| ASPEED Technology          | 8         | 4.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 5.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 4.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 4.32%   |
| Intel JasperLake [UHD Graphics]                                                          | 8         | 4.32%   |
| Intel HD Graphics 530                                                                    | 8         | 4.32%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 8         | 4.32%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 6         | 3.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 3.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 2.7%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 2.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 2.16%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.16%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 4         | 2.16%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 2.16%   |
| Matrox Electronics Systems MGA G200EH                                                    | 3         | 1.62%   |
| Matrox Electronics Systems G200eR2                                                       | 3         | 1.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.62%   |
| Intel HD Graphics 620                                                                    | 3         | 1.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.62%   |
| AMD ES1000                                                                               | 3         | 1.62%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 2         | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.08%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 2         | 1.08%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 1.08%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 2         | 1.08%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2         | 1.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.08%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 1.08%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 2         | 1.08%   |
| Intel HD Graphics 630                                                                    | 2         | 1.08%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.08%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.54%   |
| Nvidia GT218 [NVS 300]                                                                   | 1         | 0.54%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.54%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.54%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 101       | 52.33%  |
| 1 x AMD         | 21        | 10.88%  |
| 1 x Nvidia      | 18        | 9.33%   |
| 1 x Matrox      | 18        | 9.33%   |
| Other           | 17        | 8.81%   |
| 1 x ASPEED      | 6         | 3.11%   |
| Intel + Nvidia  | 4         | 2.07%   |
| 2 x Intel       | 3         | 1.55%   |
| Intel + AMD     | 2         | 1.04%   |
| 2 x AMD         | 1         | 0.52%   |
| Nvidia + ASPEED | 1         | 0.52%   |
| Intel + ASPEED  | 1         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 158       | 82.29%  |
| Unknown     | 21        | 10.94%  |
| Proprietary | 13        | 6.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 174       | 91.1%   |
| 1.01-2.0   | 6         | 3.14%   |
| 5.01-6.0   | 3         | 1.57%   |
| 0.51-1.0   | 3         | 1.57%   |
| 7.01-8.0   | 2         | 1.05%   |
| 3.01-4.0   | 2         | 1.05%   |
| 8.01-16.0  | 1         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 8         | 14.29%  |
| LG Display              | 8         | 14.29%  |
| Hewlett-Packard         | 6         | 10.71%  |
| Chimei Innolux          | 6         | 10.71%  |
| Philips                 | 4         | 7.14%   |
| Dell                    | 4         | 7.14%   |
| AU Optronics            | 3         | 5.36%   |
| LG Electronics          | 2         | 3.57%   |
| Iiyama                  | 2         | 3.57%   |
| AOC                     | 2         | 3.57%   |
| Ancor Communications    | 2         | 3.57%   |
| Panasonic               | 1         | 1.79%   |
| Lenovo Group Limited    | 1         | 1.79%   |
| Lenovo                  | 1         | 1.79%   |
| InfoVision              | 1         | 1.79%   |
| Goldstar                | 1         | 1.79%   |
| Gigabyte Technology     | 1         | 1.79%   |
| Chi Mei Optoelectronics | 1         | 1.79%   |
| BOE                     | 1         | 1.79%   |
| Acer                    | 1         | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch    | 2         | 3.33%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch             | 2         | 3.33%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch         | 2         | 3.33%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                | 2         | 3.33%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                     | 2         | 3.33%   |
| AOC 2350 AOC2350 1920x1080 510x290mm 23.1-inch                       | 2         | 3.33%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch | 1         | 1.67%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch    | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SyncMaster                           | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SE790C 3440x1440                     | 1         | 1.67%   |
| Samsung Electronics LCD Monitor S23E650 3840x1080                    | 1         | 1.67%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 1         | 1.67%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 710x400mm 32.1-inch            | 1         | 1.67%   |
| Philips PHL 221B6Q PHL08DF 1920x1080 480x270mm 21.7-inch             | 1         | 1.67%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch          | 1         | 1.67%   |
| LG Electronics LCD Monitor LX20D 1600x1200                           | 1         | 1.67%   |
| LG Electronics LCD Monitor LG HDR WQHD+ 3840x1600                    | 1         | 1.67%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch         | 1         | 1.67%   |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch         | 1         | 1.67%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch         | 1         | 1.67%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch          | 1         | 1.67%   |
| LG Display LCD Monitor LGD027B 1600x900 380x210mm 17.1-inch          | 1         | 1.67%   |
| LG Display LCD Monitor LGD0213 1600x900 310x170mm 13.9-inch          | 1         | 1.67%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 1         | 1.67%   |
| Lenovo Group Limited LCD Monitor 1920x1080                           | 1         | 1.67%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch          | 1         | 1.67%   |
| Iiyama PL2888UH IVM7104 3840x2160 620x340mm 27.8-inch                | 1         | 1.67%   |
| Hewlett-Packard Z27n G2 HPN348A 2560x1440 600x340mm 27.2-inch        | 1         | 1.67%   |
| Hewlett-Packard w2216 HWP280C 1680x1050 470x290mm 21.7-inch          | 1         | 1.67%   |
| Hewlett-Packard LCD Monitor Z24n 1920x1200                           | 1         | 1.67%   |
| Hewlett-Packard LCD Monitor E241i 1920x1200                          | 1         | 1.67%   |
| Hewlett-Packard L2335 HWP2615 1920x1200 500x310mm 23.2-inch          | 1         | 1.67%   |
| Hewlett-Packard E243i HPN3463 1920x1200 520x320mm 24.0-inch          | 1         | 1.67%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch           | 1         | 1.67%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                | 1         | 1.67%   |
| Gigabyte Technology M28U GBT2800 3840x2160 630x360mm 28.6-inch       | 1         | 1.67%   |
| Dell UP2715K DEL40B8 3840x2160 600x340mm 27.2-inch                   | 1         | 1.67%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                    | 1         | 1.67%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                    | 1         | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 15        | 26.79%  |
| 3840x2160 (4K)     | 8         | 14.29%  |
| 1920x1200 (WUXGA)  | 6         | 10.71%  |
| 1366x768 (WXGA)    | 6         | 10.71%  |
| 2560x1440 (QHD)    | 4         | 7.14%   |
| 1600x900 (HD+)     | 4         | 7.14%   |
| 3840x1080          | 2         | 3.57%   |
| 3440x1440          | 2         | 3.57%   |
| 2736x1824          | 2         | 3.57%   |
| Unknown            | 2         | 3.57%   |
| 3840x1600          | 1         | 1.79%   |
| 1920x1280          | 1         | 1.79%   |
| 1680x1050 (WSXGA+) | 1         | 1.79%   |
| 1600x1200          | 1         | 1.79%   |
| 1440x900 (WXGA+)   | 1         | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 8         | 15.38%  |
| Unknown | 8         | 15.38%  |
| 27      | 6         | 11.54%  |
| 13      | 5         | 9.62%   |
| 24      | 4         | 7.69%   |
| 23      | 4         | 7.69%   |
| 21      | 4         | 7.69%   |
| 17      | 3         | 5.77%   |
| 12      | 3         | 5.77%   |
| 14      | 2         | 3.85%   |
| 34      | 1         | 1.92%   |
| 32      | 1         | 1.92%   |
| 28      | 1         | 1.92%   |
| 11      | 1         | 1.92%   |
| 10      | 1         | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 12        | 23.08%  |
| 301-350     | 11        | 21.15%  |
| 201-300     | 9         | 17.31%  |
| Unknown     | 8         | 15.38%  |
| 401-500     | 4         | 7.69%   |
| 601-700     | 3         | 5.77%   |
| 351-400     | 3         | 5.77%   |
| 701-800     | 2         | 3.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 30        | 62.5%   |
| Unknown | 8         | 16.67%  |
| 16/10   | 6         | 12.5%   |
| 3/2     | 3         | 6.25%   |
| 21/9    | 1         | 2.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 8         | 15.69%  |
| 91-100         | 8         | 15.69%  |
| Unknown        | 8         | 15.69%  |
| 301-350        | 6         | 11.76%  |
| 81-90          | 5         | 9.8%    |
| 61-70          | 3         | 5.88%   |
| 351-500        | 3         | 5.88%   |
| 251-300        | 3         | 5.88%   |
| 121-130        | 3         | 5.88%   |
| 71-80          | 2         | 3.92%   |
| 51-60          | 2         | 3.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 13        | 24.53%  |
| 101-120       | 11        | 20.75%  |
| 51-100        | 9         | 16.98%  |
| Unknown       | 8         | 15.09%  |
| 161-240       | 6         | 11.32%  |
| More than 240 | 4         | 7.55%   |
| 1-50          | 2         | 3.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 141       | 72.68%  |
| 1     | 43        | 22.16%  |
| 2     | 9         | 4.64%   |
| 3     | 1         | 0.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 151       | 58.08%  |
| Realtek Semiconductor    | 52        | 20%     |
| Broadcom                 | 26        | 10%     |
| Qualcomm Atheros         | 10        | 3.85%   |
| TP-Link                  | 2         | 0.77%   |
| Ralink Technology        | 2         | 0.77%   |
| Sierra Wireless          | 1         | 0.38%   |
| Senao                    | 1         | 0.38%   |
| NetXen Incorporated      | 1         | 0.38%   |
| Microsoft                | 1         | 0.38%   |
| Mellanox Technologies    | 1         | 0.38%   |
| MediaTek                 | 1         | 0.38%   |
| Marvell Technology Group | 1         | 0.38%   |
| JMicron Technology       | 1         | 0.38%   |
| IMC Networks             | 1         | 0.38%   |
| Hewlett-Packard          | 1         | 0.38%   |
| Google                   | 1         | 0.38%   |
| Edimax Technology        | 1         | 0.38%   |
| D-Link System            | 1         | 0.38%   |
| Chelsio Communications   | 1         | 0.38%   |
| Apple                    | 1         | 0.38%   |
| American Megatrends      | 1         | 0.38%   |
| AMD                      | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 46        | 14.29%  |
| Intel I211 Gigabit Network Connection                                         | 24        | 7.45%   |
| Intel I210 Gigabit Network Connection                                         | 22        | 6.83%   |
| Intel Ethernet Controller I226-V                                              | 14        | 4.35%   |
| Intel 82574L Gigabit Network Connection                                       | 12        | 3.73%   |
| Intel I350 Gigabit Network Connection                                         | 11        | 3.42%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9         | 2.8%    |
| Intel Ethernet Connection I217-LM                                             | 8         | 2.48%   |
| Intel 82580 Gigabit Network Connection                                        | 7         | 2.17%   |
| Intel Wireless 7260                                                           | 6         | 1.86%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6         | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 1.86%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 1.55%   |
| Intel Wireless 8260                                                           | 4         | 1.24%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 1.24%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 1.24%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 1.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 3         | 0.93%   |
| Intel Wi-Fi 6 AX200                                                           | 3         | 0.93%   |
| Intel Ethernet Controller I225-V                                              | 3         | 0.93%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 0.93%   |
| Intel Ethernet Connection I217-V                                              | 3         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 3         | 0.93%   |
| Intel 82576 Gigabit Network Connection                                        | 3         | 0.93%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 3         | 0.93%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 0.93%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 3         | 0.93%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 3         | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 0.62%   |
| Intel Wireless-AC 9260                                                        | 2         | 0.62%   |
| Intel Wireless 7265                                                           | 2         | 0.62%   |
| Intel Wireless 3165                                                           | 2         | 0.62%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 0.62%   |
| Intel Ethernet Connection I218-V                                              | 2         | 0.62%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 0.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 53.73%  |
| Realtek Semiconductor | 8         | 11.94%  |
| Qualcomm Atheros      | 8         | 11.94%  |
| Broadcom              | 7         | 10.45%  |
| TP-Link               | 2         | 2.99%   |
| Ralink Technology     | 2         | 2.99%   |
| Sierra Wireless       | 1         | 1.49%   |
| Senao                 | 1         | 1.49%   |
| IMC Networks          | 1         | 1.49%   |
| Edimax Technology     | 1         | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                             | 6         | 8.82%   |
| Intel Wireless 8260                                             | 4         | 5.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 3         | 4.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 3         | 4.41%   |
| Intel Wi-Fi 6 AX200                                             | 3         | 4.41%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                 | 3         | 4.41%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 3         | 4.41%   |
| Broadcom BCM43228 802.11a/b/g/n                                 | 3         | 4.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2         | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 2         | 2.94%   |
| Intel Wireless-AC 9260                                          | 2         | 2.94%   |
| Intel Wireless 7265                                             | 2         | 2.94%   |
| Intel Wireless 3165                                             | 2         | 2.94%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                 | 2         | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 2         | 2.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 2         | 2.94%   |
| Intel Centrino Advanced-N 6200                                  | 2         | 2.94%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                    | 1         | 1.47%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 1         | 1.47%   |
| Sierra Wireless EM7345 4G LTE                                   | 1         | 1.47%   |
| Senao EUB9801 802.11abgn Wireless Adapter [Ralink RT3572]       | 1         | 1.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 1         | 1.47%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 1         | 1.47%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 1         | 1.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 1         | 1.47%   |
| Ralink RT5370 Wireless Adapter                                  | 1         | 1.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                           | 1         | 1.47%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1         | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 1         | 1.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 1         | 1.47%   |
| Intel Wireless 8265 / 8275                                      | 1         | 1.47%   |
| Intel WiFi Link 5100                                            | 1         | 1.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 1         | 1.47%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 1         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 1         | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 1         | 1.47%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 1         | 1.47%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 1         | 1.47%   |
| Broadcom BCM43224 802.11a/b/g/n                                 | 1         | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 132       | 61.97%  |
| Realtek Semiconductor    | 50        | 23.47%  |
| Broadcom                 | 21        | 9.86%   |
| Qualcomm Atheros         | 2         | 0.94%   |
| Microsoft                | 1         | 0.47%   |
| MediaTek                 | 1         | 0.47%   |
| Marvell Technology Group | 1         | 0.47%   |
| JMicron Technology       | 1         | 0.47%   |
| D-Link System            | 1         | 0.47%   |
| Apple                    | 1         | 0.47%   |
| American Megatrends      | 1         | 0.47%   |
| AMD                      | 1         | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 46        | 18.47%  |
| Intel I211 Gigabit Network Connection                                         | 24        | 9.64%   |
| Intel I210 Gigabit Network Connection                                         | 22        | 8.84%   |
| Intel Ethernet Controller I226-V                                              | 14        | 5.62%   |
| Intel 82574L Gigabit Network Connection                                       | 12        | 4.82%   |
| Intel I350 Gigabit Network Connection                                         | 11        | 4.42%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9         | 3.61%   |
| Intel Ethernet Connection I217-LM                                             | 8         | 3.21%   |
| Intel 82580 Gigabit Network Connection                                        | 7         | 2.81%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6         | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 2.41%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 2.01%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 1.61%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 1.61%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 1.61%   |
| Intel Ethernet Controller I225-V                                              | 3         | 1.2%    |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.2%    |
| Intel Ethernet Connection I217-V                                              | 3         | 1.2%    |
| Intel 82576 Gigabit Network Connection                                        | 3         | 1.2%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 3         | 1.2%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 1.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.8%    |
| Intel Ethernet Connection I218-V                                              | 2         | 0.8%    |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.8%    |
| Intel 82583V Gigabit Network Connection                                       | 2         | 0.8%    |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.8%    |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 0.8%    |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 2         | 0.8%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.4%    |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.4%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.4%    |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                            | 1         | 0.4%    |
| MediaTek USB Ethernet-RNDIS                                                   | 1         | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.4%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 1         | 0.4%    |
| Intel NM10/ICH7 Family LAN Controller                                         | 1         | 0.4%    |
| Intel I210 Gigabit Fiber Network Connection                                   | 1         | 0.4%    |
| Intel Ethernet Controller I226-LM                                             | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 180       | 72.87%  |
| WiFi     | 62        | 25.1%   |
| Unknown  | 5         | 2.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 169       | 86.22%  |
| WiFi     | 27        | 13.78%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 63        | 32.14%  |
| 4     | 40        | 20.41%  |
| 3     | 28        | 14.29%  |
| 1     | 27        | 13.78%  |
| 6     | 16        | 8.16%   |
| 5     | 10        | 5.1%    |
| 7     | 5         | 2.55%   |
| 8     | 4         | 2.04%   |
| 13    | 1         | 0.51%   |
| 9     | 1         | 0.51%   |
| 0     | 1         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 179       | 91.79%  |
| Yes  | 16        | 8.21%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 25        | 56.82%  |
| Cambridge Silicon Radio | 4         | 9.09%   |
| Apple                   | 4         | 9.09%   |
| Broadcom                | 3         | 6.82%   |
| IMC Networks            | 2         | 4.55%   |
| Hewlett-Packard         | 2         | 4.55%   |
| Dell                    | 2         | 4.55%   |
| Realtek Semiconductor   | 1         | 2.27%   |
| Lite-On Technology      | 1         | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 12        | 27.27%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 4         | 9.09%   |
| Intel Wireless-AC 3168 Bluetooth                        | 3         | 6.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 3         | 6.82%   |
| Apple Bluetooth Host Controller                         | 3         | 6.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 2         | 4.55%   |
| Intel AX201 Bluetooth                                   | 2         | 4.55%   |
| Intel AX200 Bluetooth                                   | 2         | 4.55%   |
| Broadcom BCM2045B (BDC-2.1)                             | 2         | 4.55%   |
| Realtek Bluetooth Adapter                               | 1         | 2.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1         | 2.27%   |
| Intel AX210 Bluetooth                                   | 1         | 2.27%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip    | 1         | 2.27%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS | 1         | 2.27%   |
| HP Broadcom 2070 Bluetooth Combo                        | 1         | 2.27%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter              | 1         | 2.27%   |
| Dell Wireless 355C Bluetooth 2.0 + EDR module           | 1         | 2.27%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module             | 1         | 2.27%   |
| Broadcom Bluetooth 4.0 Adapter                          | 1         | 2.27%   |
| Apple Broadcom Built-in Bluetooth                       | 1         | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 108       | 67.08%  |
| AMD                      | 25        | 15.53%  |
| Nvidia                   | 20        | 12.42%  |
| Realtek Semiconductor    | 1         | 0.62%   |
| Philips (or NXP)         | 1         | 0.62%   |
| Nordic Semiconductor ASA | 1         | 0.62%   |
| Lenovo                   | 1         | 0.62%   |
| Hewlett-Packard          | 1         | 0.62%   |
| GN Netcom                | 1         | 0.62%   |
| Generalplus Technology   | 1         | 0.62%   |
| BEHRINGER International  | 1         | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 5.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 5.18%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 5.18%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 4.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 4.66%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 4.66%   |
| Intel Jasper Lake HD Audio                                                                        | 8         | 4.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 4.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 4.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 2.59%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.59%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 2.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.07%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 4         | 2.07%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 2.07%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.55%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.55%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.55%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.55%   |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 3         | 1.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 1.55%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.55%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.55%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.04%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.04%   |
| Realtek Semiconductor Microphone(Attila) Microphone(Attila) Microphone(Attila)                    | 1         | 0.52%   |
| Philips (or NXP) Philips SHG7980                                                                  | 1         | 0.52%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.52%   |
| Nvidia MCP65 High Definition Audio                                                                | 1         | 0.52%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 17.71%  |
| SK hynix            | 26        | 13.54%  |
| Unknown             | 23        | 11.98%  |
| Corsair             | 23        | 11.98%  |
| Kingston            | 22        | 11.46%  |
| Micron Technology   | 19        | 9.9%    |
| Crucial             | 11        | 5.73%   |
| G.Skill             | 6         | 3.13%   |
| Kimtigo             | 4         | 2.08%   |
| Unknown             | 4         | 2.08%   |
| Ramaxel Technology  | 3         | 1.56%   |
| Hewlett-Packard     | 3         | 1.56%   |
| Elpida              | 3         | 1.56%   |
| Transcend           | 2         | 1.04%   |
| HPE                 | 2         | 1.04%   |
| Toshiba             | 1         | 0.52%   |
| Tigo                | 1         | 0.52%   |
| Smart Modular       | 1         | 0.52%   |
| Mushkin             | 1         | 0.52%   |
| GSkill              | 1         | 0.52%   |
| ASint Technology    | 1         | 0.52%   |
| Apacer              | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 10        | 4.85%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s          | 4         | 1.94%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s     | 4         | 1.94%   |
| Unknown                                                 | 4         | 1.94%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s  | 3         | 1.46%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 3         | 1.46%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s              | 2         | 0.97%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 0.97%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s    | 2         | 0.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 2         | 0.97%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 0.97%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s               | 2         | 0.97%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 0.97%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s   | 2         | 0.97%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 2         | 0.97%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s   | 2         | 0.97%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s | 2         | 0.97%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                | 2         | 0.97%   |
| Kingston RAM 9965525-116.A00LF 8GB DIMM DDR3 1600MT/s   | 2         | 0.97%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s | 2         | 0.97%   |
| Corsair RAM CMSO4GX3M1C1600C11 4GB DIMM DDR3 1600MT/s   | 2         | 0.97%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s               | 1         | 0.49%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 4096MB DIMM DDR3 1332MT/s            | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3                      | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s               | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR3 1332MT/s            | 1         | 0.49%   |
| Unknown RAM Module 1GB DIMM SDRAM                       | 1         | 0.49%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                | 1         | 0.49%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                | 1         | 0.49%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s              | 1         | 0.49%   |
| Unknown RAM Module 1024MB DIMM DDR3 1332MT/s            | 1         | 0.49%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s     | 1         | 0.49%   |
| Transcend RAM Module 2GB SODIMM DDR3 1067MT/s           | 1         | 0.49%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s    | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 92        | 52.57%  |
| DDR4    | 62        | 35.43%  |
| DDR2    | 7         | 4%      |
| DDR5    | 5         | 2.86%   |
| Unknown | 4         | 2.29%   |
| SDRAM   | 2         | 1.14%   |
| LPDDR3  | 2         | 1.14%   |
| DRAM    | 1         | 0.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 94        | 53.41%  |
| SODIMM       | 77        | 43.75%  |
| Row Of Chips | 2         | 1.14%   |
| FB-DIMM      | 2         | 1.14%   |
| Chip         | 1         | 0.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 70        | 37.43%  |
| 8192  | 62        | 33.16%  |
| 16384 | 25        | 13.37%  |
| 2048  | 18        | 9.63%   |
| 1024  | 8         | 4.28%   |
| 32768 | 4         | 2.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 51        | 28.33%  |
| 1333    | 36        | 20%     |
| 3200    | 17        | 9.44%   |
| 2133    | 16        | 8.89%   |
| 2667    | 13        | 7.22%   |
| 2400    | 12        | 6.67%   |
| 800     | 6         | 3.33%   |
| 667     | 6         | 3.33%   |
| 4800    | 5         | 2.78%   |
| 2666    | 5         | 2.78%   |
| Unknown | 4         | 2.22%   |
| 1334    | 2         | 1.11%   |
| 4400    | 1         | 0.56%   |
| 2933    | 1         | 0.56%   |
| 1867    | 1         | 0.56%   |
| 1866    | 1         | 0.56%   |
| 1332    | 1         | 0.56%   |
| 1067    | 1         | 0.56%   |
| 333     | 1         | 0.56%   |

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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 9         | 34.62%  |
| Bison Electronics     | 5         | 19.23%  |
| Microdia              | 3         | 11.54%  |
| Realtek Semiconductor | 2         | 7.69%   |
| IMC Networks          | 2         | 7.69%   |
| Syntek                | 1         | 3.85%   |
| Suyin                 | 1         | 3.85%   |
| Quanta                | 1         | 3.85%   |
| Logitech              | 1         | 3.85%   |
| Lenovo                | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Bison Integrated Camera                  | 4         | 15.38%  |
| Microdia Integrated Webcam               | 2         | 7.69%   |
| Syntek EasyCamera                        | 1         | 3.85%   |
| Suyin Asus Integrated Webcam             | 1         | 3.85%   |
| Realtek Integrated_Webcam_HD             | 1         | 3.85%   |
| Realtek Front Camera                     | 1         | 3.85%   |
| Quanta VGA WebCam                        | 1         | 3.85%   |
| Microdia USB 2.0 Camera                  | 1         | 3.85%   |
| Logitech Webcam C270                     | 1         | 3.85%   |
| Lenovo Integrated Webcam                 | 1         | 3.85%   |
| IMC Networks HP TrueVision HD Camera     | 1         | 3.85%   |
| IMC Networks EasyCamera                  | 1         | 3.85%   |
| Chicony USB2.0 HD UVC WebCam             | 1         | 3.85%   |
| Chicony USB 2.0 VGA UVC WebCam           | 1         | 3.85%   |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 3.85%   |
| Chicony ThinkPad T490 Webcam             | 1         | 3.85%   |
| Chicony Realtek DMFT RGB                 | 1         | 3.85%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 3.85%   |
| Chicony Integrated HP HD Webcam          | 1         | 3.85%   |
| Chicony Integrated Camera                | 1         | 3.85%   |
| Chicony Camera                           | 1         | 3.85%   |
| Bison ThinkPad P50 Integrated Camera     | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 30%     |
| Upek                       | 2         | 20%     |
| AuthenTec                  | 2         | 20%     |
| Synaptics                  | 1         | 10%     |
| Shenzhen Goodix Technology | 1         | 10%     |
| Broadcom                   | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 20%     |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 10%     |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 10%     |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 10%     |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| AuthenTec AES2810                                                            | 1         | 10%     |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 10%     |

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
| 1     | 81        | 41.97%  |
| 0     | 62        | 32.12%  |
| 2     | 36        | 18.65%  |
| 3     | 8         | 4.15%   |
| 4     | 4         | 2.07%   |
| 5     | 2         | 1.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 115       | 68.05%  |
| Net/wireless             | 14        | 8.28%   |
| Bluetooth                | 9         | 5.33%   |
| Fingerprint reader       | 7         | 4.14%   |
| Card reader              | 7         | 4.14%   |
| Firewire controller      | 5         | 2.96%   |
| Sound                    | 4         | 2.37%   |
| Graphics card            | 3         | 1.78%   |
| Storage/ata              | 2         | 1.18%   |
| Network                  | 2         | 1.18%   |
| Net/ethernet             | 1         | 0.59%   |

