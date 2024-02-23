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

Total: 297

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| OPNsense 21.1     | 11        | 4.45%   |
| OPNsense 22.7.10  | 9         | 3.64%   |
| OPNsense 23.7.9   | 6         | 2.43%   |
| OPNsense 23.7.10  | 6         | 2.43%   |
| OPNsense 21.7.7   | 6         | 2.43%   |
| OPNsense 21.1.3   | 6         | 2.43%   |
| OpenBSD 6.8       | 6         | 2.43%   |
| OPNsense 24.1.1   | 5         | 2.02%   |
| OPNsense 24.1     | 5         | 2.02%   |
| OPNsense 23.1.11  | 5         | 2.02%   |
| OPNsense 21.1.5   | 5         | 2.02%   |
| OPNsense 21.1.2   | 5         | 2.02%   |
| OpenBSD 7.0       | 5         | 2.02%   |
| helloSystem 0.5.0 | 5         | 2.02%   |
| OPNsense 23.7.7   | 4         | 1.62%   |
| OPNsense 22.7.8   | 4         | 1.62%   |
| OPNsense 21.1.8   | 4         | 1.62%   |
| OPNsense 23.7.6   | 3         | 1.21%   |
| OPNsense 23.7.5   | 3         | 1.21%   |
| OPNsense 23.7.4   | 3         | 1.21%   |
| OPNsense 23.7.12  | 3         | 1.21%   |
| OPNsense 23.7.1   | 3         | 1.21%   |
| OPNsense 23.1.6   | 3         | 1.21%   |
| OPNsense 23.1.3   | 3         | 1.21%   |
| OPNsense 23.1.10  | 3         | 1.21%   |
| OPNsense 22.7.9   | 3         | 1.21%   |
| OPNsense 22.7.2   | 3         | 1.21%   |
| OPNsense 22.1.8   | 3         | 1.21%   |
| OPNsense 21.7.3   | 3         | 1.21%   |
| OPNsense 21.7.1   | 3         | 1.21%   |
| OPNsense 20.7.8   | 3         | 1.21%   |
| OpenBSD 6.9       | 3         | 1.21%   |
| helloSystem 0.8.1 | 3         | 1.21%   |
| helloSystem 0.8.0 | 3         | 1.21%   |
| helloSystem 0.7.0 | 3         | 1.21%   |
| FreeBSD 13.1-p5   | 3         | 1.21%   |
| FreeBSD 13.0-p7   | 3         | 1.21%   |
| FreeBSD 12.1-p8   | 3         | 1.21%   |
| OPNsense 23.7.8   | 2         | 0.81%   |
| OPNsense 23.1.7   | 2         | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 134       | 65.05%  |
| FreeBSD     | 32        | 15.53%  |
| helloSystem | 17        | 8.25%   |
| OpenBSD     | 16        | 7.77%   |
| GhostBSD    | 4         | 1.94%   |
| pfSense     | 1         | 0.49%   |
| NomadBSD    | 1         | 0.49%   |
| FuryBSD     | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 205       | 99.51%  |
| octeon | 1         | 0.49%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 149       | 71.63%  |
| helloDesktop | 18        | 8.65%   |
| KDE5         | 12        | 5.77%   |
| fvwm         | 12        | 5.77%   |
| MATE         | 5         | 2.4%    |
| XFCE         | 2         | 0.96%   |
| i3           | 2         | 0.96%   |
| GNOME        | 2         | 0.96%   |
| xfwm         | 1         | 0.48%   |
| TWM          | 1         | 0.48%   |
| Openbox      | 1         | 0.48%   |
| Mutter       | 1         | 0.48%   |
| LXQt         | 1         | 0.48%   |
| AwesomeWM    | 1         | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 150       | 72.82%  |
| X11     | 56        | 27.18%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 163       | 77.99%  |
| SLiM    | 18        | 8.61%   |
| SDDM    | 13        | 6.22%   |
| LightDM | 8         | 3.83%   |
| GDM     | 5         | 2.39%   |
| XDM     | 2         | 0.96%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 150       | 72.12%  |
| en_US          | 26        | 12.5%   |
| C              | 21        | 10.1%   |
| sv_SE          | 5         | 2.4%    |
| sv_SE.US-ASCII | 1         | 0.48%   |
| sv             | 1         | 0.48%   |
| en_GB          | 1         | 0.48%   |
| en_CA          | 1         | 0.48%   |
| en_BE          | 1         | 0.48%   |
| en             | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 181       | 87.02%  |
| BIOS | 27        | 12.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 101       | 48.56%  |
| Zfs    | 84        | 40.38%  |
| Ffs    | 16        | 7.69%   |
| Cd9660 | 7         | 3.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 192       | 91.87%  |
| MBR     | 16        | 7.66%   |
| Unknown | 1         | 0.48%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Hewlett-Packard            | 23        | 11.17%  |
| Dell                       | 23        | 11.17%  |
| Lenovo                     | 21        | 10.19%  |
| ASUSTek Computer           | 19        | 9.22%   |
| Unknown                    | 18        | 8.74%   |
| PC Engines                 | 14        | 6.8%    |
| Intel                      | 11        | 5.34%   |
| Gigabyte Technology        | 9         | 4.37%   |
| AMI                        | 8         | 3.88%   |
| Supermicro                 | 7         | 3.4%    |
| MSI                        | 7         | 3.4%    |
| Fujitsu                    | 4         | 1.94%   |
| CWWK                       | 4         | 1.94%   |
| Techvision                 | 3         | 1.46%   |
| Microsoft                  | 3         | 1.46%   |
| ASRock                     | 3         | 1.46%   |
| Apple                      | 3         | 1.46%   |
| Toshiba                    | 2         | 0.97%   |
| Star Labs                  | 2         | 0.97%   |
| Shuttle                    | 2         | 0.97%   |
| HPE                        | 2         | 0.97%   |
| Deciso                     | 2         | 0.97%   |
| ZOTAC                      | 1         | 0.49%   |
| Wistron                    | 1         | 0.49%   |
| Sony                       | 1         | 0.49%   |
| ShenZhen MinWin Technology | 1         | 0.49%   |
| Razer                      | 1         | 0.49%   |
| Protectli                  | 1         | 0.49%   |
| Google                     | 1         | 0.49%   |
| Fujitsu Siemens            | 1         | 0.49%   |
| DFI                        | 1         | 0.49%   |
| CompuLab                   | 1         | 0.49%   |
| Cisco                      | 1         | 0.49%   |
| AZW                        | 1         | 0.49%   |
| AOpen                      | 1         | 0.49%   |
| ADI                        | 1         | 0.49%   |
| ACMA                       | 1         | 0.49%   |
| Acer                       | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 19        | 9.22%   |
| PC Engines APU2                   | 7         | 3.4%    |
| AMI Aptio CRB                     | 6         | 2.91%   |
| HP t730 Thin Client               | 4         | 1.94%   |
| Techvision TVI7309X               | 3         | 1.46%   |
| Supermicro Super Server           | 3         | 1.46%   |
| PC Engines apu4                   | 3         | 1.46%   |
| Intel CRESCENTBAY                 | 3         | 1.46%   |
| HP EliteDesk 800 G2 SFF           | 3         | 1.46%   |
| ASUS All Series                   | 3         | 1.46%   |
| Supermicro X10SLL-F               | 2         | 0.97%   |
| Star Labs StarBook                | 2         | 0.97%   |
| PC Engines APU3                   | 2         | 0.97%   |
| Microsoft Surface Pro 7           | 2         | 0.97%   |
| Intel Q3XXG4-P V1.0               | 2         | 0.97%   |
| Intel D54250WYK H13922-303        | 2         | 0.97%   |
| HP EliteDesk 800 G1 SFF           | 2         | 0.97%   |
| Dell PowerEdge R210 II            | 2         | 0.97%   |
| Dell PowerEdge R210               | 2         | 0.97%   |
| Dell OptiPlex 9020                | 2         | 0.97%   |
| CWWK CW-AD4L-N V1                 | 2         | 0.97%   |
| ZOTAC ZBOX-CI329NANO              | 1         | 0.49%   |
| Wistron ProLiant ML110 G6         | 1         | 0.49%   |
| Toshiba TECRA Z40-C-12Z           | 1         | 0.49%   |
| Toshiba Satellite L450            | 1         | 0.49%   |
| Supermicro X10SLH-N6-ST031        | 1         | 0.49%   |
| Supermicro SYS-1019S-MP           | 1         | 0.49%   |
| Sony SVP1322M1EBI                 | 1         | 0.49%   |
| Shuttle SH570                     | 1         | 0.49%   |
| Shuttle DH170                     | 1         | 0.49%   |
| ShenZhen MinWin MW-NANO-APL-4L    | 1         | 0.49%   |
| Razer Blade 14 (2022) - RZ09-0427 | 1         | 0.49%   |
| Protectli FW4B                    | 1         | 0.49%   |
| PC Engines apu6                   | 1         | 0.49%   |
| PC Engines APU                    | 1         | 0.49%   |
| MSI WC776AA-UUW HPE-110sc         | 1         | 0.49%   |
| MSI MS-7C56                       | 1         | 0.49%   |
| MSI MS-7B85                       | 1         | 0.49%   |
| MSI MS-7B43                       | 1         | 0.49%   |
| MSI MS-7A40                       | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 19        | 9.22%   |
| Dell PowerEdge                 | 11        | 5.34%   |
| Lenovo ThinkPad                | 10        | 4.85%   |
| Dell OptiPlex                  | 8         | 3.88%   |
| PC Engines APU2                | 7         | 3.4%    |
| HP EliteDesk                   | 7         | 3.4%    |
| AMI Aptio                      | 6         | 2.91%   |
| Lenovo ThinkCentre             | 5         | 2.43%   |
| HP ProLiant                    | 5         | 2.43%   |
| HP t730                        | 4         | 1.94%   |
| Techvision TVI7309X            | 3         | 1.46%   |
| Supermicro Super               | 3         | 1.46%   |
| PC Engines apu4                | 3         | 1.46%   |
| Microsoft Surface              | 3         | 1.46%   |
| Intel CRESCENTBAY              | 3         | 1.46%   |
| Dell Latitude                  | 3         | 1.46%   |
| ASUS All                       | 3         | 1.46%   |
| Supermicro X10SLL-F            | 2         | 0.97%   |
| Star Labs StarBook             | 2         | 0.97%   |
| PC Engines APU3                | 2         | 0.97%   |
| Lenovo IdeaPad                 | 2         | 0.97%   |
| Intel Q3XXG4-P                 | 2         | 0.97%   |
| Intel D54250WYK                | 2         | 0.97%   |
| HPE ProLiant                   | 2         | 0.97%   |
| Fujitsu ESPRIMO                | 2         | 0.97%   |
| CWWK CW-AD4L-N                 | 2         | 0.97%   |
| ASUS ROG                       | 2         | 0.97%   |
| ZOTAC ZBOX-CI329NANO           | 1         | 0.49%   |
| Wistron ProLiant               | 1         | 0.49%   |
| Toshiba TECRA                  | 1         | 0.49%   |
| Toshiba Satellite              | 1         | 0.49%   |
| Supermicro X10SLH-N6-ST031     | 1         | 0.49%   |
| Supermicro SYS-1019S-MP        | 1         | 0.49%   |
| Sony SVP1322M1EBI              | 1         | 0.49%   |
| Shuttle SH570                  | 1         | 0.49%   |
| Shuttle DH170                  | 1         | 0.49%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.49%   |
| Razer Blade                    | 1         | 0.49%   |
| Protectli FW4B                 | 1         | 0.49%   |
| PC Engines apu6                | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2016    | 23        | 11.17%  |
| 2020    | 19        | 9.22%   |
| 2014    | 18        | 8.74%   |
| 2022    | 17        | 8.25%   |
| 2017    | 17        | 8.25%   |
| 2018    | 16        | 7.77%   |
| 2015    | 15        | 7.28%   |
| 2019    | 14        | 6.8%    |
| 2023    | 12        | 5.83%   |
| 2021    | 12        | 5.83%   |
| 2010    | 11        | 5.34%   |
| 2012    | 10        | 4.85%   |
| 2013    | 8         | 3.88%   |
| 2009    | 7         | 3.4%    |
| 2011    | 4         | 1.94%   |
| 2007    | 1         | 0.49%   |
| 2006    | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 129       | 62.62%  |
| Notebook   | 37        | 17.96%  |
| Server     | 23        | 11.17%  |
| Mini pc    | 13        | 6.31%   |
| Tablet     | 3         | 1.46%   |
| All in one | 1         | 0.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 187       | 90.78%  |
| Yes  | 19        | 9.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 73        | 34.93%  |
| 4.01-8.0        | 47        | 22.49%  |
| 16.01-24.0      | 43        | 20.57%  |
| 32.01-64.0      | 22        | 10.53%  |
| 64.01-256.0     | 7         | 3.35%   |
| 24.01-32.0      | 6         | 2.87%   |
| 2.01-3.0        | 5         | 2.39%   |
| More than 256.0 | 3         | 1.44%   |
| 3.01-4.0        | 2         | 0.96%   |
| 1.01-2.0        | 1         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 107       | 50.95%  |
| 0.51-1.0    | 62        | 29.52%  |
| 1.01-2.0    | 25        | 11.9%   |
| 2.01-3.0    | 5         | 2.38%   |
| 4.01-8.0    | 4         | 1.9%    |
| 3.01-4.0    | 2         | 0.95%   |
| 24.01-32.0  | 2         | 0.95%   |
| 64.01-256.0 | 2         | 0.95%   |
| 32.01-64.0  | 1         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 144       | 68.57%  |
| 2      | 22        | 10.48%  |
| 0      | 16        | 7.62%   |
| 3      | 12        | 5.71%   |
| 6      | 4         | 1.9%    |
| 4      | 3         | 1.43%   |
| 11     | 2         | 0.95%   |
| 8      | 2         | 0.95%   |
| 18     | 1         | 0.48%   |
| 12     | 1         | 0.48%   |
| 10     | 1         | 0.48%   |
| 9      | 1         | 0.48%   |
| 5      | 1         | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 173       | 83.57%  |
| Yes       | 34        | 16.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 193       | 93.69%  |
| No        | 13        | 6.31%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 143       | 69.08%  |
| Yes       | 64        | 30.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 160       | 77.29%  |
| Yes       | 47        | 22.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Sweden  | 206       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Stockholm             | 33        | 14.35%  |
| Malmo                 | 13        | 5.65%   |
| Gothenburg            | 10        | 4.35%   |
| Bromma                | 6         | 2.61%   |
| LinkГ¶ping          | 5         | 2.17%   |
| VÃ¤sterÃ¥s        | 4         | 1.74%   |
| Västerås            | 4         | 1.74%   |
| UmeГҐ               | 4         | 1.74%   |
| Linköping            | 4         | 1.74%   |
| Uppsala               | 3         | 1.3%    |
| Umeå                 | 3         | 1.3%    |
| Taby                  | 3         | 1.3%    |
| Sollentuna            | 3         | 1.3%    |
| Skövde               | 3         | 1.3%    |
| Piteå                | 3         | 1.3%    |
| Lund                  | 3         | 1.3%    |
| Karlskrona            | 3         | 1.3%    |
| JГ¶nkГ¶ping       | 3         | 1.3%    |
| Henan                 | 3         | 1.3%    |
| Gävle                | 3         | 1.3%    |
| Bandhagen             | 3         | 1.3%    |
| Upplands Vasby        | 2         | 0.87%   |
| Tyreso Strand         | 2         | 0.87%   |
| Tumba                 | 2         | 0.87%   |
| Solna                 | 2         | 0.87%   |
| Solleftea             | 2         | 0.87%   |
| Örebro               | 2         | 0.87%   |
| Landskrona            | 2         | 0.87%   |
| Kungsbacka            | 2         | 0.87%   |
| Jönköping           | 2         | 0.87%   |
| Helsingborg           | 2         | 0.87%   |
| Falkenberg            | 2         | 0.87%   |
| Enskede-Arsta-Vantoer | 2         | 0.87%   |
| Г…hus              | 1         | 0.43%   |
| Г„lvГ¤ngen       | 1         | 0.43%   |
| Vaxjo                 | 1         | 0.43%   |
| Varekil               | 1         | 0.43%   |
| Vallingby             | 1         | 0.43%   |
| Vallentuna            | 1         | 0.43%   |
| UmeÃ¥               | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 44        | 61     | 17.74%  |
| Kingston            | 30        | 37     | 12.1%   |
| Seagate             | 25        | 57     | 10.08%  |
| WDC                 | 22        | 33     | 8.87%   |
| Intel               | 21        | 37     | 8.47%   |
| Hoodisk             | 15        | 23     | 6.05%   |
| SanDisk             | 11        | 14     | 4.44%   |
| Crucial             | 9         | 18     | 3.63%   |
| Toshiba             | 8         | 18     | 3.23%   |
| NVMe                | 5         | 6      | 2.02%   |
| Transcend           | 4         | 4      | 1.61%   |
| OCZ                 | 4         | 6      | 1.61%   |
| Micron Technology   | 4         | 7      | 1.61%   |
| LITEON              | 4         | 8      | 1.61%   |
| Hewlett-Packard     | 4         | 8      | 1.61%   |
| Phison              | 3         | 3      | 1.21%   |
| Hitachi             | 3         | 3      | 1.21%   |
| China               | 3         | 3      | 1.21%   |
| Apple               | 3         | 3      | 1.21%   |
| SK hynix            | 2         | 2      | 0.81%   |
| Innodisk            | 2         | 3      | 0.81%   |
| HPE                 | 2         | 14     | 0.81%   |
| Apacer              | 2         | 2      | 0.81%   |
| A-DATA Technology   | 2         | 2      | 0.81%   |
| XrayDisk            | 1         | 1      | 0.4%    |
| TCSUNBOW            | 1         | 1      | 0.4%    |
| Supermicro          | 1         | 1      | 0.4%    |
| Star Drive          | 1         | 1      | 0.4%    |
| Silicon Motion      | 1         | 1      | 0.4%    |
| PNY                 | 1         | 1      | 0.4%    |
| MARVELL             | 1         | 2      | 0.4%    |
| LITEONIT            | 1         | 1      | 0.4%    |
| KingSpec            | 1         | 1      | 0.4%    |
| Kimtigo             | 1         | 1      | 0.4%    |
| HGST                | 1         | 4      | 0.4%    |
| Fordisk             | 1         | 1      | 0.4%    |
| faspeed             | 1         | 1      | 0.4%    |
| Fanxiang            | 1         | 2      | 0.4%    |
| Dell                | 1         | 2      | 0.4%    |
| Corsair             | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB    | 5         | 1.82%   |
| SanDisk SDSA6MM-032G-1006 32GB | 4         | 1.45%   |
| Kingston SA400S37240G 240GB    | 4         | 1.45%   |
| Hoodisk SSD 64GB               | 4         | 1.45%   |
| Hoodisk SSD 16GB               | 4         | 1.45%   |
| Hoodisk SSD 128GB              | 4         | 1.45%   |
| Samsung SSD 860 QVO 1TB        | 3         | 1.09%   |
| Intel SSDSC2BW240A4 240GB      | 3         | 1.09%   |
| WDC WD5000AZLX-60K2TA0 500GB   | 2         | 0.73%   |
| Toshiba HDWR11A 10TB           | 2         | 0.73%   |
| Toshiba HDWQ140 4TB            | 2         | 0.73%   |
| Seagate ST9320423AS 320GB      | 2         | 0.73%   |
| Seagate ST4000DM004-2CV104 4TB | 2         | 0.73%   |
| Seagate ST2000DM008-2FR102 2TB | 2         | 0.73%   |
| Seagate ST1000DM010-2EP102 1TB | 2         | 0.73%   |
| SanDisk SDSSDHP256G 256GB      | 2         | 0.73%   |
| Samsung SSD 970 EVO Plus 500GB | 2         | 0.73%   |
| Samsung SSD 970 EVO 500GB      | 2         | 0.73%   |
| Samsung SSD 870 EVO 250GB      | 2         | 0.73%   |
| Samsung SSD 860 EVO 250GB      | 2         | 0.73%   |
| Samsung SSD 850 EVO 250GB      | 2         | 0.73%   |
| Samsung SSD 840 EVO 120GB      | 2         | 0.73%   |
| Samsung HD501LJ 500GB          | 2         | 0.73%   |
| Phison SATA SSD 16GB           | 2         | 0.73%   |
| OCZ AGILITY3 120GB             | 2         | 0.73%   |
| NVMe KBG40ZPZ256G TOS 256GB    | 2         | 0.73%   |
| Kingston SV300S37A240G 240GB   | 2         | 0.73%   |
| Kingston SV300S37A120G 120GB   | 2         | 0.73%   |
| Kingston SKC600MS256G 256GB    | 2         | 0.73%   |
| Kingston SA2000M8250G 250GB    | 2         | 0.73%   |
| Intel SSDSC2CT120A3 120GB      | 2         | 0.73%   |
| Intel SSDSC2CT060A3 64GB       | 2         | 0.73%   |
| Intel SSDMCEAC030B3 32GB       | 2         | 0.73%   |
| Hoodisk SSD 32GB               | 2         | 0.73%   |
| HP RAID 1(1+0) 73GB            | 2         | 0.73%   |
| Crucial CT256MX100SSD1 256GB   | 2         | 0.73%   |
| China SATA SSD 16GB            | 2         | 0.73%   |
| Apacer 64GB SATA Flash Drive   | 2         | 0.73%   |
| XrayDisk SSD 64GB              | 1         | 0.36%   |
| WDC WDS500G3X0C-00SJG0 500GB   | 1         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 54     | 36.51%  |
| WDC                 | 15        | 24     | 23.81%  |
| Toshiba             | 6         | 15     | 9.52%   |
| Samsung Electronics | 6         | 9      | 9.52%   |
| Hewlett-Packard     | 4         | 8      | 6.35%   |
| NVMe                | 3         | 4      | 4.76%   |
| Hitachi             | 3         | 3      | 4.76%   |
| HPE                 | 1         | 8      | 1.59%   |
| HGST                | 1         | 4      | 1.59%   |
| Apple               | 1         | 1      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 38     | 18.95%  |
| Kingston            | 27        | 34     | 17.65%  |
| Intel               | 18        | 33     | 11.76%  |
| Hoodisk             | 15        | 23     | 9.8%    |
| SanDisk             | 11        | 14     | 7.19%   |
| Crucial             | 7         | 16     | 4.58%   |
| OCZ                 | 4         | 6      | 2.61%   |
| Micron Technology   | 4         | 7      | 2.61%   |
| LITEON              | 4         | 8      | 2.61%   |
| WDC                 | 3         | 5      | 1.96%   |
| China               | 3         | 3      | 1.96%   |
| Transcend           | 2         | 2      | 1.31%   |
| Toshiba             | 2         | 3      | 1.31%   |
| SK hynix            | 2         | 2      | 1.31%   |
| Phison              | 2         | 2      | 1.31%   |
| NVMe                | 2         | 2      | 1.31%   |
| Innodisk            | 2         | 3      | 1.31%   |
| Apple               | 2         | 2      | 1.31%   |
| Apacer              | 2         | 2      | 1.31%   |
| XrayDisk            | 1         | 1      | 0.65%   |
| TCSUNBOW            | 1         | 1      | 0.65%   |
| Supermicro          | 1         | 1      | 0.65%   |
| Seagate             | 1         | 1      | 0.65%   |
| PNY                 | 1         | 1      | 0.65%   |
| MARVELL             | 1         | 2      | 0.65%   |
| LITEONIT            | 1         | 1      | 0.65%   |
| KingSpec            | 1         | 1      | 0.65%   |
| HPE                 | 1         | 6      | 0.65%   |
| Fordisk             | 1         | 1      | 0.65%   |
| Dell                | 1         | 2      | 0.65%   |
| Corsair             | 1         | 1      | 0.65%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 133       | 224    | 60.73%  |
| HDD  | 50        | 130    | 22.83%  |
| NVMe | 36        | 40     | 16.44%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 164       | 354    | 82%     |
| NVMe | 36        | 40     | 18%     |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 147       | 230    | 71.71%  |
| 0.51-1.0   | 30        | 45     | 14.63%  |
| 1.01-2.0   | 11        | 27     | 5.37%   |
| 3.01-4.0   | 10        | 28     | 4.88%   |
| 4.01-10.0  | 7         | 24     | 3.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 92        | 43.81%  |
| 1-20           | 28        | 13.33%  |
| 251-500        | 25        | 11.9%   |
| 51-100         | 24        | 11.43%  |
| 21-50          | 22        | 10.48%  |
| 501-1000       | 12        | 5.71%   |
| 1001-2000      | 4         | 1.9%    |
| More than 3000 | 3         | 1.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 185       | 87.68%  |
| 21-50          | 19        | 9%      |
| 251-500        | 2         | 0.95%   |
| 101-250        | 2         | 0.95%   |
| More than 3000 | 1         | 0.47%   |
| 1001-2000      | 1         | 0.47%   |
| 51-100         | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST9320423AS 320GB                    | 2         | 2      | 5.26%   |
| Seagate ST1000DM010-2EP102 1TB               | 2         | 2      | 5.26%   |
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
| Seagate             | 11        | 13     | 33.33%  |
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
| Seagate             | 10        | 12     | 52.63%  |
| WDC                 | 6         | 12     | 31.58%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| Hitachi             | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 27     | 54.84%  |
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
| Works    | 166       | 331    | 79.05%  |
| Malfunc  | 31        | 43     | 14.76%  |
| Detected | 13        | 20     | 6.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 149       | 58.89%  |
| AMD                           | 33        | 13.04%  |
| Samsung Electronics           | 15        | 5.93%   |
| Broadcom / LSI                | 9         | 3.56%   |
| Marvell Technology Group      | 6         | 2.37%   |
| Silicon Motion                | 5         | 1.98%   |
| SanDisk                       | 4         | 1.58%   |
| Phison Electronics            | 4         | 1.58%   |
| Kingston Technology Company   | 4         | 1.58%   |
| Hewlett-Packard               | 4         | 1.58%   |
| ASMedia Technology            | 4         | 1.58%   |
| Seagate Technology            | 2         | 0.79%   |
| Micron/Crucial Technology     | 2         | 0.79%   |
| KIOXIA                        | 2         | 0.79%   |
| Adaptec                       | 2         | 0.79%   |
| VIA Technologies              | 1         | 0.4%    |
| Transcend                     | 1         | 0.4%    |
| Realtek Semiconductor         | 1         | 0.4%    |
| Nvidia                        | 1         | 0.4%    |
| Integrated Technology Express | 1         | 0.4%    |
| Dell                          | 1         | 0.4%    |
| ADATA Technology              | 1         | 0.4%    |
| 3ware                         | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 26        | 8.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 16        | 5.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 4.48%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 3.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 2.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 2.76%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 8         | 2.76%   |
| Intel SATA Controller [RAID mode]                                                | 7         | 2.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 7         | 2.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 2.07%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 5         | 1.72%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 1.72%   |
| AMD FCH IDE Controller                                                           | 5         | 1.72%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 4         | 1.38%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 4         | 1.38%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 1.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.03%   |
| Intel unknown                                                                    | 3         | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3         | 1.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 3         | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 1.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.03%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 3         | 1.03%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 3         | 1.03%   |
| AMD 500 Series Chipset SATA Controller                                           | 3         | 1.03%   |
| AMD 300 Series Chipset SATA Controller                                           | 3         | 1.03%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 2         | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.69%   |
| Phison E18 PCIe4 NVMe Controller                                                 | 2         | 0.69%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 0.69%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 0.69%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                         | 2         | 0.69%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.69%   |
| Intel SSD 660P Series                                                            | 2         | 0.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.69%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 2         | 0.69%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 2         | 0.69%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 165       | 62.98%  |
| NVMe | 44        | 16.79%  |
| IDE  | 25        | 9.54%   |
| RAID | 21        | 8.02%   |
| SAS  | 7         | 2.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 168       | 81.16%  |
| AMD     | 38        | 18.36%  |
| Unknown | 1         | 0.48%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                         | 13        | 6.25%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 6         | 2.88%   |
| Intel Celeron N5105 @ 2.00GHz            | 6         | 2.88%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 6         | 2.88%   |
| Intel N100                               | 5         | 2.4%    |
| AMD RX-427BB with AMD Radeon R7 Graphics | 4         | 1.92%   |
| Intel Core i7-4770K CPU @ 3.50GHz        | 3         | 1.44%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 3         | 1.44%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 3         | 1.44%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 3         | 1.44%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz      | 2         | 0.96%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz      | 2         | 0.96%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 0.96%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 2         | 0.96%   |
| Intel Core i5-6400 CPU @ 2.70GHz         | 2         | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 2         | 0.96%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 2         | 0.96%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 0.96%   |
| Intel Core i5-4250U CPU @ 1.30GHz        | 2         | 0.96%   |
| Intel Core i5-4200U CPU @ 1.60GHz        | 2         | 0.96%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz       | 2         | 0.96%   |
| Intel Core i5 CPU M 540 @ 2.53GHz        | 2         | 0.96%   |
| Intel Core i3-4130 CPU @ 3.40GHz         | 2         | 0.96%   |
| Intel Celeron N4000 CPU @ 1.10GHz        | 2         | 0.96%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 2         | 0.96%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2         | 0.96%   |
| Intel 12th Gen Core i7-1260P             | 2         | 0.96%   |
| AMD Ryzen 9 3900X 12-Core Processor      | 2         | 0.96%   |
| AMD Ryzen 7 1700 Eight-Core Processor    | 2         | 0.96%   |
| Intel Xeon Silver 4116 CPU @ 2.10GHz     | 1         | 0.48%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz     | 1         | 0.48%   |
| Intel Xeon Silver 4110 CPU @ 2.10GHz     | 1         | 0.48%   |
| Intel Xeon E-2224 CPU @ 3.40GHz          | 1         | 0.48%   |
| Intel Xeon CPU X5680 @ 3.33GHz           | 1         | 0.48%   |
| Intel Xeon CPU X3470 @ 2.93GHz           | 1         | 0.48%   |
| Intel Xeon CPU X3450 @ 2.67GHz           | 1         | 0.48%   |
| Intel Xeon CPU X3440 @ 2.53GHz           | 1         | 0.48%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 1         | 0.48%   |
| Intel Xeon CPU E5640 @ 2.67GHz           | 1         | 0.48%   |
| Intel Xeon CPU E5450 @ 3.00GHz           | 1         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 49        | 23.56%  |
| Intel Xeon              | 29        | 13.94%  |
| Intel Celeron           | 25        | 12.02%  |
| Intel Core i7           | 22        | 10.58%  |
| Other                   | 19        | 9.13%   |
| AMD GX                  | 16        | 7.69%   |
| Intel Core i3           | 12        | 5.77%   |
| Intel Pentium           | 4         | 1.92%   |
| AMD Ryzen 7             | 4         | 1.92%   |
| Intel Xeon Silver       | 3         | 1.44%   |
| Intel Core 2 Duo        | 3         | 1.44%   |
| Intel Atom              | 3         | 1.44%   |
| AMD Ryzen 9             | 3         | 1.44%   |
| Intel Core 2 Quad       | 2         | 0.96%   |
| Intel Pentium Silver    | 1         | 0.48%   |
| Intel Pentium Dual-Core | 1         | 0.48%   |
| Intel Core m3           | 1         | 0.48%   |
| Intel Core 2            | 1         | 0.48%   |
| AMD Ryzen Threadripper  | 1         | 0.48%   |
| AMD Ryzen Embedded      | 1         | 0.48%   |
| AMD Ryzen 7 PRO         | 1         | 0.48%   |
| AMD Ryzen 5 PRO         | 1         | 0.48%   |
| AMD Ryzen 5             | 1         | 0.48%   |
| AMD G                   | 1         | 0.48%   |
| AMD FX                  | 1         | 0.48%   |
| AMD Athlon 64 X2        | 1         | 0.48%   |
| AMD Athlon              | 1         | 0.48%   |
| AMD A4                  | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 117       | 56.25%  |
| 2       | 52        | 25%     |
| 16      | 9         | 4.33%   |
| 8       | 8         | 3.85%   |
| 6       | 8         | 3.85%   |
| Unknown | 7         | 3.37%   |
| 24      | 5         | 2.4%    |
| 12      | 1         | 0.48%   |
| 10      | 1         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 196       | 95.15%  |
| 2       | 7         | 3.4%    |
| Unknown | 3         | 1.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 116       | 55.77%  |
| 2       | 85        | 40.87%  |
| Unknown | 7         | 3.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 28        | 13.46%  |
| Skylake       | 25        | 12.02%  |
| Unknown       | 22        | 10.58%  |
| KabyLake      | 18        | 8.65%   |
| Silvermont    | 14        | 6.73%   |
| Puma          | 14        | 6.73%   |
| SandyBridge   | 13        | 6.25%   |
| IvyBridge     | 9         | 4.33%   |
| Westmere      | 7         | 3.37%   |
| Penryn        | 7         | 3.37%   |
| Broadwell     | 7         | 3.37%   |
| Nehalem       | 6         | 2.88%   |
| Zen           | 5         | 2.4%    |
| Goldmont plus | 5         | 2.4%    |
| Steamroller   | 4         | 1.92%   |
| Core          | 4         | 1.92%   |
| Zen 2         | 3         | 1.44%   |
| Jaguar        | 3         | 1.44%   |
| IceLake       | 3         | 1.44%   |
| TigerLake     | 2         | 0.96%   |
| Piledriver    | 2         | 0.96%   |
| Zen+          | 1         | 0.48%   |
| Zen 3         | 1         | 0.48%   |
| K8 Hammer     | 1         | 0.48%   |
| Goldmont      | 1         | 0.48%   |
| Excavator     | 1         | 0.48%   |
| CometLake     | 1         | 0.48%   |
| Bobcat        | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 123       | 62.12%  |
| Nvidia                     | 24        | 12.12%  |
| AMD                        | 24        | 12.12%  |
| Matrox Electronics Systems | 18        | 9.09%   |
| ASPEED Technology          | 9         | 4.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 5.5%    |
| Intel HD Graphics 530                                                                    | 10        | 5%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 4.5%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 9         | 4.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 4%      |
| Intel JasperLake [UHD Graphics]                                                          | 8         | 4%      |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 6         | 3%      |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 3%      |
| Intel Alder Lake-N [UHD Graphics]                                                        | 6         | 3%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 2.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 2.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 2.5%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 2%      |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2%      |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 2%      |
| Matrox Electronics Systems MGA G200EH                                                    | 3         | 1.5%    |
| Matrox Electronics Systems G200eR2                                                       | 3         | 1.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.5%    |
| Intel HD Graphics 620                                                                    | 3         | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.5%    |
| AMD ES1000                                                                               | 3         | 1.5%    |
| Nvidia GT215 [GeForce GT 240]                                                            | 2         | 1%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1%      |
| Matrox Electronics Systems MGA G200eH3                                                   | 2         | 1%      |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 1%      |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 2         | 1%      |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2         | 1%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1%      |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 1%      |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 2         | 1%      |
| Intel HD Graphics 630                                                                    | 2         | 1%      |
| Intel HD Graphics 5500                                                                   | 2         | 1%      |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 1%      |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 1%      |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1%      |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.5%    |
| Nvidia GT218 [NVS 300]                                                                   | 1         | 0.5%    |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 113       | 54.33%  |
| 1 x AMD         | 21        | 10.1%   |
| Other           | 18        | 8.65%   |
| 1 x Nvidia      | 18        | 8.65%   |
| 1 x Matrox      | 18        | 8.65%   |
| 1 x ASPEED      | 7         | 3.37%   |
| Intel + Nvidia  | 4         | 1.92%   |
| 2 x Intel       | 3         | 1.44%   |
| Intel + AMD     | 2         | 0.96%   |
| 2 x AMD         | 1         | 0.48%   |
| Nvidia + ASPEED | 1         | 0.48%   |
| Intel + ASPEED  | 1         | 0.48%   |
| AMD + Nvidia    | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 172       | 83.09%  |
| Unknown     | 22        | 10.63%  |
| Proprietary | 13        | 6.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 188       | 91.26%  |
| 1.01-2.0   | 6         | 2.91%   |
| 5.01-6.0   | 3         | 1.46%   |
| 0.51-1.0   | 3         | 1.46%   |
| 7.01-8.0   | 2         | 0.97%   |
| 3.01-4.0   | 2         | 0.97%   |
| 8.01-16.0  | 1         | 0.49%   |
| 0.01-0.5   | 1         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 8         | 13.79%  |
| LG Display              | 8         | 13.79%  |
| Chimei Innolux          | 7         | 12.07%  |
| Hewlett-Packard         | 6         | 10.34%  |
| Philips                 | 4         | 6.9%    |
| Dell                    | 4         | 6.9%    |
| AU Optronics            | 3         | 5.17%   |
| LG Electronics          | 2         | 3.45%   |
| Iiyama                  | 2         | 3.45%   |
| AOC                     | 2         | 3.45%   |
| Ancor Communications    | 2         | 3.45%   |
| TMX                     | 1         | 1.72%   |
| Panasonic               | 1         | 1.72%   |
| Lenovo Group Limited    | 1         | 1.72%   |
| Lenovo                  | 1         | 1.72%   |
| InfoVision              | 1         | 1.72%   |
| Goldstar                | 1         | 1.72%   |
| Gigabyte Technology     | 1         | 1.72%   |
| Chi Mei Optoelectronics | 1         | 1.72%   |
| BOE                     | 1         | 1.72%   |
| Acer                    | 1         | 1.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch    | 2         | 3.23%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch             | 2         | 3.23%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch         | 2         | 3.23%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                | 2         | 3.23%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                     | 2         | 3.23%   |
| AOC 2350 AOC2350 1920x1080 510x290mm 23.1-inch                       | 2         | 3.23%   |
| TMX TL140BDXP02-0 TMX1400 2560x1440 310x170mm 13.9-inch              | 1         | 1.61%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch | 1         | 1.61%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch    | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SyncMaster                           | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SE790C 3440x1440                     | 1         | 1.61%   |
| Samsung Electronics LCD Monitor S23E650 3840x1080                    | 1         | 1.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 1         | 1.61%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 710x400mm 32.1-inch            | 1         | 1.61%   |
| Philips PHL 221B6Q PHL08DF 1920x1080 480x270mm 21.7-inch             | 1         | 1.61%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch          | 1         | 1.61%   |
| LG Electronics LCD Monitor LX20D 1600x1200                           | 1         | 1.61%   |
| LG Electronics LCD Monitor LG HDR WQHD+ 3840x1600                    | 1         | 1.61%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch         | 1         | 1.61%   |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch         | 1         | 1.61%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch         | 1         | 1.61%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD027B 1600x900 380x210mm 17.1-inch          | 1         | 1.61%   |
| LG Display LCD Monitor LGD0213 1600x900 310x170mm 13.9-inch          | 1         | 1.61%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 1         | 1.61%   |
| Lenovo Group Limited LCD Monitor 1920x1080                           | 1         | 1.61%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch          | 1         | 1.61%   |
| Iiyama PL2888UH IVM7104 3840x2160 620x340mm 27.8-inch                | 1         | 1.61%   |
| Hewlett-Packard Z27n G2 HPN348A 2560x1440 600x340mm 27.2-inch        | 1         | 1.61%   |
| Hewlett-Packard w2216 HWP280C 1680x1050 470x290mm 21.7-inch          | 1         | 1.61%   |
| Hewlett-Packard LCD Monitor Z24n 1920x1200                           | 1         | 1.61%   |
| Hewlett-Packard LCD Monitor E241i 1920x1200                          | 1         | 1.61%   |
| Hewlett-Packard L2335 HWP2615 1920x1200 500x310mm 23.2-inch          | 1         | 1.61%   |
| Hewlett-Packard E243i HPN3463 1920x1200 520x320mm 24.0-inch          | 1         | 1.61%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch           | 1         | 1.61%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                | 1         | 1.61%   |
| Gigabyte Technology M28U GBT2800 3840x2160 630x360mm 28.6-inch       | 1         | 1.61%   |
| Dell UP2715K DEL40B8 3840x2160 600x340mm 27.2-inch                   | 1         | 1.61%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                    | 1         | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 16        | 27.59%  |
| 3840x2160 (4K)     | 8         | 13.79%  |
| 1920x1200 (WUXGA)  | 6         | 10.34%  |
| 1366x768 (WXGA)    | 6         | 10.34%  |
| 2560x1440 (QHD)    | 5         | 8.62%   |
| 1600x900 (HD+)     | 4         | 6.9%    |
| 3840x1080          | 2         | 3.45%   |
| 3440x1440          | 2         | 3.45%   |
| 2736x1824          | 2         | 3.45%   |
| Unknown            | 2         | 3.45%   |
| 3840x1600          | 1         | 1.72%   |
| 1920x1280          | 1         | 1.72%   |
| 1680x1050 (WSXGA+) | 1         | 1.72%   |
| 1600x1200          | 1         | 1.72%   |
| 1440x900 (WXGA+)   | 1         | 1.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 8         | 14.81%  |
| Unknown | 8         | 14.81%  |
| 13      | 7         | 12.96%  |
| 27      | 6         | 11.11%  |
| 24      | 4         | 7.41%   |
| 23      | 4         | 7.41%   |
| 21      | 4         | 7.41%   |
| 17      | 3         | 5.56%   |
| 12      | 3         | 5.56%   |
| 14      | 2         | 3.7%    |
| 34      | 1         | 1.85%   |
| 32      | 1         | 1.85%   |
| 28      | 1         | 1.85%   |
| 11      | 1         | 1.85%   |
| 10      | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 24.07%  |
| 501-600     | 12        | 22.22%  |
| 201-300     | 9         | 16.67%  |
| Unknown     | 8         | 14.81%  |
| 401-500     | 4         | 7.41%   |
| 601-700     | 3         | 5.56%   |
| 351-400     | 3         | 5.56%   |
| 701-800     | 2         | 3.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 32        | 64%     |
| Unknown | 8         | 16%     |
| 16/10   | 6         | 12%     |
| 3/2     | 3         | 6%      |
| 21/9    | 1         | 2%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 8         | 15.09%  |
| 91-100         | 8         | 15.09%  |
| Unknown        | 8         | 15.09%  |
| 81-90          | 7         | 13.21%  |
| 301-350        | 6         | 11.32%  |
| 61-70          | 3         | 5.66%   |
| 351-500        | 3         | 5.66%   |
| 251-300        | 3         | 5.66%   |
| 121-130        | 3         | 5.66%   |
| 71-80          | 2         | 3.77%   |
| 51-60          | 2         | 3.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 14        | 25.45%  |
| 101-120       | 11        | 20%     |
| 51-100        | 9         | 16.36%  |
| Unknown       | 8         | 14.55%  |
| 161-240       | 7         | 12.73%  |
| More than 240 | 4         | 7.27%   |
| 1-50          | 2         | 3.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 154       | 73.68%  |
| 1     | 45        | 21.53%  |
| 2     | 9         | 4.31%   |
| 3     | 1         | 0.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 165       | 59.35%  |
| Realtek Semiconductor    | 56        | 20.14%  |
| Broadcom                 | 26        | 9.35%   |
| Qualcomm Atheros         | 10        | 3.6%    |
| TP-Link                  | 2         | 0.72%   |
| Ralink Technology        | 2         | 0.72%   |
| Sierra Wireless          | 1         | 0.36%   |
| Senao                    | 1         | 0.36%   |
| NetXen Incorporated      | 1         | 0.36%   |
| Microsoft                | 1         | 0.36%   |
| Mellanox Technologies    | 1         | 0.36%   |
| MediaTek                 | 1         | 0.36%   |
| Marvell Technology Group | 1         | 0.36%   |
| JMicron Technology       | 1         | 0.36%   |
| IMC Networks             | 1         | 0.36%   |
| Hewlett-Packard          | 1         | 0.36%   |
| Google                   | 1         | 0.36%   |
| Edimax Technology        | 1         | 0.36%   |
| D-Link System            | 1         | 0.36%   |
| Chelsio Communications   | 1         | 0.36%   |
| Apple                    | 1         | 0.36%   |
| American Megatrends      | 1         | 0.36%   |
| AMD                      | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 49        | 14.16%  |
| Intel I211 Gigabit Network Connection                                         | 26        | 7.51%   |
| Intel I210 Gigabit Network Connection                                         | 22        | 6.36%   |
| Intel Ethernet Controller I226-V                                              | 17        | 4.91%   |
| Intel I350 Gigabit Network Connection                                         | 13        | 3.76%   |
| Intel 82574L Gigabit Network Connection                                       | 12        | 3.47%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 10        | 2.89%   |
| Intel Ethernet Connection I217-LM                                             | 9         | 2.6%    |
| Intel 82580 Gigabit Network Connection                                        | 8         | 2.31%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7         | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 2.02%   |
| Intel Wireless 7260                                                           | 6         | 1.73%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 1.45%   |
| Intel Wireless 8260                                                           | 4         | 1.16%   |
| Intel Wi-Fi 6 AX200                                                           | 4         | 1.16%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 1.16%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 1.16%   |
| Intel 82576 Gigabit Network Connection                                        | 4         | 1.16%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 0.87%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 3         | 0.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 3         | 0.87%   |
| Intel Ethernet Controller I225-V                                              | 3         | 0.87%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 0.87%   |
| Intel Ethernet Connection I217-V                                              | 3         | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 3         | 0.87%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 3         | 0.87%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 0.87%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 3         | 0.87%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 3         | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.58%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 0.58%   |
| Intel Wireless 7265                                                           | 2         | 0.58%   |
| Intel Wireless 3165                                                           | 2         | 0.58%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 2         | 0.58%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 2         | 0.58%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 0.58%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 55.07%  |
| Realtek Semiconductor | 8         | 11.59%  |
| Qualcomm Atheros      | 8         | 11.59%  |
| Broadcom              | 7         | 10.14%  |
| TP-Link               | 2         | 2.9%    |
| Ralink Technology     | 2         | 2.9%    |
| Sierra Wireless       | 1         | 1.45%   |
| Senao                 | 1         | 1.45%   |
| IMC Networks          | 1         | 1.45%   |
| Edimax Technology     | 1         | 1.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                             | 6         | 8.57%   |
| Intel Wireless 8260                                             | 4         | 5.71%   |
| Intel Wi-Fi 6 AX200                                             | 4         | 5.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 3         | 4.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 3         | 4.29%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                 | 3         | 4.29%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 3         | 4.29%   |
| Broadcom BCM43228 802.11a/b/g/n                                 | 3         | 4.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2         | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 2         | 2.86%   |
| Intel Wireless 7265                                             | 2         | 2.86%   |
| Intel Wireless 3165                                             | 2         | 2.86%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 2         | 2.86%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 2         | 2.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                 | 2         | 2.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 2         | 2.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 2         | 2.86%   |
| Intel Centrino Advanced-N 6200                                  | 2         | 2.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                    | 1         | 1.43%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 1         | 1.43%   |
| Sierra Wireless EM7345 4G LTE                                   | 1         | 1.43%   |
| Senao EUB9801 802.11abgn Wireless Adapter [Ralink RT3572]       | 1         | 1.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 1         | 1.43%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 1         | 1.43%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 1         | 1.43%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 1         | 1.43%   |
| Ralink RT5370 Wireless Adapter                                  | 1         | 1.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                           | 1         | 1.43%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1         | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 1         | 1.43%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 1         | 1.43%   |
| Intel Wireless 8265 / 8275                                      | 1         | 1.43%   |
| Intel WiFi Link 5100                                            | 1         | 1.43%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 1         | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 1         | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 1         | 1.43%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 1         | 1.43%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 1         | 1.43%   |
| Broadcom BCM43224 802.11a/b/g/n                                 | 1         | 1.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 144       | 62.88%  |
| Realtek Semiconductor    | 54        | 23.58%  |
| Broadcom                 | 21        | 9.17%   |
| Qualcomm Atheros         | 2         | 0.87%   |
| Microsoft                | 1         | 0.44%   |
| MediaTek                 | 1         | 0.44%   |
| Marvell Technology Group | 1         | 0.44%   |
| JMicron Technology       | 1         | 0.44%   |
| D-Link System            | 1         | 0.44%   |
| Apple                    | 1         | 0.44%   |
| American Megatrends      | 1         | 0.44%   |
| AMD                      | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 49        | 18.08%  |
| Intel I211 Gigabit Network Connection                                         | 26        | 9.59%   |
| Intel I210 Gigabit Network Connection                                         | 22        | 8.12%   |
| Intel Ethernet Controller I226-V                                              | 17        | 6.27%   |
| Intel I350 Gigabit Network Connection                                         | 13        | 4.8%    |
| Intel 82574L Gigabit Network Connection                                       | 12        | 4.43%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 10        | 3.69%   |
| Intel Ethernet Connection I217-LM                                             | 9         | 3.32%   |
| Intel 82580 Gigabit Network Connection                                        | 8         | 2.95%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7         | 2.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 2.58%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 1.85%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 1.48%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 1.48%   |
| Intel 82576 Gigabit Network Connection                                        | 4         | 1.48%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 1.48%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 3         | 1.11%   |
| Intel Ethernet Controller I225-V                                              | 3         | 1.11%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.11%   |
| Intel Ethernet Connection I217-V                                              | 3         | 1.11%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 3         | 1.11%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 1.11%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.74%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2         | 0.74%   |
| Intel Ethernet Connection I218-V                                              | 2         | 0.74%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.74%   |
| Intel 82583V Gigabit Network Connection                                       | 2         | 0.74%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.74%   |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 0.74%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 2         | 0.74%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.37%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.37%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                            | 1         | 0.37%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1         | 0.37%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 1         | 0.37%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 193       | 73.66%  |
| WiFi     | 64        | 24.43%  |
| Unknown  | 5         | 1.91%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 182       | 86.26%  |
| WiFi     | 29        | 13.74%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 64        | 30.33%  |
| 4     | 45        | 21.33%  |
| 3     | 30        | 14.22%  |
| 1     | 30        | 14.22%  |
| 6     | 16        | 7.58%   |
| 5     | 13        | 6.16%   |
| 7     | 5         | 2.37%   |
| 8     | 4         | 1.9%    |
| 13    | 1         | 0.47%   |
| 10    | 1         | 0.47%   |
| 9     | 1         | 0.47%   |
| 0     | 1         | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 192       | 91.43%  |
| Yes  | 18        | 8.57%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 27        | 57.45%  |
| Cambridge Silicon Radio | 4         | 8.51%   |
| Apple                   | 4         | 8.51%   |
| Broadcom                | 3         | 6.38%   |
| IMC Networks            | 2         | 4.26%   |
| Hewlett-Packard         | 2         | 4.26%   |
| Dell                    | 2         | 4.26%   |
| Realtek Semiconductor   | 1         | 2.13%   |
| MediaTek                | 1         | 2.13%   |
| Lite-On Technology      | 1         | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 12        | 25.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 4         | 8.51%   |
| Intel Wireless-AC 3168 Bluetooth                        | 3         | 6.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 3         | 6.38%   |
| Intel AX200 Bluetooth                                   | 3         | 6.38%   |
| Apple Bluetooth Host Controller                         | 3         | 6.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 2         | 4.26%   |
| Intel AX210 Bluetooth                                   | 2         | 4.26%   |
| Intel AX201 Bluetooth                                   | 2         | 4.26%   |
| Broadcom BCM2045B (BDC-2.1)                             | 2         | 4.26%   |
| Realtek Bluetooth Adapter                               | 1         | 2.13%   |
| MediaTek Bluetooth Adapter                              | 1         | 2.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1         | 2.13%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip    | 1         | 2.13%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS | 1         | 2.13%   |
| HP Broadcom 2070 Bluetooth Combo                        | 1         | 2.13%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter              | 1         | 2.13%   |
| Dell Wireless 355C Bluetooth 2.0 + EDR module           | 1         | 2.13%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module             | 1         | 2.13%   |
| Broadcom Bluetooth 4.0 Adapter                          | 1         | 2.13%   |
| Apple Broadcom Built-in Bluetooth                       | 1         | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 120       | 68.18%  |
| AMD                      | 26        | 14.77%  |
| Nvidia                   | 21        | 11.93%  |
| Realtek Semiconductor    | 2         | 1.14%   |
| Philips (or NXP)         | 1         | 0.57%   |
| Nordic Semiconductor ASA | 1         | 0.57%   |
| Lenovo                   | 1         | 0.57%   |
| Hewlett-Packard          | 1         | 0.57%   |
| GN Netcom                | 1         | 0.57%   |
| Generalplus Technology   | 1         | 0.57%   |
| BEHRINGER International  | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 14        | 6.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 5.24%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 5.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 4.76%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 4.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 4.29%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 4.29%   |
| Intel Jasper Lake HD Audio                                                                        | 8         | 3.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 3.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 2.38%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 5         | 2.38%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.38%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 2.38%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 1.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.9%    |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 4         | 1.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.43%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.43%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.43%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.43%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.43%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.43%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.43%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.43%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.95%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.95%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.95%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.48%   |
| Realtek Semiconductor Microphone(Attila) Microphone(Attila) Microphone(Attila)                    | 1         | 0.48%   |
| Philips (or NXP) Philips SHG7980                                                                  | 1         | 0.48%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.48%   |
| Nvidia MCP65 High Definition Audio                                                                | 1         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 39        | 18.75%  |
| SK hynix            | 29        | 13.94%  |
| Kingston            | 26        | 12.5%   |
| Unknown             | 24        | 11.54%  |
| Corsair             | 24        | 11.54%  |
| Micron Technology   | 19        | 9.13%   |
| Crucial             | 12        | 5.77%   |
| G.Skill             | 6         | 2.88%   |
| Kimtigo             | 4         | 1.92%   |
| Unknown             | 4         | 1.92%   |
| Ramaxel Technology  | 3         | 1.44%   |
| Hewlett-Packard     | 3         | 1.44%   |
| Elpida              | 3         | 1.44%   |
| Transcend           | 2         | 0.96%   |
| HPE                 | 2         | 0.96%   |
| GSkill              | 2         | 0.96%   |
| Toshiba             | 1         | 0.48%   |
| tigo                | 1         | 0.48%   |
| Smart Modular       | 1         | 0.48%   |
| Mushkin             | 1         | 0.48%   |
| ASint Technology    | 1         | 0.48%   |
| Apacer              | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 11        | 4.91%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s          | 4         | 1.79%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s     | 4         | 1.79%   |
| Unknown                                                 | 4         | 1.79%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s  | 3         | 1.34%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 3         | 1.34%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s              | 2         | 0.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 0.89%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s    | 2         | 0.89%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 2         | 0.89%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 0.89%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s               | 2         | 0.89%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 0.89%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s   | 2         | 0.89%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 2         | 0.89%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s   | 2         | 0.89%   |
| Samsung RAM M471A1K43CB1-CWE 8GB SODIMM DDR4 3200MT/s   | 2         | 0.89%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s | 2         | 0.89%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 2         | 0.89%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                | 2         | 0.89%   |
| Kingston RAM 9965525-116.A00LF 8GB DIMM DDR3 1600MT/s   | 2         | 0.89%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s   | 2         | 0.89%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s | 2         | 0.89%   |
| Corsair RAM CMSO4GX3M1C1600C11 4GB DIMM DDR3 1600MT/s   | 2         | 0.89%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s               | 1         | 0.45%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1332MT/s            | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR3                      | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s               | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR3 1332MT/s            | 1         | 0.45%   |
| Unknown RAM Module 1GB DIMM SDRAM                       | 1         | 0.45%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                | 1         | 0.45%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                | 1         | 0.45%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s              | 1         | 0.45%   |
| Unknown RAM Module 1024MB DIMM DDR3 1332MT/s            | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 97        | 51.05%  |
| DDR4    | 69        | 36.32%  |
| DDR5    | 8         | 4.21%   |
| DDR2    | 7         | 3.68%   |
| Unknown | 4         | 2.11%   |
| SDRAM   | 2         | 1.05%   |
| LPDDR3  | 2         | 1.05%   |
| DRAM    | 1         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 102       | 53.4%   |
| SODIMM       | 83        | 43.46%  |
| Row Of Chips | 3         | 1.57%   |
| FB-DIMM      | 2         | 1.05%   |
| Chip         | 1         | 0.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 75        | 36.76%  |
| 8192  | 67        | 32.84%  |
| 16384 | 29        | 14.22%  |
| 2048  | 20        | 9.8%    |
| 1024  | 8         | 3.92%   |
| 32768 | 5         | 2.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 53        | 26.9%   |
| 1333    | 39        | 19.8%   |
| 3200    | 20        | 10.15%  |
| 2133    | 17        | 8.63%   |
| 2400    | 15        | 7.61%   |
| 2667    | 14        | 7.11%   |
| 4800    | 8         | 4.06%   |
| 800     | 6         | 3.05%   |
| 667     | 6         | 3.05%   |
| 2666    | 5         | 2.54%   |
| Unknown | 4         | 2.03%   |
| 1334    | 2         | 1.02%   |
| 1067    | 2         | 1.02%   |
| 4400    | 1         | 0.51%   |
| 2933    | 1         | 0.51%   |
| 1867    | 1         | 0.51%   |
| 1866    | 1         | 0.51%   |
| 1332    | 1         | 0.51%   |
| 333     | 1         | 0.51%   |

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
| Chicony Electronics   | 9         | 32.14%  |
| Bison Electronics     | 5         | 17.86%  |
| Microdia              | 4         | 14.29%  |
| IMC Networks          | 3         | 10.71%  |
| Realtek Semiconductor | 2         | 7.14%   |
| Syntek                | 1         | 3.57%   |
| Suyin                 | 1         | 3.57%   |
| Quanta                | 1         | 3.57%   |
| Logitech              | 1         | 3.57%   |
| Lenovo                | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Bison Integrated Camera                  | 4         | 14.29%  |
| Microdia REDRAGON  Live Camera           | 2         | 7.14%   |
| Microdia Integrated Webcam               | 2         | 7.14%   |
| Syntek EasyCamera                        | 1         | 3.57%   |
| Suyin Asus Integrated Webcam             | 1         | 3.57%   |
| Realtek Integrated_Webcam_HD             | 1         | 3.57%   |
| Realtek Front Camera                     | 1         | 3.57%   |
| Quanta VGA WebCam                        | 1         | 3.57%   |
| Logitech Webcam C270                     | 1         | 3.57%   |
| Lenovo Integrated Webcam                 | 1         | 3.57%   |
| IMC Networks Integrated RGB Camera       | 1         | 3.57%   |
| IMC Networks HP TrueVision HD Camera     | 1         | 3.57%   |
| IMC Networks EasyCamera                  | 1         | 3.57%   |
| Chicony USB2.0 HD UVC WebCam             | 1         | 3.57%   |
| Chicony USB 2.0 VGA UVC WebCam           | 1         | 3.57%   |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 3.57%   |
| Chicony ThinkPad T490 Webcam             | 1         | 3.57%   |
| Chicony Realtek DMFT RGB                 | 1         | 3.57%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 3.57%   |
| Chicony Integrated HP HD Webcam          | 1         | 3.57%   |
| Chicony Integrated Camera                | 1         | 3.57%   |
| Chicony Camera                           | 1         | 3.57%   |
| Bison ThinkPad P50 Integrated Camera     | 1         | 3.57%   |

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
| 1     | 91        | 43.75%  |
| 0     | 64        | 30.77%  |
| 2     | 39        | 18.75%  |
| 3     | 8         | 3.85%   |
| 4     | 4         | 1.92%   |
| 5     | 2         | 0.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 127       | 69.02%  |
| Net/wireless             | 14        | 7.61%   |
| Bluetooth                | 11        | 5.98%   |
| Fingerprint reader       | 7         | 3.8%    |
| Card reader              | 7         | 3.8%    |
| Firewire controller      | 5         | 2.72%   |
| Sound                    | 4         | 2.17%   |
| Graphics card            | 3         | 1.63%   |
| Storage/ata              | 2         | 1.09%   |
| Network                  | 2         | 1.09%   |
| Net/ethernet             | 2         | 1.09%   |

