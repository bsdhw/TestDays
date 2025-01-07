helloSystem 0.6.0 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.6.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 75

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| Gigabyte  | GA-78LMT-USB3               | [a7fe22ce82](https://bsd-hardware.info/?probe=a7fe22ce82) | May 13, 2023 |
| HP        | 3048h                       | [3f43816a5d](https://bsd-hardware.info/?probe=3f43816a5d) | Nov 25, 2022 |
| ASUSTek   | P6-P8H61E                   | [540f66f678](https://bsd-hardware.info/?probe=540f66f678) | Mar 29, 2022 |
| Dell      | 0GXM1W A00                  | [c4d10a26fd](https://bsd-hardware.info/?probe=c4d10a26fd) | Mar 04, 2022 |
| Intel     | H81                         | [dd19abd47d](https://bsd-hardware.info/?probe=dd19abd47d) | Feb 25, 2022 |
| Dell      | 014GRG A03                  | [8e0a22c065](https://bsd-hardware.info/?probe=8e0a22c065) | Jan 28, 2022 |
| Dell      | 014GRG A03                  | [5996ba19b1](https://bsd-hardware.info/?probe=5996ba19b1) | Jan 27, 2022 |
| Dell      | 014GRG A03                  | [223d955a90](https://bsd-hardware.info/?probe=223d955a90) | Jan 26, 2022 |
| Dell      | 05DN3X A00                  | [e0e63e69ef](https://bsd-hardware.info/?probe=e0e63e69ef) | Jan 23, 2022 |
| Dell      | 05DN3X A00                  | [460ea5c41d](https://bsd-hardware.info/?probe=460ea5c41d) | Jan 23, 2022 |
| ASUSTek   | M5A78L/USB3                 | [f1fe3fe225](https://bsd-hardware.info/?probe=f1fe3fe225) | Dec 30, 2021 |
| ASUSTek   | H110M-K                     | [2921401f70](https://bsd-hardware.info/?probe=2921401f70) | Dec 12, 2021 |
| HP        | 8054                        | [de953100f6](https://bsd-hardware.info/?probe=de953100f6) | Dec 10, 2021 |
| MSI       | MPG B550 GAMING EDGE WIF... | [a9423b3232](https://bsd-hardware.info/?probe=a9423b3232) | Dec 09, 2021 |
| ASUSTek   | Pro WS X570-ACE             | [35b01f0f56](https://bsd-hardware.info/?probe=35b01f0f56) | Dec 05, 2021 |
| Fujitsu   | D3220-A1 S26361-D3220-A1    | [bc3b65334e](https://bsd-hardware.info/?probe=bc3b65334e) | Nov 29, 2021 |
| ASRock    | AB350 Pro4                  | [ef35dd084e](https://bsd-hardware.info/?probe=ef35dd084e) | Nov 26, 2021 |
| HP        | 0A80h                       | [1e1153ee69](https://bsd-hardware.info/?probe=1e1153ee69) | Nov 22, 2021 |
| ASUSTek   | ROG STRIX X470-F GAMING     | [afd0cf45c6](https://bsd-hardware.info/?probe=afd0cf45c6) | Nov 21, 2021 |
| ASUSTek   | TUF GAMING X570-PLUS        | [12a360ddd1](https://bsd-hardware.info/?probe=12a360ddd1) | Nov 14, 2021 |
| T-bao     | MINI PC V1.0                | [4ee7de3597](https://bsd-hardware.info/?probe=4ee7de3597) | Nov 12, 2021 |
| Itautec   | ST 4344 ST-4344 Padrao 0... | [ec13cb0829](https://bsd-hardware.info/?probe=ec13cb0829) | Nov 07, 2021 |
| Shuttle   | FH61R                       | [a231590743](https://bsd-hardware.info/?probe=a231590743) | Nov 07, 2021 |
| ASUSTek   | M5A78L-M/USB3               | [7e27b1bc46](https://bsd-hardware.info/?probe=7e27b1bc46) | Nov 07, 2021 |
| Intel     | H81                         | [7f07aecffc](https://bsd-hardware.info/?probe=7f07aecffc) | Nov 07, 2021 |
| ASRock    | X370 Gaming X               | [2a874a33dd](https://bsd-hardware.info/?probe=2a874a33dd) | Nov 05, 2021 |
| Lenovo    | SHARKBAY No DPK             | [b9ad64f354](https://bsd-hardware.info/?probe=b9ad64f354) | Nov 04, 2021 |
| Gigabyte  | F2A78M-DS2                  | [45576fddfa](https://bsd-hardware.info/?probe=45576fddfa) | Nov 02, 2021 |
| Dell      | 0M5DCD A02                  | [4ff4198768](https://bsd-hardware.info/?probe=4ff4198768) | Nov 02, 2021 |
| Gateway   | DX4840                      | [1d2e9e175c](https://bsd-hardware.info/?probe=1d2e9e175c) | Nov 01, 2021 |
| ASRock    | X300M-STX                   | [e25f042400](https://bsd-hardware.info/?probe=e25f042400) | Oct 30, 2021 |
| Unknown   | Intel X79                   | [044908e7c3](https://bsd-hardware.info/?probe=044908e7c3) | Oct 30, 2021 |
| ASUSTek   | TUF GAMING X570-PLUS        | [9f8010bdbe](https://bsd-hardware.info/?probe=9f8010bdbe) | Oct 25, 2021 |
| ASUSTek   | TUF B450M-PRO GAMING        | [9959c0900a](https://bsd-hardware.info/?probe=9959c0900a) | Oct 23, 2021 |
| Gigabyte  | H410M S2 V2                 | [b106820e47](https://bsd-hardware.info/?probe=b106820e47) | Oct 21, 2021 |
| Acer      | RS880M05                    | [4718f0cb0c](https://bsd-hardware.info/?probe=4718f0cb0c) | Oct 21, 2021 |
| Apple     | Mac-F221BEC8                | [cb2cc35e6c](https://bsd-hardware.info/?probe=cb2cc35e6c) | Oct 19, 2021 |
| Gigabyte  | 990FXA-UD3                  | [3cf20ca77c](https://bsd-hardware.info/?probe=3cf20ca77c) | Oct 19, 2021 |
| Dell      | 0VRWRC A00                  | [9b4defb194](https://bsd-hardware.info/?probe=9b4defb194) | Oct 19, 2021 |
| HP        | 3398                        | [892f19c9bd](https://bsd-hardware.info/?probe=892f19c9bd) | Oct 18, 2021 |
| ASUSTek   | CROSSHAIR V FORMULA-Z       | [0cdd3497f6](https://bsd-hardware.info/?probe=0cdd3497f6) | Oct 18, 2021 |
| Gigabyte  | G41MT-S2                    | [2847d63db0](https://bsd-hardware.info/?probe=2847d63db0) | Oct 18, 2021 |
| ASUSTek   | P5P43TD PRO                 | [2870e26de1](https://bsd-hardware.info/?probe=2870e26de1) | Oct 17, 2021 |
| Lenovo    | SHARKBAY No DPK             | [14dcd924b5](https://bsd-hardware.info/?probe=14dcd924b5) | Oct 13, 2021 |
| Medion    | H61H2-LM3                   | [67ed0f639c](https://bsd-hardware.info/?probe=67ed0f639c) | Oct 10, 2021 |
| ASUSTek   | H81M-K                      | [e24f67a603](https://bsd-hardware.info/?probe=e24f67a603) | Oct 08, 2021 |
| MSI       | G41M-P25                    | [21eec496b4](https://bsd-hardware.info/?probe=21eec496b4) | Oct 08, 2021 |
| ASRock    | A320M-DGS                   | [11cf5c923a](https://bsd-hardware.info/?probe=11cf5c923a) | Oct 08, 2021 |
| Gigabyte  | B450 AORUS M                | [d09f63f257](https://bsd-hardware.info/?probe=d09f63f257) | Oct 07, 2021 |
| Intel     | H61                         | [6ce71c1b9e](https://bsd-hardware.info/?probe=6ce71c1b9e) | Oct 06, 2021 |
| HP        | 3397                        | [4c71aae5bf](https://bsd-hardware.info/?probe=4c71aae5bf) | Oct 05, 2021 |
| ASRock    | B365M-ITX/ac                | [1c8820a6d0](https://bsd-hardware.info/?probe=1c8820a6d0) | Oct 04, 2021 |
| MSI       | B450I GAMING PLUS AC        | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| MSI       | MPG X570 GAMING PRO CARB... | [bd312d1c88](https://bsd-hardware.info/?probe=bd312d1c88) | Oct 03, 2021 |
| HP        | ProLiant ML350 G5           | [4d525cba3e](https://bsd-hardware.info/?probe=4d525cba3e) | Oct 03, 2021 |
| ASRock    | X570 Phantom Gaming 4       | [9b14548c15](https://bsd-hardware.info/?probe=9b14548c15) | Sep 21, 2021 |
| Sapphire  | EDGE-FT1M1 E450 1AOVU044    | [ea8fefdf4e](https://bsd-hardware.info/?probe=ea8fefdf4e) | Sep 20, 2021 |
| Dell      | 0MGK50 A02                  | [9d2959b4f1](https://bsd-hardware.info/?probe=9d2959b4f1) | Sep 20, 2021 |
| HP        | 81B4 01                     | [179504116d](https://bsd-hardware.info/?probe=179504116d) | Sep 20, 2021 |
| ASRock    | B450 Gaming-ITX/ac          | [790d020ebe](https://bsd-hardware.info/?probe=790d020ebe) | Sep 19, 2021 |
| Gigabyte  | H270M-DS3H-CF               | [9b046b157e](https://bsd-hardware.info/?probe=9b046b157e) | Sep 17, 2021 |
| ASUSTek   | PRIME B360M-C               | [0f6e7e26fc](https://bsd-hardware.info/?probe=0f6e7e26fc) | Sep 11, 2021 |
| HP        | 3397                        | [5d95b75768](https://bsd-hardware.info/?probe=5d95b75768) | Sep 06, 2021 |
| Medion    | H61H2-LM3                   | [eb81abe401](https://bsd-hardware.info/?probe=eb81abe401) | Sep 02, 2021 |
| ASRock    | Z390 Pro4                   | [ecbf097bc5](https://bsd-hardware.info/?probe=ecbf097bc5) | Sep 02, 2021 |
| ASUSTek   | TUF B360M-PLUS GAMING S     | [33ba0b7c38](https://bsd-hardware.info/?probe=33ba0b7c38) | Aug 29, 2021 |
| ASUSTek   | P7H55-M LX                  | [5fe1a9e521](https://bsd-hardware.info/?probe=5fe1a9e521) | Aug 16, 2021 |
| PCPartner | MILANO-P Rev.00             | [ef8217ac30](https://bsd-hardware.info/?probe=ef8217ac30) | Aug 01, 2021 |
| ASUSTek   | H110M-PLUS                  | [d0f2da9c41](https://bsd-hardware.info/?probe=d0f2da9c41) | Jul 21, 2021 |
| Gigabyte  | H110-D3A-CF                 | [2c390b4301](https://bsd-hardware.info/?probe=2c390b4301) | Jul 09, 2021 |
| Gigabyte  | H110-D3A-CF                 | [aea3a11daf](https://bsd-hardware.info/?probe=aea3a11daf) | Jul 08, 2021 |
| Lenovo    | SHARKBAY SDK0E50510 WIN     | [6cf3337855](https://bsd-hardware.info/?probe=6cf3337855) | Jul 01, 2021 |
| ASUSTek   | M5A97 R2.0                  | [e7a0dfcecf](https://bsd-hardware.info/?probe=e7a0dfcecf) | Jun 28, 2021 |
| ASUSTek   | H81M-K                      | [1a35d2f6ab](https://bsd-hardware.info/?probe=1a35d2f6ab) | Jun 26, 2021 |
| ASUSTek   | H110M-E/M.2                 | [b0b67667d3](https://bsd-hardware.info/?probe=b0b67667d3) | Jun 16, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 61       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 61       | 98.39%  |
| GNOME        | 1        | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 61       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 61       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 61       | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 53       | 86.89%  |
| BIOS | 8        | 13.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 61       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 61       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 15       | 24.59%  |
| ASRock              | 8        | 13.11%  |
| Hewlett-Packard     | 7        | 11.48%  |
| Gigabyte Technology | 7        | 11.48%  |
| Dell                | 6        | 9.84%   |
| MSI                 | 4        | 6.56%   |
| Lenovo              | 2        | 3.28%   |
| Intel               | 2        | 3.28%   |
| T-bao               | 1        | 1.64%   |
| Shuttle             | 1        | 1.64%   |
| Sapphire            | 1        | 1.64%   |
| Medion              | 1        | 1.64%   |
| Itautec             | 1        | 1.64%   |
| Gateway             | 1        | 1.64%   |
| Fujitsu             | 1        | 1.64%   |
| Apple               | 1        | 1.64%   |
| Acer                | 1        | 1.64%   |
| Unknown             | 1        | 1.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| T-bao MINI PC                      | 1        | 1.64%   |
| Shuttle SH61R                      | 1        | 1.64%   |
| Sapphire EDGE-FT1M1 E450 1AOVU044  | 1        | 1.64%   |
| MSI MS-7C91                        | 1        | 1.64%   |
| MSI MS-7B93                        | 1        | 1.64%   |
| MSI MS-7A40                        | 1        | 1.64%   |
| MSI MS-7592                        | 1        | 1.64%   |
| Medion H61H2-LM3                   | 1        | 1.64%   |
| Lenovo ThinkCentre M83 10AHS35Q00  | 1        | 1.64%   |
| Lenovo ThinkCentre E73z 10BD004RRU | 1        | 1.64%   |
| Itautec Infoway ST-4344            | 1        | 1.64%   |
| Intel H81                          | 1        | 1.64%   |
| Intel H61                          | 1        | 1.64%   |
| HP [AH877AV] _ Currency Bulk P     | 1        | 1.64%   |
| HP ProLiant ML350 G5               | 1        | 1.64%   |
| HP EliteDesk 800 G2 SFF            | 1        | 1.64%   |
| HP Compaq Elite 8300 USDT          | 1        | 1.64%   |
| HP Compaq Elite 8300 SFF           | 1        | 1.64%   |
| HP Compaq 6000 Pro SFF PC          | 1        | 1.64%   |
| HP 260-p026                        | 1        | 1.64%   |
| Gigabyte H410M S2 V2               | 1        | 1.64%   |
| Gigabyte H270M-DS3H                | 1        | 1.64%   |
| Gigabyte GA-78LMT-USB3             | 1        | 1.64%   |
| Gigabyte G41MT-S2                  | 1        | 1.64%   |
| Gigabyte F2A78M-DS2                | 1        | 1.64%   |
| Gigabyte B450 AORUS M              | 1        | 1.64%   |
| Gigabyte 990FXA-UD3                | 1        | 1.64%   |
| Gateway DX4840                     | 1        | 1.64%   |
| Fujitsu D3220-A1                   | 1        | 1.64%   |
| Dell Studio XPS 9100               | 1        | 1.64%   |
| Dell OptiPlex 9020                 | 1        | 1.64%   |
| Dell OptiPlex 7010                 | 1        | 1.64%   |
| Dell OptiPlex 390                  | 1        | 1.64%   |
| Dell OptiPlex 3040                 | 1        | 1.64%   |
| Dell OptiPlex 3020M                | 1        | 1.64%   |
| ASUS TUF GAMING X570-PLUS          | 1        | 1.64%   |
| ASUS TUF B450M-PRO GAMING          | 1        | 1.64%   |
| ASUS TUF B360M-PLUS GAMING S       | 1        | 1.64%   |
| ASUS ROG STRIX X470-F GAMING       | 1        | 1.64%   |
| ASUS Pro WS X570-ACE               | 1        | 1.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 5        | 8.2%    |
| HP Compaq              | 3        | 4.92%   |
| ASUS TUF               | 3        | 4.92%   |
| Lenovo ThinkCentre     | 2        | 3.28%   |
| T-bao MINI             | 1        | 1.64%   |
| Shuttle SH61R          | 1        | 1.64%   |
| Sapphire EDGE-FT1M1    | 1        | 1.64%   |
| MSI MS-7C91            | 1        | 1.64%   |
| MSI MS-7B93            | 1        | 1.64%   |
| MSI MS-7A40            | 1        | 1.64%   |
| MSI MS-7592            | 1        | 1.64%   |
| Medion H61H2-LM3       | 1        | 1.64%   |
| Itautec Infoway        | 1        | 1.64%   |
| Intel H81              | 1        | 1.64%   |
| Intel H61              | 1        | 1.64%   |
| HP [AH877AV]           | 1        | 1.64%   |
| HP ProLiant            | 1        | 1.64%   |
| HP EliteDesk           | 1        | 1.64%   |
| HP 260-p026            | 1        | 1.64%   |
| Gigabyte H410M         | 1        | 1.64%   |
| Gigabyte H270M-DS3H    | 1        | 1.64%   |
| Gigabyte GA-78LMT-USB3 | 1        | 1.64%   |
| Gigabyte G41MT-S2      | 1        | 1.64%   |
| Gigabyte F2A78M-DS2    | 1        | 1.64%   |
| Gigabyte B450          | 1        | 1.64%   |
| Gigabyte 990FXA-UD3    | 1        | 1.64%   |
| Gateway DX4840         | 1        | 1.64%   |
| Fujitsu D3220-A1       | 1        | 1.64%   |
| Dell Studio            | 1        | 1.64%   |
| ASUS ROG               | 1        | 1.64%   |
| ASUS Pro               | 1        | 1.64%   |
| ASUS P7H55-M           | 1        | 1.64%   |
| ASUS P5P43TD           | 1        | 1.64%   |
| ASUS M5A97             | 1        | 1.64%   |
| ASUS M5A78L-M          | 1        | 1.64%   |
| ASUS M5A78L            | 1        | 1.64%   |
| ASUS H110M-PLUS        | 1        | 1.64%   |
| ASUS H110M-K           | 1        | 1.64%   |
| ASUS exone             | 1        | 1.64%   |
| ASUS CROSSHAIR         | 1        | 1.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 7        | 11.48%  |
| 2021 | 6        | 9.84%   |
| 2019 | 6        | 9.84%   |
| 2010 | 6        | 9.84%   |
| 2020 | 5        | 8.2%    |
| 2018 | 5        | 8.2%    |
| 2012 | 5        | 8.2%    |
| 2016 | 4        | 6.56%   |
| 2011 | 4        | 6.56%   |
| 2017 | 3        | 4.92%   |
| 2015 | 3        | 4.92%   |
| 2014 | 3        | 4.92%   |
| 2009 | 2        | 3.28%   |
| 2007 | 2        | 3.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 61       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 61       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 22       | 36.07%  |
| 8.01-16.0   | 18       | 29.51%  |
| 4.01-8.0    | 9        | 14.75%  |
| 32.01-64.0  | 9        | 14.75%  |
| 64.01-256.0 | 3        | 4.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.51-1.0 | 27       | 44.26%  |
| 0.01-0.5 | 22       | 36.07%  |
| 1.01-2.0 | 10       | 16.39%  |
| 3.01-4.0 | 1        | 1.64%   |
| 2.01-3.0 | 1        | 1.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 27       | 42.86%  |
| 2      | 17       | 26.98%  |
| 3      | 10       | 15.87%  |
| 4      | 8        | 12.7%   |
| 5      | 1        | 1.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 60.66%  |
| Yes       | 24       | 39.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 61       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 65.57%  |
| Yes       | 21       | 34.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 75.41%  |
| Yes       | 15       | 24.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 11       | 18.03%  |
| Russia      | 6        | 9.84%   |
| Germany     | 6        | 9.84%   |
| Poland      | 4        | 6.56%   |
| Brazil      | 4        | 6.56%   |
| Spain       | 3        | 4.92%   |
| Italy       | 3        | 4.92%   |
| Australia   | 3        | 4.92%   |
| Ukraine     | 2        | 3.28%   |
| India       | 2        | 3.28%   |
| China       | 2        | 3.28%   |
| UK          | 1        | 1.64%   |
| Turkey      | 1        | 1.64%   |
| Thailand    | 1        | 1.64%   |
| Taiwan      | 1        | 1.64%   |
| Switzerland | 1        | 1.64%   |
| Netherlands | 1        | 1.64%   |
| Mexico      | 1        | 1.64%   |
| Hungary     | 1        | 1.64%   |
| Hong Kong   | 1        | 1.64%   |
| Guatemala   | 1        | 1.64%   |
| Finland     | 1        | 1.64%   |
| Denmark     | 1        | 1.64%   |
| Chile       | 1        | 1.64%   |
| Canada      | 1        | 1.64%   |
| Bulgaria    | 1        | 1.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Marlborough     | 2        | 3.23%   |
| Hobart          | 2        | 3.23%   |
| Ernakulam       | 2        | 3.23%   |
| Yekaterinburg   | 1        | 1.61%   |
| Xiamen          | 1        | 1.61%   |
| Wolgast         | 1        | 1.61%   |
| Warrenton       | 1        | 1.61%   |
| Voronezh        | 1        | 1.61%   |
| Tula de Allende | 1        | 1.61%   |
| Torre del Mar   | 1        | 1.61%   |
| Tampa           | 1        | 1.61%   |
| Stuttgart       | 1        | 1.61%   |
| Stralsund       | 1        | 1.61%   |
| Sofia           | 1        | 1.61%   |
| Siedlce         | 1        | 1.61%   |
| Shepetivka      | 1        | 1.61%   |
| Santiago        | 1        | 1.61%   |
| RzeszÃ³w      | 1        | 1.61%   |
| Rostov-on-Don   | 1        | 1.61%   |
| Riehen          | 1        | 1.61%   |
| Richmond        | 1        | 1.61%   |
| Reriutaba       | 1        | 1.61%   |
| Qingdao         | 1        | 1.61%   |
| Pistoia         | 1        | 1.61%   |
| Outeiro de Rei  | 1        | 1.61%   |
| Old Town        | 1        | 1.61%   |
| Nieuwegein      | 1        | 1.61%   |
| Newtownabbey    | 1        | 1.61%   |
| Nampa           | 1        | 1.61%   |
| Munich          | 1        | 1.61%   |
| Moscow          | 1        | 1.61%   |
| Manaus          | 1        | 1.61%   |
| Kyiv            | 1        | 1.61%   |
| Kosekoy         | 1        | 1.61%   |
| Kochi           | 1        | 1.61%   |
| Kirkkonummi     | 1        | 1.61%   |
| Katowice        | 1        | 1.61%   |
| Irkutsk         | 1        | 1.61%   |
| Inhapim         | 1        | 1.61%   |
| Independence    | 1        | 1.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 26       | 32     | 25.49%  |
| Seagate             | 18       | 24     | 17.65%  |
| Samsung Electronics | 13       | 18     | 12.75%  |
| Crucial             | 7        | 10     | 6.86%   |
| Hitachi             | 6        | 8      | 5.88%   |
| Toshiba             | 5        | 7      | 4.9%    |
| Kingston            | 4        | 7      | 3.92%   |
| SanDisk             | 3        | 3      | 2.94%   |
| Smartbuy            | 2        | 2      | 1.96%   |
| Intel               | 2        | 2      | 1.96%   |
| China               | 2        | 2      | 1.96%   |
| A-DATA Technology   | 2        | 4      | 1.96%   |
| Verbatim            | 1        | 1      | 0.98%   |
| SPCC                | 1        | 1      | 0.98%   |
| Silicon Motion      | 1        | 1      | 0.98%   |
| PNY                 | 1        | 1      | 0.98%   |
| Plextor             | 1        | 1      | 0.98%   |
| LITEONIT            | 1        | 1      | 0.98%   |
| KingSpec            | 1        | 2      | 0.98%   |
| Hewlett-Packard     | 1        | 1      | 0.98%   |
| GOODRAM             | 1        | 1      | 0.98%   |
| Gigabyte Technology | 1        | 1      | 0.98%   |
| Corsair             | 1        | 1      | 0.98%   |
| Apacer              | 1        | 1      | 0.98%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB          | 3        | 2.48%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 2        | 1.65%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 2        | 1.65%   |
| Toshiba DT01ACA100 1TB             | 2        | 1.65%   |
| Seagate ST3500312CS 500GB          | 2        | 1.65%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 1.65%   |
| SanDisk SDSSDA240G 240GB           | 2        | 1.65%   |
| Samsung SSD 850 EVO 250GB          | 2        | 1.65%   |
| Samsung HD322HJ 320GB              | 2        | 1.65%   |
| China SATA SSD 120GB               | 2        | 1.65%   |
| WDC WDS500G2B0A-00SM50 500GB       | 1        | 0.83%   |
| WDC WDS250G2X0C-00L350 250GB       | 1        | 0.83%   |
| WDC WD800JD-00LSA0 80GB            | 1        | 0.83%   |
| WDC WD5000LPCX-00VHAT0 500GB       | 1        | 0.83%   |
| WDC WD5000AAVS-00ZTB0 500GB        | 1        | 0.83%   |
| WDC WD5000AAKX-08ERMA0 500GB       | 1        | 0.83%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 0.83%   |
| WDC WD5000AAKS-08V0A0 500GB        | 1        | 0.83%   |
| WDC WD5000AAKS-00V1A0 500GB        | 1        | 0.83%   |
| WDC WD40EZRZ-22GXCB0 4TB           | 1        | 0.83%   |
| WDC WD40EFRX-68N32N0 4TB           | 1        | 0.83%   |
| WDC WD3200AAKS-00UU3A0 320GB       | 1        | 0.83%   |
| WDC WD30EZRZ-00WN9B0 3TB           | 1        | 0.83%   |
| WDC WD3003FZEX-00Z4SA0 3TB         | 1        | 0.83%   |
| WDC WD2500JD-75HBB0 250GB          | 1        | 0.83%   |
| WDC WD2500BEVS-22UST0 250GB        | 1        | 0.83%   |
| WDC WD20SMZW-11YFCS0 2TB           | 1        | 0.83%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1        | 0.83%   |
| WDC WD1600AAJS-00WAA0 160GB        | 1        | 0.83%   |
| WDC WD1600AAJS-00V4A0 160GB        | 1        | 0.83%   |
| WDC WD10SPZX-22Z10T0 1TB           | 1        | 0.83%   |
| WDC WD10JMVW-11AJGS0 1TB           | 1        | 0.83%   |
| WDC WD10EZRX-00A8LB0 1TB           | 1        | 0.83%   |
| WDC WD10EZEX-75WN4A1 1TB           | 1        | 0.83%   |
| WDC WD10EFRX-68FYTN0 1TB           | 1        | 0.83%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 1        | 0.83%   |
| WDC WD1001FAES-75W7A0 1TB          | 1        | 0.83%   |
| Verbatim Vi550 S3 SSD 128GB        | 1        | 0.83%   |
| Toshiba MQ01UBD100 1TB             | 1        | 0.83%   |
| Toshiba MQ01ABD032 320GB           | 1        | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 28     | 40.35%  |
| Seagate             | 18       | 24     | 31.58%  |
| Hitachi             | 6        | 8      | 10.53%  |
| Toshiba             | 5        | 7      | 8.77%   |
| Samsung Electronics | 4        | 6      | 7.02%   |
| Hewlett-Packard     | 1        | 1      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 8      | 20%     |
| Crucial             | 7        | 10     | 20%     |
| Kingston            | 4        | 7      | 11.43%  |
| SanDisk             | 3        | 3      | 8.57%   |
| Smartbuy            | 2        | 2      | 5.71%   |
| China               | 2        | 2      | 5.71%   |
| WDC                 | 1        | 1      | 2.86%   |
| Verbatim            | 1        | 1      | 2.86%   |
| PNY                 | 1        | 1      | 2.86%   |
| Plextor             | 1        | 1      | 2.86%   |
| LITEONIT            | 1        | 1      | 2.86%   |
| KingSpec            | 1        | 2      | 2.86%   |
| Intel               | 1        | 1      | 2.86%   |
| GOODRAM             | 1        | 1      | 2.86%   |
| Apacer              | 1        | 1      | 2.86%   |
| A-DATA Technology   | 1        | 2      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 41       | 74     | 49.4%   |
| SSD  | 30       | 44     | 36.14%  |
| NVMe | 12       | 14     | 14.46%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 55       | 118    | 82.09%  |
| NVMe | 12       | 14     | 17.91%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 47       | 74     | 55.95%  |
| 0.51-1.0   | 23       | 27     | 27.38%  |
| 1.01-2.0   | 6        | 7      | 7.14%   |
| 2.01-3.0   | 4        | 6      | 4.76%   |
| 3.01-4.0   | 3        | 3      | 3.57%   |
| 4.01-10.0  | 1        | 1      | 1.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 39       | 63.93%  |
| 101-250    | 13       | 21.31%  |
| 251-500    | 6        | 9.84%   |
| 21-50      | 1        | 1.64%   |
| 501-1000   | 1        | 1.64%   |
| 51-100     | 1        | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 61       | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Samsung Electronics HD322HJ 320GB   | 2        | 2      | 10%     |
| WDC WD5000AAKX-08ERMA0 500GB        | 1        | 1      | 5%      |
| WDC WD5000AAKX-00ERMA0 500GB        | 1        | 1      | 5%      |
| WDC WD5000AAKS-08V0A0 500GB         | 1        | 1      | 5%      |
| WDC WD5000AAKS-00V1A0 500GB         | 1        | 1      | 5%      |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1        | 1      | 5%      |
| WDC WD3200AAKS-00UU3A0 320GB        | 1        | 1      | 5%      |
| WDC WD10JMVW-11AJGS0 1TB            | 1        | 1      | 5%      |
| Toshiba MQ01UBD100 1TB              | 1        | 1      | 5%      |
| Toshiba DT01ACA100 1TB              | 1        | 2      | 5%      |
| Seagate ST9320325AS 320GB           | 1        | 1      | 5%      |
| Seagate ST750LM022 HN-M750MBB 752GB | 1        | 1      | 5%      |
| Seagate ST500LT012-9WS142 500GB     | 1        | 1      | 5%      |
| Seagate ST500LT012-1DG142 500GB     | 1        | 1      | 5%      |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 5%      |
| Seagate ST3500413AS 500GB           | 1        | 1      | 5%      |
| SanDisk SDSSDA240G 240GB            | 1        | 1      | 5%      |
| Samsung Electronics HD161HJ 160GB   | 1        | 1      | 5%      |
| Hitachi HTS722020K9SA00 200GB       | 1        | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 7      | 38.89%  |
| Seagate             | 5        | 6      | 27.78%  |
| Toshiba             | 2        | 3      | 11.11%  |
| Samsung Electronics | 2        | 3      | 11.11%  |
| SanDisk             | 1        | 1      | 5.56%   |
| Hitachi             | 1        | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 7      | 41.18%  |
| Seagate             | 5        | 6      | 29.41%  |
| Toshiba             | 2        | 3      | 11.76%  |
| Samsung Electronics | 2        | 3      | 11.76%  |
| Hitachi             | 1        | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 20     | 94.12%  |
| SSD  | 1        | 1      | 5.88%   |

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
| Works    | 54       | 109    | 73.97%  |
| Malfunc  | 17       | 21     | 23.29%  |
| Detected | 2        | 2      | 2.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 38       | 48.72%  |
| AMD                        | 23       | 29.49%  |
| SanDisk                    | 3        | 3.85%   |
| Samsung Electronics        | 3        | 3.85%   |
| Phison Electronics         | 3        | 3.85%   |
| ASMedia Technology         | 3        | 3.85%   |
| Silicon Motion             | 1        | 1.28%   |
| Lite-On IT Corp. / Plextor | 1        | 1.28%   |
| JMicron Technology         | 1        | 1.28%   |
| Hewlett-Packard            | 1        | 1.28%   |
| ADATA Technology           | 1        | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 13.83%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 6.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 5.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 5.32%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 5.32%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 4.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 4.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 3.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 3.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 3.19%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 3        | 3.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 3.19%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 2        | 2.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 2.13%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 2.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 2.13%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 1.06%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 1        | 1.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.06%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 1        | 1.06%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.06%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.06%   |
| Lite-On IT Corp. / Plextor M6e PCI Express SSD [Marvell 88SS9183]                       | 1        | 1.06%   |
| JMicron JMB361 AHCI/IDE                                                                 | 1        | 1.06%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                        | 1        | 1.06%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.06%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.06%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.06%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 1.06%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 1.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.06%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 1.06%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 1.06%   |
| HP Smart Array E200i (SAS Controller)                                                   | 1        | 1.06%   |
| HP Smart Array Controller                                                               | 1        | 1.06%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 48       | 64.86%  |
| IDE  | 13       | 17.57%  |
| NVMe | 12       | 16.22%  |
| RAID | 1        | 1.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 37       | 60.66%  |
| AMD    | 24       | 39.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 4.92%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 3.28%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 3.28%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 2        | 3.28%   |
| Intel Core i3-6100T CPU @ 3.20GHz           | 2        | 3.28%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 3.28%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 3.28%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 3.28%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 1.64%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 1.64%   |
| Intel Xeon                                  | 1        | 1.64%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 1.64%   |
| Intel Genuine CPU 2160 @ 1.80GHz            | 1        | 1.64%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 1.64%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.64%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 1.64%   |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1        | 1.64%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.64%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.64%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.64%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.64%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.64%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.64%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 1.64%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 1.64%   |
| Intel Core i5 CPU 661 @ 3.33GHz             | 1        | 1.64%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 1.64%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 1        | 1.64%   |
| Intel Core i3-4150T CPU @ 3.00GHz           | 1        | 1.64%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.64%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 1        | 1.64%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 1.64%   |
| Intel Core i3-2120 CPU @ 3.30GH             | 1        | 1.64%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1.64%   |
| Intel Core 2 Duo CPU                        | 1        | 1.64%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 1        | 1.64%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 1        | 1.64%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 1.64%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 1.64%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 1        | 1.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 11       | 18.03%  |
| Intel Core i3           | 9        | 14.75%  |
| Intel Core i7           | 8        | 13.11%  |
| AMD Ryzen 5             | 5        | 8.2%    |
| AMD FX                  | 5        | 8.2%    |
| AMD Ryzen 7             | 4        | 6.56%   |
| Intel Xeon              | 3        | 4.92%   |
| AMD Ryzen 9             | 3        | 4.92%   |
| Intel Core 2 Quad       | 2        | 3.28%   |
| Intel Core 2 Duo        | 2        | 3.28%   |
| AMD Ryzen 3             | 2        | 3.28%   |
| Intel Pentium Dual-Core | 1        | 1.64%   |
| Intel Genuine           | 1        | 1.64%   |
| AMD Ryzen 5 PRO         | 1        | 1.64%   |
| AMD Phenom II X6        | 1        | 1.64%   |
| AMD Phenom II X4        | 1        | 1.64%   |
| AMD E                   | 1        | 1.64%   |
| AMD A4                  | 1        | 1.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 21       | 34.43%  |
| 2       | 14       | 22.95%  |
| 12      | 6        | 9.84%   |
| 8       | 6        | 9.84%   |
| 6       | 6        | 9.84%   |
| 16      | 4        | 6.56%   |
| 24      | 3        | 4.92%   |
| Unknown | 1        | 1.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 59       | 96.72%  |
| 2      | 2        | 3.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 42       | 68.85%  |
| 2       | 18       | 29.51%  |
| Unknown | 1        | 1.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 7        | 11.48%  |
| Haswell     | 7        | 11.48%  |
| Zen 2       | 6        | 9.84%   |
| Penryn      | 6        | 9.84%   |
| Zen         | 5        | 8.2%    |
| SandyBridge | 5        | 8.2%    |
| Piledriver  | 5        | 8.2%    |
| Zen+        | 3        | 4.92%   |
| Skylake     | 3        | 4.92%   |
| IvyBridge   | 3        | 4.92%   |
| Westmere    | 2        | 3.28%   |
| Nehalem     | 2        | 3.28%   |
| K10         | 2        | 3.28%   |
| Zen 3       | 1        | 1.64%   |
| Core        | 1        | 1.64%   |
| CometLake   | 1        | 1.64%   |
| Bulldozer   | 1        | 1.64%   |
| Bobcat      | 1        | 1.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 26       | 40%     |
| AMD    | 21       | 32.31%  |
| Intel  | 18       | 27.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 7.69%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 6.15%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 6.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 4.62%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 4.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 4.62%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 3.08%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 3.08%   |
| Intel HD Graphics 630                                                       | 2        | 3.08%   |
| Intel HD Graphics 530                                                       | 2        | 3.08%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 3.08%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 3.08%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.54%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.54%   |
| Nvidia GT215 [GeForce GT 220]                                               | 1        | 1.54%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 1        | 1.54%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.54%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.54%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.54%   |
| Nvidia GP104 [GeForce GTX 1060 3GB]                                         | 1        | 1.54%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.54%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 1.54%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 1.54%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 1.54%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.54%   |
| Nvidia G92 [GeForce GT 330]                                                 | 1        | 1.54%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.54%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.54%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.54%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 1.54%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.54%   |
| AMD Wrestler [Radeon HD 6320]                                               | 1        | 1.54%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.54%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 1.54%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 1.54%   |
| AMD Richland [Radeon HD 8470D]                                              | 1        | 1.54%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 1        | 1.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.54%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 1.54%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1        | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 24       | 38.71%  |
| 1 x AMD        | 20       | 32.26%  |
| 1 x Intel      | 14       | 22.58%  |
| Intel + Nvidia | 2        | 3.23%   |
| 2 x Intel      | 1        | 1.61%   |
| Intel + AMD    | 1        | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 48       | 78.69%  |
| Proprietary | 12       | 19.67%  |
| Unknown     | 1        | 1.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 54.1%   |
| 1.01-2.0   | 8        | 13.11%  |
| 3.01-4.0   | 6        | 9.84%   |
| 0.01-0.5   | 5        | 8.2%    |
| 7.01-8.0   | 3        | 4.92%   |
| 5.01-6.0   | 3        | 4.92%   |
| 0.51-1.0   | 3        | 4.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 5        | 13.16%  |
| Hewlett-Packard      | 4        | 10.53%  |
| Dell                 | 4        | 10.53%  |
| Iiyama               | 3        | 7.89%   |
| Goldstar             | 3        | 7.89%   |
| Philips              | 2        | 5.26%   |
| Lenovo               | 2        | 5.26%   |
| BenQ                 | 2        | 5.26%   |
| Ancor Communications | 2        | 5.26%   |
| Acer                 | 2        | 5.26%   |
| Vizio                | 1        | 2.63%   |
| ViewSonic            | 1        | 2.63%   |
| SGT                  | 1        | 2.63%   |
| Medion               | 1        | 2.63%   |
| Haier                | 1        | 2.63%   |
| Eizo                 | 1        | 2.63%   |
| ASUSTek Computer     | 1        | 2.63%   |
| AOC                  | 1        | 2.63%   |
| ALP                  | 1        | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch              | 2        | 5.13%   |
| Vizio LCD Monitor VIZ0022 1920x540 480x270mm 21.7-inch               | 1        | 2.56%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch           | 1        | 2.56%   |
| SGT YSD SGT1700 1280x1024 380x210mm 17.1-inch                        | 1        | 2.56%   |
| Samsung Electronics T22D390 SAM0B69 1920x1080 480x270mm 21.7-inch    | 1        | 2.56%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                     | 1        | 2.56%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                     | 1        | 2.56%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 520x320mm 24.0-inch  | 1        | 2.56%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch | 1        | 2.56%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 1        | 2.56%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch               | 1        | 2.56%   |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                  | 1        | 2.56%   |
| Lenovo LEN-M73Z-D LEN00A0 1600x900 440x240mm 19.7-inch               | 1        | 2.56%   |
| Lenovo LEN-E73Z-D LEN00A1 1600x900 440x240mm 19.7-inch               | 1        | 2.56%   |
| Iiyama PL2409HD IVM560C 1920x1080 520x290mm 23.4-inch                | 1        | 2.56%   |
| Hewlett-Packard ZR22w HWP2867 1920x1080 480x270mm 21.7-inch          | 1        | 2.56%   |
| Hewlett-Packard E243m HPN3465 1920x1080 530x300mm 24.0-inch          | 1        | 2.56%   |
| Hewlett-Packard 2310 HWP288F 1920x1080 510x290mm 23.1-inch           | 1        | 2.56%   |
| Hewlett-Packard 19ka HWP3328 1366x768 410x230mm 18.5-inch            | 1        | 2.56%   |
| Haier HT-20216B(C) HAI2031 1920x1080 480x270mm 21.7-inch             | 1        | 2.56%   |
| Goldstar L1553S GSM3BB0 1024x768 300x230mm 14.9-inch                 | 1        | 2.56%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 1        | 2.56%   |
| Goldstar D2342P GSM5840 1920x1080 510x290mm 23.1-inch                | 1        | 2.56%   |
| Eizo EV2316W ENC2394 1920x1080 510x290mm 23.1-inch                   | 1        | 2.56%   |
| Dell ST2321L DELF033 1920x1080 510x290mm 23.1-inch                   | 1        | 2.56%   |
| Dell ST2321L DELF031 1920x1080 510x290mm 23.1-inch                   | 1        | 2.56%   |
| Dell S2418HN/NX DEL4123 1920x1080 530x300mm 24.0-inch                | 1        | 2.56%   |
| Dell E228WFP DELD014 1680x1050 470x300mm 22.0-inch                   | 1        | 2.56%   |
| Dell 1708FP DEL4024 1280x1024 340x270mm 17.1-inch                    | 1        | 2.56%   |
| BenQ LCD Monitor BNQ7725 1920x1080 480x270mm 21.7-inch               | 1        | 2.56%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                    | 1        | 2.56%   |
| ASUSTek Computer VP247 AUS24CA 1920x1080 520x290mm 23.4-inch         | 1        | 2.56%   |
| AOC LE19W037 AOC1907 1360x768 410x230mm 18.5-inch                    | 1        | 2.56%   |
| Ancor Communications MW221 ACI22B1 1680x1050 470x300mm 22.0-inch     | 1        | 2.56%   |
| Ancor Communications BE24A ACI24AB 1920x1200 520x320mm 24.0-inch     | 1        | 2.56%   |
| ALP 2476 IPS ALP2476 1920x1080 530x300mm 24.0-inch                   | 1        | 2.56%   |
| Acer ET430K ACR0558 3840x2160 940x530mm 42.5-inch                    | 1        | 2.56%   |
| Acer B223W ACR0018 1680x1050 470x300mm 22.0-inch                     | 1        | 2.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 19       | 50%     |
| 1366x768 (WXGA)    | 4        | 10.53%  |
| 1680x1050 (WSXGA+) | 3        | 7.89%   |
| 1920x1200 (WUXGA)  | 2        | 5.26%   |
| 1600x900 (HD+)     | 2        | 5.26%   |
| 1280x1024 (SXGA)   | 2        | 5.26%   |
| 1024x768 (XGA)     | 2        | 5.26%   |
| 3840x2160 (4K)     | 1        | 2.63%   |
| 2560x1440 (QHD)    | 1        | 2.63%   |
| 1920x540           | 1        | 2.63%   |
| 1360x768           | 1        | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 9        | 23.68%  |
| 24      | 6        | 15.79%  |
| 21      | 5        | 13.16%  |
| 18      | 5        | 13.16%  |
| 22      | 3        | 7.89%   |
| 19      | 2        | 5.26%   |
| 17      | 2        | 5.26%   |
| 14      | 2        | 5.26%   |
| Unknown | 2        | 5.26%   |
| 42      | 1        | 2.63%   |
| 27      | 1        | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 16       | 42.11%  |
| 401-500     | 15       | 39.47%  |
| 201-300     | 2        | 5.26%   |
| Unknown     | 2        | 5.26%   |
| 351-400     | 1        | 2.63%   |
| 301-350     | 1        | 2.63%   |
| 901-1000    | 1        | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 30       | 78.95%  |
| 16/10 | 5        | 13.16%  |
| 4/3   | 2        | 5.26%   |
| 5/4   | 1        | 2.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 21       | 55.26%  |
| 141-150        | 6        | 15.79%  |
| 251-300        | 2        | 5.26%   |
| 151-200        | 2        | 5.26%   |
| 101-110        | 2        | 5.26%   |
| Unknown        | 2        | 5.26%   |
| 301-350        | 1        | 2.63%   |
| 121-130        | 1        | 2.63%   |
| 501-1000       | 1        | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 30       | 78.95%  |
| 101-120 | 6        | 15.79%  |
| Unknown | 2        | 5.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 35       | 56.45%  |
| 0     | 25       | 40.32%  |
| 2     | 2        | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 37       | 44.58%  |
| Intel                    | 24       | 28.92%  |
| Broadcom                 | 7        | 8.43%   |
| Qualcomm Atheros         | 5        | 6.02%   |
| Ralink Technology        | 3        | 3.61%   |
| TP-Link                  | 1        | 1.2%    |
| Ralink                   | 1        | 1.2%    |
| Marvell Technology Group | 1        | 1.2%    |
| IMC Networks             | 1        | 1.2%    |
| Belkin Components        | 1        | 1.2%    |
| ASUSTek Computer         | 1        | 1.2%    |
| Aquantia                 | 1        | 1.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 31       | 34.83%  |
| Intel I211 Gigabit Network Connection                                          | 6        | 6.74%   |
| Intel Ethernet Connection (7) I219-V                                           | 3        | 3.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3        | 3.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 2        | 2.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 2.25%   |
| Ralink MT7601U Wireless Adapter                                                | 2        | 2.25%   |
| Intel Ethernet Connection I217-V                                               | 2        | 2.25%   |
| Intel Ethernet Connection I217-LM                                              | 2        | 2.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2        | 2.25%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 2        | 2.25%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                            | 1        | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1        | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1        | 1.12%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1        | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1        | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1        | 1.12%   |
| Ralink RT3072 Wireless Adapter                                                 | 1        | 1.12%   |
| Ralink RT2561/RT61 rev B 802.11g                                               | 1        | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1        | 1.12%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1        | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1        | 1.12%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1        | 1.12%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 1.12%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 1.12%   |
| Intel Wireless 7265                                                            | 1        | 1.12%   |
| Intel Wi-Fi 6 AX200                                                            | 1        | 1.12%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 1.12%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 1.12%   |
| Intel Centrino Wireless-N 105                                                  | 1        | 1.12%   |
| Intel 82583V Gigabit Network Connection                                        | 1        | 1.12%   |
| Intel 82574L Gigabit Network Connection                                        | 1        | 1.12%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1        | 1.12%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter    | 1        | 1.12%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                 | 1        | 1.12%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 1        | 1.12%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                  | 1        | 1.12%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                   | 1        | 1.12%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                         | 1        | 1.12%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 5        | 20%     |
| Intel                 | 5        | 20%     |
| Broadcom              | 4        | 16%     |
| Ralink Technology     | 3        | 12%     |
| Qualcomm Atheros      | 3        | 12%     |
| TP-Link               | 1        | 4%      |
| Ralink                | 1        | 4%      |
| IMC Networks          | 1        | 4%      |
| Belkin Components     | 1        | 4%      |
| ASUSTek Computer      | 1        | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 2        | 7.69%   |
| Ralink MT7601U Wireless Adapter                                             | 2        | 7.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 2        | 7.69%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                | 2        | 7.69%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                         | 1        | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1        | 3.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1        | 3.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                       | 1        | 3.85%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1        | 3.85%   |
| Ralink RT3072 Wireless Adapter                                              | 1        | 3.85%   |
| Ralink RT2561/RT61 rev B 802.11g                                            | 1        | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1        | 3.85%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 1        | 3.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1        | 3.85%   |
| Intel Wireless 7265                                                         | 1        | 3.85%   |
| Intel Wi-Fi 6 AX200                                                         | 1        | 3.85%   |
| Intel Centrino Wireless-N 105                                               | 1        | 3.85%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1        | 3.85%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                | 1        | 3.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 1        | 3.85%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B]          | 1        | 3.85%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 34       | 53.97%  |
| Intel                    | 22       | 34.92%  |
| Broadcom                 | 3        | 4.76%   |
| Qualcomm Atheros         | 2        | 3.17%   |
| Marvell Technology Group | 1        | 1.59%   |
| Aquantia                 | 1        | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 31       | 49.21%  |
| Intel I211 Gigabit Network Connection                                          | 6        | 9.52%   |
| Intel Ethernet Connection (7) I219-V                                           | 3        | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3        | 4.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 3.17%   |
| Intel Ethernet Connection I217-V                                               | 2        | 3.17%   |
| Intel Ethernet Connection I217-LM                                              | 2        | 3.17%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1        | 1.59%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1        | 1.59%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 1.59%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 1.59%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 1.59%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 1.59%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 1.59%   |
| Intel 82583V Gigabit Network Connection                                        | 1        | 1.59%   |
| Intel 82574L Gigabit Network Connection                                        | 1        | 1.59%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1        | 1.59%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                 | 1        | 1.59%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 1        | 1.59%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                  | 1        | 1.59%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1        | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 61       | 74.39%  |
| WiFi     | 21       | 25.61%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 60       | 80%     |
| WiFi     | 15       | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 43       | 70.49%  |
| 2     | 16       | 26.23%  |
| 3     | 2        | 3.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 60       | 96.77%  |
| Yes  | 2        | 3.23%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 26.67%  |
| Cambridge Silicon Radio | 3        | 20%     |
| Apple                   | 3        | 20%     |
| Realtek Semiconductor   | 2        | 13.33%  |
| Foxconn / Hon Hai       | 1        | 6.67%   |
| Broadcom                | 1        | 6.67%   |
| ASUSTek Computer        | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 20%     |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 13.33%  |
| Apple Bluetooth Host Controller                     | 2        | 13.33%  |
| Realtek Bluetooth Adapter                           | 1        | 6.67%   |
| Realtek Bluetooth 4.0 Adapter                       | 1        | 6.67%   |
| Intel Bluetooth wireless interface                  | 1        | 6.67%   |
| Intel AX200 Bluetooth                               | 1        | 6.67%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1        | 6.67%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 6.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 6.67%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 34       | 33.66%  |
| AMD                     | 30       | 29.7%   |
| Nvidia                  | 23       | 22.77%  |
| C-Media Electronics     | 5        | 4.95%   |
| Texas Instruments       | 2        | 1.98%   |
| Logitech                | 2        | 1.98%   |
| Creative Labs           | 2        | 1.98%   |
| Plantronics             | 1        | 0.99%   |
| Hewlett-Packard         | 1        | 0.99%   |
| BEHRINGER International | 1        | 0.99%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 6.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7        | 5.88%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 5.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 5.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 4.2%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 4.2%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 3.36%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 3.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 3.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 3.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 3.36%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 3.36%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 2.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 2.52%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 2.52%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 3        | 2.52%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 1.68%   |
| Nvidia High Definition Audio Controller                                    | 2        | 1.68%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.68%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 1.68%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.68%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.68%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 1.68%   |
| C-Media Electronics CM108 Audio Controller                                 | 2        | 1.68%   |
| Plantronics Plantronics Blackwire 325.1                                    | 1        | 0.84%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.84%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.84%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.84%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.84%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.84%   |
| Logitech HD Webcam C910                                                    | 1        | 0.84%   |
| Logitech HD Webcam C510                                                    | 1        | 0.84%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 0.84%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 0.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 0.84%   |
| Hewlett-Packard E243m                                                      | 1        | 0.84%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1        | 0.84%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                     | 1        | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 13       | 18.31%  |
| Samsung Electronics | 10       | 14.08%  |
| Crucial             | 9        | 12.68%  |
| Unknown             | 8        | 11.27%  |
| SK hynix            | 4        | 5.63%   |
| G.Skill             | 4        | 5.63%   |
| Corsair             | 4        | 5.63%   |
| Team                | 3        | 4.23%   |
| Nanya Technology    | 3        | 4.23%   |
| Unknown             | 3        | 4.23%   |
| Transcend           | 2        | 2.82%   |
| Ramaxel Technology  | 2        | 2.82%   |
| Micron Technology   | 2        | 2.82%   |
| A-DATA Technology   | 2        | 2.82%   |
| Patriot             | 1        | 1.41%   |
| Hikvision           | 1        | 1.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown                                                 | 3        | 4.11%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s      | 2        | 2.74%   |
| SK hynix RAM HMT451S6BCFR8A-PB 4GB DIMM DDR3 1600MT/s   | 2        | 2.74%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s     | 2        | 2.74%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s   | 2        | 2.74%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s    | 2        | 2.74%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 1        | 1.37%   |
| Unknown RAM Module 4GB FB-DIMM DDR2 667MT/s             | 1        | 1.37%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                | 1        | 1.37%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                | 1        | 1.37%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 1        | 1.37%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                    | 1        | 1.37%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 1.37%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 1        | 1.37%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 1.37%   |
| Transcend RAM JM1333KSN-4G 4GB DIMM DDR3 1333MT/s       | 1        | 1.37%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2667MT/s     | 1        | 1.37%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.37%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.37%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s               | 1        | 1.37%   |
| Samsung RAM Module 2GB DIMM DDR3 400MT/s                | 1        | 1.37%   |
| Samsung RAM Module 16GB DIMM DDR3 1333MT/s              | 1        | 1.37%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s   | 1        | 1.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 1        | 1.37%   |
| Samsung RAM M393B1K70DH0 8GB DIMM DDR3 1600MT/s         | 1        | 1.37%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.37%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s     | 1        | 1.37%   |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s   | 1        | 1.37%   |
| Patriot RAM Module 2GB DIMM DDR2 533MT/s                | 1        | 1.37%   |
| Nanya RAM NT4GC72B8PB0NF-CG 4GB DIMM DDR3 1333MT/s      | 1        | 1.37%   |
| Nanya RAM M2F4G64CC88D7N-DI 4GB DIMM DDR3 1600MT/s      | 1        | 1.37%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4GB DIMM DDR3 1333MT/s      | 1        | 1.37%   |
| Nanya RAM M2F2G64CB88G7N-CG 2GB DIMM DDR3 1333MT/s      | 1        | 1.37%   |
| Micron RAM 4ATF51264HZ-2G6B1 4GB SODIMM DDR4 1200MT/s   | 1        | 1.37%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s   | 1        | 1.37%   |
| Kingston RAM KHX3466C19D4/16G 16GB DIMM DDR4 3200MT/s   | 1        | 1.37%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s    | 1        | 1.37%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2933MT/s       | 1        | 1.37%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s       | 1        | 1.37%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2400MT/s | 1        | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 26       | 42.62%  |
| DDR3    | 26       | 42.62%  |
| Unknown | 5        | 8.2%    |
| DDR2    | 2        | 3.28%   |
| SDRAM   | 1        | 1.64%   |
| DDR     | 1        | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 55       | 90.16%  |
| SODIMM  | 5        | 8.2%    |
| FB-DIMM | 1        | 1.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 24       | 35.29%  |
| 8192  | 21       | 30.88%  |
| 2048  | 10       | 14.71%  |
| 16384 | 9        | 13.24%  |
| 32768 | 3        | 4.41%   |
| 1024  | 1        | 1.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 16       | 24.62%  |
| 1333  | 15       | 23.08%  |
| 2400  | 6        | 9.23%   |
| 3200  | 5        | 7.69%   |
| 2667  | 5        | 7.69%   |
| 2133  | 5        | 7.69%   |
| 2666  | 3        | 4.62%   |
| 400   | 2        | 3.08%   |
| 3000  | 1        | 1.54%   |
| 2933  | 1        | 1.54%   |
| 1866  | 1        | 1.54%   |
| 1200  | 1        | 1.54%   |
| 1066  | 1        | 1.54%   |
| 800   | 1        | 1.54%   |
| 667   | 1        | 1.54%   |
| 533   | 1        | 1.54%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 2        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Brother HL-L2310D series | 1        | 50%     |
| Brother DCP-J100         | 1        | 50%     |

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
| Z-Star Microelectronics | 2        | 28.57%  |
| IMC Networks            | 2        | 28.57%  |
| Logitech                | 1        | 14.29%  |
| Hewlett-Packard         | 1        | 14.29%  |
| Chicony Electronics     | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| IMC Networks XHC Camera           | 2        | 28.57%  |
| Z-Star Integrated Camera          | 1        | 14.29%  |
| Z-Star A4 TECH USB2.0 PC Camera J | 1        | 14.29%  |
| Logitech Webcam C270              | 1        | 14.29%  |
| HP Premium Starter Webcam         | 1        | 14.29%  |
| Chicony HP Display Camera         | 1        | 14.29%  |

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
| 1     | 28       | 45.9%   |
| 0     | 23       | 37.7%   |
| 2     | 9        | 14.75%  |
| 3     | 1        | 1.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 27       | 58.7%   |
| Net/wireless             | 9        | 19.57%  |
| Sound                    | 3        | 6.52%   |
| Firewire controller      | 3        | 6.52%   |
| Net/ethernet             | 2        | 4.35%   |
| Network                  | 1        | 2.17%   |
| Card reader              | 1        | 2.17%   |

