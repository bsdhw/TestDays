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

Total: 321

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| ASUSTek       | G11CD                       | Desktop     | [e4d4f0e1b2](https://bsd-hardware.info/?probe=e4d4f0e1b2) | May 06, 2024 |
| Dell          | 0KYJ8C A00                  | Desktop     | [7a7c8ece3a](https://bsd-hardware.info/?probe=7a7c8ece3a) | Apr 27, 2024 |
| Dell          | 0KYJ8C A00                  | Desktop     | [d35fe4f9ef](https://bsd-hardware.info/?probe=d35fe4f9ef) | Apr 27, 2024 |
| Lenovo        | ThinkPad T530 23942U1       | Notebook    | [a3b075c680](https://bsd-hardware.info/?probe=a3b075c680) | Apr 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [3f86c9c69d](https://bsd-hardware.info/?probe=3f86c9c69d) | Apr 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [d5529f00e1](https://bsd-hardware.info/?probe=d5529f00e1) | Apr 18, 2024 |
| HP            | 8299                        | Desktop     | [7b4780009e](https://bsd-hardware.info/?probe=7b4780009e) | Apr 16, 2024 |
| PC Engines    | apu4                        | Desktop     | [5ceaa26e0d](https://bsd-hardware.info/?probe=5ceaa26e0d) | Apr 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [d9b9726d99](https://bsd-hardware.info/?probe=d9b9726d99) | Apr 10, 2024 |
| Supermicro    | A1SRi                       | Mini pc     | [dd90dd1cc2](https://bsd-hardware.info/?probe=dd90dd1cc2) | Apr 02, 2024 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [b3d1f4d1bf](https://bsd-hardware.info/?probe=b3d1f4d1bf) | Apr 02, 2024 |
| Dell          | 0YXT71 A02                  | Desktop     | [e5aceb0ceb](https://bsd-hardware.info/?probe=e5aceb0ceb) | Apr 01, 2024 |
| Dell          | 0YXT71 A02                  | Desktop     | [a8cd5867cb](https://bsd-hardware.info/?probe=a8cd5867cb) | Apr 01, 2024 |
| Fujitsu       | D3034-A1 S26361-D3034-A1... | Server      | [4151984b3a](https://bsd-hardware.info/?probe=4151984b3a) | Mar 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [147401844b](https://bsd-hardware.info/?probe=147401844b) | Mar 29, 2024 |
| Dell          | 0KYJ8C A00                  | Desktop     | [eb72b3e4b7](https://bsd-hardware.info/?probe=eb72b3e4b7) | Mar 27, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [14a9ddb552](https://bsd-hardware.info/?probe=14a9ddb552) | Mar 25, 2024 |
| Unknown       | Unknown                     | Desktop     | [c95a414132](https://bsd-hardware.info/?probe=c95a414132) | Mar 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [dc2553c7cb](https://bsd-hardware.info/?probe=dc2553c7cb) | Mar 07, 2024 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [def2b4e964](https://bsd-hardware.info/?probe=def2b4e964) | Mar 05, 2024 |
| Dell          | Latitude E7250              | Notebook    | [ffc8dcf395](https://bsd-hardware.info/?probe=ffc8dcf395) | Feb 22, 2024 |
| ASRock        | B650 PG Lightning           | Desktop     | [54d6c96d25](https://bsd-hardware.info/?probe=54d6c96d25) | Feb 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [b58cf5585d](https://bsd-hardware.info/?probe=b58cf5585d) | Feb 22, 2024 |
| HP            | 1998                        | Desktop     | [ef11b12f13](https://bsd-hardware.info/?probe=ef11b12f13) | Feb 18, 2024 |
| HP            | 1998                        | Desktop     | [6895f365c7](https://bsd-hardware.info/?probe=6895f365c7) | Feb 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [9c184fe6fa](https://bsd-hardware.info/?probe=9c184fe6fa) | Feb 14, 2024 |
| Dell          | 07WP95 A02                  | Desktop     | [aad51ede2a](https://bsd-hardware.info/?probe=aad51ede2a) | Feb 12, 2024 |
| HP            | 1998                        | Desktop     | [58de92b13d](https://bsd-hardware.info/?probe=58de92b13d) | Feb 11, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [1ea9b4724a](https://bsd-hardware.info/?probe=1ea9b4724a) | Feb 09, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [9778043e6f](https://bsd-hardware.info/?probe=9778043e6f) | Feb 08, 2024 |
| Lenovo        | ThinkPad T480 20L6SDA400    | Notebook    | [4934e88205](https://bsd-hardware.info/?probe=4934e88205) | Feb 07, 2024 |
| PC Engines    | apu4                        | Desktop     | [d0205e7f2b](https://bsd-hardware.info/?probe=d0205e7f2b) | Feb 05, 2024 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [511747dd03](https://bsd-hardware.info/?probe=511747dd03) | Feb 02, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [43d0551feb](https://bsd-hardware.info/?probe=43d0551feb) | Feb 01, 2024 |
| HP            | 8054                        | Desktop     | [4404de3242](https://bsd-hardware.info/?probe=4404de3242) | Jan 31, 2024 |
| Dell          | 0WR7PY A02                  | Desktop     | [f0eb82f1f3](https://bsd-hardware.info/?probe=f0eb82f1f3) | Jan 31, 2024 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [a2d3483ef9](https://bsd-hardware.info/?probe=a2d3483ef9) | Jan 30, 2024 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [294a66e260](https://bsd-hardware.info/?probe=294a66e260) | Jan 29, 2024 |
| HP            | 8054                        | Desktop     | [5878ff14cf](https://bsd-hardware.info/?probe=5878ff14cf) | Jan 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [9d002ec65c](https://bsd-hardware.info/?probe=9d002ec65c) | Jan 25, 2024 |
| Dell          | 07WP95 A02                  | Desktop     | [76cdddf230](https://bsd-hardware.info/?probe=76cdddf230) | Jan 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [a56d0b3643](https://bsd-hardware.info/?probe=a56d0b3643) | Jan 20, 2024 |
| Star Labs     | StarBook                    | Notebook    | [1e903acb93](https://bsd-hardware.info/?probe=1e903acb93) | Jan 16, 2024 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [2e9333aba4](https://bsd-hardware.info/?probe=2e9333aba4) | Jan 11, 2024 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [68531d8f73](https://bsd-hardware.info/?probe=68531d8f73) | Jan 03, 2024 |
| Unknown       | Unknown                     | Desktop     | [1032d282eb](https://bsd-hardware.info/?probe=1032d282eb) | Jan 03, 2024 |
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
| OPNsense 21.1     | 11        | 4.14%   |
| OPNsense 22.7.10  | 9         | 3.38%   |
| OPNsense 24.1.4   | 6         | 2.26%   |
| OPNsense 23.7.9   | 6         | 2.26%   |
| OPNsense 23.7.10  | 6         | 2.26%   |
| OPNsense 21.7.7   | 6         | 2.26%   |
| OPNsense 21.1.3   | 6         | 2.26%   |
| OpenBSD 6.8       | 6         | 2.26%   |
| OPNsense 24.1.1   | 5         | 1.88%   |
| OPNsense 24.1     | 5         | 1.88%   |
| OPNsense 23.1.11  | 5         | 1.88%   |
| OPNsense 21.1.5   | 5         | 1.88%   |
| OPNsense 21.1.2   | 5         | 1.88%   |
| OpenBSD 7.0       | 5         | 1.88%   |
| helloSystem 0.5.0 | 5         | 1.88%   |
| OPNsense 23.7.7   | 4         | 1.5%    |
| OPNsense 23.7.12  | 4         | 1.5%    |
| OPNsense 22.7.8   | 4         | 1.5%    |
| OPNsense 21.1.8   | 4         | 1.5%    |
| OPNsense 24.1.5   | 3         | 1.13%   |
| OPNsense 23.7.6   | 3         | 1.13%   |
| OPNsense 23.7.5   | 3         | 1.13%   |
| OPNsense 23.7.4   | 3         | 1.13%   |
| OPNsense 23.7.1   | 3         | 1.13%   |
| OPNsense 23.1.6   | 3         | 1.13%   |
| OPNsense 23.1.3   | 3         | 1.13%   |
| OPNsense 23.1.10  | 3         | 1.13%   |
| OPNsense 22.7.9   | 3         | 1.13%   |
| OPNsense 22.7.2   | 3         | 1.13%   |
| OPNsense 22.1.8   | 3         | 1.13%   |
| OPNsense 21.7.3   | 3         | 1.13%   |
| OPNsense 21.7.1   | 3         | 1.13%   |
| OPNsense 20.7.8   | 3         | 1.13%   |
| OpenBSD 6.9       | 3         | 1.13%   |
| helloSystem 0.8.1 | 3         | 1.13%   |
| helloSystem 0.8.0 | 3         | 1.13%   |
| helloSystem 0.7.0 | 3         | 1.13%   |
| FreeBSD 13.1-p5   | 3         | 1.13%   |
| FreeBSD 13.0-p7   | 3         | 1.13%   |
| FreeBSD 12.1-p8   | 3         | 1.13%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 144       | 65.45%  |
| FreeBSD     | 36        | 16.36%  |
| helloSystem | 17        | 7.73%   |
| OpenBSD     | 16        | 7.27%   |
| GhostBSD    | 4         | 1.82%   |
| pfSense     | 1         | 0.45%   |
| NomadBSD    | 1         | 0.45%   |
| FuryBSD     | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 219       | 99.55%  |
| octeon | 1         | 0.45%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 160       | 72.07%  |
| helloDesktop | 18        | 8.11%   |
| KDE5         | 14        | 6.31%   |
| fvwm         | 12        | 5.41%   |
| MATE         | 5         | 2.25%   |
| GNOME        | 3         | 1.35%   |
| XFCE         | 2         | 0.9%    |
| i3           | 2         | 0.9%    |
| xfwm         | 1         | 0.45%   |
| TWM          | 1         | 0.45%   |
| Openbox      | 1         | 0.45%   |
| Mutter       | 1         | 0.45%   |
| LXQt         | 1         | 0.45%   |
| AwesomeWM    | 1         | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 161       | 73.18%  |
| X11     | 59        | 26.82%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 174       | 78.03%  |
| SLiM    | 18        | 8.07%   |
| SDDM    | 14        | 6.28%   |
| LightDM | 9         | 4.04%   |
| GDM     | 5         | 2.24%   |
| XDM     | 3         | 1.35%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 161       | 72.2%   |
| en_US          | 27        | 12.11%  |
| C              | 24        | 10.76%  |
| sv_SE          | 5         | 2.24%   |
| sv_SE.US-ASCII | 1         | 0.45%   |
| sv             | 1         | 0.45%   |
| en_GB          | 1         | 0.45%   |
| en_CA          | 1         | 0.45%   |
| en_BE          | 1         | 0.45%   |
| en             | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 193       | 86.94%  |
| BIOS | 29        | 13.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 108       | 48.65%  |
| Zfs    | 91        | 40.99%  |
| Ffs    | 16        | 7.21%   |
| Cd9660 | 7         | 3.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 204       | 91.48%  |
| MBR     | 16        | 7.17%   |
| Unknown | 3         | 1.35%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 27        | 12.27%  |
| Hewlett-Packard            | 23        | 10.45%  |
| Lenovo                     | 22        | 10%     |
| Unknown                    | 22        | 10%     |
| ASUSTek Computer           | 20        | 9.09%   |
| PC Engines                 | 15        | 6.82%   |
| Intel                      | 11        | 5%      |
| Supermicro                 | 9         | 4.09%   |
| Gigabyte Technology        | 9         | 4.09%   |
| AMI                        | 8         | 3.64%   |
| MSI                        | 7         | 3.18%   |
| Fujitsu                    | 4         | 1.82%   |
| CWWK                       | 4         | 1.82%   |
| ASRock                     | 4         | 1.82%   |
| Techvision                 | 3         | 1.36%   |
| Microsoft                  | 3         | 1.36%   |
| Apple                      | 3         | 1.36%   |
| Toshiba                    | 2         | 0.91%   |
| Star Labs                  | 2         | 0.91%   |
| Shuttle                    | 2         | 0.91%   |
| HPE                        | 2         | 0.91%   |
| Deciso                     | 2         | 0.91%   |
| ZOTAC                      | 1         | 0.45%   |
| Wistron                    | 1         | 0.45%   |
| Sony                       | 1         | 0.45%   |
| ShenZhen MinWin Technology | 1         | 0.45%   |
| Razer                      | 1         | 0.45%   |
| Protectli                  | 1         | 0.45%   |
| Google                     | 1         | 0.45%   |
| Fujitsu Siemens            | 1         | 0.45%   |
| DFI                        | 1         | 0.45%   |
| CompuLab                   | 1         | 0.45%   |
| Cisco                      | 1         | 0.45%   |
| AZW                        | 1         | 0.45%   |
| AOpen                      | 1         | 0.45%   |
| ADI                        | 1         | 0.45%   |
| ACMA                       | 1         | 0.45%   |
| Acer                       | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 23        | 10.45%  |
| PC Engines APU2                   | 7         | 3.18%   |
| AMI Aptio CRB                     | 6         | 2.73%   |
| PC Engines apu4                   | 4         | 1.82%   |
| HP t730 Thin Client               | 4         | 1.82%   |
| Techvision TVI7309X               | 3         | 1.36%   |
| Supermicro Super Server           | 3         | 1.36%   |
| Intel CRESCENTBAY                 | 3         | 1.36%   |
| HP EliteDesk 800 G2 SFF           | 3         | 1.36%   |
| ASUS All Series                   | 3         | 1.36%   |
| Supermicro X10SLL-F               | 2         | 0.91%   |
| Supermicro A1SAi                  | 2         | 0.91%   |
| Star Labs StarBook                | 2         | 0.91%   |
| PC Engines APU3                   | 2         | 0.91%   |
| Microsoft Surface Pro 7           | 2         | 0.91%   |
| Intel Q3XXG4-P V1.0               | 2         | 0.91%   |
| Intel D54250WYK H13922-303        | 2         | 0.91%   |
| HP EliteDesk 800 G1 SFF           | 2         | 0.91%   |
| Dell PowerEdge R210 II            | 2         | 0.91%   |
| Dell PowerEdge R210               | 2         | 0.91%   |
| Dell OptiPlex 9020                | 2         | 0.91%   |
| Dell OptiPlex 7060                | 2         | 0.91%   |
| Dell OptiPlex 7010                | 2         | 0.91%   |
| CWWK CW-AD4L-N V1                 | 2         | 0.91%   |
| ZOTAC ZBOX-CI329NANO              | 1         | 0.45%   |
| Wistron ProLiant ML110 G6         | 1         | 0.45%   |
| Toshiba TECRA Z40-C-12Z           | 1         | 0.45%   |
| Toshiba Satellite L450            | 1         | 0.45%   |
| Supermicro X10SLH-N6-ST031        | 1         | 0.45%   |
| Supermicro SYS-1019S-MP           | 1         | 0.45%   |
| Sony SVP1322M1EBI                 | 1         | 0.45%   |
| Shuttle SH570                     | 1         | 0.45%   |
| Shuttle DH170                     | 1         | 0.45%   |
| ShenZhen MinWin MW-NANO-APL-4L    | 1         | 0.45%   |
| Razer Blade 14 (2022) - RZ09-0427 | 1         | 0.45%   |
| Protectli FW4B                    | 1         | 0.45%   |
| PC Engines apu6                   | 1         | 0.45%   |
| PC Engines APU                    | 1         | 0.45%   |
| MSI WC776AA-UUW HPE-110sc         | 1         | 0.45%   |
| MSI MS-7C56                       | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 23        | 10.45%  |
| Lenovo ThinkPad                | 11        | 5%      |
| Dell PowerEdge                 | 11        | 5%      |
| Dell OptiPlex                  | 11        | 5%      |
| PC Engines APU2                | 7         | 3.18%   |
| HP EliteDesk                   | 7         | 3.18%   |
| AMI Aptio                      | 6         | 2.73%   |
| Lenovo ThinkCentre             | 5         | 2.27%   |
| HP ProLiant                    | 5         | 2.27%   |
| PC Engines apu4                | 4         | 1.82%   |
| HP t730                        | 4         | 1.82%   |
| Dell Latitude                  | 4         | 1.82%   |
| Techvision TVI7309X            | 3         | 1.36%   |
| Supermicro Super               | 3         | 1.36%   |
| Microsoft Surface              | 3         | 1.36%   |
| Intel CRESCENTBAY              | 3         | 1.36%   |
| ASUS All                       | 3         | 1.36%   |
| Supermicro X10SLL-F            | 2         | 0.91%   |
| Supermicro A1SAi               | 2         | 0.91%   |
| Star Labs StarBook             | 2         | 0.91%   |
| PC Engines APU3                | 2         | 0.91%   |
| Lenovo IdeaPad                 | 2         | 0.91%   |
| Intel Q3XXG4-P                 | 2         | 0.91%   |
| Intel D54250WYK                | 2         | 0.91%   |
| HPE ProLiant                   | 2         | 0.91%   |
| Fujitsu ESPRIMO                | 2         | 0.91%   |
| CWWK CW-AD4L-N                 | 2         | 0.91%   |
| ASUS ROG                       | 2         | 0.91%   |
| ZOTAC ZBOX-CI329NANO           | 1         | 0.45%   |
| Wistron ProLiant               | 1         | 0.45%   |
| Toshiba TECRA                  | 1         | 0.45%   |
| Toshiba Satellite              | 1         | 0.45%   |
| Supermicro X10SLH-N6-ST031     | 1         | 0.45%   |
| Supermicro SYS-1019S-MP        | 1         | 0.45%   |
| Sony SVP1322M1EBI              | 1         | 0.45%   |
| Shuttle SH570                  | 1         | 0.45%   |
| Shuttle DH170                  | 1         | 0.45%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.45%   |
| Razer Blade                    | 1         | 0.45%   |
| Protectli FW4B                 | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2016    | 25        | 11.36%  |
| 2020    | 20        | 9.09%   |
| 2014    | 19        | 8.64%   |
| 2018    | 18        | 8.18%   |
| 2023    | 17        | 7.73%   |
| 2022    | 17        | 7.73%   |
| 2017    | 17        | 7.73%   |
| 2019    | 16        | 7.27%   |
| 2015    | 15        | 6.82%   |
| 2021    | 12        | 5.45%   |
| 2010    | 11        | 5%      |
| 2012    | 10        | 4.55%   |
| 2013    | 9         | 4.09%   |
| 2009    | 6         | 2.73%   |
| 2011    | 4         | 1.82%   |
| 2008    | 1         | 0.45%   |
| 2007    | 1         | 0.45%   |
| 2006    | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 139       | 63.18%  |
| Notebook   | 39        | 17.73%  |
| Server     | 23        | 10.45%  |
| Mini pc    | 15        | 6.82%   |
| Tablet     | 3         | 1.36%   |
| All in one | 1         | 0.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 200       | 90.91%  |
| Yes  | 20        | 9.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 82        | 36.77%  |
| 4.01-8.0        | 48        | 21.52%  |
| 16.01-24.0      | 46        | 20.63%  |
| 32.01-64.0      | 22        | 9.87%   |
| 64.01-256.0     | 8         | 3.59%   |
| 24.01-32.0      | 6         | 2.69%   |
| 2.01-3.0        | 5         | 2.24%   |
| More than 256.0 | 3         | 1.35%   |
| 3.01-4.0        | 2         | 0.9%    |
| 1.01-2.0        | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 116       | 51.56%  |
| 0.51-1.0    | 66        | 29.33%  |
| 1.01-2.0    | 26        | 11.56%  |
| 2.01-3.0    | 6         | 2.67%   |
| 4.01-8.0    | 4         | 1.78%   |
| 3.01-4.0    | 2         | 0.89%   |
| 24.01-32.0  | 2         | 0.89%   |
| 64.01-256.0 | 2         | 0.89%   |
| 32.01-64.0  | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 153       | 68.3%   |
| 2      | 24        | 10.71%  |
| 0      | 18        | 8.04%   |
| 3      | 12        | 5.36%   |
| 6      | 4         | 1.79%   |
| 4      | 4         | 1.79%   |
| 11     | 2         | 0.89%   |
| 8      | 2         | 0.89%   |
| 18     | 1         | 0.45%   |
| 12     | 1         | 0.45%   |
| 10     | 1         | 0.45%   |
| 9      | 1         | 0.45%   |
| 5      | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 186       | 84.16%  |
| Yes       | 35        | 15.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 207       | 94.09%  |
| No        | 13        | 5.91%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 153       | 69.23%  |
| Yes       | 68        | 30.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 171       | 77.38%  |
| Yes       | 50        | 22.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Sweden  | 220       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Stockholm             | 36        | 14.63%  |
| Malmo                 | 13        | 5.28%   |
| Gothenburg            | 11        | 4.47%   |
| Västerås            | 6         | 2.44%   |
| Bromma                | 6         | 2.44%   |
| LinkГ¶ping          | 5         | 2.03%   |
| VÃ¤sterÃ¥s        | 4         | 1.63%   |
| UmeГҐ               | 4         | 1.63%   |
| Umeå                 | 4         | 1.63%   |
| Linköping            | 4         | 1.63%   |
| Henan                 | 4         | 1.63%   |
| Uppsala               | 3         | 1.22%   |
| Taby                  | 3         | 1.22%   |
| Sollentuna            | 3         | 1.22%   |
| Skövde               | 3         | 1.22%   |
| Piteå                | 3         | 1.22%   |
| Lund                  | 3         | 1.22%   |
| Karlskrona            | 3         | 1.22%   |
| JГ¶nkГ¶ping       | 3         | 1.22%   |
| Gävle                | 3         | 1.22%   |
| Bandhagen             | 3         | 1.22%   |
| Vallingby             | 2         | 0.81%   |
| Upplands Vasby        | 2         | 0.81%   |
| Tyreso Strand         | 2         | 0.81%   |
| Tumba                 | 2         | 0.81%   |
| Straengnaes           | 2         | 0.81%   |
| Staffanstorp          | 2         | 0.81%   |
| Solna                 | 2         | 0.81%   |
| Solleftea             | 2         | 0.81%   |
| Östersund            | 2         | 0.81%   |
| Örebro               | 2         | 0.81%   |
| Nyköping             | 2         | 0.81%   |
| Landskrona            | 2         | 0.81%   |
| Kungsbacka            | 2         | 0.81%   |
| Jönköping           | 2         | 0.81%   |
| Helsingborg           | 2         | 0.81%   |
| Falkenberg            | 2         | 0.81%   |
| Enskede-Arsta-Vantoer | 2         | 0.81%   |
| Г…hus              | 1         | 0.41%   |
| Г„lvГ¤ngen       | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 47        | 65     | 17.94%  |
| Kingston            | 32        | 43     | 12.21%  |
| Seagate             | 25        | 58     | 9.54%   |
| WDC                 | 23        | 34     | 8.78%   |
| Intel               | 22        | 38     | 8.4%    |
| Hoodisk             | 16        | 25     | 6.11%   |
| SanDisk             | 11        | 14     | 4.2%    |
| Toshiba             | 9         | 19     | 3.44%   |
| Crucial             | 9         | 18     | 3.44%   |
| Phison              | 5         | 5      | 1.91%   |
| NVMe                | 5         | 6      | 1.91%   |
| Transcend           | 4         | 4      | 1.53%   |
| OCZ                 | 4         | 6      | 1.53%   |
| Micron Technology   | 4         | 7      | 1.53%   |
| LITEON              | 4         | 10     | 1.53%   |
| Hewlett-Packard     | 4         | 8      | 1.53%   |
| China               | 4         | 4      | 1.53%   |
| Hitachi             | 3         | 3      | 1.15%   |
| Apple               | 3         | 4      | 1.15%   |
| SK hynix            | 2         | 2      | 0.76%   |
| Innodisk            | 2         | 3      | 0.76%   |
| HPE                 | 2         | 14     | 0.76%   |
| Corsair             | 2         | 2      | 0.76%   |
| Apacer              | 2         | 2      | 0.76%   |
| A-DATA Technology   | 2         | 2      | 0.76%   |
| XrayDisk            | 1         | 1      | 0.38%   |
| TCSUNBOW            | 1         | 1      | 0.38%   |
| Supermicro          | 1         | 1      | 0.38%   |
| Star Drive          | 1         | 1      | 0.38%   |
| Silicon Motion      | 1         | 1      | 0.38%   |
| PNY                 | 1         | 1      | 0.38%   |
| MARVELL             | 1         | 2      | 0.38%   |
| LITEONIT            | 1         | 1      | 0.38%   |
| KingSpec            | 1         | 1      | 0.38%   |
| Kimtigo             | 1         | 1      | 0.38%   |
| HGST                | 1         | 4      | 0.38%   |
| Fordisk             | 1         | 1      | 0.38%   |
| faspeed             | 1         | 1      | 0.38%   |
| Fanxiang            | 1         | 2      | 0.38%   |
| Dogfish             | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB          | 5         | 1.72%   |
| Hoodisk SSD 16GB                     | 5         | 1.72%   |
| SanDisk SDSA6MM-032G-1006 32GB       | 4         | 1.38%   |
| Kingston SA400S37240G 240GB          | 4         | 1.38%   |
| Intel SSDSC2BW240A4 240GB            | 4         | 1.38%   |
| Hoodisk SSD 64GB                     | 4         | 1.38%   |
| Hoodisk SSD 128GB                    | 4         | 1.38%   |
| Samsung SSD 860 QVO 1TB              | 3         | 1.03%   |
| Samsung SSD 860 EVO 250GB            | 3         | 1.03%   |
| Phison YSO128GTLCW-E3C-2 128GB       | 3         | 1.03%   |
| WDC WD5000AZLX-60K2TA0 500GB         | 2         | 0.69%   |
| Toshiba HDWR11A 10TB                 | 2         | 0.69%   |
| Toshiba HDWQ140 4TB                  | 2         | 0.69%   |
| Toshiba DT01ACA100 1TB               | 2         | 0.69%   |
| Seagate ST9320423AS 320GB            | 2         | 0.69%   |
| Seagate ST4000DM004-2CV104 4TB       | 2         | 0.69%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 0.69%   |
| SanDisk SDSSDHP256G 256GB            | 2         | 0.69%   |
| Samsung SSD PM830 2.5-inch 7mm 128GB | 2         | 0.69%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 0.69%   |
| Samsung SSD 970 EVO 500GB            | 2         | 0.69%   |
| Samsung SSD 870 EVO 250GB            | 2         | 0.69%   |
| Samsung SSD 850 EVO 250GB            | 2         | 0.69%   |
| Samsung SSD 850 EVO 1TB              | 2         | 0.69%   |
| Samsung SSD 840 EVO 120GB            | 2         | 0.69%   |
| Samsung HD501LJ 500GB                | 2         | 0.69%   |
| Phison SATA SSD 16GB                 | 2         | 0.69%   |
| OCZ AGILITY3 120GB                   | 2         | 0.69%   |
| NVMe KBG40ZPZ256G TOS 256GB          | 2         | 0.69%   |
| Kingston SV300S37A240G 240GB         | 2         | 0.69%   |
| Kingston SV300S37A120G 120GB         | 2         | 0.69%   |
| Kingston SKC600MS256G 256GB          | 2         | 0.69%   |
| Kingston SKC600512G 512GB            | 2         | 0.69%   |
| Kingston SA2000M8250G 250GB          | 2         | 0.69%   |
| Intel SSDSC2CT120A3 120GB            | 2         | 0.69%   |
| Intel SSDSC2CT060A3 64GB             | 2         | 0.69%   |
| Intel SSDMCEAC030B3 32GB             | 2         | 0.69%   |
| Hoodisk SSD 32GB                     | 2         | 0.69%   |
| HP RAID 1(1+0) 73GB                  | 2         | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 55     | 35.38%  |
| WDC                 | 16        | 25     | 24.62%  |
| Toshiba             | 7         | 16     | 10.77%  |
| Samsung Electronics | 6         | 9      | 9.23%   |
| Hewlett-Packard     | 4         | 8      | 6.15%   |
| NVMe                | 3         | 4      | 4.62%   |
| Hitachi             | 3         | 3      | 4.62%   |
| HPE                 | 1         | 8      | 1.54%   |
| HGST                | 1         | 4      | 1.54%   |
| Apple               | 1         | 1      | 1.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 42     | 19.75%  |
| Kingston            | 29        | 39     | 17.9%   |
| Intel               | 19        | 34     | 11.73%  |
| Hoodisk             | 16        | 25     | 9.88%   |
| SanDisk             | 11        | 14     | 6.79%   |
| Crucial             | 7         | 16     | 4.32%   |
| OCZ                 | 4         | 6      | 2.47%   |
| Micron Technology   | 4         | 7      | 2.47%   |
| LITEON              | 4         | 10     | 2.47%   |
| China               | 4         | 4      | 2.47%   |
| WDC                 | 3         | 5      | 1.85%   |
| Transcend           | 2         | 2      | 1.23%   |
| Toshiba             | 2         | 3      | 1.23%   |
| SK hynix            | 2         | 2      | 1.23%   |
| Phison              | 2         | 2      | 1.23%   |
| NVMe                | 2         | 2      | 1.23%   |
| Innodisk            | 2         | 3      | 1.23%   |
| Apple               | 2         | 3      | 1.23%   |
| Apacer              | 2         | 2      | 1.23%   |
| XrayDisk            | 1         | 1      | 0.62%   |
| TCSUNBOW            | 1         | 1      | 0.62%   |
| Supermicro          | 1         | 1      | 0.62%   |
| Seagate             | 1         | 1      | 0.62%   |
| PNY                 | 1         | 1      | 0.62%   |
| MARVELL             | 1         | 2      | 0.62%   |
| LITEONIT            | 1         | 1      | 0.62%   |
| KingSpec            | 1         | 1      | 0.62%   |
| HPE                 | 1         | 6      | 0.62%   |
| Fordisk             | 1         | 1      | 0.62%   |
| Dogfish             | 1         | 1      | 0.62%   |
| Dell                | 1         | 2      | 0.62%   |
| Corsair             | 1         | 1      | 0.62%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 141       | 241    | 60.78%  |
| HDD  | 52        | 133    | 22.41%  |
| NVMe | 39        | 44     | 16.81%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 173       | 374    | 81.6%   |
| NVMe | 39        | 44     | 18.4%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 154       | 245    | 71.63%  |
| 0.51-1.0   | 32        | 49     | 14.88%  |
| 1.01-2.0   | 12        | 28     | 5.58%   |
| 3.01-4.0   | 10        | 28     | 4.65%   |
| 4.01-10.0  | 7         | 24     | 3.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 98        | 43.75%  |
| 1-20           | 29        | 12.95%  |
| 251-500        | 27        | 12.05%  |
| 21-50          | 25        | 11.16%  |
| 51-100         | 24        | 10.71%  |
| 501-1000       | 14        | 6.25%   |
| 1001-2000      | 4         | 1.79%   |
| More than 3000 | 3         | 1.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 197       | 86.78%  |
| 21-50          | 20        | 8.81%   |
| 51-100         | 4         | 1.76%   |
| 251-500        | 2         | 0.88%   |
| 101-250        | 2         | 0.88%   |
| More than 3000 | 1         | 0.44%   |
| 1001-2000      | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST9320423AS 320GB                    | 2         | 2      | 5.26%   |
| Seagate ST1000DM010-2EP102 1TB               | 2         | 3      | 5.26%   |
| Kingston SV300S37A120G 120GB                 | 2         | 2      | 5.26%   |
| Intel SSDSC2CT120A3 120GB                    | 2         | 2      | 5.26%   |
| WDC WD6400AARS-00Y5B1 640GB                  | 1         | 1      | 2.63%   |
| WDC WD40EFRX-68N32N0 4TB                     | 1         | 2      | 2.63%   |
| WDC WD2500AAJS-60B4A0 250GB                  | 1         | 2      | 2.63%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 2      | 2.63%   |
| WDC WD20EARX-00ZUDB0 2TB                     | 1         | 1      | 2.63%   |
| WDC WD2002FYPS-02W3B0 2TB                    | 1         | 1      | 2.63%   |
| WDC WD15EARS-00Z5B1 1.5TB                    | 1         | 1      | 2.63%   |
| WDC WD15EARS-00MVWB0 1.5TB                   | 1         | 1      | 2.63%   |
| WDC WD10EAVS-00D7B0 1TB                      | 1         | 1      | 2.63%   |
| SK hynix HFS128G32MND-2200A 128GB            | 1         | 1      | 2.63%   |
| Seagate ST9640320AS 640GB                    | 1         | 1      | 2.63%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 2.63%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 2.63%   |
| Seagate ST8000AS0002-1NA17Z 8TB              | 1         | 1      | 2.63%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 2.63%   |
| Seagate ST2000DM008-2FR102 2TB               | 1         | 1      | 2.63%   |
| Seagate ST100FN0021 100GB                    | 1         | 1      | 2.63%   |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 1      | 2.63%   |
| Seagate ST1000DM003-1ER162 1TB               | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 970 EVO 500GB        | 1         | 1      | 2.63%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB | 1         | 1      | 2.63%   |
| Samsung Electronics HM250JI 250GB            | 1         | 1      | 2.63%   |
| Samsung Electronics HD321KJ 320GB            | 1         | 1      | 2.63%   |
| OCZ AGILITY3 120GB                           | 1         | 2      | 2.63%   |
| Kingston SMS200S3120G 120GB                  | 1         | 1      | 2.63%   |
| Intel SSDSC2CT060A3 64GB                     | 1         | 2      | 2.63%   |
| Intel SSDSC2BF180A4H 180GB                   | 1         | 1      | 2.63%   |
| Intel SSDSC2BA400G4 400GB                    | 1         | 1      | 2.63%   |
| Intel SSDSA2M080G2GC 80GB                    | 1         | 1      | 2.63%   |
| Hitachi HTS725025A9A364 250GB                | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 14     | 33.33%  |
| WDC                 | 6         | 12     | 18.18%  |
| Intel               | 6         | 7      | 18.18%  |
| Samsung Electronics | 4         | 4      | 12.12%  |
| Kingston            | 3         | 3      | 9.09%   |
| SK hynix            | 1         | 1      | 3.03%   |
| OCZ                 | 1         | 2      | 3.03%   |
| Hitachi             | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 13     | 52.63%  |
| WDC                 | 6         | 12     | 31.58%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| Hitachi             | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 28     | 54.84%  |
| SSD  | 13        | 15     | 41.94%  |
| NVMe | 1         | 1      | 3.23%   |

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
| Works    | 178       | 354    | 80.18%  |
| Malfunc  | 31        | 44     | 13.96%  |
| Detected | 13        | 20     | 5.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 159       | 59.33%  |
| AMD                           | 35        | 13.06%  |
| Samsung Electronics           | 15        | 5.6%    |
| Broadcom / LSI                | 9         | 3.36%   |
| Phison Electronics            | 7         | 2.61%   |
| Marvell Technology Group      | 6         | 2.24%   |
| Silicon Motion                | 5         | 1.87%   |
| SanDisk                       | 4         | 1.49%   |
| Kingston Technology Company   | 4         | 1.49%   |
| Hewlett-Packard               | 4         | 1.49%   |
| ASMedia Technology            | 4         | 1.49%   |
| Seagate Technology            | 2         | 0.75%   |
| Micron/Crucial Technology     | 2         | 0.75%   |
| KIOXIA                        | 2         | 0.75%   |
| Adaptec                       | 2         | 0.75%   |
| VIA Technologies              | 1         | 0.37%   |
| Transcend                     | 1         | 0.37%   |
| Realtek Semiconductor         | 1         | 0.37%   |
| Nvidia                        | 1         | 0.37%   |
| Integrated Technology Express | 1         | 0.37%   |
| Dell                          | 1         | 0.37%   |
| ADATA Technology              | 1         | 0.37%   |
| 3ware                         | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 27        | 8.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 17        | 5.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 4.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 2.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 2.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 2.61%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 8         | 2.61%   |
| Intel SATA Controller [RAID mode]                                                | 7         | 2.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 2.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 7         | 2.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 1.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 1.95%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 5         | 1.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 5         | 1.63%   |
| AMD FCH IDE Controller                                                           | 5         | 1.63%   |
| Intel unknown                                                                    | 4         | 1.3%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 4         | 1.3%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 4         | 1.3%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 0.98%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 3         | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 0.98%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3         | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.98%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 0.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 0.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 0.98%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 3         | 0.98%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 3         | 0.98%   |
| AMD 500 Series Chipset SATA Controller                                           | 3         | 0.98%   |
| AMD 300 Series Chipset SATA Controller                                           | 3         | 0.98%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 2         | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.65%   |
| Phison E18 PCIe4 NVMe Controller                                                 | 2         | 0.65%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 0.65%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 0.65%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                         | 2         | 0.65%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.65%   |
| Intel SSD 660P Series                                                            | 2         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 176       | 63.54%  |
| NVMe | 47        | 16.97%  |
| IDE  | 25        | 9.03%   |
| RAID | 22        | 7.94%   |
| SAS  | 7         | 2.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 180       | 81.45%  |
| AMD     | 40        | 18.1%   |
| Unknown | 1         | 0.45%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                         | 14        | 6.31%   |
| Intel N100                               | 8         | 3.6%    |
| Intel Core i5-6500 CPU @ 3.20GHz         | 6         | 2.7%    |
| Intel Celeron N5105 @ 2.00GHz            | 6         | 2.7%    |
| Intel Celeron CPU J1900 @ 1.99GHz        | 6         | 2.7%    |
| AMD RX-427BB with AMD Radeon R7 Graphics | 4         | 1.8%    |
| Intel Core i7-4770K CPU @ 3.50GHz        | 3         | 1.35%   |
| Intel Core i5-6400 CPU @ 2.70GHz         | 3         | 1.35%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 3         | 1.35%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 3         | 1.35%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 3         | 1.35%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 3         | 1.35%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz      | 2         | 0.9%    |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz      | 2         | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 0.9%    |
| Intel Core i5-8500T CPU @ 2.10GHz        | 2         | 0.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz        | 2         | 0.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz        | 2         | 0.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz        | 2         | 0.9%    |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 0.9%    |
| Intel Core i5-4250U CPU @ 1.30GHz        | 2         | 0.9%    |
| Intel Core i5-4200U CPU @ 1.60GHz        | 2         | 0.9%    |
| Intel Core i5-3470 CPU @ 3.20GHz         | 2         | 0.9%    |
| Intel Core i5-1035G4 CPU @ 1.10GHz       | 2         | 0.9%    |
| Intel Core i5 CPU M 540 @ 2.53GHz        | 2         | 0.9%    |
| Intel Core i3-4130 CPU @ 3.40GHz         | 2         | 0.9%    |
| Intel Celeron N4000 CPU @ 1.10GHz        | 2         | 0.9%    |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2         | 0.9%    |
| Intel 12th Gen Core i7-1260P             | 2         | 0.9%    |
| AMD Ryzen 9 3900X 12-Core Processor      | 2         | 0.9%    |
| AMD Ryzen 7 1700 Eight-Core Processor    | 2         | 0.9%    |
| Intel Xeon Silver 4116 CPU @ 2.10GHz     | 1         | 0.45%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz     | 1         | 0.45%   |
| Intel Xeon Silver 4110 CPU @ 2.10GHz     | 1         | 0.45%   |
| Intel Xeon E-2224 CPU @ 3.40GHz          | 1         | 0.45%   |
| Intel Xeon CPU X5680 @ 3.33GHz           | 1         | 0.45%   |
| Intel Xeon CPU X3470 @ 2.93GHz           | 1         | 0.45%   |
| Intel Xeon CPU X3450 @ 2.67GHz           | 1         | 0.45%   |
| Intel Xeon CPU X3440 @ 2.53GHz           | 1         | 0.45%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 1         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 55        | 24.77%  |
| Intel Xeon              | 29        | 13.06%  |
| Intel Celeron           | 26        | 11.71%  |
| Other                   | 22        | 9.91%   |
| Intel Core i7           | 22        | 9.91%   |
| AMD GX                  | 17        | 7.66%   |
| Intel Core i3           | 12        | 5.41%   |
| Intel Atom              | 5         | 2.25%   |
| Intel Pentium           | 4         | 1.8%    |
| AMD Ryzen 9             | 4         | 1.8%    |
| AMD Ryzen 7             | 4         | 1.8%    |
| Intel Xeon Silver       | 3         | 1.35%   |
| Intel Core 2 Duo        | 3         | 1.35%   |
| Intel Core 2 Quad       | 2         | 0.9%    |
| Intel Pentium Silver    | 1         | 0.45%   |
| Intel Pentium Dual-Core | 1         | 0.45%   |
| Intel Core m3           | 1         | 0.45%   |
| Intel Core 2            | 1         | 0.45%   |
| AMD Ryzen Threadripper  | 1         | 0.45%   |
| AMD Ryzen Embedded      | 1         | 0.45%   |
| AMD Ryzen 7 PRO         | 1         | 0.45%   |
| AMD Ryzen 5 PRO         | 1         | 0.45%   |
| AMD Ryzen 5             | 1         | 0.45%   |
| AMD G                   | 1         | 0.45%   |
| AMD FX                  | 1         | 0.45%   |
| AMD Athlon 64 X2        | 1         | 0.45%   |
| AMD Athlon              | 1         | 0.45%   |
| AMD A4                  | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 125       | 56.31%  |
| 2       | 54        | 24.32%  |
| 6       | 10        | 4.5%    |
| 16      | 9         | 4.05%   |
| 8       | 9         | 4.05%   |
| Unknown | 7         | 3.15%   |
| 24      | 6         | 2.7%    |
| 12      | 1         | 0.45%   |
| 10      | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 210       | 95.45%  |
| 2       | 7         | 3.18%   |
| Unknown | 3         | 1.36%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 128       | 57.66%  |
| 2       | 87        | 39.19%  |
| Unknown | 7         | 3.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 28        | 12.61%  |
| Skylake       | 26        | 11.71%  |
| Unknown       | 26        | 11.71%  |
| KabyLake      | 20        | 9.01%   |
| Silvermont    | 16        | 7.21%   |
| Puma          | 15        | 6.76%   |
| SandyBridge   | 13        | 5.86%   |
| IvyBridge     | 11        | 4.95%   |
| Broadwell     | 8         | 3.6%    |
| Westmere      | 7         | 3.15%   |
| Penryn        | 7         | 3.15%   |
| Nehalem       | 6         | 2.7%    |
| Goldmont plus | 6         | 2.7%    |
| Zen           | 5         | 2.25%   |
| Steamroller   | 4         | 1.8%    |
| Core          | 4         | 1.8%    |
| Zen 2         | 3         | 1.35%   |
| Jaguar        | 3         | 1.35%   |
| IceLake       | 3         | 1.35%   |
| TigerLake     | 2         | 0.9%    |
| Piledriver    | 2         | 0.9%    |
| Zen+          | 1         | 0.45%   |
| Zen 3         | 1         | 0.45%   |
| K8 Hammer     | 1         | 0.45%   |
| Goldmont      | 1         | 0.45%   |
| Excavator     | 1         | 0.45%   |
| CometLake     | 1         | 0.45%   |
| Bobcat        | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 132       | 61.97%  |
| Nvidia                     | 27        | 12.68%  |
| AMD                        | 25        | 11.74%  |
| Matrox Electronics Systems | 18        | 8.45%   |
| ASPEED Technology          | 11        | 5.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 5.12%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 11        | 5.12%   |
| Intel HD Graphics 530                                                                    | 10        | 4.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 4.19%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 9         | 4.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 3.72%   |
| Intel JasperLake [UHD Graphics]                                                          | 8         | 3.72%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 6         | 2.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 2.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 2.33%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.86%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 1.86%   |
| Matrox Electronics Systems MGA G200EH                                                    | 3         | 1.4%    |
| Matrox Electronics Systems G200eR2                                                       | 3         | 1.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.4%    |
| Intel HD Graphics 620                                                                    | 3         | 1.4%    |
| Intel HD Graphics 5500                                                                   | 3         | 1.4%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.4%    |
| AMD ES1000                                                                               | 3         | 1.4%    |
| Nvidia GT215 [GeForce GT 240]                                                            | 2         | 0.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.93%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.93%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 2         | 0.93%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 0.93%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 2         | 0.93%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2         | 0.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.93%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 0.93%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 2         | 0.93%   |
| Intel HD Graphics 630                                                                    | 2         | 0.93%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 0.93%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.93%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.93%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 0.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 121       | 54.5%   |
| 1 x AMD         | 21        | 9.46%   |
| Other           | 19        | 8.56%   |
| 1 x Nvidia      | 19        | 8.56%   |
| 1 x Matrox      | 18        | 8.11%   |
| 1 x ASPEED      | 9         | 4.05%   |
| Intel + Nvidia  | 5         | 2.25%   |
| 2 x Intel       | 3         | 1.35%   |
| Intel + AMD     | 2         | 0.9%    |
| AMD + Nvidia    | 2         | 0.9%    |
| 2 x AMD         | 1         | 0.45%   |
| Nvidia + ASPEED | 1         | 0.45%   |
| Intel + ASPEED  | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 183       | 82.81%  |
| Unknown     | 23        | 10.41%  |
| Proprietary | 15        | 6.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 201       | 91.36%  |
| 1.01-2.0   | 6         | 2.73%   |
| 5.01-6.0   | 3         | 1.36%   |
| 0.51-1.0   | 3         | 1.36%   |
| 7.01-8.0   | 2         | 0.91%   |
| 3.01-4.0   | 2         | 0.91%   |
| 8.01-16.0  | 2         | 0.91%   |
| 0.01-0.5   | 1         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 8         | 12.9%   |
| LG Display              | 8         | 12.9%   |
| Chimei Innolux          | 7         | 11.29%  |
| Hewlett-Packard         | 6         | 9.68%   |
| Philips                 | 4         | 6.45%   |
| Dell                    | 4         | 6.45%   |
| AU Optronics            | 4         | 6.45%   |
| Ancor Communications    | 3         | 4.84%   |
| LG Electronics          | 2         | 3.23%   |
| Lenovo                  | 2         | 3.23%   |
| Iiyama                  | 2         | 3.23%   |
| AOC                     | 2         | 3.23%   |
| VMO                     | 1         | 1.61%   |
| TMX                     | 1         | 1.61%   |
| Panasonic               | 1         | 1.61%   |
| Lenovo Group Limited    | 1         | 1.61%   |
| InfoVision              | 1         | 1.61%   |
| Goldstar                | 1         | 1.61%   |
| Gigabyte Technology     | 1         | 1.61%   |
| Chi Mei Optoelectronics | 1         | 1.61%   |
| BOE                     | 1         | 1.61%   |
| Acer                    | 1         | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch    | 2         | 3.03%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch             | 2         | 3.03%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch         | 2         | 3.03%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                | 2         | 3.03%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                     | 2         | 3.03%   |
| AOC 2350 AOC2350 1920x1080 510x290mm 23.1-inch                       | 2         | 3.03%   |
| VMO LCD QHD 1 VMO1091 2560x1440 600x340mm 27.2-inch                  | 1         | 1.52%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x170mm 13.9-inch              | 1         | 1.52%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch | 1         | 1.52%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch    | 1         | 1.52%   |
| Samsung Electronics LCD Monitor SyncMaster                           | 1         | 1.52%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 300x170mm 13.6-inch | 1         | 1.52%   |
| Samsung Electronics LCD Monitor SE790C 3440x1440                     | 1         | 1.52%   |
| Samsung Electronics LCD Monitor S23E650 3840x1080                    | 1         | 1.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 1         | 1.52%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 710x400mm 32.1-inch            | 1         | 1.52%   |
| Philips PHL 221B6Q PHL08DF 1920x1080 480x270mm 21.7-inch             | 1         | 1.52%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch          | 1         | 1.52%   |
| LG Electronics LCD Monitor LX20D 1600x1200                           | 1         | 1.52%   |
| LG Electronics LCD Monitor LG HDR WQHD+ 3840x1600                    | 1         | 1.52%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch         | 1         | 1.52%   |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch         | 1         | 1.52%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch         | 1         | 1.52%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch          | 1         | 1.52%   |
| LG Display LCD Monitor LGD027B 1600x900 380x210mm 17.1-inch          | 1         | 1.52%   |
| LG Display LCD Monitor LGD0213 1600x900 310x170mm 13.9-inch          | 1         | 1.52%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch              | 1         | 1.52%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 1         | 1.52%   |
| Lenovo Group Limited LCD Monitor 1920x1080                           | 1         | 1.52%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch          | 1         | 1.52%   |
| Iiyama PL2888UH IVM7104 3840x2160 620x340mm 27.8-inch                | 1         | 1.52%   |
| Hewlett-Packard Z27n G2 HPN348A 2560x1440 600x340mm 27.2-inch        | 1         | 1.52%   |
| Hewlett-Packard w2216 HWP280C 1680x1050 470x290mm 21.7-inch          | 1         | 1.52%   |
| Hewlett-Packard LCD Monitor Z24n 1920x1200                           | 1         | 1.52%   |
| Hewlett-Packard LCD Monitor E241i 1920x1200                          | 1         | 1.52%   |
| Hewlett-Packard L2335 HWP2615 1920x1200 500x310mm 23.2-inch          | 1         | 1.52%   |
| Hewlett-Packard E243i HPN3463 1920x1200 520x320mm 24.0-inch          | 1         | 1.52%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch           | 1         | 1.52%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                | 1         | 1.52%   |
| Gigabyte Technology M28U GBT2800 3840x2160 630x360mm 28.6-inch       | 1         | 1.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 17        | 27.42%  |
| 3840x2160 (4K)     | 8         | 12.9%   |
| 1366x768 (WXGA)    | 7         | 11.29%  |
| 2560x1440 (QHD)    | 6         | 9.68%   |
| 1920x1200 (WUXGA)  | 6         | 9.68%   |
| 1600x900 (HD+)     | 5         | 8.06%   |
| 3840x1080          | 2         | 3.23%   |
| 3440x1440          | 2         | 3.23%   |
| 2736x1824          | 2         | 3.23%   |
| Unknown            | 2         | 3.23%   |
| 3840x1600          | 1         | 1.61%   |
| 1920x1280          | 1         | 1.61%   |
| 1680x1050 (WSXGA+) | 1         | 1.61%   |
| 1600x1200          | 1         | 1.61%   |
| 1440x900 (WXGA+)   | 1         | 1.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 15.79%  |
| Unknown | 8         | 14.04%  |
| 27      | 7         | 12.28%  |
| 13      | 7         | 12.28%  |
| 24      | 4         | 7.02%   |
| 23      | 4         | 7.02%   |
| 21      | 4         | 7.02%   |
| 12      | 4         | 7.02%   |
| 17      | 3         | 5.26%   |
| 14      | 2         | 3.51%   |
| 34      | 1         | 1.75%   |
| 32      | 1         | 1.75%   |
| 28      | 1         | 1.75%   |
| 11      | 1         | 1.75%   |
| 10      | 1         | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 24.56%  |
| 501-600     | 13        | 22.81%  |
| 201-300     | 10        | 17.54%  |
| Unknown     | 8         | 14.04%  |
| 401-500     | 4         | 7.02%   |
| 601-700     | 3         | 5.26%   |
| 351-400     | 3         | 5.26%   |
| 701-800     | 2         | 3.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 35        | 66.04%  |
| Unknown | 8         | 15.09%  |
| 16/10   | 6         | 11.32%  |
| 3/2     | 3         | 5.66%   |
| 21/9    | 1         | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 8         | 14.29%  |
| 91-100         | 8         | 14.29%  |
| Unknown        | 8         | 14.29%  |
| 81-90          | 7         | 12.5%   |
| 301-350        | 7         | 12.5%   |
| 61-70          | 4         | 7.14%   |
| 351-500        | 3         | 5.36%   |
| 251-300        | 3         | 5.36%   |
| 121-130        | 3         | 5.36%   |
| 71-80          | 2         | 3.57%   |
| 51-60          | 2         | 3.57%   |
| 101-110        | 1         | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 15        | 25.42%  |
| 101-120       | 13        | 22.03%  |
| 51-100        | 10        | 16.95%  |
| Unknown       | 8         | 13.56%  |
| 161-240       | 7         | 11.86%  |
| More than 240 | 4         | 6.78%   |
| 1-50          | 2         | 3.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 165       | 73.99%  |
| 1     | 47        | 21.08%  |
| 2     | 10        | 4.48%   |
| 3     | 1         | 0.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 177       | 59.8%   |
| Realtek Semiconductor    | 60        | 20.27%  |
| Broadcom                 | 26        | 8.78%   |
| Qualcomm Atheros         | 10        | 3.38%   |
| TP-Link                  | 2         | 0.68%   |
| Ralink Technology        | 2         | 0.68%   |
| Sierra Wireless          | 1         | 0.34%   |
| Senao                    | 1         | 0.34%   |
| OPPO Electronics         | 1         | 0.34%   |
| NetXen Incorporated      | 1         | 0.34%   |
| Microsoft                | 1         | 0.34%   |
| Mellanox Technologies    | 1         | 0.34%   |
| MediaTek                 | 1         | 0.34%   |
| Marvell Technology Group | 1         | 0.34%   |
| JMicron Technology       | 1         | 0.34%   |
| IMC Networks             | 1         | 0.34%   |
| Hewlett-Packard          | 1         | 0.34%   |
| Google                   | 1         | 0.34%   |
| Edimax Technology        | 1         | 0.34%   |
| Dell                     | 1         | 0.34%   |
| D-Link System            | 1         | 0.34%   |
| Chelsio Communications   | 1         | 0.34%   |
| Apple                    | 1         | 0.34%   |
| American Megatrends      | 1         | 0.34%   |
| AMD                      | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 51        | 13.82%  |
| Intel I211 Gigabit Network Connection                                         | 27        | 7.32%   |
| Intel I210 Gigabit Network Connection                                         | 22        | 5.96%   |
| Intel Ethernet Controller I226-V                                              | 21        | 5.69%   |
| Intel I350 Gigabit Network Connection                                         | 13        | 3.52%   |
| Intel 82574L Gigabit Network Connection                                       | 12        | 3.25%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 10        | 2.71%   |
| Intel Ethernet Connection I217-LM                                             | 9         | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 2.44%   |
| Intel 82580 Gigabit Network Connection                                        | 8         | 2.17%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7         | 1.9%    |
| Intel Wireless 7260                                                           | 6         | 1.63%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 1.36%   |
| Intel Wireless 8260                                                           | 4         | 1.08%   |
| Intel Wi-Fi 6 AX200                                                           | 4         | 1.08%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 1.08%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 1.08%   |
| Intel 82576 Gigabit Network Connection                                        | 4         | 1.08%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 0.81%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 3         | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 3         | 0.81%   |
| Intel Wireless 7265                                                           | 3         | 0.81%   |
| Intel Ethernet Controller I225-V                                              | 3         | 0.81%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 0.81%   |
| Intel Ethernet Connection I217-V                                              | 3         | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 3         | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 0.81%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 3         | 0.81%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 0.81%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 3         | 0.81%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 3         | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 0.54%   |
| Intel Wireless 3165                                                           | 2         | 0.54%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 2         | 0.54%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 55.41%  |
| Realtek Semiconductor | 9         | 12.16%  |
| Qualcomm Atheros      | 8         | 10.81%  |
| Broadcom              | 7         | 9.46%   |
| TP-Link               | 2         | 2.7%    |
| Ralink Technology     | 2         | 2.7%    |
| Sierra Wireless       | 1         | 1.35%   |
| Senao                 | 1         | 1.35%   |
| IMC Networks          | 1         | 1.35%   |
| Edimax Technology     | 1         | 1.35%   |
| Dell                  | 1         | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                             | 6         | 8%      |
| Intel Wireless 8260                                             | 4         | 5.33%   |
| Intel Wi-Fi 6 AX200                                             | 4         | 5.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 3         | 4%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 3         | 4%      |
| Intel Wireless 7265                                             | 3         | 4%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                 | 3         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 3         | 4%      |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 3         | 4%      |
| Broadcom BCM43228 802.11a/b/g/n                                 | 3         | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2         | 2.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 2         | 2.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 2         | 2.67%   |
| Intel Wireless 3165                                             | 2         | 2.67%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 2         | 2.67%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 2         | 2.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                 | 2         | 2.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 2         | 2.67%   |
| Intel Centrino Advanced-N 6200                                  | 2         | 2.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                    | 1         | 1.33%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 1         | 1.33%   |
| Sierra Wireless EM7345 4G LTE                                   | 1         | 1.33%   |
| Senao EUB9801 802.11abgn Wireless Adapter [Ralink RT3572]       | 1         | 1.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 1         | 1.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 1         | 1.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 1         | 1.33%   |
| Ralink RT5370 Wireless Adapter                                  | 1         | 1.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                           | 1         | 1.33%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 1         | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 1         | 1.33%   |
| Intel Wireless 8265 / 8275                                      | 1         | 1.33%   |
| Intel WiFi Link 5100                                            | 1         | 1.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 1         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 1         | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 1         | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 1         | 1.33%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 1         | 1.33%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 1         | 1.33%   |
| Dell Wireless 5809e Gobi 4G LTE Mobile Broadband DM Port        | 1         | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 156       | 63.41%  |
| Realtek Semiconductor    | 58        | 23.58%  |
| Broadcom                 | 21        | 8.54%   |
| Qualcomm Atheros         | 2         | 0.81%   |
| OPPO Electronics         | 1         | 0.41%   |
| Microsoft                | 1         | 0.41%   |
| MediaTek                 | 1         | 0.41%   |
| Marvell Technology Group | 1         | 0.41%   |
| JMicron Technology       | 1         | 0.41%   |
| D-Link System            | 1         | 0.41%   |
| Apple                    | 1         | 0.41%   |
| American Megatrends      | 1         | 0.41%   |
| AMD                      | 1         | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 51        | 17.65%  |
| Intel I211 Gigabit Network Connection                                         | 27        | 9.34%   |
| Intel I210 Gigabit Network Connection                                         | 22        | 7.61%   |
| Intel Ethernet Controller I226-V                                              | 21        | 7.27%   |
| Intel I350 Gigabit Network Connection                                         | 13        | 4.5%    |
| Intel 82574L Gigabit Network Connection                                       | 12        | 4.15%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 10        | 3.46%   |
| Intel Ethernet Connection I217-LM                                             | 9         | 3.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 3.11%   |
| Intel 82580 Gigabit Network Connection                                        | 8         | 2.77%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7         | 2.42%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 1.73%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 1.38%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 1.38%   |
| Intel 82576 Gigabit Network Connection                                        | 4         | 1.38%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 1.38%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 1.04%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 3         | 1.04%   |
| Intel Ethernet Controller I225-V                                              | 3         | 1.04%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.04%   |
| Intel Ethernet Connection I217-V                                              | 3         | 1.04%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 3         | 1.04%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.69%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2         | 0.69%   |
| Intel Ethernet Connection I354                                                | 2         | 0.69%   |
| Intel Ethernet Connection I218-V                                              | 2         | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.69%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.69%   |
| Intel 82583V Gigabit Network Connection                                       | 2         | 0.69%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.69%   |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 0.69%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 2         | 0.69%   |
| Realtek USB 2.5GbE Controller                                                 | 1         | 0.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.35%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.35%   |
| OPPO WAIPIO-MTP _SN:2EE444D0 RNDIS Control RNDIS Ethernet Data                | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 207       | 73.93%  |
| WiFi     | 68        | 24.29%  |
| Unknown  | 5         | 1.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 193       | 86.16%  |
| WiFi     | 31        | 13.84%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 69        | 30.67%  |
| 4     | 52        | 23.11%  |
| 1     | 31        | 13.78%  |
| 3     | 30        | 13.33%  |
| 6     | 16        | 7.11%   |
| 5     | 14        | 6.22%   |
| 7     | 5         | 2.22%   |
| 8     | 4         | 1.78%   |
| 13    | 1         | 0.44%   |
| 10    | 1         | 0.44%   |
| 9     | 1         | 0.44%   |
| 0     | 1         | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 205       | 91.11%  |
| Yes  | 20        | 8.89%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 29        | 56.86%  |
| Cambridge Silicon Radio | 4         | 7.84%   |
| Apple                   | 4         | 7.84%   |
| Broadcom                | 3         | 5.88%   |
| Realtek Semiconductor   | 2         | 3.92%   |
| IMC Networks            | 2         | 3.92%   |
| Hewlett-Packard         | 2         | 3.92%   |
| Dell                    | 2         | 3.92%   |
| Realtek                 | 1         | 1.96%   |
| MediaTek                | 1         | 1.96%   |
| Lite-On Technology      | 1         | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 13        | 25.49%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 4         | 7.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 4         | 7.84%   |
| Intel Wireless-AC 3168 Bluetooth                        | 3         | 5.88%   |
| Intel AX200 Bluetooth                                   | 3         | 5.88%   |
| Apple Bluetooth Host Controller                         | 3         | 5.88%   |
| Realtek Bluetooth Adapter                               | 2         | 3.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 2         | 3.92%   |
| Intel AX210 Bluetooth                                   | 2         | 3.92%   |
| Intel AX201 Bluetooth                                   | 2         | 3.92%   |
| Broadcom BCM2045B (BDC-2.1)                             | 2         | 3.92%   |
| Realtek  Bluetooth 4.0 Adapter                          | 1         | 1.96%   |
| MediaTek Bluetooth Adapter                              | 1         | 1.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1         | 1.96%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip    | 1         | 1.96%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS | 1         | 1.96%   |
| HP Broadcom 2070 Bluetooth Combo                        | 1         | 1.96%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter              | 1         | 1.96%   |
| Dell Wireless 355C Bluetooth 2.0 + EDR module           | 1         | 1.96%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module             | 1         | 1.96%   |
| Broadcom Bluetooth 4.0 Adapter                          | 1         | 1.96%   |
| Apple Broadcom Built-in Bluetooth                       | 1         | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 130       | 68.06%  |
| AMD                      | 27        | 14.14%  |
| Nvidia                   | 23        | 12.04%  |
| Realtek Semiconductor    | 3         | 1.57%   |
| Philips (or NXP)         | 1         | 0.52%   |
| Nordic Semiconductor ASA | 1         | 0.52%   |
| Lenovo                   | 1         | 0.52%   |
| Hewlett-Packard          | 1         | 0.52%   |
| GN Netcom                | 1         | 0.52%   |
| Generalplus Technology   | 1         | 0.52%   |
| Focusrite-Novation       | 1         | 0.52%   |
| BEHRINGER International  | 1         | 0.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 15        | 6.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 4.85%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 4.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 4.41%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 3.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 3.96%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 3.96%   |
| Intel Jasper Lake HD Audio                                                                        | 8         | 3.52%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 8         | 3.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 3.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 2.64%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 2.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 2.2%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 2.2%    |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.2%    |
| AMD FCH Azalia Controller                                                                         | 5         | 2.2%    |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.76%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.76%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 4         | 1.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.32%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.32%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.32%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.32%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.88%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.88%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 0.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.88%   |
| Realtek Semiconductor Microphone(Attila) Microphone(Attila) Microphone(Attila)                    | 1         | 0.44%   |
| Philips (or NXP) Philips SHG7980                                                                  | 1         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 40        | 17.86%  |
| SK hynix            | 32        | 14.29%  |
| Kingston            | 28        | 12.5%   |
| Unknown             | 27        | 12.05%  |
| Corsair             | 25        | 11.16%  |
| Micron Technology   | 22        | 9.82%   |
| Crucial             | 13        | 5.8%    |
| G.Skill             | 6         | 2.68%   |
| Kimtigo             | 4         | 1.79%   |
| Unknown             | 4         | 1.79%   |
| Toshiba             | 3         | 1.34%   |
| Ramaxel Technology  | 3         | 1.34%   |
| Hewlett-Packard     | 3         | 1.34%   |
| Elpida              | 3         | 1.34%   |
| Transcend           | 2         | 0.89%   |
| HPE                 | 2         | 0.89%   |
| GSkill              | 2         | 0.89%   |
| tigo                | 1         | 0.45%   |
| Smart Modular       | 1         | 0.45%   |
| Mushkin             | 1         | 0.45%   |
| ASint Technology    | 1         | 0.45%   |
| Apacer              | 1         | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 12        | 5%      |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s          | 4         | 1.67%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s     | 4         | 1.67%   |
| Unknown                                                 | 4         | 1.67%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s   | 3         | 1.25%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s  | 3         | 1.25%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 3         | 1.25%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s              | 2         | 0.83%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 0.83%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s    | 2         | 0.83%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 2         | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 0.83%   |
| SK hynix RAM HMCG78AEBSA092N 16GB SODIMM DDR5 4800MT/s  | 2         | 0.83%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s               | 2         | 0.83%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 0.83%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 2         | 0.83%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s   | 2         | 0.83%   |
| Samsung RAM M471A1K43CB1-CWE 8GB SODIMM DDR4 3200MT/s   | 2         | 0.83%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s | 2         | 0.83%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 2         | 0.83%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                | 2         | 0.83%   |
| Micron RAM 8ATF1G64HZ-2G6D1 8GB SODIMM DDR4 2667MT/s    | 2         | 0.83%   |
| Micron RAM 16KTF51264HZ-1G4M1 4GB SODIMM DDR3 1333MT/s  | 2         | 0.83%   |
| Kingston RAM 9965525-116.A00LF 8GB DIMM DDR3 1600MT/s   | 2         | 0.83%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s   | 2         | 0.83%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s | 2         | 0.83%   |
| Corsair RAM CMSO4GX3M1C1600C11 4GB DIMM DDR3 1600MT/s   | 2         | 0.83%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s             | 1         | 0.42%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s             | 1         | 0.42%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s               | 1         | 0.42%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1         | 0.42%   |
| Unknown RAM Module 4096MB DIMM DDR3 1332MT/s            | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR3                      | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s               | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 1         | 0.42%   |
| Unknown RAM Module 2048MB DIMM DDR3 1332MT/s            | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 103       | 50.49%  |
| DDR4    | 73        | 35.78%  |
| DDR5    | 12        | 5.88%   |
| DDR2    | 7         | 3.43%   |
| Unknown | 4         | 1.96%   |
| SDRAM   | 2         | 0.98%   |
| LPDDR3  | 2         | 0.98%   |
| DRAM    | 1         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 105       | 51.22%  |
| SODIMM       | 94        | 45.85%  |
| Row Of Chips | 3         | 1.46%   |
| FB-DIMM      | 2         | 0.98%   |
| Chip         | 1         | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 81        | 37.16%  |
| 8192  | 72        | 33.03%  |
| 16384 | 31        | 14.22%  |
| 2048  | 20        | 9.17%   |
| 1024  | 8         | 3.67%   |
| 32768 | 6         | 2.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 58        | 27.36%  |
| 1333    | 41        | 19.34%  |
| 3200    | 20        | 9.43%   |
| 2133    | 19        | 8.96%   |
| 2667    | 16        | 7.55%   |
| 2400    | 15        | 7.08%   |
| 4800    | 12        | 5.66%   |
| 800     | 6         | 2.83%   |
| 667     | 6         | 2.83%   |
| 2666    | 5         | 2.36%   |
| Unknown | 4         | 1.89%   |
| 1334    | 2         | 0.94%   |
| 1067    | 2         | 0.94%   |
| 4400    | 1         | 0.47%   |
| 2933    | 1         | 0.47%   |
| 1867    | 1         | 0.47%   |
| 1866    | 1         | 0.47%   |
| 1332    | 1         | 0.47%   |
| 333     | 1         | 0.47%   |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 9         | 31.03%  |
| Bison Electronics             | 5         | 17.24%  |
| Microdia                      | 4         | 13.79%  |
| IMC Networks                  | 3         | 10.34%  |
| Realtek Semiconductor         | 2         | 6.9%    |
| Syntek                        | 1         | 3.45%   |
| Suyin                         | 1         | 3.45%   |
| Sunplus Innovation Technology | 1         | 3.45%   |
| Quanta                        | 1         | 3.45%   |
| Logitech                      | 1         | 3.45%   |
| Lenovo                        | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Bison Integrated Camera                  | 4         | 13.79%  |
| Microdia USB 2.0 Camera                  | 2         | 6.9%    |
| Microdia Integrated Webcam               | 2         | 6.9%    |
| Syntek EasyCamera                        | 1         | 3.45%   |
| Suyin Asus Integrated Webcam             | 1         | 3.45%   |
| Sunplus Laptop Integrated Webcam HD      | 1         | 3.45%   |
| Realtek Integrated_Webcam_HD             | 1         | 3.45%   |
| Realtek Front Camera                     | 1         | 3.45%   |
| Quanta VGA WebCam                        | 1         | 3.45%   |
| Logitech Webcam C270                     | 1         | 3.45%   |
| Lenovo Integrated Webcam                 | 1         | 3.45%   |
| IMC Networks Integrated RGB Camera       | 1         | 3.45%   |
| IMC Networks HP TrueVision HD Camera     | 1         | 3.45%   |
| IMC Networks EasyCamera                  | 1         | 3.45%   |
| Chicony USB2.0 HD UVC WebCam             | 1         | 3.45%   |
| Chicony USB 2.0 VGA UVC WebCam           | 1         | 3.45%   |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 3.45%   |
| Chicony ThinkPad T490 Webcam             | 1         | 3.45%   |
| Chicony Realtek DMFT RGB                 | 1         | 3.45%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 3.45%   |
| Chicony Integrated HP HD Webcam          | 1         | 3.45%   |
| Chicony Integrated Camera                | 1         | 3.45%   |
| Chicony Camera                           | 1         | 3.45%   |
| Bison ThinkPad P50 Integrated Camera     | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 27.27%  |
| Upek                       | 2         | 18.18%  |
| Broadcom                   | 2         | 18.18%  |
| AuthenTec                  | 2         | 18.18%  |
| Synaptics                  | 1         | 9.09%   |
| Shenzhen Goodix Technology | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 18.18%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 18.18%  |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 9.09%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 9.09%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 9.09%   |
| AuthenTec AES2810                                                            | 1         | 9.09%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 9.09%   |

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
| 1     | 95        | 42.79%  |
| 0     | 68        | 30.63%  |
| 2     | 44        | 19.82%  |
| 3     | 9         | 4.05%   |
| 4     | 4         | 1.8%    |
| 5     | 2         | 0.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 137       | 68.84%  |
| Net/wireless             | 15        | 7.54%   |
| Bluetooth                | 12        | 6.03%   |
| Fingerprint reader       | 8         | 4.02%   |
| Card reader              | 7         | 3.52%   |
| Firewire controller      | 6         | 3.02%   |
| Sound                    | 4         | 2.01%   |
| Network                  | 3         | 1.51%   |
| Graphics card            | 3         | 1.51%   |
| Storage/ata              | 2         | 1.01%   |
| Net/ethernet             | 2         | 1.01%   |

