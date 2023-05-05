FreeBSD - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for FreeBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/FreeBSD/Desktop/README.md) and [notebooks](/Dist/FreeBSD/Notebook/README.md).

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

Total: 3340

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | HX90                        | Desktop     | [b3300c45bc](https://bsd-hardware.info/?probe=b3300c45bc) | May 01, 2023 |
| AZW           | SER                         | Mini pc     | [d3d9ba6f52](https://bsd-hardware.info/?probe=d3d9ba6f52) | Apr 30, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [9d82570c34](https://bsd-hardware.info/?probe=9d82570c34) | Apr 30, 2023 |
| Dell          | 0FF3FN A00                  | Desktop     | [717b46840a](https://bsd-hardware.info/?probe=717b46840a) | Apr 30, 2023 |
| Dell          | 0H634K A00                  | Desktop     | [5e783a1c2e](https://bsd-hardware.info/?probe=5e783a1c2e) | Apr 30, 2023 |
| GVC           | DR 738                      | Desktop     | [21b338db1b](https://bsd-hardware.info/?probe=21b338db1b) | Apr 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [e28acf1164](https://bsd-hardware.info/?probe=e28acf1164) | Apr 30, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [33d1b6e2d2](https://bsd-hardware.info/?probe=33d1b6e2d2) | Apr 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b0d9eaaceb](https://bsd-hardware.info/?probe=b0d9eaaceb) | Apr 30, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [ce8453fcce](https://bsd-hardware.info/?probe=ce8453fcce) | Apr 27, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [fc81710889](https://bsd-hardware.info/?probe=fc81710889) | Apr 27, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [692df89c1f](https://bsd-hardware.info/?probe=692df89c1f) | Apr 26, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [d4881f1fb6](https://bsd-hardware.info/?probe=d4881f1fb6) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [d3373e972b](https://bsd-hardware.info/?probe=d3373e972b) | Apr 24, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [214b0c30e0](https://bsd-hardware.info/?probe=214b0c30e0) | Apr 23, 2023 |
| HP            | Unknown                     | Notebook    | [e2aa3620b4](https://bsd-hardware.info/?probe=e2aa3620b4) | Apr 23, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6df7a17ff2](https://bsd-hardware.info/?probe=6df7a17ff2) | Apr 23, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [37564b68c3](https://bsd-hardware.info/?probe=37564b68c3) | Apr 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d44a98739c](https://bsd-hardware.info/?probe=d44a98739c) | Apr 23, 2023 |
| Dell          | 0569RT A04                  | Server      | [cff2ebd06b](https://bsd-hardware.info/?probe=cff2ebd06b) | Apr 23, 2023 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [596ddff446](https://bsd-hardware.info/?probe=596ddff446) | Apr 22, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [60f61f7ecb](https://bsd-hardware.info/?probe=60f61f7ecb) | Apr 22, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [68b1300903](https://bsd-hardware.info/?probe=68b1300903) | Apr 22, 2023 |
| Lenovo        | ThinkPad W520 4270CTO       | Notebook    | [51f0a87f01](https://bsd-hardware.info/?probe=51f0a87f01) | Apr 21, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [e17bcecec8](https://bsd-hardware.info/?probe=e17bcecec8) | Apr 21, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [838979f891](https://bsd-hardware.info/?probe=838979f891) | Apr 20, 2023 |
| Dell          | Latitude 7280               | Notebook    | [254acb5df8](https://bsd-hardware.info/?probe=254acb5df8) | Apr 20, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [6e82f69c4c](https://bsd-hardware.info/?probe=6e82f69c4c) | Apr 20, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [541f3e7f7e](https://bsd-hardware.info/?probe=541f3e7f7e) | Apr 20, 2023 |
| Dell          | Precision 5510              | Notebook    | [7028fde527](https://bsd-hardware.info/?probe=7028fde527) | Apr 20, 2023 |
| HP            | 158B                        | Desktop     | [40fe372619](https://bsd-hardware.info/?probe=40fe372619) | Apr 20, 2023 |
| Lenovo        | ThinkPad X201 3626WNP       | Notebook    | [d642970071](https://bsd-hardware.info/?probe=d642970071) | Apr 19, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [3852dcb332](https://bsd-hardware.info/?probe=3852dcb332) | Apr 19, 2023 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [b341a9c9c9](https://bsd-hardware.info/?probe=b341a9c9c9) | Apr 19, 2023 |
| HP            | Unknown                     | Notebook    | [941c021569](https://bsd-hardware.info/?probe=941c021569) | Apr 18, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [464059d8b1](https://bsd-hardware.info/?probe=464059d8b1) | Apr 18, 2023 |
| Lenovo        | YangTianM6880N              | Desktop     | [a567c3062c](https://bsd-hardware.info/?probe=a567c3062c) | Apr 18, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [b8d2c0d81d](https://bsd-hardware.info/?probe=b8d2c0d81d) | Apr 16, 2023 |
| MSI           | H81M-P33                    | Desktop     | [e285cc821f](https://bsd-hardware.info/?probe=e285cc821f) | Apr 16, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b79bdd39da](https://bsd-hardware.info/?probe=b79bdd39da) | Apr 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e6734bf5e3](https://bsd-hardware.info/?probe=e6734bf5e3) | Apr 16, 2023 |
| Lenovo        | Larne CRB 31900002 WIN      | All in one  | [1f18ec4466](https://bsd-hardware.info/?probe=1f18ec4466) | Apr 16, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [cf533da9bf](https://bsd-hardware.info/?probe=cf533da9bf) | Apr 16, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [4dfa2f0148](https://bsd-hardware.info/?probe=4dfa2f0148) | Apr 15, 2023 |
| ASUSTek       | PRIME X299-A II             | Desktop     | [8c345e7a24](https://bsd-hardware.info/?probe=8c345e7a24) | Apr 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [926ab149ae](https://bsd-hardware.info/?probe=926ab149ae) | Apr 14, 2023 |
| HP            | ProLiant DL180 G6           | Server      | [4ccb132836](https://bsd-hardware.info/?probe=4ccb132836) | Apr 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [b189b0988c](https://bsd-hardware.info/?probe=b189b0988c) | Apr 14, 2023 |
| Lenovo        | ThinkPad R61 89208RU        | Notebook    | [e892cdffee](https://bsd-hardware.info/?probe=e892cdffee) | Apr 13, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [3d7bf4205b](https://bsd-hardware.info/?probe=3d7bf4205b) | Apr 13, 2023 |
| HMT           | W041-TF-A-45                | Notebook    | [298d106fd1](https://bsd-hardware.info/?probe=298d106fd1) | Apr 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [e2b6422180](https://bsd-hardware.info/?probe=e2b6422180) | Apr 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [f54d0b103e](https://bsd-hardware.info/?probe=f54d0b103e) | Apr 13, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [4ae38adc2a](https://bsd-hardware.info/?probe=4ae38adc2a) | Apr 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [c960f2dc8b](https://bsd-hardware.info/?probe=c960f2dc8b) | Apr 12, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [bee20c6a4c](https://bsd-hardware.info/?probe=bee20c6a4c) | Apr 12, 2023 |
| HP            | 212B                        | Desktop     | [0fb2a36b23](https://bsd-hardware.info/?probe=0fb2a36b23) | Apr 12, 2023 |
| Supermicro    | M11SDV-8C+-LN4F             | Server      | [f7bcf353a9](https://bsd-hardware.info/?probe=f7bcf353a9) | Apr 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [add8280600](https://bsd-hardware.info/?probe=add8280600) | Apr 11, 2023 |
| MSI           | H81M-P33                    | Desktop     | [90ab4216eb](https://bsd-hardware.info/?probe=90ab4216eb) | Apr 09, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [62358071bf](https://bsd-hardware.info/?probe=62358071bf) | Apr 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a06682a305](https://bsd-hardware.info/?probe=a06682a305) | Apr 09, 2023 |
| HP            | 212B                        | Desktop     | [6dc537109d](https://bsd-hardware.info/?probe=6dc537109d) | Apr 09, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [6dabd5d84a](https://bsd-hardware.info/?probe=6dabd5d84a) | Apr 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [f96c113329](https://bsd-hardware.info/?probe=f96c113329) | Apr 08, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [a305360215](https://bsd-hardware.info/?probe=a305360215) | Apr 05, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [a4957dcdd6](https://bsd-hardware.info/?probe=a4957dcdd6) | Apr 04, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [ee2b566f14](https://bsd-hardware.info/?probe=ee2b566f14) | Apr 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [c801b9e5af](https://bsd-hardware.info/?probe=c801b9e5af) | Apr 03, 2023 |
| HP            | 81C6 MVB 0C                 | Server      | [65d2113596](https://bsd-hardware.info/?probe=65d2113596) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [9b2420726f](https://bsd-hardware.info/?probe=9b2420726f) | Apr 03, 2023 |
| HP            | 212B                        | Desktop     | [00c0cbbc9a](https://bsd-hardware.info/?probe=00c0cbbc9a) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [414cbf5935](https://bsd-hardware.info/?probe=414cbf5935) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b79c64c73](https://bsd-hardware.info/?probe=6b79c64c73) | Apr 03, 2023 |
| Gigabyte      | GB-BSi3-1115G4              | Desktop     | [2a7e5e0e71](https://bsd-hardware.info/?probe=2a7e5e0e71) | Apr 02, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [911a1723a2](https://bsd-hardware.info/?probe=911a1723a2) | Apr 02, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [01bf5e8678](https://bsd-hardware.info/?probe=01bf5e8678) | Apr 02, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0013b5dfa4](https://bsd-hardware.info/?probe=0013b5dfa4) | Apr 02, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [ff7383d618](https://bsd-hardware.info/?probe=ff7383d618) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d4cc6cf349](https://bsd-hardware.info/?probe=d4cc6cf349) | Apr 02, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | Notebook    | [0b93ef8199](https://bsd-hardware.info/?probe=0b93ef8199) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [9bac0139f1](https://bsd-hardware.info/?probe=9bac0139f1) | Apr 01, 2023 |
| Chuwi         | Unknown                     | Notebook    | [5e687fcc83](https://bsd-hardware.info/?probe=5e687fcc83) | Apr 01, 2023 |
| ASRock        | X570S PG Riptide            | Desktop     | [8ccb321056](https://bsd-hardware.info/?probe=8ccb321056) | Apr 01, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c7944c3ce9](https://bsd-hardware.info/?probe=c7944c3ce9) | Mar 31, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [8e2e4d6686](https://bsd-hardware.info/?probe=8e2e4d6686) | Mar 31, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [3c3a780d95](https://bsd-hardware.info/?probe=3c3a780d95) | Mar 31, 2023 |
| ASRockRack    | EPYCD8-2T                   | Desktop     | [75f414997a](https://bsd-hardware.info/?probe=75f414997a) | Mar 31, 2023 |
| HP            | 339A                        | Desktop     | [ad10416fe3](https://bsd-hardware.info/?probe=ad10416fe3) | Mar 31, 2023 |
| Biostar       | TH67B                       | Desktop     | [234c5e0b83](https://bsd-hardware.info/?probe=234c5e0b83) | Mar 31, 2023 |
| HMT           | W041-TF-A-45                | Notebook    | [666df5a7e0](https://bsd-hardware.info/?probe=666df5a7e0) | Mar 31, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [1d7c737c38](https://bsd-hardware.info/?probe=1d7c737c38) | Mar 29, 2023 |
| Google        | Stout                       | Notebook    | [d8346bb5da](https://bsd-hardware.info/?probe=d8346bb5da) | Mar 29, 2023 |
| Alienware     | 049PDM A00                  | Desktop     | [139d115cdb](https://bsd-hardware.info/?probe=139d115cdb) | Mar 29, 2023 |
| Shuttle       | FH110                       | Desktop     | [4fa8a9cc08](https://bsd-hardware.info/?probe=4fa8a9cc08) | Mar 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [b4805cd318](https://bsd-hardware.info/?probe=b4805cd318) | Mar 27, 2023 |
| ASRock        | X570S PG Riptide            | Desktop     | [0d66edbd38](https://bsd-hardware.info/?probe=0d66edbd38) | Mar 27, 2023 |
| Dell          | 0VD5HY A00                  | Desktop     | [1b54a68123](https://bsd-hardware.info/?probe=1b54a68123) | Mar 26, 2023 |
| Dell          | 0C2GT0 A05                  | Server      | [2d32ae23e6](https://bsd-hardware.info/?probe=2d32ae23e6) | Mar 26, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [7652c9891e](https://bsd-hardware.info/?probe=7652c9891e) | Mar 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [f07e9fd36c](https://bsd-hardware.info/?probe=f07e9fd36c) | Mar 26, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [3f21567fdf](https://bsd-hardware.info/?probe=3f21567fdf) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [38a22651c6](https://bsd-hardware.info/?probe=38a22651c6) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [a46f77ccdc](https://bsd-hardware.info/?probe=a46f77ccdc) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b64571464f](https://bsd-hardware.info/?probe=b64571464f) | Mar 25, 2023 |
| HP            | 1497                        | Desktop     | [08daaf3be1](https://bsd-hardware.info/?probe=08daaf3be1) | Mar 25, 2023 |
| HP            | 21B4 A01                    | Desktop     | [8de4b8231a](https://bsd-hardware.info/?probe=8de4b8231a) | Mar 25, 2023 |
| HP            | 1497                        | Desktop     | [fc6a7ebc91](https://bsd-hardware.info/?probe=fc6a7ebc91) | Mar 25, 2023 |
| eMachines     | eM350                       | Notebook    | [bb900ace2d](https://bsd-hardware.info/?probe=bb900ace2d) | Mar 25, 2023 |
| HP            | 1497                        | Desktop     | [e98b5284d9](https://bsd-hardware.info/?probe=e98b5284d9) | Mar 25, 2023 |
| Alienware     | 14                          | Notebook    | [742d648570](https://bsd-hardware.info/?probe=742d648570) | Mar 25, 2023 |
| Acer          | AOD270                      | Notebook    | [73877008e9](https://bsd-hardware.info/?probe=73877008e9) | Mar 25, 2023 |
| Acer          | Nitro AN515-53              | Notebook    | [a46e065fac](https://bsd-hardware.info/?probe=a46e065fac) | Mar 23, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [f294f7ae04](https://bsd-hardware.info/?probe=f294f7ae04) | Mar 23, 2023 |
| HP            | 3397                        | Desktop     | [a3a77965fc](https://bsd-hardware.info/?probe=a3a77965fc) | Mar 23, 2023 |
| Intel         | SandyBridge Platform        | Notebook    | [954a21f7de](https://bsd-hardware.info/?probe=954a21f7de) | Mar 23, 2023 |
| Dell          | Edge Gateway 5100           | Mini pc     | [7cb4288db0](https://bsd-hardware.info/?probe=7cb4288db0) | Mar 23, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e1b5d66244](https://bsd-hardware.info/?probe=e1b5d66244) | Mar 20, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [4dc54510d2](https://bsd-hardware.info/?probe=4dc54510d2) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [cab50cddd5](https://bsd-hardware.info/?probe=cab50cddd5) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [ff4dda40eb](https://bsd-hardware.info/?probe=ff4dda40eb) | Mar 19, 2023 |
| MSI           | H81M-P33                    | Desktop     | [17f0f138ee](https://bsd-hardware.info/?probe=17f0f138ee) | Mar 19, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [da50d91be4](https://bsd-hardware.info/?probe=da50d91be4) | Mar 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [726abe2f1d](https://bsd-hardware.info/?probe=726abe2f1d) | Mar 19, 2023 |
| HP            | 212B                        | Desktop     | [d4d93ad679](https://bsd-hardware.info/?probe=d4d93ad679) | Mar 19, 2023 |
| GVC           | DR 738                      | Desktop     | [88455ed9e7](https://bsd-hardware.info/?probe=88455ed9e7) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [c83b0dda87](https://bsd-hardware.info/?probe=c83b0dda87) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [9ac4738956](https://bsd-hardware.info/?probe=9ac4738956) | Mar 18, 2023 |
| IP3 Techno... | ACN1S                       | Notebook    | [d0761f4192](https://bsd-hardware.info/?probe=d0761f4192) | Mar 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| HP            | 3397                        | Desktop     | [2851f91f5f](https://bsd-hardware.info/?probe=2851f91f5f) | Mar 17, 2023 |
| ASUSTek       | 1001P                       | Notebook    | [76eae56ba3](https://bsd-hardware.info/?probe=76eae56ba3) | Mar 15, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [64316408f0](https://bsd-hardware.info/?probe=64316408f0) | Mar 15, 2023 |
| Acer          | Aspire V3-112P              | Notebook    | [104c10f9b0](https://bsd-hardware.info/?probe=104c10f9b0) | Mar 14, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [b878473783](https://bsd-hardware.info/?probe=b878473783) | Mar 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [49764ec5fa](https://bsd-hardware.info/?probe=49764ec5fa) | Mar 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [a8a9ed7f9e](https://bsd-hardware.info/?probe=a8a9ed7f9e) | Mar 13, 2023 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | Notebook    | [8b112aa100](https://bsd-hardware.info/?probe=8b112aa100) | Mar 13, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [b2ef9ff3dc](https://bsd-hardware.info/?probe=b2ef9ff3dc) | Mar 12, 2023 |
| HP            | 0AA8h                       | Desktop     | [15ddd97321](https://bsd-hardware.info/?probe=15ddd97321) | Mar 12, 2023 |
| Supermicro    | X7DWE                       | Desktop     | [e40b569ff7](https://bsd-hardware.info/?probe=e40b569ff7) | Mar 12, 2023 |
| MSI           | H81M-P33                    | Desktop     | [12dbc1a2b3](https://bsd-hardware.info/?probe=12dbc1a2b3) | Mar 12, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [bcd9058821](https://bsd-hardware.info/?probe=bcd9058821) | Mar 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d93ae717cc](https://bsd-hardware.info/?probe=d93ae717cc) | Mar 12, 2023 |
| Google        | Kohaku                      | Notebook    | [88491d298e](https://bsd-hardware.info/?probe=88491d298e) | Mar 12, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [80dd48bca9](https://bsd-hardware.info/?probe=80dd48bca9) | Mar 12, 2023 |
| Dell          | Precision 7720              | Notebook    | [01f5f21b76](https://bsd-hardware.info/?probe=01f5f21b76) | Mar 12, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [c8abf1f5bf](https://bsd-hardware.info/?probe=c8abf1f5bf) | Mar 11, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3548f4efa2](https://bsd-hardware.info/?probe=3548f4efa2) | Mar 11, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [a4366e53ba](https://bsd-hardware.info/?probe=a4366e53ba) | Mar 10, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [654bdb4eb2](https://bsd-hardware.info/?probe=654bdb4eb2) | Mar 10, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [62c09245a4](https://bsd-hardware.info/?probe=62c09245a4) | Mar 10, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [6ac60b8104](https://bsd-hardware.info/?probe=6ac60b8104) | Mar 10, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [88de48013c](https://bsd-hardware.info/?probe=88de48013c) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495 20NKS0HN1N    | Notebook    | [af190c38e9](https://bsd-hardware.info/?probe=af190c38e9) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | Notebook    | [223879138d](https://bsd-hardware.info/?probe=223879138d) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [e5a43dd311](https://bsd-hardware.info/?probe=e5a43dd311) | Mar 10, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [44a8bf8fbc](https://bsd-hardware.info/?probe=44a8bf8fbc) | Mar 10, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [970f35af17](https://bsd-hardware.info/?probe=970f35af17) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [278a2a11cd](https://bsd-hardware.info/?probe=278a2a11cd) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [ef85735453](https://bsd-hardware.info/?probe=ef85735453) | Mar 09, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [58090b9dbf](https://bsd-hardware.info/?probe=58090b9dbf) | Mar 09, 2023 |
| Dell          | Latitude D620               | Notebook    | [8b3ad4e8b9](https://bsd-hardware.info/?probe=8b3ad4e8b9) | Mar 09, 2023 |
| Dell          | Latitude D620               | Notebook    | [d42a8ee079](https://bsd-hardware.info/?probe=d42a8ee079) | Mar 09, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | Desktop     | [98fe8cc428](https://bsd-hardware.info/?probe=98fe8cc428) | Mar 09, 2023 |
| Samsung       | 750XEE                      | Notebook    | [47d2204f58](https://bsd-hardware.info/?probe=47d2204f58) | Mar 08, 2023 |
| Lenovo        | ThinkPad X230 2324A14       | Notebook    | [124b3bdb95](https://bsd-hardware.info/?probe=124b3bdb95) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [9466e6d4f4](https://bsd-hardware.info/?probe=9466e6d4f4) | Mar 07, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [1a2543f92f](https://bsd-hardware.info/?probe=1a2543f92f) | Mar 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [2ba0e18863](https://bsd-hardware.info/?probe=2ba0e18863) | Mar 05, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [a3f77b82cc](https://bsd-hardware.info/?probe=a3f77b82cc) | Mar 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [dfa124b6f9](https://bsd-hardware.info/?probe=dfa124b6f9) | Mar 05, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [64513c0ff5](https://bsd-hardware.info/?probe=64513c0ff5) | Mar 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ebba69095d](https://bsd-hardware.info/?probe=ebba69095d) | Mar 05, 2023 |
| ASRock        | E350M1                      | Desktop     | [461f8cca23](https://bsd-hardware.info/?probe=461f8cca23) | Mar 04, 2023 |
| Intel         | D510MO AAE76523-403         | Desktop     | [0da634580f](https://bsd-hardware.info/?probe=0da634580f) | Mar 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | Notebook    | [6d7b30d2c4](https://bsd-hardware.info/?probe=6d7b30d2c4) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f9db95d778](https://bsd-hardware.info/?probe=f9db95d778) | Mar 03, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [3daad10634](https://bsd-hardware.info/?probe=3daad10634) | Mar 02, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [98096adfaa](https://bsd-hardware.info/?probe=98096adfaa) | Mar 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [d675a5bab2](https://bsd-hardware.info/?probe=d675a5bab2) | Feb 28, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [735f2f3ece](https://bsd-hardware.info/?probe=735f2f3ece) | Feb 28, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | Notebook    | [0e051e7291](https://bsd-hardware.info/?probe=0e051e7291) | Feb 27, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [ffbb7e1a96](https://bsd-hardware.info/?probe=ffbb7e1a96) | Feb 27, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [b0fcea0c90](https://bsd-hardware.info/?probe=b0fcea0c90) | Feb 27, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [e85ed3f609](https://bsd-hardware.info/?probe=e85ed3f609) | Feb 27, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [9d406d735e](https://bsd-hardware.info/?probe=9d406d735e) | Feb 26, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1a4897cb53](https://bsd-hardware.info/?probe=1a4897cb53) | Feb 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [806efadc12](https://bsd-hardware.info/?probe=806efadc12) | Feb 26, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [efb350b5f2](https://bsd-hardware.info/?probe=efb350b5f2) | Feb 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [62567aa5d4](https://bsd-hardware.info/?probe=62567aa5d4) | Feb 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [2ab690000c](https://bsd-hardware.info/?probe=2ab690000c) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [ae0dc68ba6](https://bsd-hardware.info/?probe=ae0dc68ba6) | Feb 25, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | Notebook    | [97d9b10c8a](https://bsd-hardware.info/?probe=97d9b10c8a) | Feb 24, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1e548fa114](https://bsd-hardware.info/?probe=1e548fa114) | Feb 24, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b2681fdfb4](https://bsd-hardware.info/?probe=b2681fdfb4) | Feb 23, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [3dae7e3ebb](https://bsd-hardware.info/?probe=3dae7e3ebb) | Feb 23, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [6669622646](https://bsd-hardware.info/?probe=6669622646) | Feb 23, 2023 |
| Gigabyte      | Z87X-OC-CF                  | Desktop     | [dca82c50d0](https://bsd-hardware.info/?probe=dca82c50d0) | Feb 23, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [e55635df08](https://bsd-hardware.info/?probe=e55635df08) | Feb 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [9e92cf3575](https://bsd-hardware.info/?probe=9e92cf3575) | Feb 22, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [b2ed608da5](https://bsd-hardware.info/?probe=b2ed608da5) | Feb 21, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [8eb068a097](https://bsd-hardware.info/?probe=8eb068a097) | Feb 20, 2023 |
| MSI           | H81M-P33                    | Desktop     | [28f48b7936](https://bsd-hardware.info/?probe=28f48b7936) | Feb 19, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b3525afaa7](https://bsd-hardware.info/?probe=b3525afaa7) | Feb 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [19c7044a7d](https://bsd-hardware.info/?probe=19c7044a7d) | Feb 19, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [c30dd3fbca](https://bsd-hardware.info/?probe=c30dd3fbca) | Feb 19, 2023 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [a27331804b](https://bsd-hardware.info/?probe=a27331804b) | Feb 19, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [dd0d96422f](https://bsd-hardware.info/?probe=dd0d96422f) | Feb 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [63b73012e6](https://bsd-hardware.info/?probe=63b73012e6) | Feb 18, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1ba2a827d9](https://bsd-hardware.info/?probe=1ba2a827d9) | Feb 18, 2023 |
| Lenovo        | ThinkPad R60e 0658W2M       | Notebook    | [dba66ebfb5](https://bsd-hardware.info/?probe=dba66ebfb5) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [b241a8afd7](https://bsd-hardware.info/?probe=b241a8afd7) | Feb 16, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [dd083df1a2](https://bsd-hardware.info/?probe=dd083df1a2) | Feb 16, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [0f4dd9a9bc](https://bsd-hardware.info/?probe=0f4dd9a9bc) | Feb 15, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [6f4b514959](https://bsd-hardware.info/?probe=6f4b514959) | Feb 14, 2023 |
| Lenovo        | ThinkPad T430 2347FV6       | Notebook    | [cf016ce514](https://bsd-hardware.info/?probe=cf016ce514) | Feb 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c176577762](https://bsd-hardware.info/?probe=c176577762) | Feb 14, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | Desktop     | [d69aba5432](https://bsd-hardware.info/?probe=d69aba5432) | Feb 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [b3f41e1cb4](https://bsd-hardware.info/?probe=b3f41e1cb4) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b962baf73d](https://bsd-hardware.info/?probe=b962baf73d) | Feb 13, 2023 |
| Acer          | Aspire one V1.05            | Notebook    | [eec371a28f](https://bsd-hardware.info/?probe=eec371a28f) | Feb 13, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [df5f01d72e](https://bsd-hardware.info/?probe=df5f01d72e) | Feb 13, 2023 |
| Panasonic     | CF-30KAPAXAM                | Notebook    | [f686e3756c](https://bsd-hardware.info/?probe=f686e3756c) | Feb 13, 2023 |
| ASUSTek       | P8Z68 DELUXE                | Desktop     | [f65675c771](https://bsd-hardware.info/?probe=f65675c771) | Feb 13, 2023 |
| ASUSTek       | H170I-PRO                   | Desktop     | [63000ada74](https://bsd-hardware.info/?probe=63000ada74) | Feb 12, 2023 |
| HP            | 212B                        | Desktop     | [0e13beb9f6](https://bsd-hardware.info/?probe=0e13beb9f6) | Feb 12, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [5507e05838](https://bsd-hardware.info/?probe=5507e05838) | Feb 12, 2023 |
| Alienware     | m15                         | Notebook    | [3ab3e4b671](https://bsd-hardware.info/?probe=3ab3e4b671) | Feb 12, 2023 |
| MSI           | H81M-P33                    | Desktop     | [84aff26f99](https://bsd-hardware.info/?probe=84aff26f99) | Feb 12, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [4e899d9a1c](https://bsd-hardware.info/?probe=4e899d9a1c) | Feb 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d16e93b7f3](https://bsd-hardware.info/?probe=d16e93b7f3) | Feb 12, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [acff807555](https://bsd-hardware.info/?probe=acff807555) | Feb 12, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [d2edba8775](https://bsd-hardware.info/?probe=d2edba8775) | Feb 11, 2023 |
| Gigabyte      | Z490 VISION G               | Desktop     | [6f8ad1a8b9](https://bsd-hardware.info/?probe=6f8ad1a8b9) | Feb 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8d49d50738](https://bsd-hardware.info/?probe=8d49d50738) | Feb 11, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [81827ccbca](https://bsd-hardware.info/?probe=81827ccbca) | Feb 10, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [4284c60268](https://bsd-hardware.info/?probe=4284c60268) | Feb 10, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [0c9cf4e002](https://bsd-hardware.info/?probe=0c9cf4e002) | Feb 09, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [ca1e51a042](https://bsd-hardware.info/?probe=ca1e51a042) | Feb 09, 2023 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [dd9685a909](https://bsd-hardware.info/?probe=dd9685a909) | Feb 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d6c8ad1034](https://bsd-hardware.info/?probe=d6c8ad1034) | Feb 08, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [33af90dd93](https://bsd-hardware.info/?probe=33af90dd93) | Feb 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f3b0d5ac82](https://bsd-hardware.info/?probe=f3b0d5ac82) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [4fc5363829](https://bsd-hardware.info/?probe=4fc5363829) | Feb 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [ef722fc37b](https://bsd-hardware.info/?probe=ef722fc37b) | Feb 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [ec37957aed](https://bsd-hardware.info/?probe=ec37957aed) | Feb 05, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [a98d28355d](https://bsd-hardware.info/?probe=a98d28355d) | Feb 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6f8f329a5b](https://bsd-hardware.info/?probe=6f8f329a5b) | Feb 05, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [bd418783d4](https://bsd-hardware.info/?probe=bd418783d4) | Feb 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ec1ab0bf97](https://bsd-hardware.info/?probe=ec1ab0bf97) | Feb 05, 2023 |
| Samsung       | 700T1C                      | Notebook    | [91d5c568d1](https://bsd-hardware.info/?probe=91d5c568d1) | Feb 05, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [5462140da0](https://bsd-hardware.info/?probe=5462140da0) | Feb 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [0232c45faa](https://bsd-hardware.info/?probe=0232c45faa) | Feb 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [b7a491a010](https://bsd-hardware.info/?probe=b7a491a010) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d36789c493](https://bsd-hardware.info/?probe=d36789c493) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS04200    | Notebook    | [3178015cd3](https://bsd-hardware.info/?probe=3178015cd3) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a54516414a](https://bsd-hardware.info/?probe=a54516414a) | Feb 01, 2023 |
| Lenovo        | ThinkPad T460p 20FW0018A... | Notebook    | [932e722b2d](https://bsd-hardware.info/?probe=932e722b2d) | Feb 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [6d46662662](https://bsd-hardware.info/?probe=6d46662662) | Jan 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [82ab576c6c](https://bsd-hardware.info/?probe=82ab576c6c) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [341bae363a](https://bsd-hardware.info/?probe=341bae363a) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0b48f96d1e](https://bsd-hardware.info/?probe=0b48f96d1e) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [c2f84d2103](https://bsd-hardware.info/?probe=c2f84d2103) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [165d435f30](https://bsd-hardware.info/?probe=165d435f30) | Jan 31, 2023 |
| ASRock        | 970 Extreme3                | Desktop     | [5e2fd4b48f](https://bsd-hardware.info/?probe=5e2fd4b48f) | Jan 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [39ae8fb9c8](https://bsd-hardware.info/?probe=39ae8fb9c8) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [75b9ef6ee6](https://bsd-hardware.info/?probe=75b9ef6ee6) | Jan 30, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [21398109dc](https://bsd-hardware.info/?probe=21398109dc) | Jan 29, 2023 |
| MSI           | H81M-P33                    | Desktop     | [e6626da98c](https://bsd-hardware.info/?probe=e6626da98c) | Jan 29, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [3d5ea9f313](https://bsd-hardware.info/?probe=3d5ea9f313) | Jan 29, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9b7532b795](https://bsd-hardware.info/?probe=9b7532b795) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [2098b8808d](https://bsd-hardware.info/?probe=2098b8808d) | Jan 29, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [1c4edf62e6](https://bsd-hardware.info/?probe=1c4edf62e6) | Jan 28, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [8fd7f80256](https://bsd-hardware.info/?probe=8fd7f80256) | Jan 28, 2023 |
| Acer          | Aspire one V1.05            | Notebook    | [1cbfce4d7e](https://bsd-hardware.info/?probe=1cbfce4d7e) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [d5f06d91db](https://bsd-hardware.info/?probe=d5f06d91db) | Jan 28, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [1603f38c4c](https://bsd-hardware.info/?probe=1603f38c4c) | Jan 28, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [d32c9457b9](https://bsd-hardware.info/?probe=d32c9457b9) | Jan 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [448f9265f2](https://bsd-hardware.info/?probe=448f9265f2) | Jan 27, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [512bf8f61d](https://bsd-hardware.info/?probe=512bf8f61d) | Jan 27, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [92c676e033](https://bsd-hardware.info/?probe=92c676e033) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [87e25e2abd](https://bsd-hardware.info/?probe=87e25e2abd) | Jan 26, 2023 |
| Shuttle       | DS20U                       | Desktop     | [71033e4a64](https://bsd-hardware.info/?probe=71033e4a64) | Jan 26, 2023 |
| IBM           | 9210MML                     | Desktop     | [8b7e2413ee](https://bsd-hardware.info/?probe=8b7e2413ee) | Jan 25, 2023 |
| ADI Engine... | RCC-VE                      | Desktop     | [e2941c00fc](https://bsd-hardware.info/?probe=e2941c00fc) | Jan 25, 2023 |
| Supermicro    | X11SSH-F                    | Server      | [106cf811d8](https://bsd-hardware.info/?probe=106cf811d8) | Jan 25, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4eb4e63a2c](https://bsd-hardware.info/?probe=4eb4e63a2c) | Jan 25, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [afeb216c1e](https://bsd-hardware.info/?probe=afeb216c1e) | Jan 25, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [ab59ccf04c](https://bsd-hardware.info/?probe=ab59ccf04c) | Jan 24, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | Notebook    | [24544f4a94](https://bsd-hardware.info/?probe=24544f4a94) | Jan 24, 2023 |
| Lenovo        | ThinkPad T430 2342AG4       | Notebook    | [b5e972d19a](https://bsd-hardware.info/?probe=b5e972d19a) | Jan 24, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [7319560506](https://bsd-hardware.info/?probe=7319560506) | Jan 24, 2023 |
| Medion        | S14409                      | Notebook    | [9a44efb64c](https://bsd-hardware.info/?probe=9a44efb64c) | Jan 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [dcc804a61f](https://bsd-hardware.info/?probe=dcc804a61f) | Jan 22, 2023 |
| Dell          | Latitude E6400              | Notebook    | [9dd8d0184f](https://bsd-hardware.info/?probe=9dd8d0184f) | Jan 22, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [26d1d923d6](https://bsd-hardware.info/?probe=26d1d923d6) | Jan 22, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0bbc074f1c](https://bsd-hardware.info/?probe=0bbc074f1c) | Jan 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [28d8d82d34](https://bsd-hardware.info/?probe=28d8d82d34) | Jan 22, 2023 |
| Unknown       | AMD-GX3                     | Desktop     | [a38ff8331a](https://bsd-hardware.info/?probe=a38ff8331a) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [3afbfc6cea](https://bsd-hardware.info/?probe=3afbfc6cea) | Jan 20, 2023 |
| Unknown       | YL-SKUL6                    | Desktop     | [ef4abfe322](https://bsd-hardware.info/?probe=ef4abfe322) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [e13627df1a](https://bsd-hardware.info/?probe=e13627df1a) | Jan 20, 2023 |
| Acer          | TravelMate B311-31          | Notebook    | [dc3f072645](https://bsd-hardware.info/?probe=dc3f072645) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [35e269ef1c](https://bsd-hardware.info/?probe=35e269ef1c) | Jan 19, 2023 |
| Dell          | Precision 5540              | Notebook    | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [b528c0bbe3](https://bsd-hardware.info/?probe=b528c0bbe3) | Jan 18, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [c3281eb186](https://bsd-hardware.info/?probe=c3281eb186) | Jan 18, 2023 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [ed566c9a5c](https://bsd-hardware.info/?probe=ed566c9a5c) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [f7de27b0ca](https://bsd-hardware.info/?probe=f7de27b0ca) | Jan 18, 2023 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [cfb839082b](https://bsd-hardware.info/?probe=cfb839082b) | Jan 18, 2023 |
| Lenovo        | H30-05 90BJ0085SP           | Desktop     | [d491694079](https://bsd-hardware.info/?probe=d491694079) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [9eee9cc526](https://bsd-hardware.info/?probe=9eee9cc526) | Jan 18, 2023 |
| Intel         | DH67BL AAG10189-206         | Desktop     | [37ae895d75](https://bsd-hardware.info/?probe=37ae895d75) | Jan 17, 2023 |
| Intel         | DQ45CB AAE30148-302         | Desktop     | [349da05405](https://bsd-hardware.info/?probe=349da05405) | Jan 17, 2023 |
| HP            | 1998                        | Desktop     | [6c36e5e82e](https://bsd-hardware.info/?probe=6c36e5e82e) | Jan 17, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [78327c664e](https://bsd-hardware.info/?probe=78327c664e) | Jan 16, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [7ef714a7f1](https://bsd-hardware.info/?probe=7ef714a7f1) | Jan 16, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [247370372d](https://bsd-hardware.info/?probe=247370372d) | Jan 15, 2023 |
| AZW           | SEi                         | Mini pc     | [362a33bd50](https://bsd-hardware.info/?probe=362a33bd50) | Jan 15, 2023 |
| MSI           | H81M-P33                    | Desktop     | [800b3bc34b](https://bsd-hardware.info/?probe=800b3bc34b) | Jan 15, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [ffbcac312f](https://bsd-hardware.info/?probe=ffbcac312f) | Jan 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [48e7397e29](https://bsd-hardware.info/?probe=48e7397e29) | Jan 15, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [e4c2272546](https://bsd-hardware.info/?probe=e4c2272546) | Jan 15, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [05cc17947c](https://bsd-hardware.info/?probe=05cc17947c) | Jan 15, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [ad094a458b](https://bsd-hardware.info/?probe=ad094a458b) | Jan 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f682e06d06](https://bsd-hardware.info/?probe=f682e06d06) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [917972b6ae](https://bsd-hardware.info/?probe=917972b6ae) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [bd60eadfc4](https://bsd-hardware.info/?probe=bd60eadfc4) | Jan 12, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [95ebd841b2](https://bsd-hardware.info/?probe=95ebd841b2) | Jan 12, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [3126dc27f1](https://bsd-hardware.info/?probe=3126dc27f1) | Jan 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [cb7b02c421](https://bsd-hardware.info/?probe=cb7b02c421) | Jan 11, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | Notebook    | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [864db5c1f9](https://bsd-hardware.info/?probe=864db5c1f9) | Jan 11, 2023 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [07f15d0014](https://bsd-hardware.info/?probe=07f15d0014) | Jan 11, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [2428fe6bd3](https://bsd-hardware.info/?probe=2428fe6bd3) | Jan 10, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [9bda43254c](https://bsd-hardware.info/?probe=9bda43254c) | Jan 10, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [3a9ec9299c](https://bsd-hardware.info/?probe=3a9ec9299c) | Jan 09, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [8def3dc9b2](https://bsd-hardware.info/?probe=8def3dc9b2) | Jan 09, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [470fa4f28a](https://bsd-hardware.info/?probe=470fa4f28a) | Jan 09, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [97b65880b0](https://bsd-hardware.info/?probe=97b65880b0) | Jan 09, 2023 |
| MSI           | H81M-P33                    | Desktop     | [585a3dc78c](https://bsd-hardware.info/?probe=585a3dc78c) | Jan 08, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1e9d8cc278](https://bsd-hardware.info/?probe=1e9d8cc278) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [490261883c](https://bsd-hardware.info/?probe=490261883c) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [e56cfbdedc](https://bsd-hardware.info/?probe=e56cfbdedc) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [db483e3d46](https://bsd-hardware.info/?probe=db483e3d46) | Jan 08, 2023 |
| Supermicro    | X10DRL-i                    | Server      | [c0fa5bb871](https://bsd-hardware.info/?probe=c0fa5bb871) | Jan 06, 2023 |
| MSI           | MEG Z690 UNIFY-X            | Desktop     | [e70cd80d11](https://bsd-hardware.info/?probe=e70cd80d11) | Jan 05, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [219200b0b6](https://bsd-hardware.info/?probe=219200b0b6) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [cc9d84d5ed](https://bsd-hardware.info/?probe=cc9d84d5ed) | Jan 05, 2023 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [9dc3183152](https://bsd-hardware.info/?probe=9dc3183152) | Jan 04, 2023 |
| Supermicro    | X10DRiB                     | Desktop     | [d120c268f7](https://bsd-hardware.info/?probe=d120c268f7) | Jan 04, 2023 |
| Supermicro    | X10DRi-T                    | Desktop     | [3bd4e1dc9c](https://bsd-hardware.info/?probe=3bd4e1dc9c) | Jan 04, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [17f5e2e3d2](https://bsd-hardware.info/?probe=17f5e2e3d2) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [a1517b13f6](https://bsd-hardware.info/?probe=a1517b13f6) | Jan 04, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [409d119307](https://bsd-hardware.info/?probe=409d119307) | Jan 02, 2023 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [d66b90249d](https://bsd-hardware.info/?probe=d66b90249d) | Jan 02, 2023 |
| Alienware     | m15 R4                      | Notebook    | [1438237430](https://bsd-hardware.info/?probe=1438237430) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [1697219032](https://bsd-hardware.info/?probe=1697219032) | Jan 02, 2023 |
| Shuttle       | DS20U                       | Desktop     | [a5aa09e49f](https://bsd-hardware.info/?probe=a5aa09e49f) | Jan 01, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [a9b3805c0b](https://bsd-hardware.info/?probe=a9b3805c0b) | Jan 01, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0a57dcce99](https://bsd-hardware.info/?probe=0a57dcce99) | Jan 01, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [d3306559de](https://bsd-hardware.info/?probe=d3306559de) | Jan 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [772779fadf](https://bsd-hardware.info/?probe=772779fadf) | Jan 01, 2023 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | Notebook    | [22c4a06468](https://bsd-hardware.info/?probe=22c4a06468) | Dec 31, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [ab7e64f657](https://bsd-hardware.info/?probe=ab7e64f657) | Dec 31, 2022 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | Desktop     | [ac867149f2](https://bsd-hardware.info/?probe=ac867149f2) | Dec 31, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [956499202e](https://bsd-hardware.info/?probe=956499202e) | Dec 30, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d22c37fa81](https://bsd-hardware.info/?probe=d22c37fa81) | Dec 29, 2022 |
| MSI           | H270 GAMING M3              | Desktop     | [5d14519e73](https://bsd-hardware.info/?probe=5d14519e73) | Dec 28, 2022 |
| MSI           | H270 GAMING M3              | Desktop     | [5dcdab1ee3](https://bsd-hardware.info/?probe=5dcdab1ee3) | Dec 28, 2022 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| Google        | Peppy                       | Notebook    | [e063619f03](https://bsd-hardware.info/?probe=e063619f03) | Dec 27, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [07dc4a3178](https://bsd-hardware.info/?probe=07dc4a3178) | Dec 27, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [50c8cb79f7](https://bsd-hardware.info/?probe=50c8cb79f7) | Dec 26, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [bc829dbb1a](https://bsd-hardware.info/?probe=bc829dbb1a) | Dec 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [f73a37ab81](https://bsd-hardware.info/?probe=f73a37ab81) | Dec 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2e842ddb27](https://bsd-hardware.info/?probe=2e842ddb27) | Dec 25, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [883dbf15e4](https://bsd-hardware.info/?probe=883dbf15e4) | Dec 25, 2022 |
| Supermicro    | X10SRH-CLN4FA               | Desktop     | [84c360ad02](https://bsd-hardware.info/?probe=84c360ad02) | Dec 24, 2022 |
| Alienware     | m15 R4                      | Notebook    | [deaef8f0ef](https://bsd-hardware.info/?probe=deaef8f0ef) | Dec 24, 2022 |
| Dell          | 0H28RR A04                  | Server      | [8e22402d9e](https://bsd-hardware.info/?probe=8e22402d9e) | Dec 24, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [a2bc442acd](https://bsd-hardware.info/?probe=a2bc442acd) | Dec 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| Dell          | Vostro 1400                 | Notebook    | [087a3d269f](https://bsd-hardware.info/?probe=087a3d269f) | Dec 23, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [527bf6bbe4](https://bsd-hardware.info/?probe=527bf6bbe4) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [b8c89bdca8](https://bsd-hardware.info/?probe=b8c89bdca8) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [b0d1792185](https://bsd-hardware.info/?probe=b0d1792185) | Dec 21, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8de4ff8626](https://bsd-hardware.info/?probe=8de4ff8626) | Dec 20, 2022 |
| Lenovo        | ThinkPad T530 2392AQU       | Notebook    | [9a3cbe1893](https://bsd-hardware.info/?probe=9a3cbe1893) | Dec 19, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [0eea35e069](https://bsd-hardware.info/?probe=0eea35e069) | Dec 19, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [683591700f](https://bsd-hardware.info/?probe=683591700f) | Dec 19, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b730e64d4a](https://bsd-hardware.info/?probe=b730e64d4a) | Dec 19, 2022 |
| Acer          | Veriton M680G               | Desktop     | [cb44a9e848](https://bsd-hardware.info/?probe=cb44a9e848) | Dec 19, 2022 |
| Acer          | Veriton M680G               | Desktop     | [f7184d9158](https://bsd-hardware.info/?probe=f7184d9158) | Dec 19, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [c233fa7d25](https://bsd-hardware.info/?probe=c233fa7d25) | Dec 18, 2022 |
| Dell          | Precision M4800             | Notebook    | [b7a834c4d0](https://bsd-hardware.info/?probe=b7a834c4d0) | Dec 18, 2022 |
| ASRock        | B660M-ITX/ac                | Desktop     | [f6c8eb4e18](https://bsd-hardware.info/?probe=f6c8eb4e18) | Dec 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c1b0b83306](https://bsd-hardware.info/?probe=c1b0b83306) | Dec 18, 2022 |
| MSI           | H81M-P33                    | Desktop     | [78e4743abd](https://bsd-hardware.info/?probe=78e4743abd) | Dec 18, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [f232e5746e](https://bsd-hardware.info/?probe=f232e5746e) | Dec 18, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [108c9de5cc](https://bsd-hardware.info/?probe=108c9de5cc) | Dec 18, 2022 |
| Dell          | Latitude E6430              | Notebook    | [b8f950de05](https://bsd-hardware.info/?probe=b8f950de05) | Dec 17, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7cf06451fd](https://bsd-hardware.info/?probe=7cf06451fd) | Dec 17, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [b7e599f99d](https://bsd-hardware.info/?probe=b7e599f99d) | Dec 17, 2022 |
| Dell          | Latitude E6430              | Notebook    | [8d92a4e37e](https://bsd-hardware.info/?probe=8d92a4e37e) | Dec 17, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [e6778fa5fd](https://bsd-hardware.info/?probe=e6778fa5fd) | Dec 15, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [6fc0671dc6](https://bsd-hardware.info/?probe=6fc0671dc6) | Dec 14, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [617f431099](https://bsd-hardware.info/?probe=617f431099) | Dec 14, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f52a3d3fa6](https://bsd-hardware.info/?probe=f52a3d3fa6) | Dec 13, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [f51b401c31](https://bsd-hardware.info/?probe=f51b401c31) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [353c3d5cee](https://bsd-hardware.info/?probe=353c3d5cee) | Dec 12, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [64c92d49d9](https://bsd-hardware.info/?probe=64c92d49d9) | Dec 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [73cb5d86bc](https://bsd-hardware.info/?probe=73cb5d86bc) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [809da57d90](https://bsd-hardware.info/?probe=809da57d90) | Dec 11, 2022 |
| Biostar       | A68N-5600E                  | Desktop     | [5274876096](https://bsd-hardware.info/?probe=5274876096) | Dec 11, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [0be43b76d1](https://bsd-hardware.info/?probe=0be43b76d1) | Dec 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [1f110891d0](https://bsd-hardware.info/?probe=1f110891d0) | Dec 11, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [028383847e](https://bsd-hardware.info/?probe=028383847e) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [99502ebe9a](https://bsd-hardware.info/?probe=99502ebe9a) | Dec 11, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [6d10b2a0b4](https://bsd-hardware.info/?probe=6d10b2a0b4) | Dec 11, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [1d8397a653](https://bsd-hardware.info/?probe=1d8397a653) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [2048ff5f71](https://bsd-hardware.info/?probe=2048ff5f71) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c30f53fc6d](https://bsd-hardware.info/?probe=c30f53fc6d) | Dec 09, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [10b6c81bce](https://bsd-hardware.info/?probe=10b6c81bce) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c953c78309](https://bsd-hardware.info/?probe=c953c78309) | Dec 07, 2022 |
| HP            | 82A2                        | Desktop     | [c612b7e283](https://bsd-hardware.info/?probe=c612b7e283) | Dec 06, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [f6685811a3](https://bsd-hardware.info/?probe=f6685811a3) | Dec 05, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Google        | Lick                        | Notebook    | [8099b2df21](https://bsd-hardware.info/?probe=8099b2df21) | Dec 04, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d72a45fb8f](https://bsd-hardware.info/?probe=d72a45fb8f) | Dec 04, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [595d174631](https://bsd-hardware.info/?probe=595d174631) | Dec 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8ee41750dc](https://bsd-hardware.info/?probe=8ee41750dc) | Dec 04, 2022 |
| Google        | Lick                        | Notebook    | [9eb2abcdcc](https://bsd-hardware.info/?probe=9eb2abcdcc) | Dec 03, 2022 |
| Google        | Lars                        | Notebook    | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS5BU00    | Notebook    | [10619ac217](https://bsd-hardware.info/?probe=10619ac217) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [aeb690b9f3](https://bsd-hardware.info/?probe=aeb690b9f3) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [d4e60c5984](https://bsd-hardware.info/?probe=d4e60c5984) | Dec 03, 2022 |
| Intel         | NUC11ATBC4 M53051-400       | Mini pc     | [6fe2ba74b7](https://bsd-hardware.info/?probe=6fe2ba74b7) | Dec 01, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [087264570d](https://bsd-hardware.info/?probe=087264570d) | Nov 30, 2022 |
| Panasonic     | CF-31-5                     | Notebook    | [7047afaaf4](https://bsd-hardware.info/?probe=7047afaaf4) | Nov 30, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [3dd9e3557c](https://bsd-hardware.info/?probe=3dd9e3557c) | Nov 30, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [1d61d0cf62](https://bsd-hardware.info/?probe=1d61d0cf62) | Nov 29, 2022 |
| ASRockRack    | X470D4U                     | Desktop     | [38d7f55ef7](https://bsd-hardware.info/?probe=38d7f55ef7) | Nov 29, 2022 |
| Lenovo        | ThinkPad T430 2347G7G       | Notebook    | [640540cd67](https://bsd-hardware.info/?probe=640540cd67) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [929e4bda1e](https://bsd-hardware.info/?probe=929e4bda1e) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [7c9ee800c5](https://bsd-hardware.info/?probe=7c9ee800c5) | Nov 29, 2022 |
| Acer          | TravelMate B115-M           | Notebook    | [13e318fec2](https://bsd-hardware.info/?probe=13e318fec2) | Nov 29, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [378270eba0](https://bsd-hardware.info/?probe=378270eba0) | Nov 28, 2022 |
| MSI           | H81M-P33                    | Desktop     | [597d48d1c9](https://bsd-hardware.info/?probe=597d48d1c9) | Nov 27, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [10d76fd431](https://bsd-hardware.info/?probe=10d76fd431) | Nov 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [383341b2f1](https://bsd-hardware.info/?probe=383341b2f1) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [c93690c7ca](https://bsd-hardware.info/?probe=c93690c7ca) | Nov 27, 2022 |
| Shuttle       | FZ270                       | Desktop     | [04a7f49322](https://bsd-hardware.info/?probe=04a7f49322) | Nov 27, 2022 |
| Shuttle       | FZ270                       | Desktop     | [10016f39b9](https://bsd-hardware.info/?probe=10016f39b9) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [675c9fdf94](https://bsd-hardware.info/?probe=675c9fdf94) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [a337eb9e5f](https://bsd-hardware.info/?probe=a337eb9e5f) | Nov 27, 2022 |
| Shuttle       | FH270                       | Desktop     | [192351ac6f](https://bsd-hardware.info/?probe=192351ac6f) | Nov 27, 2022 |
| Shuttle       | FH270                       | Desktop     | [3b68d89092](https://bsd-hardware.info/?probe=3b68d89092) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [5048d00fd8](https://bsd-hardware.info/?probe=5048d00fd8) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [60bdb57227](https://bsd-hardware.info/?probe=60bdb57227) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [ebdca950cc](https://bsd-hardware.info/?probe=ebdca950cc) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5f0b8df8d0](https://bsd-hardware.info/?probe=5f0b8df8d0) | Nov 27, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [3ad7cec298](https://bsd-hardware.info/?probe=3ad7cec298) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [6c2ef140be](https://bsd-hardware.info/?probe=6c2ef140be) | Nov 25, 2022 |
| Supermicro    | M11SDV-8C+-LN4F             | Server      | [bcf17b19ec](https://bsd-hardware.info/?probe=bcf17b19ec) | Nov 25, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| Sony          | SVP1321V9RB                 | Notebook    | [932facd689](https://bsd-hardware.info/?probe=932facd689) | Nov 25, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [d0009172b1](https://bsd-hardware.info/?probe=d0009172b1) | Nov 24, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [25cc0129d9](https://bsd-hardware.info/?probe=25cc0129d9) | Nov 24, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [45d96a0b5a](https://bsd-hardware.info/?probe=45d96a0b5a) | Nov 24, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [0ed70ba3c3](https://bsd-hardware.info/?probe=0ed70ba3c3) | Nov 23, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [8ec61db3f0](https://bsd-hardware.info/?probe=8ec61db3f0) | Nov 22, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [e55eb53894](https://bsd-hardware.info/?probe=e55eb53894) | Nov 21, 2022 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | Notebook    | [56bc3b04fd](https://bsd-hardware.info/?probe=56bc3b04fd) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [f7129f1c87](https://bsd-hardware.info/?probe=f7129f1c87) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [17aa370584](https://bsd-hardware.info/?probe=17aa370584) | Nov 21, 2022 |
| HP            | ProBook 4540s               | Notebook    | [6dce896f40](https://bsd-hardware.info/?probe=6dce896f40) | Nov 20, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [8257d11669](https://bsd-hardware.info/?probe=8257d11669) | Nov 20, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d3303d1962](https://bsd-hardware.info/?probe=d3303d1962) | Nov 20, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [b1512a254c](https://bsd-hardware.info/?probe=b1512a254c) | Nov 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [521e5ffa8e](https://bsd-hardware.info/?probe=521e5ffa8e) | Nov 20, 2022 |
| TOPFEEL       | H110D4-P1                   | Desktop     | [90b1dfc430](https://bsd-hardware.info/?probe=90b1dfc430) | Nov 19, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [eaf4ec693e](https://bsd-hardware.info/?probe=eaf4ec693e) | Nov 19, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [9faf79b3f3](https://bsd-hardware.info/?probe=9faf79b3f3) | Nov 18, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [7691355396](https://bsd-hardware.info/?probe=7691355396) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [f732942dd9](https://bsd-hardware.info/?probe=f732942dd9) | Nov 18, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [436a2d30f6](https://bsd-hardware.info/?probe=436a2d30f6) | Nov 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [15657b37e2](https://bsd-hardware.info/?probe=15657b37e2) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f4a8c42773](https://bsd-hardware.info/?probe=f4a8c42773) | Nov 15, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [4c83122cc0](https://bsd-hardware.info/?probe=4c83122cc0) | Nov 14, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [443891740b](https://bsd-hardware.info/?probe=443891740b) | Nov 13, 2022 |
| Medion        | E15415                      | Notebook    | [e467080570](https://bsd-hardware.info/?probe=e467080570) | Nov 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6f1e732a53](https://bsd-hardware.info/?probe=6f1e732a53) | Nov 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [15e38a5ca8](https://bsd-hardware.info/?probe=15e38a5ca8) | Nov 13, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [2b1175a4df](https://bsd-hardware.info/?probe=2b1175a4df) | Nov 13, 2022 |
| MSI           | H81M-P33                    | Desktop     | [98b0980231](https://bsd-hardware.info/?probe=98b0980231) | Nov 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [072f2a6c27](https://bsd-hardware.info/?probe=072f2a6c27) | Nov 13, 2022 |
| Dell          | Latitude E7240              | Notebook    | [ea99621380](https://bsd-hardware.info/?probe=ea99621380) | Nov 12, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [22ec05d988](https://bsd-hardware.info/?probe=22ec05d988) | Nov 12, 2022 |
| Google        | Akemi                       | Notebook    | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [569d5b0cca](https://bsd-hardware.info/?probe=569d5b0cca) | Nov 10, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [87d7d4435b](https://bsd-hardware.info/?probe=87d7d4435b) | Nov 10, 2022 |
| HP            | 21B4 A01                    | Desktop     | [c064c50fea](https://bsd-hardware.info/?probe=c064c50fea) | Nov 09, 2022 |
| HP            | 21B4 A01                    | Desktop     | [e5c599dfab](https://bsd-hardware.info/?probe=e5c599dfab) | Nov 09, 2022 |
| ZOTAC         | ZBOX-QCM7T3000/EN072080S... | Mini pc     | [62ab446b5d](https://bsd-hardware.info/?probe=62ab446b5d) | Nov 09, 2022 |
| HP            | 21B4 A01                    | Desktop     | [0a3ba5478b](https://bsd-hardware.info/?probe=0a3ba5478b) | Nov 09, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [c32a7b407d](https://bsd-hardware.info/?probe=c32a7b407d) | Nov 09, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [32331d772c](https://bsd-hardware.info/?probe=32331d772c) | Nov 08, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [127e0126d1](https://bsd-hardware.info/?probe=127e0126d1) | Nov 08, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | Notebook    | [9f15cb8acc](https://bsd-hardware.info/?probe=9f15cb8acc) | Nov 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [5807159f51](https://bsd-hardware.info/?probe=5807159f51) | Nov 08, 2022 |
| Google        | Zako                        | Desktop     | [5d4b53e2d4](https://bsd-hardware.info/?probe=5d4b53e2d4) | Nov 08, 2022 |
| HP            | ProBook 4540s               | Notebook    | [9c4be9deab](https://bsd-hardware.info/?probe=9c4be9deab) | Nov 07, 2022 |
| ONDA          | N78G5D3 Ver:5.00            | Desktop     | [009bc44d12](https://bsd-hardware.info/?probe=009bc44d12) | Nov 07, 2022 |
| Acer          | RS880M05                    | Desktop     | [455f9b5026](https://bsd-hardware.info/?probe=455f9b5026) | Nov 07, 2022 |
| MSI           | H81M-P33                    | Desktop     | [750d2f53c7](https://bsd-hardware.info/?probe=750d2f53c7) | Nov 06, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [e427ea787e](https://bsd-hardware.info/?probe=e427ea787e) | Nov 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c6abe84145](https://bsd-hardware.info/?probe=c6abe84145) | Nov 06, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [c4fd2595e6](https://bsd-hardware.info/?probe=c4fd2595e6) | Nov 06, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [1373bd7f3e](https://bsd-hardware.info/?probe=1373bd7f3e) | Nov 05, 2022 |
| HP            | ProBook 4540s               | Notebook    | [7596b602c6](https://bsd-hardware.info/?probe=7596b602c6) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d27fd3b1a7](https://bsd-hardware.info/?probe=d27fd3b1a7) | Nov 04, 2022 |
| Lenovo        | YangTianM6880N              | Desktop     | [2e9c3b7368](https://bsd-hardware.info/?probe=2e9c3b7368) | Nov 04, 2022 |
| BESSTAR Te... | HM80                        | Desktop     | [d5c5f30a2d](https://bsd-hardware.info/?probe=d5c5f30a2d) | Nov 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [58c2f4b4f7](https://bsd-hardware.info/?probe=58c2f4b4f7) | Nov 04, 2022 |
| Samsung       | 750TDA                      | Notebook    | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| HP            | ProLiant DL180 G6           | Server      | [289d2f383b](https://bsd-hardware.info/?probe=289d2f383b) | Nov 02, 2022 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [d7141b866c](https://bsd-hardware.info/?probe=d7141b866c) | Nov 02, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [bb0f8a5bfc](https://bsd-hardware.info/?probe=bb0f8a5bfc) | Oct 31, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [cce93ff157](https://bsd-hardware.info/?probe=cce93ff157) | Oct 30, 2022 |
| MSI           | H81M-P33                    | Desktop     | [b67d6a7bb2](https://bsd-hardware.info/?probe=b67d6a7bb2) | Oct 30, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [8161bfd24d](https://bsd-hardware.info/?probe=8161bfd24d) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a0896f17e4](https://bsd-hardware.info/?probe=a0896f17e4) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | Notebook    | [2776d8c350](https://bsd-hardware.info/?probe=2776d8c350) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS10N00    | Notebook    | [04ce25bd7f](https://bsd-hardware.info/?probe=04ce25bd7f) | Oct 29, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [6911e08b7e](https://bsd-hardware.info/?probe=6911e08b7e) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [caad4323ba](https://bsd-hardware.info/?probe=caad4323ba) | Oct 23, 2022 |
| MSI           | H81M-P33                    | Desktop     | [626f503cad](https://bsd-hardware.info/?probe=626f503cad) | Oct 23, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [2b98739799](https://bsd-hardware.info/?probe=2b98739799) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [56dac6bc80](https://bsd-hardware.info/?probe=56dac6bc80) | Oct 23, 2022 |
| IBM           | 49Y6512                     | Server      | [1bc9e20b16](https://bsd-hardware.info/?probe=1bc9e20b16) | Oct 23, 2022 |
| Acer          | Revo RN86                   | Desktop     | [692ea69bab](https://bsd-hardware.info/?probe=692ea69bab) | Oct 21, 2022 |
| HP            | 18E4                        | Desktop     | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| Dell          | Precision M4500             | Notebook    | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [348bef7dba](https://bsd-hardware.info/?probe=348bef7dba) | Oct 20, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [3e2f5956c1](https://bsd-hardware.info/?probe=3e2f5956c1) | Oct 19, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [20ff21d751](https://bsd-hardware.info/?probe=20ff21d751) | Oct 18, 2022 |
| Lenovo        | 30D0 NOK                    | Desktop     | [d1fab8bd54](https://bsd-hardware.info/?probe=d1fab8bd54) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [e057b613a0](https://bsd-hardware.info/?probe=e057b613a0) | Oct 17, 2022 |
| Lenovo        | XiaoXinPro-13API 2019 81... | Notebook    | [dfa08657fd](https://bsd-hardware.info/?probe=dfa08657fd) | Oct 16, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [22881028bc](https://bsd-hardware.info/?probe=22881028bc) | Oct 16, 2022 |
| TYAN Compu... | Intel 440BX/GX Rev. 4       | Desktop     | [8d99f317e4](https://bsd-hardware.info/?probe=8d99f317e4) | Oct 15, 2022 |
| Dell          | 0G1548 A00                  | Desktop     | [226af33d5b](https://bsd-hardware.info/?probe=226af33d5b) | Oct 15, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [06214241b3](https://bsd-hardware.info/?probe=06214241b3) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [6b15856d20](https://bsd-hardware.info/?probe=6b15856d20) | Oct 15, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e67cb3a0c5](https://bsd-hardware.info/?probe=e67cb3a0c5) | Oct 14, 2022 |
| IBM           | 49Y6512                     | Server      | [4471bf6465](https://bsd-hardware.info/?probe=4471bf6465) | Oct 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [10358c7207](https://bsd-hardware.info/?probe=10358c7207) | Oct 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b20b6c7997](https://bsd-hardware.info/?probe=b20b6c7997) | Oct 13, 2022 |
| IBM           | 49Y6512                     | Server      | [1ead286cbe](https://bsd-hardware.info/?probe=1ead286cbe) | Oct 13, 2022 |
| Lenovo        | ThinkPad T440s 20AR003SM... | Notebook    | [df62882c3b](https://bsd-hardware.info/?probe=df62882c3b) | Oct 12, 2022 |
| HP            | 1589                        | Desktop     | [0696d30d3f](https://bsd-hardware.info/?probe=0696d30d3f) | Oct 12, 2022 |
| Dell          | 0WC7KF A00                  | All in one  | [5f271a82bf](https://bsd-hardware.info/?probe=5f271a82bf) | Oct 11, 2022 |
| Dell          | 0WC7KF A00                  | All in one  | [0f87a99ca7](https://bsd-hardware.info/?probe=0f87a99ca7) | Oct 11, 2022 |
| Lenovo        | 316E NOK                    | Mini pc     | [2a7c8f55cb](https://bsd-hardware.info/?probe=2a7c8f55cb) | Oct 10, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [c79fa6f001](https://bsd-hardware.info/?probe=c79fa6f001) | Oct 09, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [442a743538](https://bsd-hardware.info/?probe=442a743538) | Oct 08, 2022 |
| Supermicro    | X8DT6                       | Server      | [2bd1529913](https://bsd-hardware.info/?probe=2bd1529913) | Oct 07, 2022 |
| ASRockRack    | EP2C612D16FM                | Desktop     | [30a582fccb](https://bsd-hardware.info/?probe=30a582fccb) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [601029d3fc](https://bsd-hardware.info/?probe=601029d3fc) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [ce9cfa77aa](https://bsd-hardware.info/?probe=ce9cfa77aa) | Oct 05, 2022 |
| HP            | Compaq 6735s                | Notebook    | [f61208cfea](https://bsd-hardware.info/?probe=f61208cfea) | Oct 05, 2022 |
| HP            | Compaq 6735s                | Notebook    | [718126149c](https://bsd-hardware.info/?probe=718126149c) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | Notebook    | [86289a60aa](https://bsd-hardware.info/?probe=86289a60aa) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | Notebook    | [9f4642f6a5](https://bsd-hardware.info/?probe=9f4642f6a5) | Oct 05, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| Dell          | Precision 5510              | Notebook    | [f69c9fb0ea](https://bsd-hardware.info/?probe=f69c9fb0ea) | Oct 04, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [459c674b3b](https://bsd-hardware.info/?probe=459c674b3b) | Oct 04, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [d89559e5c2](https://bsd-hardware.info/?probe=d89559e5c2) | Oct 03, 2022 |
| Toshiba       | NB300                       | Notebook    | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e83d522905](https://bsd-hardware.info/?probe=e83d522905) | Oct 03, 2022 |
| Dell          | Precision M4500             | Notebook    | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| IBM           | 9210MML                     | Desktop     | [a6e7d7483f](https://bsd-hardware.info/?probe=a6e7d7483f) | Oct 03, 2022 |
| HPE           | ProLiant ML30 Gen10         | Desktop     | [f1b45790d4](https://bsd-hardware.info/?probe=f1b45790d4) | Oct 02, 2022 |
| Dell          | Precision M4800             | Notebook    | [0fcbdeeeb7](https://bsd-hardware.info/?probe=0fcbdeeeb7) | Oct 02, 2022 |
| HP            | 212B                        | Desktop     | [7bc6506336](https://bsd-hardware.info/?probe=7bc6506336) | Oct 01, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [bdabafdcb1](https://bsd-hardware.info/?probe=bdabafdcb1) | Oct 01, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [6f95477df3](https://bsd-hardware.info/?probe=6f95477df3) | Sep 30, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [8e658fe40f](https://bsd-hardware.info/?probe=8e658fe40f) | Sep 30, 2022 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [5fd9a63834](https://bsd-hardware.info/?probe=5fd9a63834) | Sep 30, 2022 |
| AMI           | MNHO-048                    | Desktop     | [2ec6e55a75](https://bsd-hardware.info/?probe=2ec6e55a75) | Sep 28, 2022 |
| Acer          | Swift SF313-52              | Notebook    | [83516dabac](https://bsd-hardware.info/?probe=83516dabac) | Sep 28, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [7e75a1888b](https://bsd-hardware.info/?probe=7e75a1888b) | Sep 27, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [433857f5f7](https://bsd-hardware.info/?probe=433857f5f7) | Sep 27, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| Acer          | Swift SF313-52              | Notebook    | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| Pegatron      | H81-X1                      | Desktop     | [a27c76c490](https://bsd-hardware.info/?probe=a27c76c490) | Sep 25, 2022 |
| ASUSTek       | P9D-X Series                | Server      | [3494695f54](https://bsd-hardware.info/?probe=3494695f54) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | Notebook    | [c947635b8f](https://bsd-hardware.info/?probe=c947635b8f) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | Notebook    | [533c7f35f1](https://bsd-hardware.info/?probe=533c7f35f1) | Sep 25, 2022 |
| Supermicro    | X10SRi-FB                   | Server      | [59ff2014e5](https://bsd-hardware.info/?probe=59ff2014e5) | Sep 25, 2022 |
| Intel         | S1200SP H57532-210          | Server      | [ab6e70abca](https://bsd-hardware.info/?probe=ab6e70abca) | Sep 25, 2022 |
| Supermicro    | X8DT3                       | Server      | [eda1df037b](https://bsd-hardware.info/?probe=eda1df037b) | Sep 25, 2022 |
| Supermicro    | X7DB8                       | Desktop     | [6ebc173873](https://bsd-hardware.info/?probe=6ebc173873) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [8bbf714f6d](https://bsd-hardware.info/?probe=8bbf714f6d) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [60d4585ece](https://bsd-hardware.info/?probe=60d4585ece) | Sep 25, 2022 |
| IBM           | ThinkPad T40 23737CG        | Notebook    | [dfc9b64da2](https://bsd-hardware.info/?probe=dfc9b64da2) | Sep 25, 2022 |
| System76      | Gazelle                     | Notebook    | [d087321049](https://bsd-hardware.info/?probe=d087321049) | Sep 24, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [dbda136daa](https://bsd-hardware.info/?probe=dbda136daa) | Sep 24, 2022 |
| Dell          | System Vostro 3750          | Notebook    | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| System76      | Gazelle                     | Notebook    | [6d5d4f5021](https://bsd-hardware.info/?probe=6d5d4f5021) | Sep 24, 2022 |
| NITRINOnet    | M360RUS56                   | Desktop     | [490b9593e0](https://bsd-hardware.info/?probe=490b9593e0) | Sep 23, 2022 |
| HP            | 21D0                        | Desktop     | [43fa46655e](https://bsd-hardware.info/?probe=43fa46655e) | Sep 21, 2022 |
| Acer          | Aspire E5-771               | Notebook    | [0a58077c49](https://bsd-hardware.info/?probe=0a58077c49) | Sep 20, 2022 |
| HP            | 21D0                        | Desktop     | [463e2563d7](https://bsd-hardware.info/?probe=463e2563d7) | Sep 19, 2022 |
| Toshiba       | PORTEGE R700                | Notebook    | [10b85eccae](https://bsd-hardware.info/?probe=10b85eccae) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [322c8947b6](https://bsd-hardware.info/?probe=322c8947b6) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [0307c109b5](https://bsd-hardware.info/?probe=0307c109b5) | Sep 19, 2022 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [1a9c6a10bd](https://bsd-hardware.info/?probe=1a9c6a10bd) | Sep 19, 2022 |
| HP            | 0B54h D                     | Desktop     | [a24f08281d](https://bsd-hardware.info/?probe=a24f08281d) | Sep 19, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | Notebook    | [2f1f82558e](https://bsd-hardware.info/?probe=2f1f82558e) | Sep 18, 2022 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [91e0f723ea](https://bsd-hardware.info/?probe=91e0f723ea) | Sep 18, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [431ad10ab2](https://bsd-hardware.info/?probe=431ad10ab2) | Sep 17, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [8de53ac515](https://bsd-hardware.info/?probe=8de53ac515) | Sep 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [83e48aa232](https://bsd-hardware.info/?probe=83e48aa232) | Sep 16, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [09b5ca588f](https://bsd-hardware.info/?probe=09b5ca588f) | Sep 16, 2022 |
| Lenovo        | ThinkPad L420 7829WDY       | Notebook    | [a697be2aa9](https://bsd-hardware.info/?probe=a697be2aa9) | Sep 16, 2022 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [ce024b9f84](https://bsd-hardware.info/?probe=ce024b9f84) | Sep 15, 2022 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [15a7e37cbf](https://bsd-hardware.info/?probe=15a7e37cbf) | Sep 15, 2022 |
| Google        | Peppy                       | Notebook    | [80ffa77224](https://bsd-hardware.info/?probe=80ffa77224) | Sep 15, 2022 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [2b4cf189e9](https://bsd-hardware.info/?probe=2b4cf189e9) | Sep 14, 2022 |
| Dell          | 0HJK12 A03                  | Server      | [96ad323ca0](https://bsd-hardware.info/?probe=96ad323ca0) | Sep 13, 2022 |
| Dell          | 0H5J4J A01                  | Server      | [acb91f797f](https://bsd-hardware.info/?probe=acb91f797f) | Sep 13, 2022 |
| Intel         | D945GCLF2 AAE46416-106      | Desktop     | [8e2f7792eb](https://bsd-hardware.info/?probe=8e2f7792eb) | Sep 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f023ae7ed2](https://bsd-hardware.info/?probe=f023ae7ed2) | Sep 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [baaf9cbda6](https://bsd-hardware.info/?probe=baaf9cbda6) | Sep 13, 2022 |
| HP            | 8648                        | Desktop     | [e7e610794c](https://bsd-hardware.info/?probe=e7e610794c) | Sep 12, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [5abbba28de](https://bsd-hardware.info/?probe=5abbba28de) | Sep 11, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [1cbbe33027](https://bsd-hardware.info/?probe=1cbbe33027) | Sep 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [3b668ace72](https://bsd-hardware.info/?probe=3b668ace72) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [62c287a993](https://bsd-hardware.info/?probe=62c287a993) | Sep 11, 2022 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [f91afdb2f3](https://bsd-hardware.info/?probe=f91afdb2f3) | Sep 09, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [98dff45d54](https://bsd-hardware.info/?probe=98dff45d54) | Sep 09, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [860aea3ce4](https://bsd-hardware.info/?probe=860aea3ce4) | Sep 08, 2022 |
| Dell          | Precision 7540              | Notebook    | [f39c0f4d92](https://bsd-hardware.info/?probe=f39c0f4d92) | Sep 08, 2022 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [b0965df7e1](https://bsd-hardware.info/?probe=b0965df7e1) | Sep 08, 2022 |
| Dell          | Latitude 5310               | Notebook    | [6edf4d34fe](https://bsd-hardware.info/?probe=6edf4d34fe) | Sep 07, 2022 |
| Dell          | Latitude E5470              | Notebook    | [9e798cbfc8](https://bsd-hardware.info/?probe=9e798cbfc8) | Sep 07, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7c6751649b](https://bsd-hardware.info/?probe=7c6751649b) | Sep 07, 2022 |
| Dell          | Vostro 5415                 | Notebook    | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| Dell          | Precision 7550              | Notebook    | [d2bf200529](https://bsd-hardware.info/?probe=d2bf200529) | Sep 06, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [ec74af083f](https://bsd-hardware.info/?probe=ec74af083f) | Sep 04, 2022 |
| MSI           | H81M-P33                    | Desktop     | [3f7258c807](https://bsd-hardware.info/?probe=3f7258c807) | Sep 04, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [cced3168c8](https://bsd-hardware.info/?probe=cced3168c8) | Sep 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [61b82d5ebb](https://bsd-hardware.info/?probe=61b82d5ebb) | Sep 04, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [df57940ad5](https://bsd-hardware.info/?probe=df57940ad5) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [72757feb65](https://bsd-hardware.info/?probe=72757feb65) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [5d575c85d0](https://bsd-hardware.info/?probe=5d575c85d0) | Sep 03, 2022 |
| Lenovo        | YangTianM6880N              | Desktop     | [f675498946](https://bsd-hardware.info/?probe=f675498946) | Sep 02, 2022 |
| Unknown       | HX90                        | Desktop     | [568468e95b](https://bsd-hardware.info/?probe=568468e95b) | Sep 01, 2022 |
| Dell          | 0HYPX2 A00                  | Server      | [2779d78756](https://bsd-hardware.info/?probe=2779d78756) | Sep 01, 2022 |
| Dell          | 0MD99X A07                  | Server      | [3c8cc375dc](https://bsd-hardware.info/?probe=3c8cc375dc) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [4e58d828cc](https://bsd-hardware.info/?probe=4e58d828cc) | Sep 01, 2022 |
| Dell          | 07T4MC A09                  | Desktop     | [50fbb0435c](https://bsd-hardware.info/?probe=50fbb0435c) | Aug 31, 2022 |
| Dell          | 07T4MC A09                  | Desktop     | [200b8d381e](https://bsd-hardware.info/?probe=200b8d381e) | Aug 31, 2022 |
| Dell          | 07T4MC A09                  | Desktop     | [ebc79d7728](https://bsd-hardware.info/?probe=ebc79d7728) | Aug 31, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [ac185c104b](https://bsd-hardware.info/?probe=ac185c104b) | Aug 31, 2022 |
| Intel         | X79 V2.72A                  | Desktop     | [435901d8c9](https://bsd-hardware.info/?probe=435901d8c9) | Aug 29, 2022 |
| Dell          | Latitude 7390               | Notebook    | [bc5eb8e237](https://bsd-hardware.info/?probe=bc5eb8e237) | Aug 29, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [75ec0260f9](https://bsd-hardware.info/?probe=75ec0260f9) | Aug 28, 2022 |
| Dell          | Precision 7550              | Notebook    | [71f615178f](https://bsd-hardware.info/?probe=71f615178f) | Aug 27, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [10ca365b40](https://bsd-hardware.info/?probe=10ca365b40) | Aug 26, 2022 |
| Dell          | 07T4MC A00                  | Desktop     | [1060f1b6e3](https://bsd-hardware.info/?probe=1060f1b6e3) | Aug 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [5684672f5a](https://bsd-hardware.info/?probe=5684672f5a) | Aug 26, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [a760a87c5d](https://bsd-hardware.info/?probe=a760a87c5d) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [0466d87f04](https://bsd-hardware.info/?probe=0466d87f04) | Aug 25, 2022 |
| HP            | ENVY Notebook               | Notebook    | [7e33273132](https://bsd-hardware.info/?probe=7e33273132) | Aug 25, 2022 |
| ASRock        | AD2550-ITX                  | Desktop     | [43d0101ac4](https://bsd-hardware.info/?probe=43d0101ac4) | Aug 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [fcfa6205d8](https://bsd-hardware.info/?probe=fcfa6205d8) | Aug 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [eec9546431](https://bsd-hardware.info/?probe=eec9546431) | Aug 23, 2022 |
| Lenovo        | ThinkCentre M91p 4512A47    | Desktop     | [3556794570](https://bsd-hardware.info/?probe=3556794570) | Aug 23, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [cc2a81fc1b](https://bsd-hardware.info/?probe=cc2a81fc1b) | Aug 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [6184507a45](https://bsd-hardware.info/?probe=6184507a45) | Aug 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [89535fc84c](https://bsd-hardware.info/?probe=89535fc84c) | Aug 21, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [ac2d88c2dd](https://bsd-hardware.info/?probe=ac2d88c2dd) | Aug 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b5786b8119](https://bsd-hardware.info/?probe=b5786b8119) | Aug 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c146b538e1](https://bsd-hardware.info/?probe=c146b538e1) | Aug 20, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [560213a2d6](https://bsd-hardware.info/?probe=560213a2d6) | Aug 19, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [ce0d33d973](https://bsd-hardware.info/?probe=ce0d33d973) | Aug 19, 2022 |
| ASUSTek       | ZenBook 14 UX410UFR         | Notebook    | [2bf0f0ef08](https://bsd-hardware.info/?probe=2bf0f0ef08) | Aug 19, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [a2fc8d9c67](https://bsd-hardware.info/?probe=a2fc8d9c67) | Aug 18, 2022 |
| Dell          | 0VG93V A00                  | Desktop     | [8de9fa2319](https://bsd-hardware.info/?probe=8de9fa2319) | Aug 18, 2022 |
| Google        | Peppy                       | Notebook    | [e2e0a1953d](https://bsd-hardware.info/?probe=e2e0a1953d) | Aug 18, 2022 |
| Intel         | S2600WTTR G92187-372        | Server      | [ce1988c8ff](https://bsd-hardware.info/?probe=ce1988c8ff) | Aug 18, 2022 |
| Fujitsu       | D3373-B1 S26361-D3373-B1... | Server      | [676fd4e9b4](https://bsd-hardware.info/?probe=676fd4e9b4) | Aug 17, 2022 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [c03da8657e](https://bsd-hardware.info/?probe=c03da8657e) | Aug 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [3208aefb72](https://bsd-hardware.info/?probe=3208aefb72) | Aug 17, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [7130975fe3](https://bsd-hardware.info/?probe=7130975fe3) | Aug 17, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9a7d45e51c](https://bsd-hardware.info/?probe=9a7d45e51c) | Aug 16, 2022 |
| Acer          | Aspire 4552G                | Notebook    | [a8f8e41c91](https://bsd-hardware.info/?probe=a8f8e41c91) | Aug 14, 2022 |
| Sony          | VGN-UX1XRN                  | Notebook    | [312df080a7](https://bsd-hardware.info/?probe=312df080a7) | Aug 14, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [dacea7c6be](https://bsd-hardware.info/?probe=dacea7c6be) | Aug 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [4055810ef2](https://bsd-hardware.info/?probe=4055810ef2) | Aug 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2da32e59b0](https://bsd-hardware.info/?probe=2da32e59b0) | Aug 14, 2022 |
| MSI           | H81M-P33                    | Desktop     | [3d0836d403](https://bsd-hardware.info/?probe=3d0836d403) | Aug 14, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [c50be0ecae](https://bsd-hardware.info/?probe=c50be0ecae) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4b6ad32189](https://bsd-hardware.info/?probe=4b6ad32189) | Aug 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5d4af4fba9](https://bsd-hardware.info/?probe=5d4af4fba9) | Aug 13, 2022 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [3d46e0eace](https://bsd-hardware.info/?probe=3d46e0eace) | Aug 13, 2022 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [c961cea235](https://bsd-hardware.info/?probe=c961cea235) | Aug 13, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [6884e940a1](https://bsd-hardware.info/?probe=6884e940a1) | Aug 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1292c617d2](https://bsd-hardware.info/?probe=1292c617d2) | Aug 13, 2022 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [5ceace59c1](https://bsd-hardware.info/?probe=5ceace59c1) | Aug 12, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [0c654b6c34](https://bsd-hardware.info/?probe=0c654b6c34) | Aug 11, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | Notebook    | [45e44ad953](https://bsd-hardware.info/?probe=45e44ad953) | Aug 10, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [efd9ee1d33](https://bsd-hardware.info/?probe=efd9ee1d33) | Aug 10, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [a38375fa97](https://bsd-hardware.info/?probe=a38375fa97) | Aug 08, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [81a5e313cd](https://bsd-hardware.info/?probe=81a5e313cd) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [467bcd3c04](https://bsd-hardware.info/?probe=467bcd3c04) | Aug 07, 2022 |
| GVC           | DR 738                      | Desktop     | [ea08102a81](https://bsd-hardware.info/?probe=ea08102a81) | Aug 06, 2022 |
| Gigabyte      | H97M-HD3                    | Desktop     | [4a7705414f](https://bsd-hardware.info/?probe=4a7705414f) | Aug 06, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5b88dea745](https://bsd-hardware.info/?probe=5b88dea745) | Aug 06, 2022 |
| Dell          | Inspiron 3581               | Notebook    | [f31cc32515](https://bsd-hardware.info/?probe=f31cc32515) | Aug 04, 2022 |
| Gigabyte      | P85-D3                      | Desktop     | [7f077abed9](https://bsd-hardware.info/?probe=7f077abed9) | Aug 02, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [b29e940a75](https://bsd-hardware.info/?probe=b29e940a75) | Aug 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [d5e9213bb5](https://bsd-hardware.info/?probe=d5e9213bb5) | Aug 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [f603e648c7](https://bsd-hardware.info/?probe=f603e648c7) | Aug 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | Notebook    | [546fa8380b](https://bsd-hardware.info/?probe=546fa8380b) | Aug 01, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [13baedb59b](https://bsd-hardware.info/?probe=13baedb59b) | Jul 31, 2022 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [3c33e546bb](https://bsd-hardware.info/?probe=3c33e546bb) | Jul 31, 2022 |
| Gigabyte      | GB-BSi3-1115G4              | Desktop     | [4cd0769d75](https://bsd-hardware.info/?probe=4cd0769d75) | Jul 30, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [bd2f6f8596](https://bsd-hardware.info/?probe=bd2f6f8596) | Jul 29, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [5d4d3d7553](https://bsd-hardware.info/?probe=5d4d3d7553) | Jul 29, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| HP            | 1825                        | Desktop     | [8c96329681](https://bsd-hardware.info/?probe=8c96329681) | Jul 24, 2022 |
| Dell          | Precision 5560              | Notebook    | [3dc82c6d91](https://bsd-hardware.info/?probe=3dc82c6d91) | Jul 23, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [6e31b5f45b](https://bsd-hardware.info/?probe=6e31b5f45b) | Jul 23, 2022 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [6cdc79a36f](https://bsd-hardware.info/?probe=6cdc79a36f) | Jul 22, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [051f604f9a](https://bsd-hardware.info/?probe=051f604f9a) | Jul 21, 2022 |
| Dell          | Studio XPS 1340             | Notebook    | [642da98e96](https://bsd-hardware.info/?probe=642da98e96) | Jul 21, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [3ba3cedec4](https://bsd-hardware.info/?probe=3ba3cedec4) | Jul 21, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [46a6f4e8f3](https://bsd-hardware.info/?probe=46a6f4e8f3) | Jul 19, 2022 |
| Dell          | 08HPGT A02                  | Desktop     | [ae260e17eb](https://bsd-hardware.info/?probe=ae260e17eb) | Jul 19, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [9af051c79f](https://bsd-hardware.info/?probe=9af051c79f) | Jul 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [3bf44f4bb5](https://bsd-hardware.info/?probe=3bf44f4bb5) | Jul 17, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | Notebook    | [6c5c9eefc0](https://bsd-hardware.info/?probe=6c5c9eefc0) | Jul 17, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [b11ca9c369](https://bsd-hardware.info/?probe=b11ca9c369) | Jul 16, 2022 |
| Sony          | VGN-NS21M_S                 | Notebook    | [c78caf8215](https://bsd-hardware.info/?probe=c78caf8215) | Jul 16, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [978f01c546](https://bsd-hardware.info/?probe=978f01c546) | Jul 16, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | Notebook    | [4067ce2036](https://bsd-hardware.info/?probe=4067ce2036) | Jul 16, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [fe84e9fda5](https://bsd-hardware.info/?probe=fe84e9fda5) | Jul 15, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [070ccc68f8](https://bsd-hardware.info/?probe=070ccc68f8) | Jul 15, 2022 |
| Acer          | Veriton X490G               | Desktop     | [2912c74632](https://bsd-hardware.info/?probe=2912c74632) | Jul 15, 2022 |
| Lenovo        | ThinkPad X260 20F6S0KA00    | Notebook    | [117014d55f](https://bsd-hardware.info/?probe=117014d55f) | Jul 14, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [607a66e533](https://bsd-hardware.info/?probe=607a66e533) | Jul 14, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | Notebook    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| MouseCompu... | B360M                       | Desktop     | [3c22f3e91b](https://bsd-hardware.info/?probe=3c22f3e91b) | Jul 13, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [894b6f82cf](https://bsd-hardware.info/?probe=894b6f82cf) | Jul 13, 2022 |
| Toshiba       | Satellite L305D             | Notebook    | [b0311b8175](https://bsd-hardware.info/?probe=b0311b8175) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [7081ddd59c](https://bsd-hardware.info/?probe=7081ddd59c) | Jul 11, 2022 |
| Acer          | Veriton X490G               | Desktop     | [cbae2b155b](https://bsd-hardware.info/?probe=cbae2b155b) | Jul 11, 2022 |
| Acer          | Veriton X490G               | Desktop     | [3cd79878cd](https://bsd-hardware.info/?probe=3cd79878cd) | Jul 11, 2022 |
| ASRock        | B75 Pro3                    | Desktop     | [7f4fa7f74d](https://bsd-hardware.info/?probe=7f4fa7f74d) | Jul 10, 2022 |
| Toshiba       | Satellite L305D             | Notebook    | [ed950787b0](https://bsd-hardware.info/?probe=ed950787b0) | Jul 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [947d413e10](https://bsd-hardware.info/?probe=947d413e10) | Jul 09, 2022 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [8a9a8cdbd0](https://bsd-hardware.info/?probe=8a9a8cdbd0) | Jul 08, 2022 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [2d521e085b](https://bsd-hardware.info/?probe=2d521e085b) | Jul 08, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [ba96a05e5c](https://bsd-hardware.info/?probe=ba96a05e5c) | Jul 08, 2022 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [0819ecdcf9](https://bsd-hardware.info/?probe=0819ecdcf9) | Jul 07, 2022 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [d459d3431a](https://bsd-hardware.info/?probe=d459d3431a) | Jul 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [66543e9280](https://bsd-hardware.info/?probe=66543e9280) | Jul 07, 2022 |
| Dell          | Latitude E6420              | Notebook    | [c41c8ff4f4](https://bsd-hardware.info/?probe=c41c8ff4f4) | Jul 07, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [7c34be7c2e](https://bsd-hardware.info/?probe=7c34be7c2e) | Jul 06, 2022 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [d9fd7e54cf](https://bsd-hardware.info/?probe=d9fd7e54cf) | Jul 06, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [dbbe9124a2](https://bsd-hardware.info/?probe=dbbe9124a2) | Jul 05, 2022 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [d67aa61a6b](https://bsd-hardware.info/?probe=d67aa61a6b) | Jul 05, 2022 |
| Acer          | Revo RN86                   | Desktop     | [2dc98202aa](https://bsd-hardware.info/?probe=2dc98202aa) | Jul 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [584ecf8423](https://bsd-hardware.info/?probe=584ecf8423) | Jul 05, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [b697848727](https://bsd-hardware.info/?probe=b697848727) | Jul 05, 2022 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [886522d5e6](https://bsd-hardware.info/?probe=886522d5e6) | Jul 04, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [81e9f8506f](https://bsd-hardware.info/?probe=81e9f8506f) | Jul 04, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [d82547b583](https://bsd-hardware.info/?probe=d82547b583) | Jul 04, 2022 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [a3cba2571b](https://bsd-hardware.info/?probe=a3cba2571b) | Jul 04, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [b57457834e](https://bsd-hardware.info/?probe=b57457834e) | Jul 04, 2022 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [1d3db5e35a](https://bsd-hardware.info/?probe=1d3db5e35a) | Jul 04, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | Notebook    | [5777cb6dc6](https://bsd-hardware.info/?probe=5777cb6dc6) | Jul 01, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [a76b64487b](https://bsd-hardware.info/?probe=a76b64487b) | Jul 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| ASRock        | P67 Professional            | Desktop     | [3372d35113](https://bsd-hardware.info/?probe=3372d35113) | Jun 28, 2022 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [898da0bcec](https://bsd-hardware.info/?probe=898da0bcec) | Jun 28, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| MSI           | MS-B120                     | Mini pc     | [aa27c1dfd0](https://bsd-hardware.info/?probe=aa27c1dfd0) | Jun 25, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [70aea59a1b](https://bsd-hardware.info/?probe=70aea59a1b) | Jun 25, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [c285cb7899](https://bsd-hardware.info/?probe=c285cb7899) | Jun 23, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7d054ce34f](https://bsd-hardware.info/?probe=7d054ce34f) | Jun 23, 2022 |
| MSI           | B85M-E45                    | Desktop     | [d9cc6cee6b](https://bsd-hardware.info/?probe=d9cc6cee6b) | Jun 21, 2022 |
| Lenovo        | ThinkPad X270 20HN001HUS    | Notebook    | [139e4817d7](https://bsd-hardware.info/?probe=139e4817d7) | Jun 21, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [ee4d6d5761](https://bsd-hardware.info/?probe=ee4d6d5761) | Jun 21, 2022 |
| Intel         | D945GCLF2 AAE46416-104      | Desktop     | [84f2afeff4](https://bsd-hardware.info/?probe=84f2afeff4) | Jun 21, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | Notebook    | [8ad937beaa](https://bsd-hardware.info/?probe=8ad937beaa) | Jun 21, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [5e51d228ec](https://bsd-hardware.info/?probe=5e51d228ec) | Jun 21, 2022 |
| HP            | 3031h                       | Desktop     | [96ecd77f94](https://bsd-hardware.info/?probe=96ecd77f94) | Jun 19, 2022 |
| HP            | 3031h                       | Desktop     | [4da4d936b8](https://bsd-hardware.info/?probe=4da4d936b8) | Jun 19, 2022 |
| Dell          | Latitude 5521               | Notebook    | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [6d4bc39638](https://bsd-hardware.info/?probe=6d4bc39638) | Jun 18, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [e057898546](https://bsd-hardware.info/?probe=e057898546) | Jun 18, 2022 |
| Sony          | VGN-NS21M_S                 | Notebook    | [c9701a7ff5](https://bsd-hardware.info/?probe=c9701a7ff5) | Jun 18, 2022 |
| Intel         | NUC7i5BNB J31144-306        | Mini pc     | [66f9b621be](https://bsd-hardware.info/?probe=66f9b621be) | Jun 17, 2022 |
| HP            | 86E9 A                      | Desktop     | [1d1ac2dd90](https://bsd-hardware.info/?probe=1d1ac2dd90) | Jun 16, 2022 |
| Dell          | 07KY25 A00                  | Desktop     | [9981217b1b](https://bsd-hardware.info/?probe=9981217b1b) | Jun 16, 2022 |
| ASUSTek       | ZenBook UX461FA_UX461FA     | Convertible | [3079ca74a6](https://bsd-hardware.info/?probe=3079ca74a6) | Jun 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [b699c2a617](https://bsd-hardware.info/?probe=b699c2a617) | Jun 15, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [45083c3a78](https://bsd-hardware.info/?probe=45083c3a78) | Jun 15, 2022 |
| Dell          | Latitude E5420              | Notebook    | [524ab094e1](https://bsd-hardware.info/?probe=524ab094e1) | Jun 13, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [8825a49f37](https://bsd-hardware.info/?probe=8825a49f37) | Jun 13, 2022 |
| Dell          | 0HMF7C A01                  | Desktop     | [ad0f6d4b31](https://bsd-hardware.info/?probe=ad0f6d4b31) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [1febab0774](https://bsd-hardware.info/?probe=1febab0774) | Jun 12, 2022 |
| Dell          | Latitude 7390               | Notebook    | [2b888ed291](https://bsd-hardware.info/?probe=2b888ed291) | Jun 12, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [380218b2c1](https://bsd-hardware.info/?probe=380218b2c1) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [387bf3d18f](https://bsd-hardware.info/?probe=387bf3d18f) | Jun 12, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [d81151c0e8](https://bsd-hardware.info/?probe=d81151c0e8) | Jun 12, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [5215d1ebb8](https://bsd-hardware.info/?probe=5215d1ebb8) | Jun 12, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [af923daeda](https://bsd-hardware.info/?probe=af923daeda) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [edebcb2719](https://bsd-hardware.info/?probe=edebcb2719) | Jun 12, 2022 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [23d96bc669](https://bsd-hardware.info/?probe=23d96bc669) | Jun 11, 2022 |
| Dell          | 0804P1 A04                  | Server      | [c8ddb7dae6](https://bsd-hardware.info/?probe=c8ddb7dae6) | Jun 10, 2022 |
| Dell          | Latitude E5420              | Notebook    | [aca711c5ec](https://bsd-hardware.info/?probe=aca711c5ec) | Jun 09, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [9f33082ffa](https://bsd-hardware.info/?probe=9f33082ffa) | Jun 08, 2022 |
| Dell          | Precision M4800             | Notebook    | [4d77bb0082](https://bsd-hardware.info/?probe=4d77bb0082) | Jun 08, 2022 |
| Dell          | Latitude E5420              | Notebook    | [a3a9820968](https://bsd-hardware.info/?probe=a3a9820968) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| Dell          | Latitude 5410               | Notebook    | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| MSI           | Z590 PRO WIFI               | Desktop     | [29b410eeb6](https://bsd-hardware.info/?probe=29b410eeb6) | Jun 06, 2022 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [ae3436167b](https://bsd-hardware.info/?probe=ae3436167b) | Jun 05, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [ff3865e01f](https://bsd-hardware.info/?probe=ff3865e01f) | Jun 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Lenovo        | Aptio CRB SDK0E50515 STD    | Mini pc     | [260ae5b2fe](https://bsd-hardware.info/?probe=260ae5b2fe) | Jun 04, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [f3ad761457](https://bsd-hardware.info/?probe=f3ad761457) | Jun 04, 2022 |
| Dell          | Latitude E5500              | Notebook    | [b1cb5de914](https://bsd-hardware.info/?probe=b1cb5de914) | Jun 03, 2022 |
| ASUSTek       | X441UV                      | Notebook    | [c8906b438b](https://bsd-hardware.info/?probe=c8906b438b) | Jun 03, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [1067f6ab27](https://bsd-hardware.info/?probe=1067f6ab27) | Jun 03, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [29f1ef0cdc](https://bsd-hardware.info/?probe=29f1ef0cdc) | Jun 02, 2022 |
| Lenovo        | ThinkPad W520 4282AD4       | Notebook    | [40198abaa2](https://bsd-hardware.info/?probe=40198abaa2) | Jun 02, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [0cf6981a98](https://bsd-hardware.info/?probe=0cf6981a98) | Jun 02, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [1cc3d99da5](https://bsd-hardware.info/?probe=1cc3d99da5) | May 31, 2022 |
| GPD           | MicroPC                     | Notebook    | [a448570ff9](https://bsd-hardware.info/?probe=a448570ff9) | May 31, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [283a074737](https://bsd-hardware.info/?probe=283a074737) | May 31, 2022 |
| Acer          | Aspire E5-576               | Notebook    | [138e9fdeb4](https://bsd-hardware.info/?probe=138e9fdeb4) | May 31, 2022 |
| GPD           | MicroPC                     | Notebook    | [0046ab7c9b](https://bsd-hardware.info/?probe=0046ab7c9b) | May 31, 2022 |
| NF-M2S        | ABIT                        | Desktop     | [bef9700756](https://bsd-hardware.info/?probe=bef9700756) | May 31, 2022 |
| HP            | Pavilion g6                 | Notebook    | [32854b73a5](https://bsd-hardware.info/?probe=32854b73a5) | May 30, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f39611345a](https://bsd-hardware.info/?probe=f39611345a) | May 30, 2022 |
| System76      | Galago Pro                  | Notebook    | [126ebc1522](https://bsd-hardware.info/?probe=126ebc1522) | May 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [90b27f0ac1](https://bsd-hardware.info/?probe=90b27f0ac1) | May 29, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [cf67e4079f](https://bsd-hardware.info/?probe=cf67e4079f) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8ebd281f5f](https://bsd-hardware.info/?probe=8ebd281f5f) | May 29, 2022 |
| MSI           | H81M-P33                    | Desktop     | [ab2181e1b4](https://bsd-hardware.info/?probe=ab2181e1b4) | May 29, 2022 |
| Dell          | G5 5590                     | Notebook    | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| Dell          | Latitude E6430              | Notebook    | [d7ced37bac](https://bsd-hardware.info/?probe=d7ced37bac) | May 29, 2022 |
| PC Engines    | APU3                        | Desktop     | [fca5a642c2](https://bsd-hardware.info/?probe=fca5a642c2) | May 28, 2022 |
| Lenovo        | ThinkPad X250 20CMS0FA00    | Notebook    | [5afeac632d](https://bsd-hardware.info/?probe=5afeac632d) | May 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [a56bc64f26](https://bsd-hardware.info/?probe=a56bc64f26) | May 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e15ce78c8](https://bsd-hardware.info/?probe=4e15ce78c8) | May 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [3ff577e111](https://bsd-hardware.info/?probe=3ff577e111) | May 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [9e2f16664a](https://bsd-hardware.info/?probe=9e2f16664a) | May 26, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [cddd786b51](https://bsd-hardware.info/?probe=cddd786b51) | May 26, 2022 |
| HP            | 158A                        | Desktop     | [883958cd36](https://bsd-hardware.info/?probe=883958cd36) | May 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [78d1ad4565](https://bsd-hardware.info/?probe=78d1ad4565) | May 25, 2022 |
| Notebook      | N7x0WU                      | Notebook    | [37242aa9a3](https://bsd-hardware.info/?probe=37242aa9a3) | May 25, 2022 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [d35f1fb7e0](https://bsd-hardware.info/?probe=d35f1fb7e0) | May 25, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [1cc5f44e4a](https://bsd-hardware.info/?probe=1cc5f44e4a) | May 25, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [c41aea0ea7](https://bsd-hardware.info/?probe=c41aea0ea7) | May 24, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [3dc5a6f7d2](https://bsd-hardware.info/?probe=3dc5a6f7d2) | May 24, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [727f9708b4](https://bsd-hardware.info/?probe=727f9708b4) | May 24, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [cc1c76afc0](https://bsd-hardware.info/?probe=cc1c76afc0) | May 24, 2022 |
| Dell          | Latitude E6540              | Notebook    | [70871cf070](https://bsd-hardware.info/?probe=70871cf070) | May 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a74913bffa](https://bsd-hardware.info/?probe=a74913bffa) | May 23, 2022 |
| khadas        | edge-v                      | Desktop     | [60fb48e34c](https://bsd-hardware.info/?probe=60fb48e34c) | May 23, 2022 |
| khadas        | edge-v                      | Desktop     | [6facaa8032](https://bsd-hardware.info/?probe=6facaa8032) | May 22, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [443b1d3c3e](https://bsd-hardware.info/?probe=443b1d3c3e) | May 22, 2022 |
| Dell          | Precision M4800             | Notebook    | [6a703b66f8](https://bsd-hardware.info/?probe=6a703b66f8) | May 22, 2022 |
| Dell          | Latitude E7240              | Notebook    | [970234b430](https://bsd-hardware.info/?probe=970234b430) | May 22, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d5a0fd71f2](https://bsd-hardware.info/?probe=d5a0fd71f2) | May 22, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [2b93a0b59f](https://bsd-hardware.info/?probe=2b93a0b59f) | May 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [becc2fddbd](https://bsd-hardware.info/?probe=becc2fddbd) | May 22, 2022 |
| Intel         | NUC9i7QNB K49245-402        | Mini pc     | [92881489e1](https://bsd-hardware.info/?probe=92881489e1) | May 22, 2022 |
| Supermicro    | X9SRW-F                     | Server      | [89da730497](https://bsd-hardware.info/?probe=89da730497) | May 21, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [ddaca5356c](https://bsd-hardware.info/?probe=ddaca5356c) | May 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| GVC           | DR 738                      | Desktop     | [938866fb80](https://bsd-hardware.info/?probe=938866fb80) | May 21, 2022 |
| Dell          | Latitude 5520               | Notebook    | [cbc2c03fa1](https://bsd-hardware.info/?probe=cbc2c03fa1) | May 20, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [44abecc1ef](https://bsd-hardware.info/?probe=44abecc1ef) | May 20, 2022 |
| ASUSTek       | 1001P                       | Notebook    | [6ffa9529a3](https://bsd-hardware.info/?probe=6ffa9529a3) | May 20, 2022 |
| ASUSTek       | 1001P                       | Notebook    | [2820584223](https://bsd-hardware.info/?probe=2820584223) | May 20, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [819bed6cfb](https://bsd-hardware.info/?probe=819bed6cfb) | May 19, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| Lenovo        | MAHOBAY 31900004 STD        | All in one  | [a9189728e3](https://bsd-hardware.info/?probe=a9189728e3) | May 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [1c84f0f722](https://bsd-hardware.info/?probe=1c84f0f722) | May 19, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [b0ea5e7a5e](https://bsd-hardware.info/?probe=b0ea5e7a5e) | May 19, 2022 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [f369e09063](https://bsd-hardware.info/?probe=f369e09063) | May 19, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [9c459aae41](https://bsd-hardware.info/?probe=9c459aae41) | May 19, 2022 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [d5a6eba10b](https://bsd-hardware.info/?probe=d5a6eba10b) | May 19, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [1014f7f61c](https://bsd-hardware.info/?probe=1014f7f61c) | May 18, 2022 |
| Dell          | 0DXJD9 A01                  | Desktop     | [be13c9069c](https://bsd-hardware.info/?probe=be13c9069c) | May 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [edcd612c83](https://bsd-hardware.info/?probe=edcd612c83) | May 18, 2022 |
| Lenovo        | ThinkPad L420 7854CTO       | Notebook    | [56cf502c2f](https://bsd-hardware.info/?probe=56cf502c2f) | May 18, 2022 |
| Lenovo        | ThinkPad T420s 41732AU      | Notebook    | [9d9ddcc409](https://bsd-hardware.info/?probe=9d9ddcc409) | May 18, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | Notebook    | [2d3de77101](https://bsd-hardware.info/?probe=2d3de77101) | May 18, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [86866ce217](https://bsd-hardware.info/?probe=86866ce217) | May 17, 2022 |
| Dell          | 04JN2K A12                  | Server      | [550e12f317](https://bsd-hardware.info/?probe=550e12f317) | May 17, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [311c32e56e](https://bsd-hardware.info/?probe=311c32e56e) | May 17, 2022 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [7189b48418](https://bsd-hardware.info/?probe=7189b48418) | May 17, 2022 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [fd081a3636](https://bsd-hardware.info/?probe=fd081a3636) | May 17, 2022 |
| Dell          | 07T4MC A11                  | Desktop     | [63d6080a31](https://bsd-hardware.info/?probe=63d6080a31) | May 17, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [b87692aeb4](https://bsd-hardware.info/?probe=b87692aeb4) | May 15, 2022 |
| Dell          | Precision M4800             | Notebook    | [6dc325b553](https://bsd-hardware.info/?probe=6dc325b553) | May 15, 2022 |
| ASRock        | E350M1                      | Desktop     | [1850fa38e0](https://bsd-hardware.info/?probe=1850fa38e0) | May 14, 2022 |
| ASRock        | E350M1                      | Desktop     | [4520b5034e](https://bsd-hardware.info/?probe=4520b5034e) | May 13, 2022 |
| MSI           | MS-7369                     | Desktop     | [c2c6bd80e8](https://bsd-hardware.info/?probe=c2c6bd80e8) | May 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [f3ab857e43](https://bsd-hardware.info/?probe=f3ab857e43) | May 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6a9177eef7](https://bsd-hardware.info/?probe=6a9177eef7) | May 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [11034dd80f](https://bsd-hardware.info/?probe=11034dd80f) | May 13, 2022 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [e8d2744812](https://bsd-hardware.info/?probe=e8d2744812) | May 12, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [3a3729e497](https://bsd-hardware.info/?probe=3a3729e497) | May 12, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [46b11e5051](https://bsd-hardware.info/?probe=46b11e5051) | May 12, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [e569bffe8f](https://bsd-hardware.info/?probe=e569bffe8f) | May 12, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [54a5041cdf](https://bsd-hardware.info/?probe=54a5041cdf) | May 12, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [991f67362f](https://bsd-hardware.info/?probe=991f67362f) | May 12, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [8cdb309c2e](https://bsd-hardware.info/?probe=8cdb309c2e) | May 11, 2022 |
| ASRock        | A320M Pro4-F                | Desktop     | [f307756ddf](https://bsd-hardware.info/?probe=f307756ddf) | May 11, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [224614e9ab](https://bsd-hardware.info/?probe=224614e9ab) | May 10, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [76eef59920](https://bsd-hardware.info/?probe=76eef59920) | May 10, 2022 |
| Dell          | Latitude 2100               | Notebook    | [40406069ee](https://bsd-hardware.info/?probe=40406069ee) | May 09, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [5259bc1933](https://bsd-hardware.info/?probe=5259bc1933) | May 08, 2022 |
| Lenovo        | ThinkPad X250 20CLS02V00    | Notebook    | [7e2771b8f6](https://bsd-hardware.info/?probe=7e2771b8f6) | May 08, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [a69f0fefca](https://bsd-hardware.info/?probe=a69f0fefca) | May 07, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [331947afe1](https://bsd-hardware.info/?probe=331947afe1) | May 07, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [850df51257](https://bsd-hardware.info/?probe=850df51257) | May 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [659e98fd68](https://bsd-hardware.info/?probe=659e98fd68) | May 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [015bf0fea4](https://bsd-hardware.info/?probe=015bf0fea4) | May 06, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | Notebook    | [e99738632d](https://bsd-hardware.info/?probe=e99738632d) | May 06, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [407fc42fad](https://bsd-hardware.info/?probe=407fc42fad) | May 05, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [5f9e266167](https://bsd-hardware.info/?probe=5f9e266167) | May 04, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [7d4dd8ba29](https://bsd-hardware.info/?probe=7d4dd8ba29) | May 04, 2022 |
| Dell          | Vostro 5590                 | Notebook    | [1f23973fb4](https://bsd-hardware.info/?probe=1f23973fb4) | May 04, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [86ea07c719](https://bsd-hardware.info/?probe=86ea07c719) | May 03, 2022 |
| Acer          | Aspire ES1-132              | Notebook    | [18426698ad](https://bsd-hardware.info/?probe=18426698ad) | May 02, 2022 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [1fde9daf7d](https://bsd-hardware.info/?probe=1fde9daf7d) | May 01, 2022 |
| Dell          | Latitude E5570              | Notebook    | [c214ce4ab0](https://bsd-hardware.info/?probe=c214ce4ab0) | May 01, 2022 |
| Toshiba       | Satellite P25               | Notebook    | [6a920e9c8a](https://bsd-hardware.info/?probe=6a920e9c8a) | May 01, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [5701dac149](https://bsd-hardware.info/?probe=5701dac149) | Apr 30, 2022 |
| HP            | 8158 A01                    | Mini pc     | [de45e5a021](https://bsd-hardware.info/?probe=de45e5a021) | Apr 29, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [7a212b5833](https://bsd-hardware.info/?probe=7a212b5833) | Apr 29, 2022 |
| HP            | 1495                        | Desktop     | [6e0f1cc72e](https://bsd-hardware.info/?probe=6e0f1cc72e) | Apr 29, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [336add4fcb](https://bsd-hardware.info/?probe=336add4fcb) | Apr 28, 2022 |
| Lenovo        | ThinkPad T470 20HES0ES1F    | Notebook    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [34f2ba40e7](https://bsd-hardware.info/?probe=34f2ba40e7) | Apr 27, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [0750e29d3c](https://bsd-hardware.info/?probe=0750e29d3c) | Apr 27, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [30e267dd51](https://bsd-hardware.info/?probe=30e267dd51) | Apr 27, 2022 |
| Notebook      | N7x0WU                      | Notebook    | [b7c06932a3](https://bsd-hardware.info/?probe=b7c06932a3) | Apr 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [1a475f0939](https://bsd-hardware.info/?probe=1a475f0939) | Apr 27, 2022 |
| ASRock        | X570S PG Riptide            | Desktop     | [928d2abb5e](https://bsd-hardware.info/?probe=928d2abb5e) | Apr 26, 2022 |
| Framework     | Laptop                      | Notebook    | [5d6cb039ea](https://bsd-hardware.info/?probe=5d6cb039ea) | Apr 25, 2022 |
| Intel         | S3420GP E77063-304          | Server      | [09a475e0bc](https://bsd-hardware.info/?probe=09a475e0bc) | Apr 25, 2022 |
| HP            | ProLiant DL180 G6           | Server      | [3834dccb1f](https://bsd-hardware.info/?probe=3834dccb1f) | Apr 25, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [549053284c](https://bsd-hardware.info/?probe=549053284c) | Apr 25, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [86c4af7ca4](https://bsd-hardware.info/?probe=86c4af7ca4) | Apr 25, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [e588c93d54](https://bsd-hardware.info/?probe=e588c93d54) | Apr 24, 2022 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [fd100bcc6a](https://bsd-hardware.info/?probe=fd100bcc6a) | Apr 24, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [7a43bfada9](https://bsd-hardware.info/?probe=7a43bfada9) | Apr 23, 2022 |
| Dell          | Latitude E6520              | Notebook    | [c4ae703add](https://bsd-hardware.info/?probe=c4ae703add) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [955922ebe2](https://bsd-hardware.info/?probe=955922ebe2) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [4d66b2b328](https://bsd-hardware.info/?probe=4d66b2b328) | Apr 23, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [89fcee49d9](https://bsd-hardware.info/?probe=89fcee49d9) | Apr 22, 2022 |
| HP            | 2820h                       | Desktop     | [d888b8b775](https://bsd-hardware.info/?probe=d888b8b775) | Apr 22, 2022 |
| Lenovo        | B570 1068FQG                | Notebook    | [a0d1f01226](https://bsd-hardware.info/?probe=a0d1f01226) | Apr 22, 2022 |
| Supermicro    | X9SCL/X9SCM                 | Desktop     | [947038b1f9](https://bsd-hardware.info/?probe=947038b1f9) | Apr 22, 2022 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [28c8d07136](https://bsd-hardware.info/?probe=28c8d07136) | Apr 22, 2022 |
| Dell          | 06JWJY A01                  | Desktop     | [16f4cc5d53](https://bsd-hardware.info/?probe=16f4cc5d53) | Apr 20, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [4ad1c07aa5](https://bsd-hardware.info/?probe=4ad1c07aa5) | Apr 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/FreeBSD/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| FreeBSD 13.1         | 229       | 8.75%   |
| FreeBSD 13.0         | 222       | 8.49%   |
| FreeBSD 12.2         | 141       | 5.39%   |
| FreeBSD 14.0-CURRENT | 132       | 5.05%   |
| FreeBSD 12.2-p2      | 96        | 3.67%   |
| FreeBSD 13.0-p4      | 85        | 3.25%   |
| FreeBSD 13.1-p5      | 81        | 3.1%    |
| FreeBSD 12.1-p10     | 79        | 3.02%   |
| FreeBSD 13.0-p5      | 76        | 2.91%   |
| FreeBSD 13.0-STABLE  | 72        | 2.75%   |
| FreeBSD 13.1-p2      | 71        | 2.71%   |
| FreeBSD 12.1-p8      | 69        | 2.64%   |
| FreeBSD 13.0-CURRENT | 66        | 2.52%   |
| FreeBSD 12.1         | 58        | 2.22%   |
| FreeBSD 12.1-p5      | 55        | 2.1%    |
| FreeBSD 12.2-p3      | 52        | 1.99%   |
| FreeBSD 13.1-p7      | 51        | 1.95%   |
| FreeBSD 12.1-STABLE  | 49        | 1.87%   |
| FreeBSD 12.1-p7      | 48        | 1.83%   |
| FreeBSD 13.0-p3      | 47        | 1.8%    |
| FreeBSD 12.2-p4      | 47        | 1.8%    |
| FreeBSD 13.0-p7      | 45        | 1.72%   |
| FreeBSD 13.0-p11     | 37        | 1.41%   |
| FreeBSD 12.2-p6      | 35        | 1.34%   |
| FreeBSD 13.2         | 33        | 1.26%   |
| FreeBSD 13.1-STABLE  | 33        | 1.26%   |
| FreeBSD 13.0-p2      | 33        | 1.26%   |
| FreeBSD 12.2-STABLE  | 32        | 1.22%   |
| FreeBSD 13.1-p1      | 28        | 1.07%   |
| FreeBSD 13.0-p6      | 25        | 0.96%   |
| FreeBSD 12.3         | 23        | 0.88%   |
| FreeBSD 13.0-p10     | 22        | 0.84%   |
| FreeBSD 13.1-p4      | 21        | 0.8%    |
| FreeBSD 12.1-p6      | 21        | 0.8%    |
| FreeBSD 12.2-p10     | 17        | 0.65%   |
| FreeBSD 12.1-p4      | 17        | 0.65%   |
| FreeBSD 13.1-p3      | 16        | 0.61%   |
| FreeBSD 12.3-p5      | 16        | 0.61%   |
| FreeBSD 12.1-p9      | 16        | 0.61%   |
| FreeBSD 12.1-p12     | 12        | 0.46%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| FreeBSD | 2171      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 2008      | 92.45%  |
| arm64   | 76        | 3.5%    |
| i386    | 71        | 3.27%   |
| arm     | 11        | 0.51%   |
| powerpc | 4         | 0.18%   |
| sparc64 | 1         | 0.05%   |
| riscv   | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 752       | 33.35%  |
| XFCE          | 373       | 16.54%  |
| KDE5          | 358       | 15.88%  |
| TWM           | 158       | 7.01%   |
| GNOME         | 149       | 6.61%   |
| MATE          | 124       | 5.5%    |
| i3            | 98        | 4.35%   |
| Openbox       | 58        | 2.57%   |
| Cinnamon      | 26        | 1.15%   |
| AwesomeWM     | 25        | 1.11%   |
| LXQt          | 22        | 0.98%   |
| Fluxbox       | 19        | 0.84%   |
| Enlightenment | 17        | 0.75%   |
| LXDE          | 15        | 0.67%   |
| Lumina        | 11        | 0.49%   |
| DWM           | 8         | 0.35%   |
| GNUstep       | 5         | 0.22%   |
| xfwm          | 4         | 0.18%   |
| CDE           | 4         | 0.18%   |
| X-Cinnamon    | 3         | 0.13%   |
| spectrwm      | 3         | 0.13%   |
| Picom         | 3         | 0.13%   |
| IceWM         | 3         | 0.13%   |
| Window Maker  | 2         | 0.09%   |
| helloDesktop  | 2         | 0.09%   |
| Compton       | 2         | 0.09%   |
| xinitrc       | 1         | 0.04%   |
| Xfwm4         | 1         | 0.04%   |
| sway          | 1         | 0.04%   |
| StumpWM       | 1         | 0.04%   |
| plasma        | 1         | 0.04%   |
| KWin          | 1         | 0.04%   |
| KDE           | 1         | 0.04%   |
| ctwm          | 1         | 0.04%   |
| bspwm         | 1         | 0.04%   |
| awesome       | 1         | 0.04%   |
| akonadi_newm  | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1358      | 61.5%   |
| Console | 808       | 36.59%  |
| Wayland | 41        | 1.86%   |
| Tty     | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1250      | 55.83%  |
| SDDM    | 344       | 15.36%  |
| SLiM    | 241       | 10.76%  |
| XDM     | 150       | 6.7%    |
| LightDM | 132       | 5.9%    |
| GDM     | 100       | 4.47%   |
| Ly      | 19        | 0.85%   |
| PCDM    | 2         | 0.09%   |
| WDM     | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 899       | 39.4%   |
| Unknown          | 636       | 27.87%  |
| en_US            | 323       | 14.15%  |
| ru_RU            | 126       | 5.52%   |
| de_DE            | 45        | 1.97%   |
| fr_FR            | 38        | 1.67%   |
| en_GB            | 33        | 1.45%   |
| zh_CN            | 16        | 0.7%    |
| en_CA            | 15        | 0.66%   |
| pt_BR            | 11        | 0.48%   |
| uk_UA            | 9         | 0.39%   |
| ja_JP            | 9         | 0.39%   |
| es_ES            | 9         | 0.39%   |
| pl_PL            | 8         | 0.35%   |
| en_AU            | 8         | 0.35%   |
| nb_NO            | 7         | 0.31%   |
| it_IT            | 6         | 0.26%   |
| en_IE            | 6         | 0.26%   |
| ru_RU.KOI8-R     | 4         | 0.18%   |
| en_US.ISO8859-1  | 4         | 0.18%   |
| en_NZ            | 4         | 0.18%   |
| el_GR            | 4         | 0.18%   |
| cs_CZ            | 4         | 0.18%   |
| fi_FI            | 3         | 0.13%   |
| es_AR            | 3         | 0.13%   |
| en_US.US-ASCII   | 3         | 0.13%   |
| de_DE.ISO8859-1  | 3         | 0.13%   |
| de_CH            | 3         | 0.13%   |
| zh_TW            | 2         | 0.09%   |
| sv_SE            | 2         | 0.09%   |
| pt_PT            | 2         | 0.09%   |
| nl_NL            | 2         | 0.09%   |
| it_IT.ISO8859-15 | 2         | 0.09%   |
| en_SG            | 2         | 0.09%   |
| en_GB.US-ASCII   | 2         | 0.09%   |
| en_GB.ISO8859-1  | 2         | 0.09%   |
| zh_CN.GB2312     | 1         | 0.04%   |
| sv_SE.US-ASCII   | 1         | 0.04%   |
| sl_SI            | 1         | 0.04%   |
| POSIX            | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1363      | 62.18%  |
| BIOS | 829       | 37.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 1389      | 63.31%  |
| Ufs     | 799       | 36.42%  |
| Nfs     | 2         | 0.09%   |
| Cd9660  | 2         | 0.09%   |
| Xfs     | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1922      | 88.04%  |
| MBR     | 243       | 11.13%  |
| BSD     | 10        | 0.46%   |
| Unknown | 8         | 0.37%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 358       | 16.49%  |
| Dell                    | 310       | 14.28%  |
| ASUSTek Computer        | 281       | 12.94%  |
| Hewlett-Packard         | 193       | 8.89%   |
| Gigabyte Technology     | 124       | 5.71%   |
| ASRock                  | 99        | 4.56%   |
| Unknown                 | 89        | 4.1%    |
| MSI                     | 88        | 4.05%   |
| Supermicro              | 81        | 3.73%   |
| Intel                   | 81        | 3.73%   |
| Acer                    | 63        | 2.9%    |
| Apple                   | 42        | 1.93%   |
| Fujitsu                 | 28        | 1.29%   |
| Toshiba                 | 21        | 0.97%   |
| Raspberry Pi Foundation | 18        | 0.83%   |
| IBM                     | 18        | 0.83%   |
| Samsung Electronics     | 16        | 0.74%   |
| PC Engines              | 14        | 0.64%   |
| ASRockRack              | 14        | 0.64%   |
| System76                | 13        | 0.6%    |
| HUAWEI                  | 12        | 0.55%   |
| Google                  | 12        | 0.55%   |
| Sony                    | 9         | 0.41%   |
| TUXEDO                  | 8         | 0.37%   |
| Shuttle                 | 7         | 0.32%   |
| HPE                     | 7         | 0.32%   |
| Sun Microsystems        | 6         | 0.28%   |
| AMI                     | 6         | 0.28%   |
| Panasonic               | 5         | 0.23%   |
| Notebook                | 5         | 0.23%   |
| Gateway                 | 5         | 0.23%   |
| Framework               | 5         | 0.23%   |
| Deciso                  | 5         | 0.23%   |
| Cisco Systems           | 5         | 0.23%   |
| Biostar                 | 5         | 0.23%   |
| Beckhoff Automation     | 5         | 0.23%   |
| Alienware               | 5         | 0.23%   |
| Wistron                 | 4         | 0.18%   |
| Pegatron                | 4         | 0.18%   |
| Huanan                  | 4         | 0.18%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 94        | 4.33%   |
| ASUS All Series                  | 27        | 1.24%   |
| Supermicro Super Server          | 21        | 0.97%   |
| RPi Raspberry Pi                 | 17        | 0.78%   |
| Dell OEM-R 720xd                 | 13        | 0.6%    |
| HP ProLiant MicroServer Gen8     | 10        | 0.46%   |
| Intel Nobilis                    | 9         | 0.41%   |
| PC Engines APU2                  | 7         | 0.32%   |
| Dell PowerEdge R710              | 7         | 0.32%   |
| HP ProLiant MicroServer          | 6         | 0.28%   |
| ASUS TUF GAMING X570-PLUS        | 6         | 0.28%   |
| MSI MS-7C02                      | 5         | 0.23%   |
| HP Z440 Workstation              | 5         | 0.23%   |
| HP EliteBook 840 G3              | 5         | 0.23%   |
| Framework Laptop                 | 5         | 0.23%   |
| Dell OptiPlex 9020               | 5         | 0.23%   |
| Dell Latitude E7240              | 5         | 0.23%   |
| System76 Lemur Pro               | 4         | 0.18%   |
| Supermicro X9SCL/X9SCM           | 4         | 0.18%   |
| Sun Microsystems Sun Fire X4150  | 4         | 0.18%   |
| HPE ProLiant MicroServer Gen10   | 4         | 0.18%   |
| HP Z620 Workstation              | 4         | 0.18%   |
| HP t620 Quad Core TC             | 4         | 0.18%   |
| HP Compaq Elite 8300 SFF         | 4         | 0.18%   |
| Gigabyte X570 I AORUS PRO WIFI   | 4         | 0.18%   |
| Gigabyte B450M DS3H              | 4         | 0.18%   |
| Fujitsu D3401-H2 S26361-D3401-H2 | 4         | 0.18%   |
| Dell PowerEdge T30               | 4         | 0.18%   |
| Dell PowerEdge R720              | 4         | 0.18%   |
| Dell PowerEdge R610              | 4         | 0.18%   |
| Dell OptiPlex 7040               | 4         | 0.18%   |
| Dell OptiPlex 3010               | 4         | 0.18%   |
| Dell Latitude E6430              | 4         | 0.18%   |
| ASRock Q1900B-ITX                | 4         | 0.18%   |
| Apple iMac10,1                   | 4         | 0.18%   |
| AMI Aptio CRB                    | 4         | 0.18%   |
| Wistron ProLiant ML110 G6        | 3         | 0.14%   |
| Supermicro X7SPA-HF              | 3         | 0.14%   |
| Supermicro X10SLL-F              | 3         | 0.14%   |
| PC Engines apu4                  | 3         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 259       | 11.93%  |
| Unknown            | 94        | 4.33%   |
| Dell Latitude      | 73        | 3.36%   |
| Dell PowerEdge     | 55        | 2.53%   |
| Dell Inspiron      | 47        | 2.16%   |
| Dell OptiPlex      | 41        | 1.89%   |
| ASUS PRIME         | 40        | 1.84%   |
| HP ProLiant        | 35        | 1.61%   |
| Acer Aspire        | 35        | 1.61%   |
| Dell Precision     | 33        | 1.52%   |
| Lenovo IdeaPad     | 32        | 1.47%   |
| HP Compaq          | 29        | 1.34%   |
| ASUS All           | 27        | 1.24%   |
| ASUS ROG           | 24        | 1.11%   |
| ASUS TUF           | 23        | 1.06%   |
| Supermicro Super   | 21        | 0.97%   |
| Dell XPS           | 18        | 0.83%   |
| RPi Raspberry      | 17        | 0.78%   |
| HP ProBook         | 16        | 0.74%   |
| HP EliteBook       | 15        | 0.69%   |
| Toshiba Satellite  | 13        | 0.6%    |
| Lenovo ThinkCentre | 13        | 0.6%    |
| Dell Vostro        | 13        | 0.6%    |
| Dell OEM-R         | 13        | 0.6%    |
| IBM System         | 11        | 0.51%   |
| HP Pavilion        | 11        | 0.51%   |
| ASRock X570        | 11        | 0.51%   |
| Intel Nobilis      | 9         | 0.41%   |
| HP Laptop          | 9         | 0.41%   |
| Gigabyte X570      | 9         | 0.41%   |
| HP ENVY            | 8         | 0.37%   |
| HP EliteDesk       | 8         | 0.37%   |
| ASUS ZenBook       | 8         | 0.37%   |
| ASRock X370        | 8         | 0.37%   |
| PC Engines APU2    | 7         | 0.32%   |
| Lenovo Legion      | 7         | 0.32%   |
| HPE ProLiant       | 7         | 0.32%   |
| HP t620            | 7         | 0.32%   |
| Gigabyte B450M     | 7         | 0.32%   |
| Fujitsu PRIMERGY   | 7         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 249       | 11.47%  |
| 2019    | 230       | 10.59%  |
| 2018    | 196       | 9.03%   |
| 2021    | 184       | 8.48%   |
| 2011    | 146       | 6.73%   |
| 2013    | 131       | 6.03%   |
| 2014    | 124       | 5.71%   |
| 2017    | 116       | 5.34%   |
| 2015    | 112       | 5.16%   |
| 2012    | 110       | 5.07%   |
| 2016    | 104       | 4.79%   |
| 2010    | 93        | 4.28%   |
| 2022    | 88        | 4.05%   |
| Unknown | 82        | 3.78%   |
| 2009    | 68        | 3.13%   |
| 2008    | 62        | 2.86%   |
| 2007    | 32        | 1.47%   |
| 2006    | 16        | 0.74%   |
| 2023    | 6         | 0.28%   |
| 2005    | 6         | 0.28%   |
| 2004    | 6         | 0.28%   |
| 2003    | 5         | 0.23%   |
| 2002    | 4         | 0.18%   |
| 2001    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 946       | 43.57%  |
| Notebook       | 892       | 41.09%  |
| Server         | 176       | 8.11%   |
| Mini pc        | 62        | 2.86%   |
| System on chip | 50        | 2.3%    |
| Convertible    | 24        | 1.11%   |
| All in one     | 21        | 0.97%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2128      | 98.02%  |
| Yes  | 43        | 1.98%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 573       | 26.05%  |
| 16.01-24.0      | 553       | 25.14%  |
| 32.01-64.0      | 313       | 14.23%  |
| 4.01-8.0        | 286       | 13%     |
| 64.01-256.0     | 202       | 9.18%   |
| 2.01-3.0        | 82        | 3.73%   |
| 24.01-32.0      | 50        | 2.27%   |
| 0.51-1.0        | 47        | 2.14%   |
| 3.01-4.0        | 46        | 2.09%   |
| 1.01-2.0        | 18        | 0.82%   |
| 0.01-0.5        | 16        | 0.73%   |
| More than 256.0 | 13        | 0.59%   |
| Unknown         | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 0.01-0.5        | 749       | 33.22%  |
| 0.51-1.0        | 679       | 30.11%  |
| 1.01-2.0        | 395       | 17.52%  |
| 2.01-3.0        | 104       | 4.61%   |
| 4.01-8.0        | 84        | 3.73%   |
| 3.01-4.0        | 70        | 3.1%    |
| 8.01-16.0       | 50        | 2.22%   |
| 24.01-32.0      | 31        | 1.37%   |
| 0               | 28        | 1.24%   |
| 32.01-64.0      | 22        | 0.98%   |
| 16.01-24.0      | 22        | 0.98%   |
| 64.01-256.0     | 19        | 0.84%   |
| More than 256.0 | 1         | 0.04%   |
| Unknown         | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1059      | 47.11%  |
| 2      | 476       | 21.17%  |
| 3      | 190       | 8.45%   |
| 0      | 151       | 6.72%   |
| 4      | 130       | 5.78%   |
| 5      | 76        | 3.38%   |
| 6      | 52        | 2.31%   |
| 7      | 27        | 1.2%    |
| 8      | 18        | 0.8%    |
| 10     | 11        | 0.49%   |
| 12     | 10        | 0.44%   |
| 14     | 9         | 0.4%    |
| 11     | 8         | 0.36%   |
| 9      | 8         | 0.36%   |
| 18     | 3         | 0.13%   |
| 58     | 2         | 0.09%   |
| 25     | 2         | 0.09%   |
| 23     | 2         | 0.09%   |
| 17     | 2         | 0.09%   |
| 16     | 2         | 0.09%   |
| 15     | 2         | 0.09%   |
| 13     | 2         | 0.09%   |
| 63     | 1         | 0.04%   |
| 40     | 1         | 0.04%   |
| 28     | 1         | 0.04%   |
| 24     | 1         | 0.04%   |
| 21     | 1         | 0.04%   |
| 19     | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1565      | 71.46%  |
| Yes       | 625       | 28.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1917      | 88.26%  |
| No        | 255       | 11.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1195      | 54.64%  |
| No        | 992       | 45.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1333      | 60.78%  |
| Yes       | 860       | 39.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 502       | 22.96%  |
| Russia      | 245       | 11.21%  |
| Germany     | 221       | 10.11%  |
| France      | 111       | 5.08%   |
| Canada      | 85        | 3.89%   |
| UK          | 79        | 3.61%   |
| Poland      | 72        | 3.29%   |
| Ukraine     | 48        | 2.2%    |
| China       | 48        | 2.2%    |
| Czechia     | 46        | 2.1%    |
| Netherlands | 45        | 2.06%   |
| Brazil      | 44        | 2.01%   |
| Australia   | 42        | 1.92%   |
| Japan       | 38        | 1.74%   |
| Austria     | 36        | 1.65%   |
| Switzerland | 35        | 1.6%    |
| Spain       | 31        | 1.42%   |
| Italy       | 30        | 1.37%   |
| Sweden      | 27        | 1.24%   |
| Norway      | 26        | 1.19%   |
| Finland     | 24        | 1.1%    |
| Romania     | 22        | 1.01%   |
| India       | 22        | 1.01%   |
| Indonesia   | 20        | 0.91%   |
| Greece      | 17        | 0.78%   |
| Thailand    | 15        | 0.69%   |
| Ireland     | 15        | 0.69%   |
| Portugal    | 13        | 0.59%   |
| Denmark     | 13        | 0.59%   |
| Belgium     | 13        | 0.59%   |
| Argentina   | 13        | 0.59%   |
| New Zealand | 12        | 0.55%   |
| Hungary     | 11        | 0.5%    |
| Bulgaria    | 11        | 0.5%    |
| Taiwan      | 9         | 0.41%   |
| Slovenia    | 8         | 0.37%   |
| Mexico      | 8         | 0.37%   |
| Croatia     | 8         | 0.37%   |
| Singapore   | 7         | 0.32%   |
| Serbia      | 7         | 0.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Moscow        | 93        | 3.98%   |
| Vienna        | 30        | 1.29%   |
| Brooklyn      | 27        | 1.16%   |
| Berlin        | 27        | 1.16%   |
| Kyiv          | 23        | 0.99%   |
| St Petersburg | 20        | 0.86%   |
| Paris         | 18        | 0.77%   |
| Gdynia        | 18        | 0.77%   |
| Ludwigsburg   | 16        | 0.69%   |
| London        | 16        | 0.69%   |
| Krasnodar     | 16        | 0.69%   |
| Warsaw        | 15        | 0.64%   |
| Sydney        | 15        | 0.64%   |
| Montreal      | 15        | 0.64%   |
| Grand Rapids  | 15        | 0.64%   |
| Chicago       | 15        | 0.64%   |
| Amsterdam     | 15        | 0.64%   |
| Zurich        | 14        | 0.6%    |
| Helsinki      | 14        | 0.6%    |
| Yekaterinburg | 13        | 0.56%   |
| Prague        | 13        | 0.56%   |
| Tuklaty       | 12        | 0.51%   |
| Seattle       | 10        | 0.43%   |
| Portland      | 10        | 0.43%   |
| Jakarta       | 10        | 0.43%   |
| Ozersk        | 9         | 0.39%   |
| Oslo          | 9         | 0.39%   |
| Novosibirsk   | 9         | 0.39%   |
| Lexington     | 9         | 0.39%   |
| Dublin        | 9         | 0.39%   |
| Athens        | 9         | 0.39%   |
| Sofia         | 8         | 0.34%   |
| Shenzhen      | 8         | 0.34%   |
| Rochester     | 8         | 0.34%   |
| Poway         | 8         | 0.34%   |
| Munich        | 8         | 0.34%   |
| Madrid        | 8         | 0.34%   |
| Bucharest     | 8         | 0.34%   |
| Stockholm     | 7         | 0.3%    |
| Singapore     | 7         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 607       | 1740   | 19.46%  |
| Samsung Electronics | 525       | 976    | 16.83%  |
| Seagate             | 441       | 1151   | 14.14%  |
| Toshiba             | 200       | 433    | 6.41%   |
| Crucial             | 173       | 262    | 5.55%   |
| Kingston            | 170       | 223    | 5.45%   |
| Intel               | 131       | 252    | 4.2%    |
| Hitachi             | 97        | 262    | 3.11%   |
| SanDisk             | 88        | 122    | 2.82%   |
| HGST                | 85        | 317    | 2.73%   |
| A-DATA Technology   | 55        | 71     | 1.76%   |
| SK hynix            | 47        | 53     | 1.51%   |
| Transcend           | 42        | 54     | 1.35%   |
| Micron Technology   | 42        | 68     | 1.35%   |
| Hewlett-Packard     | 28        | 162    | 0.9%    |
| Phison              | 21        | 30     | 0.67%   |
| PNY                 | 18        | 29     | 0.58%   |
| Corsair             | 17        | 36     | 0.55%   |
| OCZ                 | 16        | 20     | 0.51%   |
| KIOXIA              | 16        | 16     | 0.51%   |
| SPCC                | 15        | 34     | 0.48%   |
| Apple               | 13        | 14     | 0.42%   |
| KingSpec            | 11        | 16     | 0.35%   |
| GOODRAM             | 11        | 21     | 0.35%   |
| Gigabyte Technology | 11        | 14     | 0.35%   |
| Silicon Motion      | 10        | 11     | 0.32%   |
| LITEON              | 10        | 15     | 0.32%   |
| Fujitsu             | 10        | 15     | 0.32%   |
| Patriot             | 9         | 12     | 0.29%   |
| OWC                 | 8         | 12     | 0.26%   |
| Maxtor              | 8         | 12     | 0.26%   |
| FORESEE             | 8         | 8      | 0.26%   |
| China               | 8         | 9      | 0.26%   |
| Apacer              | 8         | 8      | 0.26%   |
| Plextor             | 7         | 13     | 0.22%   |
| Mushkin             | 7         | 8      | 0.22%   |
| Intenso             | 7         | 8      | 0.22%   |
| Lenovo              | 6         | 6      | 0.19%   |
| Hikvision           | 6         | 7      | 0.19%   |
| Team                | 5         | 7      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 41        | 1.11%   |
| Samsung SSD 850 EVO 250GB          | 29        | 0.79%   |
| Seagate ST1000DM010-2EP102 1TB     | 23        | 0.62%   |
| WDC WD40EFRX-68N32N0 4TB           | 22        | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB           | 22        | 0.6%    |
| Kingston SA400S37120G 120GB        | 22        | 0.6%    |
| WDC WD30EFRX-68EUZN0 3TB           | 21        | 0.57%   |
| Samsung SSD 860 EVO 500GB          | 20        | 0.54%   |
| Samsung SSD 970 EVO Plus 1TB       | 19        | 0.52%   |
| Samsung SSD 850 EVO 500GB          | 19        | 0.52%   |
| Crucial CT500MX500SSD1 500GB       | 18        | 0.49%   |
| WDC WD800JD-75MSA3 80GB            | 17        | 0.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 17        | 0.46%   |
| Samsung SSD 860 EVO 250GB          | 17        | 0.46%   |
| Toshiba MQ01ABD100 1TB             | 16        | 0.43%   |
| Toshiba DT01ACA100 1TB             | 16        | 0.43%   |
| Seagate ST4000DM000-1F2168 4TB     | 16        | 0.43%   |
| Seagate ST2000DM008-2FR102 2TB     | 16        | 0.43%   |
| Seagate ST1000LM035-1RK172 1TB     | 16        | 0.43%   |
| Crucial CT250MX500SSD1 250GB       | 16        | 0.43%   |
| HGST HTS721010A9E630 1TB           | 15        | 0.41%   |
| Crucial CT240BX500SSD1 240GB       | 15        | 0.41%   |
| Samsung SSD 970 EVO Plus 500GB     | 14        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB        | 14        | 0.38%   |
| Toshiba MQ01ABF050 500GB           | 13        | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB     | 13        | 0.35%   |
| Samsung SSD 860 EVO 1TB            | 13        | 0.35%   |
| WDC WD20EFRX-68EUZN0 2TB           | 12        | 0.33%   |
| Seagate ST4000VN008-2DR166 4TB     | 12        | 0.33%   |
| Samsung SSD 870 EVO 1TB            | 12        | 0.33%   |
| Seagate ST500DM002-1BD142 500GB    | 11        | 0.3%    |
| Seagate ST2000DM001-1CH164 2TB     | 11        | 0.3%    |
| Seagate ST1000LM048-2E7172 1TB     | 11        | 0.3%    |
| Samsung SSD 850 EVO 1TB            | 11        | 0.3%    |
| WDC WD40EFRX-68WT0N0 4TB           | 10        | 0.27%   |
| Seagate ST8000DM004-2CX188 8TB     | 10        | 0.27%   |
| Seagate ST3500418AS 500GB          | 10        | 0.27%   |
| Seagate ST2000LM007-1R8174 2TB     | 10        | 0.27%   |
| Samsung SSD 980 PRO 1TB            | 10        | 0.27%   |
| Samsung SSD 970 EVO 500GB          | 10        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| WDC                  | 485       | 1500   | 35.38%  |
| Seagate              | 435       | 1138   | 31.73%  |
| Toshiba              | 164       | 380    | 11.96%  |
| Hitachi              | 96        | 258    | 7%      |
| HGST                 | 85        | 317    | 6.2%    |
| Samsung Electronics  | 46        | 73     | 3.36%   |
| Hewlett-Packard      | 15        | 136    | 1.09%   |
| Fujitsu              | 10        | 15     | 0.73%   |
| Maxtor               | 8         | 12     | 0.58%   |
| Apple                | 4         | 5      | 0.29%   |
| LSI                  | 3         | 6      | 0.22%   |
| HPE                  | 3         | 17     | 0.22%   |
| IBM/Hitachi          | 2         | 2      | 0.15%   |
| HPT                  | 2         | 9      | 0.15%   |
| Dell                 | 2         | 5      | 0.15%   |
| Areca                | 2         | 3      | 0.15%   |
| Adaptec              | 2         | 12     | 0.15%   |
| WD MediaMax          | 1         | 2      | 0.07%   |
| SYNOLOGY             | 1         | 1      | 0.07%   |
| QUANTUM              | 1         | 2      | 0.07%   |
| NETAPP               | 1         | 2      | 0.07%   |
| MaxDigital           | 1         | 1      | 0.07%   |
| IBM                  | 1         | 1      | 0.07%   |
| ExcelStor Technology | 1         | 4      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 291       | 571    | 24.09%  |
| Kingston            | 146       | 189    | 12.09%  |
| Crucial             | 142       | 213    | 11.75%  |
| Intel               | 90        | 199    | 7.45%   |
| SanDisk             | 87        | 121    | 7.2%    |
| WDC                 | 67        | 112    | 5.55%   |
| A-DATA Technology   | 40        | 52     | 3.31%   |
| Transcend           | 37        | 47     | 3.06%   |
| Micron Technology   | 24        | 41     | 1.99%   |
| Toshiba             | 20        | 21     | 1.66%   |
| SK hynix            | 17        | 20     | 1.41%   |
| OCZ                 | 16        | 20     | 1.32%   |
| Hewlett-Packard     | 14        | 20     | 1.16%   |
| PNY                 | 13        | 23     | 1.08%   |
| KingSpec            | 11        | 16     | 0.91%   |
| Corsair             | 11        | 14     | 0.91%   |
| SPCC                | 10        | 27     | 0.83%   |
| Patriot             | 9         | 12     | 0.75%   |
| LITEON              | 9         | 14     | 0.75%   |
| Apple               | 9         | 9      | 0.75%   |
| OWC                 | 8         | 12     | 0.66%   |
| GOODRAM             | 8         | 17     | 0.66%   |
| China               | 8         | 9      | 0.66%   |
| Apacer              | 8         | 8      | 0.66%   |
| Intenso             | 7         | 8      | 0.58%   |
| Gigabyte Technology | 6         | 7      | 0.5%    |
| Seagate             | 5         | 7      | 0.41%   |
| Plextor             | 5         | 8      | 0.41%   |
| Mushkin             | 5         | 5      | 0.41%   |
| Team                | 4         | 6      | 0.33%   |
| Phison              | 4         | 5      | 0.33%   |
| LITEONIT            | 4         | 4      | 0.33%   |
| Hoodisk             | 4         | 6      | 0.33%   |
| Hikvision           | 4         | 5      | 0.33%   |
| Zheino              | 3         | 4      | 0.25%   |
| Verbatim            | 3         | 3      | 0.25%   |
| Vaseky              | 3         | 3      | 0.25%   |
| Supermicro          | 3         | 3      | 0.25%   |
| ORICO               | 3         | 3      | 0.25%   |
| Lexar               | 3         | 9      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1067      | 3901   | 39.71%  |
| SSD  | 1048      | 1944   | 39%     |
| NVMe | 572       | 884    | 21.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1699      | 5845   | 74.81%  |
| NVMe | 572       | 884    | 25.19%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1239      | 2372   | 52.02%  |
| 0.51-1.0   | 513       | 1001   | 21.54%  |
| 1.01-2.0   | 241       | 631    | 10.12%  |
| 3.01-4.0   | 145       | 660    | 6.09%   |
| 4.01-10.0  | 126       | 707    | 5.29%   |
| 2.01-3.0   | 82        | 288    | 3.44%   |
| 10.01-20.0 | 33        | 180    | 1.39%   |
| 20.01-50.0 | 3         | 6      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 688       | 30.5%   |
| 251-500        | 508       | 22.52%  |
| 501-1000       | 312       | 13.83%  |
| 51-100         | 242       | 10.73%  |
| 21-50          | 163       | 7.23%   |
| 1-20           | 120       | 5.32%   |
| 1001-2000      | 110       | 4.88%   |
| More than 3000 | 61        | 2.7%    |
| 2001-3000      | 28        | 1.24%   |
| Unknown        | 24        | 1.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1615      | 71.59%  |
| 21-50          | 297       | 13.16%  |
| 51-100         | 114       | 5.05%   |
| 101-250        | 82        | 3.63%   |
| 251-500        | 43        | 1.91%   |
| 501-1000       | 35        | 1.55%   |
| Unknown        | 24        | 1.06%   |
| More than 3000 | 19        | 0.84%   |
| 1001-2000      | 14        | 0.62%   |
| 2001-3000      | 12        | 0.53%   |
| 0              | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD30EFRX-68EUZN0 3TB            | 6         | 18     | 1.31%   |
| Seagate ST500LT012-1DG142 500GB     | 6         | 6      | 1.31%   |
| Seagate ST3500413AS 500GB           | 6         | 9      | 1.31%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 6         | 7      | 1.31%   |
| HGST HTS725050A7E630 500GB          | 6         | 14     | 1.31%   |
| WDC WD20EFRX-68EUZN0 2TB            | 5         | 12     | 1.09%   |
| Samsung Electronics SSD 870 EVO 1TB | 5         | 7      | 1.09%   |
| WDC WD40EFRX-68WT0N0 4TB            | 4         | 12     | 0.87%   |
| Seagate ST9500420AS 500GB           | 4         | 6      | 0.87%   |
| Samsung Electronics HD501LJ 500GB   | 4         | 6      | 0.87%   |
| Toshiba MQ01ABF050 500GB            | 3         | 3      | 0.65%   |
| Toshiba MQ01ABD100 1TB              | 3         | 3      | 0.65%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 6      | 0.65%   |
| Seagate ST380013AS 80GB             | 3         | 4      | 0.65%   |
| Seagate ST3500418AS 500GB           | 3         | 6      | 0.65%   |
| Seagate ST320LT007-9ZV142 320GB     | 3         | 3      | 0.65%   |
| Seagate ST2000DM001-9YN164 2TB      | 3         | 3      | 0.65%   |
| Seagate ST1000DM003-1CH162 1TB      | 3         | 4      | 0.65%   |
| Samsung Electronics HD103UJ 1TB     | 3         | 6      | 0.65%   |
| Intel SSDSA2M080G2GC 80GB           | 3         | 3      | 0.65%   |
| HGST HTS721010A9E630 1TB            | 3         | 16     | 0.65%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 2      | 0.44%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 2         | 3      | 0.44%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 2         | 2      | 0.44%   |
| WDC WD40EFRX-68N32N0 4TB            | 2         | 5      | 0.44%   |
| WDC WD3200BPVT-80JJ5T0 320GB        | 2         | 2      | 0.44%   |
| WDC WD20EARS-00MVWB0 2TB            | 2         | 2      | 0.44%   |
| WDC WD2002FYPS-02W3B0 2TB           | 2         | 2      | 0.44%   |
| WDC WD2002FYPS-01U1B0 2TB           | 2         | 3      | 0.44%   |
| WDC WD2000FYYZ-01UL1B2 2TB          | 2         | 4      | 0.44%   |
| WDC WD2000FYYZ-01UL1B1 2TB          | 2         | 4      | 0.44%   |
| WDC WD15EADS-00P8B0 1.5TB           | 2         | 2      | 0.44%   |
| Toshiba MK3261GSYN 320GB            | 2         | 2      | 0.44%   |
| Toshiba MK2546GSX 250GB             | 2         | 2      | 0.44%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 0.44%   |
| Seagate ST9250827AS 250GB           | 2         | 3      | 0.44%   |
| Seagate ST9250315AS 250GB           | 2         | 2      | 0.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 0.44%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 2      | 0.44%   |
| Seagate ST500DM002-1BC142 500GB     | 2         | 2      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 106       | 152    | 24.37%  |
| WDC                  | 99        | 188    | 22.76%  |
| Samsung Electronics  | 41        | 54     | 9.43%   |
| Hitachi              | 38        | 62     | 8.74%   |
| Toshiba              | 31        | 58     | 7.13%   |
| Intel                | 21        | 29     | 4.83%   |
| Kingston             | 16        | 18     | 3.68%   |
| HGST                 | 14        | 37     | 3.22%   |
| Crucial              | 11        | 17     | 2.53%   |
| SanDisk              | 8         | 10     | 1.84%   |
| A-DATA Technology    | 7         | 9      | 1.61%   |
| Micron Technology    | 6         | 11     | 1.38%   |
| Maxtor               | 5         | 9      | 1.15%   |
| SK hynix             | 4         | 6      | 0.92%   |
| Hewlett-Packard      | 4         | 7      | 0.92%   |
| OCZ                  | 3         | 4      | 0.69%   |
| Fujitsu              | 2         | 5      | 0.46%   |
| Corsair              | 2         | 4      | 0.46%   |
| Apple                | 2         | 2      | 0.46%   |
| walram               | 1         | 1      | 0.23%   |
| Transcend            | 1         | 1      | 0.23%   |
| SSSTC                | 1         | 1      | 0.23%   |
| SPCC                 | 1         | 1      | 0.23%   |
| SMI                  | 1         | 1      | 0.23%   |
| Plextor              | 1         | 1      | 0.23%   |
| Phison               | 1         | 1      | 0.23%   |
| LITEON               | 1         | 1      | 0.23%   |
| Lexar                | 1         | 1      | 0.23%   |
| IBM/Hitachi          | 1         | 1      | 0.23%   |
| GK                   | 1         | 1      | 0.23%   |
| Fanxiang             | 1         | 1      | 0.23%   |
| ExcelStor Technology | 1         | 2      | 0.23%   |
| Apacer               | 1         | 1      | 0.23%   |
| AMD                  | 1         | 2      | 0.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 105       | 151    | 33.23%  |
| WDC                  | 96        | 185    | 30.38%  |
| Hitachi              | 38        | 62     | 12.03%  |
| Toshiba              | 30        | 57     | 9.49%   |
| Samsung Electronics  | 20        | 26     | 6.33%   |
| HGST                 | 14        | 37     | 4.43%   |
| Maxtor               | 5         | 9      | 1.58%   |
| Hewlett-Packard      | 3         | 6      | 0.95%   |
| Fujitsu              | 2         | 5      | 0.63%   |
| IBM/Hitachi          | 1         | 1      | 0.32%   |
| ExcelStor Technology | 1         | 2      | 0.32%   |
| Apple                | 1         | 1      | 0.32%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 295       | 542    | 71.6%   |
| SSD  | 113       | 153    | 27.43%  |
| NVMe | 4         | 4      | 0.97%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB          | 1         | 1      | 14.29%  |
| Toshiba MG05ACA800E 8TB           | 1         | 1      | 14.29%  |
| SanDisk pSSD 128GB                | 1         | 1      | 14.29%  |
| Samsung Electronics HM250JI 250GB | 1         | 1      | 14.29%  |
| Maxtor 6E040L0 41GB               | 1         | 1      | 14.29%  |
| Hitachi HUS724040ALE641 4TB       | 1         | 14     | 14.29%  |
| Crucial M4-CT256M4SSD1 256GB      | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| SanDisk             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Maxtor              | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 14     | 14.29%  |
| Crucial             | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1834      | 5767   | 79.64%  |
| Malfunc  | 396       | 699    | 17.19%  |
| Detected | 66        | 243    | 2.87%   |
| Failed   | 7         | 20     | 0.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1438      | 50.56%  |
| AMD                              | 387       | 13.61%  |
| Samsung Electronics              | 236       | 8.3%    |
| Broadcom / LSI                   | 148       | 5.2%    |
| SanDisk                          | 94        | 3.31%   |
| ASMedia Technology               | 63        | 2.22%   |
| Marvell Technology Group         | 56        | 1.97%   |
| Silicon Motion                   | 40        | 1.41%   |
| Phison Electronics               | 40        | 1.41%   |
| SK hynix                         | 30        | 1.05%   |
| Nvidia                           | 30        | 1.05%   |
| Kingston Technology Company      | 27        | 0.95%   |
| Micron/Crucial Technology        | 26        | 0.91%   |
| JMicron Technology               | 25        | 0.88%   |
| Toshiba                          | 22        | 0.77%   |
| Micron Technology                | 20        | 0.7%    |
| Adaptec                          | 20        | 0.7%    |
| KIOXIA                           | 17        | 0.6%    |
| Hewlett-Packard                  | 16        | 0.56%   |
| ADATA Technology                 | 14        | 0.49%   |
| Silicon Image                    | 9         | 0.32%   |
| VIA Technologies                 | 7         | 0.25%   |
| Areca Technology                 | 7         | 0.25%   |
| Union Memory (Shenzhen)          | 6         | 0.21%   |
| Silicon Integrated Systems [SiS] | 6         | 0.21%   |
| Solid State Storage Technology   | 5         | 0.18%   |
| Shenzhen Longsys Electronics     | 5         | 0.18%   |
| Seagate Technology               | 5         | 0.18%   |
| Realtek Semiconductor            | 5         | 0.18%   |
| Lite-On Technology               | 5         | 0.18%   |
| Chelsio Communications           | 5         | 0.18%   |
| 3ware                            | 5         | 0.18%   |
| Transcend                        | 3         | 0.11%   |
| Lenovo                           | 3         | 0.11%   |
| Integrated Technology Express    | 3         | 0.11%   |
| Broadcom                         | 3         | 0.11%   |
| ULi Electronics                  | 2         | 0.07%   |
| Promise Technology               | 2         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.07%   |
| INNOGRIT                         | 2         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 253       | 7.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 132       | 4.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 97        | 2.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 92        | 2.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 76        | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 75        | 2.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 73        | 2.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 71        | 2.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 64        | 1.94%   |
| AMD 400 Series Chipset SATA Controller                                         | 58        | 1.76%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 57        | 1.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 51        | 1.55%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 49        | 1.49%   |
| Intel Comet Lake SATA AHCI Controller                                          | 41        | 1.24%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 39        | 1.18%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 37        | 1.12%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 36        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 36        | 1.09%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 35        | 1.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 35        | 1.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 35        | 1.06%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 34        | 1.03%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 34        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 34        | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 33        | 1%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 33        | 1%      |
| Samsung NVMe SSD Controller 980                                                | 32        | 0.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 32        | 0.97%   |
| AMD 500 Series Chipset SATA Controller                                         | 32        | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 31        | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 31        | 0.94%   |
| Unknown                                                                        | 31        | 0.94%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 28        | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 28        | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 28        | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 27        | 0.82%   |
| Phison E12 NVMe Controller                                                     | 23        | 0.7%    |
| Intel SATA Controller [RAID mode]                                              | 23        | 0.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 23        | 0.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 23        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1582      | 55.7%   |
| NVMe | 608       | 21.41%  |
| IDE  | 330       | 11.62%  |
| RAID | 192       | 6.76%   |
| SAS  | 94        | 3.31%   |
| SCSI | 34        | 1.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 1620      | 74.41%  |
| AMD                | 458       | 21.04%  |
| ARM                | 75        | 3.45%   |
| Unknown            | 14        | 0.64%   |
| IBM                | 2         | 0.09%   |
| VIA                | 1         | 0.05%   |
| Sun                | 1         | 0.05%   |
| Rockchip           | 1         | 0.05%   |
| Research           | 1         | 0.05%   |
| NXP                | 1         | 0.05%   |
| Motorola           | 1         | 0.05%   |
| i                  | 1         | 0.05%   |
| Baikal Electronics | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ARM Cortex-A72 r0p3                     | 27        | 1.23%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 23        | 1.05%   |
| ARM Cortex-A53 r0p4                     | 20        | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 19        | 0.87%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 18        | 0.82%   |
| Intel CPU Version                       | 16        | 0.73%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 16        | 0.73%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 15        | 0.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 15        | 0.68%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 15        | 0.68%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 15        | 0.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 14        | 0.64%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 14        | 0.64%   |
|                                         | 14        | 0.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 13        | 0.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 13        | 0.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 13        | 0.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 12        | 0.55%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 12        | 0.55%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 12        | 0.55%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 11        | 0.5%    |
| Intel Core i5-8350U CPU @ 1.70GHz       | 11        | 0.5%    |
| Intel Core i5-6300U CPU @ 2.40GHz       | 11        | 0.5%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 11        | 0.5%    |
| AMD Ryzen 9 3900X 12-Core Processor     | 11        | 0.5%    |
| AMD Ryzen 5 5600G with Radeon Graphics  | 11        | 0.5%    |
| AMD GX-412TC SOC                        | 11        | 0.5%    |
| AMD FX-8350 Eight-Core Processor        | 11        | 0.5%    |
| Intel Xeon                              | 10        | 0.46%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 10        | 0.46%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 10        | 0.46%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 10        | 0.46%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 9         | 0.41%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 0.41%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 9         | 0.41%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 9         | 0.41%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 9         | 0.41%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 9         | 0.41%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 9         | 0.41%   |
| Intel Core 2 Duo                        | 9         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 426       | 19.52%  |
| Intel Core i7          | 369       | 16.91%  |
| Intel Xeon             | 245       | 11.23%  |
| Other                  | 132       | 6.05%   |
| AMD Ryzen 7            | 103       | 4.72%   |
| Intel Core i3          | 98        | 4.49%   |
| Intel Celeron          | 97        | 4.45%   |
| AMD Ryzen 5            | 80        | 3.67%   |
| Intel Core 2 Duo       | 74        | 3.39%   |
| ARM Cortex             | 69        | 3.16%   |
| Intel Atom             | 52        | 2.38%   |
| Intel Pentium          | 40        | 1.83%   |
| AMD Ryzen 9            | 37        | 1.7%    |
| AMD FX                 | 28        | 1.28%   |
| AMD Ryzen 3            | 24        | 1.1%    |
| AMD GX                 | 23        | 1.05%   |
| Intel Pentium 4        | 15        | 0.69%   |
| Intel Xeon Silver      | 14        | 0.64%   |
| AMD Ryzen 7 PRO        | 14        | 0.64%   |
| Intel Core 2 Quad      | 13        | 0.6%    |
| Intel Core 2           | 13        | 0.6%    |
| Intel Pentium M        | 12        | 0.55%   |
| Intel Core i9          | 12        | 0.55%   |
| AMD Ryzen 5 PRO        | 12        | 0.55%   |
| AMD Opteron            | 12        | 0.55%   |
| AMD EPYC               | 10        | 0.46%   |
| AMD Ryzen Threadripper | 9         | 0.41%   |
| Intel Pentium Silver   | 7         | 0.32%   |
| AMD Turion II Neo      | 7         | 0.32%   |
| AMD Phenom II X6       | 7         | 0.32%   |
| AMD E                  | 7         | 0.32%   |
| AMD Athlon 64 X2       | 7         | 0.32%   |
| AMD Athlon             | 7         | 0.32%   |
| AMD A10                | 7         | 0.32%   |
| AMD A8                 | 6         | 0.27%   |
| AMD A6                 | 6         | 0.27%   |
| Intel Xeon Gold        | 5         | 0.23%   |
| Intel Pentium Dual     | 5         | 0.23%   |
| AMD Phenom II X4       | 5         | 0.23%   |
| AMD Phenom             | 5         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 703       | 32.2%   |
| 2       | 595       | 27.26%  |
| Unknown | 214       | 9.8%    |
| 8       | 158       | 7.24%   |
| 16      | 141       | 6.46%   |
| 6       | 133       | 6.09%   |
| 12      | 89        | 4.08%   |
| 1       | 55        | 2.52%   |
| 24      | 29        | 1.33%   |
| 32      | 23        | 1.05%   |
| 10      | 16        | 0.73%   |
| 20      | 11        | 0.5%    |
| 64      | 4         | 0.18%   |
| 14      | 3         | 0.14%   |
| 48      | 2         | 0.09%   |
| 28      | 2         | 0.09%   |
| 3       | 2         | 0.09%   |
| 128     | 1         | 0.05%   |
| 40      | 1         | 0.05%   |
| 11      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1957      | 89.89%  |
| 2       | 133       | 6.11%   |
| Unknown | 86        | 3.95%   |
| 4       | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1083      | 49.72%  |
| 1       | 853       | 39.16%  |
| Unknown | 242       | 11.11%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 308       | 14.13%  |
| IvyBridge       | 181       | 8.3%    |
| Haswell         | 179       | 8.21%   |
| Unknown         | 162       | 7.43%   |
| SandyBridge     | 161       | 7.39%   |
| Skylake         | 141       | 6.47%   |
| Zen 2           | 103       | 4.72%   |
| Penryn          | 82        | 3.76%   |
| Broadwell       | 81        | 3.72%   |
| Westmere        | 73        | 3.35%   |
| Core            | 65        | 2.98%   |
| Zen+            | 63        | 2.89%   |
| Zen 3           | 60        | 2.75%   |
| Silvermont      | 56        | 2.57%   |
| CometLake       | 50        | 2.29%   |
| Bonnell         | 49        | 2.25%   |
| Zen             | 48        | 2.2%    |
| TigerLake       | 38        | 1.74%   |
| K10             | 35        | 1.61%   |
| Piledriver      | 34        | 1.56%   |
| Nehalem         | 31        | 1.42%   |
| Puma            | 26        | 1.19%   |
| NetBurst        | 23        | 1.06%   |
| Goldmont plus   | 21        | 0.96%   |
| P6              | 18        | 0.83%   |
| Excavator       | 15        | 0.69%   |
| Bobcat          | 15        | 0.69%   |
| K8 Hammer       | 14        | 0.64%   |
| Goldmont        | 14        | 0.64%   |
| Jaguar          | 13        | 0.6%    |
| IceLake         | 9         | 0.41%   |
| Bulldozer       | 4         | 0.18%   |
| Steamroller     | 3         | 0.14%   |
| K8 & K10 hybrid | 2         | 0.09%   |
| Geode           | 2         | 0.09%   |
| K10 Llano       | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1090      | 47.49%  |
| Nvidia                                       | 523       | 22.79%  |
| AMD                                          | 460       | 20.04%  |
| Matrox Electronics Systems                   | 137       | 5.97%   |
| ASPEED Technology                            | 73        | 3.18%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.13%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.09%   |
| VIA Technologies                             | 2         | 0.09%   |
| S3 Graphics                                  | 2         | 0.09%   |
| Silicon Motion                               | 1         | 0.04%   |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.04%   |
| Huawei Technologies                          | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 97        | 4.1%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 73        | 3.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 72        | 3.04%   |
| Intel UHD Graphics 620                                                                   | 49        | 2.07%   |
| Intel HD Graphics 5500                                                                   | 47        | 1.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 46        | 1.94%   |
| Intel HD Graphics 620                                                                    | 44        | 1.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 42        | 1.77%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 41        | 1.73%   |
| Intel HD Graphics 530                                                                    | 40        | 1.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 38        | 1.6%    |
| AMD Renoir                                                                               | 38        | 1.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 36        | 1.52%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 36        | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 35        | 1.48%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 34        | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 32        | 1.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 30        | 1.27%   |
| Matrox Electronics Systems G200eR2                                                       | 29        | 1.22%   |
| Intel HD Graphics 630                                                                    | 29        | 1.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 29        | 1.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 29        | 1.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 29        | 1.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 1.14%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 26        | 1.1%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 26        | 1.1%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 25        | 1.06%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 23        | 0.97%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 22        | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 0.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 0.89%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 20        | 0.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 20        | 0.84%   |
| AMD ES1000                                                                               | 20        | 0.84%   |
| Matrox Electronics Systems MGA G200EH                                                    | 19        | 0.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 0.8%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 18        | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 0.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 17        | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 803       | 36.73%  |
| 1 x AMD                                  | 386       | 17.66%  |
| 1 x Nvidia                               | 336       | 15.37%  |
| Intel + Nvidia                           | 159       | 7.27%   |
| 1 x Matrox                               | 136       | 6.22%   |
| Other                                    | 115       | 5.26%   |
| 2 x Intel                                | 89        | 4.07%   |
| 1 x ASPEED                               | 65        | 2.97%   |
| Intel + AMD                              | 34        | 1.56%   |
| 2 x AMD                                  | 18        | 0.82%   |
| AMD + Nvidia                             | 17        | 0.78%   |
| Nvidia + ASPEED                          | 6         | 0.27%   |
| 2 x Nvidia                               | 5         | 0.23%   |
| 1 x SiS                                  | 3         | 0.14%   |
| 1 x XGI                                  | 2         | 0.09%   |
| 1 x VIA                                  | 2         | 0.09%   |
| 1 x S3 Graphics                          | 2         | 0.09%   |
| AMD + ASPEED                             | 2         | 0.09%   |
| 1 x Silicon Motion                       | 1         | 0.05%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.05%   |
| Nvidia + Huawei Technologies             | 1         | 0.05%   |
| Intel + Matrox                           | 1         | 0.05%   |
| Intel + ASPEED                           | 1         | 0.05%   |
| Intel + AMD + 1 x Nvidia                 | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1720      | 78.54%  |
| Proprietary | 342       | 15.62%  |
| Unknown     | 128       | 5.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1669      | 75.62%  |
| 1.01-2.0   | 142       | 6.43%   |
| 0.01-0.5   | 110       | 4.98%   |
| 0.51-1.0   | 89        | 4.03%   |
| 3.01-4.0   | 76        | 3.44%   |
| 7.01-8.0   | 61        | 2.76%   |
| 5.01-6.0   | 33        | 1.5%    |
| 2.01-3.0   | 13        | 0.59%   |
| 8.01-16.0  | 13        | 0.59%   |
| 4.01-5.0   | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 152       | 11.7%   |
| Samsung Electronics     | 144       | 11.09%  |
| LG Display              | 134       | 10.32%  |
| Dell                    | 109       | 8.39%   |
| BOE                     | 80        | 6.16%   |
| Chimei Innolux          | 77        | 5.93%   |
| Goldstar                | 61        | 4.7%    |
| Lenovo                  | 46        | 3.54%   |
| Acer                    | 43        | 3.31%   |
| Hewlett-Packard         | 42        | 3.23%   |
| AOC                     | 37        | 2.85%   |
| Philips                 | 29        | 2.23%   |
| BenQ                    | 29        | 2.23%   |
| Sharp                   | 26        | 2%      |
| Ancor Communications    | 26        | 2%      |
| Apple                   | 24        | 1.85%   |
| LG Electronics          | 20        | 1.54%   |
| Iiyama                  | 17        | 1.31%   |
| ViewSonic               | 15        | 1.15%   |
| Sony                    | 12        | 0.92%   |
| Chi Mei Optoelectronics | 12        | 0.92%   |
| InfoVision              | 10        | 0.77%   |
| Eizo                    | 10        | 0.77%   |
| Unknown                 | 9         | 0.69%   |
| NEC Computers           | 9         | 0.69%   |
| LGD                     | 8         | 0.62%   |
| ASUSTek Computer        | 8         | 0.62%   |
| Sceptre Tech            | 7         | 0.54%   |
| PANDA                   | 7         | 0.54%   |
| Idek Iiyama             | 7         | 0.54%   |
| Toshiba                 | 6         | 0.46%   |
| Panasonic               | 5         | 0.38%   |
| LG Philips              | 5         | 0.38%   |
| JDI                     | 5         | 0.38%   |
| HannStar                | 4         | 0.31%   |
| CSO                     | 4         | 0.31%   |
| CPT                     | 4         | 0.31%   |
| Unknown                 | 4         | 0.31%   |
| Mi                      | 3         | 0.23%   |
| Lenovo Group Limited    | 3         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 10        | 0.74%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 6         | 0.44%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 5         | 0.37%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 5         | 0.37%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch        | 5         | 0.37%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch       | 4         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 4         | 0.3%    |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 4         | 0.3%    |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 4         | 0.3%    |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch          | 4         | 0.3%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 4         | 0.3%    |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 4         | 0.3%    |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 4         | 0.3%    |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch              | 4         | 0.3%    |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 4         | 0.3%    |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 4         | 0.3%    |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                    | 4         | 0.3%    |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch     | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch     | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch       | 4         | 0.3%    |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                    | 4         | 0.3%    |
| Unknown                                                              | 4         | 0.3%    |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch          | 3         | 0.22%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch              | 3         | 0.22%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch    | 3         | 0.22%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch    | 3         | 0.22%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 3         | 0.22%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch            | 3         | 0.22%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 3         | 0.22%   |
| LGD LCD Monitor 1920x1080                                            | 3         | 0.22%   |
| LG Electronics LCD Monitor LG Ultra HD                               | 3         | 0.22%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 3         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 545       | 42.81%  |
| 1366x768 (WXGA)    | 184       | 14.45%  |
| 3840x2160 (4K)     | 86        | 6.76%   |
| 2560x1440 (QHD)    | 76        | 5.97%   |
| 1600x900 (HD+)     | 56        | 4.4%    |
| 1920x1200 (WUXGA)  | 54        | 4.24%   |
| 1280x1024 (SXGA)   | 44        | 3.46%   |
| 1280x800 (WXGA)    | 33        | 2.59%   |
| 1680x1050 (WSXGA+) | 24        | 1.89%   |
| Unknown            | 24        | 1.89%   |
| 1440x900 (WXGA+)   | 21        | 1.65%   |
| 1024x600           | 16        | 1.26%   |
| 2560x1080          | 15        | 1.18%   |
| 3440x1440          | 14        | 1.1%    |
| 3840x1080          | 6         | 0.47%   |
| 2560x1600          | 6         | 0.47%   |
| 2256x1504          | 6         | 0.47%   |
| 1024x768 (XGA)     | 6         | 0.47%   |
| 3200x1800 (QHD+)   | 5         | 0.39%   |
| 1600x1200          | 5         | 0.39%   |
| 1920x540           | 4         | 0.31%   |
| 3840x1200          | 3         | 0.24%   |
| 3000x2000          | 3         | 0.24%   |
| 2880x1620          | 3         | 0.24%   |
| 2160x1440          | 3         | 0.24%   |
| 5760x1080          | 2         | 0.16%   |
| 2880x1800          | 2         | 0.16%   |
| 1400x1050          | 2         | 0.16%   |
| 1360x768           | 2         | 0.16%   |
| 1280x720 (HD)      | 2         | 0.16%   |
| 7680x2160          | 1         | 0.08%   |
| 5760x2160          | 1         | 0.08%   |
| 5760x1256          | 1         | 0.08%   |
| 5760x1200          | 1         | 0.08%   |
| 4480x1440          | 1         | 0.08%   |
| 4480x1080          | 1         | 0.08%   |
| 3840x1600          | 1         | 0.08%   |
| 3640x1920          | 1         | 0.08%   |
| 3600x1080          | 1         | 0.08%   |
| 3520x1200          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 243       | 18.85%  |
| 15      | 222       | 17.22%  |
| Unknown | 136       | 10.55%  |
| 24      | 105       | 8.15%   |
| 27      | 103       | 7.99%   |
| 21      | 69        | 5.35%   |
| 23      | 65        | 5.04%   |
| 12      | 62        | 4.81%   |
| 17      | 45        | 3.49%   |
| 19      | 38        | 2.95%   |
| 31      | 27        | 2.09%   |
| 14      | 26        | 2.02%   |
| 22      | 17        | 1.32%   |
| 11      | 17        | 1.32%   |
| 34      | 16        | 1.24%   |
| 18      | 15        | 1.16%   |
| 10      | 12        | 0.93%   |
| 20      | 10        | 0.78%   |
| 29      | 7         | 0.54%   |
| 64      | 4         | 0.31%   |
| 26      | 4         | 0.31%   |
| 9       | 4         | 0.31%   |
| 46      | 3         | 0.23%   |
| 42      | 3         | 0.23%   |
| 40      | 3         | 0.23%   |
| 32      | 3         | 0.23%   |
| 25      | 3         | 0.23%   |
| 16      | 3         | 0.23%   |
| 54      | 2         | 0.16%   |
| 52      | 2         | 0.16%   |
| 49      | 2         | 0.16%   |
| 48      | 2         | 0.16%   |
| 43      | 2         | 0.16%   |
| 41      | 2         | 0.16%   |
| 39      | 2         | 0.16%   |
| 74      | 1         | 0.08%   |
| 57      | 1         | 0.08%   |
| 55      | 1         | 0.08%   |
| 47      | 1         | 0.08%   |
| 37      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 421       | 33.1%   |
| 501-600     | 258       | 20.28%  |
| 201-300     | 184       | 14.47%  |
| Unknown     | 136       | 10.69%  |
| 401-500     | 125       | 9.83%   |
| 351-400     | 46        | 3.62%   |
| 601-700     | 45        | 3.54%   |
| 701-800     | 20        | 1.57%   |
| 1001-1500   | 19        | 1.49%   |
| 901-1000    | 7         | 0.55%   |
| 801-900     | 6         | 0.47%   |
| 101-200     | 3         | 0.24%   |
| 1501-2000   | 1         | 0.08%   |
| 1-100       | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 839       | 70.45%  |
| Unknown | 126       | 10.58%  |
| 16/10   | 119       | 9.99%   |
| 5/4     | 35        | 2.94%   |
| 21/9    | 25        | 2.1%    |
| 3/2     | 19        | 1.6%    |
| 4/3     | 18        | 1.51%   |
| 6/5     | 3         | 0.25%   |
| 32/9    | 2         | 0.17%   |
| 3.18    | 1         | 0.08%   |
| 11/10   | 1         | 0.08%   |
| 1.96    | 1         | 0.08%   |
| 1.00    | 1         | 0.08%   |
| 0.46    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 217       | 16.94%  |
| 201-250        | 209       | 16.32%  |
| 91-100         | 171       | 13.35%  |
| Unknown        | 136       | 10.62%  |
| 301-350        | 109       | 8.51%   |
| 61-70          | 63        | 4.92%   |
| 101-110        | 56        | 4.37%   |
| 151-200        | 53        | 4.14%   |
| 351-500        | 51        | 3.98%   |
| 251-300        | 43        | 3.36%   |
| 71-80          | 42        | 3.28%   |
| 141-150        | 30        | 2.34%   |
| 121-130        | 28        | 2.19%   |
| 501-1000       | 19        | 1.48%   |
| 51-60          | 16        | 1.25%   |
| 41-50          | 14        | 1.09%   |
| More than 1000 | 13        | 1.01%   |
| 1-40           | 4         | 0.31%   |
| 111-120        | 4         | 0.31%   |
| 131-140        | 3         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 367       | 29.24%  |
| 121-160       | 340       | 27.09%  |
| 101-120       | 268       | 21.35%  |
| Unknown       | 136       | 10.84%  |
| 161-240       | 105       | 8.37%   |
| More than 240 | 29        | 2.31%   |
| 1-50          | 10        | 0.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1066      | 48.02%  |
| 0     | 976       | 43.96%  |
| 2     | 164       | 7.39%   |
| 3     | 13        | 0.59%   |
| 4     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1303      | 43.81%  |
| Realtek Semiconductor             | 825       | 27.74%  |
| Broadcom                          | 247       | 8.31%   |
| Qualcomm Atheros                  | 245       | 8.24%   |
| Marvell Technology Group          | 35        | 1.18%   |
| Ralink Technology                 | 31        | 1.04%   |
| TP-Link                           | 27        | 0.91%   |
| Ralink                            | 15        | 0.5%    |
| Mellanox Technologies             | 15        | 0.5%    |
| Edimax Technology                 | 14        | 0.47%   |
| Nvidia                            | 12        | 0.4%    |
| MediaTek                          | 11        | 0.37%   |
| Xiaomi                            | 10        | 0.34%   |
| D-Link System                     | 10        | 0.34%   |
| VIA Technologies                  | 9         | 0.3%    |
| Sierra Wireless                   | 8         | 0.27%   |
| Hewlett-Packard                   | 8         | 0.27%   |
| Ericsson Business Mobile Networks | 8         | 0.27%   |
| Aquantia                          | 8         | 0.27%   |
| Samsung Electronics               | 7         | 0.24%   |
| Dell                              | 6         | 0.2%    |
| IBM                               | 5         | 0.17%   |
| Google                            | 5         | 0.17%   |
| Chelsio Communications            | 5         | 0.17%   |
| Arduino SA                        | 5         | 0.17%   |
| Apple                             | 5         | 0.17%   |
| American Megatrends               | 5         | 0.17%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.13%   |
| Qualcomm                          | 4         | 0.13%   |
| NetGear                           | 4         | 0.13%   |
| Huawei Technologies               | 4         | 0.13%   |
| Emulex                            | 4         | 0.13%   |
| D-Link                            | 4         | 0.13%   |
| 3Com                              | 4         | 0.13%   |
| IMC Networks                      | 3         | 0.1%    |
| Dresden Elektronik                | 3         | 0.1%    |
| Cisco Systems                     | 3         | 0.1%    |
| AMD                               | 3         | 0.1%    |
| Solarflare Communications         | 2         | 0.07%   |
| Qualcomm Atheros Communications   | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 615       | 16.82%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 130       | 3.55%   |
| Intel I211 Gigabit Network Connection                                         | 89        | 2.43%   |
| Intel Wireless 8265 / 8275                                                    | 85        | 2.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 83        | 2.27%   |
| Intel Wi-Fi 6 AX200                                                           | 80        | 2.19%   |
| Intel I210 Gigabit Network Connection                                         | 73        | 2%      |
| Intel 82574L Gigabit Network Connection                                       | 64        | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 59        | 1.61%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 56        | 1.53%   |
| Intel Wireless 7265                                                           | 53        | 1.45%   |
| Intel Wireless 8260                                                           | 52        | 1.42%   |
| Intel I350 Gigabit Network Connection                                         | 48        | 1.31%   |
| Intel Ethernet Connection I217-LM                                             | 41        | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                             | 39        | 1.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 38        | 1.04%   |
| Intel Wireless 7260                                                           | 38        | 1.04%   |
| Intel Wireless-AC 9260                                                        | 37        | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                                         | 34        | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 31        | 0.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 30        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 30        | 0.82%   |
| Intel Wi-Fi 6 AX201                                                           | 28        | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 26        | 0.71%   |
| Intel 82579V Gigabit Network Connection                                       | 26        | 0.71%   |
| Intel Ethernet Connection I219-LM                                             | 25        | 0.68%   |
| Intel Ethernet Connection (4) I219-V                                          | 25        | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                                         | 25        | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 25        | 0.68%   |
| Intel Ethernet Controller I225-V                                              | 23        | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                                         | 23        | 0.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 23        | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 22        | 0.6%    |
| Intel Ethernet Connection (2) I219-V                                          | 22        | 0.6%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 22        | 0.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 21        | 0.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 21        | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 21        | 0.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 20        | 0.55%   |
| Intel Centrino Ultimate-N 6300                                                | 20        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 749       | 56.96%  |
| Qualcomm Atheros                      | 199       | 15.13%  |
| Realtek Semiconductor                 | 144       | 10.95%  |
| Broadcom                              | 88        | 6.69%   |
| Ralink Technology                     | 31        | 2.36%   |
| TP-Link                               | 27        | 2.05%   |
| Ralink                                | 15        | 1.14%   |
| Edimax Technology                     | 14        | 1.06%   |
| MediaTek                              | 11        | 0.84%   |
| Sierra Wireless                       | 6         | 0.46%   |
| NetGear                               | 4         | 0.3%    |
| D-Link System                         | 4         | 0.3%    |
| D-Link                                | 4         | 0.3%    |
| IMC Networks                          | 3         | 0.23%   |
| Dell                                  | 3         | 0.23%   |
| Qualcomm Atheros Communications       | 2         | 0.15%   |
| Atheros                               | 2         | 0.15%   |
| ASUSTek Computer                      | 2         | 0.15%   |
| AboCom Systems                        | 2         | 0.15%   |
| Sagem                                 | 1         | 0.08%   |
| Marvell Technology Group              | 1         | 0.08%   |
| Linksys                               | 1         | 0.08%   |
| BUFFALO                               | 1         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 85        | 6.42%   |
| Intel Wi-Fi 6 AX200                                                     | 80        | 6.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 59        | 4.45%   |
| Intel Wireless 7265                                                     | 53        | 4%      |
| Intel Wireless 8260                                                     | 52        | 3.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 38        | 2.87%   |
| Intel Wireless 7260                                                     | 38        | 2.87%   |
| Intel Wireless-AC 9260                                                  | 37        | 2.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 31        | 2.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 30        | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 30        | 2.26%   |
| Intel Wi-Fi 6 AX201                                                     | 28        | 2.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 26        | 1.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 25        | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 23        | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 1.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 21        | 1.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 21        | 1.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 21        | 1.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 20        | 1.51%   |
| Intel Wireless 3165                                                     | 19        | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 19        | 1.43%   |
| Intel Centrino Ultimate-N 6300                                          | 19        | 1.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 16        | 1.21%   |
| Ralink RT5370 Wireless Adapter                                          | 15        | 1.13%   |
| Intel Wireless 3160                                                     | 15        | 1.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 1.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 14        | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 0.91%   |
| Intel Centrino Advanced-N 6235                                          | 12        | 0.91%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 12        | 0.91%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 11        | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 0.83%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 11        | 0.83%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 11        | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 10        | 0.75%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 10        | 0.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 9         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 932       | 44.55%  |
| Realtek Semiconductor             | 756       | 36.14%  |
| Broadcom                          | 183       | 8.75%   |
| Qualcomm Atheros                  | 72        | 3.44%   |
| Marvell Technology Group          | 34        | 1.63%   |
| Nvidia                            | 12        | 0.57%   |
| Xiaomi                            | 10        | 0.48%   |
| VIA Technologies                  | 9         | 0.43%   |
| Aquantia                          | 8         | 0.38%   |
| Samsung Electronics               | 7         | 0.33%   |
| D-Link System                     | 6         | 0.29%   |
| Chelsio Communications            | 5         | 0.24%   |
| American Megatrends               | 5         | 0.24%   |
| Qualcomm                          | 4         | 0.19%   |
| Google                            | 4         | 0.19%   |
| Emulex                            | 4         | 0.19%   |
| Apple                             | 4         | 0.19%   |
| 3Com                              | 4         | 0.19%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.14%   |
| Cisco Systems                     | 3         | 0.14%   |
| AMD                               | 3         | 0.14%   |
| Solarflare Communications         | 2         | 0.1%    |
| QLogic                            | 2         | 0.1%    |
| Lenovo                            | 2         | 0.1%    |
| JMicron Technology                | 2         | 0.1%    |
| ADMtek                            | 2         | 0.1%    |
| U.S. Robotics                     | 1         | 0.05%   |
| Tehuti Networks                   | 1         | 0.05%   |
| Sundance Technology Inc / IC Plus | 1         | 0.05%   |
| Realtek                           | 1         | 0.05%   |
| OPPO Electronics                  | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.05%   |
| National Semiconductor            | 1         | 0.05%   |
| MYRICOM                           | 1         | 0.05%   |
| Insyde Software                   | 1         | 0.05%   |
| Huawei Technologies               | 1         | 0.05%   |
| HMD Global                        | 1         | 0.05%   |
| Davicom Semiconductor             | 1         | 0.05%   |
| Amazon.com                        | 1         | 0.05%   |
| Accton Technology                 | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 615       | 27.47%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 130       | 5.81%   |
| Intel I211 Gigabit Network Connection                                         | 89        | 3.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 83        | 3.71%   |
| Intel I210 Gigabit Network Connection                                         | 73        | 3.26%   |
| Intel 82574L Gigabit Network Connection                                       | 64        | 2.86%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 56        | 2.5%    |
| Intel I350 Gigabit Network Connection                                         | 48        | 2.14%   |
| Intel Ethernet Connection I217-LM                                             | 41        | 1.83%   |
| Realtek RTL8125 2.5GbE Controller                                             | 36        | 1.61%   |
| Intel Ethernet Connection (2) I219-LM                                         | 34        | 1.52%   |
| Intel 82579V Gigabit Network Connection                                       | 26        | 1.16%   |
| Intel Ethernet Connection I219-LM                                             | 25        | 1.12%   |
| Intel Ethernet Connection (4) I219-V                                          | 25        | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                                         | 25        | 1.12%   |
| Intel Ethernet Controller I225-V                                              | 23        | 1.03%   |
| Intel Ethernet Connection (3) I218-LM                                         | 23        | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                          | 22        | 0.98%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 22        | 0.98%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 20        | 0.89%   |
| Intel Ethernet Connection (7) I219-V                                          | 18        | 0.8%    |
| Intel Ethernet Connection (7) I219-LM                                         | 16        | 0.71%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 15        | 0.67%   |
| Intel 82576 Gigabit Network Connection                                        | 15        | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 13        | 0.58%   |
| Intel Ethernet Connection I218-LM                                             | 13        | 0.58%   |
| Intel 82577LM Gigabit Network Connection                                      | 13        | 0.58%   |
| Intel Ethernet Connection (2) I218-V                                          | 12        | 0.54%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 12        | 0.54%   |
| Nvidia MCP79 Ethernet                                                         | 11        | 0.49%   |
| Intel Ethernet Controller X550                                                | 11        | 0.49%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 11        | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 10        | 0.45%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 10        | 0.45%   |
| Intel Ethernet Connection I219-V                                              | 10        | 0.45%   |
| Intel Ethernet Connection (6) I219-V                                          | 10        | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 9         | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 9         | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 9         | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 9         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1919      | 59.8%   |
| WiFi     | 1197      | 37.3%   |
| Modem    | 48        | 1.5%    |
| Unknown  | 45        | 1.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1706      | 67.7%   |
| WiFi     | 799       | 31.71%  |
| Unknown  | 10        | 0.4%    |
| Modem    | 5         | 0.2%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1137      | 51.92%  |
| 1     | 685       | 31.28%  |
| 3     | 115       | 5.25%   |
| 4     | 109       | 4.98%   |
| 0     | 85        | 3.88%   |
| 6     | 26        | 1.19%   |
| 5     | 19        | 0.87%   |
| 8     | 6         | 0.27%   |
| 7     | 5         | 0.23%   |
| 10    | 3         | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1973      | 89.11%  |
| Yes  | 241       | 10.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 520       | 59.84%  |
| Broadcom                        | 61        | 7.02%   |
| Qualcomm Atheros Communications | 53        | 6.1%    |
| Realtek Semiconductor           | 46        | 5.29%   |
| Apple                           | 41        | 4.72%   |
| Cambridge Silicon Radio         | 31        | 3.57%   |
| IMC Networks                    | 21        | 2.42%   |
| Foxconn / Hon Hai               | 20        | 2.3%    |
| ASUSTek Computer                | 18        | 2.07%   |
| Lite-On Technology              | 15        | 1.73%   |
| Dell                            | 14        | 1.61%   |
| Hewlett-Packard                 | 10        | 1.15%   |
| Skylight Digital                | 5         | 0.58%   |
| MediaTek                        | 4         | 0.46%   |
| Alps Electric                   | 4         | 0.46%   |
| Toshiba                         | 1         | 0.12%   |
| Ralink                          | 1         | 0.12%   |
| Opticis                         | 1         | 0.12%   |
| Micro Star International        | 1         | 0.12%   |
| Esel International              | 1         | 0.12%   |
| Creative Technology             | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 199       | 22.82%  |
| Intel AX200 Bluetooth                                       | 77        | 8.83%   |
| Intel AX201 Bluetooth                                       | 76        | 8.72%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 73        | 8.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 33        | 3.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 31        | 3.56%   |
| Intel Wireless-AC 3168 Bluetooth                            | 25        | 2.87%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 21        | 2.41%   |
| Apple Bluetooth Host Controller                             | 21        | 2.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 20        | 2.29%   |
| Realtek Bluetooth Adapter                                   | 18        | 2.06%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 14        | 1.61%   |
| Intel AX210 Bluetooth                                       | 14        | 1.61%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 12        | 1.38%   |
| Realtek  Bluetooth 4.2 Adapter                              | 10        | 1.15%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 10        | 1.15%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 10        | 1.15%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 8         | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 7         | 0.8%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 7         | 0.8%    |
| IMC Networks Realtek Bluetooth Adapter                      | 7         | 0.8%    |
| Dell DW375 Bluetooth Module                                 | 7         | 0.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 7         | 0.8%    |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 6         | 0.69%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 6         | 0.69%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 5         | 0.57%   |
| Realtek Bluetooth 4.2 Adapter                               | 5         | 0.57%   |
| Intel Wireless Bluetooth                                    | 5         | 0.57%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 5         | 0.57%   |
| Apple Built-in iSight (no firmware loaded)                  | 5         | 0.57%   |
| Realtek Bluetooth 4.0 Adapter                               | 4         | 0.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 4         | 0.46%   |
| Lite-On Atheros AR3012 Bluetooth                            | 4         | 0.46%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 4         | 0.46%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 4         | 0.46%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 3         | 0.34%   |
| Realtek RTL8723B Bluetooth                                  | 3         | 0.34%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 3         | 0.34%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 3         | 0.34%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 3         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1278      | 54.52%  |
| AMD                                          | 481       | 20.52%  |
| Nvidia                                       | 380       | 16.21%  |
| C-Media Electronics                          | 25        | 1.07%   |
| Logitech                                     | 20        | 0.85%   |
| Creative Labs                                | 16        | 0.68%   |
| Lenovo                                       | 12        | 0.51%   |
| Texas Instruments                            | 11        | 0.47%   |
| Realtek Semiconductor                        | 11        | 0.47%   |
| Silicon Integrated Systems [SiS]             | 6         | 0.26%   |
| Kingston Technology                          | 6         | 0.26%   |
| JMTek                                        | 6         | 0.26%   |
| GN Netcom                                    | 6         | 0.26%   |
| SteelSeries ApS                              | 5         | 0.21%   |
| ASUSTek Computer                             | 5         | 0.21%   |
| Sony                                         | 4         | 0.17%   |
| Plantronics                                  | 4         | 0.17%   |
| Generalplus Technology                       | 4         | 0.17%   |
| Focusrite-Novation                           | 4         | 0.17%   |
| Blue Microphones                             | 4         | 0.17%   |
| BEHRINGER International                      | 4         | 0.17%   |
| Thesycon Systemsoftware & Consulting         | 3         | 0.13%   |
| Tenx Technology                              | 3         | 0.13%   |
| M-Audio                                      | 3         | 0.13%   |
| Creative Technology                          | 3         | 0.13%   |
| Yamaha                                       | 2         | 0.09%   |
| VIA Technologies                             | 2         | 0.09%   |
| Trust                                        | 2         | 0.09%   |
| Microsoft                                    | 2         | 0.09%   |
| Micro Star International                     | 2         | 0.09%   |
| FiiO Electronics Technology                  | 2         | 0.09%   |
| Corsair                                      | 2         | 0.09%   |
| Cambridge Silicon Radio                      | 2         | 0.09%   |
| Apple                                        | 2         | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.04%   |
| XMOS                                         | 1         | 0.04%   |
| Xilinx                                       | 1         | 0.04%   |
| ULi Electronics                              | 1         | 0.04%   |
| Samsung Electronics                          | 1         | 0.04%   |
| ROCCAT                                       | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 153       | 5.52%   |
| AMD Family 17h/19h HD Audio Controller                                     | 144       | 5.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 133       | 4.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 120       | 4.33%   |
| AMD Starship/Matisse HD Audio Controller                                   | 82        | 2.96%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 82        | 2.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 76        | 2.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 68        | 2.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 61        | 2.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 61        | 2.2%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 60        | 2.17%   |
| Intel Broadwell-U Audio Controller                                         | 55        | 1.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 51        | 1.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 50        | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 48        | 1.73%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 48        | 1.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 45        | 1.62%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 43        | 1.55%   |
| Intel Haswell-ULT HD Audio Controller                                      | 39        | 1.41%   |
| Intel 8 Series HD Audio Controller                                         | 39        | 1.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 38        | 1.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 37        | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 37        | 1.34%   |
| Intel Comet Lake PCH-LP cAVS                                               | 35        | 1.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 34        | 1.23%   |
| Intel Comet Lake PCH cAVS                                                  | 34        | 1.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 33        | 1.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 33        | 1.19%   |
| AMD FCH Azalia Controller                                                  | 33        | 1.19%   |
| Intel 200 Series PCH HD Audio                                              | 29        | 1.05%   |
| AMD Kabini HDMI/DP Audio                                                   | 28        | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 27        | 0.97%   |
| Nvidia TU116 High Definition Audio Controller                              | 26        | 0.94%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 25        | 0.9%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 23        | 0.83%   |
| Nvidia GP108 High Definition Audio Controller                              | 22        | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 22        | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 20        | 0.72%   |
| Nvidia High Definition Audio Controller                                    | 19        | 0.69%   |
| Nvidia GF119 HDMI Audio Controller                                         | 18        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 507       | 21.25%  |
| SK hynix                     | 389       | 16.3%   |
| Kingston                     | 295       | 12.36%  |
| Unknown                      | 263       | 11.02%  |
| Micron Technology            | 217       | 9.09%   |
| Crucial                      | 152       | 6.37%   |
| Corsair                      | 135       | 5.66%   |
| G.Skill                      | 73        | 3.06%   |
| Unknown                      | 45        | 1.89%   |
| Ramaxel Technology           | 38        | 1.59%   |
| A-DATA Technology            | 35        | 1.47%   |
| Elpida                       | 23        | 0.96%   |
| Nanya Technology             | 21        | 0.88%   |
| Transcend                    | 15        | 0.63%   |
| Team                         | 15        | 0.63%   |
| Goodram                      | 15        | 0.63%   |
| Patriot                      | 14        | 0.59%   |
| Hewlett-Packard              | 13        | 0.54%   |
| Unknown (ABCD)               | 8         | 0.34%   |
| Avant                        | 8         | 0.34%   |
| Super Talent                 | 6         | 0.25%   |
| Smart                        | 6         | 0.25%   |
| PNY                          | 6         | 0.25%   |
| Neo Forza                    | 5         | 0.21%   |
| Goldkey                      | 5         | 0.21%   |
| Qimonda                      | 4         | 0.17%   |
| Patriot Memory (PDP Systems) | 4         | 0.17%   |
| AMD                          | 4         | 0.17%   |
| 48spaces                     | 4         | 0.17%   |
| HPE                          | 3         | 0.13%   |
| Golden Empire                | 3         | 0.13%   |
| Apacer                       | 3         | 0.13%   |
| V-GeN                        | 2         | 0.08%   |
| V-Color                      | 2         | 0.08%   |
| Toshiba                      | 2         | 0.08%   |
| Tigo                         | 2         | 0.08%   |
| Silicon Power                | 2         | 0.08%   |
| PUSKILL                      | 2         | 0.08%   |
| KomputerBay                  | 2         | 0.08%   |
| Kllisre                      | 2         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 45        | 1.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 19        | 0.73%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 19        | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 17        | 0.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 17        | 0.65%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 17        | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 15        | 0.57%   |
| Samsung RAM M393B1G70QH0-YK0 8192MB DIMM DDR3 1600MT/s       | 15        | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 14        | 0.54%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 13        | 0.5%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 12        | 0.46%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s        | 12        | 0.46%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 11        | 0.42%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 11        | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 10        | 0.38%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 10        | 0.38%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 10        | 0.38%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s        | 10        | 0.38%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 9         | 0.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 9         | 0.34%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s        | 9         | 0.34%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 8         | 0.31%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s        | 8         | 0.31%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s        | 8         | 0.31%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 8         | 0.31%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s        | 8         | 0.31%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 7         | 0.27%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s         | 7         | 0.27%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 7         | 0.27%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s       | 7         | 0.27%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 7         | 0.27%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 7         | 0.27%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 6         | 0.23%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                         | 6         | 0.23%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                 | 6         | 0.23%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 6         | 0.23%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 6         | 0.23%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 6         | 0.23%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 1333MT/s             | 6         | 0.23%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s          | 6         | 0.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 863       | 41.75%  |
| DDR3         | 820       | 39.67%  |
| DDR2         | 140       | 6.77%   |
| Unknown      | 70        | 3.39%   |
| LPDDR3       | 48        | 2.32%   |
| SDRAM        | 36        | 1.74%   |
| LPDDR4       | 35        | 1.69%   |
| DDR          | 34        | 1.64%   |
| DRAM         | 7         | 0.34%   |
| DDR5         | 7         | 0.34%   |
| LPDDR5       | 4         | 0.19%   |
| SRAM         | 1         | 0.05%   |
| RAM          | 1         | 0.05%   |
| DDR2 FB-DIMM | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 976       | 47.2%   |
| SODIMM       | 965       | 46.66%  |
| Row Of Chips | 81        | 3.92%   |
| Chip         | 27        | 1.31%   |
| Unknown      | 7         | 0.34%   |
| RIMM         | 6         | 0.29%   |
| FB-DIMM      | 6         | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 797       | 35.14%  |
| 4096   | 583       | 25.71%  |
| 16384  | 372       | 16.4%   |
| 2048   | 292       | 12.87%  |
| 32768  | 95        | 4.19%   |
| 1024   | 91        | 4.01%   |
| 512    | 23        | 1.01%   |
| 256    | 5         | 0.22%   |
| 65536  | 3         | 0.13%   |
| 128    | 2         | 0.09%   |
| 131072 | 1         | 0.04%   |
| 2560   | 1         | 0.04%   |
| 64     | 1         | 0.04%   |
| 32     | 1         | 0.04%   |
| 8      | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 483       | 21.93%  |
| 1333    | 269       | 12.22%  |
| 3200    | 249       | 11.31%  |
| 2400    | 223       | 10.13%  |
| 2667    | 202       | 9.17%   |
| 2133    | 187       | 8.49%   |
| 667     | 80        | 3.63%   |
| 800     | 75        | 3.41%   |
| Unknown | 59        | 2.68%   |
| 1334    | 50        | 2.27%   |
| 1867    | 43        | 1.95%   |
| 2666    | 38        | 1.73%   |
| 1067    | 32        | 1.45%   |
| 1066    | 27        | 1.23%   |
| 533     | 26        | 1.18%   |
| 3000    | 20        | 0.91%   |
| 4267    | 19        | 0.86%   |
| 2933    | 18        | 0.82%   |
| 3600    | 17        | 0.77%   |
| 1866    | 12        | 0.54%   |
| 400     | 8         | 0.36%   |
| 975     | 6         | 0.27%   |
| 266     | 6         | 0.27%   |
| 4800    | 5         | 0.23%   |
| 6400    | 4         | 0.18%   |
| 4266    | 4         | 0.18%   |
| 3400    | 4         | 0.18%   |
| 2134    | 4         | 0.18%   |
| 2048    | 4         | 0.18%   |
| 4000    | 3         | 0.14%   |
| 333     | 3         | 0.14%   |
| 5200    | 2         | 0.09%   |
| 3534    | 2         | 0.09%   |
| 1639    | 2         | 0.09%   |
| 1332    | 2         | 0.09%   |
| 65535   | 1         | 0.05%   |
| 4133    | 1         | 0.05%   |
| 3500    | 1         | 0.05%   |
| 3066    | 1         | 0.05%   |
| 2800    | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 4         | 28.57%  |
| Hewlett-Packard     | 2         | 14.29%  |
| ELGIN               | 2         | 14.29%  |
| Seiko Epson         | 1         | 7.14%   |
| Samsung Electronics | 1         | 7.14%   |
| QinHeng Electronics | 1         | 7.14%   |
| Prolific Technology | 1         | 7.14%   |
| Dymo-CoStar         | 1         | 7.14%   |
| Canon               | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| ELGIN L42PRO                                                                               | 2         | 14.29%  |
| Seiko Epson Printer                                                                        | 1         | 7.14%   |
| Samsung ML-1610 Mono Laser Printer                                                         | 1         | 7.14%   |
| QinHeng CH340S                                                                             | 1         | 7.14%   |
| Prolific PL2305 Parallel Port                                                              | 1         | 7.14%   |
| HP LaserJet 1012                                                                           | 1         | 7.14%   |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer | 1         | 7.14%   |
| Dymo-CoStar LabelWriter 450                                                                | 1         | 7.14%   |
| Canon LBP2900                                                                              | 1         | 7.14%   |
| Brother MFC-7360N                                                                          | 1         | 7.14%   |
| Brother HL-L5200DW series                                                                  | 1         | 7.14%   |
| Brother HL-2030 Laser Printer                                                              | 1         | 7.14%   |
| Brother HL-1430 Laser Printer                                                              | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 66.67%  |
| Seiko Epson     | 1         | 16.67%  |
| Hewlett-Packard | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 2         | 33.33%  |
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 16.67%  |
| HP ScanJet 5300c/5370c                                                              | 1         | 16.67%  |
| Canon CanoScan LIDE 25                                                              | 1         | 16.67%  |
| Canon CanoScan LiDE 220                                                             | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 222       | 28.35%  |
| IMC Networks                           | 82        | 10.47%  |
| Microdia                               | 78        | 9.96%   |
| Bison Electronics                      | 71        | 9.07%   |
| Realtek Semiconductor                  | 58        | 7.41%   |
| Sunplus Innovation Technology          | 47        | 6%      |
| Logitech                               | 40        | 5.11%   |
| Lite-On Technology                     | 23        | 2.94%   |
| Suyin                                  | 22        | 2.81%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 2.04%   |
| Syntek                                 | 15        | 1.92%   |
| Quanta                                 | 13        | 1.66%   |
| Apple                                  | 12        | 1.53%   |
| Silicon Motion                         | 8         | 1.02%   |
| Luxvisions Innotech Limited            | 8         | 1.02%   |
| Lenovo                                 | 8         | 1.02%   |
| Z-Star Microelectronics                | 6         | 0.77%   |
| ALi                                    | 5         | 0.64%   |
| Importek                               | 4         | 0.51%   |
| Alcor Micro                            | 4         | 0.51%   |
| Supreme Electronics                    | 3         | 0.38%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.38%   |
| Ricoh                                  | 3         | 0.38%   |
| ARC International                      | 3         | 0.38%   |
| WCM_USB                                | 2         | 0.26%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.26%   |
| Primax Electronics                     | 2         | 0.26%   |
| Pixart Imaging                         | 2         | 0.26%   |
| OmniVision Technologies                | 2         | 0.26%   |
| Jiangxi Shinetech Optical              | 2         | 0.26%   |
| Intel                                  | 2         | 0.26%   |
| Cubeternet                             | 2         | 0.26%   |
| YGTek                                  | 1         | 0.13%   |
| Valve Software                         | 1         | 0.13%   |
| USB Camera                             | 1         | 0.13%   |
| Unknown                                | 1         | 0.13%   |
| Trust                                  | 1         | 0.13%   |
| Sonix Technology                       | 1         | 0.13%   |
| Huawei Technologies                    | 1         | 0.13%   |
| Goodong Industry                       | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 69        | 8.7%    |
| Bison Integrated Camera                       | 38        | 4.79%   |
| IMC Networks Integrated Camera                | 30        | 3.78%   |
| Microdia Integrated_Webcam_HD                 | 19        | 2.4%    |
| Realtek Integrated_Webcam_HD                  | 18        | 2.27%   |
| Microdia Integrated Webcam                    | 18        | 2.27%   |
| Chicony HD WebCam                             | 18        | 2.27%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 16        | 2.02%   |
| Sunplus Integrated_Webcam_HD                  | 13        | 1.64%   |
| Logitech Webcam C270                          | 13        | 1.64%   |
| Lite-On Integrated Camera                     | 13        | 1.64%   |
| Chicony Integrated Camera (1280x720@30)       | 13        | 1.64%   |
| Realtek USB 2.0 PC Camera                     | 11        | 1.39%   |
| IMC Networks Realtek PC Camera                | 10        | 1.26%   |
| IMC Networks EasyCamera                       | 9         | 1.13%   |
| Chicony Realtek DMFT RGB                      | 9         | 1.13%   |
| Logitech HD Pro Webcam C920                   | 8         | 1.01%   |
| Chicony Chicony USB2.0 Camera                 | 8         | 1.01%   |
| Syntek Integrated Camera                      | 7         | 0.88%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 7         | 0.88%   |
| Sunplus HD WebCam                             | 7         | 0.88%   |
| Chicony ThinkPad T490 Webcam                  | 7         | 0.88%   |
| Chicony Integrated IR Camera                  | 7         | 0.88%   |
| Bison SunplusIT Integrated Camera             | 7         | 0.88%   |
| Bison Lenovo EasyCamera                       | 7         | 0.88%   |
| Microdia Integrated Webcam HD                 | 6         | 0.76%   |
| IMC Networks Integrated Webcam                | 6         | 0.76%   |
| Apple FaceTime HD Camera                      | 6         | 0.76%   |
| Syntek EasyCamera                             | 5         | 0.63%   |
| Sunplus Laptop Integrated WebCam HD           | 5         | 0.63%   |
| Quanta HD Webcam                              | 5         | 0.63%   |
| Lenovo Integrated Webcam [R5U877]             | 5         | 0.63%   |
| IMC Networks UVC VGA Webcam                   | 5         | 0.63%   |
| Chicony Integrated Camera [ThinkPad]          | 5         | 0.63%   |
| Bison ThinkPad Integrated Camera              | 5         | 0.63%   |
| Apple FaceTime HD Camera (Built-in)           | 5         | 0.63%   |
| Realtek Integrated Webcam                     | 4         | 0.5%    |
| Microdia Webcam Vitade AF                     | 4         | 0.5%    |
| Microdia Dell Laptop Integrated Webcam HD     | 4         | 0.5%    |
| Luxvisions Innotech Limited Integrated Camera | 4         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 70        | 31.96%  |
| Synaptics                  | 58        | 26.48%  |
| Shenzhen Goodix Technology | 28        | 12.79%  |
| Upek                       | 20        | 9.13%   |
| STMicroelectronics         | 10        | 4.57%   |
| AuthenTec                  | 10        | 4.57%   |
| Broadcom                   | 8         | 3.65%   |
| LighTuning Technology      | 6         | 2.74%   |
| FocalTech Systems          | 5         | 2.28%   |
| Elan Microelectronics      | 2         | 0.91%   |
| Samsung Electronics        | 1         | 0.46%   |
| DigitalPersona             | 1         | 0.46%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 25        | 11.42%  |
| Shenzhen Goodix Fingerprint Reader                                           | 21        | 9.59%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 20        | 9.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 20        | 9.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 20        | 9.13%   |
| Validity Sensors Synaptics WBDI                                              | 17        | 7.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 10        | 4.57%   |
| STMicroelectronics Fingerprint Reader                                        | 10        | 4.57%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 3.65%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 7         | 3.2%    |
| Validity Sensors VFS495 Fingerprint Reader                                   | 6         | 2.74%   |
| Shenzhen Goodix  Fingerprint Device                                          | 5         | 2.28%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 5         | 2.28%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 4         | 1.83%   |
| FocalTech Systems Fingerprint Reader                                         | 4         | 1.83%   |
| AuthenTec AES1660                                                            | 4         | 1.83%   |
| Synaptics UWP WBDI                                                           | 3         | 1.37%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 3         | 1.37%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 3         | 1.37%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 0.91%   |
| Validity Sensors VFS Fingerprint sensor                                      | 2         | 0.91%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 2         | 0.91%   |
| Synaptics WBDI                                                               | 2         | 0.91%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 2         | 0.91%   |
| Elan Fingerprint Sensor                                                      | 2         | 0.91%   |
| AuthenTec AES2810                                                            | 2         | 0.91%   |
| Validity Sensors VFS491                                                      | 1         | 0.46%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 0.46%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 0.46%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 0.46%   |
| Synaptics WBDI Fingerprint Reader USB 102                                    | 1         | 0.46%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 0.46%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 0.46%   |
| FocalTech Systems FocalTech Fingerprint Device                               | 1         | 0.46%   |
| DigitalPersona Fingerprint Reader                                            | 1         | 0.46%   |
| AuthenTec AES2660                                                            | 1         | 0.46%   |

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
| 1     | 714       | 31.72%  |
| 0     | 642       | 28.52%  |
| 2     | 508       | 22.57%  |
| 3     | 255       | 11.33%  |
| 4     | 99        | 4.4%    |
| 5     | 19        | 0.84%   |
| 6     | 11        | 0.49%   |
| 7     | 2         | 0.09%   |
| 9     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1218      | 46.17%  |
| Bluetooth                | 373       | 14.14%  |
| Net/wireless             | 293       | 11.11%  |
| Card reader              | 237       | 8.98%   |
| Fingerprint reader       | 213       | 8.07%   |
| Firewire controller      | 155       | 5.88%   |
| Sound                    | 38        | 1.44%   |
| Net/ethernet             | 36        | 1.36%   |
| Network                  | 31        | 1.18%   |
| Storage                  | 20        | 0.76%   |
| Modem                    | 14        | 0.53%   |
| Dvb card                 | 5         | 0.19%   |
| Storage/ide              | 2         | 0.08%   |
| Storage/raid             | 1         | 0.04%   |
| Storage/nvme             | 1         | 0.04%   |
| Graphics card            | 1         | 0.04%   |

