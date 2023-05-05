FreeBSD - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for FreeBSD.

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

Total: 1531

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | HX90                        | [b3300c45bc](https://bsd-hardware.info/?probe=b3300c45bc) | May 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [9d82570c34](https://bsd-hardware.info/?probe=9d82570c34) | Apr 30, 2023 |
| Dell          | 0FF3FN A00                  | [717b46840a](https://bsd-hardware.info/?probe=717b46840a) | Apr 30, 2023 |
| Dell          | 0H634K A00                  | [5e783a1c2e](https://bsd-hardware.info/?probe=5e783a1c2e) | Apr 30, 2023 |
| GVC           | DR 738                      | [21b338db1b](https://bsd-hardware.info/?probe=21b338db1b) | Apr 30, 2023 |
| MSI           | H81M-P33                    | [e28acf1164](https://bsd-hardware.info/?probe=e28acf1164) | Apr 30, 2023 |
| ASUSTek       | P5Q-E                       | [33d1b6e2d2](https://bsd-hardware.info/?probe=33d1b6e2d2) | Apr 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b0d9eaaceb](https://bsd-hardware.info/?probe=b0d9eaaceb) | Apr 30, 2023 |
| MSI           | H110M PRO-VD                | [ce8453fcce](https://bsd-hardware.info/?probe=ce8453fcce) | Apr 27, 2023 |
| Gigabyte      | B360M D2V                   | [d4881f1fb6](https://bsd-hardware.info/?probe=d4881f1fb6) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [d3373e972b](https://bsd-hardware.info/?probe=d3373e972b) | Apr 24, 2023 |
| MSI           | H81M-P33                    | [6df7a17ff2](https://bsd-hardware.info/?probe=6df7a17ff2) | Apr 23, 2023 |
| ASUSTek       | P5Q-E                       | [37564b68c3](https://bsd-hardware.info/?probe=37564b68c3) | Apr 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d44a98739c](https://bsd-hardware.info/?probe=d44a98739c) | Apr 23, 2023 |
| ASUSTek       | P8H77-V                     | [60f61f7ecb](https://bsd-hardware.info/?probe=60f61f7ecb) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [838979f891](https://bsd-hardware.info/?probe=838979f891) | Apr 20, 2023 |
| HP            | 158B                        | [40fe372619](https://bsd-hardware.info/?probe=40fe372619) | Apr 20, 2023 |
| ASUSTek       | Pro B560M-C                 | [b341a9c9c9](https://bsd-hardware.info/?probe=b341a9c9c9) | Apr 19, 2023 |
| Lenovo        | YangTianM6880N              | [a567c3062c](https://bsd-hardware.info/?probe=a567c3062c) | Apr 18, 2023 |
| MSI           | H81M-P33                    | [e285cc821f](https://bsd-hardware.info/?probe=e285cc821f) | Apr 16, 2023 |
| ASUSTek       | P5Q-E                       | [b79bdd39da](https://bsd-hardware.info/?probe=b79bdd39da) | Apr 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e6734bf5e3](https://bsd-hardware.info/?probe=e6734bf5e3) | Apr 16, 2023 |
| Dell          | 09KPNV A01                  | [cf533da9bf](https://bsd-hardware.info/?probe=cf533da9bf) | Apr 16, 2023 |
| ASUSTek       | PRIME X299-A II             | [8c345e7a24](https://bsd-hardware.info/?probe=8c345e7a24) | Apr 14, 2023 |
| Unknown       | Unknown                     | [926ab149ae](https://bsd-hardware.info/?probe=926ab149ae) | Apr 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [e2b6422180](https://bsd-hardware.info/?probe=e2b6422180) | Apr 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [f54d0b103e](https://bsd-hardware.info/?probe=f54d0b103e) | Apr 13, 2023 |
| Unknown       | Unknown                     | [c960f2dc8b](https://bsd-hardware.info/?probe=c960f2dc8b) | Apr 12, 2023 |
| HP            | 212B                        | [0fb2a36b23](https://bsd-hardware.info/?probe=0fb2a36b23) | Apr 12, 2023 |
| MSI           | H81M-P33                    | [90ab4216eb](https://bsd-hardware.info/?probe=90ab4216eb) | Apr 09, 2023 |
| ASUSTek       | P5Q-E                       | [62358071bf](https://bsd-hardware.info/?probe=62358071bf) | Apr 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a06682a305](https://bsd-hardware.info/?probe=a06682a305) | Apr 09, 2023 |
| HP            | 212B                        | [6dc537109d](https://bsd-hardware.info/?probe=6dc537109d) | Apr 09, 2023 |
| Unknown       | Unknown                     | [f96c113329](https://bsd-hardware.info/?probe=f96c113329) | Apr 08, 2023 |
| ASUSTek       | PRIME B450M-K II            | [ee2b566f14](https://bsd-hardware.info/?probe=ee2b566f14) | Apr 04, 2023 |
| Unknown       | Unknown                     | [c801b9e5af](https://bsd-hardware.info/?probe=c801b9e5af) | Apr 03, 2023 |
| Unknown       | Unknown                     | [9b2420726f](https://bsd-hardware.info/?probe=9b2420726f) | Apr 03, 2023 |
| HP            | 212B                        | [00c0cbbc9a](https://bsd-hardware.info/?probe=00c0cbbc9a) | Apr 03, 2023 |
| Unknown       | Unknown                     | [414cbf5935](https://bsd-hardware.info/?probe=414cbf5935) | Apr 03, 2023 |
| Unknown       | Unknown                     | [6b79c64c73](https://bsd-hardware.info/?probe=6b79c64c73) | Apr 03, 2023 |
| Gigabyte      | GB-BSi3-1115G4              | [2a7e5e0e71](https://bsd-hardware.info/?probe=2a7e5e0e71) | Apr 02, 2023 |
| MSI           | B450M MORTAR MAX            | [01bf5e8678](https://bsd-hardware.info/?probe=01bf5e8678) | Apr 02, 2023 |
| MSI           | H81M-P33                    | [0013b5dfa4](https://bsd-hardware.info/?probe=0013b5dfa4) | Apr 02, 2023 |
| ASUSTek       | P5Q-E                       | [ff7383d618](https://bsd-hardware.info/?probe=ff7383d618) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d4cc6cf349](https://bsd-hardware.info/?probe=d4cc6cf349) | Apr 02, 2023 |
| ASRock        | X570S PG Riptide            | [8ccb321056](https://bsd-hardware.info/?probe=8ccb321056) | Apr 01, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c7944c3ce9](https://bsd-hardware.info/?probe=c7944c3ce9) | Mar 31, 2023 |
| SolidRun      | CEX7 Platform               | [8e2e4d6686](https://bsd-hardware.info/?probe=8e2e4d6686) | Mar 31, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [3c3a780d95](https://bsd-hardware.info/?probe=3c3a780d95) | Mar 31, 2023 |
| ASRockRack    | EPYCD8-2T                   | [75f414997a](https://bsd-hardware.info/?probe=75f414997a) | Mar 31, 2023 |
| HP            | 339A                        | [ad10416fe3](https://bsd-hardware.info/?probe=ad10416fe3) | Mar 31, 2023 |
| Biostar       | TH67B                       | [234c5e0b83](https://bsd-hardware.info/?probe=234c5e0b83) | Mar 31, 2023 |
| ASRock        | X570M Pro4                  | [1d7c737c38](https://bsd-hardware.info/?probe=1d7c737c38) | Mar 29, 2023 |
| Alienware     | 049PDM A00                  | [139d115cdb](https://bsd-hardware.info/?probe=139d115cdb) | Mar 29, 2023 |
| Shuttle       | FH110                       | [4fa8a9cc08](https://bsd-hardware.info/?probe=4fa8a9cc08) | Mar 28, 2023 |
| ASRock        | X570S PG Riptide            | [0d66edbd38](https://bsd-hardware.info/?probe=0d66edbd38) | Mar 27, 2023 |
| Dell          | 0VD5HY A00                  | [1b54a68123](https://bsd-hardware.info/?probe=1b54a68123) | Mar 26, 2023 |
| MSI           | H81M-P33                    | [f07e9fd36c](https://bsd-hardware.info/?probe=f07e9fd36c) | Mar 26, 2023 |
| ASUSTek       | P5Q-E                       | [3f21567fdf](https://bsd-hardware.info/?probe=3f21567fdf) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [38a22651c6](https://bsd-hardware.info/?probe=38a22651c6) | Mar 26, 2023 |
| HP            | 1497                        | [08daaf3be1](https://bsd-hardware.info/?probe=08daaf3be1) | Mar 25, 2023 |
| HP            | 21B4 A01                    | [8de4b8231a](https://bsd-hardware.info/?probe=8de4b8231a) | Mar 25, 2023 |
| HP            | 1497                        | [fc6a7ebc91](https://bsd-hardware.info/?probe=fc6a7ebc91) | Mar 25, 2023 |
| HP            | 1497                        | [e98b5284d9](https://bsd-hardware.info/?probe=e98b5284d9) | Mar 25, 2023 |
| HP            | 3397                        | [a3a77965fc](https://bsd-hardware.info/?probe=a3a77965fc) | Mar 23, 2023 |
| ASRock        | B550M Pro4                  | [4dc54510d2](https://bsd-hardware.info/?probe=4dc54510d2) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | [cab50cddd5](https://bsd-hardware.info/?probe=cab50cddd5) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | [ff4dda40eb](https://bsd-hardware.info/?probe=ff4dda40eb) | Mar 19, 2023 |
| MSI           | H81M-P33                    | [17f0f138ee](https://bsd-hardware.info/?probe=17f0f138ee) | Mar 19, 2023 |
| ASUSTek       | P5Q-E                       | [da50d91be4](https://bsd-hardware.info/?probe=da50d91be4) | Mar 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [726abe2f1d](https://bsd-hardware.info/?probe=726abe2f1d) | Mar 19, 2023 |
| HP            | 212B                        | [d4d93ad679](https://bsd-hardware.info/?probe=d4d93ad679) | Mar 19, 2023 |
| GVC           | DR 738                      | [88455ed9e7](https://bsd-hardware.info/?probe=88455ed9e7) | Mar 18, 2023 |
| HP            | 3397                        | [2851f91f5f](https://bsd-hardware.info/?probe=2851f91f5f) | Mar 17, 2023 |
| ASUSTek       | PRIME X370-PRO              | [49764ec5fa](https://bsd-hardware.info/?probe=49764ec5fa) | Mar 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [a8a9ed7f9e](https://bsd-hardware.info/?probe=a8a9ed7f9e) | Mar 13, 2023 |
| HP            | 0AA8h                       | [15ddd97321](https://bsd-hardware.info/?probe=15ddd97321) | Mar 12, 2023 |
| Supermicro    | X7DWE                       | [e40b569ff7](https://bsd-hardware.info/?probe=e40b569ff7) | Mar 12, 2023 |
| MSI           | H81M-P33                    | [12dbc1a2b3](https://bsd-hardware.info/?probe=12dbc1a2b3) | Mar 12, 2023 |
| ASUSTek       | P5Q-E                       | [bcd9058821](https://bsd-hardware.info/?probe=bcd9058821) | Mar 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d93ae717cc](https://bsd-hardware.info/?probe=d93ae717cc) | Mar 12, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [c8abf1f5bf](https://bsd-hardware.info/?probe=c8abf1f5bf) | Mar 11, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3548f4efa2](https://bsd-hardware.info/?probe=3548f4efa2) | Mar 11, 2023 |
| MSI           | PRO H610M-B DDR4            | [654bdb4eb2](https://bsd-hardware.info/?probe=654bdb4eb2) | Mar 10, 2023 |
| Gigabyte      | B360M D2V                   | [6ac60b8104](https://bsd-hardware.info/?probe=6ac60b8104) | Mar 10, 2023 |
| Huanan        | X99-QD4 V1.0                | [58090b9dbf](https://bsd-hardware.info/?probe=58090b9dbf) | Mar 09, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | [98fe8cc428](https://bsd-hardware.info/?probe=98fe8cc428) | Mar 09, 2023 |
| ASUSTek       | PRO B460M-C                 | [a3f77b82cc](https://bsd-hardware.info/?probe=a3f77b82cc) | Mar 05, 2023 |
| MSI           | H81M-P33                    | [dfa124b6f9](https://bsd-hardware.info/?probe=dfa124b6f9) | Mar 05, 2023 |
| ASUSTek       | P5Q-E                       | [64513c0ff5](https://bsd-hardware.info/?probe=64513c0ff5) | Mar 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ebba69095d](https://bsd-hardware.info/?probe=ebba69095d) | Mar 05, 2023 |
| ASRock        | E350M1                      | [461f8cca23](https://bsd-hardware.info/?probe=461f8cca23) | Mar 04, 2023 |
| Intel         | D510MO AAE76523-403         | [0da634580f](https://bsd-hardware.info/?probe=0da634580f) | Mar 03, 2023 |
| ASRock        | H470M-STX                   | [98096adfaa](https://bsd-hardware.info/?probe=98096adfaa) | Mar 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [d675a5bab2](https://bsd-hardware.info/?probe=d675a5bab2) | Feb 28, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | [735f2f3ece](https://bsd-hardware.info/?probe=735f2f3ece) | Feb 28, 2023 |
| Dell          | 0HHV7N A00                  | [ffbb7e1a96](https://bsd-hardware.info/?probe=ffbb7e1a96) | Feb 27, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | [b0fcea0c90](https://bsd-hardware.info/?probe=b0fcea0c90) | Feb 27, 2023 |
| MSI           | PRO H610M-B DDR4            | [e85ed3f609](https://bsd-hardware.info/?probe=e85ed3f609) | Feb 27, 2023 |
| MSI           | H81M-P33                    | [806efadc12](https://bsd-hardware.info/?probe=806efadc12) | Feb 26, 2023 |
| ASUSTek       | P5Q-E                       | [efb350b5f2](https://bsd-hardware.info/?probe=efb350b5f2) | Feb 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [62567aa5d4](https://bsd-hardware.info/?probe=62567aa5d4) | Feb 26, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [b2681fdfb4](https://bsd-hardware.info/?probe=b2681fdfb4) | Feb 23, 2023 |
| Gigabyte      | Z87X-OC-CF                  | [dca82c50d0](https://bsd-hardware.info/?probe=dca82c50d0) | Feb 23, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [e55635df08](https://bsd-hardware.info/?probe=e55635df08) | Feb 23, 2023 |
| Unknown       | Unknown                     | [9e92cf3575](https://bsd-hardware.info/?probe=9e92cf3575) | Feb 22, 2023 |
| ASRock        | X570 Taichi                 | [8eb068a097](https://bsd-hardware.info/?probe=8eb068a097) | Feb 20, 2023 |
| MSI           | H81M-P33                    | [28f48b7936](https://bsd-hardware.info/?probe=28f48b7936) | Feb 19, 2023 |
| ASUSTek       | P5Q-E                       | [b3525afaa7](https://bsd-hardware.info/?probe=b3525afaa7) | Feb 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [19c7044a7d](https://bsd-hardware.info/?probe=19c7044a7d) | Feb 19, 2023 |
| Intel         | DN2820FYK H24582-203        | [dd0d96422f](https://bsd-hardware.info/?probe=dd0d96422f) | Feb 19, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [b241a8afd7](https://bsd-hardware.info/?probe=b241a8afd7) | Feb 16, 2023 |
| ASRock        | A520M-ITX/ac                | [dd083df1a2](https://bsd-hardware.info/?probe=dd083df1a2) | Feb 16, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [6f4b514959](https://bsd-hardware.info/?probe=6f4b514959) | Feb 14, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | [d69aba5432](https://bsd-hardware.info/?probe=d69aba5432) | Feb 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [b3f41e1cb4](https://bsd-hardware.info/?probe=b3f41e1cb4) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b962baf73d](https://bsd-hardware.info/?probe=b962baf73d) | Feb 13, 2023 |
| ASUSTek       | P8Z68 DELUXE                | [f65675c771](https://bsd-hardware.info/?probe=f65675c771) | Feb 13, 2023 |
| ASUSTek       | H170I-PRO                   | [63000ada74](https://bsd-hardware.info/?probe=63000ada74) | Feb 12, 2023 |
| HP            | 212B                        | [0e13beb9f6](https://bsd-hardware.info/?probe=0e13beb9f6) | Feb 12, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [5507e05838](https://bsd-hardware.info/?probe=5507e05838) | Feb 12, 2023 |
| MSI           | H81M-P33                    | [84aff26f99](https://bsd-hardware.info/?probe=84aff26f99) | Feb 12, 2023 |
| ASUSTek       | P5Q-E                       | [4e899d9a1c](https://bsd-hardware.info/?probe=4e899d9a1c) | Feb 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d16e93b7f3](https://bsd-hardware.info/?probe=d16e93b7f3) | Feb 12, 2023 |
| ASUSTek       | PRIME H410M-K               | [d2edba8775](https://bsd-hardware.info/?probe=d2edba8775) | Feb 11, 2023 |
| Gigabyte      | Z490 VISION G               | [6f8ad1a8b9](https://bsd-hardware.info/?probe=6f8ad1a8b9) | Feb 11, 2023 |
| ASUSTek       | P7P55D DELUXE               | [dd9685a909](https://bsd-hardware.info/?probe=dd9685a909) | Feb 09, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [33af90dd93](https://bsd-hardware.info/?probe=33af90dd93) | Feb 08, 2023 |
| MSI           | B450M MORTAR MAX            | [ec37957aed](https://bsd-hardware.info/?probe=ec37957aed) | Feb 05, 2023 |
| MSI           | H81M-P33                    | [6f8f329a5b](https://bsd-hardware.info/?probe=6f8f329a5b) | Feb 05, 2023 |
| ASUSTek       | P5Q-E                       | [bd418783d4](https://bsd-hardware.info/?probe=bd418783d4) | Feb 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ec1ab0bf97](https://bsd-hardware.info/?probe=ec1ab0bf97) | Feb 05, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [6d46662662](https://bsd-hardware.info/?probe=6d46662662) | Jan 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [82ab576c6c](https://bsd-hardware.info/?probe=82ab576c6c) | Jan 31, 2023 |
| ASRock        | 970 Extreme3                | [5e2fd4b48f](https://bsd-hardware.info/?probe=5e2fd4b48f) | Jan 30, 2023 |
| MSI           | H81M-P33                    | [e6626da98c](https://bsd-hardware.info/?probe=e6626da98c) | Jan 29, 2023 |
| ASUSTek       | P5Q-E                       | [3d5ea9f313](https://bsd-hardware.info/?probe=3d5ea9f313) | Jan 29, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9b7532b795](https://bsd-hardware.info/?probe=9b7532b795) | Jan 29, 2023 |
| Dell          | 08NPPY A00                  | [1c4edf62e6](https://bsd-hardware.info/?probe=1c4edf62e6) | Jan 28, 2023 |
| Gigabyte      | B550 AORUS PRO              | [8fd7f80256](https://bsd-hardware.info/?probe=8fd7f80256) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [87e25e2abd](https://bsd-hardware.info/?probe=87e25e2abd) | Jan 26, 2023 |
| Shuttle       | DS20U                       | [71033e4a64](https://bsd-hardware.info/?probe=71033e4a64) | Jan 26, 2023 |
| IBM           | 9210MML                     | [8b7e2413ee](https://bsd-hardware.info/?probe=8b7e2413ee) | Jan 25, 2023 |
| ADI Engine... | RCC-VE                      | [e2941c00fc](https://bsd-hardware.info/?probe=e2941c00fc) | Jan 25, 2023 |
| ASUSTek       | P5Q-E                       | [26d1d923d6](https://bsd-hardware.info/?probe=26d1d923d6) | Jan 22, 2023 |
| MSI           | H81M-P33                    | [0bbc074f1c](https://bsd-hardware.info/?probe=0bbc074f1c) | Jan 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [28d8d82d34](https://bsd-hardware.info/?probe=28d8d82d34) | Jan 22, 2023 |
| Unknown       | AMD-GX3                     | [a38ff8331a](https://bsd-hardware.info/?probe=a38ff8331a) | Jan 20, 2023 |
| Unknown       | Unknown                     | [3afbfc6cea](https://bsd-hardware.info/?probe=3afbfc6cea) | Jan 20, 2023 |
| Unknown       | YL-SKUL6                    | [ef4abfe322](https://bsd-hardware.info/?probe=ef4abfe322) | Jan 20, 2023 |
| Unknown       | Unknown                     | [e13627df1a](https://bsd-hardware.info/?probe=e13627df1a) | Jan 20, 2023 |
| Unknown       | Unknown                     | [35e269ef1c](https://bsd-hardware.info/?probe=35e269ef1c) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [b528c0bbe3](https://bsd-hardware.info/?probe=b528c0bbe3) | Jan 18, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [c3281eb186](https://bsd-hardware.info/?probe=c3281eb186) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [f7de27b0ca](https://bsd-hardware.info/?probe=f7de27b0ca) | Jan 18, 2023 |
| Lenovo        | H30-05 90BJ0085SP           | [d491694079](https://bsd-hardware.info/?probe=d491694079) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [9eee9cc526](https://bsd-hardware.info/?probe=9eee9cc526) | Jan 18, 2023 |
| Intel         | DH67BL AAG10189-206         | [37ae895d75](https://bsd-hardware.info/?probe=37ae895d75) | Jan 17, 2023 |
| Intel         | DQ45CB AAE30148-302         | [349da05405](https://bsd-hardware.info/?probe=349da05405) | Jan 17, 2023 |
| HP            | 1998                        | [6c36e5e82e](https://bsd-hardware.info/?probe=6c36e5e82e) | Jan 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [7ef714a7f1](https://bsd-hardware.info/?probe=7ef714a7f1) | Jan 16, 2023 |
| MSI           | H81M-P33                    | [800b3bc34b](https://bsd-hardware.info/?probe=800b3bc34b) | Jan 15, 2023 |
| ASUSTek       | P5Q-E                       | [ffbcac312f](https://bsd-hardware.info/?probe=ffbcac312f) | Jan 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [48e7397e29](https://bsd-hardware.info/?probe=48e7397e29) | Jan 15, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [05cc17947c](https://bsd-hardware.info/?probe=05cc17947c) | Jan 15, 2023 |
| ASUSTek       | PRIME X370-PRO              | [f682e06d06](https://bsd-hardware.info/?probe=f682e06d06) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [917972b6ae](https://bsd-hardware.info/?probe=917972b6ae) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [bd60eadfc4](https://bsd-hardware.info/?probe=bd60eadfc4) | Jan 12, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [95ebd841b2](https://bsd-hardware.info/?probe=95ebd841b2) | Jan 12, 2023 |
| ASUSTek       | PRIME Z390-P                | [3126dc27f1](https://bsd-hardware.info/?probe=3126dc27f1) | Jan 12, 2023 |
| ASRockRack    | X470D4U2/1N1                | [07f15d0014](https://bsd-hardware.info/?probe=07f15d0014) | Jan 11, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [8def3dc9b2](https://bsd-hardware.info/?probe=8def3dc9b2) | Jan 09, 2023 |
| MSI           | H81M-P33                    | [585a3dc78c](https://bsd-hardware.info/?probe=585a3dc78c) | Jan 08, 2023 |
| ASUSTek       | P5Q-E                       | [1e9d8cc278](https://bsd-hardware.info/?probe=1e9d8cc278) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [490261883c](https://bsd-hardware.info/?probe=490261883c) | Jan 08, 2023 |
| MSI           | MEG Z690 UNIFY-X            | [e70cd80d11](https://bsd-hardware.info/?probe=e70cd80d11) | Jan 05, 2023 |
| Dell          | 02YYK5 A01                  | [219200b0b6](https://bsd-hardware.info/?probe=219200b0b6) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | [cc9d84d5ed](https://bsd-hardware.info/?probe=cc9d84d5ed) | Jan 05, 2023 |
| ASUSTek       | X99-DELUXE                  | [9dc3183152](https://bsd-hardware.info/?probe=9dc3183152) | Jan 04, 2023 |
| Supermicro    | X10DRiB                     | [d120c268f7](https://bsd-hardware.info/?probe=d120c268f7) | Jan 04, 2023 |
| Supermicro    | X10DRi-T                    | [3bd4e1dc9c](https://bsd-hardware.info/?probe=3bd4e1dc9c) | Jan 04, 2023 |
| HP            | ProLiant MicroServer Gen... | [409d119307](https://bsd-hardware.info/?probe=409d119307) | Jan 02, 2023 |
| Intel         | DH77KC AAG39641-400         | [d66b90249d](https://bsd-hardware.info/?probe=d66b90249d) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [1697219032](https://bsd-hardware.info/?probe=1697219032) | Jan 02, 2023 |
| Shuttle       | DS20U                       | [a5aa09e49f](https://bsd-hardware.info/?probe=a5aa09e49f) | Jan 01, 2023 |
| MSI           | H81M-P33                    | [0a57dcce99](https://bsd-hardware.info/?probe=0a57dcce99) | Jan 01, 2023 |
| ASUSTek       | P5Q-E                       | [d3306559de](https://bsd-hardware.info/?probe=d3306559de) | Jan 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [772779fadf](https://bsd-hardware.info/?probe=772779fadf) | Jan 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [ab7e64f657](https://bsd-hardware.info/?probe=ab7e64f657) | Dec 31, 2022 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | [ac867149f2](https://bsd-hardware.info/?probe=ac867149f2) | Dec 31, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [d22c37fa81](https://bsd-hardware.info/?probe=d22c37fa81) | Dec 29, 2022 |
| MSI           | H270 GAMING M3              | [5d14519e73](https://bsd-hardware.info/?probe=5d14519e73) | Dec 28, 2022 |
| MSI           | H270 GAMING M3              | [5dcdab1ee3](https://bsd-hardware.info/?probe=5dcdab1ee3) | Dec 28, 2022 |
| HP            | ProLiant MicroServer        | [50c8cb79f7](https://bsd-hardware.info/?probe=50c8cb79f7) | Dec 26, 2022 |
| ASUSTek       | P5Q-E                       | [bc829dbb1a](https://bsd-hardware.info/?probe=bc829dbb1a) | Dec 25, 2022 |
| MSI           | H81M-P33                    | [f73a37ab81](https://bsd-hardware.info/?probe=f73a37ab81) | Dec 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2e842ddb27](https://bsd-hardware.info/?probe=2e842ddb27) | Dec 25, 2022 |
| Supermicro    | X10SRH-CLN4FA               | [84c360ad02](https://bsd-hardware.info/?probe=84c360ad02) | Dec 24, 2022 |
| HP            | ProLiant MicroServer Gen... | [a2bc442acd](https://bsd-hardware.info/?probe=a2bc442acd) | Dec 23, 2022 |
| Unknown       | Unknown                     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| Supermicro    | X9DR3-F                     | [b8c89bdca8](https://bsd-hardware.info/?probe=b8c89bdca8) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | [b0d1792185](https://bsd-hardware.info/?probe=b0d1792185) | Dec 21, 2022 |
| ASRock        | 4X4-4000 Series             | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| HP            | ProLiant MicroServer Gen... | [8de4ff8626](https://bsd-hardware.info/?probe=8de4ff8626) | Dec 20, 2022 |
| Dell          | 09KPNV A01                  | [0eea35e069](https://bsd-hardware.info/?probe=0eea35e069) | Dec 19, 2022 |
| HP            | ProLiant MicroServer        | [b730e64d4a](https://bsd-hardware.info/?probe=b730e64d4a) | Dec 19, 2022 |
| Acer          | Veriton M680G               | [cb44a9e848](https://bsd-hardware.info/?probe=cb44a9e848) | Dec 19, 2022 |
| Acer          | Veriton M680G               | [f7184d9158](https://bsd-hardware.info/?probe=f7184d9158) | Dec 19, 2022 |
| ASRock        | B660M-ITX/ac                | [f6c8eb4e18](https://bsd-hardware.info/?probe=f6c8eb4e18) | Dec 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c1b0b83306](https://bsd-hardware.info/?probe=c1b0b83306) | Dec 18, 2022 |
| MSI           | H81M-P33                    | [78e4743abd](https://bsd-hardware.info/?probe=78e4743abd) | Dec 18, 2022 |
| ASUSTek       | P5Q-E                       | [f232e5746e](https://bsd-hardware.info/?probe=f232e5746e) | Dec 18, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [108c9de5cc](https://bsd-hardware.info/?probe=108c9de5cc) | Dec 18, 2022 |
| BESSTAR Te... | UM350                       | [b7e599f99d](https://bsd-hardware.info/?probe=b7e599f99d) | Dec 17, 2022 |
| Unknown       | Unknown                     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| HP            | ProLiant MicroServer        | [617f431099](https://bsd-hardware.info/?probe=617f431099) | Dec 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [f52a3d3fa6](https://bsd-hardware.info/?probe=f52a3d3fa6) | Dec 13, 2022 |
| ASUSTek       | PRIME H410M-A               | [f51b401c31](https://bsd-hardware.info/?probe=f51b401c31) | Dec 13, 2022 |
| Huanan        | X99-F8D V2.4                | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [73cb5d86bc](https://bsd-hardware.info/?probe=73cb5d86bc) | Dec 12, 2022 |
| Biostar       | A68N-5600E                  | [5274876096](https://bsd-hardware.info/?probe=5274876096) | Dec 11, 2022 |
| MSI           | H81M-P33                    | [1f110891d0](https://bsd-hardware.info/?probe=1f110891d0) | Dec 11, 2022 |
| ASUSTek       | P5Q-E                       | [028383847e](https://bsd-hardware.info/?probe=028383847e) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [99502ebe9a](https://bsd-hardware.info/?probe=99502ebe9a) | Dec 11, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [1d8397a653](https://bsd-hardware.info/?probe=1d8397a653) | Dec 10, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [c30f53fc6d](https://bsd-hardware.info/?probe=c30f53fc6d) | Dec 09, 2022 |
| ASUSTek       | P8H77-V LE                  | [10b6c81bce](https://bsd-hardware.info/?probe=10b6c81bce) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [c953c78309](https://bsd-hardware.info/?probe=c953c78309) | Dec 07, 2022 |
| HP            | 82A2                        | [c612b7e283](https://bsd-hardware.info/?probe=c612b7e283) | Dec 06, 2022 |
| Huanan        | X99-F8D V2.4                | [f6685811a3](https://bsd-hardware.info/?probe=f6685811a3) | Dec 05, 2022 |
| MSI           | H81M-P33                    | [d72a45fb8f](https://bsd-hardware.info/?probe=d72a45fb8f) | Dec 04, 2022 |
| ASUSTek       | P5Q-E                       | [595d174631](https://bsd-hardware.info/?probe=595d174631) | Dec 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8ee41750dc](https://bsd-hardware.info/?probe=8ee41750dc) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [aeb690b9f3](https://bsd-hardware.info/?probe=aeb690b9f3) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [d4e60c5984](https://bsd-hardware.info/?probe=d4e60c5984) | Dec 03, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | [087264570d](https://bsd-hardware.info/?probe=087264570d) | Nov 30, 2022 |
| Lenovo        | MAHOBAY                     | [1d61d0cf62](https://bsd-hardware.info/?probe=1d61d0cf62) | Nov 29, 2022 |
| ASRockRack    | X470D4U                     | [38d7f55ef7](https://bsd-hardware.info/?probe=38d7f55ef7) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | [929e4bda1e](https://bsd-hardware.info/?probe=929e4bda1e) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | [7c9ee800c5](https://bsd-hardware.info/?probe=7c9ee800c5) | Nov 29, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [378270eba0](https://bsd-hardware.info/?probe=378270eba0) | Nov 28, 2022 |
| MSI           | H81M-P33                    | [597d48d1c9](https://bsd-hardware.info/?probe=597d48d1c9) | Nov 27, 2022 |
| ASUSTek       | P5Q-E                       | [10d76fd431](https://bsd-hardware.info/?probe=10d76fd431) | Nov 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [383341b2f1](https://bsd-hardware.info/?probe=383341b2f1) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [c93690c7ca](https://bsd-hardware.info/?probe=c93690c7ca) | Nov 27, 2022 |
| Shuttle       | FZ270                       | [04a7f49322](https://bsd-hardware.info/?probe=04a7f49322) | Nov 27, 2022 |
| Shuttle       | FZ270                       | [10016f39b9](https://bsd-hardware.info/?probe=10016f39b9) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [675c9fdf94](https://bsd-hardware.info/?probe=675c9fdf94) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [a337eb9e5f](https://bsd-hardware.info/?probe=a337eb9e5f) | Nov 27, 2022 |
| Shuttle       | FH270                       | [192351ac6f](https://bsd-hardware.info/?probe=192351ac6f) | Nov 27, 2022 |
| Shuttle       | FH270                       | [3b68d89092](https://bsd-hardware.info/?probe=3b68d89092) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [5f0b8df8d0](https://bsd-hardware.info/?probe=5f0b8df8d0) | Nov 27, 2022 |
| Dell          | 0PTTT9 A01                  | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| ASRock        | B450M-HDV                   | [d0009172b1](https://bsd-hardware.info/?probe=d0009172b1) | Nov 24, 2022 |
| ASRock        | B450M-HDV                   | [25cc0129d9](https://bsd-hardware.info/?probe=25cc0129d9) | Nov 24, 2022 |
| Dell          | 0T7D40 A01                  | [45d96a0b5a](https://bsd-hardware.info/?probe=45d96a0b5a) | Nov 24, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | [e55eb53894](https://bsd-hardware.info/?probe=e55eb53894) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f7129f1c87](https://bsd-hardware.info/?probe=f7129f1c87) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [17aa370584](https://bsd-hardware.info/?probe=17aa370584) | Nov 21, 2022 |
| MSI           | H81M-P33                    | [d3303d1962](https://bsd-hardware.info/?probe=d3303d1962) | Nov 20, 2022 |
| ASUSTek       | P5Q-E                       | [b1512a254c](https://bsd-hardware.info/?probe=b1512a254c) | Nov 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [521e5ffa8e](https://bsd-hardware.info/?probe=521e5ffa8e) | Nov 20, 2022 |
| TOPFEEL       | H110D4-P1                   | [90b1dfc430](https://bsd-hardware.info/?probe=90b1dfc430) | Nov 19, 2022 |
| Huanan        | X99-F8D V2.4                | [9faf79b3f3](https://bsd-hardware.info/?probe=9faf79b3f3) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | [f732942dd9](https://bsd-hardware.info/?probe=f732942dd9) | Nov 18, 2022 |
| MSI           | B450M MORTAR MAX            | [15657b37e2](https://bsd-hardware.info/?probe=15657b37e2) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | [f4a8c42773](https://bsd-hardware.info/?probe=f4a8c42773) | Nov 15, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [443891740b](https://bsd-hardware.info/?probe=443891740b) | Nov 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [6f1e732a53](https://bsd-hardware.info/?probe=6f1e732a53) | Nov 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [15e38a5ca8](https://bsd-hardware.info/?probe=15e38a5ca8) | Nov 13, 2022 |
| ASUSTek       | P5Q-E                       | [2b1175a4df](https://bsd-hardware.info/?probe=2b1175a4df) | Nov 13, 2022 |
| MSI           | H81M-P33                    | [98b0980231](https://bsd-hardware.info/?probe=98b0980231) | Nov 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [072f2a6c27](https://bsd-hardware.info/?probe=072f2a6c27) | Nov 13, 2022 |
| Huanan        | X99-F8D V2.4                | [22ec05d988](https://bsd-hardware.info/?probe=22ec05d988) | Nov 12, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [569d5b0cca](https://bsd-hardware.info/?probe=569d5b0cca) | Nov 10, 2022 |
| ASUSTek       | P5B-Deluxe                  | [87d7d4435b](https://bsd-hardware.info/?probe=87d7d4435b) | Nov 10, 2022 |
| HP            | 21B4 A01                    | [c064c50fea](https://bsd-hardware.info/?probe=c064c50fea) | Nov 09, 2022 |
| HP            | 21B4 A01                    | [e5c599dfab](https://bsd-hardware.info/?probe=e5c599dfab) | Nov 09, 2022 |
| HP            | 21B4 A01                    | [0a3ba5478b](https://bsd-hardware.info/?probe=0a3ba5478b) | Nov 09, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [c32a7b407d](https://bsd-hardware.info/?probe=c32a7b407d) | Nov 09, 2022 |
| Dell          | 09KPNV A01                  | [32331d772c](https://bsd-hardware.info/?probe=32331d772c) | Nov 08, 2022 |
| ASRock        | B450 Gaming K4              | [127e0126d1](https://bsd-hardware.info/?probe=127e0126d1) | Nov 08, 2022 |
| Google        | Zako                        | [5d4b53e2d4](https://bsd-hardware.info/?probe=5d4b53e2d4) | Nov 08, 2022 |
| ONDA          | N78G5D3 Ver:5.00            | [009bc44d12](https://bsd-hardware.info/?probe=009bc44d12) | Nov 07, 2022 |
| Acer          | RS880M05                    | [455f9b5026](https://bsd-hardware.info/?probe=455f9b5026) | Nov 07, 2022 |
| MSI           | H81M-P33                    | [750d2f53c7](https://bsd-hardware.info/?probe=750d2f53c7) | Nov 06, 2022 |
| ASUSTek       | P5Q-E                       | [e427ea787e](https://bsd-hardware.info/?probe=e427ea787e) | Nov 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c6abe84145](https://bsd-hardware.info/?probe=c6abe84145) | Nov 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d27fd3b1a7](https://bsd-hardware.info/?probe=d27fd3b1a7) | Nov 04, 2022 |
| Lenovo        | YangTianM6880N              | [2e9c3b7368](https://bsd-hardware.info/?probe=2e9c3b7368) | Nov 04, 2022 |
| BESSTAR Te... | HM80                        | [d5c5f30a2d](https://bsd-hardware.info/?probe=d5c5f30a2d) | Nov 04, 2022 |
| Unknown       | Unknown                     | [58c2f4b4f7](https://bsd-hardware.info/?probe=58c2f4b4f7) | Nov 04, 2022 |
| Gigabyte      | Z97X-UD5H                   | [d7141b866c](https://bsd-hardware.info/?probe=d7141b866c) | Nov 02, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | [bb0f8a5bfc](https://bsd-hardware.info/?probe=bb0f8a5bfc) | Oct 31, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [cce93ff157](https://bsd-hardware.info/?probe=cce93ff157) | Oct 30, 2022 |
| MSI           | H81M-P33                    | [b67d6a7bb2](https://bsd-hardware.info/?probe=b67d6a7bb2) | Oct 30, 2022 |
| ASUSTek       | P5Q-E                       | [8161bfd24d](https://bsd-hardware.info/?probe=8161bfd24d) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a0896f17e4](https://bsd-hardware.info/?probe=a0896f17e4) | Oct 30, 2022 |
| MSI           | H81M-P33                    | [626f503cad](https://bsd-hardware.info/?probe=626f503cad) | Oct 23, 2022 |
| ASUSTek       | P5Q-E                       | [2b98739799](https://bsd-hardware.info/?probe=2b98739799) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [56dac6bc80](https://bsd-hardware.info/?probe=56dac6bc80) | Oct 23, 2022 |
| Acer          | Revo RN86                   | [692ea69bab](https://bsd-hardware.info/?probe=692ea69bab) | Oct 21, 2022 |
| HP            | 18E4                        | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [348bef7dba](https://bsd-hardware.info/?probe=348bef7dba) | Oct 20, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [3e2f5956c1](https://bsd-hardware.info/?probe=3e2f5956c1) | Oct 19, 2022 |
| Unknown       | Unknown                     | [20ff21d751](https://bsd-hardware.info/?probe=20ff21d751) | Oct 18, 2022 |
| Lenovo        | 30D0 NOK                    | [d1fab8bd54](https://bsd-hardware.info/?probe=d1fab8bd54) | Oct 18, 2022 |
| TYAN Compu... | Intel 440BX/GX Rev. 4       | [8d99f317e4](https://bsd-hardware.info/?probe=8d99f317e4) | Oct 15, 2022 |
| Dell          | 0G1548 A00                  | [226af33d5b](https://bsd-hardware.info/?probe=226af33d5b) | Oct 15, 2022 |
| ASRock        | G41C-GS R2.0                | [06214241b3](https://bsd-hardware.info/?probe=06214241b3) | Oct 15, 2022 |
| ASUSTek       | PRIME X370-PRO              | [10358c7207](https://bsd-hardware.info/?probe=10358c7207) | Oct 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [b20b6c7997](https://bsd-hardware.info/?probe=b20b6c7997) | Oct 13, 2022 |
| HP            | 1589                        | [0696d30d3f](https://bsd-hardware.info/?probe=0696d30d3f) | Oct 12, 2022 |
| ASRock        | X399 Taichi                 | [c79fa6f001](https://bsd-hardware.info/?probe=c79fa6f001) | Oct 09, 2022 |
| ASRockRack    | EP2C612D16FM                | [30a582fccb](https://bsd-hardware.info/?probe=30a582fccb) | Oct 07, 2022 |
| ASUSTek       | P8B75-M                     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| ASRock        | Z77 Extreme4                | [459c674b3b](https://bsd-hardware.info/?probe=459c674b3b) | Oct 04, 2022 |
| IBM           | 9210MML                     | [a6e7d7483f](https://bsd-hardware.info/?probe=a6e7d7483f) | Oct 03, 2022 |
| HPE           | ProLiant ML30 Gen10         | [f1b45790d4](https://bsd-hardware.info/?probe=f1b45790d4) | Oct 02, 2022 |
| HP            | 212B                        | [7bc6506336](https://bsd-hardware.info/?probe=7bc6506336) | Oct 01, 2022 |
| Unknown       | Unknown                     | [bdabafdcb1](https://bsd-hardware.info/?probe=bdabafdcb1) | Oct 01, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | [8e658fe40f](https://bsd-hardware.info/?probe=8e658fe40f) | Sep 30, 2022 |
| AMI           | MNHO-048                    | [2ec6e55a75](https://bsd-hardware.info/?probe=2ec6e55a75) | Sep 28, 2022 |
| MSI           | A520M-A PRO                 | [7e75a1888b](https://bsd-hardware.info/?probe=7e75a1888b) | Sep 27, 2022 |
| ASRock        | X570M Pro4                  | [433857f5f7](https://bsd-hardware.info/?probe=433857f5f7) | Sep 27, 2022 |
| Pegatron      | H81-X1                      | [a27c76c490](https://bsd-hardware.info/?probe=a27c76c490) | Sep 25, 2022 |
| Supermicro    | X7DB8                       | [6ebc173873](https://bsd-hardware.info/?probe=6ebc173873) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | [8bbf714f6d](https://bsd-hardware.info/?probe=8bbf714f6d) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | [60d4585ece](https://bsd-hardware.info/?probe=60d4585ece) | Sep 25, 2022 |
| MSI           | Z490-A PRO                  | [dbda136daa](https://bsd-hardware.info/?probe=dbda136daa) | Sep 24, 2022 |
| NITRINOnet    | M360RUS56                   | [490b9593e0](https://bsd-hardware.info/?probe=490b9593e0) | Sep 23, 2022 |
| HP            | 21D0                        | [43fa46655e](https://bsd-hardware.info/?probe=43fa46655e) | Sep 21, 2022 |
| HP            | 21D0                        | [463e2563d7](https://bsd-hardware.info/?probe=463e2563d7) | Sep 19, 2022 |
| HP            | ProLiant ML350p Gen8        | [1a9c6a10bd](https://bsd-hardware.info/?probe=1a9c6a10bd) | Sep 19, 2022 |
| HP            | 0B54h D                     | [a24f08281d](https://bsd-hardware.info/?probe=a24f08281d) | Sep 19, 2022 |
| Gigabyte      | H410M S2 V2                 | [8de53ac515](https://bsd-hardware.info/?probe=8de53ac515) | Sep 17, 2022 |
| Unknown       | Unknown                     | [83e48aa232](https://bsd-hardware.info/?probe=83e48aa232) | Sep 16, 2022 |
| ASUSTek       | M5A88-M                     | [09b5ca588f](https://bsd-hardware.info/?probe=09b5ca588f) | Sep 16, 2022 |
| MSI           | PRESTIGE X570 CREATION      | [2b4cf189e9](https://bsd-hardware.info/?probe=2b4cf189e9) | Sep 14, 2022 |
| Intel         | D945GCLF2 AAE46416-106      | [8e2f7792eb](https://bsd-hardware.info/?probe=8e2f7792eb) | Sep 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [f023ae7ed2](https://bsd-hardware.info/?probe=f023ae7ed2) | Sep 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [baaf9cbda6](https://bsd-hardware.info/?probe=baaf9cbda6) | Sep 13, 2022 |
| HP            | 8648                        | [e7e610794c](https://bsd-hardware.info/?probe=e7e610794c) | Sep 12, 2022 |
| ASUSTek       | P5Q-E                       | [1cbbe33027](https://bsd-hardware.info/?probe=1cbbe33027) | Sep 11, 2022 |
| MSI           | H81M-P33                    | [3b668ace72](https://bsd-hardware.info/?probe=3b668ace72) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [62c287a993](https://bsd-hardware.info/?probe=62c287a993) | Sep 11, 2022 |
| ASRockRack    | X470D4U2/1N1                | [f91afdb2f3](https://bsd-hardware.info/?probe=f91afdb2f3) | Sep 09, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [98dff45d54](https://bsd-hardware.info/?probe=98dff45d54) | Sep 09, 2022 |
| ASRockRack    | X470D4U2/1N1                | [b0965df7e1](https://bsd-hardware.info/?probe=b0965df7e1) | Sep 08, 2022 |
| MSI           | H81M-P33                    | [3f7258c807](https://bsd-hardware.info/?probe=3f7258c807) | Sep 04, 2022 |
| ASUSTek       | P5Q-E                       | [cced3168c8](https://bsd-hardware.info/?probe=cced3168c8) | Sep 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [61b82d5ebb](https://bsd-hardware.info/?probe=61b82d5ebb) | Sep 04, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [df57940ad5](https://bsd-hardware.info/?probe=df57940ad5) | Sep 03, 2022 |
| Lenovo        | YangTianM6880N              | [f675498946](https://bsd-hardware.info/?probe=f675498946) | Sep 02, 2022 |
| Unknown       | HX90                        | [568468e95b](https://bsd-hardware.info/?probe=568468e95b) | Sep 01, 2022 |
| Dell          | 07T4MC A09                  | [50fbb0435c](https://bsd-hardware.info/?probe=50fbb0435c) | Aug 31, 2022 |
| Dell          | 07T4MC A09                  | [200b8d381e](https://bsd-hardware.info/?probe=200b8d381e) | Aug 31, 2022 |
| Dell          | 07T4MC A09                  | [ebc79d7728](https://bsd-hardware.info/?probe=ebc79d7728) | Aug 31, 2022 |
| Intel         | X79 V2.72A                  | [435901d8c9](https://bsd-hardware.info/?probe=435901d8c9) | Aug 29, 2022 |
| Gigabyte      | H81M-DS2                    | [75ec0260f9](https://bsd-hardware.info/?probe=75ec0260f9) | Aug 28, 2022 |
| Dell          | 07T4MC A00                  | [1060f1b6e3](https://bsd-hardware.info/?probe=1060f1b6e3) | Aug 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [5684672f5a](https://bsd-hardware.info/?probe=5684672f5a) | Aug 26, 2022 |
| ASRock        | AD2550-ITX                  | [43d0101ac4](https://bsd-hardware.info/?probe=43d0101ac4) | Aug 24, 2022 |
| Lenovo        | ThinkCentre M91p 4512A47    | [3556794570](https://bsd-hardware.info/?probe=3556794570) | Aug 23, 2022 |
| MSI           | H81M-P33                    | [89535fc84c](https://bsd-hardware.info/?probe=89535fc84c) | Aug 21, 2022 |
| ASUSTek       | P5Q-E                       | [ac2d88c2dd](https://bsd-hardware.info/?probe=ac2d88c2dd) | Aug 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b5786b8119](https://bsd-hardware.info/?probe=b5786b8119) | Aug 21, 2022 |
| ASRock        | B550 Extreme4               | [ce0d33d973](https://bsd-hardware.info/?probe=ce0d33d973) | Aug 19, 2022 |
| Gigabyte      | H61M-DS2                    | [a2fc8d9c67](https://bsd-hardware.info/?probe=a2fc8d9c67) | Aug 18, 2022 |
| Dell          | 0VG93V A00                  | [8de9fa2319](https://bsd-hardware.info/?probe=8de9fa2319) | Aug 18, 2022 |
| ASUSTek       | M4A87TD EVO                 | [c03da8657e](https://bsd-hardware.info/?probe=c03da8657e) | Aug 17, 2022 |
| Unknown       | Unknown                     | [3208aefb72](https://bsd-hardware.info/?probe=3208aefb72) | Aug 17, 2022 |
| Dell          | 042P49 A00                  | [7130975fe3](https://bsd-hardware.info/?probe=7130975fe3) | Aug 17, 2022 |
| Gigabyte      | H61M-DS2                    | [9a7d45e51c](https://bsd-hardware.info/?probe=9a7d45e51c) | Aug 16, 2022 |
| ASUSTek       | PRIME X370-PRO              | [4055810ef2](https://bsd-hardware.info/?probe=4055810ef2) | Aug 14, 2022 |
| MSI           | H81M-P33                    | [3d0836d403](https://bsd-hardware.info/?probe=3d0836d403) | Aug 14, 2022 |
| ASUSTek       | P5Q-E                       | [c50be0ecae](https://bsd-hardware.info/?probe=c50be0ecae) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4b6ad32189](https://bsd-hardware.info/?probe=4b6ad32189) | Aug 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [5d4af4fba9](https://bsd-hardware.info/?probe=5d4af4fba9) | Aug 13, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | [6884e940a1](https://bsd-hardware.info/?probe=6884e940a1) | Aug 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [1292c617d2](https://bsd-hardware.info/?probe=1292c617d2) | Aug 13, 2022 |
| ASRock        | H110M-DGS R3.0              | [0c654b6c34](https://bsd-hardware.info/?probe=0c654b6c34) | Aug 11, 2022 |
| ASRock        | X399 Taichi                 | [efd9ee1d33](https://bsd-hardware.info/?probe=efd9ee1d33) | Aug 10, 2022 |
| Dell          | 042P49 A00                  | [a38375fa97](https://bsd-hardware.info/?probe=a38375fa97) | Aug 08, 2022 |
| Dell          | 042P49 A00                  | [81a5e313cd](https://bsd-hardware.info/?probe=81a5e313cd) | Aug 08, 2022 |
| Unknown       | Unknown                     | [467bcd3c04](https://bsd-hardware.info/?probe=467bcd3c04) | Aug 07, 2022 |
| GVC           | DR 738                      | [ea08102a81](https://bsd-hardware.info/?probe=ea08102a81) | Aug 06, 2022 |
| Gigabyte      | H97M-HD3                    | [4a7705414f](https://bsd-hardware.info/?probe=4a7705414f) | Aug 06, 2022 |
| Gigabyte      | H81M-DS2                    | [5b88dea745](https://bsd-hardware.info/?probe=5b88dea745) | Aug 06, 2022 |
| Gigabyte      | P85-D3                      | [7f077abed9](https://bsd-hardware.info/?probe=7f077abed9) | Aug 02, 2022 |
| ASUSTek       | B85-PRO GAMER               | [b29e940a75](https://bsd-hardware.info/?probe=b29e940a75) | Aug 02, 2022 |
| Gigabyte      | 970A-DS3P FX                | [3c33e546bb](https://bsd-hardware.info/?probe=3c33e546bb) | Jul 31, 2022 |
| Gigabyte      | GB-BSi3-1115G4              | [4cd0769d75](https://bsd-hardware.info/?probe=4cd0769d75) | Jul 30, 2022 |
| Dell          | 0T7D40 A01                  | [bd2f6f8596](https://bsd-hardware.info/?probe=bd2f6f8596) | Jul 29, 2022 |
| Dell          | 040DDP A01                  | [5d4d3d7553](https://bsd-hardware.info/?probe=5d4d3d7553) | Jul 29, 2022 |
| HP            | 1825                        | [8c96329681](https://bsd-hardware.info/?probe=8c96329681) | Jul 24, 2022 |
| HP            | ProLiant ML310e Gen8 v2     | [6cdc79a36f](https://bsd-hardware.info/?probe=6cdc79a36f) | Jul 22, 2022 |
| ASUSTek       | Maximus VIII HERO           | [051f604f9a](https://bsd-hardware.info/?probe=051f604f9a) | Jul 21, 2022 |
| Gigabyte      | H61M-DS2                    | [3ba3cedec4](https://bsd-hardware.info/?probe=3ba3cedec4) | Jul 21, 2022 |
| Dell          | 0WR7PY A03                  | [46a6f4e8f3](https://bsd-hardware.info/?probe=46a6f4e8f3) | Jul 19, 2022 |
| Dell          | 08HPGT A02                  | [ae260e17eb](https://bsd-hardware.info/?probe=ae260e17eb) | Jul 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3bf44f4bb5](https://bsd-hardware.info/?probe=3bf44f4bb5) | Jul 17, 2022 |
| Gigabyte      | H310M S2 x.x                | [b11ca9c369](https://bsd-hardware.info/?probe=b11ca9c369) | Jul 16, 2022 |
| Acer          | Veriton X490G               | [2912c74632](https://bsd-hardware.info/?probe=2912c74632) | Jul 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [607a66e533](https://bsd-hardware.info/?probe=607a66e533) | Jul 14, 2022 |
| MouseCompu... | B360M                       | [3c22f3e91b](https://bsd-hardware.info/?probe=3c22f3e91b) | Jul 13, 2022 |
| Acer          | Veriton X490G               | [cbae2b155b](https://bsd-hardware.info/?probe=cbae2b155b) | Jul 11, 2022 |
| Acer          | Veriton X490G               | [3cd79878cd](https://bsd-hardware.info/?probe=3cd79878cd) | Jul 11, 2022 |
| ASRock        | B75 Pro3                    | [7f4fa7f74d](https://bsd-hardware.info/?probe=7f4fa7f74d) | Jul 10, 2022 |
| Unknown       | Unknown                     | [947d413e10](https://bsd-hardware.info/?probe=947d413e10) | Jul 09, 2022 |
| Intel         | DN2820FYK H24582-203        | [8a9a8cdbd0](https://bsd-hardware.info/?probe=8a9a8cdbd0) | Jul 08, 2022 |
| ASUSTek       | PRIME A520M-A II            | [0819ecdcf9](https://bsd-hardware.info/?probe=0819ecdcf9) | Jul 07, 2022 |
| ASUSTek       | PRIME A520M-A II            | [d459d3431a](https://bsd-hardware.info/?probe=d459d3431a) | Jul 07, 2022 |
| Acer          | Aspire XC-895 V:1.0         | [d67aa61a6b](https://bsd-hardware.info/?probe=d67aa61a6b) | Jul 05, 2022 |
| Acer          | Revo RN86                   | [2dc98202aa](https://bsd-hardware.info/?probe=2dc98202aa) | Jul 05, 2022 |
| ASRock        | Z490M Pro4                  | [b57457834e](https://bsd-hardware.info/?probe=b57457834e) | Jul 04, 2022 |
| Gigabyte      | Z370M D3H-CF                | [1d3db5e35a](https://bsd-hardware.info/?probe=1d3db5e35a) | Jul 04, 2022 |
| ASRock        | X300M-STX                   | [a76b64487b](https://bsd-hardware.info/?probe=a76b64487b) | Jul 01, 2022 |
| ASRock        | P67 Professional            | [3372d35113](https://bsd-hardware.info/?probe=3372d35113) | Jun 28, 2022 |
| Gigabyte      | H61MA-D3V                   | [898da0bcec](https://bsd-hardware.info/?probe=898da0bcec) | Jun 28, 2022 |
| ASUSTek       | PRIME Z590-P                | [70aea59a1b](https://bsd-hardware.info/?probe=70aea59a1b) | Jun 25, 2022 |
| ASUSTek       | PRIME Z590-P                | [c285cb7899](https://bsd-hardware.info/?probe=c285cb7899) | Jun 23, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7d054ce34f](https://bsd-hardware.info/?probe=7d054ce34f) | Jun 23, 2022 |
| MSI           | B85M-E45                    | [d9cc6cee6b](https://bsd-hardware.info/?probe=d9cc6cee6b) | Jun 21, 2022 |
| Intel         | D945GCLF2 AAE46416-104      | [84f2afeff4](https://bsd-hardware.info/?probe=84f2afeff4) | Jun 21, 2022 |
| ASUSTek       | Z87M-PLUS                   | [5e51d228ec](https://bsd-hardware.info/?probe=5e51d228ec) | Jun 21, 2022 |
| HP            | 3031h                       | [96ecd77f94](https://bsd-hardware.info/?probe=96ecd77f94) | Jun 19, 2022 |
| HP            | 3031h                       | [4da4d936b8](https://bsd-hardware.info/?probe=4da4d936b8) | Jun 19, 2022 |
| HP            | 86E9 A                      | [1d1ac2dd90](https://bsd-hardware.info/?probe=1d1ac2dd90) | Jun 16, 2022 |
| Dell          | 07KY25 A00                  | [9981217b1b](https://bsd-hardware.info/?probe=9981217b1b) | Jun 16, 2022 |
| Dell          | 0HMF7C A01                  | [ad0f6d4b31](https://bsd-hardware.info/?probe=ad0f6d4b31) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [1febab0774](https://bsd-hardware.info/?probe=1febab0774) | Jun 12, 2022 |
| Supermicro    | X9DR3-F                     | [d81151c0e8](https://bsd-hardware.info/?probe=d81151c0e8) | Jun 12, 2022 |
| ASUSTek       | Maximus VII FORMULA         | [5215d1ebb8](https://bsd-hardware.info/?probe=5215d1ebb8) | Jun 12, 2022 |
| MSI           | Z590 PRO WIFI               | [29b410eeb6](https://bsd-hardware.info/?probe=29b410eeb6) | Jun 06, 2022 |
| Gigabyte      | F2A75M-D3H                  | [ae3436167b](https://bsd-hardware.info/?probe=ae3436167b) | Jun 05, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [ff3865e01f](https://bsd-hardware.info/?probe=ff3865e01f) | Jun 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [1cc3d99da5](https://bsd-hardware.info/?probe=1cc3d99da5) | May 31, 2022 |
| NF-M2S        | ABIT                        | [bef9700756](https://bsd-hardware.info/?probe=bef9700756) | May 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [f39611345a](https://bsd-hardware.info/?probe=f39611345a) | May 30, 2022 |
| Unknown       | Unknown                     | [90b27f0ac1](https://bsd-hardware.info/?probe=90b27f0ac1) | May 29, 2022 |
| ASUSTek       | P5Q-E                       | [cf67e4079f](https://bsd-hardware.info/?probe=cf67e4079f) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8ebd281f5f](https://bsd-hardware.info/?probe=8ebd281f5f) | May 29, 2022 |
| MSI           | H81M-P33                    | [ab2181e1b4](https://bsd-hardware.info/?probe=ab2181e1b4) | May 29, 2022 |
| PC Engines    | APU3                        | [fca5a642c2](https://bsd-hardware.info/?probe=fca5a642c2) | May 28, 2022 |
| Unknown       | Unknown                     | [a56bc64f26](https://bsd-hardware.info/?probe=a56bc64f26) | May 27, 2022 |
| Unknown       | Unknown                     | [4e15ce78c8](https://bsd-hardware.info/?probe=4e15ce78c8) | May 26, 2022 |
| HP            | 158A                        | [883958cd36](https://bsd-hardware.info/?probe=883958cd36) | May 25, 2022 |
| Unknown       | Unknown                     | [78d1ad4565](https://bsd-hardware.info/?probe=78d1ad4565) | May 25, 2022 |
| ASRockRack    | E3C242D4U2-2T               | [d35f1fb7e0](https://bsd-hardware.info/?probe=d35f1fb7e0) | May 25, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [3dc5a6f7d2](https://bsd-hardware.info/?probe=3dc5a6f7d2) | May 24, 2022 |
| Dell          | 055H3G A01                  | [cc1c76afc0](https://bsd-hardware.info/?probe=cc1c76afc0) | May 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a74913bffa](https://bsd-hardware.info/?probe=a74913bffa) | May 23, 2022 |
| khadas        | edge-v                      | [60fb48e34c](https://bsd-hardware.info/?probe=60fb48e34c) | May 23, 2022 |
| khadas        | edge-v                      | [6facaa8032](https://bsd-hardware.info/?probe=6facaa8032) | May 22, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [443b1d3c3e](https://bsd-hardware.info/?probe=443b1d3c3e) | May 22, 2022 |
| MSI           | H81M-P33                    | [d5a0fd71f2](https://bsd-hardware.info/?probe=d5a0fd71f2) | May 22, 2022 |
| ASUSTek       | P5Q-E                       | [2b93a0b59f](https://bsd-hardware.info/?probe=2b93a0b59f) | May 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [becc2fddbd](https://bsd-hardware.info/?probe=becc2fddbd) | May 22, 2022 |
| GVC           | DR 738                      | [938866fb80](https://bsd-hardware.info/?probe=938866fb80) | May 21, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [819bed6cfb](https://bsd-hardware.info/?probe=819bed6cfb) | May 19, 2022 |
| Gigabyte      | H61MA-D3V                   | [f369e09063](https://bsd-hardware.info/?probe=f369e09063) | May 19, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [9c459aae41](https://bsd-hardware.info/?probe=9c459aae41) | May 19, 2022 |
| MSI           | K9N6PGM2-V2                 | [d5a6eba10b](https://bsd-hardware.info/?probe=d5a6eba10b) | May 19, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [1014f7f61c](https://bsd-hardware.info/?probe=1014f7f61c) | May 18, 2022 |
| Dell          | 0DXJD9 A01                  | [be13c9069c](https://bsd-hardware.info/?probe=be13c9069c) | May 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [edcd612c83](https://bsd-hardware.info/?probe=edcd612c83) | May 18, 2022 |
| Dell          | 07T4MC A11                  | [63d6080a31](https://bsd-hardware.info/?probe=63d6080a31) | May 17, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [b87692aeb4](https://bsd-hardware.info/?probe=b87692aeb4) | May 15, 2022 |
| ASRock        | E350M1                      | [1850fa38e0](https://bsd-hardware.info/?probe=1850fa38e0) | May 14, 2022 |
| ASRock        | E350M1                      | [4520b5034e](https://bsd-hardware.info/?probe=4520b5034e) | May 13, 2022 |
| MSI           | MS-7369                     | [c2c6bd80e8](https://bsd-hardware.info/?probe=c2c6bd80e8) | May 13, 2022 |
| Unknown       | Unknown                     | [f3ab857e43](https://bsd-hardware.info/?probe=f3ab857e43) | May 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [6a9177eef7](https://bsd-hardware.info/?probe=6a9177eef7) | May 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [11034dd80f](https://bsd-hardware.info/?probe=11034dd80f) | May 13, 2022 |
| Intel         | DH67BL AAG10189-213         | [e8d2744812](https://bsd-hardware.info/?probe=e8d2744812) | May 12, 2022 |
| HP            | ProLiant MicroServer        | [e569bffe8f](https://bsd-hardware.info/?probe=e569bffe8f) | May 12, 2022 |
| ASRock        | A320M Pro4-F                | [f307756ddf](https://bsd-hardware.info/?probe=f307756ddf) | May 11, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [224614e9ab](https://bsd-hardware.info/?probe=224614e9ab) | May 10, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [76eef59920](https://bsd-hardware.info/?probe=76eef59920) | May 10, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [5f9e266167](https://bsd-hardware.info/?probe=5f9e266167) | May 04, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [7d4dd8ba29](https://bsd-hardware.info/?probe=7d4dd8ba29) | May 04, 2022 |
| ASUSTek       | H97I-PLUS                   | [1fde9daf7d](https://bsd-hardware.info/?probe=1fde9daf7d) | May 01, 2022 |
| HP            | 1495                        | [6e0f1cc72e](https://bsd-hardware.info/?probe=6e0f1cc72e) | Apr 29, 2022 |
| MSI           | A520M-A PRO                 | [336add4fcb](https://bsd-hardware.info/?probe=336add4fcb) | Apr 28, 2022 |
| MSI           | A520M-A PRO                 | [34f2ba40e7](https://bsd-hardware.info/?probe=34f2ba40e7) | Apr 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1a475f0939](https://bsd-hardware.info/?probe=1a475f0939) | Apr 27, 2022 |
| ASRock        | X570S PG Riptide            | [928d2abb5e](https://bsd-hardware.info/?probe=928d2abb5e) | Apr 26, 2022 |
| Gigabyte      | H310M S2 x.x                | [549053284c](https://bsd-hardware.info/?probe=549053284c) | Apr 25, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | [86c4af7ca4](https://bsd-hardware.info/?probe=86c4af7ca4) | Apr 25, 2022 |
| Dell          | 0T7D40 A01                  | [7a43bfada9](https://bsd-hardware.info/?probe=7a43bfada9) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | [955922ebe2](https://bsd-hardware.info/?probe=955922ebe2) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | [4d66b2b328](https://bsd-hardware.info/?probe=4d66b2b328) | Apr 23, 2022 |
| MSI           | X570-A PRO                  | [89fcee49d9](https://bsd-hardware.info/?probe=89fcee49d9) | Apr 22, 2022 |
| HP            | 2820h                       | [d888b8b775](https://bsd-hardware.info/?probe=d888b8b775) | Apr 22, 2022 |
| Supermicro    | X9SCL/X9SCM                 | [947038b1f9](https://bsd-hardware.info/?probe=947038b1f9) | Apr 22, 2022 |
| MSI           | PRESTIGE X570 CREATION      | [28c8d07136](https://bsd-hardware.info/?probe=28c8d07136) | Apr 22, 2022 |
| Dell          | 06JWJY A01                  | [16f4cc5d53](https://bsd-hardware.info/?probe=16f4cc5d53) | Apr 20, 2022 |
| Dell          | 0T7D40 A01                  | [4ad1c07aa5](https://bsd-hardware.info/?probe=4ad1c07aa5) | Apr 19, 2022 |
| Gigabyte      | N3160ND3V                   | [eb3d850e0a](https://bsd-hardware.info/?probe=eb3d850e0a) | Apr 17, 2022 |
| ASRockRack    | C3758D4I-4L                 | [0a550ec649](https://bsd-hardware.info/?probe=0a550ec649) | Apr 17, 2022 |
| ASRockRack    | C3758D4I-4L                 | [c1e6f095a8](https://bsd-hardware.info/?probe=c1e6f095a8) | Apr 17, 2022 |
| Shuttle       | DS20U                       | [f01372719f](https://bsd-hardware.info/?probe=f01372719f) | Apr 16, 2022 |
| Shuttle       | SH570                       | [08e2af8890](https://bsd-hardware.info/?probe=08e2af8890) | Apr 16, 2022 |
| ASUSTek       | AT5NM10T-I                  | [211c3291dd](https://bsd-hardware.info/?probe=211c3291dd) | Apr 15, 2022 |
| HP            | 86E9 A                      | [be43a8efde](https://bsd-hardware.info/?probe=be43a8efde) | Apr 14, 2022 |
| HP            | ProLiant MicroServer        | [fa76da045a](https://bsd-hardware.info/?probe=fa76da045a) | Apr 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [f6bc20d345](https://bsd-hardware.info/?probe=f6bc20d345) | Apr 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [bb9129d4df](https://bsd-hardware.info/?probe=bb9129d4df) | Apr 13, 2022 |
| Intel         | DH67CL AAG10212-205         | [ecbb820987](https://bsd-hardware.info/?probe=ecbb820987) | Apr 12, 2022 |
| Alienware     | 049PDM A00                  | [6dac56f3bb](https://bsd-hardware.info/?probe=6dac56f3bb) | Apr 11, 2022 |
| Dell          | 0WR7PY A03                  | [641d1574ce](https://bsd-hardware.info/?probe=641d1574ce) | Apr 11, 2022 |
| ASRock        | X370 Taichi                 | [7f156a0671](https://bsd-hardware.info/?probe=7f156a0671) | Apr 10, 2022 |
| ASRock        | X370 Taichi                 | [a006c9e999](https://bsd-hardware.info/?probe=a006c9e999) | Apr 10, 2022 |
| MSI           | H81M-P33                    | [52abbcbc5b](https://bsd-hardware.info/?probe=52abbcbc5b) | Apr 10, 2022 |
| ASUSTek       | P5Q-E                       | [0cbb5faa2e](https://bsd-hardware.info/?probe=0cbb5faa2e) | Apr 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5d759d6436](https://bsd-hardware.info/?probe=5d759d6436) | Apr 10, 2022 |
| Intel         | DH67CL AAG10212-205         | [de2cd29be6](https://bsd-hardware.info/?probe=de2cd29be6) | Apr 10, 2022 |
| Intel         | DH67BL AAG10189-211         | [2a03c05cce](https://bsd-hardware.info/?probe=2a03c05cce) | Apr 10, 2022 |
| Intel         | DH61CR AAG14064-204         | [fa4b6b0257](https://bsd-hardware.info/?probe=fa4b6b0257) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-205         | [4436915ba0](https://bsd-hardware.info/?probe=4436915ba0) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-210         | [a01376dfc5](https://bsd-hardware.info/?probe=a01376dfc5) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-205         | [85a5d08117](https://bsd-hardware.info/?probe=85a5d08117) | Apr 09, 2022 |
| Intel         | DH67BL AAG10189-211         | [689ff6c484](https://bsd-hardware.info/?probe=689ff6c484) | Apr 09, 2022 |
| Intel         | DH55TC AAE70932-302         | [b9a45002ae](https://bsd-hardware.info/?probe=b9a45002ae) | Apr 09, 2022 |
| Intel         | DH67CL AAG10212-205         | [68f10ed8de](https://bsd-hardware.info/?probe=68f10ed8de) | Apr 09, 2022 |
| Intel         | DH67CL AAG10212-205         | [092643d1c3](https://bsd-hardware.info/?probe=092643d1c3) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-205         | [02b581994b](https://bsd-hardware.info/?probe=02b581994b) | Apr 08, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [840805d1fa](https://bsd-hardware.info/?probe=840805d1fa) | Apr 08, 2022 |
| Gigabyte      | B450M S2H                   | [ee73e0cddb](https://bsd-hardware.info/?probe=ee73e0cddb) | Apr 07, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [da64cbb0d1](https://bsd-hardware.info/?probe=da64cbb0d1) | Apr 07, 2022 |
| MSI           | MAG B550M MORTAR            | [d9ef1569d2](https://bsd-hardware.info/?probe=d9ef1569d2) | Apr 07, 2022 |
| Gigabyte      | B560M D3H                   | [99343fc0da](https://bsd-hardware.info/?probe=99343fc0da) | Apr 06, 2022 |
| HPE           | ProLiant MicroServer Gen... | [7db1501c5c](https://bsd-hardware.info/?probe=7db1501c5c) | Apr 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2d04e83ea4](https://bsd-hardware.info/?probe=2d04e83ea4) | Apr 06, 2022 |
| ASRock        | AM1H-ITX                    | [5556bf474c](https://bsd-hardware.info/?probe=5556bf474c) | Apr 06, 2022 |
| Unknown       | Unknown                     | [821456e342](https://bsd-hardware.info/?probe=821456e342) | Apr 06, 2022 |
| Unknown       | Unknown                     | [6955791aa5](https://bsd-hardware.info/?probe=6955791aa5) | Apr 06, 2022 |
| Gigabyte      | H310M S2 x.x                | [29a9462f72](https://bsd-hardware.info/?probe=29a9462f72) | Apr 04, 2022 |
| HP            | 212B                        | [33e7c65907](https://bsd-hardware.info/?probe=33e7c65907) | Apr 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1043649da9](https://bsd-hardware.info/?probe=1043649da9) | Apr 03, 2022 |
| MSI           | H81M-P33                    | [b0d11aabb7](https://bsd-hardware.info/?probe=b0d11aabb7) | Apr 03, 2022 |
| ASUSTek       | P5Q-E                       | [dbaaa0dcda](https://bsd-hardware.info/?probe=dbaaa0dcda) | Apr 03, 2022 |
| Gigabyte      | X570 AORUS PRO              | [3877a33214](https://bsd-hardware.info/?probe=3877a33214) | Apr 02, 2022 |
| Gigabyte      | X570 AORUS PRO              | [3da637e3c6](https://bsd-hardware.info/?probe=3da637e3c6) | Apr 02, 2022 |
| HP            | 158A                        | [5d463584db](https://bsd-hardware.info/?probe=5d463584db) | Mar 31, 2022 |
| ASUSTek       | PRO B460M-C                 | [0542f7a16d](https://bsd-hardware.info/?probe=0542f7a16d) | Mar 29, 2022 |
| ASUSTek       | D700SA                      | [e0d66ad9cf](https://bsd-hardware.info/?probe=e0d66ad9cf) | Mar 28, 2022 |
| MSI           | H81M-P33                    | [823d2d7336](https://bsd-hardware.info/?probe=823d2d7336) | Mar 27, 2022 |
| ASUSTek       | P5Q-E                       | [4e44bfd765](https://bsd-hardware.info/?probe=4e44bfd765) | Mar 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [51507583f6](https://bsd-hardware.info/?probe=51507583f6) | Mar 27, 2022 |
| ASUSTek       | P5KPL-CM                    | [d9e74758f3](https://bsd-hardware.info/?probe=d9e74758f3) | Mar 24, 2022 |
| MSI           | MS-A6221 100                | [ba62f48990](https://bsd-hardware.info/?probe=ba62f48990) | Mar 23, 2022 |
| ASUSTek       | M4A78T-E                    | [7c46c8e712](https://bsd-hardware.info/?probe=7c46c8e712) | Mar 23, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [4a9a28c612](https://bsd-hardware.info/?probe=4a9a28c612) | Mar 22, 2022 |
| ASRock        | H61M-VG3                    | [543bcf2d09](https://bsd-hardware.info/?probe=543bcf2d09) | Mar 22, 2022 |
| ASUSTek       | PRO B460M-C                 | [6ceff4eca1](https://bsd-hardware.info/?probe=6ceff4eca1) | Mar 21, 2022 |
| Unknown       | Unknown                     | [c4ffde79eb](https://bsd-hardware.info/?probe=c4ffde79eb) | Mar 21, 2022 |
| ASUSTek       | PRIME B550M-A               | [d0946bc53f](https://bsd-hardware.info/?probe=d0946bc53f) | Mar 21, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [d2ecb6259c](https://bsd-hardware.info/?probe=d2ecb6259c) | Mar 20, 2022 |
| ASRock        | X570 Pro4                   | [2aeeaaacfc](https://bsd-hardware.info/?probe=2aeeaaacfc) | Mar 20, 2022 |
| ASRock        | X570 Pro4                   | [4b6df22ff5](https://bsd-hardware.info/?probe=4b6df22ff5) | Mar 20, 2022 |
| MSI           | H81M-P33                    | [d9421c2715](https://bsd-hardware.info/?probe=d9421c2715) | Mar 20, 2022 |
| ASUSTek       | P5Q-E                       | [5a6cb7ab07](https://bsd-hardware.info/?probe=5a6cb7ab07) | Mar 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [12814be80b](https://bsd-hardware.info/?probe=12814be80b) | Mar 20, 2022 |
| ASUSTek       | PRIME Z590-P                | [054946738a](https://bsd-hardware.info/?probe=054946738a) | Mar 19, 2022 |
| ASUSTek       | PRIME B350M-A               | [753af67ffa](https://bsd-hardware.info/?probe=753af67ffa) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | [b23ab09f52](https://bsd-hardware.info/?probe=b23ab09f52) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | [545e5ebfc9](https://bsd-hardware.info/?probe=545e5ebfc9) | Mar 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [6d4ac7f6f5](https://bsd-hardware.info/?probe=6d4ac7f6f5) | Mar 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [3f94a005a7](https://bsd-hardware.info/?probe=3f94a005a7) | Mar 17, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [a5fd383c40](https://bsd-hardware.info/?probe=a5fd383c40) | Mar 14, 2022 |
| Huanan        | X99-F8D V2.4                | [4ef193841e](https://bsd-hardware.info/?probe=4ef193841e) | Mar 13, 2022 |
| ASUSTek       | P5K PRO                     | [fbde5657e8](https://bsd-hardware.info/?probe=fbde5657e8) | Mar 11, 2022 |
| ASRock        | Q1900B-ITX                  | [b4142103cb](https://bsd-hardware.info/?probe=b4142103cb) | Mar 10, 2022 |
| Gigabyte      | C246-WU4-CF                 | [17b3590a3f](https://bsd-hardware.info/?probe=17b3590a3f) | Mar 08, 2022 |
| Intel         | DX79TO AAG28805-401         | [431b37f050](https://bsd-hardware.info/?probe=431b37f050) | Mar 06, 2022 |
| ASUSTek       | PRIME B550M-A               | [0d2956a144](https://bsd-hardware.info/?probe=0d2956a144) | Mar 04, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [1daab68f1f](https://bsd-hardware.info/?probe=1daab68f1f) | Mar 04, 2022 |
| Intel         | D865PERL AAC27646-213       | [4e11b970ab](https://bsd-hardware.info/?probe=4e11b970ab) | Mar 03, 2022 |
| MSI           | U-100 Ver.001               | [50aba1dee8](https://bsd-hardware.info/?probe=50aba1dee8) | Mar 03, 2022 |
| Supermicro    | A2SDi-LN4F                  | [b10f6655d9](https://bsd-hardware.info/?probe=b10f6655d9) | Mar 01, 2022 |
| MSI           | B365M PRO-VDH               | [d45ca02f84](https://bsd-hardware.info/?probe=d45ca02f84) | Feb 24, 2022 |
| MSI           | MAG B550M BAZOOKA           | [68f6eb4328](https://bsd-hardware.info/?probe=68f6eb4328) | Feb 23, 2022 |
| Shuttle       | FZ270                       | [7e0eb61342](https://bsd-hardware.info/?probe=7e0eb61342) | Feb 22, 2022 |
| MSI           | MAG B550M BAZOOKA           | [c1397b851e](https://bsd-hardware.info/?probe=c1397b851e) | Feb 22, 2022 |
| GALAX         | B365M G10b                  | [ceb2291168](https://bsd-hardware.info/?probe=ceb2291168) | Feb 22, 2022 |
| ASRock        | A88M-G                      | [14fcd1e849](https://bsd-hardware.info/?probe=14fcd1e849) | Feb 21, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [807a29112e](https://bsd-hardware.info/?probe=807a29112e) | Feb 19, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [0f3ee4caab](https://bsd-hardware.info/?probe=0f3ee4caab) | Feb 18, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | [e506cf84f4](https://bsd-hardware.info/?probe=e506cf84f4) | Feb 15, 2022 |
| Supermicro    | X9SCL/X9SCM                 | [2b58423bfe](https://bsd-hardware.info/?probe=2b58423bfe) | Feb 15, 2022 |
| Biostar       | X470GTA                     | [b7fc5ef684](https://bsd-hardware.info/?probe=b7fc5ef684) | Feb 12, 2022 |
| MSI           | H81M-P33                    | [5b4505d25e](https://bsd-hardware.info/?probe=5b4505d25e) | Feb 11, 2022 |
| ASUSTek       | P5Q-E                       | [42c29744d6](https://bsd-hardware.info/?probe=42c29744d6) | Feb 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1b042ff2e0](https://bsd-hardware.info/?probe=1b042ff2e0) | Feb 11, 2022 |
| HP            | 83E1                        | [d8e995126f](https://bsd-hardware.info/?probe=d8e995126f) | Feb 10, 2022 |
| Gigabyte      | 990FXA-UD3                  | [3c315d0c15](https://bsd-hardware.info/?probe=3c315d0c15) | Feb 09, 2022 |
| ASRock        | X370 Gaming X               | [22f8d133d4](https://bsd-hardware.info/?probe=22f8d133d4) | Feb 09, 2022 |
| ASUSTek       | PRIME Z270-P                | [ae4f0642fd](https://bsd-hardware.info/?probe=ae4f0642fd) | Feb 09, 2022 |
| Dell          | 0654JC A01                  | [bbcf2bad96](https://bsd-hardware.info/?probe=bbcf2bad96) | Feb 08, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [d57de875a6](https://bsd-hardware.info/?probe=d57de875a6) | Feb 07, 2022 |
| HP            | 0B54h D                     | [c2b43efb8f](https://bsd-hardware.info/?probe=c2b43efb8f) | Feb 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [91b1ec3b93](https://bsd-hardware.info/?probe=91b1ec3b93) | Feb 06, 2022 |
| Unknown       | Unknown                     | [8d38089ced](https://bsd-hardware.info/?probe=8d38089ced) | Feb 06, 2022 |
| HP            | ProLiant ML350p Gen8        | [7987f643d7](https://bsd-hardware.info/?probe=7987f643d7) | Feb 06, 2022 |
| Unknown       | Unknown                     | [12e979c82a](https://bsd-hardware.info/?probe=12e979c82a) | Feb 06, 2022 |
| HP            | 0B54h D                     | [1878f5822c](https://bsd-hardware.info/?probe=1878f5822c) | Feb 06, 2022 |
| HP            | ProLiant ML350p Gen8        | [b9e0021bfb](https://bsd-hardware.info/?probe=b9e0021bfb) | Feb 06, 2022 |
| Kontron       | KT965/ATXP 61420000         | [b5389bbf43](https://bsd-hardware.info/?probe=b5389bbf43) | Feb 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e41d9cff21](https://bsd-hardware.info/?probe=e41d9cff21) | Feb 06, 2022 |
| MSI           | H81M-P33                    | [049a615166](https://bsd-hardware.info/?probe=049a615166) | Feb 06, 2022 |
| ASUSTek       | P5Q-E                       | [5afa08fe32](https://bsd-hardware.info/?probe=5afa08fe32) | Feb 06, 2022 |
| Gateway       | DX4870                      | [5035507c5c](https://bsd-hardware.info/?probe=5035507c5c) | Feb 05, 2022 |
| HP            | 802E                        | [e23b3e314a](https://bsd-hardware.info/?probe=e23b3e314a) | Feb 05, 2022 |
| Gateway       | DX4870                      | [1f31c4a99b](https://bsd-hardware.info/?probe=1f31c4a99b) | Feb 05, 2022 |
| ASUSTek       | P4P800-VM                   | [2343c503a7](https://bsd-hardware.info/?probe=2343c503a7) | Feb 04, 2022 |
| Dell          | 05DN3X A00                  | [edef5c789d](https://bsd-hardware.info/?probe=edef5c789d) | Feb 04, 2022 |
| Dell          | 0D28YY A02                  | [8eb27db8c9](https://bsd-hardware.info/?probe=8eb27db8c9) | Jan 31, 2022 |
| Dell          | 0J37VM A01                  | [47061377bd](https://bsd-hardware.info/?probe=47061377bd) | Jan 31, 2022 |
| Dell          | 0TK7TF A00                  | [d13ca7163c](https://bsd-hardware.info/?probe=d13ca7163c) | Jan 30, 2022 |
| Intel         | D2500CC AAG81477-401        | [f4d8bd7979](https://bsd-hardware.info/?probe=f4d8bd7979) | Jan 30, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [e0c2a150f7](https://bsd-hardware.info/?probe=e0c2a150f7) | Jan 29, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | [37cc045649](https://bsd-hardware.info/?probe=37cc045649) | Jan 28, 2022 |
| ASUSTek       | PRIME H410M-A               | [c7ef0e518f](https://bsd-hardware.info/?probe=c7ef0e518f) | Jan 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [eb44c8d7e1](https://bsd-hardware.info/?probe=eb44c8d7e1) | Jan 27, 2022 |
| Kontron       | KT965/ATXP 61420000         | [36109b09ca](https://bsd-hardware.info/?probe=36109b09ca) | Jan 26, 2022 |
| HP            | ProLiant MicroServer        | [b62251041b](https://bsd-hardware.info/?probe=b62251041b) | Jan 26, 2022 |
| MSI           | G31TM-P21                   | [10ca6492c1](https://bsd-hardware.info/?probe=10ca6492c1) | Jan 25, 2022 |
| MSI           | G31TM-P21                   | [7563c4cf09](https://bsd-hardware.info/?probe=7563c4cf09) | Jan 25, 2022 |
| Kontron       | KT965/ATXP 61420000         | [db757ea2ef](https://bsd-hardware.info/?probe=db757ea2ef) | Jan 25, 2022 |
| Gigabyte      | H310M S2 x.x                | [b0aeac1ef8](https://bsd-hardware.info/?probe=b0aeac1ef8) | Jan 25, 2022 |
| ASUSTek       | P5M2                        | [f2d4eccf4d](https://bsd-hardware.info/?probe=f2d4eccf4d) | Jan 24, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a90b68e57b](https://bsd-hardware.info/?probe=a90b68e57b) | Jan 23, 2022 |
| MSI           | H81M-P33                    | [9d6207401e](https://bsd-hardware.info/?probe=9d6207401e) | Jan 23, 2022 |
| ASUSTek       | P5Q-E                       | [691f4c1a9a](https://bsd-hardware.info/?probe=691f4c1a9a) | Jan 23, 2022 |
| ASUSTek       | PRIME Z590-P                | [0473b57d99](https://bsd-hardware.info/?probe=0473b57d99) | Jan 19, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | [082da3ef7f](https://bsd-hardware.info/?probe=082da3ef7f) | Jan 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | [9f442754d0](https://bsd-hardware.info/?probe=9f442754d0) | Jan 17, 2022 |
| MSI           | H81M-P33                    | [4cc0e9443d](https://bsd-hardware.info/?probe=4cc0e9443d) | Jan 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7307e3e0be](https://bsd-hardware.info/?probe=7307e3e0be) | Jan 16, 2022 |
| ASUSTek       | P5Q-E                       | [d9f18d4d56](https://bsd-hardware.info/?probe=d9f18d4d56) | Jan 16, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [8b55745b6f](https://bsd-hardware.info/?probe=8b55745b6f) | Jan 14, 2022 |
| ASUSTek       | PRIME H410M-A               | [d09cf2e0a7](https://bsd-hardware.info/?probe=d09cf2e0a7) | Jan 14, 2022 |
| ASUSTek       | Z87-PRO                     | [280ea0618b](https://bsd-hardware.info/?probe=280ea0618b) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | [825d20fcf7](https://bsd-hardware.info/?probe=825d20fcf7) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b953d9d2e6](https://bsd-hardware.info/?probe=b953d9d2e6) | Jan 13, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [384cbe9714](https://bsd-hardware.info/?probe=384cbe9714) | Jan 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [1d7c4c096e](https://bsd-hardware.info/?probe=1d7c4c096e) | Jan 13, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [1527560bbd](https://bsd-hardware.info/?probe=1527560bbd) | Jan 11, 2022 |
| HP            | ProLiant MicroServer        | [0da2a93271](https://bsd-hardware.info/?probe=0da2a93271) | Jan 11, 2022 |
| Supermicro    | X7SBL                       | [c7d877a988](https://bsd-hardware.info/?probe=c7d877a988) | Jan 11, 2022 |
| Intel         | DH61CR AAG14064-210         | [15bb78bf9a](https://bsd-hardware.info/?probe=15bb78bf9a) | Jan 11, 2022 |
| Intel         | DQ35JO AAD82085-804         | [117b469a53](https://bsd-hardware.info/?probe=117b469a53) | Jan 11, 2022 |
| HP            | ProLiant MicroServer        | [e95a3dd5ec](https://bsd-hardware.info/?probe=e95a3dd5ec) | Jan 10, 2022 |
| ASUSTek       | A68HM-PLUS                  | [650628a974](https://bsd-hardware.info/?probe=650628a974) | Jan 10, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [d914e4c500](https://bsd-hardware.info/?probe=d914e4c500) | Jan 10, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [03252493ce](https://bsd-hardware.info/?probe=03252493ce) | Jan 09, 2022 |
| ASRock        | FM2A85X Extreme6            | [c87969f2d8](https://bsd-hardware.info/?probe=c87969f2d8) | Jan 09, 2022 |
| ASRock        | Z170M Extreme4              | [c518ded272](https://bsd-hardware.info/?probe=c518ded272) | Jan 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2cc4698cbc](https://bsd-hardware.info/?probe=2cc4698cbc) | Jan 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2481037b2a](https://bsd-hardware.info/?probe=2481037b2a) | Jan 09, 2022 |
| Gigabyte      | H470 HD3                    | [afa675e7a7](https://bsd-hardware.info/?probe=afa675e7a7) | Jan 08, 2022 |
| Intel         | DH67CL AAG10212-205         | [1b0837ff84](https://bsd-hardware.info/?probe=1b0837ff84) | Jan 08, 2022 |
| Gigabyte      | B150-HD3P-CF                | [9752eae10b](https://bsd-hardware.info/?probe=9752eae10b) | Jan 06, 2022 |
| Unknown       | Unknown                     | [7367c82ceb](https://bsd-hardware.info/?probe=7367c82ceb) | Jan 05, 2022 |
| Unknown       | Unknown                     | [54ba0d5236](https://bsd-hardware.info/?probe=54ba0d5236) | Jan 05, 2022 |
| ASUSTek       | TUF GAMING B550-PLUS        | [ea4719600a](https://bsd-hardware.info/?probe=ea4719600a) | Jan 05, 2022 |
| ASUSTek       | P8H67-M PRO                 | [d789a35c01](https://bsd-hardware.info/?probe=d789a35c01) | Jan 02, 2022 |
| MSI           | H81M-P33                    | [759c219ace](https://bsd-hardware.info/?probe=759c219ace) | Jan 02, 2022 |
| Unknown       | Unknown                     | [c183bdd5af](https://bsd-hardware.info/?probe=c183bdd5af) | Jan 01, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [82256452fe](https://bsd-hardware.info/?probe=82256452fe) | Jan 01, 2022 |
| ASRock        | B450 Steel Legend           | [e67007df20](https://bsd-hardware.info/?probe=e67007df20) | Jan 01, 2022 |
| Unknown       | Unknown                     | [4848e4009f](https://bsd-hardware.info/?probe=4848e4009f) | Jan 01, 2022 |
| HP            | ProLiant MicroServer        | [d641a4bea9](https://bsd-hardware.info/?probe=d641a4bea9) | Dec 30, 2021 |
| ASUSTek       | P8B75-M                     | [c3884fac44](https://bsd-hardware.info/?probe=c3884fac44) | Dec 30, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | [dd62d57a45](https://bsd-hardware.info/?probe=dd62d57a45) | Dec 29, 2021 |
| friendlyel... | nanopi-m4                   | [bb29e50061](https://bsd-hardware.info/?probe=bb29e50061) | Dec 27, 2021 |
| AMI           | PEISIA E3845 VER1.0         | [d19f149583](https://bsd-hardware.info/?probe=d19f149583) | Dec 26, 2021 |
| Gigabyte      | P67A-D3-B3                  | [62f424cac5](https://bsd-hardware.info/?probe=62f424cac5) | Dec 26, 2021 |
| khadas        | edge-v                      | [42c428aac0](https://bsd-hardware.info/?probe=42c428aac0) | Dec 26, 2021 |
| MSI           | PRESTIGE X570 CREATION      | [afc3e2a972](https://bsd-hardware.info/?probe=afc3e2a972) | Dec 25, 2021 |
| Intel         | D54250WYK H13922-304        | [61acc33619](https://bsd-hardware.info/?probe=61acc33619) | Dec 22, 2021 |
| HP            | 1850                        | [aa737033c4](https://bsd-hardware.info/?probe=aa737033c4) | Dec 21, 2021 |
| HP            | 1850                        | [17f42cda78](https://bsd-hardware.info/?probe=17f42cda78) | Dec 21, 2021 |
| Purism        | Librem Mini v2              | [528ef01c87](https://bsd-hardware.info/?probe=528ef01c87) | Dec 20, 2021 |
| ASUSTek       | X99-E-10G WS                | [dacf7f604c](https://bsd-hardware.info/?probe=dacf7f604c) | Dec 20, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [69bf80f0c6](https://bsd-hardware.info/?probe=69bf80f0c6) | Dec 20, 2021 |
| Unknown       | Raspberry Pi 3 Model B P... | [ef0dcfaccf](https://bsd-hardware.info/?probe=ef0dcfaccf) | Dec 20, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [bc55ac50d1](https://bsd-hardware.info/?probe=bc55ac50d1) | Dec 20, 2021 |
| Acer          | Revo RN86                   | [68541bb331](https://bsd-hardware.info/?probe=68541bb331) | Dec 20, 2021 |
| Acer          | Aspire XC-895 V:1.0         | [58440d7663](https://bsd-hardware.info/?probe=58440d7663) | Dec 20, 2021 |
| Gigabyte      | X570 AORUS PRO              | [17cad87a0d](https://bsd-hardware.info/?probe=17cad87a0d) | Dec 19, 2021 |
| MSI           | MS-9852 10                  | [4b851eef0a](https://bsd-hardware.info/?probe=4b851eef0a) | Dec 19, 2021 |
| ASUSTek       | M4A785TD-V EVO              | [848e618f87](https://bsd-hardware.info/?probe=848e618f87) | Dec 15, 2021 |
| ASUSTek       | PRIME X370-PRO              | [d46498baa7](https://bsd-hardware.info/?probe=d46498baa7) | Dec 13, 2021 |
| MSI           | H81M-P33                    | [fe193c863a](https://bsd-hardware.info/?probe=fe193c863a) | Dec 12, 2021 |
| Unknown       | Unknown                     | [b726a1b3e3](https://bsd-hardware.info/?probe=b726a1b3e3) | Dec 11, 2021 |
| ASUSTek       | PRIME X570-PRO              | [9a8d19aa04](https://bsd-hardware.info/?probe=9a8d19aa04) | Dec 11, 2021 |
| PC Engines    | apu4                        | [826a08be25](https://bsd-hardware.info/?probe=826a08be25) | Dec 11, 2021 |
| Unknown       | Unknown                     | [7633cb9296](https://bsd-hardware.info/?probe=7633cb9296) | Dec 11, 2021 |
| ASUSTek       | M5A99X EVO                  | [2e3b493ba3](https://bsd-hardware.info/?probe=2e3b493ba3) | Dec 11, 2021 |
| ASUSTek       | ROG Maximus X FORMULA       | [8a9387c5da](https://bsd-hardware.info/?probe=8a9387c5da) | Dec 11, 2021 |
| ASUSTek       | ROG Maximus X FORMULA       | [9762ebd7c7](https://bsd-hardware.info/?probe=9762ebd7c7) | Dec 10, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [74538b669d](https://bsd-hardware.info/?probe=74538b669d) | Dec 10, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c83118d6d0](https://bsd-hardware.info/?probe=c83118d6d0) | Dec 09, 2021 |
| MSI           | H81M-P33                    | [237b84b5fc](https://bsd-hardware.info/?probe=237b84b5fc) | Dec 09, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [3956ad0525](https://bsd-hardware.info/?probe=3956ad0525) | Dec 09, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [5dbff17614](https://bsd-hardware.info/?probe=5dbff17614) | Dec 06, 2021 |
| Unknown       | Raspberry Pi 3 Model B P... | [646ca92a69](https://bsd-hardware.info/?probe=646ca92a69) | Dec 06, 2021 |
| ASUSTek       | P5B                         | [93b542ab79](https://bsd-hardware.info/?probe=93b542ab79) | Dec 06, 2021 |
| Gigabyte      | GA-8S661FXM-775             | [3a64909558](https://bsd-hardware.info/?probe=3a64909558) | Dec 06, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [66ed413cab](https://bsd-hardware.info/?probe=66ed413cab) | Dec 05, 2021 |
| MSI           | X99S MPOWER                 | [ba0ac00cf6](https://bsd-hardware.info/?probe=ba0ac00cf6) | Dec 04, 2021 |
| ASUSTek       | P7P55D                      | [73373c3c65](https://bsd-hardware.info/?probe=73373c3c65) | Dec 04, 2021 |
| Unknown       | Unknown                     | [a91c9ec877](https://bsd-hardware.info/?probe=a91c9ec877) | Dec 04, 2021 |
| HP            | 0B54h D                     | [5186b81327](https://bsd-hardware.info/?probe=5186b81327) | Dec 02, 2021 |
| Dell          | 0Y5DDC A00                  | [888de14ef5](https://bsd-hardware.info/?probe=888de14ef5) | Dec 02, 2021 |
| ASRock        | B450 Steel Legend           | [f3a11b2c2d](https://bsd-hardware.info/?probe=f3a11b2c2d) | Dec 01, 2021 |
| ASUSTek       | P7P55D                      | [540d2ef68c](https://bsd-hardware.info/?probe=540d2ef68c) | Nov 29, 2021 |
| MSI           | H81M-P33                    | [effc42884a](https://bsd-hardware.info/?probe=effc42884a) | Nov 28, 2021 |
| ASUSTek       | P5Q-E                       | [158a4879ac](https://bsd-hardware.info/?probe=158a4879ac) | Nov 28, 2021 |
| Shuttle       | FH270                       | [81643d52fd](https://bsd-hardware.info/?probe=81643d52fd) | Nov 26, 2021 |
| ASRock        | Q1900B-ITX                  | [7f32937b2c](https://bsd-hardware.info/?probe=7f32937b2c) | Nov 26, 2021 |
| Shuttle       | FZ270                       | [309687b5be](https://bsd-hardware.info/?probe=309687b5be) | Nov 26, 2021 |
| ASRock        | Q1900B-ITX                  | [4df18caa5f](https://bsd-hardware.info/?probe=4df18caa5f) | Nov 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a915598e32](https://bsd-hardware.info/?probe=a915598e32) | Nov 26, 2021 |
| Lenovo        | MAHOBAY                     | [b77016bee5](https://bsd-hardware.info/?probe=b77016bee5) | Nov 25, 2021 |
| Gigabyte      | G41M-Combo                  | [d227ad0b48](https://bsd-hardware.info/?probe=d227ad0b48) | Nov 25, 2021 |
| Gigabyte      | G41M-Combo                  | [3a4a54eed4](https://bsd-hardware.info/?probe=3a4a54eed4) | Nov 25, 2021 |
| Gigabyte      | MZBSWBP-00                  | [9e7a72d920](https://bsd-hardware.info/?probe=9e7a72d920) | Nov 24, 2021 |
| ASRock        | X570M Pro4                  | [b10f02e887](https://bsd-hardware.info/?probe=b10f02e887) | Nov 23, 2021 |
| Supermicro    | X7SPA-HF                    | [0ed5f516f4](https://bsd-hardware.info/?probe=0ed5f516f4) | Nov 21, 2021 |
| ASUSTek       | P5Q-E                       | [60ccf13a97](https://bsd-hardware.info/?probe=60ccf13a97) | Nov 21, 2021 |
| Supermicro    | X9SRE/X9SRE-3F/X9SRi/X9S... | [fe64c7bb21](https://bsd-hardware.info/?probe=fe64c7bb21) | Nov 21, 2021 |
| ASRockRack    | E3C246D4U2-2T               | [fd00b64a4c](https://bsd-hardware.info/?probe=fd00b64a4c) | Nov 21, 2021 |
| Dell          | 0M5DCD A00                  | [2f26c69137](https://bsd-hardware.info/?probe=2f26c69137) | Nov 20, 2021 |
| HP            | 87D6 SMVB                   | [ffa88d066b](https://bsd-hardware.info/?probe=ffa88d066b) | Nov 16, 2021 |
| PC Engines    | APU                         | [c1656cb13b](https://bsd-hardware.info/?probe=c1656cb13b) | Nov 15, 2021 |
| HP            | ProLiant MicroServer Gen... | [33b6a20321](https://bsd-hardware.info/?probe=33b6a20321) | Nov 14, 2021 |
| PC Engines    | APU                         | [6db53946a4](https://bsd-hardware.info/?probe=6db53946a4) | Nov 14, 2021 |
| PC Engines    | APU2                        | [424bb1e286](https://bsd-hardware.info/?probe=424bb1e286) | Nov 10, 2021 |
| MSI           | GF615M-P33 V2               | [6be2d8aec7](https://bsd-hardware.info/?probe=6be2d8aec7) | Nov 09, 2021 |
| MSI           | MS-9129                     | [4ab900bda7](https://bsd-hardware.info/?probe=4ab900bda7) | Nov 08, 2021 |
| MSI           | MS-9129                     | [7c69051998](https://bsd-hardware.info/?probe=7c69051998) | Nov 08, 2021 |
| Unknown       | Unknown                     | [27e7cd5267](https://bsd-hardware.info/?probe=27e7cd5267) | Nov 08, 2021 |
| PC Engines    | APU                         | [a39767bccb](https://bsd-hardware.info/?probe=a39767bccb) | Nov 08, 2021 |
| PC Engines    | APU2                        | [12ab05bc2e](https://bsd-hardware.info/?probe=12ab05bc2e) | Nov 08, 2021 |
| PC Engines    | APU2                        | [bcb26e0164](https://bsd-hardware.info/?probe=bcb26e0164) | Nov 08, 2021 |
| ASUSTek       | P9X79 WS                    | [050e2e2a8c](https://bsd-hardware.info/?probe=050e2e2a8c) | Nov 08, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [dab56eef53](https://bsd-hardware.info/?probe=dab56eef53) | Nov 07, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [f26b302e43](https://bsd-hardware.info/?probe=f26b302e43) | Nov 07, 2021 |
| HP            | 3397                        | [3434fa8427](https://bsd-hardware.info/?probe=3434fa8427) | Nov 07, 2021 |
| HP            | 3048h                       | [c2e57e5b06](https://bsd-hardware.info/?probe=c2e57e5b06) | Nov 06, 2021 |
| ASUSTek       | P4PE2-X                     | [25c402cbf0](https://bsd-hardware.info/?probe=25c402cbf0) | Nov 05, 2021 |
| ASRock        | 970 Extreme4                | [cc090875b1](https://bsd-hardware.info/?probe=cc090875b1) | Nov 04, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [a6b0693d9f](https://bsd-hardware.info/?probe=a6b0693d9f) | Nov 01, 2021 |
| Gigabyte      | H110M-H-CF                  | [202d616682](https://bsd-hardware.info/?probe=202d616682) | Oct 31, 2021 |
| Apple         | Mac-F221BEC8                | [bf9d536016](https://bsd-hardware.info/?probe=bf9d536016) | Oct 30, 2021 |
| MSI           | Z270 PC MATE                | [bc9dc27f58](https://bsd-hardware.info/?probe=bc9dc27f58) | Oct 30, 2021 |
| ADI Engine... | RCC-VE                      | [9744b5eca0](https://bsd-hardware.info/?probe=9744b5eca0) | Oct 29, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [206f086c58](https://bsd-hardware.info/?probe=206f086c58) | Oct 29, 2021 |
| Gigabyte      | Z77X-UD3H                   | [4c9b877754](https://bsd-hardware.info/?probe=4c9b877754) | Oct 29, 2021 |
| HP            | 1589                        | [8a1cec788f](https://bsd-hardware.info/?probe=8a1cec788f) | Oct 28, 2021 |
| Dell          | 0KC9NP A01                  | [d80d739506](https://bsd-hardware.info/?probe=d80d739506) | Oct 28, 2021 |
| Radxa         | rock-pi-4                   | [767ef0f0a6](https://bsd-hardware.info/?probe=767ef0f0a6) | Oct 27, 2021 |
| Radxa         | rock-pi-4                   | [fcd3e65f7e](https://bsd-hardware.info/?probe=fcd3e65f7e) | Oct 26, 2021 |
| Beckhoff A... | CX51x0 G3                   | [6db720018b](https://bsd-hardware.info/?probe=6db720018b) | Oct 25, 2021 |
| Beckhoff A... | CX20x3 G1                   | [a49fbd5ce3](https://bsd-hardware.info/?probe=a49fbd5ce3) | Oct 25, 2021 |
| ASUSTek       | P5Q-E                       | [d821d68ffa](https://bsd-hardware.info/?probe=d821d68ffa) | Oct 24, 2021 |
| MSI           | H81M-P33                    | [b4a1918b44](https://bsd-hardware.info/?probe=b4a1918b44) | Oct 24, 2021 |
| ASUSTek       | P10S WS                     | [e2d86f8c45](https://bsd-hardware.info/?probe=e2d86f8c45) | Oct 23, 2021 |
| Gigabyte      | B450M S2H                   | [f3bf8edc1e](https://bsd-hardware.info/?probe=f3bf8edc1e) | Oct 22, 2021 |
| HP            | 18E7                        | [bc3f111ee4](https://bsd-hardware.info/?probe=bc3f111ee4) | Oct 22, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [15d56aee58](https://bsd-hardware.info/?probe=15d56aee58) | Oct 21, 2021 |
| Apple         | Mac-F221BEC8                | [4e91fa71b2](https://bsd-hardware.info/?probe=4e91fa71b2) | Oct 19, 2021 |
| Radxa         | rock-pi-4                   | [876564310f](https://bsd-hardware.info/?probe=876564310f) | Oct 19, 2021 |
| Unknown       | Unknown                     | [9716564d5e](https://bsd-hardware.info/?probe=9716564d5e) | Oct 19, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [39c78ac754](https://bsd-hardware.info/?probe=39c78ac754) | Oct 19, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [5173ffc13b](https://bsd-hardware.info/?probe=5173ffc13b) | Oct 17, 2021 |
| ASUSTek       | P5Q-E                       | [da31eaf836](https://bsd-hardware.info/?probe=da31eaf836) | Oct 17, 2021 |
| Dell          | 0Y7WYT A00                  | [1de7ed2a67](https://bsd-hardware.info/?probe=1de7ed2a67) | Oct 16, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [6ceda5d7b4](https://bsd-hardware.info/?probe=6ceda5d7b4) | Oct 15, 2021 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [c4efccfa90](https://bsd-hardware.info/?probe=c4efccfa90) | Oct 15, 2021 |
| ASUSTek       | PRIME X370-PRO              | [80719c7010](https://bsd-hardware.info/?probe=80719c7010) | Oct 13, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [f397fb3c85](https://bsd-hardware.info/?probe=f397fb3c85) | Oct 13, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [e53866a5d9](https://bsd-hardware.info/?probe=e53866a5d9) | Oct 11, 2021 |
| ASUSTek       | P9X79                       | [be9d90602d](https://bsd-hardware.info/?probe=be9d90602d) | Oct 11, 2021 |
| Supermicro    | X10SRH-CLN4FA               | [8e713b55dc](https://bsd-hardware.info/?probe=8e713b55dc) | Oct 06, 2021 |
| MSI           | 970A-G43                    | [5664e84f3c](https://bsd-hardware.info/?probe=5664e84f3c) | Oct 06, 2021 |
| ASUSTek       | H81M-E                      | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| MSI           | PRESTIGE X570 CREATION      | [76c73f0745](https://bsd-hardware.info/?probe=76c73f0745) | Oct 01, 2021 |
| MSI           | PRESTIGE X570 CREATION      | [1da3490d20](https://bsd-hardware.info/?probe=1da3490d20) | Sep 30, 2021 |
| Foxconn       | 2A92                        | [da467830af](https://bsd-hardware.info/?probe=da467830af) | Sep 30, 2021 |
| HP            | 0AE8h C                     | [159e371cc7](https://bsd-hardware.info/?probe=159e371cc7) | Sep 30, 2021 |
| Dell          | 06X1TJ A00                  | [ab93f4d860](https://bsd-hardware.info/?probe=ab93f4d860) | Sep 29, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [74e5b610f0](https://bsd-hardware.info/?probe=74e5b610f0) | Sep 28, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | [a302e181a5](https://bsd-hardware.info/?probe=a302e181a5) | Sep 27, 2021 |
| ASUSTek       | PRIME Z590-A                | [1aa5ced5a0](https://bsd-hardware.info/?probe=1aa5ced5a0) | Sep 23, 2021 |
| Dell          | 0Y2K8N A01                  | [1559654b51](https://bsd-hardware.info/?probe=1559654b51) | Sep 23, 2021 |
| ASUSTek       | H81M-E                      | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| ASRock        | X58 Extreme3                | [540fef417b](https://bsd-hardware.info/?probe=540fef417b) | Sep 22, 2021 |
| Unknown       | Unknown                     | [b45dad63f6](https://bsd-hardware.info/?probe=b45dad63f6) | Sep 20, 2021 |
| Unknown       | Unknown                     | [ed7c1c1f3b](https://bsd-hardware.info/?probe=ed7c1c1f3b) | Sep 20, 2021 |
| Gigabyte      | EP45-UD3R                   | [21e4a40d62](https://bsd-hardware.info/?probe=21e4a40d62) | Sep 18, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [198c4264f9](https://bsd-hardware.info/?probe=198c4264f9) | Sep 16, 2021 |
| QTQD          | Board                       | [2e778ac107](https://bsd-hardware.info/?probe=2e778ac107) | Sep 16, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [062602e8db](https://bsd-hardware.info/?probe=062602e8db) | Sep 15, 2021 |
| ASUSTek       | PRIME X370-PRO              | [433df71bee](https://bsd-hardware.info/?probe=433df71bee) | Sep 13, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [e15f50c6b9](https://bsd-hardware.info/?probe=e15f50c6b9) | Sep 13, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [8fff74c89c](https://bsd-hardware.info/?probe=8fff74c89c) | Sep 13, 2021 |
| MSI           | Z590 PRO WIFI               | [b77d4fef6b](https://bsd-hardware.info/?probe=b77d4fef6b) | Sep 11, 2021 |
| ASRock        | X570 Taichi                 | [d23af74c18](https://bsd-hardware.info/?probe=d23af74c18) | Sep 10, 2021 |
| HP            | 212B                        | [d3894b9f37](https://bsd-hardware.info/?probe=d3894b9f37) | Sep 10, 2021 |
| Gigabyte      | Z68P-DS3                    | [9a2545337b](https://bsd-hardware.info/?probe=9a2545337b) | Sep 09, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [d5750a95a4](https://bsd-hardware.info/?probe=d5750a95a4) | Sep 08, 2021 |
| HP            | 158A                        | [a9b66cb0e1](https://bsd-hardware.info/?probe=a9b66cb0e1) | Sep 08, 2021 |
| ASUSTek       | P8Z68-V LX                  | [29cfd33c5e](https://bsd-hardware.info/?probe=29cfd33c5e) | Sep 06, 2021 |
| MSI           | B360-A PRO                  | [ca906cd56a](https://bsd-hardware.info/?probe=ca906cd56a) | Sep 06, 2021 |
| Dell          | 0C522T A01                  | [f735ee3c9e](https://bsd-hardware.info/?probe=f735ee3c9e) | Sep 05, 2021 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [a78cc6a11b](https://bsd-hardware.info/?probe=a78cc6a11b) | Sep 04, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | [fa4da2509b](https://bsd-hardware.info/?probe=fa4da2509b) | Sep 03, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | [97035edd33](https://bsd-hardware.info/?probe=97035edd33) | Sep 03, 2021 |
| Dell          | 0Y2K8N A01                  | [7294dc1dcc](https://bsd-hardware.info/?probe=7294dc1dcc) | Sep 01, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [1ef37663db](https://bsd-hardware.info/?probe=1ef37663db) | Sep 01, 2021 |
| ASUSTek       | PRIME Z590-P                | [aeb23122b6](https://bsd-hardware.info/?probe=aeb23122b6) | Aug 31, 2021 |
| HP            | 1589                        | [288b956c1e](https://bsd-hardware.info/?probe=288b956c1e) | Aug 31, 2021 |
| ASRock        | 970 Extreme3                | [8f18868bb4](https://bsd-hardware.info/?probe=8f18868bb4) | Aug 30, 2021 |
| Intel         | DG33BU AAD79951-408         | [e8f4f644e3](https://bsd-hardware.info/?probe=e8f4f644e3) | Aug 30, 2021 |
| ASUSTek       | P4P800-VM                   | [f23a539453](https://bsd-hardware.info/?probe=f23a539453) | Aug 30, 2021 |
| ASRock        | H67M                        | [53d71eb3fc](https://bsd-hardware.info/?probe=53d71eb3fc) | Aug 29, 2021 |
| Gigabyte      | N3160ND3V                   | [66430483e3](https://bsd-hardware.info/?probe=66430483e3) | Aug 29, 2021 |
| ASRock        | H67M                        | [4b65ec99db](https://bsd-hardware.info/?probe=4b65ec99db) | Aug 29, 2021 |
| Dell          | 0G3HR7 A00                  | [7f75f30b75](https://bsd-hardware.info/?probe=7f75f30b75) | Aug 27, 2021 |
| Medion        | MS-7616                     | [98f0e21e6c](https://bsd-hardware.info/?probe=98f0e21e6c) | Aug 26, 2021 |
| Medion        | MS-7616                     | [663b50102d](https://bsd-hardware.info/?probe=663b50102d) | Aug 26, 2021 |
| ECS-USA       | GeForce6100PM-M2            | [f6324966fb](https://bsd-hardware.info/?probe=f6324966fb) | Aug 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [a3fe3577b0](https://bsd-hardware.info/?probe=a3fe3577b0) | Aug 26, 2021 |
| ASRock        | B450M-HDV                   | [fdeba8e75d](https://bsd-hardware.info/?probe=fdeba8e75d) | Aug 26, 2021 |
| ASRock        | B450M Pro4                  | [70dc185964](https://bsd-hardware.info/?probe=70dc185964) | Aug 25, 2021 |
| MSI           | B450 TOMAHAWK               | [b7c1cae5a8](https://bsd-hardware.info/?probe=b7c1cae5a8) | Aug 23, 2021 |
| MSI           | B450 TOMAHAWK               | [ff33f91374](https://bsd-hardware.info/?probe=ff33f91374) | Aug 22, 2021 |
| ASUSTek       | P5Q                         | [01c4a15001](https://bsd-hardware.info/?probe=01c4a15001) | Aug 22, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3e088c942b](https://bsd-hardware.info/?probe=3e088c942b) | Aug 22, 2021 |
| ASRock        | B450M-HDV                   | [996f8b5618](https://bsd-hardware.info/?probe=996f8b5618) | Aug 22, 2021 |
| ASRock        | 990FX Killer                | [9f6f8fe218](https://bsd-hardware.info/?probe=9f6f8fe218) | Aug 22, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [5bf55e14a4](https://bsd-hardware.info/?probe=5bf55e14a4) | Aug 21, 2021 |
| Lenovo        | 3728 SDK0J40709 WIN 3259... | [7ba1ccc40d](https://bsd-hardware.info/?probe=7ba1ccc40d) | Aug 19, 2021 |
| Biostar       | TH55B HD                    | [635f13a7c0](https://bsd-hardware.info/?probe=635f13a7c0) | Aug 16, 2021 |
| HP            | 158A                        | [e2c79dfa71](https://bsd-hardware.info/?probe=e2c79dfa71) | Aug 16, 2021 |
| Dell          | 0G261D A00                  | [ba9e468d6d](https://bsd-hardware.info/?probe=ba9e468d6d) | Aug 14, 2021 |
| Biostar       | TH55B HD                    | [6aef0c0281](https://bsd-hardware.info/?probe=6aef0c0281) | Aug 13, 2021 |
| ASUSTek       | PRIME X370-PRO              | [b5f1b8963a](https://bsd-hardware.info/?probe=b5f1b8963a) | Aug 13, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [8331eb7cbf](https://bsd-hardware.info/?probe=8331eb7cbf) | Aug 13, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [adf41eedab](https://bsd-hardware.info/?probe=adf41eedab) | Aug 13, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [1c835c20cb](https://bsd-hardware.info/?probe=1c835c20cb) | Aug 09, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [1a89e4b6d7](https://bsd-hardware.info/?probe=1a89e4b6d7) | Aug 07, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [0c4fd12ee6](https://bsd-hardware.info/?probe=0c4fd12ee6) | Jul 26, 2021 |
| Unknown       | Unknown                     | [223d74d547](https://bsd-hardware.info/?probe=223d74d547) | Jul 25, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [586c14dd63](https://bsd-hardware.info/?probe=586c14dd63) | Jul 23, 2021 |
| ASUSTek       | PRIME X370-PRO              | [389bf7ae4b](https://bsd-hardware.info/?probe=389bf7ae4b) | Jul 23, 2021 |
| ASUSTek       | H170 PRO GAMING             | [ef9820081f](https://bsd-hardware.info/?probe=ef9820081f) | Jul 21, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [8df129e74d](https://bsd-hardware.info/?probe=8df129e74d) | Jul 20, 2021 |
| Dell          | 0HD5W2 A00                  | [8315a3b948](https://bsd-hardware.info/?probe=8315a3b948) | Jul 17, 2021 |
| Dell          | 0HD5W2 A00                  | [8780a9eb26](https://bsd-hardware.info/?probe=8780a9eb26) | Jul 17, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [fb1c3af983](https://bsd-hardware.info/?probe=fb1c3af983) | Jul 16, 2021 |
| Gigabyte      | P55A-UD3                    | [dc1b4d8a6b](https://bsd-hardware.info/?probe=dc1b4d8a6b) | Jul 16, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [9d729e0508](https://bsd-hardware.info/?probe=9d729e0508) | Jul 13, 2021 |
| ASUSTek       | PRIME X370-PRO              | [5038f75992](https://bsd-hardware.info/?probe=5038f75992) | Jul 13, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [7717726619](https://bsd-hardware.info/?probe=7717726619) | Jul 13, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0c9fc39896](https://bsd-hardware.info/?probe=0c9fc39896) | Jul 11, 2021 |
| HP            | ProLiant MicroServer Gen... | [250fc347ce](https://bsd-hardware.info/?probe=250fc347ce) | Jul 11, 2021 |
| HP            | ProLiant MicroServer Gen... | [93b487fc6a](https://bsd-hardware.info/?probe=93b487fc6a) | Jul 11, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3d69b35f7d](https://bsd-hardware.info/?probe=3d69b35f7d) | Jul 11, 2021 |
| HP            | 158A                        | [01d7f3bfd3](https://bsd-hardware.info/?probe=01d7f3bfd3) | Jul 10, 2021 |
| Dell          | 0T7D40 A01                  | [f67d589e29](https://bsd-hardware.info/?probe=f67d589e29) | Jul 08, 2021 |
| MSI           | H81M-E33                    | [c9fda90944](https://bsd-hardware.info/?probe=c9fda90944) | Jul 08, 2021 |
| Unknown       | Unknown                     | [4a3836de00](https://bsd-hardware.info/?probe=4a3836de00) | Jul 08, 2021 |
| Pegatron      | IPPCR-SS                    | [86b2e85d24](https://bsd-hardware.info/?probe=86b2e85d24) | Jul 05, 2021 |
| Dell          | 0HD5W2 A00                  | [9fe5dd4b75](https://bsd-hardware.info/?probe=9fe5dd4b75) | Jul 04, 2021 |
| Dell          | 0HD5W2 A00                  | [e85afd7989](https://bsd-hardware.info/?probe=e85afd7989) | Jul 04, 2021 |
| HP            | 1589                        | [da8a524302](https://bsd-hardware.info/?probe=da8a524302) | Jul 04, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [7360fb3199](https://bsd-hardware.info/?probe=7360fb3199) | Jul 03, 2021 |
| Dell          | 05DN3X A00                  | [df4415dba4](https://bsd-hardware.info/?probe=df4415dba4) | Jul 03, 2021 |
| Dell          | 0T7D40 A01                  | [d39de0c0dc](https://bsd-hardware.info/?probe=d39de0c0dc) | Jun 30, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [adcfefc5cb](https://bsd-hardware.info/?probe=adcfefc5cb) | Jun 30, 2021 |
| Gigabyte      | A320M-S2H-CF                | [c1a27ca913](https://bsd-hardware.info/?probe=c1a27ca913) | Jun 27, 2021 |
| HP            | ProLiant ML310 G5p          | [e20e168df8](https://bsd-hardware.info/?probe=e20e168df8) | Jun 27, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [9f4ce06dce](https://bsd-hardware.info/?probe=9f4ce06dce) | Jun 22, 2021 |
| Dell          | 0GTK4K A02                  | [53f4f785ba](https://bsd-hardware.info/?probe=53f4f785ba) | Jun 22, 2021 |
| ASRock        | X370 Taichi                 | [925bc3b3f6](https://bsd-hardware.info/?probe=925bc3b3f6) | Jun 22, 2021 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | [ccb9856049](https://bsd-hardware.info/?probe=ccb9856049) | Jun 21, 2021 |
| ASRock        | X399M Taichi                | [8ca573bb39](https://bsd-hardware.info/?probe=8ca573bb39) | Jun 21, 2021 |
| Wistron       | ProLiant ML110 G6           | [8f336c0fa3](https://bsd-hardware.info/?probe=8f336c0fa3) | Jun 19, 2021 |
| Wistron       | ProLiant ML110 G6           | [dc619f203f](https://bsd-hardware.info/?probe=dc619f203f) | Jun 19, 2021 |
| ASUSTek       | PRIME Z270-A                | [c7b4a17b7d](https://bsd-hardware.info/?probe=c7b4a17b7d) | Jun 19, 2021 |
| Lenovo        | 36EB SDK0R32862 WIN 3258... | [9e9eedc9ed](https://bsd-hardware.info/?probe=9e9eedc9ed) | Jun 18, 2021 |
| ASRock        | C2750D4I                    | [09cbe1322a](https://bsd-hardware.info/?probe=09cbe1322a) | Jun 14, 2021 |
| ASUSTek       | PRIME X370-PRO              | [c066194e27](https://bsd-hardware.info/?probe=c066194e27) | Jun 13, 2021 |
| ASUSTek       | P5K SE/EPU                  | [60d9b24b69](https://bsd-hardware.info/?probe=60d9b24b69) | Jun 13, 2021 |
| GVC           | DR 738                      | [3e8940224f](https://bsd-hardware.info/?probe=3e8940224f) | Jun 13, 2021 |
| MSI           | Z97 GAMING 3                | [c6d7626b29](https://bsd-hardware.info/?probe=c6d7626b29) | Jun 12, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [5ccdc16de4](https://bsd-hardware.info/?probe=5ccdc16de4) | Jun 12, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [9062f35935](https://bsd-hardware.info/?probe=9062f35935) | Jun 10, 2021 |
| MSI           | B360-A PRO                  | [f0fcc2c8b0](https://bsd-hardware.info/?probe=f0fcc2c8b0) | Jun 10, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [db12a78352](https://bsd-hardware.info/?probe=db12a78352) | Jun 08, 2021 |
| ASRock        | B450M Pro4                  | [9a7adb8860](https://bsd-hardware.info/?probe=9a7adb8860) | Jun 06, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [edebe87739](https://bsd-hardware.info/?probe=edebe87739) | Jun 04, 2021 |
| Biostar       | TH67B                       | [1f2321ec41](https://bsd-hardware.info/?probe=1f2321ec41) | Jun 01, 2021 |
| Gigabyte      | H61M-DS2                    | [d9657e7246](https://bsd-hardware.info/?probe=d9657e7246) | Jun 01, 2021 |
| ASUSTek       | PRIME Z590-P                | [8c06f6b716](https://bsd-hardware.info/?probe=8c06f6b716) | Jun 01, 2021 |
| Supermicro    | X7SPA-HF                    | [b316bfd5cf](https://bsd-hardware.info/?probe=b316bfd5cf) | Jun 01, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [7a41fca3bb](https://bsd-hardware.info/?probe=7a41fca3bb) | Jun 01, 2021 |
| ASUSTek       | X99-A II                    | [6b06c67610](https://bsd-hardware.info/?probe=6b06c67610) | Jun 01, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [0b3c9a332d](https://bsd-hardware.info/?probe=0b3c9a332d) | May 31, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [a87473149b](https://bsd-hardware.info/?probe=a87473149b) | May 31, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [82d464f2a8](https://bsd-hardware.info/?probe=82d464f2a8) | May 31, 2021 |
| Gigabyte      | B85-HD3                     | [331da3091c](https://bsd-hardware.info/?probe=331da3091c) | May 28, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | [20052b0d55](https://bsd-hardware.info/?probe=20052b0d55) | May 27, 2021 |
| ASUSTek       | P7H55-M/USB3                | [87068a97be](https://bsd-hardware.info/?probe=87068a97be) | May 26, 2021 |
| MSI           | B85M-G43                    | [24b107b13c](https://bsd-hardware.info/?probe=24b107b13c) | May 26, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | [2247c7130f](https://bsd-hardware.info/?probe=2247c7130f) | May 26, 2021 |
| HP            | 1790                        | [59e472fb01](https://bsd-hardware.info/?probe=59e472fb01) | May 24, 2021 |
| HP            | 1790                        | [3a4e33eb4d](https://bsd-hardware.info/?probe=3a4e33eb4d) | May 24, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [f035aab141](https://bsd-hardware.info/?probe=f035aab141) | May 24, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | [4d15a3ffe3](https://bsd-hardware.info/?probe=4d15a3ffe3) | May 23, 2021 |
| MSI           | H61I-E35/W8                 | [d07ad10827](https://bsd-hardware.info/?probe=d07ad10827) | May 22, 2021 |
| HP            | ProLiant MicroServer Gen... | [80cf566074](https://bsd-hardware.info/?probe=80cf566074) | May 21, 2021 |
| Dell          | 0215PR A04                  | [dddf168db9](https://bsd-hardware.info/?probe=dddf168db9) | May 21, 2021 |
| HP            | 843F                        | [08eea80f1c](https://bsd-hardware.info/?probe=08eea80f1c) | May 18, 2021 |
| ASRock        | J3455-ITX                   | [c9218ee21d](https://bsd-hardware.info/?probe=c9218ee21d) | May 17, 2021 |
| Supermicro    | X7DCU                       | [b4b4ebc9f2](https://bsd-hardware.info/?probe=b4b4ebc9f2) | May 17, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [62b9ea2794](https://bsd-hardware.info/?probe=62b9ea2794) | May 14, 2021 |
| EVGA          | X299 FTW K                  | [c4862c598a](https://bsd-hardware.info/?probe=c4862c598a) | May 11, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [cc49321b12](https://bsd-hardware.info/?probe=cc49321b12) | May 11, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [a9a897258e](https://bsd-hardware.info/?probe=a9a897258e) | May 11, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8d78068ca7](https://bsd-hardware.info/?probe=8d78068ca7) | May 09, 2021 |
| ASUSTek       | P8H77-M PRO                 | [b3acafeb1a](https://bsd-hardware.info/?probe=b3acafeb1a) | May 09, 2021 |
| ASUSTek       | P8H77-M PRO                 | [86cec3b874](https://bsd-hardware.info/?probe=86cec3b874) | May 09, 2021 |
| Shuttle       | FH87                        | [bf5457ff02](https://bsd-hardware.info/?probe=bf5457ff02) | May 09, 2021 |
| ASUSTek       | P8H77-M PRO                 | [87e5651fd1](https://bsd-hardware.info/?probe=87e5651fd1) | May 06, 2021 |
| Gigabyte      | X58A-UD5                    | [24502c7f7b](https://bsd-hardware.info/?probe=24502c7f7b) | May 04, 2021 |
| ASRock        | Z170M Extreme4              | [e2d2bb7f28](https://bsd-hardware.info/?probe=e2d2bb7f28) | May 04, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | [4d7013aeab](https://bsd-hardware.info/?probe=4d7013aeab) | May 04, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [cbbf4f86cd](https://bsd-hardware.info/?probe=cbbf4f86cd) | May 03, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [7fc73d2db3](https://bsd-hardware.info/?probe=7fc73d2db3) | May 03, 2021 |
| Supermicro    | X7DCL                       | [27fc294bca](https://bsd-hardware.info/?probe=27fc294bca) | May 03, 2021 |
| ASUSTek       | Z97-K                       | [d8ecc7077a](https://bsd-hardware.info/?probe=d8ecc7077a) | May 02, 2021 |
| GVC           | DR 738                      | [9ff0fb7df4](https://bsd-hardware.info/?probe=9ff0fb7df4) | May 01, 2021 |
| GVC           | DR 738                      | [2acd0848c8](https://bsd-hardware.info/?probe=2acd0848c8) | May 01, 2021 |
| Gigabyte      | H81M-S2PV                   | [2713d38658](https://bsd-hardware.info/?probe=2713d38658) | May 01, 2021 |
| Beckhoff A... | CB3056 G4                   | [120665d4d3](https://bsd-hardware.info/?probe=120665d4d3) | Apr 30, 2021 |
| ASRock        | Z390M-ITX/ac                | [23196aa66b](https://bsd-hardware.info/?probe=23196aa66b) | Apr 30, 2021 |
| Dell          | 0FJ030                      | [91418a4965](https://bsd-hardware.info/?probe=91418a4965) | Apr 30, 2021 |
| Dell          | 0FJ030                      | [7bee24ee8a](https://bsd-hardware.info/?probe=7bee24ee8a) | Apr 30, 2021 |
| Dell          | 0FJ030                      | [d5277ad9e1](https://bsd-hardware.info/?probe=d5277ad9e1) | Apr 30, 2021 |
| Dell          | 0FJ030                      | [63b1980830](https://bsd-hardware.info/?probe=63b1980830) | Apr 30, 2021 |
| ASUSTek       | Z87-PRO                     | [d218181abb](https://bsd-hardware.info/?probe=d218181abb) | Apr 26, 2021 |
| pine64        | pinebook-pro-rk3399         | [79713a2668](https://bsd-hardware.info/?probe=79713a2668) | Apr 25, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [8055ed41df](https://bsd-hardware.info/?probe=8055ed41df) | Apr 25, 2021 |
| Gigabyte      | F2A75M-HD2                  | [18a74377ac](https://bsd-hardware.info/?probe=18a74377ac) | Apr 25, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [9a0602d408](https://bsd-hardware.info/?probe=9a0602d408) | Apr 25, 2021 |
| Gigabyte      | 990FXA-UD3                  | [da3281b86a](https://bsd-hardware.info/?probe=da3281b86a) | Apr 24, 2021 |
| Supermicro    | X10SDV-8C-TLN4F             | [6a22da5c5d](https://bsd-hardware.info/?probe=6a22da5c5d) | Apr 24, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [ab8235808d](https://bsd-hardware.info/?probe=ab8235808d) | Apr 23, 2021 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [c43975a08f](https://bsd-hardware.info/?probe=c43975a08f) | Apr 22, 2021 |
| ASUSTek       | PRIME X370-PRO              | [6251043541](https://bsd-hardware.info/?probe=6251043541) | Apr 22, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [a932c6d687](https://bsd-hardware.info/?probe=a932c6d687) | Apr 21, 2021 |
| Dell          | 0MWYPT A02                  | [92d895d2d4](https://bsd-hardware.info/?probe=92d895d2d4) | Apr 21, 2021 |
| ASRock        | J4105-ITX                   | [66eee76b50](https://bsd-hardware.info/?probe=66eee76b50) | Apr 21, 2021 |
| ASRock        | H110M-STX                   | [c98cb0e438](https://bsd-hardware.info/?probe=c98cb0e438) | Apr 19, 2021 |
| Supermicro    | X7SPA-HF                    | [418cc1382c](https://bsd-hardware.info/?probe=418cc1382c) | Apr 18, 2021 |
| ASUSTek       | P5Q-E                       | [be1821da8a](https://bsd-hardware.info/?probe=be1821da8a) | Apr 18, 2021 |
| MSI           | H81M-P33                    | [3a81fe2ee4](https://bsd-hardware.info/?probe=3a81fe2ee4) | Apr 18, 2021 |
| Unknown       | Unknown                     | [48090193c1](https://bsd-hardware.info/?probe=48090193c1) | Apr 17, 2021 |
| Unknown       | Unknown                     | [1c4a81b9a5](https://bsd-hardware.info/?probe=1c4a81b9a5) | Apr 17, 2021 |
| Unknown       | Unknown                     | [7b295345e6](https://bsd-hardware.info/?probe=7b295345e6) | Apr 17, 2021 |
| Unknown       | Unknown                     | [0c708350cd](https://bsd-hardware.info/?probe=0c708350cd) | Apr 17, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [76861635b1](https://bsd-hardware.info/?probe=76861635b1) | Apr 17, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [5b71c5420f](https://bsd-hardware.info/?probe=5b71c5420f) | Apr 15, 2021 |
| ASRock        | AM1H-ITX                    | [917ee44fe9](https://bsd-hardware.info/?probe=917ee44fe9) | Apr 15, 2021 |
| ASUSTek       | Maximus VIII HERO           | [7f9cdc62a2](https://bsd-hardware.info/?probe=7f9cdc62a2) | Apr 14, 2021 |
| Beckhoff A... | CB3163 G5                   | [25df932cdf](https://bsd-hardware.info/?probe=25df932cdf) | Apr 14, 2021 |
| Beckhoff A... | CX51x0 G2                   | [ab8247d8b5](https://bsd-hardware.info/?probe=ab8247d8b5) | Apr 14, 2021 |
| Gigabyte      | B450M DS3H-CF               | [431eaac648](https://bsd-hardware.info/?probe=431eaac648) | Apr 14, 2021 |
| ASRockRack    | EPYC3101D4I-2T              | [a2ef397dde](https://bsd-hardware.info/?probe=a2ef397dde) | Apr 13, 2021 |
| Supermicro    | X7SPA-HF                    | [6e9cbcbd1c](https://bsd-hardware.info/?probe=6e9cbcbd1c) | Apr 11, 2021 |
| MSI           | H81M-P33                    | [335cf58a3f](https://bsd-hardware.info/?probe=335cf58a3f) | Apr 11, 2021 |
| ASUSTek       | P5Q-E                       | [03a078e8b7](https://bsd-hardware.info/?probe=03a078e8b7) | Apr 11, 2021 |
| HP            | 3397                        | [93995c5c65](https://bsd-hardware.info/?probe=93995c5c65) | Apr 06, 2021 |
| Lenovo        | 3728 SDK0J40709 WIN 3259... | [acd4452f00](https://bsd-hardware.info/?probe=acd4452f00) | Apr 05, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | [f6cecd17ee](https://bsd-hardware.info/?probe=f6cecd17ee) | Apr 04, 2021 |
| Dell          | 0T2HR0 A01                  | [0ea0ca31bf](https://bsd-hardware.info/?probe=0ea0ca31bf) | Apr 04, 2021 |
| HP            | 158A                        | [ec84d94d08](https://bsd-hardware.info/?probe=ec84d94d08) | Apr 04, 2021 |
| Dell          | 0KV3RP A00                  | [95cff0e170](https://bsd-hardware.info/?probe=95cff0e170) | Apr 04, 2021 |
| ASUSTek       | M5A78L-M LE                 | [5486804bb1](https://bsd-hardware.info/?probe=5486804bb1) | Apr 03, 2021 |
| Dell          | 0KV3RP A00                  | [7b7495169b](https://bsd-hardware.info/?probe=7b7495169b) | Apr 03, 2021 |
| Dell          | 0KV3RP A00                  | [03e0a4e33d](https://bsd-hardware.info/?probe=03e0a4e33d) | Apr 03, 2021 |
| Colorful T... | C.Q1900M PRO V20            | [5283765cbe](https://bsd-hardware.info/?probe=5283765cbe) | Apr 03, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [7fc044cdb6](https://bsd-hardware.info/?probe=7fc044cdb6) | Apr 03, 2021 |
| ASUSTek       | M5A78L-M LE                 | [c6bf1a93f2](https://bsd-hardware.info/?probe=c6bf1a93f2) | Apr 02, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/FreeBSD/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| FreeBSD 13.1         | 91       | 7.74%   |
| FreeBSD 13.0         | 77       | 6.55%   |
| FreeBSD 12.2         | 65       | 5.53%   |
| FreeBSD 14.0-CURRENT | 53       | 4.51%   |
| FreeBSD 13.0-p5      | 43       | 3.66%   |
| FreeBSD 12.2-p2      | 41       | 3.49%   |
| FreeBSD 13.1-p2      | 40       | 3.4%    |
| FreeBSD 13.0-p4      | 35       | 2.98%   |
| FreeBSD 12.1-p8      | 35       | 2.98%   |
| FreeBSD 12.1-p10     | 34       | 2.89%   |
| FreeBSD 13.0-STABLE  | 33       | 2.81%   |
| FreeBSD 13.1-p5      | 32       | 2.72%   |
| FreeBSD 12.1-STABLE  | 29       | 2.47%   |
| FreeBSD 12.1-p5      | 29       | 2.47%   |
| FreeBSD 12.1-p7      | 28       | 2.38%   |
| FreeBSD 13.1-p7      | 26       | 2.21%   |
| FreeBSD 12.2-p3      | 24       | 2.04%   |
| FreeBSD 13.0-CURRENT | 22       | 1.87%   |
| FreeBSD 12.1         | 22       | 1.87%   |
| FreeBSD 13.0-p11     | 21       | 1.79%   |
| FreeBSD 13.0-p7      | 20       | 1.7%    |
| FreeBSD 12.2-p4      | 19       | 1.62%   |
| FreeBSD 13.0-p3      | 18       | 1.53%   |
| FreeBSD 13.2         | 16       | 1.36%   |
| FreeBSD 13.1-STABLE  | 16       | 1.36%   |
| FreeBSD 12.3         | 16       | 1.36%   |
| FreeBSD 12.2-STABLE  | 16       | 1.36%   |
| FreeBSD 13.0-p10     | 14       | 1.19%   |
| FreeBSD 13.1-p1      | 13       | 1.11%   |
| FreeBSD 13.0-p2      | 13       | 1.11%   |
| FreeBSD 12.2-p6      | 11       | 0.94%   |
| FreeBSD 12.1-p6      | 11       | 0.94%   |
| FreeBSD 13.1-p3      | 10       | 0.85%   |
| FreeBSD 13.0-p6      | 10       | 0.85%   |
| FreeBSD 12.2-p10     | 10       | 0.85%   |
| FreeBSD 12.1-p12     | 9        | 0.77%   |
| FreeBSD 13.1-p4      | 8        | 0.68%   |
| FreeBSD 12.1-p9      | 8        | 0.68%   |
| FreeBSD 12.3-p5      | 7        | 0.6%    |
| FreeBSD 12.2-p1      | 7        | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| FreeBSD | 946      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 877      | 92.71%  |
| arm64   | 29       | 3.07%   |
| i386    | 27       | 2.85%   |
| arm     | 7        | 0.74%   |
| powerpc | 4        | 0.42%   |
| sparc64 | 1        | 0.11%   |
| riscv   | 1        | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 421      | 42.92%  |
| KDE5          | 156      | 15.9%   |
| XFCE          | 123      | 12.54%  |
| TWM           | 57       | 5.81%   |
| GNOME         | 54       | 5.5%    |
| MATE          | 49       | 4.99%   |
| Openbox       | 24       | 2.45%   |
| i3            | 24       | 2.45%   |
| Fluxbox       | 9        | 0.92%   |
| Cinnamon      | 9        | 0.92%   |
| AwesomeWM     | 9        | 0.92%   |
| LXQt          | 7        | 0.71%   |
| LXDE          | 6        | 0.61%   |
| Lumina        | 5        | 0.51%   |
| Enlightenment | 5        | 0.51%   |
| DWM           | 4        | 0.41%   |
| CDE           | 3        | 0.31%   |
| xfwm          | 2        | 0.2%    |
| X-Cinnamon    | 2        | 0.2%    |
| Window Maker  | 2        | 0.2%    |
| GNUstep       | 2        | 0.2%    |
| xinitrc       | 1        | 0.1%    |
| spectrwm      | 1        | 0.1%    |
| plasma        | 1        | 0.1%    |
| Picom         | 1        | 0.1%    |
| KWin          | 1        | 0.1%    |
| Compton       | 1        | 0.1%    |
| bspwm         | 1        | 0.1%    |
| akonadi_newm  | 1        | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 501      | 52.08%  |
| Console | 450      | 46.78%  |
| Wayland | 10       | 1.04%   |
| Tty     | 1        | 0.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 613      | 63.2%   |
| SDDM    | 135      | 13.92%  |
| SLiM    | 73       | 7.53%   |
| XDM     | 61       | 6.29%   |
| LightDM | 48       | 4.95%   |
| GDM     | 35       | 3.61%   |
| Ly      | 5        | 0.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| C                | 358      | 35.91%  |
| Unknown          | 289      | 28.99%  |
| en_US            | 151      | 15.15%  |
| ru_RU            | 76       | 7.62%   |
| de_DE            | 20       | 2.01%   |
| en_GB            | 14       | 1.4%    |
| fr_FR            | 12       | 1.2%    |
| en_CA            | 7        | 0.7%    |
| uk_UA            | 6        | 0.6%    |
| pt_BR            | 6        | 0.6%    |
| ja_JP            | 6        | 0.6%    |
| zh_CN            | 5        | 0.5%    |
| it_IT            | 5        | 0.5%    |
| es_ES            | 4        | 0.4%    |
| en_AU            | 4        | 0.4%    |
| el_GR            | 4        | 0.4%    |
| ru_RU.KOI8-R     | 3        | 0.3%    |
| sv_SE            | 2        | 0.2%    |
| nb_NO            | 2        | 0.2%    |
| fi_FI            | 2        | 0.2%    |
| es_AR            | 2        | 0.2%    |
| en_IE            | 2        | 0.2%    |
| zh_TW            | 1        | 0.1%    |
| sv_SE.US-ASCII   | 1        | 0.1%    |
| pl_PL            | 1        | 0.1%    |
| nl_NL            | 1        | 0.1%    |
| it_IT.ISO8859-15 | 1        | 0.1%    |
| fr_FR.US-ASCII   | 1        | 0.1%    |
| fi_FI.ISO8859-15 | 1        | 0.1%    |
| et_EE.US-ASCII   | 1        | 0.1%    |
| es_MX            | 1        | 0.1%    |
| es_ES.ISO8859-15 | 1        | 0.1%    |
| en_US.utf-8      | 1        | 0.1%    |
| en_US.ISO8859-1  | 1        | 0.1%    |
| en_GB.US-ASCII   | 1        | 0.1%    |
| de_DE.ISO8859-1  | 1        | 0.1%    |
| de_CH            | 1        | 0.1%    |
| da_DK            | 1        | 0.1%    |
| cv_RU.US-ASCII   | 1        | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 536      | 55.78%  |
| BIOS | 425      | 44.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Zfs    | 596      | 62.28%  |
| Ufs    | 358      | 37.41%  |
| Cd9660 | 2        | 0.21%   |
| Nfs    | 1        | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 841      | 88.43%  |
| MBR     | 99       | 10.41%  |
| Unknown | 7        | 0.74%   |
| BSD     | 4        | 0.42%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 211      | 22.3%   |
| Gigabyte Technology        | 117      | 12.37%  |
| ASRock                     | 99       | 10.47%  |
| Hewlett-Packard            | 87       | 9.2%    |
| MSI                        | 76       | 8.03%   |
| Dell                       | 69       | 7.29%   |
| Unknown                    | 54       | 5.71%   |
| Intel                      | 38       | 4.02%   |
| Supermicro                 | 34       | 3.59%   |
| Lenovo                     | 19       | 2.01%   |
| Fujitsu                    | 15       | 1.59%   |
| PC Engines                 | 14       | 1.48%   |
| ASRockRack                 | 14       | 1.48%   |
| Acer                       | 10       | 1.06%   |
| Shuttle                    | 7        | 0.74%   |
| Biostar                    | 5        | 0.53%   |
| Beckhoff Automation        | 5        | 0.53%   |
| Wistron                    | 4        | 0.42%   |
| Huanan                     | 4        | 0.42%   |
| Foxconn                    | 4        | 0.42%   |
| Pegatron                   | 3        | 0.32%   |
| HPE                        | 3        | 0.32%   |
| Apple                      | 3        | 0.32%   |
| Google                     | 2        | 0.21%   |
| Gateway                    | 2        | 0.21%   |
| EVGA                       | 2        | 0.21%   |
| Deciso                     | 2        | 0.21%   |
| BESSTAR Tech               | 2        | 0.21%   |
| AMI                        | 2        | 0.21%   |
| ADI Engineering            | 2        | 0.21%   |
| VIA Technologies           | 1        | 0.11%   |
| TYAN Computer              | 1        | 0.11%   |
| TOPFEEL                    | 1        | 0.11%   |
| Sun Microsystems           | 1        | 0.11%   |
| SolidRun                   | 1        | 0.11%   |
| ShenZhen MinWin Technology | 1        | 0.11%   |
| Seeed Studio               | 1        | 0.11%   |
| Raspberry Pi Foundation    | 1        | 0.11%   |
| Radxa                      | 1        | 0.11%   |
| QTQD                       | 1        | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown                          | 55       | 5.81%   |
| ASUS All Series                  | 27       | 2.85%   |
| HP ProLiant MicroServer Gen8     | 10       | 1.06%   |
| Intel Nobilis                    | 9        | 0.95%   |
| PC Engines APU2                  | 7        | 0.74%   |
| HP ProLiant MicroServer          | 6        | 0.63%   |
| ASUS TUF GAMING X570-PLUS        | 6        | 0.63%   |
| MSI MS-7C02                      | 5        | 0.53%   |
| HP Z440 Workstation              | 5        | 0.53%   |
| Dell OptiPlex 9020               | 5        | 0.53%   |
| Supermicro X9SCL/X9SCM           | 4        | 0.42%   |
| HP Z620 Workstation              | 4        | 0.42%   |
| HP t620 Quad Core TC             | 4        | 0.42%   |
| HP Compaq Elite 8300 SFF         | 4        | 0.42%   |
| Gigabyte X570 I AORUS PRO WIFI   | 4        | 0.42%   |
| Gigabyte B450M DS3H              | 4        | 0.42%   |
| Fujitsu D3401-H2 S26361-D3401-H2 | 4        | 0.42%   |
| Dell PowerEdge T30               | 4        | 0.42%   |
| Dell OptiPlex 7040               | 4        | 0.42%   |
| Dell OptiPlex 3010               | 4        | 0.42%   |
| ASRock Q1900B-ITX                | 4        | 0.42%   |
| Wistron ProLiant ML110 G6        | 3        | 0.32%   |
| Supermicro X7SPA-HF              | 3        | 0.32%   |
| PC Engines apu4                  | 3        | 0.32%   |
| PC Engines APU                   | 3        | 0.32%   |
| MSI MS-7C37                      | 3        | 0.32%   |
| MSI MS-7B89                      | 3        | 0.32%   |
| MSI MS-7817                      | 3        | 0.32%   |
| MSI MS-7693                      | 3        | 0.32%   |
| MSI MS-7522                      | 3        | 0.32%   |
| HP Z600 Workstation              | 3        | 0.32%   |
| HP Z420 Workstation              | 3        | 0.32%   |
| HP t620 PLUS Quad Core TC        | 3        | 0.32%   |
| HP Compaq 6200 Pro MT PC         | 3        | 0.32%   |
| Gigabyte B550M AORUS PRO-P       | 3        | 0.32%   |
| ASUS SABERTOOTH 990FX R2.0       | 3        | 0.32%   |
| ASUS ROG STRIX X570-E GAMING     | 3        | 0.32%   |
| ASUS PRO B460M-C                 | 3        | 0.32%   |
| ASUS PRIME Z590-P                | 3        | 0.32%   |
| ASUS PRIME X370-PRO              | 3        | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 55       | 5.81%   |
| ASUS PRIME          | 40       | 4.23%   |
| Dell OptiPlex       | 38       | 4.02%   |
| ASUS All            | 27       | 2.85%   |
| ASUS ROG            | 23       | 2.43%   |
| HP Compaq           | 21       | 2.22%   |
| ASUS TUF            | 21       | 2.22%   |
| HP ProLiant         | 20       | 2.11%   |
| Dell Precision      | 13       | 1.37%   |
| ASRock X570         | 11       | 1.16%   |
| Lenovo ThinkCentre  | 9        | 0.95%   |
| Intel Nobilis       | 9        | 0.95%   |
| Gigabyte X570       | 9        | 0.95%   |
| ASRock X370         | 8        | 0.85%   |
| PC Engines APU2     | 7        | 0.74%   |
| HP t620             | 7        | 0.74%   |
| Gigabyte B450M      | 7        | 0.74%   |
| Dell PowerEdge      | 7        | 0.74%   |
| HP EliteDesk        | 6        | 0.63%   |
| ASUS PRO            | 6        | 0.63%   |
| MSI MS-7C02         | 5        | 0.53%   |
| HP Z440             | 5        | 0.53%   |
| ASRock 970          | 5        | 0.53%   |
| Acer Aspire         | 5        | 0.53%   |
| Wistron ProLiant    | 4        | 0.42%   |
| Supermicro X9SCL    | 4        | 0.42%   |
| HP Z620             | 4        | 0.42%   |
| HP ProDesk          | 4        | 0.42%   |
| Gigabyte B550M      | 4        | 0.42%   |
| Fujitsu ESPRIMO     | 4        | 0.42%   |
| Fujitsu D3401-H2    | 4        | 0.42%   |
| ASUS SABERTOOTH     | 4        | 0.42%   |
| ASUS P5Q            | 4        | 0.42%   |
| ASUS M5A78L-M       | 4        | 0.42%   |
| ASRock Q1900B-ITX   | 4        | 0.42%   |
| ASRock B550         | 4        | 0.42%   |
| ASRock B450         | 4        | 0.42%   |
| Acer Veriton        | 4        | 0.42%   |
| Supermicro X7SPA-HF | 3        | 0.32%   |
| PC Engines apu4     | 3        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 115      | 12.16%  |
| 2018    | 94       | 9.94%   |
| 2020    | 87       | 9.2%    |
| 2013    | 70       | 7.4%    |
| 2014    | 66       | 6.98%   |
| 2021    | 64       | 6.77%   |
| 2011    | 62       | 6.55%   |
| 2012    | 56       | 5.92%   |
| 2017    | 51       | 5.39%   |
| 2015    | 42       | 4.44%   |
| Unknown | 42       | 4.44%   |
| 2010    | 41       | 4.33%   |
| 2016    | 40       | 4.23%   |
| 2009    | 32       | 3.38%   |
| 2008    | 26       | 2.75%   |
| 2022    | 25       | 2.64%   |
| 2007    | 13       | 1.37%   |
| 2006    | 5        | 0.53%   |
| 2005    | 4        | 0.42%   |
| 2004    | 4        | 0.42%   |
| 2023    | 2        | 0.21%   |
| 2003    | 2        | 0.21%   |
| 2002    | 2        | 0.21%   |
| 2001    | 1        | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 946      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 924      | 97.67%  |
| Yes  | 22       | 2.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 224      | 23.41%  |
| 8.01-16.0       | 220      | 22.99%  |
| 32.01-64.0      | 188      | 19.64%  |
| 4.01-8.0        | 111      | 11.6%   |
| 64.01-256.0     | 104      | 10.87%  |
| 2.01-3.0        | 32       | 3.34%   |
| 24.01-32.0      | 21       | 2.19%   |
| 0.51-1.0        | 21       | 2.19%   |
| 3.01-4.0        | 18       | 1.88%   |
| 0.01-0.5        | 10       | 1.04%   |
| 1.01-2.0        | 6        | 0.63%   |
| More than 256.0 | 1        | 0.1%    |
| Unknown         | 1        | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 298      | 29.77%  |
| 0.51-1.0    | 293      | 29.27%  |
| 1.01-2.0    | 200      | 19.98%  |
| 2.01-3.0    | 45       | 4.5%    |
| 3.01-4.0    | 43       | 4.3%    |
| 4.01-8.0    | 40       | 4%      |
| 8.01-16.0   | 24       | 2.4%    |
| 0           | 15       | 1.5%    |
| 24.01-32.0  | 14       | 1.4%    |
| 32.01-64.0  | 10       | 1%      |
| 16.01-24.0  | 10       | 1%      |
| 64.01-256.0 | 8        | 0.8%    |
| Unknown     | 1        | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 276      | 27.74%  |
| 2      | 239      | 24.02%  |
| 3      | 150      | 15.08%  |
| 4      | 112      | 11.26%  |
| 5      | 67       | 6.73%   |
| 0      | 50       | 5.03%   |
| 6      | 39       | 3.92%   |
| 7      | 21       | 2.11%   |
| 8      | 10       | 1.01%   |
| 9      | 7        | 0.7%    |
| 10     | 6        | 0.6%    |
| 14     | 3        | 0.3%    |
| 12     | 3        | 0.3%    |
| 11     | 3        | 0.3%    |
| 23     | 2        | 0.2%    |
| 13     | 2        | 0.2%    |
| 21     | 1        | 0.1%    |
| 19     | 1        | 0.1%    |
| 18     | 1        | 0.1%    |
| 17     | 1        | 0.1%    |
| 15     | 1        | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 653      | 68.31%  |
| Yes       | 303      | 31.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 910      | 96.09%  |
| No        | 37       | 3.91%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 724      | 75.81%  |
| Yes       | 231      | 24.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 792      | 83.11%  |
| Yes       | 161      | 16.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 223      | 23.45%  |
| Russia      | 136      | 14.3%   |
| Germany     | 104      | 10.94%  |
| Canada      | 46       | 4.84%   |
| France      | 44       | 4.63%   |
| UK          | 34       | 3.58%   |
| Poland      | 27       | 2.84%   |
| Ukraine     | 23       | 2.42%   |
| Netherlands | 23       | 2.42%   |
| Australia   | 20       | 2.1%    |
| Japan       | 18       | 1.89%   |
| Czechia     | 18       | 1.89%   |
| Brazil      | 17       | 1.79%   |
| Finland     | 15       | 1.58%   |
| Sweden      | 14       | 1.47%   |
| Italy       | 14       | 1.47%   |
| Switzerland | 12       | 1.26%   |
| Spain       | 12       | 1.26%   |
| China       | 11       | 1.16%   |
| Greece      | 10       | 1.05%   |
| Romania     | 9        | 0.95%   |
| Norway      | 8        | 0.84%   |
| Thailand    | 7        | 0.74%   |
| Belgium     | 7        | 0.74%   |
| Austria     | 7        | 0.74%   |
| Ireland     | 6        | 0.63%   |
| India       | 6        | 0.63%   |
| Hungary     | 6        | 0.63%   |
| Taiwan      | 5        | 0.53%   |
| Serbia      | 5        | 0.53%   |
| Denmark     | 5        | 0.53%   |
| Bulgaria    | 5        | 0.53%   |
| Slovenia    | 4        | 0.42%   |
| New Zealand | 4        | 0.42%   |
| Indonesia   | 4        | 0.42%   |
| Estonia     | 4        | 0.42%   |
| Argentina   | 4        | 0.42%   |
| Mexico      | 3        | 0.32%   |
| Malaysia    | 3        | 0.32%   |
| UAE         | 2        | 0.21%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Moscow               | 49       | 4.84%   |
| Krasnodar            | 14       | 1.38%   |
| Grand Rapids         | 14       | 1.38%   |
| Kyiv                 | 12       | 1.18%   |
| Berlin               | 12       | 1.18%   |
| Ludwigsburg          | 11       | 1.09%   |
| Helsinki             | 9        | 0.89%   |
| Yekaterinburg        | 8        | 0.79%   |
| Tuklaty              | 8        | 0.79%   |
| St Petersburg        | 8        | 0.79%   |
| Montreal             | 8        | 0.79%   |
| Sydney               | 7        | 0.69%   |
| Warsaw               | 6        | 0.59%   |
| Rochester            | 6        | 0.59%   |
| Poway                | 6        | 0.59%   |
| Portland             | 6        | 0.59%   |
| Paris                | 6        | 0.59%   |
| Novosibirsk          | 6        | 0.59%   |
| London               | 6        | 0.59%   |
| Chicago              | 6        | 0.59%   |
| Brooklyn             | 6        | 0.59%   |
| Amsterdam            | 6        | 0.59%   |
| Zurich               | 5        | 0.49%   |
| Zaporizhzhya         | 5        | 0.49%   |
| Vienna               | 5        | 0.49%   |
| Toronto              | 5        | 0.49%   |
| Teaneck              | 5        | 0.49%   |
| Ozersk               | 5        | 0.49%   |
| Madrid               | 5        | 0.49%   |
| Kamensk-Ural'skiy    | 5        | 0.49%   |
| Falkenstein          | 5        | 0.49%   |
| City of Saint Peters | 5        | 0.49%   |
| Bellevue             | 5        | 0.49%   |
| Bangkok              | 5        | 0.49%   |
| Athens               | 5        | 0.49%   |
| Tamm                 | 4        | 0.39%   |
| Stockholm            | 4        | 0.39%   |
| Soisy-sur-Seine      | 4        | 0.39%   |
| Sofia                | 4        | 0.39%   |
| Roubaix              | 4        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 383      | 1259   | 23.5%   |
| Seagate             | 297      | 766    | 18.22%  |
| Samsung Electronics | 239      | 556    | 14.66%  |
| Toshiba             | 102      | 233    | 6.26%   |
| Crucial             | 90       | 139    | 5.52%   |
| Kingston            | 89       | 118    | 5.46%   |
| Intel               | 58       | 119    | 3.56%   |
| Hitachi             | 45       | 104    | 2.76%   |
| HGST                | 39       | 87     | 2.39%   |
| SanDisk             | 35       | 53     | 2.15%   |
| A-DATA Technology   | 31       | 42     | 1.9%    |
| Transcend           | 15       | 21     | 0.92%   |
| SK hynix            | 12       | 14     | 0.74%   |
| OCZ                 | 12       | 15     | 0.74%   |
| Corsair             | 12       | 30     | 0.74%   |
| Micron Technology   | 11       | 23     | 0.67%   |
| GOODRAM             | 11       | 21     | 0.67%   |
| Phison              | 10       | 13     | 0.61%   |
| SPCC                | 8        | 25     | 0.49%   |
| Maxtor              | 8        | 12     | 0.49%   |
| Hewlett-Packard     | 8        | 22     | 0.49%   |
| PNY                 | 7        | 9      | 0.43%   |
| Patriot             | 7        | 10     | 0.43%   |
| Plextor             | 6        | 12     | 0.37%   |
| Intenso             | 6        | 7      | 0.37%   |
| Silicon Motion      | 4        | 5      | 0.25%   |
| KIOXIA-EXCERIA      | 4        | 8      | 0.25%   |
| KingSpec            | 4        | 7      | 0.25%   |
| FORESEE             | 4        | 4      | 0.25%   |
| Apacer              | 4        | 4      | 0.25%   |
| Vaseky              | 3        | 3      | 0.18%   |
| Mushkin             | 3        | 4      | 0.18%   |
| Hoodisk             | 3        | 5      | 0.18%   |
| Gigabyte Technology | 3        | 3      | 0.18%   |
| China               | 3        | 3      | 0.18%   |
| Verbatim            | 2        | 2      | 0.12%   |
| T-FORCE             | 2        | 3      | 0.12%   |
| Supermicro          | 2        | 2      | 0.12%   |
| Smartbuy            | 2        | 2      | 0.12%   |
| ORICO               | 2        | 2      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB        | 22       | 1.08%   |
| Seagate ST1000DM010-2EP102 1TB  | 22       | 1.08%   |
| Samsung SSD 850 EVO 250GB       | 22       | 1.08%   |
| WDC WD30EFRX-68EUZN0 3TB        | 18       | 0.88%   |
| Kingston SA400S37240G 240GB     | 18       | 0.88%   |
| WDC WD800JD-75MSA3 80GB         | 16       | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB  | 15       | 0.74%   |
| WDC WD40EFRX-68N32N0 4TB        | 14       | 0.69%   |
| Toshiba DT01ACA100 1TB          | 14       | 0.69%   |
| Kingston SA400S37120G 120GB     | 14       | 0.69%   |
| Seagate ST4000DM000-1F2168 4TB  | 13       | 0.64%   |
| Crucial CT240BX500SSD1 240GB    | 12       | 0.59%   |
| Seagate ST500DM002-1BD142 500GB | 11       | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB  | 11       | 0.54%   |
| Samsung SSD 860 EVO 250GB       | 11       | 0.54%   |
| Seagate ST3500418AS 500GB       | 10       | 0.49%   |
| WDC WD20EFRX-68EUZN0 2TB        | 9        | 0.44%   |
| Seagate ST2000DM001-1CH164 2TB  | 9        | 0.44%   |
| Seagate ST1000DM003-1ER162 1TB  | 9        | 0.44%   |
| Samsung SSD 860 EVO 1TB         | 9        | 0.44%   |
| Samsung SSD 850 EVO 500GB       | 9        | 0.44%   |
| Crucial CT250MX500SSD1 250GB    | 9        | 0.44%   |
| WDC WD20EZRZ-00Z5HB0 2TB        | 8        | 0.39%   |
| WDC WD20EARX-00PASB0 2TB        | 8        | 0.39%   |
| Seagate ST4000VN008-2DR166 4TB  | 8        | 0.39%   |
| Seagate ST4000DM004-2CV104 4TB  | 8        | 0.39%   |
| Samsung SSD 980 PRO 1TB         | 8        | 0.39%   |
| Samsung SSD 970 EVO Plus 500GB  | 8        | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB    | 8        | 0.39%   |
| Samsung SSD 870 EVO 1TB         | 8        | 0.39%   |
| Samsung SSD 860 EVO 500GB       | 8        | 0.39%   |
| WDC WD40EFRX-68WT0N0 4TB        | 7        | 0.34%   |
| WDC WD10EFRX-68FYTN0 1TB        | 7        | 0.34%   |
| Seagate ST8000DM004-2CX188 8TB  | 7        | 0.34%   |
| Seagate ST3500413AS 500GB       | 7        | 0.34%   |
| Samsung SSD 970 EVO 1TB         | 7        | 0.34%   |
| WDC WD60EFRX-68L0BN1 6TB        | 6        | 0.29%   |
| WDC WD30EFRX-68AX9N0 3TB        | 6        | 0.29%   |
| WDC WD10EZEX-22MFCA0 1TB        | 6        | 0.29%   |
| Seagate ST3500312CS 500GB       | 6        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| WDC                  | 343      | 1144   | 39.33%  |
| Seagate              | 292      | 756    | 33.49%  |
| Toshiba              | 93       | 221    | 10.67%  |
| Hitachi              | 45       | 104    | 5.16%   |
| HGST                 | 39       | 87     | 4.47%   |
| Samsung Electronics  | 35       | 55     | 4.01%   |
| Maxtor               | 8        | 12     | 0.92%   |
| Hewlett-Packard      | 5        | 14     | 0.57%   |
| HPT                  | 2        | 9      | 0.23%   |
| Apple                | 2        | 3      | 0.23%   |
| WD MediaMax          | 1        | 2      | 0.11%   |
| QUANTUM              | 1        | 2      | 0.11%   |
| MaxDigital           | 1        | 1      | 0.11%   |
| IBM/Hitachi          | 1        | 1      | 0.11%   |
| IBM                  | 1        | 1      | 0.11%   |
| HPE                  | 1        | 4      | 0.11%   |
| ExcelStor Technology | 1        | 4      | 0.11%   |
| Areca                | 1        | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 147      | 355    | 24.66%  |
| Crucial             | 78       | 119    | 13.09%  |
| Kingston            | 77       | 98     | 12.92%  |
| Intel               | 45       | 101    | 7.55%   |
| WDC                 | 35       | 63     | 5.87%   |
| SanDisk             | 35       | 53     | 5.87%   |
| A-DATA Technology   | 25       | 34     | 4.19%   |
| Transcend           | 13       | 18     | 2.18%   |
| OCZ                 | 12       | 15     | 2.01%   |
| Micron Technology   | 9        | 20     | 1.51%   |
| Toshiba             | 8        | 8      | 1.34%   |
| GOODRAM             | 8        | 17     | 1.34%   |
| SK hynix            | 7        | 9      | 1.17%   |
| Patriot             | 7        | 10     | 1.17%   |
| Intenso             | 6        | 7      | 1.01%   |
| Corsair             | 6        | 8      | 1.01%   |
| SPCC                | 5        | 21     | 0.84%   |
| Plextor             | 5        | 8      | 0.84%   |
| Seagate             | 4        | 6      | 0.67%   |
| PNY                 | 4        | 5      | 0.67%   |
| KingSpec            | 4        | 7      | 0.67%   |
| Apacer              | 4        | 4      | 0.67%   |
| Vaseky              | 3        | 3      | 0.5%    |
| Hoodisk             | 3        | 5      | 0.5%    |
| FORESEE             | 3        | 3      | 0.5%    |
| China               | 3        | 3      | 0.5%    |
| Verbatim            | 2        | 2      | 0.34%   |
| Supermicro          | 2        | 2      | 0.34%   |
| Smartbuy            | 2        | 2      | 0.34%   |
| ORICO               | 2        | 2      | 0.34%   |
| Mushkin             | 2        | 2      | 0.34%   |
| LITEONIT            | 2        | 2      | 0.34%   |
| LITEON              | 2        | 2      | 0.34%   |
| Kston               | 2        | 2      | 0.34%   |
| Innodisk            | 2        | 2      | 0.34%   |
| Hikvision           | 2        | 2      | 0.34%   |
| Emtec               | 2        | 2      | 0.34%   |
| AMD                 | 2        | 3      | 0.34%   |
| ZTC                 | 1        | 2      | 0.17%   |
| walram              | 1        | 1      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 639      | 2421   | 47.65%  |
| SSD  | 504      | 1055   | 37.58%  |
| NVMe | 198      | 365    | 14.77%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 847      | 3476   | 81.05%  |
| NVMe | 198      | 365    | 18.95%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 608      | 1249   | 45.27%  |
| 0.51-1.0   | 290      | 615    | 21.59%  |
| 1.01-2.0   | 162      | 460    | 12.06%  |
| 3.01-4.0   | 108      | 356    | 8.04%   |
| 4.01-10.0  | 93       | 497    | 6.92%   |
| 2.01-3.0   | 60       | 203    | 4.47%   |
| 10.01-20.0 | 21       | 95     | 1.56%   |
| 20.01-50.0 | 1        | 1      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 261      | 26.5%   |
| 251-500        | 186      | 18.88%  |
| 501-1000       | 138      | 14.01%  |
| 51-100         | 120      | 12.18%  |
| 21-50          | 73       | 7.41%   |
| 1-20           | 66       | 6.7%    |
| 1001-2000      | 60       | 6.09%   |
| More than 3000 | 48       | 4.87%   |
| 2001-3000      | 19       | 1.93%   |
| Unknown        | 14       | 1.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 666      | 67.75%  |
| 21-50          | 134      | 13.63%  |
| 51-100         | 52       | 5.29%   |
| 101-250        | 29       | 2.95%   |
| 251-500        | 26       | 2.64%   |
| 501-1000       | 21       | 2.14%   |
| More than 3000 | 17       | 1.73%   |
| 1001-2000      | 14       | 1.42%   |
| Unknown        | 14       | 1.42%   |
| 2001-3000      | 9        | 0.92%   |
| 0              | 1        | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD30EFRX-68EUZN0 3TB            | 6        | 18     | 2.23%   |
| Seagate ST3500413AS 500GB           | 6        | 9      | 2.23%   |
| WDC WD20EFRX-68EUZN0 2TB            | 5        | 12     | 1.86%   |
| Samsung Electronics SSD 870 EVO 1TB | 5        | 7      | 1.86%   |
| WDC WD40EFRX-68WT0N0 4TB            | 3        | 7      | 1.12%   |
| Seagate ST3500418AS 500GB           | 3        | 6      | 1.12%   |
| Seagate ST2000DM001-9YN164 2TB      | 3        | 3      | 1.12%   |
| Seagate ST1000DM003-1CH162 1TB      | 3        | 4      | 1.12%   |
| Samsung Electronics HD501LJ 500GB   | 3        | 4      | 1.12%   |
| Samsung Electronics HD103UJ 1TB     | 3        | 6      | 1.12%   |
| Intel SSDSA2M080G2GC 80GB           | 3        | 3      | 1.12%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 2        | 2      | 0.74%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 5      | 0.74%   |
| WDC WD20EARS-00MVWB0 2TB            | 2        | 2      | 0.74%   |
| WDC WD2002FYPS-02W3B0 2TB           | 2        | 2      | 0.74%   |
| WDC WD2002FYPS-01U1B0 2TB           | 2        | 3      | 0.74%   |
| WDC WD2000FYYZ-01UL1B2 2TB          | 2        | 4      | 0.74%   |
| WDC WD2000FYYZ-01UL1B1 2TB          | 2        | 4      | 0.74%   |
| WDC WD15EADS-00P8B0 1.5TB           | 2        | 2      | 0.74%   |
| Seagate ST9250827AS 250GB           | 2        | 3      | 0.74%   |
| Seagate ST500DM002-1BD142 500GB     | 2        | 2      | 0.74%   |
| Seagate ST500DM002-1BC142 500GB     | 2        | 2      | 0.74%   |
| Seagate ST380013AS 80GB             | 2        | 3      | 0.74%   |
| Seagate ST2000DM008-2FR102 2TB      | 2        | 2      | 0.74%   |
| Seagate ST2000DM006-2DM164 2TB      | 2        | 2      | 0.74%   |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 6      | 0.74%   |
| Seagate ST1000DM003-1ER162 1TB      | 2        | 2      | 0.74%   |
| Samsung Electronics HD204UI 2TB     | 2        | 3      | 0.74%   |
| Samsung Electronics HD154UI 1.5TB   | 2        | 2      | 0.74%   |
| Maxtor 6Y080P0 82GB                 | 2        | 3      | 0.74%   |
| Kingston SMS200S360G 64GB           | 2        | 2      | 0.74%   |
| Kingston SA400S37120G 120GB         | 2        | 2      | 0.74%   |
| Intel SSDSC2CW120A3 120GB           | 2        | 2      | 0.74%   |
| Intel SSDSC2BW480A4 480GB           | 2        | 2      | 0.74%   |
| Hitachi HUA722020ALA330 2TB         | 2        | 3      | 0.74%   |
| Hitachi HDS721010CLA332 1TB         | 2        | 3      | 0.74%   |
| HGST HTS725050A7E630 500GB          | 2        | 6      | 0.74%   |
| Crucial CT480M500SSD1 480GB         | 2        | 3      | 0.74%   |
| WDC WDS240G2G0A-00JH30 240GB        | 1        | 1      | 0.37%   |
| WDC WD80EDAZ-11TA3A0 8TB            | 1        | 2      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| WDC                  | 75       | 150    | 29.64%  |
| Seagate              | 66       | 93     | 26.09%  |
| Samsung Electronics  | 27       | 38     | 10.67%  |
| Hitachi              | 14       | 18     | 5.53%   |
| Intel                | 12       | 16     | 4.74%   |
| Toshiba              | 11       | 30     | 4.35%   |
| Crucial              | 7        | 12     | 2.77%   |
| Kingston             | 6        | 6      | 2.37%   |
| HGST                 | 6        | 11     | 2.37%   |
| Maxtor               | 5        | 9      | 1.98%   |
| SanDisk              | 4        | 5      | 1.58%   |
| A-DATA Technology    | 3        | 4      | 1.19%   |
| SK hynix             | 2        | 4      | 0.79%   |
| OCZ                  | 2        | 3      | 0.79%   |
| Micron Technology    | 2        | 6      | 0.79%   |
| Hewlett-Packard      | 2        | 4      | 0.79%   |
| Corsair              | 2        | 4      | 0.79%   |
| walram               | 1        | 1      | 0.4%    |
| SPCC                 | 1        | 1      | 0.4%    |
| Plextor              | 1        | 1      | 0.4%    |
| LITEON               | 1        | 1      | 0.4%    |
| GK                   | 1        | 1      | 0.4%    |
| ExcelStor Technology | 1        | 2      | 0.4%    |
| AMD                  | 1        | 2      | 0.4%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| WDC                  | 74       | 149    | 38.14%  |
| Seagate              | 65       | 92     | 33.51%  |
| Samsung Electronics  | 16       | 21     | 8.25%   |
| Hitachi              | 14       | 18     | 7.22%   |
| Toshiba              | 11       | 30     | 5.67%   |
| HGST                 | 6        | 11     | 3.09%   |
| Maxtor               | 5        | 9      | 2.58%   |
| Hewlett-Packard      | 2        | 4      | 1.03%   |
| ExcelStor Technology | 1        | 2      | 0.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 177      | 336    | 75.64%  |
| SSD  | 56       | 85     | 23.93%  |
| NVMe | 1        | 1      | 0.43%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB     | 1        | 1      | 25%     |
| Toshiba MG05ACA800E 8TB      | 1        | 1      | 25%     |
| Maxtor 6E040L0 41GB          | 1        | 1      | 25%     |
| Crucial M4-CT256M4SSD1 256GB | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 25%     |
| Toshiba | 1        | 1      | 25%     |
| Maxtor  | 1        | 1      | 25%     |
| Crucial | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 833      | 3320   | 76.14%  |
| Malfunc  | 219      | 422    | 20.02%  |
| Detected | 38       | 95     | 3.47%   |
| Failed   | 4        | 4      | 0.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 594      | 43.71%  |
| AMD                              | 288      | 21.19%  |
| Samsung Electronics              | 92       | 6.77%   |
| ASMedia Technology               | 61       | 4.49%   |
| Broadcom / LSI                   | 46       | 3.38%   |
| Marvell Technology Group         | 45       | 3.31%   |
| SanDisk                          | 35       | 2.58%   |
| Silicon Motion                   | 24       | 1.77%   |
| Phison Electronics               | 23       | 1.69%   |
| JMicron Technology               | 23       | 1.69%   |
| Nvidia                           | 17       | 1.25%   |
| Kingston Technology Company      | 15       | 1.1%    |
| Micron/Crucial Technology        | 11       | 0.81%   |
| Silicon Image                    | 9        | 0.66%   |
| Adaptec                          | 8        | 0.59%   |
| VIA Technologies                 | 7        | 0.52%   |
| ADATA Technology                 | 7        | 0.52%   |
| Areca Technology                 | 6        | 0.44%   |
| SK hynix                         | 5        | 0.37%   |
| Seagate Technology               | 4        | 0.29%   |
| Micron Technology                | 4        | 0.29%   |
| KIOXIA                           | 4        | 0.29%   |
| Chelsio Communications           | 4        | 0.29%   |
| Toshiba                          | 3        | 0.22%   |
| Silicon Integrated Systems [SiS] | 3        | 0.22%   |
| Integrated Technology Express    | 3        | 0.22%   |
| Hewlett-Packard                  | 3        | 0.22%   |
| 3ware                            | 3        | 0.22%   |
| Realtek Semiconductor            | 2        | 0.15%   |
| Promise Technology               | 2        | 0.15%   |
| Lite-On Technology               | 2        | 0.15%   |
| HighPoint Technologies           | 2        | 0.15%   |
| ULi Electronics                  | 1        | 0.07%   |
| Transcend                        | 1        | 0.07%   |
| Lenovo                           | 1        | 0.07%   |
| Broadcom                         | 1        | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 169      | 10.17%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 64       | 3.85%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 56       | 3.37%   |
| AMD 400 Series Chipset SATA Controller                                         | 54       | 3.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 53       | 3.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 53       | 3.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 49       | 2.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 49       | 2.95%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 35       | 2.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 33       | 1.99%   |
| AMD 500 Series Chipset SATA Controller                                         | 31       | 1.87%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 30       | 1.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 29       | 1.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 23       | 1.38%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 23       | 1.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 21       | 1.26%   |
| Intel SATA Controller [RAID mode]                                              | 21       | 1.26%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 21       | 1.26%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 20       | 1.2%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 18       | 1.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 18       | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 17       | 1.02%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 17       | 1.02%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 17       | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                          | 16       | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 16       | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 14       | 0.84%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 14       | 0.84%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 14       | 0.84%   |
| Phison E12 NVMe Controller                                                     | 13       | 0.78%   |
| JMicron JMB363 SATA/IDE Controller                                             | 13       | 0.78%   |
| AMD X370 Series Chipset SATA Controller                                        | 13       | 0.78%   |
| AMD FCH SATA Controller [IDE mode]                                             | 13       | 0.78%   |
| Samsung NVMe SSD Controller 980                                                | 12       | 0.72%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 12       | 0.72%   |
| AMD 300 Series Chipset SATA Controller                                         | 12       | 0.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 11       | 0.66%   |
| Intel SSD 660P Series                                                          | 10       | 0.6%    |
| Intel C600/X79 series chipset SATA RAID Controller                             | 10       | 0.6%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 10       | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 754      | 57.34%  |
| NVMe | 226      | 17.19%  |
| IDE  | 202      | 15.36%  |
| RAID | 64       | 4.87%   |
| SAS  | 47       | 3.57%   |
| SCSI | 22       | 1.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 599      | 63.12%  |
| AMD      | 303      | 31.93%  |
| ARM      | 31       | 3.27%   |
| Unknown  | 8        | 0.84%   |
| IBM      | 2        | 0.21%   |
| VIA      | 1        | 0.11%   |
| Sun      | 1        | 0.11%   |
| Research | 1        | 0.11%   |
| NXP      | 1        | 0.11%   |
| Motorola | 1        | 0.11%   |
| i        | 1        | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 14       | 1.46%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 11       | 1.15%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 11       | 1.15%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 11       | 1.15%   |
| AMD GX-412TC SOC                            | 11       | 1.15%   |
| AMD FX-8350 Eight-Core Processor            | 11       | 1.15%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 9        | 0.94%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 9        | 0.94%   |
| ARM Cortex-A53 r0p4                         | 9        | 0.94%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 9        | 0.94%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 9        | 0.94%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 9        | 0.94%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 8        | 0.84%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 8        | 0.84%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 8        | 0.84%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 8        | 0.84%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 8        | 0.84%   |
|                                             | 8        | 0.84%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 7        | 0.73%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 7        | 0.73%   |
| AMD Ryzen 5 3600 6-Core Processor           | 7        | 0.73%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 7        | 0.73%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 7        | 0.73%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 6        | 0.63%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 6        | 0.63%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 6        | 0.63%   |
| Intel Celeron CPU N3150 @ 1.60GHz           | 6        | 0.63%   |
| Intel Celeron CPU G1610T @ 2.30GHz          | 6        | 0.63%   |
| ARM Cortex-A55 r2p0                         | 6        | 0.63%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 6        | 0.63%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 6        | 0.63%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 5        | 0.52%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 5        | 0.52%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 5        | 0.52%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 5        | 0.52%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 0.52%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 5        | 0.52%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 5        | 0.52%   |
| Intel Atom CPU 330 @ 1.60GHz                | 5        | 0.52%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 5        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 130      | 13.66%  |
| Intel Core i7           | 110      | 11.55%  |
| Intel Xeon              | 107      | 11.24%  |
| AMD Ryzen 7             | 59       | 6.2%    |
| AMD Ryzen 5             | 51       | 5.36%   |
| Intel Celeron           | 50       | 5.25%   |
| Intel Core i3           | 47       | 4.94%   |
| Other                   | 46       | 4.83%   |
| AMD Ryzen 9             | 35       | 3.68%   |
| Intel Atom              | 30       | 3.15%   |
| ARM Cortex              | 28       | 2.94%   |
| AMD FX                  | 28       | 2.94%   |
| Intel Pentium           | 24       | 2.52%   |
| Intel Core 2 Duo        | 24       | 2.52%   |
| AMD GX                  | 22       | 2.31%   |
| AMD Ryzen 3             | 17       | 1.79%   |
| Intel Core 2 Quad       | 13       | 1.37%   |
| Intel Pentium 4         | 12       | 1.26%   |
| AMD Ryzen Threadripper  | 9        | 0.95%   |
| Intel Core i9           | 8        | 0.84%   |
| AMD Turion II Neo       | 7        | 0.74%   |
| AMD Phenom II X6        | 7        | 0.74%   |
| AMD Athlon 64 X2        | 7        | 0.74%   |
| AMD Athlon              | 6        | 0.63%   |
| AMD A10                 | 6        | 0.63%   |
| Intel Core 2            | 5        | 0.53%   |
| AMD Phenom II X4        | 5        | 0.53%   |
| AMD Phenom              | 5        | 0.53%   |
| Intel Pentium Gold      | 4        | 0.42%   |
| AMD Ryzen 5 PRO         | 4        | 0.42%   |
| AMD G                   | 4        | 0.42%   |
| AMD Sempron             | 3        | 0.32%   |
| AMD Ryzen 7 PRO         | 3        | 0.32%   |
| AMD Opteron             | 3        | 0.32%   |
| AMD A4                  | 3        | 0.32%   |
| Intel Xeon Bronze       | 2        | 0.21%   |
| Intel Pentium Dual-Core | 2        | 0.21%   |
| Intel Pentium D         | 2        | 0.21%   |
| AMD Phenom II X2        | 2        | 0.21%   |
| AMD EPYC                | 2        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 339      | 35.57%  |
| 2       | 160      | 16.79%  |
| Unknown | 89       | 9.34%   |
| 8       | 79       | 8.29%   |
| 6       | 78       | 8.18%   |
| 16      | 71       | 7.45%   |
| 12      | 53       | 5.56%   |
| 24      | 22       | 2.31%   |
| 32      | 21       | 2.2%    |
| 1       | 21       | 2.2%    |
| 10      | 9        | 0.94%   |
| 64      | 3        | 0.31%   |
| 14      | 2        | 0.21%   |
| 3       | 2        | 0.21%   |
| 48      | 1        | 0.1%    |
| 28      | 1        | 0.1%    |
| 20      | 1        | 0.1%    |
| 11      | 1        | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 885      | 93.16%  |
| Unknown | 40       | 4.21%   |
| 2       | 24       | 2.53%   |
| 4       | 1        | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 551      | 58.12%  |
| 2       | 296      | 31.22%  |
| Unknown | 101      | 10.65%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 93       | 9.76%   |
| IvyBridge     | 81       | 8.5%    |
| KabyLake      | 78       | 8.18%   |
| Unknown       | 69       | 7.24%   |
| Zen 2         | 67       | 7.03%   |
| SandyBridge   | 65       | 6.82%   |
| Skylake       | 48       | 5.04%   |
| Zen 3         | 42       | 4.41%   |
| Zen+          | 39       | 4.09%   |
| Penryn        | 37       | 3.88%   |
| Zen           | 35       | 3.67%   |
| K10           | 32       | 3.36%   |
| Piledriver    | 31       | 3.25%   |
| Silvermont    | 27       | 2.83%   |
| CometLake     | 25       | 2.62%   |
| Westmere      | 22       | 2.31%   |
| Core          | 21       | 2.2%    |
| Bonnell       | 20       | 2.1%    |
| NetBurst      | 18       | 1.89%   |
| Puma          | 16       | 1.68%   |
| Nehalem       | 15       | 1.57%   |
| Broadwell     | 13       | 1.36%   |
| Jaguar        | 12       | 1.26%   |
| K8 Hammer     | 10       | 1.05%   |
| Goldmont      | 7        | 0.73%   |
| Bobcat        | 7        | 0.73%   |
| Goldmont plus | 6        | 0.63%   |
| Excavator     | 4        | 0.42%   |
| Bulldozer     | 4        | 0.42%   |
| Steamroller   | 3        | 0.31%   |
| P6            | 3        | 0.31%   |
| Geode         | 2        | 0.21%   |
| TigerLake     | 1        | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 317      | 34.16%  |
| Nvidia                                       | 302      | 32.54%  |
| AMD                                          | 240      | 25.86%  |
| Matrox Electronics Systems                   | 32       | 3.45%   |
| ASPEED Technology                            | 29       | 3.13%   |
| XGI Technology (eXtreme Graphics Innovation) | 2        | 0.22%   |
| VIA Technologies                             | 2        | 0.22%   |
| S3 Graphics                                  | 2        | 0.22%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.11%   |
| NVidia / SGS Thomson (Joint Venture)         | 1        | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 41       | 4.32%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 35       | 3.69%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 32       | 3.37%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 29       | 3.06%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 25       | 2.63%   |
| Intel HD Graphics 530                                                                    | 23       | 2.42%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 22       | 2.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22       | 2.32%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 20       | 2.11%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 17       | 1.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16       | 1.69%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 15       | 1.58%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 14       | 1.48%   |
| Matrox Electronics Systems MGA G200EH                                                    | 13       | 1.37%   |
| Intel HD Graphics 630                                                                    | 13       | 1.37%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 12       | 1.26%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12       | 1.26%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 11       | 1.16%   |
| Nvidia GT218 [GeForce 210]                                                               | 10       | 1.05%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 10       | 1.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9        | 0.95%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 8        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8        | 0.84%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 8        | 0.84%   |
| AMD RV730 XT [Radeon HD 4670]                                                            | 8        | 0.84%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 8        | 0.84%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 7        | 0.74%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 7        | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 7        | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 7        | 0.74%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 7        | 0.74%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 7        | 0.74%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 7        | 0.74%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 7        | 0.74%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 7        | 0.74%   |
| AMD Renoir                                                                               | 7        | 0.74%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 7        | 0.74%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 6        | 0.63%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 6        | 0.63%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 6        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| 1 x Intel                                | 274      | 28.78%  |
| 1 x Nvidia                               | 273      | 28.68%  |
| 1 x AMD                                  | 216      | 22.69%  |
| Other                                    | 63       | 6.62%   |
| 1 x Matrox                               | 32       | 3.36%   |
| 1 x ASPEED                               | 26       | 2.73%   |
| Intel + Nvidia                           | 21       | 2.21%   |
| 2 x Intel                                | 11       | 1.16%   |
| 2 x AMD                                  | 10       | 1.05%   |
| Intel + AMD                              | 9        | 0.95%   |
| 2 x Nvidia                               | 3        | 0.32%   |
| 1 x XGI                                  | 2        | 0.21%   |
| 1 x VIA                                  | 2        | 0.21%   |
| 1 x S3 Graphics                          | 2        | 0.21%   |
| Nvidia + ASPEED                          | 2        | 0.21%   |
| AMD + Nvidia                             | 2        | 0.21%   |
| 1 x SiS                                  | 1        | 0.11%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1        | 0.11%   |
| Intel + ASPEED                           | 1        | 0.11%   |
| AMD + ASPEED                             | 1        | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 651      | 68.38%  |
| Proprietary | 232      | 24.37%  |
| Unknown     | 69       | 7.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 615      | 63.73%  |
| 1.01-2.0   | 98       | 10.16%  |
| 0.51-1.0   | 60       | 6.22%   |
| 3.01-4.0   | 57       | 5.91%   |
| 7.01-8.0   | 52       | 5.39%   |
| 0.01-0.5   | 31       | 3.21%   |
| 5.01-6.0   | 29       | 3.01%   |
| 8.01-16.0  | 12       | 1.24%   |
| 2.01-3.0   | 10       | 1.04%   |
| 4.01-5.0   | 1        | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 86       | 17.3%   |
| Dell                 | 82       | 16.5%   |
| Goldstar             | 48       | 9.66%   |
| Acer                 | 32       | 6.44%   |
| Hewlett-Packard      | 28       | 5.63%   |
| AOC                  | 26       | 5.23%   |
| Philips              | 21       | 4.23%   |
| BenQ                 | 21       | 4.23%   |
| Ancor Communications | 20       | 4.02%   |
| LG Electronics       | 19       | 3.82%   |
| Sony                 | 12       | 2.41%   |
| Iiyama               | 12       | 2.41%   |
| ViewSonic            | 10       | 2.01%   |
| Lenovo               | 9        | 1.81%   |
| NEC Computers        | 8        | 1.61%   |
| Idek Iiyama          | 7        | 1.41%   |
| unknown              | 6        | 1.21%   |
| Eizo                 | 6        | 1.21%   |
| ASUSTek Computer     | 5        | 1.01%   |
| Sceptre Tech         | 3        | 0.6%    |
| Toshiba              | 2        | 0.4%    |
| RTK                  | 2        | 0.4%    |
| Panasonic            | 2        | 0.4%    |
| Mi                   | 2        | 0.4%    |
| IOD                  | 2        | 0.4%    |
| HPN                  | 2        | 0.4%    |
| Fujitsu Siemens      | 2        | 0.4%    |
| Apple                | 2        | 0.4%    |
| VIE                  | 1        | 0.2%    |
| Vestel Elektronik    | 1        | 0.2%    |
| SGT                  | 1        | 0.2%    |
| SAC                  | 1        | 0.2%    |
| Pioneer Electronic   | 1        | 0.2%    |
| Orion                | 1        | 0.2%    |
| Medion               | 1        | 0.2%    |
| Lenovo Group Limited | 1        | 0.2%    |
| Insignia             | 1        | 0.2%    |
| IBM                  | 1        | 0.2%    |
| Hitachi              | 1        | 0.2%    |
| Gateway              | 1        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 5        | 0.93%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 4        | 0.74%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch    | 3        | 0.56%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 3        | 0.56%   |
| LG Electronics LCD Monitor LG Ultra HD                               | 3        | 0.56%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 3        | 0.56%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                    | 3        | 0.56%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                    | 3        | 0.56%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                    | 3        | 0.56%   |
| ViewSonic LCD Monitor VSCFA2B 1920x1080 510x290mm 23.1-inch          | 2        | 0.37%   |
| unknown LCD Monitor SAMSUNG 1920x1080                                | 2        | 0.37%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                        | 2        | 0.37%   |
| Sony LCD Monitor TV XV 1920x1080                                     | 2        | 0.37%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 2        | 0.37%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch | 2        | 0.37%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 300x230mm 14.9-inch  | 2        | 0.37%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch  | 2        | 0.37%   |
| Samsung Electronics S27C750 SAM0A60 1920x1080 600x340mm 27.2-inch    | 2        | 0.37%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch    | 2        | 0.37%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                 | 2        | 0.37%   |
| Samsung Electronics LCD Monitor SAM04FB 1920x1080                    | 2        | 0.37%   |
| Samsung Electronics C32JG5x SAM0FDE 2560x1440 700x390mm 31.5-inch    | 2        | 0.37%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 2        | 0.37%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                | 2        | 0.37%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 2        | 0.37%   |
| NEC Computers FE791SB NEC61D7 1600x1200 330x240mm 16.1-inch          | 2        | 0.37%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                | 2        | 0.37%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch             | 2        | 0.37%   |
| Lenovo LCD Monitor LEN0990 1440x900 410x260mm 19.1-inch              | 2        | 0.37%   |
| Idek Iiyama LCD Monitor PLX2783H 1920x1080                           | 2        | 0.37%   |
| Hewlett-Packard ZR24w HWP286A 1920x1200 540x350mm 25.3-inch          | 2        | 0.37%   |
| Goldstar W2246 GSM5784 1920x1080 480x270mm 21.7-inch                 | 2        | 0.37%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                 | 2        | 0.37%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 2        | 0.37%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch           | 2        | 0.37%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch               | 2        | 0.37%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                | 2        | 0.37%   |
| Dell U2719DC DEL417C 2560x1440 600x340mm 27.2-inch                   | 2        | 0.37%   |
| Dell U2415 DELA0BA 1920x1200 520x320mm 24.0-inch                     | 2        | 0.37%   |
| Dell LCD Monitor U2412M 3840x1200                                    | 2        | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 214      | 43.23%  |
| 3840x2160 (4K)     | 47       | 9.49%   |
| 2560x1440 (QHD)    | 41       | 8.28%   |
| 1920x1200 (WUXGA)  | 40       | 8.08%   |
| 1280x1024 (SXGA)   | 35       | 7.07%   |
| 1680x1050 (WSXGA+) | 18       | 3.64%   |
| Unknown            | 18       | 3.64%   |
| 1600x900 (HD+)     | 13       | 2.63%   |
| 1366x768 (WXGA)    | 10       | 2.02%   |
| 3440x1440          | 9        | 1.82%   |
| 1440x900 (WXGA+)   | 8        | 1.62%   |
| 2560x1080          | 7        | 1.41%   |
| 3840x1080          | 5        | 1.01%   |
| 1600x1200          | 4        | 0.81%   |
| 1024x768 (XGA)     | 4        | 0.81%   |
| 3840x1200          | 2        | 0.4%    |
| 2560x1600          | 2        | 0.4%    |
| 1920x540           | 2        | 0.4%    |
| 7680x2160          | 1        | 0.2%    |
| 5760x1256          | 1        | 0.2%    |
| 5760x1200          | 1        | 0.2%    |
| 5760x1080          | 1        | 0.2%    |
| 3840x1600          | 1        | 0.2%    |
| 3640x1920          | 1        | 0.2%    |
| 3600x1080          | 1        | 0.2%    |
| 3520x1200          | 1        | 0.2%    |
| 3360x1050          | 1        | 0.2%    |
| 2648x1024          | 1        | 0.2%    |
| 2560x2520          | 1        | 0.2%    |
| 2048x1152          | 1        | 0.2%    |
| 1360x768           | 1        | 0.2%    |
| 1280x720 (HD)      | 1        | 0.2%    |
| 11520x2160         | 1        | 0.2%    |
| 1024x600           | 1        | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 102      | 20.61%  |
| 24      | 74       | 14.95%  |
| 27      | 65       | 13.13%  |
| 21      | 55       | 11.11%  |
| 23      | 46       | 9.29%   |
| 19      | 29       | 5.86%   |
| 31      | 21       | 4.24%   |
| 17      | 17       | 3.43%   |
| 22      | 15       | 3.03%   |
| 18      | 10       | 2.02%   |
| 34      | 7        | 1.41%   |
| 15      | 6        | 1.21%   |
| 20      | 5        | 1.01%   |
| 29      | 4        | 0.81%   |
| 40      | 3        | 0.61%   |
| 25      | 3        | 0.61%   |
| 14      | 3        | 0.61%   |
| 54      | 2        | 0.4%    |
| 52      | 2        | 0.4%    |
| 46      | 2        | 0.4%    |
| 42      | 2        | 0.4%    |
| 41      | 2        | 0.4%    |
| 32      | 2        | 0.4%    |
| 26      | 2        | 0.4%    |
| 16      | 2        | 0.4%    |
| 13      | 2        | 0.4%    |
| 74      | 1        | 0.2%    |
| 64      | 1        | 0.2%    |
| 57      | 1        | 0.2%    |
| 55      | 1        | 0.2%    |
| 49      | 1        | 0.2%    |
| 48      | 1        | 0.2%    |
| 47      | 1        | 0.2%    |
| 43      | 1        | 0.2%    |
| 39      | 1        | 0.2%    |
| 37      | 1        | 0.2%    |
| 28      | 1        | 0.2%    |
| 9       | 1        | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 176      | 36.51%  |
| Unknown     | 102      | 21.16%  |
| 401-500     | 97       | 20.12%  |
| 601-700     | 32       | 6.64%   |
| 301-350     | 26       | 5.39%   |
| 351-400     | 12       | 2.49%   |
| 1001-1500   | 12       | 2.49%   |
| 701-800     | 9        | 1.87%   |
| 901-1000    | 6        | 1.24%   |
| 801-900     | 4        | 0.83%   |
| 201-300     | 4        | 0.83%   |
| 1501-2000   | 1        | 0.21%   |
| 101-200     | 1        | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 269      | 57.48%  |
| Unknown | 94       | 20.09%  |
| 16/10   | 47       | 10.04%  |
| 5/4     | 27       | 5.77%   |
| 21/9    | 12       | 2.56%   |
| 4/3     | 9        | 1.92%   |
| 3/2     | 6        | 1.28%   |
| 6/5     | 2        | 0.43%   |
| 32/9    | 2        | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 150      | 30.86%  |
| Unknown        | 102      | 20.99%  |
| 301-350        | 68       | 13.99%  |
| 151-200        | 37       | 7.61%   |
| 251-300        | 35       | 7.2%    |
| 351-500        | 32       | 6.58%   |
| 141-150        | 25       | 5.14%   |
| 501-1000       | 14       | 2.88%   |
| More than 1000 | 9        | 1.85%   |
| 101-110        | 5        | 1.03%   |
| 121-130        | 3        | 0.62%   |
| 111-120        | 3        | 0.62%   |
| 81-90          | 2        | 0.41%   |
| 1-40           | 1        | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 242      | 50.95%  |
| Unknown | 102      | 21.47%  |
| 101-120 | 83       | 17.47%  |
| 121-160 | 26       | 5.47%   |
| 161-240 | 15       | 3.16%   |
| 1-50    | 7        | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 487      | 50.57%  |
| 1     | 404      | 41.95%  |
| 2     | 64       | 6.65%   |
| 3     | 8        | 0.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 494      | 40.89%  |
| Realtek Semiconductor             | 437      | 36.18%  |
| Qualcomm Atheros                  | 70       | 5.79%   |
| Broadcom                          | 65       | 5.38%   |
| Marvell Technology Group          | 12       | 0.99%   |
| Ralink Technology                 | 11       | 0.91%   |
| Mellanox Technologies             | 11       | 0.91%   |
| Ralink                            | 10       | 0.83%   |
| VIA Technologies                  | 9        | 0.75%   |
| TP-Link                           | 9        | 0.75%   |
| D-Link System                     | 6        | 0.5%    |
| Aquantia                          | 5        | 0.41%   |
| American Megatrends               | 5        | 0.41%   |
| Xiaomi                            | 4        | 0.33%   |
| Chelsio Communications            | 4        | 0.33%   |
| 3Com                              | 4        | 0.33%   |
| MediaTek                          | 3        | 0.25%   |
| IMC Networks                      | 3        | 0.25%   |
| Dresden Elektronik                | 3        | 0.25%   |
| Arduino SA                        | 3        | 0.25%   |
| Apple                             | 3        | 0.25%   |
| Qualcomm Atheros Communications   | 2        | 0.17%   |
| Qualcomm                          | 2        | 0.17%   |
| Nvidia                            | 2        | 0.17%   |
| Huawei Technologies               | 2        | 0.17%   |
| ADMtek                            | 2        | 0.17%   |
| Accton Technology                 | 2        | 0.17%   |
| U.S. Robotics                     | 1        | 0.08%   |
| Tehuti Networks                   | 1        | 0.08%   |
| Sundance Technology Inc / IC Plus | 1        | 0.08%   |
| Solarflare Communications         | 1        | 0.08%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.08%   |
| Samsung Electronics               | 1        | 0.08%   |
| Pulse-Eight                       | 1        | 0.08%   |
| OnePlus Technology (Shenzhen)     | 1        | 0.08%   |
| Microchip Technology              | 1        | 0.08%   |
| Linksys                           | 1        | 0.08%   |
| LG Electronics                    | 1        | 0.08%   |
| Hewlett-Packard                   | 1        | 0.08%   |
| Free Software Initiative of Japan | 1        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 361      | 25.62%  |
| Intel I211 Gigabit Network Connection                                         | 86       | 6.1%    |
| Intel 82574L Gigabit Network Connection                                       | 51       | 3.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 43       | 3.05%   |
| Intel Wi-Fi 6 AX200                                                           | 38       | 2.7%    |
| Intel I210 Gigabit Network Connection                                         | 37       | 2.63%   |
| Realtek RTL8125 2.5GbE Controller                                             | 36       | 2.56%   |
| Intel 82579V Gigabit Network Connection                                       | 26       | 1.85%   |
| Intel Ethernet Connection (2) I219-LM                                         | 23       | 1.63%   |
| Intel Ethernet Controller I225-V                                              | 22       | 1.56%   |
| Intel Ethernet Connection I217-LM                                             | 20       | 1.42%   |
| Intel Ethernet Connection (2) I219-V                                          | 20       | 1.42%   |
| Intel I350 Gigabit Network Connection                                         | 16       | 1.14%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 16       | 1.14%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 15       | 1.06%   |
| Intel Ethernet Connection (2) I218-V                                          | 12       | 0.85%   |
| Intel Ethernet Connection (7) I219-V                                          | 11       | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 11       | 0.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10       | 0.71%   |
| Intel Wireless-AC 9260                                                        | 10       | 0.71%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 10       | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 9        | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 9        | 0.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 9        | 0.64%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 9        | 0.64%   |
| Intel Ethernet Connection I217-V                                              | 9        | 0.64%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 9        | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 8        | 0.57%   |
| Intel Wireless 7265                                                           | 8        | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                                         | 8        | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 8        | 0.57%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 8        | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 7        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 7        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 7        | 0.5%    |
| Intel Ethernet Controller X550                                                | 7        | 0.5%    |
| Intel 82580 Gigabit Network Connection                                        | 7        | 0.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 6        | 0.43%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6        | 0.43%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 6        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 100      | 40.49%  |
| Realtek Semiconductor                 | 45       | 18.22%  |
| Qualcomm Atheros                      | 45       | 18.22%  |
| Broadcom                              | 12       | 4.86%   |
| Ralink Technology                     | 11       | 4.45%   |
| Ralink                                | 10       | 4.05%   |
| TP-Link                               | 9        | 3.64%   |
| MediaTek                              | 3        | 1.21%   |
| IMC Networks                          | 3        | 1.21%   |
| Qualcomm Atheros Communications       | 2        | 0.81%   |
| Linksys                               | 1        | 0.4%    |
| Edimax Technology                     | 1        | 0.4%    |
| D-Link                                | 1        | 0.4%    |
| Atheros                               | 1        | 0.4%    |
| ASUSTek Computer                      | 1        | 0.4%    |
| AboCom Systems                        | 1        | 0.4%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 38       | 15.14%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 11       | 4.38%   |
| Intel Wireless-AC 9260                                                                        | 10       | 3.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 9        | 3.59%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 9        | 3.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 8        | 3.19%   |
| Intel Wireless 7265                                                                           | 8        | 3.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 6        | 2.39%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 6        | 2.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 5        | 1.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 5        | 1.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 4        | 1.59%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 4        | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4        | 1.59%   |
| Intel Wireless 8260                                                                           | 4        | 1.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 4        | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 4        | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4        | 1.59%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 4        | 1.59%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 3        | 1.2%    |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                                  | 3        | 1.2%    |
| Ralink RT5572 Wireless Adapter                                                                | 3        | 1.2%    |
| Ralink RT5370 Wireless Adapter                                                                | 3        | 1.2%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 3        | 1.2%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 3        | 1.2%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 3        | 1.2%    |
| Intel Wireless 7260                                                                           | 3        | 1.2%    |
| Intel Wireless 3160                                                                           | 3        | 1.2%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 2        | 0.8%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 2        | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2        | 0.8%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.8%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 2        | 0.8%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 0.8%    |
| Realtek Bluetooth Adapter                                                                     | 2        | 0.8%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 0.8%    |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                          | 2        | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2        | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 465      | 45.01%  |
| Realtek Semiconductor             | 419      | 40.56%  |
| Broadcom                          | 53       | 5.13%   |
| Qualcomm Atheros                  | 28       | 2.71%   |
| Marvell Technology Group          | 12       | 1.16%   |
| VIA Technologies                  | 9        | 0.87%   |
| D-Link System                     | 6        | 0.58%   |
| Aquantia                          | 5        | 0.48%   |
| American Megatrends               | 5        | 0.48%   |
| Xiaomi                            | 4        | 0.39%   |
| Chelsio Communications            | 4        | 0.39%   |
| 3Com                              | 4        | 0.39%   |
| Qualcomm                          | 2        | 0.19%   |
| Nvidia                            | 2        | 0.19%   |
| Apple                             | 2        | 0.19%   |
| ADMtek                            | 2        | 0.19%   |
| U.S. Robotics                     | 1        | 0.1%    |
| Tehuti Networks                   | 1        | 0.1%    |
| Sundance Technology Inc / IC Plus | 1        | 0.1%    |
| Solarflare Communications         | 1        | 0.1%    |
| Silicon Integrated Systems [SiS]  | 1        | 0.1%    |
| Samsung Electronics               | 1        | 0.1%    |
| OnePlus Technology (Shenzhen)     | 1        | 0.1%    |
| Huawei Technologies               | 1        | 0.1%    |
| Emulex                            | 1        | 0.1%    |
| Davicom Semiconductor             | 1        | 0.1%    |
| Accton Technology                 | 1        | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 361      | 32.15%  |
| Intel I211 Gigabit Network Connection                                         | 86       | 7.66%   |
| Intel 82574L Gigabit Network Connection                                       | 51       | 4.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 43       | 3.83%   |
| Intel I210 Gigabit Network Connection                                         | 37       | 3.29%   |
| Realtek RTL8125 2.5GbE Controller                                             | 33       | 2.94%   |
| Intel 82579V Gigabit Network Connection                                       | 26       | 2.32%   |
| Intel Ethernet Connection (2) I219-LM                                         | 23       | 2.05%   |
| Intel Ethernet Controller I225-V                                              | 22       | 1.96%   |
| Intel Ethernet Connection I217-LM                                             | 20       | 1.78%   |
| Intel Ethernet Connection (2) I219-V                                          | 20       | 1.78%   |
| Intel I350 Gigabit Network Connection                                         | 16       | 1.42%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 16       | 1.42%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 15       | 1.34%   |
| Intel Ethernet Connection (2) I218-V                                          | 12       | 1.07%   |
| Intel Ethernet Connection (7) I219-V                                          | 11       | 0.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10       | 0.89%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 10       | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 9        | 0.8%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 9        | 0.8%    |
| Intel Ethernet Connection I217-V                                              | 9        | 0.8%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 9        | 0.8%    |
| Intel Ethernet Connection (7) I219-LM                                         | 8        | 0.71%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 8        | 0.71%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 8        | 0.71%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 7        | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 7        | 0.62%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 7        | 0.62%   |
| Intel Ethernet Controller X550                                                | 7        | 0.62%   |
| Intel 82580 Gigabit Network Connection                                        | 7        | 0.62%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6        | 0.53%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 5        | 0.45%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 5        | 0.45%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 5        | 0.45%   |
| Intel Ethernet Connection (2) I218-LM                                         | 5        | 0.45%   |
| Intel Ethernet Connection (11) I219-V                                         | 5        | 0.45%   |
| Intel 82576 Gigabit Network Connection                                        | 5        | 0.45%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 5        | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 5        | 0.45%   |
| American Megatrends Virtual Ethernet                                          | 5        | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 910      | 77.38%  |
| WiFi     | 231      | 19.64%  |
| Unknown  | 23       | 1.96%   |
| Modem    | 12       | 1.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 869      | 89.77%  |
| WiFi     | 94       | 9.71%   |
| Unknown  | 5        | 0.52%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 474      | 49.43%  |
| 2     | 296      | 30.87%  |
| 3     | 84       | 8.76%   |
| 4     | 37       | 3.86%   |
| 0     | 32       | 3.34%   |
| 5     | 15       | 1.56%   |
| 6     | 12       | 1.25%   |
| 7     | 5        | 0.52%   |
| 10    | 2        | 0.21%   |
| 8     | 2        | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 847      | 87.14%  |
| Yes  | 125      | 12.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 89       | 54.27%  |
| Cambridge Silicon Radio         | 26       | 15.85%  |
| ASUSTek Computer                | 12       | 7.32%   |
| Realtek Semiconductor           | 10       | 6.1%    |
| Qualcomm Atheros Communications | 6        | 3.66%   |
| Broadcom                        | 5        | 3.05%   |
| Apple                           | 5        | 3.05%   |
| IMC Networks                    | 4        | 2.44%   |
| MediaTek                        | 3        | 1.83%   |
| Lite-On Technology              | 3        | 1.83%   |
| Micro Star International        | 1        | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                       | 34       | 20.36%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 26       | 15.57%  |
| Intel Bluetooth wireless interface                          | 16       | 9.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 11       | 6.59%   |
| Intel Wireless-AC 3168 Bluetooth                            | 10       | 5.99%   |
| Intel AX201 Bluetooth                                       | 8        | 4.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 7        | 4.19%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 5        | 2.99%   |
| Realtek  Bluetooth 4.2 Adapter                              | 4        | 2.4%    |
| Realtek Bluetooth Adapter                                   | 4        | 2.4%    |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 4        | 2.4%    |
| MediaTek RZ608 Bluetooth Adapter                            | 3        | 1.8%    |
| Intel AX210 Bluetooth                                       | 3        | 1.8%    |
| Apple Bluetooth Host Controller                             | 3        | 1.8%    |
| Realtek Bluetooth 4.2 Adapter                               | 2        | 1.2%    |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 2        | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 2        | 1.2%    |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 2        | 1.2%    |
| ASUS Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter     | 2        | 1.2%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE       | 2        | 1.2%    |
| ASUS Bluetooth USB module                                   | 2        | 1.2%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2        | 1.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 1        | 0.6%    |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 0.6%    |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1        | 0.6%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 1        | 0.6%    |
| Micro Star International MS-6970 BToes Bluetooth adapter    | 1        | 0.6%    |
| Lite-On Bluetooth USB Module                                | 1        | 0.6%    |
| Lite-On Atheros AR9462 Bluetooth 4.0 + HS                   | 1        | 0.6%    |
| Lite-On Atheros AR3012 Bluetooth                            | 1        | 0.6%    |
| Intel Wireless Bluetooth                                    | 1        | 0.6%    |
| IMC Networks Realtek Bluetooth Adapter                      | 1        | 0.6%    |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 1        | 0.6%    |
| ASUS USB-BT500                                              | 1        | 0.6%    |
| ASUS Qualcomm Bluetooth 4.1                                 | 1        | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 438      | 37.76%  |
| AMD                                             | 313      | 26.98%  |
| Nvidia                                          | 271      | 23.36%  |
| C-Media Electronics                             | 19       | 1.64%   |
| Creative Labs                                   | 16       | 1.38%   |
| Logitech                                        | 14       | 1.21%   |
| Texas Instruments                               | 6        | 0.52%   |
| Realtek Semiconductor                           | 6        | 0.52%   |
| Kingston Technology                             | 4        | 0.34%   |
| JMTek                                           | 4        | 0.34%   |
| Focusrite-Novation                              | 4        | 0.34%   |
| Blue Microphones                                | 4        | 0.34%   |
| BEHRINGER International                         | 4        | 0.34%   |
| Tenx Technology                                 | 3        | 0.26%   |
| SteelSeries ApS                                 | 3        | 0.26%   |
| Sony                                            | 3        | 0.26%   |
| Silicon Integrated Systems [SiS]                | 3        | 0.26%   |
| ASUSTek Computer                                | 3        | 0.26%   |
| Yamaha                                          | 2        | 0.17%   |
| VIA Technologies                                | 2        | 0.17%   |
| Trust                                           | 2        | 0.17%   |
| Thesycon Systemsoftware & Consulting            | 2        | 0.17%   |
| Micro Star International                        | 2        | 0.17%   |
| M-Audio                                         | 2        | 0.17%   |
| Generalplus Technology                          | 2        | 0.17%   |
| Creative Technology                             | 2        | 0.17%   |
| Corsair                                         | 2        | 0.17%   |
| Cambridge Silicon Radio                         | 2        | 0.17%   |
| Zoran Co. Personal Media Division (Nogatech)    | 1        | 0.09%   |
| XMOS                                            | 1        | 0.09%   |
| Xilinx                                          | 1        | 0.09%   |
| Samsung Electronics                             | 1        | 0.09%   |
| ROCCAT                                          | 1        | 0.09%   |
| Razer USA                                       | 1        | 0.09%   |
| Plantronics                                     | 1        | 0.09%   |
| Microsoft                                       | 1        | 0.09%   |
| Micronas                                        | 1        | 0.09%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.09%   |
| iCreate Technologies                            | 1        | 0.09%   |
| Huawei Technologies                             | 1        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 80       | 5.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 51       | 3.76%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 48       | 3.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 47       | 3.46%   |
| AMD Family 17h/19h HD Audio Controller                                     | 47       | 3.46%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 43       | 3.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 41       | 3.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 41       | 3.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 40       | 2.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 37       | 2.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 35       | 2.58%   |
| Intel 200 Series PCH HD Audio                                              | 27       | 1.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 25       | 1.84%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 25       | 1.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 24       | 1.77%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 23       | 1.69%   |
| Nvidia GP108 High Definition Audio Controller                              | 22       | 1.62%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 21       | 1.55%   |
| Nvidia TU116 High Definition Audio Controller                              | 20       | 1.47%   |
| AMD FCH Azalia Controller                                                  | 19       | 1.4%    |
| Nvidia High Definition Audio Controller                                    | 18       | 1.33%   |
| Nvidia GP107GL High Definition Audio Controller                            | 18       | 1.33%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 18       | 1.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 18       | 1.33%   |
| Nvidia GP106 High Definition Audio Controller                              | 15       | 1.1%    |
| Nvidia GF119 HDMI Audio Controller                                         | 15       | 1.1%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 14       | 1.03%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 14       | 1.03%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 14       | 1.03%   |
| AMD Kabini HDMI/DP Audio                                                   | 14       | 1.03%   |
| Nvidia GP104 High Definition Audio Controller                              | 13       | 0.96%   |
| Intel Comet Lake PCH cAVS                                                  | 13       | 0.96%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 13       | 0.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12       | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 11       | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                         | 11       | 0.81%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11       | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                              | 10       | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 10       | 0.74%   |
| Nvidia TU104 HD Audio Controller                                           | 9        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Kingston                                | 166      | 16.73%  |
| Unknown                                 | 162      | 16.33%  |
| Corsair                                 | 114      | 11.49%  |
| Samsung Electronics                     | 100      | 10.08%  |
| SK hynix                                | 94       | 9.48%   |
| Crucial                                 | 78       | 7.86%   |
| G.Skill                                 | 64       | 6.45%   |
| Micron Technology                       | 63       | 6.35%   |
| A-DATA Technology                       | 21       | 2.12%   |
| Unknown                                 | 11       | 1.11%   |
| Patriot                                 | 10       | 1.01%   |
| Ramaxel Technology                      | 9        | 0.91%   |
| Hewlett-Packard                         | 9        | 0.91%   |
| Goodram                                 | 9        | 0.91%   |
| Team                                    | 8        | 0.81%   |
| Nanya Technology                        | 8        | 0.81%   |
| Transcend                               | 7        | 0.71%   |
| Patriot Memory (PDP Systems)            | 4        | 0.4%    |
| Unknown (ABCD)                          | 3        | 0.3%    |
| Super Talent                            | 3        | 0.3%    |
| Qimonda                                 | 3        | 0.3%    |
| Avant                                   | 3        | 0.3%    |
| AMD                                     | 3        | 0.3%    |
| Tigo                                    | 2        | 0.2%    |
| Silicon Power                           | 2        | 0.2%    |
| PNY                                     | 2        | 0.2%    |
| Kingmax                                 | 2        | 0.2%    |
| HPE                                     | 2        | 0.2%    |
| Goldkey                                 | 2        | 0.2%    |
| Golden Empire                           | 2        | 0.2%    |
| Elpida                                  | 2        | 0.2%    |
| V-GeN                                   | 1        | 0.1%    |
| V-Color                                 | 1        | 0.1%    |
| Unknown (AB)                            | 1        | 0.1%    |
| Unknown (8A5D)                          | 1        | 0.1%    |
| Unknown (0x05F7)                        | 1        | 0.1%    |
| TIMETEC                                 | 1        | 0.1%    |
| Smart                                   | 1        | 0.1%    |
| SK_Hynix                                | 1        | 0.1%    |
| Silicon Power Computer & Communications | 1        | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 13       | 1.19%   |
| Unknown                                                | 11       | 1.01%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 9        | 0.82%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s  | 9        | 0.82%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s  | 8        | 0.73%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 6        | 0.55%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                   | 6        | 0.55%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s           | 6        | 0.55%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3200MT/s   | 6        | 0.55%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s    | 6        | 0.55%   |
| Unknown RAM Module 512MB DIMM SDRAM                    | 5        | 0.46%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 5        | 0.46%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 5        | 0.46%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 5        | 0.46%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 5        | 0.46%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s   | 5        | 0.46%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s  | 5        | 0.46%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 4        | 0.37%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 4        | 0.37%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 4        | 0.37%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 4        | 0.37%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 4        | 0.37%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s   | 4        | 0.37%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 2666MT/s   | 4        | 0.37%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s | 4        | 0.37%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s    | 4        | 0.37%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 4        | 0.37%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM 1333MT/s       | 4        | 0.37%   |
| Kingston RAM 99U5458-005.A01LF 4GB DIMM DDR3 1333MT/s  | 4        | 0.37%   |
| Kingston RAM 9965745-002.A00G 16GB DIMM DDR4 3000MT/s  | 4        | 0.37%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s    | 4        | 0.37%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s | 4        | 0.37%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s | 4        | 0.37%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s  | 4        | 0.37%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                | 3        | 0.27%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                | 3        | 0.27%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s            | 3        | 0.27%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 3        | 0.27%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s               | 3        | 0.27%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 3        | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 379      | 42.97%  |
| DDR3         | 345      | 39.12%  |
| Unknown      | 54       | 6.12%   |
| DDR2         | 51       | 5.78%   |
| SDRAM        | 27       | 3.06%   |
| DDR          | 16       | 1.81%   |
| LPDDR4       | 3        | 0.34%   |
| DDR5         | 3        | 0.34%   |
| DRAM         | 2        | 0.23%   |
| LPDDR3       | 1        | 0.11%   |
| DDR2 FB-DIMM | 1        | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 791      | 90.4%   |
| SODIMM       | 76       | 8.69%   |
| RIMM         | 6        | 0.69%   |
| Row Of Chips | 1        | 0.11%   |
| FB-DIMM      | 1        | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 325      | 33.78%  |
| 4096  | 230      | 23.91%  |
| 16384 | 183      | 19.02%  |
| 2048  | 120      | 12.47%  |
| 32768 | 47       | 4.89%   |
| 1024  | 38       | 3.95%   |
| 512   | 13       | 1.35%   |
| 128   | 2        | 0.21%   |
| 256   | 1        | 0.1%    |
| 64    | 1        | 0.1%    |
| 32    | 1        | 0.1%    |
| 8     | 1        | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 192      | 20.53%  |
| 1333    | 153      | 16.36%  |
| 3200    | 106      | 11.34%  |
| 2400    | 82       | 8.77%   |
| 2133    | 80       | 8.56%   |
| 800     | 56       | 5.99%   |
| 2667    | 50       | 5.35%   |
| 2666    | 29       | 3.1%    |
| 667     | 28       | 2.99%   |
| Unknown | 25       | 2.67%   |
| 3000    | 20       | 2.14%   |
| 3600    | 17       | 1.82%   |
| 1066    | 13       | 1.39%   |
| 533     | 10       | 1.07%   |
| 2933    | 9        | 0.96%   |
| 1866    | 9        | 0.96%   |
| 400     | 8        | 0.86%   |
| 1867    | 6        | 0.64%   |
| 1067    | 6        | 0.64%   |
| 3400    | 4        | 0.43%   |
| 2134    | 4        | 0.43%   |
| 4000    | 3        | 0.32%   |
| 1334    | 3        | 0.32%   |
| 5200    | 2        | 0.21%   |
| 3534    | 2        | 0.21%   |
| 2048    | 2        | 0.21%   |
| 1332    | 2        | 0.21%   |
| 333     | 2        | 0.21%   |
| 65535   | 1        | 0.11%   |
| 6400    | 1        | 0.11%   |
| 4800    | 1        | 0.11%   |
| 4133    | 1        | 0.11%   |
| 3500    | 1        | 0.11%   |
| 3066    | 1        | 0.11%   |
| 2800    | 1        | 0.11%   |
| 1800    | 1        | 0.11%   |
| 1639    | 1        | 0.11%   |
| 1400    | 1        | 0.11%   |
| 933     | 1        | 0.11%   |
| 266     | 1        | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 4        | 36.36%  |
| Hewlett-Packard     | 2        | 18.18%  |
| Seiko Epson         | 1        | 9.09%   |
| QinHeng Electronics | 1        | 9.09%   |
| Prolific Technology | 1        | 9.09%   |
| Dymo-CoStar         | 1        | 9.09%   |
| Canon               | 1        | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------|----------|---------|
| Seiko Epson Printer                                                                        | 1        | 9.09%   |
| QinHeng CH340S                                                                             | 1        | 9.09%   |
| Prolific PL2305 Parallel Port                                                              | 1        | 9.09%   |
| HP LaserJet 1012                                                                           | 1        | 9.09%   |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer | 1        | 9.09%   |
| Dymo-CoStar LabelWriter 450                                                                | 1        | 9.09%   |
| Canon LBP2900                                                                              | 1        | 9.09%   |
| Brother MFC-7360N                                                                          | 1        | 9.09%   |
| Brother HL-L5200DW series                                                                  | 1        | 9.09%   |
| Brother HL-2030 Laser Printer                                                              | 1        | 9.09%   |
| Brother HL-1430 Laser Printer                                                              | 1        | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 3        | 60%     |
| Seiko Epson     | 1        | 20%     |
| Hewlett-Packard | 1        | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Desktops | Percent |
|-------------------------------------------------------------------------------------|----------|---------|
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1        | 20%     |
| HP ScanJet 5300c/5370c                                                              | 1        | 20%     |
| Canon CanoScan LIDE 25                                                              | 1        | 20%     |
| Canon CanoScan LiDE 220                                                             | 1        | 20%     |
| Canon CanoScan LiDE 110                                                             | 1        | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Logitech                  | 30       | 52.63%  |
| Microdia                  | 9        | 15.79%  |
| WCM_USB                   | 2        | 3.51%   |
| SHENZHEN EMEET TECHNOLOGY | 2        | 3.51%   |
| ARC International         | 2        | 3.51%   |
| YGTek                     | 1        | 1.75%   |
| Valve Software            | 1        | 1.75%   |
| Trust                     | 1        | 1.75%   |
| Suyin                     | 1        | 1.75%   |
| Sonix Technology          | 1        | 1.75%   |
| Realtek Semiconductor     | 1        | 1.75%   |
| OmniVision Technologies   | 1        | 1.75%   |
| Lenovo                    | 1        | 1.75%   |
| Huawei Technologies       | 1        | 1.75%   |
| Cubeternet                | 1        | 1.75%   |
| Aveo Technology           | 1        | 1.75%   |
| Arkmicro Technologies     | 1        | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 10       | 17.54%  |
| Logitech HD Pro Webcam C920                    | 4        | 7.02%   |
| Logitech C920 PRO HD Webcam                    | 3        | 5.26%   |
| WCM_USB WEB CAM                                | 2        | 3.51%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 2        | 3.51%   |
| Microdia Webcam Vitade AF                      | 2        | 3.51%   |
| Microdia USB 2.0 Camera                        | 2        | 3.51%   |
| Microdia HP Integrated Webcam                  | 2        | 3.51%   |
| Logitech Webcam C310                           | 2        | 3.51%   |
| Logitech Labtec Webcam Pro                     | 2        | 3.51%   |
| Logitech C922 Pro Stream Webcam                | 2        | 3.51%   |
| Logitech C505 HD Webcam                        | 2        | 3.51%   |
| ARC International Camera                       | 2        | 3.51%   |
| YGTek Webcam                                   | 1        | 1.75%   |
| Valve Software 3D Camera                       | 1        | 1.75%   |
| Trust Canyon CNS-CWC6 Webcam                   | 1        | 1.75%   |
| Suyin Acer CrystalEye Webcam                   | 1        | 1.75%   |
| Sonix FHD Webcam                               | 1        | 1.75%   |
| Realtek USB Video Device                       | 1        | 1.75%   |
| OmniVision Monitor Webcam                      | 1        | 1.75%   |
| Microdia REDRAGON Live Camera Audio            | 1        | 1.75%   |
| Microdia JOYACCESS JA-Webcam                   | 1        | 1.75%   |
| Microdia Camera                                | 1        | 1.75%   |
| Logitech Webcam C930e                          | 1        | 1.75%   |
| Logitech Webcam C170                           | 1        | 1.75%   |
| Logitech HD Webcam C615                        | 1        | 1.75%   |
| Logitech HD Webcam C525                        | 1        | 1.75%   |
| Logitech BRIO Ultra HD Webcam                  | 1        | 1.75%   |
| Lenovo Integrated Camera                       | 1        | 1.75%   |
| Huawei HiCamera                                | 1        | 1.75%   |
| Cubeternet GL-UPC822 UVC WebCam                | 1        | 1.75%   |
| Aveo USB2.0 Camera                             | 1        | 1.75%   |
| Arkmicro USB 2.0 PC CAMERA                     | 1        | 1.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| FocalTech Systems | 1        | 50%     |
| DigitalPersona    | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| FocalTech Systems Fingerprint Reader | 1        | 50%     |
| DigitalPersona Fingerprint Reader    | 1        | 50%     |

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
| 0     | 405      | 41.5%   |
| 1     | 400      | 40.98%  |
| 2     | 135      | 13.83%  |
| 3     | 28       | 2.87%   |
| 4     | 6        | 0.61%   |
| 6     | 2        | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 423      | 59.92%  |
| Net/wireless             | 87       | 12.32%  |
| Bluetooth                | 61       | 8.64%   |
| Firewire controller      | 60       | 8.5%    |
| Sound                    | 22       | 3.12%   |
| Net/ethernet             | 19       | 2.69%   |
| Network                  | 15       | 2.12%   |
| Card reader              | 13       | 1.84%   |
| Dvb card                 | 3        | 0.42%   |
| Fingerprint reader       | 2        | 0.28%   |
| Storage/raid             | 1        | 0.14%   |

